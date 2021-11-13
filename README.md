# Password-Generator
## Purpose
Needed a way to create passphrases programatically.

## Examples

- Generates one passphrase with default values:
    ```python
    >>> new_passphrase()
    'body-strut-plow-tray'
    ```
- Generates four passphrases:
    ```python
    >>> new_passphrase(num=4)
    ['blast-elm-bath-treat', 'hut-pulse-agile-perch', 'glide-trash-alien-cache', 'frail-lemon-lip-turf']
    ```
- Generates one passphrase with 10 words:
    ```python
    >>> new_passphrase(words=10)
    'spout-palm-hull-frost-zero-mash-pogo-gong-slice-chomp'
    ```
- Generates one passphrase with custom separator:
    ```python
    >>> new_passphrase(seperator='%%%')
    'duty%%%rush%%%punk%%%glad'
    ```
