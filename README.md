[![Board Status](https://dev.azure.com/bennystreettough/152d3214-0c82-4a84-8b56-56957d57eed9/36f59638-e22e-430f-8524-4c791a8c49ee/_apis/work/boardbadge/79908849-2eca-4f1e-baee-85c7cb015775)](https://dev.azure.com/bennystreettough/152d3214-0c82-4a84-8b56-56957d57eed9/_boards/board/t/36f59638-e22e-430f-8524-4c791a8c49ee/Microsoft.RequirementCategory)
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

