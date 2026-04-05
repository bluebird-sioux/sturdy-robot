# Contributing

Thank you for taking the time to contribute! Please follow these guidelines to keep things smooth for everyone.

## Getting started

1. **Fork** the repository and create your branch from `main`.
2. Make sure your changes pass all existing checks before opening a PR.
3. Open a pull request against `main` and fill in the PR template.

## Branch naming

Use a short, descriptive name with a prefix:

| Prefix | Use for |
|--------|---------|
| `feat/` | New features |
| `fix/` | Bug fixes |
| `chore/` | Maintenance, dependency updates |
| `docs/` | Documentation only changes |

Example: `feat/add-login-page`

## Commit messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) spec:

```
<type>(<scope>): <short summary>
```

Examples:
- `feat(auth): add OAuth2 login`
- `fix(api): handle empty response correctly`
- `chore(deps): bump actions/checkout to v4`

## Pull requests

- Keep PRs focused — one concern per PR.
- Link to the related issue in the PR description (`Closes #123`).
- At least one code-owner approval is required before merge.
- All CI checks must pass before merging.
- Direct pushes to `main` are not allowed.

## Security

- **Never** commit secrets, tokens, API keys, or credentials.
- Use `.env.example` to document required environment variables; copy it to `.env` locally (`.env` is git-ignored).
- Report security vulnerabilities privately — do not open a public issue.

## Code style

- Follow the editor settings defined in `.editorconfig`.
- Keep code readable and well-commented where intent is not obvious.

## Questions?

Open a [Discussion](../../discussions) or an issue with the `question` label.
