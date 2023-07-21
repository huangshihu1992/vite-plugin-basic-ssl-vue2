# plugin-basic-ssl-vue2 [![npm](https://img.shields.io/npm/v/@vitejs/plugin-basic-ssl.svg)](https://www.npmjs.com/package/plugin-basic-ssl-vue2)

A plugin to generate untrusted certificates which still allows to access the page after proceeding a wall with warning.

In most scenarios, it is recommended to generate a secure trusted certificate instead and use it to configure [`server.https`](https://vitejs.dev/config/server-options.html#server-https)

## Usage

```js
// vite.config.js
import basicSsl from 'plugin-basic-ssl-vue2'

export default {
  plugins: [
    basicSsl()
  ]
}
```
 
## License

MIT
