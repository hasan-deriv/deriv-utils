# Changelog

## [Unreleased]

### Security
- Updated dependencies to resolve multiple security vulnerabilities:
  - Fixed ReDoS vulnerability in @babel/helpers
  - Fixed ReDoS vulnerabilities in @octokit packages (endpoint, plugin-paginate-rest, request, request-error)
  - Fixed ReDoS vulnerability in micromatch
  - Updated vite and related packages to address development server vulnerability
  - Updated vite-plugin-dts to address XSS vulnerability in vue-template-compiler

### Dependencies
- Updated TypeScript to version ~5.3.3
- Updated Vite ecosystem packages to latest versions:
  - vite
  - vite-node
  - vitest
  - @vitest/coverage-v8
  - @vitest/coverage-istanbul
- Updated vite-plugin-dts to latest version

