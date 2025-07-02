---
allowed-tools: "*"
description: Analyze and improve project structure and organization
---

# Project Structure Analysis

Analyze and improve the project structure and organization:

## Current Project Overview
- **Directory Structure**: !`find . -type d -not -path '*/node_modules/*' -not -path '*/.git/*' -not -path '*/.*' | head -20`
- **Key Files**: !`find . -name "*.ts" -o -name "*.tsx" -o -name "*.js" -o -name "*.jsx" -o -name "*.py" | grep -E '\.(ts|tsx|js|jsx|py)$' | head -15`
- **Package.json**: !`cat package.json | grep -A 10 -B 5 '"scripts"'`
- **Dependencies**: !`cat package.json | grep -A 10 '"dependencies"'`

## Structure Analysis
- **Modularity**: Evaluate separation of concerns and module boundaries
- **Naming Conventions**: Check consistency in file and directory naming
- **Import Patterns**: Analyze import/export structure and dependencies
- **Code Organization**: Review logical grouping of related functionality
- **Configuration**: Check build, test, and deployment configuration

## Best Practices
- **Feature-Based Organization**: Group files by feature rather than file type
- **Shared Components**: Identify reusable components and utilities
- **Type Definitions**: Centralize type definitions appropriately
- **Constants & Enums**: Organize constants and configuration
- **API Layer**: Structure API calls and data fetching

## Suggested Improvements
- **Directory Restructuring**: Recommend better organization
- **File Naming**: Suggest consistent naming conventions
- **Dependency Management**: Optimize imports and reduce coupling
- **Documentation**: Add README files for complex modules
- **Build Optimization**: Improve build configuration and performance

## Framework-Specific (Next.js/React)
- **App Router Structure**: Follow Next.js 13+ conventions
- **Component Hierarchy**: Organize components logically
- **Custom Hooks**: Extract reusable logic into custom hooks
- **Middleware**: Structure middleware and API routes properly

## Tooling & Automation
- **Linting Configuration**: Check ESLint, Prettier setup
- **Testing Structure**: Organize test files and utilities
- **Build Pipeline**: Review CI/CD and build processes
- **Documentation**: Ensure adequate project documentation

Provide specific recommendations for improving project organization and maintainability.

$ARGUMENTS 