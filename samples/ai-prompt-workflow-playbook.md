# AI Prompt Workflow Playbook

A practical playbook for turning one-off ChatGPT prompts into repeatable workflows that can be reused by a solo founder, developer, marketer, or content team.

Use this when you want better results than a generic prompt list. Each workflow includes context, inputs, constraints, output format, and a quality gate.

---

## 1. The Reusable Prompt Spec

```text
You are a senior AI workflow designer.

Goal:
Turn my rough prompt into a reusable prompt spec that produces consistent results across multiple projects.

Rough prompt:
[PASTE YOUR CURRENT PROMPT]

Context:
- User type: [developer / marketer / founder / designer / other]
- Repeated task: [WHAT THIS PROMPT WILL BE USED FOR]
- Common inputs: [LIST INPUTS]
- Bad outputs to avoid: [LIST FAILURE MODES]

Create a reusable prompt with these sections:
1. Role
2. Task
3. Required inputs
4. Constraints
5. Step-by-step reasoning checklist
6. Output format
7. Quality bar
8. Optional follow-up prompts

Decision rule:
If any required input is missing, list the missing inputs first instead of guessing.
```

Why it works: it converts vague intent into an operating procedure, which is easier to test, improve, and delegate.

---

## 2. The Prompt Debugger

```text
You are a prompt QA analyst.

I will give you a prompt and a bad AI output. Diagnose why the output failed and rewrite the prompt.

Original prompt:
[PASTE PROMPT]

Bad output:
[PASTE OUTPUT]

Expected result:
[DESCRIBE WHAT YOU WANTED]

Analyze:
- Missing context
- Ambiguous instructions
- Weak constraints
- Missing examples
- Wrong output format
- Any hidden assumptions

Then provide:
1. Root cause summary
2. Improved prompt
3. A stricter output format
4. A test case I can run to verify improvement
```

---

## 3. The Team Prompt SOP

```text
You are an operations lead creating an SOP for AI-assisted work.

Task to standardize:
[DESCRIBE TASK]

Team members who will use it:
[ROLES]

Inputs available:
[INPUTS]

Business rules:
[RULES, BRAND VOICE, TECHNICAL LIMITS, COMPLIANCE NOTES]

Create an SOP that includes:
- When to use this prompt
- Required inputs checklist
- The final prompt template
- Review checklist
- Examples of acceptable vs unacceptable outputs
- Versioning notes for future improvement

Keep it concise enough to paste into a team wiki.
```

---

## 4. The Launch Content Workflow

```text
You are a launch content strategist.

Product:
[PRODUCT NAME]

Audience:
[TARGET CUSTOMER]

Core problem:
[PAIN POINT]

Proof or differentiator:
[PROOF]

Create a 7-day organic launch content workflow with:
- 2 X/Twitter posts per day
- 1 LinkedIn post per day
- 3 Reddit-safe discussion prompts
- 1 founder story post
- 1 email announcement

Rules:
- Do not sound like an ad
- Lead with useful insight
- Include soft CTA variants
- Reuse the same core idea without duplicating wording

Output as a table with day, channel, angle, draft copy, and CTA.
```

Related full pack: AI Marketing Copy Prompt Pack — https://payhip.com/b/6lqVh?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_marketing

---

## 5. The Developer Review Workflow

```text
You are a senior software engineer reviewing a code change.

Code or diff:
[PASTE CODE/DIFF]

Project context:
[STACK, ARCHITECTURE, CONSTRAINTS]

Review priorities:
[SECURITY / PERFORMANCE / READABILITY / TESTS / API DESIGN]

Return:
1. High-risk issues
2. Correctness bugs
3. Maintainability improvements
4. Missing tests
5. Suggested patch snippets
6. Questions to ask before merging

Rules:
- Do not nitpick style unless it affects maintainability
- Separate blockers from suggestions
- Explain tradeoffs briefly
```

Related full pack: Developer's Prompt Bible — https://payhip.com/b/ADsQI?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_developer

---

## 6. The Visual Concept Workflow

```text
You are a commercial art director creating AI image prompts.

Campaign/product:
[PRODUCT]

Brand style:
[STYLE]

Use case:
[AD / POSTER / PRODUCT MOCKUP / SOCIAL CREATIVE]

Audience emotion:
[EMOTION]

Create 10 image prompt concepts. For each include:
- Scene description
- Composition
- Lighting
- Materials/textures
- Color palette
- Camera/lens or design style
- Negative prompt
- Commercial usage note

Avoid copyrighted character names, living artist imitation, and brand trademark confusion.
```

Related full pack: Midjourney Commercial Design Prompt Pack — https://payhip.com/b/XLNPm?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_midjourney

---

## Upgrade path

If these samples are useful, the full PromptCraft packs contain larger, categorized systems with more examples and production-ready variations:

- Developer's Prompt Bible: https://payhip.com/b/ADsQI?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_footer
- AI Marketing Copy Prompt Pack: https://payhip.com/b/6lqVh?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_footer
- Midjourney Commercial Design Prompt Pack: https://payhip.com/b/XLNPm?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=workflow_playbook_footer
