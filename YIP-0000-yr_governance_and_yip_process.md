# YIP-0000 — Yr Governance and YIP Process

**Author:** Matheus Araújo - @mwtheus
**Status:** Accepted
**Type:** process
**Created:** 2025-01-01

---

## 1. Summary

This document defines how the Yr Improvement Proposal (YIP) process works,
including proposal format, review, acceptance, and record maintenance.

---

## 2. Goals of the YIP System

- Provide a clear, minimal, lightweight system for proposing changes.
- Avoid unnecessary bureaucracy.
- Keep the direction of Yr transparent and documented.
- Centralize decisions across the Yr ecosystem (language + official tools).

---

## 3. YIP Lifecycle

### 3.1 Draft
A new YIP, open for comments and refinement.

### 3.2 Accepted
Approved by the Yr Core Team.
Implementation is planned.

### 3.3 Rejected
Not approved for inclusion.
The reasoning should be documented.

### 3.4 Superseded
Replaced by a newer YIP.

### 3.5 Completed
Fully implemented and released.

---

## 4. YIP Types

- **language** — Syntax, compilation rules, new constructs.
- **process** — Governance decisions, release processes, YIP changes.
- **informational** — Non-binding design notes.
- **stdlib** — Future built-in Yr library proposals.

---

## 5. How to Create a YIP

1. Copy `YIP-####-title_here.md`
2. Replace `####` with the next free number
3. Replace `title_here` with the YIP title
4. Fill out all sections
5. Open a pull request

---

## 6. Decision Making

The **Yr Core Team** reviews and accepts/rejects YIPs.
Community feedback is encouraged but the Core Team decides the final outcome.

---

## 7. Versioning

YIPs are immutable once **Accepted**, except for:
- Typo fixes
- Clarifications
- Marking as **Completed** or **Superseded**