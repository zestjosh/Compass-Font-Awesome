Compass-Font-Awesome
====================

Font-Awesome scss for Compass by Flagship.

1. Place _font-awesome.scss in assets/flagship/scss/partials/

2. Replace genericons with font-awesome in assets/flagship/scss/style.scss

3. Remove genericons and add font-awesome in functions.php
```php
// http://themehybrid.com/docs/hybrid-core-styles
add_theme_support( 'hybrid-core-styles', array( 'style', 'google-fonts' ) );

// Removed genericons, add font-awesome
wp_enqueue_style( 'prefix-font-awesome', '//netdna.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css', array(), '4.2.0' );
```