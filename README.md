# nim-codemirror-mode
A codemirror mode for nim.

Mostly taken from the work of PMunch [here](https://github.com/PMunch/nim-playground-frontend).

To register the mode, `require` the mode and the call the only exported function, `register`, with the CodeMirror object as argument:

```js
require("nim-codemirror-mode").register(CodeMirror)
```