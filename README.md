# pkg
pkg is a universal command for trying to make working on several distros manageable.

copy the pkg file to /usr/local/bin/pkg or anywhere you have in your PATH for bin files.

make the file executable...

sudo chmod +x /usr/local/bin/pkg

run the commands like the following (you can also run "pkg --help" or just "pkg" on its own for a list of commands).

Usage: pkg [action] [package]

Actions:

it, install      : Install package

sr, search       : Search repositories

rm, remove       : Remove package

pr, purge        : Deep remove

ud, update       : Refresh repo lists

ug, up, upgrade  : System upgrade

cl, clean        : Remove orphans/cache
