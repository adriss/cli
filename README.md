adriss
======

Adriss CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/adriss.svg)](https://npmjs.org/package/adriss)
[![Downloads/week](https://img.shields.io/npm/dw/adriss.svg)](https://npmjs.org/package/adriss)
[![License](https://img.shields.io/npm/l/adriss.svg)](https://github.com/adriss/cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g adriss
$ adriss COMMAND
running command...
$ adriss (-v|--version|version)
adriss/0.0.1 darwin-x64 node-v12.1.0
$ adriss --help [COMMAND]
USAGE
  $ adriss COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`adriss hello [FILE]`](#adriss-hello-file)
* [`adriss help [COMMAND]`](#adriss-help-command)

## `adriss hello [FILE]`

describe the command here

```
USAGE
  $ adriss hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ adriss hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/adriss/cli/blob/v0.0.1/src/commands/hello.ts)_

## `adriss help [COMMAND]`

display help for adriss

```
USAGE
  $ adriss help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_
<!-- commandsstop -->
