# Sakhawat Hossan — academic website

Jekyll / Minimal Mistakes site for https://sakhawat19.github.io.

## Publish this update

Extract this archive and copy the **contents** of `sakhawat19.github.io-main` into the root of the existing repository, replacing matching files. Commit to the branch currently used by GitHub Pages. Retain the existing Pages settings. No new hosting service is required.

## Add lecture slides

1. Put the PDF or PPTX in `assets/teaching/csc250-spring2026/` (use filenames without spaces).
2. Add an entry in `_data/csc250.yml` with `title`, `file` (path starting `/assets/`), and `format` (`PDF` or `PPTX`).
3. Commit both files. The teaching page automatically renders download links and PDF previews.

## Maintenance

Edit `_pages/` for the main sections, `index.md` for About, and `_data/navigation.yml` for navigation. Custom styling lives in `assets/css/custom.css`.
