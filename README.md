#### Usage 

```sh
yarn add @tenjojeremy/prettier-config
```

```sh
yarn add prettier
```

package.json
```json
{
  "scripts": {
    "pretty": "prettier \"**/*.js\" --write"
  },
  "prettier": "@tenjojeremy/prettier-config"
}
```

#### Config 
```js
module.exports = {
  printWidth: 90,
  trailingComma: 'all',
  tabWidth: 2, 
  semi: false,
  singleQuote: true,
  jsxSingleQuote: true,
  arrowParens: 'always',
}
```
