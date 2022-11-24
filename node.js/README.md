# @silta/eslint-config-nodejs

A shared `eslint` config between Silta node.js projects. Extends [`eslint-config-airbnb-base`](https://www.npmjs.com/package/eslint-config-airbnb-base)
with a few changes thrown in. See [`.eslintrc.js`](./.eslintrc.js) for the ruleset.

## Usage

### Setup
First install the package with
```
npm install -D @silta/eslint-config-nodejs
```

Then install the peer dependencies. The easiest way to do this is with `npx` (`npm` > 5.2.0):
```
npx install-peerdeps [-d] @silta/eslint-config-nodejs
```
`-d` is to install them as `devDependencies`


### Config
In your `.eslintrc.json` (or `.js`) file you must extend `@silta/eslint-config-nodejs`:
```
{
  extends: '@silta/eslint-config-nodejs'
}
```
