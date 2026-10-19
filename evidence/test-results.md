Tabletop Test Results

These are simulated process checks using fictional records. They do not represent tests performed against a live identity platform.

| Test ID | Scenario | Expected result | Sample result | Status |
|---|---|---|---|---|
| T-01 | New employee request has valid approval | Access is provisioned only after approval | Procedure requires approval verification | Pass (document review) |
| T-02 | New employee requests finance access but role does not require it | Unapproved access is not granted | Least-privilege rule denies extra access | Pass (document review) |
| T-03 | Employee changes departments | Old unneeded access is removed and new access is approved | Role-change procedure includes both steps | Pass (document review) |
| T-04 | Employee leaves company | Sign-in is disabled and access removal is verified | Offboarding procedure includes verification | Pass (document review) |
| T-05 | Account disablement fails | Issue is escalated and tracked to resolution | Procedure requires escalation for failed steps | Pass (document review) |

Next Improvements
- Repeat these cases in an authorized test tenant.
- Capture sanitized screenshots of configuration and test results.
- Add timestamps and evidence references from the lab environment.
- Record any failures honestly and document corrective actions.

Additional Test: Former Employee Access Review

| Test ID | Scenario | Expected result | Sample result | Status |
|---|---|---|---|---|
| T-06 | Review a former employee account in the fictional access inventory. | Account is disabled, and removal of connected application access is verified. | Riley Placeholder (U1005) is marked Disabled. The record flags access removal for verification, but no live identity platform or connected applications were tested. | Partially verified (fictional record review)

Finding: The sample inventory identifies the former employee account as disabled, but this alone does not prove that all application access, active sessions, or tokens have been removed.

Recommended follow-up: In an authorized test environment, verify sign-in is blocked, connected application access is removed, and active sessions or tokens are revoked where supported. Record the results and evidence without including real credentials or sensitive user data.

