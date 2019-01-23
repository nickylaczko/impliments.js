# impliments.js
Impliment a Npm module into your code easier.
## Install
`` npm install impliments``
## Options
Impliment needs two specific options
```
imppliments(xo, {
	npm: (true or false),
	testFile: 'path' // optional
})
```
## Usage
-----------
```
const impliments = require('impliments')

var some_deps = ['underscore', 'cheerio', 'bluebird']
impliments(some_deps, { Npm: true })

function testing () {
	/**
	some code .....
	**/
}

```