# Region South Resource Hub

This repository publishes the Region South Resource Hub through GitHub Pages. It contains the Region South Visual Style Guide, AI prompt libraries, instructional framework references, and teacher- and leader-facing resource pages.

Public site: <https://marioapodaca.github.io/region-south-hub/>

## Public entry points

| Resource | Repository file | Public URL |
|---|---|---|
| Region South Hub | `index.html` | <https://marioapodaca.github.io/region-south-hub/> |
| Instructional Leadership Hub | `rs_hub_index.html` | <https://marioapodaca.github.io/region-south-hub/rs_hub_index.html> |
| Teacher AI Reference Hub | `rs_hub_index_teachers.html` | <https://marioapodaca.github.io/region-south-hub/rs_hub_index_teachers.html> |
| Leadership AI Prompt Library | `rs-prompt-library.html` | <https://marioapodaca.github.io/region-south-hub/rs-prompt-library.html> |
| Teacher AI Prompt Library | `rs-prompt-library-teacher.html` | <https://marioapodaca.github.io/region-south-hub/rs-prompt-library-teacher.html> |
| Visual Style Guide | `style-guide/index.html` | <https://marioapodaca.github.io/region-south-hub/style-guide/> |

## Repository organization

### Hub and prompt-library pages

- `index.html` — main Region South Hub landing page.
- `rs_hub_index.html` — instructional-leadership resource hub.
- `rs_hub_index_teachers.html` — teacher-facing AI reference hub.
- `rs-prompt-library.html` — leadership and administrator prompt library.
- `rs-prompt-library-teacher.html` — teacher prompt library.

### Shared instructional references

These root-level pages are deliberately shared by both the teacher and leadership hubs. Their URLs are embedded in AI prompts, so filenames should remain stable unless redirects are provided.

- `tlf-standard-1.html` through `tlf-standard-5.html` — LAUSD Teaching and Learning Framework references.
- `slf-index.html` and `slf-standard-1.html` through `slf-standard-6.html` — LAUSD School Leadership Framework references.
- `ca-ela-standards.html` — California ELA standards reference.
- `ca-math-standards.html` — California mathematics standards reference.
- `ngss.html` — Next Generation Science Standards reference.
- `webb-dok.html` — Webb's Depth of Knowledge and Cognitive Rigor reference.
- `rigor.html` — Region South Rigor in Practice and Blueprint for Success overview.

### Visual Style Guide

The complete and authoritative Visual Style Guide is maintained only in `style-guide/`.

Important files include:

- `style-guide/index.html` — human-facing guide.
- `style-guide/create.html` — Create with AI instructions.
- `style-guide/examples.html` — approved examples.
- `style-guide/more-examples.html` — expanded example gallery.
- `style-guide/region-south-style-guide.md` — detailed AI-readable specification.
- `style-guide/region-south-style-guide.yaml` — machine-readable specification.
- `style-guide/AI-QUICKSTART.md` — abbreviated AI guidance.
- `style-guide/AI-COPY-PASTE.md` — reusable AI instruction block.
- `style-guide/assets/` — approved logos, reference graphics, and gallery images.
- `style-guide/user-docs/` — downloadable Word and PDF documentation.

Do not create or maintain additional root-level copies of Style Guide files. Update the corresponding file inside `style-guide/` instead.

## Branding assets

- `RS-logo.png` — approved Region South logo used by root-level hub and reference pages.
- `LAUSD_seal.png` — approved LAUSD seal available for designs that specifically require it.
- Style Guide pages use the approved assets maintained within `style-guide/` and `style-guide/assets/`.

Never replace an approved logo with an AI-generated approximation.

## Maintenance guidance

1. Keep the main Hub, teacher hub, leadership hub, and prompt libraries at the repository root unless a planned migration includes redirects.
2. Preserve the current shared-reference filenames because prompt templates contain their full public URLs.
3. Maintain the Visual Style Guide only under `style-guide/`.
4. Check all internal links before publishing changes.
5. Mark an unfinished resource **Coming Soon** and remove its hyperlink rather than linking to a nonexistent page.
6. Use authentic approved branding assets only.
7. Allow GitHub Pages a few minutes to deploy after a commit, then hard-refresh the affected page.

## Current deferred resources

- The Region South Informal Classroom Observation Form reference is deferred while the form is updated for the current school year.
- Detailed pages for the seven Blueprint for Success components are planned but not yet published. Their overview cards remain visible in `rigor.html` and are marked **Coming Soon**.

## Publishing

GitHub Pages publishes from the repository's `main` branch. Files committed to the repository root appear beneath:

`https://marioapodaca.github.io/region-south-hub/`

Files committed to `style-guide/` appear beneath:

`https://marioapodaca.github.io/region-south-hub/style-guide/`

