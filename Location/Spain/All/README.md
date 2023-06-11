Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 7708

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-B0621 100                | All in one  | [aa67f8201a](https://linux-hardware.org/?probe=aa67f8201a) | Jun 10, 2023 |
| Beelink       | Gemini X                    | Notebook    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | Notebook    | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [264c056bf2](https://linux-hardware.org/?probe=264c056bf2) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | Boston                      | Desktop     | [cc58f8cdf3](https://linux-hardware.org/?probe=cc58f8cdf3) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 3397                        | Desktop     | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| MSI           | GE66 Raider 10UE            | Notebook    | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Beelink       | Gemini X                    | Notebook    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| HP            | 3397                        | Desktop     | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| HP            | 3396                        | Desktop     | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | Notebook    | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Intel         | X99 V102                    | Desktop     | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [64c321d474](https://linux-hardware.org/?probe=64c321d474) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [9a0f40789b](https://linux-hardware.org/?probe=9a0f40789b) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | Notebook    | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | Notebook    | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| Teclast       | X4                          | Tablet      | [2392aa748a](https://linux-hardware.org/?probe=2392aa748a) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [50f664d550](https://linux-hardware.org/?probe=50f664d550) | Jun 01, 2023 |
| MSI           | H81M-E33                    | Desktop     | [eb2a33204c](https://linux-hardware.org/?probe=eb2a33204c) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [ecc39bf44b](https://linux-hardware.org/?probe=ecc39bf44b) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4fbe93ecc5](https://linux-hardware.org/?probe=4fbe93ecc5) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [15c734c665](https://linux-hardware.org/?probe=15c734c665) | May 29, 2023 |
| HP            | 2820h                       | Desktop     | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3e43db6ab5](https://linux-hardware.org/?probe=3e43db6ab5) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [d44b92320b](https://linux-hardware.org/?probe=d44b92320b) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [701c6c3410](https://linux-hardware.org/?probe=701c6c3410) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [21ee588e1c](https://linux-hardware.org/?probe=21ee588e1c) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [5d462a687d](https://linux-hardware.org/?probe=5d462a687d) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Teclast       | X4                          | Tablet      | [9dc0b8fa7b](https://linux-hardware.org/?probe=9dc0b8fa7b) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [89e6088290](https://linux-hardware.org/?probe=89e6088290) | May 20, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | Notebook    | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | Notebook    | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | Notebook    | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | Notebook    | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| Medion        | MS-7675                     | Desktop     | [4890b5bbf9](https://linux-hardware.org/?probe=4890b5bbf9) | May 16, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9cb65eaaf2](https://linux-hardware.org/?probe=9cb65eaaf2) | May 15, 2023 |
| MSI           | H170A PC MATE               | Desktop     | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [975de0cf0d](https://linux-hardware.org/?probe=975de0cf0d) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [8e867c3cce](https://linux-hardware.org/?probe=8e867c3cce) | May 14, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | Notebook    | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [bbb7537d59](https://linux-hardware.org/?probe=bbb7537d59) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [f9ccb88980](https://linux-hardware.org/?probe=f9ccb88980) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | Desktop     | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| Medion        | MS-7848                     | Desktop     | [e5e1e75529](https://linux-hardware.org/?probe=e5e1e75529) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [30036be67b](https://linux-hardware.org/?probe=30036be67b) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [b93ef808c5](https://linux-hardware.org/?probe=b93ef808c5) | May 10, 2023 |
| Samsung       | X420/X520                   | Notebook    | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [d4846b3b14](https://linux-hardware.org/?probe=d4846b3b14) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 304Ah                       | Desktop     | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [83741a7884](https://linux-hardware.org/?probe=83741a7884) | May 09, 2023 |
| ASRock        | A55M-DGS                    | Desktop     | [528232ffb1](https://linux-hardware.org/?probe=528232ffb1) | May 09, 2023 |
| HP            | 630                         | Notebook    | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | Notebook    | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b76481d6a9](https://linux-hardware.org/?probe=b76481d6a9) | May 09, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [228e778389](https://linux-hardware.org/?probe=228e778389) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Intel         | NUC11TNBi5 M61235-402       | Mini pc     | [b85a510a03](https://linux-hardware.org/?probe=b85a510a03) | May 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9e3f14cf8d](https://linux-hardware.org/?probe=9e3f14cf8d) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [9369acb33c](https://linux-hardware.org/?probe=9369acb33c) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| eMachines     | eME728                      | Notebook    | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [421f2de1c3](https://linux-hardware.org/?probe=421f2de1c3) | May 05, 2023 |
| HP            | 630                         | Notebook    | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | Notebook    | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7dabc9fc5c](https://linux-hardware.org/?probe=7dabc9fc5c) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [18895a52d4](https://linux-hardware.org/?probe=18895a52d4) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [1f8f3c96a5](https://linux-hardware.org/?probe=1f8f3c96a5) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [43f32e7ed8](https://linux-hardware.org/?probe=43f32e7ed8) | May 05, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [e146c82a49](https://linux-hardware.org/?probe=e146c82a49) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [caf5cbc634](https://linux-hardware.org/?probe=caf5cbc634) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [ad56dc6f51](https://linux-hardware.org/?probe=ad56dc6f51) | May 03, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [2f16b0a530](https://linux-hardware.org/?probe=2f16b0a530) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c2dcdb892d](https://linux-hardware.org/?probe=c2dcdb892d) | May 01, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| HP            | 1495                        | Desktop     | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [88d774df0d](https://linux-hardware.org/?probe=88d774df0d) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [87d4b56fee](https://linux-hardware.org/?probe=87d4b56fee) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [a418b302b9](https://linux-hardware.org/?probe=a418b302b9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [00fe705be0](https://linux-hardware.org/?probe=00fe705be0) | Apr 27, 2023 |
| Lenovo        | 318D                        | All in one  | [8cf49b59a5](https://linux-hardware.org/?probe=8cf49b59a5) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [6d981e0d7c](https://linux-hardware.org/?probe=6d981e0d7c) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2e4cd9799b](https://linux-hardware.org/?probe=2e4cd9799b) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | Notebook    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [7609d632a4](https://linux-hardware.org/?probe=7609d632a4) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| Intel         | NUC7i7DNB J83500-206        | Mini pc     | [b00fa62f7c](https://linux-hardware.org/?probe=b00fa62f7c) | Apr 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | Notebook    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Shuttle       | FG45 V10                    | Desktop     | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [e76fb532be](https://linux-hardware.org/?probe=e76fb532be) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [3193403ef5](https://linux-hardware.org/?probe=3193403ef5) | Apr 19, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [80ee2192b6](https://linux-hardware.org/?probe=80ee2192b6) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [8858427eed](https://linux-hardware.org/?probe=8858427eed) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d076bcd8a5](https://linux-hardware.org/?probe=d076bcd8a5) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [8c450d2469](https://linux-hardware.org/?probe=8c450d2469) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [d5212d6298](https://linux-hardware.org/?probe=d5212d6298) | Apr 13, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | Notebook    | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0ba5f3a06e](https://linux-hardware.org/?probe=0ba5f3a06e) | Apr 12, 2023 |
| HP            | 3396                        | Desktop     | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1589                        | Desktop     | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | Notebook    | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Gigabyte      | B75-D3V                     | Desktop     | [fe025c9491](https://linux-hardware.org/?probe=fe025c9491) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | 1998                        | Desktop     | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| AMI           | Intel                       | Desktop     | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| Dell          | Latitude E5550              | Notebook    | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| HP            | 1998                        | Desktop     | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Packard Be... | IMEDIA S2870 V1.0           | Desktop     | [61e1ab6733](https://linux-hardware.org/?probe=61e1ab6733) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| Dell          | Latitude E4200              | Notebook    | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| HP            | 1998                        | Desktop     | [4830678f31](https://linux-hardware.org/?probe=4830678f31) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | VM42                        | Desktop     | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [0a39d6faec](https://linux-hardware.org/?probe=0a39d6faec) | Apr 04, 2023 |
| Medion        | E2221T MD61083              | Convertible | [daa63988bd](https://linux-hardware.org/?probe=daa63988bd) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [151ffca106](https://linux-hardware.org/?probe=151ffca106) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [fb78fdb60c](https://linux-hardware.org/?probe=fb78fdb60c) | Apr 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Google        | Snappy                      | Notebook    | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | Notebook    | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c767575f27](https://linux-hardware.org/?probe=c767575f27) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [bb72de54b6](https://linux-hardware.org/?probe=bb72de54b6) | Mar 31, 2023 |
| HP            | 1998                        | Desktop     | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ed35fbea6c](https://linux-hardware.org/?probe=ed35fbea6c) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Primux Tec... | A173                        | All in one  | [f31f5f63b9](https://linux-hardware.org/?probe=f31f5f63b9) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| Primux Tec... | A173                        | All in one  | [95e3fd6b4b](https://linux-hardware.org/?probe=95e3fd6b4b) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [307a8bce3e](https://linux-hardware.org/?probe=307a8bce3e) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [b924b0ff06](https://linux-hardware.org/?probe=b924b0ff06) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | Notebook    | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | Notebook    | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| IP3 Tech      | GB3B                        | Mini pc     | [58b3789af3](https://linux-hardware.org/?probe=58b3789af3) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [6a3fedcc68](https://linux-hardware.org/?probe=6a3fedcc68) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | Notebook    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [8a0cc5a4cb](https://linux-hardware.org/?probe=8a0cc5a4cb) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | Notebook    | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| HP            | 1790                        | Desktop     | [1a468c1b1c](https://linux-hardware.org/?probe=1a468c1b1c) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [81273bd2b0](https://linux-hardware.org/?probe=81273bd2b0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2db2fb4a5a](https://linux-hardware.org/?probe=2db2fb4a5a) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [79cbdbc9c1](https://linux-hardware.org/?probe=79cbdbc9c1) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fc5894dcb4](https://linux-hardware.org/?probe=fc5894dcb4) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| ASUSTek       | PB60                        | Desktop     | [ec438486aa](https://linux-hardware.org/?probe=ec438486aa) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [c2bab115eb](https://linux-hardware.org/?probe=c2bab115eb) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [aab84f14ed](https://linux-hardware.org/?probe=aab84f14ed) | Mar 21, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [deaf7b9049](https://linux-hardware.org/?probe=deaf7b9049) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| HP            | 250 G4                      | Notebook    | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Supermicro    | X10SRL-F                    | Server      | [96e896465a](https://linux-hardware.org/?probe=96e896465a) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | Notebook    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [09fac43b8e](https://linux-hardware.org/?probe=09fac43b8e) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c94efea21b](https://linux-hardware.org/?probe=c94efea21b) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [afd7547cd1](https://linux-hardware.org/?probe=afd7547cd1) | Mar 16, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| Acer          | FIH57                       | Desktop     | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| Intel         | Unknown                     | Desktop     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | Notebook    | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [c436834b30](https://linux-hardware.org/?probe=c436834b30) | Mar 14, 2023 |
| ZOTAC         | ZBOX-ID41                   | Mini pc     | [620812fe84](https://linux-hardware.org/?probe=620812fe84) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cf5cbabe11](https://linux-hardware.org/?probe=cf5cbabe11) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| MSI           | MS-B1831                    | Desktop     | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [86a3944105](https://linux-hardware.org/?probe=86a3944105) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [96c3aadd1e](https://linux-hardware.org/?probe=96c3aadd1e) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [18134c0dc1](https://linux-hardware.org/?probe=18134c0dc1) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [572cded7f3](https://linux-hardware.org/?probe=572cded7f3) | Mar 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [5df81d1297](https://linux-hardware.org/?probe=5df81d1297) | Mar 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a40a70a964](https://linux-hardware.org/?probe=a40a70a964) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [946f48cdf6](https://linux-hardware.org/?probe=946f48cdf6) | Mar 09, 2023 |
| FriendlyEl... | NanoPC-T4                   | Soc         | [901194d1e1](https://linux-hardware.org/?probe=901194d1e1) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | Notebook    | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | Desktop     | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7c17068a98](https://linux-hardware.org/?probe=7c17068a98) | Mar 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [6552e8b371](https://linux-hardware.org/?probe=6552e8b371) | Mar 07, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [4e2cd40175](https://linux-hardware.org/?probe=4e2cd40175) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| HP            | 2B0A                        | All in one  | [35f88e8f33](https://linux-hardware.org/?probe=35f88e8f33) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | Notebook    | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | Notebook    | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| HP            | 87A4 10100                  | All in one  | [6b92aede76](https://linux-hardware.org/?probe=6b92aede76) | Mar 05, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c6bb0ba4a6](https://linux-hardware.org/?probe=c6bb0ba4a6) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f4cf2185ea](https://linux-hardware.org/?probe=f4cf2185ea) | Mar 04, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Intel         | powered classmate PC        | Notebook    | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49462bd855](https://linux-hardware.org/?probe=49462bd855) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c7cee84058](https://linux-hardware.org/?probe=c7cee84058) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [5033b7233d](https://linux-hardware.org/?probe=5033b7233d) | Mar 03, 2023 |
| Chuwi         | UBook                       | Tablet      | [6cbfc99f43](https://linux-hardware.org/?probe=6cbfc99f43) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | Notebook    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [0a38248462](https://linux-hardware.org/?probe=0a38248462) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| ASRock        | Q1900M Pro3                 | Desktop     | [ef9e90045e](https://linux-hardware.org/?probe=ef9e90045e) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [84a1a2c71e](https://linux-hardware.org/?probe=84a1a2c71e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | Notebook    | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [72d16085b5](https://linux-hardware.org/?probe=72d16085b5) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f03ce01ac3](https://linux-hardware.org/?probe=f03ce01ac3) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [24952b3b19](https://linux-hardware.org/?probe=24952b3b19) | Feb 27, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [d3e84076c7](https://linux-hardware.org/?probe=d3e84076c7) | Feb 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc7b5cb76e](https://linux-hardware.org/?probe=dc7b5cb76e) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | Notebook    | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | Notebook    | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | Notebook    | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3c27f298a3](https://linux-hardware.org/?probe=3c27f298a3) | Feb 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d8bafec2da](https://linux-hardware.org/?probe=d8bafec2da) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [804306660e](https://linux-hardware.org/?probe=804306660e) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | Notebook    | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| Acer          | H57M01                      | Desktop     | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [3f26c5e55c](https://linux-hardware.org/?probe=3f26c5e55c) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | Notebook    | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | 371C No DPK                 | All in one  | [02248f5982](https://linux-hardware.org/?probe=02248f5982) | Feb 16, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [5d03d010f4](https://linux-hardware.org/?probe=5d03d010f4) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | Notebook    | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Intel         | X79M-S                      | Desktop     | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e5b971a4b0](https://linux-hardware.org/?probe=e5b971a4b0) | Feb 14, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [3f40aab3d2](https://linux-hardware.org/?probe=3f40aab3d2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4211a6a7f4](https://linux-hardware.org/?probe=4211a6a7f4) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f3e396ccc3](https://linux-hardware.org/?probe=f3e396ccc3) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | Notebook    | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [0bd59541f9](https://linux-hardware.org/?probe=0bd59541f9) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | Notebook    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Lenovo        | 3741 NOK                    | Desktop     | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Unknown       | Intel X79                   | Desktop     | [2ad659fd7a](https://linux-hardware.org/?probe=2ad659fd7a) | Feb 06, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | Desktop     | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bede5aa93c](https://linux-hardware.org/?probe=bede5aa93c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | Notebook    | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | Notebook    | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X8DTL                       | Server      | [a3be5cdf41](https://linux-hardware.org/?probe=a3be5cdf41) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [0bd8186d9e](https://linux-hardware.org/?probe=0bd8186d9e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | Notebook    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | 805D                        | Desktop     | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | Notebook    | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [838de293f2](https://linux-hardware.org/?probe=838de293f2) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | Desktop     | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | Notebook    | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| HP            | G62                         | Notebook    | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | Notebook    | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | Notebook    | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | Notebook    | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [854a69817d](https://linux-hardware.org/?probe=854a69817d) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | Desktop     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| MSI           | MS-7383                     | Desktop     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | Desktop     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | Notebook    | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b2aecb083b](https://linux-hardware.org/?probe=b2aecb083b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [73779874bd](https://linux-hardware.org/?probe=73779874bd) | Jan 23, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [39f5980c8d](https://linux-hardware.org/?probe=39f5980c8d) | Jan 22, 2023 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [70bd257f2c](https://linux-hardware.org/?probe=70bd257f2c) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [05c0d355e1](https://linux-hardware.org/?probe=05c0d355e1) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | Notebook    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| AZW           | U59                         | Desktop     | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| MSI           | H170 GAMING M3              | Desktop     | [2fe05693b8](https://linux-hardware.org/?probe=2fe05693b8) | Jan 20, 2023 |
| Toshiba       | NB520                       | Notebook    | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [26e47819f8](https://linux-hardware.org/?probe=26e47819f8) | Jan 18, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [bb86adb1ed](https://linux-hardware.org/?probe=bb86adb1ed) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [4d510de3d8](https://linux-hardware.org/?probe=4d510de3d8) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6b721444d5](https://linux-hardware.org/?probe=6b721444d5) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [8b665c7b84](https://linux-hardware.org/?probe=8b665c7b84) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| Eii           | GB01                        | Desktop     | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [407f5b7997](https://linux-hardware.org/?probe=407f5b7997) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | Desktop     | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | Notebook    | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [be72db11da](https://linux-hardware.org/?probe=be72db11da) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [92f9f48219](https://linux-hardware.org/?probe=92f9f48219) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | Notebook    | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | Notebook    | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [af87fe7cb0](https://linux-hardware.org/?probe=af87fe7cb0) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| HP            | 8433 11                     | Desktop     | [bc44066299](https://linux-hardware.org/?probe=bc44066299) | Jan 13, 2023 |
| HP            | 212A                        | Desktop     | [92f32467ec](https://linux-hardware.org/?probe=92f32467ec) | Jan 13, 2023 |
| eMachines     | E725                        | Notebook    | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| Biostar       | B250MHC                     | Desktop     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0402d5609b](https://linux-hardware.org/?probe=0402d5609b) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [287fab2142](https://linux-hardware.org/?probe=287fab2142) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | Notebook    | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | Desktop     | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Dell          | 0FM586                      | Desktop     | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [64d4a8c163](https://linux-hardware.org/?probe=64d4a8c163) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | Notebook    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 727       | 12.97%  |
| Ubuntu 18.04                 | 509       | 9.08%   |
| Ubuntu 22.04                 | 255       | 4.55%   |
| Debian 11                    | 243       | 4.34%   |
| OpenMandriva 4.2             | 182       | 3.25%   |
| OpenMandriva 4.3             | 122       | 2.18%   |
| KDE neon 20.04               | 112       | 2%      |
| Zorin 16                     | 100       | 1.78%   |
| OpenMandriva 23.01           | 83        | 1.48%   |
| Manjaro                      | 83        | 1.48%   |
| Debian 10                    | 83        | 1.48%   |
| Linux Mint 20.3              | 81        | 1.45%   |
| Arch Rolling                 | 77        | 1.37%   |
| Ubuntu 20.10                 | 72        | 1.28%   |
| Linux Mint 19.3              | 71        | 1.27%   |
| Arch                         | 65        | 1.16%   |
| Linux Mint 21.1              | 63        | 1.12%   |
| Xubuntu 20.04                | 62        | 1.11%   |
| Ubuntu 19.04                 | 61        | 1.09%   |
| Ubuntu 19.10                 | 58        | 1.03%   |
| Linux Mint 20.1              | 58        | 1.03%   |
| Fedora 36                    | 55        | 0.98%   |
| Ubuntu 21.04                 | 53        | 0.95%   |
| Linux Mint 20                | 52        | 0.93%   |
| Fedora 37                    | 51        | 0.91%   |
| Ubuntu 21.10                 | 50        | 0.89%   |
| Linux Mint 20.2              | 48        | 0.86%   |
| Fedora 35                    | 47        | 0.84%   |
| Xubuntu 18.04                | 46        | 0.82%   |
| Kubuntu 20.04                | 45        | 0.8%    |
| ROSA R10                     | 43        | 0.77%   |
| Linux Mint 21                | 41        | 0.73%   |
| Zorin 15                     | 40        | 0.71%   |
| Ubuntu 22.10                 | 40        | 0.71%   |
| OpenMandriva 23.03           | 40        | 0.71%   |
| Fedora 34                    | 40        | 0.71%   |
| Pop!_OS 22.04                | 38        | 0.68%   |
| Fedora 33                    | 38        | 0.68%   |
| Pop!_OS 20.04                | 37        | 0.66%   |
| openSUSE Tumbleweed-XXXXXXXX | 34        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1819      | 34.39%  |
| Linux Mint    | 448       | 8.47%   |
| OpenMandriva  | 435       | 8.22%   |
| Debian        | 393       | 7.43%   |
| Fedora        | 266       | 5.03%   |
| Manjaro       | 195       | 3.69%   |
| KDE neon      | 149       | 2.82%   |
| Zorin         | 145       | 2.74%   |
| Arch          | 140       | 2.65%   |
| Xubuntu       | 128       | 2.42%   |
| Endless       | 123       | 2.33%   |
| Pop!_OS       | 122       | 2.31%   |
| Kubuntu       | 112       | 2.12%   |
| ROSA          | 111       | 2.1%    |
| Ubuntu MATE   | 57        | 1.08%   |
| Elementary    | 54        | 1.02%   |
| openSUSE      | 53        | 1%      |
| Gentoo        | 48        | 0.91%   |
| ArcoLinux     | 44        | 0.83%   |
| Ubuntu Unity  | 40        | 0.76%   |
| Kali          | 39        | 0.74%   |
| Lubuntu       | 31        | 0.59%   |
| BlackPanther  | 29        | 0.55%   |
| SteamOS       | 28        | 0.53%   |
| LMDE          | 23        | 0.43%   |
| EndeavourOS   | 21        | 0.4%    |
| Parrot        | 20        | 0.38%   |
| MX            | 20        | 0.38%   |
| Nobara        | 17        | 0.32%   |
| Clear Linux   | 16        | 0.3%    |
| Ubuntu Budgie | 12        | 0.23%   |
| Garuda Linux  | 10        | 0.19%   |
| CentOS        | 10        | 0.19%   |
| Reborn OS     | 8         | 0.15%   |
| RHEL          | 6         | 0.11%   |
| Deepin        | 6         | 0.11%   |
| Ubuntu Studio | 5         | 0.09%   |
| Solus         | 5         | 0.09%   |
| Peppermint    | 5         | 0.09%   |
| Slackware     | 4         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 178       | 2.91%   |
| 5.16.7-desktop-1omv4003         | 119       | 1.95%   |
| 5.4.0-42-generic                | 96        | 1.57%   |
| 6.1.1-desktop-1omv2290          | 77        | 1.26%   |
| 5.15.0-56-generic               | 64        | 1.05%   |
| 5.4.0-58-generic                | 60        | 0.98%   |
| 5.10.0-8-amd64                  | 56        | 0.92%   |
| 5.4.0-52-generic                | 49        | 0.8%    |
| 5.4.0-54-generic                | 48        | 0.78%   |
| 5.4.0-26-generic                | 47        | 0.77%   |
| 5.15.0-52-generic               | 44        | 0.72%   |
| 5.3.0-28-generic                | 42        | 0.69%   |
| 5.15.0-58-generic               | 42        | 0.69%   |
| 5.4.0-48-generic                | 39        | 0.64%   |
| 6.2.6-desktop-1omv2390          | 38        | 0.62%   |
| 5.3.0-40-generic                | 37        | 0.6%    |
| 5.11.0-27-generic               | 37        | 0.6%    |
| 5.0.0-37-generic                | 36        | 0.59%   |
| 5.4.0-29-generic                | 34        | 0.56%   |
| 5.4.0-65-generic                | 32        | 0.52%   |
| 5.3.0-46-generic                | 32        | 0.52%   |
| 5.19.0-35-generic               | 32        | 0.52%   |
| 5.13.0-30-generic               | 32        | 0.52%   |
| 5.11.0-43-generic               | 32        | 0.52%   |
| 5.15.0-60-generic               | 31        | 0.51%   |
| 5.10.0-18-amd64                 | 31        | 0.51%   |
| 5.10.0-21-amd64                 | 30        | 0.49%   |
| 5.0.0-32-generic                | 30        | 0.49%   |
| 5.4.0-72-generic                | 29        | 0.47%   |
| 5.4.0-40-generic                | 29        | 0.47%   |
| 5.15.0-48-generic               | 29        | 0.47%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.47%   |
| 5.4.0-47-generic                | 27        | 0.44%   |
| 5.4.0-37-generic                | 27        | 0.44%   |
| 5.3.0-51-generic                | 27        | 0.44%   |
| 5.19.0-38-generic               | 26        | 0.43%   |
| 5.15.0-53-generic               | 26        | 0.43%   |
| 5.13.0-39-generic               | 26        | 0.43%   |
| 5.13.0-28-generic               | 26        | 0.43%   |
| 5.11.0-41-generic               | 26        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 957       | 16.64%  |
| 5.15.0  | 462       | 8.03%   |
| 4.15.0  | 416       | 7.23%   |
| 5.10.0  | 284       | 4.94%   |
| 5.11.0  | 276       | 4.8%    |
| 5.8.0   | 266       | 4.63%   |
| 5.3.0   | 254       | 4.42%   |
| 5.13.0  | 246       | 4.28%   |
| 5.0.0   | 198       | 3.44%   |
| 5.10.14 | 180       | 3.13%   |
| 5.19.0  | 161       | 2.8%    |
| 5.16.7  | 123       | 2.14%   |
| 4.18.0  | 114       | 1.98%   |
| 6.1.1   | 87        | 1.51%   |
| 4.19.0  | 85        | 1.48%   |
| 6.2.6   | 48        | 0.83%   |
| 6.1.0   | 33        | 0.57%   |
| 4.9.60  | 33        | 0.57%   |
| 6.0.0   | 27        | 0.47%   |
| 4.18.16 | 23        | 0.4%    |
| 4.4.0   | 22        | 0.38%   |
| 5.18.0  | 21        | 0.37%   |
| 5.14.0  | 21        | 0.37%   |
| 6.2.0   | 19        | 0.33%   |
| 5.17.5  | 16        | 0.28%   |
| 6.0.12  | 15        | 0.26%   |
| 5.9.16  | 15        | 0.26%   |
| 5.9.0   | 13        | 0.23%   |
| 5.16.0  | 13        | 0.23%   |
| 6.1.11  | 12        | 0.21%   |
| 5.7.0   | 12        | 0.21%   |
| 5.3.18  | 12        | 0.21%   |
| 5.16.11 | 12        | 0.21%   |
| 5.12.4  | 12        | 0.21%   |
| 4.9.20  | 12        | 0.21%   |
| 6.1.12  | 11        | 0.19%   |
| 5.15.6  | 11        | 0.19%   |
| 6.2.12  | 10        | 0.17%   |
| 6.0.8   | 10        | 0.17%   |
| 6.0.10  | 10        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1021      | 17.98%  |
| 5.15    | 586       | 10.32%  |
| 5.10    | 544       | 9.58%   |
| 4.15    | 416       | 7.33%   |
| 5.11    | 333       | 5.87%   |
| 5.8     | 326       | 5.74%   |
| 5.13    | 284       | 5%      |
| 5.3     | 282       | 4.97%   |
| 5.19    | 221       | 3.89%   |
| 5.0     | 202       | 3.56%   |
| 6.1     | 201       | 3.54%   |
| 5.16    | 188       | 3.31%   |
| 4.18    | 138       | 2.43%   |
| 6.2     | 121       | 2.13%   |
| 6.0     | 107       | 1.88%   |
| 4.19    | 100       | 1.76%   |
| 4.9     | 80        | 1.41%   |
| 5.14    | 77        | 1.36%   |
| 5.18    | 67        | 1.18%   |
| 5.9     | 52        | 0.92%   |
| 5.6     | 51        | 0.9%    |
| 5.17    | 49        | 0.86%   |
| 5.7     | 45        | 0.79%   |
| 5.12    | 44        | 0.78%   |
| 6.3     | 27        | 0.48%   |
| 5.5     | 26        | 0.46%   |
| 4.4     | 26        | 0.46%   |
| 4.1     | 9         | 0.16%   |
| 5.2     | 8         | 0.14%   |
| 3.10    | 8         | 0.14%   |
| 5.1     | 7         | 0.12%   |
| 4.16    | 6         | 0.11%   |
| 4.20    | 4         | 0.07%   |
| 4.17    | 4         | 0.07%   |
| 4.13    | 4         | 0.07%   |
| 4.8     | 3         | 0.05%   |
| 4.14    | 3         | 0.05%   |
| 3.16    | 3         | 0.05%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4892      | 95.87%  |
| i686    | 178       | 3.49%   |
| aarch64 | 25        | 0.49%   |
| armv7l  | 7         | 0.14%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2265      | 42.2%   |
| KDE5             | 964       | 17.96%  |
| Unknown          | 654       | 12.19%  |
| XFCE             | 401       | 7.47%   |
| X-Cinnamon       | 351       | 6.54%   |
| MATE             | 161       | 3%      |
| KDE              | 158       | 2.94%   |
| Cinnamon         | 53        | 0.99%   |
| LXQt             | 52        | 0.97%   |
| Pantheon         | 50        | 0.93%   |
| KDE4             | 48        | 0.89%   |
| Unity            | 39        | 0.73%   |
| i3               | 34        | 0.63%   |
| Budgie           | 25        | 0.47%   |
| LXDE             | 20        | 0.37%   |
| Deepin           | 19        | 0.35%   |
| GNOME Flashback  | 15        | 0.28%   |
| Openbox          | 10        | 0.19%   |
| GNOME Classic    | 7         | 0.13%   |
| bspwm            | 7         | 0.13%   |
| qtile            | 4         | 0.07%   |
| DWM              | 4         | 0.07%   |
| xmonad           | 3         | 0.06%   |
| LeftWM           | 3         | 0.06%   |
| enlightenment    | 3         | 0.06%   |
| Trinity          | 2         | 0.04%   |
| icewm            | 2         | 0.04%   |
| i3-with-shmlog   | 2         | 0.04%   |
| Hyprland         | 2         | 0.04%   |
| sway             | 1         | 0.02%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| chadwm           | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4112      | 78.22%  |
| Wayland | 714       | 13.58%  |
| Unknown | 349       | 6.64%   |
| Tty     | 82        | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2742      | 51.71%  |
| SDDM    | 834       | 15.73%  |
| GDM     | 586       | 11.05%  |
| GDM3    | 487       | 9.18%   |
| LightDM | 426       | 8.03%   |
| TDM     | 150       | 2.83%   |
| KDM     | 48        | 0.91%   |
| XDM     | 13        | 0.25%   |
| LXDM    | 7         | 0.13%   |
| SLiM    | 5         | 0.09%   |
| Ly      | 5         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 3078      | 58.51%  |
| en_US          | 903       | 17.16%  |
| Unknown        | 650       | 12.36%  |
| ca_ES          | 191       | 3.63%   |
| en_GB          | 113       | 2.15%   |
| C              | 52        | 0.99%   |
| gl_ES          | 33        | 0.63%   |
| de_DE          | 33        | 0.63%   |
| eu_ES          | 25        | 0.48%   |
| fr_FR          | 20        | 0.38%   |
| ru_RU          | 19        | 0.36%   |
| it_IT          | 16        | 0.3%    |
| an_ES          | 13        | 0.25%   |
| es_MX          | 10        | 0.19%   |
| es_AR          | 9         | 0.17%   |
| pt_BR          | 7         | 0.13%   |
| ca_AD          | 7         | 0.13%   |
| en_IE          | 6         | 0.11%   |
| pl_PL          | 5         | 0.1%    |
| en_AG          | 5         | 0.1%    |
| ca_ES@valencia | 5         | 0.1%    |
| C.UTF8         | 5         | 0.1%    |
| ro_RO          | 4         | 0.08%   |
| es_ES.UTF8     | 4         | 0.08%   |
| pt_PT          | 3         | 0.06%   |
| POSIX          | 3         | 0.06%   |
| nl_NL          | 3         | 0.06%   |
| fr_BE          | 3         | 0.06%   |
| de_AT          | 3         | 0.06%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| de_CH          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2674      | 51.27%  |
| EFI  | 2542      | 48.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3999      | 76.27%  |
| Overlay  | 456       | 8.7%    |
| Btrfs    | 372       | 7.1%    |
| Unknown  | 212       | 4.04%   |
| Xfs      | 74        | 1.41%   |
| Tmpfs    | 40        | 0.76%   |
| Ext3     | 34        | 0.65%   |
| Zfs      | 27        | 0.51%   |
| Ext2     | 16        | 0.31%   |
| Reiserfs | 4         | 0.08%   |
| Jfs      | 3         | 0.06%   |
| F2fs     | 3         | 0.06%   |
| Aufs     | 3         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2904      | 55.48%  |
| GPT     | 1765      | 33.72%  |
| MBR     | 565       | 10.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4355      | 83.41%  |
| Yes       | 866       | 16.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3465      | 66.62%  |
| Yes       | 1736      | 33.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 976       | 19.13%  |
| Hewlett-Packard         | 724       | 14.19%  |
| Lenovo                  | 603       | 11.82%  |
| MSI                     | 449       | 8.8%    |
| Gigabyte Technology     | 426       | 8.35%   |
| Acer                    | 338       | 6.63%   |
| Dell                    | 315       | 6.18%   |
| ASRock                  | 124       | 2.43%   |
| Apple                   | 124       | 2.43%   |
| Toshiba                 | 111       | 2.18%   |
| Intel                   | 83        | 1.63%   |
| Unknown                 | 68        | 1.33%   |
| HUAWEI                  | 46        | 0.9%    |
| Packard Bell            | 45        | 0.88%   |
| Sony                    | 41        | 0.8%    |
| Medion                  | 40        | 0.78%   |
| Chuwi                   | 40        | 0.78%   |
| Samsung Electronics     | 32        | 0.63%   |
| Notebook                | 32        | 0.63%   |
| SLIMBOOK                | 27        | 0.53%   |
| Valve                   | 24        | 0.47%   |
| Raspberry Pi Foundation | 21        | 0.41%   |
| LG Electronics          | 21        | 0.41%   |
| Fujitsu                 | 21        | 0.41%   |
| eMachines               | 19        | 0.37%   |
| Pegatron                | 18        | 0.35%   |
| ECS                     | 17        | 0.33%   |
| BESSTAR Tech            | 17        | 0.33%   |
| Teclast                 | 15        | 0.29%   |
| AMI                     | 14        | 0.27%   |
| Fujitsu Siemens         | 13        | 0.25%   |
| Timi                    | 12        | 0.24%   |
| Foxconn                 | 12        | 0.24%   |
| Supermicro              | 11        | 0.22%   |
| AZW                     | 11        | 0.22%   |
| Huanan                  | 10        | 0.2%    |
| Microsoft               | 8         | 0.16%   |
| Dynabook                | 8         | 0.16%   |
| Clevo                   | 8         | 0.16%   |
| Shuttle                 | 7         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 94        | 1.84%   |
| ASUS All Series                            | 54        | 1.06%   |
| Valve Jupiter                              | 24        | 0.47%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.43%   |
| HP Pavilion g6                             | 22        | 0.43%   |
| HP Pavilion dv6                            | 20        | 0.39%   |
| HP Notebook                                | 19        | 0.37%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.35%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.29%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.29%   |
| Gigabyte B450M DS3H                        | 14        | 0.27%   |
| MSI MS-7C37                                | 11        | 0.22%   |
| MSI MS-7817                                | 11        | 0.22%   |
| HP G62                                     | 11        | 0.22%   |
| ASUS P5G41T-M LX                           | 11        | 0.22%   |
| RPi Raspberry Pi                           | 10        | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.2%    |
| HUAWEI BOHK-WAX9X                          | 10        | 0.2%    |
| HP Pavilion 15                             | 10        | 0.2%    |
| HP Laptop 15-da0xxx                        | 10        | 0.2%    |
| Gigabyte 970A-DS3P                         | 10        | 0.2%    |
| Dell XPS 13 7390                           | 10        | 0.2%    |
| HP Laptop 15s-eq1xxx                       | 9         | 0.18%   |
| HP Compaq Elite 8300 SFF                   | 9         | 0.18%   |
| Gigabyte H61M-DS2                          | 9         | 0.18%   |
| Gigabyte H110M-S2H                         | 9         | 0.18%   |
| Chuwi GemiBook Pro                         | 9         | 0.18%   |
| ASUS PRIME A320M-K                         | 9         | 0.18%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.16%   |
| MSI MS-7C02                                | 8         | 0.16%   |
| MSI MS-7B79                                | 8         | 0.16%   |
| HP Laptop 15-bw0xx                         | 8         | 0.16%   |
| HP EliteDesk 800 G1 SFF                    | 8         | 0.16%   |
| Gigabyte H81M-S2H                          | 8         | 0.16%   |
| Gigabyte B450 AORUS M                      | 8         | 0.16%   |
| ASUS X555LAB                               | 8         | 0.16%   |
| ASUS X550VX                                | 8         | 0.16%   |
| ASUS X540NA                                | 8         | 0.16%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.16%   |
| ASUS TUF Gaming X570-PLUS                  | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 242       | 4.74%   |
| Lenovo ThinkPad       | 196       | 3.84%   |
| HP Pavilion           | 148       | 2.9%    |
| Lenovo IdeaPad        | 138       | 2.71%   |
| HP Compaq             | 99        | 1.94%   |
| Unknown               | 94        | 1.84%   |
| Dell Latitude         | 93        | 1.82%   |
| ASUS PRIME            | 88        | 1.73%   |
| Toshiba Satellite     | 86        | 1.69%   |
| ASUS VivoBook         | 84        | 1.65%   |
| HP Laptop             | 74        | 1.45%   |
| ASUS ROG              | 70        | 1.37%   |
| ASUS TUF              | 68        | 1.33%   |
| HP EliteBook          | 66        | 1.29%   |
| Dell XPS              | 60        | 1.18%   |
| Lenovo ThinkCentre    | 59        | 1.16%   |
| ASUS All              | 54        | 1.06%   |
| Dell OptiPlex         | 51        | 1%      |
| Dell Inspiron         | 44        | 0.86%   |
| HP ProBook            | 42        | 0.82%   |
| ASUS ZenBook          | 38        | 0.74%   |
| Packard Bell EasyNote | 32        | 0.63%   |
| HP 250                | 32        | 0.63%   |
| MSI Prestige          | 27        | 0.53%   |
| Lenovo Yoga           | 27        | 0.53%   |
| MSI Modern            | 26        | 0.51%   |
| Lenovo Legion         | 26        | 0.51%   |
| HP OMEN               | 26        | 0.51%   |
| Valve Jupiter         | 24        | 0.47%   |
| Dell Precision        | 24        | 0.47%   |
| Gigabyte B450M        | 23        | 0.45%   |
| Acer TravelMate       | 22        | 0.43%   |
| RPi Raspberry         | 21        | 0.41%   |
| Gigabyte X570         | 21        | 0.41%   |
| Acer Extensa          | 21        | 0.41%   |
| ASUS ASUS             | 20        | 0.39%   |
| HP Notebook           | 19        | 0.37%   |
| HP ENVY               | 19        | 0.37%   |
| HP EliteDesk          | 19        | 0.37%   |
| Lenovo ThinkBook      | 18        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 520       | 10.19%  |
| 2019    | 483       | 9.47%   |
| 2020    | 431       | 8.45%   |
| 2014    | 350       | 6.86%   |
| 2021    | 340       | 6.67%   |
| 2013    | 318       | 6.23%   |
| 2012    | 313       | 6.14%   |
| 2017    | 311       | 6.1%    |
| 2015    | 296       | 5.8%    |
| 2011    | 291       | 5.7%    |
| 2010    | 261       | 5.12%   |
| 2009    | 247       | 4.84%   |
| 2016    | 236       | 4.63%   |
| 2008    | 233       | 4.57%   |
| 2007    | 167       | 3.27%   |
| 2022    | 147       | 2.88%   |
| 2006    | 85        | 1.67%   |
| Unknown | 32        | 0.63%   |
| 2005    | 22        | 0.43%   |
| 2004    | 7         | 0.14%   |
| 2023    | 4         | 0.08%   |
| 2003    | 3         | 0.06%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2825      | 55.38%  |
| Desktop        | 1919      | 37.62%  |
| All in one     | 92        | 1.8%    |
| Convertible    | 81        | 1.59%   |
| Mini pc        | 79        | 1.55%   |
| Tablet         | 44        | 0.86%   |
| System on chip | 29        | 0.57%   |
| Server         | 28        | 0.55%   |
| Phone          | 3         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4796      | 93.49%  |
| Enabled  | 334       | 6.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5093      | 99.84%  |
| Yes  | 8         | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1148      | 22.12%  |
| 3.01-4.0        | 1065      | 20.52%  |
| 16.01-24.0      | 1059      | 20.4%   |
| 8.01-16.0       | 952       | 18.34%  |
| 32.01-64.0      | 450       | 8.67%   |
| 1.01-2.0        | 231       | 4.45%   |
| 2.01-3.0        | 83        | 1.6%    |
| 64.01-256.0     | 72        | 1.39%   |
| 24.01-32.0      | 61        | 1.18%   |
| 0.51-1.0        | 60        | 1.16%   |
| More than 256.0 | 6         | 0.12%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2168      | 38.22%  |
| 2.01-3.0   | 1422      | 25.07%  |
| 4.01-8.0   | 729       | 12.85%  |
| 3.01-4.0   | 640       | 11.28%  |
| 0.51-1.0   | 439       | 7.74%   |
| 8.01-16.0  | 184       | 3.24%   |
| 0.01-0.5   | 64        | 1.13%   |
| 16.01-24.0 | 14        | 0.25%   |
| 24.01-32.0 | 10        | 0.18%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3138      | 59.38%  |
| 2       | 1334      | 25.24%  |
| 3       | 424       | 8.02%   |
| 4       | 187       | 3.54%   |
| 5       | 75        | 1.42%   |
| 0       | 44        | 0.83%   |
| 6       | 39        | 0.74%   |
| 7       | 16        | 0.3%    |
| 9       | 8         | 0.15%   |
| 8       | 8         | 0.15%   |
| 10      | 4         | 0.08%   |
| 12      | 2         | 0.04%   |
| 11      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 13      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3111      | 60.38%  |
| Yes       | 2041      | 39.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4407      | 86.07%  |
| No        | 713       | 13.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3858      | 75.04%  |
| No        | 1283      | 24.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2947      | 57.09%  |
| No        | 2215      | 42.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 5101      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 851       | 15.27%  |
| Barcelona                  | 569       | 10.21%  |
| Valencia                   | 194       | 3.48%   |
| Seville                    | 190       | 3.41%   |
| Zaragoza                   | 83        | 1.49%   |
| Málaga                    | 80        | 1.44%   |
| Granada                    | 73        | 1.31%   |
| Valladolid                 | 57        | 1.02%   |
| Palma                      | 55        | 0.99%   |
| Bilbao                     | 55        | 0.99%   |
| Alcobendas                 | 53        | 0.95%   |
| Vigo                       | 52        | 0.93%   |
| Sabadell                   | 52        | 0.93%   |
| Las Palmas de Gran Canaria | 49        | 0.88%   |
| Córdoba                   | 49        | 0.88%   |
| Ourense                    | 40        | 0.72%   |
| Murcia                     | 39        | 0.7%    |
| Pamplona                   | 38        | 0.68%   |
| Donostia / San Sebastian   | 35        | 0.63%   |
| Alicante                   | 35        | 0.63%   |
| A Coruña                  | 34        | 0.61%   |
| Oviedo                     | 33        | 0.59%   |
| Alcalá de Henares         | 33        | 0.59%   |
| Santiago de Compostela     | 30        | 0.54%   |
| Gijón                     | 30        | 0.54%   |
| Santa Cruz de Tenerife     | 29        | 0.52%   |
| Almería                   | 29        | 0.52%   |
| León                      | 27        | 0.48%   |
| Burgos                     | 26        | 0.47%   |
| Salamanca                  | 25        | 0.45%   |
| Mostoles                   | 25        | 0.45%   |
| Vitoria-Gasteiz            | 23        | 0.41%   |
| Barakaldo                  | 23        | 0.41%   |
| Badalona                   | 23        | 0.41%   |
| Terrassa                   | 22        | 0.39%   |
| Albacete                   | 22        | 0.39%   |
| Santander                  | 21        | 0.38%   |
| Girona                     | 21        | 0.38%   |
| Getxo                      | 20        | 0.36%   |
| Reus                       | 19        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1269      | 1951   | 16.94%  |
| WDC                         | 1035      | 1522   | 13.82%  |
| Samsung Electronics         | 983       | 1430   | 13.12%  |
| Kingston                    | 845       | 1158   | 11.28%  |
| Toshiba                     | 535       | 819    | 7.14%   |
| SanDisk                     | 407       | 548    | 5.43%   |
| Unknown                     | 285       | 366    | 3.81%   |
| Crucial                     | 284       | 403    | 3.79%   |
| Hitachi                     | 228       | 270    | 3.04%   |
| SK hynix                    | 176       | 225    | 2.35%   |
| Intel                       | 160       | 211    | 2.14%   |
| HGST                        | 127       | 159    | 1.7%    |
| Micron Technology           | 121       | 150    | 1.62%   |
| China                       | 75        | 101    | 1%      |
| Phison                      | 55        | 61     | 0.73%   |
| KIOXIA                      | 44        | 55     | 0.59%   |
| Fujitsu                     | 44        | 50     | 0.59%   |
| Micron/Crucial Technology   | 43        | 56     | 0.57%   |
| Apple                       | 43        | 57     | 0.57%   |
| Maxtor                      | 38        | 51     | 0.51%   |
| OCZ                         | 33        | 45     | 0.44%   |
| Silicon Motion              | 30        | 36     | 0.4%    |
| Phison Electronics          | 29        | 34     | 0.39%   |
| Kingston Technology Company | 25        | 32     | 0.33%   |
| JMicron Technology          | 25        | 27     | 0.33%   |
| Transcend                   | 24        | 48     | 0.32%   |
| Netac                       | 24        | 37     | 0.32%   |
| A-DATA Technology           | 24        | 33     | 0.32%   |
| KIOXIA-EXCERIA              | 23        | 31     | 0.31%   |
| Unknown                     | 22        | 24     | 0.29%   |
| KingSpec                    | 21        | 28     | 0.28%   |
| Corsair                     | 20        | 25     | 0.27%   |
| LITEON                      | 19        | 20     | 0.25%   |
| PNY                         | 17        | 27     | 0.23%   |
| KingDian                    | 17        | 21     | 0.23%   |
| USB30                       | 16        | 34     | 0.21%   |
| Emtec                       | 16        | 20     | 0.21%   |
| Intenso                     | 14        | 21     | 0.19%   |
| Patriot                     | 13        | 20     | 0.17%   |
| Teclast                     | 11        | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 274       | 3.33%   |
| Kingston SA400S37480G 480GB SSD                     | 123       | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB                      | 98        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                     | 88        | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                     | 86        | 1.04%   |
| Kingston SV300S37A120G 120GB SSD                    | 74        | 0.9%    |
| Seagate ST3500418AS 500GB                           | 64        | 0.78%   |
| Samsung SSD 860 EVO 500GB                           | 60        | 0.73%   |
| Unknown MMC Card  64GB                              | 54        | 0.66%   |
| Crucial CT500MX500SSD1 500GB                        | 51        | 0.62%   |
| Unknown MMC Card  32GB                              | 50        | 0.61%   |
| Samsung SSD 850 EVO 250GB                           | 50        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB                      | 49        | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB                      | 49        | 0.6%    |
| Samsung SSD 850 EVO 500GB                           | 47        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB                     | 46        | 0.56%   |
| Toshiba DT01ACA100 1TB                              | 45        | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB                      | 45        | 0.55%   |
| Toshiba MQ01ABD100 1TB                              | 44        | 0.53%   |
| Kingston SUV400S37240G 240GB SSD                    | 44        | 0.53%   |
| Seagate ST9500325AS 500GB                           | 43        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 40        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 0.49%   |
| SanDisk SSD PLUS 480GB                              | 39        | 0.47%   |
| HGST HTS721010A9E630 1TB                            | 39        | 0.47%   |
| Samsung NVMe SSD Drive 512GB                        | 36        | 0.44%   |
| Samsung NVMe SSD Drive 500GB                        | 36        | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 36        | 0.44%   |
| Toshiba MQ01ABF050 500GB                            | 35        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                       | 34        | 0.41%   |
| Seagate ST31000528AS 1TB                            | 34        | 0.41%   |
| Kingston SV300S37A240G 240GB SSD                    | 33        | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                        | 32        | 0.39%   |
| Unknown SD/MMC/MS PRO 64GB                          | 31        | 0.38%   |
| Unknown MMC Card  128GB                             | 31        | 0.38%   |
| Crucial CT480BX500SSD1 480GB                        | 31        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB                            | 30        | 0.36%   |
| Toshiba TR200 240GB SSD                             | 30        | 0.36%   |
| Toshiba MQ01ABD050 500GB                            | 30        | 0.36%   |
| Seagate Expansion 1TB                               | 30        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1258      | 1935   | 40.69%  |
| WDC                 | 809       | 1178   | 26.16%  |
| Toshiba             | 383       | 552    | 12.39%  |
| Hitachi             | 228       | 270    | 7.37%   |
| HGST                | 127       | 159    | 4.11%   |
| Samsung Electronics | 126       | 156    | 4.08%   |
| Fujitsu             | 43        | 49     | 1.39%   |
| Maxtor              | 33        | 44     | 1.07%   |
| Unknown             | 31        | 37     | 1%      |
| Apple               | 18        | 22     | 0.58%   |
| USB3.0              | 6         | 6      | 0.19%   |
| ASMT                | 5         | 9      | 0.16%   |
| Hewlett-Packard     | 3         | 4      | 0.1%    |
| SSK                 | 2         | 2      | 0.06%   |
| Intenso             | 2         | 3      | 0.06%   |
| Inateck             | 2         | 2      | 0.06%   |
| ASMedia             | 2         | 2      | 0.06%   |
| USB                 | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| JMicron Technology  | 1         | 1      | 0.03%   |
| IBM-207x            | 1         | 8      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| HPE                 | 1         | 2      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| External            | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 767       | 1052   | 29.96%  |
| Samsung Electronics | 443       | 622    | 17.3%   |
| Crucial             | 257       | 363    | 10.04%  |
| SanDisk             | 234       | 296    | 9.14%   |
| WDC                 | 131       | 189    | 5.12%   |
| Toshiba             | 98        | 182    | 3.83%   |
| China               | 73        | 99     | 2.85%   |
| SK hynix            | 41        | 45     | 1.6%    |
| Intel               | 38        | 55     | 1.48%   |
| Micron Technology   | 34        | 43     | 1.33%   |
| OCZ                 | 33        | 45     | 1.29%   |
| Netac               | 24        | 37     | 0.94%   |
| Transcend           | 23        | 47     | 0.9%    |
| KingSpec            | 21        | 28     | 0.82%   |
| A-DATA Technology   | 21        | 30     | 0.82%   |
| LITEON              | 18        | 18     | 0.7%    |
| Apple               | 18        | 21     | 0.7%    |
| USB30               | 16        | 34     | 0.63%   |
| KIOXIA-EXCERIA      | 16        | 20     | 0.63%   |
| KingDian            | 16        | 20     | 0.63%   |
| JMicron Technology  | 16        | 17     | 0.63%   |
| Emtec               | 14        | 17     | 0.55%   |
| Patriot             | 12        | 19     | 0.47%   |
| Intenso             | 12        | 16     | 0.47%   |
| Teclast             | 11        | 12     | 0.43%   |
| PNY                 | 11        | 21     | 0.43%   |
| FORESEE             | 10        | 14     | 0.39%   |
| Unknown             | 10        | 10     | 0.39%   |
| Corsair             | 8         | 11     | 0.31%   |
| BAITITON            | 8         | 10     | 0.31%   |
| Drevo               | 7         | 9      | 0.27%   |
| LITEONIT            | 6         | 7      | 0.23%   |
| GOODRAM             | 6         | 8      | 0.23%   |
| SABRENT             | 5         | 5      | 0.2%    |
| Maxtor              | 5         | 7      | 0.2%    |
| Dogfish             | 5         | 6      | 0.2%    |
| TCSUNBOW            | 4         | 4      | 0.16%   |
| SPCC                | 4         | 4      | 0.16%   |
| Hoodisk             | 4         | 5      | 0.16%   |
| Unknown             | 3         | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2632      | 4452   | 39.53%  |
| SSD     | 2197      | 3547   | 33%     |
| NVMe    | 1483      | 2101   | 22.27%  |
| MMC     | 262       | 345    | 3.94%   |
| Unknown | 84        | 103    | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3842      | 7774   | 65.81%  |
| NVMe | 1482      | 2096   | 25.39%  |
| MMC  | 262       | 345    | 4.49%   |
| SAS  | 252       | 333    | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3077      | 5074   | 61.81%  |
| 0.51-1.0   | 1333      | 1967   | 26.78%  |
| 1.01-2.0   | 350       | 576    | 7.03%   |
| 3.01-4.0   | 95        | 154    | 1.91%   |
| 2.01-3.0   | 82        | 130    | 1.65%   |
| 4.01-10.0  | 36        | 93     | 0.72%   |
| 10.01-20.0 | 5         | 5      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1504      | 27.65%  |
| 251-500        | 1273      | 23.4%   |
| 501-1000       | 731       | 13.44%  |
| 1-20           | 424       | 7.79%   |
| 1001-2000      | 373       | 6.86%   |
| 51-100         | 365       | 6.71%   |
| 21-50          | 228       | 4.19%   |
| More than 3000 | 218       | 4.01%   |
| 2001-3000      | 186       | 3.42%   |
| Unknown        | 138       | 2.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2190      | 38.82%  |
| 21-50          | 952       | 16.87%  |
| 101-250        | 726       | 12.87%  |
| 51-100         | 603       | 10.69%  |
| 251-500        | 424       | 7.52%   |
| 501-1000       | 292       | 5.18%   |
| 1001-2000      | 170       | 3.01%   |
| Unknown        | 138       | 2.45%   |
| More than 3000 | 85        | 1.51%   |
| 2001-3000      | 60        | 1.06%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 15        | 15     | 3%      |
| Seagate ST3500418AS 500GB           | 14        | 20     | 2.8%    |
| Kingston SV300S37A120G 120GB SSD    | 14        | 20     | 2.8%    |
| Seagate ST9500325AS 500GB           | 10        | 12     | 2%      |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 1.4%    |
| SanDisk SSD PLUS 480GB              | 7         | 9      | 1.4%    |
| Seagate ST3500320AS 500GB           | 6         | 9      | 1.2%    |
| Seagate ST31000528AS 1TB            | 6         | 7      | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 7      | 1.2%    |
| Seagate ST1000DM003-1CH162 1TB      | 6         | 7      | 1.2%    |
| HGST HTS545050A7E680 500GB          | 5         | 7      | 1%      |
| WDC WD5000AAKX-001CA0 500GB         | 4         | 6      | 0.8%    |
| WDC WD20EARX-00PASB0 2TB            | 4         | 6      | 0.8%    |
| Seagate ST9500420AS 500GB           | 4         | 4      | 0.8%    |
| Seagate ST9250827AS 250GB           | 4         | 4      | 0.8%    |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 0.8%    |
| Seagate ST1000DM003-1ER162 1TB      | 4         | 7      | 0.8%    |
| Kingston SUV400S37240G 240GB SSD    | 4         | 6      | 0.8%    |
| Kingston SA400S37480G 480GB SSD     | 4         | 7      | 0.8%    |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.8%    |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.8%    |
| Drevo X1 SSD 120GB                  | 4         | 6      | 0.8%    |
| China G521N256GB SSD                | 4         | 5      | 0.8%    |
| WDC WD5000BEVT-22ZAT0 500GB         | 3         | 3      | 0.6%    |
| WDC WD20PURZ-85GU6Y0 2TB            | 3         | 4      | 0.6%    |
| WDC WD20EZRX-00DC0B0 2TB            | 3         | 3      | 0.6%    |
| Toshiba DT01ACA100 1TB              | 3         | 5      | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 0.6%    |
| Seagate ST3250310AS 250GB           | 3         | 3      | 0.6%    |
| Seagate ST3200822A 200GB            | 3         | 3      | 0.6%    |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 4      | 0.6%    |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 4      | 0.6%    |
| Samsung Electronics HD501LJ 500GB   | 3         | 3      | 0.6%    |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.6%    |
| Fujitsu MHZ2250BH G2 250GB          | 3         | 4      | 0.6%    |
| WDC WD6400AAKS-22A7B0 640GB         | 2         | 2      | 0.4%    |
| WDC WD5000BPVT-60HXZT3 500GB        | 2         | 2      | 0.4%    |
| WDC WD5000AAKS-402AA0 500GB         | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 209    | 34.02%  |
| WDC                 | 88        | 108    | 18.03%  |
| Toshiba             | 33        | 38     | 6.76%   |
| Hitachi             | 33        | 36     | 6.76%   |
| Samsung Electronics | 32        | 35     | 6.56%   |
| Kingston            | 29        | 41     | 5.94%   |
| HGST                | 18        | 21     | 3.69%   |
| SanDisk             | 13        | 15     | 2.66%   |
| Crucial             | 11        | 13     | 2.25%   |
| Intel               | 10        | 12     | 2.05%   |
| Maxtor              | 9         | 9      | 1.84%   |
| China               | 9         | 11     | 1.84%   |
| Fujitsu             | 7         | 8      | 1.43%   |
| Drevo               | 5         | 7      | 1.02%   |
| SK hynix            | 3         | 3      | 0.61%   |
| OCZ                 | 3         | 3      | 0.61%   |
| Micron Technology   | 3         | 4      | 0.61%   |
| KingDian            | 2         | 2      | 0.41%   |
| Transcend           | 1         | 7      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| IBM                 | 1         | 1      | 0.2%    |
| Hypertec            | 1         | 1      | 0.2%    |
| HPE                 | 1         | 2      | 0.2%    |
| Dogfish             | 1         | 1      | 0.2%    |
| Corsair             | 1         | 1      | 0.2%    |
| ASMT                | 1         | 2      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |
| A-DATA Technology   | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 209    | 44.74%  |
| WDC                 | 86        | 106    | 23.18%  |
| Hitachi             | 33        | 36     | 8.89%   |
| Toshiba             | 28        | 33     | 7.55%   |
| Samsung Electronics | 19        | 21     | 5.12%   |
| HGST                | 18        | 21     | 4.85%   |
| Maxtor              | 9         | 9      | 2.43%   |
| Fujitsu             | 7         | 8      | 1.89%   |
| IBM                 | 1         | 1      | 0.27%   |
| HPE                 | 1         | 2      | 0.27%   |
| China               | 1         | 1      | 0.27%   |
| ASMT                | 1         | 2      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 346       | 450    | 75.71%  |
| SSD  | 101       | 136    | 22.1%   |
| NVMe | 10        | 11     | 2.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 15.38%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 7.69%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 7.69%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 53.85%  |
| Samsung Electronics | 3         | 4      | 23.08%  |
| WDC                 | 1         | 1      | 7.69%   |
| Toshiba             | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3211      | 6458   | 57.66%  |
| Works    | 1907      | 3479   | 34.24%  |
| Malfunc  | 438       | 597    | 7.86%   |
| Failed   | 13        | 14     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3454      | 55.25%  |
| AMD                              | 879       | 14.06%  |
| Samsung Electronics              | 486       | 7.77%   |
| SanDisk                          | 286       | 4.57%   |
| SK hynix                         | 126       | 2.02%   |
| Kingston Technology Company      | 112       | 1.79%   |
| Nvidia                           | 107       | 1.71%   |
| Phison Electronics               | 104       | 1.66%   |
| Micron Technology                | 89        | 1.42%   |
| JMicron Technology               | 87        | 1.39%   |
| ASMedia Technology               | 84        | 1.34%   |
| Micron/Crucial Technology        | 68        | 1.09%   |
| Marvell Technology Group         | 67        | 1.07%   |
| Toshiba America Info Systems     | 61        | 0.98%   |
| KIOXIA                           | 57        | 0.91%   |
| Silicon Motion                   | 39        | 0.62%   |
| VIA Technologies                 | 34        | 0.54%   |
| Silicon Integrated Systems [SiS] | 22        | 0.35%   |
| LSI Logic / Symbios Logic        | 14        | 0.22%   |
| Union Memory (Shenzhen)          | 10        | 0.16%   |
| Hewlett-Packard                  | 6         | 0.1%    |
| Apple                            | 6         | 0.1%    |
| Silicon Image                    | 5         | 0.08%   |
| Realtek Semiconductor            | 4         | 0.06%   |
| O2 Micro                         | 4         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.06%   |
| Broadcom / LSI                   | 4         | 0.06%   |
| ADATA Technology                 | 4         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Adaptec                          | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| Seagate Technology               | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 623       | 8.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 270       | 3.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 258       | 3.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 250       | 3.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 156       | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 149       | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 134       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 132       | 1.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 131       | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 124       | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 122       | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 121       | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 110       | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 102       | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 101       | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 100       | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 94        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                | 93        | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 92        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 90        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 89        | 1.21%   |
| Micron NVMe Storage Controller                                                 | 87        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 82        | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 81        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 80        | 1.09%   |
| Intel SATA Controller [RAID mode]                                              | 78        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 76        | 1.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 72        | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 72        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 71        | 0.97%   |
| Intel SSD 660P Series                                                          | 68        | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 66        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 65        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 59        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 55        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 55        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 54        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 51        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3640      | 57.01%  |
| NVMe | 1496      | 23.43%  |
| IDE  | 839       | 13.14%  |
| RAID | 390       | 6.11%   |
| SAS  | 11        | 0.17%   |
| SCSI | 9         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3944      | 77.32%  |
| AMD          | 1123      | 22.02%  |
| ARM          | 31        | 0.61%   |
| QUALCOMM     | 2         | 0.04%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 63        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 1.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 55        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 55        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 46        | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 43        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 42        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 39        | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 37        | 0.72%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 35        | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 33        | 0.65%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 32        | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 0.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 30        | 0.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 29        | 0.57%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 27        | 0.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.53%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 24        | 0.47%   |
| AMD Custom APU 0405                           | 24        | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 23        | 0.45%   |
| ARM Processor                                 | 23        | 0.45%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.45%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 22        | 0.43%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.39%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 20        | 0.39%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 20        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 968       | 18.94%  |
| Intel Core i7           | 952       | 18.62%  |
| Intel Core i3           | 407       | 7.96%   |
| Other                   | 355       | 6.94%   |
| Intel Celeron           | 321       | 6.28%   |
| AMD Ryzen 5             | 277       | 5.42%   |
| Intel Core 2 Duo        | 252       | 4.93%   |
| AMD Ryzen 7             | 244       | 4.77%   |
| Intel Atom              | 146       | 2.86%   |
| Intel Xeon              | 112       | 2.19%   |
| Intel Pentium           | 96        | 1.88%   |
| Intel Pentium Dual-Core | 85        | 1.66%   |
| Intel Core 2 Quad       | 75        | 1.47%   |
| AMD FX                  | 60        | 1.17%   |
| Intel Pentium Dual      | 53        | 1.04%   |
| Intel Core 2            | 52        | 1.02%   |
| AMD Ryzen 9             | 49        | 0.96%   |
| AMD A4                  | 49        | 0.96%   |
| AMD Ryzen 3             | 44        | 0.86%   |
| AMD A6                  | 37        | 0.72%   |
| AMD A10                 | 35        | 0.68%   |
| Intel Genuine           | 34        | 0.67%   |
| AMD A8                  | 32        | 0.63%   |
| Intel Core i9           | 30        | 0.59%   |
| Intel Pentium 4         | 25        | 0.49%   |
| AMD Athlon 64 X2        | 24        | 0.47%   |
| AMD E1                  | 22        | 0.43%   |
| AMD Athlon II X2        | 22        | 0.43%   |
| AMD Athlon              | 20        | 0.39%   |
| AMD Phenom II X4        | 15        | 0.29%   |
| AMD E                   | 14        | 0.27%   |
| AMD Ryzen 7 PRO         | 13        | 0.25%   |
| Intel Pentium D         | 10        | 0.2%    |
| AMD Phenom              | 10        | 0.2%    |
| Intel Pentium Silver    | 9         | 0.18%   |
| Intel Pentium M         | 9         | 0.18%   |
| Intel Pentium Gold      | 8         | 0.16%   |
| Intel Celeron M         | 8         | 0.16%   |
| AMD Sempron             | 8         | 0.16%   |
| AMD Ryzen Threadripper  | 8         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2082      | 40.68%  |
| 4       | 1804      | 35.25%  |
| 6       | 489       | 9.55%   |
| 8       | 368       | 7.19%   |
| 1       | 188       | 3.67%   |
| 12      | 62        | 1.21%   |
| 14      | 29        | 0.57%   |
| 10      | 27        | 0.53%   |
| 16      | 23        | 0.45%   |
| 3       | 21        | 0.41%   |
| Unknown | 14        | 0.27%   |
| 20      | 3         | 0.06%   |
| 64      | 2         | 0.04%   |
| 32      | 2         | 0.04%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5058      | 99.14%  |
| 2       | 40        | 0.78%   |
| Unknown | 4         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3202      | 62.59%  |
| 1       | 1899      | 37.12%  |
| Unknown | 14        | 0.27%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4917      | 95.83%  |
| Unknown        | 114       | 2.22%   |
| 32-bit         | 66        | 1.29%   |
| 64-bit         | 34        | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1136      | 21.43%  |
| 0x306c3    | 262       | 4.94%   |
| 0x206a7    | 238       | 4.49%   |
| 0x306a9    | 223       | 4.21%   |
| 0x1067a    | 186       | 3.51%   |
| 0x906ea    | 148       | 2.79%   |
| 0x806ea    | 124       | 2.34%   |
| 0x806c1    | 116       | 2.19%   |
| 0x506e3    | 113       | 2.13%   |
| 0x6fd      | 108       | 2.04%   |
| 0x40651    | 104       | 1.96%   |
| 0x806ec    | 103       | 1.94%   |
| 0x20655    | 97        | 1.83%   |
| 0x806e9    | 94        | 1.77%   |
| 0x406e3    | 91        | 1.72%   |
| 0x306d4    | 78        | 1.47%   |
| 0x08108109 | 78        | 1.47%   |
| 0x906e9    | 77        | 1.45%   |
| 0x30678    | 60        | 1.13%   |
| 0x10676    | 56        | 1.06%   |
| 0x6fb      | 53        | 1%      |
| 0x20652    | 51        | 0.96%   |
| 0x0a50000c | 51        | 0.96%   |
| 0x08701021 | 51        | 0.96%   |
| 0x706a1    | 47        | 0.89%   |
| 0x0800820d | 45        | 0.85%   |
| 0x406c4    | 44        | 0.83%   |
| 0x506c9    | 43        | 0.81%   |
| 0xa0652    | 42        | 0.79%   |
| 0x706e5    | 42        | 0.79%   |
| 0x06006705 | 41        | 0.77%   |
| 0x08600106 | 38        | 0.72%   |
| 0x706a8    | 36        | 0.68%   |
| 0x6f6      | 36        | 0.68%   |
| 0x106ca    | 35        | 0.66%   |
| 0x08108102 | 35        | 0.66%   |
| 0x906ed    | 33        | 0.62%   |
| 0x06000852 | 33        | 0.62%   |
| 0x010000c8 | 33        | 0.62%   |
| 0x806eb    | 32        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 794       | 15.53%  |
| Haswell          | 492       | 9.62%   |
| Penryn           | 312       | 6.1%    |
| SandyBridge      | 305       | 5.97%   |
| IvyBridge        | 272       | 5.32%   |
| Core             | 267       | 5.22%   |
| Skylake          | 253       | 4.95%   |
| Zen+             | 204       | 3.99%   |
| Zen 2            | 194       | 3.79%   |
| Westmere         | 180       | 3.52%   |
| Silvermont       | 173       | 3.38%   |
| TigerLake        | 161       | 3.15%   |
| Unknown          | 152       | 2.97%   |
| Zen 3            | 124       | 2.43%   |
| CometLake        | 114       | 2.23%   |
| Broadwell        | 111       | 2.17%   |
| Goldmont plus    | 103       | 2.01%   |
| K10              | 92        | 1.8%    |
| Zen              | 90        | 1.76%   |
| Piledriver       | 90        | 1.76%   |
| IceLake          | 77        | 1.51%   |
| Bonnell          | 73        | 1.43%   |
| Excavator        | 70        | 1.37%   |
| K8 Hammer        | 53        | 1.04%   |
| Goldmont         | 50        | 0.98%   |
| Nehalem          | 48        | 0.94%   |
| Alderlake Hybrid | 47        | 0.92%   |
| NetBurst         | 38        | 0.74%   |
| Puma             | 32        | 0.63%   |
| P6               | 30        | 0.59%   |
| Jaguar           | 27        | 0.53%   |
| Steamroller      | 26        | 0.51%   |
| Bobcat           | 23        | 0.45%   |
| Tremont          | 13        | 0.25%   |
| K10 Llano        | 11        | 0.22%   |
| Bulldozer        | 8         | 0.16%   |
| K8 & K10 hybrid  | 3         | 0.06%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2928      | 48.51%  |
| Nvidia                                       | 1764      | 29.22%  |
| AMD                                          | 1284      | 21.27%  |
| Matrox Electronics Systems                   | 22        | 0.36%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.23%   |
| VIA Technologies                             | 11        | 0.18%   |
| ASPEED Technology                            | 10        | 0.17%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 208       | 3.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 155       | 2.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 140       | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 136       | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 131       | 2.1%    |
| Intel UHD Graphics 620                                                                   | 125       | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 121       | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 106       | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 105       | 1.68%   |
| Intel HD Graphics 620                                                                    | 100       | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 100       | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 97        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 94        | 1.51%   |
| AMD Renoir                                                                               | 93        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 90        | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 89        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 83        | 1.33%   |
| Intel HD Graphics 530                                                                    | 79        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 78        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 72        | 1.15%   |
| Intel HD Graphics 630                                                                    | 72        | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 72        | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 70        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 67        | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                               | 63        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 63        | 1.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 56        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 52        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 49        | 0.79%   |
| Intel HD Graphics 500                                                                    | 48        | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 45        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 41        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 40        | 0.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2086      | 40.56%  |
| 1 x AMD                | 1008      | 19.6%   |
| 1 x Nvidia             | 978       | 19.02%  |
| Intel + Nvidia         | 671       | 13.05%  |
| Intel + AMD            | 103       | 2%      |
| AMD + Nvidia           | 100       | 1.94%   |
| 2 x AMD                | 74        | 1.44%   |
| Other                  | 37        | 0.72%   |
| 1 x Matrox             | 19        | 0.37%   |
| 2 x Nvidia             | 15        | 0.29%   |
| 1 x SiS                | 14        | 0.27%   |
| 1 x VIA                | 11        | 0.21%   |
| 2 x Intel              | 9         | 0.17%   |
| 1 x ASPEED             | 6         | 0.12%   |
| Nvidia + ASPEED        | 4         | 0.08%   |
| Nvidia + Matrox        | 3         | 0.06%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4104      | 79.14%  |
| Proprietary | 863       | 16.64%  |
| Unknown     | 219       | 4.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2817      | 53.52%  |
| 1.01-2.0   | 700       | 13.3%   |
| 0.01-0.5   | 624       | 11.86%  |
| 3.01-4.0   | 390       | 7.41%   |
| 0.51-1.0   | 375       | 7.13%   |
| 7.01-8.0   | 192       | 3.65%   |
| 5.01-6.0   | 97        | 1.84%   |
| 2.01-3.0   | 30        | 0.57%   |
| 8.01-16.0  | 30        | 0.57%   |
| 16.01-24.0 | 8         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 637       | 11.66%  |
| AU Optronics            | 562       | 10.28%  |
| Chimei Innolux          | 521       | 9.53%   |
| LG Display              | 450       | 8.23%   |
| BOE                     | 397       | 7.26%   |
| Goldstar                | 375       | 6.86%   |
| Hewlett-Packard         | 274       | 5.01%   |
| Dell                    | 225       | 4.12%   |
| BenQ                    | 219       | 4.01%   |
| Acer                    | 187       | 3.42%   |
| Ancor Communications    | 158       | 2.89%   |
| Philips                 | 150       | 2.74%   |
| AOC                     | 117       | 2.14%   |
| Apple                   | 110       | 2.01%   |
| Chi Mei Optoelectronics | 98        | 1.79%   |
| Sharp                   | 94        | 1.72%   |
| Lenovo                  | 84        | 1.54%   |
| PANDA                   | 66        | 1.21%   |
| LG Electronics          | 56        | 1.02%   |
| Sony                    | 54        | 0.99%   |
| Unknown                 | 47        | 0.86%   |
| LG Philips              | 43        | 0.79%   |
| HannStar                | 43        | 0.79%   |
| ASUSTek Computer        | 38        | 0.7%    |
| ViewSonic               | 28        | 0.51%   |
| InfoVision              | 24        | 0.44%   |
| MSI                     | 22        | 0.4%    |
| Valve                   | 15        | 0.27%   |
| CPT                     | 14        | 0.26%   |
| Eizo                    | 13        | 0.24%   |
| Toshiba                 | 11        | 0.2%    |
| OEM                     | 11        | 0.2%    |
| CSO                     | 11        | 0.2%    |
| Vestel Elektronik       | 10        | 0.18%   |
| Panasonic               | 10        | 0.18%   |
| NEC Computers           | 10        | 0.18%   |
| Fujitsu Siemens         | 10        | 0.18%   |
| ___                     | 9         | 0.16%   |
| Packard Bell            | 9         | 0.16%   |
| Mi                      | 9         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 1.15%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 38        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 31        | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 31        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 25        | 0.44%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 21        | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 20        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 16        | 0.28%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.28%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 15        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 15        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 14        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 14        | 0.25%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 14        | 0.25%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch         | 14        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 13        | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.21%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 12        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.21%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2256      | 43.33%  |
| 1366x768 (WXGA)    | 1066      | 20.47%  |
| 3840x2160 (4K)     | 242       | 4.65%   |
| 1280x1024 (SXGA)   | 224       | 4.3%    |
| 2560x1440 (QHD)    | 200       | 3.84%   |
| 1280x800 (WXGA)    | 169       | 3.25%   |
| 1680x1050 (WSXGA+) | 156       | 3%      |
| 1440x900 (WXGA+)   | 145       | 2.78%   |
| 1600x900 (HD+)     | 119       | 2.29%   |
| 1920x1200 (WUXGA)  | 91        | 1.75%   |
| Unknown            | 63        | 1.21%   |
| 2560x1080          | 59        | 1.13%   |
| 1360x768           | 48        | 0.92%   |
| 1024x600           | 43        | 0.83%   |
| 3440x1440          | 36        | 0.69%   |
| 2560x1600          | 30        | 0.58%   |
| 2160x1440          | 28        | 0.54%   |
| 1024x768 (XGA)     | 27        | 0.52%   |
| 800x1280           | 21        | 0.4%    |
| 3840x1080          | 19        | 0.36%   |
| 2880x1800          | 15        | 0.29%   |
| 1600x1200          | 14        | 0.27%   |
| 1920x540           | 13        | 0.25%   |
| 3200x1800 (QHD+)   | 8         | 0.15%   |
| 2288x1287          | 7         | 0.13%   |
| 3840x2400          | 6         | 0.12%   |
| 3200x1080          | 6         | 0.12%   |
| 1920x1280          | 5         | 0.1%    |
| 4480x1080          | 4         | 0.08%   |
| 2736x1824          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3360x1080          | 3         | 0.06%   |
| 2960x1050          | 3         | 0.06%   |
| 2944x1080          | 3         | 0.06%   |
| 2256x1504          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1400x1050          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1572      | 28.8%   |
| 13      | 413       | 7.57%   |
| 24      | 394       | 7.22%   |
| 21      | 388       | 7.11%   |
| 27      | 352       | 6.45%   |
| 23      | 308       | 5.64%   |
| Unknown | 301       | 5.51%   |
| 17      | 284       | 5.2%    |
| 14      | 283       | 5.19%   |
| 19      | 167       | 3.06%   |
| 18      | 127       | 2.33%   |
| 22      | 89        | 1.63%   |
| 34      | 84        | 1.54%   |
| 20      | 82        | 1.5%    |
| 31      | 80        | 1.47%   |
| 12      | 70        | 1.28%   |
| 11      | 56        | 1.03%   |
| 10      | 54        | 0.99%   |
| 16      | 47        | 0.86%   |
| 84      | 45        | 0.82%   |
| 25      | 27        | 0.49%   |
| 32      | 26        | 0.48%   |
| 54      | 25        | 0.46%   |
| 72      | 24        | 0.44%   |
| 26      | 24        | 0.44%   |
| 40      | 21        | 0.38%   |
| 7       | 15        | 0.27%   |
| 65      | 10        | 0.18%   |
| 28      | 8         | 0.15%   |
| 3       | 8         | 0.15%   |
| 52      | 7         | 0.13%   |
| 48      | 7         | 0.13%   |
| 46      | 7         | 0.13%   |
| 142     | 6         | 0.11%   |
| 33      | 5         | 0.09%   |
| 60      | 4         | 0.07%   |
| 36      | 4         | 0.07%   |
| 8       | 4         | 0.07%   |
| 47      | 3         | 0.05%   |
| 42      | 3         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2134      | 39.81%  |
| 501-600        | 988       | 18.43%  |
| 401-500        | 764       | 14.25%  |
| 201-300        | 425       | 7.93%   |
| Unknown        | 301       | 5.62%   |
| 351-400        | 299       | 5.58%   |
| 601-700        | 127       | 2.37%   |
| 701-800        | 114       | 2.13%   |
| 1501-2000      | 71        | 1.32%   |
| 1001-1500      | 67        | 1.25%   |
| 801-900        | 32        | 0.6%    |
| 1-100          | 23        | 0.43%   |
| More than 2000 | 6         | 0.11%   |
| 901-1000       | 5         | 0.09%   |
| 101-200        | 4         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3617      | 73.26%  |
| 16/10   | 610       | 12.36%  |
| Unknown | 255       | 5.17%   |
| 5/4     | 205       | 4.15%   |
| 21/9    | 89        | 1.8%    |
| 3/2     | 61        | 1.24%   |
| 4/3     | 58        | 1.17%   |
| 0.67    | 15        | 0.3%    |
| 6/5     | 10        | 0.2%    |
| 1.00    | 6         | 0.12%   |
| 32/9    | 5         | 0.1%    |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1575      | 29.1%   |
| 201-250        | 965       | 17.83%  |
| 81-90          | 504       | 9.31%   |
| 151-200        | 365       | 6.74%   |
| 301-350        | 363       | 6.71%   |
| Unknown        | 301       | 5.56%   |
| 141-150        | 226       | 4.18%   |
| 351-500        | 199       | 3.68%   |
| 71-80          | 194       | 3.58%   |
| More than 1000 | 132       | 2.44%   |
| 121-130        | 130       | 2.4%    |
| 251-300        | 123       | 2.27%   |
| 61-70          | 60        | 1.11%   |
| 51-60          | 56        | 1.03%   |
| 41-50          | 54        | 1%      |
| 501-1000       | 52        | 0.96%   |
| 131-140        | 35        | 0.65%   |
| 111-120        | 34        | 0.63%   |
| 1-40           | 27        | 0.5%    |
| 91-100         | 18        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1837      | 34.92%  |
| 101-120       | 1440      | 27.37%  |
| 121-160       | 1228      | 23.34%  |
| Unknown       | 301       | 5.72%   |
| 161-240       | 271       | 5.15%   |
| 1-50          | 106       | 2.01%   |
| More than 240 | 78        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4131      | 79.02%  |
| 2     | 764       | 14.61%  |
| 0     | 237       | 4.53%   |
| 3     | 89        | 1.7%    |
| 4     | 6         | 0.11%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2925      | 37.84%  |
| Intel                             | 2195      | 28.4%   |
| Qualcomm Atheros                  | 953       | 12.33%  |
| Broadcom                          | 474       | 6.13%   |
| TP-Link                           | 131       | 1.69%   |
| Ralink Technology                 | 120       | 1.55%   |
| Marvell Technology Group          | 114       | 1.47%   |
| Broadcom Limited                  | 100       | 1.29%   |
| Nvidia                            | 90        | 1.16%   |
| Ralink                            | 80        | 1.04%   |
| MediaTek                          | 71        | 0.92%   |
| Qualcomm Atheros Communications   | 42        | 0.54%   |
| Xiaomi                            | 33        | 0.43%   |
| Samsung Electronics               | 29        | 0.38%   |
| ASIX Electronics                  | 29        | 0.38%   |
| D-Link                            | 23        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 20        | 0.26%   |
| VIA Technologies                  | 18        | 0.23%   |
| D-Link System                     | 17        | 0.22%   |
| ASUSTek Computer                  | 17        | 0.22%   |
| DisplayLink                       | 16        | 0.21%   |
| Qualcomm                          | 15        | 0.19%   |
| Lenovo                            | 14        | 0.18%   |
| JMicron Technology                | 14        | 0.18%   |
| Dell                              | 14        | 0.18%   |
| Ericsson Business Mobile Networks | 13        | 0.17%   |
| Sierra Wireless                   | 12        | 0.16%   |
| Hewlett-Packard                   | 12        | 0.16%   |
| Belkin Components                 | 12        | 0.16%   |
| Microsoft                         | 10        | 0.13%   |
| Huawei Technologies               | 9         | 0.12%   |
| Edimax Technology                 | 7         | 0.09%   |
| ZyDAS                             | 6         | 0.08%   |
| NetGear                           | 5         | 0.06%   |
| Microchip Technology              | 5         | 0.06%   |
| LSI                               | 4         | 0.05%   |
| Gemtek                            | 4         | 0.05%   |
| Attansic Technology               | 4         | 0.05%   |
| Arduino SA                        | 4         | 0.05%   |
| Aquantia                          | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1982      | 22.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 316       | 3.55%   |
| Intel Wi-Fi 6 AX200                                                     | 201       | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 155       | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 138       | 1.55%   |
| Intel Wireless 8265 / 8275                                              | 125       | 1.4%    |
| Intel Wi-Fi 6 AX201                                                     | 122       | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 116       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 115       | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 1.29%   |
| Intel Wireless 7265                                                     | 108       | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 107       | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 105       | 1.18%   |
| Intel Wireless 3165                                                     | 96        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 96        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                    | 90        | 1.01%   |
| Intel I211 Gigabit Network Connection                                   | 85        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                       | 81        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 78        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 0.81%   |
| Intel Wireless 7260                                                     | 68        | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 58        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 53        | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 47        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 45        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 45        | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 45        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 45        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 45        | 0.51%   |
| Intel WiFi Link 5100                                                    | 44        | 0.49%   |
| Intel Ethernet Connection I217-LM                                       | 44        | 0.49%   |
| Intel Wireless 8260                                                     | 43        | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1647      | 40.09%  |
| Realtek Semiconductor                 | 791       | 19.26%  |
| Qualcomm Atheros                      | 735       | 17.89%  |
| Broadcom                              | 297       | 7.23%   |
| Ralink Technology                     | 120       | 2.92%   |
| TP-Link                               | 109       | 2.65%   |
| Ralink                                | 80        | 1.95%   |
| MediaTek                              | 68        | 1.66%   |
| Broadcom Limited                      | 68        | 1.66%   |
| Qualcomm Atheros Communications       | 42        | 1.02%   |
| D-Link                                | 23        | 0.56%   |
| ASUSTek Computer                      | 17        | 0.41%   |
| Sierra Wireless                       | 12        | 0.29%   |
| Belkin Components                     | 12        | 0.29%   |
| D-Link System                         | 11        | 0.27%   |
| Microsoft                             | 9         | 0.22%   |
| Dell                                  | 8         | 0.19%   |
| Edimax Technology                     | 7         | 0.17%   |
| ZyDAS                                 | 6         | 0.15%   |
| Marvell Technology Group              | 6         | 0.15%   |
| NetGear                               | 5         | 0.12%   |
| Qualcomm                              | 4         | 0.1%    |
| Hewlett-Packard                       | 4         | 0.1%    |
| Gemtek                                | 4         | 0.1%    |
| Texas Instruments                     | 3         | 0.07%   |
| Sitecom Europe                        | 2         | 0.05%   |
| Realtek                               | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| Accton Technology                     | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Standard Microsystems                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| AirTies Wireless Networks             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 201       | 4.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 138       | 3.34%   |
| Intel Wireless 8265 / 8275                                              | 125       | 3.02%   |
| Intel Wi-Fi 6 AX201                                                     | 122       | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 115       | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 115       | 2.78%   |
| Intel Wireless 7265                                                     | 108       | 2.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 2.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 107       | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 105       | 2.54%   |
| Intel Wireless 3165                                                     | 96        | 2.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 96        | 2.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 78        | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 73        | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 1.74%   |
| Intel Wireless 7260                                                     | 68        | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 58        | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 53        | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 47        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 45        | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 45        | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 45        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 45        | 1.09%   |
| Intel WiFi Link 5100                                                    | 44        | 1.06%   |
| Intel Wireless 8260                                                     | 43        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 42        | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 40        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 40        | 0.97%   |
| Intel Wireless 3160                                                     | 40        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 38        | 0.92%   |
| Realtek 802.11ac NIC                                                    | 37        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 37        | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.82%   |
| Intel Wireless-AC 9260                                                  | 34        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2587      | 56.1%   |
| Intel                                  | 996       | 21.6%   |
| Qualcomm Atheros                       | 304       | 6.59%   |
| Broadcom                               | 231       | 5.01%   |
| Marvell Technology Group               | 109       | 2.36%   |
| Nvidia                                 | 90        | 1.95%   |
| Broadcom Limited                       | 34        | 0.74%   |
| Xiaomi                                 | 32        | 0.69%   |
| ASIX Electronics                       | 29        | 0.63%   |
| TP-Link                                | 24        | 0.52%   |
| Silicon Integrated Systems [SiS]       | 20        | 0.43%   |
| Samsung Electronics                    | 19        | 0.41%   |
| VIA Technologies                       | 18        | 0.39%   |
| DisplayLink                            | 16        | 0.35%   |
| Lenovo                                 | 14        | 0.3%    |
| JMicron Technology                     | 14        | 0.3%    |
| Qualcomm                               | 11        | 0.24%   |
| D-Link System                          | 6         | 0.13%   |
| LSI                                    | 4         | 0.09%   |
| Huawei Technologies                    | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Attansic Technology                    | 4         | 0.09%   |
| Aquantia                               | 4         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| MediaTek                               | 3         | 0.07%   |
| IBM                                    | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| Davicom Semiconductor                  | 2         | 0.04%   |
| ADMtek                                 | 2         | 0.04%   |
| Accton Technology                      | 2         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| MosChip Semiconductor                  | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1982      | 42.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 6.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 155       | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 116       | 2.47%   |
| Intel Ethernet Connection (2) I219-V                              | 90        | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 85        | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.89%   |
| Intel Ethernet Controller I225-V                                  | 42        | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 40        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 37        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33        | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 30        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 26        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                              | 26        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 23        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 21        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.43%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4402      | 52.86%  |
| WiFi     | 3855      | 46.29%  |
| Modem    | 65        | 0.78%   |
| Unknown  | 6         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2920      | 54.86%  |
| Ethernet | 2402      | 45.12%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2749      | 53.64%  |
| 1     | 2158      | 42.11%  |
| 0     | 119       | 2.32%   |
| 3     | 74        | 1.44%   |
| 4     | 16        | 0.31%   |
| 5     | 5         | 0.1%    |
| 6     | 4         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4928      | 96.17%  |
| Yes  | 196       | 3.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1316      | 44.03%  |
| Realtek Semiconductor           | 349       | 11.68%  |
| Cambridge Silicon Radio         | 252       | 8.43%   |
| IMC Networks                    | 192       | 6.42%   |
| Qualcomm Atheros Communications | 162       | 5.42%   |
| Broadcom                        | 123       | 4.12%   |
| Apple                           | 122       | 4.08%   |
| Lite-On Technology              | 101       | 3.38%   |
| Foxconn / Hon Hai               | 92        | 3.08%   |
| ASUSTek Computer                | 53        | 1.77%   |
| Realtek                         | 41        | 1.37%   |
| Toshiba                         | 37        | 1.24%   |
| Dell                            | 29        | 0.97%   |
| Hewlett-Packard                 | 23        | 0.77%   |
| Ralink                          | 18        | 0.6%    |
| Alps Electric                   | 13        | 0.43%   |
| MediaTek                        | 11        | 0.37%   |
| Belkin Components               | 9         | 0.3%    |
| Integrated System Solution      | 8         | 0.27%   |
| Foxconn International           | 8         | 0.27%   |
| TP-Link                         | 7         | 0.23%   |
| Ralink Technology               | 4         | 0.13%   |
| Marvell Semiconductor           | 4         | 0.13%   |
| Edimax Technology               | 3         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.07%   |
| Roper                           | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 481       | 16.09%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 252       | 8.43%   |
| Realtek Bluetooth Radio                             | 247       | 8.26%   |
| Intel AX201 Bluetooth                               | 243       | 8.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 220       | 7.36%   |
| Intel AX200 Bluetooth                               | 194       | 6.49%   |
| IMC Networks Bluetooth Radio                        | 92        | 3.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 65        | 2.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 65        | 2.17%   |
| Apple Bluetooth Host Controller                     | 55        | 1.84%   |
| IMC Networks Bluetooth Device                       | 52        | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 46        | 1.54%   |
| Realtek Bluetooth Radio                             | 41        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 40        | 1.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 1.3%    |
| Intel AX210 Bluetooth                               | 37        | 1.24%   |
| Intel Bluetooth Device                              | 36        | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 0.97%   |
| IMC Networks Wireless_Device                        | 29        | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 29        | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 0.9%    |
| Lite-On Bluetooth Device                            | 26        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 0.67%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.6%    |
| Apple Bluetooth HCI                                 | 16        | 0.54%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.47%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 12        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 12        | 0.4%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 12        | 0.4%    |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.37%   |
| MediaTek Wireless_Device                            | 11        | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3724      | 53.89%  |
| AMD                                  | 1355      | 19.61%  |
| Nvidia                               | 1215      | 17.58%  |
| C-Media Electronics                  | 108       | 1.56%   |
| Logitech                             | 38        | 0.55%   |
| Creative Labs                        | 38        | 0.55%   |
| Texas Instruments                    | 28        | 0.41%   |
| JMTek                                | 25        | 0.36%   |
| Silicon Integrated Systems [SiS]     | 22        | 0.32%   |
| Plantronics                          | 21        | 0.3%    |
| VIA Technologies                     | 20        | 0.29%   |
| GN Netcom                            | 20        | 0.29%   |
| Kingston Technology                  | 18        | 0.26%   |
| Corsair                              | 16        | 0.23%   |
| ASUSTek Computer                     | 16        | 0.23%   |
| Lenovo                               | 15        | 0.22%   |
| Creative Technology                  | 14        | 0.2%    |
| Realtek Semiconductor                | 13        | 0.19%   |
| Focusrite-Novation                   | 13        | 0.19%   |
| SteelSeries ApS                      | 12        | 0.17%   |
| Generalplus Technology               | 11        | 0.16%   |
| Dell                                 | 8         | 0.12%   |
| DSEA A/S                             | 7         | 0.1%    |
| M-Audio                              | 6         | 0.09%   |
| Ensoniq                              | 6         | 0.09%   |
| BEHRINGER International              | 6         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.07%   |
| Micro Star International             | 5         | 0.07%   |
| Hewlett-Packard                      | 5         | 0.07%   |
| Apple                                | 5         | 0.07%   |
| Yamaha                               | 4         | 0.06%   |
| Tenx Technology                      | 4         | 0.06%   |
| Razer USA                            | 4         | 0.06%   |
| Blue Microphones                     | 4         | 0.06%   |
| XMOS                                 | 3         | 0.04%   |
| Sony                                 | 3         | 0.04%   |
| SAVITECH                             | 3         | 0.04%   |
| QinHeng Electronics                  | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |
| Guillemot                            | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 400       | 4.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 344       | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 292       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 279       | 3.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 267       | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 228       | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 218       | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 199       | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 198       | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 195       | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 169       | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 164       | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 161       | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 154       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 151       | 1.85%   |
| AMD FCH Azalia Controller                                                  | 143       | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 140       | 1.71%   |
| Intel 8 Series HD Audio Controller                                         | 137       | 1.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 137       | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 136       | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                            | 122       | 1.49%   |
| Intel 200 Series PCH HD Audio                                              | 113       | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 112       | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 109       | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 108       | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 106       | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 103       | 1.26%   |
| Intel Broadwell-U Audio Controller                                         | 102       | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 94        | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 91        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 84        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 75        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 72        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 68        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 68        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 63        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 63        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 63        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 61        | 0.75%   |
| AMD High Definition Audio Controller                                       | 56        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 661       | 22.41%  |
| SK hynix                                         | 470       | 15.94%  |
| Kingston                                         | 454       | 15.4%   |
| Unknown                                          | 311       | 10.55%  |
| Micron Technology                                | 280       | 9.49%   |
| Crucial                                          | 208       | 7.05%   |
| Corsair                                          | 135       | 4.58%   |
| G.Skill                                          | 87        | 2.95%   |
| Ramaxel Technology                               | 69        | 2.34%   |
| Unknown (ABCD)                                   | 43        | 1.46%   |
| Elpida                                           | 40        | 1.36%   |
| Nanya Technology                                 | 27        | 0.92%   |
| A-DATA Technology                                | 25        | 0.85%   |
| Silicon Power                                    | 15        | 0.51%   |
| Unknown                                          | 14        | 0.47%   |
| GOODRAM                                          | 12        | 0.41%   |
| Team                                             | 9         | 0.31%   |
| Transcend                                        | 8         | 0.27%   |
| Apacer                                           | 8         | 0.27%   |
| Unifosa                                          | 6         | 0.2%    |
| Wilk                                             | 4         | 0.14%   |
| Patriot                                          | 4         | 0.14%   |
| Kllisre                                          | 4         | 0.14%   |
| ASint Technology                                 | 4         | 0.14%   |
| Timetec                                          | 3         | 0.1%    |
| Avant                                            | 3         | 0.1%    |
| Atermiter                                        | 3         | 0.1%    |
| Unknown (AB)                                     | 2         | 0.07%   |
| Toshiba                                          | 2         | 0.07%   |
| SHARETRONIC                                      | 2         | 0.07%   |
| Qimonda                                          | 2         | 0.07%   |
| PNY                                              | 2         | 0.07%   |
| Neo Forza                                        | 2         | 0.07%   |
| Micron/Elpida                                    | 2         | 0.07%   |
| KomputerBay                                      | 2         | 0.07%   |
| Innodisk                                         | 2         | 0.07%   |
| Exceleram                                        | 2         | 0.07%   |
| Unknown (0x5846)                                 | 1         | 0.03%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.03%   |
| Unknown (0x0B45)                                 | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 33        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 28        | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 20        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.51%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 16        | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 15        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 15        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 0.44%   |
| Unknown                                                          | 14        | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.41%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 12        | 0.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.38%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 11        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.35%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 11        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1223      | 47.57%  |
| DDR3    | 812       | 31.58%  |
| DDR2    | 148       | 5.76%   |
| LPDDR4  | 107       | 4.16%   |
| SDRAM   | 78        | 3.03%   |
| Unknown | 77        | 2.99%   |
| LPDDR3  | 62        | 2.41%   |
| DDR5    | 31        | 1.21%   |
| DDR     | 18        | 0.7%    |
| LPDDR5  | 8         | 0.31%   |
| DRAM    | 7         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1510      | 58.8%   |
| DIMM         | 864       | 33.64%  |
| Row Of Chips | 178       | 6.93%   |
| Chip         | 9         | 0.35%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1073      | 38.4%   |
| 4096  | 749       | 26.81%  |
| 16384 | 409       | 14.64%  |
| 2048  | 370       | 13.24%  |
| 1024  | 119       | 4.26%   |
| 32768 | 59        | 2.11%   |
| 512   | 8         | 0.29%   |
| 65536 | 4         | 0.14%   |
| 256   | 2         | 0.07%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 513       | 18.42%  |
| 3200    | 409       | 14.69%  |
| 2667    | 409       | 14.69%  |
| 2400    | 226       | 8.11%   |
| 1333    | 182       | 6.54%   |
| 2133    | 137       | 4.92%   |
| 667     | 97        | 3.48%   |
| 1334    | 83        | 2.98%   |
| 800     | 77        | 2.76%   |
| 3600    | 67        | 2.41%   |
| 1867    | 60        | 2.15%   |
| Unknown | 59        | 2.12%   |
| 4267    | 37        | 1.33%   |
| 8400    | 34        | 1.22%   |
| 1067    | 31        | 1.11%   |
| 4800    | 25        | 0.9%    |
| 3266    | 22        | 0.79%   |
| 3533    | 21        | 0.75%   |
| 2933    | 21        | 0.75%   |
| 3400    | 20        | 0.72%   |
| 1866    | 20        | 0.72%   |
| 1066    | 20        | 0.72%   |
| 2048    | 17        | 0.61%   |
| 533     | 17        | 0.61%   |
| 3000    | 15        | 0.54%   |
| 3733    | 14        | 0.5%    |
| 4199    | 13        | 0.47%   |
| 2733    | 13        | 0.47%   |
| 2666    | 11        | 0.39%   |
| 6400    | 10        | 0.36%   |
| 2800    | 9         | 0.32%   |
| 3800    | 7         | 0.25%   |
| 3466    | 7         | 0.25%   |
| 1639    | 7         | 0.25%   |
| 4266    | 6         | 0.22%   |
| 975     | 6         | 0.22%   |
| 400     | 6         | 0.22%   |
| 1800    | 5         | 0.18%   |
| 5200    | 4         | 0.14%   |
| 3933    | 4         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 67        | 50.38%  |
| Brother Industries       | 24        | 18.05%  |
| Canon                    | 13        | 9.77%   |
| Samsung Electronics      | 9         | 6.77%   |
| Seiko Epson              | 8         | 6.02%   |
| Oki Data                 | 3         | 2.26%   |
| Dymo-CoStar              | 2         | 1.5%    |
| Ricoh                    | 1         | 0.75%   |
| Prolific Technology      | 1         | 0.75%   |
| Magic Control Technology | 1         | 0.75%   |
| Lexmark International    | 1         | 0.75%   |
| Kyocera                  | 1         | 0.75%   |
| Konica Minolta           | 1         | 0.75%   |
| Apple                    | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 3.73%   |
| Brother HL-2030 Laser Printer                   | 5         | 3.73%   |
| HP DeskJet 2600 series                          | 4         | 2.99%   |
| Canon PIXMA MG2500 Series                       | 4         | 2.99%   |
| Oki Data USB Device                             | 3         | 2.24%   |
| HP LaserJet 1020                                | 3         | 2.24%   |
| HP ENVY 5540 series                             | 3         | 2.24%   |
| HP DeskJet F2492 All-in-One                     | 3         | 2.24%   |
| HP DeskJet 2700 series                          | 3         | 2.24%   |
| HP Deskjet 1050 J410                            | 3         | 2.24%   |
| Canon LiDE 400                                  | 3         | 2.24%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.49%   |
| Samsung M2070 Series                            | 2         | 1.49%   |
| HP LaserJet 1010                                | 2         | 1.49%   |
| HP ENVY 5000 series                             | 2         | 1.49%   |
| HP ENVY 4520 series                             | 2         | 1.49%   |
| HP ENVY 4500 series                             | 2         | 1.49%   |
| HP DeskJet 5550                                 | 2         | 1.49%   |
| HP DeskJet 3630 series                          | 2         | 1.49%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.49%   |
| Brother Printer                                 | 2         | 1.49%   |
| Brother MFC-J5330DW                             | 2         | 1.49%   |
| Brother DCP-1510                                | 2         | 1.49%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.75%   |
| Seiko Epson XP-230 Series                       | 1         | 0.75%   |
| Seiko Epson XP-225 Series                       | 1         | 0.75%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.75%   |
| Seiko Epson Printer                             | 1         | 0.75%   |
| Seiko Epson L555 Series                         | 1         | 0.75%   |
| Seiko Epson L1300 Series                        | 1         | 0.75%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.75%   |
| Samsung SCX-4300 Series                         | 1         | 0.75%   |
| Samsung SCX-3400 Series                         | 1         | 0.75%   |
| Samsung SCX-3200 Series                         | 1         | 0.75%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.75%   |
| Samsung M267x 287x Series                       | 1         | 0.75%   |
| Ricoh SP 112                                    | 1         | 0.75%   |
| Prolific PL2305 Parallel Port                   | 1         | 0.75%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.75%   |
| Lexmark International B2236dw                   | 1         | 0.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 669       | 22.69%  |
| IMC Networks                           | 320       | 10.85%  |
| Microdia                               | 189       | 6.41%   |
| Realtek Semiconductor                  | 186       | 6.31%   |
| Acer                                   | 156       | 5.29%   |
| Logitech                               | 139       | 4.71%   |
| Quanta                                 | 135       | 4.58%   |
| Sunplus Innovation Technology          | 127       | 4.31%   |
| Suyin                                  | 123       | 4.17%   |
| Bison Electronics                      | 122       | 4.14%   |
| Cheng Uei Precision Industry (Foxlink) | 102       | 3.46%   |
| Syntek                                 | 85        | 2.88%   |
| Apple                                  | 84        | 2.85%   |
| Alcor Micro                            | 52        | 1.76%   |
| Lite-On Technology                     | 45        | 1.53%   |
| Luxvisions Innotech Limited            | 42        | 1.42%   |
| Ricoh                                  | 31        | 1.05%   |
| Samsung Electronics                    | 22        | 0.75%   |
| Silicon Motion                         | 21        | 0.71%   |
| Creative Technology                    | 19        | 0.64%   |
| Z-Star Microelectronics                | 17        | 0.58%   |
| Microsoft                              | 17        | 0.58%   |
| Sonix Technology                       | 16        | 0.54%   |
| Generalplus Technology                 | 14        | 0.47%   |
| GEMBIRD                                | 14        | 0.47%   |
| Lenovo                                 | 11        | 0.37%   |
| icSpring                               | 11        | 0.37%   |
| KYE Systems (Mouse Systems)            | 9         | 0.31%   |
| Importek                               | 9         | 0.31%   |
| ARC International                      | 9         | 0.31%   |
| ALi                                    | 9         | 0.31%   |
| Sunplus Technology                     | 8         | 0.27%   |
| Cubeternet                             | 8         | 0.27%   |
| Jieli Technology                       | 7         | 0.24%   |
| Intel                                  | 7         | 0.24%   |
| Genesys Logic                          | 7         | 0.24%   |
| webcam                                 | 6         | 0.2%    |
| SunplusIT                              | 6         | 0.2%    |
| Primax Electronics                     | 6         | 0.2%    |
| Trust                                  | 5         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 86        | 2.9%    |
| Chicony Integrated Camera                               | 72        | 2.43%   |
| Chicony HD Webcam                                       | 69        | 2.32%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.26%   |
| Microdia Integrated_Webcam_HD                           | 64        | 2.16%   |
| Acer HD Webcam                                          | 61        | 2.06%   |
| IMC Networks Integrated Camera                          | 52        | 1.75%   |
| Chicony USB2.0 VGA UVC WebCam                           | 43        | 1.45%   |
| Bison Integrated Camera                                 | 38        | 1.28%   |
| Apple Built-in iSight                                   | 37        | 1.25%   |
| Realtek USB Camera                                      | 35        | 1.18%   |
| Syntek Integrated Camera                                | 34        | 1.15%   |
| Realtek Integrated_Webcam_HD                            | 34        | 1.15%   |
| Logitech Webcam C270                                    | 34        | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 33        | 1.11%   |
| Quanta HP TrueVision HD Camera                          | 31        | 1.04%   |
| Chicony EasyCamera                                      | 30        | 1.01%   |
| Sunplus HD WebCam                                       | 28        | 0.94%   |
| Microdia Webcam Vitade AF                               | 27        | 0.91%   |
| Chicony USB 2.0 Camera                                  | 27        | 0.91%   |
| Acer Integrated Camera                                  | 27        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 0.88%   |
| Logitech HD Pro Webcam C920                             | 24        | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 22        | 0.74%   |
| Chicony USB2.0 Camera                                   | 22        | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                            | 21        | 0.71%   |
| Chicony HP TrueVision HD Camera                         | 21        | 0.71%   |
| Syntek EasyCamera                                       | 20        | 0.67%   |
| Apple FaceTime HD Camera (Built-in)                     | 20        | 0.67%   |
| Chicony HP Truevision HD                                | 19        | 0.64%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.61%   |
| Lite-On Integrated Camera                               | 18        | 0.61%   |
| IMC Networks ov9734_azurewave_camera                    | 18        | 0.61%   |
| Chicony VGA Webcam                                      | 18        | 0.61%   |
| Chicony Integrated Camera (1280x720@30)                 | 18        | 0.61%   |
| Chicony HP HD Camera                                    | 18        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 18        | 0.61%   |
| Realtek Lenovo EasyCamera                               | 17        | 0.57%   |
| Quanta HP Wide Vision HD Camera                         | 17        | 0.57%   |
| Alcor Micro USB 2.0 Camera                              | 17        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 128       | 30.62%  |
| Validity Sensors                   | 94        | 22.49%  |
| Shenzhen Goodix Technology         | 73        | 17.46%  |
| Elan Microelectronics              | 39        | 9.33%   |
| AuthenTec                          | 37        | 8.85%   |
| Upek                               | 26        | 6.22%   |
| LighTuning Technology              | 13        | 3.11%   |
| STMicroelectronics                 | 7         | 1.67%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 53        | 12.68%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 36        | 8.61%   |
| Elan ELAN:Fingerprint                                                      | 35        | 8.37%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 7.42%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 5.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 4.07%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 2.87%   |
| Synaptics  WBDI                                                            | 11        | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.15%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.91%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.67%   |
| AuthenTec AES1600                                                          | 7         | 1.67%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.44%   |
| Validity Sensors VFS491                                                    | 5         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.2%    |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.2%    |
| Synaptics WBDI                                                             | 5         | 1.2%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.2%    |
| AuthenTec AES2810                                                          | 5         | 1.2%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.2%    |
| Synaptics UWP WBDI Device                                                  | 4         | 0.96%   |
| Synaptics UWP WBDI                                                         | 4         | 0.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 0.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.96%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.96%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.72%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.72%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.48%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.48%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 74        | 34.91%  |
| Broadcom                  | 56        | 26.42%  |
| O2 Micro                  | 24        | 11.32%  |
| Lenovo                    | 10        | 4.72%   |
| Advanced Card Systems     | 8         | 3.77%   |
| Realtek Semiconductor     | 6         | 2.83%   |
| Chicony Electronics       | 6         | 2.83%   |
| C3PO                      | 6         | 2.83%   |
| Cherry                    | 5         | 2.36%   |
| Upek                      | 4         | 1.89%   |
| SCM Microsystems          | 3         | 1.42%   |
| Gemalto (was Gemplus)     | 3         | 1.42%   |
| OmniKey                   | 2         | 0.94%   |
| Hewlett-Packard           | 2         | 0.94%   |
| In Focus Systems          | 1         | 0.47%   |
| Fujitsu Siemens Computers | 1         | 0.47%   |
| Bit4id                    | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 33.02%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 10.85%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 9.43%   |
| Broadcom 5880                                                                | 16        | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 4.72%   |
| Broadcom 58200                                                               | 9         | 4.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 2.83%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 2.83%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 2.83%   |
| C3PO LTC31v2                                                                 | 5         | 2.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 1.89%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 1.89%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.89%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.94%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.94%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 0.94%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.94%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.47%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.47%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.47%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.47%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.47%   |
| Bit4id miniLector-s                                                          | 1         | 0.47%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.47%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3818      | 72.96%  |
| 1     | 1120      | 21.4%   |
| 2     | 244       | 4.66%   |
| 3     | 32        | 0.61%   |
| 4     | 8         | 0.15%   |
| 5     | 7         | 0.13%   |
| 6     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 436       | 25.42%  |
| Fingerprint reader       | 409       | 23.85%  |
| Net/wireless             | 258       | 15.04%  |
| Chipcard                 | 173       | 10.09%  |
| Multimedia controller    | 109       | 6.36%   |
| Camera                   | 58        | 3.38%   |
| Communication controller | 53        | 3.09%   |
| Bluetooth                | 45        | 2.62%   |
| Unassigned class         | 35        | 2.04%   |
| Storage                  | 26        | 1.52%   |
| Sound                    | 25        | 1.46%   |
| Card reader              | 22        | 1.28%   |
| Net/ethernet             | 17        | 0.99%   |
| Network                  | 14        | 0.82%   |
| Flash memory             | 10        | 0.58%   |
| Modem                    | 9         | 0.52%   |
| Dvb card                 | 7         | 0.41%   |
| Firewire controller      | 4         | 0.23%   |
| Storage/raid             | 2         | 0.12%   |
| Tv card                  | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

