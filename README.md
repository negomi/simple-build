simple-build
============

A minimal project template for static sites, with a pure npm scripts build process.

## Features

* Development server with LiveReload
* Browserify so you can use CommonJS `require()` statements
* SCSS preprocessing (with Autoprefixer for the production build)
* Mocha for testing (assertion library is up to you)
* Built-in deployment to gh-pages

## Usage

* Assets go in `public`
* JS goes in `src/js/` (remember to `require()` all your files in `src/js/main.js`)
* SCSS goes in `src/sass/` (remember to `@import` all your files in `src/sass/main.scss`)

Start the server:
```
npm start
```

Run the tests:
```
npm test
```

Deploy to gh-pages:
```
npm deploy
```
