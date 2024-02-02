# Nmap

## Overview

Nmap is an open-source tool for network exploration and security scanning. It was designed to rapidly scan large networks, although it works fine against single hosts. Nmap uses raw IP packets to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics.

## History

Nmap was first released in September 1997 by Gordon Lyon (also known by his pseudonym Fyodor Vaskovich) as an open-source project. Since its inception, it has become one of the most important tools for network security professionals and researchers. Its development has been driven by a vibrant community contributing to its rich feature set and extensive capabilities.

## Features

- **Host Discovery**: Identifies hosts on a network, such as servers and routers.
- **Port Scanning**: Enumerates the open ports on target hosts.
- **Version Detection**: Determines software and service versions running on the target.
- **OS Detection**: Deduces the operating system and hardware characteristics of network devices.
- **Scriptable Interaction**: Enhances capabilities with Nmap Scripting Engine (NSE) scripts for more advanced discovery and exploitation.

## Getting Started

To get started with Nmap, clone this repository and follow the installation instructions in the documentation. Nmap can be run on Windows, Linux, and macOS, making it accessible to a wide range of users.

```bash
git clone https://github.com/your-nmap-repo.git
cd your-nmap-repo
./configure
make
sudo make install
```

For detailed usage and examples, refer to the official Nmap documentation at [nmap.org](https://nmap.org/).

## Educational Resources

- [Nmap Guide by Fyodor](https://nmap.org/book)
