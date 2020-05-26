<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i>Where I quickly test stuffs</i>
    <br>
    <br>
    <img src="https://github.com/garronej/my-ts-tests/workflows/ci/badge.svg">
    <img src="https://img.shields.io/bundlephobia/minzip/my-ts-tests">
    <img src="https://img.shields.io/npm/dw/my-ts-tests">
</p>
<p align="center">
  <a href="https://github.com/garronej/my-ts-tests">Home</a>
  -
  <a href="https://github.com/garronej/my-ts-tests">Documentation</a>
  -
  <a href="https://gitter.im/my-ts-tests/">Chat</a>
</p>

---

# Install / Import

```bash
> npm install --save my-ts-tests
```
```typescript
import { myFunction, myObject } from 'my-ts-tests'; 
```

Specific imports:

```typescript
import { myFunction } from 'my-ts-tests/myFunction';
import { myObject } from 'my-ts-tests/myObject';
```

## Import from HTML, with CDN

Import it via a bundle that creates a global ( wider browser support ):  

```html
<script src="//unpkg.com/my-ts-tests/bundle.min.js"></script>
<script>
  const { myFunction, myObject } = my_ts_tests;
</script>
```

Or import it as an ES module:  

```html
<script type="module">
  import { myFunction, myObject } from '//unpkg.com/my-ts-tests/zz_esm/index.js';
</script>
```

*You can specify the version you wish to import:* [unpkg.com](https://unpkg.com)
    
## Contribute

```bash
npm install
npm run build
npm test
```
