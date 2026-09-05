# Contributing to Mycelia

Thanks for helping improve **Mycelia**. Bug reports, fixes, and features are all welcome.

## Getting set up

```bash
git clone https://github.com/Facetworks/Mycelia
cd Mycelia
# no build step — open `public/index.html` in a browser, or `npx serve public`
```

## How to run it

Run it locally with: `open `public/index.html` in a browser, or `npx serve public``.

## Ways to contribute

Behaviour presets, palettes, and the simulation parameters live in `public/index.html`. Add a preset or palette, or tune the sensor/deposit/decay values.

## Pull requests

1. Fork and branch from `main`.
2. Make one focused change per PR.
3. Check it still works in the browser.
4. Bump the version and add a `CHANGELOG.md` entry.
5. Open a PR using the template.

## Style

- Match the surrounding code — this project is intentionally **zero-dependency**, so please don't add runtime dependencies.
- Keep it small, honest, and well-scoped.

Questions? Open an issue.
