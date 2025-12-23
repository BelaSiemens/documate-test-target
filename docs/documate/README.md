# Project Architecture

## Run Metadata

| Field | Value |
|-------|-------|
| Run ID | `89c8f16b-e21d-49cf-a282-ba461f80f792` |
| Repository | `BelaSiemens/documate-test-target` |
| Commit | `2a1e11ca0280390c592c61d390de06e47ecfd6c4` |
| Mode | `annotated` |
| Generated | 2025-12-23T19:02:25.814Z |
| Confidence | Annotated |

*Auto-generated documentation from source code analysis.*

## Truth Sources

**Support Level:** Partial

| Source | Status |
|--------|--------|
| TypeORM Decorators | ✓ Extracted |
| Route Definitions | ✗ Not detected |
| Migrations | ✗ Not found |
| Constraints | ⚠ Partial (from decorators only) |

**Missing Truth Sources:** migrations (constraints may be incomplete), Route definitions

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
