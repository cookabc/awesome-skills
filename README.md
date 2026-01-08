# Claude Code Skills

> A curated collection of custom skills for [Claude Code](https://claude.ai/code)

This repository contains custom skills for enhancing Claude Code functionality.

## Skills

### chunxiang-rocket

**AI Programming Bootcamp - A Comprehensive Guide**

Author: Zhao Chunxiang - Independent Developer, AI Entrepreneur, Author of "Stomach Book"

A complete AI programming prompt system that helps you master AI full-stack development from zero to one.

**Topics Covered:**
- GEB Fractal Documentation System Protocol
- Vite + React + TailwindCSS v4 Environment Setup
- shadcn/ui Design System Configuration
- Neumorphic Design with Light & Shadow
- Landing Page Architecture Standards
- Framer Motion Animation Enhancement
- Supabase Integration Workflow

---

### infographic-creation

**Infographic Creation Tool**

A skill for generating visual infographics based on [AntV Infographic](https://infographic.antv.vision/).

**Features:**
- Multiple template types (timeline, flowchart, comparison, hierarchy, etc.)
- Integrated Iconify icon library and unDraw illustration resources
- Customizable theme colors
- SVG export support

---

## Installation

1. Place skill directories under `~/.claude/skills/`
2. Restart Claude Code
3. Skills will be loaded automatically

```
~/.claude/skills/
├── chunxiang-rocket/
│   └── SKILL.md
├── infographic-creation/
│   └── SKILL.md
└── README.md
```

## Usage

Invoke skills directly in Claude Code:

```
/chunxiang-rocket
/infographic-creation
```

Or simply describe your needs in natural language, and Claude will automatically invoke the appropriate skill.

## Contributing

Issues and Pull Requests are welcome.

## License

MIT
