# Testacle

This Visual Studio Code extension is designed to make working with TDD and testing in general much more convenient, by allowing you to:

- Switch between implementation and test/spec file quickly
- Open a test/spec file or implementation in a new window.

## Usage

- To open test/implementation, you can use the command `Open test or implementation in new tab` or using shortcut `cmd + shift + t` (`ctrl+shift+alt+t` on windows/linux)
- To switch between test/implementation, you can use the command `Switch between test and implementation` or using shortcut `cmd + shift + alt + t` (`ctrl+shift+alt+t` on windows/linux)

## Supported Files and Patterns

All file extensions (eg. `.js`, `.ts`, `.py`) are supported

File extensions can have prefixes (e.g. `foo.service.ts`)

Test files can have prefixes (e.g. `foo.spec.ts` or `foo.service.spec.ts`)

Test files can be contained in a `__tests__` directory, or stored directly next to implementation.

## Credits

Written and maintained by [rbutera](https://github.com/rbutera).

Something wrong? Please submit an [Issue](https://github.com/rbutera/vscode-testacle/issues/new)!

This project was forked from [Go-To-Test](https://github.com/futantan/go-to-test) and a number of fixes and features were added.

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg