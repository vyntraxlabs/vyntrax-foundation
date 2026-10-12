# Git Workflow Standard

**Version:** 1.0  
**Owner:** VYNTRAX Intelligent Software

---

# Purpose

This document defines the official Git workflow adopted by VYNTRAX.

The goal is to maintain a clean, predictable and scalable development process across every repository.

---

# Branch Strategy

The following branches are officially recognized.

## main

Production-ready code only.

Rules:

- Protected branch
- Direct commits are not allowed
- Merge only through Pull Requests

---

## develop

Integration branch.

All completed features are merged here before reaching production.

---

## feature/<name>

Used for new functionality.

Examples:

feature/login

feature/dashboard

feature/payment-system

---

## fix/<name>

Bug fixes that are not urgent.

Example:

fix/sidebar-overflow

---

## hotfix/<name>

Critical fixes applied directly to production.

Example:

hotfix/login-error

---

## release/<version>

Optional branch used for release preparation.

Example:

release/v1.0.0

---

# Commit Convention

We follow the Conventional Commits specification.

Examples:

feat: add authentication

fix: correct login validation

docs: update README

refactor: simplify dashboard service

style: improve formatting

test: add API tests

build: update dependencies

ci: improve GitHub Actions

---

# Pull Requests

Every Pull Request should:

- Have a clear description
- Reference related issues
- Pass automated checks
- Be reviewed before merging

---

# Code Reviews

Reviewers should verify:

- Readability
- Security
- Performance
- Tests
- Documentation
- Architecture consistency

---

# Merge Strategy

Preferred:

Squash and Merge

This keeps commit history clean.

---

# Branch Protection

The main branch should require:

- Pull Request
- At least one approval
- Passing CI
- No force push

---

# Versioning

Semantic Versioning (SemVer)

MAJOR.MINOR.PATCH

Example:

1.4.2

---

# Principles

Every commit should improve the project.

Avoid:

- Temporary commits
- Unclear messages
- Large unrelated changes
- Direct commits to production

---

**Maintained by VYNTRAX Intelligent Software**
