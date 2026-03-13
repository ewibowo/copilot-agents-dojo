# Copilot Instructions

## Code Standards

- Always use TypeScript with `strict: true`
- Naming: camelCase for variables/functions, PascalCase for components/types
- Styling: Tailwind CSS + shadcn/ui components
- Testing: Write Vitest tests for every new component/logic
- Architecture: Next.js App Router, Server Actions, React Server Components when possible
- Security: Never commit secrets, use environment variables

## Agent Behavioral Governance

See [skills.md](../skills.md) for the full behavioral skills framework. Key principles:

- **Plan first**: Enter plan mode for any non-trivial task (3+ steps). Write plan to `tasks/todo.md`.
- **Verify before done**: Run tests, check logs, diff against main. Never mark complete without proof.
- **Subagents for scale**: Offload research and parallel analysis to subagents. Keep context clean.
- **Self-improvement**: Capture lessons in `tasks/lessons.md` after any correction. Review at session start.
- **Elegance over hacks**: Challenge shortcuts on non-trivial changes. Simplicity first, always.
- **Autonomous bug fixing**: Reproduce → diagnose → fix → verify. Zero hand-holding.
- **Senior-level discipline**: Find root causes. No temporary fixes. No laziness.

## Task Management

1. **Plan First**: Write plan to `tasks/todo.md` with checkable items.
2. **Verify Plan**: Check in before starting implementation.
3. **Track Progress**: Mark items complete as you go.
4. **Explain Changes**: High-level summary at each step.
5. **Document Results**: Add review section to `tasks/todo.md`.
6. **Capture Lessons**: Update `tasks/lessons.md` after corrections.

Use these for all sessions to ensure consistency.
