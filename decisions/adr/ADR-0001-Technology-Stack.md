# ADR-0001 – Official Technology Stack

**Status:** Accepted

**Date:** 2026-10-13

**Owner:** VYNTRAX Intelligent Software

---

# Context

As VYNTRAX grows, multiple software projects will be developed in parallel.

To reduce maintenance costs, improve developer productivity and ensure consistency across projects, the company requires a standardized technology stack.

Without a defined standard, projects may adopt different frameworks, libraries and architectural patterns, increasing technical debt and reducing code reuse.

---

# Decision

VYNTRAX adopts the following technologies as its official engineering stack.

## Frontend

- React
- Next.js
- TypeScript
- Tailwind CSS

---

## Backend

- Python
- FastAPI
- Node.js (when appropriate)

---

## Database

- PostgreSQL
- Supabase

---

## Infrastructure

- GitHub
- Cloudflare
- Vercel

---

## Artificial Intelligence

- OpenAI
- Google Gemini
- Anthropic Claude

---

# Rationale

These technologies were selected because they provide:

- Excellent community support
- Strong documentation
- Long-term stability
- High developer productivity
- Scalability
- Modern development practices

---

# Consequences

Benefits:

- Consistent architecture
- Faster onboarding
- Easier maintenance
- Reusable components
- Simplified deployments

Trade-offs:

- Team members should prioritize learning the official stack.
- Alternative technologies require architectural review before adoption.

---

# Future Revisions

The technology stack should be reviewed periodically.

Major changes must be documented in a new ADR instead of modifying this document.

---

**Approved by**

VYNTRAX Intelligent Software
