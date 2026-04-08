---
name: method-skill
description: "Use when the user wants AI to work through disciplined methodology rather than surface opinion: start from the concrete object, recover material conditions, identify the principal contradiction, place the issue in historical motion, move from the particular to the general, and return to practice. Trigger on requests such as 方法论, 哲学分析, 形而上学批判, 矛盾论, 唯物史观, 唯物论/唯心主义, 从特殊到一般, 具体问题具体分析. Apply it to essays, diagnosis, critique, strategy, social analysis, institutional analysis, political economy, and technology questions when a surface summary is not enough."
---

# 方法论.skill

## Overview

Use this skill as a working method, not as a slogan generator. Convert loose requests into disciplined analysis by starting from the concrete case, grounding it in material conditions and social relations, locating contradictions, tracing historical movement, and only then rising to general mechanism or principle.

Prefer clear explanation over vocabulary display. If the user asks for a direct answer, use the method internally and only surface the concepts that improve clarity.

## Chinese Output Principles

When the task is in Chinese, do not sound like a translated glossary. Write like a clear Chinese analysis that happens to be methodologically disciplined.

- start with the object, not with a doctrine label
- prefer short sentences and strong verbs over stacked abstract nouns
- explain the mechanism before naming the concept when possible
- use terms like `material conditions`, `principal contradiction`, or `base and superstructure` only when they sharpen the answer
- prefer phrasing such as "surface / underlying mechanism", "key point is", "problem is not only ... but ...", "under these conditions", and "in the current stage"
- end with a concrete implication, not a slogan

Load `references/chinese-style.md` when the answer should sound more like Chinese thought writing, commentary, or structured critique.

## Non-Negotiable Moves

Apply these moves in most tasks, even when the output is short.

### 1. Start from the concrete object

First define what is being analyzed:

- event, policy, institution, class relation, ideology, market, technology, culture, text, or person
- time horizon: immediate, medium-term, historical
- task type: explain, compare, critique, predict, or recommend

Separate four layers when useful:

1. what happened
2. why it happened
3. what contradiction structures it
4. what should be done

Do not start from abstract doctrine and force the case underneath it.

### 2. Ground the case in material conditions

Begin from concrete life-processes and practical conditions, not from slogans.

Check for:

- ownership, labor, incentives, profit model, resource constraints
- productive forces, technology, infrastructure, logistics
- institutions, law, policy, enforcement capacity
- class position, power distribution, dependency relations
- reproduction conditions: education, family, media, social norms

Treat values, discourse, and stated intentions as objects to explain, not as sufficient explanations by themselves.

### 3. Distinguish frames without flattening the case

Use the following contrasts explicitly when helpful:

- **Materialism**: explain consciousness, institutions, and ideas through material life, practice, and social relations.
- **Idealism**: explain social reality primarily through ideas, values, will, spirit, or discourse.
- **Metaphysical/static thinking**: treat things as isolated, fixed, non-historical, or externally related.
- **Dialectical thinking**: treat things as relational, contradictory, developmental, and transformable.

If the topic is conceptual, identify the practical or historical conditions that make that concept necessary or influential.

### 4. Find the contradiction that drives motion

Do not reduce contradiction to "two sides disagree." Focus on tensions built into the structure itself.

Look for:

- main contradiction versus secondary contradictions
- principal aspect versus non-principal aspect
- short-term stability versus long-term instability
- beneficiaries versus bearers of cost
- forces pushing change versus forces preserving the existing order

Ask what would intensify, displace, or temporarily suspend the contradiction.

### 5. Put the object into history

Place the object in motion.

- Explain how the present form emerged.
- Connect it to changes in productive forces and relations of production.
- Note historical stages, turning points, and path dependence.
- Distinguish structural tendencies from temporary episodes.

Avoid describing the current surface as if it were eternal.

### 6. Relate base and superstructure with mediation

When the topic involves institutions, ideology, or culture, map the relation between:

- **economic base**: ownership, labor process, production, circulation, distribution, reproduction
- **superstructure**: law, politics, education, religion, morality, media, culture, ideology

Show mediation instead of crude one-line determinism. The base sets limits and pressure; the superstructure can stabilize, justify, resist, or reorganize the base.

### 7. Move from the particular to the general, then back to practice

Use a three-step loop:

1. start from the concrete case
2. extract the general mechanism or category
3. return to the case and test whether the abstraction truly explains it and what practice would confirm or refute it

If the general claim cannot explain the concrete case, revise the abstraction.

### 8. End with an operational conclusion

- explain what matters most
- identify what is structural versus temporary
- state what can actually be changed
- name the next practical test, decision, or line of inquiry when relevant

## Pre-Answer Self-Check

Run this quickly before finalizing an answer.

- Did I start from the concrete object rather than a ready-made doctrine?
- Did I identify material conditions, interests, constraints, or power relations?
- Did I distinguish the principal contradiction from secondary ones?
- Did I put the issue into motion instead of freezing it?
- Did I separate surface appearance from underlying mechanism?
- Did I move from the particular to the general and then return to the case?
- Did I avoid turning moral attitude into explanation?
- Did I end with a usable implication, condition, or test?

## Scale the Method to the Task

Do not force macro-history onto every prompt. Scale the same method to the level of the user's problem.

### Macro social or political analysis

Focus on:

- productive forces and relations of production
- class structure and institutional reproduction
- ideology, legitimacy, and state form
- historical stage and long-wave movement

### Meso organizational or business analysis

Translate the method into:

- incentives, ownership, budgets, staffing, process bottlenecks
- formal rules versus actual power
- principal contradiction in the operating model
- short-term patch versus structural fix

### Micro personal or small-team analysis

Translate the method into:

- time, energy, money, dependency, role conflict
- immediate constraints versus self-description
- contradiction between goals and actual conditions
- what concrete practice would change the situation

## Task Router

Choose the route that matches the user's request.

### Essay or commentary route

Use when the user wants a written analysis piece, article, or long-form explanation.

Sequence:

1. define the object and stakes
2. reconstruct the material basis
3. identify the main contradiction
4. explain historical formation
5. separate appearance from essence
6. rise to the general mechanism
7. return to the case
8. close with implication or line of struggle

### Diagnosis and decision route

Use when the user wants recommendations, troubleshooting, or strategic judgment.

Sequence:

1. state the concrete problem
2. separate symptoms from structural causes
3. identify material constraints and incentives
4. identify the principal contradiction
5. identify the principal aspect at this moment
6. rank secondary contradictions
7. name the decisive leverage point
8. recommend action in order of feasibility and structural effect

### Critique and debunking route

Use when the user wants to dismantle an argument, ideology, or surface narrative.

Sequence:

1. restate the claim fairly
2. identify what it treats as primary cause
3. show what material conditions it brackets off
4. identify what relations or interests are being naturalized
5. distinguish appearance from underlying mechanism
6. show the contradiction it hides or misdescribes
7. replace it with a stronger explanation

### Technology and social-form route

Use when the object is AI, automation, platforms, data infrastructure, algorithms, or a new production technology.

Sequence:

1. define the technology as a productive force, not just a gadget
2. identify the required infrastructure: data, compute, energy, capital, labor, institutions
3. map who owns, controls, and captures value from the system
4. identify how the technology reorganizes labor, skill, surveillance, or coordination
5. distinguish productivity effects from distribution effects
6. identify the principal contradiction the technology sharpens or displaces
7. ask whether the technology stabilizes the existing order or opens a new social possibility
8. end with the institutional conditions under which the technology would serve different class interests

## Default Output Structures

Pick the smallest structure that still preserves the method.

### Short answer

Use:

1. object and scope
2. material basis
3. main contradiction
4. historical movement or structural tendency
5. conclusion

### Standard answer

1. object and scope
2. material conditions
3. contradiction map
4. historical movement
5. base-superstructure relation if relevant
6. materialist vs idealist reading if relevant
7. general conclusion
8. practical implication

### Comparative answer

Compare positions by:

- ontology: what they think reality is
- causality: what they treat as the main driver
- method: static or dialectical, abstract or historical
- politics: whose interests the position tends to reinforce
- limits: what each approach cannot explain well

## Guardrails

- Do not force every keyword into every answer.
- Do not use jargon to cover weak reasoning.
- Do not start with a theory label before reconstructing the case.
- Do not treat "economic base determines superstructure" as a mechanical shortcut; explain the mediating path.
- Do not caricature idealism; explain what it clarifies and where it becomes insufficient.
- Do not confuse moral outrage with contradiction analysis.
- Do not mistake a symptom for the principal contradiction.
- Do not stop at description; ask what practice would test the account.
- Do not stay at the level of abstraction; return to the actual case.
- If the topic is personal or small-scale, scale the framework down instead of pretending every issue is a grand historical rupture.

## Common Method Errors

Watch for recurring failures such as:

- moralizing instead of explaining
- psychologizing what is actually structural
- individualizing what is reproduced institutionally
- flattening all contradictions into one list
- treating a temporary form as eternal
- slipping into technological determinism or mechanical economic determinism

Load `references/method-errors.md` when the draft feels slogan-like, too abstract, too moralized, or too focused on personal intention.

## When to Load References

Read `references/frameworks.md` when the task needs:

- a fuller concept list
- compact diagnostic questions
- additional dialectical categories such as essence/appearance or quantity/quality
- concept distinctions such as practice versus dogmatism or universal versus particular

Read `references/templates.md` when the task needs:

- ready-to-use answer skeletons
- operational prompt patterns for essay, diagnosis, critique, or strategy work
- a reusable checklist another agent can follow step by step

Read `references/chinese-style.md` when the task needs:

- a Chinese-first writing rhythm instead of translated framework language
- sentence patterns for commentary, critique, diagnosis, or strategic analysis
- guidance on how to sound direct, concrete, and method-driven in Chinese

Read `references/method-errors.md` when the task needs:

- a checklist of common analytical mistakes
- fast diagnosis of where an answer became idealist, static, moralized, or overly abstract
- repair moves for turning a weak draft back into a disciplined one

Read `references/technology-and-ai.md` when the task needs:

- a dedicated template for AI, automation, platforms, or algorithmic governance
- a structured way to analyze productive forces, ownership, labor process, and distribution together
- guardrails against shallow "technology changes everything" answers

Read `references/source-map.md` when the task needs:

- the intellectual origin of the workflow
- a quick map from source text to operational method
- extension or refinement of the skill using the online sources behind it
