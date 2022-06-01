LMDE 5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 64

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-14-amd64      | 14        | 28%     |
| 5.10.0-13-amd64      | 14        | 28%     |
| 5.10.0-12-amd64      | 13        | 26%     |
| 5.10.0-13-686        | 5         | 10%     |
| 5.16.0-0.bpo.4-amd64 | 1         | 2%      |
| 5.16.0-0.bpo.3-amd64 | 1         | 2%      |
| 5.15.0-0.bpo.3-amd64 | 1         | 2%      |
| 5.10.0-14-686        | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 45        | 93.75%  |
| 5.16.0  | 2         | 4.17%   |
| 5.15.0  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 45        | 93.75%  |
| 5.16    | 2         | 4.17%   |
| 5.15    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 42        | 87.5%   |
| i686   | 6         | 12.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 44        | 91.67%  |
| Cinnamon   | 4         | 8.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 48        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 60.42%  |
| LightDM | 19        | 39.58%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 50%     |
| pt_BR | 5         | 10.42%  |
| en_GB | 4         | 8.33%   |
| ru_RU | 2         | 4.17%   |
| de_DE | 2         | 4.17%   |
| pl_PL | 1         | 2.08%   |
| nl_AW | 1         | 2.08%   |
| ko_KR | 1         | 2.08%   |
| it_IT | 1         | 2.08%   |
| fr_FR | 1         | 2.08%   |
| es_PE | 1         | 2.08%   |
| es_MX | 1         | 2.08%   |
| es_ES | 1         | 2.08%   |
| es_EC | 1         | 2.08%   |
| en_IE | 1         | 2.08%   |
| en_CA | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 62.5%   |
| BIOS | 18        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 44        | 91.67%  |
| Overlay | 4         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 60.42%  |
| GPT     | 15        | 31.25%  |
| MBR     | 4         | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 93.75%  |
| Yes       | 3         | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 89.58%  |
| Yes       | 5         | 10.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 12        | 25%     |
| Dell             | 11        | 22.92%  |
| Acer             | 7         | 14.58%  |
| Lenovo           | 5         | 10.42%  |
| ASUSTek Computer | 3         | 6.25%   |
| Toshiba          | 2         | 4.17%   |
| Apple            | 2         | 4.17%   |
| Philco           | 1         | 2.08%   |
| Packard Bell     | 1         | 2.08%   |
| Medion           | 1         | 2.08%   |
| LincPlus         | 1         | 2.08%   |
| Howard Computers | 1         | 2.08%   |
| Dixonsxp         | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Dell Latitude E6400                              | 2         | 4.17%   |
| Toshiba Satellite M55                            | 1         | 2.08%   |
| Toshiba Satellite L455                           | 1         | 2.08%   |
| Philco 10D                                       | 1         | 2.08%   |
| Packard Bell DOT S                               | 1         | 2.08%   |
| Medion E6220                                     | 1         | 2.08%   |
| LincPlus LINNCPLUS P1                            | 1         | 2.08%   |
| Lenovo ThinkPad T480 20L6S1RN00                  | 1         | 2.08%   |
| Lenovo Legion 5 15ACH6H 82JU                     | 1         | 2.08%   |
| Lenovo IdeaPad 5 14ALC05 82LM                    | 1         | 2.08%   |
| Lenovo IdeaPad 3 15ITL6 82H8                     | 1         | 2.08%   |
| Lenovo IdeaPad 3 14ALC6 82KT                     | 1         | 2.08%   |
| Howard Computers R7X                             | 1         | 2.08%   |
| HP ZBook Fury 17.3 inch G8 Mobile Workstation PC | 1         | 2.08%   |
| HP ProBook 6570b                                 | 1         | 2.08%   |
| HP ProBook 450 G8 Notebook PC                    | 1         | 2.08%   |
| HP Presario C500 (GF581UA#ABA)                   | 1         | 2.08%   |
| HP Pavilion Laptop 15-eh1xxx                     | 1         | 2.08%   |
| HP Notebook                                      | 1         | 2.08%   |
| HP Laptop 14-df0xxx                              | 1         | 2.08%   |
| HP Laptop 14-cf3xxx                              | 1         | 2.08%   |
| HP ENVY 17                                       | 1         | 2.08%   |
| HP EliteBook 840 G1                              | 1         | 2.08%   |
| HP 255 G7 Notebook PC                            | 1         | 2.08%   |
| HP 14                                            | 1         | 2.08%   |
| Dell XPS 13 9305                                 | 1         | 2.08%   |
| Dell Vostro 3500                                 | 1         | 2.08%   |
| Dell Precision M4400                             | 1         | 2.08%   |
| Dell Precision 7520                              | 1         | 2.08%   |
| Dell Latitude 5511                               | 1         | 2.08%   |
| Dell Latitude 3410                               | 1         | 2.08%   |
| Dell Inspiron 5566                               | 1         | 2.08%   |
| Dell Inspiron 5559                               | 1         | 2.08%   |
| Dell Inspiron 14 5410 2-in-1                     | 1         | 2.08%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA           | 1         | 2.08%   |
| ASUS VivoBook E14 E402YA_L402YA                  | 1         | 2.08%   |
| ASUS N61Jv                                       | 1         | 2.08%   |
| Apple MacBookPro14,1                             | 1         | 2.08%   |
| Apple MacBookAir7,2                              | 1         | 2.08%   |
| Acer Aspire V3-571G                              | 1         | 2.08%   |
| Acer Aspire One 522                              | 1         | 2.08%   |
| Acer Aspire E5-553G                              | 1         | 2.08%   |
| Acer Aspire E1-532                               | 1         | 2.08%   |
| Acer Aspire 7745G                                | 1         | 2.08%   |
| Acer AOD270                                      | 1         | 2.08%   |
| Acer AOA110                                      | 1         | 2.08%   |
| Unknown                                          | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 5         | 10.42%  |
| Dell Latitude        | 4         | 8.33%   |
| Lenovo IdeaPad       | 3         | 6.25%   |
| Dell Inspiron        | 3         | 6.25%   |
| Toshiba Satellite    | 2         | 4.17%   |
| HP ProBook           | 2         | 4.17%   |
| HP Laptop            | 2         | 4.17%   |
| Dell Precision       | 2         | 4.17%   |
| ASUS VivoBook        | 2         | 4.17%   |
| Philco 10D           | 1         | 2.08%   |
| Packard Bell DOT     | 1         | 2.08%   |
| Medion E6220         | 1         | 2.08%   |
| LincPlus LINNCPLUS   | 1         | 2.08%   |
| Lenovo ThinkPad      | 1         | 2.08%   |
| Lenovo Legion        | 1         | 2.08%   |
| Howard Computers R7X | 1         | 2.08%   |
| HP ZBook             | 1         | 2.08%   |
| HP Presario          | 1         | 2.08%   |
| HP Pavilion          | 1         | 2.08%   |
| HP Notebook          | 1         | 2.08%   |
| HP ENVY              | 1         | 2.08%   |
| HP EliteBook         | 1         | 2.08%   |
| HP 255               | 1         | 2.08%   |
| HP 14                | 1         | 2.08%   |
| Dell XPS             | 1         | 2.08%   |
| Dell Vostro          | 1         | 2.08%   |
| ASUS N61Jv           | 1         | 2.08%   |
| Apple MacBookPro14   | 1         | 2.08%   |
| Apple MacBookAir7    | 1         | 2.08%   |
| Acer AOD270          | 1         | 2.08%   |
| Acer AOA110          | 1         | 2.08%   |
| Unknown              | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 9         | 18.75%  |
| 2020 | 5         | 10.42%  |
| 2013 | 5         | 10.42%  |
| 2016 | 4         | 8.33%   |
| 2012 | 4         | 8.33%   |
| 2010 | 4         | 8.33%   |
| 2018 | 3         | 6.25%   |
| 2019 | 2         | 4.17%   |
| 2017 | 2         | 4.17%   |
| 2011 | 2         | 4.17%   |
| 2009 | 2         | 4.17%   |
| 2008 | 2         | 4.17%   |
| 2007 | 2         | 4.17%   |
| 2015 | 1         | 2.08%   |
| 2006 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 91.67%  |
| Enabled  | 4         | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 14        | 29.17%  |
| 4.01-8.0    | 13        | 27.08%  |
| 8.01-16.0   | 6         | 12.5%   |
| 16.01-24.0  | 5         | 10.42%  |
| 1.01-2.0    | 4         | 8.33%   |
| 2.01-3.0    | 3         | 6.25%   |
| 32.01-64.0  | 2         | 4.17%   |
| 64.01-256.0 | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 22        | 44.9%   |
| 2.01-3.0 | 15        | 30.61%  |
| 3.01-4.0 | 6         | 12.24%  |
| 0.51-1.0 | 4         | 8.16%   |
| 4.01-8.0 | 2         | 4.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 72.92%  |
| 2      | 11        | 22.92%  |
| 4      | 1         | 2.08%   |
| 3      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 72.92%  |
| Yes       | 13        | 27.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 81.25%  |
| No        | 9         | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 97.92%  |
| No        | 1         | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 66.67%  |
| No        | 16        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 25%     |
| UK          | 7         | 14.58%  |
| Brazil      | 5         | 10.42%  |
| Russia      | 3         | 6.25%   |
| Germany     | 3         | 6.25%   |
| Romania     | 2         | 4.17%   |
| France      | 2         | 4.17%   |
| Canada      | 2         | 4.17%   |
| Spain       | 1         | 2.08%   |
| South Korea | 1         | 2.08%   |
| Poland      | 1         | 2.08%   |
| Peru        | 1         | 2.08%   |
| Mexico      | 1         | 2.08%   |
| Malaysia    | 1         | 2.08%   |
| Lithuania   | 1         | 2.08%   |
| Kenya       | 1         | 2.08%   |
| Italy       | 1         | 2.08%   |
| Ecuador     | 1         | 2.08%   |
| Belgium     | 1         | 2.08%   |
| Austria     | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Neasden        | 2         | 4.17%   |
| Moscow         | 2         | 4.17%   |
| Vilnius        | 1         | 2.08%   |
| Veurne         | 1         | 2.08%   |
| Vaslui         | 1         | 2.08%   |
| Uiwang         | 1         | 2.08%   |
| Tipton         | 1         | 2.08%   |
| Spearfish      | 1         | 2.08%   |
| Scarborough    | 1         | 2.08%   |
| Saratov        | 1         | 2.08%   |
| Rochester      | 1         | 2.08%   |
| Recife         | 1         | 2.08%   |
| Petaling Jaya  | 1         | 2.08%   |
| Nairobi        | 1         | 2.08%   |
| Murphy         | 1         | 2.08%   |
| Monaca         | 1         | 2.08%   |
| Mieuxce        | 1         | 2.08%   |
| Marrero        | 1         | 2.08%   |
| Mannheim       | 1         | 2.08%   |
| Mammoth Lakes  | 1         | 2.08%   |
| Londonderry    | 1         | 2.08%   |
| London         | 1         | 2.08%   |
| Limoges        | 1         | 2.08%   |
| Lima           | 1         | 2.08%   |
| Lebanon        | 1         | 2.08%   |
| Lawrenceville  | 1         | 2.08%   |
| Knurow         | 1         | 2.08%   |
| Hollister      | 1         | 2.08%   |
| Hallwang       | 1         | 2.08%   |
| Glasgow        | 1         | 2.08%   |
| Everett        | 1         | 2.08%   |
| Darlington     | 1         | 2.08%   |
| Ciudad Juárez | 1         | 2.08%   |
| Chicago        | 1         | 2.08%   |
| Brescia        | 1         | 2.08%   |
| Branesti       | 1         | 2.08%   |
| Blairsville    | 1         | 2.08%   |
| Birigui        | 1         | 2.08%   |
| Berlin         | 1         | 2.08%   |
| Belém         | 1         | 2.08%   |
| Bandeirantes   | 1         | 2.08%   |
| Babahoyo       | 1         | 2.08%   |
| Avilés        | 1         | 2.08%   |
| Andradina      | 1         | 2.08%   |
| Amhertsburg    | 1         | 2.08%   |
| Aachen         | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 8         | 8      | 13.33%  |
| Samsung Electronics            | 7         | 8      | 11.67%  |
| Seagate                        | 6         | 6      | 10%     |
| Toshiba                        | 4         | 4      | 6.67%   |
| Hitachi                        | 4         | 4      | 6.67%   |
| Unknown                        | 3         | 3      | 5%      |
| Intel                          | 3         | 3      | 5%      |
| SanDisk                        | 2         | 2      | 3.33%   |
| Micron Technology              | 2         | 2      | 3.33%   |
| Kingston                       | 2         | 2      | 3.33%   |
| Apple                          | 2         | 3      | 3.33%   |
| A-DATA Technology              | 2         | 2      | 3.33%   |
| Solid State Storage Technology | 1         | 1      | 1.67%   |
| SK Hynix                       | 1         | 1      | 1.67%   |
| SABRENT                        | 1         | 1      | 1.67%   |
| PNY                            | 1         | 1      | 1.67%   |
| Phison                         | 1         | 1      | 1.67%   |
| Patriot                        | 1         | 1      | 1.67%   |
| Oyen                           | 1         | 1      | 1.67%   |
| Micron/Crucial Technology      | 1         | 2      | 1.67%   |
| LITEON                         | 1         | 1      | 1.67%   |
| KIOXIA                         | 1         | 2      | 1.67%   |
| KingSpec                       | 1         | 1      | 1.67%   |
| HGST                           | 1         | 1      | 1.67%   |
| China                          | 1         | 2      | 1.67%   |
| BHT                            | 1         | 1      | 1.67%   |
| Acer                           | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB             | 2         | 3.23%   |
| Unknown SD/MMC/MS PRO 999GB              | 2         | 3.23%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3.23%   |
| Micron NVMe SSD Drive 512GB              | 2         | 3.23%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 1.61%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 1.61%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 1.61%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 1.61%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB     | 1         | 1.61%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 1.61%   |
| Unknown Biwin  64GB                      | 1         | 1.61%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1.61%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 1.61%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1.61%   |
| Toshiba MK3252GSX 320GB                  | 1         | 1.61%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 1.61%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.61%   |
| Seagate ST9160412ASG 160GB               | 1         | 1.61%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 1.61%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1.61%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1.61%   |
| SanDisk DF4064  64GB                     | 1         | 1.61%   |
| Samsung SSD 980 PRO 1TB                  | 1         | 1.61%   |
| Samsung SSD 980 1TB                      | 1         | 1.61%   |
| Samsung SSD 970 EVO Plus 1TB             | 1         | 1.61%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 1.61%   |
| Samsung SSD 850 EVO 500GB                | 1         | 1.61%   |
| Samsung SSD 850 EVO 120GB                | 1         | 1.61%   |
| Samsung PM991a NVMe 512GB                | 1         | 1.61%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 1.61%   |
| SABRENT Disk 240GB                       | 1         | 1.61%   |
| PNY CS1311 480GB SSD                     | 1         | 1.61%   |
| Phison ES 512GB                          | 1         | 1.61%   |
| Patriot P210 512GB SSD                   | 1         | 1.61%   |
| Oyen MiniPro E31 5TB                     | 1         | 1.61%   |
| Micron/Crucial NVMe SSD Drive 2TB        | 1         | 1.61%   |
| LITEON CV3-CE256-11 SATA 256GB SSD       | 1         | 1.61%   |
| KIOXIA KXG60PNV2T04 2TB                  | 1         | 1.61%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 1.61%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 1.61%   |
| KingSpec MT-128 128GB                    | 1         | 1.61%   |
| Intel SSDSCKKF256G8 SATA 256GB           | 1         | 1.61%   |
| Intel SSDSC2CW060A3 64GB                 | 1         | 1.61%   |
| Intel SSDPEKNW512G8 512GB                | 1         | 1.61%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 1.61%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1.61%   |
| Hitachi HTS541680J9SA00 80GB             | 1         | 1.61%   |
| Hitachi HTS541010G9AT00 100GB            | 1         | 1.61%   |
| HGST HTS725050A7E630 500GB               | 1         | 1.61%   |
| China SATA SSD 256GB                     | 1         | 1.61%   |
| BHT WR202I0064G E70245F5 64GB            | 1         | 1.61%   |
| Apple SSD SM0128G 121GB                  | 1         | 1.61%   |
| Apple NVMe SSD Drive 8KB                 | 1         | 1.61%   |
| Apple NVMe SSD Drive 121GB               | 1         | 1.61%   |
| Acer SSD SA100 480GB                     | 1         | 1.61%   |
| A-DATA SU650 120GB SSD                   | 1         | 1.61%   |
| A-DATA ED600 1TB SSD                     | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 26.09%  |
| WDC     | 5         | 5      | 21.74%  |
| Toshiba | 4         | 4      | 17.39%  |
| Hitachi | 4         | 4      | 17.39%  |
| Unknown | 2         | 2      | 8.7%    |
| SABRENT | 1         | 1      | 4.35%   |
| HGST    | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 11.11%  |
| Kingston            | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| A-DATA Technology   | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| PNY                 | 1         | 1      | 5.56%   |
| Patriot             | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| China               | 1         | 2      | 5.56%   |
| BHT                 | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |
| Acer                | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 20        | 23     | 36.36%  |
| SSD     | 17        | 20     | 30.91%  |
| NVMe    | 15        | 19     | 27.27%  |
| MMC     | 2         | 2      | 3.64%   |
| Unknown | 1         | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 38     | 62.26%  |
| NVMe | 15        | 19     | 28.3%   |
| SAS  | 3         | 6      | 5.66%   |
| MMC  | 2         | 2      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 31     | 73.68%  |
| 0.51-1.0   | 8         | 10     | 21.05%  |
| 2.01-3.0   | 1         | 1      | 2.63%   |
| 1.01-2.0   | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 33.33%  |
| 101-250        | 9         | 18.75%  |
| 501-1000       | 6         | 12.5%   |
| 51-100         | 6         | 12.5%   |
| 1-20           | 4         | 8.33%   |
| 21-50          | 3         | 6.25%   |
| 1001-2000      | 2         | 4.17%   |
| More than 3000 | 1         | 2.08%   |
| 2001-3000      | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 28        | 56%     |
| 21-50     | 12        | 24%     |
| 101-250   | 3         | 6%      |
| 251-500   | 2         | 4%      |
| 501-1000  | 2         | 4%      |
| 51-100    | 2         | 4%      |
| 2001-3000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Phison ES 512GB                | 1         | 1      | 33.33%  |
| Intel SSDSCKKF256G8 SATA 256GB | 1         | 1      | 33.33%  |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Phison  | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 33.33%  |
| SSD  | 1         | 1      | 33.33%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Detected | 31        | 42     | 60.78%  |
| Works    | 17        | 20     | 33.33%  |
| Malfunc  | 3         | 3      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 34        | 56.67%  |
| AMD                            | 10        | 16.67%  |
| Samsung Electronics            | 6         | 10%     |
| Sandisk                        | 2         | 3.33%   |
| Micron Technology              | 2         | 3.33%   |
| Toshiba America Info Systems   | 1         | 1.67%   |
| Solid State Storage Technology | 1         | 1.67%   |
| SK Hynix                       | 1         | 1.67%   |
| Phison Electronics             | 1         | 1.67%   |
| Micron/Crucial Technology      | 1         | 1.67%   |
| Apple                          | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 12.31%  |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 6.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 6.15%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 4.62%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 4.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 4.62%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 3.08%   |
| Micron Non-Volatile memory controller                                          | 2         | 3.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 3.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 3.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.54%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.54%   |
| SK Hynix BC511                                                                 | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.54%   |
| Samsung Electronics SATA controller                                            | 1         | 1.54%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.54%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.54%   |
| Intel SSD 660P Series                                                          | 1         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.54%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.54%   |
| Apple S3X NVMe Controller                                                      | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.54%   |
| AMD IXP SB4x0 Serial ATA Controller                                            | 1         | 1.54%   |
| AMD IXP SB4x0 IDE Controller                                                   | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 55.56%  |
| NVMe | 15        | 23.81%  |
| RAID | 8         | 12.7%   |
| IDE  | 5         | 7.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 79.17%  |
| AMD    | 10        | 20.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                  | 3         | 6.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 4.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 2         | 4.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 4.17%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 2.08%   |
| Intel Pentium M processor 1.73GHz               | 1         | 2.08%   |
| Intel Pentium CPU P6000 @ 1.87GHz               | 1         | 2.08%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 2.08%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 2.08%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 2.08%   |
| Intel Core i5-7360U CPU @ 2.30GHz               | 1         | 2.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 2.08%   |
| Intel Core i5-5250U CPU @ 1.60GHz               | 1         | 2.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 2.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.08%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 2.08%   |
| Intel Core i3-6100U CPU @ 2.30GHz               | 1         | 2.08%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 2.08%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1         | 2.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 2.08%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz            | 1         | 2.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.08%   |
| Intel Celeron M CPU 520 @ 1.60GHz               | 1         | 2.08%   |
| Intel Celeron M CPU 440 @ 1.86GHz               | 1         | 2.08%   |
| Intel Celeron CPU N2815 @ 1.86GHz               | 1         | 2.08%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 2.08%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 2.08%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz         | 1         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 1         | 2.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 2.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 1         | 2.08%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 2.08%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics     | 1         | 2.08%   |
| AMD C-50 Processor                              | 1         | 2.08%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 7         | 14.58%  |
| Other                | 6         | 12.5%   |
| Intel Core i3        | 5         | 10.42%  |
| Intel Core i7        | 4         | 8.33%   |
| Intel Core 2 Duo     | 4         | 8.33%   |
| Intel Atom           | 4         | 8.33%   |
| Intel Celeron        | 3         | 6.25%   |
| AMD Ryzen 7          | 3         | 6.25%   |
| AMD Ryzen 5          | 3         | 6.25%   |
| Intel Celeron M      | 2         | 4.17%   |
| Intel Pentium Silver | 1         | 2.08%   |
| Intel Pentium M      | 1         | 2.08%   |
| Intel Pentium        | 1         | 2.08%   |
| AMD Ryzen 3          | 1         | 2.08%   |
| AMD E2               | 1         | 2.08%   |
| AMD C-50             | 1         | 2.08%   |
| AMD A10              | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 58.33%  |
| 4      | 10        | 20.83%  |
| 8      | 4         | 8.33%   |
| 1      | 4         | 8.33%   |
| 6      | 2         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 70.83%  |
| 1      | 14        | 29.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 91.67%  |
| 32-bit         | 4         | 8.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 5         | 10.42%  |
| 0x406e3    | 3         | 6.25%   |
| 0x30661    | 3         | 6.25%   |
| 0x08608103 | 3         | 6.25%   |
| 0x806e9    | 2         | 4.17%   |
| 0x40651    | 2         | 4.17%   |
| 0x306a9    | 2         | 4.17%   |
| 0x20652    | 2         | 4.17%   |
| 0x1067a    | 2         | 4.17%   |
| 0xa0652    | 1         | 2.08%   |
| 0x806ec    | 1         | 2.08%   |
| 0x806d1    | 1         | 2.08%   |
| 0x706e5    | 1         | 2.08%   |
| 0x706a8    | 1         | 2.08%   |
| 0x706a1    | 1         | 2.08%   |
| 0x6fd      | 1         | 2.08%   |
| 0x6f6      | 1         | 2.08%   |
| 0x6ec      | 1         | 2.08%   |
| 0x6d8      | 1         | 2.08%   |
| 0x506e3    | 1         | 2.08%   |
| 0x306d4    | 1         | 2.08%   |
| 0x306c3    | 1         | 2.08%   |
| 0x30673    | 1         | 2.08%   |
| 0x106e5    | 1         | 2.08%   |
| 0x106c2    | 1         | 2.08%   |
| 0x10676    | 1         | 2.08%   |
| 0x08600103 | 1         | 2.08%   |
| 0x08108109 | 1         | 2.08%   |
| 0x08108102 | 1         | 2.08%   |
| 0x07030106 | 1         | 2.08%   |
| 0x0600611a | 1         | 2.08%   |
| 0x05000029 | 1         | 2.08%   |
| Unknown    | 1         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 5         | 10.42%  |
| Skylake       | 4         | 8.33%   |
| Bonnell       | 4         | 8.33%   |
| Penryn        | 3         | 6.25%   |
| KabyLake      | 3         | 6.25%   |
| Haswell       | 3         | 6.25%   |
| Unknown       | 3         | 6.25%   |
| Zen+          | 2         | 4.17%   |
| Westmere      | 2         | 4.17%   |
| P6            | 2         | 4.17%   |
| IvyBridge     | 2         | 4.17%   |
| IceLake       | 2         | 4.17%   |
| Goldmont plus | 2         | 4.17%   |
| Core          | 2         | 4.17%   |
| Zen 3         | 1         | 2.08%   |
| Zen 2         | 1         | 2.08%   |
| Silvermont    | 1         | 2.08%   |
| Puma          | 1         | 2.08%   |
| Nehalem       | 1         | 2.08%   |
| Excavator     | 1         | 2.08%   |
| CometLake     | 1         | 2.08%   |
| Broadwell     | 1         | 2.08%   |
| Bobcat        | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 60.38%  |
| AMD    | 12        | 22.64%  |
| Nvidia | 9         | 16.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 5.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 5.36%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 3         | 5.36%   |
| AMD Lucienne                                                                          | 3         | 5.36%   |
| Nvidia G98M [Quadro NVS 160M]                                                         | 2         | 3.57%   |
| Intel Tiger Lake UHD Graphics                                                         | 2         | 3.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.57%   |
| Nvidia GT216M [GeForce GT 325M]                                                       | 1         | 1.79%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 1.79%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                     | 1         | 1.79%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                    | 1         | 1.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 1.79%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                       | 1         | 1.79%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 1.79%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                             | 1         | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.79%   |
| Intel Iris Plus Graphics 640                                                          | 1         | 1.79%   |
| Intel HD Graphics 620                                                                 | 1         | 1.79%   |
| Intel HD Graphics 6000                                                                | 1         | 1.79%   |
| Intel HD Graphics 530                                                                 | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 1.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 1.79%   |
| AMD Renoir                                                                            | 1         | 1.79%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                              | 1         | 1.79%   |
| AMD Mullins [Radeon R2 Graphics]                                                      | 1         | 1.79%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 56.25%  |
| 1 x AMD        | 10        | 20.83%  |
| 1 x Nvidia     | 5         | 10.42%  |
| Intel + Nvidia | 4         | 8.33%   |
| 2 x AMD        | 1         | 2.08%   |
| Intel + AMD    | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 95.83%  |
| Proprietary | 1         | 2.08%   |
| Unknown     | 1         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 58.33%  |
| 0.01-0.5   | 9         | 18.75%  |
| 1.01-2.0   | 5         | 10.42%  |
| 0.51-1.0   | 3         | 6.25%   |
| 3.01-4.0   | 2         | 4.17%   |
| 5.01-6.0   | 1         | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 24.07%  |
| BOE                     | 8         | 14.81%  |
| Chimei Innolux          | 7         | 12.96%  |
| LG Display              | 5         | 9.26%   |
| Samsung Electronics     | 3         | 5.56%   |
| LG Philips              | 3         | 5.56%   |
| PANDA                   | 2         | 3.7%    |
| Dell                    | 2         | 3.7%    |
| Apple                   | 2         | 3.7%    |
| Sharp                   | 1         | 1.85%   |
| Quanta Display          | 1         | 1.85%   |
| Planar                  | 1         | 1.85%   |
| Insignia                | 1         | 1.85%   |
| InfoVision              | 1         | 1.85%   |
| HannStar                | 1         | 1.85%   |
| Goldstar                | 1         | 1.85%   |
| DENON                   | 1         | 1.85%   |
| Chi Mei Optoelectronics | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 3.64%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.82%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 1.82%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 1.82%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 1.82%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 1.82%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 1.82%   |
| Insignia NS-32F202NA22 BBY3292 1920x1080 697x392mm 31.5-inch             | 1         | 1.82%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 1         | 1.82%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 1.82%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 1.82%   |
| DENON AVR DON005F 1920x1080                                              | 1         | 1.82%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 1.82%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 1.82%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE08E8 1920x1080 340x190mm 15.3-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO26ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO20D5 1280x720 222x125mm 10.0-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 1.82%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 1         | 1.82%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 41.18%  |
| 1366x768 (WXGA)   | 13        | 25.49%  |
| 1920x1200 (WUXGA) | 3         | 5.88%   |
| 1440x900 (WXGA+)  | 3         | 5.88%   |
| 1024x600          | 3         | 5.88%   |
| 1280x800 (WXGA)   | 2         | 3.92%   |
| 3840x2160 (4K)    | 1         | 1.96%   |
| 2880x1800         | 1         | 1.96%   |
| 2560x1440 (QHD)   | 1         | 1.96%   |
| 1600x900 (HD+)    | 1         | 1.96%   |
| 1280x768          | 1         | 1.96%   |
| 1280x720 (HD)     | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 40%     |
| 13     | 10        | 18.18%  |
| 14     | 7         | 12.73%  |
| 27     | 3         | 5.45%   |
| 17     | 3         | 5.45%   |
| 10     | 3         | 5.45%   |
| 21     | 2         | 3.64%   |
| 72     | 1         | 1.82%   |
| 31     | 1         | 1.82%   |
| 24     | 1         | 1.82%   |
| 16     | 1         | 1.82%   |
| 8      | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 64.81%  |
| 201-300     | 7         | 12.96%  |
| 351-400     | 4         | 7.41%   |
| 501-600     | 3         | 5.56%   |
| 401-500     | 2         | 3.7%    |
| 601-700     | 1         | 1.85%   |
| 1501-2000   | 1         | 1.85%   |
| 101-200     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 83.33%  |
| 16/10 | 8         | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 40%     |
| 81-90          | 13        | 23.64%  |
| 71-80          | 4         | 7.27%   |
| 41-50          | 3         | 5.45%   |
| 301-350        | 3         | 5.45%   |
| 201-250        | 2         | 3.64%   |
| 121-130        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 351-500        | 1         | 1.82%   |
| 1-40           | 1         | 1.82%   |
| 251-300        | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |
| 91-100         | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 43.64%  |
| 101-120       | 20        | 36.36%  |
| 51-100        | 7         | 12.73%  |
| 161-240       | 2         | 3.64%   |
| More than 240 | 1         | 1.82%   |
| 1-50          | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 83.33%  |
| 2     | 6         | 12.5%   |
| 3     | 1         | 2.08%   |
| 0     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 29        | 39.73%  |
| Intel                         | 19        | 26.03%  |
| Qualcomm Atheros              | 11        | 15.07%  |
| Broadcom                      | 8         | 10.96%  |
| Ralink Technology             | 1         | 1.37%   |
| Ralink                        | 1         | 1.37%   |
| OnePlus Technology (Shenzhen) | 1         | 1.37%   |
| Marvell Technology Group      | 1         | 1.37%   |
| JMicron Technology            | 1         | 1.37%   |
| Broadcom Limited              | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 11.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.19%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 3.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 2.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.13%   |
| Intel Wireless 7260                                               | 2         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.13%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.13%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.06%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 1.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.06%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.06%   |
| Realtek 802.11ac NIC                                              | 1         | 1.06%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 1.06%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.06%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.06%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 1.06%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 1.06%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.06%   |
| Intel Wireless 3165                                               | 1         | 1.06%   |
| Intel Wireless 3160                                               | 1         | 1.06%   |
| Intel WiFi Link 5100                                              | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.06%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 1         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.06%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.06%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 1         | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.06%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.06%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 1         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.06%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.06%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 36.73%  |
| Realtek Semiconductor | 13        | 26.53%  |
| Qualcomm Atheros      | 9         | 18.37%  |
| Broadcom              | 6         | 12.24%  |
| Ralink Technology     | 1         | 2.04%   |
| Ralink                | 1         | 2.04%   |
| Broadcom Limited      | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 5.77%   |
| Intel Wireless 8265 / 8275                                     | 3         | 5.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.85%   |
| Intel Wireless 7260                                            | 2         | 3.85%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.85%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 3.85%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 3.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.92%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.92%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 1.92%   |
| Realtek 802.11ac NIC                                           | 1         | 1.92%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 1.92%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.92%   |
| Intel Wireless 3165                                            | 1         | 1.92%   |
| Intel Wireless 3160                                            | 1         | 1.92%   |
| Intel WiFi Link 5100                                           | 1         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.92%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 1         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.92%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 1.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.92%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.92%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 23        | 56.1%   |
| Intel                         | 9         | 21.95%  |
| Qualcomm Atheros              | 4         | 9.76%   |
| Broadcom                      | 2         | 4.88%   |
| OnePlus Technology (Shenzhen) | 1         | 2.44%   |
| Marvell Technology Group      | 1         | 2.44%   |
| JMicron Technology            | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 26.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 17.07%  |
| Intel 82567LM Gigabit Network Connection                          | 3         | 7.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 4.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.44%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 2.44%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 2.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 54.02%  |
| Ethernet | 39        | 44.83%  |
| Modem    | 1         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 77.55%  |
| Ethernet | 11        | 22.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 72.92%  |
| 1     | 12        | 25%     |
| 0     | 1         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 68.75%  |
| Yes  | 15        | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 43.75%  |
| Realtek Semiconductor           | 8         | 25%     |
| Qualcomm Atheros Communications | 2         | 6.25%   |
| Foxconn / Hon Hai               | 2         | 6.25%   |
| Dell                            | 2         | 6.25%   |
| Lite-On Technology              | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |
| Apple                           | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 21.88%  |
| Realtek Bluetooth Radio                        | 5         | 15.63%  |
| Intel AX201 Bluetooth                          | 4         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 9.38%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 6.25%   |
| Intel AX200 Bluetooth                          | 2         | 6.25%   |
| Dell Wireless 370 Bluetooth Mini-card          | 2         | 6.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 3.13%   |
| IMC Networks Bluetooth Device                  | 1         | 3.13%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 3.13%   |
| Foxconn / Hon Hai Acer Bluetooth module        | 1         | 3.13%   |
| Broadcom HP Portable SoftSailing               | 1         | 3.13%   |
| Apple Bluetooth USB Host Controller            | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 62.71%  |
| AMD                   | 12        | 20.34%  |
| Nvidia                | 5         | 8.47%   |
| Texas Instruments     | 2         | 3.39%   |
| Realtek Semiconductor | 1         | 1.69%   |
| GN Netcom             | 1         | 1.69%   |
| Audioengine           | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 9.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 6.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 6.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 6.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 5.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.17%   |
| Nvidia Audio device                                                        | 2         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 2.78%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 1.39%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 1.39%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.39%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.39%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.39%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.39%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.39%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                            | 1         | 1.39%   |
| Audioengine D1 24-bit DAC                                                  | 1         | 1.39%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.39%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.39%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 1.39%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 26.32%  |
| SK Hynix            | 4         | 21.05%  |
| Unknown             | 3         | 15.79%  |
| A-DATA Technology   | 2         | 10.53%  |
| Unknown (ABCD)      | 1         | 5.26%   |
| Nanya Technology    | 1         | 5.26%   |
| Micron Technology   | 1         | 5.26%   |
| Kingston            | 1         | 5.26%   |
| Corsair             | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 4.76%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 4.76%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 1         | 4.76%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 1         | 4.76%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 4.76%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 4.76%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 4.76%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 4.76%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 4.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s          | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s    | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 4.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 4.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 4.76%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR 2048MT/s            | 1         | 4.76%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s         | 1         | 4.76%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s            | 1         | 4.76%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s      | 1         | 4.76%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                     | 1         | 4.76%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s        | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 57.89%  |
| DDR3   | 3         | 15.79%  |
| SDRAM  | 2         | 10.53%  |
| LPDDR4 | 2         | 10.53%  |
| DDR    | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 90%     |
| Row Of Chips | 2         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 42.86%  |
| 4096  | 4         | 19.05%  |
| 2048  | 4         | 19.05%  |
| 32768 | 1         | 4.76%   |
| 16384 | 1         | 4.76%   |
| 1024  | 1         | 4.76%   |
| 512   | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 7         | 36.84%  |
| 2400    | 3         | 15.79%  |
| 1600    | 3         | 15.79%  |
| 4267    | 1         | 5.26%   |
| 4199    | 1         | 5.26%   |
| 2667    | 1         | 5.26%   |
| 2048    | 1         | 5.26%   |
| 1200    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Chicony Electronics                    | 8         | 21.05%  |
| Microdia                               | 7         | 18.42%  |
| IMC Networks                           | 5         | 13.16%  |
| Suyin                                  | 4         | 10.53%  |
| Sunplus Innovation Technology          | 3         | 7.89%   |
| Realtek Semiconductor                  | 2         | 5.26%   |
| Quanta                                 | 2         | 5.26%   |
| Luxvisions Innotech Limited            | 2         | 5.26%   |
| Lite-On Technology                     | 1         | 2.63%   |
| Intel                                  | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.63%   |
| ALi                                    | 1         | 2.63%   |
| Acer                                   | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 6         | 15.79%  |
| IMC Networks Integrated Camera                       | 2         | 5.26%   |
| Chicony HP Truevision HD camera                      | 2         | 5.26%   |
| Chicony HD Webcam                                    | 2         | 5.26%   |
| Suyin HP TrueVision HD                               | 1         | 2.63%   |
| Suyin HD WebCam                                      | 1         | 2.63%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 2.63%   |
| Suyin 1.3M HD WebCam                                 | 1         | 2.63%   |
| Sunplus HD WebCam                                    | 1         | 2.63%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 2.63%   |
| Sunplus 1.3M HD WebCam                               | 1         | 2.63%   |
| Realtek MTD camera                                   | 1         | 2.63%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 2.63%   |
| Quanta HP Webcam                                     | 1         | 2.63%   |
| Quanta HP HD Camera                                  | 1         | 2.63%   |
| Microdia Integrated Webcam HD                        | 1         | 2.63%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 2.63%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 2.63%   |
| Lite-On HP TrueVision HD Camera                      | 1         | 2.63%   |
| Intel RealSense 3D Camera (Front F200)               | 1         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 2.63%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 2.63%   |
| Chicony Integrated HP HD Webcam                      | 1         | 2.63%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 2.63%   |
| Chicony Integrated Camera                            | 1         | 2.63%   |
| Chicony 1.3M Webcam                                  | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 2.63%   |
| ALi Gateway Webcam                                   | 1         | 2.63%   |
| Acer Integrated Camera                               | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| Elan Microelectronics      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS491                    | 1         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 16.67%  |
| Elan ELAN:Fingerprint                      | 1         | 16.67%  |
| Unknown                                    | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 60%     |
| Broadcom 5880                                  | 1         | 20%     |
| Broadcom 58200                                 | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 65.31%  |
| 1     | 15        | 30.61%  |
| 2     | 2         | 4.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 25%     |
| Fingerprint reader    | 5         | 25%     |
| Chipcard              | 5         | 25%     |
| Net/wireless          | 4         | 20%     |
| Graphics card         | 1         | 5%      |

