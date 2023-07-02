Kubuntu 23.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

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

Total: 36

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| MSI           | H81M-P32                    | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| ASUSTek       | H81M-A                      | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Alienware     | 04VWF2 A00                  | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| ASRock        | X99 Extreme6/ac             | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | 3397                        | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Biostar       | AM1MHP                      | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Gigabyte      | H87-HD3                     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| HP            | 828A                        | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.2.0-20-generic       | 15       | 53.57%  |
| 6.2.0-23-generic       | 5        | 17.86%  |
| 6.2.0-1003-lowlatency  | 2        | 7.14%   |
| 6.3.5-060305-generic   | 1        | 3.57%   |
| 6.2.5-060205-generic   | 1        | 3.57%   |
| 6.2.0-24-generic       | 1        | 3.57%   |
| 6.1.0-16-generic       | 1        | 3.57%   |
| 5.19.0-28-generic      | 1        | 3.57%   |
| 5.19.0-1023-lowlatency | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 23       | 82.14%  |
| 5.19.0  | 2        | 7.14%   |
| 6.3.5   | 1        | 3.57%   |
| 6.2.5   | 1        | 3.57%   |
| 6.1.0   | 1        | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 24       | 85.71%  |
| 5.19    | 2        | 7.14%   |
| 6.3     | 1        | 3.57%   |
| 6.1     | 1        | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 27       | 96.43%  |
| KDE  | 1        | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 75%     |
| Wayland | 6        | 21.43%  |
| Tty     | 1        | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 17       | 60.71%  |
| Unknown | 11       | 39.29%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 32.14%  |
| en_GB | 4        | 14.29%  |
| de_DE | 4        | 14.29%  |
| zh_TW | 1        | 3.57%   |
| sv_SE | 1        | 3.57%   |
| pt_BR | 1        | 3.57%   |
| it_IT | 1        | 3.57%   |
| fr_FR | 1        | 3.57%   |
| es_MX | 1        | 3.57%   |
| es_CO | 1        | 3.57%   |
| es_CL | 1        | 3.57%   |
| en_IN | 1        | 3.57%   |
| en_IL | 1        | 3.57%   |
| en_CA | 1        | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 60.71%  |
| EFI  | 11       | 39.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 21       | 75%     |
| Tmpfs | 5        | 17.86%  |
| F2fs  | 1        | 3.57%   |
| Btrfs | 1        | 3.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 14       | 50%     |
| Unknown | 11       | 39.29%  |
| MBR     | 3        | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 75%     |
| Yes       | 7        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 71.43%  |
| Yes       | 8        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 6        | 21.43%  |
| ASUSTek Computer    | 6        | 21.43%  |
| MSI                 | 2        | 7.14%   |
| Intel               | 2        | 7.14%   |
| Hewlett-Packard     | 2        | 7.14%   |
| Fujitsu             | 2        | 7.14%   |
| ASRock              | 2        | 7.14%   |
| Seco                | 1        | 3.57%   |
| Foxconn             | 1        | 3.57%   |
| Biostar             | 1        | 3.57%   |
| BESSTAR Tech        | 1        | 3.57%   |
| Alienware           | 1        | 3.57%   |
| Unknown             | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Seco C40                      | 1        | 3.57%   |
| MSI MS-7846                   | 1        | 3.57%   |
| MSI MS-7693                   | 1        | 3.57%   |
| Intel SHARKBAY                | 1        | 3.57%   |
| Intel H61                     | 1        | 3.57%   |
| HP Compaq Elite 8300 SFF      | 1        | 3.57%   |
| HP 870-119                    | 1        | 3.57%   |
| Gigabyte X570S AORUS ELITE AX | 1        | 3.57%   |
| Gigabyte H87-HD3              | 1        | 3.57%   |
| Gigabyte GA-MA770-US3         | 1        | 3.57%   |
| Gigabyte B550 AORUS ELITE V2  | 1        | 3.57%   |
| Gigabyte B365M H              | 1        | 3.57%   |
| Gigabyte B360M-HD3            | 1        | 3.57%   |
| Fujitsu ESPRIMO D538          | 1        | 3.57%   |
| Fujitsu D3222-B1              | 1        | 3.57%   |
| Foxconn H67M-S/H67M-V/H67     | 1        | 3.57%   |
| Biostar AM1MHP                | 1        | 3.57%   |
| BESSTAR Tech UM700            | 1        | 3.57%   |
| ASUS TUF Gaming X570-PLUS     | 1        | 3.57%   |
| ASUS PRIME H610M-E D4         | 1        | 3.57%   |
| ASUS PRIME H310M-A R2.0       | 1        | 3.57%   |
| ASUS Maximus IX HERO          | 1        | 3.57%   |
| ASUS M5A78L-M LX PLUS         | 1        | 3.57%   |
| ASUS All Series               | 1        | 3.57%   |
| ASRock X99 Extreme6/ac        | 1        | 3.57%   |
| ASRock A320M-HDV R4.0         | 1        | 3.57%   |
| Alienware Aurora              | 1        | 3.57%   |
| Unknown                       | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 2        | 7.14%   |
| Seco C40              | 1        | 3.57%   |
| MSI MS-7846           | 1        | 3.57%   |
| MSI MS-7693           | 1        | 3.57%   |
| Intel SHARKBAY        | 1        | 3.57%   |
| Intel H61             | 1        | 3.57%   |
| HP Compaq             | 1        | 3.57%   |
| HP 870-119            | 1        | 3.57%   |
| Gigabyte X570S        | 1        | 3.57%   |
| Gigabyte H87-HD3      | 1        | 3.57%   |
| Gigabyte GA-MA770-US3 | 1        | 3.57%   |
| Gigabyte B550         | 1        | 3.57%   |
| Gigabyte B365M        | 1        | 3.57%   |
| Gigabyte B360M-HD3    | 1        | 3.57%   |
| Fujitsu ESPRIMO       | 1        | 3.57%   |
| Fujitsu D3222-B1      | 1        | 3.57%   |
| Foxconn H67M-S        | 1        | 3.57%   |
| Biostar AM1MHP        | 1        | 3.57%   |
| BESSTAR Tech UM700    | 1        | 3.57%   |
| ASUS TUF              | 1        | 3.57%   |
| ASUS Maximus          | 1        | 3.57%   |
| ASUS M5A78L-M         | 1        | 3.57%   |
| ASUS All              | 1        | 3.57%   |
| ASRock X99            | 1        | 3.57%   |
| ASRock A320M-HDV      | 1        | 3.57%   |
| Alienware Aurora      | 1        | 3.57%   |
| Unknown               | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 6        | 21.43%  |
| 2018 | 4        | 14.29%  |
| 2021 | 3        | 10.71%  |
| 2013 | 3        | 10.71%  |
| 2022 | 2        | 7.14%   |
| 2014 | 2        | 7.14%   |
| 2011 | 2        | 7.14%   |
| 2020 | 1        | 3.57%   |
| 2017 | 1        | 3.57%   |
| 2016 | 1        | 3.57%   |
| 2012 | 1        | 3.57%   |
| 2010 | 1        | 3.57%   |
| 2009 | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 8        | 28.57%  |
| 8.01-16.0   | 6        | 21.43%  |
| 32.01-64.0  | 5        | 17.86%  |
| 4.01-8.0    | 4        | 14.29%  |
| 3.01-4.0    | 2        | 7.14%   |
| 64.01-256.0 | 2        | 7.14%   |
| 24.01-32.0  | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 10       | 34.48%  |
| 1.01-2.0  | 7        | 24.14%  |
| 3.01-4.0  | 5        | 17.24%  |
| 2.01-3.0  | 5        | 17.24%  |
| 8.01-16.0 | 2        | 6.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 32.14%  |
| 1      | 8        | 28.57%  |
| 3      | 6        | 21.43%  |
| 4      | 3        | 10.71%  |
| 7      | 2        | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 64.29%  |
| Yes       | 10       | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 50%     |
| No        | 14       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 71.43%  |
| Yes       | 8        | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Germany   | 5        | 17.86%  |
| UK        | 4        | 14.29%  |
| USA       | 3        | 10.71%  |
| Serbia    | 2        | 7.14%   |
| Taiwan    | 1        | 3.57%   |
| Sweden    | 1        | 3.57%   |
| Spain     | 1        | 3.57%   |
| Poland    | 1        | 3.57%   |
| Mexico    | 1        | 3.57%   |
| Italy     | 1        | 3.57%   |
| Israel    | 1        | 3.57%   |
| Indonesia | 1        | 3.57%   |
| India     | 1        | 3.57%   |
| France    | 1        | 3.57%   |
| Colombia  | 1        | 3.57%   |
| Chile     | 1        | 3.57%   |
| Canada    | 1        | 3.57%   |
| Brazil    | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| London        | 2        | 7.14%   |
| Weilmuenster  | 1        | 3.57%   |
| Taichung      | 1        | 3.57%   |
| Sutton        | 1        | 3.57%   |
| Santiago      | 1        | 3.57%   |
| Rzeszów      | 1        | 3.57%   |
| Porto Alegre  | 1        | 3.57%   |
| Pančevo      | 1        | 3.57%   |
| Orbassano     | 1        | 3.57%   |
| Oberursel     | 1        | 3.57%   |
| Niebla        | 1        | 3.57%   |
| Middlesbrough | 1        | 3.57%   |
| Metepec       | 1        | 3.57%   |
| Lucknow       | 1        | 3.57%   |
| Leipzig       | 1        | 3.57%   |
| Lazarevac     | 1        | 3.57%   |
| La Mesa       | 1        | 3.57%   |
| Helsingborg   | 1        | 3.57%   |
| Hamburg       | 1        | 3.57%   |
| Ensdorf       | 1        | 3.57%   |
| Dudley        | 1        | 3.57%   |
| Compiègne    | 1        | 3.57%   |
| Brantford     | 1        | 3.57%   |
| Boise         | 1        | 3.57%   |
| Bat Yam       | 1        | 3.57%   |
| Barranquilla  | 1        | 3.57%   |
| Banyuwangi    | 1        | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 10       | 15     | 19.61%  |
| WDC                         | 9        | 12     | 17.65%  |
| Samsung Electronics         | 7        | 16     | 13.73%  |
| Kingston                    | 6        | 8      | 11.76%  |
| SanDisk                     | 2        | 2      | 3.92%   |
| Kingston Technology Company | 2        | 2      | 3.92%   |
| A-DATA Technology           | 2        | 2      | 3.92%   |
| Unknown                     | 1        | 1      | 1.96%   |
| Toshiba                     | 1        | 1      | 1.96%   |
| SPCC                        | 1        | 5      | 1.96%   |
| PNY                         | 1        | 1      | 1.96%   |
| Patriot                     | 1        | 1      | 1.96%   |
| Micron Technology           | 1        | 1      | 1.96%   |
| Maxtor                      | 1        | 1      | 1.96%   |
| Lexar                       | 1        | 1      | 1.96%   |
| Hoodisk                     | 1        | 1      | 1.96%   |
| Hitachi                     | 1        | 1      | 1.96%   |
| Gigabyte Technology         | 1        | 1      | 1.96%   |
| Crucial                     | 1        | 1      | 1.96%   |
| Unknown                     | 1        | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB       | 3        | 4.41%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 2        | 2.94%   |
| Seagate ST1000DM003-1ER162 1TB       | 2        | 2.94%   |
| Kingston SA400S37120G 120GB SSD      | 2        | 2.94%   |
| WDC WDS500G2B0A 500GB SSD            | 1        | 1.47%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1        | 1.47%   |
| WDC WD3200AAJS-65M0A0 320GB          | 1        | 1.47%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1.47%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1        | 1.47%   |
| WDC WD10EFRX-68JCSN0 1TB             | 1        | 1.47%   |
| WDC WD10EAVS-32D7B1 1TB              | 1        | 1.47%   |
| WDC WD Green 2.5 1000GB SSD          | 1        | 1.47%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB | 1        | 1.47%   |
| Unknown SD/MMC/MS PRO 250GB          | 1        | 1.47%   |
| Toshiba DT01ACA100 1TB               | 1        | 1.47%   |
| SPCC Solid State Disk 512GB          | 1        | 1.47%   |
| SPCC Solid State Disk 2TB            | 1        | 1.47%   |
| SPCC Solid State Disk 256GB          | 1        | 1.47%   |
| SPCC Solid State Disk 1024GB         | 1        | 1.47%   |
| Seagate ST9500420AS 500GB            | 1        | 1.47%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1.47%   |
| Seagate ST4000DM005-2DP166 4TB       | 1        | 1.47%   |
| Seagate ST3500312CS 500GB            | 1        | 1.47%   |
| Seagate ST3250823AS 250GB            | 1        | 1.47%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1.47%   |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.47%   |
| Seagate ST1000DX001-1CM162 1TB       | 1        | 1.47%   |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 1.47%   |
| SanDisk SSD PLUS 240GB               | 1        | 1.47%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD  | 1        | 1.47%   |
| Samsung SSD 980 PRO 2TB              | 1        | 1.47%   |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 1.47%   |
| Samsung SSD 960 EVO 250GB            | 1        | 1.47%   |
| Samsung SSD 870 QVO 2TB              | 1        | 1.47%   |
| Samsung SSD 860 PRO 256GB            | 1        | 1.47%   |
| Samsung SSD 860 EVO 250GB            | 1        | 1.47%   |
| Samsung SSD 850 PRO 512GB            | 1        | 1.47%   |
| Samsung SSD 850 PRO 256GB            | 1        | 1.47%   |
| Samsung SSD 850 EVO 250GB            | 1        | 1.47%   |
| Samsung SSD 840 Series 120GB         | 1        | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 15     | 47.62%  |
| WDC                 | 6        | 8      | 28.57%  |
| Unknown             | 1        | 1      | 4.76%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Maxtor              | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 7      | 22.73%  |
| Samsung Electronics | 4        | 10     | 18.18%  |
| WDC                 | 3        | 3      | 13.64%  |
| SanDisk             | 2        | 2      | 9.09%   |
| A-DATA Technology   | 2        | 2      | 9.09%   |
| SPCC                | 1        | 5      | 4.55%   |
| PNY                 | 1        | 1      | 4.55%   |
| Patriot             | 1        | 1      | 4.55%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| Hoodisk             | 1        | 1      | 4.55%   |
| Gigabyte Technology | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 21       | 34     | 46.67%  |
| HDD     | 15       | 28     | 33.33%  |
| NVMe    | 8        | 11     | 17.78%  |
| Unknown | 1        | 1      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 62     | 75%     |
| NVMe | 8        | 11     | 22.22%  |
| SAS  | 1        | 1      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 34     | 51.16%  |
| 0.51-1.0   | 12       | 16     | 27.91%  |
| 1.01-2.0   | 6        | 8      | 13.95%  |
| 3.01-4.0   | 3        | 4      | 6.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 25%     |
| 251-500        | 6        | 21.43%  |
| 501-1000       | 5        | 17.86%  |
| More than 3000 | 4        | 14.29%  |
| 1001-2000      | 3        | 10.71%  |
| 2001-3000      | 2        | 7.14%   |
| 21-50          | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 25%     |
| 21-50          | 5        | 17.86%  |
| 101-250        | 4        | 14.29%  |
| 1-20           | 3        | 10.71%  |
| 501-1000       | 3        | 10.71%  |
| 51-100         | 3        | 10.71%  |
| More than 3000 | 2        | 7.14%   |
| 1001-2000      | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-65M0A0 320GB                  | 1        | 1      | 50%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

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
| SSD  | 1        | 2      | 50%     |
| HDD  | 1        | 1      | 50%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 18       | 48     | 56.25%  |
| Works    | 11       | 21     | 34.38%  |
| Malfunc  | 2        | 3      | 6.25%   |
| Failed   | 1        | 2      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 18       | 46.15%  |
| AMD                          | 10       | 25.64%  |
| Samsung Electronics          | 4        | 10.26%  |
| Kingston Technology Company  | 2        | 5.13%   |
| Silicon Image                | 1        | 2.56%   |
| Shenzhen Longsys Electronics | 1        | 2.56%   |
| SanDisk                      | 1        | 2.56%   |
| Micron/Crucial Technology    | 1        | 2.56%   |
| JMicron Technology           | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 11.63%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 11.63%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 6.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.65%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 2.33%   |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                              | 1        | 2.33%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 2.33%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 2.33%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1        | 2.33%   |
| Kingston Company NVMe Controller                                               | 1        | 2.33%   |
| JMicron JMB58x AHCI SATA controller                                            | 1        | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 2.33%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.33%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.33%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 2.33%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 2.33%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.33%   |
| AMD FCH SATA Controller D                                                      | 1        | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 69.23%  |
| NVMe | 8        | 20.51%  |
| RAID | 2        | 5.13%   |
| IDE  | 2        | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 64.29%  |
| AMD    | 10       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 7.14%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz             | 1        | 3.57%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz          | 1        | 3.57%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 1        | 3.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 3.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 3.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 3.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 3.57%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 1        | 3.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 3.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 3.57%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 3.57%   |
| Intel Core i5-9600KF CPU @ 3.70GHz              | 1        | 3.57%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 3.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 3.57%   |
| Intel Celeron N5105 @ 2.00GHz                   | 1        | 3.57%   |
| Intel 13th Gen Core i3-13100                    | 1        | 3.57%   |
| AMD Ryzen Embedded V1605B with Radeon Vega Gfx  | 1        | 3.57%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 3.57%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 3.57%   |
| AMD Ryzen 7 5700X 8-Core Processor              | 1        | 3.57%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 1        | 3.57%   |
| AMD Ryzen 3 PRO 3200G with Radeon Vega Graphics | 1        | 3.57%   |
| AMD FX-8320E Eight-Core Processor               | 1        | 3.57%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 3.57%   |
| AMD Athlon II X3 425 Processor                  | 1        | 3.57%   |
| AMD Athlon 5350 APU with Radeon R3              | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 10       | 35.71%  |
| Intel Core i5      | 3        | 10.71%  |
| AMD Ryzen 7        | 3        | 10.71%  |
| AMD FX             | 2        | 7.14%   |
| Other              | 1        | 3.57%   |
| Intel Xeon         | 1        | 3.57%   |
| Intel Pentium Gold | 1        | 3.57%   |
| Intel Pentium      | 1        | 3.57%   |
| Intel Celeron      | 1        | 3.57%   |
| AMD Ryzen Embedded | 1        | 3.57%   |
| AMD Ryzen 9        | 1        | 3.57%   |
| AMD Ryzen 3 PRO    | 1        | 3.57%   |
| AMD Athlon II X3   | 1        | 3.57%   |
| AMD Athlon         | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 17       | 60.71%  |
| 6      | 4        | 14.29%  |
| 8      | 2        | 7.14%   |
| 3      | 2        | 7.14%   |
| 2      | 2        | 7.14%   |
| 12     | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 64.29%  |
| 1      | 10       | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 28       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 82.14%  |
| 0x0a20120a | 2        | 7.14%   |
| 0x0810100b | 1        | 3.57%   |
| 0x0700010f | 1        | 3.57%   |
| 0x06000852 | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 6        | 21.43%  |
| KabyLake    | 5        | 17.86%  |
| Zen 3       | 3        | 10.71%  |
| Zen+        | 2        | 7.14%   |
| SandyBridge | 2        | 7.14%   |
| Piledriver  | 2        | 7.14%   |
| Zen         | 1        | 3.57%   |
| Tremont     | 1        | 3.57%   |
| Skylake     | 1        | 3.57%   |
| Nehalem     | 1        | 3.57%   |
| K10         | 1        | 3.57%   |
| Jaguar      | 1        | 3.57%   |
| IvyBridge   | 1        | 3.57%   |
| Unknown     | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 12       | 37.5%   |
| Intel  | 11       | 34.38%  |
| Nvidia | 9        | 28.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 9.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 6.25%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 6.25%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 3.13%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 3.13%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 3.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.13%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 3.13%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 3.13%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 3.13%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 3.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.13%   |
| Intel DG2 [Arc A380]                                                        | 1        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.13%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 3.13%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 3.13%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 3.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.13%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 3.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.13%   |
| AMD Cypress PRO [Radeon HD 5850]                                            | 1        | 3.13%   |
| AMD Cape Verde GL [FirePro W4100]                                           | 1        | 3.13%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 10       | 35.71%  |
| 1 x Nvidia      | 8        | 28.57%  |
| 1 x Intel       | 8        | 28.57%  |
| Intel + 2 x AMD | 1        | 3.57%   |
| Intel + AMD     | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 78.57%  |
| Proprietary | 6        | 21.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 57.14%  |
| 1.01-2.0   | 5        | 17.86%  |
| 7.01-8.0   | 2        | 7.14%   |
| 5.01-6.0   | 2        | 7.14%   |
| 8.01-16.0  | 2        | 7.14%   |
| 3.01-4.0   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 17.24%  |
| Philips              | 4        | 13.79%  |
| Iiyama               | 3        | 10.34%  |
| Lenovo               | 2        | 6.9%    |
| Dell                 | 2        | 6.9%    |
| BenQ                 | 2        | 6.9%    |
| Ancor Communications | 2        | 6.9%    |
| VIZ                  | 1        | 3.45%   |
| ONN                  | 1        | 3.45%   |
| Medion Akoya         | 1        | 3.45%   |
| INS                  | 1        | 3.45%   |
| Hewlett-Packard      | 1        | 3.45%   |
| Goldstar             | 1        | 3.45%   |
| DENON                | 1        | 3.45%   |
| ASUSTek Computer     | 1        | 3.45%   |
| Acer                 | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| VIZ LCD Monitor D32h-J04 1920x1080                                   | 1        | 2.78%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch    | 1        | 2.78%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch | 1        | 2.78%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch   | 1        | 2.78%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch   | 1        | 2.78%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 2.78%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch    | 1        | 2.78%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch | 1        | 2.78%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch             | 1        | 2.78%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 2.78%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch             | 1        | 2.78%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                    | 1        | 2.78%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch               | 1        | 2.78%   |
| Medion Akoya MD20491 MEC5201 1920x1080 521x293mm 23.5-inch           | 1        | 2.78%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch             | 1        | 2.78%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 1        | 2.78%   |
| INS WT70CA612 INS3694 3840x2160 1538x865mm 69.5-inch                 | 1        | 2.78%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1        | 2.78%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                 | 1        | 2.78%   |
| Iiyama PL2451 IVM610A 1920x1080 521x293mm 23.5-inch                  | 1        | 2.78%   |
| Hewlett-Packard P204v HPN3633 1600x900 432x240mm 19.5-inch           | 1        | 2.78%   |
| Hewlett-Packard M24fw FHD HPN3708 1920x1080 527x296mm 23.8-inch      | 1        | 2.78%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 1        | 2.78%   |
| DENON AVR DON004C 3840x2160 698x392mm 31.5-inch                      | 1        | 2.78%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                    | 1        | 2.78%   |
| Dell U2715H DELD067 2560x1440 600x340mm 27.2-inch                    | 1        | 2.78%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                    | 1        | 2.78%   |
| Dell S2721QS DELA198 3840x2160 597x336mm 27.0-inch                   | 1        | 2.78%   |
| BenQ G2450H BNQ78AB 1920x1080 530x300mm 24.0-inch                    | 1        | 2.78%   |
| BenQ G2010W BNQ7811 1680x1050 474x296mm 22.0-inch                    | 1        | 2.78%   |
| ASUSTek Computer PA24A AUS2462 1920x1200 518x324mm 24.1-inch         | 1        | 2.78%   |
| Ancor Communications VE248 ACI2494 1920x1080 530x300mm 24.0-inch     | 1        | 2.78%   |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch     | 1        | 2.78%   |
| Acer GF276 ACR0560 1920x1080 598x336mm 27.0-inch                     | 1        | 2.78%   |
| Acer ED320QR S ACR0805 1920x1080 609x348mm 27.6-inch                 | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 54.84%  |
| 3840x2160 (4K)     | 4        | 12.9%   |
| 2560x1440 (QHD)    | 2        | 6.45%   |
| 1366x768 (WXGA)    | 2        | 6.45%   |
| 3440x1440          | 1        | 3.23%   |
| 1920x1200 (WUXGA)  | 1        | 3.23%   |
| 1680x1050 (WSXGA+) | 1        | 3.23%   |
| 1600x900 (HD+)     | 1        | 3.23%   |
| 1440x900 (WXGA+)   | 1        | 3.23%   |
| 1360x768           | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 24.24%  |
| 27      | 5        | 15.15%  |
| 31      | 4        | 12.12%  |
| 23      | 4        | 12.12%  |
| 21      | 3        | 9.09%   |
| 19      | 3        | 9.09%   |
| 18      | 2        | 6.06%   |
| 69      | 1        | 3.03%   |
| 34      | 1        | 3.03%   |
| 22      | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 48.48%  |
| 401-500     | 9        | 27.27%  |
| 601-700     | 5        | 15.15%  |
| 701-800     | 1        | 3.03%   |
| 1501-2000   | 1        | 3.03%   |
| Unknown     | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 78.57%  |
| 16/10   | 4        | 14.29%  |
| 21/9    | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 40.63%  |
| 351-500        | 5        | 15.63%  |
| 301-350        | 5        | 15.63%  |
| 151-200        | 3        | 9.38%   |
| 251-300        | 2        | 6.25%   |
| 141-150        | 2        | 6.25%   |
| More than 1000 | 1        | 3.13%   |
| Unknown        | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 63.33%  |
| 101-120 | 6        | 20%     |
| 121-160 | 3        | 10%     |
| 161-240 | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 75%     |
| 2     | 6        | 21.43%  |
| 4     | 1        | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 50%     |
| Intel                 | 7        | 15.91%  |
| Qualcomm Atheros      | 3        | 6.82%   |
| Broadcom              | 3        | 6.82%   |
| ASUSTek Computer      | 3        | 6.82%   |
| TP-Link               | 2        | 4.55%   |
| Texas Instruments     | 1        | 2.27%   |
| Ralink                | 1        | 2.27%   |
| MediaTek              | 1        | 2.27%   |
| Aquantia              | 1        | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 17       | 35.42%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 4.17%   |
| Intel Wireless 7265                                                           | 2        | 4.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 2.08%   |
| TP-Link 802.11n NIC                                                           | 1        | 2.08%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 2.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 2.08%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 2.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 2.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.08%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 2.08%   |
| Intel Wireless 8260                                                           | 1        | 2.08%   |
| Intel Ethernet Controller I225-V                                              | 1        | 2.08%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 2.08%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                               | 1        | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 2.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 2.08%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 2.08%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 2.08%   |
| ASUS 802.11ac NIC                                                             | 1        | 2.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 20%     |
| ASUSTek Computer      | 3        | 20%     |
| TP-Link               | 2        | 13.33%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| Broadcom              | 2        | 13.33%  |
| Realtek Semiconductor | 1        | 6.67%   |
| Ralink                | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wireless 7265                                                           | 2        | 13.33%  |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 6.67%   |
| TP-Link 802.11n NIC                                                           | 1        | 6.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 6.67%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 6.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 6.67%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 6.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 6.67%   |
| Intel Wireless 8260                                                           | 1        | 6.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 6.67%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 6.67%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 6.67%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 6.67%   |
| ASUS 802.11ac NIC                                                             | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 70.97%  |
| Intel                 | 5        | 16.13%  |
| Qualcomm Atheros      | 2        | 6.45%   |
| Broadcom              | 1        | 3.23%   |
| Aquantia              | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 53.13%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 6.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.13%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 3.13%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 65.12%  |
| WiFi     | 14       | 32.56%  |
| Modem    | 1        | 2.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 74.19%  |
| WiFi     | 8        | 25.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 67.86%  |
| 2     | 8        | 28.57%  |
| 5     | 1        | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 60.71%  |
| Yes  | 11       | 39.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 30%     |
| Realtek Semiconductor   | 2        | 20%     |
| TP-Link                 | 1        | 10%     |
| MediaTek                | 1        | 10%     |
| IMC Networks            | 1        | 10%     |
| Cambridge Silicon Radio | 1        | 10%     |
| ASUSTek Computer        | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 30%     |
| Realtek Bluetooth Radio                             | 2        | 20%     |
| TP-Link UB500 Adapter                               | 1        | 10%     |
| MediaTek Wireless_Device                            | 1        | 10%     |
| IMC Networks BCM20702A0                             | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| ASUS ASUS USB-BT500                                 | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 19       | 36.54%  |
| AMD                   | 16       | 30.77%  |
| Nvidia                | 8        | 15.38%  |
| C-Media Electronics   | 3        | 5.77%   |
| Trust                 | 1        | 1.92%   |
| Texas Instruments     | 1        | 1.92%   |
| Mackie Designs        | 1        | 1.92%   |
| Dell                  | 1        | 1.92%   |
| AudioQuest            | 1        | 1.92%   |
| 2.4G Composite Device | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 8.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4.92%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 4.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 4.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 4.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 4.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 4.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 4.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.28%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 3.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.28%   |
| Trust Microphone                                                           | 1        | 1.64%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 1.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.64%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.64%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.64%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.64%   |
| Mackie Designs CHROMIUM Microphone                                         | 1        | 1.64%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 1.64%   |
| Intel DG2 Audio Controller                                                 | 1        | 1.64%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.64%   |
| Dell AC511 Sound Bar                                                       | 1        | 1.64%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.64%   |
| AudioQuest DragonFly Black v1.5                                            | 1        | 1.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.64%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.64%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]      | 1        | 1.64%   |
| 2.4G Composite Device MIC-Wireless Device                                  | 1        | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 21.43%  |
| Micron Technology   | 2        | 14.29%  |
| G.Skill             | 2        | 14.29%  |
| Crucial             | 2        | 14.29%  |
| Unknown             | 1        | 7.14%   |
| Team                | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Patriot             | 1        | 7.14%   |
| Corsair             | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 6.67%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s             | 1        | 6.67%   |
| Samsung RAM 53D512M64D4RQ-046 8GB Row Of Chips LPDDR4 3733MT/s | 1        | 6.67%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 1        | 6.67%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 6.67%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 6.67%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 6.67%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 6.67%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 6.67%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 6.67%   |
| G.Skill RAM F4-3600C18-16GVK 16384MB DIMM DDR4 3733MT/s        | 1        | 6.67%   |
| G.Skill RAM F4-2400C15-4GRK 4GB DIMM DDR4 2400MT/s             | 1        | 6.67%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 1        | 6.67%   |
| Crucial RAM BLS16G4D240FSE.16FBD 16GB DIMM DDR4 2473MT/s       | 1        | 6.67%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s          | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 7        | 53.85%  |
| DDR3    | 4        | 30.77%  |
| LPDDR4  | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 11       | 84.62%  |
| SODIMM       | 1        | 7.69%   |
| Row Of Chips | 1        | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 50%     |
| 16384 | 4        | 28.57%  |
| 4096  | 2        | 14.29%  |
| 32768 | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3733  | 2        | 14.29%  |
| 2933  | 2        | 14.29%  |
| 1800  | 2        | 14.29%  |
| 1600  | 2        | 14.29%  |
| 3600  | 1        | 7.14%   |
| 3266  | 1        | 7.14%   |
| 2667  | 1        | 7.14%   |
| 2473  | 1        | 7.14%   |
| 2400  | 1        | 7.14%   |
| 667   | 1        | 7.14%   |

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


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Brother HL-L2310D series | 1        | 100%    |

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
| Microdia            | 2        | 40%     |
| SN0002              | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| GEMBIRD             | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SN0002 1080P Web Camera                           | 1        | 20%     |
| Samsung Galaxy A5 (MTP)                           | 1        | 20%     |
| Microdia Webcam Vitade AF                         | 1        | 20%     |
| Microdia Camera                                   | 1        | 20%     |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 20%     |

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
| 0     | 23       | 82.14%  |
| 1     | 5        | 17.86%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 2        | 50%     |
| Unassigned class         | 1        | 25%     |
| Communication controller | 1        | 25%     |

