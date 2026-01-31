# Windows Event Log Hunt Lab

This project demonstrates basic Windows Event Log analysis for security investigation and troubleshooting.

## Objective
To collect and analyze Windows Event Logs in order to answer specific investigative questions related to user activity and system behavior.

## Scope
- Local Windows system
- Training environment only
- No production or sensitive data

## Tools
- Windows Event Viewer

## Investigation Questions

### Primary Questions
1. Were there failed logon attempts?
2. Were there successful logons outside normal hours?
3. Were any system errors or warnings occurring repeatedly?
4. Were there any account-related changes?

### Secondary (Follow-Up) Questions
These questions would be investigated if suspicious activity is identified during initial review.

1. Were there any privilege escalation events?
2. Were services started or stopped unexpectedly?
3. Were audit logs cleared or modified?
4. Did the same account authenticate from multiple sources?

