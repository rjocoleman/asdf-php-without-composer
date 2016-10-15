# asdf-php
 PHP plugin for [asdf version manager](https://github.com/HashNuke/asdf).

## Install

```
asdf plugin-add php https://github.com/Stratus3D/asdf-php.git
```

## Linux

You may need this libraries and packages to be able to compile PHP compiler versions:

```
sudo apt-get install curl build-essential autoconf libjpeg-dev libpng12-dev openssl libssl-dev libcurl4-openssl-dev pkg-config libsslcommon2-dev libreadline-dev libedit-dev zlib1g-dev libicu-dev libxml2-dev gettext bison libmysqlclient-dev libpq-dev
```

### macOS

In order to compile PHP on macOS machines, you must install some brew packages first:

```
brew install freetype bison27 gettext icu4c jpeg libpng openssl readline homebrew/dupes/zlib curl
```

and, in order to compile 5.x versions of PHP, you **must** link `bison27` package:

```
brew link --force bison27
```

## Development

Installing during development:

```
cp -r . ~/.asdf/plugins/php
```

####PHP Download Mirrors

I considered trying to use mirrors when downloading the source code. It seemed simpler to just download the release from GitHub. Example code: https://gist.github.com/lox/9152137

## Use

Check the [asdf](https://github.com/HashNuke/asdf) readme for instructions on how to install & manage versions of PHP.

## Contributing

Feel free to create an issue or pull request if you find a bug.

## Issues

No known issues

## License
MIT License
