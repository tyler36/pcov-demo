# PHP Coverage <!-- omit in toc -->

- [Overview](#overview)
- [PHP 8.0](#php-80)
- [PHP 8.1](#php-81)

## Overview

## PHP 8.0

Update the project's `.ddev/config.yaml`;

```yml
php_version: "8.0"
...
webimage_extra_packages: ['php8.0-pcov']
```

Run the following in your shell:

```shell
ddev phpunit --coverage-html coverage
...
Generating code coverage report in HTML format ... done [00:00.073]
```

## PHP 8.1

Update the project's `.ddev/config.yaml`;

```yml
php_version: "8.1"
...
webimage_extra_packages: ['php8.1-pcov']
```

Run the following in your shell:

```shell
ddev phpunit --coverage-html coverage
...
Generating code coverage report in HTML format ... done [00:00.073]
```
