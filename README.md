# Nobbers Orbital Command

Index page

## Development

Prereqs:

- Install npm / nvm
- Install pnpm with `npm install -g pnpm`

To launch the development server locally use:

```bash
pnpm start
```

**Note**: Because of gh-pages deployment needs base url to get set for things to work
locally you will need to comment out the "base" option in `astro.config.mjs`.

## Adding New Link

To add a new link, add a markdown file in the [content/links](./src/contant/links) folder.
See the existing ones to know what meta data is present.