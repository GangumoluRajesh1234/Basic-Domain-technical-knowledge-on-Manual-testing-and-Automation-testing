# Basic-Domain-technical-knowledge-on-Manual-testing-and-Automation-testing
Manual testing is the process of manually executing test cases without using any automation tools. Testers play the role of end-users and use most application features to ensure correct behavior.
Key Concepts

    Test Plan: A document describing the scope, approach, resources, and schedule of intended test activities. It identifies test items, features to be tested, testing tasks, who will do each task, and any risks requiring contingency planning.

    Test Case: A set of conditions or variables under which a tester will determine if a system under test satisfies requirements or works correctly.

    Test Scenario: A high-level documentation of a use case or test idea. It helps in covering the end-to-end functionality of an application.

    Defect/Bug Reporting: Identifying, logging, and tracking bugs in the software application. Includes the bug's severity and priority.

    Exploratory Testing: Simultaneous learning, test design, and test execution. Testers explore the application without pre-defined test cases.

    Ad-hoc Testing: Unstructured testing where testers aim to find defects through an informal process, without specific test cases.

Advantages

    Detects user interface issues.
    Cost-effective for small projects.
    Flexibility to accommodate changes.

Disadvantages

    Time-consuming and less efficient for large-scale testing.
    Prone to human error.
    Not reusable; tests have to be repeated manually.

Automation Testing
Definition

Automation testing uses specialized tools to execute pre-scripted tests on a software application before it is released into production. These tools run tests, report outcomes, and compare results with previous test runs.
Key Concepts

    Test Automation Framework: A set of guidelines, coding standards, concepts, and tools that enable the automation of testing processes. Types include:
        Data-Driven Testing
        Keyword-Driven Testing
        Hybrid Testing
        Behavior-Driven Development (BDD)

    Automation Tools: Software applications used to automate the execution of tests. Examples include:
        Selenium
        QTP/UFT (Unified Functional Testing)
        JUnit, TestNG
        Appium (for mobile applications)

    Scripts: Written in programming languages such as Java, Python, or C#, these are sequences of instructions that automate test cases.

    Continuous Integration (CI): A practice in DevOps where code changes are automatically tested and merged into the main branch. Tools like Jenkins, Bamboo, and GitLab CI/CD facilitate CI.

    Test Suites: Collections of test cases or test scripts intended to test a software program to show that it has some specified set of behaviors.

Advantages

    Faster execution of tests, especially for repetitive tasks.
    More reliable and less prone to human error.
    Reusable test scripts.
    Increased test coverage and efficiency.
    Facilitates continuous testing and integration.

Disadvantages

    Initial investment in tools and training.
    High maintenance of test scripts.
    Not suitable for testing user interfaces and exploratory testing.
    Requires programming knowledge.

Comparison
Aspect	Manual Testing	Automation Testing
Execution Speed	Slower, manual execution	Faster, automated execution
Accuracy	Prone to human error	More accurate and consistent
Initial Cost	Lower, but higher over time with larger tests	Higher upfront, lower over time with scalability
Test Coverage	Limited by human resources	Wider, can cover more test cases
Flexibility	High, easy to adapt to changes	Lower, scripts need updating for changes
Best For	Exploratory, ad-hoc, and UI testing	Regression, load, performance testing
Best Practices

    For Manual Testing:
        Develop comprehensive and clear test cases.
        Prioritize test cases based on critical functionality.
        Perform thorough exploratory testing to find hidden issues.
        Regularly update test cases based on new features and bug fixes.

    For Automation Testing:
        Choose the right automation tool based on the project requirements.
        Build robust and maintainable test scripts.
        Regularly review and update automation scripts to handle changes.
        Integrate automated tests into the CI/CD pipeline to ensure continuous testing.

Both manual and automation testing have their place in the software development lifecycle, and a balanced approach often yields the best results.
