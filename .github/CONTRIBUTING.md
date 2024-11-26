# Contributing to Polylang

Thank you for your interest in contributing to Polylang! This document provides guidelines and information for contributors.

## Getting Started

### Prerequisites

Before you begin, ensure you have:

1. WordPress 6.2 or later installed locally
2. Git
3. Node.js (LTS version recommended)
4. Composer

### Development Setup

1. Fork the repository on GitHub
2. Clone your fork locally:

```bash
 cd wp-content/plugins
 git clone https://github.com/YOUR-USERNAME/polylang.git
 cd polylang
 ```

3. Set up development dependencies:

```bash
composer build
```

## Development Workflow

1. Create a new branch for your feature or fix:

```bash
git checkout -b feature/your-feature-name
```

2. Make your changes following our coding standards
3. Test your changes thoroughly
4. Commit your changes with clear, descriptive messages
5. Push to your fork and submit a pull request

### Coding Standards

- Follow WordPress Coding Standards
- Use PHP CodeSniffer and ESLint (included in dev dependencies)
- Run code quality checks before submitting:

```bash
composer cs   # Check coding standards
composer stan # Static analysis
composer test # Run PHPUnit tests
```

## Pull Request Guidelines

1. Provide a clear and concise description
2. Link any related issues in your pull request description
3. Ensure all tests pass

## Reporting Issues

- Use the issue template when creating new issues
- Include detailed steps to reproduce bugs
- Specify your WordPress and Polylang versions
- Specify third party names and versions if applicable
- Include relevant error messages and screenshots

## Documentation

- Keep inline documentation up to date
- Follow PHPDoc standards for new code

## Questions?

- For general purpose questions, feel free to contact us at our [helpdesk](https://polylang.pro/support/) (premium support only).

## License

By contributing to Polylang, you agree that your contributions will be licensed under the GPL-3.0 License.
