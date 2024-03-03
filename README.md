# GitHub Actions

This repository contains shared actions and workflows.

## Using a workflow

You can call one workflow from within another workflow.
This allows you to reuse workflows, avoiding duplication and making your
workflows easier to maintain. For more information, see
[Reusing workflows.](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows).

### Example Workflow

```yaml
name: Digger Workflow

on:
  issue_comment:
    types: [created]
  pull_request:
    branches: [ "main" ]
    types: [ opened, synchronize, closed ]
  schedule: ## 8am every week on Monday
    - cron: '0 8 * * 1'

jobs:
  digger-job:
    uses: kieranbrown/github-actions/.github/workflows/digger_workflow.yaml@v1
    secrets: inherit
    permissions:
      actions: write       # required for plan persistence
      contents: write      # required to merge PRs
      id-token: write      # required for workload-identity-federation
      pull-requests: write # required to post PR comments
      statuses: write      # required to validate combined PR status
```

## Contributing

Please ensure you have [pre-commit framework](https://pre-commit.com)
installed and configured before submitting your Pull Request.

The included [Brewfile](./Brewfile) includes all dependencies necessary
to run this project. You can install these dependencies with `brew bundle`.
