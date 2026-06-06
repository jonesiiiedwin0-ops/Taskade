# 🤝 Contributing to Taskade

First off, thank you for considering contributing to Taskade! It's people like you that make the open source community such an amazing place to learn, inspire, and create. Every contribution helps us move closer to our goal of 100,000 GitHub stars! ⭐

## 🌟 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🎯 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the existing issues as you might find that the problem has already been reported. When creating a bug report, include as many details as possible:

- Use a clear and descriptive title
- Describe the exact steps to reproduce the problem
- Provide specific examples to demonstrate the steps
- Describe the behavior you observed and what behavior you expected
- Include screenshots if applicable
- Specify your OS, browser version, and Taskade version

### 💡 Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- Use a clear and descriptive title
- Provide a step-by-step description of the suggested enhancement
- Provide specific examples to demonstrate the steps
- Describe the current behavior and explain which behavior you expected
- Explain why this enhancement would be useful
- List some other tools where this enhancement exists (if applicable)

### 💻 Your First Code Contribution

Unsure where to begin? You can start by looking through these issue labels:

- `good-first-issue` - Issues that are perfect for newcomers
- `help-wanted` - Issues that need assistance
- `documentation` - Documentation improvements
- `frontend` - Frontend-related issues
- `backend` - Backend-related issues
- `design` - UI/UX improvements

### 🏗️ Development Process

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Taskade.git
   cd Taskade
   ```

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

3. **Set up development environment**
   ```bash
   npm install
   cp .env.example .env
   npm run dev
   ```

4. **Make your changes**
   - Follow our coding standards
   - Write or update tests as needed
   - Update documentation if necessary

5. **Test your changes**
   ```bash
   npm run test
   npm run lint
   npm run build
   ```

6. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add amazing new feature"
   ```
   
   We use [Conventional Commits](https://conventionalcommits.org/):
   - `feat:` - New features
   - `fix:` - Bug fixes
   - `docs:` - Documentation changes
   - `style:` - Code style changes
   - `refactor:` - Code refactoring
   - `test:` - Test additions or modifications
   - `chore:` - Build process or auxiliary tool changes

7. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

8. **Create a Pull Request**
   - Use a clear and descriptive title
   - Reference any related issues
   - Provide a comprehensive description of your changes
   - Include screenshots for UI changes

## 🛠️ Development Setup

### Prerequisites
- Node.js 18+
- npm or yarn
- PostgreSQL 14+
- Redis (optional, for caching)

### Environment Variables
Copy `.env.example` to `.env` and configure:

```bash
# Database
DATABASE_URL=postgresql://username:password@localhost:5432/taskade

# Redis (optional)
REDIS_URL=redis://localhost:6379

# JWT Secret
JWT_SECRET=your-super-secret-key

# App Settings
PORT=3000
NODE_ENV=development
```

### Project Structure
```
Taskade/
├── client/          # React frontend
├── server/          # Node.js backend
├── docs/            # Documentation
├── tests/           # Test files
├── docker/          # Docker configurations
└── scripts/         # Build and deployment scripts
```

## 📋 Coding Standards

### JavaScript/TypeScript
- Use TypeScript for type safety
- Follow ESLint and Prettier configurations
- Use meaningful variable and function names
- Write JSDoc comments for complex functions
- Prefer async/await over promises

### React Components
- Use functional components with hooks
- Follow the component file structure:
  ```typescript
  // Imports
  import React from 'react';
  
  // Types
  interface Props {
    // ...
  }
  
  // Component
  export const Component: React.FC<Props> = ({ prop }) => {
    // ...
  };
  ```

### CSS/Styling
- Use Tailwind CSS for styling
- Follow mobile-first responsive design
- Use semantic class names
- Avoid inline styles

### Testing
- Write unit tests for utility functions
- Write integration tests for API endpoints
- Write component tests for React components
- Aim for >80% code coverage

## 🎨 Design Guidelines

- Follow our [Design System](./docs/design-system.md)
- Use consistent colors, typography, and spacing
- Ensure accessibility (WCAG 2.1 AA compliance)
- Test on multiple screen sizes
- Optimize for performance

## 📚 Documentation

- Update README.md for user-facing changes
- Update API documentation for backend changes
- Add JSDoc comments for complex functions
- Update changelog for notable changes
- Write clear commit messages

## 🧪 Testing

### Running Tests
```bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch

# Run tests with coverage
npm run test:coverage

# Run specific test file
npm test TaskList.test.tsx
```

### Writing Tests
- Test file naming: `ComponentName.test.tsx`
- Test descriptions should be clear and specific
- Use `describe` blocks to group related tests
- Mock external dependencies
- Test both success and error scenarios

## 🚀 Deployment

Our deployment process is automated through GitHub Actions:

1. **Development**: Auto-deploys on push to `develop` branch
2. **Staging**: Auto-deploys on push to `staging` branch
3. **Production**: Auto-deploys on push to `main` branch (with approval)

## 📈 Performance Guidelines

- Optimize images and assets
- Use lazy loading for components
- Minimize bundle size
- Implement proper caching strategies
- Monitor Core Web Vitals

## 🔒 Security Guidelines

- Never commit secrets or API keys
- Validate all user inputs
- Use parameterized queries for database operations
- Implement proper authentication and authorization
- Keep dependencies updated

## 🏷️ Issue Labels

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `good-first-issue` - Good for newcomers
- `help-wanted` - Extra attention is needed
- `documentation` - Improvements to documentation
- `question` - Further information is requested
- `frontend` - Frontend-related issue
- `backend` - Backend-related issue
- `design` - UI/UX related issue
- `performance` - Performance improvements
- `security` - Security-related issue

## 🎉 Recognition

We believe in recognizing our contributors:

- **Contributors** are listed in our README
- **Top contributors** get special mentions in releases
- **Maintainers** receive exclusive swag and conference opportunities
- **Everyone** helps us reach our 100K stars goal!

## 💬 Community

- Join our [Discord](https://discord.gg/taskade) for real-time discussions
- Follow us on [Twitter](https://twitter.com/taskadedev) for updates
- Subscribe to our [newsletter](https://taskade.dev/newsletter) for weekly insights

## ❓ Questions?

Don't hesitate to ask questions! You can:

1. Open a [GitHub Discussion](https://github.com/jonesiiiedwin0-ops/Taskade/discussions)
2. Join our [Discord community](https://discord.gg/taskade)
3. Create an issue with the `question` label

---

**Thank you for contributing to Taskade! Together, we're building the future of productivity.** 🚀

*Remember: Every star ⭐, every contribution 💻, and every bug report 🐛 brings us closer to our goal of 100,000 stars and helps millions of people be more productive!*