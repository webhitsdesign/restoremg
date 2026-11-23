# Contributing to Restore MG

Use pull requests for site changes. Keep `main` reviewable and deployable.

## Working practice

1. Branch from the latest `main`, e.g. `feature/contact-form-integration`.
2. Keep each PR focused and describe customer-facing changes.
3. Test on a local HTTP server with `python3 -m http.server 8000`.
4. Review mobile and desktop layouts and check browser console errors.
5. Check that navigation anchors work and external links are valid.
6. Never claim that a contact request was received unless a backend confirms success.
7. Obtain approval before changing legal/business claims or live contact details.

## Pull request checklist

- [ ] Change summary and reason included
- [ ] No credentials, tokens or personal/customer data committed
- [ ] Local page loads, navigation works
- [ ] Responsive layout checked
- [ ] Form flow tested end to end if changed
- [ ] Accessibility checked (labels, contrast, keyboard)
- [ ] Documentation updated if behavior or deployment changes

Avoid force-pushing shared branches and avoid committing production data.
