# Your Name — Portfolio

A single-page personal portfolio. No build step, no dependencies beyond Google Fonts — it's plain HTML, CSS, and JavaScript in `index.html`.

**Live site:** https://your-username.github.io

## What's in here

- `index.html` — the whole site (markup, styles, and behavior all in one file)

## The facet selector

The pills under the hero ("All / Engineer / Designer / Writer") let a visitor pick which side of you they want to see. Clicking one swaps the about blurb and filters the project grid to matching cards. To add or rename a facet:

1. Edit the `<button class="facet-pill" data-facet="...">` row in the hero section — the `data-facet` value is the ID, the visible text is the label, `data-blurb` is the paragraph shown when it's selected.
2. Tag each project card with a matching `data-facet="..."` attribute so it shows up under the right filter.

## Editing content

Anything in `[brackets]` is a placeholder. The main spots:

- Hero: name, role line
- About: bio paragraph, "Currently / Based in / Previously" list
- Work: one card per project — duplicate the `<div class="card">` block for more
- Contact: email and social links

Edit directly on GitHub (pencil icon on the file → commit) or clone the repo and edit locally — either way, pushing to `main` updates the live site automatically within about a minute.

## To do

- [ ] Replace placeholder name, bio, and role line
- [ ] Swap in real facets and blurbs
- [ ] Add real projects and images
- [ ] Add real contact links
