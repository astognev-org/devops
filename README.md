# devops repo

This is set of automation scripts and configs for devops purposes. It contains:
- GitHub workflows
- Other devops stuff like automations and deployment scripts

------------------------------------------------------------------------

## GitHub workflows description

All GitHub workflow files are located in .github\workflows folder.

-   **set-env.yml** - essential workflow providing apportunity to reuse all the variables across whole CI/CD
-   **labels_devops.yml** - workflow intended to cover Label-Driven aproach with following labels:
    - "verify" - perform E2E tests against built application/docker image
    - "publish" - publish Release Candidate
-   **release_devops.yml** - workflow creates tag and release with appropriate notes
-   **bootstrap-branch-ruleset.yml** - workflow which could be reused for branch protection ruleset 
    creation (especilly for enforcing up-to-date branch with main and linear history)


------------------------------------------------------------------------

## Project structure

    .
    ├── .github/
    │   └── workflows/             # GitHub workflows
    └── ...


------------------------------------------------------------------------

## CI pipeline overview


------------------------------------------------------------------------
