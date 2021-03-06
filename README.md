# CodeIgniter Framework translations
[![CodeIgniter version](https://img.shields.io/badge/ci-v2.2.3-yellow.svg)](https://github.com/bcit-ci/CodeIgniter)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Transifex](https://img.shields.io/badge/powered-Transifex-blue.svg)](https://www.transifex.com/projects/p/ci_translations)
[![English (Source lang)](https://img.shields.io/badge/en-100%-green.svg)](https://www.transifex.com/projects/p/ci_translations/language/en/)
[![Spanish (es) translation](https://img.shields.io/badge/es-51%-green.svg)](https://www.transifex.com/projects/p/ci_translations/language/es/)
[![Italian (it) translation](https://img.shields.io/badge/it-0%-red.svg)](https://www.transifex.com/projects/p/ci_translations/language/it/)
[![Portuguese (Brazil) (pt_BR) translation](https://img.shields.io/badge/pt_BR-0%-red.svg)](https://www.transifex.com/projects/p/ci_translations/language/pt_BR/)


## Description
Language translations for CodeIgniter Framework 2, powered by [Transifex](https://www.transifex.com/projects/p/ci_translations/) Platform.


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
