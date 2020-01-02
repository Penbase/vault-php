# Vault PHP client

## About this fork

The original [vault-php](https://github.com/CSharpRU/vault-php) client was
forked to upgrade the `cache/cache` package to version 1.0.0. Since the author
of the original package is planning a 4.0.0 major upgrade removing support for
PHP versions older than 7.2.0, this fork will remain in a detached 3.6.x version.

Badges will be updated to reflect this fork state.

[![Build Status](https://travis-ci.com/bastien-boussouf/vault-php.svg?branch=master)](https://travis-ci.com/bastien-boussouf/vault-php)
[![Codacy Badge](https://api.codacy.com/project/badge/Coverage/b38fcd961fbf4a96a872679d07168087)](https://www.codacy.com/app/bastien-boussouf/vault-php?utm_source=github.com&utm_medium=referral&utm_content=bastien-boussouf/vault-php&utm_campaign=Badge_Coverage)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b38fcd961fbf4a96a872679d07168087)](https://www.codacy.com/app/bastien-boussouf/vault-php?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bastien-boussouf/vault-php&amp;utm_campaign=Badge_Grade)

The original documentation is still available at [readthedocs.org](http://vault-php.readthedocs.io).

## Features

> **Warning! This project is not production ready, however I'm using it inside a production project and it works fine.**
> **I could change versioning or break backward compatibility.**
> **Use it at your own risk.**

This is a PHP client for Vault - a tool for managing secrets.

* Supports different authentication backends with token caching and re-authentication.
* Different transports for different PHP versions.

## Installing / Getting started

Simply run this command within your directory with composer.json.

```shell
composer require csharpru/vault-php
```

## Documentation

Latest documentation is available here: http://vault-php.readthedocs.io/en/latest/

## Developing

If you want to contribute, execute following shell commands:

```shell
git clone https://github.com/CSharpRU/vault-php.git
cd vault-php/
composer install
```

Now you're ready to write tests and code.

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

Little hints for new contributors:
* This repository follows gitflow and semver.
* Please follow PSR and other good coding standards.

## Licensing

The code in this project is licensed under MIT license.
