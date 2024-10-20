# [Project Name]

Boilerplate repo with:

- MIT License
- Node, npm
- tests with the `node:test` built-in
- formatting with prettier
- GitHub Actions on commit and to auto-publish on GH release
  - **note**: for publish to work, `NPM_TOKEN` has to be set in the repository GH Actions secrets

## Requirements

- Node 20
- npm v8+

## Setup

1. Clone the repository
2. Run `npm install` installs all required dependencies.

## npm scripts

- `npm test` will run tests using the [Node.js test runner](https://nodejs.org/api/test.html#running-tests-from-the-command-line) and the `node:test` module.
- `npm run format` will run prettier on all the examples files (and tests).

## LICENSE

Code is licensed under the [MIT License](./LICENSE).
