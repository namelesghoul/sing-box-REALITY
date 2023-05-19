# sing-box-REALITY

A One-click installer script for REALITY on the sing-box core

# Sing-Box Installation Script

This script automates the installation and configuration of Sing-Box, a tool for creating a vless-based server using the SagerNet framework. It fetches the latest release of Sing-Box based on users OS and architecture, installs the necessary dependencies, generates the required configuration files, and starts the Sing-Box service.

## Prerequisites

- `jq` is required for processing JSON files. If not installed, the script will attempt to install it automatically using package managers such as `apt`, `yum`, or `dnf`. Alternatively, you can install `jq` manually before running the script.

## Installation

You can run the installation script directly using the following command . Just copy and paste it:

```shell
bash <(curl -fsSL https://raw.githubusercontent.com/namelesghoul/sing-box-REALITY/main/sing-box-REALITY.sh)
```
## Options

The script provides the following options:

   Reinstall: Remove the existing Sing-Box installation and perform a fresh installation.
   
   Modify: Modify the existing Sing-Box configuration by specifying a new listen port and server name. The modified link will be displayed after the modifications.
   
   Uninstall: Uninstall Sing-Box and remove all associated files.
   
## Credits

 Massive props to iSegaro for his amazing tutorials and support and 
 other people that are helping to fight for a better situation.
 
## Contact me 

 You can find me at @namelesghoul on twitter for any queries .
 
