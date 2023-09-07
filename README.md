# jq-msi

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A WIX project that packages jq into a Windows MSI.

## Releases

This repo checks [jqlang/jq](https://github.com/jqlang/jq) daily for a new release
and builds an MSI if required. Only the 10 most recent releases are retained.

## Features

To add the installation directory to the system path, set the `INSTALLLEVEL` to `2`.

```bat
msiexec.exe /i jq.msi INSTALLLEVEL=2
```
