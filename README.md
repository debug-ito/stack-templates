# debug-ito's template files for stack "new" command

This repository contains project templates for [stack](https://docs.haskellstack.org/), a development toolchain for Haskell programming language. See [stack user guide](https://docs.haskellstack.org/en/stable/GUIDE/#templates) for detail about templates.

- basic.hsfiles: the one that debug-ito usually uses.

## Parameters

The template uses the following parameters. You have to configure them by `$(HOME)/.stack/config.yaml` or `-p` option.

- `author-name`: Real name of the author of the new package. (e.g. Toshio Ito)
- `author-email`: Email address of the author of the new package. (e.g. debug.ito@gmail.com)
- `github-username`: GitHub username of the author of the new package (e.g. debug-ito)

## How to use

Run `stack new` like below.

    $ stack new new-package-name github:debug-ito/basic

## Author

Toshio Ito <debug.ito@gmail.com>
