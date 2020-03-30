# __Kyanit__ CTL

## Introduction

Kyanit CTL is part of the Kyanit ecosystem. See https://github.com/kyanit-project/kyanit for an
introduction to Kyanit.

Kyanit CTL is a command-line utility using Kyanit API for interfacing and interacting with Kyanit.

## The Kyanit Ecosystem

* [**Kyanit Core**](https://github.com/kyanit-project/kyanit)

The core Kyanit module, flashed into an ESP8266 board.

* [**Kyanit Board**](https://github.com/kyanit-project/kyanit-board)

A stylish, triangle-shaped ESP8266-based board built around an ESP-12F module, the official Kyanit
controller board.

* [**Kyanit CTL**](https://github.com/kyanit-project/kyanit-ctl)

This repo. Command-line utility for interacting with Kyanit.

* [**Kyanit API**](https://github.com/kyanit-project/kyanit-api)

Python API for interaction with Kyanit from Python code. (It is used by Kyanit CTL.)

## Installing Kyanit CTL

Install the latest released version with:

```
pip install kyanitctl
```

After installation, Kyanit CTL will be available through the `kyanitctl` command.

## Installing Kyanit CTL from Source

To get the latest development version, clone this repository and within the repository root, run:

```
python setup.py install
```

## Usage

Refer to the command-line help with `kyanitctl -h`.

## License Notice

Copyright (C) 2020 Zsolt Nagy

This program is free software: you can redistribute it and/or modify it under the terms of the
GNU General Public License as published by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without
even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program.
If not, see <https://www.gnu.org/licenses/>.
