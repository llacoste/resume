# AGENTS.md

This is the **public** mirror of Lance Lacoste's résumé PDF. Treat everything
here as visible to the open web.

## What belongs here

Only these files: `resume.pdf` (the compiled résumé), `index.html` (redirects
the bare subdomain to `lancelacoste.com/resume`), `CNAME`, `README.md`, and this
file. Nothing else.

`resume.pdf` is **auto-published** by the private source repo's CI on every
release — **do not hand-edit or hand-commit it.** The LaTeX source, build, git
history, and full positioning live in that private repo.

## IP guardrail (important)

This repo is public. **Never commit anything containing employer-internal system
codenames or confidential business/financial figures** — describe systems by
function only. The résumé PDF is deliberately generalized at its source; the
real specifics live solely in the private repo and never ship here.

This repo's history was reset to a single clean commit (2026-05-29) to purge
older, non-generalized PDFs. Keep it clean — don't reintroduce sensitive
content, and don't restore old history.

## Conventions

- Custom domain: `resume.lancelacoste.com` (via `CNAME` + GitHub Pages).
- Conventional Commits; changes via PR, squash-merged to `main`.
