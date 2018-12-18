# **Cooper Test client**
-------
This is a mobile app for a Cooper Test, the user-facing client (i.e. not including back-end). It allows users to measure their endurance. 

To get the back-end: https://github.com/CamronLDNF/cooper_test_api

## Tech stack
-------
Building the app:
* Ionic

Testing the app:
* Karma & Jasmine for unit testing
* Protractor for e2e acceptance testing

## How to install
-------
1. Download the app folder
2. Open the app folder in your CLI
3. Run `'npm' install` to install all packages
4. Run `ionic serve --lab` to launch the app in your browser

## How to run the test suite
-------
1. First run `ionic serve --lab` to launch the app
2. Then run `npm run test-coverage` to run the unit test
3. Run `open coverage/index.html` to open the unit test coverage report 
3. Run `npm run e2e` to run the e2e acceptance test
