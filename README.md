# CodeIgniter translations
[![CodeIgniter version](https://img.shields.io/badge/ci-v2.2.3-yellow.svg)](https://github.com/bcit-ci/CodeIgniter)
[![Transifex](https://img.shields.io/badge/translate-Transifex-blue.svg)](https://www.transifex.com/projects/p/ci_translations)

Use translations for your CodeIgniter applications using [ISO 639-1 code name](http://www.loc.gov/standards/iso639-2/php/code_list.php).

## Description
Language translations for CodeIgniter 2.2.x, using [Transifex](https://www.transifex.com/projects/p/ci_translations/) Platform.

> Note: Empty translations for now.

## Requirements
- CodeIgniter 2

## Install
- Download the latest [release](https://github.com/nelson6e65/ci_language/releases).
- Unzip that download.
- Rename the resulting folder to `language`.
- Then move this folder into your `application` directory (replace files in `application/language` as needed on update).

## Usage
You just need to set your language in `application/config/config.php`.

Example: If you want to use Spanish language, you should set `$config['language']` to `es`.

```php
<?php

# . . .

/*
|--------------------------------------------------------------------------
| Default Language
|--------------------------------------------------------------------------
|
| This determines which set of language files should be used. Make sure
| there is an available translation if you intend to use something other
| than english.
|
*/
$config['language']	= 'es';

# . . .

```


## Contribute
You can help with translations by requesting a new language (or ask for joining to) at https://www.transifex.com/projects/p/ci_translations/

> Note: You will need a Transifex account (free).


### Available languages

- [x] **en** - English (*English*)
- [x] **es** - Spanish (*Español*)
- [ ] [*Other*](https://www.transifex.com/projects/p/ci_translations/)

