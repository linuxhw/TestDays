Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [352c62bd8f](https://linux-hardware.org/?probe=352c62bd8f) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.11.0-43-generic    | 52        | 76.47%  |
| 5.11.0-41-generic    | 8         | 11.76%  |
| 5.8.0-50-generic     | 1         | 1.47%   |
| 5.15.6-surface       | 1         | 1.47%   |
| 5.15.12-xanmod1-tt   | 1         | 1.47%   |
| 5.15.10-xanmod1      | 1         | 1.47%   |
| 5.13.0-22-generic    | 1         | 1.47%   |
| 5.11.0-44-generic    | 1         | 1.47%   |
| 5.11.0-43-lowlatency | 1         | 1.47%   |
| 5.11.0-37-generic    | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 63        | 92.65%  |
| 5.8.0   | 1         | 1.47%   |
| 5.15.6  | 1         | 1.47%   |
| 5.15.12 | 1         | 1.47%   |
| 5.15.10 | 1         | 1.47%   |
| 5.13.0  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 63        | 92.65%  |
| 5.15    | 3         | 4.41%   |
| 5.8     | 1         | 1.47%   |
| 5.13    | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 68        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 68        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 68        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 67.65%  |
| LightDM | 22        | 32.35%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 52.94%  |
| de_DE | 10        | 14.71%  |
| en_GB | 7         | 10.29%  |
| pt_BR | 4         | 5.88%   |
| ru_RU | 2         | 2.94%   |
| pl_PL | 2         | 2.94%   |
| fr_FR | 2         | 2.94%   |
| es_ES | 2         | 2.94%   |
| it_IT | 1         | 1.47%   |
| hr_HR | 1         | 1.47%   |
| en_CA | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 48        | 70.59%  |
| BIOS | 20        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 91.18%  |
| Btrfs   | 4         | 5.88%   |
| Xfs     | 1         | 1.47%   |
| Overlay | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 73.53%  |
| GPT     | 17        | 25%     |
| MBR     | 1         | 1.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 94.12%  |
| Yes       | 4         | 5.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 91.18%  |
| Yes       | 6         | 8.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 19.12%  |
| Dell                | 10        | 14.71%  |
| ASUSTek Computer    | 8         | 11.76%  |
| Apple               | 8         | 11.76%  |
| Hewlett-Packard     | 6         | 8.82%   |
| Gigabyte Technology | 4         | 5.88%   |
| MSI                 | 3         | 4.41%   |
| Acer                | 3         | 4.41%   |
| Monster             | 2         | 2.94%   |
| Wortmann AG         | 1         | 1.47%   |
| Timi                | 1         | 1.47%   |
| Teclast             | 1         | 1.47%   |
| Star Labs           | 1         | 1.47%   |
| Notebook            | 1         | 1.47%   |
| Microsoft           | 1         | 1.47%   |
| LG Electronics      | 1         | 1.47%   |
| Intel               | 1         | 1.47%   |
| HUAWEI              | 1         | 1.47%   |
| Foxconn             | 1         | 1.47%   |
| Acidanthera         | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Wortmann AG 1220729_1470271                | 1         | 1.47%   |
| Timi TM1613                                | 1         | 1.47%   |
| Teclast F7                                 | 1         | 1.47%   |
| Star Labs LabTop                           | 1         | 1.47%   |
| Notebook P65xHP                            | 1         | 1.47%   |
| MSI PS63 Modern 8RD                        | 1         | 1.47%   |
| MSI PPPPP-CCC#MMMMMMMM                     | 1         | 1.47%   |
| MSI MS-7B86                                | 1         | 1.47%   |
| Monster MARKUT M7 V1.x                     | 1         | 1.47%   |
| Monster ABRA A5 V13.2                      | 1         | 1.47%   |
| Microsoft Surface Book 2                   | 1         | 1.47%   |
| LG A410-G.BC51P1                           | 1         | 1.47%   |
| Lenovo Yoga 300-11IBR 80M1                 | 1         | 1.47%   |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00       | 1         | 1.47%   |
| Lenovo ThinkPad W541 20EGS1VV00            | 1         | 1.47%   |
| Lenovo ThinkPad T470 W10DG 20JNS08H00      | 1         | 1.47%   |
| Lenovo ThinkPad T430 23501M2               | 1         | 1.47%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00E00      | 1         | 1.47%   |
| Lenovo ThinkPad L390 Yoga 20NT001KGE       | 1         | 1.47%   |
| Lenovo ThinkPad E495 20NE001RTX            | 1         | 1.47%   |
| Lenovo Legion Y530-15ICH 81GT              | 1         | 1.47%   |
| Lenovo IdeaPad 320-14AST 80XU              | 1         | 1.47%   |
| Lenovo IdeaPad 310-15ISK 80SM              | 1         | 1.47%   |
| Lenovo IdeaCentre AIO 3 24ARE05 F0EW00FLSC | 1         | 1.47%   |
| Lenovo Flex 2-14D 20376                    | 1         | 1.47%   |
| Intel NUC10i3FNH                           | 1         | 1.47%   |
| HUAWEI KPL-W0X                             | 1         | 1.47%   |
| HP Z420 Workstation                        | 1         | 1.47%   |
| HP ProLiant DL380p Gen8                    | 1         | 1.47%   |
| HP Pavilion Laptop 15-cs0xxx               | 1         | 1.47%   |
| HP EliteBook 850 G2                        | 1         | 1.47%   |
| HP EliteBook 8460p                         | 1         | 1.47%   |
| HP Compaq Elite 8300 SFF                   | 1         | 1.47%   |
| Gigabyte Z590 AORUS ELITE AX               | 1         | 1.47%   |
| Gigabyte Z390 UD                           | 1         | 1.47%   |
| Gigabyte H310M S2P 2.0                     | 1         | 1.47%   |
| Gigabyte B85M-DS3H-A                       | 1         | 1.47%   |
| Foxconn p6616f                             | 1         | 1.47%   |
| Dell XPS 13 9343                           | 1         | 1.47%   |
| Dell Vostro 15 3515                        | 1         | 1.47%   |
| Dell Precision M6500                       | 1         | 1.47%   |
| Dell Precision M3800                       | 1         | 1.47%   |
| Dell Precision 5530                        | 1         | 1.47%   |
| Dell Latitude 3580                         | 1         | 1.47%   |
| Dell Inspiron N5050                        | 1         | 1.47%   |
| Dell Inspiron 7405 2n1                     | 1         | 1.47%   |
| Dell Inspiron 5555                         | 1         | 1.47%   |
| Dell Inspiron 3542                         | 1         | 1.47%   |
| ASUS X79-DELUXE                            | 1         | 1.47%   |
| ASUS X555UB                                | 1         | 1.47%   |
| ASUS VivoBook_ASUSLaptop X512FA_A512FA     | 1         | 1.47%   |
| ASUS UX410UAK                              | 1         | 1.47%   |
| ASUS TUF GAMING B550M-PLUS                 | 1         | 1.47%   |
| ASUS M5A78L-M LX3                          | 1         | 1.47%   |
| ASUS E202SA                                | 1         | 1.47%   |
| ASUS All Series                            | 1         | 1.47%   |
| Apple MacPro3,1                            | 1         | 1.47%   |
| Apple MacBookPro9,2                        | 1         | 1.47%   |
| Apple MacBookPro5,1                        | 1         | 1.47%   |
| Apple MacBookAir7,2                        | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 7         | 10.29%  |
| Dell Inspiron          | 4         | 5.88%   |
| Dell Precision         | 3         | 4.41%   |
| Lenovo IdeaPad         | 2         | 2.94%   |
| HP EliteBook           | 2         | 2.94%   |
| Acer Aspire            | 2         | 2.94%   |
| Wortmann AG 1220729    | 1         | 1.47%   |
| Timi TM1613            | 1         | 1.47%   |
| Teclast F7             | 1         | 1.47%   |
| Star Labs LabTop       | 1         | 1.47%   |
| Notebook P65xHP        | 1         | 1.47%   |
| MSI PS63               | 1         | 1.47%   |
| MSI PPPPP-CCC#MMMMMMMM | 1         | 1.47%   |
| MSI MS-7B86            | 1         | 1.47%   |
| Monster MARKUT         | 1         | 1.47%   |
| Monster ABRA           | 1         | 1.47%   |
| Microsoft Surface      | 1         | 1.47%   |
| LG A410-G.BC51P1       | 1         | 1.47%   |
| Lenovo Yoga            | 1         | 1.47%   |
| Lenovo Legion          | 1         | 1.47%   |
| Lenovo IdeaCentre      | 1         | 1.47%   |
| Lenovo Flex            | 1         | 1.47%   |
| Intel NUC10i3FNH       | 1         | 1.47%   |
| HUAWEI KPL-W0X         | 1         | 1.47%   |
| HP Z420                | 1         | 1.47%   |
| HP ProLiant            | 1         | 1.47%   |
| HP Pavilion            | 1         | 1.47%   |
| HP Compaq              | 1         | 1.47%   |
| Gigabyte Z590          | 1         | 1.47%   |
| Gigabyte Z390          | 1         | 1.47%   |
| Gigabyte H310M         | 1         | 1.47%   |
| Gigabyte B85M-DS3H-A   | 1         | 1.47%   |
| Foxconn p6616f         | 1         | 1.47%   |
| Dell XPS               | 1         | 1.47%   |
| Dell Vostro            | 1         | 1.47%   |
| Dell Latitude          | 1         | 1.47%   |
| ASUS X79-DELUXE        | 1         | 1.47%   |
| ASUS X555UB            | 1         | 1.47%   |
| ASUS VivoBook          | 1         | 1.47%   |
| ASUS UX410UAK          | 1         | 1.47%   |
| ASUS TUF               | 1         | 1.47%   |
| ASUS M5A78L-M          | 1         | 1.47%   |
| ASUS E202SA            | 1         | 1.47%   |
| ASUS All               | 1         | 1.47%   |
| Apple MacPro3          | 1         | 1.47%   |
| Apple MacBookPro9      | 1         | 1.47%   |
| Apple MacBookPro5      | 1         | 1.47%   |
| Apple MacBookAir7      | 1         | 1.47%   |
| Apple MacBookAir6      | 1         | 1.47%   |
| Apple MacBook5         | 1         | 1.47%   |
| Apple MacBook4         | 1         | 1.47%   |
| Apple iMac7            | 1         | 1.47%   |
| Acidanthera iMac15     | 1         | 1.47%   |
| Acer TravelMate        | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 12        | 17.65%  |
| 2020 | 11        | 16.18%  |
| 2019 | 11        | 16.18%  |
| 2018 | 6         | 8.82%   |
| 2016 | 6         | 8.82%   |
| 2015 | 5         | 7.35%   |
| 2011 | 4         | 5.88%   |
| 2012 | 3         | 4.41%   |
| 2008 | 3         | 4.41%   |
| 2014 | 2         | 2.94%   |
| 2010 | 2         | 2.94%   |
| 2017 | 1         | 1.47%   |
| 2013 | 1         | 1.47%   |
| 2009 | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 46        | 67.65%  |
| Desktop     | 14        | 20.59%  |
| All in one  | 3         | 4.41%   |
| Convertible | 2         | 2.94%   |
| Tablet      | 1         | 1.47%   |
| Mini pc     | 1         | 1.47%   |
| Server      | 1         | 1.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 63        | 92.65%  |
| Enabled  | 5         | 7.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 98.53%  |
| Yes  | 1         | 1.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 32.35%  |
| 8.01-16.0   | 13        | 19.12%  |
| 32.01-64.0  | 10        | 14.71%  |
| 3.01-4.0    | 10        | 14.71%  |
| 16.01-24.0  | 10        | 14.71%  |
| 1.01-2.0    | 2         | 2.94%   |
| 64.01-256.0 | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 22        | 32.35%  |
| 1.01-2.0  | 16        | 23.53%  |
| 4.01-8.0  | 11        | 16.18%  |
| 3.01-4.0  | 11        | 16.18%  |
| 8.01-16.0 | 5         | 7.35%   |
| 0.51-1.0  | 3         | 4.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 54.41%  |
| 2      | 19        | 27.94%  |
| 3      | 6         | 8.82%   |
| 4      | 3         | 4.41%   |
| 5      | 2         | 2.94%   |
| 7      | 1         | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 70.59%  |
| Yes       | 20        | 29.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 77.94%  |
| No        | 15        | 22.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 86.76%  |
| No        | 9         | 13.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 82.35%  |
| No        | 12        | 17.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 8         | 11.76%  |
| USA          | 7         | 10.29%  |
| India        | 6         | 8.82%   |
| Brazil       | 5         | 7.35%   |
| UK           | 3         | 4.41%   |
| Turkey       | 3         | 4.41%   |
| Poland       | 3         | 4.41%   |
| Italy        | 3         | 4.41%   |
| Sweden       | 2         | 2.94%   |
| New Zealand  | 2         | 2.94%   |
| France       | 2         | 2.94%   |
| Canada       | 2         | 2.94%   |
| Austria      | 2         | 2.94%   |
| Australia    | 2         | 2.94%   |
| Ukraine      | 1         | 1.47%   |
| Thailand     | 1         | 1.47%   |
| Sri Lanka    | 1         | 1.47%   |
| Spain        | 1         | 1.47%   |
| South Africa | 1         | 1.47%   |
| Russia       | 1         | 1.47%   |
| Romania      | 1         | 1.47%   |
| Portugal     | 1         | 1.47%   |
| Pakistan     | 1         | 1.47%   |
| Netherlands  | 1         | 1.47%   |
| Mexico       | 1         | 1.47%   |
| Malaysia     | 1         | 1.47%   |
| Iran         | 1         | 1.47%   |
| Indonesia    | 1         | 1.47%   |
| Guyana       | 1         | 1.47%   |
| Croatia      | 1         | 1.47%   |
| Colombia     | 1         | 1.47%   |
| Belarus      | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Sydney                        | 2         | 2.94%   |
| Ankara                        | 2         | 2.94%   |
| Wroclaw                       | 1         | 1.47%   |
| Wriedel                       | 1         | 1.47%   |
| Wellington                    | 1         | 1.47%   |
| Wattala                       | 1         | 1.47%   |
| Vinnytsia                     | 1         | 1.47%   |
| Vilanova i la Geltr??         | 1         | 1.47%   |
| Vienna                        | 1         | 1.47%   |
| Uppsala                       | 1         | 1.47%   |
| Tehran                        | 1         | 1.47%   |
| Tecuci                        | 1         | 1.47%   |
| Steinbach                     | 1         | 1.47%   |
| Southampton                   | 1         | 1.47%   |
| Sornay                        | 1         | 1.47%   |
| Soliera                       | 1         | 1.47%   |
| Shetland Islands              | 1         | 1.47%   |
| S??o Paulo                    | 1         | 1.47%   |
| S??o Bernardo do Campo        | 1         | 1.47%   |
| San Antonio                   | 1         | 1.47%   |
| Samobor                       | 1         | 1.47%   |
| Saltsjoe-Boo                  | 1         | 1.47%   |
| Saalfelden am Steinernen Meer | 1         | 1.47%   |
| Rueso                         | 1         | 1.47%   |
| Rome                          | 1         | 1.47%   |
| Porto                         | 1         | 1.47%   |
| Petaling Jaya                 | 1         | 1.47%   |
| Osasco                        | 1         | 1.47%   |
| Napier City                   | 1         | 1.47%   |
| Munich                        | 1         | 1.47%   |
| Mumbai                        | 1         | 1.47%   |
| Montm?�dy                     | 1         | 1.47%   |
| Minsk                         | 1         | 1.47%   |
| Mahemdavad                    | 1         | 1.47%   |
| Khimki                        | 1         | 1.47%   |
| Johannesburg                  | 1         | 1.47%   |
| Jember                        | 1         | 1.47%   |
| Itaquaquecetuba               | 1         | 1.47%   |
| Islamabad                     | 1         | 1.47%   |
| Hyderabad                     | 1         | 1.47%   |
| Hudson                        | 1         | 1.47%   |
| Holland                       | 1         | 1.47%   |
| Hennef                        | 1         | 1.47%   |
| Hammonton                     | 1         | 1.47%   |
| Hamburg                       | 1         | 1.47%   |
| Gliwice                       | 1         | 1.47%   |
| Georgetown                    | 1         | 1.47%   |
| Gdansk                        | 1         | 1.47%   |
| Erkrath                       | 1         | 1.47%   |
| Edmonton                      | 1         | 1.47%   |
| Dhanbad                       | 1         | 1.47%   |
| Denver                        | 1         | 1.47%   |
| Cuernavaca                    | 1         | 1.47%   |
| Chalfont                      | 1         | 1.47%   |
| Cesate                        | 1         | 1.47%   |
| Cartagena                     | 1         | 1.47%   |
| Cabo Frio                     | 1         | 1.47%   |
| Burgess Hill                  | 1         | 1.47%   |
| Biere                         | 1         | 1.47%   |
| Bergenfield                   | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 20.39%  |
| WDC                 | 15        | 20     | 14.56%  |
| Seagate             | 12        | 12     | 11.65%  |
| Crucial             | 9         | 10     | 8.74%   |
| Sandisk             | 5         | 5      | 4.85%   |
| Kingston            | 5         | 5      | 4.85%   |
| SK Hynix            | 4         | 4      | 3.88%   |
| Unknown             | 3         | 5      | 2.91%   |
| Toshiba             | 3         | 4      | 2.91%   |
| Micron Technology   | 2         | 2      | 1.94%   |
| Hitachi             | 2         | 2      | 1.94%   |
| HGST                | 2         | 2      | 1.94%   |
| Unknown             | 2         | 2      | 1.94%   |
| Transcend           | 1         | 1      | 0.97%   |
| Teclast             | 1         | 1      | 0.97%   |
| Star                | 1         | 1      | 0.97%   |
| Silicon Motion      | 1         | 1      | 0.97%   |
| SABRENT             | 1         | 1      | 0.97%   |
| MAXTOR              | 1         | 1      | 0.97%   |
| LITEON              | 1         | 1      | 0.97%   |
| KIOXIA              | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| JMicron             | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| Intel               | 1         | 1      | 0.97%   |
| Fujitsu             | 1         | 1      | 0.97%   |
| Ext Hard            | 1         | 1      | 0.97%   |
| China               | 1         | 1      | 0.97%   |
| Apple               | 1         | 1      | 0.97%   |
| Apacer              | 1         | 1      | 0.97%   |
| A-DATA Technology   | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.65%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 2         | 1.77%   |
| Samsung SSD 850 EVO 250GB                 | 2         | 1.77%   |
| Samsung NVMe SSD Drive 512GB              | 2         | 1.77%   |
| Samsung NVMe SSD Drive 500GB              | 2         | 1.77%   |
| Samsung NVMe SSD Drive 256GB              | 2         | 1.77%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 1.77%   |
| Crucial CT250MX500SSD1 250GB              | 2         | 1.77%   |
| Crucial CT1000MX500SSD1 1TB               | 2         | 1.77%   |
| Unknown                                   | 2         | 1.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 1         | 0.88%   |
| WDC WD7500BPVT-22A1YT0 752GB              | 1         | 0.88%   |
| WDC WD6401AALS-00L3B2 640GB               | 1         | 0.88%   |
| WDC WD5000BPVT-22HXZT1 500GB              | 1         | 0.88%   |
| WDC WD40EZAZ-00SF3B0 4TB                  | 1         | 0.88%   |
| WDC WD3200AAJS-40RYA0 320GB               | 1         | 0.88%   |
| WDC WD3003FZEX-00Z4SA0 3TB                | 1         | 0.88%   |
| WDC WD20SPZX-22UA7T0 2TB                  | 1         | 0.88%   |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 0.88%   |
| WDC WD15EARX-00PASB0 1TB                  | 1         | 0.88%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.88%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 1         | 0.88%   |
| WDC WD10EZEX-00BN5A0 1TB                  | 1         | 0.88%   |
| WDC WD10EADS-00L5B1 1TB                   | 1         | 0.88%   |
| WDC PC SN520 SDAPNUW-512G                 | 1         | 0.88%   |
| Unknown USD00  16GB                       | 1         | 0.88%   |
| Unknown SD/MMC/M.S.PRO 32GB               | 1         | 0.88%   |
| Unknown SD/MMC 16GB                       | 1         | 0.88%   |
| Unknown M.S./M.S.Pro/HG 16GB              | 1         | 0.88%   |
| Unknown GD2S5  128GB                      | 1         | 0.88%   |
| Transcend TS512GMTS430S 512GB SSD         | 1         | 0.88%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.88%   |
| Toshiba HDWE140 4TB                       | 1         | 0.88%   |
| Toshiba HDWD120 2TB                       | 1         | 0.88%   |
| Toshiba HDWD110 1TB                       | 1         | 0.88%   |
| Teclast 128GB NS550-2242 SSD              | 1         | 0.88%   |
| Star Drive SATA SSD 960GB                 | 1         | 0.88%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 0.88%   |
| SK Hynix NVMe SSD Drive 512GB             | 1         | 0.88%   |
| SK Hynix NVMe SSD Drive 256GB             | 1         | 0.88%   |
| SK Hynix HFM128GDHTNG-8510B 128GB         | 1         | 0.88%   |
| Silicon Motion NVMe SSD Drive 120GB       | 1         | 0.88%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.88%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 0.88%   |
| Seagate ST3750528AS 752GB                 | 1         | 0.88%   |
| Seagate ST2000DX002-2DV164 2TB            | 1         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.88%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 0.88%   |
| Seagate ST10000DM0004-1ZC101 10TB         | 1         | 0.88%   |
| Seagate NVMe SSD Drive 500GB              | 1         | 0.88%   |
| Seagate Expansion Desk 8TB                | 1         | 0.88%   |
| SanDisk SD9SN8W256G1027 256GB SSD         | 1         | 0.88%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 0.88%   |
| SanDisk SD8SNAT128G1002 128GB SSD         | 1         | 0.88%   |
| Sandisk NVMe SSD Drive 500GB              | 1         | 0.88%   |
| Sandisk NVMe SSD Drive 250GB              | 1         | 0.88%   |
| Samsung SSD SM841 mSATA 512GB             | 1         | 0.88%   |
| Samsung SSD 950 PRO 512GB                 | 1         | 0.88%   |
| Samsung SSD 870 QVO 2TB                   | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 17     | 37.14%  |
| Seagate             | 11        | 11     | 31.43%  |
| Toshiba             | 3         | 4      | 8.57%   |
| Hitachi             | 2         | 2      | 5.71%   |
| HGST                | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| SABRENT             | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Ext Hard            | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 27.91%  |
| Crucial             | 9         | 10     | 20.93%  |
| Kingston            | 4         | 4      | 9.3%    |
| SanDisk             | 3         | 3      | 6.98%   |
| Micron Technology   | 2         | 2      | 4.65%   |
| WDC                 | 1         | 2      | 2.33%   |
| Transcend           | 1         | 1      | 2.33%   |
| Teclast             | 1         | 1      | 2.33%   |
| Star                | 1         | 1      | 2.33%   |
| MAXTOR              | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| China               | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |
| Unknown             | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 38        | 47     | 40%     |
| HDD     | 31        | 40     | 32.63%  |
| NVMe    | 21        | 23     | 22.11%  |
| MMC     | 3         | 3      | 3.16%   |
| Unknown | 2         | 4      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 82     | 64.29%  |
| NVMe | 21        | 23     | 25%     |
| SAS  | 6         | 9      | 7.14%   |
| MMC  | 3         | 3      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 44     | 51.47%  |
| 0.51-1.0   | 21        | 26     | 30.88%  |
| 1.01-2.0   | 6         | 10     | 8.82%   |
| 3.01-4.0   | 3         | 3      | 4.41%   |
| 4.01-10.0  | 2         | 2      | 2.94%   |
| 2.01-3.0   | 1         | 2      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 35.29%  |
| 251-500        | 21        | 30.88%  |
| 501-1000       | 8         | 11.76%  |
| 1001-2000      | 6         | 8.82%   |
| More than 3000 | 5         | 7.35%   |
| 51-100         | 3         | 4.41%   |
| 21-50          | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 21        | 30.88%  |
| 1-20           | 20        | 29.41%  |
| 51-100         | 10        | 14.71%  |
| 101-250        | 6         | 8.82%   |
| 501-1000       | 4         | 5.88%   |
| 251-500        | 3         | 4.41%   |
| 1001-2000      | 2         | 2.94%   |
| More than 3000 | 1         | 1.47%   |
| 2001-3000      | 1         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 55        | 92     | 75.34%  |
| Works    | 17        | 24     | 23.29%  |
| Malfunc  | 1         | 1      | 1.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 47        | 55.29%  |
| AMD                         | 12        | 14.12%  |
| Samsung Electronics         | 11        | 12.94%  |
| SK Hynix                    | 4         | 4.71%   |
| Sandisk                     | 3         | 3.53%   |
| Nvidia                      | 2         | 2.35%   |
| Silicon Motion              | 1         | 1.18%   |
| Seagate Technology          | 1         | 1.18%   |
| Marvell Technology Group    | 1         | 1.18%   |
| Kingston Technology Company | 1         | 1.18%   |
| Hewlett-Packard             | 1         | 1.18%   |
| ASMedia Technology          | 1         | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 9.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 7.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 4.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.3%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 3.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 3.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 3.23%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 2.15%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 2.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.15%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.08%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 1.08%   |
| SK Hynix BC511                                                                   | 1         | 1.08%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 1.08%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 1.08%   |
| Seagate Non-Volatile memory controller                                           | 1         | 1.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.08%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.08%   |
| Samsung Electronics SATA controller                                              | 1         | 1.08%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 1         | 1.08%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.08%   |
| Intel SSD 660P Series                                                            | 1         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.08%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 1.08%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 1.08%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.08%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 1         | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.08%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                       | 1         | 1.08%   |
| Intel 631xESB/632xESB IDE Controller                                             | 1         | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.08%   |
| HP Smart Array Gen8 Controllers                                                  | 1         | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.08%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 1         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 58        | 65.17%  |
| NVMe | 20        | 22.47%  |
| IDE  | 6         | 6.74%   |
| RAID | 4         | 4.49%   |
| SAS  | 1         | 1.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 77.94%  |
| AMD    | 15        | 22.06%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 4.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.94%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 2.94%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.94%   |
| Intel Xeon CPU E5462 @ 2.80GHz                | 1         | 1.47%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 1.47%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 1.47%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 1.47%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 1.47%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.47%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.47%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 1.47%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 1.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.47%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 1.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.47%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.47%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 1.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.47%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.47%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 1.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 1.47%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.47%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.47%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.47%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.47%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.47%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.47%   |
| Intel Core i3 CPU M 390 @ 2.67GHz             | 1         | 1.47%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1         | 1.47%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 1.47%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.47%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz          | 1         | 1.47%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 1         | 1.47%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 1         | 1.47%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.47%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 1         | 1.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.47%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 1.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 1.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.47%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 1.47%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.47%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.47%   |
| AMD Phenom II X4 B55 Processor                | 1         | 1.47%   |
| AMD Phenom II X4 820 Processor                | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 19        | 27.94%  |
| Intel Core i5    | 15        | 22.06%  |
| Intel Core i3    | 8         | 11.76%  |
| Intel Core 2 Duo | 4         | 5.88%   |
| AMD Ryzen 5      | 4         | 5.88%   |
| Intel Xeon       | 3         | 4.41%   |
| AMD Ryzen 7      | 3         | 4.41%   |
| Other            | 2         | 2.94%   |
| Intel Celeron    | 2         | 2.94%   |
| AMD Ryzen 7 PRO  | 2         | 2.94%   |
| AMD Phenom II X4 | 2         | 2.94%   |
| Intel Pentium    | 1         | 1.47%   |
| AMD Ryzen 3      | 1         | 1.47%   |
| AMD A8           | 1         | 1.47%   |
| AMD A6           | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 41.18%  |
| 4      | 24        | 35.29%  |
| 8      | 9         | 13.24%  |
| 6      | 6         | 8.82%   |
| 16     | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 66        | 97.06%  |
| 2      | 2         | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 50        | 73.53%  |
| 1      | 18        | 26.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 8.82%   |
| 0x306c3    | 5         | 7.35%   |
| 0x406e3    | 4         | 5.88%   |
| 0x206a7    | 4         | 5.88%   |
| 0x906ea    | 3         | 4.41%   |
| 0x806ec    | 3         | 4.41%   |
| 0x306d4    | 3         | 4.41%   |
| 0x306a9    | 3         | 4.41%   |
| 0x10676    | 3         | 4.41%   |
| 0x406c3    | 2         | 2.94%   |
| 0x40651    | 2         | 2.94%   |
| 0x206d7    | 2         | 2.94%   |
| 0x08600106 | 2         | 2.94%   |
| 0x08108102 | 2         | 2.94%   |
| 0xa0671    | 1         | 1.47%   |
| 0xa0660    | 1         | 1.47%   |
| 0x906ec    | 1         | 1.47%   |
| 0x906e9    | 1         | 1.47%   |
| 0x806eb    | 1         | 1.47%   |
| 0x806ea    | 1         | 1.47%   |
| 0x806e9    | 1         | 1.47%   |
| 0x6fa      | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x506c9    | 1         | 1.47%   |
| 0x306e4    | 1         | 1.47%   |
| 0x20655    | 1         | 1.47%   |
| 0x106e5    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x0a201009 | 1         | 1.47%   |
| 0x08701021 | 1         | 1.47%   |
| 0x08600104 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x08101007 | 1         | 1.47%   |
| 0x07030105 | 1         | 1.47%   |
| 0x07030104 | 1         | 1.47%   |
| 0x06006704 | 1         | 1.47%   |
| 0x010000db | 1         | 1.47%   |
| 0x010000c8 | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 14        | 20.59%  |
| Haswell     | 7         | 10.29%  |
| Skylake     | 6         | 8.82%   |
| SandyBridge | 6         | 8.82%   |
| Zen 2       | 5         | 7.35%   |
| Penryn      | 4         | 5.88%   |
| IvyBridge   | 4         | 5.88%   |
| Zen+        | 3         | 4.41%   |
| Broadwell   | 3         | 4.41%   |
| Westmere    | 2         | 2.94%   |
| Silvermont  | 2         | 2.94%   |
| Puma        | 2         | 2.94%   |
| K10         | 2         | 2.94%   |
| Zen 3       | 1         | 1.47%   |
| Zen         | 1         | 1.47%   |
| Nehalem     | 1         | 1.47%   |
| Icelake     | 1         | 1.47%   |
| Goldmont    | 1         | 1.47%   |
| Excavator   | 1         | 1.47%   |
| Core        | 1         | 1.47%   |
| CometLake   | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 40        | 49.38%  |
| Nvidia                     | 23        | 28.4%   |
| AMD                        | 17        | 20.99%  |
| Matrox Electronics Systems | 1         | 1.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.76%   |
| AMD Renoir                                                                               | 4         | 4.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.38%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.38%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.38%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 2.38%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 1.19%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 1.19%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 1.19%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.19%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.19%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.19%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.19%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.19%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 1.19%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1         | 1.19%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 1.19%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.19%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.19%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 1.19%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.19%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.19%   |
| Intel HD Graphics 630                                                                    | 1         | 1.19%   |
| Intel HD Graphics 620                                                                    | 1         | 1.19%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.19%   |
| Intel HD Graphics 520                                                                    | 1         | 1.19%   |
| Intel HD Graphics 500                                                                    | 1         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.19%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.19%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.19%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                                         | 1         | 1.19%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1         | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.19%   |
| AMD Broadway XT [Mobility Radeon HD 5870]                                                | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 39.71%  |
| 1 x AMD        | 15        | 22.06%  |
| 1 x Nvidia     | 11        | 16.18%  |
| Intel + Nvidia | 11        | 16.18%  |
| 2 x Nvidia     | 1         | 1.47%   |
| 2 x AMD        | 1         | 1.47%   |
| 1 x Matrox     | 1         | 1.47%   |
| Intel + AMD    | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 80.88%  |
| Proprietary | 13        | 19.12%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 50%     |
| 0.51-1.0   | 9         | 13.24%  |
| 3.01-4.0   | 7         | 10.29%  |
| 1.01-2.0   | 7         | 10.29%  |
| 0.01-0.5   | 6         | 8.82%   |
| 7.01-8.0   | 2         | 2.94%   |
| 5.01-6.0   | 2         | 2.94%   |
| 2.01-3.0   | 1         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 12.66%  |
| Chimei Innolux      | 10        | 12.66%  |
| AU Optronics        | 9         | 11.39%  |
| Apple               | 7         | 8.86%   |
| Samsung Electronics | 6         | 7.59%   |
| Sharp               | 5         | 6.33%   |
| Hewlett-Packard     | 4         | 5.06%   |
| Goldstar            | 4         | 5.06%   |
| BOE                 | 4         | 5.06%   |
| Acer                | 3         | 3.8%    |
| Lenovo              | 2         | 2.53%   |
| Dell                | 2         | 2.53%   |
| BenQ                | 2         | 2.53%   |
| Philips             | 1         | 1.27%   |
| PANDA               | 1         | 1.27%   |
| Panasonic           | 1         | 1.27%   |
| InfoVision          | 1         | 1.27%   |
| Iiyama              | 1         | 1.27%   |
| HPN                 | 1         | 1.27%   |
| Eizo                | 1         | 1.27%   |
| CHD                 | 1         | 1.27%   |
| AUS                 | 1         | 1.27%   |
| AOC                 | 1         | 1.27%   |
| Unknown             | 1         | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 2.41%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 2         | 2.41%   |
| Sharp PN-K321 SHP21DD 3840x2160                                      | 1         | 1.2%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 1         | 1.2%    |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch              | 1         | 1.2%    |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch              | 1         | 1.2%    |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch              | 1         | 1.2%    |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1         | 1.2%    |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1         | 1.2%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch | 1         | 1.2%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1         | 1.2%    |
| Philips LCD Monitor PHL 276E8V 7680x2160                             | 1         | 1.2%    |
| Philips LCD Monitor PHL 276E8V                                       | 1         | 1.2%    |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch              | 1         | 1.2%    |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch         | 1         | 1.2%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 1.2%    |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                 | 1         | 1.2%    |
| Lenovo LEN-A350-B-A LENF908 1920x1080 527x296mm 23.8-inch            | 1         | 1.2%    |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch             | 1         | 1.2%    |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 1.2%    |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch               | 1         | 1.2%    |
| HPN LCD Monitor HP 27fw 1920x1080                                    | 1         | 1.2%    |
| Hewlett-Packard V196bz HWP323E 1366x768 410x230mm 18.5-inch          | 1         | 1.2%    |
| Hewlett-Packard LCD Monitor w17e 1440x900                            | 1         | 1.2%    |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch           | 1         | 1.2%    |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch            | 1         | 1.2%    |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                   | 1         | 1.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1         | 1.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1         | 1.2%    |
| Goldstar E2442 GSM58C6 1920x1080 531x299mm 24.0-inch                 | 1         | 1.2%    |
| Eizo EV2455 ENC2533 1920x1200 519x324mm 24.1-inch                    | 1         | 1.2%    |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                    | 1         | 1.2%    |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                    | 1         | 1.2%    |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch     | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 1         | 1.2%    |
| CHD GDM-225JN CHD0220 1920x1080 490x270mm 22.0-inch                  | 1         | 1.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 1         | 1.2%    |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                | 1         | 1.2%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 1         | 1.2%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 1.2%    |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                   | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 39.24%  |
| 1366x768 (WXGA)    | 17        | 21.52%  |
| 2560x1440 (QHD)    | 8         | 10.13%  |
| 3840x2160 (4K)     | 6         | 7.59%   |
| 1600x900 (HD+)     | 4         | 5.06%   |
| 1440x900 (WXGA+)   | 3         | 3.8%    |
| 1280x800 (WXGA)    | 3         | 3.8%    |
| 7680x2160          | 1         | 1.27%   |
| 3200x1800 (QHD+)   | 1         | 1.27%   |
| 2560x1080          | 1         | 1.27%   |
| 1920x1200 (WUXGA)  | 1         | 1.27%   |
| 1680x1050 (WSXGA+) | 1         | 1.27%   |
| 1360x768           | 1         | 1.27%   |
| Unknown            | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 26.58%  |
| 13      | 14        | 17.72%  |
| 14      | 7         | 8.86%   |
| 24      | 6         | 7.59%   |
| Unknown | 6         | 7.59%   |
| 27      | 4         | 5.06%   |
| 31      | 3         | 3.8%    |
| 23      | 3         | 3.8%    |
| 20      | 3         | 3.8%    |
| 17      | 3         | 3.8%    |
| 11      | 3         | 3.8%    |
| 34      | 1         | 1.27%   |
| 26      | 1         | 1.27%   |
| 25      | 1         | 1.27%   |
| 22      | 1         | 1.27%   |
| 21      | 1         | 1.27%   |
| 18      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 42.86%  |
| 501-600     | 12        | 15.58%  |
| 201-300     | 12        | 15.58%  |
| Unknown     | 6         | 7.79%   |
| 601-700     | 5         | 6.49%   |
| 401-500     | 5         | 6.49%   |
| 351-400     | 3         | 3.9%    |
| 701-800     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 54        | 78.26%  |
| 16/10   | 8         | 11.59%  |
| Unknown | 5         | 7.25%   |
| 3/2     | 1         | 1.45%   |
| 21/9    | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 25.32%  |
| 81-90          | 15        | 18.99%  |
| 201-250        | 8         | 10.13%  |
| 71-80          | 6         | 7.59%   |
| Unknown        | 6         | 7.59%   |
| 301-350        | 5         | 6.33%   |
| 351-500        | 4         | 5.06%   |
| 251-300        | 4         | 5.06%   |
| 51-60          | 3         | 3.8%    |
| 151-200        | 3         | 3.8%    |
| 121-130        | 3         | 3.8%    |
| 141-150        | 1         | 1.27%   |
| 111-120        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 31.17%  |
| 101-120       | 21        | 27.27%  |
| 51-100        | 17        | 22.08%  |
| Unknown       | 6         | 7.79%   |
| 161-240       | 5         | 6.49%   |
| More than 240 | 4         | 5.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 80.88%  |
| 2     | 10        | 14.71%  |
| 3     | 3         | 4.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 33.33%  |
| Intel                    | 35        | 33.33%  |
| Qualcomm Atheros         | 11        | 10.48%  |
| Broadcom                 | 11        | 10.48%  |
| Marvell Technology Group | 3         | 2.86%   |
| TP-Link                  | 2         | 1.9%    |
| Ralink                   | 2         | 1.9%    |
| Nvidia                   | 2         | 1.9%    |
| Broadcom Limited         | 2         | 1.9%    |
| Xiaomi                   | 1         | 0.95%   |
| Ralink Technology        | 1         | 0.95%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 20.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.39%   |
| Intel Wireless 8260                                               | 4         | 3.39%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.54%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 2.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.69%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.69%   |
| Intel Wireless-AC 9260                                            | 2         | 1.69%   |
| Intel Wireless 7265                                               | 2         | 1.69%   |
| Intel Wireless 7260                                               | 2         | 1.69%   |
| Intel Wireless 3165                                               | 2         | 1.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 1.69%   |
| Broadcom BCM43227 802.11b/g/n                                     | 2         | 1.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.85%   |
| TP-Link 802.11n NIC                                               | 1         | 0.85%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.85%   |
| Realtek 802.11ac NIC                                              | 1         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.85%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 0.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1         | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 31        | 50.82%  |
| Broadcom                 | 10        | 16.39%  |
| Qualcomm Atheros         | 7         | 11.48%  |
| Realtek Semiconductor    | 5         | 8.2%    |
| TP-Link                  | 2         | 3.28%   |
| Ralink                   | 2         | 3.28%   |
| Broadcom Limited         | 2         | 3.28%   |
| Ralink Technology        | 1         | 1.64%   |
| Marvell Technology Group | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 6.56%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 4.92%   |
| Intel Wireless 8265 / 8275                                     | 3         | 4.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 4.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 4.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.28%   |
| Intel Wireless-AC 9260                                         | 2         | 3.28%   |
| Intel Wireless 7265                                            | 2         | 3.28%   |
| Intel Wireless 7260                                            | 2         | 3.28%   |
| Intel Wireless 3165                                            | 2         | 3.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 3.28%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 3.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 3.28%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 3.28%   |
| TP-Link 802.11n NIC                                            | 1         | 1.64%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.64%   |
| Realtek 802.11ac NIC                                           | 1         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.64%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 58.93%  |
| Intel                    | 11        | 19.64%  |
| Qualcomm Atheros         | 4         | 7.14%   |
| Broadcom                 | 3         | 5.36%   |
| Nvidia                   | 2         | 3.57%   |
| Marvell Technology Group | 2         | 3.57%   |
| Xiaomi                   | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 42.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 3.51%   |
| Nvidia MCP79 Ethernet                                             | 2         | 3.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.75%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 1.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.75%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.75%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 52.68%  |
| Ethernet | 53        | 47.32%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 54.63%  |
| Ethernet | 49        | 45.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 39        | 57.35%  |
| 1     | 26        | 38.24%  |
| 3     | 2         | 2.94%   |
| 4     | 1         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 58.82%  |
| Yes  | 28        | 41.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 52.63%  |
| Apple                           | 9         | 15.79%  |
| Qualcomm Atheros Communications | 5         | 8.77%   |
| Realtek Semiconductor           | 3         | 5.26%   |
| Cambridge Silicon Radio         | 3         | 5.26%   |
| Marvell Semiconductor           | 1         | 1.75%   |
| Lite-On Technology              | 1         | 1.75%   |
| IMC Networks                    | 1         | 1.75%   |
| Hewlett-Packard                 | 1         | 1.75%   |
| Foxconn / Hon Hai               | 1         | 1.75%   |
| Broadcom                        | 1         | 1.75%   |
| ASUSTek Computer                | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 28.07%  |
| Intel Bluetooth Device                              | 9         | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 8.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.26%   |
| Apple Bluetooth USB Host Controller                 | 3         | 5.26%   |
| Apple Bluetooth HCI                                 | 3         | 5.26%   |
| Realtek Bluetooth Radio                             | 2         | 3.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.51%   |
| Apple Bluetooth Host Controller                     | 2         | 3.51%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.75%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.75%   |
| IMC Networks Bluetooth Device                       | 1         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.75%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.75%   |
| ASUS BCM20702A0                                     | 1         | 1.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 49        | 55.06%  |
| AMD                     | 18        | 20.22%  |
| Nvidia                  | 16        | 17.98%  |
| Texas Instruments       | 1         | 1.12%   |
| Realtek Semiconductor   | 1         | 1.12%   |
| Focusrite-Novation      | 1         | 1.12%   |
| Creative Labs           | 1         | 1.12%   |
| C-Media Electronics     | 1         | 1.12%   |
| BEHRINGER International | 1         | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 7.27%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 7.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.73%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 2.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.82%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.82%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.82%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.91%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.91%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.91%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.91%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.91%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1         | 0.91%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.91%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 0.91%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                                        | 1         | 0.91%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 0.91%   |
| BEHRINGER International UMC202HD 192k                                                             | 1         | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.91%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.91%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.91%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.91%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 45%     |
| SK Hynix            | 5         | 25%     |
| Micron Technology   | 3         | 15%     |
| Hewlett-Packard     | 1         | 5%      |
| G.Skill             | 1         | 5%      |
| Crucial             | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s    | 2         | 9.09%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s  | 2         | 9.09%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s      | 1         | 4.55%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s | 1         | 4.55%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1         | 4.55%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 1         | 4.55%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s  | 1         | 4.55%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s  | 1         | 4.55%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s             | 1         | 4.55%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s  | 1         | 4.55%   |
| HP RAM 647650-071 8192MB DIMM DDR3 1333MT/s               | 1         | 4.55%   |
| G.Skill RAM F4-2666C18-16GRS 16384MB SODIMM DDR4 2667MT/s | 1         | 4.55%   |
| Crucial RAM CB8GS2400.C8D 8192MB SODIMM DDR4 2400MT/s     | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 13        | 68.42%  |
| DDR3 | 6         | 31.58%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 89.47%  |
| DIMM   | 1         | 5.26%   |
| Chip   | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 47.62%  |
| 4096  | 5         | 23.81%  |
| 16384 | 4         | 19.05%  |
| 2048  | 2         | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 7         | 35%     |
| 1600  | 5         | 25%     |
| 3200  | 3         | 15%     |
| 2133  | 2         | 10%     |
| 3266  | 1         | 5%      |
| 2400  | 1         | 5%      |
| 1333  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 18%     |
| Realtek Semiconductor                  | 8         | 16%     |
| Acer                                   | 6         | 12%     |
| Apple                                  | 5         | 10%     |
| Microdia                               | 4         | 8%      |
| IMC Networks                           | 4         | 8%      |
| Alcor Micro                            | 3         | 6%      |
| Quanta                                 | 2         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4%      |
| Y Media                                | 1         | 2%      |
| Syntek                                 | 1         | 2%      |
| Suyin                                  | 1         | 2%      |
| Ricoh                                  | 1         | 2%      |
| Microsoft                              | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Generalplus Technology                 | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 6%      |
| Microdia Integrated_Webcam_HD                                              | 3         | 6%      |
| IMC Networks Integrated Camera                                             | 2         | 4%      |
| Chicony Integrated Camera                                                  | 2         | 4%      |
| Apple Built-in iSight                                                      | 2         | 4%      |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 4%      |
| Acer Lenovo EasyCamera                                                     | 2         | 4%      |
| Y Media USB Camera                                                         | 1         | 2%      |
| Syntek Integrated Camera                                                   | 1         | 2%      |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2%      |
| Ricoh Dell Laptop Integrated Webcam                                        | 1         | 2%      |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 2%      |
| Realtek USB2.0 HD UVC WebCam                                               | 1         | 2%      |
| Realtek USB Camera                                                         | 1         | 2%      |
| Realtek LG Webcam                                                          | 1         | 2%      |
| Realtek Integrated Webcam                                                  | 1         | 2%      |
| Quanta VGA WebCam                                                          | 1         | 2%      |
| Quanta hm1091_techfront                                                    | 1         | 2%      |
| Microsoft LifeCam VX-800                                                   | 1         | 2%      |
| Microdia USB 2.0 Camera                                                    | 1         | 2%      |
| Logitech BRIO 4K Stream Edition                                            | 1         | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2%      |
| IMC Networks EasyCamera                                                    | 1         | 2%      |
| Generalplus GENERAL WEBCAM                                                 | 1         | 2%      |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 2%      |
| Chicony USB2.0 Camera                                                      | 1         | 2%      |
| Chicony USB 2.0 Camera                                                     | 1         | 2%      |
| Chicony thinkpad t430s camera                                              | 1         | 2%      |
| Chicony Integrated HP HD Webcam                                            | 1         | 2%      |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2%      |
| Chicony HD Webcam                                                          | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 1         | 2%      |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2%      |
| Apple FaceTime HD Camera                                                   | 1         | 2%      |
| Apple Built-in iSight [Micron]                                             | 1         | 2%      |
| Alcor Micro USB 2.0 PC Camera                                              | 1         | 2%      |
| Acer Integrated Camera                                                     | 1         | 2%      |
| Acer HD Webcam                                                             | 1         | 2%      |
| Acer EasyCamera                                                            | 1         | 2%      |
| Acer BisonCam, NB Pro                                                      | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 4         | 57.14%  |
| LighTuning Technology | 2         | 28.57%  |
| Validity Sensors      | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 28.57%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 2         | 28.57%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 14.29%  |
| Unknown                                           | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 55        | 80.88%  |
| 1     | 13        | 19.12%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 53.85%  |
| Multimedia controller | 2         | 15.38%  |
| Chipcard              | 2         | 15.38%  |
| Net/wireless          | 1         | 7.69%   |
| Camera                | 1         | 7.69%   |

