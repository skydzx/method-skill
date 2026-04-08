<div align="center">

# 方法论.skill

**让 AI 从现实条件、主要矛盾和历史过程出发做分析与判断**

> 不是让 AI 背哲学名词，而是让 AI 按方法论做事。

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Skill](https://img.shields.io/badge/Skill-Methodology-blue)
![Chinese](https://img.shields.io/badge/Language-Chinese--first-red)
![Focus](https://img.shields.io/badge/Focus-Reality%20%7C%20Contradiction%20%7C%20Practice-green)

Method-first analysis for reality, contradiction, history, and practice.

[Install](#安装) · [Usage](#使用方式) · [Examples](#示例问题) · [Method](#核心方法) · [Structure](#仓库结构)

</div>

---

很多 AI 的问题，不是不会说，而是说得太快、太满、太表面：

- 一上来就下判断，没有先界定对象
- 一上来就谈价值，没有先看现实条件
- 把现象当本质，把症状当根因
- 把一堆问题摊平，抓不住主要矛盾
- 会写结论，却不会把问题放进历史过程和实践条件里

`method-skill` 的目标，就是把这些毛病压下去。

它不是一个“哲学概念包”，也不是一个“辩论话术包”。  
它是一套给 AI 使用的工作方法：先看对象，再看条件；先抓矛盾，再看历史；从特殊上升到一般，再回到实践。

## 这是什么

`method-skill` 是一个给 Codex / Claude Code 一类 AI agent 使用的 skill。

它会约束 AI 优先做这些事情：

1. 先界定对象
2. 再看物质条件和现实约束
3. 再抓主要矛盾
4. 再放到历史过程中理解
5. 再从特殊上升到一般
6. 最后回到实践、条件与可操作结论

它尤其适合这些任务：

- 社会问题分析
- 制度与组织诊断
- 观点批判与叙事拆解
- 战略建议
- AI、平台、自动化等技术问题
- 需要从“现实条件”出发的中文分析写作

## 安装

把本仓库作为一个 skill 目录放到你的 skills 目录下，或按你所用 agent 的 skill 机制引入。

如果你的环境支持直接按仓库加载 skill，就把这个仓库作为独立 skill 仓库使用。

## 使用方式

引入后，可以直接这样调用：

```text
Use $method-skill to analyze this problem.
用 $method-skill 分析这个问题。
用方法论.skill 来拆解这个社会现象。
```

## 核心方法

这套 skill 的方法主线很简单，但足够硬：

- 从具体对象出发，不先套理论标签
- 从现实条件出发，不从口号和愿望出发
- 先分主次矛盾，不把问题摊平成一张清单
- 把对象放进历史过程，而不是静止理解
- 从特殊上升到一般，再回到具体校验
- 最后落到实践含义，而不是停在抽象表态

如果问题涉及制度、文化、技术或政治经济，它还会继续追问：

- 谁拥有
- 谁控制
- 谁获益
- 谁承担代价
- 什么在维持现状
- 什么在推动变化

## 仓库结构

- `SKILL.md`：主 skill 文件
- `agents/openai.yaml`：展示名与默认提示
- `references/frameworks.md`：概念框架与诊断问题
- `references/templates.md`：可直接复用的回答模板
- `references/chinese-style.md`：中文优先表达规范
- `references/method-errors.md`：常见方法论错误与修复方式
- `references/technology-and-ai.md`：AI / 技术问题专用分析模板
- `references/source-map.md`：来源映射

## 示例问题

- AI 会不会让我们走向共产主义社会？
- 为什么很多组织天天开会但效率还是低？
- 如何批判“只要努力就能成功”这种说法？
- 用现实条件、主要矛盾和历史过程分析某个政策问题
- 用方法论而不是空话去分析一个平台、组织或制度问题

## 适合什么，不适合什么

适合：

- 需要结构分析、现实分析、历史分析的问题
- 需要判断“表面现象后面真正起作用的机制”的问题
- 需要把 AI 从空洞总结拉回现实约束和实践条件的任务

不适合：

- 只想要一句立场表态
- 只想堆砌哲学名词
- 只想做纯修辞性输出而不关心解释力

## 一句话总结

如果你想让 AI 少一点空话、少一点唯心、少一点表面化，多一点现实感、结构感、历史感和实践感，这个 skill 就是为这个目的写的。
