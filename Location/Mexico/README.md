Linux in Mexico - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Mexico/Desktop/README.md) and [notebooks](/Location/Mexico/Notebook/README.md).

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

Total: 4099

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T400 6474AV5       | Notebook    | [b98f0a2c09](https://linux-hardware.org/?probe=b98f0a2c09) | Dec 24, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [224ca602f3](https://linux-hardware.org/?probe=224ca602f3) | Dec 24, 2023 |
| Gateway       | NV59C                       | Notebook    | [1537866140](https://linux-hardware.org/?probe=1537866140) | Dec 23, 2023 |
| Unknown       | W1415A                      | Notebook    | [f1fbd72c23](https://linux-hardware.org/?probe=f1fbd72c23) | Dec 23, 2023 |
| Gateway       | NV59C                       | Notebook    | [62d62c0a3b](https://linux-hardware.org/?probe=62d62c0a3b) | Dec 22, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [119a1632aa](https://linux-hardware.org/?probe=119a1632aa) | Dec 21, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [64131ee7e0](https://linux-hardware.org/?probe=64131ee7e0) | Dec 21, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Dell          | G7 7700                     | Notebook    | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| HP            | 1905                        | Desktop     | [540abb14df](https://linux-hardware.org/?probe=540abb14df) | Dec 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ca0eab5d48](https://linux-hardware.org/?probe=ca0eab5d48) | Dec 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [38ac246006](https://linux-hardware.org/?probe=38ac246006) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [7aa351f4c3](https://linux-hardware.org/?probe=7aa351f4c3) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [9ed9ded2ea](https://linux-hardware.org/?probe=9ed9ded2ea) | Dec 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [19af9254cb](https://linux-hardware.org/?probe=19af9254cb) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [5881287b44](https://linux-hardware.org/?probe=5881287b44) | Dec 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7383998676](https://linux-hardware.org/?probe=7383998676) | Dec 18, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0526a42f4](https://linux-hardware.org/?probe=b0526a42f4) | Dec 18, 2023 |
| HP            | Compaq CQ45                 | Notebook    | [2d0f39803d](https://linux-hardware.org/?probe=2d0f39803d) | Dec 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [39c5fad7d0](https://linux-hardware.org/?probe=39c5fad7d0) | Dec 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d3ff600405](https://linux-hardware.org/?probe=d3ff600405) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| HP            | G60                         | Notebook    | [9fabfc936c](https://linux-hardware.org/?probe=9fabfc936c) | Dec 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| ASUSTek       | Q304UAK                     | Convertible | [7c98d7ffe7](https://linux-hardware.org/?probe=7c98d7ffe7) | Dec 11, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | Desktop     | [1381c72872](https://linux-hardware.org/?probe=1381c72872) | Dec 11, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [67a35f1dd7](https://linux-hardware.org/?probe=67a35f1dd7) | Dec 10, 2023 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58 7359AW5     | Desktop     | [71d7e25b16](https://linux-hardware.org/?probe=71d7e25b16) | Dec 09, 2023 |
| Dell          | Latitude 3480               | Notebook    | [ee6070cfbe](https://linux-hardware.org/?probe=ee6070cfbe) | Dec 09, 2023 |
| HP            | Compaq 6720s                | Notebook    | [63200c945b](https://linux-hardware.org/?probe=63200c945b) | Dec 08, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [44e608daff](https://linux-hardware.org/?probe=44e608daff) | Dec 08, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [c0b0f86403](https://linux-hardware.org/?probe=c0b0f86403) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [9c8600990d](https://linux-hardware.org/?probe=9c8600990d) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [bbb500139e](https://linux-hardware.org/?probe=bbb500139e) | Dec 07, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [9b36560b08](https://linux-hardware.org/?probe=9b36560b08) | Dec 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [747cf33a22](https://linux-hardware.org/?probe=747cf33a22) | Dec 06, 2023 |
| HP            | ENVY Notebook               | Notebook    | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| HP            | 8054                        | Desktop     | [d5e57e23bb](https://linux-hardware.org/?probe=d5e57e23bb) | Dec 06, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [de505ab1fd](https://linux-hardware.org/?probe=de505ab1fd) | Dec 05, 2023 |
| NEC Infron... | MS-9888 10h                 | Desktop     | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [dbec4c564e](https://linux-hardware.org/?probe=dbec4c564e) | Dec 05, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b4efc55410](https://linux-hardware.org/?probe=b4efc55410) | Dec 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [2a17ca7efe](https://linux-hardware.org/?probe=2a17ca7efe) | Dec 05, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [0c467a2af3](https://linux-hardware.org/?probe=0c467a2af3) | Dec 04, 2023 |
| HP            | Laptop 17t-cn200            | Notebook    | [26c356c486](https://linux-hardware.org/?probe=26c356c486) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | Bantry CRB SDK0E50515 ST... | Desktop     | [09d4a641d9](https://linux-hardware.org/?probe=09d4a641d9) | Dec 04, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [f4078eb310](https://linux-hardware.org/?probe=f4078eb310) | Dec 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [2a30f0332a](https://linux-hardware.org/?probe=2a30f0332a) | Dec 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [689f0d6876](https://linux-hardware.org/?probe=689f0d6876) | Dec 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b6ccfe856f](https://linux-hardware.org/?probe=b6ccfe856f) | Dec 03, 2023 |
| Gateway       | M-6812M                     | Notebook    | [008f6448dc](https://linux-hardware.org/?probe=008f6448dc) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [54f08c139f](https://linux-hardware.org/?probe=54f08c139f) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6aff076a55](https://linux-hardware.org/?probe=6aff076a55) | Dec 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [dcde3a9390](https://linux-hardware.org/?probe=dcde3a9390) | Dec 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [a12db959e6](https://linux-hardware.org/?probe=a12db959e6) | Nov 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [f83ad2bb01](https://linux-hardware.org/?probe=f83ad2bb01) | Nov 30, 2023 |
| Dell          | Latitude E6420              | Notebook    | [12b36e0bb9](https://linux-hardware.org/?probe=12b36e0bb9) | Nov 30, 2023 |
| PC Special... | Recoil 16                   | Notebook    | [3dd3569b17](https://linux-hardware.org/?probe=3dd3569b17) | Nov 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [6965a13f84](https://linux-hardware.org/?probe=6965a13f84) | Nov 29, 2023 |
| HP            | 859B                        | Desktop     | [fd70c499d1](https://linux-hardware.org/?probe=fd70c499d1) | Nov 28, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [dd98dacf94](https://linux-hardware.org/?probe=dd98dacf94) | Nov 28, 2023 |
| HP            | 245 G4 Notebook PC          | Notebook    | [ef0bb61d83](https://linux-hardware.org/?probe=ef0bb61d83) | Nov 27, 2023 |
| HP            | 245 G4 Notebook PC          | Notebook    | [4a48fe8985](https://linux-hardware.org/?probe=4a48fe8985) | Nov 27, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [54e171f5dc](https://linux-hardware.org/?probe=54e171f5dc) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [c3c18efc38](https://linux-hardware.org/?probe=c3c18efc38) | Nov 27, 2023 |
| HP            | G42                         | Notebook    | [b53c2fe1be](https://linux-hardware.org/?probe=b53c2fe1be) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [33d8baae78](https://linux-hardware.org/?probe=33d8baae78) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [beca2cade6](https://linux-hardware.org/?probe=beca2cade6) | Nov 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [c68a8b3cc0](https://linux-hardware.org/?probe=c68a8b3cc0) | Nov 25, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e17bdfe79f](https://linux-hardware.org/?probe=e17bdfe79f) | Nov 25, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [5cbdf33238](https://linux-hardware.org/?probe=5cbdf33238) | Nov 25, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ea0a7aa615](https://linux-hardware.org/?probe=ea0a7aa615) | Nov 24, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [432ec62dd0](https://linux-hardware.org/?probe=432ec62dd0) | Nov 24, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [85f5270891](https://linux-hardware.org/?probe=85f5270891) | Nov 23, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [8b107cb438](https://linux-hardware.org/?probe=8b107cb438) | Nov 23, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [c5d9332805](https://linux-hardware.org/?probe=c5d9332805) | Nov 23, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [5317e6d4a5](https://linux-hardware.org/?probe=5317e6d4a5) | Nov 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [522acd0620](https://linux-hardware.org/?probe=522acd0620) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6b88b81e69](https://linux-hardware.org/?probe=6b88b81e69) | Nov 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f90c57452a](https://linux-hardware.org/?probe=f90c57452a) | Nov 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928f91a2f4](https://linux-hardware.org/?probe=928f91a2f4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [508c867ae8](https://linux-hardware.org/?probe=508c867ae8) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [7273b32790](https://linux-hardware.org/?probe=7273b32790) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [dc2ca2e65b](https://linux-hardware.org/?probe=dc2ca2e65b) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e5d2cc7fcd](https://linux-hardware.org/?probe=e5d2cc7fcd) | Nov 19, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [281c4b4ac5](https://linux-hardware.org/?probe=281c4b4ac5) | Nov 18, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [cc1ff7f9a8](https://linux-hardware.org/?probe=cc1ff7f9a8) | Nov 18, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [c526bb7fac](https://linux-hardware.org/?probe=c526bb7fac) | Nov 17, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [ea21fd1e60](https://linux-hardware.org/?probe=ea21fd1e60) | Nov 17, 2023 |
| Dell          | Latitude 5520               | Notebook    | [234733a1e4](https://linux-hardware.org/?probe=234733a1e4) | Nov 17, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [93616a8cb1](https://linux-hardware.org/?probe=93616a8cb1) | Nov 17, 2023 |
| Dell          | System XPS L502X            | Notebook    | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [3e6ad056d6](https://linux-hardware.org/?probe=3e6ad056d6) | Nov 16, 2023 |
| Dell          | Precision 7520              | Notebook    | [f004d80157](https://linux-hardware.org/?probe=f004d80157) | Nov 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [496e69e1e4](https://linux-hardware.org/?probe=496e69e1e4) | Nov 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [03c6bfd1ee](https://linux-hardware.org/?probe=03c6bfd1ee) | Nov 15, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [41ae79ffa6](https://linux-hardware.org/?probe=41ae79ffa6) | Nov 15, 2023 |
| HP            | 1408h                       | Desktop     | [b39e21e12c](https://linux-hardware.org/?probe=b39e21e12c) | Nov 15, 2023 |
| HP            | 1408h                       | Desktop     | [0eafe0e468](https://linux-hardware.org/?probe=0eafe0e468) | Nov 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [870fedf2eb](https://linux-hardware.org/?probe=870fedf2eb) | Nov 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c5f890cb08](https://linux-hardware.org/?probe=c5f890cb08) | Nov 14, 2023 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [c505d16c82](https://linux-hardware.org/?probe=c505d16c82) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [e0349fcb14](https://linux-hardware.org/?probe=e0349fcb14) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [f7a8d7d27e](https://linux-hardware.org/?probe=f7a8d7d27e) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [149bf90d88](https://linux-hardware.org/?probe=149bf90d88) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [1b4972f4e1](https://linux-hardware.org/?probe=1b4972f4e1) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [7d0e39fe9f](https://linux-hardware.org/?probe=7d0e39fe9f) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [243bc51d12](https://linux-hardware.org/?probe=243bc51d12) | Nov 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| Lenovo        | 3744 WIN SDK0T76466 3424... | All in one  | [765a9d56c1](https://linux-hardware.org/?probe=765a9d56c1) | Nov 12, 2023 |
| HP            | 09F0h                       | Desktop     | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [798841e126](https://linux-hardware.org/?probe=798841e126) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| AZW           | GTR V21                     | Desktop     | [8c7e39a466](https://linux-hardware.org/?probe=8c7e39a466) | Nov 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f6282ce11](https://linux-hardware.org/?probe=1f6282ce11) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e086a0153d](https://linux-hardware.org/?probe=e086a0153d) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d49ee32dd4](https://linux-hardware.org/?probe=d49ee32dd4) | Nov 11, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [0c76c82295](https://linux-hardware.org/?probe=0c76c82295) | Nov 11, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [cb0ff23750](https://linux-hardware.org/?probe=cb0ff23750) | Nov 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [164a2ae911](https://linux-hardware.org/?probe=164a2ae911) | Nov 10, 2023 |
| Dell          | 0TKD84 A02                  | Server      | [accebd9648](https://linux-hardware.org/?probe=accebd9648) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [71b28a2547](https://linux-hardware.org/?probe=71b28a2547) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c2d982c2dd](https://linux-hardware.org/?probe=c2d982c2dd) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [89417204e0](https://linux-hardware.org/?probe=89417204e0) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [4af4346c2a](https://linux-hardware.org/?probe=4af4346c2a) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [745cc9650d](https://linux-hardware.org/?probe=745cc9650d) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [7a1de78213](https://linux-hardware.org/?probe=7a1de78213) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [57fb2a4f18](https://linux-hardware.org/?probe=57fb2a4f18) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | Notebook    | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [1bf5a3e96c](https://linux-hardware.org/?probe=1bf5a3e96c) | Nov 08, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [4c2f5a3ff8](https://linux-hardware.org/?probe=4c2f5a3ff8) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b3df6b76e8](https://linux-hardware.org/?probe=b3df6b76e8) | Nov 08, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [9fd8344477](https://linux-hardware.org/?probe=9fd8344477) | Nov 07, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| HP            | 8184 X4                     | Desktop     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| American M... | A6                          | Notebook    | [4ff43d7d31](https://linux-hardware.org/?probe=4ff43d7d31) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| Alienware     | 14                          | Notebook    | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [de8e05d9e3](https://linux-hardware.org/?probe=de8e05d9e3) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [4c2cc71fc2](https://linux-hardware.org/?probe=4c2cc71fc2) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [d7b08bbbab](https://linux-hardware.org/?probe=d7b08bbbab) | Nov 01, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [90e266bd8e](https://linux-hardware.org/?probe=90e266bd8e) | Oct 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17f4f01635](https://linux-hardware.org/?probe=17f4f01635) | Oct 30, 2023 |
| Lenovo        | B40-45 20394                | Notebook    | [ef45bdcea9](https://linux-hardware.org/?probe=ef45bdcea9) | Oct 28, 2023 |
| HP            | 6360t                       | Notebook    | [d0f94e770b](https://linux-hardware.org/?probe=d0f94e770b) | Oct 28, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [607a31a8ef](https://linux-hardware.org/?probe=607a31a8ef) | Oct 27, 2023 |
| Dell          | Inspiron 3451               | Notebook    | [2c1267e536](https://linux-hardware.org/?probe=2c1267e536) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| HP            | 2B0A                        | All in one  | [e60260d9b2](https://linux-hardware.org/?probe=e60260d9b2) | Oct 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [b0175e5f47](https://linux-hardware.org/?probe=b0175e5f47) | Oct 26, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [cf4098d73b](https://linux-hardware.org/?probe=cf4098d73b) | Oct 26, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [3273bde56c](https://linux-hardware.org/?probe=3273bde56c) | Oct 25, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [f2ac570d7b](https://linux-hardware.org/?probe=f2ac570d7b) | Oct 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | Notebook    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5936f87a0e](https://linux-hardware.org/?probe=5936f87a0e) | Oct 23, 2023 |
| HP            | 83EF                        | Desktop     | [9a8026df67](https://linux-hardware.org/?probe=9a8026df67) | Oct 23, 2023 |
| Acer          | Aspire R3-431T              | Notebook    | [eb6c623c2d](https://linux-hardware.org/?probe=eb6c623c2d) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| AZW           | SER V1                      | Desktop     | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fde726622c](https://linux-hardware.org/?probe=fde726622c) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [116946c81c](https://linux-hardware.org/?probe=116946c81c) | Oct 22, 2023 |
| HP            | Notebook                    | Notebook    | [e8c7b38b1b](https://linux-hardware.org/?probe=e8c7b38b1b) | Oct 21, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [1303e88b7c](https://linux-hardware.org/?probe=1303e88b7c) | Oct 21, 2023 |
| Biostar       | B450MH                      | Desktop     | [cc72642215](https://linux-hardware.org/?probe=cc72642215) | Oct 20, 2023 |
| Google        | Pirika                      | Notebook    | [98eea3bc0f](https://linux-hardware.org/?probe=98eea3bc0f) | Oct 20, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [8e1cb99809](https://linux-hardware.org/?probe=8e1cb99809) | Oct 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [a80cd678f2](https://linux-hardware.org/?probe=a80cd678f2) | Oct 18, 2023 |
| Dell          | G7 7790                     | Notebook    | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| HP            | 2B29                        | Desktop     | [70d4194832](https://linux-hardware.org/?probe=70d4194832) | Oct 18, 2023 |
| HP            | 2B29                        | Desktop     | [b4da4bf11d](https://linux-hardware.org/?probe=b4da4bf11d) | Oct 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [501f7abc3b](https://linux-hardware.org/?probe=501f7abc3b) | Oct 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4593a22b63](https://linux-hardware.org/?probe=4593a22b63) | Oct 18, 2023 |
| AZW           | SER V1                      | Desktop     | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| Google        | Treeya                      | Notebook    | [1cf43225f5](https://linux-hardware.org/?probe=1cf43225f5) | Oct 17, 2023 |
| Google        | Treeya                      | Notebook    | [6f05b84b18](https://linux-hardware.org/?probe=6f05b84b18) | Oct 17, 2023 |
| Unknown       | Intel X79                   | Desktop     | [d2553e6cbd](https://linux-hardware.org/?probe=d2553e6cbd) | Oct 17, 2023 |
| HP            | 630                         | Notebook    | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [172cfdcd26](https://linux-hardware.org/?probe=172cfdcd26) | Oct 16, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| HP            | 339A                        | Desktop     | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [c50573f4ae](https://linux-hardware.org/?probe=c50573f4ae) | Oct 14, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [df4a5a4722](https://linux-hardware.org/?probe=df4a5a4722) | Oct 14, 2023 |
| Dell          | Inspiron 1318               | Notebook    | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| Timi          | RedmiBook 13 R              | Notebook    | [a39c380c4f](https://linux-hardware.org/?probe=a39c380c4f) | Oct 13, 2023 |
| Sony          | VPCEB15EL                   | Notebook    | [f7a3de3793](https://linux-hardware.org/?probe=f7a3de3793) | Oct 13, 2023 |
| HP            | 8714                        | Desktop     | [1379aae868](https://linux-hardware.org/?probe=1379aae868) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [fb51024b14](https://linux-hardware.org/?probe=fb51024b14) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [365f77219e](https://linux-hardware.org/?probe=365f77219e) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d582dc334c](https://linux-hardware.org/?probe=d582dc334c) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [904d65b1c0](https://linux-hardware.org/?probe=904d65b1c0) | Oct 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [38a83d68e5](https://linux-hardware.org/?probe=38a83d68e5) | Oct 09, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [d97f4b5e6f](https://linux-hardware.org/?probe=d97f4b5e6f) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [fd663ca7fa](https://linux-hardware.org/?probe=fd663ca7fa) | Oct 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [e1ff6e4124](https://linux-hardware.org/?probe=e1ff6e4124) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [83fd464aa8](https://linux-hardware.org/?probe=83fd464aa8) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [035c4dbf68](https://linux-hardware.org/?probe=035c4dbf68) | Oct 08, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [d2fc1d1762](https://linux-hardware.org/?probe=d2fc1d1762) | Oct 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [6bc395bbda](https://linux-hardware.org/?probe=6bc395bbda) | Oct 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2d73d7e286](https://linux-hardware.org/?probe=2d73d7e286) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| Thomson       | WWN15I5-8BK1T               | Notebook    | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| Pegatron      | Benicia                     | Desktop     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d54872fa1](https://linux-hardware.org/?probe=9d54872fa1) | Oct 05, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [ad0cc18353](https://linux-hardware.org/?probe=ad0cc18353) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ef041058aa](https://linux-hardware.org/?probe=ef041058aa) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [75be134738](https://linux-hardware.org/?probe=75be134738) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [1c789caaec](https://linux-hardware.org/?probe=1c789caaec) | Oct 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d2e42707c6](https://linux-hardware.org/?probe=d2e42707c6) | Oct 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| PCChips       | A51G                        | Desktop     | [307e9880cb](https://linux-hardware.org/?probe=307e9880cb) | Oct 03, 2023 |
| PCChips       | A51G                        | Desktop     | [da68aae4b8](https://linux-hardware.org/?probe=da68aae4b8) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cacc534be7](https://linux-hardware.org/?probe=cacc534be7) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7eebcdc80b](https://linux-hardware.org/?probe=7eebcdc80b) | Oct 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Pegatron      | Benicia                     | Desktop     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | Notebook    | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| HP            | Pavilion 14                 | Notebook    | [a7589d8c93](https://linux-hardware.org/?probe=a7589d8c93) | Sep 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [1aed6aba04](https://linux-hardware.org/?probe=1aed6aba04) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | Notebook    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [2af47d0dca](https://linux-hardware.org/?probe=2af47d0dca) | Sep 24, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | Notebook    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [312172129f](https://linux-hardware.org/?probe=312172129f) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [026e1e3391](https://linux-hardware.org/?probe=026e1e3391) | Sep 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [bdb084e4a8](https://linux-hardware.org/?probe=bdb084e4a8) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| HP            | ProBook 6475b               | Notebook    | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| ECS           | VX900-I                     | Desktop     | [0a69c91f6b](https://linux-hardware.org/?probe=0a69c91f6b) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [adbe2f1ead](https://linux-hardware.org/?probe=adbe2f1ead) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Dell          | Latitude 9330               | Convertible | [622af30925](https://linux-hardware.org/?probe=622af30925) | Sep 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c424e240c8](https://linux-hardware.org/?probe=c424e240c8) | Sep 15, 2023 |
| Gigabyte      | A55M-DS2                    | Desktop     | [6bc7d0b74c](https://linux-hardware.org/?probe=6bc7d0b74c) | Sep 15, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | Notebook    | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [361c6cb056](https://linux-hardware.org/?probe=361c6cb056) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [6e387e015f](https://linux-hardware.org/?probe=6e387e015f) | Sep 13, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [4ff9edf944](https://linux-hardware.org/?probe=4ff9edf944) | Sep 12, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [26b3fd07ae](https://linux-hardware.org/?probe=26b3fd07ae) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c09c04e44a](https://linux-hardware.org/?probe=c09c04e44a) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [e763eb02b7](https://linux-hardware.org/?probe=e763eb02b7) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [26d87ed353](https://linux-hardware.org/?probe=26d87ed353) | Sep 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c5f5d76ac5](https://linux-hardware.org/?probe=c5f5d76ac5) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8a48280ff2](https://linux-hardware.org/?probe=8a48280ff2) | Sep 08, 2023 |
| Unknown       | W1415A                      | Notebook    | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Google        | Pirika                      | Notebook    | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4829899c3](https://linux-hardware.org/?probe=c4829899c3) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [54f48be7f6](https://linux-hardware.org/?probe=54f48be7f6) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Google        | Pirika                      | Notebook    | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | Notebook    | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| HP            | 240 G3                      | Notebook    | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [823a9c1693](https://linux-hardware.org/?probe=823a9c1693) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| HP            | 2215                        | Desktop     | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| HP            | 1587h                       | Desktop     | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| MSI           | Boston                      | Desktop     | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [1020c99eec](https://linux-hardware.org/?probe=1020c99eec) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [3032b93bc8](https://linux-hardware.org/?probe=3032b93bc8) | Aug 30, 2023 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [e38546c509](https://linux-hardware.org/?probe=e38546c509) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [f44b99ca67](https://linux-hardware.org/?probe=f44b99ca67) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [c3065668c8](https://linux-hardware.org/?probe=c3065668c8) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [3c4c019ee5](https://linux-hardware.org/?probe=3c4c019ee5) | Aug 28, 2023 |
| Google        | Treeya                      | Notebook    | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [89044ad89b](https://linux-hardware.org/?probe=89044ad89b) | Aug 28, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Dell          | 0HR330                      | Desktop     | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| Gateway       | ZX4800                      | All in one  | [8d9b55b788](https://linux-hardware.org/?probe=8d9b55b788) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [62a1cc3d3b](https://linux-hardware.org/?probe=62a1cc3d3b) | Aug 23, 2023 |
| Gateway       | ZX4800                      | All in one  | [ca5095843f](https://linux-hardware.org/?probe=ca5095843f) | Aug 23, 2023 |
| Google        | Pirika                      | Notebook    | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| GMKtec        | NucBox K2                   | Desktop     | [3cc85b0145](https://linux-hardware.org/?probe=3cc85b0145) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | Notebook    | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| HP            | 18E7                        | Desktop     | [49957c261d](https://linux-hardware.org/?probe=49957c261d) | Aug 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [455882ed8d](https://linux-hardware.org/?probe=455882ed8d) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Lenovo        | Rev B 82KU                  | Notebook    | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| Lenovo        | S10-3                       | Notebook    | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [de166e8654](https://linux-hardware.org/?probe=de166e8654) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2f8b7afb0](https://linux-hardware.org/?probe=b2f8b7afb0) | Aug 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [876d7e9992](https://linux-hardware.org/?probe=876d7e9992) | Aug 15, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0bd04d6cc0](https://linux-hardware.org/?probe=0bd04d6cc0) | Aug 15, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4fe6eb4d59](https://linux-hardware.org/?probe=4fe6eb4d59) | Aug 12, 2023 |
| HP            | 0A04h                       | Desktop     | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| HP            | 886C                        | Desktop     | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Toshiba       | Satellite L745D             | Notebook    | [9576dab2b0](https://linux-hardware.org/?probe=9576dab2b0) | Aug 09, 2023 |
| Lenovo        | 30C1                        | Desktop     | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Dell          | Precision 3551              | Notebook    | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | Notebook    | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0c8aef568d](https://linux-hardware.org/?probe=0c8aef568d) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [597f8ddaf2](https://linux-hardware.org/?probe=597f8ddaf2) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| INET          | Z12B                        | Mini pc     | [6acbb961c7](https://linux-hardware.org/?probe=6acbb961c7) | Aug 03, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [1a39b68c7f](https://linux-hardware.org/?probe=1a39b68c7f) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Anbernic      | Win600                      | Notebook    | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| Dell          | 0D8M0M A00                  | Desktop     | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| Dell          | 0RF705                      | Desktop     | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| Dell          | 0RF705                      | Desktop     | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8d3733b439](https://linux-hardware.org/?probe=8d3733b439) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [28bd5d7d66](https://linux-hardware.org/?probe=28bd5d7d66) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| HP            | 0A04h                       | Desktop     | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [01110b1f21](https://linux-hardware.org/?probe=01110b1f21) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| Biostar       | A68MDE                      | Desktop     | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Latitude E7450              | Notebook    | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [39ea43d323](https://linux-hardware.org/?probe=39ea43d323) | Jul 20, 2023 |
| HP            | 2B26 A01                    | All in one  | [41de8f48f0](https://linux-hardware.org/?probe=41de8f48f0) | Jul 20, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [666c1c0162](https://linux-hardware.org/?probe=666c1c0162) | Jul 18, 2023 |
| HP            | G42                         | Notebook    | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [2687ecdde1](https://linux-hardware.org/?probe=2687ecdde1) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| GPU Compan... | GWTC51427                   | Notebook    | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [a1334a7b0f](https://linux-hardware.org/?probe=a1334a7b0f) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [058522b2ca](https://linux-hardware.org/?probe=058522b2ca) | Jul 11, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b1b3d1eedc](https://linux-hardware.org/?probe=b1b3d1eedc) | Jul 10, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| Dell          | Precision M6700             | Notebook    | [ec5b230e37](https://linux-hardware.org/?probe=ec5b230e37) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | Desktop     | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [883185ea85](https://linux-hardware.org/?probe=883185ea85) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo        | C205                        | All in one  | [04e0a62210](https://linux-hardware.org/?probe=04e0a62210) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [663adbe947](https://linux-hardware.org/?probe=663adbe947) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | Desktop     | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [5e07b39a67](https://linux-hardware.org/?probe=5e07b39a67) | Jul 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| Lenovo        | Aptio CRB SDK0J40679 WIN... | Mini pc     | [40f510325d](https://linux-hardware.org/?probe=40f510325d) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| HP            | 550                         | Notebook    | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [c1181f8ae7](https://linux-hardware.org/?probe=c1181f8ae7) | Jul 01, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [031599c8b1](https://linux-hardware.org/?probe=031599c8b1) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Lenovo        | ThinkPad L430 246634S       | Notebook    | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | Notebook    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [683b7b2dc2](https://linux-hardware.org/?probe=683b7b2dc2) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [558a5b8a7f](https://linux-hardware.org/?probe=558a5b8a7f) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [fbb23975d9](https://linux-hardware.org/?probe=fbb23975d9) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [eea8b39580](https://linux-hardware.org/?probe=eea8b39580) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [696e42eaba](https://linux-hardware.org/?probe=696e42eaba) | Jun 20, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Gigabyte      | GA-E350N                    | Desktop     | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Dell          | Latitude 5531               | Notebook    | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| HP            | 2B3B                        | All in one  | [5e96206d26](https://linux-hardware.org/?probe=5e96206d26) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| HP            | G61                         | Notebook    | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | Latitude 5590               | Notebook    | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Gateway       | NE572                       | Notebook    | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4cf431ecc8](https://linux-hardware.org/?probe=4cf431ecc8) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2c5f9d83bd](https://linux-hardware.org/?probe=2c5f9d83bd) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | Desktop     | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lanix         | AL V9                       | Notebook    | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | Notebook    | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [f23e90acce](https://linux-hardware.org/?probe=f23e90acce) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | Notebook    | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [0518fce589](https://linux-hardware.org/?probe=0518fce589) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| HP            | 895C                        | Desktop     | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| HP            | 2B3B                        | All in one  | [7819836b92](https://linux-hardware.org/?probe=7819836b92) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [edfd6dd6d9](https://linux-hardware.org/?probe=edfd6dd6d9) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [43cf78743a](https://linux-hardware.org/?probe=43cf78743a) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | Notebook    | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| HP            | Pavilion dm4                | Notebook    | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| HP            | 2B3B                        | All in one  | [2ed92e9c21](https://linux-hardware.org/?probe=2ed92e9c21) | May 21, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2c9a1cd71](https://linux-hardware.org/?probe=b2c9a1cd71) | May 21, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | Notebook    | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [16ecd2d81d](https://linux-hardware.org/?probe=16ecd2d81d) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [dfb0b6c8f3](https://linux-hardware.org/?probe=dfb0b6c8f3) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | Notebook    | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [2401d72219](https://linux-hardware.org/?probe=2401d72219) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| HP            | 2B3B                        | All in one  | [4785289345](https://linux-hardware.org/?probe=4785289345) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [a4c65ac28f](https://linux-hardware.org/?probe=a4c65ac28f) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [ca83ed5e3f](https://linux-hardware.org/?probe=ca83ed5e3f) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | Notebook    | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6097531bfc](https://linux-hardware.org/?probe=6097531bfc) | May 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [f8f69fc110](https://linux-hardware.org/?probe=f8f69fc110) | May 06, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | Notebook    | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [8a25091e19](https://linux-hardware.org/?probe=8a25091e19) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [0e46a82cca](https://linux-hardware.org/?probe=0e46a82cca) | May 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c2b7a8dbe1](https://linux-hardware.org/?probe=c2b7a8dbe1) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [e9df412284](https://linux-hardware.org/?probe=e9df412284) | Apr 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [155ce08a00](https://linux-hardware.org/?probe=155ce08a00) | Apr 27, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [6eeb692185](https://linux-hardware.org/?probe=6eeb692185) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| Dell          | 03FV9K A00                  | Server      | [4d9f06ca7b](https://linux-hardware.org/?probe=4d9f06ca7b) | Apr 24, 2023 |
| DERE          | X16                         | Notebook    | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| HP            | 805D                        | Desktop     | [091e90cae0](https://linux-hardware.org/?probe=091e90cae0) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9f5177c657](https://linux-hardware.org/?probe=9f5177c657) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [e263516539](https://linux-hardware.org/?probe=e263516539) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| Dell          | 0HR330                      | Desktop     | [1619f09258](https://linux-hardware.org/?probe=1619f09258) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [983906ed11](https://linux-hardware.org/?probe=983906ed11) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HP            | 1850                        | Desktop     | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| HP            | 1850                        | Desktop     | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |
| Dell          | 0HR330                      | Desktop     | [4fd4f887bd](https://linux-hardware.org/?probe=4fd4f887bd) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [73b41d39ba](https://linux-hardware.org/?probe=73b41d39ba) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| HP            | 1589                        | Desktop     | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [aaef8a36db](https://linux-hardware.org/?probe=aaef8a36db) | Apr 10, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | Desktop     | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Gateway       | M-6812M                     | Notebook    | [6101b79a06](https://linux-hardware.org/?probe=6101b79a06) | Apr 08, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [fe77afbdfa](https://linux-hardware.org/?probe=fe77afbdfa) | Apr 07, 2023 |
| HP            | ProBook 6360b               | Notebook    | [bfa6c44b14](https://linux-hardware.org/?probe=bfa6c44b14) | Apr 07, 2023 |
| HP            | 895C                        | Desktop     | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| HP            | 895C                        | Desktop     | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Acer          | Aspire 3680                 | Notebook    | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| HP            | 8522 A01                    | Mini pc     | [28b79ea28b](https://linux-hardware.org/?probe=28b79ea28b) | Apr 04, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [f17cf21fbe](https://linux-hardware.org/?probe=f17cf21fbe) | Apr 04, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [ad5d8f611a](https://linux-hardware.org/?probe=ad5d8f611a) | Apr 04, 2023 |
| Notebook      | L140PU                      | Notebook    | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9da88b2a33](https://linux-hardware.org/?probe=9da88b2a33) | Apr 04, 2023 |
| HP            | 1850                        | Desktop     | [04243d9db8](https://linux-hardware.org/?probe=04243d9db8) | Apr 03, 2023 |
| HP            | 1850                        | Desktop     | [62b8f8056b](https://linux-hardware.org/?probe=62b8f8056b) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a6dcc077f](https://linux-hardware.org/?probe=7a6dcc077f) | Apr 03, 2023 |
| HP            | Unknown                     | Notebook    | [bd783cf180](https://linux-hardware.org/?probe=bd783cf180) | Apr 03, 2023 |
| HP            | 2000                        | Notebook    | [3fffec7875](https://linux-hardware.org/?probe=3fffec7875) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a225e27910](https://linux-hardware.org/?probe=a225e27910) | Apr 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [63d38ddebf](https://linux-hardware.org/?probe=63d38ddebf) | Apr 02, 2023 |
| Gateway       | ZX6900                      | All in one  | [83a5f64b3f](https://linux-hardware.org/?probe=83a5f64b3f) | Apr 02, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [5b3fcb351b](https://linux-hardware.org/?probe=5b3fcb351b) | Apr 02, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ed08c70a9](https://linux-hardware.org/?probe=2ed08c70a9) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [111eeac3b3](https://linux-hardware.org/?probe=111eeac3b3) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2fcab6a925](https://linux-hardware.org/?probe=2fcab6a925) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f8e723a8dc](https://linux-hardware.org/?probe=f8e723a8dc) | Mar 31, 2023 |
| Gigabyte      | B460M AORUS ELITE           | Desktop     | [87145cd4b2](https://linux-hardware.org/?probe=87145cd4b2) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| EVOO          | EVC156-1                    | Notebook    | [8e665ae8b2](https://linux-hardware.org/?probe=8e665ae8b2) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [f5db7a6030](https://linux-hardware.org/?probe=f5db7a6030) | Mar 30, 2023 |
| HP            | Notebook                    | Notebook    | [e631e8e62a](https://linux-hardware.org/?probe=e631e8e62a) | Mar 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [31d94ffb5f](https://linux-hardware.org/?probe=31d94ffb5f) | Mar 29, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [90fadbf903](https://linux-hardware.org/?probe=90fadbf903) | Mar 28, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [311057a095](https://linux-hardware.org/?probe=311057a095) | Mar 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Alienware     | 17 R4                       | Notebook    | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Lenovo        | IdeaPad Y910-17ISK 80V1     | Notebook    | [5e4e7975c1](https://linux-hardware.org/?probe=5e4e7975c1) | Mar 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [32341bde2a](https://linux-hardware.org/?probe=32341bde2a) | Mar 26, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c47ec8c99a](https://linux-hardware.org/?probe=c47ec8c99a) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| American M... | XA133PR110                  | Notebook    | [7e49d89ca8](https://linux-hardware.org/?probe=7e49d89ca8) | Mar 25, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [46af7d1f6d](https://linux-hardware.org/?probe=46af7d1f6d) | Mar 25, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| HP            | Unknown                     | Notebook    | [c27dcda931](https://linux-hardware.org/?probe=c27dcda931) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [e6219dd355](https://linux-hardware.org/?probe=e6219dd355) | Mar 24, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [51aab276a2](https://linux-hardware.org/?probe=51aab276a2) | Mar 23, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| ASUSTek       | X202EP                      | Notebook    | [5cc1f3216b](https://linux-hardware.org/?probe=5cc1f3216b) | Mar 23, 2023 |
| HP            | Unknown                     | Notebook    | [913aa678bf](https://linux-hardware.org/?probe=913aa678bf) | Mar 23, 2023 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [f364402e8a](https://linux-hardware.org/?probe=f364402e8a) | Mar 23, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b16e6324ed](https://linux-hardware.org/?probe=b16e6324ed) | Mar 22, 2023 |
| Dell          | G15 5511                    | Notebook    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [3ddfc82bcd](https://linux-hardware.org/?probe=3ddfc82bcd) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ccc7e9ae1](https://linux-hardware.org/?probe=7ccc7e9ae1) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [4544e68d4a](https://linux-hardware.org/?probe=4544e68d4a) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8a70a156a4](https://linux-hardware.org/?probe=8a70a156a4) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6dc3256710](https://linux-hardware.org/?probe=6dc3256710) | Mar 21, 2023 |
| HP            | Unknown                     | Notebook    | [66723d18e0](https://linux-hardware.org/?probe=66723d18e0) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [56b1138062](https://linux-hardware.org/?probe=56b1138062) | Mar 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [1fe782c379](https://linux-hardware.org/?probe=1fe782c379) | Mar 21, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [417d3cf9b7](https://linux-hardware.org/?probe=417d3cf9b7) | Mar 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb27b0fbaf](https://linux-hardware.org/?probe=cb27b0fbaf) | Mar 19, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [a38995d817](https://linux-hardware.org/?probe=a38995d817) | Mar 18, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [70b2fab92b](https://linux-hardware.org/?probe=70b2fab92b) | Mar 17, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | Notebook    | [70812fb9c8](https://linux-hardware.org/?probe=70812fb9c8) | Mar 17, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [f22446cb1d](https://linux-hardware.org/?probe=f22446cb1d) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Server      | [74269b72b0](https://linux-hardware.org/?probe=74269b72b0) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| ASUSTek       | Q525UAR                     | Convertible | [42443a4950](https://linux-hardware.org/?probe=42443a4950) | Mar 14, 2023 |
| Lenovo        | ThinkPad A485 20MVS0C300    | Notebook    | [f3dd1409f6](https://linux-hardware.org/?probe=f3dd1409f6) | Mar 14, 2023 |
| ASUSTek       | Q525UAR                     | Convertible | [5bd1e69a10](https://linux-hardware.org/?probe=5bd1e69a10) | Mar 14, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f91bf005b0](https://linux-hardware.org/?probe=f91bf005b0) | Mar 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2e94546c02](https://linux-hardware.org/?probe=2e94546c02) | Mar 11, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [94435f58ed](https://linux-hardware.org/?probe=94435f58ed) | Mar 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9535f3676b](https://linux-hardware.org/?probe=9535f3676b) | Mar 10, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fca941c098](https://linux-hardware.org/?probe=fca941c098) | Mar 10, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e770c2f24c](https://linux-hardware.org/?probe=e770c2f24c) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | Notebook    | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| Dell          | G3 3500                     | Notebook    | [5cfed5bee9](https://linux-hardware.org/?probe=5cfed5bee9) | Mar 10, 2023 |
| HP            | Pavilion dv4                | Notebook    | [79a8c505ef](https://linux-hardware.org/?probe=79a8c505ef) | Mar 09, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c81f97ee71](https://linux-hardware.org/?probe=c81f97ee71) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | 0HR330                      | Desktop     | [314bd7b2be](https://linux-hardware.org/?probe=314bd7b2be) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | Desktop     | [a56b16b410](https://linux-hardware.org/?probe=a56b16b410) | Mar 08, 2023 |
| Dell          | 0HR330                      | Desktop     | [a652a631f1](https://linux-hardware.org/?probe=a652a631f1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d677609a51](https://linux-hardware.org/?probe=d677609a51) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [67d9219fc2](https://linux-hardware.org/?probe=67d9219fc2) | Mar 07, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [780dc15bcc](https://linux-hardware.org/?probe=780dc15bcc) | Mar 06, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6f7e8084e5](https://linux-hardware.org/?probe=6f7e8084e5) | Mar 04, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [e1bd95af21](https://linux-hardware.org/?probe=e1bd95af21) | Mar 03, 2023 |
| HP            | ProBook 6360b               | Notebook    | [8b6826988f](https://linux-hardware.org/?probe=8b6826988f) | Mar 03, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [c3113c9da6](https://linux-hardware.org/?probe=c3113c9da6) | Mar 02, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [73efff8199](https://linux-hardware.org/?probe=73efff8199) | Mar 02, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [5915c17b3a](https://linux-hardware.org/?probe=5915c17b3a) | Mar 01, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [e3ba0ef4b7](https://linux-hardware.org/?probe=e3ba0ef4b7) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| HP            | Pavilion 14                 | Notebook    | [ae0e65f5d1](https://linux-hardware.org/?probe=ae0e65f5d1) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [d93d9bff7f](https://linux-hardware.org/?probe=d93d9bff7f) | Feb 27, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 279       | 9.65%   |
| Ubuntu 22.04       | 185       | 6.4%    |
| Ubuntu 18.04       | 174       | 6.02%   |
| OpenMandriva 4.2   | 91        | 3.15%   |
| OpenMandriva 4.3   | 87        | 3.01%   |
| Debian 11          | 82        | 2.84%   |
| Fedora 38          | 73        | 2.53%   |
| Zorin 16           | 71        | 2.46%   |
| Manjaro            | 54        | 1.87%   |
| KDE neon 20.04     | 51        | 1.76%   |
| Pop!_OS 22.04      | 46        | 1.59%   |
| Linux Mint 20.3    | 46        | 1.59%   |
| Fedora 36          | 43        | 1.49%   |
| Arch Rolling       | 39        | 1.35%   |
| ArcoLinux Rolling  | 38        | 1.31%   |
| OpenMandriva 23.03 | 34        | 1.18%   |
| Arch               | 34        | 1.18%   |
| Pop!_OS 20.04      | 33        | 1.14%   |
| Debian 12          | 31        | 1.07%   |
| Linux Mint 21.2    | 30        | 1.04%   |
| Zorin 15           | 29        | 1%      |
| KDE neon 22.04     | 29        | 1%      |
| Linux Mint 21.1    | 27        | 0.93%   |
| Linux Mint 20      | 27        | 0.93%   |
| Ubuntu 19.10       | 26        | 0.9%    |
| OpenMandriva 23.08 | 26        | 0.9%    |
| Fedora 35          | 26        | 0.9%    |
| Ubuntu 21.10       | 25        | 0.87%   |
| OpenMandriva 23.01 | 25        | 0.87%   |
| Linux Mint 19.3    | 25        | 0.87%   |
| Fedora 37          | 25        | 0.87%   |
| Ubuntu 19.04       | 23        | 0.8%    |
| Debian 10          | 23        | 0.8%    |
| Ubuntu 22.10       | 22        | 0.76%   |
| Ubuntu 20.10       | 22        | 0.76%   |
| Pop!_OS 21.04      | 22        | 0.76%   |
| Linux Mint 21      | 22        | 0.76%   |
| Linux Mint 20.1    | 20        | 0.69%   |
| Kubuntu 20.04      | 20        | 0.69%   |
| Ubuntu 23.04       | 19        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 792       | 28.71%  |
| OpenMandriva  | 272       | 9.86%   |
| Fedora        | 229       | 8.3%    |
| Linux Mint    | 221       | 8.01%   |
| Debian        | 146       | 5.29%   |
| Pop!_OS       | 116       | 4.2%    |
| Zorin         | 107       | 3.88%   |
| Manjaro       | 102       | 3.7%    |
| KDE neon      | 81        | 2.94%   |
| Arch          | 73        | 2.65%   |
| Kubuntu       | 55        | 1.99%   |
| Endless       | 48        | 1.74%   |
| Xubuntu       | 47        | 1.7%    |
| ROSA          | 47        | 1.7%    |
| Elementary    | 43        | 1.56%   |
| ArcoLinux     | 38        | 1.38%   |
| Kali          | 31        | 1.12%   |
| openSUSE      | 30        | 1.09%   |
| Nobara        | 19        | 0.69%   |
| EndeavourOS   | 18        | 0.65%   |
| Lubuntu       | 17        | 0.62%   |
| Clear Linux   | 15        | 0.54%   |
| Ubuntu MATE   | 14        | 0.51%   |
| LMDE          | 14        | 0.51%   |
| Gentoo        | 13        | 0.47%   |
| Ubuntu Budgie | 12        | 0.43%   |
| Ubuntu Unity  | 11        | 0.4%    |
| SteamOS       | 11        | 0.4%    |
| Parrot        | 11        | 0.4%    |
| MX            | 10        | 0.36%   |
| CentOS        | 10        | 0.36%   |
| Xero          | 9         | 0.33%   |
| Garuda Linux  | 8         | 0.29%   |
| Archcraft     | 6         | 0.22%   |
| Peppermint    | 5         | 0.18%   |
| Linux Lite    | 5         | 0.18%   |
| RHEL          | 4         | 0.14%   |
| Reborn OS     | 4         | 0.14%   |
| BlackPanther  | 4         | 0.14%   |
| BigLinux      | 4         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 91        | 2.88%   |
| 5.16.7-desktop-1omv4003  | 80        | 2.53%   |
| 5.4.0-42-generic         | 44        | 1.39%   |
| 6.2.6-desktop-1omv2390   | 29        | 0.92%   |
| 5.4.0-58-generic         | 27        | 0.86%   |
| 5.15.0-56-generic        | 27        | 0.86%   |
| 6.1.1-desktop-1omv2290   | 23        | 0.73%   |
| 6.4.11-desktop-1omv2390  | 22        | 0.7%    |
| 5.15.0-58-generic        | 22        | 0.7%    |
| 5.8.0-14-generic         | 21        | 0.67%   |
| 5.4.0-91-generic         | 20        | 0.63%   |
| 5.3.0-40-generic         | 20        | 0.63%   |
| 5.11.0-27-generic        | 19        | 0.6%    |
| 5.4.0-52-generic         | 18        | 0.57%   |
| 5.4.0-48-generic         | 18        | 0.57%   |
| 5.15.0-52-generic        | 18        | 0.57%   |
| 5.4.0-40-generic         | 17        | 0.54%   |
| 5.19.0-35-generic        | 17        | 0.54%   |
| 5.15.0-48-generic        | 17        | 0.54%   |
| 5.15.0-47-generic        | 17        | 0.54%   |
| 6.1.0-13-amd64           | 16        | 0.51%   |
| 5.3.0-46-generic         | 16        | 0.51%   |
| 5.11.0-37-generic        | 16        | 0.51%   |
| 6.2.6-76060206-generic   | 15        | 0.48%   |
| 5.4.0-65-generic         | 15        | 0.48%   |
| 5.13.0-40-generic        | 15        | 0.48%   |
| 6.2.0-26-generic         | 14        | 0.44%   |
| 5.4.0-54-generic         | 14        | 0.44%   |
| 5.4.0-37-generic         | 14        | 0.44%   |
| 5.3.0-42-generic         | 14        | 0.44%   |
| 5.3.0-28-generic         | 14        | 0.44%   |
| 5.19.0-43-generic        | 14        | 0.44%   |
| 5.19.0-38-generic        | 14        | 0.44%   |
| 5.13.0-39-generic        | 14        | 0.44%   |
| 5.15.0-78-generic        | 13        | 0.41%   |
| 5.11.0-7620-generic      | 13        | 0.41%   |
| 6.2.0-37-generic         | 12        | 0.38%   |
| 5.4.0-7642-generic       | 12        | 0.38%   |
| 5.4.0-33-generic         | 12        | 0.38%   |
| 5.15.0-60-generic        | 12        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 397       | 13.33%  |
| 5.15.0  | 264       | 8.87%   |
| 5.11.0  | 134       | 4.5%    |
| 5.13.0  | 127       | 4.26%   |
| 5.8.0   | 120       | 4.03%   |
| 4.15.0  | 113       | 3.79%   |
| 5.3.0   | 111       | 3.73%   |
| 5.19.0  | 101       | 3.39%   |
| 5.10.14 | 91        | 3.06%   |
| 6.2.0   | 87        | 2.92%   |
| 5.10.0  | 87        | 2.92%   |
| 5.16.7  | 81        | 2.72%   |
| 4.18.0  | 74        | 2.48%   |
| 5.0.0   | 72        | 2.42%   |
| 6.1.0   | 48        | 1.61%   |
| 6.2.6   | 44        | 1.48%   |
| 4.19.0  | 35        | 1.18%   |
| 6.4.11  | 30        | 1.01%   |
| 6.1.1   | 30        | 1.01%   |
| 6.5.0   | 16        | 0.54%   |
| 6.5.5   | 11        | 0.37%   |
| 6.4.6   | 11        | 0.37%   |
| 6.2.15  | 11        | 0.37%   |
| 6.0.12  | 11        | 0.37%   |
| 5.16.13 | 11        | 0.37%   |
| 5.14.0  | 11        | 0.37%   |
| 6.0.0   | 10        | 0.34%   |
| 5.17.5  | 10        | 0.34%   |
| 6.4.12  | 9         | 0.3%    |
| 6.3.5   | 9         | 0.3%    |
| 6.2.14  | 9         | 0.3%    |
| 4.9.20  | 9         | 0.3%    |
| 6.6.2   | 8         | 0.27%   |
| 6.2.9   | 8         | 0.27%   |
| 6.6.1   | 7         | 0.24%   |
| 6.5.6   | 7         | 0.24%   |
| 6.4.8   | 7         | 0.24%   |
| 6.4.4   | 7         | 0.24%   |
| 6.4.10  | 7         | 0.24%   |
| 6.0.11  | 7         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 427       | 14.54%  |
| 5.15    | 335       | 11.41%  |
| 5.10    | 220       | 7.49%   |
| 6.2     | 179       | 6.09%   |
| 5.11    | 152       | 5.18%   |
| 5.13    | 145       | 4.94%   |
| 5.19    | 137       | 4.66%   |
| 5.8     | 135       | 4.6%    |
| 5.3     | 128       | 4.36%   |
| 5.16    | 124       | 4.22%   |
| 6.1     | 114       | 3.88%   |
| 4.15    | 113       | 3.85%   |
| 6.4     | 94        | 3.2%    |
| 4.18    | 76        | 2.59%   |
| 5.0     | 73        | 2.49%   |
| 6.5     | 66        | 2.25%   |
| 6.0     | 54        | 1.84%   |
| 6.3     | 41        | 1.4%    |
| 4.19    | 41        | 1.4%    |
| 5.18    | 37        | 1.26%   |
| 5.17    | 35        | 1.19%   |
| 5.14    | 32        | 1.09%   |
| 6.6     | 30        | 1.02%   |
| 5.9     | 25        | 0.85%   |
| 4.9     | 25        | 0.85%   |
| 5.7     | 22        | 0.75%   |
| 5.12    | 21        | 0.72%   |
| 5.6     | 19        | 0.65%   |
| 5.5     | 9         | 0.31%   |
| 4.4     | 6         | 0.2%    |
| 5.2     | 4         | 0.14%   |
| 4.12    | 4         | 0.14%   |
| 4.13    | 3         | 0.1%    |
| 4.1     | 3         | 0.1%    |
| 4.10    | 2         | 0.07%   |
| 3.10    | 2         | 0.07%   |
| 6.7     | 1         | 0.03%   |
| 5.1     | 1         | 0.03%   |
| 4.20    | 1         | 0.03%   |
| 3.2     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2565      | 96.94%  |
| i686    | 76        | 2.87%   |
| aarch64 | 4         | 0.15%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1219      | 44.09%  |
| KDE5              | 569       | 20.58%  |
| Unknown           | 231       | 8.35%   |
| XFCE              | 197       | 7.12%   |
| X-Cinnamon        | 173       | 6.26%   |
| MATE              | 84        | 3.04%   |
| KDE               | 73        | 2.64%   |
| Pantheon          | 41        | 1.48%   |
| Cinnamon          | 36        | 1.3%    |
| LXQt              | 24        | 0.87%   |
| KDE4              | 22        | 0.8%    |
| LXDE              | 17        | 0.61%   |
| Budgie            | 16        | 0.58%   |
| Unity             | 11        | 0.4%    |
| i3                | 8         | 0.29%   |
| Deepin            | 8         | 0.29%   |
| openbox           | 5         | 0.18%   |
| lightdm-xsession  | 4         | 0.14%   |
| GNOME Classic     | 4         | 0.14%   |
| trinity           | 3         | 0.11%   |
| qtile             | 3         | 0.11%   |
| Hyprland          | 3         | 0.11%   |
| GNOME Flashback   | 3         | 0.11%   |
| Enlightenment     | 3         | 0.11%   |
| awesome           | 2         | 0.07%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| xmonad            | 1         | 0.04%   |
| wayland           | 1         | 0.04%   |
| i3-with-shmlog    | 1         | 0.04%   |
| chadwm            | 1         | 0.04%   |
| bspwm             | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2018      | 73.57%  |
| Wayland | 565       | 20.6%   |
| Unknown | 142       | 5.18%   |
| Tty     | 18        | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1326      | 48.22%  |
| SDDM    | 474       | 17.24%  |
| GDM3    | 321       | 11.67%  |
| LightDM | 277       | 10.07%  |
| GDM     | 260       | 9.45%   |
| TDM     | 53        | 1.93%   |
| KDM     | 23        | 0.84%   |
| SLiM    | 5         | 0.18%   |
| XDM     | 4         | 0.15%   |
| LXDM    | 3         | 0.11%   |
| NODM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LY-DM   | 1         | 0.04%   |
| Ly      | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_MX      | 1333      | 49.08%  |
| en_US      | 868       | 31.96%  |
| Unknown    | 224       | 8.25%   |
| es_ES      | 177       | 6.52%   |
| C          | 49        | 1.8%    |
| en_GB      | 21        | 0.77%   |
| es_US      | 8         | 0.29%   |
| en_CA      | 5         | 0.18%   |
| fr_FR      | 3         | 0.11%   |
| POSIX      | 2         | 0.07%   |
| it_IT      | 2         | 0.07%   |
| es_MX.UTF8 | 2         | 0.07%   |
| es_CO      | 2         | 0.07%   |
| es_AR      | 2         | 0.07%   |
| en_MX      | 2         | 0.07%   |
| en_DK      | 2         | 0.07%   |
| C.UTF8     | 2         | 0.07%   |
| uk_UA      | 1         | 0.04%   |
| ru_RU      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nhn_MX     | 1         | 0.04%   |
| es_PE      | 1         | 0.04%   |
| es_GT      | 1         | 0.04%   |
| es_CR      | 1         | 0.04%   |
| es_419     | 1         | 0.04%   |
| en_US.UTF8 | 1         | 0.04%   |
| en_IE      | 1         | 0.04%   |
| de_DE      | 1         | 0.04%   |
| Default    | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1422      | 52.55%  |
| EFI  | 1284      | 47.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 1971      | 72.54%  |
| Btrfs               | 270       | 9.94%   |
| Overlay             | 258       | 9.5%    |
| Tmpfs               | 83        | 3.05%   |
| Unknown             | 69        | 2.54%   |
| Xfs                 | 35        | 1.29%   |
| Zfs                 | 12        | 0.44%   |
| Ext2                | 8         | 0.29%   |
| Reiserfs            | 3         | 0.11%   |
| XXXXXXX             | 2         | 0.07%   |
| F2fs                | 2         | 0.07%   |
| Ext3                | 2         | 0.07%   |
| Fuse.fuse-overlayfs | 1         | 0.04%   |
| Aufs                | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1441      | 53.13%  |
| GPT     | 965       | 35.58%  |
| MBR     | 306       | 11.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2348      | 87.22%  |
| Yes       | 344       | 12.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1837      | 68.04%  |
| Yes       | 863       | 31.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 509       | 19.24%  |
| Lenovo                  | 379       | 14.33%  |
| Dell                    | 376       | 14.22%  |
| ASUSTek Computer        | 296       | 11.19%  |
| Gigabyte Technology     | 184       | 6.96%   |
| Acer                    | 138       | 5.22%   |
| Apple                   | 86        | 3.25%   |
| Toshiba                 | 79        | 2.99%   |
| HUAWEI                  | 74        | 2.8%    |
| MSI                     | 58        | 2.19%   |
| Sony                    | 42        | 1.59%   |
| ASRock                  | 40        | 1.51%   |
| Intel                   | 36        | 1.36%   |
| ECS                     | 32        | 1.21%   |
| Biostar                 | 29        | 1.1%    |
| Gateway                 | 23        | 0.87%   |
| Samsung Electronics     | 21        | 0.79%   |
| Pegatron                | 18        | 0.68%   |
| Google                  | 17        | 0.64%   |
| Alienware               | 17        | 0.64%   |
| Lanix                   | 16        | 0.6%    |
| Unknown                 | 16        | 0.6%    |
| Chuwi                   | 11        | 0.42%   |
| Valve                   | 9         | 0.34%   |
| PCChips                 | 9         | 0.34%   |
| Microsoft               | 9         | 0.34%   |
| AMI                     | 8         | 0.3%    |
| GPU Company             | 7         | 0.26%   |
| Foxconn                 | 7         | 0.26%   |
| eMachines               | 7         | 0.26%   |
| GHIA                    | 5         | 0.19%   |
| A-DATA Technology       | 5         | 0.19%   |
| Timi                    | 4         | 0.15%   |
| System76                | 4         | 0.15%   |
| Raspberry Pi Foundation | 4         | 0.15%   |
| HONOR                   | 4         | 0.15%   |
| EVOO                    | 4         | 0.15%   |
| AZW                     | 4         | 0.15%   |
| TPV-INVENTA             | 3         | 0.11%   |
| Supermicro              | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 30        | 1.13%   |
| HP Notebook                   | 29        | 1.1%    |
| ASUS PRIME A320M-K            | 20        | 0.76%   |
| HUAWEI HVY-WXX9               | 18        | 0.68%   |
| HP Pavilion Laptop 15-cw0xxx  | 17        | 0.64%   |
| HP Pavilion g4                | 16        | 0.6%    |
| HP Pavilion Notebook          | 15        | 0.57%   |
| ASUS All Series               | 11        | 0.42%   |
| Apple MacBookPro9,2           | 11        | 0.42%   |
| HP Pavilion Laptop 15-cw1xxx  | 10        | 0.38%   |
| HP Laptop 15-da0xxx           | 10        | 0.38%   |
| Dell Latitude E6430           | 10        | 0.38%   |
| Apple MacBookPro8,1           | 10        | 0.38%   |
| Valve Jupiter                 | 9         | 0.34%   |
| HP EliteBook 8460p            | 9         | 0.34%   |
| Gigabyte B450M DS3H           | 9         | 0.34%   |
| Lenovo IdeaPad 330-14AST 81D5 | 8         | 0.3%    |
| HP Laptop 15-bw0xx            | 8         | 0.3%    |
| Dell OptiPlex 7010            | 8         | 0.3%    |
| HUAWEI NBLK-WAX9X             | 7         | 0.26%   |
| HUAWEI NBLB-WAX9N             | 7         | 0.26%   |
| HP Pavilion dv4               | 7         | 0.26%   |
| HP Laptop 15-db0xxx           | 7         | 0.26%   |
| ECS A320AM4-M3D               | 7         | 0.26%   |
| Dell OptiPlex 9020            | 7         | 0.26%   |
| Dell OptiPlex 745             | 7         | 0.26%   |
| Dell Inspiron 5559            | 7         | 0.26%   |
| ASUS PRIME B450M-A II         | 7         | 0.26%   |
| Apple MacBookPro12,1          | 7         | 0.26%   |
| Lenovo G40-45 80E1            | 6         | 0.23%   |
| HP Pavilion dv5               | 6         | 0.23%   |
| HP Pavilion 14                | 6         | 0.23%   |
| HP Laptop 14-cm0xxx           | 6         | 0.23%   |
| HP G42                        | 6         | 0.23%   |
| HP Compaq 6200 Pro SFF PC     | 6         | 0.23%   |
| GPU Company GWNR71517         | 6         | 0.23%   |
| Gigabyte GA-880GM-USB3        | 6         | 0.23%   |
| Gigabyte A320M-S2H            | 6         | 0.23%   |
| Dell Inspiron 3421            | 6         | 0.23%   |
| ASUS ROG STRIX B450-F GAMING  | 6         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 129       | 4.88%   |
| Lenovo ThinkPad    | 122       | 4.61%   |
| Dell Inspiron      | 117       | 4.42%   |
| Lenovo IdeaPad     | 116       | 4.39%   |
| Dell Latitude      | 102       | 3.86%   |
| Acer Aspire        | 97        | 3.67%   |
| Toshiba Satellite  | 70        | 2.65%   |
| HP Laptop          | 69        | 2.61%   |
| Dell OptiPlex      | 68        | 2.57%   |
| ASUS PRIME         | 67        | 2.53%   |
| HP Compaq          | 49        | 1.85%   |
| Lenovo ThinkCentre | 30        | 1.13%   |
| HP EliteBook       | 30        | 1.13%   |
| Unknown            | 30        | 1.13%   |
| HP Notebook        | 29        | 1.1%    |
| ASUS VivoBook      | 28        | 1.06%   |
| HP ProBook         | 27        | 1.02%   |
| ASUS ROG           | 26        | 0.98%   |
| Dell Precision     | 19        | 0.72%   |
| HUAWEI HVY-WXX9    | 18        | 0.68%   |
| HP ENVY            | 17        | 0.64%   |
| Lenovo Yoga        | 15        | 0.57%   |
| ASUS TUF           | 15        | 0.57%   |
| HP ProDesk         | 13        | 0.49%   |
| Dell XPS           | 13        | 0.49%   |
| Dell Vostro        | 13        | 0.49%   |
| Lenovo Legion      | 12        | 0.45%   |
| HP 240             | 12        | 0.45%   |
| Gigabyte B450M     | 12        | 0.45%   |
| Apple MacBookPro9  | 12        | 0.45%   |
| Dell Studio        | 11        | 0.42%   |
| ASUS All           | 11        | 0.42%   |
| Apple MacBookPro8  | 11        | 0.42%   |
| Gigabyte A320M-S2H | 10        | 0.38%   |
| Valve Jupiter      | 9         | 0.34%   |
| Microsoft Surface  | 9         | 0.34%   |
| HP OMEN            | 9         | 0.34%   |
| Gigabyte X570      | 9         | 0.34%   |
| ASUS M5A78L-M      | 9         | 0.34%   |
| ASUS ASUS          | 9         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 249       | 9.41%   |
| 2011    | 232       | 8.77%   |
| 2012    | 212       | 8.02%   |
| 2020    | 209       | 7.9%    |
| 2019    | 201       | 7.6%    |
| 2017    | 196       | 7.41%   |
| 2014    | 174       | 6.58%   |
| 2013    | 169       | 6.39%   |
| 2015    | 162       | 6.12%   |
| 2021    | 155       | 5.86%   |
| 2010    | 135       | 5.1%    |
| 2016    | 129       | 4.88%   |
| 2008    | 109       | 4.12%   |
| 2009    | 101       | 3.82%   |
| 2022    | 73        | 2.76%   |
| 2007    | 66        | 2.5%    |
| 2023    | 26        | 0.98%   |
| 2006    | 26        | 0.98%   |
| 2005    | 12        | 0.45%   |
| Unknown | 6         | 0.23%   |
| 2004    | 2         | 0.08%   |
| 2003    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1636      | 61.85%  |
| Desktop        | 824       | 31.15%  |
| All in one     | 56        | 2.12%   |
| Convertible    | 52        | 1.97%   |
| Mini pc        | 28        | 1.06%   |
| Tablet         | 26        | 0.98%   |
| Server         | 19        | 0.72%   |
| System on chip | 4         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2431      | 91.08%  |
| Enabled  | 238       | 8.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2626      | 99.28%  |
| Yes  | 19        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 735       | 27.36%  |
| 3.01-4.0        | 582       | 21.67%  |
| 8.01-16.0       | 526       | 19.58%  |
| 16.01-24.0      | 365       | 13.59%  |
| 1.01-2.0        | 153       | 5.7%    |
| 32.01-64.0      | 148       | 5.51%   |
| 24.01-32.0      | 53        | 1.97%   |
| 2.01-3.0        | 53        | 1.97%   |
| 64.01-256.0     | 43        | 1.6%    |
| 0.51-1.0        | 23        | 0.86%   |
| More than 256.0 | 3         | 0.11%   |
| 0.01-0.5        | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1043      | 35.66%  |
| 2.01-3.0    | 788       | 26.94%  |
| 3.01-4.0    | 386       | 13.2%   |
| 4.01-8.0    | 376       | 12.85%  |
| 0.51-1.0    | 186       | 6.36%   |
| 8.01-16.0   | 102       | 3.49%   |
| 0.01-0.5    | 23        | 0.79%   |
| 16.01-24.0  | 12        | 0.41%   |
| 24.01-32.0  | 4         | 0.14%   |
| 32.01-64.0  | 2         | 0.07%   |
| Unknown     | 2         | 0.07%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1795      | 65.8%   |
| 2       | 655       | 24.01%  |
| 3       | 143       | 5.24%   |
| 4       | 60        | 2.2%    |
| 0       | 33        | 1.21%   |
| 5       | 19        | 0.7%    |
| 6       | 14        | 0.51%   |
| 7       | 5         | 0.18%   |
| 37      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1681      | 63.1%   |
| Yes       | 983       | 36.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2258      | 85.27%  |
| No        | 390       | 14.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2181      | 82.05%  |
| No        | 477       | 17.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1590      | 59.33%  |
| No        | 1090      | 40.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Mexico  | 2645      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 546       | 19.44%  |
| Guadalajara           | 143       | 5.09%   |
| Monterrey             | 96        | 3.42%   |
| Tijuana               | 88        | 3.13%   |
| Zapopan               | 83        | 2.96%   |
| Puebla City           | 75        | 2.67%   |
| Queretaro             | 55        | 1.96%   |
| Mérida               | 54        | 1.92%   |
| Toluca                | 40        | 1.42%   |
| Morelia               | 39        | 1.39%   |
| Ciudad Juárez        | 37        | 1.32%   |
| Hermosillo            | 36        | 1.28%   |
| Tlalnepantla          | 35        | 1.25%   |
| Cancún               | 35        | 1.25%   |
| Mexicali              | 32        | 1.14%   |
| León                 | 32        | 1.14%   |
| Naucalpan             | 31        | 1.1%    |
| Ecatepec              | 31        | 1.1%    |
| Cuernavaca            | 28        | 1%      |
| Ciudad Lopez Mateos   | 28        | 1%      |
| Xalapa                | 27        | 0.96%   |
| Ciudad Nezahualcoyotl | 27        | 0.96%   |
| Apodaca               | 27        | 0.96%   |
| Culiacán             | 26        | 0.93%   |
| Chihuahua City        | 26        | 0.93%   |
| San Luis Potosí City | 25        | 0.89%   |
| Oaxaca City           | 25        | 0.89%   |
| Veracruz              | 24        | 0.85%   |
| México               | 24        | 0.85%   |
| Guadalupe             | 22        | 0.78%   |
| Saltillo              | 21        | 0.75%   |
| Villahermosa          | 20        | 0.71%   |
| Iztapalapa            | 20        | 0.71%   |
| Gustavo Adolfo Madero | 20        | 0.71%   |
| Querétaro City       | 18        | 0.64%   |
| Pachuca               | 18        | 0.64%   |
| Aguascalientes        | 18        | 0.64%   |
| Ensenada              | 17        | 0.61%   |
| Colima                | 17        | 0.61%   |
| Puerto Vallarta       | 16        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 641       | 937    | 17.83%  |
| WDC                         | 549       | 747    | 15.27%  |
| Kingston                    | 352       | 460    | 9.79%   |
| Toshiba                     | 304       | 369    | 8.46%   |
| A-DATA Technology           | 258       | 321    | 7.18%   |
| Samsung Electronics         | 231       | 300    | 6.43%   |
| Hitachi                     | 174       | 221    | 4.84%   |
| Unknown                     | 157       | 211    | 4.37%   |
| Sandisk                     | 114       | 141    | 3.17%   |
| HGST                        | 89        | 103    | 2.48%   |
| SK hynix                    | 63        | 82     | 1.75%   |
| Intel                       | 62        | 101    | 1.72%   |
| Crucial                     | 48        | 64     | 1.34%   |
| Apple                       | 39        | 54     | 1.08%   |
| XPG                         | 35        | 47     | 0.97%   |
| Micron Technology           | 30        | 41     | 0.83%   |
| Fujitsu                     | 25        | 30     | 0.7%    |
| Realtek Semiconductor       | 22        | 28     | 0.61%   |
| PNY                         | 22        | 29     | 0.61%   |
| Silicon Motion              | 19        | 20     | 0.53%   |
| Unknown                     | 18        | 18     | 0.5%    |
| KIOXIA                      | 17        | 19     | 0.47%   |
| ADATA Technology            | 17        | 19     | 0.47%   |
| Phison                      | 16        | 17     | 0.45%   |
| China                       | 16        | 17     | 0.45%   |
| LITEON                      | 15        | 20     | 0.42%   |
| Kingston Technology Company | 15        | 15     | 0.42%   |
| Hewlett-Packard             | 12        | 12     | 0.33%   |
| Phison Electronics          | 11        | 14     | 0.31%   |
| Micron/Crucial Technology   | 11        | 15     | 0.31%   |
| Netac                       | 10        | 12     | 0.28%   |
| Maxtor                      | 10        | 12     | 0.28%   |
| Acer                        | 10        | 12     | 0.28%   |
| JMicron Technology          | 9         | 10     | 0.25%   |
| YMTC                        | 8         | 9      | 0.22%   |
| Patriot                     | 8         | 12     | 0.22%   |
| Gigabyte Technology         | 8         | 9      | 0.22%   |
| UMIS                        | 6         | 7      | 0.17%   |
| AS201                       | 6         | 6      | 0.17%   |
| Wibtek                      | 5         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 94        | 2.43%   |
| Kingston SA400S37480G 480GB SSD                     | 75        | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB                      | 74        | 1.92%   |
| Toshiba MQ01ABD100 1TB                              | 50        | 1.29%   |
| A-DATA SU650 120GB SSD                              | 50        | 1.29%   |
| Toshiba MQ04ABF100 1TB                              | 44        | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 1.04%   |
| Seagate ST500DM002-1BD142 500GB                     | 39        | 1.01%   |
| A-DATA SU630 240GB SSD                              | 38        | 0.98%   |
| Unknown MMC Card  32GB                              | 34        | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 32        | 0.83%   |
| Toshiba MQ01ABF050 500GB                            | 29        | 0.75%   |
| Kingston SA400S37120G 120GB SSD                     | 29        | 0.75%   |
| A-DATA SU630 480GB SSD                              | 26        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 25        | 0.65%   |
| Kingston SA400S37960G 960GB SSD                     | 25        | 0.65%   |
| A-DATA SU650 240GB SSD                              | 21        | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 18        | 0.47%   |
| Unknown MMC Card  64GB                              | 18        | 0.47%   |
| Unknown                                             | 18        | 0.47%   |
| Unknown MMC Card  16GB                              | 17        | 0.44%   |
| Unknown SD/MMC/MS PRO 128GB                         | 16        | 0.41%   |
| Seagate ST9500325AS 500GB                           | 16        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 16        | 0.41%   |
| HGST HTS541010A9E680 1TB                            | 16        | 0.41%   |
| Toshiba DT01ACA050 500GB                            | 15        | 0.39%   |
| Seagate ST3500418AS 500GB                           | 15        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 15        | 0.39%   |
| XPG GAMMIX S11 Pro 256GB                            | 14        | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB                     | 14        | 0.36%   |
| HGST HTS725050A7E630 500GB                          | 14        | 0.36%   |
| Toshiba DT01ACA100 1TB                              | 13        | 0.34%   |
| Seagate ST2000LM007-1R8174 2TB                      | 13        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB                      | 13        | 0.34%   |
| Samsung NVMe SSD Drive 512GB                        | 13        | 0.34%   |
| A-DATA SU800 512GB SSD                              | 13        | 0.34%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 12        | 0.31%   |
| Seagate ST500LT012-9WS142 500GB                     | 12        | 0.31%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 12        | 0.31%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 637       | 931    | 36.15%  |
| WDC                 | 472       | 629    | 26.79%  |
| Toshiba             | 273       | 333    | 15.49%  |
| Hitachi             | 174       | 221    | 9.88%   |
| HGST                | 89        | 103    | 5.05%   |
| Samsung Electronics | 35        | 40     | 1.99%   |
| Fujitsu             | 25        | 30     | 1.42%   |
| Unknown             | 16        | 17     | 0.91%   |
| Apple               | 13        | 18     | 0.74%   |
| Maxtor              | 10        | 12     | 0.57%   |
| USB3.0              | 3         | 3      | 0.17%   |
| Hewlett-Packard     | 3         | 3      | 0.17%   |
| Pioneer             | 2         | 3      | 0.11%   |
| LaCie               | 2         | 3      | 0.11%   |
| StoreJet            | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QUANTUM             | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 4      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| External            | 1         | 1      | 0.06%   |
| DELLBOSS            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 316       | 404    | 30.86%  |
| A-DATA Technology   | 240       | 302    | 23.44%  |
| Samsung Electronics | 72        | 85     | 7.03%   |
| WDC                 | 64        | 84     | 6.25%   |
| Crucial             | 42        | 50     | 4.1%    |
| SanDisk             | 41        | 47     | 4%      |
| PNY                 | 22        | 29     | 2.15%   |
| Apple               | 21        | 23     | 2.05%   |
| SK hynix            | 17        | 26     | 1.66%   |
| China               | 16        | 17     | 1.56%   |
| Intel               | 15        | 20     | 1.46%   |
| LITEON              | 13        | 18     | 1.27%   |
| Micron Technology   | 11        | 14     | 1.07%   |
| Netac               | 10        | 12     | 0.98%   |
| Acer                | 9         | 10     | 0.88%   |
| Hewlett-Packard     | 8         | 8      | 0.78%   |
| Patriot             | 7         | 11     | 0.68%   |
| Gigabyte Technology | 7         | 8      | 0.68%   |
| AS201               | 6         | 6      | 0.59%   |
| Wibtek              | 5         | 5      | 0.49%   |
| JMicron Technology  | 5         | 6      | 0.49%   |
| Unknown             | 5         | 5      | 0.49%   |
| Toshiba             | 4         | 4      | 0.39%   |
| Team                | 4         | 4      | 0.39%   |
| SPCC                | 4         | 4      | 0.39%   |
| LITEONIT            | 4         | 4      | 0.39%   |
| Blackpcs            | 4         | 4      | 0.39%   |
| Yeyian              | 3         | 6      | 0.29%   |
| Unknown             | 3         | 3      | 0.29%   |
| Transcend           | 3         | 3      | 0.29%   |
| OCZ                 | 3         | 5      | 0.29%   |
| Lexar               | 3         | 3      | 0.29%   |
| BHT                 | 3         | 3      | 0.29%   |
| tecmiyo             | 2         | 3      | 0.2%    |
| Quaroni             | 2         | 2      | 0.2%    |
| KingSpec            | 2         | 7      | 0.2%    |
| Dogfish             | 2         | 5      | 0.2%    |
| ZTC                 | 1         | 1      | 0.1%    |
| ZOTAC               | 1         | 1      | 0.1%    |
| Zheino              | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1562      | 2358   | 47.65%  |
| SSD     | 928       | 1279   | 28.31%  |
| NVMe    | 605       | 848    | 18.46%  |
| MMC     | 142       | 192    | 4.33%   |
| Unknown | 41        | 57     | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2135      | 3541   | 71.07%  |
| NVMe | 602       | 843    | 20.04%  |
| MMC  | 142       | 192    | 4.73%   |
| SAS  | 125       | 158    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1555      | 2250   | 61.1%   |
| 0.51-1.0   | 768       | 1023   | 30.18%  |
| 1.01-2.0   | 144       | 204    | 5.66%   |
| 3.01-4.0   | 34        | 65     | 1.34%   |
| 2.01-3.0   | 25        | 34     | 0.98%   |
| 4.01-10.0  | 16        | 40     | 0.63%   |
| 10.01-20.0 | 3         | 21     | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 711       | 25.36%  |
| 251-500        | 648       | 23.11%  |
| 501-1000       | 447       | 15.94%  |
| 1-20           | 238       | 8.49%   |
| 51-100         | 222       | 7.92%   |
| 1001-2000      | 216       | 7.7%    |
| 21-50          | 132       | 4.71%   |
| More than 3000 | 85        | 3.03%   |
| 2001-3000      | 58        | 2.07%   |
| Unknown        | 47        | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1204      | 41.43%  |
| 21-50          | 550       | 18.93%  |
| 101-250        | 343       | 11.8%   |
| 51-100         | 316       | 10.87%  |
| 251-500        | 195       | 6.71%   |
| 501-1000       | 136       | 4.68%   |
| 1001-2000      | 76        | 2.62%   |
| Unknown        | 47        | 1.62%   |
| More than 3000 | 25        | 0.86%   |
| 2001-3000      | 14        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 8         | 9      | 2.67%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 7      | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 2%      |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 1.67%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.67%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 1.33%   |
| Seagate ST3160815AS 160GB           | 4         | 4      | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 1.33%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 1.33%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 1.33%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 1%      |
| Seagate ST3500418AS 500GB           | 3         | 3      | 1%      |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 3      | 1%      |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 3      | 1%      |
| HGST HTS545050A7E380 500GB          | 3         | 5      | 1%      |
| HGST HTS541010A7E630 1TB            | 3         | 3      | 1%      |
| China SSD 256GB                     | 3         | 3      | 1%      |
| A-DATA Technology SU650 240GB SSD   | 3         | 3      | 1%      |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.67%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 0.67%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2         | 3      | 0.67%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 0.67%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 2      | 0.67%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.67%   |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.67%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 0.67%   |
| Seagate ST9320325AS 320GB           | 2         | 4      | 0.67%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 3      | 0.67%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 0.67%   |
| Seagate ST31000524AS 1TB            | 2         | 4      | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 2      | 0.67%   |
| Seagate ST1500DL003-9VT16L 1TB      | 2         | 2      | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 2      | 0.67%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 0.67%   |
| Maxtor 6Y080M0 82GB                 | 2         | 2      | 0.67%   |
| Kingston SUV400S37480G 480GB SSD    | 2         | 2      | 0.67%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 89        | 123    | 30.58%  |
| WDC                       | 58        | 70     | 19.93%  |
| Toshiba                   | 37        | 49     | 12.71%  |
| Hitachi                   | 37        | 40     | 12.71%  |
| HGST                      | 18        | 20     | 6.19%   |
| Kingston                  | 13        | 13     | 4.47%   |
| Samsung Electronics       | 8         | 8      | 2.75%   |
| A-DATA Technology         | 7         | 7      | 2.41%   |
| Fujitsu                   | 5         | 5      | 1.72%   |
| SanDisk                   | 4         | 4      | 1.37%   |
| LITEON                    | 4         | 4      | 1.37%   |
| Maxtor                    | 3         | 3      | 1.03%   |
| China                     | 3         | 3      | 1.03%   |
| Crucial                   | 2         | 2      | 0.69%   |
| Micron/Crucial Technology | 1         | 2      | 0.34%   |
| Micron Technology         | 1         | 1      | 0.34%   |
| Intel                     | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 89        | 123    | 35.18%  |
| WDC                 | 57        | 69     | 22.53%  |
| Toshiba             | 37        | 49     | 14.62%  |
| Hitachi             | 37        | 40     | 14.62%  |
| HGST                | 18        | 20     | 7.11%   |
| Samsung Electronics | 7         | 7      | 2.77%   |
| Fujitsu             | 5         | 5      | 1.98%   |
| Maxtor              | 3         | 3      | 1.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 239       | 316    | 86.28%  |
| SSD  | 32        | 32     | 11.55%  |
| NVMe | 6         | 7      | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 16.67%  |
| Toshiba MK1234GSX 120GB           | 1         | 1      | 16.67%  |
| Seagate ST3500410AS 500GB         | 1         | 2      | 16.67%  |
| Seagate ST31500341AS 1TB          | 1         | 2      | 16.67%  |
| Samsung Electronics HD161GJ 160GB | 1         | 1      | 16.67%  |
| Hitachi HTS545016B9A300 160GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Toshiba             | 1         | 1      | 20%     |
| Seagate             | 1         | 4      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1659      | 2875   | 58.52%  |
| Works    | 900       | 1496   | 31.75%  |
| Malfunc  | 271       | 355    | 9.56%   |
| Failed   | 5         | 8      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1643      | 53.94%  |
| AMD                                     | 669       | 21.96%  |
| Samsung Electronics                     | 134       | 4.4%    |
| SanDisk                                 | 94        | 3.09%   |
| Nvidia                                  | 63        | 2.07%   |
| Kingston Technology Company             | 55        | 1.81%   |
| ADATA Technology                        | 53        | 1.74%   |
| SK hynix                                | 45        | 1.48%   |
| Realtek Semiconductor                   | 36        | 1.18%   |
| Phison Electronics                      | 29        | 0.95%   |
| Toshiba America Info Systems            | 28        | 0.92%   |
| Marvell Technology Group                | 24        | 0.79%   |
| Silicon Motion                          | 19        | 0.62%   |
| Micron Technology                       | 19        | 0.62%   |
| Micron/Crucial Technology               | 18        | 0.59%   |
| KIOXIA                                  | 18        | 0.59%   |
| Union Memory (Shenzhen)                 | 14        | 0.46%   |
| ASMedia Technology                      | 11        | 0.36%   |
| JMicron Technology                      | 10        | 0.33%   |
| Yangtze Memory Technologies             | 9         | 0.3%    |
| LSI Logic / Symbios Logic               | 9         | 0.3%    |
| MAXIO Technology (Hangzhou)             | 7         | 0.23%   |
| VIA Technologies                        | 5         | 0.16%   |
| Apple                                   | 5         | 0.16%   |
| Broadcom / LSI                          | 4         | 0.13%   |
| Silicon Image                           | 3         | 0.1%    |
| Lite-On Technology                      | 3         | 0.1%    |
| Hewlett-Packard                         | 3         | 0.1%    |
| Solid State Storage Technology          | 2         | 0.07%   |
| Seagate Technology                      | 2         | 0.07%   |
| Lenovo                                  | 2         | 0.07%   |
| INNOGRIT                                | 2         | 0.07%   |
| Solidigm                                | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| Broadcom                                | 1         | 0.03%   |
| Biwin Storage Technology                | 1         | 0.03%   |
| Adaptec                                 | 1         | 0.03%   |
| Unknown                                 | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 477       | 13.34%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 126       | 3.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 123       | 3.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 115       | 3.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 94        | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 73        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 71        | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 60        | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 59        | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 59        | 1.65%   |
| Intel SATA Controller [RAID mode]                                                       | 56        | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 55        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 50        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 50        | 1.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 48        | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 48        | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 47        | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 41        | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 41        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 41        | 1.15%   |
| AMD FCH SATA Controller D                                                               | 41        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 38        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 37        | 1.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 36        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 36        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 35        | 0.98%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 34        | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 32        | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 28        | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 27        | 0.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 27        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 26        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 25        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 25        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 25        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 25        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 25        | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 23        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1933      | 60.61%  |
| NVMe | 603       | 18.91%  |
| IDE  | 389       | 12.2%   |
| RAID | 250       | 7.84%   |
| SAS  | 12        | 0.38%   |
| SCSI | 2         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1832      | 69.24%  |
| AMD          | 807       | 30.5%   |
| ARM          | 4         | 0.15%   |
| Unknown      | 2         | 0.08%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 0.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 0.83%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 20        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 19        | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 19        | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.72%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 19        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 0.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 16        | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 14        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 14        | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 0.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 0.49%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 13        | 0.49%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 13        | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 12        | 0.45%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 12        | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.45%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 12        | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 12        | 0.45%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 12        | 0.45%   |
| AMD Ryzen 3 2300U with Radeon Vega Mobile Gfx | 12        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 476       | 17.96%  |
| Intel Core i7           | 389       | 14.68%  |
| Intel Celeron           | 229       | 8.64%   |
| Intel Core i3           | 214       | 8.08%   |
| AMD Ryzen 5             | 167       | 6.3%    |
| Other                   | 142       | 5.36%   |
| Intel Core 2 Duo        | 109       | 4.11%   |
| AMD Ryzen 7             | 96        | 3.62%   |
| Intel Atom              | 62        | 2.34%   |
| Intel Xeon              | 54        | 2.04%   |
| AMD A6                  | 54        | 2.04%   |
| Intel Pentium           | 52        | 1.96%   |
| AMD Ryzen 3             | 52        | 1.96%   |
| AMD A8                  | 48        | 1.81%   |
| AMD A4                  | 38        | 1.43%   |
| AMD FX                  | 35        | 1.32%   |
| AMD A10                 | 31        | 1.17%   |
| AMD Ryzen 9             | 30        | 1.13%   |
| AMD E                   | 30        | 1.13%   |
| AMD Athlon              | 30        | 1.13%   |
| Intel Pentium Dual-Core | 29        | 1.09%   |
| Intel Pentium Dual      | 28        | 1.06%   |
| Intel Core 2 Quad       | 16        | 0.6%    |
| AMD E1                  | 16        | 0.6%    |
| AMD Athlon II X2        | 16        | 0.6%    |
| Intel Core 2            | 15        | 0.57%   |
| AMD Athlon 64 X2        | 13        | 0.49%   |
| Intel Pentium 4         | 12        | 0.45%   |
| AMD Sempron             | 11        | 0.42%   |
| AMD Turion 64 X2 Mobile | 10        | 0.38%   |
| AMD Athlon II           | 10        | 0.38%   |
| Intel Genuine           | 9         | 0.34%   |
| AMD Ryzen 5 PRO         | 9         | 0.34%   |
| AMD Phenom II X4        | 9         | 0.34%   |
| Intel Pentium Silver    | 6         | 0.23%   |
| Intel Core i9           | 6         | 0.23%   |
| AMD Ryzen 3 PRO         | 6         | 0.23%   |
| AMD Phenom II X6        | 6         | 0.23%   |
| AMD E2                  | 6         | 0.23%   |
| AMD A12                 | 5         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1295      | 48.85%  |
| 4       | 820       | 30.93%  |
| 6       | 222       | 8.37%   |
| 1       | 128       | 4.83%   |
| 8       | 111       | 4.19%   |
| 12      | 21        | 0.79%   |
| 10      | 13        | 0.49%   |
| 16      | 11        | 0.41%   |
| 3       | 11        | 0.41%   |
| 14      | 8         | 0.3%    |
| 24      | 4         | 0.15%   |
| 28      | 3         | 0.11%   |
| Unknown | 2         | 0.08%   |
| 56      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2627      | 99.28%  |
| 2       | 18        | 0.68%   |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1597      | 60.26%  |
| 1       | 1050      | 39.62%  |
| Unknown | 2         | 0.08%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2583      | 97.43%  |
| Unknown        | 35        | 1.32%   |
| 32-bit         | 21        | 0.79%   |
| 64-bit         | 12        | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 770       | 27.87%  |
| 0x206a7    | 151       | 5.47%   |
| 0x306a9    | 116       | 4.2%    |
| 0x1067a    | 79        | 2.86%   |
| 0x306c3    | 67        | 2.42%   |
| 0x08108109 | 56        | 2.03%   |
| 0x40651    | 55        | 1.99%   |
| 0x30678    | 52        | 1.88%   |
| 0x806ec    | 50        | 1.81%   |
| 0x806e9    | 48        | 1.74%   |
| 0x806ea    | 43        | 1.56%   |
| 0x906ea    | 42        | 1.52%   |
| 0x306d4    | 42        | 1.52%   |
| 0x6fd      | 38        | 1.38%   |
| 0x506e3    | 37        | 1.34%   |
| 0x406e3    | 37        | 1.34%   |
| 0x806c1    | 36        | 1.3%    |
| 0x06006705 | 35        | 1.27%   |
| 0x406c4    | 34        | 1.23%   |
| 0x010000c8 | 33        | 1.19%   |
| 0x906e9    | 32        | 1.16%   |
| 0x20655    | 32        | 1.16%   |
| 0x06001119 | 31        | 1.12%   |
| 0x10676    | 30        | 1.09%   |
| 0x0810100b | 28        | 1.01%   |
| 0x406c3    | 26        | 0.94%   |
| 0x08600106 | 26        | 0.94%   |
| 0x07030105 | 24        | 0.87%   |
| 0x106ca    | 23        | 0.83%   |
| 0x0600611a | 23        | 0.83%   |
| 0x08608103 | 21        | 0.76%   |
| 0x08108102 | 21        | 0.76%   |
| 0x08101016 | 21        | 0.76%   |
| 0x0800820d | 20        | 0.72%   |
| 0x05000119 | 20        | 0.72%   |
| 0x706a1    | 19        | 0.69%   |
| 0x20652    | 19        | 0.69%   |
| 0x6fb      | 18        | 0.65%   |
| 0x0a50000d | 18        | 0.65%   |
| 0x506c9    | 17        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 322       | 12.16%  |
| SandyBridge      | 214       | 8.08%   |
| Haswell          | 180       | 6.8%    |
| IvyBridge        | 164       | 6.19%   |
| Silvermont       | 134       | 5.06%   |
| Penryn           | 131       | 4.95%   |
| Zen+             | 121       | 4.57%   |
| Skylake          | 112       | 4.23%   |
| Excavator        | 99        | 3.74%   |
| Core             | 91        | 3.44%   |
| Unknown          | 88        | 3.32%   |
| Zen 2            | 78        | 2.94%   |
| Zen              | 75        | 2.83%   |
| Westmere         | 69        | 2.6%    |
| Broadwell        | 68        | 2.57%   |
| K10              | 64        | 2.42%   |
| Zen 3            | 61        | 2.3%    |
| Piledriver       | 60        | 2.27%   |
| TigerLake        | 56        | 2.11%   |
| CometLake        | 52        | 1.96%   |
| Goldmont plus    | 48        | 1.81%   |
| K8 Hammer        | 42        | 1.59%   |
| Bobcat           | 42        | 1.59%   |
| Puma             | 40        | 1.51%   |
| Bonnell          | 39        | 1.47%   |
| IceLake          | 29        | 1.09%   |
| Goldmont         | 26        | 0.98%   |
| Alderlake Hybrid | 22        | 0.83%   |
| Steamroller      | 17        | 0.64%   |
| NetBurst         | 17        | 0.64%   |
| Nehalem          | 17        | 0.64%   |
| Jaguar           | 17        | 0.64%   |
| K10 Llano        | 13        | 0.49%   |
| Bulldozer        | 11        | 0.42%   |
| P6               | 10        | 0.38%   |
| Tremont          | 9         | 0.34%   |
| K8 & K10 hybrid  | 9         | 0.34%   |
| Gracemont        | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1554      | 52.13%  |
| AMD                              | 851       | 28.55%  |
| Nvidia                           | 553       | 18.55%  |
| Matrox Electronics Systems       | 14        | 0.47%   |
| VIA Technologies                 | 3         | 0.1%    |
| ASPEED Technology                | 3         | 0.1%    |
| ATI Technologies                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 175       | 5.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 96        | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 96        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 71        | 2.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 69        | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 65        | 2.1%    |
| Intel HD Graphics 620                                                                    | 57        | 1.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 57        | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 1.81%   |
| Intel HD Graphics 5500                                                                   | 54        | 1.74%   |
| Intel UHD Graphics 620                                                                   | 50        | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 50        | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 48        | 1.55%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 47        | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 46        | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 46        | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 44        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 1.39%   |
| Intel HD Graphics 530                                                                    | 38        | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 35        | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 35        | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 35        | 1.13%   |
| Intel HD Graphics 630                                                                    | 34        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.1%    |
| AMD Lucienne                                                                             | 32        | 1.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 30        | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 0.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 29        | 0.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 28        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 24        | 0.78%   |
| Intel HD Graphics 500                                                                    | 23        | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 21        | 0.68%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 20        | 0.65%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 19        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1255      | 47.15%  |
| 1 x AMD         | 712       | 26.75%  |
| 1 x Nvidia      | 292       | 10.97%  |
| Intel + Nvidia  | 209       | 7.85%   |
| Intel + AMD     | 53        | 1.99%   |
| 2 x AMD         | 49        | 1.84%   |
| AMD + Nvidia    | 41        | 1.54%   |
| 2 x Intel       | 13        | 0.49%   |
| 1 x Matrox      | 12        | 0.45%   |
| Other           | 9         | 0.34%   |
| 2 x Nvidia      | 7         | 0.26%   |
| 1 x ASPEED      | 3         | 0.11%   |
| 1 x VIA         | 2         | 0.08%   |
| Nvidia + Matrox | 2         | 0.08%   |
| 3 x AMD         | 1         | 0.04%   |
| 1 x SiS         | 1         | 0.04%   |
| Nvidia + VIA    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2335      | 87.42%  |
| Proprietary | 272       | 10.18%  |
| Unknown     | 64        | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1604      | 59.06%  |
| 0.01-0.5   | 391       | 14.4%   |
| 1.01-2.0   | 264       | 9.72%   |
| 0.51-1.0   | 217       | 7.99%   |
| 3.01-4.0   | 102       | 3.76%   |
| 7.01-8.0   | 60        | 2.21%   |
| 5.01-6.0   | 48        | 1.77%   |
| 2.01-3.0   | 18        | 0.66%   |
| 8.01-16.0  | 8         | 0.29%   |
| 16.01-24.0 | 4         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 328       | 11.4%   |
| AU Optronics            | 327       | 11.37%  |
| Samsung Electronics     | 310       | 10.78%  |
| Chimei Innolux          | 278       | 9.67%   |
| LG Display              | 254       | 8.83%   |
| Hewlett-Packard         | 206       | 7.16%   |
| Dell                    | 171       | 5.95%   |
| Goldstar                | 104       | 3.62%   |
| Apple                   | 85        | 2.96%   |
| BenQ                    | 79        | 2.75%   |
| Acer                    | 73        | 2.54%   |
| AOC                     | 59        | 2.05%   |
| Lenovo                  | 53        | 1.84%   |
| Chi Mei Optoelectronics | 44        | 1.53%   |
| Unknown                 | 39        | 1.36%   |
| Sony                    | 25        | 0.87%   |
| Sharp                   | 25        | 0.87%   |
| LG Philips              | 24        | 0.83%   |
| ASUSTek Computer        | 22        | 0.76%   |
| Ancor Communications    | 22        | 0.76%   |
| PANDA                   | 21        | 0.73%   |
| Gateway                 | 20        | 0.7%    |
| ViewSonic               | 19        | 0.66%   |
| InfoVision              | 15        | 0.52%   |
| HannStar                | 12        | 0.42%   |
| ___                     | 10        | 0.35%   |
| VOR                     | 9         | 0.31%   |
| Valve                   | 8         | 0.28%   |
| Insignia                | 8         | 0.28%   |
| FOX                     | 8         | 0.28%   |
| LG Electronics          | 7         | 0.24%   |
| HUAWEI                  | 7         | 0.24%   |
| Hitachi                 | 7         | 0.24%   |
| CSO                     | 7         | 0.24%   |
| Unknown                 | 7         | 0.24%   |
| Vizio                   | 6         | 0.21%   |
| Unknown (AAA)           | 6         | 0.21%   |
| Toshiba                 | 6         | 0.21%   |
| Sceptre Tech            | 6         | 0.21%   |
| SAC                     | 6         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 22        | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 17        | 0.58%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                 | 17        | 0.58%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 16        | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 15        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 15        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 15        | 0.51%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 15        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 14        | 0.48%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 13        | 0.44%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 13        | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 13        | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 12        | 0.41%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 12        | 0.41%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.38%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch           | 11        | 0.38%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 11        | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 10        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 10        | 0.34%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 9         | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 0.31%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 9         | 0.31%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 9         | 0.31%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 9         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 8         | 0.27%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 7         | 0.24%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 7         | 0.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 7         | 0.24%   |
| Insignia NS19D220NA16A BBY0019 1680x1050 640x384mm 29.4-inch         | 7         | 0.24%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 7         | 0.24%   |
| FOX FBC TV FOX9C01 1366x768 698x393mm 31.5-inch                      | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch      | 7         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 961       | 34.95%  |
| 1920x1080 (FHD)    | 902       | 32.8%   |
| 1600x900 (HD+)     | 119       | 4.33%   |
| 1280x800 (WXGA)    | 108       | 3.93%   |
| 1440x900 (WXGA+)   | 99        | 3.6%    |
| 3840x2160 (4K)     | 84        | 3.05%   |
| 1280x1024 (SXGA)   | 82        | 2.98%   |
| 1680x1050 (WSXGA+) | 38        | 1.38%   |
| 2560x1440 (QHD)    | 37        | 1.35%   |
| 1360x768           | 31        | 1.13%   |
| 2560x1080          | 27        | 0.98%   |
| 1024x768 (XGA)     | 27        | 0.98%   |
| 1024x600           | 27        | 0.98%   |
| 1920x1200 (WUXGA)  | 23        | 0.84%   |
| 2560x1600          | 22        | 0.8%    |
| 3440x1440          | 21        | 0.76%   |
| Unknown            | 21        | 0.76%   |
| 2160x1440          | 19        | 0.69%   |
| 800x1280           | 9         | 0.33%   |
| 3840x1080          | 9         | 0.33%   |
| 2288x1287          | 9         | 0.33%   |
| 2880x1800          | 8         | 0.29%   |
| 1600x1200          | 8         | 0.29%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 3000x2000          | 5         | 0.18%   |
| 2736x1824          | 5         | 0.18%   |
| 1280x960           | 5         | 0.18%   |
| 3840x2400          | 4         | 0.15%   |
| 2520x1680          | 3         | 0.11%   |
| 3600x1080          | 2         | 0.07%   |
| 3360x1080          | 2         | 0.07%   |
| 2256x1504          | 2         | 0.07%   |
| 2240x1400          | 2         | 0.07%   |
| 1920x540           | 2         | 0.07%   |
| 1400x1050          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 1152x864           | 2         | 0.07%   |
| 7280x2160          | 1         | 0.04%   |
| 6720x1440          | 1         | 0.04%   |
| 6000x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 739       | 25.83%  |
| 13      | 390       | 13.63%  |
| 14      | 306       | 10.7%   |
| 21      | 153       | 5.35%   |
| 23      | 135       | 4.72%   |
| 19      | 114       | 3.98%   |
| 18      | 114       | 3.98%   |
| 17      | 108       | 3.77%   |
| 24      | 105       | 3.67%   |
| 27      | 102       | 3.57%   |
| Unknown | 88        | 3.08%   |
| 20      | 76        | 2.66%   |
| 11      | 66        | 2.31%   |
| 31      | 44        | 1.54%   |
| 12      | 42        | 1.47%   |
| 34      | 41        | 1.43%   |
| 16      | 34        | 1.19%   |
| 22      | 29        | 1.01%   |
| 10      | 27        | 0.94%   |
| 72      | 23        | 0.8%    |
| 84      | 19        | 0.66%   |
| 40      | 14        | 0.49%   |
| 54      | 11        | 0.38%   |
| 32      | 9         | 0.31%   |
| 29      | 8         | 0.28%   |
| 7       | 8         | 0.28%   |
| 26      | 7         | 0.24%   |
| 142     | 6         | 0.21%   |
| 46      | 5         | 0.17%   |
| 25      | 5         | 0.17%   |
| 52      | 4         | 0.14%   |
| 39      | 4         | 0.14%   |
| 8       | 4         | 0.14%   |
| 48      | 3         | 0.1%    |
| 49      | 2         | 0.07%   |
| 42      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 86      | 1         | 0.03%   |
| 74      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1329      | 47.06%  |
| 401-500        | 437       | 15.47%  |
| 501-600        | 334       | 11.83%  |
| 201-300        | 277       | 9.81%   |
| 351-400        | 131       | 4.64%   |
| Unknown        | 88        | 3.12%   |
| 601-700        | 59        | 2.09%   |
| 701-800        | 52        | 1.84%   |
| 1501-2000      | 43        | 1.52%   |
| 1001-1500      | 30        | 1.06%   |
| 801-900        | 21        | 0.74%   |
| 1-100          | 9         | 0.32%   |
| More than 2000 | 6         | 0.21%   |
| 101-200        | 4         | 0.14%   |
| 901-1000       | 4         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1983      | 76.39%  |
| 16/10   | 309       | 11.9%   |
| 5/4     | 81        | 3.12%   |
| Unknown | 69        | 2.66%   |
| 4/3     | 46        | 1.77%   |
| 21/9    | 44        | 1.69%   |
| 3/2     | 38        | 1.46%   |
| 0.67    | 8         | 0.31%   |
| 1.00    | 7         | 0.27%   |
| 6/5     | 4         | 0.15%   |
| 32/9    | 3         | 0.12%   |
| 0.62    | 2         | 0.08%   |
| 0.56    | 2         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 756       | 26.69%  |
| 81-90          | 612       | 21.6%   |
| 201-250        | 344       | 12.14%  |
| 151-200        | 238       | 8.4%    |
| 141-150        | 149       | 5.26%   |
| 301-350        | 107       | 3.78%   |
| 351-500        | 94        | 3.32%   |
| 71-80          | 88        | 3.11%   |
| Unknown        | 88        | 3.11%   |
| More than 1000 | 71        | 2.51%   |
| 51-60          | 66        | 2.33%   |
| 121-130        | 43        | 1.52%   |
| 251-300        | 34        | 1.2%    |
| 61-70          | 33        | 1.16%   |
| 501-1000       | 33        | 1.16%   |
| 41-50          | 27        | 0.95%   |
| 111-120        | 18        | 0.64%   |
| 131-140        | 15        | 0.53%   |
| 1-40           | 13        | 0.46%   |
| 91-100         | 4         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1022      | 37.03%  |
| 51-100        | 832       | 30.14%  |
| 121-160       | 575       | 20.83%  |
| 161-240       | 117       | 4.24%   |
| 1-50          | 89        | 3.22%   |
| Unknown       | 88        | 3.19%   |
| More than 240 | 37        | 1.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2186      | 80.6%   |
| 2     | 402       | 14.82%  |
| 0     | 83        | 3.06%   |
| 3     | 38        | 1.4%    |
| 4     | 3         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1561      | 39.13%  |
| Intel                                 | 981       | 24.59%  |
| Qualcomm Atheros                      | 502       | 12.58%  |
| Broadcom                              | 302       | 7.57%   |
| Ralink Technology                     | 78        | 1.96%   |
| Ralink                                | 71        | 1.78%   |
| Broadcom Limited                      | 66        | 1.65%   |
| TP-Link                               | 58        | 1.45%   |
| Nvidia                                | 54        | 1.35%   |
| Marvell Technology Group              | 49        | 1.23%   |
| MediaTek                              | 37        | 0.93%   |
| Qualcomm Atheros Communications       | 33        | 0.83%   |
| ASIX Electronics                      | 21        | 0.53%   |
| Huawei Technologies                   | 20        | 0.5%    |
| Mercucys                              | 13        | 0.33%   |
| Motorola PCS                          | 12        | 0.3%    |
| DisplayLink                           | 12        | 0.3%    |
| Samsung Electronics                   | 11        | 0.28%   |
| Xiaomi                                | 10        | 0.25%   |
| Qualcomm                              | 6         | 0.15%   |
| Linksys                               | 6         | 0.15%   |
| ICS Advent                            | 6         | 0.15%   |
| D-Link                                | 6         | 0.15%   |
| VIA Technologies                      | 4         | 0.1%    |
| Spreadtrum Communications             | 4         | 0.1%    |
| OPPO Electronics                      | 4         | 0.1%    |
| Lenovo                                | 4         | 0.1%    |
| Google                                | 4         | 0.1%    |
| Dell                                  | 4         | 0.1%    |
| D-Link System                         | 4         | 0.1%    |
| NetGear                               | 3         | 0.08%   |
| Microchip Technology                  | 3         | 0.08%   |
| IBM                                   | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.05%   |
| Wacom                                 | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| LG Electronics                        | 2         | 0.05%   |
| JMicron Technology                    | 2         | 0.05%   |
| Tenda                                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 907       | 18.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 334       | 6.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 114       | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 106       | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 85        | 1.78%   |
| Intel Wi-Fi 6 AX200                                               | 76        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 68        | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 67        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 64        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63        | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 56        | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 54        | 1.13%   |
| Intel Wireless 8265 / 8275                                        | 51        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                     | 49        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 0.96%   |
| Intel Wireless 7265                                               | 46        | 0.96%   |
| Intel Wi-Fi 6 AX201                                               | 46        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 40        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 39        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 37        | 0.77%   |
| Intel Wireless 7260                                               | 36        | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 34        | 0.71%   |
| Intel Wireless 8260                                               | 34        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 0.71%   |
| Intel I211 Gigabit Network Connection                             | 33        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 32        | 0.67%   |
| Intel Wireless 3165                                               | 30        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 29        | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                   | 28        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 26        | 0.54%   |
| Realtek 802.11ac NIC                                              | 25        | 0.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 24        | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 23        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 716       | 30.98%  |
| Realtek Semiconductor                 | 587       | 25.4%   |
| Qualcomm Atheros                      | 420       | 18.17%  |
| Broadcom                              | 222       | 9.61%   |
| Ralink Technology                     | 78        | 3.38%   |
| Ralink                                | 71        | 3.07%   |
| TP-Link                               | 56        | 2.42%   |
| Broadcom Limited                      | 44        | 1.9%    |
| Qualcomm Atheros Communications       | 33        | 1.43%   |
| MediaTek                              | 32        | 1.38%   |
| Mercucys                              | 13        | 0.56%   |
| Marvell Technology Group              | 6         | 0.26%   |
| D-Link                                | 6         | 0.26%   |
| Linksys                               | 4         | 0.17%   |
| Qualcomm                              | 3         | 0.13%   |
| NetGear                               | 3         | 0.13%   |
| Dell                                  | 3         | 0.13%   |
| D-Link System                         | 3         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.13%   |
| Wacom                                 | 2         | 0.09%   |
| Tenda                                 | 1         | 0.04%   |
| Qualcomm Technologies                 | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 114       | 4.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 85        | 3.63%   |
| Intel Wi-Fi 6 AX200                                                     | 76        | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 68        | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 67        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 64        | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 63        | 2.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 56        | 2.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 54        | 2.31%   |
| Intel Wireless 8265 / 8275                                              | 51        | 2.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 49        | 2.09%   |
| Intel Wireless 7265                                                     | 46        | 1.96%   |
| Intel Wi-Fi 6 AX201                                                     | 46        | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 40        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 39        | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 37        | 1.58%   |
| Intel Wireless 7260                                                     | 36        | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 34        | 1.45%   |
| Intel Wireless 8260                                                     | 34        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 34        | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 32        | 1.37%   |
| Intel Wireless 3165                                                     | 30        | 1.28%   |
| Ralink MT7601U Wireless Adapter                                         | 29        | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                         | 28        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 26        | 1.11%   |
| Realtek 802.11ac NIC                                                    | 25        | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 24        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 23        | 0.98%   |
| Intel Wireless 3160                                                     | 22        | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 22        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 20        | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 19        | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 19        | 0.81%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 19        | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 17        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1331      | 55.97%  |
| Intel                                  | 517       | 21.74%  |
| Qualcomm Atheros                       | 146       | 6.14%   |
| Broadcom                               | 128       | 5.38%   |
| Nvidia                                 | 54        | 2.27%   |
| Marvell Technology Group               | 43        | 1.81%   |
| Broadcom Limited                       | 22        | 0.93%   |
| ASIX Electronics                       | 21        | 0.88%   |
| Huawei Technologies                    | 19        | 0.8%    |
| DisplayLink                            | 12        | 0.5%    |
| Xiaomi                                 | 10        | 0.42%   |
| Motorola PCS                           | 8         | 0.34%   |
| ICS Advent                             | 6         | 0.25%   |
| Samsung Electronics                    | 5         | 0.21%   |
| MediaTek                               | 5         | 0.21%   |
| VIA Technologies                       | 4         | 0.17%   |
| Spreadtrum Communications              | 4         | 0.17%   |
| OPPO Electronics                       | 4         | 0.17%   |
| Google                                 | 4         | 0.17%   |
| Qualcomm                               | 3         | 0.13%   |
| Lenovo                                 | 3         | 0.13%   |
| IBM                                    | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.08%   |
| TP-Link                                | 2         | 0.08%   |
| Microchip Technology                   | 2         | 0.08%   |
| Linksys                                | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| JMicron Technology                     | 2         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| Lab126                                 | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Hisense                                | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Emulex                                 | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 907       | 37.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 334       | 13.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 106       | 4.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 1.62%   |
| Intel I211 Gigabit Network Connection                             | 33        | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22        | 0.91%   |
| Nvidia MCP61 Ethernet                                             | 22        | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.7%    |
| Huawei MAR-LX1M                                                   | 17        | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 15        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13        | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 12        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 10        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2256      | 50.55%  |
| WiFi     | 2179      | 48.82%  |
| Modem    | 18        | 0.4%    |
| Unknown  | 10        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1708      | 61.2%   |
| Ethernet | 1081      | 38.73%  |
| Unknown  | 2         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1540      | 58.05%  |
| 1     | 1029      | 38.79%  |
| 0     | 48        | 1.81%   |
| 3     | 23        | 0.87%   |
| 4     | 6         | 0.23%   |
| 8     | 3         | 0.11%   |
| 6     | 3         | 0.11%   |
| 5     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1826      | 67.03%  |
| Yes  | 898       | 32.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 547       | 34.06%  |
| Realtek Semiconductor           | 276       | 17.19%  |
| Qualcomm Atheros Communications | 141       | 8.78%   |
| Cambridge Silicon Radio         | 115       | 7.16%   |
| Broadcom                        | 99        | 6.16%   |
| Apple                           | 77        | 4.79%   |
| IMC Networks                    | 62        | 3.86%   |
| Lite-On Technology              | 61        | 3.8%    |
| Foxconn / Hon Hai               | 45        | 2.8%    |
| Realtek                         | 32        | 1.99%   |
| Dell                            | 32        | 1.99%   |
| Hewlett-Packard                 | 24        | 1.49%   |
| Toshiba                         | 19        | 1.18%   |
| Ralink                          | 19        | 1.18%   |
| ASUSTek Computer                | 14        | 0.87%   |
| MediaTek                        | 8         | 0.5%    |
| Ralink Technology               | 7         | 0.44%   |
| TP-Link                         | 6         | 0.37%   |
| Marvell Semiconductor           | 6         | 0.37%   |
| Foxconn International           | 4         | 0.25%   |
| Alps Electric                   | 4         | 0.25%   |
| USI                             | 1         | 0.06%   |
| Roper                           | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Dynex                           | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 211       | 13.12%  |
| Realtek Bluetooth Radio                                                             | 135       | 8.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 115       | 7.15%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 110       | 6.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 97        | 6.03%   |
| Intel AX201 Bluetooth                                                               | 90        | 5.6%    |
| Intel AX200 Bluetooth                                                               | 74        | 4.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 69        | 4.29%   |
| Apple Bluetooth Host Controller                                                     | 35        | 2.18%   |
| Realtek 802.11ac WLAN Adapter                                                       | 32        | 1.99%   |
| IMC Networks Bluetooth Radio                                                        | 31        | 1.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 29        | 1.8%    |
| Apple Bluetooth USB Host Controller                                                 | 23        | 1.43%   |
| Lite-On Bluetooth Device                                                            | 22        | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 20        | 1.24%   |
| Ralink RT3290 Bluetooth                                                             | 19        | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 18        | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 18        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 1.12%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 16        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 14        | 0.87%   |
| Intel Bluetooth Device                                                              | 14        | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 11        | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 11        | 0.68%   |
| IMC Networks Wireless_Device                                                        | 10        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.62%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 0.56%   |
| IMC Networks Bluetooth Device                                                       | 9         | 0.56%   |
| MediaTek Wireless_Device                                                            | 8         | 0.5%    |
| Intel AX210 Bluetooth                                                               | 8         | 0.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.5%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.5%    |
| Apple Bluetooth HCI                                                                 | 8         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1762      | 53.88%  |
| AMD                                          | 856       | 26.18%  |
| Nvidia                                       | 427       | 13.06%  |
| C-Media Electronics                          | 31        | 0.95%   |
| Logitech                                     | 22        | 0.67%   |
| Generalplus Technology                       | 17        | 0.52%   |
| Texas Instruments                            | 16        | 0.49%   |
| Realtek Semiconductor                        | 9         | 0.28%   |
| Creative Labs                                | 9         | 0.28%   |
| Kingston Technology                          | 8         | 0.24%   |
| JMTek                                        | 8         | 0.24%   |
| GN Netcom                                    | 7         | 0.21%   |
| ASUSTek Computer                             | 7         | 0.21%   |
| VIA Technologies                             | 6         | 0.18%   |
| Razer USA                                    | 6         | 0.18%   |
| Plantronics                                  | 6         | 0.18%   |
| Corsair                                      | 6         | 0.18%   |
| Tenx Technology                              | 5         | 0.15%   |
| Lenovo                                       | 5         | 0.15%   |
| Syntek                                       | 4         | 0.12%   |
| Focusrite-Novation                           | 4         | 0.12%   |
| Creative Technology                          | 4         | 0.12%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.06%   |
| Synaptics                                    | 2         | 0.06%   |
| SAVITECH                                     | 2         | 0.06%   |
| Samson Technologies                          | 2         | 0.06%   |
| Microsoft                                    | 2         | 0.06%   |
| M-Audio                                      | 2         | 0.06%   |
| BR25                                         | 2         | 0.06%   |
| ATI Technologies                             | 2         | 0.06%   |
| Apple                                        | 2         | 0.06%   |
| Anlya.cn                                     | 2         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.03%   |
| Shure                                        | 1         | 0.03%   |
| Sennheiser Communications                    | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 263       | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 191       | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 170       | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 167       | 4.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 150       | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 148       | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 117       | 2.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 106       | 2.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 100       | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 96        | 2.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 96        | 2.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 95        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 79        | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 75        | 1.83%   |
| Intel 8 Series HD Audio Controller                                                                | 72        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 71        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 71        | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 71        | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 64        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 63        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 61        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 58        | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 57        | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 56        | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 51        | 1.24%   |
| AMD High Definition Audio Controller                                                              | 50        | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 48        | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 40        | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 40        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 37        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 36        | 0.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 30        | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 28        | 0.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                                                | 27        | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 27        | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 27        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 370       | 22.73%  |
| SK hynix                                         | 281       | 17.26%  |
| Kingston                                         | 261       | 16.03%  |
| Micron Technology                                | 180       | 11.06%  |
| A-DATA Technology                                | 130       | 7.99%   |
| Unknown                                          | 126       | 7.74%   |
| Corsair                                          | 45        | 2.76%   |
| Ramaxel Technology                               | 43        | 2.64%   |
| Crucial                                          | 34        | 2.09%   |
| Elpida                                           | 28        | 1.72%   |
| Nanya Technology                                 | 23        | 1.41%   |
| Unknown (ABCD)                                   | 15        | 0.92%   |
| Team                                             | 14        | 0.86%   |
| Patriot                                          | 9         | 0.55%   |
| Qimonda                                          | 7         | 0.43%   |
| PNY                                              | 7         | 0.43%   |
| Unknown                                          | 7         | 0.43%   |
| G.Skill                                          | 6         | 0.37%   |
| Timetec                                          | 5         | 0.31%   |
| ChangXin Memory                                  | 5         | 0.31%   |
| Transcend                                        | 4         | 0.25%   |
| Hewlett-Packard                                  | 2         | 0.12%   |
| CSX                                              | 2         | 0.12%   |
| Avant                                            | 2         | 0.12%   |
| Unknown (8A6B)                                   | 1         | 0.06%   |
| Unknown (0x8AF1)                                 | 1         | 0.06%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.06%   |
| Unknown (0x29E)                                  | 1         | 0.06%   |
| Unknown (0x0E9D)                                 | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Silicon Power                                    | 1         | 0.06%   |
| SHARETRONIC                                      | 1         | 0.06%   |
| SGS/Thomson                                      | 1         | 0.06%   |
| S                                                | 1         | 0.06%   |
| Patriot Memory                                   | 1         | 0.06%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER                   | 1         | 0.06%   |
| Goldkey                                          | 1         | 0.06%   |
| Gigabyte Technology                              | 1         | 0.06%   |
| ff                                               | 1         | 0.06%   |
| ASint Technology                                 | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 1.02%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 18        | 1.02%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 17        | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.79%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 0.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.62%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 11        | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.57%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 10        | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.45%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 8         | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 7         | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.4%    |
| Unknown                                                          | 7         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 6         | 0.34%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 6         | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 6         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.34%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 6         | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.34%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 6         | 0.34%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 563       | 41.8%   |
| DDR3    | 508       | 37.71%  |
| DDR2    | 91        | 6.76%   |
| LPDDR4  | 46        | 3.41%   |
| SDRAM   | 44        | 3.27%   |
| LPDDR3  | 29        | 2.15%   |
| Unknown | 28        | 2.08%   |
| DDR5    | 14        | 1.04%   |
| DDR     | 13        | 0.97%   |
| LPDDR5  | 9         | 0.67%   |
| RAM     | 1         | 0.07%   |
| DRAM    | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 800       | 60.02%  |
| DIMM         | 406       | 30.46%  |
| Row Of Chips | 116       | 8.7%    |
| Chip         | 5         | 0.38%   |
| Unknown      | 3         | 0.23%   |
| RIMM         | 2         | 0.15%   |
| FB-DIMM      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 539       | 35.23%  |
| 4096  | 468       | 30.59%  |
| 2048  | 236       | 15.42%  |
| 16384 | 145       | 9.48%   |
| 1024  | 70        | 4.58%   |
| 32768 | 58        | 3.79%   |
| 512   | 8         | 0.52%   |
| 256   | 2         | 0.13%   |
| 65536 | 1         | 0.07%   |
| 32767 | 1         | 0.07%   |
| 12288 | 1         | 0.07%   |
| 128   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 345       | 23.08%  |
| 2667    | 210       | 14.05%  |
| 3200    | 175       | 11.71%  |
| 1333    | 109       | 7.29%   |
| 2400    | 89        | 5.95%   |
| 2133    | 72        | 4.82%   |
| 667     | 51        | 3.41%   |
| 1334    | 48        | 3.21%   |
| 3600    | 44        | 2.94%   |
| 800     | 37        | 2.47%   |
| Unknown | 31        | 2.07%   |
| 3266    | 25        | 1.67%   |
| 1067    | 21        | 1.4%    |
| 4267    | 19        | 1.27%   |
| 1867    | 19        | 1.27%   |
| 3733    | 18        | 1.2%    |
| 1866    | 14        | 0.94%   |
| 533     | 13        | 0.87%   |
| 2048    | 12        | 0.8%    |
| 1066    | 12        | 0.8%    |
| 4800    | 9         | 0.6%    |
| 6400    | 8         | 0.54%   |
| 2933    | 8         | 0.54%   |
| 2800    | 8         | 0.54%   |
| 975     | 8         | 0.54%   |
| 3400    | 7         | 0.47%   |
| 3000    | 7         | 0.47%   |
| 4199    | 6         | 0.4%    |
| 3466    | 6         | 0.4%    |
| 2666    | 6         | 0.4%    |
| 8400    | 5         | 0.33%   |
| 49926   | 4         | 0.27%   |
| 5600    | 4         | 0.27%   |
| 3933    | 4         | 0.27%   |
| 1800    | 4         | 0.27%   |
| 1331    | 4         | 0.27%   |
| 3800    | 3         | 0.2%    |
| 2200    | 3         | 0.2%    |
| 1639    | 3         | 0.2%    |
| 400     | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 16        | 25.4%   |
| Hewlett-Packard        | 15        | 23.81%  |
| Brother Industries     | 13        | 20.63%  |
| Samsung Electronics    | 7         | 11.11%  |
| Canon                  | 7         | 11.11%  |
| Kyocera                | 2         | 3.17%   |
| TSC Auto ID Technology | 1         | 1.59%   |
| QinHeng Electronics    | 1         | 1.59%   |
| BIXOLON                | 1         | 1.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 9.38%   |
| HP DeskJet 1110 series                  | 3         | 4.69%   |
| Samsung M2020 Series                    | 2         | 3.13%   |
| HP LaserJet Professional P 1102w        | 2         | 3.13%   |
| HP DeskJet 2300 series                  | 2         | 3.13%   |
| Canon G3000 series                      | 2         | 3.13%   |
| Brother MFC-J470DW                      | 2         | 3.13%   |
| Brother HL-1110 series                  | 2         | 3.13%   |
| TSC Auto ID Printer                     | 1         | 1.56%   |
| Seiko Epson XP-235 Series               | 1         | 1.56%   |
| Seiko Epson Printer                     | 1         | 1.56%   |
| Seiko Epson L805 Series                 | 1         | 1.56%   |
| Seiko Epson L6160 Series                | 1         | 1.56%   |
| Seiko Epson L555 Series                 | 1         | 1.56%   |
| Seiko Epson L382 Series                 | 1         | 1.56%   |
| Seiko Epson L300 Series                 | 1         | 1.56%   |
| Seiko Epson L210 Series                 | 1         | 1.56%   |
| Seiko Epson L200 Series                 | 1         | 1.56%   |
| Seiko Epson L1300 Series                | 1         | 1.56%   |
| Seiko Epson ET-2700 Series              | 1         | 1.56%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.56%   |
| Samsung SCX-4600 Series                 | 1         | 1.56%   |
| Samsung ML-1660 Series                  | 1         | 1.56%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 1.56%   |
| Samsung M283x Series                    | 1         | 1.56%   |
| QinHeng CH340S                          | 1         | 1.56%   |
| Kyocera FS-1116MFP                      | 1         | 1.56%   |
| Kyocera FS-1030D printer                | 1         | 1.56%   |
| HP OfficeJet Pro 7740 series            | 1         | 1.56%   |
| HP LaserJet P3010 Series                | 1         | 1.56%   |
| HP DeskJet F4200 series                 | 1         | 1.56%   |
| HP DeskJet F300 series                  | 1         | 1.56%   |
| HP DeskJet 4720 series                  | 1         | 1.56%   |
| HP DeskJet 3700 series                  | 1         | 1.56%   |
| HP DeskJet 2620 All-in-One Printer      | 1         | 1.56%   |
| HP Deskjet 2540 series                  | 1         | 1.56%   |
| Canon PIXMA MG3500 Series               | 1         | 1.56%   |
| Canon PIXMA iP3000x Printer             | 1         | 1.56%   |
| Canon iP2600 series                     | 1         | 1.56%   |
| Canon G2010 series                      | 1         | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 5         | 83.33%  |
| Seiko Epson     | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                    | 2         | 33.33%  |
| HP ScanJet 4500C/5550C                             | 2         | 33.33%  |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1         | 16.67%  |
| HP ScanJet 3300c                                   | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 377       | 21.28%  |
| Microdia                               | 163       | 9.2%    |
| IMC Networks                           | 161       | 9.09%   |
| Realtek Semiconductor                  | 119       | 6.72%   |
| Cheng Uei Precision Industry (Foxlink) | 91        | 5.14%   |
| Sunplus Innovation Technology          | 86        | 4.85%   |
| Bison Electronics                      | 86        | 4.85%   |
| Quanta                                 | 78        | 4.4%    |
| Suyin                                  | 72        | 4.06%   |
| Apple                                  | 64        | 3.61%   |
| Logitech                               | 62        | 3.5%    |
| Syntek                                 | 56        | 3.16%   |
| Lite-On Technology                     | 45        | 2.54%   |
| Generalplus Technology                 | 26        | 1.47%   |
| Silicon Motion                         | 23        | 1.3%    |
| Ricoh                                  | 23        | 1.3%    |
| Alcor Micro                            | 18        | 1.02%   |
| Acer                                   | 18        | 1.02%   |
| Importek                               | 17        | 0.96%   |
| Luxvisions Innotech Limited            | 14        | 0.79%   |
| Microsoft                              | 13        | 0.73%   |
| Samsung Electronics                    | 11        | 0.62%   |
| Jieli Technology                       | 11        | 0.62%   |
| Z-Star Microelectronics                | 9         | 0.51%   |
| Primax Electronics                     | 9         | 0.51%   |
| Y Media                                | 8         | 0.45%   |
| Sonix Technology                       | 8         | 0.45%   |
| GEMBIRD                                | 8         | 0.45%   |
| ALi                                    | 8         | 0.45%   |
| OmniVision Technologies                | 7         | 0.4%    |
| HRY                                    | 6         | 0.34%   |
| Genesys Logic                          | 6         | 0.34%   |
| KYE Systems (Mouse Systems)            | 5         | 0.28%   |
| MacroSilicon                           | 4         | 0.23%   |
| LG Electronics                         | 4         | 0.23%   |
| Lenovo                                 | 4         | 0.23%   |
| icSpring                               | 4         | 0.23%   |
| Xiongmai                               | 3         | 0.17%   |
| SunplusIT                              | 3         | 0.17%   |
| Sunplus Technology                     | 3         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 53        | 2.97%   |
| Microdia Integrated_Webcam_HD                                  | 52        | 2.91%   |
| Chicony HD WebCam                                              | 36        | 2.02%   |
| IMC Networks Integrated Camera                                 | 35        | 1.96%   |
| Bison Integrated Camera                                        | 33        | 1.85%   |
| Realtek Integrated_Webcam_HD                                   | 30        | 1.68%   |
| Sunplus Integrated_Webcam_HD                                   | 27        | 1.51%   |
| IMC Networks HD Camera                                         | 25        | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 24        | 1.34%   |
| Chicony HP Webcam                                              | 23        | 1.29%   |
| Logitech HD Pro Webcam C920                                    | 22        | 1.23%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 22        | 1.23%   |
| Generalplus GENERAL WEBCAM                                     | 22        | 1.23%   |
| Syntek Integrated Camera                                       | 21        | 1.18%   |
| Chicony HP TrueVision HD Camera                                | 21        | 1.18%   |
| Apple FaceTime HD Camera                                       | 21        | 1.18%   |
| Quanta HP Webcam                                               | 18        | 1.01%   |
| Lite-On HP Wide Vision HD Camera                               | 18        | 1.01%   |
| Chicony HP Truevision HD                                       | 18        | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 18        | 1.01%   |
| Microdia Integrated Webcam                                     | 17        | 0.95%   |
| Syntek Lenovo EasyCamera                                       | 15        | 0.84%   |
| IMC Networks EasyCamera                                        | 15        | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 14        | 0.78%   |
| Apple Built-in iSight                                          | 14        | 0.78%   |
| Sunplus HD WebCam                                              | 13        | 0.73%   |
| Logitech Webcam C270                                           | 13        | 0.73%   |
| IMC Networks ov9734_azurewave_camera                           | 13        | 0.73%   |
| Bison EasyCamera                                               | 13        | 0.73%   |
| Apple FaceTime HD Camera (Built-in)                            | 13        | 0.73%   |
| Realtek USB Camera                                             | 12        | 0.67%   |
| Microdia Lenovo EasyCamera                                     | 12        | 0.67%   |
| Chicony USB 2.0 Camera                                         | 12        | 0.67%   |
| Chicony HP Wide Vision HD Camera                               | 12        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 11        | 0.62%   |
| Quanta HP TrueVision HD Camera                                 | 11        | 0.62%   |
| Jieli USB PHY 2.0                                              | 11        | 0.62%   |
| Chicony HP HD Camera                                           | 11        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 11        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 11        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 95        | 32.09%  |
| Shenzhen Goodix Technology         | 74        | 25%     |
| Synaptics                          | 49        | 16.55%  |
| AuthenTec                          | 24        | 8.11%   |
| Upek                               | 18        | 6.08%   |
| Elan Microelectronics              | 13        | 4.39%   |
| Focal-systems.Corp                 | 8         | 2.7%    |
| STMicroelectronics                 | 5         | 1.69%   |
| LighTuning Technology              | 4         | 1.35%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.68%   |
| Suprema                            | 1         | 0.34%   |
| Samsung Electronics                | 1         | 0.34%   |
| GDMicroelectronics                 | 1         | 0.34%   |
| DigitalPersona                     | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 64        | 21.62%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 7.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 5.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 4.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 3.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.04%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 8         | 2.7%    |
| Elan ELAN:Fingerprint                                                      | 7         | 2.36%   |
| Validity Sensors VFS491                                                    | 6         | 2.03%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.03%   |
| AuthenTec AES2810                                                          | 6         | 2.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.69%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.35%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.01%   |
| Synaptics WBDI                                                             | 3         | 1.01%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.01%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.01%   |
| AuthenTec AES1600                                                          | 3         | 1.01%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.68%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.68%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.68%   |
| Synaptics UWP WBDI                                                         | 2         | 0.68%   |
| Synaptics  WBDI                                                            | 2         | 0.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.68%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.68%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.34%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.34%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.34%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 51        | 64.56%  |
| Alcor Micro           | 13        | 16.46%  |
| Upek                  | 7         | 8.86%   |
| Lenovo                | 6         | 7.59%   |
| O2 Micro              | 1         | 1.27%   |
| Gemalto (was Gemplus) | 1         | 1.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 25.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 17.72%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 16.46%  |
| Broadcom 5880                                                                | 9         | 11.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 8.86%   |
| Broadcom 58200                                                               | 7         | 8.86%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 7.59%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1866      | 69.06%  |
| 1     | 692       | 25.61%  |
| 2     | 122       | 4.52%   |
| 3     | 15        | 0.56%   |
| 6     | 2         | 0.07%   |
| 5     | 2         | 0.07%   |
| 8     | 1         | 0.04%   |
| 7     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 293       | 29.69%  |
| Graphics card            | 197       | 19.96%  |
| Net/wireless             | 160       | 16.21%  |
| Chipcard                 | 75        | 7.6%    |
| Multimedia controller    | 72        | 7.29%   |
| Communication controller | 46        | 4.66%   |
| Bluetooth                | 31        | 3.14%   |
| Camera                   | 30        | 3.04%   |
| Unassigned class         | 15        | 1.52%   |
| Net/ethernet             | 13        | 1.32%   |
| Storage                  | 12        | 1.22%   |
| Sound                    | 12        | 1.22%   |
| Card reader              | 7         | 0.71%   |
| Network                  | 6         | 0.61%   |
| Modem                    | 6         | 0.61%   |
| Storage/raid             | 3         | 0.3%    |
| Storage/ide              | 2         | 0.2%    |
| Firewire controller      | 2         | 0.2%    |
| Video                    | 1         | 0.1%    |
| Tv card                  | 1         | 0.1%    |
| Storage/nvme             | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

