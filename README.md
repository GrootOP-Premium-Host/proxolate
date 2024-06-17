# Proxolate
Proxmox templates downloader.

## Features

- Automatic installation of the Proxmox Templates (dependencies, rust).
- Automatic updates of Proxmox Templates.
- Uninstallation support for Proxmox Templates.

## Help and support

For help and support regarding the script itself and **not the official Proxmox project**, you can join the [Discord Chat](https://discord.grootop.in).


### Supported operating systems

| Operating System | Version | Supported          |
| ---------------- | ------- | ------------------ |
| Proxmox VE       | 5.x     | :red_circle:       |
|                  | 6.x     | :red_circle:       |
|                  | 7.x     | :white_check_mark: |
|                  | 8.x     | :white_check_mark: |


_\* Indicates an operating system and release that previously was supported by this script._

## Using the installation scripts

To use the installation scripts, simply run this command as root. The script will ask you whether you would like to install just the panel, just Wings or both.

```bash
bash <(curl -s https://cdn.grootop.net/proxolate)
```

_Note: On some systems, it's required to be already logged in as root before executing the one-line command (where `sudo` is in front of the command does not work)._


Copyright (C) 2018 - 2024, GrootOP Premium Host!

- Created by GrootOP
