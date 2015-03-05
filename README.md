# Minio Client

mc - unified command line interface for Minio and S3 released under [Apache license v2](./LICENSE).

## Install

```
# go get github.com/minio-io/mc
```

## Usage

### Commands
```
NAME:
   mc - unified command line interface for Minio and S3

USAGE:
   mc [global options] command [command options] [arguments...]

VERSION:
   0.1.0

AUTHOR:
  Minio Community

COMMANDS:
   cp
   ls
   mb
   sync
   configure
   help, h      Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --help, -h           show help
   --version, -v        print the version
```

## Contribute

[Contribute to mc](./CONTRIBUTING.md)

### Enable bash completion

Edit your ``${HOME}/.bashrc`` file

```
source ${HOME}/.minio/mc/mc.completion

$ mc <TAB><TAB>
configure  cp         h          help       ls         mb         sync
```