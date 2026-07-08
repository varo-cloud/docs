# Varo Cloud Documentation

The source for the [Varo Cloud](https://varocloud.io) documentation site.

- Pages are MDX files with YAML frontmatter.
- Site configuration and navigation live in `docs.json`.

## Local development

Install the CLI, then run the preview server from the repo root (where `docs.json` lives):

```bash
npm i -g mint
mint dev
```

The preview is served at `http://localhost:3000`.

## Publishing

Changes pushed to the default branch are deployed to production automatically.

## Troubleshooting

- Preview server won't start: run `mint update` to get the latest CLI.
- A page returns 404: confirm you're running from the folder that contains `docs.json`.
