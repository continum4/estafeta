# estafeta

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

Librería PHP para rastrear o cotizar un envío por Estafeta.

## Install

Via Composer

``` bash
$ composer require continum4/estafeta
```

## Usage

``` php
$guia = new continum4\estafeta();
echo $guia->cotizar('1234567890');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Security

If you discover any security related issues, please email continum4.dev@gmail.com instead of using the issue tracker.

## Credits

- [continum4][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/continum4/estafeta.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/continum4/estafeta/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/continum4/estafeta.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/continum4/estafeta.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/continum4/estafeta.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/continum4/estafeta
[link-travis]: https://travis-ci.org/continum4/estafeta
[link-scrutinizer]: https://scrutinizer-ci.com/g/continum4/estafeta/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/continum4/estafeta
[link-downloads]: https://packagist.org/packages/continum4/estafeta
[link-author]: https://github.com/continum4
[link-contributors]: ../../contributors
