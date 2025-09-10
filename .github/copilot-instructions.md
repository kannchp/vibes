# GitHub Copilot Context Instructions

This is a Vite + React TypeScript project for a book lending application. When making suggestions or modifications, please consider the following guidelines:

## Project Structure
- Use TypeScript for all new code
- Follow the existing component structure in `src/components`
- UI components should be placed in `src/components/ui`
- Custom hooks should be placed in `src/hooks`
- Types and interfaces should be defined in `src/types`
- Pages should be placed in `src/pages`

## Coding Standards
- Use functional components with hooks
- Prefer TypeScript interfaces over types where appropriate
- Use shadcn/ui components for consistent UI elements
- Follow the existing naming conventions:
  - Components: PascalCase (e.g., `BookCard.tsx`)
  - Hooks: camelCase with 'use' prefix (e.g., `useBooks.ts`)
  - Utilities: camelCase (e.g., `utils.ts`)

## State Management
- Use React hooks for local state management
- Follow the existing pattern in `useBooks.ts` for data handling

## Styling
- Use Tailwind CSS for styling
- Follow the existing color scheme and design system
- Use the utility classes defined in the project

## Testing
- Write tests for new components and hooks
- Follow existing test patterns and conventions

## Best Practices
- Keep components small and focused
- Use proper TypeScript types and interfaces
- Follow React best practices for performance optimization
- Use proper error handling and loading states
- Implement responsive design using Tailwind's breakpoint system

## Dependencies
- Prefer existing project dependencies
- Consult before suggesting new major dependencies
- Use shadcn/ui components when available instead of creating new UI components
