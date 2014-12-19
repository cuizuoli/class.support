# class.support

Javascript class support

## Getting Started
### In the browser
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/cuizuoli/class.support/master/dist/class.support.min.js
[max]: https://raw.github.com/cuizuoli/class.support/master/dist/class.support.js

In your web page:

```html
<script src="dist/class.support.min.js"></script>
<script>
Class('cn.cuizuoli.ClassSupportTest', {
	init: function(options) {
		var _this = this;
		_this._options = $.extend({
			id: 'body'
		}, options);
		_this._root = $(_this._options.id);
		_this._bindEvent();
		//TODO init.
	},
	_bindEvent: function() {
		var _this = this;
		// TODO binding event.
	}
});
new cn.cuizuoli.ClassSupportTest();
</script>
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

_Also, please don't edit files in the "dist" subdirectory as they are generated via Grunt. You'll find source code in the "src" subdirectory!_

## Release History
_(Nothing yet)_

## License
Copyright (c) 2014 cuizuoli  
Licensed under the MIT license.
