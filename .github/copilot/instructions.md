# Copilot Instructions (Enterprise Banking Context)

These instructions apply to all Copilot interactions in this repository.

## Mandatory Principles

- Assume **regulated banking environment**
- Security, auditability, and traceability are mandatory
- Prefer explicit, verbose, and readable implementations
- Never optimize at the cost of clarity or compliance

## Architecture Expectations

- Layered architecture (API / Domain / Application / Infrastructure)
- Clear bounded contexts
- Dependency inversion enforced

## Forbidden Patterns

- Hard-coded secrets or credentials
- Implicit magic behavior
- Undocumented business logic
