# Aura.Payload

A Domain Payload implementation.

## Installation and Autoloading

This package is installable and PSR-4 autoloadable via Composer as
[aura/payload][].

Alternatively, [download a release][], or clone this repository, then map the
`Aura\Payload\` namespace to the package `src/` directory.

## Dependencies

This package requires PHP 5.5 or later; it has been tested on PHP 5.6, PHP 7,
and HHVM. We recommend using the latest available version of PHP as a matter of
principle.

Aura library packages may sometimes depend on external interfaces, but never on
external implementations. This allows compliance with community standards
without compromising flexibility. For specifics, please examine the package
[composer.json][] file.

## Quality

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/auraphp/Aura.Payload/badges/quality-score.png?b=3.x)](https://scrutinizer-ci.com/g/auraphp/Aura.Payload/)
[![Code Coverage](https://scrutinizer-ci.com/g/auraphp/Aura.Payload/badges/coverage.png?b=3.x)](https://scrutinizer-ci.com/g/auraphp/Aura.Payload/)
[![Build Status](https://travis-ci.org/auraphp/Aura.Payload.png?branch=3.x)](https://travis-ci.org/auraphp/Aura.Payload)

This project adheres to [Semantic Versioning](http://semver.org/).

To run the unit tests at the command line, issue `composer install` and then
`phpunit` at the package root. This requires [Composer][] to be available as
`composer`, and [PHPUnit][] to be available as `phpunit`.

This package attempts to comply with [PSR-1][], [PSR-2][], and [PSR-4][]. If
you notice compliance oversights, please send a patch via pull request.

## Community

To ask questions, provide feedback, or otherwise communicate with other Aura
users, please join our [Google Group][], follow [@auraphp][], or chat with us
on Freenode in the #auraphp channel.

## Documentation

This package is fully documented [here](./docs/index.md).

[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[PSR-2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[PSR-4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
[Composer]: http://getcomposer.org/
[PHPUnit]: http://phpunit.de/
[Google Group]: http://groups.google.com/group/auraphp
[@auraphp]: http://twitter.com/auraphp
[download a release]: https://github.com/auraphp/Aura.Payload/releases
[aura/payload]: https://packagist.org/packages/aura/payload
[composer.json]: ./composer.json
