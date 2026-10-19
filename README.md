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

Lessons Learned

What I learned: I learned how identity and access management (IAM) supports the employee lifecycle, including onboarding, role changes, and offboarding. I also learned why lease privilege matters and why disabling an account does not, by itself, prove that access to connected applications, active sessions, and tokens have been removed.

What I found difficult: Distingushing between what a fictional access record confirms and what still needs verification was an important challenge. For example, the former employee record showed a disabled account, but I could not confirm actual sign-in prevention or removal of connected application access because I did not use a live identity platform.

What I would improve: I would test these procedures in an authorized lab environment, verify access removal in connected applications, and capture sanitized evidence of the results. I would also expand the least-privilege review to investigate whether employees have access that is unnecessary for their assigned roles.

Limitations
This is a process-design exercise. It does not create or disable real accounts, revoke sessions, or prove a technical control is enforced by a cloud identity provider.

Disclaimer
All names and access records in this repository are fictional. Do not add real credentials, tokens, employee records, or confidential information.

