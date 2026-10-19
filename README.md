IAM User Lifecycle Lab

Overview
This beginner-friendly portfolio project documents identity lifecycle processes for a fictional company, Northstar Solutions. It demonstrates how access should be requested, approved, provisioned, changed, reviewed, and removed.

Objectives
- Explain onboarding, role changes, and offboarding.
- Apply least privilege and role-based access control (RBAC).
- Document verification steps and evidence.
- Identify risks created by stale or excessive access.

Environment and Tools
- GitHub for version-controlled documentation
- Markdown for procedures
- CSV for fictional sample data
- No production accounts or real employee information are used

Repository Contents
- `docs/onboarding-procedure.md` — new employee account workflow
- `docs/access-change-procedure.md` — job or permission changes
- `docs/offboarding-procedure.md` — termination workflow
- `examples/fictional-user-access.csv` — fictional access inventory
- `evidence/test-results.md` — sample test cases and results

Security Principles
- Least privilege: grant only access required for assigned duties.
- Approval and traceability: access changes should be authorized and recorded.
- Timely deprovisioning: remove access promptly when it is no longer needed.
- Separation of duties: sensitive approvals and administration should not be concentrated unnecessarily.
- Verification: confirm that changes worked and retain appropriate audit evidence.

Testing and Results
See `evidence/test-results.md`. The cases are tabletop/documentation exercises, not tests against a real identity platform.

Limitations
This is a process-design exercise. It does not create or disable real accounts, revoke sessions, or prove a technical control is enforced by a cloud identity provider.

Lessons Learned
Update this section after completing the exercise. Describe what you learned, what you found difficult, and what you would improve.

Disclaimer
All names and access records in this repository are fictional. Do not add real credentials, tokens, employee records, or confidential information.

