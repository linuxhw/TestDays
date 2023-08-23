Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 5353

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
| ASUSTek       | P8B75-M                     | [df7a7f2c36](https://linux-hardware.org/?probe=df7a7f2c36) | Jul 13, 2023 |
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
| ASUSTek       | GA35DX                      | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
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
| ASUSTek       | P6T DELUXE V2               | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
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
| ASUSTek       | PRIME TRX40-PRO             | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
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
| ASUSTek       | SABERTOOTH X79              | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
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
| Supermicro    | X9SAE                       | [01195f072e](https://linux-hardware.org/?probe=01195f072e) | Mar 21, 2023 |
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
| Dell          | 0NNNCT A01                  | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
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
| ASUSTek       | TUF Gaming X570-PLUS        | [3221475cc8](https://linux-hardware.org/?probe=3221475cc8) | Jan 24, 2023 |
| MSI           | B450M MORTAR MAX            | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [75acbba6b1](https://linux-hardware.org/?probe=75acbba6b1) | Jan 23, 2023 |
| ASRock        | AM1H-ITX                    | [82b094a66b](https://linux-hardware.org/?probe=82b094a66b) | Jan 23, 2023 |
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
| Intel         | DP55WB AAE64798-206         | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
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
| Gigabyte      | B550I AORUS PRO AX          | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
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
| Intel         | X79M-S                      | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
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
| ASUSTek       | PRIME B450M-K               | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
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
| MSI           | 2AE0                        | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
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
| Positivo      | POS-EIH61CR POSITIVO        | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
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
| Colorful T... | A320M-K PRO YV14            | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 22.04 | 1084     | 28.65%  |
| Pop!_OS 20.04 | 861      | 22.76%  |
| Pop!_OS 21.04 | 719      | 19.01%  |
| Pop!_OS 20.10 | 672      | 17.76%  |
| Pop!_OS 21.10 | 421      | 11.13%  |
| Pop!_OS 19.10 | 15       | 0.4%    |
| Pop!_OS 19.04 | 6        | 0.16%   |
| Pop!_OS 18.04 | 4        | 0.11%   |
| Pop!_OS 18.10 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3568     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 340      | 8.28%   |
| 5.8.0-7630-generic       | 315      | 7.67%   |
| 6.2.6-76060206-generic   | 291      | 7.08%   |
| 5.4.0-7634-generic       | 281      | 6.84%   |
| 5.8.0-7642-generic       | 203      | 4.94%   |
| 5.13.0-7614-generic      | 203      | 4.94%   |
| 5.4.0-7642-generic       | 187      | 4.55%   |
| 5.11.0-7614-generic      | 181      | 4.41%   |
| 5.17.5-76051705-generic  | 179      | 4.36%   |
| 6.0.12-76060006-generic  | 175      | 4.26%   |
| 5.13.0-7620-generic      | 171      | 4.16%   |
| 5.19.0-76051900-generic  | 143      | 3.48%   |
| 5.16.11-76051611-generic | 112      | 2.73%   |
| 5.15.15-76051515-generic | 109      | 2.65%   |
| 6.0.6-76060006-generic   | 102      | 2.48%   |
| 5.15.5-76051505-generic  | 92       | 2.24%   |
| 5.11.0-7612-generic      | 87       | 2.12%   |
| 5.8.0-7625-generic       | 78       | 1.9%    |
| 5.18.10-76051810-generic | 75       | 1.83%   |
| 5.11.0-7633-generic      | 71       | 1.73%   |
| 5.17.15-76051715-generic | 69       | 1.68%   |
| 5.16.19-76051619-generic | 65       | 1.58%   |
| 5.15.8-76051508-generic  | 63       | 1.53%   |
| 5.16.15-76051615-generic | 56       | 1.36%   |
| 5.15.11-76051511-generic | 47       | 1.14%   |
| 5.4.0-7626-generic       | 43       | 1.05%   |
| 6.2.0-76060200-generic   | 37       | 0.9%    |
| 5.15.23-76051523-generic | 29       | 0.71%   |
| 6.1.11-76060111-generic  | 28       | 0.68%   |
| 6.0.2-76060002-generic   | 27       | 0.66%   |
| 5.4.0-7625-generic       | 24       | 0.58%   |
| 5.4.0-7629-generic       | 21       | 0.51%   |
| 5.19.16-76051916-generic | 18       | 0.44%   |
| 6.0.3-76060003-generic   | 14       | 0.34%   |
| 6.4.6-76060406-generic   | 10       | 0.24%   |
| 5.3.0-7629-generic       | 5        | 0.12%   |
| 5.3.0-7625-generic       | 5        | 0.12%   |
| 5.8.5-xanmod1            | 4        | 0.1%    |
| 5.8.5-050805-generic     | 4        | 0.1%    |
| 5.8.12-xanmod1           | 4        | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 651      | 16.2%   |
| 5.8.0   | 568      | 14.14%  |
| 5.4.0   | 537      | 13.36%  |
| 5.13.0  | 371      | 9.23%   |
| 6.2.6   | 291      | 7.24%   |
| 5.17.5  | 179      | 4.45%   |
| 6.0.12  | 178      | 4.43%   |
| 5.19.0  | 143      | 3.56%   |
| 5.16.11 | 112      | 2.79%   |
| 5.15.15 | 110      | 2.74%   |
| 6.0.6   | 103      | 2.56%   |
| 5.15.5  | 92       | 2.29%   |
| 5.18.10 | 75       | 1.87%   |
| 5.17.15 | 69       | 1.72%   |
| 5.16.19 | 65       | 1.62%   |
| 5.15.8  | 63       | 1.57%   |
| 5.16.15 | 56       | 1.39%   |
| 5.15.11 | 47       | 1.17%   |
| 6.2.0   | 37       | 0.92%   |
| 5.15.23 | 29       | 0.72%   |
| 6.1.11  | 28       | 0.7%    |
| 6.0.2   | 28       | 0.7%    |
| 5.19.16 | 18       | 0.45%   |
| 5.3.0   | 17       | 0.42%   |
| 6.0.3   | 14       | 0.35%   |
| 6.4.6   | 10       | 0.25%   |
| 5.8.5   | 8        | 0.2%    |
| 5.0.0   | 6        | 0.15%   |
| 5.8.12  | 5        | 0.12%   |
| 6.3.7   | 3        | 0.07%   |
| 6.1.0   | 3        | 0.07%   |
| 5.7.8   | 3        | 0.07%   |
| 5.7.0   | 3        | 0.07%   |
| 5.6.16  | 3        | 0.07%   |
| 5.15.0  | 3        | 0.07%   |
| 6.3.4   | 2        | 0.05%   |
| 5.9.1   | 2        | 0.05%   |
| 5.8.6   | 2        | 0.05%   |
| 5.8.18  | 2        | 0.05%   |
| 5.7.16  | 2        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 653      | 16.44%  |
| 5.8     | 590      | 14.85%  |
| 5.4     | 539      | 13.57%  |
| 5.13    | 376      | 9.47%   |
| 5.15    | 343      | 8.64%   |
| 6.2     | 325      | 8.18%   |
| 6.0     | 318      | 8.01%   |
| 5.17    | 246      | 6.19%   |
| 5.16    | 224      | 5.64%   |
| 5.19    | 161      | 4.05%   |
| 5.18    | 77       | 1.94%   |
| 6.1     | 34       | 0.86%   |
| 5.3     | 17       | 0.43%   |
| 5.7     | 14       | 0.35%   |
| 6.4     | 11       | 0.28%   |
| 5.6     | 8        | 0.2%    |
| 5.10    | 8        | 0.2%    |
| 6.3     | 6        | 0.15%   |
| 5.0     | 6        | 0.15%   |
| 5.9     | 5        | 0.13%   |
| 5.14    | 5        | 0.13%   |
| 5.12    | 4        | 0.1%    |
| 4.18    | 1        | 0.03%   |
| 4.15    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3568     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3447     | 95.99%  |
| KDE5            | 39       | 1.09%   |
| KDE             | 33       | 0.92%   |
| X-Cinnamon      | 19       | 0.53%   |
| Unknown         | 16       | 0.45%   |
| MATE            | 9        | 0.25%   |
| XFCE            | 8        | 0.22%   |
| GNOME Flashback | 5        | 0.14%   |
| Cinnamon        | 5        | 0.14%   |
| LXQt            | 3        | 0.08%   |
| i3              | 3        | 0.08%   |
| Budgie          | 2        | 0.06%   |
| Unity           | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3509     | 97.96%  |
| Wayland | 61       | 1.7%    |
| Tty     | 6        | 0.17%   |
| Unknown | 6        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3049     | 84.88%  |
| GDM     | 345      | 9.6%    |
| GDM3    | 183      | 5.09%   |
| SDDM    | 10       | 0.28%   |
| TDM     | 3        | 0.08%   |
| LightDM | 2        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2034     | 56.48%  |
| en_GB   | 273      | 7.58%   |
| pt_BR   | 258      | 7.16%   |
| de_DE   | 191      | 5.3%    |
| C       | 128      | 3.55%   |
| en_AU   | 107      | 2.97%   |
| en_CA   | 104      | 2.89%   |
| fr_FR   | 73       | 2.03%   |
| it_IT   | 45       | 1.25%   |
| ru_RU   | 43       | 1.19%   |
| es_ES   | 40       | 1.11%   |
| pl_PL   | 33       | 0.92%   |
| nl_NL   | 27       | 0.75%   |
| sv_SE   | 23       | 0.64%   |
| Unknown | 20       | 0.56%   |
| pt_PT   | 14       | 0.39%   |
| fi_FI   | 14       | 0.39%   |
| fr_CA   | 10       | 0.28%   |
| es_CL   | 10       | 0.28%   |
| es_AR   | 10       | 0.28%   |
| da_DK   | 10       | 0.28%   |
| en_DK   | 9        | 0.25%   |
| ja_JP   | 8        | 0.22%   |
| zh_TW   | 7        | 0.19%   |
| nl_BE   | 7        | 0.19%   |
| en_ZA   | 7        | 0.19%   |
| sk_SK   | 6        | 0.17%   |
| nb_NO   | 6        | 0.17%   |
| en_NZ   | 6        | 0.17%   |
| en_IN   | 6        | 0.17%   |
| es_MX   | 5        | 0.14%   |
| de_AT   | 5        | 0.14%   |
| cs_CZ   | 5        | 0.14%   |
| tr_TR   | 4        | 0.11%   |
| hu_HU   | 4        | 0.11%   |
| hr_HR   | 4        | 0.11%   |
| fr_CH   | 4        | 0.11%   |
| zh_CN   | 3        | 0.08%   |
| uk_UA   | 3        | 0.08%   |
| ro_RO   | 3        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2919     | 80.93%  |
| EFI  | 688      | 19.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3434     | 95.84%  |
| Overlay | 70       | 1.95%   |
| Btrfs   | 60       | 1.67%   |
| Xfs     | 8        | 0.22%   |
| Unknown | 6        | 0.17%   |
| Zfs     | 5        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3039     | 84.65%  |
| GPT     | 476      | 13.26%  |
| MBR     | 75       | 2.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3460     | 96.49%  |
| Yes       | 126      | 3.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3260     | 90.88%  |
| Yes       | 327      | 9.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1010     | 28.31%  |
| Gigabyte Technology | 695      | 19.48%  |
| MSI                 | 536      | 15.02%  |
| ASRock              | 354      | 9.92%   |
| Dell                | 272      | 7.62%   |
| Hewlett-Packard     | 181      | 5.07%   |
| Lenovo              | 89       | 2.49%   |
| Intel               | 66       | 1.85%   |
| System76            | 34       | 0.95%   |
| Acer                | 30       | 0.84%   |
| Pegatron            | 25       | 0.7%    |
| Unknown             | 23       | 0.64%   |
| Biostar             | 19       | 0.53%   |
| Alienware           | 19       | 0.53%   |
| Foxconn             | 18       | 0.5%    |
| Fujitsu             | 17       | 0.48%   |
| ECS                 | 15       | 0.42%   |
| Apple               | 15       | 0.42%   |
| Positivo            | 11       | 0.31%   |
| Huanan              | 11       | 0.31%   |
| Supermicro          | 10       | 0.28%   |
| Medion              | 10       | 0.28%   |
| BESSTAR Tech        | 9        | 0.25%   |
| PCWare              | 8        | 0.22%   |
| Gateway             | 7        | 0.2%    |
| MACHINIST           | 6        | 0.17%   |
| EVGA                | 6        | 0.17%   |
| Minix               | 5        | 0.14%   |
| AZW                 | 4        | 0.11%   |
| Samsung Electronics | 3        | 0.08%   |
| OEM                 | 3        | 0.08%   |
| NZXT                | 3        | 0.08%   |
| MAXSUN              | 3        | 0.08%   |
| TYAN Computer       | 2        | 0.06%   |
| T-bao               | 2        | 0.06%   |
| Shuttle             | 2        | 0.06%   |
| Packard Bell        | 2        | 0.06%   |
| Megaware            | 2        | 0.06%   |
| Login Informatica   | 2        | 0.06%   |
| Google              | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 88       | 2.47%   |
| ASUS TUF Gaming X570-PLUS      | 42       | 1.18%   |
| Gigabyte B450M DS3H            | 34       | 0.95%   |
| MSI MS-7C02                    | 31       | 0.87%   |
| ASUS ROG STRIX B450-F GAMING   | 30       | 0.84%   |
| MSI MS-7C37                    | 29       | 0.81%   |
| ASUS ROG STRIX B550-F GAMING   | 29       | 0.81%   |
| MSI MS-7B86                    | 28       | 0.78%   |
| Dell OptiPlex 9020             | 24       | 0.67%   |
| Unknown                        | 24       | 0.67%   |
| ASUS PRIME B450M-A             | 22       | 0.62%   |
| System76 Thelio                | 21       | 0.59%   |
| Gigabyte X570 AORUS ELITE      | 21       | 0.59%   |
| Gigabyte A320M-S2H             | 17       | 0.48%   |
| MSI MS-7C91                    | 16       | 0.45%   |
| Dell OptiPlex 7010             | 16       | 0.45%   |
| ASRock B450M Steel Legend      | 16       | 0.45%   |
| ASRock B450M Pro4              | 16       | 0.45%   |
| Gigabyte B450 AORUS PRO WIFI   | 14       | 0.39%   |
| Gigabyte B450 AORUS M          | 14       | 0.39%   |
| ASUS ROG STRIX B550-I GAMING   | 14       | 0.39%   |
| MSI MS-7B89                    | 13       | 0.36%   |
| Gigabyte X570 AORUS MASTER     | 13       | 0.36%   |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.36%   |
| MSI MS-7C84                    | 12       | 0.34%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.34%   |
| ASUS PRIME B450M-GAMING/BR     | 12       | 0.34%   |
| MSI MS-7B79                    | 11       | 0.31%   |
| MSI MS-7A38                    | 11       | 0.31%   |
| MSI MS-7817                    | 11       | 0.31%   |
| MSI MS-7693                    | 11       | 0.31%   |
| Gigabyte B75M-D3H              | 11       | 0.31%   |
| Dell OptiPlex 3020             | 11       | 0.31%   |
| Dell OptiPlex 3010             | 11       | 0.31%   |
| ASUS TUF Gaming X570-PRO       | 11       | 0.31%   |
| ASUS TUF Gaming B550-PLUS      | 11       | 0.31%   |
| ASUS ROG STRIX X570-E GAMING   | 11       | 0.31%   |
| ASUS ROG CROSSHAIR VIII HERO   | 11       | 0.31%   |
| MSI MS-7A34                    | 10       | 0.28%   |
| HP Compaq 8200 Elite SFF PC    | 10       | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 238      | 6.67%   |
| ASUS PRIME             | 186      | 5.21%   |
| Dell OptiPlex          | 150      | 4.2%    |
| ASUS TUF               | 130      | 3.64%   |
| ASUS All               | 88       | 2.47%   |
| Gigabyte X570          | 74       | 2.07%   |
| HP Compaq              | 58       | 1.63%   |
| Gigabyte B450          | 54       | 1.51%   |
| Lenovo ThinkCentre     | 50       | 1.4%    |
| Gigabyte B450M         | 49       | 1.37%   |
| Dell Precision         | 47       | 1.32%   |
| ASRock B450M           | 38       | 1.07%   |
| ASRock X570            | 35       | 0.98%   |
| System76 Thelio        | 34       | 0.95%   |
| Gigabyte B550          | 33       | 0.92%   |
| MSI MS-7C02            | 31       | 0.87%   |
| MSI MS-7C37            | 29       | 0.81%   |
| Dell Inspiron          | 29       | 0.81%   |
| MSI MS-7B86            | 28       | 0.78%   |
| Unknown                | 24       | 0.67%   |
| ASUS SABERTOOTH        | 23       | 0.64%   |
| ASRock B450            | 22       | 0.62%   |
| Gigabyte A320M-S2H     | 21       | 0.59%   |
| Dell XPS               | 21       | 0.59%   |
| HP EliteDesk           | 20       | 0.56%   |
| Acer Aspire            | 20       | 0.56%   |
| Gigabyte Z390          | 18       | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 18       | 0.5%    |
| ASUS M5A97             | 17       | 0.48%   |
| MSI MS-7C91            | 16       | 0.45%   |
| Gigabyte B550M         | 16       | 0.45%   |
| ASUS P8Z77-V           | 16       | 0.45%   |
| ASUS M5A78L-M          | 16       | 0.45%   |
| ASUS Crosshair         | 15       | 0.42%   |
| Lenovo IdeaCentre      | 14       | 0.39%   |
| MSI MS-7B89            | 13       | 0.36%   |
| MSI MS-7C84            | 12       | 0.34%   |
| HP ProDesk             | 12       | 0.34%   |
| HP OMEN                | 12       | 0.34%   |
| Gigabyte X470          | 12       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 568      | 15.92%  |
| 2019    | 419      | 11.74%  |
| 2020    | 414      | 11.6%   |
| 2012    | 285      | 7.99%   |
| 2017    | 256      | 7.17%   |
| 2013    | 249      | 6.98%   |
| 2011    | 209      | 5.86%   |
| 2014    | 201      | 5.63%   |
| 2021    | 183      | 5.13%   |
| 2015    | 151      | 4.23%   |
| 2016    | 139      | 3.9%    |
| 2010    | 135      | 3.78%   |
| 2009    | 118      | 3.31%   |
| 2022    | 92       | 2.58%   |
| 2008    | 70       | 1.96%   |
| 2007    | 53       | 1.49%   |
| 2023    | 12       | 0.34%   |
| 2006    | 12       | 0.34%   |
| 2005    | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3568     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3566     | 99.92%  |
| Enabled  | 3        | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3566     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1176     | 32.28%  |
| 32.01-64.0      | 791      | 21.71%  |
| 8.01-16.0       | 650      | 17.84%  |
| 4.01-8.0        | 346      | 9.5%    |
| 3.01-4.0        | 265      | 7.27%   |
| 64.01-256.0     | 242      | 6.64%   |
| 24.01-32.0      | 122      | 3.35%   |
| 1.01-2.0        | 30       | 0.82%   |
| 2.01-3.0        | 12       | 0.33%   |
| More than 256.0 | 8        | 0.22%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 1041     | 26.41%  |
| 4.01-8.0    | 929      | 23.57%  |
| 1.01-2.0    | 926      | 23.49%  |
| 3.01-4.0    | 708      | 17.96%  |
| 8.01-16.0   | 263      | 6.67%   |
| 16.01-24.0  | 36       | 0.91%   |
| 32.01-64.0  | 15       | 0.38%   |
| 24.01-32.0  | 14       | 0.36%   |
| 0.51-1.0    | 7        | 0.18%   |
| 64.01-256.0 | 3        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1201     | 32.51%  |
| 2      | 1107     | 29.97%  |
| 3      | 662      | 17.92%  |
| 4      | 396      | 10.72%  |
| 5      | 174      | 4.71%   |
| 6      | 73       | 1.98%   |
| 7      | 28       | 0.76%   |
| 0      | 18       | 0.49%   |
| 8      | 11       | 0.3%    |
| 11     | 7        | 0.19%   |
| 9      | 7        | 0.19%   |
| 10     | 3        | 0.08%   |
| 26     | 1        | 0.03%   |
| 23     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 19     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |
| 12     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2421     | 67.31%  |
| Yes       | 1176     | 32.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3522     | 98.68%  |
| No        | 47       | 1.32%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1919     | 53.22%  |
| No        | 1687     | 46.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2165     | 59.96%  |
| Yes       | 1446     | 40.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1240     | 34.56%  |
| Brazil       | 329      | 9.17%   |
| Germany      | 267      | 7.44%   |
| Canada       | 198      | 5.52%   |
| UK           | 197      | 5.49%   |
| Australia    | 130      | 3.62%   |
| Netherlands  | 82       | 2.29%   |
| France       | 80       | 2.23%   |
| Italy        | 79       | 2.2%    |
| Sweden       | 67       | 1.87%   |
| Poland       | 61       | 1.7%    |
| Russia       | 51       | 1.42%   |
| Spain        | 39       | 1.09%   |
| South Africa | 39       | 1.09%   |
| Finland      | 38       | 1.06%   |
| India        | 37       | 1.03%   |
| Mexico       | 30       | 0.84%   |
| Switzerland  | 29       | 0.81%   |
| Norway       | 29       | 0.81%   |
| Austria      | 29       | 0.81%   |
| Romania      | 28       | 0.78%   |
| Denmark      | 27       | 0.75%   |
| Greece       | 26       | 0.72%   |
| New Zealand  | 25       | 0.7%    |
| Portugal     | 24       | 0.67%   |
| Belgium      | 23       | 0.64%   |
| Argentina    | 23       | 0.64%   |
| Philippines  | 20       | 0.56%   |
| Czechia      | 17       | 0.47%   |
| Bulgaria     | 17       | 0.47%   |
| Japan        | 16       | 0.45%   |
| Hungary      | 16       | 0.45%   |
| Chile        | 16       | 0.45%   |
| Serbia       | 13       | 0.36%   |
| Malaysia     | 13       | 0.36%   |
| Ireland      | 13       | 0.36%   |
| Slovakia     | 12       | 0.33%   |
| Ukraine      | 11       | 0.31%   |
| Lithuania    | 11       | 0.31%   |
| Israel       | 11       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 41       | 1.1%    |
| Sydney         | 37       | 0.99%   |
| Berlin         | 27       | 0.72%   |
| Melbourne      | 25       | 0.67%   |
| Rio de Janeiro | 22       | 0.59%   |
| Brisbane       | 21       | 0.56%   |
| Miami          | 20       | 0.54%   |
| Helsinki       | 20       | 0.54%   |
| Vienna         | 17       | 0.46%   |
| Seattle        | 17       | 0.46%   |
| Chicago        | 16       | 0.43%   |
| Browning       | 16       | 0.43%   |
| Denver         | 15       | 0.4%    |
| Warsaw         | 14       | 0.38%   |
| Milan          | 14       | 0.38%   |
| Phoenix        | 13       | 0.35%   |
| Edmonton       | 13       | 0.35%   |
| Dallas         | 13       | 0.35%   |
| Toronto        | 12       | 0.32%   |
| Perth          | 12       | 0.32%   |
| Moscow         | 12       | 0.32%   |
| Montreal       | 12       | 0.32%   |
| London         | 12       | 0.32%   |
| Hamburg        | 12       | 0.32%   |
| Auckland       | 12       | 0.32%   |
| Amsterdam      | 12       | 0.32%   |
| Adelaide       | 12       | 0.32%   |
| Washington     | 11       | 0.3%    |
| St Louis       | 11       | 0.3%    |
| Sofia          | 11       | 0.3%    |
| Calgary        | 11       | 0.3%    |
| Athens         | 11       | 0.3%    |
| New York       | 10       | 0.27%   |
| Johannesburg   | 10       | 0.27%   |
| Cape Town      | 10       | 0.27%   |
| Brasília      | 10       | 0.27%   |
| Vancouver      | 9        | 0.24%   |
| Rome           | 9        | 0.24%   |
| Paris          | 9        | 0.24%   |
| Madrid         | 9        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1227     | 2095   | 17.42%  |
| Seagate                     | 1216     | 1902   | 17.27%  |
| WDC                         | 1160     | 1776   | 16.47%  |
| SanDisk                     | 443      | 592    | 6.29%   |
| Kingston                    | 434      | 572    | 6.16%   |
| Crucial                     | 327      | 462    | 4.64%   |
| Toshiba                     | 297      | 379    | 4.22%   |
| Hitachi                     | 173      | 239    | 2.46%   |
| Phison                      | 151      | 224    | 2.14%   |
| Intel                       | 146      | 210    | 2.07%   |
| A-DATA Technology           | 111      | 140    | 1.58%   |
| Micron/Crucial Technology   | 86       | 114    | 1.22%   |
| PNY                         | 82       | 107    | 1.16%   |
| Silicon Motion              | 80       | 111    | 1.14%   |
| China                       | 76       | 113    | 1.08%   |
| Unknown                     | 63       | 101    | 0.89%   |
| Phison Electronics          | 55       | 78     | 0.78%   |
| HGST                        | 52       | 69     | 0.74%   |
| SK hynix                    | 51       | 73     | 0.72%   |
| OCZ                         | 45       | 63     | 0.64%   |
| XPG                         | 39       | 52     | 0.55%   |
| SPCC                        | 37       | 51     | 0.53%   |
| Realtek Semiconductor       | 35       | 40     | 0.5%    |
| Micron Technology           | 35       | 50     | 0.5%    |
| Patriot                     | 32       | 45     | 0.45%   |
| Corsair                     | 32       | 44     | 0.45%   |
| Maxtor                      | 31       | 32     | 0.44%   |
| Team                        | 28       | 35     | 0.4%    |
| Intenso                     | 23       | 29     | 0.33%   |
| Kingston Technology Company | 18       | 21     | 0.26%   |
| Lexar                       | 17       | 20     | 0.24%   |
| Hewlett-Packard             | 16       | 24     | 0.23%   |
| JMicron Technology          | 15       | 25     | 0.21%   |
| Gigabyte Technology         | 15       | 15     | 0.21%   |
| Transcend                   | 14       | 17     | 0.2%    |
| KingSpec                    | 14       | 17     | 0.2%    |
| SABRENT                     | 13       | 14     | 0.18%   |
| Apacer                      | 13       | 16     | 0.18%   |
| ADATA Technology            | 13       | 14     | 0.18%   |
| GOODRAM                     | 12       | 13     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 131      | 1.6%    |
| Samsung NVMe SSD Drive 500GB                        | 117      | 1.43%   |
| Kingston SA400S37240G 240GB SSD                     | 113      | 1.38%   |
| Seagate ST2000DM008-2FR102 2TB                      | 102      | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB                      | 100      | 1.22%   |
| Samsung SSD 850 EVO 250GB                           | 94       | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 82       | 1%      |
| Samsung SSD 850 EVO 500GB                           | 80       | 0.98%   |
| Samsung SSD 860 EVO 1TB                             | 78       | 0.95%   |
| Samsung SSD 860 EVO 500GB                           | 77       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 69       | 0.84%   |
| Kingston SA400S37120G 120GB SSD                     | 69       | 0.84%   |
| SanDisk NVMe SSD Drive 1TB                          | 67       | 0.82%   |
| SanDisk NVMe SSD Drive 500GB                        | 66       | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 61       | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 54       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                         | 53       | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                      | 48       | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB                      | 47       | 0.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 47       | 0.57%   |
| Toshiba DT01ACA100 1TB                              | 44       | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 44       | 0.54%   |
| Phison NVMe SSD Drive 1TB                           | 43       | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                    | 40       | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                      | 39       | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 37       | 0.45%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 37       | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 36       | 0.44%   |
| Samsung SSD 860 EVO 250GB                           | 34       | 0.41%   |
| Toshiba HDWD110 1TB                                 | 31       | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB                      | 31       | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 31       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 30       | 0.37%   |
| Samsung SSD 870 QVO 1TB                             | 30       | 0.37%   |
| Toshiba DT01ACA200 2TB                              | 29       | 0.35%   |
| Seagate ST3500418AS 500GB                           | 29       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                      | 29       | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                        | 29       | 0.35%   |
| Samsung NVMe SSD Drive 2TB                          | 29       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                      | 28       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1181     | 1809   | 40.7%   |
| WDC                 | 1007     | 1510   | 34.7%   |
| Toshiba             | 266      | 339    | 9.17%   |
| Hitachi             | 173      | 239    | 5.96%   |
| Samsung Electronics | 114      | 140    | 3.93%   |
| HGST                | 52       | 69     | 1.79%   |
| Maxtor              | 27       | 28     | 0.93%   |
| Unknown             | 22       | 31     | 0.76%   |
| JMicron Technology  | 9        | 16     | 0.31%   |
| ASMT                | 8        | 9      | 0.28%   |
| Apple               | 8        | 10     | 0.28%   |
| Fujitsu             | 5        | 8      | 0.17%   |
| SABRENT             | 3        | 4      | 0.1%    |
| Hewlett-Packard     | 3        | 5      | 0.1%    |
| External            | 3        | 3      | 0.1%    |
| ExcelStor           | 3        | 3      | 0.1%    |
| USB                 | 2        | 3      | 0.07%   |
| Magnetic Data       | 2        | 2      | 0.07%   |
| LaCie               | 2        | 2      | 0.07%   |
| Unknown             | 2        | 3      | 0.07%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| OEM                 | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 2      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| Glyph               | 1        | 2      | 0.03%   |
| ASMT109x            | 1        | 1      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 688      | 1081   | 26.72%  |
| Kingston            | 366      | 478    | 14.21%  |
| Crucial             | 300      | 420    | 11.65%  |
| SanDisk             | 228      | 298    | 8.85%   |
| WDC                 | 176      | 227    | 6.83%   |
| A-DATA Technology   | 97       | 124    | 3.77%   |
| PNY                 | 81       | 106    | 3.15%   |
| China               | 75       | 112    | 2.91%   |
| Intel               | 62       | 86     | 2.41%   |
| OCZ                 | 44       | 59     | 1.71%   |
| SPCC                | 32       | 40     | 1.24%   |
| Patriot             | 32       | 45     | 1.24%   |
| SK hynix            | 27       | 41     | 1.05%   |
| Team                | 25       | 31     | 0.97%   |
| Corsair             | 25       | 31     | 0.97%   |
| Micron Technology   | 22       | 26     | 0.85%   |
| Toshiba             | 18       | 19     | 0.7%    |
| Seagate             | 18       | 33     | 0.7%    |
| Lexar               | 16       | 19     | 0.62%   |
| Intenso             | 16       | 22     | 0.62%   |
| Transcend           | 14       | 17     | 0.54%   |
| KingSpec            | 14       | 17     | 0.54%   |
| Apacer              | 13       | 16     | 0.5%    |
| Hewlett-Packard     | 12       | 18     | 0.47%   |
| GOODRAM             | 10       | 11     | 0.39%   |
| Gigabyte Technology | 10       | 10     | 0.39%   |
| Netac               | 9        | 10     | 0.35%   |
| LITEONIT            | 9        | 9      | 0.35%   |
| TO Exter            | 7        | 10     | 0.27%   |
| Plextor             | 7        | 9      | 0.27%   |
| Mushkin             | 7        | 9      | 0.27%   |
| LITEON              | 7        | 12     | 0.27%   |
| KingDian            | 5        | 7      | 0.19%   |
| Verbatim            | 4        | 8      | 0.16%   |
| OWC                 | 4        | 13     | 0.16%   |
| Maxtor              | 4        | 4      | 0.16%   |
| XPG                 | 3        | 4      | 0.12%   |
| PNY USB             | 3        | 10     | 0.12%   |
| Dogfish             | 3        | 4      | 0.12%   |
| Colorful            | 3        | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2262     | 4245   | 38.37%  |
| SSD     | 2084     | 3596   | 35.35%  |
| NVMe    | 1402     | 2344   | 23.78%  |
| Unknown | 131      | 210    | 2.22%   |
| MMC     | 16       | 20     | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3131     | 7578   | 64.76%  |
| NVMe | 1396     | 2326   | 28.87%  |
| SAS  | 292      | 491    | 6.04%   |
| MMC  | 16       | 20     | 0.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2271     | 3912   | 47.62%  |
| 0.51-1.0        | 1402     | 2212   | 29.4%   |
| 1.01-2.0        | 589      | 864    | 12.35%  |
| 3.01-4.0        | 202      | 332    | 4.24%   |
| 4.01-10.0       | 149      | 274    | 3.12%   |
| 2.01-3.0        | 137      | 200    | 2.87%   |
| 10.01-20.0      | 18       | 46     | 0.38%   |
| More than 100.0 | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 859      | 22.88%  |
| 501-1000       | 743      | 19.79%  |
| 251-500        | 737      | 19.63%  |
| 1001-2000      | 514      | 13.69%  |
| More than 3000 | 392      | 10.44%  |
| 2001-3000      | 217      | 5.78%   |
| 51-100         | 121      | 3.22%   |
| 1-20           | 89       | 2.37%   |
| 21-50          | 59       | 1.57%   |
| Unknown        | 24       | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1216     | 31%     |
| 21-50          | 663      | 16.9%   |
| 101-250        | 481      | 12.26%  |
| 51-100         | 414      | 10.55%  |
| 251-500        | 378      | 9.64%   |
| 501-1000       | 295      | 7.52%   |
| 1001-2000      | 224      | 5.71%   |
| More than 3000 | 145      | 3.7%    |
| 2001-3000      | 83       | 2.12%   |
| Unknown        | 24       | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4        | 4      | 2.61%   |
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 1.96%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 4      | 1.96%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 3      | 1.96%   |
| Samsung Electronics HD502HI 500GB     | 3        | 4      | 1.96%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 1.96%   |
| Kingston SA400S37120G 120GB SSD       | 3        | 5      | 1.96%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2        | 2      | 1.31%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2        | 2      | 1.31%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 1.31%   |
| Toshiba HDWD110 1TB                   | 2        | 2      | 1.31%   |
| Seagate ST3250310AS 250GB             | 2        | 3      | 1.31%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 1.31%   |
| Samsung Electronics SSD 850 EVO 250GB | 2        | 2      | 1.31%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 2      | 1.31%   |
| Hitachi HDP725050GLA360 500GB         | 2        | 2      | 1.31%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 2      | 1.31%   |
| China SSD 240GB                       | 2        | 2      | 1.31%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1        | 1      | 0.65%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1        | 1      | 0.65%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.65%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 1      | 0.65%   |
| WDC WD5001AALS-00J7B1 500GB           | 1        | 1      | 0.65%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1        | 2      | 0.65%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1        | 2      | 0.65%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 0.65%   |
| WDC WD5000AAKX-753CA1 500GB           | 1        | 1      | 0.65%   |
| WDC WD5000AAKS-41YGA1 500GB           | 1        | 1      | 0.65%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 0.65%   |
| WDC WD5000AADS-00M2B0 500GB           | 1        | 1      | 0.65%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 0.65%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1        | 1      | 0.65%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1        | 1      | 0.65%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 6      | 0.65%   |
| WDC WD2003FYYS-05T9B0 2TB             | 1        | 1      | 0.65%   |
| WDC WD15EVDS-73V9B0 1TB               | 1        | 1      | 0.65%   |
| WDC WD15EADS-11P8B1 1TB               | 1        | 1      | 0.65%   |
| WDC WD15EADS-00P8B0 1TB               | 1        | 1      | 0.65%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1        | 1      | 0.65%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1        | 1      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 43       | 52     | 29.05%  |
| WDC                         | 36       | 45     | 24.32%  |
| Samsung Electronics         | 21       | 27     | 14.19%  |
| Kingston                    | 8        | 12     | 5.41%   |
| Toshiba                     | 7        | 7      | 4.73%   |
| HGST                        | 6        | 6      | 4.05%   |
| Hitachi                     | 5        | 6      | 3.38%   |
| Crucial                     | 4        | 4      | 2.7%    |
| SanDisk                     | 2        | 2      | 1.35%   |
| Intel                       | 2        | 2      | 1.35%   |
| China                       | 2        | 2      | 1.35%   |
| Team                        | 1        | 1      | 0.68%   |
| SPCC                        | 1        | 1      | 0.68%   |
| SABRENT                     | 1        | 1      | 0.68%   |
| S3+                         | 1        | 1      | 0.68%   |
| Plextor                     | 1        | 1      | 0.68%   |
| Micron Technology           | 1        | 1      | 0.68%   |
| Maxtor                      | 1        | 1      | 0.68%   |
| Kingston Technology Company | 1        | 1      | 0.68%   |
| Intenso                     | 1        | 1      | 0.68%   |
| BAITITON                    | 1        | 1      | 0.68%   |
| ASMT                        | 1        | 1      | 0.68%   |
| A-DATA Technology           | 1        | 1      | 0.68%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 43       | 52     | 39.45%  |
| WDC                 | 36       | 45     | 33.03%  |
| Samsung Electronics | 10       | 11     | 9.17%   |
| Toshiba             | 7        | 7      | 6.42%   |
| HGST                | 6        | 6      | 5.5%    |
| Hitachi             | 5        | 6      | 4.59%   |
| Maxtor              | 1        | 1      | 0.92%   |
| ASMT                | 1        | 1      | 0.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 98       | 129    | 71.53%  |
| SSD  | 33       | 42     | 24.09%  |
| NVMe | 6        | 6      | 4.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 50%     |
| Patriot Pyro SSD 120GB          | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Patriot | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3079     | 8843   | 81.54%  |
| Works    | 565      | 1391   | 14.96%  |
| Malfunc  | 129      | 177    | 3.42%   |
| Failed   | 2        | 3      | 0.05%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1921     | 34.1%   |
| AMD                              | 1621     | 28.77%  |
| Samsung Electronics              | 617      | 10.95%  |
| SanDisk                          | 246      | 4.37%   |
| Phison Electronics               | 213      | 3.78%   |
| ASMedia Technology               | 210      | 3.73%   |
| Micron/Crucial Technology        | 114      | 2.02%   |
| Marvell Technology Group         | 90       | 1.6%    |
| Kingston Technology Company      | 90       | 1.6%    |
| Silicon Motion                   | 86       | 1.53%   |
| JMicron Technology               | 84       | 1.49%   |
| Nvidia                           | 62       | 1.1%    |
| ADATA Technology                 | 57       | 1.01%   |
| Realtek Semiconductor            | 45       | 0.8%    |
| SK hynix                         | 25       | 0.44%   |
| Broadcom / LSI                   | 23       | 0.41%   |
| Toshiba America Info Systems     | 16       | 0.28%   |
| Micron Technology                | 16       | 0.28%   |
| LSI Logic / Symbios Logic        | 16       | 0.28%   |
| Seagate Technology               | 15       | 0.27%   |
| VIA Technologies                 | 12       | 0.21%   |
| Lite-On Technology               | 9        | 0.16%   |
| Silicon Image                    | 6        | 0.11%   |
| Shenzhen Longsys Electronics     | 5        | 0.09%   |
| INNOGRIT                         | 5        | 0.09%   |
| Adaptec                          | 5        | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.07%   |
| Solidigm                         | 3        | 0.05%   |
| HighPoint Technologies           | 3        | 0.05%   |
| Union Memory (Shenzhen)          | 2        | 0.04%   |
| Silicon Integrated Systems [SiS] | 2        | 0.04%   |
| KIOXIA                           | 2        | 0.04%   |
| Hewlett-Packard                  | 2        | 0.04%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1066     | 15.43%  |
| AMD 400 Series Chipset SATA Controller                                                  | 452      | 6.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 388      | 5.62%   |
| AMD 500 Series Chipset SATA Controller                                                  | 246      | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 213      | 3.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 201      | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 168      | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 160      | 2.32%   |
| Intel SATA Controller [RAID mode]                                                       | 156      | 2.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 156      | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 135      | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 116      | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 113      | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 105      | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 103      | 1.49%   |
| Phison E12 NVMe Controller                                                              | 101      | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 82       | 1.19%   |
| AMD 300 Series Chipset SATA Controller                                                  | 82       | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 80       | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 77       | 1.11%   |
| AMD FCH SATA Controller D                                                               | 74       | 1.07%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 73       | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 70       | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 70       | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70       | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 67       | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 62       | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 54       | 0.78%   |
| Samsung NVMe SSD Controller 980                                                         | 53       | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 53       | 0.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 49       | 0.71%   |
| Intel SSD 660P Series                                                                   | 49       | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 49       | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 47       | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                         | 46       | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 45       | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 43       | 0.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 42       | 0.61%   |
| AMD X370 Series Chipset SATA Controller                                                 | 41       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3047     | 57.26%  |
| NVMe | 1398     | 26.27%  |
| IDE  | 573      | 10.77%  |
| RAID | 255      | 4.79%   |
| SAS  | 36       | 0.68%   |
| SCSI | 12       | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1892     | 53.03%  |
| AMD    | 1676     | 46.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 150      | 4.18%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 118      | 3.29%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 71       | 1.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 70       | 1.95%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 60       | 1.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 58       | 1.62%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 57       | 1.59%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 51       | 1.42%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 50       | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 48       | 1.34%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 45       | 1.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 43       | 1.2%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 43       | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 42       | 1.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 39       | 1.09%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 39       | 1.09%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 38       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 38       | 1.06%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 34       | 0.95%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 34       | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 34       | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 31       | 0.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 31       | 0.86%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 31       | 0.86%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 31       | 0.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 30       | 0.84%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 28       | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 27       | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 24       | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 24       | 0.67%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 24       | 0.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 23       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 23       | 0.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 22       | 0.61%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 22       | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 21       | 0.58%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 21       | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 20       | 0.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 20       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 582      | 16.23%  |
| AMD Ryzen 5             | 571      | 15.93%  |
| Intel Core i7           | 542      | 15.12%  |
| AMD Ryzen 7             | 392      | 10.93%  |
| AMD Ryzen 9             | 210      | 5.86%   |
| Intel Core i3           | 178      | 4.97%   |
| Intel Xeon              | 171      | 4.77%   |
| AMD FX                  | 129      | 3.6%    |
| Other                   | 91       | 2.54%   |
| AMD Ryzen 3             | 67       | 1.87%   |
| Intel Core 2 Duo        | 58       | 1.62%   |
| Intel Core i9           | 57       | 1.59%   |
| AMD Ryzen Threadripper  | 50       | 1.39%   |
| Intel Pentium           | 49       | 1.37%   |
| Intel Core 2 Quad       | 49       | 1.37%   |
| Intel Celeron           | 41       | 1.14%   |
| AMD Phenom II X4        | 34       | 0.95%   |
| Intel Pentium Dual-Core | 31       | 0.86%   |
| AMD A10                 | 28       | 0.78%   |
| AMD A8                  | 27       | 0.75%   |
| AMD Athlon II X2        | 24       | 0.67%   |
| AMD Athlon              | 18       | 0.5%    |
| Intel Core 2            | 16       | 0.45%   |
| AMD Athlon II X4        | 16       | 0.45%   |
| AMD A6                  | 15       | 0.42%   |
| AMD Phenom II X6        | 14       | 0.39%   |
| AMD A4                  | 12       | 0.33%   |
| Intel Atom              | 10       | 0.28%   |
| AMD Athlon 64 X2        | 10       | 0.28%   |
| AMD Ryzen 5 PRO         | 9        | 0.25%   |
| AMD Phenom              | 9        | 0.25%   |
| Intel Pentium Dual      | 8        | 0.22%   |
| AMD Athlon X4           | 8        | 0.22%   |
| Intel Pentium Gold      | 6        | 0.17%   |
| Intel Pentium D         | 6        | 0.17%   |
| AMD Sempron             | 5        | 0.14%   |
| AMD Ryzen 7 PRO         | 4        | 0.11%   |
| AMD Ryzen 3 PRO         | 4        | 0.11%   |
| AMD Athlon II X3        | 4        | 0.11%   |
| AMD Athlon 64           | 4        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1336     | 37.28%  |
| 6      | 753      | 21.01%  |
| 8      | 543      | 15.15%  |
| 2      | 498      | 13.9%   |
| 12     | 175      | 4.88%   |
| 16     | 102      | 2.85%   |
| 3      | 53       | 1.48%   |
| 10     | 41       | 1.14%   |
| 1      | 31       | 0.86%   |
| 24     | 20       | 0.56%   |
| 32     | 16       | 0.45%   |
| 14     | 9        | 0.25%   |
| 64     | 4        | 0.11%   |
| 36     | 1        | 0.03%   |
| 28     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3529     | 98.91%  |
| 2      | 39       | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2452     | 68.59%  |
| 1      | 1123     | 31.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3564     | 99.89%  |
| Unknown        | 4        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2632     | 72.13%  |
| 0x08701021 | 108      | 2.96%   |
| 0x306c3    | 77       | 2.11%   |
| 0x0800820d | 75       | 2.06%   |
| 0x08701013 | 73       | 2%      |
| 0x306a9    | 63       | 1.73%   |
| 0x206a7    | 50       | 1.37%   |
| 0x506e3    | 42       | 1.15%   |
| 0x906ea    | 38       | 1.04%   |
| 0x906e9    | 30       | 0.82%   |
| 0x08001138 | 28       | 0.77%   |
| 0x1067a    | 27       | 0.74%   |
| 0x0a201016 | 26       | 0.71%   |
| 0x08108109 | 25       | 0.69%   |
| 0x06000852 | 25       | 0.69%   |
| 0x906ec    | 15       | 0.41%   |
| 0x0a201009 | 15       | 0.41%   |
| 0x906ed    | 14       | 0.38%   |
| 0x08301039 | 14       | 0.38%   |
| 0x0a601203 | 12       | 0.33%   |
| 0xa0655    | 11       | 0.3%    |
| 0x08001137 | 11       | 0.3%    |
| 0x06001119 | 11       | 0.3%    |
| 0x010000c8 | 10       | 0.27%   |
| 0x306f2    | 9        | 0.25%   |
| 0x106a5    | 9        | 0.25%   |
| 0x06003106 | 9        | 0.25%   |
| 0xa0653    | 8        | 0.22%   |
| 0x206c2    | 8        | 0.22%   |
| 0xa0671    | 7        | 0.19%   |
| 0x906eb    | 7        | 0.19%   |
| 0x90672    | 6        | 0.16%   |
| 0x6fd      | 6        | 0.16%   |
| 0x206d7    | 6        | 0.16%   |
| 0x20655    | 6        | 0.16%   |
| 0x0a50000c | 6        | 0.16%   |
| 0x0a20120a | 6        | 0.16%   |
| 0x08101016 | 6        | 0.16%   |
| 0x6fb      | 5        | 0.14%   |
| 0x010000dc | 5        | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 516      | 14.41%  |
| Haswell          | 371      | 10.36%  |
| KabyLake         | 318      | 8.88%   |
| Zen 3            | 305      | 8.52%   |
| Zen+             | 278      | 7.76%   |
| IvyBridge        | 250      | 6.98%   |
| SandyBridge      | 226      | 6.31%   |
| Zen              | 182      | 5.08%   |
| Skylake          | 180      | 5.03%   |
| Piledriver       | 153      | 4.27%   |
| Penryn           | 116      | 3.24%   |
| Unknown          | 113      | 3.16%   |
| K10              | 111      | 3.1%    |
| CometLake        | 93       | 2.6%    |
| Nehalem          | 76       | 2.12%   |
| Westmere         | 60       | 1.68%   |
| Core             | 58       | 1.62%   |
| Steamroller      | 27       | 0.75%   |
| Silvermont       | 21       | 0.59%   |
| K8 Hammer        | 18       | 0.5%    |
| Excavator        | 16       | 0.45%   |
| Alderlake Hybrid | 15       | 0.42%   |
| Bulldozer        | 14       | 0.39%   |
| K10 Llano        | 13       | 0.36%   |
| Broadwell        | 10       | 0.28%   |
| NetBurst         | 9        | 0.25%   |
| Jaguar           | 7        | 0.2%    |
| Icelake          | 7        | 0.2%    |
| Goldmont plus    | 7        | 0.2%    |
| Goldmont         | 4        | 0.11%   |
| Bobcat           | 4        | 0.11%   |
| Bonnell          | 2        | 0.06%   |
| Puma             | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1871     | 48.53%  |
| AMD                              | 1309     | 33.96%  |
| Intel                            | 668      | 17.33%  |
| Matrox Electronics Systems       | 5        | 0.13%   |
| Silicon Integrated Systems [SiS] | 2        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 259      | 6.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 130      | 3.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 120      | 3%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 111      | 2.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 83       | 2.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 81       | 2.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 79       | 1.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 70       | 1.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 68       | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 66       | 1.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 64       | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 62       | 1.55%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 58       | 1.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 54       | 1.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 52       | 1.3%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 51       | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 50       | 1.25%   |
| Intel HD Graphics 530                                                       | 48       | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 45       | 1.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 44       | 1.1%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 43       | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 43       | 1.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 42       | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 40       | 1%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 39       | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 36       | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 36       | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 35       | 0.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 33       | 0.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 33       | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 32       | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 32       | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 31       | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                  | 31       | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 30       | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 30       | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 30       | 0.75%   |
| AMD Raphael                                                                 | 30       | 0.75%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 28       | 0.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 28       | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1719     | 47.43%  |
| 1 x AMD              | 1168     | 32.23%  |
| 1 x Intel            | 486      | 13.41%  |
| 2 x AMD              | 62       | 1.71%   |
| Intel + Nvidia       | 56       | 1.55%   |
| AMD + Nvidia         | 54       | 1.49%   |
| 2 x Nvidia           | 36       | 0.99%   |
| Intel + AMD          | 28       | 0.77%   |
| 1 x Matrox           | 4        | 0.11%   |
| 1 x SiS              | 2        | 0.06%   |
| Intel + 2 x Nvidia   | 2        | 0.06%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1890     | 52.15%  |
| Proprietary | 1524     | 42.05%  |
| Unknown     | 210      | 5.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1988     | 54.36%  |
| 7.01-8.0   | 469      | 12.82%  |
| 1.01-2.0   | 301      | 8.23%   |
| 3.01-4.0   | 292      | 7.98%   |
| 5.01-6.0   | 243      | 6.64%   |
| 8.01-16.0  | 152      | 4.16%   |
| 0.51-1.0   | 87       | 2.38%   |
| 2.01-3.0   | 48       | 1.31%   |
| 0.01-0.5   | 48       | 1.31%   |
| 16.01-24.0 | 24       | 0.66%   |
| 4.01-5.0   | 3        | 0.08%   |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 639      | 16.16%  |
| Goldstar             | 446      | 11.28%  |
| Dell                 | 438      | 11.07%  |
| Acer                 | 354      | 8.95%   |
| Hewlett-Packard      | 248      | 6.27%   |
| AOC                  | 231      | 5.84%   |
| Ancor Communications | 188      | 4.75%   |
| BenQ                 | 179      | 4.53%   |
| ASUSTek Computer     | 140      | 3.54%   |
| Philips              | 117      | 2.96%   |
| ViewSonic            | 68       | 1.72%   |
| Iiyama               | 63       | 1.59%   |
| Lenovo               | 62       | 1.57%   |
| MSI                  | 53       | 1.34%   |
| Sony                 | 51       | 1.29%   |
| Sceptre Tech         | 42       | 1.06%   |
| Vizio                | 32       | 0.81%   |
| Gigabyte Technology  | 29       | 0.73%   |
| Toshiba              | 25       | 0.63%   |
| Unknown              | 23       | 0.58%   |
| Panasonic            | 20       | 0.51%   |
| Eizo                 | 18       | 0.46%   |
| Insignia             | 17       | 0.43%   |
| NEC Computers        | 16       | 0.4%    |
| Fujitsu Siemens      | 16       | 0.4%    |
| LG Electronics       | 14       | 0.35%   |
| MStar                | 13       | 0.33%   |
| Hitachi              | 13       | 0.33%   |
| Vestel Elektronik    | 11       | 0.28%   |
| HannStar             | 10       | 0.25%   |
| ONN                  | 9        | 0.23%   |
| Mi                   | 9        | 0.23%   |
| Viotek               | 8        | 0.2%    |
| Videoseven           | 8        | 0.2%    |
| Sharp                | 8        | 0.2%    |
| Pixio                | 8        | 0.2%    |
| Medion               | 8        | 0.2%    |
| HKC                  | 8        | 0.2%    |
| CVT                  | 8        | 0.2%    |
| ___                  | 7        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 43       | 1.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 32       | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 25       | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 19       | 0.45%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 19       | 0.45%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 16       | 0.38%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 16       | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 15       | 0.36%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 13       | 0.31%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 13       | 0.31%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 13       | 0.31%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 13       | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.29%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 12       | 0.29%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 12       | 0.29%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 11       | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 11       | 0.26%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 11       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 11       | 0.26%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 10       | 0.24%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 10       | 0.24%   |
| Acer V246HQL ACR0424 1920x1080 520x290mm 23.4-inch                    | 10       | 0.24%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 9        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9        | 0.21%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 9        | 0.21%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 9        | 0.21%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 9        | 0.21%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 9        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 9        | 0.21%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 9        | 0.21%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 8        | 0.19%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 8        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 8        | 0.19%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 8        | 0.19%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch     | 8        | 0.19%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 8        | 0.19%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch               | 8        | 0.19%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 8        | 0.19%   |
| AOC G2460 AOC0001 1920x1080 531x299mm 24.0-inch                       | 8        | 0.19%   |
| AOC 2770 AOC2770 1920x1080 598x336mm 27.0-inch                        | 8        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1727     | 45.75%  |
| 3840x2160 (4K)     | 482      | 12.77%  |
| 2560x1440 (QHD)    | 393      | 10.41%  |
| 3440x1440          | 148      | 3.92%   |
| 1680x1050 (WSXGA+) | 148      | 3.92%   |
| 1280x1024 (SXGA)   | 141      | 3.74%   |
| 1366x768 (WXGA)    | 129      | 3.42%   |
| 2560x1080          | 119      | 3.15%   |
| 1440x900 (WXGA+)   | 88       | 2.33%   |
| 1920x1200 (WUXGA)  | 87       | 2.3%    |
| 1600x900 (HD+)     | 79       | 2.09%   |
| 1360x768           | 46       | 1.22%   |
| 3840x1080          | 33       | 0.87%   |
| 1920x540           | 32       | 0.85%   |
| Unknown            | 28       | 0.74%   |
| 3840x1600          | 15       | 0.4%    |
| 1024x768 (XGA)     | 12       | 0.32%   |
| 1600x1200          | 11       | 0.29%   |
| 1280x720 (HD)      | 11       | 0.29%   |
| 2560x1600          | 8        | 0.21%   |
| 4480x1440          | 4        | 0.11%   |
| 2048x1152          | 4        | 0.11%   |
| 5120x1440          | 2        | 0.05%   |
| 3840x1200          | 2        | 0.05%   |
| 2288x1287          | 2        | 0.05%   |
| 9840x3840          | 1        | 0.03%   |
| 8320x2160          | 1        | 0.03%   |
| 8160x4627          | 1        | 0.03%   |
| 7680x2160          | 1        | 0.03%   |
| 6400x1440          | 1        | 0.03%   |
| 5280x1080          | 1        | 0.03%   |
| 5200x2160          | 1        | 0.03%   |
| 4096x2160          | 1        | 0.03%   |
| 4080x2030          | 1        | 0.03%   |
| 4080x2026          | 1        | 0.03%   |
| 3360x1080          | 1        | 0.03%   |
| 3280x2048          | 1        | 0.03%   |
| 3280x1080          | 1        | 0.03%   |
| 3040x900           | 1        | 0.03%   |
| 2960x1050          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 685      | 17.32%  |
| 24      | 611      | 15.45%  |
| 23      | 474      | 11.99%  |
| 21      | 373      | 9.43%   |
| 31      | 246      | 6.22%   |
| 34      | 223      | 5.64%   |
| 19      | 157      | 3.97%   |
| Unknown | 132      | 3.34%   |
| 18      | 111      | 2.81%   |
| 22      | 110      | 2.78%   |
| 20      | 87       | 2.2%    |
| 84      | 82       | 2.07%   |
| 17      | 73       | 1.85%   |
| 32      | 65       | 1.64%   |
| 72      | 62       | 1.57%   |
| 15      | 50       | 1.26%   |
| 40      | 35       | 0.89%   |
| 54      | 34       | 0.86%   |
| 26      | 29       | 0.73%   |
| 48      | 28       | 0.71%   |
| 25      | 27       | 0.68%   |
| 28      | 23       | 0.58%   |
| 35      | 21       | 0.53%   |
| 65      | 20       | 0.51%   |
| 52      | 18       | 0.46%   |
| 49      | 18       | 0.46%   |
| 37      | 17       | 0.43%   |
| 29      | 16       | 0.4%    |
| 46      | 12       | 0.3%    |
| 36      | 12       | 0.3%    |
| 33      | 11       | 0.28%   |
| 47      | 9        | 0.23%   |
| 42      | 9        | 0.23%   |
| 74      | 7        | 0.18%   |
| 43      | 6        | 0.15%   |
| 38      | 6        | 0.15%   |
| 12      | 6        | 0.15%   |
| 55      | 5        | 0.13%   |
| 57      | 4        | 0.1%    |
| 44      | 4        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1583     | 41.91%  |
| 401-500        | 738      | 19.54%  |
| 601-700        | 371      | 9.82%   |
| 701-800        | 303      | 8.02%   |
| 1001-1500      | 163      | 4.32%   |
| 1501-2000      | 155      | 4.1%    |
| Unknown        | 132      | 3.49%   |
| 301-350        | 112      | 2.97%   |
| 351-400        | 99       | 2.62%   |
| 801-900        | 87       | 2.3%    |
| 901-1000       | 19       | 0.5%    |
| 201-300        | 14       | 0.37%   |
| More than 2000 | 1        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2525     | 72.14%  |
| 16/10   | 386      | 11.03%  |
| 21/9    | 274      | 7.83%   |
| 5/4     | 138      | 3.94%   |
| Unknown | 78       | 2.23%   |
| 4/3     | 38       | 1.09%   |
| 32/9    | 37       | 1.06%   |
| 3/2     | 9        | 0.26%   |
| 6/5     | 7        | 0.2%    |
| 1.96    | 5        | 0.14%   |
| 3.20    | 2        | 0.06%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1222     | 31.75%  |
| 301-350        | 703      | 18.26%  |
| 351-500        | 572      | 14.86%  |
| 151-200        | 352      | 9.15%   |
| More than 1000 | 258      | 6.7%    |
| 251-300        | 236      | 6.13%   |
| 141-150        | 151      | 3.92%   |
| 501-1000       | 149      | 3.87%   |
| Unknown        | 132      | 3.43%   |
| 101-110        | 39       | 1.01%   |
| 71-80          | 8        | 0.21%   |
| 131-140        | 8        | 0.21%   |
| 111-120        | 6        | 0.16%   |
| 91-100         | 6        | 0.16%   |
| 51-60          | 4        | 0.1%    |
| 121-130        | 3        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2211     | 61.54%  |
| 101-120       | 779      | 21.68%  |
| 1-50          | 196      | 5.46%   |
| 121-160       | 193      | 5.37%   |
| Unknown       | 132      | 3.67%   |
| 161-240       | 81       | 2.25%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2533     | 69.32%  |
| 2     | 770      | 21.07%  |
| 0     | 242      | 6.62%   |
| 3     | 97       | 2.65%   |
| 4     | 10       | 0.27%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 2123     | 40.21%  |
| Intel                                 | 1733     | 32.82%  |
| Qualcomm Atheros                      | 307      | 5.81%   |
| Broadcom                              | 178      | 3.37%   |
| TP-Link                               | 103      | 1.95%   |
| Ralink Technology                     | 101      | 1.91%   |
| Microsoft                             | 67       | 1.27%   |
| MediaTek                              | 58       | 1.1%    |
| Nvidia                                | 50       | 0.95%   |
| Ralink                                | 49       | 0.93%   |
| Samsung Electronics                   | 45       | 0.85%   |
| NetGear                               | 39       | 0.74%   |
| InterBiometrics                       | 36       | 0.68%   |
| Qualcomm Atheros Communications       | 35       | 0.66%   |
| Aquantia                              | 33       | 0.63%   |
| Marvell Technology Group              | 24       | 0.45%   |
| Xiaomi                                | 22       | 0.42%   |
| Google                                | 22       | 0.42%   |
| D-Link                                | 19       | 0.36%   |
| Linksys                               | 18       | 0.34%   |
| Huawei Technologies                   | 17       | 0.32%   |
| Broadcom Limited                      | 16       | 0.3%    |
| ASIX Electronics                      | 15       | 0.28%   |
| ASUSTek Computer                      | 13       | 0.25%   |
| D-Link System                         | 11       | 0.21%   |
| Edimax Technology                     | 9        | 0.17%   |
| Belkin Components                     | 9        | 0.17%   |
| OPPO Electronics                      | 8        | 0.15%   |
| OnePlus Technology (Shenzhen)         | 8        | 0.15%   |
| Motorola PCS                          | 7        | 0.13%   |
| DisplayLink                           | 6        | 0.11%   |
| AVM                                   | 6        | 0.11%   |
| VIA Technologies                      | 5        | 0.09%   |
| Sitecom Europe                        | 5        | 0.09%   |
| Mellanox Technologies                 | 5        | 0.09%   |
| Gemtek                                | 5        | 0.09%   |
| Mercucys                              | 4        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.08%   |
| Qualcomm                              | 3        | 0.06%   |
| Microchip Technology                  | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1632     | 26.55%  |
| Intel I211 Gigabit Network Connection                             | 417      | 6.78%   |
| Intel Wi-Fi 6 AX200                                               | 359      | 5.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 255      | 4.15%   |
| Intel Ethernet Controller I225-V                                  | 152      | 2.47%   |
| Intel Ethernet Connection (2) I219-V                              | 151      | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 129      | 2.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 102      | 1.66%   |
| Intel Wireless-AC 9260                                            | 100      | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 90       | 1.46%   |
| Intel Ethernet Connection I217-LM                                 | 80       | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 63       | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 58       | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 54       | 0.88%   |
| Realtek 802.11ac NIC                                              | 53       | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 51       | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 47       | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45       | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 45       | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 44       | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 43       | 0.7%    |
| Microsoft Xbox Wireless Adapter for Windows                       | 42       | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 42       | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 40       | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 39       | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 37       | 0.6%    |
| InterBiometrics Io                                                | 35       | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32       | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 30       | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                   | 29       | 0.47%   |
| Intel Wireless 7265                                               | 29       | 0.47%   |
| Intel Wireless 8265 / 8275                                        | 28       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27       | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 27       | 0.44%   |
| Microsoft Xbox 360 Wireless Adapter                               | 26       | 0.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 26       | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 26       | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24       | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 24       | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 838      | 40.54%  |
| Realtek Semiconductor                 | 404      | 19.55%  |
| Qualcomm Atheros                      | 158      | 7.64%   |
| Broadcom                              | 108      | 5.22%   |
| Ralink Technology                     | 101      | 4.89%   |
| TP-Link                               | 98       | 4.74%   |
| Microsoft                             | 67       | 3.24%   |
| MediaTek                              | 54       | 2.61%   |
| Ralink                                | 49       | 2.37%   |
| NetGear                               | 39       | 1.89%   |
| Qualcomm Atheros Communications       | 35       | 1.69%   |
| D-Link                                | 18       | 0.87%   |
| Linksys                               | 17       | 0.82%   |
| ASUSTek Computer                      | 13       | 0.63%   |
| Edimax Technology                     | 9        | 0.44%   |
| Belkin Components                     | 9        | 0.44%   |
| D-Link System                         | 7        | 0.34%   |
| Broadcom Limited                      | 6        | 0.29%   |
| AVM                                   | 6        | 0.29%   |
| Sitecom Europe                        | 5        | 0.24%   |
| Gemtek                                | 5        | 0.24%   |
| Mercucys                              | 4        | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.19%   |
| IMC Networks                          | 3        | 0.15%   |
| ZyDAS                                 | 1        | 0.05%   |
| Wilocity                              | 1        | 0.05%   |
| Wacom                                 | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Texas Instruments                     | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| Ovislink                              | 1        | 0.05%   |
| Micro Star International              | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |
| Accton Technology                     | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 359      | 17.18%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 102      | 4.88%   |
| Intel Wireless-AC 9260                                         | 100      | 4.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 63       | 3.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 58       | 2.78%   |
| Realtek 802.11ac NIC                                           | 53       | 2.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 51       | 2.44%   |
| Ralink MT7601U Wireless Adapter                                | 44       | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 43       | 2.06%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 42       | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 42       | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32       | 1.53%   |
| Qualcomm Atheros AR9271 802.11n                                | 29       | 1.39%   |
| Intel Wireless 7265                                            | 29       | 1.39%   |
| Intel Wireless 8265 / 8275                                     | 28       | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 27       | 1.29%   |
| Microsoft Xbox 360 Wireless Adapter                            | 26       | 1.24%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 26       | 1.24%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24       | 1.15%   |
| Intel Wireless 7260                                            | 23       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22       | 1.05%   |
| Intel Wireless 8260                                            | 22       | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 22       | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 21       | 1%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 21       | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 21       | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 17       | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 17       | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17       | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17       | 0.81%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16       | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 15       | 0.72%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15       | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 14       | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 14       | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14       | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 13       | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13       | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1964     | 50.85%  |
| Intel                            | 1366     | 35.37%  |
| Qualcomm Atheros                 | 162      | 4.19%   |
| Broadcom                         | 77       | 1.99%   |
| Nvidia                           | 50       | 1.29%   |
| Aquantia                         | 33       | 0.85%   |
| Samsung Electronics              | 27       | 0.7%    |
| Marvell Technology Group         | 24       | 0.62%   |
| Xiaomi                           | 22       | 0.57%   |
| Google                           | 22       | 0.57%   |
| Huawei Technologies              | 17       | 0.44%   |
| ASIX Electronics                 | 15       | 0.39%   |
| Broadcom Limited                 | 10       | 0.26%   |
| OPPO Electronics                 | 8        | 0.21%   |
| DisplayLink                      | 6        | 0.16%   |
| VIA Technologies                 | 5        | 0.13%   |
| TP-Link                          | 5        | 0.13%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.13%   |
| Motorola PCS                     | 5        | 0.13%   |
| Mellanox Technologies            | 4        | 0.1%    |
| MediaTek                         | 4        | 0.1%    |
| D-Link System                    | 4        | 0.1%    |
| Qualcomm                         | 3        | 0.08%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.05%   |
| Lenovo                           | 2        | 0.05%   |
| ICS Advent                       | 2        | 0.05%   |
| 3Com                             | 2        | 0.05%   |
| Tehuti Networks                  | 1        | 0.03%   |
| T & A Mobile Phones              | 1        | 0.03%   |
| Solarflare Communications        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| QLogic                           | 1        | 0.03%   |
| Netchip Technology               | 1        | 0.03%   |
| Linksys                          | 1        | 0.03%   |
| LG Electronics                   | 1        | 0.03%   |
| JMicron Technology               | 1        | 0.03%   |
| HMD Global                       | 1        | 0.03%   |
| Hangzhou Silan Microelectronics  | 1        | 0.03%   |
| Emulex                           | 1        | 0.03%   |
| D-Link                           | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1632     | 41.13%  |
| Intel I211 Gigabit Network Connection                             | 417      | 10.51%  |
| Realtek RTL8125 2.5GbE Controller                                 | 255      | 6.43%   |
| Intel Ethernet Controller I225-V                                  | 152      | 3.83%   |
| Intel Ethernet Connection (2) I219-V                              | 151      | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 129      | 3.25%   |
| Intel Ethernet Connection (7) I219-V                              | 90       | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 80       | 2.02%   |
| Intel 82579V Gigabit Network Connection                           | 54       | 1.36%   |
| Intel Ethernet Connection (2) I218-V                              | 47       | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45       | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 45       | 1.13%   |
| Intel Ethernet Connection I217-V                                  | 40       | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 39       | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 37       | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 30       | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27       | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 26       | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24       | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 24       | 0.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24       | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 23       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22       | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 16       | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 16       | 0.4%    |
| Huawei WLZ-AN00                                                   | 15       | 0.38%   |
| Google Nexus/Pixel Device (tether)                                | 15       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.35%   |
| Intel 82578DM Gigabit Network Connection                          | 13       | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.33%   |
| Intel Ethernet Connection (2) I218-LM                             | 12       | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 12       | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11       | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10       | 0.25%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10       | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 9        | 0.23%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 9        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3523     | 63.7%   |
| WiFi     | 1921     | 34.73%  |
| Modem    | 73       | 1.32%   |
| Unknown  | 14       | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2682     | 71.01%  |
| WiFi     | 1090     | 28.86%  |
| Modem    | 3        | 0.08%   |
| Unknown  | 2        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2072     | 57.68%  |
| 2     | 1274     | 35.47%  |
| 3     | 178      | 4.96%   |
| 0     | 35       | 0.97%   |
| 4     | 23       | 0.64%   |
| 5     | 6        | 0.17%   |
| 10    | 2        | 0.06%   |
| 6     | 2        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2820     | 77.49%  |
| Yes  | 819      | 22.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 775      | 52.58%  |
| Cambridge Silicon Radio         | 290      | 19.67%  |
| ASUSTek Computer                | 85       | 5.77%   |
| Realtek Semiconductor           | 80       | 5.43%   |
| Broadcom                        | 62       | 4.21%   |
| Qualcomm Atheros Communications | 47       | 3.19%   |
| MediaTek                        | 33       | 2.24%   |
| Apple                           | 28       | 1.9%    |
| TP-Link                         | 12       | 0.81%   |
| IMC Networks                    | 9        | 0.61%   |
| Foxconn / Hon Hai               | 9        | 0.61%   |
| Dynex                           | 8        | 0.54%   |
| Lite-On Technology              | 4        | 0.27%   |
| Integrated System Solution      | 4        | 0.27%   |
| HTC (High Tech Computer)        | 4        | 0.27%   |
| Actions                         | 3        | 0.2%    |
| SINO WEALTH                     | 2        | 0.14%   |
| Realtek                         | 2        | 0.14%   |
| Ralink                          | 2        | 0.14%   |
| Logitech                        | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Dell                            | 2        | 0.14%   |
| Creative Technology             | 2        | 0.14%   |
| Conwise Technology              | 2        | 0.14%   |
| Belkin Components               | 2        | 0.14%   |
| Primax Electronics              | 1        | 0.07%   |
| Micro Star International        | 1        | 0.07%   |
| Edimax Technology               | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 334      | 22.6%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 290      | 19.62%  |
| Intel Bluetooth wireless interface                                   | 101      | 6.83%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 99       | 6.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 95       | 6.43%   |
| Realtek Bluetooth Radio                                              | 52       | 3.52%   |
| Intel AX201 Bluetooth                                                | 48       | 3.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 46       | 3.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 45       | 3.04%   |
| Intel AX210 Bluetooth                                                | 37       | 2.5%    |
| MediaTek Wireless_Device                                             | 33       | 2.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 30       | 2.03%   |
| Qualcomm Atheros  Bluetooth Device                                   | 25       | 1.69%   |
| ASUS Bluetooth Radio                                                 | 23       | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 19       | 1.29%   |
| Apple Bluetooth USB Host Controller                                  | 15       | 1.01%   |
| Intel Bluetooth Device                                               | 13       | 0.88%   |
| TP-Link UB500 Adapter                                                | 12       | 0.81%   |
| ASUS ASUS USB-BT500                                                  | 9        | 0.61%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 8        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.47%   |
| IMC Networks Bluetooth Radio                                         | 7        | 0.47%   |
| ASUS BCM20702A0                                                      | 7        | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 7        | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.41%   |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.34%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 5        | 0.34%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 5        | 0.34%   |
| Apple Bluetooth HCI                                                  | 5        | 0.34%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.27%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.2%    |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.2%    |
| ASUS Bluetooth Device                                                | 3        | 0.2%    |
| ASUS Bluetooth Adapter                                               | 3        | 0.2%    |
| Actions general adapter                                              | 3        | 0.2%    |
| SINO WEALTH RK Bluetooth Keyboar                                     | 2        | 0.14%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 2        | 0.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 1997     | 28.99%  |
| Nvidia                                          | 1809     | 26.26%  |
| Intel                                           | 1803     | 26.17%  |
| C-Media Electronics                             | 196      | 2.85%   |
| Logitech                                        | 94       | 1.36%   |
| Creative Labs                                   | 71       | 1.03%   |
| Razer USA                                       | 55       | 0.8%    |
| Kingston Technology                             | 55       | 0.8%    |
| JMTek                                           | 51       | 0.74%   |
| Corsair                                         | 49       | 0.71%   |
| SteelSeries ApS                                 | 46       | 0.67%   |
| Texas Instruments                               | 40       | 0.58%   |
| ASUSTek Computer                                | 39       | 0.57%   |
| Creative Technology                             | 31       | 0.45%   |
| Focusrite-Novation                              | 29       | 0.42%   |
| Blue Microphones                                | 28       | 0.41%   |
| Generalplus Technology                          | 24       | 0.35%   |
| Micro Star International                        | 23       | 0.33%   |
| GN Netcom                                       | 17       | 0.25%   |
| Giga-Byte Technology                            | 17       | 0.25%   |
| Astro Gaming                                    | 16       | 0.23%   |
| Sony                                            | 15       | 0.22%   |
| Scarlett                                        | 15       | 0.22%   |
| DSEA A/S                                        | 14       | 0.2%    |
| Plantronics                                     | 13       | 0.19%   |
| Samson Technologies                             | 12       | 0.17%   |
| Realtek Semiconductor                           | 12       | 0.17%   |
| M-Audio                                         | 12       | 0.17%   |
| Turtle Beach                                    | 11       | 0.16%   |
| Tenx Technology                                 | 11       | 0.16%   |
| SAVITECH                                        | 11       | 0.16%   |
| Valve Software                                  | 10       | 0.15%   |
| Yamaha                                          | 9        | 0.13%   |
| Thesycon Systemsoftware & Consulting            | 9        | 0.13%   |
| FiiO Electronics Technology                     | 9        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.12%   |
| BEHRINGER International                         | 8        | 0.12%   |
| Audio-Technica                                  | 7        | 0.1%    |
| VIA Technologies                                | 6        | 0.09%   |
| Medeli Electronics                              | 6        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 714      | 8.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 311      | 3.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 262      | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 245      | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 240      | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 232      | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 198      | 2.46%   |
| Nvidia GP104 High Definition Audio Controller                              | 182      | 2.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 176      | 2.18%   |
| Intel 200 Series PCH HD Audio                                              | 174      | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 170      | 2.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 158      | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 148      | 1.84%   |
| AMD Navi 10 HDMI Audio                                                     | 147      | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 142      | 1.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 139      | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 129      | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 128      | 1.59%   |
| Nvidia TU104 HD Audio Controller                                           | 116      | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 105      | 1.3%    |
| Nvidia GA104 High Definition Audio Controller                              | 102      | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 100      | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 98       | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 90       | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 89       | 1.1%    |
| AMD FCH Azalia Controller                                                  | 88       | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 86       | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 84       | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 82       | 1.02%   |
| Nvidia GM204 High Definition Audio Controller                              | 77       | 0.96%   |
| Nvidia GA102 High Definition Audio Controller                              | 74       | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 67       | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 60       | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 58       | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                         | 53       | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                         | 52       | 0.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52       | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 45       | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 45       | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                              | 44       | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 154      | 22.48%  |
| Kingston                     | 123      | 17.96%  |
| G.Skill                      | 105      | 15.33%  |
| Crucial                      | 67       | 9.78%   |
| Unknown                      | 54       | 7.88%   |
| Samsung Electronics          | 39       | 5.69%   |
| SK hynix                     | 33       | 4.82%   |
| Team                         | 28       | 4.09%   |
| Micron Technology            | 20       | 2.92%   |
| A-DATA Technology            | 19       | 2.77%   |
| Patriot                      | 9        | 1.31%   |
| Ramaxel Technology           | 3        | 0.44%   |
| Patriot Memory               | 2        | 0.29%   |
| OLOY                         | 2        | 0.29%   |
| Neo Forza                    | 2        | 0.29%   |
| Avant                        | 2        | 0.29%   |
| Apacer                       | 2        | 0.29%   |
| Unknown                      | 2        | 0.29%   |
| Unifosa                      | 1        | 0.15%   |
| Transcend                    | 1        | 0.15%   |
| Toshiba                      | 1        | 0.15%   |
| Teikon                       | 1        | 0.15%   |
| Smart                        | 1        | 0.15%   |
| Silicon Power                | 1        | 0.15%   |
| Patriot Memory (PDP Systems) | 1        | 0.15%   |
| Nanya Technology             | 1        | 0.15%   |
| HMD                          | 1        | 0.15%   |
| Goodram                      | 1        | 0.15%   |
| Goldkey                      | 1        | 0.15%   |
| GLOWAY                       | 1        | 0.15%   |
| GeIL                         | 1        | 0.15%   |
| EVGA                         | 1        | 0.15%   |
| Elpida                       | 1        | 0.15%   |
| CSX                          | 1        | 0.15%   |
| ASint Technology             | 1        | 0.15%   |
| Asgard                       | 1        | 0.15%   |
| AMD                          | 1        | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 22       | 3.03%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s     | 13       | 1.79%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 12       | 1.65%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 10       | 1.38%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 9        | 1.24%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 8        | 1.1%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s    | 8        | 1.1%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 7        | 0.96%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 6        | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 6        | 0.83%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 5        | 0.69%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s        | 5        | 0.69%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 5        | 0.69%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 5        | 0.69%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s     | 5        | 0.69%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s    | 5        | 0.69%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s              | 5        | 0.69%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s              | 5        | 0.69%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 4        | 0.55%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 4        | 0.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 4        | 0.55%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s      | 4        | 0.55%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s      | 4        | 0.55%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 4        | 0.55%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s    | 4        | 0.55%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 4        | 0.55%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 4        | 0.55%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 4        | 0.55%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 4        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 3        | 0.41%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s        | 3        | 0.41%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 3        | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 3        | 0.41%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s       | 3        | 0.41%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 3        | 0.41%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 3        | 0.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 3        | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 3        | 0.41%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 3        | 0.41%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 3        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 447      | 70.73%  |
| DDR3    | 129      | 20.41%  |
| DDR5    | 18       | 2.85%   |
| Unknown | 16       | 2.53%   |
| DDR2    | 12       | 1.9%    |
| SDRAM   | 7        | 1.11%   |
| DDR     | 2        | 0.32%   |
| LPDDR4  | 1        | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 606      | 96.5%   |
| SODIMM       | 20       | 3.18%   |
| Row Of Chips | 1        | 0.16%   |
| RIMM         | 1        | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 302      | 45.14%  |
| 16384 | 166      | 24.81%  |
| 4096  | 106      | 15.84%  |
| 32768 | 56       | 8.37%   |
| 2048  | 28       | 4.19%   |
| 1024  | 9        | 1.35%   |
| 512   | 2        | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 118      | 17.23%  |
| 3200    | 80       | 11.68%  |
| 1600    | 70       | 10.22%  |
| 2400    | 46       | 6.72%   |
| 1333    | 45       | 6.57%   |
| 3000    | 27       | 3.94%   |
| 2667    | 24       | 3.5%    |
| 2133    | 24       | 3.5%    |
| 3800    | 20       | 2.92%   |
| 3400    | 18       | 2.63%   |
| 3866    | 16       | 2.34%   |
| 3733    | 16       | 2.34%   |
| 3533    | 14       | 2.04%   |
| 1867    | 14       | 2.04%   |
| 2933    | 12       | 1.75%   |
| 2800    | 10       | 1.46%   |
| 800     | 10       | 1.46%   |
| 2666    | 9        | 1.31%   |
| 3534    | 8        | 1.17%   |
| 1866    | 8        | 1.17%   |
| 1800    | 8        | 1.17%   |
| 3466    | 7        | 1.02%   |
| 667     | 7        | 1.02%   |
| 4800    | 6        | 0.88%   |
| 6000    | 5        | 0.73%   |
| 4000    | 5        | 0.73%   |
| 3666    | 5        | 0.73%   |
| Unknown | 5        | 0.73%   |
| 4400    | 4        | 0.58%   |
| 3333    | 4        | 0.58%   |
| 3100    | 3        | 0.44%   |
| 6400    | 2        | 0.29%   |
| 5200    | 2        | 0.29%   |
| 4266    | 2        | 0.29%   |
| 3334    | 2        | 0.29%   |
| 3266    | 2        | 0.29%   |
| 3151    | 2        | 0.29%   |
| 3066    | 2        | 0.29%   |
| 2733    | 2        | 0.29%   |
| 2472    | 2        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 47       | 31.54%  |
| Brother Industries    | 29       | 19.46%  |
| Canon                 | 23       | 15.44%  |
| Samsung Electronics   | 18       | 12.08%  |
| Seiko Epson           | 15       | 10.07%  |
| Dymo-CoStar           | 4        | 2.68%   |
| Fuji Xerox            | 3        | 2.01%   |
| QinHeng Electronics   | 2        | 1.34%   |
| Xerox                 | 1        | 0.67%   |
| STMicroelectronics    | 1        | 0.67%   |
| Prolific Technology   | 1        | 0.67%   |
| Oki Data              | 1        | 0.67%   |
| Lexmark International | 1        | 0.67%   |
| Kyocera               | 1        | 0.67%   |
| Dell                  | 1        | 0.67%   |
| Apple                 | 1        | 0.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.67%   |
| Samsung SCX-3400 Series                                    | 3        | 2%      |
| HP LaserJet Professional P 1102w                           | 3        | 2%      |
| Brother Printer                                            | 3        | 2%      |
| Brother HL-2130 series                                     | 3        | 2%      |
| Seiko Epson WF-4830 Series                                 | 2        | 1.33%   |
| Seiko Epson L396 Series                                    | 2        | 1.33%   |
| Seiko Epson L355 Series                                    | 2        | 1.33%   |
| Seiko Epson ET-2700 Series                                 | 2        | 1.33%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.33%   |
| Samsung M2070 Series                                       | 2        | 1.33%   |
| Samsung M2020 Series                                       | 2        | 1.33%   |
| QinHeng CH340S                                             | 2        | 1.33%   |
| HP ENVY Pro 6400 series                                    | 2        | 1.33%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.33%   |
| HP ENVY 4500 series                                        | 2        | 1.33%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.33%   |
| HP DeskJet 2620 All-in-One Printer                         | 2        | 1.33%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.33%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.33%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.33%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.33%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.33%   |
| Brother HL-L3230CDW series                                 | 2        | 1.33%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.33%   |
| Brother HL-1110 series                                     | 2        | 1.33%   |
| Xerox Phaser 6000B                                         | 1        | 0.67%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.67%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.67%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]               | 1        | 0.67%   |
| Seiko Epson L365 Series                                    | 1        | 0.67%   |
| Seiko Epson L3110 Series                                   | 1        | 0.67%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.67%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.67%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.67%   |
| Samsung SCX-4500 Laser Printer                             | 1        | 0.67%   |
| Samsung SCX-4200 series                                    | 1        | 0.67%   |
| Samsung ML-2540 Series Laser Printer                       | 1        | 0.67%   |
| Samsung ML-216x Series Laser Printer                       | 1        | 0.67%   |
| Samsung ML-191x/ML-252x Laser Printer                      | 1        | 0.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 55%     |
| Seiko Epson     | 5        | 25%     |
| Hewlett-Packard | 3        | 15%     |
| Mustek Systems  | 1        | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30                           | 2        | 10%     |
| Canon CanoScan LiDE 210                                 | 2        | 10%     |
| Seiko Epson Scanner                                     | 1        | 5%      |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 5%      |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1        | 5%      |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 5%      |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 5%      |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 5%      |
| HP ScanJet 82x0C                                        | 1        | 5%      |
| HP Scanjet 300                                          | 1        | 5%      |
| HP ScanJet 2400c                                        | 1        | 5%      |
| Canon CanoScan N650U/N656U                              | 1        | 5%      |
| Canon CanoScan LiDE 60                                  | 1        | 5%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 5%      |
| Canon CanoScan LiDE 220                                 | 1        | 5%      |
| Canon CanoScan LiDE 200                                 | 1        | 5%      |
| Canon CanoScan LiDE 110                                 | 1        | 5%      |
| Canon CanoScan 9000F Mark II                            | 1        | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 305      | 44.4%   |
| Microdia                      | 57       | 8.3%    |
| Microsoft                     | 36       | 5.24%   |
| Sunplus Innovation Technology | 24       | 3.49%   |
| Apple                         | 21       | 3.06%   |
| Generalplus Technology        | 19       | 2.77%   |
| ARC International             | 15       | 2.18%   |
| Samsung Electronics           | 13       | 1.89%   |
| Razer USA                     | 13       | 1.89%   |
| Realtek Semiconductor         | 12       | 1.75%   |
| Chicony Electronics           | 12       | 1.75%   |
| Z-Star Microelectronics       | 11       | 1.6%    |
| MacroSilicon                  | 10       | 1.46%   |
| Jieli Technology              | 10       | 1.46%   |
| Creative Technology           | 10       | 1.46%   |
| Valve Software                | 9        | 1.31%   |
| KYE Systems (Mouse Systems)   | 8        | 1.16%   |
| Cubeternet                    | 6        | 0.87%   |
| LG Electronics                | 5        | 0.73%   |
| Huawei Technologies           | 5        | 0.73%   |
| Hewlett-Packard               | 5        | 0.73%   |
| AVerMedia Technologies        | 5        | 0.73%   |
| Aveo Technology               | 4        | 0.58%   |
| Trust                         | 3        | 0.44%   |
| A4Tech                        | 3        | 0.44%   |
| 2M UVC CAMERA                 | 3        | 0.44%   |
| YGTek                         | 2        | 0.29%   |
| WCM_USB                       | 2        | 0.29%   |
| ValueHD                       | 2        | 0.29%   |
| Sunplus IT                    | 2        | 0.29%   |
| SN0002                        | 2        | 0.29%   |
| Ruision                       | 2        | 0.29%   |
| Novatek Microelectronics      | 2        | 0.29%   |
| Intel                         | 2        | 0.29%   |
| HTC (High Tech Computer)      | 2        | 0.29%   |
| GenesysLogic Technology       | 2        | 0.29%   |
| Genesys Logic                 | 2        | 0.29%   |
| GEMBIRD                       | 2        | 0.29%   |
| eMeet                         | 2        | 0.29%   |
| Elgato Systems                | 2        | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 68       | 9.86%   |
| Logitech Webcam C270                    | 61       | 8.84%   |
| Logitech C922 Pro Stream Webcam         | 24       | 3.48%   |
| Microdia Webcam Vitade AF               | 23       | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 20       | 2.9%    |
| Logitech BRIO Ultra HD Webcam           | 18       | 2.61%   |
| Generalplus GENERAL WEBCAM              | 15       | 2.17%   |
| ARC International Camera                | 15       | 2.17%   |
| Microsoft LifeCam HD-3000               | 14       | 2.03%   |
| Logitech HD Webcam C525                 | 14       | 2.03%   |
| Samsung Galaxy series, misc. (MTP mode) | 13       | 1.88%   |
| Logitech HD Webcam C615                 | 13       | 1.88%   |
| Microdia USB 2.0 Camera                 | 11       | 1.59%   |
| Razer USA Gaming Webcam [Kiyo]          | 10       | 1.45%   |
| Logitech Webcam C925e                   | 10       | 1.45%   |
| Jieli USB PHY 2.0                       | 10       | 1.45%   |
| Valve Software 3D Camera                | 9        | 1.3%    |
| Logitech Webcam C310                    | 9        | 1.3%    |
| Microdia Integrated Camera              | 8        | 1.16%   |
| MacroSilicon USB Video                  | 8        | 1.16%   |
| Logitech Webcam Pro 9000                | 8        | 1.16%   |
| Logitech Webcam C930e                   | 8        | 1.16%   |
| Logitech Webcam C170                    | 8        | 1.16%   |
| Logitech StreamCam                      | 8        | 1.16%   |
| Logitech C920 PRO HD Webcam             | 8        | 1.16%   |
| Microsoft LifeCam Cinema                | 7        | 1.01%   |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.87%   |
| Microdia Camera                         | 5        | 0.72%   |
| Logitech HD Webcam C510                 | 5        | 0.72%   |
| Huawei HiCamera                         | 5        | 0.72%   |
| AVerMedia Live Streamer CAM 313         | 5        | 0.72%   |
| Sunplus USB 2.0 Camera                  | 4        | 0.58%   |
| Realtek FULL HD 1080P Webcam            | 4        | 0.58%   |
| Microdia Sonix USB 2.0 Camera           | 4        | 0.58%   |
| Logitech Logi Webcam C920e              | 4        | 0.58%   |
| Logitech HD Webcam C910                 | 4        | 0.58%   |
| Logitech B525 HD Webcam                 | 4        | 0.58%   |
| Z-Star Venus USB2.0 Camera              | 3        | 0.43%   |
| Sunplus video capture device            | 3        | 0.43%   |
| Sunplus SPCA2281 Web Camera             | 3        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 25%     |
| Elan Microelectronics | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |
| AuthenTec             | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 2        | 25%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 12.5%   |
| LighTuning Fingerprint Sensor                               | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                           | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                                | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 37.5%   |
| OmniKey               | 3        | 18.75%  |
| Alcor Micro           | 3        | 18.75%  |
| Realtek Semiconductor | 2        | 12.5%   |
| Chicony Electronics   | 1        | 6.25%   |
| Advanced Card Systems | 1        | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 25%     |
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 12.5%   |
| OmniKey CardMan 3021 / 3121                            | 2        | 12.5%   |
| Alcor Micro Watchdata W 1981                           | 2        | 12.5%   |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 6.25%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 6.25%   |
| OmniKey CardMan 1021                                   | 1        | 6.25%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 6.25%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 6.25%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2944     | 80.64%  |
| 1     | 633      | 17.34%  |
| 2     | 62       | 1.7%    |
| 3     | 9        | 0.25%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 280      | 36.41%  |
| Graphics card            | 269      | 34.98%  |
| Unassigned class         | 49       | 6.37%   |
| Multimedia controller    | 24       | 3.12%   |
| Sound                    | 23       | 2.99%   |
| Communication controller | 22       | 2.86%   |
| Bluetooth                | 21       | 2.73%   |
| Storage/raid             | 14       | 1.82%   |
| Net/ethernet             | 14       | 1.82%   |
| Chipcard                 | 13       | 1.69%   |
| Network                  | 11       | 1.43%   |
| Fingerprint reader       | 8        | 1.04%   |
| Camera                   | 7        | 0.91%   |
| Storage/ide              | 4        | 0.52%   |
| Card reader              | 4        | 0.52%   |
| Storage/nvme             | 3        | 0.39%   |
| Firewire controller      | 2        | 0.26%   |
| Dvb card                 | 1        | 0.13%   |

