Parrot - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Parrot.

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

Total: 449

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| Acer          | Nitro AN515-42              | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| Dell          | Latitude 7280               | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| ASUSTek       | X551MA                      | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| Dell          | Latitude 7370               | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Google        | Lillipup                    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| Google        | Robo360                     | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Apple         | MacBookPro9,2               | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| Apple         | MacBookAir7,2               | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| Dell          | Latitude E6400              | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| HP            | 250 G2                      | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| Unknown       | Unknown                     | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| HP            | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell          | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Lenovo        | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI           | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Toshiba       | Satellite L775D             | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell          | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba       | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| HP            | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| HP            | HDX PREMIUM SERIES          | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| HP            | ENVY 15                     | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| Acer          | Aspire 5250                 | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | X540YA                      | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Alienware     | 17 R4                       | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Dell          | Latitude 3400               | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Dell          | G7 7790                     | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Google        | Celes                       | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Dell          | XPS 12-9Q33                 | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| Acer          | Aspire 5250                 | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | Inspiron 5721               | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| HP            | Laptop 17-by0xxx            | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Notebook      | W510TU                      | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| HUAWEI        | WRT-WX9                     | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| Apple         | MacBookAir7,2               | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 82        | 24.26%  |
| Parrot 4.11  | 69        | 20.41%  |
| Parrot 5.1   | 52        | 15.38%  |
| Parrot 4.10  | 45        | 13.31%  |
| Parrot 5.3   | 23        | 6.8%    |
| Parrot 5.2   | 23        | 6.8%    |
| Parrot 4.8   | 15        | 4.44%   |
| Parrot 4.9   | 13        | 3.85%   |
| Parrot 4.7   | 10        | 2.96%   |
| Parrot 4.6   | 2         | 0.59%   |
| Parrot 4.5   | 1         | 0.3%    |
| Parrot 4.4   | 1         | 0.3%    |
| Parrot 4.2.2 | 1         | 0.3%    |
| Parrot 3.10  | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 322       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 37        | 10.79%  |
| 5.16.0-12parrot1-amd64   | 35        | 10.2%   |
| 6.0.0-12parrot1-amd64    | 29        | 8.45%   |
| 5.18.0-14parrot1-amd64   | 27        | 7.87%   |
| 5.7.0-2parrot2-amd64     | 26        | 7.58%   |
| 5.10.0-6parrot1-amd64    | 26        | 7.58%   |
| 6.1.0-1parrot1-amd64     | 22        | 6.41%   |
| 6.0.0-2parrot1-amd64     | 22        | 6.41%   |
| 5.18.0-1parrot1-amd64    | 14        | 4.08%   |
| 5.10.0-8parrot1-amd64    | 14        | 4.08%   |
| 5.5.0-1parrot1-amd64     | 12        | 3.5%    |
| 5.4.0-4parrot1-amd64     | 11        | 3.21%   |
| 5.6.0-2parrot1-amd64     | 9         | 2.62%   |
| 5.14.0-2parrot1-amd64    | 9         | 2.62%   |
| 5.9.0-2parrot1-amd64     | 7         | 2.04%   |
| 5.15.0-15parrot1-amd64   | 5         | 1.46%   |
| 5.8.0-2parrot1-amd64     | 3         | 0.87%   |
| 5.4.0-2parrot1-amd64     | 3         | 0.87%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.87%   |
| 5.10.0-5parrot1-amd64    | 3         | 0.87%   |
| 5.10.0-3parrot1-amd64    | 3         | 0.87%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.87%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.58%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.58%   |
| 4.18.0-parrot10-amd64    | 2         | 0.58%   |
| 6.1.0-0.deb11.5-amd64    | 1         | 0.29%   |
| 5.7.0-rc6-galliumos      | 1         | 0.29%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.29%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.29%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.29%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.29%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.29%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.29%   |
| 5.10.0-kali6-amd64       | 1         | 0.29%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.29%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.29%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.29%   |
| 4.14.0-parrot7-amd64     | 1         | 0.29%   |
| Unknown                  | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.0   | 51        | 14.96%  |
| 5.10.0  | 48        | 14.08%  |
| 5.14.0  | 45        | 13.2%   |
| 5.18.0  | 40        | 11.73%  |
| 5.16.0  | 35        | 10.26%  |
| 5.7.0   | 27        | 7.92%   |
| 6.1.0   | 23        | 6.74%   |
| 5.4.0   | 18        | 5.28%   |
| 5.5.0   | 12        | 3.52%   |
| 5.6.0   | 9         | 2.64%   |
| 5.9.0   | 7         | 2.05%   |
| 5.15.0  | 6         | 1.76%   |
| 5.8.0   | 5         | 1.47%   |
| 4.19.0  | 4         | 1.17%   |
| 5.3.0   | 3         | 0.88%   |
| 5.2.0   | 3         | 0.88%   |
| 4.18.0  | 2         | 0.59%   |
| 5.1.0   | 1         | 0.29%   |
| 4.14.0  | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 51        | 14.96%  |
| 5.10    | 48        | 14.08%  |
| 5.14    | 45        | 13.2%   |
| 5.18    | 40        | 11.73%  |
| 5.16    | 35        | 10.26%  |
| 5.7     | 27        | 7.92%   |
| 6.1     | 23        | 6.74%   |
| 5.4     | 18        | 5.28%   |
| 5.5     | 12        | 3.52%   |
| 5.6     | 9         | 2.64%   |
| 5.9     | 7         | 2.05%   |
| 5.15    | 6         | 1.76%   |
| 5.8     | 5         | 1.47%   |
| 4.19    | 4         | 1.17%   |
| 5.3     | 3         | 0.88%   |
| 5.2     | 3         | 0.88%   |
| 4.18    | 2         | 0.59%   |
| 5.1     | 1         | 0.29%   |
| 4.14    | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 321       | 99.69%  |
| i686   | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 232       | 70.95%  |
| KDE5          | 56        | 17.13%  |
| Unknown       | 18        | 5.5%    |
| KDE           | 13        | 3.98%   |
| XFCE          | 5         | 1.53%   |
| X-Cinnamon    | 1         | 0.31%   |
| LXDE          | 1         | 0.31%   |
| GNOME Classic | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 318       | 98.76%  |
| Tty     | 2         | 0.62%   |
| Wayland | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 162       | 49.24%  |
| Unknown | 106       | 32.22%  |
| TDM     | 50        | 15.2%   |
| SDDM    | 6         | 1.82%   |
| GDM     | 5         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 169       | 52.32%  |
| en_GB   | 27        | 8.36%   |
| fr_FR   | 17        | 5.26%   |
| Unknown | 14        | 4.33%   |
| es_ES   | 10        | 3.1%    |
| ru_RU   | 9         | 2.79%   |
| de_DE   | 9         | 2.79%   |
| pl_PL   | 8         | 2.48%   |
| en_IN   | 8         | 2.48%   |
| en_AU   | 8         | 2.48%   |
| pt_BR   | 7         | 2.17%   |
| it_IT   | 6         | 1.86%   |
| en_CA   | 4         | 1.24%   |
| tr_TR   | 3         | 0.93%   |
| es_AR   | 3         | 0.93%   |
| es_PE   | 2         | 0.62%   |
| es_MX   | 2         | 0.62%   |
| cs_CZ   | 2         | 0.62%   |
| pt_PT   | 1         | 0.31%   |
| nl_BE   | 1         | 0.31%   |
| id_ID   | 1         | 0.31%   |
| fr_CA   | 1         | 0.31%   |
| fi_FI   | 1         | 0.31%   |
| es_CO   | 1         | 0.31%   |
| es_CL   | 1         | 0.31%   |
| en_ZW   | 1         | 0.31%   |
| en_ZA   | 1         | 0.31%   |
| en_NZ   | 1         | 0.31%   |
| en_NG   | 1         | 0.31%   |
| en_DK   | 1         | 0.31%   |
| de_CH   | 1         | 0.31%   |
| C       | 1         | 0.31%   |
| arn_CL  | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 181       | 55.52%  |
| EFI  | 145       | 44.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 255       | 78.22%  |
| Ext4    | 44        | 13.5%   |
| Overlay | 10        | 3.07%   |
| Xfs     | 9         | 2.76%   |
| Unknown | 7         | 2.15%   |
| Tmpfs   | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 148       | 45.26%  |
| Unknown | 121       | 37%     |
| MBR     | 58        | 17.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 286       | 87.73%  |
| Yes       | 40        | 12.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 213       | 65.54%  |
| Yes       | 112       | 34.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 65        | 20.19%  |
| Hewlett-Packard       | 61        | 18.94%  |
| Dell                  | 53        | 16.46%  |
| ASUSTek Computer      | 34        | 10.56%  |
| Acer                  | 24        | 7.45%   |
| MSI                   | 14        | 4.35%   |
| Apple                 | 11        | 3.42%   |
| Toshiba               | 8         | 2.48%   |
| HUAWEI                | 5         | 1.55%   |
| Samsung Electronics   | 4         | 1.24%   |
| Alienware             | 4         | 1.24%   |
| Sony                  | 3         | 0.93%   |
| Fujitsu               | 3         | 0.93%   |
| Razer                 | 2         | 0.62%   |
| Quanta                | 2         | 0.62%   |
| Notebook              | 2         | 0.62%   |
| Google                | 2         | 0.62%   |
| Gateway               | 2         | 0.62%   |
| Unknown               | 2         | 0.62%   |
| Wortmann AG           | 1         | 0.31%   |
| Toxic                 | 1         | 0.31%   |
| Timi                  | 1         | 0.31%   |
| System76              | 1         | 0.31%   |
| Standard              | 1         | 0.31%   |
| Positivo Bahia - VAIO | 1         | 0.31%   |
| Positivo              | 1         | 0.31%   |
| Panasonic             | 1         | 0.31%   |
| Onda TLC              | 1         | 0.31%   |
| Metabox               | 1         | 0.31%   |
| Jumper                | 1         | 0.31%   |
| Irbis                 | 1         | 0.31%   |
| Intel Client Systems  | 1         | 0.31%   |
| GPU Company           | 1         | 0.31%   |
| Gigabyte Technology   | 1         | 0.31%   |
| eMachines             | 1         | 0.31%   |
| Eluktronics           | 1         | 0.31%   |
| Digma                 | 1         | 0.31%   |
| Clevo                 | 1         | 0.31%   |
| Chuwi                 | 1         | 0.31%   |
| BANGHO                | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| HP Notebook                      | 4         | 1.24%   |
| Unknown                          | 4         | 1.24%   |
| MSI Modern 15 A5M                | 3         | 0.93%   |
| Lenovo IdeaPad 3 15IIL05 81WE    | 3         | 0.93%   |
| HP Pavilion 15                   | 3         | 0.93%   |
| HP EliteBook 8470p               | 3         | 0.93%   |
| Dell Latitude E6420              | 3         | 0.93%   |
| Dell Inspiron MM061              | 3         | 0.93%   |
| Quanta TW9/SW9                   | 2         | 0.62%   |
| MSI Katana GF66 12UC             | 2         | 0.62%   |
| HP ProBook 650 G1                | 2         | 0.62%   |
| HP Pavilion dv6                  | 2         | 0.62%   |
| HP Laptop 15-dy2xxx              | 2         | 0.62%   |
| Dell Latitude E7440              | 2         | 0.62%   |
| Dell Latitude E6410              | 2         | 0.62%   |
| Dell Latitude 7280               | 2         | 0.62%   |
| Dell Inspiron N5110              | 2         | 0.62%   |
| ASUS Q524UQ                      | 2         | 0.62%   |
| Apple MacBookPro8,1              | 2         | 0.62%   |
| Apple MacBookAir7,2              | 2         | 0.62%   |
| Acer Nitro AN515-57              | 2         | 0.62%   |
| Acer Nitro AN515-54              | 2         | 0.62%   |
| Acer Extensa 215-54              | 2         | 0.62%   |
| Acer Aspire ES1-111M             | 2         | 0.62%   |
| Wortmann AG TERRA_MOBILE_1542    | 1         | 0.31%   |
| Toxic GM7MQ8P                    | 1         | 0.31%   |
| Toshiba Satellite-L845           | 1         | 0.31%   |
| Toshiba Satellite L775D          | 1         | 0.31%   |
| Toshiba Satellite L750           | 1         | 0.31%   |
| Toshiba Satellite L655           | 1         | 0.31%   |
| Toshiba Satellite L300D          | 1         | 0.31%   |
| Toshiba Satellite Click 2 L35W-B | 1         | 0.31%   |
| Toshiba Satellite C855D          | 1         | 0.31%   |
| Toshiba Satellite C75D-B         | 1         | 0.31%   |
| Timi TM1613                      | 1         | 0.31%   |
| System76 Gazelle                 | 1         | 0.31%   |
| Sony VPCSB1C5E                   | 1         | 0.31%   |
| Sony VPCCB15FG                   | 1         | 0.31%   |
| Sony SVP1321L1EBI                | 1         | 0.31%   |
| Samsung RV415/RV515              | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 38        | 11.8%   |
| Dell Latitude      | 22        | 6.83%   |
| Dell Inspiron      | 19        | 5.9%    |
| HP Pavilion        | 15        | 4.66%   |
| Lenovo IdeaPad     | 13        | 4.04%   |
| HP Laptop          | 11        | 3.42%   |
| HP EliteBook       | 10        | 3.11%   |
| Acer Aspire        | 10        | 3.11%   |
| Toshiba Satellite  | 7         | 2.17%   |
| HP ProBook         | 6         | 1.86%   |
| ASUS VivoBook      | 6         | 1.86%   |
| Acer Nitro         | 6         | 1.86%   |
| ASUS ASUS          | 5         | 1.55%   |
| HP ZBook           | 4         | 1.24%   |
| HP Notebook        | 4         | 1.24%   |
| Dell XPS           | 4         | 1.24%   |
| Unknown            | 4         | 1.24%   |
| MSI Modern         | 3         | 0.93%   |
| MSI Katana         | 3         | 0.93%   |
| Lenovo Legion      | 3         | 0.93%   |
| Fujitsu LIFEBOOK   | 3         | 0.93%   |
| Dell Precision     | 3         | 0.93%   |
| ASUS ROG           | 3         | 0.93%   |
| Acer Swift         | 3         | 0.93%   |
| Razer Blade        | 2         | 0.62%   |
| Quanta TW9         | 2         | 0.62%   |
| MSI GT60           | 2         | 0.62%   |
| HP Victus          | 2         | 0.62%   |
| HP ENVY            | 2         | 0.62%   |
| HP 250             | 2         | 0.62%   |
| Dell Vostro        | 2         | 0.62%   |
| ASUS Zenbook       | 2         | 0.62%   |
| ASUS TUF           | 2         | 0.62%   |
| ASUS Q524UQ        | 2         | 0.62%   |
| Apple MacBookPro8  | 2         | 0.62%   |
| Apple MacBookPro11 | 2         | 0.62%   |
| Apple MacBookAir7  | 2         | 0.62%   |
| Alienware m15      | 2         | 0.62%   |
| Acer Predator      | 2         | 0.62%   |
| Acer Extensa       | 2         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 40        | 12.42%  |
| 2019 | 36        | 11.18%  |
| 2011 | 33        | 10.25%  |
| 2020 | 31        | 9.63%   |
| 2012 | 26        | 8.07%   |
| 2018 | 25        | 7.76%   |
| 2016 | 23        | 7.14%   |
| 2013 | 22        | 6.83%   |
| 2017 | 17        | 5.28%   |
| 2022 | 16        | 4.97%   |
| 2014 | 15        | 4.66%   |
| 2010 | 11        | 3.42%   |
| 2015 | 10        | 3.11%   |
| 2008 | 7         | 2.17%   |
| 2006 | 4         | 1.24%   |
| 2007 | 3         | 0.93%   |
| 2009 | 2         | 0.62%   |
| 2023 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 322       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 322       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 320       | 99.38%  |
| Yes  | 2         | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 88        | 27.16%  |
| 8.01-16.0   | 71        | 21.91%  |
| 16.01-24.0  | 66        | 20.37%  |
| 3.01-4.0    | 56        | 17.28%  |
| 32.01-64.0  | 23        | 7.1%    |
| 1.01-2.0    | 8         | 2.47%   |
| 64.01-256.0 | 5         | 1.54%   |
| 24.01-32.0  | 4         | 1.23%   |
| 2.01-3.0    | 3         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 114       | 33.73%  |
| 2.01-3.0   | 109       | 32.25%  |
| 3.01-4.0   | 51        | 15.09%  |
| 4.01-8.0   | 42        | 12.43%  |
| 0.51-1.0   | 13        | 3.85%   |
| 8.01-16.0  | 7         | 2.07%   |
| 16.01-24.0 | 1         | 0.3%    |
| 0.01-0.5   | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 67.48%  |
| 2      | 96        | 29.45%  |
| 3      | 9         | 2.76%   |
| 0      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 226       | 69.97%  |
| Yes       | 97        | 30.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 80.8%   |
| No        | 62        | 19.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 99.07%  |
| No        | 3         | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 79.14%  |
| No        | 68        | 20.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 95        | 29.32%  |
| France       | 19        | 5.86%   |
| Germany      | 18        | 5.56%   |
| UK           | 14        | 4.32%   |
| Spain        | 14        | 4.32%   |
| Russia       | 11        | 3.4%    |
| Netherlands  | 11        | 3.4%    |
| India        | 10        | 3.09%   |
| Brazil       | 10        | 3.09%   |
| Italy        | 8         | 2.47%   |
| Australia    | 8         | 2.47%   |
| Kenya        | 7         | 2.16%   |
| Canada       | 6         | 1.85%   |
| Indonesia    | 5         | 1.54%   |
| Turkey       | 4         | 1.23%   |
| Sweden       | 4         | 1.23%   |
| Poland       | 4         | 1.23%   |
| Mexico       | 4         | 1.23%   |
| Czechia      | 4         | 1.23%   |
| Switzerland  | 3         | 0.93%   |
| South Africa | 3         | 0.93%   |
| Iraq         | 3         | 0.93%   |
| Finland      | 3         | 0.93%   |
| Denmark      | 3         | 0.93%   |
| Bangladesh   | 3         | 0.93%   |
| Argentina    | 3         | 0.93%   |
| Puerto Rico  | 2         | 0.62%   |
| Portugal     | 2         | 0.62%   |
| Peru         | 2         | 0.62%   |
| Pakistan     | 2         | 0.62%   |
| Nepal        | 2         | 0.62%   |
| Namibia      | 2         | 0.62%   |
| Myanmar      | 2         | 0.62%   |
| Mongolia     | 2         | 0.62%   |
| Luxembourg   | 2         | 0.62%   |
| Chile        | 2         | 0.62%   |
| Bulgaria     | 2         | 0.62%   |
| Austria      | 2         | 0.62%   |
| Algeria      | 2         | 0.62%   |
| Zimbabwe     | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Nairobi       | 6         | 1.76%   |
| Amsterdam     | 6         | 1.76%   |
| Moscow        | 5         | 1.47%   |
| Dallas        | 5         | 1.47%   |
| Seattle       | 4         | 1.18%   |
| Melbourne     | 4         | 1.18%   |
| London        | 4         | 1.18%   |
| Houston       | 4         | 1.18%   |
| Sydney        | 3         | 0.88%   |
| Prague        | 3         | 0.88%   |
| Paris         | 3         | 0.88%   |
| Lyon          | 3         | 0.88%   |
| Dhaka         | 3         | 0.88%   |
| Chicago       | 3         | 0.88%   |
| Berlin        | 3         | 0.88%   |
| Barcelona     | 3         | 0.88%   |
| Zurich        | 2         | 0.59%   |
| Warsaw        | 2         | 0.59%   |
| Visalia       | 2         | 0.59%   |
| Ulan Bator    | 2         | 0.59%   |
| Stockholm     | 2         | 0.59%   |
| St Petersburg | 2         | 0.59%   |
| San Juan      | 2         | 0.59%   |
| Ruskin        | 2         | 0.59%   |
| Rome          | 2         | 0.59%   |
| Reading       | 2         | 0.59%   |
| Pretoria      | 2         | 0.59%   |
| New York      | 2         | 0.59%   |
| Mostoles      | 2         | 0.59%   |
| Mesa          | 2         | 0.59%   |
| Madrid        | 2         | 0.59%   |
| Luxembourg    | 2         | 0.59%   |
| Los Angeles   | 2         | 0.59%   |
| Helsinki      | 2         | 0.59%   |
| Dublin        | 2         | 0.59%   |
| Dresden       | 2         | 0.59%   |
| Camden        | 2         | 0.59%   |
| Bursa         | 2         | 0.59%   |
| Baghdad       | 2         | 0.59%   |
| Zagreb        | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 79     | 15.78%  |
| WDC                         | 49        | 58     | 11.89%  |
| Toshiba                     | 47        | 52     | 11.41%  |
| Seagate                     | 31        | 32     | 7.52%   |
| Unknown                     | 29        | 31     | 7.04%   |
| Kingston                    | 27        | 27     | 6.55%   |
| SanDisk                     | 17        | 21     | 4.13%   |
| Micron Technology           | 14        | 14     | 3.4%    |
| Hitachi                     | 14        | 16     | 3.4%    |
| Crucial                     | 14        | 19     | 3.4%    |
| SK hynix                    | 13        | 14     | 3.16%   |
| HGST                        | 11        | 14     | 2.67%   |
| Intel                       | 8         | 13     | 1.94%   |
| China                       | 6         | 6      | 1.46%   |
| Apple                       | 6         | 6      | 1.46%   |
| A-DATA Technology           | 6         | 6      | 1.46%   |
| KIOXIA                      | 5         | 6      | 1.21%   |
| LITEON                      | 4         | 4      | 0.97%   |
| YMTC                        | 3         | 3      | 0.73%   |
| Unknown                     | 3         | 3      | 0.73%   |
| Team                        | 2         | 2      | 0.49%   |
| PNY                         | 2         | 2      | 0.49%   |
| Phison                      | 2         | 2      | 0.49%   |
| Lexar                       | 2         | 2      | 0.49%   |
| Kingston Technology Company | 2         | 2      | 0.49%   |
| KingFast                    | 2         | 3      | 0.49%   |
| HUAWEI                      | 2         | 2      | 0.49%   |
| BR                          | 2         | 2      | 0.49%   |
| Zheino                      | 1         | 1      | 0.24%   |
| W800SH                      | 1         | 1      | 0.24%   |
| Unknown (583)               | 1         | 1      | 0.24%   |
| Transcend                   | 1         | 1      | 0.24%   |
| Silicon Motion              | 1         | 1      | 0.24%   |
| SCY                         | 1         | 1      | 0.24%   |
| S3+                         | 1         | 1      | 0.24%   |
| RZX                         | 1         | 1      | 0.24%   |
| Patriot                     | 1         | 1      | 0.24%   |
| Netac                       | 1         | 1      | 0.24%   |
| LITEONIT                    | 1         | 1      | 0.24%   |
| KingSpec                    | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB              | 10        | 2.31%   |
| Toshiba MQ01ABF050 500GB            | 7         | 1.62%   |
| Toshiba MQ01ABD100 1TB              | 7         | 1.62%   |
| Kingston NVMe SSD Drive 512GB       | 5         | 1.15%   |
| Unknown SD/MMC/MS PRO 64GB          | 4         | 0.92%   |
| Unknown MMC Card  32GB              | 4         | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 0.92%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.92%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.92%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.92%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.69%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.69%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.69%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 3         | 0.69%   |
| SanDisk SSD PLUS 1000GB             | 3         | 0.69%   |
| SanDisk NVMe SSD Drive 1TB          | 3         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.69%   |
| Kingston OM8PCP3512F-AB 512GB       | 3         | 0.69%   |
| Unknown                             | 3         | 0.69%   |
| YMTC PC005 256GB                    | 2         | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB            | 2         | 0.46%   |
| WDC WD10SPZX-08Z10 1TB              | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB  | 2         | 0.46%   |
| Unknown MMC Card  64GB              | 2         | 0.46%   |
| Toshiba KXG6AZNV256G 256GB          | 2         | 0.46%   |
| Team TM8PS7512G 512GB SSD           | 2         | 0.46%   |
| Seagate ST9250315AS 250GB           | 2         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.46%   |
| Seagate BUP Slim BK 2TB             | 2         | 0.46%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.46%   |
| Samsung SSD 980 PRO 1TB             | 2         | 0.46%   |
| Samsung SSD 980 1TB                 | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.46%   |
| Samsung SSD 860 EVO M.2 500GB       | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 36        | 40     | 26.47%  |
| WDC                 | 34        | 38     | 25%     |
| Seagate             | 30        | 31     | 22.06%  |
| Hitachi             | 14        | 16     | 10.29%  |
| HGST                | 11        | 14     | 8.09%   |
| Samsung Electronics | 5         | 5      | 3.68%   |
| Unknown             | 4         | 5      | 2.94%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| ASMedia             | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 26     | 19.01%  |
| Kingston            | 12        | 12     | 9.92%   |
| Crucial             | 11        | 16     | 9.09%   |
| SanDisk             | 10        | 11     | 8.26%   |
| WDC                 | 6         | 7      | 4.96%   |
| China               | 6         | 6      | 4.96%   |
| Apple               | 5         | 5      | 4.13%   |
| Toshiba             | 4         | 5      | 3.31%   |
| Micron Technology   | 4         | 4      | 3.31%   |
| LITEON              | 4         | 4      | 3.31%   |
| Team                | 2         | 2      | 1.65%   |
| SK hynix            | 2         | 2      | 1.65%   |
| PNY                 | 2         | 2      | 1.65%   |
| KingFast            | 2         | 2      | 1.65%   |
| Intel               | 2         | 2      | 1.65%   |
| BR                  | 2         | 2      | 1.65%   |
| A-DATA Technology   | 2         | 2      | 1.65%   |
| Unknown             | 2         | 2      | 1.65%   |
| Zheino              | 1         | 1      | 0.83%   |
| W800SH              | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |
| Transcend           | 1         | 1      | 0.83%   |
| Seagate             | 1         | 1      | 0.83%   |
| S3+                 | 1         | 1      | 0.83%   |
| RZX                 | 1         | 1      | 0.83%   |
| Patriot             | 1         | 1      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 1      | 0.83%   |
| Lexar               | 1         | 1      | 0.83%   |
| KingSpec            | 1         | 2      | 0.83%   |
| Kingmax             | 1         | 1      | 0.83%   |
| Intenso             | 1         | 2      | 0.83%   |
| HS-SSD-C100         | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| Corsair             | 1         | 2      | 0.83%   |
| BHT                 | 1         | 1      | 0.83%   |
| ASMT                | 1         | 1      | 0.83%   |
| Apacer              | 1         | 2      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 133       | 151    | 33.76%  |
| NVMe    | 120       | 150    | 30.46%  |
| SSD     | 112       | 136    | 28.43%  |
| MMC     | 23        | 26     | 5.84%   |
| Unknown | 6         | 6      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 221       | 276    | 58.01%  |
| NVMe | 120       | 149    | 31.5%   |
| MMC  | 23        | 26     | 6.04%   |
| SAS  | 17        | 18     | 4.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 153       | 192    | 63.49%  |
| 0.51-1.0   | 81        | 87     | 33.61%  |
| 1.01-2.0   | 7         | 8      | 2.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 26.99%  |
| 101-250        | 64        | 19.63%  |
| 501-1000       | 56        | 17.18%  |
| Unknown        | 37        | 11.35%  |
| 1001-2000      | 33        | 10.12%  |
| 51-100         | 17        | 5.21%   |
| 21-50          | 14        | 4.29%   |
| 1-20           | 9         | 2.76%   |
| More than 3000 | 4         | 1.23%   |
| 2001-3000      | 4         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 107       | 31.94%  |
| 51-100         | 63        | 18.81%  |
| 1-20           | 46        | 13.73%  |
| 101-250        | 40        | 11.94%  |
| Unknown        | 37        | 11.04%  |
| 251-500        | 27        | 8.06%   |
| 501-1000       | 9         | 2.69%   |
| 1001-2000      | 2         | 0.6%    |
| 0              | 2         | 0.6%    |
| More than 3000 | 1         | 0.3%    |
| 2001-3000      | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 5.41%   |
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 5.41%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 2         | 2      | 5.41%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 2.7%    |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.7%    |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.7%    |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 2.7%    |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.7%    |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.7%    |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.7%    |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.7%    |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 2.7%    |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.7%    |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.7%    |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.7%    |
| Kingston SUV400S37480G 480GB SSD                    | 1         | 1      | 2.7%    |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 2.7%    |
| Hitachi HTS725050A9A364 500GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.7%    |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.7%    |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.7%    |
| Hewlett-Packard SSD S700 Pro 1TB                    | 1         | 1      | 2.7%    |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.7%    |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 2.7%    |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.7%    |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.7%    |
| Unknown                                             | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 16.22%  |
| Hitachi             | 5         | 5      | 13.51%  |
| Seagate             | 4         | 4      | 10.81%  |
| Samsung Electronics | 4         | 4      | 10.81%  |
| WDC                 | 3         | 3      | 8.11%   |
| HGST                | 3         | 3      | 8.11%   |
| LITEON              | 2         | 2      | 5.41%   |
| A-DATA Technology   | 2         | 2      | 5.41%   |
| SanDisk             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| Unknown             | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 24%     |
| Hitachi             | 5         | 5      | 20%     |
| Seagate             | 4         | 4      | 16%     |
| WDC                 | 3         | 3      | 12%     |
| Samsung Electronics | 3         | 3      | 12%     |
| HGST                | 3         | 3      | 12%     |
| Fujitsu             | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 25     | 67.57%  |
| SSD  | 10        | 10     | 27.03%  |
| NVMe | 2         | 2      | 5.41%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 176       | 220    | 49.16%  |
| Detected | 146       | 212    | 40.78%  |
| Malfunc  | 36        | 37     | 10.06%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 235       | 59.19%  |
| Samsung Electronics          | 42        | 10.58%  |
| AMD                          | 33        | 8.31%   |
| SanDisk                      | 18        | 4.53%   |
| Kingston Technology Company  | 17        | 4.28%   |
| SK hynix                     | 11        | 2.77%   |
| Micron Technology            | 10        | 2.52%   |
| Toshiba America Info Systems | 7         | 1.76%   |
| KIOXIA                       | 5         | 1.26%   |
| Yangtze Memory Technologies  | 3         | 0.76%   |
| Silicon Motion               | 3         | 0.76%   |
| Nvidia                       | 3         | 0.76%   |
| Micron/Crucial Technology    | 3         | 0.76%   |
| ADATA Technology             | 3         | 0.76%   |
| Phison Electronics           | 2         | 0.5%    |
| Realtek Semiconductor        | 1         | 0.25%   |
| Apple                        | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 31        | 7.18%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 28        | 6.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 25        | 5.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 23        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 20        | 4.63%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 19        | 4.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 18        | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 11        | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 2.55%   |
| Micron NVMe Storage Controller                                                         | 10        | 2.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 10        | 2.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 8         | 1.85%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 7         | 1.62%   |
| Kingston Company Company Non-Volatile memory controller                                | 7         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 7         | 1.62%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 6         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 6         | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 5         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.16%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 5         | 1.16%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.16%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 4         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 4         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 0.93%   |
| Yangtze Memory Non-Volatile memory controller                                          | 3         | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.69%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                   | 3         | 0.69%   |
| SK hynix BC511                                                                         | 3         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 0.69%   |
| SanDisk NVMe Controller                                                                | 3         | 0.69%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 218       | 53.43%  |
| NVMe | 120       | 29.41%  |
| RAID | 44        | 10.78%  |
| IDE  | 26        | 6.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 276       | 85.71%  |
| AMD    | 46        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 3.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 2.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 1.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.55%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 1.55%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.24%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.24%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.24%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.24%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.24%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 1.24%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.93%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 0.93%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 3         | 0.93%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.93%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 0.93%   |
| Intel 12th Gen Core i5-12500H                 | 3         | 0.93%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 3         | 0.93%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 0.93%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.93%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.62%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 27.02%  |
| Intel Core i7           | 75        | 23.29%  |
| Other                   | 43        | 13.35%  |
| Intel Core i3           | 31        | 9.63%   |
| Intel Celeron           | 18        | 5.59%   |
| AMD Ryzen 7             | 15        | 4.66%   |
| AMD Ryzen 5             | 10        | 3.11%   |
| Intel Core 2 Duo        | 9         | 2.8%    |
| AMD A6                  | 6         | 1.86%   |
| Intel Core 2            | 4         | 1.24%   |
| Intel Pentium           | 3         | 0.93%   |
| AMD Ryzen 3             | 3         | 0.93%   |
| AMD E1                  | 3         | 0.93%   |
| Intel Pentium Silver    | 2         | 0.62%   |
| Intel Atom              | 2         | 0.62%   |
| AMD A4                  | 2         | 0.62%   |
| Intel Pentium Dual-Core | 1         | 0.31%   |
| Intel Core m5           | 1         | 0.31%   |
| Intel Core 2 Quad       | 1         | 0.31%   |
| Intel Core 2 Extreme    | 1         | 0.31%   |
| AMD FX                  | 1         | 0.31%   |
| AMD E2                  | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD C-50                | 1         | 0.31%   |
| AMD Athlon X2           | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 166       | 51.55%  |
| 4      | 91        | 28.26%  |
| 6      | 27        | 8.39%   |
| 8      | 19        | 5.9%    |
| 12     | 7         | 2.17%   |
| 14     | 5         | 1.55%   |
| 1      | 4         | 1.24%   |
| 10     | 3         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 322       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 245       | 76.09%  |
| 1      | 76        | 23.6%   |
| 8      | 1         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 317       | 98.45%  |
| Unknown        | 5         | 1.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 40.73%  |
| 0x206a7    | 22        | 6.69%   |
| 0x306a9    | 15        | 4.56%   |
| 0x906a3    | 12        | 3.65%   |
| 0x806ec    | 12        | 3.65%   |
| 0x406e3    | 10        | 3.04%   |
| 0x806e9    | 9         | 2.74%   |
| 0x806c1    | 9         | 2.74%   |
| 0xa0652    | 8         | 2.43%   |
| 0x906ea    | 8         | 2.43%   |
| 0x806ea    | 7         | 2.13%   |
| 0x706a8    | 6         | 1.82%   |
| 0x806d1    | 5         | 1.52%   |
| 0x706e5    | 5         | 1.52%   |
| 0x40651    | 5         | 1.52%   |
| 0x6f6      | 4         | 1.22%   |
| 0x306d4    | 4         | 1.22%   |
| 0x306c3    | 4         | 1.22%   |
| 0x1067a    | 4         | 1.22%   |
| 0x08600106 | 4         | 1.22%   |
| 0x906a4    | 3         | 0.91%   |
| 0x0a50000c | 3         | 0.91%   |
| 0x08608103 | 3         | 0.91%   |
| 0x07030105 | 3         | 0.91%   |
| 0x906e9    | 2         | 0.61%   |
| 0x806eb    | 2         | 0.61%   |
| 0x6fd      | 2         | 0.61%   |
| 0x406c4    | 2         | 0.61%   |
| 0x30678    | 2         | 0.61%   |
| 0x08108109 | 2         | 0.61%   |
| 0x08108102 | 2         | 0.61%   |
| 0x06006705 | 2         | 0.61%   |
| 0x03000027 | 2         | 0.61%   |
| 0xa0660    | 1         | 0.3%    |
| 0x906ed    | 1         | 0.3%    |
| 0x806c2    | 1         | 0.3%    |
| 0x706a1    | 1         | 0.3%    |
| 0x506e3    | 1         | 0.3%    |
| 0x506c9    | 1         | 0.3%    |
| 0x40661    | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 18.63%  |
| SandyBridge      | 34        | 10.56%  |
| IvyBridge        | 26        | 8.07%   |
| Skylake          | 20        | 6.21%   |
| Haswell          | 20        | 6.21%   |
| TigerLake        | 18        | 5.59%   |
| Alderlake Hybrid | 14        | 4.35%   |
| Broadwell        | 13        | 4.04%   |
| Unknown          | 12        | 3.73%   |
| IceLake          | 11        | 3.42%   |
| CometLake        | 11        | 3.42%   |
| Silvermont       | 10        | 3.11%   |
| Penryn           | 10        | 3.11%   |
| Goldmont plus    | 8         | 2.48%   |
| Zen 2            | 7         | 2.17%   |
| Core             | 7         | 2.17%   |
| Zen+             | 6         | 1.86%   |
| Zen 3            | 6         | 1.86%   |
| Westmere         | 6         | 1.86%   |
| Excavator        | 5         | 1.55%   |
| Puma             | 3         | 0.93%   |
| Jaguar           | 3         | 0.93%   |
| Zen              | 2         | 0.62%   |
| Piledriver       | 2         | 0.62%   |
| K10 Llano        | 2         | 0.62%   |
| Goldmont         | 2         | 0.62%   |
| Bobcat           | 2         | 0.62%   |
| Nehalem          | 1         | 0.31%   |
| K8 & K10 hybrid  | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 258       | 59.86%  |
| Nvidia | 102       | 23.67%  |
| AMD    | 71        | 16.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 6.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 5.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 3.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 3.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 2.74%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.51%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.51%   |
| Intel HD Graphics 620                                                                    | 10        | 2.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 2.28%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.6%    |
| AMD Renoir                                                                               | 7         | 1.6%    |
| AMD Lucienne                                                                             | 7         | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 1.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 1.14%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 5         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.14%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.91%   |
| Intel HD Graphics 630                                                                    | 4         | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.68%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 158       | 48.92%  |
| Intel + Nvidia | 82        | 25.39%  |
| 1 x AMD        | 43        | 13.31%  |
| Intel + AMD    | 17        | 5.26%   |
| 1 x Nvidia     | 11        | 3.41%   |
| AMD + Nvidia   | 9         | 2.79%   |
| 2 x AMD        | 2         | 0.62%   |
| 2 x Nvidia     | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 292       | 90.4%   |
| Proprietary | 28        | 8.67%   |
| Unknown     | 3         | 0.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 250       | 76.92%  |
| 1.01-2.0   | 20        | 6.15%   |
| 0.51-1.0   | 17        | 5.23%   |
| 0.01-0.5   | 16        | 4.92%   |
| 3.01-4.0   | 14        | 4.31%   |
| 5.01-6.0   | 4         | 1.23%   |
| 7.01-8.0   | 2         | 0.62%   |
| 2.01-3.0   | 2         | 0.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 77        | 21.45%  |
| LG Display              | 64        | 17.83%  |
| BOE                     | 58        | 16.16%  |
| Chimei Innolux          | 47        | 13.09%  |
| Samsung Electronics     | 30        | 8.36%   |
| Apple                   | 12        | 3.34%   |
| Chi Mei Optoelectronics | 10        | 2.79%   |
| Sharp                   | 9         | 2.51%   |
| Dell                    | 7         | 1.95%   |
| PANDA                   | 5         | 1.39%   |
| Lenovo                  | 4         | 1.11%   |
| Acer                    | 3         | 0.84%   |
| Sceptre Tech            | 2         | 0.56%   |
| Hewlett-Packard         | 2         | 0.56%   |
| Eizo                    | 2         | 0.56%   |
| CSO                     | 2         | 0.56%   |
| Ancor Communications    | 2         | 0.56%   |
| ___                     | 1         | 0.28%   |
| VIZ                     | 1         | 0.28%   |
| ViewSonic               | 1         | 0.28%   |
| Unknown (AAA)           | 1         | 0.28%   |
| Unknown                 | 1         | 0.28%   |
| STD                     | 1         | 0.28%   |
| STA                     | 1         | 0.28%   |
| SANYO                   | 1         | 0.28%   |
| Planar                  | 1         | 0.28%   |
| Pixio                   | 1         | 0.28%   |
| Philips                 | 1         | 0.28%   |
| Panasonic               | 1         | 0.28%   |
| ONN                     | 1         | 0.28%   |
| NEC Computers           | 1         | 0.28%   |
| LG Philips              | 1         | 0.28%   |
| Kogan                   | 1         | 0.28%   |
| InfoVision              | 1         | 0.28%   |
| Iiyama                  | 1         | 0.28%   |
| Goldstar                | 1         | 0.28%   |
| Element                 | 1         | 0.28%   |
| BOE Technology Group    | 1         | 0.28%   |
| BenQ                    | 1         | 0.28%   |
| AOC                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 1.11%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 4         | 1.11%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 3         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.84%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch       | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 3         | 0.84%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 2         | 0.56%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch         | 2         | 0.56%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 2         | 0.56%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch         | 2         | 0.56%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch         | 2         | 0.56%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch      | 2         | 0.56%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 2         | 0.56%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                | 2         | 0.56%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.56%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 2         | 0.56%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 2         | 0.56%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 2         | 0.56%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 2         | 0.56%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.28%   |
| VIZ LCD Monitor VA19L HDTV10T                                        | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 149       | 43.57%  |
| 1366x768 (WXGA)    | 114       | 33.33%  |
| 1600x900 (HD+)     | 19        | 5.56%   |
| 1280x800 (WXGA)    | 12        | 3.51%   |
| 3840x2160 (4K)     | 8         | 2.34%   |
| 1440x900 (WXGA+)   | 7         | 2.05%   |
| 2560x1440 (QHD)    | 5         | 1.46%   |
| 1920x1200 (WUXGA)  | 4         | 1.17%   |
| 1680x1050 (WSXGA+) | 4         | 1.17%   |
| 2880x1800          | 3         | 0.88%   |
| 2560x1600          | 3         | 0.88%   |
| 2160x1440          | 2         | 0.58%   |
| 1024x768 (XGA)     | 2         | 0.58%   |
| 3840x2400          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 3200x1080          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 2240x1400          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1920x515           | 1         | 0.29%   |
| 1360x768           | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |
| Unknown            | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 157       | 43.98%  |
| 14      | 49        | 13.73%  |
| 13      | 44        | 12.32%  |
| 17      | 30        | 8.4%    |
| 12      | 16        | 4.48%   |
| 27      | 10        | 2.8%    |
| 24      | 7         | 1.96%   |
| 11      | 7         | 1.96%   |
| 31      | 5         | 1.4%    |
| 16      | 5         | 1.4%    |
| 23      | 4         | 1.12%   |
| 21      | 4         | 1.12%   |
| Unknown | 4         | 1.12%   |
| 22      | 3         | 0.84%   |
| 32      | 2         | 0.56%   |
| 19      | 2         | 0.56%   |
| 18      | 2         | 0.56%   |
| 84      | 1         | 0.28%   |
| 72      | 1         | 0.28%   |
| 54      | 1         | 0.28%   |
| 48      | 1         | 0.28%   |
| 40      | 1         | 0.28%   |
| 29      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 231       | 64.89%  |
| 201-300     | 42        | 11.8%   |
| 351-400     | 36        | 10.11%  |
| 501-600     | 21        | 5.9%    |
| 401-500     | 9         | 2.53%   |
| 601-700     | 6         | 1.69%   |
| Unknown     | 4         | 1.12%   |
| 701-800     | 2         | 0.56%   |
| 1501-2000   | 2         | 0.56%   |
| 1001-1500   | 2         | 0.56%   |
| 801-900     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 282       | 86.77%  |
| 16/10   | 34        | 10.46%  |
| 4/3     | 2         | 0.62%   |
| 3/2     | 2         | 0.62%   |
| 6/5     | 1         | 0.31%   |
| 32/9    | 1         | 0.31%   |
| 3.73    | 1         | 0.31%   |
| 21/9    | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 160       | 44.82%  |
| 81-90          | 77        | 21.57%  |
| 121-130        | 27        | 7.56%   |
| 71-80          | 16        | 4.48%   |
| 61-70          | 16        | 4.48%   |
| 201-250        | 16        | 4.48%   |
| 301-350        | 11        | 3.08%   |
| 51-60          | 7         | 1.96%   |
| 351-500        | 7         | 1.96%   |
| More than 1000 | 4         | 1.12%   |
| Unknown        | 4         | 1.12%   |
| 131-140        | 3         | 0.84%   |
| 251-300        | 2         | 0.56%   |
| 151-200        | 2         | 0.56%   |
| 141-150        | 2         | 0.56%   |
| 111-120        | 2         | 0.56%   |
| 501-1000       | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 156       | 44.07%  |
| 101-120       | 111       | 31.36%  |
| 51-100        | 48        | 13.56%  |
| 161-240       | 23        | 6.5%    |
| More than 240 | 8         | 2.26%   |
| 1-50          | 4         | 1.13%   |
| Unknown       | 4         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 276       | 84.66%  |
| 2     | 42        | 12.88%  |
| 3     | 5         | 1.53%   |
| 0     | 3         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 186       | 34.13%  |
| Realtek Semiconductor                  | 177       | 32.48%  |
| Qualcomm Atheros                       | 64        | 11.74%  |
| Broadcom                               | 28        | 5.14%   |
| MediaTek                               | 11        | 2.02%   |
| Broadcom Limited                       | 10        | 1.83%   |
| TP-Link                                | 8         | 1.47%   |
| Samsung Electronics                    | 8         | 1.47%   |
| Xiaomi                                 | 5         | 0.92%   |
| Ralink Technology                      | 4         | 0.73%   |
| Qualcomm Atheros Communications        | 4         | 0.73%   |
| Huawei Technologies                    | 4         | 0.73%   |
| OPPO Electronics                       | 3         | 0.55%   |
| NetGear                                | 3         | 0.55%   |
| ASUSTek Computer                       | 3         | 0.55%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.37%   |
| Ralink                                 | 2         | 0.37%   |
| Nvidia                                 | 2         | 0.37%   |
| Lenovo                                 | 2         | 0.37%   |
| JMicron Technology                     | 2         | 0.37%   |
| Ericsson Business Mobile Networks      | 2         | 0.37%   |
| ASIX Electronics                       | 2         | 0.37%   |
| Apple                                  | 2         | 0.37%   |
| ZyXEL Communications                   | 1         | 0.18%   |
| Sagem                                  | 1         | 0.18%   |
| Qualcomm                               | 1         | 0.18%   |
| Mercucys                               | 1         | 0.18%   |
| Linksys                                | 1         | 0.18%   |
| Google                                 | 1         | 0.18%   |
| DisplayLink                            | 1         | 0.18%   |
| Dell                                   | 1         | 0.18%   |
| D-Link                                 | 1         | 0.18%   |
| Belkin Components                      | 1         | 0.18%   |
| Arduino SA                             | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 14.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 5.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 3.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 2.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 14        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 1.98%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.98%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.37%   |
| Intel Wireless 7260                                               | 9         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.22%   |
| Intel Wireless 7265                                               | 8         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.91%   |
| Realtek 802.11ac NIC                                              | 6         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.91%   |
| Intel Wireless 8260                                               | 6         | 0.91%   |
| Intel Wireless 3165                                               | 6         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.61%   |
| Intel Wireless 3160                                               | 4         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 182       | 49.32%  |
| Realtek Semiconductor           | 66        | 17.89%  |
| Qualcomm Atheros                | 49        | 13.28%  |
| Broadcom                        | 24        | 6.5%    |
| MediaTek                        | 9         | 2.44%   |
| TP-Link                         | 8         | 2.17%   |
| Broadcom Limited                | 8         | 2.17%   |
| Ralink Technology               | 4         | 1.08%   |
| Qualcomm Atheros Communications | 4         | 1.08%   |
| NetGear                         | 3         | 0.81%   |
| ASUSTek Computer                | 3         | 0.81%   |
| Ralink                          | 2         | 0.54%   |
| ZyXEL Communications            | 1         | 0.27%   |
| Sagem                           | 1         | 0.27%   |
| Mercucys                        | 1         | 0.27%   |
| Linksys                         | 1         | 0.27%   |
| Dell                            | 1         | 0.27%   |
| D-Link                          | 1         | 0.27%   |
| Belkin Components               | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 17        | 4.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 14        | 3.78%   |
| Intel Wireless 8265 / 8275                                     | 13        | 3.51%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 3.24%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 3.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.43%   |
| Intel Wireless 7260                                            | 9         | 2.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 2.16%   |
| Intel Wireless 7265                                            | 8         | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 2.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.62%   |
| Realtek 802.11ac NIC                                           | 6         | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.62%   |
| Intel Wireless 8260                                            | 6         | 1.62%   |
| Intel Wireless 3165                                            | 6         | 1.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.08%   |
| Intel Wireless 3160                                            | 4         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 4         | 1.08%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 151       | 54.91%  |
| Intel                                  | 58        | 21.09%  |
| Qualcomm Atheros                       | 24        | 8.73%   |
| Broadcom                               | 9         | 3.27%   |
| Samsung Electronics                    | 6         | 2.18%   |
| Xiaomi                                 | 5         | 1.82%   |
| OPPO Electronics                       | 3         | 1.09%   |
| Nvidia                                 | 2         | 0.73%   |
| MediaTek                               | 2         | 0.73%   |
| Lenovo                                 | 2         | 0.73%   |
| JMicron Technology                     | 2         | 0.73%   |
| Broadcom Limited                       | 2         | 0.73%   |
| ASIX Electronics                       | 2         | 0.73%   |
| Apple                                  | 2         | 0.73%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.36%   |
| Qualcomm                               | 1         | 0.36%   |
| Huawei Technologies                    | 1         | 0.36%   |
| Google                                 | 1         | 0.36%   |
| DisplayLink                            | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 12.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 7.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 4.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 2.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 2.15%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.08%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.08%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.72%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.72%   |
| OPPO SM8150-MTP _SN:487017FC                                      | 2         | 0.72%   |
| MediaTek TECNO SPARK 9T                                           | 2         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.72%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.36%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.36%   |
| Qualcomm Redmi Note 9 Pro                                         | 1         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 320       | 54.33%  |
| Ethernet | 260       | 44.14%  |
| Modem    | 8         | 1.36%   |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 258       | 76.56%  |
| Ethernet | 78        | 23.15%  |
| Unknown  | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 231       | 71.52%  |
| 1     | 82        | 25.39%  |
| 0     | 7         | 2.17%   |
| 3     | 3         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 262       | 80.12%  |
| Yes     | 64        | 19.57%  |
| Unknown | 1         | 0.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 130       | 49.81%  |
| Realtek Semiconductor           | 25        | 9.58%   |
| Qualcomm Atheros Communications | 25        | 9.58%   |
| Broadcom                        | 19        | 7.28%   |
| IMC Networks                    | 11        | 4.21%   |
| Lite-On Technology              | 10        | 3.83%   |
| Foxconn / Hon Hai               | 10        | 3.83%   |
| Apple                           | 9         | 3.45%   |
| Dell                            | 4         | 1.53%   |
| Cambridge Silicon Radio         | 4         | 1.53%   |
| MediaTek                        | 3         | 1.15%   |
| Toshiba                         | 2         | 0.77%   |
| Ralink                          | 2         | 0.77%   |
| TP-Link                         | 1         | 0.38%   |
| Realtek                         | 1         | 0.38%   |
| Hewlett-Packard                 | 1         | 0.38%   |
| Dynex                           | 1         | 0.38%   |
| ASUSTek Computer                | 1         | 0.38%   |
| Alps Electric                   | 1         | 0.38%   |
| Unknown                         | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 44        | 16.86%  |
| Intel AX201 Bluetooth                                                               | 34        | 13.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 25        | 9.58%   |
| Realtek Bluetooth Radio                                                             | 15        | 5.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 4.21%   |
| Intel AX200 Bluetooth                                                               | 11        | 4.21%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.68%   |
| Intel Bluetooth Device                                                              | 6         | 2.3%    |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.92%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.53%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.53%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.53%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.53%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.15%   |
| MediaTek Wireless_Device                                                            | 3         | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.15%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.15%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.15%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.15%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.15%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.15%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.77%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.77%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.77%   |
| Lite-On Wireless_Device                                                             | 2         | 0.77%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.77%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.77%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.38%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.38%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 270       | 69.23%  |
| Nvidia                | 61        | 15.64%  |
| AMD                   | 51        | 13.08%  |
| JMTek                 | 2         | 0.51%   |
| Realtek Semiconductor | 1         | 0.26%   |
| Lenovo                | 1         | 0.26%   |
| Guillemot             | 1         | 0.26%   |
| GN Netcom             | 1         | 0.26%   |
| Conexant Systems      | 1         | 0.26%   |
| Apple                 | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 39        | 8.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 6.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30        | 6.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 5.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 3.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 3.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 3.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 3.02%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 3.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 2.81%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.59%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 2.16%   |
| AMD FCH Azalia Controller                                                  | 10        | 2.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.51%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.3%    |
| Nvidia Audio device                                                        | 6         | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.86%   |
| AMD High Definition Audio Controller                                       | 4         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 75        | 28.74%  |
| Micron Technology   | 49        | 18.77%  |
| SK hynix            | 48        | 18.39%  |
| Crucial             | 18        | 6.9%    |
| Kingston            | 14        | 5.36%   |
| Unknown             | 9         | 3.45%   |
| Ramaxel Technology  | 8         | 3.07%   |
| Elpida              | 8         | 3.07%   |
| Unknown (ABCD)      | 5         | 1.92%   |
| Nanya Technology    | 5         | 1.92%   |
| A-DATA Technology   | 5         | 1.92%   |
| Corsair             | 3         | 1.15%   |
| Transcend           | 2         | 0.77%   |
| Team                | 2         | 0.77%   |
| Smart               | 2         | 0.77%   |
| G.Skill             | 2         | 0.77%   |
| Timetec             | 1         | 0.38%   |
| Teikon              | 1         | 0.38%   |
| Saikano             | 1         | 0.38%   |
| PNY                 | 1         | 0.38%   |
| fef5                | 1         | 0.38%   |
| ChangXin Memory     | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.21%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.47%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.1%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.1%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.1%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.1%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.1%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.74%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM 1334MT/s                   | 2         | 0.74%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.74%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.74%   |
| Samsung RAM M4 70T2953CZ3-CE6 1024MB SODIMM DDR2 667MT/s         | 2         | 0.74%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.74%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 2         | 0.74%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.74%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 0.74%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.74%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.74%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 101       | 45.7%   |
| DDR3    | 78        | 35.29%  |
| LPDDR4  | 15        | 6.79%   |
| LPDDR3  | 10        | 4.52%   |
| DDR2    | 5         | 2.26%   |
| DDR5    | 4         | 1.81%   |
| LPDDR5  | 3         | 1.36%   |
| Unknown | 3         | 1.36%   |
| SDRAM   | 1         | 0.45%   |
| DDR     | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 194       | 88.18%  |
| Row Of Chips | 23        | 10.45%  |
| Unknown      | 2         | 0.91%   |
| Chip         | 1         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 91        | 38.56%  |
| 4096  | 77        | 32.63%  |
| 16384 | 33        | 13.98%  |
| 2048  | 20        | 8.47%   |
| 1024  | 10        | 4.24%   |
| 32768 | 5         | 2.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 52        | 21.76%  |
| 2667    | 51        | 21.34%  |
| 3200    | 43        | 17.99%  |
| 2400    | 20        | 8.37%   |
| 1334    | 17        | 7.11%   |
| 2133    | 11        | 4.6%    |
| 1333    | 8         | 3.35%   |
| 4800    | 5         | 2.09%   |
| 1867    | 5         | 2.09%   |
| 1067    | 4         | 1.67%   |
| 6400    | 3         | 1.26%   |
| 3266    | 3         | 1.26%   |
| 1066    | 3         | 1.26%   |
| 667     | 3         | 1.26%   |
| 4267    | 2         | 0.84%   |
| 3733    | 2         | 0.84%   |
| Unknown | 2         | 0.84%   |
| 8400    | 1         | 0.42%   |
| 2048    | 1         | 0.42%   |
| 975     | 1         | 0.42%   |
| 800     | 1         | 0.42%   |
| 533     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 78        | 27.18%  |
| IMC Networks                           | 34        | 11.85%  |
| Microdia                               | 23        | 8.01%   |
| Sunplus Innovation Technology          | 18        | 6.27%   |
| Realtek Semiconductor                  | 18        | 6.27%   |
| Quanta                                 | 16        | 5.57%   |
| Bison Electronics                      | 14        | 4.88%   |
| Acer                                   | 14        | 4.88%   |
| Apple                                  | 10        | 3.48%   |
| Syntek                                 | 8         | 2.79%   |
| Luxvisions Innotech Limited            | 8         | 2.79%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.79%   |
| Suyin                                  | 5         | 1.74%   |
| Ricoh                                  | 5         | 1.74%   |
| Samsung Electronics                    | 4         | 1.39%   |
| Sonix Technology                       | 3         | 1.05%   |
| Silicon Motion                         | 3         | 1.05%   |
| Lite-On Technology                     | 3         | 1.05%   |
| Alcor Micro                            | 3         | 1.05%   |
| Primax Electronics                     | 2         | 0.7%    |
| Importek                               | 2         | 0.7%    |
| icSpring                               | 2         | 0.7%    |
| USB Camera CS                          | 1         | 0.35%   |
| Tobii Technology AB                    | 1         | 0.35%   |
| Logitech                               | 1         | 0.35%   |
| LG Electronics                         | 1         | 0.35%   |
| Goertek Electronics                    | 1         | 0.35%   |
| ALi                                    | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 16        | 5.57%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 3.83%   |
| IMC Networks Integrated Camera                      | 9         | 3.14%   |
| Realtek Integrated_Webcam_HD                        | 8         | 2.79%   |
| Acer HD Webcam                                      | 8         | 2.79%   |
| Syntek Integrated Camera                            | 7         | 2.44%   |
| Quanta HD User Facing                               | 6         | 2.09%   |
| Microdia Integrated_Webcam_HD                       | 6         | 2.09%   |
| Chicony HP Truevision HD                            | 6         | 2.09%   |
| Chicony HD Webcam                                   | 6         | 2.09%   |
| Chicony HD User Facing                              | 6         | 2.09%   |
| Chicony USB2.0 Camera                               | 5         | 1.74%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.39%   |
| Realtek Integrated Webcam HD                        | 4         | 1.39%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.39%   |
| Bison SunplusIT Integrated Camera                   | 4         | 1.39%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.05%   |
| Microdia Webcam Vitade AF                           | 3         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD                | 3         | 1.05%   |
| Microdia Integrated Webcam                          | 3         | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.05%   |
| IMC Networks HD Camera                              | 3         | 1.05%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.05%   |
| Chicony HP HD Camera                                | 3         | 1.05%   |
| Bison EasyCamera                                    | 3         | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 3         | 1.05%   |
| Apple FaceTime HD Camera                            | 3         | 1.05%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.05%   |
| Acer Integrated Camera                              | 3         | 1.05%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 0.7%    |
| Sunplus Laptop Integrated Webcam FHD                | 2         | 0.7%    |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.7%    |
| Sunplus HD WebCam                                   | 2         | 0.7%    |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 0.7%    |
| Realtek Integrated Webcam                           | 2         | 0.7%    |
| Quanta VGA WebCam                                   | 2         | 0.7%    |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.7%    |
| Microdia PC Microscope camera                       | 2         | 0.7%    |
| Microdia Integrated Webcam HD                       | 2         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 36.36%  |
| Synaptics                  | 17        | 30.91%  |
| Shenzhen Goodix Technology | 7         | 12.73%  |
| Elan Microelectronics      | 5         | 9.09%   |
| Upek                       | 2         | 3.64%   |
| LighTuning Technology      | 2         | 3.64%   |
| AuthenTec                  | 2         | 3.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 10.91%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 10.91%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 7.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.45%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 5.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 5.45%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.45%   |
| Validity Sensors VFS491                                                    | 2         | 3.64%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.64%   |
| Synaptics UWP WBDI Device                                                  | 2         | 3.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.64%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Synaptics  WBDI                                                            | 1         | 1.82%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.82%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.82%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 59.09%  |
| Alcor Micro | 6         | 27.27%  |
| Upek        | 1         | 4.55%   |
| OmniKey     | 1         | 4.55%   |
| O2 Micro    | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 31.82%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.64%  |
| Broadcom 5880                                                                | 3         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.55%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 196       | 59.76%  |
| 1     | 102       | 31.1%   |
| 2     | 28        | 8.54%   |
| 3     | 2         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 56        | 35.44%  |
| Graphics card         | 24        | 15.19%  |
| Chipcard              | 21        | 13.29%  |
| Net/wireless          | 18        | 11.39%  |
| Multimedia controller | 14        | 8.86%   |
| Camera                | 7         | 4.43%   |
| Storage               | 6         | 3.8%    |
| Net/ethernet          | 4         | 2.53%   |
| Network               | 3         | 1.9%    |
| Bluetooth             | 3         | 1.9%    |
| Modem                 | 1         | 0.63%   |
| Card reader           | 1         | 0.63%   |

