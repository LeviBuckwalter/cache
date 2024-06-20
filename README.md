```js
let {store, retrieve, discard} = await import("./functions/endUser.js")
let { cache, redefineCache } = await import("./cache.js")
let { readCache, writeCache } = await import("./functions/fileIO.js")
let { customStringify, customParse } = await import("./functions/parseAndStringify.js")
await readCache()
```