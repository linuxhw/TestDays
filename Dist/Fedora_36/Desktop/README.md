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

Total: 26

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.17.1-300.fc36.x86_64                                        | 2        | 15.38%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 2        | 15.38%  |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2        | 15.38%  |
| 5.17.0-300.fc36.x86_64                                        | 1        | 7.69%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 1        | 7.69%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1        | 7.69%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1        | 7.69%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1        | 7.69%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1        | 7.69%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1        | 7.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.0  | 5        | 41.67%  |
| 5.15.0  | 3        | 25%     |
| 5.17.1  | 2        | 16.67%  |
| 5.14.0  | 2        | 16.67%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 7        | 58.33%  |
| 5.15    | 3        | 25%     |
| 5.14    | 2        | 16.67%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 11       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 9        | 81.82%  |
| KDE5    | 1        | 9.09%   |
| Unknown | 1        | 9.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 8        | 72.73%  |
| X11     | 2        | 18.18%  |
| Tty     | 1        | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 5        | 45.45%  |
| Unknown | 5        | 45.45%  |
| SDDM    | 1        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 4        | 36.36%  |
| ru_RU | 2        | 18.18%  |
| en_GB | 2        | 18.18%  |
| pt_BR | 1        | 9.09%   |
| es_AR | 1        | 9.09%   |
| de_DE | 1        | 9.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 6        | 54.55%  |
| BIOS | 5        | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 8        | 72.73%  |
| Ext4  | 2        | 18.18%  |
| Xfs   | 1        | 9.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 5        | 45.45%  |
| Unknown | 4        | 36.36%  |
| MBR     | 2        | 18.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 54.55%  |
| Yes       | 5        | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 4        | 36.36%  |
| MSI                 | 3        | 27.27%  |
| Hewlett-Packard     | 1        | 9.09%   |
| Dell                | 1        | 9.09%   |
| Biostar             | 1        | 9.09%   |
| ASUSTek Computer    | 1        | 9.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI MS-7D06                 | 1        | 9.09%   |
| MSI MS-7C95                 | 1        | 9.09%   |
| MSI MS-7721                 | 1        | 9.09%   |
| HP Compaq 8100 Elite SFF PC | 1        | 9.09%   |
| Gigabyte H370M-DS3H         | 1        | 9.09%   |
| Gigabyte EP45-DS3L          | 1        | 9.09%   |
| Gigabyte B85M-D3V-A         | 1        | 9.09%   |
| Gigabyte B550 AORUS ELITE   | 1        | 9.09%   |
| Dell OptiPlex 9020          | 1        | 9.09%   |
| Biostar H55 HD              | 1        | 9.09%   |
| ASUS TUF GAMING B550M-PLUS  | 1        | 9.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7D06         | 1        | 9.09%   |
| MSI MS-7C95         | 1        | 9.09%   |
| MSI MS-7721         | 1        | 9.09%   |
| HP Compaq           | 1        | 9.09%   |
| Gigabyte H370M-DS3H | 1        | 9.09%   |
| Gigabyte EP45-DS3L  | 1        | 9.09%   |
| Gigabyte B85M-D3V-A | 1        | 9.09%   |
| Gigabyte B550       | 1        | 9.09%   |
| Dell OptiPlex       | 1        | 9.09%   |
| Biostar H55         | 1        | 9.09%   |
| ASUS TUF            | 1        | 9.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 27.27%  |
| 2015 | 2        | 18.18%  |
| 2021 | 1        | 9.09%   |
| 2018 | 1        | 9.09%   |
| 2013 | 1        | 9.09%   |
| 2010 | 1        | 9.09%   |
| 2009 | 1        | 9.09%   |
| 2008 | 1        | 9.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 3        | 27.27%  |
| 16.01-24.0  | 3        | 27.27%  |
| 4.01-8.0    | 2        | 18.18%  |
| 32.01-64.0  | 1        | 9.09%   |
| 64.01-256.0 | 1        | 9.09%   |
| 8.01-16.0   | 1        | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 4        | 36.36%  |
| 1.01-2.0  | 3        | 27.27%  |
| 2.01-3.0  | 2        | 18.18%  |
| 8.01-16.0 | 1        | 9.09%   |
| 0.51-1.0  | 1        | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 45.45%  |
| 2      | 4        | 36.36%  |
| 4      | 1        | 9.09%   |
| 3      | 1        | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 63.64%  |
| Yes       | 4        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 54.55%  |
| No        | 5        | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 63.64%  |
| Yes       | 4        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Belarus     | 2        | 18.18%  |
| USA         | 1        | 9.09%   |
| UK          | 1        | 9.09%   |
| Switzerland | 1        | 9.09%   |
| Netherlands | 1        | 9.09%   |
| Indonesia   | 1        | 9.09%   |
| Germany     | 1        | 9.09%   |
| Brazil      | 1        | 9.09%   |
| Bangladesh  | 1        | 9.09%   |
| Argentina   | 1        | 9.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Minsk        | 2        | 18.18%  |
| Zurich       | 1        | 9.09%   |
| Jakarta      | 1        | 9.09%   |
| Houston      | 1        | 9.09%   |
| Halstead     | 1        | 9.09%   |
| Goiânia     | 1        | 9.09%   |
| Dhaka        | 1        | 9.09%   |
| Delft        | 1        | 9.09%   |
| Buenos Aires | 1        | 9.09%   |
| Bonn         | 1        | 9.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 33.33%  |
| WDC                 | 4        | 6      | 22.22%  |
| Kingston            | 3        | 3      | 16.67%  |
| Toshiba             | 2        | 2      | 11.11%  |
| XPG                 | 1        | 1      | 5.56%   |
| Seagate             | 1        | 1      | 5.56%   |
| Phison              | 1        | 1      | 5.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB    | 2        | 10%     |
| Kingston SA400S37120G 120GB SSD | 2        | 10%     |
| XPG GAMMIX S11 Pro 256GB        | 1        | 5%      |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 5%      |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 5%      |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 5%      |
| WDC WD20EZRX-00D8PB0 2TB        | 1        | 5%      |
| WDC WD20EARS-00MVWB0 2TB        | 1        | 5%      |
| WDC WD10EZEX-00ZF5A0 1TB        | 1        | 5%      |
| Toshiba THNSNJ128GCSU 128GB SSD | 1        | 5%      |
| Toshiba HDWD120 2TB             | 1        | 5%      |
| Seagate ST3500413AS 500GB       | 1        | 5%      |
| Samsung SSD 970 EVO 250GB       | 1        | 5%      |
| Samsung SSD 870 QVO 2TB         | 1        | 5%      |
| Samsung SSD 860 EVO 250GB       | 1        | 5%      |
| Samsung NVMe SSD Drive 2TB      | 1        | 5%      |
| Phison NVMe SSD Drive 512GB     | 1        | 5%      |
| Kingston SA400S37240G 240GB SSD | 1        | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 6      | 66.67%  |
| Toshiba | 1        | 1      | 16.67%  |
| Seagate | 1        | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 3        | 3      | 50%     |
| Samsung Electronics | 2        | 4      | 33.33%  |
| Toshiba             | 1        | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 8      | 37.5%   |
| HDD  | 6        | 8      | 37.5%   |
| NVMe | 4        | 6      | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 8        | 16     | 66.67%  |
| NVMe | 4        | 6      | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 6        | 9      | 54.55%  |
| 1.01-2.0   | 3        | 5      | 27.27%  |
| 0.51-1.0   | 2        | 2      | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 4        | 36.36%  |
| 501-1000   | 3        | 27.27%  |
| 251-500    | 2        | 18.18%  |
| 1001-2000  | 1        | 9.09%   |
| Unknown    | 1        | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 3        | 27.27%  |
| 101-250   | 3        | 27.27%  |
| 1-20      | 2        | 18.18%  |
| 251-500   | 1        | 9.09%   |
| 1001-2000 | 1        | 9.09%   |
| Unknown   | 1        | 9.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EZRX-00D8PB0 2TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Works    | 7        | 15     | 58.33%  |
| Detected | 4        | 6      | 33.33%  |
| Malfunc  | 1        | 1      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 7        | 35%     |
| Samsung Electronics | 4        | 20%     |
| AMD                 | 4        | 20%     |
| VIA Technologies    | 1        | 5%      |
| Phison Electronics  | 1        | 5%      |
| JMicron Technology  | 1        | 5%      |
| ASMedia Technology  | 1        | 5%      |
| ADATA Technology    | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD 500 Series Chipset SATA Controller                                         | 3        | 12.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 8.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 8.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 8.33%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 8.33%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 4.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 4.17%   |
| Phison E12 NVMe Controller                                                     | 1        | 4.17%   |
| JMicron JMB368 IDE controller                                                  | 1        | 4.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 4.17%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 4.17%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 4.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 4.17%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 4.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 4.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 8        | 53.33%  |
| NVMe | 4        | 26.67%  |
| IDE  | 3        | 20%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 63.64%  |
| AMD    | 4        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 18.18%  |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1        | 9.09%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1        | 9.09%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 9.09%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 1        | 9.09%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1        | 9.09%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 9.09%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 1        | 9.09%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1        | 9.09%   |
| AMD A8-5500 APU with Radeon HD Graphics | 1        | 9.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 3        | 27.27%  |
| AMD Ryzen 5      | 2        | 18.18%  |
| Other            | 1        | 9.09%   |
| Intel Core i7    | 1        | 9.09%   |
| Intel Core i3    | 1        | 9.09%   |
| Intel Core 2 Duo | 1        | 9.09%   |
| AMD Ryzen 7      | 1        | 9.09%   |
| AMD A8           | 1        | 9.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 45.45%  |
| 6      | 3        | 27.27%  |
| 8      | 2        | 18.18%  |
| 4      | 1        | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 81.82%  |
| 1      | 2        | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 2        | 18.18%  |
| 0x08701021 | 2        | 18.18%  |
| 0xa0671    | 1        | 9.09%   |
| 0x906ea    | 1        | 9.09%   |
| 0x20655    | 1        | 9.09%   |
| 0x20652    | 1        | 9.09%   |
| 0x1067a    | 1        | 9.09%   |
| 0x0800820d | 1        | 9.09%   |
| 0x06001119 | 1        | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Zen 2      | 2        | 18.18%  |
| Westmere   | 2        | 18.18%  |
| Haswell    | 2        | 18.18%  |
| Zen+       | 1        | 9.09%   |
| Piledriver | 1        | 9.09%   |
| Penryn     | 1        | 9.09%   |
| KabyLake   | 1        | 9.09%   |
| Icelake    | 1        | 9.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 5        | 41.67%  |
| Nvidia | 4        | 33.33%  |
| AMD    | 3        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Core Processor Integrated Graphics Controller                         | 2        | 16.67%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 16.67%  |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 8.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 8.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 8.33%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 8.33%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 8.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 8.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 8.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 4        | 36.36%  |
| 1 x Nvidia     | 3        | 27.27%  |
| 1 x AMD        | 3        | 27.27%  |
| Intel + Nvidia | 1        | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 81.82%  |
| Proprietary | 2        | 18.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 45.45%  |
| 3.01-4.0   | 3        | 27.27%  |
| 7.01-8.0   | 1        | 9.09%   |
| 1.01-2.0   | 1        | 9.09%   |
| 0.51-1.0   | 1        | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 3        | 30%     |
| AOC                  | 3        | 30%     |
| Samsung Electronics  | 1        | 10%     |
| Philips              | 1        | 10%     |
| Hewlett-Packard      | 1        | 10%     |
| Ancor Communications | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch | 1        | 10%     |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1        | 10%     |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch           | 1        | 10%     |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                 | 1        | 10%     |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch             | 1        | 10%     |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                | 1        | 10%     |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                     | 1        | 10%     |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                      | 1        | 10%     |
| AOC 2043 AOC2043 1600x900 443x249mm 20.0-inch                        | 1        | 10%     |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 1        | 10%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 60%     |
| 3840x1600          | 1        | 10%     |
| 2560x1440 (QHD)    | 1        | 10%     |
| 1680x1050 (WSXGA+) | 1        | 10%     |
| 1600x900 (HD+)     | 1        | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 2        | 20%     |
| 24     | 2        | 20%     |
| 23     | 2        | 20%     |
| 21     | 2        | 20%     |
| 37     | 1        | 10%     |
| 20     | 1        | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 50%     |
| 401-500     | 4        | 40%     |
| 801-900     | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 7        | 77.78%  |
| 3/2   | 1        | 11.11%  |
| 21/9  | 1        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4        | 44.44%  |
| 301-350        | 2        | 22.22%  |
| 151-200        | 2        | 22.22%  |
| 351-500        | 1        | 11.11%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 70%     |
| 101-120 | 2        | 20%     |
| 121-160 | 1        | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 81.82%  |
| 2     | 1        | 9.09%   |
| 0     | 1        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 38.89%  |
| Intel                 | 6        | 33.33%  |
| Ralink Technology     | 1        | 5.56%   |
| Microsoft             | 1        | 5.56%   |
| MicroPython           | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |
| Belkin Components     | 1        | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 5        | 26.32%  |
| Realtek RTL8125 2.5GbE Controller                                  | 2        | 10.53%  |
| Ralink MT7601U Wireless Adapter                                    | 1        | 5.26%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1        | 5.26%   |
| MicroPython Board in FS mode                                       | 1        | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 5.26%   |
| Intel Wi-Fi 6 AX200                                                | 1        | 5.26%   |
| Intel Ethernet Controller I225-V                                   | 1        | 5.26%   |
| Intel Ethernet Connection I217-LM                                  | 1        | 5.26%   |
| Intel Ethernet Connection (7) I219-V                               | 1        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 5.26%   |
| Intel 82578DM Gigabit Network Connection                           | 1        | 5.26%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 5.26%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 5.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 3        | 42.86%  |
| Ralink Technology | 1        | 14.29%  |
| Microsoft         | 1        | 14.29%  |
| Broadcom          | 1        | 14.29%  |
| Belkin Components | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                    | 1        | 14.29%  |
| Microsoft Xbox 360 Wireless Adapter                                | 1        | 14.29%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                                | 1        | 14.29%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1        | 14.29%  |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1        | 14.29%  |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 63.64%  |
| Intel                 | 4        | 36.36%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 45.45%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 18.18%  |
| Intel Ethernet Controller I225-V                                  | 1        | 9.09%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 9.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 9.09%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 61.11%  |
| WiFi     | 6        | 33.33%  |
| Modem    | 1        | 5.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 71.43%  |
| WiFi     | 4        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 63.64%  |
| 2     | 4        | 36.36%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| Yes  | 6        | 54.55%  |
| No   | 5        | 45.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 75%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 25%     |
| Intel AX210 Bluetooth                               | 1        | 25%     |
| Intel AX200 Bluetooth                               | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 7        | 43.75%  |
| Nvidia                   | 4        | 25%     |
| AMD                      | 4        | 25%     |
| Micro Star International | 1        | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 10%     |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2        | 10%     |
| AMD Starship/Matisse HD Audio Controller                            | 2        | 10%     |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2        | 10%     |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 5%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1        | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1        | 5%      |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 5%      |
| Micro Star International USB Audio                                  | 1        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1        | 5%      |
| Intel Tiger Lake-H HD Audio Controller                              | 1        | 5%      |
| Intel Cannon Lake PCH cAVS                                          | 1        | 5%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 5%      |
| AMD FCH Azalia Controller                                           | 1        | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 5%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1        | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 2        | 22.22%  |
| Micron Technology | 2        | 22.22%  |
| Crucial           | 2        | 22.22%  |
| V-GeN             | 1        | 11.11%  |
| Mushkin           | 1        | 11.11%  |
| GOODRAM           | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s         | 1        | 11.11%  |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 1        | 11.11%  |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s          | 1        | 11.11%  |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s | 1        | 11.11%  |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s   | 1        | 11.11%  |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s   | 1        | 11.11%  |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s  | 1        | 11.11%  |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s | 1        | 11.11%  |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 57.14%  |
| DDR4    | 2        | 28.57%  |
| Unknown | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 3        | 42.86%  |
| 4096 | 2        | 28.57%  |
| 2048 | 2        | 28.57%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 37.5%   |
| 1333  | 2        | 25%     |
| 3200  | 1        | 12.5%   |
| 2133  | 1        | 12.5%   |
| 800   | 1        | 12.5%   |

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
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 200 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 50%     |
| Logitech  | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microsoft LifeCam Cinema             | 1        | 50%     |
| Logitech QuickCam Communicate Deluxe | 1        | 50%     |

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
| 0     | 8        | 72.73%  |
| 1     | 2        | 18.18%  |
| 2     | 1        | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 1        | 50%     |
| Graphics card | 1        | 50%     |

