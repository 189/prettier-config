# prettier-config

## install

```
yarn add @shangwenwang/prettier-config
```

## Edit

Edit `package.json`

```
{
    // ...
    "prettier": "@shangwenwang/prettier-config"
}
```

Or make file `.prettierrc.js`

```
const base = require("@shangwenwang/prettier-config");
module.export = {
    ...base,
    // your rule override
    ...
}

```
