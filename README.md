# Java implementation of Lox language interpreter

Created following Robert Nystrom's awesome book [Crafting interpreters](https://craftinginterpreters.com/).

Additionally, I added support for `break` statement and multiline comments signified with delimiters `/*` and `*/`, changed truthiness behavior for a more JavaScript-inspired one: `nil`, number literals equal to 0, and string literals with length equal to 0 (declared with `""`) are all evaluating to false.

Project uses Java SDK 11.0.13
