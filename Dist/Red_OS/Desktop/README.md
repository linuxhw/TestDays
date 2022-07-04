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

Total: 42

| Vendor   | Model            | Probe                                                      | Date         |
|----------|------------------|------------------------------------------------------------|--------------|
| ASUSTek  | M2N68-AM Plus    | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek  | PRIME H510T2/CSM | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek  | H81M-K           | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP       | 0B4Ch D          | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| ASRock   | B365M Pro4-F     | [3a12e41029](https://linux-hardware.org/?probe=3a12e41029) | Jun 01, 2022 |
| MSI      | A520M PRO        | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI      | A520M PRO        | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock   | B365M Pro4-F     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI      | H510TI-S01       | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte | B365M H          | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek  | H81M-K           | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock   | B560 Pro4        | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte | B75M-D3V         | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte | B75M-D2V         | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte | H410M H V3       | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte | B75M-D2V         | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek  | H110-PLUS        | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius | AQH410T          | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius | AQB560M          | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte | B560M DS3H       | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek  | PRIME H510M-K    | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte | B75M-D3V         | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek  | PRIME H510T2/CSM | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte | B365M DS3H       | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius | AQB560M          | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius | AQB560M          | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte | B75M-D2V         | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte | B560M DS3H       | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock   | H470M-HDV        | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte | H110M-M2-CF      | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek  | H110-PLUS        | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte | B365M DS3H       | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek  | H110M-PLUS       | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek  | P8H61-I LX R2.0  | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte | B365M DS3H       | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek  | H81M-K           | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek  | H110M-K          | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek  | H110M-K          | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek  | H81M-K           | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte | B360M DS3H       | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte | B360M DS3H       | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek  | H81M-K           | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 17       | 48.57%  |
| Red OS 7.3.1 | 13       | 37.14%  |
| Red OS 7.2   | 5        | 14.29%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 31       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.29-1.el7.x86_64   | 11       | 30.56%  |
| 5.15.35-1.el7.3.x86_64 | 5        | 13.89%  |
| 5.15.10-1.el7.x86_64   | 5        | 13.89%  |
| 5.15.10-3.el7.x86_64   | 3        | 8.33%   |
| 5.15.10-2.el7.x86_64   | 3        | 8.33%   |
| 4.19.79-1.el7.x86_64   | 3        | 8.33%   |
| 5.14.9-1.el7.x86_64    | 1        | 2.78%   |
| 5.10.24-3.el7.x86_64   | 1        | 2.78%   |
| 5.10.24-2.el7.x86_64   | 1        | 2.78%   |
| 5.10.1-1.el7.x86_64    | 1        | 2.78%   |
| 4.19.56-2.el7.x86_64   | 1        | 2.78%   |
| 4.19.204-1.el7.x86_64  | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.10  | 11       | 30.56%  |
| 5.10.29  | 11       | 30.56%  |
| 5.15.35  | 5        | 13.89%  |
| 4.19.79  | 3        | 8.33%   |
| 5.10.24  | 2        | 5.56%   |
| 5.14.9   | 1        | 2.78%   |
| 5.10.1   | 1        | 2.78%   |
| 4.19.56  | 1        | 2.78%   |
| 4.19.204 | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 44.44%  |
| 5.10    | 14       | 38.89%  |
| 4.19    | 5        | 13.89%  |
| 5.14    | 1        | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 31       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 25       | 73.53%  |
| Cinnamon   | 7        | 20.59%  |
| X-Cinnamon | 1        | 2.94%   |
| Unknown    | 1        | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 27       | 84.38%  |
| Wayland | 4        | 12.5%   |
| Unknown | 1        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 30       | 93.75%  |
| SDDM    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 90.63%  |
| ru_RU   | 3        | 9.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 22       | 68.75%  |
| BIOS | 10       | 31.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 28       | 90.32%  |
| Btrfs   | 2        | 6.45%   |
| Unknown | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 22       | 68.75%  |
| MBR     | 9        | 28.13%  |
| Unknown | 1        | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 87.5%   |
| Yes       | 4        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 84.38%  |
| Yes       | 5        | 15.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 11       | 35.48%  |
| ASUSTek Computer    | 9        | 29.03%  |
| Aquarius            | 4        | 12.9%   |
| MSI                 | 3        | 9.68%   |
| ASRock              | 3        | 9.68%   |
| Hewlett-Packard     | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte B365M DS3H   | 3        | 9.68%   |
| MSI MS-7D14           | 2        | 6.45%   |
| Gigabyte B560M DS3H   | 2        | 6.45%   |
| MSI MS-7D35           | 1        | 3.23%   |
| HP Z400 Workstation   | 1        | 3.23%   |
| Gigabyte H410M H V3   | 1        | 3.23%   |
| Gigabyte H110M-M.2    | 1        | 3.23%   |
| Gigabyte B75M-D3V     | 1        | 3.23%   |
| Gigabyte B75M-D2V     | 1        | 3.23%   |
| Gigabyte B365M H      | 1        | 3.23%   |
| Gigabyte B360M-DS3H   | 1        | 3.23%   |
| ASUS PRIME H510T2/CSM | 1        | 3.23%   |
| ASUS PRIME H510M-K    | 1        | 3.23%   |
| ASUS PC               | 1        | 3.23%   |
| ASUS P8H61-I LX R2.0  | 1        | 3.23%   |
| ASUS M2N68-AM Plus    | 1        | 3.23%   |
| ASUS H110M-PLUS       | 1        | 3.23%   |
| ASUS H110M-K          | 1        | 3.23%   |
| ASUS H110-PLUS        | 1        | 3.23%   |
| ASUS All Series       | 1        | 3.23%   |
| ASRock H470M-HDV      | 1        | 3.23%   |
| ASRock B560 Pro4      | 1        | 3.23%   |
| ASRock B365M Pro4-F   | 1        | 3.23%   |
| Aquarius Pro T584     | 1        | 3.23%   |
| Aquarius P30 K44 R53  | 1        | 3.23%   |
| Aquarius AQH410T      | 1        | 3.23%   |
| Aquarius AQB560M      | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte B365M      | 4        | 12.9%   |
| MSI MS-7D14         | 2        | 6.45%   |
| Gigabyte B560M      | 2        | 6.45%   |
| ASUS PRIME          | 2        | 6.45%   |
| MSI MS-7D35         | 1        | 3.23%   |
| HP Z400             | 1        | 3.23%   |
| Gigabyte H410M      | 1        | 3.23%   |
| Gigabyte H110M-M.2  | 1        | 3.23%   |
| Gigabyte B75M-D3V   | 1        | 3.23%   |
| Gigabyte B75M-D2V   | 1        | 3.23%   |
| Gigabyte B360M-DS3H | 1        | 3.23%   |
| ASUS PC             | 1        | 3.23%   |
| ASUS P8H61-I        | 1        | 3.23%   |
| ASUS M2N68-AM       | 1        | 3.23%   |
| ASUS H110M-PLUS     | 1        | 3.23%   |
| ASUS H110M-K        | 1        | 3.23%   |
| ASUS H110-PLUS      | 1        | 3.23%   |
| ASUS All            | 1        | 3.23%   |
| ASRock H470M-HDV    | 1        | 3.23%   |
| ASRock B560         | 1        | 3.23%   |
| ASRock B365M        | 1        | 3.23%   |
| Aquarius Pro        | 1        | 3.23%   |
| Aquarius P30        | 1        | 3.23%   |
| Aquarius AQH410T    | 1        | 3.23%   |
| Aquarius AQB560M    | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 35.48%  |
| 2019 | 5        | 16.13%  |
| 2016 | 3        | 9.68%   |
| 2012 | 3        | 9.68%   |
| 2022 | 2        | 6.45%   |
| 2020 | 2        | 6.45%   |
| 2018 | 1        | 3.23%   |
| 2017 | 1        | 3.23%   |
| 2013 | 1        | 3.23%   |
| 2010 | 1        | 3.23%   |
| 2009 | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 12       | 38.71%  |
| 4.01-8.0   | 7        | 22.58%  |
| 3.01-4.0   | 5        | 16.13%  |
| 8.01-16.0  | 5        | 16.13%  |
| 24.01-32.0 | 1        | 3.23%   |
| Unknown    | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 11       | 30.56%  |
| 1.01-2.0  | 9        | 25%     |
| 0.51-1.0  | 6        | 16.67%  |
| 3.01-4.0  | 5        | 13.89%  |
| 2.01-3.0  | 3        | 8.33%   |
| 8.01-16.0 | 1        | 2.78%   |
| Unknown   | 1        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 65.63%  |
| 2      | 11       | 34.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 70.97%  |
| Yes       | 9        | 29.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 72.73%  |
| Yes       | 9        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 80.65%  |
| Yes       | 6        | 19.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 31       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Murom         | 13       | 41.94%  |
| Moscow        | 4        | 12.9%   |
| Salekhard     | 3        | 9.68%   |
| Yekaterinburg | 1        | 3.23%   |
| Surgut        | 1        | 3.23%   |
| Stavropol     | 1        | 3.23%   |
| Penza         | 1        | 3.23%   |
| Kursk         | 1        | 3.23%   |
| Krasnodar     | 1        | 3.23%   |
| Kovrov        | 1        | 3.23%   |
| Kirov         | 1        | 3.23%   |
| Kaluga        | 1        | 3.23%   |
| Bryansk       | 1        | 3.23%   |
| Arzamas       | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 23     | 31.71%  |
| A-DATA Technology   | 4        | 4      | 9.76%   |
| WDC                 | 3        | 3      | 7.32%   |
| Toshiba             | 3        | 3      | 7.32%   |
| Foxline             | 3        | 3      | 7.32%   |
| SanDisk             | 2        | 3      | 4.88%   |
| Samsung Electronics | 2        | 2      | 4.88%   |
| KIOXIA-EXCERIA      | 2        | 2      | 4.88%   |
| Kingston            | 2        | 2      | 4.88%   |
| Crucial             | 2        | 4      | 4.88%   |
| Smartbuy            | 1        | 1      | 2.44%   |
| Patriot             | 1        | 1      | 2.44%   |
| ExeGate             | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |
| AMD                 | 1        | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 4        | 9.52%   |
| Seagate ST1000DM010-2DM162 1TB     | 2        | 4.76%   |
| Seagate ST1000DM003-1SB10C 1TB     | 2        | 4.76%   |
| SanDisk SD8SBAT256G1122 256GB SSD  | 2        | 4.76%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 2        | 4.76%   |
| Foxline FLSSD240X5SE 240GB         | 2        | 4.76%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 4.76%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 2.38%   |
| WDC WD3200AAKX-001CA0 320GB        | 1        | 2.38%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 2.38%   |
| Toshiba KHK61VSE960G 960GB SSD     | 1        | 2.38%   |
| Toshiba HDWD110 1TB                | 1        | 2.38%   |
| Toshiba DT01ACA200 2TB             | 1        | 2.38%   |
| Smartbuy SSD 240GB                 | 1        | 2.38%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 2.38%   |
| Seagate ST3400620AS 400GB          | 1        | 2.38%   |
| Seagate ST3250823AS 250GB          | 1        | 2.38%   |
| Seagate ST31000528AS 1TB           | 1        | 2.38%   |
| Seagate ST2000DM008-2UB102 2TB     | 1        | 2.38%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 2.38%   |
| Samsung SSD 870 EVO 250GB          | 1        | 2.38%   |
| Samsung SSD 860 EVO 250GB          | 1        | 2.38%   |
| Patriot P210 128GB SSD             | 1        | 2.38%   |
| Kingston SA400S37120G 120GB SSD    | 1        | 2.38%   |
| Kingston OM8PCP3512F-A02 512GB     | 1        | 2.38%   |
| Foxline FLSSD120SM5 120GB          | 1        | 2.38%   |
| ExeGate EX276690RUS(960G 960GB SSD | 1        | 2.38%   |
| China SSD 256GB                    | 1        | 2.38%   |
| AMD R5MP120G8 120GB                | 1        | 2.38%   |
| A-DATA SX6000PNP 256GB             | 1        | 2.38%   |
| A-DATA SU800 256GB SSD             | 1        | 2.38%   |
| A-DATA SU630 960GB SSD             | 1        | 2.38%   |
| A-DATA FALCON 512GB                | 1        | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 13       | 23     | 72.22%  |
| WDC     | 3        | 3      | 16.67%  |
| Toshiba | 2        | 2      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Foxline             | 3        | 3      | 15.79%  |
| SanDisk             | 2        | 3      | 10.53%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| KIOXIA-EXCERIA      | 2        | 2      | 10.53%  |
| Crucial             | 2        | 4      | 10.53%  |
| A-DATA Technology   | 2        | 2      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| Smartbuy            | 1        | 1      | 5.26%   |
| Patriot             | 1        | 1      | 5.26%   |
| Kingston            | 1        | 1      | 5.26%   |
| ExeGate             | 1        | 1      | 5.26%   |
| China               | 1        | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 19       | 22     | 47.5%   |
| HDD  | 17       | 28     | 42.5%   |
| NVMe | 4        | 4      | 10%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 50     | 87.88%  |
| NVMe | 4        | 4      | 12.12%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 24     | 54.05%  |
| 0.51-1.0   | 15       | 24     | 40.54%  |
| 1.01-2.0   | 2        | 2      | 5.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 9        | 29.03%  |
| 501-1000   | 9        | 29.03%  |
| 251-500    | 6        | 19.35%  |
| 2001-3000  | 2        | 6.45%   |
| 1001-2000  | 2        | 6.45%   |
| 51-100     | 2        | 6.45%   |
| Unknown    | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 18       | 50%     |
| 501-1000  | 6        | 16.67%  |
| 251-500   | 3        | 8.33%   |
| 51-100    | 3        | 8.33%   |
| 101-250   | 2        | 5.56%   |
| 1001-2000 | 2        | 5.56%   |
| 21-50     | 1        | 2.78%   |
| Unknown   | 1        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB    | 1        | 1      | 25%     |
| WDC WD10EARS-00Y5B1 1TB        | 1        | 1      | 25%     |
| Seagate ST3250823AS 250GB      | 1        | 1      | 25%     |
| Seagate ST1000DM010-2EP102 1TB | 1        | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 2        | 3      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 2        | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 100%    |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 29       | 49     | 90.63%  |
| Malfunc | 3        | 5      | 9.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 28       | 80%     |
| Realtek Semiconductor       | 2        | 5.71%   |
| AMD                         | 2        | 5.71%   |
| Silicon Motion              | 1        | 2.86%   |
| Nvidia                      | 1        | 2.86%   |
| Kingston Technology Company | 1        | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 28.95%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 13.16%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 10.53%  |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 5.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 5.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 2.63%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.63%   |
| Nvidia MCP61 IDE                                                                        | 1        | 2.63%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 2.63%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 77.14%  |
| NVMe | 4        | 11.43%  |
| IDE  | 3        | 8.57%   |
| RAID | 1        | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 90.32%  |
| AMD    | 3        | 9.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i3-10100 CPU @ 3.60GHz          | 7        | 22.58%  |
| Intel Core i5-9400 CPU @ 2.90GHz           | 6        | 19.35%  |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3        | 9.68%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2        | 6.45%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 2        | 6.45%   |
| Intel Xeon CPU W3670 @ 3.20GHz             | 1        | 3.23%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz     | 1        | 3.23%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 3.23%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 1        | 3.23%   |
| Intel Core i5-10500 CPU @ 3.10GHz          | 1        | 3.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1        | 3.23%   |
| Intel Core i3-10105 CPU @ 3.70GHz          | 1        | 3.23%   |
| Intel Celeron G5925 CPU @ 3.60GHz          | 1        | 3.23%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 1        | 3.23%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz     | 1        | 3.23%   |
| AMD Athlon II X2 240 Processor             | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 11       | 35.48%  |
| Intel Core i3      | 11       | 35.48%  |
| Intel Celeron      | 2        | 6.45%   |
| AMD Ryzen 7 PRO    | 2        | 6.45%   |
| Other              | 1        | 3.23%   |
| Intel Xeon         | 1        | 3.23%   |
| Intel Pentium Gold | 1        | 3.23%   |
| Intel Pentium      | 1        | 3.23%   |
| AMD Athlon II X2   | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 35.48%  |
| 6      | 10       | 32.26%  |
| 2      | 8        | 25.81%  |
| 8      | 2        | 6.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 58.06%  |
| 1      | 13       | 41.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 30       | 96.77%  |
| Unknown        | 1        | 3.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 11       | 34.38%  |
| 0x906ed    | 4        | 12.5%   |
| 0x506e3    | 3        | 9.38%   |
| 0x306a9    | 3        | 9.38%   |
| 0x906ea    | 2        | 6.25%   |
| 0x08600106 | 2        | 6.25%   |
| 0xa0671    | 1        | 3.13%   |
| 0xa0654    | 1        | 3.13%   |
| 0x906e9    | 1        | 3.13%   |
| 0x306c3    | 1        | 3.13%   |
| 0x206c2    | 1        | 3.13%   |
| 0x010000c7 | 1        | 3.13%   |
| Unknown    | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| CometLake | 12       | 38.71%  |
| KabyLake  | 7        | 22.58%  |
| Skylake   | 3        | 9.68%   |
| IvyBridge | 3        | 9.68%   |
| Zen 2     | 2        | 6.45%   |
| Westmere  | 1        | 3.23%   |
| K10       | 1        | 3.23%   |
| Haswell   | 1        | 3.23%   |
| Unknown   | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 80.65%  |
| Nvidia | 3        | 9.68%   |
| AMD    | 3        | 9.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 9        | 28.13%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 6        | 18.75%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 3        | 9.38%   |
| Intel HD Graphics 530                                                     | 2        | 6.25%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                  | 2        | 6.25%   |
| AMD Renoir                                                                | 2        | 6.25%   |
| Nvidia NV43 [GeForce 6600 GT]                                             | 1        | 3.13%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                         | 1        | 3.13%   |
| Nvidia G94GL [Quadro FX 1800]                                             | 1        | 3.13%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 3.13%   |
| Intel HD Graphics 610                                                     | 1        | 3.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 3.13%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                     | 1        | 3.13%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                 | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 25       | 80.65%  |
| 1 x Nvidia | 3        | 9.68%   |
| 1 x AMD    | 2        | 6.45%   |
| 2 x AMD    | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 23       | 74.19%  |
| Unknown     | 7        | 22.58%  |
| Proprietary | 1        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 83.87%  |
| 1.01-2.0   | 2        | 6.45%   |
| 0.01-0.5   | 2        | 6.45%   |
| 0.51-1.0   | 1        | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 9        | 30%     |
| Samsung Electronics | 6        | 20%     |
| ViewSonic           | 3        | 10%     |
| AOC                 | 3        | 10%     |
| SGT                 | 2        | 6.67%   |
| BenQ                | 2        | 6.67%   |
| Acer                | 2        | 6.67%   |
| DOY                 | 1        | 3.33%   |
| Dell                | 1        | 3.33%   |
| CHR                 | 1        | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 18.75%  |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 2        | 6.25%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 6.25%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 6.25%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 6.25%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 3.13%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 3.13%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 1        | 3.13%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 3.13%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 3.13%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 3.13%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 1        | 3.13%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 1        | 3.13%   |
| DOY LCD Monitor DOY2760 1920x1080 598x336mm 27.0-inch                 | 1        | 3.13%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1        | 3.13%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 1        | 3.13%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 1        | 3.13%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 1        | 3.13%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 1        | 3.13%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 1        | 3.13%   |
| AOC 2250W AOC2250 1920x1080 480x270mm 21.7-inch                       | 1        | 3.13%   |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 1        | 3.13%   |
| Acer H226HQL ACR0319 1920x1080 476x268mm 21.5-inch                    | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 21       | 80.77%  |
| 3840x2160 (4K)    | 1        | 3.85%   |
| 1920x1200 (WUXGA) | 1        | 3.85%   |
| 1600x900 (HD+)    | 1        | 3.85%   |
| 1280x1024 (SXGA)  | 1        | 3.85%   |
| 1024x768 (XGA)    | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 10       | 33.33%  |
| 23     | 9        | 30%     |
| 27     | 3        | 10%     |
| 21     | 3        | 10%     |
| 32     | 1        | 3.33%   |
| 31     | 1        | 3.33%   |
| 20     | 1        | 3.33%   |
| 19     | 1        | 3.33%   |
| 15     | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 69.23%  |
| 401-500     | 4        | 15.38%  |
| 701-800     | 1        | 3.85%   |
| 601-700     | 1        | 3.85%   |
| 351-400     | 1        | 3.85%   |
| 301-350     | 1        | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 22       | 84.62%  |
| 16/10 | 2        | 7.69%   |
| 5/4   | 1        | 3.85%   |
| 4/3   | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 64.29%  |
| 301-350        | 3        | 10.71%  |
| 351-500        | 2        | 7.14%   |
| 251-300        | 2        | 7.14%   |
| 151-200        | 2        | 7.14%   |
| 101-110        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 87.5%   |
| 101-120 | 3        | 12.5%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 64.71%  |
| 2     | 6        | 17.65%  |
| 0     | 6        | 17.65%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 24       | 64.86%  |
| Intel                 | 8        | 21.62%  |
| Realtek               | 1        | 2.7%    |
| Ralink Technology     | 1        | 2.7%    |
| Nvidia                | 1        | 2.7%    |
| Edimax Technology     | 1        | 2.7%    |
| Broadcom              | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 55%     |
| Intel Ethernet Controller I225-V                                  | 3        | 7.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 5%      |
| Intel Ethernet Connection (2) I219-V                              | 2        | 5%      |
| Intel Ethernet Connection (14) I219-V                             | 2        | 5%      |
| Realtek 802.11ac NIC                                              | 1        | 2.5%    |
| Realtek 802.11n NIC                                               | 1        | 2.5%    |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.5%    |
| Nvidia MCP61 Ethernet                                             | 1        | 2.5%    |
| Intel Wireless 3165                                               | 1        | 2.5%    |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU]   | 1        | 2.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 55.56%  |
| Realtek               | 1        | 11.11%  |
| Ralink Technology     | 1        | 11.11%  |
| Intel                 | 1        | 11.11%  |
| Edimax Technology     | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2        | 22.22%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2        | 22.22%  |
| Realtek 802.11ac NIC                                            | 1        | 11.11%  |
| Realtek 802.11n NIC                                             | 1        | 11.11%  |
| Ralink MT7601U Wireless Adapter                                 | 1        | 11.11%  |
| Intel Wireless 3165                                             | 1        | 11.11%  |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 70.97%  |
| Intel                 | 7        | 22.58%  |
| Nvidia                | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 70.97%  |
| Intel Ethernet Controller I225-V                                  | 3        | 9.68%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 6.45%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 6.45%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 77.5%   |
| WiFi     | 9        | 22.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 93.94%  |
| WiFi     | 2        | 6.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 90.32%  |
| 2     | 3        | 9.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 66.67%  |
| Intel                 | 1        | 16.67%  |
| Broadcom              | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                          | 4        | 66.67%  |
| Intel Bluetooth wireless interface               | 1        | 16.67%  |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 87.5%   |
| Nvidia | 2        | 6.25%   |
| AMD    | 2        | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 10       | 28.57%  |
| Intel 200 Series PCH HD Audio                                              | 5        | 14.29%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 11.43%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 5.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 5.71%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.86%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2.86%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.86%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 7        | 21.88%  |
| Kingston            | 6        | 18.75%  |
| Unknown             | 3        | 9.38%   |
| Foxline             | 3        | 9.38%   |
| AMD                 | 3        | 9.38%   |
| SK hynix            | 2        | 6.25%   |
| Samsung Electronics | 1        | 3.13%   |
| Qumo                | 1        | 3.13%   |
| Neo Forza           | 1        | 3.13%   |
| Corsair             | 1        | 3.13%   |
| ChangXin Memory     | 1        | 3.13%   |
| Apacer              | 1        | 3.13%   |
| A-DATA Technology   | 1        | 3.13%   |
| Unknown             | 1        | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4U19-8G 8192MB DIMM DDR4 2667MT/s         | 3        | 9.09%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 6.06%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 6.06%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 2        | 6.06%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 3.03%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 3.03%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 3.03%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 1        | 3.03%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s             | 1        | 3.03%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 1        | 3.03%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 1        | 3.03%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 3.03%   |
| Kingston RAM 99U5471-060.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 3.03%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 3.03%   |
| Kingston RAM 99P5663-010.A00G 16GB SODIMM DDR4 2667MT/s      | 1        | 3.03%   |
| Crucial RAM CT8G4SFRA266.C8FE 8192MB SODIMM DDR4 2667MT/s    | 1        | 3.03%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s         | 1        | 3.03%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s         | 1        | 3.03%   |
| Crucial RAM CT8G4DFRA266.C16FG 8GB DIMM DDR4 2667MT/s        | 1        | 3.03%   |
| Crucial RAM CT8G4DFD8213.M16FA 8192MB DIMM DDR4 2133MT/s     | 1        | 3.03%   |
| Crucial RAM CT4G4DFS824A.C8FE 4GB DIMM DDR4 2400MT/s         | 1        | 3.03%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s       | 1        | 3.03%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s         | 1        | 3.03%   |
| ChangXin Memory RAM QUM4S-8G2666P19 8GB SODIMM DDR4 2667MT/s | 1        | 3.03%   |
| Apacer RAM D22.22242S.001 8GB SODIMM DDR4 2667MT/s           | 1        | 3.03%   |
| AMD RAM R744G2606U1S 4GB DIMM DDR4 2866MT/s                  | 1        | 3.03%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1        | 3.03%   |
| Unknown                                                      | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 23       | 82.14%  |
| DDR3 | 4        | 14.29%  |
| DDR2 | 1        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 24       | 85.71%  |
| SODIMM | 4        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 59.38%  |
| 4096  | 8        | 25%     |
| 16384 | 3        | 9.38%   |
| 2048  | 2        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 12       | 37.5%   |
| 3200  | 4        | 12.5%   |
| 2133  | 3        | 9.38%   |
| 1333  | 3        | 9.38%   |
| 2400  | 2        | 6.25%   |
| 3466  | 1        | 3.13%   |
| 3000  | 1        | 3.13%   |
| 2866  | 1        | 3.13%   |
| 2800  | 1        | 3.13%   |
| 2666  | 1        | 3.13%   |
| 1800  | 1        | 3.13%   |
| 1600  | 1        | 3.13%   |
| 800   | 1        | 3.13%   |

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
| SunplusIT             | 3        | 30%     |
| Alcor Micro           | 3        | 30%     |
| Realtek Semiconductor | 1        | 10%     |
| Creative Technology   | 1        | 10%     |
| Arkmicro Technologies | 1        | 10%     |
| Apple                 | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SunplusIT USB Camera              | 3        | 30%     |
| Alcor Micro USB 2.0 PC Camera     | 3        | 30%     |
| Realtek 1080p Camera              | 1        | 10%     |
| Creative VF0530 Live! Cam Chat IM | 1        | 10%     |
| Arkmicro USB2.0 PC CAMERA         | 1        | 10%     |
| Apple iPhone 5/5C/5S/6/SE         | 1        | 10%     |

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
| 0     | 22       | 68.75%  |
| 1     | 10       | 31.25%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 7        | 70%     |
| Net/wireless  | 2        | 20%     |
| Chipcard      | 1        | 10%     |

