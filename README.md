<!-- Do not modify README.md, instead modify README.hbs -->

# @shabados/gurmukhi-utils

General utilities for working with Gurmukhi.

[![CircleCI](https://img.shields.io/circleci/project/github/ShabadOS/gurmukhi-utils.svg?style=for-the-badge)](https://circleci.com/gh/ShabadOS/gurmukhi-utils)
[![npm (scoped)](https://img.shields.io/npm/v/@shabados/gurmukhi-utils.svg?style=for-the-badge)](https://www.npmjs.com/package/@shabados/gurmukhi-utils)
[![David](https://img.shields.io/david/ShabadOS/gurmukhi-utils.svg?style=for-the-badge)](<>)
[![license](https://img.shields.io/github/license/ShabadOS/gurmukhi-utils.svg?style=for-the-badge)](<>)

## Usage

```javascript
const { toUnicode, toAscii, firstLetters } = require('gurmukhi-utils')

toUnicode('Koj')    // Returns ਖੋਜ
toAscii('ਖੋਜ')       // Returns Koj
firstLetters('hir hir hir gunI')   // Returns hhhg
firstLetters('ਹਰਿ ਹਰਿ ਹਰਿ ਗੁਨੀ')      // Returns ਹਹਹਗ
```

## Docs

* * *

<a name="toUnicode"></a>

## toUnicode(text) ⇒ <code>String</code>
Converts ASCII text used in the GurmukhiAkhar font to Unicode.

**Kind**: global function  
**Returns**: <code>String</code> - A unicode representation of the provided ascii gurmukhi string.  

| Param | Type | Description |
| --- | --- | --- |
| text | <code>String</code> | The ascii text to convert. |


* * *

## Future

-   Unicode to ASCII