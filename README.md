# Shruti Mishra — Portfolio

A single-page personal portfolio. No build step, no dependencies beyond Google Fonts — it's plain HTML, CSS, and JavaScript in `index.html`.

**Live site:** https://shrutimishra816.github.io

## What's in here

- `index.html` — the whole site (markup, styles, and behavior all in one file)

## The facet selector

The pills under the hero ("MIS Analyst / Python Developer") let a visitor pick which side of you they want to see. Clicking one swaps the bio, the skills display, the projects, and the accent color. To add or rename a facet:

1. Edit the `<button class="facet-pill" data-facet="...">` row in the hero section — the `data-facet` value is the ID, the visible text is the label.
2. Add a matching `<div data-facet-content="...">` block for each section (bio, skills, projects) that should show up under that facet.
3. Update the `labels` object and the `--accent` / `--accent-soft` color swap in the `<script>` block if you're adding a brand-new facet beyond the current two.

## Editing content

- **Hero:** name, role line ("MCA Graduate (Fresher)"), and the two facet bios
- **MIS Analyst:** skills table (`.ledger`) — one row per tool, plus a projects grid (currently a placeholder card, ready for the first real project)
- **Python Developer:** skills shown as an `import`-style code block, plus a projects grid — Research Companion Chrome extension is listed, with a placeholder card for what's next
- **Contact:** email, phone, LinkedIn, GitHub — all in the footer `.contact-grid`

Edit directly on GitHub (pencil icon on the file → commit) or clone the repo and edit locally — either way, pushing to `main` updates the live site automatically within about a minute.

## To do

- [x] Replace placeholder name, bio, and role line
- [x] Swap in real facets (MIS Analyst / Python Developer) and blurbs
- [x] Add real contact links
- [ ] Add first MIS Analyst project (dashboard/reporting work)
- [ ] Add additional Python projects as they're built
