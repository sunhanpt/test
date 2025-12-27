# test

This repository contains a small Marp slide deck.

## Export slides with Marp (PPTX)

### Prerequisites

- Node.js (recommended: latest LTS)
- Marp CLI

Install Marp CLI:

```bash
npm install -g @marp-team/marp-cli
```

### Export to PowerPoint (.pptx)

From the repository root, run:

```bash
marp slides/hunan-culture.md --pptx --output slides/hunan-culture.pptx
```

Optional: export to PDF as well:

```bash
marp slides/hunan-culture.md --pdf --output slides/hunan-culture.pdf
```

### Notes

- If you prefer not to install globally, use `npx`:

```bash
npx @marp-team/marp-cli slides/hunan-culture.md --pptx --output slides/hunan-culture.pptx
```

- The `.pptx` export works best when slides use simple layouts and common fonts.
