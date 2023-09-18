# Revealjs-text-resizer Extension For Quarto

A small extension that makes it easy to adjust the size of your fonts on Quarto-based Reveal.js slides, without having to disable Reveal.js's built-in slide scaling features.

This extension is for anyone who has presented with Quarto slides and tried to press <kbd>Ctrl/Cmd</kbd> + <kbd>+/-</kbd> to adjust the font size to find the text stubbornly stays exactly the same size.

## Installing

```bash
quarto add gadenbuie/revealjs-text-resizer
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

The extension adds three keyboard shortcuts to your slides:

* Press <kbd>Alt/Opt</kbd> + <kbd>+</kbd> to increase text size

* Press <kbd>Alt/Opt</kbd> + <kbd>-</kbd> to decrease text size

* Press <kbd>Alt/Opt</kbd> + <kbd>0</kbd> to reset the text size

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

