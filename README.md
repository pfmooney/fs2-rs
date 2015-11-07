# fs2

Extended utilities for working with files and filesystems in Rust. `fs2`
requires Rust stable 1.1 or greater.

[Documentation](https://danburkert.github.io/fs2-rs/fs2/index.html)

[![Linux Status](https://travis-ci.org/danburkert/fs2-rs.svg?branch=master)](https://travis-ci.org/danburkert/fs2-rs)
[![Windows Status](https://ci.appveyor.com/api/projects/status/iuvjv1aaaml0rntt/branch/master?svg=true)](https://ci.appveyor.com/project/danburkert/fs2-rs)

## Features

- [x] file descriptor duplication.
- [x] file locks.
- [ ] file (pre)allocation.
- [ ] file allocation information.
- [ ] filesystem usage information.

## Platforms

`fs2` should work on any platform supported by
[`libc`](https://github.com/rust-lang-nursery/libc#platforms-and-documentation).

`fs2` is continuously tested on:
  * `x86_64-unknown-linux-gnu` (Linux)
  * `i686-unknown-linux-gnu`
  * `x86_64-apple-darwin` (OSX)
  * `i686-apple-darwin`
  * `x86_64-pc-windows-msvc` (Windows)
  * `i686-pc-windows-msvc`
  * `x86_64-pc-windows-gnu`
  * `i686-pc-windows-gnu`

## License

`fs2` is primarily distributed under the terms of both the MIT license and the
Apache License (Version 2.0).

See [LICENSE-APACHE](LICENSE-APACHE), [LICENSE-MIT](LICENSE-MIT) for details.

Copyright (c) 2015 Dan Burkert.
