nor-jquery
==============

[jQuery](https://github.com/jquery/jquery) NPM wrapper for easier 
use with browserify.

This repository does not contain any source code for jQuery (it's not fork).

It declares a dependency for current jQuery from Github. When you do 
`require('nor-jquery')` you will actually include 
`node_modules/jquery/scripts/bundled/html5/native.jquery`. 

***Please note:*** The actual version for jQuery might be any 1.x even if 
this module lists the version as 1.x.

State
-----

Currently this package is not working.

Usage
------------

You may use it from the NPM in `package.json`:

```javascript
{
  "dependencies": {
    "nor-jquery": "1.*"
  }
}
```

..or directly from Github in `package.json`:

```javascript
{
  "dependencies": {
    "jquery": "Sendanor/nor-jquery"
  }
}
```
