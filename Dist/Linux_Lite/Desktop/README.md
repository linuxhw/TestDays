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

Total: 77

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 3740 NOK                    | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| AMI           | Intel                       | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MSI           | H110M PRO-VH                | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| ASUSTek       | B85M-G                      | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| ASRock        | B550M-ITX/ac                | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
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
| Linux Lite 5.8 | 12       | 23.53%  |
| Linux Lite 5.6 | 7        | 13.73%  |
| Linux Lite 5.2 | 7        | 13.73%  |
| Linux Lite 5.0 | 7        | 13.73%  |
| Linux Lite 5.4 | 6        | 11.76%  |
| Linux Lite 6.4 | 4        | 7.84%   |
| Linux Lite 6.2 | 3        | 5.88%   |
| Linux Lite 6.0 | 2        | 3.92%   |
| Linux Lite 3.8 | 2        | 3.92%   |
| Linux Lite 4.6 | 1        | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Lite | 51       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.4.0-96-generic     | 3        | 5.77%   |
| 5.4.0-91-generic     | 3        | 5.77%   |
| 5.4.0-80-generic     | 2        | 3.85%   |
| 5.4.0-54-generic     | 2        | 3.85%   |
| 5.4.0-48-generic     | 2        | 3.85%   |
| 5.4.0-42-generic     | 2        | 3.85%   |
| 5.4.0-113-generic    | 2        | 3.85%   |
| 5.4.0-104-generic    | 2        | 3.85%   |
| 5.15.0-71-generic    | 2        | 3.85%   |
| 5.15.0-58-generic    | 2        | 3.85%   |
| 4.4.0-112-generic    | 2        | 3.85%   |
| 6.0.0-1.linuxlite    | 1        | 1.92%   |
| 5.9.0                | 1        | 1.92%   |
| 5.4.0-99-generic     | 1        | 1.92%   |
| 5.4.0-88-generic     | 1        | 1.92%   |
| 5.4.0-72-generic     | 1        | 1.92%   |
| 5.4.0-70-generic     | 1        | 1.92%   |
| 5.4.0-58-generic     | 1        | 1.92%   |
| 5.4.0-52-generic     | 1        | 1.92%   |
| 5.4.0-45-generic     | 1        | 1.92%   |
| 5.4.0-37-generic     | 1        | 1.92%   |
| 5.4.0-33-generic     | 1        | 1.92%   |
| 5.4.0-144-generic    | 1        | 1.92%   |
| 5.4.0-137-generic    | 1        | 1.92%   |
| 5.4.0-133-generic    | 1        | 1.92%   |
| 5.4.0-132-generic    | 1        | 1.92%   |
| 5.4.0-131-generic    | 1        | 1.92%   |
| 5.4.0-110-generic    | 1        | 1.92%   |
| 5.4.0-109-generic    | 1        | 1.92%   |
| 5.4.0-107-generic    | 1        | 1.92%   |
| 5.4.0-105-generic    | 1        | 1.92%   |
| 5.15.0-75-generic    | 1        | 1.92%   |
| 5.15.0-73-generic    | 1        | 1.92%   |
| 5.15.0-69-generic    | 1        | 1.92%   |
| 5.15.0-46-generic    | 1        | 1.92%   |
| 5.15.0-33-generic    | 1        | 1.92%   |
| 5.15.0               | 1        | 1.92%   |
| 5.13.0-44-lowlatency | 1        | 1.92%   |
| 4.15.0-147-generic   | 1        | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 36       | 69.23%  |
| 5.15.0  | 10       | 19.23%  |
| 4.4.0   | 2        | 3.85%   |
| 6.0.0   | 1        | 1.92%   |
| 5.9.0   | 1        | 1.92%   |
| 5.13.0  | 1        | 1.92%   |
| 4.15.0  | 1        | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 36       | 69.23%  |
| 5.15    | 10       | 19.23%  |
| 4.4     | 2        | 3.85%   |
| 6.0     | 1        | 1.92%   |
| 5.9     | 1        | 1.92%   |
| 5.13    | 1        | 1.92%   |
| 4.15    | 1        | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 96.08%  |
| i686   | 2        | 3.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 40       | 78.43%  |
| GNOME | 11       | 21.57%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 51       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 32       | 62.75%  |
| TDM     | 10       | 19.61%  |
| Unknown | 9        | 17.65%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 31.37%  |
| pt_BR | 5        | 9.8%    |
| es_MX | 4        | 7.84%   |
| de_DE | 4        | 7.84%   |
| en_CA | 3        | 5.88%   |
| pl_PL | 2        | 3.92%   |
| fr_FR | 2        | 3.92%   |
| es_ES | 2        | 3.92%   |
| en_GB | 2        | 3.92%   |
| ru_UA | 1        | 1.96%   |
| nl_NL | 1        | 1.96%   |
| hu_HU | 1        | 1.96%   |
| fr_CA | 1        | 1.96%   |
| es_CL | 1        | 1.96%   |
| es_AR | 1        | 1.96%   |
| en_NZ | 1        | 1.96%   |
| en_IE | 1        | 1.96%   |
| da_DK | 1        | 1.96%   |
| C     | 1        | 1.96%   |
| ar_SA | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 37       | 72.55%  |
| EFI  | 14       | 27.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 90.2%   |
| Overlay | 3        | 5.88%   |
| Tmpfs   | 1        | 1.96%   |
| Ext3    | 1        | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 20       | 39.22%  |
| GPT     | 18       | 35.29%  |
| Unknown | 13       | 25.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 76.47%  |
| Yes       | 12       | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 66.67%  |
| Yes       | 17       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 15.69%  |
| Lenovo              | 6        | 11.76%  |
| MSI                 | 5        | 9.8%    |
| ASUSTek Computer    | 5        | 9.8%    |
| Gigabyte Technology | 3        | 5.88%   |
| ASRock              | 3        | 5.88%   |
| Pegatron            | 2        | 3.92%   |
| Intel               | 2        | 3.92%   |
| Foxconn             | 2        | 3.92%   |
| Dell                | 2        | 3.92%   |
| Acer                | 2        | 3.92%   |
| Packard Bell        | 1        | 1.96%   |
| Minix               | 1        | 1.96%   |
| Jetway              | 1        | 1.96%   |
| Fujitsu Siemens     | 1        | 1.96%   |
| Fujitsu             | 1        | 1.96%   |
| EVGA                | 1        | 1.96%   |
| Braview             | 1        | 1.96%   |
| Biostar             | 1        | 1.96%   |
| Apple               | 1        | 1.96%   |
| AMI                 | 1        | 1.96%   |
| ABIT                | 1        | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7758                            | 2        | 3.92%   |
| Pegatron 520-1135la                    | 1        | 1.96%   |
| Pegatron 520-1030a                     | 1        | 1.96%   |
| Packard Bell ISTART D2314              | 1        | 1.96%   |
| MSI MS-7C95                            | 1        | 1.96%   |
| MSI MS-7996                            | 1        | 1.96%   |
| MSI FZ079AA-ABF a6625fr                | 1        | 1.96%   |
| Minix Z83-4                            | 1        | 1.96%   |
| Lenovo ThinkStation P320 30BH000BFR    | 1        | 1.96%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE  | 1        | 1.96%   |
| Lenovo ThinkCentre M91p 4524RS6        | 1        | 1.96%   |
| Lenovo ThinkCentre M91p 4518E2M        | 1        | 1.96%   |
| Lenovo ThinkCentre A55 9265BL7         | 1        | 1.96%   |
| Lenovo H505S 10107                     | 1        | 1.96%   |
| Jetway I61MG4                          | 1        | 1.96%   |
| Intel H61M-S1                          | 1        | 1.96%   |
| Intel DG31PR AAD97573-300              | 1        | 1.96%   |
| HP Z400 Workstation                    | 1        | 1.96%   |
| HP xw8600 Workstation                  | 1        | 1.96%   |
| HP t5000 series                        | 1        | 1.96%   |
| HP rp5800                              | 1        | 1.96%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 1.96%   |
| HP Compaq dc5800 Small Form Factor     | 1        | 1.96%   |
| HP Compaq 6005 Pro SFF PC              | 1        | 1.96%   |
| HP 200-5320br                          | 1        | 1.96%   |
| Gigabyte X570 AORUS MASTER             | 1        | 1.96%   |
| Gigabyte GA-E350N                      | 1        | 1.96%   |
| Gigabyte B450M DS3H                    | 1        | 1.96%   |
| Fujitsu Siemens ESPRIMO P5730          | 1        | 1.96%   |
| Fujitsu ESPRIMO P2560                  | 1        | 1.96%   |
| Foxconn 500B Microtower                | 1        | 1.96%   |
| Foxconn 45CMX/45GMX/45CMX-K            | 1        | 1.96%   |
| EVGA X58 SLI FTW3 Tylersburg           | 1        | 1.96%   |
| Dell OptiPlex 790                      | 1        | 1.96%   |
| Dell Inspiron 560                      | 1        | 1.96%   |
| Braview BRW-BSWI-D2                    | 1        | 1.96%   |
| Biostar G41D3C                         | 1        | 1.96%   |
| ASUS TUF B450-PLUS GAMING              | 1        | 1.96%   |
| ASUS TERRA_PC                          | 1        | 1.96%   |
| ASUS M5A78L-M LX PLUS                  | 1        | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lenovo ThinkCentre      | 4        | 7.84%   |
| HP Compaq               | 3        | 5.88%   |
| MSI MS-7758             | 2        | 3.92%   |
| Pegatron 520-1135la     | 1        | 1.96%   |
| Pegatron 520-1030a      | 1        | 1.96%   |
| Packard Bell ISTART     | 1        | 1.96%   |
| MSI MS-7C95             | 1        | 1.96%   |
| MSI MS-7996             | 1        | 1.96%   |
| MSI FZ079AA-ABF         | 1        | 1.96%   |
| Minix Z83-4             | 1        | 1.96%   |
| Lenovo ThinkStation     | 1        | 1.96%   |
| Lenovo H505S            | 1        | 1.96%   |
| Jetway I61MG4           | 1        | 1.96%   |
| Intel H61M-S1           | 1        | 1.96%   |
| Intel DG31PR            | 1        | 1.96%   |
| HP Z400                 | 1        | 1.96%   |
| HP xw8600               | 1        | 1.96%   |
| HP t5000                | 1        | 1.96%   |
| HP rp5800               | 1        | 1.96%   |
| HP 200-5320br           | 1        | 1.96%   |
| Gigabyte X570           | 1        | 1.96%   |
| Gigabyte GA-E350N       | 1        | 1.96%   |
| Gigabyte B450M          | 1        | 1.96%   |
| Fujitsu Siemens ESPRIMO | 1        | 1.96%   |
| Fujitsu ESPRIMO         | 1        | 1.96%   |
| Foxconn 500B            | 1        | 1.96%   |
| Foxconn 45CMX           | 1        | 1.96%   |
| EVGA X58                | 1        | 1.96%   |
| Dell OptiPlex           | 1        | 1.96%   |
| Dell Inspiron           | 1        | 1.96%   |
| Braview BRW-BSWI-D2     | 1        | 1.96%   |
| Biostar G41D3C          | 1        | 1.96%   |
| ASUS TUF                | 1        | 1.96%   |
| ASUS TERRA              | 1        | 1.96%   |
| ASUS M5A78L-M           | 1        | 1.96%   |
| ASUS M5A78L             | 1        | 1.96%   |
| ASUS M4N72-E            | 1        | 1.96%   |
| ASRock N68C-S           | 1        | 1.96%   |
| ASRock H61M-VG3         | 1        | 1.96%   |
| ASRock 5600G            | 1        | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 10       | 19.61%  |
| 2008 | 8        | 15.69%  |
| 2012 | 7        | 13.73%  |
| 2010 | 6        | 11.76%  |
| 2007 | 4        | 7.84%   |
| 2018 | 3        | 5.88%   |
| 2021 | 2        | 3.92%   |
| 2020 | 2        | 3.92%   |
| 2009 | 2        | 3.92%   |
| 2023 | 1        | 1.96%   |
| 2022 | 1        | 1.96%   |
| 2019 | 1        | 1.96%   |
| 2017 | 1        | 1.96%   |
| 2016 | 1        | 1.96%   |
| 2015 | 1        | 1.96%   |
| 2013 | 1        | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 51       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 98.04%  |
| Enabled  | 1        | 1.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 13       | 25.49%  |
| 4.01-8.0   | 9        | 17.65%  |
| 1.01-2.0   | 8        | 15.69%  |
| 8.01-16.0  | 8        | 15.69%  |
| 16.01-24.0 | 6        | 11.76%  |
| 32.01-64.0 | 5        | 9.8%    |
| 24.01-32.0 | 1        | 1.96%   |
| 2.01-3.0   | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 23       | 45.1%   |
| 2.01-3.0  | 9        | 17.65%  |
| 4.01-8.0  | 7        | 13.73%  |
| 0.51-1.0  | 6        | 11.76%  |
| 3.01-4.0  | 5        | 9.8%    |
| 8.01-16.0 | 1        | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 50.98%  |
| 2      | 16       | 31.37%  |
| 3      | 5        | 9.8%    |
| 0      | 2        | 3.92%   |
| 5      | 1        | 1.96%   |
| 4      | 1        | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 50.98%  |
| No        | 25       | 49.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 98.04%  |
| No        | 1        | 1.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 54.9%   |
| No        | 23       | 45.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 80.39%  |
| Yes       | 10       | 19.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 17.65%  |
| Brazil       | 7        | 13.73%  |
| Canada       | 5        | 9.8%    |
| Mexico       | 4        | 7.84%   |
| Germany      | 4        | 7.84%   |
| Poland       | 3        | 5.88%   |
| Peru         | 3        | 5.88%   |
| UK           | 2        | 3.92%   |
| France       | 2        | 3.92%   |
| Ukraine      | 1        | 1.96%   |
| Spain        | 1        | 1.96%   |
| Saudi Arabia | 1        | 1.96%   |
| New Zealand  | 1        | 1.96%   |
| Netherlands  | 1        | 1.96%   |
| Malaysia     | 1        | 1.96%   |
| Ireland      | 1        | 1.96%   |
| Hungary      | 1        | 1.96%   |
| Greenland    | 1        | 1.96%   |
| Chile        | 1        | 1.96%   |
| Australia    | 1        | 1.96%   |
| Argentina    | 1        | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Ottawa                   | 2        | 3.92%   |
| Mexico City              | 2        | 3.92%   |
| Lima                     | 2        | 3.92%   |
| Würzburg                | 1        | 1.96%   |
| Wellington               | 1        | 1.96%   |
| Waterbury                | 1        | 1.96%   |
| Warsaw                   | 1        | 1.96%   |
| Vancouver                | 1        | 1.96%   |
| Trujillo                 | 1        | 1.96%   |
| Toronto                  | 1        | 1.96%   |
| Thetford-Mines           | 1        | 1.96%   |
| Sao Paulo                | 1        | 1.96%   |
| Rio de Janeiro           | 1        | 1.96%   |
| Purmerend                | 1        | 1.96%   |
| Porto Velho              | 1        | 1.96%   |
| Porto Alegre             | 1        | 1.96%   |
| Pabianice                | 1        | 1.96%   |
| Osasco                   | 1        | 1.96%   |
| Oldenburg                | 1        | 1.96%   |
| Neuquén                 | 1        | 1.96%   |
| Naugatuck                | 1        | 1.96%   |
| Nashville                | 1        | 1.96%   |
| Narbonne                 | 1        | 1.96%   |
| Munster                  | 1        | 1.96%   |
| Makkah                   | 1        | 1.96%   |
| Maineville               | 1        | 1.96%   |
| Lublin                   | 1        | 1.96%   |
| Long Seridan             | 1        | 1.96%   |
| Kyiv                     | 1        | 1.96%   |
| Ilulissat                | 1        | 1.96%   |
| Fortin de las Flores     | 1        | 1.96%   |
| Enfield                  | 1        | 1.96%   |
| Dublin                   | 1        | 1.96%   |
| Dover                    | 1        | 1.96%   |
| Donostia / San Sebastian | 1        | 1.96%   |
| Cuauhtemoc               | 1        | 1.96%   |
| Craigavon                | 1        | 1.96%   |
| Conchali                 | 1        | 1.96%   |
| Columbus                 | 1        | 1.96%   |
| Cibakhaza                | 1        | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 24.32%  |
| WDC                 | 15       | 20     | 20.27%  |
| Samsung Electronics | 9        | 9      | 12.16%  |
| Toshiba             | 3        | 3      | 4.05%   |
| SanDisk             | 3        | 3      | 4.05%   |
| Kingston            | 3        | 5      | 4.05%   |
| Crucial             | 3        | 3      | 4.05%   |
| Unknown             | 2        | 2      | 2.7%    |
| Hitachi             | 2        | 2      | 2.7%    |
| China               | 2        | 2      | 2.7%    |
| SK hynix            | 1        | 1      | 1.35%   |
| PNY                 | 1        | 1      | 1.35%   |
| Phison              | 1        | 1      | 1.35%   |
| OCZ                 | 1        | 1      | 1.35%   |
| Maxtor              | 1        | 1      | 1.35%   |
| Mass                | 1        | 1      | 1.35%   |
| Intenso             | 1        | 1      | 1.35%   |
| HPE                 | 1        | 1      | 1.35%   |
| Hewlett-Packard     | 1        | 1      | 1.35%   |
| Goodram             | 1        | 1      | 1.35%   |
| Gigabyte Technology | 1        | 1      | 1.35%   |
| Fujitsu             | 1        | 1      | 1.35%   |
| Fanxiang            | 1        | 2      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 3        | 3.7%    |
| WDC WD5000AAKX-001CA0 500GB            | 2        | 2.47%   |
| SanDisk SDSSDA240G 240GB               | 2        | 2.47%   |
| WDC WDS250G2B0A 250GB SSD              | 1        | 1.23%   |
| WDC WDS120G2G0A-00JH30 128GB SSD       | 1        | 1.23%   |
| WDC WD800JD-60LSA0 80GB                | 1        | 1.23%   |
| WDC WD5000AAKX-003CA0 500GB            | 1        | 1.23%   |
| WDC WD5000AAKS-60WWPA0 500GB           | 1        | 1.23%   |
| WDC WD5000AADS-56S9B0 500GB            | 1        | 1.23%   |
| WDC WD5000AADS-00S9B0 500GB            | 1        | 1.23%   |
| WDC WD5000AACS-00G8B1 500GB            | 1        | 1.23%   |
| WDC WD20PURX-64PFUY0 2TB               | 1        | 1.23%   |
| WDC WD2005FBYZ-01YCBB2 2TB             | 1        | 1.23%   |
| WDC WD10JPVX-75JC3T0 1TB               | 1        | 1.23%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1        | 1.23%   |
| WDC WD10EZEX-07WN4A0 1TB               | 1        | 1.23%   |
| WDC WD10EADS-00L5B1 1TB                | 1        | 1.23%   |
| WDC WD1003FBYX-01Y7B1 1TB              | 1        | 1.23%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB     | 1        | 1.23%   |
| Unknown MMC Card  64GB                 | 1        | 1.23%   |
| Unknown MMC Card  32GB                 | 1        | 1.23%   |
| Toshiba MK1059GSM 1TB                  | 1        | 1.23%   |
| Toshiba HDWD110 1TB                    | 1        | 1.23%   |
| Toshiba DT01ACA100 1TB                 | 1        | 1.23%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB | 1        | 1.23%   |
| Seagate ST980811AS 80GB                | 1        | 1.23%   |
| Seagate ST9500325AS 500GB              | 1        | 1.23%   |
| Seagate ST500LM030-1RK17D 500GB        | 1        | 1.23%   |
| Seagate ST500DM002-1BC142 500GB        | 1        | 1.23%   |
| Seagate ST3750640NS 752GB              | 1        | 1.23%   |
| Seagate ST3750528AS 752GB              | 1        | 1.23%   |
| Seagate ST3500418AS 500GB              | 1        | 1.23%   |
| Seagate ST3320620A 320GB               | 1        | 1.23%   |
| Seagate ST3250310AS 250GB              | 1        | 1.23%   |
| Seagate ST320LM001 HN-M320MBB 320GB    | 1        | 1.23%   |
| Seagate ST3120026A 120GB               | 1        | 1.23%   |
| Seagate ST2000DL003-9VT166 2TB         | 1        | 1.23%   |
| Seagate ST1000VM002-1ET162 1TB         | 1        | 1.23%   |
| Seagate ST1000LM048-2E7172 1TB         | 1        | 1.23%   |
| Seagate ST1000LM010-9YH146 1TB         | 1        | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 45%     |
| WDC                 | 13       | 15     | 32.5%   |
| Toshiba             | 3        | 3      | 7.5%    |
| Hitachi             | 2        | 2      | 5%      |
| Samsung Electronics | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 1      | 2.5%    |
| HPE                 | 1        | 1      | 2.5%    |
| Fujitsu             | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 6      | 24%     |
| SanDisk             | 3        | 3      | 12%     |
| Crucial             | 3        | 3      | 12%     |
| WDC                 | 2        | 3      | 8%      |
| Kingston            | 2        | 4      | 8%      |
| China               | 2        | 2      | 8%      |
| PNY                 | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Hewlett-Packard     | 1        | 1      | 4%      |
| Goodram             | 1        | 1      | 4%      |
| Gigabyte Technology | 1        | 1      | 4%      |
| Fanxiang            | 1        | 2      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 34       | 44     | 50%     |
| SSD     | 24       | 29     | 35.29%  |
| NVMe    | 6        | 7      | 8.82%   |
| MMC     | 2        | 2      | 2.94%   |
| Unknown | 2        | 2      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 46       | 72     | 80.7%   |
| NVMe | 6        | 7      | 10.53%  |
| SAS  | 3        | 3      | 5.26%   |
| MMC  | 2        | 2      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 52     | 66.67%  |
| 0.51-1.0   | 16       | 17     | 28.07%  |
| 1.01-2.0   | 3        | 4      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 31.37%  |
| 251-500        | 8        | 15.69%  |
| 51-100         | 8        | 15.69%  |
| 501-1000       | 6        | 11.76%  |
| 1001-2000      | 4        | 7.84%   |
| More than 3000 | 3        | 5.88%   |
| 21-50          | 3        | 5.88%   |
| 1-20           | 2        | 3.92%   |
| 2001-3000      | 1        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 17       | 33.33%  |
| 21-50     | 11       | 21.57%  |
| 101-250   | 7        | 13.73%  |
| 51-100    | 7        | 13.73%  |
| 501-1000  | 4        | 7.84%   |
| 251-500   | 3        | 5.88%   |
| 2001-3000 | 1        | 1.96%   |
| 1001-2000 | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD800JD-60LSA0 80GB       | 1        | 1      | 10%     |
| WDC WD5000AAKX-001CA0 500GB   | 1        | 1      | 10%     |
| WDC WD5000AAKS-60WWPA0 500GB  | 1        | 1      | 10%     |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 10%     |
| Seagate ST980811AS 80GB       | 1        | 1      | 10%     |
| Seagate ST9500325AS 500GB     | 1        | 1      | 10%     |
| Seagate ST3750528AS 752GB     | 1        | 1      | 10%     |
| Seagate ST3120026A 120GB      | 1        | 1      | 10%     |
| Hitachi HDS722020ALA330 2TB   | 1        | 1      | 10%     |
| Hitachi HDS721616PLA380 160GB | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 40%     |
| WDC     | 3        | 3      | 30%     |
| Hitachi | 2        | 2      | 20%     |
| Toshiba | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 40%     |
| WDC     | 3        | 3      | 30%     |
| Hitachi | 2        | 2      | 20%     |
| Toshiba | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 10     | 100%    |

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
| Works    | 26       | 40     | 48.15%  |
| Detected | 20       | 34     | 37.04%  |
| Malfunc  | 8        | 10     | 14.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 34       | 56.67%  |
| AMD                         | 13       | 21.67%  |
| Nvidia                      | 3        | 5%      |
| Samsung Electronics         | 2        | 3.33%   |
| SK hynix                    | 1        | 1.67%   |
| SanDisk                     | 1        | 1.67%   |
| Phison Electronics          | 1        | 1.67%   |
| Marvell Technology Group    | 1        | 1.67%   |
| LSI Logic / Symbios Logic   | 1        | 1.67%   |
| Kingston Technology Company | 1        | 1.67%   |
| JMicron Technology          | 1        | 1.67%   |
| Broadcom / LSI              | 1        | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.95%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 5.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 4.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.38%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.38%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.38%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.38%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 2.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 1.19%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.19%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.19%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 1.19%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 1.19%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 1.19%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.19%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.19%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 1.19%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.19%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.19%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                   | 1        | 1.19%   |
| Kingston Company NVMe Controller                                                        | 1        | 1.19%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.19%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.19%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 50%     |
| IDE  | 25       | 37.88%  |
| NVMe | 6        | 9.09%   |
| RAID | 1        | 1.52%   |
| SCSI | 1        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 70.59%  |
| AMD    | 15       | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 5.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 3.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 3.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 3.92%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 1.96%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.96%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 1.96%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 1.96%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.96%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.96%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.96%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1        | 1.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.96%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.96%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1        | 1.96%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.96%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.96%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 1.96%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 1.96%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.96%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.96%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.96%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.96%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.96%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 1.96%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 1.96%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 1.96%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1        | 1.96%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 1        | 1.96%   |
| Intel Celeron CPU G540 @ 2.50GHz            | 1        | 1.96%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 1.96%   |
| Intel 12th Gen Core i3-12100                | 1        | 1.96%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 1        | 1.96%   |
| AMD Sempron 145 Processor                   | 1        | 1.96%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.96%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 1.96%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 1.96%   |
| AMD Phenom II X2 B55 Processor              | 1        | 1.96%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 11.76%  |
| Intel Core i3           | 5        | 9.8%    |
| Intel Xeon              | 4        | 7.84%   |
| Intel Pentium Dual-Core | 4        | 7.84%   |
| Intel Core 2 Duo        | 4        | 7.84%   |
| Intel Core i7           | 3        | 5.88%   |
| Intel Celeron           | 3        | 5.88%   |
| AMD Ryzen 5             | 3        | 5.88%   |
| Intel Pentium Dual      | 2        | 3.92%   |
| AMD E                   | 2        | 3.92%   |
| AMD Athlon II X2        | 2        | 3.92%   |
| AMD A6                  | 2        | 3.92%   |
| Other                   | 1        | 1.96%   |
| Intel Pentium D         | 1        | 1.96%   |
| Intel Pentium           | 1        | 1.96%   |
| Intel Core 2 Quad       | 1        | 1.96%   |
| Intel Atom              | 1        | 1.96%   |
| AMD Turion 64 X2 Mobile | 1        | 1.96%   |
| AMD Sempron             | 1        | 1.96%   |
| AMD Ryzen 9             | 1        | 1.96%   |
| AMD Ryzen 3             | 1        | 1.96%   |
| AMD Phenom II X2        | 1        | 1.96%   |
| AMD FX                  | 1        | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 50.98%  |
| 4      | 15       | 29.41%  |
| 6      | 6        | 11.76%  |
| 1      | 2        | 3.92%   |
| 12     | 1        | 1.96%   |
| 8      | 1        | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 96.08%  |
| 2      | 2        | 3.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 68.63%  |
| 2      | 16       | 31.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 9        | 17.65%  |
| 0x206a7    | 7        | 13.73%  |
| Unknown    | 7        | 13.73%  |
| 0x010000c8 | 3        | 5.88%   |
| 0x406c4    | 2        | 3.92%   |
| 0x206c2    | 2        | 3.92%   |
| 0x10676    | 2        | 3.92%   |
| 0xf64      | 1        | 1.96%   |
| 0xa0653    | 1        | 1.96%   |
| 0x6fd      | 1        | 1.96%   |
| 0x6fb      | 1        | 1.96%   |
| 0x6f6      | 1        | 1.96%   |
| 0x506e3    | 1        | 1.96%   |
| 0x506c9    | 1        | 1.96%   |
| 0x306c3    | 1        | 1.96%   |
| 0x20655    | 1        | 1.96%   |
| 0x0a50000d | 1        | 1.96%   |
| 0x0a50000c | 1        | 1.96%   |
| 0x08701013 | 1        | 1.96%   |
| 0x0810100b | 1        | 1.96%   |
| 0x0800820d | 1        | 1.96%   |
| 0x06000852 | 1        | 1.96%   |
| 0x05000119 | 1        | 1.96%   |
| 0x05000029 | 1        | 1.96%   |
| 0x03000027 | 1        | 1.96%   |
| 0x010000c7 | 1        | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 11       | 21.57%  |
| SandyBridge | 7        | 13.73%  |
| K10         | 4        | 7.84%   |
| Core        | 4        | 7.84%   |
| Westmere    | 3        | 5.88%   |
| Zen 3       | 2        | 3.92%   |
| Silvermont  | 2        | 3.92%   |
| K10 Llano   | 2        | 3.92%   |
| IvyBridge   | 2        | 3.92%   |
| Bobcat      | 2        | 3.92%   |
| Zen+        | 1        | 1.96%   |
| Zen 2       | 1        | 1.96%   |
| Zen         | 1        | 1.96%   |
| Skylake     | 1        | 1.96%   |
| Piledriver  | 1        | 1.96%   |
| NetBurst    | 1        | 1.96%   |
| KabyLake    | 1        | 1.96%   |
| K8 Hammer   | 1        | 1.96%   |
| Haswell     | 1        | 1.96%   |
| Goldmont    | 1        | 1.96%   |
| CometLake   | 1        | 1.96%   |
| Unknown     | 1        | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 37.25%  |
| AMD    | 17       | 33.33%  |
| Nvidia | 15       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 7.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 5.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 5.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.77%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 3.77%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 1.89%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 1.89%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.89%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 1.89%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 1.89%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 1.89%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 1.89%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1        | 1.89%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1        | 1.89%   |
| Nvidia C73 [GeForce 7050 / nForce 610i]                                                  | 1        | 1.89%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.89%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.89%   |
| Intel HD Graphics 530                                                                    | 1        | 1.89%   |
| Intel HD Graphics 500                                                                    | 1        | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.89%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 1        | 1.89%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1        | 1.89%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.89%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.89%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1        | 1.89%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1        | 1.89%   |
| AMD Sumo [Radeon HD 6530D]                                                               | 1        | 1.89%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 1        | 1.89%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 1.89%   |
| AMD RS780L [Radeon 3000]                                                                 | 1        | 1.89%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1        | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.89%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                             | 1        | 1.89%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 19       | 37.25%  |
| 1 x Nvidia | 15       | 29.41%  |
| 1 x AMD    | 15       | 29.41%  |
| 2 x AMD    | 2        | 3.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42       | 82.35%  |
| Proprietary | 8        | 15.69%  |
| Unknown     | 1        | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 41.18%  |
| 0.01-0.5   | 16       | 31.37%  |
| 1.01-2.0   | 5        | 9.8%    |
| 0.51-1.0   | 5        | 9.8%    |
| 5.01-6.0   | 2        | 3.92%   |
| 3.01-4.0   | 2        | 3.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 10       | 19.61%  |
| Hewlett-Packard         | 10       | 19.61%  |
| Goldstar                | 7        | 13.73%  |
| Ancor Communications    | 4        | 7.84%   |
| Acer                    | 4        | 7.84%   |
| NEC Computers           | 3        | 5.88%   |
| ViewSonic               | 2        | 3.92%   |
| Sony                    | 2        | 3.92%   |
| Toshiba                 | 1        | 1.96%   |
| Philips                 | 1        | 1.96%   |
| NCS                     | 1        | 1.96%   |
| MSI                     | 1        | 1.96%   |
| Hitachi                 | 1        | 1.96%   |
| Chi Mei Optoelectronics | 1        | 1.96%   |
| Apple                   | 1        | 1.96%   |
| AOC                     | 1        | 1.96%   |
| Unknown                 | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch     | 2        | 3.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 3.51%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch             | 1        | 1.75%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch         | 1        | 1.75%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                             | 1        | 1.75%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                  | 1        | 1.75%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 1.75%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                       | 1        | 1.75%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                     | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 518x324mm 24.1-inch | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch | 1        | 1.75%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch    | 1        | 1.75%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch     | 1        | 1.75%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch     | 1        | 1.75%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch    | 1        | 1.75%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                 | 1        | 1.75%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 1.75%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1        | 1.75%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1        | 1.75%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch       | 1        | 1.75%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch         | 1        | 1.75%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch           | 1        | 1.75%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                | 1        | 1.75%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                       | 1        | 1.75%   |
| Hitachi N91W DVI HIT6D0D 1440x900 410x260mm 19.1-inch                | 1        | 1.75%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch            | 1        | 1.75%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 1        | 1.75%   |
| Hewlett-Packard V214a HPN3490 1920x1080 458x258mm 20.7-inch          | 1        | 1.75%   |
| Hewlett-Packard V214a HPN348C 1920x1080 458x258mm 20.7-inch          | 1        | 1.75%   |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch            | 1        | 1.75%   |
| Hewlett-Packard LV2311 HWP3006 1920x1080 510x287mm 23.0-inch         | 1        | 1.75%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch         | 1        | 1.75%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 1.75%   |
| Hewlett-Packard f1503 HWP2590 1024x768 304x228mm 15.0-inch           | 1        | 1.75%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 510x290mm 23.1-inch     | 1        | 1.75%   |
| Goldstar W2254 GSM56DE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.75%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                 | 1        | 1.75%   |
| Goldstar ULTRAFINE GSM5BC1 3840x2160 697x392mm 31.5-inch             | 1        | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 29.41%  |
| 3840x2160 (4K)     | 5        | 9.8%    |
| 1366x768 (WXGA)    | 5        | 9.8%    |
| 1280x1024 (SXGA)   | 5        | 9.8%    |
| 1920x1200 (WUXGA)  | 4        | 7.84%   |
| 1680x1050 (WSXGA+) | 4        | 7.84%   |
| 1440x900 (WXGA+)   | 3        | 5.88%   |
| 2560x1440 (QHD)    | 2        | 3.92%   |
| 1600x900 (HD+)     | 2        | 3.92%   |
| 1360x768           | 2        | 3.92%   |
| 5280x1080          | 1        | 1.96%   |
| 1280x720 (HD)      | 1        | 1.96%   |
| 1024x768 (XGA)     | 1        | 1.96%   |
| Unknown            | 1        | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 11.54%  |
| 27      | 5        | 9.62%   |
| 23      | 5        | 9.62%   |
| 21      | 5        | 9.62%   |
| 18      | 5        | 9.62%   |
| Unknown | 5        | 9.62%   |
| 20      | 4        | 7.69%   |
| 19      | 4        | 7.69%   |
| 17      | 4        | 7.69%   |
| 22      | 2        | 3.85%   |
| 15      | 2        | 3.85%   |
| 72      | 1        | 1.92%   |
| 46      | 1        | 1.92%   |
| 31      | 1        | 1.92%   |
| 28      | 1        | 1.92%   |
| 12      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 18       | 35.29%  |
| 501-600     | 14       | 27.45%  |
| 301-350     | 6        | 11.76%  |
| Unknown     | 5        | 9.8%    |
| 601-700     | 3        | 5.88%   |
| 351-400     | 2        | 3.92%   |
| 201-300     | 1        | 1.96%   |
| 1501-2000   | 1        | 1.96%   |
| 1001-1500   | 1        | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 27       | 55.1%   |
| 16/10   | 10       | 20.41%  |
| 5/4     | 6        | 12.24%  |
| Unknown | 4        | 8.16%   |
| 4/3     | 2        | 4.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 26.92%  |
| 151-200        | 10       | 19.23%  |
| 141-150        | 8        | 15.38%  |
| 301-350        | 5        | 9.62%   |
| Unknown        | 5        | 9.62%   |
| 251-300        | 3        | 5.77%   |
| 351-500        | 2        | 3.85%   |
| 101-110        | 2        | 3.85%   |
| More than 1000 | 1        | 1.92%   |
| 71-80          | 1        | 1.92%   |
| 501-1000       | 1        | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 60%     |
| 101-120 | 9        | 18%     |
| Unknown | 5        | 10%     |
| 121-160 | 3        | 6%      |
| 1-50    | 2        | 4%      |
| 161-240 | 1        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 86.27%  |
| 2     | 6        | 11.76%  |
| 3     | 1        | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 30       | 37.97%  |
| Intel                                 | 14       | 17.72%  |
| Broadcom                              | 6        | 7.59%   |
| Ralink Technology                     | 4        | 5.06%   |
| TP-Link                               | 3        | 3.8%    |
| Ralink                                | 3        | 3.8%    |
| Qualcomm Atheros                      | 3        | 3.8%    |
| Nvidia                                | 2        | 2.53%   |
| ASUSTek Computer                      | 2        | 2.53%   |
| ZTE WCDMA Technologies MSM            | 1        | 1.27%   |
| Sundance Technology Inc / IC Plus     | 1        | 1.27%   |
| Samsung Electronics                   | 1        | 1.27%   |
| Qualcomm Atheros Communications       | 1        | 1.27%   |
| Microsoft                             | 1        | 1.27%   |
| MediaTek                              | 1        | 1.27%   |
| Marvell Technology Group              | 1        | 1.27%   |
| Linksys                               | 1        | 1.27%   |
| Broadcom Limited                      | 1        | 1.27%   |
| ASIX Electronics                      | 1        | 1.27%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.27%   |
| 3Com                                  | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 24       | 27.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4        | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 4.6%    |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 3.45%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 2.3%    |
| ZTE WCDMA MSM Android                                                                         | 1        | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.15%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.15%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1        | 1.15%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.15%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 1.15%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.15%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.15%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.15%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.15%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.15%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1        | 1.15%   |
| Nvidia MCP77 Ethernet                                                                         | 1        | 1.15%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 1.15%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.15%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.15%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.15%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 1.15%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                                         | 1        | 1.15%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                 | 1        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 1        | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 7        | 23.33%  |
| Ralink Technology                     | 4        | 13.33%  |
| TP-Link                               | 3        | 10%     |
| Ralink                                | 3        | 10%     |
| Qualcomm Atheros                      | 2        | 6.67%   |
| Intel                                 | 2        | 6.67%   |
| ASUSTek Computer                      | 2        | 6.67%   |
| Qualcomm Atheros Communications       | 1        | 3.33%   |
| Microsoft                             | 1        | 3.33%   |
| MediaTek                              | 1        | 3.33%   |
| Linksys                               | 1        | 3.33%   |
| Broadcom Limited                      | 1        | 3.33%   |
| Broadcom                              | 1        | 3.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                                        | 3        | 10%     |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 1        | 3.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                    | 1        | 3.33%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 3.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1        | 3.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 3.33%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1        | 3.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 1        | 3.33%   |
| Realtek 802.11ac NIC                                                                                   | 1        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 1        | 3.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 3.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 3.33%   |
| Ralink RT2561/RT61 802.11g PCI                                                                         | 1        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 3.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 3.33%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1        | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                | 1        | 3.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                                                    | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1        | 3.33%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1        | 3.33%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1        | 3.33%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1        | 3.33%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                                        | 1        | 3.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 29       | 51.79%  |
| Intel                             | 13       | 23.21%  |
| Broadcom                          | 5        | 8.93%   |
| Nvidia                            | 2        | 3.57%   |
| ZTE WCDMA Technologies MSM        | 1        | 1.79%   |
| Sundance Technology Inc / IC Plus | 1        | 1.79%   |
| Samsung Electronics               | 1        | 1.79%   |
| Qualcomm Atheros                  | 1        | 1.79%   |
| Marvell Technology Group          | 1        | 1.79%   |
| ASIX Electronics                  | 1        | 1.79%   |
| 3Com                              | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 24       | 42.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 7.02%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 3.51%   |
| ZTE WCDMA MSM Android                                                         | 1        | 1.75%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 1.75%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 1.75%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.75%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.75%   |
| Intel Ethernet Connection (17) I219-V                                         | 1        | 1.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.75%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 1.75%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 1.75%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 1.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 1.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 1.75%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 1.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1        | 1.75%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.75%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 64.1%   |
| WiFi     | 28       | 35.9%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 64.81%  |
| WiFi     | 19       | 35.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 62.75%  |
| 2     | 16       | 31.37%  |
| 3     | 2        | 3.92%   |
| 4     | 1        | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 78.43%  |
| Yes  | 11       | 21.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 5        | 50%     |
| Intel                   | 2        | 20%     |
| Realtek Semiconductor   | 1        | 10%     |
| Lite-On Technology      | 1        | 10%     |
| Broadcom                | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 50%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| Intel AX200 Bluetooth                               | 1        | 10%     |
| Broadcom HP Bluethunder                             | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 34       | 45.95%  |
| AMD                   | 19       | 25.68%  |
| Nvidia                | 11       | 14.86%  |
| C-Media Electronics   | 3        | 4.05%   |
| JMTek                 | 2        | 2.7%    |
| Texas Instruments     | 1        | 1.35%   |
| Realtek Semiconductor | 1        | 1.35%   |
| Logitech              | 1        | 1.35%   |
| Ensoniq               | 1        | 1.35%   |
| Creative Labs         | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7        | 8.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 5.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 4.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 3.57%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.38%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 2.38%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 2        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 2.38%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 2.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.38%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1        | 1.19%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 1.19%   |
| Nvidia MCP73 High Definition Audio                                                                | 1        | 1.19%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1        | 1.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.19%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 1.19%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Logitech Wireless Headset                                                                         | 1        | 1.19%   |
| JMTek USB Speaker                                                                                 | 1        | 1.19%   |
| JMTek LCS USB Audio                                                                               | 1        | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 1.19%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.19%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 1.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.19%   |
| Ensoniq 5880B / Creative Labs CT5880                                                              | 1        | 1.19%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 30%     |
| Kingston            | 8        | 16%     |
| Samsung Electronics | 5        | 10%     |
| Micron Technology   | 5        | 10%     |
| SK hynix            | 3        | 6%      |
| Corsair             | 2        | 4%      |
| Unknown             | 2        | 4%      |
| Unknown (ABCD)      | 1        | 2%      |
| Unknown (0x7F61)    | 1        | 2%      |
| Qumo                | 1        | 2%      |
| GeIL                | 1        | 2%      |
| G Skil              | 1        | 2%      |
| Avant               | 1        | 2%      |
| 2C0C1121390963FE    | 1        | 2%      |
| 2C0C1121390963FD    | 1        | 2%      |
| 2C0C1121390963F9    | 1        | 2%      |
| 2C0C1121390963F8    | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 2        | 3.7%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 1.85%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                     | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1        | 1.85%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 1.85%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 1.85%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                     | 1        | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.85%   |
| Unknown (0x7F61) RAM Module 1GB FB-DIMM DDR2 667MT/s           | 1        | 1.85%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 1        | 1.85%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.85%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s        | 1        | 1.85%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s        | 1        | 1.85%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 1        | 1.85%   |
| Samsung RAM Module 4GB DIMM DDR3 1067MT/s                      | 1        | 1.85%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 1.85%   |
| Samsung RAM M378B2873FH0-CH9 1GB DIMM DDR3 1333MT/s            | 1        | 1.85%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 1.85%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s            | 1        | 1.85%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1        | 1.85%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 1.85%   |
| Micron RAM Module 512MB FB-DIMM DDR2 667MT/s                   | 1        | 1.85%   |
| Micron RAM 8HTF12864AY-800G1 1GB DIMM DDR2 800MT/s             | 1        | 1.85%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.85%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB DIMM DDR3 1600MT/s            | 1        | 1.85%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s                      | 1        | 1.85%   |
| Kingston RAM Module 1024MB DIMM DDR2 800MT/s                   | 1        | 1.85%   |
| Kingston RAM KTW149-ELD 1024MB DIMM DDR3 1333MT/s              | 1        | 1.85%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 1        | 1.85%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 1        | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR2    | 11       | 27.5%   |
| DDR3    | 10       | 25%     |
| DDR4    | 7        | 17.5%   |
| SDRAM   | 5        | 12.5%   |
| Unknown | 4        | 10%     |
| DDR     | 2        | 5%      |
| LPDDR4  | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 37       | 92.5%   |
| FB-DIMM | 2        | 5%      |
| SODIMM  | 1        | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 14       | 31.82%  |
| 4096  | 12       | 27.27%  |
| 1024  | 8        | 18.18%  |
| 8192  | 5        | 11.36%  |
| 16384 | 3        | 6.82%   |
| 32768 | 1        | 2.27%   |
| 512   | 1        | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 13.95%  |
| 1333    | 6        | 13.95%  |
| Unknown | 6        | 13.95%  |
| 3200    | 4        | 9.3%    |
| 800     | 4        | 9.3%    |
| 667     | 4        | 9.3%    |
| 2133    | 2        | 4.65%   |
| 49926   | 1        | 2.33%   |
| 19791   | 1        | 2.33%   |
| 3933    | 1        | 2.33%   |
| 3500    | 1        | 2.33%   |
| 2666    | 1        | 2.33%   |
| 2400    | 1        | 2.33%   |
| 1639    | 1        | 2.33%   |
| 1067    | 1        | 2.33%   |
| 1033    | 1        | 2.33%   |
| 400     | 1        | 2.33%   |
| 133     | 1        | 2.33%   |

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
| Mustek Systems  | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1        | 33.33%  |
| HP ScanJet 5200c                   | 1        | 33.33%  |
| Canon CanoScan LiDE 110            | 1        | 33.33%  |

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
| 0     | 46       | 90.2%   |
| 1     | 5        | 9.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 3        | 60%     |
| Unassigned class | 1        | 20%     |
| Net/wireless     | 1        | 20%     |

