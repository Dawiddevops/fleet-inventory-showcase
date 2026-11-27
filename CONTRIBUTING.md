# Contributing to this Showcase

This repository is a documentation-first portfolio case study for a private Power Platform application.

## Before editing

- Preserve the distinction between documented concepts and reconstructed previews.
- Do not add production names, tenant identifiers, credentials, SharePoint URLs, customer data, or personal information.
- Use generic placeholders in examples and clearly label them as such.
- Do not claim an app is runnable when no public app package or setup environment exists.

## Documentation expectations

- Keep README positioning factual and concise.
- Explain architecture in logical components instead of publishing private schemas.
- Link to the relevant mockup rather than embedding raw, unsupported screenshots.
- Update architecture documentation whenever a documented workflow or integration changes.

## SVG mockups

Mockups are stored in `screenshots/` and should remain self-contained SVG files. Keep existing text legible and retain an explanatory footer that identifies each image as a reconstructed preview with fabricated data.

Update [docs/VISUAL_EVIDENCE.md](docs/VISUAL_EVIDENCE.md) if a real, privacy-approved screenshot or app package becomes available.

## Review checklist

- Does the change describe implemented behavior without inventing metrics or outcomes?
- Is private or tenant-specific information excluded?
- Are screenshots or diagrams identified as mockups?
- Does the README still make the repository scope clear within the first few lines?
- Did a Markdown, Mermaid, or SVG preview remain readable after the change?
