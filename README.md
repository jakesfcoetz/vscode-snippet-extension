# VSCode Snippets Extension

[![Last Commit][commit badge]][commit]
[![Code Style][style badge]][style]

[commit badge]: https://img.shields.io/github/last-commit/jakesfcoetz/vscode-snippet-extension?style=flat
[style badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat

[commit]: https://github.com/first-care-solutions/hub/commit/HEAD
[style]: https://github.com/prettier/prettier

## Accessable through intellisense

-  jdoc - Creates JSDoc snippets in Typescript files
-  jlayout - Creates HTML snippets in HTML files

### jdoc

| Prefix  | Used for |
| ------------- | ------------- |
| `jdoc file`  | Typescript file headings |
| `jdoc class`  | Typescript classes  |
| `jdoc constructor`  | Typescript constructor |
| `jdoc interface`  | Typescript interfaces (also creates)  |
| `jdoc method`  | Typescript methods (also creates)  |

### jlayout

| Prefix  | Used for |
| ------------- | ------------- |
| `jlayout card`  | Ionic card with classes defined in FCS css |
| `jlayout grid`  | Ionic grid with all available ion classes  |
| `jlayout grid row`  | Ionic grid row with all available ion classes  |
| `jlayout grid col`  | Ionic grid col with all available ion classes  |

## To create extention package from code, run

``` BASH
vsce package
```
