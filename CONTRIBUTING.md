# Contributing to Corfedo

Thanks for contributing to Corfedo.

## Before opening a pull request

- Check existing issues and pull requests.
- Keep changes focused on one problem.
- For substantial behavioral or architectural changes, open an issue or
  discussion first.
- Follow the repository's local development and testing instructions.

## Commit messages

Commit messages follow [Conventional Commits 1.0](https://www.conventionalcommits.org/en/v1.0.0/). Release notes
are generated from them when a version is tagged:

```
<type>(<scope>): <summary>
```

| Type | For | Release notes section |
| --- | --- | --- |
| `feat` | New or changed behavior | Features |
| `fix` | Bug fixes | Fixes |
| `perf` | Performance improvements | Performance |
| `docs` | Documentation | Documentation |
| `build` | Build, packaging and dependency updates | Build and dependencies |
| `refactor`, `test`, `ci`, `chore`, `style` | Changes users do not see | Not listed |

- The scope is optional and names the affected area in lowercase, for example `feat(sqlserver):` or `build(deps):`.
- The summary is in the imperative mood without a trailing period: `fix: report cancelled commands as
  OperationCanceledException`.
- A breaking change adds `!` after the type or scope and a `BREAKING CHANGE:` footer that says what changed and what
  users need to do. Release notes list breaking changes first.
- Each entry credits its author by GitHub username when the commit email belongs to a GitHub account.

## Pull requests

The pull request title follows the commit message format. A pull request should explain:

- What changed and why.
- How the change was tested.
- Any compatibility or migration implications.

Repository-specific contribution instructions take precedence over this file.
Follow the [Corfedo code of conduct](https://github.com/corfedo/.github/blob/main/CODE_OF_CONDUCT.md)
when participating.

## Reporting security issues

Do not report security vulnerabilities through public issues. Follow the
[security policy](https://github.com/corfedo/.github/blob/main/SECURITY.md).
