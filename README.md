### Install  
```
npm install -D @fantaptik/webpack-config
```

### Webpack Config
```js
const fantaptikWebpack = require( '@fantaptik/webpack-react' );

module.exports = {
    stats : {
        ...fantaptikWebpack.stats,
    },
    externals : {
        ...fantaptikWebpack.externals,
    },
}
```