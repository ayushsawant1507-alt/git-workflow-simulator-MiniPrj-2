# Contributing Guide

## Overview

This repository demonstrates a Git workflow used by a collaborative development team. Contributors should follow the branching strategy and review process described below.

## Branch Strategy

### main

The production-ready branch containing stable and tested code.

### develop

The integration branch where completed features are merged before being released to production.

### Feature Branches

All new features should be developed in separate feature branches created from the develop branch.

Examples:

- feature-login
- feature-dashboard
- feature-profile

## Development Workflow

1. Create a new feature branch from develop.
2. Implement the required feature.
3. Commit changes with meaningful commit messages.
4. Push the branch to GitHub.
5. Create a Pull Request targeting develop.
6. Perform code review and address comments.
7. Merge the Pull Request into develop.
8. Merge develop into main for releases.

## Pull Request Guidelines

- Use clear and descriptive titles.
- Provide a brief description of the changes.
- Ensure the feature is tested before creating a PR.
- Request review before merging.
- Resolve merge conflicts before approval.

## Commit Message Examples

- feat: add login page
- feat: add dashboard page
- feat: add profile page
- fix: resolve merge conflict
- docs: update project documentation

## Release Process

1. Merge all approved changes into develop.
2. Merge develop into main.
3. Create a version tag.
4. Push the tag to GitHub.

Example Release:

**v1.0 – First Stable Release**

## Code Review

All contributions should be reviewed before merging. Reviewers should verify:

- Code quality
- Functionality
- Readability
- Documentation updates

## Branch Protection

The main branch is protected using GitHub branch protection rules. Changes to the main branch must be made through Pull Requests.
