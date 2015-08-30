# npm-auto-update

## Requirements

- [Node.js](https://nodejs.org/), e.g. via [nvm](https://github.com/creationix/nvm)
- [David](https://david-dm.org/), via `npm install david -g`


## Usage

```bash
GITHUB_TOKEN=USER_TOKEN ./npm-auto-update username reponame
```

The `GITHUB_TOKEN` has to have the rights to create a pull request on GitHub for the given `username`.
