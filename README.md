# Deaf Link Uganda — Website

A single-file, static homepage for Deaf Link Uganda (DLU), a national NGO promoting the welfare of Deaf and hard-of-hearing people in Uganda through education, livelihoods, business enterprise, and rights advocacy.

## Files

- `index.html` — the entire site (HTML, CSS, and structure in one file). No build step, no dependencies except two Google Fonts loaded via `<link>`.

## How to use it

**Preview locally**
Just open `index.html` in any browser (double-click it, or drag it into a browser window).

**Publish it**
Upload `index.html` to your host as the homepage (e.g. replace the current WordPress homepage template, or host it as a static page). If you're staying on WordPress, a developer can port these sections into a WordPress page/theme rather than replacing the whole CMS.

## What's in the page

Sections, top to bottom:

1. **Header / nav** — logo mark, links to each section, "Support DLU" button
2. **Hero** — mission statement + key facts strip (founded 2007, NGO since 2017, 3 programme areas, 0.35% of Uganda's population)
3. **About** — org history, Vision, Mission, and the meaning behind the DLU logo
4. **Programmes** — Education, Business Enterprise, Livelihoods, plus a Deaf Rights & Advocacy callout
5. **Uganda Sign Language** — embedded UgSL introduction video
6. **News** — featured story + secondary story cards
7. **Get Involved** — Donate / Volunteer or Partner / Learn UgSL
8. **Footer** — address, contact numbers, email, quick links, social icons

## Design notes

- **Palette**: navy (`#16233d`), terracotta (`#c1392b`), gold (`#e0a545`), warm cream background (`#faf5ea`) — pulled from the DLU logo's triangle/red-arrow motif.
- **Type**: Fraunces (serif, headings) + Work Sans (body/UI).
- **Signature element**: a small arc/curve motif reused as a section divider, echoing the "link" arrow that encircles the triangle in the DLU logo.
- Fully responsive — collapses to a single column under 860px width.

## ⚠️ Things you still need to fill in

These are placeholders and need real content before publishing:

- **Donate link** — the "Give today →" link in Get Involved currently points to `#`. Add a real donation page, payment link, or bank transfer details.
- **Social media links** — Facebook, Instagram, X, and LinkedIn icons in the footer are placeholders (`#`). Add your real profile URLs.
- **Images** — currently pulled directly from the old site's media URLs (`deaflinkuganda.org/wp-content/uploads/...`). If you migrate hosting, download these images and update the `src` paths to local files.
- **Video** — the UgSL video also currently links to the old site's hosted `.mp4`. Same note as images.

## Also fix on the old WordPress site (can't be fixed from this file)

- Remove the `<meta name="robots" content="noindex, nofollow">` tag — this is currently blocking Google from indexing deaflinkuganda.org at all.
- Fix the browser tab title, which currently reads "for the advancement of **dead** people."
- 
