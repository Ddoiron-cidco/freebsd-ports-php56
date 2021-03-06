# FreeBSD PHP 5.6 ports (freebsd-ports-php56)
Patch your Ports tree for (removed) PHP5.6 support with the last available version (5.6.40).

Tested on FreeBSD 11.2 and 12.0.

## Patch your Ports tree

First, update your FreeBSD Ports tree by your favourite method (probably "portsnap fetch update"), and then:

    fetch https://raw.githubusercontent.com/simplerezo/freebsd-ports-php56/master/php56.sh
    chmod +x php56.sh
    ./php56.sh
    
Note: you need to re-run the script after every FreeBSD Ports tree update.
    
## Usage

Now you can build or upgrade individual packages:

	cd /usr/local/ports/php56/lang/php56 &&	make install
	cd /usr/local/ports/php56/www/mod_php56 && make install
