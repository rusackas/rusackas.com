# Konami Code For jQuery
By [Tom McFarlin](http://tommcfarlin.com). Last Updated 11/10/2013.

## About

Using the Konami code, easily configure and Easter Egg for your page or any element on the page.

## Parameters

* `cheat` The callback function to fire once the cheat code has been entered.

## Instructions

Include the plugin in the header of your page:

```
	<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>`
	<script src="jquery.konami.js" type="text/javascript"></script>
```

Apply the plugin to the window to capture keypresses:

`$( window ).konami();`

Specify a callback to fire once the code has been entered:

```
  $( window ).konami({	
		cheat: function() {
			alert( 'Cheat code activated!' );
		}
	});
```

## Contact

* Web: [Tom McFarlin](http://tommcfarlin.com)
* Twitter: [@tommcfarlin](http://twitter.com/tommcfarlin/)

## License

[MIT license](http://www.opensource.org/licenses/mit-license.php)