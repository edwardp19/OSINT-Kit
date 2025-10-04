# Contributing

Thank you for wanting to improve the OSINT Kit — small, consistent contributions make this list far more useful. This document explains the preferred format for adding **new tools** and the process for submitting changes.

## Quick rule (required)
When submitting a tool, **use this one-line format** in the README:

`- [Tool Name](https://example.com/) - Short description (max 10 words).`

Example:
`- [Spiderfoot](https://github.com/smicallef/spiderfoot) - Automated OSINT recon and data collection.`

## Why this format?
- Keeps the list consistent and scannable.
- Reduces duplicate or unclear entries.
- Speeds up review and approval of pull requests.

## Submission template
Please include the following fields in your PR description (not required in README; only in PR body):

```
Tool Name: Spiderfoot
URL: https://github.com/smicallef/spiderfoot
Short description (≤10 words): Automated OSINT recon and data collection.
Category: OSINT Aggregator Tools
Benefits: Visual graphing, modular scans, active community
Usage notes: Self-hosted or use HX cloud; needs python deps.
License: GPL-3.0
Source / Repo: https://github.com/smicallef/spiderfoot
Submitter: github-username
```

## Content guidelines
- **Tool Name**: Official name (no emojis).
- **URL**: Use the canonical project page or repo.
- **Short description**: **Max 10 words** — concise, informative.
- **Category**: Pick one existing category from README (e.g., "Domain Information", "Location Tracking", "Miscellaneous").
- **Benefits**: 1–3 short bullets or a single sentence.
- **Usage notes & license**: Optional but helpful.
- **Duplicates**: Search the README before submitting. If similar, explain why this entry is different.

## Link & formatting rules
- Use standard Markdown links: `[Name](https://...) - Description.`
- Keep descriptions sentence-case (start with capital, no trailing period required).
- Do not add screenshots or large files to the list — link to hosted resources.

## PR checklist (before opening PR)
- [ ] Entry follows single-line README format.
- [ ] Short description ≤ 10 words.
- [ ] Correct category selected.
- [ ] URL works and is the canonical source.
- [ ] Not a duplicate (search README).
- [ ] Add any usage notes or license info in the PR body.

## Review process
- Maintainers will check format, link validity, and duplicates.
- Minor formatting fixes may be applied by maintainers.
- Substantial changes may be requested in PR comments.

## If you want to add more structure
If you propose changing README structure (e.g., adding a table with columns), open an issue describing the proposal and rationale so maintainers can discuss before larger edits.

Thanks — we appreciate your contribution!
