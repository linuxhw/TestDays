Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.11.0-43-generic  | 40        | 86.96%  |
| 5.11.0-41-generic  | 3         | 6.52%   |
| 5.8.0-50-generic   | 1         | 2.17%   |
| 5.15.12-xanmod1-tt | 1         | 2.17%   |
| 5.11.0-44-generic  | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 44        | 95.65%  |
| 5.8.0   | 1         | 2.17%   |
| 5.15.12 | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 44        | 95.65%  |
| 5.8     | 1         | 2.17%   |
| 5.15    | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 46        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 46        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 63.04%  |
| LightDM | 17        | 36.96%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 52.17%  |
| en_GB | 6         | 13.04%  |
| de_DE | 6         | 13.04%  |
| pt_BR | 4         | 8.7%    |
| pl_PL | 2         | 4.35%   |
| ru_RU | 1         | 2.17%   |
| it_IT | 1         | 2.17%   |
| fr_FR | 1         | 2.17%   |
| es_ES | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 35        | 76.09%  |
| BIOS | 11        | 23.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 93.48%  |
| Btrfs   | 2         | 4.35%   |
| Overlay | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 31        | 67.39%  |
| GPT     | 14        | 30.43%  |
| MBR     | 1         | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 93.48%  |
| Yes       | 3         | 6.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 89.13%  |
| Yes       | 5         | 10.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 23.91%  |
| Dell             | 9         | 19.57%  |
| Apple            | 6         | 13.04%  |
| ASUSTek Computer | 4         | 8.7%    |
| Hewlett-Packard  | 3         | 6.52%   |
| Acer             | 3         | 6.52%   |
| Monster          | 2         | 4.35%   |
| Wortmann AG      | 1         | 2.17%   |
| Timi             | 1         | 2.17%   |
| Teclast          | 1         | 2.17%   |
| Star Labs        | 1         | 2.17%   |
| Notebook         | 1         | 2.17%   |
| MSI              | 1         | 2.17%   |
| LG Electronics   | 1         | 2.17%   |
| HUAWEI           | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Wortmann AG 1220729_1470271            | 1         | 2.17%   |
| Timi TM1613                            | 1         | 2.17%   |
| Teclast F7                             | 1         | 2.17%   |
| Star Labs LabTop                       | 1         | 2.17%   |
| Notebook P65xHP                        | 1         | 2.17%   |
| MSI PS63 Modern 8RD                    | 1         | 2.17%   |
| Monster MARKUT M7 V1.x                 | 1         | 2.17%   |
| Monster ABRA A5 V13.2                  | 1         | 2.17%   |
| LG A410-G.BC51P1                       | 1         | 2.17%   |
| Lenovo Yoga 300-11IBR 80M1             | 1         | 2.17%   |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00   | 1         | 2.17%   |
| Lenovo ThinkPad W541 20EGS1VV00        | 1         | 2.17%   |
| Lenovo ThinkPad T470 W10DG 20JNS08H00  | 1         | 2.17%   |
| Lenovo ThinkPad T430 23501M2           | 1         | 2.17%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00E00  | 1         | 2.17%   |
| Lenovo ThinkPad E495 20NE001RTX        | 1         | 2.17%   |
| Lenovo Legion Y530-15ICH 81GT          | 1         | 2.17%   |
| Lenovo IdeaPad 320-14AST 80XU          | 1         | 2.17%   |
| Lenovo IdeaPad 310-15ISK 80SM          | 1         | 2.17%   |
| Lenovo Flex 2-14D 20376                | 1         | 2.17%   |
| HUAWEI KPL-W0X                         | 1         | 2.17%   |
| HP Pavilion Laptop 15-cs0xxx           | 1         | 2.17%   |
| HP EliteBook 850 G2                    | 1         | 2.17%   |
| HP EliteBook 8460p                     | 1         | 2.17%   |
| Dell XPS 13 9343                       | 1         | 2.17%   |
| Dell Vostro 15 3515                    | 1         | 2.17%   |
| Dell Precision M6500                   | 1         | 2.17%   |
| Dell Precision M3800                   | 1         | 2.17%   |
| Dell Precision 5530                    | 1         | 2.17%   |
| Dell Latitude 3580                     | 1         | 2.17%   |
| Dell Inspiron N5050                    | 1         | 2.17%   |
| Dell Inspiron 5555                     | 1         | 2.17%   |
| Dell Inspiron 3542                     | 1         | 2.17%   |
| ASUS X555UB                            | 1         | 2.17%   |
| ASUS VivoBook_ASUSLaptop X512FA_A512FA | 1         | 2.17%   |
| ASUS UX410UAK                          | 1         | 2.17%   |
| ASUS E202SA                            | 1         | 2.17%   |
| Apple MacBookPro9,2                    | 1         | 2.17%   |
| Apple MacBookPro5,1                    | 1         | 2.17%   |
| Apple MacBookAir7,2                    | 1         | 2.17%   |
| Apple MacBookAir6,1                    | 1         | 2.17%   |
| Apple MacBook5,2                       | 1         | 2.17%   |
| Apple MacBook4,1                       | 1         | 2.17%   |
| Acer TravelMate 5760                   | 1         | 2.17%   |
| Acer Aspire A315-42                    | 1         | 2.17%   |
| Acer Aspire 7750G                      | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 6         | 13.04%  |
| Dell Precision      | 3         | 6.52%   |
| Dell Inspiron       | 3         | 6.52%   |
| Lenovo IdeaPad      | 2         | 4.35%   |
| HP EliteBook        | 2         | 4.35%   |
| Acer Aspire         | 2         | 4.35%   |
| Wortmann AG 1220729 | 1         | 2.17%   |
| Timi TM1613         | 1         | 2.17%   |
| Teclast F7          | 1         | 2.17%   |
| Star Labs LabTop    | 1         | 2.17%   |
| Notebook P65xHP     | 1         | 2.17%   |
| MSI PS63            | 1         | 2.17%   |
| Monster MARKUT      | 1         | 2.17%   |
| Monster ABRA        | 1         | 2.17%   |
| LG A410-G.BC51P1    | 1         | 2.17%   |
| Lenovo Yoga         | 1         | 2.17%   |
| Lenovo Legion       | 1         | 2.17%   |
| Lenovo Flex         | 1         | 2.17%   |
| HUAWEI KPL-W0X      | 1         | 2.17%   |
| HP Pavilion         | 1         | 2.17%   |
| Dell XPS            | 1         | 2.17%   |
| Dell Vostro         | 1         | 2.17%   |
| Dell Latitude       | 1         | 2.17%   |
| ASUS X555UB         | 1         | 2.17%   |
| ASUS VivoBook       | 1         | 2.17%   |
| ASUS UX410UAK       | 1         | 2.17%   |
| ASUS E202SA         | 1         | 2.17%   |
| Apple MacBookPro9   | 1         | 2.17%   |
| Apple MacBookPro5   | 1         | 2.17%   |
| Apple MacBookAir7   | 1         | 2.17%   |
| Apple MacBookAir6   | 1         | 2.17%   |
| Apple MacBook5      | 1         | 2.17%   |
| Apple MacBook4      | 1         | 2.17%   |
| Acer TravelMate     | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 21.74%  |
| 2021 | 7         | 15.22%  |
| 2020 | 6         | 13.04%  |
| 2018 | 5         | 10.87%  |
| 2015 | 4         | 8.7%    |
| 2011 | 4         | 8.7%    |
| 2016 | 3         | 6.52%   |
| 2012 | 2         | 4.35%   |
| 2017 | 1         | 2.17%   |
| 2014 | 1         | 2.17%   |
| 2013 | 1         | 2.17%   |
| 2009 | 1         | 2.17%   |
| 2008 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 41        | 89.13%  |
| Enabled  | 5         | 10.87%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 97.83%  |
| Yes  | 1         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 43.48%  |
| 3.01-4.0    | 9         | 19.57%  |
| 8.01-16.0   | 7         | 15.22%  |
| 16.01-24.0  | 5         | 10.87%  |
| 32.01-64.0  | 2         | 4.35%   |
| 1.01-2.0    | 2         | 4.35%   |
| 64.01-256.0 | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 41.3%   |
| 1.01-2.0  | 10        | 21.74%  |
| 3.01-4.0  | 6         | 13.04%  |
| 4.01-8.0  | 5         | 10.87%  |
| 8.01-16.0 | 4         | 8.7%    |
| 0.51-1.0  | 2         | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 63.04%  |
| 2      | 13        | 28.26%  |
| 3      | 3         | 6.52%   |
| 5      | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 76.09%  |
| Yes       | 11        | 23.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 71.74%  |
| No        | 13        | 28.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 93.48%  |
| No        | 3         | 6.52%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| India       | 6         | 13.04%  |
| Brazil      | 5         | 10.87%  |
| USA         | 4         | 8.7%    |
| Germany     | 4         | 8.7%    |
| Turkey      | 3         | 6.52%   |
| Poland      | 3         | 6.52%   |
| Italy       | 3         | 6.52%   |
| UK          | 2         | 4.35%   |
| Australia   | 2         | 4.35%   |
| Ukraine     | 1         | 2.17%   |
| Sweden      | 1         | 2.17%   |
| Romania     | 1         | 2.17%   |
| Portugal    | 1         | 2.17%   |
| Pakistan    | 1         | 2.17%   |
| New Zealand | 1         | 2.17%   |
| Netherlands | 1         | 2.17%   |
| Mexico      | 1         | 2.17%   |
| Indonesia   | 1         | 2.17%   |
| Guyana      | 1         | 2.17%   |
| France      | 1         | 2.17%   |
| Colombia    | 1         | 2.17%   |
| Belarus     | 1         | 2.17%   |
| Austria     | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Sydney                 | 2         | 4.35%   |
| Ankara                 | 2         | 4.35%   |
| Wroclaw                | 1         | 2.17%   |
| Wriedel                | 1         | 2.17%   |
| Wellington             | 1         | 2.17%   |
| Vinnytsia              | 1         | 2.17%   |
| Vienna                 | 1         | 2.17%   |
| Tecuci                 | 1         | 2.17%   |
| Soliera                | 1         | 2.17%   |
| Shetland Islands       | 1         | 2.17%   |
| S??o Paulo             | 1         | 2.17%   |
| S??o Bernardo do Campo | 1         | 2.17%   |
| San Antonio            | 1         | 2.17%   |
| Saltsjoe-Boo           | 1         | 2.17%   |
| Rome                   | 1         | 2.17%   |
| Porto                  | 1         | 2.17%   |
| Osasco                 | 1         | 2.17%   |
| Mumbai                 | 1         | 2.17%   |
| Montm?�dy              | 1         | 2.17%   |
| Minsk                  | 1         | 2.17%   |
| Mahemdavad             | 1         | 2.17%   |
| Jember                 | 1         | 2.17%   |
| Itaquaquecetuba        | 1         | 2.17%   |
| Islamabad              | 1         | 2.17%   |
| Hyderabad              | 1         | 2.17%   |
| Hudson                 | 1         | 2.17%   |
| Holland                | 1         | 2.17%   |
| Gliwice                | 1         | 2.17%   |
| Georgetown             | 1         | 2.17%   |
| Gdansk                 | 1         | 2.17%   |
| Erkrath                | 1         | 2.17%   |
| Dhanbad                | 1         | 2.17%   |
| Cuernavaca             | 1         | 2.17%   |
| Chalfont               | 1         | 2.17%   |
| Cesate                 | 1         | 2.17%   |
| Cartagena              | 1         | 2.17%   |
| Cabo Frio              | 1         | 2.17%   |
| Burgess Hill           | 1         | 2.17%   |
| Bengaluru              | 1         | 2.17%   |
| Bad Friedrichshall     | 1         | 2.17%   |
| Antalya                | 1         | 2.17%   |
| Alphen aan den Rijn    | 1         | 2.17%   |
| Ahmedabad              | 1         | 2.17%   |
| Aachen                 | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 18.46%  |
| WDC                 | 8         | 8      | 12.31%  |
| Seagate             | 6         | 6      | 9.23%   |
| Crucial             | 6         | 6      | 9.23%   |
| SanDisk             | 4         | 4      | 6.15%   |
| Kingston            | 4         | 4      | 6.15%   |
| Unknown             | 2         | 2      | 3.08%   |
| SK Hynix            | 2         | 2      | 3.08%   |
| Micron Technology   | 2         | 2      | 3.08%   |
| Hitachi             | 2         | 2      | 3.08%   |
| HGST                | 2         | 2      | 3.08%   |
| Unknown             | 2         | 2      | 3.08%   |
| Transcend           | 1         | 1      | 1.54%   |
| Toshiba             | 1         | 1      | 1.54%   |
| Teclast             | 1         | 1      | 1.54%   |
| Star                | 1         | 1      | 1.54%   |
| Silicon Motion      | 1         | 1      | 1.54%   |
| SABRENT             | 1         | 1      | 1.54%   |
| LITEON              | 1         | 1      | 1.54%   |
| KIOXIA              | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 1      | 1.54%   |
| Fujitsu             | 1         | 1      | 1.54%   |
| China               | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 4.48%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 2         | 2.99%   |
| Samsung SSD 850 EVO 250GB                 | 2         | 2.99%   |
| Samsung NVMe SSD Drive 256GB              | 2         | 2.99%   |
| Unknown                                   | 2         | 2.99%   |
| WDC WD7500BPVT-22A1YT0 752GB              | 1         | 1.49%   |
| WDC WD5000BPVT-22HXZT1 500GB              | 1         | 1.49%   |
| WDC WD20SPZX-22UA7T0 2TB                  | 1         | 1.49%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.49%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 1.49%   |
| WDC PC SN520 SDAPNUW-512G                 | 1         | 1.49%   |
| Unknown USD00  16GB                       | 1         | 1.49%   |
| Unknown GD2S5  128GB                      | 1         | 1.49%   |
| Transcend TS512GMTS430S 512GB SSD         | 1         | 1.49%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.49%   |
| Teclast 128GB NS550-2242 SSD              | 1         | 1.49%   |
| Star Drive SATA SSD 960GB                 | 1         | 1.49%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 1.49%   |
| SK Hynix HFM128GDHTNG-8510B 128GB         | 1         | 1.49%   |
| Silicon Motion NVMe SSD Drive 120GB       | 1         | 1.49%   |
| Seagate ST9500325AS 500GB                 | 1         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.49%   |
| Seagate Expansion Desk 8TB                | 1         | 1.49%   |
| SanDisk SD9SN8W256G1027 256GB SSD         | 1         | 1.49%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 1.49%   |
| SanDisk SD8SNAT128G1002 128GB SSD         | 1         | 1.49%   |
| Sandisk NVMe SSD Drive 250GB              | 1         | 1.49%   |
| Samsung SSD SM841 mSATA 512GB             | 1         | 1.49%   |
| Samsung SSD 950 PRO 512GB                 | 1         | 1.49%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.49%   |
| Samsung SSD 850 EVO 2TB                   | 1         | 1.49%   |
| Samsung SSD 850 EVO 1TB                   | 1         | 1.49%   |
| Samsung PSSD T7 Touch 2TB                 | 1         | 1.49%   |
| Samsung Portable SSD T5 500GB             | 1         | 1.49%   |
| Samsung NVMe SSD Drive 512GB              | 1         | 1.49%   |
| Samsung MZVLB512HBJQ-000L7 512GB          | 1         | 1.49%   |
| Samsung MZMPA064HMDR-00000 64GB SSD       | 1         | 1.49%   |
| SABRENT Disk 320GB                        | 1         | 1.49%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD       | 1         | 1.49%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD       | 1         | 1.49%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD   | 1         | 1.49%   |
| KIOXIA NVMe SSD Drive 256GB               | 1         | 1.49%   |
| Kingston SV300S37A120G 120GB SSD          | 1         | 1.49%   |
| Kingston SA400S37240G 240GB SSD           | 1         | 1.49%   |
| Kingston SA1000M8240G 240GB               | 1         | 1.49%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD     | 1         | 1.49%   |
| KingSpec P4-120 120GB                     | 1         | 1.49%   |
| Hitachi HTS725032A7E630 320GB             | 1         | 1.49%   |
| Hitachi HTS543212L9SA02 120GB             | 1         | 1.49%   |
| HGST HTS545050A7E680 500GB                | 1         | 1.49%   |
| HGST HTS545050A7E380 500GB                | 1         | 1.49%   |
| Fujitsu MHY2250BH 250GB                   | 1         | 1.49%   |
| Crucial CT480BX500SSD1 480GB              | 1         | 1.49%   |
| Crucial CT250MX500SSD1 250GB              | 1         | 1.49%   |
| Crucial CT2000MX500SSD1 2TB               | 1         | 1.49%   |
| Crucial CT120BX300SSD1 120GB              | 1         | 1.49%   |
| Crucial CT1050MX300SSD4 1050GB            | 1         | 1.49%   |
| Crucial CT1000MX500SSD1 1TB               | 1         | 1.49%   |
| China SSD 240GB                           | 1         | 1.49%   |
| Apple SSD SM0128G 121GB                   | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 35%     |
| Seagate | 6         | 6      | 30%     |
| Hitachi | 2         | 2      | 10%     |
| HGST    | 2         | 2      | 10%     |
| Toshiba | 1         | 1      | 5%      |
| SABRENT | 1         | 1      | 5%      |
| Fujitsu | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 25.81%  |
| Crucial             | 6         | 6      | 19.35%  |
| SanDisk             | 3         | 3      | 9.68%   |
| Kingston            | 3         | 3      | 9.68%   |
| Micron Technology   | 2         | 2      | 6.45%   |
| Transcend           | 1         | 1      | 3.23%   |
| Teclast             | 1         | 1      | 3.23%   |
| Star                | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |
| Unknown             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 27        | 33     | 43.55%  |
| HDD  | 20        | 20     | 32.26%  |
| NVMe | 12        | 13     | 19.35%  |
| MMC  | 3         | 3      | 4.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 49     | 68.42%  |
| NVMe | 12        | 13     | 21.05%  |
| SAS  | 3         | 4      | 5.26%   |
| MMC  | 3         | 3      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 33     | 62.22%  |
| 0.51-1.0   | 13        | 13     | 28.89%  |
| 1.01-2.0   | 3         | 6      | 6.67%   |
| 4.01-10.0  | 1         | 1      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 41.3%   |
| 251-500        | 14        | 30.43%  |
| 1001-2000      | 5         | 10.87%  |
| 501-1000       | 5         | 10.87%  |
| 51-100         | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 15        | 32.61%  |
| 1-20      | 14        | 30.43%  |
| 51-100    | 6         | 13.04%  |
| 101-250   | 4         | 8.7%    |
| 251-500   | 3         | 6.52%   |
| 501-1000  | 3         | 6.52%   |
| 2001-3000 | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 36        | 46     | 69.23%  |
| Works    | 15        | 22     | 28.85%  |
| Malfunc  | 1         | 1      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 33        | 62.26%  |
| Samsung Electronics         | 6         | 11.32%  |
| AMD                         | 6         | 11.32%  |
| SK Hynix                    | 2         | 3.77%   |
| Sandisk                     | 2         | 3.77%   |
| Nvidia                      | 2         | 3.77%   |
| Silicon Motion              | 1         | 1.89%   |
| Kingston Technology Company | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 12.96%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 11.11%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 7.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 3.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 3.7%    |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 3.7%    |
| SK Hynix Non-Volatile memory controller                                          | 1         | 1.85%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 1.85%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.85%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.85%   |
| Samsung Electronics SATA controller                                              | 1         | 1.85%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 74.07%  |
| NVMe | 11        | 20.37%  |
| RAID | 2         | 3.7%    |
| IDE  | 1         | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 80.43%  |
| AMD    | 9         | 19.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 6.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 4.35%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 2.17%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 2.17%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 2.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.17%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 2.17%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 2.17%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2.17%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 2.17%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 2.17%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.17%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 2.17%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 2.17%   |
| Intel Core i3 CPU M 390 @ 2.67GHz             | 1         | 2.17%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 2.17%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 1         | 2.17%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 1         | 2.17%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.17%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.17%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 13        | 28.26%  |
| Intel Core i5    | 12        | 26.09%  |
| Intel Core i3    | 6         | 13.04%  |
| Intel Core 2 Duo | 3         | 6.52%   |
| AMD Ryzen 5      | 3         | 6.52%   |
| Intel Celeron    | 2         | 4.35%   |
| AMD Ryzen 7 PRO  | 2         | 4.35%   |
| Other            | 1         | 2.17%   |
| Intel Pentium    | 1         | 2.17%   |
| AMD Ryzen 3      | 1         | 2.17%   |
| AMD A8           | 1         | 2.17%   |
| AMD A6           | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 54.35%  |
| 4      | 16        | 34.78%  |
| 6      | 3         | 6.52%   |
| 8      | 2         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 80.43%  |
| 1      | 9         | 19.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x406e3    | 4         | 8.7%    |
| 0x206a7    | 4         | 8.7%    |
| Unknown    | 4         | 8.7%    |
| 0x306d4    | 3         | 6.52%   |
| 0x906ea    | 2         | 4.35%   |
| 0x406c3    | 2         | 4.35%   |
| 0x40651    | 2         | 4.35%   |
| 0x306c3    | 2         | 4.35%   |
| 0x306a9    | 2         | 4.35%   |
| 0x10676    | 2         | 4.35%   |
| 0x08600106 | 2         | 4.35%   |
| 0x08108102 | 2         | 4.35%   |
| 0xa0660    | 1         | 2.17%   |
| 0x906e9    | 1         | 2.17%   |
| 0x806ec    | 1         | 2.17%   |
| 0x806eb    | 1         | 2.17%   |
| 0x806ea    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x506e3    | 1         | 2.17%   |
| 0x506c9    | 1         | 2.17%   |
| 0x106e5    | 1         | 2.17%   |
| 0x1067a    | 1         | 2.17%   |
| 0x08108109 | 1         | 2.17%   |
| 0x08101007 | 1         | 2.17%   |
| 0x07030105 | 1         | 2.17%   |
| 0x07030104 | 1         | 2.17%   |
| 0x06006704 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 19.57%  |
| Skylake     | 6         | 13.04%  |
| SandyBridge | 4         | 8.7%    |
| Haswell     | 4         | 8.7%    |
| Zen+        | 3         | 6.52%   |
| Penryn      | 3         | 6.52%   |
| Broadwell   | 3         | 6.52%   |
| Zen 2       | 2         | 4.35%   |
| Silvermont  | 2         | 4.35%   |
| Puma        | 2         | 4.35%   |
| IvyBridge   | 2         | 4.35%   |
| Zen         | 1         | 2.17%   |
| Westmere    | 1         | 2.17%   |
| Nehalem     | 1         | 2.17%   |
| Goldmont    | 1         | 2.17%   |
| Excavator   | 1         | 2.17%   |
| CometLake   | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 58.93%  |
| Nvidia | 13        | 23.21%  |
| AMD    | 10        | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 5.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 5.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 3.45%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.45%   |
| AMD Renoir                                                                               | 2         | 3.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 3.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 1.72%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.72%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.72%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.72%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.72%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.72%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.72%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.72%   |
| Intel HD Graphics 630                                                                    | 1         | 1.72%   |
| Intel HD Graphics 620                                                                    | 1         | 1.72%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.72%   |
| Intel HD Graphics 520                                                                    | 1         | 1.72%   |
| Intel HD Graphics 500                                                                    | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.72%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.72%   |
| AMD Broadway XT [Mobility Radeon HD 5870]                                                | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 50%     |
| Intel + Nvidia | 10        | 21.74%  |
| 1 x AMD        | 10        | 21.74%  |
| 1 x Nvidia     | 2         | 4.35%   |
| 2 x Nvidia     | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 84.78%  |
| Proprietary | 7         | 15.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 58.7%   |
| 1.01-2.0   | 6         | 13.04%  |
| 0.51-1.0   | 6         | 13.04%  |
| 0.01-0.5   | 4         | 8.7%    |
| 3.01-4.0   | 2         | 4.35%   |
| 5.01-6.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 10        | 18.52%  |
| LG Display          | 9         | 16.67%  |
| AU Optronics        | 9         | 16.67%  |
| Apple               | 6         | 11.11%  |
| Sharp               | 5         | 9.26%   |
| BOE                 | 4         | 7.41%   |
| Samsung Electronics | 3         | 5.56%   |
| Goldstar            | 2         | 3.7%    |
| Dell                | 2         | 3.7%    |
| PANDA               | 1         | 1.85%   |
| Lenovo              | 1         | 1.85%   |
| Hewlett-Packard     | 1         | 1.85%   |
| BenQ                | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 2         | 3.57%   |
| Sharp PN-K321 SHP21DD 3840x2160                                      | 1         | 1.79%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 1         | 1.79%   |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch              | 1         | 1.79%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch              | 1         | 1.79%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch              | 1         | 1.79%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch | 1         | 1.79%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch         | 1         | 1.79%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 1.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 1.79%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                 | 1         | 1.79%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch             | 1         | 1.79%   |
| Hewlett-Packard V196bz HWP323E 1366x768 410x230mm 18.5-inch          | 1         | 1.79%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1         | 1.79%   |
| Goldstar E2442 GSM58C6 1920x1080 531x299mm 24.0-inch                 | 1         | 1.79%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                    | 1         | 1.79%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                    | 1         | 1.79%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 1         | 1.79%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                | 1         | 1.79%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 1         | 1.79%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 1.79%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                   | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 1.79%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 1         | 1.79%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 1.79%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 1         | 1.79%   |
| Apple Color LCD APP9C85 1440x900 340x220mm 15.9-inch                 | 1         | 1.79%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 1.79%   |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                 | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 21        | 39.62%  |
| 1366x768 (WXGA)  | 16        | 30.19%  |
| 3840x2160 (4K)   | 4         | 7.55%   |
| 2560x1440 (QHD)  | 3         | 5.66%   |
| 1280x800 (WXGA)  | 3         | 5.66%   |
| 1600x900 (HD+)   | 2         | 3.77%   |
| 1440x900 (WXGA+) | 2         | 3.77%   |
| 3200x1800 (QHD+) | 1         | 1.89%   |
| 2560x1080        | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 21        | 38.89%  |
| 13      | 13        | 24.07%  |
| 14      | 6         | 11.11%  |
| 11      | 3         | 5.56%   |
| 24      | 2         | 3.7%    |
| 17      | 2         | 3.7%    |
| 34      | 1         | 1.85%   |
| 31      | 1         | 1.85%   |
| 27      | 1         | 1.85%   |
| 25      | 1         | 1.85%   |
| 23      | 1         | 1.85%   |
| 18      | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 59.26%  |
| 201-300     | 11        | 20.37%  |
| 501-600     | 5         | 9.26%   |
| 351-400     | 2         | 3.7%    |
| 701-800     | 1         | 1.85%   |
| 601-700     | 1         | 1.85%   |
| 401-500     | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 86.96%  |
| 16/10 | 4         | 8.7%    |
| 3/2   | 1         | 2.17%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 37.04%  |
| 81-90          | 14        | 25.93%  |
| 71-80          | 5         | 9.26%   |
| 51-60          | 3         | 5.56%   |
| 201-250        | 3         | 5.56%   |
| 351-500        | 2         | 3.7%    |
| 121-130        | 2         | 3.7%    |
| 301-350        | 1         | 1.85%   |
| 251-300        | 1         | 1.85%   |
| 141-150        | 1         | 1.85%   |
| 111-120        | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 43.4%   |
| 101-120       | 19        | 35.85%  |
| 51-100        | 4         | 7.55%   |
| More than 240 | 3         | 5.66%   |
| 161-240       | 3         | 5.66%   |
| Unknown       | 1         | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 80.43%  |
| 2     | 7         | 15.22%  |
| 3     | 2         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 26        | 35.14%  |
| Realtek Semiconductor    | 22        | 29.73%  |
| Qualcomm Atheros         | 10        | 13.51%  |
| Broadcom                 | 7         | 9.46%   |
| TP-Link                  | 2         | 2.7%    |
| Nvidia                   | 2         | 2.7%    |
| Broadcom Limited         | 2         | 2.7%    |
| Xiaomi                   | 1         | 1.35%   |
| Ralink                   | 1         | 1.35%   |
| Marvell Technology Group | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 18.07%  |
| Intel Wireless 8260                                               | 4         | 4.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.61%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.41%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.41%   |
| Intel Wireless-AC 9260                                            | 2         | 2.41%   |
| Intel Wireless 7265                                               | 2         | 2.41%   |
| Intel Wireless 7260                                               | 2         | 2.41%   |
| Intel Wireless 3165                                               | 2         | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 2.41%   |
| Broadcom BCM43227 802.11b/g/n                                     | 2         | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.2%    |
| TP-Link 802.11n NIC                                               | 1         | 1.2%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.2%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.2%    |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 55.32%  |
| Qualcomm Atheros      | 7         | 14.89%  |
| Broadcom              | 7         | 14.89%  |
| TP-Link               | 2         | 4.26%   |
| Realtek Semiconductor | 2         | 4.26%   |
| Broadcom Limited      | 2         | 4.26%   |
| Ralink                | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 8.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 6.38%   |
| Intel Wireless 8265 / 8275                                     | 3         | 6.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 4.26%   |
| Intel Wireless-AC 9260                                         | 2         | 4.26%   |
| Intel Wireless 7265                                            | 2         | 4.26%   |
| Intel Wireless 7260                                            | 2         | 4.26%   |
| Intel Wireless 3165                                            | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 4.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 4.26%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 4.26%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 4.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 4.26%   |
| TP-Link 802.11n NIC                                            | 1         | 2.13%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 60%     |
| Intel                    | 5         | 14.29%  |
| Qualcomm Atheros         | 3         | 8.57%   |
| Nvidia                   | 2         | 5.71%   |
| Broadcom                 | 2         | 5.71%   |
| Xiaomi                   | 1         | 2.86%   |
| Marvell Technology Group | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 41.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 8.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 5.56%   |
| Nvidia MCP79 Ethernet                                             | 2         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.78%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.78%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 58.23%  |
| Ethernet | 33        | 41.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 61.33%  |
| Ethernet | 29        | 38.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 63.04%  |
| 1     | 16        | 34.78%  |
| 3     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 54.35%  |
| Yes  | 21        | 45.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 56.82%  |
| Apple                           | 6         | 13.64%  |
| Qualcomm Atheros Communications | 5         | 11.36%  |
| Realtek Semiconductor           | 2         | 4.55%   |
| Lite-On Technology              | 1         | 2.27%   |
| IMC Networks                    | 1         | 2.27%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn / Hon Hai               | 1         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 2.27%   |
| Broadcom                        | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 36.36%  |
| Intel Bluetooth Device                              | 5         | 11.36%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 9.09%   |
| Apple Bluetooth USB Host Controller                 | 3         | 6.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.27%   |
| Realtek Bluetooth Radio                             | 1         | 2.27%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.27%   |
| IMC Networks Bluetooth Device                       | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.27%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.27%   |
| Apple Bluetooth Host Controller                     | 1         | 2.27%   |
| Apple Bluetooth HCI                                 | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 35        | 63.64%  |
| AMD                     | 10        | 18.18%  |
| Nvidia                  | 7         | 12.73%  |
| Texas Instruments       | 1         | 1.82%   |
| Realtek Semiconductor   | 1         | 1.82%   |
| BEHRINGER International | 1         | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 9.86%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 6         | 8.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 5.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.23%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.23%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 2.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.82%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.41%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.41%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.41%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.41%   |
| BEHRINGER International UMC202HD 192k                                                             | 1         | 1.41%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 1.41%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 47.06%  |
| SK Hynix            | 4         | 23.53%  |
| Micron Technology   | 3         | 17.65%  |
| G.Skill             | 1         | 5.88%   |
| Crucial             | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s    | 2         | 10.53%  |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 10.53%  |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 5.26%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 5.26%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s      | 1         | 5.26%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 5.26%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 5.26%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1         | 5.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 5.26%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 1         | 5.26%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s  | 1         | 5.26%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s  | 1         | 5.26%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s | 1         | 5.26%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s             | 1         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s  | 1         | 5.26%   |
| G.Skill RAM F4-2666C18-16GRS 16384MB SODIMM DDR4 2667MT/s | 1         | 5.26%   |
| Crucial RAM CB8GS2400.C8D 8192MB SODIMM DDR4 2400MT/s     | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 11        | 68.75%  |
| DDR3 | 5         | 31.25%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 15        | 93.75%  |
| Chip   | 1         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 44.44%  |
| 4096  | 5         | 27.78%  |
| 16384 | 3         | 16.67%  |
| 2048  | 2         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 6         | 35.29%  |
| 1600  | 5         | 29.41%  |
| 3200  | 2         | 11.76%  |
| 2133  | 2         | 11.76%  |
| 3266  | 1         | 5.88%   |
| 2400  | 1         | 5.88%   |

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


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Canon PIXMA MG2500 Series | 1         | 100%    |

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
| Chicony Electronics                    | 8         | 19.51%  |
| Realtek Semiconductor                  | 7         | 17.07%  |
| Acer                                   | 6         | 14.63%  |
| IMC Networks                           | 4         | 9.76%   |
| Microdia                               | 3         | 7.32%   |
| Apple                                  | 3         | 7.32%   |
| Alcor Micro                            | 3         | 7.32%   |
| Quanta                                 | 2         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Y Media                                | 1         | 2.44%   |
| Suyin                                  | 1         | 2.44%   |
| Ricoh                                  | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 3         | 7.32%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.88%   |
| IMC Networks Integrated Camera                                             | 2         | 4.88%   |
| Chicony Integrated Camera                                                  | 2         | 4.88%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 4.88%   |
| Acer Lenovo EasyCamera                                                     | 2         | 4.88%   |
| Y Media USB Camera                                                         | 1         | 2.44%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2.44%   |
| Ricoh Dell Laptop Integrated Webcam                                        | 1         | 2.44%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 2.44%   |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 2.44%   |
| Realtek USB Camera                                                         | 1         | 2.44%   |
| Realtek LG Webcam                                                          | 1         | 2.44%   |
| Realtek Integrated Webcam                                                  | 1         | 2.44%   |
| Quanta VGA WebCam                                                          | 1         | 2.44%   |
| Quanta hm1091_techfront                                                    | 1         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.44%   |
| IMC Networks EasyCamera                                                    | 1         | 2.44%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 2.44%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.44%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.44%   |
| Chicony thinkpad t430s camera                                              | 1         | 2.44%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.44%   |
| Chicony HD Webcam                                                          | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 2.44%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.44%   |
| Apple Built-in iSight [Micron]                                             | 1         | 2.44%   |
| Apple Built-in iSight                                                      | 1         | 2.44%   |
| Alcor Micro USB 2.0 PC Camera                                              | 1         | 2.44%   |
| Acer Integrated Camera                                                     | 1         | 2.44%   |
| Acer HD Webcam                                                             | 1         | 2.44%   |
| Acer EasyCamera                                                            | 1         | 2.44%   |
| Acer BisonCam, NB Pro                                                      | 1         | 2.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 3         | 50%     |
| LighTuning Technology | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 33.33%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 2         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Unknown                                           | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 35        | 76.09%  |
| 1     | 11        | 23.91%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 54.55%  |
| Multimedia controller | 2         | 18.18%  |
| Chipcard              | 2         | 18.18%  |
| Camera                | 1         | 9.09%   |

