# THE APEX LIBRARY — LAW OF THE SHELF

Founded Nov 26, 2026, on the owner's order: **"Make a library of our own so we don't need a door."**

The Library is the house's single shelf for media and build assets. Everything the house owns — pages, audio, video, images and textures, games, face art, documents — is held here durably, under house control, catalogued with provenance. Surfaces (the Door, the graphic seat, the games, the faces) draw from the Library. A surface is a window onto the shelf, never the thing the work depends on.

## The law

1. **Surfaces pull from the Library.** When a surface needs an asset, it takes the Library's canonical copy or a copy struck from it.
2. **Nothing in production hangs off an expiring or third-party link when a Library copy exists.** An expiring download link, a stranger's CDN, a chat attachment — none of these is a shelf. If the asset matters, it is ingested; then it is served from house ground.
3. **New house media is ingested at creation.** Hashing and a catalogue line are part of the build record, not an afterthought: when a build produces media, the same pass that benches it shelves it.
4. **Hash first, dedupe always.** Every item enters by its SHA-256. Identical bytes are one canonical copy; duplicates are ledgered in the catalogue, never copied twice.
5. **Originals stay home.** The Library holds the canonical shelf copy; the catalogue names where the working original lives. Ingest never deletes or moves an original out of its home project.
6. **Provenance rides with the file.** Every catalogue line carries source and licence — house-made, CC0 (and which library), or owner-supplied. No file without paper travels with a product.
7. **Missing is a line, not a hole.** Anything named in the records but not found on disk is entered as a MISSING line with its source record. The Library never invents a file to fill a shelf.

## Layout

- `pages/` — served pages (Door portal, player)
- `audio/` — tracks and tones
- `video/` — cuts and clips
- `images/` — stills, posters, renders, captures · `images/textures/` — texture/HDRI pieces (CC0 libraries land here)
- `games/` — game builds and their installable packages
- `faces/` — watch faces, face art, wallpaper builds, launcher icons
- `apps/` — native Android applications in their installable packages (added Nov 26, 2026, estate hang-and-label pass)
- `documents/` — charters and standards that govern the media
- `CATALOG.md` — the catalogue, human-readable · `catalog.json` — the same, machine-readable
