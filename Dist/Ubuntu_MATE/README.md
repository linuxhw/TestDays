Ubuntu MATE - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE/Notebook/README.md).

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

Total: 2175

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite Pro L650          | Notebook    | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Dell          | Studio 1558                 | Notebook    | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | Notebook    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Extensa 2519                | Notebook    | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8a0a603eef](https://linux-hardware.org/?probe=8a0a603eef) | Jun 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [784d676a8d](https://linux-hardware.org/?probe=784d676a8d) | Jun 21, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [ac006b8cb7](https://linux-hardware.org/?probe=ac006b8cb7) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e68730cae4](https://linux-hardware.org/?probe=e68730cae4) | Jun 13, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [e8ed8e8b1e](https://linux-hardware.org/?probe=e8ed8e8b1e) | Jun 09, 2023 |
| AZW           | EQ                          | Desktop     | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| HP            | 1998                        | Desktop     | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | Notebook    | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| Unknown       | HX90                        | Desktop     | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| Dell          | Latitude E6510              | Notebook    | [731befae67](https://linux-hardware.org/?probe=731befae67) | May 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Unknown       | NF-CK804                    | Desktop     | [754a676bd7](https://linux-hardware.org/?probe=754a676bd7) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [aa0e7978c5](https://linux-hardware.org/?probe=aa0e7978c5) | May 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [34efd36999](https://linux-hardware.org/?probe=34efd36999) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [e69f8169fc](https://linux-hardware.org/?probe=e69f8169fc) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a95a3bd3a3](https://linux-hardware.org/?probe=a95a3bd3a3) | May 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | Desktop     | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [90d59ac61a](https://linux-hardware.org/?probe=90d59ac61a) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [aeabc8c63c](https://linux-hardware.org/?probe=aeabc8c63c) | May 03, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| ASRock        | H170A-X1                    | Desktop     | [a89448e417](https://linux-hardware.org/?probe=a89448e417) | Apr 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [77b462630d](https://linux-hardware.org/?probe=77b462630d) | Apr 18, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [83f752ffd8](https://linux-hardware.org/?probe=83f752ffd8) | Apr 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| MSI           | G41M-P26                    | Desktop     | [80c102169c](https://linux-hardware.org/?probe=80c102169c) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b821e02641](https://linux-hardware.org/?probe=b821e02641) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [ecefe27269](https://linux-hardware.org/?probe=ecefe27269) | Apr 13, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Google        | Chell                       | Notebook    | [64cecf4575](https://linux-hardware.org/?probe=64cecf4575) | Apr 12, 2023 |
| MSI           | G41M-P26                    | Desktop     | [5b6831f7fc](https://linux-hardware.org/?probe=5b6831f7fc) | Apr 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [707d59612f](https://linux-hardware.org/?probe=707d59612f) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [058290755b](https://linux-hardware.org/?probe=058290755b) | Apr 05, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| RCA           | W101AS23T2                  | Tablet      | [21e469a8a9](https://linux-hardware.org/?probe=21e469a8a9) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Dell          | Latitude E6320              | Notebook    | [a6a0d01947](https://linux-hardware.org/?probe=a6a0d01947) | Mar 31, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53a11e07e8](https://linux-hardware.org/?probe=53a11e07e8) | Mar 31, 2023 |
| Acer          | Aspire XC-1760              | Desktop     | [68e6aec940](https://linux-hardware.org/?probe=68e6aec940) | Mar 30, 2023 |
| MSI           | MS-AA5E 0A                  | All in one  | [36d66ad0a2](https://linux-hardware.org/?probe=36d66ad0a2) | Mar 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50387b06e7](https://linux-hardware.org/?probe=50387b06e7) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2a9ae9d859](https://linux-hardware.org/?probe=2a9ae9d859) | Mar 26, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [6b09e87ee2](https://linux-hardware.org/?probe=6b09e87ee2) | Mar 24, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | Desktop     | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ce6f515364](https://linux-hardware.org/?probe=ce6f515364) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [a5ba989714](https://linux-hardware.org/?probe=a5ba989714) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [0bb94771bc](https://linux-hardware.org/?probe=0bb94771bc) | Mar 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [74cf43f3e2](https://linux-hardware.org/?probe=74cf43f3e2) | Mar 16, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [afe4b0baa5](https://linux-hardware.org/?probe=afe4b0baa5) | Mar 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| HP            | 339A                        | Desktop     | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [4a54741fec](https://linux-hardware.org/?probe=4a54741fec) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| HP            | Presario CQ61               | Notebook    | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [3a34571e3d](https://linux-hardware.org/?probe=3a34571e3d) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [7e85150e30](https://linux-hardware.org/?probe=7e85150e30) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [dbc8fc4b0d](https://linux-hardware.org/?probe=dbc8fc4b0d) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| ASUSTek       | P5K                         | Desktop     | [1769888b2b](https://linux-hardware.org/?probe=1769888b2b) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | Desktop     | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| HP            | 85A2                        | All in one  | [c9f6d95fb2](https://linux-hardware.org/?probe=c9f6d95fb2) | Feb 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e1a9b1b0fa](https://linux-hardware.org/?probe=e1a9b1b0fa) | Feb 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [68dcf39492](https://linux-hardware.org/?probe=68dcf39492) | Feb 18, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | Notebook    | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | Notebook    | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [9c839fa75b](https://linux-hardware.org/?probe=9c839fa75b) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [fef1f72c3a](https://linux-hardware.org/?probe=fef1f72c3a) | Feb 09, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| HP            | Presario CQ56               | Notebook    | [3c6de43677](https://linux-hardware.org/?probe=3c6de43677) | Feb 05, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4644d239d7](https://linux-hardware.org/?probe=4644d239d7) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [6f95748149](https://linux-hardware.org/?probe=6f95748149) | Jan 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [eb2e4b24cc](https://linux-hardware.org/?probe=eb2e4b24cc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [9536b9eedc](https://linux-hardware.org/?probe=9536b9eedc) | Jan 22, 2023 |
| Google        | Relm                        | Notebook    | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [571389ffa0](https://linux-hardware.org/?probe=571389ffa0) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3525b1f86](https://linux-hardware.org/?probe=e3525b1f86) | Jan 21, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [91dea34a76](https://linux-hardware.org/?probe=91dea34a76) | Jan 20, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [08502cda27](https://linux-hardware.org/?probe=08502cda27) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| HP            | 1495                        | Desktop     | [3f6b7a9b73](https://linux-hardware.org/?probe=3f6b7a9b73) | Jan 19, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [e652633643](https://linux-hardware.org/?probe=e652633643) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [c2b8de2fdf](https://linux-hardware.org/?probe=c2b8de2fdf) | Jan 17, 2023 |
| Dell          | Latitude 5410               | Notebook    | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| HP            | 805A                        | Desktop     | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | Notebook    | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [aa53c5066d](https://linux-hardware.org/?probe=aa53c5066d) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | Notebook    | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [88ffbf550c](https://linux-hardware.org/?probe=88ffbf550c) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [e14b3158f3](https://linux-hardware.org/?probe=e14b3158f3) | Jan 10, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [433ba8749a](https://linux-hardware.org/?probe=433ba8749a) | Jan 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [b30f449318](https://linux-hardware.org/?probe=b30f449318) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a8fb72e94a](https://linux-hardware.org/?probe=a8fb72e94a) | Jan 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | Notebook    | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | Notebook    | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [c0bba3f9fd](https://linux-hardware.org/?probe=c0bba3f9fd) | Jan 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [cb89cf0f00](https://linux-hardware.org/?probe=cb89cf0f00) | Jan 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [73de62ce79](https://linux-hardware.org/?probe=73de62ce79) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [03ca911bb7](https://linux-hardware.org/?probe=03ca911bb7) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [13c0ee7f2d](https://linux-hardware.org/?probe=13c0ee7f2d) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [531e60d101](https://linux-hardware.org/?probe=531e60d101) | Dec 30, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [0a5cad12c2](https://linux-hardware.org/?probe=0a5cad12c2) | Dec 26, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [a4447312cc](https://linux-hardware.org/?probe=a4447312cc) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [af260af715](https://linux-hardware.org/?probe=af260af715) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Biostar       | A320MH                      | Desktop     | [31cc96d1d3](https://linux-hardware.org/?probe=31cc96d1d3) | Dec 11, 2022 |
| MSI           | H81M-E34                    | Desktop     | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c57f5be505](https://linux-hardware.org/?probe=c57f5be505) | Dec 10, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [c41ea027f7](https://linux-hardware.org/?probe=c41ea027f7) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| Intel         | H61                         | Desktop     | [4050e46b94](https://linux-hardware.org/?probe=4050e46b94) | Dec 03, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e61b6313fa](https://linux-hardware.org/?probe=e61b6313fa) | Dec 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [9964cb6fe2](https://linux-hardware.org/?probe=9964cb6fe2) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Getac         | S410                        | Notebook    | [3df44aa3af](https://linux-hardware.org/?probe=3df44aa3af) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [29b92290e8](https://linux-hardware.org/?probe=29b92290e8) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | Notebook    | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | Desktop     | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6e773a6bf0](https://linux-hardware.org/?probe=6e773a6bf0) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| Dell          | Studio 1558                 | Notebook    | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [65c0f5965b](https://linux-hardware.org/?probe=65c0f5965b) | Nov 04, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [4b580ecb2b](https://linux-hardware.org/?probe=4b580ecb2b) | Nov 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c47ee488a5](https://linux-hardware.org/?probe=c47ee488a5) | Nov 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [34c050ed44](https://linux-hardware.org/?probe=34c050ed44) | Nov 03, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [ada830a489](https://linux-hardware.org/?probe=ada830a489) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [e4af6d51f3](https://linux-hardware.org/?probe=e4af6d51f3) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [e1709bf653](https://linux-hardware.org/?probe=e1709bf653) | Oct 28, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [05cffb09e0](https://linux-hardware.org/?probe=05cffb09e0) | Oct 28, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [92e65a376a](https://linux-hardware.org/?probe=92e65a376a) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [682eb02d48](https://linux-hardware.org/?probe=682eb02d48) | Sep 22, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Dell          | Precision 7520              | Notebook    | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [8774a8312b](https://linux-hardware.org/?probe=8774a8312b) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| HP            | Pavilion dv5                | Notebook    | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [e8b519c4de](https://linux-hardware.org/?probe=e8b519c4de) | Aug 18, 2022 |
| ASUSTek       | UX32A                       | Notebook    | [99bb55bc78](https://linux-hardware.org/?probe=99bb55bc78) | Aug 17, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [a5ed221478](https://linux-hardware.org/?probe=a5ed221478) | Aug 17, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [9655bf78d0](https://linux-hardware.org/?probe=9655bf78d0) | Aug 05, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Google        | Swanky                      | Notebook    | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Google        | Swanky                      | Notebook    | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3aa2ff8224](https://linux-hardware.org/?probe=3aa2ff8224) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19572ca302](https://linux-hardware.org/?probe=19572ca302) | Jul 27, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5795e098d2](https://linux-hardware.org/?probe=5795e098d2) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| BESSTAR Te... | CB9                         | Mini pc     | [faa42224f0](https://linux-hardware.org/?probe=faa42224f0) | Jul 18, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Sony          | VPCEB1S1E                   | Notebook    | [d35015a369](https://linux-hardware.org/?probe=d35015a369) | Jul 12, 2022 |
| Dell          | Latitude XT                 | Notebook    | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | Notebook    | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| MicroByte     | ezbook                      | Notebook    | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [cce90ecbf2](https://linux-hardware.org/?probe=cce90ecbf2) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | 2B0D A01                    | All in one  | [43b3fd0fd4](https://linux-hardware.org/?probe=43b3fd0fd4) | Jul 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [87eecce08e](https://linux-hardware.org/?probe=87eecce08e) | Jun 30, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0685f37e2c](https://linux-hardware.org/?probe=0685f37e2c) | Jun 22, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0112d58d4e](https://linux-hardware.org/?probe=0112d58d4e) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e048d9df09](https://linux-hardware.org/?probe=e048d9df09) | Jun 17, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3de31234b3](https://linux-hardware.org/?probe=3de31234b3) | Jun 12, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [33d201cb1d](https://linux-hardware.org/?probe=33d201cb1d) | Jun 10, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [d9e8d3957e](https://linux-hardware.org/?probe=d9e8d3957e) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [20544feb00](https://linux-hardware.org/?probe=20544feb00) | Jun 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | Notebook    | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Medion        | Akoya E6415                 | Notebook    | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [4d68e6fd8d](https://linux-hardware.org/?probe=4d68e6fd8d) | May 12, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4dd8fa1d2f](https://linux-hardware.org/?probe=4dd8fa1d2f) | Apr 27, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fc283a78af](https://linux-hardware.org/?probe=fc283a78af) | Apr 26, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [bbb54a4f60](https://linux-hardware.org/?probe=bbb54a4f60) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| Dell          | 0X9M3X A05                  | Desktop     | [f049c88dfe](https://linux-hardware.org/?probe=f049c88dfe) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [81dced5e0a](https://linux-hardware.org/?probe=81dced5e0a) | Apr 16, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [52d05bca1d](https://linux-hardware.org/?probe=52d05bca1d) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| Samsung       | R505                        | Notebook    | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | Notebook    | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a54c91912a](https://linux-hardware.org/?probe=a54c91912a) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | Desktop     | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| Toshiba       | Satellite L755D             | Notebook    | [d99ccc2771](https://linux-hardware.org/?probe=d99ccc2771) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [3a8a0e2c0c](https://linux-hardware.org/?probe=3a8a0e2c0c) | Mar 26, 2022 |
| Dell          | 05KX61 A00                  | Server      | [77d570f7ae](https://linux-hardware.org/?probe=77d570f7ae) | Mar 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | Notebook    | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| HP            | 802E                        | Desktop     | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | 3397                        | Desktop     | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| HP            | Pavilion dv7                | Notebook    | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | Desktop     | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [8e3573295d](https://linux-hardware.org/?probe=8e3573295d) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [d57f5c8ce3](https://linux-hardware.org/?probe=d57f5c8ce3) | Mar 07, 2022 |
| Medion        | MS-7797                     | Desktop     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [f23d0b2728](https://linux-hardware.org/?probe=f23d0b2728) | Mar 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Lenovo        | U310                        | Notebook    | [856a65502e](https://linux-hardware.org/?probe=856a65502e) | Feb 28, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Intel         | H55                         | Desktop     | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [beeb081772](https://linux-hardware.org/?probe=beeb081772) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Pegatron      | Narra6                      | Desktop     | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | Notebook    | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Notebook      | NK50S5_SZ                   | Notebook    | [c5a3485d32](https://linux-hardware.org/?probe=c5a3485d32) | Feb 11, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [7c3fa0c43b](https://linux-hardware.org/?probe=7c3fa0c43b) | Feb 08, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3d6c666b77](https://linux-hardware.org/?probe=3d6c666b77) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| HP            | Notebook                    | Notebook    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [451c540217](https://linux-hardware.org/?probe=451c540217) | Feb 05, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [47e447f5da](https://linux-hardware.org/?probe=47e447f5da) | Jan 25, 2022 |
| Sony          | VPCF13Z1R                   | Notebook    | [7aff0d5c29](https://linux-hardware.org/?probe=7aff0d5c29) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [a4b48a8427](https://linux-hardware.org/?probe=a4b48a8427) | Jan 23, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [622bf721f3](https://linux-hardware.org/?probe=622bf721f3) | Jan 23, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [55067d6afe](https://linux-hardware.org/?probe=55067d6afe) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [37730388fd](https://linux-hardware.org/?probe=37730388fd) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [512b021ab8](https://linux-hardware.org/?probe=512b021ab8) | Jan 19, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [09e824f68b](https://linux-hardware.org/?probe=09e824f68b) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [556d0fb884](https://linux-hardware.org/?probe=556d0fb884) | Jan 18, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3d19d1297](https://linux-hardware.org/?probe=c3d19d1297) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [89d70da207](https://linux-hardware.org/?probe=89d70da207) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ae80854830](https://linux-hardware.org/?probe=ae80854830) | Jan 15, 2022 |
| ZOTAC         | NM10                        | Desktop     | [d758728651](https://linux-hardware.org/?probe=d758728651) | Jan 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d2fa7ede7](https://linux-hardware.org/?probe=9d2fa7ede7) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2fbac2ebd5](https://linux-hardware.org/?probe=2fbac2ebd5) | Jan 12, 2022 |
| HPE           | ML10Gen9                    | Server      | [03f2d30df2](https://linux-hardware.org/?probe=03f2d30df2) | Jan 11, 2022 |
| Dell          | Latitude E5400              | Notebook    | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| HP            | 3397                        | Desktop     | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [858d718984](https://linux-hardware.org/?probe=858d718984) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faef08af10](https://linux-hardware.org/?probe=faef08af10) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| HP            | ProLiant DL120 G7           | Server      | [70c39995ec](https://linux-hardware.org/?probe=70c39995ec) | Jan 03, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [9eb9340d47](https://linux-hardware.org/?probe=9eb9340d47) | Jan 02, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| ASRock        | 870iCafe R2.0               | Desktop     | [f67cc91b2e](https://linux-hardware.org/?probe=f67cc91b2e) | Dec 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5a25a3ab14](https://linux-hardware.org/?probe=5a25a3ab14) | Dec 31, 2021 |
| Gigabyte      | MZ71-CE0-00 01000100        | Server      | [6d2ee30f72](https://linux-hardware.org/?probe=6d2ee30f72) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e637f730e7](https://linux-hardware.org/?probe=e637f730e7) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [4c225dc457](https://linux-hardware.org/?probe=4c225dc457) | Dec 30, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [e32af6a3de](https://linux-hardware.org/?probe=e32af6a3de) | Dec 26, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [62abb9d0ef](https://linux-hardware.org/?probe=62abb9d0ef) | Dec 25, 2021 |
| Lenovo        | U310                        | Notebook    | [fa57a69141](https://linux-hardware.org/?probe=fa57a69141) | Dec 24, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [8f53f4e97c](https://linux-hardware.org/?probe=8f53f4e97c) | Dec 19, 2021 |
| AZW           | GK mini                     | Mini pc     | [bb4770d627](https://linux-hardware.org/?probe=bb4770d627) | Dec 17, 2021 |
| HP            | ENVY Notebook               | Notebook    | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | Notebook    | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [3bd9548bab](https://linux-hardware.org/?probe=3bd9548bab) | Dec 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| ASUSTek       | X751BP                      | Notebook    | [e1acc83725](https://linux-hardware.org/?probe=e1acc83725) | Dec 06, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d26ec246](https://linux-hardware.org/?probe=d0d26ec246) | Dec 01, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b7ec76b64](https://linux-hardware.org/?probe=6b7ec76b64) | Nov 28, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Dell          | 0T656F A01                  | Desktop     | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [bb170a308c](https://linux-hardware.org/?probe=bb170a308c) | Nov 24, 2021 |
| HPE           | ML10Gen9                    | Server      | [141f8709dd](https://linux-hardware.org/?probe=141f8709dd) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| Dell          | Precision 5560              | Notebook    | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [1bb376a60b](https://linux-hardware.org/?probe=1bb376a60b) | Nov 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [8a6de2970d](https://linux-hardware.org/?probe=8a6de2970d) | Nov 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Notebook    | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| AMI           | Unknown                     | Notebook    | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | Notebook    | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [1971073b86](https://linux-hardware.org/?probe=1971073b86) | Nov 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [c0b1971c18](https://linux-hardware.org/?probe=c0b1971c18) | Nov 09, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| Rockchip      | Unknown                     | Soc         | [de559ac6d9](https://linux-hardware.org/?probe=de559ac6d9) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [914d585adc](https://linux-hardware.org/?probe=914d585adc) | Nov 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| AZW           | SEi                         | Notebook    | [6d9a86e769](https://linux-hardware.org/?probe=6d9a86e769) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| MSI           | GE76 Raider 11UG            | Notebook    | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [7eaeae034c](https://linux-hardware.org/?probe=7eaeae034c) | Oct 29, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [6e1fbe4dde](https://linux-hardware.org/?probe=6e1fbe4dde) | Oct 27, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | Notebook    | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| HP            | G70                         | Notebook    | [68fb8430c2](https://linux-hardware.org/?probe=68fb8430c2) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [3e2c50a321](https://linux-hardware.org/?probe=3e2c50a321) | Oct 24, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4ba408d68c](https://linux-hardware.org/?probe=4ba408d68c) | Oct 23, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [e82ee9096e](https://linux-hardware.org/?probe=e82ee9096e) | Oct 23, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [3e15c8708a](https://linux-hardware.org/?probe=3e15c8708a) | Oct 23, 2021 |
| Rockchip      | Unknown                     | Soc         | [e7c44d5f41](https://linux-hardware.org/?probe=e7c44d5f41) | Oct 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | Notebook    | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [34a5253469](https://linux-hardware.org/?probe=34a5253469) | Oct 16, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [b4660289b3](https://linux-hardware.org/?probe=b4660289b3) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Latitude E6440              | Notebook    | [383edb4c99](https://linux-hardware.org/?probe=383edb4c99) | Oct 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c0867e544](https://linux-hardware.org/?probe=6c0867e544) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 633       | 44.83%  |
| Ubuntu MATE 18.04 | 267       | 18.91%  |
| Ubuntu MATE 22.04 | 235       | 16.64%  |
| Ubuntu MATE 20.10 | 53        | 3.75%   |
| Ubuntu MATE 19.10 | 48        | 3.4%    |
| Ubuntu MATE 21.10 | 45        | 3.19%   |
| Ubuntu MATE 21.04 | 42        | 2.97%   |
| Ubuntu MATE 22.10 | 37        | 2.62%   |
| Ubuntu MATE 16.04 | 21        | 1.49%   |
| Ubuntu MATE 23.04 | 17        | 1.2%    |
| Ubuntu MATE       | 6         | 0.42%   |
| Ubuntu MATE 19.04 | 2         | 0.14%   |
| Ubuntu MATE 18.10 | 2         | 0.14%   |
| Ubuntu MATE 17.04 | 2         | 0.14%   |
| Ubuntu MATE 16.10 | 1         | 0.07%   |
| Ubuntu MATE 15.04 | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 1361      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 56        | 3.54%   |
| 5.4.0-48-generic   | 44        | 2.78%   |
| 5.4.0-52-generic   | 35        | 2.22%   |
| 5.4.0-47-generic   | 31        | 1.96%   |
| 5.15.0-56-generic  | 31        | 1.96%   |
| 5.4.0-65-generic   | 23        | 1.46%   |
| 5.4.0-58-generic   | 19        | 1.2%    |
| 5.4.0-40-generic   | 18        | 1.14%   |
| 5.15.0-47-generic  | 18        | 1.14%   |
| 4.15.0-163-generic | 17        | 1.08%   |
| 5.4.0-45-generic   | 16        | 1.01%   |
| 5.3.0-46-generic   | 16        | 1.01%   |
| 5.3.0-40-generic   | 16        | 1.01%   |
| 5.15.0-48-generic  | 16        | 1.01%   |
| 5.8.0-48-generic   | 15        | 0.95%   |
| 5.15.0-46-generic  | 14        | 0.89%   |
| 5.4.0-94-generic   | 13        | 0.82%   |
| 5.3.0-42-generic   | 13        | 0.82%   |
| 5.15.0-60-generic  | 13        | 0.82%   |
| 5.15.0-58-generic  | 13        | 0.82%   |
| 5.11.0-40-generic  | 13        | 0.82%   |
| 5.8.0-50-generic   | 12        | 0.76%   |
| 5.4.0-81-generic   | 12        | 0.76%   |
| 5.4.0-56-generic   | 12        | 0.76%   |
| 5.4.0-26-generic   | 12        | 0.76%   |
| 5.15.0-52-generic  | 12        | 0.76%   |
| 5.15.0-43-generic  | 12        | 0.76%   |
| 5.15.0-40-generic  | 11        | 0.7%    |
| 5.13.0-30-generic  | 11        | 0.7%    |
| 5.4.0-89-generic   | 10        | 0.63%   |
| 5.4.0-74-generic   | 10        | 0.63%   |
| 5.4.0-66-generic   | 10        | 0.63%   |
| 5.4.0-31-generic   | 10        | 0.63%   |
| 5.4.0-29-generic   | 10        | 0.63%   |
| 5.3.0-51-generic   | 10        | 0.63%   |
| 5.3.0-28-generic   | 10        | 0.63%   |
| 5.15.0-67-generic  | 10        | 0.63%   |
| 5.15.0-25-generic  | 10        | 0.63%   |
| 5.13.0-39-generic  | 10        | 0.63%   |
| 5.8.0-59-generic   | 9         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 519       | 35.99%  |
| 5.15.0  | 222       | 15.4%   |
| 5.3.0   | 118       | 8.18%   |
| 5.8.0   | 105       | 7.28%   |
| 4.15.0  | 101       | 7%      |
| 5.11.0  | 97        | 6.73%   |
| 5.13.0  | 88        | 6.1%    |
| 5.19.0  | 66        | 4.58%   |
| 5.0.0   | 15        | 1.04%   |
| 6.2.0   | 10        | 0.69%   |
| 4.4.0   | 9         | 0.62%   |
| 5.14.0  | 8         | 0.55%   |
| 5.17.0  | 4         | 0.28%   |
| 5.10.27 | 4         | 0.28%   |
| 4.9.277 | 4         | 0.28%   |
| 4.18.0  | 4         | 0.28%   |
| 5.18.0  | 3         | 0.21%   |
| 4.10.0  | 3         | 0.21%   |
| 6.4.0   | 2         | 0.14%   |
| 6.3.7   | 2         | 0.14%   |
| 6.3.4   | 2         | 0.14%   |
| 6.3.1   | 2         | 0.14%   |
| 6.3.0   | 2         | 0.14%   |
| 6.2.11  | 2         | 0.14%   |
| 6.1.12  | 2         | 0.14%   |
| 5.4.2   | 2         | 0.14%   |
| 5.10.5  | 2         | 0.14%   |
| 5.10.0  | 2         | 0.14%   |
| 4.4.154 | 2         | 0.14%   |
| 6.2.9   | 1         | 0.07%   |
| 6.2.8   | 1         | 0.07%   |
| 6.2.3   | 1         | 0.07%   |
| 6.1.8   | 1         | 0.07%   |
| 6.1.11  | 1         | 0.07%   |
| 6.1.0   | 1         | 0.07%   |
| 6.0.8   | 1         | 0.07%   |
| 5.9.3   | 1         | 0.07%   |
| 5.9.1   | 1         | 0.07%   |
| 5.9.0   | 1         | 0.07%   |
| 5.8.17  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 522       | 36.33%  |
| 5.15    | 227       | 15.8%   |
| 5.3     | 118       | 8.21%   |
| 5.8     | 107       | 7.45%   |
| 4.15    | 101       | 7.03%   |
| 5.11    | 97        | 6.75%   |
| 5.13    | 88        | 6.12%   |
| 5.19    | 66        | 4.59%   |
| 5.0     | 15        | 1.04%   |
| 6.2     | 13        | 0.9%    |
| 4.4     | 12        | 0.84%   |
| 5.14    | 8         | 0.56%   |
| 5.10    | 8         | 0.56%   |
| 6.3     | 6         | 0.42%   |
| 4.9     | 6         | 0.42%   |
| 6.1     | 5         | 0.35%   |
| 5.17    | 5         | 0.35%   |
| 4.18    | 4         | 0.28%   |
| 5.9     | 3         | 0.21%   |
| 5.18    | 3         | 0.21%   |
| 4.14    | 3         | 0.21%   |
| 4.10    | 3         | 0.21%   |
| 6.4     | 2         | 0.14%   |
| 5.7     | 2         | 0.14%   |
| 5.6     | 2         | 0.14%   |
| 5.5     | 2         | 0.14%   |
| 5.12    | 2         | 0.14%   |
| 6.0     | 1         | 0.07%   |
| 5.16    | 1         | 0.07%   |
| 4.8     | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 3.19    | 1         | 0.07%   |
| 3.16    | 1         | 0.07%   |
| 3.14    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1229      | 90.3%   |
| i686    | 76        | 5.58%   |
| aarch64 | 45        | 3.31%   |
| armv7l  | 10        | 0.73%   |
| ppc     | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 1331      | 97.72%  |
| cinnamon   | 7         | 0.51%   |
| X-Cinnamon | 6         | 0.44%   |
| KDE5       | 6         | 0.44%   |
| GNOME      | 6         | 0.44%   |
| Trinity    | 2         | 0.15%   |
| Budgie     | 2         | 0.15%   |
| XFCE       | 1         | 0.07%   |
| i3         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1322      | 96.99%  |
| Tty     | 26        | 1.91%   |
| Wayland | 15        | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 556       | 39.43%  |
| Unknown | 459       | 32.55%  |
| TDM     | 309       | 21.91%  |
| GDM     | 36        | 2.55%   |
| GDM3    | 35        | 2.48%   |
| SDDM    | 6         | 0.43%   |
| LXDM    | 6         | 0.43%   |
| SLiM    | 3         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 456       | 33.19%  |
| fr_FR   | 125       | 9.1%    |
| de_DE   | 125       | 9.1%    |
| pt_BR   | 117       | 8.52%   |
| en_GB   | 66        | 4.8%    |
| it_IT   | 59        | 4.29%   |
| es_ES   | 43        | 3.13%   |
| ru_RU   | 41        | 2.98%   |
| el_GR   | 35        | 2.55%   |
| Unknown | 35        | 2.55%   |
| en_CA   | 31        | 2.26%   |
| C       | 30        | 2.18%   |
| en_AU   | 25        | 1.82%   |
| es_AR   | 16        | 1.16%   |
| pl_PL   | 14        | 1.02%   |
| sv_SE   | 11        | 0.8%    |
| hu_HU   | 11        | 0.8%    |
| nl_NL   | 9         | 0.66%   |
| en_IN   | 9         | 0.66%   |
| de_CH   | 8         | 0.58%   |
| cs_CZ   | 8         | 0.58%   |
| fi_FI   | 7         | 0.51%   |
| es_PE   | 7         | 0.51%   |
| ru_UA   | 6         | 0.44%   |
| es_MX   | 5         | 0.36%   |
| zh_TW   | 4         | 0.29%   |
| es_VE   | 4         | 0.29%   |
| es_CL   | 4         | 0.29%   |
| en_PH   | 4         | 0.29%   |
| en_IL   | 4         | 0.29%   |
| de_AT   | 4         | 0.29%   |
| pt_PT   | 3         | 0.22%   |
| nl_BE   | 3         | 0.22%   |
| hr_HR   | 3         | 0.22%   |
| fr_CA   | 3         | 0.22%   |
| da_DK   | 3         | 0.22%   |
| ca_ES   | 3         | 0.22%   |
| zh_CN   | 2         | 0.15%   |
| ja_JP   | 2         | 0.15%   |
| fr_BE   | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 770       | 55.52%  |
| EFI  | 617       | 44.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1233      | 89.87%  |
| Overlay | 54        | 3.94%   |
| Btrfs   | 25        | 1.82%   |
| Zfs     | 17        | 1.24%   |
| Tmpfs   | 15        | 1.09%   |
| Xfs     | 9         | 0.66%   |
| Unknown | 9         | 0.66%   |
| Ext3    | 3         | 0.22%   |
| Jfs     | 2         | 0.15%   |
| Ext2    | 2         | 0.15%   |
| Aufs    | 2         | 0.15%   |
| ExX4    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 565       | 40.68%  |
| GPT     | 551       | 39.67%  |
| MBR     | 273       | 19.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1182      | 85.78%  |
| Yes       | 196       | 14.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 920       | 66.57%  |
| Yes       | 462       | 33.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 229       | 16.83%  |
| ASUSTek Computer        | 209       | 15.36%  |
| Dell                    | 183       | 13.45%  |
| Lenovo                  | 160       | 11.76%  |
| Gigabyte Technology     | 74        | 5.44%   |
| MSI                     | 72        | 5.29%   |
| Acer                    | 63        | 4.63%   |
| Raspberry Pi Foundation | 39        | 2.87%   |
| ASRock                  | 37        | 2.72%   |
| Intel                   | 35        | 2.57%   |
| Toshiba                 | 26        | 1.91%   |
| Unknown                 | 18        | 1.32%   |
| Sony                    | 16        | 1.18%   |
| Apple                   | 16        | 1.18%   |
| Samsung Electronics     | 14        | 1.03%   |
| Fujitsu                 | 11        | 0.81%   |
| Hardkernel              | 10        | 0.73%   |
| Medion                  | 9         | 0.66%   |
| Notebook                | 7         | 0.51%   |
| Supermicro              | 6         | 0.44%   |
| Packard Bell            | 6         | 0.44%   |
| Pegatron                | 5         | 0.37%   |
| AZW                     | 5         | 0.37%   |
| Positivo                | 4         | 0.29%   |
| HUAWEI                  | 4         | 0.29%   |
| Google                  | 4         | 0.29%   |
| Fujitsu Siemens         | 4         | 0.29%   |
| ECS                     | 4         | 0.29%   |
| Biostar                 | 4         | 0.29%   |
| TUXEDO                  | 3         | 0.22%   |
| TrekStor                | 3         | 0.22%   |
| Quanta                  | 3         | 0.22%   |
| LG Electronics          | 3         | 0.22%   |
| eMachines               | 3         | 0.22%   |
| Clevo                   | 3         | 0.22%   |
| Chuwi                   | 3         | 0.22%   |
| Avell High Performance  | 3         | 0.22%   |
| Wortmann AG             | 2         | 0.15%   |
| TYAN Computer           | 2         | 0.15%   |
| System76                | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 28        | 2.06%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 10        | 0.73%   |
| HP Compaq Elite 8300 SFF           | 10        | 0.73%   |
| ASUS All Series                    | 10        | 0.73%   |
| RPi Raspberry Pi                   | 9         | 0.66%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 8         | 0.59%   |
| HP ProDesk 600 G1 SFF              | 8         | 0.59%   |
| HP Compaq 6005 Pro SFF PC          | 8         | 0.59%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 7         | 0.51%   |
| HP Pavilion g6                     | 6         | 0.44%   |
| Hardkernel ODROID-N2Plus           | 6         | 0.44%   |
| Dell Latitude E6410                | 6         | 0.44%   |
| HP Pavilion dv7                    | 5         | 0.37%   |
| Dell OptiPlex 3010                 | 5         | 0.37%   |
| Dell Latitude E6420                | 5         | 0.37%   |
| ASUS M5A97 R2.0                    | 5         | 0.37%   |
| MSI MS-7817                        | 4         | 0.29%   |
| Lenovo IdeaPad 3 15IIL05 81WE      | 4         | 0.29%   |
| HP Notebook                        | 4         | 0.29%   |
| HP Compaq 6200 Pro SFF PC          | 4         | 0.29%   |
| Dell OptiPlex GX520                | 4         | 0.29%   |
| Dell OptiPlex 755                  | 4         | 0.29%   |
| Dell OptiPlex 390                  | 4         | 0.29%   |
| Dell OptiPlex 360                  | 4         | 0.29%   |
| ASRock B450M Pro4                  | 4         | 0.29%   |
| TrekStor Surfbook A13B             | 3         | 0.22%   |
| RPi Raspberry Pi 3 Model B Rev 1.2 | 3         | 0.22%   |
| HP ProLiant MicroServer            | 3         | 0.22%   |
| HP Pavilion 17                     | 3         | 0.22%   |
| HP Compaq 8000 Elite SFF PC        | 3         | 0.22%   |
| HP 15                              | 3         | 0.22%   |
| Gigabyte B450M DS3H                | 3         | 0.22%   |
| Dell Precision M4800               | 3         | 0.22%   |
| Dell OptiPlex GX620                | 3         | 0.22%   |
| Dell OptiPlex 790                  | 3         | 0.22%   |
| Dell OptiPlex 330                  | 3         | 0.22%   |
| Dell Latitude E6500                | 3         | 0.22%   |
| ASUS M5A78L-M/USB3                 | 3         | 0.22%   |
| ASUS M5A78L-M PLUS/USB3            | 3         | 0.22%   |
| ASUS H61M-K                        | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 73        | 5.36%   |
| Dell OptiPlex            | 50        | 3.67%   |
| HP Compaq                | 46        | 3.38%   |
| Dell Latitude            | 46        | 3.38%   |
| Acer Aspire              | 44        | 3.23%   |
| HP Pavilion              | 41        | 3.01%   |
| RPi Raspberry            | 39        | 2.87%   |
| Lenovo IdeaPad           | 30        | 2.2%    |
| Unknown                  | 28        | 2.06%   |
| Dell Precision           | 27        | 1.98%   |
| HP EliteBook             | 26        | 1.91%   |
| Dell Inspiron            | 25        | 1.84%   |
| Toshiba Satellite        | 24        | 1.76%   |
| ASUS PRIME               | 22        | 1.62%   |
| Lenovo ThinkCentre       | 16        | 1.18%   |
| ASUS ROG                 | 16        | 1.18%   |
| HP ProBook               | 13        | 0.96%   |
| Dell Vostro              | 11        | 0.81%   |
| HP ProDesk               | 10        | 0.73%   |
| HP Laptop                | 10        | 0.73%   |
| Dell XPS                 | 10        | 0.73%   |
| ASUS All                 | 10        | 0.73%   |
| Fujitsu LIFEBOOK         | 9         | 0.66%   |
| ASUS VivoBook            | 8         | 0.59%   |
| HP ZBook                 | 7         | 0.51%   |
| ASUS TUF                 | 7         | 0.51%   |
| ASUS M5A97               | 7         | 0.51%   |
| ASUS M5A78L-M            | 7         | 0.51%   |
| Lenovo ThinkBook         | 6         | 0.44%   |
| HP ProLiant              | 6         | 0.44%   |
| HP ENVY                  | 6         | 0.44%   |
| HP EliteDesk             | 6         | 0.44%   |
| HP 250                   | 6         | 0.44%   |
| Hardkernel ODROID-N2Plus | 6         | 0.44%   |
| Acer TravelMate          | 6         | 0.44%   |
| Packard Bell EasyNote    | 5         | 0.37%   |
| HP Stream                | 5         | 0.37%   |
| MSI MS-7817              | 4         | 0.29%   |
| Lenovo Legion            | 4         | 0.29%   |
| Lenovo IdeaPadFlex       | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 133       | 9.77%   |
| 2012    | 123       | 9.04%   |
| 2020    | 112       | 8.23%   |
| 2018    | 111       | 8.16%   |
| 2013    | 102       | 7.49%   |
| 2019    | 85        | 6.25%   |
| 2014    | 78        | 5.73%   |
| 2010    | 78        | 5.73%   |
| 2008    | 73        | 5.36%   |
| 2021    | 72        | 5.29%   |
| 2009    | 69        | 5.07%   |
| 2017    | 67        | 4.92%   |
| 2015    | 65        | 4.78%   |
| 2016    | 56        | 4.11%   |
| Unknown | 38        | 2.79%   |
| 2007    | 37        | 2.72%   |
| 2006    | 24        | 1.76%   |
| 2022    | 21        | 1.54%   |
| 2005    | 12        | 0.88%   |
| 2023    | 3         | 0.22%   |
| 2004    | 1         | 0.07%   |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 676       | 49.67%  |
| Desktop        | 544       | 39.97%  |
| System on chip | 53        | 3.89%   |
| Mini pc        | 27        | 1.98%   |
| Convertible    | 19        | 1.4%    |
| All in one     | 17        | 1.25%   |
| Server         | 15        | 1.1%    |
| Tablet         | 10        | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1278      | 93.49%  |
| Enabled  | 89        | 6.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1356      | 99.63%  |
| Yes  | 5         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 357       | 25.94%  |
| 4.01-8.0        | 279       | 20.28%  |
| 8.01-16.0       | 215       | 15.63%  |
| 16.01-24.0      | 207       | 15.04%  |
| 32.01-64.0      | 107       | 7.78%   |
| 1.01-2.0        | 74        | 5.38%   |
| 64.01-256.0     | 59        | 4.29%   |
| 2.01-3.0        | 33        | 2.4%    |
| 24.01-32.0      | 22        | 1.6%    |
| 0.51-1.0        | 21        | 1.53%   |
| More than 256.0 | 1         | 0.07%   |
| 0.01-0.5        | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 515       | 35.11%  |
| 2.01-3.0   | 334       | 22.77%  |
| 0.51-1.0   | 197       | 13.43%  |
| 4.01-8.0   | 170       | 11.59%  |
| 3.01-4.0   | 163       | 11.11%  |
| 8.01-16.0  | 48        | 3.27%   |
| 0.01-0.5   | 22        | 1.5%    |
| 24.01-32.0 | 8         | 0.55%   |
| 32.01-64.0 | 5         | 0.34%   |
| 16.01-24.0 | 5         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 841       | 60.29%  |
| 2      | 350       | 25.09%  |
| 3      | 107       | 7.67%   |
| 4      | 45        | 3.23%   |
| 5      | 15        | 1.08%   |
| 6      | 11        | 0.79%   |
| 0      | 9         | 0.65%   |
| 7      | 6         | 0.43%   |
| 10     | 3         | 0.22%   |
| 8      | 3         | 0.22%   |
| 11     | 2         | 0.14%   |
| 20     | 1         | 0.07%   |
| 12     | 1         | 0.07%   |
| 9      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 711       | 51.86%  |
| Yes       | 660       | 48.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1188      | 87.22%  |
| No        | 174       | 12.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 941       | 68.59%  |
| No        | 431       | 31.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 700       | 51.06%  |
| No        | 671       | 48.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 189       | 13.81%  |
| Germany     | 154       | 11.25%  |
| Brazil      | 139       | 10.15%  |
| France      | 133       | 9.72%   |
| Italy       | 75        | 5.48%   |
| UK          | 65        | 4.75%   |
| Russia      | 65        | 4.75%   |
| Spain       | 59        | 4.31%   |
| Greece      | 42        | 3.07%   |
| Canada      | 32        | 2.34%   |
| Australia   | 26        | 1.9%    |
| Netherlands | 21        | 1.53%   |
| Argentina   | 21        | 1.53%   |
| Hungary     | 19        | 1.39%   |
| Switzerland | 17        | 1.24%   |
| Ukraine     | 16        | 1.17%   |
| Sweden      | 16        | 1.17%   |
| Poland      | 16        | 1.17%   |
| Belgium     | 16        | 1.17%   |
| Czechia     | 14        | 1.02%   |
| India       | 13        | 0.95%   |
| Finland     | 13        | 0.95%   |
| Austria     | 13        | 0.95%   |
| Turkey      | 12        | 0.88%   |
| Mexico      | 11        | 0.8%    |
| Romania     | 9         | 0.66%   |
| Portugal    | 9         | 0.66%   |
| Norway      | 9         | 0.66%   |
| Indonesia   | 8         | 0.58%   |
| Peru        | 7         | 0.51%   |
| Denmark     | 7         | 0.51%   |
| Chile       | 7         | 0.51%   |
| Thailand    | 6         | 0.44%   |
| Taiwan      | 6         | 0.44%   |
| Croatia     | 6         | 0.44%   |
| Venezuela   | 5         | 0.37%   |
| Israel      | 5         | 0.37%   |
| Estonia     | 5         | 0.37%   |
| Philippines | 4         | 0.29%   |
| Japan       | 4         | 0.29%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 76        | 5.26%   |
| Paris             | 26        | 1.8%    |
| Moscow            | 22        | 1.52%   |
| Thessaloniki      | 19        | 1.32%   |
| Berlin            | 19        | 1.32%   |
| Athens            | 17        | 1.18%   |
| Rome              | 12        | 0.83%   |
| St Petersburg     | 9         | 0.62%   |
| Madrid            | 8         | 0.55%   |
| Budapest          | 8         | 0.55%   |
| Melbourne         | 7         | 0.48%   |
| Barcelona         | 7         | 0.48%   |
| Zurich            | 6         | 0.42%   |
| Sundbyberg        | 6         | 0.42%   |
| Mannheim          | 6         | 0.42%   |
| Manchester        | 6         | 0.42%   |
| Los Ángeles      | 6         | 0.42%   |
| Kyiv              | 6         | 0.42%   |
| Hamburg           | 6         | 0.42%   |
| Amsterdam         | 6         | 0.42%   |
| Vienna            | 5         | 0.35%   |
| Rio de Janeiro    | 5         | 0.35%   |
| Perth             | 5         | 0.35%   |
| Munich            | 5         | 0.35%   |
| Montpellier       | 5         | 0.35%   |
| Milan             | 5         | 0.35%   |
| Helsinki          | 5         | 0.35%   |
| Cologne           | 5         | 0.35%   |
| Sydney            | 4         | 0.28%   |
| Southampton       | 4         | 0.28%   |
| Genoa             | 4         | 0.28%   |
| Frankfurt am Main | 4         | 0.28%   |
| Essen             | 4         | 0.28%   |
| Ely               | 4         | 0.28%   |
| Cleveland         | 4         | 0.28%   |
| Buenos Aires      | 4         | 0.28%   |
| Bucharest         | 4         | 0.28%   |
| Brisbane          | 4         | 0.28%   |
| Bordeaux          | 4         | 0.28%   |
| Bengaluru         | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 320       | 506    | 16.39%  |
| WDC                       | 307       | 449    | 15.73%  |
| Samsung Electronics       | 288       | 440    | 14.75%  |
| Toshiba                   | 124       | 189    | 6.35%   |
| Unknown                   | 123       | 163    | 6.3%    |
| Kingston                  | 115       | 144    | 5.89%   |
| Sandisk                   | 83        | 100    | 4.25%   |
| Hitachi                   | 76        | 91     | 3.89%   |
| Crucial                   | 75        | 106    | 3.84%   |
| Intel                     | 43        | 54     | 2.2%    |
| SK hynix                  | 39        | 49     | 2%      |
| A-DATA Technology         | 28        | 30     | 1.43%   |
| China                     | 20        | 24     | 1.02%   |
| HGST                      | 19        | 27     | 0.97%   |
| Phison                    | 16        | 17     | 0.82%   |
| Fujitsu                   | 16        | 17     | 0.82%   |
| PNY                       | 13        | 14     | 0.67%   |
| Micron Technology         | 13        | 14     | 0.67%   |
| KIOXIA                    | 12        | 13     | 0.61%   |
| Intenso                   | 10        | 13     | 0.51%   |
| SPCC                      | 8         | 16     | 0.41%   |
| Silicon Motion            | 8         | 9      | 0.41%   |
| Patriot                   | 8         | 10     | 0.41%   |
| Corsair                   | 8         | 9      | 0.41%   |
| Transcend                 | 7         | 13     | 0.36%   |
| Maxtor                    | 7         | 12     | 0.36%   |
| JMicron Technology        | 7         | 10     | 0.36%   |
| LITEONIT                  | 6         | 7      | 0.31%   |
| LITEON                    | 6         | 7      | 0.31%   |
| Apacer                    | 6         | 7      | 0.31%   |
| Unknown                   | 6         | 6      | 0.31%   |
| OCZ                       | 5         | 5      | 0.26%   |
| Netac                     | 5         | 5      | 0.26%   |
| Micron/Crucial Technology | 5         | 10     | 0.26%   |
| KingSpec                  | 5         | 6      | 0.26%   |
| Hewlett-Packard           | 5         | 6      | 0.26%   |
| SABRENT                   | 4         | 4      | 0.2%    |
| Phison Electronics        | 4         | 4      | 0.2%    |
| Verbatim                  | 3         | 7      | 0.15%   |
| Team                      | 3         | 3      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 31        | 1.44%   |
| Seagate ST500DM002-1BD142 500GB     | 27        | 1.26%   |
| Unknown MMC Card  64GB              | 21        | 0.98%   |
| Kingston SA400S37120G 120GB SSD     | 21        | 0.98%   |
| Kingston SA400S37240G 240GB SSD     | 19        | 0.88%   |
| Samsung SSD 860 EVO 500GB           | 17        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB            | 15        | 0.7%    |
| Toshiba MQ01ABF050 500GB            | 13        | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB      | 12        | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB      | 12        | 0.56%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB      | 11        | 0.51%   |
| Kingston SA400S37480G 480GB SSD     | 11        | 0.51%   |
| Unknown MMC Card  16GB              | 10        | 0.46%   |
| Toshiba DT01ACA050 500GB            | 10        | 0.46%   |
| Seagate ST3500418AS 500GB           | 10        | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 9         | 0.42%   |
| Unknown MMC Card  128GB             | 9         | 0.42%   |
| Toshiba DT01ACA100 1TB              | 9         | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 0.42%   |
| Samsung SSD 850 EVO 250GB           | 9         | 0.42%   |
| Seagate ST9500325AS 500GB           | 8         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 0.37%   |
| WDC WD5000AAKX-083CA1 500GB         | 7         | 0.33%   |
| WDC WD5000AAKX-003CA0 500GB         | 7         | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB            | 7         | 0.33%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.33%   |
| Toshiba DT01ACA200 2TB              | 7         | 0.33%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.33%   |
| Seagate ST4000DM004-2CV104 4TB      | 7         | 0.33%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 0.33%   |
| Seagate ST2000DM001-9YN164 2TB      | 7         | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 0.33%   |
| Seagate Expansion 1TB               | 7         | 0.33%   |
| SanDisk SSD PLUS 480GB              | 7         | 0.33%   |
| SanDisk SDSSDA240G 240GB            | 7         | 0.33%   |
| Samsung NVMe SSD Drive 500GB        | 7         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 319       | 502    | 36.92%  |
| WDC                 | 259       | 376    | 29.98%  |
| Toshiba             | 102       | 159    | 11.81%  |
| Hitachi             | 76        | 91     | 8.8%    |
| Samsung Electronics | 43        | 56     | 4.98%   |
| HGST                | 19        | 27     | 2.2%    |
| Fujitsu             | 16        | 17     | 1.85%   |
| Unknown             | 8         | 11     | 0.93%   |
| Maxtor              | 6         | 10     | 0.69%   |
| SAGE                | 2         | 2      | 0.23%   |
| IBM/Hitachi         | 2         | 2      | 0.23%   |
| Hewlett-Packard     | 2         | 3      | 0.23%   |
| ASMT109x            | 2         | 3      | 0.23%   |
| USB3.0              | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| KESU                | 1         | 3      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| Inateck             | 1         | 1      | 0.12%   |
| DAS                 | 1         | 6      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| Apricorn            | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 158       | 226    | 24.73%  |
| Kingston            | 96        | 117    | 15.02%  |
| Crucial             | 69        | 100    | 10.8%   |
| SanDisk             | 65        | 79     | 10.17%  |
| WDC                 | 34        | 46     | 5.32%   |
| A-DATA Technology   | 24        | 26     | 3.76%   |
| Intel               | 22        | 31     | 3.44%   |
| China               | 19        | 23     | 2.97%   |
| PNY                 | 13        | 14     | 2.03%   |
| Toshiba             | 9         | 11     | 1.41%   |
| SK hynix            | 8         | 10     | 1.25%   |
| Intenso             | 8         | 11     | 1.25%   |
| Transcend           | 7         | 13     | 1.1%    |
| SPCC                | 6         | 13     | 0.94%   |
| Patriot             | 6         | 8      | 0.94%   |
| LITEONIT            | 6         | 7      | 0.94%   |
| Apacer              | 6         | 7      | 0.94%   |
| OCZ                 | 5         | 5      | 0.78%   |
| LITEON              | 5         | 6      | 0.78%   |
| KingSpec            | 5         | 6      | 0.78%   |
| Netac               | 4         | 4      | 0.63%   |
| Micron Technology   | 4         | 5      | 0.63%   |
| Verbatim            | 3         | 7      | 0.47%   |
| Team                | 3         | 3      | 0.47%   |
| Plextor             | 3         | 3      | 0.47%   |
| Vaseky              | 2         | 2      | 0.31%   |
| Seagate             | 2         | 2      | 0.31%   |
| LDLC                | 2         | 2      | 0.31%   |
| FORESEE             | 2         | 2      | 0.31%   |
| Corsair             | 2         | 2      | 0.31%   |
| BAITITON            | 2         | 2      | 0.31%   |
| ASMT                | 2         | 3      | 0.31%   |
| Argon               | 2         | 3      | 0.31%   |
| Apple               | 2         | 2      | 0.31%   |
| AMD                 | 2         | 2      | 0.31%   |
| WDC WDS2            | 1         | 1      | 0.16%   |
| Unknown             | 1         | 2      | 0.16%   |
| TO Exter            | 1         | 1      | 0.16%   |
| Super Talent        | 1         | 1      | 0.16%   |
| SMI                 | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 740       | 1274   | 42.17%  |
| SSD     | 564       | 837    | 32.14%  |
| NVMe    | 310       | 432    | 17.66%  |
| MMC     | 110       | 147    | 6.27%   |
| Unknown | 31        | 38     | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1077      | 2037   | 68.34%  |
| NVMe | 305       | 424    | 19.35%  |
| MMC  | 110       | 147    | 6.98%   |
| SAS  | 84        | 120    | 5.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 831       | 1204   | 60%     |
| 0.51-1.0   | 348       | 538    | 25.13%  |
| 1.01-2.0   | 117       | 188    | 8.45%   |
| 3.01-4.0   | 38        | 53     | 2.74%   |
| 4.01-10.0  | 29        | 84     | 2.09%   |
| 2.01-3.0   | 20        | 35     | 1.44%   |
| 10.01-20.0 | 2         | 9      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 367       | 25.92%  |
| 251-500        | 339       | 23.94%  |
| 501-1000       | 206       | 14.55%  |
| 1001-2000      | 118       | 8.33%   |
| 51-100         | 94        | 6.64%   |
| More than 3000 | 82        | 5.79%   |
| 21-50          | 67        | 4.73%   |
| 1-20           | 62        | 4.38%   |
| 2001-3000      | 50        | 3.53%   |
| Unknown        | 31        | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 475       | 32.78%  |
| 21-50          | 230       | 15.87%  |
| 101-250        | 202       | 13.94%  |
| 51-100         | 175       | 12.08%  |
| 251-500        | 125       | 8.63%   |
| 501-1000       | 86        | 5.94%   |
| 1001-2000      | 61        | 4.21%   |
| More than 3000 | 35        | 2.42%   |
| Unknown        | 31        | 2.14%   |
| 2001-3000      | 29        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 9      | 5.26%   |
| Seagate ST320LT007-9ZV142 320GB       | 5         | 5      | 2.92%   |
| WDC WD5000AAKX-083CA1 500GB           | 4         | 4      | 2.34%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 2.34%   |
| WDC WD5000AAKX-003CA0 500GB           | 2         | 2      | 1.17%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 2         | 2      | 1.17%   |
| WDC WD2500AAKX-753CA1 250GB           | 2         | 2      | 1.17%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 4      | 1.17%   |
| Unknown MM0500EANCR 500GB             | 2         | 5      | 1.17%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 1.17%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 1.17%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.17%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.17%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.17%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.17%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 3      | 1.17%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 1.17%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 1.17%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 1.17%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 1.17%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 1.17%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.17%   |
| Hitachi HTS542516K9SA00 160GB         | 2         | 2      | 1.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.58%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 0.58%   |
| WDC WD7500BPVT-75HXZT1 752GB          | 1         | 1      | 0.58%   |
| WDC WD7500BPVT-22A1YT0 752GB          | 1         | 1      | 0.58%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.58%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 2      | 0.58%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 1      | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.58%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1         | 2      | 0.58%   |
| WDC WD3200BEKT-60V5T1 320GB           | 1         | 1      | 0.58%   |
| WDC WD3200AAJS-40VWA1 320GB           | 1         | 1      | 0.58%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.58%   |
| WDC WD2500YS-01SHB1 256GB             | 1         | 1      | 0.58%   |
| WDC WD2500BEKT-60A25T1 250GB          | 1         | 1      | 0.58%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.58%   |
| WDC WD2500AAJS-75M0A0 249GB           | 1         | 1      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 58     | 32.74%  |
| WDC                 | 39        | 47     | 23.21%  |
| Samsung Electronics | 16        | 20     | 9.52%   |
| Hitachi             | 12        | 12     | 7.14%   |
| Toshiba             | 9         | 9      | 5.36%   |
| Intel               | 5         | 6      | 2.98%   |
| Kingston            | 4         | 5      | 2.38%   |
| OCZ                 | 3         | 3      | 1.79%   |
| Unknown             | 2         | 5      | 1.19%   |
| SK hynix            | 2         | 5      | 1.19%   |
| SanDisk             | 2         | 2      | 1.19%   |
| Maxtor              | 2         | 2      | 1.19%   |
| Fujitsu             | 2         | 2      | 1.19%   |
| Crucial             | 2         | 2      | 1.19%   |
| China               | 2         | 2      | 1.19%   |
| A-DATA Technology   | 2         | 4      | 1.19%   |
| Vaseky              | 1         | 1      | 0.6%    |
| NGFF                | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| IBM/Hitachi         | 1         | 1      | 0.6%    |
| HGST                | 1         | 2      | 0.6%    |
| Eluktro             | 1         | 1      | 0.6%    |
| DAS                 | 1         | 3      | 0.6%    |
| ASMT                | 1         | 2      | 0.6%    |
| Apricorn            | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 58     | 41.67%  |
| WDC                 | 38        | 46     | 28.79%  |
| Hitachi             | 12        | 12     | 9.09%   |
| Toshiba             | 9         | 9      | 6.82%   |
| Samsung Electronics | 8         | 9      | 6.06%   |
| Unknown             | 2         | 5      | 1.52%   |
| Maxtor              | 2         | 2      | 1.52%   |
| Fujitsu             | 2         | 2      | 1.52%   |
| IBM/Hitachi         | 1         | 1      | 0.76%   |
| HGST                | 1         | 2      | 0.76%   |
| DAS                 | 1         | 3      | 0.76%   |
| Apricorn            | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 127       | 150    | 78.4%   |
| SSD  | 28        | 32     | 17.28%  |
| NVMe | 7         | 15     | 4.32%   |

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
| Detected | 685       | 1367   | 45.79%  |
| Works    | 653       | 1164   | 43.65%  |
| Malfunc  | 158       | 197    | 10.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 902       | 57.38%  |
| AMD                              | 252       | 16.03%  |
| Samsung Electronics              | 105       | 6.68%   |
| Sandisk                          | 39        | 2.48%   |
| Phison Electronics               | 30        | 1.91%   |
| SK hynix                         | 28        | 1.78%   |
| Nvidia                           | 27        | 1.72%   |
| ASMedia Technology               | 24        | 1.53%   |
| Kingston Technology Company      | 22        | 1.4%    |
| Marvell Technology Group         | 20        | 1.27%   |
| Toshiba America Info Systems     | 17        | 1.08%   |
| Silicon Motion                   | 15        | 0.95%   |
| JMicron Technology               | 14        | 0.89%   |
| Micron/Crucial Technology        | 10        | 0.64%   |
| KIOXIA                           | 10        | 0.64%   |
| Micron Technology                | 9         | 0.57%   |
| Silicon Integrated Systems [SiS] | 8         | 0.51%   |
| ADATA Technology                 | 7         | 0.45%   |
| VIA Technologies                 | 6         | 0.38%   |
| LSI Logic / Symbios Logic        | 4         | 0.25%   |
| Union Memory (Shenzhen)          | 3         | 0.19%   |
| Solid State Storage Technology   | 3         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.19%   |
| Hewlett-Packard                  | 3         | 0.19%   |
| Realtek Semiconductor            | 2         | 0.13%   |
| Silicon Image                    | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| Broadcom / LSI                   | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |
| 3ware                            | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 142       | 7.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 69        | 3.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 68        | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 51        | 2.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 49        | 2.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 47        | 2.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 46        | 2.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 42        | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 38        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 36        | 1.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 28        | 1.5%    |
| Samsung NVMe SSD Controller 980                                                         | 27        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 27        | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 26        | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 26        | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25        | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 21        | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 20        | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 20        | 1.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 18        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17        | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 17        | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 16        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 16        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 15        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 0.8%    |
| Intel SATA Controller [RAID mode]                                                       | 14        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 14        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 956       | 59.27%  |
| NVMe | 303       | 18.78%  |
| IDE  | 258       | 16%     |
| RAID | 88        | 5.46%   |
| SAS  | 6         | 0.37%   |
| SCSI | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1004      | 73.77%  |
| AMD          | 300       | 22.04%  |
| ARM          | 55        | 4.04%   |
| PowerBook5,6 | 1         | 0.07%   |
| CentaurHauls | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 45        | 3.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 11        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 8         | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.59%   |
| AMD Ryzen 5 3600 6-Core Processor             | 8         | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 7         | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.51%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.51%   |
| AMD Phenom II X4 B97 Processor                | 7         | 0.51%   |
| AMD FX-6300 Six-Core Processor                | 7         | 0.51%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.44%   |
| Intel Pentium 4 CPU 3.00GHz                   | 6         | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 6         | 0.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 6         | 0.44%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 6         | 0.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 6         | 0.44%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.44%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 6         | 0.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 6         | 0.44%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.37%   |
| Intel Pentium D CPU 2.80GHz                   | 5         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 270       | 19.84%  |
| Intel Core i7           | 200       | 14.7%   |
| Other                   | 110       | 8.08%   |
| Intel Core i3           | 105       | 7.71%   |
| Intel Celeron           | 80        | 5.88%   |
| Intel Core 2 Duo        | 67        | 4.92%   |
| AMD Ryzen 5             | 53        | 3.89%   |
| Intel Pentium           | 49        | 3.6%    |
| Intel Xeon              | 35        | 2.57%   |
| AMD Ryzen 7             | 32        | 2.35%   |
| Intel Atom              | 31        | 2.28%   |
| AMD FX                  | 24        | 1.76%   |
| Intel Pentium Dual-Core | 21        | 1.54%   |
| Intel Core 2 Quad       | 18        | 1.32%   |
| AMD Athlon II X2        | 18        | 1.32%   |
| AMD Ryzen 9             | 16        | 1.18%   |
| AMD Ryzen 3             | 14        | 1.03%   |
| AMD Phenom II X4        | 13        | 0.96%   |
| Intel Genuine           | 12        | 0.88%   |
| AMD A6                  | 12        | 0.88%   |
| Intel Pentium 4         | 10        | 0.73%   |
| AMD A8                  | 10        | 0.73%   |
| AMD A4                  | 10        | 0.73%   |
| Intel Core i9           | 8         | 0.59%   |
| Intel Core 2            | 8         | 0.59%   |
| AMD Athlon              | 8         | 0.59%   |
| ARM BCM                 | 7         | 0.51%   |
| Intel Pentium Dual      | 6         | 0.44%   |
| Intel Pentium D         | 6         | 0.44%   |
| AMD E                   | 6         | 0.44%   |
| Intel Pentium Silver    | 5         | 0.37%   |
| AMD Turion 64 X2 Mobile | 5         | 0.37%   |
| AMD Ryzen Threadripper  | 5         | 0.37%   |
| AMD Ryzen 7 PRO         | 5         | 0.37%   |
| AMD Athlon II X4        | 5         | 0.37%   |
| AMD Athlon 64 X2        | 5         | 0.37%   |
| AMD A10                 | 5         | 0.37%   |
| AMD E2                  | 4         | 0.29%   |
| AMD E1                  | 4         | 0.29%   |
| Intel Core m3           | 3         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 590       | 43.26%  |
| 4       | 504       | 36.95%  |
| 6       | 97        | 7.11%   |
| 8       | 65        | 4.77%   |
| 1       | 47        | 3.45%   |
| 12      | 17        | 1.25%   |
| 16      | 13        | 0.95%   |
| 3       | 12        | 0.88%   |
| 10      | 8         | 0.59%   |
| 24      | 3         | 0.22%   |
| 14      | 3         | 0.22%   |
| Unknown | 3         | 0.22%   |
| 32      | 2         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1331      | 97.72%  |
| 2       | 27        | 1.98%   |
| 4       | 2         | 0.15%   |
| Unknown | 2         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 749       | 54.91%  |
| 1       | 612       | 44.87%  |
| Unknown | 3         | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1295      | 95.08%  |
| Unknown        | 37        | 2.72%   |
| 32-bit         | 27        | 1.98%   |
| 64-bit         | 3         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 323       | 23.01%  |
| 0x306a9    | 91        | 6.48%   |
| 0x206a7    | 89        | 6.34%   |
| 0x306c3    | 72        | 5.13%   |
| 0x1067a    | 57        | 4.06%   |
| 0x806ec    | 28        | 1.99%   |
| 0x6fd      | 25        | 1.78%   |
| 0x010000c8 | 25        | 1.78%   |
| 0x506e3    | 24        | 1.71%   |
| 0x40651    | 24        | 1.71%   |
| 0x906e9    | 23        | 1.64%   |
| 0x806ea    | 23        | 1.64%   |
| 0x806c1    | 23        | 1.64%   |
| 0x906ea    | 22        | 1.57%   |
| 0x20655    | 20        | 1.42%   |
| 0x806e9    | 19        | 1.35%   |
| 0x406c4    | 19        | 1.35%   |
| 0x30678    | 19        | 1.35%   |
| 0x306d4    | 18        | 1.28%   |
| 0x406e3    | 16        | 1.14%   |
| 0x10676    | 16        | 1.14%   |
| 0x08108109 | 14        | 1%      |
| 0x706e5    | 13        | 0.93%   |
| 0x0a50000c | 13        | 0.93%   |
| 0x06000852 | 13        | 0.93%   |
| 0x706a1    | 12        | 0.85%   |
| 0x106e5    | 11        | 0.78%   |
| 0x6fb      | 10        | 0.71%   |
| 0x08701021 | 10        | 0.71%   |
| 0x06001119 | 10        | 0.71%   |
| 0xa0671    | 9         | 0.64%   |
| 0x906ed    | 9         | 0.64%   |
| 0x20652    | 9         | 0.64%   |
| 0x08600106 | 9         | 0.64%   |
| 0x05000119 | 9         | 0.64%   |
| 0x106ca    | 8         | 0.57%   |
| 0x0800820d | 8         | 0.57%   |
| 0xf41      | 7         | 0.5%    |
| 0x806d1    | 7         | 0.5%    |
| 0x706a8    | 7         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 164       | 12.02%  |
| Haswell          | 119       | 8.72%   |
| SandyBridge      | 118       | 8.65%   |
| IvyBridge        | 109       | 7.99%   |
| Penryn           | 85        | 6.23%   |
| Unknown          | 76        | 5.57%   |
| K10              | 53        | 3.89%   |
| Core             | 52        | 3.81%   |
| Silvermont       | 51        | 3.74%   |
| Skylake          | 49        | 3.59%   |
| Zen 2            | 42        | 3.08%   |
| Westmere         | 41        | 3.01%   |
| Zen+             | 33        | 2.42%   |
| Piledriver       | 32        | 2.35%   |
| Zen 3            | 28        | 2.05%   |
| Zen              | 28        | 2.05%   |
| IceLake          | 28        | 2.05%   |
| TigerLake        | 25        | 1.83%   |
| Goldmont plus    | 23        | 1.69%   |
| Broadwell        | 23        | 1.69%   |
| K8 Hammer        | 20        | 1.47%   |
| CometLake        | 20        | 1.47%   |
| Nehalem          | 19        | 1.39%   |
| NetBurst         | 18        | 1.32%   |
| Bonnell          | 18        | 1.32%   |
| Excavator        | 16        | 1.17%   |
| P6               | 14        | 1.03%   |
| Bobcat           | 11        | 0.81%   |
| Puma             | 9         | 0.66%   |
| Alderlake Hybrid | 8         | 0.59%   |
| Goldmont         | 7         | 0.51%   |
| Jaguar           | 6         | 0.44%   |
| Bulldozer        | 6         | 0.44%   |
| K8 & K10 hybrid  | 5         | 0.37%   |
| Steamroller      | 4         | 0.29%   |
| K10 Llano        | 2         | 0.15%   |
| Tremont          | 1         | 0.07%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 774       | 51.46%  |
| Nvidia                           | 366       | 24.34%  |
| AMD                              | 343       | 22.81%  |
| Matrox Electronics Systems       | 7         | 0.47%   |
| Silicon Integrated Systems [SiS] | 6         | 0.4%    |
| ASPEED Technology                | 5         | 0.33%   |
| VIA Technologies                 | 3         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 5.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 63        | 4.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42        | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 1.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 25        | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.55%   |
| Intel UHD Graphics 620                                                                   | 23        | 1.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 1.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23        | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 1.48%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 1.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.1%    |
| AMD Renoir                                                                               | 17        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 15        | 0.97%   |
| Intel HD Graphics 630                                                                    | 15        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 0.97%   |
| Intel HD Graphics 530                                                                    | 14        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.84%   |
| Intel HD Graphics 620                                                                    | 13        | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.77%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 12        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11        | 0.71%   |
| AMD RS880 [Radeon HD 4200]                                                               | 11        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 601       | 44.06%  |
| 1 x AMD                  | 274       | 20.09%  |
| 1 x Nvidia               | 224       | 16.42%  |
| Intel + Nvidia           | 122       | 8.94%   |
| Other                    | 56        | 4.11%   |
| Intel + AMD              | 35        | 2.57%   |
| 2 x AMD                  | 16        | 1.17%   |
| AMD + Nvidia             | 12        | 0.88%   |
| 1 x SiS                  | 6         | 0.44%   |
| 1 x Matrox               | 4         | 0.29%   |
| 1 x VIA                  | 3         | 0.22%   |
| Nvidia + Matrox          | 3         | 0.22%   |
| 2 x Nvidia               | 2         | 0.15%   |
| 1 x ASPEED               | 2         | 0.15%   |
| AMD + ASPEED             | 2         | 0.15%   |
| Nvidia + ASPEED          | 1         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1042      | 75.95%  |
| Proprietary | 229       | 16.69%  |
| Unknown     | 101       | 7.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 790       | 56.92%  |
| 1.01-2.0   | 173       | 12.46%  |
| 0.01-0.5   | 171       | 12.32%  |
| 0.51-1.0   | 112       | 8.07%   |
| 3.01-4.0   | 75        | 5.4%    |
| 7.01-8.0   | 37        | 2.67%   |
| 5.01-6.0   | 17        | 1.22%   |
| 2.01-3.0   | 7         | 0.5%    |
| 16.01-24.0 | 3         | 0.22%   |
| 8.01-16.0  | 2         | 0.14%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 212       | 14.89%  |
| AU Optronics            | 146       | 10.25%  |
| Dell                    | 131       | 9.2%    |
| LG Display              | 117       | 8.22%   |
| Chimei Innolux          | 97        | 6.81%   |
| BOE                     | 83        | 5.83%   |
| Goldstar                | 82        | 5.76%   |
| Hewlett-Packard         | 63        | 4.42%   |
| Acer                    | 49        | 3.44%   |
| Philips                 | 45        | 3.16%   |
| BenQ                    | 30        | 2.11%   |
| Ancor Communications    | 30        | 2.11%   |
| AOC                     | 27        | 1.9%    |
| Chi Mei Optoelectronics | 25        | 1.76%   |
| ViewSonic               | 18        | 1.26%   |
| Sharp                   | 16        | 1.12%   |
| Iiyama                  | 16        | 1.12%   |
| Apple                   | 16        | 1.12%   |
| Lenovo                  | 15        | 1.05%   |
| Unknown                 | 13        | 0.91%   |
| PANDA                   | 13        | 0.91%   |
| Sony                    | 12        | 0.84%   |
| LG Philips              | 9         | 0.63%   |
| LG Electronics          | 9         | 0.63%   |
| ASUSTek Computer        | 9         | 0.63%   |
| HannStar                | 8         | 0.56%   |
| NEC Computers           | 7         | 0.49%   |
| Eizo                    | 7         | 0.49%   |
| Vizio                   | 6         | 0.42%   |
| InfoVision              | 6         | 0.42%   |
| Fujitsu Siemens         | 6         | 0.42%   |
| Toshiba                 | 4         | 0.28%   |
| Packard Bell            | 4         | 0.28%   |
| Medion                  | 4         | 0.28%   |
| Gateway                 | 4         | 0.28%   |
| Belinea                 | 4         | 0.28%   |
| Sceptre Tech            | 3         | 0.21%   |
| RTK                     | 3         | 0.21%   |
| Panasonic               | 3         | 0.21%   |
| LGD                     | 3         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                        | 31        | 2.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 11        | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.41%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.34%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                        | 5         | 0.34%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch            | 4         | 0.27%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 4         | 0.27%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.27%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 4         | 0.27%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.27%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 4         | 0.27%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 3         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 3         | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.2%    |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.2%    |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch              | 3         | 0.2%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 3         | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 3         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.2%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.2%    |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                     | 3         | 0.2%    |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                    | 3         | 0.2%    |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                        | 3         | 0.2%    |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 3         | 0.2%    |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                        | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 520       | 38.1%   |
| 1366x768 (WXGA)    | 268       | 19.63%  |
| 1280x1024 (SXGA)   | 113       | 8.28%   |
| 1600x900 (HD+)     | 65        | 4.76%   |
| 3840x2160 (4K)     | 64        | 4.69%   |
| 2560x1440 (QHD)    | 49        | 3.59%   |
| 1680x1050 (WSXGA+) | 43        | 3.15%   |
| 1440x900 (WXGA+)   | 40        | 2.93%   |
| 1920x1200 (WUXGA)  | 35        | 2.56%   |
| 1280x800 (WXGA)    | 34        | 2.49%   |
| 1360x768           | 23        | 1.68%   |
| Unknown            | 20        | 1.47%   |
| 1024x600           | 12        | 0.88%   |
| 3440x1440          | 11        | 0.81%   |
| 3840x1080          | 9         | 0.66%   |
| 1600x1200          | 9         | 0.66%   |
| 2560x1600          | 6         | 0.44%   |
| 2560x1080          | 4         | 0.29%   |
| 1024x768 (XGA)     | 4         | 0.29%   |
| 2160x1440          | 3         | 0.22%   |
| 1280x720 (HD)      | 3         | 0.22%   |
| 3840x2400          | 2         | 0.15%   |
| 3840x1200          | 2         | 0.15%   |
| 3200x1800 (QHD+)   | 2         | 0.15%   |
| 2880x1800          | 2         | 0.15%   |
| 1920x540           | 2         | 0.15%   |
| 1920x1280          | 2         | 0.15%   |
| 1400x1050          | 2         | 0.15%   |
| 6400x1080          | 1         | 0.07%   |
| 5840x1440          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 5040x1050          | 1         | 0.07%   |
| 4240x1440          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3520x1200          | 1         | 0.07%   |
| 3200x1080          | 1         | 0.07%   |
| 3000x1920          | 1         | 0.07%   |
| 2880x900           | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 309       | 21.87%  |
| 17      | 147       | 10.4%   |
| 14      | 100       | 7.08%   |
| 13      | 96        | 6.79%   |
| 24      | 90        | 6.37%   |
| 21      | 89        | 6.3%    |
| 23      | 85        | 6.02%   |
| 27      | 83        | 5.87%   |
| Unknown | 83        | 5.87%   |
| 19      | 51        | 3.61%   |
| 18      | 39        | 2.76%   |
| 31      | 31        | 2.19%   |
| 22      | 29        | 2.05%   |
| 12      | 24        | 1.7%    |
| 20      | 22        | 1.56%   |
| 11      | 21        | 1.49%   |
| 10      | 16        | 1.13%   |
| 34      | 14        | 0.99%   |
| 72      | 10        | 0.71%   |
| 84      | 9         | 0.64%   |
| 40      | 9         | 0.64%   |
| 32      | 7         | 0.5%    |
| 25      | 6         | 0.42%   |
| 46      | 5         | 0.35%   |
| 54      | 4         | 0.28%   |
| 52      | 4         | 0.28%   |
| 42      | 4         | 0.28%   |
| 33      | 4         | 0.28%   |
| 16      | 4         | 0.28%   |
| 36      | 3         | 0.21%   |
| 38      | 2         | 0.14%   |
| 74      | 1         | 0.07%   |
| 65      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 57      | 1         | 0.07%   |
| 49      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 41      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 523       | 37.52%  |
| 501-600     | 241       | 17.29%  |
| 401-500     | 197       | 14.13%  |
| 351-400     | 115       | 8.25%   |
| 201-300     | 107       | 7.68%   |
| Unknown     | 83        | 5.95%   |
| 601-700     | 43        | 3.08%   |
| 701-800     | 28        | 2.01%   |
| 1501-2000   | 20        | 1.43%   |
| 1001-1500   | 19        | 1.36%   |
| 801-900     | 12        | 0.86%   |
| 901-1000    | 5         | 0.36%   |
| 101-200     | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 915       | 70.55%  |
| 16/10   | 158       | 12.18%  |
| 5/4     | 101       | 7.79%   |
| Unknown | 70        | 5.4%    |
| 4/3     | 17        | 1.31%   |
| 21/9    | 15        | 1.16%   |
| 3/2     | 14        | 1.08%   |
| 6/5     | 4         | 0.31%   |
| 32/9    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 300       | 21.41%  |
| 201-250        | 226       | 16.13%  |
| 81-90          | 153       | 10.92%  |
| 141-150        | 110       | 7.85%   |
| 151-200        | 98        | 7%      |
| 301-350        | 83        | 5.92%   |
| Unknown        | 83        | 5.92%   |
| 351-500        | 57        | 4.07%   |
| 121-130        | 57        | 4.07%   |
| 251-300        | 44        | 3.14%   |
| 71-80          | 40        | 2.86%   |
| More than 1000 | 32        | 2.28%   |
| 501-1000       | 27        | 1.93%   |
| 61-70          | 24        | 1.71%   |
| 51-60          | 21        | 1.5%    |
| 41-50          | 16        | 1.14%   |
| 131-140        | 14        | 1%      |
| 111-120        | 8         | 0.57%   |
| 91-100         | 7         | 0.5%    |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 530       | 38.77%  |
| 101-120       | 358       | 26.19%  |
| 121-160       | 282       | 20.63%  |
| Unknown       | 83        | 6.07%   |
| 161-240       | 57        | 4.17%   |
| 1-50          | 40        | 2.93%   |
| More than 240 | 17        | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1087      | 79.11%  |
| 2     | 199       | 14.48%  |
| 0     | 66        | 4.8%    |
| 3     | 21        | 1.53%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 700       | 35.43%  |
| Intel                             | 606       | 30.67%  |
| Qualcomm Atheros                  | 218       | 11.03%  |
| Broadcom                          | 131       | 6.63%   |
| Broadcom Limited                  | 39        | 1.97%   |
| Marvell Technology Group          | 26        | 1.32%   |
| Ralink Technology                 | 25        | 1.27%   |
| Ralink                            | 25        | 1.27%   |
| Nvidia                            | 23        | 1.16%   |
| TP-Link                           | 21        | 1.06%   |
| MediaTek                          | 12        | 0.61%   |
| Qualcomm Atheros Communications   | 10        | 0.51%   |
| ASIX Electronics                  | 10        | 0.51%   |
| Sierra Wireless                   | 8         | 0.4%    |
| Microchip Technology              | 8         | 0.4%    |
| Aquantia                          | 8         | 0.4%    |
| Silicon Integrated Systems [SiS]  | 7         | 0.35%   |
| ASUSTek Computer                  | 7         | 0.35%   |
| Xiaomi                            | 6         | 0.3%    |
| NetGear                           | 6         | 0.3%    |
| D-Link                            | 6         | 0.3%    |
| Attansic Technology               | 6         | 0.3%    |
| Ericsson Business Mobile Networks | 5         | 0.25%   |
| VIA Technologies                  | 4         | 0.2%    |
| Huawei Technologies               | 4         | 0.2%    |
| Edimax Technology                 | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| Samsung Electronics               | 3         | 0.15%   |
| Hewlett-Packard                   | 3         | 0.15%   |
| Dell                              | 3         | 0.15%   |
| QLogic                            | 2         | 0.1%    |
| Microsoft                         | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| Lenovo                            | 2         | 0.1%    |
| JMicron Technology                | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |
| DisplayLink                       | 2         | 0.1%    |
| Belkin Components                 | 2         | 0.1%    |
| ZyDAS                             | 1         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 459       | 19.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 102       | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 70        | 3.02%   |
| Intel Wi-Fi 6 AX200                                                     | 39        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 31        | 1.34%   |
| Intel Wireless 7265                                                     | 31        | 1.34%   |
| Intel Ethernet Connection I217-LM                                       | 31        | 1.34%   |
| Intel Wireless 7260                                                     | 28        | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.17%   |
| Intel Wireless 8265 / 8275                                              | 26        | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                       | 23        | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 22        | 0.95%   |
| Intel Wireless 3165                                                     | 22        | 0.95%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 0.91%   |
| Intel I211 Gigabit Network Connection                                   | 20        | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 0.82%   |
| Intel Ethernet Controller I225-V                                        | 19        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 16        | 0.69%   |
| Intel Wireless 8260                                                     | 15        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 0.65%   |
| Realtek 802.11ac NIC                                                    | 14        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 14        | 0.6%    |
| Nvidia MCP61 Ethernet                                                   | 14        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 13        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.52%   |
| Intel 82574L Gigabit Network Connection                                 | 12        | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.47%   |
| Intel Ethernet Connection I217-V                                        | 11        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                    | 11        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 421       | 42.02%  |
| Realtek Semiconductor           | 180       | 17.96%  |
| Qualcomm Atheros                | 169       | 16.87%  |
| Broadcom                        | 65        | 6.49%   |
| Ralink Technology               | 25        | 2.5%    |
| Ralink                          | 25        | 2.5%    |
| Broadcom Limited                | 24        | 2.4%    |
| TP-Link                         | 21        | 2.1%    |
| MediaTek                        | 11        | 1.1%    |
| Qualcomm Atheros Communications | 10        | 1%      |
| Sierra Wireless                 | 8         | 0.8%    |
| ASUSTek Computer                | 7         | 0.7%    |
| NetGear                         | 6         | 0.6%    |
| Edimax Technology               | 4         | 0.4%    |
| D-Link                          | 4         | 0.4%    |
| Microsoft                       | 2         | 0.2%    |
| Linksys                         | 2         | 0.2%    |
| Fibocom                         | 2         | 0.2%    |
| Dell                            | 2         | 0.2%    |
| Belkin Components               | 2         | 0.2%    |
| ZyDAS                           | 1         | 0.1%    |
| Xiaomi                          | 1         | 0.1%    |
| U.S. Robotics                   | 1         | 0.1%    |
| Sitecom Europe                  | 1         | 0.1%    |
| Realtek                         | 1         | 0.1%    |
| Quectel Wireless Solutions      | 1         | 0.1%    |
| Qualcomm                        | 1         | 0.1%    |
| IMC Networks                    | 1         | 0.1%    |
| Hewlett-Packard                 | 1         | 0.1%    |
| Gemtek                          | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| AVM                             | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 39        | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 3.18%   |
| Intel Wireless 7265                                                     | 31        | 3.08%   |
| Intel Wireless 7260                                                     | 28        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.68%   |
| Intel Wireless 8265 / 8275                                              | 26        | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 2.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 22        | 2.19%   |
| Intel Wireless 3165                                                     | 22        | 2.19%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.79%   |
| Intel Wireless 8260                                                     | 15        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.49%   |
| Realtek 802.11ac NIC                                                    | 14        | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.09%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 10        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 10        | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.99%   |
| Intel Wireless 3160                                                     | 9         | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 9         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 617       | 49.52%  |
| Intel                            | 350       | 28.09%  |
| Qualcomm Atheros                 | 72        | 5.78%   |
| Broadcom                         | 72        | 5.78%   |
| Marvell Technology Group         | 26        | 2.09%   |
| Nvidia                           | 23        | 1.85%   |
| Broadcom Limited                 | 16        | 1.28%   |
| ASIX Electronics                 | 10        | 0.8%    |
| Microchip Technology             | 8         | 0.64%   |
| Aquantia                         | 8         | 0.64%   |
| Silicon Integrated Systems [SiS] | 6         | 0.48%   |
| Attansic Technology              | 6         | 0.48%   |
| Xiaomi                           | 5         | 0.4%    |
| VIA Technologies                 | 4         | 0.32%   |
| Huawei Technologies              | 3         | 0.24%   |
| D-Link System                    | 3         | 0.24%   |
| Samsung Electronics              | 2         | 0.16%   |
| QLogic                           | 2         | 0.16%   |
| Lenovo                           | 2         | 0.16%   |
| JMicron Technology               | 2         | 0.16%   |
| DisplayLink                      | 2         | 0.16%   |
| D-Link                           | 2         | 0.16%   |
| Netchip Technology               | 1         | 0.08%   |
| Motorola PCS                     | 1         | 0.08%   |
| Mellanox Technologies            | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 459       | 35.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 102       | 7.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 2.41%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 20        | 1.56%   |
| Intel Ethernet Controller I225-V                                  | 19        | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 16        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 1.09%   |
| Nvidia MCP61 Ethernet                                             | 14        | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 8         | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 7         | 0.55%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 7         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.55%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 6         | 0.47%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 6         | 0.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1185      | 55.12%  |
| WiFi     | 940       | 43.72%  |
| Modem    | 23        | 1.07%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 727       | 52.72%  |
| Ethernet | 652       | 47.28%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 710       | 51.86%  |
| 1     | 556       | 40.61%  |
| 0     | 68        | 4.97%   |
| 3     | 23        | 1.68%   |
| 4     | 8         | 0.58%   |
| 6     | 2         | 0.15%   |
| 14    | 1         | 0.07%   |
| 5     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1154      | 83.99%  |
| Yes     | 219       | 15.94%  |
| Unknown | 1         | 0.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 329       | 46.14%  |
| Realtek Semiconductor           | 71        | 9.96%   |
| Broadcom                        | 58        | 8.13%   |
| Qualcomm Atheros Communications | 50        | 7.01%   |
| Cambridge Silicon Radio         | 44        | 6.17%   |
| IMC Networks                    | 25        | 3.51%   |
| Lite-On Technology              | 22        | 3.09%   |
| Dell                            | 22        | 3.09%   |
| Foxconn / Hon Hai               | 17        | 2.38%   |
| Apple                           | 17        | 2.38%   |
| ASUSTek Computer                | 12        | 1.68%   |
| Hewlett-Packard                 | 10        | 1.4%    |
| Ralink                          | 8         | 1.12%   |
| Toshiba                         | 5         | 0.7%    |
| MediaTek                        | 4         | 0.56%   |
| Foxconn International           | 3         | 0.42%   |
| Belkin Components               | 3         | 0.42%   |
| TP-Link                         | 2         | 0.28%   |
| Ralink Technology               | 2         | 0.28%   |
| Integrated System Solution      | 2         | 0.28%   |
| Alps Electric                   | 2         | 0.28%   |
| TRENDnet                        | 1         | 0.14%   |
| Smart Modular Technologies      | 1         | 0.14%   |
| Qcom                            | 1         | 0.14%   |
| Conwise Technology              | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 126       | 17.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 61        | 8.56%   |
| Intel AX201 Bluetooth                               | 57        | 7.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44        | 6.17%   |
| Realtek Bluetooth Radio                             | 42        | 5.89%   |
| Intel AX200 Bluetooth                               | 38        | 5.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 3.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 2.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.96%   |
| Dell DW375 Bluetooth Module                         | 14        | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 1.68%   |
| IMC Networks Bluetooth Device                       | 12        | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 1.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.26%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 1.12%   |
| Intel AX210 Bluetooth                               | 8         | 1.12%   |
| IMC Networks Bluetooth Radio                        | 7         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.98%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 0.98%   |
| Lite-On Bluetooth Device                            | 6         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.84%   |
| Apple Bluetooth HCI                                 | 6         | 0.84%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.7%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 5         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.7%    |
| Broadcom HP Portable SoftSailing                    | 5         | 0.7%    |
| MediaTek Wireless_Device                            | 4         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.56%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.56%   |
| Intel Bluetooth Device                              | 3         | 0.42%   |
| IMC Networks Wireless_Device                        | 3         | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 960       | 54.05%  |
| AMD                                            | 348       | 19.59%  |
| Nvidia                                         | 294       | 16.55%  |
| C-Media Electronics                            | 35        | 1.97%   |
| Logitech                                       | 11        | 0.62%   |
| Realtek Semiconductor                          | 9         | 0.51%   |
| Creative Labs                                  | 9         | 0.51%   |
| Silicon Integrated Systems [SiS]               | 8         | 0.45%   |
| JMTek                                          | 7         | 0.39%   |
| GN Netcom                                      | 7         | 0.39%   |
| Generalplus Technology                         | 6         | 0.34%   |
| ASUSTek Computer                               | 6         | 0.34%   |
| Hewlett-Packard                                | 5         | 0.28%   |
| Corsair                                        | 5         | 0.28%   |
| VIA Technologies                               | 4         | 0.23%   |
| Plantronics                                    | 4         | 0.23%   |
| Lenovo                                         | 4         | 0.23%   |
| Kingston Technology                            | 4         | 0.23%   |
| Razer USA                                      | 3         | 0.17%   |
| Focusrite-Novation                             | 3         | 0.17%   |
| Creative Technology                            | 3         | 0.17%   |
| Cambridge Silicon Radio                        | 3         | 0.17%   |
| Thesycon Systemsoftware & Consulting           | 2         | 0.11%   |
| Tenx Technology                                | 2         | 0.11%   |
| Sony                                           | 2         | 0.11%   |
| Meizu                                          | 2         | 0.11%   |
| Jieli Technology                               | 2         | 0.11%   |
| Dell                                           | 2         | 0.11%   |
| D&M Holdings (Denon/Marantz)                   | 2         | 0.11%   |
| Conexant Systems                               | 2         | 0.11%   |
| BEHRINGER International                        | 2         | 0.11%   |
| Alesis                                         | 2         | 0.11%   |
| XMOS                                           | 1         | 0.06%   |
| Texas Instruments                              | 1         | 0.06%   |
| TerraTec Electronic                            | 1         | 0.06%   |
| SteelSeries ApS                                | 1         | 0.06%   |
| SmartAction                                    | 1         | 0.06%   |
| Siemens Information and Communication Products | 1         | 0.06%   |
| Sennheiser Communications                      | 1         | 0.06%   |
| No brand                                       | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 109       | 5.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 108       | 5.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 86        | 4.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 84        | 4.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 74        | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 3.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 64        | 3.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 64        | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 38        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 37        | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 37        | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 36        | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 30        | 1.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 29        | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 1.34%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 1.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 25        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 24        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 23        | 1.1%    |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 1.05%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 20        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 0.91%   |
| Intel 200 Series PCH HD Audio                                                                     | 19        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 19        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 18        | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 17        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 16        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 185       | 18.76%  |
| SK hynix                                         | 154       | 15.62%  |
| Kingston                                         | 135       | 13.69%  |
| Unknown                                          | 123       | 12.47%  |
| Micron Technology                                | 90        | 9.13%   |
| Crucial                                          | 65        | 6.59%   |
| Corsair                                          | 52        | 5.27%   |
| G.Skill                                          | 30        | 3.04%   |
| Ramaxel Technology                               | 23        | 2.33%   |
| Nanya Technology                                 | 22        | 2.23%   |
| Elpida                                           | 15        | 1.52%   |
| Unknown (ABCD)                                   | 13        | 1.32%   |
| A-DATA Technology                                | 13        | 1.32%   |
| Smart                                            | 11        | 1.12%   |
| Team                                             | 8         | 0.81%   |
| Teikon                                           | 5         | 0.51%   |
| Patriot                                          | 5         | 0.51%   |
| Qimonda                                          | 3         | 0.3%    |
| HBS                                              | 3         | 0.3%    |
| GOODRAM                                          | 3         | 0.3%    |
| Unknown                                          | 3         | 0.3%    |
| Transcend                                        | 2         | 0.2%    |
| Silicon Power                                    | 2         | 0.2%    |
| Netlist                                          | 2         | 0.2%    |
| Atermiter                                        | 2         | 0.2%    |
| Unknown (9B0D)                                   | 1         | 0.1%    |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.1%    |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.1%    |
| Unknown (0x0C26)                                 | 1         | 0.1%    |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.1%    |
| Unifosa                                          | 1         | 0.1%    |
| Toshiba                                          | 1         | 0.1%    |
| Timetec                                          | 1         | 0.1%    |
| Neo Forza                                        | 1         | 0.1%    |
| Kreton                                           | 1         | 0.1%    |
| Hewlett-Packard                                  | 1         | 0.1%    |
| Goldenmars                                       | 1         | 0.1%    |
| Golden Empire                                    | 1         | 0.1%    |
| GeIL                                             | 1         | 0.1%    |
| Eluktro                                          | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 8         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 6         | 0.57%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.57%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 6         | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 5         | 0.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.38%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 4         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.38%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.38%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.38%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                     | 4         | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 4         | 0.38%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 4         | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 4         | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.28%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 344       | 40.14%  |
| DDR4    | 321       | 37.46%  |
| DDR2    | 64        | 7.47%   |
| SDRAM   | 34        | 3.97%   |
| Unknown | 28        | 3.27%   |
| LPDDR4  | 24        | 2.8%    |
| LPDDR3  | 18        | 2.1%    |
| DDR     | 15        | 1.75%   |
| DDR5    | 5         | 0.58%   |
| DRAM    | 3         | 0.35%   |
| LPDDR5  | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 467       | 54.88%  |
| DIMM         | 334       | 39.25%  |
| Row Of Chips | 43        | 5.05%   |
| Chip         | 4         | 0.47%   |
| Unknown      | 2         | 0.24%   |
| RIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 288       | 30.93%  |
| 8192  | 284       | 30.5%   |
| 2048  | 154       | 16.54%  |
| 16384 | 131       | 14.07%  |
| 1024  | 34        | 3.65%   |
| 32768 | 33        | 3.54%   |
| 512   | 4         | 0.43%   |
| 1536  | 1         | 0.11%   |
| 256   | 1         | 0.11%   |
| 32    | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 214       | 23.41%  |
| 3200    | 115       | 12.58%  |
| 2667    | 98        | 10.72%  |
| 1333    | 87        | 9.52%   |
| 2400    | 68        | 7.44%   |
| 1334    | 36        | 3.94%   |
| 2133    | 34        | 3.72%   |
| 800     | 32        | 3.5%    |
| 667     | 32        | 3.5%    |
| Unknown | 27        | 2.95%   |
| 1066    | 15        | 1.64%   |
| 3266    | 12        | 1.31%   |
| 1067    | 11        | 1.2%    |
| 3600    | 10        | 1.09%   |
| 1867    | 10        | 1.09%   |
| 533     | 10        | 1.09%   |
| 4199    | 8         | 0.88%   |
| 2048    | 8         | 0.88%   |
| 3400    | 7         | 0.77%   |
| 4267    | 5         | 0.55%   |
| 3000    | 5         | 0.55%   |
| 2933    | 5         | 0.55%   |
| 3800    | 4         | 0.44%   |
| 2800    | 4         | 0.44%   |
| 1866    | 4         | 0.44%   |
| 975     | 4         | 0.44%   |
| 49926   | 3         | 0.33%   |
| 4800    | 3         | 0.33%   |
| 3533    | 3         | 0.33%   |
| 2666    | 3         | 0.33%   |
| 1800    | 3         | 0.33%   |
| 400     | 3         | 0.33%   |
| 266     | 3         | 0.33%   |
| 8400    | 2         | 0.22%   |
| 6400    | 2         | 0.22%   |
| 3866    | 2         | 0.22%   |
| 3733    | 2         | 0.22%   |
| 3534    | 2         | 0.22%   |
| 3466    | 2         | 0.22%   |
| 3100    | 2         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 17        | 30.91%  |
| Brother Industries     | 9         | 16.36%  |
| Samsung Electronics    | 7         | 12.73%  |
| Seiko Epson            | 5         | 9.09%   |
| Canon                  | 5         | 9.09%   |
| Dymo-CoStar            | 4         | 7.27%   |
| QinHeng Electronics    | 2         | 3.64%   |
| STMicroelectronics     | 1         | 1.82%   |
| Prolific Technology    | 1         | 1.82%   |
| Panasonic (Matsushita) | 1         | 1.82%   |
| Lexmark International  | 1         | 1.82%   |
| Graphtec America       | 1         | 1.82%   |
| BIXOLON                | 1         | 1.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother Printer                                           | 3         | 5.36%   |
| Seiko Epson Printer                                       | 2         | 3.57%   |
| Samsung SCX-4200 series                                   | 2         | 3.57%   |
| Samsung M2020 Series                                      | 2         | 3.57%   |
| QinHeng CH340S                                            | 2         | 3.57%   |
| HP LaserJet Professional P1102w                           | 2         | 3.57%   |
| HP LaserJet Professional P 1102w                          | 2         | 3.57%   |
| HP Deskjet F4500 series                                   | 2         | 3.57%   |
| HP DeskJet 2700 series                                    | 2         | 3.57%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 3.57%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.79%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.79%   |
| Seiko Epson WF-2010 Series                                | 1         | 1.79%   |
| Seiko Epson L310 Series                                   | 1         | 1.79%   |
| Samsung M2070 Series                                      | 1         | 1.79%   |
| Samsung CLX-8380 Series                                   | 1         | 1.79%   |
| Samsung CLX-4190 Series                                   | 1         | 1.79%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.79%   |
| Panasonic (Matsushita) KX-MB2130RU                        | 1         | 1.79%   |
| Lexmark International InkJet Color Printer                | 1         | 1.79%   |
| HP Officejet 4500 G510a-f                                 | 1         | 1.79%   |
| HP LaserJet 1022                                          | 1         | 1.79%   |
| HP LaserJet 1020                                          | 1         | 1.79%   |
| HP DeskJet F300 series                                    | 1         | 1.79%   |
| HP DeskJet 845c                                           | 1         | 1.79%   |
| HP Deskjet 3050 J610 series                               | 1         | 1.79%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.79%   |
| HP DeskJet 2130 series                                    | 1         | 1.79%   |
| HP color LaserJet 4650                                    | 1         | 1.79%   |
| Graphtec America Graphtec Printer                         | 1         | 1.79%   |
| Dymo-CoStar LabelWriter 310                               | 1         | 1.79%   |
| Dymo-CoStar DYMO LabelWriter 320                          | 1         | 1.79%   |
| Canon PIXMA MG2500 Series                                 | 1         | 1.79%   |
| Canon Pixma iP4500 Printer                                | 1         | 1.79%   |
| Canon LiDE 400                                            | 1         | 1.79%   |
| Canon LBP7010C/7018C                                      | 1         | 1.79%   |
| Canon LaserShot LBP-1120 Printer                          | 1         | 1.79%   |
| Brother MFC-L2710DN series                                | 1         | 1.79%   |
| Brother HL-3170CDW series                                 | 1         | 1.79%   |
| Brother HL-3140CW series                                  | 1         | 1.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 6         | 40%     |
| Seiko Epson                                    | 5         | 33.33%  |
| Hewlett-Packard                                | 2         | 13.33%  |
| Siemens Information and Communication Products | 1         | 6.67%   |
| Acer Peripherals (now BenQ)                    | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                         | 2         | 13.33%  |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 6.67%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                | 1         | 6.67%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                               | 1         | 6.67%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 6.67%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                            | 1         | 6.67%   |
| Seiko Epson ES-D400 [GT-S80]                                                    | 1         | 6.67%   |
| HP ScanJet G4010                                                                | 1         | 6.67%   |
| HP ScanJet 4370                                                                 | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                                          | 1         | 6.67%   |
| Canon CanoScan LiDE 210                                                         | 1         | 6.67%   |
| Canon CanoScan LiDE 120                                                         | 1         | 6.67%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                     | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 181       | 24.86%  |
| Microdia                               | 61        | 8.38%   |
| IMC Networks                           | 49        | 6.73%   |
| Realtek Semiconductor                  | 46        | 6.32%   |
| Logitech                               | 45        | 6.18%   |
| Bison Electronics                      | 39        | 5.36%   |
| Sunplus Innovation Technology          | 34        | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 4.4%    |
| Quanta                                 | 30        | 4.12%   |
| Suyin                                  | 21        | 2.88%   |
| Acer                                   | 21        | 2.88%   |
| Syntek                                 | 18        | 2.47%   |
| Ricoh                                  | 17        | 2.34%   |
| Apple                                  | 17        | 2.34%   |
| Silicon Motion                         | 13        | 1.79%   |
| Lite-On Technology                     | 12        | 1.65%   |
| Luxvisions Innotech Limited            | 8         | 1.1%    |
| Samsung Electronics                    | 7         | 0.96%   |
| Alcor Micro                            | 7         | 0.96%   |
| Importek                               | 6         | 0.82%   |
| Z-Star Microelectronics                | 5         | 0.69%   |
| Lenovo                                 | 5         | 0.69%   |
| Microsoft                              | 4         | 0.55%   |
| Generalplus Technology                 | 4         | 0.55%   |
| ARC International                      | 4         | 0.55%   |
| Primax Electronics                     | 3         | 0.41%   |
| KYE Systems (Mouse Systems)            | 3         | 0.41%   |
| Creative Technology                    | 3         | 0.41%   |
| ALi                                    | 3         | 0.41%   |
| Sunplus Technology                     | 2         | 0.27%   |
| Ruision                                | 2         | 0.27%   |
| Razer USA                              | 2         | 0.27%   |
| LG Electronics                         | 2         | 0.27%   |
| DigiTech                               | 2         | 0.27%   |
| Cubeternet                             | 2         | 0.27%   |
| Aveo Technology                        | 2         | 0.27%   |
| Y Media                                | 1         | 0.14%   |
| Unknown                                | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| Sunplus IT                             | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 30        | 4.1%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 16        | 2.19%   |
| Bison Integrated Camera                                 | 15        | 2.05%   |
| Realtek Integrated_Webcam_HD                            | 14        | 1.91%   |
| Chicony HD WebCam                                       | 13        | 1.78%   |
| Microdia Integrated_Webcam_HD                           | 12        | 1.64%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 1.37%   |
| Logitech Webcam C270                                    | 10        | 1.37%   |
| IMC Networks Integrated Camera                          | 10        | 1.37%   |
| Chicony USB2.0 Camera                                   | 10        | 1.37%   |
| Syntek Integrated Camera                                | 9         | 1.23%   |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 1.23%   |
| Chicony HP HD Camera                                    | 9         | 1.23%   |
| Samsung Galaxy A5 (MTP)                                 | 7         | 0.96%   |
| Microdia Webcam Vitade AF                               | 7         | 0.96%   |
| Microdia Integrated Webcam                              | 7         | 0.96%   |
| Logitech HD Pro Webcam C920                             | 7         | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 7         | 0.96%   |
| Ricoh HD Webcam                                         | 6         | 0.82%   |
| Realtek USB Camera                                      | 6         | 0.82%   |
| Quanta HD User Facing                                   | 6         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 6         | 0.82%   |
| Chicony USB 2.0 Camera                                  | 6         | 0.82%   |
| Chicony HP Webcam                                       | 6         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 6         | 0.82%   |
| Suyin HP TrueVision HD Integrated Webcam                | 5         | 0.68%   |
| Chicony VGA Webcam                                      | 5         | 0.68%   |
| Chicony Integrated IR Camera                            | 5         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 5         | 0.68%   |
| Acer Integrated Camera                                  | 5         | 0.68%   |
| Syntek Lenovo EasyCamera                                | 4         | 0.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 4         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 4         | 0.55%   |
| Quanta HP HD Camera                                     | 4         | 0.55%   |
| IMC Networks UVC VGA Webcam                             | 4         | 0.55%   |
| Chicony Webcam                                          | 4         | 0.55%   |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 0.55%   |
| Chicony HP Truevision HD camera                         | 4         | 0.55%   |
| Chicony HP Truevision HD                                | 4         | 0.55%   |
| Chicony FJ Camera                                       | 4         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 40%     |
| Synaptics                  | 30        | 23.08%  |
| Shenzhen Goodix Technology | 16        | 12.31%  |
| Upek                       | 9         | 6.92%   |
| Elan Microelectronics      | 8         | 6.15%   |
| AuthenTec                  | 6         | 4.62%   |
| LighTuning Technology      | 4         | 3.08%   |
| STMicroelectronics         | 3         | 2.31%   |
| Samsung Electronics        | 1         | 0.77%   |
| Focal-systems.Corp         | 1         | 0.77%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 6.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 6.15%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.15%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 6.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.38%   |
| Validity Sensors VFS491                                                    | 5         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.85%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.08%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.08%   |
| Elan ELAN:ARM-M4                                                           | 4         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.31%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.31%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.31%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.31%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.54%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.54%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.54%   |
| Synaptics WBDI                                                             | 2         | 1.54%   |
| Synaptics UWP WBDI                                                         | 2         | 1.54%   |
| Synaptics  WBDI                                                            | 2         | 1.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.54%   |
| AuthenTec AES1600                                                          | 2         | 1.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.77%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.77%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.77%   |
| Synaptics WBDI Device                                                      | 1         | 0.77%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.77%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.77%   |
| Samsung Fingerprint Device                                                 | 1         | 0.77%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.77%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 40        | 49.38%  |
| Alcor Micro           | 19        | 23.46%  |
| Upek                  | 4         | 4.94%   |
| O2 Micro              | 4         | 4.94%   |
| Lenovo                | 3         | 3.7%    |
| Advanced Card Systems | 3         | 3.7%    |
| SCM Microsystems      | 2         | 2.47%   |
| Gemalto (was Gemplus) | 2         | 2.47%   |
| Realtek Semiconductor | 1         | 1.23%   |
| OmniKey               | 1         | 1.23%   |
| Kobil Systems         | 1         | 1.23%   |
| Chicony Electronics   | 1         | 1.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 23.46%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 18.52%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 16.05%  |
| Broadcom 58200                                                               | 8         | 9.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 4.94%   |
| Broadcom 5880                                                                | 4         | 4.94%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.7%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 2.47%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.47%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.23%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.23%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.23%   |
| OmniKey CardMan 1021                                                         | 1         | 1.23%   |
| Kobil Systems Smart Token                                                    | 1         | 1.23%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.23%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1011      | 73.31%  |
| 1     | 295       | 21.39%  |
| 2     | 58        | 4.21%   |
| 3     | 11        | 0.8%    |
| 8     | 2         | 0.15%   |
| 5     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 130       | 28.89%  |
| Graphics card            | 100       | 22.22%  |
| Chipcard                 | 74        | 16.44%  |
| Net/wireless             | 37        | 8.22%   |
| Camera                   | 17        | 3.78%   |
| Bluetooth                | 15        | 3.33%   |
| Communication controller | 14        | 3.11%   |
| Multimedia controller    | 12        | 2.67%   |
| Storage                  | 11        | 2.44%   |
| Unassigned class         | 7         | 1.56%   |
| Modem                    | 7         | 1.56%   |
| Sound                    | 6         | 1.33%   |
| Network                  | 5         | 1.11%   |
| Card reader              | 5         | 1.11%   |
| Flash memory             | 4         | 0.89%   |
| Net/ethernet             | 2         | 0.44%   |
| Tv card                  | 1         | 0.22%   |
| Storage/ata              | 1         | 0.22%   |
| Firewire controller      | 1         | 0.22%   |
| Dvb card                 | 1         | 0.22%   |

