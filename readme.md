# LinQ for TypeScript
eddede
[![Build](https://img.shields.io/travis/kutyel/linq.ts/master.svg?style=flat-square)](https://travis-ci.org/kutyel/linq.ts)
[![Dependencies](https://img.shields.io/david/kutyel/linq.ts.svg?style=flat-square)](https://david-dm.org/kutyel/linq.ts)
[![Dev Dependencies](https://img.shields.io/david/dev/kutyel/linq.ts.svg?style=flat-square)](https://david-dm.org/kutyel/linq.ts#info=devDependencies)
[![Downloads](https://img.shields.io/npm/dm/linqts.svg?style=flat-square)](https://npmjs.com/packages/linqts)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/flaviocorpa)

[![linqts](https://raw.githubusercontent.com/kutyel/linq/master/assets/linqts.png)](http://www.typescriptlang.org)

## Install

```
npm install linqts
```

## Usage

```ts
import {List} from './linq.ts';

let arr = new List<number>([1,2,3,4,5])
    .Where(x => x > 3)
    .Select(y => y * 2)
    .ToArray(); // => [8, 10]
```

## Sample

![linqts.gif](https://raw.githubusercontent.com/kutyel/linq/master/assets/linqts.gif)

## Tests

```
npm test
```

Powered by [AVA](https://github.com/sindresorhus/ava)

## License

MIT © [Flavio Corpa](http://flaviocorpa.com)
