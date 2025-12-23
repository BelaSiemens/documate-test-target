# Project Architecture

## Run Metadata

| Field | Value |
|-------|-------|
| Run ID | `0670c989-1137-4a71-aeba-86707e2459c8` |
| Repository | `BelaSiemens/documate-test-target` |
| Commit | `8f04beec0109f426d4e29815fd6ec1b0a3f03914` |
| Mode | `annotated` |
| Generated | 2025-12-23T16:47:45.023Z |
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
*Source: `User.ts:L4-L19`*

| Column | Type | Constraints |
|--------|------|-------------|
| id | string | PK, AUTO, NOT NULL |
| email | string | UNIQUE, NOT NULL |
| name | string | NULL |

## API Routes

*No routes extracted. The codebase may use a routing pattern not currently detected.*

## Enumerations

*No enums extracted.*

## Model Gaps & Assumptions

*The following items were detected but require clarification or are incomplete:*
