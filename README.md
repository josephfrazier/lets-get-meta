# lets-get-meta

Extract meta tags from an HTML string in Node.js (not browsers)

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install lets-get-meta --save
```

## Usage

```js
var getMeta = require("lets-get-meta")

// Pass and HTML string
getMeta("<meta name='page' content='index'><meta name='description' content='This is the index page'>")

// Get back an object
{
  page: "index",
  description: "This is the index page"
}

```

## Tests

```sh
npm install
npm test
```

## Dependencies

- [cheerio](https://github.com/MatthewMueller/cheerio): Tiny, fast, and elegant implementation of core jQuery designed specifically for the server


## Dev Dependencies

- [mocha](https://github.com/visionmedia/mocha): simple, flexible, fun test framework


## License

ISC

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_
