# delay.js

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url] [![Dependency status][david-dm-image]][david-dm-url] [![Dev Dependency status][david-dm-dev-image]][david-dm-dev-url]

Promisified `setTimeout`.

## Installation
```
npm install --save delay.js
```

## Usage
Basic usage:
```javascript
import delay from 'delay.js'

async function foo() {
  // ... do something
  await delay(1000) // sleep 1 second
  // ... continue
}
```

[npm-url]: https://npmjs.org/package/delay.js
[downloads-image]: http://img.shields.io/npm/dm/delay.js.svg
[npm-image]: http://img.shields.io/npm/v/delay.js.svg
[david-dm-url]:https://david-dm.org/inker/delay.js
[david-dm-image]:https://david-dm.org/inker/delay.js.svg
[david-dm-dev-url]:https://david-dm.org/inker/delay.js#info=devDependencies
[david-dm-dev-image]:https://david-dm.org/inker/delay.js/dev-status.svg
