# prettier-config-cristianl

## Changes to default config

- No semicolons
- Use single quotes
- 72 characters per line

## Usage

Add to *package.json*:

```json
{
  "prettier": "@cristianl/prettier-config"
}
```

If you must override this config for a project, do not add that line to package.json. Instead, create a *prettier.config.js* file:

```js
module.exports = {
  ...require('@cristianl/prettier-config'),
  // custom properties below
}
```
