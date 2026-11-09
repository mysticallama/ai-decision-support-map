# Map of AI decision support tools and programs

Interactive map of the AI tools and programs that governments, frontier AI developers and defense technology companies use for negotiation, intelligence analysis, wargaming and planning, and budget and investment decisions. Public sources only, as of November 9, 2026.

The whole site is one file, `index.html`. It loads D3 7.8.5 from cdnjs and IBM Plex from Google Fonts.

## Publish on GitHub Pages

1. Create a new public repository (for example `ai-decision-support-map`).
2. Add `index.html`, `.nojekyll` and this README to the root of the repository and push to `main`.
3. In the repository, open Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. The site appears at `https://<your-username>.github.io/ai-decision-support-map/` within a minute or two.

## Updating entries

Each program, its description, status and sources live in the `DATA` object near the bottom of `index.html`. Edit an entry there and push again.
