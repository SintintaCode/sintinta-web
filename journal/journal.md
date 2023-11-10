# Project Development Journal - FE-Ink

## Installation

**Date:** 10-10-2023

**Details:**
- Initialized new Angular project using the command `ng new fe-ink`.
- This sets up the basic structure of the Angular application.

## Manual Deployment

**Date:** 10-10-2023

**Details:**
- Deployed the application manually using `rsync`.
- Command used: `rsync -avz -e "ssh -i /path/to/private/key" /path/to/source remote_user@remote_domain:/remote/path`
- This command synchronizes files from the local `dist/fe-ink` directory to the remote server at `sintinta.com`.

## Jest Migration

**Date:** 10-10-2023

**Details:**
- Migrated testing framework from Jasmine to Jest for better performance and simpler syntax.
- References:
  - [Migrate from Jasmine to Jest and Testing in Angular](https://dev.to/this-is-angular/migrate-from-jasmine-to-jest-and-testing-in-angular-286i)
  - [Testing Library Documentation](https://testing-library.com/docs/)

## GitHub Actions for Deployment

**Date:** 10-10-2023

**Details:**
- Set up GitHub Actions for continuous integration and deployment.
- Automates the deployment process upon code push to the repository.
- Reference: [How to Build and Deploy an Angular Application Directly from GitHub](https://betterprogramming.pub/how-to-build-and-deploy-an-angular-application-directly-from-github-a0aa5f28e6aa)

## PLESK Configuration

**Date:** 10-10-2023

**Details:**
- Configured PLESK for server management.
- Node logs location: `/var/log/passenger/passenger.log`

## Semantic Versioning and Conventions

**Date:** 10-10-2023

**Details:**
- Adopted Semantic Versioning for a systematic approach to version control.
- Followed Angular commit message format for better change tracking and release management.
- References:
  - [Angular Commit Message Format](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#-commit-message-format)
  - [Using Semantic Release with GitHub Actions](https://levelup.gitconnected.com/using-semantic-release-with-github-actions-c30d197829f1)
