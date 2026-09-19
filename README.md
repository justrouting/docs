# JustRouting Docs

Source for the [JustRouting docs site](https://justrouting.tech) — built with [Mintlify](https://mintlify.com).

JustRouting provides super lightweight routing APIs tuned for Southeast Asia: road-accurate **Directions**, **Distance Matrix**, **Map Matching**, and **Fleet Optimization** — built on open source (OSRM, VROOM, OpenStreetMap). Standard protocols, zero lock-in.

## Repository structure

| Path | Contents |
| --- | --- |
| `index.mdx`, `quickstart.mdx`, `authentication.mdx`, `rate-limits.mdx`, `errors.mdx`, `coverage.mdx` | Getting-started pages |
| `api-reference/` | Per-API documentation (directions, distance matrix, map matching, trip, nearest, fleet optimization) |
| `guides/` | How-to guides (draw routes on a map, turn-by-turn navigation, SDKs) |
| `openapi.json` | OpenAPI spec powering the API reference |
| `images/` | Logos and illustrations |
| `docs.json` | Mintlify configuration (navigation, theme, colors) |

## Local development

Install the [Mint CLI](https://www.npmjs.com/package/mint) (`npm install -g mint`), then run:

```bash
./preview.sh
```

or directly:

```bash
mint dev
```

This starts a local preview at `http://localhost:3000` with hot reload.

> Note: files not listed in `docs.json`'s `navigation` (like this README) are not part of the docs site.

## Contributing

1. Create a branch for your changes.
2. Run `mint dev` locally and check the preview.
3. Open a pull request — changes merged to `main` are deployed automatically.

## License

[MIT](LICENSE)
