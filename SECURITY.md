# Security Policy

The Tekton project takes security seriously. We appreciate your efforts to
responsibly disclose any security vulnerabilities you find.

## Supported Versions

The Tekton project maintains four LTS release branches for each project,
resulting in an overall support window of approximately one year. Security
fixes are backported to all supported LTS releases. See the
[Tekton support policy](https://github.com/tektoncd/community/blob/main/releases.md#support-policy)
for details.

## Threat Model

For a detailed overview of our security architecture, trust boundaries, and potential threats, please refer to the specific Threat Model for each project:

* **Tekton Pipeline:** [Pipeline Security Threat Model](https://github.com/tektoncd/pipeline/blob/main/docs/security-threat-model.md)

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

To report a vulnerability, please use
[GitHub Security Advisories](https://github.com/tektoncd/pipeline/security/advisories/new)
on the affected repository. If you are unsure which repository is affected,
use the [pipeline](https://github.com/tektoncd/pipeline/security/advisories/new)
repository.

Alternatively, you can email the
[Tekton Vulnerability Management Team (VMT)](https://github.com/orgs/tektoncd/teams/tekton-vmt)
at **tekton-vmt\[at\]googlegroups.com** with a description of the issue, the steps you
took to create the issue, affected versions, and, if known, mitigations for
the issue.

## Response Process

Our vulnerability management team will respond within **3 working days** of
your report. If the issue is confirmed as a vulnerability, we will open a
Security Advisory.

This project follows a **90 day disclosure timeline**.

1. Confirm the vulnerability and determine affected versions
2. Develop and test a fix
3. Release patches for all supported versions
4. Publish a [GitHub Security Advisory](https://github.com/tektoncd/pipeline/security/advisories)
   with a CVE identifier

## Disclosure Policy

We follow a coordinated disclosure process. We ask that you:

- Allow us reasonable time to investigate and address the vulnerability
  before public disclosure
- Avoid exploiting the vulnerability beyond what is necessary to
  demonstrate it
- Do not access or modify other users' data

## Past Security Advisories

Security advisories for Tekton projects are published on the respective
GitHub repositories:

- [Tekton Pipeline](https://github.com/tektoncd/pipeline/security/advisories)
- [Tekton Chains](https://github.com/tektoncd/chains/security/advisories)
- [Tekton Triggers](https://github.com/tektoncd/triggers/security/advisories)
- [Tekton Operator](https://github.com/tektoncd/operator/security/advisories)
- [Tekton Dashboard](https://github.com/tektoncd/dashboard/security/advisories)
