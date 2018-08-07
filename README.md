# Icon Fonts (Legacy) for Visual Studio Code

[![The MIT License](https://flat.badgen.net/badge/license/MIT/orange)](http://opensource.org/licenses/MIT)
[![GitHub](https://flat.badgen.net/github/release/idleberg/vscode-icon-fonts-legacy)](https://github.com/idleberg/vscode-icon-fonts-legacy/releases)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/idleberg.icon-fonts-legacy.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts-legacy)
[![Travis](https://flat.badgen.net/travis/idleberg/vscode-icon-fonts-legacy)](https://travis-ci.org/idleberg/vscode-icon-fonts-legacy)
[![David](https://flat.badgen.net/david/dev/idleberg/vscode-icon-fonts-legacy)](https://david-dm.org/idleberg/vscode-icon-fonts-legacy?type=dev)

Snippets for icon fonts that have been deprecated from the main [Icon Fonts](https://github.com/idleberg/vscode-icon-fonts) package ([see details](https://github.com/idleberg/vscode-icon-fonts-legacy#prefixes)).

This package is also available for [Atom](https://github.com/idleberg/atom-icon-fonts-legacy) and [Sublime Text](https://github.com/idleberg/sublime-icon-fonts-legacy).

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install icon-fonts-legacy`

### Packaged Extension

Download the package extension from the the [release page](https://github.com/idleberg/vscode-icon-fonts-legacy/releases) and install it from the command-line:

```bash
$ code --install-extension icon-fonts-legacy-*.vsix
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

Prefix         | Icon Font                           | Version
---------------|-------------------------------------|--------
`brandico`     | [Brandico Font][brandico]           | – 
`filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0
`fontawesome`  | [Font Awesome][fontawesome]         | 4.7.0
`foundico`     | [Foundation Icons][foundico]        | 1.0.0
`glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0
`halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0
`icofont`      | [ShapeBootstrap IcoFont][icofont]   | 1.0.0b
`line`         | [Elegant Theme Line Icons][line]    | –
`social`       | [Glyphicons Social][social]         | 1.9.0
`ui`           | [Semantic UI Icons][ui]             | 2.0.7

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/atom-icon-fonts-legacy) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`

[brandico]: https://github.com/fontello/brandico.font
[filetypes]: http://glyphicons.com
[fontawesome]: https://fontawesome.com
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[icofont]: http://icofont.com/
[line]: https://www.elegantthemes.com/blog/resources/elegant-icon-font
[social]: http://glyphicons.com
[ui]: http://semantic-ui.com/elements/icon.html
