MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 78

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| Dell          | 0PC5F7 A02                  | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| HP            | 3396                        | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0HY9JP A02                  | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar       | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel         | DH55TC AAE70932-303         | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP            | MS-7848                     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | 0DR845                      | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek       | SABERTOOTH X99              | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | SABERTOOTH X99              | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.0-20-amd64              | 9        | 13.64%  |
| 5.14.0-4mx-amd64             | 6        | 9.09%   |
| 5.10.0-19-amd64              | 6        | 9.09%   |
| 5.10.0-13-amd64              | 5        | 7.58%   |
| 5.10.0-18-amd64              | 4        | 6.06%   |
| 5.10.0-16-amd64              | 4        | 6.06%   |
| 5.10.0-15-amd64              | 4        | 6.06%   |
| 5.16.0-5mx-amd64             | 3        | 4.55%   |
| 5.14.0-3mx-amd64             | 2        | 3.03%   |
| 5.10.0-9-amd64               | 2        | 3.03%   |
| 5.10.0-11-amd64              | 2        | 3.03%   |
| 6.1.0-2mx-amd64              | 1        | 1.52%   |
| 6.0.5-x64v1-xanmod1          | 1        | 1.52%   |
| 6.0.0-4mx-rt-amd64           | 1        | 1.52%   |
| 6.0.0-13.3-liquorix-amd64    | 1        | 1.52%   |
| 5.19.0-4.2-liquorix-amd64    | 1        | 1.52%   |
| 5.19.0-17.2-liquorix-amd64   | 1        | 1.52%   |
| 5.19.0-14.1-liquorix-amd64   | 1        | 1.52%   |
| 5.16.0-rc5-hwmon-next+       | 1        | 1.52%   |
| 5.16.0-6mx-amd64             | 1        | 1.52%   |
| 5.15.0-2-amd64               | 1        | 1.52%   |
| 5.15.0-0.bpo.2-amd64         | 1        | 1.52%   |
| 5.14.0-2mx-amd64             | 1        | 1.52%   |
| 5.10.52-antix.1-amd64-smp    | 1        | 1.52%   |
| 5.10.111-tkg-cfs             | 1        | 1.52%   |
| 5.10.0-21-amd64              | 1        | 1.52%   |
| 5.10.0-18-686-pae            | 1        | 1.52%   |
| 5.10.0-17-amd64              | 1        | 1.52%   |
| 5.10.0-10-amd64              | 1        | 1.52%   |
| 4.19.0-256-antix.1-amd64-smp | 1        | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 40       | 60.61%  |
| 5.14.0   | 9        | 13.64%  |
| 5.16.0   | 5        | 7.58%   |
| 5.19.0   | 3        | 4.55%   |
| 6.0.0    | 2        | 3.03%   |
| 5.15.0   | 2        | 3.03%   |
| 6.1.0    | 1        | 1.52%   |
| 6.0.5    | 1        | 1.52%   |
| 5.10.52  | 1        | 1.52%   |
| 5.10.111 | 1        | 1.52%   |
| 4.19.0   | 1        | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 42       | 63.64%  |
| 5.14    | 9        | 13.64%  |
| 5.16    | 5        | 7.58%   |
| 6.0     | 3        | 4.55%   |
| 5.19    | 3        | 4.55%   |
| 5.15    | 2        | 3.03%   |
| 6.1     | 1        | 1.52%   |
| 4.19    | 1        | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 65       | 98.48%  |
| i686   | 1        | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 48       | 72.73%  |
| KDE5             | 15       | 22.73%  |
| lightdm-xsession | 2        | 3.03%   |
| Unknown          | 1        | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 66       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 47       | 71.21%  |
| SDDM    | 15       | 22.73%  |
| SLiM    | 3        | 4.55%   |
| GDM     | 1        | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 29       | 43.94%  |
| de_DE | 10       | 15.15%  |
| it_IT | 6        | 9.09%   |
| ru_RU | 3        | 4.55%   |
| pl_PL | 3        | 4.55%   |
| en_GB | 3        | 4.55%   |
| de_CH | 2        | 3.03%   |
| sv_SE | 1        | 1.52%   |
| pt_BR | 1        | 1.52%   |
| hu_HU | 1        | 1.52%   |
| fr_FR | 1        | 1.52%   |
| fi_FI | 1        | 1.52%   |
| es_VE | 1        | 1.52%   |
| es_MX | 1        | 1.52%   |
| es_ES | 1        | 1.52%   |
| es_CO | 1        | 1.52%   |
| en_NZ | 1        | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 59.09%  |
| EFI  | 27       | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 58       | 87.88%  |
| Overlay  | 4        | 6.06%   |
| Xfs      | 1        | 1.52%   |
| Reiserfs | 1        | 1.52%   |
| Ext3     | 1        | 1.52%   |
| Btrfs    | 1        | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 39       | 59.09%  |
| MBR  | 27       | 40.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 59.09%  |
| Yes       | 27       | 40.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 56.06%  |
| No        | 29       | 43.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 13       | 19.7%   |
| Gigabyte Technology | 9        | 13.64%  |
| MSI                 | 7        | 10.61%  |
| Dell                | 7        | 10.61%  |
| Lenovo              | 4        | 6.06%   |
| Hewlett-Packard     | 4        | 6.06%   |
| ASRock              | 4        | 6.06%   |
| Intel               | 3        | 4.55%   |
| Pegatron            | 2        | 3.03%   |
| Fujitsu             | 2        | 3.03%   |
| Biostar             | 2        | 3.03%   |
| ZOTAC               | 1        | 1.52%   |
| SIRAGON             | 1        | 1.52%   |
| MP                  | 1        | 1.52%   |
| Medion              | 1        | 1.52%   |
| Huanan              | 1        | 1.52%   |
| GALAX               | 1        | 1.52%   |
| Foxconn             | 1        | 1.52%   |
| BESSTAR Tech        | 1        | 1.52%   |
| AOpen               | 1        | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 3        | 4.55%   |
| Dell OptiPlex 755                           | 2        | 3.03%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 3.03%   |
| SIRAGON AIO-5150                            | 1        | 1.52%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 1.52%   |
| Pegatron 2AD5                               | 1        | 1.52%   |
| MSI MS-7C91                                 | 1        | 1.52%   |
| MSI MS-7C37                                 | 1        | 1.52%   |
| MSI MS-7B98                                 | 1        | 1.52%   |
| MSI MS-7A63                                 | 1        | 1.52%   |
| MSI MS-7A34                                 | 1        | 1.52%   |
| MSI MS-7917                                 | 1        | 1.52%   |
| MSI MS-7758                                 | 1        | 1.52%   |
| MP MS-7848                                  | 1        | 1.52%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 1.52%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 1.52%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 1.52%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 1.52%   |
| Lenovo 10AAS1QB0B                           | 1        | 1.52%   |
| Intel V1.3                                  | 1        | 1.52%   |
| Intel DH55TC AAE70932-303                   | 1        | 1.52%   |
| Intel D34010WYK H14771-303                  | 1        | 1.52%   |
| Huanan X99-F8                               | 1        | 1.52%   |
| HP Z400 Workstation                         | 1        | 1.52%   |
| HP Compaq Elite 8300 CMT                    | 1        | 1.52%   |
| HP Compaq 8100 Elite SFF PC                 | 1        | 1.52%   |
| HP Compaq 8000 Elite CMT PC                 | 1        | 1.52%   |
| Gigabyte Z77X-D3H                           | 1        | 1.52%   |
| Gigabyte Z390 UD                            | 1        | 1.52%   |
| Gigabyte X570 AORUS PRO                     | 1        | 1.52%   |
| Gigabyte H410M S2H V3                       | 1        | 1.52%   |
| Gigabyte GA-MA785GM-US2H                    | 1        | 1.52%   |
| Gigabyte GA-MA770-UD3                       | 1        | 1.52%   |
| Gigabyte B560M DS3H V2                      | 1        | 1.52%   |
| Gigabyte B550M S2H                          | 1        | 1.52%   |
| Gigabyte B550M DS3H                         | 1        | 1.52%   |
| GALAX B550M                                 | 1        | 1.52%   |
| Fujitsu ESPRIMO P720                        | 1        | 1.52%   |
| Fujitsu CELSIUS M770                        | 1        | 1.52%   |
| Foxconn Pro3500 Series                      | 1        | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 6        | 9.09%   |
| HP Compaq                | 3        | 4.55%   |
| ASUS All                 | 3        | 4.55%   |
| Gigabyte B550M           | 2        | 3.03%   |
| ASUS ROG                 | 2        | 3.03%   |
| ASUS P5GC-MX             | 2        | 3.03%   |
| SIRAGON AIO-5150         | 1        | 1.52%   |
| Pegatron FQ425AA-ABA     | 1        | 1.52%   |
| Pegatron 2AD5            | 1        | 1.52%   |
| MSI MS-7C91              | 1        | 1.52%   |
| MSI MS-7C37              | 1        | 1.52%   |
| MSI MS-7B98              | 1        | 1.52%   |
| MSI MS-7A63              | 1        | 1.52%   |
| MSI MS-7A34              | 1        | 1.52%   |
| MSI MS-7917              | 1        | 1.52%   |
| MSI MS-7758              | 1        | 1.52%   |
| MP MS-7848               | 1        | 1.52%   |
| Medion Akoya             | 1        | 1.52%   |
| Lenovo ThinkStation      | 1        | 1.52%   |
| Lenovo ThinkCentre       | 1        | 1.52%   |
| Lenovo IdeaCentre        | 1        | 1.52%   |
| Lenovo 10AAS1QB0B        | 1        | 1.52%   |
| Intel V1.3               | 1        | 1.52%   |
| Intel DH55TC             | 1        | 1.52%   |
| Intel D34010WYK          | 1        | 1.52%   |
| Huanan X99-F8            | 1        | 1.52%   |
| HP Z400                  | 1        | 1.52%   |
| Gigabyte Z77X-D3H        | 1        | 1.52%   |
| Gigabyte Z390            | 1        | 1.52%   |
| Gigabyte X570            | 1        | 1.52%   |
| Gigabyte H410M           | 1        | 1.52%   |
| Gigabyte GA-MA785GM-US2H | 1        | 1.52%   |
| Gigabyte GA-MA770-UD3    | 1        | 1.52%   |
| Gigabyte B560M           | 1        | 1.52%   |
| GALAX B550M              | 1        | 1.52%   |
| Fujitsu ESPRIMO          | 1        | 1.52%   |
| Fujitsu CELSIUS          | 1        | 1.52%   |
| Foxconn Pro3500          | 1        | 1.52%   |
| Dell Precision           | 1        | 1.52%   |
| Biostar H61MH            | 1        | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 10.61%  |
| 2018 | 6        | 9.09%   |
| 2012 | 6        | 9.09%   |
| 2021 | 5        | 7.58%   |
| 2019 | 5        | 7.58%   |
| 2013 | 5        | 7.58%   |
| 2009 | 5        | 7.58%   |
| 2022 | 4        | 6.06%   |
| 2016 | 4        | 6.06%   |
| 2014 | 4        | 6.06%   |
| 2007 | 4        | 6.06%   |
| 2011 | 3        | 4.55%   |
| 2010 | 3        | 4.55%   |
| 2015 | 2        | 3.03%   |
| 2008 | 2        | 3.03%   |
| 2017 | 1        | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 66       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 66       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 20       | 30.3%   |
| 32.01-64.0  | 16       | 24.24%  |
| 4.01-8.0    | 11       | 16.67%  |
| 16.01-24.0  | 8        | 12.12%  |
| 3.01-4.0    | 7        | 10.61%  |
| 64.01-256.0 | 2        | 3.03%   |
| 24.01-32.0  | 1        | 1.52%   |
| 2.01-3.0    | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 22       | 32.84%  |
| 2.01-3.0   | 18       | 26.87%  |
| 3.01-4.0   | 12       | 17.91%  |
| 4.01-8.0   | 9        | 13.43%  |
| 8.01-16.0  | 3        | 4.48%   |
| 0.51-1.0   | 2        | 2.99%   |
| 16.01-24.0 | 1        | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 28.79%  |
| 1      | 19       | 28.79%  |
| 3      | 16       | 24.24%  |
| 4      | 7        | 10.61%  |
| 5      | 3        | 4.55%   |
| 8      | 2        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 50%     |
| No        | 33       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 66       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 56.06%  |
| Yes       | 29       | 43.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 81.82%  |
| Yes       | 12       | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 25.76%  |
| Germany     | 10       | 15.15%  |
| Italy       | 6        | 9.09%   |
| Russia      | 3        | 4.55%   |
| Poland      | 3        | 4.55%   |
| Finland     | 3        | 4.55%   |
| Venezuela   | 2        | 3.03%   |
| UK          | 2        | 3.03%   |
| Switzerland | 2        | 3.03%   |
| India       | 2        | 3.03%   |
| France      | 2        | 3.03%   |
| Sweden      | 1        | 1.52%   |
| Spain       | 1        | 1.52%   |
| Romania     | 1        | 1.52%   |
| New Zealand | 1        | 1.52%   |
| Netherlands | 1        | 1.52%   |
| Mexico      | 1        | 1.52%   |
| Indonesia   | 1        | 1.52%   |
| Hungary     | 1        | 1.52%   |
| Greece      | 1        | 1.52%   |
| Estonia     | 1        | 1.52%   |
| Colombia    | 1        | 1.52%   |
| Canada      | 1        | 1.52%   |
| Brazil      | 1        | 1.52%   |
| Australia   | 1        | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Houston             | 2        | 3.03%   |
| Ettingen            | 2        | 3.03%   |
| Volos               | 1        | 1.52%   |
| Voghera             | 1        | 1.52%   |
| Vilhelmina          | 1        | 1.52%   |
| Vasco da Gama       | 1        | 1.52%   |
| Vaidasoo            | 1        | 1.52%   |
| Tuglie              | 1        | 1.52%   |
| Tampere             | 1        | 1.52%   |
| Stevens Point       | 1        | 1.52%   |
| St Petersburg       | 1        | 1.52%   |
| Seelbach            | 1        | 1.52%   |
| San Diego           | 1        | 1.52%   |
| Rzeszów            | 1        | 1.52%   |
| Rosporden           | 1        | 1.52%   |
| Reno                | 1        | 1.52%   |
| Rathenow            | 1        | 1.52%   |
| Puebla City         | 1        | 1.52%   |
| Portland            | 1        | 1.52%   |
| Pompano Beach       | 1        | 1.52%   |
| Pila                | 1        | 1.52%   |
| Piedmont            | 1        | 1.52%   |
| Osnabrück          | 1        | 1.52%   |
| Normal              | 1        | 1.52%   |
| Narbonne            | 1        | 1.52%   |
| Moscow              | 1        | 1.52%   |
| Milwaukee           | 1        | 1.52%   |
| Mesquite            | 1        | 1.52%   |
| Maringá            | 1        | 1.52%   |
| Lodi                | 1        | 1.52%   |
| Krakow              | 1        | 1.52%   |
| Khabarovsk          | 1        | 1.52%   |
| Katonah             | 1        | 1.52%   |
| Kamiah              | 1        | 1.52%   |
| Herzogenrath        | 1        | 1.52%   |
| Helsinki            | 1        | 1.52%   |
| Granadilla de Abona | 1        | 1.52%   |
| Gouda               | 1        | 1.52%   |
| Göttingen          | 1        | 1.52%   |
| Freital             | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 26       | 46     | 20.31%  |
| Seagate                   | 24       | 32     | 18.75%  |
| WDC                       | 16       | 22     | 12.5%   |
| Kingston                  | 13       | 14     | 10.16%  |
| Toshiba                   | 7        | 8      | 5.47%   |
| SanDisk                   | 4        | 4      | 3.13%   |
| Hitachi                   | 4        | 5      | 3.13%   |
| PNY                       | 3        | 4      | 2.34%   |
| Crucial                   | 3        | 3      | 2.34%   |
| Corsair                   | 3        | 3      | 2.34%   |
| China                     | 3        | 3      | 2.34%   |
| Unknown                   | 2        | 3      | 1.56%   |
| Transcend                 | 2        | 2      | 1.56%   |
| GOODRAM                   | 2        | 2      | 1.56%   |
| Apacer                    | 2        | 2      | 1.56%   |
| A-DATA Technology         | 2        | 2      | 1.56%   |
| SPCC                      | 1        | 1      | 0.78%   |
| Phison Electronics        | 1        | 1      | 0.78%   |
| OCZ                       | 1        | 1      | 0.78%   |
| Micron/Crucial Technology | 1        | 1      | 0.78%   |
| Micron Technology         | 1        | 1      | 0.78%   |
| Maxtor                    | 1        | 1      | 0.78%   |
| JMicron Technology        | 1        | 1      | 0.78%   |
| Intel                     | 1        | 1      | 0.78%   |
| HGST                      | 1        | 1      | 0.78%   |
| External                  | 1        | 1      | 0.78%   |
| Avant                     | 1        | 1      | 0.78%   |
| Acer                      | 1        | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 4        | 2.58%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.94%   |
| SanDisk SDSSDA240G 240GB         | 3        | 1.94%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.94%   |
| Kingston SV300S37A240G 240GB SSD | 3        | 1.94%   |
| Toshiba DT01ACA100 1TB           | 2        | 1.29%   |
| Seagate ST3500413AS 500GB        | 2        | 1.29%   |
| Samsung SSD 980 PRO 1TB          | 2        | 1.29%   |
| Samsung SSD 970 PRO 512GB        | 2        | 1.29%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 1.29%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 1.29%   |
| Samsung SSD 870 EVO 500GB        | 2        | 1.29%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.29%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.29%   |
| Samsung SSD 850 EVO 1TB          | 2        | 1.29%   |
| Samsung SSD 840 Series 120GB     | 2        | 1.29%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.29%   |
| Corsair MP400 2TB                | 2        | 1.29%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.65%   |
| WDC WD800AAJS-60M0A0 80GB        | 1        | 0.65%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 1        | 0.65%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 0.65%   |
| WDC WD5002AALX-00J37A0 500GB     | 1        | 0.65%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.65%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.65%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.65%   |
| WDC WD3200AAKS-75L9A0 320GB      | 1        | 0.65%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.65%   |
| WDC WD20EZRX-22D8PB0 2TB         | 1        | 0.65%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.65%   |
| WDC WD10EZEX-75WN4A0 1TB         | 1        | 0.65%   |
| WDC WD10EZEX-60ZF5A0 1TB         | 1        | 0.65%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.65%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.65%   |
| WDC WD10EZEX-00BBHA0 1TB         | 1        | 0.65%   |
| WDC WD10EVDS-63U8B1 1TB          | 1        | 0.65%   |
| WDC WD10EADS-98M2B0 1TB          | 1        | 0.65%   |
| WDC WD10EADS-00M2B0 1TB          | 1        | 0.65%   |
| Unknown SD/MMC/MS PRO 2GB        | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 32     | 42.86%  |
| WDC                 | 14       | 20     | 25%     |
| Toshiba             | 7        | 8      | 12.5%   |
| Hitachi             | 4        | 5      | 7.14%   |
| Samsung Electronics | 3        | 3      | 5.36%   |
| Unknown             | 1        | 1      | 1.79%   |
| Maxtor              | 1        | 1      | 1.79%   |
| HGST                | 1        | 1      | 1.79%   |
| External            | 1        | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 25     | 35.19%  |
| Kingston            | 11       | 12     | 20.37%  |
| SanDisk             | 4        | 4      | 7.41%   |
| China               | 3        | 3      | 5.56%   |
| Transcend           | 2        | 2      | 3.7%    |
| PNY                 | 2        | 2      | 3.7%    |
| GOODRAM             | 2        | 2      | 3.7%    |
| Crucial             | 2        | 2      | 3.7%    |
| A-DATA Technology   | 2        | 2      | 3.7%    |
| WDC                 | 1        | 1      | 1.85%   |
| SPCC                | 1        | 1      | 1.85%   |
| OCZ                 | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 1      | 1.85%   |
| Avant               | 1        | 1      | 1.85%   |
| Apacer              | 1        | 1      | 1.85%   |
| Acer                | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 46       | 72     | 40%     |
| SSD     | 44       | 61     | 38.26%  |
| NVMe    | 23       | 31     | 20%     |
| Unknown | 2        | 3      | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 127    | 67.42%  |
| NVMe | 23       | 31     | 25.84%  |
| SAS  | 6        | 9      | 6.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 77     | 51.09%  |
| 0.51-1.0   | 26       | 31     | 28.26%  |
| 1.01-2.0   | 10       | 14     | 10.87%  |
| 3.01-4.0   | 3        | 3      | 3.26%   |
| 2.01-3.0   | 3        | 3      | 3.26%   |
| 4.01-10.0  | 2        | 4      | 2.17%   |
| 10.01-20.0 | 1        | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 24.24%  |
| 251-500        | 15       | 22.73%  |
| 1001-2000      | 9        | 13.64%  |
| More than 3000 | 6        | 9.09%   |
| 2001-3000      | 6        | 9.09%   |
| 501-1000       | 6        | 9.09%   |
| 51-100         | 5        | 7.58%   |
| 1-20           | 2        | 3.03%   |
| 21-50          | 1        | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 22.39%  |
| 21-50          | 13       | 19.4%   |
| 1-20           | 12       | 17.91%  |
| 51-100         | 8        | 11.94%  |
| 251-500        | 6        | 8.96%   |
| 1001-2000      | 6        | 8.96%   |
| 501-1000       | 3        | 4.48%   |
| More than 3000 | 2        | 2.99%   |
| 2001-3000      | 2        | 2.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 4.17%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 4.17%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 4.17%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 4.17%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 4.17%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 4.17%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 4.17%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 4.17%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 4.17%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 4.17%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 4.17%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 4.17%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 4.17%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 4.17%   |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB               | 1        | 1      | 4.17%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 4.17%   |
| China SSD 512GB                          | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 11     | 43.48%  |
| Samsung Electronics | 4        | 5      | 17.39%  |
| WDC                 | 3        | 3      | 13.04%  |
| Toshiba             | 1        | 1      | 4.35%   |
| Maxtor              | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 2      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| GOODRAM             | 1        | 1      | 4.35%   |
| China               | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 11     | 62.5%   |
| WDC     | 2        | 2      | 12.5%   |
| Toshiba | 1        | 1      | 6.25%   |
| Maxtor  | 1        | 1      | 6.25%   |
| Hitachi | 1        | 2      | 6.25%   |
| HGST    | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 18     | 68.18%  |
| SSD  | 7        | 8      | 31.82%  |

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
| Works    | 59       | 132    | 67.82%  |
| Malfunc  | 22       | 26     | 25.29%  |
| Detected | 6        | 9      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 47       | 48.45%  |
| AMD                         | 18       | 18.56%  |
| Samsung Electronics         | 12       | 12.37%  |
| Phison Electronics          | 6        | 6.19%   |
| ASMedia Technology          | 5        | 5.15%   |
| Micron/Crucial Technology   | 2        | 2.06%   |
| Kingston Technology Company | 2        | 2.06%   |
| ULi Electronics             | 1        | 1.03%   |
| SanDisk                     | 1        | 1.03%   |
| Nvidia                      | 1        | 1.03%   |
| Marvell Technology Group    | 1        | 1.03%   |
| LSI Logic / Symbios Logic   | 1        | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 5.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 4.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 4.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 4.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 4.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 3.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.52%   |
| Phison E12 NVMe Controller                                                     | 3        | 2.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 2.52%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 2.52%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 2.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 2.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.68%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 1.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 1.68%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.68%   |
| Intel 82Q35 Express PT IDER Controller                                         | 2        | 1.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 2        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.68%   |
| ULi M5229 IDE                                                                  | 1        | 0.84%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.84%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 0.84%   |
| Phison E7 NVMe Controller                                                      | 1        | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.84%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.84%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.84%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.84%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 1        | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57       | 58.76%  |
| NVMe | 23       | 23.71%  |
| IDE  | 13       | 13.4%   |
| RAID | 3        | 3.09%   |
| SCSI | 1        | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 47       | 71.21%  |
| AMD    | 19       | 28.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 4.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 4.55%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 3.03%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 3.03%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 3.03%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 3.03%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 1.52%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.52%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 1.52%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.52%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 1.52%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 1.52%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 1.52%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 1.52%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.52%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.52%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.52%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.52%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 1.52%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.52%   |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 1.52%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.52%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1        | 1.52%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1        | 1.52%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1        | 1.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.52%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.52%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.52%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.52%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.52%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 1        | 1.52%   |
| Intel 12th Gen Core i7-12700                | 1        | 1.52%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz     | 1        | 1.52%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 1.52%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores  | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 15.15%  |
| Intel Core i7           | 9        | 13.64%  |
| Intel Core i3           | 9        | 13.64%  |
| Intel Core 2 Duo        | 5        | 7.58%   |
| AMD Ryzen 7             | 5        | 7.58%   |
| Intel Xeon              | 4        | 6.06%   |
| AMD Ryzen 5             | 4        | 6.06%   |
| Other                   | 3        | 4.55%   |
| Intel Core i9           | 2        | 3.03%   |
| AMD Ryzen 3             | 2        | 3.03%   |
| AMD Athlon II X4        | 2        | 3.03%   |
| Intel Pentium Dual-Core | 1        | 1.52%   |
| Intel Pentium Dual      | 1        | 1.52%   |
| Intel Pentium           | 1        | 1.52%   |
| Intel Core M            | 1        | 1.52%   |
| Intel Celeron           | 1        | 1.52%   |
| AMD Ryzen Threadripper  | 1        | 1.52%   |
| AMD Ryzen 9             | 1        | 1.52%   |
| AMD Ryzen 5 PRO         | 1        | 1.52%   |
| AMD Phenom II X4        | 1        | 1.52%   |
| AMD Phenom              | 1        | 1.52%   |
| AMD Athlon              | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 37.88%  |
| 2      | 20       | 30.3%   |
| 8      | 9        | 13.64%  |
| 6      | 7        | 10.61%  |
| 12     | 4        | 6.06%   |
| 10     | 1        | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 98.48%  |
| 2      | 1        | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 62.12%  |
| 1      | 25       | 37.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 66       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 7        | 10.61%  |
| Unknown    | 7        | 10.61%  |
| 0x306c3    | 4        | 6.06%   |
| 0x206a7    | 4        | 6.06%   |
| 0x1067a    | 4        | 6.06%   |
| 0x906ed    | 3        | 4.55%   |
| 0x08701021 | 3        | 4.55%   |
| 0x08108109 | 3        | 4.55%   |
| 0x6fd      | 2        | 3.03%   |
| 0x506e3    | 2        | 3.03%   |
| 0x306f2    | 2        | 3.03%   |
| 0x20655    | 2        | 3.03%   |
| 0x0800820d | 2        | 3.03%   |
| 0x010000db | 2        | 3.03%   |
| 0xa0671    | 1        | 1.52%   |
| 0xa0655    | 1        | 1.52%   |
| 0xa0653    | 1        | 1.52%   |
| 0x906e9    | 1        | 1.52%   |
| 0x90672    | 1        | 1.52%   |
| 0x50654    | 1        | 1.52%   |
| 0x406c3    | 1        | 1.52%   |
| 0x40651    | 1        | 1.52%   |
| 0x306d4    | 1        | 1.52%   |
| 0x106e5    | 1        | 1.52%   |
| 0x106a5    | 1        | 1.52%   |
| 0x10676    | 1        | 1.52%   |
| 0x0a20120a | 1        | 1.52%   |
| 0x0a201016 | 1        | 1.52%   |
| 0x0a201009 | 1        | 1.52%   |
| 0x08301039 | 1        | 1.52%   |
| 0x08101016 | 1        | 1.52%   |
| 0x08001138 | 1        | 1.52%   |
| 0x01000083 | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 10       | 15.15%  |
| IvyBridge   | 7        | 10.61%  |
| Zen+        | 5        | 7.58%   |
| Penryn      | 5        | 7.58%   |
| Zen 3       | 4        | 6.06%   |
| Zen 2       | 4        | 6.06%   |
| SandyBridge | 4        | 6.06%   |
| KabyLake    | 4        | 6.06%   |
| K10         | 4        | 6.06%   |
| Skylake     | 3        | 4.55%   |
| Nehalem     | 3        | 4.55%   |
| Zen         | 2        | 3.03%   |
| Westmere    | 2        | 3.03%   |
| Core        | 2        | 3.03%   |
| CometLake   | 2        | 3.03%   |
| Unknown     | 2        | 3.03%   |
| Silvermont  | 1        | 1.52%   |
| Icelake     | 1        | 1.52%   |
| Broadwell   | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 36.49%  |
| Intel  | 25       | 33.78%  |
| AMD    | 22       | 29.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 4%      |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 4%      |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2        | 2.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 2.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 2.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 2.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.67%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 2.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 1.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.33%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.33%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.33%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1        | 1.33%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 1.33%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 1.33%   |
| Nvidia GF116 [GeForce GT 640 OEM]                                                        | 1        | 1.33%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 1.33%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 1.33%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 1.33%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 1.33%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 1.33%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.33%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.33%   |
| Intel HD Graphics 5300                                                                   | 1        | 1.33%   |
| Intel HD Graphics 530                                                                    | 1        | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.33%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 27       | 40.91%  |
| 1 x AMD     | 20       | 30.3%   |
| 1 x Intel   | 17       | 25.76%  |
| Intel + AMD | 2        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 68.18%  |
| Proprietary | 17       | 25.76%  |
| Unknown     | 4        | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 32.84%  |
| 1.01-2.0   | 12       | 17.91%  |
| 7.01-8.0   | 9        | 13.43%  |
| 0.51-1.0   | 9        | 13.43%  |
| 3.01-4.0   | 8        | 11.94%  |
| 8.01-16.0  | 3        | 4.48%   |
| 0.01-0.5   | 3        | 4.48%   |
| 2.01-3.0   | 1        | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 16.9%   |
| Dell                 | 8        | 11.27%  |
| Hewlett-Packard      | 6        | 8.45%   |
| Acer                 | 6        | 8.45%   |
| Goldstar             | 4        | 5.63%   |
| Fujitsu Siemens      | 4        | 5.63%   |
| Sony                 | 3        | 4.23%   |
| Lenovo               | 3        | 4.23%   |
| Eizo                 | 3        | 4.23%   |
| AOC                  | 3        | 4.23%   |
| Ancor Communications | 3        | 4.23%   |
| Medion               | 2        | 2.82%   |
| Iiyama               | 2        | 2.82%   |
| Vizio                | 1        | 1.41%   |
| Vestel Elektronik    | 1        | 1.41%   |
| SAC                  | 1        | 1.41%   |
| RTK                  | 1        | 1.41%   |
| Philips              | 1        | 1.41%   |
| Panasonic            | 1        | 1.41%   |
| NEC Computers        | 1        | 1.41%   |
| MSI                  | 1        | 1.41%   |
| MiTAC                | 1        | 1.41%   |
| Grundig              | 1        | 1.41%   |
| Gigabyte Technology  | 1        | 1.41%   |
| BenQ                 | 1        | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch     | 2        | 2.6%    |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 2.6%    |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 2        | 2.6%    |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 1.3%    |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 1.3%    |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                    | 1        | 1.3%    |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                  | 1        | 1.3%    |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                    | 1        | 1.3%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 1.3%    |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 1.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.3%    |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 1.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 1.3%    |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 1.3%    |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 1.3%    |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 1.3%    |
| Panasonic TV MEIA09B 1280x720 698x392mm 31.5-inch                     | 1        | 1.3%    |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 1.3%    |
| MSI G27C6 MSI5CA9 1920x1080 600x340mm 27.2-inch                       | 1        | 1.3%    |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                       | 1        | 1.3%    |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                   | 1        | 1.3%    |
| Lenovo T22v-10 LEN61BB 1920x1080 476x267mm 21.5-inch                  | 1        | 1.3%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1        | 1.3%    |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                   | 1        | 1.3%    |
| Iiyama PLE430 IVM46B4 1280x1024 340x270mm 17.1-inch                   | 1        | 1.3%    |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 1        | 1.3%    |
| Hewlett-Packard ZR2330w HWP3069 1920x1080 509x286mm 23.0-inch         | 1        | 1.3%    |
| Hewlett-Packard X27q HPN3725 2560x1440 597x336mm 27.0-inch            | 1        | 1.3%    |
| Hewlett-Packard X27q HPN3724 2560x1440 597x336mm 27.0-inch            | 1        | 1.3%    |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 1.3%    |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch             | 1        | 1.3%    |
| Hewlett-Packard L1940T HWP2683 1280x1024 376x301mm 19.0-inch          | 1        | 1.3%    |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch            | 1        | 1.3%    |
| Grundig WXGA GRU4448 1600x1200                                        | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 38.57%  |
| 2560x1440 (QHD)    | 9        | 12.86%  |
| 1680x1050 (WSXGA+) | 7        | 10%     |
| 1280x1024 (SXGA)   | 7        | 10%     |
| 3840x2160 (4K)     | 5        | 7.14%   |
| 3440x1440          | 2        | 2.86%   |
| 1920x1200 (WUXGA)  | 2        | 2.86%   |
| 1440x900 (WXGA+)   | 2        | 2.86%   |
| 1366x768 (WXGA)    | 2        | 2.86%   |
| 1280x720 (HD)      | 2        | 2.86%   |
| 2560x1600          | 1        | 1.43%   |
| 2560x1080          | 1        | 1.43%   |
| 1600x900 (HD+)     | 1        | 1.43%   |
| 1360x768           | 1        | 1.43%   |
| 1024x768 (XGA)     | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 12       | 17.14%  |
| 23      | 12       | 17.14%  |
| 31      | 8        | 11.43%  |
| 22      | 7        | 10%     |
| 24      | 6        | 8.57%   |
| 21      | 4        | 5.71%   |
| 34      | 3        | 4.29%   |
| 19      | 3        | 4.29%   |
| 17      | 3        | 4.29%   |
| 18      | 2        | 2.86%   |
| 15      | 2        | 2.86%   |
| 84      | 1        | 1.43%   |
| 54      | 1        | 1.43%   |
| 47      | 1        | 1.43%   |
| 40      | 1        | 1.43%   |
| 26      | 1        | 1.43%   |
| 20      | 1        | 1.43%   |
| 16      | 1        | 1.43%   |
| Unknown | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 28       | 41.18%  |
| 401-500     | 14       | 20.59%  |
| 601-700     | 8        | 11.76%  |
| 351-400     | 5        | 7.35%   |
| 301-350     | 5        | 7.35%   |
| 701-800     | 3        | 4.41%   |
| 1001-1500   | 2        | 2.94%   |
| 801-900     | 1        | 1.47%   |
| 1501-2000   | 1        | 1.47%   |
| Unknown     | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 45       | 66.18%  |
| 16/10 | 11       | 16.18%  |
| 5/4   | 7        | 10.29%  |
| 21/9  | 3        | 4.41%   |
| 4/3   | 1        | 1.47%   |
| 3/2   | 1        | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 33.33%  |
| 301-350        | 12       | 17.39%  |
| 351-500        | 11       | 15.94%  |
| 151-200        | 8        | 11.59%  |
| 251-300        | 4        | 5.8%    |
| 141-150        | 3        | 4.35%   |
| More than 1000 | 2        | 2.9%    |
| 501-1000       | 2        | 2.9%    |
| 121-130        | 1        | 1.45%   |
| 101-110        | 1        | 1.45%   |
| 91-100         | 1        | 1.45%   |
| Unknown        | 1        | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 48       | 72.73%  |
| 101-120 | 12       | 18.18%  |
| 1-50    | 4        | 6.06%   |
| 121-160 | 1        | 1.52%   |
| Unknown | 1        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 75.76%  |
| 2     | 12       | 18.18%  |
| 3     | 2        | 3.03%   |
| 0     | 2        | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 36       | 38.3%   |
| Intel                 | 29       | 30.85%  |
| Qualcomm Atheros      | 7        | 7.45%   |
| Ralink Technology     | 4        | 4.26%   |
| TP-Link               | 3        | 3.19%   |
| Broadcom              | 3        | 3.19%   |
| Ralink                | 2        | 2.13%   |
| Xiaomi                | 1        | 1.06%   |
| OPPO Electronics      | 1        | 1.06%   |
| Nvidia                | 1        | 1.06%   |
| Mercucys              | 1        | 1.06%   |
| Linksys               | 1        | 1.06%   |
| JMicron Technology    | 1        | 1.06%   |
| Edimax Technology     | 1        | 1.06%   |
| Broadcom Limited      | 1        | 1.06%   |
| AVM                   | 1        | 1.06%   |
| Aquantia              | 1        | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 26.21%  |
| Intel I211 Gigabit Network Connection                             | 4        | 3.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.88%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.91%   |
| Intel Ethernet Controller I225-V                                  | 3        | 2.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.94%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.94%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.94%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.94%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.94%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.97%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.97%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.97%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.97%   |
| Realtek B1610311068                                               | 1        | 0.97%   |
| Realtek 802.11ac NIC                                              | 1        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.97%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 0.97%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.97%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 1        | 0.97%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.97%   |
| Mercucys MW300UM RTL8192EU wifi                                   | 1        | 0.97%   |
| Linksys WUSB6300 V2                                               | 1        | 0.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.97%   |
| Intel Wireless 8260                                               | 1        | 0.97%   |
| Intel Wireless 7265                                               | 1        | 0.97%   |
| Intel Wireless 7260                                               | 1        | 0.97%   |
| Intel Wireless 3160                                               | 1        | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 29.03%  |
| Intel                 | 6        | 19.35%  |
| Ralink Technology     | 4        | 12.9%   |
| TP-Link               | 3        | 9.68%   |
| Ralink                | 2        | 6.45%   |
| Qualcomm Atheros      | 1        | 3.23%   |
| Mercucys              | 1        | 3.23%   |
| Linksys               | 1        | 3.23%   |
| Edimax Technology     | 1        | 3.23%   |
| Broadcom Limited      | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |
| AVM                   | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                            | 3        | 9.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 2        | 6.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 2        | 6.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 3.23%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 3.23%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 3.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 3.23%   |
| Realtek B1610311068                                        | 1        | 3.23%   |
| Realtek 802.11ac NIC                                       | 1        | 3.23%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 3.23%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1        | 3.23%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 3.23%   |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 3.23%   |
| Linksys WUSB6300 V2                                        | 1        | 3.23%   |
| Intel Wireless 8260                                        | 1        | 3.23%   |
| Intel Wireless 7265                                        | 1        | 3.23%   |
| Intel Wireless 7260                                        | 1        | 3.23%   |
| Intel Wireless 3160                                        | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 3.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 3.23%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 3.23%   |
| AVM FRITZ!WLAN AC 860                                      | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 30       | 42.86%  |
| Intel                 | 27       | 38.57%  |
| Qualcomm Atheros      | 6        | 8.57%   |
| Broadcom              | 2        | 2.86%   |
| Xiaomi                | 1        | 1.43%   |
| OPPO Electronics      | 1        | 1.43%   |
| Nvidia                | 1        | 1.43%   |
| JMicron Technology    | 1        | 1.43%   |
| Aquantia              | 1        | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 37.5%   |
| Intel I211 Gigabit Network Connection                             | 4        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 3        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.78%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.39%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 1        | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 1.39%   |
| Intel Ethernet Connection I218-V                                  | 1        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.39%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.39%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.39%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 69.47%  |
| WiFi     | 29       | 30.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 71.64%  |
| WiFi     | 19       | 28.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 71.21%  |
| 2     | 16       | 24.24%  |
| 3     | 3        | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 50       | 75.76%  |
| Yes  | 16       | 24.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 33.33%  |
| Cambridge Silicon Radio | 4        | 33.33%  |
| ASUSTek Computer        | 2        | 16.67%  |
| Foxconn / Hon Hai       | 1        | 8.33%   |
| Apple                   | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4        | 33.33%  |
| Intel Bluetooth wireless interface                    | 3        | 25%     |
| Intel Bluetooth Device                                | 1        | 8.33%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 8.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 8.33%   |
| Apple Bluetooth USB Host Controller                   | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 45       | 37.5%   |
| AMD                     | 28       | 23.33%  |
| Nvidia                  | 25       | 20.83%  |
| Creative Labs           | 5        | 4.17%   |
| C-Media Electronics     | 5        | 4.17%   |
| ROCCAT                  | 2        | 1.67%   |
| Unknown                 | 1        | 0.83%   |
| Texas Instruments       | 1        | 0.83%   |
| TerraTec Electronic     | 1        | 0.83%   |
| Schiit Audio            | 1        | 0.83%   |
| Razer USA               | 1        | 0.83%   |
| JMTek                   | 1        | 0.83%   |
| GYROCOM C&C             | 1        | 0.83%   |
| GN Netcom               | 1        | 0.83%   |
| Generalplus Technology  | 1        | 0.83%   |
| BEHRINGER International | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 6        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 5        | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5        | 3.62%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 5        | 3.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 2.9%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 4        | 2.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 4        | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 2.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 2.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 3        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 3        | 2.17%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 3        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 2.17%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 3        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 2.17%   |
| ROCCAT Khan AIMO                                                                                | 2        | 1.45%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                      | 2        | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2        | 1.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 2        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 1.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 2        | 1.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 1.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2        | 1.45%   |
| Unknown Realtek USB Audio Rear                                                                  | 1        | 0.72%   |
| Unknown Realtek USB Audio Front                                                                 | 1        | 0.72%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.72%   |
| TerraTec Electronic Aureon Dual USB                                                             | 1        | 0.72%   |
| Schiit Audio I'm Fulla Schiit                                                                   | 1        | 0.72%   |
| Razer USA Kraken Tournament Edition                                                             | 1        | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                              | 1        | 0.72%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 1        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 15.28%  |
| Unknown             | 10       | 13.89%  |
| Samsung Electronics | 10       | 13.89%  |
| Corsair             | 10       | 13.89%  |
| G.Skill             | 6        | 8.33%   |
| SK hynix            | 4        | 5.56%   |
| Ramaxel Technology  | 4        | 5.56%   |
| Nanya Technology    | 3        | 4.17%   |
| Crucial             | 3        | 4.17%   |
| A-DATA Technology   | 3        | 4.17%   |
| Transcend           | 2        | 2.78%   |
| Micron Technology   | 2        | 2.78%   |
| Patriot             | 1        | 1.39%   |
| Elpida              | 1        | 1.39%   |
| Apacer              | 1        | 1.39%   |
| Unknown             | 1        | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 4        | 5.26%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                | 2        | 2.63%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s   | 2        | 2.63%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 2        | 2.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.32%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 1        | 1.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s               | 1        | 1.32%   |
| Unknown RAM Module 4GB DIMM 667MT/s                     | 1        | 1.32%   |
| Unknown RAM Module 4GB DIMM                             | 1        | 1.32%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 1.32%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 1.32%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR 2048MT/s      | 1        | 1.32%   |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s      | 1        | 1.32%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 1.32%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.32%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 1.32%   |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s | 1        | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1        | 1.32%   |
| Samsung RAM M393B5170DZ1-CF8 4GB DIMM DDR3 1066MT/s     | 1        | 1.32%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 1.32%   |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2666MT/s    | 1        | 1.32%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s    | 1        | 1.32%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 1.32%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s     | 1        | 1.32%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s     | 1        | 1.32%   |
| Samsung RAM M378A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s     | 1        | 1.32%   |
| Samsung RAM DDR3 1600 8G 8GB DIMM DDR3 1333MT/s         | 1        | 1.32%   |
| Ramaxel RAM RMUA5200ME78HAF-3200 8GB DIMM DDR4 3200MT/s | 1        | 1.32%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 1        | 1.32%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.32%   |
| Ramaxel RAM RMR5030MN68F9F160 4GB DIMM DDR3 1333MT/s    | 1        | 1.32%   |
| Ramaxel RAM RMR5030ME68F9F160 4GB DIMM DDR3 1333MT/s    | 1        | 1.32%   |
| Ramaxel RAM RMR5030KD68F9F160 4GB DIMM DDR3 1333MT/s    | 1        | 1.32%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s     | 1        | 1.32%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s      | 1        | 1.32%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.32%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.32%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s              | 1        | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 30       | 46.15%  |
| DDR3    | 24       | 36.92%  |
| DDR2    | 4        | 6.15%   |
| Unknown | 4        | 6.15%   |
| SDRAM   | 3        | 4.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 59       | 92.19%  |
| SODIMM | 5        | 7.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 22       | 31.88%  |
| 8192  | 19       | 27.54%  |
| 16384 | 11       | 15.94%  |
| 2048  | 11       | 15.94%  |
| 32768 | 4        | 5.8%    |
| 1024  | 2        | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 14.71%  |
| 1333    | 10       | 14.71%  |
| 3600    | 8        | 11.76%  |
| 3200    | 6        | 8.82%   |
| 2133    | 5        | 7.35%   |
| 2667    | 4        | 5.88%   |
| 3400    | 3        | 4.41%   |
| 2666    | 3        | 4.41%   |
| 800     | 3        | 4.41%   |
| 667     | 3        | 4.41%   |
| 2048    | 2        | 2.94%   |
| 333     | 2        | 2.94%   |
| Unknown | 2        | 2.94%   |
| 3466    | 1        | 1.47%   |
| 3266    | 1        | 1.47%   |
| 2933    | 1        | 1.47%   |
| 2000    | 1        | 1.47%   |
| 1866    | 1        | 1.47%   |
| 1800    | 1        | 1.47%   |
| 1066    | 1        | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 75%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Canon MF641C        | 2        | 50%     |
| Canon MG5700 series | 1        | 25%     |
| Brother MFC-7340    | 1        | 25%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 42.86%  |
| Microsoft                     | 2        | 14.29%  |
| Chicony Electronics           | 2        | 14.29%  |
| Sunplus Innovation Technology | 1        | 7.14%   |
| Sonix Technology              | 1        | 7.14%   |
| Generalplus Technology        | 1        | 7.14%   |
| Arkmicro Technologies         | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Microsoft LifeCam HD-3000         | 2        | 14.29%  |
| Logitech Webcam C930e             | 2        | 14.29%  |
| Logitech Webcam C270              | 2        | 14.29%  |
| Sunplus HD 720P webcam            | 1        | 7.14%   |
| Sonix USB Camera                  | 1        | 7.14%   |
| Logitech Webcam C110              | 1        | 7.14%   |
| Logitech HD Webcam C615           | 1        | 7.14%   |
| Generalplus GENERAL WEBCAM        | 1        | 7.14%   |
| Chicony HP Prem AF Webcam KQ245AA | 1        | 7.14%   |
| Chicony HD Webcam                 | 1        | 7.14%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

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
| 0     | 55       | 83.33%  |
| 1     | 10       | 15.15%  |
| 2     | 1        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 33.33%  |
| Unassigned class         | 3        | 25%     |
| Net/wireless             | 2        | 16.67%  |
| Fingerprint reader       | 1        | 8.33%   |
| Dvb card                 | 1        | 8.33%   |
| Communication controller | 1        | 8.33%   |

