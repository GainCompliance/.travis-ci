# .travis-ci

Repository of reusable configuration for Travis CI

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

## Usage

<!-- consumer badges -->
[![MIT license][license-badge]][license-link]

### Importing into other GainCompliance projects

All configs in this repository can be [imported](https://docs.travis-ci.com/user/build-config-imports)
into the configuration of projects within the `GainCompliance` organization.
This includes the configs prefixed with `authenticated-` because the
[shared encrypted secrets](https://docs.travis-ci.com/user/build-config-imports#sharing-encrypted-secrets)
are accessible across the organization.

:warning: Be sure to use the correct casing of `GainCompliance` in the import
statement. Failing to do so will prevent the import from working.

## Contributing

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![PRs Welcome][PRs-badge]][PRs-link]

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/GainCompliance/.travis-ci.svg
[ci-link]: https://travis-ci.com/GainCompliance/.travis-ci
[ci-badge]: https://img.shields.io/travis/com/GainCompliance/.travis-ci/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
