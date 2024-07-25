# Webaune Support

**Common** support helpers, contracts, and traits required by various Webaune packages. Validator functionality, and basic controller included out-of-the-box.

> **Note:** this package is just a support package for other Webaune packages, which may not be useful on it's own, but contains some complementary generic functionality and also may not respect SemVer and break backward compatibility.


## Installation

Install via `composer require webaune/laravel-support`


## Usage

### `mimetypes()` helper

The `mimetypes` method gets valid mime types:
```php
$mimetypes = mimetypes();
```

### `timezones()` helper

The `timezones` method gets valid timezones:
```php
$timezones = timezones();
```

### unique_with Validator Rule

This feature contains a variant of the `validateUnique` rule for Laravel, that allows for validation of multi-column UNIQUE indexes.

It was forked and merged from the awesome [felixkiss/uniquewith-validator](https://github.com/felixkiss/uniquewith-validator) package, which at the time been outdated and un-maintained for a long time. Many thanks to core contributors for developing this.


## Changelog

Refer to the [Changelog](CHANGELOG.md) for a full history of the project.


## Support

The following support channels are available at your fingertips:


## Contributing & Protocols

Thank you for considering contributing to this project! The contribution guide can be found in [CONTRIBUTING.md](CONTRIBUTING.md).

Bug reports, feature requests, and pull requests are very welcome.

- [Versioning](CONTRIBUTING.md#versioning)
- [Pull Requests](CONTRIBUTING.md#pull-requests)
- [Coding Standards](CONTRIBUTING.md#coding-standards)
- [Feature Requests](CONTRIBUTING.md#feature-requests)
- [Git Flow](CONTRIBUTING.md#git-flow)


## Security Vulnerabilities

If you discover a security vulnerability within this project, please send an e-mail to [razeek@webaune.com](razeek@webaune.com). All security vulnerabilities will be promptly addressed.


## About Webaune

Webaune is a software solutions startup, specialized in integrated enterprise solutions for SMEs established in Alexandria, Egypt since June 2016. We believe that our drive The Value, The Reach, and The Impact is what differentiates us and unleash the endless possibilities of our philosophy through the power of software. We like to call it Innovation At The Speed Of Life. That’s how we do our share of advancing humanity.


## License

This software is released under [The MIT License (MIT)](LICENSE).

(c) 2016-2022 Webaune LLC, Some rights reserved.
