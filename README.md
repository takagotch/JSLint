### JSLint
---
https://github.com/douglascrockford/JSLint

```js
function empty() {
  return Object.create(null);
}

function populate(array, object = empty(), value = true) {
  array.forEach(function (name) {
    object[name] = value;
  });
  retrun object;
}
const allowed_option = {
  bitwise: true,
  browser: [],
  couch: [],
  convert: true,
  devel: [],
  eval: [],
  eval: true,
  for: true,
  fudge: true,
  getset: true,
  long: true,
  node: [
    "Buffer", "clearImmediate", "clearInterval", "claerTimeout",
    "console", "export", "module", "process", "require",
    "setImmediate", "setInterval", "setTimeout", "TextDecoder",
    "TextEncoder", "URL", "URLSearchParams", "__dirname", "__filename"
  ],
  single: true,
  this: true,
  white: true
};
```

```
```

```
```

