# ⛔️ This module is now part of https://github.com/ipfs/js-stores

# blockstore-fs <!-- omit in toc -->

[![ipfs.tech](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.tech)
[![Discuss](https://img.shields.io/discourse/https/discuss.ipfs.tech/posts.svg?style=flat-square)](https://discuss.ipfs.tech)
[![codecov](https://img.shields.io/codecov/c/github/ipfs/js-blockstore-fs.svg?style=flat-square)](https://codecov.io/gh/ipfs/js-blockstore-fs)
[![CI](https://img.shields.io/github/actions/workflow/status/ipfs/js-blockstore-fs/js-test-and-release.yml?branch=main\&style=flat-square)](https://github.com/ipfs/js-blockstore-fs/actions/workflows/js-test-and-release.yml?query=branch%3Amain)

> Blockstore implementation with file system backend

## Table of contents <!-- omit in toc -->

- [Install](#install)
- [Usage](#usage)
- [API Docs](#api-docs)
- [License](#license)
- [Contribute](#contribute)

## Install

```console
$ npm i blockstore-fs
```

## Usage

```js
import { FSBlockstore } from 'blockstore-fs'

const store = new FSBlockstore('path/to/store')
```

## API Docs

- <https://ipfs.github.io/js-blockstore-fs>

## License

Licensed under either of

- Apache 2.0, ([LICENSE-APACHE](LICENSE-APACHE) / <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT ([LICENSE-MIT](LICENSE-MIT) / <http://opensource.org/licenses/MIT>)

## Contribute

Contributions welcome! Please check out [the issues](https://github.com/ipfs/js-blockstore-fs/issues).

Also see our [contributing document](https://github.com/ipfs/community/blob/master/CONTRIBUTING_JS.md) for more information on how we work, and about contributing in general.

Please be aware that all interactions related to this repo are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/CONTRIBUTING.md)
