Red OS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 89

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A520M DS3H                  | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Gigabyte      | B560M H                     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| ASUSTek       | H81M-K                      | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | 3708 NOK                    | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Gigabyte      | H510M S2H                   | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| ASUSTek       | H81M-K                      | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| HP            | 1495                        | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| MSI           | H55M-E33                    | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| ASRock        | B360M-HDV                   | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| RDW           | MB-B450M V.1                | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Unknown       | Unknown                     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| ASRock        | N68-VS3 FX                  | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| ASRock        | H110M-DVS R2.0              | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00                  | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T                     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3                     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus               | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| MSI           | A520M PRO                   | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H                     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K                      | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4                   | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V                    | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS                   | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H                  | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M                     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV                   | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS                   | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H                  | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K                      | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3.1 | 39       | 54.93%  |
| Red OS 7.3   | 25       | 35.21%  |
| Red OS 7.2   | 5        | 7.04%   |
| Red OS 7.3.2 | 2        | 2.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 66       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.10-1.el7.x86_64   | 18       | 24%     |
| 5.15.35-5.el7.3.x86_64 | 15       | 20%     |
| 5.10.29-1.el7.x86_64   | 13       | 17.33%  |
| 5.15.35-1.el7.3.x86_64 | 8        | 10.67%  |
| 5.15.35-4.el7.3.x86_64 | 6        | 8%      |
| 5.15.10-3.el7.x86_64   | 3        | 4%      |
| 5.15.10-2.el7.x86_64   | 3        | 4%      |
| 4.19.79-1.el7.x86_64   | 3        | 4%      |
| 5.14.9-1.el7.x86_64    | 1        | 1.33%   |
| 5.10.24-3.el7.x86_64   | 1        | 1.33%   |
| 5.10.24-2.el7.x86_64   | 1        | 1.33%   |
| 5.10.1-1.el7.x86_64    | 1        | 1.33%   |
| 4.19.56-2.el7.x86_64   | 1        | 1.33%   |
| 4.19.204-1.el7.x86_64  | 1        | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.35  | 26       | 36.11%  |
| 5.15.10  | 24       | 33.33%  |
| 5.10.29  | 13       | 18.06%  |
| 4.19.79  | 3        | 4.17%   |
| 5.10.24  | 2        | 2.78%   |
| 5.14.9   | 1        | 1.39%   |
| 5.10.1   | 1        | 1.39%   |
| 4.19.56  | 1        | 1.39%   |
| 4.19.204 | 1        | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 49       | 69.01%  |
| 5.10    | 16       | 22.54%  |
| 4.19    | 5        | 7.04%   |
| 5.14    | 1        | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 66       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 54       | 77.14%  |
| Cinnamon   | 14       | 20%     |
| X-Cinnamon | 1        | 1.43%   |
| Unknown    | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 61       | 89.71%  |
| Wayland | 6        | 8.82%   |
| Unknown | 1        | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 63       | 94.03%  |
| SDDM    | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 94.03%  |
| ru_RU   | 4        | 5.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 44       | 64.71%  |
| BIOS | 24       | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 63       | 95.45%  |
| Btrfs   | 2        | 3.03%   |
| Unknown | 1        | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 45       | 66.18%  |
| MBR     | 21       | 30.88%  |
| Unknown | 2        | 2.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 88.24%  |
| Yes       | 8        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 80.6%   |
| Yes       | 13       | 19.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 25       | 37.88%  |
| ASUSTek Computer    | 11       | 16.67%  |
| ASRock              | 9        | 13.64%  |
| MSI                 | 5        | 7.58%   |
| DEPO Computers      | 4        | 6.06%   |
| Aquarius            | 4        | 6.06%   |
| Lenovo              | 2        | 3.03%   |
| Hewlett-Packard     | 2        | 3.03%   |
| RDW                 | 1        | 1.52%   |
| ECS                 | 1        | 1.52%   |
| Dell                | 1        | 1.52%   |
| Unknown             | 1        | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Gigabyte B365M DS3H                    | 4        | 6.06%   |
| DEPO Computers DPH310T                 | 4        | 6.06%   |
| MSI MS-7D14                            | 2        | 3.03%   |
| Gigabyte H110M-S2                      | 2        | 3.03%   |
| Gigabyte B560M DS3H                    | 2        | 3.03%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 3.03%   |
| ASUS PC                                | 2        | 3.03%   |
| RDW RDW-MB-B450M V.1                   | 1        | 1.52%   |
| MSI MS-7D35                            | 1        | 1.52%   |
| MSI MS-7636                            | 1        | 1.52%   |
| MSI Compaq dx2300 Microtower           | 1        | 1.52%   |
| Lenovo V50s-07IMB 11EF0011RU           | 1        | 1.52%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS | 1        | 1.52%   |
| HP Z400 Workstation                    | 1        | 1.52%   |
| HP Compaq 8200 Elite SFF PC            | 1        | 1.52%   |
| Gigabyte X58-USB3                      | 1        | 1.52%   |
| Gigabyte H510M S2H                     | 1        | 1.52%   |
| Gigabyte H410M H V3                    | 1        | 1.52%   |
| Gigabyte H110M-M.2                     | 1        | 1.52%   |
| Gigabyte GA-880GM-D2H                  | 1        | 1.52%   |
| Gigabyte B75M-D3V                      | 1        | 1.52%   |
| Gigabyte B75M-D2V                      | 1        | 1.52%   |
| Gigabyte B560M H                       | 1        | 1.52%   |
| Gigabyte B450M H                       | 1        | 1.52%   |
| Gigabyte B450 AORUS PRO                | 1        | 1.52%   |
| Gigabyte B365M H                       | 1        | 1.52%   |
| Gigabyte B360M-DS3H                    | 1        | 1.52%   |
| Gigabyte B360 HD3                      | 1        | 1.52%   |
| Gigabyte A520M DS3H                    | 1        | 1.52%   |
| Gigabyte 970A-D3                       | 1        | 1.52%   |
| ECS H510H6-M7                          | 1        | 1.52%   |
| Dell OptiPlex 3020                     | 1        | 1.52%   |
| ASUS PRIME H510T2/CSM                  | 1        | 1.52%   |
| ASUS PRIME H510M-K                     | 1        | 1.52%   |
| ASUS P8H61-I LX R2.0                   | 1        | 1.52%   |
| ASUS M2N68-AM Plus                     | 1        | 1.52%   |
| ASUS H110M-PLUS                        | 1        | 1.52%   |
| ASUS H110M-K                           | 1        | 1.52%   |
| ASUS H110-PLUS                         | 1        | 1.52%   |
| ASUS B150M-C                           | 1        | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B365M         | 5        | 7.58%   |
| DEPO Computers DPH310T | 4        | 6.06%   |
| Gigabyte B560M         | 3        | 4.55%   |
| MSI MS-7D14            | 2        | 3.03%   |
| Gigabyte H110M-S2      | 2        | 3.03%   |
| Gigabyte B550          | 2        | 3.03%   |
| ASUS PRIME             | 2        | 3.03%   |
| ASUS PC                | 2        | 3.03%   |
| RDW RDW-MB-B450M       | 1        | 1.52%   |
| MSI MS-7D35            | 1        | 1.52%   |
| MSI MS-7636            | 1        | 1.52%   |
| MSI Compaq             | 1        | 1.52%   |
| Lenovo V50s-07IMB      | 1        | 1.52%   |
| Lenovo IdeaCentre      | 1        | 1.52%   |
| HP Z400                | 1        | 1.52%   |
| HP Compaq              | 1        | 1.52%   |
| Gigabyte X58-USB3      | 1        | 1.52%   |
| Gigabyte H510M         | 1        | 1.52%   |
| Gigabyte H410M         | 1        | 1.52%   |
| Gigabyte H110M-M.2     | 1        | 1.52%   |
| Gigabyte GA-880GM-D2H  | 1        | 1.52%   |
| Gigabyte B75M-D3V      | 1        | 1.52%   |
| Gigabyte B75M-D2V      | 1        | 1.52%   |
| Gigabyte B450M         | 1        | 1.52%   |
| Gigabyte B450          | 1        | 1.52%   |
| Gigabyte B360M-DS3H    | 1        | 1.52%   |
| Gigabyte B360          | 1        | 1.52%   |
| Gigabyte A520M         | 1        | 1.52%   |
| Gigabyte 970A-D3       | 1        | 1.52%   |
| ECS H510H6-M7          | 1        | 1.52%   |
| Dell OptiPlex          | 1        | 1.52%   |
| ASUS P8H61-I           | 1        | 1.52%   |
| ASUS M2N68-AM          | 1        | 1.52%   |
| ASUS H110M-PLUS        | 1        | 1.52%   |
| ASUS H110M-K           | 1        | 1.52%   |
| ASUS H110-PLUS         | 1        | 1.52%   |
| ASUS B150M-C           | 1        | 1.52%   |
| ASUS All               | 1        | 1.52%   |
| ASRock N68-VS3         | 1        | 1.52%   |
| ASRock H510M-HVS       | 1        | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 17       | 25.76%  |
| 2020 | 10       | 15.15%  |
| 2019 | 8        | 12.12%  |
| 2016 | 6        | 9.09%   |
| 2022 | 5        | 7.58%   |
| 2018 | 4        | 6.06%   |
| 2012 | 4        | 6.06%   |
| 2010 | 3        | 4.55%   |
| 2011 | 2        | 3.03%   |
| 2009 | 2        | 3.03%   |
| 2017 | 1        | 1.52%   |
| 2015 | 1        | 1.52%   |
| 2014 | 1        | 1.52%   |
| 2013 | 1        | 1.52%   |
| 2007 | 1        | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 66       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 66       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 23       | 34.85%  |
| 16.01-24.0 | 19       | 28.79%  |
| 8.01-16.0  | 11       | 16.67%  |
| 3.01-4.0   | 7        | 10.61%  |
| 32.01-64.0 | 2        | 3.03%   |
| 24.01-32.0 | 2        | 3.03%   |
| 1.01-2.0   | 1        | 1.52%   |
| Unknown    | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 30       | 41.67%  |
| 4.01-8.0  | 12       | 16.67%  |
| 3.01-4.0  | 10       | 13.89%  |
| 0.51-1.0  | 10       | 13.89%  |
| 2.01-3.0  | 7        | 9.72%   |
| 8.01-16.0 | 2        | 2.78%   |
| Unknown   | 1        | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 63.24%  |
| 2      | 19       | 27.94%  |
| 4      | 3        | 4.41%   |
| 3      | 2        | 2.94%   |
| 5      | 1        | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 65.15%  |
| Yes       | 23       | 34.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 98.48%  |
| No        | 1        | 1.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 76.47%  |
| Yes       | 16       | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 86.36%  |
| Yes       | 9        | 13.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 66       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Murom         | 16       | 24.24%  |
| Moscow        | 13       | 19.7%   |
| Salekhard     | 10       | 15.15%  |
| Yekaterinburg | 4        | 6.06%   |
| Kaluga        | 2        | 3.03%   |
| Balashikha    | 2        | 3.03%   |
| Ulyanovsk     | 1        | 1.52%   |
| Tomsk         | 1        | 1.52%   |
| Surgut        | 1        | 1.52%   |
| Stavropol     | 1        | 1.52%   |
| St Petersburg | 1        | 1.52%   |
| Rostov-on-Don | 1        | 1.52%   |
| Penza         | 1        | 1.52%   |
| Novosibirsk   | 1        | 1.52%   |
| Kursk         | 1        | 1.52%   |
| Krasnoyarsk   | 1        | 1.52%   |
| Krasnodar     | 1        | 1.52%   |
| Kovrov        | 1        | 1.52%   |
| Kol'chugino   | 1        | 1.52%   |
| Kirov         | 1        | 1.52%   |
| Kholmsk       | 1        | 1.52%   |
| Khabarovsk    | 1        | 1.52%   |
| Bryansk       | 1        | 1.52%   |
| Arzamas       | 1        | 1.52%   |
| Arkhangelsk   | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 22       | 35     | 22.92%  |
| WDC                          | 13       | 15     | 13.54%  |
| Toshiba                      | 9        | 9      | 9.38%   |
| Samsung Electronics          | 8        | 12     | 8.33%   |
| Kingston                     | 8        | 8      | 8.33%   |
| A-DATA Technology            | 7        | 7      | 7.29%   |
| Apacer                       | 4        | 4      | 4.17%   |
| SanDisk                      | 3        | 4      | 3.13%   |
| Patriot                      | 3        | 3      | 3.13%   |
| Foxline                      | 3        | 3      | 3.13%   |
| KIOXIA-EXCERIA               | 2        | 2      | 2.08%   |
| Hitachi                      | 2        | 2      | 2.08%   |
| Crucial                      | 2        | 4      | 2.08%   |
| XPG                          | 1        | 1      | 1.04%   |
| Smartbuy                     | 1        | 1      | 1.04%   |
| Shenzhen Longsys Electronics | 1        | 1      | 1.04%   |
| Phison                       | 1        | 1      | 1.04%   |
| KingSpec                     | 1        | 1      | 1.04%   |
| GOODRAM                      | 1        | 1      | 1.04%   |
| ExeGate                      | 1        | 1      | 1.04%   |
| Corsair                      | 1        | 1      | 1.04%   |
| China                        | 1        | 1      | 1.04%   |
| AMD                          | 1        | 1      | 1.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seagate ST1000LM049-2GH172 1TB        | 4        | 3.96%   |
| Seagate ST1000DM010-2EP102 1TB        | 4        | 3.96%   |
| Apacer AS2280P4 256GB                 | 4        | 3.96%   |
| Toshiba HDWD110 1TB                   | 3        | 2.97%   |
| Seagate ST1000DM010-2DM162 1TB        | 3        | 2.97%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 2.97%   |
| Toshiba HDWD105 500GB                 | 2        | 1.98%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 1.98%   |
| Seagate ST1000DM003-1SB10C 1TB        | 2        | 1.98%   |
| SanDisk SD8SBAT256G1122 256GB SSD     | 2        | 1.98%   |
| Samsung SSD 860 EVO 250GB             | 2        | 1.98%   |
| KIOXIA-EXCERIA SATA SSD 480GB         | 2        | 1.98%   |
| Kingston OM8PCP3512F-A02 512GB        | 2        | 1.98%   |
| Foxline FLSSD240X5SE 240GB            | 2        | 1.98%   |
| Crucial CT240BX500SSD1 240GB          | 2        | 1.98%   |
| XPG GAMMIX S70 BLADE 2TB              | 1        | 0.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 0.99%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 0.99%   |
| WDC WD40PURZ-85TTDY0 4TB              | 1        | 0.99%   |
| WDC WD3200AAKX-001CA0 320GB           | 1        | 0.99%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 0.99%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 0.99%   |
| WDC WD15EARS-19MVWB0 1TB              | 1        | 0.99%   |
| WDC WD10SPZX-22Z10T1 1TB              | 1        | 0.99%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1        | 0.99%   |
| WDC WD10EZEX-00BBHA0 1TB              | 1        | 0.99%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 0.99%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 0.99%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB  | 1        | 0.99%   |
| Toshiba MK5075GSX 500GB               | 1        | 0.99%   |
| Toshiba KHK61VSE960G 960GB SSD        | 1        | 0.99%   |
| Toshiba DT01ACA200 2TB                | 1        | 0.99%   |
| Toshiba DT01ACA100 1TB                | 1        | 0.99%   |
| Smartbuy SSD 240GB                    | 1        | 0.99%   |
| Shenzhen Longsys NVMe SSD Drive 256GB | 1        | 0.99%   |
| Seagate ST9320325AS 320GB             | 1        | 0.99%   |
| Seagate ST3400620AS 400GB             | 1        | 0.99%   |
| Seagate ST3320620AS 320GB             | 1        | 0.99%   |
| Seagate ST3250823AS 250GB             | 1        | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 35     | 48.89%  |
| WDC                 | 11       | 13     | 24.44%  |
| Toshiba             | 8        | 8      | 17.78%  |
| Samsung Electronics | 2        | 3      | 4.44%   |
| Hitachi             | 2        | 2      | 4.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 15.15%  |
| A-DATA Technology   | 5        | 5      | 15.15%  |
| Samsung Electronics | 4        | 5      | 12.12%  |
| SanDisk             | 3        | 4      | 9.09%   |
| Foxline             | 3        | 3      | 9.09%   |
| Patriot             | 2        | 2      | 6.06%   |
| KIOXIA-EXCERIA      | 2        | 2      | 6.06%   |
| Crucial             | 2        | 4      | 6.06%   |
| WDC                 | 1        | 1      | 3.03%   |
| Toshiba             | 1        | 1      | 3.03%   |
| Smartbuy            | 1        | 1      | 3.03%   |
| KingSpec            | 1        | 1      | 3.03%   |
| GOODRAM             | 1        | 1      | 3.03%   |
| ExeGate             | 1        | 1      | 3.03%   |
| China               | 1        | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 61     | 45.05%  |
| SSD  | 32       | 37     | 35.16%  |
| NVMe | 18       | 20     | 19.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 98     | 76.62%  |
| NVMe | 18       | 20     | 23.38%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 45     | 48.65%  |
| 0.51-1.0   | 31       | 45     | 41.89%  |
| 1.01-2.0   | 5        | 6      | 6.76%   |
| 3.01-4.0   | 1        | 1      | 1.35%   |
| 2.01-3.0   | 1        | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 29.41%  |
| 501-1000       | 19       | 27.94%  |
| 251-500        | 13       | 19.12%  |
| 51-100         | 6        | 8.82%   |
| 1001-2000      | 4        | 5.88%   |
| 2001-3000      | 3        | 4.41%   |
| More than 3000 | 1        | 1.47%   |
| 21-50          | 1        | 1.47%   |
| Unknown        | 1        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 56.34%  |
| 21-50          | 9        | 12.68%  |
| 501-1000       | 7        | 9.86%   |
| 51-100         | 6        | 8.45%   |
| 251-500        | 3        | 4.23%   |
| 101-250        | 3        | 4.23%   |
| More than 3000 | 1        | 1.41%   |
| 1001-2000      | 1        | 1.41%   |
| Unknown        | 1        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1      | 16.67%  |
| WDC WD3200AAKX-001CA0 320GB      | 1        | 1      | 16.67%  |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 1      | 16.67%  |
| Seagate ST3250823AS 250GB        | 1        | 1      | 16.67%  |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 4      | 16.67%  |
| Hitachi HDS5C1050CLA382 500GB    | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 50%     |
| Seagate | 2        | 5      | 33.33%  |
| Hitachi | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 40%     |
| Seagate | 2        | 5      | 40%     |
| Hitachi | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 8      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Works    | 62       | 104    | 89.86%  |
| Malfunc  | 5        | 9      | 7.25%   |
| Detected | 2        | 5      | 2.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 52       | 60.47%  |
| AMD                          | 12       | 13.95%  |
| Phison Electronics           | 6        | 6.98%   |
| Samsung Electronics          | 3        | 3.49%   |
| Kingston Technology Company  | 3        | 3.49%   |
| Realtek Semiconductor        | 2        | 2.33%   |
| Nvidia                       | 2        | 2.33%   |
| Silicon Motion               | 1        | 1.16%   |
| Shenzhen Longsys Electronics | 1        | 1.16%   |
| SanDisk                      | 1        | 1.16%   |
| MAXIO Technology (Hangzhou)  | 1        | 1.16%   |
| JMicron Technology           | 1        | 1.16%   |
| ADATA Technology             | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16       | 16.49%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 10.31%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 8.25%   |
| Phison PS5013 E13 NVMe Controller                                                       | 5        | 5.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 5.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 4.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 4.12%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3        | 3.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.09%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 2.06%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 2.06%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 2.06%   |
| Nvidia MCP61 IDE                                                                        | 2        | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.03%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                             | 1        | 1.03%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.03%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 1.03%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.03%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.03%   |
| Intel 300 Series Chipset Family SATA RAID Controller                                    | 1        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 67.06%  |
| NVMe | 18       | 21.18%  |
| IDE  | 8        | 9.41%   |
| RAID | 2        | 2.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 52       | 78.79%  |
| AMD    | 14       | 21.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz              | 10       | 15.15%  |
| Intel Core i3-10100 CPU @ 3.60GHz             | 9        | 13.64%  |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 4.55%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 2        | 3.03%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2        | 3.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2        | 3.03%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2        | 3.03%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2        | 3.03%   |
| AMD FX-4100 Quad-Core Processor               | 2        | 3.03%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 1.52%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1        | 1.52%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 1.52%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1        | 1.52%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1        | 1.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1        | 1.52%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1        | 1.52%   |
| Intel Core i7 CPU 950 @ 3.07GHz               | 1        | 1.52%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 1.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 1.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1        | 1.52%   |
| Intel Core i5-10600K CPU @ 4.10GHz            | 1        | 1.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 1        | 1.52%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1        | 1.52%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 1.52%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 1        | 1.52%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1        | 1.52%   |
| Intel Core 2 CPU 6600 @ 2.40GHz               | 1        | 1.52%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 1.52%   |
| Intel Celeron G5925 CPU @ 3.60GHz             | 1        | 1.52%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 1        | 1.52%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1        | 1.52%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1        | 1.52%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1        | 1.52%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1        | 1.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 1        | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1        | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1        | 1.52%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 1        | 1.52%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1        | 1.52%   |
| AMD FX-6300 Six-Core Processor                | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 22       | 33.33%  |
| Intel Core i3      | 15       | 22.73%  |
| AMD Ryzen 5        | 5        | 7.58%   |
| Intel Pentium      | 4        | 6.06%   |
| Intel Core i7      | 3        | 4.55%   |
| Intel Celeron      | 3        | 4.55%   |
| AMD FX             | 3        | 4.55%   |
| Intel Pentium Gold | 2        | 3.03%   |
| AMD Ryzen 7 PRO    | 2        | 3.03%   |
| Other              | 1        | 1.52%   |
| Intel Xeon         | 1        | 1.52%   |
| Intel Core 2       | 1        | 1.52%   |
| AMD Ryzen 7        | 1        | 1.52%   |
| AMD Ryzen 5 PRO    | 1        | 1.52%   |
| AMD Ryzen 3        | 1        | 1.52%   |
| AMD Athlon II X2   | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 34.85%  |
| 6      | 22       | 33.33%  |
| 2      | 16       | 24.24%  |
| 8      | 4        | 6.06%   |
| 3      | 1        | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 59.09%  |
| 1      | 27       | 40.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 98.48%  |
| Unknown        | 1        | 1.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 17       | 25.37%  |
| 0x906ed    | 8        | 11.94%  |
| 0x506e3    | 7        | 10.45%  |
| 0x906ea    | 4        | 5.97%   |
| 0x306a9    | 3        | 4.48%   |
| 0x08600106 | 3        | 4.48%   |
| 0x306c3    | 2        | 2.99%   |
| 0x0a50000d | 2        | 2.99%   |
| 0x08108109 | 2        | 2.99%   |
| 0x0600063e | 2        | 2.99%   |
| 0xa0671    | 1        | 1.49%   |
| 0xa0655    | 1        | 1.49%   |
| 0xa0654    | 1        | 1.49%   |
| 0x906eb    | 1        | 1.49%   |
| 0x906e9    | 1        | 1.49%   |
| 0x706a8    | 1        | 1.49%   |
| 0x6f6      | 1        | 1.49%   |
| 0x206c2    | 1        | 1.49%   |
| 0x206a7    | 1        | 1.49%   |
| 0x20652    | 1        | 1.49%   |
| 0x106a5    | 1        | 1.49%   |
| 0x0a201016 | 1        | 1.49%   |
| 0x08701021 | 1        | 1.49%   |
| 0x08101016 | 1        | 1.49%   |
| 0x06000852 | 1        | 1.49%   |
| 0x010000c7 | 1        | 1.49%   |
| Unknown    | 1        | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| CometLake     | 19       | 28.79%  |
| KabyLake      | 14       | 21.21%  |
| Skylake       | 7        | 10.61%  |
| Zen 2         | 4        | 6.06%   |
| Zen 3         | 3        | 4.55%   |
| IvyBridge     | 3        | 4.55%   |
| Zen+          | 2        | 3.03%   |
| Westmere      | 2        | 3.03%   |
| Haswell       | 2        | 3.03%   |
| Bulldozer     | 2        | 3.03%   |
| Zen           | 1        | 1.52%   |
| SandyBridge   | 1        | 1.52%   |
| Piledriver    | 1        | 1.52%   |
| Nehalem       | 1        | 1.52%   |
| K10           | 1        | 1.52%   |
| Goldmont plus | 1        | 1.52%   |
| Core          | 1        | 1.52%   |
| Unknown       | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 44       | 64.71%  |
| AMD    | 14       | 20.59%  |
| Nvidia | 10       | 14.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 21.74%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 15.94%  |
| Intel HD Graphics 530                                                       | 4        | 5.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.35%   |
| AMD Renoir                                                                  | 3        | 4.35%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.9%    |
| AMD Cezanne                                                                 | 2        | 2.9%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 1.45%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.45%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.45%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.45%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 1.45%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.45%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.45%   |
| Intel HD Graphics 610                                                       | 1        | 1.45%   |
| Intel HD Graphics 510                                                       | 1        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.45%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.45%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 1.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.45%   |
| AMD RV770 [Radeon HD 4850]                                                  | 1        | 1.45%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                       | 1        | 1.45%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                   | 1        | 1.45%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.45%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 1        | 1.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.45%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 42       | 63.64%  |
| 1 x AMD        | 13       | 19.7%   |
| 1 x Nvidia     | 9        | 13.64%  |
| 2 x AMD        | 1        | 1.52%   |
| Intel + Nvidia | 1        | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 52       | 78.79%  |
| Unknown     | 12       | 18.18%  |
| Proprietary | 2        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 69.7%   |
| 1.01-2.0   | 9        | 13.64%  |
| 0.01-0.5   | 5        | 7.58%   |
| 0.51-1.0   | 3        | 4.55%   |
| 3.01-4.0   | 2        | 3.03%   |
| 2.01-3.0   | 1        | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 11       | 18.03%  |
| ViewSonic            | 10       | 16.39%  |
| Samsung Electronics  | 8        | 13.11%  |
| BenQ                 | 7        | 11.48%  |
| Acer                 | 7        | 11.48%  |
| AOC                  | 4        | 6.56%   |
| SGT                  | 2        | 3.28%   |
| Hewlett-Packard      | 2        | 3.28%   |
| Goldstar             | 2        | 3.28%   |
| Dell                 | 2        | 3.28%   |
| Sony                 | 1        | 1.64%   |
| Lenovo               | 1        | 1.64%   |
| HUAWEI               | 1        | 1.64%   |
| DOY                  | 1        | 1.64%   |
| CHR                  | 1        | 1.64%   |
| Ancor Communications | 1        | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 6        | 9.52%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 4        | 6.35%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 2        | 3.17%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 3.17%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 2        | 3.17%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 3.17%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 3.17%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch               | 2        | 3.17%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 2        | 3.17%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 2        | 3.17%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 1.59%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1        | 1.59%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                    | 1        | 1.59%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 1.59%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 1.59%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 1.59%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 1.59%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch    | 1        | 1.59%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 1.59%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch              | 1        | 1.59%   |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch             | 1        | 1.59%   |
| Philips 190VL PHLC080 1440x900 408x255mm 18.9-inch                    | 1        | 1.59%   |
| Lenovo S24e-20 LEN62AE 1920x1080 527x296mm 23.8-inch                  | 1        | 1.59%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 1.59%   |
| Hewlett-Packard Z22i HWP308E 1920x1080 477x268mm 21.5-inch            | 1        | 1.59%   |
| Hewlett-Packard LP2065 HWP0A71 1600x1200 408x306mm 20.1-inch          | 1        | 1.59%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 1        | 1.59%   |
| Goldstar E2250 GSM578E 1920x1080 477x268mm 21.5-inch                  | 1        | 1.59%   |
| DOY LCD Monitor DOY2760 1920x1080 598x336mm 27.0-inch                 | 1        | 1.59%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1        | 1.59%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 1        | 1.59%   |
| CHR CH7511B CHR7511 1024x768 519x324mm 24.1-inch                      | 1        | 1.59%   |
| BenQ V2420H BNQ7B14 1920x1080 531x299mm 24.0-inch                     | 1        | 1.59%   |
| BenQ V2200Eco BNQ7D03 1920x1080 477x268mm 21.5-inch                   | 1        | 1.59%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 1        | 1.59%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 1        | 1.59%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 1        | 1.59%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 1        | 1.59%   |
| AOC 2250W AOC2250 1920x1080 480x270mm 21.7-inch                       | 1        | 1.59%   |
| Ancor Communications PA246 ACIFF24 1920x1200 546x352mm 25.6-inch      | 1        | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 41       | 71.93%  |
| 2560x1440 (QHD)   | 6        | 10.53%  |
| 1280x1024 (SXGA)  | 3        | 5.26%   |
| 1920x1200 (WUXGA) | 2        | 3.51%   |
| 3840x2160 (4K)    | 1        | 1.75%   |
| 1600x900 (HD+)    | 1        | 1.75%   |
| 1600x1200         | 1        | 1.75%   |
| 1440x900 (WXGA+)  | 1        | 1.75%   |
| 1024x768 (XGA)    | 1        | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 16       | 26.23%  |
| 23     | 15       | 24.59%  |
| 21     | 10       | 16.39%  |
| 27     | 9        | 14.75%  |
| 19     | 3        | 4.92%   |
| 31     | 2        | 3.28%   |
| 20     | 2        | 3.28%   |
| 32     | 1        | 1.64%   |
| 25     | 1        | 1.64%   |
| 18     | 1        | 1.64%   |
| 15     | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 36       | 64.29%  |
| 401-500     | 13       | 23.21%  |
| 351-400     | 3        | 5.36%   |
| 601-700     | 2        | 3.57%   |
| 701-800     | 1        | 1.79%   |
| 301-350     | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 48       | 84.21%  |
| 16/10 | 4        | 7.02%   |
| 5/4   | 3        | 5.26%   |
| 4/3   | 2        | 3.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 59.32%  |
| 301-350        | 9        | 15.25%  |
| 151-200        | 8        | 13.56%  |
| 351-500        | 3        | 5.08%   |
| 251-300        | 3        | 5.08%   |
| 101-110        | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 71.7%   |
| 101-120 | 15       | 28.3%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 73.91%  |
| 0     | 11       | 15.94%  |
| 2     | 7        | 10.14%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 52       | 64.2%   |
| Intel                 | 16       | 19.75%  |
| TP-Link               | 2        | 2.47%   |
| Samsung Electronics   | 2        | 2.47%   |
| Nvidia                | 2        | 2.47%   |
| Broadcom              | 2        | 2.47%   |
| Ralink Technology     | 1        | 1.23%   |
| Qualcomm Atheros      | 1        | 1.23%   |
| Mercucys              | 1        | 1.23%   |
| MediaTek              | 1        | 1.23%   |
| Edimax Technology     | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 51.14%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.55%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.27%   |
| Nvidia MCP61 Ethernet                                             | 2        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.27%   |
| TP-Link USB 10/100 LAN                                            | 1        | 1.14%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.14%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.14%   |
| Realtek 802.11ac NIC                                              | 1        | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.14%   |
| Mercucys 802.11n NIC                                              | 1        | 1.14%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1        | 1.14%   |
| Intel Wireless 3165                                               | 1        | 1.14%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.14%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.14%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.14%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                              | 1        | 1.14%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 62.5%   |
| TP-Link               | 1        | 6.25%   |
| Ralink Technology     | 1        | 6.25%   |
| Mercucys              | 1        | 6.25%   |
| Intel                 | 1        | 6.25%   |
| Edimax Technology     | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 4        | 25%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 4        | 25%     |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                      | 1        | 6.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter          | 1        | 6.25%   |
| Realtek 802.11ac NIC                                     | 1        | 6.25%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 6.25%   |
| Mercucys 802.11n NIC                                     | 1        | 6.25%   |
| Intel Wireless 3165                                      | 1        | 6.25%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                     | 1        | 6.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter       | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 47       | 67.14%  |
| Intel                 | 15       | 21.43%  |
| Samsung Electronics   | 2        | 2.86%   |
| Nvidia                | 2        | 2.86%   |
| TP-Link               | 1        | 1.43%   |
| Qualcomm Atheros      | 1        | 1.43%   |
| MediaTek              | 1        | 1.43%   |
| Broadcom              | 1        | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 62.5%   |
| Intel Ethernet Controller I225-V                                  | 4        | 5.56%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.78%   |
| Nvidia MCP61 Ethernet                                             | 2        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.78%   |
| TP-Link USB 10/100 LAN                                            | 1        | 1.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.39%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1        | 1.39%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 80.25%  |
| WiFi     | 16       | 19.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 92.54%  |
| WiFi     | 5        | 7.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 81.82%  |
| 2     | 12       | 18.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 66.67%  |
| TP-Link               | 1        | 11.11%  |
| Intel                 | 1        | 11.11%  |
| Broadcom              | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                          | 6        | 66.67%  |
| TP-Link TPuLink UB500 Adapter                    | 1        | 11.11%  |
| Intel Bluetooth wireless interface               | 1        | 11.11%  |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 52       | 64.2%   |
| AMD                 | 16       | 19.75%  |
| Nvidia              | 9        | 11.11%  |
| C-Media Electronics | 2        | 2.47%   |
| Texas Instruments   | 1        | 1.23%   |
| Razer USA           | 1        | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 15       | 16.13%  |
| Intel 200 Series PCH HD Audio                                              | 10       | 10.75%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8        | 8.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 8.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 5.38%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 3.23%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.15%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.08%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.08%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.08%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.08%   |
| C-Media Electronics USB PnP Sound Device                                   | 1        | 1.08%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.08%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 1.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 12       | 17.65%  |
| Kingston            | 10       | 14.71%  |
| Foxline             | 8        | 11.76%  |
| Unknown             | 7        | 10.29%  |
| AMD                 | 5        | 7.35%   |
| Samsung Electronics | 4        | 5.88%   |
| Patriot             | 4        | 5.88%   |
| SK hynix            | 3        | 4.41%   |
| Corsair             | 2        | 2.94%   |
| Apacer              | 2        | 2.94%   |
| A-DATA Technology   | 2        | 2.94%   |
| Unknown             | 2        | 2.94%   |
| Unknown (ABCD)      | 1        | 1.47%   |
| Qumo                | 1        | 1.47%   |
| Neo Forza           | 1        | 1.47%   |
| Good Wealth         | 1        | 1.47%   |
| Golden Empire       | 1        | 1.47%   |
| Elpida              | 1        | 1.47%   |
| ChangXin Memory     | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s            | 4        | 5.71%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s          | 4        | 5.71%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 3        | 4.29%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 2.86%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s              | 2        | 2.86%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s       | 2        | 2.86%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s       | 2        | 2.86%   |
| Unknown                                                      | 2        | 2.86%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 1        | 1.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 1        | 1.43%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 1        | 1.43%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.43%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.43%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1        | 1.43%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 1        | 1.43%   |
| Samsung RAM M378B5273DH0 4GB DIMM DDR3 1333MT/s              | 1        | 1.43%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s          | 1        | 1.43%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s             | 1        | 1.43%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s              | 1        | 1.43%   |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 3200MT/s            | 1        | 1.43%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 1        | 1.43%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 1.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 1        | 1.43%   |
| Kingston RAM 99U5734-036.A00G 16GB DIMM DDR4 2667MT/s        | 1        | 1.43%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.43%   |
| Kingston RAM 99U5471-060.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 1.43%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 1.43%   |
| Kingston RAM 99P5700-014.A00G 8GB SODIMM DDR4 2667MT/s       | 1        | 1.43%   |
| Kingston RAM 99P5663-010.A00G 16GB SODIMM DDR4 2667MT/s      | 1        | 1.43%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s         | 1        | 1.43%   |
| Good Wealth RAM QUM4U-8G3200P22 8GB DIMM DDR4 2666MT/s       | 1        | 1.43%   |
| Golden Empire RAM CL23-23-23 D4-3200 8GB DIMM DDR4 2933MT/s  | 1        | 1.43%   |
| Elpida RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 1.43%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s       | 1        | 1.43%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s         | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 48       | 77.42%  |
| DDR3    | 7        | 11.29%  |
| Unknown | 3        | 4.84%   |
| DDR2    | 2        | 3.23%   |
| SDRAM   | 1        | 1.61%   |
| LPDDR4  | 1        | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 52       | 83.87%  |
| SODIMM | 10       | 16.13%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 36       | 52.17%  |
| 4096  | 16       | 23.19%  |
| 16384 | 7        | 10.14%  |
| 2048  | 6        | 8.7%    |
| 32768 | 2        | 2.9%    |
| 1024  | 2        | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 20       | 30.3%   |
| 3200    | 10       | 15.15%  |
| 1333    | 6        | 9.09%   |
| 2400    | 5        | 7.58%   |
| 2133    | 4        | 6.06%   |
| 2934    | 2        | 3.03%   |
| 2933    | 2        | 3.03%   |
| 2800    | 2        | 3.03%   |
| 2666    | 2        | 3.03%   |
| 1600    | 2        | 3.03%   |
| 3466    | 1        | 1.52%   |
| 3400    | 1        | 1.52%   |
| 3000    | 1        | 1.52%   |
| 2866    | 1        | 1.52%   |
| 2733    | 1        | 1.52%   |
| 1800    | 1        | 1.52%   |
| 800     | 1        | 1.52%   |
| 667     | 1        | 1.52%   |
| 400     | 1        | 1.52%   |
| 333     | 1        | 1.52%   |
| Unknown | 1        | 1.52%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 4        | 28.57%  |
| SunplusIT             | 3        | 21.43%  |
| Logitech              | 2        | 14.29%  |
| Realtek Semiconductor | 1        | 7.14%   |
| Creative Technology   | 1        | 7.14%   |
| Arkmicro Technologies | 1        | 7.14%   |
| Apple                 | 1        | 7.14%   |
| AlcorMicroCorp        | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SunplusIT 5M-A2SP Webcam          | 3        | 21.43%  |
| Alcor Micro USB 2.0 PC Camera     | 3        | 21.43%  |
| Logitech HD Webcam C615           | 2        | 14.29%  |
| Realtek 1080p Camera              | 1        | 7.14%   |
| Creative VF0530 Live! Cam Chat IM | 1        | 7.14%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 7.14%   |
| Apple iPhone 5/5C/5S/6/SE         | 1        | 7.14%   |
| AlcorMicroCorp SHUNCCM            | 1        | 7.14%   |
| Alcor Micro USB2.0 Camera         | 1        | 7.14%   |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Aladdin R.D. | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Aladdin R.D. JaCarta | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 53       | 77.94%  |
| 1     | 15       | 22.06%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 12       | 80%     |
| Net/wireless  | 2        | 13.33%  |
| Chipcard      | 1        | 6.67%   |

