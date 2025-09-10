# GitHub Copilot Instructions

## Project Overview
This is a library management web application built with React, TypeScript, and Vite. The application allows users to manage books, including adding new books, lending books, and viewing book details.

## Code Style Guidelines

1. **TypeScript**:
   - Use TypeScript strict mode
   - Prefer explicit type annotations for function parameters and return types
   - Use interfaces for object shapes
   - Avoid using `any` type

2. **React Components**:
   - Use functional components with hooks
   - Follow React hooks best practices
   - Props interfaces should be named with `Props` suffix (e.g., `ButtonProps`)
   - Keep components focused and single-responsibility

3. **File Structure**:
   - Components go in `src/components/`
   - Pages go in `src/pages/`
   - Hooks go in `src/hooks/`
   - Types go in `src/types/`
   - UI components go in `src/components/ui/`

4. **Naming Conventions**:
   - PascalCase for component files and component names
   - camelCase for functions and variables
   - Use descriptive, meaningful names
   - Prefix custom hooks with "use"

5. **State Management**:
   - Use React hooks for local state
   - Keep state as close as possible to where it's used
   - Use context for global state when necessary

6. **Error Handling**:
   - Use try-catch blocks for async operations
   - Implement proper error boundaries
   - Display user-friendly error messages

7. **Comments and Documentation**:
   - Add JSDoc comments for components and functions
   - Document complex logic
   - Keep comments up to date and meaningful

8. **Testing**:
   - Write unit tests for components
   - Test edge cases and error scenarios
   - Keep test files alongside component files

## Dependencies
- Use existing UI components from the components/ui directory
- Utilize existing hooks when possible
- Add new dependencies only when necessary

## Performance Considerations
- Implement proper memoization where needed
- Optimize re-renders
- Use lazy loading for routes
- Consider bundle size when adding new features

## Security Guidelines
- Sanitize user inputs
- Implement proper data validation
- Follow React security best practices
