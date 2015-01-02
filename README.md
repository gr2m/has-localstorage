# has-localstorage

> returns true if localStorage is supported _and_ persistent

returns `true` or `false` depending on whether localStorage is supported or not.
Beware that some browsers like Safari do not support localStorage in private mode.


## Downlaod or Installation

- Download [has-localstorage.js](https://raw.githubusercontent.com/gr2m/initials.js/master/lib/has-localstorage.js)
- or: install via Bower: `bower install --save has-localstorage`
- or: install via npm: `npm install --save has-localstorage`


## Usage

```js
if (hasLocalStorage()) {
  // localStorage can be used, all data gets persisted
} else {
  // localStorage is not available, or changes are not persisted
}
```


# Acknowledgement

`hasLocalStorage()` has been inspired by this [Cappuccino](http://www.cappuccino-project.org/) commit:
https://github.com/cappuccino/cappuccino/commit/063b05d9643c35b303568a28809e4eb3224f71ec

## License

MIT
