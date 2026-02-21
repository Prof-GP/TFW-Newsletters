# The Forensics Way

A weekly digital forensics newsletter covering threat intelligence, CVEs, historic case studies, and forensic tools. Published every Tuesday.

## Archive

Browse all past issues at the GitHub Pages site.

## Structure

```
issues/
├── Newsletter_012726.html + .pdf   (Issue 01 — Jan 27, 2026)
├── Newsletter_020326.html + .pdf   (Issue 02 — Feb 3, 2026)
├── Newsletter_021726.html + .pdf   (Issue 03 — Feb 17, 2026)
└── Newsletter_022426.html + .pdf   (Issue 04 — Feb 24, 2026)
index.html                          (Archive landing page)
```

## Adding a New Issue

1. Drop the new `Newsletter_MMDDYY.html` and `.pdf` into `issues/`
2. Add a new card to `index.html`
3. Move the "Latest" badge to the new issue
4. `git add . && git commit -m "Add Issue XX — Month DD, 2026" && git push`
