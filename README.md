# @nitpum/prettier-config

[![npm version](https://img.shields.io/npm/v/@nitpum/prettier-config.svg?style=flat)](https://www.npmjs.com/package/@nitpum/prettier-config)

Shared Prettier config

## Installation

```bash
yarn add -D @nitpum/prettier-config
```

## Usage

Add the `prettier` key to `package.json` file

```json
  "prettier": "@nitpum/prettier-config"
```

OR

Create `.prettierrc`, `.prettierrc.json` or `.prettierrc.yml`

```
"@nitpum/prettier-config"
```

OR

Create `.prettierrc.js` or `.prettier.config.js` file

```js
module.exports = {
  ...require('@nitpum/prettier-config'),
}
```

## Support

If you think this is useful, you can support me ;)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/F1F21LCOB)

## License

[MIT License](LICENSE)
