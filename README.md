*This repository is a mirror of the [component](http://component.io) module [stagas/tabify](http://github.com/stagas/tabify). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-tabify`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# tabify

convert a list to tabs

## Install

`component-install stagas/tabify`

## Usage

```js
var tabify = require('tabify')

var tabs = tabify(document.getElementById('tabs'))
tabs.on('change', function (targetId, target) {
  console.log(targetId, target)
})
```

## License

MIT
