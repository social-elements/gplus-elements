# &lt;gplus&gt;

Web Component wrapper for [Google's +1 button](https://developers.google.com/+/web/+1button/) using Polymer.

> Maintained by [Zeno Rocha](https://github.com/zenorocha).

## Demo

![GPlus Element](http://zno.io/Qvag/gplus-element.png)

> [Check it live](http://zenorocha.github.io/gplus-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/gplus.html">
	```

3. Start using it!

	```html
	<gplus></gplus>
	```

## Options

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`annotation` | `inline`, `bubble`, `none`            | `inline`            		 | Sets the annotation to display next to the button
`href`       | *string*                              | `http://customelement.io` | The URL to +1
`size`       | `small`, `medium`, `standard`, `tall` | `standard`          		 | Sets the +1 button size to render
`height`     | *int*                                 | `25`               		 | The height of the button
`width`      | *int*                                 | `300`               		 | The width of the button

> See Google Plus' [official documentation](https://developers.google.com/+/web/+1button/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.1](https://github.com/zenorocha/gplus-element/releases/tag/0.1.1) September 3, 2013
	* Use Polymer from CDN and update it to v0.0.20130816
* [v0.1.0](https://github.com/zenorocha/gplus-element/releases/tag/0.1.0) August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)