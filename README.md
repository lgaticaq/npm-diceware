# diceware-generator

[![npm version](https://img.shields.io/npm/v/diceware-generator.svg?style=flat-square)](https://www.npmjs.com/package/diceware-generator)
[![npm downloads](https://img.shields.io/npm/dm/diceware-generator.svg?style=flat-square)](https://www.npmjs.com/package/diceware-generator)
[![Build Status](https://img.shields.io/travis/lgaticaq/diceware-generator.svg?style=flat-square)](https://travis-ci.org/lgaticaq/diceware-generator)
[![Coverage Status](https://img.shields.io/coveralls/lgaticaq/diceware-generator/master.svg?style=flat-square)](https://coveralls.io/github/lgaticaq/diceware-generator?branch=master)
[![Code Climate](https://img.shields.io/codeclimate/github/lgaticaq/diceware-generator.svg?style=flat-square)](https://codeclimate.com/github/lgaticaq/diceware-generator)
[![dependency Status](https://img.shields.io/david/lgaticaq/diceware-generator.svg?style=flat-square)](https://david-dm.org/lgaticaq/diceware-generator#info=dependencies)
[![devDependency Status](https://img.shields.io/david/dev/lgaticaq/diceware-generator.svg?style=flat-square)](https://david-dm.org/lgaticaq/diceware-generator#info=devDependencies)

> A diceware generator

## Installation

```bash
# Install core package
npm i -S diceware-generator
# Install some diceware wordlist
npm i -S diceware-wordlist-en
# or
npm i -S diceware-wordlist-jp
# or
npm i -S diceware-wordlist-sp
# or
npm i -S diceware-wordlist-swe
# or
npm i -S diceware-wordlist-en-eff
```

[Try on Tonic](https://tonicdev.com/npm/diceware-generator)
## Usage
```javascript
const dwGen = require('diceware-generator');
const enEFF = require('diceware-wordlist-en-eff');

const options = {
  language: enEFF,
  wordcount: 6, // Default 6
  format: 'string', // Default 'string'. One of [array, string]
}
const pass = dwGen(options);
console.log(pass);
// "lavender lunacy quickness ladybug playful reaffirm"
```

## License

[MIT](https://tldrlegal.com/license/mit-license)
