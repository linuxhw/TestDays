Kubuntu 23.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

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

Total: 102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG B550 GAMING PLUS        | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Dell          | 0XPDFK A01                  | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| MSI           | MAG B550M BAZOOKA           | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| MSI           | B550-A PRO                  | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| ASRock        | X570 Steel Legend           | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASRock        | X570 Steel Legend           | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| ASRock        | X370 Taichi                 | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Dell          | 0HY9JP A00                  | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-K                | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 158A                        | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 158A                        | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| Google        | Zako                        | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Acer          | Aspire X3990                | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| ASRock        | B560M Pro4                  | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | 83E9                        | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Gigabyte      | X570S UD                    | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| MSI           | B360M MORTAR TITANIUM       | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | PRIME H510M-K               | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| Gigabyte      | B550 AORUS PRO              | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Gigabyte      | X570S UD                    | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| MSI           | H81M-P32                    | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| ASUSTek       | H81M-A                      | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Alienware     | 04VWF2 A00                  | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| ASRock        | X99 Extreme6/ac             | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | 3397                        | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Biostar       | AM1MHP                      | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Gigabyte      | H87-HD3                     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| HP            | 828A                        | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.2.0-20-generic       | 17       | 21.52%  |
| 6.2.0-27-generic       | 14       | 17.72%  |
| 6.2.0-24-generic       | 8        | 10.13%  |
| 6.2.0-26-generic       | 6        | 7.59%   |
| 6.2.0-23-generic       | 6        | 7.59%   |
| 6.2.0-25-generic       | 5        | 6.33%   |
| 6.2.0-31-generic       | 4        | 5.06%   |
| 6.2.0-32-generic       | 3        | 3.8%    |
| 6.2.0-1003-lowlatency  | 3        | 3.8%    |
| 6.4.6-060406-generic   | 1        | 1.27%   |
| 6.4.3-1-liquorix-amd64 | 1        | 1.27%   |
| 6.4.1-2-liquorix-amd64 | 1        | 1.27%   |
| 6.4.0-060400-generic   | 1        | 1.27%   |
| 6.3.5-060305-generic   | 1        | 1.27%   |
| 6.3.10                 | 1        | 1.27%   |
| 6.2.5-060205-generic   | 1        | 1.27%   |
| 6.2.0-1009-lowlatency  | 1        | 1.27%   |
| 6.2.0-1008-lowlatency  | 1        | 1.27%   |
| 6.2.0-1007-lowlatency  | 1        | 1.27%   |
| 6.1.0-16-generic       | 1        | 1.27%   |
| 5.19.0-28-generic      | 1        | 1.27%   |
| 5.19.0-1023-lowlatency | 1        | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 69       | 87.34%  |
| 5.19.0  | 2        | 2.53%   |
| 6.4.6   | 1        | 1.27%   |
| 6.4.3   | 1        | 1.27%   |
| 6.4.1   | 1        | 1.27%   |
| 6.4.0   | 1        | 1.27%   |
| 6.3.5   | 1        | 1.27%   |
| 6.3.10  | 1        | 1.27%   |
| 6.2.5   | 1        | 1.27%   |
| 6.1.0   | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 70       | 88.61%  |
| 6.4     | 4        | 5.06%   |
| 6.3     | 2        | 2.53%   |
| 5.19    | 2        | 2.53%   |
| 6.1     | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 78       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 75       | 96.15%  |
| KDE  | 3        | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 63       | 80.77%  |
| Wayland | 14       | 17.95%  |
| Tty     | 1        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 46       | 58.23%  |
| Unknown | 30       | 37.97%  |
| GDM3    | 2        | 2.53%   |
| LightDM | 1        | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 35       | 44.87%  |
| de_DE | 10       | 12.82%  |
| en_GB | 7        | 8.97%   |
| ru_RU | 4        | 5.13%   |
| fr_FR | 4        | 5.13%   |
| pt_BR | 3        | 3.85%   |
| it_IT | 2        | 2.56%   |
| C     | 2        | 2.56%   |
| zh_TW | 1        | 1.28%   |
| sv_SE | 1        | 1.28%   |
| pl_PL | 1        | 1.28%   |
| fr_BE | 1        | 1.28%   |
| es_MX | 1        | 1.28%   |
| es_CO | 1        | 1.28%   |
| es_CL | 1        | 1.28%   |
| en_IN | 1        | 1.28%   |
| en_IL | 1        | 1.28%   |
| en_CA | 1        | 1.28%   |
| da_DK | 1        | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 46       | 58.97%  |
| EFI  | 32       | 41.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 54       | 69.23%  |
| Tmpfs   | 16       | 20.51%  |
| Btrfs   | 6        | 7.69%   |
| Overlay | 1        | 1.28%   |
| F2fs    | 1        | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 46       | 58.23%  |
| Unknown | 29       | 36.71%  |
| MBR     | 4        | 5.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 78.21%  |
| Yes       | 17       | 21.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 66.67%  |
| Yes       | 26       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 22       | 28.21%  |
| Gigabyte Technology | 16       | 20.51%  |
| MSI                 | 12       | 15.38%  |
| ASRock              | 6        | 7.69%   |
| Intel               | 3        | 3.85%   |
| Hewlett-Packard     | 3        | 3.85%   |
| Fujitsu             | 2        | 2.56%   |
| Dell                | 2        | 2.56%   |
| Seco                | 1        | 1.28%   |
| Pegatron            | 1        | 1.28%   |
| Lenovo              | 1        | 1.28%   |
| Huanan              | 1        | 1.28%   |
| Google              | 1        | 1.28%   |
| Gateway             | 1        | 1.28%   |
| Foxconn             | 1        | 1.28%   |
| Biostar             | 1        | 1.28%   |
| BESSTAR Tech        | 1        | 1.28%   |
| Alienware           | 1        | 1.28%   |
| Acer                | 1        | 1.28%   |
| Unknown             | 1        | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C95                            | 2        | 2.56%   |
| MSI MS-7C56                            | 2        | 2.56%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 2.56%   |
| ASUS TUF Gaming B550-PLUS              | 2        | 2.56%   |
| Seco C40                               | 1        | 1.28%   |
| Pegatron 520-1000nl                    | 1        | 1.28%   |
| MSI MS-7D75                            | 1        | 1.28%   |
| MSI MS-7D74                            | 1        | 1.28%   |
| MSI MS-7D17                            | 1        | 1.28%   |
| MSI MS-7B86                            | 1        | 1.28%   |
| MSI MS-7B23                            | 1        | 1.28%   |
| MSI MS-7A32                            | 1        | 1.28%   |
| MSI MS-7846                            | 1        | 1.28%   |
| MSI MS-7693                            | 1        | 1.28%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS | 1        | 1.28%   |
| Intel SHARKBAY                         | 1        | 1.28%   |
| Intel H61                              | 1        | 1.28%   |
| Intel H55                              | 1        | 1.28%   |
| Huanan X99-F8 GAMING V5.0              | 1        | 1.28%   |
| HP EliteDesk 705 G4 DM 35W (TAA)       | 1        | 1.28%   |
| HP Compaq Elite 8300 SFF               | 1        | 1.28%   |
| HP 870-119                             | 1        | 1.28%   |
| Google Zako                            | 1        | 1.28%   |
| Gigabyte Z390 M GAMING                 | 1        | 1.28%   |
| Gigabyte X570S UD                      | 1        | 1.28%   |
| Gigabyte X570S AORUS ELITE AX          | 1        | 1.28%   |
| Gigabyte X470 AORUS ULTRA GAMING       | 1        | 1.28%   |
| Gigabyte H87-HD3                       | 1        | 1.28%   |
| Gigabyte GA-MA770-US3                  | 1        | 1.28%   |
| Gigabyte B650M AORUS ELITE AX          | 1        | 1.28%   |
| Gigabyte B550 GAMING X V2              | 1        | 1.28%   |
| Gigabyte B550 AORUS PRO                | 1        | 1.28%   |
| Gigabyte B365M H                       | 1        | 1.28%   |
| Gigabyte B365M D3H                     | 1        | 1.28%   |
| Gigabyte B360M-HD3                     | 1        | 1.28%   |
| Gigabyte A320M-S2H                     | 1        | 1.28%   |
| Gigabyte 7200-5143A                    | 1        | 1.28%   |
| Gateway DX4860                         | 1        | 1.28%   |
| Fujitsu ESPRIMO D538                   | 1        | 1.28%   |
| Fujitsu D3222-B1                       | 1        | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 10       | 12.82%  |
| Gigabyte B550         | 4        | 5.13%   |
| ASUS ROG              | 4        | 5.13%   |
| ASUS TUF              | 3        | 3.85%   |
| MSI MS-7C95           | 2        | 2.56%   |
| MSI MS-7C56           | 2        | 2.56%   |
| Gigabyte X570S        | 2        | 2.56%   |
| Gigabyte B365M        | 2        | 2.56%   |
| Seco C40              | 1        | 1.28%   |
| Pegatron 520-1000nl   | 1        | 1.28%   |
| MSI MS-7D75           | 1        | 1.28%   |
| MSI MS-7D74           | 1        | 1.28%   |
| MSI MS-7D17           | 1        | 1.28%   |
| MSI MS-7B86           | 1        | 1.28%   |
| MSI MS-7B23           | 1        | 1.28%   |
| MSI MS-7A32           | 1        | 1.28%   |
| MSI MS-7846           | 1        | 1.28%   |
| MSI MS-7693           | 1        | 1.28%   |
| Lenovo IdeaCentre     | 1        | 1.28%   |
| Intel SHARKBAY        | 1        | 1.28%   |
| Intel H61             | 1        | 1.28%   |
| Intel H55             | 1        | 1.28%   |
| Huanan X99-F8         | 1        | 1.28%   |
| HP EliteDesk          | 1        | 1.28%   |
| HP Compaq             | 1        | 1.28%   |
| HP 870-119            | 1        | 1.28%   |
| Google Zako           | 1        | 1.28%   |
| Gigabyte Z390         | 1        | 1.28%   |
| Gigabyte X470         | 1        | 1.28%   |
| Gigabyte H87-HD3      | 1        | 1.28%   |
| Gigabyte GA-MA770-US3 | 1        | 1.28%   |
| Gigabyte B650M        | 1        | 1.28%   |
| Gigabyte B360M-HD3    | 1        | 1.28%   |
| Gigabyte A320M-S2H    | 1        | 1.28%   |
| Gigabyte 7200-5143A   | 1        | 1.28%   |
| Gateway DX4860        | 1        | 1.28%   |
| Fujitsu ESPRIMO       | 1        | 1.28%   |
| Fujitsu D3222-B1      | 1        | 1.28%   |
| Foxconn H67M-S        | 1        | 1.28%   |
| Dell Precision        | 1        | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 15       | 19.23%  |
| 2019 | 12       | 15.38%  |
| 2018 | 8        | 10.26%  |
| 2021 | 7        | 8.97%   |
| 2011 | 7        | 8.97%   |
| 2022 | 6        | 7.69%   |
| 2017 | 6        | 7.69%   |
| 2014 | 3        | 3.85%   |
| 2013 | 3        | 3.85%   |
| 2012 | 3        | 3.85%   |
| 2023 | 2        | 2.56%   |
| 2016 | 2        | 2.56%   |
| 2009 | 2        | 2.56%   |
| 2015 | 1        | 1.28%   |
| 2010 | 1        | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 78       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 77       | 98.72%  |
| Enabled  | 1        | 1.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 98.72%  |
| Yes  | 1        | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 23       | 29.49%  |
| 16.01-24.0  | 19       | 24.36%  |
| 4.01-8.0    | 10       | 12.82%  |
| 8.01-16.0   | 10       | 12.82%  |
| 64.01-256.0 | 7        | 8.97%   |
| 24.01-32.0  | 5        | 6.41%   |
| 3.01-4.0    | 4        | 5.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 26       | 32.5%   |
| 2.01-3.0  | 17       | 21.25%  |
| 3.01-4.0  | 14       | 17.5%   |
| 1.01-2.0  | 12       | 15%     |
| 8.01-16.0 | 11       | 13.75%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 25.64%  |
| 3      | 17       | 21.79%  |
| 4      | 16       | 20.51%  |
| 1      | 15       | 19.23%  |
| 5      | 5        | 6.41%   |
| 7      | 2        | 2.56%   |
| 6      | 2        | 2.56%   |
| 8      | 1        | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 70.51%  |
| Yes       | 23       | 29.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 52.56%  |
| Yes       | 37       | 47.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 61.54%  |
| Yes       | 30       | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 18       | 23.08%  |
| Germany      | 12       | 15.38%  |
| UK           | 8        | 10.26%  |
| France       | 5        | 6.41%   |
| Russia       | 4        | 5.13%   |
| Sweden       | 3        | 3.85%   |
| Brazil       | 3        | 3.85%   |
| Switzerland  | 2        | 2.56%   |
| Serbia       | 2        | 2.56%   |
| Poland       | 2        | 2.56%   |
| Netherlands  | 2        | 2.56%   |
| Canada       | 2        | 2.56%   |
| Taiwan       | 1        | 1.28%   |
| Spain        | 1        | 1.28%   |
| Saudi Arabia | 1        | 1.28%   |
| Romania      | 1        | 1.28%   |
| Portugal     | 1        | 1.28%   |
| Mexico       | 1        | 1.28%   |
| Kazakhstan   | 1        | 1.28%   |
| Italy        | 1        | 1.28%   |
| Israel       | 1        | 1.28%   |
| Indonesia    | 1        | 1.28%   |
| India        | 1        | 1.28%   |
| Denmark      | 1        | 1.28%   |
| Colombia     | 1        | 1.28%   |
| Chile        | 1        | 1.28%   |
| Belgium      | 1        | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| London           | 3        | 3.85%   |
| Virginia Beach   | 2        | 2.56%   |
| Oberburg         | 2        | 2.56%   |
| Hamburg          | 2        | 2.56%   |
| Arzamas          | 2        | 2.56%   |
| Wiesmoor         | 1        | 1.28%   |
| West Valley      | 1        | 1.28%   |
| Weilmuenster     | 1        | 1.28%   |
| Warsaw           | 1        | 1.28%   |
| Vaggeryd         | 1        | 1.28%   |
| Uelversheim      | 1        | 1.28%   |
| Tilburg          | 1        | 1.28%   |
| The Hague        | 1        | 1.28%   |
| Taichung         | 1        | 1.28%   |
| Sutton           | 1        | 1.28%   |
| Sundsvall        | 1        | 1.28%   |
| Strasbourg       | 1        | 1.28%   |
| Stone Mountain   | 1        | 1.28%   |
| Simpsonville     | 1        | 1.28%   |
| Sibiu            | 1        | 1.28%   |
| Sherbrooke       | 1        | 1.28%   |
| Sao Paulo        | 1        | 1.28%   |
| Santiago         | 1        | 1.28%   |
| San Jose         | 1        | 1.28%   |
| San Francisco    | 1        | 1.28%   |
| Rzeszów         | 1        | 1.28%   |
| Porto Alegre     | 1        | 1.28%   |
| Portimao         | 1        | 1.28%   |
| Pasco            | 1        | 1.28%   |
| Paris            | 1        | 1.28%   |
| Pančevo         | 1        | 1.28%   |
| Orbassano        | 1        | 1.28%   |
| Oberursel        | 1        | 1.28%   |
| Novato           | 1        | 1.28%   |
| Nizhniy Novgorod | 1        | 1.28%   |
| Niebla           | 1        | 1.28%   |
| Minneapolis      | 1        | 1.28%   |
| Middlesbrough    | 1        | 1.28%   |
| Metepec          | 1        | 1.28%   |
| Marshalltown     | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 28       | 46     | 15.56%  |
| Seagate                     | 26       | 42     | 14.44%  |
| WDC                         | 25       | 31     | 13.89%  |
| SanDisk                     | 11       | 13     | 6.11%   |
| Kingston                    | 9        | 12     | 5%      |
| Crucial                     | 9        | 12     | 5%      |
| Toshiba                     | 7        | 7      | 3.89%   |
| Phison Electronics          | 4        | 4      | 2.22%   |
| Kingston Technology Company | 4        | 5      | 2.22%   |
| Hitachi                     | 4        | 4      | 2.22%   |
| HGST                        | 4        | 4      | 2.22%   |
| A-DATA Technology           | 4        | 4      | 2.22%   |
| Silicon Motion              | 3        | 3      | 1.67%   |
| PNY                         | 3        | 3      | 1.67%   |
| Intel                       | 3        | 3      | 1.67%   |
| SPCC                        | 2        | 6      | 1.11%   |
| Micron/Crucial Technology   | 2        | 4      | 1.11%   |
| Maxtor                      | 2        | 2      | 1.11%   |
| Hewlett-Packard             | 2        | 3      | 1.11%   |
| Corsair                     | 2        | 2      | 1.11%   |
| China                       | 2        | 2      | 1.11%   |
| ADATA Technology            | 2        | 2      | 1.11%   |
| Vaseky                      | 1        | 1      | 0.56%   |
| Unknown                     | 1        | 1      | 0.56%   |
| Transcend                   | 1        | 1      | 0.56%   |
| Team                        | 1        | 1      | 0.56%   |
| Smartbuy                    | 1        | 1      | 0.56%   |
| S3+                         | 1        | 1      | 0.56%   |
| Realtek Semiconductor       | 1        | 1      | 0.56%   |
| PHD 3.0                     | 1        | 1      | 0.56%   |
| Patriot                     | 1        | 1      | 0.56%   |
| Neo                         | 1        | 1      | 0.56%   |
| Micron Technology           | 1        | 1      | 0.56%   |
| Lexar                       | 1        | 1      | 0.56%   |
| Intenso                     | 1        | 1      | 0.56%   |
| INNOVATION IT               | 1        | 1      | 0.56%   |
| HS-SSD-E100                 | 1        | 1      | 0.56%   |
| Hoodisk                     | 1        | 1      | 0.56%   |
| Gigabyte Technology         | 1        | 1      | 0.56%   |
| Emtec                       | 1        | 2      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB                                  | 4        | 1.83%   |
| Samsung SSD 860 EVO 500GB                                       | 4        | 1.83%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 3        | 1.38%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 3        | 1.38%   |
| Samsung SSD 980 1TB                                             | 3        | 1.38%   |
| Samsung SSD 850 EVO 250GB                                       | 3        | 1.38%   |
| Phison PS5013 E13 NVMe Controller 512GB                         | 3        | 1.38%   |
| Kingston SA400S37480G 480GB SSD                                 | 3        | 1.38%   |
| WDC WD5000AAKX-60U6AA0 500GB                                    | 2        | 0.92%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 2        | 0.92%   |
| Sandisk WD_BLACK SN850X 4000GB                                  | 2        | 0.92%   |
| Sandisk WD Black SN850 256GB                                    | 2        | 0.92%   |
| Samsung SSD 980 PRO 2TB                                         | 2        | 0.92%   |
| Samsung SSD 980 PRO 1TB                                         | 2        | 0.92%   |
| Samsung SSD 870 QVO 2TB                                         | 2        | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB             | 2        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB           | 2        | 0.92%   |
| Samsung HD103SI 1TB                                             | 2        | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 2        | 0.92%   |
| Kingston Company SNV2S1000G 1TB                                 | 2        | 0.92%   |
| Kingston SA400S37120G 120GB SSD                                 | 2        | 0.92%   |
| Hitachi HDP725050GLA360 500GB                                   | 2        | 0.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 2        | 0.92%   |
| WDC WUH721818ALE6L4 18TB                                        | 1        | 0.46%   |
| WDC WDS500G2B0A 500GB SSD                                       | 1        | 0.46%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                                  | 1        | 0.46%   |
| WDC WD6003FZBX-00K5WB0 6TB                                      | 1        | 0.46%   |
| WDC WD6003FZBX-00GXAB0 6TB                                      | 1        | 0.46%   |
| WDC WD40EZAZ-00SF3B0 4TB                                        | 1        | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 1        | 0.46%   |
| WDC WD3200AAJS-65M0A0 320GB                                     | 1        | 0.46%   |
| WDC WD20EURX-63T0FY0 2TB                                        | 1        | 0.46%   |
| WDC WD20EARX-00PASB0 2TB                                        | 1        | 0.46%   |
| WDC WD20EARS-60MVWB0 2TB                                        | 1        | 0.46%   |
| WDC WD10EZRZ-00HTKB0 1TB                                        | 1        | 0.46%   |
| WDC WD10EZEX-60WN4A0 1TB                                        | 1        | 0.46%   |
| WDC WD10EZEX-60M2NA0 1TB                                        | 1        | 0.46%   |
| WDC WD10EZEX-22MFCA0 1TB                                        | 1        | 0.46%   |
| WDC WD10EZEX-08M2NA0 1TB                                        | 1        | 0.46%   |
| WDC WD10EURX-63UY4Y0 1TB                                        | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 40     | 36.76%  |
| WDC                 | 20       | 25     | 29.41%  |
| Toshiba             | 7        | 7      | 10.29%  |
| Hitachi             | 4        | 4      | 5.88%   |
| HGST                | 4        | 4      | 5.88%   |
| Samsung Electronics | 3        | 3      | 4.41%   |
| Maxtor              | 2        | 2      | 2.94%   |
| Unknown             | 1        | 1      | 1.47%   |
| PHD 3.0             | 1        | 1      | 1.47%   |
| Apple               | 1        | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 26     | 22.39%  |
| Kingston            | 8        | 11     | 11.94%  |
| SanDisk             | 5        | 6      | 7.46%   |
| Crucial             | 5        | 7      | 7.46%   |
| WDC                 | 4        | 4      | 5.97%   |
| PNY                 | 3        | 3      | 4.48%   |
| A-DATA Technology   | 3        | 3      | 4.48%   |
| Seagate             | 2        | 2      | 2.99%   |
| Intel               | 2        | 2      | 2.99%   |
| Hewlett-Packard     | 2        | 2      | 2.99%   |
| China               | 2        | 2      | 2.99%   |
| Vaseky              | 1        | 1      | 1.49%   |
| Transcend           | 1        | 1      | 1.49%   |
| Team                | 1        | 1      | 1.49%   |
| SPCC                | 1        | 5      | 1.49%   |
| Smartbuy            | 1        | 1      | 1.49%   |
| S3+                 | 1        | 1      | 1.49%   |
| Patriot             | 1        | 1      | 1.49%   |
| Neo                 | 1        | 1      | 1.49%   |
| Micron Technology   | 1        | 1      | 1.49%   |
| INNOVATION IT       | 1        | 1      | 1.49%   |
| Hoodisk             | 1        | 1      | 1.49%   |
| Gigabyte Technology | 1        | 1      | 1.49%   |
| Emtec               | 1        | 2      | 1.49%   |
| CT1000MX            | 1        | 1      | 1.49%   |
| Corsair             | 1        | 1      | 1.49%   |
| AMD                 | 1        | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 57       | 89     | 39.31%  |
| HDD     | 45       | 88     | 31.03%  |
| NVMe    | 40       | 57     | 27.59%  |
| Unknown | 3        | 3      | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 172    | 59.32%  |
| NVMe | 40       | 57     | 33.9%   |
| SAS  | 8        | 8      | 6.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 78     | 42.86%  |
| 0.51-1.0   | 37       | 55     | 31.09%  |
| 1.01-2.0   | 16       | 23     | 13.45%  |
| 3.01-4.0   | 7        | 9      | 5.88%   |
| 4.01-10.0  | 6        | 10     | 5.04%   |
| 2.01-3.0   | 1        | 1      | 0.84%   |
| 10.01-20.0 | 1        | 1      | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 17       | 21.52%  |
| More than 3000 | 16       | 20.25%  |
| 101-250        | 15       | 18.99%  |
| 251-500        | 11       | 13.92%  |
| 1001-2000      | 9        | 11.39%  |
| 2001-3000      | 6        | 7.59%   |
| 1-20           | 2        | 2.53%   |
| 51-100         | 2        | 2.53%   |
| 21-50          | 1        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 13       | 16.46%  |
| 21-50          | 12       | 15.19%  |
| 101-250        | 12       | 15.19%  |
| 501-1000       | 12       | 15.19%  |
| 1-20           | 9        | 11.39%  |
| More than 3000 | 7        | 8.86%   |
| 51-100         | 7        | 8.86%   |
| 1001-2000      | 5        | 6.33%   |
| 2001-3000      | 2        | 2.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 2      | 5.56%   |
| WDC WD3200AAJS-65M0A0 320GB                  | 1        | 1      | 5.56%   |
| WDC WD10EZEX-22MFCA0 1TB                     | 1        | 1      | 5.56%   |
| WDC WD10EURX-63UY4Y0 1TB                     | 1        | 1      | 5.56%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1        | 1      | 5.56%   |
| WDC WD10EADS-65L5B1 1TB                      | 1        | 1      | 5.56%   |
| WDC WD Blue SA510 2.5 1000GB                 | 1        | 1      | 5.56%   |
| Seagate ST3500320AS 500GB                    | 1        | 1      | 5.56%   |
| Seagate ST1000VX000-1CU162 1TB               | 1        | 1      | 5.56%   |
| Seagate ST1000DM003-1CH162 1TB               | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 2      | 5.56%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 5.56%   |
| Neo Forza NFS121SA312-6007000 120GB SSD      | 1        | 1      | 5.56%   |
| Maxtor STM3160215AS 160GB                    | 1        | 1      | 5.56%   |
| Intel SSDSCKKW240H6 240GB                    | 1        | 1      | 5.56%   |
| Intel SSDPEKNW512G8 512GB                    | 1        | 1      | 5.56%   |
| Apple HDD HTS541010A9E662 1TB                | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 38.89%  |
| Seagate             | 3        | 3      | 16.67%  |
| Samsung Electronics | 3        | 4      | 16.67%  |
| Intel               | 2        | 2      | 11.11%  |
| Neo                 | 1        | 1      | 5.56%   |
| Maxtor              | 1        | 1      | 5.56%   |
| Apple               | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 50%     |
| Seagate             | 3        | 3      | 25%     |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Maxtor              | 1        | 1      | 8.33%   |
| Apple               | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 13     | 61.54%  |
| SSD  | 4        | 6      | 30.77%  |
| NVMe | 1        | 1      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 49       | 143    | 52.13%  |
| Works    | 32       | 72     | 34.04%  |
| Malfunc  | 12       | 20     | 12.77%  |
| Failed   | 1        | 2      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 40       | 29.85%  |
| Intel                        | 38       | 28.36%  |
| Samsung Electronics          | 14       | 10.45%  |
| SanDisk                      | 8        | 5.97%   |
| Micron/Crucial Technology    | 6        | 4.48%   |
| Phison Electronics           | 5        | 3.73%   |
| ASMedia Technology           | 5        | 3.73%   |
| Silicon Motion               | 4        | 2.99%   |
| Kingston Technology Company  | 4        | 2.99%   |
| ADATA Technology             | 3        | 2.24%   |
| Realtek Semiconductor        | 2        | 1.49%   |
| JMicron Technology           | 2        | 1.49%   |
| Silicon Image                | 1        | 0.75%   |
| Shenzhen Longsys Electronics | 1        | 0.75%   |
| Marvell Technology Group     | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 15.19%  |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 6.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 4.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 3.8%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5        | 3.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 3.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4        | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 2.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 2.53%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 1.9%    |
| Phison PS5013 E13 NVMe Controller                                              | 3        | 1.9%    |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.9%    |
| AMD X370 Series Chipset SATA Controller                                        | 3        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.9%    |
| AMD FCH SATA Controller D                                                      | 3        | 1.9%    |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 2        | 1.27%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 1.27%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 1.27%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.63%   |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                              | 1        | 0.63%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                             | 1        | 0.63%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.63%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1        | 0.63%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.63%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.63%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.63%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1        | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 0.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 73       | 60.33%  |
| NVMe | 40       | 33.06%  |
| IDE  | 5        | 4.13%   |
| RAID | 3        | 2.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 40       | 51.28%  |
| Intel  | 38       | 48.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 4        | 5.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 3        | 3.85%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 3        | 3.85%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 3        | 3.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 2        | 2.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2        | 2.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2        | 2.56%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 2        | 2.56%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 2        | 2.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 2        | 2.56%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 2        | 2.56%   |
| Intel Xeon CPU W3580 @ 3.33GHz          | 1        | 1.28%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz     | 1        | 1.28%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 1.28%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz  | 1        | 1.28%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1        | 1.28%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 1        | 1.28%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1        | 1.28%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1        | 1.28%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 1        | 1.28%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1        | 1.28%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1        | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1        | 1.28%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1        | 1.28%   |
| Intel Core i7 CPU 920 @ 2.67GHz         | 1        | 1.28%   |
| Intel Core i5-9600KF CPU @ 3.70GHz      | 1        | 1.28%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 1.28%   |
| Intel Core i5-8500 CPU @ 3.00GHz        | 1        | 1.28%   |
| Intel Core i5-4690 CPU @ 3.50GHz        | 1        | 1.28%   |
| Intel Core i5-3330 CPU @ 3.00GHz        | 1        | 1.28%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1        | 1.28%   |
| Intel Core i5-2320 CPU @ 3.00GHz        | 1        | 1.28%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1        | 1.28%   |
| Intel Core i5 CPU 660 @ 3.33GHz         | 1        | 1.28%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 1        | 1.28%   |
| Intel Celeron N5105 @ 2.00GHz           | 1        | 1.28%   |
| Intel 13th Gen Core i3-13100            | 1        | 1.28%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1        | 1.28%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1        | 1.28%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz | 1        | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 14       | 17.95%  |
| AMD Ryzen 5        | 14       | 17.95%  |
| Intel Core i5      | 12       | 15.38%  |
| AMD Ryzen 7        | 11       | 14.1%   |
| AMD Ryzen 9        | 6        | 7.69%   |
| Other              | 4        | 5.13%   |
| Intel Xeon         | 3        | 3.85%   |
| AMD Ryzen 5 PRO    | 2        | 2.56%   |
| AMD FX             | 2        | 2.56%   |
| Intel Pentium Gold | 1        | 1.28%   |
| Intel Pentium      | 1        | 1.28%   |
| Intel Core i9      | 1        | 1.28%   |
| Intel Core i3      | 1        | 1.28%   |
| Intel Celeron      | 1        | 1.28%   |
| AMD Ryzen Embedded | 1        | 1.28%   |
| AMD Ryzen 3 PRO    | 1        | 1.28%   |
| AMD Phenom II X4   | 1        | 1.28%   |
| AMD Athlon II X3   | 1        | 1.28%   |
| AMD Athlon         | 1        | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 37.18%  |
| 6      | 22       | 28.21%  |
| 8      | 13       | 16.67%  |
| 2      | 5        | 6.41%   |
| 16     | 3        | 3.85%   |
| 12     | 3        | 3.85%   |
| 3      | 2        | 2.56%   |
| 10     | 1        | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 78       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 59       | 75.64%  |
| 1      | 19       | 24.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 78       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 77.22%  |
| 0x0a601203 | 3        | 3.8%    |
| 0x0a20120a | 3        | 3.8%    |
| 0x08701021 | 3        | 3.8%    |
| 0x0a50000d | 1        | 1.27%   |
| 0x0a201025 | 1        | 1.27%   |
| 0x08701030 | 1        | 1.27%   |
| 0x08108109 | 1        | 1.27%   |
| 0x0810100b | 1        | 1.27%   |
| 0x0800820d | 1        | 1.27%   |
| 0x08001138 | 1        | 1.27%   |
| 0x0700010f | 1        | 1.27%   |
| 0x06000852 | 1        | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 14       | 17.95%  |
| KabyLake    | 10       | 12.82%  |
| Haswell     | 8        | 10.26%  |
| Zen+        | 7        | 8.97%   |
| SandyBridge | 7        | 8.97%   |
| Unknown     | 7        | 8.97%   |
| Zen 2       | 6        | 7.69%   |
| Zen         | 4        | 5.13%   |
| Piledriver  | 2        | 2.56%   |
| Nehalem     | 2        | 2.56%   |
| K10         | 2        | 2.56%   |
| IvyBridge   | 2        | 2.56%   |
| Westmere    | 1        | 1.28%   |
| Tremont     | 1        | 1.28%   |
| Skylake     | 1        | 1.28%   |
| Jaguar      | 1        | 1.28%   |
| Icelake     | 1        | 1.28%   |
| CometLake   | 1        | 1.28%   |
| Broadwell   | 1        | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 38       | 44.19%  |
| Nvidia | 30       | 34.88%  |
| Intel  | 18       | 20.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 8.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 8.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 4.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 3.45%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.45%   |
| AMD Raphael                                                                 | 3        | 3.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.3%    |
| Intel DG2 [Arc A380]                                                        | 2        | 2.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.3%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 2.3%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.3%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.15%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.15%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 1.15%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.15%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.15%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.15%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.15%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.15%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 1.15%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.15%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.15%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.15%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.15%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.15%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.15%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.15%   |
| Intel HD Graphics 630                                                       | 1        | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.15%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.15%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 33       | 42.31%  |
| 1 x Nvidia      | 27       | 34.62%  |
| 1 x Intel       | 12       | 15.38%  |
| Intel + AMD     | 2        | 2.56%   |
| 2 x AMD         | 1        | 1.28%   |
| Intel + 2 x AMD | 1        | 1.28%   |
| Intel + Nvidia  | 1        | 1.28%   |
| AMD + Nvidia    | 1        | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 67.95%  |
| Proprietary | 25       | 32.05%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 46.15%  |
| 7.01-8.0   | 10       | 12.82%  |
| 3.01-4.0   | 9        | 11.54%  |
| 1.01-2.0   | 8        | 10.26%  |
| 8.01-16.0  | 7        | 8.97%   |
| 5.01-6.0   | 3        | 3.85%   |
| 16.01-24.0 | 2        | 2.56%   |
| 0.01-0.5   | 2        | 2.56%   |
| 2.01-3.0   | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 11       | 12.22%  |
| Iiyama               | 9        | 10%     |
| Samsung Electronics  | 7        | 7.78%   |
| Hewlett-Packard      | 7        | 7.78%   |
| Acer                 | 7        | 7.78%   |
| Philips              | 6        | 6.67%   |
| Goldstar             | 6        | 6.67%   |
| ASUSTek Computer     | 6        | 6.67%   |
| Ancor Communications | 6        | 6.67%   |
| AOC                  | 5        | 5.56%   |
| Lenovo               | 3        | 3.33%   |
| Gigabyte Technology  | 3        | 3.33%   |
| BenQ                 | 3        | 3.33%   |
| Eizo                 | 2        | 2.22%   |
| Wacom                | 1        | 1.11%   |
| VIZ                  | 1        | 1.11%   |
| RTK                  | 1        | 1.11%   |
| ONN                  | 1        | 1.11%   |
| NEC Computers        | 1        | 1.11%   |
| Medion Akoya         | 1        | 1.11%   |
| INS                  | 1        | 1.11%   |
| GDH                  | 1        | 1.11%   |
| DENON                | 1        | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                | 2        | 1.96%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                 | 2        | 1.96%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                    | 2        | 1.96%   |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch     | 2        | 1.96%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch             | 1        | 0.98%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                   | 1        | 0.98%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch    | 1        | 0.98%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.98%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch | 1        | 0.98%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch   | 1        | 0.98%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch   | 1        | 0.98%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.98%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch    | 1        | 0.98%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch | 1        | 0.98%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch   | 1        | 0.98%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                    | 1        | 0.98%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch            | 1        | 0.98%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch             | 1        | 0.98%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch             | 1        | 0.98%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 0.98%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch             | 1        | 0.98%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                    | 1        | 0.98%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                  | 1        | 0.98%   |
| NEC Computers E233WM NEC2BE4 1920x1080 509x286mm 23.0-inch           | 1        | 0.98%   |
| Medion Akoya MD20491 MEC5201 1920x1080 521x293mm 23.5-inch           | 1        | 0.98%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch             | 1        | 0.98%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 1        | 0.98%   |
| Lenovo L1940p Wide LEN1148 1440x900 410x257mm 19.1-inch              | 1        | 0.98%   |
| INS WT70CA612 INS3694 3840x2160 1538x865mm 69.5-inch                 | 1        | 0.98%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1        | 0.98%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 1        | 0.98%   |
| Iiyama PL2791Q IVM6647 2560x1440 597x336mm 27.0-inch                 | 1        | 0.98%   |
| Iiyama PL2791Q IVM6646 2560x1440 597x336mm 27.0-inch                 | 1        | 0.98%   |
| Iiyama PL2760Q IVM663D 2560x1440 597x336mm 27.0-inch                 | 1        | 0.98%   |
| Iiyama PL2480H IVM610B 1920x1080 521x293mm 23.5-inch                 | 1        | 0.98%   |
| Iiyama PL2451 IVM610A 1920x1080 521x293mm 23.5-inch                  | 1        | 0.98%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 1        | 0.98%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch           | 1        | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 47.19%  |
| 3840x2160 (4K)     | 15       | 16.85%  |
| 2560x1440 (QHD)    | 11       | 12.36%  |
| 1600x900 (HD+)     | 4        | 4.49%   |
| 1440x900 (WXGA+)   | 4        | 4.49%   |
| 1920x1200 (WUXGA)  | 3        | 3.37%   |
| 1366x768 (WXGA)    | 3        | 3.37%   |
| 3440x1440          | 2        | 2.25%   |
| 2560x1080          | 2        | 2.25%   |
| 2560x1600          | 1        | 1.12%   |
| 1680x1050 (WSXGA+) | 1        | 1.12%   |
| 1360x768           | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 23       | 24.47%  |
| 27      | 22       | 23.4%   |
| 31      | 9        | 9.57%   |
| 23      | 9        | 9.57%   |
| 21      | 9        | 9.57%   |
| 19      | 8        | 8.51%   |
| 34      | 4        | 4.26%   |
| 18      | 3        | 3.19%   |
| 69      | 1        | 1.06%   |
| 52      | 1        | 1.06%   |
| 33      | 1        | 1.06%   |
| 25      | 1        | 1.06%   |
| 22      | 1        | 1.06%   |
| 20      | 1        | 1.06%   |
| Unknown | 1        | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 48       | 54.55%  |
| 401-500     | 20       | 22.73%  |
| 601-700     | 12       | 13.64%  |
| 701-800     | 5        | 5.68%   |
| 1501-2000   | 1        | 1.14%   |
| 1001-1500   | 1        | 1.14%   |
| Unknown     | 1        | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 65       | 81.25%  |
| 16/10   | 10       | 12.5%   |
| 21/9    | 4        | 5%      |
| Unknown | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 32.61%  |
| 301-350        | 22       | 23.91%  |
| 351-500        | 14       | 15.22%  |
| 251-300        | 10       | 10.87%  |
| 151-200        | 10       | 10.87%  |
| 141-150        | 3        | 3.26%   |
| More than 1000 | 2        | 2.17%   |
| Unknown        | 1        | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 50       | 60.98%  |
| 101-120 | 19       | 23.17%  |
| 121-160 | 8        | 9.76%   |
| 161-240 | 3        | 3.66%   |
| 1-50    | 1        | 1.22%   |
| Unknown | 1        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 73.08%  |
| 2     | 15       | 19.23%  |
| 3     | 5        | 6.41%   |
| 4     | 1        | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 54       | 45.76%  |
| Intel                 | 28       | 23.73%  |
| MediaTek              | 8        | 6.78%   |
| TP-Link               | 5        | 4.24%   |
| Qualcomm Atheros      | 4        | 3.39%   |
| Broadcom              | 4        | 3.39%   |
| Ralink                | 3        | 2.54%   |
| ASUSTek Computer      | 3        | 2.54%   |
| Texas Instruments     | 1        | 0.85%   |
| QinHeng Electronics   | 1        | 0.85%   |
| NetGear               | 1        | 0.85%   |
| Microsoft             | 1        | 0.85%   |
| Linksys               | 1        | 0.85%   |
| Huawei Technologies   | 1        | 0.85%   |
| Google                | 1        | 0.85%   |
| Arduino SA            | 1        | 0.85%   |
| Aquantia              | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 36       | 27.91%  |
| Realtek RTL8125 2.5GbE Controller                                             | 13       | 10.08%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 5.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 4        | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 2.33%   |
| Intel Ethernet Controller I225-V                                              | 3        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 1.55%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.55%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 1.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.55%   |
| Intel Wireless 7265                                                           | 2        | 1.55%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.78%   |
| TP-Link 802.11n NIC                                                           | 1        | 0.78%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.78%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.78%   |
| QinHeng USB Single Serial                                                     | 1        | 0.78%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 0.78%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 1        | 0.78%   |
| MediaTek WiFi                                                                 | 1        | 0.78%   |
| MediaTek moto g22                                                             | 1        | 0.78%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                     | 1        | 0.78%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.78%   |
| Intel Wireless 8260                                                           | 1        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| MediaTek              | 7        | 17.95%  |
| Intel                 | 7        | 17.95%  |
| Realtek Semiconductor | 6        | 15.38%  |
| TP-Link               | 5        | 12.82%  |
| Ralink                | 3        | 7.69%   |
| Qualcomm Atheros      | 3        | 7.69%   |
| ASUSTek Computer      | 3        | 7.69%   |
| Broadcom              | 2        | 5.13%   |
| NetGear               | 1        | 2.56%   |
| Microsoft             | 1        | 2.56%   |
| Linksys               | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 4        | 10%     |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 5%      |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 5%      |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 5%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 5%      |
| Intel Wireless 7265                                                           | 2        | 5%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 2.5%    |
| TP-Link 802.11n NIC                                                           | 1        | 2.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 2.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 2.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 2.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 2.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 2.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.5%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2.5%    |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 2.5%    |
| Microsoft Xbox Wireless Adapter for Windows                                   | 1        | 2.5%    |
| MediaTek WiFi                                                                 | 1        | 2.5%    |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                     | 1        | 2.5%    |
| Intel Wireless-AC 9260                                                        | 1        | 2.5%    |
| Intel Wireless 8260                                                           | 1        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 2.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 2.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 2.5%    |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 2.5%    |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 2.5%    |
| ASUS 802.11ac NIC                                                             | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 53       | 62.35%  |
| Intel                 | 24       | 28.24%  |
| Qualcomm Atheros      | 2        | 2.35%   |
| Broadcom              | 2        | 2.35%   |
| MediaTek              | 1        | 1.18%   |
| Huawei Technologies   | 1        | 1.18%   |
| Google                | 1        | 1.18%   |
| Aquantia              | 1        | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 41.86%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 15.12%  |
| Intel I211 Gigabit Network Connection                             | 7        | 8.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.49%   |
| Intel Ethernet Controller I225-V                                  | 3        | 3.49%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.49%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.16%   |
| MediaTek moto g22                                                 | 1        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.16%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.16%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.16%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.16%   |
| Huawei MLA-L11                                                    | 1        | 1.16%   |
| Google Pixel 6                                                    | 1        | 1.16%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 1.16%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.16%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 78       | 66.1%   |
| WiFi     | 37       | 31.36%  |
| Modem    | 3        | 2.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 77.91%  |
| WiFi     | 19       | 22.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 69.23%  |
| 2     | 22       | 28.21%  |
| 5     | 1        | 1.28%   |
| 3     | 1        | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 64.56%  |
| Yes  | 28       | 35.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 9        | 28.13%  |
| Intel                           | 8        | 25%     |
| MediaTek                        | 4        | 12.5%   |
| Realtek Semiconductor           | 3        | 9.38%   |
| TP-Link                         | 2        | 6.25%   |
| Qualcomm Atheros Communications | 2        | 6.25%   |
| Realtek                         | 1        | 3.13%   |
| IMC Networks                    | 1        | 3.13%   |
| Foxconn / Hon Hai               | 1        | 3.13%   |
| ASUSTek Computer                | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9        | 28.13%  |
| MediaTek Wireless_Device                            | 4        | 12.5%   |
| Realtek Bluetooth Radio                             | 3        | 9.38%   |
| Intel Bluetooth wireless interface                  | 3        | 9.38%   |
| TP-Link UB5A Adapter                                | 2        | 6.25%   |
| Intel AX210 Bluetooth                               | 2        | 6.25%   |
| Realtek Bluetooth Radio                             | 1        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.13%   |
| Intel Bluetooth Device                              | 1        | 3.13%   |
| Intel AX201 Bluetooth                               | 1        | 3.13%   |
| IMC Networks BCM20702A0                             | 1        | 3.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 3.13%   |
| ASUS ASUS USB-BT500                                 | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 52       | 33.55%  |
| Intel                    | 40       | 25.81%  |
| Nvidia                   | 29       | 18.71%  |
| C-Media Electronics      | 7        | 4.52%   |
| Focusrite-Novation       | 4        | 2.58%   |
| Logitech                 | 3        | 1.94%   |
| Texas Instruments        | 2        | 1.29%   |
| SteelSeries ApS          | 2        | 1.29%   |
| SAVITECH                 | 2        | 1.29%   |
| Trust                    | 1        | 0.65%   |
| TEAC                     | 1        | 0.65%   |
| Realtek Semiconductor    | 1        | 0.65%   |
| Micro Star International | 1        | 0.65%   |
| Mackie Designs           | 1        | 0.65%   |
| JMTek                    | 1        | 0.65%   |
| Generalplus Technology   | 1        | 0.65%   |
| Dell                     | 1        | 0.65%   |
| Creative Labs            | 1        | 0.65%   |
| Corsair                  | 1        | 0.65%   |
| AudioQuest               | 1        | 0.65%   |
| ASUSTek Computer         | 1        | 0.65%   |
| Asahi Kasei Microsystems | 1        | 0.65%   |
| 2.4G Composite Device    | 1        | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 8.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 6.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 5.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 4.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.69%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 2.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 2.15%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 2.15%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 1.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.61%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3        | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.08%   |
| Intel DG2 Audio Controller                                                 | 2        | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.08%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 2        | 1.08%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.08%   |
| Trust Microphone                                                           | 1        | 0.54%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.54%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.54%   |
| TEAC US-1x2HR                                                              | 1        | 0.54%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.54%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.54%   |
| SAVITECH SA9123 USB Audio                                                  | 1        | 0.54%   |
| SAVITECH SA9023 audio controller                                           | 1        | 0.54%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 7        | 16.28%  |
| Corsair             | 7        | 16.28%  |
| G.Skill             | 6        | 13.95%  |
| Samsung Electronics | 5        | 11.63%  |
| Crucial             | 3        | 6.98%   |
| A-DATA Technology   | 3        | 6.98%   |
| Unknown             | 2        | 4.65%   |
| Team                | 2        | 4.65%   |
| SK hynix            | 2        | 4.65%   |
| Micron Technology   | 2        | 4.65%   |
| Patriot             | 1        | 2.33%   |
| Nanya Technology    | 1        | 2.33%   |
| Atermiter           | 1        | 2.33%   |
| Unknown             | 1        | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 4.44%   |
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 2.22%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 2.22%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 2.22%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s          | 1        | 2.22%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 2.22%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 2.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 2.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1        | 2.22%   |
| Samsung RAM M391B5773CH0-YH9 2GB DIMM DDR3 1333MT/s            | 1        | 2.22%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s            | 1        | 2.22%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 3733MT/s | 1        | 2.22%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s            | 1        | 2.22%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 2.22%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 2.22%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 2.22%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 2.22%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 1        | 2.22%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 4800MT/s               | 1        | 2.22%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 2.22%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 1        | 2.22%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s             | 1        | 2.22%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 2.22%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 2.22%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s           | 1        | 2.22%   |
| G.Skill RAM F4-3600C18-16GVK 16GB DIMM DDR4 3733MT/s           | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-8GFX 8GB DIMM DDR4 3200MT/s             | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-16GFX 16GB DIMM DDR4 3266MT/s           | 1        | 2.22%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 1        | 2.22%   |
| G.Skill RAM F4-2400C15-4GRK 4GB DIMM DDR4 2400MT/s             | 1        | 2.22%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 1        | 2.22%   |
| Crucial RAM BLS16G4D240FSE.16FBD 16GB DIMM DDR4 2473MT/s       | 1        | 2.22%   |
| Crucial RAM BL16G36C16U4R.M8FB1 16GB DIMM DDR4 3600MT/s        | 1        | 2.22%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s            | 1        | 2.22%   |
| Corsair RAM CMW32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 1        | 2.22%   |
| Corsair RAM CMU16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s          | 1        | 2.22%   |
| Corsair RAM CMT32GX5M2D6000Z36 16GB DIMM DDR5 4800MT/s         | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 24       | 61.54%  |
| DDR3    | 10       | 25.64%  |
| DDR5    | 3        | 7.69%   |
| LPDDR4  | 1        | 2.56%   |
| Unknown | 1        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 35       | 89.74%  |
| SODIMM       | 3        | 7.69%   |
| Row Of Chips | 1        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 34.88%  |
| 16384 | 14       | 32.56%  |
| 4096  | 8        | 18.6%   |
| 32768 | 4        | 9.3%    |
| 2048  | 2        | 4.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 8        | 18.6%   |
| 3600  | 6        | 13.95%  |
| 3733  | 3        | 6.98%   |
| 2667  | 3        | 6.98%   |
| 2400  | 3        | 6.98%   |
| 1800  | 3        | 6.98%   |
| 1333  | 3        | 6.98%   |
| 4800  | 2        | 4.65%   |
| 3266  | 2        | 4.65%   |
| 2933  | 2        | 4.65%   |
| 1600  | 2        | 4.65%   |
| 6400  | 1        | 2.33%   |
| 3666  | 1        | 2.33%   |
| 3334  | 1        | 2.33%   |
| 2473  | 1        | 2.33%   |
| 2133  | 1        | 2.33%   |
| 667   | 1        | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-7100 Series | 1        | 33.33%  |
| Seiko Epson XP-2200 Series | 1        | 33.33%  |
| Brother HL-L2310D series   | 1        | 33.33%  |

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
| Logitech                      | 4        | 25%     |
| Samsung Electronics           | 2        | 12.5%   |
| Microdia                      | 2        | 12.5%   |
| Sunplus Innovation Technology | 1        | 6.25%   |
| SN0002                        | 1        | 6.25%   |
| Realtek Semiconductor         | 1        | 6.25%   |
| OPPO Electronics              | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| GEMBIRD                       | 1        | 6.25%   |
| Chicony Electronics           | 1        | 6.25%   |
| AVerMedia Technologies        | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 12.5%   |
| Sunplus FHD Camera Microphone                     | 1        | 6.25%   |
| SN0002 HIK 1080P USB CAMERA                       | 1        | 6.25%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 6.25%   |
| OPPO Oppo N1                                      | 1        | 6.25%   |
| Microdia Webcam Vitade AF                         | 1        | 6.25%   |
| Microdia Camera                                   | 1        | 6.25%   |
| Logitech HD Webcam C615                           | 1        | 6.25%   |
| Logitech HD Pro Webcam C920                       | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 6.25%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 6.25%   |
| Generalplus 808 Camera                            | 1        | 6.25%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 6.25%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 6.25%   |
| AVerMedia PW310O Webcam                           | 1        | 6.25%   |

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
| 0     | 67       | 85.9%   |
| 1     | 9        | 11.54%  |
| 3     | 1        | 1.28%   |
| 2     | 1        | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 36.36%  |
| Unassigned class         | 2        | 18.18%  |
| Communication controller | 2        | 18.18%  |
| Sound                    | 1        | 9.09%   |
| Graphics card            | 1        | 9.09%   |
| Camera                   | 1        | 9.09%   |

