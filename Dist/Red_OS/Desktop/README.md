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

Total: 50

| Vendor        | Model            | Probe                                                      | Date         |
|---------------|------------------|------------------------------------------------------------|--------------|
| ASRock        | H110M-DVS R2.0   | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H       | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00       | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T          | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T          | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3          | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus    | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K           | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D          | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F     | [3a12e41029](https://linux-hardware.org/?probe=3a12e41029) | Jun 01, 2022 |
| MSI           | A520M PRO        | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO        | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01       | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H          | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K           | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4        | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V         | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V         | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3       | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V         | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS        | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T          | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M          | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H       | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K    | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V         | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H       | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M          | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M          | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V         | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H       | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV        | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF      | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS        | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H       | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS       | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0  | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H       | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K           | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K          | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K          | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K           | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H       | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H       | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K           | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 21       | 48.84%  |
| Red OS 7.3.1 | 17       | 39.53%  |
| Red OS 7.2   | 5        | 11.63%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 39       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.29-1.el7.x86_64   | 12       | 27.27%  |
| 5.15.10-1.el7.x86_64   | 8        | 18.18%  |
| 5.15.35-1.el7.3.x86_64 | 7        | 15.91%  |
| 5.15.10-3.el7.x86_64   | 3        | 6.82%   |
| 5.15.10-2.el7.x86_64   | 3        | 6.82%   |
| 4.19.79-1.el7.x86_64   | 3        | 6.82%   |
| 5.15.35-4.el7.3.x86_64 | 2        | 4.55%   |
| 5.14.9-1.el7.x86_64    | 1        | 2.27%   |
| 5.10.24-3.el7.x86_64   | 1        | 2.27%   |
| 5.10.24-2.el7.x86_64   | 1        | 2.27%   |
| 5.10.1-1.el7.x86_64    | 1        | 2.27%   |
| 4.19.56-2.el7.x86_64   | 1        | 2.27%   |
| 4.19.204-1.el7.x86_64  | 1        | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.15.10  | 14       | 31.82%  |
| 5.10.29  | 12       | 27.27%  |
| 5.15.35  | 9        | 20.45%  |
| 4.19.79  | 3        | 6.82%   |
| 5.10.24  | 2        | 4.55%   |
| 5.14.9   | 1        | 2.27%   |
| 5.10.1   | 1        | 2.27%   |
| 4.19.56  | 1        | 2.27%   |
| 4.19.204 | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 23       | 52.27%  |
| 5.10    | 15       | 34.09%  |
| 4.19    | 5        | 11.36%  |
| 5.14    | 1        | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 39       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 30       | 71.43%  |
| Cinnamon   | 10       | 23.81%  |
| X-Cinnamon | 1        | 2.38%   |
| Unknown    | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 35       | 87.5%   |
| Wayland | 4        | 10%     |
| Unknown | 1        | 2.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 37       | 92.5%   |
| SDDM    | 2        | 5%      |
| Unknown | 1        | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 92.5%   |
| ru_RU   | 3        | 7.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 67.5%   |
| BIOS | 13       | 32.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 36       | 92.31%  |
| Btrfs   | 2        | 5.13%   |
| Unknown | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 28       | 70%     |
| MBR     | 11       | 27.5%   |
| Unknown | 1        | 2.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 82.5%   |
| Yes       | 7        | 17.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 82.5%   |
| Yes       | 7        | 17.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 33.33%  |
| ASUSTek Computer    | 9        | 23.08%  |
| DEPO Computers      | 4        | 10.26%  |
| ASRock              | 4        | 10.26%  |
| Aquarius            | 4        | 10.26%  |
| MSI                 | 3        | 7.69%   |
| Hewlett-Packard     | 1        | 2.56%   |
| Dell                | 1        | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B365M DS3H    | 4        | 10.26%  |
| DEPO Computers DPH310T | 4        | 10.26%  |
| MSI MS-7D14            | 2        | 5.13%   |
| Gigabyte B560M DS3H    | 2        | 5.13%   |
| MSI MS-7D35            | 1        | 2.56%   |
| HP Z400 Workstation    | 1        | 2.56%   |
| Gigabyte H410M H V3    | 1        | 2.56%   |
| Gigabyte H110M-M.2     | 1        | 2.56%   |
| Gigabyte B75M-D3V      | 1        | 2.56%   |
| Gigabyte B75M-D2V      | 1        | 2.56%   |
| Gigabyte B365M H       | 1        | 2.56%   |
| Gigabyte B360M-DS3H    | 1        | 2.56%   |
| Gigabyte 970A-D3       | 1        | 2.56%   |
| Dell OptiPlex 3020     | 1        | 2.56%   |
| ASUS PRIME H510T2/CSM  | 1        | 2.56%   |
| ASUS PRIME H510M-K     | 1        | 2.56%   |
| ASUS PC                | 1        | 2.56%   |
| ASUS P8H61-I LX R2.0   | 1        | 2.56%   |
| ASUS M2N68-AM Plus     | 1        | 2.56%   |
| ASUS H110M-PLUS        | 1        | 2.56%   |
| ASUS H110M-K           | 1        | 2.56%   |
| ASUS H110-PLUS         | 1        | 2.56%   |
| ASUS All Series        | 1        | 2.56%   |
| ASRock H470M-HDV       | 1        | 2.56%   |
| ASRock H110M-DVS R2.0  | 1        | 2.56%   |
| ASRock B560 Pro4       | 1        | 2.56%   |
| ASRock B365M Pro4-F    | 1        | 2.56%   |
| Aquarius Pro T584      | 1        | 2.56%   |
| Aquarius P30 K44 R53   | 1        | 2.56%   |
| Aquarius AQH410T       | 1        | 2.56%   |
| Aquarius AQB560M       | 1        | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte B365M         | 5        | 12.82%  |
| DEPO Computers DPH310T | 4        | 10.26%  |
| MSI MS-7D14            | 2        | 5.13%   |
| Gigabyte B560M         | 2        | 5.13%   |
| ASUS PRIME             | 2        | 5.13%   |
| MSI MS-7D35            | 1        | 2.56%   |
| HP Z400                | 1        | 2.56%   |
| Gigabyte H410M         | 1        | 2.56%   |
| Gigabyte H110M-M.2     | 1        | 2.56%   |
| Gigabyte B75M-D3V      | 1        | 2.56%   |
| Gigabyte B75M-D2V      | 1        | 2.56%   |
| Gigabyte B360M-DS3H    | 1        | 2.56%   |
| Gigabyte 970A-D3       | 1        | 2.56%   |
| Dell OptiPlex          | 1        | 2.56%   |
| ASUS PC                | 1        | 2.56%   |
| ASUS P8H61-I           | 1        | 2.56%   |
| ASUS M2N68-AM          | 1        | 2.56%   |
| ASUS H110M-PLUS        | 1        | 2.56%   |
| ASUS H110M-K           | 1        | 2.56%   |
| ASUS H110-PLUS         | 1        | 2.56%   |
| ASUS All               | 1        | 2.56%   |
| ASRock H470M-HDV       | 1        | 2.56%   |
| ASRock H110M-DVS       | 1        | 2.56%   |
| ASRock B560            | 1        | 2.56%   |
| ASRock B365M           | 1        | 2.56%   |
| Aquarius Pro           | 1        | 2.56%   |
| Aquarius P30           | 1        | 2.56%   |
| Aquarius AQH410T       | 1        | 2.56%   |
| Aquarius AQB560M       | 1        | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 28.21%  |
| 2020 | 6        | 15.38%  |
| 2019 | 6        | 15.38%  |
| 2012 | 4        | 10.26%  |
| 2016 | 3        | 7.69%   |
| 2022 | 2        | 5.13%   |
| 2017 | 2        | 5.13%   |
| 2018 | 1        | 2.56%   |
| 2014 | 1        | 2.56%   |
| 2013 | 1        | 2.56%   |
| 2010 | 1        | 2.56%   |
| 2009 | 1        | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 39       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 39       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 16       | 41.03%  |
| 4.01-8.0   | 8        | 20.51%  |
| 8.01-16.0  | 8        | 20.51%  |
| 3.01-4.0   | 5        | 12.82%  |
| 24.01-32.0 | 1        | 2.56%   |
| Unknown    | 1        | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 13       | 29.55%  |
| 4.01-8.0  | 11       | 25%     |
| 3.01-4.0  | 8        | 18.18%  |
| 0.51-1.0  | 6        | 13.64%  |
| 2.01-3.0  | 4        | 9.09%   |
| 8.01-16.0 | 1        | 2.27%   |
| Unknown   | 1        | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 60%     |
| 2      | 15       | 37.5%   |
| 4      | 1        | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 74.36%  |
| Yes       | 10       | 25.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 78.05%  |
| Yes       | 9        | 21.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 84.62%  |
| Yes       | 6        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 39       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Murom         | 13       | 33.33%  |
| Salekhard     | 9        | 23.08%  |
| Moscow        | 4        | 10.26%  |
| Yekaterinburg | 1        | 2.56%   |
| Ulyanovsk     | 1        | 2.56%   |
| Surgut        | 1        | 2.56%   |
| Stavropol     | 1        | 2.56%   |
| Penza         | 1        | 2.56%   |
| Kursk         | 1        | 2.56%   |
| Krasnodar     | 1        | 2.56%   |
| Kovrov        | 1        | 2.56%   |
| Kirov         | 1        | 2.56%   |
| Kholmsk       | 1        | 2.56%   |
| Kaluga        | 1        | 2.56%   |
| Bryansk       | 1        | 2.56%   |
| Arzamas       | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 29     | 34.55%  |
| Toshiba             | 5        | 5      | 9.09%   |
| WDC                 | 4        | 5      | 7.27%   |
| Apacer              | 4        | 4      | 7.27%   |
| A-DATA Technology   | 4        | 4      | 7.27%   |
| SanDisk             | 3        | 4      | 5.45%   |
| Foxline             | 3        | 3      | 5.45%   |
| Samsung Electronics | 2        | 2      | 3.64%   |
| KIOXIA-EXCERIA      | 2        | 2      | 3.64%   |
| Kingston            | 2        | 2      | 3.64%   |
| Crucial             | 2        | 4      | 3.64%   |
| Smartbuy            | 1        | 1      | 1.82%   |
| Patriot             | 1        | 1      | 1.82%   |
| ExeGate             | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |
| AMD                 | 1        | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000LM049-2GH172 1TB     | 4        | 7.14%   |
| Seagate ST1000DM010-2EP102 1TB     | 4        | 7.14%   |
| Apacer AS2280P4 256GB              | 4        | 7.14%   |
| Toshiba HDWD110 1TB                | 2        | 3.57%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 3.57%   |
| Seagate ST1000DM010-2DM162 1TB     | 2        | 3.57%   |
| Seagate ST1000DM003-1SB10C 1TB     | 2        | 3.57%   |
| SanDisk SD8SBAT256G1122 256GB SSD  | 2        | 3.57%   |
| KIOXIA-EXCERIA SATA SSD 480GB      | 2        | 3.57%   |
| Foxline FLSSD240X5SE 240GB         | 2        | 3.57%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 3.57%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 1.79%   |
| WDC WD3200AAKX-001CA0 320GB        | 1        | 1.79%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1.79%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1.79%   |
| Toshiba KHK61VSE960G 960GB SSD     | 1        | 1.79%   |
| Toshiba HDWD105 500GB              | 1        | 1.79%   |
| Toshiba DT01ACA200 2TB             | 1        | 1.79%   |
| Smartbuy SSD 240GB                 | 1        | 1.79%   |
| Seagate ST3400620AS 400GB          | 1        | 1.79%   |
| Seagate ST3320620AS 320GB          | 1        | 1.79%   |
| Seagate ST3250823AS 250GB          | 1        | 1.79%   |
| Seagate ST31000528AS 1TB           | 1        | 1.79%   |
| Seagate ST2000DM008-2UB102 2TB     | 1        | 1.79%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1.79%   |
| SanDisk SSD PLUS 240GB             | 1        | 1.79%   |
| Samsung SSD 870 EVO 250GB          | 1        | 1.79%   |
| Samsung SSD 860 EVO 250GB          | 1        | 1.79%   |
| Patriot P210 128GB SSD             | 1        | 1.79%   |
| Kingston SA400S37120G 120GB SSD    | 1        | 1.79%   |
| Kingston OM8PCP3512F-A02 512GB     | 1        | 1.79%   |
| Foxline FLSSD120SM5 120GB          | 1        | 1.79%   |
| ExeGate EX276690RUS(960G 960GB SSD | 1        | 1.79%   |
| China SSD 256GB                    | 1        | 1.79%   |
| AMD R5MP120G8 120GB                | 1        | 1.79%   |
| A-DATA SX6000PNP 256GB             | 1        | 1.79%   |
| A-DATA SU800 256GB SSD             | 1        | 1.79%   |
| A-DATA SU630 960GB SSD             | 1        | 1.79%   |
| A-DATA FALCON 512GB                | 1        | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 19       | 29     | 70.37%  |
| WDC     | 4        | 5      | 14.81%  |
| Toshiba | 4        | 4      | 14.81%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 3        | 4      | 15%     |
| Foxline             | 3        | 3      | 15%     |
| Samsung Electronics | 2        | 2      | 10%     |
| KIOXIA-EXCERIA      | 2        | 2      | 10%     |
| Crucial             | 2        | 4      | 10%     |
| A-DATA Technology   | 2        | 2      | 10%     |
| Toshiba             | 1        | 1      | 5%      |
| Smartbuy            | 1        | 1      | 5%      |
| Patriot             | 1        | 1      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| ExeGate             | 1        | 1      | 5%      |
| China               | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 38     | 47.17%  |
| SSD  | 20       | 23     | 37.74%  |
| NVMe | 8        | 8      | 15.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 37       | 61     | 82.22%  |
| NVMe | 8        | 8      | 17.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 28     | 50%     |
| 0.51-1.0   | 20       | 29     | 43.48%  |
| 1.01-2.0   | 3        | 4      | 6.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 501-1000   | 12       | 30.77%  |
| 101-250    | 11       | 28.21%  |
| 251-500    | 8        | 20.51%  |
| 51-100     | 3        | 7.69%   |
| 2001-3000  | 2        | 5.13%   |
| 1001-2000  | 2        | 5.13%   |
| Unknown    | 1        | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 24       | 54.55%  |
| 501-1000  | 6        | 13.64%  |
| 251-500   | 3        | 6.82%   |
| 21-50     | 3        | 6.82%   |
| 51-100    | 3        | 6.82%   |
| 101-250   | 2        | 4.55%   |
| 1001-2000 | 2        | 4.55%   |
| Unknown   | 1        | 2.27%   |

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
| Works   | 37       | 64     | 92.5%   |
| Malfunc | 3        | 5      | 7.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 35       | 74.47%  |
| Phison Electronics          | 4        | 8.51%   |
| AMD                         | 3        | 6.38%   |
| Realtek Semiconductor       | 2        | 4.26%   |
| Silicon Motion              | 1        | 2.13%   |
| Nvidia                      | 1        | 2.13%   |
| Kingston Technology Company | 1        | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 22%     |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 20%     |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 10%     |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 8%      |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4%      |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 4%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 2%      |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2%      |
| Nvidia MCP61 IDE                                                                        | 1        | 2%      |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 2%      |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2%      |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 2%      |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 74.47%  |
| NVMe | 8        | 17.02%  |
| IDE  | 3        | 6.38%   |
| RAID | 1        | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 89.74%  |
| AMD    | 4        | 10.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz           | 10       | 25.64%  |
| Intel Core i3-10100 CPU @ 3.60GHz          | 7        | 17.95%  |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3        | 7.69%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2        | 5.13%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 2        | 5.13%   |
| Intel Xeon CPU W3670 @ 3.20GHz             | 1        | 2.56%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz     | 1        | 2.56%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 2.56%   |
| Intel Pentium CPU G4500 @ 3.50GHz          | 1        | 2.56%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 2.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 1        | 2.56%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 1        | 2.56%   |
| Intel Core i5-10500 CPU @ 3.10GHz          | 1        | 2.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1        | 2.56%   |
| Intel Core i3-10105 CPU @ 3.70GHz          | 1        | 2.56%   |
| Intel Celeron G5925 CPU @ 3.60GHz          | 1        | 2.56%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 1        | 2.56%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz     | 1        | 2.56%   |
| AMD FX-6300 Six-Core Processor             | 1        | 2.56%   |
| AMD Athlon II X2 240 Processor             | 1        | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 17       | 43.59%  |
| Intel Core i3      | 11       | 28.21%  |
| Intel Pentium      | 2        | 5.13%   |
| Intel Celeron      | 2        | 5.13%   |
| AMD Ryzen 7 PRO    | 2        | 5.13%   |
| Other              | 1        | 2.56%   |
| Intel Xeon         | 1        | 2.56%   |
| Intel Pentium Gold | 1        | 2.56%   |
| AMD FX             | 1        | 2.56%   |
| AMD Athlon II X2   | 1        | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 15       | 38.46%  |
| 4      | 12       | 30.77%  |
| 2      | 9        | 23.08%  |
| 8      | 2        | 5.13%   |
| 3      | 1        | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 51.28%  |
| 2      | 19       | 48.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 97.44%  |
| Unknown        | 1        | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 11       | 27.5%   |
| 0x906ed    | 8        | 20%     |
| 0x506e3    | 4        | 10%     |
| 0x906ea    | 3        | 7.5%    |
| 0x306a9    | 3        | 7.5%    |
| 0x306c3    | 2        | 5%      |
| 0x08600106 | 2        | 5%      |
| 0xa0671    | 1        | 2.5%    |
| 0xa0654    | 1        | 2.5%    |
| 0x906e9    | 1        | 2.5%    |
| 0x206c2    | 1        | 2.5%    |
| 0x06000852 | 1        | 2.5%    |
| 0x010000c7 | 1        | 2.5%    |
| Unknown    | 1        | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KabyLake   | 12       | 30.77%  |
| CometLake  | 12       | 30.77%  |
| Skylake    | 4        | 10.26%  |
| IvyBridge  | 3        | 7.69%   |
| Zen 2      | 2        | 5.13%   |
| Haswell    | 2        | 5.13%   |
| Westmere   | 1        | 2.56%   |
| Piledriver | 1        | 2.56%   |
| K10        | 1        | 2.56%   |
| Unknown    | 1        | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 79.49%  |
| Nvidia | 4        | 10.26%  |
| AMD    | 4        | 10.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 25%     |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 9        | 22.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 7.5%    |
| Intel HD Graphics 530                                                       | 3        | 7.5%    |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2        | 5%      |
| AMD Renoir                                                                  | 2        | 5%      |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.5%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 2.5%    |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.5%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 2.5%    |
| Intel HD Graphics 610                                                       | 1        | 2.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.5%    |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                       | 1        | 2.5%    |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                   | 1        | 2.5%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 31       | 79.49%  |
| 1 x Nvidia | 4        | 10.26%  |
| 1 x AMD    | 3        | 7.69%   |
| 2 x AMD    | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 31       | 79.49%  |
| Unknown     | 7        | 17.95%  |
| Proprietary | 1        | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 82.05%  |
| 1.01-2.0   | 3        | 7.69%   |
| 0.01-0.5   | 2        | 5.13%   |
| 3.01-4.0   | 1        | 2.56%   |
| 0.51-1.0   | 1        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 9        | 23.68%  |
| ViewSonic           | 7        | 18.42%  |
| Samsung Electronics | 6        | 15.79%  |
| Acer                | 5        | 13.16%  |
| BenQ                | 3        | 7.89%   |
| AOC                 | 3        | 7.89%   |
| SGT                 | 2        | 5.26%   |
| DOY                 | 1        | 2.63%   |
| Dell                | 1        | 2.63%   |
| CHR                 | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 15%     |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 4        | 10%     |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 2        | 5%      |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 2        | 5%      |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 5%      |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 2        | 5%      |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                  | 1        | 2.5%    |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 1        | 2.5%    |
| ViewSonic LCD Monitor VSC8C31 1920x1080 520x290mm 23.4-inch           | 1        | 2.5%    |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch | 1        | 2.5%    |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch | 1        | 2.5%    |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 1        | 2.5%    |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch             | 1        | 2.5%    |
| DOY LCD Monitor DOY2760 1920x1080 598x336mm 27.0-inch                 | 1        | 2.5%    |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 1        | 2.5%    |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 1        | 2.5%    |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                      | 1        | 2.5%    |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                      | 1        | 2.5%    |
| AOC Q3277 AOC3277 2560x1440 708x399mm 32.0-inch                       | 1        | 2.5%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 1        | 2.5%    |
| AOC 2250W AOC2250 1920x1080 480x270mm 21.7-inch                       | 1        | 2.5%    |
| Acer VG272U ACR0778 2560x1440 597x336mm 27.0-inch                     | 1        | 2.5%    |
| Acer V243HQ ACR00B0 1920x1080 521x293mm 23.5-inch                     | 1        | 2.5%    |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 1        | 2.5%    |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 1        | 2.5%    |
| Acer H226HQL ACR0319 1920x1080 476x268mm 21.5-inch                    | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 24       | 70.59%  |
| 2560x1440 (QHD)   | 5        | 14.71%  |
| 3840x2160 (4K)    | 1        | 2.94%   |
| 1920x1200 (WUXGA) | 1        | 2.94%   |
| 1600x900 (HD+)    | 1        | 2.94%   |
| 1280x1024 (SXGA)  | 1        | 2.94%   |
| 1024x768 (XGA)    | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 12       | 31.58%  |
| 23     | 9        | 23.68%  |
| 27     | 8        | 21.05%  |
| 21     | 4        | 10.53%  |
| 32     | 1        | 2.63%   |
| 31     | 1        | 2.63%   |
| 20     | 1        | 2.63%   |
| 19     | 1        | 2.63%   |
| 15     | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 73.53%  |
| 401-500     | 5        | 14.71%  |
| 701-800     | 1        | 2.94%   |
| 601-700     | 1        | 2.94%   |
| 351-400     | 1        | 2.94%   |
| 301-350     | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 30       | 88.24%  |
| 16/10 | 2        | 5.88%   |
| 5/4   | 1        | 2.94%   |
| 4/3   | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 58.33%  |
| 301-350        | 8        | 22.22%  |
| 351-500        | 2        | 5.56%   |
| 251-300        | 2        | 5.56%   |
| 151-200        | 2        | 5.56%   |
| 101-110        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 71.88%  |
| 101-120 | 9        | 28.13%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 71.43%  |
| 2     | 6        | 14.29%  |
| 0     | 6        | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 32       | 71.11%  |
| Intel                 | 8        | 17.78%  |
| Ralink Technology     | 1        | 2.22%   |
| Nvidia                | 1        | 2.22%   |
| Mercucys              | 1        | 2.22%   |
| Edimax Technology     | 1        | 2.22%   |
| Broadcom              | 1        | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 62.5%   |
| Intel Ethernet Controller I225-V                                  | 3        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 4.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.17%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 4.17%   |
| Realtek 802.11ac NIC                                              | 1        | 2.08%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.08%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.08%   |
| Mercucys 802.11n NIC                                              | 1        | 2.08%   |
| Intel Wireless 3165                                               | 1        | 2.08%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU]   | 1        | 2.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 55.56%  |
| Ralink Technology     | 1        | 11.11%  |
| Mercucys              | 1        | 11.11%  |
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
| Ralink MT7601U Wireless Adapter                                 | 1        | 11.11%  |
| Mercucys 802.11n NIC                                            | 1        | 11.11%  |
| Intel Wireless 3165                                             | 1        | 11.11%  |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 76.92%  |
| Intel                 | 7        | 17.95%  |
| Nvidia                | 1        | 2.56%   |
| Broadcom              | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 76.92%  |
| Intel Ethernet Controller I225-V                                  | 3        | 7.69%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 5.13%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 5.13%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 81.25%  |
| WiFi     | 9        | 18.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 95.12%  |
| WiFi     | 2        | 4.88%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 82.05%  |
| 2     | 7        | 17.95%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 100%    |

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
| Intel  | 35       | 83.33%  |
| AMD    | 4        | 9.52%   |
| Nvidia | 3        | 7.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 10       | 21.74%  |
| Intel 200 Series PCH HD Audio                                              | 10       | 21.74%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 10.87%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 4.35%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.17%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2.17%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.17%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 8        | 19.51%  |
| Foxline             | 7        | 17.07%  |
| Kingston            | 6        | 14.63%  |
| Unknown             | 3        | 7.32%   |
| SK hynix            | 3        | 7.32%   |
| AMD                 | 3        | 7.32%   |
| Samsung Electronics | 2        | 4.88%   |
| Corsair             | 2        | 4.88%   |
| Qumo                | 1        | 2.44%   |
| Patriot             | 1        | 2.44%   |
| Neo Forza           | 1        | 2.44%   |
| ChangXin Memory     | 1        | 2.44%   |
| Apacer              | 1        | 2.44%   |
| A-DATA Technology   | 1        | 2.44%   |
| Unknown             | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s          | 4        | 9.52%   |
| Foxline RAM FL2666D4U19-8G 8192MB DIMM DDR4 2667MT/s         | 3        | 7.14%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 2        | 4.76%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 4.76%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                  | 2        | 4.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 2.38%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 2.38%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 2.38%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 2.38%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 1        | 2.38%   |
| Samsung RAM M378B5273DH0 4GB DIMM DDR3 1333MT/s              | 1        | 2.38%   |
| Qumo RAM QUM4U-4G2133KK15 4GB DIMM DDR4 2133MT/s             | 1        | 2.38%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s              | 1        | 2.38%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 1        | 2.38%   |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 2.38%   |
| Kingston RAM 99U5471-060.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 2.38%   |
| Kingston RAM 99U5471-047.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 2.38%   |
| Kingston RAM 99P5663-010.A00G 16GB SODIMM DDR4 2667MT/s      | 1        | 2.38%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s       | 1        | 2.38%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s         | 1        | 2.38%   |
| Crucial RAM CT8G4DFS824A.M8FH3 8GB DIMM DDR4 2400MT/s        | 1        | 2.38%   |
| Crucial RAM CT8G4DFRA266.C8FP 8GB DIMM DDR4 2666MT/s         | 1        | 2.38%   |
| Crucial RAM CT8G4DFRA266.C16FG 8GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Crucial RAM CT8G4DFD8213.M16FA 8192MB DIMM DDR4 2133MT/s     | 1        | 2.38%   |
| Crucial RAM CT4G4DFS824A.C8FE 4GB DIMM DDR4 2400MT/s         | 1        | 2.38%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s       | 1        | 2.38%   |
| Corsair RAM CMX4GX3M2A160 2GB DIMM DDR3 1333MT/s             | 1        | 2.38%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s         | 1        | 2.38%   |
| ChangXin Memory RAM QUM4S-8G2666P19 8GB SODIMM DDR4 2667MT/s | 1        | 2.38%   |
| Apacer RAM D22.22242S.001 8GB SODIMM DDR4 2667MT/s           | 1        | 2.38%   |
| AMD RAM R744G2606U1S 4GB DIMM DDR4 2866MT/s                  | 1        | 2.38%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 1        | 2.38%   |
| Unknown                                                      | 1        | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 29       | 80.56%  |
| DDR3 | 6        | 16.67%  |
| DDR2 | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 77.78%  |
| SODIMM | 8        | 22.22%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 60.98%  |
| 4096  | 10       | 24.39%  |
| 16384 | 3        | 7.32%   |
| 2048  | 3        | 7.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 16       | 40%     |
| 3200  | 4        | 10%     |
| 1333  | 4        | 10%     |
| 2400  | 3        | 7.5%    |
| 2133  | 3        | 7.5%    |
| 1600  | 2        | 5%      |
| 3466  | 1        | 2.5%    |
| 3000  | 1        | 2.5%    |
| 2934  | 1        | 2.5%    |
| 2866  | 1        | 2.5%    |
| 2800  | 1        | 2.5%    |
| 2666  | 1        | 2.5%    |
| 1800  | 1        | 2.5%    |
| 800   | 1        | 2.5%    |

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
| 0     | 30       | 75%     |
| 1     | 10       | 25%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 7        | 70%     |
| Net/wireless  | 2        | 20%     |
| Chipcard      | 1        | 10%     |

