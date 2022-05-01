LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 64

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [9213736f1c](https://linux-hardware.org/?probe=9213736f1c) | Mar 27, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 24        | 52.17%  |
| 5.10.0-12-amd64      | 14        | 30.43%  |
| 5.10.0-13-686        | 5         | 10.87%  |
| 5.16.0-0.bpo.3-amd64 | 1         | 2.17%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 2.17%   |
| 5.10.0-11-686        | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 43        | 95.56%  |
| 5.16.0  | 1         | 2.22%   |
| 5.15.0  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 43        | 95.56%  |
| 5.16    | 1         | 2.22%   |
| 5.15    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 86.67%  |
| i686   | 6         | 13.33%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 43        | 95.56%  |
| Cinnamon   | 2         | 4.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 45        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 66.67%  |
| LightDM | 15        | 33.33%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 22        | 48.89%  |
| ru_RU | 3         | 6.67%   |
| en_GB | 3         | 6.67%   |
| de_DE | 3         | 6.67%   |
| pt_BR | 2         | 4.44%   |
| fr_CA | 2         | 4.44%   |
| es_ES | 2         | 4.44%   |
| pl_PL | 1         | 2.22%   |
| nl_AW | 1         | 2.22%   |
| ko_KR | 1         | 2.22%   |
| it_IT | 1         | 2.22%   |
| fr_FR | 1         | 2.22%   |
| es_PE | 1         | 2.22%   |
| es_MX | 1         | 2.22%   |
| en_CA | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 24        | 53.33%  |
| BIOS | 21        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 88.89%  |
| Overlay | 3         | 6.67%   |
| Tmpfs   | 2         | 4.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 66.67%  |
| GPT     | 11        | 24.44%  |
| MBR     | 4         | 8.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 93.33%  |
| Yes       | 3         | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 86.67%  |
| Yes       | 6         | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 20%     |
| Hewlett-Packard     | 8         | 17.78%  |
| ASUSTek Computer    | 6         | 13.33%  |
| Acer                | 5         | 11.11%  |
| Lenovo              | 4         | 8.89%   |
| MSI                 | 2         | 4.44%   |
| Apple               | 2         | 4.44%   |
| Toshiba             | 1         | 2.22%   |
| Samsung Electronics | 1         | 2.22%   |
| Panasonic           | 1         | 2.22%   |
| Packard Bell        | 1         | 2.22%   |
| Medion              | 1         | 2.22%   |
| LincPlus            | 1         | 2.22%   |
| Howard Computers    | 1         | 2.22%   |
| Dixonsxp            | 1         | 2.22%   |
| ASRock              | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude E6400                 | 2         | 4.44%   |
| Toshiba Satellite L455              | 1         | 2.22%   |
| Samsung 730QDA                      | 1         | 2.22%   |
| Panasonic CF-H2BJJHZDE              | 1         | 2.22%   |
| Packard Bell DOT S                  | 1         | 2.22%   |
| MSI MS-7B79                         | 1         | 2.22%   |
| MSI MS-7977                         | 1         | 2.22%   |
| Medion E6220                        | 1         | 2.22%   |
| LincPlus LINNCPLUS P1               | 1         | 2.22%   |
| Lenovo Yoga 7 15ITL5 82BJ           | 1         | 2.22%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1         | 2.22%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS   | 1         | 2.22%   |
| Lenovo IdeaPad 3 14ALC6 82KT        | 1         | 2.22%   |
| Howard Computers R7X                | 1         | 2.22%   |
| HP Z600 Workstation                 | 1         | 2.22%   |
| HP ProBook 6570b                    | 1         | 2.22%   |
| HP ProBook 450 G8 Notebook PC       | 1         | 2.22%   |
| HP Presario C500 (GF581UA#ABA)      | 1         | 2.22%   |
| HP Pavilion Laptop 15-eh1xxx        | 1         | 2.22%   |
| HP EliteBook 840 G1                 | 1         | 2.22%   |
| HP 255 G7 Notebook PC               | 1         | 2.22%   |
| HP 14                               | 1         | 2.22%   |
| Dell XPS A2010                      | 1         | 2.22%   |
| Dell Vostro 3500                    | 1         | 2.22%   |
| Dell Precision M4400                | 1         | 2.22%   |
| Dell Precision 7520                 | 1         | 2.22%   |
| Dell Latitude 5511                  | 1         | 2.22%   |
| Dell Latitude 3410                  | 1         | 2.22%   |
| Dell Inspiron 14 5410 2-in-1        | 1         | 2.22%   |
| ASUS PRIME H610M-A D4               | 1         | 2.22%   |
| ASUS PRIME H510M-D                  | 1         | 2.22%   |
| ASUS PRIME B350M-A                  | 1         | 2.22%   |
| ASUS P6T                            | 1         | 2.22%   |
| ASUS P5G41T-M LX3                   | 1         | 2.22%   |
| ASUS N61Jv                          | 1         | 2.22%   |
| ASRock A320M-DGS                    | 1         | 2.22%   |
| Apple MacBookPro14,1                | 1         | 2.22%   |
| Apple iMac5,1                       | 1         | 2.22%   |
| Acer Aspire X3910                   | 1         | 2.22%   |
| Acer Aspire E5-553G                 | 1         | 2.22%   |
| Acer Aspire 7745G                   | 1         | 2.22%   |
| Acer AOD270                         | 1         | 2.22%   |
| Acer AOA110                         | 1         | 2.22%   |
| Unknown                             | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 4         | 8.89%   |
| ASUS PRIME             | 3         | 6.67%   |
| Acer Aspire            | 3         | 6.67%   |
| HP ProBook             | 2         | 4.44%   |
| Dell Precision         | 2         | 4.44%   |
| Toshiba Satellite      | 1         | 2.22%   |
| Samsung 730QDA         | 1         | 2.22%   |
| Panasonic CF-H2BJJHZDE | 1         | 2.22%   |
| Packard Bell DOT       | 1         | 2.22%   |
| MSI MS-7B79            | 1         | 2.22%   |
| MSI MS-7977            | 1         | 2.22%   |
| Medion E6220           | 1         | 2.22%   |
| LincPlus LINNCPLUS     | 1         | 2.22%   |
| Lenovo Yoga            | 1         | 2.22%   |
| Lenovo ThinkCentre     | 1         | 2.22%   |
| Lenovo IdeaPadFlex     | 1         | 2.22%   |
| Lenovo IdeaPad         | 1         | 2.22%   |
| Howard Computers R7X   | 1         | 2.22%   |
| HP Z600                | 1         | 2.22%   |
| HP Presario            | 1         | 2.22%   |
| HP Pavilion            | 1         | 2.22%   |
| HP EliteBook           | 1         | 2.22%   |
| HP 255                 | 1         | 2.22%   |
| HP 14                  | 1         | 2.22%   |
| Dell XPS               | 1         | 2.22%   |
| Dell Vostro            | 1         | 2.22%   |
| Dell Inspiron          | 1         | 2.22%   |
| ASUS P6T               | 1         | 2.22%   |
| ASUS P5G41T-M          | 1         | 2.22%   |
| ASUS N61Jv             | 1         | 2.22%   |
| ASRock A320M-DGS       | 1         | 2.22%   |
| Apple MacBookPro14     | 1         | 2.22%   |
| Apple iMac5            | 1         | 2.22%   |
| Acer AOD270            | 1         | 2.22%   |
| Acer AOA110            | 1         | 2.22%   |
| Unknown                | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 7         | 15.56%  |
| 2010 | 7         | 15.56%  |
| 2020 | 6         | 13.33%  |
| 2017 | 4         | 8.89%   |
| 2013 | 4         | 8.89%   |
| 2007 | 4         | 8.89%   |
| 2008 | 3         | 6.67%   |
| 2019 | 2         | 4.44%   |
| 2012 | 2         | 4.44%   |
| 2011 | 2         | 4.44%   |
| 2018 | 1         | 2.22%   |
| 2016 | 1         | 2.22%   |
| 2015 | 1         | 2.22%   |
| 2009 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 28        | 62.22%  |
| Desktop     | 12        | 26.67%  |
| Convertible | 3         | 6.67%   |
| Tablet      | 1         | 2.22%   |
| All in one  | 1         | 2.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 41        | 91.11%  |
| Enabled  | 4         | 8.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 28.89%  |
| 4.01-8.0   | 9         | 20%     |
| 8.01-16.0  | 6         | 13.33%  |
| 16.01-24.0 | 5         | 11.11%  |
| 1.01-2.0   | 5         | 11.11%  |
| 32.01-64.0 | 3         | 6.67%   |
| 2.01-3.0   | 3         | 6.67%   |
| 24.01-32.0 | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 18        | 39.13%  |
| 2.01-3.0 | 14        | 30.43%  |
| 3.01-4.0 | 7         | 15.22%  |
| 0.51-1.0 | 5         | 10.87%  |
| 4.01-8.0 | 2         | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 71.11%  |
| 2      | 8         | 17.78%  |
| 4      | 2         | 4.44%   |
| 3      | 2         | 4.44%   |
| 6      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 64.44%  |
| Yes       | 16        | 35.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 82.22%  |
| No        | 8         | 17.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 80%     |
| No        | 9         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 51.11%  |
| Yes       | 22        | 48.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 13        | 28.89%  |
| UK          | 4         | 8.89%   |
| Canada      | 4         | 8.89%   |
| Germany     | 3         | 6.67%   |
| France      | 3         | 6.67%   |
| Spain       | 2         | 4.44%   |
| Russia      | 2         | 4.44%   |
| Brazil      | 2         | 4.44%   |
| Venezuela   | 1         | 2.22%   |
| Sweden      | 1         | 2.22%   |
| South Korea | 1         | 2.22%   |
| Romania     | 1         | 2.22%   |
| Poland      | 1         | 2.22%   |
| Peru        | 1         | 2.22%   |
| Mexico      | 1         | 2.22%   |
| Latvia      | 1         | 2.22%   |
| Kenya       | 1         | 2.22%   |
| Italy       | 1         | 2.22%   |
| Belgium     | 1         | 2.22%   |
| Austria     | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Montreal                 | 2         | 4.44%   |
| Vincennes                | 1         | 2.22%   |
| Veurne                   | 1         | 2.22%   |
| Vaslui                   | 1         | 2.22%   |
| Uiwang                   | 1         | 2.22%   |
| Toledo                   | 1         | 2.22%   |
| Tipton                   | 1         | 2.22%   |
| Stockbridge              | 1         | 2.22%   |
| Spearfish                | 1         | 2.22%   |
| Scarborough              | 1         | 2.22%   |
| San Antonio de Los Altos | 1         | 2.22%   |
| Rochester                | 1         | 2.22%   |
| Riga                     | 1         | 2.22%   |
| Queens                   | 1         | 2.22%   |
| Porto Alegre             | 1         | 2.22%   |
| Peterborough             | 1         | 2.22%   |
| Nottingham               | 1         | 2.22%   |
| National City            | 1         | 2.22%   |
| Nairobi                  | 1         | 2.22%   |
| Murphy                   | 1         | 2.22%   |
| Moscow                   | 1         | 2.22%   |
| Mieuxce                  | 1         | 2.22%   |
| Marrero                  | 1         | 2.22%   |
| Mannheim                 | 1         | 2.22%   |
| Madrid                   | 1         | 2.22%   |
| Limoges                  | 1         | 2.22%   |
| Lima                     | 1         | 2.22%   |
| Lebanon                  | 1         | 2.22%   |
| Lawrenceville            | 1         | 2.22%   |
| Knurow                   | 1         | 2.22%   |
| Hollister                | 1         | 2.22%   |
| Hamburg                  | 1         | 2.22%   |
| Hallwang                 | 1         | 2.22%   |
| Glasgow                  | 1         | 2.22%   |
| Darlington               | 1         | 2.22%   |
| Ciudad Juárez           | 1         | 2.22%   |
| Chicago                  | 1         | 2.22%   |
| Castejon                 | 1         | 2.22%   |
| Brescia                  | 1         | 2.22%   |
| Belém                   | 1         | 2.22%   |
| Arkhangelsk              | 1         | 2.22%   |
| Amhertsburg              | 1         | 2.22%   |
| AElvdalen                | 1         | 2.22%   |
| Aachen                   | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 10        | 16     | 17.24%  |
| Seagate                        | 9         | 9      | 15.52%  |
| Samsung Electronics            | 7         | 7      | 12.07%  |
| Kingston                       | 5         | 5      | 8.62%   |
| Hitachi                        | 5         | 6      | 8.62%   |
| Toshiba                        | 2         | 2      | 3.45%   |
| Sandisk                        | 2         | 2      | 3.45%   |
| Intel                          | 2         | 2      | 3.45%   |
| Unknown                        | 1         | 1      | 1.72%   |
| Transcend                      | 1         | 2      | 1.72%   |
| Solid State Storage Technology | 1         | 1      | 1.72%   |
| SK Hynix                       | 1         | 1      | 1.72%   |
| SABRENT                        | 1         | 1      | 1.72%   |
| Phison                         | 1         | 1      | 1.72%   |
| Oyen                           | 1         | 1      | 1.72%   |
| OCZ-VERTEX                     | 1         | 1      | 1.72%   |
| Micron/Crucial Technology      | 1         | 1      | 1.72%   |
| Micron Technology              | 1         | 1      | 1.72%   |
| LITEON                         | 1         | 1      | 1.72%   |
| KingSpec                       | 1         | 1      | 1.72%   |
| HGST                           | 1         | 1      | 1.72%   |
| China                          | 1         | 2      | 1.72%   |
| Apple                          | 1         | 2      | 1.72%   |
| Acer                           | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD          | 3         | 4.76%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3.17%   |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 3.17%   |
| Samsung SSD 970 EVO Plus 1TB             | 2         | 3.17%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 1.59%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 1.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 1.59%   |
| WDC WD3200AAJS-22B4A0 320GB              | 1         | 1.59%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1.59%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 1.59%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1         | 1.59%   |
| WDC WD10EFRX-68JCSN0 1TB                 | 1         | 1.59%   |
| WDC WD10EFRX-68FYTN0 1TB                 | 1         | 1.59%   |
| WDC WD10EAVS-00D7B0 1TB                  | 1         | 1.59%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1         | 1.59%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 1.59%   |
| Unknown Biwin  64GB                      | 1         | 1.59%   |
| Transcend TS480GSSD220S 480GB            | 1         | 1.59%   |
| Transcend TS240GSSD220S 240GB            | 1         | 1.59%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.59%   |
| Toshiba DT01ACA050 500GB                 | 1         | 1.59%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 1.59%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.59%   |
| Seagate ST9160412ASG 160GB               | 1         | 1.59%   |
| Seagate ST3250318AS 250GB                | 1         | 1.59%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 1.59%   |
| Seagate ST3160812AS Q 160GB              | 1         | 1.59%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 1.59%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.59%   |
| Sandisk NVMe SSD Drive 512GB             | 1         | 1.59%   |
| Samsung SSD 980 1TB                      | 1         | 1.59%   |
| Samsung SSD 850 EVO 250GB                | 1         | 1.59%   |
| Samsung SSD 850 EVO 120GB                | 1         | 1.59%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.59%   |
| Samsung MZALQ512HBLU-00BL2 512GB         | 1         | 1.59%   |
| SABRENT Disk 1TB                         | 1         | 1.59%   |
| Phison ES 512GB                          | 1         | 1.59%   |
| Oyen MiniPro E31 5TB                     | 1         | 1.59%   |
| OCZ-VERTEX PLUS R2 128GB SSD             | 1         | 1.59%   |
| Micron/Crucial NVMe SSD Drive 2TB        | 1         | 1.59%   |
| Micron NVMe SSD Drive 512GB              | 1         | 1.59%   |
| LITEON CV3-CE256-11 SATA 256GB SSD       | 1         | 1.59%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 1.59%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.59%   |
| KingSpec MT-128 128GB                    | 1         | 1.59%   |
| Intel SSDSCKKF256G8 SATA 256GB           | 1         | 1.59%   |
| Intel NVMe SSD Drive 256GB               | 1         | 1.59%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 1.59%   |
| Hitachi HTS541680J9SA00 80GB             | 1         | 1.59%   |
| Hitachi HDT725025VLA380 250GB            | 1         | 1.59%   |
| Hitachi HDS5C1032CLA382 320GB            | 1         | 1.59%   |
| Hitachi HDP725050GLA360 500GB            | 1         | 1.59%   |
| HGST HTS725050A7E630 500GB               | 1         | 1.59%   |
| China SATA SSD 256GB                     | 1         | 1.59%   |
| Apple NVMe SSD Drive 8KB                 | 1         | 1.59%   |
| Apple NVMe SSD Drive 121GB               | 1         | 1.59%   |
| Acer SSD SA100 480GB                     | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 34.62%  |
| WDC     | 8         | 14     | 30.77%  |
| Hitachi | 5         | 6      | 19.23%  |
| Toshiba | 2         | 2      | 7.69%   |
| SABRENT | 1         | 1      | 3.85%   |
| HGST    | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 31.25%  |
| Samsung Electronics | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Transcend           | 1         | 2      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| OCZ-VERTEX          | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| China               | 1         | 2      | 6.25%   |
| Acer                | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22        | 33     | 41.51%  |
| SSD     | 15        | 18     | 28.3%   |
| NVMe    | 14        | 15     | 26.42%  |
| MMC     | 1         | 1      | 1.89%   |
| Unknown | 1         | 1      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 49     | 68%     |
| NVMe | 14        | 15     | 28%     |
| SAS  | 1         | 3      | 2%      |
| MMC  | 1         | 1      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 35     | 71.79%  |
| 0.51-1.0   | 6         | 10     | 15.38%  |
| 1.01-2.0   | 3         | 3      | 7.69%   |
| 2.01-3.0   | 2         | 3      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 28.89%  |
| 101-250        | 10        | 22.22%  |
| 1-20           | 6         | 13.33%  |
| 51-100         | 5         | 11.11%  |
| 501-1000       | 4         | 8.89%   |
| 1001-2000      | 3         | 6.67%   |
| More than 3000 | 2         | 4.44%   |
| 21-50          | 2         | 4.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 67.39%  |
| 21-50     | 7         | 15.22%  |
| 101-250   | 3         | 6.52%   |
| 51-100    | 2         | 4.35%   |
| 251-500   | 1         | 2.17%   |
| 2001-3000 | 1         | 2.17%   |
| 1001-2000 | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB      | 1         | 1      | 25%     |
| Phison ES 512GB                | 1         | 1      | 25%     |
| Intel SSDSCKKF256G8 SATA 256GB | 1         | 1      | 25%     |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 25%     |
| Phison  | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 1      | 25%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 31        | 47     | 63.27%  |
| Works    | 14        | 17     | 28.57%  |
| Malfunc  | 4         | 4      | 8.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 34        | 60.71%  |
| AMD                            | 8         | 14.29%  |
| Samsung Electronics            | 5         | 8.93%   |
| Sandisk                        | 2         | 3.57%   |
| Solid State Storage Technology | 1         | 1.79%   |
| SK Hynix                       | 1         | 1.79%   |
| Phison Electronics             | 1         | 1.79%   |
| Micron/Crucial Technology      | 1         | 1.79%   |
| Micron Technology              | 1         | 1.79%   |
| JMicron Technology             | 1         | 1.79%   |
| Apple                          | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 8.96%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 5.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 4         | 5.97%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 4.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 2.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 2.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                      | 2         | 2.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 2.99%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 1.49%   |
| SK Hynix BC511                                                                         | 1         | 1.49%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.49%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 1.49%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.49%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 1.49%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                     | 1         | 1.49%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.49%   |
| Intel SSD 600P Series                                                                  | 1         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.49%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 1         | 1.49%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                             | 1         | 1.49%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                             | 1         | 1.49%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.49%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.49%   |
| Apple S3X NVMe Controller                                                              | 1         | 1.49%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 1.49%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.49%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                                 | 1         | 1.49%   |
| AMD 300 Series Chipset SATA Controller                                                 | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 30        | 50%     |
| NVMe | 14        | 23.33%  |
| IDE  | 9         | 15%     |
| RAID | 7         | 11.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 82.22%  |
| AMD    | 8         | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 6.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2         | 4.44%   |
| Intel Atom CPU N2600 @ 1.60GHz                  | 2         | 4.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 4.44%   |
| Intel Xeon CPU X5675 @ 3.07GHz                  | 1         | 2.22%   |
| Intel Xeon CPU X5570 @ 2.93GHz                  | 1         | 2.22%   |
| Intel Pentium CPU P6000 @ 1.87GHz               | 1         | 2.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 2.22%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 2.22%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1         | 2.22%   |
| Intel Core i5-7360U CPU @ 2.30GHz               | 1         | 2.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 2.22%   |
| Intel Core i5-2557M CPU @ 1.70GHz               | 1         | 2.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1         | 2.22%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 2.22%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.22%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 2.22%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1         | 2.22%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 2.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.22%   |
| Intel Celeron M CPU 520 @ 1.60GHz               | 1         | 2.22%   |
| Intel Celeron M CPU 440 @ 1.86GHz               | 1         | 2.22%   |
| Intel Celeron CPU N2815 @ 1.86GHz               | 1         | 2.22%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 2.22%   |
| Intel 12th Gen Core i3-12100F                   | 1         | 2.22%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2.22%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1         | 2.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.22%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 2.22%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 2.22%   |
| AMD Athlon 220GE with Radeon Vega Graphics      | 1         | 2.22%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 7         | 15.56%  |
| Intel Core i5           | 7         | 15.56%  |
| Intel Core 2 Duo        | 5         | 11.11%  |
| Intel Core i7           | 3         | 6.67%   |
| Intel Atom              | 3         | 6.67%   |
| AMD Ryzen 7             | 3         | 6.67%   |
| Intel Xeon              | 2         | 4.44%   |
| Intel Pentium Dual-Core | 2         | 4.44%   |
| Intel Core i3           | 2         | 4.44%   |
| Intel Celeron M         | 2         | 4.44%   |
| Intel Celeron           | 2         | 4.44%   |
| AMD Ryzen 5             | 2         | 4.44%   |
| Intel Pentium           | 1         | 2.22%   |
| Intel Core 2            | 1         | 2.22%   |
| AMD Ryzen 3             | 1         | 2.22%   |
| AMD Athlon              | 1         | 2.22%   |
| AMD A10                 | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 48.89%  |
| 4      | 12        | 26.67%  |
| 8      | 4         | 8.89%   |
| 6      | 4         | 8.89%   |
| 1      | 3         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 97.78%  |
| 2      | 1         | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 66.67%  |
| 1      | 15        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 93.33%  |
| 32-bit         | 3         | 6.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 6         | 13.33%  |
| 0x1067a    | 4         | 8.89%   |
| 0x6fd      | 2         | 4.44%   |
| 0x6f6      | 2         | 4.44%   |
| 0x506e3    | 2         | 4.44%   |
| 0x30661    | 2         | 4.44%   |
| 0x20652    | 2         | 4.44%   |
| 0x08608103 | 2         | 4.44%   |
| 0x08108109 | 2         | 4.44%   |
| 0xa0653    | 1         | 2.22%   |
| 0xa0652    | 1         | 2.22%   |
| 0x906ea    | 1         | 2.22%   |
| 0x90675    | 1         | 2.22%   |
| 0x806ec    | 1         | 2.22%   |
| 0x806e9    | 1         | 2.22%   |
| 0x706a8    | 1         | 2.22%   |
| 0x6ec      | 1         | 2.22%   |
| 0x40651    | 1         | 2.22%   |
| 0x306a9    | 1         | 2.22%   |
| 0x30673    | 1         | 2.22%   |
| 0x206c2    | 1         | 2.22%   |
| 0x206a7    | 1         | 2.22%   |
| 0x106e5    | 1         | 2.22%   |
| 0x106c2    | 1         | 2.22%   |
| 0x106a5    | 1         | 2.22%   |
| 0x10676    | 1         | 2.22%   |
| 0x08600103 | 1         | 2.22%   |
| 0x0810100b | 1         | 2.22%   |
| 0x08001137 | 1         | 2.22%   |
| 0x0600611a | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| TigerLake     | 6         | 13.33%  |
| Penryn        | 5         | 11.11%  |
| Core          | 4         | 8.89%   |
| Westmere      | 3         | 6.67%   |
| KabyLake      | 3         | 6.67%   |
| Bonnell       | 3         | 6.67%   |
| Unknown       | 3         | 6.67%   |
| Zen+          | 2         | 4.44%   |
| Zen           | 2         | 4.44%   |
| Skylake       | 2         | 4.44%   |
| Nehalem       | 2         | 4.44%   |
| CometLake     | 2         | 4.44%   |
| Zen 2         | 1         | 2.22%   |
| Silvermont    | 1         | 2.22%   |
| SandyBridge   | 1         | 2.22%   |
| P6            | 1         | 2.22%   |
| IvyBridge     | 1         | 2.22%   |
| Haswell       | 1         | 2.22%   |
| Goldmont plus | 1         | 2.22%   |
| Excavator     | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 52.08%  |
| Nvidia | 12        | 25%     |
| AMD    | 11        | 22.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 9.62%   |
| Nvidia GT218 [GeForce 210]                                                            | 2         | 3.85%   |
| Nvidia G98M [Quadro NVS 160M]                                                         | 2         | 3.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 3.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 2         | 3.85%   |
| AMD Lucienne                                                                          | 2         | 3.85%   |
| Nvidia GT216M [GeForce GT 325M]                                                       | 1         | 1.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 1         | 1.92%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 1.92%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 1.92%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1.92%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                     | 1         | 1.92%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                       | 1         | 1.92%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 1.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.92%   |
| Intel Iris Plus Graphics 640                                                          | 1         | 1.92%   |
| Intel HD Graphics 530                                                                 | 1         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 1         | 1.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.92%   |
| AMD RV530/M56-P [Mobility Radeon X1600]                                               | 1         | 1.92%   |
| AMD Renoir                                                                            | 1         | 1.92%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                              | 1         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.92%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                 | 1         | 1.92%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.92%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                      | 1         | 1.92%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                        | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 48.89%  |
| 1 x Nvidia     | 10        | 22.22%  |
| 1 x AMD        | 9         | 20%     |
| 2 x AMD        | 2         | 4.44%   |
| Intel + Nvidia | 2         | 4.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 43        | 95.56%  |
| Unknown | 2         | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 51.11%  |
| 0.01-0.5   | 8         | 17.78%  |
| 1.01-2.0   | 6         | 13.33%  |
| 3.01-4.0   | 4         | 8.89%   |
| 0.51-1.0   | 4         | 8.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 20.83%  |
| Samsung Electronics     | 6         | 12.5%   |
| BOE                     | 5         | 10.42%  |
| LG Display              | 3         | 6.25%   |
| Dell                    | 3         | 6.25%   |
| PANDA                   | 2         | 4.17%   |
| LG Philips              | 2         | 4.17%   |
| Hewlett-Packard         | 2         | 4.17%   |
| Chimei Innolux          | 2         | 4.17%   |
| Apple                   | 2         | 4.17%   |
| Acer                    | 2         | 4.17%   |
| Sharp                   | 1         | 2.08%   |
| Quanta Display          | 1         | 2.08%   |
| Planar                  | 1         | 2.08%   |
| Philips                 | 1         | 2.08%   |
| Medion                  | 1         | 2.08%   |
| HannStar                | 1         | 2.08%   |
| Goldstar                | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| Ancor Communications    | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 3.92%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch     | 1         | 1.96%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 1.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.96%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 1.96%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 1.96%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch                | 1         | 1.96%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 1.96%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1.96%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                      | 1         | 1.96%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 1.96%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch               | 1         | 1.96%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch               | 1         | 1.96%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch               | 1         | 1.96%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 1.96%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 1.96%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 1.96%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 1.96%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 1.96%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                       | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE099E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO26ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 1.96%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 1         | 1.96%   |
| Apple Color LCD APP9C58 1440x900 367x229mm 17.0-inch                     | 1         | 1.96%   |
| Ancor Communications ASUS MX299 ACI2931 2560x1080 673x284mm 28.8-inch    | 1         | 1.96%   |
| Acer V203HV ACR01D3 1600x900 443x249mm 20.0-inch                         | 1         | 1.96%   |
| Acer P223WB ACR000E 1680x1050 473x296mm 22.0-inch                        | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 37.78%  |
| 1366x768 (WXGA)    | 7         | 15.56%  |
| 1600x900 (HD+)     | 4         | 8.89%   |
| 1440x900 (WXGA+)   | 3         | 6.67%   |
| 1024x600           | 3         | 6.67%   |
| 2560x1440 (QHD)    | 2         | 4.44%   |
| 1920x1200 (WUXGA)  | 2         | 4.44%   |
| 1680x1050 (WSXGA+) | 2         | 4.44%   |
| 1280x800 (WXGA)    | 2         | 4.44%   |
| 2880x1800          | 1         | 2.22%   |
| 2560x1080          | 1         | 2.22%   |
| 1280x1024 (SXGA)   | 1         | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 14        | 28.57%  |
| 14     | 6         | 12.24%  |
| 13     | 5         | 10.2%   |
| 27     | 3         | 6.12%   |
| 21     | 3         | 6.12%   |
| 20     | 3         | 6.12%   |
| 17     | 3         | 6.12%   |
| 24     | 2         | 4.08%   |
| 23     | 2         | 4.08%   |
| 10     | 2         | 4.08%   |
| 32     | 1         | 2.04%   |
| 28     | 1         | 2.04%   |
| 22     | 1         | 2.04%   |
| 19     | 1         | 2.04%   |
| 16     | 1         | 2.04%   |
| 8      | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 46.81%  |
| 501-600     | 6         | 12.77%  |
| 401-500     | 6         | 12.77%  |
| 351-400     | 5         | 10.64%  |
| 201-300     | 5         | 10.64%  |
| 701-800     | 1         | 2.13%   |
| 601-700     | 1         | 2.13%   |
| 101-200     | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 72.73%  |
| 16/10 | 10        | 22.73%  |
| 5/4   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 31.25%  |
| 81-90          | 8         | 16.67%  |
| 201-250        | 5         | 10.42%  |
| 151-200        | 4         | 8.33%   |
| 71-80          | 3         | 6.25%   |
| 301-350        | 3         | 6.25%   |
| 251-300        | 3         | 6.25%   |
| 41-50          | 2         | 4.17%   |
| 121-130        | 2         | 4.17%   |
| 351-500        | 1         | 2.08%   |
| 1-40           | 1         | 2.08%   |
| 131-140        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 35.42%  |
| 121-160       | 16        | 33.33%  |
| 101-120       | 12        | 25%     |
| 161-240       | 2         | 4.17%   |
| More than 240 | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 84.44%  |
| 2     | 4         | 8.89%   |
| 3     | 2         | 4.44%   |
| 0     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 22        | 33.33%  |
| Intel                         | 19        | 28.79%  |
| Qualcomm Atheros              | 8         | 12.12%  |
| Broadcom                      | 8         | 12.12%  |
| Ralink Technology             | 3         | 4.55%   |
| Ralink                        | 1         | 1.52%   |
| OnePlus Technology (Shenzhen) | 1         | 1.52%   |
| Microchip Technology          | 1         | 1.52%   |
| Mercucys                      | 1         | 1.52%   |
| Marvell Technology Group      | 1         | 1.52%   |
| Broadcom Limited              | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 10        | 11.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4         | 4.76%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                                                      | 3         | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 2         | 2.38%   |
| Realtek 802.11ac NIC                                                                          | 2         | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 2.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 2.38%   |
| Intel Ultimate N WiFi Link 5300                                                               | 2         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 2.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 1.19%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 1.19%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 1.19%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.19%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 1.19%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.19%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 1.19%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 1.19%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                 | 1         | 1.19%   |
| OnePlus (Shenzhen) AC2001                                                                     | 1         | 1.19%   |
| Microchip LAN9500/LAN9500i                                                                    | 1         | 1.19%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 1.19%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                                       | 1         | 1.19%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.19%   |
| Intel Wireless 7260                                                                           | 1         | 1.19%   |
| Intel WiFi Link 5100                                                                          | 1         | 1.19%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.19%   |
| Intel I210 Gigabit Fiber Network Connection                                                   | 1         | 1.19%   |
| Intel Ethernet Connection I218-LM                                                             | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1         | 1.19%   |
| Intel Ethernet Connection (5) I219-LM                                                         | 1         | 1.19%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1         | 1.19%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1         | 1.19%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.19%   |
| Intel 82579V Gigabit Network Connection                                                       | 1         | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1         | 1.19%   |
| Intel 82567V-2 Gigabit Network Connection                                                     | 1         | 1.19%   |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 1         | 1.19%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 1         | 1.19%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 1.19%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 1.19%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 1.19%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 1.19%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 1.19%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.19%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 30.77%  |
| Realtek Semiconductor | 10        | 25.64%  |
| Broadcom              | 7         | 17.95%  |
| Qualcomm Atheros      | 4         | 10.26%  |
| Ralink Technology     | 3         | 7.69%   |
| Ralink                | 1         | 2.56%   |
| Mercucys              | 1         | 2.56%   |
| Broadcom Limited      | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                                           | 4         | 9.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 6.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2         | 4.65%   |
| Realtek 802.11ac NIC                                                                          | 2         | 4.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 4.65%   |
| Intel Ultimate N WiFi Link 5300                                                               | 2         | 4.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 4.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 2.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 2.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1         | 2.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1         | 2.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 2.33%   |
| Realtek RTL8187B Wireless Adapter                                                             | 1         | 2.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.33%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 2.33%   |
| Ralink RT2561/RT61 rev B 802.11g                                                              | 1         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.33%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.33%   |
| Intel Wireless 7260                                                                           | 1         | 2.33%   |
| Intel WiFi Link 5100                                                                          | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 2.33%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                        | 1         | 2.33%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 1         | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1         | 2.33%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 2.33%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 2.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 18        | 45%     |
| Intel                         | 13        | 32.5%   |
| Qualcomm Atheros              | 5         | 12.5%   |
| OnePlus Technology (Shenzhen) | 1         | 2.5%    |
| Microchip Technology          | 1         | 2.5%    |
| Marvell Technology Group      | 1         | 2.5%    |
| Broadcom                      | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 24.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 9.76%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 7.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 4.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.44%   |
| OnePlus (Shenzhen) AC2001                                         | 1         | 2.44%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 2.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 2.44%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 2.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.44%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 2.44%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 2.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 50.68%  |
| WiFi     | 36        | 49.32%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 57.45%  |
| Ethernet | 20        | 42.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 53.33%  |
| 1     | 20        | 44.44%  |
| 0     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 73.33%  |
| Yes  | 12        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 40.91%  |
| Realtek Semiconductor           | 5         | 22.73%  |
| Dell                            | 3         | 13.64%  |
| Qualcomm Atheros Communications | 1         | 4.55%   |
| Lite-On Technology              | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |
| Broadcom                        | 1         | 4.55%   |
| Apple                           | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 5         | 22.73%  |
| Realtek Bluetooth Radio                        | 4         | 18.18%  |
| Intel Bluetooth wireless interface             | 2         | 9.09%   |
| Dell Wireless 370 Bluetooth Mini-card          | 2         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 4.55%   |
| Lite-On Bluetooth Device                       | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4.55%   |
| Intel AX200 Bluetooth                          | 1         | 4.55%   |
| Foxconn / Hon Hai Acer Bluetooth module        | 1         | 4.55%   |
| Dell BT Mini-Receiver                          | 1         | 4.55%   |
| Broadcom HP Portable SoftSailing               | 1         | 4.55%   |
| Apple Bluetooth HCI                            | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 59.02%  |
| AMD                   | 11        | 18.03%  |
| Nvidia                | 9         | 14.75%  |
| Texas Instruments     | 2         | 3.28%   |
| Realtek Semiconductor | 1         | 1.64%   |
| GN Netcom             | 1         | 1.64%   |
| Audioengine           | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 8.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 8.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 8.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 7.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 4.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.29%   |
| Nvidia High Definition Audio Controller                                    | 2         | 2.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 2.86%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.43%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 1.43%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.43%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.43%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.43%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 1.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.43%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.43%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.43%   |
| Intel Audio device                                                         | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.43%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.43%   |
| GN Netcom Jabra EVOLVE 20 MS                                               | 1         | 1.43%   |
| Audioengine D1 24-bit DAC                                                  | 1         | 1.43%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.43%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 31.25%  |
| A-DATA Technology   | 3         | 18.75%  |
| SK Hynix            | 2         | 12.5%   |
| Nanya Technology    | 2         | 12.5%   |
| Unknown (ABCD)      | 1         | 6.25%   |
| Unknown             | 1         | 6.25%   |
| Kingston            | 1         | 6.25%   |
| G.Skill             | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 11.11%  |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 5.56%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 5.56%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 5.56%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 5.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 5.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 5.56%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 5.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 5.56%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s             | 1         | 5.56%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s             | 1         | 5.56%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1024MB DIMM DDR2 667MT/s             | 1         | 5.56%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s              | 1         | 5.56%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s            | 1         | 5.56%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                       | 1         | 5.56%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3200MT/s                     | 1         | 5.56%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s          | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 68.75%  |
| SDRAM   | 3         | 18.75%  |
| LPDDR4  | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 58.82%  |
| DIMM         | 5         | 29.41%  |
| Row Of Chips | 2         | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 44.44%  |
| 4096  | 3         | 16.67%  |
| 2048  | 3         | 16.67%  |
| 16384 | 2         | 11.11%  |
| 32768 | 1         | 5.56%   |
| 1024  | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 50%     |
| 2400  | 2         | 12.5%   |
| 4199  | 1         | 6.25%   |
| 2667  | 1         | 6.25%   |
| 2048  | 1         | 6.25%   |
| 1333  | 1         | 6.25%   |
| 1200  | 1         | 6.25%   |
| 667   | 1         | 6.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 5         | 17.86%  |
| Chicony Electronics                    | 5         | 17.86%  |
| Suyin                                  | 2         | 7.14%   |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Luxvisions Innotech Limited            | 2         | 7.14%   |
| Logitech                               | 2         | 7.14%   |
| IMC Networks                           | 2         | 7.14%   |
| Unknown                                | 1         | 3.57%   |
| Syntek                                 | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| OmniVision Technologies                | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| ARC International                      | 1         | 3.57%   |
| ALi                                    | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 5         | 17.86%  |
| Chicony HP Truevision HD camera                      | 2         | 7.14%   |
| Chicony HD WebCam                                    | 2         | 7.14%   |
| Unknown 720p HD Camera                               | 1         | 3.57%   |
| Syntek Integrated Camera                             | 1         | 3.57%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 3.57%   |
| Suyin 1.3M HD WebCam                                 | 1         | 3.57%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 3.57%   |
| Sunplus 1.3M HD WebCam                               | 1         | 3.57%   |
| Realtek Integrated Camera 2M                         | 1         | 3.57%   |
| OmniVision Integrated Webcam for Dell XPS 2010       | 1         | 3.57%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 3.57%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 3.57%   |
| Logitech Webcam C925e                                | 1         | 3.57%   |
| Logitech Webcam C210                                 | 1         | 3.57%   |
| IMC Networks Integrated Camera                       | 1         | 3.57%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 3.57%   |
| Chicony Integrated HP HD Webcam                      | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 3.57%   |
| ARC International Camera                             | 1         | 3.57%   |
| ALi Gateway Webcam                                   | 1         | 3.57%   |
| Acer Integrated Camera                               | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Validity Sensors    | 2         | 50%     |
| Synaptics           | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 25%     |
| Validity Sensors VFS491                    | 1         | 25%     |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 25%     |
| Unknown                                    | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 60%     |
| Broadcom 5880                                  | 1         | 20%     |
| Broadcom 58200                                 | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 26        | 56.52%  |
| 1     | 19        | 41.3%   |
| 2     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 27.27%  |
| Chipcard              | 5         | 22.73%  |
| Multimedia controller | 4         | 18.18%  |
| Fingerprint reader    | 4         | 18.18%  |
| Graphics card         | 2         | 9.09%   |
| Camera                | 1         | 4.55%   |

