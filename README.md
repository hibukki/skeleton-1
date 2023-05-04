# Run dev

## Frontend

```bash
yarn workspace frontend dev
```

# Deploy production

## Frontend

### Create a cloudflare-pages account

Including getting an API token

See [User Guide][CF pages deploy user guide]

### Set the secrets in github

See the secrets in the file [`.github/workflows/publish-frontend.yml`][frontend deploy file]

### Push to `main`

### See deployment at github actions

In your github repo

### It should be deployed

At $YOUR_PROJECT_NAME.pages.dev

[CF pages deploy user guide]: https://github.com/marketplace/actions/cloudflare-pages-github-action
[frontend deploy file]: .github/workflows/publish-frontend.yml
