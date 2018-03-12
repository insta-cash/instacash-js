InstaCash-JS Library
=======

[![NPM Package](https://img.shields.io/npm/v/bitcore-lib-dash.svg?style=flat-square)](https://www.npmjs.org/package/bitcore-lib-dash)
[![Build Status](https://img.shields.io/travis/dashpay/bitcore-lib-dash.svg?branch=master&style=flat-square)](https://travis-ci.org/dashpay/bitcore-lib-dash)
[![Coverage Status](https://img.shields.io/coveralls/dashpay/bitcore-lib-dash.svg?style=flat-square)](https://coveralls.io/github/dashpay/bitcore-lib-dash?branch=master)

A pure and powerful JavaScript Instacash protocol intergration library.
This was made possible with the help of bitcore.

## Principles

Instacash is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Instacash network allows for highly resilient Instacash infrastructure.

## Get Started

```
npm install instacash-js
```

```
bower install instacash-js
```

## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)


## Examples

* [Generate a random address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Dash message](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Dash message](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Building the Browser Bundle

To build a instacash-js full bundle for the browser:

```sh
gulp browser
```

This will generate files named `instacash-js.js` and `instacash-js.min.js`.

## Development & Tests

```sh
git clone https://github.com/insta-cash/instacash-js.git
cd bitcore-lib-dash
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/dashpay/bitcore-lib-dash/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
Copyright 2016 The Dash Foundation, Inc.
Copyright 2018 InstaCash CORE Team.
