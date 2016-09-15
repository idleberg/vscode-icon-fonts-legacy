# Icon Fonts (Legacy) for Visual Studio Code

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GNU General Public License](https://img.shields.io/badge/license-GPL%20v2-orange.svg?style=flat-square)](http://www.gnu.org/licenses/gpl-2.0.html)
[![GitHub](https://img.shields.io/github/release/idleberg/vscode-icon-fonts-legacy.svg?style=flat-square)](https://github.com/idleberg/vscode-icon-fonts-legacy-legacy/releases)
[![Travis](https://img.shields.io/travis/idleberg/vscode-icon-fonts-legacy.svg?style=flat-square)](https://travis-ci.org/idleberg/vscode-icon-fonts-legacy)
[![David](https://img.shields.io/david/dev/idleberg/vscode-icon-fonts-legacy.svg?style=flat-square)](https://david-dm.org/idleberg/vscode-icon-fonts-legacy?type=dev)

Snippets for icon fonts that have been deprecated from the main [Icon Fonts](https://github.com/idleberg/vscode-icon-fonts) package ([see details](#prefixes)).

This package is also available for [Atom](https://github.com/idleberg/atom-icon-fonts-legacy) and [Sublime Text](https://github.com/idleberg/sublime-icon-fonts-legacy).

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install icon-fonts`

### GitHub

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `icon-fonts`:

```bash
$ git clone https://github.com/idleberg/vscode-icon-fonts-legacy icon-fonts
```

### Usage

Snippets are limited to the `html` scope. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class.

### Prefixes

Prefix         | Icon Font                           | Version
---------------|-------------------------------------|--------
`filetypes`    | [Glyphicons Filetypes][filetypes]   | 1.9.0
`foundico`     | [Foundation Icons][foundico]        | 1.0.0
`glyphicons`   | [Glyphicons Pro][glyphicons]        | 1.9.0
`halflings`    | [Glyphicons Halflings][halflings]   | 1.9.0
`line`         | [Elegant Theme Line Icons][line]    | –
`social`       | [Glyphicons Social][social]         | 1.9.0

Examples:

* `foundicon-checkmark`+<kbd>Tab</kbd> completes to `<i class="foundicon-checkmark"></i>`
* `glyphicons-check`+<kbd>Tab</kbd> completes to `<span class="glyphicons glyphicons-check"></span>`
* well, you get the idea

## License

This work is licensed under the [The MIT License](LICENSE.md).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/atom-icon-fonts-legacy) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`

[filetypes]: http://glyphicons.com
[foundico]: https://github.com/zurb/foundation-icons/tree/original-implementation
[glyphicons]: http://glyphicons.com
[halflings]: http://glyphicons.com
[line]: https://www.elegantthemes.com/blog/resources/elegant-icon-font
[social]: http://glyphicons.com
