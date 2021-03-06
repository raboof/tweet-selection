# tweet-selection

<p align="center">
  <br>
  <img src="http://g.recordit.co/N2fdZHEWsk.gif" alt="tweet-selection">
  <br>
</p>

![Last version](https://img.shields.io/github/tag/Kikobeats/tweet-selection.svg?style=flat-square)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/tweet-selection.svg?style=flat-square)](https://david-dm.org/Kikobeats/tweet-selection#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/tweet-selection.svg?style=flat-square)](https://www.npmjs.org/package/tweet-selection)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/Kikobeats)

> Tweet selected text. Like Medium but out of the box.

## Install

```bash
npm install tweet-selection --save
```

or

```bash
bower install tweet-selection --save
```

## Usage

**Note:** You need to use a DOM Selector.

API and default values are:

```js
$('body').tweetSelection({
  height: 300,
  width: 600,
  minimumTextSelected: 3,
  shareClass: '.tweet-selection'
  ellipsis: '…',
  quoteLeft: '“',
  quoteRight: '”'
})
```

Also support the rest of the query optional parameters for [Tweet Web intent](https://dev.twitter.com/web/tweet-button/web-intent).

## License

MIT © [Kiko Beats](http://kikobeats.com)
