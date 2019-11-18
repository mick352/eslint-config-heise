# @heise/eslint-config

[![Greenkeeper badge](https://badges.greenkeeper.io/heiseonline/eslint-config-heise.svg)](https://greenkeeper.io/)

Die eslint-Konfiguration von Heise.

```sh
$ cd my-project
$ yarn add --dev @heise/eslint-config #oder mit npm
$ npm install --save-dev @heise/eslint-config
```

`my-project/.eslintrc.js` bearbeiten:

```js
module.exports = {
  extends: '@heise',
  // Optional: Weitere Konfiguration, z.B.:
  // parser: 'babel-eslint',
}
```
