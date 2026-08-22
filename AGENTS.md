# Repository Guidelines

## Project Structure & Module Organization

This repository is a presentation and documentation package for PA3. The main deliverable is `PA3_presentation.html`, a self-contained HTML/CSS/JavaScript slide deck. Presentation narration lives in `PA3_script.md`, and the assignment/workflow reference is `PA3_Task_Workflow_Specification.md`.

Use `resource/` for source assignment materials, including the PDF and Vietnamese/English Markdown versions. Use `img/` for prototype photos referenced by the presentation; keep image filenames descriptive and stable because the HTML links to them directly. `scripts/` and `output/` are available for helper scripts and generated artifacts, but are currently empty.

## Build, Test, and Development Commands

There is no package manager or build step. Useful local commands:

```bash
open PA3_presentation.html
```

Opens the deck directly in a browser on macOS.

```bash
python3 -m http.server 8000
```

Serves the repository locally; visit `http://localhost:8000/PA3_presentation.html`. Prefer this when checking relative image paths.

```bash
git diff --check
```

Checks for whitespace errors before committing.

## Coding Style & Naming Conventions

Keep `PA3_presentation.html` self-contained unless a new external asset is necessary. Match the existing style: four-space indentation, semantic class names, CSS custom properties in `:root`, and section comments for major slide/style groups. Keep slide dimensions aligned with the existing 1920x1080 stage model.

Name new prototype images with lowercase, descriptive words separated by underscores, for example `schedule_filter_open.JPG`. When adding Markdown documents, use clear PA3-prefixed names where appropriate.

## Testing Guidelines

No automated test framework is configured. Manually verify the presentation after changes by opening the deck, navigating with arrow keys, and checking that all images load from `img/`. For layout changes, test a normal browser view and print/export behavior, since print styles are defined in the HTML.

## Commit & Pull Request Guidelines

Recent commits use short imperative summaries, with occasional Conventional Commit prefixes such as `feat:` and `docs:`. Prefer `type: concise summary`, for example `docs: add contributor guide` or `feat: update prototype slide flow`.

Pull requests should include a brief description of the change, list any affected files or assets, and attach screenshots or exported slide previews when visual layout changes. Mention any manual checks performed, especially browser navigation and image-loading verification.

## Agent-Specific Instructions

Avoid renaming or moving existing assets unless all HTML references are updated in the same change. Keep generated outputs out of source folders unless they are intended deliverables.
