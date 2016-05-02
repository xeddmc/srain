Srain
=====
[![Travis](https://img.shields.io/travis/LastAvenger/srain.svg?maxAge=2592000)]()
[![Github All Releases](https://img.shields.io/github/downloads/LastAvenger/srain/total.svg?maxAge=2592000)]()

it does not look like a irc client :-)

# Dependencies

* make          (makedepends)
* gcc           (makedepends)
* libcurl       (makedepends)
* pkg-config    (makedepends)
* gettext       (makedepends)
* gtk >= 3.16
* glib2
* python >= 3.2

# Build

    make init
    make
    make run

# Install

## For Arch Linux users

    yaourt -S srain-git

## For other linux distributions:

    make init
    make DESTDIR=/usr
	make DESTDIR=/usr install

# Feature

- relay bot message transform
- preview image from url
- get avatar from github (plugin)
- auto upload image to pastebin (plugin)

# Screenshot

As you see, its theme is inspired by Telegram Desktop.

![screenshot](https://img.vim-cn.com/4f/59a3f20a2f7402d94b6759b860e37dac5bf843.png)
