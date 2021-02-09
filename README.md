# php-data-structures

Common data structures written in PHP 8

## Usage

Put dcli `docker-compose cli` alias in your profile shell file

> alias dcli="docker-compose -f docker-compose.cli.yml run --rm"

## Commands

```bash
# Run static analysis
dcli composer phpstan

# Check PHP Syntax
dcli composer lint:check

# Fix bad PHP Syntax
dcli composer lint

# Run unit tests
dcli composer phpunit

# Run all checks
dcli composer test

# Run php file
dcli php src/dir/file.php
```
