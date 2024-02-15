# Modern React Snippet

Code snippets for React 17/18+ in ES6+ syntax and the JavaScript Standard Style.
It is very basic but additional snippets can be added if requested.

## Features

Add React snippets that:

- excludes `import React from 'react'`, beginning with React 17, bundlers now
  can use JSX transform without importing `React`.
- excludes Class components, Functional components is now the best and default
  way to create React components.
- excludes Semicolons, JavaScript automatically insert semicolons to terminate
  statements.
- using interfaces for prop types in TypeScript.

Use [ESLint](https://eslint.org), [TypeScript ESLint][1], and a formatter
(like [Prettier](https://prettier.io)) after adding snippets to conform to your
coding style. Additionally add `"source.addMissingImports" = "explicit"` to
`"editor.codeActionsOnSave"` in your vscode settings to add imports.

## Release Notes

[Check out the changelog for release.](CHANGELOG.md)

## License

Modern React Snippets is licensed under the [MIT License](LICENSE.md).

[1]: https://typescript-eslint.io/
