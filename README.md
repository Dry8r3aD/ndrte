# ndrte

<img src="https://avatars3.githubusercontent.com/u/19686401" align="center" />

'ndrte' is a light-weight parallel computing framework, that is focusing on fast packet processing.
It designed to provide the network developer an easy, efficient, flexible way to create programs which need to send, receive and manipulate network packets.
It runs mostly in linux userland; process task scheduling and memory mapping autonomously to achieve the best performance and low-latency.

*It's inspired by [Intel® Data Plane Development Kit](http://dpdk.org/)*

[![License: MIT (API codes)](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![License: GPL-3.0 (Linux kernel modules)](https://img.shields.io/badge/License-GPL--3.0-green.svg)](https://opensource.org/licenses/GPL-3.0)
[![Release: 1.0.0-rc1](https://img.shields.io/badge/release-v1.0.0--rc1-blue.svg)](https://github.com/openndr/ndrte/releases/tag/v1.0.0-rc1)

## Latest Release
### 1.0.0-rc1
- [Release](https://github.com/openndr/ndrte/releases/tag/v1.0.0-rc1)
- [Change Log]()

## Features
### Light-weight context switching scheduler
* Coroutine like light-weight work unit

### Packet user-space mapping drivers
* SW-implemented Flow Director
* 1-copy skbuff user-mapping (for generic drivers)

## Documentation
Reference [here](https://github.com/openndr/ndrte/wiki)