# scientific-figure-style

适用于 Codex 的科研绘图风格 Skill。用于创建或重绘论文、科研汇报 PPT 与报告中的流程图、方法架构图和结果图。

Scientific figure style skill for editable, publication-friendly research visuals.

## 风格特点

- 白底、深蓝标题、蓝色细线与克制的蓝绿配色
- 圆角框、淡蓝辅助底、虚线分组和清晰箭头逻辑
- 网格对齐、充分留白、明确的信息层级
- 优先输出可编辑 PPT/SVG，避免文字截断
- 强调数据、术语、单位与科学语义准确
- 禁止过度渐变、3D、发光和典型 AI 海报风

## 快速安装

项目级安装：

```bash
git clone https://github.com/sukkeejuice-creator/scientific-figure-style.git .agents/skills/scientific-figure-style
```

个人全局安装：

```bash
git clone https://github.com/sukkeejuice-creator/scientific-figure-style.git ~/.codex/skills/scientific-figure-style
```

Windows PowerShell 可将 `~/.codex/skills/` 替换为 `$HOME/.codex/skills/`。

## 使用

显式调用：

```text
Use $scientific-figure-style to create an editable scientific workflow figure.
```

若希望它成为某个项目的默认科研绘图风格，在该项目根目录的 `AGENTS.md` 中加入：

```markdown
For scientific figures, workflows, method architectures, result graphics,
and visuals for papers, presentations, or reports, always load and follow
`.agents/skills/scientific-figure-style/SKILL.md`.

If the user explicitly requests another visual style, the user's style wins.
```

## 内容

```text
scientific-figure-style/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── README.md
└── LICENSE
```

## 许可

MIT License
