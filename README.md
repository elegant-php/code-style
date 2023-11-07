# PHP coding style guide

This rules extends the [PSR-1](https://www.php-fig.org/psr/psr-1/) and the [PSR-12](https://www.php-fig.org/psr/psr-12/).

## General

1. Use strict types
2. Set line length to **120** characters
3. Follow [Mozilla coding style](https://docs.telemetry.mozilla.org/concepts/sql_style) for SQL
4. Always remove `use` lines with unused classes
5. Always import classes or their family at the top of the script, under the namespace
6. Use `sprintf` instead of concatenation
7. Try to avoid `else` operator
8. The ternary operator must be on the same line, **or** `:` and `?` must start on a new line, offset by 1 tab

Follow these rules from [symfony coding standarts](https://symfony.com/doc/current/contributing/code/standards.html#structure):

- Place unary operators (`!`, `--`, `...`) adjacent to the affected variable
- Always use identical comparison unless you need type juggling
- Use parentheses when instantiating classes regardless of the number of arguments the constructor has
- Do not use else, elseif, break after if and case conditions which return or throw something

## DocBlock

These rules extends [Laravel DocBlock style guide](https://laravel.com/docs/master/contributions#phpdoc):

1. Always add a [DocBlock](https://docs.phpdoc.org/guide/getting-started/what-is-a-docblock.html) for methods and keep it up to date
2. DocBlock must contain all exceptions

## Spaces

1. Add blank lines around the `use` block of lines

Follow these rules modified based on [symfony coding standarts](https://symfony.com/doc/current/contributing/code/standards.html#structure):

- Add a single space after each comma delimiter
- Add a single space around binary operators (`==`, `&&`, `...`)
- Add a comma after each array item in a multi-line array, even after the last one
- Add a blank line before return statements, unless the return is alone inside a statement-group (like an `if` statement)
- Use braces to indicate control structure body regardless of the number of statements it contains
- Declare class properties before methods
- Declare public methods first, then protected ones and finally private ones
