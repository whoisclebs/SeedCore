# 🌱 Seed OS 🌱

> A simple OS made with rust.

[![GitHub repo size][repo-size]][project-url]
[![GitHub license][license]][license-url]
[![GitHub issues open][issues-open]][issues-url]
[![GitHub issues closed][issues-closed]][issues-url]
[![GitHub pr open][pr-open]][pr-url]
[![GitHub pr closed][pr-closed]][pr-url]
[![GitHub stars][stars]][stargazers]

This repository is an experiment of an operating system made with rust.

## Why in rust? 

1. Rust is one of the most energy efficient languages
2. It's a great way to learn
3. Why not?

## Installation

OS X & Linux:

```sh
cargo build --target thumbv7em-none-eabihf 
```

Windows:

```sh
cargo rustc -- -C link-args="/ENTRY:_start /SUBSYSTEM:console"
```

## Release History

* 0.0.1
  * Work in progress

## Contact

Clebson Augusto Fonseca– [@clebsonf](https://www.linkedin.com/in/fclebson/) – clebson.augusto@dcx.ufpb.br

Distributed under the MIT license. See ``LICENSE`` for more information.

## Contributing

1. Fork it (<https://github.com/clebsonf/Seed_OS/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[repo-size]: https://img.shields.io/github/repo-size/clebsonf/Seed_OS?color=greendark
[project-url]: https://github.com/clebsonf/Seed_OS
[license]: https://img.shields.io/github/license/clebsonf/Seed_OS
[license-url]: https://github.com/clebsonf/Seed_OS/blob/main/LICENSE
[issues-open]:https://img.shields.io/github/issues/clebsonf/Seed_OS
[issues-closed]: https://img.shields.io/github/issues-closed/clebsonf/Seed_OS
[issues-url]: https://github.com/clebsonf/Seed_OS/issues
[pr-open]: https://img.shields.io/github/issues-pr/clebsonf/Seed_OS
[pr-closed]: https://img.shields.io/github/issues-pr-closed/clebsonf/Seed_OS
[pr-url]: https://github.com/clebsonf/Seed_OS/pulls
[stars]: https://img.shields.io/github/stars/clebsonf/Seed_OS?style=social
[stargazers]: https://github.com/clebsonf/Seed_OS/stargazers