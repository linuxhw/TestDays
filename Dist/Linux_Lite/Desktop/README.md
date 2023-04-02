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

Total: 69

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 0AE4h C                     | [fe2502088a](https://linux-hardware.org/?probe=fe2502088a) | Mar 21, 2023 |
| HP            | 0AE4h C                     | [71bdbbb36f](https://linux-hardware.org/?probe=71bdbbb36f) | Mar 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [b0289f0ef8](https://linux-hardware.org/?probe=b0289f0ef8) | Jan 22, 2023 |
| ASUSTek       | M4N72-E                     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| Pegatron      | 2ACB                        | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Braview       | BRW-BSWI-D2                 | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| Packard Be... | MCP73VT-PM                  | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| HP            | 1632                        | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP            | 1632                        | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| ASUSTek       | M51BC                       | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP            | 3047h                       | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Dell          | 018D1Y A00                  | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| HP            | 2820h                       | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Dell          | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| Dell          | 0HY9JP A02                  | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn       | 2A8C                        | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| ABIT          | IP35-E                      | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Pegatron      | 2ACB                        | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASRock        | H61M-VG3                    | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Gigabyte      | GA-E350N                    | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Biostar       | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar       | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | M5A78L LE                   | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Intel         | DG31PR AAD97573-300         | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-300         | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP            | 0A98h                       | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS           | Livermore                   | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| MSI           | Boston                      | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| MSI           | B75A-G43                    | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| Minix         | NEO Z83-4 V1.1              | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| HP            | 0ACCh                       | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel         | H61M-S1                     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo        | ThinkCentre A55 9265BL7     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP            | 2AA6 PVT                    | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| MSI           | Z77A-G43                    | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| ASRock        | N68C-S UCC                  | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock        | N68C-S UCC                  | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway        | I61MG4                      | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway        | I61MG4                      | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Acer          | EQ35M                       | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Linux Lite 5.8 | 11       | 25%     |
| Linux Lite 5.2 | 7        | 15.91%  |
| Linux Lite 5.0 | 7        | 15.91%  |
| Linux Lite 5.6 | 6        | 13.64%  |
| Linux Lite 5.4 | 6        | 13.64%  |
| Linux Lite 6.2 | 2        | 4.55%   |
| Linux Lite 6.0 | 2        | 4.55%   |
| Linux Lite 3.8 | 2        | 4.55%   |
| Linux Lite 4.6 | 1        | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Lite | 44       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.4.0-96-generic     | 3        | 6.67%   |
| 5.4.0-91-generic     | 3        | 6.67%   |
| 5.4.0-80-generic     | 2        | 4.44%   |
| 5.4.0-54-generic     | 2        | 4.44%   |
| 5.4.0-48-generic     | 2        | 4.44%   |
| 5.4.0-42-generic     | 2        | 4.44%   |
| 5.4.0-113-generic    | 2        | 4.44%   |
| 5.4.0-104-generic    | 2        | 4.44%   |
| 5.15.0-58-generic    | 2        | 4.44%   |
| 4.4.0-112-generic    | 2        | 4.44%   |
| 6.0.0-1.linuxlite    | 1        | 2.22%   |
| 5.9.0                | 1        | 2.22%   |
| 5.4.0-99-generic     | 1        | 2.22%   |
| 5.4.0-88-generic     | 1        | 2.22%   |
| 5.4.0-72-generic     | 1        | 2.22%   |
| 5.4.0-70-generic     | 1        | 2.22%   |
| 5.4.0-58-generic     | 1        | 2.22%   |
| 5.4.0-52-generic     | 1        | 2.22%   |
| 5.4.0-45-generic     | 1        | 2.22%   |
| 5.4.0-37-generic     | 1        | 2.22%   |
| 5.4.0-33-generic     | 1        | 2.22%   |
| 5.4.0-133-generic    | 1        | 2.22%   |
| 5.4.0-132-generic    | 1        | 2.22%   |
| 5.4.0-131-generic    | 1        | 2.22%   |
| 5.4.0-110-generic    | 1        | 2.22%   |
| 5.4.0-109-generic    | 1        | 2.22%   |
| 5.4.0-107-generic    | 1        | 2.22%   |
| 5.4.0-105-generic    | 1        | 2.22%   |
| 5.15.0-46-generic    | 1        | 2.22%   |
| 5.15.0-33-generic    | 1        | 2.22%   |
| 5.15.0               | 1        | 2.22%   |
| 5.13.0-44-lowlatency | 1        | 2.22%   |
| 4.15.0-147-generic   | 1        | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 34       | 75.56%  |
| 5.15.0  | 5        | 11.11%  |
| 4.4.0   | 2        | 4.44%   |
| 6.0.0   | 1        | 2.22%   |
| 5.9.0   | 1        | 2.22%   |
| 5.13.0  | 1        | 2.22%   |
| 4.15.0  | 1        | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 75.56%  |
| 5.15    | 5        | 11.11%  |
| 4.4     | 2        | 4.44%   |
| 6.0     | 1        | 2.22%   |
| 5.9     | 1        | 2.22%   |
| 5.13    | 1        | 2.22%   |
| 4.15    | 1        | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 42       | 95.45%  |
| i686   | 2        | 4.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 33       | 75%     |
| GNOME | 11       | 25%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 44       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 25       | 56.82%  |
| TDM     | 10       | 22.73%  |
| Unknown | 9        | 20.45%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 36.36%  |
| pt_BR | 5        | 11.36%  |
| es_MX | 4        | 9.09%   |
| fr_FR | 2        | 4.55%   |
| en_GB | 2        | 4.55%   |
| en_CA | 2        | 4.55%   |
| de_DE | 2        | 4.55%   |
| ru_UA | 1        | 2.27%   |
| pl_PL | 1        | 2.27%   |
| nl_NL | 1        | 2.27%   |
| hu_HU | 1        | 2.27%   |
| fr_CA | 1        | 2.27%   |
| es_ES | 1        | 2.27%   |
| es_CL | 1        | 2.27%   |
| en_NZ | 1        | 2.27%   |
| en_IE | 1        | 2.27%   |
| da_DK | 1        | 2.27%   |
| C     | 1        | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 35       | 79.55%  |
| EFI  | 9        | 20.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 40       | 90.91%  |
| Overlay | 3        | 6.82%   |
| Ext3    | 1        | 2.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 19       | 43.18%  |
| Unknown | 13       | 29.55%  |
| GPT     | 12       | 27.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 77.27%  |
| Yes       | 10       | 22.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 68.18%  |
| Yes       | 14       | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 18.18%  |
| Lenovo              | 5        | 11.36%  |
| MSI                 | 4        | 9.09%   |
| ASUSTek Computer    | 4        | 9.09%   |
| Gigabyte Technology | 3        | 6.82%   |
| Pegatron            | 2        | 4.55%   |
| Intel               | 2        | 4.55%   |
| Foxconn             | 2        | 4.55%   |
| Dell                | 2        | 4.55%   |
| ASRock              | 2        | 4.55%   |
| Acer                | 2        | 4.55%   |
| Packard Bell        | 1        | 2.27%   |
| Minix               | 1        | 2.27%   |
| Jetway              | 1        | 2.27%   |
| Fujitsu             | 1        | 2.27%   |
| EVGA                | 1        | 2.27%   |
| Braview             | 1        | 2.27%   |
| Biostar             | 1        | 2.27%   |
| ABIT                | 1        | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7758                            | 2        | 4.55%   |
| Pegatron 520-1135la                    | 1        | 2.27%   |
| Pegatron 520-1030a                     | 1        | 2.27%   |
| Packard Bell ISTART D2314              | 1        | 2.27%   |
| MSI MS-7C95                            | 1        | 2.27%   |
| MSI FZ079AA-ABF a6625fr                | 1        | 2.27%   |
| Minix Z83-4                            | 1        | 2.27%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1        | 2.27%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1        | 2.27%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1        | 2.27%   |
| Lenovo ThinkCentre A55 9265BL7         | 1        | 2.27%   |
| Lenovo H505S 10107                     | 1        | 2.27%   |
| Jetway I61MG4                          | 1        | 2.27%   |
| Intel H61M-S1                          | 1        | 2.27%   |
| Intel DG31PR AAD97573-300              | 1        | 2.27%   |
| HP Z400 Workstation                    | 1        | 2.27%   |
| HP xw8600 Workstation                  | 1        | 2.27%   |
| HP t5000 series                        | 1        | 2.27%   |
| HP rp5800                              | 1        | 2.27%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.27%   |
| HP Compaq dc5800 Small Form Factor     | 1        | 2.27%   |
| HP Compaq 6005 Pro SFF PC              | 1        | 2.27%   |
| HP 200-5320br                          | 1        | 2.27%   |
| Gigabyte X570 AORUS MASTER             | 1        | 2.27%   |
| Gigabyte GA-E350N                      | 1        | 2.27%   |
| Gigabyte B450M DS3H                    | 1        | 2.27%   |
| Fujitsu ESPRIMO P2560                  | 1        | 2.27%   |
| Foxconn 500B Microtower                | 1        | 2.27%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1        | 2.27%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1        | 2.27%   |
| Dell OptiPlex 790                      | 1        | 2.27%   |
| Dell Inspiron 560                      | 1        | 2.27%   |
| Braview BRW-BSWI-D2                    | 1        | 2.27%   |
| Biostar G41D3C                         | 1        | 2.27%   |
| ASUS TUF B450-PLUS GAMING              | 1        | 2.27%   |
| ASUS M5A78L-M LX PLUS                  | 1        | 2.27%   |
| ASUS M5A78L LE                         | 1        | 2.27%   |
| ASUS M4N72-E                           | 1        | 2.27%   |
| ASRock N68C-S UCC                      | 1        | 2.27%   |
| ASRock H61M-VG3                        | 1        | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo ThinkCentre  | 3        | 6.82%   |
| HP Compaq           | 3        | 6.82%   |
| MSI MS-7758         | 2        | 4.55%   |
| Pegatron 520-1135la | 1        | 2.27%   |
| Pegatron 520-1030a  | 1        | 2.27%   |
| Packard Bell ISTART | 1        | 2.27%   |
| MSI MS-7C95         | 1        | 2.27%   |
| MSI FZ079AA-ABF     | 1        | 2.27%   |
| Minix Z83-4         | 1        | 2.27%   |
| Lenovo ThinkStation | 1        | 2.27%   |
| Lenovo H505S        | 1        | 2.27%   |
| Jetway I61MG4       | 1        | 2.27%   |
| Intel H61M-S1       | 1        | 2.27%   |
| Intel DG31PR        | 1        | 2.27%   |
| HP Z400             | 1        | 2.27%   |
| HP xw8600           | 1        | 2.27%   |
| HP t5000            | 1        | 2.27%   |
| HP rp5800           | 1        | 2.27%   |
| HP 200-5320br       | 1        | 2.27%   |
| Gigabyte X570       | 1        | 2.27%   |
| Gigabyte GA-E350N   | 1        | 2.27%   |
| Gigabyte B450M      | 1        | 2.27%   |
| Fujitsu ESPRIMO     | 1        | 2.27%   |
| Foxconn 500B        | 1        | 2.27%   |
| Foxconn 45CMX       | 1        | 2.27%   |
| EVGA X58            | 1        | 2.27%   |
| Dell OptiPlex       | 1        | 2.27%   |
| Dell Inspiron       | 1        | 2.27%   |
| Braview BRW-BSWI-D2 | 1        | 2.27%   |
| Biostar G41D3C      | 1        | 2.27%   |
| ASUS TUF            | 1        | 2.27%   |
| ASUS M5A78L-M       | 1        | 2.27%   |
| ASUS M5A78L         | 1        | 2.27%   |
| ASUS M4N72-E        | 1        | 2.27%   |
| ASRock N68C-S       | 1        | 2.27%   |
| ASRock H61M-VG3     | 1        | 2.27%   |
| Acer Veriton        | 1        | 2.27%   |
| Acer Aspire         | 1        | 2.27%   |
| ABIT IP35-E         | 1        | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 10       | 22.73%  |
| 2008 | 8        | 18.18%  |
| 2012 | 7        | 15.91%  |
| 2010 | 6        | 13.64%  |
| 2007 | 3        | 6.82%   |
| 2020 | 2        | 4.55%   |
| 2018 | 2        | 4.55%   |
| 2021 | 1        | 2.27%   |
| 2019 | 1        | 2.27%   |
| 2017 | 1        | 2.27%   |
| 2016 | 1        | 2.27%   |
| 2013 | 1        | 2.27%   |
| 2009 | 1        | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 44       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 43       | 97.73%  |
| Enabled  | 1        | 2.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 13       | 29.55%  |
| 1.01-2.0   | 8        | 18.18%  |
| 4.01-8.0   | 7        | 15.91%  |
| 16.01-24.0 | 5        | 11.36%  |
| 8.01-16.0  | 5        | 11.36%  |
| 32.01-64.0 | 4        | 9.09%   |
| 24.01-32.0 | 1        | 2.27%   |
| 2.01-3.0   | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 20       | 45.45%  |
| 2.01-3.0  | 9        | 20.45%  |
| 4.01-8.0  | 5        | 11.36%  |
| 0.51-1.0  | 5        | 11.36%  |
| 3.01-4.0  | 4        | 9.09%   |
| 8.01-16.0 | 1        | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 52.27%  |
| 2      | 12       | 27.27%  |
| 3      | 5        | 11.36%  |
| 0      | 2        | 4.55%   |
| 5      | 1        | 2.27%   |
| 4      | 1        | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 50%     |
| No        | 22       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 97.73%  |
| No        | 1        | 2.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 54.55%  |
| No        | 20       | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 84.09%  |
| Yes       | 7        | 15.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 20.45%  |
| Brazil      | 7        | 15.91%  |
| Mexico      | 4        | 9.09%   |
| Canada      | 4        | 9.09%   |
| Peru        | 3        | 6.82%   |
| UK          | 2        | 4.55%   |
| Poland      | 2        | 4.55%   |
| Germany     | 2        | 4.55%   |
| France      | 2        | 4.55%   |
| Ukraine     | 1        | 2.27%   |
| New Zealand | 1        | 2.27%   |
| Netherlands | 1        | 2.27%   |
| Malaysia    | 1        | 2.27%   |
| Ireland     | 1        | 2.27%   |
| Hungary     | 1        | 2.27%   |
| Greenland   | 1        | 2.27%   |
| Chile       | 1        | 2.27%   |
| Australia   | 1        | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Ottawa               | 2        | 4.55%   |
| Mexico City          | 2        | 4.55%   |
| Lima                 | 2        | 4.55%   |
| Würzburg            | 1        | 2.27%   |
| Wellington           | 1        | 2.27%   |
| Waterbury            | 1        | 2.27%   |
| Warsaw               | 1        | 2.27%   |
| Vancouver            | 1        | 2.27%   |
| Trujillo             | 1        | 2.27%   |
| Thetford-Mines       | 1        | 2.27%   |
| Sao Paulo            | 1        | 2.27%   |
| Rio de Janeiro       | 1        | 2.27%   |
| Purmerend            | 1        | 2.27%   |
| Porto Velho          | 1        | 2.27%   |
| Porto Alegre         | 1        | 2.27%   |
| Pabianice            | 1        | 2.27%   |
| Osasco               | 1        | 2.27%   |
| Oldenburg            | 1        | 2.27%   |
| Nashville            | 1        | 2.27%   |
| Narbonne             | 1        | 2.27%   |
| Maineville           | 1        | 2.27%   |
| Long Seridan         | 1        | 2.27%   |
| Kyiv                 | 1        | 2.27%   |
| Ilulissat            | 1        | 2.27%   |
| Fortin de las Flores | 1        | 2.27%   |
| Enfield              | 1        | 2.27%   |
| Dublin               | 1        | 2.27%   |
| Dover                | 1        | 2.27%   |
| Cuauhtemoc           | 1        | 2.27%   |
| Craigavon            | 1        | 2.27%   |
| Conchali             | 1        | 2.27%   |
| Columbus             | 1        | 2.27%   |
| Cibakhaza            | 1        | 2.27%   |
| Cheshire             | 1        | 2.27%   |
| Chapel Hill          | 1        | 2.27%   |
| Carrollton           | 1        | 2.27%   |
| Canto do Buriti      | 1        | 2.27%   |
| Campinas             | 1        | 2.27%   |
| Brisbane             | 1        | 2.27%   |
| Birmingham           | 1        | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 24.19%  |
| WDC                 | 14       | 19     | 22.58%  |
| Samsung Electronics | 8        | 8      | 12.9%   |
| Toshiba             | 3        | 3      | 4.84%   |
| SanDisk             | 2        | 2      | 3.23%   |
| Kingston            | 2        | 4      | 3.23%   |
| Hitachi             | 2        | 2      | 3.23%   |
| Crucial             | 2        | 2      | 3.23%   |
| Unknown             | 1        | 1      | 1.61%   |
| PNY                 | 1        | 1      | 1.61%   |
| Phison              | 1        | 1      | 1.61%   |
| OCZ                 | 1        | 1      | 1.61%   |
| Maxtor              | 1        | 1      | 1.61%   |
| Mass                | 1        | 1      | 1.61%   |
| Intenso             | 1        | 1      | 1.61%   |
| HPE                 | 1        | 1      | 1.61%   |
| Hewlett-Packard     | 1        | 1      | 1.61%   |
| Goodram             | 1        | 1      | 1.61%   |
| Gigabyte Technology | 1        | 1      | 1.61%   |
| Fanxiang            | 1        | 2      | 1.61%   |
| China               | 1        | 1      | 1.61%   |
| A-DATA Technology   | 1        | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3        | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB         | 2        | 2.9%    |
| WDC WDS250G2B0A 250GB SSD           | 1        | 1.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 1.45%   |
| WDC WD800JD-60LSA0 80GB             | 1        | 1.45%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 1.45%   |
| WDC WD5000AAKS-60WWPA0 500GB        | 1        | 1.45%   |
| WDC WD5000AADS-56S9B0 500GB         | 1        | 1.45%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1.45%   |
| WDC WD5000AACS-00G8B1 500GB         | 1        | 1.45%   |
| WDC WD20PURX-64PFUY0 2TB            | 1        | 1.45%   |
| WDC WD2005FBYZ-01YCBB2 2TB          | 1        | 1.45%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1        | 1.45%   |
| WDC WD10EZEX-07WN4A0 1TB            | 1        | 1.45%   |
| WDC WD10EADS-00L5B1 1TB             | 1        | 1.45%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 1        | 1.45%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB  | 1        | 1.45%   |
| Unknown MMC Card  32GB              | 1        | 1.45%   |
| Toshiba MK1059GSM 1TB               | 1        | 1.45%   |
| Toshiba HDWD110 1TB                 | 1        | 1.45%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.45%   |
| Seagate ST980811AS 80GB             | 1        | 1.45%   |
| Seagate ST9500325AS 500GB           | 1        | 1.45%   |
| Seagate ST500LM030-1RK17D 500GB     | 1        | 1.45%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1.45%   |
| Seagate ST3750640NS 752GB           | 1        | 1.45%   |
| Seagate ST3500418AS 500GB           | 1        | 1.45%   |
| Seagate ST3320620A 320GB            | 1        | 1.45%   |
| Seagate ST3250310AS 250GB           | 1        | 1.45%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1.45%   |
| Seagate ST3120026A 120GB            | 1        | 1.45%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1.45%   |
| Seagate ST1000LM010-9YH146 1TB      | 1        | 1.45%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1.45%   |
| SanDisk SDSSDA240G 240GB            | 1        | 1.45%   |
| SanDisk SD8TB8U256G1001 256GB SSD   | 1        | 1.45%   |
| Samsung SSD PM851 2.5 7mm 256GB     | 1        | 1.45%   |
| Samsung SSD 970 EVO Plus 250GB      | 1        | 1.45%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.45%   |
| Samsung SSD 860 EVO 250GB           | 1        | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 42.86%  |
| WDC                 | 12       | 14     | 34.29%  |
| Toshiba             | 3        | 3      | 8.57%   |
| Hitachi             | 2        | 2      | 5.71%   |
| Samsung Electronics | 1        | 1      | 2.86%   |
| Maxtor              | 1        | 1      | 2.86%   |
| HPE                 | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 5      | 23.81%  |
| WDC                 | 2        | 3      | 9.52%   |
| SanDisk             | 2        | 2      | 9.52%   |
| Kingston            | 2        | 4      | 9.52%   |
| Crucial             | 2        | 2      | 9.52%   |
| PNY                 | 1        | 1      | 4.76%   |
| OCZ                 | 1        | 1      | 4.76%   |
| Hewlett-Packard     | 1        | 1      | 4.76%   |
| Goodram             | 1        | 1      | 4.76%   |
| Gigabyte Technology | 1        | 1      | 4.76%   |
| Fanxiang            | 1        | 2      | 4.76%   |
| China               | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 29       | 39     | 51.79%  |
| SSD     | 20       | 25     | 35.71%  |
| NVMe    | 4        | 5      | 7.14%   |
| Unknown | 2        | 2      | 3.57%   |
| MMC     | 1        | 1      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 64     | 85.11%  |
| NVMe | 4        | 5      | 8.51%   |
| SAS  | 2        | 2      | 4.26%   |
| MMC  | 1        | 1      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 47     | 68.75%  |
| 0.51-1.0   | 12       | 13     | 25%     |
| 1.01-2.0   | 3        | 4      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 29.55%  |
| 251-500        | 8        | 18.18%  |
| 51-100         | 7        | 15.91%  |
| 501-1000       | 5        | 11.36%  |
| More than 3000 | 3        | 6.82%   |
| 21-50          | 3        | 6.82%   |
| 1001-2000      | 3        | 6.82%   |
| 1-20           | 2        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 16       | 36.36%  |
| 21-50     | 9        | 20.45%  |
| 51-100    | 7        | 15.91%  |
| 101-250   | 5        | 11.36%  |
| 251-500   | 3        | 6.82%   |
| 501-1000  | 2        | 4.55%   |
| 2001-3000 | 1        | 2.27%   |
| 1001-2000 | 1        | 2.27%   |

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
| Works    | 22       | 33     | 47.83%  |
| Detected | 17       | 30     | 36.96%  |
| Malfunc  | 7        | 9      | 15.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 28       | 54.9%   |
| AMD                       | 12       | 23.53%  |
| Nvidia                    | 3        | 5.88%   |
| Samsung Electronics       | 2        | 3.92%   |
| SanDisk                   | 1        | 1.96%   |
| Phison Electronics        | 1        | 1.96%   |
| Marvell Technology Group  | 1        | 1.96%   |
| LSI Logic / Symbios Logic | 1        | 1.96%   |
| JMicron Technology        | 1        | 1.96%   |
| Broadcom / LSI            | 1        | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 9.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 6.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 5.48%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 4.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 4.11%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.74%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 2.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.37%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.37%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 1.37%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.37%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 1.37%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.37%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.37%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 1.37%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.37%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.37%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 1.37%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.37%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.37%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.37%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 1.37%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.37%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.37%   |
| Broadcom / LSI SAS1068 PCI-X Fusion-MPT SAS                                             | 1        | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 47.27%  |
| IDE  | 23       | 41.82%  |
| NVMe | 4        | 7.27%   |
| RAID | 1        | 1.82%   |
| SCSI | 1        | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 68.18%  |
| AMD    | 14       | 31.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 6.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 4.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 4.55%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 2.27%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 2.27%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 2.27%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 2.27%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 2.27%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 2.27%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 2.27%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1        | 2.27%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 2.27%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1        | 2.27%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.27%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 2.27%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 2.27%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 2.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2.27%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 2.27%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.27%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 2.27%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 2.27%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 2.27%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 1        | 2.27%   |
| Intel Celeron CPU G540 @ 2.50GHz            | 1        | 2.27%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 2.27%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 1        | 2.27%   |
| AMD Sempron 145 Processor                   | 1        | 2.27%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 2.27%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 2.27%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 2.27%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.27%   |
| AMD Phenom II X2 B55 Processor              | 1        | 2.27%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 2.27%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 2.27%   |
| AMD E-350 Processor                         | 1        | 2.27%   |
| AMD Athlon II X2 250 Processor              | 1        | 2.27%   |
| AMD Athlon II X2 245 Processor              | 1        | 2.27%   |
| AMD A6-3620 APU with Radeon HD Graphics     | 1        | 2.27%   |
| AMD A6-3600 APU with Radeon HD Graphics     | 1        | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 13.64%  |
| Intel Pentium Dual-Core | 4        | 9.09%   |
| Intel Core i3           | 4        | 9.09%   |
| Intel Core 2 Duo        | 4        | 9.09%   |
| Intel Xeon              | 3        | 6.82%   |
| Intel Pentium Dual      | 2        | 4.55%   |
| Intel Core i7           | 2        | 4.55%   |
| Intel Celeron           | 2        | 4.55%   |
| AMD Ryzen 5             | 2        | 4.55%   |
| AMD E                   | 2        | 4.55%   |
| AMD Athlon II X2        | 2        | 4.55%   |
| AMD A6                  | 2        | 4.55%   |
| Intel Pentium D         | 1        | 2.27%   |
| Intel Pentium           | 1        | 2.27%   |
| Intel Atom              | 1        | 2.27%   |
| AMD Turion 64 X2 Mobile | 1        | 2.27%   |
| AMD Sempron             | 1        | 2.27%   |
| AMD Ryzen 9             | 1        | 2.27%   |
| AMD Ryzen 3             | 1        | 2.27%   |
| AMD Phenom II X2        | 1        | 2.27%   |
| AMD FX                  | 1        | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 54.55%  |
| 4      | 11       | 25%     |
| 6      | 5        | 11.36%  |
| 1      | 2        | 4.55%   |
| 12     | 1        | 2.27%   |
| 8      | 1        | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 97.73%  |
| 2      | 1        | 2.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 72.73%  |
| 2      | 12       | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 8        | 18.18%  |
| 0x206a7    | 7        | 15.91%  |
| Unknown    | 6        | 13.64%  |
| 0x010000c8 | 3        | 6.82%   |
| 0x406c4    | 2        | 4.55%   |
| 0x206c2    | 2        | 4.55%   |
| 0x10676    | 2        | 4.55%   |
| 0xf64      | 1        | 2.27%   |
| 0xa0653    | 1        | 2.27%   |
| 0x6fd      | 1        | 2.27%   |
| 0x6fb      | 1        | 2.27%   |
| 0x20655    | 1        | 2.27%   |
| 0x0a50000d | 1        | 2.27%   |
| 0x08701013 | 1        | 2.27%   |
| 0x0810100b | 1        | 2.27%   |
| 0x0800820d | 1        | 2.27%   |
| 0x06000852 | 1        | 2.27%   |
| 0x05000119 | 1        | 2.27%   |
| 0x05000029 | 1        | 2.27%   |
| 0x03000027 | 1        | 2.27%   |
| 0x010000c7 | 1        | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 10       | 22.73%  |
| SandyBridge | 7        | 15.91%  |
| K10         | 4        | 9.09%   |
| Westmere    | 3        | 6.82%   |
| Core        | 3        | 6.82%   |
| Silvermont  | 2        | 4.55%   |
| K10 Llano   | 2        | 4.55%   |
| IvyBridge   | 2        | 4.55%   |
| Bobcat      | 2        | 4.55%   |
| Zen+        | 1        | 2.27%   |
| Zen 3       | 1        | 2.27%   |
| Zen 2       | 1        | 2.27%   |
| Zen         | 1        | 2.27%   |
| Piledriver  | 1        | 2.27%   |
| NetBurst    | 1        | 2.27%   |
| KabyLake    | 1        | 2.27%   |
| K8 Hammer   | 1        | 2.27%   |
| CometLake   | 1        | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 34.09%  |
| AMD    | 15       | 34.09%  |
| Nvidia | 14       | 31.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 8.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 6.52%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 6.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 4.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 4.35%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 2.17%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 2.17%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 2.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 2.17%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 2.17%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 2.17%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 2.17%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 2.17%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1        | 2.17%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1        | 2.17%   |
| Nvidia C73 [GeForce 7050 / nForce 610i]                                                  | 1        | 2.17%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 2.17%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1        | 2.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 2.17%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 2.17%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 2.17%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1        | 2.17%   |
| AMD Sumo [Radeon HD 6530D]                                                               | 1        | 2.17%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 1        | 2.17%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 2.17%   |
| AMD RS780L [Radeon 3000]                                                                 | 1        | 2.17%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1        | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 2.17%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                             | 1        | 2.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1        | 2.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.17%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 15       | 34.09%  |
| 1 x Nvidia | 14       | 31.82%  |
| 1 x AMD    | 13       | 29.55%  |
| 2 x AMD    | 2        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 36       | 81.82%  |
| Proprietary | 7        | 15.91%  |
| Unknown     | 1        | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 38.64%  |
| 0.01-0.5   | 15       | 34.09%  |
| 1.01-2.0   | 4        | 9.09%   |
| 0.51-1.0   | 4        | 9.09%   |
| 5.01-6.0   | 2        | 4.55%   |
| 3.01-4.0   | 2        | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 9        | 20.93%  |
| Hewlett-Packard         | 9        | 20.93%  |
| Goldstar                | 5        | 11.63%  |
| Acer                    | 4        | 9.3%    |
| NEC Computers           | 3        | 6.98%   |
| Ancor Communications    | 3        | 6.98%   |
| ViewSonic               | 2        | 4.65%   |
| Toshiba                 | 1        | 2.33%   |
| Sony                    | 1        | 2.33%   |
| Philips                 | 1        | 2.33%   |
| MSI                     | 1        | 2.33%   |
| Hitachi                 | 1        | 2.33%   |
| Chi Mei Optoelectronics | 1        | 2.33%   |
| AOC                     | 1        | 2.33%   |
| Unknown                 | 1        | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2        | 4.17%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 4.17%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1        | 2.08%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1        | 2.08%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1        | 2.08%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1        | 2.08%   |
| Sony TV SNYDC01 1360x768                                              | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1        | 2.08%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1        | 2.08%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1        | 2.08%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1        | 2.08%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1        | 2.08%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                  | 1        | 2.08%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.08%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 2.08%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                    | 1        | 2.08%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch        | 1        | 2.08%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch          | 1        | 2.08%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch            | 1        | 2.08%   |
| MSI MAG275R MSI3CB5 1920x1080 598x336mm 27.0-inch                     | 1        | 2.08%   |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                 | 1        | 2.08%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch             | 1        | 2.08%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch            | 1        | 2.08%   |
| Hewlett-Packard TouchSmart HWP4211 1920x1080 509x286mm 23.0-inch      | 1        | 2.08%   |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch             | 1        | 2.08%   |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch          | 1        | 2.08%   |
| Hewlett-Packard LCD Monitor HWP285A 1920x1080 470x270mm 21.3-inch     | 1        | 2.08%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 2.08%   |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch            | 1        | 2.08%   |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                  | 1        | 2.08%   |
| Goldstar E2241 GSM5819 1920x1080 477x268mm 21.5-inch                  | 1        | 2.08%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                   | 1        | 2.08%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch | 1        | 2.08%   |
| AOC 1621Wb AOC1621 1366x768 344x194mm 15.5-inch                       | 1        | 2.08%   |
| Ancor Communications ASUS VB175 ACI17B8 1280x1024 340x270mm 17.1-inch | 1        | 2.08%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch | 1        | 2.08%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 1        | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 25.58%  |
| 1366x768 (WXGA)    | 5        | 11.63%  |
| 1280x1024 (SXGA)   | 5        | 11.63%  |
| 3840x2160 (4K)     | 3        | 6.98%   |
| 1920x1200 (WUXGA)  | 3        | 6.98%   |
| 1680x1050 (WSXGA+) | 3        | 6.98%   |
| 1440x900 (WXGA+)   | 3        | 6.98%   |
| 2560x1440 (QHD)    | 2        | 4.65%   |
| 1600x900 (HD+)     | 2        | 4.65%   |
| 1360x768           | 2        | 4.65%   |
| 5280x1080          | 1        | 2.33%   |
| 1280x720 (HD)      | 1        | 2.33%   |
| 1024x768 (XGA)     | 1        | 2.33%   |
| Unknown            | 1        | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 11.36%  |
| 21      | 5        | 11.36%  |
| 18      | 5        | 11.36%  |
| Unknown | 5        | 11.36%  |
| 27      | 4        | 9.09%   |
| 23      | 4        | 9.09%   |
| 19      | 4        | 9.09%   |
| 17      | 4        | 9.09%   |
| 20      | 3        | 6.82%   |
| 15      | 2        | 4.55%   |
| 72      | 1        | 2.27%   |
| 28      | 1        | 2.27%   |
| 22      | 1        | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 15       | 34.88%  |
| 501-600     | 13       | 30.23%  |
| 301-350     | 6        | 13.95%  |
| Unknown     | 5        | 11.63%  |
| 351-400     | 2        | 4.65%   |
| 601-700     | 1        | 2.33%   |
| 1501-2000   | 1        | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 53.66%  |
| 16/10   | 8        | 19.51%  |
| 5/4     | 6        | 14.63%  |
| Unknown | 4        | 9.76%   |
| 4/3     | 1        | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 25%     |
| 151-200        | 9        | 20.45%  |
| 141-150        | 8        | 18.18%  |
| Unknown        | 5        | 11.36%  |
| 301-350        | 4        | 9.09%   |
| 251-300        | 3        | 6.82%   |
| 101-110        | 2        | 4.55%   |
| More than 1000 | 1        | 2.27%   |
| 351-500        | 1        | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 64.29%  |
| 101-120 | 8        | 19.05%  |
| Unknown | 5        | 11.9%   |
| 1-50    | 1        | 2.38%   |
| 121-160 | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 88.64%  |
| 2     | 4        | 9.09%   |
| 3     | 1        | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 26       | 37.68%  |
| Intel                                 | 10       | 14.49%  |
| Broadcom                              | 6        | 8.7%    |
| Ralink Technology                     | 4        | 5.8%    |
| Ralink                                | 3        | 4.35%   |
| Qualcomm Atheros                      | 3        | 4.35%   |
| Nvidia                                | 2        | 2.9%    |
| ASUSTek Computer                      | 2        | 2.9%    |
| ZTE WCDMA Technologies MSM            | 1        | 1.45%   |
| TP-Link                               | 1        | 1.45%   |
| Sundance Technology Inc / IC Plus     | 1        | 1.45%   |
| Samsung Electronics                   | 1        | 1.45%   |
| Qualcomm Atheros Communications       | 1        | 1.45%   |
| Microsoft                             | 1        | 1.45%   |
| MediaTek                              | 1        | 1.45%   |
| Marvell Technology Group              | 1        | 1.45%   |
| Linksys                               | 1        | 1.45%   |
| Broadcom Limited                      | 1        | 1.45%   |
| ASIX Electronics                      | 1        | 1.45%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.45%   |
| 3Com                                  | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 20       | 27.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 5.41%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 4.05%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 2.7%    |
| ZTE WCDMA MSM ZTE BLADE A530                                                  | 1        | 1.35%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                       | 1        | 1.35%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 1.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.35%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 1.35%   |
| Realtek 802.11ac WLAN Adapter                                                 | 1        | 1.35%   |
| Realtek 802.11ac NIC                                                          | 1        | 1.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.35%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 1        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1        | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 1.35%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 1.35%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 1.35%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.35%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 1        | 1.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.35%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                           | 1        | 1.35%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.35%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 1.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 1.35%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 1.35%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1        | 1.35%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 1.35%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                       | 1        | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 5        | 20%     |
| Ralink Technology                     | 4        | 16%     |
| Ralink                                | 3        | 12%     |
| Qualcomm Atheros                      | 2        | 8%      |
| ASUSTek Computer                      | 2        | 8%      |
| TP-Link                               | 1        | 4%      |
| Qualcomm Atheros Communications       | 1        | 4%      |
| Microsoft                             | 1        | 4%      |
| MediaTek                              | 1        | 4%      |
| Linksys                               | 1        | 4%      |
| Intel                                 | 1        | 4%      |
| Broadcom Limited                      | 1        | 4%      |
| Broadcom                              | 1        | 4%      |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                                        | 3        | 12%     |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1        | 4%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1        | 4%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 4%      |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1        | 4%      |
| Realtek 802.11ac WLAN Adapter                                                                          | 1        | 4%      |
| Realtek 802.11ac NIC                                                                                   | 1        | 4%      |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1        | 4%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 4%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 4%      |
| Ralink RT2561/RT61 802.11g PCI                                                                         | 1        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 4%      |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 4%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 4%      |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                | 1        | 4%      |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                                                                    | 1        | 4%      |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1        | 4%      |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1        | 4%      |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1        | 4%      |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                                        | 1        | 4%      |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 25       | 51.02%  |
| Intel                             | 10       | 20.41%  |
| Broadcom                          | 5        | 10.2%   |
| Nvidia                            | 2        | 4.08%   |
| ZTE WCDMA Technologies MSM        | 1        | 2.04%   |
| Sundance Technology Inc / IC Plus | 1        | 2.04%   |
| Samsung Electronics               | 1        | 2.04%   |
| Qualcomm Atheros                  | 1        | 2.04%   |
| Marvell Technology Group          | 1        | 2.04%   |
| ASIX Electronics                  | 1        | 2.04%   |
| 3Com                              | 1        | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 20       | 40.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 8.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 8.16%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 4.08%   |
| ZTE WCDMA MSM ZTE BLADE A530                                                  | 1        | 2.04%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 2.04%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 2.04%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 2.04%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 2.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 2.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 2.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 2.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1        | 2.04%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 2.04%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 2.04%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 64.18%  |
| WiFi     | 24       | 35.82%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 67.39%  |
| WiFi     | 15       | 32.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 70.45%  |
| 2     | 11       | 25%     |
| 4     | 1        | 2.27%   |
| 3     | 1        | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 81.82%  |
| Yes  | 8        | 18.18%  |

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
| Intel                 | 28       | 44.44%  |
| AMD                   | 17       | 26.98%  |
| Nvidia                | 10       | 15.87%  |
| C-Media Electronics   | 2        | 3.17%   |
| Texas Instruments     | 1        | 1.59%   |
| Realtek Semiconductor | 1        | 1.59%   |
| Logitech              | 1        | 1.59%   |
| JMTek                 | 1        | 1.59%   |
| Ensoniq               | 1        | 1.59%   |
| Creative Labs         | 1        | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 9.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7        | 9.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 7.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 5.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 4.23%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 2.82%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 2.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 2.82%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1        | 1.41%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 1.41%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 1.41%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1        | 1.41%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 1.41%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 1.41%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1        | 1.41%   |
| Logitech Wireless Headset                                                                         | 1        | 1.41%   |
| JMTek LCS USB Audio                                                                               | 1        | 1.41%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.41%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.41%   |
| Ensoniq 5880B / Creative Labs CT5880                                                              | 1        | 1.41%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.41%   |
| C-Media Electronics Multimedia Headset [Gigaware by Ignition L.P.]                                | 1        | 1.41%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1        | 1.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.41%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1        | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 33.33%  |
| Kingston            | 6        | 14.29%  |
| Samsung Electronics | 5        | 11.9%   |
| Micron Technology   | 4        | 9.52%   |
| SK hynix            | 2        | 4.76%   |
| Corsair             | 2        | 4.76%   |
| Unknown             | 2        | 4.76%   |
| Qumo                | 1        | 2.38%   |
| GeIL                | 1        | 2.38%   |
| Avant               | 1        | 2.38%   |
| 2C0C1121390963FE    | 1        | 2.38%   |
| 2C0C1121390963FD    | 1        | 2.38%   |
| 2C0C1121390963F9    | 1        | 2.38%   |
| 2C0C1121390963F8    | 1        | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Unknown                                                             | 2        | 4.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1        | 2.33%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                             | 1        | 2.33%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                            | 1        | 2.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1        | 2.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1        | 2.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                          | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                          | 1        | 2.33%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                              | 1        | 2.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1        | 2.33%   |
| Unknown RAM Module 1024MB DIMM DDR2                                 | 1        | 2.33%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                          | 1        | 2.33%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 1        | 2.33%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s                | 1        | 2.33%   |
| Samsung RAM Module 4GB DIMM DDR3 1067MT/s                           | 1        | 2.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                 | 1        | 2.33%   |
| Samsung RAM M378B2873FH0-CH9 1GB DIMM DDR3 1333MT/s                 | 1        | 2.33%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                 | 1        | 2.33%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM SDRAM                        | 1        | 2.33%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                           | 1        | 2.33%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                            | 1        | 2.33%   |
| Micron RAM 8HTF12864AY-800G1 1GB DIMM DDR2 800MT/s                  | 1        | 2.33%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                | 1        | 2.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB DIMM DDR3 1600MT/s                 | 1        | 2.33%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                           | 1        | 2.33%   |
| Kingston RAM Module 1024MB DIMM DDR2 800MT/s                        | 1        | 2.33%   |
| Kingston RAM KTW149-ELD 1024MB DIMM DDR3 1333MT/s                   | 1        | 2.33%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s                 | 1        | 2.33%   |
| Kingston RAM 99U5474-020.A00LF 4096MB DIMM DDR3 1333MT/s            | 1        | 2.33%   |
| Kingston RAM 9905458-009.A00LF 2GB DIMM DDR3 1600MT/s               | 1        | 2.33%   |
| GeIL RAM CL16-20-20 D4-3200 8192MB DIMM DDR4 3200MT/s               | 1        | 2.33%   |
| Corsair RAM CMW32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s              | 1        | 2.33%   |
| Corsair RAM CML8GX3M2A1600C9W 4GB DIMM DDR3 2133MT/s                | 1        | 2.33%   |
| Avant RAM Module 1GB DIMM DDR2 667MT/s                              | 1        | 2.33%   |
| 2C0C1121390963FE RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.33%   |
| 2C0C1121390963FD RAM 36HTF25672F667G1N8 2048MB FB-DIMM DDR2 667MT/s | 1        | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 26.47%  |
| DDR2    | 9        | 26.47%  |
| SDRAM   | 5        | 14.71%  |
| DDR4    | 5        | 14.71%  |
| Unknown | 4        | 11.76%  |
| DDR     | 2        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 32       | 94.12%  |
| SODIMM  | 1        | 2.94%   |
| FB-DIMM | 1        | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 13       | 36.11%  |
| 4096  | 9        | 25%     |
| 1024  | 7        | 19.44%  |
| 8192  | 5        | 13.89%  |
| 16384 | 2        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 17.14%  |
| 1600    | 5        | 14.29%  |
| 1333    | 5        | 14.29%  |
| 3200    | 4        | 11.43%  |
| 800     | 4        | 11.43%  |
| 667     | 2        | 5.71%   |
| 49926   | 1        | 2.86%   |
| 19791   | 1        | 2.86%   |
| 3500    | 1        | 2.86%   |
| 2133    | 1        | 2.86%   |
| 1639    | 1        | 2.86%   |
| 1067    | 1        | 2.86%   |
| 1033    | 1        | 2.86%   |
| 400     | 1        | 2.86%   |
| 133     | 1        | 2.86%   |

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


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Mustek Systems  | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1        | 50%     |
| HP ScanJet 5200c                   | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Chicony Electronics         | 3        | 33.33%  |
| Z-Star Microelectronics     | 1        | 11.11%  |
| Microsoft                   | 1        | 11.11%  |
| Jieli Technology            | 1        | 11.11%  |
| Hopewin Electronic Material | 1        | 11.11%  |
| Hewlett-Packard             | 1        | 11.11%  |
| Generalplus Technology      | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam               | 2        | 22.22%  |
| Z-Star Venus USB2.0 Camera                          | 1        | 11.11%  |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 11.11%  |
| Jieli USB PHY 2.0                                   | 1        | 11.11%  |
| Hopewin Electronic Material Integrated RGB Camera   | 1        | 11.11%  |
| HP Webcam HD 2300                                   | 1        | 11.11%  |
| Generalplus GENERAL WEBCAM                          | 1        | 11.11%  |
| Chicony HP Webcam                                   | 1        | 11.11%  |

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
| 0     | 39       | 88.64%  |
| 1     | 5        | 11.36%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 3        | 60%     |
| Unassigned class | 1        | 20%     |
| Net/wireless     | 1        | 20%     |

