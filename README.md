# atom-config

Personal configuration files for [Atom](https://atom.io) editor

## Installation

* Clone this repo
* Install **Atom**
* Create symlinks for your local home directory (*~/.atom/*)
* Packages:

    `$ apm install --packages-file packages.txt`
* Launch **Atom**!

## Regenerating packages file

    $ apm list --installed --bare

## Creating symlinks to your directory

    ln -s ~/atom-config/conf/config.cson ~/.atom/config.cson
    ln -s ~/atom-config/conf/init.coffee ~/.atom/init.coffee
    ln -s ~/atom-config/conf/keymap.cson ~/.atom/keymap.cson
    ln -s ~/atom-config/conf/snippets.cson ~/.atom/snippets.cson
    ln -s ~/atom-config/conf/styles.less ~/.atom/styles.less
