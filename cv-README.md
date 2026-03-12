# CV PDF Generation Guide

This project includes a workflow to generate a professional PDF from the `CV.md` markdown file using `md-to-pdf` and a custom CSS stylesheet.

## Quick Update Command

To regenerate the `CV.pdf` with the current styles and content, run this command from the project root:

```bash
npx md-to-pdf CV.md --stylesheet cv-style.css --pdf-options '{"format": "A4", "margin": "15mm"}'
```

## Customization

- **Content**: Edit `CV.md` directly.
- **Styling**: Modify `cv-style.css` to change fonts, colors, or spacing.
- **Margins/Format**: Adjust the `--pdf-options` JSON string in the command above.

## Prerequisites

- **Node.js**: Required to run `npx`.
- **Internet Connection**: The stylesheet imports the 'Inter' font from Google Fonts.
