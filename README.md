# API for Voices.az


[![Latest Version](https://img.shields.io/github/release/almazovelnar/voices-api.svg?style=flat-square)](https://github.com/almazovelnar/voices-api/releases)

----------

## Installation

- [Voices.az API on Packagist](https://packagist.org/packages/almazovelnar/voices-api)
- [Voices.az API on GitHub](https://github.com/almazovelnar/voices-api)

From the command line run

```
$ composer require voices-az/api
```

Once VoicesAPI is installed you need initialize with API Key. Sign up or login for go to cabinet on [Voices.az](https://app.voices.az/profile) and get API Key for authentication.

```php
VoicesAi::initialize("{api_key}");
```

For setting locale (Azerbaijani - az, English - en, Russian - ru)

```php
VoicesAi::setLocale("{language_key}");
```