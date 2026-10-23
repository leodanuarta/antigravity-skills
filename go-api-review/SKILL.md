---
name: go-api-review
description: Reviews and implements small Go HTTP API changes using explicit acceptance criteria, focused changes, and tests. Use when implementing, debugging, or reviewing Go API endpoints.
---

# Go API Review

## Workflow

1. Inspect the existing project structure and HTTP routes.
2. Confirm the requirement and acceptance criteria before coding.
3. Follow the existing project conventions and dependencies.
4. Keep changes limited to files relevant to the task.
5. Handle HTTP status codes, JSON responses, and invalid input.
6. Add tests for success cases, empty results, and invalid input.
7. Run the relevant tests, including `go test ./...` when appropriate.
8. Inspect the diff for unrelated changes.
9. Report changed files, test commands, actual results, and remaining issues.

## Constraints

- Do not add dependencies without justification.
- Do not claim tests passed unless they were executed.
- Ask before making destructive or unrelated changes.
