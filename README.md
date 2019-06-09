# tdd-very-quickstart-js
minimal setup for katas in node

### Starting with an empty directory
1) Run command: npm init (use all defaults)
2) Install jasmine, karma, and headless Chrome launcher:

```npm install --save-dev jasmine-core karma karma-jasmine karma-chrome-launcher```

3) Create file karma.conf.js:

```
module.exports = function(config) {
    config.set({
        frameworks: ['jasmine'],

        files: [
            'src/**/*.js'
        ],

        reporters: ['progress'],

        browsers: ['ChromeHeadless']
    })
}
```
4) Create src directory
5) Run command: karma start karma.conf.js, in top directory
6) Add .js code, and .spec.js tests as desired
