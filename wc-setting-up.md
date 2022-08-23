## Step One: WordPress Environment Variable

[WP_ENVIRONMENT_TYPE](https://developer.wordpress.org/apis/wp-config-php/)

[Setting the environment type](https://make.wordpress.org/core/2020/07/24/new-wp_get_environment_type-function-in-wordpress-5-5/)

By default, this function will return production. Other values supported are local, development and staging.

What are environment variables?

- An environment variable is a variable whose value is set outside the program, typically through functionality built into the operating system or microservice. An environment variable is made up of a name/value pair, and any number may be created and available for reference at a point in time.

```
{
  define( 'WP_ENVIRONMENT_TYPE', 'development' );
  define( 'SCRIPT_DEBUG', true );
}

```

## Step Two: Plug Ins

Inside the wp-config.php file of the site.

[Query Monitor](https://wordpress.org/plugins/query-monitor/)
[Debug Bar Console](https://wordpress.org/plugins/debug-bar-console/)

Plug-ins to set up to download:
Debug Bar Console - Adds a PHP/MySQL console to the debug bar.
Query Monitor - Developer tools panel for WordPress.

## Step Three: Configuring WooCommerce Settings

[WooCommerce Settings](https://woocommerce.com/document/configuring-woocommerce-settings/)

## WooCommerce Examples

[10 Best WordPress eCommerce Themes for 2021](https://www.sitepoint.com/top-wordpress-ecommerce-themes/)
