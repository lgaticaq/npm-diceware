# diceware-generator

[![npm version](https://img.shields.io/npm/v/diceware-generator.svg?style=flat-square)](https://www.npmjs.com/package/diceware-generator)
[![npm downloads](https://img.shields.io/npm/dm/diceware-generator.svg?style=flat-square)](https://www.npmjs.com/package/diceware-generator)
[![Build Status](https://img.shields.io/travis/lgaticaq/diceware-generator.svg?style=flat-square)](https://travis-ci.org/lgaticaq/diceware-generator)
[![Coverage Status](https://img.shields.io/coveralls/lgaticaq/diceware-generator/master.svg?style=flat-square)](https://coveralls.io/github/lgaticaq/diceware-generator?branch=master)
[![Code Climate](https://img.shields.io/codeclimate/github/lgaticaq/diceware-generator.svg?style=flat-square)](https://codeclimate.com/github/lgaticaq/diceware-generator)
[![dependency Status](https://img.shields.io/david/lgaticaq/diceware-generator.svg?style=flat-square)](https://david-dm.org/lgaticaq/diceware-generator#info=dependencies)
[![devDependency Status](https://img.shields.io/david/dev/lgaticaq/diceware-generator.svg?style=flat-square)](https://david-dm.org/lgaticaq/diceware-generator#info=devDependencies)

A diceware generator

## Installation

```bash
npm i -S diceware-generator
```

[Try on Tonic](https://tonicdev.com/npm/diceware-generator)
## Usage
```javascript
import dwGen from 'diceware-generator';
dwGen();  // 'stare too magog guess kirov grout'
dwGen(options);
default options:
{
	'language': 'en',  // currently only en, swe, jp, sp and enEFF are supported
	'wordcount': 6,
	'format': 'string',  // one of [array, string]
}
```
