# Contributing to Primal Genesis Engine

Thank you for your interest in the Primal Genesis Engine. This document outlines the process for contributing to this project.

## 🌟 Before You Begin

### Code of Conduct

This project adheres to a strict code of conduct. By participating, you are expected to uphold this code.

### Our Development Philosophy

- **Quality over quantity**: Every line of code matters
- **Document everything**: Clear documentation is as important as the code itself
- **Think long-term**: Build with sustainability and maintainability in mind

## 🛠️ Development Setup

### Prerequisites

- Git
- Node.js 20.x or higher
- Python 3.11 or higher

### Getting Started

1. **Fork the repository**
   ```bash
   git clone https://github.com/MKWorldWide/primal-genesis-manifest.git
   cd primal-genesis-manifest
   ```

2. **Install dependencies**
   ```bash
   # Install Node.js dependencies
   npm install
   
   # Install Python dependencies
   pip install -r AthenaMyst_Host/requirements.txt
   ```

3. **Run tests**
   ```bash
   # Run all tests
   npm test
   pytest AthenaMyst_Host/tests
   ```

## 📝 Making Changes

1. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Follow the existing code style
   - Write tests for new features
   - Update documentation as needed

3. **Commit your changes**
   ```bash
   git commit -m "feat: add new feature"
   ```
   
   Use semantic commit messages:
   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation changes
   - `style:` for formatting changes
   - `refactor:` for code changes that neither fix bugs nor add features
   - `test:` for adding or modifying tests
   - `chore:` for maintenance tasks

4. **Push your changes**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**
   - Open a pull request against the `main` branch
   - Describe your changes and reference any related issues
   - Ensure all tests pass
   - Request review from project maintainers

## 🔍 Code Review Process

1. A maintainer will review your PR
2. You may be asked to make changes
3. Once approved, your PR will be merged

## 📜 License

By contributing, you agree that your contributions will be licensed under the project's license.

## 🙏 Thank You

Your contributions help make the Primal Genesis Engine better. Thank you for being part of this journey.
