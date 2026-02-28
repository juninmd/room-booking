```markdown
# AGENTS.md - Coding Guidelines

These guidelines are designed to ensure high-quality, maintainable, and effective code for our AI agents. Adherence to these principles is critical for the long-term health and success of the project.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined purpose.  Avoid creating overly complex modules with multiple responsibilities.
*   **Component Reusability:** Design components with potential for reuse across multiple agents.  Consider creating reusable data structures, algorithms, or helper functions.
*   **Code Patterns:** Favor established code patterns (e.g., dependency injection, state management) to reduce boilerplate and improve consistency.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:**  Strive for the shortest possible code that achieves the desired functionality.  Avoid unnecessary complexity.
*   **Readability:**  Use clear and descriptive variable and function names.  Employ consistent naming conventions.
*   **Comments:**  Provide concise and helpful comments only where necessary to explain complex logic or design choices.  Avoid overly verbose comments.

## 3. SOLID Principles

*   **Single Responsibility:**  All agents should have a single, focused responsibility.
*   **Open/Closed Principle:**  The agent's design should allow for extensions without modifying existing code.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace their base class without affecting the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Features:**  Don't add functionality that is not currently required.  Refactor existing code to remove unused features.
*   **Progress Over Perfection:**  Focus on delivering working code rather than premature optimization.

## 5. Development Practices

*   **Code Reviews:**  All code must undergo thorough code reviews.
*   **Static Analysis:** Utilize static analysis tools (e.g., pylint, eslint) to automatically identify potential issues and enforce coding standards.
*   **Unit Testing:** All agents should have comprehensive unit tests covering core functionality.
*   **Integration Testing:**  Focus on integration testing to ensure agents work correctly together.
*   **Documentation:**  Provide clear documentation for agents, including API documentation and usage examples.
*   **Version Control:**  Use Git for version control and adhere to Git best practices.
*   **Error Handling:** Implement robust error handling and logging.

## 6. Code Structure & Length

*   **Maximum Line Count:** Each file must have a maximum of 180 lines of code.
*   **Modularization:**  Break down complex agent functionalities into smaller, modular units.
*   **Data Structures:** Utilize appropriate data structures for efficient data management.

## 7. Test Coverage

*   **Minimum Coverage:**  Aim for at least 80% test coverage. This is a baseline target.
*   **Test Case Design:**  Create test cases that cover all critical scenarios and edge cases.
*   **Automated Testing:**  Employ automated testing frameworks (e.g., pytest, unittest) for comprehensive testing.

## 8.  File Structure & Organization

*   **Root Directory:**  The primary `AGENTS.md` file should be at the root of the repository.
*   **Agent Modules:** Organize code into logical agent modules (e.g., `agent_a`, `agent_b`).
*   **Component-Based Architecture:**  Encourage the use of component-based design for increased reusability.

## 9.  Coding Style & Conventions

*   **Consistent Formatting:**  Use consistent indentation and line spacing.
*   **Naming Conventions:**  Follow established naming conventions (e.g., snake_case).
*   **Code Formatting:** Utilize a code formatter (e.g., black) for automated code formatting.

## 10.  Future Considerations (Not Mandatory)**

*   **Logging:** Implement comprehensive logging for debugging and monitoring.
*   **Configuration:**  Allow for configuration of agent behavior through configuration files or environment variables.
*   **API Documentation:** Create clear and concise API documentation.

These guidelines will guide the development of high-quality and maintainable AI agents within the AGENTS.md repository.
```