# 🛠️ Daily Tasks – Aiken Project

[![Project Status](https://img.shields.io/badge/Status-Complete-brightgreen)](README.md)

## Project Overview

This project demonstrates my understanding of the **Aiken development environment** and **Cardano fundamentals** through a simple Daily Tasks validator. The project includes multiple validator files with tests covering boolean logic, integers, strings, mathematical operations, and trace messages for debugging.

---

## 🚀 Quick Start

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    ```

2.  **Navigate to the project folder:**
    ```bash
    cd my-project
    ```

3.  **Run all tests:**
    ```bash
    aiken check
    ```
    All tests should pass, and trace messages will be displayed for tests that include the `trace` function.

---

## ✅ Exercises Completed

### Exercise 1: Environment Verification
* Verified installation of Aiken, Node.js, npm, and the VS Code Aiken extension.
* Ensured correct versions and successful setup.

### Exercise 2: Create First Project
* Created a new Aiken project (`workshop-m000`).
* Explored project structure, including `validators/` and `lib/` folders.
* Verified tests ran successfully.

### Exercise 3: Experiment with Tests
* Added tests using different data types: booleans, integers, and strings.
* Experimented with intentionally failing tests to understand test feedback.

### Exercise 4: Working with Trace Messages
* Added trace messages to tests for debugging and monitoring execution.
* Observed output of trace messages when running tests.
* Created additional tests to experiment with trace placement.

### Exercise 5: Project Organization
* Created multiple validator files for better organization.
* Separated tests for tasks, trace experiments, and mathematical operations.
* Ran all tests and verified proper functionality.

---

## 🛑 Challenges and Solutions

| Challenge | Solution |
| :--- | :--- |
| **Missing `aiken` keyword** at the top of test files. | **Added `aiken`** at the top of each `.ak` file, which allowed `aiken check` to detect the tests. |
| **Installing Aiken** (Latest version gave a “GitHub not found” error). | **Manually downloaded** the executable from GitHub and added it to my system's `PATH`. |
| **Trace messages not appearing** in test output. | Learned that `trace` only works inside test functions with **boolean expressions**. Updated tests accordingly. |

---

## 🧠 Lessons Learned

* **Proper project structure** and naming conventions are crucial for Aiken to detect tests.
* The `trace` messages are a powerful and essential tool for **debugging** Plutus/Aiken code execution.
* Understanding basic **Cardano concepts** (like validators) helps significantly in building functional smart contract logic.

---

## 📝 Additional Notes / Questions

* I would appreciate feedback on whether my **test organization** and **trace usage** are optimal.
* Are there better ways to **structure validator files** for readability and scalability in a larger project?
