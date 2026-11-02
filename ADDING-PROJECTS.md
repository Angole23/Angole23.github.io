# Add a project

New projects automatically appear in the portfolio and homepage carousel.

1. Sign in at https://github.com/Angole23/Angole23.github.io.
2. Open assets → Add file → Upload files. Upload your images and commit to main. Use simple filenames.
3. Open projects.json and click the pencil. Add a comma after the last project object, then add this object before the final closing square bracket:

```json
{
  "title": "My new project",
  "year": "Interaction Design · 2026",
  "images": ["/assets/new-project-cover.webp", "/assets/new-project-detail.webp"],
  "text": "Project introduction.\n\nAnother paragraph about the process.",
  "url": "https://example.com"
}
```

The first image is the cover. Add as many images as needed. Omit url if you have no external project link, removing the preceding comma too. Keep existing projects in the same order to preserve old links.

4. Commit changes to main. GitHub Pages automatically republishes, usually within a few minutes.

Or send Codex your title, year, description, images and optional link and ask it to add the project.
