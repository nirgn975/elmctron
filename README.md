# Elmctron

[![license](https://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/nirgn975/Elmctron/blob/master/LICENSE) [![Build Status](https://travis-ci.org/nirgn975/Elmctron.svg?branch=master)](https://travis-ci.org/nirgn975/Elmctron) [![Build status](https://ci.appveyor.com/api/projects/status/ouaskt8wyeummjfv/branch/master?svg=true)](https://ci.appveyor.com/project/nirgn975/elmctron/branch/master)

TodoMVC app written in Elm and using Electron.

**What you get**

 * `SCSS` is compiled to `CSS` automatically.
 * `Elm` is compiled to `JS` automatically.
 * `HTML`, `SCSS`, and `Elm` are watched, trigger auto-reload when updated.
 * Elm packages are downloaded and installed automagically.
 * When the `Electron` app starts, the `dev-tools` show up.

**For more information read [Gizra post](http://www.gizra.com/content/elm-electron-build/).**

## Installation

1. Run `npm install`.

## Development

1. Run `npm run gulp`.

## Build

If you want to build the app on our local machine, you'll need to [install some packages](https://github.com/electron-userland/electron-builder/wiki/Multi-Platform-Build).

1. Run `npm run dist` to build for all platforms (linux, mac, and windows).

 * Run `npm run dist-mac` to build just for Mac OS.
 * Run `npm run dist-linux` to build just for GNU/Linux.
 * Run `npm run dist-win` to build just for Windows.

## License

ISC
