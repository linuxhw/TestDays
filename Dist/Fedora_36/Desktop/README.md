Fedora 36 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 31

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | B150M-K                     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Gigabyte | B550I AORUS PRO AX          | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| Gigabyte | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Dell     | 088DT1 A01                  | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Gigabyte | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI      | MPG Z590 GAMING CARBON W... | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Gigabyte | H370M DS3H-CF               | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Gigabyte | EP45-DS3L                   | [7879818528](https://linux-hardware.org/?probe=7879818528) | Mar 30, 2022 |
| Gigabyte | EP45-DS3L                   | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte | B85M-D3V-A                  | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Gigabyte | EP45-DS3L                   | [efdb29ff92](https://linux-hardware.org/?probe=efdb29ff92) | Mar 07, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte | EP45-DS3L                   | [0efde9a187](https://linux-hardware.org/?probe=0efde9a187) | Mar 03, 2022 |
| Gigabyte | EP45-DS3L                   | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Biostar  | H55 HD                      | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar  | H55 HD                      | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| MSI      | B550M PRO-VDH WIFI          | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell     | 0KC9NP A01                  | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Dell     | 0KC9NP A01                  | [a072a33607](https://linux-hardware.org/?probe=a072a33607) | Oct 12, 2021 |
| MSI      | FM2-A55M-E33                | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI      | FM2-A55M-E33                | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Dell     | 0KC9NP A01                  | [95229554a9](https://linux-hardware.org/?probe=95229554a9) | Sep 19, 2021 |
| Dell     | 0KC9NP A01                  | [d235dcf0d1](https://linux-hardware.org/?probe=d235dcf0d1) | Sep 18, 2021 |
| Dell     | 0KC9NP A01                  | [ad5f2b8ea5](https://linux-hardware.org/?probe=ad5f2b8ea5) | Sep 04, 2021 |
| Dell     | 0KC9NP A01                  | [f191342fa8](https://linux-hardware.org/?probe=f191342fa8) | Sep 02, 2021 |
| Dell     | 0KC9NP A01                  | [270961aa02](https://linux-hardware.org/?probe=270961aa02) | Aug 30, 2021 |
| Dell     | 0KC9NP A01                  | [1257d6c6f4](https://linux-hardware.org/?probe=1257d6c6f4) | Aug 27, 2021 |
| Dell     | 0KC9NP A01                  | [373f7e6861](https://linux-hardware.org/?probe=373f7e6861) | Aug 22, 2021 |
| HP       | 304Ah                       | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell     | 0KC9NP A01                  | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 6        | 33.33%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 2        | 11.11%  |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2        | 11.11%  |
| 5.17.0-300.fc36.x86_64                                        | 1        | 5.56%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 1        | 5.56%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1        | 5.56%   |
| 5.16.17-200.fc35.x86_64                                       | 1        | 5.56%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1        | 5.56%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1        | 5.56%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1        | 5.56%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 6        | 35.29%  |
| 5.17.0  | 5        | 29.41%  |
| 5.15.0  | 3        | 17.65%  |
| 5.14.0  | 2        | 11.76%  |
| 5.16.17 | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 11       | 64.71%  |
| 5.15    | 3        | 17.65%  |
| 5.14    | 2        | 11.76%  |
| 5.16    | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 13       | 81.25%  |
| KDE5    | 2        | 12.5%   |
| Unknown | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 12       | 75%     |
| X11     | 3        | 18.75%  |
| Tty     | 1        | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 8        | 50%     |
| Unknown | 6        | 37.5%   |
| SDDM    | 2        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 43.75%  |
| en_GB | 3        | 18.75%  |
| ru_RU | 2        | 12.5%   |
| pt_BR | 1        | 6.25%   |
| fi_FI | 1        | 6.25%   |
| es_AR | 1        | 6.25%   |
| de_DE | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 10       | 62.5%   |
| BIOS | 6        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 12       | 75%     |
| Ext4  | 3        | 18.75%  |
| Xfs   | 1        | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 9        | 56.25%  |
| Unknown | 5        | 31.25%  |
| MBR     | 2        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 7        | 43.75%  |
| MSI                 | 3        | 18.75%  |
| Dell                | 2        | 12.5%   |
| ASUSTek Computer    | 2        | 12.5%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Biostar             | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI MS-7D06                 | 1        | 6.25%   |
| MSI MS-7C95                 | 1        | 6.25%   |
| MSI MS-7721                 | 1        | 6.25%   |
| HP Compaq 8100 Elite SFF PC | 1        | 6.25%   |
| Gigabyte H81M-S2H           | 1        | 6.25%   |
| Gigabyte H370M-DS3H         | 1        | 6.25%   |
| Gigabyte EP45-DS3L          | 1        | 6.25%   |
| Gigabyte B85M-D3V-A         | 1        | 6.25%   |
| Gigabyte B550I AORUS PRO AX | 1        | 6.25%   |
| Gigabyte B550 AORUS ELITE   | 1        | 6.25%   |
| Gigabyte 970A-DS3P          | 1        | 6.25%   |
| Dell OptiPlex 9020          | 1        | 6.25%   |
| Dell Inspiron 3847          | 1        | 6.25%   |
| Biostar H55 HD              | 1        | 6.25%   |
| ASUS TUF GAMING B550M-PLUS  | 1        | 6.25%   |
| ASUS B150M-K                | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7D06         | 1        | 6.25%   |
| MSI MS-7C95         | 1        | 6.25%   |
| MSI MS-7721         | 1        | 6.25%   |
| HP Compaq           | 1        | 6.25%   |
| Gigabyte H81M-S2H   | 1        | 6.25%   |
| Gigabyte H370M-DS3H | 1        | 6.25%   |
| Gigabyte EP45-DS3L  | 1        | 6.25%   |
| Gigabyte B85M-D3V-A | 1        | 6.25%   |
| Gigabyte B550I      | 1        | 6.25%   |
| Gigabyte B550       | 1        | 6.25%   |
| Gigabyte 970A-DS3P  | 1        | 6.25%   |
| Dell OptiPlex       | 1        | 6.25%   |
| Dell Inspiron       | 1        | 6.25%   |
| Biostar H55         | 1        | 6.25%   |
| ASUS TUF            | 1        | 6.25%   |
| ASUS B150M-K        | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 25%     |
| 2013 | 3        | 18.75%  |
| 2018 | 2        | 12.5%   |
| 2015 | 2        | 12.5%   |
| 2021 | 1        | 6.25%   |
| 2014 | 1        | 6.25%   |
| 2010 | 1        | 6.25%   |
| 2009 | 1        | 6.25%   |
| 2008 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 4        | 25%     |
| 8.01-16.0   | 4        | 25%     |
| 4.01-8.0    | 3        | 18.75%  |
| 3.01-4.0    | 3        | 18.75%  |
| 32.01-64.0  | 1        | 6.25%   |
| 64.01-256.0 | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 6        | 37.5%   |
| 2.01-3.0  | 3        | 18.75%  |
| 1.01-2.0  | 3        | 18.75%  |
| 4.01-8.0  | 2        | 12.5%   |
| 8.01-16.0 | 1        | 6.25%   |
| 0.51-1.0  | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 31.25%  |
| 1      | 5        | 31.25%  |
| 4      | 3        | 18.75%  |
| 3      | 3        | 18.75%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 56.25%  |
| No        | 7        | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 2        | 12.5%   |
| Brazil      | 2        | 12.5%   |
| Belarus     | 2        | 12.5%   |
| UK          | 1        | 6.25%   |
| Switzerland | 1        | 6.25%   |
| Spain       | 1        | 6.25%   |
| Netherlands | 1        | 6.25%   |
| Indonesia   | 1        | 6.25%   |
| Germany     | 1        | 6.25%   |
| Finland     | 1        | 6.25%   |
| Belgium     | 1        | 6.25%   |
| Bangladesh  | 1        | 6.25%   |
| Argentina   | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Minsk        | 2        | 12.5%   |
| Zurich       | 1        | 6.25%   |
| Turku        | 1        | 6.25%   |
| Tarragona    | 1        | 6.25%   |
| Sao Paulo    | 1        | 6.25%   |
| Kanne        | 1        | 6.25%   |
| Jakarta      | 1        | 6.25%   |
| Houston      | 1        | 6.25%   |
| Halstead     | 1        | 6.25%   |
| Goiânia     | 1        | 6.25%   |
| Folsom       | 1        | 6.25%   |
| Dhaka        | 1        | 6.25%   |
| Delft        | 1        | 6.25%   |
| Buenos Aires | 1        | 6.25%   |
| Bonn         | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 14     | 31.03%  |
| WDC                 | 6        | 9      | 20.69%  |
| Kingston            | 6        | 6      | 20.69%  |
| Toshiba             | 3        | 3      | 10.34%  |
| Seagate             | 3        | 3      | 10.34%  |
| XPG                 | 1        | 1      | 3.45%   |
| Phison              | 1        | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD        | 3        | 8.82%   |
| Samsung SSD 970 EVO 250GB              | 2        | 5.88%   |
| Samsung SSD 870 QVO 2TB                | 2        | 5.88%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2        | 5.88%   |
| Kingston SA400S37120G 120GB SSD        | 2        | 5.88%   |
| XPG GAMMIX S11 Pro 256GB               | 1        | 2.94%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1        | 2.94%   |
| WDC WD6400AAKS-22A7B2 640GB            | 1        | 2.94%   |
| WDC WD5000AAKX-001CA0 500GB            | 1        | 2.94%   |
| WDC WD40EZRZ-00WN9B0 4TB               | 1        | 2.94%   |
| WDC WD30EZRX-00SPEB0 3TB               | 1        | 2.94%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 1        | 2.94%   |
| WDC WD20EZRX-00D8PB0 2TB               | 1        | 2.94%   |
| WDC WD20EARS-00MVWB0 2TB               | 1        | 2.94%   |
| WDC WD10EZEX-00ZF5A0 1TB               | 1        | 2.94%   |
| Toshiba THNSNJ128GCSU 128GB SSD        | 1        | 2.94%   |
| Toshiba MQ01ABD050 500GB               | 1        | 2.94%   |
| Toshiba HDWD120 2TB                    | 1        | 2.94%   |
| Seagate ST3500413AS 500GB              | 1        | 2.94%   |
| Seagate ST2000DM009-2G4100 2TB         | 1        | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB         | 1        | 2.94%   |
| Samsung SSD 970 EVO Plus 500GB         | 1        | 2.94%   |
| Samsung SSD 860 EVO 500GB              | 1        | 2.94%   |
| Samsung SSD 860 EVO 250GB              | 1        | 2.94%   |
| Samsung SSD 850 EVO 250GB              | 1        | 2.94%   |
| Samsung NVMe SSD Drive 2TB             | 1        | 2.94%   |
| Phison NVMe SSD Drive 512GB            | 1        | 2.94%   |
| Kingston SA400S37480G 480GB SSD        | 1        | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 8      | 54.55%  |
| Seagate | 3        | 3      | 27.27%  |
| Toshiba | 2        | 2      | 18.18%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 46.15%  |
| Samsung Electronics | 5        | 8      | 38.46%  |
| WDC                 | 1        | 1      | 7.69%   |
| Toshiba             | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 11       | 16     | 42.31%  |
| HDD  | 10       | 13     | 38.46%  |
| NVMe | 5        | 8      | 19.23%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 29     | 72.22%  |
| NVMe | 5        | 8      | 27.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 17     | 50%     |
| 1.01-2.0   | 5        | 7      | 25%     |
| 0.51-1.0   | 3        | 3      | 15%     |
| 3.01-4.0   | 1        | 1      | 5%      |
| 2.01-3.0   | 1        | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 4        | 25%     |
| 501-1000       | 4        | 25%     |
| 251-500        | 3        | 18.75%  |
| More than 3000 | 2        | 12.5%   |
| 1001-2000      | 2        | 12.5%   |
| Unknown        | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 4        | 25%     |
| 21-50          | 3        | 18.75%  |
| 1-20           | 3        | 18.75%  |
| 501-1000       | 2        | 12.5%   |
| More than 3000 | 1        | 6.25%   |
| 251-500        | 1        | 6.25%   |
| 1001-2000      | 1        | 6.25%   |
| Unknown        | 1        | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB | 1        | 1      | 50%     |
| WDC WD20EZRX-00D8PB0 2TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Works    | 11       | 26     | 61.11%  |
| Detected | 5        | 9      | 27.78%  |
| Malfunc  | 2        | 2      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 10       | 38.46%  |
| AMD                 | 6        | 23.08%  |
| Samsung Electronics | 5        | 19.23%  |
| VIA Technologies    | 1        | 3.85%   |
| Phison Electronics  | 1        | 3.85%   |
| JMicron Technology  | 1        | 3.85%   |
| ASMedia Technology  | 1        | 3.85%   |
| ADATA Technology    | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 13.33%  |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 10%     |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 6.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 6.67%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 3.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 3.33%   |
| Phison E12 NVMe Controller                                                     | 1        | 3.33%   |
| JMicron JMB368 IDE controller                                                  | 1        | 3.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.33%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 3.33%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 3.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 3.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 61.9%   |
| NVMe | 5        | 23.81%  |
| IDE  | 3        | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 62.5%   |
| AMD    | 6        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz        | 2        | 12.5%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 12.5%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 6.25%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 1        | 6.25%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1        | 6.25%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 6.25%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 1        | 6.25%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1        | 6.25%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 1        | 6.25%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 6.25%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 1        | 6.25%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1        | 6.25%   |
| AMD Phenom II X4 B25 Processor          | 1        | 6.25%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 6        | 37.5%   |
| AMD Ryzen 7      | 2        | 12.5%   |
| AMD Ryzen 5      | 2        | 12.5%   |
| Other            | 1        | 6.25%   |
| Intel Core i7    | 1        | 6.25%   |
| Intel Core i3    | 1        | 6.25%   |
| Intel Core 2 Duo | 1        | 6.25%   |
| AMD Phenom II X4 | 1        | 6.25%   |
| AMD A8           | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 5        | 31.25%  |
| 2      | 5        | 31.25%  |
| 8      | 3        | 18.75%  |
| 6      | 3        | 18.75%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 62.5%   |
| 1      | 6        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 4        | 25%     |
| 0x08701021 | 2        | 12.5%   |
| 0xa0671    | 1        | 6.25%   |
| 0x906ea    | 1        | 6.25%   |
| 0x506e3    | 1        | 6.25%   |
| 0x20655    | 1        | 6.25%   |
| 0x20652    | 1        | 6.25%   |
| 0x1067a    | 1        | 6.25%   |
| 0x0800820d | 1        | 6.25%   |
| 0x06001119 | 1        | 6.25%   |
| 0x010000c6 | 1        | 6.25%   |
| Unknown    | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Haswell    | 4        | 25%     |
| Zen 2      | 2        | 12.5%   |
| Westmere   | 2        | 12.5%   |
| Zen+       | 1        | 6.25%   |
| Zen 3      | 1        | 6.25%   |
| Skylake    | 1        | 6.25%   |
| Piledriver | 1        | 6.25%   |
| Penryn     | 1        | 6.25%   |
| KabyLake   | 1        | 6.25%   |
| K10        | 1        | 6.25%   |
| Icelake    | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 7        | 38.89%  |
| Intel  | 6        | 33.33%  |
| Nvidia | 5        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 22.22%  |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 11.11%  |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 5.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 5.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 5.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5.56%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 5.56%   |
| Intel HD Graphics 530                                                       | 1        | 5.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 5.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 5.56%   |
| AMD Cezanne                                                                 | 1        | 5.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 7        | 43.75%  |
| 1 x Nvidia     | 4        | 25%     |
| 1 x Intel      | 4        | 25%     |
| Intel + Nvidia | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 81.25%  |
| Proprietary | 3        | 18.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 37.5%   |
| 3.01-4.0   | 5        | 31.25%  |
| 7.01-8.0   | 2        | 12.5%   |
| 1.01-2.0   | 2        | 12.5%   |
| 0.51-1.0   | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 4        | 23.53%  |
| Goldstar             | 3        | 17.65%  |
| Ancor Communications | 3        | 17.65%  |
| Hewlett-Packard      | 2        | 11.76%  |
| Samsung Electronics  | 1        | 5.88%   |
| Philips              | 1        | 5.88%   |
| Lenovo               | 1        | 5.88%   |
| Gigabyte Technology  | 1        | 5.88%   |
| Dell                 | 1        | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1        | 5.88%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1        | 5.88%   |
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                   | 1        | 5.88%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch            | 1        | 5.88%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 1        | 5.88%   |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                  | 1        | 5.88%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch              | 1        | 5.88%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                 | 1        | 5.88%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 5.88%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 1        | 5.88%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                      | 1        | 5.88%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 1        | 5.88%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 5.88%   |
| AOC 2043 AOC2043 1600x900 443x249mm 20.0-inch                         | 1        | 5.88%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 1        | 5.88%   |
| Ancor Communications ASUS VP278 ACI27C8 1920x1080 598x336mm 27.0-inch | 1        | 5.88%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 1        | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 66.67%  |
| 2560x1440 (QHD)    | 2        | 13.33%  |
| 3840x1600          | 1        | 6.67%   |
| 1680x1050 (WSXGA+) | 1        | 6.67%   |
| 1600x900 (HD+)     | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 4        | 23.53%  |
| 23     | 4        | 23.53%  |
| 27     | 3        | 17.65%  |
| 21     | 3        | 17.65%  |
| 37     | 1        | 5.88%   |
| 31     | 1        | 5.88%   |
| 20     | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 56.25%  |
| 401-500     | 5        | 31.25%  |
| 801-900     | 1        | 6.25%   |
| 601-700     | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 78.57%  |
| 3/2   | 1        | 7.14%   |
| 21/9  | 1        | 7.14%   |
| 16/10 | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 46.67%  |
| 301-350        | 3        | 20%     |
| 351-500        | 2        | 13.33%  |
| 151-200        | 2        | 13.33%  |
| 251-300        | 1        | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 75%     |
| 101-120 | 3        | 18.75%  |
| 121-160 | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 75%     |
| 2     | 3        | 18.75%  |
| 0     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 44.44%  |
| Intel                 | 7        | 25.93%  |
| Microsoft             | 2        | 7.41%   |
| Ralink Technology     | 1        | 3.7%    |
| Qualcomm Atheros      | 1        | 3.7%    |
| MicroPython           | 1        | 3.7%    |
| MEDIATEK              | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |
| Belkin Components     | 1        | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 9        | 32.14%  |
| Realtek RTL8125 2.5GbE Controller                                  | 3        | 10.71%  |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                | 2        | 7.14%   |
| Ralink MT7601U Wireless Adapter                                    | 1        | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1        | 3.57%   |
| MicroPython Board in FS mode                                       | 1        | 3.57%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                   | 1        | 3.57%   |
| Intel Ethernet Connection I217-LM                                  | 1        | 3.57%   |
| Intel Ethernet Connection (7) I219-V                               | 1        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 3.57%   |
| Intel 82578DM Gigabit Network Connection                           | 1        | 3.57%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 3.57%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 4        | 36.36%  |
| Microsoft         | 2        | 18.18%  |
| Ralink Technology | 1        | 9.09%   |
| Qualcomm Atheros  | 1        | 9.09%   |
| MEDIATEK          | 1        | 9.09%   |
| Broadcom          | 1        | 9.09%   |
| Belkin Components | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 18.18%  |
| Intel Wi-Fi 6 AX200                                                | 2        | 18.18%  |
| Ralink MT7601U Wireless Adapter                                    | 1        | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1        | 9.09%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1        | 9.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 9.09%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 9.09%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 75%     |
| Intel                 | 4        | 25%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 56.25%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 18.75%  |
| Intel Ethernet Controller I225-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 6.25%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 6.25%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 61.54%  |
| WiFi     | 9        | 34.62%  |
| Modem    | 1        | 3.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 73.68%  |
| WiFi     | 5        | 26.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 56.25%  |
| 2     | 7        | 43.75%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 9        | 56.25%  |
| Yes  | 7        | 43.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 57.14%  |
| Qualcomm Atheros Communications | 1        | 14.29%  |
| MediaTek                        | 1        | 14.29%  |
| Cambridge Silicon Radio         | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 28.57%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 14.29%  |
| MediaTek Wireless_Device                            | 1        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 14.29%  |
| Intel AX210 Bluetooth                               | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 40%     |
| AMD                      | 8        | 32%     |
| Nvidia                   | 5        | 20%     |
| Micro Star International | 1        | 4%      |
| C-Media Electronics      | 1        | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4        | 13.33%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 4        | 13.33%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2        | 6.67%   |
| AMD Starship/Matisse HD Audio Controller                            | 2        | 6.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2        | 6.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1        | 3.33%   |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 3.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1        | 3.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1        | 3.33%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 3.33%   |
| Micro Star International USB Audio                                  | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1        | 3.33%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1        | 3.33%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 3.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1        | 3.33%   |
| C-Media Electronics MAXTER 7.1                                      | 1        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1        | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1        | 3.33%   |
| AMD FCH Azalia Controller                                           | 1        | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 2        | 14.29%  |
| Micron Technology   | 2        | 14.29%  |
| Kingston            | 2        | 14.29%  |
| Crucial             | 2        | 14.29%  |
| V-GeN               | 1        | 7.14%   |
| SK Hynix            | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Mushkin             | 1        | 7.14%   |
| GOODRAM             | 1        | 7.14%   |
| G.Skill             | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s            | 1        | 7.14%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 7.14%   |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s             | 1        | 7.14%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 7.14%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s      | 1        | 7.14%   |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s    | 1        | 7.14%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 7.14%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s      | 1        | 7.14%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 7.14%   |
| Kingston RAM 99U5471-034.A 4GB DIMM DDR3 667MT/s         | 1        | 7.14%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s     | 1        | 7.14%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s | 1        | 7.14%   |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s    | 1        | 7.14%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 54.55%  |
| DDR4    | 4        | 36.36%  |
| Unknown | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 11       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 5        | 41.67%  |
| 8192  | 4        | 33.33%  |
| 2048  | 2        | 16.67%  |
| 16384 | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 30.77%  |
| 2133  | 2        | 15.38%  |
| 1333  | 2        | 15.38%  |
| 3866  | 1        | 7.69%   |
| 3200  | 1        | 7.69%   |
| 2933  | 1        | 7.69%   |
| 800   | 1        | 7.69%   |
| 667   | 1        | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model           | Desktops | Percent |
|-----------------|----------|---------|
| Brother Printer | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 50%     |
| Canon CanoScan LiDE 200 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Microsoft                   | 1        | 33.33%  |
| Logitech                    | 1        | 33.33%  |
| KYE Systems (Mouse Systems) | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Microsoft LifeCam Cinema                         | 1        | 33.33%  |
| Logitech QuickCam Communicate Deluxe             | 1        | 33.33%  |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1        | 33.33%  |

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
| 0     | 12       | 75%     |
| 1     | 3        | 18.75%  |
| 2     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Net/wireless       | 1        | 33.33%  |
| Graphics card      | 1        | 33.33%  |
| Fingerprint reader | 1        | 33.33%  |

