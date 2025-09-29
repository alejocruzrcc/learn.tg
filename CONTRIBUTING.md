# Contributing to learn.tg

Thank you for your interest in contributing to learn.tg! 🎯

## 📋 Code of Conduct
By participating in this project, you agree to maintain a respectful and collaborative environment.

## 🚀 Development Setup

### Backend (Rails Server)
See instructions in [servidor/README.md](servidor/README.md)

### Frontend (Next.js App)
See instructions in [packages/nextjs-app/README.md](packages/nextjs-app/README.md)

## 🔄 Contributing Process

1. **Fork** the repository
2. **Create a branch** from `main`: `git checkout -b feature/my-feature`
3. **Make your changes** following the style guides
4. **Run tests in directory `packages/nextjs-app`**: `make syntax` and `npm test`
5. **Commit** with clear messages: `git commit -m "feat: add feature X"`
6. **Push** and create a **Pull Request**

## 📝 Code Standards

- **TypeScript**: 
  - Use explicit types, avoid `any` when possible
  - Don´t use ; at the end of the lines
- **Tests**: Try to include tests for new functionality
- **Commits**: Use [Conventional Commits](https://conventionalcommits.org/): `feat:`, `fix:`, `docs:`
- **Linting**: Code at `packages/nextjs-app` must pass `make syntax` without errors

## 🐛 Reporting Bugs

1. Check that no similar issue exists
2. Include steps to reproduce the problem
3. Specify browser/Node.js versions
4. Attach logs or screenshots if relevant

## 💡 Suggesting Features

1. Open an issue describing the feature
2. Explain the use case and benefits
3. Discuss implementation before starting to code

## ❓ Getting Help

- **Issues**: For bugs and suggestions
- **Discussions**: For general questions
- **Documentation**: Check README files for each component
