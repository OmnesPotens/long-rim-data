# The Long Rim data for Comp/Con

[![NPM Publish](https://github.com/OmnesPotens/long-rim-data/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/OmnesPotens/long-rim-data/actions/workflows/npm-publish.yml) [![GPR Publish](https://github.com/OmnesPotens/long-rim-data/actions/workflows/gpr-publish.yaml/badge.svg)](https://github.com/OmnesPotens/long-rim-data/actions/workflows/gpr-publish.yaml)


## Installation

```js
npm add @massif/long-rim-data
//or
yarn add @massif/long-rim-data
```

## Usage

```js
import * as longRim from '@massif/long-rim-data';

const longRimFrameData = longRim.frames;
```

## Building LCP

```js
yarn && yarn build
// or
npm install && npm run build
```

produces a versioned LCP file in `dist/`
