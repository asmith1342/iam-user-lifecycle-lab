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

