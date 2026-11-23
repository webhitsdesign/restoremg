# Restore MG Project Baseline

**Recorded:** 2026-11-23  
**Repository:** https://github.com/webhitsdesign/restoremg  
**Source:** `main` at commit `81505c25dfc561f300ed395c012b5fd4d2e25166`  
**Baseline type:** Documentation and process only; no website behavior changes.

## Inventory

| Area | Baseline |
| --- | --- |
| Site | Single-page static HTML website |
| Implementation | `index.html` with embedded CSS and inline form handler |
| Libraries | None imported in the reviewed file |
| Pages | Services, process, why us, contact sections within one HTML page |
| Responsive | CSS grid, viewport metadata, and mobile nav adjustments |
| Theme | Light/dark preference support with manual theme variables |
| Lead capture | Not operational — browser-only success text |
| Tests | No automated test files in initial repository |
| CI/CD | No workflow files in initial repository |
| Hosting | Not identifiable from initial repository |
| Secrets | No secrets or credentials observed in initial tracked file |

## Known risks and action items

| Priority | Finding | Recommendation |
| --- | --- | --- |
| Critical | Form claims a request was received although nothing is transmitted | Connect a tested form provider/server endpoint; show success only on confirmed submission |
| High | Business/service claims are published without supporting records in repo | Verify licensing, insurance, certification, 24/7 coverage, and insurance-support language |
| High | No published privacy/consent or spam-abuse controls for future lead capture | Add appropriate notice, consent, validation, rate-limiting/spam protection |
| Medium | No CI and no automated tests | Add HTML linting, link checks, and a form integration smoke test |
| Medium | Hosting and deployment ownership not documented | Document production domain, provider, DNS, deployment method and rollback |
| Medium | No accessibility audit | Validate keyboard navigation, labels, semantic sections, contrast and focus states |
| Low | Styles are embedded in one file | Consider CSS extraction after functionality is stabilized |

## Baseline acceptance criteria

- Preserve `index.html` byte-for-byte.
- Establish clear documentation for setup, limitations, risk and review.
- Propose changes via a pull request targeting `main`.
- Do not deploy or activate advertising from this baseline task.
- Avoid adding unverified business phone numbers, emails, domain names or credentials.

## Release readiness checklist

- [ ] Contact form submits a test lead and downstream receipt is verified
- [ ] Real business contact methods and response SLA are confirmed
- [ ] All public claims are verified
- [ ] Privacy notice and lead-consent requirements are reviewed
- [ ] Mobile and desktop experience checked
- [ ] Accessibility review completed
- [ ] Hosting, deployment and rollback documented
- [ ] Changes approved before production deployment
