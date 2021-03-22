<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i></i>
    <br>
    <br>
    <img src="https://github.com/garronej/edit-dockerfile/workflows/ci/badge.svg?branch=main">
    <img src="https://img.shields.io/bundlephobia/minzip/edit-dockerfile">
    <img src="https://img.shields.io/npm/dw/edit-dockerfile">
    <img src="https://img.shields.io/npm/l/edit-dockerfile">
</p>
<p align="center">
  <a href="https://github.com/garronej/edit-dockerfile">Home</a>
  -
  <a href="https://github.com/garronej/edit-dockerfile">Documentation</a>
</p>

# Install / Import

```bash
$ npm install --save edit-dockerfile
```

```typescript
import { myFunction, myObject } from "edit-dockerfile";
```

Specific imports:

```typescript
import { myFunction } from "edit-dockerfile/myFunction";
import { myObject } from "edit-dockerfile/myObject";
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):

```html
<script src="//unpkg.com/edit-dockerfile/bundle.min.js"></script>
<script>
    const { myFunction, myObject } = edit_dockerfile;
</script>
```

Or import it as an ES module:

```html
<script type="module">
    import { myFunction, myObject } from "//unpkg.com/edit-dockerfile/zz_esm/index.js";
</script>
```

_You can specify the version you wish to import:_ [unpkg.com](https://unpkg.com)

## Contribute

```bash
npm install
npm run build
npm test
```
