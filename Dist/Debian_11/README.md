Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 10401

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1495                        | Desktop     | [50dfd57e41](https://linux-hardware.org/?probe=50dfd57e41) | Jan 03, 2026 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [6ae53887a0](https://linux-hardware.org/?probe=6ae53887a0) | Dec 31, 2025 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c827dc109a](https://linux-hardware.org/?probe=c827dc109a) | Dec 31, 2025 |
| Dell          | Latitude 5490               | Notebook    | [adbe981dd3](https://linux-hardware.org/?probe=adbe981dd3) | Dec 26, 2025 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [33d7824d2a](https://linux-hardware.org/?probe=33d7824d2a) | Dec 23, 2025 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [4afd2ee4ad](https://linux-hardware.org/?probe=4afd2ee4ad) | Dec 23, 2025 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [30fe3e1f95](https://linux-hardware.org/?probe=30fe3e1f95) | Dec 14, 2025 |
| Dell          | Latitude E6410              | Notebook    | [270d84c5b3](https://linux-hardware.org/?probe=270d84c5b3) | Dec 14, 2025 |
| IBM           | ThinkPad T40 2373MU1        | Notebook    | [7fb3c2c8fc](https://linux-hardware.org/?probe=7fb3c2c8fc) | Dec 11, 2025 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8a3c1cfa03](https://linux-hardware.org/?probe=8a3c1cfa03) | Dec 09, 2025 |
| Dell          | Latitude 2120               | Notebook    | [bcfef96715](https://linux-hardware.org/?probe=bcfef96715) | Dec 07, 2025 |
| ASUSTek       | K52F                        | Notebook    | [92f40ae93e](https://linux-hardware.org/?probe=92f40ae93e) | Dec 07, 2025 |
| Dell          | Latitude 3400               | Notebook    | [57b6b912fc](https://linux-hardware.org/?probe=57b6b912fc) | Dec 06, 2025 |
| MSI           | A88XM-E35 V2                | Desktop     | [f3017661e5](https://linux-hardware.org/?probe=f3017661e5) | Dec 05, 2025 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [91feb2ac1a](https://linux-hardware.org/?probe=91feb2ac1a) | Nov 17, 2025 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8c3cf5f28e](https://linux-hardware.org/?probe=8c3cf5f28e) | Nov 13, 2025 |
| Supermicro    | X10SRL-FB                   | Server      | [890f346695](https://linux-hardware.org/?probe=890f346695) | Nov 12, 2025 |
| Intel         | Alpha lite                  | Desktop     | [93be5c1af5](https://linux-hardware.org/?probe=93be5c1af5) | Nov 09, 2025 |
| ASUSTek       | UX303LN                     | Notebook    | [95937e22ad](https://linux-hardware.org/?probe=95937e22ad) | Nov 08, 2025 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [14b7317d76](https://linux-hardware.org/?probe=14b7317d76) | Oct 30, 2025 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c34cf00b99](https://linux-hardware.org/?probe=c34cf00b99) | Oct 29, 2025 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [10c7f52e27](https://linux-hardware.org/?probe=10c7f52e27) | Oct 29, 2025 |
| ASUSTek       | X551MA                      | Notebook    | [2cdf545de6](https://linux-hardware.org/?probe=2cdf545de6) | Oct 28, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0e6621daf2](https://linux-hardware.org/?probe=0e6621daf2) | Oct 27, 2025 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [7c044a8bbb](https://linux-hardware.org/?probe=7c044a8bbb) | Oct 21, 2025 |
| NTT SYSTEM    | Komputer All-in-One NTT ... | Desktop     | [acfa9d530d](https://linux-hardware.org/?probe=acfa9d530d) | Oct 20, 2025 |
| Radxa         | ROCK 4C+                    | Soc         | [96b6428ebd](https://linux-hardware.org/?probe=96b6428ebd) | Oct 15, 2025 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [15db125ea6](https://linux-hardware.org/?probe=15db125ea6) | Oct 15, 2025 |
| Unknown       | sun60iw2 (DT)               | Soc         | [375497e2bf](https://linux-hardware.org/?probe=375497e2bf) | Oct 14, 2025 |
| Dell          | 0M5DCD A00                  | Desktop     | [76a7edd20f](https://linux-hardware.org/?probe=76a7edd20f) | Oct 09, 2025 |
| HP            | 1790                        | Desktop     | [c6a242ab21](https://linux-hardware.org/?probe=c6a242ab21) | Oct 09, 2025 |
| YADRO         | System Board 451A9726L12    | Server      | [0c33390fcc](https://linux-hardware.org/?probe=0c33390fcc) | Oct 06, 2025 |
| ASRock        | B450 Pro4                   | Desktop     | [fbf8668490](https://linux-hardware.org/?probe=fbf8668490) | Oct 06, 2025 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [b3f3ecf4e6](https://linux-hardware.org/?probe=b3f3ecf4e6) | Oct 01, 2025 |
| Acer          | Aspire one                  | Notebook    | [9b25a25862](https://linux-hardware.org/?probe=9b25a25862) | Sep 29, 2025 |
| ASUSTek       | K56CM                       | Notebook    | [79b8537fef](https://linux-hardware.org/?probe=79b8537fef) | Sep 27, 2025 |
| ASUSTek       | K56CM                       | Notebook    | [1ea52daf1f](https://linux-hardware.org/?probe=1ea52daf1f) | Sep 27, 2025 |
| HP            | Pavilion g6                 | Notebook    | [fd3053f503](https://linux-hardware.org/?probe=fd3053f503) | Sep 14, 2025 |
| HP            | 876C SMVB                   | Desktop     | [faa6bb4bdb](https://linux-hardware.org/?probe=faa6bb4bdb) | Sep 10, 2025 |
| HP            | 1790                        | Desktop     | [f4a4ccf236](https://linux-hardware.org/?probe=f4a4ccf236) | Sep 10, 2025 |
| Lenovo        | ThinkPad T580 20LAS24800    | Notebook    | [f914be01a7](https://linux-hardware.org/?probe=f914be01a7) | Sep 08, 2025 |
| Lenovo        | ThinkPad T580 20LAS24800    | Notebook    | [8df96a5e94](https://linux-hardware.org/?probe=8df96a5e94) | Sep 08, 2025 |
| HP            | 1495                        | Desktop     | [1b730db0b1](https://linux-hardware.org/?probe=1b730db0b1) | Sep 07, 2025 |
| ASUSTek       | Z97-PRO                     | Desktop     | [6bf2414c3b](https://linux-hardware.org/?probe=6bf2414c3b) | Sep 07, 2025 |
| ASUSTek       | Z97-PRO                     | Desktop     | [f83b15944f](https://linux-hardware.org/?probe=f83b15944f) | Sep 07, 2025 |
| HP            | 1495                        | Desktop     | [ddeaaec5bc](https://linux-hardware.org/?probe=ddeaaec5bc) | Sep 04, 2025 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [15b41c928c](https://linux-hardware.org/?probe=15b41c928c) | Aug 31, 2025 |
| ASUSTek       | P8H67-M                     | Desktop     | [6db63132a5](https://linux-hardware.org/?probe=6db63132a5) | Aug 30, 2025 |
| Teclast       | F5                          | Convertible | [1719d2aef2](https://linux-hardware.org/?probe=1719d2aef2) | Aug 30, 2025 |
| Toshiba       | PORTEGE M600                | Notebook    | [8ab214b522](https://linux-hardware.org/?probe=8ab214b522) | Aug 26, 2025 |
| HP            | 8712                        | Desktop     | [47663d6487](https://linux-hardware.org/?probe=47663d6487) | Aug 24, 2025 |
| HP            | 1790                        | Desktop     | [9b0bedd9b7](https://linux-hardware.org/?probe=9b0bedd9b7) | Aug 24, 2025 |
| HP            | 1790                        | Desktop     | [e34fdab0a9](https://linux-hardware.org/?probe=e34fdab0a9) | Aug 24, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [87c713b815](https://linux-hardware.org/?probe=87c713b815) | Aug 20, 2025 |
| Gigabyte      | H410M H V2                  | Desktop     | [1bc206cbd3](https://linux-hardware.org/?probe=1bc206cbd3) | Aug 20, 2025 |
| VANT          | MOOVE2-14                   | Notebook    | [9601ebcdfd](https://linux-hardware.org/?probe=9601ebcdfd) | Aug 19, 2025 |
| Acer          | AOD270                      | Notebook    | [46e41183d3](https://linux-hardware.org/?probe=46e41183d3) | Aug 18, 2025 |
| Dell          | Inspiron 5767               | Notebook    | [016c7911b4](https://linux-hardware.org/?probe=016c7911b4) | Aug 16, 2025 |
| Radxa         | ROCK 4C+                    | Soc         | [54906df422](https://linux-hardware.org/?probe=54906df422) | Jul 28, 2025 |
| VANT          | MOOVE2-14                   | Notebook    | [ffc1d9b714](https://linux-hardware.org/?probe=ffc1d9b714) | Jul 22, 2025 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [33e6bdebef](https://linux-hardware.org/?probe=33e6bdebef) | Jul 16, 2025 |
| Dell          | 0P03DX A04                  | Desktop     | [a1d023a277](https://linux-hardware.org/?probe=a1d023a277) | Jul 14, 2025 |
| Dell          | 0P03DX A04                  | Desktop     | [b4fdad092a](https://linux-hardware.org/?probe=b4fdad092a) | Jul 13, 2025 |
| Radxa         | ZERO 3                      | Soc         | [0cd637d23e](https://linux-hardware.org/?probe=0cd637d23e) | Jul 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [ef7a4cd4c1](https://linux-hardware.org/?probe=ef7a4cd4c1) | Jul 10, 2025 |
| Fujitsu Si... | AMILO Pro V3205             | Notebook    | [570d0c0d63](https://linux-hardware.org/?probe=570d0c0d63) | Jul 09, 2025 |
| Radxa         | ROCK 4C+                    | Soc         | [631d51cdc4](https://linux-hardware.org/?probe=631d51cdc4) | Jul 09, 2025 |
| HP            | EliteBook 2540p             | Notebook    | [348828e683](https://linux-hardware.org/?probe=348828e683) | Jul 06, 2025 |
| TI            | AM335x PocketBeagle         | Soc         | [cb3d62849a](https://linux-hardware.org/?probe=cb3d62849a) | Jul 03, 2025 |
| ASUSTek       | K43SV                       | Notebook    | [bca06c5a32](https://linux-hardware.org/?probe=bca06c5a32) | Jul 01, 2025 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [0c7ca7bfa9](https://linux-hardware.org/?probe=0c7ca7bfa9) | Jun 25, 2025 |
| ASRock        | X570 PG Velocita            | Desktop     | [521dfe6c86](https://linux-hardware.org/?probe=521dfe6c86) | Jun 24, 2025 |
| OrangePi      | Zero2 W                     | Soc         | [6e651ac3f0](https://linux-hardware.org/?probe=6e651ac3f0) | Jun 20, 2025 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [28f94963d3](https://linux-hardware.org/?probe=28f94963d3) | Jun 18, 2025 |
| Dell          | Latitude 7480               | Notebook    | [72f8a64a21](https://linux-hardware.org/?probe=72f8a64a21) | Jun 16, 2025 |
| Dell          | Latitude 7480               | Notebook    | [1522b32e5d](https://linux-hardware.org/?probe=1522b32e5d) | Jun 16, 2025 |
| Lenovo        | 312F SEK0N11843 IOT 3806... | Mini pc     | [895d39716d](https://linux-hardware.org/?probe=895d39716d) | Jun 14, 2025 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [b4bc28a035](https://linux-hardware.org/?probe=b4bc28a035) | Jun 11, 2025 |
| Dell          | Latitude E6420              | Notebook    | [45ed7757f9](https://linux-hardware.org/?probe=45ed7757f9) | Jun 09, 2025 |
| Dell          | 0J3C2F A00                  | Desktop     | [9f8a3628b3](https://linux-hardware.org/?probe=9f8a3628b3) | Jun 08, 2025 |
| ASUSTek       | X455LD                      | Notebook    | [d8fd5fad72](https://linux-hardware.org/?probe=d8fd5fad72) | Jun 05, 2025 |
| Dell          | 00NH4P A09                  | Server      | [3c29f268d0](https://linux-hardware.org/?probe=3c29f268d0) | Jun 05, 2025 |
| Intel         | NUC7i5DNB J57626-514        | Mini pc     | [0bfa2beb64](https://linux-hardware.org/?probe=0bfa2beb64) | May 31, 2025 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [43c8f9da20](https://linux-hardware.org/?probe=43c8f9da20) | May 29, 2025 |
| Intel         | H61                         | Desktop     | [173afcaade](https://linux-hardware.org/?probe=173afcaade) | May 26, 2025 |
| Bananapi      | BPI-R2                      | Soc         | [846e4cab6c](https://linux-hardware.org/?probe=846e4cab6c) | May 23, 2025 |
| Bananapi      | BPI-R2                      | Soc         | [68dedc3ed7](https://linux-hardware.org/?probe=68dedc3ed7) | May 23, 2025 |
| Dell          | Inspiron 1525               | Notebook    | [a8c786d129](https://linux-hardware.org/?probe=a8c786d129) | May 21, 2025 |
| LETSUNG       | Unknown                     | Notebook    | [ecf1643964](https://linux-hardware.org/?probe=ecf1643964) | May 21, 2025 |
| Dell          | Latitude 7480               | Notebook    | [47832173fd](https://linux-hardware.org/?probe=47832173fd) | May 17, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0a7d7ef579](https://linux-hardware.org/?probe=0a7d7ef579) | May 16, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [0c4fcddebd](https://linux-hardware.org/?probe=0c4fcddebd) | May 13, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [6a765d2ecc](https://linux-hardware.org/?probe=6a765d2ecc) | May 13, 2025 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [7484312508](https://linux-hardware.org/?probe=7484312508) | May 10, 2025 |
| FriendlyEl... | NanoPi M6                   | Soc         | [b3eeec9d76](https://linux-hardware.org/?probe=b3eeec9d76) | May 09, 2025 |
| Dell          | 01CTXG A04                  | Server      | [2a6abb2053](https://linux-hardware.org/?probe=2a6abb2053) | May 08, 2025 |
| HP            | 1495                        | Desktop     | [581ae40ba0](https://linux-hardware.org/?probe=581ae40ba0) | May 08, 2025 |
| Rockchip      | RK3318 BOX                  | Soc         | [7d6a685b06](https://linux-hardware.org/?probe=7d6a685b06) | May 06, 2025 |
| Dell          | Latitude 7480               | Notebook    | [1bbc741054](https://linux-hardware.org/?probe=1bbc741054) | May 02, 2025 |
| HP            | 871A                        | Mini pc     | [af290e8957](https://linux-hardware.org/?probe=af290e8957) | May 01, 2025 |
| Radxa         | E20C                        | Soc         | [6ba8e3218b](https://linux-hardware.org/?probe=6ba8e3218b) | Apr 28, 2025 |
| Radxa         | E20C                        | Soc         | [41c232629f](https://linux-hardware.org/?probe=41c232629f) | Apr 28, 2025 |
| Gigabyte      | J1800N-D2PH                 | Desktop     | [3f579c4858](https://linux-hardware.org/?probe=3f579c4858) | Apr 28, 2025 |
| OrangePi      | Zero2 W                     | Soc         | [5ca775b5ed](https://linux-hardware.org/?probe=5ca775b5ed) | Apr 26, 2025 |
| Lenovo        | ThinkPad T530 23594LU       | Notebook    | [cfec33da3b](https://linux-hardware.org/?probe=cfec33da3b) | Apr 25, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f5bd4c233b](https://linux-hardware.org/?probe=f5bd4c233b) | Apr 24, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [2b4950ef6b](https://linux-hardware.org/?probe=2b4950ef6b) | Apr 24, 2025 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e3069a35ec](https://linux-hardware.org/?probe=e3069a35ec) | Apr 24, 2025 |
| HP            | 1495                        | Desktop     | [2387fc7971](https://linux-hardware.org/?probe=2387fc7971) | Apr 23, 2025 |
| sunxi         | FriendlyARM NanoPi NEO 2    | Soc         | [1c20ebde25](https://linux-hardware.org/?probe=1c20ebde25) | Apr 22, 2025 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [0df03dcaeb](https://linux-hardware.org/?probe=0df03dcaeb) | Apr 21, 2025 |
| Toshiba       | Satellite P50-C             | Notebook    | [23afdd547d](https://linux-hardware.org/?probe=23afdd547d) | Apr 20, 2025 |
| Intel         | Granite Well FABA           | Desktop     | [e46838f2b2](https://linux-hardware.org/?probe=e46838f2b2) | Apr 18, 2025 |
| ASRock        | B450M Pro4                  | Desktop     | [45728a8f62](https://linux-hardware.org/?probe=45728a8f62) | Apr 18, 2025 |
| Acer          | Aspire A515-57              | Notebook    | [acb0629796](https://linux-hardware.org/?probe=acb0629796) | Apr 16, 2025 |
| HP            | ProBook 6570b               | Notebook    | [095957fe0a](https://linux-hardware.org/?probe=095957fe0a) | Apr 10, 2025 |
| ASUSTek       | G750JW                      | Notebook    | [14a6a91b11](https://linux-hardware.org/?probe=14a6a91b11) | Apr 09, 2025 |
| OrangePi      | Zero2 W                     | Soc         | [48db8bf070](https://linux-hardware.org/?probe=48db8bf070) | Apr 09, 2025 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [542f3c1717](https://linux-hardware.org/?probe=542f3c1717) | Apr 07, 2025 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [81856c6957](https://linux-hardware.org/?probe=81856c6957) | Apr 07, 2025 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [df6f005f45](https://linux-hardware.org/?probe=df6f005f45) | Apr 06, 2025 |
| ASRock        | B250M-HDV                   | Desktop     | [33d5c70b89](https://linux-hardware.org/?probe=33d5c70b89) | Apr 06, 2025 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [d94d49a8ad](https://linux-hardware.org/?probe=d94d49a8ad) | Apr 05, 2025 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [dfd78d3cc1](https://linux-hardware.org/?probe=dfd78d3cc1) | Apr 03, 2025 |
| HP            | 1489                        | All in one  | [41df5a043b](https://linux-hardware.org/?probe=41df5a043b) | Apr 01, 2025 |
| HP            | 1489                        | All in one  | [498cbba9ee](https://linux-hardware.org/?probe=498cbba9ee) | Apr 01, 2025 |
| HP            | 1489                        | All in one  | [56e3e3866a](https://linux-hardware.org/?probe=56e3e3866a) | Mar 28, 2025 |
| OEM           | Intel H81                   | Desktop     | [46140488e4](https://linux-hardware.org/?probe=46140488e4) | Mar 28, 2025 |
| HP            | 1489                        | All in one  | [a988cb663b](https://linux-hardware.org/?probe=a988cb663b) | Mar 27, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [23c3f84810](https://linux-hardware.org/?probe=23c3f84810) | Mar 26, 2025 |
| Compal        | QAL50                       | Notebook    | [9ce5dd20d2](https://linux-hardware.org/?probe=9ce5dd20d2) | Mar 25, 2025 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [d5cf4899f3](https://linux-hardware.org/?probe=d5cf4899f3) | Mar 24, 2025 |
| Dell          | Precision M4800             | Notebook    | [ecfce85772](https://linux-hardware.org/?probe=ecfce85772) | Mar 24, 2025 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [decd87067a](https://linux-hardware.org/?probe=decd87067a) | Mar 23, 2025 |
| OEM           | Intel H81                   | Desktop     | [61e414370c](https://linux-hardware.org/?probe=61e414370c) | Mar 22, 2025 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [44ec4f3d1b](https://linux-hardware.org/?probe=44ec4f3d1b) | Mar 21, 2025 |
| Radxa         | ROCK3 Model A               | Soc         | [ef0b507cb7](https://linux-hardware.org/?probe=ef0b507cb7) | Mar 21, 2025 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [d28a6d121b](https://linux-hardware.org/?probe=d28a6d121b) | Mar 21, 2025 |
| MSI           | 760GA-P43                   | Desktop     | [1166034212](https://linux-hardware.org/?probe=1166034212) | Mar 21, 2025 |
| MSI           | 760GA-P43                   | Desktop     | [703785faf9](https://linux-hardware.org/?probe=703785faf9) | Mar 21, 2025 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [2b8d965a19](https://linux-hardware.org/?probe=2b8d965a19) | Mar 19, 2025 |
| Gigabyte      | H410M H V3                  | Desktop     | [e0eb7cae1a](https://linux-hardware.org/?probe=e0eb7cae1a) | Mar 19, 2025 |
| HP            | 1495                        | Desktop     | [abcc376227](https://linux-hardware.org/?probe=abcc376227) | Mar 15, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d518898db1](https://linux-hardware.org/?probe=d518898db1) | Mar 14, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11e40071b8](https://linux-hardware.org/?probe=11e40071b8) | Mar 14, 2025 |
| ELSKY         | M219FN-6C                   | Desktop     | [0819c68770](https://linux-hardware.org/?probe=0819c68770) | Mar 12, 2025 |
| Dell          | 04N3DF A10                  | Server      | [f133c9e29f](https://linux-hardware.org/?probe=f133c9e29f) | Mar 12, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [9058ac67fc](https://linux-hardware.org/?probe=9058ac67fc) | Mar 10, 2025 |
| ASUSTek       | B85-PLUS                    | Desktop     | [12dff811e1](https://linux-hardware.org/?probe=12dff811e1) | Mar 10, 2025 |
| OrangePi      | 3 LTS                       | Soc         | [006d4838f9](https://linux-hardware.org/?probe=006d4838f9) | Mar 09, 2025 |
| Pegatron      | EVANS                       | Desktop     | [d5171b4701](https://linux-hardware.org/?probe=d5171b4701) | Mar 08, 2025 |
| ASRock        | ConRoe1333-D667             | Desktop     | [ccc4dcc6a4](https://linux-hardware.org/?probe=ccc4dcc6a4) | Mar 07, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [65182d1c75](https://linux-hardware.org/?probe=65182d1c75) | Mar 07, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c0df4a632](https://linux-hardware.org/?probe=4c0df4a632) | Mar 06, 2025 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [8d2930b96e](https://linux-hardware.org/?probe=8d2930b96e) | Mar 06, 2025 |
| HP            | 3397                        | Desktop     | [587f49298b](https://linux-hardware.org/?probe=587f49298b) | Mar 05, 2025 |
| MCT           | Capri 411C47600014          | Server      | [053d891ec4](https://linux-hardware.org/?probe=053d891ec4) | Mar 04, 2025 |
| IceWhale T... | ZMB216-i ZMB                | Desktop     | [4c45b06c90](https://linux-hardware.org/?probe=4c45b06c90) | Mar 01, 2025 |
| Dell          | Inspiron 5521               | Notebook    | [55c7bb12ed](https://linux-hardware.org/?probe=55c7bb12ed) | Feb 27, 2025 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [582931ae92](https://linux-hardware.org/?probe=582931ae92) | Feb 18, 2025 |
| ASRock        | X570 Steel Legend           | Desktop     | [7cde997af7](https://linux-hardware.org/?probe=7cde997af7) | Feb 16, 2025 |
| HP            | Laptop 15-da0xxx            | Notebook    | [9d7f9a5008](https://linux-hardware.org/?probe=9d7f9a5008) | Feb 15, 2025 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [b15e4a5767](https://linux-hardware.org/?probe=b15e4a5767) | Feb 11, 2025 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [35b6f20e8d](https://linux-hardware.org/?probe=35b6f20e8d) | Feb 05, 2025 |
| Gigabyte      | H610M S2H V3 DDR4           | Desktop     | [45e02baaa7](https://linux-hardware.org/?probe=45e02baaa7) | Feb 04, 2025 |
| HP            | ProLiant DL180 G6           | Server      | [de88ce9058](https://linux-hardware.org/?probe=de88ce9058) | Feb 02, 2025 |
| Unknown       | Unknown                     | Soc         | [1a66926448](https://linux-hardware.org/?probe=1a66926448) | Feb 02, 2025 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [5c17f992f2](https://linux-hardware.org/?probe=5c17f992f2) | Jan 31, 2025 |
| HP            | G62                         | Notebook    | [0b03652865](https://linux-hardware.org/?probe=0b03652865) | Jan 27, 2025 |
| ASRock        | B450M Pro4-F                | Desktop     | [22b68f9601](https://linux-hardware.org/?probe=22b68f9601) | Jan 27, 2025 |
| Acer          | AOD257                      | Notebook    | [a7bbedaebd](https://linux-hardware.org/?probe=a7bbedaebd) | Jan 27, 2025 |
| Positivo B... | VJFE54F11X-B3711H           | Notebook    | [39f4c96b4a](https://linux-hardware.org/?probe=39f4c96b4a) | Jan 25, 2025 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [3c0a5cde0c](https://linux-hardware.org/?probe=3c0a5cde0c) | Jan 24, 2025 |
| Acer          | Extensa 215-32              | Notebook    | [af9d70e82c](https://linux-hardware.org/?probe=af9d70e82c) | Jan 24, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [86a5a19643](https://linux-hardware.org/?probe=86a5a19643) | Jan 20, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [cb08c9120c](https://linux-hardware.org/?probe=cb08c9120c) | Jan 20, 2025 |
| HP            | 1790                        | Desktop     | [32de7b3c8e](https://linux-hardware.org/?probe=32de7b3c8e) | Jan 20, 2025 |
| IBM           | 94Y7718 SIT                 | Server      | [bccdeb06cd](https://linux-hardware.org/?probe=bccdeb06cd) | Jan 19, 2025 |
| MSI           | PRO B660M-P DDR4            | Desktop     | [0000452d93](https://linux-hardware.org/?probe=0000452d93) | Jan 19, 2025 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [5b98dd4ff7](https://linux-hardware.org/?probe=5b98dd4ff7) | Jan 16, 2025 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [29934f1cac](https://linux-hardware.org/?probe=29934f1cac) | Jan 15, 2025 |
| Acer          | AOD270                      | Notebook    | [a7314c5fcd](https://linux-hardware.org/?probe=a7314c5fcd) | Jan 14, 2025 |
| Acer          | AOD270                      | Notebook    | [955a47ce14](https://linux-hardware.org/?probe=955a47ce14) | Jan 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [e1bd5d456b](https://linux-hardware.org/?probe=e1bd5d456b) | Jan 12, 2025 |
| HP            | Synoden                     | Server      | [81f218517b](https://linux-hardware.org/?probe=81f218517b) | Jan 12, 2025 |
| Positivo B... | VJFE59F11X-B1011H           | Notebook    | [61ca13cb48](https://linux-hardware.org/?probe=61ca13cb48) | Jan 10, 2025 |
| Unknown       | Unknown                     | Soc         | [1feb0ee53b](https://linux-hardware.org/?probe=1feb0ee53b) | Jan 08, 2025 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [ed27c636e3](https://linux-hardware.org/?probe=ed27c636e3) | Jan 07, 2025 |
| MSI           | GE60 0NC\0ND                | Notebook    | [423eca6c8c](https://linux-hardware.org/?probe=423eca6c8c) | Jan 05, 2025 |
| Dell          | 09KPNV A00                  | Desktop     | [d2a1de9dc7](https://linux-hardware.org/?probe=d2a1de9dc7) | Jan 04, 2025 |
| ASRock        | J5040-ITX                   | Desktop     | [cfe9a3c37e](https://linux-hardware.org/?probe=cfe9a3c37e) | Dec 28, 2024 |
| Intel         | S5000VSA                    | Server      | [ec199dc348](https://linux-hardware.org/?probe=ec199dc348) | Dec 27, 2024 |
| Insyde        | Purley                      | Server      | [943c34d6fe](https://linux-hardware.org/?probe=943c34d6fe) | Dec 27, 2024 |
| Intel         | S5520UR E22554-751          | Server      | [e32d8048dd](https://linux-hardware.org/?probe=e32d8048dd) | Dec 27, 2024 |
| Insyde        | Purley                      | Server      | [0a1ed074fe](https://linux-hardware.org/?probe=0a1ed074fe) | Dec 27, 2024 |
| IBM           | 94Y7718 SIT                 | Server      | [133f7bc9a5](https://linux-hardware.org/?probe=133f7bc9a5) | Dec 27, 2024 |
| IBM           | 69Y1006 SIT                 | Server      | [31413f8015](https://linux-hardware.org/?probe=31413f8015) | Dec 27, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [31f432f98b](https://linux-hardware.org/?probe=31f432f98b) | Dec 26, 2024 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [293052fc3b](https://linux-hardware.org/?probe=293052fc3b) | Dec 24, 2024 |
| Dell          | Latitude E6410              | Notebook    | [b51666dd6f](https://linux-hardware.org/?probe=b51666dd6f) | Dec 19, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [30c96f3002](https://linux-hardware.org/?probe=30c96f3002) | Dec 19, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [379d336bc2](https://linux-hardware.org/?probe=379d336bc2) | Dec 16, 2024 |
| Acer          | Aspire 5733                 | Notebook    | [edc4741bd8](https://linux-hardware.org/?probe=edc4741bd8) | Dec 15, 2024 |
| Acer          | Aspire 5733                 | Notebook    | [b7af1c256d](https://linux-hardware.org/?probe=b7af1c256d) | Dec 15, 2024 |
| OEM           | B75 Ver:1.41                | Desktop     | [26fc19a77d](https://linux-hardware.org/?probe=26fc19a77d) | Dec 15, 2024 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [5312d0eb27](https://linux-hardware.org/?probe=5312d0eb27) | Dec 04, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [81eb56f0f7](https://linux-hardware.org/?probe=81eb56f0f7) | Dec 03, 2024 |
| TI            | AM335x BeagleBone Black ... | Soc         | [75a37fdb48](https://linux-hardware.org/?probe=75a37fdb48) | Dec 02, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2e9144632c](https://linux-hardware.org/?probe=2e9144632c) | Dec 02, 2024 |
| HP            | 339A                        | Desktop     | [c64449a47e](https://linux-hardware.org/?probe=c64449a47e) | Dec 02, 2024 |
| Clevo         | W35_37ET                    | Notebook    | [8c4d3d1caa](https://linux-hardware.org/?probe=8c4d3d1caa) | Nov 30, 2024 |
| Clevo         | W35_37ET                    | Notebook    | [4b7ce97c36](https://linux-hardware.org/?probe=4b7ce97c36) | Nov 30, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [c865d51386](https://linux-hardware.org/?probe=c865d51386) | Nov 30, 2024 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [3b5585bec8](https://linux-hardware.org/?probe=3b5585bec8) | Nov 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [45fd5080cc](https://linux-hardware.org/?probe=45fd5080cc) | Nov 26, 2024 |
| MSI           | 880GM-E41                   | Desktop     | [d2d4d7473b](https://linux-hardware.org/?probe=d2d4d7473b) | Nov 26, 2024 |
| Supermicro    | X10DRH-iT                   | Server      | [f59d7a8db6](https://linux-hardware.org/?probe=f59d7a8db6) | Nov 25, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7b394d91fc](https://linux-hardware.org/?probe=7b394d91fc) | Nov 24, 2024 |
| ASUSTek       | Rampage III GENE            | Desktop     | [89662fc2f1](https://linux-hardware.org/?probe=89662fc2f1) | Nov 23, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5b66a14834](https://linux-hardware.org/?probe=5b66a14834) | Nov 20, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [a13d39cf07](https://linux-hardware.org/?probe=a13d39cf07) | Nov 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [69c39a72ba](https://linux-hardware.org/?probe=69c39a72ba) | Nov 18, 2024 |
| HP            | Notebook                    | Notebook    | [9ec4cde8a4](https://linux-hardware.org/?probe=9ec4cde8a4) | Nov 18, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [de3a243820](https://linux-hardware.org/?probe=de3a243820) | Nov 17, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [64e57644f0](https://linux-hardware.org/?probe=64e57644f0) | Nov 17, 2024 |
| Acer          | FI946GZG                    | Desktop     | [a7f49035aa](https://linux-hardware.org/?probe=a7f49035aa) | Nov 16, 2024 |
| Acer          | FI946GZG                    | Desktop     | [9d9080e57a](https://linux-hardware.org/?probe=9d9080e57a) | Nov 16, 2024 |
| Dell          | 0KWVT8 A00                  | Desktop     | [cbf908cc03](https://linux-hardware.org/?probe=cbf908cc03) | Nov 13, 2024 |
| Gigabyte      | GA-MA78GM-DS2H              | Desktop     | [5b63d6de06](https://linux-hardware.org/?probe=5b63d6de06) | Nov 12, 2024 |
| Dell          | Inspiron 5720               | Notebook    | [5c8bf7fb22](https://linux-hardware.org/?probe=5c8bf7fb22) | Nov 09, 2024 |
| HP            | 1495                        | Desktop     | [5778238fb5](https://linux-hardware.org/?probe=5778238fb5) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | Desktop     | [a71b3adfe4](https://linux-hardware.org/?probe=a71b3adfe4) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | Desktop     | [03ca590abe](https://linux-hardware.org/?probe=03ca590abe) | Nov 09, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [a66d7f6087](https://linux-hardware.org/?probe=a66d7f6087) | Nov 09, 2024 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [7e99679aa4](https://linux-hardware.org/?probe=7e99679aa4) | Nov 07, 2024 |
| MSI           | Thin GF63 12UCX             | Notebook    | [20bee02e0a](https://linux-hardware.org/?probe=20bee02e0a) | Nov 07, 2024 |
| Dell          | 0V8WGR A00                  | Desktop     | [8b995d3611](https://linux-hardware.org/?probe=8b995d3611) | Nov 05, 2024 |
| PC Special... | 14 Fusion IV                | Notebook    | [1ef6e14285](https://linux-hardware.org/?probe=1ef6e14285) | Nov 04, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [11a8379f5e](https://linux-hardware.org/?probe=11a8379f5e) | Nov 03, 2024 |
| Insyde        | GeminiLake                  | Notebook    | [df7e9af6a4](https://linux-hardware.org/?probe=df7e9af6a4) | Nov 02, 2024 |
| Unknown       | Unknown                     | Soc         | [9fba92e2b4](https://linux-hardware.org/?probe=9fba92e2b4) | Nov 02, 2024 |
| HP            | 1495                        | Desktop     | [00133664ce](https://linux-hardware.org/?probe=00133664ce) | Nov 02, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [9db603450a](https://linux-hardware.org/?probe=9db603450a) | Nov 01, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [597318b1e3](https://linux-hardware.org/?probe=597318b1e3) | Nov 01, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [009c07413d](https://linux-hardware.org/?probe=009c07413d) | Oct 29, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b93eb7acfd](https://linux-hardware.org/?probe=b93eb7acfd) | Oct 28, 2024 |
| IBASE Tech... | MB980VF B1                  | Desktop     | [0950d198d6](https://linux-hardware.org/?probe=0950d198d6) | Oct 27, 2024 |
| IBASE Tech... | MB980VF B1                  | Desktop     | [b7bff2d716](https://linux-hardware.org/?probe=b7bff2d716) | Oct 27, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [5226011358](https://linux-hardware.org/?probe=5226011358) | Oct 27, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5Q1E    | Notebook    | [b36104396e](https://linux-hardware.org/?probe=b36104396e) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [5938a70edc](https://linux-hardware.org/?probe=5938a70edc) | Oct 26, 2024 |
| Acer          | FI946GZG                    | Desktop     | [57835df373](https://linux-hardware.org/?probe=57835df373) | Oct 26, 2024 |
| Sony          | VGN-NW26M                   | Notebook    | [b7d8f997e5](https://linux-hardware.org/?probe=b7d8f997e5) | Oct 25, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [338df85e2c](https://linux-hardware.org/?probe=338df85e2c) | Oct 23, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [0642feaea1](https://linux-hardware.org/?probe=0642feaea1) | Oct 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [b13668c203](https://linux-hardware.org/?probe=b13668c203) | Oct 22, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [4f556994ff](https://linux-hardware.org/?probe=4f556994ff) | Oct 20, 2024 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [904c305f40](https://linux-hardware.org/?probe=904c305f40) | Oct 20, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [8a3b4ef522](https://linux-hardware.org/?probe=8a3b4ef522) | Oct 20, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [8f4ed9b69e](https://linux-hardware.org/?probe=8f4ed9b69e) | Oct 20, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [daf26b85a4](https://linux-hardware.org/?probe=daf26b85a4) | Oct 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d01b3d0dd1](https://linux-hardware.org/?probe=d01b3d0dd1) | Oct 18, 2024 |
| Dell          | Latitude E6520              | Notebook    | [aff7fc0640](https://linux-hardware.org/?probe=aff7fc0640) | Oct 16, 2024 |
| MSI           | MS-7071                     | Desktop     | [6cf8497c89](https://linux-hardware.org/?probe=6cf8497c89) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | Desktop     | [e8c22589e3](https://linux-hardware.org/?probe=e8c22589e3) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | Desktop     | [e2cdb3ceef](https://linux-hardware.org/?probe=e2cdb3ceef) | Oct 16, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [292dcee628](https://linux-hardware.org/?probe=292dcee628) | Oct 15, 2024 |
| Unknown       | Marble based on Qualcomm... | Soc         | [848397f66d](https://linux-hardware.org/?probe=848397f66d) | Oct 14, 2024 |
| SLIMBOOK      | Unknown                     | Notebook    | [a45b75d9ec](https://linux-hardware.org/?probe=a45b75d9ec) | Oct 14, 2024 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [434208e85f](https://linux-hardware.org/?probe=434208e85f) | Oct 12, 2024 |
| Acer          | Aspire A515-56              | Notebook    | [a61df1d187](https://linux-hardware.org/?probe=a61df1d187) | Oct 11, 2024 |
| ASRock        | H610M-HVS                   | Desktop     | [91361cad1e](https://linux-hardware.org/?probe=91361cad1e) | Oct 10, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2927ff6f0d](https://linux-hardware.org/?probe=2927ff6f0d) | Oct 09, 2024 |
| Acer          | FI946GZG                    | Desktop     | [92bd6f1fc1](https://linux-hardware.org/?probe=92bd6f1fc1) | Oct 09, 2024 |
| Acer          | FI946GZG                    | Desktop     | [535a355530](https://linux-hardware.org/?probe=535a355530) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [d0eaae2f60](https://linux-hardware.org/?probe=d0eaae2f60) | Oct 09, 2024 |
| ForeScout ... | 0VRCY5 A14                  | Server      | [4e8721ab88](https://linux-hardware.org/?probe=4e8721ab88) | Oct 04, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [1abb05bf25](https://linux-hardware.org/?probe=1abb05bf25) | Oct 03, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [eca6363c57](https://linux-hardware.org/?probe=eca6363c57) | Oct 02, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [3b48795f8e](https://linux-hardware.org/?probe=3b48795f8e) | Sep 30, 2024 |
| HP            | G60                         | Notebook    | [c4e7fe598d](https://linux-hardware.org/?probe=c4e7fe598d) | Sep 30, 2024 |
| HP            | 3397                        | Desktop     | [63009f600f](https://linux-hardware.org/?probe=63009f600f) | Sep 30, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbe298738b](https://linux-hardware.org/?probe=dbe298738b) | Sep 26, 2024 |
| Rockchip      | RK3399 EVB IND LPDDR4 Bo... | Soc         | [2609d42a42](https://linux-hardware.org/?probe=2609d42a42) | Sep 25, 2024 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [91c64d17ea](https://linux-hardware.org/?probe=91c64d17ea) | Sep 22, 2024 |
| Dell          | 0T065F A01                  | Desktop     | [bcbba2bc39](https://linux-hardware.org/?probe=bcbba2bc39) | Sep 21, 2024 |
| Acer          | FI946GZG                    | Desktop     | [38457fe3eb](https://linux-hardware.org/?probe=38457fe3eb) | Sep 20, 2024 |
| Acer          | FI946GZG                    | Desktop     | [7f888553ed](https://linux-hardware.org/?probe=7f888553ed) | Sep 20, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [b96fef78f4](https://linux-hardware.org/?probe=b96fef78f4) | Sep 20, 2024 |
| Acer          | Aspire ES1-533              | Notebook    | [238267b887](https://linux-hardware.org/?probe=238267b887) | Sep 20, 2024 |
| ASUSTek       | 1000                        | Notebook    | [4ba77b632f](https://linux-hardware.org/?probe=4ba77b632f) | Sep 20, 2024 |
| HP            | G60                         | Notebook    | [918e4c12c2](https://linux-hardware.org/?probe=918e4c12c2) | Sep 20, 2024 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [075f6eaa32](https://linux-hardware.org/?probe=075f6eaa32) | Sep 19, 2024 |
| Lenovo        | SHARKBAY SDK0J40697 WIN     | Desktop     | [6d2a1ac8e1](https://linux-hardware.org/?probe=6d2a1ac8e1) | Sep 18, 2024 |
| Microsoft     | Surface 3                   | Tablet      | [d3f7875b8b](https://linux-hardware.org/?probe=d3f7875b8b) | Sep 16, 2024 |
| Fujitsu       | D2619 S26361-D2619-A14 W... | Server      | [df81b53b94](https://linux-hardware.org/?probe=df81b53b94) | Sep 16, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [b1768b27cf](https://linux-hardware.org/?probe=b1768b27cf) | Sep 14, 2024 |
| Dell          | 0NNNCT A01                  | Desktop     | [c3aeffdb84](https://linux-hardware.org/?probe=c3aeffdb84) | Sep 13, 2024 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [0e9f60231f](https://linux-hardware.org/?probe=0e9f60231f) | Sep 11, 2024 |
| Unknown       | Wiren Board rev. 6.9.0 (... | Other       | [ae1973cba8](https://linux-hardware.org/?probe=ae1973cba8) | Sep 11, 2024 |
| Intel         | CRESCENTBAY                 | Desktop     | [14865f8a73](https://linux-hardware.org/?probe=14865f8a73) | Sep 10, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [ff593c19ff](https://linux-hardware.org/?probe=ff593c19ff) | Sep 10, 2024 |
| iEi           | SAX9 V1.00                  | Desktop     | [d25454a2fb](https://linux-hardware.org/?probe=d25454a2fb) | Sep 10, 2024 |
| Dell          | 0NNNCT A01                  | Desktop     | [c5d73da3a3](https://linux-hardware.org/?probe=c5d73da3a3) | Sep 09, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dc90d7b0f6](https://linux-hardware.org/?probe=dc90d7b0f6) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [4a801900e1](https://linux-hardware.org/?probe=4a801900e1) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1c6ee65d7a](https://linux-hardware.org/?probe=1c6ee65d7a) | Sep 09, 2024 |
| Radxa         | ZERO 3                      | Soc         | [2a505955f1](https://linux-hardware.org/?probe=2a505955f1) | Sep 09, 2024 |
| HP            | EliteBook 8760w             | Notebook    | [78169bfe9b](https://linux-hardware.org/?probe=78169bfe9b) | Sep 08, 2024 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [9d86f13601](https://linux-hardware.org/?probe=9d86f13601) | Sep 05, 2024 |
| HP            | 18E7                        | Desktop     | [dbea31ed81](https://linux-hardware.org/?probe=dbea31ed81) | Sep 02, 2024 |
| Positivo      | C8240AI-15                  | Notebook    | [cf5df4af8e](https://linux-hardware.org/?probe=cf5df4af8e) | Sep 02, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [5310dbbf32](https://linux-hardware.org/?probe=5310dbbf32) | Sep 01, 2024 |
| MSI           | B85M-G43                    | Desktop     | [374b7d32b3](https://linux-hardware.org/?probe=374b7d32b3) | Sep 01, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [6e978f31cf](https://linux-hardware.org/?probe=6e978f31cf) | Sep 01, 2024 |
| MSI           | X79A-GD45                   | Desktop     | [2f16c5924f](https://linux-hardware.org/?probe=2f16c5924f) | Aug 29, 2024 |
| ASUSTek       | P5B SE                      | Desktop     | [d545ce5d36](https://linux-hardware.org/?probe=d545ce5d36) | Aug 28, 2024 |
| Phoenix Co... | PSB514 A12                  | Desktop     | [b6636750fd](https://linux-hardware.org/?probe=b6636750fd) | Aug 25, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b4dc6d4025](https://linux-hardware.org/?probe=b4dc6d4025) | Aug 24, 2024 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [c0a760b1bf](https://linux-hardware.org/?probe=c0a760b1bf) | Aug 23, 2024 |
| TYAN Compu... | S5553GM2NR-2T-HE-B          | Desktop     | [81952b8f97](https://linux-hardware.org/?probe=81952b8f97) | Aug 23, 2024 |
| ASUSTek       | M4N78-AM                    | Desktop     | [b8ac55c9e9](https://linux-hardware.org/?probe=b8ac55c9e9) | Aug 22, 2024 |
| TI            | AM335x BeagleBone Black     | Soc         | [28a2645f4c](https://linux-hardware.org/?probe=28a2645f4c) | Aug 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [921ec4cff0](https://linux-hardware.org/?probe=921ec4cff0) | Aug 21, 2024 |
| ASRock        | X570 PG Velocita            | Desktop     | [a7fa96eb22](https://linux-hardware.org/?probe=a7fa96eb22) | Aug 21, 2024 |
| HP            | G60                         | Notebook    | [b27d94e4b9](https://linux-hardware.org/?probe=b27d94e4b9) | Aug 21, 2024 |
| HP            | G60                         | Notebook    | [98fc212513](https://linux-hardware.org/?probe=98fc212513) | Aug 21, 2024 |
| ASUSTek       | M4N78-AM                    | Desktop     | [c0fb89099b](https://linux-hardware.org/?probe=c0fb89099b) | Aug 20, 2024 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [1d9b0a4f71](https://linux-hardware.org/?probe=1d9b0a4f71) | Aug 19, 2024 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [c12d510377](https://linux-hardware.org/?probe=c12d510377) | Aug 19, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [48f20ce29b](https://linux-hardware.org/?probe=48f20ce29b) | Aug 19, 2024 |
| HP            | ProLiant DL60 Gen9          | Server      | [ac48708bdd](https://linux-hardware.org/?probe=ac48708bdd) | Aug 18, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [3d467b94d9](https://linux-hardware.org/?probe=3d467b94d9) | Aug 14, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [0e32b18772](https://linux-hardware.org/?probe=0e32b18772) | Aug 12, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [12d18c1ee6](https://linux-hardware.org/?probe=12d18c1ee6) | Aug 12, 2024 |
| Lenovo        | ThinkPad E490 20N8S0WH00    | Notebook    | [4df92c7741](https://linux-hardware.org/?probe=4df92c7741) | Aug 12, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [5aba1832f5](https://linux-hardware.org/?probe=5aba1832f5) | Aug 11, 2024 |
| Lenovo        | ThinkPad E595 20NF001HRT    | Notebook    | [ed43fa321d](https://linux-hardware.org/?probe=ed43fa321d) | Aug 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [32a29957a4](https://linux-hardware.org/?probe=32a29957a4) | Aug 10, 2024 |
| HP            | Mini China Mobile Editio... | Notebook    | [573e118166](https://linux-hardware.org/?probe=573e118166) | Aug 09, 2024 |
| HP            | Mini China Mobile Editio... | Notebook    | [f1700dec96](https://linux-hardware.org/?probe=f1700dec96) | Aug 09, 2024 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [7f7717743d](https://linux-hardware.org/?probe=7f7717743d) | Aug 08, 2024 |
| AZW           | MINI S 10                   | Desktop     | [62de36544b](https://linux-hardware.org/?probe=62de36544b) | Aug 08, 2024 |
| Radxa         | ROCK 4C+ (DT)               | Soc         | [bce627af57](https://linux-hardware.org/?probe=bce627af57) | Aug 06, 2024 |
| Dell          | 0GXM1W A00                  | Desktop     | [e80fba5694](https://linux-hardware.org/?probe=e80fba5694) | Aug 05, 2024 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [e7d1a5439b](https://linux-hardware.org/?probe=e7d1a5439b) | Aug 04, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [caf4309fbe](https://linux-hardware.org/?probe=caf4309fbe) | Aug 02, 2024 |
| HP            | 1998                        | Desktop     | [718d1847d7](https://linux-hardware.org/?probe=718d1847d7) | Aug 01, 2024 |
| Acer          | Aspire E5-523G              | Notebook    | [dcae9fea91](https://linux-hardware.org/?probe=dcae9fea91) | Aug 01, 2024 |
| Unknown       | Unknown                     | Soc         | [59672d4fe2](https://linux-hardware.org/?probe=59672d4fe2) | Aug 01, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f9b69bff33](https://linux-hardware.org/?probe=f9b69bff33) | Jul 31, 2024 |
| Acer          | AOD270                      | Notebook    | [086d69b5dc](https://linux-hardware.org/?probe=086d69b5dc) | Jul 31, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7a6c894fc9](https://linux-hardware.org/?probe=7a6c894fc9) | Jul 31, 2024 |
| Acer          | AOD270                      | Notebook    | [5a2f98fbf0](https://linux-hardware.org/?probe=5a2f98fbf0) | Jul 31, 2024 |
| Seco          | D62 B.1                     | Desktop     | [fa8221ca8a](https://linux-hardware.org/?probe=fa8221ca8a) | Jul 30, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [9845091f7e](https://linux-hardware.org/?probe=9845091f7e) | Jul 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [b83c73ebb9](https://linux-hardware.org/?probe=b83c73ebb9) | Jul 27, 2024 |
| Dell          | Latitude E6420              | Notebook    | [062d91bd4e](https://linux-hardware.org/?probe=062d91bd4e) | Jul 26, 2024 |
| NOBLEX        | NT1010E                     | Notebook    | [c27368454d](https://linux-hardware.org/?probe=c27368454d) | Jul 25, 2024 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [345e2f9291](https://linux-hardware.org/?probe=345e2f9291) | Jul 24, 2024 |
| Lenovo        | 3000 N100 0768FPG           | Notebook    | [1f529ec188](https://linux-hardware.org/?probe=1f529ec188) | Jul 24, 2024 |
| OrangePi      | Zero2 W                     | Soc         | [ffac8056dc](https://linux-hardware.org/?probe=ffac8056dc) | Jul 24, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6bfee437e7](https://linux-hardware.org/?probe=6bfee437e7) | Jul 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [af38eddfb9](https://linux-hardware.org/?probe=af38eddfb9) | Jul 23, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [03179392b1](https://linux-hardware.org/?probe=03179392b1) | Jul 22, 2024 |
| Gigabyte      | B365M H                     | Desktop     | [b2bc363dc6](https://linux-hardware.org/?probe=b2bc363dc6) | Jul 22, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d3a54a2ba6](https://linux-hardware.org/?probe=d3a54a2ba6) | Jul 22, 2024 |
| AMI           | Cherry Trail CR             | Notebook    | [bef52595c6](https://linux-hardware.org/?probe=bef52595c6) | Jul 21, 2024 |
| Dell          | 051FJ8 A02                  | Desktop     | [757139a0c9](https://linux-hardware.org/?probe=757139a0c9) | Jul 21, 2024 |
| ASUSTek       | VANGUARD B85                | Desktop     | [7453f3f267](https://linux-hardware.org/?probe=7453f3f267) | Jul 19, 2024 |
| IceWhale T... | ZBB001-BK10032 ZMB          | Desktop     | [334a362aba](https://linux-hardware.org/?probe=334a362aba) | Jul 19, 2024 |
| Unknown       | biqu RK3566-ROC-PC HDMI(... | Soc         | [3c3653ce84](https://linux-hardware.org/?probe=3c3653ce84) | Jul 13, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [ac4dbbb061](https://linux-hardware.org/?probe=ac4dbbb061) | Jul 12, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [52d8794632](https://linux-hardware.org/?probe=52d8794632) | Jul 11, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [19d6067144](https://linux-hardware.org/?probe=19d6067144) | Jul 08, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [cc46df44b5](https://linux-hardware.org/?probe=cc46df44b5) | Jul 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [e298a5c2b9](https://linux-hardware.org/?probe=e298a5c2b9) | Jul 06, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [6cadfd61f0](https://linux-hardware.org/?probe=6cadfd61f0) | Jul 05, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4625edbfa8](https://linux-hardware.org/?probe=4625edbfa8) | Jul 05, 2024 |
| Dell          | 06MC09 A00                  | Mini pc     | [12ba7ec8cc](https://linux-hardware.org/?probe=12ba7ec8cc) | Jul 03, 2024 |
| Dell          | 06MC09 A00                  | Mini pc     | [d6fc5e561e](https://linux-hardware.org/?probe=d6fc5e561e) | Jul 03, 2024 |
| HP            | 213D A01                    | Desktop     | [84f1dcac4f](https://linux-hardware.org/?probe=84f1dcac4f) | Jul 02, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c7aa930920](https://linux-hardware.org/?probe=c7aa930920) | Jul 01, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [80bbfc4e43](https://linux-hardware.org/?probe=80bbfc4e43) | Jun 30, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [b12e2708ad](https://linux-hardware.org/?probe=b12e2708ad) | Jun 30, 2024 |
| Unknown       | CN700-8237                  | Desktop     | [696664c26e](https://linux-hardware.org/?probe=696664c26e) | Jun 30, 2024 |
| ASUSTek       | M4N78-AM                    | Desktop     | [dcacfa2dba](https://linux-hardware.org/?probe=dcacfa2dba) | Jun 30, 2024 |
| HP            | ZBook 15u G5                | Notebook    | [026a2f799a](https://linux-hardware.org/?probe=026a2f799a) | Jun 30, 2024 |
| libre-comp... | roc-rk3328-cc               | Soc         | [2f3fe5fade](https://linux-hardware.org/?probe=2f3fe5fade) | Jun 30, 2024 |
| Tablet        | 8                           | Notebook    | [05e319ff90](https://linux-hardware.org/?probe=05e319ff90) | Jun 28, 2024 |
| MiTAC         | PH10CI AAG92370-407         | All in one  | [75f967b327](https://linux-hardware.org/?probe=75f967b327) | Jun 28, 2024 |
| MiTAC         | PH10CI AAG92370-407         | All in one  | [3b287b8f18](https://linux-hardware.org/?probe=3b287b8f18) | Jun 28, 2024 |
| Positivo B... | VJFE59F11X-B1011H           | Notebook    | [b3a0915574](https://linux-hardware.org/?probe=b3a0915574) | Jun 24, 2024 |
| MSI           | PE70 7RD                    | Notebook    | [26556b06ad](https://linux-hardware.org/?probe=26556b06ad) | Jun 24, 2024 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [715fa28bb7](https://linux-hardware.org/?probe=715fa28bb7) | Jun 23, 2024 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [7abc3101ea](https://linux-hardware.org/?probe=7abc3101ea) | Jun 22, 2024 |
| Toshiba       | Satellite L650D             | Notebook    | [09f8b8509c](https://linux-hardware.org/?probe=09f8b8509c) | Jun 22, 2024 |
| Daten Tecn... | DA5UP DC                    | Mini pc     | [512405af17](https://linux-hardware.org/?probe=512405af17) | Jun 21, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [9c05a4ef2d](https://linux-hardware.org/?probe=9c05a4ef2d) | Jun 20, 2024 |
| Dell          | 0F56WK A03                  | Desktop     | [98a85a6db0](https://linux-hardware.org/?probe=98a85a6db0) | Jun 19, 2024 |
| Dell          | Latitude E6420              | Notebook    | [07364acb42](https://linux-hardware.org/?probe=07364acb42) | Jun 19, 2024 |
| Gigabyte      | B760M H DDR4                | Desktop     | [8d6956f9a6](https://linux-hardware.org/?probe=8d6956f9a6) | Jun 17, 2024 |
| Gigabyte      | B760M H DDR4                | Desktop     | [3e87b834d6](https://linux-hardware.org/?probe=3e87b834d6) | Jun 17, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [abf647d335](https://linux-hardware.org/?probe=abf647d335) | Jun 10, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [4fc663cdab](https://linux-hardware.org/?probe=4fc663cdab) | Jun 10, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [09b3b01ee7](https://linux-hardware.org/?probe=09b3b01ee7) | Jun 07, 2024 |
| Lenovo        | B490 37722QP                | Notebook    | [d8afa9ab6e](https://linux-hardware.org/?probe=d8afa9ab6e) | Jun 07, 2024 |
| Lenovo        | B490 37722QP                | Notebook    | [981e272711](https://linux-hardware.org/?probe=981e272711) | Jun 06, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [8fbbbe6686](https://linux-hardware.org/?probe=8fbbbe6686) | Jun 05, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [eeb2f4e975](https://linux-hardware.org/?probe=eeb2f4e975) | Jun 05, 2024 |
| HP            | EliteBook 725 G4            | Notebook    | [5a8af90597](https://linux-hardware.org/?probe=5a8af90597) | Jun 04, 2024 |
| HP            | EliteBook 725 G4            | Notebook    | [ddcee8dc11](https://linux-hardware.org/?probe=ddcee8dc11) | Jun 04, 2024 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [aac83e9625](https://linux-hardware.org/?probe=aac83e9625) | Jun 03, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [f8ad181953](https://linux-hardware.org/?probe=f8ad181953) | Jun 02, 2024 |
| Acer          | FI946GZG                    | Desktop     | [76cc9c0af8](https://linux-hardware.org/?probe=76cc9c0af8) | Jun 01, 2024 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [4ac8e343f3](https://linux-hardware.org/?probe=4ac8e343f3) | May 30, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [c4f21338da](https://linux-hardware.org/?probe=c4f21338da) | May 27, 2024 |
| sunxi         | Unknown                     | Soc         | [b687301078](https://linux-hardware.org/?probe=b687301078) | May 24, 2024 |
| sunxi         | Unknown                     | Soc         | [f1ca318cb1](https://linux-hardware.org/?probe=f1ca318cb1) | May 22, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| Acer          | FI946GZG                    | Desktop     | [0cfa96d8b2](https://linux-hardware.org/?probe=0cfa96d8b2) | May 19, 2024 |
| Acer          | FI946GZG                    | Desktop     | [6abf4b2ff8](https://linux-hardware.org/?probe=6abf4b2ff8) | May 18, 2024 |
| Acer          | FI946GZG                    | Desktop     | [a4b0b80358](https://linux-hardware.org/?probe=a4b0b80358) | May 18, 2024 |
| Acer          | FI946GZG                    | Desktop     | [988cb72164](https://linux-hardware.org/?probe=988cb72164) | May 18, 2024 |
| Unknown       | CN700-8237                  | Desktop     | [45ae7f3f3d](https://linux-hardware.org/?probe=45ae7f3f3d) | May 17, 2024 |
| ASUSTek       | M4N78-AM                    | Desktop     | [b4082fa5bc](https://linux-hardware.org/?probe=b4082fa5bc) | May 17, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [29e720dc59](https://linux-hardware.org/?probe=29e720dc59) | May 15, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [a3d788cabf](https://linux-hardware.org/?probe=a3d788cabf) | May 15, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [8d96e5f65b](https://linux-hardware.org/?probe=8d96e5f65b) | May 15, 2024 |
| ASUSTek       | P5PL2                       | Desktop     | [fba00cbc3b](https://linux-hardware.org/?probe=fba00cbc3b) | May 14, 2024 |
| ASUSTek       | P5PL2                       | Desktop     | [299b8ee2c4](https://linux-hardware.org/?probe=299b8ee2c4) | May 14, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [356bb616db](https://linux-hardware.org/?probe=356bb616db) | May 13, 2024 |
| Dell          | Precision M4700             | Notebook    | [3025a7f21e](https://linux-hardware.org/?probe=3025a7f21e) | May 13, 2024 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [a883753e51](https://linux-hardware.org/?probe=a883753e51) | May 13, 2024 |
| Lenovo        | ThinkPad T430 2349BG6       | Notebook    | [590a71a235](https://linux-hardware.org/?probe=590a71a235) | May 13, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [94e1335220](https://linux-hardware.org/?probe=94e1335220) | May 13, 2024 |
| Dell          | Precision 5510              | Notebook    | [dfe5317b14](https://linux-hardware.org/?probe=dfe5317b14) | May 12, 2024 |
| Unknown       | 775V88+                     | Desktop     | [73f73bf5c8](https://linux-hardware.org/?probe=73f73bf5c8) | May 11, 2024 |
| Dell          | Precision 5510              | Notebook    | [f16ec110d5](https://linux-hardware.org/?probe=f16ec110d5) | May 11, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [f160688603](https://linux-hardware.org/?probe=f160688603) | May 10, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [79ec6e2044](https://linux-hardware.org/?probe=79ec6e2044) | May 09, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [801eeb31ef](https://linux-hardware.org/?probe=801eeb31ef) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c01de63e1](https://linux-hardware.org/?probe=7c01de63e1) | May 08, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ab33f7c9fc](https://linux-hardware.org/?probe=ab33f7c9fc) | May 06, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [264e965e8b](https://linux-hardware.org/?probe=264e965e8b) | May 04, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f6497f948](https://linux-hardware.org/?probe=8f6497f948) | May 04, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [27d57e495a](https://linux-hardware.org/?probe=27d57e495a) | May 04, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [f4dbf33638](https://linux-hardware.org/?probe=f4dbf33638) | May 02, 2024 |
| Dell          | Precision 5510              | Notebook    | [a010faffda](https://linux-hardware.org/?probe=a010faffda) | May 01, 2024 |
| Acer          | Aspire M5910                | Desktop     | [61b5809dc9](https://linux-hardware.org/?probe=61b5809dc9) | May 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90d5348bf5](https://linux-hardware.org/?probe=90d5348bf5) | Apr 28, 2024 |
| Acer          | Aspire E1-532               | Notebook    | [b50154d060](https://linux-hardware.org/?probe=b50154d060) | Apr 28, 2024 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [d486386bde](https://linux-hardware.org/?probe=d486386bde) | Apr 26, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [a5fcd90239](https://linux-hardware.org/?probe=a5fcd90239) | Apr 26, 2024 |
| Dell          | Precision M6800             | Notebook    | [1d41e8bb92](https://linux-hardware.org/?probe=1d41e8bb92) | Apr 25, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a61a96f7dd](https://linux-hardware.org/?probe=a61a96f7dd) | Apr 24, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [e61e4963d5](https://linux-hardware.org/?probe=e61e4963d5) | Apr 23, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [50751e1c9e](https://linux-hardware.org/?probe=50751e1c9e) | Apr 22, 2024 |
| Acer          | Aspire S3                   | Notebook    | [e43ba2d3ae](https://linux-hardware.org/?probe=e43ba2d3ae) | Apr 21, 2024 |
| Colorful T... | C.A68M-E V15                | Desktop     | [b0b7690daa](https://linux-hardware.org/?probe=b0b7690daa) | Apr 20, 2024 |
| Dell          | Precision M6800             | Notebook    | [c44a2aee51](https://linux-hardware.org/?probe=c44a2aee51) | Apr 20, 2024 |
| Unknown       | i855-W83627HF               | Desktop     | [e1c3562c4a](https://linux-hardware.org/?probe=e1c3562c4a) | Apr 18, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [01121cc898](https://linux-hardware.org/?probe=01121cc898) | Apr 18, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| HP            | 805B                        | Desktop     | [d5bf7c2652](https://linux-hardware.org/?probe=d5bf7c2652) | Apr 18, 2024 |
| HP            | 245 G6                      | Notebook    | [17b7e55361](https://linux-hardware.org/?probe=17b7e55361) | Apr 17, 2024 |
| HP            | 245 G6                      | Notebook    | [7c3534813c](https://linux-hardware.org/?probe=7c3534813c) | Apr 17, 2024 |
| Supermicro    | X11DPi-NT                   | Server      | [5a3102ebe7](https://linux-hardware.org/?probe=5a3102ebe7) | Apr 17, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [0d46687bb7](https://linux-hardware.org/?probe=0d46687bb7) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| AMI           | Cherry Trail CR             | Desktop     | [e60bc95699](https://linux-hardware.org/?probe=e60bc95699) | Apr 16, 2024 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [7ccf67d720](https://linux-hardware.org/?probe=7ccf67d720) | Apr 16, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [7cad8d2493](https://linux-hardware.org/?probe=7cad8d2493) | Apr 16, 2024 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [1ede6792e9](https://linux-hardware.org/?probe=1ede6792e9) | Apr 16, 2024 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [d6865e9438](https://linux-hardware.org/?probe=d6865e9438) | Apr 14, 2024 |
| Dell          | 0FRVY0 A00                  | Server      | [097c771b65](https://linux-hardware.org/?probe=097c771b65) | Apr 13, 2024 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [84f25faab3](https://linux-hardware.org/?probe=84f25faab3) | Apr 12, 2024 |
| ASRock        | Z690 PG Riptide             | Desktop     | [b5891958b5](https://linux-hardware.org/?probe=b5891958b5) | Apr 12, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [716fbdb5b2](https://linux-hardware.org/?probe=716fbdb5b2) | Apr 12, 2024 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [57b8f56426](https://linux-hardware.org/?probe=57b8f56426) | Apr 12, 2024 |
| Olimex        | A20-OLinuXino-LIME2-eMMC    | Soc         | [37be09f11b](https://linux-hardware.org/?probe=37be09f11b) | Apr 11, 2024 |
| HP            | 1998                        | Desktop     | [c0b0ec87ec](https://linux-hardware.org/?probe=c0b0ec87ec) | Apr 10, 2024 |
| HP            | Presario V6000 (GH918EA#... | Notebook    | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [c3ee8b2d3d](https://linux-hardware.org/?probe=c3ee8b2d3d) | Apr 09, 2024 |
| Lenovo        | 32E6 NOK                    | Desktop     | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a50be3e60f](https://linux-hardware.org/?probe=a50be3e60f) | Apr 09, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [fb71c7fef7](https://linux-hardware.org/?probe=fb71c7fef7) | Apr 08, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a0b38f568d](https://linux-hardware.org/?probe=a0b38f568d) | Apr 08, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [708da72614](https://linux-hardware.org/?probe=708da72614) | Apr 07, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [e927b8e190](https://linux-hardware.org/?probe=e927b8e190) | Apr 06, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [304df5369f](https://linux-hardware.org/?probe=304df5369f) | Apr 06, 2024 |
| Acer          | Aspire 3690                 | Notebook    | [a3091a1ceb](https://linux-hardware.org/?probe=a3091a1ceb) | Apr 06, 2024 |
| MSI           | MS-B0A21                    | Desktop     | [e74fc30957](https://linux-hardware.org/?probe=e74fc30957) | Apr 05, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [e759ee33bf](https://linux-hardware.org/?probe=e759ee33bf) | Apr 04, 2024 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [0c26980268](https://linux-hardware.org/?probe=0c26980268) | Apr 03, 2024 |
| Juana Mans... | SF20GM7                     | Notebook    | [8571d52a38](https://linux-hardware.org/?probe=8571d52a38) | Apr 02, 2024 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [b45101bd55](https://linux-hardware.org/?probe=b45101bd55) | Apr 02, 2024 |
| Rockchip      | Orange Pi 5                 | Soc         | [0bc6342638](https://linux-hardware.org/?probe=0bc6342638) | Apr 02, 2024 |
| ASUSTek       | N55SF                       | Notebook    | [69918bf880](https://linux-hardware.org/?probe=69918bf880) | Apr 01, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8875ed3afe](https://linux-hardware.org/?probe=8875ed3afe) | Apr 01, 2024 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [38d1d0b6b6](https://linux-hardware.org/?probe=38d1d0b6b6) | Mar 31, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [8b3c41683d](https://linux-hardware.org/?probe=8b3c41683d) | Mar 30, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [7542f194a2](https://linux-hardware.org/?probe=7542f194a2) | Mar 28, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [91c6a3e118](https://linux-hardware.org/?probe=91c6a3e118) | Mar 28, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [34d7c41e80](https://linux-hardware.org/?probe=34d7c41e80) | Mar 28, 2024 |
| ASUSTek       | F52Q                        | Notebook    | [edb335c489](https://linux-hardware.org/?probe=edb335c489) | Mar 27, 2024 |
| Digma         | EVE 15 C419 ES5065EW        | Notebook    | [83810dcd33](https://linux-hardware.org/?probe=83810dcd33) | Mar 26, 2024 |
| HP            | Presario V2000 (EH459UA#... | Notebook    | [af3a09ea38](https://linux-hardware.org/?probe=af3a09ea38) | Mar 26, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [6940ab6143](https://linux-hardware.org/?probe=6940ab6143) | Mar 24, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [05267117e8](https://linux-hardware.org/?probe=05267117e8) | Mar 23, 2024 |
| Primux Tec... | Primux ioxbook 1402FX       | Notebook    | [53e6d67001](https://linux-hardware.org/?probe=53e6d67001) | Mar 23, 2024 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [4558c9a4f4](https://linux-hardware.org/?probe=4558c9a4f4) | Mar 22, 2024 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [870960dbb0](https://linux-hardware.org/?probe=870960dbb0) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| MSI           | Z97 GAMING 3                | Desktop     | [ed6f176128](https://linux-hardware.org/?probe=ed6f176128) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | Desktop     | [aad6effeb0](https://linux-hardware.org/?probe=aad6effeb0) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [fecb6cf968](https://linux-hardware.org/?probe=fecb6cf968) | Mar 18, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [e467a62b44](https://linux-hardware.org/?probe=e467a62b44) | Mar 18, 2024 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [0018e3e74d](https://linux-hardware.org/?probe=0018e3e74d) | Mar 16, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [08ca6f8423](https://linux-hardware.org/?probe=08ca6f8423) | Mar 14, 2024 |
| Dell          | Latitude 5401               | Notebook    | [651b3a2f09](https://linux-hardware.org/?probe=651b3a2f09) | Mar 14, 2024 |
| Toshiba       | All In One PC MP            | All in one  | [540c821d0f](https://linux-hardware.org/?probe=540c821d0f) | Mar 14, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [6d006ade6c](https://linux-hardware.org/?probe=6d006ade6c) | Mar 13, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [f7ddcc5c64](https://linux-hardware.org/?probe=f7ddcc5c64) | Mar 13, 2024 |
| Intel         | X58 V1608                   | Desktop     | [48e5f0f5a6](https://linux-hardware.org/?probe=48e5f0f5a6) | Mar 13, 2024 |
| Intel         | X58 V1608                   | Desktop     | [84ccc96b6b](https://linux-hardware.org/?probe=84ccc96b6b) | Mar 13, 2024 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [2a14a96457](https://linux-hardware.org/?probe=2a14a96457) | Mar 12, 2024 |
| Dell          | System XPS L702X            | Notebook    | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| Supermicro    | X9DR3-F                     | Desktop     | [f4f1646c44](https://linux-hardware.org/?probe=f4f1646c44) | Mar 10, 2024 |
| HPE           | ProLiant DL20 Gen10 Plus    | Server      | [afb2f8105a](https://linux-hardware.org/?probe=afb2f8105a) | Mar 09, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [a690fc2f4c](https://linux-hardware.org/?probe=a690fc2f4c) | Mar 06, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [cad73d3451](https://linux-hardware.org/?probe=cad73d3451) | Mar 06, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [d6aa64ff6c](https://linux-hardware.org/?probe=d6aa64ff6c) | Mar 06, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [585ba3971c](https://linux-hardware.org/?probe=585ba3971c) | Mar 05, 2024 |
| Rockchip      | Unknown                     | Soc         | [3fecbdffcd](https://linux-hardware.org/?probe=3fecbdffcd) | Mar 05, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [35d70301d6](https://linux-hardware.org/?probe=35d70301d6) | Mar 04, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [dede36b712](https://linux-hardware.org/?probe=dede36b712) | Mar 04, 2024 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [21f2a28872](https://linux-hardware.org/?probe=21f2a28872) | Mar 04, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [e69e7cf8f3](https://linux-hardware.org/?probe=e69e7cf8f3) | Mar 02, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [f526190f31](https://linux-hardware.org/?probe=f526190f31) | Mar 01, 2024 |
| Pegatron      | IPM41-D3                    | Desktop     | [5249318369](https://linux-hardware.org/?probe=5249318369) | Feb 29, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [66a88413c4](https://linux-hardware.org/?probe=66a88413c4) | Feb 28, 2024 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [57284c6e0e](https://linux-hardware.org/?probe=57284c6e0e) | Feb 28, 2024 |
| VANT          | MOOVE2-14                   | Notebook    | [9d5df13f40](https://linux-hardware.org/?probe=9d5df13f40) | Feb 27, 2024 |
| HP            | ProLiant DL165 G7           | Server      | [8850a77792](https://linux-hardware.org/?probe=8850a77792) | Feb 27, 2024 |
| Packard Be... | H17HV                       | Notebook    | [aa7bdcf198](https://linux-hardware.org/?probe=aa7bdcf198) | Feb 27, 2024 |
| ASUSTek       | M2N-E                       | Desktop     | [b3041e34a7](https://linux-hardware.org/?probe=b3041e34a7) | Feb 27, 2024 |
| HP            | ProBook 4540s               | Notebook    | [da8c81f864](https://linux-hardware.org/?probe=da8c81f864) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [ad9632b089](https://linux-hardware.org/?probe=ad9632b089) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [d44ed1a56f](https://linux-hardware.org/?probe=d44ed1a56f) | Feb 26, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [16759c3ced](https://linux-hardware.org/?probe=16759c3ced) | Feb 26, 2024 |
| HP            | Pavilion dv7                | Notebook    | [4712b3d187](https://linux-hardware.org/?probe=4712b3d187) | Feb 25, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [702dee066a](https://linux-hardware.org/?probe=702dee066a) | Feb 25, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [cf8780be93](https://linux-hardware.org/?probe=cf8780be93) | Feb 24, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [dc0f4d581f](https://linux-hardware.org/?probe=dc0f4d581f) | Feb 23, 2024 |
| congatec      | conga-MA7 B.4               | Mini pc     | [3ebbc89b09](https://linux-hardware.org/?probe=3ebbc89b09) | Feb 23, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [033fe9a8a6](https://linux-hardware.org/?probe=033fe9a8a6) | Feb 22, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [ed5e87fbaf](https://linux-hardware.org/?probe=ed5e87fbaf) | Feb 21, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [2d163839aa](https://linux-hardware.org/?probe=2d163839aa) | Feb 21, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [ec826c4feb](https://linux-hardware.org/?probe=ec826c4feb) | Feb 20, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [847d92dde1](https://linux-hardware.org/?probe=847d92dde1) | Feb 20, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ed69d93c9c](https://linux-hardware.org/?probe=ed69d93c9c) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [b6fb308e13](https://linux-hardware.org/?probe=b6fb308e13) | Feb 19, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [d166d054d9](https://linux-hardware.org/?probe=d166d054d9) | Feb 18, 2024 |
| HP            | ProLiant DL380p Gen8        | Server      | [9e2f7a350a](https://linux-hardware.org/?probe=9e2f7a350a) | Feb 17, 2024 |
| Toshiba       | Satellite C670D-121         | Notebook    | [e72d5daf72](https://linux-hardware.org/?probe=e72d5daf72) | Feb 17, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0fe8b08e8c](https://linux-hardware.org/?probe=0fe8b08e8c) | Feb 16, 2024 |
| ASUSTek       | P12R-M Series 60SB0AU0-S... | Server      | [f61de673d0](https://linux-hardware.org/?probe=f61de673d0) | Feb 16, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c795e9fcb9](https://linux-hardware.org/?probe=c795e9fcb9) | Feb 16, 2024 |
| Toshiba       | Satellite C670D-121         | Notebook    | [31876b1946](https://linux-hardware.org/?probe=31876b1946) | Feb 15, 2024 |
| Dell          | 05842Y A00                  | Desktop     | [50fc41ef5c](https://linux-hardware.org/?probe=50fc41ef5c) | Feb 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [64bdaa6db8](https://linux-hardware.org/?probe=64bdaa6db8) | Feb 15, 2024 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [56739f7004](https://linux-hardware.org/?probe=56739f7004) | Feb 15, 2024 |
| HP            | ProLiant DL380p Gen8        | Server      | [b1d8a070e5](https://linux-hardware.org/?probe=b1d8a070e5) | Feb 15, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [b3ffbe3673](https://linux-hardware.org/?probe=b3ffbe3673) | Feb 14, 2024 |
| Rockchip      | RK3318 BOX                  | Soc         | [9b806c989c](https://linux-hardware.org/?probe=9b806c989c) | Feb 13, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [b734675c3c](https://linux-hardware.org/?probe=b734675c3c) | Feb 13, 2024 |
| ASUSTek       | X751LB                      | Notebook    | [e2b955fef7](https://linux-hardware.org/?probe=e2b955fef7) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [0c27b7881f](https://linux-hardware.org/?probe=0c27b7881f) | Feb 12, 2024 |
| YANYU         | EPIC-C19                    | Desktop     | [9a93a8fd98](https://linux-hardware.org/?probe=9a93a8fd98) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2ef5e51010](https://linux-hardware.org/?probe=2ef5e51010) | Feb 12, 2024 |
| Dell          | Latitude E6440              | Notebook    | [af1136c398](https://linux-hardware.org/?probe=af1136c398) | Feb 11, 2024 |
| Dell          | Latitude E6440              | Notebook    | [3d82406435](https://linux-hardware.org/?probe=3d82406435) | Feb 11, 2024 |
| Positivo B... | VJFE59F11X-B0821H           | Notebook    | [749f5aacff](https://linux-hardware.org/?probe=749f5aacff) | Feb 10, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [51db691206](https://linux-hardware.org/?probe=51db691206) | Feb 09, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [225644e904](https://linux-hardware.org/?probe=225644e904) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [1c2ec48565](https://linux-hardware.org/?probe=1c2ec48565) | Feb 08, 2024 |
| Intel         | NUC7JYB J67969-401          | Mini pc     | [54c69c7b5e](https://linux-hardware.org/?probe=54c69c7b5e) | Feb 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9ce8b249bf](https://linux-hardware.org/?probe=9ce8b249bf) | Feb 07, 2024 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [10a9284561](https://linux-hardware.org/?probe=10a9284561) | Feb 07, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [08432d000e](https://linux-hardware.org/?probe=08432d000e) | Feb 07, 2024 |
| ASRock        | G31M-GS                     | Desktop     | [50925f48af](https://linux-hardware.org/?probe=50925f48af) | Feb 06, 2024 |
| HP            | Compaq 15                   | Notebook    | [beb2ca6a98](https://linux-hardware.org/?probe=beb2ca6a98) | Feb 06, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d8d66e42bc](https://linux-hardware.org/?probe=d8d66e42bc) | Feb 05, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [8c4de7da42](https://linux-hardware.org/?probe=8c4de7da42) | Feb 05, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [db79d01310](https://linux-hardware.org/?probe=db79d01310) | Feb 05, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [65e4664bc8](https://linux-hardware.org/?probe=65e4664bc8) | Feb 03, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c918dcf201](https://linux-hardware.org/?probe=c918dcf201) | Feb 03, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [f7d0fcd205](https://linux-hardware.org/?probe=f7d0fcd205) | Feb 02, 2024 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [88794835fb](https://linux-hardware.org/?probe=88794835fb) | Feb 02, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a3932a77fb](https://linux-hardware.org/?probe=a3932a77fb) | Feb 01, 2024 |
| HP            | 15                          | Notebook    | [5abc868cce](https://linux-hardware.org/?probe=5abc868cce) | Jan 31, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [a2536bd0a5](https://linux-hardware.org/?probe=a2536bd0a5) | Jan 31, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1127b13645](https://linux-hardware.org/?probe=1127b13645) | Jan 30, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [385d8d4782](https://linux-hardware.org/?probe=385d8d4782) | Jan 29, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [66d4abe24d](https://linux-hardware.org/?probe=66d4abe24d) | Jan 29, 2024 |
| HP            | 3397                        | Desktop     | [fcbc5b3ac6](https://linux-hardware.org/?probe=fcbc5b3ac6) | Jan 29, 2024 |
| ASUSTek       | N550JK                      | Notebook    | [097f96652f](https://linux-hardware.org/?probe=097f96652f) | Jan 29, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [dbbc24a0ed](https://linux-hardware.org/?probe=dbbc24a0ed) | Jan 28, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [5c34879ea0](https://linux-hardware.org/?probe=5c34879ea0) | Jan 28, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [4a48eb8f58](https://linux-hardware.org/?probe=4a48eb8f58) | Jan 28, 2024 |
| HP            | Compaq nc6320 (EN371UA#A... | Notebook    | [24bcfc0005](https://linux-hardware.org/?probe=24bcfc0005) | Jan 28, 2024 |
| Supermicro    | X13DEI                      | Server      | [044e82e684](https://linux-hardware.org/?probe=044e82e684) | Jan 27, 2024 |
| Dell          | 01W23F A05                  | Server      | [93f017d8b0](https://linux-hardware.org/?probe=93f017d8b0) | Jan 27, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [380fafe6a3](https://linux-hardware.org/?probe=380fafe6a3) | Jan 27, 2024 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [b0019abd70](https://linux-hardware.org/?probe=b0019abd70) | Jan 26, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [aa46ef22c8](https://linux-hardware.org/?probe=aa46ef22c8) | Jan 24, 2024 |
| MSI           | GL62M 7RDX                  | Notebook    | [bd42ee7dc8](https://linux-hardware.org/?probe=bd42ee7dc8) | Jan 24, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [f5a09bd7f0](https://linux-hardware.org/?probe=f5a09bd7f0) | Jan 23, 2024 |
| Intel         | S1200SP H57532-250          | Server      | [94a4904dc7](https://linux-hardware.org/?probe=94a4904dc7) | Jan 22, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [25d4886028](https://linux-hardware.org/?probe=25d4886028) | Jan 22, 2024 |
| Rockchip      | RK3288 Asus Tinker          | Soc         | [b21fbd5b1c](https://linux-hardware.org/?probe=b21fbd5b1c) | Jan 22, 2024 |
| ASRock        | H61M-HVS                    | Desktop     | [3cfc574d2d](https://linux-hardware.org/?probe=3cfc574d2d) | Jan 22, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58f6bacae6](https://linux-hardware.org/?probe=58f6bacae6) | Jan 21, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Lenovo        | ThinkPad T490 20N2000RRT    | Notebook    | [b48f14a503](https://linux-hardware.org/?probe=b48f14a503) | Jan 20, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [37613f1ec6](https://linux-hardware.org/?probe=37613f1ec6) | Jan 20, 2024 |
| IBM           | 94Y7718 SIT                 | Server      | [4c4fece75e](https://linux-hardware.org/?probe=4c4fece75e) | Jan 19, 2024 |
| IBM           | 69Y1006 SIT                 | Server      | [b9e00770bb](https://linux-hardware.org/?probe=b9e00770bb) | Jan 19, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [b09c608815](https://linux-hardware.org/?probe=b09c608815) | Jan 19, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [5b5d90211c](https://linux-hardware.org/?probe=5b5d90211c) | Jan 18, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [930cd5c4f3](https://linux-hardware.org/?probe=930cd5c4f3) | Jan 17, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3bb258a169](https://linux-hardware.org/?probe=3bb258a169) | Jan 15, 2024 |
| Multilaser    | MLGW08                      | Notebook    | [abfe537d6f](https://linux-hardware.org/?probe=abfe537d6f) | Jan 15, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [1d65e65b24](https://linux-hardware.org/?probe=1d65e65b24) | Jan 14, 2024 |
| Unknown       | Unknown                     | Soc         | [8eb428515e](https://linux-hardware.org/?probe=8eb428515e) | Jan 14, 2024 |
| ASRock        | C2750D4I                    | Desktop     | [c1426b3157](https://linux-hardware.org/?probe=c1426b3157) | Jan 14, 2024 |
| HP            | Compaq 6720s                | Notebook    | [4b6c283ab3](https://linux-hardware.org/?probe=4b6c283ab3) | Jan 13, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [02122a5ac3](https://linux-hardware.org/?probe=02122a5ac3) | Jan 13, 2024 |
| ASUSTek       | Z87-C                       | Desktop     | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a485e19625](https://linux-hardware.org/?probe=a485e19625) | Jan 12, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [854720405d](https://linux-hardware.org/?probe=854720405d) | Jan 12, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7eabdfe5d0](https://linux-hardware.org/?probe=7eabdfe5d0) | Jan 12, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [d04339c0dc](https://linux-hardware.org/?probe=d04339c0dc) | Jan 12, 2024 |
| HP            | 348 G5                      | Notebook    | [a7c6a60aaf](https://linux-hardware.org/?probe=a7c6a60aaf) | Jan 12, 2024 |
| HP            | 530 Notebook PC(GH634AA#... | Notebook    | [a17c4145f4](https://linux-hardware.org/?probe=a17c4145f4) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [5479dc0213](https://linux-hardware.org/?probe=5479dc0213) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [48bddf33da](https://linux-hardware.org/?probe=48bddf33da) | Jan 11, 2024 |
| Unknown       | Unknown                     | Notebook    | [0f2d55f419](https://linux-hardware.org/?probe=0f2d55f419) | Jan 11, 2024 |
| Unknown       | Unknown                     | Notebook    | [f5d4b22b3c](https://linux-hardware.org/?probe=f5d4b22b3c) | Jan 11, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e4bcfdfed2](https://linux-hardware.org/?probe=e4bcfdfed2) | Jan 10, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [8f4190a60f](https://linux-hardware.org/?probe=8f4190a60f) | Jan 10, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [5223d11808](https://linux-hardware.org/?probe=5223d11808) | Jan 10, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [90b63b0d8a](https://linux-hardware.org/?probe=90b63b0d8a) | Jan 10, 2024 |
| HP            | EliteBook 2530p             | Notebook    | [0de99e6532](https://linux-hardware.org/?probe=0de99e6532) | Jan 09, 2024 |
| HP            | ProBook 6545b               | Notebook    | [278d4aea3c](https://linux-hardware.org/?probe=278d4aea3c) | Jan 09, 2024 |
| TI            | AM335x PocketBeagle         | Soc         | [dc70357482](https://linux-hardware.org/?probe=dc70357482) | Jan 09, 2024 |
| Acer          | TMP455-M                    | Notebook    | [559512a222](https://linux-hardware.org/?probe=559512a222) | Jan 09, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [6f8302ddde](https://linux-hardware.org/?probe=6f8302ddde) | Jan 08, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ded26713a9](https://linux-hardware.org/?probe=ded26713a9) | Jan 08, 2024 |
| Dell          | Precision 5570              | Notebook    | [acc6213478](https://linux-hardware.org/?probe=acc6213478) | Jan 08, 2024 |
| HP            | 350 G2                      | Notebook    | [75e4063ce8](https://linux-hardware.org/?probe=75e4063ce8) | Jan 07, 2024 |
| Toshiba       | PORTEGE R500                | Notebook    | [315837012b](https://linux-hardware.org/?probe=315837012b) | Jan 07, 2024 |
| MSI           | X79A-GD65                   | Desktop     | [55c0071638](https://linux-hardware.org/?probe=55c0071638) | Jan 06, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [a44b8f65f6](https://linux-hardware.org/?probe=a44b8f65f6) | Jan 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [408830a147](https://linux-hardware.org/?probe=408830a147) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| Phoenix Co... | PSB514 A12                  | Desktop     | [424bbc0491](https://linux-hardware.org/?probe=424bbc0491) | Jan 03, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [63582c85bf](https://linux-hardware.org/?probe=63582c85bf) | Jan 03, 2024 |
| Unknown       | Unknown                     | Other       | [ceb8edb5ac](https://linux-hardware.org/?probe=ceb8edb5ac) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2f74327d87](https://linux-hardware.org/?probe=2f74327d87) | Jan 01, 2024 |
| HP            | 1495                        | Desktop     | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [f1144c99b2](https://linux-hardware.org/?probe=f1144c99b2) | Dec 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| Gigabyte      | P55-UD4P                    | Desktop     | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfc1d4289e](https://linux-hardware.org/?probe=dfc1d4289e) | Dec 22, 2023 |
| Gigabyte      | MZ72-HB0-00 01020102        | Server      | [771f7edd98](https://linux-hardware.org/?probe=771f7edd98) | Dec 22, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [22b9c27eb8](https://linux-hardware.org/?probe=22b9c27eb8) | Dec 21, 2023 |
| HP            | 3396                        | Desktop     | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | Desktop     | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9133031c56](https://linux-hardware.org/?probe=9133031c56) | Dec 18, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [e4c855bedc](https://linux-hardware.org/?probe=e4c855bedc) | Dec 16, 2023 |
| Dell          | 0M5WNK A02                  | Desktop     | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| Acer          | Aspire 1510 Rev.A           | Desktop     | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Unknown       | AMedia X96 Max+             | Soc         | [4df1c17523](https://linux-hardware.org/?probe=4df1c17523) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1ef755944c](https://linux-hardware.org/?probe=1ef755944c) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [e4fcf233c5](https://linux-hardware.org/?probe=e4fcf233c5) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ae61f1039f](https://linux-hardware.org/?probe=ae61f1039f) | Dec 09, 2023 |
| AZW           | MINI S                      | Desktop     | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [39d65538cb](https://linux-hardware.org/?probe=39d65538cb) | Dec 08, 2023 |
| Dell          | 0KP561                      | Desktop     | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Intel         | H61                         | Desktop     | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [523404e018](https://linux-hardware.org/?probe=523404e018) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6d4537080b](https://linux-hardware.org/?probe=6d4537080b) | Dec 05, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | Notebook    | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | Notebook    | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [c4f3b7fec9](https://linux-hardware.org/?probe=c4f3b7fec9) | Dec 01, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0c7a29604](https://linux-hardware.org/?probe=b0c7a29604) | Dec 01, 2023 |
| MSI           | A78M-E45                    | Desktop     | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | Desktop     | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b0642c446](https://linux-hardware.org/?probe=2b0642c446) | Nov 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | Desktop     | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| MSI           | X299 GAMING PRO CARBON      | Desktop     | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | Notebook    | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [a7890b3e79](https://linux-hardware.org/?probe=a7890b3e79) | Nov 27, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [b784691187](https://linux-hardware.org/?probe=b784691187) | Nov 27, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [1e36c88b83](https://linux-hardware.org/?probe=1e36c88b83) | Nov 27, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| MSI           | B85M-G43                    | Desktop     | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [5bf94efca1](https://linux-hardware.org/?probe=5bf94efca1) | Nov 26, 2023 |
| AZW           | U59                         | Desktop     | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6706fb6f0f](https://linux-hardware.org/?probe=6706fb6f0f) | Nov 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [729045e89d](https://linux-hardware.org/?probe=729045e89d) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [80a223d120](https://linux-hardware.org/?probe=80a223d120) | Nov 21, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [09b6107952](https://linux-hardware.org/?probe=09b6107952) | Nov 20, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | 1905                        | Desktop     | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [67cba6139f](https://linux-hardware.org/?probe=67cba6139f) | Nov 20, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9d71a8e453](https://linux-hardware.org/?probe=9d71a8e453) | Nov 20, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | Desktop     | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Phoenix/Si... | M730SR                      | Notebook    | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [01ce54e1ed](https://linux-hardware.org/?probe=01ce54e1ed) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | Notebook    | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| WanYou        | WanYouChunXiao              | Desktop     | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8b8d073259](https://linux-hardware.org/?probe=8b8d073259) | Nov 13, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [26e08a35c7](https://linux-hardware.org/?probe=26e08a35c7) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Acer          | EG43M                       | Desktop     | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [25387a2c6f](https://linux-hardware.org/?probe=25387a2c6f) | Nov 08, 2023 |
| Lenovo        | ThinkPad X121e 30515YG      | Notebook    | [4008ec0eb0](https://linux-hardware.org/?probe=4008ec0eb0) | Nov 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470 20HES3JR02    | Notebook    | [4cdded6623](https://linux-hardware.org/?probe=4cdded6623) | Nov 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Acer          | AO532h                      | Notebook    | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| ASRock        | Z77 WS                      | Desktop     | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | Desktop     | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Unknown       | Unknown                     | Soc         | [c1888a18d4](https://linux-hardware.org/?probe=c1888a18d4) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| Supermicro    | X8DTH                       | Server      | [25d685c01e](https://linux-hardware.org/?probe=25d685c01e) | Oct 30, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [081a87b55c](https://linux-hardware.org/?probe=081a87b55c) | Oct 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [137821ca25](https://linux-hardware.org/?probe=137821ca25) | Oct 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | Notebook    | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [fa28d68e1b](https://linux-hardware.org/?probe=fa28d68e1b) | Oct 26, 2023 |
| Matsushita... | CF-30CTWAZBM                | Notebook    | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| MSI           | GT62VR 6RD                  | Notebook    | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [047f359430](https://linux-hardware.org/?probe=047f359430) | Oct 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de56b09e8](https://linux-hardware.org/?probe=2de56b09e8) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| Unknown       | Unknown                     | Soc         | [0a48bce51e](https://linux-hardware.org/?probe=0a48bce51e) | Oct 21, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [deaf93db4b](https://linux-hardware.org/?probe=deaf93db4b) | Oct 21, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [46dd11286b](https://linux-hardware.org/?probe=46dd11286b) | Oct 21, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [c1f0e34df5](https://linux-hardware.org/?probe=c1f0e34df5) | Oct 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| Rockchip      | RK3288 Asus Tinker Board... | Soc         | [b51d195a9b](https://linux-hardware.org/?probe=b51d195a9b) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e8dd286f6d](https://linux-hardware.org/?probe=e8dd286f6d) | Oct 16, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [6a64c8bbf2](https://linux-hardware.org/?probe=6a64c8bbf2) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34f4a7b2a5](https://linux-hardware.org/?probe=34f4a7b2a5) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d2501217c](https://linux-hardware.org/?probe=7d2501217c) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | Desktop     | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | Notebook    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [37a3b14ed3](https://linux-hardware.org/?probe=37a3b14ed3) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Dell          | Latitude E6520              | Notebook    | [30a511af92](https://linux-hardware.org/?probe=30a511af92) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [679e27a869](https://linux-hardware.org/?probe=679e27a869) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [941644a3ed](https://linux-hardware.org/?probe=941644a3ed) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [427ca84f59](https://linux-hardware.org/?probe=427ca84f59) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| IBM           | 94Y7614                     | Server      | [e9f6bf0852](https://linux-hardware.org/?probe=e9f6bf0852) | Oct 10, 2023 |
| Supermicro    | X10SLM-F                    | Server      | [a47217adb4](https://linux-hardware.org/?probe=a47217adb4) | Oct 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [601fd070ec](https://linux-hardware.org/?probe=601fd070ec) | Oct 10, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [74a043fcf5](https://linux-hardware.org/?probe=74a043fcf5) | Oct 09, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [e763607fe3](https://linux-hardware.org/?probe=e763607fe3) | Oct 09, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [881454bd02](https://linux-hardware.org/?probe=881454bd02) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | Notebook    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | Notebook    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [71bc4e1d3f](https://linux-hardware.org/?probe=71bc4e1d3f) | Oct 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [fea9ed801a](https://linux-hardware.org/?probe=fea9ed801a) | Oct 07, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [63ad812f2f](https://linux-hardware.org/?probe=63ad812f2f) | Oct 06, 2023 |
| Exo           | Smart Serie L               | Notebook    | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bf88efbfff](https://linux-hardware.org/?probe=bf88efbfff) | Oct 05, 2023 |
| Philco Inf... | EC10IS2                     | Notebook    | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ff4fd8349](https://linux-hardware.org/?probe=7ff4fd8349) | Oct 02, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [3779ac7003](https://linux-hardware.org/?probe=3779ac7003) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | Notebook    | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aae60ff071](https://linux-hardware.org/?probe=aae60ff071) | Oct 01, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4aa68077](https://linux-hardware.org/?probe=ba4aa68077) | Sep 30, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [c7b049f922](https://linux-hardware.org/?probe=c7b049f922) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | Desktop     | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [acde6e2ba0](https://linux-hardware.org/?probe=acde6e2ba0) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8a7db88ae5](https://linux-hardware.org/?probe=8a7db88ae5) | Sep 25, 2023 |
| MSI           | MS-7318                     | Desktop     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 250 G4                      | Notebook    | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| HP            | 1905                        | Desktop     | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | Desktop     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [6f6fbfc86f](https://linux-hardware.org/?probe=6f6fbfc86f) | Sep 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Dell          | Precision 7550              | Notebook    | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | Desktop     | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| HP            | 8158 A01                    | Mini pc     | [bd8aa3d09c](https://linux-hardware.org/?probe=bd8aa3d09c) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | Notebook    | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| Google        | Droid                       | Notebook    | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f8e68bfc81](https://linux-hardware.org/?probe=f8e68bfc81) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f89ec253d3](https://linux-hardware.org/?probe=f89ec253d3) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae1f2b94e5](https://linux-hardware.org/?probe=ae1f2b94e5) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | Desktop     | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | Notebook    | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | Desktop     | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| Acer          | Extensa 5220                | Notebook    | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e8fe3531c7](https://linux-hardware.org/?probe=e8fe3531c7) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6bea6e300b](https://linux-hardware.org/?probe=6bea6e300b) | Sep 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da21e863a4](https://linux-hardware.org/?probe=da21e863a4) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | Desktop     | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0841c5e196](https://linux-hardware.org/?probe=0841c5e196) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8d52d37e1e](https://linux-hardware.org/?probe=8d52d37e1e) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c3fe8cb8e9](https://linux-hardware.org/?probe=c3fe8cb8e9) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e0133bb14e](https://linux-hardware.org/?probe=e0133bb14e) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a200aa5407](https://linux-hardware.org/?probe=a200aa5407) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | 1495                        | Desktop     | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [52306fce15](https://linux-hardware.org/?probe=52306fce15) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | Desktop     | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| HP            | 158A                        | Desktop     | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Rockchip      | RK3568 EVB1 DDR4 V10        | Soc         | [846c733ed7](https://linux-hardware.org/?probe=846c733ed7) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Lenovo        | IdeaPad Z485 20151          | Notebook    | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [5f5f76ff98](https://linux-hardware.org/?probe=5f5f76ff98) | Aug 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 967       | 11.91%  |
| 5.10.0-7-amd64         | 693       | 8.54%   |
| 5.10.0-10-amd64        | 578       | 7.12%   |
| 5.10.0-21-amd64        | 472       | 5.81%   |
| 5.10.0-20-amd64        | 383       | 4.72%   |
| 5.10.0-16-amd64        | 373       | 4.59%   |
| 5.10.0-9-amd64         | 329       | 4.05%   |
| 5.10.0-18-amd64        | 296       | 3.65%   |
| 5.10.0-19-amd64        | 295       | 3.63%   |
| 5.10.0-13-amd64        | 266       | 3.28%   |
| 5.10.0-23-amd64        | 225       | 2.77%   |
| 5.10.0-11-amd64        | 194       | 2.39%   |
| 5.10.0-2-amd64         | 158       | 1.95%   |
| 5.10.0-14-amd64        | 141       | 1.74%   |
| 5.10.0-17-amd64        | 126       | 1.55%   |
| 5.10.0-15-amd64        | 119       | 1.47%   |
| 5.10.0-22-amd64        | 107       | 1.32%   |
| 5.10.0-26-amd64        | 77        | 0.95%   |
| 5.10.0-12-amd64        | 73        | 0.9%    |
| 5.10.0-28-amd64        | 54        | 0.67%   |
| 6.1.21-v8+             | 49        | 0.6%    |
| 6.0.0-0.deb11.6-amd64  | 47        | 0.58%   |
| 5.10.0-6-amd64         | 47        | 0.58%   |
| 5.10.0-25-amd64        | 47        | 0.58%   |
| 5.18.0-0.deb11.4-amd64 | 45        | 0.55%   |
| 5.10.0-33-amd64        | 41        | 0.51%   |
| 5.16.0-0.bpo.4-amd64   | 38        | 0.47%   |
| 5.15.0-2-amd64         | 36        | 0.44%   |
| 5.10.0-27-amd64        | 36        | 0.44%   |
| 5.10.0-32-amd64        | 30        | 0.37%   |
| 5.10.0-13-686-pae      | 30        | 0.37%   |
| 6.0.0-0.deb11.2-amd64  | 29        | 0.36%   |
| 5.19.0-0.deb11.2-amd64 | 27        | 0.33%   |
| 5.18.0-0.bpo.1-amd64   | 26        | 0.32%   |
| 5.14.0-0.bpo.2-amd64   | 26        | 0.32%   |
| 5.15.74-1-pve          | 25        | 0.31%   |
| 6.1.0-0.deb11.7-amd64  | 24        | 0.3%    |
| 5.13.19-6-pve          | 24        | 0.3%    |
| 5.10.0-34-amd64        | 23        | 0.28%   |
| 5.15.85-1-pve          | 22        | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5931      | 79.29%  |
| 6.1.0    | 113       | 1.51%   |
| 6.0.0    | 107       | 1.43%   |
| 5.18.0   | 99        | 1.32%   |
| 5.15.0   | 79        | 1.06%   |
| 5.16.0   | 72        | 0.96%   |
| 5.19.0   | 62        | 0.83%   |
| 5.13.19  | 60        | 0.8%    |
| 6.1.21   | 49        | 0.66%   |
| 5.14.0   | 44        | 0.59%   |
| 5.15.107 | 37        | 0.49%   |
| 5.15.74  | 29        | 0.39%   |
| 5.17.0   | 26        | 0.35%   |
| 5.11.22  | 26        | 0.35%   |
| 5.15.85  | 22        | 0.29%   |
| 5.15.102 | 21        | 0.28%   |
| 5.15.84  | 20        | 0.27%   |
| 5.15.30  | 20        | 0.27%   |
| 5.15.83  | 19        | 0.25%   |
| 5.15.39  | 19        | 0.25%   |
| 5.15.32  | 18        | 0.24%   |
| 5.15.35  | 17        | 0.23%   |
| 5.15.76  | 16        | 0.21%   |
| 5.15.53  | 15        | 0.2%    |
| 5.10.92  | 15        | 0.2%    |
| 5.15.61  | 13        | 0.17%   |
| 5.15.108 | 13        | 0.17%   |
| 5.15.126 | 11        | 0.15%   |
| 5.15.104 | 11        | 0.15%   |
| 6.2.16   | 10        | 0.13%   |
| 5.15.158 | 10        | 0.13%   |
| 4.19.0   | 10        | 0.13%   |
| 5.10.110 | 9         | 0.12%   |
| 6.1.15   | 8         | 0.11%   |
| 5.19.17  | 8         | 0.11%   |
| 5.15.60  | 8         | 0.11%   |
| 6.2.6    | 7         | 0.09%   |
| 5.15.116 | 7         | 0.09%   |
| 5.13.0   | 7         | 0.09%   |
| 5.10.63  | 7         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10     | 6037      | 81.21%  |
| 5.15     | 452       | 6.08%   |
| 6.1      | 204       | 2.74%   |
| 6.0      | 124       | 1.67%   |
| 5.18     | 108       | 1.45%   |
| 5.16     | 87        | 1.17%   |
| 5.19     | 83        | 1.12%   |
| 5.13     | 80        | 1.08%   |
| 5.14     | 51        | 0.69%   |
| 6.2      | 38        | 0.51%   |
| 5.17     | 36        | 0.48%   |
| 5.11     | 35        | 0.47%   |
| 4.19     | 14        | 0.19%   |
| 5.4      | 12        | 0.16%   |
| 5.12     | 9         | 0.12%   |
| 6.3      | 7         | 0.09%   |
| 4.4      | 6         | 0.08%   |
| 6.6      | 5         | 0.07%   |
| 6.5      | 5         | 0.07%   |
| 6.4      | 5         | 0.07%   |
| 5        | 5         | 0.07%   |
| 4.9      | 5         | 0.07%   |
| 6.12     | 4         | 0.05%   |
| 6.7      | 3         | 0.04%   |
| 5.9      | 3         | 0.04%   |
| 5.1      | 3         | 0.04%   |
| 3.18     | 2         | 0.03%   |
| 6.9      | 1         | 0.01%   |
| 6.8      | 1         | 0.01%   |
| 6.10     | 1         | 0.01%   |
| 6        | 1         | 0.01%   |
| 5.8      | 1         | 0.01%   |
| 5.5      | 1         | 0.01%   |
| 5.15.6   | 1         | 0.01%   |
| 5.10.164 | 1         | 0.01%   |
| 4.14     | 1         | 0.01%   |
| 3.8      | 1         | 0.01%   |
| 3.10     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6723      | 92.48%  |
| aarch64 | 268       | 3.69%   |
| i686    | 230       | 3.16%   |
| armv7l  | 40        | 0.55%   |
| riscv64 | 8         | 0.11%   |
| i586    | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2672      | 36.19%  |
| GNOME             | 1635      | 22.15%  |
| XFCE              | 870       | 11.78%  |
| KDE5              | 797       | 10.8%   |
| MATE              | 295       | 4%      |
| LXDE              | 256       | 3.47%   |
| X-Cinnamon        | 227       | 3.07%   |
| Cinnamon          | 180       | 2.44%   |
| LXQt              | 101       | 1.37%   |
| i3                | 76        | 1.03%   |
| KDE               | 56        | 0.76%   |
| Openbox           | 48        | 0.65%   |
| GNOME Flashback   | 42        | 0.57%   |
| lightdm-xsession  | 28        | 0.38%   |
| trinity           | 22        | 0.3%    |
| GNOME Classic     | 16        | 0.22%   |
| Budgie            | 15        | 0.2%    |
| sway              | 5         | 0.07%   |
| awesome           | 5         | 0.07%   |
| DWM               | 4         | 0.05%   |
| x-session-manager | 3         | 0.04%   |
| ICEWM             | 3         | 0.04%   |
| Enlightenment     | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| BunsenLabs        | 3         | 0.04%   |
| GNUstep           | 2         | 0.03%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Unity             | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| TOS:GNOME         | 1         | 0.01%   |
| Phosh:GNOME       | 1         | 0.01%   |
| mwm               | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |
| fvwm              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| e16-session       | 1         | 0.01%   |
| default           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 3457      | 46.87%  |
| Unknown     | 1905      | 25.83%  |
| Wayland     | 1037      | 14.06%  |
| Tty         | 966       | 13.1%   |
| Unspecified | 7         | 0.09%   |
| Web         | 4         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3429      | 46.64%  |
| LightDM | 1553      | 21.12%  |
| GDM     | 1307      | 17.78%  |
| SDDM    | 704       | 9.58%   |
| TDM     | 156       | 2.12%   |
| GDM3    | 143       | 1.95%   |
| XDM     | 19        | 0.26%   |
| SLiM    | 15        | 0.2%    |
| LXDM    | 12        | 0.16%   |
| NODM    | 8         | 0.11%   |
| SU      | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2521      | 34.32%  |
| ru_RU   | 968       | 13.18%  |
| Unknown | 954       | 12.99%  |
| de_DE   | 442       | 6.02%   |
| en_GB   | 377       | 5.13%   |
| fr_FR   | 372       | 5.06%   |
| es_ES   | 208       | 2.83%   |
| pt_BR   | 169       | 2.3%    |
| it_IT   | 169       | 2.3%    |
| pl_PL   | 116       | 1.58%   |
| C       | 101       | 1.38%   |
| en_CA   | 85        | 1.16%   |
| en_AU   | 85        | 1.16%   |
| es_MX   | 55        | 0.75%   |
| es_AR   | 50        | 0.68%   |
| zh_CN   | 48        | 0.65%   |
| es_VE   | 34        | 0.46%   |
| hu_HU   | 33        | 0.45%   |
| en_IN   | 33        | 0.45%   |
| en_IE   | 31        | 0.42%   |
| ja_JP   | 26        | 0.35%   |
| de_CH   | 24        | 0.33%   |
| de_AT   | 24        | 0.33%   |
| nl_NL   | 21        | 0.29%   |
| en_NZ   | 18        | 0.25%   |
| sv_SE   | 17        | 0.23%   |
| fi_FI   | 17        | 0.23%   |
| pt_PT   | 16        | 0.22%   |
| es_CO   | 14        | 0.19%   |
| es_CL   | 14        | 0.19%   |
| fr_BE   | 13        | 0.18%   |
| en_ZA   | 13        | 0.18%   |
| cs_CZ   | 13        | 0.18%   |
| ca_ES   | 13        | 0.18%   |
| tr_TR   | 12        | 0.16%   |
| nl_BE   | 12        | 0.16%   |
| fr_CH   | 12        | 0.16%   |
| ru_UA   | 10        | 0.14%   |
| zh_TW   | 9         | 0.12%   |
| nb_NO   | 9         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4212      | 57.35%  |
| BIOS | 3133      | 42.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4898      | 67.04%  |
| Overlay | 1909      | 26.13%  |
| Btrfs   | 217       | 2.97%   |
| Zfs     | 124       | 1.7%    |
| Xfs     | 75        | 1.03%   |
| Tmpfs   | 38        | 0.52%   |
| Ext3    | 19        | 0.26%   |
| Ext2    | 11        | 0.15%   |
| Unknown | 9         | 0.12%   |
| Rootfs  | 3         | 0.04%   |
| Aufs    | 2         | 0.03%   |
| F2fs    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4401      | 59.91%  |
| MBR     | 2002      | 27.25%  |
| Unknown | 943       | 12.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5949      | 81.04%  |
| Yes       | 1392      | 18.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5166      | 70.47%  |
| Yes       | 2165      | 29.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1023      | 14.08%  |
| Lenovo                  | 988       | 13.59%  |
| Hewlett-Packard         | 805       | 11.08%  |
| Dell                    | 715       | 9.84%   |
| Apple                   | 696       | 9.58%   |
| Gigabyte Technology     | 447       | 6.15%   |
| MSI                     | 333       | 4.58%   |
| Acer                    | 264       | 3.63%   |
| ASRock                  | 260       | 3.58%   |
| Raspberry Pi Foundation | 182       | 2.5%    |
| Intel                   | 180       | 2.48%   |
| Google                  | 141       | 1.94%   |
| Unknown                 | 127       | 1.75%   |
| Supermicro              | 72        | 0.99%   |
| Fujitsu                 | 62        | 0.85%   |
| Toshiba                 | 60        | 0.83%   |
| ECS                     | 49        | 0.67%   |
| Aquarius                | 47        | 0.65%   |
| Samsung Electronics     | 44        | 0.61%   |
| AZW                     | 38        | 0.52%   |
| ASRockRack              | 35        | 0.48%   |
| HUAWEI                  | 28        | 0.39%   |
| Foxconn                 | 28        | 0.39%   |
| Sony                    | 21        | 0.29%   |
| Packard Bell            | 20        | 0.28%   |
| Pegatron                | 19        | 0.26%   |
| Notebook                | 19        | 0.26%   |
| AMI                     | 17        | 0.23%   |
| Medion                  | 16        | 0.22%   |
| Rockchip                | 14        | 0.19%   |
| Microsoft               | 14        | 0.19%   |
| Inventec                | 14        | 0.19%   |
| BESSTAR Tech            | 14        | 0.19%   |
| IBM                     | 13        | 0.18%   |
| Hardkernel              | 13        | 0.18%   |
| Biostar                 | 13        | 0.18%   |
| Positivo                | 12        | 0.17%   |
| sunxi                   | 11        | 0.15%   |
| Clevo                   | 11        | 0.15%   |
| Panasonic               | 10        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 353       | 4.86%   |
| Unknown                                   | 142       | 1.95%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.57%   |
| ASUS All Series                           | 87        | 1.2%    |
| Apple MacBookAir7,2                       | 77        | 1.06%   |
| Apple MacBookAir7,1                       | 77        | 1.06%   |
| Google Enguarde                           | 74        | 1.02%   |
| ASUS S20 K29                              | 55        | 0.76%   |
| Apple MacBook2,1                          | 55        | 0.76%   |
| Aquarius NS585                            | 44        | 0.61%   |
| MSI MS-7996                               | 39        | 0.54%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 35        | 0.48%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 25        | 0.34%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.33%   |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 23        | 0.32%   |
| Google Terra                              | 23        | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 22        | 0.3%    |
| MSI MS-7817                               | 22        | 0.3%    |
| ECS G31T-M9                               | 22        | 0.3%    |
| Apple MacBook4,1                          | 21        | 0.29%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 20        | 0.28%   |
| ASRock H470M-HVS                          | 20        | 0.28%   |
| Supermicro Super Server                   | 19        | 0.26%   |
| HP Notebook                               | 19        | 0.26%   |
| Gigabyte H81M-S2V                         | 18        | 0.25%   |
| ASUS PRIME H510M-A                        | 17        | 0.23%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.22%   |
| Gigabyte H410M S2H                        | 16        | 0.22%   |
| ECS H61H2-M13                             | 16        | 0.22%   |
| Dell OptiPlex 7010                        | 16        | 0.22%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.21%   |
| Acer Aspire A315-23                       | 15        | 0.21%   |
| RPi Raspberry Pi                          | 14        | 0.19%   |
| HP Pavilion g6                            | 14        | 0.19%   |
| ASUS 1005HA                               | 14        | 0.19%   |
| Google Reks                               | 13        | 0.18%   |
| AZW MINI S                                | 13        | 0.18%   |
| AZW U59                                   | 12        | 0.17%   |
| ASUS PRIME A320M-K                        | 12        | 0.17%   |
| RPi Raspberry Pi 400 Rev 1.0              | 11        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 609       | 8.38%   |
| Apple MacBook5     | 353       | 4.86%   |
| Dell Latitude      | 199       | 2.74%   |
| RPi Raspberry      | 182       | 2.5%    |
| Acer Aspire        | 170       | 2.34%   |
| Apple MacBookAir7  | 154       | 2.12%   |
| ASUS PRIME         | 152       | 2.09%   |
| Dell Inspiron      | 151       | 2.08%   |
| Unknown            | 142       | 1.95%   |
| Lenovo IdeaPad     | 121       | 1.66%   |
| HP EliteBook       | 116       | 1.6%    |
| Dell OptiPlex      | 107       | 1.47%   |
| HP Pavilion        | 96        | 1.32%   |
| HP Compaq          | 88        | 1.21%   |
| ASUS All           | 87        | 1.2%    |
| Dell Precision     | 84        | 1.16%   |
| HP Laptop          | 78        | 1.07%   |
| Google Enguarde    | 74        | 1.02%   |
| Lenovo ThinkCentre | 72        | 0.99%   |
| HP ProBook         | 64        | 0.88%   |
| ASUS ROG           | 63        | 0.87%   |
| Dell XPS           | 55        | 0.76%   |
| ASUS S20           | 55        | 0.76%   |
| Apple MacBook2     | 55        | 0.76%   |
| ASUS TUF           | 53        | 0.73%   |
| Dell PowerEdge     | 48        | 0.66%   |
| HP ProLiant        | 47        | 0.65%   |
| Toshiba Satellite  | 46        | 0.63%   |
| ASUS VivoBook      | 44        | 0.61%   |
| Aquarius NS585     | 44        | 0.61%   |
| Dell Vostro        | 40        | 0.55%   |
| MSI MS-7996        | 39        | 0.54%   |
| ASUS P8H61-M       | 33        | 0.45%   |
| HP EliteDesk       | 28        | 0.39%   |
| HP ENVY            | 27        | 0.37%   |
| ASUS ASUS          | 27        | 0.37%   |
| HP ZBook           | 25        | 0.34%   |
| Gigabyte B450M     | 25        | 0.34%   |
| HP 250             | 24        | 0.33%   |
| Fujitsu ESPRIMO    | 24        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 822       | 11.31%  |
| 2021    | 655       | 9.01%   |
| 2009    | 592       | 8.15%   |
| 2019    | 532       | 7.32%   |
| 2012    | 526       | 7.24%   |
| 2018    | 484       | 6.66%   |
| 2013    | 424       | 5.83%   |
| 2015    | 381       | 5.24%   |
| 2011    | 378       | 5.2%    |
| 2017    | 359       | 4.94%   |
| 2022    | 331       | 4.55%   |
| 2014    | 328       | 4.51%   |
| 2016    | 277       | 3.81%   |
| 2010    | 261       | 3.59%   |
| Unknown | 249       | 3.43%   |
| 2008    | 219       | 3.01%   |
| 2007    | 181       | 2.49%   |
| 2006    | 135       | 1.86%   |
| 2023    | 54        | 0.74%   |
| 2005    | 39        | 0.54%   |
| 2003    | 16        | 0.22%   |
| 2004    | 12        | 0.17%   |
| 2024    | 7         | 0.1%    |
| 2001    | 3         | 0.04%   |
| 2025    | 1         | 0.01%   |
| 2002    | 1         | 0.01%   |
| 2000    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3578      | 49.23%  |
| Desktop        | 2721      | 37.44%  |
| System on chip | 297       | 4.09%   |
| Convertible    | 207       | 2.85%   |
| Mini pc        | 186       | 2.56%   |
| Server         | 174       | 2.39%   |
| All in one     | 63        | 0.87%   |
| Tablet         | 35        | 0.48%   |
| Phone          | 4         | 0.06%   |
| Other          | 2         | 0.03%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6899      | 94.51%  |
| Enabled  | 401       | 5.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7114      | 97.87%  |
| Yes  | 155       | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1655      | 22.54%  |
| 16.01-24.0      | 1320      | 17.98%  |
| 3.01-4.0        | 1290      | 17.57%  |
| 8.01-16.0       | 919       | 12.52%  |
| 1.01-2.0        | 696       | 9.48%   |
| 32.01-64.0      | 627       | 8.54%   |
| 64.01-256.0     | 363       | 4.94%   |
| 0.51-1.0        | 149       | 2.03%   |
| 2.01-3.0        | 146       | 1.99%   |
| 24.01-32.0      | 110       | 1.5%    |
| 0.01-0.5        | 36        | 0.49%   |
| More than 256.0 | 31        | 0.42%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2550      | 33.13%  |
| 0.51-1.0        | 1329      | 17.27%  |
| 2.01-3.0        | 1273      | 16.54%  |
| 4.01-8.0        | 866       | 11.25%  |
| 3.01-4.0        | 699       | 9.08%   |
| 0.01-0.5        | 417       | 5.42%   |
| 8.01-16.0       | 321       | 4.17%   |
| 16.01-24.0      | 92        | 1.2%    |
| 32.01-64.0      | 73        | 0.95%   |
| 24.01-32.0      | 41        | 0.53%   |
| 64.01-256.0     | 32        | 0.42%   |
| More than 256.0 | 2         | 0.03%   |
| Unknown         | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4880      | 65.88%  |
| 2      | 1379      | 18.62%  |
| 3      | 448       | 6.05%   |
| 4      | 266       | 3.59%   |
| 5      | 127       | 1.71%   |
| 6      | 77        | 1.04%   |
| 0      | 62        | 0.84%   |
| 7      | 46        | 0.62%   |
| 8      | 43        | 0.58%   |
| 9      | 17        | 0.23%   |
| 10     | 14        | 0.19%   |
| 13     | 11        | 0.15%   |
| 12     | 8         | 0.11%   |
| 11     | 7         | 0.09%   |
| 14     | 5         | 0.07%   |
| 16     | 3         | 0.04%   |
| 28     | 2         | 0.03%   |
| 19     | 2         | 0.03%   |
| 18     | 2         | 0.03%   |
| 79     | 1         | 0.01%   |
| 47     | 1         | 0.01%   |
| 29     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 21     | 1         | 0.01%   |
| 15     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4982      | 68.31%  |
| Yes       | 2311      | 31.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6276      | 86.24%  |
| No        | 1001      | 13.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4798      | 65.86%  |
| No        | 2487      | 34.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3964      | 54.29%  |
| No        | 3338      | 45.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1817      | 24.94%  |
| Russia       | 1074      | 14.74%  |
| Germany      | 692       | 9.5%    |
| France       | 482       | 6.62%   |
| Spain        | 280       | 3.84%   |
| Italy        | 242       | 3.32%   |
| Brazil       | 228       | 3.13%   |
| UK           | 191       | 2.62%   |
| Poland       | 181       | 2.48%   |
| Canada       | 153       | 2.1%    |
| Australia    | 122       | 1.67%   |
| Netherlands  | 119       | 1.63%   |
| Switzerland  | 104       | 1.43%   |
| Mexico       | 87        | 1.19%   |
| China        | 85        | 1.17%   |
| Argentina    | 82        | 1.13%   |
| Sweden       | 60        | 0.82%   |
| Belgium      | 57        | 0.78%   |
| Austria      | 56        | 0.77%   |
| India        | 55        | 0.75%   |
| Hungary      | 54        | 0.74%   |
| Ukraine      | 53        | 0.73%   |
| Finland      | 48        | 0.66%   |
| Czechia      | 45        | 0.62%   |
| Portugal     | 44        | 0.6%    |
| Norway       | 42        | 0.58%   |
| Turkey       | 41        | 0.56%   |
| Venezuela    | 39        | 0.54%   |
| Japan        | 37        | 0.51%   |
| Bulgaria     | 37        | 0.51%   |
| Romania      | 32        | 0.44%   |
| Ireland      | 29        | 0.4%    |
| Greece       | 29        | 0.4%    |
| New Zealand  | 25        | 0.34%   |
| Taiwan       | 24        | 0.33%   |
| Malaysia     | 24        | 0.33%   |
| Denmark      | 24        | 0.33%   |
| Colombia     | 23        | 0.32%   |
| Croatia      | 22        | 0.3%    |
| South Africa | 21        | 0.29%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 758       | 9.96%   |
| Voronezh          | 715       | 9.4%    |
| Dover-Foxcroft    | 304       | 4%      |
| Moscow            | 89        | 1.17%   |
| St Petersburg     | 74        | 0.97%   |
| Paris             | 72        | 0.95%   |
| Seville           | 53        | 0.7%    |
| Berlin            | 51        | 0.67%   |
| Warsaw            | 44        | 0.58%   |
| Madrid            | 41        | 0.54%   |
| Vienna            | 38        | 0.5%    |
| Barcelona         | 37        | 0.49%   |
| Munich            | 35        | 0.46%   |
| Milan             | 34        | 0.45%   |
| Amsterdam         | 34        | 0.45%   |
| Zurich            | 30        | 0.39%   |
| Sao Paulo         | 30        | 0.39%   |
| Sydney            | 28        | 0.37%   |
| Toronto           | 26        | 0.34%   |
| Frankfurt am Main | 25        | 0.33%   |
| Falkenstein       | 25        | 0.33%   |
| Brisbane          | 24        | 0.32%   |
| Perm              | 23        | 0.3%    |
| Hamburg           | 23        | 0.3%    |
| Melbourne         | 22        | 0.29%   |
| London            | 21        | 0.28%   |
| Istanbul          | 20        | 0.26%   |
| Helsinki          | 20        | 0.26%   |
| Buenos Aires      | 20        | 0.26%   |
| Prague            | 19        | 0.25%   |
| Dublin            | 19        | 0.25%   |
| Stuttgart         | 18        | 0.24%   |
| Cologne           | 18        | 0.24%   |
| Athens            | 18        | 0.24%   |
| San José         | 17        | 0.22%   |
| Leipzig           | 17        | 0.22%   |
| Kuala Lumpur      | 17        | 0.22%   |
| Chicago           | 17        | 0.22%   |
| Budapest          | 17        | 0.22%   |
| Brasília         | 17        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1479      | 2195   | 14.58%  |
| WDC                 | 1323      | 2227   | 13.04%  |
| Seagate             | 1273      | 2376   | 12.55%  |
| Toshiba             | 700       | 1021   | 6.9%    |
| Unknown             | 610       | 793    | 6.01%   |
| Kingston            | 609       | 790    | 6%      |
| Crucial             | 452       | 557    | 4.46%   |
| SanDisk             | 393       | 494    | 3.87%   |
| Hitachi             | 295       | 398    | 2.91%   |
| Fujitsu             | 287       | 301    | 2.83%   |
| Intel               | 235       | 335    | 2.32%   |
| Apple               | 199       | 239    | 1.96%   |
| SK hynix            | 198       | 253    | 1.95%   |
| A-DATA Technology   | 178       | 293    | 1.75%   |
| HGST                | 169       | 306    | 1.67%   |
| Micron Technology   | 136       | 164    | 1.34%   |
| China               | 122       | 139    | 1.2%    |
| Unknown             | 102       | 110    | 1.01%   |
| KIOXIA              | 70        | 77     | 0.69%   |
| PNY                 | 66        | 123    | 0.65%   |
| SPCC                | 64        | 75     | 0.63%   |
| Transcend           | 54        | 61     | 0.53%   |
| Phison              | 46        | 57     | 0.45%   |
| Intenso             | 45        | 59     | 0.44%   |
| Hewlett-Packard     | 43        | 96     | 0.42%   |
| LITEON              | 39        | 47     | 0.38%   |
| JMicron Technology  | 38        | 42     | 0.37%   |
| Corsair             | 38        | 59     | 0.37%   |
| Patriot             | 37        | 44     | 0.36%   |
| Netac               | 37        | 97     | 0.36%   |
| SABRENT             | 30        | 31     | 0.3%    |
| GOODRAM             | 30        | 49     | 0.3%    |
| OCZ                 | 27        | 32     | 0.27%   |
| Team                | 26        | 51     | 0.26%   |
| Silicon Motion      | 26        | 32     | 0.26%   |
| Maxtor              | 24        | 32     | 0.24%   |
| Apacer              | 24        | 24     | 0.24%   |
| Gigabyte Technology | 23        | 26     | 0.23%   |
| ASMT                | 22        | 31     | 0.22%   |
| LITEONIT            | 21        | 29     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 2.11%   |
| Kingston SA400S37240G 240GB SSD    | 141       | 1.26%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.09%   |
| Unknown                            | 102       | 0.91%   |
| Seagate ST500DM002-1BD142 500GB    | 89        | 0.79%   |
| Crucial CT480BX500SSD1 480GB       | 81        | 0.72%   |
| Apple SSD AP0128H 121GB            | 77        | 0.69%   |
| Apple SSD SM0128G 121GB            | 72        | 0.64%   |
| Kingston SV300S37A120G 120GB SSD   | 67        | 0.6%    |
| Kingston SA400S37120G 120GB SSD    | 66        | 0.59%   |
| Toshiba DT01ACA050 500GB           | 65        | 0.58%   |
| Samsung SSD 860 EVO 500GB          | 65        | 0.58%   |
| Kingston SA400S37480G 480GB SSD    | 65        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB     | 60        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 60        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 59        | 0.53%   |
| Crucial CT500MX500SSD1 500GB       | 59        | 0.53%   |
| Unknown MMC Card  32GB             | 55        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB        | 54        | 0.48%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB     | 53        | 0.47%   |
| Samsung SSD 850 EVO 250GB          | 48        | 0.43%   |
| A-DATA SU800 512GB SSD             | 48        | 0.43%   |
| Toshiba DT01ACA100 1TB             | 46        | 0.41%   |
| Samsung SSD 860 EVO 1TB            | 45        | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 44        | 0.39%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.38%   |
| Crucial CT240BX500SSD1 240GB       | 43        | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 42        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 42        | 0.37%   |
| Unknown AGND3R  16GB               | 40        | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB     | 40        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB     | 39        | 0.35%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 37        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 36        | 0.32%   |
| Samsung SSD 980 1TB                | 36        | 0.32%   |
| Toshiba MQ04ABF100 1TB             | 34        | 0.3%    |
| WDC WD10EZEX-08WN4A0 1TB           | 33        | 0.29%   |
| Hitachi HDS721050CLA362 500GB      | 32        | 0.29%   |
| Toshiba MQ01ABF050 500GB           | 31        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1238      | 2298   | 32.06%  |
| WDC                 | 995       | 1758   | 25.77%  |
| Toshiba             | 592       | 881    | 15.33%  |
| Hitachi             | 295       | 398    | 7.64%   |
| Fujitsu             | 287       | 301    | 7.43%   |
| HGST                | 167       | 303    | 4.33%   |
| Samsung Electronics | 101       | 127    | 2.62%   |
| Unknown             | 30        | 39     | 0.78%   |
| Maxtor              | 22        | 27     | 0.57%   |
| Hewlett-Packard     | 22        | 65     | 0.57%   |
| JMicron Technology  | 21        | 25     | 0.54%   |
| Apple               | 15        | 18     | 0.39%   |
| External            | 7         | 8      | 0.18%   |
| Intenso             | 5         | 5      | 0.13%   |
| ASMT                | 5         | 10     | 0.13%   |
| ASMedia             | 5         | 5      | 0.13%   |
| USB3.0              | 4         | 4      | 0.1%    |
| TO Exter            | 4         | 4      | 0.1%    |
| QNAP                | 3         | 4      | 0.08%   |
| IBM/Hitachi         | 3         | 3      | 0.08%   |
| IBM-ESXS            | 3         | 5      | 0.08%   |
| HPE                 | 3         | 10     | 0.08%   |
| LaCie               | 2         | 2      | 0.05%   |
| JetFlash            | 2         | 4      | 0.05%   |
| Unknown             | 2         | 2      | 0.05%   |
| WD MediaMax         | 1         | 6      | 0.03%   |
| USB                 | 1         | 1      | 0.03%   |
| Unknown (CF)        | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| Space ke            | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| SD                  | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NETAPP              | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 693       | 948    | 20.27%  |
| Kingston            | 520       | 670    | 15.21%  |
| Crucial             | 393       | 478    | 11.49%  |
| SanDisk             | 258       | 327    | 7.55%   |
| WDC                 | 149       | 177    | 4.36%   |
| A-DATA Technology   | 130       | 214    | 3.8%    |
| China               | 120       | 137    | 3.51%   |
| Intel               | 106       | 160    | 3.1%    |
| Apple               | 98        | 108    | 2.87%   |
| Micron Technology   | 58        | 80     | 1.7%    |
| SPCC                | 52        | 60     | 1.52%   |
| PNY                 | 52        | 106    | 1.52%   |
| Transcend           | 48        | 55     | 1.4%    |
| Toshiba             | 43        | 56     | 1.26%   |
| SK hynix            | 40        | 50     | 1.17%   |
| Intenso             | 37        | 49     | 1.08%   |
| Netac               | 36        | 96     | 1.05%   |
| LITEON              | 32        | 38     | 0.94%   |
| SABRENT             | 30        | 31     | 0.88%   |
| Patriot             | 30        | 33     | 0.88%   |
| OCZ                 | 27        | 32     | 0.79%   |
| Team                | 23        | 45     | 0.67%   |
| GOODRAM             | 23        | 31     | 0.67%   |
| Unknown             | 23        | 25     | 0.67%   |
| Apacer              | 22        | 22     | 0.64%   |
| LITEONIT            | 21        | 29     | 0.61%   |
| ASMT                | 16        | 20     | 0.47%   |
| Corsair             | 14        | 18     | 0.41%   |
| Seagate             | 13        | 16     | 0.38%   |
| Hewlett-Packard     | 13        | 19     | 0.38%   |
| Gigabyte Technology | 12        | 12     | 0.35%   |
| KingDian            | 10        | 10     | 0.29%   |
| Plextor             | 9         | 12     | 0.26%   |
| Lexar               | 8         | 10     | 0.23%   |
| Unknown             | 7         | 10     | 0.2%    |
| Mushkin             | 7         | 8      | 0.2%    |
| KIOXIA-EXCERIA      | 7         | 10     | 0.2%    |
| Hajaan              | 7         | 8      | 0.2%    |
| NGFF                | 6         | 6      | 0.18%   |
| LDLC                | 6         | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3292      | 6354   | 35.84%  |
| SSD     | 3011      | 4482   | 32.79%  |
| NVMe    | 2126      | 3029   | 23.15%  |
| MMC     | 643       | 799    | 7%      |
| Unknown | 112       | 193    | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5159      | 10168  | 61.77%  |
| NVMe | 2119      | 3013   | 25.37%  |
| MMC  | 643       | 799    | 7.7%    |
| SAS  | 431       | 877    | 5.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 4056      | 5777   | 60.46%  |
| 0.51-1.0    | 1494      | 2351   | 22.27%  |
| 1.01-2.0    | 508       | 967    | 7.57%   |
| 3.01-4.0    | 273       | 667    | 4.07%   |
| 4.01-10.0   | 200       | 532    | 2.98%   |
| 2.01-3.0    | 113       | 247    | 1.68%   |
| 10.01-20.0  | 62        | 289    | 0.92%   |
| 20.01-50.0  | 1         | 1      | 0.01%   |
| 50.01-100.0 | 1         | 4      | 0.01%   |
| 0           | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1629      | 21.82%  |
| Unknown        | 1529      | 20.48%  |
| 251-500        | 1251      | 16.76%  |
| 501-1000       | 836       | 11.2%   |
| 51-100         | 474       | 6.35%   |
| 1001-2000      | 423       | 5.67%   |
| 1-20           | 422       | 5.65%   |
| More than 3000 | 390       | 5.23%   |
| 21-50          | 343       | 4.6%    |
| 2001-3000      | 167       | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2766      | 36.29%  |
| Unknown        | 1529      | 20.06%  |
| 21-50          | 740       | 9.71%   |
| 101-250        | 717       | 9.41%   |
| 51-100         | 606       | 7.95%   |
| 251-500        | 449       | 5.89%   |
| 501-1000       | 343       | 4.5%    |
| 1001-2000      | 199       | 2.61%   |
| More than 3000 | 165       | 2.16%   |
| 2001-3000      | 86        | 1.13%   |
| 0              | 22        | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 2.25%   |
| Seagate ST500DM002-1BD142 500GB      | 24        | 40     | 2.16%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 21        | 25     | 1.89%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 21     | 1.89%   |
| Seagate ST9500325AS 500GB            | 11        | 13     | 0.99%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 11     | 0.9%    |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.81%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.81%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 8         | 8      | 0.72%   |
| Seagate ST3500418AS 500GB            | 8         | 10     | 0.72%   |
| Hitachi HDS721050CLA362 500GB        | 8         | 8      | 0.72%   |
| Toshiba DT01ACA050 500GB             | 7         | 8      | 0.63%   |
| Seagate ST9500420AS 500GB            | 7         | 8      | 0.63%   |
| Seagate ST3250318AS 250GB            | 7         | 8      | 0.63%   |
| Seagate ST250DM000-1BD141 250GB      | 7         | 7      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 8      | 0.63%   |
| HGST HTS541010A9E680 1TB             | 7         | 7      | 0.63%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.54%   |
| Seagate ST31000528AS 1TB             | 6         | 7      | 0.54%   |
| Hitachi HDS721050DLE630 500GB        | 6         | 11     | 0.54%   |
| WDC WD20EARX-00PASB0 2TB             | 5         | 5      | 0.45%   |
| WDC WD20EARS-00MVWB0 2TB             | 5         | 5      | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB             | 5         | 5      | 0.45%   |
| Toshiba MQ01ABF050 500GB             | 5         | 5      | 0.45%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 5      | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 0.45%   |
| Seagate ST3320613AS 320GB            | 5         | 5      | 0.45%   |
| Seagate ST31500341AS 1TB             | 5         | 7      | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 7      | 0.45%   |
| Hitachi HTS547575A9E384 752GB        | 5         | 5      | 0.45%   |
| Hitachi HTS542512K9SA00 120GB        | 5         | 6      | 0.45%   |
| HGST HTS725050A7E630 500GB           | 5         | 6      | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 4      | 0.36%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 4         | 5      | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB             | 4         | 7      | 0.36%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 4         | 4      | 0.36%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.36%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.36%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 281       | 379    | 26.24%  |
| WDC                 | 225       | 295    | 21.01%  |
| Hitachi             | 113       | 135    | 10.55%  |
| Toshiba             | 85        | 95     | 7.94%   |
| Samsung Electronics | 64        | 72     | 5.98%   |
| Kingston            | 50        | 56     | 4.67%   |
| Intel               | 38        | 46     | 3.55%   |
| Fujitsu             | 35        | 38     | 3.27%   |
| HGST                | 28        | 32     | 2.61%   |
| SK hynix            | 21        | 25     | 1.96%   |
| SanDisk             | 18        | 19     | 1.68%   |
| Crucial             | 16        | 21     | 1.49%   |
| A-DATA Technology   | 15        | 18     | 1.4%    |
| Micron Technology   | 14        | 20     | 1.31%   |
| Maxtor              | 10        | 13     | 0.93%   |
| LITEONIT            | 4         | 5      | 0.37%   |
| LITEON              | 4         | 4      | 0.37%   |
| China               | 4         | 4      | 0.37%   |
| Transcend           | 3         | 3      | 0.28%   |
| Hewlett-Packard     | 3         | 5      | 0.28%   |
| Apple               | 3         | 4      | 0.28%   |
| Apacer              | 3         | 3      | 0.28%   |
| SPCC                | 2         | 2      | 0.19%   |
| ShiJi               | 2         | 2      | 0.19%   |
| PNY                 | 2         | 7      | 0.19%   |
| OCZ                 | 2         | 2      | 0.19%   |
| JMicron Technology  | 2         | 3      | 0.19%   |
| Corsair             | 2         | 2      | 0.19%   |
| Unknown             | 2         | 2      | 0.19%   |
| Western Digital     | 1         | 2      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| Team                | 1         | 1      | 0.09%   |
| SSSTC               | 1         | 1      | 0.09%   |
| Plextor             | 1         | 1      | 0.09%   |
| Patriot             | 1         | 1      | 0.09%   |
| Netac               | 1         | 1      | 0.09%   |
| Lenovo              | 1         | 1      | 0.09%   |
| KingSpec            | 1         | 1      | 0.09%   |
| KingDian            | 1         | 1      | 0.09%   |
| Intenso             | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 281       | 379    | 34.78%  |
| WDC                 | 217       | 286    | 26.86%  |
| Hitachi             | 113       | 135    | 13.99%  |
| Toshiba             | 82        | 92     | 10.15%  |
| Fujitsu             | 35        | 38     | 4.33%   |
| Samsung Electronics | 31        | 34     | 3.84%   |
| HGST                | 28        | 32     | 3.47%   |
| Maxtor              | 10        | 13     | 1.24%   |
| Hewlett-Packard     | 3         | 5      | 0.37%   |
| Apple               | 3         | 4      | 0.37%   |
| USB3.0              | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 2      | 0.12%   |
| IBM/Hitachi         | 1         | 1      | 0.12%   |
| IBM                 | 1         | 4      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 769       | 1027   | 74.81%  |
| SSD  | 216       | 255    | 21.01%  |
| NVMe | 43        | 54     | 4.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 3.57%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 3.57%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 3.57%   |
| Toshiba MK3276GSXN 320GB                        | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 3.57%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 3.57%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 3.57%   |
| Seagate ST2000NM0011 2TB                        | 1         | 1      | 3.57%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB     | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 980 250GB               | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 3.57%   |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 3.57%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 3.57%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 3.57%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 1      | 3.57%   |
| KingDian S400 120GB                             | 1         | 1      | 3.57%   |
| Intel SSDSC2KW256G8 256GB                       | 1         | 1      | 3.57%   |
| Inland SATA SSD 128GB                           | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 3.57%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 3.57%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 3.57%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 3.57%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 3.57%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 28.57%  |
| Seagate             | 7         | 8      | 25%     |
| HGST                | 3         | 4      | 10.71%  |
| WDC                 | 2         | 2      | 7.14%   |
| Toshiba             | 2         | 2      | 7.14%   |
| KingDian            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Inland              | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 2      | 3.57%   |
| Hewlett-Packard     | 1         | 2      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5208      | 9869   | 64.47%  |
| Detected | 1837      | 3618   | 22.74%  |
| Malfunc  | 1003      | 1336   | 12.42%  |
| Failed   | 28        | 32     | 0.35%   |
| Limited  | 2         | 2      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4353      | 50.12%  |
| AMD                              | 1109      | 12.77%  |
| Samsung Electronics              | 854       | 9.83%   |
| Nvidia                           | 438       | 5.04%   |
| SanDisk                          | 341       | 3.93%   |
| SK hynix                         | 152       | 1.75%   |
| ASMedia Technology               | 150       | 1.73%   |
| Phison Electronics               | 122       | 1.4%    |
| Kingston Technology Company      | 113       | 1.3%    |
| Marvell Technology Group         | 87        | 1%      |
| Apple                            | 86        | 0.99%   |
| Toshiba America Info Systems     | 81        | 0.93%   |
| Micron/Crucial Technology        | 79        | 0.91%   |
| Micron Technology                | 79        | 0.91%   |
| JMicron Technology               | 78        | 0.9%    |
| LSI Logic / Symbios Logic        | 77        | 0.89%   |
| KIOXIA                           | 67        | 0.77%   |
| Broadcom / LSI                   | 65        | 0.75%   |
| ADATA Technology                 | 60        | 0.69%   |
| Silicon Motion                   | 55        | 0.63%   |
| VIA Technologies                 | 38        | 0.44%   |
| Hewlett-Packard                  | 24        | 0.28%   |
| Solid State Storage Technology   | 21        | 0.24%   |
| Adaptec                          | 21        | 0.24%   |
| MAXIO Technology (Hangzhou)      | 18        | 0.21%   |
| Realtek Semiconductor            | 16        | 0.18%   |
| Silicon Image                    | 11        | 0.13%   |
| Union Memory (Shenzhen)          | 10        | 0.12%   |
| Silicon Integrated Systems [SiS] | 9         | 0.1%    |
| Shenzhen Longsys Electronics     | 9         | 0.1%    |
| Lite-On Technology               | 9         | 0.1%    |
| Seagate Technology               | 8         | 0.09%   |
| Lenovo                           | 5         | 0.06%   |
| INNOGRIT                         | 5         | 0.06%   |
| Biwin Storage Technology         | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| ULi Electronics                  | 3         | 0.03%   |
| Jiangsu Huacun Elec.             | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| 3ware                            | 3         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 732       | 7.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 437       | 4.39%   |
| Nvidia MCP79 AHCI Controller                                                            | 369       | 3.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 327       | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 278       | 2.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 240       | 2.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 190       | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 169       | 1.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 169       | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 167       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 164       | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 160       | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 156       | 1.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 147       | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 146       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 136       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 135       | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 127       | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 125       | 1.26%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 119       | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 111       | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 106       | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                                  | 103       | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 100       | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 99        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 98        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 95        | 0.95%   |
| Intel SATA Controller [RAID mode]                                                       | 89        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 86        | 0.86%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 85        | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 85        | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 84        | 0.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 80        | 0.8%    |
| Apple S1X NVMe Controller                                                               | 79        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 74        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 72        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 72        | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 69        | 0.69%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 68        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 65        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5054      | 57.24%  |
| NVMe | 2118      | 23.99%  |
| IDE  | 978       | 11.08%  |
| RAID | 549       | 6.22%   |
| SAS  | 105       | 1.19%   |
| SCSI | 26        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5602      | 77.07%  |
| AMD                   | 1342      | 18.46%  |
| ARM                   | 300       | 4.13%   |
| CentaurHauls          | 9         | 0.12%   |
| Unknown               | 5         | 0.07%   |
| sifive,u74-mc         | 4         | 0.06%   |
| Phytium               | 4         | 0.06%   |
| Qualcomm              | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 4.87%   |
| ARM Processor                                 | 257       | 3.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 183       | 2.51%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 149       | 2.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 86        | 1.18%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 64        | 0.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 62        | 0.85%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 54        | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 52        | 0.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 46        | 0.63%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 39        | 0.54%   |
| Intel Celeron N5105 @ 2.00GHz                 | 37        | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.49%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 36        | 0.49%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 33        | 0.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.45%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 32        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 32        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.43%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 31        | 0.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 30        | 0.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 29        | 0.4%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.38%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 28        | 0.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 28        | 0.38%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 28        | 0.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 28        | 0.38%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.37%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.36%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 26        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1413      | 19.43%  |
| Other                   | 866       | 11.91%  |
| Intel Core i7           | 861       | 11.84%  |
| Intel Core 2 Duo        | 601       | 8.26%   |
| Intel Celeron           | 529       | 7.27%   |
| Intel Core i3           | 520       | 7.15%   |
| AMD Ryzen 5             | 324       | 4.45%   |
| Intel Xeon              | 299       | 4.11%   |
| Intel Pentium           | 244       | 3.35%   |
| AMD Ryzen 7             | 228       | 3.13%   |
| Intel Atom              | 152       | 2.09%   |
| AMD Ryzen 9             | 111       | 1.53%   |
| Intel Core 2            | 84        | 1.15%   |
| AMD FX                  | 82        | 1.13%   |
| Intel Pentium Dual-Core | 79        | 1.09%   |
| AMD Ryzen 3             | 55        | 0.76%   |
| Intel Core 2 Quad       | 41        | 0.56%   |
| AMD A6                  | 41        | 0.56%   |
| AMD Ryzen 7 PRO         | 34        | 0.47%   |
| Intel Core i9           | 32        | 0.44%   |
| AMD A10                 | 32        | 0.44%   |
| AMD Ryzen 5 PRO         | 28        | 0.38%   |
| AMD Athlon              | 27        | 0.37%   |
| Intel Pentium Silver    | 26        | 0.36%   |
| Intel Pentium Gold      | 26        | 0.36%   |
| AMD Ryzen Threadripper  | 26        | 0.36%   |
| Intel Pentium 4         | 25        | 0.34%   |
| Intel Genuine           | 25        | 0.34%   |
| AMD A4                  | 25        | 0.34%   |
| Intel Pentium M         | 23        | 0.32%   |
| AMD A8                  | 23        | 0.32%   |
| Intel Pentium Dual      | 22        | 0.3%    |
| AMD Athlon II X2        | 20        | 0.27%   |
| AMD Athlon 64 X2        | 19        | 0.26%   |
| ARM Allwinner           | 18        | 0.25%   |
| AMD Phenom II X4        | 18        | 0.25%   |
| AMD GX                  | 17        | 0.23%   |
| AMD E                   | 15        | 0.21%   |
| Intel Xeon Gold         | 13        | 0.18%   |
| Intel Celeron M         | 13        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3027      | 41.58%  |
| 4       | 2485      | 34.13%  |
| 6       | 626       | 8.6%    |
| 8       | 485       | 6.66%   |
| 1       | 242       | 3.32%   |
| 12      | 116       | 1.59%   |
| 16      | 100       | 1.37%   |
| 10      | 48        | 0.66%   |
| 3       | 34        | 0.47%   |
| Unknown | 25        | 0.34%   |
| 14      | 21        | 0.29%   |
| 24      | 20        | 0.27%   |
| 32      | 18        | 0.25%   |
| 20      | 7         | 0.1%    |
| 28      | 5         | 0.07%   |
| 48      | 4         | 0.05%   |
| 18      | 4         | 0.05%   |
| 36      | 3         | 0.04%   |
| 64      | 2         | 0.03%   |
| 44      | 2         | 0.03%   |
| 192     | 1         | 0.01%   |
| 128     | 1         | 0.01%   |
| 96      | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7078      | 97.33%  |
| 2       | 158       | 2.17%   |
| Unknown | 25        | 0.34%   |
| 3       | 6         | 0.08%   |
| 4       | 3         | 0.04%   |
| 8       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4117      | 56.55%  |
| 1       | 3136      | 43.08%  |
| Unknown | 25        | 0.34%   |
| 12      | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7057      | 97.06%  |
| 32-bit         | 128       | 1.76%   |
| Unknown        | 61        | 0.84%   |
| 64-bit         | 25        | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1501      | 20.27%  |
| 0x1067a    | 568       | 7.67%   |
| 0x306a9    | 326       | 4.4%    |
| 0x306c3    | 324       | 4.38%   |
| 0x206a7    | 310       | 4.19%   |
| 0x806c1    | 285       | 3.85%   |
| 0x306d4    | 233       | 3.15%   |
| 0x906ea    | 170       | 2.3%    |
| 0x506e3    | 152       | 2.05%   |
| 0x806ec    | 140       | 1.89%   |
| 0x806e9    | 130       | 1.76%   |
| 0x30678    | 123       | 1.66%   |
| 0x806ea    | 110       | 1.49%   |
| 0x406e3    | 97        | 1.31%   |
| 0x40651    | 94        | 1.27%   |
| 0x08108109 | 92        | 1.24%   |
| 0x906e9    | 89        | 1.2%    |
| 0x406c4    | 86        | 1.16%   |
| 0xa0653    | 84        | 1.13%   |
| 0x906c0    | 75        | 1.01%   |
| 0x6f6      | 74        | 1%      |
| 0x08701021 | 72        | 0.97%   |
| 0x20655    | 69        | 0.93%   |
| 0x906eb    | 67        | 0.9%    |
| 0x706a8    | 66        | 0.89%   |
| 0x0a50000c | 66        | 0.89%   |
| 0x08600106 | 63        | 0.85%   |
| 0xa0652    | 59        | 0.8%    |
| 0x10676    | 55        | 0.74%   |
| 0x506c9    | 54        | 0.73%   |
| 0x6fd      | 53        | 0.72%   |
| 0x08608103 | 46        | 0.62%   |
| 0x0600611a | 44        | 0.59%   |
| 0xa0671    | 43        | 0.58%   |
| 0xa0655    | 42        | 0.57%   |
| 0x0a201016 | 42        | 0.57%   |
| 0x706e5    | 41        | 0.55%   |
| 0x106c2    | 39        | 0.53%   |
| 0x306f2    | 38        | 0.51%   |
| 0x0800820d | 37        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 941       | 12.92%  |
| Penryn           | 665       | 9.13%   |
| Haswell          | 568       | 7.8%    |
| Unknown          | 544       | 7.47%   |
| IvyBridge        | 435       | 5.97%   |
| SandyBridge      | 425       | 5.84%   |
| Skylake          | 337       | 4.63%   |
| TigerLake        | 332       | 4.56%   |
| Broadwell        | 277       | 3.8%    |
| Silvermont       | 272       | 3.74%   |
| Zen 2            | 238       | 3.27%   |
| Zen 3            | 225       | 3.09%   |
| CometLake        | 221       | 3.03%   |
| Core             | 208       | 2.86%   |
| Zen+             | 207       | 2.84%   |
| Westmere         | 158       | 2.17%   |
| Goldmont plus    | 111       | 1.52%   |
| Excavator        | 102       | 1.4%    |
| Zen              | 92        | 1.26%   |
| Piledriver       | 88        | 1.21%   |
| K10              | 88        | 1.21%   |
| Bonnell          | 86        | 1.18%   |
| Tremont          | 85        | 1.17%   |
| Icelake          | 84        | 1.15%   |
| Goldmont         | 65        | 0.89%   |
| P6               | 62        | 0.85%   |
| Alderlake Hybrid | 54        | 0.74%   |
| Nehalem          | 52        | 0.71%   |
| NetBurst         | 43        | 0.59%   |
| Bobcat           | 43        | 0.59%   |
| K8 Hammer        | 42        | 0.58%   |
| Puma             | 32        | 0.44%   |
| Jaguar           | 26        | 0.36%   |
| Steamroller      | 25        | 0.34%   |
| Bulldozer        | 22        | 0.3%    |
| K10 Llano        | 12        | 0.16%   |
| K8 & K10 hybrid  | 7         | 0.1%    |
| K6               | 4         | 0.05%   |
| Gracemont        | 2         | 0.03%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4191      | 53.61%  |
| Nvidia                                       | 1959      | 25.06%  |
| AMD                                          | 1411      | 18.05%  |
| Matrox Electronics Systems                   | 119       | 1.52%   |
| ASPEED Technology                            | 114       | 1.46%   |
| VIA Technologies                             | 11        | 0.14%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.09%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 4.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 306       | 3.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 288       | 3.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 215       | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 179       | 2.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 173       | 2.14%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 156       | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 152       | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 146       | 1.8%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 128       | 1.58%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 124       | 1.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 119       | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 116       | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 114       | 1.41%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 114       | 1.41%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 110       | 1.36%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 108       | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 106       | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 105       | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 98        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 95        | 1.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 88        | 1.09%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 88        | 1.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 86        | 1.06%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 83        | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 83        | 1.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 78        | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 75        | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 74        | 0.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 64        | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 63        | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 63        | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 62        | 0.77%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 61        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 60        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 60        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 60        | 0.74%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 60        | 0.74%   |
| AMD Lucienne                                                                             | 60        | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 57        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3442      | 47.18%  |
| 1 x Nvidia                        | 1278      | 17.52%  |
| 1 x AMD                           | 1145      | 15.69%  |
| Intel + Nvidia                    | 563       | 7.72%   |
| Other                             | 342       | 4.69%   |
| 1 x Matrox                        | 114       | 1.56%   |
| Intel + AMD                       | 105       | 1.44%   |
| 1 x ASPEED                        | 90        | 1.23%   |
| AMD + Nvidia                      | 87        | 1.19%   |
| 2 x AMD                           | 61        | 0.84%   |
| Nvidia + ASPEED                   | 12        | 0.16%   |
| 1 x VIA                           | 11        | 0.15%   |
| 2 x Nvidia                        | 9         | 0.12%   |
| AMD + ASPEED                      | 9         | 0.12%   |
| 1 x SiS                           | 7         | 0.1%    |
| Nvidia + Matrox                   | 4         | 0.05%   |
| 2 x Intel                         | 3         | 0.04%   |
| 1 x Zhaoxin                       | 3         | 0.04%   |
| Intel + 2 x Nvidia                | 3         | 0.04%   |
| 3 x AMD                           | 2         | 0.03%   |
| 2 x Nvidia + 1 x ASPEED           | 2         | 0.03%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x S3 Graphics                   | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| AMD + Matrox                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5214      | 71.21%  |
| Unknown     | 1562      | 21.33%  |
| Proprietary | 546       | 7.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 5288      | 71.97%  |
| 0.01-0.5       | 836       | 11.38%  |
| 1.01-2.0       | 407       | 5.54%   |
| 0.51-1.0       | 258       | 3.51%   |
| 3.01-4.0       | 251       | 3.42%   |
| 7.01-8.0       | 139       | 1.89%   |
| 5.01-6.0       | 87        | 1.18%   |
| 8.01-16.0      | 39        | 0.53%   |
| 2.01-3.0       | 26        | 0.35%   |
| 16.01-24.0     | 8         | 0.11%   |
| 4.01-5.0       | 5         | 0.07%   |
| More than 64.0 | 1         | 0.01%   |
| 32.01-64.0     | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 745       | 11.84%  |
| Apple                   | 664       | 10.55%  |
| Samsung Electronics     | 613       | 9.74%   |
| BOE                     | 513       | 8.15%   |
| LG Display              | 451       | 7.17%   |
| Chimei Innolux          | 437       | 6.94%   |
| Dell                    | 339       | 5.39%   |
| Goldstar                | 268       | 4.26%   |
| Hewlett-Packard         | 179       | 2.84%   |
| Acer                    | 164       | 2.61%   |
| BenQ                    | 155       | 2.46%   |
| AOC                     | 138       | 2.19%   |
| Philips                 | 133       | 2.11%   |
| Lenovo                  | 130       | 2.07%   |
| Ancor Communications    | 115       | 1.83%   |
| Sharp                   | 80        | 1.27%   |
| Unknown                 | 74        | 1.18%   |
| ViewSonic               | 73        | 1.16%   |
| Iiyama                  | 73        | 1.16%   |
| Chi Mei Optoelectronics | 72        | 1.14%   |
| InfoVision              | 66        | 1.05%   |
| Eizo                    | 43        | 0.68%   |
| ASUSTek Computer        | 41        | 0.65%   |
| PANDA                   | 39        | 0.62%   |
| Sony                    | 37        | 0.59%   |
| HannStar                | 36        | 0.57%   |
| NEC Computers           | 35        | 0.56%   |
| LG Philips              | 27        | 0.43%   |
| LG Electronics          | 24        | 0.38%   |
| MSI                     | 18        | 0.29%   |
| CSO                     | 18        | 0.29%   |
| Unknown                 | 18        | 0.29%   |
| Panasonic               | 15        | 0.24%   |
| Vestel Elektronik       | 14        | 0.22%   |
| Toshiba                 | 13        | 0.21%   |
| Fujitsu Siemens         | 12        | 0.19%   |
| Vizio                   | 11        | 0.17%   |
| Medion                  | 11        | 0.17%   |
| Hitachi                 | 9         | 0.14%   |
| AGO                     | 9         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 209       | 3.24%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 187       | 2.9%    |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 112       | 1.74%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 57        | 0.88%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 0.84%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 42        | 0.65%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 41        | 0.64%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.64%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 28        | 0.43%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 26        | 0.4%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 25        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 23        | 0.36%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 22        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 22        | 0.34%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 20        | 0.31%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 18        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 18        | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 18        | 0.28%   |
| Unknown                                                              | 18        | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 17        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 17        | 0.26%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 16        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 16        | 0.25%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                    | 14        | 0.22%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch | 13        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 13        | 0.2%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 13        | 0.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 13        | 0.2%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 13        | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 12        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 12        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 11        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 11        | 0.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 11        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 11        | 0.17%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 10        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2442      | 40.4%   |
| 1366x768 (WXGA)    | 1049      | 17.36%  |
| 1280x800 (WXGA)    | 546       | 9.03%   |
| 3840x2160 (4K)     | 328       | 5.43%   |
| 2560x1440 (QHD)    | 231       | 3.82%   |
| 1280x1024 (SXGA)   | 230       | 3.81%   |
| 1600x900 (HD+)     | 194       | 3.21%   |
| 1440x900 (WXGA+)   | 180       | 2.98%   |
| 1920x1200 (WUXGA)  | 136       | 2.25%   |
| 1680x1050 (WSXGA+) | 123       | 2.04%   |
| Unknown            | 68        | 1.13%   |
| 2288x1287          | 59        | 0.98%   |
| 1024x600           | 56        | 0.93%   |
| 1024x768 (XGA)     | 47        | 0.78%   |
| 2560x1080          | 40        | 0.66%   |
| 1360x768           | 40        | 0.66%   |
| 3440x1440          | 37        | 0.61%   |
| 2560x1600          | 27        | 0.45%   |
| 1600x1200          | 24        | 0.4%    |
| 3840x1080          | 23        | 0.38%   |
| 3840x2400          | 13        | 0.22%   |
| 1920x540           | 13        | 0.22%   |
| 2160x1440          | 11        | 0.18%   |
| 2880x1800          | 10        | 0.17%   |
| 1400x1050          | 9         | 0.15%   |
| 2880x1920          | 7         | 0.12%   |
| 4480x1440          | 6         | 0.1%    |
| 1920x1280          | 6         | 0.1%    |
| 2048x1152          | 5         | 0.08%   |
| 5760x1080          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3200x1080          | 4         | 0.07%   |
| 1280x720 (HD)      | 4         | 0.07%   |
| 5760x2160          | 3         | 0.05%   |
| 5120x1440          | 3         | 0.05%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1800 (QHD+)   | 3         | 0.05%   |
| 2736x1824          | 3         | 0.05%   |
| 2256x1504          | 3         | 0.05%   |
| 1800x1200          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1179      | 18.9%   |
| 13      | 1133      | 18.16%  |
| 24      | 463       | 7.42%   |
| 14      | 458       | 7.34%   |
| 27      | 375       | 6.01%   |
| 23      | 338       | 5.42%   |
| 17      | 296       | 4.74%   |
| 21      | 286       | 4.58%   |
| 11      | 266       | 4.26%   |
| Unknown | 203       | 3.25%   |
| 19      | 167       | 2.68%   |
| 12      | 133       | 2.13%   |
| 31      | 131       | 2.1%    |
| 18      | 119       | 1.91%   |
| 22      | 86        | 1.38%   |
| 20      | 82        | 1.31%   |
| 10      | 64        | 1.03%   |
| 34      | 59        | 0.95%   |
| 142     | 57        | 0.91%   |
| 32      | 38        | 0.61%   |
| 84      | 37        | 0.59%   |
| 72      | 32        | 0.51%   |
| 16      | 29        | 0.46%   |
| 25      | 24        | 0.38%   |
| 54      | 22        | 0.35%   |
| 40      | 18        | 0.29%   |
| 28      | 16        | 0.26%   |
| 29      | 13        | 0.21%   |
| 52      | 11        | 0.18%   |
| 26      | 11        | 0.18%   |
| 65      | 10        | 0.16%   |
| 43      | 7         | 0.11%   |
| 33      | 7         | 0.11%   |
| 49      | 6         | 0.1%    |
| 48      | 6         | 0.1%    |
| 42      | 6         | 0.1%    |
| 63      | 5         | 0.08%   |
| 46      | 5         | 0.08%   |
| 39      | 4         | 0.06%   |
| 37      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2018      | 32.85%  |
| 201-300        | 1312      | 21.36%  |
| 501-600        | 1086      | 17.68%  |
| 401-500        | 625       | 10.17%  |
| 351-400        | 329       | 5.36%   |
| 601-700        | 206       | 3.35%   |
| Unknown        | 203       | 3.3%    |
| 701-800        | 107       | 1.74%   |
| 1001-1500      | 79        | 1.29%   |
| 1501-2000      | 74        | 1.2%    |
| More than 2000 | 58        | 0.94%   |
| 801-900        | 30        | 0.49%   |
| 901-1000       | 11        | 0.18%   |
| 101-200        | 5         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3972      | 69.38%  |
| 16/10   | 1060      | 18.52%  |
| 5/4     | 211       | 3.69%   |
| Unknown | 164       | 2.86%   |
| 4/3     | 99        | 1.73%   |
| 21/9    | 72        | 1.26%   |
| 1.00    | 59        | 1.03%   |
| 3/2     | 49        | 0.86%   |
| 6/5     | 14        | 0.24%   |
| 32/9    | 7         | 0.12%   |
| 2.65    | 5         | 0.09%   |
| 3.40    | 2         | 0.03%   |
| 3.20    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 0.45    | 2         | 0.03%   |
| 3.73    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1229      | 19.85%  |
| 101-110        | 1167      | 18.85%  |
| 201-250        | 930       | 15.02%  |
| 301-350        | 384       | 6.2%    |
| 71-80          | 360       | 5.81%   |
| 151-200        | 335       | 5.41%   |
| 51-60          | 269       | 4.34%   |
| 351-500        | 257       | 4.15%   |
| 141-150        | 203       | 3.28%   |
| Unknown        | 203       | 3.28%   |
| More than 1000 | 198       | 3.2%    |
| 251-300        | 176       | 2.84%   |
| 121-130        | 163       | 2.63%   |
| 61-70          | 123       | 1.99%   |
| 41-50          | 63        | 1.02%   |
| 501-1000       | 53        | 0.86%   |
| 131-140        | 32        | 0.52%   |
| 111-120        | 27        | 0.44%   |
| 91-100         | 15        | 0.24%   |
| 1-40           | 5         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1828      | 30.25%  |
| 121-160       | 1686      | 27.9%   |
| 101-120       | 1685      | 27.89%  |
| 161-240       | 392       | 6.49%   |
| Unknown       | 203       | 3.36%   |
| 1-50          | 175       | 2.9%    |
| More than 240 | 73        | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4808      | 65.05%  |
| 0     | 1668      | 22.57%  |
| 2     | 823       | 11.14%  |
| 3     | 89        | 1.2%    |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3415      | 32.45%  |
| Intel                             | 3249      | 30.88%  |
| Qualcomm Atheros                  | 910       | 8.65%   |
| Broadcom                          | 878       | 8.34%   |
| Nvidia                            | 425       | 4.04%   |
| Broadcom Limited                  | 279       | 2.65%   |
| Marvell Technology Group          | 153       | 1.45%   |
| MediaTek                          | 109       | 1.04%   |
| Ralink Technology                 | 88        | 0.84%   |
| TP-Link                           | 83        | 0.79%   |
| Ralink                            | 68        | 0.65%   |
| ASIX Electronics                  | 67        | 0.64%   |
| Samsung Electronics               | 48        | 0.46%   |
| Microchip Technology              | 46        | 0.44%   |
| Xiaomi                            | 34        | 0.32%   |
| Dell                              | 33        | 0.31%   |
| Sierra Wireless                   | 31        | 0.29%   |
| Mellanox Technologies             | 30        | 0.29%   |
| Qualcomm Atheros Communications   | 25        | 0.24%   |
| Qualcomm                          | 25        | 0.24%   |
| Huawei Technologies               | 23        | 0.22%   |
| DisplayLink                       | 21        | 0.2%    |
| NetGear                           | 20        | 0.19%   |
| Aquantia                          | 20        | 0.19%   |
| American Megatrends               | 19        | 0.18%   |
| Shenzhen Goodix Technology        | 18        | 0.17%   |
| D-Link System                     | 18        | 0.17%   |
| Lenovo                            | 17        | 0.16%   |
| JMicron Technology                | 16        | 0.15%   |
| Ericsson Business Mobile Networks | 15        | 0.14%   |
| Dresden Elektronik                | 15        | 0.14%   |
| D-Link                            | 15        | 0.14%   |
| VIA Technologies                  | 14        | 0.13%   |
| Hewlett-Packard                   | 14        | 0.13%   |
| Edimax Technology                 | 14        | 0.13%   |
| ASUSTek Computer                  | 14        | 0.13%   |
| Sigma Designs                     | 13        | 0.12%   |
| Microsoft                         | 12        | 0.11%   |
| QinHeng Electronics               | 11        | 0.1%    |
| OPPO Electronics                  | 11        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 2377      | 19.31%  |
| Nvidia MCP79 Ethernet                                                                 | 370       | 3.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 365       | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 338       | 2.75%   |
| Intel Wi-Fi 6 AX201                                                                   | 267       | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 239       | 1.94%   |
| Intel Wi-Fi 6 AX200                                                                   | 209       | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 193       | 1.57%   |
| Intel Wireless 8265 / 8275                                                            | 177       | 1.44%   |
| Intel Wireless 7260                                                                   | 177       | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 168       | 1.36%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 165       | 1.34%   |
| Intel Wireless 7265                                                                   | 161       | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 159       | 1.29%   |
| Intel Ethernet Connection (13) I219-V                                                 | 138       | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 124       | 1.01%   |
| Intel I211 Gigabit Network Connection                                                 | 106       | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 102       | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 100       | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 95        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 95        | 0.77%   |
| Intel Wireless 8260                                                                   | 94        | 0.76%   |
| Intel Wireless 3165                                                                   | 93        | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 0.75%   |
| Intel I210 Gigabit Network Connection                                                 | 92        | 0.75%   |
| Intel Ethernet Controller I225-V                                                      | 92        | 0.75%   |
| Intel Ethernet Connection I217-LM                                                     | 91        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 90        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 85        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 76        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                                  | 70        | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 66        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 63        | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 61        | 0.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 60        | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 59        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                                  | 58        | 0.47%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 55        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2214      | 44.15%  |
| Qualcomm Atheros                      | 738       | 14.72%  |
| Realtek Semiconductor                 | 693       | 13.82%  |
| Broadcom                              | 615       | 12.26%  |
| Broadcom Limited                      | 219       | 4.37%   |
| MediaTek                              | 99        | 1.97%   |
| Ralink Technology                     | 88        | 1.75%   |
| Ralink                                | 68        | 1.36%   |
| TP-Link                               | 63        | 1.26%   |
| Sierra Wireless                       | 31        | 0.62%   |
| Qualcomm Atheros Communications       | 25        | 0.5%    |
| NetGear                               | 19        | 0.38%   |
| Dell                                  | 19        | 0.38%   |
| Edimax Technology                     | 14        | 0.28%   |
| ASUSTek Computer                      | 14        | 0.28%   |
| D-Link                                | 12        | 0.24%   |
| Qualcomm                              | 11        | 0.22%   |
| Marvell Technology Group              | 10        | 0.2%    |
| Microsoft                             | 8         | 0.16%   |
| Fibocom                               | 8         | 0.16%   |
| D-Link System                         | 8         | 0.16%   |
| Belkin Components                     | 7         | 0.14%   |
| Gemtek                                | 4         | 0.08%   |
| Wilocity                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| AVM                                   | 3         | 0.06%   |
| Linksys                               | 2         | 0.04%   |
| Hewlett-Packard                       | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| Z-Com                                 | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| CyberTAN Technology                   | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 365       | 7.25%   |
| Intel Wi-Fi 6 AX201                                                                   | 267       | 5.3%    |
| Intel Wi-Fi 6 AX200                                                                   | 209       | 4.15%   |
| Intel Wireless 8265 / 8275                                                            | 177       | 3.51%   |
| Intel Wireless 7260                                                                   | 177       | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 168       | 3.34%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 165       | 3.28%   |
| Intel Wireless 7265                                                                   | 161       | 3.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 124       | 2.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 102       | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 100       | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 95        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 95        | 1.89%   |
| Intel Wireless 8260                                                                   | 94        | 1.87%   |
| Intel Wireless 3165                                                                   | 93        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 90        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 85        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 76        | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 66        | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 63        | 1.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 60        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 59        | 1.17%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 1.09%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]                  | 53        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 48        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 47        | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 44        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 43        | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 42        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 40        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 36        | 0.71%   |
| Realtek 802.11ac NIC                                                                  | 35        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 33        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                                       | 32        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                                        | 31        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 30        | 0.6%    |
| Intel Wireless 3160                                                                   | 30        | 0.6%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 30        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3127      | 45.94%  |
| Intel                            | 1961      | 28.81%  |
| Nvidia                           | 424       | 6.23%   |
| Broadcom                         | 317       | 4.66%   |
| Qualcomm Atheros                 | 255       | 3.75%   |
| Marvell Technology Group         | 144       | 2.12%   |
| ASIX Electronics                 | 67        | 0.98%   |
| Broadcom Limited                 | 63        | 0.93%   |
| Microchip Technology             | 46        | 0.68%   |
| Samsung Electronics              | 45        | 0.66%   |
| Xiaomi                           | 33        | 0.48%   |
| Mellanox Technologies            | 28        | 0.41%   |
| DisplayLink                      | 21        | 0.31%   |
| TP-Link                          | 20        | 0.29%   |
| Aquantia                         | 20        | 0.29%   |
| American Megatrends              | 19        | 0.28%   |
| Lenovo                           | 17        | 0.25%   |
| JMicron Technology               | 16        | 0.24%   |
| VIA Technologies                 | 14        | 0.21%   |
| Huawei Technologies              | 14        | 0.21%   |
| Qualcomm                         | 13        | 0.19%   |
| OPPO Electronics                 | 11        | 0.16%   |
| ICS Advent                       | 10        | 0.15%   |
| D-Link System                    | 10        | 0.15%   |
| MediaTek                         | 9         | 0.13%   |
| Silicon Integrated Systems [SiS] | 8         | 0.12%   |
| IBM                              | 8         | 0.12%   |
| 3Com                             | 7         | 0.1%    |
| Motorola PCS                     | 6         | 0.09%   |
| Cypress Semiconductor            | 6         | 0.09%   |
| NetXen Incorporated              | 4         | 0.06%   |
| Hewlett-Packard                  | 4         | 0.06%   |
| Emulex                           | 4         | 0.06%   |
| Attansic Technology              | 4         | 0.06%   |
| QLogic                           | 3         | 0.04%   |
| Microsoft                        | 3         | 0.04%   |
| Insyde Software                  | 3         | 0.04%   |
| Google                           | 3         | 0.04%   |
| Dell                             | 3         | 0.04%   |
| D-Link                           | 3         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2377      | 33.62%  |
| Nvidia MCP79 Ethernet                                                  | 370       | 5.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 338       | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 239       | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 193       | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 159       | 2.25%   |
| Intel Ethernet Connection (13) I219-V                                  | 138       | 1.95%   |
| Intel I211 Gigabit Network Connection                                  | 106       | 1.5%    |
| Intel I210 Gigabit Network Connection                                  | 92        | 1.3%    |
| Intel Ethernet Controller I225-V                                       | 92        | 1.3%    |
| Intel Ethernet Connection I217-LM                                      | 91        | 1.29%   |
| Intel Ethernet Connection (2) I219-V                                   | 70        | 0.99%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 61        | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                   | 58        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 55        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 55        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 54        | 0.76%   |
| Intel 82574L Gigabit Network Connection                                | 54        | 0.76%   |
| Intel I350 Gigabit Network Connection                                  | 49        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 47        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 47        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 45        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                   | 45        | 0.64%   |
| Intel Ethernet Connection (14) I219-V                                  | 44        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                   | 40        | 0.57%   |
| Intel Ethernet Connection I218-LM                                      | 38        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 38        | 0.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 37        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 35        | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 35        | 0.5%    |
| Intel Ethernet Connection (10) I219-V                                  | 35        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                               | 32        | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 31        | 0.44%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 31        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 30        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                  | 30        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 29        | 0.41%   |
| Nvidia MCP61 Ethernet                                                  | 29        | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 29        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 28        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6270      | 55.68%  |
| WiFi     | 4794      | 42.58%  |
| Modem    | 183       | 1.63%   |
| Unknown  | 13        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3857      | 54.21%  |
| WiFi     | 3255      | 45.75%  |
| Modem    | 3         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3702      | 50.79%  |
| 1     | 2808      | 38.52%  |
| 0     | 364       | 4.99%   |
| 3     | 222       | 3.05%   |
| 4     | 103       | 1.41%   |
| 6     | 31        | 0.43%   |
| 5     | 24        | 0.33%   |
| 8     | 16        | 0.22%   |
| 7     | 8         | 0.11%   |
| 9     | 3         | 0.04%   |
| 20    | 2         | 0.03%   |
| 12    | 2         | 0.03%   |
| 17    | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5894      | 80.41%  |
| Yes  | 1436      | 19.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1807      | 45.03%  |
| Apple                           | 677       | 16.87%  |
| Realtek Semiconductor           | 340       | 8.47%   |
| Qualcomm Atheros Communications | 252       | 6.28%   |
| Cambridge Silicon Radio         | 192       | 4.78%   |
| Broadcom                        | 159       | 3.96%   |
| IMC Networks                    | 134       | 3.34%   |
| Lite-On Technology              | 118       | 2.94%   |
| Foxconn / Hon Hai               | 76        | 1.89%   |
| ASUSTek Computer                | 50        | 1.25%   |
| Dell                            | 43        | 1.07%   |
| Hewlett-Packard                 | 34        | 0.85%   |
| MediaTek                        | 29        | 0.72%   |
| Toshiba                         | 20        | 0.5%    |
| Realtek                         | 17        | 0.42%   |
| Ralink                          | 12        | 0.3%    |
| Ralink Technology               | 6         | 0.15%   |
| TP-Link                         | 5         | 0.12%   |
| Alps Electric                   | 5         | 0.12%   |
| Taiyo Yuden                     | 4         | 0.1%    |
| Marvell Semiconductor           | 4         | 0.1%    |
| Foxconn International           | 4         | 0.1%    |
| USI                             | 3         | 0.07%   |
| Fujitsu                         | 3         | 0.07%   |
| Belkin Components               | 3         | 0.07%   |
| Edimax Technology               | 2         | 0.05%   |
| Unknown                         | 2         | 0.05%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |
| AICSemi                         | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 691       | 17.21%  |
| Intel AX201 Bluetooth                               | 441       | 10.98%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 366       | 9.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 235       | 5.85%   |
| Realtek Bluetooth Radio                             | 228       | 5.68%   |
| Intel AX200 Bluetooth                               | 199       | 4.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 192       | 4.78%   |
| Apple Bluetooth USB Host Controller                 | 174       | 4.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 148       | 3.69%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 71        | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 57        | 1.42%   |
| Apple Bluetooth Host Controller                     | 48        | 1.2%    |
| Intel AX210 Bluetooth                               | 47        | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 44        | 1.1%    |
| Intel Bluetooth Device                              | 44        | 1.1%    |
| IMC Networks Bluetooth Radio                        | 41        | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 38        | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 35        | 0.87%   |
| IMC Networks Bluetooth Device                       | 34        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 0.77%   |
| Lite-On Bluetooth Device                            | 29        | 0.72%   |
| MediaTek Wireless_Device                            | 28        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 28        | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 0.6%    |
| IMC Networks Wireless_Device                        | 24        | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 21        | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 21        | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 20        | 0.5%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 0.47%   |
| Realtek Bluetooth Radio                             | 17        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.35%   |
| Apple Bluetooth HCI                                 | 13        | 0.32%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4855      | 55.95%  |
| Nvidia                                       | 1570      | 18.09%  |
| AMD                                          | 1493      | 17.2%   |
| C-Media Electronics                          | 120       | 1.38%   |
| Logitech                                     | 57        | 0.66%   |
| Creative Labs                                | 38        | 0.44%   |
| ASUSTek Computer                             | 31        | 0.36%   |
| Texas Instruments                            | 28        | 0.32%   |
| Generalplus Technology                       | 28        | 0.32%   |
| Realtek Semiconductor                        | 27        | 0.31%   |
| KTMicro                                      | 25        | 0.29%   |
| Lenovo                                       | 23        | 0.27%   |
| Plantronics                                  | 22        | 0.25%   |
| VIA Technologies                             | 20        | 0.23%   |
| Creative Technology                          | 20        | 0.23%   |
| GN Netcom                                    | 19        | 0.22%   |
| JMTek                                        | 17        | 0.2%    |
| Focusrite-Novation                           | 16        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 14        | 0.16%   |
| Kingston Technology                          | 12        | 0.14%   |
| Micro Star International                     | 11        | 0.13%   |
| SteelSeries ApS                              | 9         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 9         | 0.1%    |
| Hewlett-Packard                              | 9         | 0.1%    |
| DSEA A/S                                     | 9         | 0.1%    |
| RODE Microphones                             | 8         | 0.09%   |
| Razer USA                                    | 8         | 0.09%   |
| Dell                                         | 8         | 0.09%   |
| GYROCOM C&C                                  | 7         | 0.08%   |
| BEHRINGER International                      | 7         | 0.08%   |
| Microsoft                                    | 6         | 0.07%   |
| Yamaha                                       | 5         | 0.06%   |
| Tenx Technology                              | 5         | 0.06%   |
| Samson Technologies                          | 5         | 0.06%   |
| M-Audio                                      | 5         | 0.06%   |
| Giga-Byte Technology                         | 5         | 0.06%   |
| Cambridge Silicon Radio                      | 5         | 0.06%   |
| Apple                                        | 5         | 0.06%   |
| SAVITECH                                     | 4         | 0.05%   |
| Ensoniq                                      | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 502       | 4.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 418       | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 390       | 3.8%    |
| Nvidia MCP79 High Definition Audio                                                                | 373       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 365       | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 348       | 3.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 331       | 3.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 306       | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 272       | 2.65%   |
| Intel Broadwell-U Audio Controller                                                                | 255       | 2.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 250       | 2.43%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 250       | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 213       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 192       | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 192       | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 183       | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 180       | 1.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 168       | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 137       | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 137       | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 131       | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 130       | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 124       | 1.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 123       | 1.2%    |
| Intel 8 Series HD Audio Controller                                                                | 123       | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 119       | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 112       | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 112       | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 111       | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 109       | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 104       | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 103       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 98        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 91        | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 89        | 0.87%   |
| Intel Jasper Lake HD Audio                                                                        | 76        | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 76        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 75        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 73        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 68        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1476      | 21.18%  |
| SK hynix            | 1400      | 20.09%  |
| Kingston            | 771       | 11.06%  |
| Unknown             | 669       | 9.6%    |
| Micron Technology   | 584       | 8.38%   |
| Crucial             | 549       | 7.88%   |
| Corsair             | 269       | 3.86%   |
| G.Skill             | 166       | 2.38%   |
| Elpida              | 123       | 1.76%   |
| A-DATA Technology   | 116       | 1.66%   |
| Ramaxel Technology  | 96        | 1.38%   |
| Patriot             | 79        | 1.13%   |
| Unknown             | 69        | 0.99%   |
| Unknown (ABCD)      | 68        | 0.98%   |
| Nanya Technology    | 62        | 0.89%   |
| Team                | 42        | 0.6%    |
| GOODRAM             | 38        | 0.55%   |
| Smart               | 36        | 0.52%   |
| Transcend           | 27        | 0.39%   |
| Hikvision           | 22        | 0.32%   |
| AMD                 | 22        | 0.32%   |
| Timetec             | 17        | 0.24%   |
| Hewlett-Packard     | 16        | 0.23%   |
| Apacer              | 15        | 0.22%   |
| Silicon Power       | 11        | 0.16%   |
| Qimonda             | 9         | 0.13%   |
| PNY                 | 8         | 0.11%   |
| GeIL                | 8         | 0.11%   |
| Avant               | 8         | 0.11%   |
| ASint Technology    | 8         | 0.11%   |
| Unknown (0x5846)    | 7         | 0.1%    |
| Wilk                | 5         | 0.07%   |
| Unknown (AB)        | 5         | 0.07%   |
| Unifosa             | 5         | 0.07%   |
| Infineon            | 5         | 0.07%   |
| Goldkey             | 5         | 0.07%   |
| 48spaces            | 5         | 0.07%   |
| Unknown (0x0DD5)    | 4         | 0.06%   |
| Toshiba             | 4         | 0.06%   |
| Teikon              | 4         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 3.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 145       | 1.95%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 69        | 0.93%   |
| Unknown                                                          | 69        | 0.93%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.85%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 61        | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 47        | 0.63%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.59%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 41        | 0.55%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 40        | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 37        | 0.5%    |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 36        | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 35        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 33        | 0.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 33        | 0.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 31        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 31        | 0.42%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2667MT/s            | 31        | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.39%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.39%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 29        | 0.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 28        | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 27        | 0.36%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 27        | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.35%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 26        | 0.35%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.32%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 3600MT/s             | 24        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 23        | 0.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.31%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 22        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2639      | 42.72%  |
| DDR3         | 2016      | 32.64%  |
| DDR2         | 683       | 11.06%  |
| SDRAM        | 221       | 3.58%   |
| Unknown      | 185       | 2.99%   |
| LPDDR4       | 172       | 2.78%   |
| LPDDR3       | 122       | 1.98%   |
| DDR          | 61        | 0.99%   |
| DDR5         | 44        | 0.71%   |
| DRAM         | 25        | 0.4%    |
| LPDDR5       | 8         | 0.13%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3490      | 56.91%  |
| DIMM         | 2319      | 37.81%  |
| Row Of Chips | 224       | 3.65%   |
| Unknown      | 55        | 0.9%    |
| Chip         | 28        | 0.46%   |
| FB-DIMM      | 9         | 0.15%   |
| RIMM         | 8         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 2141      | 32.16%  |
| 4096    | 1540      | 23.13%  |
| 2048    | 993       | 14.91%  |
| 16384   | 896       | 13.46%  |
| 1024    | 651       | 9.78%   |
| 32768   | 328       | 4.93%   |
| 512     | 69        | 1.04%   |
| 256     | 18        | 0.27%   |
| 65536   | 11        | 0.17%   |
| 131072  | 2         | 0.03%   |
| 12288   | 2         | 0.03%   |
| 8072    | 1         | 0.02%   |
| 3072    | 1         | 0.02%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| 16      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1295      | 19.54%  |
| 3200    | 1031      | 15.56%  |
| 2667    | 832       | 12.56%  |
| 800     | 491       | 7.41%   |
| 1333    | 444       | 6.7%    |
| 2400    | 434       | 6.55%   |
| 2133    | 284       | 4.29%   |
| 667     | 220       | 3.32%   |
| Unknown | 186       | 2.81%   |
| 3600    | 178       | 2.69%   |
| 1334    | 113       | 1.71%   |
| 1867    | 92        | 1.39%   |
| 1866    | 90        | 1.36%   |
| 1067    | 79        | 1.19%   |
| 1066    | 65        | 0.98%   |
| 2666    | 56        | 0.85%   |
| 4267    | 50        | 0.75%   |
| 3733    | 47        | 0.71%   |
| 3266    | 45        | 0.68%   |
| 2933    | 37        | 0.56%   |
| 4800    | 36        | 0.54%   |
| 3000    | 36        | 0.54%   |
| 4199    | 34        | 0.51%   |
| 533     | 32        | 0.48%   |
| 1800    | 31        | 0.47%   |
| 8400    | 30        | 0.45%   |
| 3400    | 28        | 0.42%   |
| 3800    | 27        | 0.41%   |
| 3466    | 26        | 0.39%   |
| 2048    | 23        | 0.35%   |
| 4000    | 22        | 0.33%   |
| 400     | 18        | 0.27%   |
| 3933    | 13        | 0.2%    |
| 333     | 13        | 0.2%    |
| 6400    | 12        | 0.18%   |
| 1639    | 11        | 0.17%   |
| 266     | 11        | 0.17%   |
| 4266    | 9         | 0.14%   |
| 3100    | 9         | 0.14%   |
| 975     | 9         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 49        | 33.56%  |
| Brother Industries     | 26        | 17.81%  |
| Canon                  | 19        | 13.01%  |
| Samsung Electronics    | 11        | 7.53%   |
| Xerox                  | 8         | 5.48%   |
| Seiko Epson            | 8         | 5.48%   |
| Dymo-CoStar            | 4         | 2.74%   |
| Prolific Technology    | 3         | 2.05%   |
| Lexmark International  | 3         | 2.05%   |
| Zebra                  | 2         | 1.37%   |
| Pantum                 | 2         | 1.37%   |
| STMicroelectronics     | 1         | 0.68%   |
| Ricoh                  | 1         | 0.68%   |
| QinHeng Electronics    | 1         | 0.68%   |
| Printer                | 1         | 0.68%   |
| Panasonic (Matsushita) | 1         | 0.68%   |
| Oki Data               | 1         | 0.68%   |
| Kyocera                | 1         | 0.68%   |
| Konica Minolta         | 1         | 0.68%   |
| GODEX INTERNATIONAL    | 1         | 0.68%   |
| Custom Engineering SPA | 1         | 0.68%   |
| Apple                  | 1         | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 4.79%   |
| HP LaserJet 1200                                                      | 5         | 3.42%   |
| Samsung ML-1660 Series                                                | 3         | 2.05%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.05%   |
| HP LaserJet P1005                                                     | 3         | 2.05%   |
| HP LaserJet 1020                                                      | 3         | 2.05%   |
| HP HP LaserJet M101-M106                                              | 3         | 2.05%   |
| Canon PIXMA MG3600 Series                                             | 3         | 2.05%   |
| HP LaserJet 1150                                                      | 2         | 1.37%   |
| HP ENVY 4520 series                                                   | 2         | 1.37%   |
| HP DeskJet 2700 series                                                | 2         | 1.37%   |
| HP DeskJet 2600 series                                                | 2         | 1.37%   |
| HP DeskJet 2130 series                                                | 2         | 1.37%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.37%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.37%   |
| Canon MF4410                                                          | 2         | 1.37%   |
| Canon LiDE 400                                                        | 2         | 1.37%   |
| Canon LiDE 300                                                        | 2         | 1.37%   |
| Canon G3010 series                                                    | 2         | 1.37%   |
| Brother PT-9500PC                                                     | 2         | 1.37%   |
| Brother MFC-7460DN                                                    | 2         | 1.37%   |
| Brother HL-L2395DW series                                             | 2         | 1.37%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.68%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.68%   |
| Xerox Phaser 3250                                                     | 1         | 0.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.68%   |
| Seiko Epson Printer                                                   | 1         | 0.68%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.68%   |
| Seiko Epson M105 Series                                               | 1         | 0.68%   |
| Seiko Epson L120 Series                                               | 1         | 0.68%   |
| Seiko Epson ET-2850 Series                                            | 1         | 0.68%   |
| Seiko Epson ET-2710 Series                                            | 1         | 0.68%   |
| Seiko Epson ET-2700 Series                                            | 1         | 0.68%   |
| Seiko Epson EPSON XP-205 207 Series                                   | 1         | 0.68%   |
| Samsung SCX-4x26 Series                                               | 1         | 0.68%   |
| Samsung SCX-472x Series                                               | 1         | 0.68%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.68%   |
| Samsung SCX-3200 Series                                               | 1         | 0.68%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.68%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 22        | 61.11%  |
| Seiko Epson     | 7         | 19.44%  |
| Hewlett-Packard | 3         | 8.33%   |
| Mustek Systems  | 2         | 5.56%   |
| AGFA-Gevaert NV | 2         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 6         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 4         | 11.11%  |
| Canon CanoScan LiDE 210                                       | 3         | 8.33%   |
| Canon CanoScan LiDE 120                                       | 2         | 5.56%   |
| Canon CanoScan LiDE 110                                       | 2         | 5.56%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 5.56%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 2.78%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 2.78%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 2.78%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 2.78%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 2.78%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 2.78%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 2.78%   |
| Mustek Systems SNAPSCAN e22                                   | 1         | 2.78%   |
| Mustek Systems BearPaw 2400 CU Plus                           | 1         | 2.78%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 2.78%   |
| HP ScanJet 3970c                                              | 1         | 2.78%   |
| HP HP Scanjet 300                                             | 1         | 2.78%   |
| Canon CanoScan LiDE 60                                        | 1         | 2.78%   |
| Canon CanoScan LIDE 25                                        | 1         | 2.78%   |
| Canon CanoScan 8800F                                          | 1         | 2.78%   |
| Canon CanoScan 5600F                                          | 1         | 2.78%   |
| Canon CanoScan 4400F                                          | 1         | 2.78%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 766       | 22.52%  |
| Bison Electronics                      | 382       | 11.23%  |
| IMC Networks                           | 299       | 8.79%   |
| Quanta                                 | 250       | 7.35%   |
| Microdia                               | 236       | 6.94%   |
| Realtek Semiconductor                  | 208       | 6.11%   |
| Logitech                               | 200       | 5.88%   |
| Sunplus Innovation Technology          | 149       | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 100       | 2.94%   |
| Apple                                  | 97        | 2.85%   |
| Suyin                                  | 83        | 2.44%   |
| Lite-On Technology                     | 72        | 2.12%   |
| Syntek                                 | 61        | 1.79%   |
| Luxvisions Innotech Limited            | 61        | 1.79%   |
| Silicon Motion                         | 30        | 0.88%   |
| Alcor Micro                            | 28        | 0.82%   |
| Lenovo                                 | 24        | 0.71%   |
| Generalplus Technology                 | 23        | 0.68%   |
| Microsoft                              | 22        | 0.65%   |
| Acer                                   | 22        | 0.65%   |
| Z-Star Microelectronics                | 17        | 0.5%    |
| Samsung Electronics                    | 16        | 0.47%   |
| Sonix Technology                       | 15        | 0.44%   |
| Ricoh                                  | 14        | 0.41%   |
| Creative Technology                    | 13        | 0.38%   |
| Jieli Technology                       | 12        | 0.35%   |
| Primax Electronics                     | 11        | 0.32%   |
| ARC International                      | 11        | 0.32%   |
| SunplusIT                              | 10        | 0.29%   |
| Importek                               | 10        | 0.29%   |
| Genesys Logic                          | 9         | 0.26%   |
| GEMBIRD                                | 9         | 0.26%   |
| KYE Systems (Mouse Systems)            | 8         | 0.24%   |
| MacroSilicon                           | 6         | 0.18%   |
| icSpring                               | 6         | 0.18%   |
| ALi                                    | 6         | 0.18%   |
| Unknown                                | 6         | 0.18%   |
| Y Media                                | 5         | 0.15%   |
| OmniVision Technologies                | 5         | 0.15%   |
| Intel                                  | 5         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 222       | 6.42%   |
| Bison Integrated Camera                             | 140       | 4.05%   |
| Microdia Integrated_Webcam_HD                       | 108       | 3.12%   |
| IMC Networks Integrated Camera                      | 95        | 2.75%   |
| Bison Integrated 5M Camera                          | 73        | 2.11%   |
| Realtek Integrated_Webcam_HD                        | 72        | 2.08%   |
| Quanta Chromebook HD Camera                         | 69        | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 66        | 1.91%   |
| Logitech Webcam C270                                | 59        | 1.71%   |
| Chicony HD Webcam                                   | 59        | 1.71%   |
| Bison BisonCam, NB Pro                              | 52        | 1.5%    |
| Chicony Integrated 5M Camera                        | 43        | 1.24%   |
| Sunplus Integrated_Webcam_HD                        | 41        | 1.18%   |
| Chicony HP HD Camera                                | 38        | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                        | 37        | 1.07%   |
| Apple Built-in iSight                               | 36        | 1.04%   |
| Quanta HD User Facing                               | 34        | 0.98%   |
| Quanta HP TrueVision HD Camera                      | 32        | 0.92%   |
| Syntek Integrated Camera                            | 31        | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 30        | 0.87%   |
| Quanta VGA WebCam                                   | 26        | 0.75%   |
| Microdia Integrated Webcam                          | 24        | 0.69%   |
| Logitech HD Pro Webcam C920                         | 24        | 0.69%   |
| Lite-On Integrated Camera                           | 24        | 0.69%   |
| Bison SunplusIT Integrated Camera                   | 24        | 0.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 24        | 0.69%   |
| Quanta HP HD Camera                                 | 23        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 23        | 0.66%   |
| Lite-On HP HD Camera                                | 22        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)             | 21        | 0.61%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.61%   |
| Apple FaceTime HD Camera (Built-in)                 | 21        | 0.61%   |
| Realtek USB Camera                                  | 20        | 0.58%   |
| Bison Lenovo Integrated Webcam                      | 20        | 0.58%   |
| Bison Lenovo EasyCamera                             | 20        | 0.58%   |
| Sunplus HD WebCam                                   | 18        | 0.52%   |
| Luxvisions Innotech Limited HP HD Camera            | 17        | 0.49%   |
| Logitech C922 Pro Stream Webcam                     | 17        | 0.49%   |
| Chicony HD User Facing                              | 17        | 0.49%   |
| Samsung Galaxy series, misc. (MTP mode)             | 16        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 305       | 43.57%  |
| Validity Sensors                   | 197       | 28.14%  |
| Shenzhen Goodix Technology         | 73        | 10.43%  |
| AuthenTec                          | 33        | 4.71%   |
| Upek                               | 31        | 4.43%   |
| Elan Microelectronics              | 28        | 4%      |
| LighTuning Technology              | 20        | 2.86%   |
| STMicroelectronics                 | 10        | 1.43%   |
| Samsung Electronics                | 1         | 0.14%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.14%   |
| Focal-systems.Corp                 | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 184       | 26.29%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 6%      |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 5.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 4.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 29        | 4.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 4%      |
| Validity Sensors Synaptics WBDI                                            | 23        | 3.29%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 2.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 2.43%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.14%   |
| Elan ELAN:Fingerprint                                                      | 15        | 2.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 2%      |
| Elan ELAN:ARM-M4                                                           | 13        | 1.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 1.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 1.57%   |
| Validity Sensors VFS491                                                    | 10        | 1.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.14%   |
| Synaptics  WBDI                                                            | 8         | 1.14%   |
| Synaptics Prometheus Fingerprint Reader                                    | 8         | 1.14%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.14%   |
| AuthenTec AES2810                                                          | 8         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1%      |
| Validity Sensors Fingerprint scanner                                       | 7         | 1%      |
| Synaptics WBDI                                                             | 7         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.86%   |
| Synaptics UWP WBDI                                                         | 6         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.57%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.43%   |
| AuthenTec AES1600                                                          | 3         | 0.43%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 119       | 36.62%  |
| Alcor Micro               | 104       | 32%     |
| Upek                      | 26        | 8%      |
| O2 Micro                  | 25        | 7.69%   |
| Lenovo                    | 19        | 5.85%   |
| Gemalto (was Gemplus)     | 6         | 1.85%   |
| SCM Microsystems          | 5         | 1.54%   |
| Yubico.com                | 3         | 0.92%   |
| Advanced Card Systems     | 3         | 0.92%   |
| Reiner SCT Kartensysteme  | 2         | 0.62%   |
| Clay Logic                | 2         | 0.62%   |
| Cherry                    | 2         | 0.62%   |
| C3PO                      | 2         | 0.62%   |
| Aladdin Knowledge Systems | 2         | 0.62%   |
| Realtek Semiconductor     | 1         | 0.31%   |
| OmniKey                   | 1         | 0.31%   |
| Feitian Technologies      | 1         | 0.31%   |
| CREATOR                   | 1         | 0.31%   |
| Chicony Electronics       | 1         | 0.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 102       | 31.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 10.46%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 8%      |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 24        | 7.38%   |
| Broadcom 5880                                                                | 24        | 7.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 6.77%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 6.46%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.54%   |
| Broadcom 58200                                                               | 13        | 4%      |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.62%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.62%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.62%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.62%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.62%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.62%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.62%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.31%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.31%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.31%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.31%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.31%   |
| OmniKey CardMan 4321                                                         | 1         | 0.31%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.31%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.31%   |
| Feitian Technologies SCR301                                                  | 1         | 0.31%   |
| CREATOR CRT-603(CZ1) CCR                                                     | 1         | 0.31%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.31%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.31%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.31%   |
| C3PO LTC31v2                                                                 | 1         | 0.31%   |
| C3PO KBR36                                                                   | 1         | 0.31%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.31%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4244      | 57.73%  |
| 1     | 2474      | 33.65%  |
| 2     | 497       | 6.76%   |
| 3     | 111       | 1.51%   |
| 4     | 19        | 0.26%   |
| 5     | 5         | 0.07%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1642      | 44.34%  |
| Fingerprint reader       | 697       | 18.82%  |
| Net/wireless             | 333       | 8.99%   |
| Chipcard                 | 294       | 7.94%   |
| Multimedia controller    | 240       | 6.48%   |
| Communication controller | 153       | 4.13%   |
| Unassigned class         | 98        | 2.65%   |
| Bluetooth                | 52        | 1.4%    |
| Sound                    | 37        | 1%      |
| Camera                   | 34        | 0.92%   |
| Card reader              | 31        | 0.84%   |
| Storage                  | 27        | 0.73%   |
| Net/ethernet             | 21        | 0.57%   |
| Network                  | 10        | 0.27%   |
| Modem                    | 8         | 0.22%   |
| Storage/raid             | 7         | 0.19%   |
| Flash memory             | 6         | 0.16%   |
| Tv card                  | 5         | 0.14%   |
| Dvb card                 | 4         | 0.11%   |
| Firewire controller      | 2         | 0.05%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

