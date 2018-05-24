---
layout: project
version: 1.x
title: About
description: About this library
lib: 
    name: opis/string
    version: 1.4.0
---
# Manipulate multi-byte strings

This tiny library allows you to manipulate multi-byte encoded strings, 
using an object-oriented paradigm. The library has no dependencies to *mbstring* 
or similar PHP extensions and is compatible with PHP 5.3+, PHP 7.0 and HHVM.

## License

**Opis String** is licensed under [Apache License, Version 2.0][apache_license].

## Requirements

* PHP 5.3 or higher

## Installation

**Opis String** is available on [Packagist] and it can be installed from a 
command line interface by using [Composer]. 

```bash
composer require {{page.lib.name}}
```

Or you could directly reference it into your `composer.json` file as a dependency

```json
{
    "require": {
        "{{page.lib.name}}": "^{{page.lib.version}}"
    }
}
```


[apache_license]: http://www.apache.org/licenses/LICENSE-2.0 "Project license" 
{:rel="nofollow" target="_blank"}
[Packagist]: https://packagist.org/packages/{{page.lib.name}} "Packagist" 
{:rel="nofollow" target="_blank"}
[Composer]: http://getcomposer.org "Composer" 
{:ref="nofollow" target="_blank"}