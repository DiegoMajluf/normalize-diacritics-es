Adaptation of normalize-diacritics for es2016 usage.


## Install

```
$ npm install --save normalize-diacritics-es
```

## Usage

Brief example to show how to use:

```js
const  normalize = require('normalize-diacritics-es').normalize;
//import { normalize } from 'normalize-diacritics-es'

/* To normalize string */
const str = 'söme stüff with áccènts';
normalize(str); // some stuff with accents
```