# Stylish Workflow
##### Github Actions workflow template

## Unit Testing
#### Run unit testing action(`unit-testing.yml`)
### Feature
- start action when push or open pull request
- support private package (using `unit-testing-with-private-package.yml`)
- leave result comment when open pull request (skip if push to branch)
### How to use
- add file to `.github/workflows` of your repository root directory

## Draft Release
#### Create draft a new release action(`release-drafter.yml`)
### Feature
- start action when push to main(default) branch
### How to use
- add file to `.github/workflows` of your repository root directory
- add `release-drafter-config` to `.github` of your repository root directory

## Pull Request Template
### How to Use
- add `PULL_REQUEST_TEMPLATE.md` to `.github` of your repository root directory