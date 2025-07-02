---
allowed-tools: "*"
description: Comprehensive code review with git context and best practices
---

# Comprehensive Code Review

Perform a thorough code review of the following changes:

## Git Context Analysis
- **Recent Changes**: !`git log --oneline -10`
- **Current Status**: !`git status`
- **Staged Changes**: !`git diff --cached`
- **Unstaged Changes**: !`git diff`
- **Current Branch**: !`git branch --show-current`

## Code Quality Review
- **Architecture**: Evaluate overall design and structure
- **Maintainability**: Assess code clarity and future maintenance needs  
- **Performance**: Identify potential performance issues
- **Security**: Review for security vulnerabilities and best practices
- **Type Safety**: Verify comprehensive type coverage and safety

## Best Practices Checklist
- **Naming**: Clear, descriptive variable and function names
- **Function Size**: Functions are small and single-purpose
- **Error Handling**: Proper error handling and edge case coverage
- **Testing**: Adequate test coverage and quality
- **Documentation**: Appropriate comments and documentation

## Language-Specific Review
- **TypeScript/JavaScript**: Type annotations, async/await patterns, module structure
- **Python**: Type hints, PEP 8 compliance, proper imports
- **React/Next.js**: Component patterns, hooks usage, performance optimizations

## Security & Reliability
- **Input Validation**: Proper sanitization and validation
- **Authentication**: Secure auth implementation
- **Data Handling**: Safe data processing and storage
- **Dependency Management**: Review of external dependencies

## Suggestions & Improvements
- Provide specific, actionable feedback
- Suggest alternative implementations where beneficial
- Highlight potential refactoring opportunities
- Recommend additional tests or documentation

## Approval Criteria
- Code follows established patterns and conventions
- No security vulnerabilities identified
- Adequate test coverage
- Clear documentation and comments
- Performance considerations addressed

Provide detailed feedback with specific line-by-line suggestions where applicable.

$ARGUMENTS 