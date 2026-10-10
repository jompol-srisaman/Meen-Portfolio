# HFT Packing Control — Public Portfolio Demo Requirements

Status: FOUNDER-APPROVED SPECIFICATION, 2026-10-10
Linked private product repository: jompol-srisaman/HFT-Warehouse

## Portfolio navigation
Meen Portfolio landing -> organization/project collection -> HFT Packing Control case study -> Try Live Demo (separate Google Apps Script Demo Web App).
Public use of Home Fit Tools branding, screenshots and proprietary details remains subject to company authorization. Use redacted or generic branding if authorization has not been obtained.

## Real working Demo, fictitious data
- Full functional app, not clickable mockup: Record, Dashboard, Report, plus admin/user management reached within the approved navigation design.
- Uses independent demo backend and DEMO-ONLY Google Sheets data. No company/user-identifiable information, production endpoints or credentials.
- As Production changes, the Demo receives matching new features and fixes in the same release flow. This is a required parity gate.
- Record save/load/edit, server validation, role checks, metrics, audit, and data export must actually work against synthetic data.
- Demo must recover/reset to a clean reference dataset. Isolate visitor changes where feasible.

## Visible credential guide on Demo login
Display 3 clearly labeled sets of demo username/password in Thai, with each account's available capabilities:
- ADMIN — demo_admin / (demo-only seeded password): users, settings, Record, Dashboard, Report, audit, allowed exports
- MANAGER — demo_manager / (demo-only seeded password): Dashboard, Report, approved exports/audit, granted corrections
- STAFF — demo_staff / (demo-only seeded password): authorized data entry/edit and permitted summaries
Provide copy/fill aids as appropriate. Actual displayed passwords must be the exact seeded values accepted by Demo server, not arbitrary placeholders. Public passwords must NEVER be used by Production.
No open self-registration. Unknown username or incorrect password fails server-side with a generic message. Do not bypass authentication with a UI-only role selector.
For user-management scenarios requiring newly created demo accounts, confine them to a disposable visitor-scoped sandbox; they do not become global published credentials.

## Protection and honesty
Published demo credentials are by definition public; compensate with strict separation from Production, per-visitor isolation, quotas/rate-limits, expiring sessions, and account/data reset. Authentication must still actually work.
Do not publish HFT live data, internal IDs, sensitive source, test evidence containing real people, or secrets.
Case studies can describe design/process and verified non-confidential results. Do not imply the Demo represents live operations.

## Acceptance
Valid role pair logs in; invalid pair is denied; every demo role's permitted functions work; forbidden operations fail server authorization; dashboard/report reflect Record updates; safe export/audit function; reset does not affect others; new Production feature is visible in Demo after its release.

## Implementation status
Specification only, not yet a deployed Pages site or working demo.
