### Actual

```txt
$ node --loader esbuild-node-loader index.mts
Error: Invalid loader: "mts" (valid: js, jsx, ts, tsx, css, json, text, base64, dataurl, file, binary)
```

### Expected

No error

```sh
$ node --loader esbuild-node-loader index.mts
42
```
