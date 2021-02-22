## dnb-hugo/remark-config

This is a remark preset used across DNB projects.

This configuration uses [remark-preset-lint-recommended](https://github.com/remarkjs/remark-lint/tree/main/packages/remark-preset-lint-recommended) with some additions on it's own.

You probably won't need this ;)

### Installation

```shell script
npm install -D dnb-hugo/remark-config
```

### Configuration

Put the following into `.remarkrc` in the root of your project. Remove the `write-good` line if you want to ensure the quality of text. It tends to be overzealous though, so it's deactivated by default.

```json
{
  "plugins": [
    "@dnb-hugo/remark-config",
    ["remark-lint-write-good", false]
  ]
}
```

### Remark Setup Rules
