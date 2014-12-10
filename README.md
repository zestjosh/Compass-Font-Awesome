Compass-Font-Awesome
====================

Font-Awesome scss for Compass by Flagship.

1. Place _font-awesome.scss in assets/flagship/scss/partials/

2. Replace genericons with font-awesome in assets/flagship/scss/style.scss and assets/flagship/scss/editor-style.scss

3. Remove genericons in functions.php
```php
// http://themehybrid.com/docs/hybrid-core-styles
add_theme_support( 'hybrid-core-styles', array( 'style', 'google-fonts' ) );
```

4. Replace references to genericons with font-awesome in theme/includes/scripts.php
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
