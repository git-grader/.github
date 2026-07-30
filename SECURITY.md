# Security Policy

GitGrader executes untrusted student code — we take security reports seriously.

## Reporting a vulnerability

**Do not open a public issue for security problems.**

Preferred: use GitHub's
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
on the affected repository ("Security" tab → "Report a vulnerability").

Alternatively, email **security@git-grader.org** with:

- A description of the issue and its impact
- Steps to reproduce (proof of concept if possible)
- Affected repository, version, or commit

## What to expect

- Acknowledgement within **72 hours**
- A triage decision and severity assessment within **7 days**
- Coordinated disclosure: we will agree on a timeline with you before
  publishing a fix and advisory, and credit you unless you prefer otherwise

## Scope

All repositories in the `git-grader` organization. Issues in the isolation /
sandboxing of grading runners are considered highest severity.
