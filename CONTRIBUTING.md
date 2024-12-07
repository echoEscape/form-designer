# Contributing to Waypoint

First off, thank you for considering contributing to **Waypoint**! Contributions are what make open-source projects thrive. Whether you're reporting a bug, suggesting a new feature, improving documentation, or contributing code, your input is greatly appreciated.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [How to Contribute](#how-to-contribute)
    - [Report Bugs](#report-bugs)
    - [Suggest Features](#suggest-features)
    - [Submit Code Changes](#submit-code-changes)
3. [Development Setup](#development-setup)
4. [Style Guide](#style-guide)
5. [Pull Request Process](#pull-request-process)
6. [Community and Support](#community-and-support)

---

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/). By participating, you are expected to uphold this code.

---

## How to Contribute

### Report Bugs

If you encounter a bug, please open an issue on the [GitHub Issue Tracker](https://github.com/echoEscape/waypoint/issues) and include:

- A clear and descriptive title.
- Steps to reproduce the problem.
- The expected behavior.
- Any relevant screenshots or logs.

### Suggest Features

Have an idea for a new feature? Great! Open an issue and provide:

- A detailed description of the feature.
- Any examples or mockups to illustrate your suggestion.
- Why this feature would be useful.

### Submit Code Changes

Code contributions are welcome! To submit changes:

1. Fork the repository.
2. Create a new branch for your changes.
3. Follow the [Style Guide](#style-guide).
4. Test your changes thoroughly.
5. Submit a pull request (PR) following the [Pull Request Process](#pull-request-process).

---

## Development Setup

Follow these steps to set up the development environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/echoEscape/waypoint.git
    cd waypoint
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Run the development server:
    ```bash
    ng serve
    ```
4. Open the application in your browser at `http://localhost:4200`.

---

## Style Guide

### Code Formatting

- Use **Prettier** for consistent formatting. Run `npm run format` before committing.
- Use **TypeScript** conventions: strict types, camelCase variables, and PascalCase for classes.
- Follow the [Angular Style Guide](https://angular.dev/style-guide).

### Commit Messages

Use the [Conventional Commit](https://www.conventionalcommits.org/) format:
<type>(<scope>): <short summary>

[optional body]

[optional footer(s)]

#### Example:

feat(waypoint): add drag-and-drop feature to canvas fix(ui): correct alignment of input fields in preview mode
**Commit Types:**

- **feat**: A new feature.
- **fix**: A bug fix.
- **docs**: Documentation changes only.
- **style**: Changes that do not affect functionality (e.g., formatting, whitespace).
- **refactor**: Code changes that neither fix a bug nor add a feature.
- **test**: Adding or updating tests.
- **chore**: Maintenance changes, such as dependency updates.

### Testing

- Write unit tests using Jest for any new functionality.
- Run all tests before submitting a PR:
    ```bash
    npm run test
    ```
- For E2E tests, use Cypress:
    ```bash
    npm run e2e
    ```

---

## Pull Request Process

1. Ensure your changes pass all tests and adhere to the project’s style guide.
2. Submit your pull request against the `main` branch.
3. Include a clear description of the changes made and reference related issues, if applicable.
4. The pull request will be reviewed by maintainers. You may be asked to make changes before it’s merged.
5. Once approved, your changes will be merged and included in the next release.

---

## Community and Support

If you have any questions or need help, feel free to:

- Open a [GitHub Discussion](https://github.com/echoEscape/waypoint/discussions).
- Report an issue on the [GitHub Issue Tracker](https://github.com/echoEscape/waypoint/issues).
