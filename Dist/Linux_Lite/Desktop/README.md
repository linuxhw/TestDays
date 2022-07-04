Linux Lite - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Lite.

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

Total: 56

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | 103D SDK0J40697 WIN 3305... | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Acer     | Aspire TC-895 V:1.0         | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Lenovo   | Remore CRB Win8 STD MM D... | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo   | Remore CRB Win8 STD MM D... | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP       | 3047h                       | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Lenovo   | ThinkCentre M91p 4518E2M    | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo   | ThinkCentre M91p 4518E2M    | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek  | TUF B450-PLUS GAMING        | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Dell     | 018D1Y A00                  | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| HP       | 2820h                       | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Dell     | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte | B450M DS3H-CF               | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte | B450M DS3H-CF               | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| Dell     | 0HY9JP A02                  | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn  | 2A8C                        | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| ABIT     | IP35-E                      | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Acer     | Aspire TC-895 V:1.0         | [fb0408c4ea](https://linux-hardware.org/?probe=fb0408c4ea) | Feb 10, 2022 |
| Pegatron | 2ACB                        | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| Acer     | Aspire TC-895 V:1.0         | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA     | X58 SLI FTW3 Tylersburg     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASRock   | H61M-VG3                    | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Gigabyte | GA-E350N                    | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Biostar  | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar  | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek  | M5A78L LE                   | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek  | M5A78L LE                   | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Intel    | DG31PR AAD97573-300         | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel    | DG31PR AAD97573-300         | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP       | 0A98h                       | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS      | Livermore                   | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| MSI      | Boston                      | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| MSI      | B75A-G43                    | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte | X570 AORUS MASTER           | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| Minix    | NEO Z83-4 V1.1              | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte | X570 AORUS MASTER           | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte | X570 AORUS MASTER           | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix    | NEO Z83-4 V1.1              | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| HP       | 0ACCh                       | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP       | 0ACCh                       | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo   | ThinkCentre M91p 4524RS6    | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo   | ThinkCentre M91p 4524RS6    | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP       | 3032h                       | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel    | H61M-S1                     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel    | H61M-S1                     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo   | ThinkCentre A55 9265BL7     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP       | 2AA6 PVT                    | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| MSI      | Z77A-G43                    | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| ASRock   | N68C-S UCC                  | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock   | N68C-S UCC                  | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway   | I61MG4                      | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway   | I61MG4                      | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Acer     | EQ35M                       | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer     | EQ35M                       | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn  | 45CMX/45GMX/45CMX-K         | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Linux Lite 5.8 | 8        | 22.86%  |
| Linux Lite 5.0 | 7        | 20%     |
| Linux Lite 5.6 | 6        | 17.14%  |
| Linux Lite 5.2 | 6        | 17.14%  |
| Linux Lite 5.4 | 5        | 14.29%  |
| Linux Lite 3.8 | 2        | 5.71%   |
| Linux Lite 4.6 | 1        | 2.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Lite | 35       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.4.0-91-generic     | 3        | 8.33%   |
| 5.4.0-96-generic     | 2        | 5.56%   |
| 5.4.0-80-generic     | 2        | 5.56%   |
| 5.4.0-54-generic     | 2        | 5.56%   |
| 5.4.0-48-generic     | 2        | 5.56%   |
| 5.4.0-42-generic     | 2        | 5.56%   |
| 5.4.0-113-generic    | 2        | 5.56%   |
| 5.4.0-104-generic    | 2        | 5.56%   |
| 4.4.0-112-generic    | 2        | 5.56%   |
| 5.9.0                | 1        | 2.78%   |
| 5.4.0-99-generic     | 1        | 2.78%   |
| 5.4.0-88-generic     | 1        | 2.78%   |
| 5.4.0-72-generic     | 1        | 2.78%   |
| 5.4.0-70-generic     | 1        | 2.78%   |
| 5.4.0-58-generic     | 1        | 2.78%   |
| 5.4.0-52-generic     | 1        | 2.78%   |
| 5.4.0-45-generic     | 1        | 2.78%   |
| 5.4.0-37-generic     | 1        | 2.78%   |
| 5.4.0-33-generic     | 1        | 2.78%   |
| 5.4.0-110-generic    | 1        | 2.78%   |
| 5.4.0-109-generic    | 1        | 2.78%   |
| 5.4.0-107-generic    | 1        | 2.78%   |
| 5.4.0-105-generic    | 1        | 2.78%   |
| 5.15.0               | 1        | 2.78%   |
| 5.13.0-44-lowlatency | 1        | 2.78%   |
| 4.15.0-147-generic   | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 30       | 83.33%  |
| 4.4.0   | 2        | 5.56%   |
| 5.9.0   | 1        | 2.78%   |
| 5.15.0  | 1        | 2.78%   |
| 5.13.0  | 1        | 2.78%   |
| 4.15.0  | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 30       | 83.33%  |
| 4.4     | 2        | 5.56%   |
| 5.9     | 1        | 2.78%   |
| 5.15    | 1        | 2.78%   |
| 5.13    | 1        | 2.78%   |
| 4.15    | 1        | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 94.29%  |
| i686   | 2        | 5.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 25       | 71.43%  |
| GNOME | 10       | 28.57%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 35       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 17       | 48.57%  |
| TDM     | 10       | 28.57%  |
| Unknown | 8        | 22.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 13       | 37.14%  |
| pt_BR | 4        | 11.43%  |
| es_MX | 3        | 8.57%   |
| fr_FR | 2        | 5.71%   |
| de_DE | 2        | 5.71%   |
| ru_UA | 1        | 2.86%   |
| pl_PL | 1        | 2.86%   |
| nl_NL | 1        | 2.86%   |
| fr_CA | 1        | 2.86%   |
| es_ES | 1        | 2.86%   |
| es_CL | 1        | 2.86%   |
| en_NZ | 1        | 2.86%   |
| en_IE | 1        | 2.86%   |
| en_GB | 1        | 2.86%   |
| en_CA | 1        | 2.86%   |
| da_DK | 1        | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 82.86%  |
| EFI  | 6        | 17.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 31       | 88.57%  |
| Overlay | 3        | 8.57%   |
| Ext3    | 1        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 16       | 45.71%  |
| Unknown | 12       | 34.29%  |
| GPT     | 7        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 77.14%  |
| Yes       | 8        | 22.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 62.86%  |
| Yes       | 13       | 37.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 17.14%  |
| Lenovo              | 5        | 14.29%  |
| MSI                 | 3        | 8.57%   |
| Gigabyte Technology | 3        | 8.57%   |
| Intel               | 2        | 5.71%   |
| Foxconn             | 2        | 5.71%   |
| Dell                | 2        | 5.71%   |
| ASUSTek Computer    | 2        | 5.71%   |
| ASRock              | 2        | 5.71%   |
| Acer                | 2        | 5.71%   |
| Pegatron            | 1        | 2.86%   |
| Minix               | 1        | 2.86%   |
| Jetway              | 1        | 2.86%   |
| EVGA                | 1        | 2.86%   |
| Biostar             | 1        | 2.86%   |
| ABIT                | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7758                            | 2        | 5.71%   |
| Pegatron 520-1135la                    | 1        | 2.86%   |
| MSI FZ079AA-ABF a6625fr                | 1        | 2.86%   |
| Minix Z83-4                            | 1        | 2.86%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1        | 2.86%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1        | 2.86%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1        | 2.86%   |
| Lenovo ThinkCentre A55 9265BL7         | 1        | 2.86%   |
| Lenovo H505S 10107                     | 1        | 2.86%   |
| Jetway I61MG4                          | 1        | 2.86%   |
| Intel H61M-S1                          | 1        | 2.86%   |
| Intel DG31PR AAD97573-300              | 1        | 2.86%   |
| HP xw8600 Workstation                  | 1        | 2.86%   |
| HP t5000 series                        | 1        | 2.86%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.86%   |
| HP Compaq dc5800 Small Form Factor     | 1        | 2.86%   |
| HP Compaq 6005 Pro SFF PC              | 1        | 2.86%   |
| HP 200-5320br                          | 1        | 2.86%   |
| Gigabyte X570 AORUS MASTER             | 1        | 2.86%   |
| Gigabyte GA-E350N                      | 1        | 2.86%   |
| Gigabyte B450M DS3H                    | 1        | 2.86%   |
| Foxconn 500B Microtower                | 1        | 2.86%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1        | 2.86%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1        | 2.86%   |
| Dell OptiPlex 790                      | 1        | 2.86%   |
| Dell Inspiron 560                      | 1        | 2.86%   |
| Biostar G41D3C                         | 1        | 2.86%   |
| ASUS TUF B450-PLUS GAMING              | 1        | 2.86%   |
| ASUS M5A78L LE                         | 1        | 2.86%   |
| ASRock N68C-S UCC                      | 1        | 2.86%   |
| ASRock H61M-VG3                        | 1        | 2.86%   |
| Acer Veriton T/M/S661_461              | 1        | 2.86%   |
| Acer Aspire TC-895                     | 1        | 2.86%   |
| ABIT IP35-E                            | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo ThinkCentre  | 3        | 8.57%   |
| HP Compaq           | 3        | 8.57%   |
| MSI MS-7758         | 2        | 5.71%   |
| Pegatron 520-1135la | 1        | 2.86%   |
| MSI FZ079AA-ABF     | 1        | 2.86%   |
| Minix Z83-4         | 1        | 2.86%   |
| Lenovo ThinkStation | 1        | 2.86%   |
| Lenovo H505S        | 1        | 2.86%   |
| Jetway I61MG4       | 1        | 2.86%   |
| Intel H61M-S1       | 1        | 2.86%   |
| Intel DG31PR        | 1        | 2.86%   |
| HP xw8600           | 1        | 2.86%   |
| HP t5000            | 1        | 2.86%   |
| HP 200-5320br       | 1        | 2.86%   |
| Gigabyte X570       | 1        | 2.86%   |
| Gigabyte GA-E350N   | 1        | 2.86%   |
| Gigabyte B450M      | 1        | 2.86%   |
| Foxconn 500B        | 1        | 2.86%   |
| Foxconn 45CMX       | 1        | 2.86%   |
| EVGA X58            | 1        | 2.86%   |
| Dell OptiPlex       | 1        | 2.86%   |
| Dell Inspiron       | 1        | 2.86%   |
| Biostar G41D3C      | 1        | 2.86%   |
| ASUS TUF            | 1        | 2.86%   |
| ASUS M5A78L         | 1        | 2.86%   |
| ASRock N68C-S       | 1        | 2.86%   |
| ASRock H61M-VG3     | 1        | 2.86%   |
| Acer Veriton        | 1        | 2.86%   |
| Acer Aspire         | 1        | 2.86%   |
| ABIT IP35-E         | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 8        | 22.86%  |
| 2012 | 6        | 17.14%  |
| 2008 | 6        | 17.14%  |
| 2010 | 4        | 11.43%  |
| 2007 | 3        | 8.57%   |
| 2018 | 2        | 5.71%   |
| 2009 | 2        | 5.71%   |
| 2021 | 1        | 2.86%   |
| 2020 | 1        | 2.86%   |
| 2019 | 1        | 2.86%   |
| 2016 | 1        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 35       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 35       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 9        | 25.71%  |
| 1.01-2.0   | 7        | 20%     |
| 4.01-8.0   | 6        | 17.14%  |
| 16.01-24.0 | 5        | 14.29%  |
| 8.01-16.0  | 4        | 11.43%  |
| 32.01-64.0 | 3        | 8.57%   |
| 2.01-3.0   | 1        | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 18       | 51.43%  |
| 2.01-3.0 | 6        | 17.14%  |
| 4.01-8.0 | 4        | 11.43%  |
| 3.01-4.0 | 4        | 11.43%  |
| 0.51-1.0 | 3        | 8.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 48.57%  |
| 2      | 10       | 28.57%  |
| 3      | 4        | 11.43%  |
| 0      | 2        | 5.71%   |
| 5      | 1        | 2.86%   |
| 4      | 1        | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 51.43%  |
| No        | 17       | 48.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 97.14%  |
| No        | 1        | 2.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 51.43%  |
| Yes       | 17       | 48.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 80%     |
| Yes       | 7        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 6        | 17.14%  |
| Brazil      | 6        | 17.14%  |
| Peru        | 3        | 8.57%   |
| Mexico      | 3        | 8.57%   |
| Canada      | 3        | 8.57%   |
| Poland      | 2        | 5.71%   |
| Germany     | 2        | 5.71%   |
| France      | 2        | 5.71%   |
| Ukraine     | 1        | 2.86%   |
| UK          | 1        | 2.86%   |
| New Zealand | 1        | 2.86%   |
| Netherlands | 1        | 2.86%   |
| Malaysia    | 1        | 2.86%   |
| Ireland     | 1        | 2.86%   |
| Greenland   | 1        | 2.86%   |
| Chile       | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Lima                 | 2        | 5.71%   |
| Würzburg            | 1        | 2.86%   |
| Wellington           | 1        | 2.86%   |
| Waterbury            | 1        | 2.86%   |
| Warsaw               | 1        | 2.86%   |
| Vancouver            | 1        | 2.86%   |
| Trujillo             | 1        | 2.86%   |
| Thetford-Mines       | 1        | 2.86%   |
| Sao Paulo            | 1        | 2.86%   |
| Rio de Janeiro       | 1        | 2.86%   |
| Purmerend            | 1        | 2.86%   |
| Porto Velho          | 1        | 2.86%   |
| Porto Alegre         | 1        | 2.86%   |
| Pabianice            | 1        | 2.86%   |
| Ottawa               | 1        | 2.86%   |
| Osasco               | 1        | 2.86%   |
| Oldenburg            | 1        | 2.86%   |
| Nashville            | 1        | 2.86%   |
| Narbonne             | 1        | 2.86%   |
| Mexico City          | 1        | 2.86%   |
| Long Seridan         | 1        | 2.86%   |
| Kyiv                 | 1        | 2.86%   |
| Ilulissat            | 1        | 2.86%   |
| Fortin de las Flores | 1        | 2.86%   |
| Dublin               | 1        | 2.86%   |
| Dover                | 1        | 2.86%   |
| Cuauhtemoc           | 1        | 2.86%   |
| Conchali             | 1        | 2.86%   |
| Columbus             | 1        | 2.86%   |
| Chapel Hill          | 1        | 2.86%   |
| Carrollton           | 1        | 2.86%   |
| Canto do Buriti      | 1        | 2.86%   |
| Birmingham           | 1        | 2.86%   |
| Ambares-et-Lagrave   | 1        | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 25.49%  |
| Seagate             | 13       | 15     | 25.49%  |
| Samsung Electronics | 5        | 5      | 9.8%    |
| Toshiba             | 3        | 3      | 5.88%   |
| Kingston            | 2        | 4      | 3.92%   |
| Hitachi             | 2        | 2      | 3.92%   |
| Crucial             | 2        | 2      | 3.92%   |
| Unknown             | 1        | 1      | 1.96%   |
| SanDisk             | 1        | 1      | 1.96%   |
| PNY                 | 1        | 1      | 1.96%   |
| Phison              | 1        | 1      | 1.96%   |
| OCZ                 | 1        | 1      | 1.96%   |
| Maxtor              | 1        | 1      | 1.96%   |
| Mass                | 1        | 1      | 1.96%   |
| HPE                 | 1        | 1      | 1.96%   |
| Hewlett-Packard     | 1        | 1      | 1.96%   |
| Goodram             | 1        | 1      | 1.96%   |
| Gigabyte Technology | 1        | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 3        | 5.36%   |
| WDC WD5000AAKX-001CA0 500GB          | 2        | 3.57%   |
| WDC WDS250G2B0A 250GB SSD            | 1        | 1.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1        | 1.79%   |
| WDC WD800JD-60LSA0 80GB              | 1        | 1.79%   |
| WDC WD5000AAKX-003CA0 500GB          | 1        | 1.79%   |
| WDC WD5000AAKS-60WWPA0 500GB         | 1        | 1.79%   |
| WDC WD5000AACS-00G8B1 500GB          | 1        | 1.79%   |
| WDC WD20PURX-64PFUY0 2TB             | 1        | 1.79%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1        | 1.79%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1        | 1.79%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1        | 1.79%   |
| WDC WD10EADS-00L5B1 1TB              | 1        | 1.79%   |
| WDC WD1003FBYX-01Y7B1 1TB            | 1        | 1.79%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1        | 1.79%   |
| Unknown MMC Card  32GB               | 1        | 1.79%   |
| Toshiba MK1059GSM 1TB                | 1        | 1.79%   |
| Toshiba HDWD110 1TB                  | 1        | 1.79%   |
| Toshiba DT01ACA100 1TB               | 1        | 1.79%   |
| Seagate ST980811AS 80GB              | 1        | 1.79%   |
| Seagate ST9500325AS 500GB            | 1        | 1.79%   |
| Seagate ST500LM030-1RK17D 500GB      | 1        | 1.79%   |
| Seagate ST500DM002-1BC142 500GB      | 1        | 1.79%   |
| Seagate ST3750640NS 752GB            | 1        | 1.79%   |
| Seagate ST3320620A 320GB             | 1        | 1.79%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1        | 1.79%   |
| Seagate ST3120026A 120GB             | 1        | 1.79%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1.79%   |
| Seagate ST1000LM010-9YH146 1TB       | 1        | 1.79%   |
| Seagate ST1000DM003-1CH162 1TB       | 1        | 1.79%   |
| SanDisk SDSSDA240G 240GB             | 1        | 1.79%   |
| Samsung SSD PM851 2.5 7mm 256GB      | 1        | 1.79%   |
| Samsung SSD 860 EVO 500GB            | 1        | 1.79%   |
| Samsung SSD 830 Series 128GB         | 1        | 1.79%   |
| Samsung MZVKW512HMJP-000L7 512GB     | 1        | 1.79%   |
| Samsung HM500JI 500GB                | 1        | 1.79%   |
| PNY CS900 120GB SSD                  | 1        | 1.79%   |
| Phison NVMe SSD Drive 2TB            | 1        | 1.79%   |
| OCZ AGILITY3 64GB SSD                | 1        | 1.79%   |
| Maxtor 6L250S0 250GB                 | 1        | 1.79%   |
| Mass Mass Storage 8MB                | 1        | 1.79%   |
| Kingston SV300S37A60G 64GB SSD       | 1        | 1.79%   |
| Kingston SV300S37A120G 120GB SSD     | 1        | 1.79%   |
| Kingston SUV400S37480G 480GB SSD     | 1        | 1.79%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 1.79%   |
| HPE MB0500GCEHE 500GB                | 1        | 1.79%   |
| Hitachi HDS722020ALA330 2TB          | 1        | 1.79%   |
| Hitachi HDS721616PLA380 160GB        | 1        | 1.79%   |
| HP SSD S700 500GB                    | 1        | 1.79%   |
| Goodram IR-SSDPR-S25A-120 120GB      | 1        | 1.79%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 1        | 1.79%   |
| Crucial CT256MX100SSD1 256GB         | 1        | 1.79%   |
| Crucial CT1000MX500SSD1 1TB          | 1        | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 41.94%  |
| WDC                 | 11       | 12     | 35.48%  |
| Toshiba             | 3        | 3      | 9.68%   |
| Hitachi             | 2        | 2      | 6.45%   |
| Samsung Electronics | 1        | 1      | 3.23%   |
| Maxtor              | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 20%     |
| WDC                 | 2        | 3      | 13.33%  |
| Kingston            | 2        | 4      | 13.33%  |
| Crucial             | 2        | 2      | 13.33%  |
| SanDisk             | 1        | 1      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| OCZ                 | 1        | 1      | 6.67%   |
| Hewlett-Packard     | 1        | 1      | 6.67%   |
| Goodram             | 1        | 1      | 6.67%   |
| Gigabyte Technology | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 26       | 34     | 56.52%  |
| SSD     | 14       | 18     | 30.43%  |
| NVMe    | 3        | 4      | 6.52%   |
| Unknown | 2        | 2      | 4.35%   |
| MMC     | 1        | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 31       | 52     | 83.78%  |
| NVMe | 3        | 4      | 8.11%   |
| SAS  | 2        | 2      | 5.41%   |
| MMC  | 1        | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 36     | 63.16%  |
| 0.51-1.0   | 11       | 12     | 28.95%  |
| 1.01-2.0   | 3        | 4      | 7.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 20%     |
| 101-250        | 7        | 20%     |
| 51-100         | 7        | 20%     |
| 501-1000       | 4        | 11.43%  |
| More than 3000 | 3        | 8.57%   |
| 1001-2000      | 3        | 8.57%   |
| 21-50          | 2        | 5.71%   |
| 1-20           | 2        | 5.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 13       | 37.14%  |
| 21-50     | 8        | 22.86%  |
| 51-100    | 4        | 11.43%  |
| 251-500   | 3        | 8.57%   |
| 101-250   | 3        | 8.57%   |
| 501-1000  | 2        | 5.71%   |
| 2001-3000 | 1        | 2.86%   |
| 1001-2000 | 1        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD800JD-60LSA0 80GB       | 1        | 1      | 11.11%  |
| WDC WD5000AAKX-001CA0 500GB   | 1        | 1      | 11.11%  |
| WDC WD5000AAKS-60WWPA0 500GB  | 1        | 1      | 11.11%  |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 11.11%  |
| Seagate ST980811AS 80GB       | 1        | 1      | 11.11%  |
| Seagate ST9500325AS 500GB     | 1        | 1      | 11.11%  |
| Seagate ST3120026A 120GB      | 1        | 1      | 11.11%  |
| Hitachi HDS722020ALA330 2TB   | 1        | 1      | 11.11%  |
| Hitachi HDS721616PLA380 160GB | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 33.33%  |
| Seagate | 3        | 3      | 33.33%  |
| Hitachi | 2        | 2      | 22.22%  |
| Toshiba | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 33.33%  |
| Seagate | 3        | 3      | 33.33%  |
| Hitachi | 2        | 2      | 22.22%  |
| Toshiba | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 100%    |

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
| Works    | 17       | 27     | 47.22%  |
| Detected | 12       | 23     | 33.33%  |
| Malfunc  | 7        | 9      | 19.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 24       | 58.54%  |
| AMD                       | 9        | 21.95%  |
| SanDisk                   | 1        | 2.44%   |
| Samsung Electronics       | 1        | 2.44%   |
| Phison Electronics        | 1        | 2.44%   |
| Nvidia                    | 1        | 2.44%   |
| Marvell Technology Group  | 1        | 2.44%   |
| LSI Logic / Symbios Logic | 1        | 2.44%   |
| JMicron Technology        | 1        | 2.44%   |
| Broadcom / LSI            | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 10%     |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 6.67%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 5%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 3.33%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 3.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.67%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.67%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.67%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.67%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.67%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 1.67%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.67%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.67%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 1.67%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.67%   |
| Broadcom / LSI SAS1068 PCI-X Fusion-MPT SAS                                             | 1        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.67%   |
| AMD SB600 IDE                                                                           | 1        | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.67%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 46.51%  |
| IDE  | 19       | 44.19%  |
| NVMe | 3        | 6.98%   |
| SCSI | 1        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 71.43%  |
| AMD    | 10       | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 5.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 5.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 5.71%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 2.86%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 2.86%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 2.86%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 2.86%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 2.86%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1        | 2.86%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 2.86%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1        | 2.86%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.86%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 2.86%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 2.86%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 2.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2.86%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 2.86%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.86%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 2.86%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 2.86%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 2.86%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 2.86%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 1        | 2.86%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 2.86%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 2.86%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.86%   |
| AMD Phenom II X2 B55 Processor              | 1        | 2.86%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 2.86%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 2.86%   |
| AMD E-350 Processor                         | 1        | 2.86%   |
| AMD Athlon II X2 250 Processor              | 1        | 2.86%   |
| AMD A6-3620 APU with Radeon HD Graphics     | 1        | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 17.14%  |
| Intel Core i3           | 4        | 11.43%  |
| Intel Core 2 Duo        | 4        | 11.43%  |
| Intel Pentium Dual-Core | 3        | 8.57%   |
| Intel Xeon              | 2        | 5.71%   |
| Intel Core i7           | 2        | 5.71%   |
| AMD E                   | 2        | 5.71%   |
| Intel Pentium Dual      | 1        | 2.86%   |
| Intel Pentium D         | 1        | 2.86%   |
| Intel Pentium           | 1        | 2.86%   |
| Intel Atom              | 1        | 2.86%   |
| AMD Turion 64 X2 Mobile | 1        | 2.86%   |
| AMD Ryzen 9             | 1        | 2.86%   |
| AMD Ryzen 5             | 1        | 2.86%   |
| AMD Ryzen 3             | 1        | 2.86%   |
| AMD Phenom II X2        | 1        | 2.86%   |
| AMD FX                  | 1        | 2.86%   |
| AMD Athlon II X2        | 1        | 2.86%   |
| AMD A6                  | 1        | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 54.29%  |
| 4      | 10       | 28.57%  |
| 6      | 3        | 8.57%   |
| 12     | 1        | 2.86%   |
| 8      | 1        | 2.86%   |
| 1      | 1        | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 97.14%  |
| 2      | 1        | 2.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 71.43%  |
| 2      | 10       | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 35       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 7        | 20%     |
| 0x206a7    | 6        | 17.14%  |
| Unknown    | 4        | 11.43%  |
| 0x10676    | 2        | 5.71%   |
| 0x010000c8 | 2        | 5.71%   |
| 0xf64      | 1        | 2.86%   |
| 0xa0653    | 1        | 2.86%   |
| 0x6fd      | 1        | 2.86%   |
| 0x6fb      | 1        | 2.86%   |
| 0x406c4    | 1        | 2.86%   |
| 0x206c2    | 1        | 2.86%   |
| 0x20655    | 1        | 2.86%   |
| 0x08701013 | 1        | 2.86%   |
| 0x0810100b | 1        | 2.86%   |
| 0x0800820d | 1        | 2.86%   |
| 0x06000852 | 1        | 2.86%   |
| 0x05000119 | 1        | 2.86%   |
| 0x05000029 | 1        | 2.86%   |
| 0x03000027 | 1        | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 9        | 25.71%  |
| SandyBridge | 6        | 17.14%  |
| Westmere    | 2        | 5.71%   |
| K10         | 2        | 5.71%   |
| IvyBridge   | 2        | 5.71%   |
| Core        | 2        | 5.71%   |
| Bobcat      | 2        | 5.71%   |
| Zen+        | 1        | 2.86%   |
| Zen 2       | 1        | 2.86%   |
| Zen         | 1        | 2.86%   |
| Silvermont  | 1        | 2.86%   |
| Piledriver  | 1        | 2.86%   |
| NetBurst    | 1        | 2.86%   |
| KabyLake    | 1        | 2.86%   |
| K8 Hammer   | 1        | 2.86%   |
| K10 Llano   | 1        | 2.86%   |
| CometLake   | 1        | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 37.14%  |
| Nvidia | 11       | 31.43%  |
| AMD    | 11       | 31.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 10.81%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 5.41%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 5.41%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 5.41%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 2.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 2.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 2.7%    |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 2.7%    |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 2.7%    |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 2.7%    |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 2.7%    |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1        | 2.7%    |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1        | 2.7%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.7%    |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1        | 2.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 2.7%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 2.7%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 2.7%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 1        | 2.7%    |
| AMD Sumo [Radeon HD 6530D]                                                               | 1        | 2.7%    |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 1        | 2.7%    |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 2.7%    |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1        | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 2.7%    |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                             | 1        | 2.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 13       | 37.14%  |
| 1 x Nvidia | 11       | 31.43%  |
| 1 x AMD    | 9        | 25.71%  |
| 2 x AMD    | 2        | 5.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 29       | 82.86%  |
| Proprietary | 6        | 17.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 14       | 40%     |
| Unknown    | 12       | 34.29%  |
| 1.01-2.0   | 4        | 11.43%  |
| 0.51-1.0   | 3        | 8.57%   |
| 5.01-6.0   | 1        | 2.86%   |
| 3.01-4.0   | 1        | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 9        | 25.71%  |
| Hewlett-Packard         | 7        | 20%     |
| Goldstar                | 4        | 11.43%  |
| Acer                    | 4        | 11.43%  |
| NEC Computers           | 3        | 8.57%   |
| ViewSonic               | 2        | 5.71%   |
| Philips                 | 1        | 2.86%   |
| MSI                     | 1        | 2.86%   |
| Hitachi                 | 1        | 2.86%   |
| Chi Mei Optoelectronics | 1        | 2.86%   |
| AOC                     | 1        | 2.86%   |
| Ancor Communications    | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 5%      |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 2.5%    |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1        | 2.5%    |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1        | 2.5%    |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1        | 2.5%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1        | 2.5%    |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1        | 2.5%    |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.5%    |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 2.5%    |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1        | 2.5%    |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1        | 2.5%    |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1        | 2.5%    |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1        | 2.5%    |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                        | 1        | 2.5%    |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                 | 1        | 2.5%    |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 1        | 2.5%    |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 1        | 2.5%    |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch             | 1        | 2.5%    |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch          | 1        | 2.5%    |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1        | 2.5%    |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 2.5%    |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch            | 1        | 2.5%    |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch      | 1        | 2.5%    |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                  | 1        | 2.5%    |
| Goldstar LS1920wG GSM4BF0 1366x768 410x230mm 18.5-inch                | 1        | 2.5%    |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch | 1        | 2.5%    |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 1        | 2.5%    |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 1        | 2.5%    |
| Acer X193HQ ACR0069 1366x768 410x230mm 18.5-inch                      | 1        | 2.5%    |
| Acer S241HL ACR0312 1920x1080 531x299mm 24.0-inch                     | 1        | 2.5%    |
| Acer LCD Monitor G236HL 5280x1080                                     | 1        | 2.5%    |
| Acer LCD Monitor G236HL                                               | 1        | 2.5%    |
| Acer GF246 ACR055F 1920x1080 531x299mm 24.0-inch                      | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 25.71%  |
| 1366x768 (WXGA)    | 5        | 14.29%  |
| 1280x1024 (SXGA)   | 4        | 11.43%  |
| 3840x2160 (4K)     | 3        | 8.57%   |
| 1920x1200 (WUXGA)  | 3        | 8.57%   |
| 1680x1050 (WSXGA+) | 3        | 8.57%   |
| 1600x900 (HD+)     | 2        | 5.71%   |
| 1440x900 (WXGA+)   | 2        | 5.71%   |
| 5280x1080          | 1        | 2.86%   |
| 2560x1440 (QHD)    | 1        | 2.86%   |
| 1024x768 (XGA)     | 1        | 2.86%   |
| Unknown            | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 13.89%  |
| 21      | 4        | 11.11%  |
| 19      | 4        | 11.11%  |
| 18      | 4        | 11.11%  |
| Unknown | 4        | 11.11%  |
| 27      | 3        | 8.33%   |
| 23      | 3        | 8.33%   |
| 20      | 3        | 8.33%   |
| 17      | 2        | 5.56%   |
| 15      | 2        | 5.56%   |
| 28      | 1        | 2.78%   |
| 22      | 1        | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 13       | 37.14%  |
| 501-600     | 11       | 31.43%  |
| 301-350     | 4        | 11.43%  |
| Unknown     | 4        | 11.43%  |
| 351-400     | 2        | 5.71%   |
| 601-700     | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 54.55%  |
| 16/10   | 7        | 21.21%  |
| 5/4     | 4        | 12.12%  |
| Unknown | 3        | 9.09%   |
| 4/3     | 1        | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 25%     |
| 151-200        | 8        | 22.22%  |
| 141-150        | 6        | 16.67%  |
| Unknown        | 4        | 11.11%  |
| 301-350        | 3        | 8.33%   |
| 251-300        | 3        | 8.33%   |
| 101-110        | 2        | 5.56%   |
| 351-500        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 68.57%  |
| 101-120 | 6        | 17.14%  |
| Unknown | 4        | 11.43%  |
| 121-160 | 1        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 85.71%  |
| 2     | 4        | 11.43%  |
| 3     | 1        | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 21       | 39.62%  |
| Intel                                 | 9        | 16.98%  |
| Broadcom                              | 5        | 9.43%   |
| Qualcomm Atheros                      | 3        | 5.66%   |
| Ralink Technology                     | 2        | 3.77%   |
| TP-Link                               | 1        | 1.89%   |
| Samsung Electronics                   | 1        | 1.89%   |
| Ralink                                | 1        | 1.89%   |
| Qualcomm Atheros Communications       | 1        | 1.89%   |
| Nvidia                                | 1        | 1.89%   |
| Microsoft                             | 1        | 1.89%   |
| Marvell Technology Group              | 1        | 1.89%   |
| Linksys                               | 1        | 1.89%   |
| Broadcom Limited                      | 1        | 1.89%   |
| ASUSTek Computer                      | 1        | 1.89%   |
| ASIX Electronics                      | 1        | 1.89%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.89%   |
| 3Com                                  | 1        | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                      | 16       | 28.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                  | 3        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                  | 3        | 5.26%   |
| Intel 82566DM-2 Gigabit Network Connection                                                             | 2        | 3.51%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1        | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                                          | 1        | 1.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1        | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                                                      | 1        | 1.75%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1        | 1.75%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 1        | 1.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1        | 1.75%   |
| Ralink MT7601U Wireless Adapter                                                                        | 1        | 1.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 1.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                             | 1        | 1.75%   |
| Nvidia MCP61 Ethernet                                                                                  | 1        | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1        | 1.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                | 1        | 1.75%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1        | 1.75%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1        | 1.75%   |
| Intel I211 Gigabit Network Connection                                                                  | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                                                  | 1        | 1.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                          | 1        | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                                             | 1        | 1.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                                       | 1        | 1.75%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                                                | 1        | 1.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                                 | 1        | 1.75%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                                                  | 1        | 1.75%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1        | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1        | 1.75%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1        | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                                                          | 1        | 1.75%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1        | 1.75%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                                          | 1        | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 4        | 22.22%  |
| Ralink Technology                     | 2        | 11.11%  |
| Qualcomm Atheros                      | 2        | 11.11%  |
| TP-Link                               | 1        | 5.56%   |
| Ralink                                | 1        | 5.56%   |
| Qualcomm Atheros Communications       | 1        | 5.56%   |
| Microsoft                             | 1        | 5.56%   |
| Linksys                               | 1        | 5.56%   |
| Intel                                 | 1        | 5.56%   |
| Broadcom Limited                      | 1        | 5.56%   |
| Broadcom                              | 1        | 5.56%   |
| ASUSTek Computer                      | 1        | 5.56%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1        | 5.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1        | 5.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 5.56%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1        | 5.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 1        | 5.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                                                        | 1        | 5.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 5.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 5.56%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1        | 5.56%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1        | 5.56%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1        | 5.56%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1        | 5.56%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1        | 5.56%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 51.28%  |
| Intel                    | 9        | 23.08%  |
| Broadcom                 | 4        | 10.26%  |
| Samsung Electronics      | 1        | 2.56%   |
| Qualcomm Atheros         | 1        | 2.56%   |
| Nvidia                   | 1        | 2.56%   |
| Marvell Technology Group | 1        | 2.56%   |
| ASIX Electronics         | 1        | 2.56%   |
| 3Com                     | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 41.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 7.69%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 5.13%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 2.56%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 2.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 2.56%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 2.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1        | 2.56%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 2.56%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 2.56%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 66.67%  |
| WiFi     | 17       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 70.27%  |
| WiFi     | 11       | 29.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 71.43%  |
| 2     | 8        | 22.86%  |
| 4     | 1        | 2.86%   |
| 3     | 1        | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 85.71%  |
| Yes  | 5        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 4        | 57.14%  |
| Lite-On Technology      | 1        | 14.29%  |
| Intel                   | 1        | 14.29%  |
| Broadcom                | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 57.14%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 14.29%  |
| Intel AX200 Bluetooth                               | 1        | 14.29%  |
| Broadcom HP Bluethunder                             | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 47.06%  |
| AMD                   | 13       | 25.49%  |
| Nvidia                | 7        | 13.73%  |
| C-Media Electronics   | 2        | 3.92%   |
| Texas Instruments     | 1        | 1.96%   |
| Realtek Semiconductor | 1        | 1.96%   |
| Logitech              | 1        | 1.96%   |
| Ensoniq               | 1        | 1.96%   |
| Creative Labs         | 1        | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 10.71%  |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 7.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 5.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 3.57%   |
| AMD Wrestler HDMI Audio                                                           | 2        | 3.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 3.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 3.57%   |
| Texas Instruments PCM2902C Audio CODEC                                            | 1        | 1.79%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                        | 1        | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.79%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.79%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.79%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.79%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.79%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 1.79%   |
| Nvidia GF104 High Definition Audio Controller                                     | 1        | 1.79%   |
| Logitech Wireless Headset                                                         | 1        | 1.79%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 1.79%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 1.79%   |
| Ensoniq 5880B / Creative Labs CT5880                                              | 1        | 1.79%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 1.79%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                | 1        | 1.79%   |
| C-Media Electronics CM108 Audio Controller                                        | 1        | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 1.79%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 1        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 1.79%   |
| AMD FCH Azalia Controller                                                         | 1        | 1.79%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 1.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10       | 27.78%  |
| Kingston            | 6        | 16.67%  |
| Samsung Electronics | 4        | 11.11%  |
| Micron Technology   | 4        | 11.11%  |
| SK hynix            | 2        | 5.56%   |
| Unknown             | 2        | 5.56%   |
| Qumo                | 1        | 2.78%   |
| GeIL                | 1        | 2.78%   |
| Corsair             | 1        | 2.78%   |
| Avant               | 1        | 2.78%   |
| 2C0C1121390963FE    | 1        | 2.78%   |
| 2C0C1121390963FD    | 1        | 2.78%   |
| 2C0C1121390963F9    | 1        | 2.78%   |
| 2C0C1121390963F8    | 1        | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Unknown                                                             | 2        | 5.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1        | 2.7%    |
| Unknown RAM Module 8192MB DIMM 1600MT/s                             | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1        | 2.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                          | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1        | 2.7%    |
| Unknown RAM Module 1024MB DIMM DDR2                                 | 1        | 2.7%    |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                          | 1        | 2.7%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 1        | 2.7%    |
| SK hynix RAM HMT112U6TFR8C-H9 1024MB DIMM DDR3 1333MT/s             | 1        | 2.7%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                 | 1        | 2.7%    |
| Samsung RAM M378B2873FH0-CH9 1024MB DIMM DDR3 1333MT/s              | 1        | 2.7%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                 | 1        | 2.7%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s                | 1        | 2.7%    |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                           | 1        | 2.7%    |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                            | 1        | 2.7%    |
| Micron RAM 8HTF12864AY-800G1 1024MB DIMM DDR2 800MT/s               | 1        | 2.7%    |
| Micron RAM 16KTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s             | 1        | 2.7%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB DIMM DDR3 1066MT/s              | 1        | 2.7%    |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                           | 1        | 2.7%    |
| Kingston RAM Module 1024MB DIMM DDR2 800MT/s                        | 1        | 2.7%    |
| Kingston RAM KTW149-ELD 1024MB DIMM DDR3 1333MT/s                   | 1        | 2.7%    |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s                 | 1        | 2.7%    |
| Kingston RAM 99U5474-020.A00LF 4096MB DIMM DDR3 1333MT/s            | 1        | 2.7%    |
| Kingston RAM 9905458-009.A00LF 2GB DIMM DDR3 1333MT/s               | 1        | 2.7%    |
| GeIL RAM CL16-20-20 D4-3200 16384MB DIMM DDR4 2133MT/s              | 1        | 2.7%    |
| Corsair RAM CML8GX3M2A1600C9W 4GB DIMM DDR3 2133MT/s                | 1        | 2.7%    |
| Avant RAM Module 1GB DIMM DDR2 667MT/s                              | 1        | 2.7%    |
| 2C0C1121390963FE RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.7%    |
| 2C0C1121390963FD RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.7%    |
| 2C0C1121390963F9 RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.7%    |
| 2C0C1121390963F8 RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 28.57%  |
| DDR2    | 7        | 25%     |
| SDRAM   | 4        | 14.29%  |
| DDR4    | 4        | 14.29%  |
| Unknown | 3        | 10.71%  |
| DDR     | 2        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 26       | 92.86%  |
| SODIMM  | 1        | 3.57%   |
| FB-DIMM | 1        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 12       | 40%     |
| 4096  | 6        | 20%     |
| 1024  | 6        | 20%     |
| 8192  | 5        | 16.67%  |
| 16384 | 1        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 5        | 17.24%  |
| Unknown | 5        | 17.24%  |
| 1600    | 3        | 10.34%  |
| 3200    | 2        | 6.9%    |
| 2133    | 2        | 6.9%    |
| 800     | 2        | 6.9%    |
| 667     | 2        | 6.9%    |
| 49926   | 1        | 3.45%   |
| 19791   | 1        | 3.45%   |
| 3500    | 1        | 3.45%   |
| 1639    | 1        | 3.45%   |
| 1066    | 1        | 3.45%   |
| 1033    | 1        | 3.45%   |
| 400     | 1        | 3.45%   |
| 133     | 1        | 3.45%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Chicony Electronics     | 2        | 25%     |
| Z-Star Microelectronics | 1        | 12.5%   |
| Unknown                 | 1        | 12.5%   |
| Microsoft               | 1        | 12.5%   |
| Jieli Technology        | 1        | 12.5%   |
| Hewlett-Packard         | 1        | 12.5%   |
| Generalplus Technology  | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera                          | 1        | 12.5%   |
| Unknown Integrated RGB Camera                       | 1        | 12.5%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 12.5%   |
| Jieli USB PHY 2.0                                   | 1        | 12.5%   |
| HP Webcam HD 2300                                   | 1        | 12.5%   |
| Generalplus GENERAL WEBCAM                          | 1        | 12.5%   |
| Chicony HP Webcam                                   | 1        | 12.5%   |
| Chicony HP High Definition 1MP Webcam               | 1        | 12.5%   |

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
| 0     | 32       | 91.43%  |
| 1     | 3        | 8.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 33.33%  |
| Net/wireless     | 1        | 33.33%  |
| Graphics card    | 1        | 33.33%  |

