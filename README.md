Homebrew Mingw-w64 Formulae
===

## Sub command

Unofficial Homebrew user-defined sub-command.

To use this sub-command:

```bash
$ brew tap cosmo0920/mingw_w64
```

and then,

```bash
$ brew install-mingw-w64
```

Finally, you can install `mingw-w64` named keg cellar.
You can uninstall this cellar with `brew uninstall mingw-w64`.

## Formulae

Unofficial Homebrew Mingw-w64 Formulae.

To use these formulae,

```bash
$ brew tap cosmo0920/mingw_w64
```

and then,

```bash
$ brew install <mingw_w64 formula>
```
### Contents

* (i686|x86-64)-w64-mingw32-binutils
    - install mingw-w64 binutils
* (i686|x86-64)-w64-mingw32-gcc
    - install mingw-w64 cross gcc and its runtime (winpthread also included)

### install dir

These formulae try to install mingw-w64 toolchain into each of `#{prefix}/libexec`.

And now, `keg_only` attributes has been removed by [pull#11](https://github.com/cosmo0920/homebrew-mingw_w64/pull/11).
You can use `mingw32-gcc`s without additional environment variables.

## installing gcc, binutils, and mingw versions

* gcc 7.2.0
* binutils 2.29
* mingw 5.0.3

### LICENSE

[MIT](LICENSE.txt).
