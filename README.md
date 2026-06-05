<div align="center">

# antd-skills

**Ant Design component library skills — Vue, React, Mobile, Mini**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Fantd-skills-green.svg)](https://github.com/full-statck-skills/antd-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) ·
[Install](#-install) ·
[Skills](#-skills) ·
[Supported Agents](#-supported-agents) ·
[Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**Ant Design Skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **4 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-statck-skills/antd-skills
```

Or install specific skills:

```bash
npx skills add full-statck-skills/antd-skills --skill <skill-name>
```

## 🎯 Skills (4)

| Skill | Description |
|-------|-------------|
| `ant-design-mini` | Provides comprehensive guidance for Ant Design Mini component library for mini-programs including components, themes,... |
| `ant-design-mobile` | Provides comprehensive guidance for Ant Design Mobile component library including mobile components, themes, and plat... |
| `ant-design-react` | Provides comprehensive guidance for Ant Design React component library including components, design system, themes, a... |
| `ant-design-vue` | Provides comprehensive guidance for Ant Design Vue (AntDV) component library for Vue 3. Covers installation, usage, A... |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-statck-skills/antd-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-statck-skills/antd-skills.git
cp -r antd-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
