<!--
Sync Impact Report:
- Version change: None (initial fill) → 1.0.0
- List of modified principles:
  - Test-Driven Development (TDD) (Added)
  - Modern Python & Type Hinting (Added)
  - Code Readability & Maintainability (Added)
  - Architectural Decision Records (ADRs) (Added)
  - OOP Principles: SOLID, DRY, KISS (Added)
- Added sections:
  - Technical Stack
  - Quality Requirements
- Removed sections: None
- Templates requiring updates:
  - .specify/templates/plan-template.md (✅ updated)
  - .specify/templates/spec-template.md (✅ updated)
  - .specify/templates/tasks-template.md (✅ updated)
  - .gemini/commands/sp.adr.toml (✅ updated)
  - .gemini/commands/sp.analyze.toml (✅ updated)
  - .gemini/commands/sp.checklist.toml (✅ updated)
  - .gemini/commands/sp.clarify.toml (✅ updated)
  - .gemini/commands/sp.constitution.toml (✅ updated)
  - .gemini/commands/sp.git.commit_pr.toml (✅ updated)
  - .gemini/commands/sp.implement.toml (✅ updated)
  - .gemini/commands/sp.phr.toml (✅ updated)
  - .gemini/commands/sp.plan.toml (✅ updated)
  - .gemini/commands/sp.specify.toml (✅ updated)
  - .gemini/commands/sp.tasks.toml (✅ updated)
  - README.md (⚠ not found)
- Follow-up TODOs: None
-->
# Calculator Project Constitution

## Core Principles

### I. Test-Driven Development (TDD)
All new features and bug fixes MUST be developed using a Test-Driven Development (TDD) approach. Tests MUST be written before implementation, pass when the implementation is complete, and strictly follow the Red-Green-Refactor cycle.

### II. Modern Python & Type Hinting
All Python code MUST use Python 3.12 or newer. Type hints MUST be used comprehensively across the entire codebase to improve readability, maintainability, and error detection.

### III. Code Readability & Maintainability
Code MUST be clean, easy to read, and follow established Python style guides (e.g., PEP 8). Complexity MUST be minimized, and code SHOULD be refactored regularly to ensure high maintainability.

### IV. Architectural Decision Records (ADRs)
Significant architectural decisions MUST be documented using Architectural Decision Records (ADRs). ADRs provide context, alternatives considered, and rationale for decisions, ensuring long-term project understanding.

### V. OOP Principles: SOLID, DRY, KISS
Object-Oriented Programming (OOP) principles including SOLID (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion), DRY (Don't Repeat Yourself), and KISS (Keep It Simple, Stupid) MUST be applied consistently throughout the codebase.

## Technical Stack

- Python 3.12+: Primary language for all development.
- UV package manager: Used for dependency management and project environments.
- pytest: The designated framework for all unit and integration testing.
- Git: All project files MUST be managed under version control using Git.

## Quality Requirements

- Test Coverage: All implemented features MUST have comprehensive test coverage, with a minimum target of 80% line coverage.
- Test Pass Rate: All tests MUST pass before any code can be merged into the main branch.
- Data Structures: Python `dataclasses` MUST be used for defining data structures to ensure clarity, immutability where appropriate, and type safety.

## Governance

This constitution defines the fundamental principles and standards for the Calculator Project.
- All Pull Requests (PRs) and code reviews MUST verify compliance with these principles.
- Any amendments to this constitution MUST be documented, approved by core contributors, and include a clear migration plan if changes are backward-incompatible.
- The versioning policy for this constitution follows Semantic Versioning (MAJOR.MINOR.PATCH).
- For day-to-day development guidance, refer to project-specific documentation (e.g., README.md).

**Version**: 1.0.0 | **Ratified**: 2025-11-23 | **Last Amended**: 2025-11-23