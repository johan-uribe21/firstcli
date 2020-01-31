firstcli
========

My first CLI tool

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/firstcli.svg)](https://npmjs.org/package/firstcli)
[![Downloads/week](https://img.shields.io/npm/dw/firstcli.svg)](https://npmjs.org/package/firstcli)
[![License](https://img.shields.io/npm/l/firstcli.svg)](https://github.com/johan-uribe21/firstcli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g firstcli
$ firstcli COMMAND
running command...
$ firstcli (-v|--version|version)
firstcli/0.0.0 darwin-x64 node-v13.5.0
$ firstcli --help [COMMAND]
USAGE
  $ firstcli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`firstcli hello [FILE]`](#firstcli-hello-file)
* [`firstcli help [COMMAND]`](#firstcli-help-command)

## `firstcli hello [FILE]`

describe the command here

```
USAGE
  $ firstcli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ firstcli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/johan-uribe21/firstcli/blob/v0.0.0/src/commands/hello.ts)_

## `firstcli help [COMMAND]`

display help for firstcli

```
USAGE
  $ firstcli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
