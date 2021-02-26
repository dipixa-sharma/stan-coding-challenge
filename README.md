# Test Automation Challenge 🔄
 
## Description
 
You will be writing end to end and UI tests for the play.stan website.
 
The purpose of this challenge is to assess your skills and approach to creating test cases in a javascript testing framework that validate and check on page assets.
 
This challenge is expected to take around 2-3 hours.
 
## Details
 
### 👣 Steps
 
- Install a javascript test framework of your choice into the directory follow the specific framework README.md file to correctly install, here are some examples below. 
 
    - [Cypress](https://www.cypress.io/)
    - [Playwright](https://playwright.dev/)
 
- Create a folder and file structure to run your tests
 
- Add a script in your package.json file for kicking off your tests on the URLS specified.
 
- Create 3-5 tests for https://play.stan.com.au/ 
- Create 3-5 tests for https://www.stan.com.au/watch/
- Create 1-2 tests for https://www.stan.com.au/ 
 
- Also, add the following info to your README:
 
 How did you decide on the structure and framework of your solution?
 Are there any improvements you could make to your submission?
 What would you do differently if you were allocated more time?
 
### 🏗 Structure
 
Create a file to hold your reusable selectors, simple example below: 
 
```javascript
const SELECTORS = {
 LOGIN_EMAIL_INPUT: '[name="email"]',
 LOGIN_PASSWORD_INPUT: '[name="password"]',
};
```
 
Create a file to store your functions
 
```javascript
const checkLoginPage = () => {
 cy.get(selectors.LOGIN_EMAIL_INPUT);
 cy.get(selectors.LOGIN_PASSWORD_INPUT);
};
```

Comment your code! When writing a test cases please add comments to your code and why you would assert on specific areas of its deemed important.

Upload your code to a public github repo to be assesed. 
 
### 🏆 Additional Challenges
 
- Adding additional browser support
- Typescript configuration
- Mock data
- API tests
- Reporting
 
### ❓ FAQ
 
If you don't have a stan login you can signup for a free trial here > https://www.stan.com.au/
 
If you are stuck or request a code review before submitting contact cheryl.fowlie@stan.com.au
