# ❤ Feels

> Simple feels tracker

## Table of contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Installation](#installation)
- [Usage](#usage)
- [Configure](#configure)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

```
npm install -g @itsjonq/feels
```

## Usage

In your Terminal, run the `feel` command:

```
feels
```

By default, it will output the help content:

```
❤️ Feels

feels <command>

Example:
  feels add "Great!"

Options:
  -V, --version  output the version number
  -h, --help     output usage information

Commands:
  config [options]  Configures Feels
  add|a [task]      Add a new feels for Today
  new|n [task]      Alias for "add"
  list|ls           List Today's feels
  edit|e            Edit Today's feels
  print|p           Print Yesterday's and Today's feels
  copy|cp           Copy Yesterday's and Today's feels
  open|o            Opens the feels directory
  which             Display location of feels
```

## Configure

By default, Do will create `.md` files under the `~/.feels` directory. You can customize the directory by running:

```
feels config --dir=~/Stuff/my-custom-do/here
```
