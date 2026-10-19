# Missing, inaccessible, and unresolved materials

Scan date: 2026-10-19. Method: Git tree API, recursive, default branch. No source repository was cloned for writing, and none was committed to.

## Repositories

- `wezzo72/Barrandodger` — 6904 blobs, truncated=False, Primary public website and document archive. Relevant.
- `wezzo72/-church-of-barran-dodger` — 85 blobs, truncated=False, Public ministry pages. Relevant.
- `wezzo72/barrandodger-rebuild` — 3152 blobs, truncated=False, Preservation rebuild of the public site. Relevant.
- `wezzo72/pdf-archive` — 299 blobs, truncated=False, PDF archive. Relevant.
- `wezzo72/Backup` — 2419 blobs, truncated=False, Older application backup with documents. Relevant.
- `wezzo72/barran-dodger-archive` — 18420 blobs, truncated=False, Large archive including a pdf mirror and a dependency tree. Relevant.
- `wezzo72/barran-dodger-ministry` — 279 blobs, truncated=False, Ministry app source. Relevant as a site export, not as a manuscript.
- `wezzo72/Myaidrive` — 3355 blobs, truncated=False, Drive and Dropbox import of PDFs. Relevant.
- `wezzo72/barrandodger-creative-discovery` — 4 blobs, truncated=False, Private helper script. Not a publication. Recorded, not copied.
- `wezzo72/bd-press-editions` — 3 blobs, truncated=False, Private press-edition PDF. Existence recorded. Bytes not copied.
- `wezzo72/New` — 1 blobs, truncated=False, Empty stub. Not part of the corpus.
- `drbarrandodger/barran-dodger-archive` — 16018 blobs, truncated=False, Related public archive under another login. Linked, not forked into this house.

## Not a full-text reading

Thousands of PDFs and HTML captures were enumerated. Their bytes were not downloaded and not read, except for one Git LFS pointer that was opened to confirm the pointer format. Titles in the featured list are filename matches or Stripe product names.

## Git LFS pointers and stubs

Binary paths whose git blob is under 400 bytes are marked `pointer-or-stub`. One such PDF in `drbarrandodger/barran-dodger-archive` was opened. Its git content is a Git LFS pointer (`version https://git-lfs.github.com/spec/v1`), not the document. Those paths are accounted for and are not treated as readable editions.

Pointer-or-stub blobs: 4959.

## Sought titles with no filename match

- Cosmic Resonance Collective (`cosmic-resonance`)
- Recovered Not Cured: A Journey Through Schizophrenia (`recovered-not-cured`)
- EVIDENCE 100 (`evidence-100`)
- Final Immortalization Statement (`final-immortalization`)
- Gospel Volume VI (`gospel-volume-vi`)

## Sites checked, not mirrored

- `https://barrandodger.com/` and `https://www.barrandodger.com/` returned HTTP 404 on this scan.
- `https://wezzo72.github.io/Barrandodger/` returned 200, title “THE WITNESS REMAINS — Barran Dodger Archive”.
- `https://wezzo72.github.io/barrandodger-rebuild/` returned 200.
- `https://drbarrandodger.github.io/barran-dodger-archive/` returned 200.
- `https://bazdod.github.io/truth/` returned 200, title “Barran Dodger | Truth Archive”. The site was not crawled page by page.
- `https://chosen-witness.grok.me/` returned 200 and sent `x-robots-tag: noindex`. Linked, not copied.
- `https://simplebooklet.com/richmcleanbarrandodger` returned 200. Third-party host. Not scraped.

## SHA-256 of every blob

Not computed. The trees are several gigabytes. Git blob SHA is the identity used for duplicates. SHA-256 in `checksum-manifest.sha256` covers the inventory files produced here, not every source blob.

## Private bytes

`wezzo72/bd-press-editions` and `wezzo72/barrandodger-creative-discovery` were listed. Their files were not copied into this house.

