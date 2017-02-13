# QaTools
Yet another meta-package for installing PHP Quality Assurance Tools.

This one provides a collection of very known tools from PHP 5.3 to PHP 7.1 :

* [phpunit/phpunit](https://phpunit.de/),
* [squizlabs/php_codesniffer](https://github.com/squizlabs/PHP_CodeSniffer),
* [phpmd/phpmd](https://phpmd.org/),
* [theseer/phpdox](http://phpdox.de/),
* [sebastian/phpcpd](https://github.com/sebastianbergmann/phpcpd),
* [phpbench/phpbench](http://phpbench.readthedocs.io/en/latest/),
* [phing/phing](https://www.phing.info/),
* [phploc/phploc](https://github.com/sebastianbergmann/phploc),
* [friendsofphp/php-cs-fixer](http://cs.sensiolabs.org/),
* [sensiolabs/security-checker](https://security.sensiolabs.org/)

[![Build Status](https://travis-ci.org/JamesRezo/QaTools.svg?branch=5.3)](https://travis-ci.org/JamesRezo/QaTools)
[![Latest Stable Version](https://poser.pugx.org/jamesrezo/qatools/v/stable)](https://packagist.org/packages/jamesrezo/qatools)
[![Latest Unstable Version](https://poser.pugx.org/jamesrezo/qatools/v/unstable)](https://packagist.org/packages/jamesrezo/qatools)
[![License](https://poser.pugx.org/jamesrezo/qatools/license)](https://packagist.org/packages/jamesrezo/qatools)
[![composer.lock](https://poser.pugx.org/jamesrezo/qatools/composerlock)](https://packagist.org/packages/jamesrezo/qatools)
[![Dependency Status](https://www.versioneye.com/user/projects/57e6452e79806f002f4ab81c/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57e6452e79806f002f4ab81c)

## Installation & Usage

In your project :
```
composer require --dev jamesrezo/qatools
```

Then all tools will be available under `vendor/bin/` directory path.

Or globally :
```
composer global require jamesrezo/qatools
```

```
export PATH=~/.composer/vendor/bin:$PATH
```

## Contributing

Everyone is welcome :-)

## Licence

MIT
