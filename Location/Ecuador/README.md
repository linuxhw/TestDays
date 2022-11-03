Linux in Ecuador - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ecuador/Desktop/README.md) and [notebooks](/Location/Ecuador/Notebook/README.md).

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

Total: 328

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway       | NV510P                      | Notebook    | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway       | NV510P                      | Notebook    | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | Desktop     | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | Notebook    | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Sony          | SVE14113ELW                 | Notebook    | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | Desktop     | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| Biostar       | G41D3C                      | Desktop     | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| HP            | Unknown                     | Notebook    | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | Unknown                     | Notebook    | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Google        | Panther                     | Desktop     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | Desktop     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | Notebook    | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | Notebook    | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | Notebook    | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | Notebook    | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | Notebook    | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Dell          | G5 5587                     | Notebook    | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | Notebook    | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f2ba12e1f](https://linux-hardware.org/?probe=9f2ba12e1f) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [82281b42b0](https://linux-hardware.org/?probe=82281b42b0) | Dec 29, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Google        | Treeya                      | Notebook    | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | Notebook    | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | Notebook    | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [6257ee6ddd](https://linux-hardware.org/?probe=6257ee6ddd) | Oct 07, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [5972d02719](https://linux-hardware.org/?probe=5972d02719) | Oct 07, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [2307619c77](https://linux-hardware.org/?probe=2307619c77) | Sep 27, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [d4cd8cbc7e](https://linux-hardware.org/?probe=d4cd8cbc7e) | Sep 27, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Toshiba       | Satellite S55-B             | Notebook    | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | Notebook    | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Google        | Grunt                       | Notebook    | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | Notebook    | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| Google        | Kip                         | Notebook    | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | Notebook    | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Dell          | G5 5587                     | Notebook    | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Shuttle       | SFM27 V20                   | Desktop     | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [35cc521571](https://linux-hardware.org/?probe=35cc521571) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | Notebook    | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | Notebook    | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | Notebook    | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | Notebook    | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| HP            | ProBook 4440s               | Notebook    | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | Notebook    | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | Notebook    | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| MSI           | B75A-G43                    | Desktop     | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | Desktop     | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | 1497                        | Desktop     | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [40aeea62f1](https://linux-hardware.org/?probe=40aeea62f1) | Sep 13, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | Notebook    | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [1f4ef5bb49](https://linux-hardware.org/?probe=1f4ef5bb49) | Aug 19, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | Notebook    | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | Notebook                    | Notebook    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [853f76e35e](https://linux-hardware.org/?probe=853f76e35e) | Jun 23, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [87e6d2f056](https://linux-hardware.org/?probe=87e6d2f056) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [7332f612bc](https://linux-hardware.org/?probe=7332f612bc) | May 30, 2020 |
| HP            | ProBook 4440s               | Notebook    | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [15c3385fcd](https://linux-hardware.org/?probe=15c3385fcd) | May 30, 2020 |
| Biostar       | H81MLV3                     | Desktop     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Apple         | MacBookPro13,3              | Notebook    | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | Notebook    | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | Notebook    | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | Notebook    | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | Notebook    | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b37b6efdf7](https://linux-hardware.org/?probe=b37b6efdf7) | Feb 18, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [f8c6ef3229](https://linux-hardware.org/?probe=f8c6ef3229) | Feb 17, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0893b14338](https://linux-hardware.org/?probe=0893b14338) | Feb 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | Notebook    | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | Notebook    | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| HP            | 18E7                        | Desktop     | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Toshiba       | Satellite P55W-C            | Notebook    | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | Notebook    | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | Notebook    | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| Dell          | 0CRH6C A02                  | Desktop     | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | Notebook    | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |
| Cartimex      | H61H2-MV                    | Desktop     | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 40        | 17.86%  |
| Ubuntu 18.04        | 22        | 9.82%   |
| Linux Mint 20.3     | 8         | 3.57%   |
| Debian 11           | 8         | 3.57%   |
| Ubuntu 22.04        | 7         | 3.13%   |
| OpenMandriva 4.3    | 7         | 3.13%   |
| KDE neon 20.04      | 6         | 2.68%   |
| Linux Mint 19.3     | 5         | 2.23%   |
| Fedora 36           | 5         | 2.23%   |
| Fedora 34           | 5         | 2.23%   |
| Zorin 16            | 4         | 1.79%   |
| Zorin 15            | 4         | 1.79%   |
| Pop!_OS 21.10       | 4         | 1.79%   |
| Pop!_OS 21.04       | 4         | 1.79%   |
| OpenMandriva 4.2    | 4         | 1.79%   |
| LMDE 4              | 4         | 1.79%   |
| Fedora 33           | 4         | 1.79%   |
| Ubuntu 21.10        | 3         | 1.34%   |
| Pop!_OS 20.04       | 3         | 1.34%   |
| Linux Mint 20.1     | 3         | 1.34%   |
| Kubuntu 22.04       | 3         | 1.34%   |
| Elementary 5.1.7    | 3         | 1.34%   |
| Arch                | 3         | 1.34%   |
| Xubuntu 20.04       | 2         | 0.89%   |
| Xubuntu 18.04       | 2         | 0.89%   |
| Ubuntu 21.04        | 2         | 0.89%   |
| Ubuntu              | 2         | 0.89%   |
| Manjaro 21.2.5      | 2         | 0.89%   |
| Manjaro             | 2         | 0.89%   |
| Linux Mint 20.2     | 2         | 0.89%   |
| Linux Mint 20       | 2         | 0.89%   |
| Linux Mint 19.1     | 2         | 0.89%   |
| Fedora 35           | 2         | 0.89%   |
| Debian 10           | 2         | 0.89%   |
| BlackPanther 18.1   | 2         | 0.89%   |
| Arch Rolling        | 2         | 0.89%   |
| Void Linux          | 1         | 0.45%   |
| Ubuntu MATE 20.04   | 1         | 0.45%   |
| Ubuntu MATE 18.04   | 1         | 0.45%   |
| Ubuntu Budgie 22.04 | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 79        | 36.24%  |
| Linux Mint    | 21        | 9.63%   |
| Fedora        | 19        | 8.72%   |
| Pop!_OS       | 12        | 5.5%    |
| OpenMandriva  | 11        | 5.05%   |
| Debian        | 10        | 4.59%   |
| Zorin         | 8         | 3.67%   |
| Manjaro       | 7         | 3.21%   |
| KDE neon      | 7         | 3.21%   |
| Arch          | 5         | 2.29%   |
| Xubuntu       | 4         | 1.83%   |
| LMDE          | 4         | 1.83%   |
| Kubuntu       | 4         | 1.83%   |
| Elementary    | 4         | 1.83%   |
| Lubuntu       | 3         | 1.38%   |
| Ubuntu MATE   | 2         | 0.92%   |
| Ubuntu Budgie | 2         | 0.92%   |
| Endless       | 2         | 0.92%   |
| Clear Linux   | 2         | 0.92%   |
| BlackPanther  | 2         | 0.92%   |
| Void Linux    | 1         | 0.46%   |
| RHEL          | 1         | 0.46%   |
| Peppermint    | 1         | 0.46%   |
| openSUSE      | 1         | 0.46%   |
| Nobara        | 1         | 0.46%   |
| Kali          | 1         | 0.46%   |
| Garuda Linux  | 1         | 0.46%   |
| Deepin        | 1         | 0.46%   |
| CentOS        | 1         | 0.46%   |
| ArcoLinux     | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 6         | 2.45%   |
| 5.16.7-desktop-1omv4003  | 6         | 2.45%   |
| 5.4.0-42-generic         | 5         | 2.04%   |
| 5.13.0-35-generic        | 5         | 2.04%   |
| 5.4.0-45-generic         | 4         | 1.63%   |
| 5.15.0-33-generic        | 4         | 1.63%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.63%   |
| 5.8.0-41-generic         | 3         | 1.22%   |
| 5.4.0-7634-generic       | 3         | 1.22%   |
| 5.4.0-58-generic         | 3         | 1.22%   |
| 5.4.0-56-generic         | 3         | 1.22%   |
| 5.4.0-48-generic         | 3         | 1.22%   |
| 5.4.0-37-generic         | 3         | 1.22%   |
| 5.4.0-26-generic         | 3         | 1.22%   |
| 5.16.11-76051611-generic | 3         | 1.22%   |
| 5.13.0-7614-generic      | 3         | 1.22%   |
| 5.0.0-37-generic         | 3         | 1.22%   |
| 5.0.0-23-generic         | 3         | 1.22%   |
| 5.8.0-50-generic         | 2         | 0.82%   |
| 5.8.0-43-generic         | 2         | 0.82%   |
| 5.8.0-14-generic         | 2         | 0.82%   |
| 5.4.0-77-generic         | 2         | 0.82%   |
| 5.4.0-73-generic         | 2         | 0.82%   |
| 5.4.0-47-generic         | 2         | 0.82%   |
| 5.4.0-29-generic         | 2         | 0.82%   |
| 5.4.0-110-generic        | 2         | 0.82%   |
| 5.3.0-62-generic         | 2         | 0.82%   |
| 5.15.59-xanmod1          | 2         | 0.82%   |
| 5.15.0-50-generic        | 2         | 0.82%   |
| 5.15.0-27-generic        | 2         | 0.82%   |
| 5.13.0-51-generic        | 2         | 0.82%   |
| 5.13.0-30-generic        | 2         | 0.82%   |
| 5.13.0-27-generic        | 2         | 0.82%   |
| 5.11.16-300.fc34.x86_64  | 2         | 0.82%   |
| 5.11.0-27-generic        | 2         | 0.82%   |
| 5.10.0-8-amd64           | 2         | 0.82%   |
| 4.18.16-desktop-1bP      | 2         | 0.82%   |
| 4.18.0-17-generic        | 2         | 0.82%   |
| 4.15.0-54-generic        | 2         | 0.82%   |
| 4.15.0-50-generic        | 2         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 57        | 24.57%  |
| 4.15.0  | 18        | 7.76%   |
| 5.13.0  | 17        | 7.33%   |
| 5.15.0  | 15        | 6.47%   |
| 5.8.0   | 12        | 5.17%   |
| 5.11.0  | 9         | 3.88%   |
| 5.0.0   | 9         | 3.88%   |
| 5.16.7  | 7         | 3.02%   |
| 5.10.0  | 7         | 3.02%   |
| 5.3.0   | 6         | 2.59%   |
| 5.10.14 | 4         | 1.72%   |
| 5.17.5  | 3         | 1.29%   |
| 5.16.11 | 3         | 1.29%   |
| 4.19.0  | 3         | 1.29%   |
| 4.18.0  | 3         | 1.29%   |
| 5.16.13 | 2         | 0.86%   |
| 5.16.0  | 2         | 0.86%   |
| 5.15.59 | 2         | 0.86%   |
| 5.11.16 | 2         | 0.86%   |
| 4.18.16 | 2         | 0.86%   |
| 6.0.2   | 1         | 0.43%   |
| 5.9.16  | 1         | 0.43%   |
| 5.8.15  | 1         | 0.43%   |
| 5.8.1   | 1         | 0.43%   |
| 5.7.17  | 1         | 0.43%   |
| 5.7.1   | 1         | 0.43%   |
| 5.7.0   | 1         | 0.43%   |
| 5.5.5   | 1         | 0.43%   |
| 5.5.16  | 1         | 0.43%   |
| 5.4.50  | 1         | 0.43%   |
| 5.4.26  | 1         | 0.43%   |
| 5.4.111 | 1         | 0.43%   |
| 5.3.9   | 1         | 0.43%   |
| 5.3.18  | 1         | 0.43%   |
| 5.19.9  | 1         | 0.43%   |
| 5.19.7  | 1         | 0.43%   |
| 5.19.16 | 1         | 0.43%   |
| 5.19.15 | 1         | 0.43%   |
| 5.19.10 | 1         | 0.43%   |
| 5.18.6  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 26.32%  |
| 5.15    | 22        | 9.65%   |
| 5.13    | 18        | 7.89%   |
| 4.15    | 18        | 7.89%   |
| 5.16    | 15        | 6.58%   |
| 5.10    | 15        | 6.58%   |
| 5.8     | 14        | 6.14%   |
| 5.11    | 12        | 5.26%   |
| 5.0     | 10        | 4.39%   |
| 5.3     | 8         | 3.51%   |
| 5.17    | 6         | 2.63%   |
| 5.19    | 5         | 2.19%   |
| 4.18    | 5         | 2.19%   |
| 5.7     | 3         | 1.32%   |
| 5.18    | 3         | 1.32%   |
| 5.14    | 3         | 1.32%   |
| 4.19    | 3         | 1.32%   |
| 5.5     | 2         | 0.88%   |
| 5.12    | 2         | 0.88%   |
| 6.0     | 1         | 0.44%   |
| 5.9     | 1         | 0.44%   |
| 4.9     | 1         | 0.44%   |
| 3.10    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 94.2%   |
| i686   | 12        | 5.8%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 99        | 46.26%  |
| KDE5       | 28        | 13.08%  |
| Unknown    | 27        | 12.62%  |
| X-Cinnamon | 21        | 9.81%   |
| XFCE       | 10        | 4.67%   |
| MATE       | 7         | 3.27%   |
| KDE        | 6         | 2.8%    |
| Pantheon   | 4         | 1.87%   |
| LXDE       | 3         | 1.4%    |
| qtile      | 2         | 0.93%   |
| Deepin     | 2         | 0.93%   |
| Budgie     | 2         | 0.93%   |
| LXQt       | 1         | 0.47%   |
| jwm        | 1         | 0.47%   |
| ICEWM      | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 168       | 77.42%  |
| Wayland | 34        | 15.67%  |
| Unknown | 14        | 6.45%   |
| Tty     | 1         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 127       | 58.26%  |
| GDM     | 28        | 12.84%  |
| SDDM    | 27        | 12.39%  |
| GDM3    | 20        | 9.17%   |
| LightDM | 11        | 5.05%   |
| TDM     | 5         | 2.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_EC   | 101       | 47.87%  |
| en_US   | 56        | 26.54%  |
| es_ES   | 19        | 9%      |
| Unknown | 19        | 9%      |
| C       | 3         | 1.42%   |
| ru_RU   | 2         | 0.95%   |
| fr_FR   | 2         | 0.95%   |
| es_PE   | 2         | 0.95%   |
| es_MX   | 2         | 0.95%   |
| de_DE   | 2         | 0.95%   |
| es_US   | 1         | 0.47%   |
| es_CO   | 1         | 0.47%   |
| en_AG   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 112       | 52.83%  |
| EFI  | 100       | 47.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 170       | 79.81%  |
| Overlay | 17        | 7.98%   |
| Btrfs   | 15        | 7.04%   |
| Xfs     | 4         | 1.88%   |
| Unknown | 4         | 1.88%   |
| Zfs     | 1         | 0.47%   |
| Tmpfs   | 1         | 0.47%   |
| Ext2    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 138       | 65.71%  |
| GPT     | 52        | 24.76%  |
| MBR     | 20        | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 185       | 87.68%  |
| Yes       | 26        | 12.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 70.48%  |
| Yes       | 62        | 29.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 37        | 17.87%  |
| ASUSTek Computer      | 33        | 15.94%  |
| Dell                  | 25        | 12.08%  |
| Lenovo                | 22        | 10.63%  |
| Toshiba               | 11        | 5.31%   |
| Gigabyte Technology   | 10        | 4.83%   |
| Intel                 | 9         | 4.35%   |
| Biostar               | 8         | 3.86%   |
| Google                | 7         | 3.38%   |
| Acer                  | 7         | 3.38%   |
| Sony                  | 5         | 2.42%   |
| MSI                   | 3         | 1.45%   |
| Foxconn               | 3         | 1.45%   |
| ASRock                | 3         | 1.45%   |
| Apple                 | 3         | 1.45%   |
| Samsung Electronics   | 2         | 0.97%   |
| Razer                 | 2         | 0.97%   |
| Gateway               | 2         | 0.97%   |
| Unknown               | 2         | 0.97%   |
| XTRATECH COMPUTERS SA | 1         | 0.48%   |
| TrekStor              | 1         | 0.48%   |
| TPV-INVENTA           | 1         | 0.48%   |
| Timi                  | 1         | 0.48%   |
| Shuttle               | 1         | 0.48%   |
| Pegatron              | 1         | 0.48%   |
| Fujitsu               | 1         | 0.48%   |
| ECS                   | 1         | 0.48%   |
| Compal                | 1         | 0.48%   |
| Chuwi                 | 1         | 0.48%   |
| Cartimex              | 1         | 0.48%   |
| AMI                   | 1         | 0.48%   |
| Alienware             | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 4         | 1.93%   |
| ASUS PRIME A320M-A                    | 3         | 1.45%   |
| Unknown                               | 3         | 1.45%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.97%   |
| Lenovo IdeaPad 320-15ABR 80XS         | 2         | 0.97%   |
| HP ProBook 4440s                      | 2         | 0.97%   |
| HP Pavilion Laptop 15-cw0xxx          | 2         | 0.97%   |
| HP Notebook                           | 2         | 0.97%   |
| HP Laptop 15-da0xxx                   | 2         | 0.97%   |
| Gigabyte H81M-H                       | 2         | 0.97%   |
| Dell Inspiron 5570                    | 2         | 0.97%   |
| Dell Inspiron 3442                    | 2         | 0.97%   |
| Dell Inspiron 1420                    | 2         | 0.97%   |
| Dell G5 5587                          | 2         | 0.97%   |
| Biostar H61MGV3                       | 2         | 0.97%   |
| Biostar G31-M7 TE                     | 2         | 0.97%   |
| XTRATECH COMPUTERS SA MN-1022X        | 1         | 0.48%   |
| TrekStor Primebook C13                | 1         | 0.48%   |
| TPV-INVENTA 2AF2 A01                  | 1         | 0.48%   |
| Toshiba Satellite S55-B               | 1         | 0.48%   |
| Toshiba Satellite S55-A               | 1         | 0.48%   |
| Toshiba Satellite P775                | 1         | 0.48%   |
| Toshiba Satellite P55W-C              | 1         | 0.48%   |
| Toshiba Satellite L50-B               | 1         | 0.48%   |
| Toshiba Satellite L45-B               | 1         | 0.48%   |
| Toshiba Satellite E45t-B              | 1         | 0.48%   |
| Toshiba Satellite C55D-A              | 1         | 0.48%   |
| Toshiba Satellite C55-B               | 1         | 0.48%   |
| Toshiba Satellite C45-A               | 1         | 0.48%   |
| Toshiba PORTEGE M805                  | 1         | 0.48%   |
| Timi RedmiBook 14-APCS                | 1         | 0.48%   |
| Sony VPCEG30EL                        | 1         | 0.48%   |
| Sony VPCCW1S1E                        | 1         | 0.48%   |
| Sony VGN-CR120E                       | 1         | 0.48%   |
| Sony SVE14A25CLB                      | 1         | 0.48%   |
| Sony SVE14113ELW                      | 1         | 0.48%   |
| Shuttle SFM27                         | 1         | 0.48%   |
| Samsung 550XCJ/550XCR                 | 1         | 0.48%   |
| Samsung 530U4E/540U4E                 | 1         | 0.48%   |
| Razer Blade Stealth                   | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 15        | 7.25%   |
| Toshiba Satellite              | 10        | 4.83%   |
| HP Pavilion                    | 9         | 4.35%   |
| ASUS PRIME                     | 9         | 4.35%   |
| Lenovo IdeaPad                 | 8         | 3.86%   |
| HP Laptop                      | 6         | 2.9%    |
| Lenovo ThinkPad                | 5         | 2.42%   |
| ASUS VivoBook                  | 5         | 2.42%   |
| Dell Latitude                  | 4         | 1.93%   |
| ASUS All                       | 4         | 1.93%   |
| Acer Aspire                    | 4         | 1.93%   |
| HP ProBook                     | 3         | 1.45%   |
| HP EliteBook                   | 3         | 1.45%   |
| Unknown                        | 3         | 1.45%   |
| Razer Blade                    | 2         | 0.97%   |
| Lenovo Yoga                    | 2         | 0.97%   |
| HP Notebook                    | 2         | 0.97%   |
| HP ENVY                        | 2         | 0.97%   |
| HP 15                          | 2         | 0.97%   |
| Gigabyte H81M-H                | 2         | 0.97%   |
| Gigabyte H410M                 | 2         | 0.97%   |
| Dell G5                        | 2         | 0.97%   |
| Biostar H61MGV3                | 2         | 0.97%   |
| Biostar G31-M7                 | 2         | 0.97%   |
| Acer TravelMate                | 2         | 0.97%   |
| XTRATECH COMPUTERS SA MN-1022X | 1         | 0.48%   |
| TrekStor Primebook             | 1         | 0.48%   |
| TPV-INVENTA 2AF2               | 1         | 0.48%   |
| Toshiba PORTEGE                | 1         | 0.48%   |
| Timi RedmiBook                 | 1         | 0.48%   |
| Sony VPCEG30EL                 | 1         | 0.48%   |
| Sony VPCCW1S1E                 | 1         | 0.48%   |
| Sony VGN-CR120E                | 1         | 0.48%   |
| Sony SVE14A25CLB               | 1         | 0.48%   |
| Sony SVE14113ELW               | 1         | 0.48%   |
| Shuttle SFM27                  | 1         | 0.48%   |
| Samsung 550XCJ                 | 1         | 0.48%   |
| Samsung 530U4E                 | 1         | 0.48%   |
| Pegatron CQ1506LA              | 1         | 0.48%   |
| MSI MS-7B98                    | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 26        | 12.56%  |
| 2013 | 22        | 10.63%  |
| 2020 | 21        | 10.14%  |
| 2017 | 19        | 9.18%   |
| 2012 | 19        | 9.18%   |
| 2019 | 15        | 7.25%   |
| 2011 | 15        | 7.25%   |
| 2021 | 10        | 4.83%   |
| 2016 | 10        | 4.83%   |
| 2015 | 10        | 4.83%   |
| 2014 | 10        | 4.83%   |
| 2007 | 8         | 3.86%   |
| 2010 | 7         | 3.38%   |
| 2009 | 7         | 3.38%   |
| 2008 | 4         | 1.93%   |
| 2006 | 2         | 0.97%   |
| 2022 | 1         | 0.48%   |
| 2005 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 132       | 63.77%  |
| Desktop     | 64        | 30.92%  |
| Convertible | 8         | 3.86%   |
| Mini pc     | 2         | 0.97%   |
| Tablet      | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 194       | 92.82%  |
| Enabled  | 15        | 7.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 96.62%  |
| Yes  | 7         | 3.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 59        | 27.57%  |
| 8.01-16.0  | 47        | 21.96%  |
| 3.01-4.0   | 43        | 20.09%  |
| 16.01-24.0 | 27        | 12.62%  |
| 1.01-2.0   | 18        | 8.41%   |
| 32.01-64.0 | 11        | 5.14%   |
| 24.01-32.0 | 5         | 2.34%   |
| 2.01-3.0   | 3         | 1.4%    |
| 0.51-1.0   | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 70        | 30.17%  |
| 1.01-2.0   | 69        | 29.74%  |
| 4.01-8.0   | 36        | 15.52%  |
| 3.01-4.0   | 35        | 15.09%  |
| 0.51-1.0   | 11        | 4.74%   |
| 8.01-16.0  | 7         | 3.02%   |
| 0.01-0.5   | 3         | 1.29%   |
| 24.01-32.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 149       | 69.95%  |
| 2      | 50        | 23.47%  |
| 3      | 13        | 6.1%    |
| 5      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 59.81%  |
| Yes       | 84        | 40.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 84.54%  |
| No        | 32        | 15.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 77.88%  |
| No        | 46        | 22.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 59.13%  |
| No        | 85        | 40.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ecuador | 207       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 89        | 41.98%  |
| Guayaquil                      | 55        | 25.94%  |
| Cuenca                         | 18        | 8.49%   |
| Manta                          | 6         | 2.83%   |
| Loja                           | 4         | 1.89%   |
| Ambato                         | 4         | 1.89%   |
| Riobamba                       | 3         | 1.42%   |
| Portoviejo                     | 3         | 1.42%   |
| Machala                        | 3         | 1.42%   |
| Hacienda Ibarra                | 3         | 1.42%   |
| Latacunga                      | 2         | 0.94%   |
| Cotacachi                      | 2         | 0.94%   |
| Uyumbicho                      | 1         | 0.47%   |
| Santo Domingo de los Colorados | 1         | 0.47%   |
| Samborondon                    | 1         | 0.47%   |
| Quevedo                        | 1         | 0.47%   |
| Ponceano                       | 1         | 0.47%   |
| Otavalo                        | 1         | 0.47%   |
| Nueva Loja                     | 1         | 0.47%   |
| Montecristi                    | 1         | 0.47%   |
| Las Pinas                      | 1         | 0.47%   |
| La Troncal                     | 1         | 0.47%   |
| La Providencia                 | 1         | 0.47%   |
| Ibarra                         | 1         | 0.47%   |
| Hacienda La Libertad           | 1         | 0.47%   |
| Guanujo                        | 1         | 0.47%   |
| Guamani                        | 1         | 0.47%   |
| Cayambe                        | 1         | 0.47%   |
| Cariamanga                     | 1         | 0.47%   |
| Babahoyo                       | 1         | 0.47%   |
| Azogues                        | 1         | 0.47%   |
| Ayacucho                       | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 60        | 84     | 22.3%   |
| Seagate                 | 41        | 63     | 15.24%  |
| Toshiba                 | 40        | 46     | 14.87%  |
| Samsung Electronics     | 19        | 21     | 7.06%   |
| Kingston                | 15        | 23     | 5.58%   |
| Hitachi                 | 15        | 17     | 5.58%   |
| Unknown                 | 10        | 17     | 3.72%   |
| SanDisk                 | 9         | 11     | 3.35%   |
| SK hynix                | 7         | 8      | 2.6%    |
| A-DATA Technology       | 7         | 11     | 2.6%    |
| Hewlett-Packard         | 6         | 6      | 2.23%   |
| HGST                    | 4         | 5      | 1.49%   |
| PNY                     | 3         | 3      | 1.12%   |
| Micron Technology       | 3         | 3      | 1.12%   |
| Intel                   | 3         | 4      | 1.12%   |
| Fujitsu                 | 3         | 3      | 1.12%   |
| SPCC                    | 2         | 2      | 0.74%   |
| Crucial                 | 2         | 2      | 0.74%   |
| USB3.0                  | 1         | 1      | 0.37%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.37%   |
| UMIS                    | 1         | 1      | 0.37%   |
| SABRENT                 | 1         | 1      | 0.37%   |
| Phison Electronics      | 1         | 1      | 0.37%   |
| Phison                  | 1         | 1      | 0.37%   |
| OWC                     | 1         | 1      | 0.37%   |
| Netac                   | 1         | 1      | 0.37%   |
| Micro Center            | 1         | 1      | 0.37%   |
| LITEON                  | 1         | 1      | 0.37%   |
| Lite-On                 | 1         | 1      | 0.37%   |
| KIOXIA                  | 1         | 2      | 0.37%   |
| JMicron Technology      | 1         | 1      | 0.37%   |
| Imation                 | 1         | 1      | 0.37%   |
| HS-SSD-E100N            | 1         | 1      | 0.37%   |
| HPE                     | 1         | 1      | 0.37%   |
| Golden                  | 1         | 1      | 0.37%   |
| Gigabyte Technology     | 1         | 1      | 0.37%   |
| Apple                   | 1         | 2      | 0.37%   |
| Unknown                 | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                | 6         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 2.08%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 2.08%   |
| Toshiba MQ04ABF100 1TB                  | 5         | 1.73%   |
| Toshiba DT01ACA100 1TB                  | 5         | 1.73%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 1.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 4         | 1.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 4         | 1.38%   |
| WDC WD10SPZX-24Z10 1TB                  | 3         | 1.04%   |
| Unknown MMC Card  32GB                  | 3         | 1.04%   |
| Unknown MMC Card  16GB                  | 3         | 1.04%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.04%   |
| Samsung HD502HJ 500GB                   | 3         | 1.04%   |
| HP SSD S700 500GB                       | 3         | 1.04%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 2         | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 2         | 0.69%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 0.69%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.69%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.69%   |
| Unknown MMC Card  64GB                  | 2         | 0.69%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.69%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.69%   |
| Toshiba DT01ACA200 2TB                  | 2         | 0.69%   |
| SK hynix NVMe SSD Drive 256GB           | 2         | 0.69%   |
| Seagate ST9500325AS 500GB               | 2         | 0.69%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 0.69%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.69%   |
| Micron NVMe SSD Drive 512GB             | 2         | 0.69%   |
| Kingston SV300S37A60G 64GB SSD          | 2         | 0.69%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.69%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 0.69%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 0.69%   |
| Hitachi HDS721050CLA660 500GB           | 2         | 0.69%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.69%   |
| A-DATA SU650 120GB SSD                  | 2         | 0.69%   |
| A-DATA ED600 1TB SSD                    | 2         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 63     | 27.39%  |
| Seagate             | 41        | 63     | 26.11%  |
| Toshiba             | 36        | 41     | 22.93%  |
| Hitachi             | 15        | 17     | 9.55%   |
| Samsung Electronics | 11        | 13     | 7.01%   |
| HGST                | 4         | 5      | 2.55%   |
| Fujitsu             | 3         | 3      | 1.91%   |
| USB3.0              | 1         | 1      | 0.64%   |
| Unknown             | 1         | 3      | 0.64%   |
| SABRENT             | 1         | 1      | 0.64%   |
| HPE                 | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 21.43%  |
| Kingston            | 14        | 18     | 20%     |
| A-DATA Technology   | 6         | 9      | 8.57%   |
| SanDisk             | 5         | 5      | 7.14%   |
| Hewlett-Packard     | 5         | 5      | 7.14%   |
| Toshiba             | 3         | 4      | 4.29%   |
| PNY                 | 3         | 3      | 4.29%   |
| SPCC                | 2         | 2      | 2.86%   |
| SK hynix            | 2         | 2      | 2.86%   |
| Samsung Electronics | 2         | 2      | 2.86%   |
| Intel               | 2         | 2      | 2.86%   |
| Crucial             | 2         | 2      | 2.86%   |
| OWC                 | 1         | 1      | 1.43%   |
| Netac               | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| Micro Center        | 1         | 1      | 1.43%   |
| LITEON              | 1         | 1      | 1.43%   |
| HS-SSD-E100N        | 1         | 1      | 1.43%   |
| Golden              | 1         | 1      | 1.43%   |
| Gigabyte Technology | 1         | 1      | 1.43%   |
| Apple               | 1         | 2      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 140       | 211    | 57.14%  |
| SSD     | 62        | 80     | 25.31%  |
| NVMe    | 33        | 44     | 13.47%  |
| MMC     | 9         | 15     | 3.67%   |
| Unknown | 1         | 1      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 178       | 280    | 78.76%  |
| NVMe | 33        | 43     | 14.6%   |
| MMC  | 9         | 15     | 3.98%   |
| SAS  | 6         | 13     | 2.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 161    | 56.46%  |
| 0.51-1.0   | 74        | 107    | 35.41%  |
| 1.01-2.0   | 15        | 21     | 7.18%   |
| 3.01-4.0   | 1         | 1      | 0.48%   |
| 2.01-3.0   | 1         | 1      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 57        | 26.03%  |
| 101-250        | 53        | 24.2%   |
| 501-1000       | 35        | 15.98%  |
| 1001-2000      | 25        | 11.42%  |
| 1-20           | 15        | 6.85%   |
| 51-100         | 14        | 6.39%   |
| 21-50          | 10        | 4.57%   |
| More than 3000 | 5         | 2.28%   |
| Unknown        | 5         | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 35.4%   |
| 21-50          | 45        | 19.91%  |
| 101-250        | 35        | 15.49%  |
| 251-500        | 23        | 10.18%  |
| 51-100         | 20        | 8.85%   |
| 501-1000       | 10        | 4.42%   |
| 1001-2000      | 6         | 2.65%   |
| Unknown        | 5         | 2.21%   |
| More than 3000 | 2         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2         | 3      | 8.7%    |
| Hitachi HDS721050CLA660 500GB     | 2         | 2      | 8.7%    |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB          | 1         | 2      | 4.35%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 4.35%   |
| Toshiba MK3259GSXP 320GB          | 1         | 1      | 4.35%   |
| Toshiba MK2561GSYN 250GB          | 1         | 1      | 4.35%   |
| Seagate ST3750330AS 752GB         | 1         | 1      | 4.35%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 4.35%   |
| Seagate ST1000LX015-1U7172 1TB    | 1         | 3      | 4.35%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 4.35%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 4.35%   |
| Samsung Electronics HD501LJ 500GB | 1         | 1      | 4.35%   |
| Samsung Electronics HD322HJ 320GB | 1         | 1      | 4.35%   |
| Kingston SNS4151S316GD 16GB SSD   | 1         | 1      | 4.35%   |
| HPE MB0500EAMZD 500GB             | 1         | 1      | 4.35%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 4.35%   |
| Hitachi HTS543232L9SA00 320GB     | 1         | 1      | 4.35%   |
| HGST HTS545050A7E380 500GB        | 1         | 1      | 4.35%   |
| Fujitsu MHZ2160BH G1 160GB        | 1         | 1      | 4.35%   |
| Fujitsu MHY2250BH 250GB           | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 11     | 30.43%  |
| Toshiba             | 4         | 5      | 17.39%  |
| Hitachi             | 4         | 4      | 17.39%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Fujitsu             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| HPE                 | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 11     | 31.82%  |
| Toshiba             | 4         | 5      | 18.18%  |
| Hitachi             | 4         | 4      | 18.18%  |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Fujitsu             | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| HPE                 | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 27     | 95%     |
| SSD  | 1         | 1      | 5%      |

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
| Detected | 144       | 254    | 66.06%  |
| Works    | 54        | 69     | 24.77%  |
| Malfunc  | 20        | 28     | 9.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 148       | 64.07%  |
| AMD                          | 39        | 16.88%  |
| SanDisk                      | 9         | 3.9%    |
| Samsung Electronics          | 7         | 3.03%   |
| SK hynix                     | 5         | 2.16%   |
| Marvell Technology Group     | 4         | 1.73%   |
| VIA Technologies             | 2         | 0.87%   |
| Union Memory (Shenzhen)      | 2         | 0.87%   |
| Phison Electronics           | 2         | 0.87%   |
| Micron Technology            | 2         | 0.87%   |
| Kingston Technology Company  | 2         | 0.87%   |
| JMicron Technology           | 2         | 0.87%   |
| ASMedia Technology           | 2         | 0.87%   |
| Toshiba America Info Systems | 1         | 0.43%   |
| Silicon Motion               | 1         | 0.43%   |
| Lite-On Technology           | 1         | 0.43%   |
| KIOXIA                       | 1         | 0.43%   |
| ADATA Technology             | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 10.94%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 5.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 4.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 4.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 3.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.51%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.51%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 1.13%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2         | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.75%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.75%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.75%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.75%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 0.75%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 151       | 65.09%  |
| NVMe | 33        | 14.22%  |
| IDE  | 31        | 13.36%  |
| RAID | 17        | 7.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 163       | 78.74%  |
| AMD    | 44        | 21.26%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 4.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 1.93%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 4         | 1.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 3         | 1.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 1.45%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 3         | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.45%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 1.45%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 3         | 1.45%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 2         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 0.97%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 2         | 0.97%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 0.97%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.97%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 0.97%   |
| Intel Core i3-10100F CPU @ 3.60GHz              | 2         | 0.97%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 2         | 0.97%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz            | 2         | 0.97%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 2         | 0.97%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 2         | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 0.97%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2         | 0.97%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 2         | 0.97%   |
| AMD E1-2100 APU with Radeon HD Graphics         | 2         | 0.97%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 0.97%   |
| AMD E-300 APU with Radeon HD Graphics           | 2         | 0.97%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 2         | 0.97%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.97%   |
| Intel Xeon CPU X5660 @ 2.80GHz                  | 1         | 0.48%   |
| Intel Pentium M processor 1.86GHz               | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 46        | 22.22%  |
| Intel Core i5           | 40        | 19.32%  |
| Intel Core i3           | 24        | 11.59%  |
| AMD Ryzen 5             | 17        | 8.21%   |
| Intel Celeron           | 16        | 7.73%   |
| Intel Core 2 Duo        | 11        | 5.31%   |
| Intel Pentium           | 7         | 3.38%   |
| Intel Atom              | 6         | 2.9%    |
| Other                   | 5         | 2.42%   |
| AMD Ryzen 7             | 4         | 1.93%   |
| AMD E1                  | 4         | 1.93%   |
| Intel Pentium Dual-Core | 2         | 0.97%   |
| Intel Genuine           | 2         | 0.97%   |
| Intel Core 2 Quad       | 2         | 0.97%   |
| AMD Ryzen 3             | 2         | 0.97%   |
| AMD E                   | 2         | 0.97%   |
| AMD A8                  | 2         | 0.97%   |
| AMD A4                  | 2         | 0.97%   |
| AMD A12                 | 2         | 0.97%   |
| Intel Xeon              | 1         | 0.48%   |
| Intel Pentium M         | 1         | 0.48%   |
| Intel Core m3           | 1         | 0.48%   |
| AMD Phenom II X6        | 1         | 0.48%   |
| AMD Phenom II X2        | 1         | 0.48%   |
| AMD E2                  | 1         | 0.48%   |
| AMD C-70                | 1         | 0.48%   |
| AMD C-60                | 1         | 0.48%   |
| AMD Athlon II X2        | 1         | 0.48%   |
| AMD Athlon II Neo       | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 109       | 52.66%  |
| 4      | 71        | 34.3%   |
| 6      | 19        | 9.18%   |
| 8      | 5         | 2.42%   |
| 1      | 3         | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 207       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 124       | 59.9%   |
| 1      | 83        | 40.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 97.58%  |
| 32-bit         | 3         | 1.45%   |
| Unknown        | 2         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 15.42%  |
| 0x306a9    | 17        | 7.94%   |
| 0x206a7    | 15        | 7.01%   |
| 0x806ea    | 14        | 6.54%   |
| 0x306c3    | 12        | 5.61%   |
| 0x306d4    | 8         | 3.74%   |
| 0x6fd      | 7         | 3.27%   |
| 0x40651    | 7         | 3.27%   |
| 0x1067a    | 7         | 3.27%   |
| 0xa0653    | 4         | 1.87%   |
| 0x906ed    | 4         | 1.87%   |
| 0x906ea    | 4         | 1.87%   |
| 0x0810100b | 4         | 1.87%   |
| 0x05000119 | 4         | 1.87%   |
| 0x806eb    | 3         | 1.4%    |
| 0x806c1    | 3         | 1.4%    |
| 0x706e5    | 3         | 1.4%    |
| 0x406e3    | 3         | 1.4%    |
| 0x30678    | 3         | 1.4%    |
| 0x106ca    | 3         | 1.4%    |
| 0x08108109 | 3         | 1.4%    |
| 0x0600611a | 3         | 1.4%    |
| 0x806ec    | 2         | 0.93%   |
| 0x806e9    | 2         | 0.93%   |
| 0x706a1    | 2         | 0.93%   |
| 0x6e8      | 2         | 0.93%   |
| 0x406c4    | 2         | 0.93%   |
| 0x106e5    | 2         | 0.93%   |
| 0x0a201005 | 2         | 0.93%   |
| 0x08600104 | 2         | 0.93%   |
| 0x0700010f | 2         | 0.93%   |
| 0x06006705 | 2         | 0.93%   |
| 0x06006704 | 2         | 0.93%   |
| 0x010000c8 | 2         | 0.93%   |
| 0xa0660    | 1         | 0.47%   |
| 0x906ec    | 1         | 0.47%   |
| 0x706a8    | 1         | 0.47%   |
| 0x6fa      | 1         | 0.47%   |
| 0x6d8      | 1         | 0.47%   |
| 0x506e3    | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 17.87%  |
| Haswell       | 23        | 11.11%  |
| IvyBridge     | 19        | 9.18%   |
| SandyBridge   | 15        | 7.25%   |
| Penryn        | 8         | 3.86%   |
| Core          | 8         | 3.86%   |
| Broadwell     | 8         | 3.86%   |
| Skylake       | 7         | 3.38%   |
| Silvermont    | 7         | 3.38%   |
| Excavator     | 7         | 3.38%   |
| CometLake     | 7         | 3.38%   |
| Zen+          | 6         | 2.9%    |
| Zen 2         | 6         | 2.9%    |
| Zen           | 6         | 2.9%    |
| Bobcat        | 6         | 2.9%    |
| TigerLake     | 4         | 1.93%   |
| K10           | 4         | 1.93%   |
| Bonnell       | 4         | 1.93%   |
| Zen 3         | 3         | 1.45%   |
| Westmere      | 3         | 1.45%   |
| P6            | 3         | 1.45%   |
| Nehalem       | 3         | 1.45%   |
| IceLake       | 3         | 1.45%   |
| Goldmont plus | 3         | 1.45%   |
| Jaguar        | 2         | 0.97%   |
| Unknown       | 2         | 0.97%   |
| Puma          | 1         | 0.48%   |
| K10 Llano     | 1         | 0.48%   |
| Goldmont      | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 144       | 59.5%   |
| AMD              | 54        | 22.31%  |
| Nvidia           | 43        | 17.77%  |
| VIA Technologies | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 15        | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 5.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 2.8%    |
| Intel HD Graphics 5500                                                                   | 7         | 2.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.6%    |
| Intel HD Graphics 620                                                                    | 4         | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.2%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.2%    |
| AMD Renoir                                                                               | 3         | 1.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.8%    |
| Intel HD Graphics 630                                                                    | 2         | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 113       | 54.07%  |
| 1 x AMD                  | 41        | 19.62%  |
| 1 x Nvidia               | 20        | 9.57%   |
| Intel + Nvidia           | 20        | 9.57%   |
| Intel + AMD              | 10        | 4.78%   |
| AMD + Nvidia             | 2         | 0.96%   |
| 2 x AMD                  | 1         | 0.48%   |
| 1 x VIA                  | 1         | 0.48%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 177       | 84.29%  |
| Proprietary | 23        | 10.95%  |
| Unknown     | 10        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 61.29%  |
| 1.01-2.0   | 31        | 14.29%  |
| 0.01-0.5   | 27        | 12.44%  |
| 3.01-4.0   | 11        | 5.07%   |
| 0.51-1.0   | 9         | 4.15%   |
| 7.01-8.0   | 2         | 0.92%   |
| 5.01-6.0   | 2         | 0.92%   |
| 2.01-3.0   | 1         | 0.46%   |
| 8.01-16.0  | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 33        | 14.93%  |
| LG Display              | 27        | 12.22%  |
| BOE                     | 27        | 12.22%  |
| Chimei Innolux          | 24        | 10.86%  |
| AU Optronics            | 24        | 10.86%  |
| Samsung Electronics     | 16        | 7.24%   |
| BenQ                    | 9         | 4.07%   |
| AOC                     | 9         | 4.07%   |
| Hewlett-Packard         | 8         | 3.62%   |
| Chi Mei Optoelectronics | 5         | 2.26%   |
| LG Electronics          | 4         | 1.81%   |
| Acer                    | 4         | 1.81%   |
| Dell                    | 3         | 1.36%   |
| Apple                   | 3         | 1.36%   |
| Unknown (XXX)           | 2         | 0.9%    |
| Sharp                   | 2         | 0.9%    |
| PANDA                   | 2         | 0.9%    |
| LG Philips              | 2         | 0.9%    |
| InfoVision              | 2         | 0.9%    |
| ASUSTek Computer        | 2         | 0.9%    |
| Toshiba                 | 1         | 0.45%   |
| TCL                     | 1         | 0.45%   |
| Sony                    | 1         | 0.45%   |
| SKY                     | 1         | 0.45%   |
| RTK                     | 1         | 0.45%   |
| NEC Computers           | 1         | 0.45%   |
| Lenovo                  | 1         | 0.45%   |
| KTC                     | 1         | 0.45%   |
| InnoLux Display         | 1         | 0.45%   |
| Huion                   | 1         | 0.45%   |
| DTV                     | 1         | 0.45%   |
| DMT                     | 1         | 0.45%   |
| CPT                     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 4         | 1.75%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 4         | 1.75%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                  | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.32%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 2         | 0.88%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.88%   |
| LG Electronics LCD Monitor LG TV 1360x768                             | 2         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.88%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 2         | 0.88%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 2         | 0.88%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 2         | 0.88%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 2         | 0.88%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.88%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 0.88%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 2         | 0.88%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.44%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.44%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.44%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.44%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch   | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch   | 1         | 0.44%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch      | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SMB1930N 1366x768                     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 85        | 39.72%  |
| 1920x1080 (FHD)    | 64        | 29.91%  |
| 1600x900 (HD+)     | 16        | 7.48%   |
| 1440x900 (WXGA+)   | 7         | 3.27%   |
| 1360x768           | 7         | 3.27%   |
| 1280x800 (WXGA)    | 7         | 3.27%   |
| 3840x2160 (4K)     | 5         | 2.34%   |
| 1024x768 (XGA)     | 5         | 2.34%   |
| 2560x1440 (QHD)    | 3         | 1.4%    |
| 1280x1024 (SXGA)   | 3         | 1.4%    |
| 2560x1600          | 2         | 0.93%   |
| 1024x600           | 2         | 0.93%   |
| Unknown            | 2         | 0.93%   |
| 3520x1080          | 1         | 0.47%   |
| 2880x1800          | 1         | 0.47%   |
| 2646x1024          | 1         | 0.47%   |
| 1920x1200 (WUXGA)  | 1         | 0.47%   |
| 1680x1050 (WSXGA+) | 1         | 0.47%   |
| 1600x1200          | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 68        | 30.49%  |
| 13      | 25        | 11.21%  |
| 18      | 24        | 10.76%  |
| 14      | 24        | 10.76%  |
| 19      | 16        | 7.17%   |
| 21      | 11        | 4.93%   |
| 23      | 8         | 3.59%   |
| Unknown | 8         | 3.59%   |
| 17      | 7         | 3.14%   |
| 11      | 7         | 3.14%   |
| 12      | 5         | 2.24%   |
| 24      | 4         | 1.79%   |
| 20      | 4         | 1.79%   |
| 54      | 3         | 1.35%   |
| 32      | 2         | 0.9%    |
| 31      | 2         | 0.9%    |
| 10      | 2         | 0.9%    |
| 52      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 27      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 48.86%  |
| 401-500     | 49        | 22.37%  |
| 201-300     | 23        | 10.5%   |
| 501-600     | 13        | 5.94%   |
| 351-400     | 10        | 4.57%   |
| Unknown     | 8         | 3.65%   |
| 1001-1500   | 4         | 1.83%   |
| 701-800     | 2         | 0.91%   |
| 601-700     | 2         | 0.91%   |
| 801-900     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 81.96%  |
| 16/10   | 18        | 9.28%   |
| Unknown | 8         | 4.12%   |
| 4/3     | 5         | 2.58%   |
| 5/4     | 3         | 1.55%   |
| 3/2     | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 30.04%  |
| 81-90          | 42        | 18.83%  |
| 151-200        | 24        | 10.76%  |
| 141-150        | 23        | 10.31%  |
| 201-250        | 19        | 8.52%   |
| Unknown        | 8         | 3.59%   |
| 71-80          | 7         | 3.14%   |
| 51-60          | 7         | 3.14%   |
| 61-70          | 5         | 2.24%   |
| 121-130        | 5         | 2.24%   |
| More than 1000 | 4         | 1.79%   |
| 351-500        | 4         | 1.79%   |
| 41-50          | 2         | 0.9%    |
| 131-140        | 2         | 0.9%    |
| 301-350        | 1         | 0.45%   |
| 251-300        | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| 91-100         | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 76        | 35.35%  |
| 51-100        | 62        | 28.84%  |
| 121-160       | 53        | 24.65%  |
| 161-240       | 8         | 3.72%   |
| Unknown       | 8         | 3.72%   |
| 1-50          | 6         | 2.79%   |
| More than 240 | 2         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 172       | 81.13%  |
| 2     | 31        | 14.62%  |
| 0     | 7         | 3.3%    |
| 3     | 2         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 131       | 43.23%  |
| Intel                           | 65        | 21.45%  |
| Qualcomm Atheros                | 50        | 16.5%   |
| Broadcom                        | 19        | 6.27%   |
| Ralink Technology               | 6         | 1.98%   |
| Ralink                          | 6         | 1.98%   |
| TP-Link                         | 5         | 1.65%   |
| Marvell Technology Group        | 5         | 1.65%   |
| Broadcom Limited                | 3         | 0.99%   |
| Xiaomi                          | 2         | 0.66%   |
| Qualcomm Atheros Communications | 2         | 0.66%   |
| MediaTek                        | 2         | 0.66%   |
| D-Link System                   | 2         | 0.66%   |
| VIA Technologies                | 1         | 0.33%   |
| TRENDnet                        | 1         | 0.33%   |
| Samsung Electronics             | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |
| Arduino SA                      | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 23.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 8.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 3.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 2.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.98%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.42%   |
| Intel Wireless 3160                                               | 5         | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 1.13%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.85%   |
| Intel Wireless 8260                                               | 3         | 0.85%   |
| Intel Wireless 7260                                               | 3         | 0.85%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.57%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                              | 2         | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.57%   |
| Intel Wireless-AC 9260                                            | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 32.93%  |
| Qualcomm Atheros                | 39        | 23.35%  |
| Realtek Semiconductor           | 38        | 22.75%  |
| Broadcom                        | 13        | 7.78%   |
| Ralink Technology               | 6         | 3.59%   |
| Ralink                          | 6         | 3.59%   |
| TP-Link                         | 4         | 2.4%    |
| Qualcomm Atheros Communications | 2         | 1.2%    |
| MediaTek                        | 2         | 1.2%    |
| TRENDnet                        | 1         | 0.6%    |
| Broadcom Limited                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 11        | 6.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                        | 10        | 5.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 10        | 5.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 7         | 4.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 7         | 4.14%   |
| Realtek RTL8723DE Wireless Network Adapter                                        | 5         | 2.96%   |
| Intel Wireless 3160                                                               | 5         | 2.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                               | 5         | 2.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 4         | 2.37%   |
| Intel Wireless 8265 / 8275                                                        | 4         | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                          | 3         | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                   | 3         | 1.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 3         | 1.78%   |
| Intel Wireless 8260                                                               | 3         | 1.78%   |
| Intel Wireless 7260                                                               | 3         | 1.78%   |
| Intel Wi-Fi 6 AX200                                                               | 3         | 1.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                             | 3         | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                          | 3         | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 3         | 1.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 2         | 1.18%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 2         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                                   | 2         | 1.18%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                              | 2         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 2         | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 2         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 2         | 1.18%   |
| Intel Wireless-AC 9260                                                            | 2         | 1.18%   |
| Intel Wireless 7265                                                               | 2         | 1.18%   |
| Intel Wireless 3165                                                               | 2         | 1.18%   |
| Intel WiFi Link 5100                                                              | 2         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                               | 2         | 1.18%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                     | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                 | 2         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                       | 2         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                                     | 2         | 1.18%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1         | 0.59%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 1         | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 121       | 67.22%  |
| Intel                    | 21        | 11.67%  |
| Qualcomm Atheros         | 16        | 8.89%   |
| Broadcom                 | 8         | 4.44%   |
| Marvell Technology Group | 5         | 2.78%   |
| Xiaomi                   | 2         | 1.11%   |
| D-Link System            | 2         | 1.11%   |
| Broadcom Limited         | 2         | 1.11%   |
| VIA Technologies         | 1         | 0.56%   |
| TP-Link                  | 1         | 0.56%   |
| Samsung Electronics      | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 45.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 17.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.66%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.66%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.1%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.1%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.1%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.1%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.55%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.55%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.55%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.55%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.55%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 175       | 51.47%  |
| WiFi     | 162       | 47.65%  |
| Modem    | 3         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 59.05%  |
| Ethernet | 86        | 40.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 55.29%  |
| 1     | 90        | 43.27%  |
| 0     | 2         | 0.96%   |
| 3     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 177       | 83.49%  |
| Yes  | 35        | 16.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 31.71%  |
| Realtek Semiconductor           | 20        | 16.26%  |
| Qualcomm Atheros Communications | 16        | 13.01%  |
| Foxconn / Hon Hai               | 9         | 7.32%   |
| Cambridge Silicon Radio         | 9         | 7.32%   |
| IMC Networks                    | 6         | 4.88%   |
| Lite-On Technology              | 5         | 4.07%   |
| Broadcom                        | 5         | 4.07%   |
| Toshiba                         | 3         | 2.44%   |
| Ralink Technology               | 2         | 1.63%   |
| Ralink                          | 2         | 1.63%   |
| Apple                           | 2         | 1.63%   |
| Hewlett-Packard                 | 1         | 0.81%   |
| Foxconn International           | 1         | 0.81%   |
| Dell                            | 1         | 0.81%   |
| D-Link System                   | 1         | 0.81%   |
| Alps Electric                   | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 16.26%  |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 8.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 8.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 7.32%   |
| Realtek Bluetooth Radio                             | 7         | 5.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 5.69%   |
| Intel AX201 Bluetooth                               | 5         | 4.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 4.07%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.25%   |
| Toshiba Bluetooth Device                            | 3         | 2.44%   |
| Intel AX200 Bluetooth                               | 3         | 2.44%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.63%   |
| Lite-On Bluetooth Device                            | 2         | 1.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.81%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.81%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.81%   |
| Ralink CSR BS8510                                   | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.81%   |
| Lite-On Wireless_Device                             | 1         | 0.81%   |
| Lite-On Bluetooth Radio                             | 1         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.81%   |
| IMC Networks Bluetooth Device                       | 1         | 0.81%   |
| IMC Networks BCM20702A0                             | 1         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.81%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.81%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.81%   |
| D-Link System DBT-122 Bluetooth                     | 1         | 0.81%   |
| Broadcom HP Portable Valentine                      | 1         | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 162       | 66.12%  |
| AMD                 | 50        | 20.41%  |
| Nvidia              | 28        | 11.43%  |
| VIA Technologies    | 1         | 0.41%   |
| Samson Technologies | 1         | 0.41%   |
| Focusrite-Novation  | 1         | 0.41%   |
| Corsair             | 1         | 0.41%   |
| C-Media Electronics | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 24        | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 5.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 3.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 3.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 3.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 2.94%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.61%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.61%   |
| AMD FCH Azalia Controller                                                  | 8         | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.63%   |
| AMD Wrestler HDMI Audio                                                    | 5         | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.31%   |
| AMD High Definition Audio Controller                                       | 4         | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.98%   |
| Intel Comet Lake PCH-V cAVS                                                | 3         | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.98%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 26.4%   |
| SK hynix            | 20        | 16%     |
| Kingston            | 20        | 16%     |
| Unknown             | 13        | 10.4%   |
| Micron Technology   | 11        | 8.8%    |
| Ramaxel Technology  | 5         | 4%      |
| Corsair             | 5         | 4%      |
| A-DATA Technology   | 4         | 3.2%    |
| Nanya Technology    | 3         | 2.4%    |
| Crucial             | 3         | 2.4%    |
| Avant               | 2         | 1.6%    |
| Unknown (ABCD)      | 1         | 0.8%    |
| Team                | 1         | 0.8%    |
| PNY                 | 1         | 0.8%    |
| Hewlett-Packard     | 1         | 0.8%    |
| Goodram             | 1         | 0.8%    |
| Elpida              | 1         | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 3.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.24%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 1.49%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s          | 2         | 1.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.49%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s       | 2         | 1.49%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                          | 1         | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.75%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.75%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.75%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.75%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |
| SK hynix RAM HMA851S6DJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 0.75%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 48%     |
| DDR3    | 35        | 35%     |
| DDR2    | 6         | 6%      |
| SDRAM   | 3         | 3%      |
| LPDDR4  | 3         | 3%      |
| Unknown | 3         | 3%      |
| LPDDR3  | 2         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 69.39%  |
| DIMM         | 25        | 25.51%  |
| Row Of Chips | 3         | 3.06%   |
| Chip         | 1         | 1.02%   |
| Unknown      | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 43        | 38.74%  |
| 8192  | 33        | 29.73%  |
| 16384 | 15        | 13.51%  |
| 2048  | 14        | 12.61%  |
| 1024  | 5         | 4.5%    |
| 32768 | 1         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 29        | 25%     |
| 1600    | 25        | 21.55%  |
| 1333    | 11        | 9.48%   |
| 3200    | 9         | 7.76%   |
| 2400    | 6         | 5.17%   |
| 3266    | 5         | 4.31%   |
| 1334    | 5         | 4.31%   |
| Unknown | 4         | 3.45%   |
| 2133    | 3         | 2.59%   |
| 4199    | 2         | 1.72%   |
| 3600    | 2         | 1.72%   |
| 3466    | 2         | 1.72%   |
| 800     | 2         | 1.72%   |
| 667     | 2         | 1.72%   |
| 8400    | 1         | 0.86%   |
| 3733    | 1         | 0.86%   |
| 3400    | 1         | 0.86%   |
| 2666    | 1         | 0.86%   |
| 1867    | 1         | 0.86%   |
| 1866    | 1         | 0.86%   |
| 1066    | 1         | 0.86%   |
| 975     | 1         | 0.86%   |
| 933     | 1         | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Seiko Epson         | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L3110 Series           | 1         | 20%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| Prolific PL2305 Parallel Port      | 1         | 20%     |
| HP Ink Tank Wireless 410 series    | 1         | 20%     |
| HP Deskjet 2050 J510               | 1         | 20%     |

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
| Chicony Electronics                    | 32        | 21.77%  |
| IMC Networks                           | 19        | 12.93%  |
| Microdia                               | 12        | 8.16%   |
| Realtek Semiconductor                  | 10        | 6.8%    |
| Quanta                                 | 9         | 6.12%   |
| Syntek                                 | 7         | 4.76%   |
| Suyin                                  | 7         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.08%   |
| Sunplus Innovation Technology          | 5         | 3.4%    |
| Lite-On Technology                     | 5         | 3.4%    |
| Ricoh                                  | 3         | 2.04%   |
| Generalplus Technology                 | 3         | 2.04%   |
| Alcor Micro                            | 3         | 2.04%   |
| Acer                                   | 3         | 2.04%   |
| Silicon Motion                         | 2         | 1.36%   |
| Pixart Imaging                         | 2         | 1.36%   |
| OmniVision Technologies                | 2         | 1.36%   |
| Logitech                               | 2         | 1.36%   |
| KYE Systems (Mouse Systems)            | 2         | 1.36%   |
| Apple                                  | 2         | 1.36%   |
| Sonix Technology                       | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Luxvisions Innotech Limited            | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Jieli Technology                       | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| Genesys Logic                          | 1         | 0.68%   |
| GEMBIRD                                | 1         | 0.68%   |
| Foxconn / Hon Hai                      | 1         | 0.68%   |
| Arkmicro Technologies                  | 1         | 0.68%   |
| ALi                                    | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 6         | 4.08%   |
| IMC Networks Integrated Camera                      | 5         | 3.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.72%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.04%   |
| IMC Networks TOSHIBA Web Camera - HD                | 3         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 2.04%   |
| Chicony Integrated Camera                           | 3         | 2.04%   |
| Chicony HP Truevision HD                            | 3         | 2.04%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.36%   |
| Syntek Integrated Camera                            | 2         | 1.36%   |
| Syntek EasyCamera                                   | 2         | 1.36%   |
| Suyin Integrated_Webcam_HD                          | 2         | 1.36%   |
| Suyin HP Truevision HD                              | 2         | 1.36%   |
| Suyin HD WebCam                                     | 2         | 1.36%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.36%   |
| Realtek Integrated Webcam                           | 2         | 1.36%   |
| Realtek HD WebCam                                   | 2         | 1.36%   |
| Quanta HP Webcam-50                                 | 2         | 1.36%   |
| Quanta HP Webcam                                    | 2         | 1.36%   |
| OmniVision OV2640 Webcam                            | 2         | 1.36%   |
| Microdia Camera                                     | 2         | 1.36%   |
| Logitech Webcam C270                                | 2         | 1.36%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.36%   |
| Lite-On HP TrueVision HD Camera                     | 2         | 1.36%   |
| IMC Networks VGA UVC WebCam                         | 2         | 1.36%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.36%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.36%   |
| Chicony HD User Facing                              | 2         | 1.36%   |
| Chicony EasyCamera                                  | 2         | 1.36%   |
| Syntek USB Video Device                             | 1         | 0.68%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.68%   |
| Sunplus HP TrueVision HD Camera                     | 1         | 0.68%   |
| Sunplus HD WebCam                                   | 1         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.68%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.68%   |
| Silicon Motion Web Camera                           | 1         | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.68%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 1         | 0.68%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 4         | 28.57%  |
| Validity Sensors      | 3         | 21.43%  |
| AuthenTec             | 3         | 21.43%  |
| Upek                  | 1         | 7.14%   |
| STMicroelectronics    | 1         | 7.14%   |
| LighTuning Technology | 1         | 7.14%   |
| Elan Microelectronics | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics  WBDI                                        | 2         | 14.29%  |
| AuthenTec AES1600                                      | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 7.14%   |
| LighTuning Fingerprint Sensor                          | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 2         | 33.33%  |
| Broadcom    | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 159       | 75.36%  |
| 1     | 43        | 20.38%  |
| 2     | 8         | 3.79%   |
| 5     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 25%     |
| Fingerprint reader       | 14        | 21.88%  |
| Net/wireless             | 13        | 20.31%  |
| Chipcard                 | 6         | 9.38%   |
| Multimedia controller    | 4         | 6.25%   |
| Communication controller | 3         | 4.69%   |
| Bluetooth                | 3         | 4.69%   |
| Storage                  | 2         | 3.13%   |
| Sound                    | 2         | 3.13%   |
| Camera                   | 1         | 1.56%   |

