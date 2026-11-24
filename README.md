# human-writing（说人话）

一个给 AI 编程助手用的中文写作 skill：把商务文档、职场沟通和日常文字写得像人写的，清掉常见 AI 腔。

默认平实风格，也支持灵动、文学、口语三种风格。适用于 BRD、SOP、协作方案、报告、周报、邮件、飞书消息、公众号、分享稿，或任何需要“说人话”“去 AI 味”的场景。

## 安装

把 `SKILL.md` 放到对应工具的 skills 目录，目录名用 `human-writing`：

| 工具 | 目标路径 |
| --- | --- |
| Claude Code | `~/.claude/skills/human-writing/` |
| Codex | `~/.codex/skills/human-writing/` |
| OpenCode | `~/.config/opencode/skills/human-writing/` 或 `~/.agents/skills/human-writing/` |
| magpie | `~/.config/magpie/library/skills/human-writing/` |

用 git clone：

```bash
git clone https://github.com/lalalanull/human-writing-skill ~/.claude/skills/human-writing
```

或者只下载 SKILL.md：

```bash
mkdir -p ~/.claude/skills/human-writing
curl -fsSL https://raw.githubusercontent.com/lalalanull/human-writing-skill/main/SKILL.md \
  -o ~/.claude/skills/human-writing/SKILL.md
```

## 用法

安装后直接让助手用它，例如：

- “用 human-writing 润色这段周报”
- “把这封邮件去掉 AI 味”
- “用口语风格改一下这条飞书消息”
- “这份 SOP 写得太端着，说明白点”

## 内容

- `SKILL.md`：完整的写作底线、四种风格、AI 腔检查清单、标点排版规则和工作流程。

## License

MIT
