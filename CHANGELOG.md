# Change Log

All notable changes to the "modern-react-snippets" extension will be documented in this file.

## [0.0.2]

- Fix snippets configuration
- Add entry point snippet

## [0.0.1]

- Initial release
- Add snippets that:
  - excludes `import React from 'react'`, beginning with React 17, bundlers now
    can use JSX transform without importing `React`.
  - excludes Class components, Function components is now the best and default
    way to create React components.
  - excludes Semicolons, JavaScript automatically insert semicolons to terminate
    statements.
  - using interfaces for prop types in TypeScript.
