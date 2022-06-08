# kidsloop-action-center

This repository is used to store reusable GitHub Action Workflows, to be used in other repositories.

## Usage

In your local repository:
```yml
jobs:
  install:
    uses: KL-Engineering/kidsloop-action-center/.github/actions/gocache@main
        with:
          GIT_TOKEN: ${{ secrets.PACKAGES_TOKEN }}
```
