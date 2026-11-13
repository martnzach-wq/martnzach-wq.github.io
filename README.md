# Personal website (Quarto)

## Local preview
    quarto preview

## Add a note
Create `posts/YYYY-MM-DD-short-name/index.qmd` with a header:

    ---
    title: "..."
    description: "One sentence for listings and link previews."
    date: 2026-11-13
    image: ../../assets/img/<project>.svg
    categories: [<PROJECT>, <Type: Event | Publication | Workshop | Note>, <Topic>, ...]
    ---

The first category is the project name; project pages list all notes carrying that category.
Placeholders are marked as `[text]{.todo}` (yellow) – search for `.todo` before going live.

## Publish
Every push to `main` builds the site and deploys it to GitHub Pages
(Settings → Pages → Source: "GitHub Actions").
