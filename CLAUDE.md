# CLAUDE.md — antd-skills

An Agent Skills pack providing AI coding assistants with Ant Design component
library guidance across 4 platforms. Part of the Full Stack Skills ecosystem.

## Skills

| Skill | Target | Version | Component Files |
|---|---|---|---|
| `ant-design-react` | React (Web) | 4.x | 10 components |
| `ant-design-vue` | Vue 3 | 4.x | 7 category groups (~70 components) |
| `ant-design-mobile` | React (Mobile) | latest | 51 components |
| `ant-design-mini` | Mini Program (Alipay/WeChat) | latest | 22 components |

## Directory Structure

```
skills/<skill-name>/
  SKILL.md              # Entry point with YAML frontmatter (name, description, license)
  LICENSE.txt           # Apache 2.0
  api/                  # API reference docs (components.md, config-provider.md, etc.)
  examples/
    getting-started/    # Installation and basic usage
    components/         # Per-component or per-category usage examples
    advanced/           # Theme, i18n, advanced patterns
  templates/            # Reusable code scaffolds (component-template.md, project-setup.md)
```

Other key files at repo root: `AGENTS.md` (authoring guide), `AGENTS_EN.md`,
`README.md`, `README.zh-CN.md`, `.claude-plugin/plugin.json`.

## Plugin Registration

`.claude-plugin/plugin.json` declares the skill pack for Claude Code discovery.
Each skill path is listed under `skills[]`. Add new skills there when created.

## SKILL.md Authoring Conventions

- **Frontmatter**: `name`, `description` (include trigger phrases), `license`
- **Sections**: When to Use → Usage Instructions → Documentation Map → Examples
  and Templates → API Reference → Best Practices → Resources → Keywords
- **Description field**: Acts as the AI agent trigger — include phrases like
  "Use when the user asks about Ant Design React components"
- **Keep SKILL.md under 500 lines** — offload reference content to `examples/`
  and `api/` directories; the agent reads them on demand.
- **No scripts**: All workload is static Markdown consumed as context by agents.

## Example/API File Conventions

- Filenames: lowercase kebab-case (`button.md`, `data-entry.md`)
- Structure: official doc link → key concepts → code examples (5-7 per file) → takeaways
- Code blocks use the target framework syntax (JSX, Vue SFC, AXML/WXML)
- Vue examples use `<script setup lang="ts">` and `a-` prefixed components

## Creating a New Skill

1. Create `skills/<skill-name>/` with `SKILL.md` + `LICENSE.txt`
2. Add `api/`, `examples/`, `templates/` subdirectories as needed
3. Register in `.claude-plugin/plugin.json` under `skills[]`
4. Update `README.md` and `README.zh-CN.md` skill tables

Refer to `AGENTS.md` for the full authoring guide.
