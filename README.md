# ValueAdd NestJS Packages

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![build](https://github.com/valueadd-poland/nestjs-packages/workflows/MASTER%20CI/badge.svg)](https://github.com/valueadd-poland/nestjs-packages/actions?query=workflow%3A%22MASTER+CI%22)

A collection of packages, modules and utilities for NestJS.

| Package                                            | Description                                                        | Version                                                                                                                             | Changelog                                    |
| -------------------------------------------------- | ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| [`@valueadd/nestjs-streaming`](packages/streaming) | Useful providers that allows working with streaming like responses | [![version](https://img.shields.io/npm/v/@valueadd/nestjs-streaming.svg)](https://www.npmjs.com/package/@valueadd/nestjs-streaming) | [changelog](packages/streaming/CHANGELOG.md) |

## Development

### Setup

- `$ npm install`
- `$ npm run lerna bootstrap`

### Publish packages

- `npm run lerna version -- --conventional-commits`
- `npm run lerna publish from-git`
