# commitlint-config-velosodigital

Shareable [`commitlint`](https://github.com/conventional-changelog/commitlint) config used by Veloso Digital.

## Getting started

Installing:

```sh
# npm
npm i -D commitlint-config-velosodigital

# yarn
yarn add -D commitlint-config-velosodigital
```

Apply the config to `commitlint`:

```sh
echo "module.exports = {extends: ['velosodigital']};" > commitlint.config.js
```

## Examples
```sh
chore: (updating grunt tasks etc; no production code change)
ci: (updating grunt tasks etc; no production code change)
docs: (changes to the documentation)
feat: (new feature for the user, not a new feature for build script)
fix: (bug fix for the user, not a fix to a build script)
test: (adding missing tests, refactoring tests; no production code change)
refactor: (refactoring production code, eg. renaming a variable)

```
