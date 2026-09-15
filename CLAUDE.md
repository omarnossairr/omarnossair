# omarnossair site notes

This repo is Omar Nossair's personal research/writing site: `index.md` is the homepage, `featured.md` curates top pieces, and each literature review is a standalone `.md` page paired with a source PDF.

## Standing instruction: keep Field Notes in sync

There is a private reference artifact called **Field Notes** (https://claude.ai/artifact/RgYUHhBxbZj5FvE943Hx55) that lists every piece on the site in chronological order with a summary, why it matters, and how it connects to the other pieces (grouped into named threads).

**Whenever a new piece is added to the site, update this artifact too** — don't just leave it as a one-time snapshot. To update it:
1. Read the artifact (`action: "read"` with the URL above) to get its current HTML.
2. Add a new numbered entry (summary, why it matters, connects-to) in chronological order, renumbering IDs/TOC as needed.
3. Reconsider the "How the pieces connect" threads at the bottom — the new piece likely fits an existing thread, or may warrant a new one.
4. Republish to the same URL (pass `url`) so the link stays the same.

Don't wait to be asked — treat adding a site piece and updating Field Notes as one task.
