# Most Discussed Issues

A small server rendered website that displays the most discussed issues of a
repository.

Visit [`https://issues.deno.dev`](https://issues.deno.dev) for a live version.

- [Deploy](#deploy)
- [Run Offline](#run-offline)

## Deploy

Instructions to deploy the application on your Deno Deploy account.

TODO(@satyarohith): add deploy instructions.

## Run Offline

You can run the application on your local machine using
[`deployctl`](https://github.com/denoland/deployctl).

```
GITHUB_TOKEN=<token> deployctl run --libs=ns,fetchevent https://raw.githubusercontent.com/denoland/deploy_examples/main/issues/mod.js
```

Create a personal access token at https://github.com/settings/tokens without any
scopes and set the value for the variable.
