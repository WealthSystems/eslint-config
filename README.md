# @WealthSystems/eslint-config

The [ESLint](https://eslint.org) shared configuration to be used in all JavaScript project's across Wealth Systems.

## Requirements

- Node: >= 8
- eslint: ^5.12.0
- eslint-plugin-import: ^2.16.0
- eslint-plugin-promise: ^4.0.0
- eslint-plugin-react: ^7.12.0
- eslint-plugin-unicorn: ^7.1.0

## Installation

First, install this shared configuration and the required plugins:

```sh
# npm
npm install --save-dev @wealthsystems/eslint-config eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-unicorn

# yarn
yarn add @wealthsystems/eslint-config eslint-plugin-import eslint-plugin-promise eslint-plugin-react eslint-plugin-unicorn --dev
```

Then, add `@wealthsystems/eslint-config` in your `.eslintrc` file:

```json
{
    "extends": [
        "@wealthsystems"
    ]
}
```
