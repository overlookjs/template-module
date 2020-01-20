[![NPM version](https://img.shields.io/npm/v/@overlook/{{name}}.svg)](https://www.npmjs.com/package/@overlook/{{name}})
[![Build Status](https://img.shields.io/travis/overlookjs/{{name}}/master.svg)](http://travis-ci.org/overlookjs/{{name}})
[![Dependency Status](https://img.shields.io/david/overlookjs/{{name}}.svg)](https://david-dm.org/overlookjs/{{name}})
[![Dev dependency Status](https://img.shields.io/david/dev/overlookjs/{{name}}.svg)](https://david-dm.org/overlookjs/{{name}})
[![Greenkeeper badge](https://badges.greenkeeper.io/overlookjs/{{name}}.svg)](https://greenkeeper.io/)
[![Coverage Status](https://img.shields.io/coveralls/overlookjs/{{name}}/master.svg)](https://coveralls.io/r/overlookjs/{{name}})

# {{description}}

Part of the [Overlook framework](https://overlookjs.github.io/).

## Usage

This module is under development and not ready for use yet.

## Versioning

This module follows [semver](https://semver.org/). Breaking changes will only be made in major version updates.

All active NodeJS release lines are supported (v10+ at time of writing). After a release line of NodeJS reaches end of life according to [Node's LTS schedule](https://nodejs.org/en/about/releases/), support for that version of Node may be dropped at any time, and this will not be considered a breaking change. Dropping support for a Node version will be made in a minor version update (e.g. 1.2.0 to 1.3.0). If you are using a Node version which is approaching end of life, pin your dependency of this module to patch updates only using tilde (`~`) e.g. `~1.2.3` to avoid breakages.

## Tests

Use `npm test` to run the tests. Use `npm run cover` to check coverage.

## Changelog

See [changelog.md](https://github.com/overlookjs/{{name}}/blob/master/changelog.md)

## Issues

If you discover a bug, please raise an issue on Github. https://github.com/overlookjs/{{name}}/issues

## Contribution

Pull requests are very welcome. Please:

* ensure all tests pass before submitting PR
* add tests for new features
* document new functionality/API additions in README
* do not add an entry to Changelog (Changelog is created when cutting releases)
