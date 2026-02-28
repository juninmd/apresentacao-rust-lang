```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the creation and maintenance of high-quality, maintainable, and robust AI coding agents. Compliance with these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic and data structures must be encapsulated in reusable components.
*   Avoid duplication of code across multiple files or modules.
*   Utilize functions, classes, and modules to break down complex tasks.
*   Refactor existing code to eliminate redundancy.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for concise and easily understandable code.
*   Prioritize clarity and readability over unnecessary complexity.
*   Minimize the number of lines of code while maintaining functionality.
*   Avoid over-engineering solutions.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be extensible without modification.  New functionality should be added through interfaces or abstraction.
*   **Liskov Substitution Principle:** Subclasses must be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on methods it does not use.
*   **Dependency Inversion Principle:** Higher-level modules should not depend on implementation details.  Instead, they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are absolutely necessary at the current point in time.
*   Avoid adding functionality that is likely to be obsolete or superseded.
*   Refactor code to remove unused or unnecessary components.

## 5. Code Quality & Structure

*   **File Size:** Each file must be no more than 180 lines of code.
*   **Comments:** Provide concise and informative comments where necessary, explaining complex logic or design decisions.  Avoid redundant commenting.
*   **Naming Conventions:**  Follow consistent naming conventions (e.g., camelCase, snake_case) throughout the codebase.
*   **Error Handling:** Implement robust error handling and logging to facilitate debugging and monitoring.
*   **Data Structures:** Employ appropriate data structures to optimize performance and readability.
*   **Code Style:** Adhere to a consistent code style guide (e.g., Google Style).

## 6. Testing & Verification

*   **Unit Tests:** All code must be thoroughly unit tested with comprehensive tests.  Test coverage should be at least 80%.
*   **Integration Tests:** Integrate the AI agent components with the testing framework.
*   **Edge Case Testing:**  Specifically test boundary conditions and unusual scenarios.
*   **Negative Testing:**  Include tests that intentionally trigger errors or unexpected behavior.
*   **Mocking (Only for Tests):** Use mocks and stubs exclusively for testing. Do NOT use actual data sources or service calls within the core logic.

## 7.  AI Agent Specific Considerations

*   **State Management:** Employ a clear and consistent state management strategy.
*   **Agent Logic:** Document complex agent logic clearly using comments and structured data.
*   **Parameter Handling:**  Properly handle parameter inputs and return values.
*   **Logging:** Implement structured logging to aid in debugging and monitoring.
*   **Error Reporting:** Define standardized error reporting mechanisms.

## 8.  Version Control

*   All code must be committed to the version control system (e.g., Git).
*   Use meaningful commit messages.
*   Follow a consistent branching strategy.

## 9.  Documentation

*   Provide clear documentation for all modules, functions, and classes.
*   Explain the purpose, input, and output of each component.

## 10.  Maintainability

*   The codebase should be easily understandable and adaptable to future changes.
*   Design for extensibility.

These guidelines are intended to be a living document and will be reviewed and updated periodically.  Any deviation from these principles will be subject to review by the AI Development Team.
```