# webdriverio_ui_test

#Retiremnent Calculator

##Packages used
1. webdriverio - Next-gen browser and mobile automation test framework for Node.js
2. Cucumber - JavaScript test framework for Node.js
3. Chai - Assertion library
4. Nodejs - JavaScript runtime environment
5. Allure - HTML reporter

###Framework setup
1. Clone the repository from GitHub
2. Unzip the executableFiles.zip file and open the project in IDE
3. In the terminal (from the root folder of the project) call `npm install` to install the node_modules
4. To access the test script, navigate and open - test > features > RetirementCalculator > RetirementCalculator.feature

###Test Execution
- Ensure that latest stable version of NodeJS is installed on the machine.
- Use the following command to run the automated UI tests
  `npm run wdio`
- To generate the html report, run the command
  `allure generate allure-results --clean`
- To view the HTML report, run the command
  `allure open allure-report`
- To view the test logs, navigate and open logs > testExecution.log