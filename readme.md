# What Does It Do?
A fast and simple way to encode a javascript object into a string that can be used for POST/GET params for xhr2 requests.

## How To Use
```sh
npm i serialize-for-xhr --save
```

```js
var serialize = require('serialize-for-xhr')

console.log(serialize({foo: "hi there", bar: { blah: 123, quux: [1, 2, 3] }}));
// foo=hi%20there&bar%5Bblah%5D=123&bar%5Bquux%5D%5B0%5D=1&bar%5Bquux%5D%5B1%5D=2&bar%5Bquux%5D%5B2%5D=3
```
