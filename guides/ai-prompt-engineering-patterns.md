# AI Prompt Engineering Patterns for Real Workflows

This note is a practical SEO landing page for people searching for reusable AI prompt engineering patterns, ChatGPT workflow prompts, Claude prompts, developer AI prompts, marketing AI prompts, and Midjourney commercial prompts.

Most prompt libraries fail because they only list commands. A reliable prompt system has repeatable structure:

```text
Role → Context → Inputs → Constraints → Output format → Quality check → Next action
```

Use the patterns below as starting points. They are free samples from PromptCraft-style workflows.

## Pattern 1: Role + decision frame

Use this when you need judgment, not just text generation.

```text
You are a [SENIOR ROLE] helping with [TASK].

Context:
- Goal: [GOAL]
- Audience/user: [AUDIENCE]
- Constraints: [TIME/BUDGET/TECH/BRAND]
- Risk tolerance: [LOW/MEDIUM/HIGH]

Analyze [INPUT].
Return:
1. Main recommendation
2. 3 strongest reasons
3. Risks and tradeoffs
4. What you would do next
5. What information is missing

Decision rule: if the evidence is weak, say so and give the safest next step.
```

Best for: code review, product decisions, positioning, ad strategy, landing page critique.

## Pattern 2: Convert messy input into a reusable asset

Use this when your source material is scattered: notes, transcripts, docs, tickets, or customer feedback.

```text
Transform the following raw material into a reusable [ASSET TYPE].

Raw material:
[PASTE NOTES / TRANSCRIPT / DOC]

Target audience: [AUDIENCE]
Channel: [CHANNEL]
Tone: [TONE]
Primary CTA: [CTA]

Return:
- One clear angle
- Final asset draft
- 5 alternative hooks
- 3 objections to address
- Repurposing ideas for 3 other channels
```

Best for: newsletters, X/Twitter posts, LinkedIn posts, product launch copy, documentation.

## Pattern 3: Force implementation-ready output

Use this when you need code, plans, tests, or operations steps.

```text
Act as a [ROLE]. Build an implementation-ready answer for [TASK].

Project context:
- Stack/tools: [STACK]
- Current state: [CURRENT STATE]
- Desired outcome: [OUTCOME]
- Constraints: [CONSTRAINTS]

Return:
1. Assumptions
2. Step-by-step plan
3. Exact commands/code/templates where useful
4. Test or validation checklist
5. Rollback/failure plan

Do not give generic advice. If something depends on missing information, choose the safest default and label it.
```

Best for: developer workflows, debugging, CI fixes, technical documentation, launch checklists.

## Pattern 4: Commercial image prompt scaffold

Use this for Midjourney or other image models when the output must look like usable marketing creative.

```text
Create a commercial visual prompt for [PRODUCT / BRAND / CAMPAIGN].

Creative brief:
- Product: [PRODUCT]
- Audience: [AUDIENCE]
- Mood: [MOOD]
- Composition: [COMPOSITION]
- Usage: [AD / HERO IMAGE / SOCIAL / POSTER]
- Brand constraints: [COLORS / STYLE / DO-NOT-USE]

Prompt format:
[subject], [setting], [lighting], [camera/composition], [materials/details], [brand mood], [commercial photography/design terms], [negative constraints]
```

Best for: product mockups, ad concepts, hero images, posters, brand assets.

## Full packs

- Developer's Prompt Bible: https://payhip.com/b/ADsQI?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=seo_patterns_dev
- AI Marketing Copy Prompt Pack: https://payhip.com/b/6lqVh?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=seo_patterns_marketing
- Midjourney Commercial Design Prompt Pack: https://payhip.com/b/XLNPm?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=seo_patterns_midjourney

## Free samples

See the repo README for more free workflow prompt samples: developer prompts, marketing prompts, Midjourney prompts, and content repurposing prompts.
