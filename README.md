# tdd-very-quickstart-js
minimal setup for katas in node

### Starting with an empty directory
1) Run command: npm init (use all defaults)
2) Install mocha, chai:

```npm install --save-dev mocha chai```

3) Create file .mocharc.js to top directory of project:

```
module.exports = {
  "spec":  "./src/**/*.spec.js",
  "recursive": true,
  "watch": true
};
```

5) Run command: "mocha", from top directory, or set "mocha" as the "test" command, in package.json
6) Inside a "src" directory, add .js code, and .spec.js tests as desired, and test results should update, live, in the terminal
