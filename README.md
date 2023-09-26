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
    npm i
    ```

1. Login to NPM

    ```
    npm adduser
    ```



## Deploy to NPM

Update the package.json version number
Build `index.json` and publish to npm

```
npm run prepare
npm publish
```

## Changelog

- 1.1.0 - Rules for async/await
- 2.0.0 - Major updatest to latest packages (Feb 22)
- 2.1.0 - Updatest to latest packages, simplify with npm (Sep 23)

