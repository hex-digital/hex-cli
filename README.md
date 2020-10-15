@hexdigital/cli
===============

Hex CLI for repetitive development tasks

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@hexdigital/cli.svg)](https://npmjs.org/package/@hexdigital/cli)
[![CircleCI](https://circleci.com/gh/hex-digital/hex-cli/tree/master.svg?style=shield)](https://circleci.com/gh/hex-digital/hex-cli/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/@hexdigital/cli.svg)](https://npmjs.org/package/@hexdigital/cli)
[![License](https://img.shields.io/npm/l/@hexdigital/cli.svg)](https://github.com/hex-digital/hex-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @hexdigital/cli
$ hex COMMAND
running command...
$ hex (-v|--version|version)
@hexdigital/cli/0.0.1 darwin-x64 node-v10.16.3
$ hex --help [COMMAND]
USAGE
  $ hex COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`hex hello [FILE]`](#hex-hello-file)
* [`hex help [COMMAND]`](#hex-help-command)

## `hex hello [FILE]`

describe the command here

```
USAGE
  $ hex hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ hex hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/hex-digital/hex-cli/blob/v0.0.1/src/commands/hello.ts)_

## `hex help [COMMAND]`

display help for hex

```
USAGE
  $ hex help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
