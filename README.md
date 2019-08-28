# wds-repro-quiet-flag-not-working

Reproduction repo showing the `quiet` flag not working.

To get started,

```
yarn
yarn dev
```

The output in the terminal will show initial startup information as well as bundle build information. If you then enable quiet mode in [`webpack.config.js`](./webpack.config.js), the startup information should still show. However, it does not.
