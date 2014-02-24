# &lt;gplus-button&gt;

Web Component wrapper for [Google's +1 button](https://developers.google.com/+/web/+1button/) using Polymer.

## Demo

![GPlus Element](http://zno.io/Qvag/gplus-element.png)

> [Check it live](http://zenorocha.github.io/gplus-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/gplus-button.html">
	```

3. Start using it!

	```xml
	<gplus-button></gplus-button>
	```

## Options

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`type`       | `g-plusone`, `g-follow`               | `g-plusone`               | The type of button
`lang`    | `pt-BR`, `en-US`, `es`, [more languages](https://developers.google.com/+/web/+1button/#available-languages)              | `en-US`                            | language of component


## Options - button gplus

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`href`       | *string*                              | `http://customelement.io` | The URL to +1
`size`       | `small`, `medium`, `standard`, `tall` | `standard`          		 | Sets the +1 button size to render
`width`      | *int*                                 | `300`               		 | The width of the button
`annotation`  | `bubble`,`inline`,`none`             | `bubble`                  | Sets the annotation to display next to the button.


## Options - button follow

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`pageId`      | `URL to the Google+ page or user profile, examples: https://plus.google.com/110967630299632321627, https://plus.google.com/+LarryPage`  | `109325404047497404656`            | URL to the Google+ page or user profile
`annotation`  | `bubble`,`vertical-bubble`,`none`   | `bubble`                           | Sets the annotation to display next to the button.
`rel`         | `author or publisher`               | `string empty`                     | Describes the relationship of the entity defined at the href location to the page the badge is embedded.
`height`      | `15`,`20`,`24`                      | `20`                               | The pixel height of the button to render.


> See Google Plus' [official documentation](https://developers.google.com/+/web/+1button/).

## Browser Support

![IE](https://raw.github.com/paulirish/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/paulirish/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/paulirish/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/paulirish/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/paulirish/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/zenorocha/gplus-button/releases) list.

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha
