# jest-playwright-boilerplate
A node package template to quickly jump into Playwright testing with Jest

## Requirements
* Node.js >= 10.15.0
* Playwright >= 0.12.1
* Jest >= 25
* Yarn >= 1.22.5

## Links
* [Playwright Docs](https://playwright.dev/docs/api/class-playwright)
* [jest-playwright](https://github.com/playwright-community/jest-playwright)
* [Jest Docs](https://jestjs.io/docs/getting-started)

## Babel config
This template includes a babel preset for jest, and a `babel.config.js` file to account for async/awaits. If you would rather not utilize babel as a transpiler, you will simply:

  * remove "@babel/core", "@babel/preset-env", and "babel-jest" from the `package.json` file
  * delete, or comment out the contents of the `babel.config.js` file
  * replace any `import` statements with `require` statements
