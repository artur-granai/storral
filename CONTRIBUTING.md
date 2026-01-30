# 🛠️ Contribution Guide for the Storral Project

> Step-by-step guide to report problems, suggest improvements, and contribute code and documentation to the Storral ecosystem.

---

## 📌 Golden Rule

> **1 commit = 1 intention**  
> Keep changes atomic and focused.  
> If you are fixing a bug and adding a feature, split them into two separate commits or pull requests.

---

## 1️⃣ 🐛 Issues – Report Problems or Suggest Improvements

Issues are used to track bugs, suggest improvements, and register questions.
They help keep the project organized and prioritize tasks.

- ✅ **Report a Bug:** Found an error? Describe the problem in as much detail as possible.
- ✅ **Suggest an Improvement:** Have an idea to improve the project? Share it!
- ✅ **Request Clarification:** Need help with the code or documentation? Open an issue.

📌 Before opening an issue, search if it already exists to avoid duplication:  
https://github.com/artur-granai/storral/issues

➕ **Open a new Issue:**  
https://github.com/artur-granai/storral/issues/new/choose

---

## 2️⃣ ⚙️ Pull Requests (PR) – Code Contribution

If you wish to contribute code, follow these guidelines to ensure organized, secure, and auditable development.

### Branch Strategy

- **`contrib`** 🌍 — **Community Entry Point**  
  All external Pull Requests (from forks) **must target this branch**.

- **`dev`** 🔒 — **Internal Staging**  
  Approved community contributions and internal work are integrated here.

- **`main`** 🔒 — **Stable Release**  
  Never accepts direct PRs. Only validated code promoted from `dev`.

### Workflow

1. **Fork** the repository.
2. Create a branch for your feature:  
   `git checkout -b feature/my-new-feature`
3. Commit your changes following the **Commit Rules** below.
4. Push to your branch:  
   `git push origin feature/my-new-feature`
5. Open a Pull Request targeting the **`contrib`** branch.

➕ **Create a new Pull Request:**  
https://github.com/artur-granai/storral/compare

---

## 3️⃣ 🧾 Commit Rules

We follow a strict commit convention to ensure traceability and clean project history.

---

## 2️⃣ ⚙️ Pull Requests (PR) – Code Contribution

If you wish to contribute code, follow these guidelines to ensure organized and secure development.

### Branch Strategy
- **`contrib`** 🌍: **Community Entry Point.** All external Pull Requests (from Forks) MUST target this branch.
- **`dev`** 🔒: **Internal Staging.** Where the team integrates approved community contributions and internal work.
- **`main`** 🔒: **Stable Release.** Never accept direct PRs. Only validated code promoted from `dev`.

### Workflow
1. **Fork** the repository.
2. Create a branch for your feature: `git checkout -b feature/my-new-feature`.
3. Commit your changes following the **Commit Rules** below.
4. Push to your branch: `git push origin feature/my-new-feature`.
5. Open a Pull Request targeting the **`contrib`** branch.

➕ **Create a new Pull Request:**
https://github.com/artur-granai/storral/compare

---

## 3️⃣ Commits Rules

We follow a strict convention to ensure traceability and automated changelog generation.

### 🔧 Commit Structure
```text
[type] (division) - Description (max 70 chars)

- Additional details (optional)
- List of relevant changes
- Reason for change or impact
```

### 🟧 Allowed Types (`[type]`)

| Type         | Description                                  | Example                                             |
| :----------- | :------------------------------------------- | :-------------------------------------------------- |
| `[init]`     | Project initialization or structural changes | `[init] (repo) - Initial folder structure`          |
| `[feat]`     | New feature                                  | `[feat] (firmware) - Implement offline signing`     |
| `[fix]`      | Bug correction                               | `[fix] (firmware) - Fix screen update issue`        |
| `[docs]`     | Documentation update                         | `[docs] (readme) - Update security best practices`  |
| `[security]` | Security improvements or critical fixes      | `[security] (wallet) - Enforce stronger encryption` |
| `[config]`   | System configuration changes                 | `[config] (boot) - Adjust boot parameters`          |
| `[refactor]` | Refactoring without changing behavior        | `[refactor] (power) - Optimize power management`    |

### 🏢 Divisions (`(division)`)

Specify the context/module of the change:
- `(storm)` - Governance, documentation, central repo
- `(engineering)` - Physical device, firmware, hardware
- `(labs)` - Applications, Wallet App, UX
- `(orbit)` - Node infrastructure, networking
- `(care)` - Support, recovery, educational content

### Examples
- `[feat] (labs) - Add biometric login support`
- `[fix] (engineering) - Correct pin entry timeout`
- `[docs] (storm) - Update contribution guidelines`

---

## 💛 Support the Project

In addition to contributing with code and ideas, you can financially support the **Storral Project**.

Check support options at:
- [`FUNDING.yml`](./.github/FUNDING.yml)
- **Sponsor** button on GitHub (when available)

Your collaboration helps keep the project active and evolving.

---

## 📌 Compliance Note

Any contribution that violates these rules may be:
- Rejected
- Reverted
- Requested to be rewritten (Squash/Rebase)

We value a clean history as part of the project's **security and auditability**.

---
🚀 Thank you for contributing!
For general questions or support, consult:
Start a discussion in the [Discussions tab](https://github.com/artur-granai/storral/discussions)

---

© 2026 Storral · All rights reserved. 

---
