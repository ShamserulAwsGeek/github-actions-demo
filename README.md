# GitHub Actions Demo

This repository demonstrates the use of GitHub Actions for CI/CD.

## Workflows

### Branch Protection

Enforces branch protection rules on the `main` branch.

### Setup Workflow

Sets up the repository, installs dependencies, and runs tests on every push and pull request.

## Setup Instructions

1. Place workflow files in the `.github/workflows` directory.
2. Ensure `branch-protection.yaml` contains branch protection rules.
3. Ensure `setup-workflow.yaml` contains setup and test instructions.

## Usage

1. Push changes or create a pull request.
2. GitHub Actions will run the workflows based on the triggers.
3. Check the Actions tab in your GitHub repository for workflow runs and status.
