# Monokai Dark

A dark theme with monokai syntax highlight and dimmed operators.

![Showcase](/colors.png)

## Features

The most notable difference from other themes is that operators such as `+-&,;` etc. are dimmed
to the point where you can focus on keywords, storage types and identifiers. Parentheses, brackets
and braces are still white.

The only officially supported language as of now is Rust. Any other language will have it's
`keyword.operator`s dimmed as well but for example JavaScript's dot operator is still white.
I don't have much interest of creating explicit grammars for all of the existing, popular or not,
languages so any contributions are welcome!

Planned features:
* Markdown highlight inside Rust doc comments.
* Explicit grammars for JavaScript and C.

NOTE: There is also plain TODO/FIXME/NOTE highlight for the supported languages.

## Credits

The theme and the custom grammars were insiped by `sublime` and `vscode`'s defaults.
