# Zoopla API for Node.js

[![npm](https://img.shields.io/npm/v/zoopla.svg)](https://www.npmjs.com/package/zoopla)  
[![Build Status](https://travis-ci.org/InsidersByte/zoopla.svg)](https://travis-ci.org/InsidersByte/zoopla)
[![Coverage Status](https://coveralls.io/repos/github/InsidersByte/zoopla/badge.svg?branch=master)](https://coveralls.io/github/InsidersByte/zoopla?branch=master)
[![Code Climate](https://codeclimate.com/github/InsidersByte/zoopla/badges/gpa.svg)](https://codeclimate.com/github/InsidersByte/zoopla)  
[![Dependency Status](https://david-dm.org/InsidersByte/zoopla.svg)](https://david-dm.org/InsidersByte/zoopla)
[![devDependency Status](https://david-dm.org/InsidersByte/zoopla/dev-status.svg)](https://david-dm.org/InsidersByte/zoopla#info=devDependencies)

[![NPM](https://nodei.co/npm/zoopla.png?downloads=true&downloadRank=true)](https://nodei.co/npm/zoopla/)

Note that we don't currently support the full API.

## Documentation

Please refer to the [Zoopla API documentation](http://developer.zoopla.com/docs).

## Installing

```bash
npm install zoopla --save
```

## Basic Usage

```js
const Zoopla = require('zoopla');
const zoopla = new Zoopla({ apiKey: 'YOUR_API_KEY' });

zoopla
  .getPropertyListings({ area: 'london' })
  .then((response) => {
    console.log(response);
  })
  .catch((error) => {
    console.error('error', error);
  });
```

## Methods Supported

- [ ] Zed-Index
- [ ] Area Value Graphs
- [ ] Property Rich List
- [ ] Average Area Sold Price
- [ ] Area Zed-Indices
- [ ] Average Sold Prices
- [X] Property Listings
- [ ] Get Session ID
- [ ] Refine Estimate
- [ ] Arrange Viewing
- [ ] Arrange Appraisals
- [ ] Local Info Graphs
- [ ] Geo Autocomplete
