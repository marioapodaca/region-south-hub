# Region South Style Guide — Logo-Control Update

## Why this update was needed
The generated ELA Guideposts example added an unrequested circular “Region South” seal in the bottom-left footer. That mark was not an approved Region South asset and was invented by the image generator.

## Existing rules that were violated
The current guide already prohibited this behavior:

1. **Human-facing Brand Foundation:** “Use official Region South and LAUSD assets only. Never redraw, recolor, distort, crop, or approximate official logos.”
2. **AI-ready Canonical Assets:** official Region South and LAUSD assets must not be redrawn, recolored, distorted, rotated, cropped, or approximated; if an authentic logo cannot be inserted reliably, it should be omitted rather than fabricated.
3. **AI-ready Logo Validation:** “Generated or approximate logos are non-compliant” and substitute/altered Region South marks are prohibited.
4. **Approved-example production rule:** authentic logos are brand-critical elements that must be verified in post-production before an example is considered approved.

The invented circular footer seal therefore violated the existing “official assets only / never approximate” rule and the Logo Validation rule.

## Why the existing wording still needed strengthening
Two areas could be misread by an image-generation system:

- The specification previously said the Region South logo’s **preferred placement on data graphics was bottom left**. An image model can overgeneralize this into “put some Region South-looking mark in the bottom-left,” especially when it cannot faithfully render the canonical asset. This placement statement has been replaced with a conditional rule: use the authentic asset only when requested or defined by an approved template; never assume a default placement.
- The footer standard previously listed **Region South / LAUSD branding** in the left footer zone without explicitly saying branding is conditional. That language is now qualified so it cannot be interpreted as permission to invent or duplicate branding.

## Where new language was inserted
- **Human-facing Style Guide (`index.html`)**: Brand Foundation now includes Logo Control, Brand Placement, AI Image-Generation Restriction, Final Validation — Brand Assets, and the core brand-failure rule.
- **AI-readable specification (`region-south-style-guide.md`)**: expanded Canonical Assets rules; new Logo Control and Brand Placement section; strengthened Logo Validation; conditional Footer Standard; expanded AI self-check; strengthened Approved Example production rule; expanded Core AI Rule.
- **AI Quick Start (`AI-QUICKSTART.md`)**: explicit no-invention/no-duplication/no-decorative-branding rules plus the exact image-generation instruction.
- **Machine-readable specification (`region-south-style-guide.yaml`)**: protected brand mark constraints, placement controls, image-generation instruction, validation flags, and core brand-failure rule.
- **Copy/Paste AI Instructions (`AI-COPY-PASTE.md`)**: logo-control requirements are embedded directly in the fallback prompt so they apply even if the AI cannot open the linked guide.
- **Create with AI (`create.html`)**: the copied master prompt now contains the strengthened logo-control language, and the preflight checklist identifies approved logo assets as optional and conditional.

## Core rule added
**An invented or approximated logo is a brand-compliance failure, even if it looks visually appropriate or resembles an official Region South or LAUSD asset.**
