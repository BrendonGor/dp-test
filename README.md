# dp-template

Minimal authoring template for docs publishing.

## What stays in this repo

- `site.config.yaml`
- `content/**/*.md`
- `.github/workflows/publish.yml`

All validation/build/publish logic lives in the public `dp-publish-workflow` action repo.

## Publish target

The workflow is configured for the deployed `dp-workers` endpoint:

- `publish URL`: `https://dp-workers.brendongorelik.workers.dev/v1/publish`
- `OIDC audience`: `dp-workers.brendongorelik.workers.dev-publish-v0`
- `root domain`: `dp-workers.brendongorelik.workers.dev`
