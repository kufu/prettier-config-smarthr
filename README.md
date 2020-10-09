# prettier-config-smarthr

A sharable prettier config for SmartHR.

## Install

```sh
yarn add --dev prettier-config-smarthr
```

## How to use

Edit `package.json`

```json
{
  // ...
  "prettier": "prettier-config-smarthr"
}
```

### how to extend

Create `.prettierrc.js` , import the file in a `.prettierrc.js` file and export the modifications.

```js
module.exports = {
  ...require("prettier-config-smarthr"),
  "arrowParens": "avoid",
};
```
