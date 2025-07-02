---
allowed-tools: "*"
description: Apply clean code principles and best practices for maintainable software
---

# Clean Code Review

Apply clean code principles to improve the following code:

## Naming Conventions
- **Descriptive Names**: Use clear, descriptive names that reveal intent
- **Consistent Terminology**: Use consistent vocabulary throughout the codebase
- **Avoid Abbreviations**: Use full words instead of cryptic abbreviations
- **Boolean Naming**: Use is/has/can prefixes for boolean variables
- **Function Names**: Use verbs for functions, nouns for variables/classes

## Function Design
- **Single Responsibility**: Each function should do one thing well
- **Small Functions**: Keep functions small and focused (ideally < 20 lines)
- **Pure Functions**: Prefer pure functions without side effects
- **Function Arguments**: Limit to 3-4 parameters, use objects for more
- **Avoid Deep Nesting**: Extract nested logic into separate functions

## Code Organization
- **DRY Principle**: Eliminate duplicate code through abstraction
- **Separation of Concerns**: Separate business logic from presentation and data
- **Consistent Formatting**: Apply consistent indentation and spacing
- **Logical Grouping**: Group related functionality together
- **Import Organization**: Organize imports (external, internal, relative)

## Error Handling
- **Explicit Error Handling**: Handle errors explicitly, don't ignore them
- **Error Types**: Use specific error types instead of generic ones
- **Graceful Degradation**: Provide fallbacks for non-critical failures
- **Logging**: Add appropriate logging for debugging and monitoring

## Comments & Documentation
- **Intent Documentation**: Explain why, not what
- **Remove Dead Code**: Delete commented-out code and unused imports
- **API Documentation**: Document public interfaces thoroughly
- **Complex Logic**: Add comments for non-obvious algorithms or business rules

## Performance Considerations
- **Avoid Premature Optimization**: Focus on clarity first
- **Efficient Algorithms**: Use appropriate data structures and algorithms
- **Memory Management**: Avoid memory leaks and unnecessary allocations
- **Async Best Practices**: Use async/await properly for I/O operations

## Type Safety (Critical)
- **Complete Type Coverage**: Add type hints/annotations everywhere
- **Runtime Validation**: Validate external data at boundaries
- **Type Guards**: Use type guards for safe type narrowing
- **Null Safety**: Handle null/undefined cases explicitly

Provide cleaned code following these principles with explanations for improvements.

$ARGUMENTS 