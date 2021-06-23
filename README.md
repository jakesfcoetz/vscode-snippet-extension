# VSCode Snippets Extension
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