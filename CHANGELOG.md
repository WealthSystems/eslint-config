# Changelog

## Unreleased

### Changed

- no-unused-vars: allow destructuring to remove properties
- react/no-did-update-set-state: change to warn due a lot of valid cases

## 1.0.0-alpha.9 - 2019-07-16

### Changed

- no-misleading-character-class: turn on following eslint:recommended
- no-prototype-builtins: turn on following eslint:recommended
- remove options that are now default
- function-paren-newline: change to the new option 'multiline-arguments'
- prefer-named-capture-group: turn off new rule
- import/no-unused-modules: turn on new rule to avoid unused files or dead code
- promise/catch-or-return: allow finally
- react/no-string-refs: disallow template literals as refs
- react: configure new rules
- unicorn: configure new rules
- react/sort-comp: remove patterns that conflicts with arrow-functions

### Breaking changes

Now requires:

- eslint@^6.0
- eslint-plugin-import@^2.18
- eslint-plugin-promise@^4.2
- eslint-plugin-react@^7.14
- eslint-plugin-unicorn@^9.1

## 1.0.0-alpha.8 - 2019-05-02

### Changed

- no-eq-null: turned off

## 1.0.0-alpha.7 - 2019-04-16

### Changed

- camelcase: allow UNSAFE React methods
- react/sort-comp: use default lifecycle group
- react/no-unsafe: changed to warn

## 1.0.0-alpha.6 - 2019-04-15

### Changed

- eqeqeq: allow non-strict equality when comparing with the `null` literal

## 1.0.0-alpha.5 - 2019-04-11

### Changed

- class-methods-use-this: turned off
- consistent-return: changed to warn
- lines-between-class-members: allowed after single line
- new-cap: allowed to properties
- no-invalid-this: turned off
- no-param-reassign: allowed to properties
- no-unused-expressions: turned off
- prefer-destructuring: turned off
- import/prefer-default-export: turned off
- promise/prefer-await-to-then: turned off
- react/destructuring-assignment: turned off
- react/sort-comp: changed patterns
- react/jsx-handler-names: changed to warn

## 1.0.0-alpha.4 - 2019-02-13

### Changed

- react/forbid-prop-types: allow 'any' and 'object'
- react/require-default-props: turn off

## 1.0.0-alpha.3 - 2019-02-12

### Changed

- multiline-comment-style: disabled
- no-shadow: allow shadow confusing browser globals
- import/no-extraneous-dependencies: allow devDependencies under `config/**`

## 1.0.0-alpha.2 - 2019-02-12

### Added

- Engine validation for Node >= 8

### Changed

- Moved ESLint Plugins from `dependencies` to `peerDependencies`
- import/extensions: Ignore extension validation on package import

### Fixed

- Fixed some typos

## 1.0.0-alpha.1 - 2019-02-08

### Added

- Initial configuration
- README explaining how to use this shared configuration
- This CHANGELOG
