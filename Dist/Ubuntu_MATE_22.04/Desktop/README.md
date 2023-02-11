Ubuntu MATE 22.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

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

Total: 88

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | CROSSHAIR VI HERO           | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Gigabyte | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Gigabyte | H510M H                     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| ASUSTek  | ROG STRIX Z370-G GAMING     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte | B85M-D3H                    | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte | B85M-D3H                    | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| HP       | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP       | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP       | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| ASUSTek  | M5A78L-M LX                 | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek  | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Gigabyte | B85M-D3H                    | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Dell     | 0J1C3P A00                  | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek  | P8Z77-V PRO                 | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek  | P8Z77-V PRO                 | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| ASRock   | B550M-ITX/ac                | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| ASUSTek  | PRIME Z590-P WIFI           | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| ASUSTek  | ROG STRIX Z690-A GAMING ... | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP       | 2215                        | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Gigabyte | F2A68HM-DS2                 | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Gigabyte | AB350M-Gaming 3-CF          | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock   | B550M-ITX/ac                | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock   | B550M-ITX/ac                | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| ASUSTek  | P7P55 LX                    | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| ASRock   | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| HP       | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI      | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| ASUSTek  | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock   | Z77 Extreme4                | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| Gigabyte | B450M DS3H-CF               | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek  | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek  | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek  | ROG STRIX Z590-E GAMING ... | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| MSI      | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI      | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek  | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo   | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| MSI      | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo   | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek  | PRIME B450-PLUS             | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo   | SHARKBAY SDK0E50510 PRO     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo   | SHARKBAY SDK0E50510 PRO     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek  | PRIME B450-PLUS             | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek  | K30AD_M31AD_M51AD_M32AD     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| MSI      | H81M-P33                    | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock   | HM55-HT                     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| MSI      | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek  | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek  | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek  | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek  | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer     | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek  | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock   | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| HP       | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| HP       | 18E4                        | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP       | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Lenovo   | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| AZW      | GK55                        | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| MSI      | H170M PRO-VDH               | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| Dell     | 08NPPY A00                  | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell     | 08NPPY A00                  | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| MSI      | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP       | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Dell     | 0KWVT8 A03                  | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell     | 0KWVT8 A03                  | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| MSI      | 2AE0                        | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI      | 2AE0                        | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Medion   | MS-7797                     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Dell     | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Gigabyte | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP       | 3646h                       | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Gigabyte | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP       | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP       | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| Acer     | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown  | Unknown                     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| HP       | 3397                        | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASUSTek  | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Unknown  | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| MSI      | B450 TOMAHAWK MAX           | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP       | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Gigabyte | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek  | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek  | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek  | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek  | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 12       | 17.39%  |
| 5.15.0-47-generic    | 11       | 15.94%  |
| 5.15.0-48-generic    | 6        | 8.7%    |
| 5.15.0-50-generic    | 5        | 7.25%   |
| 5.15.0-52-generic    | 4        | 5.8%    |
| 5.15.0-46-generic    | 3        | 4.35%   |
| 5.15.0-40-generic    | 3        | 4.35%   |
| 5.15.0-27-generic    | 3        | 4.35%   |
| 5.15.0-58-generic    | 2        | 2.9%    |
| 5.15.0-57-generic    | 2        | 2.9%    |
| 5.15.0-41-generic    | 2        | 2.9%    |
| 5.15.0-37-generic    | 2        | 2.9%    |
| 5.15.0-25-generic    | 2        | 2.9%    |
| 5.18.0-1-generic     | 1        | 1.45%   |
| 5.15.0-58-lowlatency | 1        | 1.45%   |
| 5.15.0-56-lowlatency | 1        | 1.45%   |
| 5.15.0-43-generic    | 1        | 1.45%   |
| 5.15.0-39-generic    | 1        | 1.45%   |
| 5.15.0-35-generic    | 1        | 1.45%   |
| 5.15.0-30-generic    | 1        | 1.45%   |
| 5.15.0-22-generic    | 1        | 1.45%   |
| 5.15.0-11-generic    | 1        | 1.45%   |
| 5.14.0-1054-oem      | 1        | 1.45%   |
| 5.13.0-52-generic    | 1        | 1.45%   |
| 5.13.0-19-generic    | 1        | 1.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 61       | 93.85%  |
| 5.13.0  | 2        | 3.08%   |
| 5.18.0  | 1        | 1.54%   |
| 5.14.0  | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 61       | 93.85%  |
| 5.13    | 2        | 3.08%   |
| 5.18    | 1        | 1.54%   |
| 5.14    | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| MATE   | 62       | 96.88%  |
| KDE5   | 1        | 1.56%   |
| Budgie | 1        | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 60       | 93.75%  |
| Wayland | 2        | 3.13%   |
| Tty     | 2        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 53       | 80.3%   |
| GDM3    | 8        | 12.12%  |
| Unknown | 5        | 7.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 24       | 37.5%   |
| fr_FR | 7        | 10.94%  |
| it_IT | 6        | 9.38%   |
| de_DE | 4        | 6.25%   |
| en_AU | 3        | 4.69%   |
| pt_BR | 2        | 3.13%   |
| hr_HR | 2        | 3.13%   |
| en_CA | 2        | 3.13%   |
| de_CH | 2        | 3.13%   |
| C     | 2        | 3.13%   |
| ru_RU | 1        | 1.56%   |
| nl_NL | 1        | 1.56%   |
| hu_HU | 1        | 1.56%   |
| fi_FI | 1        | 1.56%   |
| es_PE | 1        | 1.56%   |
| es_AR | 1        | 1.56%   |
| en_IL | 1        | 1.56%   |
| en_GB | 1        | 1.56%   |
| de_AT | 1        | 1.56%   |
| da_DK | 1        | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 62.12%  |
| EFI  | 25       | 37.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 61       | 93.85%  |
| Btrfs | 2        | 3.08%   |
| Zfs   | 1        | 1.54%   |
| Xfs   | 1        | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 42       | 63.64%  |
| Unknown | 18       | 27.27%  |
| MBR     | 6        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 76.56%  |
| Yes       | 15       | 23.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 58.46%  |
| Yes       | 27       | 41.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 31.25%  |
| Hewlett-Packard     | 11       | 17.19%  |
| MSI                 | 9        | 14.06%  |
| Gigabyte Technology | 8        | 12.5%   |
| ASRock              | 5        | 7.81%   |
| Dell                | 4        | 6.25%   |
| Lenovo              | 2        | 3.13%   |
| Unknown             | 2        | 3.13%   |
| Medion              | 1        | 1.56%   |
| AZW                 | 1        | 1.56%   |
| Acer                | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP Compaq Elite 8300 SFF             | 2        | 3.13%   |
| Unknown                              | 2        | 3.13%   |
| MSI p6-2330                          | 1        | 1.56%   |
| MSI MS-7C56                          | 1        | 1.56%   |
| MSI MS-7C09                          | 1        | 1.56%   |
| MSI MS-7C02                          | 1        | 1.56%   |
| MSI MS-7982                          | 1        | 1.56%   |
| MSI MS-7817                          | 1        | 1.56%   |
| MSI MS-7758                          | 1        | 1.56%   |
| MSI MS-7599                          | 1        | 1.56%   |
| MSI B02311                           | 1        | 1.56%   |
| Medion MS-7797                       | 1        | 1.56%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1        | 1.56%   |
| Lenovo T530-28ICB                    | 1        | 1.56%   |
| HP ProLiant ML350p Gen8              | 1        | 1.56%   |
| HP ProLiant MicroServer              | 1        | 1.56%   |
| HP ProDesk 600 G2 DM                 | 1        | 1.56%   |
| HP Pavilion 590-p0049 3LC38AA        | 1        | 1.56%   |
| HP EliteDesk 800 G1 TWR              | 1        | 1.56%   |
| HP EliteDesk 800 G1 SFF              | 1        | 1.56%   |
| HP EliteDesk 705 G1 SFF              | 1        | 1.56%   |
| HP Compaq 8000 Elite SFF PC          | 1        | 1.56%   |
| HP 23-d027c                          | 1        | 1.56%   |
| Gigabyte Z87-HD3                     | 1        | 1.56%   |
| Gigabyte X99P-SLI-CF                 | 1        | 1.56%   |
| Gigabyte H510M H                     | 1        | 1.56%   |
| Gigabyte F2A68HM-DS2                 | 1        | 1.56%   |
| Gigabyte B85M-D3H                    | 1        | 1.56%   |
| Gigabyte B550 GAMING X V2            | 1        | 1.56%   |
| Gigabyte B450M DS3H                  | 1        | 1.56%   |
| Gigabyte AB350M-Gaming 3             | 1        | 1.56%   |
| Dell XPS 8700                        | 1        | 1.56%   |
| Dell Precision 3660                  | 1        | 1.56%   |
| Dell OptiPlex 755                    | 1        | 1.56%   |
| Dell OptiPlex 3050                   | 1        | 1.56%   |
| AZW GK55                             | 1        | 1.56%   |
| ASUS Z170 PRO GAMING/AURA            | 1        | 1.56%   |
| ASUS TUF Gaming B560M-PLUS           | 1        | 1.56%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 1        | 1.56%   |
| ASUS ROG STRIX Z590-E GAMING WIFI    | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 4        | 6.25%   |
| ASUS PRIME             | 4        | 6.25%   |
| HP EliteDesk           | 3        | 4.69%   |
| HP Compaq              | 3        | 4.69%   |
| HP ProLiant            | 2        | 3.13%   |
| Dell OptiPlex          | 2        | 3.13%   |
| Unknown                | 2        | 3.13%   |
| MSI p6-2330            | 1        | 1.56%   |
| MSI MS-7C56            | 1        | 1.56%   |
| MSI MS-7C09            | 1        | 1.56%   |
| MSI MS-7C02            | 1        | 1.56%   |
| MSI MS-7982            | 1        | 1.56%   |
| MSI MS-7817            | 1        | 1.56%   |
| MSI MS-7758            | 1        | 1.56%   |
| MSI MS-7599            | 1        | 1.56%   |
| MSI B02311             | 1        | 1.56%   |
| Medion MS-7797         | 1        | 1.56%   |
| Lenovo ThinkCentre     | 1        | 1.56%   |
| Lenovo T530-28ICB      | 1        | 1.56%   |
| HP ProDesk             | 1        | 1.56%   |
| HP Pavilion            | 1        | 1.56%   |
| HP 23-d027c            | 1        | 1.56%   |
| Gigabyte Z87-HD3       | 1        | 1.56%   |
| Gigabyte X99P-SLI-CF   | 1        | 1.56%   |
| Gigabyte H510M         | 1        | 1.56%   |
| Gigabyte F2A68HM-DS2   | 1        | 1.56%   |
| Gigabyte B85M-D3H      | 1        | 1.56%   |
| Gigabyte B550          | 1        | 1.56%   |
| Gigabyte B450M         | 1        | 1.56%   |
| Gigabyte AB350M-Gaming | 1        | 1.56%   |
| Dell XPS               | 1        | 1.56%   |
| Dell Precision         | 1        | 1.56%   |
| AZW GK55               | 1        | 1.56%   |
| ASUS Z170              | 1        | 1.56%   |
| ASUS TUF               | 1        | 1.56%   |
| ASUS P8Z77-V           | 1        | 1.56%   |
| ASUS P7P55             | 1        | 1.56%   |
| ASUS P5GZ-MX           | 1        | 1.56%   |
| ASUS P5G41T-M          | 1        | 1.56%   |
| ASUS M5A78L-M          | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 12.5%   |
| 2020 | 7        | 10.94%  |
| 2018 | 7        | 10.94%  |
| 2013 | 7        | 10.94%  |
| 2012 | 7        | 10.94%  |
| 2014 | 5        | 7.81%   |
| 2011 | 4        | 6.25%   |
| 2009 | 4        | 6.25%   |
| 2017 | 3        | 4.69%   |
| 2016 | 3        | 4.69%   |
| 2010 | 3        | 4.69%   |
| 2019 | 2        | 3.13%   |
| 2015 | 2        | 3.13%   |
| 2007 | 1        | 1.56%   |
| 2006 | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 96.88%  |
| Enabled  | 2        | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 14       | 21.88%  |
| 8.01-16.0   | 14       | 21.88%  |
| 16.01-24.0  | 11       | 17.19%  |
| 4.01-8.0    | 9        | 14.06%  |
| 3.01-4.0    | 9        | 14.06%  |
| 64.01-256.0 | 4        | 6.25%   |
| 24.01-32.0  | 2        | 3.13%   |
| 1.01-2.0    | 1        | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 22       | 33.33%  |
| 2.01-3.0   | 21       | 31.82%  |
| 4.01-8.0   | 11       | 16.67%  |
| 3.01-4.0   | 5        | 7.58%   |
| 8.01-16.0  | 4        | 6.06%   |
| 0.51-1.0   | 2        | 3.03%   |
| 24.01-32.0 | 1        | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 35.94%  |
| 2      | 12       | 18.75%  |
| 3      | 11       | 17.19%  |
| 4      | 10       | 15.63%  |
| 6      | 4        | 6.25%   |
| 5      | 2        | 3.13%   |
| 20     | 1        | 1.56%   |
| 7      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 62.5%   |
| No        | 24       | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 53.13%  |
| No        | 30       | 46.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 68.75%  |
| Yes       | 20       | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 20.31%  |
| France      | 7        | 10.94%  |
| Italy       | 6        | 9.38%   |
| Germany     | 5        | 7.81%   |
| Croatia     | 3        | 4.69%   |
| Canada      | 3        | 4.69%   |
| Australia   | 3        | 4.69%   |
| Switzerland | 2        | 3.13%   |
| Portugal    | 2        | 3.13%   |
| Hungary     | 2        | 3.13%   |
| Finland     | 2        | 3.13%   |
| Brazil      | 2        | 3.13%   |
| Belgium     | 2        | 3.13%   |
| Austria     | 2        | 3.13%   |
| Ukraine     | 1        | 1.56%   |
| UK          | 1        | 1.56%   |
| Russia      | 1        | 1.56%   |
| Peru        | 1        | 1.56%   |
| New Zealand | 1        | 1.56%   |
| Israel      | 1        | 1.56%   |
| Isle of Man | 1        | 1.56%   |
| Greece      | 1        | 1.56%   |
| Denmark     | 1        | 1.56%   |
| Argentina   | 1        | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Zagreb              | 2        | 3.03%   |
| Melbourne           | 2        | 3.03%   |
| Lansdale            | 2        | 3.03%   |
| Zottegem            | 1        | 1.52%   |
| York                | 1        | 1.52%   |
| Whanganui           | 1        | 1.52%   |
| Washington          | 1        | 1.52%   |
| Viana do Castelo    | 1        | 1.52%   |
| Velyki Mosty        | 1        | 1.52%   |
| Vancouver           | 1        | 1.52%   |
| Turku               | 1        | 1.52%   |
| Toulon              | 1        | 1.52%   |
| Torring             | 1        | 1.52%   |
| Terrace             | 1        | 1.52%   |
| Tel Aviv            | 1        | 1.52%   |
| Taranto             | 1        | 1.52%   |
| Talence             | 1        | 1.52%   |
| St Petersburg       | 1        | 1.52%   |
| Split               | 1        | 1.52%   |
| Seia                | 1        | 1.52%   |
| Schmelz             | 1        | 1.52%   |
| Saint-Etienne       | 1        | 1.52%   |
| Saint Paul          | 1        | 1.52%   |
| Rome                | 1        | 1.52%   |
| Pindamonhangaba     | 1        | 1.52%   |
| Paris               | 1        | 1.52%   |
| Palermo             | 1        | 1.52%   |
| Overpelt            | 1        | 1.52%   |
| Olathe              | 1        | 1.52%   |
| Noventa Vicentina   | 1        | 1.52%   |
| Mount Waverley      | 1        | 1.52%   |
| Miami               | 1        | 1.52%   |
| Marysville          | 1        | 1.52%   |
| Maitenbeth          | 1        | 1.52%   |
| Limoges             | 1        | 1.52%   |
| Lima                | 1        | 1.52%   |
| Lanigan             | 1        | 1.52%   |
| Kematen an der Ybbs | 1        | 1.52%   |
| Joigny              | 1        | 1.52%   |
| Isle of Man         | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 42     | 20.51%  |
| Seagate             | 19       | 40     | 16.24%  |
| Samsung Electronics | 19       | 36     | 16.24%  |
| Crucial             | 8        | 11     | 6.84%   |
| Toshiba             | 6        | 12     | 5.13%   |
| SanDisk             | 6        | 9      | 5.13%   |
| Kingston            | 5        | 7      | 4.27%   |
| Hitachi             | 4        | 4      | 3.42%   |
| Unknown             | 3        | 4      | 2.56%   |
| A-DATA Technology   | 3        | 3      | 2.56%   |
| SPCC                | 2        | 3      | 1.71%   |
| Phison Electronics  | 2        | 2      | 1.71%   |
| Phison              | 2        | 2      | 1.71%   |
| RZX                 | 1        | 1      | 0.85%   |
| NGFF                | 1        | 1      | 0.85%   |
| Maxtor              | 1        | 1      | 0.85%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.85%   |
| KingSpec            | 1        | 1      | 0.85%   |
| Kimtigo             | 1        | 1      | 0.85%   |
| KESU                | 1        | 1      | 0.85%   |
| Hewlett-Packard     | 1        | 2      | 0.85%   |
| GOODRAM             | 1        | 1      | 0.85%   |
| DAS                 | 1        | 6      | 0.85%   |
| Corsair             | 1        | 1      | 0.85%   |
| China               | 1        | 1      | 0.85%   |
| BAITITON            | 1        | 1      | 0.85%   |
| Unknown             | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 2.01%   |
| Samsung SSD 870 QVO 1TB                             | 3        | 2.01%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2        | 1.34%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2        | 1.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 1.34%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.34%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 1.34%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 1.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2        | 1.34%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 1.34%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 1.34%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.34%   |
| Crucial CT2000MX500SSD1 2TB                         | 2        | 1.34%   |
| Crucial CT1000BX500SSD1 1TB                         | 2        | 1.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.67%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.67%   |
| WDC WD8001FZBX-00ASYA0 8TB                          | 1        | 0.67%   |
| WDC WD6400AAKS-00E4A0 640GB                         | 1        | 0.67%   |
| WDC WD60 EFAX-68JH4N1 6TB                           | 1        | 0.67%   |
| WDC WD5003AZEX-00K1GA0 500GB                        | 1        | 0.67%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 0.67%   |
| WDC WD5000AZLX-75K2TA0 500GB                        | 1        | 0.67%   |
| WDC WD5000AAKX-08ERMA0 500GB                        | 1        | 0.67%   |
| WDC WD5000AAKX-003CA0 500GB                         | 1        | 0.67%   |
| WDC WD5000AAKS-65TMA0 500GB                         | 1        | 0.67%   |
| WDC WD5000AAKS-00A7B0 500GB                         | 1        | 0.67%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1        | 0.67%   |
| WDC WD40EZRZ-22GXCB0 4TB                            | 1        | 0.67%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 0.67%   |
| WDC WD4003FFBX-68MU3N0 4TB                          | 1        | 0.67%   |
| WDC WD40 PURZ-85TTDY0 4TB                           | 1        | 0.67%   |
| WDC WD30EFRX-68N32N0 3TB                            | 1        | 0.67%   |
| WDC WD3000HLFS-01G6U0 304GB                         | 1        | 0.67%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.67%   |
| WDC WD20EADS-00R6B0 2TB                             | 1        | 0.67%   |
| WDC WD2000FYYZ-01UL1B1 2TB                          | 1        | 0.67%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1        | 0.67%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 1        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 40     | 40.68%  |
| Seagate             | 19       | 40     | 32.2%   |
| Toshiba             | 6        | 12     | 10.17%  |
| Hitachi             | 4        | 4      | 6.78%   |
| Samsung Electronics | 2        | 5      | 3.39%   |
| Maxtor              | 1        | 1      | 1.69%   |
| KESU                | 1        | 1      | 1.69%   |
| Hewlett-Packard     | 1        | 2      | 1.69%   |
| DAS                 | 1        | 6      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 19     | 30.95%  |
| Crucial             | 8        | 11     | 19.05%  |
| SanDisk             | 4        | 6      | 9.52%   |
| Kingston            | 3        | 5      | 7.14%   |
| WDC                 | 2        | 2      | 4.76%   |
| SPCC                | 2        | 3      | 4.76%   |
| A-DATA Technology   | 2        | 2      | 4.76%   |
| Unknown             | 1        | 1      | 2.38%   |
| RZX                 | 1        | 1      | 2.38%   |
| NGFF                | 1        | 1      | 2.38%   |
| KIOXIA-EXCERIA      | 1        | 1      | 2.38%   |
| KingSpec            | 1        | 1      | 2.38%   |
| GOODRAM             | 1        | 1      | 2.38%   |
| China               | 1        | 1      | 2.38%   |
| BAITITON            | 1        | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 45       | 111    | 45.45%  |
| SSD     | 34       | 56     | 34.34%  |
| NVMe    | 17       | 24     | 17.17%  |
| Unknown | 2        | 3      | 2.02%   |
| MMC     | 1        | 1      | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 157    | 71.6%   |
| NVMe | 17       | 24     | 20.99%  |
| SAS  | 5        | 13     | 6.17%   |
| MMC  | 1        | 1      | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 74     | 43.14%  |
| 0.51-1.0   | 27       | 49     | 26.47%  |
| 1.01-2.0   | 16       | 18     | 15.69%  |
| 3.01-4.0   | 9        | 11     | 8.82%   |
| 4.01-10.0  | 4        | 9      | 3.92%   |
| 2.01-3.0   | 2        | 6      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 14       | 21.54%  |
| 501-1000       | 14       | 21.54%  |
| 101-250        | 13       | 20%     |
| More than 3000 | 12       | 18.46%  |
| 1001-2000      | 6        | 9.23%   |
| 2001-3000      | 2        | 3.08%   |
| 51-100         | 2        | 3.08%   |
| 21-50          | 1        | 1.54%   |
| Unknown        | 1        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 12       | 18.46%  |
| 101-250        | 10       | 15.38%  |
| More than 3000 | 8        | 12.31%  |
| 21-50          | 8        | 12.31%  |
| 51-100         | 8        | 12.31%  |
| 501-1000       | 7        | 10.77%  |
| 251-500        | 5        | 7.69%   |
| 1001-2000      | 4        | 6.15%   |
| 2001-3000      | 2        | 3.08%   |
| Unknown        | 1        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2        | 2      | 22.22%  |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 11.11%  |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 960 PRO 1TB | 1        | 1      | 11.11%  |
| NGFF 2280 256GB SSD                 | 1        | 1      | 11.11%  |
| Hitachi HTS721080G9SA00 80GB        | 1        | 1      | 11.11%  |
| DAS TerraMaster 500GB               | 1        | 3      | 11.11%  |
| China SSD 180GB                     | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 33.33%  |
| WDC                 | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| NGFF                | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |
| DAS                 | 1        | 3      | 11.11%  |
| China               | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 50%     |
| WDC     | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |
| DAS     | 1        | 3      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 8      | 62.5%   |
| SSD  | 2        | 2      | 25%     |
| NVMe | 1        | 1      | 12.5%   |

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
| Works    | 36       | 107    | 49.32%  |
| Detected | 29       | 77     | 39.73%  |
| Malfunc  | 8        | 11     | 10.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 41       | 47.67%  |
| AMD                         | 22       | 25.58%  |
| Samsung Electronics         | 7        | 8.14%   |
| Phison Electronics          | 5        | 5.81%   |
| ASMedia Technology          | 4        | 4.65%   |
| SanDisk                     | 2        | 2.33%   |
| Kingston Technology Company | 2        | 2.33%   |
| Silicon Motion              | 1        | 1.16%   |
| Hewlett-Packard             | 1        | 1.16%   |
| ADATA Technology            | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 8.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7        | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 5.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 4.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 4.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 3.57%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 3.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 3.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 2.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.79%   |
| Phison NVMe Storage Controller                                                 | 2        | 1.79%   |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 1.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 1.79%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 1.79%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.89%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 0.89%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 0.89%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.89%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 0.89%   |
| Phison E7 NVMe Controller                                                      | 1        | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.89%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1        | 0.89%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1        | 0.89%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 0.89%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 0.89%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1        | 0.89%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 0.89%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 55       | 58.51%  |
| NVMe | 17       | 18.09%  |
| IDE  | 15       | 15.96%  |
| RAID | 7        | 7.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 65.63%  |
| AMD    | 22       | 34.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 3.13%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2        | 3.13%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 3.13%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1        | 1.56%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1        | 1.56%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.56%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.56%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.56%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1        | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1        | 1.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.56%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.56%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1        | 1.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.56%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.56%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1        | 1.56%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.56%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.56%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.56%   |
| Intel Core i3-2105 CPU @ 3.10GHz            | 1        | 1.56%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 1.56%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.56%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1        | 1.56%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.56%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.56%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 1        | 1.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.56%   |
| Intel 12th Gen Core i9-12900K               | 1        | 1.56%   |
| Intel 12th Gen Core i7-12700F               | 1        | 1.56%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz     | 1        | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 12       | 18.75%  |
| AMD Ryzen 5       | 8        | 12.5%   |
| Intel Core i7     | 7        | 10.94%  |
| Other             | 6        | 9.38%   |
| Intel Core i3     | 6        | 9.38%   |
| Intel Xeon        | 3        | 4.69%   |
| Intel Pentium     | 3        | 4.69%   |
| Intel Core 2 Duo  | 2        | 3.13%   |
| AMD Ryzen 7       | 2        | 3.13%   |
| AMD Athlon II X2  | 2        | 3.13%   |
| Intel Pentium 4   | 1        | 1.56%   |
| Intel Core 2 Quad | 1        | 1.56%   |
| Intel Celeron     | 1        | 1.56%   |
| AMD Turion II Neo | 1        | 1.56%   |
| AMD Ryzen 9       | 1        | 1.56%   |
| AMD Ryzen 3       | 1        | 1.56%   |
| AMD Phenom II X6  | 1        | 1.56%   |
| AMD FX            | 1        | 1.56%   |
| AMD E             | 1        | 1.56%   |
| AMD Athlon II X4  | 1        | 1.56%   |
| AMD A8            | 1        | 1.56%   |
| AMD A6            | 1        | 1.56%   |
| AMD A4            | 1        | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 35.94%  |
| 2      | 16       | 25%     |
| 6      | 13       | 20.31%  |
| 8      | 5        | 7.81%   |
| 1      | 3        | 4.69%   |
| 12     | 2        | 3.13%   |
| 16     | 1        | 1.56%   |
| 10     | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 98.44%  |
| 2      | 1        | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 37       | 57.81%  |
| 1      | 27       | 42.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 64       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 44.62%  |
| 0x306c3    | 4        | 6.15%   |
| 0xa0671    | 3        | 4.62%   |
| 0x906ea    | 3        | 4.62%   |
| 0x506e3    | 3        | 4.62%   |
| 0x306a9    | 3        | 4.62%   |
| 0x206a7    | 2        | 3.08%   |
| 0x20655    | 2        | 3.08%   |
| 0x0a50000c | 2        | 3.08%   |
| 0x06001119 | 2        | 3.08%   |
| 0xa0653    | 1        | 1.54%   |
| 0x906ed    | 1        | 1.54%   |
| 0x90672    | 1        | 1.54%   |
| 0x6fd      | 1        | 1.54%   |
| 0x306f2    | 1        | 1.54%   |
| 0x206d7    | 1        | 1.54%   |
| 0x10677    | 1        | 1.54%   |
| 0x08108109 | 1        | 1.54%   |
| 0x0800820d | 1        | 1.54%   |
| 0x05000119 | 1        | 1.54%   |
| 0x010000dc | 1        | 1.54%   |
| 0x010000c8 | 1        | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8        | 12.31%  |
| Skylake          | 5        | 7.69%   |
| KabyLake         | 5        | 7.69%   |
| K10              | 5        | 7.69%   |
| IvyBridge        | 5        | 7.69%   |
| Zen 3            | 4        | 6.15%   |
| Zen+             | 3        | 4.62%   |
| Zen              | 3        | 4.62%   |
| Westmere         | 3        | 4.62%   |
| SandyBridge      | 3        | 4.62%   |
| Piledriver       | 3        | 4.62%   |
| Icelake          | 3        | 4.62%   |
| Unknown          | 3        | 4.62%   |
| Zen 2            | 2        | 3.08%   |
| Penryn           | 2        | 3.08%   |
| CometLake        | 2        | 3.08%   |
| NetBurst         | 1        | 1.54%   |
| Goldmont plus    | 1        | 1.54%   |
| Core             | 1        | 1.54%   |
| Bulldozer        | 1        | 1.54%   |
| Bobcat           | 1        | 1.54%   |
| Alderlake Hybrid | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 25       | 36.23%  |
| AMD                        | 23       | 33.33%  |
| Nvidia                     | 20       | 28.99%  |
| Matrox Electronics Systems | 1        | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.35%   |
| Intel HD Graphics 530                                                       | 3        | 4.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 4.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.9%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 2.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.9%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.45%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.45%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 1.45%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.45%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.45%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.45%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.45%   |
| Intel HD Graphics 630                                                       | 1        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1        | 1.45%   |
| Intel AlderLake-S GT1                                                       | 1        | 1.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.45%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.45%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 1        | 1.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.45%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 1.45%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 21       | 32.81%  |
| 1 x AMD        | 21       | 32.81%  |
| 1 x Nvidia     | 18       | 28.13%  |
| 1 x Matrox     | 1        | 1.56%   |
| Intel + Nvidia | 1        | 1.56%   |
| Intel + AMD    | 1        | 1.56%   |
| AMD + Nvidia   | 1        | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 49       | 76.56%  |
| Proprietary | 13       | 20.31%  |
| Unknown     | 2        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 60.94%  |
| 0.51-1.0   | 6        | 9.38%   |
| 0.01-0.5   | 5        | 7.81%   |
| 3.01-4.0   | 4        | 6.25%   |
| 1.01-2.0   | 4        | 6.25%   |
| 5.01-6.0   | 3        | 4.69%   |
| 7.01-8.0   | 1        | 1.56%   |
| 2.01-3.0   | 1        | 1.56%   |
| 8.01-16.0  | 1        | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 17.65%  |
| Goldstar             | 11       | 16.18%  |
| Acer                 | 7        | 10.29%  |
| Philips              | 6        | 8.82%   |
| Dell                 | 6        | 8.82%   |
| Hewlett-Packard      | 5        | 7.35%   |
| Iiyama               | 3        | 4.41%   |
| Lenovo               | 2        | 2.94%   |
| BenQ                 | 2        | 2.94%   |
| Ancor Communications | 2        | 2.94%   |
| Westinghouse         | 1        | 1.47%   |
| VMO                  | 1        | 1.47%   |
| Vizio                | 1        | 1.47%   |
| Vita                 | 1        | 1.47%   |
| ViewSonic            | 1        | 1.47%   |
| Sony                 | 1        | 1.47%   |
| NEC Computers        | 1        | 1.47%   |
| Medion               | 1        | 1.47%   |
| Insignia             | 1        | 1.47%   |
| Gateway              | 1        | 1.47%   |
| ASUSTek Computer     | 1        | 1.47%   |
| AOC                  | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                   | 2        | 2.86%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch         | 1        | 1.43%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1        | 1.43%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                | 1        | 1.43%   |
| Vita LCD Monitor VIT0780 1920x1080                                   | 1        | 1.43%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch        | 1        | 1.43%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 1.43%   |
| Sony LCD Monitor TV                                                  | 1        | 1.43%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1        | 1.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1        | 1.43%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1        | 1.43%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch    | 1        | 1.43%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 1.43%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch    | 1        | 1.43%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch    | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM0D4B 1360x768 609x347mm 27.6-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch | 1        | 1.43%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                       | 1        | 1.43%   |
| Philips PHL BDL3220QL PHLD230 1920x1080 698x393mm 31.5-inch          | 1        | 1.43%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 1.43%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch             | 1        | 1.43%   |
| Philips PHL 242E2F PHLC238 1920x1080 527x296mm 23.8-inch             | 1        | 1.43%   |
| Philips PHL 227E6 PHLC0E5 1920x1080 477x268mm 21.5-inch              | 1        | 1.43%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch              | 1        | 1.43%   |
| NEC Computers AS221WM NEC67C2 1680x1050 473x296mm 22.0-inch          | 1        | 1.43%   |
| Medion MD 20431 MED36A5 1920x1080 520x290mm 23.4-inch                | 1        | 1.43%   |
| Lenovo LEN G25-10 LEN65FE 1920x1080 544x303mm 24.5-inch              | 1        | 1.43%   |
| Lenovo C27-35 LEN66BA 1920x1080 597x336mm 27.0-inch                  | 1        | 1.43%   |
| Insignia NS-19E310A13 BBY0101 1360x768 410x230mm 18.5-inch           | 1        | 1.43%   |
| Iiyama PLX436S IVM46D7 1280x1024 340x270mm 17.1-inch                 | 1        | 1.43%   |
| Iiyama PL2770H IVM665D 1920x1080 598x336mm 27.0-inch                 | 1        | 1.43%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.43%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 465x291mm 21.6-inch          | 1        | 1.43%   |
| Hewlett-Packard Omni HWP1001 1920x1080 509x286mm 23.0-inch           | 1        | 1.43%   |
| Hewlett-Packard LA1905 HWP2845 1440x900 408x255mm 18.9-inch          | 1        | 1.43%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 1.43%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 698x393mm 31.5-inch     | 1        | 1.43%   |
| Hewlett-Packard 24fw HPN3546 1920x1080 527x296mm 23.8-inch           | 1        | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 50.82%  |
| 3840x2160 (4K)     | 5        | 8.2%    |
| 1680x1050 (WSXGA+) | 4        | 6.56%   |
| 2560x1440 (QHD)    | 3        | 4.92%   |
| 1440x900 (WXGA+)   | 3        | 4.92%   |
| 1280x1024 (SXGA)   | 3        | 4.92%   |
| 3440x1440          | 2        | 3.28%   |
| 1366x768 (WXGA)    | 2        | 3.28%   |
| 1360x768           | 2        | 3.28%   |
| 3840x1080          | 1        | 1.64%   |
| 2560x1600          | 1        | 1.64%   |
| 2560x1080          | 1        | 1.64%   |
| 1920x1200 (WUXGA)  | 1        | 1.64%   |
| 1280x720 (HD)      | 1        | 1.64%   |
| Unknown            | 1        | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 11       | 16.67%  |
| 23      | 10       | 15.15%  |
| 21      | 9        | 13.64%  |
| 31      | 8        | 12.12%  |
| 24      | 7        | 10.61%  |
| 19      | 4        | 6.06%   |
| 17      | 4        | 6.06%   |
| 34      | 3        | 4.55%   |
| Unknown | 3        | 4.55%   |
| 22      | 2        | 3.03%   |
| 74      | 1        | 1.52%   |
| 54      | 1        | 1.52%   |
| 40      | 1        | 1.52%   |
| 18      | 1        | 1.52%   |
| 15      | 1        | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 38.46%  |
| 401-500     | 16       | 24.62%  |
| 601-700     | 10       | 15.38%  |
| 301-350     | 5        | 7.69%   |
| 701-800     | 3        | 4.62%   |
| Unknown     | 3        | 4.62%   |
| 801-900     | 1        | 1.54%   |
| 1501-2000   | 1        | 1.54%   |
| 1001-1500   | 1        | 1.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 68.42%  |
| 16/10   | 10       | 17.54%  |
| 5/4     | 4        | 7.02%   |
| 21/9    | 3        | 5.26%   |
| Unknown | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 34.38%  |
| 351-500        | 11       | 17.19%  |
| 301-350        | 11       | 17.19%  |
| 151-200        | 6        | 9.38%   |
| 141-150        | 5        | 7.81%   |
| Unknown        | 3        | 4.69%   |
| More than 1000 | 2        | 3.13%   |
| 251-300        | 2        | 3.13%   |
| 101-110        | 1        | 1.56%   |
| 501-1000       | 1        | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 64.41%  |
| 101-120 | 11       | 18.64%  |
| 121-160 | 4        | 6.78%   |
| 1-50    | 3        | 5.08%   |
| Unknown | 3        | 5.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 72.31%  |
| 2     | 15       | 23.08%  |
| 0     | 3        | 4.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 43       | 47.78%  |
| Intel                           | 26       | 28.89%  |
| Broadcom                        | 7        | 7.78%   |
| Qualcomm Atheros                | 4        | 4.44%   |
| Ralink                          | 3        | 3.33%   |
| TP-Link                         | 2        | 2.22%   |
| Qualcomm Atheros Communications | 1        | 1.11%   |
| NetGear                         | 1        | 1.11%   |
| MediaTek                        | 1        | 1.11%   |
| Marvell Technology Group        | 1        | 1.11%   |
| ASUSTek Computer                | 1        | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34       | 33.33%  |
| Intel Ethernet Controller I225-V                                  | 5        | 4.9%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.96%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.96%   |
| Intel Wireless 7265                                               | 2        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.96%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 1.96%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.98%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.98%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.98%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.98%   |
| NetGear A6150                                                     | 1        | 0.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.98%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.98%   |
| Intel Wireless 3165                                               | 1        | 0.98%   |
| Intel Wireless 3160                                               | 1        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 32.35%  |
| Realtek Semiconductor           | 10       | 29.41%  |
| Ralink                          | 3        | 8.82%   |
| TP-Link                         | 2        | 5.88%   |
| Qualcomm Atheros                | 2        | 5.88%   |
| Broadcom                        | 2        | 5.88%   |
| Qualcomm Atheros Communications | 1        | 2.94%   |
| NetGear                         | 1        | 2.94%   |
| MediaTek                        | 1        | 2.94%   |
| ASUSTek Computer                | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 5.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 5.88%   |
| Intel Wireless 7265                                            | 2        | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 5.88%   |
| TP-Link Archer T4U ver.3                                       | 1        | 2.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 2.94%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 2.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 2.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 2.94%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 2.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.94%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.94%   |
| NetGear A6150                                                  | 1        | 2.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 2.94%   |
| Intel Wireless 3165                                            | 1        | 2.94%   |
| Intel Wireless 3160                                            | 1        | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1        | 2.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 2.94%   |
| Broadcom Network controller                                    | 1        | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 2.94%   |
| ASUS 802.11ac NIC                                              | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 38       | 57.58%  |
| Intel                    | 20       | 30.3%   |
| Broadcom                 | 5        | 7.58%   |
| Qualcomm Atheros         | 2        | 3.03%   |
| Marvell Technology Group | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34       | 50%     |
| Intel Ethernet Controller I225-V                                  | 5        | 7.35%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.94%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.47%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 1.47%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.47%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.47%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.47%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1        | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 65.31%  |
| WiFi     | 34       | 34.69%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 51       | 79.69%  |
| WiFi     | 13       | 20.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 53.13%  |
| 2     | 26       | 40.63%  |
| 3     | 3        | 4.69%   |
| 4     | 1        | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 73.85%  |
| Yes  | 17       | 26.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 40%     |
| Realtek Semiconductor   | 3        | 15%     |
| Cambridge Silicon Radio | 2        | 10%     |
| Broadcom                | 2        | 10%     |
| Ralink                  | 1        | 5%      |
| MediaTek                | 1        | 5%      |
| IMC Networks            | 1        | 5%      |
| Belkin Components       | 1        | 5%      |
| ASUSTek Computer        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 15%     |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 10%     |
| Intel Bluetooth Device                              | 2        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 10%     |
| Realtek RTL8723B Bluetooth                          | 1        | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5%      |
| Realtek Bluetooth Radio                             | 1        | 5%      |
| Ralink RT3290 Bluetooth                             | 1        | 5%      |
| MediaTek Wireless_Device                            | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| IMC Networks Bluetooth Radio                        | 1        | 5%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 5%      |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 5%      |
| Belkin Components F8T013 Bluetooth Adapter          | 1        | 5%      |
| ASUS Bluetooth Radio                                | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 40       | 37.74%  |
| AMD                     | 27       | 25.47%  |
| Nvidia                  | 20       | 18.87%  |
| C-Media Electronics     | 4        | 3.77%   |
| ASUSTek Computer        | 3        | 2.83%   |
| Generalplus Technology  | 2        | 1.89%   |
| TerraTec Electronic     | 1        | 0.94%   |
| Kingston Technology     | 1        | 0.94%   |
| JMTek                   | 1        | 0.94%   |
| GN Netcom               | 1        | 0.94%   |
| Creative Technology     | 1        | 0.94%   |
| Corsair                 | 1        | 0.94%   |
| Cambridge Silicon Radio | 1        | 0.94%   |
| BlackWeb                | 1        | 0.94%   |
| Anlya.cn                | 1        | 0.94%   |
| Alesis                  | 1        | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 7        | 5.6%    |
| AMD Family 17h/19h HD Audio Controller                              | 7        | 5.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 6        | 4.8%    |
| AMD SBx00 Azalia (Intel HDA)                                        | 6        | 4.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                               | 5        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 4        | 3.2%    |
| Intel Tiger Lake-H HD Audio Controller                              | 4        | 3.2%    |
| Intel 200 Series PCH HD Audio                                       | 4        | 3.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 4        | 3.2%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 4        | 3.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 3        | 2.4%    |
| ASUSTek Computer USB Audio                                          | 3        | 2.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3        | 2.4%    |
| AMD FCH Azalia Controller                                           | 3        | 2.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3        | 2.4%    |
| Nvidia GP108 High Definition Audio Controller                       | 2        | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                       | 2        | 1.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 2        | 1.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 2        | 1.6%    |
| Intel Cannon Lake PCH cAVS                                          | 2        | 1.6%    |
| Intel Alder Lake-S HD Audio Controller                              | 2        | 1.6%    |
| Generalplus Technology USB Audio Device                             | 2        | 1.6%    |
| AMD Trinity HDMI Audio Controller                                   | 2        | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                            | 2        | 1.6%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                      | 2        | 1.6%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 2        | 1.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2        | 1.6%    |
| TerraTec Electronic Aureon Dual USB                                 | 1        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                       | 1        | 0.8%    |
| Nvidia High Definition Audio Controller                             | 1        | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                       | 1        | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                       | 1        | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                  | 1        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                       | 1        | 0.8%    |
| Nvidia GA102 High Definition Audio Controller                       | 1        | 0.8%    |
| Kingston Technology HyperX 7.1 Audio                                | 1        | 0.8%    |
| JMTek USB Speaker                                                   | 1        | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                         | 1        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 9        | 19.15%  |
| Crucial             | 8        | 17.02%  |
| Kingston            | 7        | 14.89%  |
| Unknown             | 6        | 12.77%  |
| SK hynix            | 5        | 10.64%  |
| Samsung Electronics | 5        | 10.64%  |
| G.Skill             | 2        | 4.26%   |
| Unifosa             | 1        | 2.13%   |
| Ramaxel Technology  | 1        | 2.13%   |
| Micron Technology   | 1        | 2.13%   |
| Hewlett-Packard     | 1        | 2.13%   |
| HBS                 | 1        | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                  | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 2.04%   |
| Unknown RAM Module 4GB DIMM                               | 1        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 2.04%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s   | 1        | 2.04%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s | 1        | 2.04%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s         | 1        | 2.04%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s       | 1        | 2.04%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s      | 1        | 2.04%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 2.04%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s     | 1        | 2.04%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s    | 1        | 2.04%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.04%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 2.04%   |
| Samsung RAM M323R2GA3BB0-CQKOL 16GB DIMM DDR5 4800MT/s    | 1        | 2.04%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s       | 1        | 2.04%   |
| Ramaxel RAM RMR1870EC58E9 4GB DIMM DDR3 1333MT/s          | 1        | 2.04%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 2.04%   |
| Kingston RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 2.04%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 2.04%   |
| Kingston RAM KHX1600C9D3LK2/8GX 4GB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s     | 1        | 2.04%   |
| Kingston RAM KF2666C16D4/16G 16GB DIMM DDR4 2666MT/s      | 1        | 2.04%   |
| Kingston RAM 99U5702-094.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 2.04%   |
| Kingston RAM 9905471-014.A 4GB DIMM DDR3 1333MT/s         | 1        | 2.04%   |
| HP RAM 712383-081 16GB DIMM DDR3 1866MT/s                 | 1        | 2.04%   |
| HBS RAM SO8G1600CL11L 8GB SODIMM DDR3 1600MT/s            | 1        | 2.04%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s      | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s     | 1        | 2.04%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s   | 1        | 2.04%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s     | 1        | 2.04%   |
| Crucial RAM CT16G4DFRA266.M8FB 16GB DIMM DDR4 2667MT/s    | 1        | 2.04%   |
| Crucial RAM CT16G4DFD824A.C16FE 16GB DIMM DDR4 2400MT/s   | 1        | 2.04%   |
| Crucial RAM BLT8G3D1608DT1TX0. 8192MB DIMM DDR3 1600MT/s  | 1        | 2.04%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s     | 1        | 2.04%   |
| Crucial RAM BLS16G4D240FSC.16FA 16GB DIMM DDR4 2400MT/s   | 1        | 2.04%   |
| Crucial RAM BLM16G40C18U4B.M8FB1 16GB DIMM DDR4 4000MT/s  | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 21       | 51.22%  |
| DDR3    | 15       | 36.59%  |
| DDR2    | 2        | 4.88%   |
| DDR5    | 1        | 2.44%   |
| DDR     | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 37       | 90.24%  |
| SODIMM | 4        | 9.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 14       | 30.43%  |
| 8192  | 13       | 28.26%  |
| 4096  | 13       | 28.26%  |
| 2048  | 3        | 6.52%   |
| 32768 | 2        | 4.35%   |
| 1024  | 1        | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 9        | 20.93%  |
| 1333    | 6        | 13.95%  |
| 2400    | 4        | 9.3%    |
| 3200    | 3        | 6.98%   |
| 2667    | 3        | 6.98%   |
| 3600    | 2        | 4.65%   |
| 2133    | 2        | 4.65%   |
| 800     | 2        | 4.65%   |
| 4800    | 1        | 2.33%   |
| 4000    | 1        | 2.33%   |
| 3466    | 1        | 2.33%   |
| 3400    | 1        | 2.33%   |
| 3333    | 1        | 2.33%   |
| 3100    | 1        | 2.33%   |
| 2800    | 1        | 2.33%   |
| 2747    | 1        | 2.33%   |
| 2666    | 1        | 2.33%   |
| 1866    | 1        | 2.33%   |
| 1648    | 1        | 2.33%   |
| Unknown | 1        | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 40%     |
| Seiko Epson        | 1        | 20%     |
| Hewlett-Packard    | 1        | 20%     |
| Graphtec America   | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series        | 1        | 20%     |
| HP DeskJet 2700 series            | 1        | 20%     |
| Graphtec America Graphtec Printer | 1        | 20%     |
| Brother HL-3140CW series          | 1        | 20%     |
| Brother DCP-L5500DN series        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet G4010        | 1        | 33.33%  |
| Canon CanoScan LiDE 120 | 1        | 33.33%  |
| Canon CanoScan LiDE 110 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 5        | 38.46%  |
| Z-Star Microelectronics | 1        | 7.69%   |
| Realtek Semiconductor   | 1        | 7.69%   |
| Razer USA               | 1        | 7.69%   |
| Microsoft               | 1        | 7.69%   |
| Microdia                | 1        | 7.69%   |
| Generalplus Technology  | 1        | 7.69%   |
| ARC International       | 1        | 7.69%   |
| Apple                   | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 2        | 15.38%  |
| Z-Star HP 3-MegaPixel Webcam GX607AA    | 1        | 7.69%   |
| Realtek HP 1.0MP High Definition Webcam | 1        | 7.69%   |
| Razer USA Gaming Webcam [Kiyo]          | 1        | 7.69%   |
| Microsoft LifeCam VX-500 [1357]         | 1        | 7.69%   |
| Microdia Webcam Vitade AF               | 1        | 7.69%   |
| Logitech Webcam C925e                   | 1        | 7.69%   |
| Logitech QuickCam E 3500                | 1        | 7.69%   |
| Logitech HD Pro Webcam C920             | 1        | 7.69%   |
| Generalplus GENERAL WEBCAM              | 1        | 7.69%   |
| ARC International Camera                | 1        | 7.69%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 7.69%   |

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
| 0     | 57       | 87.69%  |
| 1     | 7        | 10.77%  |
| 3     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 33.33%  |
| Graphics card    | 3        | 33.33%  |
| Unassigned class | 1        | 11.11%  |
| Card reader      | 1        | 11.11%  |
| Bluetooth        | 1        | 11.11%  |

