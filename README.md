# KeyStage styles

Style packs that the KeyStage app can download (Styles → **Download styles**).

- `styles/<pack-id>/` holds each pack's style files and `pack.json` (name, description).
- `packs/<pack-id>.zip` and `index.json` are built from them with
  `python tools/build_style_index.py <this-repo>` (in the KeyStage app repo).
- The app checks each downloaded zip against the size and SHA-256 in `index.json`
  before importing it. The folder inside the zip becomes the style category.

Styles here are shared with permission of the people who made or own them.
To have a style removed, open an issue.
