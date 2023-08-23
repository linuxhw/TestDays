Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 4483

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 8643 SMVB                   | Desktop     | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | Desktop     | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| System76      | Darter Pro                  | Notebook    | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | Desktop     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| Alienware     | 14                          | Notebook    | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Dell          | Inspiron 5482               | Convertible | [7e2aa092cf](https://linux-hardware.org/?probe=7e2aa092cf) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | Notebook    | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | Notebook    | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| Dell          | Inspiron 5482               | Convertible | [9c910c0949](https://linux-hardware.org/?probe=9c910c0949) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Notebook      | 1745                        | Notebook    | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | Notebook    | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a45c9f834](https://linux-hardware.org/?probe=9a45c9f834) | Aug 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3cfd827251](https://linux-hardware.org/?probe=3cfd827251) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | Notebook    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | Notebook    | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| JHZD          | X830                        | Desktop     | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [542578b4cf](https://linux-hardware.org/?probe=542578b4cf) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 8309                        | Desktop     | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [1e13eec6e4](https://linux-hardware.org/?probe=1e13eec6e4) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | K95VM                       | Notebook    | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| System76      | Darter Pro                  | Notebook    | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | 3646h                       | Desktop     | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [fba35d8a25](https://linux-hardware.org/?probe=fba35d8a25) | Jul 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | Notebook    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | Desktop     | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [65b9117b13](https://linux-hardware.org/?probe=65b9117b13) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Dell          | 0YXG0N A00                  | Desktop     | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | Notebook    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [c78a2441ee](https://linux-hardware.org/?probe=c78a2441ee) | Jul 23, 2023 |
| Dell          | Latitude 3500               | Notebook    | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| HP            | 829A                        | Mini pc     | [f768f29747](https://linux-hardware.org/?probe=f768f29747) | Jul 22, 2023 |
| Dell          | Latitude 5410               | Notebook    | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Intel         | X99H                        | Desktop     | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | Notebook    | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | Notebook    | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | Notebook    | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [9a9670d446](https://linux-hardware.org/?probe=9a9670d446) | Jul 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [37a65534a3](https://linux-hardware.org/?probe=37a65534a3) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | Notebook    | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | Notebook    | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | Notebook    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | Notebook    | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [71e33b92ad](https://linux-hardware.org/?probe=71e33b92ad) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | Notebook    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [4be00d26b2](https://linux-hardware.org/?probe=4be00d26b2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | 0B40h                       | Desktop     | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [080a9244cf](https://linux-hardware.org/?probe=080a9244cf) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | 0AA8h                       | Desktop     | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2239b2744d](https://linux-hardware.org/?probe=2239b2744d) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | Desktop     | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | Notebook    | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4e0acb57f9](https://linux-hardware.org/?probe=4e0acb57f9) | Jul 07, 2023 |
| HP            | 8918                        | Desktop     | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [cae21c5121](https://linux-hardware.org/?probe=cae21c5121) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | Notebook    | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | Notebook    | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [b5157e26b1](https://linux-hardware.org/?probe=b5157e26b1) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5ddd2d6cf0](https://linux-hardware.org/?probe=5ddd2d6cf0) | Jul 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Unknown       | 1.31                        | Desktop     | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | Notebook    | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [1c527ab64f](https://linux-hardware.org/?probe=1c527ab64f) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [baec2d3618](https://linux-hardware.org/?probe=baec2d3618) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | Notebook    | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [446ce08df0](https://linux-hardware.org/?probe=446ce08df0) | Jun 30, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | Notebook    | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| HP            | Notebook                    | Notebook    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [70954bb61e](https://linux-hardware.org/?probe=70954bb61e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | Notebook    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [1b2f8eb529](https://linux-hardware.org/?probe=1b2f8eb529) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Intel         | H55                         | Desktop     | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| HP            | 829A                        | Mini pc     | [0ca8c646bb](https://linux-hardware.org/?probe=0ca8c646bb) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | Notebook    | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HP            | 8949 11                     | Desktop     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | Desktop     | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Dell          | Inspiron 5481               | Convertible | [4e24ca3b12](https://linux-hardware.org/?probe=4e24ca3b12) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | Notebook    | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [c7c537bd79](https://linux-hardware.org/?probe=c7c537bd79) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [42e6a44062](https://linux-hardware.org/?probe=42e6a44062) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | Notebook    | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [384ee8b42e](https://linux-hardware.org/?probe=384ee8b42e) | Jun 13, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [ad75eab286](https://linux-hardware.org/?probe=ad75eab286) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [e2cd0602f8](https://linux-hardware.org/?probe=e2cd0602f8) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [fd51db661f](https://linux-hardware.org/?probe=fd51db661f) | Jun 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| HP            | 8949 11                     | Desktop     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1256480fca](https://linux-hardware.org/?probe=1256480fca) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | Desktop     | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | Desktop     | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e127b4c2f4](https://linux-hardware.org/?probe=e127b4c2f4) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [4d60f57084](https://linux-hardware.org/?probe=4d60f57084) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [5a2d788a64](https://linux-hardware.org/?probe=5a2d788a64) | Jun 05, 2023 |
| HP            | 8949 11                     | Desktop     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | Desktop     | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | Desktop     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2354c37832](https://linux-hardware.org/?probe=2354c37832) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | Desktop     | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | Notebook    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4f41d4f16f](https://linux-hardware.org/?probe=4f41d4f16f) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9144d0218a](https://linux-hardware.org/?probe=9144d0218a) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | 0NM64V A01                  | Desktop     | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | Notebook    | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | Notebook    | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | Desktop     | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | Notebook    | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [f339d13a59](https://linux-hardware.org/?probe=f339d13a59) | May 24, 2023 |
| HP            | 212A                        | Desktop     | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Unknown       | V00                         | Mini pc     | [7b8747aad5](https://linux-hardware.org/?probe=7b8747aad5) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | Notebook    | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Reliance C... | R141TL5                     | Notebook    | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | Desktop     | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | Notebook    | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Google        | Blorb                       | Notebook    | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| MSI           | H61M-P23                    | Desktop     | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | Notebook    | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| System76      | Galago Pro                  | Notebook    | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | Notebook    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| HP            | 158A                        | Desktop     | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | Desktop     | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96310a4cfe](https://linux-hardware.org/?probe=96310a4cfe) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ed6a0c4e82](https://linux-hardware.org/?probe=ed6a0c4e82) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [30036be67b](https://linux-hardware.org/?probe=30036be67b) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [8ba2d54929](https://linux-hardware.org/?probe=8ba2d54929) | May 10, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [6d6dffc4fe](https://linux-hardware.org/?probe=6d6dffc4fe) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | Notebook    | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | Notebook    | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [95dbf74d72](https://linux-hardware.org/?probe=95dbf74d72) | May 08, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | Notebook    | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | Desktop     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | Notebook    | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | Notebook    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [7c3b61fab9](https://linux-hardware.org/?probe=7c3b61fab9) | May 05, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [f28f7150ba](https://linux-hardware.org/?probe=f28f7150ba) | May 05, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | Notebook    | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [7b9a0196b1](https://linux-hardware.org/?probe=7b9a0196b1) | May 05, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [7fd9fd4619](https://linux-hardware.org/?probe=7fd9fd4619) | May 04, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [040ab09ebe](https://linux-hardware.org/?probe=040ab09ebe) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [95f75e1344](https://linux-hardware.org/?probe=95f75e1344) | May 04, 2023 |
| Dell          | Latitude 7370               | Notebook    | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | Notebook    | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [46abb3e5c7](https://linux-hardware.org/?probe=46abb3e5c7) | May 03, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [691239a442](https://linux-hardware.org/?probe=691239a442) | May 03, 2023 |
| HP            | Unknown                     | Notebook    | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | Notebook    | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| System76      | Oryx Pro                    | Notebook    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | Notebook    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | Notebook    | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [37ba71ddb4](https://linux-hardware.org/?probe=37ba71ddb4) | May 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [b61c6e5277](https://linux-hardware.org/?probe=b61c6e5277) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | Notebook    | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dc16d81ba0](https://linux-hardware.org/?probe=dc16d81ba0) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [80671ff25c](https://linux-hardware.org/?probe=80671ff25c) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [998427cdcf](https://linux-hardware.org/?probe=998427cdcf) | Apr 29, 2023 |
| HP            | 8054                        | Desktop     | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [9a9fdf0dd3](https://linux-hardware.org/?probe=9a9fdf0dd3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [323e28fded](https://linux-hardware.org/?probe=323e28fded) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | Notebook    | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| HP            | ENVY 15                     | Notebook    | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | Notebook    | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | Desktop     | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | Notebook    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Intel         | X99H                        | Desktop     | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| System76      | Gazelle                     | Notebook    | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [da35752b66](https://linux-hardware.org/?probe=da35752b66) | Apr 25, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| Alienware     | 13 R2                       | Notebook    | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| G7-2011       | X79                         | Desktop     | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Alienware     | 13 R3                       | Notebook    | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | Desktop     | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| HP            | ZBook 15                    | Notebook    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | Notebook    | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [eedaf9f548](https://linux-hardware.org/?probe=eedaf9f548) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | Notebook    | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | Notebook    | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [9feb6e0d59](https://linux-hardware.org/?probe=9feb6e0d59) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a9d18f5eaa](https://linux-hardware.org/?probe=a9d18f5eaa) | Apr 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 786       | 22.68%  |
| 6.0.12-76060006-generic  | 473       | 13.65%  |
| 5.19.0-76051900-generic  | 446       | 12.87%  |
| 5.17.5-76051705-generic  | 417       | 12.03%  |
| 6.0.6-76060006-generic   | 300       | 8.66%   |
| 5.18.10-76051810-generic | 207       | 5.97%   |
| 5.17.15-76051715-generic | 185       | 5.34%   |
| 6.2.0-76060200-generic   | 121       | 3.49%   |
| 5.16.19-76051619-generic | 121       | 3.49%   |
| 6.0.2-76060002-generic   | 91        | 2.63%   |
| 6.1.11-76060111-generic  | 90        | 2.6%    |
| 5.19.16-76051916-generic | 43        | 1.24%   |
| 6.0.3-76060003-generic   | 39        | 1.13%   |
| 6.4.6-76060406-generic   | 34        | 0.98%   |
| 6.3.7-060307-generic     | 5         | 0.14%   |
| 6.3.4-060304-generic     | 3         | 0.09%   |
| 6.1.0-1006-oem           | 3         | 0.09%   |
| 5.16.15-76051615-generic | 3         | 0.09%   |
| 6.4.0-060400-generic     | 2         | 0.06%   |
| 6.2.11-060211-generic    | 2         | 0.06%   |
| 6.1.8-060108-generic     | 2         | 0.06%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.06%   |
| 6.0.9-060009-generic     | 2         | 0.06%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.06%   |
| 5.19.12-xanmod1          | 2         | 0.06%   |
| 5.17.7-051707-generic    | 2         | 0.06%   |
| 5.17.5-051705-generic    | 2         | 0.06%   |
| 6.5.0-rc2                | 1         | 0.03%   |
| 6.4.8-x64v3-xanmod1      | 1         | 0.03%   |
| 6.4.5-x64v2-xanmod1      | 1         | 0.03%   |
| 6.4.3-060403-generic     | 1         | 0.03%   |
| 6.4.2-surface            | 1         | 0.03%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.03%   |
| 6.3.9-060309-generic     | 1         | 0.03%   |
| 6.3.8-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.8-1-liquorix-amd64   | 1         | 0.03%   |
| 6.3.5-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.4-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.2-060302-generic     | 1         | 0.03%   |
| 6.3.1-x64v1-xanmod1      | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 787       | 22.72%  |
| 6.0.12  | 474       | 13.68%  |
| 5.19.0  | 450       | 12.99%  |
| 5.17.5  | 420       | 12.12%  |
| 6.0.6   | 301       | 8.69%   |
| 5.18.10 | 207       | 5.98%   |
| 5.17.15 | 185       | 5.34%   |
| 6.2.0   | 121       | 3.49%   |
| 5.16.19 | 121       | 3.49%   |
| 6.0.2   | 94        | 2.71%   |
| 6.1.11  | 91        | 2.63%   |
| 5.19.16 | 43        | 1.24%   |
| 6.0.3   | 39        | 1.13%   |
| 6.4.6   | 34        | 0.98%   |
| 6.1.0   | 6         | 0.17%   |
| 5.15.0  | 6         | 0.17%   |
| 6.3.7   | 5         | 0.14%   |
| 6.3.4   | 4         | 0.12%   |
| 6.1.8   | 3         | 0.09%   |
| 6.0.9   | 3         | 0.09%   |
| 5.16.15 | 3         | 0.09%   |
| 6.4.0   | 2         | 0.06%   |
| 6.3.9   | 2         | 0.06%   |
| 6.3.8   | 2         | 0.06%   |
| 6.3.1   | 2         | 0.06%   |
| 6.2.9   | 2         | 0.06%   |
| 6.2.2   | 2         | 0.06%   |
| 6.2.11  | 2         | 0.06%   |
| 6.1.9   | 2         | 0.06%   |
| 6.1.12  | 2         | 0.06%   |
| 6.0.0   | 2         | 0.06%   |
| 5.19.12 | 2         | 0.06%   |
| 5.18.0  | 2         | 0.06%   |
| 5.17.7  | 2         | 0.06%   |
| 5.17.0  | 2         | 0.06%   |
| 6.5.0   | 1         | 0.03%   |
| 6.4.8   | 1         | 0.03%   |
| 6.4.5   | 1         | 0.03%   |
| 6.4.3   | 1         | 0.03%   |
| 6.4.2   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 907       | 26.65%  |
| 6.0     | 887       | 26.07%  |
| 5.17    | 601       | 17.66%  |
| 5.19    | 495       | 14.55%  |
| 5.18    | 213       | 6.26%   |
| 5.16    | 125       | 3.67%   |
| 6.1     | 108       | 3.17%   |
| 6.4     | 39        | 1.15%   |
| 6.3     | 17        | 0.5%    |
| 5.15    | 9         | 0.26%   |
| 6.5     | 1         | 0.03%   |
| 5.4     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3123      | 99.87%  |
| aarch64 | 4         | 0.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3045      | 97.04%  |
| KDE5            | 43        | 1.37%   |
| Unknown         | 19        | 0.61%   |
| X-Cinnamon      | 13        | 0.41%   |
| GNOME Flashback | 4         | 0.13%   |
| Unity           | 3         | 0.1%    |
| LXQt            | 3         | 0.1%    |
| Cinnamon        | 3         | 0.1%    |
| XFCE            | 2         | 0.06%   |
| MATE            | 2         | 0.06%   |
| i3              | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2992      | 95.04%  |
| Wayland | 137       | 4.35%   |
| Unknown | 14        | 0.44%   |
| Tty     | 5         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2360      | 74.97%  |
| GDM3    | 769       | 24.43%  |
| SDDM    | 10        | 0.32%   |
| GDM     | 7         | 0.22%   |
| LightDM | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1894      | 60.11%  |
| en_GB   | 206       | 6.54%   |
| pt_BR   | 169       | 5.36%   |
| de_DE   | 140       | 4.44%   |
| C       | 99        | 3.14%   |
| en_AU   | 69        | 2.19%   |
| it_IT   | 64        | 2.03%   |
| en_CA   | 61        | 1.94%   |
| fr_FR   | 53        | 1.68%   |
| es_ES   | 40        | 1.27%   |
| ru_RU   | 34        | 1.08%   |
| pl_PL   | 33        | 1.05%   |
| nb_NO   | 19        | 0.6%    |
| Unknown | 19        | 0.6%    |
| sv_SE   | 17        | 0.54%   |
| pt_PT   | 15        | 0.48%   |
| fi_FI   | 15        | 0.48%   |
| nl_NL   | 14        | 0.44%   |
| es_CL   | 12        | 0.38%   |
| en_IN   | 12        | 0.38%   |
| en_IE   | 12        | 0.38%   |
| es_MX   | 10        | 0.32%   |
| en_NZ   | 10        | 0.32%   |
| de_CH   | 10        | 0.32%   |
| da_DK   | 10        | 0.32%   |
| ja_JP   | 9         | 0.29%   |
| fr_CA   | 9         | 0.29%   |
| es_AR   | 9         | 0.29%   |
| de_AT   | 9         | 0.29%   |
| en_ZA   | 8         | 0.25%   |
| tr_TR   | 7         | 0.22%   |
| en_DK   | 7         | 0.22%   |
| cs_CZ   | 6         | 0.19%   |
| fr_CH   | 4         | 0.13%   |
| fr_BE   | 4         | 0.13%   |
| es_CO   | 4         | 0.13%   |
| ro_RO   | 3         | 0.1%    |
| zh_TW   | 2         | 0.06%   |
| zh_CN   | 2         | 0.06%   |
| sk_SK   | 2         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2403      | 76.36%  |
| EFI  | 744       | 23.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2964      | 94.46%  |
| Btrfs   | 94        | 3%      |
| Overlay | 66        | 2.1%    |
| Xfs     | 10        | 0.32%   |
| Zfs     | 3         | 0.1%    |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2342      | 74.4%   |
| GPT     | 757       | 24.05%  |
| MBR     | 49        | 1.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3036      | 96.78%  |
| Yes       | 101       | 3.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2821      | 89.96%  |
| Yes       | 315       | 10.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 558       | 17.84%  |
| Lenovo                  | 448       | 14.33%  |
| Dell                    | 391       | 12.5%   |
| Hewlett-Packard         | 352       | 11.26%  |
| MSI                     | 234       | 7.48%   |
| Gigabyte Technology     | 206       | 6.59%   |
| Apple                   | 165       | 5.28%   |
| Acer                    | 146       | 4.67%   |
| ASRock                  | 98        | 3.13%   |
| System76                | 71        | 2.27%   |
| Intel                   | 40        | 1.28%   |
| Toshiba                 | 34        | 1.09%   |
| Samsung Electronics     | 34        | 1.09%   |
| HUAWEI                  | 27        | 0.86%   |
| Alienware               | 22        | 0.7%    |
| Microsoft               | 19        | 0.61%   |
| Fujitsu                 | 17        | 0.54%   |
| Unknown                 | 16        | 0.51%   |
| Google                  | 15        | 0.48%   |
| Notebook                | 13        | 0.42%   |
| Sony                    | 11        | 0.35%   |
| AZW                     | 11        | 0.35%   |
| Positivo                | 10        | 0.32%   |
| BESSTAR Tech            | 10        | 0.32%   |
| Razer                   | 9         | 0.29%   |
| GPU Company             | 9         | 0.29%   |
| Timi                    | 8         | 0.26%   |
| MACHINIST               | 6         | 0.19%   |
| HONOR                   | 6         | 0.19%   |
| Framework               | 6         | 0.19%   |
| Avell High Performance  | 6         | 0.19%   |
| Supermicro              | 5         | 0.16%   |
| Pegatron                | 5         | 0.16%   |
| Foxconn                 | 5         | 0.16%   |
| TUXEDO                  | 4         | 0.13%   |
| Raspberry Pi Foundation | 4         | 0.13%   |
| PC Specialist           | 4         | 0.13%   |
| Medion                  | 4         | 0.13%   |
| Clevo                   | 4         | 0.13%   |
| Biostar                 | 4         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 23        | 0.74%   |
| ASUS All Series                | 20        | 0.64%   |
| System76 Oryx Pro              | 17        | 0.54%   |
| ASUS ROG STRIX B550-F GAMING   | 15        | 0.48%   |
| System76 Lemur Pro             | 14        | 0.45%   |
| Apple MacBookPro12,1           | 12        | 0.38%   |
| Apple MacBookAir7,2            | 12        | 0.38%   |
| System76 Gazelle               | 10        | 0.32%   |
| ASUS ROG STRIX B550-I GAMING   | 10        | 0.32%   |
| ASUS ROG STRIX B450-F GAMING   | 10        | 0.32%   |
| HP Dev One Notebook PC         | 9         | 0.29%   |
| Gigabyte X570 AORUS ELITE      | 9         | 0.29%   |
| Apple MacBookPro9,2            | 9         | 0.29%   |
| Gigabyte B450 AORUS M          | 8         | 0.26%   |
| ASUS TUF Gaming X570-PLUS      | 8         | 0.26%   |
| ASUS TUF Gaming B550-PLUS      | 8         | 0.26%   |
| Apple MacBookPro11,3           | 8         | 0.26%   |
| MSI MS-7B86                    | 7         | 0.22%   |
| Apple MacBookPro8,1            | 7         | 0.22%   |
| Apple MacBookAir6,2            | 7         | 0.22%   |
| System76 Thelio                | 6         | 0.19%   |
| System76 Galago Pro            | 6         | 0.19%   |
| MSI MS-7C91                    | 6         | 0.19%   |
| MSI MS-7C37                    | 6         | 0.19%   |
| MSI MS-7A38                    | 6         | 0.19%   |
| Lenovo IdeaPad S145-15API 81V7 | 6         | 0.19%   |
| HP Notebook                    | 6         | 0.19%   |
| Gigabyte B550M DS3H            | 6         | 0.19%   |
| Gigabyte A320M-S2H             | 6         | 0.19%   |
| Dell XPS 15 9520               | 6         | 0.19%   |
| Dell Latitude E7240            | 6         | 0.19%   |
| ASUS TUF Gaming B550M-PLUS     | 6         | 0.19%   |
| ASUS PRIME B550M-A             | 6         | 0.19%   |
| Apple MacBookPro7,1            | 6         | 0.19%   |
| Acer Aspire A515-45            | 6         | 0.19%   |
| MSI MS-7D54                    | 5         | 0.16%   |
| MSI MS-7D32                    | 5         | 0.16%   |
| MSI MS-7C02                    | 5         | 0.16%   |
| MSI MS-7A34                    | 5         | 0.16%   |
| MSI MS-7693                    | 5         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 178       | 5.69%   |
| ASUS ROG           | 154       | 4.92%   |
| Dell Inspiron      | 102       | 3.26%   |
| Lenovo IdeaPad     | 98        | 3.13%   |
| Acer Aspire        | 87        | 2.78%   |
| Dell Latitude      | 79        | 2.53%   |
| Dell XPS           | 69        | 2.21%   |
| HP Pavilion        | 60        | 1.92%   |
| ASUS TUF           | 55        | 1.76%   |
| ASUS PRIME         | 54        | 1.73%   |
| Dell Precision     | 50        | 1.6%    |
| HP EliteBook       | 45        | 1.44%   |
| ASUS VivoBook      | 44        | 1.41%   |
| Lenovo Legion      | 41        | 1.31%   |
| HP Laptop          | 41        | 1.31%   |
| Dell OptiPlex      | 34        | 1.09%   |
| Lenovo Yoga        | 30        | 0.96%   |
| HP ENVY            | 30        | 0.96%   |
| Toshiba Satellite  | 29        | 0.93%   |
| HP ProBook         | 28        | 0.9%    |
| ASUS ASUS          | 28        | 0.9%    |
| ASUS ZenBook       | 24        | 0.77%   |
| Lenovo ThinkCentre | 23        | 0.74%   |
| Unknown            | 23        | 0.74%   |
| Acer Swift         | 22        | 0.7%    |
| HP Compaq          | 21        | 0.67%   |
| Gigabyte X570      | 21        | 0.67%   |
| HP ZBook           | 20        | 0.64%   |
| ASUS All           | 20        | 0.64%   |
| Microsoft Surface  | 19        | 0.61%   |
| Gigabyte B450      | 19        | 0.61%   |
| Dell Vostro        | 19        | 0.61%   |
| Acer Nitro         | 19        | 0.61%   |
| HP OMEN            | 18        | 0.58%   |
| Apple MacBookPro11 | 18        | 0.58%   |
| System76 Oryx      | 17        | 0.54%   |
| System76 Lemur     | 14        | 0.45%   |
| Lenovo ThinkBook   | 13        | 0.42%   |
| HP EliteDesk       | 13        | 0.42%   |
| Gigabyte B550      | 13        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 433       | 13.85%  |
| 2020    | 407       | 13.02%  |
| 2022    | 340       | 10.87%  |
| 2018    | 308       | 9.85%   |
| 2019    | 299       | 9.56%   |
| 2013    | 180       | 5.76%   |
| 2012    | 168       | 5.37%   |
| 2017    | 164       | 5.24%   |
| 2015    | 151       | 4.83%   |
| 2016    | 143       | 4.57%   |
| 2011    | 137       | 4.38%   |
| 2014    | 134       | 4.29%   |
| 2010    | 89        | 2.85%   |
| 2009    | 76        | 2.43%   |
| 2023    | 41        | 1.31%   |
| 2008    | 34        | 1.09%   |
| 2007    | 14        | 0.45%   |
| Unknown | 6         | 0.19%   |
| 2006    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1796      | 57.44%  |
| Desktop        | 1084      | 34.67%  |
| Convertible    | 110       | 3.52%   |
| Mini pc        | 55        | 1.76%   |
| All in one     | 38        | 1.22%   |
| Tablet         | 30        | 0.96%   |
| Server         | 9         | 0.29%   |
| System on chip | 5         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3126      | 99.94%  |
| Enabled  | 2         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3065      | 98.02%  |
| Yes  | 62        | 1.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 842       | 26.64%  |
| 4.01-8.0        | 685       | 21.67%  |
| 8.01-16.0       | 562       | 17.78%  |
| 32.01-64.0      | 536       | 16.96%  |
| 3.01-4.0        | 271       | 8.57%   |
| 64.01-256.0     | 165       | 5.22%   |
| 24.01-32.0      | 79        | 2.5%    |
| 1.01-2.0        | 10        | 0.32%   |
| 2.01-3.0        | 8         | 0.25%   |
| More than 256.0 | 3         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1093      | 32.09%  |
| 2.01-3.0    | 884       | 25.95%  |
| 3.01-4.0    | 748       | 21.96%  |
| 8.01-16.0   | 325       | 9.54%   |
| 1.01-2.0    | 289       | 8.49%   |
| 16.01-24.0  | 43        | 1.26%   |
| 24.01-32.0  | 12        | 0.35%   |
| 32.01-64.0  | 7         | 0.21%   |
| 0.51-1.0    | 3         | 0.09%   |
| 64.01-256.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1834      | 57.65%  |
| 2      | 818       | 25.72%  |
| 3      | 274       | 8.61%   |
| 4      | 125       | 3.93%   |
| 5      | 65        | 2.04%   |
| 6      | 28        | 0.88%   |
| 0      | 14        | 0.44%   |
| 7      | 12        | 0.38%   |
| 9      | 3         | 0.09%   |
| 8      | 3         | 0.09%   |
| 10     | 2         | 0.06%   |
| 26     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2417      | 77.12%  |
| Yes       | 717       | 22.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2566      | 81.62%  |
| No        | 578       | 18.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2626      | 83.79%  |
| No        | 508       | 16.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2253      | 71.64%  |
| No        | 892       | 28.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 998       | 31.74%  |
| Brazil       | 238       | 7.57%   |
| Germany      | 212       | 6.74%   |
| UK           | 144       | 4.58%   |
| Canada       | 142       | 4.52%   |
| Italy        | 115       | 3.66%   |
| Australia    | 96        | 3.05%   |
| India        | 82        | 2.61%   |
| France       | 78        | 2.48%   |
| Netherlands  | 61        | 1.94%   |
| Russia       | 57        | 1.81%   |
| Poland       | 52        | 1.65%   |
| Spain        | 47        | 1.49%   |
| Sweden       | 44        | 1.4%    |
| Norway       | 42        | 1.34%   |
| Mexico       | 40        | 1.27%   |
| Portugal     | 34        | 1.08%   |
| Finland      | 34        | 1.08%   |
| Austria      | 29        | 0.92%   |
| Switzerland  | 28        | 0.89%   |
| Greece       | 26        | 0.83%   |
| Turkey       | 23        | 0.73%   |
| Chile        | 23        | 0.73%   |
| Argentina    | 23        | 0.73%   |
| Philippines  | 22        | 0.7%    |
| Denmark      | 22        | 0.7%    |
| Romania      | 21        | 0.67%   |
| New Zealand  | 21        | 0.67%   |
| Japan        | 21        | 0.67%   |
| Indonesia    | 21        | 0.67%   |
| Belgium      | 20        | 0.64%   |
| Czechia      | 19        | 0.6%    |
| Hungary      | 18        | 0.57%   |
| South Africa | 17        | 0.54%   |
| Ireland      | 16        | 0.51%   |
| Thailand     | 14        | 0.45%   |
| Serbia       | 14        | 0.45%   |
| Malaysia     | 13        | 0.41%   |
| Bulgaria     | 13        | 0.41%   |
| Slovakia     | 10        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Milan          | 23        | 0.7%    |
| Melbourne      | 23        | 0.7%    |
| Sao Paulo      | 22        | 0.67%   |
| Helsinki       | 22        | 0.67%   |
| Brisbane       | 22        | 0.67%   |
| Seattle        | 20        | 0.61%   |
| Rio de Janeiro | 20        | 0.61%   |
| Berlin         | 20        | 0.61%   |
| Vienna         | 19        | 0.58%   |
| Sydney         | 19        | 0.58%   |
| Oslo           | 18        | 0.55%   |
| Istanbul       | 16        | 0.49%   |
| Chicago        | 15        | 0.46%   |
| Moscow         | 14        | 0.43%   |
| Rome           | 13        | 0.4%    |
| Madrid         | 13        | 0.4%    |
| Lisbon         | 13        | 0.4%    |
| Bengaluru      | 13        | 0.4%    |
| Zurich         | 12        | 0.37%   |
| New York       | 12        | 0.37%   |
| Denver         | 12        | 0.37%   |
| Dallas         | 12        | 0.37%   |
| Warsaw         | 11        | 0.34%   |
| Toronto        | 11        | 0.34%   |
| San Antonio    | 11        | 0.34%   |
| Munich         | 11        | 0.34%   |
| London         | 11        | 0.34%   |
| Hamburg        | 11        | 0.34%   |
| Edmonton       | 11        | 0.34%   |
| Belgrade       | 11        | 0.34%   |
| Amsterdam      | 11        | 0.34%   |
| Portland       | 9         | 0.28%   |
| Paris          | 9         | 0.28%   |
| Dublin         | 9         | 0.28%   |
| Cleveland      | 9         | 0.28%   |
| Calgary        | 9         | 0.28%   |
| Auckland       | 9         | 0.28%   |
| St Petersburg  | 8         | 0.24%   |
| Sofia          | 8         | 0.24%   |
| Santiago       | 8         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 916       | 1327   | 19.08%  |
| WDC                         | 525       | 711    | 10.93%  |
| Seagate                     | 507       | 701    | 10.56%  |
| SanDisk                     | 366       | 468    | 7.62%   |
| Kingston                    | 249       | 295    | 5.19%   |
| Toshiba                     | 220       | 261    | 4.58%   |
| Crucial                     | 208       | 279    | 4.33%   |
| SK hynix                    | 182       | 215    | 3.79%   |
| Intel                       | 137       | 177    | 2.85%   |
| Unknown                     | 125       | 166    | 2.6%    |
| Micron Technology           | 112       | 135    | 2.33%   |
| Apple                       | 94        | 106    | 1.96%   |
| Hitachi                     | 73        | 111    | 1.52%   |
| Phison Electronics          | 68        | 93     | 1.42%   |
| Micron/Crucial Technology   | 67        | 88     | 1.4%    |
| HGST                        | 66        | 76     | 1.37%   |
| A-DATA Technology           | 66        | 74     | 1.37%   |
| Phison                      | 51        | 62     | 1.06%   |
| KIOXIA                      | 48        | 54     | 1%      |
| PNY                         | 46        | 60     | 0.96%   |
| China                       | 46        | 62     | 0.96%   |
| Silicon Motion              | 41        | 52     | 0.85%   |
| Kingston Technology Company | 38        | 42     | 0.79%   |
| SPCC                        | 27        | 36     | 0.56%   |
| Netac                       | 22        | 23     | 0.46%   |
| Unknown                     | 21        | 25     | 0.44%   |
| Intenso                     | 20        | 28     | 0.42%   |
| ADATA Technology            | 19        | 20     | 0.4%    |
| Team                        | 17        | 22     | 0.35%   |
| Realtek Semiconductor       | 16        | 16     | 0.33%   |
| Patriot                     | 16        | 19     | 0.33%   |
| LITEON                      | 15        | 18     | 0.31%   |
| LITEONIT                    | 14        | 23     | 0.29%   |
| KingSpec                    | 14        | 15     | 0.29%   |
| OCZ                         | 13        | 18     | 0.27%   |
| JMicron Technology          | 13        | 23     | 0.27%   |
| Transcend                   | 12        | 15     | 0.25%   |
| XPG                         | 11        | 13     | 0.23%   |
| Lexar                       | 11        | 14     | 0.23%   |
| Union Memory (Shenzhen)     | 9         | 11     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 115       | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 67        | 1.26%   |
| Kingston SA400S37240G 240GB SSD                     | 62        | 1.17%   |
| SanDisk NVMe SSD Drive 1TB                          | 40        | 0.75%   |
| Samsung SSD 860 EVO 1TB                             | 36        | 0.68%   |
| Samsung NVMe SSD Drive 1TB                          | 36        | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB                      | 35        | 0.66%   |
| Samsung SSD 850 EVO 250GB                           | 35        | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 34        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 34        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 33        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 32        | 0.6%    |
| Kingston SA400S37120G 120GB SSD                     | 31        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 30        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 30        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 29        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 29        | 0.55%   |
| Samsung SSD 860 EVO 500GB                           | 29        | 0.55%   |
| Samsung NVMe SSD Drive 500GB                        | 29        | 0.55%   |
| Phison E12 NVMe Controller 2TB                      | 27        | 0.51%   |
| Crucial CT240BX500SSD1 240GB                        | 27        | 0.51%   |
| Samsung SSD 980 1TB                                 | 23        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 23        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 22        | 0.41%   |
| Unknown MMC Card  64GB                              | 21        | 0.4%    |
| Toshiba MQ01ABD100 1TB                              | 21        | 0.4%    |
| Intel SSD 660P Series 1024GB                        | 21        | 0.4%    |
| Unknown                                             | 21        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 20        | 0.38%   |
| Samsung NVMe SSD Drive 2TB                          | 20        | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                     | 19        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                      | 19        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 0.36%   |
| Seagate Expansion 1TB                               | 19        | 0.36%   |
| Toshiba MQ04ABF100 1TB                              | 18        | 0.34%   |
| Samsung SSD 980 PRO 1TB                             | 18        | 0.34%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.34%   |
| Crucial CT1000BX500SSD1 1TB                         | 18        | 0.34%   |
| Apple SSD SM0128G 121GB                             | 18        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 17        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 488       | 669    | 38.67%  |
| WDC                 | 374       | 517    | 29.64%  |
| Toshiba             | 152       | 180    | 12.04%  |
| Hitachi             | 73        | 111    | 5.78%   |
| HGST                | 66        | 76     | 5.23%   |
| Samsung Electronics | 34        | 43     | 2.69%   |
| Apple               | 20        | 23     | 1.58%   |
| Unknown             | 18        | 22     | 1.43%   |
| JMicron Technology  | 10        | 18     | 0.79%   |
| Fujitsu             | 5         | 8      | 0.4%    |
| Maxtor              | 3         | 3      | 0.24%   |
| ASMT                | 3         | 4      | 0.24%   |
| SABRENT             | 2         | 3      | 0.16%   |
| PHD 3.0             | 2         | 2      | 0.16%   |
| Intenso             | 2         | 5      | 0.16%   |
| ASMedia             | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 1      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| RSH-339             | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| HGST HDN            | 1         | 1      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| Asm                 | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 365       | 512    | 23.52%  |
| Kingston            | 191       | 221    | 12.31%  |
| Crucial             | 182       | 242    | 11.73%  |
| SanDisk             | 135       | 166    | 8.7%    |
| WDC                 | 88        | 106    | 5.67%   |
| Apple               | 63        | 67     | 4.06%   |
| PNY                 | 45        | 59     | 2.9%    |
| China               | 45        | 61     | 2.9%    |
| A-DATA Technology   | 44        | 49     | 2.84%   |
| Intel               | 31        | 40     | 2%      |
| SK hynix            | 30        | 35     | 1.93%   |
| Micron Technology   | 26        | 28     | 1.68%   |
| SPCC                | 21        | 25     | 1.35%   |
| Toshiba             | 20        | 20     | 1.29%   |
| Netac               | 18        | 19     | 1.16%   |
| Patriot             | 15        | 18     | 0.97%   |
| LITEONIT            | 14        | 23     | 0.9%    |
| KingSpec            | 14        | 15     | 0.9%    |
| OCZ                 | 13        | 18     | 0.84%   |
| LITEON              | 13        | 16     | 0.84%   |
| Intenso             | 13        | 17     | 0.84%   |
| Transcend           | 11        | 14     | 0.71%   |
| Team                | 10        | 14     | 0.64%   |
| Apacer              | 8         | 12     | 0.52%   |
| Lexar               | 7         | 9      | 0.45%   |
| Hewlett-Packard     | 7         | 10     | 0.45%   |
| Seagate             | 5         | 6      | 0.32%   |
| GOODRAM             | 5         | 5      | 0.32%   |
| Mushkin             | 4         | 6      | 0.26%   |
| KingDian            | 4         | 9      | 0.26%   |
| Gigabyte Technology | 4         | 4      | 0.26%   |
| Dogfish             | 4         | 4      | 0.26%   |
| Corsair             | 4         | 5      | 0.26%   |
| Unknown             | 4         | 4      | 0.26%   |
| Verbatim            | 3         | 7      | 0.19%   |
| TO Exter            | 3         | 3      | 0.19%   |
| OWC                 | 3         | 3      | 0.19%   |
| MyDigitalSSD        | 3         | 3      | 0.19%   |
| Fanxiang            | 3         | 3      | 0.19%   |
| TrekStor            | 2         | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1640      | 2386   | 38.77%  |
| SSD     | 1339      | 1960   | 31.65%  |
| HDD     | 1063      | 1694   | 25.13%  |
| MMC     | 101       | 119    | 2.39%   |
| Unknown | 87        | 146    | 2.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1935      | 3470   | 49.82%  |
| NVMe | 1636      | 2370   | 42.12%  |
| SAS  | 212       | 346    | 5.46%   |
| MMC  | 101       | 119    | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1321      | 1904   | 51.68%  |
| 0.51-1.0   | 818       | 1122   | 32%     |
| 1.01-2.0   | 244       | 341    | 9.55%   |
| 3.01-4.0   | 71        | 105    | 2.78%   |
| 4.01-10.0  | 63        | 116    | 2.46%   |
| 2.01-3.0   | 33        | 53     | 1.29%   |
| 10.01-20.0 | 6         | 13     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 879       | 27.21%  |
| 251-500        | 803       | 24.86%  |
| 501-1000       | 695       | 21.52%  |
| 1001-2000      | 305       | 9.44%   |
| More than 3000 | 183       | 5.67%   |
| 2001-3000      | 122       | 3.78%   |
| 51-100         | 97        | 3%      |
| 1-20           | 79        | 2.45%   |
| 21-50          | 46        | 1.42%   |
| Unknown        | 21        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 954       | 28.4%   |
| 21-50          | 742       | 22.09%  |
| 101-250        | 501       | 14.92%  |
| 51-100         | 421       | 12.53%  |
| 251-500        | 324       | 9.65%   |
| 501-1000       | 187       | 5.57%   |
| 1001-2000      | 104       | 3.1%    |
| More than 3000 | 66        | 1.96%   |
| 2001-3000      | 39        | 1.16%   |
| Unknown        | 21        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 3         | 3      | 3.26%   |
| HGST HTS725050A7E630 500GB                  | 3         | 4      | 3.26%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 2         | 2      | 2.17%   |
| Seagate ST3250310AS 250GB                   | 2         | 3      | 2.17%   |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.17%   |
| Samsung Electronics SSD 850 EVO 250GB       | 2         | 2      | 2.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.09%   |
| WDC WDS100T2B0B-00YS70 1TB SSD              | 1         | 1      | 1.09%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.09%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1         | 1      | 1.09%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.09%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.09%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1         | 5      | 1.09%   |
| WDC WD15EADS-00P8B0 1TB                     | 1         | 1      | 1.09%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.09%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.09%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.09%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.09%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1         | 1      | 1.09%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.09%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.09%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.09%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.09%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.09%   |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.09%   |
| Toshiba MK1655GSX 160GB                     | 1         | 1      | 1.09%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.09%   |
| Team T253X1120G 120GB SSD                   | 1         | 1      | 1.09%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 1         | 1      | 1.09%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.09%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.09%   |
| Seagate STM3500418AS 500GB                  | 1         | 1      | 1.09%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.09%   |
| Seagate ST6000AS0002-1N917X 6TB             | 1         | 1      | 1.09%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 1.09%   |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 1.09%   |
| Seagate ST5000LM000-2AN170 5TB              | 1         | 1      | 1.09%   |
| Seagate ST4000LM024-2AN17V 4TB              | 1         | 1      | 1.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 21.35%  |
| WDC                 | 16        | 20     | 17.98%  |
| Samsung Electronics | 10        | 11     | 11.24%  |
| SK hynix            | 7         | 7      | 7.87%   |
| HGST                | 7         | 8      | 7.87%   |
| Toshiba             | 6         | 6      | 6.74%   |
| Kingston            | 3         | 4      | 3.37%   |
| Intel               | 3         | 3      | 3.37%   |
| Hitachi             | 3         | 5      | 3.37%   |
| Team                | 2         | 2      | 2.25%   |
| Micron Technology   | 2         | 4      | 2.25%   |
| Crucial             | 2         | 2      | 2.25%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| SanDisk             | 1         | 1      | 1.12%   |
| SABRENT             | 1         | 1      | 1.12%   |
| Plextor             | 1         | 1      | 1.12%   |
| Lexar               | 1         | 1      | 1.12%   |
| Leven               | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| BAITITON            | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 39.58%  |
| WDC                 | 13        | 17     | 27.08%  |
| HGST                | 7         | 8      | 14.58%  |
| Toshiba             | 4         | 4      | 8.33%   |
| Hitachi             | 3         | 5      | 6.25%   |
| Samsung Electronics | 2         | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 58     | 53.41%  |
| SSD  | 26        | 28     | 29.55%  |
| NVMe | 15        | 17     | 17.05%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB               | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| KingDian            | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2428      | 4914   | 73.33%  |
| Works    | 795       | 1284   | 24.01%  |
| Malfunc  | 85        | 103    | 2.57%   |
| Failed   | 3         | 4      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1739      | 38.61%  |
| AMD                            | 785       | 17.43%  |
| Samsung Electronics            | 635       | 14.1%   |
| SanDisk                        | 301       | 6.68%   |
| SK hynix                       | 153       | 3.4%    |
| Phison Electronics             | 125       | 2.78%   |
| Kingston Technology Company    | 95        | 2.11%   |
| Micron/Crucial Technology      | 93        | 2.06%   |
| Micron Technology              | 86        | 1.91%   |
| ASMedia Technology             | 64        | 1.42%   |
| Toshiba America Info Systems   | 53        | 1.18%   |
| Silicon Motion                 | 49        | 1.09%   |
| KIOXIA                         | 47        | 1.04%   |
| Nvidia                         | 44        | 0.98%   |
| ADATA Technology               | 43        | 0.95%   |
| Marvell Technology Group       | 33        | 0.73%   |
| Realtek Semiconductor          | 25        | 0.56%   |
| Solid State Storage Technology | 22        | 0.49%   |
| JMicron Technology             | 16        | 0.36%   |
| Union Memory (Shenzhen)        | 15        | 0.33%   |
| Apple                          | 13        | 0.29%   |
| Seagate Technology             | 10        | 0.22%   |
| Shenzhen Longsys Electronics   | 8         | 0.18%   |
| Broadcom / LSI                 | 8         | 0.18%   |
| MAXIO Technology (Hangzhou)    | 7         | 0.16%   |
| LSI Logic / Symbios Logic      | 6         | 0.13%   |
| Lite-On Technology             | 5         | 0.11%   |
| INNOGRIT                       | 5         | 0.11%   |
| VIA Technologies               | 3         | 0.07%   |
| Solidigm                       | 3         | 0.07%   |
| Netac Technology               | 3         | 0.07%   |
| Hewlett-Packard                | 3         | 0.07%   |
| Silicon Image                  | 2         | 0.04%   |
| Yangtze Memory Technologies    | 1         | 0.02%   |
| Transcend                      | 1         | 0.02%   |
| O2 Micro                       | 1         | 0.02%   |
| Biwin Storage Technology       | 1         | 0.02%   |
| Adaptec                        | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 561       | 11.26%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 277       | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 138       | 2.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 137       | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 134       | 2.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 132       | 2.65%   |
| Samsung NVMe SSD Controller 980                                                | 122       | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 122       | 2.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 116       | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 101       | 2.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 90        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 84        | 1.69%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 82        | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 68        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 62        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 60        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 60        | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 58        | 1.16%   |
| Phison E12 NVMe Controller                                                     | 55        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 54        | 1.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 51        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 51        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 50        | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 50        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 49        | 0.98%   |
| Intel SSD 660P Series                                                          | 49        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 45        | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 43        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 39        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 38        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 37        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 36        | 0.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 33        | 0.66%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 32        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 31        | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 31        | 0.62%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 31        | 0.62%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 30        | 0.6%    |
| Intel Tiger Lake-LP SATA Controller                                            | 30        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2214      | 50.86%  |
| NVMe | 1630      | 37.45%  |
| RAID | 313       | 7.19%   |
| IDE  | 180       | 4.14%   |
| SAS  | 15        | 0.34%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2111      | 67.51%  |
| AMD    | 1012      | 32.36%  |
| ARM    | 4         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 44        | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.21%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 37        | 1.18%   |
| AMD Ryzen 5 3600 6-Core Processor             | 37        | 1.18%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 1.12%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 34        | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 1.05%   |
| Intel 12th Gen Core i7-12700H                 | 32        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 29        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 28        | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 28        | 0.89%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 28        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 0.86%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 27        | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 27        | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 25        | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 0.8%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 25        | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 24        | 0.77%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 24        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.77%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 23        | 0.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 0.57%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 18        | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 17        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.51%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 16        | 0.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 16        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 15        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 15        | 0.48%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.48%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 15        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 665       | 21.23%  |
| Intel Core i5           | 598       | 19.09%  |
| Other                   | 393       | 12.55%  |
| AMD Ryzen 5             | 320       | 10.22%  |
| AMD Ryzen 7             | 316       | 10.09%  |
| Intel Core i3           | 146       | 4.66%   |
| AMD Ryzen 9             | 131       | 4.18%   |
| Intel Core 2 Duo        | 74        | 2.36%   |
| Intel Celeron           | 74        | 2.36%   |
| Intel Xeon              | 64        | 2.04%   |
| AMD FX                  | 38        | 1.21%   |
| AMD Ryzen 3             | 33        | 1.05%   |
| Intel Pentium           | 29        | 0.93%   |
| Intel Core i9           | 26        | 0.83%   |
| AMD Ryzen 7 PRO         | 24        | 0.77%   |
| AMD A8                  | 19        | 0.61%   |
| AMD A10                 | 17        | 0.54%   |
| AMD A6                  | 14        | 0.45%   |
| AMD Ryzen Threadripper  | 11        | 0.35%   |
| Intel Pentium Dual-Core | 10        | 0.32%   |
| Intel Core 2 Quad       | 10        | 0.32%   |
| AMD Ryzen 5 PRO         | 10        | 0.32%   |
| Intel Pentium Silver    | 8         | 0.26%   |
| AMD Athlon              | 8         | 0.26%   |
| AMD Athlon II X2        | 7         | 0.22%   |
| AMD A4                  | 7         | 0.22%   |
| Intel Pentium Gold      | 6         | 0.19%   |
| AMD Athlon II X4        | 6         | 0.19%   |
| Intel Core m5           | 5         | 0.16%   |
| Intel Atom              | 5         | 0.16%   |
| AMD Phenom II X4        | 5         | 0.16%   |
| Intel Core 2            | 4         | 0.13%   |
| AMD Ryzen 3 PRO         | 4         | 0.13%   |
| AMD Phenom II X6        | 4         | 0.13%   |
| AMD E                   | 4         | 0.13%   |
| Intel Pentium D         | 3         | 0.1%    |
| AMD Phenom              | 3         | 0.1%    |
| AMD E1                  | 3         | 0.1%    |
| AMD Athlon X4           | 3         | 0.1%    |
| AMD Athlon X2           | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1063      | 33.94%  |
| 2       | 794       | 25.35%  |
| 8       | 482       | 15.39%  |
| 6       | 466       | 14.88%  |
| 12      | 98        | 3.13%   |
| 16      | 74        | 2.36%   |
| 14      | 63        | 2.01%   |
| 10      | 46        | 1.47%   |
| 3       | 15        | 0.48%   |
| 1       | 13        | 0.42%   |
| 24      | 8         | 0.26%   |
| Unknown | 4         | 0.13%   |
| 32      | 2         | 0.06%   |
| 64      | 1         | 0.03%   |
| 40      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3107      | 99.36%  |
| 2       | 16        | 0.51%   |
| Unknown | 4         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2573      | 82.2%   |
| 1       | 553       | 17.67%  |
| Unknown | 4         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3124      | 99.9%   |
| 64-bit         | 3         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2497      | 78.67%  |
| 0x806c1    | 49        | 1.54%   |
| 0x0a50000c | 42        | 1.32%   |
| 0x806ec    | 26        | 0.82%   |
| 0x906a3    | 24        | 0.76%   |
| 0x806ea    | 24        | 0.76%   |
| 0x806d1    | 24        | 0.76%   |
| 0x08701021 | 24        | 0.76%   |
| 0x08600106 | 23        | 0.72%   |
| 0x306a9    | 22        | 0.69%   |
| 0x906ea    | 21        | 0.66%   |
| 0xa0652    | 20        | 0.63%   |
| 0x08608103 | 20        | 0.63%   |
| 0x0a404101 | 16        | 0.5%    |
| 0x08108109 | 15        | 0.47%   |
| 0x506e3    | 14        | 0.44%   |
| 0x406e3    | 14        | 0.44%   |
| 0x206a7    | 14        | 0.44%   |
| 0x0a601203 | 14        | 0.44%   |
| 0x0a404102 | 14        | 0.44%   |
| 0x0a201016 | 14        | 0.44%   |
| 0x806e9    | 13        | 0.41%   |
| 0x306c3    | 13        | 0.41%   |
| 0x0a50000d | 13        | 0.41%   |
| 0x0800820d | 13        | 0.41%   |
| 0x906a4    | 12        | 0.38%   |
| 0x40651    | 12        | 0.38%   |
| 0x906e9    | 11        | 0.35%   |
| 0x08600104 | 10        | 0.32%   |
| 0x306d4    | 9         | 0.28%   |
| 0x706e5    | 8         | 0.25%   |
| 0x1067a    | 8         | 0.25%   |
| 0x706a8    | 7         | 0.22%   |
| 0x0a20120a | 6         | 0.19%   |
| 0x906ec    | 5         | 0.16%   |
| 0x90672    | 5         | 0.16%   |
| 0x806eb    | 5         | 0.16%   |
| 0x08701013 | 5         | 0.16%   |
| 0x08600103 | 5         | 0.16%   |
| 0x08108102 | 5         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 496       | 15.83%  |
| Unknown          | 314       | 10.02%  |
| Zen 3            | 304       | 9.7%    |
| Haswell          | 274       | 8.74%   |
| Zen 2            | 196       | 6.25%   |
| SandyBridge      | 160       | 5.11%   |
| Skylake          | 157       | 5.01%   |
| IvyBridge        | 156       | 4.98%   |
| TigerLake        | 139       | 4.44%   |
| Zen+             | 134       | 4.28%   |
| CometLake        | 98        | 3.13%   |
| Broadwell        | 88        | 2.81%   |
| Penryn           | 85        | 2.71%   |
| Alderlake Hybrid | 72        | 2.3%    |
| Zen              | 66        | 2.11%   |
| Icelake          | 60        | 1.91%   |
| Westmere         | 55        | 1.75%   |
| Piledriver       | 52        | 1.66%   |
| Goldmont plus    | 37        | 1.18%   |
| K10              | 30        | 0.96%   |
| Silvermont       | 28        | 0.89%   |
| Nehalem          | 27        | 0.86%   |
| Excavator        | 22        | 0.7%    |
| Core             | 19        | 0.61%   |
| Puma             | 15        | 0.48%   |
| Steamroller      | 13        | 0.41%   |
| Goldmont         | 8         | 0.26%   |
| K10 Llano        | 6         | 0.19%   |
| Bobcat           | 5         | 0.16%   |
| K8 Hammer        | 4         | 0.13%   |
| Jaguar           | 4         | 0.13%   |
| Tremont          | 3         | 0.1%    |
| NetBurst         | 3         | 0.1%    |
| Bulldozer        | 3         | 0.1%    |
| K8 & K10 hybrid  | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1619      | 42.02%  |
| Nvidia                     | 1250      | 32.44%  |
| AMD                        | 980       | 25.43%  |
| Matrox Electronics Systems | 4         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 125       | 3.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 124       | 3.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 113       | 2.86%   |
| Intel UHD Graphics 620                                                      | 95        | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 88        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 82        | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 79        | 2%      |
| Intel Alder Lake-P Integrated Graphics Controller                           | 79        | 2%      |
| AMD Renoir                                                                  | 79        | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                            | 75        | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 64        | 1.62%   |
| AMD Lucienne                                                                | 64        | 1.62%   |
| Intel HD Graphics 620                                                       | 60        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 58        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 57        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 54        | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 52        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 52        | 1.32%   |
| AMD Rembrandt [Radeon 680M]                                                 | 52        | 1.32%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 51        | 1.29%   |
| Intel HD Graphics 5500                                                      | 51        | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 47        | 1.19%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 40        | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 40        | 1.01%   |
| Intel HD Graphics 530                                                       | 39        | 0.99%   |
| Intel HD Graphics 630                                                       | 35        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                         | 35        | 0.89%   |
| AMD Raphael                                                                 | 34        | 0.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 33        | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 33        | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 33        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 30        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 30        | 0.76%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 28        | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 27        | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 24        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 24        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 23        | 0.58%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 23        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1056      | 33.53%  |
| 1 x AMD              | 698       | 22.17%  |
| 1 x Nvidia           | 629       | 19.97%  |
| Intel + Nvidia       | 453       | 14.39%  |
| AMD + Nvidia         | 149       | 4.73%   |
| Intel + AMD          | 69        | 2.19%   |
| 2 x AMD              | 65        | 2.06%   |
| 2 x Nvidia           | 13        | 0.41%   |
| Other                | 8         | 0.25%   |
| 1 x Matrox           | 4         | 0.13%   |
| Intel + 2 x Nvidia   | 3         | 0.1%    |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + 2 x Nvidia     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2070      | 65.59%  |
| Proprietary | 1010      | 32%     |
| Unknown     | 76        | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2552      | 80.45%  |
| 7.01-8.0   | 121       | 3.81%   |
| 1.01-2.0   | 109       | 3.44%   |
| 0.01-0.5   | 108       | 3.4%    |
| 3.01-4.0   | 94        | 2.96%   |
| 5.01-6.0   | 74        | 2.33%   |
| 8.01-16.0  | 64        | 2.02%   |
| 0.51-1.0   | 27        | 0.85%   |
| 2.01-3.0   | 14        | 0.44%   |
| 16.01-24.0 | 8         | 0.25%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 426       | 11.78%  |
| Samsung Electronics     | 391       | 10.81%  |
| BOE                     | 351       | 9.71%   |
| Chimei Innolux          | 323       | 8.93%   |
| LG Display              | 276       | 7.63%   |
| Goldstar                | 238       | 6.58%   |
| Dell                    | 224       | 6.19%   |
| Apple                   | 128       | 3.54%   |
| Acer                    | 123       | 3.4%    |
| Hewlett-Packard         | 106       | 2.93%   |
| AOC                     | 95        | 2.63%   |
| Sharp                   | 86        | 2.38%   |
| ASUSTek Computer        | 79        | 2.18%   |
| Ancor Communications    | 69        | 1.91%   |
| BenQ                    | 64        | 1.77%   |
| Lenovo                  | 56        | 1.55%   |
| PANDA                   | 53        | 1.47%   |
| Philips                 | 49        | 1.36%   |
| InfoVision              | 31        | 0.86%   |
| MSI                     | 28        | 0.77%   |
| Iiyama                  | 28        | 0.77%   |
| CSO                     | 24        | 0.66%   |
| Chi Mei Optoelectronics | 22        | 0.61%   |
| ViewSonic               | 21        | 0.58%   |
| Sceptre Tech            | 18        | 0.5%    |
| Sony                    | 16        | 0.44%   |
| Gigabyte Technology     | 16        | 0.44%   |
| NEC Computers           | 15        | 0.41%   |
| Panasonic               | 14        | 0.39%   |
| Vizio                   | 12        | 0.33%   |
| Toshiba                 | 9         | 0.25%   |
| TMX                     | 9         | 0.25%   |
| Unknown                 | 8         | 0.22%   |
| Vestel Elektronik       | 7         | 0.19%   |
| HKC                     | 7         | 0.19%   |
| Insignia                | 6         | 0.17%   |
| Hitachi                 | 6         | 0.17%   |
| Eizo                    | 6         | 0.17%   |
| Pioneer                 | 5         | 0.14%   |
| LG Electronics          | 5         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 21        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch    | 20        | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch           | 17        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 17        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 15        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 14        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch   | 13        | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 11        | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch      | 10        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch      | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch  | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch     | 10        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch              | 10        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 9         | 0.24%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch      | 9         | 0.24%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch             | 9         | 0.24%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                | 9         | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch       | 8         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 8         | 0.21%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch        | 8         | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                 | 8         | 0.21%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                 | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch     | 8         | 0.21%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                  | 7         | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch       | 7         | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch   | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch  | 7         | 0.19%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch             | 7         | 0.19%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch             | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 7         | 0.19%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch    | 7         | 0.19%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch              | 7         | 0.19%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch              | 7         | 0.19%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch  | 7         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1618      | 47.19%  |
| 1366x768 (WXGA)    | 457       | 13.33%  |
| 3840x2160 (4K)     | 313       | 9.13%   |
| 2560x1440 (QHD)    | 243       | 7.09%   |
| 1920x1200 (WUXGA)  | 97        | 2.83%   |
| 1600x900 (HD+)     | 87        | 2.54%   |
| 3440x1440          | 80        | 2.33%   |
| 2560x1080          | 63        | 1.84%   |
| 2560x1600          | 61        | 1.78%   |
| 1440x900 (WXGA+)   | 57        | 1.66%   |
| 2880x1800          | 45        | 1.31%   |
| 1680x1050 (WSXGA+) | 45        | 1.31%   |
| 1280x1024 (SXGA)   | 41        | 1.2%    |
| 1280x800 (WXGA)    | 40        | 1.17%   |
| 3840x1080          | 21        | 0.61%   |
| 1360x768           | 19        | 0.55%   |
| 3840x2400          | 15        | 0.44%   |
| 1920x540           | 13        | 0.38%   |
| 2160x1440          | 11        | 0.32%   |
| 3840x1600          | 8         | 0.23%   |
| 2736x1824          | 8         | 0.23%   |
| 2256x1504          | 8         | 0.23%   |
| Unknown            | 8         | 0.23%   |
| 3200x1800 (QHD+)   | 7         | 0.2%    |
| 3072x1920          | 7         | 0.2%    |
| 1920x1280          | 6         | 0.17%   |
| 1024x768 (XGA)     | 6         | 0.17%   |
| 1600x1200          | 5         | 0.15%   |
| 3456x2160          | 4         | 0.12%   |
| 3200x2000          | 4         | 0.12%   |
| 1280x720 (HD)      | 4         | 0.12%   |
| 3840x1100          | 3         | 0.09%   |
| 3000x2000          | 3         | 0.09%   |
| 800x1280           | 2         | 0.06%   |
| 4480x1440          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 3840x1200          | 1         | 0.03%   |
| 3280x1080          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 895       | 24.71%  |
| 13      | 399       | 11.02%  |
| 27      | 339       | 9.36%   |
| 24      | 280       | 7.73%   |
| 14      | 276       | 7.62%   |
| 23      | 208       | 5.74%   |
| 17      | 169       | 4.67%   |
| 21      | 150       | 4.14%   |
| 31      | 143       | 3.95%   |
| 34      | 127       | 3.51%   |
| 12      | 61        | 1.68%   |
| 16      | 59        | 1.63%   |
| 19      | 53        | 1.46%   |
| Unknown | 53        | 1.46%   |
| 32      | 39        | 1.08%   |
| 84      | 38        | 1.05%   |
| 18      | 37        | 1.02%   |
| 22      | 34        | 0.94%   |
| 20      | 28        | 0.77%   |
| 72      | 26        | 0.72%   |
| 11      | 26        | 0.72%   |
| 48      | 21        | 0.58%   |
| 40      | 17        | 0.47%   |
| 28      | 17        | 0.47%   |
| 54      | 11        | 0.3%    |
| 37      | 11        | 0.3%    |
| 25      | 11        | 0.3%    |
| 35      | 9         | 0.25%   |
| 26      | 9         | 0.25%   |
| 29      | 8         | 0.22%   |
| 65      | 7         | 0.19%   |
| 33      | 7         | 0.19%   |
| 52      | 6         | 0.17%   |
| 49      | 6         | 0.17%   |
| 47      | 6         | 0.17%   |
| 46      | 4         | 0.11%   |
| 36      | 4         | 0.11%   |
| 74      | 3         | 0.08%   |
| 57      | 3         | 0.08%   |
| 44      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1415      | 40.08%  |
| 501-600     | 738       | 20.91%  |
| 201-300     | 302       | 8.56%   |
| 401-500     | 272       | 7.71%   |
| 601-700     | 203       | 5.75%   |
| 351-400     | 185       | 5.24%   |
| 701-800     | 172       | 4.87%   |
| 1501-2000   | 72        | 2.04%   |
| 1001-1500   | 68        | 1.93%   |
| Unknown     | 53        | 1.5%    |
| 801-900     | 42        | 1.19%   |
| 901-1000    | 5         | 0.14%   |
| 1-100       | 2         | 0.06%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2494      | 77.82%  |
| 16/10   | 401       | 12.51%  |
| 21/9    | 153       | 4.77%   |
| 5/4     | 43        | 1.34%   |
| 3/2     | 37        | 1.15%   |
| 32/9    | 25        | 0.78%   |
| Unknown | 24        | 0.75%   |
| 4/3     | 18        | 0.56%   |
| 3.40    | 3         | 0.09%   |
| 6/5     | 2         | 0.06%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.63    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 892       | 24.93%  |
| 201-250        | 521       | 14.56%  |
| 81-90          | 514       | 14.37%  |
| 301-350        | 350       | 9.78%   |
| 351-500        | 331       | 9.25%   |
| 71-80          | 162       | 4.53%   |
| 121-130        | 135       | 3.77%   |
| 151-200        | 117       | 3.27%   |
| More than 1000 | 106       | 2.96%   |
| 251-300        | 105       | 2.93%   |
| 501-1000       | 71        | 1.98%   |
| 141-150        | 59        | 1.65%   |
| 111-120        | 59        | 1.65%   |
| Unknown        | 53        | 1.48%   |
| 61-70          | 49        | 1.37%   |
| 51-60          | 29        | 0.81%   |
| 131-140        | 12        | 0.34%   |
| 91-100         | 10        | 0.28%   |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1095      | 31.72%  |
| 51-100        | 1020      | 29.55%  |
| 101-120       | 780       | 22.6%   |
| 161-240       | 301       | 8.72%   |
| More than 240 | 122       | 3.53%   |
| 1-50          | 81        | 2.35%   |
| Unknown       | 53        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2410      | 75.71%  |
| 2     | 579       | 18.19%  |
| 0     | 98        | 3.08%   |
| 3     | 88        | 2.76%   |
| 4     | 7         | 0.22%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1692      | 35.53%  |
| Intel                             | 1650      | 34.65%  |
| Qualcomm Atheros                  | 429       | 9.01%   |
| Broadcom                          | 248       | 5.21%   |
| MediaTek                          | 160       | 3.36%   |
| Broadcom Limited                  | 74        | 1.55%   |
| TP-Link                           | 49        | 1.03%   |
| Marvell Technology Group          | 38        | 0.8%    |
| ASIX Electronics                  | 38        | 0.8%    |
| Nvidia                            | 31        | 0.65%   |
| Ralink Technology                 | 29        | 0.61%   |
| Samsung Electronics               | 28        | 0.59%   |
| Ralink                            | 27        | 0.57%   |
| NetGear                           | 22        | 0.46%   |
| Xiaomi                            | 19        | 0.4%    |
| DisplayLink                       | 18        | 0.38%   |
| Dell                              | 13        | 0.27%   |
| Aquantia                          | 13        | 0.27%   |
| Microsoft                         | 12        | 0.25%   |
| Qualcomm                          | 11        | 0.23%   |
| Lenovo                            | 11        | 0.23%   |
| InterBiometrics                   | 11        | 0.23%   |
| Google                            | 11        | 0.23%   |
| Sierra Wireless                   | 10        | 0.21%   |
| D-Link                            | 9         | 0.19%   |
| Linksys                           | 8         | 0.17%   |
| ASUSTek Computer                  | 8         | 0.17%   |
| Qualcomm Atheros Communications   | 7         | 0.15%   |
| OPPO Electronics                  | 7         | 0.15%   |
| JMicron Technology                | 7         | 0.15%   |
| D-Link System                     | 7         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.13%   |
| Huawei Technologies               | 6         | 0.13%   |
| Hewlett-Packard                   | 5         | 0.1%    |
| Ericsson Business Mobile Networks | 4         | 0.08%   |
| Motorola PCS                      | 3         | 0.06%   |
| Mellanox Technologies             | 3         | 0.06%   |
| Fibocom                           | 3         | 0.06%   |
| Edimax Technology                 | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1076      | 19.08%  |
| Intel Wi-Fi 6 AX200                                               | 253       | 4.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 166       | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 129       | 2.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115       | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 111       | 1.97%   |
| Intel Wireless 8265 / 8275                                        | 108       | 1.91%   |
| Intel Ethernet Controller I225-V                                  | 105       | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 95        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 76        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 74        | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 66        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 65        | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 61        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 60        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 60        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 59        | 1.05%   |
| Intel Wireless 7265                                               | 58        | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 56        | 0.99%   |
| Intel Wireless 7260                                               | 54        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 52        | 0.92%   |
| Intel Wireless 8260                                               | 51        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 50        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 50        | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 47        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 45        | 0.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 41        | 0.73%   |
| Intel Wireless-AC 9260                                            | 38        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 38        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 37        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 34        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 33        | 0.59%   |
| Realtek 802.11ac NIC                                              | 33        | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 33        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1348      | 48.66%  |
| Realtek Semiconductor                 | 426       | 15.38%  |
| Qualcomm Atheros                      | 340       | 12.27%  |
| Broadcom                              | 199       | 7.18%   |
| MediaTek                              | 159       | 5.74%   |
| Broadcom Limited                      | 62        | 2.24%   |
| TP-Link                               | 42        | 1.52%   |
| Ralink Technology                     | 29        | 1.05%   |
| Ralink                                | 27        | 0.97%   |
| NetGear                               | 22        | 0.79%   |
| Marvell Technology Group              | 13        | 0.47%   |
| Microsoft                             | 12        | 0.43%   |
| Dell                                  | 12        | 0.43%   |
| Sierra Wireless                       | 10        | 0.36%   |
| Qualcomm                              | 10        | 0.36%   |
| Linksys                               | 8         | 0.29%   |
| D-Link                                | 8         | 0.29%   |
| Qualcomm Atheros Communications       | 7         | 0.25%   |
| ASUSTek Computer                      | 7         | 0.25%   |
| D-Link System                         | 6         | 0.22%   |
| Hewlett-Packard                       | 3         | 0.11%   |
| Fibocom                               | 3         | 0.11%   |
| Edimax Technology                     | 3         | 0.11%   |
| Belkin Components                     | 2         | 0.07%   |
| Accton Technology                     | 2         | 0.07%   |
| ZyDAS                                 | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| Ericsson Business Mobile Networks     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| Arduino SA                            | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 253       | 9.07%   |
| Intel Wi-Fi 6 AX201                                            | 111       | 3.98%   |
| Intel Wireless 8265 / 8275                                     | 108       | 3.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 95        | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 76        | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 74        | 2.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 66        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 65        | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 61        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 60        | 2.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 60        | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 59        | 2.12%   |
| Intel Wireless 7265                                            | 58        | 2.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 56        | 2.01%   |
| Intel Wireless 7260                                            | 54        | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 52        | 1.86%   |
| Intel Wireless 8260                                            | 51        | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 50        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 50        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 47        | 1.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 45        | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 1.47%   |
| Intel Wireless-AC 9260                                         | 38        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 34        | 1.22%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 33        | 1.18%   |
| Realtek 802.11ac NIC                                           | 33        | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 33        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 29        | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 27        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 22        | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 22        | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 22        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 21        | 0.75%   |
| Intel Wireless 3165                                            | 21        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1499      | 54.69%  |
| Intel                         | 773       | 28.2%   |
| Qualcomm Atheros              | 127       | 4.63%   |
| Broadcom                      | 100       | 3.65%   |
| ASIX Electronics              | 38        | 1.39%   |
| Nvidia                        | 31        | 1.13%   |
| Marvell Technology Group      | 25        | 0.91%   |
| Xiaomi                        | 19        | 0.69%   |
| DisplayLink                   | 18        | 0.66%   |
| Samsung Electronics           | 16        | 0.58%   |
| Aquantia                      | 13        | 0.47%   |
| Broadcom Limited              | 12        | 0.44%   |
| Lenovo                        | 11        | 0.4%    |
| Google                        | 11        | 0.4%    |
| TP-Link                       | 7         | 0.26%   |
| OPPO Electronics              | 7         | 0.26%   |
| JMicron Technology            | 7         | 0.26%   |
| OnePlus Technology (Shenzhen) | 5         | 0.18%   |
| Huawei Technologies           | 5         | 0.18%   |
| Motorola PCS                  | 3         | 0.11%   |
| Mellanox Technologies         | 3         | 0.11%   |
| Apple                         | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.04%   |
| VIA Technologies              | 1         | 0.04%   |
| T & A Mobile Phones           | 1         | 0.04%   |
| Qualcomm                      | 1         | 0.04%   |
| Hewlett-Packard               | 1         | 0.04%   |
| D-Link System                 | 1         | 0.04%   |
| D-Link                        | 1         | 0.04%   |
| ASUSTek Computer              | 1         | 0.04%   |
| American Megatrends           | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1076      | 38.37%  |
| Realtek RTL8125 2.5GbE Controller                                 | 166       | 5.92%   |
| Intel I211 Gigabit Network Connection                             | 129       | 4.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 128       | 4.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 115       | 4.1%    |
| Intel Ethernet Controller I225-V                                  | 105       | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 37        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 23        | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 21        | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 20        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 17        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 17        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 12        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.39%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 10        | 0.36%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 0.32%   |
| Intel Ethernet Connection (16) I219-V                             | 9         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2629      | 50.23%  |
| Ethernet | 2558      | 48.87%  |
| Modem    | 37        | 0.71%   |
| Unknown  | 10        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2040      | 61.58%  |
| Ethernet | 1272      | 38.39%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1748      | 55.83%  |
| 1     | 1251      | 39.96%  |
| 3     | 89        | 2.84%   |
| 0     | 34        | 1.09%   |
| 4     | 7         | 0.22%   |
| 5     | 2         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2202      | 69.51%  |
| Yes  | 966       | 30.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1202      | 52.84%  |
| Realtek Semiconductor           | 215       | 9.45%   |
| Qualcomm Atheros Communications | 155       | 6.81%   |
| Apple                           | 150       | 6.59%   |
| IMC Networks                    | 98        | 4.31%   |
| Cambridge Silicon Radio         | 91        | 4%      |
| Foxconn / Hon Hai               | 83        | 3.65%   |
| Lite-On Technology              | 59        | 2.59%   |
| Broadcom                        | 49        | 2.15%   |
| MediaTek                        | 38        | 1.67%   |
| ASUSTek Computer                | 26        | 1.14%   |
| Dell                            | 14        | 0.62%   |
| Realtek                         | 13        | 0.57%   |
| Marvell Semiconductor           | 13        | 0.57%   |
| TP-Link                         | 11        | 0.48%   |
| Toshiba                         | 10        | 0.44%   |
| Hewlett-Packard                 | 8         | 0.35%   |
| Dynex                           | 6         | 0.26%   |
| Ralink                          | 4         | 0.18%   |
| Actions                         | 4         | 0.18%   |
| Opticis                         | 3         | 0.13%   |
| Micro Star International        | 3         | 0.13%   |
| Integrated System Solution      | 3         | 0.13%   |
| Foxconn International           | 3         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| Smart Modular Technologies      | 2         | 0.09%   |
| Ralink Technology               | 2         | 0.09%   |
| Fujitsu                         | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 290       | 12.74%  |
| Intel AX201 Bluetooth                               | 277       | 12.17%  |
| Intel AX200 Bluetooth                               | 239       | 10.5%   |
| Realtek Bluetooth Radio                             | 153       | 6.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 138       | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 91        | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 87        | 3.82%   |
| Intel Bluetooth Device                              | 86        | 3.78%   |
| Apple Bluetooth Host Controller                     | 61        | 2.68%   |
| Apple Bluetooth USB Host Controller                 | 59        | 2.59%   |
| Intel AX210 Bluetooth                               | 54        | 2.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 1.98%   |
| IMC Networks Wireless_Device                        | 42        | 1.84%   |
| MediaTek Wireless_Device                            | 38        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 1.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 26        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 19        | 0.83%   |
| IMC Networks Bluetooth Device                       | 18        | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 0.7%    |
| Lite-On Wireless_Device                             | 15        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.53%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.53%   |
| TP-Link UB500 Adapter                               | 11        | 0.48%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.48%   |
| Lite-On Bluetooth Device                            | 11        | 0.48%   |
| Apple Bluetooth HCI                                 | 11        | 0.48%   |
| Marvell Bluetooth and Wireless LAN Composite        | 10        | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.35%   |
| Lite-On Bluetooth Radio                             | 8         | 0.35%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.35%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2048      | 41.96%  |
| AMD                                  | 1154      | 23.64%  |
| Nvidia                               | 996       | 20.41%  |
| C-Media Electronics                  | 83        | 1.7%    |
| Logitech                             | 52        | 1.07%   |
| Kingston Technology                  | 35        | 0.72%   |
| JMTek                                | 28        | 0.57%   |
| Razer USA                            | 26        | 0.53%   |
| ASUSTek Computer                     | 25        | 0.51%   |
| Generalplus Technology               | 24        | 0.49%   |
| Creative Labs                        | 22        | 0.45%   |
| SteelSeries ApS                      | 21        | 0.43%   |
| Micro Star International             | 21        | 0.43%   |
| Focusrite-Novation                   | 21        | 0.43%   |
| GN Netcom                            | 19        | 0.39%   |
| Lenovo                               | 17        | 0.35%   |
| Texas Instruments                    | 15        | 0.31%   |
| Corsair                              | 15        | 0.31%   |
| Realtek Semiconductor                | 14        | 0.29%   |
| Creative Technology                  | 13        | 0.27%   |
| Sony                                 | 12        | 0.25%   |
| Apple                                | 11        | 0.23%   |
| Hewlett-Packard                      | 10        | 0.2%    |
| Blue Microphones                     | 10        | 0.2%    |
| Scarlett                             | 8         | 0.16%   |
| Plantronics                          | 8         | 0.16%   |
| DSEA A/S                             | 8         | 0.16%   |
| FiiO Electronics Technology          | 5         | 0.1%    |
| Astro Gaming                         | 5         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 4         | 0.08%   |
| Tenx Technology                      | 4         | 0.08%   |
| Medeli Electronics                   | 4         | 0.08%   |
| Mackie Designs                       | 4         | 0.08%   |
| M-Audio                              | 4         | 0.08%   |
| Jieli Technology                     | 4         | 0.08%   |
| Giga-Byte Technology                 | 4         | 0.08%   |
| FUXIN                                | 4         | 0.08%   |
| BEHRINGER International              | 4         | 0.08%   |
| Antlion Audio                        | 4         | 0.08%   |
| Yamaha                               | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 497       | 8.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 271       | 4.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 244       | 4.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 232       | 3.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 161       | 2.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 154       | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 143       | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 139       | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 129       | 2.19%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 115       | 1.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 111       | 1.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 104       | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 100       | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 97        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 85        | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 81        | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 79        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 79        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 76        | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 76        | 1.29%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 76        | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 75        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 75        | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 73        | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 68        | 1.15%   |
| Nvidia Audio device                                                        | 66        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 65        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 63        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 63        | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 62        | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 61        | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 60        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 60        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 60        | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 59        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 57        | 0.97%   |
| AMD FCH Azalia Controller                                                  | 57        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 55        | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 46        | 0.78%   |
| Nvidia GA102 High Definition Audio Controller                              | 42        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 253       | 25.3%   |
| SK hynix                     | 188       | 18.8%   |
| Micron Technology            | 132       | 13.2%   |
| Kingston                     | 83        | 8.3%    |
| Corsair                      | 71        | 7.1%    |
| Crucial                      | 63        | 6.3%    |
| G.Skill                      | 46        | 4.6%    |
| Unknown                      | 25        | 2.5%    |
| Team                         | 23        | 2.3%    |
| A-DATA Technology            | 19        | 1.9%    |
| Smart                        | 13        | 1.3%    |
| Unknown                      | 12        | 1.2%    |
| Neo Forza                    | 9         | 0.9%    |
| Unknown (ABCD)               | 8         | 0.8%    |
| Goldkey                      | 7         | 0.7%    |
| Elpida                       | 7         | 0.7%    |
| Ramaxel Technology           | 6         | 0.6%    |
| PNY                          | 4         | 0.4%    |
| Nanya Technology             | 3         | 0.3%    |
| GSkill                       | 3         | 0.3%    |
| Avant                        | 3         | 0.3%    |
| Transcend                    | 2         | 0.2%    |
| Teikon                       | 2         | 0.2%    |
| Smart Brazil                 | 2         | 0.2%    |
| Gold Key                     | 2         | 0.2%    |
| Apacer                       | 2         | 0.2%    |
| Unknown (8A02)               | 1         | 0.1%    |
| Unknown (09B6)               | 1         | 0.1%    |
| Unknown (09A4)               | 1         | 0.1%    |
| Timetec                      | 1         | 0.1%    |
| Patriot Memory (PDP Systems) | 1         | 0.1%    |
| Patriot Memory               | 1         | 0.1%    |
| Patriot                      | 1         | 0.1%    |
| Kllisre                      | 1         | 0.1%    |
| GeIL                         | 1         | 0.1%    |
| CSX                          | 1         | 0.1%    |
| ChangXin Memory              | 1         | 0.1%    |
| Asgard                       | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 20        | 1.91%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 16        | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 14        | 1.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 14        | 1.34%   |
| Unknown                                                           | 12        | 1.15%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s              | 11        | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 10        | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 10        | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 8         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 8         | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 8         | 0.76%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 8         | 0.76%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s           | 8         | 0.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 8         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 7         | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 7         | 0.67%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s            | 7         | 0.67%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s          | 7         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 7         | 0.67%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                | 6         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 6         | 0.57%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s            | 6         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 6         | 0.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 6         | 0.57%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s  | 6         | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 6         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 6         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 6         | 0.57%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s             | 5         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 5         | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 5         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 5         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s              | 5         | 0.48%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 5         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 4         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 4         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 571       | 65.48%  |
| DDR3    | 130       | 14.91%  |
| DDR5    | 53        | 6.08%   |
| LPDDR4  | 51        | 5.85%   |
| LPDDR5  | 30        | 3.44%   |
| LPDDR3  | 23        | 2.64%   |
| DDR2    | 8         | 0.92%   |
| SDRAM   | 3         | 0.34%   |
| Unknown | 3         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 554       | 62.46%  |
| DIMM         | 207       | 23.34%  |
| Row Of Chips | 120       | 13.53%  |
| Chip         | 4         | 0.45%   |
| Unknown      | 2         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 421       | 44.98%  |
| 16384 | 215       | 22.97%  |
| 4096  | 186       | 19.87%  |
| 32768 | 71        | 7.59%   |
| 2048  | 39        | 4.17%   |
| 1024  | 4         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 265       | 28.4%   |
| 2667  | 159       | 17.04%  |
| 1600  | 98        | 10.5%   |
| 2400  | 55        | 5.89%   |
| 4800  | 39        | 4.18%   |
| 3600  | 39        | 4.18%   |
| 2133  | 37        | 3.97%   |
| 6400  | 32        | 3.43%   |
| 4267  | 30        | 3.22%   |
| 1867  | 14        | 1.5%    |
| 1333  | 14        | 1.5%    |
| 3733  | 13        | 1.39%   |
| 3800  | 11        | 1.18%   |
| 3266  | 9         | 0.96%   |
| 1334  | 9         | 0.96%   |
| 8400  | 8         | 0.86%   |
| 3533  | 8         | 0.86%   |
| 3000  | 8         | 0.86%   |
| 800   | 7         | 0.75%   |
| 4266  | 6         | 0.64%   |
| 2933  | 6         | 0.64%   |
| 1067  | 6         | 0.64%   |
| 6000  | 5         | 0.54%   |
| 3534  | 5         | 0.54%   |
| 3400  | 5         | 0.54%   |
| 5200  | 3         | 0.32%   |
| 3866  | 3         | 0.32%   |
| 2800  | 3         | 0.32%   |
| 2666  | 3         | 0.32%   |
| 1866  | 3         | 0.32%   |
| 5600  | 2         | 0.21%   |
| 4000  | 2         | 0.21%   |
| 3666  | 2         | 0.21%   |
| 3466  | 2         | 0.21%   |
| 3333  | 2         | 0.21%   |
| 3100  | 2         | 0.21%   |
| 2048  | 2         | 0.21%   |
| 667   | 2         | 0.21%   |
| 6800  | 1         | 0.11%   |
| 6600  | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 31.37%  |
| Canon               | 9         | 17.65%  |
| Brother Industries  | 9         | 17.65%  |
| Samsung Electronics | 6         | 11.76%  |
| Seiko Epson         | 4         | 7.84%   |
| Xerox               | 1         | 1.96%   |
| STMicroelectronics  | 1         | 1.96%   |
| QinHeng Electronics | 1         | 1.96%   |
| Prolific Technology | 1         | 1.96%   |
| ICS Advent          | 1         | 1.96%   |
| Dymo-CoStar         | 1         | 1.96%   |
| Dell                | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-2130 series                                    | 3         | 5.77%   |
| Seiko Epson WF-4830 Series                                | 2         | 3.85%   |
| HP ENVY Pro 6400 series                                   | 2         | 3.85%   |
| Canon PIXMA MX920 Series                                  | 2         | 3.85%   |
| Xerox B215                                                | 1         | 1.92%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.92%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.92%   |
| Seiko Epson ET-2800 Series                                | 1         | 1.92%   |
| Samsung SCX-4500 Laser Printer                            | 1         | 1.92%   |
| Samsung SCX-3400 Series                                   | 1         | 1.92%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.92%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 1.92%   |
| Samsung M2070 Series                                      | 1         | 1.92%   |
| Samsung M2020 Series                                      | 1         | 1.92%   |
| QinHeng CH340S                                            | 1         | 1.92%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.92%   |
| ICS Advent Parallel Adapter                               | 1         | 1.92%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.92%   |
| HP OfficeJet Pro 9010 series                              | 1         | 1.92%   |
| HP OfficeJet 3830 series                                  | 1         | 1.92%   |
| HP LaserJet Professional P1102w                           | 1         | 1.92%   |
| HP LaserJet Professional P 1102w                          | 1         | 1.92%   |
| HP LaserJet Pro M201dw                                    | 1         | 1.92%   |
| HP LaserJet P2035                                         | 1         | 1.92%   |
| HP LaserJet 3050                                          | 1         | 1.92%   |
| HP LaserJet 1010                                          | 1         | 1.92%   |
| HP Ink Tank Wireless 410 series                           | 1         | 1.92%   |
| HP Ink Tank 110 series                                    | 1         | 1.92%   |
| HP ENVY 5000 series                                       | 1         | 1.92%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.92%   |
| HP Color LaserJet CP2025dn                                | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 1.92%   |
| Dell Laser Printer 1720                                   | 1         | 1.92%   |
| Canon TS9100 series                                       | 1         | 1.92%   |
| Canon TR8500 series                                       | 1         | 1.92%   |
| Canon TR4700 series                                       | 1         | 1.92%   |
| Canon Pro9000II series                                    | 1         | 1.92%   |
| Canon PIXMA MP240                                         | 1         | 1.92%   |
| Canon PIXMA MG2500 Series                                 | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Mustek Systems  | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 11.11%  |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 11.11%  |
| HP ScanJet 82x0C                                        | 1         | 11.11%  |
| Canon CanoScan N650U/N656U                              | 1         | 11.11%  |
| Canon CanoScan LiDE 60                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |
| Canon CanoScan 9000F Mark II                            | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 385       | 18.77%  |
| IMC Networks                           | 198       | 9.65%   |
| Microdia                               | 193       | 9.41%   |
| Realtek Semiconductor                  | 145       | 7.07%   |
| Logitech                               | 129       | 6.29%   |
| Quanta                                 | 115       | 5.61%   |
| Apple                                  | 115       | 5.61%   |
| Sunplus Innovation Technology          | 101       | 4.92%   |
| Acer                                   | 99        | 4.83%   |
| Bison Electronics                      | 98        | 4.78%   |
| Luxvisions Innotech Limited            | 53        | 2.58%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 2.58%   |
| Syntek                                 | 45        | 2.19%   |
| Lite-On Technology                     | 38        | 1.85%   |
| Suyin                                  | 27        | 1.32%   |
| Microsoft                              | 25        | 1.22%   |
| Sonix Technology                       | 20        | 0.98%   |
| Silicon Motion                         | 18        | 0.88%   |
| Samsung Electronics                    | 18        | 0.88%   |
| SunplusIT                              | 13        | 0.63%   |
| Razer USA                              | 11        | 0.54%   |
| Z-Star Microelectronics                | 9         | 0.44%   |
| Generalplus Technology                 | 9         | 0.44%   |
| Creative Technology                    | 7         | 0.34%   |
| Alcor Micro                            | 7         | 0.34%   |
| Ricoh                                  | 6         | 0.29%   |
| Jieli Technology                       | 6         | 0.29%   |
| Primax Electronics                     | 5         | 0.24%   |
| MacroSilicon                           | 5         | 0.24%   |
| Lenovo                                 | 5         | 0.24%   |
| ARC International                      | 5         | 0.24%   |
| Sunplus IT                             | 4         | 0.2%    |
| LG Electronics                         | 4         | 0.2%    |
| icSpring                               | 4         | 0.2%    |
| Cubeternet                             | 4         | 0.2%    |
| AVerMedia Technologies                 | 4         | 0.2%    |
| Trust                                  | 3         | 0.15%   |
| Tobii Technology AB                    | 3         | 0.15%   |
| Importek                               | 3         | 0.15%   |
| ALi                                    | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 88        | 4.24%   |
| Microdia Integrated_Webcam_HD                       | 86        | 4.14%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 79        | 3.8%    |
| Realtek Integrated_Webcam_HD                        | 63        | 3.03%   |
| IMC Networks Integrated Camera                      | 47        | 2.26%   |
| Acer BisonCam,NB Pro                                | 38        | 1.83%   |
| Chicony HD Webcam                                   | 37        | 1.78%   |
| Syntek Integrated Camera                            | 35        | 1.69%   |
| Apple Built-in iSight                               | 34        | 1.64%   |
| Logitech Webcam C270                                | 31        | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 31        | 1.49%   |
| Chicony USB2.0 Camera                               | 29        | 1.4%    |
| Sunplus Integrated_Webcam_HD                        | 26        | 1.25%   |
| Quanta HD User Facing                               | 26        | 1.25%   |
| Apple FaceTime HD Camera (Built-in)                 | 26        | 1.25%   |
| Bison Integrated Camera                             | 22        | 1.06%   |
| Logitech HD Pro Webcam C920                         | 21        | 1.01%   |
| Chicony HP HD Camera                                | 20        | 0.96%   |
| Apple FaceTime HD Camera                            | 20        | 0.96%   |
| Acer Integrated Camera                              | 20        | 0.96%   |
| Quanta HP HD Camera                                 | 19        | 0.91%   |
| Chicony HD User Facing                              | 19        | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)             | 18        | 0.87%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.77%   |
| Sonix USB2.0 HD UVC WebCam                          | 15        | 0.72%   |
| Realtek USB Camera                                  | 15        | 0.72%   |
| Microdia Integrated Webcam                          | 15        | 0.72%   |
| Lite-On Integrated Camera                           | 15        | 0.72%   |
| Quanta HP TrueVision HD Camera                      | 14        | 0.67%   |
| Microdia Webcam Vitade AF                           | 14        | 0.67%   |
| Microdia USB 2.0 Camera                             | 14        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.67%   |
| Bison HD Webcam                                     | 14        | 0.67%   |
| Acer HD Webcam                                      | 14        | 0.67%   |
| Realtek Integrated Webcam                           | 12        | 0.58%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera            | 12        | 0.58%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.58%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 137       | 36.24%  |
| Validity Sensors                   | 96        | 25.4%   |
| Shenzhen Goodix Technology         | 72        | 19.05%  |
| Elan Microelectronics              | 23        | 6.08%   |
| LighTuning Technology              | 15        | 3.97%   |
| Upek                               | 14        | 3.7%    |
| AuthenTec                          | 8         | 2.12%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.06%   |
| Focal-systems.Corp                 | 4         | 1.06%   |
| HOLTEK                             | 3         | 0.79%   |
| Samsung Electronics                | 1         | 0.26%   |
| DigitalPersona                     | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 34        | 8.99%   |
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 8.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 6.61%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 5.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.23%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 3.7%    |
| Elan ELAN:ARM-M4                                                           | 14        | 3.7%    |
| Synaptics UWP WBDI                                                         | 13        | 3.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.91%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.38%   |
| Synaptics WBDI Device                                                      | 9         | 2.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 2.38%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.12%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.12%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.85%   |
| Synaptics  WBDI                                                            | 7         | 1.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.59%   |
| Synaptics WBDI                                                             | 6         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.59%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.32%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.32%   |
| Unknown                                                                    | 5         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.06%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 1.06%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.79%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.79%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.79%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.79%   |
| Validity Sensors VFS491                                                    | 2         | 0.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 63        | 51.22%  |
| Alcor Micro           | 39        | 31.71%  |
| O2 Micro              | 6         | 4.88%   |
| Lenovo                | 5         | 4.07%   |
| Upek                  | 4         | 3.25%   |
| OmniKey               | 2         | 1.63%   |
| SCM Microsystems      | 1         | 0.81%   |
| Gemalto (was Gemplus) | 1         | 0.81%   |
| Clay Logic            | 1         | 0.81%   |
| Advanced Card Systems | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 38        | 30.89%  |
| Broadcom 58200                                                               | 21        | 17.07%  |
| Broadcom 5880                                                                | 17        | 13.82%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 13.01%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 7.32%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.07%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.07%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.25%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.81%   |
| OmniKey CardMan 4321                                                         | 1         | 0.81%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.81%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.81%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.81%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.81%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2142      | 67.4%   |
| 1     | 841       | 26.46%  |
| 2     | 165       | 5.19%   |
| 3     | 26        | 0.82%   |
| 4     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 366       | 30%     |
| Net/wireless             | 175       | 14.34%  |
| Multimedia controller    | 174       | 14.26%  |
| Graphics card            | 170       | 13.93%  |
| Chipcard                 | 116       | 9.51%   |
| Bluetooth                | 55        | 4.51%   |
| Camera                   | 41        | 3.36%   |
| Sound                    | 25        | 2.05%   |
| Unassigned class         | 19        | 1.56%   |
| Communication controller | 18        | 1.48%   |
| Net/ethernet             | 15        | 1.23%   |
| Network                  | 12        | 0.98%   |
| Storage                  | 9         | 0.74%   |
| Card reader              | 8         | 0.66%   |
| Modem                    | 5         | 0.41%   |
| Storage/ide              | 4         | 0.33%   |
| Storage/raid             | 3         | 0.25%   |
| Storage/nvme             | 3         | 0.25%   |
| Wireless                 | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

