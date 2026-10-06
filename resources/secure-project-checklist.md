[← Back to Cybersecurity Track home](../README.md)


# 🔐 Secure Project Checklist

Use before you share a project, publish a repo, or demo. It supports the Build stage and the Cyber × Web project.

## Security requirements
- [ ] I wrote down what the app must protect and from whom
- [ ] I know who the users are and what each can do

## Secrets
- [ ] No passwords, tokens, keys or `.env` files in the repo or its history
- [ ] `.gitignore` covers credential and environment files
- [ ] Any leaked secret has been revoked and replaced

## Authentication and access
- [ ] Passwords are hashed, never stored in plain text
- [ ] Two-factor authentication on GitHub and cloud accounts
- [ ] Each person and app has only the access it needs
- [ ] Default and test passwords have been removed

## Code
- [ ] User input is validated and not trusted
- [ ] Error messages do not reveal sensitive details
- [ ] HTTPS is used for anything that leaves the machine

## Dependencies
- [ ] Packages are up to date and from trusted sources
- [ ] Dependabot or similar alerts are on

## Testing
- [ ] I tested **my own project** for common problems and fixed what I found
- [ ] I kept a short test report with before and after

## Data
- [ ] The project only collects data it needs
- [ ] Personal data is not in the repo or screenshots

If you find a serious problem in someone else's project, tell them privately and kindly. See the [security policy](https://github.com/GDG-TUM/.github/blob/main/SECURITY.md).
