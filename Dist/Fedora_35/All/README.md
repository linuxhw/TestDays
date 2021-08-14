Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-35

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer      | Aspire ES1-572              | Notebook    | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell      | XPS 15 9570                 | Notebook    | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell      | XPS 13 9380                 | Notebook    | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo    | IdeaPad 530S-14IKB 81EU     | Notebook    | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| HP        | 8055                        | Desktop     | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| HUAWEI    | KLVL-WXX9                   | Notebook    | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell      | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte  | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek   | Maximus V FORMULA           | Desktop     | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook  | P377SM-A                    | Notebook    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Microsoft | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [89892d4957](https://linux-hardware.org/?probe=89892d4957) | Apr 18, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [97c124c8a3](https://linux-hardware.org/?probe=97c124c8a3) | Apr 18, 2021 |
| ECS       | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek   | PRIME X570-PRO              | Desktop     | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |
| Lenovo    | ThinkPad W541 20EF000UMN    | Notebook    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HP        | Pavilion x360 Convertibl... | Convertible | [c0901f4607](https://linux-hardware.org/?probe=c0901f4607) | Mar 29, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| 5.14.0-0.rc5.42.fc35.x86_64                          | 3         | 12.5%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64  | 2         | 8.33%   |
| 5.12.0-0.rc7.189.fc35.x86_64                         | 2         | 8.33%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64  | 1         | 4.17%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64   | 1         | 4.17%   |
| 5.13.7-200.fc34.x86_64                               | 1         | 4.17%   |
| 5.13.0-58.fc35.x86_64                                | 1         | 4.17%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64  | 1         | 4.17%   |
| 5.13.0-0.rc6.45.fc35.x86_64                          | 1         | 4.17%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64  | 1         | 4.17%   |
| 5.13.0-0.rc2.19.fc35.x86_64                          | 1         | 4.17%   |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64  | 1         | 4.17%   |
| 5.13.0-0.rc1.13.fc35.x86_64                          | 1         | 4.17%   |
| 5.12.8-300.fc34.x86_64                               | 1         | 4.17%   |
| 5.12.0-0.rc8.20210423git7af08140979a.193.fc35.x86_64 | 1         | 4.17%   |
| 5.12.0-0.rc8.191.fc35.x86_64                         | 1         | 4.17%   |
| 5.12.0-0.rc7.20210416git7e25f40eab52.191.fc35.x86_64 | 1         | 4.17%   |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64 | 1         | 4.17%   |
| 5.12.0-0.rc4.20210326gitdb24726bfefa.178.fc35.x86_64 | 1         | 4.17%   |
| 5.12.0-0.rc1.162.fc35.x86_64                         | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.12.0  | 7         | 36.84%  |
| 5.14.0  | 6         | 31.58%  |
| 5.13.0  | 4         | 21.05%  |
| 5.13.7  | 1         | 5.26%   |
| 5.12.8  | 1         | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.12    | 8         | 42.11%  |
| 5.14    | 6         | 31.58%  |
| 5.13    | 5         | 26.32%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 17        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 11        | 61.11%  |
| KDE     | 4         | 22.22%  |
| MATE    | 2         | 11.11%  |
| Unknown | 1         | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 11        | 64.71%  |
| X11     | 4         | 23.53%  |
| Tty     | 2         | 11.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 8         | 47.06%  |
| Unknown | 7         | 41.18%  |
| TDM     | 1         | 5.88%   |
| LightDM | 1         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 11        | 61.11%  |
| sv_SE | 1         | 5.56%   |
| ru_RU | 1         | 5.56%   |
| pl_PL | 1         | 5.56%   |
| es_ES | 1         | 5.56%   |
| es_CL | 1         | 5.56%   |
| en_GB | 1         | 5.56%   |
| en_CA | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 15        | 88.24%  |
| BIOS | 2         | 11.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 8         | 44.44%  |
| Btrfs | 8         | 44.44%  |
| Xfs   | 2         | 11.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 11        | 61.11%  |
| Unknown | 6         | 33.33%  |
| MBR     | 1         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 12        | 63.16%  |
| Yes       | 7         | 36.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 78.95%  |
| Yes       | 4         | 21.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 17.65%  |
| Dell                | 3         | 17.65%  |
| Lenovo              | 2         | 11.76%  |
| HUAWEI              | 2         | 11.76%  |
| ASUSTek Computer    | 2         | 11.76%  |
| Notebook            | 1         | 5.88%   |
| Microsoft           | 1         | 5.88%   |
| Gigabyte Technology | 1         | 5.88%   |
| ECS                 | 1         | 5.88%   |
| Acer                | 1         | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Notebook P377SM-A                      | 1         | 5.88%   |
| Microsoft Surface Pro                  | 1         | 5.88%   |
| Lenovo ThinkPad W541 20EF000UMN        | 1         | 5.88%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 1         | 5.88%   |
| HUAWEI KLVL-WXX9                       | 1         | 5.88%   |
| HUAWEI BOHK-WAX9X                      | 1         | 5.88%   |
| HP Pavilion x360 Convertible 15-cr0xxx | 1         | 5.88%   |
| HP Pavilion x360 Convertible 14-dh0xxx | 1         | 5.88%   |
| HP EliteDesk 800 G2 DM 35W             | 1         | 5.88%   |
| Gigabyte F2A88XN-WIFI                  | 1         | 5.88%   |
| ECS MCP61M-M3                          | 1         | 5.88%   |
| Dell XPS 15 9570                       | 1         | 5.88%   |
| Dell XPS 13 9380                       | 1         | 5.88%   |
| Dell OptiPlex 9020                     | 1         | 5.88%   |
| ASUS PRIME X570-PRO                    | 1         | 5.88%   |
| ASUS Maximus V FORMULA                 | 1         | 5.88%   |
| Acer Aspire ES1-572                    | 1         | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 2         | 11.76%  |
| Dell XPS              | 2         | 11.76%  |
| Notebook P377SM-A     | 1         | 5.88%   |
| Microsoft Surface     | 1         | 5.88%   |
| Lenovo ThinkPad       | 1         | 5.88%   |
| Lenovo IdeaPad        | 1         | 5.88%   |
| HUAWEI KLVL-WXX9      | 1         | 5.88%   |
| HUAWEI BOHK-WAX9X     | 1         | 5.88%   |
| HP EliteDesk          | 1         | 5.88%   |
| Gigabyte F2A88XN-WIFI | 1         | 5.88%   |
| ECS MCP61M-M3         | 1         | 5.88%   |
| Dell OptiPlex         | 1         | 5.88%   |
| ASUS PRIME            | 1         | 5.88%   |
| ASUS Maximus          | 1         | 5.88%   |
| Acer Aspire           | 1         | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 6         | 35.29%  |
| 2019 | 5         | 29.41%  |
| 2015 | 3         | 17.65%  |
| 2021 | 1         | 5.88%   |
| 2013 | 1         | 5.88%   |
| 2010 | 1         | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 8         | 47.06%  |
| Desktop     | 6         | 35.29%  |
| Convertible | 2         | 11.76%  |
| Tablet      | 1         | 5.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 12        | 66.67%  |
| Enabled  | 6         | 33.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 38.89%  |
| 8.01-16.0  | 4         | 22.22%  |
| 32.01-64.0 | 3         | 16.67%  |
| 3.01-4.0   | 3         | 16.67%  |
| 16.01-24.0 | 1         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 38.1%   |
| 3.01-4.0 | 5         | 23.81%  |
| 1.01-2.0 | 4         | 19.05%  |
| 4.01-8.0 | 2         | 9.52%   |
| 0.51-1.0 | 1         | 4.76%   |
| 0.01-0.5 | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 12        | 70.59%  |
| 2      | 3         | 17.65%  |
| 5      | 1         | 5.88%   |
| 4      | 1         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 14        | 82.35%  |
| Yes       | 3         | 17.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 58.82%  |
| No        | 7         | 41.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 82.35%  |
| No        | 3         | 17.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 70.59%  |
| No        | 5         | 29.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 4         | 23.53%  |
| Canada      | 2         | 11.76%  |
| Turkey      | 1         | 5.88%   |
| Switzerland | 1         | 5.88%   |
| Sweden      | 1         | 5.88%   |
| Spain       | 1         | 5.88%   |
| Russia      | 1         | 5.88%   |
| Poland      | 1         | 5.88%   |
| Netherlands | 1         | 5.88%   |
| Hong Kong   | 1         | 5.88%   |
| Germany     | 1         | 5.88%   |
| Chile       | 1         | 5.88%   |
| Brazil      | 1         | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Yakima         | 2         | 10.53%  |
| Zurich         | 1         | 5.26%   |
| Wroclaw        | 1         | 5.26%   |
| Whittier       | 1         | 5.26%   |
| Wateringen     | 1         | 5.26%   |
| Vancouver      | 1         | 5.26%   |
| St Petersburg  | 1         | 5.26%   |
| Seattle        | 1         | 5.26%   |
| Raesfeld       | 1         | 5.26%   |
| Porto Ferreira | 1         | 5.26%   |
| Owatonna       | 1         | 5.26%   |
| Montreal       | 1         | 5.26%   |
| Madrid         | 1         | 5.26%   |
| La Florida     | 1         | 5.26%   |
| Kwu Tung       | 1         | 5.26%   |
| Istanbul       | 1         | 5.26%   |
| Handen         | 1         | 5.26%   |
| Bolszewo       | 1         | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 8      | 20.83%  |
| Samsung Electronics | 5         | 17     | 20.83%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Unknown             | 2         | 2      | 8.33%   |
| Seagate             | 2         | 7      | 8.33%   |
| SanDisk             | 2         | 3      | 8.33%   |
| SUNEAST             | 1         | 1      | 4.17%   |
| SK Hynix            | 1         | 2      | 4.17%   |
| SABRENT             | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 3.7%    |
| WDC WD30EZRX-00MMMB0 3TB                | 1         | 3.7%    |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 3.7%    |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 3.7%    |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 3.7%    |
| Unknown SSD0240S00 240GB                | 1         | 3.7%    |
| Unknown SD256  249GB                    | 1         | 3.7%    |
| Toshiba MG05ACA800E 8TB                 | 1         | 3.7%    |
| Toshiba KXG60ZNV256G NVMe 256GB         | 1         | 3.7%    |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 3.7%    |
| SUNEAST SSD SE800 256GB                 | 1         | 3.7%    |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 3.7%    |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 3.7%    |
| Seagate ST3500630AS 500GB               | 1         | 3.7%    |
| Seagate ST3000DM001-1CH166 3TB          | 1         | 3.7%    |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 3.7%    |
| SanDisk SDSSDH3512G 512GB               | 1         | 3.7%    |
| Sandisk NVMe SSD Drive 256GB            | 1         | 3.7%    |
| Samsung SSD 860 EVO 250GB               | 1         | 3.7%    |
| Samsung SSD 850 PRO 1TB                 | 1         | 3.7%    |
| Samsung SSD 850 EVO mSATA 1TB           | 1         | 3.7%    |
| Samsung SSD 840 EVO 250GB               | 1         | 3.7%    |
| Samsung NVMe SSD Drive 500GB            | 1         | 3.7%    |
| Samsung KUS020203M-B000 128GB           | 1         | 3.7%    |
| SABRENT ASM1153E 512GB                  | 1         | 3.7%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 1         | 3.7%    |
| LITEON CV8-8E128-HP 128GB SSD           | 1         | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 4      | 40%     |
| Seagate | 2         | 7      | 40%     |
| Toshiba | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 14     | 30%     |
| WDC                 | 1         | 1      | 10%     |
| Unknown             | 1         | 1      | 10%     |
| SUNEAST             | 1         | 1      | 10%     |
| SanDisk             | 1         | 2      | 10%     |
| SABRENT             | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| LITEON              | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 22     | 40%     |
| NVMe | 7         | 11     | 35%     |
| HDD  | 4         | 12     | 20%     |
| MMC  | 1         | 1      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11        | 33     | 55%     |
| NVMe | 7         | 11     | 35%     |
| SAS  | 1         | 1      | 5%      |
| MMC  | 1         | 1      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 14     | 53.85%  |
| 0.51-1.0   | 3         | 12     | 23.08%  |
| 2.01-3.0   | 1         | 6      | 7.69%   |
| 1.01-2.0   | 1         | 1      | 7.69%   |
| 4.01-10.0  | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 5         | 26.32%  |
| 101-250    | 4         | 21.05%  |
| 1-20       | 4         | 21.05%  |
| 501-1000   | 2         | 10.53%  |
| 21-50      | 1         | 5.26%   |
| 2001-3000  | 1         | 5.26%   |
| 1001-2000  | 1         | 5.26%   |
| 51-100     | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 8         | 44.44%  |
| 21-50     | 3         | 16.67%  |
| 251-500   | 2         | 11.11%  |
| 101-250   | 2         | 11.11%  |
| 1001-2000 | 1         | 5.56%   |
| 501-1000  | 1         | 5.56%   |
| 51-100    | 1         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB      | 1         | 1      | 33.33%  |
| Seagate ST3500630AS 500GB     | 1         | 1      | 33.33%  |
| LITEON CV8-8E128-HP 128GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| LITEON  | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 2      | 50%     |

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
| Works    | 12        | 17     | 52.17%  |
| Detected | 9         | 26     | 39.13%  |
| Malfunc  | 2         | 3      | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 10        | 47.62%  |
| Toshiba America Info Systems | 2         | 9.52%   |
| Sandisk                      | 2         | 9.52%   |
| Samsung Electronics          | 2         | 9.52%   |
| AMD                          | 2         | 9.52%   |
| SK Hynix                     | 1         | 4.76%   |
| Nvidia                       | 1         | 4.76%   |
| ASMedia Technology           | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 13.64%  |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 9.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 9.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 4.55%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 4.55%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 4.55%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 4.55%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 4.55%   |
| Nvidia MCP61 IDE                                                                 | 1         | 4.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 4.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 4.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 4.55%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10        | 50%     |
| NVMe | 7         | 35%     |
| RAID | 2         | 10%     |
| IDE  | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 12        | 70.59%  |
| AMD    | 5         | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 11.76%  |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 5.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 5.88%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 5.88%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 5.88%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 5.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 5.88%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 5.88%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1         | 5.88%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 5.88%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 5.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 1         | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 5.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 5.88%   |
| AMD Athlon II X2 250 Processor                  | 1         | 5.88%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1         | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 5         | 29.41%  |
| Intel Core i5    | 5         | 29.41%  |
| AMD Ryzen 5      | 3         | 17.65%  |
| Intel Core i3    | 2         | 11.76%  |
| AMD Athlon II X2 | 1         | 5.88%   |
| AMD A10          | 1         | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 9         | 52.94%  |
| 2      | 5         | 29.41%  |
| 6      | 3         | 17.65%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 14        | 82.35%  |
| 1      | 3         | 17.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 3         | 17.65%  |
| 0x806ec    | 2         | 11.76%  |
| 0x806ea    | 2         | 11.76%  |
| 0x906ea    | 1         | 5.88%   |
| 0x806e9    | 1         | 5.88%   |
| 0x506e3    | 1         | 5.88%   |
| 0x406e3    | 1         | 5.88%   |
| 0x306a9    | 1         | 5.88%   |
| 0x08701021 | 1         | 5.88%   |
| 0x08600104 | 1         | 5.88%   |
| 0x08108109 | 1         | 5.88%   |
| 0x06003106 | 1         | 5.88%   |
| 0x010000b6 | 1         | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 35.29%  |
| Haswell     | 3         | 17.65%  |
| Zen 2       | 2         | 11.76%  |
| Skylake     | 2         | 11.76%  |
| Zen+        | 1         | 5.88%   |
| Steamroller | 1         | 5.88%   |
| K10         | 1         | 5.88%   |
| IvyBridge   | 1         | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 11        | 55%     |
| AMD    | 5         | 25%     |
| Nvidia | 4         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 10%     |
| Intel UHD Graphics 620                                                      | 2         | 10%     |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 5%      |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 5%      |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 5%      |
| Nvidia GK104 [GeForce GTX 670]                                              | 1         | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 5%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 5%      |
| Intel HD Graphics 620                                                       | 1         | 5%      |
| Intel HD Graphics 530                                                       | 1         | 5%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 5%      |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1         | 5%      |
| AMD Renoir                                                                  | 1         | 5%      |
| AMD Picasso                                                                 | 1         | 5%      |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1         | 5%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1         | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 47.06%  |
| 1 x AMD        | 5         | 29.41%  |
| 1 x Nvidia     | 2         | 11.76%  |
| Intel + Nvidia | 2         | 11.76%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 16        | 88.89%  |
| Proprietary | 2         | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 52.63%  |
| 3.01-4.0   | 2         | 10.53%  |
| 1.01-2.0   | 2         | 10.53%  |
| 0.51-1.0   | 2         | 10.53%  |
| 0.01-0.5   | 2         | 10.53%  |
| 7.01-8.0   | 1         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 3         | 18.75%  |
| AU Optronics         | 3         | 18.75%  |
| Chimei Innolux       | 2         | 12.5%   |
| BOE                  | 2         | 12.5%   |
| AOC                  | 2         | 12.5%   |
| Sharp                | 1         | 6.25%   |
| Hewlett-Packard      | 1         | 6.25%   |
| Dell                 | 1         | 6.25%   |
| Ancor Communications | 1         | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 5.88%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 5.88%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 1         | 5.88%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch           | 1         | 5.88%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1         | 5.88%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                      | 1         | 5.88%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                      | 1         | 5.88%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 1         | 5.88%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 5.88%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 1         | 5.88%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch         | 1         | 5.88%   |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1         | 5.88%   |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1         | 5.88%   |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1         | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 9         | 60%     |
| 3840x2160 (4K)    | 1         | 6.67%   |
| 2736x1824         | 1         | 6.67%   |
| 2560x1440 (QHD)   | 1         | 6.67%   |
| 2160x1440         | 1         | 6.67%   |
| 1920x1200 (WUXGA) | 1         | 6.67%   |
| 1366x768 (WXGA)   | 1         | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 5         | 31.25%  |
| 21     | 3         | 18.75%  |
| 14     | 3         | 18.75%  |
| 27     | 1         | 6.25%   |
| 25     | 1         | 6.25%   |
| 17     | 1         | 6.25%   |
| 13     | 1         | 6.25%   |
| 12     | 1         | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 43.75%  |
| 401-500     | 3         | 18.75%  |
| 201-300     | 3         | 18.75%  |
| 501-600     | 2         | 12.5%   |
| 351-400     | 1         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 80%     |
| 3/2   | 2         | 13.33%  |
| 16/10 | 1         | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 5         | 31.25%  |
| 81-90          | 3         | 18.75%  |
| 71-80          | 2         | 12.5%   |
| 201-250        | 2         | 12.5%   |
| 301-350        | 1         | 6.25%   |
| 251-300        | 1         | 6.25%   |
| 151-200        | 1         | 6.25%   |
| 121-130        | 1         | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 43.75%  |
| 101-120       | 5         | 31.25%  |
| 161-240       | 2         | 12.5%   |
| More than 240 | 1         | 6.25%   |
| 51-100        | 1         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 16        | 88.89%  |
| 3     | 1         | 5.56%   |
| 0     | 1         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 34.78%  |
| Intel                    | 8         | 34.78%  |
| Qualcomm Atheros         | 2         | 8.7%    |
| TP-Link                  | 1         | 4.35%   |
| Nvidia                   | 1         | 4.35%   |
| Marvell Technology Group | 1         | 4.35%   |
| Broadcom                 | 1         | 4.35%   |
| ASIX Electronics         | 1         | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 12.5%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 8.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 8.33%   |
| Intel Wireless 7260                                               | 2         | 8.33%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 8.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 4.17%   |
| Nvidia MCP61 Ethernet                                             | 1         | 4.17%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 4.17%   |
| Intel Wireless-AC 9260                                            | 1         | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 4.17%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 4.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 4.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 5         | 35.71%  |
| Intel                    | 4         | 28.57%  |
| Qualcomm Atheros         | 2         | 14.29%  |
| TP-Link                  | 1         | 7.14%   |
| Marvell Technology Group | 1         | 7.14%   |
| Broadcom                 | 1         | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 14.29%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 14.29%  |
| Intel Wireless 7260                                        | 2         | 14.29%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 7.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 7.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 7.14%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 1         | 7.14%   |
| Intel Wireless-AC 9260                                     | 1         | 7.14%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]              | 1         | 7.14%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 50%     |
| Realtek Semiconductor | 3         | 30%     |
| Nvidia                | 1         | 10%     |
| ASIX Electronics      | 1         | 10%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 30%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 20%     |
| Nvidia MCP61 Ethernet                                             | 1         | 10%     |
| Intel I211 Gigabit Network Connection                             | 1         | 10%     |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 10%     |
| Intel 82579V Gigabit Network Connection                           | 1         | 10%     |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 10%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 58.33%  |
| Ethernet | 10        | 41.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 59.09%  |
| Ethernet | 9         | 40.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 12        | 70.59%  |
| 2     | 5         | 29.41%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11        | 64.71%  |
| Yes  | 6         | 35.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 3         | 23.08%  |
| Intel                   | 3         | 23.08%  |
| Realtek                 | 2         | 15.38%  |
| Foxconn / Hon Hai       | 2         | 15.38%  |
| Marvell Semiconductor   | 1         | 7.69%   |
| Cambridge Silicon Radio | 1         | 7.69%   |
| ASUSTek Computer        | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 2         | 15.38%  |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 15.38%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 7.69%   |
| Realtek Bluetooth Radio                             | 1         | 7.69%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 7.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 7.69%   |
| Intel Bluetooth wireless interface                  | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |
| ASUS BCM20702A0                                     | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 12        | 54.55%  |
| AMD      | 5         | 22.73%  |
| Nvidia   | 4         | 18.18%  |
| Micronas | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 4         | 14.29%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 3         | 10.71%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 7.14%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 7.14%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                 | 2         | 7.14%   |
| Nvidia MCP61 High Definition Audio                                  | 1         | 3.57%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 3.57%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 3.57%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 3.57%   |
| Micronas BLUE USB Audio 2.0                                         | 1         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 3.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1         | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 3.57%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1         | 3.57%   |
| AMD FCH Azalia Controller                                           | 1         | 3.57%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 40%     |
| SK Hynix            | 2         | 13.33%  |
| Micron Technology   | 2         | 13.33%  |
| Crucial             | 2         | 13.33%  |
| Corsair             | 2         | 13.33%  |
| A-DATA Technology   | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 6.25%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 6.25%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 6.25%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 6.25%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 6.25%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 6.25%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 6.25%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1867MT/s            | 1         | 6.25%   |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s         | 1         | 6.25%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s       | 1         | 6.25%   |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s                | 1         | 6.25%   |
| Corsair RAM VS2GB1333D3 2GB DIMM DDR3 1333MT/s                   | 1         | 6.25%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s            | 1         | 6.25%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 57.14%  |
| DDR3   | 4         | 28.57%  |
| LPDDR3 | 2         | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 50%     |
| Row Of Chips | 4         | 28.57%  |
| DIMM         | 3         | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 46.67%  |
| 8192  | 6         | 40%     |
| 16384 | 1         | 6.67%   |
| 2048  | 1         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 6         | 37.5%   |
| 2400  | 2         | 12.5%   |
| 2133  | 2         | 12.5%   |
| 1867  | 2         | 12.5%   |
| 1600  | 2         | 12.5%   |
| 1333  | 2         | 12.5%   |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| IMC Networks        | 3         | 27.27%  |
| Chicony Electronics | 3         | 27.27%  |
| Quanta              | 2         | 18.18%  |
| Microdia            | 2         | 18.18%  |
| Logitech            | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Quanta HP Wide Vision HD Camera      | 2         | 16.67%  |
| Microdia Integrated_Webcam_HD        | 2         | 16.67%  |
| Logitech QuickCam Pro 9000           | 1         | 8.33%   |
| IMC Networks ov9734_azurewave_camera | 1         | 8.33%   |
| IMC Networks Integrated Camera       | 1         | 8.33%   |
| IMC Networks HD Camera               | 1         | 8.33%   |
| Chicony VGA Webcam                   | 1         | 8.33%   |
| Chicony USB2.0 2M WebCam             | 1         | 8.33%   |
| Chicony USB 5M WebCam                | 1         | 8.33%   |
| Chicony Integrated Camera            | 1         | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device          | 2         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| LighTuning EgisTec_ES603                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12        | 70.59%  |
| 1     | 5         | 29.41%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 80%     |
| Multimedia controller | 1         | 20%     |

