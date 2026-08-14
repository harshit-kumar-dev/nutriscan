# 🤝 Contributing to NutriScan

Thank you for taking the time to contribute to **NutriScan**! We welcome contributions from developers, designers, nutritional experts, and open-source enthusiasts.

---

## 📋 Table of Contents
- [Code of Conduct](#-code-of-conduct)
- [How to Contribute](#-how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Development Setup](#-development-setup)
- [Branching Strategy & Commit Guidelines](#-branching-strategy--commit-guidelines)
- [Coding Standards](#-coding-standards)

---

## 📜 Code of Conduct

This project and everyone participating in it is governed by the [NutriScan Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

---

## 🚀 How to Contribute

### Reporting Bugs

Before creating a bug report, please check the existing [GitHub Issues](https://github.com/harshit-kumar-dev/nutriscan/issues). If you find a new bug, please open a issue with:
- A clear and descriptive title.
- Steps to reproduce the issue.
- Expected vs. actual behavior.
- Screenshots or console log tracebacks if applicable.
- Environment details (Browser, OS, Node.js version).

### Suggesting Features

Feature requests are always welcome! When opening a feature request, please provide:
- A summary of the feature and why it would benefit users.
- Potential implementation details or mockups.

### Submitting Pull Requests

1. **Fork the Repository**: Create your own copy of NutriScan.
2. **Create a Feature Branch**: `git checkout -b feature/amazing-feature` or `fix/bug-fix`.
3. **Commit your changes**: Follow the [Commit Message Convention](#-branching-strategy--commit-guidelines).
4. **Push to GitHub**: `git push origin feature/amazing-feature`.
5. **Open a Pull Request**: Provide a clear explanation of your changes and reference any related issues.

---

## 🛠️ Development Setup

Refer to the [Setup Guide in README.md](README.md#-setup--installation-guide) to configure both the React Frontend and Node.js Backend locally.

```bash
# Clone your fork
git clone https://github.com/YOUR-USERNAME/nutriscan.git
cd nutriscan

# Setup Backend
cd backend && npm install

# Setup Frontend
cd ../frontend && npm install
```

---

## 🌲 Branching Strategy & Commit Guidelines

We follow standard Conventional Commits:

- `feat:` A new feature for the app.
- `fix:` A bug fix.
- `docs:` Documentation changes only.
- `style:` Code style/formatting fixes without functional changes.
- `refactor:` Code restructuring without changing external behavior.
- `test:` Adding or updating tests.
- `chore:` Updating build tasks, package dependencies, etc.

*Example:* `feat(scanner): add flash light toggle button to barcode scanner`

---

## 🎨 Coding Standards

- **Frontend (React)**: Use functional components with Hooks, clean prop structure, and modular Tailwind CSS classes.
- **Backend (Node/Express)**: Modular controller-service architecture. Handle async errors gracefully using try/catch blocks and proper HTTP status codes.
- **Formatting**: Format code with Prettier and follow ESLint rules before submitting PRs.

---

Thank you for building a healthier world with **NutriScan**! 🥗
