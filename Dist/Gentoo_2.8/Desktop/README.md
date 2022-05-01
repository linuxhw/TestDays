Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 61

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | MPG Z390 GAMING PRO CARB... | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Dell     | 0J37VM A00                  | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Gigabyte | Z590 UD                     | [b304c37639](https://linux-hardware.org/?probe=b304c37639) | Apr 27, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI      | Z390-A PRO                  | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| ASUSTek  | PRIME H570M-PLUS            | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI      | B450-A PRO MAX              | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| ASUSTek  | ROG Maximus XIII APEX       | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Gigabyte | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASUSTek  | P6X58D-E                    | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek  | TUF Gaming B550-PLUS        | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASRock   | Z170A-X1                    | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI      | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Gigabyte | Z590 UD                     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [f4e6e46fc5](https://linux-hardware.org/?probe=f4e6e46fc5) | Mar 23, 2022 |
| ASUSTek  | ROG STRIX Z370-H GAMING     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI      | MAG B550M MORTAR            | [78b6d2b02e](https://linux-hardware.org/?probe=78b6d2b02e) | Mar 21, 2022 |
| MSI      | MAG B550M MORTAR            | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| ASUSTek  | Z170 PRO GAMING             | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| Dell     | 0J37VM A00                  | [bbcd3639ab](https://linux-hardware.org/?probe=bbcd3639ab) | Mar 15, 2022 |
| ASUSTek  | ROG STRIX Z390-E GAMING     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| Dell     | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Gigabyte | Z590 UD                     | [392c7890c2](https://linux-hardware.org/?probe=392c7890c2) | Mar 08, 2022 |
| ASUSTek  | TUF GAMING X570-PRO         | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte | Z590 UD                     | [06d8d67698](https://linux-hardware.org/?probe=06d8d67698) | Feb 24, 2022 |
| Gigabyte | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Gigabyte | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASRock   | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASRock   | X370 Gaming X               | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| EVGA     | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Gigabyte | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.10-gentoo               | 3        | 6.52%   |
| 5.17.1-gentoo-r1             | 2        | 4.35%   |
| 5.17.0-gentoo                | 2        | 4.35%   |
| 5.16.11-gentoo-x86_64        | 2        | 4.35%   |
| 5.14.13-gentoo               | 2        | 4.35%   |
| 5.14.12-gentoo               | 2        | 4.35%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 2.17%   |
| 5.17.5-gentoo-x86_64         | 1        | 2.17%   |
| 5.17.3-gentoo-11-02-22       | 1        | 2.17%   |
| 5.17.2-gentoo-limelight      | 1        | 2.17%   |
| 5.17.2-gentoo                | 1        | 2.17%   |
| 5.17.1-gentoo-r1-x86_64      | 1        | 2.17%   |
| 5.17.0-gentoo-x86_64         | 1        | 2.17%   |
| 5.16.8-gentoo-x86_64         | 1        | 2.17%   |
| 5.16.7-tkg-cacule            | 1        | 2.17%   |
| 5.16.5-gentoo-dist           | 1        | 2.17%   |
| 5.16.4-gentoo                | 1        | 2.17%   |
| 5.16.2-gentoo                | 1        | 2.17%   |
| 5.16.15                      | 1        | 2.17%   |
| 5.16.14-gentoo-x86_64        | 1        | 2.17%   |
| 5.16.14-gentoo-girlhog       | 1        | 2.17%   |
| 5.16.13-gentoo               | 1        | 2.17%   |
| 5.16.12-gentoo-x86_64        | 1        | 2.17%   |
| 5.16.10-gentoo-x86_64        | 1        | 2.17%   |
| 5.15.6-gentoo                | 1        | 2.17%   |
| 5.15.4-gentoo-deimos         | 1        | 2.17%   |
| 5.15.32-gentoo-r1            | 1        | 2.17%   |
| 5.15.2-gentoo20210917        | 1        | 2.17%   |
| 5.15.2-gentoo-x86_64         | 1        | 2.17%   |
| 5.15.16-gentoo-dist          | 1        | 2.17%   |
| 5.15.1-gentoo-x86_64         | 1        | 2.17%   |
| 5.15.0-gentoo-x86_64         | 1        | 2.17%   |
| 5.14.6                       | 1        | 2.17%   |
| 5.14.15-gentoo20210917       | 1        | 2.17%   |
| 5.14.14-gentoo-x86_64        | 1        | 2.17%   |
| 5.14.14-gentoo               | 1        | 2.17%   |
| 5.14.11-zen1                 | 1        | 2.17%   |
| 5.10.84-gentoo-112-overlayfs | 1        | 2.17%   |
| 5.10.74-gentoo-x86_64        | 1        | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 3        | 6.52%   |
| 5.17.0  | 3        | 6.52%   |
| 5.15.10 | 3        | 6.52%   |
| 5.17.2  | 2        | 4.35%   |
| 5.16.14 | 2        | 4.35%   |
| 5.16.11 | 2        | 4.35%   |
| 5.15.2  | 2        | 4.35%   |
| 5.14.14 | 2        | 4.35%   |
| 5.14.13 | 2        | 4.35%   |
| 5.14.12 | 2        | 4.35%   |
| 6.0.0   | 1        | 2.17%   |
| 5.17.5  | 1        | 2.17%   |
| 5.17.3  | 1        | 2.17%   |
| 5.16.8  | 1        | 2.17%   |
| 5.16.7  | 1        | 2.17%   |
| 5.16.5  | 1        | 2.17%   |
| 5.16.4  | 1        | 2.17%   |
| 5.16.2  | 1        | 2.17%   |
| 5.16.15 | 1        | 2.17%   |
| 5.16.13 | 1        | 2.17%   |
| 5.16.12 | 1        | 2.17%   |
| 5.16.10 | 1        | 2.17%   |
| 5.15.6  | 1        | 2.17%   |
| 5.15.4  | 1        | 2.17%   |
| 5.15.32 | 1        | 2.17%   |
| 5.15.16 | 1        | 2.17%   |
| 5.15.1  | 1        | 2.17%   |
| 5.15.0  | 1        | 2.17%   |
| 5.14.6  | 1        | 2.17%   |
| 5.14.15 | 1        | 2.17%   |
| 5.14.11 | 1        | 2.17%   |
| 5.10.84 | 1        | 2.17%   |
| 5.10.74 | 1        | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 11       | 25.58%  |
| 5.15    | 11       | 25.58%  |
| 5.17    | 9        | 20.93%  |
| 5.14    | 9        | 20.93%  |
| 5.10    | 2        | 4.65%   |
| 6.0     | 1        | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 38       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 17       | 43.59%  |
| Unknown | 9        | 23.08%  |
| GNOME   | 7        | 17.95%  |
| XFCE    | 3        | 7.69%   |
| LXQt    | 1        | 2.56%   |
| KDE     | 1        | 2.56%   |
| DWM     | 1        | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 19       | 48.72%  |
| Wayland | 9        | 23.08%  |
| Tty     | 6        | 15.38%  |
| Unknown | 5        | 12.82%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 43.59%  |
| SDDM    | 15       | 38.46%  |
| GDM     | 4        | 10.26%  |
| SLiM    | 1        | 2.56%   |
| LXDM    | 1        | 2.56%   |
| LightDM | 1        | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 13       | 34.21%  |
| en_GB   | 7        | 18.42%  |
| Unknown | 5        | 13.16%  |
| ru_RU   | 2        | 5.26%   |
| pl_PL   | 2        | 5.26%   |
| C.UTF8  | 2        | 5.26%   |
| sl_SI   | 1        | 2.63%   |
| fr_FR   | 1        | 2.63%   |
| es_ES   | 1        | 2.63%   |
| el_GR   | 1        | 2.63%   |
| de_DE   | 1        | 2.63%   |
| de_CH   | 1        | 2.63%   |
| C       | 1        | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 32       | 82.05%  |
| BIOS | 7        | 17.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 21       | 55.26%  |
| Btrfs | 12       | 31.58%  |
| F2fs  | 2        | 5.26%   |
| Zfs   | 1        | 2.63%   |
| XXX   | 1        | 2.63%   |
| Xfs   | 1        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 35       | 89.74%  |
| Unknown | 4        | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 61.54%  |
| Yes       | 15       | 38.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 65.79%  |
| Yes       | 13       | 34.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 47.37%  |
| MSI                 | 7        | 18.42%  |
| Gigabyte Technology | 6        | 15.79%  |
| ASRock              | 5        | 13.16%  |
| EVGA                | 1        | 2.63%   |
| Dell                | 1        | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS TUF Gaming B550-PLUS         | 2        | 5.26%   |
| MSI MS-7D31                       | 1        | 2.63%   |
| MSI MS-7C94                       | 1        | 2.63%   |
| MSI MS-7C56                       | 1        | 2.63%   |
| MSI MS-7B98                       | 1        | 2.63%   |
| MSI MS-7B86                       | 1        | 2.63%   |
| MSI MS-7B17                       | 1        | 2.63%   |
| MSI MS-7996                       | 1        | 2.63%   |
| Gigabyte Z87X-UD3H                | 1        | 2.63%   |
| Gigabyte Z590 UD                  | 1        | 2.63%   |
| Gigabyte Z490 UD                  | 1        | 2.63%   |
| Gigabyte X570 AORUS MASTER        | 1        | 2.63%   |
| Gigabyte H470 HD3                 | 1        | 2.63%   |
| Gigabyte B450M S2H                | 1        | 2.63%   |
| EVGA Z390 DARK                    | 1        | 2.63%   |
| Dell OptiPlex 7080                | 1        | 2.63%   |
| ASUS Z170-A                       | 1        | 2.63%   |
| ASUS Z170 PRO GAMING              | 1        | 2.63%   |
| ASUS TUF GAMING X570-PRO          | 1        | 2.63%   |
| ASUS TUF B450-PLUS GAMING         | 1        | 2.63%   |
| ASUS ROG ZENITH II EXTREME        | 1        | 2.63%   |
| ASUS ROG STRIX Z390-E GAMING      | 1        | 2.63%   |
| ASUS ROG STRIX Z370-H GAMING      | 1        | 2.63%   |
| ASUS ROG STRIX X570-E GAMING      | 1        | 2.63%   |
| ASUS ROG STRIX B550-F GAMING      | 1        | 2.63%   |
| ASUS ROG Maximus XIII APEX        | 1        | 2.63%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 2.63%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 2.63%   |
| ASUS PRIME X570-P                 | 1        | 2.63%   |
| ASUS PRIME H570M-PLUS             | 1        | 2.63%   |
| ASUS P6X58D-E                     | 1        | 2.63%   |
| ASUS P5LD2-Deluxe                 | 1        | 2.63%   |
| ASRock Z170A-X1                   | 1        | 2.63%   |
| ASRock X370 Killer SLI/ac         | 1        | 2.63%   |
| ASRock X370 Gaming X              | 1        | 2.63%   |
| ASRock H110M-HDV R3.0             | 1        | 2.63%   |
| ASRock AB350M Pro4                | 1        | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 8        | 21.05%  |
| ASUS TUF           | 4        | 10.53%  |
| ASUS PRIME         | 2        | 5.26%   |
| ASRock X370        | 2        | 5.26%   |
| MSI MS-7D31        | 1        | 2.63%   |
| MSI MS-7C94        | 1        | 2.63%   |
| MSI MS-7C56        | 1        | 2.63%   |
| MSI MS-7B98        | 1        | 2.63%   |
| MSI MS-7B86        | 1        | 2.63%   |
| MSI MS-7B17        | 1        | 2.63%   |
| MSI MS-7996        | 1        | 2.63%   |
| Gigabyte Z87X-UD3H | 1        | 2.63%   |
| Gigabyte Z590      | 1        | 2.63%   |
| Gigabyte Z490      | 1        | 2.63%   |
| Gigabyte X570      | 1        | 2.63%   |
| Gigabyte H470      | 1        | 2.63%   |
| Gigabyte B450M     | 1        | 2.63%   |
| EVGA Z390          | 1        | 2.63%   |
| Dell OptiPlex      | 1        | 2.63%   |
| ASUS Z170-A        | 1        | 2.63%   |
| ASUS Z170          | 1        | 2.63%   |
| ASUS P6X58D-E      | 1        | 2.63%   |
| ASUS P5LD2-Deluxe  | 1        | 2.63%   |
| ASRock Z170A-X1    | 1        | 2.63%   |
| ASRock H110M-HDV   | 1        | 2.63%   |
| ASRock AB350M      | 1        | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 10       | 26.32%  |
| 2019 | 6        | 15.79%  |
| 2021 | 5        | 13.16%  |
| 2018 | 4        | 10.53%  |
| 2017 | 4        | 10.53%  |
| 2016 | 3        | 7.89%   |
| 2015 | 2        | 5.26%   |
| 2022 | 1        | 2.63%   |
| 2013 | 1        | 2.63%   |
| 2010 | 1        | 2.63%   |
| 2005 | 1        | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 38       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 37       | 97.37%  |
| Enabled  | 1        | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 13       | 34.21%  |
| 64.01-256.0 | 10       | 26.32%  |
| 16.01-24.0  | 9        | 23.68%  |
| 24.01-32.0  | 3        | 7.89%   |
| 8.01-16.0   | 2        | 5.26%   |
| 2.01-3.0    | 1        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 15       | 35.71%  |
| 8.01-16.0  | 10       | 23.81%  |
| 1.01-2.0   | 6        | 14.29%  |
| 2.01-3.0   | 4        | 9.52%   |
| 16.01-24.0 | 3        | 7.14%   |
| 3.01-4.0   | 2        | 4.76%   |
| 24.01-32.0 | 1        | 2.38%   |
| 0.51-1.0   | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 9        | 23.08%  |
| 2      | 9        | 23.08%  |
| 5      | 8        | 20.51%  |
| 4      | 5        | 12.82%  |
| 1      | 4        | 10.26%  |
| 7      | 2        | 5.13%   |
| 6      | 2        | 5.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 86.84%  |
| Yes       | 5        | 13.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 97.37%  |
| No        | 1        | 2.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 57.89%  |
| Yes       | 16       | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 51.28%  |
| No        | 19       | 48.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 28.95%  |
| Russia      | 4        | 10.53%  |
| Poland      | 4        | 10.53%  |
| UK          | 2        | 5.26%   |
| Switzerland | 2        | 5.26%   |
| Spain       | 2        | 5.26%   |
| Germany     | 2        | 5.26%   |
| Slovenia    | 1        | 2.63%   |
| Mexico      | 1        | 2.63%   |
| Malaysia    | 1        | 2.63%   |
| Ireland     | 1        | 2.63%   |
| Hong Kong   | 1        | 2.63%   |
| Greece      | 1        | 2.63%   |
| France      | 1        | 2.63%   |
| Czechia     | 1        | 2.63%   |
| Canada      | 1        | 2.63%   |
| Bangladesh  | 1        | 2.63%   |
| Australia   | 1        | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 2        | 5.13%   |
| Swansea           | 2        | 5.13%   |
| Moscow            | 2        | 5.13%   |
| Los Angeles       | 2        | 5.13%   |
| Vigo              | 1        | 2.56%   |
| Ufa               | 1        | 2.56%   |
| Sydney            | 1        | 2.56%   |
| Svobodnyy         | 1        | 2.56%   |
| St Louis          | 1        | 2.56%   |
| RzeszÃ³w        | 1        | 2.56%   |
| Redmond           | 1        | 2.56%   |
| Prague            | 1        | 2.56%   |
| Orange            | 1        | 2.56%   |
| Ocala             | 1        | 2.56%   |
| Morcenx           | 1        | 2.56%   |
| Monroe            | 1        | 2.56%   |
| Laziska Gorne     | 1        | 2.56%   |
| Kulmbach          | 1        | 2.56%   |
| Kuala Lumpur      | 1        | 2.56%   |
| Krakow            | 1        | 2.56%   |
| IvanÄna Gorica | 1        | 2.56%   |
| Hyannis           | 1        | 2.56%   |
| Houston           | 1        | 2.56%   |
| Glen Ellyn        | 1        | 2.56%   |
| Fort Collins      | 1        | 2.56%   |
| Essen             | 1        | 2.56%   |
| Dublin            | 1        | 2.56%   |
| Dhaka             | 1        | 2.56%   |
| Ciudad JuÃ¡rez  | 1        | 2.56%   |
| Cieszyn           | 1        | 2.56%   |
| Central           | 1        | 2.56%   |
| Boucherville      | 1        | 2.56%   |
| Blagoveshchensk   | 1        | 2.56%   |
| Bellaterra        | 1        | 2.56%   |
| Athens            | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 37     | 21.28%  |
| Samsung Electronics | 20       | 40     | 21.28%  |
| Seagate             | 12       | 20     | 12.77%  |
| Toshiba             | 5        | 6      | 5.32%   |
| SanDisk             | 4        | 5      | 4.26%   |
| Hitachi             | 4        | 6      | 4.26%   |
| Crucial             | 4        | 10     | 4.26%   |
| Corsair             | 4        | 5      | 4.26%   |
| Kingston            | 3        | 3      | 3.19%   |
| Intel               | 3        | 4      | 3.19%   |
| A-DATA Technology   | 3        | 4      | 3.19%   |
| KIOXIA-EXCERIA      | 2        | 3      | 2.13%   |
| Team                | 1        | 2      | 1.06%   |
| SK Hynix            | 1        | 2      | 1.06%   |
| PNY                 | 1        | 1      | 1.06%   |
| PLEXTOR             | 1        | 2      | 1.06%   |
| Phison              | 1        | 1      | 1.06%   |
| OCZ-VERTEX          | 1        | 1      | 1.06%   |
| LaCie               | 1        | 1      | 1.06%   |
| Kingchuxing         | 1        | 2      | 1.06%   |
| HGST                | 1        | 1      | 1.06%   |
| GOODRAM             | 1        | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2        | 1.61%   |
| WDC WD10EZEX-08M2NA0 1TB                   | 2        | 1.61%   |
| Toshiba DT01ACA100 1TB                     | 2        | 1.61%   |
| Seagate ST4000DM005-2DP166 4TB             | 2        | 1.61%   |
| Seagate ST2000DM001-1ER164 2TB             | 2        | 1.61%   |
| Samsung SSD 980 PRO 2TB                    | 2        | 1.61%   |
| Samsung SSD 980 PRO 1TB                    | 2        | 1.61%   |
| Samsung SSD 980 1TB                        | 2        | 1.61%   |
| Samsung SSD 970 EVO Plus 2TB               | 2        | 1.61%   |
| Samsung SSD 970 EVO Plus 250GB             | 2        | 1.61%   |
| Samsung NVMe SSD Drive 512GB               | 2        | 1.61%   |
| Hitachi HDS723020BLA642 2TB                | 2        | 1.61%   |
| Crucial CT2000MX500SSD1 2TB                | 2        | 1.61%   |
| Crucial CT1000MX500SSD1 1TB                | 2        | 1.61%   |
| A-DATA SX8200PNP 512GB                     | 2        | 1.61%   |
| A-DATA SX8200PNP 1TB                       | 2        | 1.61%   |
| WDC WDS500G2X0C-00L350 500GB               | 1        | 0.81%   |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1        | 0.81%   |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1        | 0.81%   |
| WDC WDS240G2G0A 240GB SSD                  | 1        | 0.81%   |
| WDC WDS100T2B0A-00SM50 1TB SSD             | 1        | 0.81%   |
| WDC WD8003FFBX-68B9AN0 8TB                 | 1        | 0.81%   |
| WDC WD60EZRX-00MVLB1 6TB                   | 1        | 0.81%   |
| WDC WD60EFRX-68L0BN1 6TB                   | 1        | 0.81%   |
| WDC WD5000AZLX-00JKKA0 500GB               | 1        | 0.81%   |
| WDC WD40EZRZ-00GXCB0 4TB                   | 1        | 0.81%   |
| WDC WD30EFRX-68AX9N0 3TB                   | 1        | 0.81%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 0.81%   |
| WDC WD20EZAZ-00GGJB0 2TB                   | 1        | 0.81%   |
| WDC WD20EFRX-68EUZN0 2TB                   | 1        | 0.81%   |
| WDC WD2003FZEX-00Z4SA0 2TB                 | 1        | 0.81%   |
| WDC WD2003FYYS-18W0B0 2TB                  | 1        | 0.81%   |
| WDC WD10PURX-64E5EY0 1TB                   | 1        | 0.81%   |
| WDC WD10EZEX-60WN4A1 1TB                   | 1        | 0.81%   |
| WDC WD10EZEX-22M                           | 1        | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 0.81%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 0.81%   |
| WDC WD10EADS-00L5B1 1TB                    | 1        | 0.81%   |
| WDC WD1002FBYS-18W8B0 1TB                  | 1        | 0.81%   |
| WDC WD1001FALS-00J7B1 1TB                  | 1        | 0.81%   |
| Toshiba TR200 480GB SSD                    | 1        | 0.81%   |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1        | 0.81%   |
| Toshiba HDWQ140 4TB                        | 1        | 0.81%   |
| Team TM8FP2240G 240GB                      | 1        | 0.81%   |
| SK Hynix PC611 NVMe 512GB                  | 1        | 0.81%   |
| Seagate ST8000DM004-2CX188 8TB             | 1        | 0.81%   |
| Seagate ST6000VN0033-2EE110 6TB            | 1        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 0.81%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 0.81%   |
| Seagate ST4000DM000-1F2168 4TB             | 1        | 0.81%   |
| Seagate ST3500630AS 500GB                  | 1        | 0.81%   |
| Seagate ST3250318AS 250GB                  | 1        | 0.81%   |
| Seagate ST3160023AS 160GB                  | 1        | 0.81%   |
| Seagate ST2000LX001-1RG174 2TB             | 1        | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB             | 1        | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB             | 1        | 0.81%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 0.81%   |
| SanDisk Ultra II 480GB SSD                 | 1        | 0.81%   |
| SanDisk SSD PLUS 240GB                     | 1        | 0.81%   |
| SanDisk SSD PLUS 1000GB                    | 1        | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 17       | 32     | 45.95%  |
| Seagate | 11       | 19     | 29.73%  |
| Hitachi | 4        | 6      | 10.81%  |
| Toshiba | 3        | 3      | 8.11%   |
| LaCie   | 1        | 1      | 2.7%    |
| HGST    | 1        | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 33.33%  |
| WDC                 | 4        | 4      | 12.12%  |
| SanDisk             | 4        | 5      | 12.12%  |
| Kingston            | 3        | 3      | 9.09%   |
| Crucial             | 3        | 8      | 9.09%   |
| Corsair             | 3        | 4      | 9.09%   |
| Toshiba             | 1        | 2      | 3.03%   |
| PNY                 | 1        | 1      | 3.03%   |
| OCZ-VERTEX          | 1        | 1      | 3.03%   |
| Intel               | 1        | 1      | 3.03%   |
| GOODRAM             | 1        | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 27       | 51     | 34.18%  |
| SSD  | 26       | 44     | 32.91%  |
| HDD  | 26       | 62     | 32.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 105    | 55.56%  |
| NVMe | 27       | 51     | 42.86%  |
| SAS  | 1        | 1      | 1.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 33     | 31.67%  |
| 0.51-1.0   | 16       | 24     | 26.67%  |
| 1.01-2.0   | 14       | 22     | 23.33%  |
| 3.01-4.0   | 6        | 9      | 10%     |
| 4.01-10.0  | 3        | 13     | 5%      |
| 2.01-3.0   | 2        | 5      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 9        | 23.08%  |
| More than 3000 | 8        | 20.51%  |
| 2001-3000      | 6        | 15.38%  |
| 1001-2000      | 6        | 15.38%  |
| 251-500        | 5        | 12.82%  |
| 1-20           | 2        | 5.13%   |
| 101-250        | 1        | 2.56%   |
| 51-100         | 1        | 2.56%   |
| Unknown        | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 25%     |
| 1001-2000      | 6        | 15%     |
| More than 3000 | 5        | 12.5%   |
| 501-1000       | 4        | 10%     |
| 51-100         | 4        | 10%     |
| 21-50          | 3        | 7.5%    |
| 101-250        | 3        | 7.5%    |
| 1-20           | 3        | 7.5%    |
| 2001-3000      | 1        | 2.5%    |
| Unknown        | 1        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB        | 1        | 3      | 9.09%   |
| WDC WD30EFRX-68AX9N0 3TB        | 1        | 2      | 9.09%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 1      | 9.09%   |
| WDC WD1002FBYS-18W8B0 1TB       | 1        | 1      | 9.09%   |
| Seagate ST3160023AS 160GB       | 1        | 1      | 9.09%   |
| SanDisk SSD PLUS 1000GB         | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB | 1        | 1      | 9.09%   |
| Kingston SV100S2128G 128GB SSD  | 1        | 1      | 9.09%   |
| Hitachi HUA721010KLA330 1TB     | 1        | 1      | 9.09%   |
| Hitachi HDS722020ALA330 2TB     | 1        | 2      | 9.09%   |
| Crucial CT525MX300SSD1 528GB    | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 36.36%  |
| Hitachi             | 2        | 3      | 18.18%  |
| Seagate             | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Kingston            | 1        | 1      | 9.09%   |
| Crucial             | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 57.14%  |
| Hitachi | 2        | 3      | 28.57%  |
| Seagate | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 11     | 55.56%  |
| SSD  | 3        | 3      | 33.33%  |
| NVMe | 1        | 1      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 35       | 126    | 71.43%  |
| Malfunc  | 9        | 15     | 18.37%  |
| Detected | 4        | 15     | 8.16%   |
| Failed   | 1        | 1      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 20       | 27.03%  |
| AMD                            | 18       | 24.32%  |
| Samsung Electronics            | 15       | 20.27%  |
| ASMedia Technology             | 4        | 5.41%   |
| Phison Electronics             | 3        | 4.05%   |
| ADATA Technology               | 3        | 4.05%   |
| KIOXIA                         | 2        | 2.7%    |
| Toshiba America Info Systems   | 1        | 1.35%   |
| Solid State Storage Technology | 1        | 1.35%   |
| SK Hynix                       | 1        | 1.35%   |
| Silicon Motion                 | 1        | 1.35%   |
| Silicon Image                  | 1        | 1.35%   |
| Seagate Technology             | 1        | 1.35%   |
| Sandisk                        | 1        | 1.35%   |
| Micron/Crucial Technology      | 1        | 1.35%   |
| Marvell Technology Group       | 1        | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13       | 15.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 11.9%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5        | 5.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 5.95%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 5.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 4.76%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 4.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 3.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 3.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 3.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 3.57%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 2.38%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 2.38%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 2.38%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 1.19%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 1.19%   |
| SK Hynix Non-Volatile memory controller                                        | 1        | 1.19%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.19%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.19%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 1.19%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.19%   |
| Phison E7 NVMe Controller                                                      | 1        | 1.19%   |
| Micron/Crucial NVMe Controller                                                 | 1        | 1.19%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.19%   |
| KIOXIA NVMe SSD                                                                | 1        | 1.19%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 1.19%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 1.19%   |
| Intel Optane SSD 900P Series                                                   | 1        | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.19%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.19%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 56.06%  |
| NVMe | 27       | 40.91%  |
| RAID | 1        | 1.52%   |
| IDE  | 1        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 52.63%  |
| AMD    | 18       | 47.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 3950X 16-Core Processor            | 3        | 7.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 5.26%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 5.26%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 2        | 5.26%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 5.26%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 5.26%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 5.26%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 5.26%   |
| Intel Xeon CPU X5690 @ 3.47GHz                 | 1        | 2.63%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 2.63%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 2.63%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 2.63%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 2.63%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 2.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 2.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 2.63%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 2.63%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 1        | 2.63%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 2.63%   |
| Intel 12th Gen Core i7-12700K                  | 1        | 2.63%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz        | 1        | 2.63%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 2.63%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 2.63%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 2.63%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 2.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 2.63%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 2.63%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 2.63%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 8        | 21.05%  |
| AMD Ryzen 9            | 8        | 21.05%  |
| Intel Core i7          | 5        | 13.16%  |
| AMD Ryzen 5            | 5        | 13.16%  |
| Other                  | 3        | 7.89%   |
| AMD Ryzen 7            | 3        | 7.89%   |
| Intel Core i9          | 2        | 5.26%   |
| Intel Xeon             | 1        | 2.63%   |
| Intel Pentium 4        | 1        | 2.63%   |
| AMD Ryzen Threadripper | 1        | 2.63%   |
| AMD Ryzen 7 PRO        | 1        | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 11       | 28.95%  |
| 8      | 10       | 26.32%  |
| 4      | 6        | 15.79%  |
| 16     | 5        | 13.16%  |
| 12     | 4        | 10.53%  |
| 24     | 1        | 2.63%   |
| 1      | 1        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 81.58%  |
| 1      | 7        | 18.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 17.95%  |
| 0x08701021 | 5        | 12.82%  |
| 0x906ed    | 3        | 7.69%   |
| 0x506e3    | 3        | 7.69%   |
| 0x0a201016 | 3        | 7.69%   |
| 0x08001138 | 3        | 7.69%   |
| 0xa0655    | 2        | 5.13%   |
| 0xa0653    | 2        | 5.13%   |
| 0xf43      | 1        | 2.56%   |
| 0xa0671    | 1        | 2.56%   |
| 0x906ec    | 1        | 2.56%   |
| 0x906e9    | 1        | 2.56%   |
| 0x90672    | 1        | 2.56%   |
| 0x206c2    | 1        | 2.56%   |
| 0x0a50000c | 1        | 2.56%   |
| 0x0a50000b | 1        | 2.56%   |
| 0x0a201205 | 1        | 2.56%   |
| 0x08301039 | 1        | 2.56%   |
| 0x0800820d | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 7        | 18.42%  |
| Zen 3            | 6        | 15.79%  |
| KabyLake         | 6        | 15.79%  |
| Skylake          | 4        | 10.53%  |
| CometLake        | 4        | 10.53%  |
| Zen              | 3        | 7.89%   |
| Zen+             | 2        | 5.26%   |
| Westmere         | 1        | 2.63%   |
| NetBurst         | 1        | 2.63%   |
| Icelake          | 1        | 2.63%   |
| Haswell          | 1        | 2.63%   |
| Alderlake Hybrid | 1        | 2.63%   |
| Unknown          | 1        | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 20       | 45.45%  |
| Nvidia | 17       | 38.64%  |
| Intel  | 7        | 15.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 9        | 19.57%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 3        | 6.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 2        | 4.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 2        | 4.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                            | 2        | 4.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 2        | 4.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 1        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 2.17%   |
| Nvidia TU106 [GeForce RTX 2070]                                     | 1        | 2.17%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                              | 1        | 2.17%   |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 2.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                 | 1        | 2.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                     | 1        | 2.17%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 1        | 2.17%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 2.17%   |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 2.17%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                  | 1        | 2.17%   |
| Nvidia GA106 [Geforce RTX 3050]                                     | 1        | 2.17%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                  | 1        | 2.17%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                  | 1        | 2.17%   |
| Intel HD Graphics 630                                               | 1        | 2.17%   |
| Intel HD Graphics 530                                               | 1        | 2.17%   |
| Intel AlderLake-S GT1                                               | 1        | 2.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 1        | 2.17%   |
| AMD Turks PRO [Radeon HD 7570]                                      | 1        | 2.17%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                      | 1        | 2.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                | 1        | 2.17%   |
| AMD Ellesmere [Radeon Pro WX 7100]                                  | 1        | 2.17%   |
| AMD Cezanne                                                         | 1        | 2.17%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                | 1        | 2.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 2.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 15       | 39.47%  |
| 1 x Nvidia     | 13       | 34.21%  |
| 1 x Intel      | 3        | 7.89%   |
| AMD + Nvidia   | 3        | 7.89%   |
| Other          | 1        | 2.63%   |
| 2 x AMD        | 1        | 2.63%   |
| Intel + Nvidia | 1        | 2.63%   |
| Intel + AMD    | 1        | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 57.89%  |
| Proprietary | 14       | 36.84%  |
| Unknown     | 2        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 11       | 27.5%   |
| Unknown    | 11       | 27.5%   |
| 8.01-16.0  | 7        | 17.5%   |
| 3.01-4.0   | 4        | 10%     |
| 5.01-6.0   | 2        | 5%      |
| 1.01-2.0   | 2        | 5%      |
| 0.51-1.0   | 2        | 5%      |
| 2.01-3.0   | 1        | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 5        | 9.8%    |
| Goldstar                | 5        | 9.8%    |
| Hewlett-Packard         | 4        | 7.84%   |
| Lenovo                  | 3        | 5.88%   |
| Dell                    | 3        | 5.88%   |
| AOC                     | 3        | 5.88%   |
| Acer                    | 3        | 5.88%   |
| Philips                 | 2        | 3.92%   |
| BenQ                    | 2        | 3.92%   |
| ASUSTek Computer        | 2        | 3.92%   |
| Ancor Communications    | 2        | 3.92%   |
| ViewSonic               | 1        | 1.96%   |
| Valve                   | 1        | 1.96%   |
| Toshiba                 | 1        | 1.96%   |
| Onkyo                   | 1        | 1.96%   |
| NEC Computers           | 1        | 1.96%   |
| MStar                   | 1        | 1.96%   |
| Microstep               | 1        | 1.96%   |
| Mi                      | 1        | 1.96%   |
| LYC                     | 1        | 1.96%   |
| KTC                     | 1        | 1.96%   |
| Iiyama                  | 1        | 1.96%   |
| HannStar                | 1        | 1.96%   |
| Gigabyte Technology     | 1        | 1.96%   |
| Gateway                 | 1        | 1.96%   |
| Chi Mei Optoelectronics | 1        | 1.96%   |
| Belinea                 | 1        | 1.96%   |
| Unknown                 | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 2        | 3.57%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 2        | 3.57%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch             | 1        | 1.79%   |
| Valve Index HMD VLV91A8                                                | 1        | 1.79%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1        | 1.79%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch   | 1        | 1.79%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1        | 1.79%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1        | 1.79%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1        | 1.79%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1        | 1.79%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.79%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch                | 1        | 1.79%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1        | 1.79%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1        | 1.79%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1        | 1.79%   |
| Microstep LCD Monitor MSI MPG27CQ 2560x1440                            | 1        | 1.79%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 1.79%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                        | 1        | 1.79%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1        | 1.79%   |
| Lenovo M14t LEN62A3 1920x1080 309x174mm 14.0-inch                      | 1        | 1.79%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch               | 1        | 1.79%   |
| KTC Q2711SH KTC2700 2560x1440 597x336mm 27.0-inch                      | 1        | 1.79%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 1        | 1.79%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 1        | 1.79%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1        | 1.79%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1        | 1.79%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch             | 1        | 1.79%   |
| Hewlett-Packard 24mq HPN366F 2560x1440 527x296mm 23.8-inch             | 1        | 1.79%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch             | 1        | 1.79%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1        | 1.79%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 1        | 1.79%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 1        | 1.79%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1        | 1.79%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1        | 1.79%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1        | 1.79%   |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                      | 1        | 1.79%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                      | 1        | 1.79%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1        | 1.79%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                      | 1        | 1.79%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1        | 1.79%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1        | 1.79%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1        | 1.79%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1        | 1.79%   |
| ASUSTek Computer XG27WQ AUS2724 2560x1440 597x336mm 27.0-inch          | 1        | 1.79%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 597x336mm 27.0-inch           | 1        | 1.79%   |
| AOC 2757M AOC2757 1920x1080 598x336mm 27.0-inch                        | 1        | 1.79%   |
| AOC 2437 AOC2437 1920x1080 521x293mm 23.5-inch                         | 1        | 1.79%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 1.79%   |
| Ancor Communications VN279 ACI27A4 1920x1080 597x336mm 27.0-inch       | 1        | 1.79%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 1.79%   |
| Acer VG270U P ACR06CF 2560x1440 597x336mm 27.0-inch                    | 1        | 1.79%   |
| Acer T231H ACR0184 1920x1080 510x287mm 23.0-inch                       | 1        | 1.79%   |
| Acer K272HUL ACR03DD 2560x1440 597x336mm 27.0-inch                     | 1        | 1.79%   |
| Unknown                                                                | 1        | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 2560x1440 (QHD)    | 16       | 33.33%  |
| 1920x1080 (FHD)    | 15       | 31.25%  |
| 3840x2160 (4K)     | 5        | 10.42%  |
| 3440x1440          | 3        | 6.25%   |
| 1280x1024 (SXGA)   | 2        | 4.17%   |
| 3840x1080          | 1        | 2.08%   |
| 2560x1080          | 1        | 2.08%   |
| 1920x1200 (WUXGA)  | 1        | 2.08%   |
| 1680x1050 (WSXGA+) | 1        | 2.08%   |
| 1440x900 (WXGA+)   | 1        | 2.08%   |
| 1366x768 (WXGA)    | 1        | 2.08%   |
| Unknown            | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 17       | 32.69%  |
| 23      | 9        | 17.31%  |
| 34      | 4        | 7.69%   |
| 24      | 3        | 5.77%   |
| 21      | 3        | 5.77%   |
| Unknown | 3        | 5.77%   |
| 49      | 2        | 3.85%   |
| 25      | 2        | 3.85%   |
| 19      | 2        | 3.85%   |
| 17      | 2        | 3.85%   |
| 31      | 1        | 1.92%   |
| 28      | 1        | 1.92%   |
| 20      | 1        | 1.92%   |
| 15      | 1        | 1.92%   |
| 14      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 53.19%  |
| 401-500     | 5        | 10.64%  |
| 701-800     | 4        | 8.51%   |
| 301-350     | 4        | 8.51%   |
| 601-700     | 3        | 6.38%   |
| Unknown     | 3        | 6.38%   |
| 1001-1500   | 2        | 4.26%   |
| 351-400     | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 28       | 66.67%  |
| 21/9    | 4        | 9.52%   |
| 16/10   | 4        | 9.52%   |
| Unknown | 3        | 7.14%   |
| 5/4     | 2        | 4.76%   |
| 32/9    | 1        | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 17       | 33.33%  |
| 201-250        | 12       | 23.53%  |
| 351-500        | 6        | 11.76%  |
| 151-200        | 4        | 7.84%   |
| 251-300        | 3        | 5.88%   |
| Unknown        | 3        | 5.88%   |
| 141-150        | 2        | 3.92%   |
| More than 1000 | 1        | 1.96%   |
| 81-90          | 1        | 1.96%   |
| 101-110        | 1        | 1.96%   |
| 501-1000       | 1        | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 18       | 40%     |
| 51-100  | 17       | 37.78%  |
| 121-160 | 4        | 8.89%   |
| Unknown | 3        | 6.67%   |
| 161-240 | 2        | 4.44%   |
| 1-50    | 1        | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 51.28%  |
| 2     | 12       | 30.77%  |
| 0     | 3        | 7.69%   |
| 4     | 2        | 5.13%   |
| 3     | 2        | 5.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 24       | 47.06%  |
| Realtek Semiconductor    | 16       | 31.37%  |
| Aquantia                 | 3        | 5.88%   |
| Marvell Technology Group | 2        | 3.92%   |
| Raspberry Pi             | 1        | 1.96%   |
| Ralink Technology        | 1        | 1.96%   |
| Qualcomm Atheros         | 1        | 1.96%   |
| Microsoft                | 1        | 1.96%   |
| MEDIATEK                 | 1        | 1.96%   |
| Broadcom                 | 1        | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 12.31%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 10.77%  |
| Intel Wi-Fi 6 AX200                                               | 5        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 5        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 4        | 6.15%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 6.15%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 6.15%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 4.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 3.08%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.54%   |
| Raspberry Pi Pico                                                 | 1        | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.54%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.54%   |
| Microsoft XBOX ACC                                                | 1        | 1.54%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                     | 1        | 1.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.54%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.54%   |
| Intel Wireless-AC 9260                                            | 1        | 1.54%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.54%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.54%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.54%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 64.71%  |
| Realtek Semiconductor | 1        | 5.88%   |
| Ralink Technology     | 1        | 5.88%   |
| Qualcomm Atheros      | 1        | 5.88%   |
| Microsoft             | 1        | 5.88%   |
| MEDIATEK              | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 5        | 27.78%  |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 11.11%  |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 5.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 5.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 5.56%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 5.56%   |
| Microsoft XBOX ACC                                         | 1        | 5.56%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                              | 1        | 5.56%   |
| Intel Wireless-AC 9260                                     | 1        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 5.56%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 5.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 5.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 22       | 51.16%  |
| Realtek Semiconductor    | 16       | 37.21%  |
| Aquantia                 | 3        | 6.98%   |
| Marvell Technology Group | 2        | 4.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 17.39%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 15.22%  |
| Intel I211 Gigabit Network Connection                             | 5        | 10.87%  |
| Intel Ethernet Controller I225-V                                  | 4        | 8.7%    |
| Intel Ethernet Connection (7) I219-V                              | 4        | 8.7%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 8.7%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 6.52%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.17%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.17%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.17%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.17%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 2.17%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.17%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 69.81%  |
| WiFi     | 15       | 28.3%   |
| Modem    | 1        | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 78.05%  |
| WiFi     | 9        | 21.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 50%     |
| 2     | 11       | 28.95%  |
| 3     | 7        | 18.42%  |
| 0     | 1        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 73.68%  |
| Yes  | 10       | 26.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 13       | 65%     |
| Cambridge Silicon Radio | 4        | 20%     |
| Realtek Semiconductor   | 1        | 5%      |
| MediaTek                | 1        | 5%      |
| ASUSTek Computer        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 6        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 20%     |
| Intel Bluetooth Device                              | 2        | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 10%     |
| Realtek Bluetooth Radio                             | 1        | 5%      |
| MediaTek Wireless_Device                            | 1        | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 26       | 29.55%  |
| Intel                                | 18       | 20.45%  |
| Nvidia                               | 17       | 19.32%  |
| Thesycon Systemsoftware & Consulting | 3        | 3.41%   |
| ASUSTek Computer                     | 3        | 3.41%   |
| Yamaha                               | 2        | 2.27%   |
| Logitech                             | 2        | 2.27%   |
| Creative Labs                        | 2        | 2.27%   |
| C-Media Electronics                  | 2        | 2.27%   |
| AudioQuest                           | 2        | 2.27%   |
| Valve Software                       | 1        | 1.14%   |
| SteelSeries ApS                      | 1        | 1.14%   |
| Sony                                 | 1        | 1.14%   |
| Sennheiser Communications            | 1        | 1.14%   |
| SAVITECH                             | 1        | 1.14%   |
| RODE Microphones                     | 1        | 1.14%   |
| Razer USA                            | 1        | 1.14%   |
| JMTek                                | 1        | 1.14%   |
| Generalplus Technology               | 1        | 1.14%   |
| FiiO Electronics Technology          | 1        | 1.14%   |
| Creative Technology                  | 1        | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 10       | 9.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 10       | 9.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 5        | 4.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 5        | 4.95%   |
| Intel Cannon Lake PCH cAVS                                              | 4        | 3.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 4        | 3.96%   |
| Thesycon Systemsoftware & Consulting D10s                               | 3        | 2.97%   |
| Nvidia GP106 High Definition Audio Controller                           | 3        | 2.97%   |
| Intel Comet Lake PCH cAVS                                               | 3        | 2.97%   |
| Nvidia TU106 High Definition Audio Controller                           | 2        | 1.98%   |
| Nvidia TU102 High Definition Audio Controller                           | 2        | 1.98%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 2        | 1.98%   |
| ASUSTek Computer USB Audio                                              | 2        | 1.98%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 2        | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                  | 2        | 1.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2        | 1.98%   |
| Yamaha Steinberg UR22mkII                                               | 1        | 0.99%   |
| Yamaha Steinberg UR22C                                                  | 1        | 0.99%   |
| Valve Software Valve VR Radio & HMD Mic                                 | 1        | 0.99%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1        | 0.99%   |
| Sony DualShock 4 [CUH-ZCT2x]                                            | 1        | 0.99%   |
| Sennheiser Communications GSX 1200 Pro Main Audio                       | 1        | 0.99%   |
| SAVITECH SA9023 audio controller                                        | 1        | 0.99%   |
| RODE Microphones RODE VideoMic NTG                                      | 1        | 0.99%   |
| Razer USA Kraken Tournament Edition                                     | 1        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1        | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GK110 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GA104 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia GA102 High Definition Audio Controller                           | 1        | 0.99%   |
| Nvidia Audio device                                                     | 1        | 0.99%   |
| Logitech Z-5 Speakers                                                   | 1        | 0.99%   |
| Logitech Yeti X                                                         | 1        | 0.99%   |
| JMTek USB PnP Audio Device                                              | 1        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 0.99%   |
| Intel Audio device                                                      | 1        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 1        | 0.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1        | 0.99%   |
| Intel 200 Series PCH HD Audio                                           | 1        | 0.99%   |
| Generalplus Technology USB Audio Device                                 | 1        | 0.99%   |
| FiiO Electronics Technology K3                                          | 1        | 0.99%   |
| Creative Technology Sound BlasterX G6                                   | 1        | 0.99%   |
| C-Media Electronics USB Advanced Audio Device                           | 1        | 0.99%   |
| C-Media Electronics CM108 Audio Controller                              | 1        | 0.99%   |
| AudioQuest SDAC                                                         | 1        | 0.99%   |
| AudioQuest DragonFly Red                                                | 1        | 0.99%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1        | 0.99%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                              | 1        | 0.99%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]               | 1        | 0.99%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                      | 1        | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 10       | 26.32%  |
| Kingston            | 9        | 23.68%  |
| Crucial             | 9        | 23.68%  |
| Corsair             | 3        | 7.89%   |
| Unknown             | 2        | 5.26%   |
| Team                | 1        | 2.63%   |
| Samsung Electronics | 1        | 2.63%   |
| Patriot             | 1        | 2.63%   |
| Micron Technology   | 1        | 2.63%   |
| A-DATA Technology   | 1        | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1        | 2.38%   |
| Unknown RAM Module 512MB DIMM SDRAM                         | 1        | 2.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1        | 2.38%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1        | 2.38%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s        | 1        | 2.38%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 1        | 2.38%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s          | 1        | 2.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s        | 1        | 2.38%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 2.38%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s         | 1        | 2.38%   |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s      | 1        | 2.38%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s        | 1        | 2.38%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s         | 1        | 2.38%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 1        | 2.38%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s            | 1        | 2.38%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s        | 1        | 2.38%   |
| G.Skill RAM F4-4400C19-32GTRS 32GB DIMM DDR4 2667MT/s       | 1        | 2.38%   |
| G.Skill RAM F4-3600C17-16GTZR 16384MB DIMM DDR4 3666MT/s    | 1        | 2.38%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s      | 1        | 2.38%   |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s         | 1        | 2.38%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s       | 1        | 2.38%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s          | 1        | 2.38%   |
| G.Skill RAM F4-3200C14-32GVK 32GB DIMM DDR4 2666MT/s        | 1        | 2.38%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3000MT/s         | 1        | 2.38%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s         | 1        | 2.38%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s        | 1        | 2.38%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s       | 1        | 2.38%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s     | 1        | 2.38%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s    | 1        | 2.38%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Crucial RAM BL8G32C16U4R.M8FE1 8GB DIMM DDR4 3400MT/s       | 1        | 2.38%   |
| Crucial RAM BL8G32C16U4B.M8FE1 8GB DIMM DDR4 3600MT/s       | 1        | 2.38%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3600MT/s    | 1        | 2.38%   |
| Crucial RAM BL32G32C16U4B.M16FB1 32GB DIMM DDR4 3200MT/s    | 1        | 2.38%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s    | 1        | 2.38%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s | 1        | 2.38%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s     | 1        | 2.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 1        | 2.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s       | 1        | 2.38%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s       | 1        | 2.38%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s            | 1        | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 91.43%  |
| SDRAM   | 1        | 2.86%   |
| DDR3    | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 35       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 42.5%   |
| 16384 | 13       | 32.5%   |
| 32768 | 5        | 12.5%   |
| 4096  | 3        | 7.5%    |
| 1024  | 1        | 2.5%    |
| 512   | 1        | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 8        | 20%     |
| 3600    | 5        | 12.5%   |
| 2667    | 4        | 10%     |
| 2133    | 4        | 10%     |
| 3666    | 2        | 5%      |
| 3466    | 2        | 5%      |
| 3400    | 2        | 5%      |
| 3000    | 2        | 5%      |
| 2400    | 2        | 5%      |
| 4000    | 1        | 2.5%    |
| 3866    | 1        | 2.5%    |
| 3533    | 1        | 2.5%    |
| 2933    | 1        | 2.5%    |
| 2733    | 1        | 2.5%    |
| 2666    | 1        | 2.5%    |
| 1867    | 1        | 2.5%    |
| 1333    | 1        | 2.5%    |
| Unknown | 1        | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 50%     |
| YGTek                         | 1        | 8.33%   |
| Valve Software                | 1        | 8.33%   |
| Sunplus Innovation Technology | 1        | 8.33%   |
| Generalplus Technology        | 1        | 8.33%   |
| Cubeternet                    | 1        | 8.33%   |
| Creative Technology           | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| YGTek Webcam                                                        | 1        | 8.33%   |
| Valve Software 3D Camera                                            | 1        | 8.33%   |
| Sunplus Canyon CNS CWC5 Webcam                                      | 1        | 8.33%   |
| Logitech Webcam C270                                                | 1        | 8.33%   |
| Logitech StreamCam                                                  | 1        | 8.33%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1        | 8.33%   |
| Logitech HD Webcam C510                                             | 1        | 8.33%   |
| Logitech HD Pro Webcam C920                                         | 1        | 8.33%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 8.33%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 8.33%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 8.33%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 29       | 72.5%   |
| 1     | 7        | 17.5%   |
| 4     | 2        | 5%      |
| 3     | 1        | 2.5%    |
| 2     | 1        | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 6        | 40%     |
| Graphics card            | 2        | 13.33%  |
| Storage/ata              | 1        | 6.67%   |
| Sound                    | 1        | 6.67%   |
| Net/wireless             | 1        | 6.67%   |
| Modem                    | 1        | 6.67%   |
| Fingerprint reader       | 1        | 6.67%   |
| Camera                   | 1        | 6.67%   |
| Bluetooth                | 1        | 6.67%   |

