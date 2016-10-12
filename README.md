[![Build Status](https://travis-ci.org/DenisCarriere/geocoder-promise.svg?branch=master)](https://travis-ci.org/DenisCarriere/geocoder-promise)
[![Coverage Status](https://coveralls.io/repos/github/DenisCarriere/geocoder-promise/badge.svg?branch=master)](https://coveralls.io/github/DenisCarriere/geocoder-promise?branch=master)

# Geocoder (ES6 Module)

A Geocoder written purely in TypeScript and returns Promises.

## Install

```bash
$ npm install --save geocoder-promise
```

## Quickstart

```javascript
import * as geocoder from 'geocoder-promise'

geocoder.google('New York City')
  .then(data => console.log(data))
```

## Tests

```bash
$ npm test
```

## Documentation

```bash
$ npm run docs
```

## Providers

| Providers       | Coverage    | Restrictions |
|-----------------|:------------|:-------------|
| Google          | Global      | API Key      |
<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

# google

Google Provider

**Parameters**

-   `address` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** Location for your search

**Examples**

```javascript
geocoder.google('Ottawa')
  .then(data => data.results)
```

Returns **GoogleResults** JSON Object
