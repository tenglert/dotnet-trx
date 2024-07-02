![Icon](assets/icon.png) dotnet-trx
============

[![Version](https://img.shields.io/nuget/vpre/dotnet-trx.svg?color=royalblue)](https://www.nuget.org/packages/dotnet-trx)
[![Downloads](https://img.shields.io/nuget/dt/dotnet-trx.svg?color=green)](https://www.nuget.org/packages/dotnet-trx)
[![License](https://img.shields.io/github/license/devlooped/dotnet-trx.svg?color=blue)](https://github.com//devlooped/dotnet-trx/blob/main/license.txt)
[![Build](https://github.com/devlooped/dotnet-trx/workflows/build/badge.svg?branch=main)](https://github.com/devlooped/dotnet-trx/actions)

<!-- #content -->
Pretty-print test results in TRX format.

```shell
USAGE:
    trx [PATH] [OPTIONS]

ARGUMENTS:
    [PATH]    Optional base directory for *.trx files discovery. Defaults to current directory

OPTIONS:
                       DEFAULT
    -h, --help                    Prints help information
    -r, --recursive    True       Recursively search for *.trx files
        --version                 Show version information
```

Install:

```shell
dotnet tool install -g dotnet-trx
```

Update:

```shell
dotnet tool update -g dotnet-trx
```

<!-- #content -->
<!-- include https://github.com/devlooped/sponsors/raw/main/footer.md -->