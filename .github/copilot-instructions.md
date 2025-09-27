# Copilot Instructions

## Repository Overview

This is a monorepo designed to house 5 Next.js projects in separate subfolders. The repository follows a structured approach to managing multiple related Next.js applications within a single codebase.

## Project Structure

```
/
├── README.md
├── .github/
│   └── copilot-instructions.md
└── [5 Next.js project subfolders - to be created]
```

## Development Guidelines

### Monorepo Management
- Each Next.js project should be contained in its own subfolder
- Maintain consistent package.json structure across all projects
- Use a shared configuration where possible (ESLint, Prettier, TypeScript)
- Consider workspace configuration for dependency management

### Next.js Best Practices
- Follow Next.js 13+ app directory structure when applicable
- Use TypeScript for type safety
- Implement proper error boundaries and loading states
- Optimize for performance with Next.js built-in features (Image, Link, etc.)
- Use Server Components where appropriate

### Code Quality
- Write clean, readable, and maintainable code
- Use meaningful variable and function names
- Add comments for complex logic
- Follow consistent naming conventions (camelCase for variables/functions, PascalCase for components)
- Implement proper error handling

### Git Workflow
- Create feature branches for new development
- Write descriptive commit messages
- Keep commits focused and atomic
- Test changes before committing

### Dependencies
- Prefer stable, well-maintained packages
- Keep dependencies up to date
- Use exact versions for critical dependencies
- Document any specific version requirements

## Coding Standards

- **JavaScript/TypeScript**: Use modern ES6+ syntax
- **React**: Functional components with hooks
- **Styling**: CSS Modules or styled-components preferred
- **File naming**: kebab-case for files, PascalCase for React components
- **Import order**: External packages, internal modules, relative imports

## Testing
- Write unit tests for utilities and complex components
- Use integration tests for critical user flows
- Aim for meaningful test coverage, not just high percentages
- Test error states and edge cases

## Performance Considerations
- Optimize bundle size and loading performance
- Use Next.js Image component for images
- Implement proper caching strategies
- Monitor and optimize Core Web Vitals

## When Working on This Repository

1. **Understanding the Context**: This is a monorepo structure for 5 Next.js projects
2. **Making Changes**: Ensure changes don't break other projects in the monorepo
3. **Adding Features**: Consider if features can be shared across projects
4. **Dependencies**: Be mindful of version conflicts across projects
5. **Build Process**: Ensure build processes work for all projects

## Specific Guidance for AI Assistants

- Always consider the monorepo context when making suggestions
- Propose solutions that work well with Next.js best practices
- Consider cross-project impacts when making changes
- Suggest shared utilities when appropriate
- Be mindful of the repository's purpose as a container for 5 related projects