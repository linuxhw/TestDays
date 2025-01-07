Makulu - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Makulu.

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

Total: 35

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Dell    | Latitude E6220              | [a795975b1e](https://linux-hardware.org/?probe=a795975b1e) | Apr 02, 2024 |
| Lenovo  | V14-IIL 82C4                | [459870519f](https://linux-hardware.org/?probe=459870519f) | Dec 09, 2023 |
| HP      | Laptop 17-ca2xxx            | [f6d894d339](https://linux-hardware.org/?probe=f6d894d339) | Aug 26, 2023 |
| Dell    | Latitude E5470              | [8033ce619e](https://linux-hardware.org/?probe=8033ce619e) | Aug 22, 2023 |
| Dell    | Latitude E5470              | [2fa90c8f06](https://linux-hardware.org/?probe=2fa90c8f06) | Aug 22, 2023 |
| Fujitsu | STYLISTIC Q665              | [438b08fb3d](https://linux-hardware.org/?probe=438b08fb3d) | Mar 06, 2023 |
| HUAWEI  | MateBook X                  | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI  | MateBook X                  | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| Fujitsu | STYLISTIC Q665              | [268703bd9e](https://linux-hardware.org/?probe=268703bd9e) | Feb 13, 2023 |
| Dell    | Latitude E64406342Q0286/    | [e044c94514](https://linux-hardware.org/?probe=e044c94514) | Dec 26, 2022 |
| Dell    | Latitude E64406342Q0286/    | [41b2b27a91](https://linux-hardware.org/?probe=41b2b27a91) | Dec 16, 2022 |
| Dell    | Latitude E64406342Q0286/    | [e8b2c9218f](https://linux-hardware.org/?probe=e8b2c9218f) | Dec 15, 2022 |
| Dell    | Inspiron 5565               | [a583bbdc35](https://linux-hardware.org/?probe=a583bbdc35) | May 19, 2022 |
| Dell    | Latitude 3540               | [6fb057646a](https://linux-hardware.org/?probe=6fb057646a) | Feb 25, 2022 |
| Samsung | R580                        | [b796f42cc3](https://linux-hardware.org/?probe=b796f42cc3) | Jan 31, 2022 |
| HP      | Pavilion Laptop 15z-cw10... | [c014435339](https://linux-hardware.org/?probe=c014435339) | Dec 29, 2021 |
| HP      | Pavilion Laptop 15z-cw10... | [97cfd9951b](https://linux-hardware.org/?probe=97cfd9951b) | Dec 29, 2021 |
| Lenovo  | V14-IIL 82C4                | [cb48d8f436](https://linux-hardware.org/?probe=cb48d8f436) | Dec 28, 2021 |
| HUAWEI  | KPL-W0X                     | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI  | KPL-W0X                     | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Lenovo  | V14-IIL 82C4                | [e3873f9847](https://linux-hardware.org/?probe=e3873f9847) | Dec 23, 2021 |
| ASUSTek | N55SL                       | [11ed4def95](https://linux-hardware.org/?probe=11ed4def95) | Oct 24, 2021 |
| Lenovo  | IdeaPad Y530                | [6ca5521110](https://linux-hardware.org/?probe=6ca5521110) | Sep 24, 2021 |
| Dell    | Inspiron 3521               | [9787940762](https://linux-hardware.org/?probe=9787940762) | Aug 29, 2021 |
| Apple   | MacBookAir6,2               | [66f7c33d00](https://linux-hardware.org/?probe=66f7c33d00) | Jun 08, 2021 |
| Apple   | MacBookAir6,2               | [1ce8c5e2c7](https://linux-hardware.org/?probe=1ce8c5e2c7) | Jun 03, 2021 |
| HP      | ENVY Notebook               | [61cb15af98](https://linux-hardware.org/?probe=61cb15af98) | Apr 28, 2021 |
| ASUSTek | K55VD                       | [b9086bf814](https://linux-hardware.org/?probe=b9086bf814) | Apr 14, 2021 |
| ASUSTek | K55VD                       | [10987a7dec](https://linux-hardware.org/?probe=10987a7dec) | Apr 13, 2021 |
| HP      | Compaq 15                   | [455bc50dc9](https://linux-hardware.org/?probe=455bc50dc9) | Mar 15, 2021 |
| HP      | ENVY Notebook               | [f71898211e](https://linux-hardware.org/?probe=f71898211e) | Feb 25, 2021 |
| Lenovo  | ThinkPad T420 4236W1W       | [3c3ff4f10e](https://linux-hardware.org/?probe=3c3ff4f10e) | Dec 02, 2020 |
| Lenovo  | ThinkPad T420 4236W1W       | [73279e52cd](https://linux-hardware.org/?probe=73279e52cd) | Oct 01, 2020 |
| HP      | Pavilion 17                 | [a6aa670ab4](https://linux-hardware.org/?probe=a6aa670ab4) | Sep 02, 2020 |
| HP      | Pavilion 17                 | [03171f4dbe](https://linux-hardware.org/?probe=03171f4dbe) | Aug 30, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Makulu 2020              | 10        | 43.48%  |
| Makulu Build: 2021.12.15 | 4         | 17.39%  |
| Makulu Buildvar          | 1         | 4.35%   |
| Makulu Build: 2022.01.06 | 1         | 4.35%   |
| Makulu Bld-2022.12.04    | 1         | 4.35%   |
| Makulu Bld-2022.11.03    | 1         | 4.35%   |
| Makulu Bld-2022.08.19    | 1         | 4.35%   |
| Makulu Beta1             | 1         | 4.35%   |
| Makulu Beta-1            | 1         | 4.35%   |
| Makulu 68                | 1         | 4.35%   |
| Makulu 2023.07.12        | 1         | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Makulu | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.11.0-41-generic      | 3         | 13.04%  |
| 5.15.0-53-generic      | 2         | 8.7%    |
| 5.11.0-43-generic      | 2         | 8.7%    |
| 5.10.0-8-amd64         | 2         | 8.7%    |
| 6.3.0-1-amd64          | 1         | 4.35%   |
| 6.1.6-060106-generic   | 1         | 4.35%   |
| 6.1.11-060111-generic  | 1         | 4.35%   |
| 5.8.0-55-generic       | 1         | 4.35%   |
| 5.8.0-49-generic       | 1         | 4.35%   |
| 5.8.0-44-generic       | 1         | 4.35%   |
| 5.8.0-38-generic       | 1         | 4.35%   |
| 5.4.0-48-generic       | 1         | 4.35%   |
| 5.4.0-42-generic       | 1         | 4.35%   |
| 5.15.10-051510-generic | 1         | 4.35%   |
| 5.15.0-91-generic      | 1         | 4.35%   |
| 5.15.0-79-generic      | 1         | 4.35%   |
| 5.15.0-46-generic      | 1         | 4.35%   |
| 5.11.0-36-generic      | 1         | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 6         | 26.09%  |
| 5.15.0  | 5         | 21.74%  |
| 5.8.0   | 4         | 17.39%  |
| 5.4.0   | 2         | 8.7%    |
| 5.10.0  | 2         | 8.7%    |
| 6.3.0   | 1         | 4.35%   |
| 6.1.6   | 1         | 4.35%   |
| 6.1.11  | 1         | 4.35%   |
| 5.15.10 | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 6         | 27.27%  |
| 5.11    | 6         | 27.27%  |
| 5.8     | 4         | 18.18%  |
| 5.4     | 2         | 9.09%   |
| 5.10    | 2         | 9.09%   |
| 6.3     | 1         | 4.55%   |
| 6.1     | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| GNOME       | 16        | 72.73%  |
| X-Cinnamon  | 5         | 22.73%  |
| MakuluGameR | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 22        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 81.82%  |
| LightDM | 4         | 18.18%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 9         | 39.13%  |
| en_CA | 4         | 17.39%  |
| de_DE | 3         | 13.04%  |
| it_IT | 2         | 8.7%    |
| en_GB | 2         | 8.7%    |
| pt_BR | 1         | 4.35%   |
| pl_PL | 1         | 4.35%   |
| nl_NL | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 13        | 56.52%  |
| EFI  | 10        | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 18        | 81.82%  |
| Tmpfs | 3         | 13.64%  |
| Btrfs | 1         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 86.36%  |
| GPT     | 2         | 9.09%   |
| MBR     | 1         | 4.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 95.45%  |
| Yes       | 1         | 4.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 6         | 27.27%  |
| Hewlett-Packard     | 5         | 22.73%  |
| Lenovo              | 4         | 18.18%  |
| HUAWEI              | 2         | 9.09%   |
| ASUSTek Computer    | 2         | 9.09%   |
| Samsung Electronics | 1         | 4.55%   |
| Fujitsu             | 1         | 4.55%   |
| Apple               | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo V14-IIL 82C4           | 2         | 9.09%   |
| Samsung R580                  | 1         | 4.55%   |
| Lenovo ThinkPad T420 4236W1W  | 1         | 4.55%   |
| Lenovo IdeaPad Y530           | 1         | 4.55%   |
| HUAWEI MateBook X             | 1         | 4.55%   |
| HUAWEI KPL-W0X                | 1         | 4.55%   |
| HP Pavilion Laptop 15z-cw100  | 1         | 4.55%   |
| HP Pavilion 17                | 1         | 4.55%   |
| HP Laptop 17-ca2xxx           | 1         | 4.55%   |
| HP ENVY Notebook              | 1         | 4.55%   |
| HP Compaq 15                  | 1         | 4.55%   |
| Fujitsu STYLISTIC Q665        | 1         | 4.55%   |
| Dell Latitude E64406342Q0286/ | 1         | 4.55%   |
| Dell Latitude E6220           | 1         | 4.55%   |
| Dell Latitude E5470           | 1         | 4.55%   |
| Dell Latitude 3540            | 1         | 4.55%   |
| Dell Inspiron 5565            | 1         | 4.55%   |
| Dell Inspiron 3521            | 1         | 4.55%   |
| ASUS N55SL                    | 1         | 4.55%   |
| ASUS K55VD                    | 1         | 4.55%   |
| Apple MacBookAir6,2           | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Latitude     | 4         | 18.18%  |
| Lenovo V14-IIL    | 2         | 9.09%   |
| HP Pavilion       | 2         | 9.09%   |
| Dell Inspiron     | 2         | 9.09%   |
| Samsung R580      | 1         | 4.55%   |
| Lenovo ThinkPad   | 1         | 4.55%   |
| Lenovo IdeaPad    | 1         | 4.55%   |
| HUAWEI MateBook   | 1         | 4.55%   |
| HUAWEI KPL-W0X    | 1         | 4.55%   |
| HP Laptop         | 1         | 4.55%   |
| HP ENVY           | 1         | 4.55%   |
| HP Compaq         | 1         | 4.55%   |
| Fujitsu STYLISTIC | 1         | 4.55%   |
| ASUS N55SL        | 1         | 4.55%   |
| ASUS K55VD        | 1         | 4.55%   |
| Apple MacBookAir6 | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 18.18%  |
| 2013 | 4         | 18.18%  |
| 2011 | 3         | 13.64%  |
| 2018 | 2         | 9.09%   |
| 2016 | 2         | 9.09%   |
| 2015 | 2         | 9.09%   |
| 2012 | 2         | 9.09%   |
| 2014 | 1         | 4.55%   |
| 2009 | 1         | 4.55%   |
| 2008 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 22        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 47.83%  |
| 3.01-4.0   | 6         | 26.09%  |
| 8.01-16.0  | 4         | 17.39%  |
| 16.01-24.0 | 2         | 8.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 33.33%  |
| 1.01-2.0 | 7         | 29.17%  |
| 3.01-4.0 | 5         | 20.83%  |
| 4.01-8.0 | 4         | 16.67%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 78.26%  |
| 2      | 3         | 13.04%  |
| 3      | 2         | 8.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 59.09%  |
| Yes       | 9         | 40.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 72.73%  |
| No        | 6         | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 81.82%  |
| No        | 4         | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 22.73%  |
| UK          | 3         | 13.64%  |
| Germany     | 3         | 13.64%  |
| Canada      | 3         | 13.64%  |
| Poland      | 2         | 9.09%   |
| Uganda      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| Italy       | 1         | 4.55%   |
| France      | 1         | 4.55%   |
| Brazil      | 1         | 4.55%   |
| Australia   | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Steinfeld            | 1         | 4%      |
| Saint John           | 1         | 4%      |
| Porto Alegre         | 1         | 4%      |
| Piotrkow Trybunalski | 1         | 4%      |
| Paris                | 1         | 4%      |
| Oschersleben         | 1         | 4%      |
| Northborough         | 1         | 4%      |
| New York             | 1         | 4%      |
| Munich               | 1         | 4%      |
| Millers Creek        | 1         | 4%      |
| Melbourne            | 1         | 4%      |
| Manchester           | 1         | 4%      |
| Lodz                 | 1         | 4%      |
| Knoxville            | 1         | 4%      |
| Kampala              | 1         | 4%      |
| Jamestown            | 1         | 4%      |
| Imperia              | 1         | 4%      |
| Hillegom             | 1         | 4%      |
| Glovertown           | 1         | 4%      |
| Freisbach            | 1         | 4%      |
| Etobicoke            | 1         | 4%      |
| Dover                | 1         | 4%      |
| Dallas               | 1         | 4%      |
| Brunswick West       | 1         | 4%      |
| Ballygowan           | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 17.24%  |
| Seagate             | 4         | 5      | 13.79%  |
| SanDisk             | 4         | 4      | 13.79%  |
| Toshiba             | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| Unknown             | 1         | 1      | 3.45%   |
| Transcend           | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| LITEON              | 1         | 2      | 3.45%   |
| Lite-On Technology  | 1         | 1      | 3.45%   |
| KIOXIA              | 1         | 1      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                | 2         | 6.67%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 6.67%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 3.33%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 3.33%   |
| Unknown SD/MMC/MS PRO 128GB           | 1         | 3.33%   |
| Transcend TS64GMSA230S 64GB SSD       | 1         | 3.33%   |
| Toshiba MQ01ABF050M 500GB             | 1         | 3.33%   |
| Seagate ST9320325AS 320GB             | 1         | 3.33%   |
| Seagate Expansion Desk 5TB            | 1         | 3.33%   |
| SanDisk SSD U110 128GB                | 1         | 3.33%   |
| SanDisk SSD PLUS 1000GB               | 1         | 3.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 3.33%   |
| SanDisk NVMe SSD Drive 512GB          | 1         | 3.33%   |
| Samsung NVMe SSD Drive 1TB            | 1         | 3.33%   |
| Samsung NVMe SSD Drive 1024GB         | 1         | 3.33%   |
| Samsung MZNLN256HCHP-00000 256GB SSD  | 1         | 3.33%   |
| Samsung MZALQ256HAJD-000L2 256GB      | 1         | 3.33%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD  | 1         | 3.33%   |
| Samsung HM500JI 500GB                 | 1         | 3.33%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 1         | 3.33%   |
| LITEON L8H-256V2G-HP 256GB SSD        | 1         | 3.33%   |
| Lite-On LITEON CB1-SD256 256GB        | 1         | 3.33%   |
| KIOXIA NVMe SSD Drive 256GB           | 1         | 3.33%   |
| JMicron Tech 250GB                    | 1         | 3.33%   |
| Hitachi HTS545025B9A300 250GB         | 1         | 3.33%   |
| HGST HTS721010A9E630 1TB              | 1         | 3.33%   |
| Crucial CT2000BX500SSD1 2TB           | 1         | 3.33%   |
| Apple SSD SM0256F 256GB               | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 30.77%  |
| Toshiba             | 3         | 3      | 23.08%  |
| WDC                 | 2         | 2      | 15.38%  |
| Unknown             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 30%     |
| Samsung Electronics | 2         | 4      | 20%     |
| Transcend           | 1         | 1      | 10%     |
| LITEONIT            | 1         | 1      | 10%     |
| LITEON              | 1         | 2      | 10%     |
| Crucial             | 1         | 1      | 10%     |
| Apple               | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 12        | 14     | 44.44%  |
| SSD     | 9         | 13     | 33.33%  |
| NVMe    | 5         | 6      | 18.52%  |
| Unknown | 1         | 1      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 25     | 73.08%  |
| NVMe | 5         | 6      | 19.23%  |
| SAS  | 2         | 3      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 20     | 66.67%  |
| 0.51-1.0   | 5         | 5      | 23.81%  |
| 1.01-2.0   | 1         | 1      | 4.76%   |
| 4.01-10.0  | 1         | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 39.13%  |
| 251-500        | 6         | 26.09%  |
| 501-1000       | 4         | 17.39%  |
| More than 3000 | 1         | 4.35%   |
| 21-50          | 1         | 4.35%   |
| 1-20           | 1         | 4.35%   |
| 51-100         | 1         | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 10        | 40%     |
| 1-20           | 8         | 32%     |
| 101-250        | 3         | 12%     |
| 251-500        | 2         | 8%      |
| More than 3000 | 1         | 4%      |
| 51-100         | 1         | 4%      |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 20        | 31     | 90.91%  |
| Works    | 2         | 3      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 14        | 56%     |
| AMD                 | 5         | 20%     |
| Samsung Electronics | 3         | 12%     |
| SanDisk             | 1         | 4%      |
| Lite-On Technology  | 1         | 4%      |
| KIOXIA              | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 20%     |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 8%      |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 4%      |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 4%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 4%      |
| Lite-On CB1-SD256, CB1-SD512 NVMe SSD                                          | 1         | 4%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 4%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 4%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 4%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 4%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 76%     |
| NVMe | 5         | 20%     |
| RAID | 1         | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 72.73%  |
| AMD    | 6         | 27.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 9.09%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 4.55%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                 | 1         | 4.55%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 4.55%   |
| Intel Core i7-4600M CPU @ 2.90GHz               | 1         | 4.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 4.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 4.55%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 4.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 4.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 4.55%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 4.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 4.55%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 4.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 4.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 4.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 4.55%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 1         | 4.55%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 1         | 4.55%   |
| AMD A4-5000 APU with Radeon HD Graphics         | 1         | 4.55%   |
| AMD A12-9700P RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 5         | 22.73%  |
| Intel Core i5           | 5         | 22.73%  |
| Intel Core i3           | 4         | 18.18%  |
| Intel Pentium Dual-Core | 1         | 4.55%   |
| Intel Core M            | 1         | 4.55%   |
| AMD Ryzen 7             | 1         | 4.55%   |
| AMD Ryzen 5             | 1         | 4.55%   |
| AMD Ryzen 3             | 1         | 4.55%   |
| AMD E1                  | 1         | 4.55%   |
| AMD A4                  | 1         | 4.55%   |
| AMD A12                 | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 72.73%  |
| 4      | 6         | 27.27%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 86.36%  |
| 1      | 3         | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 33.33%  |
| 0x40651    | 2         | 8.33%   |
| 0x206a7    | 2         | 8.33%   |
| 0x806e9    | 1         | 4.17%   |
| 0x706e5    | 1         | 4.17%   |
| 0x406e3    | 1         | 4.17%   |
| 0x306c3    | 1         | 4.17%   |
| 0x306a9    | 1         | 4.17%   |
| 0x20652    | 1         | 4.17%   |
| 0x1067a    | 1         | 4.17%   |
| 0x08108102 | 1         | 4.17%   |
| 0x08101007 | 1         | 4.17%   |
| 0x07000110 | 1         | 4.17%   |
| 0x0700010f | 1         | 4.17%   |
| 0x06006118 | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| SandyBridge | 3         | 13.64%  |
| Haswell     | 3         | 13.64%  |
| Zen+        | 2         | 9.09%   |
| Skylake     | 2         | 9.09%   |
| Jaguar      | 2         | 9.09%   |
| IvyBridge   | 2         | 9.09%   |
| IceLake     | 2         | 9.09%   |
| Zen         | 1         | 4.55%   |
| Westmere    | 1         | 4.55%   |
| Penryn      | 1         | 4.55%   |
| KabyLake    | 1         | 4.55%   |
| Excavator   | 1         | 4.55%   |
| Broadwell   | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 58.33%  |
| AMD    | 6         | 25%     |
| Nvidia | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 12.5%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 8.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 8.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 8.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 8.33%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 4.17%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 4.17%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 4.17%   |
| Nvidia G96CM [GeForce 9600M GS]                                           | 1         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 4.17%   |
| Intel HD Graphics 620                                                     | 1         | 4.17%   |
| Intel HD Graphics 5300                                                    | 1         | 4.17%   |
| Intel HD Graphics 530                                                     | 1         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 4.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1         | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 4.17%   |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 4.17%   |
| AMD Kabini [Radeon HD 8210]                                               | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 54.55%  |
| 1 x AMD        | 6         | 27.27%  |
| 1 x Nvidia     | 2         | 9.09%   |
| Intel + Nvidia | 2         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 22        | 95.65%  |
| Unknown | 1         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 59.09%  |
| 0.01-0.5   | 4         | 18.18%  |
| 1.01-2.0   | 3         | 13.64%  |
| 0.51-1.0   | 2         | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5         | 20.83%  |
| LG Display              | 5         | 20.83%  |
| Chimei Innolux          | 4         | 16.67%  |
| AU Optronics            | 3         | 12.5%   |
| BOE                     | 2         | 8.33%   |
| Vizio                   | 1         | 4.17%   |
| Sharp                   | 1         | 4.17%   |
| Goldstar                | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| Apple                   | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                      | 1         | 4.17%   |
| Sharp LQ116M1JW02 SHP1440 1920x1080 256x144mm 11.6-inch                  | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 4.17%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 4.17%   |
| Goldstar 32LG5010 GSM75F0 1920x1080 700x390mm 31.5-inch                  | 1         | 4.17%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1746 1600x900 382x214mm 17.2-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 1         | 4.17%   |
| BOE LCD Monitor BOE083C 1920x1080 309x173mm 13.9-inch                    | 1         | 4.17%   |
| BOE LCD Monitor BOE07D3 1920x1080 309x174mm 14.0-inch                    | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO9274 1280x800 331x207mm 15.4-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 1         | 4.17%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 39.13%  |
| 1366x768 (WXGA)  | 8         | 34.78%  |
| 1600x900 (HD+)   | 2         | 8.7%    |
| 3840x2400        | 1         | 4.35%   |
| 2160x1440        | 1         | 4.35%   |
| 1440x900 (WXGA+) | 1         | 4.35%   |
| 1280x800 (WXGA)  | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 41.67%  |
| 14     | 4         | 16.67%  |
| 13     | 4         | 16.67%  |
| 17     | 2         | 8.33%   |
| 38     | 1         | 4.17%   |
| 31     | 1         | 4.17%   |
| 16     | 1         | 4.17%   |
| 11     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 58.33%  |
| 351-400     | 5         | 20.83%  |
| 201-300     | 3         | 12.5%   |
| 801-900     | 1         | 4.17%   |
| 601-700     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 81.82%  |
| 16/10 | 3         | 13.64%  |
| 3/2   | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 41.67%  |
| 81-90          | 7         | 29.17%  |
| 121-130        | 3         | 12.5%   |
| 71-80          | 1         | 4.17%   |
| 51-60          | 1         | 4.17%   |
| 351-500        | 1         | 4.17%   |
| 501-1000       | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 29.17%  |
| 51-100        | 7         | 29.17%  |
| 101-120       | 6         | 25%     |
| 161-240       | 2         | 8.33%   |
| More than 240 | 1         | 4.17%   |
| 1-50          | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 86.96%  |
| 2     | 2         | 8.7%    |
| 0     | 1         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 30.3%   |
| Realtek Semiconductor           | 9         | 27.27%  |
| Qualcomm Atheros                | 6         | 18.18%  |
| Broadcom Limited                | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| Ralink Technology               | 1         | 3.03%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| Marvell Technology Group        | 1         | 3.03%   |
| D-Link                          | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller               | 4         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 4         | 9.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 4.76%   |
| Intel Wireless 7265                                                                  | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 2         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 2.38%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 2.38%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 2.38%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 2.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 2.38%   |
| Intel Wireless 8260                                                                  | 1         | 2.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 1         | 2.38%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 2.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 2.38%   |
| Intel Ethernet Connection I217-LM                                                    | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                                                | 1         | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                                | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 2.38%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 1         | 2.38%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 2.38%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                          | 1         | 2.38%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                 | 1         | 2.38%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 1         | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 40%     |
| Qualcomm Atheros                | 5         | 20%     |
| Realtek Semiconductor           | 4         | 16%     |
| Broadcom                        | 2         | 8%      |
| Ralink Technology               | 1         | 4%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| D-Link                          | 1         | 4%      |
| Broadcom Limited                | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2         | 7.69%   |
| Intel Wireless 7265                                                                  | 2         | 7.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 3.85%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 3.85%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 3.85%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 3.85%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 3.85%   |
| Intel Wireless 8260                                                                  | 1         | 3.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 1         | 3.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 3.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 3.85%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 1         | 3.85%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 3.85%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                 | 1         | 3.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 1         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 50%     |
| Intel                    | 5         | 31.25%  |
| Qualcomm Atheros         | 1         | 6.25%   |
| Marvell Technology Group | 1         | 6.25%   |
| Broadcom Limited         | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 4         | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 12.5%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 6.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 6.25%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 6.25%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 6.25%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 6.25%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 57.89%  |
| Ethernet | 16        | 42.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 72.73%  |
| Ethernet | 6         | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 72.73%  |
| 1     | 6         | 27.27%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 73.91%  |
| Yes  | 6         | 26.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 33.33%  |
| Broadcom                        | 4         | 22.22%  |
| Realtek Semiconductor           | 3         | 16.67%  |
| Qualcomm Atheros Communications | 2         | 11.11%  |
| IMC Networks                    | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 22.22%  |
| Realtek Bluetooth Radio                             | 2         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 5.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 5.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 5.56%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 5.56%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 5.56%   |
| Apple Bluetooth USB Host Controller                 | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 16        | 64%     |
| AMD     | 6         | 24%     |
| Nvidia  | 2         | 8%      |
| Unknown | 1         | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 8.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 8.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 8.82%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3         | 8.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 5.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 5.88%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5.88%   |
| AMD FCH Azalia Controller                                                  | 2         | 5.88%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.94%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.94%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.94%   |
| Unknown                                                                    | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Micron Technology   | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 25%     |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 25%     |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 1         | 25%     |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 3         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3         | 75%     |
| Row Of Chips | 1         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 2         | 50%     |
| 16384 | 1         | 25%     |
| 4096  | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 2         | 50%     |
| 2667  | 2         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 20%     |
| Suyin                                  | 3         | 15%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 15%     |
| Sunplus Innovation Technology          | 2         | 10%     |
| Realtek Semiconductor                  | 2         | 10%     |
| Microdia                               | 2         | 10%     |
| IMC Networks                           | 2         | 10%     |
| Z-Star Microelectronics                | 1         | 5%      |
| Lite-On Technology                     | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 10%     |
| Z-Star WebCam SCB-1900N                                        | 1         | 5%      |
| Suyin UVC HD Webcam                                            | 1         | 5%      |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 5%      |
| Suyin HP Truevision HD                                         | 1         | 5%      |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 5%      |
| Sunplus Integrated_Webcam_HD                                   | 1         | 5%      |
| Realtek Integrated Webcam HD                                   | 1         | 5%      |
| Realtek FJ Camera                                              | 1         | 5%      |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 5%      |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 5%      |
| Lite-On HP Wide Vision HD Camera                               | 1         | 5%      |
| IMC Networks Integrated Camera                                 | 1         | 5%      |
| IMC Networks Huawei Web Camera - HD                            | 1         | 5%      |
| Chicony UVC 1.00 device HD UVC WebCam                          | 1         | 5%      |
| Chicony Lenovo EasyCamera                                      | 1         | 5%      |
| Chicony Integrated Camera                                      | 1         | 5%      |
| Chicony FJ 5M Camera                                           | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 2         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| O2 Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 73.91%  |
| 1     | 3         | 13.04%  |
| 2     | 2         | 8.7%    |
| 3     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chipcard              | 3         | 37.5%   |
| Fingerprint reader    | 2         | 25%     |
| Storage               | 1         | 12.5%   |
| Multimedia controller | 1         | 12.5%   |
| Graphics card         | 1         | 12.5%   |

