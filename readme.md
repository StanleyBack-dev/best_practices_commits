# Commit Best Practices
---

## Summary

- [ABOUT THE PROJECT](#about-the-project)
  - [OVERVIEW OF COMMIT TAGS](#overview-of-commit-tags) 
    - [FEAT](#feat)
    - [FIX](#fix)
    - [DOCS](#docs)
    - [STYLE](#style)
    - [REFACTOR](#refactor)
    - [TEST](#test)
    - [CHORE](#chore)
    - [PERF](#perf)
    - [CI](#ci)
    - [BUILD](#build)
    - [REVERT](#revert)
    - [MERGE](#merge)
    - [HOTFIX](#hotfix)
    - [ENV](#env)
    - [I18N](#i18n)
    - [A11Y](#a11y)
    - [UX](#ux)
    - [SECURITY](#security)
    - [CONFIG](#config)
    - [WIP](#wip)
    - [RELEASE](#release)
    - [INIT](#init)
    - [DATA](#data)
    - [ANALYTICS](#analytics)
    - [DEPS](#deps)
- [CONTRIBUTIONS](#contributions)
- [CONTATOS](#contatos)
- [LICENSE](#license)

---

# About the Project

This project aims to demonstrate best practices for writing commit messages using specific tags. Well-written commit messages are essential for keeping the project history organized and easy to understand.

---

### Overview of Commit Tags

---

### FEAT

- **Description:**
The `feat` tag is used when adding a new feature to the project.

**Example of Commit:**

```bash
git commit -m "feat: add median calculation function"
```

---

### FIX

- **Description:**
The `fix` tag should be used to indicate that a bug was fixed.

**Example of Commit:**

```bash
git commit -m "fix: correct compound interest calculation error"
```

---

### DOCS

- **Description:**
Use `docs` for changes in documentation, such as README or other `.md` files.

**Example of Commit:**

```bash
git commit -m "docs: add installation instructions to README"
```

---

### STYLE

- **Description:**
The `style` tag is used for changes that do not affect the logic of the code, such as formatting, spacing, semicolons, etc.

**Example of Commit:**

```bash
git commit -m "style: format code according to ESLint"
```

---

### REFACTOR

- **Description:**
Use `refactor` when refactoring code. This tag is for changes that improve the structure of the code without changing its behavior.

**Example of Commit:**

```bash
git commit -m "refactor: optimize compound interest calculation function"
```

---

### TEST

- **Description:**
The `test` tag is used to add or correct tests, without altering production logic.

**Example of Commit:**

```bash
git commit -m "test: add tests for median calculation function"`
```

---

### CHORE

- **Description:**
Use `chore` for maintenance tasks, such as dependency updates or build configurations that do not affect production code.

**Example of Commit:**

```bash
git commit -m "chore: update npm dependencies"
```

---

### PERF

- **Description:**
Use `perf` for commits that improve code performance.

**Example of Commit:**

```bash
git commit -m "perf: improve search algorithm performance"
```

---

### CI

- **Description:**
Use `ci` for continuous integration-related changes, such as pipeline configurations and build scripts.

**Example of Commit:**

```bash
git commit -m "ci: configure script for running tests on CI"
```

---

### BUILD

- **Description:**
Use `build` for changes that affect the build system or external dependencies like npm packages, gradle, etc.

**Example of Commit:**

```bash
git commit -m "build: update Webpack version"
```

---

### REVERT

- **Description:**
Use `revert` to roll back a previous commit. It is usually followed by a reference to the commit being rolled back.

**Example of Commit:**

```bash
git commit -m "revert: revert commit abc1234"
```

---

### MERGE

- **Description:**
Use `merge` when you are integrating changes from one branch to another, usually during a branch merge.

**Example of Commit:**

```bash
git commit -m "merge: integrate branch feature/login"
```

---

### HOTFIX

- **Description:**
Use `hotfix`. Similar to fix, but used for urgent corrections in production.

**Example of Commit:**

```bash
git commit -m "hotfix: fix critical error in tax calculation"
```

---

### ENV

- **Description:**
Use `env` for changes related to environment variables or environment settings.

**Example of Commit:**

```bash
git commit -m "env: add environment variables to production environment"
```

---

### I18N

- **Description:**
Use `i18n` for changes related to internationalization and localization (i18n).

**Example of Commit:**

```bash
git commit -m "i18n: add Spanish language support"
```

---

### A11Y

- **Description:**
Use `a11y` for changes that improve project accessibility.

**Example of Commit:**

```bash
git commit -m "a11y: improve color contrast for accessibility"
```

---

### UX

- **Description:**
Use `ux` for changes that improve the user experience, but don't necessarily add new functionality.

**Example of Commit:**

```bash
git commit -m "ux: simplify user registration flow"
```

---

### SECURITY

- **Description:**
Use `security` for commits that improve project security.

**Example of Commit:**

```bash
git commit -m "security: fix XSS vulnerability in login form"
```

---

### CONFIG

- **Description:**
Use `config` for changes to configuration files or environment tweaks.

**Example of Commit:**

```bash
git commit -m "config: adjust Webpack configuration for production"
```

---

### WIP

- **Description:**
Use `wip` to indicate that work is still in progress and not ready to be finalized or revised. This tag is generally used for temporary commits that will be improved or revised later.

**Example of Commit:**

```bash
git commit -m "wip: start development of new UI"
```

---

### RELEASE

- **Description:**
Use `release` for commits that are related to the release of a new version of the project.

**Example of Commit:**

```bash
git commit -m "release: prepare version 1.0.0"
```

---

### INIT

- **Description:**
Use init for the initial commit of a project, where you are setting up the repository for the first time.

**Example of Commit:**

```bash
git commit -m "init: configure initial project structure"
```

---

### DATA

- **Description:**
Use `data` for changes that involve modifications to data files, such as seed changes, database migrations, etc.

**Example of Commit:**

```bash
git commit -m "data: update seeds with new test data"
```

---

### ANALYTICS

- **Description:**
Use `analytics` for changes related to data analysis, such as adding or modifying tracking tools.

**Example of Commit:**

```bash
git commit -m "analytics: add Google Analytics to project"
```

---

### DEPS

- **Description:**
Use `deps` to indicate updating, adding, or removing project dependencies.

**Example of Commit:**

```bash
git commit -m "deps: update lodash dependency to latest version"
```

---

### CONTRIBUTIONS

Welcome to contribute to this project! Here are the basic steps to get started:

1. **Repository Fork**
    - First, fork this repository to your GitHub account to have your own localized copy.

2. **Clone the Repository**
    - Then clone the repository to your local machine using the command:

 ```bash
 git clone https://github.com/StanleyBack-dev/best_practices_commits.git
 ```

1. **Create a Branch**
    - It is a good practice to create a new branch to work on your changes. This helps keep your commit history clean and organized. To create and switch to a new branch, use the command:

 ```bash
 git checkout -b your_branch_name
 ```

1. **Make Your Changes**
    - Now you can start making your changes to the code. Remember to follow the project's style guidelines and naming conventions.

2. **Test Your Changes Locally**
    - Before pushing your changes, be sure to test them locally to ensure everything is working as expected.

3. **Submit your Changes**
    - When you're ready to share your changes, add them to your current branch and push to GitHub:

 ```bash
 git add .
 ```
 ```bash
 git commit -m "fix: short description of your changes"
 ```
 ```bash
 git push origin your_branch_name
 ```


1. **Open a Pull Request**
    - Finally, go to your fork's GitHub page and click "New pull request". Select the branch that contains your changes and submit the pull request to this thread.

### Additional Notes

- **Discussions**
   - Feel free to open an issue if you need to discuss something before making changes or if you encounter any problems along the way.

- **Compliance**
   - Ensure that all contributions follow the project's style guidelines and coding conventions.

Thank you very much for helping to improve this project!

---

### CONTACTS

If you would like to contact me to discuss the project or any related matter, please feel free to use the following contact methods:

- 📧 **E-mail**: contactstanley.devtech@gmail.com
- 📷 **Instagram**: [@stanley.devtech](https://www.instagram.com/stanley.devtech/)

---

### LICENSE

This project is licensed under the [MIT License](LICENSE).