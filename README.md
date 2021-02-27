Book Finder
===========

## Requirements
You only need <b>node.js</b> `>=10.13.0` pre-installed and you’re good to go.

If you don’t want to work with lodash, just remove it from the node packages.

## Usage
Download OR git clone to use this repository as a template
```sh
git clone https://github.com/palanikphp/book-finder-starter.git
```

## Setup
Install dependencies
```sh
$ npm install
```

## Development
Build the app in dev mode and run webpack serve with livereload and autocompile on [http://localhost:8080/](http://localhost0:8080/)
```sh
$ npm run dev
```
## Production
Build the app in production mode
```sh
$ npm run build
```

## [webpack](https://webpack.js.org/)
If you're not familiar with webpack, [webpack serve](https://github.com/webpack/webpack-cli/blob/master/packages/serve/README.md#webpack-cli-serve) will serve the static files in your build folder and watch your source files for changes.
When changes are made the bundle will be recompiled. This modified bundle is served from memory at the relative path specified in publicPath.
