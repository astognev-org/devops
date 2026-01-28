# devops repo

This is set of automation scripts and configs for devops purposes. It contains:
- GitHub workflows
- Deployment scripts
- Automation scripts
- ...

------------------------------------------------------------------------

## GitHub workflows description

All GitHub workflow files are located in .github\workflows folder.

-   **labels_devops.yml** - workflow intended to cover Label-Driven aproach with following labels:
    - "verify" - perform E2E tests against built application/docker image
    - "publish" - publish Release Candidate
-   **release_devops.yml** - workflow creates tag and release with appropriate notes
-   **set-env.yml** - essential workflow providing apportunity to reuse all the variables across whole CI/CD


------------------------------------------------------------------------

## Project structure

    .
    ├── .github/
    │   └── workflows/             # GitHub workflows
    ├── terraform/                 # Terraform templates
    │   ├── environments/          # Infrastructure environments
    └── scripts/                   # Automation scripts


------------------------------------------------------------------------

## CI pipeline overview


------------------------------------------------------------------------
