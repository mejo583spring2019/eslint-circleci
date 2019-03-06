# eslint-circleci

## Getting Started

Ensure your project has a `package.json` in the root of the repo. You can use the following command to create one if it doesn't exist:

```
node init
```

Ensure the `devDevependencies` include `eslint` and `eslint-config-google`. You can use the following command to add them.

```
npm i --save-dev eslint eslint-config-google
```

Here's an example of an updated `package.json`:

```
{
  "name": "testing-linting",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {},
  "devDependencies": {
    "eslint": "^5.15.1",
    "eslint-config-google": "^0.12.0"
  }
}
```
