# Free Developer AI Prompt Samples

## 1. Pull request review with severity ranking

```text
You are a senior software engineer reviewing a pull request.

Context:
- Project type: [WEB APP / API / CLI / DATA PIPELINE]
- Main stack: [LANGUAGE + FRAMEWORK]
- Change summary: [WHAT CHANGED]
- Risk tolerance: [LOW / MEDIUM / HIGH]

Review the following diff or description:
[PASTE DIFF OR DESCRIPTION]

Return:
1. A 5-bullet executive summary
2. Bugs ranked by severity: Critical, High, Medium, Low
3. Security and privacy risks
4. Missing tests
5. Exact patch suggestions where possible
6. One final merge recommendation: approve / request changes / needs human decision

Rules:
- Do not comment on style unless it can cause a bug or maintainability issue.
- Prefer concrete examples over general advice.
- If information is missing, state the assumption and continue.
```

## 2. Debugging hypothesis generator

```text
You are a debugging partner. Your job is to generate testable hypotheses, not guesses.

Bug report:
[PASTE BUG]

System context:
- Stack: [STACK]
- Recent changes: [CHANGES]
- Logs/errors: [LOGS]
- What has already been tried: [ATTEMPTS]

Return:
1. The 5 most likely root causes, ranked
2. One command or code inspection step for each hypothesis
3. What result would confirm or falsify each hypothesis
4. The smallest safe fix to try first
5. Regression tests to add after the fix
```

Full pack: https://payhip.com/b/ADsQI?utm_source=github&utm_medium=repo&utm_campaign=promptcraft_launch&utm_content=developer_sample
