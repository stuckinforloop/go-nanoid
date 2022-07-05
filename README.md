# Go Nanoid

[![Build Status](https://github.com/matoous/go-nanoid/workflows/Tests/badge.svg)](https://github.com/matoous/go-nanoid/actions) 
[![Build Status](https://github.com/matoous/go-nanoid/workflows/Lint/badge.svg)](https://github.com/matoous/go-nanoid/actions) 
[![GoDoc](https://godoc.org/github.com/matoous/go-nanoid?status.svg)](https://godoc.org/github.com/matoous/go-nanoid)
[![Go Report Card](https://goreportcard.com/badge/github.com/matoous/go-nanoid)](https://goreportcard.com/report/github.com/matoous/go-nanoid)
[![GitHub issues](https://img.shields.io/github/issues/matoous/go-nanoid.svg)](https://github.com/matoous/go-nanoid/issues)
[![License](https://img.shields.io/badge/license-MIT%20License-blue.svg)](https://github.com/matoous/go-nanoid/LICENSE)


This package is Go implementation of [ai's](https://github.com/ai) [nanoid](https://github.com/ai/nanoid)!

**Safe.** It uses cryptographically strong random generator.

**Compact.** It uses more symbols than UUID (`A-Za-z0-9_-`)
and has the same number of unique options in just 22 symbols instead of 36.

**Fast.** Nanoid is as fast as UUID but can be used in URLs.

There's also this alternative: https://github.com/jaevor/go-nanoid.

## Install

Via go get tool

``` bash
$ go get github.com/matoous/go-nanoid/v2
```

## Usage

Generate ID

``` go
id, err := gonanoid.New()
```

Generate ID with a custom alphabet and length

``` go
id, err := gonanoid.Generate("abcde", 54)
```

## Notice

If you use Go Nanoid in your project, please let me know!

If you have any issues, just feel free and open it in this repository, thanks!

## Credits

- [ai](https://github.com/ai) - [nanoid](https://github.com/ai/nanoid)
- icza - his tutorial on [random strings in Go](https://stackoverflow.com/questions/22892120/how-to-generate-a-random-string-of-a-fixed-length-in-golang)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
