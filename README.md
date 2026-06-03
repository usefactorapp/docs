# Factor Docs

Merge Risk Intelligence for Distributed Backend Systems.

Factor helps engineering teams understand what could break in production before a pull request is merged.

It analyzes pull requests in the context of your system and surfaces risks that traditional code review and CI miss.

---

## 🧠 What Factor does

Modern backend systems are complex, and most production issues are not caught by tests or CI.

Factor focuses on system-level risks, including:

- Hidden assumptions in code
- Failure scenarios under real conditions
- Cross-service and downstream impacts
- Missing validation and edge cases
- Business logic risks in critical workflows

---

## ⚙️ How it works

Factor runs automatically on every pull request after installation.

```text
PR opened or updated
        ↓
Factor analyzes code + repository context
        ↓
System-level risk analysis generated
        ↓
Results appear directly on the pull request
```

No manual triggers. No code changes required.

---

## 📚 Documentation

This repository contains the full documentation for Factor.

### Start here

- **[Overview](index.mdx)** — What Factor is and why it exists
- **[Quickstart](getting-started/quickstart.mdx)** — Get Factor running in 5 minutes
- **[How Factor Works](guides/how-factor-works.mdx)** — Technical breakdown of the analysis system

---

### Learn by example

- **[Example Reviews](examples/example-reviews.mdx)** — Real PR analyses
- **[Financial Systems](examples/financial.mdx)** — Risk in monetary logic
- **[Authentication](examples/authentication.mdx)** — Security-sensitive flows
- **[Background Jobs](examples/background-jobs.mdx)** — Async system risks
- **[API Contracts](examples/api-contract.mdx)** — Integration stability
- **[Data Migration](examples/data-migration.mdx)** — Schema and state changes

---

### Reference

- **[Verdicts](reference/verdicts.mdx)** — How to interpret risk levels
- **[FAQ](reference/faq.mdx)** — Common questions
- **[Security & Privacy](reference/security.mdx)** — Data handling and safety

---

## 🎯 Why Factor exists

Code review and CI are good at catching:

- syntax errors
- test failures
- style issues

But they often miss:

- system-level behavior changes
- hidden assumptions
- cascading failures across services
- real-world edge cases

Factor exists to surface those risks before merge time.

---

## 🚀 Get started

To start using Factor:

1. Install Factor on your GitHub account
2. Select repositories to enable
3. Open a pull request

Factor will automatically begin analyzing changes.

---

## 🔒 Security & trust

Factor is built for private source code environments.

- Only analyzes repositories you explicitly grant access to
- Does not use customer code for model training
- Does not expose code to other customers
- Follows GitHub permission boundaries

See full details in **Security & Privacy** docs.

---

## 💡 Outcome

With Factor, engineers don’t just review code.

They understand **production risk before it ships**.

```

---

# 🧠 Why this works

This README does 4 critical jobs:

### 1. Instant positioning
> Merge Risk Intelligence for Distributed Backend Systems

### 2. Immediate clarity
> what it does in 1–2 lines

### 3. Fast mental model
> PR → analysis → risk surfaced

### 4. Guided navigation
> tells users exactly what to click next

```
