# @alexistessier/msg

![draft](https://img.shields.io/badge/stability-draft-lightgrey.svg?style=flat-square)

![Branch : master](https://img.shields.io/badge/Branch-master-blue.svg)
[![version](https://img.shields.io/badge/version-1.1.9-blue.svg)](https://github.com/AlexisTessier/msg#readme)
[![npm version](https://badge.fury.io/js/%40alexistessier%2Fmsg.svg)](https://badge.fury.io/js/%40alexistessier%2Fmsg)

[![Build Status](https://travis-ci.org/AlexisTessier/msg.svg?branch=master)](https://travis-ci.org/AlexisTessier/msg)
[![Coverage Status](https://coveralls.io/repos/AlexisTessier/msg/badge.svg?branch=master&service=github)](https://coveralls.io/github/AlexisTessier/msg?branch=master)

[![Dependency Status](https://david-dm.org/AlexisTessier/msg.svg)](https://david-dm.org/AlexisTessier/msg)
[![devDependency Status](https://david-dm.org/AlexisTessier/msg/dev-status.svg)](https://david-dm.org/AlexisTessier/msg#info=devDependencies)

Tiny helper to write single line messages on multiple lines

-   [How to use](#how-to-use)
-   [Documentation](#documentation)
-   [License](#license)

## How to use

```javascript
const msg = require('@alexistessier/msg');

console.log(msg(
  `Oh no, this message is too long !!! It's better`,
  `to split it in multiple lines, otherwise my codebase`,
  `will be a little bit ugly.`,
  `In Spanish now !!!`,
  `¡¡¡ Oh no, este mensaje es muy grande !!! Parece mejor`,
  `dividir lo en varias lineas, en otro caso mi base de código`,
  `sera un pocito feia.`,
  `¡¡¡ En Español ahora !!!`
))
```

## Documentation

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

-   [msg](#msg)

### msg

takes strings as parameters, join them with a space and returns the result.

**Parameters**

-   `strings` **...[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** The strings to join

Returns **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** the joined strings

## License

@alexistessier/msg is released under [MIT](http://opensource.org/licenses/MIT). 
Copyright (c) 2017-present [Alexis Tessier](https://github.com/AlexisTessier)
