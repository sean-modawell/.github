# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this repository, please report it privately rather than opening a public issue.

**Preferred method:** [GitHub Security Advisories](../../security/advisories/new) for this repository — this creates a private discussion thread with the maintainer.

**Alternative:** Email **[sean.modawell@gmail.com]** with:

- A description of the vulnerability and its potential impact
- Steps to reproduce (proof-of-concept code, request/response samples, etc.)
- Any relevant environment details (dependency versions, config)

Please do not disclose the issue publicly (including in issues, PRs, or discussions) until it has been reviewed and, if applicable, patched.

## Response Expectations

This is a portfolio/template repository maintained by a single developer, not a production system handling live data. As such:

- I aim to acknowledge reports within **5 business days**.
- Confirmed vulnerabilities will be patched on a best-effort basis, prioritized by severity.
- Credit will be given to the reporter in the fix's changelog/commit, unless you prefer to remain anonymous.

## Scope

This repository contains **integration templates and case studies** meant to demonstrate patterns, not production-hardened services. A few scope notes:

- Sample credentials, API keys, and payloads in this repo are **fake/mock data** — do not reuse them, and do not report them as leaked secrets.
- Case studies may intentionally simplify auth, error handling, or validation for clarity. If you spot a simplification that could mislead someone into an insecure production implementation, that's a valid and welcome report — even if it's not an exploitable vulnerability in this repo itself.
- Vulnerabilities in third-party dependencies should be reported upstream, but flagging them here (e.g., via `pip-audit` or Dependabot alerts) is  also appreciated.

## Supported Versions

As a template/reference repository rather than a versioned release, security fixes are applied to the `main` branch only.

| Branch | Supported |
| --- | --- |
| main | ✅ |
