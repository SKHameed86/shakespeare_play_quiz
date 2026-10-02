# Shakespeare Play Personality Quiz — v5

GitHub Pages-ready static build.

## v5 changes
- Replaced the temporary SVG artwork with the individually generated and approved play artwork.
- Each of the 24 plays in the quiz has its own local PNG asset under `assets/plays/`.
- Artwork appears on the primary recommendation, close matches, and the All Plays view.
- Quiz questions, scoring profiles, genres, recommendation text, and result behaviour are unchanged from v4.
- No external image hosting or runtime dependencies.

## Publish on GitHub Pages
Upload the contents of this folder to the root of the branch/folder used by GitHub Pages. `index.html` is the entry point.


## v6 — expanded result pool
Nine additional plays can now be returned as quiz results: Timon of Athens, All’s Well That Ends Well, The Merry Wives of Windsor, The Two Gentlemen of Verona, Henry VI, Henry VIII, King John, Pericles, and Cymbeline. Their approved individual artwork is bundled locally. The quiz now has 33 possible play recommendations.


## v7 sharing
Adds Share Result using the Web Share API with clipboard fallback. Compact `?r=` payloads store only local play indexes (base-36) for the main result and three close matches; no server or database is required. Shared links reconstruct the result locally. `#r=` and `#result=` are accepted for backwards compatibility. Runtime filenames are versioned to reduce stale GitHub Pages/browser caching.
