Stopwords Russian (RU)
=======

[![Build Status](https://travis-ci.org/stopwords-iso/stopwords-ru.svg?branch=master)](https://travis-ci.org/stopwords-iso/stopwords-ru)

The most comprehensive collection of stopwords for the russian language.

A [multiple language](https://github.com/stopwords-iso/stopwords-iso) collection is also available.

### Usage

The collection comes in a
[JSON format](https://raw.githubusercontent.com/stopwords-iso/stopwords-ru/master/stopwords-ru.json) and a
[text format](https://raw.githubusercontent.com/stopwords-iso/stopwords-ru/master/stopwords-ru.txt).
You are free to use this collection any way you like.
It is only currently published on [npm](https://www.npmjs.com/stopwords-ru) and [bower](https://bower.io).

```sh
$ npm install stopwords-ru
```

```sh
$ bower install stopwords-ru
```

```js
// Node
const stopwords = require('stopwords-ru'); // array of stopwords
```

### Contributing

If you wish to remove or update some of the stopwords, please file an issue first before sending a PR on the repo of the specific language.

If you would like to add a stopword or a new set of stopwords, please add them as a new text file insie the `raw` directory then send a PR.

Please send a separate PR on the [main repo](https://github.com/stopwords-iso/stopwords-iso) to credit the source of the added stopwords.

### Credits

All stopwords sources are [listed on the main repo](https://github.com/stopwords-iso/stopwords-iso/blob/master/CREDITS.md).
