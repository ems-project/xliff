# PHP Helpers
enclose and simplify regular PHP functions in PHPStan compliant functions

Coding standards
----------------
PHP Code Sniffer is available via composer, the standard used is defined in phpcs.xml.diff:
````bash
composer phpcs
````

Unit tests:
````bash
composer phpunit
````

PHPStan is configured at level 3, you can check for errors locally using:
`````bash
composer phpstan
`````

If you want to regenerate a PHPStan baseline run this command:
```
vendor/bin/phpstan analyse --generate-baseline
```
