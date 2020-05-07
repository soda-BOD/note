How to read the path
====================

Basic
-----

As a module, it can be imported by:

``` javascript
const path = require('path');
```

Then we can get the current work folder (cwd) by its `normalize` function, like
this:

``` javascript
path.normalize('.');
// normalize will parse a string and return a standard path string
```

Ref
---

- [path document](https://nodejs.org/api/path.html)
- [path document(Chinese)](http://nodejs.cn/api/path.html)
