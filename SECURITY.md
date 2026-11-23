# Security Policy

## Reporting security issues

Do not post secrets, customer data, or exploitable security details in public issues. Contact the project owner privately using a verified channel.

## Baseline safeguards

- Never commit API keys, access tokens, passwords, cloud credentials, or customer lead records.
- If a secret is exposed, revoke/rotate it; deleting the Git commit is not sufficient.
- Only collect customer information through a secure, tested endpoint.
- Use HTTPS, server-side validation, spam protection, and least-privilege credentials for any future backend.
- Apply relevant data retention, consent, and privacy practices before enabling real lead capture.
- Review dependency and deployment security whenever build or hosting tools are introduced.

This document does not imply that a formal penetration test has been performed.
