# Restore MG LLC Website

A lightweight, responsive website for Restore MG LLC, highlighting emergency property restoration services.

## Current baseline

- **Application:** Static HTML/CSS website
- **Entry point:** `index.html`
- **Framework/build:** None required
- **Hosting:** Not configured in this repository
- **Baseline date:** 2026-11-23
- **Baseline branch point:** `main` at `81505c25dfc561f300ed395c012b5fd4d2e25166`

### Site sections

- Emergency response hero
- Water, fire/smoke, mold, storm, cleaning, and reconstruction services
- Four-step restoration process
- Company positioning
- Contact/estimate request form

## Getting started

Open `index.html` in a browser. For local HTTP testing, run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000/.

## Important limitations

**The contact form is currently a front-end demonstration only.** Its inline `onsubmit` handler prevents submission and replaces the form with a success message. It does **not** send emails, save leads, or notify Restore MG. Do not treat leads as captured until a working back end or form provider is integrated and tested.

The website currently includes business claims such as 24/7 availability, insurance assistance, certifications, and licensing/insurance. Confirm these claims with the business owner before production use.

## Suggested release workflow

1. Create a short-lived feature branch from `main`.
2. Make one focused change and open a pull request.
3. Run the checks documented in [CONTRIBUTING.md](CONTRIBUTING.md).
4. Review the changes and merge only after validation.
5. Deploy through the hosting provider after approval.

## Documentation

- [Project baseline and risks](docs/BASELINE.md)
- [Contribution and validation guidance](CONTRIBUTING.md)
- [Security policy](SECURITY.md)

## Next priorities

1. Integrate and test a real lead-capture workflow.
2. Verify company contact details and all public business claims.
3. Add basic automated website checks.
4. Identify the hosting provider, production URL, and deployment process.
5. Add privacy/consent disclosures appropriate for the form and analytics.
