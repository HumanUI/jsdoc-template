# Braintree JSDoc Template for @freshes

### 使用方法

``` bash
yarn add -D @freshes/jsdoc-template
```

编辑你项目的 `package.json` 文件：

```json
"script": {
  "docs": "jsdoc -r -c ./docs/jsdoc.json"
}
```

编辑你项目的 `./docs/jsdoc.json` 文件：

```json
"opts": {
  "template": "node_modules/jsdoc-template",
  "destination": "./docs/apis"
}
```

## 感谢

- [github.com/nijikokun/minami](https://github.com/nijikokun/minami)
- [the Taffy Database library](http://taffydb.com/)
- [Underscore Template library](http://documentcloud.github.com/underscore/#template)
- [Algolia DocSearch](https://community.algolia.com/docsearch/)
