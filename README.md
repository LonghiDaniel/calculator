[![Build Status](https://dev.azure.com/keyworksti/Project%20Integration%20Github/_apis/build/status/LonghiDaniel.calculator?branchName=master)](https://dev.azure.com/keyworksti/Project%20Integration%20Github/_build/latest?definitionId=43&branchName=master)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

