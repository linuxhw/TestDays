Red OS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Red OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Red_OS/Desktop/README.md) and [notebooks](/Dist/Red_OS/Notebook/README.md).

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

Total: 78

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Kraftway      | ACCORD                      | Notebook    | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| Aquarius      | NS685U                      | Notebook    | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| ICL           | Unknown                     | Notebook    | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| iRU           | v1.0                        | Mini pc     | [845212ce42](https://linux-hardware.org/?probe=845212ce42) | Jun 02, 2022 |
| iRU           | v1.0                        | Mini pc     | [dab83a5e53](https://linux-hardware.org/?probe=dab83a5e53) | Jun 02, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3a12e41029](https://linux-hardware.org/?probe=3a12e41029) | Jun 01, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| Pegatron      | A35                         | Notebook    | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3   | 31        | 49.21%  |
| Red OS 7.3.1 | 27        | 42.86%  |
| Red OS 7.2   | 5         | 7.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.29-1.el7.x86_64   | 19        | 28.79%  |
| 5.15.35-1.el7.3.x86_64 | 9         | 13.64%  |
| 5.15.10-1.el7.x86_64   | 8         | 12.12%  |
| 5.15.10-2.el7.x86_64   | 5         | 7.58%   |
| 5.15.10-3.el7.x86_64   | 4         | 6.06%   |
| 5.10.1-1.el7.x86_64    | 4         | 6.06%   |
| 5.10.24-2.el7.x86_64   | 3         | 4.55%   |
| 4.19.79-1.el7.x86_64   | 3         | 4.55%   |
| 5.18.1-1.el7.x86_64    | 2         | 3.03%   |
| 5.15.10-4.el7.x86_64   | 2         | 3.03%   |
| 5.15.35-4.el7.3.x86_64 | 1         | 1.52%   |
| 5.14.9-1.el7.x86_64    | 1         | 1.52%   |
| 5.13.15-1.el7.x86_64   | 1         | 1.52%   |
| 5.10.24-3.el7.x86_64   | 1         | 1.52%   |
| 5.10.24-1.el7.x86_64   | 1         | 1.52%   |
| 4.19.56-2.el7.x86_64   | 1         | 1.52%   |
| 4.19.204-1.el7.x86_64  | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.10  | 19        | 28.79%  |
| 5.10.29  | 19        | 28.79%  |
| 5.15.35  | 10        | 15.15%  |
| 5.10.24  | 5         | 7.58%   |
| 5.10.1   | 4         | 6.06%   |
| 4.19.79  | 3         | 4.55%   |
| 5.18.1   | 2         | 3.03%   |
| 5.14.9   | 1         | 1.52%   |
| 5.13.15  | 1         | 1.52%   |
| 4.19.56  | 1         | 1.52%   |
| 4.19.204 | 1         | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 44.62%  |
| 5.10    | 27        | 41.54%  |
| 4.19    | 5         | 7.69%   |
| 5.18    | 2         | 3.08%   |
| 5.14    | 1         | 1.54%   |
| 5.13    | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 46        | 74.19%  |
| Cinnamon   | 14        | 22.58%  |
| X-Cinnamon | 1         | 1.61%   |
| Unknown    | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 50        | 83.33%  |
| Wayland | 9         | 15%     |
| Unknown | 1         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 57        | 96.61%  |
| SDDM    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 93.22%  |
| ru_RU   | 3         | 5.08%   |
| en_US   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 76.67%  |
| BIOS | 14        | 23.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 93.22%  |
| Btrfs   | 3         | 5.08%   |
| Unknown | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 46        | 77.97%  |
| MBR     | 12        | 20.34%  |
| Unknown | 1         | 1.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 89.83%  |
| Yes       | 6         | 10.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 76.67%  |
| Yes       | 14        | 23.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 12        | 20.69%  |
| Gigabyte Technology | 11        | 18.97%  |
| Aquarius            | 7         | 12.07%  |
| Lenovo              | 6         | 10.34%  |
| Hewlett-Packard     | 4         | 6.9%    |
| MSI                 | 3         | 5.17%   |
| HUAWEI              | 3         | 5.17%   |
| ASRock              | 3         | 5.17%   |
| ICL                 | 2         | 3.45%   |
| Pegatron            | 1         | 1.72%   |
| mtech               | 1         | 1.72%   |
| Kraftway            | 1         | 1.72%   |
| iRU                 | 1         | 1.72%   |
| Digma               | 1         | 1.72%   |
| Acer                | 1         | 1.72%   |
| 3Logic Group        | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Gigabyte B365M DS3H                 | 3         | 5.17%   |
| MSI MS-7D14                         | 2         | 3.45%   |
| Gigabyte B560M DS3H                 | 2         | 3.45%   |
| Pegatron A35                        | 1         | 1.72%   |
| mtech MTL1578                       | 1         | 1.72%   |
| MSI MS-7D35                         | 1         | 1.72%   |
| Lenovo ThinkCentre M720q 10T8S08X00 | 1         | 1.72%   |
| Lenovo ThinkCentre M70q 11DT003QRU  | 1         | 1.72%   |
| Lenovo ThinkBook 15 G3 ACL 21A4     | 1         | 1.72%   |
| Lenovo ThinkBook 14-IIL 20SL        | 1         | 1.72%   |
| Lenovo IdeaPad L340-15IWL 81LG      | 1         | 1.72%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 1         | 1.72%   |
| Kraftway ACCORD                     | 1         | 1.72%   |
| iRU P11AP                           | 1         | 1.72%   |
| ICL RAYbook Si1514                  | 1         | 1.72%   |
| HUAWEI NBLK-WAX9X                   | 1         | 1.72%   |
| HUAWEI BOHL-WXX9                    | 1         | 1.72%   |
| HUAWEI BOD-WXX9                     | 1         | 1.72%   |
| HP Z400 Workstation                 | 1         | 1.72%   |
| HP Pavilion g6                      | 1         | 1.72%   |
| HP Laptop 15s-eq1xxx                | 1         | 1.72%   |
| HP Laptop 15-dw3xxx                 | 1         | 1.72%   |
| Gigabyte H410M H V3                 | 1         | 1.72%   |
| Gigabyte H110M-M.2                  | 1         | 1.72%   |
| Gigabyte B75M-D3V                   | 1         | 1.72%   |
| Gigabyte B75M-D2V                   | 1         | 1.72%   |
| Gigabyte B365M H                    | 1         | 1.72%   |
| Gigabyte B360M-DS3H                 | 1         | 1.72%   |
| Digma CITI 10 C402T CS1044EW        | 1         | 1.72%   |
| ASUS X75VD                          | 1         | 1.72%   |
| ASUS V241IC-R                       | 1         | 1.72%   |
| ASUS TUF Gaming FX705DT_FX705DT     | 1         | 1.72%   |
| ASUS PRIME H510T2/CSM               | 1         | 1.72%   |
| ASUS PRIME H510M-K                  | 1         | 1.72%   |
| ASUS PC                             | 1         | 1.72%   |
| ASUS P8H61-I LX R2.0                | 1         | 1.72%   |
| ASUS M2N68-AM Plus                  | 1         | 1.72%   |
| ASUS H110M-PLUS                     | 1         | 1.72%   |
| ASUS H110M-K                        | 1         | 1.72%   |
| ASUS H110-PLUS                      | 1         | 1.72%   |
| ASUS All Series                     | 1         | 1.72%   |
| ASRock H470M-HDV                    | 1         | 1.72%   |
| ASRock B560 Pro4                    | 1         | 1.72%   |
| ASRock B365M Pro4-F                 | 1         | 1.72%   |
| Aquarius Pro T584                   | 1         | 1.72%   |
| Aquarius Pro T514 R53               | 1         | 1.72%   |
| Aquarius P30 K44 R53                | 1         | 1.72%   |
| Aquarius NS685U                     | 1         | 1.72%   |
| Aquarius NS585 R32                  | 1         | 1.72%   |
| Aquarius AQH410T                    | 1         | 1.72%   |
| Aquarius AQB560M                    | 1         | 1.72%   |
| Acer TravelMate P215-53             | 1         | 1.72%   |
| 3Logic Group APM Graviton A15i-K2   | 1         | 1.72%   |
| Unknown                             | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Gigabyte B365M      | 4         | 6.9%    |
| MSI MS-7D14         | 2         | 3.45%   |
| Lenovo ThinkCentre  | 2         | 3.45%   |
| Lenovo ThinkBook    | 2         | 3.45%   |
| Lenovo IdeaPad      | 2         | 3.45%   |
| HP Laptop           | 2         | 3.45%   |
| Gigabyte B560M      | 2         | 3.45%   |
| ASUS PRIME          | 2         | 3.45%   |
| Aquarius Pro        | 2         | 3.45%   |
| Pegatron A35        | 1         | 1.72%   |
| mtech MTL1578       | 1         | 1.72%   |
| MSI MS-7D35         | 1         | 1.72%   |
| Kraftway ACCORD     | 1         | 1.72%   |
| iRU P11AP           | 1         | 1.72%   |
| ICL RAYbook         | 1         | 1.72%   |
| HUAWEI NBLK-WAX9X   | 1         | 1.72%   |
| HUAWEI BOHL-WXX9    | 1         | 1.72%   |
| HUAWEI BOD-WXX9     | 1         | 1.72%   |
| HP Z400             | 1         | 1.72%   |
| HP Pavilion         | 1         | 1.72%   |
| Gigabyte H410M      | 1         | 1.72%   |
| Gigabyte H110M-M.2  | 1         | 1.72%   |
| Gigabyte B75M-D3V   | 1         | 1.72%   |
| Gigabyte B75M-D2V   | 1         | 1.72%   |
| Gigabyte B360M-DS3H | 1         | 1.72%   |
| Digma CITI          | 1         | 1.72%   |
| ASUS X75VD          | 1         | 1.72%   |
| ASUS V241IC-R       | 1         | 1.72%   |
| ASUS TUF            | 1         | 1.72%   |
| ASUS PC             | 1         | 1.72%   |
| ASUS P8H61-I        | 1         | 1.72%   |
| ASUS M2N68-AM       | 1         | 1.72%   |
| ASUS H110M-PLUS     | 1         | 1.72%   |
| ASUS H110M-K        | 1         | 1.72%   |
| ASUS H110-PLUS      | 1         | 1.72%   |
| ASUS All            | 1         | 1.72%   |
| ASRock H470M-HDV    | 1         | 1.72%   |
| ASRock B560         | 1         | 1.72%   |
| ASRock B365M        | 1         | 1.72%   |
| Aquarius P30        | 1         | 1.72%   |
| Aquarius NS685U     | 1         | 1.72%   |
| Aquarius NS585      | 1         | 1.72%   |
| Aquarius AQH410T    | 1         | 1.72%   |
| Aquarius AQB560M    | 1         | 1.72%   |
| Acer TravelMate     | 1         | 1.72%   |
| 3Logic Group APM    | 1         | 1.72%   |
| Unknown             | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 20        | 34.48%  |
| 2019 | 11        | 18.97%  |
| 2020 | 9         | 15.52%  |
| 2012 | 5         | 8.62%   |
| 2022 | 3         | 5.17%   |
| 2016 | 3         | 5.17%   |
| 2018 | 2         | 3.45%   |
| 2017 | 1         | 1.72%   |
| 2013 | 1         | 1.72%   |
| 2011 | 1         | 1.72%   |
| 2010 | 1         | 1.72%   |
| 2009 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 31        | 53.45%  |
| Notebook   | 21        | 36.21%  |
| Mini pc    | 3         | 5.17%   |
| All in one | 2         | 3.45%   |
| Tablet     | 1         | 1.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 41.38%  |
| 16.01-24.0 | 15        | 25.86%  |
| 8.01-16.0  | 9         | 15.52%  |
| 3.01-4.0   | 8         | 13.79%  |
| 24.01-32.0 | 1         | 1.72%   |
| Unknown    | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 23        | 35.94%  |
| 0.51-1.0  | 12        | 18.75%  |
| 4.01-8.0  | 11        | 17.19%  |
| 2.01-3.0  | 9         | 14.06%  |
| 3.01-4.0  | 7         | 10.94%  |
| 8.01-16.0 | 1         | 1.56%   |
| Unknown   | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 73.33%  |
| 2      | 15        | 25%     |
| 3      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 74.58%  |
| Yes       | 15        | 25.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 91.38%  |
| No        | 5         | 8.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 56.67%  |
| No        | 26        | 43.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 55.17%  |
| Yes       | 26        | 44.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 57        | 98.28%  |
| Ukraine | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Murom         | 22        | 37.93%  |
| Moscow        | 11        | 18.97%  |
| Salekhard     | 4         | 6.9%    |
| Kursk         | 3         | 5.17%   |
| Yekaterinburg | 2         | 3.45%   |
| Vladimir      | 2         | 3.45%   |
| Krasnodar     | 2         | 3.45%   |
| Yaroslavl     | 1         | 1.72%   |
| Surgut        | 1         | 1.72%   |
| Stavropol     | 1         | 1.72%   |
| Sevastopol    | 1         | 1.72%   |
| Perm          | 1         | 1.72%   |
| Penza         | 1         | 1.72%   |
| Novosibirsk   | 1         | 1.72%   |
| Kovrov        | 1         | 1.72%   |
| Kirov         | 1         | 1.72%   |
| Kaluga        | 1         | 1.72%   |
| Bryansk       | 1         | 1.72%   |
| Arzamas       | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 25     | 20.83%  |
| WDC                 | 10        | 12     | 13.89%  |
| A-DATA Technology   | 8         | 8      | 11.11%  |
| Samsung Electronics | 5         | 5      | 6.94%   |
| Toshiba             | 4         | 4      | 5.56%   |
| Foxline             | 4         | 4      | 5.56%   |
| SanDisk             | 3         | 4      | 4.17%   |
| Crucial             | 3         | 5      | 4.17%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 4      | 2.78%   |
| KIOXIA-EXCERIA      | 2         | 2      | 2.78%   |
| Kingston            | 2         | 2      | 2.78%   |
| Unknown             | 2         | 3      | 2.78%   |
| Transcend           | 1         | 1      | 1.39%   |
| Smartbuy            | 1         | 1      | 1.39%   |
| Phison              | 1         | 1      | 1.39%   |
| Patriot             | 1         | 1      | 1.39%   |
| JMicron Technology  | 1         | 1      | 1.39%   |
| Gigabyte Technology | 1         | 1      | 1.39%   |
| ExeGate             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| AMD                 | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000DM010-2EP102 1TB            | 4         | 5.48%   |
| SanDisk SD8SBAT256G1122 256GB SSD         | 3         | 4.11%   |
| Seagate ST1000DM010-2DM162 1TB            | 2         | 2.74%   |
| Seagate ST1000DM003-1SB10C 1TB            | 2         | 2.74%   |
| KIOXIA-EXCERIA SATA SSD 480GB             | 2         | 2.74%   |
| Foxline FLSSD240X5SE 240GB                | 2         | 2.74%   |
| Crucial CT240BX500SSD1 240GB              | 2         | 2.74%   |
| A-DATA SU800 256GB SSD                    | 2         | 2.74%   |
| A-DATA SU630 960GB SSD                    | 2         | 2.74%   |
| Unknown                                   | 2         | 2.74%   |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 1.37%   |
| WDC WD5000AAKX-75U6AA0 500GB              | 1         | 1.37%   |
| WDC WD3200AAKX-001CA0 320GB               | 1         | 1.37%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.37%   |
| WDC WD10EARS-00Y5B1 1TB                   | 1         | 1.37%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 1         | 1.37%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.37%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 1.37%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.37%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 1.37%   |
| Transcend TS480GMTS420S 480GB SSD         | 1         | 1.37%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 1.37%   |
| Toshiba KHK61VSE960G 960GB SSD            | 1         | 1.37%   |
| Toshiba HDWD110 1TB                       | 1         | 1.37%   |
| Toshiba DT01ACA200 2TB                    | 1         | 1.37%   |
| Smartbuy SSD 240GB                        | 1         | 1.37%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.37%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 1         | 1.37%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.37%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.37%   |
| Seagate ST3400620AS 400GB                 | 1         | 1.37%   |
| Seagate ST3250823AS 250GB                 | 1         | 1.37%   |
| Seagate ST31000528AS 1TB                  | 1         | 1.37%   |
| Seagate ST2000DM008-2UB102 2TB            | 1         | 1.37%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.37%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1.37%   |
| Samsung SSD 870 EVO 250GB                 | 1         | 1.37%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.37%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 1.37%   |
| Samsung MZVLQ256HAJD-000H1 256GB          | 1         | 1.37%   |
| Samsung MZVLB256HBHQ-000L7 256GB          | 1         | 1.37%   |
| Phison 311CD0512GB                        | 1         | 1.37%   |
| Patriot P210 128GB SSD                    | 1         | 1.37%   |
| Micron 2200V_MTFDHBA512TCK 512GB          | 1         | 1.37%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD       | 1         | 1.37%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 1.37%   |
| Kingston OM8PCP3512F-A02 512GB            | 1         | 1.37%   |
| JMicron Generic 2TB                       | 1         | 1.37%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 1         | 1.37%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 1         | 1.37%   |
| Foxline FLSSD120SM5 120GB                 | 1         | 1.37%   |
| ExeGate EX276690RUS(960G 960GB SSD        | 1         | 1.37%   |
| Crucial CT250MX500SSD4 250GB              | 1         | 1.37%   |
| China SSD 256GB                           | 1         | 1.37%   |
| Apacer AS350 256GB SSD                    | 1         | 1.37%   |
| AMD R5MP120G8 120GB                       | 1         | 1.37%   |
| A-DATA SX6000PNP 256GB                    | 1         | 1.37%   |
| A-DATA SX6000LNP 256GB                    | 1         | 1.37%   |
| A-DATA SU650 240GB SSD                    | 1         | 1.37%   |
| A-DATA FALCON 512GB                       | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 15        | 25     | 65.22%  |
| WDC                | 5         | 7      | 21.74%  |
| Toshiba            | 2         | 2      | 8.7%    |
| JMicron Technology | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 5         | 5      | 17.86%  |
| SanDisk             | 3         | 4      | 10.71%  |
| Samsung Electronics | 3         | 3      | 10.71%  |
| Foxline             | 3         | 3      | 10.71%  |
| Crucial             | 3         | 5      | 10.71%  |
| KIOXIA-EXCERIA      | 2         | 2      | 7.14%   |
| Transcend           | 1         | 1      | 3.57%   |
| Toshiba             | 1         | 1      | 3.57%   |
| Smartbuy            | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| ExeGate             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| Apacer              | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 31     | 40%     |
| HDD  | 21        | 35     | 30%     |
| NVMe | 19        | 21     | 27.14%  |
| MMC  | 2         | 3      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 65     | 65.63%  |
| NVMe | 19        | 21     | 29.69%  |
| MMC  | 2         | 3      | 3.13%   |
| SAS  | 1         | 1      | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 33     | 56.86%  |
| 0.51-1.0   | 19        | 30     | 37.25%  |
| 1.01-2.0   | 3         | 3      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 35.59%  |
| 251-500    | 14        | 23.73%  |
| 501-1000   | 12        | 20.34%  |
| 1001-2000  | 4         | 6.78%   |
| 51-100     | 3         | 5.08%   |
| 2001-3000  | 2         | 3.39%   |
| 21-50      | 1         | 1.69%   |
| 1-20       | 1         | 1.69%   |
| Unknown    | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 57.81%  |
| 501-1000  | 7         | 10.94%  |
| 51-100    | 5         | 7.81%   |
| 251-500   | 4         | 6.25%   |
| 21-50     | 4         | 6.25%   |
| 101-250   | 4         | 6.25%   |
| 1001-2000 | 2         | 3.13%   |
| Unknown   | 1         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 16.67%  |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 16.67%  |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 16.67%  |
| Seagate ST3250823AS 250GB           | 1         | 1      | 16.67%  |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 2      | 16.67%  |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 50%     |
| WDC               | 2         | 2      | 33.33%  |
| A-DATA Technology | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| WDC     | 2         | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 80%     |
| SSD  | 1         | 1      | 20%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 53        | 79     | 86.89%  |
| Malfunc  | 5         | 7      | 8.2%    |
| Detected | 3         | 4      | 4.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 48        | 65.75%  |
| SanDisk                      | 5         | 6.85%   |
| AMD                          | 5         | 6.85%   |
| Realtek Semiconductor        | 3         | 4.11%   |
| Phison Electronics           | 3         | 4.11%   |
| SK hynix                     | 2         | 2.74%   |
| Samsung Electronics          | 2         | 2.74%   |
| Toshiba America Info Systems | 1         | 1.37%   |
| Silicon Motion               | 1         | 1.37%   |
| Nvidia                       | 1         | 1.37%   |
| Micron Technology            | 1         | 1.37%   |
| Kingston Technology Company  | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12        | 15.58%  |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 7.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 6.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 5.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 3.9%    |
| Realtek Realtek Non-Volatile memory controller                                          | 3         | 3.9%    |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 3.9%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 3         | 3.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 3.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 3.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3         | 3.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 2.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 2.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 1.3%    |
| SK hynix Gold P31 SSD                                                                   | 1         | 1.3%    |
| SK hynix BC511                                                                          | 1         | 1.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.3%    |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 1.3%    |
| SanDisk Non-Volatile memory controller                                                  | 1         | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 1.3%    |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.3%    |
| Nvidia MCP61 SATA Controller                                                            | 1         | 1.3%    |
| Nvidia MCP61 IDE                                                                        | 1         | 1.3%    |
| Micron Non-Volatile memory controller                                                   | 1         | 1.3%    |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1         | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.3%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 50        | 67.57%  |
| NVMe | 19        | 25.68%  |
| IDE  | 3         | 4.05%   |
| RAID | 2         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 84.48%  |
| AMD    | 9         | 15.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-10100 CPU @ 3.60GHz             | 8         | 13.79%  |
| Intel Core i5-9400 CPU @ 2.90GHz              | 6         | 10.34%  |
| Intel Core i5-8279U CPU @ 2.40GHz             | 3         | 5.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 5.17%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 3.45%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.45%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 3.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 3.45%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1         | 1.72%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 1.72%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 1.72%   |
| Intel Core i5-8500T CPU @ 2.10GHz             | 1         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i5-10600K CPU @ 4.10GHz            | 1         | 1.72%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 1         | 1.72%   |
| Intel Core i5-10400T CPU @ 2.00GHz            | 1         | 1.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.72%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 1.72%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.72%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 1         | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Celeron G5925 CPU @ 3.60GHz             | 1         | 1.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.72%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 1         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.72%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 1.72%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 1         | 1.72%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 1         | 1.72%   |
| AMD Athlon II X2 240 Processor                | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 22        | 37.93%  |
| Intel Core i3      | 15        | 25.86%  |
| Other              | 5         | 8.62%   |
| Intel Celeron      | 4         | 6.9%    |
| AMD Ryzen 5        | 3         | 5.17%   |
| AMD Ryzen 7 PRO    | 2         | 3.45%   |
| AMD Ryzen 3        | 2         | 3.45%   |
| Intel Xeon         | 1         | 1.72%   |
| Intel Pentium Gold | 1         | 1.72%   |
| Intel Pentium      | 1         | 1.72%   |
| AMD Ryzen 7        | 1         | 1.72%   |
| AMD Athlon II X2   | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 29        | 50%     |
| 6      | 14        | 24.14%  |
| 2      | 13        | 22.41%  |
| 8      | 2         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 65.52%  |
| 1      | 20        | 34.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 98.28%  |
| Unknown        | 1         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 13        | 22.03%  |
| 0x806ea    | 5         | 8.47%   |
| 0x906ed    | 4         | 6.78%   |
| 0x806c1    | 4         | 6.78%   |
| 0x306a9    | 4         | 6.78%   |
| 0x08600106 | 4         | 6.78%   |
| 0x906ea    | 3         | 5.08%   |
| 0x506e3    | 3         | 5.08%   |
| 0x206a7    | 2         | 3.39%   |
| 0xa0671    | 1         | 1.69%   |
| 0xa0654    | 1         | 1.69%   |
| 0x906eb    | 1         | 1.69%   |
| 0x906e9    | 1         | 1.69%   |
| 0x806ec    | 1         | 1.69%   |
| 0x706e5    | 1         | 1.69%   |
| 0x706a8    | 1         | 1.69%   |
| 0x506c9    | 1         | 1.69%   |
| 0x406e3    | 1         | 1.69%   |
| 0x306c3    | 1         | 1.69%   |
| 0x206c2    | 1         | 1.69%   |
| 0x08608103 | 1         | 1.69%   |
| 0x08600104 | 1         | 1.69%   |
| 0x08108109 | 1         | 1.69%   |
| 0x08108102 | 1         | 1.69%   |
| 0x010000c7 | 1         | 1.69%   |
| Unknown    | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 25.86%  |
| CometLake     | 14        | 24.14%  |
| Zen 2         | 5         | 8.62%   |
| TigerLake     | 4         | 6.9%    |
| Skylake       | 4         | 6.9%    |
| IvyBridge     | 4         | 6.9%    |
| Zen+          | 2         | 3.45%   |
| SandyBridge   | 2         | 3.45%   |
| Unknown       | 2         | 3.45%   |
| Westmere      | 1         | 1.72%   |
| K10           | 1         | 1.72%   |
| IceLake       | 1         | 1.72%   |
| Haswell       | 1         | 1.72%   |
| Goldmont plus | 1         | 1.72%   |
| Goldmont      | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 73.02%  |
| AMD    | 10        | 15.87%  |
| Nvidia | 7         | 11.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 11        | 17.19%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 8         | 12.5%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 5         | 7.81%   |
| AMD Renoir                                                                | 5         | 7.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 3         | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 4.69%   |
| Intel HD Graphics 530                                                     | 2         | 3.13%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                  | 2         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.56%   |
| Nvidia NV43 [GeForce 6600 GT]                                             | 1         | 1.56%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.56%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 1.56%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                         | 1         | 1.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 1.56%   |
| Nvidia G94GL [Quadro FX 1800]                                             | 1         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.56%   |
| Intel Tiger Lake UHD Graphics                                             | 1         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.56%   |
| Intel HD Graphics 610                                                     | 1         | 1.56%   |
| Intel HD Graphics 500                                                     | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 1.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 1.56%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                     | 1         | 1.56%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                 | 1         | 1.56%   |
| AMD Lucienne                                                              | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 72.41%  |
| 1 x AMD        | 7         | 12.07%  |
| 1 x Nvidia     | 3         | 5.17%   |
| Intel + Nvidia | 3         | 5.17%   |
| 2 x AMD        | 1         | 1.72%   |
| Intel + AMD    | 1         | 1.72%   |
| AMD + Nvidia   | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 49        | 83.05%  |
| Unknown     | 8         | 13.56%  |
| Proprietary | 2         | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 71.67%  |
| 1.01-2.0   | 5         | 8.33%   |
| 0.51-1.0   | 5         | 8.33%   |
| 0.01-0.5   | 5         | 8.33%   |
| 3.01-4.0   | 2         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Philips              | 10        | 17.54%  |
| Samsung Electronics  | 8         | 14.04%  |
| BOE                  | 6         | 10.53%  |
| LG Display           | 4         | 7.02%   |
| Chimei Innolux       | 4         | 7.02%   |
| ViewSonic            | 3         | 5.26%   |
| AU Optronics         | 3         | 5.26%   |
| AOC                  | 3         | 5.26%   |
| SGT                  | 2         | 3.51%   |
| PANDA                | 2         | 3.51%   |
| BenQ                 | 2         | 3.51%   |
| Ancor Communications | 2         | 3.51%   |
| Acer                 | 2         | 3.51%   |
| XSP                  | 1         | 1.75%   |
| Iiyama               | 1         | 1.75%   |
| DOY                  | 1         | 1.75%   |
| Dell                 | 1         | 1.75%   |
| CHR                  | 1         | 1.75%   |
| ASUSTek Computer     | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6         | 10.17%  |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 3         | 5.08%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                 | 3         | 5.08%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 2         | 3.39%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2         | 3.39%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2         | 3.39%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 3.39%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch        | 2         | 3.39%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                     | 1         | 1.69%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1         | 1.69%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1         | 1.69%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 1         | 1.69%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1         | 1.69%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1         | 1.69%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 1         | 1.69%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 1         | 1.69%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.69%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1.69%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.69%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                  | 1         | 1.69%   |
| DOY LCD Monitor DOY2760 1920x1080 598x336mm 27.0-inch                 | 1         | 1.69%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1         | 1.69%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.69%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 1         | 1.69%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 1         | 1.69%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 1         | 1.69%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 1         | 1.69%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch        | 1         | 1.69%   |
| ASUSTek Computer VA24D AUS2403 1920x1080 527x296mm 23.8-inch          | 1         | 1.69%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 1         | 1.69%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 1         | 1.69%   |
| AOC 2250W AOC2250 1920x1080 480x270mm 21.7-inch                       | 1         | 1.69%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch      | 1         | 1.69%   |
| Ancor Communications VE208 ACI20A8 1600x900 443x249mm 20.0-inch       | 1         | 1.69%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 1         | 1.69%   |
| Acer H226HQL ACR0319 1920x1080 476x268mm 21.5-inch                    | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 82.69%  |
| 1600x900 (HD+)    | 3         | 5.77%   |
| 1366x768 (WXGA)   | 2         | 3.85%   |
| 3840x2160 (4K)    | 1         | 1.92%   |
| 1920x1200 (WUXGA) | 1         | 1.92%   |
| 1280x1024 (SXGA)  | 1         | 1.92%   |
| 1024x768 (XGA)    | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 18        | 31.58%  |
| 24     | 13        | 22.81%  |
| 23     | 11        | 19.3%   |
| 27     | 3         | 5.26%   |
| 21     | 3         | 5.26%   |
| 20     | 2         | 3.51%   |
| 17     | 2         | 3.51%   |
| 13     | 2         | 3.51%   |
| 32     | 1         | 1.75%   |
| 31     | 1         | 1.75%   |
| 19     | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 23        | 43.4%   |
| 301-350     | 20        | 37.74%  |
| 401-500     | 5         | 9.43%   |
| 351-400     | 3         | 5.66%   |
| 701-800     | 1         | 1.89%   |
| 601-700     | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 92%     |
| 16/10 | 2         | 4%      |
| 5/4   | 1         | 2%      |
| 4/3   | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 41.82%  |
| 101-110        | 18        | 32.73%  |
| 301-350        | 3         | 5.45%   |
| 151-200        | 3         | 5.45%   |
| 81-90          | 2         | 3.64%   |
| 351-500        | 2         | 3.64%   |
| 251-300        | 2         | 3.64%   |
| 121-130        | 2         | 3.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 26        | 52%     |
| 121-160 | 18        | 36%     |
| 101-120 | 6         | 12%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 72.13%  |
| 0     | 9         | 14.75%  |
| 2     | 8         | 13.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 53.33%  |
| Intel                 | 21        | 28%     |
| Qualcomm Atheros      | 4         | 5.33%   |
| Broadcom              | 2         | 2.67%   |
| TP-Link               | 1         | 1.33%   |
| Samsung Electronics   | 1         | 1.33%   |
| Realtek               | 1         | 1.33%   |
| Ralink Technology     | 1         | 1.33%   |
| Ralink                | 1         | 1.33%   |
| OKB SAPR              | 1         | 1.33%   |
| Nvidia                | 1         | 1.33%   |
| Edimax Technology     | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 35.56%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 4         | 4.44%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 3.33%   |
| Intel Wireless 7265                                               | 3         | 3.33%   |
| Intel Wireless 3165                                               | 3         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.22%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.22%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.11%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.11%   |
| Realtek 802.11ac NIC                                              | 1         | 1.11%   |
| Realtek 802.11n NIC                                               | 1         | 1.11%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.11%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.11%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.11%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.11%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.11%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU]   | 1         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 40%     |
| Intel                 | 12        | 34.29%  |
| Qualcomm Atheros      | 3         | 8.57%   |
| TP-Link               | 1         | 2.86%   |
| Realtek               | 1         | 2.86%   |
| Ralink Technology     | 1         | 2.86%   |
| Ralink                | 1         | 2.86%   |
| Edimax Technology     | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 5         | 14.29%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 3         | 8.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 8.57%   |
| Intel Wireless 7265                                             | 3         | 8.57%   |
| Intel Wireless 3165                                             | 3         | 8.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 2         | 5.71%   |
| Intel Wi-Fi 6 AX201                                             | 2         | 5.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 2         | 5.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1         | 2.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 1         | 2.86%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                      | 1         | 2.86%   |
| Realtek 802.11ac NIC                                            | 1         | 2.86%   |
| Realtek 802.11n NIC                                             | 1         | 2.86%   |
| Ralink MT7601U Wireless Adapter                                 | 1         | 2.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                       | 1         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 1         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 1         | 2.86%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 61.82%  |
| Intel                 | 16        | 29.09%  |
| Samsung Electronics   | 1         | 1.82%   |
| Qualcomm Atheros      | 1         | 1.82%   |
| OKB SAPR              | 1         | 1.82%   |
| Nvidia                | 1         | 1.82%   |
| Broadcom              | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 58.18%  |
| Intel Ethernet Controller I225-V                                  | 4         | 7.27%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 7.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 3.64%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 3.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.82%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.82%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.82%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.82%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.82%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 60.92%  |
| WiFi     | 34        | 39.08%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 75.41%  |
| WiFi     | 15        | 24.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 60.34%  |
| 2     | 22        | 37.93%  |
| 0     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 98.28%  |
| Yes  | 1         | 1.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 38.46%  |
| Realtek Semiconductor           | 8         | 30.77%  |
| Realtek                         | 2         | 7.69%   |
| IMC Networks                    | 2         | 7.69%   |
| Broadcom                        | 2         | 7.69%   |
| Ralink                          | 1         | 3.85%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 7         | 26.92%  |
| Intel Bluetooth wireless interface               | 5         | 19.23%  |
| Intel Bluetooth Device                           | 3         | 11.54%  |
| Realtek Bluetooth Radio                          | 2         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 3.85%   |
| Ralink RT3290 Bluetooth                          | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 3.85%   |
| IMC Networks Bluetooth Radio                     | 1         | 3.85%   |
| IMC Networks Bluetooth Device                    | 1         | 3.85%   |
| Broadcom HP Portable Valentine                   | 1         | 3.85%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 79.03%  |
| AMD    | 8         | 12.9%   |
| Nvidia | 4         | 6.45%   |
| Lenovo | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Audio device                                                         | 11        | 15.71%  |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 11.43%  |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 8.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 8.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 7.14%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 7.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 5.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 5.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 4.29%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.43%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 1.43%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.43%   |
| Lenovo ThinkCentre TIO27 for USB-audio                                     | 1         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.43%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Crucial             | 10        | 16.67%  |
| SK hynix            | 8         | 13.33%  |
| Samsung Electronics | 8         | 13.33%  |
| Kingston            | 7         | 11.67%  |
| Foxline             | 6         | 10%     |
| Unknown             | 3         | 5%      |
| AMD                 | 3         | 5%      |
| Unknown (ABCD)      | 2         | 3.33%   |
| Ramaxel Technology  | 2         | 3.33%   |
| Micron Technology   | 2         | 3.33%   |
| Elpida              | 2         | 3.33%   |
| Qumo                | 1         | 1.67%   |
| Neo Forza           | 1         | 1.67%   |
| Corsair             | 1         | 1.67%   |
| ChangXin Memory     | 1         | 1.67%   |
| Apacer              | 1         | 1.67%   |
| A-DATA Technology   | 1         | 1.67%   |
| Unknown             | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Foxline RAM FL2666D4U19-8G 8192MB DIMM DDR4 2667MT/s                | 3         | 4.84%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                           | 2         | 3.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 3.23%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 2         | 3.23%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                         | 2         | 3.23%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.61%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.61%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1         | 1.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 1.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s        | 1         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.61%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.61%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.61%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                 | 1         | 1.61%   |
| Samsung RAM M378A2G43MX3-CTD 16384MB DIMM DDR4 3466MT/s             | 1         | 1.61%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s          | 1         | 1.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s                    | 1         | 1.61%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s               | 1         | 1.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 1.61%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 1         | 1.61%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s                | 1         | 1.61%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s               | 1         | 1.61%   |
| Kingston RAM 99U5471-060.A00LF 8GB DIMM DDR3 1333MT/s               | 1         | 1.61%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s               | 1         | 1.61%   |
| Kingston RAM 99P5663-010.A00G 16GB SODIMM DDR4 2667MT/s             | 1         | 1.61%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.61%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s                | 1         | 1.61%   |
| Foxline RAM FL2400D4S17-8G 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.61%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.61%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 1         | 1.61%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 1         | 1.61%   |
| Crucial RAM CT8G4SFRA32A.C8FN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.61%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s              | 1         | 1.61%   |
| Crucial RAM CT8G4SFRA266.C8FE 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s                | 1         | 1.61%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s                | 1         | 1.61%   |
| Crucial RAM CT8G4DFRA266.C16FG 8GB DIMM DDR4 2667MT/s               | 1         | 1.61%   |
| Crucial RAM CT8G4DFD8213.M16FA 8192MB DIMM DDR4 2133MT/s            | 1         | 1.61%   |
| Crucial RAM CT4G4DFS824A.C8FE 4GB DIMM DDR4 2400MT/s                | 1         | 1.61%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s              | 1         | 1.61%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.61%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s                | 1         | 1.61%   |
| ChangXin Memory RAM QUM4S-8G2666P19 8GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Apacer RAM D22.22242S.001 8GB SODIMM DDR4 2667MT/s                  | 1         | 1.61%   |
| AMD RAM R744G2606U1S 4GB DIMM DDR4 2866MT/s                         | 1         | 1.61%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                          | 1         | 1.61%   |
| Unknown                                                             | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 44        | 81.48%  |
| DDR3   | 7         | 12.96%  |
| LPDDR4 | 2         | 3.7%    |
| DDR2   | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 26        | 47.27%  |
| SODIMM       | 24        | 43.64%  |
| Row Of Chips | 5         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 51.67%  |
| 4096  | 18        | 30%     |
| 16384 | 7         | 11.67%  |
| 2048  | 4         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 22        | 37.93%  |
| 3200  | 12        | 20.69%  |
| 2400  | 6         | 10.34%  |
| 2133  | 3         | 5.17%   |
| 1600  | 3         | 5.17%   |
| 1333  | 3         | 5.17%   |
| 3466  | 2         | 3.45%   |
| 3000  | 1         | 1.72%   |
| 2866  | 1         | 1.72%   |
| 2800  | 1         | 1.72%   |
| 2666  | 1         | 1.72%   |
| 1800  | 1         | 1.72%   |
| 1334  | 1         | 1.72%   |
| 800   | 1         | 1.72%   |

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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 7         | 20.59%  |
| Chicony Electronics                    | 6         | 17.65%  |
| SunplusIT                              | 4         | 11.76%  |
| Alcor Micro                            | 4         | 11.76%  |
| Acer                                   | 3         | 8.82%   |
| Sunplus Innovation Technology          | 2         | 5.88%   |
| Syntek                                 | 1         | 2.94%   |
| Realtek Semiconductor                  | 1         | 2.94%   |
| Microdia                               | 1         | 2.94%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| Creative Technology                    | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.94%   |
| Arkmicro Technologies                  | 1         | 2.94%   |
| Apple                                  | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SunplusIT USB Camera                                          | 3         | 8.82%   |
| Chicony USB camera                                            | 3         | 8.82%   |
| Alcor Micro USB 2.0 PC Camera                                 | 3         | 8.82%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 2         | 5.88%   |
| IMC Networks ov9734_azurewave_camera                          | 2         | 5.88%   |
| IMC Networks Integrated Camera                                | 2         | 5.88%   |
| Acer Integrated Camera                                        | 2         | 5.88%   |
| Syntek Integrated RGB Camera                                  | 1         | 2.94%   |
| SunplusIT MTD camera                                          | 1         | 2.94%   |
| Sunplus Integrated Camera                                     | 1         | 2.94%   |
| Sunplus Asus Webcam                                           | 1         | 2.94%   |
| Realtek 1080p Camera                                          | 1         | 2.94%   |
| Microdia USB 2.0 Camera                                       | 1         | 2.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 2.94%   |
| IMC Networks HD Camera                                        | 1         | 2.94%   |
| Creative VF0530 Live! Cam Chat IM                             | 1         | 2.94%   |
| Chicony HP Webcam-50                                          | 1         | 2.94%   |
| Chicony HP TrueVision HD Camera                               | 1         | 2.94%   |
| Chicony HD User Facing                                        | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 2.94%   |
| Arkmicro USB2.0 PC CAMERA                                     | 1         | 2.94%   |
| Apple iPhone 5/5C/5S/6/SE                                     | 1         | 2.94%   |
| Alcor Micro USB FHD Camera                                    | 1         | 2.94%   |
| Acer BisonCam, NB Pro                                         | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device | 4         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aladdin R.D. | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Aladdin R.D. JaCarta | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 68.33%  |
| 1     | 18        | 30%     |
| 2     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 9         | 45%     |
| Fingerprint reader    | 4         | 20%     |
| Net/wireless          | 3         | 15%     |
| Net/ethernet          | 1         | 5%      |
| Multimedia controller | 1         | 5%      |
| Chipcard              | 1         | 5%      |
| Bluetooth             | 1         | 5%      |

