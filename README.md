# nerv-test-utils
> Mock [react-test-utils](https://facebook.github.io/react/docs/test-utils.html) used for Nerv.js

## Usege

```javascript
// enzyme in Jest
module.exports = {
  "moduleNameMapper": {
    "react-dom/server": "nerv-server",
    "react-addons-test-utils": "nerv-test-utils",
    "react": "nerv-compat",
    "react-dom": "nerv-compat"
  }
}
```
