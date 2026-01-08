# Claude Code Skills

> 精选 Claude Code 技能集合

[**English**](README.md) | 中文文档

这个仓库包含用于增强 Claude Code 功能的自定义技能。

## 技能列表

### chunxiang-rocket

**纯想独立开发火箭课程 - AI编程实战指南**

作者：赵纯想 - 独立开发者、AI创业者、胃之书作者

这是一个完整的 AI 编程提示词系统，帮助你从 0 到 1 掌握 AI 全栈开发技能。

**涵盖内容：**
- GEB 分形文档系统协议
- Vite + React + TailwindCSS v4 环境初始化
- shadcn/ui 设计系统配置
- 微拟物光影质感设计
- Landing Page 架构规范
- Framer Motion 动画提升
- Supabase 接入全流程

---

### infographic-creation

**信息图表创建工具**

基于 [AntV Infographic](https://infographic.antv.vision/) 的可视化信息图表生成技能。

**功能：**
- 支持多种模板类型（时间线、流程图、对比图、层级图等）
- 集成 Iconify 图标库和 unDraw 插画资源
- 自定义主题配色
- 导出 SVG 格式

---

## 安装

1. 将技能目录放置在 `~/.claude/skills/` 下
2. 重启 Claude Code
3. 技能将自动加载

```
~/.claude/skills/
├── chunxiang-rocket/
│   └── SKILL.md
├── infographic-creation/
│   └── SKILL.md
└── README.md
```

## 使用

在 Claude Code 中直接调用技能：

```
/chunxiang-rocket
/infographic-creation
```

或通过自然语言描述需求，Claude 会自动调用相应技能。

## 贡献

欢迎提交 Issue 和 Pull Request。

## 许可证

MIT
