# CV PDF Generation Guide

This project includes a workflow to generate a professional PDF from a `cv-***.md` markdown file using `md-to-pdf` and a custom CSS stylesheet.

## Quick Update Command

To regenerate the `cv-cig_4ai.pdf` with the current styles and content, run this command from the project root (the stylesheet and page margins are now configured via YAML front matter in the `.md` files themselves):

```bash
npx md-to-pdf cv-cig_4ai.md
```

## Customization

- **Content**: Edit `cv-***.md` file directly.
- **Styling**: Modify `cv-style.css` to change fonts, colors, or spacing.
- **Margins/Format**: Adjust the `pdf_options` in the YAML front matter of the `.md` file.

## Prerequisites

- **Node.js**: Required to run `npx`.
- **Internet Connection**: The stylesheet imports the 'Inter' font from Google Fonts.
