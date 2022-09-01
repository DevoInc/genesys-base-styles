# Contributing to vizco

Thanks for taking the time to contribute! 😄

## Code of Conduct

All contributors are expecting to abide by our [Code of
Conduct](CODE_OF_CONDUCT.md).

## Table of Contents

- [Requirements](#requirements)
- [Getting Started](#getting-started)
  - [Clone repo](#clone-repo)
  - [Install dependencies](#install-dependencies)
- [Committing Code](#committing-code)
  - [Committing message](#committing-message)

## Requirements

You must have the following installed on your system to contribute locally:

- [Node.js](https://nodejs.org/en/): Version of **node >= 14.18.1**.
- [Npm.js](https://www.npmjs.com/): Version of **npm >= 7.24.2**.

Info! Before installing anything you can check if you
already have it on your system and what versions you have by running this
command:

```sh
node -v; npm -v
//v14.18.1
//v7.24.2
```

## Getting Started

### Clone repo

```sh
git clone git@github.com:DevoInc/dali-base-styles.git
```

### Install dependencies

```sh
# Go into the repository
cd dali-base-styles

# Install dependencies
npm ci
```

### Build the dist directory with the SCSS resources

```sh
npm run build
```

## Committing Code

In this project we use continuos integration. The repository is setup with a
single **master** branch, with the already published Dali styles.

### Committing message

Follow [coventional commits](https://www.conventionalcommits.org/en/v1.0.0/).

For example:

```sh
fix: lorem ipsum...
```

There are certain points to keep in mind in order to have common messages among
all team members:

- **Scope of the commit is always in lower case**. For example:

```sh
fix(scope): lorem ipsum...

fix(scope): lorem ipsum...
```
