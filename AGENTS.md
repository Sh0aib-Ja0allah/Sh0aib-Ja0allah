# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub Profile README** — it contains only a single `README.md` file (Markdown with inline HTML and shield.io badges). There is no application code, no package manager, no build system, no automated tests, and no services to run.

### Developing

- Edit `README.md` directly. The file uses GitHub-Flavored Markdown with inline HTML (`<div>`, `<img>`, `<a>`) for layout and [shields.io](https://shields.io) badges for visual elements.
- To preview locally, run: `grip README.md <port>` (requires `grip` — `pip3 install grip`). This renders the Markdown using GitHub's styling.
- To lint: `markdownlint README.md` (requires `markdownlint-cli` — `npm install -g markdownlint-cli`). Expect warnings for inline HTML and long lines, which are intentional for badge URLs and layout divs.

### Notes

- External images (header/footer from `capsule-render.vercel.app`, badges from `img.shields.io`) require network access to render.
- No CI/CD pipeline or pre-commit hooks are configured.
