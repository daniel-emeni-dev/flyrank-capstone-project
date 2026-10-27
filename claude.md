# Claude Rules

## Purpose
Use this file as a lightweight operating guide for AI-assisted work in this repository. Keep actions focused, safe, and easy to review.

## Core principles
- Be concise and practical.
- Prefer the smallest correct change over broad refactors.
- Preserve existing patterns and architecture unless the task explicitly requires a change.
- Do not add dependencies or complexity without a clear need.
- Ask for clarification when requirements are ambiguous or conflicting.

## Workflow
1. Read the relevant files first and identify the exact task.
2. Keep the scope limited to the requested change.
3. Implement the fix or feature in the least invasive way.
4. Validate with the smallest relevant command or test.
5. Summarize what changed and how it was verified.

## Code standards
- Write clear, readable code with meaningful names.
- Favor explicit logic over clever or abstract solutions.
- Keep functions small and focused.
- Handle errors gracefully and avoid silent failures.
- Preserve formatting and existing style in the project.

## Documentation
- Update or add documentation when behavior changes materially.
- Keep comments useful and limited to non-obvious logic.
- Prefer clear implementation over excessive inline explanation.

## Verification
- Run the relevant validation command before claiming success.
- If full tests are not feasible, run the smallest meaningful check.
- Report actual results, including failures or limitations.

## Communication
- Keep explanations brief and actionable.
- State assumptions clearly when necessary.
- Call out risks, trade-offs, and remaining unknowns.
- Do not claim completion without verification evidence.

## Safety
- Do not expose secrets, credentials, or environment-specific values.
- Avoid destructive commands unless explicitly requested.
- Do not make unrelated cleanup changes while fixing a task.

## Default behavior
When in doubt, choose the simpler, more maintainable option and explain the reasoning briefly.
