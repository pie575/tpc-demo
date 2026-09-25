# The Prompting Company — Docs (local Mintlify mirror)

A local [Mintlify](https://mintlify.com) reproduction of the production documentation at
<https://docs.promptingcompany.com>.

## Contents

| Path | What it is |
|---|---|
| `docs.json` | Site config — theme, colors, logo, navbar, footer, contextual menu, and the full four-tab navigation tree |
| `guides/` | Guides tab — get started, dashboard overview, CMS publishing, analytics, agent experience |
| `cli/` | CLI tab — install, auth, command reference, recipes, troubleshooting |
| `api/` | API tab — overview, concepts, Content API prose pages |
| `ts-sdk/` | SDK tab — TypeScript SDK docs |
| `api-reference/openapi.json` | OpenAPI 3.1 spec (89 operations) that Mintlify expands into the generated endpoint pages under `/api/reference/...` |
| `logo/`, `favicon.svg` | Brand assets |

57 authored MDX pages plus 89 OpenAPI-generated endpoint pages.

## Run it

```bash
npx mint@latest dev
```

Then open <http://localhost:3000>.

## Check it

```bash
npx mint@latest broken-links
```
