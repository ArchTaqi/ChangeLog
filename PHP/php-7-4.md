# PHP 7.4 – Features, Deprecations, and Updates


## New Features

PHP Core – 

- Support for Typed Properties
- Support for Arrow Functions
- Limited Covariant Returns and Contravariant Parameters
- Support for Null coalescing assign (??=) operator
- Support for WeakReferences
- Preloading
- Spread Operator in Array Expression


## Deprecations



- Nested ternary operators without explicit parentheses.
- Array and string offset access using curly braces.
- (real) cast and [is_real()](https://www.php.net/manual/en/function.is-real.php) function.
- Unbinding $this when $this is used.
- parent keyword without parent class.
- allow_url_include INI option.
- Invalid characters in base conversion functions.
- Using [array_key_exists()](https://www.php.net/manual/en/function.array-key-exists.php) on objects.
- Magic quotes legacy
- FILTER_SANITIZE_MAGIC_QUOTES filter
- Reflection export() methods
- mb_strrpos() with encoding as 3rd argument
- implode() parameter order mix
- Unbinding $this from non-static closures
- hebrevc() function
- convert_cyr_string() function
- money_format() function
- ezmlm_hash() function
- restore_include_path() function


[More in Detail](https://wiki.php.net/rfc/deprecations_php_7_4)



