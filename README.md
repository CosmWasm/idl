🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨
The content of this repo was moved to cosmwasm (https://github.com/CosmWasm/cosmwasm/pull/2028)
🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨🚨


# CosmWasm IDL docs

[Here's the live version.](https://cosmwasm.github.io/idl/)

Built using [_MkDocs_](https://www.mkdocs.org/).

## Development

The `gh-pages` branch is for the release artifacts. Don't modify it directly.
Any modifications will get overwritten during next deployment.

The _MkDocs_ project maintains a quality
[User Guide](https://www.mkdocs.org/user-guide/).

### Prerequisites

```sh
pip install mkdocs mkdocs-bootswatch
```

### Iterating

```sh
mkdocs serve
```

This should get you a locally deployed website. If you open it in your browser,
it will auto-update as you make changes to the `.md` docs.

### Deploying

```sh
mkdocs gh-deploy
```

As long as you have write permissions to this repo, this should handle
everything! It will update the `gh-pages` branch with the newly generated static
website. GitHub will then pick it up and serve.
