# Contributing Guide

## 1. Overview

The Production-Grade-Resilience-Platform follows a controlled development
workflow designed to simulate production engineering practices.

All meaningful changes should be developed on a feature branch and merged
through a Pull Request.

---

## 2. Branching Strategy

The `main` branch represents the stable version of the project.

Do not develop directly on `main`.

Create a dedicated branch for each change.

### Branch naming

Use the following convention:

- `feature/<name>` — New functionality
- `fix/<name>` — Bug fixes
- `docs/<name>` — Documentation changes
- `refactor/<name>` — Code restructuring
- `test/<name>` — Test changes
- `ci/<name>` — CI/CD changes
- `infra/<name>` — Infrastructure changes

### Examples

```text
feature/application-health-check
feature/prometheus-monitoring
fix/database-connection
docs/disaster-recovery
ci/github-actions
infra/eks-cluster


