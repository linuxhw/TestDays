Kubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

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

Total: 71

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | G3 3779                     | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Apple    | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple    | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple    | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo   | Slim 7 ProX 14ARH7 82V2     | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo   | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| Lenovo   | Slim 7 ProX 14ARH7 82V2     | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Lenovo   | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek  | K50IJ                       | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP       | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP       | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| ASUSTek  | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| MSI      | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer     | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo   | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo   | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo   | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Google   | Bluebird                    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple    | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Lenovo   | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME  | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek  | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer     | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo   | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Acer     | Swift SFX14-41G             | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP       | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI   | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP       | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo   | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP       | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo   | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI   | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell     | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Lenovo   | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP       | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP       | Pavilion Laptop 15-eg0xx... | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| ASUSTek  | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google   | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| HP       | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion   | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo   | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Lenovo   | IdeaPad 3 15IAU7 82RK       | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP       | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Lenovo   | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo   | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek  | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo   | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Samsung  | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo   | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP       | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo   | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP       | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell     | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell     | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell     | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell     | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| ASUSTek  | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Acer     | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Apple    | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI   | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| ASUSTek  | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell     | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI      | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI      | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 46        | 74.19%  |
| 6.2.0-18-generic        | 3         | 4.84%   |
| 6.3.6-custom            | 1         | 1.61%   |
| 6.3.4-060304-generic    | 1         | 1.61%   |
| 6.3.3-060303-generic    | 1         | 1.61%   |
| 6.3.1-060301-generic    | 1         | 1.61%   |
| 6.2.10-060210-generic   | 1         | 1.61%   |
| 6.2.0-21-generic        | 1         | 1.61%   |
| 6.1.12-060112-generic   | 1         | 1.61%   |
| 6.1.0-14-generic        | 1         | 1.61%   |
| 6.1.0-060100rc4-generic | 1         | 1.61%   |
| 5.19.0-42-generic       | 1         | 1.61%   |
| 5.19.0-40-generic       | 1         | 1.61%   |
| 5.19.0-28-generic       | 1         | 1.61%   |
| 5.19.0-21-generic       | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 50        | 80.65%  |
| 5.19.0  | 4         | 6.45%   |
| 6.1.0   | 2         | 3.23%   |
| 6.3.6   | 1         | 1.61%   |
| 6.3.4   | 1         | 1.61%   |
| 6.3.3   | 1         | 1.61%   |
| 6.3.1   | 1         | 1.61%   |
| 6.2.10  | 1         | 1.61%   |
| 6.1.12  | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 51        | 82.26%  |
| 6.3     | 4         | 6.45%   |
| 5.19    | 4         | 6.45%   |
| 6.1     | 3         | 4.84%   |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 58        | 95.08%  |
| KDE   | 2         | 3.28%   |
| GNOME | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 88.52%  |
| Wayland | 7         | 11.48%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 33        | 54.1%   |
| Unknown | 24        | 39.34%  |
| GDM3    | 3         | 4.92%   |
| LightDM | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 28        | 45.9%   |
| de_DE  | 6         | 9.84%   |
| ru_RU  | 3         | 4.92%   |
| pl_PL  | 3         | 4.92%   |
| fr_FR  | 3         | 4.92%   |
| it_IT  | 2         | 3.28%   |
| en_NZ  | 2         | 3.28%   |
| en_GB  | 2         | 3.28%   |
| pt_PT  | 1         | 1.64%   |
| pt_BR  | 1         | 1.64%   |
| nl_NL  | 1         | 1.64%   |
| hu_HU  | 1         | 1.64%   |
| fr_BE  | 1         | 1.64%   |
| es_ES  | 1         | 1.64%   |
| es_CR  | 1         | 1.64%   |
| es_CL  | 1         | 1.64%   |
| es_419 | 1         | 1.64%   |
| en_IN  | 1         | 1.64%   |
| en_AU  | 1         | 1.64%   |
| C      | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 33        | 53.23%  |
| EFI  | 29        | 46.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 70.97%  |
| Tmpfs   | 9         | 14.52%  |
| Btrfs   | 4         | 6.45%   |
| Overlay | 3         | 4.84%   |
| Zfs     | 2         | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 37        | 60.66%  |
| Unknown | 24        | 39.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 77.05%  |
| Yes       | 14        | 22.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 26.23%  |
| Hewlett-Packard     | 10        | 16.39%  |
| ASUSTek Computer    | 8         | 13.11%  |
| Dell                | 6         | 9.84%   |
| Acer                | 4         | 6.56%   |
| MSI                 | 3         | 4.92%   |
| HUAWEI              | 3         | 4.92%   |
| Gigabyte Technology | 3         | 4.92%   |
| Apple               | 3         | 4.92%   |
| Google              | 2         | 3.28%   |
| Samsung Electronics | 1         | 1.64%   |
| Medion              | 1         | 1.64%   |
| BOSGAME             | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Dell G3 3779                                       | 2         | 3.28%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI           | 2         | 3.28%   |
| Samsung 950XED                                     | 1         | 1.64%   |
| MSI Titan GT77HX 13VH                              | 1         | 1.64%   |
| MSI Raider GE67HX 12UGS                            | 1         | 1.64%   |
| MSI Bravo 17 A4DDK                                 | 1         | 1.64%   |
| Medion E11201                                      | 1         | 1.64%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW        | 1         | 1.64%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01             | 1         | 1.64%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00              | 1         | 1.64%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE                | 1         | 1.64%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100               | 1         | 1.64%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW               | 1         | 1.64%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000               | 1         | 1.64%   |
| Lenovo ThinkPad E14 Gen 3 20YDS02D00               | 1         | 1.64%   |
| Lenovo ThinkBook 14 G4 ABA 21DK                    | 1         | 1.64%   |
| Lenovo Slim 7 ProX 14ARH7 82V2                     | 1         | 1.64%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                   | 1         | 1.64%   |
| Lenovo IdeaPad Y700-15ISK 80NV                     | 1         | 1.64%   |
| Lenovo IdeaPad 700-17ISK 80RV                      | 1         | 1.64%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN                   | 1         | 1.64%   |
| Lenovo IdeaPad 3 15IAU7 82RK                       | 1         | 1.64%   |
| Lenovo IdeaPad 3 15ALC6 82MF                       | 1         | 1.64%   |
| HUAWEI NBD-WXX9                                    | 1         | 1.64%   |
| HUAWEI HN-WX9X                                     | 1         | 1.64%   |
| HUAWEI BOHB-WAX9                                   | 1         | 1.64%   |
| HP ZBook Studio 15.6 inch G8 Mobile Workstation PC | 1         | 1.64%   |
| HP ProBook 650 G1                                  | 1         | 1.64%   |
| HP ProBook 440 G5                                  | 1         | 1.64%   |
| HP Pavilion Notebook                               | 1         | 1.64%   |
| HP Pavilion Laptop 15-eh1xxx                       | 1         | 1.64%   |
| HP Pavilion Laptop 15-eg0xxx                       | 1         | 1.64%   |
| HP Laptop 15-da2xxx                                | 1         | 1.64%   |
| HP ENVY TS 15                                      | 1         | 1.64%   |
| HP EliteBook 865 16 inch G9 Notebook PC            | 1         | 1.64%   |
| HP Compaq CQ58                                     | 1         | 1.64%   |
| Google Lars                                        | 1         | 1.64%   |
| Google Bluebird                                    | 1         | 1.64%   |
| Gigabyte G5 KD                                     | 1         | 1.64%   |
| Gigabyte G5 GE                                     | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 8         | 13.11%  |
| Lenovo IdeaPad    | 5         | 8.2%    |
| HP Pavilion       | 3         | 4.92%   |
| Acer Aspire       | 3         | 4.92%   |
| HP ProBook        | 2         | 3.28%   |
| Gigabyte G5       | 2         | 3.28%   |
| Dell Latitude     | 2         | 3.28%   |
| Dell G3           | 2         | 3.28%   |
| ASUS ROG          | 2         | 3.28%   |
| ASUS ASUS         | 2         | 3.28%   |
| Samsung 950XED    | 1         | 1.64%   |
| MSI Titan         | 1         | 1.64%   |
| MSI Raider        | 1         | 1.64%   |
| MSI Bravo         | 1         | 1.64%   |
| Medion E11201     | 1         | 1.64%   |
| Lenovo ThinkBook  | 1         | 1.64%   |
| Lenovo Slim       | 1         | 1.64%   |
| Lenovo Legion     | 1         | 1.64%   |
| HUAWEI NBD-WXX9   | 1         | 1.64%   |
| HUAWEI HN-WX9X    | 1         | 1.64%   |
| HUAWEI BOHB-WAX9  | 1         | 1.64%   |
| HP ZBook          | 1         | 1.64%   |
| HP Laptop         | 1         | 1.64%   |
| HP ENVY           | 1         | 1.64%   |
| HP EliteBook      | 1         | 1.64%   |
| HP Compaq         | 1         | 1.64%   |
| Google Lars       | 1         | 1.64%   |
| Google Bluebird   | 1         | 1.64%   |
| Gigabyte AORUS    | 1         | 1.64%   |
| Dell Precision    | 1         | 1.64%   |
| Dell Inspiron     | 1         | 1.64%   |
| BOSGAME B95       | 1         | 1.64%   |
| ASUS Zenbook      | 1         | 1.64%   |
| ASUS X51RL        | 1         | 1.64%   |
| ASUS VivoBook     | 1         | 1.64%   |
| ASUS K50IJ        | 1         | 1.64%   |
| Apple MacBookPro9 | 1         | 1.64%   |
| Apple MacBookPro8 | 1         | 1.64%   |
| Apple MacBookAir5 | 1         | 1.64%   |
| Acer Swift        | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 16        | 26.23%  |
| 2021 | 15        | 24.59%  |
| 2023 | 5         | 8.2%    |
| 2019 | 4         | 6.56%   |
| 2012 | 4         | 6.56%   |
| 2020 | 3         | 4.92%   |
| 2016 | 3         | 4.92%   |
| 2018 | 2         | 3.28%   |
| 2017 | 2         | 3.28%   |
| 2013 | 2         | 3.28%   |
| 2015 | 1         | 1.64%   |
| 2014 | 1         | 1.64%   |
| 2011 | 1         | 1.64%   |
| 2009 | 1         | 1.64%   |
| 2007 | 1         | 1.64%   |

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
| Disabled | 56        | 91.8%   |
| Enabled  | 5         | 8.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 96.72%  |
| Yes  | 2         | 3.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 29.51%  |
| 4.01-8.0    | 12        | 19.67%  |
| 16.01-24.0  | 11        | 18.03%  |
| 32.01-64.0  | 8         | 13.11%  |
| 3.01-4.0    | 7         | 11.48%  |
| 24.01-32.0  | 2         | 3.28%   |
| 64.01-256.0 | 2         | 3.28%   |
| 2.01-3.0    | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 18        | 29.03%  |
| 2.01-3.0  | 17        | 27.42%  |
| 1.01-2.0  | 12        | 19.35%  |
| 3.01-4.0  | 11        | 17.74%  |
| 8.01-16.0 | 4         | 6.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 75.41%  |
| 2      | 12        | 19.67%  |
| 3      | 3         | 4.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 85.25%  |
| Yes       | 9         | 14.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 70.49%  |
| No        | 18        | 29.51%  |

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
| Yes       | 53        | 86.89%  |
| No        | 8         | 13.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 11        | 18.03%  |
| Germany      | 9         | 14.75%  |
| Poland       | 4         | 6.56%   |
| Belgium      | 4         | 6.56%   |
| UK           | 3         | 4.92%   |
| Russia       | 3         | 4.92%   |
| France       | 3         | 4.92%   |
| Portugal     | 2         | 3.28%   |
| New Zealand  | 2         | 3.28%   |
| Netherlands  | 2         | 3.28%   |
| Italy        | 2         | 3.28%   |
| India        | 2         | 3.28%   |
| Turkey       | 1         | 1.64%   |
| Sweden       | 1         | 1.64%   |
| Spain        | 1         | 1.64%   |
| Saudi Arabia | 1         | 1.64%   |
| Mexico       | 1         | 1.64%   |
| Lithuania    | 1         | 1.64%   |
| Hungary      | 1         | 1.64%   |
| Costa Rica   | 1         | 1.64%   |
| Colombia     | 1         | 1.64%   |
| Chile        | 1         | 1.64%   |
| Canada       | 1         | 1.64%   |
| Brazil       | 1         | 1.64%   |
| Australia    | 1         | 1.64%   |
| Argentina    | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Munich                  | 2         | 3.28%   |
| Brussels                | 2         | 3.28%   |
| Berlin                  | 2         | 3.28%   |
| West Des Moines         | 1         | 1.64%   |
| Warsaw                  | 1         | 1.64%   |
| Waianae                 | 1         | 1.64%   |
| Vsevolozhsk             | 1         | 1.64%   |
| Viña del Mar           | 1         | 1.64%   |
| Vilnius                 | 1         | 1.64%   |
| Villa Dominico          | 1         | 1.64%   |
| Theydon Bois            | 1         | 1.64%   |
| Szczecin                | 1         | 1.64%   |
| Sydney                  | 1         | 1.64%   |
| Sumter                  | 1         | 1.64%   |
| Stavropol               | 1         | 1.64%   |
| Sherbrooke              | 1         | 1.64%   |
| Salt Lake City          | 1         | 1.64%   |
| Saint-Georges-sur-Meuse | 1         | 1.64%   |
| Roubaix                 | 1         | 1.64%   |
| Rewal                   | 1         | 1.64%   |
| Remeteszolos            | 1         | 1.64%   |
| Raleigh                 | 1         | 1.64%   |
| Poznan                  | 1         | 1.64%   |
| Portimao                | 1         | 1.64%   |
| Phoenix                 | 1         | 1.64%   |
| Philadelphia            | 1         | 1.64%   |
| Paris                   | 1         | 1.64%   |
| Oldenburg               | 1         | 1.64%   |
| Olathe                  | 1         | 1.64%   |
| Nashik                  | 1         | 1.64%   |
| Münster                | 1         | 1.64%   |
| Moseley                 | 1         | 1.64%   |
| Mönchengladbach        | 1         | 1.64%   |
| Medellín               | 1         | 1.64%   |
| Madrid                  | 1         | 1.64%   |
| Maastricht              | 1         | 1.64%   |
| Lisbon                  | 1         | 1.64%   |
| Krasnoyarsk             | 1         | 1.64%   |
| Jeddah                  | 1         | 1.64%   |
| Istanbul                | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 15        | 18     | 19.23%  |
| Micron Technology       | 7         | 7      | 8.97%   |
| SK hynix                | 6         | 6      | 7.69%   |
| Sandisk                 | 5         | 5      | 6.41%   |
| Intel                   | 5         | 6      | 6.41%   |
| WDC                     | 4         | 4      | 5.13%   |
| Toshiba                 | 4         | 4      | 5.13%   |
| Phison Electronics      | 4         | 4      | 5.13%   |
| Crucial                 | 4         | 4      | 5.13%   |
| Unknown                 | 3         | 3      | 3.85%   |
| Seagate                 | 3         | 3      | 3.85%   |
| Kingston                | 3         | 3      | 3.85%   |
| UMIS                    | 2         | 3      | 2.56%   |
| Silicon Motion          | 2         | 2      | 2.56%   |
| WALRAM                  | 1         | 1      | 1.28%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.28%   |
| SSSTC                   | 1         | 1      | 1.28%   |
| SSDPR-CX                | 1         | 1      | 1.28%   |
| Solid State Storage     | 1         | 1      | 1.28%   |
| Phison                  | 1         | 1      | 1.28%   |
| Patriot                 | 1         | 1      | 1.28%   |
| Lenovo                  | 1         | 1      | 1.28%   |
| JMicron Technology      | 1         | 1      | 1.28%   |
| Hitachi                 | 1         | 1      | 1.28%   |
| A-DATA Technology       | 1         | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Phison E16 PCIe4 NVMe Controller 1TB                | 3         | 3.85%   |
| Unknown MMC Card  32GB                              | 2         | 2.56%   |
| UMIS RPJTJ512MGE1QDQ 512GB                          | 2         | 2.56%   |
| SanDisk NVMe SSD Drive 2TB                          | 2         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 2.56%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 2         | 2.56%   |
| Intel SSD 660P Series 512GB                         | 2         | 2.56%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1         | 1.28%   |
| WDC WD16 00AVBB-63SYA0 160GB                        | 1         | 1.28%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1.28%   |
| WDC WD10 JPVX-00JC3T0 1TB                           | 1         | 1.28%   |
| WALRAM 240G                                         | 1         | 1.28%   |
| Unknown Biwin  64GB                                 | 1         | 1.28%   |
| Union Memory (Shenzhen) RPFTJ256PDD2MWX 256GB       | 1         | 1.28%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 1.28%   |
| Toshiba MQ02ABF100 1TB                              | 1         | 1.28%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1.28%   |
| Toshiba KXG60ZNV512G 512GB                          | 1         | 1.28%   |
| SSSTC CL4-4D512-Q79 512GB                           | 1         | 1.28%   |
| SSDPR-CX 400-256-G2 256GB                           | 1         | 1.28%   |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 1.28%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 1         | 1.28%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 1         | 1.28%   |
| SK hynix HFS256G32MND-2900A 256GB SSD               | 1         | 1.28%   |
| SK hynix HFM512GD3JX016N 512GB                      | 1         | 1.28%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 1.28%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 1         | 1.28%   |
| Silicon Motion PCIe-8 SSD 256GB                     | 1         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1.28%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1.28%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.28%   |
| Sandisk WDC WDS240G2G0C-00AJM0 240GB                | 1         | 1.28%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.28%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                 | 1         | 1.28%   |
| Samsung SSD 980 500GB                               | 1         | 1.28%   |
| Samsung SSD 870 QVO 1TB                             | 1         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 1.28%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 1.28%   |
| Samsung MZVLQ512HBLU-00B 512GB                      | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 33.33%  |
| Seagate | 3         | 3      | 33.33%  |
| Toshiba | 2         | 2      | 22.22%  |
| Hitachi | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 4         | 4      | 23.53%  |
| Micron Technology   | 2         | 2      | 11.76%  |
| Kingston            | 2         | 2      | 11.76%  |
| Intel               | 2         | 3      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| SK hynix            | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Patriot             | 1         | 1      | 5.88%   |
| Lenovo              | 1         | 1      | 5.88%   |
| JMicron Technology  | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 41        | 51     | 58.57%  |
| SSD     | 15        | 18     | 21.43%  |
| HDD     | 9         | 9      | 12.86%  |
| MMC     | 3         | 3      | 4.29%   |
| Unknown | 2         | 2      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 41        | 51     | 58.57%  |
| SATA | 22        | 25     | 31.43%  |
| SAS  | 4         | 4      | 5.71%   |
| MMC  | 3         | 3      | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 17     | 63.64%  |
| 0.51-1.0   | 6         | 8      | 27.27%  |
| 1.01-2.0   | 2         | 2      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 27.87%  |
| 501-1000       | 13        | 21.31%  |
| 251-500        | 10        | 16.39%  |
| 1001-2000      | 7         | 11.48%  |
| 1-20           | 4         | 6.56%   |
| More than 3000 | 3         | 4.92%   |
| 2001-3000      | 3         | 4.92%   |
| 21-50          | 2         | 3.28%   |
| 51-100         | 2         | 3.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 15        | 23.44%  |
| 1-20           | 15        | 23.44%  |
| 101-250        | 11        | 17.19%  |
| 51-100         | 7         | 10.94%  |
| 251-500        | 6         | 9.38%   |
| 1001-2000      | 6         | 9.38%   |
| 501-1000       | 3         | 4.69%   |
| More than 3000 | 1         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 38        | 56     | 61.29%  |
| Works    | 23        | 26     | 37.1%   |
| Malfunc  | 1         | 1      | 1.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 29        | 35.8%   |
| Samsung Electronics            | 14        | 17.28%  |
| AMD                            | 8         | 9.88%   |
| SK hynix                       | 5         | 6.17%   |
| Phison Electronics             | 5         | 6.17%   |
| Micron Technology              | 5         | 6.17%   |
| SanDisk                        | 4         | 4.94%   |
| Union Memory (Shenzhen)        | 3         | 3.7%    |
| Toshiba America Info Systems   | 2         | 2.47%   |
| Solid State Storage Technology | 2         | 2.47%   |
| Silicon Motion                 | 2         | 2.47%   |
| Kingston Technology Company    | 1         | 1.23%   |
| ADATA Technology               | 1         | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 8.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 5.88%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 5.88%   |
| Micron NVMe Storage Controller                                                 | 5         | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 5.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 4.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 3.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.53%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 2         | 2.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.35%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.35%   |
| Intel SSD 660P Series                                                          | 2         | 2.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 2.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.35%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.35%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1.18%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.18%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.18%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.18%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.18%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.18%   |
| Samsung NVMe SSD Controller PM9B1                                              | 1         | 1.18%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.18%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.18%   |
| Intel SATA controller                                                          | 1         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 41        | 51.9%   |
| SATA | 34        | 43.04%  |
| RAID | 3         | 3.8%    |
| IDE  | 1         | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 67.21%  |
| AMD    | 20        | 32.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 6.56%   |
| AMD Ryzen 7 5825U with Radeon Graphics      | 3         | 4.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 3.28%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 3.28%   |
| AMD Ryzen 7 6800H with Radeon Graphics      | 2         | 3.28%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.64%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 1.64%   |
| Intel N95                                   | 1         | 1.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.64%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.64%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.64%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 1.64%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.64%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.64%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.64%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.64%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.64%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.64%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.64%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.64%   |
| Intel Core i3-6157U CPU @ 2.40GHz           | 1         | 1.64%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.64%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 1.64%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.64%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 1         | 1.64%   |
| Intel 13th Gen Core i9-13980HX              | 1         | 1.64%   |
| Intel 13th Gen Core i7-1365U                | 1         | 1.64%   |
| Intel 12th Gen Core i7-12800HX              | 1         | 1.64%   |
| Intel 12th Gen Core i7-1260P                | 1         | 1.64%   |
| Intel 12th Gen Core i5-12500H               | 1         | 1.64%   |
| Intel 12th Gen Core i5-1235U                | 1         | 1.64%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 1         | 1.64%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz     | 1         | 1.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 13        | 21.31%  |
| Intel Core i7           | 10        | 16.39%  |
| Intel Core i5           | 10        | 16.39%  |
| AMD Ryzen 7             | 8         | 13.11%  |
| AMD Ryzen 5             | 8         | 13.11%  |
| Intel Celeron           | 4         | 6.56%   |
| AMD Ryzen 9             | 3         | 4.92%   |
| Intel Pentium Dual-Core | 1         | 1.64%   |
| Intel Pentium           | 1         | 1.64%   |
| Intel Core i3           | 1         | 1.64%   |
| Intel Core 2 Duo        | 1         | 1.64%   |
| AMD A4                  | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 17        | 27.87%  |
| 2      | 15        | 24.59%  |
| 8      | 13        | 21.31%  |
| 6      | 10        | 16.39%  |
| 12     | 2         | 3.28%   |
| 10     | 2         | 3.28%   |
| 24     | 1         | 1.64%   |
| 16     | 1         | 1.64%   |

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
| 2      | 51        | 83.61%  |
| 1      | 10        | 16.39%  |

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
| Unknown    | 49        | 79.03%  |
| 0x0a50000c | 5         | 8.06%   |
| 0x0a404102 | 4         | 6.45%   |
| 0x90672    | 1         | 1.61%   |
| 0x0a404101 | 1         | 1.61%   |
| 0x08600104 | 1         | 1.61%   |
| 0x08108109 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 16        | 26.23%  |
| KabyLake         | 8         | 13.11%  |
| Zen 3            | 7         | 11.48%  |
| Skylake          | 6         | 9.84%   |
| IvyBridge        | 4         | 6.56%   |
| Alderlake Hybrid | 4         | 6.56%   |
| TigerLake        | 3         | 4.92%   |
| SandyBridge      | 2         | 3.28%   |
| Haswell          | 2         | 3.28%   |
| CometLake        | 2         | 3.28%   |
| Zen+             | 1         | 1.64%   |
| Zen 2            | 1         | 1.64%   |
| Puma             | 1         | 1.64%   |
| Penryn           | 1         | 1.64%   |
| Goldmont plus    | 1         | 1.64%   |
| Goldmont         | 1         | 1.64%   |
| Core             | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 46.51%  |
| Nvidia | 24        | 27.91%  |
| AMD    | 22        | 25.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt [Radeon 680M]                                               | 6         | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 4.6%    |
| AMD Lucienne                                                              | 4         | 4.6%    |
| AMD Barcelo                                                               | 4         | 4.6%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 3.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 3.45%   |
| Intel HD Graphics 530                                                     | 3         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 3.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 3.45%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 2.3%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 2.3%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 2         | 2.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 2.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 2.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.3%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                      | 1         | 1.15%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 1.15%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.15%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.15%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 1.15%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 1.15%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.15%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 1.15%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 1.15%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                  | 1         | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.15%   |
| Nvidia AD104M [GeForce RTX 4080 Max-Q / Mobile]                           | 1         | 1.15%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.15%   |
| Intel Raptor Lake-S UHD Graphics                                          | 1         | 1.15%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.15%   |
| Intel Iris Graphics 550                                                   | 1         | 1.15%   |
| Intel HD Graphics 630                                                     | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 32.79%  |
| Intel + Nvidia | 18        | 29.51%  |
| 1 x AMD        | 14        | 22.95%  |
| AMD + Nvidia   | 6         | 9.84%   |
| Other          | 1         | 1.64%   |
| 2 x AMD        | 1         | 1.64%   |
| Intel + AMD    | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 40        | 64.52%  |
| Proprietary | 21        | 33.87%  |
| Unknown     | 1         | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 66.13%  |
| 3.01-4.0   | 8         | 12.9%   |
| 0.51-1.0   | 4         | 6.45%   |
| 0.01-0.5   | 4         | 6.45%   |
| 1.01-2.0   | 3         | 4.84%   |
| 7.01-8.0   | 2         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 20.83%  |
| BOE                     | 14        | 19.44%  |
| Samsung Electronics     | 9         | 12.5%   |
| Chimei Innolux          | 9         | 12.5%   |
| LG Display              | 4         | 5.56%   |
| Goldstar                | 4         | 5.56%   |
| Apple                   | 3         | 4.17%   |
| Sharp                   | 2         | 2.78%   |
| PANDA                   | 2         | 2.78%   |
| UGD                     | 1         | 1.39%   |
| Panasonic               | 1         | 1.39%   |
| LOE                     | 1         | 1.39%   |
| Lenovo                  | 1         | 1.39%   |
| KDC                     | 1         | 1.39%   |
| KDB                     | 1         | 1.39%   |
| Denver                  | 1         | 1.39%   |
| Dell                    | 1         | 1.39%   |
| CSO                     | 1         | 1.39%   |
| Chi Mei Optoelectronics | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 4.17%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 2.78%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 1.39%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 1.39%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 1         | 1.39%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 1.39%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 1.39%   |
| PANDA LCD Monitor NCP003F 1920x1080 344x194mm 15.5-inch               | 1         | 1.39%   |
| Panasonic TV MEIA081 1280x720 698x392mm 31.5-inch                     | 1         | 1.39%   |
| LOE LOEWE HDMI TV LOE0610 1280x720 700x394mm 31.6-inch                | 1         | 1.39%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| Lenovo P24h-2L LEN62B2 2560x1440 527x296mm 23.8-inch                  | 1         | 1.39%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 1.39%   |
| KDB LCD Monitor KDB0101 1366x768 256x144mm 11.6-inch                  | 1         | 1.39%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1         | 1.39%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1         | 1.39%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                   | 1         | 1.39%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 800x340mm 34.2-inch           | 1         | 1.39%   |
| Denver M24-FHD-165 LHC2400 1920x1080 527x296mm 23.8-inch              | 1         | 1.39%   |
| Dell E2318HX DELF097 1920x1080 509x286mm 23.0-inch                    | 1         | 1.39%   |
| CSO LCD Monitor CSO1410 3072x1920 312x195mm 14.5-inch                 | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x194mm 15.5-inch       | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN153E 1920x1080 344x193mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 32        | 47.76%  |
| 1366x768 (WXGA)   | 12        | 17.91%  |
| 2560x1440 (QHD)   | 5         | 7.46%   |
| 3840x2160 (4K)    | 2         | 2.99%   |
| 2560x1600         | 2         | 2.99%   |
| 2560x1080         | 2         | 2.99%   |
| 1600x900 (HD+)    | 2         | 2.99%   |
| 3840x2400         | 1         | 1.49%   |
| 3440x1440         | 1         | 1.49%   |
| 3072x1920         | 1         | 1.49%   |
| 2880x1800         | 1         | 1.49%   |
| 2160x1440         | 1         | 1.49%   |
| 1920x540          | 1         | 1.49%   |
| 1920x1200 (WUXGA) | 1         | 1.49%   |
| 1440x900 (WXGA+)  | 1         | 1.49%   |
| 1280x800 (WXGA)   | 1         | 1.49%   |
| 1280x720 (HD)     | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 42.25%  |
| 17      | 8         | 11.27%  |
| 13      | 8         | 11.27%  |
| 14      | 5         | 7.04%   |
| 23      | 4         | 5.63%   |
| 16      | 4         | 5.63%   |
| 11      | 3         | 4.23%   |
| 34      | 2         | 2.82%   |
| 31      | 2         | 2.82%   |
| 72      | 1         | 1.41%   |
| 40      | 1         | 1.41%   |
| 24      | 1         | 1.41%   |
| 20      | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 61.97%  |
| 351-400     | 9         | 12.68%  |
| 501-600     | 5         | 7.04%   |
| 201-300     | 5         | 7.04%   |
| 701-800     | 2         | 2.82%   |
| 601-700     | 2         | 2.82%   |
| 801-900     | 1         | 1.41%   |
| 401-500     | 1         | 1.41%   |
| 1501-2000   | 1         | 1.41%   |
| Unknown     | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 52        | 82.54%  |
| 16/10 | 8         | 12.7%   |
| 21/9  | 2         | 3.17%   |
| 3/2   | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 42.25%  |
| 81-90          | 11        | 15.49%  |
| 121-130        | 8         | 11.27%  |
| 201-250        | 5         | 7.04%   |
| 351-500        | 4         | 5.63%   |
| 111-120        | 4         | 5.63%   |
| 51-60          | 3         | 4.23%   |
| More than 1000 | 1         | 1.41%   |
| 71-80          | 1         | 1.41%   |
| 151-200        | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |
| 91-100         | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 51.43%  |
| 51-100        | 12        | 17.14%  |
| 101-120       | 9         | 12.86%  |
| 161-240       | 7         | 10%     |
| More than 240 | 4         | 5.71%   |
| 1-50          | 1         | 1.43%   |
| Unknown       | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 78.69%  |
| 2     | 11        | 18.03%  |
| 3     | 1         | 1.64%   |
| 0     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 42.22%  |
| Intel                 | 30        | 33.33%  |
| MediaTek              | 9         | 10%     |
| Qualcomm Atheros      | 4         | 4.44%   |
| Broadcom              | 4         | 4.44%   |
| Samsung Electronics   | 1         | 1.11%   |
| Ralink                | 1         | 1.11%   |
| Lenovo                | 1         | 1.11%   |
| Hewlett-Packard       | 1         | 1.11%   |
| Broadcom Limited      | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 21        | 19.44%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 5.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 4.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 2.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.85%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 1.85%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.85%   |
| Intel Wireless 8260                                                     | 2         | 1.85%   |
| Intel Wireless 7260                                                     | 2         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.85%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Lenovo USB-C Dock Ethernet                                              | 1         | 0.93%   |
| Intel Wireless 7265                                                     | 1         | 0.93%   |
| Intel Wireless 3165                                                     | 1         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.93%   |
| Intel Ethernet Controller I225-V                                        | 1         | 0.93%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.93%   |
| Intel Ethernet Connection (14) I219-V                                   | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 48.39%  |
| Realtek Semiconductor | 13        | 20.97%  |
| MediaTek              | 9         | 14.52%  |
| Qualcomm Atheros      | 4         | 6.45%   |
| Broadcom              | 3         | 4.84%   |
| Ralink                | 1         | 1.61%   |
| Hewlett-Packard       | 1         | 1.61%   |
| Broadcom Limited      | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 9.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 8.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 6.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 4.84%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 4.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 4.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.23%   |
| Intel Wireless 8260                                                     | 2         | 3.23%   |
| Intel Wireless 7260                                                     | 2         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 3.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.61%   |
| Intel Wireless 7265                                                     | 1         | 1.61%   |
| Intel Wireless 3165                                                     | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.61%   |
| Intel Alder Lake-U CNVi: Wireless-AC                                    | 1         | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1         | 1.61%   |
| Intel 700 Series Chipset Family Wi-Fi                                   | 1         | 1.61%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.61%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 71.11%  |
| Intel                 | 7         | 15.56%  |
| Broadcom              | 3         | 6.67%   |
| Samsung Electronics   | 1         | 2.22%   |
| Qualcomm Atheros      | 1         | 2.22%   |
| Lenovo                | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 45.65%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 8.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 4.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.17%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.17%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 2.17%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.17%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 59.22%  |
| Ethernet | 42        | 40.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 85.48%  |
| Ethernet | 9         | 14.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 65.57%  |
| 1     | 21        | 34.43%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 70.49%  |
| Yes  | 18        | 29.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 52.83%  |
| Realtek Semiconductor | 11        | 20.75%  |
| IMC Networks          | 4         | 7.55%   |
| Lite-On Technology    | 3         | 5.66%   |
| Apple                 | 3         | 5.66%   |
| Foxconn / Hon Hai     | 2         | 3.77%   |
| Realtek               | 1         | 1.89%   |
| Broadcom              | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 11        | 20.75%  |
| Intel Bluetooth wireless interface             | 8         | 15.09%  |
| Intel Bluetooth Device                         | 5         | 9.43%   |
| Intel AX201 Bluetooth                          | 5         | 9.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 7.55%   |
| IMC Networks Wireless_Device                   | 4         | 7.55%   |
| Intel AX200 Bluetooth                          | 3         | 5.66%   |
| Lite-On Wireless_Device                        | 2         | 3.77%   |
| Intel AX210 Bluetooth                          | 2         | 3.77%   |
| Realtek Bluetooth Radio                        | 1         | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.89%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.89%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.89%   |
| Broadcom BCM20702A0                            | 1         | 1.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 1.89%   |
| Apple Bluetooth USB Host Controller            | 1         | 1.89%   |
| Apple Bluetooth Host Controller                | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 50.63%  |
| AMD                   | 21        | 26.58%  |
| Nvidia                | 14        | 17.72%  |
| Hewlett-Packard       | 2         | 2.53%   |
| Realtek Semiconductor | 1         | 1.27%   |
| Lenovo                | 1         | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 19.19%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 10.1%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.05%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 5.05%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 4.04%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.03%   |
| Nvidia Audio device                                                        | 3         | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 3.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 2.02%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.01%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.01%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 1         | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.01%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.01%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.01%   |
| Hewlett-Packard USB Audio                                                  | 1         | 1.01%   |
| Hewlett-Packard HyperX Cloud Alpha Wireless                                | 1         | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.01%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.01%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 38.89%  |
| SK hynix            | 8         | 22.22%  |
| Micron Technology   | 5         | 13.89%  |
| Ramaxel Technology  | 3         | 8.33%   |
| Kingston            | 2         | 5.56%   |
| Unknown (ABCD)      | 1         | 2.78%   |
| Crucial             | 1         | 2.78%   |
| Corsair             | 1         | 2.78%   |
| 4ea5                | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 7.89%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 7.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 2.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.63%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 2.63%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 2.63%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 2.63%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.63%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.63%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 2.63%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.63%   |
| Samsung RAM K4F6E3S4HM-MGCJ 2GB LPDDR4 2400MT/s                  | 1         | 2.63%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.63%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 2.63%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 2.63%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s         | 1         | 2.63%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.63%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 1         | 2.63%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.63%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.63%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Kingston RAM 9905703-002.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 2.63%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.63%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 2.63%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 2.63%   |
| 4ea5 RAM K4F6E3S4HM-MGCJ 2GB LPDDR4 2400MT/s                     | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 48.28%  |
| LPDDR5 | 5         | 17.24%  |
| DDR3   | 4         | 13.79%  |
| LPDDR4 | 3         | 10.34%  |
| DDR5   | 3         | 10.34%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 76.67%  |
| Row Of Chips | 6         | 20%     |
| Unknown      | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 60%     |
| 4096  | 7         | 23.33%  |
| 16384 | 3         | 10%     |
| 32768 | 1         | 3.33%   |
| 2048  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 31.03%  |
| 6400  | 5         | 17.24%  |
| 2400  | 4         | 13.79%  |
| 4800  | 3         | 10.34%  |
| 1600  | 3         | 10.34%  |
| 2667  | 2         | 6.9%    |
| 4267  | 1         | 3.45%   |
| 2133  | 1         | 3.45%   |
| 1333  | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon PIXMA MX490 Series | 1         | 100%    |

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
| Chicony Electronics                    | 10        | 20%     |
| Quanta                                 | 8         | 16%     |
| Acer                                   | 5         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 4         | 8%      |
| Syntek                                 | 3         | 6%      |
| Realtek Semiconductor                  | 3         | 6%      |
| Bison Electronics                      | 3         | 6%      |
| Apple                                  | 3         | 6%      |
| Sunplus Innovation Technology          | 2         | 4%      |
| Microdia                               | 2         | 4%      |
| Luxvisions Innotech Limited            | 2         | 4%      |
| IMC Networks                           | 2         | 4%      |
| SunplusIT                              | 1         | 2%      |
| OYT Tech                               | 1         | 2%      |
| Logitech                               | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 4         | 8%      |
| Syntek Integrated Camera                                        | 2         | 4%      |
| Sunplus Integrated_Webcam_HD                                    | 2         | 4%      |
| Realtek HP Truevision HD                                        | 2         | 4%      |
| Quanta USB2.0 HD UVC WebCam                                     | 2         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 4%      |
| Chicony HD WebCam                                               | 2         | 4%      |
| Bison Integrated Camera                                         | 2         | 4%      |
| Apple FaceTime HD Camera                                        | 2         | 4%      |
| Acer Integrated RGB Camera                                      | 2         | 4%      |
| Syntek Lenovo EasyCamera                                        | 1         | 2%      |
| SunplusIT 1080p FHD Camera                                      | 1         | 2%      |
| Realtek Integrated Webcam                                       | 1         | 2%      |
| Quanta ov9734_techfront_camera                                  | 1         | 2%      |
| Quanta HP Wide Vision HD Camera                                 | 1         | 2%      |
| Quanta HP HD Camera                                             | 1         | 2%      |
| Quanta HP 5MP Camera                                            | 1         | 2%      |
| Quanta HD User Facing                                           | 1         | 2%      |
| Quanta HD Camera                                                | 1         | 2%      |
| OYT Tech OYV1RDFF1                                              | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                   | 1         | 2%      |
| Microdia Dell Laptop Integrated Webcam HD                       | 1         | 2%      |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 2%      |
| Luxvisions Innotech Limited Integrated Camera                   | 1         | 2%      |
| Logitech Webcam C925e                                           | 1         | 2%      |
| Chicony USB2.0 Camera                                           | 1         | 2%      |
| Chicony HP Truevision HD                                        | 1         | 2%      |
| Chicony HD User Facing                                          | 1         | 2%      |
| Chicony 720p HD Camera                                          | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 1         | 2%      |
| Bison HD Camera                                                 | 1         | 2%      |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 2%      |
| Acer Integrated Camera                                          | 1         | 2%      |
| Acer HD Webcam                                                  | 1         | 2%      |
| Acer BisonCam,NB Pro                                            | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 4         | 36.36%  |
| Shenzhen Goodix Technology         | 3         | 27.27%  |
| Validity Sensors                   | 2         | 18.18%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 9.09%   |
| Elan Microelectronics              | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 18.18%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 18.18%  |
| Shenzhen Goodix  Fingerprint Device                             | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 9.09%   |
| Elan ELAN:ARM-M4                                                | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader  | 2         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 25%     |
| Broadcom 5880                        | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 67.21%  |
| 1     | 15        | 24.59%  |
| 2     | 5         | 8.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 44%     |
| Chipcard              | 4         | 16%     |
| Multimedia controller | 3         | 12%     |
| Camera                | 3         | 12%     |
| Net/wireless          | 2         | 8%      |
| Graphics card         | 1         | 4%      |
| Card reader           | 1         | 4%      |

