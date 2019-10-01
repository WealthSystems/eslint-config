# @WealthSystems/eslint-config

The [ESLint](https://eslint.org) shared configuration to be used in all JavaScript project's across Wealth Systems.

## Requirements

- Node: >= 8
- eslint: ^6.5.0
- eslint-plugin-import: ^2.18.0
- eslint-plugin-promise: ^4.2.0
- eslint-plugin-react: ^7.14.0
- eslint-plugin-unicorn: ^12.0.0

## Installation

First, install this shared configuration and the required plugins:

```sh
# npm
npm install --save-dev @wealthsystems/eslint-config eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-unicorn

# yarn
yarn add --dev @wealthsystems/eslint-config eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-unicorn
```

Then, add `@wealthsystems/eslint-config` in your `.eslintrc` file:

```json
{
    "extends": [
        "@wealthsystems"
    ]
}
```
