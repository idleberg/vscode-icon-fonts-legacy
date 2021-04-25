# Icon Fonts (Legacy) for Visual Studio Code

[![The MIT License](https://flat.badgen.net/badge/license/MIT/orange)](http://opensource.org/licenses/MIT)
[![GitHub](https://flat.badgen.net/github/release/idleberg/vscode-icon-fonts-legacy)](https://github.com/idleberg/vscode-icon-fonts-legacy/releases)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/idleberg.icon-fonts-legacy.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts-legacy)
[![CircleCI](https://flat.badgen.net/circleci/github/idleberg/vscode-icon-fonts-legacy)](https://circleci.com/gh/idleberg/vscode-icon-fonts-legacy)

Snippets for icon fonts that have been deprecated from the main [Icon Fonts](https://github.com/idleberg/vscode-icon-fonts) package ([see details](https://github.com/idleberg/vscode-icon-fonts-legacy#prefixes)).

This package is also available for [Atom](https://github.com/idleberg/atom-icon-fonts-legacy) and [Sublime Text](https://github.com/idleberg/sublime-icon-fonts-legacy).

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install idleberg.icon-fonts-legacy`

### CLI

With [shell commands](https://code.visualstudio.com/docs/editor/command-line) installed, you can use the following command to install the extension:

`$ code --install-extension idleberg.icon-fonts-legacy`

### Packaged Extension

Download the packaged extension from the the [release page](https://github.com/idleberg/vscode-icon-fonts-legacy/releases) and install it from the command-line:

```bash
$ code --install-extension path/to/icon-fonts-legacy-*.vsix
```

Alternatively, you can download the packaged extension from the [Open VSX Registry](https://open-vsx.org/) or install it using the [`ovsx`](https://www.npmjs.com/package/ovsx) command-line tool:

```bash
$ ovsx get idleberg.icon-fonts-legacy
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `icon-fonts-legacy`:

```bash
$ git clone https://github.com/idleberg/vscode-icon-fonts-legacy icon-fonts-legacy
```

### Usage

Snippets are limited to the `html`, `css|less|sass|scss|stylus`, `jsx`, `blade` and `vue` scopes. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class.

### Prefixes

| Prefix         | Icon Font                           | Version |
|----------------|-------------------------------------|---------|
| `brandico`     | [Brandico Font][brandico]           | –       |
| `fi`           | [Foundation Icons v3][fi]           | 3.0     |
| `filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0   |
| `fa`           | [Font Awesome][fontawesome]         | 4.7.0   |
| `foundico`     | [Foundation Icons][foundico]        | 1.0.0   |
| `geomicon`     | [Geomicons Open][geomicon]          | 2.0.0   |
| `glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0   |
| `halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0   |
| `icofont`      | [ShapeBootstrap IcoFont][icofont]   | 1.0.0b  |
| `line`         | [Elegant Theme Line Icons][line]    | –       |
| `social`       | [Glyphicons Social][social]         | 1.9.0   |
| `ratchicon`    | [Ratchicons][ratchicon]             | 2.0.2   |
| `ui`           | [Semantic UI Icons][ui]             | 2.0.7   |

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

[brandico]: https://github.com/fontello/brandico.font
[fi]: https://github.com/zurb/foundation-icons
[filetypes]: http://glyphicons.com
[fontawesome]: https://fontawesome.com
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[geomicon]: https://github.com/jxnblk/geomicons-open
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[icofont]: http://icofont.com/
[line]: https://www.elegantthemes.com/blog/resources/elegant-icon-font
[ratchicon]: http://github.com/twbs/ratchet
[social]: http://glyphicons.com
[ui]: http://semantic-ui.com/elements/icon.html
