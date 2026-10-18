# Release Notes — Investigative Technology Preview

**Public documentation date:** 18 October 2026  
**Private platform:** R2 authentication + R3 assessment/reporting + R4/R4.2 experimental deep-source inspection

## Demonstrated in the private environment

- Authenticated investigator login, with server-side credentials and protected actions.
- Public repository discovery and family-based correlation.
- Explainable rule-based repository triage with preserved artifact associations.
- Private JSON evidence and SHA-256 reporting, plus print-ready report output.
- At least one verified commit-pinned public source file during an earlier R4 trial.

## Known limitations — disclosed, not concealed

- In the first R4 trial, two GitHub API 404 responses prevented two of three planned inspections; only one repository returned a verified source file.
- In the subsequent R4.2 evidence-first trial, the scheduler attempted nine repositories but returned **0 of 3 targeted verified inspections**. The bounded scheduler and error reporting operated; the substantive inspection objective was **not met**.
- The interface has also shown a temporary inconsistency in which the user header displayed an authenticated administrator while a family-list request returned a login-required error. Root cause has not been established.
- Public source and APK binary analysis remain incomplete; no trustworthy benign/malicious classifier has been validated.
- Printed report table formatting and source coverage explanations require further improvement.

## Public release scope

Documentation and synthetic demonstration material **only**. No private backend code, database, captured files, credentials, non-public investigations or automated malicious-payload processing tools are distributed.

## Next engineering objectives

Resolve session-state inconsistencies, strengthen live GitHub source eligibility and fallback, incorporate investigator-selected targets and historical evidence more effectively, and subject classification rules to measured false-positive/false-negative testing.
