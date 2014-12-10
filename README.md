Compass-Font-Awesome
====================

Font-Awesome scss for Compass by Flagship.

* Place _font-awesome.scss in assets/flagship/scss/partials/

* Replace genericons with font-awesome in assets/flagship/scss/style.scss and assets/flagship/scss/editor-style.scss

* Remove genericons in theme/functions.php
```php
// http://themehybrid.com/docs/hybrid-core-styles
add_theme_support( 'hybrid-core-styles', array( 'style', 'google-fonts' ) );
```

* Replace references to genericons with font-awesome in theme/includes/scripts.php
```php
  $editor_styles = array(
		'//fonts.googleapis.com/css?family=Open+Sans',
		'css/font-awesome.css',
		'css/editor-style.css',
	);
```
```
  wp_register_style(
		'font-awesome',
		'//netdna.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css',
		array(),
		'4.2.0'
	);
```
