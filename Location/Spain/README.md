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

Total: 8378

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| Dell          | 0Y56T3 A01                  | Desktop     | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4d2f60a496](https://linux-hardware.org/?probe=4d2f60a496) | Sep 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0a548c4390](https://linux-hardware.org/?probe=0a548c4390) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b6316ea4df](https://linux-hardware.org/?probe=b6316ea4df) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f75ab187aa](https://linux-hardware.org/?probe=f75ab187aa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [426e8bd9c0](https://linux-hardware.org/?probe=426e8bd9c0) | Sep 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3c4c65947a](https://linux-hardware.org/?probe=3c4c65947a) | Sep 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2bdd48e441](https://linux-hardware.org/?probe=2bdd48e441) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [14cbad7097](https://linux-hardware.org/?probe=14cbad7097) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1e61c0fb6b](https://linux-hardware.org/?probe=1e61c0fb6b) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | Notebook    | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [21c3145a6a](https://linux-hardware.org/?probe=21c3145a6a) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [786338b217](https://linux-hardware.org/?probe=786338b217) | Sep 26, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [9395b9347e](https://linux-hardware.org/?probe=9395b9347e) | Sep 26, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [19afe08920](https://linux-hardware.org/?probe=19afe08920) | Sep 25, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | Desktop     | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| Dell          | 0441XG A04                  | Server      | [60298ae886](https://linux-hardware.org/?probe=60298ae886) | Sep 25, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6dca52cc54](https://linux-hardware.org/?probe=6dca52cc54) | Sep 25, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c50564e3bb](https://linux-hardware.org/?probe=c50564e3bb) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4b78e93dff](https://linux-hardware.org/?probe=4b78e93dff) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [e05aa71be7](https://linux-hardware.org/?probe=e05aa71be7) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [38a92e23c8](https://linux-hardware.org/?probe=38a92e23c8) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [1c09a9f9c9](https://linux-hardware.org/?probe=1c09a9f9c9) | Sep 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [54ed40361d](https://linux-hardware.org/?probe=54ed40361d) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [7ddc30adc9](https://linux-hardware.org/?probe=7ddc30adc9) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [fe1c9060da](https://linux-hardware.org/?probe=fe1c9060da) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [30a324bad7](https://linux-hardware.org/?probe=30a324bad7) | Sep 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [226a590989](https://linux-hardware.org/?probe=226a590989) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [aee02d5429](https://linux-hardware.org/?probe=aee02d5429) | Sep 22, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1fe2e34799](https://linux-hardware.org/?probe=1fe2e34799) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [146d33a16d](https://linux-hardware.org/?probe=146d33a16d) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| HP            | 1495                        | Desktop     | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | Notebook    | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f87766b547](https://linux-hardware.org/?probe=f87766b547) | Sep 21, 2023 |
| ASUSTek       | B150M-A                     | Desktop     | [d2e741051e](https://linux-hardware.org/?probe=d2e741051e) | Sep 21, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [03c9da6c46](https://linux-hardware.org/?probe=03c9da6c46) | Sep 20, 2023 |
| MSI           | Indio                       | Desktop     | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [a25329cfdb](https://linux-hardware.org/?probe=a25329cfdb) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [2225b3687d](https://linux-hardware.org/?probe=2225b3687d) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b6f78da91](https://linux-hardware.org/?probe=8b6f78da91) | Sep 20, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [a2f44141ba](https://linux-hardware.org/?probe=a2f44141ba) | Sep 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [911f7b8df2](https://linux-hardware.org/?probe=911f7b8df2) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [233a59e640](https://linux-hardware.org/?probe=233a59e640) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| HP            | ProBook 4530s               | Notebook    | [251e7cc45b](https://linux-hardware.org/?probe=251e7cc45b) | Sep 18, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [56340d8ed4](https://linux-hardware.org/?probe=56340d8ed4) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [0866503148](https://linux-hardware.org/?probe=0866503148) | Sep 17, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Google        | Droid                       | Notebook    | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [3bd1c975cc](https://linux-hardware.org/?probe=3bd1c975cc) | Sep 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [cfa86cec4f](https://linux-hardware.org/?probe=cfa86cec4f) | Sep 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c8ac03221f](https://linux-hardware.org/?probe=c8ac03221f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f48f6375b2](https://linux-hardware.org/?probe=f48f6375b2) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9390e3d243](https://linux-hardware.org/?probe=9390e3d243) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9fc334d8b3](https://linux-hardware.org/?probe=9fc334d8b3) | Sep 15, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b0702745f5](https://linux-hardware.org/?probe=b0702745f5) | Sep 14, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [e2454dd5b9](https://linux-hardware.org/?probe=e2454dd5b9) | Sep 14, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [21e27c3e56](https://linux-hardware.org/?probe=21e27c3e56) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c0bcb5b2c6](https://linux-hardware.org/?probe=c0bcb5b2c6) | Sep 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [262209b6a0](https://linux-hardware.org/?probe=262209b6a0) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b57846d1cb](https://linux-hardware.org/?probe=b57846d1cb) | Sep 12, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [c687b18168](https://linux-hardware.org/?probe=c687b18168) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| Lenovo        | ThinkPad E490 20N8000YUK    | Notebook    | [df9271331c](https://linux-hardware.org/?probe=df9271331c) | Sep 12, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [0191ff7bb8](https://linux-hardware.org/?probe=0191ff7bb8) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [486d89ed3a](https://linux-hardware.org/?probe=486d89ed3a) | Sep 11, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [335798b8c9](https://linux-hardware.org/?probe=335798b8c9) | Sep 11, 2023 |
| MSI           | GE62 7RD                    | Notebook    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [366932ee55](https://linux-hardware.org/?probe=366932ee55) | Sep 11, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [2e9fbd4683](https://linux-hardware.org/?probe=2e9fbd4683) | Sep 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [dbd0ea122b](https://linux-hardware.org/?probe=dbd0ea122b) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [34601ced54](https://linux-hardware.org/?probe=34601ced54) | Sep 08, 2023 |
| HP            | 630                         | Notebook    | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | Notebook    | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| SLIMBOOK      | ONE-AM5                     | Desktop     | [0c8c554ff5](https://linux-hardware.org/?probe=0c8c554ff5) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Notebook    | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9ffcb827b4](https://linux-hardware.org/?probe=9ffcb827b4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [0ca7d43ae9](https://linux-hardware.org/?probe=0ca7d43ae9) | Sep 07, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [1a2a0eef04](https://linux-hardware.org/?probe=1a2a0eef04) | Sep 06, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e6c990ad64](https://linux-hardware.org/?probe=e6c990ad64) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Sony          | VGN-AW41MF_H                | Notebook    | [d3a3262a6e](https://linux-hardware.org/?probe=d3a3262a6e) | Sep 06, 2023 |
| MSI           | Boston                      | Desktop     | [f4749c6ef7](https://linux-hardware.org/?probe=f4749c6ef7) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | Notebook    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [8209a15afb](https://linux-hardware.org/?probe=8209a15afb) | Sep 06, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [ee70bf217a](https://linux-hardware.org/?probe=ee70bf217a) | Sep 06, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [cac93ead6f](https://linux-hardware.org/?probe=cac93ead6f) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [9d86c0f6e5](https://linux-hardware.org/?probe=9d86c0f6e5) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| Dell          | Precision 7670              | Notebook    | [42788bf2c7](https://linux-hardware.org/?probe=42788bf2c7) | Sep 05, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [75d602c66f](https://linux-hardware.org/?probe=75d602c66f) | Sep 05, 2023 |
| Dell          | Precision 7670              | Notebook    | [41bb07b203](https://linux-hardware.org/?probe=41bb07b203) | Sep 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [8ae585f958](https://linux-hardware.org/?probe=8ae585f958) | Sep 05, 2023 |
| Acer          | Aspire C24-865              | All in one  | [62ba0d2a97](https://linux-hardware.org/?probe=62ba0d2a97) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| Acer          | Aspire C24-865              | All in one  | [66f268deab](https://linux-hardware.org/?probe=66f268deab) | Sep 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [db9fa6ee49](https://linux-hardware.org/?probe=db9fa6ee49) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [5a9932b3b8](https://linux-hardware.org/?probe=5a9932b3b8) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [def3f0d266](https://linux-hardware.org/?probe=def3f0d266) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| Samsung       | 950QED                      | Convertible | [3d5bc9f8ca](https://linux-hardware.org/?probe=3d5bc9f8ca) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| IP3 Techno... | ARN59P                      | Notebook    | [493a986305](https://linux-hardware.org/?probe=493a986305) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [1e52631ae6](https://linux-hardware.org/?probe=1e52631ae6) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [c4acf7ebb9](https://linux-hardware.org/?probe=c4acf7ebb9) | Sep 02, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [1ae5cc8cf9](https://linux-hardware.org/?probe=1ae5cc8cf9) | Sep 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9190ad12c2](https://linux-hardware.org/?probe=9190ad12c2) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0a715ba5aa](https://linux-hardware.org/?probe=0a715ba5aa) | Sep 01, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| Lenovo        | NOK                         | Desktop     | [3b2d750004](https://linux-hardware.org/?probe=3b2d750004) | Aug 31, 2023 |
| Lenovo        | NOK                         | Desktop     | [0e10fff36a](https://linux-hardware.org/?probe=0e10fff36a) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| Medion        | E15301                      | Notebook    | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Intel         | HM570                       | Desktop     | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Gigabyte      | MTGU5AB-00                  | Desktop     | [2501ea0755](https://linux-hardware.org/?probe=2501ea0755) | Aug 31, 2023 |
| Acer          | Extensa 5230                | Notebook    | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| MSI           | MS-B1421                    | Desktop     | [65d24e365e](https://linux-hardware.org/?probe=65d24e365e) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| HP            | 8768 A                      | Desktop     | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| Alurin        | Go Notebook                 | Notebook    | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| HP            | 876C SMVB                   | Desktop     | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| Dell          | Precision 7680              | Notebook    | [90240d0ffd](https://linux-hardware.org/?probe=90240d0ffd) | Aug 30, 2023 |
| Dell          | Precision 7680              | Notebook    | [065ed91451](https://linux-hardware.org/?probe=065ed91451) | Aug 30, 2023 |
| Dell          | Latitude 5330               | Notebook    | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0817c6178e](https://linux-hardware.org/?probe=0817c6178e) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0a2adee694](https://linux-hardware.org/?probe=0a2adee694) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Huanan        | H97-ZD3 V2.1                | Desktop     | [0587a85214](https://linux-hardware.org/?probe=0587a85214) | Aug 28, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [151de667a5](https://linux-hardware.org/?probe=151de667a5) | Aug 28, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8c1bc17ecf](https://linux-hardware.org/?probe=8c1bc17ecf) | Aug 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| MSI           | Katana GF66 12UGS           | Notebook    | [ca352a81f4](https://linux-hardware.org/?probe=ca352a81f4) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [9abe07288a](https://linux-hardware.org/?probe=9abe07288a) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| HP            | ProBook 4540s               | Notebook    | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| Chuwi         | UBook X                     | Tablet      | [e2281326e3](https://linux-hardware.org/?probe=e2281326e3) | Aug 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [582c495a92](https://linux-hardware.org/?probe=582c495a92) | Aug 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [63816a7b5f](https://linux-hardware.org/?probe=63816a7b5f) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [01a0f80107](https://linux-hardware.org/?probe=01a0f80107) | Aug 27, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [d03d50ea3c](https://linux-hardware.org/?probe=d03d50ea3c) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [01062889f6](https://linux-hardware.org/?probe=01062889f6) | Aug 26, 2023 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [22c5b125e0](https://linux-hardware.org/?probe=22c5b125e0) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | Laptop                      | Notebook    | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e2c530b9fd](https://linux-hardware.org/?probe=e2c530b9fd) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| HP            | 18E4                        | Desktop     | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Packard Be... | GA-T671MG                   | Desktop     | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | Desktop     | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [5f108773ec](https://linux-hardware.org/?probe=5f108773ec) | Aug 24, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [03cff37b1a](https://linux-hardware.org/?probe=03cff37b1a) | Aug 24, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| HP            | 8835                        | Desktop     | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | Desktop     | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| GEEKOM        | GM08i3T                     | Desktop     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [06b5fb7c7f](https://linux-hardware.org/?probe=06b5fb7c7f) | Aug 22, 2023 |
| Dynabook      | Satellite Pro C50-E-11F     | Notebook    | [b8955c7cf1](https://linux-hardware.org/?probe=b8955c7cf1) | Aug 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e9c7a12d52](https://linux-hardware.org/?probe=e9c7a12d52) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| Medion        | MS-7728                     | Desktop     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d93165e8a9](https://linux-hardware.org/?probe=d93165e8a9) | Aug 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [62ecbe2f01](https://linux-hardware.org/?probe=62ecbe2f01) | Aug 18, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [809590bdb0](https://linux-hardware.org/?probe=809590bdb0) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [2981eb04ba](https://linux-hardware.org/?probe=2981eb04ba) | Aug 16, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d2b1d6e9ad](https://linux-hardware.org/?probe=d2b1d6e9ad) | Aug 16, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [97ced089bf](https://linux-hardware.org/?probe=97ced089bf) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e2a4a35103](https://linux-hardware.org/?probe=e2a4a35103) | Aug 15, 2023 |
| System76      | Galago Pro                  | Notebook    | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Medion        | E15301                      | Notebook    | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [589af795e9](https://linux-hardware.org/?probe=589af795e9) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [e1a35ce655](https://linux-hardware.org/?probe=e1a35ce655) | Aug 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| MSI           | Summit E16Flip A13VET       | Notebook    | [c8d4dbcf88](https://linux-hardware.org/?probe=c8d4dbcf88) | Aug 13, 2023 |
| MSI           | A78M-E45                    | Desktop     | [2affb76a98](https://linux-hardware.org/?probe=2affb76a98) | Aug 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [441be5ab4d](https://linux-hardware.org/?probe=441be5ab4d) | Aug 13, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [9e0052d329](https://linux-hardware.org/?probe=9e0052d329) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | Notebook    | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| MSI           | 2AE0                        | Desktop     | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| Dell          | G7 7588                     | Notebook    | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [504746e40c](https://linux-hardware.org/?probe=504746e40c) | Aug 12, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [9651bc99b0](https://linux-hardware.org/?probe=9651bc99b0) | Aug 12, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [ccf80c6f9a](https://linux-hardware.org/?probe=ccf80c6f9a) | Aug 12, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [b5604d9633](https://linux-hardware.org/?probe=b5604d9633) | Aug 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3181a592ac](https://linux-hardware.org/?probe=3181a592ac) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [1c2e98b598](https://linux-hardware.org/?probe=1c2e98b598) | Aug 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b50bdc5845](https://linux-hardware.org/?probe=b50bdc5845) | Aug 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8a3df803a6](https://linux-hardware.org/?probe=8a3df803a6) | Aug 11, 2023 |
| Intel Clie... | LAPQC71A                    | Notebook    | [c87bff1d43](https://linux-hardware.org/?probe=c87bff1d43) | Aug 11, 2023 |
| MSI           | Creator Z16 A11UET          | Notebook    | [7883e9a69d](https://linux-hardware.org/?probe=7883e9a69d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | Notebook    | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [9ce8c0dd74](https://linux-hardware.org/?probe=9ce8c0dd74) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | Notebook    | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8b57037d50](https://linux-hardware.org/?probe=8b57037d50) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Unknown       | AB07H                       | Desktop     | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [939205ed85](https://linux-hardware.org/?probe=939205ed85) | Aug 09, 2023 |
| MSI           | A78M-E45                    | Desktop     | [d39f224497](https://linux-hardware.org/?probe=d39f224497) | Aug 09, 2023 |
| Dell          | Latitude 5520               | Notebook    | [478f0a6a07](https://linux-hardware.org/?probe=478f0a6a07) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | Notebook    | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| MSI           | Creator Z16 A11UET          | Notebook    | [ea05388cf5](https://linux-hardware.org/?probe=ea05388cf5) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e703e9ae63](https://linux-hardware.org/?probe=e703e9ae63) | Aug 07, 2023 |
| SGIN          | laptop                      | Notebook    | [d80389ea87](https://linux-hardware.org/?probe=d80389ea87) | Aug 07, 2023 |
| HP            | 255 G3                      | Notebook    | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | Notebook    | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [77840c201a](https://linux-hardware.org/?probe=77840c201a) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [e6955ee04c](https://linux-hardware.org/?probe=e6955ee04c) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [804851c490](https://linux-hardware.org/?probe=804851c490) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | Notebook    | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [d71ac9524e](https://linux-hardware.org/?probe=d71ac9524e) | Aug 06, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [37bf6e8191](https://linux-hardware.org/?probe=37bf6e8191) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [151339db32](https://linux-hardware.org/?probe=151339db32) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| ASUSTek       | R2H                         | Notebook    | [a2972dc454](https://linux-hardware.org/?probe=a2972dc454) | Aug 06, 2023 |
| ASUSTek       | R2H                         | Notebook    | [c32b5889aa](https://linux-hardware.org/?probe=c32b5889aa) | Aug 06, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| MSI           | A78M-E45                    | Desktop     | [988c1f5878](https://linux-hardware.org/?probe=988c1f5878) | Aug 05, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | Notebook    | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [0b6f7a1d70](https://linux-hardware.org/?probe=0b6f7a1d70) | Aug 05, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [4fe47419ee](https://linux-hardware.org/?probe=4fe47419ee) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [eabd86788e](https://linux-hardware.org/?probe=eabd86788e) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| HP            | 83E8                        | Desktop     | [0d285189b9](https://linux-hardware.org/?probe=0d285189b9) | Aug 04, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [71e97069b6](https://linux-hardware.org/?probe=71e97069b6) | Aug 04, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [42ac042892](https://linux-hardware.org/?probe=42ac042892) | Aug 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [0e3cacbea1](https://linux-hardware.org/?probe=0e3cacbea1) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [582f50ea25](https://linux-hardware.org/?probe=582f50ea25) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8e7e80c44e](https://linux-hardware.org/?probe=8e7e80c44e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [648421ac0a](https://linux-hardware.org/?probe=648421ac0a) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [2dcefa3349](https://linux-hardware.org/?probe=2dcefa3349) | Aug 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [6ea9f908cb](https://linux-hardware.org/?probe=6ea9f908cb) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [2ca9767252](https://linux-hardware.org/?probe=2ca9767252) | Jul 31, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [63b8471789](https://linux-hardware.org/?probe=63b8471789) | Jul 30, 2023 |
| VANT          | MOOVE15_2023                | Notebook    | [6943d341c4](https://linux-hardware.org/?probe=6943d341c4) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | Notebook    | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| HP            | g14                         | Notebook    | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| Qualcomm T... | SM8150 V2 PM8150 VAYU       | Soc         | [42cf42a0d2](https://linux-hardware.org/?probe=42cf42a0d2) | Jul 28, 2023 |
| Unknown       | Unknown                     | Soc         | [dbb70e9c8b](https://linux-hardware.org/?probe=dbb70e9c8b) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [61321e569d](https://linux-hardware.org/?probe=61321e569d) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [2af263d1b7](https://linux-hardware.org/?probe=2af263d1b7) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Samsung       | 700T                        | Notebook    | [a6c83540ad](https://linux-hardware.org/?probe=a6c83540ad) | Jul 27, 2023 |
| Acer          | Extensa 2510                | Notebook    | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| Samsung       | 700T                        | Notebook    | [881cb15d92](https://linux-hardware.org/?probe=881cb15d92) | Jul 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [865eacc7bb](https://linux-hardware.org/?probe=865eacc7bb) | Jul 25, 2023 |
| Acer          | Extensa 2530                | Notebook    | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [33c7ff96a8](https://linux-hardware.org/?probe=33c7ff96a8) | Jul 25, 2023 |
| HP            | 1495                        | Desktop     | [99072e94e8](https://linux-hardware.org/?probe=99072e94e8) | Jul 25, 2023 |
| HP            | 8719                        | Desktop     | [68870aa596](https://linux-hardware.org/?probe=68870aa596) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| Unknown       | Huawei Y635                 | Soc         | [399a63d7fe](https://linux-hardware.org/?probe=399a63d7fe) | Jul 23, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [4c5a8d18b9](https://linux-hardware.org/?probe=4c5a8d18b9) | Jul 22, 2023 |
| Medion        | E15301                      | Notebook    | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [e222d263f6](https://linux-hardware.org/?probe=e222d263f6) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | Notebook    | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| Chuwi         | M01ALWR310-ADA90A           | Mini pc     | [0274c94523](https://linux-hardware.org/?probe=0274c94523) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [fbd6b6197b](https://linux-hardware.org/?probe=fbd6b6197b) | Jul 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [06099a3fdd](https://linux-hardware.org/?probe=06099a3fdd) | Jul 21, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [0c95406e21](https://linux-hardware.org/?probe=0c95406e21) | Jul 21, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [b3f1259905](https://linux-hardware.org/?probe=b3f1259905) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [714d6a38d3](https://linux-hardware.org/?probe=714d6a38d3) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f7edcc8364](https://linux-hardware.org/?probe=f7edcc8364) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ec673415b4](https://linux-hardware.org/?probe=ec673415b4) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [3ed4a6a897](https://linux-hardware.org/?probe=3ed4a6a897) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [3428acceaf](https://linux-hardware.org/?probe=3428acceaf) | Jul 19, 2023 |
| MSI           | H81M-E33                    | Desktop     | [dc821e7080](https://linux-hardware.org/?probe=dc821e7080) | Jul 19, 2023 |
| Intel         | Skylake U DDR3L RVP7 1      | All in one  | [d1342e70a2](https://linux-hardware.org/?probe=d1342e70a2) | Jul 19, 2023 |
| Gigabyte      | B75-D3V                     | Desktop     | [ad01a23df5](https://linux-hardware.org/?probe=ad01a23df5) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| HP            | 889C                        | Desktop     | [3124074b5a](https://linux-hardware.org/?probe=3124074b5a) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [fdbbd2b641](https://linux-hardware.org/?probe=fdbbd2b641) | Jul 18, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [e5d8647d32](https://linux-hardware.org/?probe=e5d8647d32) | Jul 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [10e24627b0](https://linux-hardware.org/?probe=10e24627b0) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| Unknown       | Unknown                     | Soc         | [d69b7167f2](https://linux-hardware.org/?probe=d69b7167f2) | Jul 15, 2023 |
| Unknown       | Unknown                     | Soc         | [96ae9a1ca6](https://linux-hardware.org/?probe=96ae9a1ca6) | Jul 15, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [649fb482b4](https://linux-hardware.org/?probe=649fb482b4) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [b84898fc8a](https://linux-hardware.org/?probe=b84898fc8a) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [bcf8e9f2c3](https://linux-hardware.org/?probe=bcf8e9f2c3) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [fc6d20a364](https://linux-hardware.org/?probe=fc6d20a364) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2bdf7534ad](https://linux-hardware.org/?probe=2bdf7534ad) | Jul 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e3ad1f49b1](https://linux-hardware.org/?probe=e3ad1f49b1) | Jul 13, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [59a6da64a7](https://linux-hardware.org/?probe=59a6da64a7) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [d7c5b64bcb](https://linux-hardware.org/?probe=d7c5b64bcb) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Dell          | Latitude 7275               | Notebook    | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [500fee1ce5](https://linux-hardware.org/?probe=500fee1ce5) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [0095feba57](https://linux-hardware.org/?probe=0095feba57) | Jul 10, 2023 |
| Clevo         | M550SE/M660SE               | Notebook    | [65697a4412](https://linux-hardware.org/?probe=65697a4412) | Jul 10, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [6b4434fd14](https://linux-hardware.org/?probe=6b4434fd14) | Jul 10, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [ca812ae8ad](https://linux-hardware.org/?probe=ca812ae8ad) | Jul 10, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [4967fbddb9](https://linux-hardware.org/?probe=4967fbddb9) | Jul 10, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [4ee2490bde](https://linux-hardware.org/?probe=4ee2490bde) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| Notebook      | V1x0PNPx                    | Notebook    | [5a37402681](https://linux-hardware.org/?probe=5a37402681) | Jul 09, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [7fc70add85](https://linux-hardware.org/?probe=7fc70add85) | Jul 08, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [352e4ef5e5](https://linux-hardware.org/?probe=352e4ef5e5) | Jul 08, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [fd3d1bc540](https://linux-hardware.org/?probe=fd3d1bc540) | Jul 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [a0359f0f09](https://linux-hardware.org/?probe=a0359f0f09) | Jul 07, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [83bbe4315f](https://linux-hardware.org/?probe=83bbe4315f) | Jul 07, 2023 |
| AZW           | SER                         | Mini pc     | [1a93a70c6b](https://linux-hardware.org/?probe=1a93a70c6b) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [c4421f6f50](https://linux-hardware.org/?probe=c4421f6f50) | Jul 06, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [a783ca495d](https://linux-hardware.org/?probe=a783ca495d) | Jul 06, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [c4bea06a7d](https://linux-hardware.org/?probe=c4bea06a7d) | Jul 06, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [f603fed65f](https://linux-hardware.org/?probe=f603fed65f) | Jul 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [a2728115f2](https://linux-hardware.org/?probe=a2728115f2) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8121ccc8a9](https://linux-hardware.org/?probe=8121ccc8a9) | Jul 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [656b411052](https://linux-hardware.org/?probe=656b411052) | Jul 05, 2023 |
| Dell          | 0WK833                      | Desktop     | [bf1756a33c](https://linux-hardware.org/?probe=bf1756a33c) | Jul 05, 2023 |
| Medion        | X782X                       | Notebook    | [7369e18cc2](https://linux-hardware.org/?probe=7369e18cc2) | Jul 05, 2023 |
| Teclast       | X4                          | Tablet      | [6aab5b6610](https://linux-hardware.org/?probe=6aab5b6610) | Jul 05, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [7acafd9528](https://linux-hardware.org/?probe=7acafd9528) | Jul 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [4c68104591](https://linux-hardware.org/?probe=4c68104591) | Jul 03, 2023 |
| Dell          | Latitude 5520               | Notebook    | [acb3fdea1b](https://linux-hardware.org/?probe=acb3fdea1b) | Jul 03, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4bbef448c9](https://linux-hardware.org/?probe=4bbef448c9) | Jul 03, 2023 |
| Unknown       | AB07H                       | Desktop     | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| HP            | ENVY m6                     | Notebook    | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5daabbcd55](https://linux-hardware.org/?probe=5daabbcd55) | Jul 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [7863106765](https://linux-hardware.org/?probe=7863106765) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1eb1ecf3a9](https://linux-hardware.org/?probe=1eb1ecf3a9) | Jul 02, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
| Teclast       | X4                          | Tablet      | [a7149387c0](https://linux-hardware.org/?probe=a7149387c0) | Jul 02, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [a53eeb72a6](https://linux-hardware.org/?probe=a53eeb72a6) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [d5e55f9e7d](https://linux-hardware.org/?probe=d5e55f9e7d) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [546fe2b3ab](https://linux-hardware.org/?probe=546fe2b3ab) | Jul 01, 2023 |
| HP            | 8054                        | Desktop     | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | Desktop     | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b57a18d9b](https://linux-hardware.org/?probe=4b57a18d9b) | Jun 30, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [1abd7f9f95](https://linux-hardware.org/?probe=1abd7f9f95) | Jun 30, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9f8e4c6a70](https://linux-hardware.org/?probe=9f8e4c6a70) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [5b7bc3205d](https://linux-hardware.org/?probe=5b7bc3205d) | Jun 29, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Dell          | 0WK833                      | Desktop     | [fd4a07e088](https://linux-hardware.org/?probe=fd4a07e088) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [d73388baab](https://linux-hardware.org/?probe=d73388baab) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| Dell          | 0WK833                      | Desktop     | [39a5ca93a7](https://linux-hardware.org/?probe=39a5ca93a7) | Jun 27, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [09f4e0e86a](https://linux-hardware.org/?probe=09f4e0e86a) | Jun 27, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [8aaaef4a62](https://linux-hardware.org/?probe=8aaaef4a62) | Jun 27, 2023 |
| MW            | NVR-N5105                   | Desktop     | [36ee490ef2](https://linux-hardware.org/?probe=36ee490ef2) | Jun 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | Notebook    | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [f58c462a34](https://linux-hardware.org/?probe=f58c462a34) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8c0f33ffe](https://linux-hardware.org/?probe=a8c0f33ffe) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9a30b63c87](https://linux-hardware.org/?probe=9a30b63c87) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [785d3130e7](https://linux-hardware.org/?probe=785d3130e7) | Jun 24, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [68b591e6d8](https://linux-hardware.org/?probe=68b591e6d8) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | Notebook    | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [39d5409264](https://linux-hardware.org/?probe=39d5409264) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [3708ae400f](https://linux-hardware.org/?probe=3708ae400f) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [d447bb1029](https://linux-hardware.org/?probe=d447bb1029) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Foxconn       | ETON                        | Desktop     | [ae0d87abfb](https://linux-hardware.org/?probe=ae0d87abfb) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5fbfa89321](https://linux-hardware.org/?probe=5fbfa89321) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2bd22135e0](https://linux-hardware.org/?probe=2bd22135e0) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5cbbd51d7f](https://linux-hardware.org/?probe=5cbbd51d7f) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [39ed83a165](https://linux-hardware.org/?probe=39ed83a165) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | Notebook    | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e33558044f](https://linux-hardware.org/?probe=e33558044f) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [eebb6ba229](https://linux-hardware.org/?probe=eebb6ba229) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Notebook    | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Beelink       | Gemini X                    | Notebook    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | Notebook    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [851020a59f](https://linux-hardware.org/?probe=851020a59f) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [7ee7ee0f67](https://linux-hardware.org/?probe=7ee7ee0f67) | Jun 14, 2023 |
| HP            | 3397                        | Desktop     | [e67824996f](https://linux-hardware.org/?probe=e67824996f) | Jun 14, 2023 |
| AMI           | Intel                       | Desktop     | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| MW            | NVR-N5105                   | Desktop     | [7481711a2f](https://linux-hardware.org/?probe=7481711a2f) | Jun 13, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [1364983b69](https://linux-hardware.org/?probe=1364983b69) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | Notebook    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [c8e822d0d7](https://linux-hardware.org/?probe=c8e822d0d7) | Jun 10, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 742       | 12.21%  |
| Ubuntu 18.04                 | 512       | 8.43%   |
| Ubuntu 22.04                 | 319       | 5.25%   |
| Debian 11                    | 251       | 4.13%   |
| OpenMandriva 4.2             | 184       | 3.03%   |
| OpenMandriva 4.3             | 124       | 2.04%   |
| Zorin 16                     | 118       | 1.94%   |
| KDE neon 20.04               | 112       | 1.84%   |
| Arch Rolling                 | 90        | 1.48%   |
| Manjaro                      | 88        | 1.45%   |
| OpenMandriva 23.01           | 86        | 1.42%   |
| Linux Mint 20.3              | 83        | 1.37%   |
| Debian 10                    | 83        | 1.37%   |
| Linux Mint 21.1              | 76        | 1.25%   |
| Ubuntu 20.10                 | 72        | 1.18%   |
| Linux Mint 19.3              | 71        | 1.17%   |
| Arch                         | 65        | 1.07%   |
| Xubuntu 20.04                | 62        | 1.02%   |
| Ubuntu 19.04                 | 61        | 1%      |
| Ubuntu 19.10                 | 58        | 0.95%   |
| Linux Mint 20.1              | 58        | 0.95%   |
| Fedora 36                    | 57        | 0.94%   |
| Fedora 38                    | 55        | 0.91%   |
| OpenMandriva 23.03           | 54        | 0.89%   |
| Ubuntu 21.04                 | 53        | 0.87%   |
| Pop!_OS 22.04                | 53        | 0.87%   |
| Linux Mint 20                | 53        | 0.87%   |
| Fedora 37                    | 52        | 0.86%   |
| Ubuntu 21.10                 | 50        | 0.82%   |
| Linux Mint 20.2              | 48        | 0.79%   |
| Xubuntu 18.04                | 47        | 0.77%   |
| Fedora 35                    | 47        | 0.77%   |
| Kubuntu 20.04                | 46        | 0.76%   |
| ArcoLinux Rolling            | 44        | 0.72%   |
| Ubuntu 22.10                 | 43        | 0.71%   |
| ROSA R10                     | 43        | 0.71%   |
| Linux Mint 21                | 43        | 0.71%   |
| Debian 12                    | 42        | 0.69%   |
| Zorin 15                     | 41        | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 40        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1912      | 33.44%  |
| Linux Mint    | 482       | 8.43%   |
| OpenMandriva  | 481       | 8.41%   |
| Debian        | 426       | 7.45%   |
| Fedora        | 308       | 5.39%   |
| Manjaro       | 202       | 3.53%   |
| Zorin         | 164       | 2.87%   |
| KDE neon      | 153       | 2.68%   |
| Arch          | 153       | 2.68%   |
| Pop!_OS       | 137       | 2.4%    |
| Xubuntu       | 132       | 2.31%   |
| Endless       | 123       | 2.15%   |
| Kubuntu       | 122       | 2.13%   |
| ROSA          | 112       | 1.96%   |
| openSUSE      | 63        | 1.1%    |
| Ubuntu MATE   | 61        | 1.07%   |
| Elementary    | 58        | 1.01%   |
| ArcoLinux     | 55        | 0.96%   |
| Gentoo        | 52        | 0.91%   |
| Kali          | 48        | 0.84%   |
| Ubuntu Unity  | 40        | 0.7%    |
| SteamOS       | 37        | 0.65%   |
| Lubuntu       | 33        | 0.58%   |
| BlackPanther  | 30        | 0.52%   |
| EndeavourOS   | 26        | 0.45%   |
| LMDE          | 24        | 0.42%   |
| Nobara        | 23        | 0.4%    |
| MX            | 23        | 0.4%    |
| Parrot        | 21        | 0.37%   |
| Clear Linux   | 18        | 0.31%   |
| Ubuntu Budgie | 13        | 0.23%   |
| Garuda Linux  | 12        | 0.21%   |
| CentOS        | 10        | 0.17%   |
| Reborn OS     | 8         | 0.14%   |
| Deepin        | 7         | 0.12%   |
| Ubuntu Studio | 6         | 0.1%    |
| RHEL          | 6         | 0.1%    |
| Xero          | 5         | 0.09%   |
| Sparky        | 5         | 0.09%   |
| Solus         | 5         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 180       | 2.71%   |
| 5.16.7-desktop-1omv4003         | 121       | 1.82%   |
| 5.4.0-42-generic                | 96        | 1.45%   |
| 6.1.1-desktop-1omv2290          | 81        | 1.22%   |
| 5.15.0-56-generic               | 66        | 1%      |
| 5.4.0-58-generic                | 60        | 0.9%    |
| 5.10.0-8-amd64                  | 56        | 0.84%   |
| 6.2.6-desktop-1omv2390          | 52        | 0.78%   |
| 5.4.0-52-generic                | 49        | 0.74%   |
| 5.4.0-54-generic                | 48        | 0.72%   |
| 5.4.0-26-generic                | 47        | 0.71%   |
| 5.15.0-52-generic               | 44        | 0.66%   |
| 5.15.0-58-generic               | 43        | 0.65%   |
| 5.3.0-28-generic                | 42        | 0.63%   |
| 5.4.0-48-generic                | 39        | 0.59%   |
| 5.11.0-27-generic               | 38        | 0.57%   |
| 5.3.0-40-generic                | 37        | 0.56%   |
| 5.0.0-37-generic                | 36        | 0.54%   |
| 5.4.0-29-generic                | 34        | 0.51%   |
| 5.4.0-65-generic                | 32        | 0.48%   |
| 5.3.0-46-generic                | 32        | 0.48%   |
| 5.19.0-35-generic               | 32        | 0.48%   |
| 5.13.0-30-generic               | 32        | 0.48%   |
| 5.11.0-43-generic               | 32        | 0.48%   |
| 5.15.0-60-generic               | 31        | 0.47%   |
| 5.10.0-21-amd64                 | 31        | 0.47%   |
| 5.10.0-18-amd64                 | 31        | 0.47%   |
| 5.0.0-32-generic                | 30        | 0.45%   |
| 5.4.0-72-generic                | 29        | 0.44%   |
| 5.4.0-40-generic                | 29        | 0.44%   |
| 5.15.0-48-generic               | 29        | 0.44%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.44%   |
| 5.4.0-47-generic                | 27        | 0.41%   |
| 5.4.0-37-generic                | 27        | 0.41%   |
| 5.3.0-51-generic                | 27        | 0.41%   |
| 5.19.0-38-generic               | 26        | 0.39%   |
| 5.15.0-53-generic               | 26        | 0.39%   |
| 5.13.0-39-generic               | 26        | 0.39%   |
| 5.13.0-28-generic               | 26        | 0.39%   |
| 5.11.0-41-generic               | 26        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 964       | 15.44%  |
| 5.15.0  | 539       | 8.63%   |
| 4.15.0  | 419       | 6.71%   |
| 5.10.0  | 291       | 4.66%   |
| 5.11.0  | 277       | 4.44%   |
| 5.8.0   | 266       | 4.26%   |
| 5.3.0   | 254       | 4.07%   |
| 5.13.0  | 253       | 4.05%   |
| 5.19.0  | 204       | 3.27%   |
| 5.0.0   | 198       | 3.17%   |
| 5.10.14 | 182       | 2.91%   |
| 5.16.7  | 125       | 2%      |
| 4.18.0  | 114       | 1.83%   |
| 6.1.1   | 91        | 1.46%   |
| 4.19.0  | 86        | 1.38%   |
| 6.2.0   | 75        | 1.2%    |
| 6.2.6   | 71        | 1.14%   |
| 6.1.0   | 70        | 1.12%   |
| 4.9.60  | 33        | 0.53%   |
| 6.4.11  | 27        | 0.43%   |
| 6.0.0   | 27        | 0.43%   |
| 4.18.16 | 24        | 0.38%   |
| 5.14.0  | 23        | 0.37%   |
| 4.4.0   | 22        | 0.35%   |
| 5.18.0  | 21        | 0.34%   |
| 6.4.8   | 19        | 0.3%    |
| 5.17.5  | 18        | 0.29%   |
| 6.3.5   | 15        | 0.24%   |
| 6.0.12  | 15        | 0.24%   |
| 5.9.16  | 15        | 0.24%   |
| 5.16.0  | 14        | 0.22%   |
| 6.1.11  | 13        | 0.21%   |
| 5.9.0   | 13        | 0.21%   |
| 6.4.6   | 12        | 0.19%   |
| 6.1.12  | 12        | 0.19%   |
| 5.7.0   | 12        | 0.19%   |
| 5.3.18  | 12        | 0.19%   |
| 5.16.11 | 12        | 0.19%   |
| 5.12.4  | 12        | 0.19%   |
| 4.9.20  | 12        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1028      | 16.68%  |
| 5.15    | 663       | 10.76%  |
| 5.10    | 555       | 9%      |
| 4.15    | 419       | 6.8%    |
| 5.11    | 334       | 5.42%   |
| 5.8     | 326       | 5.29%   |
| 5.13    | 291       | 4.72%   |
| 5.3     | 282       | 4.57%   |
| 5.19    | 266       | 4.32%   |
| 6.1     | 255       | 4.14%   |
| 6.2     | 208       | 3.37%   |
| 5.0     | 202       | 3.28%   |
| 5.16    | 191       | 3.1%    |
| 4.18    | 139       | 2.26%   |
| 6.4     | 111       | 1.8%    |
| 6.0     | 108       | 1.75%   |
| 4.19    | 102       | 1.65%   |
| 5.14    | 81        | 1.31%   |
| 4.9     | 80        | 1.3%    |
| 6.3     | 74        | 1.2%    |
| 5.18    | 67        | 1.09%   |
| 5.9     | 52        | 0.84%   |
| 5.17    | 52        | 0.84%   |
| 5.6     | 51        | 0.83%   |
| 5.7     | 45        | 0.73%   |
| 5.12    | 44        | 0.71%   |
| 5.5     | 26        | 0.42%   |
| 4.4     | 26        | 0.42%   |
| 6.5     | 21        | 0.34%   |
| 4.1     | 9         | 0.15%   |
| 5.2     | 8         | 0.13%   |
| 3.10    | 8         | 0.13%   |
| 5.1     | 7         | 0.11%   |
| 4.16    | 6         | 0.1%    |
| 4.14    | 5         | 0.08%   |
| 4.20    | 4         | 0.06%   |
| 4.17    | 4         | 0.06%   |
| 4.13    | 4         | 0.06%   |
| 4.8     | 3         | 0.05%   |
| 3.16    | 3         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5280      | 95.95%  |
| i686    | 184       | 3.34%   |
| aarch64 | 30        | 0.55%   |
| armv7l  | 8         | 0.15%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2454      | 42.41%  |
| KDE5             | 1063      | 18.37%  |
| Unknown          | 670       | 11.58%  |
| XFCE             | 441       | 7.62%   |
| X-Cinnamon       | 380       | 6.57%   |
| MATE             | 168       | 2.9%    |
| KDE              | 158       | 2.73%   |
| LXQt             | 66        | 1.14%   |
| Pantheon         | 54        | 0.93%   |
| Cinnamon         | 53        | 0.92%   |
| KDE4             | 48        | 0.83%   |
| Unity            | 39        | 0.67%   |
| i3               | 38        | 0.66%   |
| Budgie           | 27        | 0.47%   |
| LXDE             | 23        | 0.4%    |
| Deepin           | 20        | 0.35%   |
| GNOME Flashback  | 16        | 0.28%   |
| openbox          | 10        | 0.17%   |
| bspwm            | 8         | 0.14%   |
| GNOME Classic    | 7         | 0.12%   |
| Dwm              | 5         | 0.09%   |
| qtile            | 4         | 0.07%   |
| lightdm-xsession | 4         | 0.07%   |
| ICEWM            | 4         | 0.07%   |
| Hyprland         | 4         | 0.07%   |
| xmonad           | 3         | 0.05%   |
| LeftWM           | 3         | 0.05%   |
| enlightenment    | 3         | 0.05%   |
| Trinity          | 2         | 0.03%   |
| sway             | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| awesome          | 2         | 0.03%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| chadwm           | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4375      | 76.82%  |
| Wayland | 876       | 15.38%  |
| Unknown | 357       | 6.27%   |
| Tty     | 87        | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2880      | 50.34%  |
| SDDM    | 919       | 16.06%  |
| GDM     | 618       | 10.8%   |
| GDM3    | 584       | 10.21%  |
| LightDM | 488       | 8.53%   |
| TDM     | 150       | 2.62%   |
| KDM     | 48        | 0.84%   |
| XDM     | 13        | 0.23%   |
| LXDM    | 8         | 0.14%   |
| SLiM    | 5         | 0.09%   |
| Ly      | 5         | 0.09%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 3332      | 58.7%   |
| en_US          | 1012      | 17.83%  |
| Unknown        | 658       | 11.59%  |
| ca_ES          | 203       | 3.58%   |
| en_GB          | 119       | 2.1%    |
| C              | 58        | 1.02%   |
| gl_ES          | 38        | 0.67%   |
| de_DE          | 35        | 0.62%   |
| eu_ES          | 27        | 0.48%   |
| ru_RU          | 20        | 0.35%   |
| fr_FR          | 20        | 0.35%   |
| it_IT          | 17        | 0.3%    |
| an_ES          | 13        | 0.23%   |
| es_MX          | 10        | 0.18%   |
| es_AR          | 10        | 0.18%   |
| pt_BR          | 9         | 0.16%   |
| en_IE          | 7         | 0.12%   |
| ca_AD          | 7         | 0.12%   |
| ro_RO          | 5         | 0.09%   |
| POSIX          | 5         | 0.09%   |
| pl_PL          | 5         | 0.09%   |
| en_AG          | 5         | 0.09%   |
| ca_ES@valencia | 5         | 0.09%   |
| C.UTF8         | 5         | 0.09%   |
| es_ES.UTF8     | 4         | 0.07%   |
| pt_PT          | 3         | 0.05%   |
| nl_NL          | 3         | 0.05%   |
| fr_BE          | 3         | 0.05%   |
| de_AT          | 3         | 0.05%   |
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

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2836      | 50.35%  |
| EFI  | 2797      | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4248      | 74.88%  |
| Overlay  | 488       | 8.6%    |
| Btrfs    | 452       | 7.97%   |
| Unknown  | 212       | 3.74%   |
| Tmpfs    | 101       | 1.78%   |
| Xfs      | 81        | 1.43%   |
| Ext3     | 34        | 0.6%    |
| Zfs      | 27        | 0.48%   |
| Ext2     | 16        | 0.28%   |
| Reiserfs | 4         | 0.07%   |
| F2fs     | 4         | 0.07%   |
| Jfs      | 3         | 0.05%   |
| Aufs     | 3         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3035      | 53.73%  |
| GPT     | 2010      | 35.58%  |
| MBR     | 604       | 10.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4695      | 83.32%  |
| Yes       | 940       | 16.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3753      | 66.9%   |
| Yes       | 1857      | 33.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1038      | 18.87%  |
| Hewlett-Packard         | 775       | 14.09%  |
| Lenovo                  | 655       | 11.91%  |
| MSI                     | 488       | 8.87%   |
| Gigabyte Technology     | 450       | 8.18%   |
| Acer                    | 360       | 6.54%   |
| Dell                    | 344       | 6.25%   |
| Apple                   | 143       | 2.6%    |
| ASRock                  | 131       | 2.38%   |
| Toshiba                 | 118       | 2.15%   |
| Intel                   | 87        | 1.58%   |
| Unknown                 | 73        | 1.33%   |
| HUAWEI                  | 53        | 0.96%   |
| Packard Bell            | 49        | 0.89%   |
| Sony                    | 46        | 0.84%   |
| Chuwi                   | 46        | 0.84%   |
| Medion                  | 45        | 0.82%   |
| Samsung Electronics     | 36        | 0.65%   |
| Notebook                | 35        | 0.64%   |
| Valve                   | 32        | 0.58%   |
| SLIMBOOK                | 28        | 0.51%   |
| Raspberry Pi Foundation | 23        | 0.42%   |
| Fujitsu                 | 23        | 0.42%   |
| LG Electronics          | 22        | 0.4%    |
| Pegatron                | 20        | 0.36%   |
| eMachines               | 19        | 0.35%   |
| BESSTAR Tech            | 18        | 0.33%   |
| ECS                     | 17        | 0.31%   |
| AMI                     | 17        | 0.31%   |
| Teclast                 | 16        | 0.29%   |
| Fujitsu Siemens         | 13        | 0.24%   |
| Timi                    | 12        | 0.22%   |
| Foxconn                 | 12        | 0.22%   |
| AZW                     | 12        | 0.22%   |
| Supermicro              | 11        | 0.2%    |
| Huanan                  | 11        | 0.2%    |
| Microsoft               | 10        | 0.18%   |
| Dynabook                | 9         | 0.16%   |
| Clevo                   | 9         | 0.16%   |
| Shuttle                 | 7         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 100       | 1.82%   |
| ASUS All Series                            | 58        | 1.05%   |
| Valve Jupiter                              | 32        | 0.58%   |
| HP Pavilion g6                             | 24        | 0.44%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.4%    |
| HP Pavilion dv6                            | 21        | 0.38%   |
| HP Notebook                                | 20        | 0.36%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.33%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 17        | 0.31%   |
| Gigabyte B450M DS3H                        | 15        | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.27%   |
| MSI MS-7817                                | 12        | 0.22%   |
| HUAWEI BOHK-WAX9X                          | 12        | 0.22%   |
| HP G62                                     | 12        | 0.22%   |
| Gigabyte 970A-DS3P                         | 12        | 0.22%   |
| MSI MS-7C37                                | 11        | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8               | 11        | 0.2%    |
| Chuwi GemiBook Pro                         | 11        | 0.2%    |
| ASUS P5G41T-M LX                           | 11        | 0.2%    |
| RPi Raspberry Pi                           | 10        | 0.18%   |
| MSI MS-7C91                                | 10        | 0.18%   |
| HP Pavilion 15                             | 10        | 0.18%   |
| HP Laptop 15-da0xxx                        | 10        | 0.18%   |
| Dell XPS 13 7390                           | 10        | 0.18%   |
| MSI MS-7B79                                | 9         | 0.16%   |
| HP Laptop 15s-fq1xxx                       | 9         | 0.16%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.16%   |
| HP Compaq Elite 8300 SFF                   | 9         | 0.16%   |
| Gigabyte H81M-S2H                          | 9         | 0.16%   |
| Gigabyte H61M-DS2                          | 9         | 0.16%   |
| Gigabyte H110M-S2H                         | 9         | 0.16%   |
| Gigabyte B450 AORUS M                      | 9         | 0.16%   |
| ASUS PRIME A320M-K                         | 9         | 0.16%   |
| ASUS H110M-D                               | 9         | 0.16%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.15%   |
| MSI MS-7C02                                | 8         | 0.15%   |
| MSI MS-7B86                                | 8         | 0.15%   |
| MSI Modern 14 A10M                         | 8         | 0.15%   |
| HP Laptop 15-bw0xx                         | 8         | 0.15%   |
| HP EliteDesk 800 G1 SFF                    | 8         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 255       | 4.64%   |
| Lenovo ThinkPad       | 211       | 3.84%   |
| HP Pavilion           | 158       | 2.87%   |
| Lenovo IdeaPad        | 154       | 2.8%    |
| HP Compaq             | 102       | 1.85%   |
| Unknown               | 100       | 1.82%   |
| Dell Latitude         | 99        | 1.8%    |
| ASUS PRIME            | 95        | 1.73%   |
| ASUS VivoBook         | 93        | 1.69%   |
| Toshiba Satellite     | 91        | 1.65%   |
| HP Laptop             | 85        | 1.55%   |
| ASUS ROG              | 83        | 1.51%   |
| ASUS TUF              | 71        | 1.29%   |
| Dell XPS              | 69        | 1.25%   |
| HP EliteBook          | 68        | 1.24%   |
| Lenovo ThinkCentre    | 61        | 1.11%   |
| ASUS All              | 58        | 1.05%   |
| Dell OptiPlex         | 55        | 1%      |
| Dell Inspiron         | 47        | 0.85%   |
| HP ProBook            | 44        | 0.8%    |
| ASUS Zenbook          | 44        | 0.8%    |
| Packard Bell EasyNote | 35        | 0.64%   |
| MSI Prestige          | 33        | 0.6%    |
| Valve Jupiter         | 32        | 0.58%   |
| HP 250                | 32        | 0.58%   |
| Lenovo Yoga           | 30        | 0.55%   |
| Lenovo Legion         | 30        | 0.55%   |
| MSI Modern            | 29        | 0.53%   |
| Dell Precision        | 28        | 0.51%   |
| HP OMEN               | 27        | 0.49%   |
| Acer TravelMate       | 27        | 0.49%   |
| Gigabyte B450M        | 25        | 0.45%   |
| RPi Raspberry         | 23        | 0.42%   |
| Gigabyte X570         | 23        | 0.42%   |
| ASUS ASUS             | 23        | 0.42%   |
| Acer Extensa          | 23        | 0.42%   |
| HP EliteDesk          | 22        | 0.4%    |
| Lenovo ThinkBook      | 20        | 0.36%   |
| HP Notebook           | 20        | 0.36%   |
| HP ENVY               | 20        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 547       | 9.94%   |
| 2019    | 508       | 9.23%   |
| 2020    | 467       | 8.49%   |
| 2021    | 401       | 7.29%   |
| 2014    | 385       | 7%      |
| 2013    | 337       | 6.13%   |
| 2012    | 334       | 6.07%   |
| 2017    | 321       | 5.84%   |
| 2015    | 312       | 5.67%   |
| 2011    | 311       | 5.65%   |
| 2010    | 271       | 4.93%   |
| 2009    | 254       | 4.62%   |
| 2016    | 246       | 4.47%   |
| 2008    | 242       | 4.4%    |
| 2022    | 205       | 3.73%   |
| 2007    | 175       | 3.18%   |
| 2006    | 87        | 1.58%   |
| Unknown | 37        | 0.67%   |
| 2023    | 25        | 0.45%   |
| 2005    | 22        | 0.4%    |
| 2004    | 7         | 0.13%   |
| 2003    | 3         | 0.05%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3068      | 55.77%  |
| Desktop        | 2044      | 37.16%  |
| All in one     | 104       | 1.89%   |
| Convertible    | 84        | 1.53%   |
| Mini pc        | 84        | 1.53%   |
| Tablet         | 49        | 0.89%   |
| System on chip | 35        | 0.64%   |
| Server         | 29        | 0.53%   |
| Phone          | 3         | 0.05%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5162      | 93.29%  |
| Enabled  | 371       | 6.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5493      | 99.85%  |
| Yes  | 8         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1245      | 22.21%  |
| 16.01-24.0      | 1145      | 20.42%  |
| 3.01-4.0        | 1113      | 19.85%  |
| 8.01-16.0       | 1049      | 18.71%  |
| 32.01-64.0      | 500       | 8.92%   |
| 1.01-2.0        | 236       | 4.21%   |
| 64.01-256.0     | 91        | 1.62%   |
| 2.01-3.0        | 88        | 1.57%   |
| 24.01-32.0      | 66        | 1.18%   |
| 0.51-1.0        | 64        | 1.14%   |
| More than 256.0 | 6         | 0.11%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2275      | 37.13%  |
| 2.01-3.0   | 1557      | 25.41%  |
| 4.01-8.0   | 803       | 13.11%  |
| 3.01-4.0   | 728       | 11.88%  |
| 0.51-1.0   | 457       | 7.46%   |
| 8.01-16.0  | 207       | 3.38%   |
| 0.01-0.5   | 69        | 1.13%   |
| 16.01-24.0 | 15        | 0.24%   |
| 24.01-32.0 | 11        | 0.18%   |
| 32.01-64.0 | 4         | 0.07%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3400      | 59.63%  |
| 2       | 1432      | 25.11%  |
| 3       | 453       | 7.94%   |
| 4       | 201       | 3.53%   |
| 5       | 84        | 1.47%   |
| 0       | 47        | 0.82%   |
| 6       | 41        | 0.72%   |
| 7       | 16        | 0.28%   |
| 9       | 8         | 0.14%   |
| 8       | 8         | 0.14%   |
| 10      | 4         | 0.07%   |
| 12      | 2         | 0.04%   |
| 11      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 13      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3405      | 61.27%  |
| Yes       | 2152      | 38.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4727      | 85.57%  |
| No        | 797       | 14.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4178      | 75.37%  |
| No        | 1365      | 24.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3230      | 58.04%  |
| No        | 2335      | 41.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 5501      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 921       | 15.3%   |
| Barcelona                  | 613       | 10.18%  |
| Valencia                   | 215       | 3.57%   |
| Seville                    | 201       | 3.34%   |
| Zaragoza                   | 98        | 1.63%   |
| Málaga                    | 88        | 1.46%   |
| Granada                    | 80        | 1.33%   |
| Valladolid                 | 62        | 1.03%   |
| Bilbao                     | 59        | 0.98%   |
| Alcobendas                 | 59        | 0.98%   |
| Vigo                       | 58        | 0.96%   |
| Palma                      | 58        | 0.96%   |
| Sabadell                   | 55        | 0.91%   |
| Córdoba                   | 52        | 0.86%   |
| Las Palmas de Gran Canaria | 51        | 0.85%   |
| Pamplona                   | 41        | 0.68%   |
| Murcia                     | 41        | 0.68%   |
| Donostia / San Sebastian   | 41        | 0.68%   |
| Alicante                   | 41        | 0.68%   |
| Oviedo                     | 40        | 0.66%   |
| Ourense                    | 40        | 0.66%   |
| A Coruña                  | 37        | 0.61%   |
| Santiago de Compostela     | 35        | 0.58%   |
| Alcalá de Henares         | 35        | 0.58%   |
| Santa Cruz de Tenerife     | 34        | 0.56%   |
| Gijón                     | 31        | 0.52%   |
| Burgos                     | 31        | 0.52%   |
| Almería                   | 31        | 0.52%   |
| León                      | 27        | 0.45%   |
| Salamanca                  | 26        | 0.43%   |
| Mostoles                   | 26        | 0.43%   |
| Vitoria-Gasteiz            | 25        | 0.42%   |
| Barakaldo                  | 25        | 0.42%   |
| Badalona                   | 24        | 0.4%    |
| Terrassa                   | 22        | 0.37%   |
| Santander                  | 22        | 0.37%   |
| Girona                     | 22        | 0.37%   |
| Getxo                      | 22        | 0.37%   |
| Albacete                   | 22        | 0.37%   |
| Reus                       | 20        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1331      | 2059   | 16.49%  |
| WDC                         | 1086      | 1615   | 13.45%  |
| Samsung Electronics         | 1063      | 1549   | 13.17%  |
| Kingston                    | 893       | 1238   | 11.06%  |
| Toshiba                     | 568       | 878    | 7.03%   |
| SanDisk                     | 458       | 625    | 5.67%   |
| Crucial                     | 313       | 445    | 3.88%   |
| Unknown                     | 312       | 410    | 3.86%   |
| Hitachi                     | 245       | 294    | 3.03%   |
| SK hynix                    | 198       | 251    | 2.45%   |
| Intel                       | 176       | 235    | 2.18%   |
| Micron Technology           | 145       | 185    | 1.8%    |
| HGST                        | 132       | 164    | 1.63%   |
| China                       | 82        | 111    | 1.02%   |
| Phison                      | 57        | 64     | 0.71%   |
| Apple                       | 54        | 72     | 0.67%   |
| Micron/Crucial Technology   | 50        | 66     | 0.62%   |
| KIOXIA                      | 50        | 65     | 0.62%   |
| Fujitsu                     | 45        | 51     | 0.56%   |
| Phison Electronics          | 43        | 53     | 0.53%   |
| Maxtor                      | 40        | 57     | 0.5%    |
| Kingston Technology Company | 36        | 48     | 0.45%   |
| OCZ                         | 35        | 49     | 0.43%   |
| Silicon Motion              | 34        | 41     | 0.42%   |
| JMicron Technology          | 28        | 30     | 0.35%   |
| Netac                       | 26        | 39     | 0.32%   |
| KIOXIA-EXCERIA              | 26        | 35     | 0.32%   |
| Transcend                   | 24        | 49     | 0.3%    |
| A-DATA Technology           | 24        | 35     | 0.3%    |
| Unknown                     | 24        | 27     | 0.3%    |
| KingSpec                    | 22        | 29     | 0.27%   |
| LITEON                      | 20        | 22     | 0.25%   |
| Emtec                       | 20        | 25     | 0.25%   |
| Corsair                     | 20        | 25     | 0.25%   |
| PNY                         | 19        | 29     | 0.24%   |
| KingDian                    | 18        | 23     | 0.22%   |
| USB30                       | 16        | 34     | 0.2%    |
| Intenso                     | 16        | 26     | 0.2%    |
| Patriot                     | 14        | 23     | 0.17%   |
| Teclast                     | 12        | 14     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 291       | 3.28%   |
| Kingston SA400S37480G 480GB SSD                     | 138       | 1.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 103       | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                     | 89        | 1%      |
| Kingston SA400S37120G 120GB SSD                     | 89        | 1%      |
| Kingston SV300S37A120G 120GB SSD                    | 78        | 0.88%   |
| Seagate ST3500418AS 500GB                           | 68        | 0.77%   |
| Samsung SSD 860 EVO 500GB                           | 66        | 0.74%   |
| Unknown MMC Card  64GB                              | 61        | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB                      | 58        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 55        | 0.62%   |
| Unknown MMC Card  32GB                              | 53        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB                      | 53        | 0.6%    |
| Samsung SSD 850 EVO 250GB                           | 52        | 0.59%   |
| Seagate ST500LT012-1DG142 500GB                     | 48        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                      | 48        | 0.54%   |
| Samsung SSD 850 EVO 500GB                           | 48        | 0.54%   |
| Toshiba DT01ACA100 1TB                              | 46        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 45        | 0.51%   |
| SanDisk SSD PLUS 480GB                              | 45        | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 45        | 0.51%   |
| Kingston SUV400S37240G 240GB SSD                    | 45        | 0.51%   |
| Seagate ST9500325AS 500GB                           | 44        | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 42        | 0.47%   |
| HGST HTS721010A9E630 1TB                            | 40        | 0.45%   |
| Toshiba MQ01ABF050 500GB                            | 37        | 0.42%   |
| Unknown MMC Card  128GB                             | 36        | 0.41%   |
| Samsung NVMe SSD Drive 512GB                        | 36        | 0.41%   |
| Samsung NVMe SSD Drive 500GB                        | 36        | 0.41%   |
| Seagate ST31000528AS 1TB                            | 35        | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB                         | 34        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                       | 34        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                        | 34        | 0.38%   |
| Kingston SV300S37A240G 240GB SSD                    | 34        | 0.38%   |
| Crucial CT480BX500SSD1 480GB                        | 33        | 0.37%   |
| Toshiba TR200 240GB SSD                             | 32        | 0.36%   |
| Toshiba MQ01ABD050 500GB                            | 32        | 0.36%   |
| Seagate Expansion 1TB                               | 32        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB                            | 30        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1317      | 2036   | 40.54%  |
| WDC                 | 846       | 1246   | 26.04%  |
| Toshiba             | 403       | 584    | 12.4%   |
| Hitachi             | 245       | 294    | 7.54%   |
| Samsung Electronics | 132       | 163    | 4.06%   |
| HGST                | 132       | 164    | 4.06%   |
| Fujitsu             | 44        | 50     | 1.35%   |
| Maxtor              | 35        | 49     | 1.08%   |
| Unknown             | 34        | 41     | 1.05%   |
| Apple               | 22        | 27     | 0.68%   |
| USB3.0              | 6         | 6      | 0.18%   |
| SABRENT             | 6         | 6      | 0.18%   |
| ASMT                | 5         | 9      | 0.15%   |
| Hewlett-Packard     | 3         | 4      | 0.09%   |
| USB                 | 2         | 2      | 0.06%   |
| SSK                 | 2         | 2      | 0.06%   |
| Intenso             | 2         | 3      | 0.06%   |
| Quantum             | 1         | 1      | 0.03%   |
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
| Unknown             | 1         | 3      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 809       | 1122   | 29.44%  |
| Samsung Electronics | 479       | 674    | 17.43%  |
| Crucial             | 282       | 400    | 10.26%  |
| SanDisk             | 253       | 326    | 9.21%   |
| WDC                 | 137       | 201    | 4.99%   |
| Toshiba             | 106       | 203    | 3.86%   |
| China               | 80        | 109    | 2.91%   |
| SK hynix            | 44        | 49     | 1.6%    |
| Intel               | 38        | 55     | 1.38%   |
| Micron Technology   | 36        | 48     | 1.31%   |
| OCZ                 | 35        | 49     | 1.27%   |
| Netac               | 26        | 39     | 0.95%   |
| Transcend           | 23        | 48     | 0.84%   |
| KingSpec            | 22        | 29     | 0.8%    |
| Apple               | 21        | 25     | 0.76%   |
| A-DATA Technology   | 21        | 32     | 0.76%   |
| KIOXIA-EXCERIA      | 19        | 24     | 0.69%   |
| LITEON              | 18        | 19     | 0.66%   |
| JMicron Technology  | 18        | 19     | 0.66%   |
| Emtec               | 18        | 22     | 0.66%   |
| KingDian            | 17        | 22     | 0.62%   |
| USB30               | 16        | 34     | 0.58%   |
| Intenso             | 14        | 21     | 0.51%   |
| PNY                 | 13        | 23     | 0.47%   |
| Patriot             | 13        | 22     | 0.47%   |
| Teclast             | 12        | 14     | 0.44%   |
| FORESEE             | 11        | 16     | 0.4%    |
| Unknown             | 11        | 11     | 0.4%    |
| Drevo               | 10        | 12     | 0.36%   |
| Corsair             | 8         | 11     | 0.29%   |
| BAITITON            | 8         | 12     | 0.29%   |
| LITEONIT            | 6         | 7      | 0.22%   |
| GOODRAM             | 6         | 8      | 0.22%   |
| Maxtor              | 5         | 8      | 0.18%   |
| Dogfish             | 5         | 7      | 0.18%   |
| TCSUNBOW            | 4         | 5      | 0.15%   |
| SPCC                | 4         | 4      | 0.15%   |
| Phison              | 4         | 5      | 0.15%   |
| Hoodisk             | 4         | 5      | 0.15%   |
| Unknown             | 3         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2765      | 4709   | 38.49%  |
| SSD     | 2357      | 3853   | 32.81%  |
| NVMe    | 1689      | 2405   | 23.51%  |
| MMC     | 284       | 384    | 3.95%   |
| Unknown | 89        | 106    | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4066      | 8305   | 64.41%  |
| NVMe | 1687      | 2397   | 26.72%  |
| MMC  | 284       | 384    | 4.5%    |
| SAS  | 276       | 371    | 4.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3246      | 5409   | 61.54%  |
| 0.51-1.0        | 1426      | 2125   | 27.03%  |
| 1.01-2.0        | 374       | 614    | 7.09%   |
| 3.01-4.0        | 91        | 158    | 1.73%   |
| 2.01-3.0        | 86        | 136    | 1.63%   |
| 4.01-10.0       | 49        | 116    | 0.93%   |
| 10.01-20.0      | 2         | 2      | 0.04%   |
| More than 100.0 | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1593      | 27.08%  |
| 251-500        | 1383      | 23.51%  |
| 501-1000       | 806       | 13.7%   |
| 1-20           | 453       | 7.7%    |
| 1001-2000      | 420       | 7.14%   |
| 51-100         | 388       | 6.6%    |
| More than 3000 | 244       | 4.15%   |
| 21-50          | 242       | 4.11%   |
| 2001-3000      | 199       | 3.38%   |
| Unknown        | 154       | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2337      | 38.29%  |
| 21-50          | 1039      | 17.02%  |
| 101-250        | 783       | 12.83%  |
| 51-100         | 666       | 10.91%  |
| 251-500        | 461       | 7.55%   |
| 501-1000       | 321       | 5.26%   |
| 1001-2000      | 184       | 3.01%   |
| Unknown        | 154       | 2.52%   |
| More than 3000 | 92        | 1.51%   |
| 2001-3000      | 65        | 1.06%   |
| 0              | 2         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 18        | 18     | 3.28%   |
| Seagate ST3500418AS 500GB           | 16        | 22     | 2.92%   |
| Kingston SV300S37A120G 120GB SSD    | 14        | 20     | 2.55%   |
| Seagate ST9500325AS 500GB           | 12        | 14     | 2.19%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 1.46%   |
| SanDisk SSD PLUS 480GB              | 8         | 10     | 1.46%   |
| HGST HTS545050A7E680 500GB          | 7         | 9      | 1.28%   |
| Seagate ST3500320AS 500GB           | 6         | 10     | 1.09%   |
| Seagate ST31000528AS 1TB            | 6         | 7      | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 7      | 1.09%   |
| Seagate ST1000DM003-1CH162 1TB      | 6         | 7      | 1.09%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 8      | 0.91%   |
| China G521N256GB                    | 5         | 6      | 0.91%   |
| WDC WD5000AAKX-001CA0 500GB         | 4         | 6      | 0.73%   |
| WDC WD20EARX-00PASB0 2TB            | 4         | 6      | 0.73%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 0.73%   |
| Seagate ST9250827AS 250GB           | 4         | 4      | 0.73%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 0.73%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 4      | 0.73%   |
| Seagate ST1000DM003-1ER162 1TB      | 4         | 7      | 0.73%   |
| Kingston SUV400S37240G 240GB SSD    | 4         | 6      | 0.73%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.73%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.73%   |
| Drevo X1 SSD 64GB                   | 4         | 6      | 0.73%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 3         | 4      | 0.55%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 3         | 3      | 0.55%   |
| WDC WD20PURZ-85GU6Y0 2TB            | 3         | 4      | 0.55%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3         | 3      | 0.55%   |
| Toshiba DT01ACA100 1TB              | 3         | 6      | 0.55%   |
| Seagate ST3250310AS 250GB           | 3         | 3      | 0.55%   |
| Seagate ST3200822A 200GB            | 3         | 3      | 0.55%   |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 4      | 0.55%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 4      | 0.55%   |
| Samsung Electronics HD501LJ 500GB   | 3         | 3      | 0.55%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 4      | 0.55%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 0.55%   |
| Fujitsu MHZ2250BH G2 250GB          | 3         | 4      | 0.55%   |
| WDC WD6400AAKS-22A7B0 640GB         | 2         | 2      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 222    | 32.96%  |
| WDC                 | 95        | 122    | 17.79%  |
| Hitachi             | 38        | 41     | 7.12%   |
| Toshiba             | 36        | 42     | 6.74%   |
| Samsung Electronics | 36        | 39     | 6.74%   |
| Kingston            | 30        | 43     | 5.62%   |
| HGST                | 20        | 23     | 3.75%   |
| SanDisk             | 17        | 19     | 3.18%   |
| Crucial             | 12        | 14     | 2.25%   |
| Intel               | 10        | 12     | 1.87%   |
| China               | 10        | 12     | 1.87%   |
| Maxtor              | 9         | 11     | 1.69%   |
| SK hynix            | 7         | 7      | 1.31%   |
| Fujitsu             | 7         | 8      | 1.31%   |
| Drevo               | 5         | 7      | 0.94%   |
| OCZ                 | 3         | 3      | 0.56%   |
| Micron Technology   | 3         | 4      | 0.56%   |
| KingDian            | 2         | 3      | 0.37%   |
| Intenso             | 2         | 2      | 0.37%   |
| Transcend           | 1         | 8      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| Netac               | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 1      | 0.19%   |
| IBM                 | 1         | 1      | 0.19%   |
| Hypertec            | 1         | 1      | 0.19%   |
| HPE                 | 1         | 2      | 0.19%   |
| G521N               | 1         | 1      | 0.19%   |
| Dogfish             | 1         | 2      | 0.19%   |
| Corsair             | 1         | 1      | 0.19%   |
| ASMT                | 1         | 2      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| A-DATA Technology   | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 222    | 44%     |
| WDC                 | 93        | 120    | 23.25%  |
| Hitachi             | 38        | 41     | 9.5%    |
| Toshiba             | 31        | 37     | 7.75%   |
| Samsung Electronics | 21        | 23     | 5.25%   |
| HGST                | 20        | 23     | 5%      |
| Maxtor              | 9         | 11     | 2.25%   |
| Fujitsu             | 7         | 8      | 1.75%   |
| IBM                 | 1         | 1      | 0.25%   |
| HPE                 | 1         | 2      | 0.25%   |
| China               | 1         | 1      | 0.25%   |
| ASMT                | 1         | 2      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 371       | 492    | 74.35%  |
| SSD  | 115       | 154    | 23.05%  |
| NVMe | 13        | 14     | 2.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 14.29%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 7.14%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 7.14%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.14%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 7.14%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.14%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 7.14%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 7.14%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 50%     |
| Samsung Electronics | 3         | 4      | 21.43%  |
| Toshiba             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3431      | 6920   | 57.13%  |
| Works    | 2084      | 3862   | 34.7%   |
| Malfunc  | 477       | 660    | 7.94%   |
| Failed   | 14        | 15     | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3691      | 54.43%  |
| AMD                              | 955       | 14.08%  |
| Samsung Electronics              | 532       | 7.85%   |
| SanDisk                          | 325       | 4.79%   |
| SK hynix                         | 145       | 2.14%   |
| Kingston Technology Company      | 129       | 1.9%    |
| Phison Electronics               | 118       | 1.74%   |
| Micron Technology                | 112       | 1.65%   |
| Nvidia                           | 109       | 1.61%   |
| JMicron Technology               | 91        | 1.34%   |
| ASMedia Technology               | 88        | 1.3%    |
| Micron/Crucial Technology        | 79        | 1.17%   |
| Marvell Technology Group         | 68        | 1%      |
| Toshiba America Info Systems     | 66        | 0.97%   |
| KIOXIA                           | 63        | 0.93%   |
| Silicon Motion                   | 44        | 0.65%   |
| VIA Technologies                 | 35        | 0.52%   |
| Silicon Integrated Systems [SiS] | 23        | 0.34%   |
| LSI Logic / Symbios Logic        | 14        | 0.21%   |
| Union Memory (Shenzhen)          | 11        | 0.16%   |
| Apple                            | 10        | 0.15%   |
| Realtek Semiconductor            | 6         | 0.09%   |
| Hewlett-Packard                  | 6         | 0.09%   |
| Solid State Storage Technology   | 5         | 0.07%   |
| Silicon Image                    | 5         | 0.07%   |
| O2 Micro                         | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.07%   |
| Broadcom / LSI                   | 5         | 0.07%   |
| Shenzhen Longsys Electronics     | 4         | 0.06%   |
| Seagate Technology               | 4         | 0.06%   |
| Lite-On Technology               | 4         | 0.06%   |
| ADATA Technology                 | 4         | 0.06%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Adaptec                          | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Lenovo                           | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |
| Swissbit                         | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 674       | 8.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 288       | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 279       | 3.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 264       | 3.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 165       | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 153       | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 143       | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                         | 141       | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 140       | 1.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 131       | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 126       | 1.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 125       | 1.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 123       | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 121       | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 114       | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 105       | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 103       | 1.3%    |
| Samsung NVMe SSD Controller 980                                                | 102       | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 100       | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 99        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 94        | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 93        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 87        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 85        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 85        | 1.08%   |
| Intel SATA Controller [RAID mode]                                              | 82        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 77        | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 76        | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 75        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 73        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 71        | 0.9%    |
| Intel SSD 660P Series                                                          | 70        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 68        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 66        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 62        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 58        | 0.73%   |
| AMD 500 Series Chipset SATA Controller                                         | 58        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 57        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 53        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3906      | 56.48%  |
| NVMe | 1701      | 24.6%   |
| IDE  | 863       | 12.48%  |
| RAID | 425       | 6.15%   |
| SAS  | 12        | 0.17%   |
| SCSI | 9         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4222      | 76.75%  |
| AMD          | 1239      | 22.52%  |
| ARM          | 35        | 0.64%   |
| Qualcomm     | 4         | 0.07%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 65        | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 61        | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 57        | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 57        | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 48        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 48        | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 48        | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 45        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 41        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 40        | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 39        | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 0.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 38        | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 38        | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 37        | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 34        | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 33        | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 32        | 0.58%   |
| AMD Custom APU 0405                           | 32        | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 30        | 0.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 29        | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.49%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 27        | 0.49%   |
| Intel 12th Gen Core i7-12700H                 | 27        | 0.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.47%   |
| ARM Processor                                 | 26        | 0.47%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 26        | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 25        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 24        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 23        | 0.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 23        | 0.42%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 23        | 0.42%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1039      | 18.85%  |
| Intel Core i7           | 1014      | 18.39%  |
| Intel Core i3           | 434       | 7.87%   |
| Other                   | 429       | 7.78%   |
| Intel Celeron           | 345       | 6.26%   |
| AMD Ryzen 5             | 304       | 5.51%   |
| AMD Ryzen 7             | 281       | 5.1%    |
| Intel Core 2 Duo        | 263       | 4.77%   |
| Intel Atom              | 151       | 2.74%   |
| Intel Xeon              | 115       | 2.09%   |
| Intel Pentium           | 97        | 1.76%   |
| Intel Pentium Dual-Core | 86        | 1.56%   |
| Intel Core 2 Quad       | 76        | 1.38%   |
| AMD FX                  | 65        | 1.18%   |
| AMD Ryzen 9             | 61        | 1.11%   |
| Intel Pentium Dual      | 55        | 1%      |
| Intel Core 2            | 55        | 1%      |
| AMD A4                  | 50        | 0.91%   |
| AMD Ryzen 3             | 49        | 0.89%   |
| AMD A6                  | 39        | 0.71%   |
| Intel Genuine           | 36        | 0.65%   |
| AMD A8                  | 36        | 0.65%   |
| AMD A10                 | 36        | 0.65%   |
| Intel Core i9           | 31        | 0.56%   |
| AMD Athlon 64 X2        | 26        | 0.47%   |
| Intel Pentium 4         | 25        | 0.45%   |
| AMD E1                  | 24        | 0.44%   |
| AMD Athlon II X2        | 22        | 0.4%    |
| AMD Athlon              | 20        | 0.36%   |
| AMD Phenom II X4        | 15        | 0.27%   |
| AMD E                   | 15        | 0.27%   |
| AMD Ryzen 7 PRO         | 14        | 0.25%   |
| AMD Phenom              | 11        | 0.2%    |
| Intel Pentium D         | 10        | 0.18%   |
| Intel Pentium Silver    | 9         | 0.16%   |
| Intel Pentium M         | 9         | 0.16%   |
| Intel Celeron M         | 9         | 0.16%   |
| AMD Ryzen 5 PRO         | 9         | 0.16%   |
| AMD Phenom II X6        | 9         | 0.16%   |
| Intel Pentium Gold      | 8         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2206      | 39.97%  |
| 4       | 1933      | 35.02%  |
| 6       | 530       | 9.6%    |
| 8       | 422       | 7.65%   |
| 1       | 193       | 3.5%    |
| 12      | 72        | 1.3%    |
| 14      | 44        | 0.8%    |
| 10      | 38        | 0.69%   |
| 16      | 29        | 0.53%   |
| 3       | 22        | 0.4%    |
| Unknown | 16        | 0.29%   |
| 20      | 4         | 0.07%   |
| 24      | 3         | 0.05%   |
| 64      | 2         | 0.04%   |
| 32      | 2         | 0.04%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5451      | 99.07%  |
| 2       | 45        | 0.82%   |
| Unknown | 6         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3492      | 63.31%  |
| 1       | 2007      | 36.39%  |
| Unknown | 16        | 0.29%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5315      | 96.09%  |
| Unknown        | 115       | 2.08%   |
| 32-bit         | 67        | 1.21%   |
| 64-bit         | 34        | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1363      | 23.75%  |
| 0x306c3    | 269       | 4.69%   |
| 0x206a7    | 246       | 4.29%   |
| 0x306a9    | 229       | 3.99%   |
| 0x1067a    | 188       | 3.28%   |
| 0x906ea    | 151       | 2.63%   |
| 0x806ea    | 128       | 2.23%   |
| 0x806c1    | 123       | 2.14%   |
| 0x506e3    | 115       | 2%      |
| 0x40651    | 109       | 1.9%    |
| 0x6fd      | 108       | 1.88%   |
| 0x806ec    | 106       | 1.85%   |
| 0x806e9    | 99        | 1.73%   |
| 0x20655    | 98        | 1.71%   |
| 0x406e3    | 97        | 1.69%   |
| 0x08108109 | 86        | 1.5%    |
| 0x306d4    | 81        | 1.41%   |
| 0x906e9    | 80        | 1.39%   |
| 0x0a50000c | 63        | 1.1%    |
| 0x30678    | 62        | 1.08%   |
| 0x10676    | 59        | 1.03%   |
| 0x08701021 | 56        | 0.98%   |
| 0x6fb      | 54        | 0.94%   |
| 0x20652    | 52        | 0.91%   |
| 0x706a1    | 48        | 0.84%   |
| 0x0800820d | 47        | 0.82%   |
| 0x706e5    | 45        | 0.78%   |
| 0x506c9    | 45        | 0.78%   |
| 0x406c4    | 45        | 0.78%   |
| 0xa0652    | 42        | 0.73%   |
| 0x06006705 | 42        | 0.73%   |
| 0x08600106 | 41        | 0.71%   |
| 0x706a8    | 40        | 0.7%    |
| 0x6f6      | 38        | 0.66%   |
| 0x106ca    | 36        | 0.63%   |
| 0x08108102 | 36        | 0.63%   |
| 0x906ed    | 35        | 0.61%   |
| 0x906a3    | 35        | 0.61%   |
| 0x06000852 | 35        | 0.61%   |
| 0x06001119 | 34        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 840       | 15.23%  |
| Haswell          | 526       | 9.54%   |
| SandyBridge      | 327       | 5.93%   |
| Penryn           | 322       | 5.84%   |
| IvyBridge        | 286       | 5.18%   |
| Core             | 277       | 5.02%   |
| Skylake          | 271       | 4.91%   |
| Zen+             | 215       | 3.9%    |
| Zen 2            | 209       | 3.79%   |
| Unknown          | 204       | 3.7%    |
| Westmere         | 189       | 3.43%   |
| TigerLake        | 178       | 3.23%   |
| Silvermont       | 178       | 3.23%   |
| Zen 3            | 154       | 2.79%   |
| CometLake        | 126       | 2.28%   |
| Broadwell        | 120       | 2.18%   |
| Goldmont plus    | 116       | 2.1%    |
| Piledriver       | 99        | 1.79%   |
| Zen              | 95        | 1.72%   |
| K10              | 94        | 1.7%    |
| Icelake          | 91        | 1.65%   |
| Bonnell          | 75        | 1.36%   |
| Excavator        | 72        | 1.31%   |
| Alderlake Hybrid | 71        | 1.29%   |
| K8 Hammer        | 56        | 1.02%   |
| Goldmont         | 53        | 0.96%   |
| Nehalem          | 48        | 0.87%   |
| NetBurst         | 38        | 0.69%   |
| Puma             | 34        | 0.62%   |
| P6               | 31        | 0.56%   |
| Steamroller      | 28        | 0.51%   |
| Jaguar           | 28        | 0.51%   |
| Bobcat           | 25        | 0.45%   |
| Tremont          | 16        | 0.29%   |
| K10 Llano        | 12        | 0.22%   |
| Bulldozer        | 8         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3153      | 48.37%  |
| Nvidia                                       | 1891      | 29.01%  |
| AMD                                          | 1411      | 21.65%  |
| Matrox Electronics Systems                   | 23        | 0.35%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.23%   |
| VIA Technologies                             | 12        | 0.18%   |
| ASPEED Technology                            | 10        | 0.15%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 224       | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 169       | 2.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 149       | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 145       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 141       | 2.1%    |
| Intel UHD Graphics 620                                                                   | 132       | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 128       | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 114       | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 113       | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 107       | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 104       | 1.55%   |
| Intel HD Graphics 620                                                                    | 103       | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 103       | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 99        | 1.47%   |
| AMD Renoir                                                                               | 99        | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 96        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 92        | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 90        | 1.34%   |
| Intel HD Graphics 530                                                                    | 86        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 86        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 83        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 83        | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 77        | 1.14%   |
| Intel HD Graphics 630                                                                    | 76        | 1.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 74        | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 69        | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                               | 67        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 65        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 58        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 58        | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 54        | 0.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 53        | 0.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 52        | 0.77%   |
| Intel HD Graphics 500                                                                    | 50        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 44        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 43        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2239      | 40.37%  |
| 1 x AMD                | 1100      | 19.83%  |
| 1 x Nvidia             | 1035      | 18.66%  |
| Intel + Nvidia         | 724       | 13.05%  |
| AMD + Nvidia           | 117       | 2.11%   |
| Intel + AMD            | 115       | 2.07%   |
| 2 x AMD                | 80        | 1.44%   |
| Other                  | 43        | 0.78%   |
| 1 x Matrox             | 20        | 0.36%   |
| 2 x Nvidia             | 16        | 0.29%   |
| 1 x SiS                | 15        | 0.27%   |
| 2 x Intel              | 12        | 0.22%   |
| 1 x VIA                | 12        | 0.22%   |
| 1 x ASPEED             | 6         | 0.11%   |
| Nvidia + ASPEED        | 4         | 0.07%   |
| Nvidia + Matrox        | 3         | 0.05%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4415      | 78.97%  |
| Proprietary | 936       | 16.74%  |
| Unknown     | 240       | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3082      | 54.29%  |
| 1.01-2.0   | 738       | 13%     |
| 0.01-0.5   | 668       | 11.77%  |
| 3.01-4.0   | 407       | 7.17%   |
| 0.51-1.0   | 395       | 6.96%   |
| 7.01-8.0   | 210       | 3.7%    |
| 5.01-6.0   | 102       | 1.8%    |
| 8.01-16.0  | 36        | 0.63%   |
| 2.01-3.0   | 31        | 0.55%   |
| 16.01-24.0 | 8         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 688       | 11.63%  |
| AU Optronics            | 610       | 10.31%  |
| Chimei Innolux          | 566       | 9.57%   |
| LG Display              | 470       | 7.94%   |
| BOE                     | 443       | 7.49%   |
| Goldstar                | 415       | 7.01%   |
| Hewlett-Packard         | 291       | 4.92%   |
| Dell                    | 235       | 3.97%   |
| BenQ                    | 233       | 3.94%   |
| Acer                    | 201       | 3.4%    |
| Ancor Communications    | 166       | 2.81%   |
| Philips                 | 162       | 2.74%   |
| Apple                   | 127       | 2.15%   |
| AOC                     | 127       | 2.15%   |
| Chi Mei Optoelectronics | 103       | 1.74%   |
| Sharp                   | 101       | 1.71%   |
| Lenovo                  | 90        | 1.52%   |
| PANDA                   | 73        | 1.23%   |
| LG Electronics          | 58        | 0.98%   |
| Sony                    | 54        | 0.91%   |
| Unknown                 | 48        | 0.81%   |
| ASUSTek Computer        | 47        | 0.79%   |
| HannStar                | 45        | 0.76%   |
| LG Philips              | 44        | 0.74%   |
| ViewSonic               | 34        | 0.57%   |
| InfoVision              | 24        | 0.41%   |
| Valve                   | 23        | 0.39%   |
| MSI                     | 23        | 0.39%   |
| CPT                     | 15        | 0.25%   |
| Toshiba                 | 13        | 0.22%   |
| OEM                     | 13        | 0.22%   |
| Eizo                    | 13        | 0.22%   |
| CSO                     | 13        | 0.22%   |
| ___                     | 11        | 0.19%   |
| Vestel Elektronik       | 11        | 0.19%   |
| NEC Computers           | 11        | 0.19%   |
| Mi                      | 11        | 0.19%   |
| Iiyama                  | 11        | 0.19%   |
| Fujitsu Siemens         | 11        | 0.19%   |
| Panasonic               | 10        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 67        | 1.09%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 40        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 33        | 0.54%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 32        | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 32        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 29        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 24        | 0.39%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 23        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 23        | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.36%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 21        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 20        | 0.33%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 20        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 20        | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 20        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 16        | 0.26%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 15        | 0.25%   |
| Ancor Communications VX239 ACI23E1 1920x1080 510x290mm 23.1-inch         | 15        | 0.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 14        | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 14        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 14        | 0.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 14        | 0.23%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 14        | 0.23%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 14        | 0.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 13        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.21%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 13        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.21%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 13        | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2447      | 43.49%  |
| 1366x768 (WXGA)    | 1122      | 19.94%  |
| 3840x2160 (4K)     | 281       | 4.99%   |
| 1280x1024 (SXGA)   | 230       | 4.09%   |
| 2560x1440 (QHD)    | 222       | 3.95%   |
| 1280x800 (WXGA)    | 175       | 3.11%   |
| 1680x1050 (WSXGA+) | 159       | 2.83%   |
| 1440x900 (WXGA+)   | 157       | 2.79%   |
| 1600x900 (HD+)     | 125       | 2.22%   |
| 1920x1200 (WUXGA)  | 99        | 1.76%   |
| 2560x1080          | 66        | 1.17%   |
| Unknown            | 65        | 1.16%   |
| 1360x768           | 51        | 0.91%   |
| 1024x600           | 44        | 0.78%   |
| 3440x1440          | 42        | 0.75%   |
| 2560x1600          | 39        | 0.69%   |
| 2160x1440          | 34        | 0.6%    |
| 800x1280           | 29        | 0.52%   |
| 1024x768 (XGA)     | 27        | 0.48%   |
| 3840x1080          | 21        | 0.37%   |
| 2880x1800          | 21        | 0.37%   |
| 1600x1200          | 15        | 0.27%   |
| 1920x540           | 14        | 0.25%   |
| 3200x1800 (QHD+)   | 9         | 0.16%   |
| 2288x1287          | 8         | 0.14%   |
| 3840x2400          | 7         | 0.12%   |
| 3200x1080          | 6         | 0.11%   |
| 2736x1824          | 6         | 0.11%   |
| 3840x1600          | 5         | 0.09%   |
| 1920x1280          | 5         | 0.09%   |
| 1280x768           | 5         | 0.09%   |
| 4480x1080          | 4         | 0.07%   |
| 1280x720 (HD)      | 4         | 0.07%   |
| 3840x1200          | 3         | 0.05%   |
| 3600x1080          | 3         | 0.05%   |
| 3456x2160          | 3         | 0.05%   |
| 3360x1080          | 3         | 0.05%   |
| 3072x1920          | 3         | 0.05%   |
| 2960x1050          | 3         | 0.05%   |
| 2944x1080          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1677      | 28.36%  |
| 13      | 457       | 7.73%   |
| 24      | 429       | 7.26%   |
| 21      | 415       | 7.02%   |
| 27      | 401       | 6.78%   |
| 23      | 342       | 5.78%   |
| 14      | 317       | 5.36%   |
| Unknown | 314       | 5.31%   |
| 17      | 294       | 4.97%   |
| 19      | 179       | 3.03%   |
| 18      | 135       | 2.28%   |
| 34      | 94        | 1.59%   |
| 22      | 91        | 1.54%   |
| 31      | 88        | 1.49%   |
| 20      | 84        | 1.42%   |
| 12      | 80        | 1.35%   |
| 16      | 61        | 1.03%   |
| 11      | 60        | 1.01%   |
| 10      | 55        | 0.93%   |
| 84      | 52        | 0.88%   |
| 54      | 30        | 0.51%   |
| 25      | 27        | 0.46%   |
| 32      | 26        | 0.44%   |
| 26      | 25        | 0.42%   |
| 72      | 24        | 0.41%   |
| 7       | 23        | 0.39%   |
| 40      | 21        | 0.36%   |
| 65      | 9         | 0.15%   |
| 46      | 9         | 0.15%   |
| 28      | 9         | 0.15%   |
| 52      | 8         | 0.14%   |
| 48      | 8         | 0.14%   |
| 3       | 8         | 0.14%   |
| 142     | 7         | 0.12%   |
| 33      | 6         | 0.1%    |
| 37      | 5         | 0.08%   |
| 29      | 5         | 0.08%   |
| 60      | 4         | 0.07%   |
| 36      | 4         | 0.07%   |
| 8       | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2297      | 39.57%  |
| 501-600        | 1091      | 18.79%  |
| 401-500        | 810       | 13.95%  |
| 201-300        | 468       | 8.06%   |
| 351-400        | 319       | 5.5%    |
| Unknown        | 314       | 5.41%   |
| 601-700        | 144       | 2.48%   |
| 701-800        | 127       | 2.19%   |
| 1501-2000      | 79        | 1.36%   |
| 1001-1500      | 73        | 1.26%   |
| 801-900        | 35        | 0.6%    |
| 1-100          | 31        | 0.53%   |
| More than 2000 | 7         | 0.12%   |
| 901-1000       | 6         | 0.1%    |
| 101-200        | 4         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3911      | 73.32%  |
| 16/10   | 661       | 12.39%  |
| Unknown | 264       | 4.95%   |
| 5/4     | 210       | 3.94%   |
| 21/9    | 101       | 1.89%   |
| 3/2     | 70        | 1.31%   |
| 4/3     | 61        | 1.14%   |
| 0.67    | 23        | 0.43%   |
| 6/5     | 10        | 0.19%   |
| 1.00    | 7         | 0.13%   |
| 32/9    | 6         | 0.11%   |
| 0.45    | 3         | 0.06%   |
| 0.56    | 2         | 0.04%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1685      | 28.75%  |
| 201-250        | 1048      | 17.88%  |
| 81-90          | 562       | 9.59%   |
| 301-350        | 414       | 7.06%   |
| 151-200        | 382       | 6.52%   |
| Unknown        | 314       | 5.36%   |
| 141-150        | 234       | 3.99%   |
| 351-500        | 219       | 3.74%   |
| 71-80          | 215       | 3.67%   |
| More than 1000 | 149       | 2.54%   |
| 121-130        | 137       | 2.34%   |
| 251-300        | 130       | 2.22%   |
| 61-70          | 68        | 1.16%   |
| 51-60          | 60        | 1.02%   |
| 41-50          | 55        | 0.94%   |
| 501-1000       | 55        | 0.94%   |
| 111-120        | 43        | 0.73%   |
| 131-140        | 37        | 0.63%   |
| 1-40           | 35        | 0.6%    |
| 91-100         | 19        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1968      | 34.54%  |
| 101-120       | 1530      | 26.85%  |
| 121-160       | 1356      | 23.8%   |
| 161-240       | 325       | 5.7%    |
| Unknown       | 314       | 5.51%   |
| 1-50          | 115       | 2.02%   |
| More than 240 | 90        | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4439      | 78.66%  |
| 2     | 837       | 14.83%  |
| 0     | 257       | 4.55%   |
| 3     | 102       | 1.81%   |
| 4     | 7         | 0.12%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3152      | 37.88%  |
| Intel                             | 2364      | 28.41%  |
| Qualcomm Atheros                  | 994       | 11.94%  |
| Broadcom                          | 514       | 6.18%   |
| TP-Link                           | 139       | 1.67%   |
| Ralink Technology                 | 127       | 1.53%   |
| Marvell Technology Group          | 123       | 1.48%   |
| MediaTek                          | 106       | 1.27%   |
| Broadcom Limited                  | 106       | 1.27%   |
| Nvidia                            | 92        | 1.11%   |
| Ralink                            | 86        | 1.03%   |
| Qualcomm Atheros Communications   | 42        | 0.5%    |
| ASIX Electronics                  | 40        | 0.48%   |
| Xiaomi                            | 35        | 0.42%   |
| Samsung Electronics               | 29        | 0.35%   |
| D-Link                            | 27        | 0.32%   |
| Silicon Integrated Systems [SiS]  | 20        | 0.24%   |
| VIA Technologies                  | 19        | 0.23%   |
| DisplayLink                       | 18        | 0.22%   |
| D-Link System                     | 18        | 0.22%   |
| ASUSTek Computer                  | 18        | 0.22%   |
| Qualcomm                          | 16        | 0.19%   |
| Lenovo                            | 15        | 0.18%   |
| Ericsson Business Mobile Networks | 15        | 0.18%   |
| Dell                              | 15        | 0.18%   |
| JMicron Technology                | 14        | 0.17%   |
| Sierra Wireless                   | 13        | 0.16%   |
| Hewlett-Packard                   | 13        | 0.16%   |
| Belkin Components                 | 12        | 0.14%   |
| Huawei Technologies               | 11        | 0.13%   |
| Microsoft                         | 10        | 0.12%   |
| Edimax Technology                 | 9         | 0.11%   |
| Microchip Technology              | 7         | 0.08%   |
| ZyDAS                             | 6         | 0.07%   |
| NetGear                           | 5         | 0.06%   |
| Aquantia                          | 5         | 0.06%   |
| LSI                               | 4         | 0.05%   |
| Google                            | 4         | 0.05%   |
| Gemtek                            | 4         | 0.05%   |
| Attansic Technology               | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2128      | 22.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 329       | 3.43%   |
| Intel Wi-Fi 6 AX200                                                     | 221       | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 167       | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 155       | 1.62%   |
| Intel Wi-Fi 6 AX201                                                     | 132       | 1.38%   |
| Intel Wireless 8265 / 8275                                              | 130       | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 127       | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 122       | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 120       | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 114       | 1.19%   |
| Intel Wireless 7265                                                     | 112       | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 111       | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 107       | 1.12%   |
| Intel Wireless 3165                                                     | 104       | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                       | 101       | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 99        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                    | 91        | 0.95%   |
| Intel I211 Gigabit Network Connection                                   | 90        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 85        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 77        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 75        | 0.78%   |
| Intel Wireless 7260                                                     | 71        | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 67        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 56        | 0.58%   |
| Intel Ethernet Controller I225-V                                        | 51        | 0.53%   |
| Intel WiFi Link 5100                                                    | 50        | 0.52%   |
| Intel Ethernet Connection I217-LM                                       | 50        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 0.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 50        | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 49        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 48        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 48        | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.49%   |
| Intel Wireless 8260                                                     | 47        | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 46        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 46        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1789      | 40.27%  |
| Realtek Semiconductor                 | 857       | 19.29%  |
| Qualcomm Atheros                      | 765       | 17.22%  |
| Broadcom                              | 324       | 7.29%   |
| Ralink Technology                     | 127       | 2.86%   |
| TP-Link                               | 117       | 2.63%   |
| MediaTek                              | 101       | 2.27%   |
| Ralink                                | 86        | 1.94%   |
| Broadcom Limited                      | 73        | 1.64%   |
| Qualcomm Atheros Communications       | 42        | 0.95%   |
| D-Link                                | 27        | 0.61%   |
| ASUSTek Computer                      | 18        | 0.41%   |
| Sierra Wireless                       | 13        | 0.29%   |
| D-Link System                         | 12        | 0.27%   |
| Belkin Components                     | 12        | 0.27%   |
| Microsoft                             | 9         | 0.2%    |
| Edimax Technology                     | 9         | 0.2%    |
| Dell                                  | 9         | 0.2%    |
| Marvell Technology Group              | 7         | 0.16%   |
| ZyDAS                                 | 6         | 0.14%   |
| NetGear                               | 5         | 0.11%   |
| Qualcomm                              | 4         | 0.09%   |
| Hewlett-Packard                       | 4         | 0.09%   |
| Gemtek                                | 4         | 0.09%   |
| Texas Instruments                     | 3         | 0.07%   |
| Tenda                                 | 2         | 0.05%   |
| Sitecom Europe                        | 2         | 0.05%   |
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

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 221       | 4.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 155       | 3.47%   |
| Intel Wi-Fi 6 AX201                                                     | 132       | 2.95%   |
| Intel Wireless 8265 / 8275                                              | 130       | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 127       | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 122       | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 114       | 2.55%   |
| Intel Wireless 7265                                                     | 112       | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 111       | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 107       | 2.39%   |
| Intel Wireless 3165                                                     | 104       | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 99        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 85        | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 77        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 75        | 1.68%   |
| Intel Wireless 7260                                                     | 71        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 67        | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 56        | 1.25%   |
| Intel WiFi Link 5100                                                    | 50        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 50        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 49        | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 48        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 48        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 1.05%   |
| Intel Wireless 8260                                                     | 47        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 46        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 45        | 1.01%   |
| Intel Wireless 3160                                                     | 44        | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 44        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 44        | 0.98%   |
| Realtek 802.11ac NIC                                                    | 42        | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 40        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 0.85%   |
| Intel Wireless-AC 9260                                                  | 38        | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2781      | 56.18%  |
| Intel                                  | 1054      | 21.29%  |
| Qualcomm Atheros                       | 320       | 6.46%   |
| Broadcom                               | 255       | 5.15%   |
| Marvell Technology Group               | 117       | 2.36%   |
| Nvidia                                 | 92        | 1.86%   |
| ASIX Electronics                       | 40        | 0.81%   |
| Broadcom Limited                       | 35        | 0.71%   |
| Xiaomi                                 | 34        | 0.69%   |
| Samsung Electronics                    | 28        | 0.57%   |
| TP-Link                                | 23        | 0.46%   |
| Silicon Integrated Systems [SiS]       | 20        | 0.4%    |
| VIA Technologies                       | 19        | 0.38%   |
| DisplayLink                            | 18        | 0.36%   |
| Lenovo                                 | 15        | 0.3%    |
| JMicron Technology                     | 14        | 0.28%   |
| Qualcomm                               | 12        | 0.24%   |
| D-Link System                          | 6         | 0.12%   |
| Microchip Technology                   | 5         | 0.1%    |
| Huawei Technologies                    | 5         | 0.1%    |
| Hewlett-Packard                        | 5         | 0.1%    |
| Aquantia                               | 5         | 0.1%    |
| MediaTek                               | 4         | 0.08%   |
| LSI                                    | 4         | 0.08%   |
| Google                                 | 4         | 0.08%   |
| Attansic Technology                    | 4         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.06%   |
| IBM                                    | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| OPPO Electronics                       | 2         | 0.04%   |
| Davicom Semiconductor                  | 2         | 0.04%   |
| ADMtek                                 | 2         | 0.04%   |
| Accton Technology                      | 2         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| MosChip Semiconductor                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2128      | 42.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 329       | 6.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 167       | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 120       | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 101       | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 91        | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 90        | 1.78%   |
| Intel Ethernet Controller I225-V                                  | 51        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 50        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 43        | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 42        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 39        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 38        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 34        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 34        | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 30        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 29        | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 28        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 27        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 27        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 26        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 26        | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 26        | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 24        | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 23        | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 21        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4722      | 52.67%  |
| WiFi     | 4174      | 46.55%  |
| Modem    | 62        | 0.69%   |
| Unknown  | 8         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3163      | 55.02%  |
| Ethernet | 2586      | 44.98%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2944      | 53.29%  |
| 1     | 2346      | 42.46%  |
| 0     | 130       | 2.35%   |
| 3     | 78        | 1.41%   |
| 4     | 18        | 0.33%   |
| 5     | 5         | 0.09%   |
| 6     | 4         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5296      | 95.66%  |
| Yes  | 240       | 4.34%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1440      | 43.93%  |
| Realtek Semiconductor           | 386       | 11.78%  |
| Cambridge Silicon Radio         | 266       | 8.11%   |
| IMC Networks                    | 215       | 6.56%   |
| Qualcomm Atheros Communications | 173       | 5.28%   |
| Apple                           | 136       | 4.15%   |
| Broadcom                        | 127       | 3.87%   |
| Foxconn / Hon Hai               | 113       | 3.45%   |
| Lite-On Technology              | 108       | 3.29%   |
| ASUSTek Computer                | 56        | 1.71%   |
| Realtek                         | 44        | 1.34%   |
| Toshiba                         | 40        | 1.22%   |
| Dell                            | 30        | 0.92%   |
| Hewlett-Packard                 | 24        | 0.73%   |
| Ralink                          | 23        | 0.7%    |
| MediaTek                        | 18        | 0.55%   |
| Alps Electric                   | 15        | 0.46%   |
| Foxconn International           | 11        | 0.34%   |
| Belkin Components               | 10        | 0.31%   |
| TP-Link                         | 8         | 0.24%   |
| Integrated System Solution      | 8         | 0.24%   |
| Marvell Semiconductor           | 5         | 0.15%   |
| Ralink Technology               | 4         | 0.12%   |
| Edimax Technology               | 3         | 0.09%   |
| Askey Computer                  | 3         | 0.09%   |
| Actions                         | 3         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| Roper                           | 2         | 0.06%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 510       | 15.55%  |
| Realtek Bluetooth Radio                             | 280       | 8.54%   |
| Intel AX201 Bluetooth                               | 267       | 8.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 266       | 8.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 234       | 7.14%   |
| Intel AX200 Bluetooth                               | 214       | 6.53%   |
| IMC Networks Bluetooth Radio                        | 105       | 3.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 72        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 70        | 2.13%   |
| Apple Bluetooth Host Controller                     | 59        | 1.8%    |
| IMC Networks Bluetooth Device                       | 53        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 1.49%   |
| Intel Bluetooth Device                              | 49        | 1.49%   |
| Realtek Bluetooth Radio                             | 44        | 1.34%   |
| Intel AX210 Bluetooth                               | 43        | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 41        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 41        | 1.25%   |
| IMC Networks Wireless_Device                        | 38        | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 36        | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 35        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 29        | 0.88%   |
| Lite-On Bluetooth Device                            | 28        | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 0.82%   |
| Ralink RT3290 Bluetooth                             | 23        | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 23        | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 20        | 0.61%   |
| MediaTek Wireless_Device                            | 18        | 0.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.55%   |
| Apple Bluetooth HCI                                 | 17        | 0.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.4%    |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.4%    |
| Realtek RTL8821A Bluetooth                          | 12        | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3996      | 53.55%  |
| AMD                                  | 1484      | 19.89%  |
| Nvidia                               | 1305      | 17.49%  |
| C-Media Electronics                  | 114       | 1.53%   |
| Logitech                             | 42        | 0.56%   |
| Creative Labs                        | 39        | 0.52%   |
| Texas Instruments                    | 30        | 0.4%    |
| JMTek                                | 28        | 0.38%   |
| Silicon Integrated Systems [SiS]     | 23        | 0.31%   |
| Plantronics                          | 23        | 0.31%   |
| ASUSTek Computer                     | 23        | 0.31%   |
| VIA Technologies                     | 21        | 0.28%   |
| GN Netcom                            | 20        | 0.27%   |
| Kingston Technology                  | 18        | 0.24%   |
| Lenovo                               | 17        | 0.23%   |
| Corsair                              | 17        | 0.23%   |
| Focusrite-Novation                   | 16        | 0.21%   |
| Creative Technology                  | 15        | 0.2%    |
| SteelSeries ApS                      | 13        | 0.17%   |
| Realtek Semiconductor                | 13        | 0.17%   |
| Generalplus Technology               | 12        | 0.16%   |
| Sennheiser Communications            | 9         | 0.12%   |
| Dell                                 | 9         | 0.12%   |
| BEHRINGER International              | 9         | 0.12%   |
| Micro Star International             | 8         | 0.11%   |
| Apple                                | 8         | 0.11%   |
| Tenx Technology                      | 6         | 0.08%   |
| M-Audio                              | 6         | 0.08%   |
| Hewlett-Packard                      | 6         | 0.08%   |
| Ensoniq                              | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.07%   |
| Sony                                 | 5         | 0.07%   |
| Razer USA                            | 5         | 0.07%   |
| Yamaha                               | 4         | 0.05%   |
| Blue Microphones                     | 4         | 0.05%   |
| XMOS                                 | 3         | 0.04%   |
| SAVITECH                             | 3         | 0.04%   |
| QinHeng Electronics                  | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |
| Guillemot                            | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 464       | 5.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 365       | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 311       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 301       | 3.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 280       | 3.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 233       | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 231       | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 210       | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 207       | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 205       | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 203       | 2.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 178       | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 176       | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 164       | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 163       | 1.84%   |
| AMD FCH Azalia Controller                                                  | 154       | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 150       | 1.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 149       | 1.68%   |
| Intel 8 Series HD Audio Controller                                         | 146       | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 145       | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 126       | 1.42%   |
| Intel 200 Series PCH HD Audio                                              | 119       | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 117       | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 116       | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 115       | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 114       | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 112       | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 111       | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 102       | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 95        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 89        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 81        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 75        | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 75        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 71        | 0.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 70        | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 66        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 65        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 64        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 64        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 720       | 22.38%  |
| SK hynix            | 512       | 15.92%  |
| Kingston            | 500       | 15.54%  |
| Unknown             | 325       | 10.1%   |
| Micron Technology   | 311       | 9.67%   |
| Crucial             | 225       | 6.99%   |
| Corsair             | 147       | 4.57%   |
| G.Skill             | 93        | 2.89%   |
| Ramaxel Technology  | 74        | 2.3%    |
| Unknown (ABCD)      | 48        | 1.49%   |
| Elpida              | 44        | 1.37%   |
| A-DATA Technology   | 31        | 0.96%   |
| Nanya Technology    | 30        | 0.93%   |
| Unknown             | 19        | 0.59%   |
| Silicon Power       | 15        | 0.47%   |
| GOODRAM             | 13        | 0.4%    |
| Team                | 10        | 0.31%   |
| Transcend           | 9         | 0.28%   |
| Apacer              | 8         | 0.25%   |
| Unifosa             | 6         | 0.19%   |
| Wilk                | 4         | 0.12%   |
| Timetec             | 4         | 0.12%   |
| Patriot             | 4         | 0.12%   |
| Kllisre             | 4         | 0.12%   |
| Avant               | 4         | 0.12%   |
| ASint Technology    | 4         | 0.12%   |
| Atermiter           | 3         | 0.09%   |
| Wodposit            | 2         | 0.06%   |
| Unknown (AB)        | 2         | 0.06%   |
| Toshiba             | 2         | 0.06%   |
| SHARETRONIC         | 2         | 0.06%   |
| Qimonda             | 2         | 0.06%   |
| PNY                 | 2         | 0.06%   |
| Neo Forza           | 2         | 0.06%   |
| Micron/Elpida       | 2         | 0.06%   |
| KomputerBay         | 2         | 0.06%   |
| Innodisk            | 2         | 0.06%   |
| Goldkey             | 2         | 0.06%   |
| Exceleram           | 2         | 0.06%   |
| ChangXin Memory     | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 1.07%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 35        | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 31        | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 25        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 21        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.58%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 20        | 0.58%   |
| Unknown                                                          | 19        | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 17        | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 16        | 0.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 16        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 14        | 0.41%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 14        | 0.41%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 13        | 0.38%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 13        | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.35%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 12        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1351      | 48.03%  |
| DDR3    | 865       | 30.75%  |
| DDR2    | 155       | 5.51%   |
| LPDDR4  | 122       | 4.34%   |
| SDRAM   | 84        | 2.99%   |
| Unknown | 82        | 2.92%   |
| LPDDR3  | 65        | 2.31%   |
| DDR5    | 48        | 1.71%   |
| DDR     | 19        | 0.68%   |
| LPDDR5  | 14        | 0.5%    |
| DRAM    | 8         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1647      | 58.61%  |
| DIMM            | 942       | 33.52%  |
| Row Of Chips    | 203       | 7.22%   |
| Chip            | 10        | 0.36%   |
| FB-DIMM         | 3         | 0.11%   |
| RIMM            | 2         | 0.07%   |
| Unknown         | 2         | 0.07%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1215      | 39.76%  |
| 4096  | 783       | 25.62%  |
| 16384 | 455       | 14.89%  |
| 2048  | 392       | 12.83%  |
| 1024  | 123       | 4.02%   |
| 32768 | 71        | 2.32%   |
| 512   | 9         | 0.29%   |
| 65536 | 4         | 0.13%   |
| 256   | 3         | 0.1%    |
| 3072  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 539       | 17.74%  |
| 3200    | 480       | 15.79%  |
| 2667    | 441       | 14.51%  |
| 2400    | 245       | 8.06%   |
| 1333    | 191       | 6.28%   |
| 2133    | 139       | 4.57%   |
| 667     | 98        | 3.22%   |
| 1334    | 92        | 3.03%   |
| 800     | 80        | 2.63%   |
| 3600    | 77        | 2.53%   |
| Unknown | 63        | 2.07%   |
| 1867    | 60        | 1.97%   |
| 4267    | 40        | 1.32%   |
| 4800    | 38        | 1.25%   |
| 8400    | 36        | 1.18%   |
| 1067    | 32        | 1.05%   |
| 1866    | 25        | 0.82%   |
| 3266    | 24        | 0.79%   |
| 3400    | 22        | 0.72%   |
| 2933    | 22        | 0.72%   |
| 3533    | 20        | 0.66%   |
| 1066    | 20        | 0.66%   |
| 2048    | 19        | 0.63%   |
| 3000    | 17        | 0.56%   |
| 533     | 17        | 0.56%   |
| 6400    | 16        | 0.53%   |
| 3733    | 16        | 0.53%   |
| 4199    | 14        | 0.46%   |
| 2733    | 13        | 0.43%   |
| 3800    | 11        | 0.36%   |
| 2666    | 11        | 0.36%   |
| 2800    | 9         | 0.3%    |
| 1800    | 9         | 0.3%    |
| 4266    | 8         | 0.26%   |
| 3466    | 7         | 0.23%   |
| 1639    | 7         | 0.23%   |
| 975     | 6         | 0.2%    |
| 400     | 6         | 0.2%    |
| 3933    | 5         | 0.16%   |
| 3534    | 5         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 73        | 51.41%  |
| Brother Industries       | 26        | 18.31%  |
| Canon                    | 14        | 9.86%   |
| Samsung Electronics      | 9         | 6.34%   |
| Seiko Epson              | 8         | 5.63%   |
| Oki Data                 | 3         | 2.11%   |
| Dymo-CoStar              | 2         | 1.41%   |
| Ricoh                    | 1         | 0.7%    |
| Prolific Technology      | 1         | 0.7%    |
| Magic Control Technology | 1         | 0.7%    |
| Lexmark International    | 1         | 0.7%    |
| Kyocera                  | 1         | 0.7%    |
| Konica Minolta           | 1         | 0.7%    |
| Apple                    | 1         | 0.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 6         | 4.2%    |
| HP DeskJet 2600 series                          | 6         | 4.2%    |
| Brother HL-2030 Laser Printer                   | 5         | 3.5%    |
| HP LaserJet 1020                                | 4         | 2.8%    |
| Canon PIXMA MG2500 Series                       | 4         | 2.8%    |
| Oki Data USB Device                             | 3         | 2.1%    |
| HP ENVY 5540 series                             | 3         | 2.1%    |
| HP DeskJet F2492 All-in-One                     | 3         | 2.1%    |
| HP DeskJet 2700 series                          | 3         | 2.1%    |
| HP Deskjet 1050 J410                            | 3         | 2.1%    |
| Canon LiDE 400                                  | 3         | 2.1%    |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.4%    |
| Samsung M2070 Series                            | 2         | 1.4%    |
| HP LaserJet M14-M17                             | 2         | 1.4%    |
| HP LaserJet 1010                                | 2         | 1.4%    |
| HP ENVY 5000 series                             | 2         | 1.4%    |
| HP ENVY 4520 series                             | 2         | 1.4%    |
| HP ENVY 4500 series                             | 2         | 1.4%    |
| HP DeskJet 5550                                 | 2         | 1.4%    |
| HP DeskJet 3630 series                          | 2         | 1.4%    |
| HP Deskjet 2050 J510                            | 2         | 1.4%    |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.4%    |
| Brother Printer                                 | 2         | 1.4%    |
| Brother MFC-J5330DW                             | 2         | 1.4%    |
| Brother DCP-1510                                | 2         | 1.4%    |
| Seiko Epson XP-255 257 Series                   | 1         | 0.7%    |
| Seiko Epson XP-230 Series                       | 1         | 0.7%    |
| Seiko Epson XP-225 Series                       | 1         | 0.7%    |
| Seiko Epson WF-2830 Series                      | 1         | 0.7%    |
| Seiko Epson Printer                             | 1         | 0.7%    |
| Seiko Epson L555 Series                         | 1         | 0.7%    |
| Seiko Epson L1300 Series                        | 1         | 0.7%    |
| Seiko Epson ET-2700 Series                      | 1         | 0.7%    |
| Samsung SCX-4300 Series                         | 1         | 0.7%    |
| Samsung SCX-3400 Series                         | 1         | 0.7%    |
| Samsung SCX-3200 Series                         | 1         | 0.7%    |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.7%    |
| Samsung M267x 287x Series                       | 1         | 0.7%    |
| Ricoh SP 112                                    | 1         | 0.7%    |
| Prolific PL2305 Parallel Port                   | 1         | 0.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 15        | 44.12%  |
| Hewlett-Packard             | 8         | 23.53%  |
| Seiko Epson                 | 7         | 20.59%  |
| Acer Peripherals (now BenQ) | 2         | 5.88%   |
| Mustek Systems              | 1         | 2.94%   |
| KYE Systems (Mouse Systems) | 1         | 2.94%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 11.76%  |
| Canon CanoScan N1240U/LiDE 30                            | 3         | 8.82%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 5.88%   |
| HP Scanjet 300                                           | 2         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 5.88%   |
| Canon CanoScan N650U/N656U                               | 2         | 5.88%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 5.88%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 2.94%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 2.94%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 2.94%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 2.94%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 2.94%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 2.94%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 2.94%   |
| HP Scanjet N6010                                         | 1         | 2.94%   |
| HP ScanJet 5200c                                         | 1         | 2.94%   |
| HP ScanJet 4570c                                         | 1         | 2.94%   |
| HP ScanJet 4300c                                         | 1         | 2.94%   |
| HP ScanJet 3570c                                         | 1         | 2.94%   |
| HP ScanJet 3300c                                         | 1         | 2.94%   |
| Canon CanoScan LiDE 700F                                 | 1         | 2.94%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 2.94%   |
| Canon CanoScan LIDE 25                                   | 1         | 2.94%   |
| Canon CanoScan LiDE 220                                  | 1         | 2.94%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 708       | 22.15%  |
| IMC Networks                           | 354       | 11.08%  |
| Microdia                               | 216       | 6.76%   |
| Bison Electronics                      | 209       | 6.54%   |
| Realtek Semiconductor                  | 193       | 6.04%   |
| Logitech                               | 154       | 4.82%   |
| Quanta                                 | 152       | 4.76%   |
| Sunplus Innovation Technology          | 140       | 4.38%   |
| Suyin                                  | 129       | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 109       | 3.41%   |
| Apple                                  | 98        | 3.07%   |
| Acer                                   | 89        | 2.78%   |
| Syntek                                 | 85        | 2.66%   |
| Alcor Micro                            | 56        | 1.75%   |
| Luxvisions Innotech Limited            | 49        | 1.53%   |
| Lite-On Technology                     | 48        | 1.5%    |
| Ricoh                                  | 34        | 1.06%   |
| Silicon Motion                         | 25        | 0.78%   |
| Samsung Electronics                    | 24        | 0.75%   |
| Sonix Technology                       | 21        | 0.66%   |
| Creative Technology                    | 20        | 0.63%   |
| Z-Star Microelectronics                | 17        | 0.53%   |
| Microsoft                              | 17        | 0.53%   |
| Generalplus Technology                 | 14        | 0.44%   |
| GEMBIRD                                | 14        | 0.44%   |
| icSpring                               | 12        | 0.38%   |
| Lenovo                                 | 11        | 0.34%   |
| Importek                               | 10        | 0.31%   |
| ARC International                      | 10        | 0.31%   |
| ALi                                    | 10        | 0.31%   |
| SunplusIT                              | 9         | 0.28%   |
| Sunplus Technology                     | 9         | 0.28%   |
| KYE Systems (Mouse Systems)            | 9         | 0.28%   |
| webcamvendor                           | 8         | 0.25%   |
| Trust                                  | 8         | 0.25%   |
| Cubeternet                             | 8         | 0.25%   |
| Jieli Technology                       | 7         | 0.22%   |
| Intel                                  | 7         | 0.22%   |
| Genesys Logic                          | 7         | 0.22%   |
| DigiTech                               | 7         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 98        | 3.04%   |
| Chicony Integrated Camera                           | 81        | 2.52%   |
| Microdia Integrated_Webcam_HD                       | 74        | 2.3%    |
| Chicony HD Webcam                                   | 72        | 2.24%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 71        | 2.2%    |
| IMC Networks Integrated Camera                      | 63        | 1.96%   |
| Bison HD Webcam                                     | 63        | 1.96%   |
| Bison Integrated Camera                             | 53        | 1.65%   |
| Chicony USB2.0 VGA UVC WebCam                       | 44        | 1.37%   |
| Apple Built-in iSight                               | 40        | 1.24%   |
| Realtek Integrated_Webcam_HD                        | 36        | 1.12%   |
| Logitech Webcam C270                                | 36        | 1.12%   |
| Sunplus HD WebCam                                   | 35        | 1.09%   |
| Syntek Integrated Camera                            | 34        | 1.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 34        | 1.06%   |
| Microdia Webcam Vitade AF                           | 34        | 1.06%   |
| Quanta HP TrueVision HD Camera                      | 33        | 1.02%   |
| Realtek USB Camera                                  | 30        | 0.93%   |
| Chicony EasyCamera                                  | 30        | 0.93%   |
| Chicony USB 2.0 Camera                              | 28        | 0.87%   |
| Apple FaceTime HD Camera (Built-in)                 | 26        | 0.81%   |
| Logitech HD Pro Webcam C920                         | 25        | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)             | 24        | 0.75%   |
| Chicony USB2.0 Camera                               | 23        | 0.71%   |
| Chicony HP Truevision HD camera                     | 23        | 0.71%   |
| Sunplus Integrated_Webcam_HD                        | 22        | 0.68%   |
| Microdia USB 2.0 Camera                             | 22        | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                        | 22        | 0.68%   |
| Syntek EasyCamera                                   | 20        | 0.62%   |
| IMC Networks ov9734_azurewave_camera                | 20        | 0.62%   |
| Chicony HP Truevision HD                            | 20        | 0.62%   |
| Quanta HP Wide Vision HD Camera                     | 19        | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 19        | 0.59%   |
| Lite-On Integrated Camera                           | 19        | 0.59%   |
| Acer HD Camera                                      | 19        | 0.59%   |
| Syntek Lenovo EasyCamera                            | 18        | 0.56%   |
| Realtek Lenovo EasyCamera                           | 18        | 0.56%   |
| Chicony VGA Webcam                                  | 18        | 0.56%   |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.56%   |
| Chicony HP HD Camera                                | 18        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 142       | 30.87%  |
| Validity Sensors                   | 103       | 22.39%  |
| Shenzhen Goodix Technology         | 83        | 18.04%  |
| Elan Microelectronics              | 42        | 9.13%   |
| AuthenTec                          | 41        | 8.91%   |
| Upek                               | 27        | 5.87%   |
| LighTuning Technology              | 14        | 3.04%   |
| STMicroelectronics                 | 7         | 1.52%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 61        | 13.26%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 39        | 8.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 36        | 7.83%   |
| Elan ELAN:Fingerprint                                                      | 34        | 7.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 4.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 4.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 16        | 3.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 2.83%   |
| Synaptics  WBDI                                                            | 12        | 2.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.39%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.96%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.74%   |
| AuthenTec AES1600                                                          | 8         | 1.74%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.52%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.52%   |
| Validity Sensors VFS491                                                    | 6         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.3%    |
| Synaptics WBDI                                                             | 6         | 1.3%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.3%    |
| Elan ELAN:ARM-M4                                                           | 6         | 1.3%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 6         | 1.3%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.09%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.09%   |
| AuthenTec AES2810                                                          | 5         | 1.09%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.87%   |
| Synaptics UWP WBDI                                                         | 4         | 0.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.87%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.87%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.65%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 80        | 35.24%  |
| Broadcom                  | 59        | 25.99%  |
| O2 Micro                  | 25        | 11.01%  |
| Lenovo                    | 10        | 4.41%   |
| Advanced Card Systems     | 8         | 3.52%   |
| Cherry                    | 7         | 3.08%   |
| Realtek Semiconductor     | 6         | 2.64%   |
| Chicony Electronics       | 6         | 2.64%   |
| C3PO                      | 6         | 2.64%   |
| Upek                      | 5         | 2.2%    |
| SCM Microsystems          | 4         | 1.76%   |
| Gemalto (was Gemplus)     | 4         | 1.76%   |
| OmniKey                   | 2         | 0.88%   |
| Hewlett-Packard           | 2         | 0.88%   |
| In Focus Systems          | 1         | 0.44%   |
| Fujitsu Siemens Computers | 1         | 0.44%   |
| Bit4id                    | 1         | 0.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 75        | 33.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 10.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 8.81%   |
| Broadcom 5880                                                                | 17        | 7.49%   |
| Broadcom 58200                                                               | 11        | 4.85%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 4.41%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 2.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 2.64%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 2.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 2.2%    |
| C3PO LTC31v2                                                                 | 5         | 2.2%    |
| Alcor Micro Watchdata W 1981                                                 | 5         | 2.2%    |
| Cherry SmartTerminal XX1X                                                    | 4         | 1.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.32%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 1.32%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.88%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.88%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 0.88%   |
| SCM Microsystems SCR35xx USB Smart Card Reader                               | 1         | 0.44%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.44%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.44%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.44%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.44%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.44%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.44%   |
| Bit4id miniLector-s                                                          | 1         | 0.44%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.44%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4072      | 72.17%  |
| 1     | 1225      | 21.71%  |
| 2     | 279       | 4.95%   |
| 3     | 43        | 0.76%   |
| 4     | 10        | 0.18%   |
| 5     | 8         | 0.14%   |
| 6     | 3         | 0.05%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 512       | 26.67%  |
| Fingerprint reader       | 450       | 23.44%  |
| Net/wireless             | 278       | 14.48%  |
| Chipcard                 | 185       | 9.64%   |
| Multimedia controller    | 122       | 6.35%   |
| Camera                   | 66        | 3.44%   |
| Communication controller | 56        | 2.92%   |
| Bluetooth                | 53        | 2.76%   |
| Unassigned class         | 39        | 2.03%   |
| Storage                  | 31        | 1.61%   |
| Sound                    | 30        | 1.56%   |
| Card reader              | 25        | 1.3%    |
| Network                  | 17        | 0.89%   |
| Net/ethernet             | 17        | 0.89%   |
| Flash memory             | 11        | 0.57%   |
| Modem                    | 10        | 0.52%   |
| Dvb card                 | 7         | 0.36%   |
| Storage/raid             | 4         | 0.21%   |
| Firewire controller      | 4         | 0.21%   |
| Tv card                  | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ide              | 1         | 0.05%   |

