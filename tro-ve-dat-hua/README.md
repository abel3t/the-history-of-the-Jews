# Trở về Đất Hứa

* * 
## Getting Started With TypeScript <a id="getting-started-with-typescript"></a>

TypeScript compiles into JavaScript. JavaScript is what you are actually going to execute \(either in the browser or on the server\). So you are going to need the following:

* TypeScript compiler \(OSS available [in source](https://github.com/Microsoft/TypeScript/) and on [NPM](https://www.npmjs.com/package/typescript)\)
* A TypeScript editor \(you can use notepad if you want but I use [vscode 🌹](https://code.visualstudio.com/) with an [extension I wrote](https://marketplace.visualstudio.com/items?itemName=basarat.god). Also [lots of other IDES support it as well](https://github.com/Microsoft/TypeScript/wiki/TypeScript-Editor-Support)\)

### TypeScript Version <a id="typescript-version"></a>

Instead of using the _stable_ TypeScript compiler we will be presenting a lot of new stuff in this book that may not be associated with a version number yet. I generally recommend people to use the nightly version because **the compiler test suite only catches more bugs over time**.

You can install it on the command line as

And now the command line `tsc` will be the latest and greatest. Various IDEs support it too, e.g.

* You can ask vscode to use this version by creating `.vscode/settings.json` with the following contents:

```text
{  "typescript.tsdk": "./node_modules/typescript/lib"}
```

### Getting the Source Code <a id="getting-the-source-code"></a>

The source for this book is available in the books github repository [https://github.com/basarat/typescript-book/tree/master/code](https://github.com/basarat/typescript-book/tree/master/code) most of the code samples can be copied into vscode and you can play with them as is. For code samples that need additional setup \(e.g. npm modules\), we will link you to the code sample before presenting the code. e.g.

`this/will/be/the/link/to/the/code.ts`

With a dev setup out of the way let's jump into TypeScript syntax.

