# Stylish Workflow

Github Actions workflow template

## Testing

Run unit/E2E test script

### Unit Testing

Run unit testing action `unit-testing.yml`

### E2E Testing

Run E2E testing action `e2e-testing.yml`

### Feature

- start action when push or open pull request
- support private package
  - unit: `unit-testing-with-private-package.yml`
  - E2E: `e2e-testing-with-private-package.yml`
- leave result comment when open pull request (skip if push to branch)

## Docker Deploy

Run docker deploy action `docker-deploy.yml`

### Feature

- deploy docker image to github container registry
- deploy to Render

## Draft Release

Create draft a new release action(`release-drafter.yml`)

### Feature

- start action when push to main(default) branch

### How to use it

- add file to `.github/workflows` of your repository root directory
- add `release-drafter-config` to `.github` of your repository root directory

## Pull Request Template

Can request a quick code review

### How to Use

- add `PULL_REQUEST_TEMPLATE.md` to `.github` of your repository root directory
