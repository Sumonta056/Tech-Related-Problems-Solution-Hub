Examples of commit types
Commit messages can vary depending on the task you are working on. Here are some common conventions for different scenarios:

feat : New Features

Description: Introduces a new feature or enhancement.

Example:
feat(auth): add login functionality.
feat(ui) : improve button desing
fix: Bug Fixes

Description: Fixe a bug in the codebase.

Example:
fix(api): resolve timeout issue
fix(ui) : correct alignment of navbar

docs: Documentation

Description: Updates or improvements to documents to documentation (README, code comments, etc.).

Example:
docs: update README with installation steps
docs(api): add missing function descriptions
style: Code Styling

Description: Changes that do not affect functionality (formatting, spacing, linting).
style: fix ESLint warnings
style: reformat code for consistency
perf: Performance Improvements

Description: Enhances performance without changing functionality.
perf: optimize database queries
perf(ui): reduce image loading time
refactor: Code Refactoring

Description: Improves code structure or readability without changing functionality.

refactor: simplify user validation logic
refactor(api): split large functions into smaller ones
test: Tests

Description: Adds or updates test cases.

Example:
test: add unit tests for login service
test(api): update integration tests for payment gateway
chore: Maintenance

Description: Miscellaneous tasks like dependency updates or build changes.

Example:
chore: update dependencies to latest versions
chore(ci): configure GitHub Actions for CI/CD
build: Build Changes

Description: Changes to the build system or external dependencies.

Example:
build: upgrade webpack to v5
build: add Babel support for modern JS features
ci: Continuous Integration

Description: Updates related to CI/CD pipelines or automation scripts.

Example:
ci: fix Dockerfile for deployment
ci: update GitHub Actions workflow
revert: Reverts

Description: Reverts a previous commit.

Example:
revert: revert "feat(auth): add login functionality"
BREAKING CHANGE : Breaking API/Functionality

Description: A commit introducing a breaking change in the codebase.
Usage: Add ! to the type or include BREAKING CHANGE \*\*\*\* in the footer.

Example:
feat(api)!: rename `getUser` to `fetchUser`

BREAKING CHANGE: `getUser` is replaced by `fetchUser` to improve naming consistency.
Git Commit Types Overview
