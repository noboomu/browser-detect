# browser-detect

> Simplify detecting your browser.

----

```plaintext
This library helps you detect user's browser and version.
And this project is focusing to support client and server(Node).
```

## Getting Started

### Installation

**\* NPM**

```bash
$ npm install browser-detect --save
```

**\* Bower**

```bash
$ bower install browser-detect --save
```

**\* Yarn**

```bash
$ yarn install browser-detect --save
```

**\* Download zip**

[Download zip file from this link](https://github.com/KennethanCeyer/browser-detect/archive/master.zip)

----

### How to use

**Client (browser)**

Add following code in your `head` tag.

```html
<script src="node_modules/browser-detect/dist/browser-detect.min.js"></script>
```

And follow this code to detect browser.

```javascript
console.log(browser());
```

```bash
> { name: 'MSIE', version: 9 } # IE 9
```

**Server (node)**

Just simple :trollface:

```javascript
var browser = require('browser-detect');
var result = browser();
console.log(result);
```

```bash
> { name: 'MSIE', version: 9 } # IE 9
```