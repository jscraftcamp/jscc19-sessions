# WebAssembly Europe
_Session by Thomas Tränkler (@ttraenkler)_

* organizer of the [Munic WebAssembly Meetup](https://www.meetup.com/WebAssembly/) [videos](https://www.youtube.com/channel/UCdV8K8PaJgxgmQ83Lr4-WVQ)
* runs the WebAssembly news site [webassembly.eu](https://webassembly.eu/)


## History of WebAssembly

* [Luke Wagner](https://twitter.com/luke_wagner) and ...
* inspired by asm.js
* because they tried to get game engines to run in the browser and hit some hard limits (and need predictive performance)

## Features

* binary distribution ("assembly without the os-architecture part")
* tightly integration with javascript engine
  * javascript can call webassembly, webassembly can call javascript
* sandboxed for security
* integrate multiple languages in your components

## Status

* [caniuse](https://caniuse.com/#feat=wasm)
* "MCP" embedded in main browsers, inside the javascript engine


## Built on top of WebAssembly...

* autodesk: [autocad viewer](https://www.autodesk.com/products/autocad-web-app/overview) on the web built with webassembly [](www
* google earth (beta)
* sass: [not yet](https://github.com/sass/node-sass/issues/2011)
* could be used for codecs as well that you don't have to wait for browser implementations

## Languages that compile to WebAssembly

* everything clang/llvm
* [AssemblyScript](https://docs.assemblyscript.org/)

## Q and A

* Serverside WebAssembly
  * node supports it
  * see [talk on WASI](https://www.youtube.com/watch?v=YhNkspvw37w)
  * see also [innative](https://hub.packtpub.com/introducing-innative-an-aot-compiler-that-runs-webassembly-using-llvm-outside-the-sandbox-at-95-native-speed/) - runs WebAssembly using LLVM outside the Sandbox at 95% native speed
  
  
## See also

* [WebAssembly Weekly](https://twitter.com/wasmweekly)
* Join the [discord](https://discordapp.com/invite/nEFErF8)
* [Awesome WebAssembly](https://github.com/mbasso/awesome-wasm/blob/master/README.md)
