## General Code Review Guideline

1. Code Style and Formatting

Does the code adhere to the team's coding style and formatting guidelines, including design pattern conventions?
Are naming conventions consistent and meaningful, reflecting design patterns where applicable?

2. Comments and Documentation

Are comments used effectively to explain the rationale behind design decisions, especially when employing design patterns?
Is there clear documentation for design patterns used in the code?

3. Code Organization

Does the code follow a modular structure that aligns with design patterns?
Are design patterns applied consistently and appropriately across the codebase?

## Functionality

1. Correctness: Does the code correctly implement the chosen design patterns to meet the requirements?
Are there any design pattern-related errors or misuse?

2. Design Patterns: Are design patterns used where appropriate to solve recurring design problems effectively?
Are anti-patterns, such as excessive inheritance or overuse of singletons, avoided?

4. Security: Is the code protected against common security issues, and are design patterns used to enhance security where applicable?
Are potential security vulnerabilities identified and addressed?

5. Memory Safety: Does the code exhibit memory safety through the use of modern C++ features like smart pointers and RAII?
Are manual memory management and raw pointers avoided where possible?

6. Code Quality and Code Duplication: 
Is code duplication minimized through the use of design patterns like the Factory Method or Singleton?
Are common design patterns and idioms employed to improve code quality?

7. Variable Usage: Are variables and objects managed safely, and are design patterns like the Observer pattern used for appropriate event handling?
Are resource management design patterns (e.g., Resource Acquisition Is Initialization) applied where necessary?

9. Memory Management: Is memory management handled correctly and safely, especially when implementing custom design patterns?
Are memory leaks and resource leaks prevented?

10. Testing
Do unit tests cover the functionality of code sections implementing design patterns?
Are design patterns thoroughly tested to ensure they work as intended?

## Readability and Maintainability

Modularity: Is the code structured to promote modularity and the use of design patterns?
Can someone unfamiliar with the codebase understand the design choices made?
Code Complexity

Are design patterns applied judiciously to manage code complexity?
Is the code as simple as possible while still using appropriate design patterns?

## Performance
Resource Usage: Is the code optimized for performance, considering design patterns like the Flyweight pattern for resource-efficient objects?
Are there potential performance bottlenecks related to design pattern usage?

Concurrency and Thread Safety: Are design patterns applied to ensure thread safety where required?
Is the code designed to handle concurrency gracefully?

## Dependencies
Are external libraries and dependencies used securely, and do they adhere to modern C++ practices?
Are potential security vulnerabilities in dependencies considered?

## Error Handling
Does the code implement error handling mechanisms following modern C++ practices?
Are design patterns like the Null Object pattern used for graceful error handling?

## Security
Security Best Practices: Are design patterns used to enforce security best practices, such as the Proxy pattern for access control?
Are potential security risks associated with design patterns mitigated?

## Documentation
User Documentation: Is there user documentation or README files explaining how to use the code, including any design patterns employed?

API Documentation: Is there clear documentation for the public API, including how design patterns are utilized?
Remember that while design patterns can greatly enhance code structure and maintainability, they should be applied judiciously. 
Overuse or misuse of design patterns can lead to code complexity and decreased maintainability. Additionally, staying updated with modern C++ practices, such as those introduced in C++11 and later versions, 
is crucial for writing robust and secure code.

## Reference

https://www.incredibuild.com/blog/the-ultimate-guide-to-cpp-code-review-part-1

https://www.incredibuild.com/blog/the-ultimate-guide-to-cpp-code-review-part-2

https://learn.microsoft.com/en-us/cpp/code-quality/using-the-cpp-core-guidelines-checkers?view=msvc-170
