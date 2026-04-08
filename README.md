# 方法论.skill

让 AI 从现实条件、主要矛盾和历史过程出发做分析与判断。

不是让 AI 背哲学名词，而是让 AI 按方法论做事。

## 这是什么

`method-skill` 是一个给 Codex / Claude Code 一类 AI coding agent 使用的 skill。

它的核心目标只有一个：

- 避免 AI 只停留在表面意见、价值表态和空洞总结
- 让 AI 先看具体对象、现实条件、利益结构、权力关系和历史过程
- 让 AI 抓住主要矛盾，再从特殊上升到一般，最后回到实践结论

## 适用场景

- 社会问题分析
- 制度与组织诊断
- 观点批判与叙事拆解
- 战略建议
- AI、平台、自动化等技术问题
- 需要从“现实条件”出发的中文分析写作

## 核心方法

这套 skill 会约束 AI 优先做这些动作：

1. 先界定对象
2. 再看物质条件和现实约束
3. 再抓主要矛盾
4. 再放到历史过程中理解
5. 再从特殊上升到一般
6. 最后回到实践、条件与可操作结论

## 仓库结构

- `SKILL.md`：主 skill 文件
- `agents/openai.yaml`：展示名与默认提示
- `references/frameworks.md`：概念框架与诊断问题
- `references/templates.md`：可直接复用的回答模板
- `references/chinese-style.md`：中文优先表达规范
- `references/method-errors.md`：常见方法论错误与修复方式
- `references/technology-and-ai.md`：AI / 技术问题专用分析模板
- `references/source-map.md`：来源映射

## 使用方式

把本仓库作为一个 skill 目录放到你的 skills 目录下，或按你所用 agent 的 skill 机制引入。

调用时可以直接说：

- `Use $method-skill to analyze this problem.`
- `用 $method-skill 分析这个问题。`
- `用方法论.skill 来拆解这个社会现象。`

## 示例问题

- AI 会不会让我们走向共产主义社会？
- 为什么很多组织天天开会但效率还是低？
- 如何批判“只要努力就能成功”这种说法？
- 用现实条件、主要矛盾和历史过程分析某个政策问题
