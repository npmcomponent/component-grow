*This repository is a mirror of the [component](http://component.io) module [component/grow](http://github.com/component/grow). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-grow`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# Grow

  Grow textareas as the user types.

## Installation

```
$ npm install grow-component
```

## API

### grow(el, [options])

```js
var el = document.querySelector('textarea');
var grow = require('grow');
grow(el, { max: 5 });
```

## Options

  - `max` (number) maximum rows

## License

  MIT