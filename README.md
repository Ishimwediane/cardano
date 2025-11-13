Daily Tasks – Aiken Project
Project Overview

This project demonstrates my understanding of the Aiken development environment and Cardano fundamentals through a simple Daily Tasks validator. The project includes multiple validator files with tests covering boolean logic, integers, strings, mathematical operations, and trace messages for debugging.

Quick Start

Clone the repository:

git clone <your-repo-url>


Navigate to the project folder:

cd my-project


Run all tests:

aiken check


All tests should pass and trace messages will be displayed for tests that include trace.

Folder Structure
my-project/
├── validators/      # Contains all test files for the project
├── lib/             # Library code (if needed)
├── build/           # Auto-generated build files
└── aiken.toml       # Project manifest


validators/ – Contains test files for daily tasks, traces, and mathematical operations

lib/ – Reserved for reusable code

build/ – Auto-generated build files

Exercises Completed
Exercise 1: Environment Verification

Verified installation of Aiken, Node.js, npm, and the VS Code Aiken extension

Ensured correct versions and successful setup

Exercise 2: Create First Project

Created a new Aiken project (workshop-m000)

Explored project structure, including validators/ and lib/ folders

Verified tests ran successfully

Exercise 3: Experiment with Tests

Added tests using different data types: booleans, integers, and strings

Experimented with intentionally failing tests to understand test feedback

Exercise 4: Working with Trace Messages

Added trace messages to tests for debugging and monitoring execution

Observed output of trace messages when running tests

Exercise 5: Project Organization

Created multiple validator files for better organization

Separated tests for tasks, trace experiments, and mathematical operations

Ran all tests and verified proper functionality

Challenges and Solutions

Missing aiken keyword at the top of test files

Initially caused aiken check to detect 0 tests with no errors

Solution: Added aiken at the top of each .ak file, which resolved the issue

Installing Aiken

Latest version gave a “GitHub not found” error

Solution: Manually downloaded executable from GitHub and added it to PATH

Trace messages not appearing

Learned that trace only works inside test functions with boolean expressions

Updated tests to include trace messages properly

Lessons Learned

Proper project structure and naming conventions are crucial for Aiken to detect tests

Trace messages are a powerful tool for debugging

Understanding basic Cardano concepts helps in building validator logic

Additional Notes / Questions

I would like feedback on whether my test organization and trace usage are optimal

Are there better ways to structure validator files for readability and scalability?
