SteamOS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 73

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Valve   | Jupiter                     | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Valve   | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve   | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve   | Jupiter                     | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve   | Jupiter                     | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| Valve   | Jupiter                     | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve   | Jupiter                     | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve   | Jupiter                     | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Valve   | Jupiter                     | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| Valve   | Jupiter                     | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| Dell    | G15 5510                    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve   | Jupiter                     | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve   | Jupiter                     | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve   | Jupiter                     | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve   | Jupiter                     | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve   | Jupiter                     | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve   | Jupiter                     | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve   | Jupiter                     | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve   | Jupiter                     | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve   | Jupiter                     | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve   | Jupiter                     | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP      | Pavilion Gaming Laptop 1... | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve   | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve   | Jupiter                     | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Valve   | Jupiter                     | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve   | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve   | Jupiter                     | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve   | Jupiter                     | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve   | Jupiter                     | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| Valve   | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve   | Jupiter                     | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve   | Jupiter                     | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve   | Jupiter                     | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Valve   | Jupiter                     | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve   | Jupiter                     | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve   | Jupiter                     | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve   | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| HP      | Pavilion Gaming Laptop 1... | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve   | Jupiter                     | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| Valve   | Jupiter                     | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve   | Jupiter                     | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve   | Jupiter                     | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer    | Aspire A315-23              | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung | 950XDB/951XDB/950XDY        | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve   | Jupiter                     | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve   | Jupiter                     | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve   | Jupiter                     | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve   | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve   | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve   | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve   | Jupiter                     | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve   | Jupiter                     | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve   | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve   | Jupiter                     | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve   | Jupiter                     | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve   | Jupiter                     | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve   | Jupiter                     | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve   | Jupiter                     | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve   | Jupiter                     | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve   | Jupiter                     | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve   | Jupiter                     | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve   | Jupiter                     | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve   | Jupiter                     | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve   | Jupiter                     | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve   | Jupiter                     | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve   | Jupiter                     | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve   | Jupiter                     | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve   | Jupiter                     | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve   | Jupiter                     | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve   | Jupiter                     | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve   | Jupiter                     | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve   | Jupiter                     | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve   | Jupiter                     | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.2                  | 31        | 49.21%  |
| SteamOS Snapshot             | 21        | 33.33%  |
| SteamOS 3.1                  | 8         | 12.7%   |
| SteamOS 3.2 (steamdeck-main) | 2         | 3.17%   |
| SteamOS 3.4                  | 1         | 1.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SteamOS | 61        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 26        | 41.27%  |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 25.4%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 10        | 15.87%  |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 7.94%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 5         | 7.94%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 61        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 61        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 61        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 60        | 98.36%  |
| Unknown | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 61        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 52        | 85.25%  |
| fr_FR | 2         | 3.28%   |
| en_GB | 2         | 3.28%   |
| pt_BR | 1         | 1.64%   |
| it_IT | 1         | 1.64%   |
| es_ES | 1         | 1.64%   |
| en_DE | 1         | 1.64%   |
| an_ES | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 60        | 98.36%  |
| EFI  | 1         | 1.64%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 61        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 98.36%  |
| GPT     | 1         | 1.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 98.36%  |
| Yes       | 1         | 1.64%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Valve               | 56        | 91.8%   |
| Hewlett-Packard     | 2         | 3.28%   |
| Samsung Electronics | 1         | 1.64%   |
| Dell                | 1         | 1.64%   |
| Acer                | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Valve Jupiter                       | 56        | 91.8%   |
| Samsung 950XDB/951XDB/950XDY        | 1         | 1.64%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 1         | 1.64%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 1         | 1.64%   |
| Dell G15 5510                       | 1         | 1.64%   |
| Acer Aspire A315-23                 | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Valve Jupiter  | 56        | 91.8%   |
| HP Pavilion    | 2         | 3.28%   |
| Samsung 950XDB | 1         | 1.64%   |
| Dell G15       | 1         | 1.64%   |
| Acer Aspire    | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 44        | 72.13%  |
| Unknown | 12        | 19.67%  |
| 2021    | 3         | 4.92%   |
| 2020    | 1         | 1.64%   |
| 2019    | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 61        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 57        | 93.44%  |
| 4.01-8.0   | 2         | 3.28%   |
| 16.01-24.0 | 2         | 3.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 29        | 45.31%  |
| 3.01-4.0 | 17        | 26.56%  |
| 4.01-8.0 | 12        | 18.75%  |
| 1.01-2.0 | 6         | 9.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 59.68%  |
| 1      | 23        | 37.1%   |
| 4      | 1         | 1.61%   |
| 3      | 1         | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 98.36%  |
| Yes       | 1         | 1.64%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 77.05%  |
| Yes       | 14        | 22.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 28        | 45.9%   |
| Germany     | 9         | 14.75%  |
| UK          | 7         | 11.48%  |
| France      | 3         | 4.92%   |
| Spain       | 2         | 3.28%   |
| Netherlands | 2         | 3.28%   |
| Slovakia    | 1         | 1.64%   |
| Poland      | 1         | 1.64%   |
| Latvia      | 1         | 1.64%   |
| Italy       | 1         | 1.64%   |
| Hungary     | 1         | 1.64%   |
| Greece      | 1         | 1.64%   |
| Czechia     | 1         | 1.64%   |
| Canada      | 1         | 1.64%   |
| Brazil      | 1         | 1.64%   |
| Austria     | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Colorado Springs | 2         | 3.23%   |
| Wokingham        | 1         | 1.61%   |
| Whitley Bay      | 1         | 1.61%   |
| Washington       | 1         | 1.61%   |
| Warsaw           | 1         | 1.61%   |
| Treviso          | 1         | 1.61%   |
| Torre del Mar    | 1         | 1.61%   |
| Thessaloniki     | 1         | 1.61%   |
| Temecula         | 1         | 1.61%   |
| St Louis         | 1         | 1.61%   |
| Spanish Fork     | 1         | 1.61%   |
| Shepperton       | 1         | 1.61%   |
| Seattle          | 1         | 1.61%   |
| San Diego        | 1         | 1.61%   |
| Sacramento       | 1         | 1.61%   |
| Rueil-Malmaison  | 1         | 1.61%   |
| Rohnert Park     | 1         | 1.61%   |
| Riga             | 1         | 1.61%   |
| Reignier-Esery   | 1         | 1.61%   |
| Phoenix          | 1         | 1.61%   |
| Palatine         | 1         | 1.61%   |
| Odenton          | 1         | 1.61%   |
| Oakham           | 1         | 1.61%   |
| Nuremberg        | 1         | 1.61%   |
| Newberg          | 1         | 1.61%   |
| Nashville        | 1         | 1.61%   |
| Mooresville      | 1         | 1.61%   |
| Maplewood        | 1         | 1.61%   |
| Manchester       | 1         | 1.61%   |
| Lodi             | 1         | 1.61%   |
| Leicester        | 1         | 1.61%   |
| Knoxville        | 1         | 1.61%   |
| Klagenfurt       | 1         | 1.61%   |
| Kenosha          | 1         | 1.61%   |
| Kansas City      | 1         | 1.61%   |
| Iserlohn         | 1         | 1.61%   |
| Heerhugowaard    | 1         | 1.61%   |
| Hanau            | 1         | 1.61%   |
| Goochland        | 1         | 1.61%   |
| Germantown       | 1         | 1.61%   |
| Fort Myers       | 1         | 1.61%   |
| Eaubonne         | 1         | 1.61%   |
| Dresden          | 1         | 1.61%   |
| Charlotte        | 1         | 1.61%   |
| Budapest         | 1         | 1.61%   |
| Brno             | 1         | 1.61%   |
| Bremen           | 1         | 1.61%   |
| Breitscheid      | 1         | 1.61%   |
| Bratislava       | 1         | 1.61%   |
| Brantford        | 1         | 1.61%   |
| Bothell          | 1         | 1.61%   |
| Birmingham       | 1         | 1.61%   |
| Berlin           | 1         | 1.61%   |
| Barakaldo        | 1         | 1.61%   |
| Bamberg          | 1         | 1.61%   |
| Atlanta          | 1         | 1.61%   |
| Arbroath         | 1         | 1.61%   |
| Amsterdam        | 1         | 1.61%   |
| Americana        | 1         | 1.61%   |
| Aliso Viejo      | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 28        | 28     | 27.18%  |
| Kingston                       | 24        | 26     | 23.3%   |
| Phison                         | 17        | 17     | 16.5%   |
| Unknown                        | 10        | 11     | 9.71%   |
| O2 Micro                       | 8         | 8      | 7.77%   |
| Silicon Motion                 | 3         | 3      | 2.91%   |
| Samsung Electronics            | 3         | 4      | 2.91%   |
| WDC                            | 2         | 2      | 1.94%   |
| Toshiba                        | 1         | 1      | 0.97%   |
| Solid State Storage Technology | 1         | 1      | 0.97%   |
| SK hynix                       | 1         | 1      | 0.97%   |
| SanDisk                        | 1         | 1      | 0.97%   |
| Lexar 25                       | 1         | 1      | 0.97%   |
| JMicron Technology             | 1         | 1      | 0.97%   |
| External                       | 1         | 2      | 0.97%   |
| ADATA Technology               | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Kingston NVMe SSD Drive 512GB            | 15        | 14.56%  |
| Unknown MMC Card  512GB                  | 13        | 12.62%  |
| Phison NVMe SSD Drive 512GB              | 10        | 9.71%   |
| Unknown                                  | 10        | 9.71%   |
| Kingston NVMe SSD Drive 256GB            | 9         | 8.74%   |
| O2 Micro NVMe SSD Drive 64GB             | 8         | 7.77%   |
| Phison NVMe SSD Drive 256GB              | 7         | 6.8%    |
| Unknown MMC Card  256GB                  | 3         | 2.91%   |
| Silicon Motion NVMe SSD Drive 256GB      | 3         | 2.91%   |
| Unknown MMC Card  64GB                   | 2         | 1.94%   |
| Unknown MMC Card  393GB                  | 2         | 1.94%   |
| Unknown MMC Card  128GB                  | 2         | 1.94%   |
| Samsung NVMe SSD Drive 512GB             | 2         | 1.94%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 0.97%   |
| WDC CH SN530 SDBPTPZ-1T00-1024 930GB     | 1         | 0.97%   |
| Unknown MMC Card  498GB                  | 1         | 0.97%   |
| Unknown MMC Card  32GB                   | 1         | 0.97%   |
| Unknown MMC Card  248GB                  | 1         | 0.97%   |
| Unknown MMC Card  1TB                    | 1         | 0.97%   |
| Unknown MMC Card  196GB                  | 1         | 0.97%   |
| Unknown MMC Card  1048GB                 | 1         | 0.97%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD      | 1         | 0.97%   |
| Solid State Storage NVMe SSD Drive 128GB | 1         | 0.97%   |
| SK hynix NVMe SSD Drive 256GB            | 1         | 0.97%   |
| SanDisk NVMe SSD Drive 512GB             | 1         | 0.97%   |
| Samsung NVMe SSD Drive 1024GB            | 1         | 0.97%   |
| Lexar 25 6GB SSD                         | 1         | 0.97%   |
| JMicron Generic 2TB                      | 1         | 0.97%   |
| External USB3.0 120GB                    | 1         | 0.97%   |
| ADATA NVMe SSD Drive 512GB               | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 1         | 1      | 50%     |
| JMicron Technology | 1         | 1      | 50%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Lexar 25 | 1         | 1      | 100%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 61        | 66     | 60.4%   |
| MMC  | 37        | 39     | 36.63%  |
| HDD  | 2         | 2      | 1.98%   |
| SSD  | 1         | 1      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 61        | 64     | 59.8%   |
| MMC  | 37        | 39     | 36.27%  |
| SAS  | 3         | 4      | 2.94%   |
| SATA | 1         | 1      | 0.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 1.01-2.0   | 1         | 1      | 33.33%  |
| 0.51-1.0   | 1         | 1      | 33.33%  |
| 0.01-0.5   | 1         | 1      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 28        | 45.9%   |
| 101-250    | 21        | 34.43%  |
| 51-100     | 6         | 9.84%   |
| 501-1000   | 5         | 8.2%    |
| 1001-2000  | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 101-250  | 28        | 44.44%  |
| 251-500  | 12        | 19.05%  |
| 21-50    | 12        | 19.05%  |
| 1-20     | 5         | 7.94%   |
| 501-1000 | 3         | 4.76%   |
| 51-100   | 3         | 4.76%   |

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
| Detected | 61        | 107    | 98.39%  |
| Works    | 1         | 1      | 1.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 24        | 37.5%   |
| Phison Electronics             | 17        | 26.56%  |
| O2 Micro                       | 8         | 12.5%   |
| Silicon Motion                 | 3         | 4.69%   |
| Samsung Electronics            | 3         | 4.69%   |
| SanDisk                        | 2         | 3.13%   |
| AMD                            | 2         | 3.13%   |
| Toshiba America Info Systems   | 1         | 1.56%   |
| Solid State Storage Technology | 1         | 1.56%   |
| SK hynix                       | 1         | 1.56%   |
| Intel                          | 1         | 1.56%   |
| ADATA Technology               | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                       | 23        | 35.94%  |
| Phison PS5013 E13 NVMe Controller                       | 17        | 26.56%  |
| O2 Micro Non-Volatile memory controller                 | 8         | 12.5%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller         | 3         | 4.69%   |
| Samsung NVMe SSD Controller 980                         | 3         | 4.69%   |
| AMD FCH SATA Controller [AHCI mode]                     | 2         | 3.13%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller    | 1         | 1.56%   |
| Solid State Storage Non-Volatile memory controller      | 1         | 1.56%   |
| SK hynix Gold P31 SSD                                   | 1         | 1.56%   |
| SanDisk PC SN530 NVMe SSD                               | 1         | 1.56%   |
| SanDisk Non-Volatile memory controller                  | 1         | 1.56%   |
| Kingston Company Company Non-Volatile memory controller | 1         | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]          | 1         | 1.56%   |
| ADATA Non-Volatile memory controller                    | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 61        | 95.31%  |
| SATA | 2         | 3.13%   |
| RAID | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 58        | 95.08%  |
| Intel  | 3         | 4.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 56        | 91.8%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.64%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.64%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 57        | 93.44%  |
| AMD Ryzen 5   | 2         | 3.28%   |
| Intel Core i7 | 1         | 1.64%   |
| Intel Core i5 | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 59        | 96.72%  |
| 8      | 1         | 1.64%   |
| 6      | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 100%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 61        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 98.36%  |
| 0x08900201 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 56        | 91.8%   |
| Zen+      | 1         | 1.64%   |
| Zen 3     | 1         | 1.64%   |
| TigerLake | 1         | 1.64%   |
| KabyLake  | 1         | 1.64%   |
| CometLake | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 58        | 90.63%  |
| Nvidia | 3         | 4.69%   |
| Intel  | 3         | 4.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                    | 56        | 87.5%   |
| Nvidia TU117M                                                        | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                          | 1         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 1.56%   |
| AMD Cezanne                                                          | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 57        | 93.44%  |
| Intel + Nvidia | 2         | 3.28%   |
| 1 x Intel      | 1         | 1.64%   |
| AMD + Nvidia   | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 59        | 96.72%  |
| Proprietary | 2         | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 98.36%  |
| 0.51-1.0   | 1         | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| ANX                  | 54        | 73.97%  |
| Samsung Electronics  | 2         | 2.74%   |
| Philips              | 2         | 2.74%   |
| Goldstar             | 2         | 2.74%   |
| BOE                  | 2         | 2.74%   |
| AU Optronics         | 2         | 2.74%   |
| ZSC                  | 1         | 1.37%   |
| YTH                  | 1         | 1.37%   |
| TCL                  | 1         | 1.37%   |
| Microsoft            | 1         | 1.37%   |
| Hewlett-Packard      | 1         | 1.37%   |
| EXP                  | 1         | 1.37%   |
| Dell                 | 1         | 1.37%   |
| AOC                  | 1         | 1.37%   |
| Ancor Communications | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 54        | 73.97%  |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 1.37%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 1.37%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 1.37%   |
| Samsung Electronics S27HG5x SAM0E10 2560x1440 598x336mm 27.0-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 1.37%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch               | 1         | 1.37%   |
| Philips PHL 326M6V PHLC193 3840x2160 698x398mm 31.6-inch               | 1         | 1.37%   |
| Microsoft Xbox One MSH0001 1920x1080 1210x680mm 54.6-inch              | 1         | 1.37%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch              | 1         | 1.37%   |
| Goldstar LG ULTRAGEAR GSM775B 1920x1080 700x390mm 31.5-inch            | 1         | 1.37%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 1         | 1.37%   |
| EXP EPDP17.1127 EXP9632 1920x1080 1150x650mm 52.0-inch                 | 1         | 1.37%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                      | 1         | 1.37%   |
| BOE LCD Monitor BOE094D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| AU Optronics LCD Monitor AUOED8F 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch          | 1         | 1.37%   |
| AOC AG352UCG6 AOC3525 3440x1440 819x346mm 35.0-inch                    | 1         | 1.37%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 800x1280        | 54        | 73.97%  |
| 1920x1080 (FHD) | 11        | 15.07%  |
| 3840x2160 (4K)  | 3         | 4.11%   |
| 3440x1440       | 2         | 2.74%   |
| 2560x1440 (QHD) | 2         | 2.74%   |
| 1366x768 (WXGA) | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 75%     |
| 15      | 6         | 8.33%   |
| 31      | 2         | 2.78%   |
| 27      | 2         | 2.78%   |
| 72      | 1         | 1.39%   |
| 54      | 1         | 1.39%   |
| 52      | 1         | 1.39%   |
| 35      | 1         | 1.39%   |
| 34      | 1         | 1.39%   |
| 24      | 1         | 1.39%   |
| 23      | 1         | 1.39%   |
| 13      | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 54        | 75%     |
| 301-350     | 6         | 8.33%   |
| 501-600     | 4         | 5.56%   |
| 601-700     | 2         | 2.78%   |
| 1001-1500   | 2         | 2.78%   |
| 801-900     | 1         | 1.39%   |
| 701-800     | 1         | 1.39%   |
| 201-300     | 1         | 1.39%   |
| 1501-2000   | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 0.62  | 54        | 76.06%  |
| 16/9  | 15        | 21.13%  |
| 21/9  | 2         | 2.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 54        | 75%     |
| 101-110        | 6         | 8.33%   |
| 351-500        | 4         | 5.56%   |
| More than 1000 | 3         | 4.17%   |
| 301-350        | 2         | 2.78%   |
| 71-80          | 1         | 1.39%   |
| 251-300        | 1         | 1.39%   |
| 201-250        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54        | 73.97%  |
| 121-160 | 6         | 8.22%   |
| 101-120 | 5         | 6.85%   |
| 51-100  | 5         | 6.85%   |
| 1-50    | 2         | 2.74%   |
| 161-240 | 1         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 81.97%  |
| 2     | 10        | 16.39%  |
| 3     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 60        | 86.96%  |
| ASIX Electronics      | 4         | 5.8%    |
| Intel                 | 2         | 2.9%    |
| Qualcomm Atheros      | 1         | 1.45%   |
| DisplayLink           | 1         | 1.45%   |
| AVM                   | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 56        | 72.73%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 5.19%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 3.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.3%    |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 1.3%    |
| AVM FRITZ!WLAN AC 860                                             | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 58        | 93.55%  |
| Intel                 | 2         | 3.23%   |
| Qualcomm Atheros      | 1         | 1.61%   |
| AVM                   | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 56        | 90.32%  |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.61%   |
| AVM FRITZ!WLAN AC 860                                      | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 64.29%  |
| ASIX Electronics      | 4         | 28.57%  |
| DisplayLink           | 1         | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 40%     |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 26.67%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 20%     |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 6.67%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 81.33%  |
| Ethernet | 14        | 18.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 90.63%  |
| Ethernet | 6         | 9.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 93.44%  |
| 2     | 4         | 6.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 62.9%   |
| Yes  | 23        | 37.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| IMC Networks          | 56        | 91.8%   |
| Realtek Semiconductor | 2         | 3.28%   |
| Intel                 | 2         | 3.28%   |
| Lite-On Technology    | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio               | 56        | 91.8%   |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 1.64%   |
| Realtek Bluetooth Radio                    | 1         | 1.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 1.64%   |
| Intel Bluetooth Device                     | 1         | 1.64%   |
| Intel AX210 Bluetooth                      | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AMD                 | 58        | 86.57%  |
| Nvidia              | 3         | 4.48%   |
| Intel               | 3         | 4.48%   |
| Kingston Technology | 1         | 1.49%   |
| C-Media Electronics | 1         | 1.49%   |
| Blue Microphones    | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller          | 56        | 82.35%  |
| AMD Family 17h/19h HD Audio Controller                         | 2         | 2.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller | 1         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                | 1         | 1.47%   |
| Nvidia Audio device                                            | 1         | 1.47%   |
| Kingston Technology HyperX Quadcast                            | 1         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller    | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                      | 1         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                     | 1         | 1.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)              | 1         | 1.47%   |
| Blue Microphones Yeti Stereo Microphone                        | 1         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller            | 1         | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Realtek Semiconductor       | 2         | 28.57%  |
| Quanta                      | 2         | 28.57%  |
| Unknown                     | 1         | 14.29%  |
| Luxvisions Innotech Limited | 1         | 14.29%  |
| Logitech                    | 1         | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown 720p HD Camera                              | 1         | 14.29%  |
| Realtek WEB CAMERA M9 Pro                           | 1         | 14.29%  |
| Realtek Integrated_Webcam_HD                        | 1         | 14.29%  |
| Quanta VGA WebCam                                   | 1         | 14.29%  |
| Quanta HP Wide Vision HD Camera                     | 1         | 14.29%  |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 14.29%  |
| Logitech CrystalCam                                 | 1         | 14.29%  |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 58        | 95.08%  |
| 1     | 2         | 3.28%   |
| 2     | 1         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 2         | 50%     |
| Multimedia controller | 1         | 25%     |
| Graphics card         | 1         | 25%     |

