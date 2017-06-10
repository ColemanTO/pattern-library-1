# Pattern Library

## Installation

### NPM

```bash
$ npm install deque-pattern-library
```

### Bower

```bash
$ bower install deque-pattern-library
```

## Usage

Just drop the css and js into your page:

```html
<html>
  <head>
    ...
    <link rel="stylesheet" href="./node_modules/deque-pattern-library/css/cauldron.min.css" />
  </head>
  <body>
    ...
    <script src="./node_modules/deque-pattern-library/js/cauldron.min.js"></script>
  </body>
</html>
```

## Getting started

Please refer to the [wiki](https://github.com/dequelabs/pattern-library/wiki)

## Development

- `npm install`
- `npm run build` or for development - `npm run dev` which will rebuild when files are changed

__NOTE__: if a new component or composite is added, remember to create a quick [wiki](https://github.com/dequelabs/pattern-library/wiki) entry explaining what is absolutely necessary in using this widget.

### Testing
Testing is done using mochify along with the 'chai' assertion library (`assert.equal(!!0, false)`).  The `test/` directory structure matches the `lib/` directory.  This means that if you're testing `lib/components/foo/index.js`, you would create a test in `test/components/foo/index.js`.  See the `test/` directory for examples.  The tests are browserified and transpiled before running in the phantomjs headless browser so you can `require` stuff and use es6 syntax in the tests.

```bash
$ npm run test
```

or to have a watcher re-run tests every time you add a new test:

```bash
$ npm run test:dev
```

### Releases
Orphan branch dist-only releases:

 * https://gist.github.com/schne324/6ca72fac89f35d961a0d
