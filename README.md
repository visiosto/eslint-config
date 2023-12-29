# Visiosto ESLint Configuration

These are the ESLint configurations for Visiosto projects.

## Installation

First install [ESLint](https://eslint.org) and the configuration package. Please
note that the `@visiosto/eslint-config` package is stored within the GitHub npm
package registry. To get the package from the right registry, add
`@visiosto:registry=https://npm.pkg.github.com` to your `.npmrc`.

    npm install --save-dev eslint @visiosto/eslint-config

Extend the shared configuration in your ESLint configuration.

```json
{
  "extends": "@visiosto/eslint-config"
}
```

For more information on shared ESLint configuration, please see
[the ESLint documentation](https://eslint.org/docs/latest/extend/shareable-configs#using-a-shareable-config).

## Licence

This project is licensed under the BSD 3-Clause License. For more information,
please see the [LICENSE](LICENSE) file.
