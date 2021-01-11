# exiftool-vendored.pl

Provides the perl runtime distribution of
[ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool/) to
[node](https://nodejs.org/en/). As of version `10.38.0`, both testing and help
files are omitted, as they almost double the size of the package and more than
triple the number of files in the package.

[![CI](https://github.com/photostructure/exiftool-vendored.pl/workflows/Node.js%20CI/badge.svg?branch=master)](https://github.com/photostructure/exiftool-vendored.pl/actions?query=workflow%3A%22Node.js+CI%22)

## Usage

**See [exiftool-vendored](https://github.com/mceachen/exiftool-vendored) for
performant, type-safe access to this binary.**

## Versioning

This package exposes the version of ExifTool it vendors, and adds a patch
number, if necessary, to follow SemVer.