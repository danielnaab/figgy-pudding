# Figgy Pudding 2016

This project will generate a static site to highlight a Spotify playlist.

## Install

```shell
npm install
```

This will install all dependencies into a local `node_modules` directory. Then,
use the `watch` job to start a local dev server on port 9000:

```shell
npm run watch
```

To build a minified distributable, use the `build` job:

```shell
npm run build
```

To deploy to an S3 bucket, use the `deploy` job:

```shell
npm run deploy
```
