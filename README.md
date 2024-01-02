# Automation Engineer Roadmap
This roadmap is designed to guide Automation Engineers seeking to expand their skill set. No matter if you're already good in this subject or just starting out, this guide will give you the tools and knowledge you need to stay ahead.

### Prerequisite
Basic understanding of software testing.

<details>
<summary>Foundational Pillars - Beginner Level
</summary>
  
  #### Introduction to Problem Solving
    
  - Understanding Problem Specification.
  - Algorithmic Thinking.
  - Data organization.
  - Writing the first Pseudocode.
    
  #### Programming Basics:
  - Explore IDE features well.
  - Learn fundamental programming constructs like I/O, variables, data types, loops, conditionals and functions.
  - File handling.
  - Practise basic algorithms and data structures. 
  - Understand error handling and debugging techniques.
  - Get familiar with version control system.
    
  #### OOP Concepts:
  - Introduction to Packages, Classes and objects, Constructors and Access Modifiers.
  - Understand the principles of object-oriented programming (OOP) like encapsulation, inheritance, polymorphism, and abstraction.
  - Understand relationships between classes (association, aggregation, composition etc).
  - Apply good class design principles for maintainability.
  - Grasp object relationships and interactions (message passing, method calls).
  
  <details>
  <summary>Projects
  </summary>

   #### 1. Quiz Application:  
   
   #### Features:
   - Create a variety of question types (multiple choice, true/false, short answer).
   - Implement different difficulty levels.
   - Track user scores and progress.
   - Store and retrieve quiz data   
   
   #### Hint
   - Model questions, answers, and user scores using classes.
   - Use inheritance to create different question types.
   - Implement methods for handling user input, checking answers, and calculating scores.

   #### 2. Personal Finance Tracker:  
   #### Features:
   - Track income, expenses, and account balances.
   - Create budgets and categorize transactions.
   - Generate reports on spending habits and financial progress.
   
   #### Hint
   - Model accounts, transactions, and categories as classes.
   - Use methods for calculating balances, generating reports, and visualizing financial data.

   ### 3. Restaurant Menu Management System:  
   #### Features:
   - Add, edit, and delete menu items. 
   - Categorise dishes
   - Calculate bills
   - Print orders.

   #### Hint
   - Create a "MenuItem" class with constructors for different dish types (drinks, appetisers, main courses).
   - Use static methods for common tasks like printing the entire menu or calculating total bill.
   - Implement inner classes for order details and customer information.
   - Apply generics to handle different data types for menu items and order specifics.
   - Develop a console based user interface for managing the menu and handling orders.
   
   #### Aditonal project ideas
   - https://www.geeksforgeeks.org/java-projects/
   - https://www.geeksforgeeks.org/python-projects-beginner-to-advanced/
   - https://www.interviewbit.com/blog/c-sharp-projects/
   - https://www.freecodecamp.org/news/javascript-projects-for-beginners/

  </details>
</details>

<details>
<summary>Deep Dive into Advanced Programming - Intermediate to Advanced Level
</summary>

  #### Advanced Programming Concepts:
  - Explore advanced features of your chosen language (e.g., Java 8 streams, Python decorators etc).
  - Learn functional programming concepts.
  - Gain understanding of concurrency concepts and how to use those effectively.
  - Learn error handling. Example: Utilize custom exceptions for clear and specific error categorization.
  - Leverage exception chaining for propagating context and simplifying debugging.

<details>
<summary>Projects
</summary>
  
#### 1. Data Processing with Streams:
Implement a program that reads a text file, filters out words containing a specific letter, sorts them alphabetically, and counts the occurrences of each word.

Concepts:
- Stream API for functional-style operations on collections
- Lambda expressions and method references
- Intermediate operations (filter, map, sort) and terminal operations (count, collect)

#### 2. Functional Programming with Comparators:
Create a program that compares and sorts a list of Person objects based on different criteria (name, age, height) using custom comparators.

Concepts:
- Functional interfaces and lambda expressions
- Method references to existing methods
- Comparator chaining for combining multiple criteria

#### 3. Concurrent File Processing:
Develop a program that concurrently processes multiple files in a directory, performing tasks like counting lines, words, or characters.

Concepts:
- Use ExecutorService for managing threads
- Use Callable for tasks that return results
- Use Future for handling asynchronous results
- Use Synchronization mechanisms (locks, synchronized blocks) to ensure thread safety

#### 4. Custom Exception Handling:

Create a library management system that throws custom exceptions for invalid book IDs, missing books, or overdue returns.

Concepts:
- Extending Exception class to create custom exceptions
- Throwing and catching custom exceptions
- Exception chaining for preserving context information
    
</details>

#### Clean Code Practices:
- Readability: Write code that's easy to understand.
- Maintainability: Structure code for easy modification and bug fixing.
- Modularity: Break down code into well-defined, reusable components.
- Documentation: Provide clear explanations of code functionality and intent.
- Descriptive Naming: Use meaningful variable, function, and class names.
- Meaningful Comments: Explain complex logic or non-obvious code sections.
- Consistent Formatting: Adhere to a consistent code style guide for indentation, spacing, and newlines.
- Error Handling: Implement robust error checking and handling mechanisms.
- Refactoring: Regularly improve code structure without changing its external behavior.
- Code Reviews: Learn various effective ways for performing code reviews.

<details>
<summary>Project on Clean Code Practices
</summary>
  
  - Start with any open source sample code and try to apply the clean code concepts
  - Improve any of the above project already done using clean code practices now.
    
</details>

</details>

<details>
<summary>Unit testing - Intermediate Level
</summary>

### Unit Testing Concepts:
  - Understand the importance of unit testing and its role in automating test cases.
  - Introduction to Test Automation Pyramid
  - Start with any unit testing framework (Junit/TestNG/Pytest/NUnit etc)
  - Learn about test organization (hooks/fixtures)
  - Learn about test configurations
  - Learn about the  core compomnet of the unit test framework (Annotiations, Parameters, Dependencies, Factories, Listeners, Dependency injection etc as applicable.)
  - Understand about Assertions (AAA Pattern)
  - Creating Layered architecture (clear segrigation between business logic/application logic/data/utils).
  - Handling test data effectively.
  - Creating useful test reports.
  - Creating reusable utlilities.

### Test execution:
  - Run test on local machine
  - Deep dive into environment setup
  - Test Execution patterns (sequencial vs parallel)
  - Run test on docker container in local machine
  - Run test on CI (example: github action)
  - Run test on dedicated setup in cloud (example:EC2)
  - Run test using cloud services (example: browserstack)

<details>
<summary>Project - Test Data Management System
</summary>

  ### Features to be added
  #### Database Interactions:
  - Connect to your chosen database (MySQL, PostgreSQL, etc.).
  - Create classes to represent test data entities and map them to database tables.
  - Implement methods for CRUD (Create, Read, Update, Delete) operations on test data.
  #### Mock Data Generation:
  - Use supported libraries for random data generation.
  - Create custom logic for generating realistic data based on specific data types and formats.
  #### Data Anonymization:
  - Develop algorithms for masking or obfuscating sensitive information (e.g., names, addresses).
  - Consider using libraries like Apache OpenBLAS for more advanced anonymization techniques.
  #### Import/Export:
  - Use file I/O capabilities to read and write test data from/to files (CSV, JSON, XML).
  - Implement parsing and formatting logic for different data formats.
  #### User Interface:
  - Create a menu-driven console application for user input.
  - Display options for managing test data, generating data, searching, importing/exporting, etc.
  #### Test Framework Integration:
  - Write unit tests to ensure the TDMP's functionalities work as expected.
  - Create test cases for database interactions, data generation, anonymization, and other features.
</details>

</details>

<details>
<summary> Common Automation tools & libraries - Intermediate Level
</summary>

  #### Web app Automation
  - Understand common web application architectures (e.g., client-server, single-page applications).
  - Recognize elements of website design and layout (headers, footers, navigations, forms).
  - Practice manipulating DOM elements from browser console (adding/removing nodes, modifying attributes).
  - Understand basic event handling and user interaction patterns on web pages.
  - Explore different web automation frameworks (Example: Selenium, Cypress, Playwright) features
  - Start with any one web automation library and learn it well.
  - Learn common strategies for handling dynamic elements and page transitions.
  - Understand debugging techniques for identifying and resolving web automation issues.

  ### Mobile app Automation
  - Understand how mobile apps interact with the device (operating system, sensors, hardware).
  - Differentiate between native, hybrid, and web mobile app architectures.
  - Grasp the concept of app packages, activities, and intents.
  - Understand the need for emulators, simulators, and real devices for automation testing.
  - Familiarize yourself with mobile device configuration and management tools.
  - Compare and contrast popular mobile automation frameworks (Appium, Espresso etc).
  - Choose a stable tool based on your app type, language preference, and project requirements.
  - Deep dive into concepts like object locators, desired capabilities, driver configurations etc.
  - Start with mobile web browser automation (e.g., Chrome on Android) for fundamental understanding.
  - Progress to native app automation 
  - Finally, explore hybrid app automation, understanding the interplay between native and web components.
    
  ### API Automation
  - Understanding API basics: Grasp the fundamental concepts of APIs, including RESTful architecture, request-response patterns, HTTP methods (GET, POST, PUT, DELETE), status codes, authentication methods (basic, OAuth, tokens).
  - Explore various Backend technologies used for API development, such as Node.js, Flask (Python), Spring Boot (Java)
  - Choose appropriate API testing tools/libraries (Postman, RestAssured, Karate DSL or others based on your language and project needs.
  - Configure necessary environments for testing, including test servers, API endpoints, mocking tools, and data setup.
  - Learn how to construct and execute API requests using the chosen tool, handling different HTTP methods, headers, parameters, and body data.
  - Understand the concept of serialization and deserialization for request body.
  - Validate API responses for expected structure, data, status codes, and error messages.
  - Learn how to use API chains for validating business scenarios using APIs.
  - Manage test data effectively for different test cases, using techniques like parameterization and data-driven testing. 

</details>

<details>
<summary> Design Patterns for Solving Testing Problems - Advanced level
</summary>
  
  - Understand importantance of using design patterns in test code.
  - Design pattern classifications
  - Page Object for managing application side code in a web automation framework
  - Factory method design pattern for enabling flexibility in test setup and teardown.
  - Fluent Interface for enhancing test readability and maintainability by enabling method chaining.
  - Decorator pattern for dynamically adding or modifying behavior of test objects without affecting their core functionality.
  - Singleton pattern for managing shared resources or test configurations.
  - Adapter pattern for facilitate testing with external systems or legacy code by adapting incompatible interfaces.
  - Observer pattern can be used for implementing notification mechanisms or test reporting.
  - Builder patterns for creating pojo classes in api framework.

  <details>
  <summary> Project
  </summary>
  
  #### Web/mobile automation Framework 
  - Create an automation framework using Page object and singleton design patterns supporting desktop and mobile chrome browser.
  - Execute the tests using cloud based service (example: Lambdatest)

  ### Web/API automation framework
  - Combine web UI interaction capabilities with API testing functionalities within a single framework.

  ### Rest API automation framework with complete test pyramid coverage.
  - Start with any existing API backend code from github.
  - Create a API automation framework adding tests in unit/integration/contract and end2end layers.

  </details>

</details>

<details>
<summary>Additional Automation Techniques & Tools - Intermediate Level
</summary>

- Static analysis/Style guides: Enforce code quality and consistency before execution (e.g., SonarQube, ESLint).
- Contract testing: Ensure independent systems communicate as expected (e.g., Pact, Spring Cloud Contract).
- Model Based Testing: Derive test cases from system model behavior (e.g., Conformiq Qtronic, GraphWalker).
- Visual Validation:Verify UI appearance and layouts automatically (e.g., Applitools Eyes, Percy).
- Test containers: Provide lightweight, isolated environments for tests (e.g., Testcontainers, Docker Compose).
- Property based Testing: Generate varied inputs to uncover edge cases (e.g., Hypothesis, QuickCheck).
- Mutation testing: Measure test effectiveness by intentionally introducing errors (e.g., Pitest, Stryker).
- API Mocking: Simulate external services for testing in isolation (e.g., WireMock, MockServer).
- Monitoring tools: Track application performance and health (e.g., Splunk, Datadog).
- Performance testing tools: Measure application performance under load (e.g., JMeter, Gatling, K6, LightHouse).
- Static Application Security Testing (SAST) Tools: Analyse source code for security vulnerabilities without needing to run the application. (e.g., SonarQube, Fortify)
- Dynamic Application Security Testing (DAST) Tools: Scan running applications for vulnerabilities (e.g., Veracode, Qualys)
- Secret scaners : Scan code for leaked secrets (e.g., Talisman,TruffleHog ) 

</details>

<details>
<summary>Low-code/No-code Automation - Intermediate Level
</summary>

- Explore the world of low-code/no-code automation tools. 
- Pick up any one low-code automation tool and understand the key features and limitations

#### Project
Create a keyword-driven automation frameworks similar to the low code tool you had explored.

</details>

<details>
<summary>Cloud Based Test Infra Setup - Intermediate Level
</summary>

- Explore key offerings from various cloud providers like AWS CodeBuild, Google Cloud Build, Azure DevOps Pipelines, etc.
- Setting up and configuring cloud-based automation pipelines for specific testing scenarios (e.g., web UI automation, API testing).
- How to integrate Cloud-based automation environment with CI/CD pipelines for continuous testing and delivery.
- Explore and understand essential security practices for cloud-based automation, like access control, secrets management, and vulnerability scanning.

</details>

<details>
<summary>AI assistance in Automation
</summary>
  
  - Code Generation and Completion 
  - Template generation tools for generate boilerplate code, configuration files, and API client libraries automatically, saving you time and effort.
  - Generate test scripts
  - Generate test data
  - Analyse test results for RCA
    
</details>

<details>
<summary>Additional Resources
</summary>

  ### Youtube Videos:
  - [freeCodeCamp.org](https://www.youtube.com/playlist?list=PLWKjhJtqVAbnRT_hue-3zyiuIYj0OlpyG)
  - [Coding With John](https://www.youtube.com/playlist?list=PLkeaG1zpPTHiMjczpmZ6ALd46VjjiQJ_8)
  - [In28mins](https://www.youtube.com/playlist?list=PL91AF2D4024AA59AF)
  - [Programming with Mosh](https://www.youtube.com/@programmingwithmosh)

  ### Blogs/Links
  - https://jenkov.com/tutorials/java/index.html
  - https://github.com/onlyfullstack/java-8-features
  - https://github.com/PacktPublishing/Java-Coding-Problems
  - https://www.baeldung.com/
  - https://www.javacodegeeks.com/
  - https://www.baeldung.com/java-jqwik-property-based-testing
  - https://graphwalker.github.io/
  - https://www.baeldung.com/java-mutation-testing-with-pitest
  - https://martinfowler.com/articles/practical-test-pyramid.html

</details>

<details>
<summary>How To Follow this Roadmap
</summary>
  
  - Dedicate at least 1 hour daily to practising and learning new skills. Consistency is key to progress.
  - Use a github repostory to push code and share with others.
  - Create a 3-month plan with specific goals and review it monthly to adapt and adjust your roadmap as needed.
  - The field of test automation is constantly evolving. Stay updated with the latest trends and technologies through blogs, conferences, and online communities.
  - Connect with other automation engineers, participate in online forums and discussions, and learn from each other's experiences.
</details>
