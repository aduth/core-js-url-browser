# core-js-url-browser

[`core-js`](https://github.com/zloirock/core-js)'s [URL](https://developer.mozilla.org/en-US/docs/Web/API/URL) polyfills, prebundled for the browser using [Browserify](https://github.com/browserify/browserify).

Includes:

- [`new URL()`](https://developer.mozilla.org/en-US/docs/Web/API/URL/URL)
- [`URL#toJSON`](https://developer.mozilla.org/en-US/docs/Web/API/URL/toJSON)
- [`URLSearchParams](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams)

## Installation

Install using [npm](https://npmjs.com):

```
npm install core-js-url-browser
```

## Usage

Included are two browser-ready scripts: `url.js` and `url.min.js` (a minified version). Copy and/or reference directly from a `script` tag:

```html
<script src="./node_modules/core-js-url-browser/url.min.js"></script>
```

See also [noted implementation caveats](https://github.com/zloirock/core-js#caveats-when-using-url-and-urlsearchparams).

## Frequently Asked Questions

### Why?

You might not need this if you are using Node.js or already use a bundler as part of your build process. In those cases, you can use `core-js` directly. This package is useful in cases where you do not have this option; either that you need to load the script directly in the browser, or your build consists of simple file copies of your dependency scripts. In these cases, you may find `core-js-url-browser` to be a convenient alternative to creating or reworking a build process.

### What version of `core-js` is used?

The versioning of this package aligns to the version from `core-js` from which it was built. This is a manual process, and is not automatically kept in sync as new version of `core-js` are released. If there are changes that you need from a newer version of `core-js`, [submit an issue](https://github.com/aduth/core-js-url-browser/issues/new) and I can prepare an updated release.

## License

`core-js-url-browser`

Copyright (c) 2020 Andrew Duthie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

`core-js`

Copyright (c) 2014-2020 Denis Pushkarev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
