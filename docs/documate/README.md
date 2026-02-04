# Project Architecture

## Run Metadata

| Field | Value |
|-------|-------|
| Run ID | `f19334d7-d986-493c-8757-9e0ed3d98ae2` |
| Repository | `BelaSiemens/documate-test-target` |
| Commit | `54490375c9f6a398ff16aee52902160691989ae2` |
| Mode | `annotated` |
| Generated | 2026-02-04T22:00:25.370Z |
| Confidence | Annotated |

*Auto-generated documentation from source code analysis.*

## Truth Sources

**Support Level:** Authoritative (100% evidence coverage)

| Source | Status |
|--------|--------|
| TypeORM Decorators | ✓ Extracted |
| Route Definitions | ✗ Not detected |
| Migrations | ✗ Not found |
| Constraints | ⚠ Partial (from decorators only) |

**Missing Truth Sources:** migrations (constraints may be incomplete), Route definitions

### Confidence per Entity

| Entity | Confidence | Evidence Coverage | Source |
|--------|------------|-------------------|--------|
| User | ✓ Verified | 100% (6/6) | `User.ts:L3` |

## Entities

### User
*Source: `User.ts:L3-L19`*
*Table: `users`*

| Column | Type | Constraints |
|--------|------|-------------|
| id | string | PK, AUTO, NOT NULL |
| email | string | UNIQUE, NOT NULL |
| name | string | NULL |
| createdAt | Date | NOT NULL |
| updatedAt | Date | NOT NULL |

*Has timestamp columns (createdAt/updatedAt)*

## API Routes

*No routes extracted. The codebase may use a routing pattern not currently detected.*

## Enumerations

*No enums extracted.*

## Model Gaps & Assumptions

*The following items were detected but require clarification or are incomplete:*
