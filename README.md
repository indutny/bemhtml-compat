# BEMHTML-COMPAT [![Build Status](https://secure.travis-ci.org/indutny/bemhtml-compat.png)](http://travis-ci.org/indutny/bemhtml-compat)

Transpiler from old bemhtml source code to new javascript-compatible code.

## Usage

```javascript
var bemcompat = require('bemhtml-compat');

bemcompat.transpile('block b1, tag: "a"');
/* Returns:
 *   match(this.block === 'b1', this._mode === 'tag')('a');
 */
```
