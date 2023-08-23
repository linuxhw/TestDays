Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 1535

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 8643 SMVB                   | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Unknown       | Unknown                     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| Gigabyte      | H410M S2 V2                 | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Unknown       | Unknown                     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| JHZD          | X830                        | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| JHZD          | X830                        | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | 07PR60 A00                  | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| HP            | 8309                        | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | 3646h                       | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Dell          | 0YXG0N A00                  | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Gigabyte      | H81M-H                      | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| MSI           | Boston                      | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| Intel         | X99H                        | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| ASUSTek       | Z97-A                       | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR            | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| MSI           | PRO Z790-A WIFI             | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| HP            | 0B40h                       | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | 0AA8h                       | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| HP            | 0AA8h                       | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| HP            | 8918                        | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| MSI           | B350 GAMING PLUS            | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Unknown       | 1.31                        | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Gigabyte      | B550 UD AC                  | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Intel         | H55                         | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| ASUSTek       | Maximus VI HERO             | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| ASUSTek       | Maximus VI HERO             | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| HP            | 8949 11                     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| Gigabyte      | B450M S2H                   | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| Dell          | 0WMJ54 A01                  | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| HP            | 8949 11                     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| HP            | 8949 11                     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| MSI           | B350M BAZOOKA               | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| MSI           | B350M PRO-VD PLUS           | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| ASUSTek       | M5A97                       | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Dell          | 0NM64V A01                  | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| ASUSTek       | Crosshair IV Formula        | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| AZW           | EQ                          | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| AZW           | EQ                          | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASRock        | X300M-STX                   | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| HP            | 212A                        | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| MSI           | B150M MORTAR                | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Gigabyte      | H61M-S2PV                   | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | 048DY8 A01                  | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| EVGA          | 151-HE-E999                 | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| HP            | 3398                        | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| MSI           | H61M-P23                    | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| Dell          | 02GDWG A00                  | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| MSI           | H110I PRO                   | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| HP            | 158A                        | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Gigabyte      | H97N-WIFI                   | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| ASUSTek       | Z170-K                      | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| ASUSTek       | M3N WS                      | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | M4A87TD EVO                 | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Gigabyte      | H310M H x.x                 | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Dell          | 02GDWG A00                  | [7b9a0196b1](https://linux-hardware.org/?probe=7b9a0196b1) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [95f75e1344](https://linux-hardware.org/?probe=95f75e1344) | May 04, 2023 |
| Gigabyte      | H410M H                     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| Dell          | 02GDWG A00                  | [46abb3e5c7](https://linux-hardware.org/?probe=46abb3e5c7) | May 03, 2023 |
| MSI           | B450M MORTAR                | [691239a442](https://linux-hardware.org/?probe=691239a442) | May 03, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| EVGA          | 151-HE-E999                 | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [37ba71ddb4](https://linux-hardware.org/?probe=37ba71ddb4) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [b61c6e5277](https://linux-hardware.org/?probe=b61c6e5277) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| HP            | 8054                        | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| MSI           | PRO X670-P WIFI             | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Intel         | X99H                        | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASRock        | Z370 Extreme4               | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| G7-2011       | X79                         | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| Dell          | 0FDY5C A00                  | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| MSI           | H110M PRO-D                 | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| ASRock        | X670E Pro RS                | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [87b5989939](https://linux-hardware.org/?probe=87b5989939) | Apr 13, 2023 |
| HP            | 8433 11                     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [3acd31b3be](https://linux-hardware.org/?probe=3acd31b3be) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [7a1d69f216](https://linux-hardware.org/?probe=7a1d69f216) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| MSI           | H81M-P33                    | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [8302310eaf](https://linux-hardware.org/?probe=8302310eaf) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [645fe56eb3](https://linux-hardware.org/?probe=645fe56eb3) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [c963121074](https://linux-hardware.org/?probe=c963121074) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Apple         | Mac-F221BEC8                | [d1f4197f52](https://linux-hardware.org/?probe=d1f4197f52) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| PS            | X570 Pro4                   | [f67323ef28](https://linux-hardware.org/?probe=f67323ef28) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Unknown       | X99-GT                      | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [29dc58335f](https://linux-hardware.org/?probe=29dc58335f) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| Dell          | 0KWVT8 A03                  | [1e66b2ab37](https://linux-hardware.org/?probe=1e66b2ab37) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Dell          | 0KWVT8 A03                  | [a700fbd33d](https://linux-hardware.org/?probe=a700fbd33d) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| HP            | 0AA4h                       | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| BESSTAR Te... | HM80                        | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| Lenovo        | 4030                        | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| HP            | 0AA4h                       | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| HP            | 8433 11                     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| HP            | 09F0h                       | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| Dell          | 0PC5F7 A01                  | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| HP            | 212B                        | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| Dell          | 0RK936                      | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Dell          | 0RK936                      | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Dell          | 02GDWG A00                  | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| ASUSTek       | Z87-K                       | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| ASRock        | B550 Extreme4               | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Gateway       | WG43M                       | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| ASRock        | FM2A68M-HD+                 | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| Gigabyte      | H110M-DS2V DDR3-CF          | [d101f34459](https://linux-hardware.org/?probe=d101f34459) | Mar 09, 2023 |
| MSI           | X58 PLATINUM SLI            | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| Dell          | 051FJ8 A02                  | [4c15877e95](https://linux-hardware.org/?probe=4c15877e95) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | [6ddf3ecd86](https://linux-hardware.org/?probe=6ddf3ecd86) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| HP            | 83E9                        | [9a756f9158](https://linux-hardware.org/?probe=9a756f9158) | Mar 07, 2023 |
| ASRock        | G41M-GS3                    | [9e11e1f2af](https://linux-hardware.org/?probe=9e11e1f2af) | Mar 07, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [bfc1bf412e](https://linux-hardware.org/?probe=bfc1bf412e) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [da3b20e7c1](https://linux-hardware.org/?probe=da3b20e7c1) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [eb3f7a337f](https://linux-hardware.org/?probe=eb3f7a337f) | Mar 05, 2023 |
| Gigabyte      | B450M GAMING                | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| HP            | 339A                        | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [efd2d0c074](https://linux-hardware.org/?probe=efd2d0c074) | Mar 05, 2023 |
| MSI           | B350 GAMING PLUS            | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| Acer          | Aspire M3970                | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [141faab02f](https://linux-hardware.org/?probe=141faab02f) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [840dab3a7c](https://linux-hardware.org/?probe=840dab3a7c) | Mar 03, 2023 |
| Biostar       | H81MHV3 5.0                 | [6ea9159a52](https://linux-hardware.org/?probe=6ea9159a52) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8ce5103cac](https://linux-hardware.org/?probe=8ce5103cac) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| ASRockRack    | X570D4U                     | [9c4b25d5dc](https://linux-hardware.org/?probe=9c4b25d5dc) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [4207bf1ee6](https://linux-hardware.org/?probe=4207bf1ee6) | Mar 02, 2023 |
| ASUSTek       | Crosshair IV Formula        | [ed4f0e394a](https://linux-hardware.org/?probe=ed4f0e394a) | Mar 02, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5b94fc8fa8](https://linux-hardware.org/?probe=5b94fc8fa8) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [6126e81a28](https://linux-hardware.org/?probe=6126e81a28) | Mar 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Dell          | 03KWTV A02                  | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| ZOTAC         | MEK1                        | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Dell          | 0M6C7G A00                  | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| ASRock        | B550 Extreme4               | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| ASRock        | H87 Performance             | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [8df8fe9ae8](https://linux-hardware.org/?probe=8df8fe9ae8) | Feb 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [b99541f6ad](https://linux-hardware.org/?probe=b99541f6ad) | Feb 19, 2023 |
| HP            | 8437                        | [f8f0f71bf5](https://linux-hardware.org/?probe=f8f0f71bf5) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c82882e708](https://linux-hardware.org/?probe=c82882e708) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [2ca590a85e](https://linux-hardware.org/?probe=2ca590a85e) | Feb 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [27c2ee6ee0](https://linux-hardware.org/?probe=27c2ee6ee0) | Feb 14, 2023 |
| Dell          | 0Y7WYT A00                  | [d94084bbee](https://linux-hardware.org/?probe=d94084bbee) | Feb 12, 2023 |
| ASRock        | B550M Steel Legend          | [2a6f501cb1](https://linux-hardware.org/?probe=2a6f501cb1) | Feb 12, 2023 |
| Dell          | 08WKV3 A00                  | [89ba42b53e](https://linux-hardware.org/?probe=89ba42b53e) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [687ecdce15](https://linux-hardware.org/?probe=687ecdce15) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2c1562b21f](https://linux-hardware.org/?probe=2c1562b21f) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | [b82ab8816d](https://linux-hardware.org/?probe=b82ab8816d) | Feb 11, 2023 |
| HP            | 18E4                        | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0b14ee6551](https://linux-hardware.org/?probe=0b14ee6551) | Feb 11, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [181c0e03e2](https://linux-hardware.org/?probe=181c0e03e2) | Feb 10, 2023 |
| Dell          | 0Y7WYT A00                  | [e4369afe1e](https://linux-hardware.org/?probe=e4369afe1e) | Feb 10, 2023 |
| ASUSTek       | A55BM-PLUS                  | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Samsung       | DeskTop System              | [2437c4afda](https://linux-hardware.org/?probe=2437c4afda) | Feb 10, 2023 |
| Biostar       | H81MHV3 5.0                 | [390c8dd03a](https://linux-hardware.org/?probe=390c8dd03a) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [17bf959fd0](https://linux-hardware.org/?probe=17bf959fd0) | Feb 09, 2023 |
| Acer          | Aspire M3970                | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [1c07b901bb](https://linux-hardware.org/?probe=1c07b901bb) | Feb 08, 2023 |
| HP            | 2129                        | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d8dcaddb54](https://linux-hardware.org/?probe=d8dcaddb54) | Feb 08, 2023 |
| ASRock        | B660 Pro-C/ax               | [31e10f0e68](https://linux-hardware.org/?probe=31e10f0e68) | Feb 07, 2023 |
| ASRock        | FM2A68M-HD+                 | [8588a36683](https://linux-hardware.org/?probe=8588a36683) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Gigabyte      | F2A55M-HD2                  | [fe95bfe3d3](https://linux-hardware.org/?probe=fe95bfe3d3) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [03a392d41f](https://linux-hardware.org/?probe=03a392d41f) | Feb 07, 2023 |
| Dell          | 02GDWG A00                  | [c0660c15fb](https://linux-hardware.org/?probe=c0660c15fb) | Feb 07, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | [25fbfe1d66](https://linux-hardware.org/?probe=25fbfe1d66) | Feb 07, 2023 |
| System76      | Thelio thelio-r2            | [4cdf7d2895](https://linux-hardware.org/?probe=4cdf7d2895) | Feb 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [42dba6bdb3](https://linux-hardware.org/?probe=42dba6bdb3) | Feb 06, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a9bfc9669d](https://linux-hardware.org/?probe=a9bfc9669d) | Feb 06, 2023 |
| ASUSTek       | H81M-K                      | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [cd9d867630](https://linux-hardware.org/?probe=cd9d867630) | Feb 04, 2023 |
| Biostar       | H81MHV3 5.0                 | [084eee2317](https://linux-hardware.org/?probe=084eee2317) | Feb 03, 2023 |
| HP            | 834F                        | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [6d4ee8a3c6](https://linux-hardware.org/?probe=6d4ee8a3c6) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ffabf45521](https://linux-hardware.org/?probe=ffabf45521) | Feb 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Intel         | H61                         | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| HP            | 1495                        | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| Acer          | Aspire M3970                | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| MSI           | B450M MORTAR MAX            | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| MSI           | H81M-E34                    | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| ASUSTek       | G10DK                       | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| ASUSTek       | P8Z77-V LK                  | [a10fc5f5a9](https://linux-hardware.org/?probe=a10fc5f5a9) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [ebc45fdfd5](https://linux-hardware.org/?probe=ebc45fdfd5) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | [0eae2f92fa](https://linux-hardware.org/?probe=0eae2f92fa) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [f908807ed9](https://linux-hardware.org/?probe=f908807ed9) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6e8f360d6e](https://linux-hardware.org/?probe=6e8f360d6e) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H AC               | [22fca13d2b](https://linux-hardware.org/?probe=22fca13d2b) | Jan 17, 2023 |
| Gigabyte      | B450M S2H                   | [2ba8d32a71](https://linux-hardware.org/?probe=2ba8d32a71) | Jan 17, 2023 |
| Gateway       | WG43M                       | [af3a009366](https://linux-hardware.org/?probe=af3a009366) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | [48cc2e0e69](https://linux-hardware.org/?probe=48cc2e0e69) | Jan 17, 2023 |
| Gateway       | WG43M                       | [b0aa3af22f](https://linux-hardware.org/?probe=b0aa3af22f) | Jan 17, 2023 |
| ASRock        | H87 Performance             | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| ASRock        | B450 Pro4                   | [2e65fc8357](https://linux-hardware.org/?probe=2e65fc8357) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ba736834cd](https://linux-hardware.org/?probe=ba736834cd) | Jan 16, 2023 |
| HC            | HCAR357-MI V1.0             | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| ASRock        | B550 Extreme4               | [01f850d2fb](https://linux-hardware.org/?probe=01f850d2fb) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [82f04ecd77](https://linux-hardware.org/?probe=82f04ecd77) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | [25db796fd6](https://linux-hardware.org/?probe=25db796fd6) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d3896698c8](https://linux-hardware.org/?probe=d3896698c8) | Jan 14, 2023 |
| ASUSTek       | G10DK                       | [a92296f2e7](https://linux-hardware.org/?probe=a92296f2e7) | Jan 14, 2023 |
| Acer          | Aspire XC-603G              | [21e24944ad](https://linux-hardware.org/?probe=21e24944ad) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| ASUSTek       | P9X79-E WS                  | [e868d6909e](https://linux-hardware.org/?probe=e868d6909e) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [1921b19009](https://linux-hardware.org/?probe=1921b19009) | Jan 13, 2023 |
| HP            | 8299                        | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| ASUSTek       | H61M-E                      | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M71e 3157W8B    | [70078ceabd](https://linux-hardware.org/?probe=70078ceabd) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [ae12526ceb](https://linux-hardware.org/?probe=ae12526ceb) | Jan 11, 2023 |
| ASUSTek       | P9X79-E WS                  | [f3b4e5135f](https://linux-hardware.org/?probe=f3b4e5135f) | Jan 10, 2023 |
| HP            | 8433 11                     | [5e26cba33b](https://linux-hardware.org/?probe=5e26cba33b) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [3982bc570e](https://linux-hardware.org/?probe=3982bc570e) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| MSI           | B350M BAZOOKA               | [e7d2bcfcfb](https://linux-hardware.org/?probe=e7d2bcfcfb) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [1b055dc79d](https://linux-hardware.org/?probe=1b055dc79d) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [0b85968e35](https://linux-hardware.org/?probe=0b85968e35) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| HP            | 2B4B                        | [57273c7b72](https://linux-hardware.org/?probe=57273c7b72) | Jan 07, 2023 |
| Dell          | 04GJJT A00                  | [85142569a6](https://linux-hardware.org/?probe=85142569a6) | Jan 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2024a8808](https://linux-hardware.org/?probe=f2024a8808) | Jan 06, 2023 |
| Acer          | Aspire M3970                | [2ef35b6d4b](https://linux-hardware.org/?probe=2ef35b6d4b) | Jan 05, 2023 |
| MSI           | B250M PRO-VD                | [0abf746107](https://linux-hardware.org/?probe=0abf746107) | Jan 05, 2023 |
| Intel         | HM570                       | [8728d2372a](https://linux-hardware.org/?probe=8728d2372a) | Jan 05, 2023 |
| AZW           | GTR V02                     | [2cf7a814cb](https://linux-hardware.org/?probe=2cf7a814cb) | Jan 05, 2023 |
| Gigabyte      | X570S AERO G                | [04ca884448](https://linux-hardware.org/?probe=04ca884448) | Jan 05, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [98fafd877d](https://linux-hardware.org/?probe=98fafd877d) | Jan 04, 2023 |
| HP            | 3047h                       | [2c75b0b4ee](https://linux-hardware.org/?probe=2c75b0b4ee) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| System76      | Thelio Mira thelio-mira-... | [78367dd37f](https://linux-hardware.org/?probe=78367dd37f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| ASRock        | B550M Steel Legend          | [e8ad216a59](https://linux-hardware.org/?probe=e8ad216a59) | Jan 02, 2023 |
| ASUSTek       | P6T                         | [e648b2523e](https://linux-hardware.org/?probe=e648b2523e) | Jan 02, 2023 |
| Acer          | Aspire XC-603G              | [b2e25a20de](https://linux-hardware.org/?probe=b2e25a20de) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Win elemen... | M600                        | [5d4320db68](https://linux-hardware.org/?probe=5d4320db68) | Jan 02, 2023 |
| MSI           | PRO B550-VC                 | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Acer          | Aspire XC-603G              | [660548d31c](https://linux-hardware.org/?probe=660548d31c) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Dell          | 0NNGP2 A00                  | [12638171d9](https://linux-hardware.org/?probe=12638171d9) | Dec 28, 2022 |
| Lenovo        | No DPK                      | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASRock        | Z790M-ITX WiFi              | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 00CV7F A00                  | [49a36278c4](https://linux-hardware.org/?probe=49a36278c4) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| HP            | 2B4B                        | [b07e2ecc23](https://linux-hardware.org/?probe=b07e2ecc23) | Dec 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1522e4a536](https://linux-hardware.org/?probe=1522e4a536) | Dec 28, 2022 |
| Acer          | Aspire XC-603G              | [e8adbb63a4](https://linux-hardware.org/?probe=e8adbb63a4) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ee1658b320](https://linux-hardware.org/?probe=ee1658b320) | Dec 27, 2022 |
| HP            | 876C SMVB                   | [7926807626](https://linux-hardware.org/?probe=7926807626) | Dec 27, 2022 |
| ASUSTek       | Z87-K                       | [9c65749eb1](https://linux-hardware.org/?probe=9c65749eb1) | Dec 27, 2022 |
| MSI           | B450M PRO-M2                | [89d9265559](https://linux-hardware.org/?probe=89d9265559) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [c49123106a](https://linux-hardware.org/?probe=c49123106a) | Dec 24, 2022 |
| Gigabyte      | MJPLNBB-00                  | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| ASUSTek       | P7P55D PRO                  | [7402ac8671](https://linux-hardware.org/?probe=7402ac8671) | Dec 22, 2022 |
| MSI           | B85M-E45                    | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 02GDWG A00                  | [d20f5b0751](https://linux-hardware.org/?probe=d20f5b0751) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| Supermicro    | X9DR3-F                     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| HP            | 18E7                        | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d179359230](https://linux-hardware.org/?probe=d179359230) | Dec 18, 2022 |
| HP            | 8433 11                     | [4368b19d60](https://linux-hardware.org/?probe=4368b19d60) | Dec 18, 2022 |
| Gigabyte      | B550 VISION D-P             | [163b883ce2](https://linux-hardware.org/?probe=163b883ce2) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [d7e869aded](https://linux-hardware.org/?probe=d7e869aded) | Dec 17, 2022 |
| Unknown       | Unknown                     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | [f12e6b75b5](https://linux-hardware.org/?probe=f12e6b75b5) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [b31e9dfa64](https://linux-hardware.org/?probe=b31e9dfa64) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | [9cff930a2e](https://linux-hardware.org/?probe=9cff930a2e) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| ASUSTek       | PRIME X570-PRO              | [af4e397bbe](https://linux-hardware.org/?probe=af4e397bbe) | Dec 16, 2022 |
| System76      | Thelio thelio-r2            | [d2065497b9](https://linux-hardware.org/?probe=d2065497b9) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [cdc6f36d8c](https://linux-hardware.org/?probe=cdc6f36d8c) | Dec 11, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | [8f45bcde64](https://linux-hardware.org/?probe=8f45bcde64) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [229065f67f](https://linux-hardware.org/?probe=229065f67f) | Dec 11, 2022 |
| MSI           | A55M-E33                    | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | [5cea05fe88](https://linux-hardware.org/?probe=5cea05fe88) | Dec 11, 2022 |
| Apple         | Mac-F221BEC8                | [55a5f34bf0](https://linux-hardware.org/?probe=55a5f34bf0) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [e8d8a922a2](https://linux-hardware.org/?probe=e8d8a922a2) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | [1b848d1587](https://linux-hardware.org/?probe=1b848d1587) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1280df2c5d](https://linux-hardware.org/?probe=1280df2c5d) | Dec 08, 2022 |
| MSI           | PRO Z790-A WIFI             | [9dfb20d74f](https://linux-hardware.org/?probe=9dfb20d74f) | Dec 08, 2022 |
| ASRock        | Z97 Extreme6                | [f000ea7b78](https://linux-hardware.org/?probe=f000ea7b78) | Dec 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [d2c01d70df](https://linux-hardware.org/?probe=d2c01d70df) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3c65af8425](https://linux-hardware.org/?probe=3c65af8425) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d66311f833](https://linux-hardware.org/?probe=d66311f833) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| MSI           | 760GM-P23                   | [df9ebcbba6](https://linux-hardware.org/?probe=df9ebcbba6) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | B350 TOMAHAWK               | [2607a15d58](https://linux-hardware.org/?probe=2607a15d58) | Dec 03, 2022 |
| ASRock        | Z370 Pro4                   | [76cd787c24](https://linux-hardware.org/?probe=76cd787c24) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | [8e317647dc](https://linux-hardware.org/?probe=8e317647dc) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [953943c231](https://linux-hardware.org/?probe=953943c231) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Unknown       | 1.0                         | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| ASRock        | H77M                        | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Acer          | Nitro N50-610               | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| ASRock        | B550M-ITX/ac                | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASRock        | H310CM-HG4                  | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| Gigabyte      | B550M DS3H                  | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Gigabyte      | 990FXA-UD3                  | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| HP            | 1998                        | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | X399 Taichi                 | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| MSI           | B85-G43                     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | 970A-G46                    | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.2.6-76060206-generic    | 291      | 24.09%  |
| 6.0.12-76060006-generic   | 174      | 14.4%   |
| 5.17.5-76051705-generic   | 158      | 13.08%  |
| 5.19.0-76051900-generic   | 143      | 11.84%  |
| 6.0.6-76060006-generic    | 102      | 8.44%   |
| 5.18.10-76051810-generic  | 72       | 5.96%   |
| 5.17.15-76051715-generic  | 66       | 5.46%   |
| 5.16.19-76051619-generic  | 40       | 3.31%   |
| 6.2.0-76060200-generic    | 37       | 3.06%   |
| 6.1.11-76060111-generic   | 28       | 2.32%   |
| 6.0.2-76060002-generic    | 27       | 2.24%   |
| 5.19.16-76051916-generic  | 18       | 1.49%   |
| 6.0.3-76060003-generic    | 14       | 1.16%   |
| 6.4.6-76060406-generic    | 10       | 0.83%   |
| 6.3.7-060307-generic      | 3        | 0.25%   |
| 6.1.0-x64v1-xanmod1       | 2        | 0.17%   |
| 6.4.8-x64v3-xanmod1       | 1        | 0.08%   |
| 6.3.4-x64v1-xanmod1       | 1        | 0.08%   |
| 6.3.4-060304-generic      | 1        | 0.08%   |
| 6.3.1-x64v1-xanmod1       | 1        | 0.08%   |
| 6.2.9-060209-generic      | 1        | 0.08%   |
| 6.2.8-060208-generic      | 1        | 0.08%   |
| 6.2.2-x64v3-xanmod1       | 1        | 0.08%   |
| 6.1.8-060108-generic      | 1        | 0.08%   |
| 6.1.13-x64v3-xanmod1      | 1        | 0.08%   |
| 6.1.12-x64v3-xanmod1      | 1        | 0.08%   |
| 6.1.0-060100rc5-generic   | 1        | 0.08%   |
| 6.0.9-060009-generic      | 1        | 0.08%   |
| 6.0.8-x64v1-xanmod1       | 1        | 0.08%   |
| 6.0.6-060006-generic      | 1        | 0.08%   |
| 6.0.2-x64v1-xanmod1       | 1        | 0.08%   |
| 6.0.12-x64v1-xanmod1      | 1        | 0.08%   |
| 5.4.210-whitehax0r        | 1        | 0.08%   |
| 5.19.6-xanmod1-x64v2      | 1        | 0.08%   |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.08%   |
| 5.17.4-051704-generic     | 1        | 0.08%   |
| 5.17.14-xanmod1           | 1        | 0.08%   |
| 5.16.15-76051615-generic  | 1        | 0.08%   |
| 5.15.15-76051515-generic  | 1        | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.6   | 291      | 24.09%  |
| 6.0.12  | 175      | 14.49%  |
| 5.17.5  | 158      | 13.08%  |
| 5.19.0  | 143      | 11.84%  |
| 6.0.6   | 103      | 8.53%   |
| 5.18.10 | 72       | 5.96%   |
| 5.17.15 | 66       | 5.46%   |
| 5.16.19 | 40       | 3.31%   |
| 6.2.0   | 37       | 3.06%   |
| 6.1.11  | 28       | 2.32%   |
| 6.0.2   | 28       | 2.32%   |
| 5.19.16 | 18       | 1.49%   |
| 6.0.3   | 14       | 1.16%   |
| 6.4.6   | 10       | 0.83%   |
| 6.3.7   | 3        | 0.25%   |
| 6.1.0   | 3        | 0.25%   |
| 6.3.4   | 2        | 0.17%   |
| 6.4.8   | 1        | 0.08%   |
| 6.3.1   | 1        | 0.08%   |
| 6.2.9   | 1        | 0.08%   |
| 6.2.8   | 1        | 0.08%   |
| 6.2.2   | 1        | 0.08%   |
| 6.1.8   | 1        | 0.08%   |
| 6.1.13  | 1        | 0.08%   |
| 6.1.12  | 1        | 0.08%   |
| 6.0.9   | 1        | 0.08%   |
| 6.0.8   | 1        | 0.08%   |
| 5.4.210 | 1        | 0.08%   |
| 5.19.6  | 1        | 0.08%   |
| 5.18.0  | 1        | 0.08%   |
| 5.17.4  | 1        | 0.08%   |
| 5.17.14 | 1        | 0.08%   |
| 5.16.15 | 1        | 0.08%   |
| 5.15.15 | 1        | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 325      | 27.38%  |
| 6.0     | 315      | 26.54%  |
| 5.17    | 219      | 18.45%  |
| 5.19    | 161      | 13.56%  |
| 5.18    | 73       | 6.15%   |
| 5.16    | 41       | 3.45%   |
| 6.1     | 34       | 2.86%   |
| 6.4     | 11       | 0.93%   |
| 6.3     | 6        | 0.51%   |
| 5.4     | 1        | 0.08%   |
| 5.15    | 1        | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1084     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 1045     | 95.87%  |
| KDE5            | 26       | 2.39%   |
| X-Cinnamon      | 8        | 0.73%   |
| Unknown         | 4        | 0.37%   |
| LXQt            | 2        | 0.18%   |
| GNOME Flashback | 2        | 0.18%   |
| XFCE            | 1        | 0.09%   |
| i3              | 1        | 0.09%   |
| Cinnamon        | 1        | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1059     | 97.25%  |
| Wayland | 27       | 2.48%   |
| Unknown | 2        | 0.18%   |
| Tty     | 1        | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 896      | 82.43%  |
| GDM3    | 180      | 16.56%  |
| SDDM    | 7        | 0.64%   |
| GDM     | 3        | 0.28%   |
| LightDM | 1        | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 653      | 59.63%  |
| en_GB   | 70       | 6.39%   |
| pt_BR   | 61       | 5.57%   |
| de_DE   | 58       | 5.3%    |
| C       | 43       | 3.93%   |
| en_CA   | 30       | 2.74%   |
| fr_FR   | 23       | 2.1%    |
| en_AU   | 23       | 2.1%    |
| it_IT   | 16       | 1.46%   |
| pl_PL   | 12       | 1.1%    |
| es_ES   | 9        | 0.82%   |
| ru_RU   | 8        | 0.73%   |
| es_CL   | 7        | 0.64%   |
| sv_SE   | 6        | 0.55%   |
| fi_FI   | 6        | 0.55%   |
| da_DK   | 6        | 0.55%   |
| ja_JP   | 5        | 0.46%   |
| de_AT   | 5        | 0.46%   |
| Unknown | 5        | 0.46%   |
| pt_PT   | 4        | 0.37%   |
| nl_NL   | 4        | 0.37%   |
| nb_NO   | 4        | 0.37%   |
| en_DK   | 4        | 0.37%   |
| es_AR   | 3        | 0.27%   |
| en_IN   | 3        | 0.27%   |
| zh_TW   | 2        | 0.18%   |
| ro_RO   | 2        | 0.18%   |
| nl_BE   | 2        | 0.18%   |
| fr_CH   | 2        | 0.18%   |
| fr_CA   | 2        | 0.18%   |
| fr_BE   | 2        | 0.18%   |
| en_ZA   | 2        | 0.18%   |
| cs_CZ   | 2        | 0.18%   |
| sk_SK   | 1        | 0.09%   |
| hu_HU   | 1        | 0.09%   |
| et_EE   | 1        | 0.09%   |
| es_UY   | 1        | 0.09%   |
| es_DO   | 1        | 0.09%   |
| en_ZW   | 1        | 0.09%   |
| en_IL   | 1        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 920      | 84.64%  |
| EFI  | 167      | 15.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1031     | 94.85%  |
| Overlay | 28       | 2.58%   |
| Btrfs   | 23       | 2.12%   |
| Xfs     | 3        | 0.28%   |
| Zfs     | 1        | 0.09%   |
| Unknown | 1        | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 893      | 82.15%  |
| GPT     | 178      | 16.38%  |
| MBR     | 16       | 1.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1041     | 95.68%  |
| Yes       | 47       | 4.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 968      | 89.13%  |
| Yes       | 118      | 10.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 320      | 29.52%  |
| Gigabyte Technology                  | 197      | 18.17%  |
| MSI                                  | 169      | 15.59%  |
| ASRock                               | 96       | 8.86%   |
| Dell                                 | 72       | 6.64%   |
| Hewlett-Packard                      | 58       | 5.35%   |
| Lenovo                               | 34       | 3.14%   |
| Intel                                | 19       | 1.75%   |
| System76                             | 11       | 1.01%   |
| Acer                                 | 11       | 1.01%   |
| Unknown                              | 9        | 0.83%   |
| BESSTAR Tech                         | 8        | 0.74%   |
| Alienware                            | 8        | 0.74%   |
| Fujitsu                              | 7        | 0.65%   |
| MACHINIST                            | 6        | 0.55%   |
| Apple                                | 6        | 0.55%   |
| Foxconn                              | 5        | 0.46%   |
| Pegatron                             | 4        | 0.37%   |
| Biostar                              | 4        | 0.37%   |
| AZW                                  | 4        | 0.37%   |
| Supermicro                           | 3        | 0.28%   |
| Samsung Electronics                  | 3        | 0.28%   |
| Positivo                             | 3        | 0.28%   |
| NZXT                                 | 3        | 0.28%   |
| EVGA                                 | 3        | 0.28%   |
| Huanan                               | 2        | 0.18%   |
| ECS                                  | 2        | 0.18%   |
| ZOTAC                                | 1        | 0.09%   |
| Win element                          | 1        | 0.09%   |
| Soyo                                 | 1        | 0.09%   |
| SIEMENS                              | 1        | 0.09%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.09%   |
| PS                                   | 1        | 0.09%   |
| Packard Bell                         | 1        | 0.09%   |
| Minix                                | 1        | 0.09%   |
| Medion                               | 1        | 0.09%   |
| MAXSUN                               | 1        | 0.09%   |
| LattePanda                           | 1        | 0.09%   |
| JHZD                                 | 1        | 0.09%   |
| HC                                   | 1        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 20       | 1.85%   |
| ASUS ROG STRIX B550-F GAMING      | 15       | 1.38%   |
| ASUS ROG STRIX B550-I GAMING      | 10       | 0.92%   |
| ASUS ROG STRIX B450-F GAMING      | 10       | 0.92%   |
| Gigabyte X570 AORUS ELITE         | 9        | 0.83%   |
| Unknown                           | 9        | 0.83%   |
| Gigabyte B450 AORUS M             | 8        | 0.74%   |
| ASUS TUF Gaming X570-PLUS         | 8        | 0.74%   |
| ASUS TUF Gaming B550-PLUS         | 8        | 0.74%   |
| MSI MS-7B86                       | 7        | 0.65%   |
| System76 Thelio                   | 6        | 0.55%   |
| MSI MS-7C91                       | 6        | 0.55%   |
| MSI MS-7C37                       | 6        | 0.55%   |
| MSI MS-7A38                       | 6        | 0.55%   |
| Gigabyte B550M DS3H               | 6        | 0.55%   |
| ASUS TUF Gaming B550M-PLUS        | 6        | 0.55%   |
| ASUS PRIME B550M-A                | 6        | 0.55%   |
| MSI MS-7D54                       | 5        | 0.46%   |
| MSI MS-7D32                       | 5        | 0.46%   |
| MSI MS-7C02                       | 5        | 0.46%   |
| MSI MS-7693                       | 5        | 0.46%   |
| Gigabyte B450M DS3H               | 5        | 0.46%   |
| Gigabyte A320M-S2H                | 5        | 0.46%   |
| Dell OptiPlex 3020                | 5        | 0.46%   |
| ASUS ROG CROSSHAIR VIII HERO      | 5        | 0.46%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 5        | 0.46%   |
| ASUS PRIME B450M-A                | 5        | 0.46%   |
| System76 Thelio Mira              | 4        | 0.37%   |
| MSI MS-7C95                       | 4        | 0.37%   |
| MSI MS-7C94                       | 4        | 0.37%   |
| MSI MS-7C56                       | 4        | 0.37%   |
| MSI MS-7C35                       | 4        | 0.37%   |
| MSI MS-7B89                       | 4        | 0.37%   |
| MSI MS-7A34                       | 4        | 0.37%   |
| MSI MS-7721                       | 4        | 0.37%   |
| Intel X99                         | 4        | 0.37%   |
| HP Compaq Elite 8300 USDT         | 4        | 0.37%   |
| Gigabyte X570 AORUS MASTER        | 4        | 0.37%   |
| Gigabyte B550 AORUS ELITE AX V2   | 4        | 0.37%   |
| Gigabyte B450 AORUS PRO WIFI      | 4        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 106      | 9.78%   |
| ASUS PRIME             | 54       | 4.98%   |
| ASUS TUF               | 49       | 4.52%   |
| Dell OptiPlex          | 34       | 3.14%   |
| Gigabyte X570          | 21       | 1.94%   |
| Lenovo ThinkCentre     | 20       | 1.85%   |
| ASUS All               | 20       | 1.85%   |
| Gigabyte B450          | 19       | 1.75%   |
| HP Compaq              | 18       | 1.66%   |
| Dell Precision         | 16       | 1.48%   |
| Gigabyte B550          | 13       | 1.2%    |
| System76 Thelio        | 11       | 1.01%   |
| HP EliteDesk           | 10       | 0.92%   |
| Gigabyte B450M         | 10       | 0.92%   |
| Gigabyte B550M         | 9        | 0.83%   |
| Dell Inspiron          | 9        | 0.83%   |
| ASRock X570            | 9        | 0.83%   |
| Unknown                | 9        | 0.83%   |
| Dell XPS               | 8        | 0.74%   |
| MSI MS-7B86            | 7        | 0.65%   |
| ASRock B450            | 7        | 0.65%   |
| Alienware Aurora       | 7        | 0.65%   |
| Acer Aspire            | 7        | 0.65%   |
| MSI MS-7C91            | 6        | 0.55%   |
| MSI MS-7C37            | 6        | 0.55%   |
| MSI MS-7A38            | 6        | 0.55%   |
| Lenovo IdeaCentre      | 6        | 0.55%   |
| HP OMEN                | 6        | 0.55%   |
| Gigabyte A320M-S2H     | 6        | 0.55%   |
| Fujitsu ESPRIMO        | 6        | 0.55%   |
| ASRock B550            | 6        | 0.55%   |
| ASRock B450M           | 6        | 0.55%   |
| MSI MS-7D54            | 5        | 0.46%   |
| MSI MS-7D32            | 5        | 0.46%   |
| MSI MS-7C02            | 5        | 0.46%   |
| MSI MS-7693            | 5        | 0.46%   |
| Gigabyte GA-78LMT-USB3 | 5        | 0.46%   |
| ASUS SABERTOOTH        | 5        | 0.46%   |
| ASUS M5A97             | 5        | 0.46%   |
| ASRock X670E           | 5        | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 168      | 15.5%   |
| 2018    | 142      | 13.1%   |
| 2019    | 111      | 10.24%  |
| 2021    | 101      | 9.32%   |
| 2022    | 90       | 8.3%    |
| 2012    | 67       | 6.18%   |
| 2013    | 66       | 6.09%   |
| 2017    | 62       | 5.72%   |
| 2014    | 56       | 5.17%   |
| 2011    | 48       | 4.43%   |
| 2015    | 41       | 3.78%   |
| 2016    | 36       | 3.32%   |
| 2010    | 35       | 3.23%   |
| 2009    | 27       | 2.49%   |
| 2023    | 12       | 1.11%   |
| 2008    | 12       | 1.11%   |
| 2007    | 7        | 0.65%   |
| 2006    | 1        | 0.09%   |
| 2005    | 1        | 0.09%   |
| Unknown | 1        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1084     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1083     | 99.82%  |
| Enabled  | 2        | 0.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1084     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 353      | 32.03%  |
| 32.01-64.0      | 307      | 27.86%  |
| 8.01-16.0       | 150      | 13.61%  |
| 64.01-256.0     | 107      | 9.71%   |
| 4.01-8.0        | 93       | 8.44%   |
| 3.01-4.0        | 45       | 4.08%   |
| 24.01-32.0      | 40       | 3.63%   |
| More than 256.0 | 3        | 0.27%   |
| 2.01-3.0        | 2        | 0.18%   |
| 1.01-2.0        | 2        | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 415      | 34.73%  |
| 3.01-4.0    | 258      | 21.59%  |
| 2.01-3.0    | 256      | 21.42%  |
| 8.01-16.0   | 145      | 12.13%  |
| 1.01-2.0    | 91       | 7.62%   |
| 16.01-24.0  | 17       | 1.42%   |
| 32.01-64.0  | 7        | 0.59%   |
| 24.01-32.0  | 5        | 0.42%   |
| 64.01-256.0 | 1        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 351      | 31.56%  |
| 1      | 327      | 29.41%  |
| 3      | 204      | 18.35%  |
| 4      | 114      | 10.25%  |
| 5      | 63       | 5.67%   |
| 6      | 27       | 2.43%   |
| 7      | 11       | 0.99%   |
| 0      | 4        | 0.36%   |
| 9      | 3        | 0.27%   |
| 8      | 3        | 0.27%   |
| 10     | 2        | 0.18%   |
| 26     | 1        | 0.09%   |
| 19     | 1        | 0.09%   |
| 11     | 1        | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 786      | 72.31%  |
| Yes       | 301      | 27.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1070     | 98.71%  |
| No        | 14       | 1.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 617      | 56.66%  |
| No        | 472      | 43.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 592      | 54.26%  |
| Yes       | 499      | 45.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 403      | 36.9%   |
| Germany      | 91       | 8.33%   |
| Brazil       | 81       | 7.42%   |
| Canada       | 64       | 5.86%   |
| UK           | 51       | 4.67%   |
| Australia    | 35       | 3.21%   |
| Italy        | 33       | 3.02%   |
| France       | 32       | 2.93%   |
| Poland       | 21       | 1.92%   |
| Netherlands  | 20       | 1.83%   |
| Sweden       | 17       | 1.56%   |
| Finland      | 17       | 1.56%   |
| Norway       | 14       | 1.28%   |
| Russia       | 13       | 1.19%   |
| Greece       | 13       | 1.19%   |
| Mexico       | 12       | 1.1%    |
| Spain        | 11       | 1.01%   |
| Austria      | 11       | 1.01%   |
| Denmark      | 10       | 0.92%   |
| Portugal     | 8        | 0.73%   |
| Japan        | 8        | 0.73%   |
| India        | 8        | 0.73%   |
| Chile        | 8        | 0.73%   |
| Switzerland  | 7        | 0.64%   |
| South Africa | 7        | 0.64%   |
| Hungary      | 7        | 0.64%   |
| Hong Kong    | 7        | 0.64%   |
| Belgium      | 7        | 0.64%   |
| Romania      | 6        | 0.55%   |
| Malaysia     | 5        | 0.46%   |
| Ireland      | 5        | 0.46%   |
| Slovakia     | 4        | 0.37%   |
| Serbia       | 4        | 0.37%   |
| Czechia      | 4        | 0.37%   |
| Argentina    | 4        | 0.37%   |
| Thailand     | 3        | 0.27%   |
| Philippines  | 3        | 0.27%   |
| Lithuania    | 3        | 0.27%   |
| Indonesia    | 3        | 0.27%   |
| Sri Lanka    | 2        | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Seattle        | 10       | 0.88%   |
| Rio de Janeiro | 10       | 0.88%   |
| Helsinki       | 9        | 0.79%   |
| Berlin         | 9        | 0.79%   |
| Sydney         | 8        | 0.71%   |
| Sao Paulo      | 8        | 0.71%   |
| Vienna         | 7        | 0.62%   |
| Milan          | 6        | 0.53%   |
| Melbourne      | 6        | 0.53%   |
| Hamburg        | 6        | 0.53%   |
| Cleveland      | 6        | 0.53%   |
| Brisbane       | 6        | 0.53%   |
| San Francisco  | 5        | 0.44%   |
| Miami          | 5        | 0.44%   |
| Edmonton       | 5        | 0.44%   |
| Chicago        | 5        | 0.44%   |
| Central        | 5        | 0.44%   |
| Weimar         | 4        | 0.35%   |
| Toronto        | 4        | 0.35%   |
| Portland       | 4        | 0.35%   |
| Nuremberg      | 4        | 0.35%   |
| Montreal       | 4        | 0.35%   |
| Mannheim       | 4        | 0.35%   |
| Madrid         | 4        | 0.35%   |
| Johannesburg   | 4        | 0.35%   |
| Dublin         | 4        | 0.35%   |
| Dallas         | 4        | 0.35%   |
| Bratislava     | 4        | 0.35%   |
| Belgrade       | 4        | 0.35%   |
| Amsterdam      | 4        | 0.35%   |
| Adelaide       | 4        | 0.35%   |
| Zurich         | 3        | 0.26%   |
| Washington     | 3        | 0.26%   |
| Virginia Beach | 3        | 0.26%   |
| Vancouver      | 3        | 0.26%   |
| Temecula       | 3        | 0.26%   |
| Santiago       | 3        | 0.26%   |
| San Antonio    | 3        | 0.26%   |
| Rome           | 3        | 0.26%   |
| Richmond       | 3        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 408      | 661    | 18.32%  |
| Seagate                     | 337      | 500    | 15.13%  |
| WDC                         | 314      | 469    | 14.1%   |
| Sandisk                     | 158      | 199    | 7.09%   |
| Kingston                    | 126      | 157    | 5.66%   |
| Crucial                     | 122      | 182    | 5.48%   |
| Toshiba                     | 85       | 103    | 3.82%   |
| Phison Electronics          | 50       | 73     | 2.25%   |
| Hitachi                     | 44       | 73     | 1.98%   |
| Micron/Crucial Technology   | 38       | 49     | 1.71%   |
| A-DATA Technology           | 38       | 41     | 1.71%   |
| Intel                       | 37       | 54     | 1.66%   |
| Silicon Motion              | 26       | 34     | 1.17%   |
| Phison                      | 26       | 35     | 1.17%   |
| Unknown                     | 24       | 44     | 1.08%   |
| PNY                         | 24       | 31     | 1.08%   |
| China                       | 23       | 33     | 1.03%   |
| SK hynix                    | 22       | 32     | 0.99%   |
| SPCC                        | 18       | 27     | 0.81%   |
| Kingston Technology Company | 17       | 20     | 0.76%   |
| HGST                        | 15       | 19     | 0.67%   |
| Realtek Semiconductor       | 14       | 14     | 0.63%   |
| Micron Technology           | 12       | 14     | 0.54%   |
| Patriot                     | 11       | 13     | 0.49%   |
| OCZ                         | 11       | 16     | 0.49%   |
| ADATA Technology            | 11       | 12     | 0.49%   |
| Team                        | 10       | 15     | 0.45%   |
| Intenso                     | 10       | 14     | 0.45%   |
| XPG                         | 9        | 11     | 0.4%    |
| Netac                       | 9        | 10     | 0.4%    |
| Apple                       | 8        | 8      | 0.36%   |
| Lexar                       | 7        | 9      | 0.31%   |
| JMicron Technology          | 7        | 16     | 0.31%   |
| Hewlett-Packard             | 6        | 9      | 0.27%   |
| Corsair                     | 6        | 11     | 0.27%   |
| Unknown                     | 6        | 6      | 0.27%   |
| Verbatim                    | 5        | 9      | 0.22%   |
| Transcend                   | 5        | 7      | 0.22%   |
| SABRENT                     | 5        | 6      | 0.22%   |
| Gigabyte Technology         | 5        | 5      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 57       | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 37       | 1.42%   |
| Seagate ST2000DM008-2FR102 2TB                        | 33       | 1.27%   |
| Samsung SSD 860 EVO 1TB                               | 32       | 1.23%   |
| Samsung SSD 850 EVO 250GB                             | 29       | 1.12%   |
| Kingston SA400S37240G 240GB SSD                       | 29       | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB                        | 28       | 1.08%   |
| Samsung NVMe SSD Drive 1TB                            | 25       | 0.96%   |
| Samsung SSD 850 EVO 500GB                             | 23       | 0.89%   |
| Phison E12 NVMe Controller 2TB                        | 20       | 0.77%   |
| Kingston SA400S37120G 120GB SSD                       | 20       | 0.77%   |
| Crucial CT1000MX500SSD1 1TB                           | 20       | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                       | 19       | 0.73%   |
| Seagate ST4000DM004-2CV104 4TB                        | 19       | 0.73%   |
| Samsung SSD 860 EVO 500GB                             | 19       | 0.73%   |
| SanDisk NVMe SSD Drive 1TB                            | 18       | 0.69%   |
| Samsung NVMe SSD Drive 500GB                          | 18       | 0.69%   |
| Kingston SA400S37480G 480GB SSD                       | 17       | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 16       | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB                        | 16       | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 16       | 0.62%   |
| Crucial CT500MX500SSD1 500GB                          | 16       | 0.62%   |
| Samsung SSD 980 1TB                                   | 15       | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 14       | 0.54%   |
| Samsung SSD 870 QVO 1TB                               | 13       | 0.5%    |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 13       | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB                        | 12       | 0.46%   |
| Crucial CT1000BX500SSD1 1TB                           | 12       | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 11       | 0.42%   |
| Toshiba DT01ACA100 1TB                                | 11       | 0.42%   |
| Seagate Expansion 1TB                                 | 11       | 0.42%   |
| Samsung SSD 870 EVO 1TB                               | 11       | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                      | 11       | 0.42%   |
| Toshiba DT01ACA200 2TB                                | 10       | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 10       | 0.39%   |
| Samsung SSD 980 PRO 1TB                               | 10       | 0.39%   |
| Samsung SSD 850 EVO 1TB                               | 10       | 0.39%   |
| Samsung NVMe SSD Drive 2TB                            | 10       | 0.39%   |
| Crucial CT240BX500SSD1 240GB                          | 10       | 0.39%   |
| Crucial CT2000MX500SSD1 2TB                           | 10       | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 323      | 473    | 41.3%   |
| WDC                 | 264      | 391    | 33.76%  |
| Toshiba             | 77       | 95     | 9.85%   |
| Hitachi             | 44       | 73     | 5.63%   |
| Samsung Electronics | 28       | 37     | 3.58%   |
| HGST                | 15       | 19     | 1.92%   |
| Unknown             | 9        | 13     | 1.15%   |
| JMicron Technology  | 5        | 12     | 0.64%   |
| Apple               | 5        | 5      | 0.64%   |
| Maxtor              | 3        | 3      | 0.38%   |
| SABRENT             | 2        | 3      | 0.26%   |
| Fujitsu             | 2        | 5      | 0.26%   |
| ASMT                | 2        | 2      | 0.26%   |
| RSH-339             | 1        | 1      | 0.13%   |
| LaCie               | 1        | 1      | 0.13%   |
| Unknown             | 1        | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 209      | 313    | 26.32%  |
| Crucial             | 107      | 156    | 13.48%  |
| Kingston            | 103      | 125    | 12.97%  |
| SanDisk             | 60       | 73     | 7.56%   |
| WDC                 | 49       | 61     | 6.17%   |
| A-DATA Technology   | 32       | 35     | 4.03%   |
| PNY                 | 24       | 31     | 3.02%   |
| China               | 22       | 32     | 2.77%   |
| Intel               | 15       | 23     | 1.89%   |
| SPCC                | 14       | 18     | 1.76%   |
| Patriot             | 11       | 13     | 1.39%   |
| OCZ                 | 11       | 16     | 1.39%   |
| SK hynix            | 10       | 14     | 1.26%   |
| Team                | 8        | 12     | 1.01%   |
| Netac               | 8        | 9      | 1.01%   |
| Intenso             | 7        | 11     | 0.88%   |
| Micron Technology   | 6        | 6      | 0.76%   |
| Lexar               | 6        | 8      | 0.76%   |
| Transcend           | 5        | 7      | 0.63%   |
| Seagate             | 5        | 6      | 0.63%   |
| Hewlett-Packard     | 5        | 8      | 0.63%   |
| Apacer              | 5        | 5      | 0.63%   |
| Toshiba             | 4        | 4      | 0.5%    |
| KingSpec            | 4        | 4      | 0.5%    |
| GOODRAM             | 4        | 4      | 0.5%    |
| Corsair             | 4        | 5      | 0.5%    |
| Verbatim            | 3        | 7      | 0.38%   |
| TO Exter            | 3        | 3      | 0.38%   |
| Mushkin             | 3        | 4      | 0.38%   |
| LITEON              | 3        | 5      | 0.38%   |
| Gigabyte Technology | 3        | 3      | 0.38%   |
| Apple               | 3        | 3      | 0.38%   |
| LITEONIT            | 2        | 2      | 0.25%   |
| Yeyian              | 1        | 1      | 0.13%   |
| XPG                 | 1        | 1      | 0.13%   |
| V-GeN               | 1        | 1      | 0.13%   |
| TrekStor            | 1        | 1      | 0.13%   |
| Timetec             | 1        | 1      | 0.13%   |
| TCSUNBOW            | 1        | 1      | 0.13%   |
| T-FORCE             | 1        | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 640      | 1067   | 34.84%  |
| HDD     | 603      | 1134   | 32.83%  |
| NVMe    | 539      | 890    | 29.34%  |
| Unknown | 50       | 92     | 2.72%   |
| MMC     | 5        | 6      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 909      | 2106   | 58.27%  |
| NVMe | 536      | 883    | 34.36%  |
| SAS  | 110      | 194    | 7.05%   |
| MMC  | 5        | 6      | 0.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 602      | 987    | 42.94%  |
| 0.51-1.0   | 437      | 667    | 31.17%  |
| 1.01-2.0   | 202      | 283    | 14.41%  |
| 3.01-4.0   | 68       | 102    | 4.85%   |
| 4.01-10.0  | 56       | 103    | 3.99%   |
| 2.01-3.0   | 31       | 46     | 2.21%   |
| 10.01-20.0 | 6        | 13     | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 254      | 22.46%  |
| 101-250        | 212      | 18.74%  |
| 251-500        | 195      | 17.24%  |
| 1001-2000      | 172      | 15.21%  |
| More than 3000 | 143      | 12.64%  |
| 2001-3000      | 77       | 6.81%   |
| 1-20           | 32       | 2.83%   |
| 51-100         | 26       | 2.3%    |
| 21-50          | 13       | 1.15%   |
| Unknown        | 7        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 262      | 22.18%  |
| 21-50          | 207      | 17.53%  |
| 101-250        | 165      | 13.97%  |
| 251-500        | 138      | 11.69%  |
| 51-100         | 136      | 11.52%  |
| 501-1000       | 100      | 8.47%   |
| 1001-2000      | 80       | 6.77%   |
| More than 3000 | 55       | 4.66%   |
| 2001-3000      | 31       | 2.62%   |
| Unknown        | 7        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST3250310AS 250GB                    | 2        | 3      | 4.26%   |
| Samsung Electronics SSD 850 EVO 250GB        | 2        | 2      | 4.26%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 1      | 2.13%   |
| WDC WD5001AALS-00J7B1 500GB                  | 1        | 1      | 2.13%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 2.13%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 5      | 2.13%   |
| WDC WD15EADS-00P8B0 1TB                      | 1        | 1      | 2.13%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 2.13%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 2.13%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1        | 1      | 2.13%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1        | 1      | 2.13%   |
| Toshiba MK1655GSX 160GB                      | 1        | 1      | 2.13%   |
| Team T253X1120G 120GB SSD                    | 1        | 1      | 2.13%   |
| Seagate STM3500418AS 500GB                   | 1        | 1      | 2.13%   |
| Seagate ST6000AS0002-1N917X 6TB              | 1        | 1      | 2.13%   |
| Seagate ST5000LM000-2AN170 5TB               | 1        | 1      | 2.13%   |
| Seagate ST4000LM024-2AN17V 4TB               | 1        | 1      | 2.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1        | 1      | 2.13%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1      | 2.13%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 2.13%   |
| Seagate ST2000DM001-1CH164 2TB               | 1        | 1      | 2.13%   |
| Seagate ST2000DL004 HD204UI 2TB              | 1        | 1      | 2.13%   |
| Seagate ST1500DL003-9VT16L 1TB               | 1        | 1      | 2.13%   |
| Seagate Expansion Desk 8TB                   | 1        | 1      | 2.13%   |
| SanDisk SD8TB8U-256G-1006 256GB SSD          | 1        | 1      | 2.13%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1        | 1      | 2.13%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1        | 1      | 2.13%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 2.13%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1        | 1      | 2.13%   |
| Samsung Electronics MZVKW512HMJP-00000 512GB | 1        | 1      | 2.13%   |
| Samsung Electronics HD502HI 500GB            | 1        | 1      | 2.13%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 2.13%   |
| SABRENT Disk 1TB                             | 1        | 1      | 2.13%   |
| Plextor PX-128M6M 128GB SSD                  | 1        | 1      | 2.13%   |
| Kingston SV300S37A240G 240GB SSD             | 1        | 1      | 2.13%   |
| Kingston SA400S37120G 120GB SSD              | 1        | 2      | 2.13%   |
| Hitachi HDS5C3020BLE630 2TB                  | 1        | 1      | 2.13%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 2.13%   |
| HGST HUS726060ALA640 6TB                     | 1        | 1      | 2.13%   |
| HGST HTS725050A7E630 500GB                   | 1        | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 14     | 25%     |
| WDC                 | 9        | 13     | 20.45%  |
| Samsung Electronics | 8        | 9      | 18.18%  |
| Kingston            | 2        | 3      | 4.55%   |
| Hitachi             | 2        | 2      | 4.55%   |
| HGST                | 2        | 2      | 4.55%   |
| Crucial             | 2        | 2      | 4.55%   |
| Toshiba             | 1        | 1      | 2.27%   |
| Team                | 1        | 1      | 2.27%   |
| SanDisk             | 1        | 1      | 2.27%   |
| SABRENT             | 1        | 1      | 2.27%   |
| Plextor             | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |
| BAITITON            | 1        | 1      | 2.27%   |
| A-DATA Technology   | 1        | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 14     | 40.74%  |
| WDC                 | 9        | 13     | 33.33%  |
| Samsung Electronics | 2        | 2      | 7.41%   |
| Hitachi             | 2        | 2      | 7.41%   |
| HGST                | 2        | 2      | 7.41%   |
| Toshiba             | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 34     | 60.47%  |
| SSD  | 14       | 16     | 32.56%  |
| NVMe | 3        | 3      | 6.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 920      | 2630   | 79.11%  |
| Works    | 202      | 505    | 17.37%  |
| Malfunc  | 40       | 53     | 3.44%   |
| Failed   | 1        | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 542      | 29.23%  |
| Intel                          | 539      | 29.07%  |
| Samsung Electronics            | 233      | 12.57%  |
| SanDisk                        | 113      | 6.09%   |
| Phison Electronics             | 79       | 4.26%   |
| ASMedia Technology             | 64       | 3.45%   |
| Micron/Crucial Technology      | 55       | 2.97%   |
| Kingston Technology Company    | 41       | 2.21%   |
| Silicon Motion                 | 29       | 1.56%   |
| Marvell Technology Group       | 23       | 1.24%   |
| Realtek Semiconductor          | 21       | 1.13%   |
| ADATA Technology               | 19       | 1.02%   |
| JMicron Technology             | 16       | 0.86%   |
| SK hynix                       | 13       | 0.7%    |
| Nvidia                         | 10       | 0.54%   |
| Seagate Technology             | 8        | 0.43%   |
| Micron Technology              | 7        | 0.38%   |
| Broadcom / LSI                 | 7        | 0.38%   |
| Toshiba America Info Systems   | 5        | 0.27%   |
| MAXIO Technology (Hangzhou)    | 4        | 0.22%   |
| LSI Logic / Symbios Logic      | 4        | 0.22%   |
| VIA Technologies               | 3        | 0.16%   |
| Solidigm                       | 3        | 0.16%   |
| Lite-On Technology             | 3        | 0.16%   |
| INNOGRIT                       | 3        | 0.16%   |
| Silicon Image                  | 2        | 0.11%   |
| KIOXIA                         | 2        | 0.11%   |
| Union Memory (Shenzhen)        | 1        | 0.05%   |
| Solid State Storage Technology | 1        | 0.05%   |
| Shenzhen Longsys Electronics   | 1        | 0.05%   |
| Netac Technology               | 1        | 0.05%   |
| Biwin Storage Technology       | 1        | 0.05%   |
| Adaptec                        | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 329      | 14.98%  |
| AMD 500 Series Chipset SATA Controller                                                  | 130      | 5.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 124      | 5.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 114      | 5.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 65       | 2.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 60       | 2.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 58       | 2.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 46       | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 45       | 2.05%   |
| Intel SATA Controller [RAID mode]                                                       | 37       | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 37       | 1.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 36       | 1.64%   |
| Samsung NVMe SSD Controller 980                                                         | 34       | 1.55%   |
| Phison E12 NVMe Controller                                                              | 34       | 1.55%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 32       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 32       | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 29       | 1.32%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 27       | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 26       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 25       | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                                  | 25       | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 24       | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 22       | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 22       | 1%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 20       | 0.91%   |
| AMD FCH SATA Controller D                                                               | 19       | 0.87%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 18       | 0.82%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 17       | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 16       | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15       | 0.68%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 13       | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 0.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 13       | 0.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 12       | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 12       | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12       | 0.55%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 12       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 963      | 56.18%  |
| NVMe | 536      | 31.27%  |
| IDE  | 130      | 7.58%   |
| RAID | 70       | 4.08%   |
| SAS  | 14       | 0.82%   |
| SCSI | 1        | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 552      | 50.92%  |
| Intel  | 532      | 49.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 37       | 3.4%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 33       | 3.03%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 28       | 2.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 27       | 2.48%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 26       | 2.39%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 25       | 2.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 24       | 2.2%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 23       | 2.11%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 16       | 1.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15       | 1.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 15       | 1.38%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 15       | 1.38%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 1.38%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 14       | 1.29%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12       | 1.1%    |
| AMD FX-8350 Eight-Core Processor            | 12       | 1.1%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 11       | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 1.01%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 11       | 1.01%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 11       | 1.01%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 11       | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10       | 0.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 0.83%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 9        | 0.83%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9        | 0.83%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 8        | 0.73%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 8        | 0.73%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 8        | 0.73%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 8        | 0.73%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 8        | 0.73%   |
| AMD Ryzen 5 5600 6-Core Processor           | 8        | 0.73%   |
| AMD FX-6300 Six-Core Processor              | 8        | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 7        | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 7        | 0.64%   |
| Intel 12th Gen Core i9-12900K               | 7        | 0.64%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 7        | 0.64%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 7        | 0.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 6        | 0.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 187      | 17.17%  |
| Intel Core i7           | 156      | 14.33%  |
| AMD Ryzen 7             | 156      | 14.33%  |
| Intel Core i5           | 146      | 13.41%  |
| AMD Ryzen 9             | 93       | 8.54%   |
| Other                   | 63       | 5.79%   |
| Intel Xeon              | 52       | 4.78%   |
| Intel Core i3           | 43       | 3.95%   |
| AMD FX                  | 37       | 3.4%    |
| Intel Core i9           | 15       | 1.38%   |
| AMD Ryzen 3             | 15       | 1.38%   |
| Intel Core 2 Duo        | 12       | 1.1%    |
| AMD Ryzen Threadripper  | 11       | 1.01%   |
| Intel Pentium           | 10       | 0.92%   |
| Intel Celeron           | 10       | 0.92%   |
| Intel Core 2 Quad       | 9        | 0.83%   |
| AMD Athlon II X2        | 7        | 0.64%   |
| AMD Athlon II X4        | 6        | 0.55%   |
| AMD A8                  | 6        | 0.55%   |
| AMD Phenom II X4        | 5        | 0.46%   |
| Intel Pentium Gold      | 4        | 0.37%   |
| AMD Phenom II X6        | 4        | 0.37%   |
| AMD Athlon              | 4        | 0.37%   |
| AMD A10                 | 4        | 0.37%   |
| Intel Pentium Dual-Core | 3        | 0.28%   |
| Intel Pentium D         | 3        | 0.28%   |
| AMD Phenom              | 3        | 0.28%   |
| AMD Athlon X4           | 3        | 0.28%   |
| AMD A4                  | 3        | 0.28%   |
| Intel Pentium Dual      | 2        | 0.18%   |
| Intel Core 2            | 2        | 0.18%   |
| Intel Atom              | 2        | 0.18%   |
| AMD Ryzen 5 PRO         | 2        | 0.18%   |
| AMD A6                  | 2        | 0.18%   |
| Intel Pentium Silver    | 1        | 0.09%   |
| AMD Sempron             | 1        | 0.09%   |
| AMD Ryzen Embedded      | 1        | 0.09%   |
| AMD Ryzen 3 PRO         | 1        | 0.09%   |
| AMD PRO A8              | 1        | 0.09%   |
| AMD PRO A10             | 1        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 345      | 31.68%  |
| 6      | 243      | 22.31%  |
| 8      | 209      | 19.19%  |
| 2      | 106      | 9.73%   |
| 12     | 67       | 6.15%   |
| 16     | 63       | 5.79%   |
| 10     | 19       | 1.74%   |
| 3      | 14       | 1.29%   |
| 14     | 7        | 0.64%   |
| 24     | 6        | 0.55%   |
| 1      | 5        | 0.46%   |
| 32     | 2        | 0.18%   |
| 64     | 1        | 0.09%   |
| 36     | 1        | 0.09%   |
| 18     | 1        | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1072     | 98.89%  |
| 2      | 12       | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 817      | 75.37%  |
| 1      | 267      | 24.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1084     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 921      | 84.26%  |
| 0x08701021 | 24       | 2.2%    |
| 0x0a201016 | 14       | 1.28%   |
| 0x0800820d | 13       | 1.19%   |
| 0x0a601203 | 12       | 1.1%    |
| 0x506e3    | 7        | 0.64%   |
| 0x306c3    | 6        | 0.55%   |
| 0x306a9    | 6        | 0.55%   |
| 0x0a20120a | 6        | 0.55%   |
| 0x906ec    | 5        | 0.46%   |
| 0x90672    | 5        | 0.46%   |
| 0x206a7    | 5        | 0.46%   |
| 0x08701013 | 5        | 0.46%   |
| 0x08108109 | 5        | 0.46%   |
| 0x906e9    | 4        | 0.37%   |
| 0x0a50000d | 4        | 0.37%   |
| 0x0a201205 | 4        | 0.37%   |
| 0x08001138 | 4        | 0.37%   |
| 0xa0655    | 3        | 0.27%   |
| 0x906ea    | 3        | 0.27%   |
| 0x08001137 | 3        | 0.27%   |
| 0x06003106 | 3        | 0.27%   |
| 0x06000852 | 3        | 0.27%   |
| 0xa0671    | 2        | 0.18%   |
| 0xa0653    | 2        | 0.18%   |
| 0x50657    | 2        | 0.18%   |
| 0x0a50000c | 2        | 0.18%   |
| 0x0a201025 | 2        | 0.18%   |
| 0x0a201009 | 2        | 0.18%   |
| 0x08101016 | 2        | 0.18%   |
| 0xb0671    | 1        | 0.09%   |
| 0x906ed    | 1        | 0.09%   |
| 0x906c0    | 1        | 0.09%   |
| 0x806d1    | 1        | 0.09%   |
| 0x406f1    | 1        | 0.09%   |
| 0x306e4    | 1        | 0.09%   |
| 0x0a601201 | 1        | 0.09%   |
| 0x0a201006 | 1        | 0.09%   |
| 0x08600103 | 1        | 0.09%   |
| 0x08301039 | 1        | 0.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 188      | 17.28%  |
| Zen 2            | 123      | 11.31%  |
| Haswell          | 107      | 9.83%   |
| Unknown          | 92       | 8.46%   |
| KabyLake         | 83       | 7.63%   |
| Zen+             | 67       | 6.16%   |
| IvyBridge        | 59       | 5.42%   |
| Skylake          | 56       | 5.15%   |
| Zen              | 50       | 4.6%    |
| SandyBridge      | 50       | 4.6%    |
| Piledriver       | 40       | 3.68%   |
| CometLake        | 28       | 2.57%   |
| K10              | 27       | 2.48%   |
| Nehalem          | 22       | 2.02%   |
| Penryn           | 21       | 1.93%   |
| Alderlake Hybrid | 14       | 1.29%   |
| Westmere         | 13       | 1.19%   |
| Steamroller      | 10       | 0.92%   |
| Core             | 9        | 0.83%   |
| Broadwell        | 8        | 0.74%   |
| Silvermont       | 3        | 0.28%   |
| NetBurst         | 3        | 0.28%   |
| Goldmont         | 3        | 0.28%   |
| Excavator        | 3        | 0.28%   |
| Bulldozer        | 3        | 0.28%   |
| Jaguar           | 2        | 0.18%   |
| Icelake          | 2        | 0.18%   |
| K8 Hammer        | 1        | 0.09%   |
| K10 Llano        | 1        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 570      | 48.26%  |
| AMD                        | 424      | 35.9%   |
| Intel                      | 186      | 15.75%  |
| Matrox Electronics Systems | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 55       | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 40       | 3.26%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 33       | 2.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 33       | 2.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 30       | 2.44%   |
| AMD Raphael                                                                 | 30       | 2.44%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 28       | 2.28%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 27       | 2.2%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 27       | 2.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 23       | 1.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 20       | 1.63%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 19       | 1.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 18       | 1.47%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 17       | 1.38%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 16       | 1.3%    |
| Intel HD Graphics 530                                                       | 16       | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 16       | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 15       | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 15       | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 15       | 1.22%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 15       | 1.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15       | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 14       | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 13       | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 12       | 0.98%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 12       | 0.98%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 0.98%   |
| Nvidia GF108 [GeForce GT 730]                                               | 12       | 0.98%   |
| Intel AlderLake-S GT1                                                       | 12       | 0.98%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 11       | 0.9%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 11       | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 11       | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 10       | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 0.81%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 10       | 0.81%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 10       | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 0.81%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 10       | 0.81%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 10       | 0.81%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 9        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 511      | 46.62%  |
| 1 x AMD              | 360      | 32.85%  |
| 1 x Intel            | 127      | 11.59%  |
| 2 x AMD              | 29       | 2.65%   |
| AMD + Nvidia         | 26       | 2.37%   |
| Intel + Nvidia       | 21       | 1.92%   |
| 2 x Nvidia           | 9        | 0.82%   |
| Intel + AMD          | 8        | 0.73%   |
| Other                | 1        | 0.09%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.09%   |
| 1 x Matrox           | 1        | 0.09%   |
| Intel + 2 x Nvidia   | 1        | 0.09%   |
| AMD + 2 x Nvidia     | 1        | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 574      | 52.23%  |
| Proprietary | 482      | 43.86%  |
| Unknown     | 43       | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 762      | 68.9%   |
| 7.01-8.0   | 92       | 8.32%   |
| 8.01-16.0  | 59       | 5.33%   |
| 3.01-4.0   | 55       | 4.97%   |
| 1.01-2.0   | 55       | 4.97%   |
| 5.01-6.0   | 45       | 4.07%   |
| 0.51-1.0   | 11       | 0.99%   |
| 2.01-3.0   | 10       | 0.9%    |
| 16.01-24.0 | 8        | 0.72%   |
| 0.01-0.5   | 8        | 0.72%   |
| 32.01-64.0 | 1        | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 196      | 15.93%  |
| Goldstar             | 152      | 12.36%  |
| Dell                 | 136      | 11.06%  |
| Acer                 | 93       | 7.56%   |
| Hewlett-Packard      | 80       | 6.5%    |
| AOC                  | 75       | 6.1%    |
| ASUSTek Computer     | 60       | 4.88%   |
| Ancor Communications | 53       | 4.31%   |
| BenQ                 | 52       | 4.23%   |
| Philips              | 31       | 2.52%   |
| MSI                  | 23       | 1.87%   |
| Iiyama               | 22       | 1.79%   |
| Lenovo               | 19       | 1.54%   |
| Sceptre Tech         | 14       | 1.14%   |
| Gigabyte Technology  | 14       | 1.14%   |
| ViewSonic            | 12       | 0.98%   |
| Vizio                | 9        | 0.73%   |
| Sony                 | 9        | 0.73%   |
| NEC Computers        | 9        | 0.73%   |
| Unknown              | 6        | 0.49%   |
| Toshiba              | 5        | 0.41%   |
| Sharp                | 5        | 0.41%   |
| Panasonic            | 5        | 0.41%   |
| Eizo                 | 5        | 0.41%   |
| Viotek               | 4        | 0.33%   |
| Pioneer              | 4        | 0.33%   |
| Insignia             | 4        | 0.33%   |
| HKC                  | 4        | 0.33%   |
| Fujitsu Siemens      | 4        | 0.33%   |
| Vestel Elektronik    | 3        | 0.24%   |
| Valve                | 3        | 0.24%   |
| Unknown (XXX)        | 3        | 0.24%   |
| ONN                  | 3        | 0.24%   |
| NCS                  | 3        | 0.24%   |
| Mi                   | 3        | 0.24%   |
| Medion               | 3        | 0.24%   |
| LG Electronics       | 3        | 0.24%   |
| Hitachi              | 3        | 0.24%   |
| GDH                  | 3        | 0.24%   |
| Denver               | 3        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 11       | 0.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10       | 0.77%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 8        | 0.61%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.54%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 6        | 0.46%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 6        | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.46%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6        | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5        | 0.38%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 5        | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5        | 0.38%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 5        | 0.38%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch  | 4        | 0.31%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 4        | 0.31%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch    | 4        | 0.31%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 4        | 0.31%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 4        | 0.31%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 4        | 0.31%   |
| ASUSTek Computer VG279 AUS2782 1920x1080 598x336mm 27.0-inch          | 4        | 0.31%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch          | 4        | 0.31%   |
| AOC G2460 AOC0001 1920x1080 531x299mm 24.0-inch                       | 4        | 0.31%   |
| AOC AG241QG4 AOC2410 2560x1440 527x396mm 26.0-inch                    | 4        | 0.31%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 4        | 0.31%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 0.31%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 3        | 0.23%   |
| Valve Index HMD VLV91A8                                               | 3        | 0.23%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 521x293mm 23.5-inch        | 3        | 0.23%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 3        | 0.23%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 3        | 0.23%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch     | 3        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 3        | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.23%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 3        | 0.23%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 3        | 0.23%   |
| MSI MAG241C MSI3EA2 1920x1080 521x293mm 23.5-inch                     | 3        | 0.23%   |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                        | 3        | 0.23%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch               | 3        | 0.23%   |
| Hewlett-Packard E231 HWP3063 1920x1080 510x287mm 23.0-inch            | 3        | 0.23%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 3        | 0.23%   |
| Goldstar ULTRAGEAR GSM5BB3 2560x1440 597x336mm 27.0-inch              | 3        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 528      | 44.52%  |
| 3840x2160 (4K)     | 182      | 15.35%  |
| 2560x1440 (QHD)    | 142      | 11.97%  |
| 3440x1440          | 58       | 4.89%   |
| 2560x1080          | 38       | 3.2%    |
| 1366x768 (WXGA)    | 37       | 3.12%   |
| 1680x1050 (WSXGA+) | 33       | 2.78%   |
| 1280x1024 (SXGA)   | 30       | 2.53%   |
| 1920x1200 (WUXGA)  | 27       | 2.28%   |
| 1600x900 (HD+)     | 22       | 1.85%   |
| 1440x900 (WXGA+)   | 17       | 1.43%   |
| 3840x1080          | 16       | 1.35%   |
| 1360x768           | 12       | 1.01%   |
| 1920x540           | 9        | 0.76%   |
| 3840x1600          | 8        | 0.67%   |
| Unknown            | 7        | 0.59%   |
| 1024x768 (XGA)     | 5        | 0.42%   |
| 2560x1600          | 3        | 0.25%   |
| 1600x1200          | 3        | 0.25%   |
| 4480x1440          | 2        | 0.17%   |
| 1280x720 (HD)      | 2        | 0.17%   |
| 3280x1080          | 1        | 0.08%   |
| 3040x900           | 1        | 0.08%   |
| 2880x1600          | 1        | 0.08%   |
| 2288x1287          | 1        | 0.08%   |
| 1280x800 (WXGA)    | 1        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 237      | 19.17%  |
| 24      | 195      | 15.78%  |
| 23      | 146      | 11.81%  |
| 31      | 100      | 8.09%   |
| 21      | 96       | 7.77%   |
| 34      | 85       | 6.88%   |
| Unknown | 39       | 3.16%   |
| 19      | 36       | 2.91%   |
| 84      | 27       | 2.18%   |
| 22      | 26       | 2.1%    |
| 18      | 26       | 2.1%    |
| 32      | 25       | 2.02%   |
| 20      | 20       | 1.62%   |
| 72      | 19       | 1.54%   |
| 17      | 18       | 1.46%   |
| 48      | 16       | 1.29%   |
| 28      | 12       | 0.97%   |
| 37      | 10       | 0.81%   |
| 54      | 9        | 0.73%   |
| 15      | 9        | 0.73%   |
| 25      | 8        | 0.65%   |
| 40      | 7        | 0.57%   |
| 65      | 6        | 0.49%   |
| 29      | 6        | 0.49%   |
| 26      | 6        | 0.49%   |
| 52      | 5        | 0.4%    |
| 33      | 5        | 0.4%    |
| 46      | 4        | 0.32%   |
| 36      | 4        | 0.32%   |
| 35      | 4        | 0.32%   |
| 12      | 4        | 0.32%   |
| 49      | 3        | 0.24%   |
| 47      | 3        | 0.24%   |
| 44      | 3        | 0.24%   |
| 42      | 3        | 0.24%   |
| 74      | 2        | 0.16%   |
| 69      | 2        | 0.16%   |
| 57      | 2        | 0.16%   |
| 38      | 2        | 0.16%   |
| 75      | 1        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 511      | 43.75%  |
| 401-500     | 181      | 15.5%   |
| 601-700     | 141      | 12.07%  |
| 701-800     | 115      | 9.85%   |
| 1501-2000   | 51       | 4.37%   |
| 1001-1500   | 51       | 4.37%   |
| Unknown     | 39       | 3.34%   |
| 301-350     | 26       | 2.23%   |
| 801-900     | 25       | 2.14%   |
| 351-400     | 18       | 1.54%   |
| 201-300     | 5        | 0.43%   |
| 901-1000    | 5        | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 810      | 73.84%  |
| 21/9    | 104      | 9.48%   |
| 16/10   | 99       | 9.02%   |
| 5/4     | 32       | 2.92%   |
| 32/9    | 19       | 1.73%   |
| Unknown | 19       | 1.73%   |
| 4/3     | 14       | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 350      | 29.24%  |
| 301-350        | 245      | 20.47%  |
| 351-500        | 222      | 18.55%  |
| 151-200        | 79       | 6.6%    |
| 251-300        | 78       | 6.52%   |
| More than 1000 | 76       | 6.35%   |
| 501-1000       | 50       | 4.18%   |
| 141-150        | 42       | 3.51%   |
| Unknown        | 39       | 3.26%   |
| 101-110        | 8        | 0.67%   |
| 71-80          | 5        | 0.42%   |
| 111-120        | 2        | 0.17%   |
| 131-140        | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 683      | 61.09%  |
| 101-120       | 242      | 21.65%  |
| 121-160       | 65       | 5.81%   |
| 1-50          | 54       | 4.83%   |
| Unknown       | 39       | 3.49%   |
| 161-240       | 34       | 3.04%   |
| More than 240 | 1        | 0.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 781      | 71%     |
| 2     | 232      | 21.09%  |
| 0     | 48       | 4.36%   |
| 3     | 34       | 3.09%   |
| 4     | 4        | 0.36%   |
| 6     | 1        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 643      | 40.06%  |
| Intel                           | 558      | 34.77%  |
| Qualcomm Atheros                | 88       | 5.48%   |
| MediaTek                        | 49       | 3.05%   |
| Broadcom                        | 46       | 2.87%   |
| TP-Link                         | 31       | 1.93%   |
| Ralink Technology               | 20       | 1.25%   |
| NetGear                         | 16       | 1%      |
| Ralink                          | 12       | 0.75%   |
| Microsoft                       | 12       | 0.75%   |
| Aquantia                        | 12       | 0.75%   |
| InterBiometrics                 | 11       | 0.69%   |
| Samsung Electronics             | 10       | 0.62%   |
| Nvidia                          | 8        | 0.5%    |
| Google                          | 8        | 0.5%    |
| D-Link                          | 7        | 0.44%   |
| Xiaomi                          | 6        | 0.37%   |
| Linksys                         | 6        | 0.37%   |
| D-Link System                   | 6        | 0.37%   |
| ASIX Electronics                | 6        | 0.37%   |
| Qualcomm Atheros Communications | 5        | 0.31%   |
| Broadcom Limited                | 5        | 0.31%   |
| Marvell Technology Group        | 4        | 0.25%   |
| Mellanox Technologies           | 3        | 0.19%   |
| Huawei Technologies             | 3        | 0.19%   |
| ASUSTek Computer                | 3        | 0.19%   |
| OPPO Electronics                | 2        | 0.12%   |
| Belkin Components               | 2        | 0.12%   |
| Wacom                           | 1        | 0.06%   |
| VIA Technologies                | 1        | 0.06%   |
| U-Blox                          | 1        | 0.06%   |
| T & A Mobile Phones             | 1        | 0.06%   |
| STMicroelectronics              | 1        | 0.06%   |
| Sitecom Europe                  | 1        | 0.06%   |
| SIEMENS                         | 1        | 0.06%   |
| ROCCAT                          | 1        | 0.06%   |
| Qualcomm                        | 1        | 0.06%   |
| QinHeng Electronics             | 1        | 0.06%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.06%   |
| Micro Star International        | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 445      | 23.46%  |
| Realtek RTL8125 2.5GbE Controller                                 | 135      | 7.12%   |
| Intel Wi-Fi 6 AX200                                               | 129      | 6.8%    |
| Intel I211 Gigabit Network Connection                             | 127      | 6.69%   |
| Intel Ethernet Controller I225-V                                  | 94       | 4.96%   |
| Intel Ethernet Connection (2) I219-V                              | 35       | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 35       | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34       | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29       | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 27       | 1.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 25       | 1.32%   |
| Realtek 802.11ac NIC                                              | 21       | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 21       | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 21       | 1.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 17       | 0.9%    |
| Intel Wireless-AC 9260                                            | 17       | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 16       | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16       | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 16       | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 14       | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14       | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13       | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 0.58%   |
| InterBiometrics Io                                                | 11       | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10       | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10       | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 0.53%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 10       | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9        | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9        | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.47%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 8        | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 0.42%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8        | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7        | 0.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7        | 0.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 7        | 0.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 293      | 44.87%  |
| Realtek Semiconductor           | 107      | 16.39%  |
| MediaTek                        | 49       | 7.5%    |
| Qualcomm Atheros                | 45       | 6.89%   |
| Broadcom                        | 35       | 5.36%   |
| TP-Link                         | 28       | 4.29%   |
| Ralink Technology               | 20       | 3.06%   |
| NetGear                         | 16       | 2.45%   |
| Ralink                          | 12       | 1.84%   |
| Microsoft                       | 12       | 1.84%   |
| Linksys                         | 6        | 0.92%   |
| D-Link                          | 6        | 0.92%   |
| Qualcomm Atheros Communications | 5        | 0.77%   |
| D-Link System                   | 5        | 0.77%   |
| ASUSTek Computer                | 3        | 0.46%   |
| Broadcom Limited                | 2        | 0.31%   |
| Belkin Components               | 2        | 0.31%   |
| Wacom                           | 1        | 0.15%   |
| Sitecom Europe                  | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| IMC Networks                    | 1        | 0.15%   |
| Gemtek                          | 1        | 0.15%   |
| Edimax Technology               | 1        | 0.15%   |
| AVM                             | 1        | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 129      | 19.52%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 35       | 5.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 29       | 4.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 25       | 3.78%   |
| Realtek 802.11ac NIC                                                                          | 21       | 3.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 21       | 3.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 17       | 2.57%   |
| Intel Wireless-AC 9260                                                                        | 17       | 2.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 16       | 2.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 16       | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 14       | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 10       | 1.51%   |
| Intel 700 Series Chipset Family Wi-Fi                                                         | 10       | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 9        | 1.36%   |
| Ralink MT7601U Wireless Adapter                                                               | 9        | 1.36%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                                   | 8        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 8        | 1.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 7        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 7        | 1.06%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 7        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7        | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 7        | 1.06%   |
| NetGear A6210                                                                                 | 7        | 1.06%   |
| Intel Wireless 8265 / 8275                                                                    | 7        | 1.06%   |
| Intel Wireless 7265                                                                           | 7        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 6        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6        | 0.91%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 6        | 0.91%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 6        | 0.91%   |
| Intel Wireless 7260                                                                           | 6        | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 5        | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 5        | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 5        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 5        | 0.76%   |
| TP-Link 802.11ac NIC                                                                          | 4        | 0.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 4        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4        | 0.61%   |
| Intel Wireless 3165                                                                           | 4        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 603      | 51.28%  |
| Intel                    | 439      | 37.33%  |
| Qualcomm Atheros         | 48       | 4.08%   |
| Broadcom                 | 14       | 1.19%   |
| Aquantia                 | 12       | 1.02%   |
| Nvidia                   | 8        | 0.68%   |
| Google                   | 8        | 0.68%   |
| Xiaomi                   | 6        | 0.51%   |
| Samsung Electronics      | 6        | 0.51%   |
| ASIX Electronics         | 6        | 0.51%   |
| Marvell Technology Group | 4        | 0.34%   |
| TP-Link                  | 3        | 0.26%   |
| Mellanox Technologies    | 3        | 0.26%   |
| Huawei Technologies      | 3        | 0.26%   |
| Broadcom Limited         | 3        | 0.26%   |
| OPPO Electronics         | 2        | 0.17%   |
| VIA Technologies         | 1        | 0.09%   |
| T & A Mobile Phones      | 1        | 0.09%   |
| Qualcomm                 | 1        | 0.09%   |
| Lenovo                   | 1        | 0.09%   |
| DisplayLink              | 1        | 0.09%   |
| D-Link System            | 1        | 0.09%   |
| D-Link                   | 1        | 0.09%   |
| American Megatrends      | 1        | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 445      | 36.75%  |
| Realtek RTL8125 2.5GbE Controller                                 | 135      | 11.15%  |
| Intel I211 Gigabit Network Connection                             | 127      | 10.49%  |
| Intel Ethernet Controller I225-V                                  | 94       | 7.76%   |
| Intel Ethernet Connection (2) I219-V                              | 35       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34       | 2.81%   |
| Intel Ethernet Connection I217-LM                                 | 27       | 2.23%   |
| Intel Ethernet Connection (7) I219-V                              | 21       | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16       | 1.32%   |
| Intel Ethernet Connection (2) I218-V                              | 14       | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13       | 1.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10       | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 10       | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9        | 0.74%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 0.66%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 6        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 0.5%    |
| Google Pixel 7                                                    | 6        | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.41%   |
| Intel Ethernet Connection (2) I218-LM                             | 5        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                          | 5        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.33%   |
| Intel Ethernet Controller I226-V                                  | 4        | 0.33%   |
| Intel Ethernet Connection (17) I219-V                             | 4        | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4        | 0.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3        | 0.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3        | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1071     | 62.45%  |
| WiFi     | 619      | 36.09%  |
| Modem    | 19       | 1.11%   |
| Unknown  | 6        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 812      | 70.61%  |
| WiFi     | 337      | 29.3%   |
| Modem    | 1        | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 558      | 51.33%  |
| 2     | 443      | 40.75%  |
| 3     | 69       | 6.35%   |
| 0     | 11       | 1.01%   |
| 4     | 4        | 0.37%   |
| 5     | 2        | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 742      | 67.45%  |
| Yes  | 358      | 32.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 267      | 52.25%  |
| Cambridge Silicon Radio         | 78       | 15.26%  |
| Realtek Semiconductor           | 37       | 7.24%   |
| MediaTek                        | 32       | 6.26%   |
| ASUSTek Computer                | 23       | 4.5%    |
| Qualcomm Atheros Communications | 17       | 3.33%   |
| Apple                           | 12       | 2.35%   |
| Broadcom                        | 10       | 1.96%   |
| TP-Link                         | 9        | 1.76%   |
| Dynex                           | 6        | 1.17%   |
| Foxconn / Hon Hai               | 5        | 0.98%   |
| Actions                         | 3        | 0.59%   |
| Lite-On Technology              | 2        | 0.39%   |
| Integrated System Solution      | 2        | 0.39%   |
| IMC Networks                    | 2        | 0.39%   |
| SINO WEALTH                     | 1        | 0.2%    |
| Micro Star International        | 1        | 0.2%    |
| Logitech                        | 1        | 0.2%    |
| HTC (High Tech Computer)        | 1        | 0.2%    |
| Edimax Technology               | 1        | 0.2%    |
| Belkin Components               | 1        | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 118      | 23.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 78       | 15.23%  |
| MediaTek Wireless_Device                                 | 32       | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                         | 32       | 6.25%   |
| Intel AX201 Bluetooth                                    | 30       | 5.86%   |
| Realtek Bluetooth Radio                                  | 24       | 4.69%   |
| Intel AX210 Bluetooth                                    | 24       | 4.69%   |
| Intel Bluetooth wireless interface                       | 20       | 3.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 17       | 3.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 14       | 2.73%   |
| Intel Bluetooth Device                                   | 11       | 2.15%   |
| Qualcomm Atheros  Bluetooth Device                       | 10       | 1.95%   |
| TP-Link UB500 Adapter                                    | 9        | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                           | 9        | 1.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 7        | 1.37%   |
| ASUS Bluetooth Radio                                     | 7        | 1.37%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 6        | 1.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 1.17%   |
| ASUS ASUS USB-BT500                                      | 6        | 1.17%   |
| Apple Bluetooth USB Host Controller                      | 6        | 1.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 3        | 0.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3        | 0.59%   |
| Actions general adapter                                  | 3        | 0.59%   |
| Realtek RTL8821A Bluetooth                               | 2        | 0.39%   |
| Realtek Bluetooth 5.1 Radio                              | 2        | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 0.39%   |
| Foxconn / Hon Hai Wireless_Device                        | 2        | 0.39%   |
| Foxconn / Hon Hai Bluetooth Device                       | 2        | 0.39%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 2        | 0.39%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 0.39%   |
| Apple Bluetooth HCI                                      | 2        | 0.39%   |
| SINO WEALTH RK Bluetooth Keyboar                         | 1        | 0.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.2%    |
| Qualcomm Atheros Bluetooth                               | 1        | 0.2%    |
| Micro Star International Bluetooth Device                | 1        | 0.2%    |
| Logitech BT Mini-Receiver (HCI mode)                     | 1        | 0.2%    |
| Lite-On Bluetooth Radio                                  | 1        | 0.2%    |
| Lite-On Bluetooth Device                                 | 1        | 0.2%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.2%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 650      | 29.67%  |
| Nvidia                               | 559      | 25.51%  |
| Intel                                | 515      | 23.51%  |
| C-Media Electronics                  | 62       | 2.83%   |
| Logitech                             | 31       | 1.41%   |
| Kingston Technology                  | 25       | 1.14%   |
| Razer USA                            | 23       | 1.05%   |
| Creative Labs                        | 22       | 1%      |
| Micro Star International             | 21       | 0.96%   |
| ASUSTek Computer                     | 21       | 0.96%   |
| JMTek                                | 18       | 0.82%   |
| SteelSeries ApS                      | 16       | 0.73%   |
| Focusrite-Novation                   | 14       | 0.64%   |
| Creative Technology                  | 11       | 0.5%    |
| Corsair                              | 11       | 0.5%    |
| Generalplus Technology               | 10       | 0.46%   |
| Texas Instruments                    | 9        | 0.41%   |
| Blue Microphones                     | 9        | 0.41%   |
| Scarlett                             | 8        | 0.37%   |
| GN Netcom                            | 7        | 0.32%   |
| DSEA A/S                             | 6        | 0.27%   |
| Tenx Technology                      | 4        | 0.18%   |
| Realtek Semiconductor                | 4        | 0.18%   |
| Plantronics                          | 4        | 0.18%   |
| Medeli Electronics                   | 4        | 0.18%   |
| M-Audio                              | 4        | 0.18%   |
| Giga-Byte Technology                 | 4        | 0.18%   |
| FUXIN                                | 4        | 0.18%   |
| BEHRINGER International              | 4        | 0.18%   |
| Astro Gaming                         | 4        | 0.18%   |
| Valve Software                       | 3        | 0.14%   |
| Trust                                | 3        | 0.14%   |
| Thesycon Systemsoftware & Consulting | 3        | 0.14%   |
| Sony                                 | 3        | 0.14%   |
| SAVITECH                             | 3        | 0.14%   |
| Native Instruments                   | 3        | 0.14%   |
| Mackie Designs                       | 3        | 0.14%   |
| Jieli Technology                     | 3        | 0.14%   |
| FiiO Electronics Technology          | 3        | 0.14%   |
| Antlion Audio                        | 3        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 242      | 9.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 120      | 4.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 108      | 4.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 82       | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 71       | 2.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 61       | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 61       | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 58       | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 51       | 1.97%   |
| Intel 200 Series PCH HD Audio                                              | 50       | 1.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 48       | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48       | 1.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 46       | 1.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 46       | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46       | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 45       | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 44       | 1.7%    |
| Nvidia GA102 High Definition Audio Controller                              | 41       | 1.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 40       | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 36       | 1.39%   |
| Nvidia TU104 HD Audio Controller                                           | 35       | 1.35%   |
| AMD Navi 10 HDMI Audio                                                     | 33       | 1.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 32       | 1.23%   |
| Intel Alder Lake-S HD Audio Controller                                     | 30       | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 27       | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                              | 26       | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 26       | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 25       | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 25       | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 22       | 0.85%   |
| Micro Star International USB Audio                                         | 21       | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 21       | 0.81%   |
| AMD FCH Azalia Controller                                                  | 19       | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18       | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 16       | 0.62%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 16       | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                              | 15       | 0.58%   |
| Kingston Technology HyperX 7.1 Audio                                       | 15       | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15       | 0.58%   |
| Nvidia GM206 High Definition Audio Controller                              | 14       | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 61       | 27.11%  |
| G.Skill                      | 38       | 16.89%  |
| Kingston                     | 37       | 16.44%  |
| Crucial                      | 17       | 7.56%   |
| Team                         | 16       | 7.11%   |
| Samsung Electronics          | 15       | 6.67%   |
| SK hynix                     | 10       | 4.44%   |
| Unknown                      | 9        | 4%      |
| Micron Technology            | 6        | 2.67%   |
| A-DATA Technology            | 5        | 2.22%   |
| Unknown                      | 2        | 0.89%   |
| Teikon                       | 1        | 0.44%   |
| Patriot Memory (PDP Systems) | 1        | 0.44%   |
| Patriot Memory               | 1        | 0.44%   |
| Patriot                      | 1        | 0.44%   |
| Neo Forza                    | 1        | 0.44%   |
| GeIL                         | 1        | 0.44%   |
| Avant                        | 1        | 0.44%   |
| Asgard                       | 1        | 0.44%   |
| Apacer                       | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 10       | 4.22%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 8        | 3.38%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 6        | 2.53%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s    | 5        | 2.11%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 4        | 1.69%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 3        | 1.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 3        | 1.27%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 3        | 1.27%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 3        | 1.27%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s        | 2        | 0.84%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s  | 2        | 0.84%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 2        | 0.84%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 2        | 0.84%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 0.84%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 2        | 0.84%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2        | 0.84%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s      | 2        | 0.84%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 2        | 0.84%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 2        | 0.84%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s      | 2        | 0.84%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 2        | 0.84%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 2        | 0.84%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s     | 2        | 0.84%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3400MT/s  | 2        | 0.84%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s     | 2        | 0.84%   |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM 5200MT/s         | 2        | 0.84%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s    | 2        | 0.84%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 2        | 0.84%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s    | 2        | 0.84%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 2        | 0.84%   |
| Corsair RAM CMH32GX5M2D6000C36 16GB DIMM DDR5 4800MT/s    | 2        | 0.84%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s              | 2        | 0.84%   |
| Unknown                                                   | 2        | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                  | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 154      | 72.99%  |
| DDR3    | 33       | 15.64%  |
| DDR5    | 18       | 8.53%   |
| Unknown | 3        | 1.42%   |
| DDR2    | 2        | 0.95%   |
| LPDDR4  | 1        | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 201      | 95.26%  |
| SODIMM       | 9        | 4.27%   |
| Row Of Chips | 1        | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 90       | 40.72%  |
| 16384 | 70       | 31.67%  |
| 32768 | 29       | 13.12%  |
| 4096  | 28       | 12.67%  |
| 2048  | 4        | 1.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 39       | 17.26%  |
| 1600  | 27       | 11.95%  |
| 3200  | 26       | 11.5%   |
| 3800  | 11       | 4.87%   |
| 2400  | 11       | 4.87%   |
| 3733  | 10       | 4.42%   |
| 3533  | 8        | 3.54%   |
| 2667  | 8        | 3.54%   |
| 3000  | 7        | 3.1%    |
| 4800  | 6        | 2.65%   |
| 2133  | 6        | 2.65%   |
| 1333  | 6        | 2.65%   |
| 6000  | 5        | 2.21%   |
| 3534  | 5        | 2.21%   |
| 3400  | 5        | 2.21%   |
| 2933  | 4        | 1.77%   |
| 3866  | 3        | 1.33%   |
| 2800  | 3        | 1.33%   |
| 2666  | 3        | 1.33%   |
| 1866  | 3        | 1.33%   |
| 6400  | 2        | 0.88%   |
| 5200  | 2        | 0.88%   |
| 4000  | 2        | 0.88%   |
| 3666  | 2        | 0.88%   |
| 3466  | 2        | 0.88%   |
| 3333  | 2        | 0.88%   |
| 3100  | 2        | 0.88%   |
| 800   | 2        | 0.88%   |
| 6800  | 1        | 0.44%   |
| 6600  | 1        | 0.44%   |
| 5600  | 1        | 0.44%   |
| 4400  | 1        | 0.44%   |
| 3500  | 1        | 0.44%   |
| 3266  | 1        | 0.44%   |
| 3066  | 1        | 0.44%   |
| 2733  | 1        | 0.44%   |
| 2600  | 1        | 0.44%   |
| 2187  | 1        | 0.44%   |
| 1867  | 1        | 0.44%   |
| 1800  | 1        | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 11       | 28.95%  |
| Brother Industries  | 8        | 21.05%  |
| Canon               | 6        | 15.79%  |
| Samsung Electronics | 5        | 13.16%  |
| Seiko Epson         | 4        | 10.53%  |
| QinHeng Electronics | 1        | 2.63%   |
| Prolific Technology | 1        | 2.63%   |
| Dymo-CoStar         | 1        | 2.63%   |
| Dell                | 1        | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Brother HL-2130 series                       | 3        | 7.69%   |
| Seiko Epson WF-4830 Series                   | 2        | 5.13%   |
| HP ENVY Pro 6400 series                      | 2        | 5.13%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 2.56%   |
| Seiko Epson ET-2800 Series                   | 1        | 2.56%   |
| Samsung SCX-4500 Laser Printer               | 1        | 2.56%   |
| Samsung SCX-3400 Series                      | 1        | 2.56%   |
| Samsung ML-216x Series Laser Printer         | 1        | 2.56%   |
| Samsung ML-191x/ML-252x Laser Printer        | 1        | 2.56%   |
| Samsung M2070 Series                         | 1        | 2.56%   |
| QinHeng CH340S                               | 1        | 2.56%   |
| Prolific PL2305 Parallel Port                | 1        | 2.56%   |
| HP PSC-1315/PSC-1317                         | 1        | 2.56%   |
| HP OfficeJet Pro 9010 series                 | 1        | 2.56%   |
| HP LaserJet Professional P1102w              | 1        | 2.56%   |
| HP LaserJet Professional P 1102w             | 1        | 2.56%   |
| HP LaserJet Pro M201dw                       | 1        | 2.56%   |
| HP LaserJet P2035                            | 1        | 2.56%   |
| HP LaserJet 3050                             | 1        | 2.56%   |
| HP Ink Tank 110 series                       | 1        | 2.56%   |
| HP DeskJet 2620 All-in-One Printer           | 1        | 2.56%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 2.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 1        | 2.56%   |
| Dell Laser Printer 1720                      | 1        | 2.56%   |
| Canon TS9100 series                          | 1        | 2.56%   |
| Canon TR8500 series                          | 1        | 2.56%   |
| Canon TR4700 series                          | 1        | 2.56%   |
| Canon Pro9000II series                       | 1        | 2.56%   |
| Canon PIXMA MP240                            | 1        | 2.56%   |
| Canon PIXMA MG2500 Series                    | 1        | 2.56%   |
| Brother MFC-L2700DW                          | 1        | 2.56%   |
| Brother MFC-5440CN                           | 1        | 2.56%   |
| Brother HL-3140CW series                     | 1        | 2.56%   |
| Brother HL-2270DW Laser Printer              | 1        | 2.56%   |
| Brother HL-1200 series                       | 1        | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 44.44%  |
| Seiko Epson     | 3        | 33.33%  |
| Mustek Systems  | 1        | 11.11%  |
| Hewlett-Packard | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 11.11%  |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 11.11%  |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 11.11%  |
| HP ScanJet 82x0C                                        | 1        | 11.11%  |
| Canon CanoScan N650U/N656U                              | 1        | 11.11%  |
| Canon CanoScan LiDE 60                                  | 1        | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1        | 11.11%  |
| Canon CanoScan 9000F Mark II                            | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 103      | 39.46%  |
| Microdia                      | 23       | 8.81%   |
| Sunplus Innovation Technology | 15       | 5.75%   |
| Microsoft                     | 12       | 4.6%    |
| Apple                         | 11       | 4.21%   |
| Razer USA                     | 7        | 2.68%   |
| Samsung Electronics           | 6        | 2.3%    |
| Jieli Technology              | 6        | 2.3%    |
| Creative Technology           | 6        | 2.3%    |
| Realtek Semiconductor         | 5        | 1.92%   |
| ARC International             | 5        | 1.92%   |
| MacroSilicon                  | 4        | 1.53%   |
| Generalplus Technology        | 4        | 1.53%   |
| Cubeternet                    | 4        | 1.53%   |
| LG Electronics                | 3        | 1.15%   |
| Chicony Electronics           | 3        | 1.15%   |
| Z-Star Microelectronics       | 2        | 0.77%   |
| YGTek                         | 2        | 0.77%   |
| Valve Software                | 2        | 0.77%   |
| Trust                         | 2        | 0.77%   |
| Sunplus IT                    | 2        | 0.77%   |
| SN0002                        | 2        | 0.77%   |
| Ruision                       | 2        | 0.77%   |
| Hewlett-Packard               | 2        | 0.77%   |
| eMeet                         | 2        | 0.77%   |
| Elgato Systems                | 2        | 0.77%   |
| AVerMedia Technologies        | 2        | 0.77%   |
| YT-221117-J                   | 1        | 0.38%   |
| Xiaomi                        | 1        | 0.38%   |
| XHT-210518                    | 1        | 0.38%   |
| WaveRider Communications      | 1        | 0.38%   |
| ValueHD                       | 1        | 0.38%   |
| SunplusIT                     | 1        | 0.38%   |
| Polycom                       | 1        | 0.38%   |
| Philips (or NXP)              | 1        | 0.38%   |
| Owon                          | 1        | 0.38%   |
| OmniVision Technologies       | 1        | 0.38%   |
| Novatek Microelectronics      | 1        | 0.38%   |
| Lenovo                        | 1        | 0.38%   |
| KYE Systems (Mouse Systems)   | 1        | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 26       | 9.89%   |
| Logitech HD Pro Webcam C920                           | 19       | 7.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 11       | 4.18%   |
| Microdia Webcam Vitade AF                             | 9        | 3.42%   |
| Logitech BRIO Ultra HD Webcam                         | 8        | 3.04%   |
| Logitech C922 Pro Stream Webcam                       | 7        | 2.66%   |
| Samsung Galaxy series, misc. (MTP mode)               | 6        | 2.28%   |
| Microdia USB 2.0 Camera                               | 6        | 2.28%   |
| Logitech Webcam C925e                                 | 6        | 2.28%   |
| Jieli USB PHY 2.0                                     | 6        | 2.28%   |
| Razer USA Gaming Webcam [Kiyo]                        | 5        | 1.9%    |
| Logitech HD Webcam C525                               | 5        | 1.9%    |
| Logitech C920 PRO HD Webcam                           | 5        | 1.9%    |
| ARC International Camera                              | 5        | 1.9%    |
| Microsoft LifeCam HD-3000                             | 4        | 1.52%   |
| MacroSilicon USB Video                                | 4        | 1.52%   |
| Logitech StreamCam                                    | 4        | 1.52%   |
| Logitech HD Webcam C615                               | 4        | 1.52%   |
| Sunplus video capture device                          | 3        | 1.14%   |
| Microsoft LifeCam Cinema                              | 3        | 1.14%   |
| Logitech Webcam C930e                                 | 3        | 1.14%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 3        | 1.14%   |
| Generalplus GENERAL WEBCAM                            | 3        | 1.14%   |
| YGTek Webcam                                          | 2        | 0.76%   |
| Valve Software 3D Camera                              | 2        | 0.76%   |
| Trust USB Camera                                      | 2        | 0.76%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 2        | 0.76%   |
| Sunplus SPCA2281 Web Camera                           | 2        | 0.76%   |
| Sunplus FULL HD webcam                                | 2        | 0.76%   |
| Sunplus 1080P Webcam                                  | 2        | 0.76%   |
| SN0002 HIK 1080P USB CAMERA                           | 2        | 0.76%   |
| Ruision UVC Camera                                    | 2        | 0.76%   |
| Microdia Integrated Camera                            | 2        | 0.76%   |
| Microdia Camera                                       | 2        | 0.76%   |
| Microdia AUKEY-W1                                     | 2        | 0.76%   |
| Logitech Webcam C170                                  | 2        | 0.76%   |
| Logitech HD Webcam C510                               | 2        | 0.76%   |
| Logitech BRIO 4K Stream Edition                       | 2        | 0.76%   |
| Logitech B525 HD Webcam                               | 2        | 0.76%   |
| eMeet HD Webcam C960                                  | 2        | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |
| DigitalPersona        | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor               | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 33.33%  |
| DigitalPersona Fingerprint Reader           | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 2        | 50%     |
| SCM Microsystems      | 1        | 25%     |
| Advanced Card Systems | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 25%     |
| Alcor Micro Watchdata W 1981                           | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 25%     |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 905      | 81.97%  |
| 1     | 178      | 16.12%  |
| 2     | 18       | 1.63%   |
| 3     | 3        | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 71       | 33.18%  |
| Graphics card            | 63       | 29.44%  |
| Unassigned class         | 16       | 7.48%   |
| Bluetooth                | 14       | 6.54%   |
| Multimedia controller    | 9        | 4.21%   |
| Sound                    | 8        | 3.74%   |
| Net/ethernet             | 7        | 3.27%   |
| Communication controller | 7        | 3.27%   |
| Chipcard                 | 4        | 1.87%   |
| Storage/raid             | 3        | 1.4%    |
| Fingerprint reader       | 3        | 1.4%    |
| Camera                   | 3        | 1.4%    |
| Storage/nvme             | 2        | 0.93%   |
| Network                  | 2        | 0.93%   |
| Storage/ide              | 1        | 0.47%   |
| Firewire controller      | 1        | 0.47%   |

