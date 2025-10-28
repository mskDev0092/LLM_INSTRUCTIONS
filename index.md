# Copilot Development Instructions

## General Guidelines

- Follow SOLID principles for object-oriented design
- Apply KISS principle - Keep It Simple, Stupid
- Follow DRY - Don't Repeat Yourself
- Use meaningful names for variables, functions, and classes
- Write modular code with single responsibility functions
- Include proper error handling for all potential failure points
- Add comprehensive documentation for all public APIs
- Follow consistent formatting and style guides
- Implement proper logging throughout the application
- Write unit tests for all critical functionality

## Coding Standards

- Use consistent indentation (e.g., 2-4 spaces or tabs)
- Use consistent naming conventions (e.g., camelCase or snake_case)
- Prefer immutable variables where possible
- Use modern language features for async operations
- Employ type safety where supported
- Use string interpolation methods
- Use optional chaining or equivalent null-safety features

## Development Workflow

1. **Planning**

   - Review requirements thoroughly
   - Break tasks into small, manageable pieces
   - Create detailed TODOs with clear acceptance criteria

2. **Implementation**

   - Follow test-driven development where appropriate
   - Implement features incrementally
   - Commit frequently with meaningful commit messages
   - Update logs and TODOs as you progress

3. **Testing**

   - Write unit tests for all functions
   - Write integration tests for complex workflows
   - Test edge cases and error conditions

4. **Review & Refactor**
   - Review code for improvements
   - Refactor for readability and performance
   - Ensure code is maintainable
   - Remove dead code and unused imports

## Documentation Standards

- **File headers**: Include purpose, author, date, license, dependencies
- **Function comments**: Include purpose, parameters, returns, exceptions, examples
- **README.md**: Include overview, installation, usage, contributions, license

## Logging Standards

- Use consistent format with timestamps, levels, and context
- Log activities performed by ai agents in /logs.md file
- Use very less tokens i.e one liners for logging

## TODO Management

- Create detailed TODOs with acceptance criteria
- Prioritize tasks
- Update as completed in /todo.md file
- Format: [ ] [Priority] Task description - Status (Completed/In Progress/Pending)

## Error Handling

- Use try/catch for error-prone operations
- Handle errors appropriately
- Provide meaningful messages
- Use custom error classes

## Performance Considerations

- Optimize readability first
- Profile for bottlenecks
- Use efficient algorithms
- Minimize memory usage
- Use caching

## Security Considerations

- Validate inputs
- Sanitize outputs
- Use parameterized queries
- Implement auth and authz
- Use secure communications
- Follow least privilege
- Update dependencies

## Version Control

- Descriptive commit messages
- Semantic versioning
- Meaningful branch names
- Use pull requests
- Include tests in commits

## Deployment

- Use env variables for config
- Implement CI/CD
- Test in staging
- Use feature flags
- Implement monitoring
- Have rollbacks
