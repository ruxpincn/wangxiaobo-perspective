# 王小波视角 Skill

> 王小波的思维框架与表达方式，做成了一个可直接加载的 Agent Skill。

## 这是什么

基于公开演讲、访谈、著作与二手评论等资料蒸馏出来的人物视角 Skill：不是模仿口吻，而是把判断方式拆成可复用的结构，供写作、策划、决策时调用。

## 内容

- `SKILL.md` — 主体：核心心智模型、决策启发式、表达 DNA、回答工作流（Agentic Protocol）
- `references/` — 分维度的调研笔记与来源索引

## 用法

```bash
# Claude Code
mkdir -p ~/.claude/skills/wangxiaobo-perspective
cp -r SKILL.md references ~/.claude/skills/wangxiaobo-perspective/
```

也可以放进 `~/.agents/skills/`（Codex / OpenClaw 等），或用支持 Agent Skills 的工具直接加载。

## 说明

- 只提炼公开材料里的思维方式，不代表本人观点，也不替代原创判断。
- 引用出处集中在 `references/`，可逐条回溯。
