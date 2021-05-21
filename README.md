# node-starter

NodeJS application boilerplate

## Quick start

### Prepare your app

```
$ git clone https://github.com/trubavuong/node-starter my-app
$ cd my-app
$ rm -rf .git
$ git init .
```

### Edit some files

1. Update `package.json`
2. Remove `package-lock.json`
3. Update `LICENSE`
4. Update `README.md`
5. Clean `CHANGELOG.md`

### Enjoy

```
$ npm install
```

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
2. Run `npm run version:*`
3. Merge the release branch to `master` and `develop` branch
4. Create a git tag version in `master` branch
5. Delete the release branch
6. Run `npm run release`
7. Run `npm publish`

Note: `git-flow` can be used here (step 1, 3-5)
