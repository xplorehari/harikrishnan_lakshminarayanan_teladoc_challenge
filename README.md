AutomateAngularProtractorWebtable
This project's main purpose is to automate the user interactions on Angularprotractorwebtable and successfully finish the scenarios:Add user and validate,Delete user Novak and validate  using BDD
The project is implemented with Cypress  and Gherkin Language.
##Setup and Execution instructions.
1.	Cypress version used: Cypress 10.9.0
Operation system : Windows 10 Install Git if you dont have in your system.
https://git-scm.com/download/win
2.	Open Git Bash and clone this repository in a directory.
$ git clone :https://github.com/xplorehari/Automation
3.	Open the cloned project in a code editor.
4.	In the Terminal window of the Code editor use NPM commands for installing cypress(Javascript) using following commands
a.	Download and setup Node.JS from the link below based on the system requirments
https://nodejs.org/en/download/
open Command Prompt or Terminal window and run the following NPM commands
b.	Npm init
(enter for all the default options)
c.	Npm install Cypress
(if you are getting SSL certificate error or any other error you can download the binary from https://www.cypress.io/. And follow the instructions on the page for the direct download: https://docs.cypress.io/guides/getting-started/installing-cypress#Direct-download)
d.	 npm install @badeball/cypress-cucumber-preprocessor
(installing the Cucumber preprocessor dependencies and configuring the same is          mandatory for running this project.Copy the package.Json file and cypress.config.js file from the repository and update your local copy for these files.For more instructions please refer to the github page:https://github.com/badeball/cypress-cucumber-preprocessor
e.	Npx cypress open
(When we open the first time cypress asks for the default setup of e2e spec file and other support file configuration click continue to proceed. Now click on E2E testing and select the browser:chrome and it asks for default scaffold set of spec files or create new spec file directly. Select the second option)

5.	Now copy the spec files from the github repository under cypress\e2e\AutomateAngularProtractorwebtable.feature and cypress\e2e\AutomateAngularProtractorwebtable.js

(For the feature file to highlight in blue cucumber/full gherkin extension may be required to install depending on the editor from the extension/plugin section)

6.	Cypress Testrunner will open in a new chrome window and show the updated AutomateAngularProtractorwebtable.feature as hyperlink click on that and the execution will start on the cypress Test runner for both Add and the Delete scenarios

7.	The script runs and completes the execution of both the scenarios and the test report shows both the assertions used as well as the screenshots of the applications (before/after state when we hover)