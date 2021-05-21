# node-starter

NodeJS application boilerplate

## Features

- EditorConfig
- Eslint
- Prettier
- Jest
- Husky
- Changelog
- Visual Studio Code

## Popular NPM tasks

- lint
- test
- test:watch
- test:cover
- qc (lint + test)
- version:major
- version:minor
- version:patch
- release

## Release and publish steps

1. Create and switch to a release branch
2. Run `version:*` task
3. Merge the release branch to master and develop branch
4. Create a git tag
5. Run `release` task
6. Run `npm publish`

Note: git-flow can be used here
