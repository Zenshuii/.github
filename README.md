# Zenshuii Org Profile

This repository powers the Zenshuii organisation profile on GitHub.

To update the public org page, edit `profile/README.md`.

Issues and PRs are tracked in individual project repositories.

## What's Inside
- `profile/README.md`: Content for the org profile page.
- `.github/pull_request_template.md`: Default PR template for org repos.
- `.github/ISSUE_TEMPLATE/`: Bug and feature request templates.
- `.github/workflows/ci.yml`: Reusable CI workflow. See file header for usage.
 - `CONTRIBUTING.md`: Org-wide contributing guidance (used if a repo lacks its own).
 - `CODE_OF_CONDUCT.md`: Contributor Covenant v3.0 + reporting instructions.
 - `SECURITY.md`: Security policy and responsible disclosure contact.

## Notes
- Org defaults (issue templates, contributing, CoC, security) inherit to public repos unless overridden.
- PR templates and CODEOWNERS do not inherit; add them in each repo as needed.
