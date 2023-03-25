# Security Policy

The Pion project is committed to the highest degree of secure computing. We take a number of measures to guarantee the
security of the Pion codebase and all of our users.

If you believe you have found a security vulnerability in any Pion repository, please report it to us as described
below.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report by sending an email to secure@pionframework.io. If possible, encrypt your message with our PGP
key. Please download it here. You should receive a response within 24 hours, or the next business day if submitted on
a weekend. Please include the requested information listed below (as much as you can provide) tp help us better
understand the nature and scope of the possible issue:

* Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
* Full paths of source file(s) related to the manifestation of the issue
* The location of the affected source code (tag/branch/commit or direct URL)
* Any special configuration required to reproduce the issue
* Step-by-step instructions to reproduce the issue
* Proof-of-concept or exploit code (if possible)
* Impact of the issue, including how an attacker might exploit the issue\

This information will help us triage your report more quickly.

### Preferred Languages

We prefer all communications to be in English.

## Security Practices

### Code Validation

Pull requests are validated using Sonar Cloud for security and other code issues. Releases will never be made with
versions that have suspected security issues.

### Contributions

All contributors are required to have a verified email address and GPG key, and all commits must be GPG-signed.
