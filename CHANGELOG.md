# Changelog

## Unreleased

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
