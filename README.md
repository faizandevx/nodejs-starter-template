# Node.js Starter Template

[![CI](https://github.com/faizandevx/nodejs-starter-template/actions/workflows/ci.yml/badge.svg)](https://github.com/faizandevx/nodejs-starter-template/actions/workflows/ci.yml)
![Node.js](https://img.shields.io/badge/Node.js-24%2B-339933?logo=node.js&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-enabled-4B32C3?logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-enabled-F7B93E?logo=prettier&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-tested-C21325?logo=jest&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

🚀 A reusable Node.js starter template with code quality, formatting, testing, CI, and a clean development workflow preconfigured.

## What's Included

- ✅ Node.js 24+
- ✅ ESLint for code quality
- ✅ Prettier for consistent formatting
- ✅ Jest with a sample unit test
- ✅ GitHub Actions CI
- ✅ Conventional Commits
- ✅ Trunk-based development workflow
- ✅ Pull request workflow guidance
- ✅ Contribution guidelines
- ✅ Security policy
- ✅ Code of Conduct
- ✅ MIT License

## Quick Start

### Prerequisites

Before getting started, make sure you have:

- Git
- Node.js 24 or later
- npm

Verify your installation with:

```bash
git --version
node --version
npm --version
```

### 1. Create a Repository from This Template

Click **Use this template** on GitHub and create a new repository.

### 2. Clone Your New Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Replace:

- `YOUR_USERNAME` with your GitHub username
- `YOUR_REPOSITORY` with the name of the repository you created from this template

### 3. Update the CI Badge

After creating your repository, update the CI badge at the top of this README with your own GitHub username and repository name.

### 4. Install Dependencies

```bash
npm ci
```

### 5. Run ESLint

```bash
npm run lint
```

### 6. Check Code Formatting

```bash
npm run format:check
```

### 7. Run Tests

```bash
npm test
```

If all checks pass successfully, your project is ready for development.

## Available Scripts

| Command | Purpose |
| --- | --- |
| `npm test` | Run Jest tests |
| `npm run lint` | Run ESLint |
| `npm run format` | Format project files with Prettier |
| `npm run format:check` | Check formatting without modifying files |

## Project Structure

```text
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── .prettierignore
├── .prettierrc
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── SECURITY.md
├── eslint.config.js
├── package-lock.json
├── package.json
├── sum.js
└── sum.test.js
```

`sum.js` and `sum.test.js` are simple example files demonstrating the Jest setup. Replace them with your application code and tests when starting a real project.

## Continuous Integration

GitHub Actions automatically runs CI on pushes and pull requests targeting `main`.

The CI workflow checks:

- ESLint
- Prettier
- Jest

Changes should only be merged when the required CI checks pass.

## Development Workflow

This repository follows a trunk-based development approach.

- `main` is the primary branch.
- Create short-lived branches for changes.
- Open a pull request before merging.
- Keep changes small and focused.
- Ensure CI passes before merging.
- Delete temporary branches after they are merged.

Example branch names:

```text
feature/user-login
fix/input-validation
docs/update-readme
test/add-unit-tests
chore/update-config
```

## Conventional Commits

Use clear Conventional Commit messages.

Examples:

```text
feat: add authentication
fix: resolve validation issue
docs: update README
test: add unit tests
chore: update dependencies
refactor: simplify service logic
```

## Contributing

Contributions are welcome.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## Security

For security guidance and vulnerability reporting, see [SECURITY.md](SECURITY.md).

Please do not report security vulnerabilities through public GitHub issues.

## License

This project is licensed under the [MIT License](LICENSE).

Copyright © 2026 Faizan Ali.