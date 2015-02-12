# Rails API and AngularJS Template

This template can serve as a starting point for [Rails API](https://github.com/rails-api/rails-api) and AngularJS based application. AngularJS was scaffold using [Yeoman](http://yeoman.io) with [yo angular generator](https://github.com/yeoman/generator-angular) version 0.11.1. So you can utilize all the goodies offered by yo angular generator.

## Prerequisites
1. node
2. npm
3. grunt
4. bower

## Getting started

Clone the repository and navigate to repository root directory and run following commands

```
npm install
bower install
```

## Source files

Angular source files are present in `app/angular` directory.

## Build & development

Run `grunt` for building the javascript and CSS files. The build javascript and CSS files are transferred to `public` directory after build.

## Testing

Running `grunt test` will run the unit tests with karma. `karma.conf.js` is present in `test` directory.
