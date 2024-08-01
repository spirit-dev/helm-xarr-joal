# Welcome to joal

[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=joal-turingpi&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/joal-turingpi)

## Table of content

- [Welcome to joal](#welcome-to-joal)
  - [Table of content](#table-of-content)
  - [Installation process](#installation-process)

## Installation process

The installation is entirely managed by Argocd.

A `Makefile` is present here to ease the first and one-time deployment or in case of an issue.
The installation should be done in two steps:

```shell
#> make dry-run ENV=<ENV>
#> make install ENV=<ENV>
```
