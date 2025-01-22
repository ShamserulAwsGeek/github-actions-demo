# GitHub Actions Demo

This repository demonstrates the use of GitHub Actions for CI/CD.

## Workflows

### Branch Protection

The `branch-protection.yaml` workflow enforces branch protection rules on the `main` branch.

### Setup Workflow

The `setup-workflow.yaml` workflow sets up the repository, installs dependencies, and runs tests on every push and pull request.

## Setup Instructions

1. Ensure the workflow files are located in the `.github/workflows` directory.
2. The `branch-protection.yaml` file should contain the branch protection rules.
3. The `setup-workflow.yaml` file should contain the setup and test instructions.

## Usage

1. Push changes to the repository or create a pull request.
2. GitHub Actions will automatically run the workflows based on the defined triggers.
3. Check the Actions tab in your GitHub repository to see the workflow runs and their status.
