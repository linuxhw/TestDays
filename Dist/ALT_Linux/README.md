ALT Linux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ALT_Linux/Desktop/README.md) and [notebooks](/Dist/ALT_Linux/Notebook/README.md).

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

Total: 828

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | DP43TF AAE34878-404         | Desktop     | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| ASUSTek       | V221IC                      | All in one  | [1abad6ed2e](https://linux-hardware.org/?probe=1abad6ed2e) | Sep 03, 2023 |
| ASUSTek       | V221IC                      | All in one  | [06240bab5b](https://linux-hardware.org/?probe=06240bab5b) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| Intel         | B75                         | Desktop     | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [dfc1f52af5](https://linux-hardware.org/?probe=dfc1f52af5) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [18ace46778](https://linux-hardware.org/?probe=18ace46778) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [4b7e9a8b93](https://linux-hardware.org/?probe=4b7e9a8b93) | Aug 09, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [baf3a83d91](https://linux-hardware.org/?probe=baf3a83d91) | Aug 06, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | Desktop     | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [1096cf2959](https://linux-hardware.org/?probe=1096cf2959) | Jul 31, 2023 |
| HP            | 0AA8h                       | Desktop     | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | Notebook    | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| ASRock        | G41M-VS2                    | Desktop     | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| INSYS         | IP1-XN23                    | Notebook    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| ASUSTek       | X55A                        | Notebook    | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [6284551b74](https://linux-hardware.org/?probe=6284551b74) | Jul 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4b683fcc22](https://linux-hardware.org/?probe=4b683fcc22) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0cf82c02d3](https://linux-hardware.org/?probe=0cf82c02d3) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [da27044389](https://linux-hardware.org/?probe=da27044389) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Graviton      | N15I-T                      | Notebook    | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Graviton      | N15I-T                      | Notebook    | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [2d91c7c05a](https://linux-hardware.org/?probe=2d91c7c05a) | Jun 28, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [7007bb2db5](https://linux-hardware.org/?probe=7007bb2db5) | Jun 27, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [a2dbae939a](https://linux-hardware.org/?probe=a2dbae939a) | Jun 27, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [929fce049c](https://linux-hardware.org/?probe=929fce049c) | Jun 26, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| ASUSTek       | V221IC                      | All in one  | [c54f07785e](https://linux-hardware.org/?probe=c54f07785e) | Jun 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c4198042a](https://linux-hardware.org/?probe=0c4198042a) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| Biostar       | H610MH                      | Desktop     | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | Notebook    | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | Notebook    | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | Notebook    | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [e34e6ab643](https://linux-hardware.org/?probe=e34e6ab643) | May 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [91ad90fd67](https://linux-hardware.org/?probe=91ad90fd67) | May 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9c184f4251](https://linux-hardware.org/?probe=9c184f4251) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [1bfbf34771](https://linux-hardware.org/?probe=1bfbf34771) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d9cac69c4c](https://linux-hardware.org/?probe=d9cac69c4c) | May 16, 2023 |
| HP            | 8374 1100                   | All in one  | [2e31c0e1d5](https://linux-hardware.org/?probe=2e31c0e1d5) | May 12, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [0959f95f56](https://linux-hardware.org/?probe=0959f95f56) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [b502077711](https://linux-hardware.org/?probe=b502077711) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ab733d41de](https://linux-hardware.org/?probe=ab733d41de) | May 12, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [dea48fc3fa](https://linux-hardware.org/?probe=dea48fc3fa) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [f0fbd1eda9](https://linux-hardware.org/?probe=f0fbd1eda9) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [096f897a80](https://linux-hardware.org/?probe=096f897a80) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [7a1acf3851](https://linux-hardware.org/?probe=7a1acf3851) | May 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [848dc775e0](https://linux-hardware.org/?probe=848dc775e0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3ed55d530a](https://linux-hardware.org/?probe=3ed55d530a) | May 04, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | Notebook    | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HP            | 8374 1100                   | All in one  | [68015b73d0](https://linux-hardware.org/?probe=68015b73d0) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [a61ffc94f5](https://linux-hardware.org/?probe=a61ffc94f5) | Apr 18, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [d0c1433d54](https://linux-hardware.org/?probe=d0c1433d54) | Apr 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [ec2b541d85](https://linux-hardware.org/?probe=ec2b541d85) | Apr 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [3504e8b3bd](https://linux-hardware.org/?probe=3504e8b3bd) | Apr 11, 2023 |
| Aquarius      | Cmp NS483                   | Convertible | [2a8ffe8e0d](https://linux-hardware.org/?probe=2a8ffe8e0d) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e734b33010](https://linux-hardware.org/?probe=e734b33010) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [b0f85c7afd](https://linux-hardware.org/?probe=b0f85c7afd) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bec5bda3bd](https://linux-hardware.org/?probe=bec5bda3bd) | Apr 05, 2023 |
| Timi          | TM1701                      | Notebook    | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [9ec66a8f48](https://linux-hardware.org/?probe=9ec66a8f48) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [9d7a43d81f](https://linux-hardware.org/?probe=9d7a43d81f) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [123e95cee1](https://linux-hardware.org/?probe=123e95cee1) | Mar 22, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d06af8741](https://linux-hardware.org/?probe=5d06af8741) | Mar 22, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [24b07c4402](https://linux-hardware.org/?probe=24b07c4402) | Mar 21, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [8e021e8177](https://linux-hardware.org/?probe=8e021e8177) | Mar 21, 2023 |
| Intel         | NUC7JYB M37329-601          | Mini pc     | [b9649aaa48](https://linux-hardware.org/?probe=b9649aaa48) | Mar 21, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [1b993725aa](https://linux-hardware.org/?probe=1b993725aa) | Mar 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Biostar       | TB250-BTC                   | Desktop     | [59d148cedc](https://linux-hardware.org/?probe=59d148cedc) | Mar 11, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [8a58676b8d](https://linux-hardware.org/?probe=8a58676b8d) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [e514c2892e](https://linux-hardware.org/?probe=e514c2892e) | Mar 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| Intel         | SKYBAY                      | Desktop     | [226b8468d4](https://linux-hardware.org/?probe=226b8468d4) | Mar 09, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d62a6bc830](https://linux-hardware.org/?probe=d62a6bc830) | Mar 07, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [5fb80da27b](https://linux-hardware.org/?probe=5fb80da27b) | Mar 07, 2023 |
| ICL           | H310SB-TM                   | All in one  | [63dbb9394e](https://linux-hardware.org/?probe=63dbb9394e) | Mar 07, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [4b3689dc5c](https://linux-hardware.org/?probe=4b3689dc5c) | Mar 05, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [2e8dc3ddd2](https://linux-hardware.org/?probe=2e8dc3ddd2) | Mar 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5ab1863f2b](https://linux-hardware.org/?probe=5ab1863f2b) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| MSI           | MS-7357                     | Desktop     | [84cadfbabc](https://linux-hardware.org/?probe=84cadfbabc) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [d7f1d6a937](https://linux-hardware.org/?probe=d7f1d6a937) | Feb 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [a9267dffac](https://linux-hardware.org/?probe=a9267dffac) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| ASUSTek       | P5B-E                       | Desktop     | [92bf62be3c](https://linux-hardware.org/?probe=92bf62be3c) | Feb 11, 2023 |
| Acer          | RS880M05                    | Desktop     | [c585589925](https://linux-hardware.org/?probe=c585589925) | Feb 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [788d1d408b](https://linux-hardware.org/?probe=788d1d408b) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [97252e199d](https://linux-hardware.org/?probe=97252e199d) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | Notebook    | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | Notebook    | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | Notebook    | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Eii           | P612F                       | All in one  | [29acda8f67](https://linux-hardware.org/?probe=29acda8f67) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | Desktop     | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [9a8967485d](https://linux-hardware.org/?probe=9a8967485d) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | Notebook    | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Pegatron      | C15B                        | Notebook    | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | Notebook    | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | Notebook    | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [25e63313c0](https://linux-hardware.org/?probe=25e63313c0) | Dec 13, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [b58d61f85f](https://linux-hardware.org/?probe=b58d61f85f) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Graviton      | DMB-H610-TMI01              | All in one  | [0b2b77d521](https://linux-hardware.org/?probe=0b2b77d521) | Dec 12, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | Notebook    | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | Notebook    | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Samsung       | R560                        | Notebook    | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | Notebook    | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | Notebook    | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| MSI           | J1800I                      | Desktop     | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | Notebook    | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | Notebook    | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [ece886e874](https://linux-hardware.org/?probe=ece886e874) | Nov 17, 2022 |
| Timi          | TM1701                      | Notebook    | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | Notebook    | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | Desktop     | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| Acer          | TravelMate 6292             | Notebook    | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae13c0bb6b](https://linux-hardware.org/?probe=ae13c0bb6b) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | Notebook    | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [a28efd61d1](https://linux-hardware.org/?probe=a28efd61d1) | Oct 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | Desktop     | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| Acer          | AOA150                      | Notebook    | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | Notebook    | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | Notebook    | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | Notebook    | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| HP            | 83EB                        | All in one  | [beb4a8d108](https://linux-hardware.org/?probe=beb4a8d108) | Aug 03, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | Notebook    | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| OEM           | KX-18 V1.0                  | Desktop     | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | Notebook    | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | Notebook    | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [8598f1f5ee](https://linux-hardware.org/?probe=8598f1f5ee) | Jun 30, 2022 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [a473baa2ff](https://linux-hardware.org/?probe=a473baa2ff) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [12009b21d8](https://linux-hardware.org/?probe=12009b21d8) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [3f2bf77788](https://linux-hardware.org/?probe=3f2bf77788) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [83881d4eb6](https://linux-hardware.org/?probe=83881d4eb6) | Mar 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [2379c7546f](https://linux-hardware.org/?probe=2379c7546f) | Mar 09, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| Dell          | G5 5590                     | Notebook    | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [4f93db2c52](https://linux-hardware.org/?probe=4f93db2c52) | Mar 05, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [04a1a09e43](https://linux-hardware.org/?probe=04a1a09e43) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | Notebook    | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| T-Platform... | TF307-MB                    | Soc         | [c34cd190e4](https://linux-hardware.org/?probe=c34cd190e4) | Feb 01, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| Dell          | Latitude 3590               | Notebook    | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| MSI           | MS-AC16 100                 | All in one  | [3a3bfc48f7](https://linux-hardware.org/?probe=3a3bfc48f7) | Jan 17, 2022 |
| MSI           | A68HM-P33 V2                | Desktop     | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | Desktop     | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [adc426b903](https://linux-hardware.org/?probe=adc426b903) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| Samsung       | 750XDA                      | Notebook    | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Unknown       | Baikal Electronics Baika... | Soc         | [b4e6606b42](https://linux-hardware.org/?probe=b4e6606b42) | Dec 10, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| HUAWEI        | BC11SPSCB0 V100R005         | Server      | [ad903545ce](https://linux-hardware.org/?probe=ad903545ce) | Oct 14, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | Desktop     | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [92829c951d](https://linux-hardware.org/?probe=92829c951d) | Sep 21, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| Timi          | TM1701                      | Notebook    | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | Notebook    | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | Notebook    | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| Durabook      | Z14                         | Notebook    | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Aquarius      | NS483                       | Convertible | [bc5d045def](https://linux-hardware.org/?probe=bc5d045def) | Jul 20, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Aquarius      | NS585                       | Notebook    | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | Desktop     | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [d31e4518a6](https://linux-hardware.org/?probe=d31e4518a6) | Jun 22, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| Dell          | G3 3779                     | Notebook    | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | Notebook    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | T09-D                       | Stick pc    | [678542f4fe](https://linux-hardware.org/?probe=678542f4fe) | May 18, 2021 |
| DEPO Compu... | DPH410S                     | Desktop     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | Desktop     | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| Lenovo        | 3184 No DPK                 | All in one  | [bd5551c49a](https://linux-hardware.org/?probe=bd5551c49a) | Mar 31, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | Desktop     | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | Desktop     | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Dell          | 04G47W A00                  | All in one  | [3a565370de](https://linux-hardware.org/?probe=3a565370de) | Feb 15, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| Supermicro    | X11DPH-i                    | Server      | [8d109ac7b4](https://linux-hardware.org/?probe=8d109ac7b4) | Jan 26, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | Desktop     | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [593a489e8d](https://linux-hardware.org/?probe=593a489e8d) | Jan 13, 2021 |
| Intel         | B75                         | Desktop     | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Acer          | NC-ES1-131-C1NL             | Notebook    | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| Irbis         | TW100                       | Tablet      | [23c593482c](https://linux-hardware.org/?probe=23c593482c) | Dec 28, 2020 |
| SYS           | H310SB                      | Desktop     | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | Desktop     | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| MSI           | MS-AC16 100                 | All in one  | [8df63d744b](https://linux-hardware.org/?probe=8df63d744b) | Dec 23, 2020 |
| HP            | 877E A                      | Desktop     | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | Notebook    | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Irbis         | TW100                       | Tablet      | [5ebe1b6e89](https://linux-hardware.org/?probe=5ebe1b6e89) | Dec 19, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cf089cfa1](https://linux-hardware.org/?probe=5cf089cfa1) | Dec 07, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | Desktop     | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| Acer          | Veriton Z4860G              | All in one  | [8adebb44d3](https://linux-hardware.org/?probe=8adebb44d3) | Nov 20, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | Desktop     | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | Desktop     | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| MSI           | X300/X340/X400 series       | Notebook    | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | Desktop     | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| Samsung       | R510/P510                   | Notebook    | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [cee7ed2ce9](https://linux-hardware.org/?probe=cee7ed2ce9) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [f31ffbf544](https://linux-hardware.org/?probe=f31ffbf544) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [72c1d1ffca](https://linux-hardware.org/?probe=72c1d1ffca) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [298376a45e](https://linux-hardware.org/?probe=298376a45e) | Jun 23, 2020 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [b03abee3fb](https://linux-hardware.org/?probe=b03abee3fb) | Jun 12, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [70139de021](https://linux-hardware.org/?probe=70139de021) | Jun 10, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ee83d50faa](https://linux-hardware.org/?probe=ee83d50faa) | Jun 10, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [861b6c69a0](https://linux-hardware.org/?probe=861b6c69a0) | May 21, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ae09cd2a40](https://linux-hardware.org/?probe=ae09cd2a40) | May 21, 2020 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | Notebook    | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| HP            | 09F0h                       | Desktop     | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| HUAWEI        | BC11HGSB0 V100R003          | Server      | [5eb4dfc951](https://linux-hardware.org/?probe=5eb4dfc951) | Oct 22, 2019 |
| Dell          | 0F96C8 A00                  | All in one  | [29d0ad2441](https://linux-hardware.org/?probe=29d0ad2441) | Oct 22, 2019 |
| MSI           | B350M PRO-VDH               | Desktop     | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| MSI           | MEGA BOOK S430              | Notebook    | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | Desktop     | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | Desktop     | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | Desktop     | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | Notebook    | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 165       | 26.92%  |
| ALT Linux 10.1     | 120       | 19.58%  |
| ALT Linux 9.1      | 65        | 10.6%   |
| MOS 10             | 61        | 9.95%   |
| ALT Linux 10.0     | 56        | 9.14%   |
| ALT Linux 9.0      | 31        | 5.06%   |
| ALT Linux 9.2      | 18        | 2.94%   |
| ALT Linux 10.2     | 15        | 2.45%   |
| ALT Linux P10      | 11        | 1.79%   |
| ALT Linux 8.4      | 11        | 1.79%   |
| ALT Linux 10.1.900 | 8         | 1.31%   |
| ALT Linux 10.0.900 | 6         | 0.98%   |
| ALT Linux P8       | 5         | 0.82%   |
| ALT Linux 8.2      | 5         | 0.82%   |
| ALT Linux P9       | 4         | 0.65%   |
| ALT Linux 20220110 | 4         | 0.65%   |
| ALT Linux 20201124 | 4         | 0.65%   |
| ALT Linux 10       | 4         | 0.65%   |
| ALT Linux 7.0.5    | 2         | 0.33%   |
| ALT Linux 20191026 | 2         | 0.33%   |
| Kometa 1           | 1         | 0.16%   |
| ALT Linux 9.1.990  | 1         | 0.16%   |
| ALT Linux 9        | 1         | 0.16%   |
| ALT Linux 8.990    | 1         | 0.16%   |
| ALT Linux 8.93     | 1         | 0.16%   |
| ALT Linux 8.920    | 1         | 0.16%   |
| ALT Linux 8.3      | 1         | 0.16%   |
| ALT Linux 8.2.0    | 1         | 0.16%   |
| ALT Linux 8.0.0    | 1         | 0.16%   |
| ALT Linux 8.0      | 1         | 0.16%   |
| ALT Linux 20190624 | 1         | 0.16%   |
| ALT Linux 20190303 | 1         | 0.16%   |
| ALT Linux 10.0.920 | 1         | 0.16%   |
| ALT Linux 10.0.910 | 1         | 0.16%   |
| ALT Linux 0.7.6    | 1         | 0.16%   |
| ALT Linux          | 1         | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ALT Linux | 579       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.109-std-def-alt1      | 85        | 13.28%  |
| 5.10.102-std-def-alt1      | 80        | 12.5%   |
| 5.15.72-un-def-alt1        | 19        | 2.97%   |
| 5.15.34-un-def-alt1        | 19        | 2.97%   |
| 5.10.139-std-def-alt1      | 18        | 2.81%   |
| 5.15.80-un-def-alt1        | 16        | 2.5%    |
| 5.10.82-std-def-alt1       | 16        | 2.5%    |
| 5.10.156-std-def-alt1      | 14        | 2.19%   |
| 5.4.51-std-def-alt1        | 12        | 1.88%   |
| 5.10.164-std-def-alt1      | 12        | 1.88%   |
| 5.10.123-std-def-alt1      | 12        | 1.88%   |
| 5.10.88-std-def-alt1       | 11        | 1.72%   |
| 4.19.79-std-def-alt1       | 11        | 1.72%   |
| 5.4.68-std-def-alt1.1      | 10        | 1.56%   |
| 5.10.152-std-def-alt1      | 7         | 1.09%   |
| 6.1.38-un-def-alt1         | 6         | 0.94%   |
| 5.4.28-std-def-alt1        | 6         | 0.94%   |
| 5.15.76-un-def-alt1        | 5         | 0.78%   |
| 5.15.32-un-def-alt1        | 5         | 0.78%   |
| 5.10.93-std-def-alt1       | 5         | 0.78%   |
| 5.10.83-std-def-alt0.c9f.2 | 5         | 0.78%   |
| 5.10.32-un-def-alt1        | 5         | 0.78%   |
| 5.10.145-std-def-alt1      | 5         | 0.78%   |
| 5.7.19-un-def-alt1         | 4         | 0.63%   |
| 5.4.62-std-def-alt1        | 4         | 0.63%   |
| 5.4.41-std-def-alt1        | 4         | 0.63%   |
| 5.10.35-un-def-alt1        | 4         | 0.63%   |
| 5.10.179-std-def-alt1      | 4         | 0.63%   |
| 5.10.17-un-def-alt1        | 4         | 0.63%   |
| 5.4.85-std-def-alt1        | 3         | 0.47%   |
| 5.4.127-std-def-alt1       | 3         | 0.47%   |
| 5.15.79-un-def-alt1        | 3         | 0.47%   |
| 5.15.74-un-def-alt1        | 3         | 0.47%   |
| 5.15.73-un-def-alt1        | 3         | 0.47%   |
| 5.15.70-un-def-alt1        | 3         | 0.47%   |
| 5.15.63-un-def-alt1        | 3         | 0.47%   |
| 5.15.15-un-def-alt1        | 3         | 0.47%   |
| 5.10.72-std-def-alt1       | 3         | 0.47%   |
| 5.10.186-std-def-alt1      | 3         | 0.47%   |
| 5.10.168-std-def-alt1      | 3         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.109 | 85        | 13.28%  |
| 5.10.102 | 80        | 12.5%   |
| 5.15.72  | 19        | 2.97%   |
| 5.15.34  | 19        | 2.97%   |
| 5.10.139 | 18        | 2.81%   |
| 5.15.80  | 17        | 2.66%   |
| 5.10.82  | 16        | 2.5%    |
| 5.10.156 | 15        | 2.34%   |
| 5.4.51   | 12        | 1.88%   |
| 5.10.164 | 12        | 1.88%   |
| 5.10.123 | 12        | 1.88%   |
| 5.10.88  | 11        | 1.72%   |
| 4.19.79  | 11        | 1.72%   |
| 5.4.68   | 10        | 1.56%   |
| 5.10.152 | 7         | 1.09%   |
| 6.1.38   | 6         | 0.94%   |
| 5.4.28   | 6         | 0.94%   |
| 5.15.76  | 5         | 0.78%   |
| 5.15.32  | 5         | 0.78%   |
| 5.10.93  | 5         | 0.78%   |
| 5.10.83  | 5         | 0.78%   |
| 5.10.35  | 5         | 0.78%   |
| 5.10.32  | 5         | 0.78%   |
| 5.10.145 | 5         | 0.78%   |
| 5.7.19   | 4         | 0.63%   |
| 5.4.62   | 4         | 0.63%   |
| 5.4.41   | 4         | 0.63%   |
| 5.10.179 | 4         | 0.63%   |
| 5.10.17  | 4         | 0.63%   |
| 5.10.118 | 4         | 0.63%   |
| 5.4.85   | 3         | 0.47%   |
| 5.4.127  | 3         | 0.47%   |
| 5.15.79  | 3         | 0.47%   |
| 5.15.74  | 3         | 0.47%   |
| 5.15.73  | 3         | 0.47%   |
| 5.15.70  | 3         | 0.47%   |
| 5.15.63  | 3         | 0.47%   |
| 5.15.15  | 3         | 0.47%   |
| 5.10.72  | 3         | 0.47%   |
| 5.10.54  | 3         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 356       | 59.14%  |
| 5.15    | 102       | 16.94%  |
| 5.4     | 64        | 10.63%  |
| 4.19    | 26        | 4.32%   |
| 6.1     | 18        | 2.99%   |
| 4.9     | 7         | 1.16%   |
| 5.7     | 5         | 0.83%   |
| 6.2     | 3         | 0.5%    |
| 5.2     | 3         | 0.5%    |
| 5.18    | 3         | 0.5%    |
| 5.13    | 3         | 0.5%    |
| 6.4     | 2         | 0.33%   |
| 5.14    | 2         | 0.33%   |
| 4.14    | 2         | 0.33%   |
| 5.9     | 1         | 0.17%   |
| 5.3     | 1         | 0.17%   |
| 5.16    | 1         | 0.17%   |
| 5.12    | 1         | 0.17%   |
| 4.4     | 1         | 0.17%   |
| 4.20    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 556       | 96.03%  |
| i686    | 16        | 2.76%   |
| aarch64 | 4         | 0.69%   |
| e2k     | 3         | 0.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 384       | 64.97%  |
| XFCE            | 88        | 14.89%  |
| Unknown         | 84        | 14.21%  |
| MATE            | 14        | 2.37%   |
| LXQt            | 7         | 1.18%   |
| Cinnamon        | 6         | 1.02%   |
| GNOME           | 4         | 0.68%   |
| KDE             | 2         | 0.34%   |
| GNOME Flashback | 2         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 560       | 96.22%  |
| Unknown | 10        | 1.72%   |
| Tty     | 7         | 1.2%    |
| Wayland | 5         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 314       | 52.95%  |
| LightDM | 134       | 22.6%   |
| Unknown | 79        | 13.32%  |
| TDM     | 62        | 10.46%  |
| GDM     | 2         | 0.34%   |
| XDM     | 1         | 0.17%   |
| WDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| ru_RU      | 486       | 81.96%  |
| Unknown    | 81        | 13.66%  |
| en_US      | 17        | 2.87%   |
| POSIX      | 6         | 1.01%   |
| it_IT@euro | 1         | 0.17%   |
| el_GR      | 1         | 0.17%   |
| C          | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 376       | 64.38%  |
| BIOS | 208       | 35.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 520       | 89.19%  |
| Overlay | 37        | 6.35%   |
| Btrfs   | 23        | 3.95%   |
| Unknown | 2         | 0.34%   |
| Xfs     | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 361       | 61.39%  |
| MBR     | 145       | 24.66%  |
| Unknown | 82        | 13.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 521       | 89.06%  |
| Yes       | 64        | 10.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 406       | 69.4%   |
| Yes       | 179       | 30.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 77        | 13.3%   |
| Hewlett-Packard         | 70        | 12.09%  |
| Intel                   | 58        | 10.02%  |
| Lenovo                  | 44        | 7.6%    |
| Gigabyte Technology     | 41        | 7.08%   |
| Acer                    | 37        | 6.39%   |
| Clevo                   | 32        | 5.53%   |
| 3Logic Group            | 27        | 4.66%   |
| MSI                     | 23        | 3.97%   |
| ASRock                  | 23        | 3.97%   |
| ICL                     | 21        | 3.63%   |
| Unknown                 | 16        | 2.76%   |
| Dell                    | 14        | 2.42%   |
| HUAWEI                  | 11        | 1.9%    |
| DEPO Computers          | 10        | 1.73%   |
| Graviton                | 7         | 1.21%   |
| Samsung Electronics     | 6         | 1.04%   |
| Aquarius                | 5         | 0.86%   |
| Apple                   | 5         | 0.86%   |
| Supermicro              | 4         | 0.69%   |
| MAINBRD                 | 4         | 0.69%   |
| Toshiba                 | 3         | 0.52%   |
| iRU                     | 3         | 0.52%   |
| Biostar                 | 3         | 0.52%   |
| Timi                    | 2         | 0.35%   |
| Panasonic               | 2         | 0.35%   |
| Kraftway                | 2         | 0.35%   |
| Irbis                   | 2         | 0.35%   |
| Yadro                   | 1         | 0.17%   |
| VIA Technologies        | 1         | 0.17%   |
| Valve                   | 1         | 0.17%   |
| T-Platforms             | 1         | 0.17%   |
| SYS                     | 1         | 0.17%   |
| Sony                    | 1         | 0.17%   |
| Raspberry Pi Foundation | 1         | 0.17%   |
| Pegatron                | 1         | 0.17%   |
| OEM                     | 1         | 0.17%   |
| LTD Delovoy Office      | 1         | 0.17%   |
| IP3 Technology          | 1         | 0.17%   |
| IP3 Tech                | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel SKYBAY                             | 47        | 8.12%   |
| Clevo NL41MU2                            | 32        | 5.53%   |
| 3Logic Group Graviton                    | 20        | 3.45%   |
| Unknown                                  | 18        | 3.11%   |
| HP 250 G7 Notebook PC                    | 12        | 2.07%   |
| ASUS PRIME B450-PLUS                     | 12        | 2.07%   |
| Lenovo V540-24IWL AIO 10YS0031RU         | 10        | 1.73%   |
| Acer Veriton X2640G                      | 10        | 1.73%   |
| HP ZBook 17 G5                           | 9         | 1.55%   |
| HP ProBook 440 G5                        | 8         | 1.38%   |
| ICL RAYbook Si1512                       | 6         | 1.04%   |
| Lenovo ThinkSystem SR590 -[7X99CTO1WW]-  | 5         | 0.86%   |
| MAINBRD OPS62A-SHA                       | 4         | 0.69%   |
| ICL RAY Si105.Mi                         | 4         | 0.69%   |
| ICL RAY S122.Mi                          | 4         | 0.69%   |
| Gigabyte H110M-S2H                       | 4         | 0.69%   |
| DEPO Computers DPC156                    | 4         | 0.69%   |
| Lenovo ThinkBook 15 G2 ITL 20VE          | 3         | 0.52%   |
| HUAWEI NBD-WXX9                          | 3         | 0.52%   |
| HP EliteBook 840 G4                      | 3         | 0.52%   |
| HP 250 G6 Notebook PC                    | 3         | 0.52%   |
| Graviton DMB-A520-MCA01                  | 3         | 0.52%   |
| Dell Latitude 3420                       | 3         | 0.52%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA | 3         | 0.52%   |
| ASUS H110M-R                             | 3         | 0.52%   |
| 3Logic Group Graviton N15i-K2            | 3         | 0.52%   |
| 3Logic Group Graviton N15i               | 3         | 0.52%   |
| Supermicro Super Server                  | 2         | 0.35%   |
| MSI MS-7D46                              | 2         | 0.35%   |
| MSI MPG B560 Trident A (MS-B926)         | 2         | 0.35%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT     | 2         | 0.35%   |
| iRU 515                                  | 2         | 0.35%   |
| Irbis TW100                              | 2         | 0.35%   |
| Intel B75                                | 2         | 0.35%   |
| ICL NJ50_70CU                            | 2         | 0.35%   |
| ICL H510SB-TM                            | 2         | 0.35%   |
| HUAWEI KLVL-WXXW                         | 2         | 0.35%   |
| HP ProBook 440 G4                        | 2         | 0.35%   |
| HP EliteBook 8470p                       | 2         | 0.35%   |
| Gigabyte H77M-D3H                        | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Intel SKYBAY            | 47        | 8.12%   |
| Clevo NL41MU2           | 32        | 5.53%   |
| 3Logic Group Graviton   | 27        | 4.66%   |
| ASUS PRIME              | 18        | 3.11%   |
| Unknown                 | 18        | 3.11%   |
| HP 250                  | 16        | 2.76%   |
| Acer Veriton            | 16        | 2.76%   |
| HP ProBook              | 13        | 2.25%   |
| Acer Aspire             | 13        | 2.25%   |
| Lenovo V540-24IWL       | 10        | 1.73%   |
| HP Pavilion             | 10        | 1.73%   |
| HP ZBook                | 9         | 1.55%   |
| ICL RAY                 | 8         | 1.38%   |
| HP EliteBook            | 8         | 1.38%   |
| ICL RAYbook             | 7         | 1.21%   |
| ASUS VivoBook           | 7         | 1.21%   |
| Lenovo ThinkPad         | 6         | 1.04%   |
| Lenovo IdeaPad          | 6         | 1.04%   |
| ASUS ASUS               | 6         | 1.04%   |
| Lenovo ThinkSystem      | 5         | 0.86%   |
| HP Laptop               | 5         | 0.86%   |
| Dell Latitude           | 5         | 0.86%   |
| MAINBRD OPS62A-SHA      | 4         | 0.69%   |
| Gigabyte H110M-S2H      | 4         | 0.69%   |
| DEPO Computers DPC156   | 4         | 0.69%   |
| Dell OptiPlex           | 4         | 0.69%   |
| Acer TravelMate         | 4         | 0.69%   |
| Lenovo ThinkBook        | 3         | 0.52%   |
| HUAWEI NBD-WXX9         | 3         | 0.52%   |
| Graviton DMB-A520-MCA01 | 3         | 0.52%   |
| ASUS P7H55-M            | 3         | 0.52%   |
| ASUS H110M-R            | 3         | 0.52%   |
| Toshiba Satellite       | 2         | 0.35%   |
| Supermicro Super        | 2         | 0.35%   |
| MSI MS-7D46             | 2         | 0.35%   |
| MSI MPG                 | 2         | 0.35%   |
| Lenovo ThinkCentre      | 2         | 0.35%   |
| iRU 515                 | 2         | 0.35%   |
| Irbis TW100             | 2         | 0.35%   |
| Intel B75               | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 79        | 13.64%  |
| 2022    | 78        | 13.47%  |
| 2020    | 66        | 11.4%   |
| 2017    | 62        | 10.71%  |
| 2021    | 57        | 9.84%   |
| 2019    | 44        | 7.6%    |
| 2016    | 31        | 5.35%   |
| 2012    | 23        | 3.97%   |
| 2010    | 20        | 3.45%   |
| 2011    | 18        | 3.11%   |
| 2008    | 16        | 2.76%   |
| 2014    | 15        | 2.59%   |
| 2009    | 15        | 2.59%   |
| 2015    | 12        | 2.07%   |
| 2013    | 10        | 1.73%   |
| 2007    | 10        | 1.73%   |
| 2006    | 9         | 1.55%   |
| Unknown | 5         | 0.86%   |
| 2023    | 4         | 0.69%   |
| 2005    | 3         | 0.52%   |
| 2004    | 1         | 0.17%   |
| 2003    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 250       | 43.18%  |
| Desktop        | 249       | 43.01%  |
| All in one     | 54        | 9.33%   |
| Server         | 10        | 1.73%   |
| Mini pc        | 5         | 0.86%   |
| System on chip | 4         | 0.69%   |
| Convertible    | 4         | 0.69%   |
| Tablet         | 2         | 0.35%   |
| Stick pc       | 1         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 506       | 86.79%  |
| Enabled  | 77        | 13.21%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 579       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 202       | 34.83%  |
| 8.01-16.0       | 121       | 20.86%  |
| 16.01-24.0      | 114       | 19.66%  |
| 3.01-4.0        | 79        | 13.62%  |
| 1.01-2.0        | 23        | 3.97%   |
| 32.01-64.0      | 14        | 2.41%   |
| 64.01-256.0     | 13        | 2.24%   |
| 2.01-3.0        | 7         | 1.21%   |
| 24.01-32.0      | 3         | 0.52%   |
| 0.51-1.0        | 3         | 0.52%   |
| More than 256.0 | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 310       | 50.74%  |
| 2.01-3.0   | 104       | 17.02%  |
| 0.51-1.0   | 82        | 13.42%  |
| 4.01-8.0   | 48        | 7.86%   |
| 3.01-4.0   | 45        | 7.36%   |
| 8.01-16.0  | 10        | 1.64%   |
| 0.01-0.5   | 10        | 1.64%   |
| 32.01-64.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 431       | 73.05%  |
| 2       | 103       | 17.46%  |
| 3       | 28        | 4.75%   |
| 4       | 11        | 1.86%   |
| 5       | 7         | 1.19%   |
| 0       | 6         | 1.02%   |
| 8       | 2         | 0.34%   |
| 6       | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 402       | 69.07%  |
| Yes       | 180       | 30.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 536       | 92.57%  |
| No        | 43        | 7.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 352       | 60.79%  |
| No        | 227       | 39.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 52.41%  |
| No        | 277       | 47.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Russia     | 552       | 95.34%  |
| Greece     | 6         | 1.04%   |
| Ukraine    | 4         | 0.69%   |
| Egypt      | 2         | 0.35%   |
| Belarus    | 2         | 0.35%   |
| Uzbekistan | 1         | 0.17%   |
| USA        | 1         | 0.17%   |
| Moldova    | 1         | 0.17%   |
| Kazakhstan | 1         | 0.17%   |
| Italy      | 1         | 0.17%   |
| France     | 1         | 0.17%   |
| Finland    | 1         | 0.17%   |
| Estonia    | 1         | 0.17%   |
| Czechia    | 1         | 0.17%   |
| Costa Rica | 1         | 0.17%   |
| Colombia   | 1         | 0.17%   |
| China      | 1         | 0.17%   |
| Australia  | 1         | 0.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 358       | 60.68%  |
| St Petersburg     | 35        | 5.93%   |
| Samara            | 12        | 2.03%   |
| Novosibirsk       | 10        | 1.69%   |
| Barnaul           | 9         | 1.53%   |
| Krasnoyarsk       | 7         | 1.19%   |
| Irkutsk           | 6         | 1.02%   |
| Chelyabinsk       | 5         | 0.85%   |
| Yekaterinburg     | 4         | 0.68%   |
| Saratov           | 4         | 0.68%   |
| Perm              | 4         | 0.68%   |
| Obninsk           | 4         | 0.68%   |
| Kaliningrad       | 4         | 0.68%   |
| Surgut            | 3         | 0.51%   |
| Sevastopol        | 3         | 0.51%   |
| Rostov-on-Don     | 3         | 0.51%   |
| Korolyov          | 3         | 0.51%   |
| Kirov             | 3         | 0.51%   |
| Belgorod          | 3         | 0.51%   |
| Astrakhan         | 3         | 0.51%   |
| Zheleznodorozhnyy | 2         | 0.34%   |
| Zelenodolsk       | 2         | 0.34%   |
| Voronezh          | 2         | 0.34%   |
| Vladivostok       | 2         | 0.34%   |
| Vladimir          | 2         | 0.34%   |
| Verkhnyaya Pyshma | 2         | 0.34%   |
| Vergina           | 2         | 0.34%   |
| Ufa               | 2         | 0.34%   |
| Tyumen            | 2         | 0.34%   |
| Thessaloniki      | 2         | 0.34%   |
| Tambov            | 2         | 0.34%   |
| Nizhny Tagil      | 2         | 0.34%   |
| Lipetsk           | 2         | 0.34%   |
| Krasnodar         | 2         | 0.34%   |
| Kostroma          | 2         | 0.34%   |
| Kazan’          | 2         | 0.34%   |
| Donetsk           | 2         | 0.34%   |
| Yessentuki        | 1         | 0.17%   |
| Vologda           | 1         | 0.17%   |
| Vikhorevka        | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 99        | 139    | 13.38%  |
| Seagate                     | 92        | 129    | 12.43%  |
| Samsung Electronics         | 77        | 97     | 10.41%  |
| Toshiba                     | 47        | 67     | 6.35%   |
| Kingston                    | 47        | 52     | 6.35%   |
| Apacer                      | 34        | 39     | 4.59%   |
| BIWIN                       | 33        | 34     | 4.46%   |
| Intel                       | 31        | 39     | 4.19%   |
| SK hynix                    | 30        | 32     | 4.05%   |
| AXIOMTEK                    | 29        | 31     | 3.92%   |
| A-DATA Technology           | 23        | 27     | 3.11%   |
| Hitachi                     | 15        | 16     | 2.03%   |
| China                       | 12        | 13     | 1.62%   |
| Foxline                     | 10        | 10     | 1.35%   |
| Crucial                     | 10        | 12     | 1.35%   |
| SanDisk                     | 9         | 10     | 1.22%   |
| Phison                      | 9         | 10     | 1.22%   |
| HGST                        | 9         | 9      | 1.22%   |
| Unknown                     | 8         | 14     | 1.08%   |
| AMD                         | 7         | 7      | 0.95%   |
| XPG                         | 6         | 7      | 0.81%   |
| Micron Technology           | 6         | 11     | 0.81%   |
| Gigabyte Technology         | 6         | 6      | 0.81%   |
| Plextor                     | 5         | 5      | 0.68%   |
| Transcend                   | 4         | 5      | 0.54%   |
| Smartbuy                    | 4         | 4      | 0.54%   |
| Patriot                     | 4         | 6      | 0.54%   |
| KingSpec                    | 4         | 4      | 0.54%   |
| Fujitsu                     | 4         | 4      | 0.54%   |
| SPCC                        | 3         | 3      | 0.41%   |
| Silicon Motion              | 3         | 4      | 0.41%   |
| Phison Electronics          | 3         | 3      | 0.41%   |
| Netac                       | 3         | 4      | 0.41%   |
| Unknown                     | 3         | 4      | 0.41%   |
| XrayDisk                    | 2         | 2      | 0.27%   |
| TMI                         | 2         | 3      | 0.27%   |
| Team                        | 2         | 2      | 0.27%   |
| SSSTC                       | 2         | 2      | 0.27%   |
| PNY                         | 2         | 2      | 0.27%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB               | 32        | 4.12%   |
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD      | 29        | 3.73%   |
| Samsung MZVLW128HEGR-00000 128GB          | 18        | 2.32%   |
| Apacer AS2280P4 256GB                     | 18        | 2.32%   |
| Toshiba HDWD120 2TB                       | 13        | 1.67%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 13        | 1.67%   |
| WDC WD5000AZLX-21K2TA0 500GB              | 10        | 1.29%   |
| Seagate ST1000LM049-2GH172 1TB            | 10        | 1.29%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB | 9         | 1.16%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 9         | 1.16%   |
| Intel SSDPEMKF256G8H 256GB                | 8         | 1.03%   |
| Intel SSDPEKKF256G7H 256GB                | 8         | 1.03%   |
| Toshiba HDWD110 1TB                       | 7         | 0.9%    |
| Toshiba DT01ACA100 1TB                    | 6         | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB            | 6         | 0.77%   |
| Samsung SSD 860 EVO 250GB                 | 6         | 0.77%   |
| Phison 311CD0512GB                        | 5         | 0.64%   |
| Kingston SA400S37240G 240GB SSD           | 5         | 0.64%   |
| Kingston RBUSC180S37256GJ 256GB SSD       | 5         | 0.64%   |
| Crucial CT240BX500SSD1 240GB              | 5         | 0.64%   |
| Apacer AS350 256GB SSD                    | 5         | 0.64%   |
| A-DATA SU650 240GB SSD                    | 5         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 4         | 0.51%   |
| Seagate ST380815AS 80GB                   | 4         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 0.51%   |
| Samsung SSD 970 EVO Plus 250GB            | 4         | 0.51%   |
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD          | 4         | 0.51%   |
| Kingston SA400S37120G 120GB SSD           | 4         | 0.51%   |
| XPG SPECTRIX S40G 1TB                     | 3         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 3         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 3         | 0.39%   |
| WDC WDS240G1G0A-00SS50 240GB SSD          | 3         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 3         | 0.39%   |
| WDC WD10EZEX-00BBHA0 1TB                  | 3         | 0.39%   |
| Toshiba MQ04ABF100 1TB                    | 3         | 0.39%   |
| Seagate ST9250315AS 250GB                 | 3         | 0.39%   |
| Seagate ST500LM030-2E717D 500GB           | 3         | 0.39%   |
| Seagate ST500DM002-1BD142 500GB           | 3         | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB            | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 123    | 36%     |
| WDC                 | 77        | 112    | 30.8%   |
| Toshiba             | 45        | 64     | 18%     |
| Hitachi             | 15        | 16     | 6%      |
| HGST                | 9         | 9      | 3.6%    |
| Samsung Electronics | 6         | 7      | 2.4%    |
| Fujitsu             | 4         | 4      | 1.6%    |
| SINTECHI            | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| FreeBSD             | 1         | 1      | 0.4%    |
| External            | 1         | 2      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 33        | 36     | 13.98%  |
| AXIOMTEK            | 29        | 31     | 12.29%  |
| Samsung Electronics | 21        | 24     | 8.9%    |
| A-DATA Technology   | 17        | 19     | 7.2%    |
| WDC                 | 16        | 19     | 6.78%   |
| Apacer              | 13        | 17     | 5.51%   |
| China               | 12        | 13     | 5.08%   |
| Crucial             | 9         | 11     | 3.81%   |
| AMD                 | 6         | 6      | 2.54%   |
| SanDisk             | 5         | 5      | 2.12%   |
| Plextor             | 5         | 5      | 2.12%   |
| Intel               | 5         | 9      | 2.12%   |
| Transcend           | 4         | 5      | 1.69%   |
| Smartbuy            | 4         | 4      | 1.69%   |
| Patriot             | 4         | 6      | 1.69%   |
| Micron Technology   | 4         | 9      | 1.69%   |
| KingSpec            | 4         | 4      | 1.69%   |
| Gigabyte Technology | 3         | 3      | 1.27%   |
| XrayDisk            | 2         | 2      | 0.85%   |
| TMI                 | 2         | 3      | 0.85%   |
| Team                | 2         | 2      | 0.85%   |
| SK hynix            | 2         | 2      | 0.85%   |
| Seagate             | 2         | 6      | 0.85%   |
| PNY                 | 2         | 2      | 0.85%   |
| Phison              | 2         | 2      | 0.85%   |
| Netac               | 2         | 2      | 0.85%   |
| JMicron Technology  | 2         | 2      | 0.85%   |
| Foxline             | 2         | 2      | 0.85%   |
| DEPO                | 2         | 2      | 0.85%   |
| Unknown             | 2         | 3      | 0.85%   |
| SPCC                | 1         | 1      | 0.42%   |
| SP-8                | 1         | 1      | 0.42%   |
| OCZ                 | 1         | 1      | 0.42%   |
| MaiChai             | 1         | 1      | 0.42%   |
| LuminouTek          | 1         | 1      | 0.42%   |
| LITEON              | 1         | 1      | 0.42%   |
| KingDian            | 1         | 1      | 0.42%   |
| HYDRA               | 1         | 1      | 0.42%   |
| HS-SSD-C100         | 1         | 1      | 0.42%   |
| HEORIADY            | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 237       | 280    | 34.45%  |
| HDD  | 222       | 340    | 32.27%  |
| SSD  | 217       | 278    | 31.54%  |
| MMC  | 12        | 18     | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 367       | 606    | 58.72%  |
| NVMe | 237       | 280    | 37.92%  |
| MMC  | 12        | 18     | 1.92%   |
| SAS  | 9         | 12     | 1.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 291       | 377    | 66.14%  |
| 0.51-1.0   | 105       | 161    | 23.86%  |
| 1.01-2.0   | 34        | 68     | 7.73%   |
| 3.01-4.0   | 3         | 3      | 0.68%   |
| 2.01-3.0   | 3         | 4      | 0.68%   |
| 4.01-10.0  | 3         | 4      | 0.68%   |
| 0          | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 306       | 50.92%  |
| 251-500        | 88        | 14.64%  |
| 1001-2000      | 46        | 7.65%   |
| 51-100         | 43        | 7.15%   |
| 501-1000       | 42        | 6.99%   |
| 21-50          | 29        | 4.83%   |
| 1-20           | 23        | 3.83%   |
| 2001-3000      | 11        | 1.83%   |
| More than 3000 | 10        | 1.66%   |
| Unknown        | 3         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 325       | 53.54%  |
| 21-50          | 128       | 21.09%  |
| 51-100         | 50        | 8.24%   |
| 101-250        | 42        | 6.92%   |
| 251-500        | 21        | 3.46%   |
| 501-1000       | 21        | 3.46%   |
| 1001-2000      | 10        | 1.65%   |
| More than 3000 | 4         | 0.66%   |
| 2001-3000      | 3         | 0.49%   |
| Unknown        | 3         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                  | Computers | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 3         | 3      | 5.26%   |
| Seagate ST380815AS 80GB                                | 2         | 2      | 3.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 3.51%   |
| XrayDisk 512GB SSD                                     | 1         | 1      | 1.75%   |
| XrayDisk 240GB SSD                                     | 1         | 1      | 1.75%   |
| WDC WD7501AALS-00E3A0 752GB                            | 1         | 1      | 1.75%   |
| WDC WD7500AAKS-00RBA0 752GB                            | 1         | 2      | 1.75%   |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 1.75%   |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 1.75%   |
| WDC WD3200AAKS-00V1A0 320GB                            | 1         | 1      | 1.75%   |
| WDC WD2500KS-00MJB0 250GB                              | 1         | 1      | 1.75%   |
| WDC WD2500BEVT-60ZCT1 250GB                            | 1         | 3      | 1.75%   |
| WDC WD20EARX-008FB0 2TB                                | 1         | 1      | 1.75%   |
| WDC WD2005FBYZ-01YCBB3 2TB                             | 1         | 1      | 1.75%   |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 1.75%   |
| WDC WD1003FBYX-01Y7B0 1TB                              | 1         | 1      | 1.75%   |
| Toshiba MQ01ABD050 500GB                               | 1         | 1      | 1.75%   |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 1.75%   |
| Toshiba DT01ACA050 500GB                               | 1         | 1      | 1.75%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 1.75%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 1.75%   |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 1.75%   |
| Seagate STM3500418AS 500GB                             | 1         | 1      | 1.75%   |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 1.75%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB           | 1         | 1      | 1.75%   |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 1.75%   |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 1.75%   |
| Seagate ST380811AS 80GB                                | 1         | 1      | 1.75%   |
| Seagate ST3320418AS 320GB                              | 1         | 1      | 1.75%   |
| Seagate ST32000641AS 2TB                               | 1         | 2      | 1.75%   |
| Seagate ST3000DM001-1CH166 3TB                         | 1         | 1      | 1.75%   |
| Seagate ST250DM000-1BD141 250GB                        | 1         | 2      | 1.75%   |
| Seagate ST1000DL004 HD105SI 1TB                        | 1         | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 500GB                  | 1         | 1      | 1.75%   |
| Samsung Electronics HD250HJ 250GB                      | 1         | 1      | 1.75%   |
| Netac SSD 480GB                                        | 1         | 1      | 1.75%   |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 1.75%   |
| Intel SSDSC2BW480A4 480GB                              | 1         | 1      | 1.75%   |
| Hitachi HUA722010CLA330 1TB                            | 1         | 1      | 1.75%   |
| Hitachi HTS725050A9A364 500GB                          | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 18        | 25     | 31.58%  |
| WDC                          | 11        | 14     | 19.3%   |
| Hitachi                      | 8         | 9      | 14.04%  |
| Toshiba                      | 3         | 3      | 5.26%   |
| XrayDisk                     | 2         | 2      | 3.51%   |
| SK hynix                     | 2         | 2      | 3.51%   |
| Samsung Electronics          | 2         | 2      | 3.51%   |
| Intel                        | 2         | 2      | 3.51%   |
| HGST                         | 2         | 2      | 3.51%   |
| AMD                          | 2         | 2      | 3.51%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.75%   |
| Netac                        | 1         | 1      | 1.75%   |
| Fujitsu                      | 1         | 1      | 1.75%   |
| DEPO                         | 1         | 1      | 1.75%   |
| Corsair                      | 1         | 3      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 25     | 40.91%  |
| WDC                 | 11        | 14     | 25%     |
| Hitachi             | 8         | 9      | 18.18%  |
| Toshiba             | 3         | 3      | 6.82%   |
| HGST                | 2         | 2      | 4.55%   |
| Samsung Electronics | 1         | 1      | 2.27%   |
| Fujitsu             | 1         | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 55     | 75.93%  |
| SSD  | 11        | 13     | 20.37%  |
| NVMe | 2         | 2      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB     | 1         | 1      | 50%     |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 445       | 639    | 73.19%  |
| Detected | 108       | 205    | 17.76%  |
| Malfunc  | 53        | 70     | 8.72%   |
| Failed   | 2         | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 446       | 56.38%  |
| AMD                              | 75        | 9.48%   |
| Samsung Electronics              | 50        | 6.32%   |
| Phison Electronics               | 41        | 5.18%   |
| INNOGRIT                         | 33        | 4.17%   |
| SK hynix                         | 27        | 3.41%   |
| Kingston Technology Company      | 17        | 2.15%   |
| Nvidia                           | 14        | 1.77%   |
| SanDisk                          | 11        | 1.39%   |
| JMicron Technology               | 10        | 1.26%   |
| Realtek Semiconductor            | 8         | 1.01%   |
| Broadcom / LSI                   | 7         | 0.88%   |
| ASMedia Technology               | 7         | 0.88%   |
| Silicon Motion                   | 6         | 0.76%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.63%   |
| Shenzhen Longsys Electronics     | 4         | 0.51%   |
| Marvell Technology Group         | 4         | 0.51%   |
| ADATA Technology                 | 4         | 0.51%   |
| Toshiba America Info Systems     | 3         | 0.38%   |
| MCST                             | 3         | 0.38%   |
| VIA Technologies                 | 2         | 0.25%   |
| Solid State Storage Technology   | 2         | 0.25%   |
| Micron/Crucial Technology        | 2         | 0.25%   |
| Micron Technology                | 2         | 0.25%   |
| LSI Logic / Symbios Logic        | 2         | 0.25%   |
| Zhaoxin                          | 1         | 0.13%   |
| Yangtze Memory Technologies      | 1         | 0.13%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.13%   |
| KIOXIA                           | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |
| Adaptec                          | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 74        | 8.19%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 58        | 6.42%   |
| Intel Tiger Lake-LP SATA Controller                                            | 50        | 5.54%   |
| Phison PS5013 E13 NVMe Controller                                              | 37        | 4.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 33        | 3.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 33        | 3.65%   |
| INNOGRIT NVMe SSD Controller IG5216 (DRAM-less)                                | 33        | 3.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 20        | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 2.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 1.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 18        | 1.99%   |
| AMD 400 Series Chipset SATA Controller                                         | 18        | 1.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 1.77%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 15        | 1.66%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 1.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 1.22%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.11%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 9         | 1%      |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 9         | 1%      |
| Intel SSD 600P Series                                                          | 9         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 0.89%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 8         | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 0.89%   |
| JMicron JMB363 SATA/IDE Controller                                             | 7         | 0.78%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 7         | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 0.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 0.78%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 6         | 0.66%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.55%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 5         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 462       | 57.11%  |
| NVMe | 236       | 29.17%  |
| IDE  | 71        | 8.78%   |
| RAID | 40        | 4.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 469       | 81%     |
| AMD          | 101       | 17.44%  |
| ARM          | 4         | 0.69%   |
| CentaurHauls | 2         | 0.35%   |
| Elbrus-MCST  | 1         | 0.17%   |
| E8C/EATX     | 1         | 0.17%   |
| E8C-SWTX     | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 9.12%   |
| Intel Core i3-6100TE CPU @ 2.70GHz            | 46        | 7.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 24        | 4.13%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 19        | 3.27%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 14        | 2.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 2.24%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 2.07%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 10        | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 9         | 1.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.38%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 7         | 1.2%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 1.03%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 6         | 1.03%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz          | 5         | 0.86%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 5         | 0.86%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 4         | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.69%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.69%   |
| ARM Processor                                 | 4         | 0.69%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 4         | 0.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.69%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.52%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.52%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 3         | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.52%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 3         | 0.52%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 0.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.52%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 2         | 0.34%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 2         | 0.34%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.34%   |
| Intel Genuine CPU 0000 @ 2.40GHz              | 2         | 0.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 124       | 21.38%  |
| Intel Core i3           | 111       | 19.14%  |
| Other                   | 84        | 14.48%  |
| AMD Ryzen 5             | 34        | 5.86%   |
| Intel Core i7           | 32        | 5.52%   |
| Intel Celeron           | 24        | 4.14%   |
| Intel Pentium           | 21        | 3.62%   |
| AMD Ryzen 7             | 20        | 3.45%   |
| Intel Core 2 Duo        | 19        | 3.28%   |
| Intel Xeon              | 9         | 1.55%   |
| Intel Atom              | 8         | 1.38%   |
| Intel Pentium Dual-Core | 7         | 1.21%   |
| AMD A8                  | 7         | 1.21%   |
| Intel Xeon Silver       | 6         | 1.03%   |
| Intel Pentium Gold      | 6         | 1.03%   |
| Intel Core 2 Quad       | 6         | 1.03%   |
| AMD A10                 | 6         | 1.03%   |
| AMD Athlon 64 X2        | 5         | 0.86%   |
| Intel Genuine           | 4         | 0.69%   |
| Intel Pentium Silver    | 3         | 0.52%   |
| Intel Core i9           | 3         | 0.52%   |
| AMD Ryzen 3             | 3         | 0.52%   |
| AMD FX                  | 3         | 0.52%   |
| AMD Athlon              | 3         | 0.52%   |
| AMD A6                  | 3         | 0.52%   |
| AMD Phenom II X4        | 2         | 0.34%   |
| AMD E1                  | 2         | 0.34%   |
| Intel Xeon Gold         | 1         | 0.17%   |
| Intel Pentium Dual      | 1         | 0.17%   |
| Intel Pentium D         | 1         | 0.17%   |
| Intel Pentium 4         | 1         | 0.17%   |
| Intel Core m5           | 1         | 0.17%   |
| Intel Core Duo          | 1         | 0.17%   |
| Intel Core 2 Solo       | 1         | 0.17%   |
| Intel Core 2            | 1         | 0.17%   |
| Intel Celeron M         | 1         | 0.17%   |
| Intel Celeron Dual-Core | 1         | 0.17%   |
| Intel Celeron D         | 1         | 0.17%   |
| CentaurHauls VIA C7     | 1         | 0.17%   |
| AMD Turion 64 X2 Mobile | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 227       | 39.14%  |
| 4      | 205       | 35.34%  |
| 6      | 82        | 14.14%  |
| 8      | 30        | 5.17%   |
| 1      | 14        | 2.41%   |
| 20     | 5         | 0.86%   |
| 12     | 5         | 0.86%   |
| 16     | 3         | 0.52%   |
| 10     | 3         | 0.52%   |
| 32     | 2         | 0.34%   |
| 3      | 2         | 0.34%   |
| 18     | 1         | 0.17%   |
| 14     | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 568       | 98.1%   |
| 2      | 9         | 1.55%   |
| 4      | 2         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 414       | 71.5%   |
| 1      | 165       | 28.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 566       | 97.75%  |
| 32-bit         | 7         | 1.21%   |
| Unknown        | 6         | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 119       | 20.31%  |
| 0x806c1    | 57        | 9.73%   |
| 0x506e3    | 54        | 9.22%   |
| 0x906ea    | 34        | 5.8%    |
| 0x1067a    | 22        | 3.75%   |
| 0x806e9    | 21        | 3.58%   |
| 0x806ec    | 19        | 3.24%   |
| 0xa0653    | 17        | 2.9%    |
| 0x806ea    | 15        | 2.56%   |
| 0x08001138 | 14        | 2.39%   |
| 0x906e9    | 13        | 2.22%   |
| 0x806eb    | 10        | 1.71%   |
| 0x306a9    | 10        | 1.71%   |
| 0x206a7    | 10        | 1.71%   |
| 0x0a50000c | 9         | 1.54%   |
| 0x08108109 | 9         | 1.54%   |
| 0xa0660    | 8         | 1.37%   |
| 0x906eb    | 8         | 1.37%   |
| 0x50657    | 8         | 1.37%   |
| 0xa0671    | 6         | 1.02%   |
| 0x906ed    | 5         | 0.85%   |
| 0x706e5    | 5         | 0.85%   |
| 0x506c9    | 5         | 0.85%   |
| 0x306c3    | 5         | 0.85%   |
| 0x08600106 | 5         | 0.85%   |
| 0x06001119 | 5         | 0.85%   |
| 0x6fd      | 4         | 0.68%   |
| 0x406e3    | 4         | 0.68%   |
| 0x20655    | 4         | 0.68%   |
| 0x706a8    | 3         | 0.51%   |
| 0x40651    | 3         | 0.51%   |
| 0x106ca    | 3         | 0.51%   |
| 0x906c0    | 2         | 0.34%   |
| 0x906a3    | 2         | 0.34%   |
| 0x90675    | 2         | 0.34%   |
| 0x806c2    | 2         | 0.34%   |
| 0x6e8      | 2         | 0.34%   |
| 0x406c4    | 2         | 0.34%   |
| 0x406c3    | 2         | 0.34%   |
| 0x306e4    | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 142       | 24.48%  |
| Skylake          | 74        | 12.76%  |
| TigerLake        | 63        | 10.86%  |
| CometLake        | 32        | 5.52%   |
| Penryn           | 27        | 4.66%   |
| Unknown          | 25        | 4.31%   |
| IvyBridge        | 20        | 3.45%   |
| Zen 3            | 19        | 3.28%   |
| SandyBridge      | 19        | 3.28%   |
| Zen              | 16        | 2.76%   |
| Haswell          | 14        | 2.41%   |
| Zen+             | 13        | 2.24%   |
| Westmere         | 11        | 1.9%    |
| Silvermont       | 11        | 1.9%    |
| Core             | 10        | 1.72%   |
| Zen 2            | 9         | 1.55%   |
| Piledriver       | 8         | 1.38%   |
| K8 Hammer        | 8         | 1.38%   |
| IceLake          | 7         | 1.21%   |
| Bonnell          | 6         | 1.03%   |
| Steamroller      | 5         | 0.86%   |
| K10              | 5         | 0.86%   |
| Goldmont plus    | 5         | 0.86%   |
| Goldmont         | 5         | 0.86%   |
| Alderlake Hybrid | 4         | 0.69%   |
| P6               | 3         | 0.52%   |
| NetBurst         | 3         | 0.52%   |
| K10 Llano        | 3         | 0.52%   |
| Excavator        | 3         | 0.52%   |
| Tremont          | 2         | 0.34%   |
| Nehalem          | 2         | 0.34%   |
| Jaguar           | 2         | 0.34%   |
| Bobcat           | 2         | 0.34%   |
| Puma             | 1         | 0.17%   |
| Broadwell        | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 392       | 62.92%  |
| Nvidia                     | 115       | 18.46%  |
| AMD                        | 100       | 16.05%  |
| Matrox Electronics Systems | 5         | 0.8%    |
| ASPEED Technology          | 5         | 0.8%    |
| Silicon Motion             | 2         | 0.32%   |
| Huawei Technologies        | 2         | 0.32%   |
| Zhaoxin                    | 1         | 0.16%   |
| VIA Technologies           | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 57        | 8.89%   |
| Intel HD Graphics 530                                                                    | 54        | 8.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 32        | 4.99%   |
| Intel HD Graphics 620                                                                    | 29        | 4.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 4.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 2.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 2.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.72%   |
| Intel HD Graphics 610                                                                    | 10        | 1.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.56%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 9         | 1.4%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 9         | 1.4%    |
| Intel Comet Lake UHD Graphics                                                            | 8         | 1.25%   |
| AMD Renoir                                                                               | 7         | 1.09%   |
| Intel UHD Graphics 620                                                                   | 6         | 0.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 0.94%   |
| Intel HD Graphics 510                                                                    | 6         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.94%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 0.78%   |
| Intel HD Graphics 630                                                                    | 5         | 0.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.78%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 5         | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.62%   |
| Intel HD Graphics 500                                                                    | 4         | 0.62%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 4         | 0.62%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.62%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.62%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.47%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 3         | 0.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.47%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 0.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 349       | 60.07%  |
| 1 x Nvidia              | 78        | 13.43%  |
| 1 x AMD                 | 78        | 13.43%  |
| Intel + Nvidia          | 32        | 5.51%   |
| 2 x AMD                 | 11        | 1.89%   |
| Other                   | 6         | 1.03%   |
| Intel + AMD             | 6         | 1.03%   |
| 1 x Matrox              | 5         | 0.86%   |
| 1 x ASPEED              | 5         | 0.86%   |
| AMD + Nvidia            | 4         | 0.69%   |
| 1 x Silicon Motion      | 2         | 0.34%   |
| 1 x Huawei Technologies | 2         | 0.34%   |
| 2 x Intel               | 1         | 0.17%   |
| 1 x VIA                 | 1         | 0.17%   |
| Nvidia + Zhaoxin        | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 496       | 85.08%  |
| Proprietary | 64        | 10.98%  |
| Unknown     | 23        | 3.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 439       | 74.79%  |
| 0.01-0.5   | 44        | 7.5%    |
| 3.01-4.0   | 36        | 6.13%   |
| 1.01-2.0   | 29        | 4.94%   |
| 0.51-1.0   | 28        | 4.77%   |
| 7.01-8.0   | 4         | 0.68%   |
| 8.01-16.0  | 4         | 0.68%   |
| 5.01-6.0   | 2         | 0.34%   |
| 2.01-3.0   | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 59        | 9.82%   |
| Chimei Innolux          | 57        | 9.48%   |
| Samsung Electronics     | 51        | 8.49%   |
| HHT                     | 48        | 7.99%   |
| AU Optronics            | 39        | 6.49%   |
| Acer                    | 34        | 5.66%   |
| AOC                     | 32        | 5.32%   |
| LG Display              | 29        | 4.83%   |
| BenQ                    | 28        | 4.66%   |
| ECS                     | 22        | 3.66%   |
| Goldstar                | 20        | 3.33%   |
| Philips                 | 17        | 2.83%   |
| PANDA                   | 13        | 2.16%   |
| Lenovo                  | 13        | 2.16%   |
| Dell                    | 13        | 2.16%   |
| ViewSonic               | 10        | 1.66%   |
| Sharp                   | 8         | 1.33%   |
| CHR                     | 7         | 1.16%   |
| Hewlett-Packard         | 6         | 1%      |
| Chi Mei Optoelectronics | 6         | 1%      |
| Apple                   | 6         | 1%      |
| Ancor Communications    | 6         | 1%      |
| PRM                     | 5         | 0.83%   |
| PRW                     | 4         | 0.67%   |
| Iiyama                  | 4         | 0.67%   |
| ASUSTek Computer        | 4         | 0.67%   |
| WBT                     | 3         | 0.5%    |
| VIE                     | 3         | 0.5%    |
| STA                     | 3         | 0.5%    |
| RTK                     | 3         | 0.5%    |
| LG Electronics          | 3         | 0.5%    |
| HannStar                | 3         | 0.5%    |
| Toshiba                 | 2         | 0.33%   |
| STD                     | 2         | 0.33%   |
| NEC Computers           | 2         | 0.33%   |
| MSI                     | 2         | 0.33%   |
| JRY                     | 2         | 0.33%   |
| AGO                     | 2         | 0.33%   |
| Unknown                 | 2         | 0.33%   |
| ZCS                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 48        | 7.86%   |
| ECS AIO PC ECS2486 1920x1080 477x268mm 21.5-inch                     | 22        | 3.6%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 12        | 1.96%   |
| AOC LCD Monitor 2778X 2560x1440                                      | 11        | 1.8%    |
| Lenovo LEN-V3V5-B-A LENE288 1920x1080 527x296mm 23.8-inch            | 10        | 1.64%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                    | 10        | 1.64%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 9         | 1.47%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 1.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 9         | 1.47%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 8         | 1.31%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 8         | 1.31%   |
| CHR CH7511B CHR7511 1024x768 430x290mm 20.4-inch                     | 6         | 0.98%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 0.98%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 5         | 0.82%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                | 5         | 0.82%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5         | 0.82%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 0.82%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch        | 4         | 0.65%   |
| PRW AP7_Titanium PRW4200 3840x2160                                   | 4         | 0.65%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 4         | 0.65%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                    | 4         | 0.65%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                     | 3         | 0.49%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 3         | 0.49%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 0.49%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch              | 3         | 0.49%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 3         | 0.49%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 3         | 0.49%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch               | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 0.49%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 3         | 0.49%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.49%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                  | 3         | 0.49%   |
| AOC 2475W AOC2475 1920x1080 521x293mm 23.5-inch                      | 3         | 0.49%   |
| Acer AIO LCD ACRF132 1920x1080 509x286mm 23.0-inch                   | 3         | 0.49%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch        | 2         | 0.33%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch          | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 324       | 56.35%  |
| 3840x2160 (4K)     | 63        | 10.96%  |
| 1366x768 (WXGA)    | 48        | 8.35%   |
| 2560x1440 (QHD)    | 30        | 5.22%   |
| 1280x1024 (SXGA)   | 30        | 5.22%   |
| 1600x900 (HD+)     | 17        | 2.96%   |
| 1280x800 (WXGA)    | 13        | 2.26%   |
| 1680x1050 (WSXGA+) | 10        | 1.74%   |
| 1440x900 (WXGA+)   | 6         | 1.04%   |
| Unknown            | 5         | 0.87%   |
| 2560x1600          | 4         | 0.7%    |
| 1920x1200 (WUXGA)  | 4         | 0.7%    |
| 1024x600           | 3         | 0.52%   |
| 3840x1080          | 2         | 0.35%   |
| 2160x1440          | 2         | 0.35%   |
| 1600x1200          | 2         | 0.35%   |
| 1360x768           | 2         | 0.35%   |
| 800x1280           | 1         | 0.17%   |
| 4480x1440          | 1         | 0.17%   |
| 3840x1600          | 1         | 0.17%   |
| 3840x1440          | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 2880x1620          | 1         | 0.17%   |
| 2160x1200          | 1         | 0.17%   |
| 1400x1050          | 1         | 0.17%   |
| 1280x720 (HD)      | 1         | 0.17%   |
| 1024x768 (XGA)     | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 112       | 18.82%  |
| 23      | 72        | 12.1%   |
| 24      | 55        | 9.24%   |
| 40      | 50        | 8.4%    |
| 13      | 49        | 8.24%   |
| 14      | 44        | 7.39%   |
| 21      | 39        | 6.55%   |
| 17      | 38        | 6.39%   |
| Unknown | 38        | 6.39%   |
| 27      | 26        | 4.37%   |
| 19      | 17        | 2.86%   |
| 12      | 10        | 1.68%   |
| 26      | 6         | 1.01%   |
| 20      | 6         | 1.01%   |
| 31      | 5         | 0.84%   |
| 11      | 5         | 0.84%   |
| 22      | 3         | 0.5%    |
| 18      | 3         | 0.5%    |
| 10      | 3         | 0.5%    |
| 16      | 2         | 0.34%   |
| 85      | 1         | 0.17%   |
| 72      | 1         | 0.17%   |
| 59      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 50      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 33      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 8       | 1         | 0.17%   |
| 7       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 208       | 35.37%  |
| 501-600     | 149       | 25.34%  |
| 401-500     | 58        | 9.86%   |
| 901-1000    | 48        | 8.16%   |
| Unknown     | 38        | 6.46%   |
| 351-400     | 32        | 5.44%   |
| 201-300     | 31        | 5.27%   |
| 601-700     | 11        | 1.87%   |
| 1001-1500   | 4         | 0.68%   |
| 801-900     | 3         | 0.51%   |
| 701-800     | 2         | 0.34%   |
| 1501-2000   | 2         | 0.34%   |
| 101-200     | 1         | 0.17%   |
| 1-100       | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 402       | 71.15%  |
| 21/9    | 49        | 8.67%   |
| 16/10   | 46        | 8.14%   |
| 5/4     | 28        | 4.96%   |
| Unknown | 25        | 4.42%   |
| 4/3     | 8         | 1.42%   |
| 3/2     | 5         | 0.88%   |
| 6/5     | 1         | 0.18%   |
| 0.67    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 140       | 23.73%  |
| 101-110        | 113       | 19.15%  |
| 81-90          | 86        | 14.58%  |
| 501-1000       | 52        | 8.81%   |
| Unknown        | 38        | 6.44%   |
| 151-200        | 34        | 5.76%   |
| 301-350        | 32        | 5.42%   |
| 121-130        | 21        | 3.56%   |
| 141-150        | 18        | 3.05%   |
| 251-300        | 14        | 2.37%   |
| 71-80          | 10        | 1.69%   |
| 351-500        | 8         | 1.36%   |
| 61-70          | 7         | 1.19%   |
| More than 1000 | 5         | 0.85%   |
| 51-60          | 5         | 0.85%   |
| 41-50          | 3         | 0.51%   |
| 1-40           | 2         | 0.34%   |
| 131-140        | 1         | 0.17%   |
| 111-120        | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 193       | 32.88%  |
| 121-160       | 189       | 32.2%   |
| 101-120       | 142       | 24.19%  |
| Unknown       | 38        | 6.47%   |
| 161-240       | 16        | 2.73%   |
| 1-50          | 7         | 1.19%   |
| More than 240 | 2         | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 507       | 86.67%  |
| 2     | 55        | 9.4%    |
| 0     | 21        | 3.59%   |
| 3     | 2         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 351       | 42.49%  |
| Intel                           | 301       | 36.44%  |
| Qualcomm Atheros                | 56        | 6.78%   |
| Broadcom                        | 25        | 3.03%   |
| Nvidia                          | 13        | 1.57%   |
| Marvell Technology Group        | 9         | 1.09%   |
| D-Link                          | 8         | 0.97%   |
| MediaTek                        | 6         | 0.73%   |
| IBM                             | 5         | 0.61%   |
| Broadcom Limited                | 5         | 0.61%   |
| TP-Link                         | 4         | 0.48%   |
| Ralink Technology               | 4         | 0.48%   |
| Ralink                          | 4         | 0.48%   |
| ASIX Electronics                | 4         | 0.48%   |
| Xiaomi                          | 3         | 0.36%   |
| Microchip Technology            | 3         | 0.36%   |
| MCST                            | 3         | 0.36%   |
| JMicron Technology              | 3         | 0.36%   |
| ASUSTek Computer                | 3         | 0.36%   |
| VIA Technologies                | 2         | 0.24%   |
| Sierra Wireless                 | 2         | 0.24%   |
| Huawei Technologies             | 2         | 0.24%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.12%   |
| Vimtron Electronics             | 1         | 0.12%   |
| U-Blox                          | 1         | 0.12%   |
| Qualcomm Atheros Communications | 1         | 0.12%   |
| Qualcomm                        | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Exar                            | 1         | 0.12%   |
| DisplayLink                     | 1         | 0.12%   |
| Attansic Technology             | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 246       | 24.53%  |
| Intel Wi-Fi 6 AX201                                               | 55        | 5.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 48        | 4.79%   |
| Intel Ethernet Connection (13) I219-V                             | 45        | 4.49%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 3.69%   |
| Intel Wireless 3165                                               | 20        | 1.99%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 17        | 1.69%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 1.5%    |
| Intel Wireless 7265                                               | 14        | 1.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 11        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.7%    |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.7%    |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 5         | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 5         | 0.5%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 0.5%    |
| Intel Ethernet Connection (17) I219-V                             | 5         | 0.5%    |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 0.5%    |
| IBM RNDIS/CDC ETHER                                               | 5         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 213       | 59.17%  |
| Realtek Semiconductor           | 62        | 17.22%  |
| Qualcomm Atheros                | 38        | 10.56%  |
| Broadcom                        | 18        | 5%      |
| MediaTek                        | 6         | 1.67%   |
| TP-Link                         | 4         | 1.11%   |
| Ralink Technology               | 4         | 1.11%   |
| Ralink                          | 4         | 1.11%   |
| Broadcom Limited                | 3         | 0.83%   |
| ASUSTek Computer                | 3         | 0.83%   |
| Sierra Wireless                 | 2         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| Micro Star International        | 1         | 0.28%   |
| D-Link                          | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 55        | 15.15%  |
| Intel Wireless 3165                                                     | 20        | 5.51%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 5.23%   |
| Intel Wireless 8265 / 8275                                              | 17        | 4.68%   |
| Intel Wireless 7265                                                     | 14        | 3.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 3.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 3.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.83%   |
| Intel WiFi Link 5100                                                    | 3         | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.83%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 2         | 0.55%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 328       | 53.86%  |
| Intel                      | 186       | 30.54%  |
| Qualcomm Atheros           | 27        | 4.43%   |
| Nvidia                     | 13        | 2.13%   |
| Marvell Technology Group   | 9         | 1.48%   |
| Broadcom                   | 9         | 1.48%   |
| D-Link                     | 7         | 1.15%   |
| IBM                        | 5         | 0.82%   |
| ASIX Electronics           | 4         | 0.66%   |
| Xiaomi                     | 3         | 0.49%   |
| MCST                       | 3         | 0.49%   |
| JMicron Technology         | 3         | 0.49%   |
| VIA Technologies           | 2         | 0.33%   |
| Huawei Technologies        | 2         | 0.33%   |
| Broadcom Limited           | 2         | 0.33%   |
| ZTE WCDMA Technologies MSM | 1         | 0.16%   |
| Vimtron Electronics        | 1         | 0.16%   |
| TP-Link                    | 1         | 0.16%   |
| Qualcomm                   | 1         | 0.16%   |
| DisplayLink                | 1         | 0.16%   |
| Attansic Technology        | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 246       | 38.86%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 48        | 7.58%   |
| Intel Ethernet Connection (13) I219-V                             | 45        | 7.11%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 5.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 2.84%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 2.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.26%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.11%   |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 1.11%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.79%   |
| Intel I210 Gigabit Network Connection                             | 5         | 0.79%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 0.79%   |
| Intel Ethernet Connection (17) I219-V                             | 5         | 0.79%   |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 0.79%   |
| IBM RNDIS/CDC ETHER                                               | 5         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.63%   |
| Intel I350 Gigabit Network Connection                             | 4         | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.63%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.47%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.47%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.47%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 3         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.32%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.32%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 536       | 59.89%  |
| WiFi     | 352       | 39.33%  |
| Modem    | 6         | 0.67%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 321       | 54.5%   |
| WiFi     | 268       | 45.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 293       | 50.6%   |
| 1     | 259       | 44.73%  |
| 0     | 12        | 2.07%   |
| 6     | 5         | 0.86%   |
| 3     | 4         | 0.69%   |
| 4     | 3         | 0.52%   |
| 13    | 1         | 0.17%   |
| 12    | 1         | 0.17%   |
| 8     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 560       | 96.55%  |
| Yes  | 20        | 3.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 197       | 63.75%  |
| Realtek Semiconductor           | 21        | 6.8%    |
| IMC Networks                    | 18        | 5.83%   |
| Cambridge Silicon Radio         | 14        | 4.53%   |
| Broadcom                        | 14        | 4.53%   |
| Qualcomm Atheros Communications | 8         | 2.59%   |
| Foxconn / Hon Hai               | 7         | 2.27%   |
| Lite-On Technology              | 6         | 1.94%   |
| Hewlett-Packard                 | 5         | 1.62%   |
| Realtek                         | 4         | 1.29%   |
| ASUSTek Computer                | 4         | 1.29%   |
| Apple                           | 4         | 1.29%   |
| USI                             | 1         | 0.32%   |
| Toshiba                         | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Opticis                         | 1         | 0.32%   |
| Logitech                        | 1         | 0.32%   |
| HTC (High Tech Computer)        | 1         | 0.32%   |
| Chicony Electronics             | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 19.74%  |
| Intel AX201 Bluetooth                               | 59        | 19.09%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 38        | 12.3%   |
| Intel AX200 Bluetooth                               | 19        | 6.15%   |
| Realtek Bluetooth Radio                             | 14        | 4.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 4.53%   |
| Intel Bluetooth Device                              | 13        | 4.21%   |
| IMC Networks Wireless_Device                        | 6         | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.62%   |
| IMC Networks Bluetooth Device                       | 5         | 1.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.29%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.29%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 1.29%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.97%   |
| Intel AX210 Bluetooth                               | 3         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.97%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.97%   |
| Apple Bluetooth Host Controller                     | 3         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.65%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.65%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.32%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.32%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.32%   |
| Realtek RTL8723A Bluetooth                          | 1         | 0.32%   |
| Realtek Bluetooth Radio                             | 1         | 0.32%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.32%   |
| Opticis Bluetooth Radio                             | 1         | 0.32%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.32%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.32%   |
| Lite-On Bluetooth Radio                             | 1         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 449       | 61.51%  |
| AMD                                          | 112       | 15.34%  |
| Nvidia                                       | 92        | 12.6%   |
| C-Media Electronics                          | 43        | 5.89%   |
| Promethean Limited                           | 7         | 0.96%   |
| MCST                                         | 3         | 0.41%   |
| JMTek                                        | 3         | 0.41%   |
| Creative Technology                          | 3         | 0.41%   |
| VIA Technologies                             | 2         | 0.27%   |
| Realtek Semiconductor                        | 2         | 0.27%   |
| Logitech                                     | 2         | 0.27%   |
| Apple                                        | 2         | 0.27%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.14%   |
| Zhaoxin                                      | 1         | 0.14%   |
| Texas Instruments                            | 1         | 0.14%   |
| Goldvish                                     | 1         | 0.14%   |
| Generalplus Technology                       | 1         | 0.14%   |
| FIFINE Microphones                           | 1         | 0.14%   |
| EasyPass Industrial                          | 1         | 0.14%   |
| Creative Labs                                | 1         | 0.14%   |
| ASUSTek Computer                             | 1         | 0.14%   |
| A4Tech                                       | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 74        | 9.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 63        | 7.83%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 36        | 4.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 4.35%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 4.1%    |
| C-Media Electronics USB Advanced Audio Device                              | 33        | 4.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 23        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 18        | 2.24%   |
| AMD FCH Azalia Controller                                                  | 17        | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 1.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 1.74%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 13        | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 0.99%   |
| Promethean Limited Audio                                                   | 7         | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                | 7         | 0.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 0.87%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 7         | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.62%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 0.62%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 85        | 17.75%  |
| Crucial             | 72        | 15.03%  |
| SK hynix            | 54        | 11.27%  |
| Unknown             | 48        | 10.02%  |
| Kingston            | 46        | 9.6%    |
| Micron Technology   | 33        | 6.89%   |
| ACPI Digital        | 32        | 6.68%   |
| A-DATA Technology   | 17        | 3.55%   |
| Ramaxel Technology  | 15        | 3.13%   |
| Foxline             | 11        | 2.3%    |
| Apacer              | 10        | 2.09%   |
| Elpida              | 6         | 1.25%   |
| AMD                 | 6         | 1.25%   |
| Unknown             | 6         | 1.25%   |
| Patriot             | 5         | 1.04%   |
| Corsair             | 5         | 1.04%   |
| Unknown (ABCD)      | 4         | 0.84%   |
| GOODRAM             | 4         | 0.84%   |
| ChangXin Memory     | 3         | 0.63%   |
| Shenzhen Longsys    | 2         | 0.42%   |
| Goldkey             | 2         | 0.42%   |
| G.Skill             | 2         | 0.42%   |
| Wilk                | 1         | 0.21%   |
| Unknown (0x0B7A)    | 1         | 0.21%   |
| Unknown (081A)      | 1         | 0.21%   |
| tigo                | 1         | 0.21%   |
| SHARETRONIC         | 1         | 0.21%   |
| Qumo                | 1         | 0.21%   |
| Lexar Co Limited    | 1         | 0.21%   |
| Kimtigo             | 1         | 0.21%   |
| Juhor               | 1         | 0.21%   |
| Golden Empire       | 1         | 0.21%   |
| ATLA                | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 32        | 6.44%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 17        | 3.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 2.62%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13        | 2.62%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 10        | 2.01%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10        | 2.01%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 1.81%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 7         | 1.41%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s           | 7         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.21%   |
| Unknown                                                          | 6         | 1.21%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.01%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 5         | 1.01%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.8%    |
| Samsung RAM M393A2K43CB2-CVF 16384MB DIMM DDR4 2933MT/s          | 4         | 0.8%    |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4         | 0.8%    |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3         | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.6%    |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.6%    |
| Crucial RAM CT8G4SFRA266.C16FG 8GB SODIMM DDR4 2667MT/s          | 3         | 0.6%    |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3         | 0.6%    |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 3         | 0.6%    |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 3         | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 2         | 0.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 310       | 69.04%  |
| DDR3    | 68        | 15.14%  |
| DDR2    | 25        | 5.57%   |
| Unknown | 16        | 3.56%   |
| LPDDR4  | 15        | 3.34%   |
| SDRAM   | 6         | 1.34%   |
| DDR     | 3         | 0.67%   |
| LPDDR5  | 2         | 0.45%   |
| DDR5    | 2         | 0.45%   |
| LPDDR3  | 1         | 0.22%   |
| DRAM    | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 271       | 60.36%  |
| DIMM         | 156       | 34.74%  |
| Row Of Chips | 22        | 4.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 198       | 42.86%  |
| 4096  | 123       | 26.62%  |
| 16384 | 73        | 15.8%   |
| 2048  | 38        | 8.23%   |
| 1024  | 19        | 4.11%   |
| 512   | 5         | 1.08%   |
| 32768 | 4         | 0.87%   |
| 65536 | 1         | 0.22%   |
| 1536  | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 113       | 23.99%  |
| 3200    | 102       | 21.66%  |
| 2400    | 55        | 11.68%  |
| 1600    | 40        | 8.49%   |
| 2133    | 27        | 5.73%   |
| 667     | 15        | 3.18%   |
| 1333    | 14        | 2.97%   |
| 2933    | 12        | 2.55%   |
| Unknown | 12        | 2.55%   |
| 1334    | 10        | 2.12%   |
| 800     | 9         | 1.91%   |
| 3266    | 8         | 1.7%    |
| 1067    | 4         | 0.85%   |
| 533     | 4         | 0.85%   |
| 4267    | 3         | 0.64%   |
| 3733    | 3         | 0.64%   |
| 3600    | 3         | 0.64%   |
| 3466    | 3         | 0.64%   |
| 1866    | 3         | 0.64%   |
| 400     | 3         | 0.64%   |
| 333     | 3         | 0.64%   |
| 6400    | 2         | 0.42%   |
| 4800    | 2         | 0.42%   |
| 3066    | 2         | 0.42%   |
| 2666    | 2         | 0.42%   |
| 1867    | 2         | 0.42%   |
| 4333    | 1         | 0.21%   |
| 4199    | 1         | 0.21%   |
| 3866    | 1         | 0.21%   |
| 3534    | 1         | 0.21%   |
| 3533    | 1         | 0.21%   |
| 3333    | 1         | 0.21%   |
| 3151    | 1         | 0.21%   |
| 3000    | 1         | 0.21%   |
| 2866    | 1         | 0.21%   |
| 2800    | 1         | 0.21%   |
| 2448    | 1         | 0.21%   |
| 1800    | 1         | 0.21%   |
| 1648    | 1         | 0.21%   |
| 1066    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Canon                  | 10        | 28.57%  |
| Samsung Electronics    | 9         | 25.71%  |
| Hewlett-Packard        | 6         | 17.14%  |
| Xerox                  | 2         | 5.71%   |
| Ricoh                  | 2         | 5.71%   |
| QinHeng Electronics    | 2         | 5.71%   |
| Brother Industries     | 2         | 5.71%   |
| Pantum                 | 1         | 2.86%   |
| Panasonic (Matsushita) | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SCX-3400 Series              | 4         | 11.43%  |
| QinHeng CH340S                       | 2         | 5.71%   |
| HP LaserJet P1102                    | 2         | 5.71%   |
| HP LaserJet 1010                     | 2         | 5.71%   |
| Canon MF4410                         | 2         | 5.71%   |
| Canon MF4010 series                  | 2         | 5.71%   |
| Brother HL-L2300D series             | 2         | 5.71%   |
| Xerox WorkCentre 5222                | 1         | 2.86%   |
| Xerox WorkCentre 3220                | 1         | 2.86%   |
| Samsung SCX-4200 series              | 1         | 2.86%   |
| Samsung SCX-3200 Series              | 1         | 2.86%   |
| Samsung ML-1640 Series Laser Printer | 1         | 2.86%   |
| Samsung M332x 382x 402x Series       | 1         | 2.86%   |
| Samsung CLX-3180 Series              | 1         | 2.86%   |
| Ricoh SP 210SU                       | 1         | 2.86%   |
| Ricoh Aficio SP C240DN               | 1         | 2.86%   |
| Pantum P2200 series                  | 1         | 2.86%   |
| Panasonic (Matsushita) KX-MB283RU    | 1         | 2.86%   |
| HP LaserJet M402dn                   | 1         | 2.86%   |
| HP LaserJet 3055                     | 1         | 2.86%   |
| Canon PIXMA MP190                    | 1         | 2.86%   |
| Canon MF3110                         | 1         | 2.86%   |
| Canon imageRUNNER1133 series         | 1         | 2.86%   |
| Canon I-SENSYS MF4550d               | 1         | 2.86%   |
| Canon G3010 series                   | 1         | 2.86%   |
| Canon G1010 series                   | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 66.67%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 65        | 19.64%  |
| Acer                                   | 39        | 11.78%  |
| Cheng Uei Precision Industry (Foxlink) | 32        | 9.67%   |
| IMC Networks                           | 29        | 8.76%   |
| Alcor Micro                            | 24        | 7.25%   |
| Logitech                               | 21        | 6.34%   |
| Realtek Semiconductor                  | 20        | 6.04%   |
| Sunplus Innovation Technology          | 18        | 5.44%   |
| Microdia                               | 12        | 3.63%   |
| Suyin                                  | 10        | 3.02%   |
| Quanta                                 | 10        | 3.02%   |
| Syntek                                 | 8         | 2.42%   |
| Bison Electronics                      | 7         | 2.11%   |
| Apple                                  | 6         | 1.81%   |
| lihappe8                               | 5         | 1.51%   |
| Z-Star Microelectronics                | 4         | 1.21%   |
| Unknown                                | 2         | 0.6%    |
| Sonix Technology                       | 2         | 0.6%    |
| Silicon Motion                         | 2         | 0.6%    |
| Luxvisions Innotech Limited            | 2         | 0.6%    |
| Lite-On Technology                     | 2         | 0.6%    |
| Y Media                                | 1         | 0.3%    |
| SunplusIT                              | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| Primax Electronics                     | 1         | 0.3%    |
| Microsoft                              | 1         | 0.3%    |
| Importek                               | 1         | 0.3%    |
| icSpring                               | 1         | 0.3%    |
| Hewlett-Packard                        | 1         | 0.3%    |
| GEMBIRD                                | 1         | 0.3%    |
| ALi                                    | 1         | 0.3%    |
| Unknown                                | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer BisonCam,NB Pro                                           | 33        | 9.85%   |
| Alcor Micro USB 2.0 PC Camera                                  | 21        | 6.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 4.48%   |
| Chicony Integrated Camera                                      | 14        | 4.18%   |
| Logitech Webcam C270                                           | 12        | 3.58%   |
| Chicony HP HD Camera                                           | 11        | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 11        | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 2.99%   |
| Realtek USB Camera                                             | 8         | 2.39%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 2.09%   |
| Chicony USB2.0 Camera                                          | 7         | 2.09%   |
| Realtek MTD camera                                             | 6         | 1.79%   |
| Chicony USB camera                                             | 6         | 1.79%   |
| Syntek Integrated Camera                                       | 5         | 1.49%   |
| Microdia Webcam Vitade AF                                      | 5         | 1.49%   |
| lihappe8 USB 2.0 Camera                                        | 5         | 1.49%   |
| IMC Networks HD Camera                                         | 5         | 1.49%   |
| Sunplus BKX Usb FHD Camera                                     | 4         | 1.19%   |
| IMC Networks Integrated Camera                                 | 4         | 1.19%   |
| Quanta ov9734_techfront_camera                                 | 3         | 0.9%    |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.9%    |
| IMC Networks UVC VGA Webcam                                    | 3         | 0.9%    |
| Chicony USB2.0 FHD Camera                                      | 3         | 0.9%    |
| Chicony HD WebCam                                              | 3         | 0.9%    |
| Apple Built-in iSight                                          | 3         | 0.9%    |
| Z-Star Vega USB 2.0 Camera                                     | 2         | 0.6%    |
| Syntek Lenovo EasyCamera                                       | 2         | 0.6%    |
| Suyin 1.3M Front                                               | 2         | 0.6%    |
| Sunplus USB Microphone                                         | 2         | 0.6%    |
| Sunplus Asus Webcam                                            | 2         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.6%    |
| Microdia Integrated_Webcam_HD                                  | 2         | 0.6%    |
| Microdia HDE Webcam USB                                        | 2         | 0.6%    |
| Microdia GC02M2                                                | 2         | 0.6%    |
| Microdia Camera                                                | 2         | 0.6%    |
| Logitech HD Pro Webcam C920                                    | 2         | 0.6%    |
| Logitech C505 HD Webcam                                        | 2         | 0.6%    |
| Chicony VGA Webcam                                             | 2         | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 0.6%    |
| Chicony Lenovo EasyCamera                                      | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 9         | 25.71%  |
| Validity Sensors           | 8         | 22.86%  |
| Elan Microelectronics      | 7         | 20%     |
| Synaptics                  | 4         | 11.43%  |
| LighTuning Technology      | 4         | 11.43%  |
| Upek                       | 2         | 5.71%   |
| Focal-systems.Corp         | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 9         | 25.71%  |
| Elan ELAN:Fingerprint                                    | 5         | 14.29%  |
| LighTuning Fingerprint Reader                            | 3         | 8.57%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 5.71%   |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 5.71%   |
| Validity Sensors VFS491                                  | 2         | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 5.71%   |
| Elan ELAN:ARM-M4                                         | 2         | 5.71%   |
| Validity Sensors VFS471 Fingerprint Reader               | 1         | 2.86%   |
| Validity Sensors Fingerprint scanner                     | 1         | 2.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 2.86%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 1         | 20%     |
| Aktiv       | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 60%     |
| Broadcom 5880                       | 1         | 20%     |
| Aktiv Rutoken lite                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 487       | 83.25%  |
| 1     | 69        | 11.79%  |
| 2     | 14        | 2.39%   |
| 4     | 7         | 1.2%    |
| 5     | 4         | 0.68%   |
| 3     | 4         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 26.72%  |
| Graphics card            | 28        | 21.37%  |
| Communication controller | 27        | 20.61%  |
| Unassigned class         | 9         | 6.87%   |
| Multimedia controller    | 8         | 6.11%   |
| Net/ethernet             | 6         | 4.58%   |
| Chipcard                 | 5         | 3.82%   |
| Sound                    | 3         | 2.29%   |
| Net/wireless             | 3         | 2.29%   |
| Camera                   | 3         | 2.29%   |
| Flash memory             | 2         | 1.53%   |
| Bluetooth                | 2         | 1.53%   |

