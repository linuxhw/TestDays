GNOME OS - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GNOME OS.

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

Total: 31

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B550M-ITX/ac                | [71efebc36f](https://linux-hardware.org/?probe=71efebc36f) | Nov 17, 2025 |
| ASRock        | B550M-ITX/ac                | [21347e70d0](https://linux-hardware.org/?probe=21347e70d0) | Sep 23, 2025 |
| Unknown       | Unknown                     | [04df8f67e8](https://linux-hardware.org/?probe=04df8f67e8) | Sep 19, 2025 |
| MSI           | H81M-P33                    | [18d0d50173](https://linux-hardware.org/?probe=18d0d50173) | Sep 04, 2025 |
| Gigabyte      | B550 AORUS PRO AC           | [64dcae5fdc](https://linux-hardware.org/?probe=64dcae5fdc) | Apr 21, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8fa24df745](https://linux-hardware.org/?probe=8fa24df745) | Dec 18, 2024 |
| MSI           | Z97 GAMING 3                | [a04a3de413](https://linux-hardware.org/?probe=a04a3de413) | Jul 27, 2024 |
| ASUSTek       | X99-A/USB                   | [9a5a476598](https://linux-hardware.org/?probe=9a5a476598) | May 16, 2024 |
| Gigabyte      | B450M DS3H-CF               | [c21a61a96d](https://linux-hardware.org/?probe=c21a61a96d) | Mar 23, 2024 |
| MSI           | Z97 GAMING 3                | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Intel         | H61                         | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| Unknown       | 1.0                         | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Gigabyte      | B450M S2H V2                | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| ASUSTek       | H61M-A/BR                   | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| HP            | 8767 A                      | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte      | X570 GAMING X               | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte      | B450M S2H V2                | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel         | X79                         | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo        | 317E NOK                    | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| ASUSTek       | PRIME H410M-K               | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Acer          | Aspire GX-781               | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek       | SABERTOOTH X79              | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME OS Nightly | 19       | 76%     |
| GNOME OS 3.38    | 2        | 8%      |
| GNOME OS 49      | 1        | 4%      |
| GNOME OS 46      | 1        | 4%      |
| GNOME OS 43      | 1        | 4%      |
| GNOME OS 41      | 1        | 4%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME OS | 25       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 18.52%  |
| 6.16.4  | 3        | 11.11%  |
| 5.7.14  | 2        | 7.41%   |
| 5.19.17 | 2        | 7.41%   |
| 5.19.16 | 2        | 7.41%   |
| 5.13.9  | 2        | 7.41%   |
| 6.9.8   | 1        | 3.7%    |
| 6.7.9   | 1        | 3.7%    |
| 6.6.10  | 1        | 3.7%    |
| 6.4.0   | 1        | 3.7%    |
| 6.17.6  | 1        | 3.7%    |
| 6.13.6  | 1        | 3.7%    |
| 6.12.4  | 1        | 3.7%    |
| 5.18.16 | 1        | 3.7%    |
| 5.14.4  | 1        | 3.7%    |
| 5.12.12 | 1        | 3.7%    |
| 5.11.0  | 1        | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 18.52%  |
| 6.16.4  | 3        | 11.11%  |
| 5.7.14  | 2        | 7.41%   |
| 5.19.17 | 2        | 7.41%   |
| 5.19.16 | 2        | 7.41%   |
| 5.13.9  | 2        | 7.41%   |
| 6.9.8   | 1        | 3.7%    |
| 6.7.9   | 1        | 3.7%    |
| 6.6.10  | 1        | 3.7%    |
| 6.4.0   | 1        | 3.7%    |
| 6.17.6  | 1        | 3.7%    |
| 6.13.6  | 1        | 3.7%    |
| 6.12.4  | 1        | 3.7%    |
| 5.18.16 | 1        | 3.7%    |
| 5.14.4  | 1        | 3.7%    |
| 5.12.12 | 1        | 3.7%    |
| 5.11.0  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 6        | 22.22%  |
| 5.19    | 4        | 14.81%  |
| 6.16    | 3        | 11.11%  |
| 5.7     | 2        | 7.41%   |
| 5.13    | 2        | 7.41%   |
| 6.9     | 1        | 3.7%    |
| 6.7     | 1        | 3.7%    |
| 6.6     | 1        | 3.7%    |
| 6.4     | 1        | 3.7%    |
| 6.17    | 1        | 3.7%    |
| 6.13    | 1        | 3.7%    |
| 6.12    | 1        | 3.7%    |
| 5.18    | 1        | 3.7%    |
| 5.14    | 1        | 3.7%    |
| 5.12    | 1        | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| GNOME | 25       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 24       | 96%     |
| Tty     | 1        | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 40%     |
| pt_BR | 4        | 16%     |
| de_DE | 4        | 16%     |
| it_IT | 2        | 8%      |
| cs_CZ | 2        | 8%      |
| ru_UA | 1        | 4%      |
| es_ES | 1        | 4%      |
| en_IN | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 24       | 96%     |
| BIOS | 1        | 4%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 19       | 73.08%  |
| Btrfs | 7        | 26.92%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 96%     |
| GPT     | 1        | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 7        | 28%     |
| Gigabyte Technology | 5        | 20%     |
| MSI                 | 2        | 8%      |
| Intel               | 2        | 8%      |
| Hewlett-Packard     | 2        | 8%      |
| ASRock              | 2        | 8%      |
| Unknown             | 2        | 8%      |
| Lenovo              | 1        | 4%      |
| Colorful Technology | 1        | 4%      |
| Acer                | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASRock B550M-ITX/ac                    | 2        | 8%      |
| Unknown                                | 2        | 8%      |
| MSI MS-7918                            | 1        | 4%      |
| MSI MS-7817                            | 1        | 4%      |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1        | 4%      |
| Intel X79                              | 1        | 4%      |
| Intel H61                              | 1        | 4%      |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1        | 4%      |
| HP Pavilion Desktop PC 570-p0xx        | 1        | 4%      |
| Gigabyte Z97X-Gaming 7                 | 1        | 4%      |
| Gigabyte X570 GAMING X                 | 1        | 4%      |
| Gigabyte B550 AORUS PRO AC             | 1        | 4%      |
| Gigabyte B450M S2H V2                  | 1        | 4%      |
| Gigabyte B450M DS3H                    | 1        | 4%      |
| Colorful BATTLE-AX B660M-HD DELUXE     | 1        | 4%      |
| ASUS TUF Gaming B550M-PLUS             | 1        | 4%      |
| ASUS TERRA_PC                          | 1        | 4%      |
| ASUS SABERTOOTH X79                    | 1        | 4%      |
| ASUS PRIME H410M-K                     | 1        | 4%      |
| ASUS PRIME A320M-K                     | 1        | 4%      |
| ASUS M5A97 R2.0                        | 1        | 4%      |
| ASUS H61M-A/BR                         | 1        | 4%      |
| Acer Aspire GX-781                     | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Pavilion          | 2        | 8%      |
| Gigabyte B450M       | 2        | 8%      |
| ASUS PRIME           | 2        | 8%      |
| ASRock B550M-ITX     | 2        | 8%      |
| Unknown              | 2        | 8%      |
| MSI MS-7918          | 1        | 4%      |
| MSI MS-7817          | 1        | 4%      |
| Lenovo IdeaCentre    | 1        | 4%      |
| Intel X79            | 1        | 4%      |
| Intel H61            | 1        | 4%      |
| Gigabyte Z97X-Gaming | 1        | 4%      |
| Gigabyte X570        | 1        | 4%      |
| Gigabyte B550        | 1        | 4%      |
| Colorful BATTLE-AX   | 1        | 4%      |
| ASUS TUF             | 1        | 4%      |
| ASUS TERRA           | 1        | 4%      |
| ASUS SABERTOOTH      | 1        | 4%      |
| ASUS M5A97           | 1        | 4%      |
| ASUS H61M-A          | 1        | 4%      |
| Acer Aspire          | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 8        | 32%     |
| 2022 | 2        | 8%      |
| 2019 | 2        | 8%      |
| 2017 | 2        | 8%      |
| 2016 | 2        | 8%      |
| 2014 | 2        | 8%      |
| 2013 | 2        | 8%      |
| 2012 | 2        | 8%      |
| 2021 | 1        | 4%      |
| 2018 | 1        | 4%      |
| 2009 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 7        | 28%     |
| 16.01-24.0  | 6        | 24%     |
| 8.01-16.0   | 6        | 24%     |
| 3.01-4.0    | 4        | 16%     |
| 4.01-8.0    | 1        | 4%      |
| 64.01-256.0 | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 11       | 42.31%  |
| 3.01-4.0  | 6        | 23.08%  |
| 2.01-3.0  | 4        | 15.38%  |
| 4.01-8.0  | 2        | 7.69%   |
| 0.51-1.0  | 2        | 7.69%   |
| 8.01-16.0 | 1        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 36%     |
| 1      | 9        | 36%     |
| 4      | 4        | 16%     |
| 3      | 3        | 12%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 80%     |
| Yes       | 5        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 61.54%  |
| No        | 10       | 38.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 52%     |
| No        | 12       | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Brazil             | 5        | 20%     |
| Germany            | 4        | 16%     |
| USA                | 3        | 12%     |
| Italy              | 2        | 8%      |
| India              | 2        | 8%      |
| Czechia            | 2        | 8%      |
| Ukraine            | 1        | 4%      |
| Thailand           | 1        | 4%      |
| Spain              | 1        | 4%      |
| Russia             | 1        | 4%      |
| Romania            | 1        | 4%      |
| Dominican Republic | 1        | 4%      |
| Canada             | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Waldachtal             | 1        | 4%      |
| Verden an der Aller    | 1        | 4%      |
| Vancouver              | 1        | 4%      |
| Tyumen                 | 1        | 4%      |
| Targoviste             | 1        | 4%      |
| St. Ingbert            | 1        | 4%      |
| Si Racha               | 1        | 4%      |
| Sesto Fiorentino       | 1        | 4%      |
| Sao Bernardo do Campo  | 1        | 4%      |
| Rome                   | 1        | 4%      |
| Rio de Janeiro         | 1        | 4%      |
| Prague                 | 1        | 4%      |
| Ottawa                 | 1        | 4%      |
| Novoyavorovske         | 1        | 4%      |
| Munich                 | 1        | 4%      |
| Mumbai                 | 1        | 4%      |
| Kolkata                | 1        | 4%      |
| Goiânia               | 1        | 4%      |
| Getxo                  | 1        | 4%      |
| Foz do Iguaçu         | 1        | 4%      |
| Concepción de la Vega | 1        | 4%      |
| Columbia               | 1        | 4%      |
| Brdo                   | 1        | 4%      |
| Brasília              | 1        | 4%      |
| Bolivia                | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 10       | 12     | 20.83%  |
| Samsung Electronics         | 7        | 9      | 14.58%  |
| Kingston                    | 7        | 8      | 14.58%  |
| WDC                         | 5        | 5      | 10.42%  |
| Toshiba                     | 3        | 3      | 6.25%   |
| Sandisk                     | 3        | 4      | 6.25%   |
| SOLIDIGM                    | 1        | 1      | 2.08%   |
| SK hynix                    | 1        | 1      | 2.08%   |
| PNY                         | 1        | 1      | 2.08%   |
| Phison Electronics          | 1        | 1      | 2.08%   |
| Micron/Crucial Technology   | 1        | 1      | 2.08%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 2.08%   |
| Kingston Technology Company | 1        | 1      | 2.08%   |
| Fanxiang                    | 1        | 1      | 2.08%   |
| Crucial                     | 1        | 2      | 2.08%   |
| CONSISTENT                  | 1        | 1      | 2.08%   |
| Apacer                      | 1        | 1      | 2.08%   |
| AirDisk                     | 1        | 1      | 2.08%   |
| ADATA Technology            | 1        | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 3.92%   |
| WDC WD5000AAKX-003CA0 500GB                       | 1        | 1.96%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 1        | 1.96%   |
| WDC WD1600AAJS-22L7A0 160GB                       | 1        | 1.96%   |
| WDC WD10SPZX-00Z10T0 1TB                          | 1        | 1.96%   |
| WDC WD10EALX-009BA0 1TB                           | 1        | 1.96%   |
| Toshiba HDWD120 2TB                               | 1        | 1.96%   |
| Toshiba DT01ACA100 1TB                            | 1        | 1.96%   |
| Toshiba DT01ACA050 500GB                          | 1        | 1.96%   |
| SOLIDIGM NVMe SSD Drive 2TB                       | 1        | 1.96%   |
| SK hynix HFS128G39TND-N210A 128GB SSD             | 1        | 1.96%   |
| Seagate ST9500325AS 500GB                         | 1        | 1.96%   |
| Seagate ST8000DM004-2CX188 8TB                    | 1        | 1.96%   |
| Seagate ST4000DX001-1CE168 4TB                    | 1        | 1.96%   |
| Seagate ST3500312CS 500GB                         | 1        | 1.96%   |
| Seagate ST31000528AS 1TB                          | 1        | 1.96%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1        | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1        | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB                    | 1        | 1.96%   |
| Seagate ST1000DM003-1CH162 1TB                    | 1        | 1.96%   |
| Sandisk WD Black SN850 1TB                        | 1        | 1.96%   |
| SanDisk Ultra II 240GB SSD                        | 1        | 1.96%   |
| SanDisk NVMe SSD Drive 500GB                      | 1        | 1.96%   |
| Samsung SSD 9100 PRO 1TB                          | 1        | 1.96%   |
| Samsung SSD 870 QVO 1TB                           | 1        | 1.96%   |
| Samsung SSD 860 QVO 1TB                           | 1        | 1.96%   |
| Samsung SSD 840 EVO 250GB                         | 1        | 1.96%   |
| Samsung NVMe SSD Drive 512GB                      | 1        | 1.96%   |
| Samsung NVMe SSD Drive 256GB                      | 1        | 1.96%   |
| Samsung NVMe SSD Drive 1024GB                     | 1        | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1.96%   |
| PNY CS900 240GB SSD                               | 1        | 1.96%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 1        | 1.96%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB               | 1        | 1.96%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB  | 1        | 1.96%   |
| Kingston Company SNV2S1000G 1TB                   | 1        | 1.96%   |
| Kingston SV300S37A240G 240GB SSD                  | 1        | 1.96%   |
| Kingston SV300S37A120G 120GB SSD                  | 1        | 1.96%   |
| Kingston SUV400S37120G 120GB SSD                  | 1        | 1.96%   |
| Kingston SNVS500G 500GB                           | 1        | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 12     | 55.56%  |
| WDC     | 5        | 5      | 27.78%  |
| Toshiba | 3        | 3      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 7      | 38.89%  |
| Samsung Electronics | 3        | 4      | 16.67%  |
| SK hynix            | 1        | 1      | 5.56%   |
| SanDisk             | 1        | 1      | 5.56%   |
| PNY                 | 1        | 1      | 5.56%   |
| Fanxiang            | 1        | 1      | 5.56%   |
| Crucial             | 1        | 2      | 5.56%   |
| CONSISTENT          | 1        | 1      | 5.56%   |
| Apacer              | 1        | 1      | 5.56%   |
| AirDisk             | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 15       | 20     | 36.59%  |
| HDD  | 15       | 20     | 36.59%  |
| NVMe | 11       | 15     | 26.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 40     | 66.67%  |
| NVMe | 11       | 15     | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 21     | 48.39%  |
| 0.51-1.0   | 10       | 13     | 32.26%  |
| 1.01-2.0   | 3        | 3      | 9.68%   |
| 3.01-4.0   | 2        | 2      | 6.45%   |
| 4.01-10.0  | 1        | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 8        | 30.77%  |
| 501-1000   | 8        | 30.77%  |
| 251-500    | 4        | 15.38%  |
| 1001-2000  | 4        | 15.38%  |
| 2001-3000  | 1        | 3.85%   |
| 51-100     | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 15       | 55.56%  |
| 21-50    | 4        | 14.81%  |
| 501-1000 | 3        | 11.11%  |
| 101-250  | 2        | 7.41%   |
| 51-100   | 2        | 7.41%   |
| 251-500  | 1        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 25       | 55     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 16       | 38.1%   |
| AMD                         | 9        | 21.43%  |
| Samsung Electronics         | 5        | 11.9%   |
| SanDisk                     | 2        | 4.76%   |
| Marvell Technology Group    | 2        | 4.76%   |
| Kingston Technology Company | 2        | 4.76%   |
| Solidigm                    | 1        | 2.38%   |
| Phison Electronics          | 1        | 2.38%   |
| Micron/Crucial Technology   | 1        | 2.38%   |
| MAXIO Technology (Hangzhou) | 1        | 2.38%   |
| ASMedia Technology          | 1        | 2.38%   |
| ADATA Technology            | 1        | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 8.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 8.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 6.52%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 4.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 4.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 4.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 4.35%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                                    | 1        | 2.17%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 2.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 2.17%   |
| Samsung NVMe SSD 9100 PRO [PM9E1]                                                       | 1        | 2.17%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 2.17%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 2.17%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 1        | 2.17%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 2.17%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 2.17%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                                        | 1        | 2.17%   |
| Kingston Company NV1 NVMe SSD [E13T] (DRAM-less)                                        | 1        | 2.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 2.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.17%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.17%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.17%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 1        | 2.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 61.11%  |
| NVMe | 11       | 30.56%  |
| RAID | 2        | 5.56%   |
| IDE  | 1        | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 64%     |
| AMD    | 9        | 36%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 8%      |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 8%      |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz         | 1        | 4%      |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 4%      |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 4%      |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 4%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 4%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 4%      |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 4%      |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 4%      |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 4%      |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 4%      |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 4%      |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 4%      |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 4%      |
| Intel 12th Gen Core i3-12100                | 1        | 4%      |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 1        | 4%      |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 4%      |
| AMD Ryzen 7 5700X 8-Core Processor          | 1        | 4%      |
| AMD Ryzen 5 3600X 6-Core Processor          | 1        | 4%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 4%      |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 4%      |
| AMD FX-6300 Six-Core Processor              | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i3 | 6        | 24%     |
| AMD Ryzen 5   | 5        | 20%     |
| Intel Core i5 | 3        | 12%     |
| AMD Ryzen 7   | 3        | 12%     |
| Intel Xeon    | 2        | 8%      |
| Intel Core i7 | 2        | 8%      |
| Other         | 1        | 4%      |
| Intel Pentium | 1        | 4%      |
| Intel Celeron | 1        | 4%      |
| AMD FX        | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 32%     |
| 6      | 6        | 24%     |
| 2      | 5        | 20%     |
| 8      | 4        | 16%     |
| 18     | 1        | 4%      |
| 3      | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 84%     |
| 1      | 4        | 16%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 32%     |
| 0xa0653    | 3        | 12%     |
| 0x906e9    | 2        | 8%      |
| 0x90675    | 1        | 4%      |
| 0x506c9    | 1        | 4%      |
| 0x306e4    | 1        | 4%      |
| 0x306c3    | 1        | 4%      |
| 0x306a9    | 1        | 4%      |
| 0x206d7    | 1        | 4%      |
| 0x206a7    | 1        | 4%      |
| 0x0a201009 | 1        | 4%      |
| 0x08701021 | 1        | 4%      |
| 0x08108109 | 1        | 4%      |
| 0x0800820d | 1        | 4%      |
| 0x06000822 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 5        | 20%     |
| Haswell          | 4        | 16%     |
| IvyBridge        | 3        | 12%     |
| CometLake        | 3        | 12%     |
| Zen+             | 2        | 8%      |
| SandyBridge      | 2        | 8%      |
| KabyLake         | 2        | 8%      |
| Zen 2            | 1        | 4%      |
| Piledriver       | 1        | 4%      |
| Goldmont         | 1        | 4%      |
| Alderlake Hybrid | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 13       | 52%     |
| AMD    | 7        | 28%     |
| Intel  | 5        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 3        | 12%     |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2        | 8%      |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 4%      |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 4%      |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 4%      |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 4%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 4%      |
| Nvidia GA102 [GeForce RTX 3090]                                           | 1        | 4%      |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                            | 1        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 4%      |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                   | 1        | 4%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 4%      |
| Intel Apollo Lake [HD Graphics 505]                                       | 1        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 4%      |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                  | 1        | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 4%      |
| AMD Navi 44 [Radeon RX 9060 XT]                                           | 1        | 4%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 1        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 4%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 4%      |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 13       | 52%     |
| 1 x AMD    | 7        | 28%     |
| 1 x Intel  | 5        | 20%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Desktops | Percent |
|--------|----------|---------|
| Free   | 25       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 32%     |
| 7.01-8.0   | 4        | 16%     |
| 1.01-2.0   | 4        | 16%     |
| 3.01-4.0   | 3        | 12%     |
| 2.01-3.0   | 3        | 12%     |
| 5.01-6.0   | 2        | 8%      |
| 8.01-16.0  | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 23.08%  |
| Goldstar             | 4        | 15.38%  |
| AOC                  | 3        | 11.54%  |
| Acer                 | 3        | 11.54%  |
| Viotek               | 2        | 7.69%   |
| Dell                 | 2        | 7.69%   |
| SuperFrame           | 1        | 3.85%   |
| Sony                 | 1        | 3.85%   |
| Philips              | 1        | 3.85%   |
| Iiyama               | 1        | 3.85%   |
| Hewlett-Packard      | 1        | 3.85%   |
| Ancor Communications | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                   | 2        | 7.14%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 7.14%   |
| SuperFrame SFV2409 SUE2409 1920x1080 597x336mm 27.0-inch              | 1        | 3.57%   |
| Sony TV SNY4803 1920x1080 1218x685mm 55.0-inch                        | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 1        | 3.57%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 3.57%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 3.57%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1        | 3.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.57%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 3.57%   |
| Iiyama X2485 IVM6122 1920x1200 518x324mm 24.1-inch                    | 1        | 3.57%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 1        | 3.57%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                   | 1        | 3.57%   |
| Goldstar M2262D GSM5755 1920x1080 598x336mm 27.0-inch                 | 1        | 3.57%   |
| Goldstar LG ULTRAGEAR GSM5B73 1920x1080 530x300mm 24.0-inch           | 1        | 3.57%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 1        | 3.57%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 1        | 3.57%   |
| Dell S2721DS DELA19E 2560x1440 597x336mm 27.0-inch                    | 1        | 3.57%   |
| Dell G2724D DELD177 2560x1440 596x335mm 26.9-inch                     | 1        | 3.57%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 1        | 3.57%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 1        | 3.57%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 1        | 3.57%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 1        | 3.57%   |
| Acer K222HQL ACR0512 1920x1080 480x270mm 21.7-inch                    | 1        | 3.57%   |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                   | 1        | 3.57%   |
| Acer EK220Q ACR0757 1920x1080 477x268mm 21.5-inch                     | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 15       | 62.5%   |
| 3440x1440         | 2        | 8.33%   |
| 2560x1440 (QHD)   | 2        | 8.33%   |
| 1440x900 (WXGA+)  | 2        | 8.33%   |
| 3840x2160 (4K)    | 1        | 4.17%   |
| 1920x1200 (WUXGA) | 1        | 4.17%   |
| 1366x768 (WXGA)   | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 4        | 14.81%  |
| 21     | 4        | 14.81%  |
| 27     | 3        | 11.11%  |
| 24     | 3        | 11.11%  |
| 40     | 2        | 7.41%   |
| 34     | 2        | 7.41%   |
| 72     | 1        | 3.7%    |
| 60     | 1        | 3.7%    |
| 32     | 1        | 3.7%    |
| 31     | 1        | 3.7%    |
| 26     | 1        | 3.7%    |
| 22     | 1        | 3.7%    |
| 19     | 1        | 3.7%    |
| 18     | 1        | 3.7%    |
| 17     | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 36%     |
| 401-500     | 7        | 28%     |
| 701-800     | 3        | 12%     |
| 801-900     | 2        | 8%      |
| 601-700     | 1        | 4%      |
| 351-400     | 1        | 4%      |
| 1501-2000   | 1        | 4%      |
| 1001-1500   | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 19       | 76%     |
| 16/10 | 4        | 16%     |
| 21/9  | 2        | 8%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 38.46%  |
| 351-500        | 4        | 15.38%  |
| 301-350        | 4        | 15.38%  |
| More than 1000 | 2        | 7.69%   |
| 501-1000       | 2        | 7.69%   |
| 251-300        | 1        | 3.85%   |
| 151-200        | 1        | 3.85%   |
| 141-150        | 1        | 3.85%   |
| 131-140        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 64%     |
| 101-120 | 8        | 32%     |
| 1-50    | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 88%     |
| 2     | 3        | 12%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 20       | 47.62%  |
| Intel                           | 12       | 28.57%  |
| Qualcomm Atheros                | 2        | 4.76%   |
| TP-Link                         | 1        | 2.38%   |
| Samsung Electronics             | 1        | 2.38%   |
| Ralink Technology               | 1        | 2.38%   |
| Qualcomm Atheros Communications | 1        | 2.38%   |
| OPPO Electronics                | 1        | 2.38%   |
| Motorola PCS                    | 1        | 2.38%   |
| Google                          | 1        | 2.38%   |
| Broadcom Limited                | 1        | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15       | 33.33%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4        | 8.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 4.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 4.44%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 4.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 2.22%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 2.22%   |
| Ralink RT2770 Wireless Adapter                                         | 1        | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 2.22%   |
| OPPO Ace 3V                                                            | 1        | 2.22%   |
| Motorola PCS moto g100 pro                                             | 1        | 2.22%   |
| Intel Wireless 8260                                                    | 1        | 2.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 2.22%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.22%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 2.22%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 2.22%   |
| Google Nexus/Pixel Device (tether)                                     | 1        | 2.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 50%     |
| Realtek Semiconductor           | 4        | 25%     |
| TP-Link                         | 1        | 6.25%   |
| Ralink Technology               | 1        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| Broadcom Limited                | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4        | 25%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 18.75%  |
| Intel Wi-Fi 6 AX200                                                  | 2        | 12.5%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 6.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 6.25%   |
| Ralink RT2770 Wireless Adapter                                       | 1        | 6.25%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 6.25%   |
| Intel Wireless 8260                                                  | 1        | 6.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 6.25%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 65.52%  |
| Intel                 | 4        | 13.79%  |
| Qualcomm Atheros      | 2        | 6.9%    |
| Samsung Electronics   | 1        | 3.45%   |
| OPPO Electronics      | 1        | 3.45%   |
| Motorola PCS          | 1        | 3.45%   |
| Google                | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15       | 51.72%  |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 6.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 6.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 6.9%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 3.45%   |
| OPPO Ace 3V                                                            | 1        | 3.45%   |
| Motorola PCS moto g100 pro                                             | 1        | 3.45%   |
| Intel Ethernet Controller I225-V                                       | 1        | 3.45%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 3.45%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 3.45%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 3.45%   |
| Google Nexus/Pixel Device (tether)                                     | 1        | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 60.98%  |
| WiFi     | 16       | 39.02%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 73.91%  |
| WiFi     | 6        | 26.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 13       | 52%     |
| 1     | 12       | 48%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 68%     |
| Yes  | 8        | 32%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 50%     |
| Realtek Semiconductor   | 3        | 21.43%  |
| Cambridge Silicon Radio | 1        | 7.14%   |
| Broadcom                | 1        | 7.14%   |
| ASUSTek Computer        | 1        | 7.14%   |
| Apple                   | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 28.57%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 14.29%  |
| Realtek Bluetooth Radio                             | 1        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.14%   |
| Intel Bluetooth wireless interface                  | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 7.14%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.14%   |
| Apple Bluetooth USB Host Controller                 | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 16       | 36.36%  |
| Nvidia              | 13       | 29.55%  |
| AMD                 | 11       | 25%     |
| C-Media Electronics | 2        | 4.55%   |
| Guillemot           | 1        | 2.27%   |
| Creative Labs       | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 12.24%  |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 8.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 4.08%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 4.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 4.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.04%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.04%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.04%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 2.04%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 2.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 2.04%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.04%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.04%   |
| Guillemot Hercules DJ Console 4-Mx                                         | 1        | 2.04%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 2.04%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 2.04%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.04%   |
| AMD Ryzen HD Audio Controller                                              | 1        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.04%   |
| AMD Navi 48 HDMI/DP Audio Controller                                       | 1        | 2.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Crucial | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 100%    |

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


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Logitech  | 2        | 50%     |
| webcam    | 1        | 25%     |
| Microsoft | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| webcam webcam               | 1        | 25%     |
| Microsoft LifeCam Cinema    | 1        | 25%     |
| Logitech Webcam C170        | 1        | 25%     |
| Logitech HD Pro Webcam C920 | 1        | 25%     |

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
| 0     | 11       | 42.31%  |
| 1     | 10       | 38.46%  |
| 2     | 4        | 15.38%  |
| 3     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 12       | 57.14%  |
| Net/wireless             | 4        | 19.05%  |
| Unassigned class         | 1        | 4.76%   |
| Net/ethernet             | 1        | 4.76%   |
| Graphics card            | 1        | 4.76%   |
| Firewire controller      | 1        | 4.76%   |
| Bluetooth                | 1        | 4.76%   |

