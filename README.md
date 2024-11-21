# prettier-config-smarthr

A sharable prettier config for SmartHR.

## Information

This repository has been archived.  
The project has been moved to [kufu/tamatebako/packages/prettier-config-smarthr](https://github.com/kufu/tamatebako/tree/master/packages/prettier-config-smarthr) and is being actively maintained there.

---

## Installation

prettier-config-smarthr is available as an  [npm package](https://www.npmjs.com/package/prettier-config-smarthr).

```sh
// with npm
npm install --save-dev prettier-config-smarthr

// with yarn
yarn add --dev prettier-config-smarthr
```

## How to use

Edit `package.json`.

```json
{
  "name": "your project",
  "prettier": "prettier-config-smarthr"
}
```

If you don’t want to use `package.json`, you can use any of the supported extensions to export a string, e.g. `.prettierrc.json`:

```
"prettier-config-smarthr"
```

Check here for details : https://prettier.io/docs/en/configuration.html

### How to extend

Create `.prettierrc.js` , import the file in a `.prettierrc.js` file and export the modifications.

```js
module.exports = {
  ...require("prettier-config-smarthr"),
  "arrowParens": "avoid",
};
```
