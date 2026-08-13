# Northstar Platform Docs

A small fictional documentation site for experimenting with [Docusaurus](https://docusaurus.io/) and [Vale](https://vale.sh/). It contains realistic Markdown content without depending on a real product or cloud account.

## Run the site

```bash
npm install
```

```bash
npm run start
```

Open the local URL printed by Docusaurus, then edit files under `docs/`. The site reloads after changes.

## Check the site

```bash
npm run build
```

This generates the static site in `build/` and reports broken links or invalid front matter.

## Try Vale

The repository includes a tiny custom Vale style in `styles/Northstar/`. Install Vale with your preferred package manager, then run:

```bash
vale docs
```

`whitelist` and `blacklist` are intentionally flagged as suggestions in the sample content, so you can see Vale working. The rules are examples only; replace them with your team's agreed style guide or a published style package.

## What to explore

- `docs/`: front matter, Markdown, code blocks, admonitions, and cross-links.
- `sidebars.ts`: a deliberately manual sidebar so you can change navigation order.
- `docusaurus.config.ts`: navigation, edit links, title, and metadata.
- `.vale.ini` and `styles/Northstar/`: a small local linting configuration.
