Hamlbars
========

Sublime Text 3 syntax definitions and auto-completions for .hamlbars files.  

## Installation
#### With [Package Control](https://packagecontrol.io/)
  1. Open the command palette. (ctrl+shift+p or command+shift+p)
  2. Type "install" and choose Package Control: Install Package
  3. Type "Hamlbars" and select the package by Greplytix.
  
#### Manually
Clone this repository into one of the following directories:

**OS X:** ~/Library/Application Support/Sublime Text 3/Packages/User

**Windows:** %APPDATA%/Roaming/Sublime Text 3/Packages/User

**Linux:** ~/.config/sublime-text-3/Packages/User

#### Trouble-shooting:

If .hamlbar files are not being automatically associated with the Hamlbars language:
  1. While viewing a .hamlbars file
  2. Go to the bottom-right language switcher.
  3. Go to sub-menu "Open all with current extension as...".
  4. Select Hamlbars.

## Development Pipeline

Contributors, when updating the syntax definitions, please transcompile the Hamlbars.tmLanguage.YAML (YAML) file to the Hamlbars.tmLanguage (plist) file via [SerializedDataConverter](https://packagecontrol.io/packages/SerializedDataConverter).

## Credits

This package has been adapted from [Handlebars](https://github.com/daaain/Handlebars) by [Daniel Demmel](https://github.com/daaain), which was adapted from [Nicholas Westlake's](https://github.com/nrw) Handlebars [package](https://github.com/nrw/sublime-text-handlebars), and has been combined with built-in Sublime Text 3 support for Haml.

## License

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
