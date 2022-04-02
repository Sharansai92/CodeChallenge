# CodeChallenge

##Test-Automation-Challenge-1

This practical challenge is to build browser based tests

This test contains 7 acceptance criterias

**URL** :https://start.duckduckgo.com/ and s https://start.duckduckgo.com/traffic 
 

**IDE**: Microsoft visual studio code

**Prerequisites**: Node.js and npm installed

**Plugins** : TestCafe Test Runner for Visual Studio Code,Code snippets for TestCafe

**Browser** : Chrome

**Installation** :You can install TestCafe from npm globally or locally in your project.
**Global Installation** : npm install -g testcafe

**Command to run test from terminal** : testcafe browsername projectname/filename.js

**eg**:testcafe chrome CodeChallenge/AC4.js

**Installation guide** : https://testcafe.io/documentation/402635/getting-started

**Test Results** :

AC1 - PASS

AC2 - FAIL (Only 8 results show up, acceptance criteria is wrong)

AC3 - FAIL ( First result is differenet to acceptance criteria)

AC4 - PASS

AC5 - I couldn't figure out how to assert the colour has changed. Would have talked to developer in real world.

AC6 - Should have used scenario outline but not sure how to do in test cafe. Didn't have time to investigate having a release this weekend.

AC7 - Have an issue through after clicking the 2018 traffic section, get this error.

:**A JavaScript error occurred on "https://start.duckduckgo.com/traffic".
      Repeat test actions in the browser and check the console for errors.
      To ignore client-side JavaScript errors, enable the "--skip-js-errors" CLI option, or set the "skipJsErrors"
      configuration file property to "true".
      If the website only throws this error when you test it with TestCafe, please create a new issue at:
      "https://github.com/DevExpress/testcafe/issues/new?template=bug-report.md".

      JavaScript error details:
      TypeError: Cannot read properties of undefined (reading 'SearchExperimentsData')
          at https://start.duckduckgo.com/util/u623.js:2:63**
