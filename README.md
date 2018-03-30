


WoodenLog
=========
This is a test project for learning MEAN stack better. I'm learning that from this book: https://www.amazon.com/MEAN-Stack-Development-Elad-Elrom-ebook/dp/B01N5AIZ7G


Minimalist log node messages module to add colors for console.log for specific type of log.

## Installation
```shell
npm install woodenlog --save
```

## Usage
```js
var woodenlog = require('woodenlog');
// woodenlog.configurate(null, 'white', 'green', 'red');
woodenlog.log('just log!');
woodenlog.warn('this is a warning!');
woodenlog.error('this is an error!');
```

## Tests
```shell
npm test
```
## Release History
* 1.0.0 Initial release