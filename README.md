# eslint-config-node
huddo eslint config for node services

.eslintrc.yaml:

```
  extends:
    - @huddo/eslint-config-node
```

## Getting Started

1. Install dependencies

    ```
    yarn
    ```

1. Login to NPM

    ```
    npm adduser
    ```



## Deploy to NPM

Update the package.json version number
Build `index.json` and publish to npm

```
yarn run prepare
npm publish
```

## Changelog

- 1.1.0 - Rules for async/await
