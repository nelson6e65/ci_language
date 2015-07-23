# CodeIgniter translations
[![English (Source lang)](https://img.shields.io/badge/lang-en-green.svg)](https://www.transifex.com/projects/p/ci_translations/language/en/)
[![Spanish translation](https://img.shields.io/badge/lang-es-green.svg)](https://www.transifex.com/projects/p/ci_translations/language/es/)
[![CodeIgniter version](https://img.shields.io/badge/ci-v2.2.3-yellow.svg)](https://github.com/bcit-ci/CodeIgniter)
[![Transifex](https://img.shields.io/badge/translate-Transifex-blue.svg)](https://www.transifex.com/projects/p/ci_translations)


## Description
Language translations for CodeIgniter 2, powered by [Transifex](https://www.transifex.com/projects/p/ci_translations/) Platform.


## Requirements
- CodeIgniter 2


## Install
- Download the latest [release](https://github.com/nelson6e65/ci_language/releases).
- Unzip that download.
- Rename the resulting folder to `language`.
- Then move this folder into your `application` directory (replace files in `application/language/` as needed on update).


## Usage
You just need to set your language in `application/config/config.php`.

This translations uses [ISO 639-1 code namming standard](http://www.loc.gov/standards/iso639-2/php/code_list.php) for languages. So, for example, you must to use `'es'` instead of `'spanish'`:

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
You can help with translations by *requesting* a new language (or ask for joining to) at https://www.transifex.com/projects/p/ci_translations/

> Note: You will need a Transifex account (free).
