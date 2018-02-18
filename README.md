# WordPress Boilerplate

An opinionated WordPress boilerplate, including [Advanced Custom Fields Pro](https://www.advancedcustomfields.com/pro/) and [Timber](https://upstatement.com/timber/), and using [phpdotenv](https://github.com/vlucas/phpdotenv).


## Dependencies

* [Composer](https://getcomposer.org/download/).
* [WP-CLI](http://wp-cli.org/).
* [WP-CLI Dotenv Command](https://github.com/aaemnnosttv/wp-cli-dotenv-command).


### Usage
* From the project root, run `composer install` to get dependencies, including WordPress itself.
* Run `$ wp dotenv init --template=.env.example --interactive --with-salts` to add your credentials and generate new keys and salts.
* Install WordPress as usual.

Full details on this approach to WordPress can be found at [short.is/wordpress-and-composer](https://short.is/wordpress-and-composer).
