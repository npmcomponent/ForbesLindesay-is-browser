*This repository is a mirror of the [component](http://component.io) module [forbeslindesay/is-browser](http://github.com/forbeslindesay/is-browser). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/forbeslindesay-is-browser`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
<img src="http://i.imgur.com/T9MsYS0.png" align="right"/>
# is-browser

  Test whether you're a component in browser or a package in npm

## Installation

  client:

    $ component install ForbesLindesay/is-browser

  server:

    $ npm install is-browser

## API

  This simply exports `true` or `false`:

```javascript
if (require('is-browser')) {
  console.log('The module was installed using component');
} else {
  console.log('The module was installed using npm');
}
```

## License

  MIT
