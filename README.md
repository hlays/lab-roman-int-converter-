# Conversor de algarismos romanos para arábicos (e vice-versa)

[![Build Status](https://travis-ci.org/layshidani/lab-roman-int-converter.svg?branch=master)](https://travis-ci.org/layshidani/lab-roman-int-converter)
[![Coverage Status](https://coveralls.io/repos/github/layshidani/lab-roman-int-converter/badge.svg?branch=master)](https://coveralls.io/github/layshidani/lab-roman-int-converter?branch=master)

[![link-npm](https://img.shields.io/badge/link-npm-red.svg)](https://www.npmjs.com/package/lab-roman-int-converter)

![JavaScript](https://img.shields.io/badge/-JavaScript-yellow.svg)
![mocha](https://img.shields.io/badge/-mocha-yellowgreen.svg)
![nyc](https://img.shields.io/badge/-nyc-brightgreen.svg)
![chai](https://img.shields.io/badge/-chai-orange.svg)

Esta biblioteca se destina a converter algarismos romanos para números inteiros e vice e versa.

## Como instalar:

```bash
$  npm install lab-roman-int-converter
```

## Como utilizar:

### Converter algarismos romanos

*Formato de entrada da função: string.*

Exemplo:

```node
const romanToInt = require('lab-roman-int-converter');

romanToInt('Xx');
// return 20
```

### Converter números inteiros para romanos
*Formato de entrada da função: números (em string ou number).*

Exemplo:

```node
const intToRoman = require('lab-roman-int-converter');

intToRoman(20);
// return XX
```

## Roadmap oficial do projeto

### versão 1.0.0 (released)
* converte romanos para inteiros
* converte inteiros para romanos
* aceita strings maiúsculas e minúsculas para converter romanos para números inteiros
* aceita strings e números para converter inteiros para romanos