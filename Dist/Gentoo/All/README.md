Gentoo - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

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

Total: 3219

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [075ee0ca67](https://linux-hardware.org/?probe=075ee0ca67) | Feb 02, 2024 |
| Razer         | Blade 14 - RZ09-0482        | Notebook    | [49f14f0aae](https://linux-hardware.org/?probe=49f14f0aae) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afbbc9ebf0](https://linux-hardware.org/?probe=afbbc9ebf0) | Jan 31, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7ad6a0ecce](https://linux-hardware.org/?probe=7ad6a0ecce) | Jan 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [4690cc047a](https://linux-hardware.org/?probe=4690cc047a) | Jan 30, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cc38ac2dfc](https://linux-hardware.org/?probe=cc38ac2dfc) | Jan 29, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8949a81c2e](https://linux-hardware.org/?probe=8949a81c2e) | Jan 29, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [76a1ecf2ba](https://linux-hardware.org/?probe=76a1ecf2ba) | Jan 29, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e17793cd71](https://linux-hardware.org/?probe=e17793cd71) | Jan 28, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [19c619ae3f](https://linux-hardware.org/?probe=19c619ae3f) | Jan 27, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [999ea9c685](https://linux-hardware.org/?probe=999ea9c685) | Jan 26, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9b7cbb57c7](https://linux-hardware.org/?probe=9b7cbb57c7) | Jan 26, 2024 |
| HP            | 1589                        | Desktop     | [d731924276](https://linux-hardware.org/?probe=d731924276) | Jan 25, 2024 |
| Star Labs     | StarBook                    | Notebook    | [a324d865a6](https://linux-hardware.org/?probe=a324d865a6) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ff2fc44691](https://linux-hardware.org/?probe=ff2fc44691) | Jan 23, 2024 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [07799fb2f9](https://linux-hardware.org/?probe=07799fb2f9) | Jan 19, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [13086bc4ce](https://linux-hardware.org/?probe=13086bc4ce) | Jan 19, 2024 |
| Gigabyte      | B650M D3HP                  | Desktop     | [fdc83ca691](https://linux-hardware.org/?probe=fdc83ca691) | Jan 18, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e736cc5c9a](https://linux-hardware.org/?probe=e736cc5c9a) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [18a0aeeddf](https://linux-hardware.org/?probe=18a0aeeddf) | Jan 18, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [68c23a7bd3](https://linux-hardware.org/?probe=68c23a7bd3) | Jan 17, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ed6bfe4f8f](https://linux-hardware.org/?probe=ed6bfe4f8f) | Jan 16, 2024 |
| Dell          | 0VHRW1 A03                  | Desktop     | [668e361f20](https://linux-hardware.org/?probe=668e361f20) | Jan 15, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [4af392aac3](https://linux-hardware.org/?probe=4af392aac3) | Jan 14, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [e509920598](https://linux-hardware.org/?probe=e509920598) | Jan 14, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [dc433d32e3](https://linux-hardware.org/?probe=dc433d32e3) | Jan 13, 2024 |
| HP            | 1589                        | Desktop     | [194b5a119c](https://linux-hardware.org/?probe=194b5a119c) | Jan 13, 2024 |
| MSI           | Pulse 15 B13VFK             | Notebook    | [75dde9eefd](https://linux-hardware.org/?probe=75dde9eefd) | Jan 12, 2024 |
| HP            | Laptop 15 da0018nk          | Notebook    | [11c54a0e5b](https://linux-hardware.org/?probe=11c54a0e5b) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [30679c3606](https://linux-hardware.org/?probe=30679c3606) | Jan 11, 2024 |
| Dell          | 030VXY A01                  | Desktop     | [50a18e5eba](https://linux-hardware.org/?probe=50a18e5eba) | Jan 10, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d3f6265673](https://linux-hardware.org/?probe=d3f6265673) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [7bef06dee9](https://linux-hardware.org/?probe=7bef06dee9) | Jan 10, 2024 |
| DEXP          | Aquilon C14                 | Notebook    | [d38932d74f](https://linux-hardware.org/?probe=d38932d74f) | Jan 10, 2024 |
| Gigabyte      | Z590 UD                     | Desktop     | [6953296967](https://linux-hardware.org/?probe=6953296967) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [36dc56b0ed](https://linux-hardware.org/?probe=36dc56b0ed) | Jan 09, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [ac39f0a923](https://linux-hardware.org/?probe=ac39f0a923) | Jan 08, 2024 |
| Star Labs     | StarLite                    | Notebook    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [ca5d4c7c00](https://linux-hardware.org/?probe=ca5d4c7c00) | Jan 07, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [33b192a7d0](https://linux-hardware.org/?probe=33b192a7d0) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1ecec883dd](https://linux-hardware.org/?probe=1ecec883dd) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [94b30c5116](https://linux-hardware.org/?probe=94b30c5116) | Jan 06, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3b6e799f22](https://linux-hardware.org/?probe=3b6e799f22) | Jan 06, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8d63c2ea2b](https://linux-hardware.org/?probe=8d63c2ea2b) | Jan 06, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [90b8ceb64c](https://linux-hardware.org/?probe=90b8ceb64c) | Jan 05, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bf93755f2](https://linux-hardware.org/?probe=7bf93755f2) | Jan 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [da0c7ff210](https://linux-hardware.org/?probe=da0c7ff210) | Jan 04, 2024 |
| ASUSTek       | P8H67-M                     | Desktop     | [06843ca788](https://linux-hardware.org/?probe=06843ca788) | Jan 04, 2024 |
| Star Labs     | StarLite                    | Notebook    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a0e025d32d](https://linux-hardware.org/?probe=a0e025d32d) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [ee3998d501](https://linux-hardware.org/?probe=ee3998d501) | Jan 02, 2024 |
| Acer          | Aspire A517-52G             | Notebook    | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| Dell          | Latitude D630               | Notebook    | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [0e7bbb6dea](https://linux-hardware.org/?probe=0e7bbb6dea) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | Notebook    | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [618dfee965](https://linux-hardware.org/?probe=618dfee965) | Dec 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [619ddf5210](https://linux-hardware.org/?probe=619ddf5210) | Dec 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [983d2046a3](https://linux-hardware.org/?probe=983d2046a3) | Dec 27, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| ASUSTek       | D500MD                      | Desktop     | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [47255f4ba3](https://linux-hardware.org/?probe=47255f4ba3) | Dec 25, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [646b9af5a9](https://linux-hardware.org/?probe=646b9af5a9) | Dec 24, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [8503d79f6c](https://linux-hardware.org/?probe=8503d79f6c) | Dec 24, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [391ef34135](https://linux-hardware.org/?probe=391ef34135) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c6caf2cc7a](https://linux-hardware.org/?probe=c6caf2cc7a) | Dec 22, 2023 |
| Dell          | Precision 5480              | Notebook    | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [f65d61f128](https://linux-hardware.org/?probe=f65d61f128) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [37ee5a4acd](https://linux-hardware.org/?probe=37ee5a4acd) | Dec 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [877c79184e](https://linux-hardware.org/?probe=877c79184e) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [25525c17e0](https://linux-hardware.org/?probe=25525c17e0) | Dec 17, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [c01e13535f](https://linux-hardware.org/?probe=c01e13535f) | Dec 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [402a34ec30](https://linux-hardware.org/?probe=402a34ec30) | Dec 17, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [776cc9f3bb](https://linux-hardware.org/?probe=776cc9f3bb) | Dec 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f02dc20ac0](https://linux-hardware.org/?probe=f02dc20ac0) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| HP            | 8592                        | Desktop     | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| HP            | 8592                        | Desktop     | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ba4e95a15e](https://linux-hardware.org/?probe=ba4e95a15e) | Dec 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5eaaa9dcdc](https://linux-hardware.org/?probe=5eaaa9dcdc) | Dec 13, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [8524c9dcd5](https://linux-hardware.org/?probe=8524c9dcd5) | Dec 13, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| Dell          | 02C2CP A03                  | Server      | [3a651d8f80](https://linux-hardware.org/?probe=3a651d8f80) | Dec 13, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| Foxconn       | TPS01                       | Desktop     | [a417ff19ae](https://linux-hardware.org/?probe=a417ff19ae) | Dec 12, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ba355033b7](https://linux-hardware.org/?probe=ba355033b7) | Dec 08, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [7e738d8259](https://linux-hardware.org/?probe=7e738d8259) | Dec 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d57960be0a](https://linux-hardware.org/?probe=d57960be0a) | Dec 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [675f997c0b](https://linux-hardware.org/?probe=675f997c0b) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [358a92be0d](https://linux-hardware.org/?probe=358a92be0d) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | Notebook    | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [7f49fad2c7](https://linux-hardware.org/?probe=7f49fad2c7) | Dec 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [fc87fb1112](https://linux-hardware.org/?probe=fc87fb1112) | Dec 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| Unknown       | Unknown                     | Soc         | [ab9297851b](https://linux-hardware.org/?probe=ab9297851b) | Nov 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [720eead0a5](https://linux-hardware.org/?probe=720eead0a5) | Nov 29, 2023 |
| Unknown       | Unknown                     | Soc         | [7acffa679c](https://linux-hardware.org/?probe=7acffa679c) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [f16bc78368](https://linux-hardware.org/?probe=f16bc78368) | Nov 29, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [879c59cf41](https://linux-hardware.org/?probe=879c59cf41) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [68644f2689](https://linux-hardware.org/?probe=68644f2689) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6fcbd9b64c](https://linux-hardware.org/?probe=6fcbd9b64c) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| Supermicro    | X8DT3                       | Server      | [93de2051e2](https://linux-hardware.org/?probe=93de2051e2) | Nov 27, 2023 |
| Dell          | Latitude D630               | Notebook    | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [9e8f9907bb](https://linux-hardware.org/?probe=9e8f9907bb) | Nov 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [fde8cf07ef](https://linux-hardware.org/?probe=fde8cf07ef) | Nov 24, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [c397c51bfb](https://linux-hardware.org/?probe=c397c51bfb) | Nov 24, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [2305a057a8](https://linux-hardware.org/?probe=2305a057a8) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [221dcda3ae](https://linux-hardware.org/?probe=221dcda3ae) | Nov 19, 2023 |
| UMAX          | VisionBook 9Wi Pro          | Tablet      | [816a26352f](https://linux-hardware.org/?probe=816a26352f) | Nov 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [fc7f2d74b8](https://linux-hardware.org/?probe=fc7f2d74b8) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | Notebook    | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a868498279](https://linux-hardware.org/?probe=a868498279) | Nov 18, 2023 |
| Dell          | Precision 5480              | Notebook    | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [477c710fe1](https://linux-hardware.org/?probe=477c710fe1) | Nov 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [76092ba872](https://linux-hardware.org/?probe=76092ba872) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6a5b4cf051](https://linux-hardware.org/?probe=6a5b4cf051) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1105d135a2](https://linux-hardware.org/?probe=1105d135a2) | Nov 14, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | Notebook    | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [ab65845e2f](https://linux-hardware.org/?probe=ab65845e2f) | Nov 12, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [3efb188b16](https://linux-hardware.org/?probe=3efb188b16) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | Notebook    | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Dell          | Latitude D630               | Notebook    | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [4c763ba78a](https://linux-hardware.org/?probe=4c763ba78a) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [1de1299edf](https://linux-hardware.org/?probe=1de1299edf) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [715aee0ee7](https://linux-hardware.org/?probe=715aee0ee7) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [b865e2f52d](https://linux-hardware.org/?probe=b865e2f52d) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8e8cfaa103](https://linux-hardware.org/?probe=8e8cfaa103) | Nov 05, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [63e30986f6](https://linux-hardware.org/?probe=63e30986f6) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [40deedc435](https://linux-hardware.org/?probe=40deedc435) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [57d643d36b](https://linux-hardware.org/?probe=57d643d36b) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f6e8c279ef](https://linux-hardware.org/?probe=f6e8c279ef) | Oct 31, 2023 |
| Dell          | Latitude 7320               | Notebook    | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0cea8f6bb](https://linux-hardware.org/?probe=d0cea8f6bb) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [50b77f9f9e](https://linux-hardware.org/?probe=50b77f9f9e) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [78bdbc6419](https://linux-hardware.org/?probe=78bdbc6419) | Oct 25, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| HP            | 3397                        | Desktop     | [1344d9d38b](https://linux-hardware.org/?probe=1344d9d38b) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [9a65857d3c](https://linux-hardware.org/?probe=9a65857d3c) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [001c668695](https://linux-hardware.org/?probe=001c668695) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [95d6dab241](https://linux-hardware.org/?probe=95d6dab241) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [4b93c11bcb](https://linux-hardware.org/?probe=4b93c11bcb) | Oct 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [62ae73f967](https://linux-hardware.org/?probe=62ae73f967) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [b677f99638](https://linux-hardware.org/?probe=b677f99638) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [911d7f21e7](https://linux-hardware.org/?probe=911d7f21e7) | Oct 18, 2023 |
| ASRock        | H170 Pro4S                  | Desktop     | [e3960f114d](https://linux-hardware.org/?probe=e3960f114d) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| Dell          | 0MNPJ9 A03                  | Desktop     | [36e7a1e261](https://linux-hardware.org/?probe=36e7a1e261) | Oct 18, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [1e2597a152](https://linux-hardware.org/?probe=1e2597a152) | Oct 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [65277f3f01](https://linux-hardware.org/?probe=65277f3f01) | Oct 16, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [d3cf683bad](https://linux-hardware.org/?probe=d3cf683bad) | Oct 15, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| PINE64        | Pinebook Pro                | Soc         | [e62b12571a](https://linux-hardware.org/?probe=e62b12571a) | Oct 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [212f394b32](https://linux-hardware.org/?probe=212f394b32) | Oct 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [586d5eef76](https://linux-hardware.org/?probe=586d5eef76) | Oct 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [c5d7f755ac](https://linux-hardware.org/?probe=c5d7f755ac) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | 1589                        | Desktop     | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| Dell          | 0NGT4D A01                  | Mini pc     | [457dfea13d](https://linux-hardware.org/?probe=457dfea13d) | Oct 03, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [5e6d01b044](https://linux-hardware.org/?probe=5e6d01b044) | Oct 03, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [5018997f48](https://linux-hardware.org/?probe=5018997f48) | Oct 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [25c3794b84](https://linux-hardware.org/?probe=25c3794b84) | Oct 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [ff0e651b1b](https://linux-hardware.org/?probe=ff0e651b1b) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| HP            | 1589                        | Desktop     | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [c2ba80af3b](https://linux-hardware.org/?probe=c2ba80af3b) | Sep 26, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6dca52cc54](https://linux-hardware.org/?probe=6dca52cc54) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [fb93d199f3](https://linux-hardware.org/?probe=fb93d199f3) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [d17427680f](https://linux-hardware.org/?probe=d17427680f) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [1c0c7815dd](https://linux-hardware.org/?probe=1c0c7815dd) | Sep 24, 2023 |
| Supermicro    | X10SDE-DF                   | Desktop     | [b0297cff82](https://linux-hardware.org/?probe=b0297cff82) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| Dell          | 0RY206                      | Desktop     | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| ASRock        | B85M                        | Desktop     | [8a3dc73931](https://linux-hardware.org/?probe=8a3dc73931) | Sep 18, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [524eb9d966](https://linux-hardware.org/?probe=524eb9d966) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [2f86649b91](https://linux-hardware.org/?probe=2f86649b91) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [12f4431262](https://linux-hardware.org/?probe=12f4431262) | Sep 12, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [0dabf67d5f](https://linux-hardware.org/?probe=0dabf67d5f) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [ce24c28731](https://linux-hardware.org/?probe=ce24c28731) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | Notebook    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [32a90ea48e](https://linux-hardware.org/?probe=32a90ea48e) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f0e20e0089](https://linux-hardware.org/?probe=f0e20e0089) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | Desktop     | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | Desktop     | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Dell          | 0RY206                      | Desktop     | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [34ef0ea7ff](https://linux-hardware.org/?probe=34ef0ea7ff) | Aug 20, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [101202101b](https://linux-hardware.org/?probe=101202101b) | Aug 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [8af741a2c4](https://linux-hardware.org/?probe=8af741a2c4) | Aug 19, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [a4747bf8ea](https://linux-hardware.org/?probe=a4747bf8ea) | Aug 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [6b5f510903](https://linux-hardware.org/?probe=6b5f510903) | Aug 18, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| Dell          | 0RY206                      | Desktop     | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| Dell          | Latitude E7450              | Notebook    | [057d88b470](https://linux-hardware.org/?probe=057d88b470) | Aug 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [aa4c1f2237](https://linux-hardware.org/?probe=aa4c1f2237) | Aug 13, 2023 |
| Foxconn       | TPS01                       | Desktop     | [8e5b20544d](https://linux-hardware.org/?probe=8e5b20544d) | Aug 13, 2023 |
| AMD           | A690G M2+                   | Desktop     | [4179510c0b](https://linux-hardware.org/?probe=4179510c0b) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [231f8f9b37](https://linux-hardware.org/?probe=231f8f9b37) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [13aee7ad4d](https://linux-hardware.org/?probe=13aee7ad4d) | Aug 13, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [6f3ec125fd](https://linux-hardware.org/?probe=6f3ec125fd) | Aug 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [5712d7b72d](https://linux-hardware.org/?probe=5712d7b72d) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5cbfb27db2](https://linux-hardware.org/?probe=5cbfb27db2) | Aug 11, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [72b375ad38](https://linux-hardware.org/?probe=72b375ad38) | Aug 11, 2023 |
| NEC Comput... | 312C                        | Desktop     | [770ffcfcf5](https://linux-hardware.org/?probe=770ffcfcf5) | Aug 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| MSI           | 970A-G43 PLUS               | Desktop     | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [ed97e2ea3e](https://linux-hardware.org/?probe=ed97e2ea3e) | Aug 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [584974f252](https://linux-hardware.org/?probe=584974f252) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [570728a351](https://linux-hardware.org/?probe=570728a351) | Aug 05, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [18146f8bc9](https://linux-hardware.org/?probe=18146f8bc9) | Aug 04, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| HP            | 2B47                        | Desktop     | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| Alienware     | x17 R1                      | Notebook    | [bcdf52a63e](https://linux-hardware.org/?probe=bcdf52a63e) | Aug 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [51541062dc](https://linux-hardware.org/?probe=51541062dc) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4e2e9f1f7f](https://linux-hardware.org/?probe=4e2e9f1f7f) | Jul 31, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [23c9c57a00](https://linux-hardware.org/?probe=23c9c57a00) | Jul 30, 2023 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [f9b68dbdc9](https://linux-hardware.org/?probe=f9b68dbdc9) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [731b8aed1b](https://linux-hardware.org/?probe=731b8aed1b) | Jul 29, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7e6ad75fc4](https://linux-hardware.org/?probe=7e6ad75fc4) | Jul 28, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [ba2f93d0af](https://linux-hardware.org/?probe=ba2f93d0af) | Jul 28, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [27da4128a7](https://linux-hardware.org/?probe=27da4128a7) | Jul 28, 2023 |
| MSI           | TRX40 PRO 10G               | Desktop     | [6391114079](https://linux-hardware.org/?probe=6391114079) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4895ec9de1](https://linux-hardware.org/?probe=4895ec9de1) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| Gateway       | MS-7399                     | Desktop     | [904775a387](https://linux-hardware.org/?probe=904775a387) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| Foxconn       | TPS01                       | Desktop     | [d8e4cab1b8](https://linux-hardware.org/?probe=d8e4cab1b8) | Jul 21, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [8504edcacf](https://linux-hardware.org/?probe=8504edcacf) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [aac317ef80](https://linux-hardware.org/?probe=aac317ef80) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [cda9e7abe9](https://linux-hardware.org/?probe=cda9e7abe9) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [8d8d1d6cbf](https://linux-hardware.org/?probe=8d8d1d6cbf) | Jul 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [1f1b7763a5](https://linux-hardware.org/?probe=1f1b7763a5) | Jul 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c8179fd349](https://linux-hardware.org/?probe=c8179fd349) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [be7dcafaba](https://linux-hardware.org/?probe=be7dcafaba) | Jul 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [4d1ecd77ad](https://linux-hardware.org/?probe=4d1ecd77ad) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [2a37881afa](https://linux-hardware.org/?probe=2a37881afa) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [89dc06fa6d](https://linux-hardware.org/?probe=89dc06fa6d) | Jul 09, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [cf9ad63ff9](https://linux-hardware.org/?probe=cf9ad63ff9) | Jul 09, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [306eaba8f1](https://linux-hardware.org/?probe=306eaba8f1) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [0b6dcc1ea9](https://linux-hardware.org/?probe=0b6dcc1ea9) | Jul 09, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ca41a9886a](https://linux-hardware.org/?probe=ca41a9886a) | Jul 09, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [4b611c264e](https://linux-hardware.org/?probe=4b611c264e) | Jul 08, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [8cccaeb0ed](https://linux-hardware.org/?probe=8cccaeb0ed) | Jul 08, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [9a6e78196d](https://linux-hardware.org/?probe=9a6e78196d) | Jul 06, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [b4b26d2f53](https://linux-hardware.org/?probe=b4b26d2f53) | Jul 06, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Aierben       | NA17                        | Desktop     | [462b502bab](https://linux-hardware.org/?probe=462b502bab) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f4fdc8a532](https://linux-hardware.org/?probe=f4fdc8a532) | Jul 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [49bcd116ba](https://linux-hardware.org/?probe=49bcd116ba) | Jul 04, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Jumper        | EZbook                      | Notebook    | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0ac212cac](https://linux-hardware.org/?probe=a0ac212cac) | Jul 01, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [0f0e96b03c](https://linux-hardware.org/?probe=0f0e96b03c) | Jul 01, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [a0fdd16a9e](https://linux-hardware.org/?probe=a0fdd16a9e) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [af8af2c7e8](https://linux-hardware.org/?probe=af8af2c7e8) | Jun 30, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [4df7190c46](https://linux-hardware.org/?probe=4df7190c46) | Jun 29, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [6388cc47ae](https://linux-hardware.org/?probe=6388cc47ae) | Jun 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c7a5d0ef6c](https://linux-hardware.org/?probe=c7a5d0ef6c) | Jun 29, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [b6c0bd1df6](https://linux-hardware.org/?probe=b6c0bd1df6) | Jun 28, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [498d9375d4](https://linux-hardware.org/?probe=498d9375d4) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| ASRock        | J3160M                      | Desktop     | [0521c9a5a7](https://linux-hardware.org/?probe=0521c9a5a7) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8e26542f2d](https://linux-hardware.org/?probe=8e26542f2d) | Jun 17, 2023 |
| HP            | ENVY m6                     | Notebook    | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell          | Precision 5530              | Notebook    | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell          | Precision 5530              | Notebook    | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google        | Nightfury                   | Notebook    | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [deeef80345](https://linux-hardware.org/?probe=deeef80345) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [153ae28a9e](https://linux-hardware.org/?probe=153ae28a9e) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [26262445d4](https://linux-hardware.org/?probe=26262445d4) | Jun 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [96256dca48](https://linux-hardware.org/?probe=96256dca48) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Dell          | Precision 5530              | Notebook    | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d7ae224bea](https://linux-hardware.org/?probe=d7ae224bea) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [c1cfe9f08d](https://linux-hardware.org/?probe=c1cfe9f08d) | Jun 02, 2023 |
| Dell          | Precision 5530              | Notebook    | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Pegatron      | 2ACE                        | Desktop     | [fd6056dba8](https://linux-hardware.org/?probe=fd6056dba8) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| MSI           | GE76 Raider 11UH            | Notebook    | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [5384efc9d9](https://linux-hardware.org/?probe=5384efc9d9) | May 28, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [39f6ad44fe](https://linux-hardware.org/?probe=39f6ad44fe) | May 28, 2023 |
| Supermicro    | H12SSL-CT                   | Server      | [00dea5aed8](https://linux-hardware.org/?probe=00dea5aed8) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | Desktop     | [f7a170dd7d](https://linux-hardware.org/?probe=f7a170dd7d) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [95231653d0](https://linux-hardware.org/?probe=95231653d0) | May 26, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [6c74d47711](https://linux-hardware.org/?probe=6c74d47711) | May 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [d44b92320b](https://linux-hardware.org/?probe=d44b92320b) | May 25, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [aa919fe5b3](https://linux-hardware.org/?probe=aa919fe5b3) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [41ca623e3c](https://linux-hardware.org/?probe=41ca623e3c) | May 24, 2023 |
| ASRock        | Z170 OC Formula             | Desktop     | [d7a354fa41](https://linux-hardware.org/?probe=d7a354fa41) | May 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [7ad8de5a40](https://linux-hardware.org/?probe=7ad8de5a40) | May 22, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e0611754f3](https://linux-hardware.org/?probe=e0611754f3) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| Foxconn       | TPS01                       | Desktop     | [385129d471](https://linux-hardware.org/?probe=385129d471) | May 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [46697ea0e2](https://linux-hardware.org/?probe=46697ea0e2) | May 20, 2023 |
| Foxconn       | TPS01                       | Desktop     | [853284b818](https://linux-hardware.org/?probe=853284b818) | May 20, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [7c52ccb596](https://linux-hardware.org/?probe=7c52ccb596) | May 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [22ef34bb50](https://linux-hardware.org/?probe=22ef34bb50) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [8bd01d7d16](https://linux-hardware.org/?probe=8bd01d7d16) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| TYAN Compu... | S2505T                      | Desktop     | [a17c60c707](https://linux-hardware.org/?probe=a17c60c707) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [9257bb2c1a](https://linux-hardware.org/?probe=9257bb2c1a) | May 16, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [4160bd4f84](https://linux-hardware.org/?probe=4160bd4f84) | May 16, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [6d60b321b1](https://linux-hardware.org/?probe=6d60b321b1) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [a13951a75b](https://linux-hardware.org/?probe=a13951a75b) | May 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Foxconn       | nT-330i                     | Desktop     | [b95166587e](https://linux-hardware.org/?probe=b95166587e) | May 14, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [334b015373](https://linux-hardware.org/?probe=334b015373) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [e172257a22](https://linux-hardware.org/?probe=e172257a22) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [1cf183101b](https://linux-hardware.org/?probe=1cf183101b) | May 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0ae43bcc58](https://linux-hardware.org/?probe=0ae43bcc58) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [49ad1e2075](https://linux-hardware.org/?probe=49ad1e2075) | May 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [aa2af0a4bc](https://linux-hardware.org/?probe=aa2af0a4bc) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bfd53a8d28](https://linux-hardware.org/?probe=bfd53a8d28) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [5d774e899c](https://linux-hardware.org/?probe=5d774e899c) | May 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [063e548538](https://linux-hardware.org/?probe=063e548538) | May 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [77ef33da62](https://linux-hardware.org/?probe=77ef33da62) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1c158dca0e](https://linux-hardware.org/?probe=1c158dca0e) | May 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| HP            | G62                         | Notebook    | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| Dell          | Precision 7770              | Notebook    | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [0f7e30ded3](https://linux-hardware.org/?probe=0f7e30ded3) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | Desktop     | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [80ead18196](https://linux-hardware.org/?probe=80ead18196) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [0f17162503](https://linux-hardware.org/?probe=0f17162503) | Apr 21, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [056db62b47](https://linux-hardware.org/?probe=056db62b47) | Apr 20, 2023 |
| Dell          | Latitude 7420               | Notebook    | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | Desktop     | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | Desktop     | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb21111c89](https://linux-hardware.org/?probe=cb21111c89) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [6b71471847](https://linux-hardware.org/?probe=6b71471847) | Apr 15, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [d00ebfbc62](https://linux-hardware.org/?probe=d00ebfbc62) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8b0e1ffa20](https://linux-hardware.org/?probe=8b0e1ffa20) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [3b2ac9206c](https://linux-hardware.org/?probe=3b2ac9206c) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [16ee5e0082](https://linux-hardware.org/?probe=16ee5e0082) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [1b21351033](https://linux-hardware.org/?probe=1b21351033) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [f6f55c801f](https://linux-hardware.org/?probe=f6f55c801f) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [7f20e3160b](https://linux-hardware.org/?probe=7f20e3160b) | Apr 13, 2023 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [1b44c95410](https://linux-hardware.org/?probe=1b44c95410) | Apr 13, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [f46283dc4c](https://linux-hardware.org/?probe=f46283dc4c) | Apr 13, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f5241c853f](https://linux-hardware.org/?probe=f5241c853f) | Apr 12, 2023 |
| Dell          | Precision 7770              | Notebook    | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f85fdf6564](https://linux-hardware.org/?probe=f85fdf6564) | Apr 09, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [9384fef88d](https://linux-hardware.org/?probe=9384fef88d) | Apr 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [e378272577](https://linux-hardware.org/?probe=e378272577) | Apr 08, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [97e76297c9](https://linux-hardware.org/?probe=97e76297c9) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2fccbc61e2](https://linux-hardware.org/?probe=2fccbc61e2) | Apr 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d19221e116](https://linux-hardware.org/?probe=d19221e116) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | Notebook    | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4bf7fa5f9c](https://linux-hardware.org/?probe=4bf7fa5f9c) | Mar 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | Notebook    | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [e79acda971](https://linux-hardware.org/?probe=e79acda971) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [210b2e16e3](https://linux-hardware.org/?probe=210b2e16e3) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | Notebook    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [fab37d7522](https://linux-hardware.org/?probe=fab37d7522) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Foxconn       | TPS01                       | Desktop     | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | Desktop     | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [06d54f03f9](https://linux-hardware.org/?probe=06d54f03f9) | Mar 13, 2023 |
| Unknown       | Unknown                     | Soc         | [211fbfe507](https://linux-hardware.org/?probe=211fbfe507) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| Samsung       | 950QDB                      | Convertible | [525ce83d74](https://linux-hardware.org/?probe=525ce83d74) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | Notebook    | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| ASRock        | H170 Pro4                   | Desktop     | [7d749add31](https://linux-hardware.org/?probe=7d749add31) | Mar 07, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [4d48b829ca](https://linux-hardware.org/?probe=4d48b829ca) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [ffd546b665](https://linux-hardware.org/?probe=ffd546b665) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| Dell          | Precision 7770              | Notebook    | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| IBM           | ThinkPad T41 23737JU        | Notebook    | [5495bd2109](https://linux-hardware.org/?probe=5495bd2109) | Mar 03, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [e260724901](https://linux-hardware.org/?probe=e260724901) | Mar 03, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | Desktop     | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [cede8b490a](https://linux-hardware.org/?probe=cede8b490a) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Alienware     | 17                          | Notebook    | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| Dell          | Precision 7770              | Notebook    | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [a526504d18](https://linux-hardware.org/?probe=a526504d18) | Feb 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [46289356fa](https://linux-hardware.org/?probe=46289356fa) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [fa6a3fe6e3](https://linux-hardware.org/?probe=fa6a3fe6e3) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [aedfc67444](https://linux-hardware.org/?probe=aedfc67444) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [ba881ed411](https://linux-hardware.org/?probe=ba881ed411) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [469eaa6fba](https://linux-hardware.org/?probe=469eaa6fba) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [4998be684f](https://linux-hardware.org/?probe=4998be684f) | Feb 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2cfb05371e](https://linux-hardware.org/?probe=2cfb05371e) | Feb 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4468518165](https://linux-hardware.org/?probe=4468518165) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [85b07c179c](https://linux-hardware.org/?probe=85b07c179c) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [238c7a2c08](https://linux-hardware.org/?probe=238c7a2c08) | Feb 09, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [f09cd898c8](https://linux-hardware.org/?probe=f09cd898c8) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [78a631609d](https://linux-hardware.org/?probe=78a631609d) | Feb 04, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [37d0cc301b](https://linux-hardware.org/?probe=37d0cc301b) | Feb 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [a08ee9b387](https://linux-hardware.org/?probe=a08ee9b387) | Feb 03, 2023 |
| Dell          | Precision 7770              | Notebook    | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [a1bb8934a0](https://linux-hardware.org/?probe=a1bb8934a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4bb9990abe](https://linux-hardware.org/?probe=4bb9990abe) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [0a7c76da78](https://linux-hardware.org/?probe=0a7c76da78) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [c93e84b79b](https://linux-hardware.org/?probe=c93e84b79b) | Jan 29, 2023 |
| Google        | Helios                      | Notebook    | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [f71299a9c6](https://linux-hardware.org/?probe=f71299a9c6) | Jan 27, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [a30690db0c](https://linux-hardware.org/?probe=a30690db0c) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [6a876fb2b4](https://linux-hardware.org/?probe=6a876fb2b4) | Jan 23, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [287d005187](https://linux-hardware.org/?probe=287d005187) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| Dell          | Precision 7770              | Notebook    | [47044d362f](https://linux-hardware.org/?probe=47044d362f) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | Notebook    | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ebe686793d](https://linux-hardware.org/?probe=ebe686793d) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [706152a268](https://linux-hardware.org/?probe=706152a268) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [d37b338c87](https://linux-hardware.org/?probe=d37b338c87) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [413cd3b7cf](https://linux-hardware.org/?probe=413cd3b7cf) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [753a61e1de](https://linux-hardware.org/?probe=753a61e1de) | Jan 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [b14d57e1a3](https://linux-hardware.org/?probe=b14d57e1a3) | Jan 19, 2023 |
| Dell          | Precision 7720              | Notebook    | [9a00916b91](https://linux-hardware.org/?probe=9a00916b91) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Schenker      | XMG PRO (E22)               | Notebook    | [475e812e56](https://linux-hardware.org/?probe=475e812e56) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0d5c9f7a33](https://linux-hardware.org/?probe=0d5c9f7a33) | Jan 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [f8e1c53257](https://linux-hardware.org/?probe=f8e1c53257) | Jan 16, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8e35281ea5](https://linux-hardware.org/?probe=8e35281ea5) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5e6192ed2b](https://linux-hardware.org/?probe=5e6192ed2b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [4fe502c977](https://linux-hardware.org/?probe=4fe502c977) | Jan 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Google        | Sasuke                      | Notebook    | [aa3a09aaef](https://linux-hardware.org/?probe=aa3a09aaef) | Jan 07, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [0944e31ade](https://linux-hardware.org/?probe=0944e31ade) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| HP            | 212A                        | Desktop     | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [0dbae6cda4](https://linux-hardware.org/?probe=0dbae6cda4) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [bca9343f96](https://linux-hardware.org/?probe=bca9343f96) | Jan 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 556       | 28.44%  |
| Gentoo 2.6     | 413       | 21.13%  |
| Gentoo 2.8     | 306       | 15.65%  |
| Gentoo 2.13    | 240       | 12.28%  |
| Gentoo 2.14    | 225       | 11.51%  |
| Gentoo 2.9     | 160       | 8.18%   |
| Gentoo 2.4.1   | 14        | 0.72%   |
| Gentoo         | 11        | 0.56%   |
| Gentoo 2.3     | 9         | 0.46%   |
| Gentoo 2.2     | 7         | 0.36%   |
| Gentoo 23      | 3         | 0.15%   |
| Gentoo 1       | 3         | 0.15%   |
| Gentoo 22.0.1  | 2         | 0.1%    |
| Gentoo Pelikan | 1         | 0.05%   |
| Gentoo 22      | 1         | 0.05%   |
| Gentoo 2022    | 1         | 0.05%   |
| Gentoo 20.04   | 1         | 0.05%   |
| Gentoo 2.1     | 1         | 0.05%   |
| Gentoo 13.0    | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1684      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.13%   |
| 5.10.27-gentoo           | 25        | 1.09%   |
| 5.10.61-gentoo           | 23        | 1%      |
| 5.15.32-gentoo-r1        | 18        | 0.78%   |
| 6.1.57-gentoo            | 16        | 0.7%    |
| 6.1.12-gentoo            | 16        | 0.7%    |
| 5.15.80-gentoo-x86_64    | 16        | 0.7%    |
| 5.15.80-gentoo           | 16        | 0.7%    |
| 6.1.19-gentoo-x86_64     | 15        | 0.65%   |
| 5.4.80-gentoo-r1         | 15        | 0.65%   |
| 5.4.48-gentoo            | 15        | 0.65%   |
| 6.1.19-gentoo            | 14        | 0.61%   |
| 5.4.97-gentoo            | 14        | 0.61%   |
| 5.4.28-gentoo            | 14        | 0.61%   |
| 5.10.76-gentoo-r1        | 14        | 0.61%   |
| 6.1.57-gentoo-x86_64     | 13        | 0.57%   |
| 5.15.75-gentoo-x86_64    | 13        | 0.57%   |
| 5.10.61-gentoo-x86_64    | 13        | 0.57%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.57%   |
| 5.15.59-gentoo-x86_64    | 12        | 0.52%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.52%   |
| 5.10.52-gentoo           | 12        | 0.52%   |
| 5.7.0-gentoo             | 11        | 0.48%   |
| 5.4.60-gentoo            | 11        | 0.48%   |
| 5.15.88-gentoo           | 11        | 0.48%   |
| 6.1.53-gentoo-r1         | 10        | 0.44%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.44%   |
| 6.1.67-gentoo            | 9         | 0.39%   |
| 6.1.41-gentoo-dist       | 9         | 0.39%   |
| 6.1.31-gentoo-dist       | 9         | 0.39%   |
| 6.1.12-gentoo-x86_64     | 9         | 0.39%   |
| 5.15.75-gentoo           | 9         | 0.39%   |
| 5.15.59-gentoo           | 9         | 0.39%   |
| 5.15.52-gentoo-x86_64    | 9         | 0.39%   |
| 5.15.52-gentoo           | 9         | 0.39%   |
| 5.15.41-gentoo-x86_64    | 9         | 0.39%   |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.39%   |
| 6.1.46-gentoo            | 8         | 0.35%   |
| 6.1.41-gentoo            | 8         | 0.35%   |
| 5.6.15-gentoo            | 8         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 2.01%   |
| 5.4.38  | 45        | 1.97%   |
| 5.15.32 | 41        | 1.79%   |
| 6.1.57  | 39        | 1.7%    |
| 5.10.61 | 39        | 1.7%    |
| 6.1.19  | 37        | 1.62%   |
| 6.1.12  | 35        | 1.53%   |
| 5.15.80 | 34        | 1.49%   |
| 5.4.48  | 33        | 1.44%   |
| 5.10.76 | 32        | 1.4%    |
| 5.15.75 | 30        | 1.31%   |
| 5.15.59 | 26        | 1.14%   |
| 6.1.31  | 25        | 1.09%   |
| 5.4.97  | 25        | 1.09%   |
| 5.4.28  | 25        | 1.09%   |
| 5.15.52 | 24        | 1.05%   |
| 5.10.52 | 24        | 1.05%   |
| 5.15.41 | 23        | 1%      |
| 6.1.41  | 22        | 0.96%   |
| 5.4.80  | 22        | 0.96%   |
| 6.1.67  | 21        | 0.92%   |
| 5.15.11 | 19        | 0.83%   |
| 6.1.53  | 18        | 0.79%   |
| 6.1.46  | 18        | 0.79%   |
| 5.4.66  | 17        | 0.74%   |
| 5.15.88 | 17        | 0.74%   |
| 5.6.15  | 16        | 0.7%    |
| 5.4.60  | 16        | 0.7%    |
| 5.17.1  | 16        | 0.7%    |
| 5.15.72 | 16        | 0.7%    |
| 5.15.69 | 16        | 0.7%    |
| 6.1.38  | 15        | 0.66%   |
| 5.7.0   | 15        | 0.66%   |
| 5.15.23 | 15        | 0.66%   |
| 5.4.72  | 13        | 0.57%   |
| 4.19.97 | 13        | 0.57%   |
| 6.6.8   | 12        | 0.52%   |
| 6.2.11  | 12        | 0.52%   |
| 6.0.0   | 12        | 0.52%   |
| 5.9.11  | 12        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 336       | 16.11%  |
| 6.1     | 268       | 12.85%  |
| 5.4     | 230       | 11.03%  |
| 5.10    | 226       | 10.83%  |
| 4.19    | 66        | 3.16%   |
| 5.6     | 64        | 3.07%   |
| 5.9     | 58        | 2.78%   |
| 6.6     | 55        | 2.64%   |
| 6.2     | 54        | 2.59%   |
| 5.8     | 54        | 2.59%   |
| 5.16    | 50        | 2.4%    |
| 5.14    | 50        | 2.4%    |
| 5.7     | 49        | 2.35%   |
| 5.17    | 49        | 2.35%   |
| 6.0     | 45        | 2.16%   |
| 6.5     | 42        | 2.01%   |
| 6.4     | 42        | 2.01%   |
| 6.3     | 41        | 1.97%   |
| 5.18    | 41        | 1.97%   |
| 5.11    | 41        | 1.97%   |
| 5.19    | 37        | 1.77%   |
| 5.13    | 36        | 1.73%   |
| 5.12    | 30        | 1.44%   |
| 5.5     | 17        | 0.81%   |
| 4.14    | 17        | 0.81%   |
| 5.2     | 12        | 0.58%   |
| 6.7     | 10        | 0.48%   |
| 5.1     | 10        | 0.48%   |
| 5.3     | 9         | 0.43%   |
| 5.0     | 9         | 0.43%   |
| 4.9     | 8         | 0.38%   |
| 4.4     | 8         | 0.38%   |
| 4.18    | 7         | 0.34%   |
| 4.6     | 3         | 0.14%   |
| 4.12    | 3         | 0.14%   |
| 4.20    | 2         | 0.1%    |
| 4.10    | 2         | 0.1%    |
| 4.5     | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1617      | 96.02%  |
| i686        | 31        | 1.84%   |
| aarch64     | 16        | 0.95%   |
| ppc         | 7         | 0.42%   |
| armv7l      | 3         | 0.18%   |
| armv6l      | 3         | 0.18%   |
| loongarch64 | 2         | 0.12%   |
| armv5tel    | 2         | 0.12%   |
| riscv64     | 1         | 0.06%   |
| ppc64le     | 1         | 0.06%   |
| ppc64       | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 743       | 40.91%  |
| KDE5           | 405       | 22.3%   |
| GNOME          | 223       | 12.28%  |
| XFCE           | 165       | 9.09%   |
| KDE            | 61        | 3.36%   |
| MATE           | 48        | 2.64%   |
| DWM            | 32        | 1.76%   |
| LXQt           | 19        | 1.05%   |
| Hyprland       | 16        | 0.88%   |
| i3             | 15        | 0.83%   |
| sway           | 14        | 0.77%   |
| X-Cinnamon     | 12        | 0.66%   |
| LXDE           | 9         | 0.5%    |
| Enlightenment  | 8         | 0.44%   |
| awesome        | 7         | 0.39%   |
| Xsession       | 6         | 0.33%   |
| Cinnamon       | 6         | 0.33%   |
| openbox        | 4         | 0.22%   |
| bspwm          | 4         | 0.22%   |
| Trinity        | 3         | 0.17%   |
| GNOME Classic  | 3         | 0.17%   |
| Unity          | 2         | 0.11%   |
| xmonad         | 1         | 0.06%   |
| X-Generic      | 1         | 0.06%   |
| sussy_bspwm    | 1         | 0.06%   |
| ratpoison      | 1         | 0.06%   |
| qt5ct          | 1         | 0.06%   |
| LeftWM         | 1         | 0.06%   |
| KDE6           | 1         | 0.06%   |
| ICEWM          | 1         | 0.06%   |
| i3-with-shmlog | 1         | 0.06%   |
| fvwm           | 1         | 0.06%   |
| fluxbox        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 937       | 51.4%   |
| Unknown | 346       | 18.98%  |
| Tty     | 281       | 15.41%  |
| Wayland | 259       | 14.21%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 839       | 47.29%  |
| SDDM    | 471       | 26.55%  |
| LightDM | 206       | 11.61%  |
| GDM     | 157       | 8.85%   |
| SLiM    | 32        | 1.8%    |
| XDM     | 27        | 1.52%   |
| LXDM    | 21        | 1.18%   |
| GREETD  | 11        | 0.62%   |
| TDM     | 7         | 0.39%   |
| Ly      | 1         | 0.06%   |
| KDM     | 1         | 0.06%   |
| GDM3    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 651       | 36.72%  |
| Unknown    | 259       | 14.61%  |
| C.UTF8     | 170       | 9.59%   |
| en_GB      | 112       | 6.32%   |
| de_DE      | 109       | 6.15%   |
| ru_RU      | 72        | 4.06%   |
| C          | 47        | 2.65%   |
| fr_FR      | 37        | 2.09%   |
| es_ES      | 25        | 1.41%   |
| it_IT      | 23        | 1.3%    |
| en_CA      | 22        | 1.24%   |
| cs_CZ      | 22        | 1.24%   |
| pl_PL      | 18        | 1.02%   |
| en_AU      | 18        | 1.02%   |
| pt_BR      | 13        | 0.73%   |
| zh_CN      | 12        | 0.68%   |
| en_IE      | 11        | 0.62%   |
| sv_SE      | 7         | 0.39%   |
| ru_RU.UTF8 | 7         | 0.39%   |
| POSIX      | 7         | 0.39%   |
| nl_NL      | 7         | 0.39%   |
| de_CH      | 7         | 0.39%   |
| fi_FI      | 6         | 0.34%   |
| es_AR      | 6         | 0.34%   |
| en_US.UTF8 | 6         | 0.34%   |
| el_GR      | 6         | 0.34%   |
| uk_UA      | 5         | 0.28%   |
| nl_BE      | 5         | 0.28%   |
| ja_JP      | 5         | 0.28%   |
| fr_CA      | 5         | 0.28%   |
| ca_ES      | 5         | 0.28%   |
| zh_TW      | 4         | 0.23%   |
| es_MX      | 4         | 0.23%   |
| ro_RO      | 3         | 0.17%   |
| es_CL      | 3         | 0.17%   |
| en_ZA      | 3         | 0.17%   |
| ru_UA      | 2         | 0.11%   |
| pt_PT      | 2         | 0.11%   |
| mi_NZ      | 2         | 0.11%   |
| lt_LT      | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1257      | 73.17%  |
| BIOS | 461       | 26.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1003      | 58.21%  |
| Btrfs    | 409       | 23.74%  |
| Xfs      | 85        | 4.93%   |
| F2fs     | 64        | 3.71%   |
| Zfs      | 61        | 3.54%   |
| Unknown  | 46        | 2.67%   |
| XXXXXXX  | 23        | 1.33%   |
| Reiserfs | 17        | 0.99%   |
| Overlay  | 3         | 0.17%   |
| Jfs      | 3         | 0.17%   |
| Ext3     | 3         | 0.17%   |
| XXX      | 2         | 0.12%   |
| Bcachefs | 2         | 0.12%   |
| Xtrfs    | 1         | 0.06%   |
| Ext2     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1433      | 83.9%   |
| MBR     | 182       | 10.66%  |
| Unknown | 93        | 5.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1212      | 68.55%  |
| Yes       | 556       | 31.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1164      | 67.24%  |
| Yes       | 567       | 32.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 381       | 22.62%  |
| Lenovo                  | 246       | 14.61%  |
| Dell                    | 162       | 9.62%   |
| Hewlett-Packard         | 154       | 9.14%   |
| MSI                     | 145       | 8.61%   |
| Gigabyte Technology     | 117       | 6.95%   |
| ASRock                  | 97        | 5.76%   |
| Acer                    | 52        | 3.09%   |
| Unknown                 | 33        | 1.96%   |
| Intel                   | 30        | 1.78%   |
| Apple                   | 29        | 1.72%   |
| Supermicro              | 24        | 1.43%   |
| Raspberry Pi Foundation | 14        | 0.83%   |
| Fujitsu                 | 13        | 0.77%   |
| Timi                    | 12        | 0.71%   |
| HUAWEI                  | 12        | 0.71%   |
| Samsung Electronics     | 11        | 0.65%   |
| Toshiba                 | 9         | 0.53%   |
| Framework               | 9         | 0.53%   |
| TUXEDO                  | 7         | 0.42%   |
| Razer                   | 6         | 0.36%   |
| IBM                     | 5         | 0.3%    |
| Google                  | 5         | 0.3%    |
| ASRockRack              | 5         | 0.3%    |
| TYAN Computer           | 4         | 0.24%   |
| System76                | 4         | 0.24%   |
| Notebook                | 4         | 0.24%   |
| Alienware               | 4         | 0.24%   |
| Tekram Technology       | 3         | 0.18%   |
| Star Labs               | 3         | 0.18%   |
| Sony                    | 3         | 0.18%   |
| Pegatron                | 3         | 0.18%   |
| Medion                  | 3         | 0.18%   |
| Foxconn                 | 3         | 0.18%   |
| BESSTAR Tech            | 3         | 0.18%   |
| ZOTAC                   | 2         | 0.12%   |
| win element             | 2         | 0.12%   |
| Valve                   | 2         | 0.12%   |
| Schenker                | 2         | 0.12%   |
| Purism                  | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 40        | 2.38%   |
| ASUS All Series                        | 21        | 1.25%   |
| ASUS TUF Gaming X570-PLUS              | 12        | 0.71%   |
| Supermicro Super Server                | 9         | 0.53%   |
| MSI MS-7C02                            | 9         | 0.53%   |
| ASUS ROG STRIX X570-E GAMING           | 8         | 0.48%   |
| ASUS PRIME X570-PRO                    | 8         | 0.48%   |
| ASUS PRIME X470-PRO                    | 7         | 0.42%   |
| MSI MS-7A38                            | 6         | 0.36%   |
| Dell XPS 15 9570                       | 6         | 0.36%   |
| ASUS TUF Gaming B550-PLUS              | 6         | 0.36%   |
| ASUS ROG Strix G513QY_G513QY           | 6         | 0.36%   |
| ASUS PRIME X370-PRO                    | 6         | 0.36%   |
| MSI MS-7C91                            | 5         | 0.3%    |
| MSI MS-7C37                            | 5         | 0.3%    |
| MSI MS-7C35                            | 5         | 0.3%    |
| HP Pavilion Notebook                   | 5         | 0.3%    |
| HP OMEN by Laptop                      | 5         | 0.3%    |
| Gigabyte X570 AORUS ELITE              | 5         | 0.3%    |
| ASUS ROG STRIX B450-F GAMING           | 5         | 0.3%    |
| ASUS ROG CROSSHAIR VIII HERO           | 5         | 0.3%    |
| ASUS PRIME X570-P                      | 5         | 0.3%    |
| ASRock B450 Pro4                       | 5         | 0.3%    |
| MSI MS-7B89                            | 4         | 0.24%   |
| MSI MS-7B86                            | 4         | 0.24%   |
| MSI MS-7B79                            | 4         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec1xxx    | 4         | 0.24%   |
| HP Laptop 14-dk1xxx                    | 4         | 0.24%   |
| Gigabyte B450M DS3H                    | 4         | 0.24%   |
| Framework Laptop (13th Gen Intel Core) | 4         | 0.24%   |
| Dell XPS 17 9710                       | 4         | 0.24%   |
| Dell XPS 15 7590                       | 4         | 0.24%   |
| Dell XPS 13 9310                       | 4         | 0.24%   |
| ASUS Z170 PRO GAMING                   | 4         | 0.24%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II  | 4         | 0.24%   |
| ASUS ROG STRIX X570-I GAMING           | 4         | 0.24%   |
| ASUS ROG STRIX B550-F GAMING           | 4         | 0.24%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 4         | 0.24%   |
| ASUS ROG CROSSHAIR VII HERO            | 4         | 0.24%   |
| ASUS PRIME B450M-A                     | 4         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 141       | 8.37%   |
| ASUS ROG          | 98        | 5.82%   |
| ASUS PRIME        | 68        | 4.04%   |
| Dell Latitude     | 46        | 2.73%   |
| ASUS TUF          | 45        | 2.67%   |
| Dell XPS          | 43        | 2.55%   |
| Unknown           | 40        | 2.38%   |
| Acer Aspire       | 31        | 1.84%   |
| Lenovo IdeaPad    | 27        | 1.6%    |
| HP EliteBook      | 27        | 1.6%    |
| Lenovo Legion     | 26        | 1.54%   |
| HP Pavilion       | 26        | 1.54%   |
| Dell Precision    | 23        | 1.37%   |
| ASUS All          | 21        | 1.25%   |
| HP Laptop         | 20        | 1.19%   |
| Dell Inspiron     | 20        | 1.19%   |
| Lenovo Yoga       | 18        | 1.07%   |
| ASUS VivoBook     | 18        | 1.07%   |
| RPi Raspberry     | 14        | 0.83%   |
| HP OMEN           | 13        | 0.77%   |
| Gigabyte X570     | 13        | 0.77%   |
| ASRock X570       | 13        | 0.77%   |
| Dell OptiPlex     | 12        | 0.71%   |
| HP ProBook        | 11        | 0.65%   |
| ASUS ZenBook      | 10        | 0.59%   |
| Supermicro Super  | 9         | 0.53%   |
| MSI MS-7C02       | 9         | 0.53%   |
| Gigabyte B450M    | 9         | 0.53%   |
| Framework Laptop  | 9         | 0.53%   |
| Acer Swift        | 9         | 0.53%   |
| HP ProLiant       | 8         | 0.48%   |
| Gigabyte B450     | 8         | 0.48%   |
| ASUS ASUS         | 8         | 0.48%   |
| ASRock X370       | 8         | 0.48%   |
| Toshiba Satellite | 7         | 0.42%   |
| Timi RedmiBook    | 7         | 0.42%   |
| HP ZBook          | 7         | 0.42%   |
| HP Compaq         | 7         | 0.42%   |
| Acer Nitro        | 7         | 0.42%   |
| Razer Blade       | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 252       | 14.96%  |
| 2020    | 223       | 13.24%  |
| 2018    | 202       | 12%     |
| 2021    | 185       | 10.99%  |
| 2022    | 104       | 6.18%   |
| 2017    | 98        | 5.82%   |
| 2012    | 75        | 4.45%   |
| 2015    | 73        | 4.33%   |
| 2014    | 68        | 4.04%   |
| 2013    | 65        | 3.86%   |
| 2016    | 62        | 3.68%   |
| 2011    | 51        | 3.03%   |
| 2010    | 47        | 2.79%   |
| 2023    | 40        | 2.38%   |
| 2008    | 36        | 2.14%   |
| Unknown | 35        | 2.08%   |
| 2009    | 30        | 1.78%   |
| 2007    | 13        | 0.77%   |
| 2006    | 7         | 0.42%   |
| 2005    | 5         | 0.3%    |
| 2004    | 5         | 0.3%    |
| 2003    | 4         | 0.24%   |
| 2000    | 3         | 0.18%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 791       | 46.97%  |
| Desktop        | 760       | 45.13%  |
| Server         | 43        | 2.55%   |
| Convertible    | 39        | 2.32%   |
| System on chip | 20        | 1.19%   |
| Mini pc        | 17        | 1.01%   |
| All in one     | 7         | 0.42%   |
| Tablet         | 5         | 0.3%    |
| Phone          | 1         | 0.06%   |
| Stick pc       | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1657      | 97.93%  |
| Enabled  | 35        | 2.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1672      | 99.29%  |
| Yes  | 12        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 430       | 24.83%  |
| 16.01-24.0      | 398       | 22.98%  |
| 8.01-16.0       | 265       | 15.3%   |
| 4.01-8.0        | 204       | 11.78%  |
| 64.01-256.0     | 194       | 11.2%   |
| 3.01-4.0        | 90        | 5.2%    |
| 24.01-32.0      | 71        | 4.1%    |
| 1.01-2.0        | 30        | 1.73%   |
| 0.51-1.0        | 20        | 1.15%   |
| 2.01-3.0        | 19        | 1.1%    |
| 0.01-0.5        | 8         | 0.46%   |
| More than 256.0 | 3         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 411       | 20.23%  |
| 4.01-8.0    | 381       | 18.75%  |
| 2.01-3.0    | 345       | 16.98%  |
| 3.01-4.0    | 235       | 11.56%  |
| 8.01-16.0   | 205       | 10.09%  |
| 0.01-0.5    | 185       | 9.1%    |
| 0.51-1.0    | 177       | 8.71%   |
| 16.01-24.0  | 55        | 2.71%   |
| 32.01-64.0  | 18        | 0.89%   |
| 24.01-32.0  | 13        | 0.64%   |
| 64.01-256.0 | 4         | 0.2%    |
| 0           | 3         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 782       | 43.96%  |
| 2      | 463       | 26.03%  |
| 3      | 203       | 11.41%  |
| 4      | 119       | 6.69%   |
| 5      | 82        | 4.61%   |
| 6      | 43        | 2.42%   |
| 7      | 33        | 1.85%   |
| 8      | 17        | 0.96%   |
| 0      | 12        | 0.67%   |
| 9      | 6         | 0.34%   |
| 13     | 4         | 0.22%   |
| 10     | 4         | 0.22%   |
| 12     | 3         | 0.17%   |
| 21     | 2         | 0.11%   |
| 31     | 1         | 0.06%   |
| 26     | 1         | 0.06%   |
| 19     | 1         | 0.06%   |
| 18     | 1         | 0.06%   |
| 17     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1351      | 78.91%  |
| Yes       | 361       | 21.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1452      | 85.56%  |
| No        | 245       | 14.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1168      | 68.95%  |
| No        | 526       | 31.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1081      | 63.25%  |
| No        | 628       | 36.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 361       | 21.15%  |
| Germany      | 239       | 14%     |
| Russia       | 148       | 8.67%   |
| UK           | 86        | 5.04%   |
| France       | 78        | 4.57%   |
| Canada       | 66        | 3.87%   |
| Spain        | 56        | 3.28%   |
| Poland       | 52        | 3.05%   |
| China        | 52        | 3.05%   |
| Czechia      | 42        | 2.46%   |
| Italy        | 39        | 2.28%   |
| Sweden       | 35        | 2.05%   |
| Netherlands  | 34        | 1.99%   |
| Australia    | 34        | 1.99%   |
| Finland      | 31        | 1.82%   |
| Ukraine      | 24        | 1.41%   |
| Brazil       | 24        | 1.41%   |
| Switzerland  | 22        | 1.29%   |
| Greece       | 18        | 1.05%   |
| Belgium      | 17        | 1%      |
| Austria      | 15        | 0.88%   |
| Mexico       | 14        | 0.82%   |
| Japan        | 13        | 0.76%   |
| Turkey       | 12        | 0.7%    |
| Romania      | 11        | 0.64%   |
| Norway       | 11        | 0.64%   |
| Belarus      | 11        | 0.64%   |
| Hungary      | 10        | 0.59%   |
| Hong Kong    | 10        | 0.59%   |
| Slovakia     | 9         | 0.53%   |
| India        | 9         | 0.53%   |
| Argentina    | 9         | 0.53%   |
| Taiwan       | 8         | 0.47%   |
| Ireland      | 7         | 0.41%   |
| Portugal     | 6         | 0.35%   |
| Indonesia    | 6         | 0.35%   |
| Bulgaria     | 6         | 0.35%   |
| Vietnam      | 5         | 0.29%   |
| South Africa | 5         | 0.29%   |
| Slovenia     | 5         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 58        | 3.08%   |
| Moscow            | 50        | 2.66%   |
| St Petersburg     | 22        | 1.17%   |
| Athens            | 18        | 0.96%   |
| Sydney            | 17        | 0.9%    |
| Warsaw            | 16        | 0.85%   |
| Munich            | 15        | 0.8%    |
| Paris             | 14        | 0.74%   |
| Frankfurt am Main | 14        | 0.74%   |
| Los Angeles       | 13        | 0.69%   |
| Helsinki          | 13        | 0.69%   |
| Amsterdam         | 13        | 0.69%   |
| Vancouver         | 12        | 0.64%   |
| Cieszyn           | 12        | 0.64%   |
| Prague            | 11        | 0.58%   |
| Milan             | 11        | 0.58%   |
| Kyiv              | 11        | 0.58%   |
| Vladivostok       | 10        | 0.53%   |
| New York          | 10        | 0.53%   |
| Beijing           | 10        | 0.53%   |
| Seattle           | 9         | 0.48%   |
| Guangzhou         | 9         | 0.48%   |
| Wuelfrath         | 8         | 0.42%   |
| Vienna            | 8         | 0.42%   |
| Stockholm         | 8         | 0.42%   |
| Minsk             | 8         | 0.42%   |
| Melbourne         | 8         | 0.42%   |
| Barcelona         | 8         | 0.42%   |
| Sao Paulo         | 7         | 0.37%   |
| Oulu              | 7         | 0.37%   |
| Ottawa            | 7         | 0.37%   |
| Madrid            | 7         | 0.37%   |
| London            | 7         | 0.37%   |
| Hamburg           | 7         | 0.37%   |
| Dublin            | 7         | 0.37%   |
| Bothell           | 7         | 0.37%   |
| Zurich            | 6         | 0.32%   |
| Woolwich          | 6         | 0.32%   |
| Weatherford       | 6         | 0.32%   |
| Sterling          | 6         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 632       | 1323   | 21.68%  |
| WDC                         | 453       | 1026   | 15.54%  |
| Seagate                     | 343       | 756    | 11.77%  |
| Sandisk                     | 158       | 229    | 5.42%   |
| Kingston                    | 140       | 201    | 4.8%    |
| Toshiba                     | 132       | 239    | 4.53%   |
| Intel                       | 129       | 214    | 4.43%   |
| Crucial                     | 88        | 165    | 3.02%   |
| SK hynix                    | 83        | 105    | 2.85%   |
| Unknown                     | 76        | 112    | 2.61%   |
| Hitachi                     | 66        | 188    | 2.26%   |
| HGST                        | 61        | 103    | 2.09%   |
| Micron Technology           | 50        | 67     | 1.72%   |
| Phison Electronics          | 44        | 58     | 1.51%   |
| A-DATA Technology           | 42        | 59     | 1.44%   |
| KIOXIA                      | 28        | 37     | 0.96%   |
| Phison                      | 22        | 34     | 0.75%   |
| Micron/Crucial Technology   | 20        | 26     | 0.69%   |
| Kingston Technology Company | 19        | 21     | 0.65%   |
| Corsair                     | 19        | 34     | 0.65%   |
| OCZ                         | 18        | 26     | 0.62%   |
| China                       | 17        | 43     | 0.58%   |
| Silicon Motion              | 13        | 20     | 0.45%   |
| Apple                       | 12        | 14     | 0.41%   |
| GOODRAM                     | 11        | 68     | 0.38%   |
| Transcend                   | 10        | 15     | 0.34%   |
| Realtek Semiconductor       | 8         | 16     | 0.27%   |
| PNY                         | 8         | 13     | 0.27%   |
| Patriot                     | 8         | 12     | 0.27%   |
| Fujitsu                     | 8         | 11     | 0.27%   |
| ADATA Technology            | 8         | 12     | 0.27%   |
| XPG                         | 7         | 14     | 0.24%   |
| SPCC                        | 7         | 9      | 0.24%   |
| Plextor                     | 7         | 8      | 0.24%   |
| MAXIO Technology (Hangzhou) | 7         | 8      | 0.24%   |
| LITEONIT                    | 7         | 9      | 0.24%   |
| Team                        | 6         | 13     | 0.21%   |
| Mushkin                     | 6         | 6      | 0.21%   |
| Unknown                     | 6         | 7      | 0.21%   |
| Yangtze Memory Technologies | 5         | 7      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 83        | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 60        | 1.71%   |
| Samsung SSD 860 EVO 1TB                            | 33        | 0.94%   |
| Samsung SSD 850 EVO 250GB                          | 31        | 0.88%   |
| Samsung SSD 980 1TB                                | 26        | 0.74%   |
| Samsung SSD 860 EVO 500GB                          | 26        | 0.74%   |
| Samsung SSD 850 EVO 500GB                          | 26        | 0.74%   |
| HGST HTS721010A9E630 1TB                           | 26        | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 23        | 0.66%   |
| Kingston SA400S37240G 240GB SSD                    | 22        | 0.63%   |
| Samsung SSD 860 EVO 250GB                          | 21        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                     | 19        | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB                     | 19        | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB                     | 16        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                    | 16        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                        | 16        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 15        | 0.43%   |
| Unknown MMC Card  32GB                             | 15        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                     | 15        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                       | 15        | 0.43%   |
| Samsung SSD 970 EVO 500GB                          | 15        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                    | 14        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 14        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 14        | 0.4%    |
| Intel SSD 660P Series 1024GB                       | 14        | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                     | 13        | 0.37%   |
| Samsung SSD 970 EVO 250GB                          | 13        | 0.37%   |
| Samsung SSD 970 EVO 1TB                            | 13        | 0.37%   |
| Phison E12 NVMe Controller 1TB                     | 13        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 12        | 0.34%   |
| Unknown MMC Card  128GB                            | 12        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                     | 12        | 0.34%   |
| Samsung SSD 980 PRO 1TB                            | 12        | 0.34%   |
| Samsung SSD 870 EVO 1TB                            | 12        | 0.34%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 12        | 0.34%   |
| Kingston SA400S37120G 120GB SSD                    | 12        | 0.34%   |
| WDC WD40EZRZ-00GXCB0 4TB                           | 11        | 0.31%   |
| WDC WD20EFRX-68EUZN0 2TB                           | 11        | 0.31%   |
| Toshiba DT01ACA100 1TB                             | 11        | 0.31%   |
| Samsung SSD 970 PRO 512GB                          | 11        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 343       | 829    | 35.54%  |
| Seagate             | 334       | 739    | 34.61%  |
| Toshiba             | 90        | 185    | 9.33%   |
| Hitachi             | 66        | 188    | 6.84%   |
| HGST                | 61        | 103    | 6.32%   |
| Samsung Electronics | 30        | 45     | 3.11%   |
| Fujitsu             | 8         | 11     | 0.83%   |
| IBM                 | 5         | 6      | 0.52%   |
| Unknown             | 4         | 5      | 0.41%   |
| IBM/Hitachi         | 3         | 4      | 0.31%   |
| TO Exter            | 2         | 2      | 0.21%   |
| MDT                 | 2         | 2      | 0.21%   |
| Maxtor              | 2         | 2      | 0.21%   |
| LaCie               | 2         | 12     | 0.21%   |
| Apple               | 2         | 2      | 0.21%   |
| Teleplan            | 1         | 4      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| NETAPP              | 1         | 3      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 2      | 0.1%    |
| FNK TECH            | 1         | 1      | 0.1%    |
| Dyconn H            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |
| AFAYA               | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 299       | 547    | 32.19%  |
| Kingston            | 103       | 144    | 11.09%  |
| SanDisk             | 81        | 124    | 8.72%   |
| Crucial             | 80        | 150    | 8.61%   |
| WDC                 | 59        | 82     | 6.35%   |
| Intel               | 41        | 54     | 4.41%   |
| A-DATA Technology   | 27        | 38     | 2.91%   |
| OCZ                 | 17        | 25     | 1.83%   |
| China               | 17        | 43     | 1.83%   |
| Micron Technology   | 16        | 26     | 1.72%   |
| Toshiba             | 13        | 15     | 1.4%    |
| SK hynix            | 13        | 14     | 1.4%    |
| Corsair             | 12        | 19     | 1.29%   |
| GOODRAM             | 11        | 68     | 1.18%   |
| Transcend           | 8         | 13     | 0.86%   |
| Apple               | 8         | 9      | 0.86%   |
| PNY                 | 7         | 12     | 0.75%   |
| LITEONIT            | 7         | 9      | 0.75%   |
| SPCC                | 6         | 8      | 0.65%   |
| Plextor             | 6         | 6      | 0.65%   |
| Patriot             | 6         | 10     | 0.65%   |
| Team                | 5         | 7      | 0.54%   |
| Mushkin             | 5         | 5      | 0.54%   |
| Unknown             | 5         | 6      | 0.54%   |
| Verbatim            | 4         | 4      | 0.43%   |
| Intenso             | 4         | 5      | 0.43%   |
| T-FORCE             | 3         | 8      | 0.32%   |
| Seagate             | 3         | 6      | 0.32%   |
| SABRENT             | 3         | 3      | 0.32%   |
| Netac               | 3         | 3      | 0.32%   |
| KingSpec            | 3         | 4      | 0.32%   |
| Dogfish             | 3         | 3      | 0.32%   |
| Apacer              | 3         | 5      | 0.32%   |
| Smartbuy            | 2         | 2      | 0.22%   |
| MyDigitalSSD        | 2         | 2      | 0.22%   |
| LITEON              | 2         | 4      | 0.22%   |
| Linux               | 2         | 2      | 0.22%   |
| Lexar               | 2         | 2      | 0.22%   |
| Lenovo              | 2         | 3      | 0.22%   |
| KingDian            | 2         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 949       | 1717   | 37.61%  |
| SSD     | 755       | 1550   | 29.92%  |
| HDD     | 744       | 2153   | 29.49%  |
| MMC     | 65        | 95     | 2.58%   |
| Unknown | 10        | 21     | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1100      | 3614   | 50.55%  |
| NVMe | 948       | 1716   | 43.57%  |
| MMC  | 65        | 95     | 2.99%   |
| SAS  | 63        | 111    | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 742       | 1457   | 43.21%  |
| 0.51-1.0   | 491       | 879    | 28.6%   |
| 1.01-2.0   | 219       | 525    | 12.75%  |
| 3.01-4.0   | 115       | 277    | 6.7%    |
| 4.01-10.0  | 68        | 280    | 3.96%   |
| 2.01-3.0   | 62        | 219    | 3.61%   |
| 10.01-20.0 | 19        | 65     | 1.11%   |
| 20.01-50.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 347       | 18.94%  |
| 501-1000       | 316       | 17.25%  |
| 101-250        | 315       | 17.19%  |
| 1001-2000      | 220       | 12.01%  |
| More than 3000 | 215       | 11.74%  |
| Unknown        | 104       | 5.68%   |
| 2001-3000      | 92        | 5.02%   |
| 1-20           | 91        | 4.97%   |
| 51-100         | 90        | 4.91%   |
| 21-50          | 42        | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 403       | 20.87%  |
| 101-250        | 276       | 14.29%  |
| 21-50          | 269       | 13.93%  |
| 251-500        | 239       | 12.38%  |
| 51-100         | 183       | 9.48%   |
| 501-1000       | 180       | 9.32%   |
| 1001-2000      | 130       | 6.73%   |
| Unknown        | 104       | 5.39%   |
| More than 3000 | 97        | 5.02%   |
| 2001-3000      | 50        | 2.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                     | 8         | 9      | 2.54%   |
| Seagate ST3500418AS 500GB                    | 6         | 7      | 1.9%    |
| Seagate ST500DM002-1BC142 500GB              | 5         | 5      | 1.59%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4         | 14     | 1.27%   |
| Seagate ST500DM002-1BD142 500GB              | 4         | 4      | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 9      | 1.27%   |
| Samsung Electronics SSD 980 1TB              | 4         | 4      | 1.27%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 3         | 3      | 0.95%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 3         | 8      | 0.95%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 3         | 7      | 0.95%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 3         | 6      | 0.95%   |
| WDC WD2002FAEX-007BA0 2TB                    | 3         | 3      | 0.95%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3         | 15     | 0.95%   |
| Samsung Electronics SSD 850 EVO 1TB          | 3         | 3      | 0.95%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 3         | 3      | 0.95%   |
| IBM DJSA-220 12GB                            | 3         | 3      | 0.95%   |
| Hitachi HDS722020ALA330 2TB                  | 3         | 17     | 0.95%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2         | 5      | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB                     | 2         | 2      | 0.63%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2         | 3      | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2         | 2      | 0.63%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 2         | 2      | 0.63%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2         | 2      | 0.63%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 2         | 2      | 0.63%   |
| Toshiba DT01ACA200 2TB                       | 2         | 2      | 0.63%   |
| SK hynix PC711 HFS512GDE9X073N 512GB         | 2         | 3      | 0.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 2         | 2      | 0.63%   |
| Seagate ST4000DM000-1F2168 4TB               | 2         | 2      | 0.63%   |
| Seagate ST31000340NS 1TB                     | 2         | 3      | 0.63%   |
| Seagate ST3000DM001-9YN166 3TB               | 2         | 3      | 0.63%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 2      | 0.63%   |
| Seagate ST2000DX002-2DV164 2TB               | 2         | 2      | 0.63%   |
| Seagate ST2000DL003-9VT166 2TB               | 2         | 3      | 0.63%   |
| Seagate ST1000NM0011 1TB                     | 2         | 6      | 0.63%   |
| SanDisk SSD PLUS 480GB                       | 2         | 2      | 0.63%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2      | 0.63%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 0.63%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2         | 3      | 0.63%   |
| Samsung Electronics SSD 870 EVO 1TB          | 2         | 9      | 0.63%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2         | 4      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 70        | 109    | 23.33%  |
| WDC                         | 66        | 125    | 22%     |
| Samsung Electronics         | 34        | 54     | 11.33%  |
| Hitachi                     | 18        | 34     | 6%      |
| Toshiba                     | 17        | 19     | 5.67%   |
| HGST                        | 15        | 21     | 5%      |
| SanDisk                     | 9         | 11     | 3%      |
| Intel                       | 9         | 11     | 3%      |
| Kingston                    | 8         | 8      | 2.67%   |
| SK hynix                    | 7         | 10     | 2.33%   |
| Crucial                     | 7         | 7      | 2.33%   |
| IBM                         | 4         | 4      | 1.33%   |
| Fujitsu                     | 4         | 4      | 1.33%   |
| Realtek Semiconductor       | 3         | 9      | 1%      |
| OCZ                         | 3         | 3      | 1%      |
| A-DATA Technology           | 3         | 3      | 1%      |
| PNY                         | 2         | 3      | 0.67%   |
| Plextor                     | 2         | 2      | 0.67%   |
| MDT                         | 2         | 2      | 0.67%   |
| IBM/Hitachi                 | 2         | 2      | 0.67%   |
| Corsair                     | 2         | 5      | 0.67%   |
| China                       | 2         | 3      | 0.67%   |
| Transcend                   | 1         | 1      | 0.33%   |
| SPCC                        | 1         | 1      | 0.33%   |
| Mushkin                     | 1         | 1      | 0.33%   |
| Maxtor                      | 1         | 1      | 0.33%   |
| LITEON                      | 1         | 3      | 0.33%   |
| Kingston Technology Company | 1         | 1      | 0.33%   |
| HGST HTS                    | 1         | 1      | 0.33%   |
| Emtec                       | 1         | 2      | 0.33%   |
| Apple                       | 1         | 1      | 0.33%   |
| 2.5"                        | 1         | 1      | 0.33%   |
| Unknown                     | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 109    | 34.15%  |
| WDC                 | 64        | 123    | 31.22%  |
| Hitachi             | 18        | 34     | 8.78%   |
| Toshiba             | 16        | 18     | 7.8%    |
| HGST                | 15        | 21     | 7.32%   |
| Samsung Electronics | 6         | 7      | 2.93%   |
| IBM                 | 4         | 4      | 1.95%   |
| Fujitsu             | 4         | 4      | 1.95%   |
| MDT                 | 2         | 2      | 0.98%   |
| IBM/Hitachi         | 2         | 2      | 0.98%   |
| Maxtor              | 1         | 1      | 0.49%   |
| HGST HTS            | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 194       | 328    | 67.13%  |
| SSD  | 70        | 96     | 24.22%  |
| NVMe | 25        | 39     | 8.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB                 | 2         | 2      | 20%     |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 10%     |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 2      | 10%     |
| Seagate ST3500630AS 500GB                        | 1         | 2      | 10%     |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 10%     |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 10%     |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 10%     |
| Hitachi HTS723232L9A360 320GB                    | 1         | 1      | 10%     |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 3      | 20%     |
| Toshiba             | 2         | 2      | 20%     |
| Seagate             | 2         | 3      | 20%     |
| Samsung Electronics | 2         | 3      | 20%     |
| Hitachi             | 2         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1478      | 4559   | 73.9%   |
| Malfunc  | 275       | 463    | 13.75%  |
| Detected | 237       | 501    | 11.85%  |
| Failed   | 10        | 13     | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 862       | 33.8%   |
| AMD                              | 488       | 19.14%  |
| Samsung Electronics              | 411       | 16.12%  |
| SanDisk                          | 150       | 5.88%   |
| ASMedia Technology               | 80        | 3.14%   |
| Phison Electronics               | 75        | 2.94%   |
| SK hynix                         | 70        | 2.75%   |
| Kingston Technology Company      | 57        | 2.24%   |
| Micron Technology                | 35        | 1.37%   |
| Toshiba America Info Systems     | 34        | 1.33%   |
| Marvell Technology Group         | 32        | 1.25%   |
| KIOXIA                           | 30        | 1.18%   |
| Micron/Crucial Technology        | 27        | 1.06%   |
| ADATA Technology                 | 26        | 1.02%   |
| Nvidia                           | 24        | 0.94%   |
| JMicron Technology               | 20        | 0.78%   |
| Silicon Motion                   | 18        | 0.71%   |
| Broadcom / LSI                   | 18        | 0.71%   |
| LSI Logic / Symbios Logic        | 14        | 0.55%   |
| Realtek Semiconductor            | 11        | 0.43%   |
| Seagate Technology               | 8         | 0.31%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.27%   |
| Adaptec                          | 6         | 0.24%   |
| Yangtze Memory Technologies      | 5         | 0.2%    |
| Solid State Storage Technology   | 5         | 0.2%    |
| Silicon Image                    | 5         | 0.2%    |
| INNOGRIT                         | 5         | 0.2%    |
| VIA Technologies                 | 3         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| Lite-On Technology               | 3         | 0.12%   |
| Union Memory (Shenzhen)          | 2         | 0.08%   |
| Loongson Technology              | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| 3ware                            | 2         | 0.08%   |
| Transcend                        | 1         | 0.04%   |
| Solidigm                         | 1         | 0.04%   |
| OCZ Technology Group             | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 339       | 11.68%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 237       | 8.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 100       | 3.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 90        | 3.1%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 69        | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 58        | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 57        | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 55        | 1.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 54        | 1.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 51        | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 48        | 1.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 43        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 43        | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 42        | 1.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 40        | 1.38%   |
| Intel SSD 660P Series                                                          | 37        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 36        | 1.24%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 32        | 1.1%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 30        | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 1%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 1%      |
| AMD 600 Series Chipset SATA Controller                                         | 29        | 1%      |
| Intel Comet Lake SATA AHCI Controller                                          | 27        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 26        | 0.9%    |
| Phison E12 NVMe Controller                                                     | 25        | 0.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 25        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 23        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 21        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 21        | 0.72%   |
| AMD X370 Series Chipset SATA Controller                                        | 21        | 0.72%   |
| Phison E16 PCIe4 NVMe Controller                                               | 20        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 20        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 19        | 0.65%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 18        | 0.62%   |
| Intel SATA Controller [RAID mode]                                              | 17        | 0.59%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 16        | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 16        | 0.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1191      | 48.77%  |
| NVMe | 955       | 39.11%  |
| RAID | 133       | 5.45%   |
| IDE  | 126       | 5.16%   |
| SAS  | 29        | 1.19%   |
| SCSI | 8         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 1022      | 60.69%  |
| AMD                      | 626       | 37.17%  |
| ARM                      | 21        | 1.25%   |
| Marvell Semiconductor    | 3         | 0.18%   |
| Loongson                 | 2         | 0.12%   |
| thead,c906               | 1         | 0.06%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.06%   |
| PowerMac8,1              | 1         | 0.06%   |
| PowerMac3,6              | 1         | 0.06%   |
| PowerMac10,2             | 1         | 0.06%   |
| PowerBook6,7             | 1         | 0.06%   |
| PowerBook5,6             | 1         | 0.06%   |
| PowerBook5,5             | 1         | 0.06%   |
| PowerBook5,4             | 1         | 0.06%   |
| PowerBook3,4             | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 1.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 1.41%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 23        | 1.36%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 1.3%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 1.24%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 20        | 1.18%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 20        | 1.18%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 19        | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.06%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 1.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.94%   |
| ARM Processor                                 | 16        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 0.88%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 15        | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 14        | 0.82%   |
| Intel 12th Gen Core i7-12700H                 | 13        | 0.77%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 13        | 0.77%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 13        | 0.77%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 13        | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.71%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 12        | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 10        | 0.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 10        | 0.59%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.59%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 10        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.59%   |
| AMD FX-8350 Eight-Core Processor              | 10        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.53%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 363       | 21.45%  |
| Intel Core i5          | 227       | 13.42%  |
| AMD Ryzen 7            | 205       | 12.12%  |
| Other                  | 188       | 11.11%  |
| AMD Ryzen 5            | 145       | 8.57%   |
| AMD Ryzen 9            | 117       | 6.91%   |
| Intel Xeon             | 81        | 4.79%   |
| AMD Ryzen 7 PRO        | 33        | 1.95%   |
| Intel Core i3          | 27        | 1.6%    |
| Intel Celeron          | 27        | 1.6%    |
| Intel Atom             | 27        | 1.6%    |
| Intel Core i9          | 26        | 1.54%   |
| AMD FX                 | 25        | 1.48%   |
| Intel Core 2 Duo       | 22        | 1.3%    |
| Intel Pentium          | 20        | 1.18%   |
| AMD Ryzen 3            | 17        | 1%      |
| AMD Ryzen Threadripper | 11        | 0.65%   |
| AMD Phenom II X4       | 11        | 0.65%   |
| Intel Core 2 Quad      | 10        | 0.59%   |
| Intel Pentium M        | 9         | 0.53%   |
| AMD Ryzen 5 PRO        | 9         | 0.53%   |
| Intel Pentium 4        | 8         | 0.47%   |
| AMD A6                 | 7         | 0.41%   |
| AMD Phenom II X6       | 6         | 0.35%   |
| Intel Pentium Silver   | 5         | 0.3%    |
| AMD A10                | 5         | 0.3%    |
| Intel Pentium III      | 4         | 0.24%   |
| ARM BCM                | 4         | 0.24%   |
| AMD Sempron            | 4         | 0.24%   |
| AMD EPYC               | 4         | 0.24%   |
| AMD Athlon 64 X2       | 4         | 0.24%   |
| AMD Athlon             | 4         | 0.24%   |
| Intel Core m3          | 3         | 0.18%   |
| Intel Core 2           | 3         | 0.18%   |
| AMD E                  | 3         | 0.18%   |
| AMD Athlon II X3       | 3         | 0.18%   |
| AMD A8                 | 3         | 0.18%   |
| Intel Genuine          | 2         | 0.12%   |
| Intel Core Duo         | 2         | 0.12%   |
| AMD E1                 | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 549       | 32.41%  |
| 8       | 324       | 19.13%  |
| 6       | 279       | 16.47%  |
| 2       | 260       | 15.35%  |
| 12      | 91        | 5.37%   |
| 16      | 65        | 3.84%   |
| 1       | 48        | 2.83%   |
| 14      | 28        | 1.65%   |
| 10      | 13        | 0.77%   |
| Unknown | 13        | 0.77%   |
| 3       | 7         | 0.41%   |
| 32      | 5         | 0.3%    |
| 24      | 4         | 0.24%   |
| 28      | 2         | 0.12%   |
| 20      | 2         | 0.12%   |
| 64      | 1         | 0.06%   |
| 44      | 1         | 0.06%   |
| 22      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1640      | 97.27%  |
| 2       | 34        | 2.02%   |
| Unknown | 12        | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1352      | 79.76%  |
| 1       | 328       | 19.35%  |
| Unknown | 13        | 0.77%   |
| 4       | 2         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1634      | 97.03%  |
| 32-bit         | 35        | 2.08%   |
| Unknown        | 15        | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 331       | 18.61%  |
| 0x906ea    | 75        | 4.22%   |
| 0x08701021 | 68        | 3.82%   |
| 0x506e3    | 55        | 3.09%   |
| 0x306a9    | 50        | 2.81%   |
| 0x306c3    | 49        | 2.75%   |
| 0x806ec    | 47        | 2.64%   |
| 0x0a50000c | 47        | 2.64%   |
| 0x806c1    | 42        | 2.36%   |
| 0x0800820d | 41        | 2.3%    |
| 0x906e9    | 40        | 2.25%   |
| 0x806ea    | 36        | 2.02%   |
| 0x206a7    | 36        | 2.02%   |
| 0x08701013 | 35        | 1.97%   |
| 0x08600106 | 34        | 1.91%   |
| 0x0a201016 | 31        | 1.74%   |
| 0x806e9    | 28        | 1.57%   |
| 0x906ed    | 26        | 1.46%   |
| 0x0a601203 | 25        | 1.41%   |
| 0x08108109 | 21        | 1.18%   |
| 0x08001138 | 21        | 1.18%   |
| 0xa0652    | 20        | 1.12%   |
| 0x0a201009 | 20        | 1.12%   |
| 0x806d1    | 19        | 1.07%   |
| 0x40651    | 19        | 1.07%   |
| 0x0a20120a | 19        | 1.07%   |
| 0x906a3    | 18        | 1.01%   |
| 0x406e3    | 17        | 0.96%   |
| 0x1067a    | 17        | 0.96%   |
| 0x90672    | 14        | 0.79%   |
| 0x306d4    | 14        | 0.79%   |
| 0x0a50000d | 14        | 0.79%   |
| 0x08600103 | 14        | 0.79%   |
| 0x306f2    | 13        | 0.73%   |
| 0x206c2    | 13        | 0.73%   |
| 0x0a404102 | 13        | 0.73%   |
| 0x08608103 | 13        | 0.73%   |
| 0xa0671    | 12        | 0.67%   |
| 0x306e4    | 12        | 0.67%   |
| 0x08108102 | 12        | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 309       | 18.2%   |
| Zen 2            | 190       | 11.19%  |
| Zen 3            | 151       | 8.89%   |
| Unknown          | 130       | 7.66%   |
| Haswell          | 99        | 5.83%   |
| Zen+             | 89        | 5.24%   |
| Skylake          | 83        | 4.89%   |
| IvyBridge        | 70        | 4.12%   |
| Alderlake Hybrid | 66        | 3.89%   |
| SandyBridge      | 56        | 3.3%    |
| TigerLake        | 48        | 2.83%   |
| Icelake          | 46        | 2.71%   |
| CometLake        | 44        | 2.59%   |
| Zen              | 43        | 2.53%   |
| Broadwell        | 32        | 1.88%   |
| Westmere         | 27        | 1.59%   |
| Silvermont       | 24        | 1.41%   |
| Penryn           | 24        | 1.41%   |
| Piledriver       | 23        | 1.35%   |
| K10              | 23        | 1.35%   |
| P6               | 18        | 1.06%   |
| Bonnell          | 17        | 1%      |
| Core             | 15        | 0.88%   |
| Goldmont plus    | 11        | 0.65%   |
| Nehalem          | 9         | 0.53%   |
| K8 Hammer        | 9         | 0.53%   |
| NetBurst         | 8         | 0.47%   |
| Steamroller      | 5         | 0.29%   |
| Bulldozer        | 5         | 0.29%   |
| Bobcat           | 5         | 0.29%   |
| Jaguar           | 4         | 0.24%   |
| Goldmont         | 4         | 0.24%   |
| Excavator        | 4         | 0.24%   |
| Tremont          | 2         | 0.12%   |
| Puma             | 2         | 0.12%   |
| K10 Llano        | 2         | 0.12%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 697       | 34.76%  |
| Nvidia                           | 647       | 32.27%  |
| AMD                              | 608       | 30.32%  |
| ASPEED Technology                | 31        | 1.55%   |
| Matrox Electronics Systems       | 19        | 0.95%   |
| Loongson Technology              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 95        | 4.53%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 66        | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 61        | 2.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 51        | 2.43%   |
| Intel UHD Graphics 620                                                      | 47        | 2.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 45        | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 41        | 1.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 38        | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 35        | 1.67%   |
| Intel HD Graphics 530                                                       | 34        | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 31        | 1.48%   |
| ASPEED Technology ASPEED Graphics Family                                    | 31        | 1.48%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 30        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 28        | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 27        | 1.29%   |
| AMD Raphael                                                                 | 26        | 1.24%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 24        | 1.14%   |
| Intel HD Graphics 620                                                       | 23        | 1.1%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 23        | 1.1%    |
| Intel HD Graphics 630                                                       | 21        | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 20        | 0.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 20        | 0.95%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 20        | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 19        | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 18        | 0.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 18        | 0.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 17        | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 17        | 0.81%   |
| AMD Rembrandt [Radeon 680M]                                                 | 17        | 0.81%   |
| AMD Lucienne                                                                | 17        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16        | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16        | 0.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 16        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 15        | 0.72%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14        | 0.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.62%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 13        | 0.62%   |
| Intel HD Graphics 5500                                                      | 13        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 13        | 0.62%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x AMD                   | 484       | 28.16%  |
| 1 x Intel                 | 417       | 24.26%  |
| 1 x Nvidia                | 358       | 20.83%  |
| Intel + Nvidia            | 230       | 13.38%  |
| AMD + Nvidia              | 55        | 3.2%    |
| 2 x AMD                   | 43        | 2.5%    |
| Other                     | 29        | 1.69%   |
| Intel + AMD               | 27        | 1.57%   |
| 1 x ASPEED                | 27        | 1.57%   |
| 1 x Matrox                | 16        | 0.93%   |
| 2 x Intel                 | 13        | 0.76%   |
| 2 x Nvidia                | 8         | 0.47%   |
| Nvidia + ASPEED           | 2         | 0.12%   |
| AMD + Matrox              | 2         | 0.12%   |
| AMD + Loongson Technology | 2         | 0.12%   |
| AMD + ASPEED              | 2         | 0.12%   |
| 1 x SiS                   | 1         | 0.06%   |
| Nvidia + Matrox           | 1         | 0.06%   |
| Intel + 2 x Nvidia        | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia  | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1192      | 68.62%  |
| Proprietary | 406       | 23.37%  |
| Unknown     | 139       | 8%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 818       | 46.19%  |
| 7.01-8.0   | 201       | 11.35%  |
| 0.01-0.5   | 184       | 10.39%  |
| 1.01-2.0   | 162       | 9.15%   |
| 3.01-4.0   | 142       | 8.02%   |
| 8.01-16.0  | 88        | 4.97%   |
| 0.51-1.0   | 82        | 4.63%   |
| 5.01-6.0   | 64        | 3.61%   |
| 2.01-3.0   | 16        | 0.9%    |
| 16.01-24.0 | 12        | 0.68%   |
| 4.01-5.0   | 2         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 204       | 10.54%  |
| AU Optronics            | 177       | 9.14%   |
| Dell                    | 160       | 8.26%   |
| BOE                     | 148       | 7.64%   |
| Chimei Innolux          | 125       | 6.46%   |
| LG Display              | 123       | 6.35%   |
| Goldstar                | 104       | 5.37%   |
| BenQ                    | 63        | 3.25%   |
| AOC                     | 63        | 3.25%   |
| Sharp                   | 61        | 3.15%   |
| Ancor Communications    | 60        | 3.1%    |
| Hewlett-Packard         | 59        | 3.05%   |
| Acer                    | 57        | 2.94%   |
| ASUSTek Computer        | 46        | 2.38%   |
| Lenovo                  | 42        | 2.17%   |
| Iiyama                  | 41        | 2.12%   |
| Philips                 | 39        | 2.01%   |
| ViewSonic               | 36        | 1.86%   |
| Apple                   | 33        | 1.7%    |
| Eizo                    | 19        | 0.98%   |
| Chi Mei Optoelectronics | 18        | 0.93%   |
| Gigabyte Technology     | 15        | 0.77%   |
| PANDA                   | 14        | 0.72%   |
| Unknown                 | 13        | 0.67%   |
| CSO                     | 13        | 0.67%   |
| LG Electronics          | 12        | 0.62%   |
| MSI                     | 10        | 0.52%   |
| Fujitsu Siemens         | 10        | 0.52%   |
| NEC Computers           | 8         | 0.41%   |
| Unknown                 | 8         | 0.41%   |
| TMX                     | 6         | 0.31%   |
| Sony                    | 6         | 0.31%   |
| Mi                      | 6         | 0.31%   |
| InfoVision              | 6         | 0.31%   |
| Idek Iiyama             | 6         | 0.31%   |
| HannStar                | 6         | 0.31%   |
| Toshiba                 | 5         | 0.26%   |
| Sceptre Tech            | 5         | 0.26%   |
| RTK                     | 4         | 0.21%   |
| Panasonic               | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 11        | 0.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 10        | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.44%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 8         | 0.39%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 8         | 0.39%   |
| Unknown                                                               | 8         | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.34%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6         | 0.29%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 6         | 0.29%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch      | 6         | 0.29%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 6         | 0.29%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 6         | 0.29%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.24%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.24%   |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                     | 5         | 0.24%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                    | 5         | 0.24%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 5         | 0.24%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.2%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 4         | 0.2%    |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch       | 4         | 0.2%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 4         | 0.2%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 4         | 0.2%    |
| MSI MAG274QRF-QD MSI3CA8 2560x1440 597x336mm 27.0-inch                | 4         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.2%    |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 4         | 0.2%    |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch            | 4         | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.2%    |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch    | 4         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.2%    |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 4         | 0.2%    |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 4         | 0.2%    |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 4         | 0.2%    |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 839       | 45.9%   |
| 3840x2160 (4K)     | 184       | 10.07%  |
| 2560x1440 (QHD)    | 170       | 9.3%    |
| 1366x768 (WXGA)    | 100       | 5.47%   |
| 1920x1200 (WUXGA)  | 67        | 3.67%   |
| 1280x1024 (SXGA)   | 49        | 2.68%   |
| 3440x1440          | 42        | 2.3%    |
| 1680x1050 (WSXGA+) | 41        | 2.24%   |
| 1600x900 (HD+)     | 35        | 1.91%   |
| Unknown            | 33        | 1.81%   |
| 2560x1600          | 29        | 1.59%   |
| 2560x1080          | 26        | 1.42%   |
| 1440x900 (WXGA+)   | 25        | 1.37%   |
| 3840x2400          | 20        | 1.09%   |
| 3840x1080          | 18        | 0.98%   |
| 1280x800 (WXGA)    | 14        | 0.77%   |
| 2256x1504          | 10        | 0.55%   |
| 2880x1800          | 9         | 0.49%   |
| 1600x1200          | 8         | 0.44%   |
| 1024x600           | 8         | 0.44%   |
| 2288x1287          | 6         | 0.33%   |
| 3840x1200          | 5         | 0.27%   |
| 3200x2000          | 5         | 0.27%   |
| 2160x1440          | 5         | 0.27%   |
| 2048x1152          | 5         | 0.27%   |
| 3200x1800 (QHD+)   | 4         | 0.22%   |
| 2160x1200          | 4         | 0.22%   |
| 1920x540           | 4         | 0.22%   |
| 1360x768           | 4         | 0.22%   |
| 1024x768 (XGA)     | 4         | 0.22%   |
| 7680x2160          | 3         | 0.16%   |
| 3456x2160          | 3         | 0.16%   |
| 1400x1050          | 3         | 0.16%   |
| 1280x960           | 3         | 0.16%   |
| 1280x854           | 3         | 0.16%   |
| 800x1280           | 2         | 0.11%   |
| 5760x2160          | 2         | 0.11%   |
| 3072x1920          | 2         | 0.11%   |
| 2880x1620          | 2         | 0.11%   |
| 2240x1400          | 2         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 346       | 18.05%  |
| 27      | 251       | 13.09%  |
| 24      | 178       | 9.29%   |
| 13      | 157       | 8.19%   |
| 23      | 153       | 7.98%   |
| 14      | 129       | 6.73%   |
| Unknown | 102       | 5.32%   |
| 21      | 100       | 5.22%   |
| 17      | 98        | 5.11%   |
| 34      | 58        | 3.03%   |
| 19      | 43        | 2.24%   |
| 31      | 39        | 2.03%   |
| 16      | 34        | 1.77%   |
| 12      | 31        | 1.62%   |
| 22      | 28        | 1.46%   |
| 25      | 17        | 0.89%   |
| 20      | 14        | 0.73%   |
| 18      | 13        | 0.68%   |
| 11      | 13        | 0.68%   |
| 84      | 12        | 0.63%   |
| 32      | 12        | 0.63%   |
| 40      | 9         | 0.47%   |
| 54      | 7         | 0.37%   |
| 48      | 7         | 0.37%   |
| 26      | 7         | 0.37%   |
| 10      | 7         | 0.37%   |
| 142     | 6         | 0.31%   |
| 72      | 6         | 0.31%   |
| 49      | 5         | 0.26%   |
| 29      | 5         | 0.26%   |
| 28      | 4         | 0.21%   |
| 42      | 3         | 0.16%   |
| 8       | 3         | 0.16%   |
| 58      | 2         | 0.1%    |
| 7       | 2         | 0.1%    |
| 75      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 60      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 581       | 31.42%  |
| 501-600        | 507       | 27.42%  |
| 401-500        | 173       | 9.36%   |
| 201-300        | 147       | 7.95%   |
| 351-400        | 110       | 5.95%   |
| Unknown        | 102       | 5.52%   |
| 601-700        | 83        | 4.49%   |
| 701-800        | 72        | 3.89%   |
| 1001-1500      | 26        | 1.41%   |
| 1501-2000      | 20        | 1.08%   |
| 801-900        | 12        | 0.65%   |
| More than 2000 | 6         | 0.32%   |
| 101-200        | 4         | 0.22%   |
| 901-1000       | 4         | 0.22%   |
| 1-100          | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1174      | 70.22%  |
| 16/10   | 231       | 13.82%  |
| Unknown | 85        | 5.08%   |
| 21/9    | 62        | 3.71%   |
| 5/4     | 46        | 2.75%   |
| 3/2     | 29        | 1.73%   |
| 4/3     | 16        | 0.96%   |
| 32/9    | 13        | 0.78%   |
| 1.00    | 7         | 0.42%   |
| 6/5     | 3         | 0.18%   |
| 3.40    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 0.89    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |
| 0.31    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 345       | 18.27%  |
| 201-250        | 339       | 17.96%  |
| 301-350        | 257       | 13.61%  |
| 81-90          | 210       | 11.12%  |
| 351-500        | 112       | 5.93%   |
| Unknown        | 102       | 5.4%    |
| 251-300        | 89        | 4.71%   |
| 151-200        | 84        | 4.45%   |
| 71-80          | 75        | 3.97%   |
| 121-130        | 66        | 3.5%    |
| More than 1000 | 41        | 2.17%   |
| 141-150        | 35        | 1.85%   |
| 111-120        | 34        | 1.8%    |
| 61-70          | 28        | 1.48%   |
| 501-1000       | 28        | 1.48%   |
| 51-60          | 15        | 0.79%   |
| 131-140        | 9         | 0.48%   |
| 41-50          | 7         | 0.37%   |
| 1-40           | 6         | 0.32%   |
| 91-100         | 6         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 558       | 30.93%  |
| 121-160       | 524       | 29.05%  |
| 101-120       | 333       | 18.46%  |
| 161-240       | 176       | 9.76%   |
| Unknown       | 102       | 5.65%   |
| More than 240 | 79        | 4.38%   |
| 1-50          | 32        | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1200      | 67.76%  |
| 2     | 327       | 18.46%  |
| 0     | 163       | 9.2%    |
| 3     | 67        | 3.78%   |
| 4     | 14        | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1043      | 42.33%  |
| Realtek Semiconductor             | 806       | 32.71%  |
| Qualcomm Atheros                  | 149       | 6.05%   |
| Broadcom                          | 98        | 3.98%   |
| MediaTek                          | 66        | 2.68%   |
| ASIX Electronics                  | 25        | 1.01%   |
| Aquantia                          | 21        | 0.85%   |
| Nvidia                            | 20        | 0.81%   |
| Marvell Technology Group          | 17        | 0.69%   |
| Lenovo                            | 15        | 0.61%   |
| Qualcomm                          | 14        | 0.57%   |
| TP-Link                           | 11        | 0.45%   |
| Broadcom Limited                  | 11        | 0.45%   |
| Apple                             | 10        | 0.41%   |
| Sierra Wireless                   | 9         | 0.37%   |
| Qualcomm Atheros Communications   | 9         | 0.37%   |
| Dell                              | 9         | 0.37%   |
| Xiaomi                            | 8         | 0.32%   |
| Ralink Technology                 | 8         | 0.32%   |
| Microsoft                         | 8         | 0.32%   |
| Samsung Electronics               | 6         | 0.24%   |
| Ralink                            | 6         | 0.24%   |
| Fibocom                           | 5         | 0.2%    |
| Ericsson Business Mobile Networks | 5         | 0.2%    |
| NetGear                           | 4         | 0.16%   |
| Huawei Technologies               | 4         | 0.16%   |
| D-Link System                     | 4         | 0.16%   |
| Standard Microsystems             | 3         | 0.12%   |
| Microchip Technology              | 3         | 0.12%   |
| ICS Advent                        | 3         | 0.12%   |
| D-Link                            | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.08%   |
| U-Blox                            | 2         | 0.08%   |
| Texas Instruments                 | 2         | 0.08%   |
| STMicroelectronics                | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Sigma Designs                     | 2         | 0.08%   |
| QLogic                            | 2         | 0.08%   |
| Prusa                             | 2         | 0.08%   |
| OpenMoko                          | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 563       | 18.96%  |
| Intel Wi-Fi 6 AX200                                                    | 170       | 5.73%   |
| Intel I211 Gigabit Network Connection                                  | 126       | 4.24%   |
| Realtek RTL8125 2.5GbE Controller                                      | 95        | 3.2%    |
| Intel Wireless 8265 / 8275                                             | 65        | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 62        | 2.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 47        | 1.58%   |
| Intel Ethernet Controller I225-V                                       | 47        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 47        | 1.58%   |
| Intel I210 Gigabit Network Connection                                  | 39        | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 38        | 1.28%   |
| Intel Wi-Fi 6 AX201                                                    | 36        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 33        | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 33        | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 30        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 30        | 1.01%   |
| Intel Wireless 8260                                                    | 29        | 0.98%   |
| Intel Wireless 7265                                                    | 29        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 28        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 27        | 0.91%   |
| Intel 82574L Gigabit Network Connection                                | 26        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 25        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 25        | 0.84%   |
| Intel Wireless 7260                                                    | 24        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 24        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 24        | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 24        | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 23        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                                  | 21        | 0.71%   |
| Intel Wireless 3165                                                    | 19        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 19        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 18        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 18        | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 17        | 0.57%   |
| Intel I350 Gigabit Network Connection                                  | 17        | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 15        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 0.44%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 743       | 60.31%  |
| Realtek Semiconductor                 | 144       | 11.69%  |
| Qualcomm Atheros                      | 114       | 9.25%   |
| Broadcom                              | 64        | 5.19%   |
| MediaTek                              | 63        | 5.11%   |
| Qualcomm                              | 14        | 1.14%   |
| TP-Link                               | 9         | 0.73%   |
| Sierra Wireless                       | 9         | 0.73%   |
| Qualcomm Atheros Communications       | 9         | 0.73%   |
| Ralink Technology                     | 8         | 0.65%   |
| Microsoft                             | 8         | 0.65%   |
| Broadcom Limited                      | 8         | 0.65%   |
| Dell                                  | 7         | 0.57%   |
| Ralink                                | 6         | 0.49%   |
| Fibocom                               | 5         | 0.41%   |
| NetGear                               | 4         | 0.32%   |
| D-Link System                         | 3         | 0.24%   |
| D-Link                                | 3         | 0.24%   |
| Ericsson Business Mobile Networks     | 2         | 0.16%   |
| Wilocity                              | 1         | 0.08%   |
| Texas Instruments                     | 1         | 0.08%   |
| Senao                                 | 1         | 0.08%   |
| Quectel Wireless Solutions            | 1         | 0.08%   |
| Edimax Technology                     | 1         | 0.08%   |
| Cisco Aironet Wireless Communications | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| AVM                                   | 1         | 0.08%   |
| ASUSTek Computer                      | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 170       | 13.74%  |
| Intel Wireless 8265 / 8275                                              | 65        | 5.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 47        | 3.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 47        | 3.8%    |
| Intel Wi-Fi 6 AX201                                                     | 36        | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 30        | 2.43%   |
| Intel Wireless 8260                                                     | 29        | 2.34%   |
| Intel Wireless 7265                                                     | 29        | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 2.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 2.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 2.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 25        | 2.02%   |
| Intel Wireless 7260                                                     | 24        | 1.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 24        | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 1.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 23        | 1.86%   |
| Intel Wireless 3165                                                     | 19        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 18        | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 18        | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 0.97%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 12        | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 11        | 0.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 11        | 0.89%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 10        | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 10        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.65%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 757       | 47.34%  |
| Intel                            | 587       | 36.71%  |
| Qualcomm Atheros                 | 48        | 3%      |
| Broadcom                         | 44        | 2.75%   |
| ASIX Electronics                 | 25        | 1.56%   |
| Aquantia                         | 21        | 1.31%   |
| Nvidia                           | 20        | 1.25%   |
| Marvell Technology Group         | 17        | 1.06%   |
| Lenovo                           | 15        | 0.94%   |
| Apple                            | 10        | 0.63%   |
| Xiaomi                           | 8         | 0.5%    |
| Samsung Electronics              | 5         | 0.31%   |
| Standard Microsystems            | 3         | 0.19%   |
| Microchip Technology             | 3         | 0.19%   |
| ICS Advent                       | 3         | 0.19%   |
| Broadcom Limited                 | 3         | 0.19%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.13%   |
| TP-Link                          | 2         | 0.13%   |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| QLogic                           | 2         | 0.13%   |
| MediaTek                         | 2         | 0.13%   |
| Loongson Technology              | 2         | 0.13%   |
| Huawei Technologies              | 2         | 0.13%   |
| Google                           | 2         | 0.13%   |
| DisplayLink                      | 2         | 0.13%   |
| 3Com                             | 2         | 0.13%   |
| NetXen Incorporated              | 1         | 0.06%   |
| Mellanox Technologies            | 1         | 0.06%   |
| JMicron Technology               | 1         | 0.06%   |
| Insyde Software                  | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Gemtek                           | 1         | 0.06%   |
| Davicom Semiconductor            | 1         | 0.06%   |
| D-Link System                    | 1         | 0.06%   |
| American Megatrends              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 563       | 33.45%  |
| Intel I211 Gigabit Network Connection                                          | 126       | 7.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 95        | 5.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 62        | 3.68%   |
| Intel Ethernet Controller I225-V                                               | 47        | 2.79%   |
| Intel I210 Gigabit Network Connection                                          | 39        | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 38        | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                           | 33        | 1.96%   |
| Intel Ethernet Connection (7) I219-V                                           | 30        | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 1.66%   |
| Intel 82574L Gigabit Network Connection                                        | 26        | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 24        | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                                          | 21        | 1.25%   |
| Intel I350 Gigabit Network Connection                                          | 17        | 1.01%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                           | 13        | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 12        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                                           | 12        | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                          | 11        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 11        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                        | 11        | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 9         | 0.53%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 9         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 7         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 7         | 0.42%   |
| Nvidia MCP77 Ethernet                                                          | 7         | 0.42%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                          | 7         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 0.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 7         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 6         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                                     | 6         | 0.36%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 0.36%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1452      | 54.5%   |
| WiFi     | 1165      | 43.73%  |
| Modem    | 45        | 1.69%   |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 949       | 53.92%  |
| WiFi     | 811       | 46.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 850       | 49.88%  |
| 1     | 675       | 39.61%  |
| 3     | 95        | 5.58%   |
| 0     | 35        | 2.05%   |
| 4     | 27        | 1.58%   |
| 5     | 9         | 0.53%   |
| 6     | 7         | 0.41%   |
| 8     | 2         | 0.12%   |
| 7     | 2         | 0.12%   |
| 12    | 1         | 0.06%   |
| 9     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1406      | 80.67%  |
| Yes  | 337       | 19.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 665       | 60.18%  |
| Realtek Semiconductor           | 91        | 8.24%   |
| Cambridge Silicon Radio         | 62        | 5.61%   |
| IMC Networks                    | 39        | 3.53%   |
| Apple                           | 37        | 3.35%   |
| Foxconn / Hon Hai               | 33        | 2.99%   |
| Broadcom                        | 30        | 2.71%   |
| Qualcomm Atheros Communications | 26        | 2.35%   |
| Lite-On Technology              | 25        | 2.26%   |
| MediaTek                        | 22        | 1.99%   |
| ASUSTek Computer                | 22        | 1.99%   |
| Dell                            | 9         | 0.81%   |
| Realtek                         | 8         | 0.72%   |
| USI                             | 7         | 0.63%   |
| Toshiba                         | 5         | 0.45%   |
| HTC (High Tech Computer)        | 4         | 0.36%   |
| Hewlett-Packard                 | 4         | 0.36%   |
| Foxconn International           | 3         | 0.27%   |
| Belkin Components               | 3         | 0.27%   |
| Edimax Technology               | 2         | 0.18%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| Dynex                           | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |
| Actiontec Electronics           | 1         | 0.09%   |
| Actions                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 169       | 15.28%  |
| Intel Bluetooth wireless interface                                   | 166       | 15.01%  |
| Intel AX201 Bluetooth                                                | 107       | 9.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 88        | 7.96%   |
| Realtek Bluetooth Radio                                              | 62        | 5.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 62        | 5.61%   |
| Intel AX210 Bluetooth                                                | 44        | 3.98%   |
| Intel Bluetooth Device                                               | 35        | 3.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 31        | 2.8%    |
| MediaTek Wireless_Device                                             | 22        | 1.99%   |
| Apple Bluetooth Host Controller                                      | 21        | 1.9%    |
| Foxconn / Hon Hai Wireless_Device                                    | 20        | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 18        | 1.63%   |
| IMC Networks Wireless_Device                                         | 17        | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 16        | 1.45%   |
| IMC Networks Bluetooth Radio                                         | 14        | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10        | 0.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 0.81%   |
| Realtek Bluetooth Radio                                              | 8         | 0.72%   |
| Lite-On Bluetooth Device                                             | 8         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.72%   |
| USI Bluetooth Device                                                 | 7         | 0.63%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 7         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 7         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 7         | 0.63%   |
| Realtek RTL8723B Bluetooth                                           | 6         | 0.54%   |
| IMC Networks Bluetooth Device                                        | 6         | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 5         | 0.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.36%   |
| Lite-On Wireless_Device                                              | 4         | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.36%   |
| Dell DW375 Bluetooth Module                                          | 4         | 0.36%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 4         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 4         | 0.36%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 0.36%   |
| Apple Bluetooth HCI                                                  | 4         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 919       | 35.04%  |
| AMD                                  | 696       | 26.53%  |
| Nvidia                               | 511       | 19.48%  |
| C-Media Electronics                  | 67        | 2.55%   |
| Logitech                             | 35        | 1.33%   |
| ASUSTek Computer                     | 25        | 0.95%   |
| Creative Labs                        | 23        | 0.88%   |
| SteelSeries ApS                      | 22        | 0.84%   |
| Lenovo                               | 17        | 0.65%   |
| Creative Technology                  | 17        | 0.65%   |
| Realtek Semiconductor                | 16        | 0.61%   |
| Texas Instruments                    | 15        | 0.57%   |
| Kingston Technology                  | 14        | 0.53%   |
| Razer USA                            | 13        | 0.5%    |
| Plantronics                          | 12        | 0.46%   |
| JMTek                                | 11        | 0.42%   |
| Focusrite-Novation                   | 10        | 0.38%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.3%    |
| Micro Star International             | 8         | 0.3%    |
| GYROCOM C&C                          | 8         | 0.3%    |
| GN Netcom                            | 8         | 0.3%    |
| Blue Microphones                     | 8         | 0.3%    |
| Generalplus Technology               | 7         | 0.27%   |
| AudioQuest                           | 7         | 0.27%   |
| Corsair                              | 6         | 0.23%   |
| BEHRINGER International              | 6         | 0.23%   |
| Samson Technologies                  | 5         | 0.19%   |
| RODE Microphones                     | 5         | 0.19%   |
| Hewlett-Packard                      | 5         | 0.19%   |
| Dell                                 | 5         | 0.19%   |
| Sony                                 | 4         | 0.15%   |
| Solid State Logic                    | 4         | 0.15%   |
| Sennheiser Communications            | 4         | 0.15%   |
| SAVITECH                             | 4         | 0.15%   |
| No brand                             | 4         | 0.15%   |
| DSEA A/S                             | 4         | 0.15%   |
| Audient                              | 4         | 0.15%   |
| Yamaha                               | 3         | 0.11%   |
| Trust                                | 3         | 0.11%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 241       | 7.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 185       | 5.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 135       | 4.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 104       | 3.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 99        | 3.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 97        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 77        | 2.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 70        | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 59        | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 54        | 1.69%   |
| AMD Navi 10 HDMI Audio                                                     | 51        | 1.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 49        | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 48        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46        | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 39        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 37        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 35        | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 35        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 35        | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 33        | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 32        | 1%      |
| Nvidia GA106 High Definition Audio Controller                              | 31        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 31        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 30        | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 30        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 28        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 27        | 0.84%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.75%   |
| Intel CM238 HD Audio Controller                                            | 24        | 0.75%   |
| Nvidia GA102 High Definition Audio Controller                              | 22        | 0.69%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 22        | 0.69%   |
| Nvidia Audio device                                                        | 21        | 0.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 21        | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                              | 20        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 359       | 20.09%  |
| Kingston                     | 243       | 13.6%   |
| SK hynix                     | 237       | 13.26%  |
| Micron Technology            | 171       | 9.57%   |
| Corsair                      | 166       | 9.29%   |
| G.Skill                      | 146       | 8.17%   |
| Crucial                      | 140       | 7.83%   |
| Unknown                      | 132       | 7.39%   |
| A-DATA Technology            | 23        | 1.29%   |
| Ramaxel Technology           | 21        | 1.18%   |
| Team                         | 18        | 1.01%   |
| Unknown                      | 16        | 0.9%    |
| Patriot                      | 15        | 0.84%   |
| Elpida                       | 15        | 0.84%   |
| Transcend                    | 11        | 0.62%   |
| Nanya Technology             | 10        | 0.56%   |
| GOODRAM                      | 8         | 0.45%   |
| Unknown (ABCD)               | 5         | 0.28%   |
| AMD                          | 4         | 0.22%   |
| Timetec                      | 3         | 0.17%   |
| Apacer                       | 3         | 0.17%   |
| Toshiba                      | 2         | 0.11%   |
| Patriot Memory (PDP Systems) | 2         | 0.11%   |
| KLEVV                        | 2         | 0.11%   |
| Kimtigo                      | 2         | 0.11%   |
| Chun Well                    | 2         | 0.11%   |
| Avant                        | 2         | 0.11%   |
| Unknown (0x5D00000000000000) | 1         | 0.06%   |
| Unknown (0x0B92)             | 1         | 0.06%   |
| Thermaltake                  | 1         | 0.06%   |
| Teikon                       | 1         | 0.06%   |
| T-FORCE                      | 1         | 0.06%   |
| SGS/Thomson                  | 1         | 0.06%   |
| Saikano                      | 1         | 0.06%   |
| Qumo                         | 1         | 0.06%   |
| Qimonda                      | 1         | 0.06%   |
| PUSKILL                      | 1         | 0.06%   |
| PNY                          | 1         | 0.06%   |
| Patriot Memory               | 1         | 0.06%   |
| Mushkin                      | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 16        | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 14        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 14        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 14        | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 14        | 0.73%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s      | 13        | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 12        | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 12        | 0.63%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 12        | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 11        | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 11        | 0.58%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 10        | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 9         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 9         | 0.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 9         | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 9         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.42%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.42%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.42%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.42%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 8         | 0.42%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 8         | 0.42%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 8         | 0.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 8         | 0.42%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 7         | 0.37%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.37%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 7         | 0.37%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 7         | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 6         | 0.31%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.31%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.31%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s        | 6         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 975       | 61.48%  |
| DDR3    | 326       | 20.55%  |
| DDR5    | 64        | 4.04%   |
| DDR2    | 51        | 3.22%   |
| LPDDR4  | 47        | 2.96%   |
| Unknown | 33        | 2.08%   |
| LPDDR3  | 28        | 1.77%   |
| LPDDR5  | 24        | 1.51%   |
| SDRAM   | 19        | 1.2%    |
| DDR     | 16        | 1.01%   |
| DRAM    | 3         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 741       | 46.69%  |
| DIMM         | 739       | 46.57%  |
| Row Of Chips | 98        | 6.18%   |
| Chip         | 6         | 0.38%   |
| Unknown      | 2         | 0.13%   |
| RIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 690       | 40.3%   |
| 16384 | 449       | 26.23%  |
| 4096  | 270       | 15.77%  |
| 32768 | 147       | 8.59%   |
| 2048  | 103       | 6.02%   |
| 1024  | 39        | 2.28%   |
| 512   | 8         | 0.47%   |
| 256   | 5         | 0.29%   |
| 49152 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 340       | 19.76%  |
| 2667    | 240       | 13.95%  |
| 1600    | 201       | 11.68%  |
| 2400    | 108       | 6.28%   |
| 3600    | 96        | 5.58%   |
| 2133    | 86        | 5%      |
| 1333    | 74        | 4.3%    |
| 3733    | 34        | 1.98%   |
| 667     | 34        | 1.98%   |
| 4800    | 33        | 1.92%   |
| 6400    | 31        | 1.8%    |
| 800     | 31        | 1.8%    |
| 3800    | 29        | 1.69%   |
| 3000    | 28        | 1.63%   |
| Unknown | 28        | 1.63%   |
| 4267    | 27        | 1.57%   |
| 2933    | 23        | 1.34%   |
| 1867    | 22        | 1.28%   |
| 2666    | 18        | 1.05%   |
| 1334    | 18        | 1.05%   |
| 1866    | 15        | 0.87%   |
| 5600    | 14        | 0.81%   |
| 3400    | 14        | 0.81%   |
| 3266    | 14        | 0.81%   |
| 3466    | 12        | 0.7%    |
| 3866    | 11        | 0.64%   |
| 8400    | 10        | 0.58%   |
| 1067    | 9         | 0.52%   |
| 1066    | 9         | 0.52%   |
| 4000    | 8         | 0.46%   |
| 3533    | 8         | 0.46%   |
| 6000    | 7         | 0.41%   |
| 3666    | 7         | 0.41%   |
| 3534    | 7         | 0.41%   |
| 2800    | 6         | 0.35%   |
| 400     | 6         | 0.35%   |
| 4266    | 5         | 0.29%   |
| 3333    | 5         | 0.29%   |
| 3066    | 5         | 0.29%   |
| 2048    | 5         | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 40.63%  |
| Seiko Epson           | 4         | 12.5%   |
| Samsung Electronics   | 4         | 12.5%   |
| Canon                 | 4         | 12.5%   |
| Brother Industries    | 4         | 12.5%   |
| Xiaomi                | 1         | 3.13%   |
| Lexmark International | 1         | 3.13%   |
| Konica Minolta        | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP HP LaserJet M14-M17                | 2         | 6.25%   |
| Canon LiDE 400                        | 2         | 6.25%   |
| Xiaomi MiMouse 2                      | 1         | 3.13%   |
| Seiko Epson XP-4200 Series            | 1         | 3.13%   |
| Seiko Epson WF-3520 Series            | 1         | 3.13%   |
| Seiko Epson WF-2510 Series            | 1         | 3.13%   |
| Seiko Epson AL-M310DN                 | 1         | 3.13%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 3.13%   |
| Samsung ML-1630 Series                | 1         | 3.13%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 3.13%   |
| Samsung C460 Series                   | 1         | 3.13%   |
| Lexmark International Lexmark E352dn  | 1         | 3.13%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 3.13%   |
| HP PhotoSmart 130                     | 1         | 3.13%   |
| HP LaserJet P2055 series              | 1         | 3.13%   |
| HP LaserJet 3200                      | 1         | 3.13%   |
| HP LaserJet 1020                      | 1         | 3.13%   |
| HP LaserJet 1018                      | 1         | 3.13%   |
| HP LaserJet 1010                      | 1         | 3.13%   |
| HP Deskjet D1500 series               | 1         | 3.13%   |
| HP Deskjet 9800                       | 1         | 3.13%   |
| HP DeskJet 5440                       | 1         | 3.13%   |
| HP DeskJet 3630 series                | 1         | 3.13%   |
| HP Deskjet 2050 J510                  | 1         | 3.13%   |
| Canon PIXMA MG2900 Series             | 1         | 3.13%   |
| Canon CanoScan LiDE 300               | 1         | 3.13%   |
| Brother QL-500 label printer          | 1         | 3.13%   |
| Brother MFC-L2700DW                   | 1         | 3.13%   |
| Brother MFC-9340CDW                   | 1         | 3.13%   |
| Brother MFC-9130CW                    | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Mustek Systems  | 1         | 14.29%  |
| AGFA-Gevaert NV | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30      | 2         | 28.57%  |
| Mustek Systems BearPaw 2448 TA Pro | 1         | 14.29%  |
| Canon CanoScan LiDE 600F           | 1         | 14.29%  |
| Canon CanoScan LiDE 220            | 1         | 14.29%  |
| Canon CanoScan LiDE 110            | 1         | 14.29%  |
| AGFA-Gevaert NV SnapScan e20       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 186       | 19.96%  |
| Logitech                               | 119       | 12.77%  |
| IMC Networks                           | 103       | 11.05%  |
| Microdia                               | 80        | 8.58%   |
| Realtek Semiconductor                  | 61        | 6.55%   |
| Bison Electronics                      | 47        | 5.04%   |
| Sunplus Innovation Technology          | 46        | 4.94%   |
| Quanta                                 | 42        | 4.51%   |
| Lite-On Technology                     | 26        | 2.79%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 2.79%   |
| Luxvisions Innotech Limited            | 21        | 2.25%   |
| Apple                                  | 20        | 2.15%   |
| Syntek                                 | 19        | 2.04%   |
| Acer                                   | 16        | 1.72%   |
| Samsung Electronics                    | 15        | 1.61%   |
| Z-Star Microelectronics                | 8         | 0.86%   |
| Sonix Technology                       | 7         | 0.75%   |
| Microsoft                              | 7         | 0.75%   |
| Suyin                                  | 4         | 0.43%   |
| MacroSilicon                           | 4         | 0.43%   |
| Generalplus Technology                 | 4         | 0.43%   |
| DigiTech                               | 4         | 0.43%   |
| Creative Technology                    | 4         | 0.43%   |
| ARC International                      | 4         | 0.43%   |
| Silicon Motion                         | 3         | 0.32%   |
| Elgato Systems                         | 3         | 0.32%   |
| AVerMedia Technologies                 | 3         | 0.32%   |
| SunplusIT                              | 2         | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.21%   |
| Ricoh                                  | 2         | 0.21%   |
| Razer USA                              | 2         | 0.21%   |
| LG Electronics                         | 2         | 0.21%   |
| Lenovo                                 | 2         | 0.21%   |
| KYE Systems (Mouse Systems)            | 2         | 0.21%   |
| kingcome                               | 2         | 0.21%   |
| Hy-UXGA(B5M2)-Camera                   | 2         | 0.21%   |
| Genesys Logic                          | 2         | 0.21%   |
| Cubeternet                             | 2         | 0.21%   |
| Alcor Micro                            | 2         | 0.21%   |
| A4Tech                                 | 2         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 65        | 6.89%   |
| IMC Networks Integrated Camera                       | 41        | 4.34%   |
| Microdia Integrated_Webcam_HD                        | 40        | 4.24%   |
| Logitech HD Pro Webcam C920                          | 29        | 3.07%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 28        | 2.97%   |
| Realtek Integrated_Webcam_HD                         | 26        | 2.75%   |
| Logitech Webcam C270                                 | 24        | 2.54%   |
| Bison Integrated Camera                              | 23        | 2.44%   |
| Chicony HD Webcam                                    | 18        | 1.91%   |
| Samsung Galaxy series, misc. (MTP mode)              | 15        | 1.59%   |
| Syntek Integrated Camera                             | 14        | 1.48%   |
| Sunplus Integrated_Webcam_HD                         | 12        | 1.27%   |
| Chicony HP HD Camera                                 | 12        | 1.27%   |
| Microdia USB 2.0 Camera                              | 11        | 1.17%   |
| Logitech C922 Pro Stream Webcam                      | 11        | 1.17%   |
| Lite-On Integrated Camera                            | 10        | 1.06%   |
| Quanta HD User Facing                                | 9         | 0.95%   |
| Logitech Webcam C310                                 | 8         | 0.85%   |
| Logitech BRIO Ultra HD Webcam                        | 8         | 0.85%   |
| Chicony USB2.0 Camera                                | 8         | 0.85%   |
| Quanta HP Wide Vision HD Camera                      | 7         | 0.74%   |
| Chicony HD User Facing                               | 7         | 0.74%   |
| Sunplus HD WebCam                                    | 6         | 0.64%   |
| Realtek Laptop Camera                                | 6         | 0.64%   |
| Lite-On HP HD Camera                                 | 6         | 0.64%   |
| Chicony Lenovo EasyCamera                            | 6         | 0.64%   |
| Apple FaceTime HD Camera                             | 6         | 0.64%   |
| Acer SunplusIT Integrated Camera                     | 6         | 0.64%   |
| Quanta HP TrueVision HD Camera                       | 5         | 0.53%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 5         | 0.53%   |
| Luxvisions Innotech Limited Integrated Camera        | 5         | 0.53%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 0.53%   |
| Luxvisions Innotech Limited HP HD Camera             | 5         | 0.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 0.53%   |
| IMC Networks ov9734_azurewave_camera                 | 5         | 0.53%   |
| Chicony ThinkPad T490 Webcam                         | 5         | 0.53%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 0.53%   |
| Bison HD Webcam                                      | 5         | 0.53%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 5         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 78        | 44.83%  |
| Validity Sensors                   | 40        | 22.99%  |
| Shenzhen Goodix Technology         | 29        | 16.67%  |
| Elan Microelectronics              | 9         | 5.17%   |
| STMicroelectronics                 | 4         | 2.3%    |
| LighTuning Technology              | 4         | 2.3%    |
| AuthenTec                          | 4         | 2.3%    |
| DigitalPersona                     | 3         | 1.72%   |
| Upek                               | 1         | 0.57%   |
| Samsung Electronics                | 1         | 0.57%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 17.82%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 8.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 6.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 6.32%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 5.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 5.17%   |
| Synaptics WBDI                                                             | 8         | 4.6%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 4.02%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.02%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.45%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.87%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.3%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.3%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.3%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.72%   |
| DigitalPersona Fingerprint Reader                                          | 3         | 1.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.15%   |
| Validity Sensors VFS491                                                    | 2         | 1.15%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.15%   |
| Unknown                                                                    | 2         | 1.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.57%   |
| Synaptics WBDI Device                                                      | 1         | 0.57%   |
| Synaptics TouchPad                                                         | 1         | 0.57%   |
| Synaptics  WBDI                                                            | 1         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.57%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.57%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 44        | 35.2%   |
| Broadcom                          | 42        | 33.6%   |
| Upek                              | 5         | 4%      |
| O2 Micro                          | 5         | 4%      |
| Clay Logic                        | 5         | 4%      |
| Yubico.com                        | 4         | 3.2%    |
| SCM Microsystems                  | 4         | 3.2%    |
| Hewlett-Packard                   | 2         | 1.6%    |
| Gemalto (was Gemplus)             | 2         | 1.6%    |
| Advanced Card Systems             | 2         | 1.6%    |
| VASCO Data Security International | 1         | 0.8%    |
| Purism, SPC                       | 1         | 0.8%    |
| OmniKey                           | 1         | 0.8%    |
| Microchip Technology              | 1         | 0.8%    |
| Lenovo                            | 1         | 0.8%    |
| Free Software Initiative of Japan | 1         | 0.8%    |
| Feitian Technologies              | 1         | 0.8%    |
| Bit4id                            | 1         | 0.8%    |
| Aladdin Knowledge Systems         | 1         | 0.8%    |
| Aktiv                             | 1         | 0.8%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 35.2%   |
| Broadcom 58200                                                               | 16        | 12.8%   |
| Broadcom 5880                                                                | 12        | 9.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 5.6%    |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 4.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4%      |
| Clay Logic Nitrokey Pro                                                      | 5         | 4%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 3.2%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 3.2%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.6%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 1.6%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.6%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.6%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.8%    |
| Purism, SPC Librem Key                                                       | 1         | 0.8%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.8%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.8%    |
| Lenovo Integrated Smart Card Reader                                          | 1         | 0.8%    |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 0.8%    |
| Feitian Technologies FIDO CCID KB                                            | 1         | 0.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.8%    |
| Bit4id miniLector-s                                                          | 1         | 0.8%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.8%    |
| Aktiv Rutoken lite                                                           | 1         | 0.8%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.8%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.8%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 820       | 43.46%  |
| 1     | 518       | 27.45%  |
| 2     | 260       | 13.78%  |
| 3     | 140       | 7.42%   |
| 4     | 80        | 4.24%   |
| 5     | 42        | 2.23%   |
| 6     | 21        | 1.11%   |
| 7     | 5         | 0.26%   |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 335       | 17.5%   |
| Graphics card            | 266       | 13.9%   |
| Bluetooth                | 237       | 12.38%  |
| Camera                   | 194       | 10.14%  |
| Fingerprint reader       | 172       | 8.99%   |
| Net/wireless             | 144       | 7.52%   |
| Chipcard                 | 98        | 5.12%   |
| Multimedia controller    | 90        | 4.7%    |
| Sound                    | 85        | 4.44%   |
| Card reader              | 77        | 4.02%   |
| Network                  | 36        | 1.88%   |
| Net/ethernet             | 31        | 1.62%   |
| Firewire controller      | 31        | 1.62%   |
| Unassigned class         | 25        | 1.31%   |
| Storage/ide              | 22        | 1.15%   |
| Modem                    | 21        | 1.1%    |
| Storage/ata              | 17        | 0.89%   |
| Storage/raid             | 9         | 0.47%   |
| Tv card                  | 7         | 0.37%   |
| Storage                  | 6         | 0.31%   |
| Storage/nvme             | 5         | 0.26%   |
| Dvb card                 | 4         | 0.21%   |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |

