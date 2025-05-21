# @f88/test-ghp

[![Publish to GitHub Packages](https://github.com/F88/test-ghp/actions/workflows/npm-publish-github-packages.yml/badge.svg?branch=main)](https://github.com/F88/test-ghp/actions/workflows/npm-publish-github-packages.yml)

A test package for publishing to the GitHub Packages npm registry (npm.pkg.github.com). This package is intended to be used with an AI agent.

## Overview/Features

Currently, the package provides a simple "Hello, World!" example. It is designed to be a component of an AI agent, providing specific functionalities to interact with Node.js environments. This package is published on GitHub Packages.

## Installation Instructions

To install the package, use the following npm command:

```bash
npm install @f88/test-ghp
```
Ensure your `.npmrc` file is configured to scope `@f88` to the GitHub Packages registry, or that the package is publicly accessible.

## Usage Examples

Here's a basic JavaScript example of how to import and use the package:

```javascript
const myPackage = require('@f88/test-ghp');

// Example usage (assuming the package exports a function)
// myPackage.someFunction();
console.log(myPackage.hello()); // If the package has a hello() function
```

## Publishing

This package is automatically published to GitHub Packages using GitHub Actions when new releases are created or code is pushed to the `main` branch.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the ISC License.
