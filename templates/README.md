# Recipe Template Usage

`recipe-template.html` is the source template for new Samsung Food recipe pages. Publish completed recipe pages to the repository root.

For each recipe, Codex should copy the template, replace every placeholder, remove unused optional sections, validate the JSON-LD, and commit the completed root HTML file directly to `main`. Update an existing recipe page instead of creating a duplicate.

Do not edit the template during routine recipe publishing. Make global visual changes in the template only when the user explicitly requests them.

Public image URLs must use HTTPS. Published files must contain no unresolved `{{PLACEHOLDER}}` tokens and no local file paths. The visible recipe and JSON-LD must match exactly.

## Publishing checklist

1. Read `AGENTS.md`.
2. Read `templates/recipe-template.html`.
3. Confirm the recipe details.
4. Choose a stable lowercase kebab-case filename.
5. Replace all placeholders.
6. Remove unused optional blocks.
7. Validate the JSON-LD.
8. Create or update the root HTML file.
9. Commit directly to `main`.
10. Return the exact GitHub Pages URL.
