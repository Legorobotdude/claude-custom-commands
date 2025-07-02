---
allowed-tools: "*"
description: Generate comprehensive tests for code with proper TypeScript/Python typing
---

# Test Generation

Generate comprehensive tests for the following code:

## Requirements
- **Unit Tests**: Test individual functions/methods in isolation
- **Integration Tests**: Test component interactions where applicable
- **Edge Cases**: Include boundary conditions, error scenarios, and null/undefined handling
- **Type Safety**: Use proper TypeScript types or Python type hints in tests
- **Mocking**: Mock external dependencies appropriately

## Test Structure
- Clear, descriptive test names that explain what is being tested
- Arrange-Act-Assert pattern
- Group related tests logically
- Include setup/teardown when needed

## Framework Expectations
- **Node.js/TypeScript**: Use Jest with TypeScript support
- **Python**: Use pytest with type hints
- Follow existing project testing patterns if apparent

## Coverage Goals
- Test all public methods/functions
- Test error conditions and edge cases
- Verify type constraints are respected
- Include performance tests for critical paths if applicable

Provide complete test files with proper imports, type annotations, and clear documentation.

$ARGUMENTS 