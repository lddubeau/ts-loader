# TypeScript, Babel, React, and Karma Sample using [happypack](https://github.com/amireh/happypack) and the [fork-ts-checker-webpack-plugin](https://github.com/Realytics/fork-ts-checker-webpack-plugin)

## Getting started

You'll need [node / npm](https://nodejs.org/) installed.  To get up and running just enter:

```
yarn install
yarn serve
```

This will:

1. Download the npm packages you need (including the type definitions from DefinitelyTyped)
2. Compile the code and serve it up at [http://localhost:8080](http://localhost:8080)

When you're building for production then `yarn build`