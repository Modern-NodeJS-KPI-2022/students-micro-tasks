# Lab 1

## Goals
- setup environment

## Task
Create project in GitHub with minimal code-quality checks and autodepoly
### Requirements
- new repo in GitHub
- initial empty commit
- add ESlint (as strict as possible)
- add Sonar-Lint to ESLint
- add Prettier
- Add check on pre-commit hooks
- Add GitHub action to run checks\tests on commit or PR
- Add AutoDeployment to any hosting provider
- Add Editorconfig
- Bonus: the same with TypeScript
- Bonus: SonarCloud, https://github.com/SonarSource/sonarcloud-github-action
## Questions
- dev Deps vs Deps
- Why we have separate tooling for formatting/linting
- Difference with VPS/FaaS?
- Why we need peerDeps?
- `npm i` vs `npm ci`
- 
## Links
- https://gist.github.com/kjellskogsrud/d824c38f76e38010156d0bc80dbd3c62
- https://docs.npmjs.com/specifying-dependencies-and-devdependencies-in-a-package-json-file
- https://eslint.org/
- https://github.com/SonarSource/eslint-plugin-sonarjs
- https://prettier.io/
- https://editorconfig.org/
- https://prettier.io/docs/en/configuration.html#editorconfig
- https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
- https://prettier.io/docs/en/precommit.html
- https://www.npmjs.com/package/husky
- https://github.com/features/actions
- https://github.com/actions/setup-node
- https://github.com/actions/cache/blob/main/examples.md#node---npm
- Deployment options:
  - Lambda
    - https://pages.cloudflare.com/
    - https://vercel.com/
    - https://firebase.google.com/
    - https://cloud.google.com/run
    - exotic: https://denoflare.dev/
  - VPS
    - https://www.digitalocean.com/
    - https://render.com/
    - https://fly.io/
    - https://www.oracle.com/cloud/free/
    - AWS (free tier should be Ok)
    - Azure (free tier should be Ok)
    - Google Cloud ([free tier](https://cloud.google.com/free-trial/))
  - Do not use:
    - Heroku
