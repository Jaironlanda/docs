# JSONsilo Docs

Source for [docs.jsonsilo.com](https://docs.jsonsilo.com), built with [Mintlify](https://mintlify.com).

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) (Node.js 18 or later):

```bash
npm i -g mint
```

Run the preview at the root of the repo (where `docs.json` is):

```bash
mint dev
```

The site is served at `http://localhost:3000`. Use `mint dev --port 3333` to pick another port.

Before pushing, check the build and links:

```bash
mint validate
mint broken-links --check-anchors --check-redirects
```

Keep the CLI current with `mint update`.

## Structure

| Path | Contents |
|---|---|
| `docs.json` | Site config and navigation |
| `api-reference/openapi.json` | OpenAPI spec for the Manage API |
| `features/`, `how-to/`, `keys/`, `mcp/`, ... | Pages, one `.mdx` file per page |
| `snippets/` | Reusable MDX snippets (never rendered as pages) |
| `images/` | Screenshots and diagrams |
| `.mintignore` | Files excluded from the build |

A page only appears in the sidebar once it is listed in `docs.json`'s `navigation`. When you move or rename a page, add a `redirects` entry from the old path.

## Publishing Changes

The Mintlify GitHub app deploys changes automatically after a push to `main`.

## Troubleshooting

- `mint dev` isn't running: run `mint update` and try again.
- A page loads as a 404: make sure it is listed in `docs.json` and you are running in the folder that has `docs.json`.
