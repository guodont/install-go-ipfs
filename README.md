# install-go-ipfs

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> install go-ipfs shell script

This shell script installs the [go-ipfs](https://github.com/ipfs/go-ipfs) binary. It is not very safe, as it trusts gobuilder to provide a valid binary.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Examples](#examples)
- [Contribute](#contribute)
- [License](#license)

## Install

```sh
wget -q https://raw.githubusercontent.com/ipfs/install-go-ipfs/master/install-ipfs.sh
chmod +x install-ipfs.sh
./install-ipfs.sh
```

## Usage

```sh
> install-ipfs.sh [<version>] [<install-path>]
installs the ipfs binary at a local install path
```

Possible `<version>` values:
- [`release` - the last released version](https://gobuilder.me/github.com/ipfs/go-ipfs/cmd/ipfs?branch=release)  **<-- recommended**
- [`master` - development, stable](https://gobuilder.me/github.com/ipfs/go-ipfs/cmd/ipfs?branch=master)
- Eg. [`v0.3.7` - one of the releases](https://github.com/ipfs/go-ipfs/releases) 

## Examples

Install a specific version
```sh
install-ipfs.sh v0.3.7
```

Install to a specific path
```sh
install-ipfs.sh v0.3.7 ./bin/ipfs
```

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs/install-go-ipfs/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

MIT
