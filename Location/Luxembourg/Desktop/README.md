Linux in Luxembourg - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Luxembourg.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 45

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| LattePanda | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Gigabyte   | X99-UD3-CF                  | [75dbdd1681](https://linux-hardware.org/?probe=75dbdd1681) | Jul 26, 2022 |
| Gigabyte   | X99-UD3-CF                  | [7eaa9fa16b](https://linux-hardware.org/?probe=7eaa9fa16b) | Jul 26, 2022 |
| HP         | 2820h                       | [7303ad365d](https://linux-hardware.org/?probe=7303ad365d) | Jul 11, 2022 |
| Intel      | DG41WV AAE90316-104         | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASRock     | H110M-STX                   | [e5876258c7](https://linux-hardware.org/?probe=e5876258c7) | Feb 19, 2022 |
| ASUSTek    | Z97-A                       | [19d74bd6f0](https://linux-hardware.org/?probe=19d74bd6f0) | Jan 31, 2022 |
| ASUSTek    | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Medion     | Cattle24 1M                 | [05747b9a42](https://linux-hardware.org/?probe=05747b9a42) | Nov 10, 2021 |
| Medion     | Cattle24 1M                 | [9763c21680](https://linux-hardware.org/?probe=9763c21680) | Nov 10, 2021 |
| ASUSTek    | TUF Gaming Z590-PLUS WIF... | [b2f196476a](https://linux-hardware.org/?probe=b2f196476a) | Nov 04, 2021 |
| ASUSTek    | UN62                        | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [ce97f26d1d](https://linux-hardware.org/?probe=ce97f26d1d) | Sep 09, 2021 |
| Intel      | DG41WV AAE90316-104         | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [80a7298343](https://linux-hardware.org/?probe=80a7298343) | Jul 27, 2021 |
| ASRock     | B450M-HDV R4.0              | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Intel      | DG965SS AAD41678-308        | [d76e4b9ec3](https://linux-hardware.org/?probe=d76e4b9ec3) | May 04, 2021 |
| ASUSTek    | M5A78L-M LX3                | [565be765f5](https://linux-hardware.org/?probe=565be765f5) | Apr 29, 2021 |
| Intel      | DG41WV AAE90316-104         | [af606a347f](https://linux-hardware.org/?probe=af606a347f) | Mar 15, 2021 |
| Gigabyte   | H81M-DS2                    | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Gigabyte   | H81M-DS2                    | [3500ce2480](https://linux-hardware.org/?probe=3500ce2480) | Feb 09, 2021 |
| ASUSTek    | Z87-DELUXE                  | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [ae14c03ffc](https://linux-hardware.org/?probe=ae14c03ffc) | Dec 19, 2020 |
| Gigabyte   | X570 AORUS PRO              | [9ec2d84b9b](https://linux-hardware.org/?probe=9ec2d84b9b) | Dec 10, 2020 |
| ASUSTek    | PRIME H470M-PLUS            | [1d77b8496d](https://linux-hardware.org/?probe=1d77b8496d) | Nov 28, 2020 |
| Gigabyte   | H81M-DS2                    | [e6be700463](https://linux-hardware.org/?probe=e6be700463) | Oct 28, 2020 |
| ASUSTek    | Z87-A                       | [bbe1190702](https://linux-hardware.org/?probe=bbe1190702) | Oct 01, 2020 |
| MSI        | MAG Z490 TOMAHAWK           | [ffd532c8d8](https://linux-hardware.org/?probe=ffd532c8d8) | Aug 16, 2020 |
| Gigabyte   | Z97X-Gaming 5               | [e1c1c22a7b](https://linux-hardware.org/?probe=e1c1c22a7b) | Aug 11, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [3f740083f9](https://linux-hardware.org/?probe=3f740083f9) | Jul 19, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [f1c586d370](https://linux-hardware.org/?probe=f1c586d370) | Jul 19, 2020 |
| Medion     | MS-7848                     | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| MSI        | H310M PRO-M2 PLUS           | [33665c7f49](https://linux-hardware.org/?probe=33665c7f49) | May 04, 2020 |
| MSI        | H310M PRO-M2 PLUS           | [6e21e82c58](https://linux-hardware.org/?probe=6e21e82c58) | Mar 26, 2020 |
| ASUSTek    | PRIME B250M-A               | [68e88028d6](https://linux-hardware.org/?probe=68e88028d6) | Jan 09, 2020 |
| ASUSTek    | PRIME B250M-A               | [453044841e](https://linux-hardware.org/?probe=453044841e) | Jan 09, 2020 |
| Foxconn    | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn    | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Lenovo     | 3106 SDK0J40697 WIN 3305... | [c1c91fe558](https://linux-hardware.org/?probe=c1c91fe558) | Nov 18, 2019 |
| Lenovo     | 3106 SDK0J40697 WIN 3305... | [9ee20bcfcb](https://linux-hardware.org/?probe=9ee20bcfcb) | Nov 18, 2019 |
| Lenovo     | 3106 SDK0J40697 WIN 3305... | [3b96b0c40d](https://linux-hardware.org/?probe=3b96b0c40d) | Nov 17, 2019 |
| Gigabyte   | Z270M-D3H-CF                | [3bcd649400](https://linux-hardware.org/?probe=3bcd649400) | Jul 14, 2019 |
| HP         | 3048h                       | [ab8f89fdcc](https://linux-hardware.org/?probe=ab8f89fdcc) | Oct 07, 2018 |
| MSI        | NF750-G55                   | [d1b2ddb193](https://linux-hardware.org/?probe=d1b2ddb193) | May 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 6        | 17.65%  |
| Ubuntu 18.04       | 3        | 8.82%   |
| openSUSE Leap-15.2 | 2        | 5.88%   |
| Xubuntu 16.04      | 1        | 2.94%   |
| UbuntuDDE 20.04    | 1        | 2.94%   |
| Ubuntu 22.10       | 1        | 2.94%   |
| Ubuntu 20.10       | 1        | 2.94%   |
| Ubuntu 19.10       | 1        | 2.94%   |
| ROSA R9            | 1        | 2.94%   |
| Pop!_OS 22.04      | 1        | 2.94%   |
| openSUSE Leap-15.3 | 1        | 2.94%   |
| Manjaro 21.1.0     | 1        | 2.94%   |
| Mageia 7           | 1        | 2.94%   |
| Lubuntu 20.10      | 1        | 2.94%   |
| LMDE 4             | 1        | 2.94%   |
| Linux Mint 20.1    | 1        | 2.94%   |
| Kubuntu 20.04      | 1        | 2.94%   |
| KDE neon 20.04     | 1        | 2.94%   |
| Kali 2021.3        | 1        | 2.94%   |
| Fedora 34          | 1        | 2.94%   |
| Fedora 33          | 1        | 2.94%   |
| Fedora 32          | 1        | 2.94%   |
| Elementary 5.1.7   | 1        | 2.94%   |
| Debian 10          | 1        | 2.94%   |
| CentOS 8           | 1        | 2.94%   |
| Arch               | 1        | 2.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Ubuntu     | 12       | 36.36%  |
| Fedora     | 3        | 9.09%   |
| openSUSE   | 2        | 6.06%   |
| Xubuntu    | 1        | 3.03%   |
| UbuntuDDE  | 1        | 3.03%   |
| ROSA       | 1        | 3.03%   |
| Pop!_OS    | 1        | 3.03%   |
| Manjaro    | 1        | 3.03%   |
| Mageia     | 1        | 3.03%   |
| Lubuntu    | 1        | 3.03%   |
| LMDE       | 1        | 3.03%   |
| Linux Mint | 1        | 3.03%   |
| Kubuntu    | 1        | 3.03%   |
| KDE neon   | 1        | 3.03%   |
| Kali       | 1        | 3.03%   |
| Elementary | 1        | 3.03%   |
| Debian     | 1        | 3.03%   |
| CentOS     | 1        | 3.03%   |
| Arch       | 1        | 3.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.4.0-90-generic                | 2        | 5.41%   |
| 5.9.13-zen1-1-zen               | 1        | 2.7%    |
| 5.9.10-200.fc33.x86_64          | 1        | 2.7%    |
| 5.8.0-44-generic                | 1        | 2.7%    |
| 5.8.0-43-generic                | 1        | 2.7%    |
| 5.8.0-26-generic                | 1        | 2.7%    |
| 5.7.19-desktop-3.mga7           | 1        | 2.7%    |
| 5.4.0-91-generic                | 1        | 2.7%    |
| 5.4.0-72-generic                | 1        | 2.7%    |
| 5.4.0-58-generic                | 1        | 2.7%    |
| 5.4.0-47-generic                | 1        | 2.7%    |
| 5.4.0-42-generic                | 1        | 2.7%    |
| 5.4.0-40-generic                | 1        | 2.7%    |
| 5.4.0-21-generic                | 1        | 2.7%    |
| 5.3.18-lp152.66-default         | 1        | 2.7%    |
| 5.3.18-lp152.33-default         | 1        | 2.7%    |
| 5.3.18-59.19-preempt            | 1        | 2.7%    |
| 5.3.18-150300.59.49-preempt     | 1        | 2.7%    |
| 5.3.0-46-generic                | 1        | 2.7%    |
| 5.3.0-42-generic                | 1        | 2.7%    |
| 5.3.0-26-generic                | 1        | 2.7%    |
| 5.3.0-0.bpo.2-686-pae           | 1        | 2.7%    |
| 5.19.0-76051900-generic         | 1        | 2.7%    |
| 5.15.0-41-generic               | 1        | 2.7%    |
| 5.15.0-25-generic               | 1        | 2.7%    |
| 5.13.4-1-MANJARO                | 1        | 2.7%    |
| 5.12.7-300.fc34.x86_64          | 1        | 2.7%    |
| 5.11.0-38-generic               | 1        | 2.7%    |
| 5.10.7-100.fc32.x86_64          | 1        | 2.7%    |
| 5.10.0-kali9-amd64              | 1        | 2.7%    |
| 5.0.0-36-generic                | 1        | 2.7%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 1        | 2.7%    |
| 4.4.0-137-generic               | 1        | 2.7%    |
| 4.19.0-17-amd64                 | 1        | 2.7%    |
| 4.18.0-80.11.2.el8_0.x86_64     | 1        | 2.7%    |
| 4.18.0-25-generic               | 1        | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 9        | 28.13%  |
| 5.3.0   | 3        | 9.38%   |
| 5.3.18  | 2        | 6.25%   |
| 5.15.0  | 2        | 6.25%   |
| 4.18.0  | 2        | 6.25%   |
| 5.9.13  | 1        | 3.13%   |
| 5.9.10  | 1        | 3.13%   |
| 5.8.0   | 1        | 3.13%   |
| 5.7.19  | 1        | 3.13%   |
| 5.19.0  | 1        | 3.13%   |
| 5.13.4  | 1        | 3.13%   |
| 5.12.7  | 1        | 3.13%   |
| 5.11.0  | 1        | 3.13%   |
| 5.10.7  | 1        | 3.13%   |
| 5.10.0  | 1        | 3.13%   |
| 5.0.0   | 1        | 3.13%   |
| 4.9.20  | 1        | 3.13%   |
| 4.4.0   | 1        | 3.13%   |
| 4.19.0  | 1        | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 28.13%  |
| 5.3     | 5        | 15.63%  |
| 5.9     | 2        | 6.25%   |
| 5.15    | 2        | 6.25%   |
| 5.10    | 2        | 6.25%   |
| 4.18    | 2        | 6.25%   |
| 5.8     | 1        | 3.13%   |
| 5.7     | 1        | 3.13%   |
| 5.19    | 1        | 3.13%   |
| 5.13    | 1        | 3.13%   |
| 5.12    | 1        | 3.13%   |
| 5.11    | 1        | 3.13%   |
| 5.0     | 1        | 3.13%   |
| 4.9     | 1        | 3.13%   |
| 4.4     | 1        | 3.13%   |
| 4.19    | 1        | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 31       | 96.88%  |
| i686   | 1        | 3.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 16       | 47.06%  |
| Unknown    | 5        | 14.71%  |
| KDE5       | 4        | 11.76%  |
| X-Cinnamon | 2        | 5.88%   |
| KDE        | 2        | 5.88%   |
| XFCE       | 1        | 2.94%   |
| Pantheon   | 1        | 2.94%   |
| LXQt       | 1        | 2.94%   |
| Deepin     | 1        | 2.94%   |
| Cinnamon   | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 70.59%  |
| Wayland | 4        | 11.76%  |
| Tty     | 3        | 8.82%   |
| Unknown | 3        | 8.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 48.48%  |
| SDDM    | 5        | 15.15%  |
| GDM     | 5        | 15.15%  |
| LightDM | 4        | 12.12%  |
| GDM3    | 2        | 6.06%   |
| TDM     | 1        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 37.5%   |
| fr_FR   | 4        | 12.5%   |
| C       | 4        | 12.5%   |
| Unknown | 3        | 9.38%   |
| es_ES   | 2        | 6.25%   |
| en_GB   | 2        | 6.25%   |
| de_LU   | 2        | 6.25%   |
| lb_LU   | 1        | 3.13%   |
| de_DE   | 1        | 3.13%   |
| de_CH   | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 59.38%  |
| EFI  | 13       | 40.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 22       | 68.75%  |
| Btrfs   | 4        | 12.5%   |
| Xfs     | 3        | 9.38%   |
| Zfs     | 1        | 3.13%   |
| Overlay | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 56.25%  |
| GPT     | 13       | 40.63%  |
| MBR     | 1        | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 78.13%  |
| Yes       | 7        | 21.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 66.67%  |
| Yes       | 11       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 37.5%   |
| Gigabyte Technology | 5        | 15.63%  |
| MSI                 | 3        | 9.38%   |
| ASRock              | 3        | 9.38%   |
| Medion              | 2        | 6.25%   |
| Intel               | 2        | 6.25%   |
| Hewlett-Packard     | 2        | 6.25%   |
| Lenovo              | 1        | 3.13%   |
| LattePanda          | 1        | 3.13%   |
| Foxconn             | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 9.38%   |
| MSI MS-7C80                         | 1        | 3.13%   |
| MSI MS-7C08                         | 1        | 3.13%   |
| MSI MS-7578                         | 1        | 3.13%   |
| Medion P961x                        | 1        | 3.13%   |
| Medion MS-7848                      | 1        | 3.13%   |
| Lenovo ThinkCentre M910s 10MKS02N04 | 1        | 3.13%   |
| LattePanda 3 Delta                  | 1        | 3.13%   |
| Intel DG965SS AAD41678-308          | 1        | 3.13%   |
| Intel DG41WV AAE90316-104           | 1        | 3.13%   |
| HP Compaq dc5800 Small Form Factor  | 1        | 3.13%   |
| HP Compaq 6000 Pro SFF PC           | 1        | 3.13%   |
| Gigabyte Z97X-Gaming 5              | 1        | 3.13%   |
| Gigabyte Z270M-D3H                  | 1        | 3.13%   |
| Gigabyte X99-UD3-CF                 | 1        | 3.13%   |
| Gigabyte X570 AORUS PRO             | 1        | 3.13%   |
| Gigabyte H81M-DS2                   | 1        | 3.13%   |
| Foxconn p6601fr-m                   | 1        | 3.13%   |
| ASUS UN62                           | 1        | 3.13%   |
| ASUS TUF Gaming Z590-PLUS WIFI      | 1        | 3.13%   |
| ASUS ROG STRIX X570-E GAMING        | 1        | 3.13%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 1        | 3.13%   |
| ASUS PRIME X470-PRO                 | 1        | 3.13%   |
| ASUS PRIME H470M-PLUS               | 1        | 3.13%   |
| ASUS PRIME B450-PLUS                | 1        | 3.13%   |
| ASUS PRIME B250M-A                  | 1        | 3.13%   |
| ASUS M5A78L-M LX3                   | 1        | 3.13%   |
| ASRock H110M-STX                    | 1        | 3.13%   |
| ASRock B450M-HDV R4.0               | 1        | 3.13%   |
| ASRock B450 Gaming-ITX/ac           | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 12.5%   |
| ASUS All             | 3        | 9.38%   |
| HP Compaq            | 2        | 6.25%   |
| ASUS ROG             | 2        | 6.25%   |
| MSI MS-7C80          | 1        | 3.13%   |
| MSI MS-7C08          | 1        | 3.13%   |
| MSI MS-7578          | 1        | 3.13%   |
| Medion P961x         | 1        | 3.13%   |
| Medion MS-7848       | 1        | 3.13%   |
| Lenovo ThinkCentre   | 1        | 3.13%   |
| LattePanda 3         | 1        | 3.13%   |
| Intel DG965SS        | 1        | 3.13%   |
| Intel DG41WV         | 1        | 3.13%   |
| Gigabyte Z97X-Gaming | 1        | 3.13%   |
| Gigabyte Z270M-D3H   | 1        | 3.13%   |
| Gigabyte X99-UD3-CF  | 1        | 3.13%   |
| Gigabyte X570        | 1        | 3.13%   |
| Gigabyte H81M-DS2    | 1        | 3.13%   |
| Foxconn p6601fr-m    | 1        | 3.13%   |
| ASUS UN62            | 1        | 3.13%   |
| ASUS TUF             | 1        | 3.13%   |
| ASUS M5A78L-M        | 1        | 3.13%   |
| ASRock H110M-STX     | 1        | 3.13%   |
| ASRock B450M-HDV     | 1        | 3.13%   |
| ASRock B450          | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 5        | 15.63%  |
| 2013 | 4        | 12.5%   |
| 2010 | 4        | 12.5%   |
| 2016 | 3        | 9.38%   |
| 2014 | 3        | 9.38%   |
| 2021 | 2        | 6.25%   |
| 2020 | 2        | 6.25%   |
| 2019 | 2        | 6.25%   |
| 2022 | 1        | 3.13%   |
| 2017 | 1        | 3.13%   |
| 2015 | 1        | 3.13%   |
| 2012 | 1        | 3.13%   |
| 2009 | 1        | 3.13%   |
| 2008 | 1        | 3.13%   |
| 2007 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 30       | 93.75%  |
| Enabled  | 2        | 6.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 13       | 40.63%  |
| 8.01-16.0   | 6        | 18.75%  |
| 4.01-8.0    | 4        | 12.5%   |
| 32.01-64.0  | 4        | 12.5%   |
| 3.01-4.0    | 3        | 9.38%   |
| 64.01-256.0 | 2        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 9        | 26.47%  |
| 4.01-8.0  | 8        | 23.53%  |
| 3.01-4.0  | 6        | 17.65%  |
| 1.01-2.0  | 6        | 17.65%  |
| 8.01-16.0 | 3        | 8.82%   |
| 0.51-1.0  | 2        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 38.24%  |
| 3      | 7        | 20.59%  |
| 1      | 7        | 20.59%  |
| 4      | 4        | 11.76%  |
| 5      | 2        | 5.88%   |
| 7      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 62.5%   |
| Yes       | 12       | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 68.75%  |
| Yes       | 10       | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Luxembourg | 32       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Luxembourg        | 16       | 45.71%  |
| Sanem             | 2        | 5.71%   |
| Esch-sur-Alzette  | 2        | 5.71%   |
| Differdange       | 2        | 5.71%   |
| Wormeldange       | 1        | 2.86%   |
| Wasserbillig      | 1        | 2.86%   |
| Useldange         | 1        | 2.86%   |
| Strassen          | 1        | 2.86%   |
| Schieren          | 1        | 2.86%   |
| Roeser            | 1        | 2.86%   |
| Pontpierre        | 1        | 2.86%   |
| Junglinster       | 1        | 2.86%   |
| Itzig             | 1        | 2.86%   |
| Hosingen          | 1        | 2.86%   |
| Ehnen             | 1        | 2.86%   |
| Bettange-sur-Mess | 1        | 2.86%   |
| Belvaux           | 1        | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 16       | 25     | 27.12%  |
| Seagate                   | 10       | 17     | 16.95%  |
| WDC                       | 9        | 18     | 15.25%  |
| Crucial                   | 5        | 7      | 8.47%   |
| Toshiba                   | 2        | 4      | 3.39%   |
| Kingston                  | 2        | 3      | 3.39%   |
| Unknown                   | 1        | 2      | 1.69%   |
| Transcend                 | 1        | 1      | 1.69%   |
| TCSUNBOW                  | 1        | 1      | 1.69%   |
| SABRENT                   | 1        | 1      | 1.69%   |
| Phison                    | 1        | 1      | 1.69%   |
| OCZ                       | 1        | 1      | 1.69%   |
| Micron/Crucial Technology | 1        | 1      | 1.69%   |
| Maxtor                    | 1        | 2      | 1.69%   |
| KingSpec                  | 1        | 1      | 1.69%   |
| Intenso                   | 1        | 1      | 1.69%   |
| Inateck                   | 1        | 1      | 1.69%   |
| Hitachi                   | 1        | 2      | 1.69%   |
| HGST                      | 1        | 2      | 1.69%   |
| Gigabyte Technology       | 1        | 1      | 1.69%   |
| A-DATA Technology         | 1        | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 250GB                  | 2        | 2.67%   |
| Samsung SSD 850 EVO 250GB                  | 2        | 2.67%   |
| Samsung SSD 840 EVO 250GB                  | 2        | 2.67%   |
| Samsung SP2504C 250GB                      | 2        | 2.67%   |
| Kingston SA400S37240G 240GB SSD            | 2        | 2.67%   |
| Crucial CT1000P2SSD8 1TB                   | 2        | 2.67%   |
| WDC WDS500G3X0C-00SJG0 500GB               | 1        | 1.33%   |
| WDC WD5000AAVS-00ZTB0 500GB                | 1        | 1.33%   |
| WDC WD5000AAKS-60Z1A0 500GB                | 1        | 1.33%   |
| WDC WD40EZRZ-75GXCB0 4TB                   | 1        | 1.33%   |
| WDC WD4000FYYZ-01UL1B2 4TB                 | 1        | 1.33%   |
| WDC WD3001FFSX-68JNUN0 3TB                 | 1        | 1.33%   |
| WDC WD3000GLFS-01F8U0 304GB                | 1        | 1.33%   |
| WDC WD20EFAX-68FB5N0 2TB                   | 1        | 1.33%   |
| WDC WD141KRYZ-01C66B0 14TB                 | 1        | 1.33%   |
| WDC WD10EZRX-00A8LB0 1TB                   | 1        | 1.33%   |
| WDC WD10EZEX-60ZF5A0 1TB                   | 1        | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.33%   |
| WDC WD10EARS-00Y5B1 1TB                    | 1        | 1.33%   |
| WDC WD10EACS-00D6B1 1TB                    | 1        | 1.33%   |
| WDC WD1001FALS-00J7B0 1TB                  | 1        | 1.33%   |
| Unknown MMC Card  64GB                     | 1        | 1.33%   |
| Unknown DA4064  64GB                       | 1        | 1.33%   |
| Transcend TS512GSSD370 512GB               | 1        | 1.33%   |
| Toshiba MG03ACA100 1TB                     | 1        | 1.33%   |
| Toshiba DT01ACA050 500GB                   | 1        | 1.33%   |
| TCSUNBOW X3 240GB SSD                      | 1        | 1.33%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1.33%   |
| Seagate ST4000VN008-2DR166 4TB             | 1        | 1.33%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 1.33%   |
| Seagate ST3750630AS 752GB                  | 1        | 1.33%   |
| Seagate ST3500418AS 500GB                  | 1        | 1.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB         | 1        | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB             | 1        | 1.33%   |
| Seagate ST1000DM003-9YN162 1TB             | 1        | 1.33%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 1.33%   |
| Seagate M3 Portable 2TB                    | 1        | 1.33%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.33%   |
| Samsung SSD 980 PRO 2TB                    | 1        | 1.33%   |
| Samsung SSD 970 EVO Plus 500GB             | 1        | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 17     | 33.33%  |
| Seagate             | 8        | 15     | 33.33%  |
| Toshiba             | 2        | 4      | 8.33%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Intenso             | 1        | 1      | 4.17%   |
| Inateck             | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 2      | 4.17%   |
| HGST                | 1        | 2      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 16     | 52.17%  |
| Crucial             | 3        | 5      | 13.04%  |
| Kingston            | 2        | 3      | 8.7%    |
| Transcend           | 1        | 1      | 4.35%   |
| TCSUNBOW            | 1        | 1      | 4.35%   |
| OCZ                 | 1        | 1      | 4.35%   |
| Maxtor              | 1        | 2      | 4.35%   |
| KingSpec            | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 19       | 44     | 38.78%  |
| SSD     | 17       | 31     | 34.69%  |
| NVMe    | 11       | 15     | 22.45%  |
| MMC     | 1        | 2      | 2.04%   |
| Unknown | 1        | 1      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 73     | 63.41%  |
| NVMe | 11       | 14     | 26.83%  |
| SAS  | 3        | 4      | 7.32%   |
| MMC  | 1        | 2      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 41     | 48.84%  |
| 0.51-1.0   | 11       | 20     | 25.58%  |
| 3.01-4.0   | 5        | 6      | 11.63%  |
| 1.01-2.0   | 3        | 4      | 6.98%   |
| 2.01-3.0   | 2        | 3      | 4.65%   |
| 10.01-20.0 | 1        | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 31.25%  |
| 251-500        | 5        | 15.63%  |
| Unknown        | 5        | 15.63%  |
| More than 3000 | 4        | 12.5%   |
| 2001-3000      | 3        | 9.38%   |
| 501-1000       | 3        | 9.38%   |
| 1-20           | 1        | 3.13%   |
| 51-100         | 1        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 11       | 34.38%  |
| 101-250        | 6        | 18.75%  |
| Unknown        | 5        | 15.63%  |
| 251-500        | 2        | 6.25%   |
| 21-50          | 2        | 6.25%   |
| 1001-2000      | 2        | 6.25%   |
| More than 3000 | 1        | 3.13%   |
| 2001-3000      | 1        | 3.13%   |
| 501-1000       | 1        | 3.13%   |
| 51-100         | 1        | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Crucial CT128MX100SSD1 128GB | 1        | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 2      | 100%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 20       | 53     | 55.56%  |
| Works    | 15       | 38     | 41.67%  |
| Malfunc  | 1        | 2      | 2.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 21       | 47.73%  |
| AMD                       | 9        | 20.45%  |
| Samsung Electronics       | 5        | 11.36%  |
| Micron/Crucial Technology | 3        | 6.82%   |
| Phison Electronics        | 2        | 4.55%   |
| Seagate Technology        | 1        | 2.27%   |
| SanDisk                   | 1        | 2.27%   |
| Marvell Technology Group  | 1        | 2.27%   |
| ASMedia Technology        | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 13.21%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 7.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 7.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 7.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 5.66%   |
| Phison E12 NVMe Controller                                                     | 2        | 3.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 3.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 3.77%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 1.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.89%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.89%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1        | 1.89%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.89%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.89%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1        | 1.89%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                         | 1        | 1.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 1        | 1.89%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 1        | 1.89%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 1        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1        | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 60.47%  |
| NVMe | 11       | 25.58%  |
| IDE  | 5        | 11.63%  |
| RAID | 1        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 68.75%  |
| AMD    | 10       | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 6.25%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1        | 3.13%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 3.13%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 3.13%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1        | 3.13%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 3.13%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 3.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 3.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 3.13%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 3.13%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 3.13%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 3.13%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 3.13%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 3.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 3.13%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 3.13%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 3.13%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 3.13%   |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 1        | 3.13%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 3.13%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 1        | 3.13%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 1        | 3.13%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 3.13%   |
| AMD Phenom II X4 945 Processor              | 1        | 3.13%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 3.13%   |
| AMD Athlon II X4 640 Processor              | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 8        | 25%     |
| AMD Ryzen 5             | 4        | 12.5%   |
| Intel Core i5           | 3        | 9.38%   |
| Intel Pentium           | 2        | 6.25%   |
| Intel Core i3           | 2        | 6.25%   |
| Intel Core 2 Quad       | 2        | 6.25%   |
| AMD Ryzen 9             | 2        | 6.25%   |
| Other                   | 1        | 3.13%   |
| Intel Pentium Dual-Core | 1        | 3.13%   |
| Intel Core 2 Duo        | 1        | 3.13%   |
| Intel Core 2            | 1        | 3.13%   |
| Intel Celeron           | 1        | 3.13%   |
| AMD Ryzen 7             | 1        | 3.13%   |
| AMD Phenom II X4        | 1        | 3.13%   |
| AMD FX                  | 1        | 3.13%   |
| AMD Athlon II X4        | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 12       | 37.5%   |
| 2       | 8        | 25%     |
| 6       | 5        | 15.63%  |
| 8       | 4        | 12.5%   |
| 12      | 2        | 6.25%   |
| Unknown | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 19       | 59.38%  |
| 1       | 12       | 37.5%   |
| Unknown | 1        | 3.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 4        | 12.5%   |
| Unknown    | 3        | 9.38%   |
| 0xa0655    | 2        | 6.25%   |
| 0x906e9    | 2        | 6.25%   |
| 0x506e3    | 2        | 6.25%   |
| 0x1067a    | 2        | 6.25%   |
| 0x10677    | 2        | 6.25%   |
| 0x08701021 | 2        | 6.25%   |
| 0x08701013 | 2        | 6.25%   |
| 0xa0671    | 1        | 3.13%   |
| 0x906ed    | 1        | 3.13%   |
| 0x906c0    | 1        | 3.13%   |
| 0x6f6      | 1        | 3.13%   |
| 0x406f1    | 1        | 3.13%   |
| 0x40651    | 1        | 3.13%   |
| 0x0a201009 | 1        | 3.13%   |
| 0x0810100b | 1        | 3.13%   |
| 0x0800820d | 1        | 3.13%   |
| 0x010000db | 1        | 3.13%   |
| 0x010000c8 | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Haswell    | 7        | 21.88%  |
| Zen 2      | 4        | 12.5%   |
| Penryn     | 4        | 12.5%   |
| KabyLake   | 3        | 9.38%   |
| Skylake    | 2        | 6.25%   |
| K10        | 2        | 6.25%   |
| CometLake  | 2        | 6.25%   |
| Zen+       | 1        | 3.13%   |
| Zen 3      | 1        | 3.13%   |
| Zen        | 1        | 3.13%   |
| Piledriver | 1        | 3.13%   |
| Icelake    | 1        | 3.13%   |
| Core       | 1        | 3.13%   |
| Broadwell  | 1        | 3.13%   |
| Unknown    | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 16       | 50%     |
| Intel  | 12       | 37.5%   |
| AMD    | 4        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.06%   |
| Intel HD Graphics 530                                                       | 2        | 6.06%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 3.03%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 3.03%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 3.03%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 3.03%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1        | 3.03%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.03%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 3.03%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 3.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.03%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 3.03%   |
| Nvidia GF119 [GeForce GT 705]                                               | 1        | 3.03%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 3.03%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 3.03%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 3.03%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 3.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.03%   |
| Intel 82Q33 Express Integrated Graphics Controller                          | 1        | 3.03%   |
| Intel 82G965 Integrated Graphics Controller                                 | 1        | 3.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.03%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1        | 3.03%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.03%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 3.03%   |
| AMD Baffin [Radeon Pro WX 4100]                                             | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 17       | 53.13%  |
| 1 x Intel  | 11       | 34.38%  |
| 1 x AMD    | 3        | 9.38%   |
| 2 x AMD    | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 53.13%  |
| Proprietary | 12       | 37.5%   |
| Unknown     | 3        | 9.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 50%     |
| 0.51-1.0   | 5        | 15.63%  |
| 3.01-4.0   | 4        | 12.5%   |
| 1.01-2.0   | 2        | 6.25%   |
| 8.01-16.0  | 2        | 6.25%   |
| 0.01-0.5   | 2        | 6.25%   |
| 5.01-6.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 23.53%  |
| Dell                 | 5        | 14.71%  |
| Goldstar             | 4        | 11.76%  |
| Philips              | 3        | 8.82%   |
| Iiyama               | 3        | 8.82%   |
| Hewlett-Packard      | 3        | 8.82%   |
| Medion               | 2        | 5.88%   |
| MSI                  | 1        | 2.94%   |
| Fujitsu Siemens      | 1        | 2.94%   |
| BenQ                 | 1        | 2.94%   |
| Belinea              | 1        | 2.94%   |
| AOC                  | 1        | 2.94%   |
| Ancor Communications | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1        | 2.94%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1        | 2.94%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1        | 2.94%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 2.94%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1        | 2.94%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 2.94%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1        | 2.94%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1        | 2.94%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 2.94%   |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1        | 2.94%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1        | 2.94%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1        | 2.94%   |
| Iiyama X2485 IVM610F 1920x1080 520x320mm 24.0-inch                    | 1        | 2.94%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 1        | 2.94%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                  | 1        | 2.94%   |
| Hewlett-Packard S2331 HWP2907 1920x1080 509x286mm 23.0-inch           | 1        | 2.94%   |
| Hewlett-Packard L1950 HWP26E8 1280x1024 380x300mm 19.1-inch           | 1        | 2.94%   |
| Hewlett-Packard 24y HPN3506 1920x1080 528x297mm 23.9-inch             | 1        | 2.94%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1        | 2.94%   |
| Goldstar TV GSMC0A0 3840x2160                                         | 1        | 2.94%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1        | 2.94%   |
| Goldstar 24EA53 GSM59AC 1920x1080 510x290mm 23.1-inch                 | 1        | 2.94%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 509x286mm 23.0-inch      | 1        | 2.94%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1        | 2.94%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1        | 2.94%   |
| Dell U2211H DEL405E 1920x1080 480x270mm 21.7-inch                     | 1        | 2.94%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 1        | 2.94%   |
| Dell LCD Monitor P2715Q 3840x2160                                     | 1        | 2.94%   |
| BenQ PJ BNQ0203 1920x1080                                             | 1        | 2.94%   |
| Belinea Belinea101540 MAX0604 1024x768 307x230mm 15.1-inch            | 1        | 2.94%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 2.94%   |
| Ancor Communications VC279 ACI27C4 1920x1080 598x336mm 27.0-inch      | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 54.55%  |
| 3840x2160 (4K)     | 5        | 15.15%  |
| 2560x1440 (QHD)    | 4        | 12.12%  |
| 1920x1200 (WUXGA)  | 2        | 6.06%   |
| 1680x1050 (WSXGA+) | 1        | 3.03%   |
| 1360x768           | 1        | 3.03%   |
| 1280x1024 (SXGA)   | 1        | 3.03%   |
| 1024x768 (XGA)     | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 23.53%  |
| 23      | 6        | 17.65%  |
| 24      | 5        | 14.71%  |
| Unknown | 3        | 8.82%   |
| 72      | 2        | 5.88%   |
| 21      | 2        | 5.88%   |
| 46      | 1        | 2.94%   |
| 32      | 1        | 2.94%   |
| 31      | 1        | 2.94%   |
| 25      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 18      | 1        | 2.94%   |
| 15      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 54.55%  |
| 401-500     | 4        | 12.12%  |
| Unknown     | 3        | 9.09%   |
| 601-700     | 2        | 6.06%   |
| 1501-2000   | 2        | 6.06%   |
| 701-800     | 1        | 3.03%   |
| 351-400     | 1        | 3.03%   |
| 301-350     | 1        | 3.03%   |
| 1001-1500   | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 77.42%  |
| 16/10   | 3        | 9.68%   |
| Unknown | 2        | 6.45%   |
| 5/4     | 1        | 3.23%   |
| 4/3     | 1        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 35.29%  |
| 301-350        | 8        | 23.53%  |
| 251-300        | 3        | 8.82%   |
| Unknown        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 351-500        | 2        | 5.88%   |
| 151-200        | 1        | 2.94%   |
| 141-150        | 1        | 2.94%   |
| 101-110        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 75%     |
| 101-120 | 4        | 12.5%   |
| Unknown | 3        | 9.38%   |
| 1-50    | 1        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 78.13%  |
| 2     | 5        | 15.63%  |
| 0     | 2        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 46.67%  |
| Realtek Semiconductor | 14       | 31.11%  |
| Qualcomm Atheros      | 4        | 8.89%   |
| Broadcom              | 3        | 6.67%   |
| TP-Link               | 1        | 2.22%   |
| Ralink Technology     | 1        | 2.22%   |
| Unknown               | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 20%     |
| Intel I211 Gigabit Network Connection                             | 5        | 10%     |
| Intel Wi-Fi 6 AX200                                               | 4        | 8%      |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 6%      |
| Intel Ethernet Connection (2) I219-V                              | 3        | 6%      |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 4%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 2%      |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1        | 2%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2%      |
| Ralink RT5370 Wireless Adapter                                    | 1        | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1        | 2%      |
| Intel Ethernet Controller I225-V                                  | 1        | 2%      |
| Intel Ethernet controller                                         | 1        | 2%      |
| Intel Ethernet Connection I217-V                                  | 1        | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2%      |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2%      |
| Intel 82566DC Gigabit Network Connection                          | 1        | 2%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 2%      |
| Unknown                                                           | 1        | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 40%     |
| Broadcom              | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| TP-Link               | 1        | 6.67%   |
| Ralink Technology     | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 4        | 26.67%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 2        | 13.33%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 6.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1        | 6.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1        | 6.67%   |
| Ralink RT5370 Wireless Adapter                             | 1        | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 6.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 6.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                 | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 6.67%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 52.94%  |
| Realtek Semiconductor | 14       | 41.18%  |
| Qualcomm Atheros      | 2        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 29.41%  |
| Intel I211 Gigabit Network Connection                             | 5        | 14.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 8.82%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 8.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.94%   |
| Intel Ethernet controller                                         | 1        | 2.94%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.94%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 2.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.94%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 67.39%  |
| WiFi     | 14       | 30.43%  |
| Modem    | 1        | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 87.1%   |
| WiFi     | 4        | 12.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 56.25%  |
| 2     | 11       | 34.38%  |
| 3     | 3        | 9.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 87.5%   |
| Yes  | 4        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 45.45%  |
| Cambridge Silicon Radio | 3        | 27.27%  |
| IMC Networks            | 1        | 9.09%   |
| Broadcom                | 1        | 9.09%   |
| ASUSTek Computer        | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 27.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 27.27%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 9.09%   |
| Intel AX201 Bluetooth                               | 1        | 9.09%   |
| IMC Networks Bluetooth Module                       | 1        | 9.09%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 9.09%   |
| ASUS BCM20702A0                                     | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 22       | 42.31%  |
| Nvidia                         | 15       | 28.85%  |
| AMD                            | 10       | 19.23%  |
| www.hirestech.com 2010 REV 1.4 | 1        | 1.92%   |
| SteelSeries ApS                | 1        | 1.92%   |
| Sony                           | 1        | 1.92%   |
| Logitech                       | 1        | 1.92%   |
| C-Media Electronics            | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 5        | 8.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4        | 6.67%   |
| Intel 200 Series PCH HD Audio                                       | 4        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3        | 5%      |
| Nvidia High Definition Audio Controller                             | 2        | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2        | 3.33%   |
| Intel Comet Lake PCH cAVS                                           | 2        | 3.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 2        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 2        | 3.33%   |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                   | 1        | 1.67%   |
| SteelSeries ApS SteelSeries Arctis 7                                | 1        | 1.67%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                       | 1        | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                  | 1        | 1.67%   |
| Nvidia GP108 High Definition Audio Controller                       | 1        | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                       | 1        | 1.67%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1        | 1.67%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1        | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1        | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                       | 1        | 1.67%   |
| Nvidia GA102 High Definition Audio Controller                       | 1        | 1.67%   |
| Logitech QuickCam Fusion                                            | 1        | 1.67%   |
| Intel USB PnP Sound Device                                          | 1        | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1        | 1.67%   |
| Intel Jasper Lake HD Audio                                          | 1        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                               | 1        | 1.67%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 1        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                 | 1        | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                      | 1        | 1.67%   |
| Intel 8 Series HD Audio Controller                                  | 1        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1        | 1.67%   |
| C-Media Electronics Blue Snowball                                   | 1        | 1.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1        | 1.67%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                      | 1        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1        | 1.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 1        | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                              | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 4        | 22.22%  |
| Samsung Electronics | 3        | 16.67%  |
| Kingston            | 3        | 16.67%  |
| G.Skill             | 3        | 16.67%  |
| Crucial             | 2        | 11.11%  |
| Unknown             | 1        | 5.56%   |
| Qimonda             | 1        | 5.56%   |
| A-DATA Technology   | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 5.56%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s      | 1        | 5.56%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 1        | 5.56%   |
| Samsung RAM 99U5429-007.A00LF 2GB DIMM DDR2 800MT/s      | 1        | 5.56%   |
| Qimonda RAM 64T256020EU2.5C2 2048MB DIMM DDR2 800MT/s    | 1        | 5.56%   |
| Kingston RAM KHX4000C19D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 1        | 5.56%   |
| Kingston RAM 9905625-074.A00G 16384MB DIMM DDR4 2400MT/s | 1        | 5.56%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 5.56%   |
| Crucial RAM CT8G4DFS8266.C8FE 8GB DIMM DDR4 2667MT/s     | 1        | 5.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s  | 1        | 5.56%   |
| Corsair RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 5.56%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 1        | 5.56%   |
| Corsair RAM CMW16GX4M2A2666C16 8GB DIMM DDR4 2666MT/s    | 1        | 5.56%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s   | 1        | 5.56%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s             | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 11       | 61.11%  |
| DDR3   | 3        | 16.67%  |
| DDR2   | 2        | 11.11%  |
| SDRAM  | 1        | 5.56%   |
| LPDDR4 | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 15       | 88.24%  |
| SODIMM       | 1        | 5.88%   |
| Row Of Chips | 1        | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 47.06%  |
| 16384 | 4        | 23.53%  |
| 32768 | 2        | 11.76%  |
| 2048  | 2        | 11.76%  |
| 4096  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 3        | 17.65%  |
| 3400  | 2        | 11.76%  |
| 3200  | 2        | 11.76%  |
| 800   | 2        | 11.76%  |
| 3500  | 1        | 5.88%   |
| 2933  | 1        | 5.88%   |
| 2667  | 1        | 5.88%   |
| 2666  | 1        | 5.88%   |
| 2400  | 1        | 5.88%   |
| 1867  | 1        | 5.88%   |
| 1600  | 1        | 5.88%   |
| 1333  | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP OfficeJet 6950        | 1        | 33.33%  |
| HP Officejet 6600        | 1        | 33.33%  |
| HP OfficeJet 5200 series | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 75%     |
| Huawei Technologies | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech B525 HD Webcam | 2        | 50%     |
| Logitech Webcam C270    | 1        | 25%     |
| Huawei HiCamera         | 1        | 25%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 25       | 78.13%  |
| 1     | 7        | 21.88%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 2        | 28.57%  |
| Unassigned class      | 1        | 14.29%  |
| Network               | 1        | 14.29%  |
| Net/ethernet          | 1        | 14.29%  |
| Multimedia controller | 1        | 14.29%  |
| Chipcard              | 1        | 14.29%  |

