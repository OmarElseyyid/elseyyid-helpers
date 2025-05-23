# Elseyyid Helpers

A personal collection of clean, efficient PHP utility classes and functions 

— designed to streamline your development workflow with runtime type checks, test utilities, and strict code quality tools.

## Features
- Interface implementation checks at runtime
- Clean PSR-4 autoloaded structure
- Pest & PHPUnit compatible test suite
- PHPStan static analysis ready
- Code style enforcement via PHP CS Fixer

## Installation
```bash
composer require omarelsayyid/omar-helpers
```
**Requires PHP 8.1+**

## Usage Example
Check if a class implements an interface:
```php
  use OmarElseyyid\\Helpers\\ClassImplements;

  if (ClassImplements::check(SomeClass::class, SomeInterface::class)) {
    // Class implements interface, proceed accordingly
  }
```
  
## Development
Run test suite:
```bash
vendor/bin/pest
```
Run static analysis:
```bash
vendor/bin/phpstan analyse src
```
Fix code style:
```bash
vendor/bin/php-cs-fixer fix
```

## Contributing
Pull requests are welcome. Fork the repository, push your feature branch, and submit a PR.

## License
MIT License — see the LICENSE file.

## Maintainer
- Omar El Seyyid – mhmoud.omar3@gmail.com
- GitHub Profile: [https://github.com/OmarElseyyid](https://github.com/OmarElseyyid)
