---
name: ant-design-vue
description: Provides comprehensive guidance for Ant Design Vue (AntDV) component library for Vue 3. Covers installation, usage, API reference, templates, and all component categories. Use when building enterprise-class UI with Vue 3 and Ant Design.
license: Complete terms in LICENSE.txt
---

## When to use this skill

**ALWAYS use this skill when the user mentions:**
- "Ant Design Vue", "AntDV", "Ant Design of Vue"
- Building Vue 3 applications with Ant Design
- Using UI components like Button, Table, Form, Modal, Menu in a Vue context
- "Ant Design Vue 4.x", "AntDV 4"
- Requests to "implement a [component] with Ant Design Vue"
- Requests for Ant Design Vue API or configuration

## How to use this skill

This skill is organized to match the Ant Design Vue official documentation structure.

### 1. Identify the User's Need

- **Getting Started/Setup** → `examples/getting-started/installation.md` or `templates/project-setup.md`
- **Component Usage** → See Component Categories below
- **API Reference** → `api/components.md` or `api/config-provider.md`
- **Theme/i18n** → `examples/advanced/`
- **Templates** → `templates/component-template.md`

### 2. Component Categories (One-to-One Mapping)

**通用 (General)**
- **Contains**: Button, Icon, Typography
- **File**: `examples/components/general.md`

**布局 (Layout)**
- **Contains**: Divider, Grid, Layout, Space
- **File**: `examples/components/layout.md`

**导航 (Navigation)**
- **Contains**: Anchor, Breadcrumb, Dropdown, Menu, Pagination, Steps
- **File**: `examples/components/navigation.md`

**数据录入 (Data Entry)**
- **Contains**: AutoComplete, Cascader, Checkbox, DatePicker, Form, Input, InputNumber, Mentions, Radio, Rate, Select, Slider, Switch, TimePicker, Transfer, TreeSelect, Upload
- **File**: `examples/components/data-entry.md`

**数据展示 (Data Display)**
- **Contains**: Avatar, Badge, Calendar, Card, Carousel, Collapse, Descriptions, Empty, Image, List, Popover, QRCode, Segmented, Statistic, Table, Tabs, Tag, Timeline, Tooltip, Tour, Tree
- **File**: `examples/components/data-display.md`

**反馈 (Feedback)**
- **Contains**: Alert, Drawer, Message, Modal, Notification, Popconfirm, Progress, Result, Skeleton, Spin, Watermark
- **File**: `examples/components/feedback.md`

**其他 (Other)**
- **Contains**: Affix, App, BackTop, ConfigProvider, FloatButton
- **File**: `examples/components/other.md`

### 3. API & Advanced Topics

- **Components API**: `api/components.md` (Props, Events for common components)
- **ConfigProvider API**: `api/config-provider.md` (Global config, Theme)
- **Theme Customization**: `examples/advanced/theme-customization.md` (Design Token)
- **Internationalization**: `examples/advanced/internationalization.md`

### 4. Templates

- **Component Templates**: `templates/component-template.md` (Basic, Form, Modal patterns)
- **Project Setup**: `templates/project-setup.md` (Vite, Main.ts, App.vue setup)

## 能力边界

### ✅ 适用场景
- 当你需要使用此技能对应的技术栈时
- 当项目需要遵循最佳实践时
- 当需要快速上手或深入理解核心概念时

### ⚠️ 需要注意
- 复杂业务逻辑需要结合具体场景调整
- 性能优化需要根据实际数据量评估

### ❌ 不适用场景
- 不相关的技术栈或框架
- 需要完全自定义的特殊场景

## 常见陷阱 (Gotchas)

1. **版本兼容性**：注意框架版本与依赖库的兼容性，不同版本 API 可能有差异
2. **配置文件格式**：配置文件格式错误是最常见的问题，建议使用编辑器的语法检查
3. **环境变量**：确保所有必要的环境变量已正确设置，敏感信息不要硬编码
4. **依赖冲突**：多版本共存时注意依赖冲突，使用 lock 文件锁定版本
5. **性能陷阱**：大数据量场景下注意性能优化，避免 N+1 查询等常见问题

## 使用流程

### Step 1: 环境准备
确保开发环境已安装必要的依赖和工具。

### Step 2: 配置初始化
根据项目需求进行基础配置。

### Step 3: 核心功能使用
按照示例代码实现核心功能。

### Step 4: 测试验证
运行测试确保功能正常。

### Step 5: 部署上线
完成开发后进行部署和监控。
