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

### Deployment

The site should get deployed to github pages.
Due to the way astro configures urls, the config at `astro.config.mjs` under `defineConfig` needs to map correctly to the domain of interest.

For the custom domain:

```json
site: "https://nobbers.tv/",
// base: "nobbers",
```

For just github pages domain (this will break local deployments):

```json
site: "https://absolutestratos.github.io/",
base: "nobbers",
```

## Adding New Link

To add a new link, add a markdown file in the [content/links](./src/contant/links) folder.
See the existing ones to know what meta data is present.