# Project Structure Standard

**Version:** 1.0  
**Owner:** VYNTRAX Intelligent Software

---

# Purpose

This document defines the standard folder structure adopted by all VYNTRAX software projects.

The objective is to ensure consistency, maintainability and scalability across every repository.

---

# Standard Structure

```
project-name/
│
├── public/
│
├── src/
│   ├── app/
│   ├── assets/
│   ├── components/
│   │   ├── common/
│   │   ├── layout/
│   │   ├── ui/
│   │   └── features/
│   │
│   ├── hooks/
│   ├── services/
│   ├── api/
│   ├── lib/
│   ├── contexts/
│   ├── store/
│   ├── types/
│   ├── utils/
│   ├── styles/
│   ├── constants/
│   ├── config/
│   ├── pages/
│   └── tests/
│
├── docs/
├── scripts/
├── .github/
├── package.json
├── tsconfig.json
├── vite.config.ts
├── README.md
└── LICENSE
```

---

# Folder Responsibilities

## app/

Application entry point and routing.

---

## assets/

Static assets such as images, fonts and icons.

---

## components/

Reusable UI components.

### common/

Generic components shared across the application.

### layout/

Navbar, Sidebar, Footer, Header and layout components.

### ui/

Design System components.

### features/

Components specific to business features.

---

## hooks/

Reusable custom React hooks.

---

## services/

Business logic and communication with external services.

---

## api/

API clients and endpoint definitions.

---

## lib/

Shared libraries and helper integrations.

---

## contexts/

React Context providers.

---

## store/

Global state management.

---

## types/

Shared TypeScript interfaces and types.

---

## utils/

Pure utility functions.

---

## styles/

Global styles and theme configuration.

---

## constants/

Application constants.

---

## config/

Environment configuration and application settings.

---

## tests/

Unit, integration and end-to-end tests.

---

# Naming Convention

Folders

- lowercase

Examples

components

services

hooks

Files

Use PascalCase for React components.

Example

DashboardCard.tsx

Use camelCase for utilities.

Example

formatCurrency.ts

Use kebab-case for folders when appropriate.

---

# Principles

- Keep components small.
- Separate UI from business logic.
- Avoid duplicated code.
- Prefer composition over inheritance.
- Write reusable modules.
- Every project should follow the same structure.

---

# Future Evolution

This standard will evolve as the engineering platform grows.

Changes must be documented through Architecture Decision Records (ADR).

---

**Maintained by VYNTRAX Intelligent Software**
