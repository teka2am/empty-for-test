# AGENTS.md

## Cursor Cloud specific instructions

### Repository state

This repository is currently an empty placeholder with no application source code, dependencies, or services. The only non-git file is `.cursorrules`.

### Pre-installed tooling in the base environment

The cloud agent VM already has these runtimes and tools available — no installation is needed:

| Tool    | Version  |
|---------|----------|
| Node.js | v22.x    |
| npm     | 10.x     |
| pnpm    | 10.x     |
| yarn    | 1.22.x   |
| Python  | 3.12.x   |
| pip     | 24.x     |
| nvm     | 0.40.x   |
| git     | 2.43.x   |

### Startup

There are no dependencies to install and no services to start. The update script is intentionally a no-op (`true`). When application code is added to this repository, the update script and this section should be updated to match.

### Lint / Test / Build / Run

No lint, test, build, or run commands exist because there is no application code. When code is added, document the commands here or reference the relevant config files (e.g. `package.json` scripts, `Makefile` targets).
