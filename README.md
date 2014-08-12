# karma-jasmine-html-reporter-livereload

> Reporter that dynamically shows tests results at debug.html page and can be reloaded with livereload.

Forked from [karma-jasmine-html-reporter](https://www.npmjs.org/package/karma-jasmine-html-reporter)

## Installation

The easiest way is to keep `karma-jasmine-html-reporter-livereload` as a devDependency in your `package.json`.
```json
{
  "devDependencies": {
    "karma": "~0.10",
    "karma-jasmine-html-reporter-livereload": "~1.0"
  }
}
```

You can simple do it by:
```bash
npm install karma-jasmine-html-reporter-livereload --save-dev
```

## Configuration
```js
// karma.conf.js
module.exports = function(config) {
  config.set({

    reporters: ['html']

  });
};
```

You can pass list of reporters as a CLI argument too:
```bash
karma start --reporters html
```
