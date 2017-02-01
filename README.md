# Annict CLI tool

thanks to https://annict.com/ and its API

![](http://pbs.twimg.com/media/C3lyg4aVcAEafFI.jpg)

## Setup

`./annict` is a portable shell script.
Copy it to your path.

## Requirements

- bash
- curl
- jq
- peco

## Usage

```bash
$ annict auth

makes oAuth with Annict.com

$ annict calendar

lists up all your unwatch

$ annict watch <title-query>

marks a episode as watched.
This command works as a CLI.
1. search works with <title-query> (the search history and this result will be cached)
2. choose a work
3. show all episodes of the work (this list will be cached)
4. choose a episode
5. mark it
```

