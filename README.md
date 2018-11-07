[![Build Status](https://travis-ci.org/mistaguy/metvn.svg?branch=master)](https://travis-ci.org/mistaguy/metvn)
[![Code Climate](https://img.shields.io/codeclimate/maintainability/mistaguy/metvn.svg?style=flat-square)](https://codeclimate.com/github/mistaguy/metvn)
[![Dependency Status](https://david-dm.org/mistaguy/metvn.svg)](https://david-dm.org/mistaguy/metvn)
[![Dev Dependency Status](https://david-dm.org/mistaguy/metvn.svg#info=devDependencies)](https://david-dm.org/mistaguy/metvn#info=devDependencies)
[![Known Vulnerabilities](https://snyk.io/test/github/mistaguy/metvn.svg)](https://snyk.io/test/github/mistaguy/metvn)
![Node 6](https://img.shields.io/badge/node-6.11.3-green.svg)
![VueJS 2](https://img.shields.io/badge/vuejs-2.5.2-green.svg)
![Webpack 4](https://img.shields.io/badge/webpack-4.25.1-green.svg)
[![codecov](https://codecov.io/gh/mistaguy/metvn/branch/master/graph/badge.svg)](https://codecov.io/gh/mistaguy/metvn)
[![Coverage Status](https://coveralls.io/repos/github/mistaguy/metvn/badge.svg?branch=master)](https://coveralls.io/github/mistaguy/metvn?branch=master)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](https://github.com/mistaguy/metvn/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![code style: Tslint Latest](https://img.shields.io/badge/tslint_rules-latest-ff69b4.svg?style=flat-square)](https://github.com/buzinas/tslint-eslint-rules)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmistaguy%2Fmetvn.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmistaguy%2Fmetvn?ref=badge_shield)
[![Apache License, Version 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://opensource.org/licenses/Apache-2.0)

# METVN
A boilerplate for MongoDB  ExpressJs Typscript Vue NodeJs App

<img src="https://vuejs.org/images/logo.png" height="50"> <img src="https://i.cloudup.com/zfY6lL7eFa-300x300.png" height="50"> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/45/MongoDB-Logo.svg/527px-MongoDB-Logo.svg.png" height="50"> <img src="https://worldvectorlogo.com/logos/nodejs-icon.svg" height="50"> <img src="https://camo.githubusercontent.com/66747a6e05a799aec9c6e04a3e721ca567748e8b/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313336353838312f313931383337332f32653035373166612d376462632d313165332d383436352d3839356632393164343366652e706e67" height="50">

## Issues, suggestions and feature requests
We are actively maintaining this widget, please report any issues or suggestion for improvement at https://github.com/mistaguy/metvn/issues

## Development and contribution
Prerequisite: Install git, node package manager, webpack CLI, grunt CLI, Vue CLI

To contribute, fork and clone.

    > git clone https://github.com/mistaguy/metvn.git

The code is in typescript. Use a typescript IDE of your choice, like Visual Studio Code or WebStorm.

To set up the development environment, run:

    > npm install

To automatically compile, bundle and push code changes to the running test project, run:

    > npm start

To run the project unit tests with code coverage, results can be found at `dist/testresults/coverage/index.html`, run:

    > npm run test:unit

Run the unit test continuously during development:

    > npm run test:dev

Run the end to end test during development:

    > npm run test:e2e:dev

## Scripts
While developing, you will probably rely mostly on `npm start`; however, there are additional scripts at your disposal:

|`npm run <script>`|Description|
|------------------|-----------|
|`start`|Build the project and monitor source and config for changes and rebuild.|
|`test`|Runs lint, build, unit tests with mocha and generates a coverage report, deploy and run e2e test|
|`test:dev`|Runs mocha and watches for changes to re-run tests; does not generate coverage reports.|
|`test:unit`|Runs unit tests with mocha and generates a coverage report.|
|`test:e2e`|Runs end to end tests with remote.|
|`test:e2e:dev`|Runs end to end tests with locally on localhost:8080|
|`build:prod`|Build app optimized for production|
|`build:dev`|Build app optimized for debugging.|
|`lint`|Lint all `.js` files.|
|`lint:fix`|Lint and fix all `.ts` files.|

