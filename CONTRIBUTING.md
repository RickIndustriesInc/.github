# Contributing

Rick Industries Inc. executes one approved task at a time.

## Workflow

1. Confirm the task exists in Notion and is marked **In Progress**.
2. Create a focused branch from the current default branch.
3. Keep the change inside the task's acceptance criteria.
4. Run the repository's documented quality checks.
5. Open a pull request and link the Notion task or ticket.
6. After merge, update the task evidence and mark it **Done**.

## Commit style

Use concise conventional commits when practical:

- `feat:` product behavior
- `fix:` defect correction
- `test:` test coverage
- `docs:` documentation
- `refactor:` internal change without behavior change
- `chore:` tooling or maintenance

## Guardrails

- Never commit secrets, credentials, tokens, or `.env` files.
- Never mix development and test databases.
- Avoid destructive infrastructure commands unless explicitly required.
- Do not expand scope without updating the task decision first.
