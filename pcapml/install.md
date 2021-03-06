---
layout: default
title: Installation
has_children: false
parent: pcapML
grand_parent: The nPrint Project
nav_order: 1
---


# Installation

## Supported Operating Systems

* Debian Linux
* macOS

## Dependencies

* [libpcap](https://www.tcpdump.org/) - Packet sniffing
* [argp](https://www.gnu.org/software/libc/manual/html_node/Argp.html) - Argument parsing

### Install dependencies on Debian:

`sudo apt-get install libpcap-dev`

### Install dependencies on Mac OS

`brew install argp-standalone`

## Installation

1. Download the latest release tar [here](https://github.com/nprint/pcapml/releases/)
2. Extract the tar `tar -xvf [pcapml-version.tar.gz]`
3. `cd [pcapml-directory]`

2. `./configure && make && sudo make install`
