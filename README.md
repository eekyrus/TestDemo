**RUNNING TESTS**

Prerequisites: 
- JDK 1.8 or later installed
- Chrome v98 (probably works with other versions as well)

Clone this repository using git or manually download zipped contents and extract them.
Open terminal in project's directory and run 'gradlew test' command. ..or you can use your preferred IDE to edit and run tests.
There are 4 empty test methods in the project so terminal should print that all 4 tests have successfully passed.

**TASKS**

There is a demo website for test automation excercises: https://automationexercise.com/.

Using Selenium's Page Object pattern:
- implement a smoke test that would check if the website https://automationexercise.com/ is operational. Operational could mean that a correct title is displayed in the browser's tab for example;

- implement a test that checks if user registration is performed successfully when correct email is provided by the user

- implement a test that checks if user login is successful when correct credentials are provided. 

- implement a test that checks if user login fails if incorrect credentials are provided.

- Smoke test should be ran first and if it fails, the remaining tests should be skipped.


The tests should preferably be runnable using 'gradlew test' command to execute gradle's test task but can also be ran using java command.

Either create a pull request of the test implementations to this repository or your zipped source code to recruitment contact via email.
