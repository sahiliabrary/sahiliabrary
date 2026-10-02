# Sahil's Library — PDF Library

## Publishing workflow
1. Write in Google Docs.
2. Download/export the document as PDF.
3. Put the PDF inside the `pdfs` folder.
4. Open `index.html`.
5. Find `const publications = [...]`.
6. Add an entry like:

`{type:"Poetry",title:"My Poem",desc:"Short description.",date:"2026-10-02",file:"pdfs/my-poem.pdf"}`

Allowed types: `Poetry`, `Blog`, `Writing`.

7. Commit `index.html` and the PDF to GitHub.
8. Wait for GitHub Pages to update.

### File naming
Use simple names with lowercase letters, numbers and hyphens:
`my-first-poem.pdf`

Avoid spaces and special characters in PDF filenames.

The website is designed for free GitHub Pages hosting.
