# Paintball 255 - Release Notes

Public release notes for **Paintball 255**, a VR paintball range on the beach for Meta Quest.

**Live page:** https://seedexr.github.io/paintball255-releases

## How to update (every time we publish a build)

1. Open `CHANGELOG.md`.
2. Add a new version block at the **top** of the list:
   ```
   ## [1.4.1] - 2026-10-07
   One-line summary of this build (optional).

   ### Added
   - New things players can now do.

   ### Changed
   - Things that were reworked or improved.

   ### Fixed
   - Bugs squashed.

   ### Known Issues
   - Things we already know about.
   ```
3. Commit and push.

The branded page (`index.html`) fetches `CHANGELOG.md` and re-renders automatically. You only ever edit `CHANGELOG.md`.

Use whichever sections apply (`Added`, `Changed`, `Fixed`, `Known Issues`, `Removed`) - empty ones can be left out. Match the version number to the app's `bundleVersion`.

Write for players, in plain text. The page does not render bold or italics, so asterisks would print literally.
