# 🤝 Contributing to Taskade

We're thrilled that you want to contribute to Taskade! This document will guide you through the process of contributing to our open-source productivity platform.

## 🌟 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md). Please read it before contributing.

## 🎯 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check if the issue already exists. When creating a bug report, include:

- **Clear description** of what happened
- **Steps to reproduce** the issue
- **Expected behavior** vs actual behavior
- **Screenshots** if applicable
- **Environment details** (OS, browser, version)
- **Console logs** if relevant

### 💡 Suggesting Features

We love new ideas! Before suggesting a feature:

1. Check existing issues and discussions
2. Consider if it fits our [roadmap goals](./ROADMAP_TO_100K_STARS.md)
3. Create a detailed feature request with:
   - Problem statement
   - Proposed solution
   - Alternative solutions considered
   - Mockups or diagrams if helpful

### 🔧 Code Contributions

#### Development Setup

1. **Fork the repository**
```bash
git clone https://github.com/YOUR_USERNAME/Taskade.git
cd Taskade
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment**
```bash
cp .env.example .env
# Edit .env with your local configuration
```

4. **Start development server**
```bash
npm run dev
```

5. **Run tests**
```bash
npm test
npm run test:watch  # For development
```

#### Coding Standards

- **TypeScript** - All new code should be written in TypeScript
- **ESLint + Prettier** - Run `npm run lint` and `npm run format`
- **Testing** - Add tests for new features and bug fixes
- **Comments** - Document complex logic and public APIs
- **Performance** - Consider performance implications of your changes

#### Commit Guidelines

We use [Conventional Commits](https://conventionalcommits.org/) for consistent commit messages:

- `feat: add new feature`
- `fix: resolve bug in component`
- `docs: update documentation`
- `style: format code (no functional changes)`
- `refactor: restructure code without changing behavior`
- `test: add or update tests`
- `chore: update dependencies or tooling`

#### Pull Request Process

1. **Create a feature branch**
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

2. **Make your changes**
   - Write clean, well-documented code
   - Add tests for new functionality
   - Update documentation if needed
   - Follow our coding standards

3. **Test your changes**
```bash
npm test
npm run lint
npm run type-check
```

4. **Commit and push**
```bash
git add .
git commit -m "feat: add amazing new feature"
git push origin feature/your-feature-name
```

5. **Create Pull Request**
   - Use our PR template
   - Provide clear description of changes
   - Link related issues
   - Add screenshots for UI changes
   - Request review from maintainers

### 📝 Documentation

Documentation improvements are always welcome:

- **User guides** - Help users understand features
- **Developer docs** - Improve setup and API documentation
- **Code comments** - Clarify complex logic
- **README updates** - Keep project information current
- **Tutorials** - Create step-by-step guides

### 🎨 Design Contributions

- **UI/UX improvements** - Enhance user experience
- **Design system** - Contribute to our component library
- **Accessibility** - Improve accessibility compliance
- **Mobile design** - Optimize for mobile devices
- **Icons and graphics** - Create visual assets

## 🏗️ Project Structure

```
Taskade/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Application pages
│   ├── hooks/          # Custom React hooks
│   ├── utils/          # Utility functions
│   ├── types/          # TypeScript type definitions
│   └── services/       # API and external services
├── docs/               # Documentation
├── tests/              # Test files
├── public/             # Static assets
├── server/             # Backend code
└── scripts/            # Build and utility scripts
```

## 🧪 Testing

### Testing Strategy

- **Unit tests** - Test individual functions and components
- **Integration tests** - Test component interactions
- **E2E tests** - Test complete user workflows
- **Performance tests** - Ensure app remains fast

### Running Tests

```bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch

# Run E2E tests
npm run test:e2e

# Run performance tests
npm run test:perf

# Generate coverage report
npm run test:coverage
```

## 🔍 Code Review Process

### For Contributors

- Be open to feedback and suggestions
- Respond promptly to review comments
- Make requested changes in a timely manner
- Ask questions if feedback isn't clear

### For Reviewers

- Be constructive and respectful
- Focus on code quality and maintainability
- Consider security implications
- Check for test coverage
- Verify documentation updates

## 🏆 Recognition

### Contributor Levels

- **First-time contributor** - Special welcome and guidance
- **Regular contributor** - Recognition in release notes
- **Core contributor** - Invitation to maintainer discussions
- **Maintainer** - Commit access and leadership role

### Hall of Fame

Outstanding contributors will be featured in our:
- README.md contributor section
- Annual contributor highlights
- Conference presentations
- Swag and special recognition

## 📞 Getting Help

### Where to Ask Questions

- **GitHub Discussions** - General questions and ideas
- **Issues** - Bug reports and feature requests
- **Discord** - Real-time community chat (coming soon)
- **Email** - Direct contact for sensitive issues

### Response Times

- **Issues** - 24-48 hours for initial response
- **Pull Requests** - 48-72 hours for first review
- **Discussions** - Community-driven, usually quick
- **Security issues** - 24 hours for acknowledgment

## 🚀 Roadmap Alignment

Help us achieve our [100K stars goal](./ROADMAP_TO_100K_STARS.md) by focusing on:

### Phase 1 (2026-2027) - Foundation
- Core feature development
- Documentation improvements
- Community building
- Performance optimization

### How Your Contribution Fits
- **Code quality** - Builds trust and adoption
- **Feature completeness** - Attracts more users
- **Documentation** - Improves onboarding
- **Community engagement** - Grows our ecosystem

## 📊 Metrics and Goals

### Contribution Metrics
- Pull requests merged per month
- Issues resolved per week
- New contributors joining
- Community engagement levels

### Quality Metrics
- Test coverage percentage
- Code review approval rate
- Bug regression rate
- Performance benchmarks

## 🎉 Release Process

### Versioning

We follow [Semantic Versioning](https://semver.org/):
- **Major** (1.0.0) - Breaking changes
- **Minor** (0.1.0) - New features
- **Patch** (0.0.1) - Bug fixes

### Release Schedule
- **Weekly** - Patch releases for bug fixes
- **Monthly** - Minor releases with new features
- **Quarterly** - Major releases with significant changes

## 🙏 Thank You

Every contribution, no matter how small, makes Taskade better for everyone. Whether you're fixing a typo, adding a feature, or helping other contributors, you're part of building something amazing.

**Together, we're creating the future of collaborative productivity!**

---

*Last updated: June 2026*
*Questions? Open an issue or start a discussion!*