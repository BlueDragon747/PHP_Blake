8 round Blake-256 for PHP

http://www.sinfocol.org/2011/01/blake-hash-extension-for-php/

phpize
./configure
make


test with
php -r "echo blake('123', BLAKE_256) . PHP_EOL;"
