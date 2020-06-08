# prettier-config-cristianl

## Changes to default config

- No semicolons
- Use single quotes
- 72 characters per line

## Usage

Add to *package.json*:

```json
{
  "prettier": "prettier-config-cristianl"
}
```

If a project needs a config override, do not add the above line to package.json. Instead, create a *prettier.config.js* file:

```js
module.exports = {
  ...require('prettier-config-cristianl'),
  // custom properties below
}
```
