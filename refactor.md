---
allowed-tools: "*"
description: Refactor code for better maintainability, organization, and clarity
---

# Code Refactoring

Refactor the following code following these core principles:

## Maintainability
- Use clear, descriptive names for variables, functions, and classes
- Break down complex logic into small, single-responsibility functions
- Apply DRY principles to eliminate redundant code
- Add meaningful comments (JSDoc/TSDoc for JS/TS, Python Docstrings) explaining intent and complexity

## Organization  
- Follow standard style guides (PEP 8 for Python, Airbnb/Google for JS/TS)
- Ensure consistent formatting and logical code structure
- Group related functionality appropriately

## Clarity & Type Safety
- **CRITICAL**: Add comprehensive type hints (TypeScript types, JSDoc @type, Python typing)
- Avoid deep nesting - refactor into helper functions
- Use explicit variable declarations and standard language features
- Prefer clarity over clever implementations

## Language Best Practices
- Apply idiomatic patterns (async/await, proper error handling for Node.js; list comprehensions, context managers for Python)
- Use explicit imports and standard library features

Provide the refactored code with explanations for significant changes.

$ARGUMENTS 