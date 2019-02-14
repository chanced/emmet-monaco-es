# emmet-monaco-es

<p>
  <a href="https://npmcharts.com/compare/emmet-monaco-es?minimal=true"><img src="https://img.shields.io/npm/dm/emmet-monaco-es.svg" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/emmet-monaco-es"><img src="https://img.shields.io/npm/v/emmet-monaco-es.svg" alt="Version"></a>
  <a href="https://www.npmjs.com/package/emmet-monaco-es"><img src="https://img.shields.io/npm/l/emmet-monaco-es.svg" alt="License"></a>
</p>

Emmet Plugin for [monaco-editor](https://github.com/Microsoft/monaco-editor)

**compatible with monaco-editor v0.12.0 and above**

Treeshaking support

Source codes are well commented if you want to figure out how it works

# Install

```shell
$ npm install emmet-monaco-es
```

# Example

```javascript
import { emmetHTML, emmetCSS } from "emmet-monaco-es";

// both `emmetHTML` and `emmetCSS` are used the same way
emmetHTML(
  editor, // monaco editor instance
  monaco // monaco self. If not provided, will use window.monaco instead
);
```

# License

MIT
