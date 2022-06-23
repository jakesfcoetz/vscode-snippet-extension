# VSCode Snippets Extension

[![Last Commit][commit badge]][commit]
![Package.json version][version bage]
![VS Marketplace Release Date][release date]
![VS Marketplace Last Updated][last updated]
[![Code Style][style badge]][style]

[commit badge]: https://img.shields.io/github/last-commit/jakesfcoetz/vscode-snippet-extension?style=flat
[version bage]: https://img.shields.io/github/package-json/v/jakesfcoetz/vscode-snippet-extension
[release date]: https://img.shields.io/visual-studio-marketplace/release-date/jakesfcoetz.jakes-snippets
[last updated]: https://img.shields.io/visual-studio-marketplace/last-updated/jakesfcoetz.jakes-snippets
[style badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat
[commit]: https://github.com/first-care-solutions/hub/commit/HEAD
[style]: https://github.com/prettier/prettier

## Accessible through intellisense

- jdoc - Creates JSDoc snippets in Typescript files
- jlayout - Creates HTML snippets in HTML files

### jdoc

| Prefix             | Used for                             |
| ------------------ | ------------------------------------ |
| `jdoc file`        | Typescript file headings             |
| `jdoc class`       | Typescript classes                   |
| `jdoc constructor` | Typescript constructor               |
| `jdoc interface`   | Typescript interfaces (also creates) |
| `jdoc method`      | Typescript methods (also creates)    |

### jlayout

| Prefix             | Used for                                      |
| ------------------ | --------------------------------------------- |
| `jlayout card`     | Ionic card with classes defined in FCS css    |
| `jlayout grid`     | Ionic grid with all available ion classes     |
| `jlayout grid row` | Ionic grid row with all available ion classes |
| `jlayout grid col` | Ionic grid col with all available ion classes |

## To create extension package from code

### Install

```BASH
npm install -g vsce
```

### Run

```BASH
vsce package
```
