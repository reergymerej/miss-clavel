As Miss Clavel said, ["Something is not
right."](https://www.youtube.com/watch?v=qgqJSxviu6Q)

```
node index.js

internal/modules/cjs/loader.js:638
    throw err;
    ^

Error: Cannot find module 'vscode'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:636:15)
    at Function.Module._load (internal/modules/cjs/loader.js:562:25)
    at Module.require (internal/modules/cjs/loader.js:692:17)
    at require (internal/modules/cjs/helpers.js:25:18)
    at Object.<anonymous> (/Users/jeremygreer/Desktop/delete-me/node_modules/vscode-languageclient/lib/client.js:10:18)
    at Module._compile (internal/modules/cjs/loader.js:778:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:789:10)
    at Module.load (internal/modules/cjs/loader.js:653:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:593:12)
    at Function.Module._load (internal/modules/cjs/loader.js:585:3)
  ```
