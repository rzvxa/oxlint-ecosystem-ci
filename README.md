# oxlint-ecosystem ci

This repository is used to run integration tests for oxlint ecosystem projects

## Scheduled github workflow

Workflows are scheduled to run automatically every day

## Manual github workflow

* open [workflow](https://github.com/oxc-project/oxlint-ecosystem-ci/actions/workflows/ecosystem-ci.yml)
* click 'Run workflow' button on top right of the list
* select suite to run in dropdown
* start workflow

## Local

- `./clone.js` - clones all the repositories
- `./update.js` - updates (git pull) all the repositories
- `./run.js PATH_TO_OXLINT_BINARY` - run oxlint

## Add a new integration test

* Add your repository to the test-ecosystem matrix [ecosystem-ci.yml](https://github.com/oxc-project/oxlint-ecosystem-ci/blob/main/.github/workflows/ecosystem-ci.yml)
* Due to maintenance burden, a [sponsorship](https://github.com/sponsors/Boshen) will have a more likely hood of having the PR accepted.

## repositories

* [rolldown/rolldown](https://github.com/rolldown-rs/rolldown)
* [napi-rs/napi-rs](https://github.com/napi-rs/napi-rs)
* [toeverything/affine](https://github.com/toeverything/affine)
* [preactjs/preact](https://github.com/preactjs/preact)

<p align="center">
  <a href="https://github.com/sponsors/Boshen">
    <img src="https://cdn.jsdelivr.net/gh/boshen/sponsors/sponsors.svg" alt="My sponsors" />
  </a>
</p>
