# pecl/propro

## About:

The "Property Proxy" extension provides a fairly transparent proxy for internal object properties hidden in custom non-zval implementations.

See the php\PropertyProxy class, for the user-land visible part of the implementation.

## Installation:

This extension is hosted at [PECL](http://pecl.php.net) and can be installed with [PEAR](http://pear.php.net)'s pecl command:

    # pecl install propro

### PHARext

Watch out for [PECL replicates](https://replicator.pharext.org?propro)
and pharext packages attached to [releases](https://github.com/m6w6/ext-propro/releases).

### Checkout

	git clone github.com:m6w6/ext-propro
	cd ext-propro
	/path/to/phpize
	./configure --with-php-config=/path/to/php-config
	make
	sudo make install

## Internals:

> ***NOTE:***
  This extension mostly only provides infrastructure for other extensions.
  See the [API docs here](http://m6w6.github.io/ext-propro/master/).
