---
allowed-tools: "*"
description: Review and improve API design following REST principles and best practices
---

# API Design Review

Review and improve the API design for the following code:

## REST Principles
- **Resource-Based URLs**: Use nouns, not verbs in endpoint paths
- **HTTP Methods**: Use appropriate methods (GET, POST, PUT, PATCH, DELETE)
- **Status Codes**: Return proper HTTP status codes for different scenarios
- **Idempotency**: Ensure PUT and DELETE operations are idempotent
- **Statelessness**: Design stateless interactions

## Request/Response Design
- **Consistent Structure**: Use consistent JSON structure across endpoints
- **Validation**: Implement comprehensive input validation with clear error messages
- **Pagination**: Add pagination for collection endpoints
- **Filtering & Sorting**: Support query parameters for filtering and sorting
- **Versioning**: Consider API versioning strategy

## Type Safety & Documentation
- **TypeScript Interfaces**: Define clear request/response types
- **OpenAPI/Swagger**: Consider API documentation standards
- **Error Types**: Define consistent error response structures
- **Validation Schemas**: Use schema validation (Zod, Joi, etc.)

## Security Considerations
- **Authentication**: Implement proper auth mechanisms
- **Authorization**: Role-based access control where needed
- **Rate Limiting**: Consider rate limiting for public APIs
- **Input Sanitization**: Prevent injection attacks
- **CORS**: Configure CORS appropriately

## Performance & Reliability
- **Caching**: Add appropriate caching headers
- **Compression**: Use response compression where beneficial
- **Error Handling**: Graceful error handling and logging
- **Monitoring**: Add health checks and metrics endpoints

## Next.js Specific
- **Route Handlers**: Follow Next.js App Router patterns
- **Middleware**: Use middleware for cross-cutting concerns
- **Edge Runtime**: Consider edge runtime for performance

Provide improved API design with explanations for architectural decisions.

$ARGUMENTS 