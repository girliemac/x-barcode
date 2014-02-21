# &lt;x-barcode&gt;

Web Component wrapper for UPC-A (for now) barcode using Polymer.

> Maintained by [Tomomi Imura](https://github.com/girliemac).

## Demo

> [Check it live](http://girliemac.github.io/x-barcode).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/x-barcode.html">
	```

3. Start using it!

	```html
	<x-barcodet></x-barcode>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`code`      | *int*                  | `00000000000`               | The first 11 disit of UPC-A code. The last digit (check sum) will be calculated).
`color`      | *string* 	   | `black`               | Color name or hex


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 Feb 19, 2014
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)

## Yay, it works!

![scanning the barcode](https://lh4.googleusercontent.com/-cUBi64JvpGA/UwWk1J2iDCI/AAAAAAAAKH4/1d01QeASmls/w433-h770/14+-+1)