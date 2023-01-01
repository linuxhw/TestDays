Linux in Austria - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

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

Total: 874

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550M AORUS PRO-P           | [de6ea0ae2e](https://linux-hardware.org/?probe=de6ea0ae2e) | Dec 30, 2022 |
| ASUSTek       | P7P55D-E                    | [f725a0095a](https://linux-hardware.org/?probe=f725a0095a) | Dec 30, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [d680b8dd2a](https://linux-hardware.org/?probe=d680b8dd2a) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [e8dce940d8](https://linux-hardware.org/?probe=e8dce940d8) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| ASUSTek       | P7P55D-E                    | [a6be229477](https://linux-hardware.org/?probe=a6be229477) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| HP            | 8906 SMVB                   | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| Dell          | 0T7D40 A01                  | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [fa03fe621a](https://linux-hardware.org/?probe=fa03fe621a) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [8480834751](https://linux-hardware.org/?probe=8480834751) | Dec 17, 2022 |
| Gigabyte      | B550M DS3H                  | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| ASRock        | X670E PG Lightning          | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [cc2d9043d9](https://linux-hardware.org/?probe=cc2d9043d9) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [f6341e7afb](https://linux-hardware.org/?probe=f6341e7afb) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [2b34016cad](https://linux-hardware.org/?probe=2b34016cad) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [790ae8be94](https://linux-hardware.org/?probe=790ae8be94) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | [373dac5bbb](https://linux-hardware.org/?probe=373dac5bbb) | Dec 02, 2022 |
| ASUSTek       | H110M-A                     | [d7694493c0](https://linux-hardware.org/?probe=d7694493c0) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | [01dfdc071e](https://linux-hardware.org/?probe=01dfdc071e) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [9aa4880856](https://linux-hardware.org/?probe=9aa4880856) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [c1f5a1f413](https://linux-hardware.org/?probe=c1f5a1f413) | Dec 01, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [ae01075720](https://linux-hardware.org/?probe=ae01075720) | Nov 28, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [6d3657ecde](https://linux-hardware.org/?probe=6d3657ecde) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| Gigabyte      | Z590 UD AC                  | [4fc70b9ddc](https://linux-hardware.org/?probe=4fc70b9ddc) | Nov 21, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9c6a00b034](https://linux-hardware.org/?probe=9c6a00b034) | Nov 09, 2022 |
| ASUSTek       | VM40B                       | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| HP            | 8906 SMVB                   | [2670a536f0](https://linux-hardware.org/?probe=2670a536f0) | Nov 08, 2022 |
| Medion        | MS-7797                     | [41ba0c8fdc](https://linux-hardware.org/?probe=41ba0c8fdc) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1a0fbb4d0d](https://linux-hardware.org/?probe=1a0fbb4d0d) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [7007ab7df6](https://linux-hardware.org/?probe=7007ab7df6) | Nov 03, 2022 |
| Dell          | 0NW6H5 A00                  | [d768cd4c66](https://linux-hardware.org/?probe=d768cd4c66) | Oct 29, 2022 |
| ASUSTek       | Z87-A                       | [0b4711df41](https://linux-hardware.org/?probe=0b4711df41) | Oct 26, 2022 |
| MSI           | H81M-P33                    | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Unknown       | Unknown                     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| Gigabyte      | H87-HD3                     | [bdd6e6d3a5](https://linux-hardware.org/?probe=bdd6e6d3a5) | Oct 23, 2022 |
| ASRock        | B450M Pro4-F                | [eb651764eb](https://linux-hardware.org/?probe=eb651764eb) | Oct 22, 2022 |
| MSI           | H81M-P33                    | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| ASUSTek       | P9X79                       | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| ASUSTek       | PRIME H410M-A               | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Dell          | 0MN1TX A01                  | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Unknown       | 775VM8                      | [114c84d76c](https://linux-hardware.org/?probe=114c84d76c) | Sep 30, 2022 |
| Unknown       | 775VM8                      | [903649eae9](https://linux-hardware.org/?probe=903649eae9) | Sep 30, 2022 |
| MSI           | H110 PC MATE                | [ac97c636a5](https://linux-hardware.org/?probe=ac97c636a5) | Sep 30, 2022 |
| Biostar       | A10N-8800E                  | [d27bf09dc8](https://linux-hardware.org/?probe=d27bf09dc8) | Sep 27, 2022 |
| Medion        | MS-7728                     | [82da4b643b](https://linux-hardware.org/?probe=82da4b643b) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | [89303afdb5](https://linux-hardware.org/?probe=89303afdb5) | Sep 26, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [a213c6d22a](https://linux-hardware.org/?probe=a213c6d22a) | Sep 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [0047e2de0e](https://linux-hardware.org/?probe=0047e2de0e) | Sep 24, 2022 |
| MSI           | H110 PC MATE                | [006830e521](https://linux-hardware.org/?probe=006830e521) | Sep 23, 2022 |
| ASUSTek       | WS C422 PRO_SE              | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| HP            | 1998                        | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [4d5fc6b39f](https://linux-hardware.org/?probe=4d5fc6b39f) | Sep 20, 2022 |
| Dell          | 02M8NY A01                  | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| Dell          | 0T7D40 A01                  | [9eba047248](https://linux-hardware.org/?probe=9eba047248) | Sep 18, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [980e4272fb](https://linux-hardware.org/?probe=980e4272fb) | Sep 17, 2022 |
| Intel         | DH67BL AAG10189-209         | [3507c0cdb7](https://linux-hardware.org/?probe=3507c0cdb7) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3c37d36ba8](https://linux-hardware.org/?probe=3c37d36ba8) | Sep 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [321432c752](https://linux-hardware.org/?probe=321432c752) | Sep 12, 2022 |
| ASUSTek       | H170M-PLUS                  | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Unknown       | Unknown                     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [106bdf4d1b](https://linux-hardware.org/?probe=106bdf4d1b) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | [ebceb9b949](https://linux-hardware.org/?probe=ebceb9b949) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | [d7c48b7007](https://linux-hardware.org/?probe=d7c48b7007) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | H61M-A/USB3                 | [7801ef775b](https://linux-hardware.org/?probe=7801ef775b) | Sep 03, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| Dell          | 0T7D40 A01                  | [0968e0629e](https://linux-hardware.org/?probe=0968e0629e) | Aug 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Foxconn       | A6VMX 0A                    | [f31fcbf60d](https://linux-hardware.org/?probe=f31fcbf60d) | Aug 26, 2022 |
| Acer          | Predator G3-710             | [7a58c9348e](https://linux-hardware.org/?probe=7a58c9348e) | Aug 22, 2022 |
| MSI           | 2A9C                        | [4f15bcded6](https://linux-hardware.org/?probe=4f15bcded6) | Aug 22, 2022 |
| Dell          | 0T10XW A01                  | [30ebde5edc](https://linux-hardware.org/?probe=30ebde5edc) | Aug 21, 2022 |
| ASUSTek       | Maximus IX HERO             | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| MSI           | 760GM-P23                   | [42245b8fc8](https://linux-hardware.org/?probe=42245b8fc8) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| ASUSTek       | F2A85-V                     | [cc26af3a41](https://linux-hardware.org/?probe=cc26af3a41) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| MSI           | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 3031h                       | [2409514846](https://linux-hardware.org/?probe=2409514846) | Aug 06, 2022 |
| MSI           | 2A9C                        | [e279622ca6](https://linux-hardware.org/?probe=e279622ca6) | Aug 06, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [03f6cbc20a](https://linux-hardware.org/?probe=03f6cbc20a) | Aug 05, 2022 |
| HP            | 8054                        | [888466c84e](https://linux-hardware.org/?probe=888466c84e) | Aug 04, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [8251f56856](https://linux-hardware.org/?probe=8251f56856) | Aug 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [06c0366665](https://linux-hardware.org/?probe=06c0366665) | Aug 03, 2022 |
| ASUSTek       | P9X79                       | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Acer          | RS880M05                    | [0a5ede14e3](https://linux-hardware.org/?probe=0a5ede14e3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| HP            | 0AA0h                       | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| MSI           | B350 TOMAHAWK               | [1d04421fd5](https://linux-hardware.org/?probe=1d04421fd5) | Jul 27, 2022 |
| Dell          | 08WKV3 A00                  | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| MSI           | X79A-GD45 Plus              | [5496428dac](https://linux-hardware.org/?probe=5496428dac) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [79113b8782](https://linux-hardware.org/?probe=79113b8782) | Jul 23, 2022 |
| Shuttle       | FH67H                       | [fe77bc1ab0](https://linux-hardware.org/?probe=fe77bc1ab0) | Jul 22, 2022 |
| MSI           | H77MA-G43                   | [4cb547564b](https://linux-hardware.org/?probe=4cb547564b) | Jul 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bb0bb0b58f](https://linux-hardware.org/?probe=bb0bb0b58f) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| Dell          | 0T7D40 A01                  | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| HP            | 8906 SMVB                   | [a10adc5a33](https://linux-hardware.org/?probe=a10adc5a33) | Jun 24, 2022 |
| ASRock        | Z370 Extreme4               | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| MSI           | 970A-G43                    | [9514e1e2ef](https://linux-hardware.org/?probe=9514e1e2ef) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| MSI           | H510M PRO                   | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| HP            | 8906 SMVB                   | [772043704c](https://linux-hardware.org/?probe=772043704c) | Jun 13, 2022 |
| HP            | 8906 SMVB                   | [7cc9d90361](https://linux-hardware.org/?probe=7cc9d90361) | Jun 12, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| ASRock        | B365M Pro4-F                | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| ASUSTek       | H87-PRO                     | [fd496870e4](https://linux-hardware.org/?probe=fd496870e4) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [156b265da0](https://linux-hardware.org/?probe=156b265da0) | Jun 01, 2022 |
| Gigabyte      | 970A-UD3                    | [c56522071c](https://linux-hardware.org/?probe=c56522071c) | Jun 01, 2022 |
| MSI           | MEG X570 UNIFY              | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| HP            | 304Bh                       | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d6bd3ae553](https://linux-hardware.org/?probe=d6bd3ae553) | May 26, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [257b7363bd](https://linux-hardware.org/?probe=257b7363bd) | May 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [666b9afd8f](https://linux-hardware.org/?probe=666b9afd8f) | May 24, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [e4fa1610cb](https://linux-hardware.org/?probe=e4fa1610cb) | May 22, 2022 |
| ASUSTek       | F2A85-V                     | [4d990d8f08](https://linux-hardware.org/?probe=4d990d8f08) | May 21, 2022 |
| ASUSTek       | H61M-A/USB3                 | [4d5f3d8c33](https://linux-hardware.org/?probe=4d5f3d8c33) | May 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| Gigabyte      | Z68XP-UD3                   | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [cea36d8ad8](https://linux-hardware.org/?probe=cea36d8ad8) | May 15, 2022 |
| Gigabyte      | B450M S2H                   | [1185abcaaa](https://linux-hardware.org/?probe=1185abcaaa) | May 14, 2022 |
| ASRock        | N68C-S UCC                  | [369f214ed2](https://linux-hardware.org/?probe=369f214ed2) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6003e5a67f](https://linux-hardware.org/?probe=6003e5a67f) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f7d09ea6c5](https://linux-hardware.org/?probe=f7d09ea6c5) | May 13, 2022 |
| ASRock        | B365M Pro4-F                | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| ASUSTek       | Z87-A                       | [62ffc7ab1a](https://linux-hardware.org/?probe=62ffc7ab1a) | May 11, 2022 |
| Dell          | 0T7D40 A01                  | [36b253f8bc](https://linux-hardware.org/?probe=36b253f8bc) | May 09, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| ASRock        | B450 Steel Legend           | [d2a6709c96](https://linux-hardware.org/?probe=d2a6709c96) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [dbb48b83bf](https://linux-hardware.org/?probe=dbb48b83bf) | Apr 24, 2022 |
| ASUSTek       | M4A78-E                     | [e4779f4dc8](https://linux-hardware.org/?probe=e4779f4dc8) | Apr 23, 2022 |
| ASRock        | X470 Taichi Ultimate        | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e269a6b9b8](https://linux-hardware.org/?probe=e269a6b9b8) | Apr 18, 2022 |
| ASUSTek       | P7P55D LE                   | [381477f3e6](https://linux-hardware.org/?probe=381477f3e6) | Apr 15, 2022 |
| Fujitsu       | D3434-S2 S26361-D3434-S2    | [7ff488cc8d](https://linux-hardware.org/?probe=7ff488cc8d) | Apr 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-A                | [cb3eb74403](https://linux-hardware.org/?probe=cb3eb74403) | Apr 13, 2022 |
| ASUSTek       | P9X79                       | [b7a035ea6b](https://linux-hardware.org/?probe=b7a035ea6b) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f75dc153d0](https://linux-hardware.org/?probe=f75dc153d0) | Apr 13, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [3930b32e77](https://linux-hardware.org/?probe=3930b32e77) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [1e302e1cce](https://linux-hardware.org/?probe=1e302e1cce) | Apr 12, 2022 |
| Medion        | MS-7707                     | [fb95ae3a92](https://linux-hardware.org/?probe=fb95ae3a92) | Apr 09, 2022 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [fa2e3ae8ee](https://linux-hardware.org/?probe=fa2e3ae8ee) | Apr 08, 2022 |
| ECS           | CMLU-MINI                   | [742c0da37b](https://linux-hardware.org/?probe=742c0da37b) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | [16d1981053](https://linux-hardware.org/?probe=16d1981053) | Apr 04, 2022 |
| MSI           | MEG X570 UNIFY              | [0c57600526](https://linux-hardware.org/?probe=0c57600526) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [85a3c0a47e](https://linux-hardware.org/?probe=85a3c0a47e) | Mar 29, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [973087697b](https://linux-hardware.org/?probe=973087697b) | Mar 28, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [1bfef458ea](https://linux-hardware.org/?probe=1bfef458ea) | Mar 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2b4181439](https://linux-hardware.org/?probe=d2b4181439) | Mar 16, 2022 |
| Dell          | 0T7D40 A01                  | [192926e183](https://linux-hardware.org/?probe=192926e183) | Mar 14, 2022 |
| Acer          | Predator PO3-600 V:1.1      | [fc992250ca](https://linux-hardware.org/?probe=fc992250ca) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [0f103bcb15](https://linux-hardware.org/?probe=0f103bcb15) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [304738db66](https://linux-hardware.org/?probe=304738db66) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [5183569327](https://linux-hardware.org/?probe=5183569327) | Mar 06, 2022 |
| BESSTAR Te... | UM200 V1.0                  | [bae5f3ad77](https://linux-hardware.org/?probe=bae5f3ad77) | Feb 26, 2022 |
| ASUSTek       | P9X79                       | [cd0609e2cc](https://linux-hardware.org/?probe=cd0609e2cc) | Feb 25, 2022 |
| ASUSTek       | P9X79                       | [f576f08ecb](https://linux-hardware.org/?probe=f576f08ecb) | Feb 24, 2022 |
| MSI           | H81M-P33                    | [64955f775b](https://linux-hardware.org/?probe=64955f775b) | Feb 24, 2022 |
| Medion        | B250H4-EM                   | [851288ccf7](https://linux-hardware.org/?probe=851288ccf7) | Feb 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [803b4d504c](https://linux-hardware.org/?probe=803b4d504c) | Feb 19, 2022 |
| HP            | 8906 SMVB                   | [ae83ee4d22](https://linux-hardware.org/?probe=ae83ee4d22) | Feb 19, 2022 |
| ASRock        | X299 Taichi XE              | [04a1425dca](https://linux-hardware.org/?probe=04a1425dca) | Feb 17, 2022 |
| ASRock        | X299 Taichi XE              | [45b82f5330](https://linux-hardware.org/?probe=45b82f5330) | Feb 17, 2022 |
| MSI           | Z270 GAMING PRO             | [6c6a916a0b](https://linux-hardware.org/?probe=6c6a916a0b) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [4ff66e932f](https://linux-hardware.org/?probe=4ff66e932f) | Feb 13, 2022 |
| HP            | 3397                        | [8ea2c45260](https://linux-hardware.org/?probe=8ea2c45260) | Feb 13, 2022 |
| Lenovo        | ThinkCentre A58 7515M6G     | [7b86a1d792](https://linux-hardware.org/?probe=7b86a1d792) | Feb 12, 2022 |
| HP            | 3397                        | [f92e367657](https://linux-hardware.org/?probe=f92e367657) | Feb 12, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [b229af38f0](https://linux-hardware.org/?probe=b229af38f0) | Feb 12, 2022 |
| Biostar       | A10N-8800E                  | [8231d95ddc](https://linux-hardware.org/?probe=8231d95ddc) | Feb 12, 2022 |
| Intel         | DH67GD AAG10206-202         | [56c802164a](https://linux-hardware.org/?probe=56c802164a) | Feb 11, 2022 |
| HP            | 1494                        | [93502b8c70](https://linux-hardware.org/?probe=93502b8c70) | Feb 11, 2022 |
| MSI           | B550-A PRO                  | [577fc1abce](https://linux-hardware.org/?probe=577fc1abce) | Feb 11, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [529666b867](https://linux-hardware.org/?probe=529666b867) | Feb 10, 2022 |
| ASRock        | H81M-HDS                    | [5f2ada50f9](https://linux-hardware.org/?probe=5f2ada50f9) | Feb 10, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c83ca2e528](https://linux-hardware.org/?probe=c83ca2e528) | Feb 10, 2022 |
| HP            | 8906 SMVB                   | [646a1296e0](https://linux-hardware.org/?probe=646a1296e0) | Feb 10, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4706a4f369](https://linux-hardware.org/?probe=4706a4f369) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [c945332cad](https://linux-hardware.org/?probe=c945332cad) | Feb 10, 2022 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [eb3836e9d0](https://linux-hardware.org/?probe=eb3836e9d0) | Feb 10, 2022 |
| ASUSTek       | PRIME X570-PRO              | [88181832a0](https://linux-hardware.org/?probe=88181832a0) | Feb 09, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9ff4906aa1](https://linux-hardware.org/?probe=9ff4906aa1) | Feb 09, 2022 |
| ASUSTek       | H97-PLUS                    | [435e9532a8](https://linux-hardware.org/?probe=435e9532a8) | Feb 09, 2022 |
| HP            | 8906 SMVB                   | [454f14e47d](https://linux-hardware.org/?probe=454f14e47d) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| Dell          | 0GY6Y8 A01                  | [8b8eda08e4](https://linux-hardware.org/?probe=8b8eda08e4) | Feb 07, 2022 |
| Dell          | 042P49 A00                  | [9f98143f82](https://linux-hardware.org/?probe=9f98143f82) | Feb 07, 2022 |
| ASUSTek       | Z87-A                       | [b48601a549](https://linux-hardware.org/?probe=b48601a549) | Jan 31, 2022 |
| ASUSTek       | Z87-A                       | [b62cc09b63](https://linux-hardware.org/?probe=b62cc09b63) | Jan 30, 2022 |
| ASRock        | 970 Extreme4                | [f024dd97a0](https://linux-hardware.org/?probe=f024dd97a0) | Jan 29, 2022 |
| ASUSTek       | P8H77-M PRO                 | [16d9024680](https://linux-hardware.org/?probe=16d9024680) | Jan 26, 2022 |
| HP            | 8906 SMVB                   | [132c3acbb1](https://linux-hardware.org/?probe=132c3acbb1) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| MSI           | B450M MORTAR MAX            | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [635e361ebb](https://linux-hardware.org/?probe=635e361ebb) | Jan 22, 2022 |
| HP            | 1998                        | [422b7b3f1c](https://linux-hardware.org/?probe=422b7b3f1c) | Jan 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0aab49a3e3](https://linux-hardware.org/?probe=0aab49a3e3) | Jan 20, 2022 |
| HP            | 8906 SMVB                   | [566e943f08](https://linux-hardware.org/?probe=566e943f08) | Jan 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| HP            | 8906 SMVB                   | [118b411a8c](https://linux-hardware.org/?probe=118b411a8c) | Jan 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [960bd82b34](https://linux-hardware.org/?probe=960bd82b34) | Jan 11, 2022 |
| MSI           | B360M PRO-VDH               | [bd136c19e0](https://linux-hardware.org/?probe=bd136c19e0) | Jan 10, 2022 |
| ASUSTek       | H81M-PLUS                   | [67ab65d5f0](https://linux-hardware.org/?probe=67ab65d5f0) | Jan 10, 2022 |
| ASUSTek       | F2A85-V PRO                 | [9333fdb2cc](https://linux-hardware.org/?probe=9333fdb2cc) | Jan 06, 2022 |
| ASRock        | Z77 Pro4-M                  | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| ASRock        | X370 Killer SLI             | [7c10b6f7ae](https://linux-hardware.org/?probe=7c10b6f7ae) | Dec 30, 2021 |
| Unknown       | Unknown                     | [cbe80d8c24](https://linux-hardware.org/?probe=cbe80d8c24) | Dec 30, 2021 |
| Dell          | 051FJ8 A02                  | [8cc53ce548](https://linux-hardware.org/?probe=8cc53ce548) | Dec 30, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [b3d411a4d7](https://linux-hardware.org/?probe=b3d411a4d7) | Dec 18, 2021 |
| Gigabyte      | GA-870A-UD3                 | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| ASUSTek       | M4A77                       | [4231ac26aa](https://linux-hardware.org/?probe=4231ac26aa) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [89dd614f98](https://linux-hardware.org/?probe=89dd614f98) | Dec 09, 2021 |
| Acer          | Aspire XC-605               | [770f6167f6](https://linux-hardware.org/?probe=770f6167f6) | Dec 08, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [01b9229bd4](https://linux-hardware.org/?probe=01b9229bd4) | Dec 08, 2021 |
| MSI           | X570-A PRO                  | [d2704f29ec](https://linux-hardware.org/?probe=d2704f29ec) | Dec 06, 2021 |
| ASUSTek       | P9X79-E WS                  | [b65be23e52](https://linux-hardware.org/?probe=b65be23e52) | Dec 06, 2021 |
| ASRockRack    | C3558D4I-4L                 | [d563eb82ae](https://linux-hardware.org/?probe=d563eb82ae) | Dec 04, 2021 |
| Gigabyte      | Z270P-D3-CF                 | [ca35105e1a](https://linux-hardware.org/?probe=ca35105e1a) | Dec 04, 2021 |
| HP            | 21D0                        | [50548c11b7](https://linux-hardware.org/?probe=50548c11b7) | Dec 04, 2021 |
| Lenovo        | MAHOBAY                     | [e6f6525ecd](https://linux-hardware.org/?probe=e6f6525ecd) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1669a775b](https://linux-hardware.org/?probe=a1669a775b) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0d42fdd2bf](https://linux-hardware.org/?probe=0d42fdd2bf) | Nov 30, 2021 |
| Medion        | MS-7748                     | [bb473ca5d8](https://linux-hardware.org/?probe=bb473ca5d8) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| Dell          | 0T7D40 A01                  | [065636c444](https://linux-hardware.org/?probe=065636c444) | Nov 25, 2021 |
| MSI           | A78M-E35                    | [999bbc1197](https://linux-hardware.org/?probe=999bbc1197) | Nov 24, 2021 |
| Acer          | Revo 70                     | [f5cdb95334](https://linux-hardware.org/?probe=f5cdb95334) | Nov 24, 2021 |
| Acer          | Revo 70                     | [4c99b6ac71](https://linux-hardware.org/?probe=4c99b6ac71) | Nov 24, 2021 |
| ASRock        | X570 Pro4                   | [1cce90a2eb](https://linux-hardware.org/?probe=1cce90a2eb) | Nov 23, 2021 |
| HP            | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| HP            | ProLiant MicroServer Gen... | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| ASUSTek       | P7P55D EVO                  | [f453f8d58d](https://linux-hardware.org/?probe=f453f8d58d) | Nov 18, 2021 |
| ASUSTek       | Z170-P                      | [1e333032a4](https://linux-hardware.org/?probe=1e333032a4) | Nov 14, 2021 |
| ASRock        | P67 Pro3                    | [17c9af356a](https://linux-hardware.org/?probe=17c9af356a) | Nov 08, 2021 |
| ASUSTek       | Z170-P                      | [37f9ff3c0b](https://linux-hardware.org/?probe=37f9ff3c0b) | Nov 07, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Dell          | 0Y2MRG A00                  | [80cfec46fc](https://linux-hardware.org/?probe=80cfec46fc) | Nov 03, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| ASRock        | A320M-HDV R4.0              | [267a4603eb](https://linux-hardware.org/?probe=267a4603eb) | Nov 02, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [500411363b](https://linux-hardware.org/?probe=500411363b) | Nov 01, 2021 |
| Gigabyte      | P55M-UD2                    | [b14c0e8dd2](https://linux-hardware.org/?probe=b14c0e8dd2) | Oct 29, 2021 |
| MSI           | A78M-E35                    | [69da26c946](https://linux-hardware.org/?probe=69da26c946) | Oct 29, 2021 |
| ASUSTek       | SABERTOOTH X79              | [2b361b1035](https://linux-hardware.org/?probe=2b361b1035) | Oct 28, 2021 |
| ASUSTek       | M11BB                       | [c049f2b753](https://linux-hardware.org/?probe=c049f2b753) | Oct 28, 2021 |
| Acer          | FIH57                       | [719b6ffbe5](https://linux-hardware.org/?probe=719b6ffbe5) | Oct 24, 2021 |
| ASUSTek       | PRIME J4005I-C              | [2c5d786879](https://linux-hardware.org/?probe=2c5d786879) | Oct 20, 2021 |
| Intel         | D54250WYK H13922-303        | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| Gigabyte      | H61MA-D2V                   | [3968e39b0b](https://linux-hardware.org/?probe=3968e39b0b) | Oct 12, 2021 |
| ASUSTek       | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4054b4ec35](https://linux-hardware.org/?probe=4054b4ec35) | Oct 11, 2021 |
| HP            | 8906 SMVB                   | [8fca5ef20e](https://linux-hardware.org/?probe=8fca5ef20e) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [971cdf3ab8](https://linux-hardware.org/?probe=971cdf3ab8) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [d01c751c63](https://linux-hardware.org/?probe=d01c751c63) | Oct 11, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | [719e7db7f5](https://linux-hardware.org/?probe=719e7db7f5) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS PRO              | [d3c72411ee](https://linux-hardware.org/?probe=d3c72411ee) | Oct 09, 2021 |
| HP            | 212B                        | [a4318b7064](https://linux-hardware.org/?probe=a4318b7064) | Oct 06, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8f7011b085](https://linux-hardware.org/?probe=8f7011b085) | Oct 03, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Gigabyte      | GA-M56S-S3                  | [4502947e1a](https://linux-hardware.org/?probe=4502947e1a) | Sep 30, 2021 |
| ASRock        | Z170 Gaming K4              | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| MSI           | 790FX-GD70                  | [ba5f2949aa](https://linux-hardware.org/?probe=ba5f2949aa) | Sep 26, 2021 |
| Gigabyte      | Z590 D                      | [97c779cffc](https://linux-hardware.org/?probe=97c779cffc) | Sep 20, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [83649103a6](https://linux-hardware.org/?probe=83649103a6) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [ee40317007](https://linux-hardware.org/?probe=ee40317007) | Sep 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [ae610c34e9](https://linux-hardware.org/?probe=ae610c34e9) | Sep 16, 2021 |
| ASUSTek       | P5K-VM                      | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| MSI           | Z170-A PRO                  | [5b702a6c05](https://linux-hardware.org/?probe=5b702a6c05) | Sep 12, 2021 |
| HP            | 8767 A                      | [bb5655cf3b](https://linux-hardware.org/?probe=bb5655cf3b) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [bc2d35138c](https://linux-hardware.org/?probe=bc2d35138c) | Sep 10, 2021 |
| Unknown       | 1.21                        | [dbf4f53e70](https://linux-hardware.org/?probe=dbf4f53e70) | Sep 05, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [68da5f41b2](https://linux-hardware.org/?probe=68da5f41b2) | Aug 27, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [d87877599e](https://linux-hardware.org/?probe=d87877599e) | Aug 26, 2021 |
| Shuttle       | FS61                        | [fc97f7167b](https://linux-hardware.org/?probe=fc97f7167b) | Aug 26, 2021 |
| HP            | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | [5f90a39c6f](https://linux-hardware.org/?probe=5f90a39c6f) | Aug 20, 2021 |
| ASRock        | J4205-ITX                   | [30de75d2c8](https://linux-hardware.org/?probe=30de75d2c8) | Aug 18, 2021 |
| Medion        | MS-7707                     | [66ace31297](https://linux-hardware.org/?probe=66ace31297) | Aug 16, 2021 |
| ASRock        | Z590 Pro4                   | [5d9a3a97f2](https://linux-hardware.org/?probe=5d9a3a97f2) | Aug 16, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| ASRock        | H97M Pro4                   | [5edf7e02c8](https://linux-hardware.org/?probe=5edf7e02c8) | Aug 14, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| HP            | 8906 SMVB                   | [98dc285619](https://linux-hardware.org/?probe=98dc285619) | Aug 11, 2021 |
| HP            | 8906 SMVB                   | [4c7e9555c1](https://linux-hardware.org/?probe=4c7e9555c1) | Aug 08, 2021 |
| Dell          | 0T7D40 A01                  | [0728097100](https://linux-hardware.org/?probe=0728097100) | Aug 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [729ae360b5](https://linux-hardware.org/?probe=729ae360b5) | Aug 03, 2021 |
| HP            | 1495                        | [48e893c344](https://linux-hardware.org/?probe=48e893c344) | Aug 03, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [50136afddd](https://linux-hardware.org/?probe=50136afddd) | Aug 02, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [27e7a22365](https://linux-hardware.org/?probe=27e7a22365) | Aug 02, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [55f86a29a2](https://linux-hardware.org/?probe=55f86a29a2) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| ASUSTek       | B150M-K                     | [34e2582dc2](https://linux-hardware.org/?probe=34e2582dc2) | Jul 25, 2021 |
| ASUSTek       | X79-DELUXE                  | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| MSI           | B85M-E45                    | [16178cb493](https://linux-hardware.org/?probe=16178cb493) | Jul 24, 2021 |
| ASUSTek       | Z170-WS                     | [3368a26a83](https://linux-hardware.org/?probe=3368a26a83) | Jul 23, 2021 |
| Acer          | Aspire TC-780               | [cc39834e1d](https://linux-hardware.org/?probe=cc39834e1d) | Jul 21, 2021 |
| ASUSTek       | F2A85-V                     | [ad05a07bb3](https://linux-hardware.org/?probe=ad05a07bb3) | Jul 19, 2021 |
| HP            | 1495                        | [f2affe9c46](https://linux-hardware.org/?probe=f2affe9c46) | Jul 18, 2021 |
| HP            | 212A                        | [56cd9e7eaa](https://linux-hardware.org/?probe=56cd9e7eaa) | Jul 18, 2021 |
| HP            | 0AECh D                     | [9b91275879](https://linux-hardware.org/?probe=9b91275879) | Jul 13, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [497c16be4b](https://linux-hardware.org/?probe=497c16be4b) | Jul 12, 2021 |
| HP            | 0AECh D                     | [540f6d1b4e](https://linux-hardware.org/?probe=540f6d1b4e) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [7adcf7dc7c](https://linux-hardware.org/?probe=7adcf7dc7c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| ASRock        | H67M                        | [660e47da08](https://linux-hardware.org/?probe=660e47da08) | Jul 08, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e8044f366](https://linux-hardware.org/?probe=1e8044f366) | Jul 07, 2021 |
| MSI           | A78M-E35                    | [cef9d93dd1](https://linux-hardware.org/?probe=cef9d93dd1) | Jul 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [647b8b3725](https://linux-hardware.org/?probe=647b8b3725) | Jul 02, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [9a49b1159d](https://linux-hardware.org/?probe=9a49b1159d) | Jul 01, 2021 |
| ASUSTek       | Maximus VII HERO            | [0e605c5229](https://linux-hardware.org/?probe=0e605c5229) | Jun 26, 2021 |
| Dell          | 0T7D40 A01                  | [5ee785eb32](https://linux-hardware.org/?probe=5ee785eb32) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dbc4494db2](https://linux-hardware.org/?probe=dbc4494db2) | Jun 23, 2021 |
| Gigabyte      | X570 AORUS PRO              | [ea70f9fe3b](https://linux-hardware.org/?probe=ea70f9fe3b) | Jun 23, 2021 |
| MSI           | Z170A SLI PLUS              | [d715625644](https://linux-hardware.org/?probe=d715625644) | Jun 22, 2021 |
| Unknown       | Unknown                     | [489dc53e4d](https://linux-hardware.org/?probe=489dc53e4d) | Jun 20, 2021 |
| Unknown       | Unknown                     | [077a1849dd](https://linux-hardware.org/?probe=077a1849dd) | Jun 20, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [bd42ad29b1](https://linux-hardware.org/?probe=bd42ad29b1) | Jun 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [42e10b10fd](https://linux-hardware.org/?probe=42e10b10fd) | Jun 15, 2021 |
| Gigabyte      | Z590 VISION G               | [c3b20ee137](https://linux-hardware.org/?probe=c3b20ee137) | Jun 12, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Lenovo        | SDK0E50510 WIN 262508179... | [489ce4720c](https://linux-hardware.org/?probe=489ce4720c) | Jun 06, 2021 |
| ASRock        | H87 Pro4                    | [5f78dd5211](https://linux-hardware.org/?probe=5f78dd5211) | Jun 06, 2021 |
| ASUSTek       | P7P55D LE                   | [5e58b5909b](https://linux-hardware.org/?probe=5e58b5909b) | Jun 04, 2021 |
| ASUSTek       | P7P55D LE                   | [119ec1d3ba](https://linux-hardware.org/?probe=119ec1d3ba) | Jun 04, 2021 |
| Gigabyte      | Z590 VISION G               | [ea4492aeee](https://linux-hardware.org/?probe=ea4492aeee) | May 30, 2021 |
| MSI           | H97 PC Mate                 | [05dcac5e7f](https://linux-hardware.org/?probe=05dcac5e7f) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | [ef3b21caf0](https://linux-hardware.org/?probe=ef3b21caf0) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | [02fee32807](https://linux-hardware.org/?probe=02fee32807) | May 29, 2021 |
| HP            | 1495                        | [660c4ff2ed](https://linux-hardware.org/?probe=660c4ff2ed) | May 28, 2021 |
| ASRock        | J5040-ITX                   | [5ffe86e682](https://linux-hardware.org/?probe=5ffe86e682) | May 28, 2021 |
| Medion        | B460H6-EM                   | [0b9ae4f256](https://linux-hardware.org/?probe=0b9ae4f256) | May 28, 2021 |
| HP            | 198E                        | [39fd78a563](https://linux-hardware.org/?probe=39fd78a563) | May 26, 2021 |
| MSI           | X570-A PRO                  | [49eb802c2e](https://linux-hardware.org/?probe=49eb802c2e) | May 25, 2021 |
| ASRock        | A320M-HDV R4.0              | [2983d7e745](https://linux-hardware.org/?probe=2983d7e745) | May 25, 2021 |
| ASRock        | Z170 Extreme7+              | [324df6eb69](https://linux-hardware.org/?probe=324df6eb69) | May 25, 2021 |
| ASRock        | H77M                        | [3a362598fb](https://linux-hardware.org/?probe=3a362598fb) | May 23, 2021 |
| ASUSTek       | J1900I-C                    | [560fd63326](https://linux-hardware.org/?probe=560fd63326) | May 21, 2021 |
| ASRock        | B365M Pro4-F                | [9b31a1e94f](https://linux-hardware.org/?probe=9b31a1e94f) | May 21, 2021 |
| ASRock        | H77M                        | [e3d59b843a](https://linux-hardware.org/?probe=e3d59b843a) | May 21, 2021 |
| ASRock        | 970 Pro3 R2.0               | [d811152e10](https://linux-hardware.org/?probe=d811152e10) | May 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [daf3bcdc44](https://linux-hardware.org/?probe=daf3bcdc44) | May 18, 2021 |
| ASUSTek       | P5B                         | [ff621cb51a](https://linux-hardware.org/?probe=ff621cb51a) | May 17, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [c11404a76b](https://linux-hardware.org/?probe=c11404a76b) | May 14, 2021 |
| MSI           | H97 PC Mate                 | [14457815f8](https://linux-hardware.org/?probe=14457815f8) | May 13, 2021 |
| ASUSTek       | P8H77-M PRO                 | [524de3a747](https://linux-hardware.org/?probe=524de3a747) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [daf2cdf31f](https://linux-hardware.org/?probe=daf2cdf31f) | May 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [70628bdf55](https://linux-hardware.org/?probe=70628bdf55) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| Gigabyte      | B450M S2H                   | [9e1c2c1ffd](https://linux-hardware.org/?probe=9e1c2c1ffd) | May 05, 2021 |
| Biostar       | A78MD                       | [3f56e00dd2](https://linux-hardware.org/?probe=3f56e00dd2) | May 04, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [573b65efbd](https://linux-hardware.org/?probe=573b65efbd) | May 02, 2021 |
| HP            | 844C                        | [913d5aff80](https://linux-hardware.org/?probe=913d5aff80) | Apr 30, 2021 |
| ASRock        | H110 Pro BTC+               | [799ad15d8b](https://linux-hardware.org/?probe=799ad15d8b) | Apr 30, 2021 |
| ASRock        | Z170 Extreme6+              | [74e3dec02b](https://linux-hardware.org/?probe=74e3dec02b) | Apr 29, 2021 |
| ASRock        | Z170 Extreme6+              | [7f2a8a7ab8](https://linux-hardware.org/?probe=7f2a8a7ab8) | Apr 29, 2021 |
| Dell          | 0Y7WYT A00                  | [399bf0d60e](https://linux-hardware.org/?probe=399bf0d60e) | Apr 28, 2021 |
| HP            | 304Bh                       | [dc42bd8e41](https://linux-hardware.org/?probe=dc42bd8e41) | Apr 27, 2021 |
| ASUSTek       | GRYPHON Z87                 | [8a54738ba0](https://linux-hardware.org/?probe=8a54738ba0) | Apr 26, 2021 |
| MSI           | X570-A PRO                  | [1a7d9facd2](https://linux-hardware.org/?probe=1a7d9facd2) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | P4i65G                      | [3818ed802a](https://linux-hardware.org/?probe=3818ed802a) | Apr 24, 2021 |
| Sapphire      | PI-AM3RS760G2               | [f54647d31e](https://linux-hardware.org/?probe=f54647d31e) | Apr 24, 2021 |
| MSI           | MS-7091                     | [f5d9a3ba0e](https://linux-hardware.org/?probe=f5d9a3ba0e) | Apr 19, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ca0c473e06](https://linux-hardware.org/?probe=ca0c473e06) | Apr 18, 2021 |
| MSI           | X570-A PRO                  | [c4e4afedd6](https://linux-hardware.org/?probe=c4e4afedd6) | Apr 17, 2021 |
| ASUSTek       | J1900I-C                    | [e980e0a528](https://linux-hardware.org/?probe=e980e0a528) | Apr 17, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [12b9e4bb0f](https://linux-hardware.org/?probe=12b9e4bb0f) | Apr 16, 2021 |
| ASUSTek       | M2N-MX                      | [8dd14baaf0](https://linux-hardware.org/?probe=8dd14baaf0) | Apr 16, 2021 |
| Medion        | MS-7713                     | [0acac9a543](https://linux-hardware.org/?probe=0acac9a543) | Apr 13, 2021 |
| ASRock        | X370 Taichi                 | [fbefa3cd0b](https://linux-hardware.org/?probe=fbefa3cd0b) | Apr 11, 2021 |
| ASUSTek       | P5QPL-AM                    | [b609880289](https://linux-hardware.org/?probe=b609880289) | Apr 10, 2021 |
| Acer          | Veriton M480                | [a7a0203b44](https://linux-hardware.org/?probe=a7a0203b44) | Apr 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [e4dcbccb5c](https://linux-hardware.org/?probe=e4dcbccb5c) | Apr 05, 2021 |
| MSI           | X570-A PRO                  | [465d54d765](https://linux-hardware.org/?probe=465d54d765) | Apr 05, 2021 |
| Acer          | Nitro N50-600 V:1.1         | [e7ddf93f9f](https://linux-hardware.org/?probe=e7ddf93f9f) | Apr 04, 2021 |
| Acer          | Nitro N50-600 V:1.1         | [b281b84f5b](https://linux-hardware.org/?probe=b281b84f5b) | Apr 04, 2021 |
| MSI           | Z77 MPower                  | [a6d2710163](https://linux-hardware.org/?probe=a6d2710163) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [7100e0c7bc](https://linux-hardware.org/?probe=7100e0c7bc) | Mar 30, 2021 |
| ASRock        | J3160-NUC                   | [3f44c1a54f](https://linux-hardware.org/?probe=3f44c1a54f) | Mar 28, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [6e36a57c6d](https://linux-hardware.org/?probe=6e36a57c6d) | Mar 28, 2021 |
| Medion        | B550A4-EM                   | [641ec219ff](https://linux-hardware.org/?probe=641ec219ff) | Mar 27, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ed38cf686e](https://linux-hardware.org/?probe=ed38cf686e) | Mar 26, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [70072ce040](https://linux-hardware.org/?probe=70072ce040) | Mar 26, 2021 |
| Lenovo        | SHARKBAY NOK                | [87a2ba2f24](https://linux-hardware.org/?probe=87a2ba2f24) | Mar 25, 2021 |
| ASRock        | Z87 Extreme3                | [702e348746](https://linux-hardware.org/?probe=702e348746) | Mar 25, 2021 |
| ASUSTek       | F2A85-V                     | [a393c07087](https://linux-hardware.org/?probe=a393c07087) | Mar 20, 2021 |
| HP            | 1494                        | [8aec7a3cbf](https://linux-hardware.org/?probe=8aec7a3cbf) | Mar 20, 2021 |
| MSI           | B450-A PRO MAX              | [1f8eee9aa4](https://linux-hardware.org/?probe=1f8eee9aa4) | Mar 18, 2021 |
| HP            | 1998                        | [43924e927e](https://linux-hardware.org/?probe=43924e927e) | Mar 18, 2021 |
| HP            | 1998                        | [c98634a421](https://linux-hardware.org/?probe=c98634a421) | Mar 18, 2021 |
| MSI           | B450-A PRO MAX              | [a15b0ecd7b](https://linux-hardware.org/?probe=a15b0ecd7b) | Mar 18, 2021 |
| ASUSTek       | P8Z68-V LX                  | [d1673f61bc](https://linux-hardware.org/?probe=d1673f61bc) | Mar 17, 2021 |
| ASRock        | H77M                        | [13d87f3380](https://linux-hardware.org/?probe=13d87f3380) | Mar 16, 2021 |
| ASRock        | H77M                        | [f7f669b943](https://linux-hardware.org/?probe=f7f669b943) | Mar 14, 2021 |
| ASRock        | B365M Pro4-F                | [0c6489fca5](https://linux-hardware.org/?probe=0c6489fca5) | Mar 14, 2021 |
| ASUSTek       | Z170-A                      | [2fe6674c71](https://linux-hardware.org/?probe=2fe6674c71) | Mar 13, 2021 |
| ASRock        | X570 Taichi                 | [31906d8b73](https://linux-hardware.org/?probe=31906d8b73) | Mar 13, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [41735bfb3d](https://linux-hardware.org/?probe=41735bfb3d) | Mar 12, 2021 |
| ASUSTek       | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| MSI           | H81M-P33                    | [5498e38a32](https://linux-hardware.org/?probe=5498e38a32) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [74c947442a](https://linux-hardware.org/?probe=74c947442a) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a35ded4130](https://linux-hardware.org/?probe=a35ded4130) | Mar 09, 2021 |
| ASRock        | A300M-STX                   | [6377ea853f](https://linux-hardware.org/?probe=6377ea853f) | Mar 07, 2021 |
| ASUSTek       | P5Q3                        | [dd50fe59b2](https://linux-hardware.org/?probe=dd50fe59b2) | Mar 07, 2021 |
| MSI           | Z87-G45 GAMING              | [3464f180fe](https://linux-hardware.org/?probe=3464f180fe) | Mar 04, 2021 |
| Biostar       | A78MD                       | [0bd08c0771](https://linux-hardware.org/?probe=0bd08c0771) | Mar 02, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [332fc8bbcf](https://linux-hardware.org/?probe=332fc8bbcf) | Mar 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [94a4e1db49](https://linux-hardware.org/?probe=94a4e1db49) | Feb 28, 2021 |
| Biostar       | A78MD                       | [06b1319f09](https://linux-hardware.org/?probe=06b1319f09) | Feb 28, 2021 |
| Biostar       | A78MD                       | [6aff42d829](https://linux-hardware.org/?probe=6aff42d829) | Feb 28, 2021 |
| Biostar       | A78MD                       | [c468e84e6d](https://linux-hardware.org/?probe=c468e84e6d) | Feb 28, 2021 |
| MSI           | Z97 GAMING 9 ACK            | [11e9217472](https://linux-hardware.org/?probe=11e9217472) | Feb 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [cb866ef0ba](https://linux-hardware.org/?probe=cb866ef0ba) | Feb 28, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [8ad661d01b](https://linux-hardware.org/?probe=8ad661d01b) | Feb 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [95f839ef17](https://linux-hardware.org/?probe=95f839ef17) | Feb 26, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [fe1a81c6bc](https://linux-hardware.org/?probe=fe1a81c6bc) | Feb 24, 2021 |
| Gigabyte      | A520M S2H                   | [f502acb72d](https://linux-hardware.org/?probe=f502acb72d) | Feb 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| ASUSTek       | F2A85-V                     | [48e9166aea](https://linux-hardware.org/?probe=48e9166aea) | Feb 21, 2021 |
| ASUSTek       | M5A99X EVO                  | [2300d9d1f9](https://linux-hardware.org/?probe=2300d9d1f9) | Feb 20, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [b0af95e7a7](https://linux-hardware.org/?probe=b0af95e7a7) | Feb 20, 2021 |
| Gigabyte      | GA-MA78LMT-S2               | [a642c82f46](https://linux-hardware.org/?probe=a642c82f46) | Feb 19, 2021 |
| MSI           | A320M-A PRO MAX             | [f22bf6b05d](https://linux-hardware.org/?probe=f22bf6b05d) | Feb 18, 2021 |
| HP            | ProLiant ML30 Gen9          | [f6af5a4d70](https://linux-hardware.org/?probe=f6af5a4d70) | Feb 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [015f4f6c33](https://linux-hardware.org/?probe=015f4f6c33) | Feb 15, 2021 |
| ASUSTek       | Z87-C                       | [601b3fd251](https://linux-hardware.org/?probe=601b3fd251) | Feb 14, 2021 |
| ASUSTek       | B85-PRO GAMER               | [3cd9ecf495](https://linux-hardware.org/?probe=3cd9ecf495) | Feb 14, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [105a38c590](https://linux-hardware.org/?probe=105a38c590) | Feb 14, 2021 |
| ASRock        | Z77 Pro3                    | [d129998ffb](https://linux-hardware.org/?probe=d129998ffb) | Feb 13, 2021 |
| Gigabyte      | 970A-DS3P                   | [bdecca84fa](https://linux-hardware.org/?probe=bdecca84fa) | Feb 13, 2021 |
| ASRock        | Z77 Pro3                    | [06b57f0a75](https://linux-hardware.org/?probe=06b57f0a75) | Feb 13, 2021 |
| Dell          | 0WWJRX A00                  | [a3efc0b825](https://linux-hardware.org/?probe=a3efc0b825) | Feb 13, 2021 |
| ASUSTek       | P5QPL-AM                    | [d51e8f5abc](https://linux-hardware.org/?probe=d51e8f5abc) | Feb 10, 2021 |
| ASUSTek       | M2N-MX                      | [c8ae57e616](https://linux-hardware.org/?probe=c8ae57e616) | Feb 07, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Dell          | 05XGC8 A01                  | [910c9c3e21](https://linux-hardware.org/?probe=910c9c3e21) | Feb 01, 2021 |
| Dell          | 05XGC8 A01                  | [46719a0e53](https://linux-hardware.org/?probe=46719a0e53) | Feb 01, 2021 |
| Dell          | 05XGC8 A01                  | [b1c22c1894](https://linux-hardware.org/?probe=b1c22c1894) | Feb 01, 2021 |
| ASUSTek       | P5Q                         | [037cf0158e](https://linux-hardware.org/?probe=037cf0158e) | Jan 30, 2021 |
| ASUSTek       | P5Q                         | [aaa6e7b901](https://linux-hardware.org/?probe=aaa6e7b901) | Jan 30, 2021 |
| ASRock        | Z77 Pro3                    | [ea0df821be](https://linux-hardware.org/?probe=ea0df821be) | Jan 28, 2021 |
| ASRock        | Z77 Pro3                    | [9592e5cbb6](https://linux-hardware.org/?probe=9592e5cbb6) | Jan 28, 2021 |
| HP            | 3646h                       | [e540758f9c](https://linux-hardware.org/?probe=e540758f9c) | Jan 26, 2021 |
| ASUSTek       | PRIME Z270-A                | [e6f737276c](https://linux-hardware.org/?probe=e6f737276c) | Jan 25, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [5d23694899](https://linux-hardware.org/?probe=5d23694899) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| MSI           | Z97 GAMING 5                | [8da68cf0c1](https://linux-hardware.org/?probe=8da68cf0c1) | Jan 20, 2021 |
| HP            | 1998                        | [06c680725c](https://linux-hardware.org/?probe=06c680725c) | Jan 19, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [536f80b3b5](https://linux-hardware.org/?probe=536f80b3b5) | Jan 17, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7d647c8ecb](https://linux-hardware.org/?probe=7d647c8ecb) | Jan 16, 2021 |
| MSI           | MS-7A66                     | [083df1e870](https://linux-hardware.org/?probe=083df1e870) | Jan 16, 2021 |
| ASRock        | X470 Taichi                 | [d7179bef44](https://linux-hardware.org/?probe=d7179bef44) | Jan 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [742e66b7f0](https://linux-hardware.org/?probe=742e66b7f0) | Jan 12, 2021 |
| ASRock        | X470 Taichi                 | [da311c1d96](https://linux-hardware.org/?probe=da311c1d96) | Jan 11, 2021 |
| ASRock        | B450 Steel Legend           | [2b825ca52c](https://linux-hardware.org/?probe=2b825ca52c) | Jan 11, 2021 |
| HP            | 0AECh D                     | [8ae3501e15](https://linux-hardware.org/?probe=8ae3501e15) | Jan 10, 2021 |
| Lenovo        | MAHOBAY                     | [6186295ee1](https://linux-hardware.org/?probe=6186295ee1) | Jan 10, 2021 |
| MSI           | Z390-A PRO                  | [5927c2d7dd](https://linux-hardware.org/?probe=5927c2d7dd) | Jan 09, 2021 |
| Intel         | B75                         | [991f6ce47d](https://linux-hardware.org/?probe=991f6ce47d) | Jan 09, 2021 |
| Intel         | B75                         | [f2aa38279b](https://linux-hardware.org/?probe=f2aa38279b) | Jan 09, 2021 |
| Gigabyte      | B550M AORUS PRO             | [32a3812ca0](https://linux-hardware.org/?probe=32a3812ca0) | Jan 08, 2021 |
| HP            | 0AECh D                     | [d870844e43](https://linux-hardware.org/?probe=d870844e43) | Jan 08, 2021 |
| ASUSTek       | P8Z77-V LX                  | [c5ed6d05c0](https://linux-hardware.org/?probe=c5ed6d05c0) | Jan 08, 2021 |
| MSI           | H110 PC MATE                | [e4353652f8](https://linux-hardware.org/?probe=e4353652f8) | Jan 07, 2021 |
| Medion        | MS-7707                     | [c48264f558](https://linux-hardware.org/?probe=c48264f558) | Jan 06, 2021 |
| ASUSTek       | Z97-AR                      | [7bb75eb062](https://linux-hardware.org/?probe=7bb75eb062) | Jan 04, 2021 |
| ASRock        | B450 Steel Legend           | [11ee0a81c2](https://linux-hardware.org/?probe=11ee0a81c2) | Jan 03, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [feb58a7b82](https://linux-hardware.org/?probe=feb58a7b82) | Jan 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [f3aa67a60f](https://linux-hardware.org/?probe=f3aa67a60f) | Jan 02, 2021 |
| HP            | 0AACh                       | [73e545d08e](https://linux-hardware.org/?probe=73e545d08e) | Dec 30, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [7443ed9c8e](https://linux-hardware.org/?probe=7443ed9c8e) | Dec 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [7774d76390](https://linux-hardware.org/?probe=7774d76390) | Dec 29, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a747cbbc12](https://linux-hardware.org/?probe=a747cbbc12) | Dec 29, 2020 |
| ASUSTek       | P8H77-M PRO                 | [7479398d6b](https://linux-hardware.org/?probe=7479398d6b) | Dec 26, 2020 |
| ASUSTek       | P8H77-M PRO                 | [dae4f56b87](https://linux-hardware.org/?probe=dae4f56b87) | Dec 26, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [14d8088058](https://linux-hardware.org/?probe=14d8088058) | Dec 26, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [5f9cd7bf8d](https://linux-hardware.org/?probe=5f9cd7bf8d) | Dec 26, 2020 |
| Gigabyte      | H61M-S2PV                   | [c8192fa1b8](https://linux-hardware.org/?probe=c8192fa1b8) | Dec 25, 2020 |
| ASUSTek       | Z87-A                       | [1f96153282](https://linux-hardware.org/?probe=1f96153282) | Dec 24, 2020 |
| MSI           | B450M MORTAR MAX            | [95d87e6473](https://linux-hardware.org/?probe=95d87e6473) | Dec 22, 2020 |
| ASRock        | 970 Extreme4                | [036cbb8abd](https://linux-hardware.org/?probe=036cbb8abd) | Dec 19, 2020 |
| ASRock        | 970 Extreme4                | [076e600b98](https://linux-hardware.org/?probe=076e600b98) | Dec 17, 2020 |
| ASRock        | 970 Extreme4                | [c772b379fb](https://linux-hardware.org/?probe=c772b379fb) | Dec 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [52ea92c087](https://linux-hardware.org/?probe=52ea92c087) | Dec 11, 2020 |
| Gigabyte      | B460M D3H                   | [5a7f0069e7](https://linux-hardware.org/?probe=5a7f0069e7) | Dec 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | [ba214d2a0b](https://linux-hardware.org/?probe=ba214d2a0b) | Dec 08, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | [3597a3315a](https://linux-hardware.org/?probe=3597a3315a) | Dec 07, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| ASUSTek       | Rampage II GENE             | [c551fbc02b](https://linux-hardware.org/?probe=c551fbc02b) | Dec 05, 2020 |
| Medion        | MS-7785                     | [7db825feae](https://linux-hardware.org/?probe=7db825feae) | Dec 05, 2020 |
| HP            | 83E1                        | [b02eab0d7b](https://linux-hardware.org/?probe=b02eab0d7b) | Dec 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2745a37c0a](https://linux-hardware.org/?probe=2745a37c0a) | Dec 02, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [4f5d0b5689](https://linux-hardware.org/?probe=4f5d0b5689) | Dec 02, 2020 |
| HP            | 304Ah                       | [e0127b5745](https://linux-hardware.org/?probe=e0127b5745) | Dec 02, 2020 |
| MSI           | H110 PC MATE                | [1ace18d8c6](https://linux-hardware.org/?probe=1ace18d8c6) | Dec 02, 2020 |
| MSI           | X570-A PRO                  | [619a44519d](https://linux-hardware.org/?probe=619a44519d) | Nov 26, 2020 |
| MSI           | X570-A PRO                  | [4da3e1e733](https://linux-hardware.org/?probe=4da3e1e733) | Nov 25, 2020 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [c7afad637f](https://linux-hardware.org/?probe=c7afad637f) | Nov 21, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| ASUSTek       | P6T SE                      | [ab5ae06143](https://linux-hardware.org/?probe=ab5ae06143) | Nov 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [4a2a55be34](https://linux-hardware.org/?probe=4a2a55be34) | Nov 19, 2020 |
| ASUSTek       | Z170-A                      | [7ecb8cf20c](https://linux-hardware.org/?probe=7ecb8cf20c) | Nov 18, 2020 |
| ASUSTek       | P5Q3                        | [7aea73f517](https://linux-hardware.org/?probe=7aea73f517) | Nov 18, 2020 |
| MSI           | B450 TOMAHAWK               | [12ad3a5613](https://linux-hardware.org/?probe=12ad3a5613) | Nov 17, 2020 |
| Unknown       | 1.21                        | [03bbb3fe9d](https://linux-hardware.org/?probe=03bbb3fe9d) | Nov 17, 2020 |
| MSI           | 970 GAMING                  | [ad2e6869d2](https://linux-hardware.org/?probe=ad2e6869d2) | Nov 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [dad48b0b71](https://linux-hardware.org/?probe=dad48b0b71) | Nov 15, 2020 |
| ASUSTek       | SABERTOOTH X79              | [85af1aa380](https://linux-hardware.org/?probe=85af1aa380) | Nov 15, 2020 |
| MSI           | B450-A PRO MAX              | [174f09979c](https://linux-hardware.org/?probe=174f09979c) | Nov 15, 2020 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [afa9fa19f7](https://linux-hardware.org/?probe=afa9fa19f7) | Nov 13, 2020 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [848659f1bb](https://linux-hardware.org/?probe=848659f1bb) | Nov 13, 2020 |
| HP            | 304Bh                       | [eabe5c6576](https://linux-hardware.org/?probe=eabe5c6576) | Nov 12, 2020 |
| HP            | 1998                        | [ba70213a7c](https://linux-hardware.org/?probe=ba70213a7c) | Nov 12, 2020 |
| HP            | 304Bh                       | [2a0818c8b9](https://linux-hardware.org/?probe=2a0818c8b9) | Nov 12, 2020 |
| Dell          | 0KWVT8 A02                  | [f5beb28b88](https://linux-hardware.org/?probe=f5beb28b88) | Nov 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1eaf5979d8](https://linux-hardware.org/?probe=1eaf5979d8) | Nov 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a0619b8d1d](https://linux-hardware.org/?probe=a0619b8d1d) | Nov 10, 2020 |
| ASUSTek       | Z170-DELUXE                 | [ece6cbfa68](https://linux-hardware.org/?probe=ece6cbfa68) | Nov 10, 2020 |
| ASUSTek       | Rampage II GENE             | [bf53346564](https://linux-hardware.org/?probe=bf53346564) | Nov 10, 2020 |
| ASUSTek       | PRIME A320M-K               | [901ff66119](https://linux-hardware.org/?probe=901ff66119) | Nov 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [e84ecfe5e0](https://linux-hardware.org/?probe=e84ecfe5e0) | Nov 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [f33a623bd5](https://linux-hardware.org/?probe=f33a623bd5) | Nov 08, 2020 |
| MSI           | B450-A PRO MAX              | [5052705b44](https://linux-hardware.org/?probe=5052705b44) | Nov 07, 2020 |
| MSI           | B450-A PRO MAX              | [aa0cd52789](https://linux-hardware.org/?probe=aa0cd52789) | Nov 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8090d5d13d](https://linux-hardware.org/?probe=8090d5d13d) | Nov 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [33b552fa2a](https://linux-hardware.org/?probe=33b552fa2a) | Nov 07, 2020 |
| Medion        | MS-7800                     | [2bda8fb463](https://linux-hardware.org/?probe=2bda8fb463) | Nov 06, 2020 |
| ASUSTek       | Z87M-PLUS                   | [fe30aa6977](https://linux-hardware.org/?probe=fe30aa6977) | Nov 06, 2020 |
| MSI           | 970 GAMING                  | [8787720406](https://linux-hardware.org/?probe=8787720406) | Nov 06, 2020 |
| ASUSTek       | Z170-DELUXE                 | [5b260893c7](https://linux-hardware.org/?probe=5b260893c7) | Nov 04, 2020 |
| Gigabyte      | H61M-S2PV                   | [3ddf6dd16e](https://linux-hardware.org/?probe=3ddf6dd16e) | Nov 02, 2020 |
| Gigabyte      | H61M-S2PV                   | [602a208acb](https://linux-hardware.org/?probe=602a208acb) | Nov 02, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| MSI           | Z390-A PRO                  | [7e3367f5de](https://linux-hardware.org/?probe=7e3367f5de) | Oct 31, 2020 |
| Gigabyte      | B550M AORUS PRO             | [cc234953ee](https://linux-hardware.org/?probe=cc234953ee) | Oct 29, 2020 |
| Gigabyte      | B550M AORUS PRO             | [8694779259](https://linux-hardware.org/?probe=8694779259) | Oct 28, 2020 |
| Gigabyte      | 990FXA-UD3                  | [2640f19771](https://linux-hardware.org/?probe=2640f19771) | Oct 27, 2020 |
| MSI           | B450-A PRO                  | [8d3080c24b](https://linux-hardware.org/?probe=8d3080c24b) | Oct 27, 2020 |
| Gigabyte      | 990FXA-UD3                  | [edad386a06](https://linux-hardware.org/?probe=edad386a06) | Oct 26, 2020 |
| Dell          | 0KWVT8 A02                  | [6067b5fdca](https://linux-hardware.org/?probe=6067b5fdca) | Oct 26, 2020 |
| MSI           | 785G-E53                    | [896761d94a](https://linux-hardware.org/?probe=896761d94a) | Oct 26, 2020 |
| MSI           | B450-A PRO                  | [2af48de4a6](https://linux-hardware.org/?probe=2af48de4a6) | Oct 25, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [18dfc7eccc](https://linux-hardware.org/?probe=18dfc7eccc) | Oct 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [1e299c5dbc](https://linux-hardware.org/?probe=1e299c5dbc) | Oct 20, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [e6d077732c](https://linux-hardware.org/?probe=e6d077732c) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c37609a667](https://linux-hardware.org/?probe=c37609a667) | Oct 18, 2020 |
| ASRock        | H55M/USB3                   | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| ASRock        | B75 Pro3-M                  | [d8b4105b7c](https://linux-hardware.org/?probe=d8b4105b7c) | Oct 18, 2020 |
| Intel         | DN2820FYK H24582-202        | [64105a10e1](https://linux-hardware.org/?probe=64105a10e1) | Oct 13, 2020 |
| ASUSTek       | Z97-DELUXE                  | [5bfe608b47](https://linux-hardware.org/?probe=5bfe608b47) | Oct 12, 2020 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [648cae37e8](https://linux-hardware.org/?probe=648cae37e8) | Oct 11, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0G261D A00                  | [f42ed32356](https://linux-hardware.org/?probe=f42ed32356) | Oct 08, 2020 |
| ASRock        | Z170 Extreme4               | [b6708fc3ec](https://linux-hardware.org/?probe=b6708fc3ec) | Oct 08, 2020 |
| ASRock        | Z170 Extreme4               | [67f95905f8](https://linux-hardware.org/?probe=67f95905f8) | Oct 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [becb2dabd4](https://linux-hardware.org/?probe=becb2dabd4) | Oct 02, 2020 |
| Gigabyte      | Z77-D3H                     | [12b1ada1b7](https://linux-hardware.org/?probe=12b1ada1b7) | Oct 01, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [019f1044f5](https://linux-hardware.org/?probe=019f1044f5) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [34ab2deca5](https://linux-hardware.org/?probe=34ab2deca5) | Sep 30, 2020 |
| Lenovo        | ThinkCentre A55 96417RG     | [e66b41beda](https://linux-hardware.org/?probe=e66b41beda) | Sep 30, 2020 |
| Lenovo        | ThinkCentre A55 96417RG     | [40217b727c](https://linux-hardware.org/?probe=40217b727c) | Sep 30, 2020 |
| HP            | 3396                        | [08d4e10fe8](https://linux-hardware.org/?probe=08d4e10fe8) | Sep 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [d1379f41e9](https://linux-hardware.org/?probe=d1379f41e9) | Sep 28, 2020 |
| MSI           | X470 GAMING PLUS            | [1f88d959a3](https://linux-hardware.org/?probe=1f88d959a3) | Sep 28, 2020 |
| MSI           | H170A PC MATE               | [1ccbc6d2a3](https://linux-hardware.org/?probe=1ccbc6d2a3) | Sep 26, 2020 |
| HP            | 3396                        | [54a44b3423](https://linux-hardware.org/?probe=54a44b3423) | Sep 24, 2020 |
| Gigabyte      | B550M AORUS PRO             | [f4ca6f2be3](https://linux-hardware.org/?probe=f4ca6f2be3) | Sep 24, 2020 |
| ASUSTek       | P9X79 PRO                   | [6cdc4d7b68](https://linux-hardware.org/?probe=6cdc4d7b68) | Sep 18, 2020 |
| MSI           | A68HM-E33 V2                | [f3b0511fad](https://linux-hardware.org/?probe=f3b0511fad) | Sep 16, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [2a2f29d4f4](https://linux-hardware.org/?probe=2a2f29d4f4) | Sep 13, 2020 |
| MSI           | X470 GAMING PLUS            | [c863e26606](https://linux-hardware.org/?probe=c863e26606) | Sep 13, 2020 |
| Gigabyte      | 970A-UD3                    | [d54620a8e6](https://linux-hardware.org/?probe=d54620a8e6) | Sep 04, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [e5f0dd8145](https://linux-hardware.org/?probe=e5f0dd8145) | Sep 04, 2020 |
| ASUSTek       | NODUSM3                     | [f8d3ca460a](https://linux-hardware.org/?probe=f8d3ca460a) | Sep 04, 2020 |
| MSI           | Z97-G45 GAMING              | [23d327ddd1](https://linux-hardware.org/?probe=23d327ddd1) | Sep 02, 2020 |
| Medion        | MS-7800                     | [350be22d12](https://linux-hardware.org/?probe=350be22d12) | Sep 02, 2020 |
| Gigabyte      | B550M AORUS PRO             | [a4b94dc9a0](https://linux-hardware.org/?probe=a4b94dc9a0) | Sep 02, 2020 |
| MSI           | MS-7502 Fab D               | [90f4a91dab](https://linux-hardware.org/?probe=90f4a91dab) | Sep 02, 2020 |
| MSI           | MS-7502 Fab D               | [bb820cc0f5](https://linux-hardware.org/?probe=bb820cc0f5) | Sep 02, 2020 |
| ASRock        | TRX40 Creator               | [e8bbe1674e](https://linux-hardware.org/?probe=e8bbe1674e) | Sep 01, 2020 |
| Gigabyte      | B250-FinTech-CF             | [0b97759dbc](https://linux-hardware.org/?probe=0b97759dbc) | Aug 31, 2020 |
| Gigabyte      | H370M DS3H-CF               | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9c6deccbd7](https://linux-hardware.org/?probe=9c6deccbd7) | Aug 29, 2020 |
| ASRock        | TRX40 Creator               | [3e63a6cb23](https://linux-hardware.org/?probe=3e63a6cb23) | Aug 29, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [804af7bd77](https://linux-hardware.org/?probe=804af7bd77) | Aug 29, 2020 |
| MSI           | B450 TOMAHAWK               | [8d2a486570](https://linux-hardware.org/?probe=8d2a486570) | Aug 23, 2020 |
| Gigabyte      | 970A-UD3                    | [a5bc169d85](https://linux-hardware.org/?probe=a5bc169d85) | Aug 19, 2020 |
| ASUSTek       | M5A99X EVO                  | [6aae8e8b65](https://linux-hardware.org/?probe=6aae8e8b65) | Aug 12, 2020 |
| ASUSTek       | P5KC                        | [9fb165eec5](https://linux-hardware.org/?probe=9fb165eec5) | Aug 10, 2020 |
| Gigabyte      | X570 GAMING X               | [cf865f40d3](https://linux-hardware.org/?probe=cf865f40d3) | Aug 10, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [ba1dcb2d6a](https://linux-hardware.org/?probe=ba1dcb2d6a) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [eea93c64ef](https://linux-hardware.org/?probe=eea93c64ef) | Aug 04, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5f6337d416](https://linux-hardware.org/?probe=5f6337d416) | Aug 04, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [9bc233d847](https://linux-hardware.org/?probe=9bc233d847) | Jul 28, 2020 |
| ASUSTek       | M5A97 PRO                   | [2feb4909d3](https://linux-hardware.org/?probe=2feb4909d3) | Jul 26, 2020 |
| ASUSTek       | PRIME X570-P                | [57be047558](https://linux-hardware.org/?probe=57be047558) | Jul 21, 2020 |
| ASRock        | Z87M Extreme4               | [c964d8e6aa](https://linux-hardware.org/?probe=c964d8e6aa) | Jul 17, 2020 |
| ASRock        | Z87M Extreme4               | [647e26f9c0](https://linux-hardware.org/?probe=647e26f9c0) | Jul 17, 2020 |
| MSI           | B360 GAMING PRO CARBON      | [878e756625](https://linux-hardware.org/?probe=878e756625) | Jul 13, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [89a4e31a34](https://linux-hardware.org/?probe=89a4e31a34) | Jul 12, 2020 |
| ASUSTek       | P5KC                        | [b43325a5a2](https://linux-hardware.org/?probe=b43325a5a2) | Jul 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [f680a985bf](https://linux-hardware.org/?probe=f680a985bf) | Jul 06, 2020 |
| ASUSTek       | SABERTOOTH X58              | [dc448a83c5](https://linux-hardware.org/?probe=dc448a83c5) | Jul 06, 2020 |
| ASUSTek       | SABERTOOTH X58              | [a4a160f8f5](https://linux-hardware.org/?probe=a4a160f8f5) | Jul 06, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [e4db7317e2](https://linux-hardware.org/?probe=e4db7317e2) | Jul 03, 2020 |
| Foxconn       | NETBOX NT-425/525 Ver       | [bdce37f0a6](https://linux-hardware.org/?probe=bdce37f0a6) | Jul 02, 2020 |
| Acer          | Veriton X4630G              | [504ec0d230](https://linux-hardware.org/?probe=504ec0d230) | Jun 30, 2020 |
| MSI           | 760GM-P23                   | [c130373ac8](https://linux-hardware.org/?probe=c130373ac8) | Jun 29, 2020 |
| ASUSTek       | P7H55-M PRO                 | [76aa2e624e](https://linux-hardware.org/?probe=76aa2e624e) | Jun 28, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | [120fd84f28](https://linux-hardware.org/?probe=120fd84f28) | Jun 26, 2020 |
| MSI           | X470 GAMING PRO             | [a7138e79c0](https://linux-hardware.org/?probe=a7138e79c0) | Jun 23, 2020 |
| MSI           | 760GM-P23                   | [8463ee797e](https://linux-hardware.org/?probe=8463ee797e) | Jun 21, 2020 |
| ASUSTek       | P5Q3                        | [4e73fc0ebd](https://linux-hardware.org/?probe=4e73fc0ebd) | Jun 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ae1cea8d82](https://linux-hardware.org/?probe=ae1cea8d82) | Jun 15, 2020 |
| ASUSTek       | P5Q3                        | [f2a4215c2c](https://linux-hardware.org/?probe=f2a4215c2c) | Jun 14, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [1598cd7c04](https://linux-hardware.org/?probe=1598cd7c04) | Jun 10, 2020 |
| MSI           | H270 GAMING M3              | [10c5cc23af](https://linux-hardware.org/?probe=10c5cc23af) | Jun 09, 2020 |
| MSI           | B450 GAMING PLUS            | [534ac38dd7](https://linux-hardware.org/?probe=534ac38dd7) | Jun 09, 2020 |
| ASUSTek       | Q87T                        | [8eae2b51f5](https://linux-hardware.org/?probe=8eae2b51f5) | Jun 08, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [8c865a795a](https://linux-hardware.org/?probe=8c865a795a) | Jun 05, 2020 |
| ASRock        | B150M Pro4                  | [d704cdc9e0](https://linux-hardware.org/?probe=d704cdc9e0) | Jun 04, 2020 |
| Dell          | 0CT017                      | [7a9a09ec49](https://linux-hardware.org/?probe=7a9a09ec49) | Jun 03, 2020 |
| Gigabyte      | H110N-CF                    | [3e9da1e0fc](https://linux-hardware.org/?probe=3e9da1e0fc) | Jun 02, 2020 |
| Gigabyte      | GA-890FXA-UD5               | [b9edeb9db7](https://linux-hardware.org/?probe=b9edeb9db7) | Jun 01, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [2290624850](https://linux-hardware.org/?probe=2290624850) | May 31, 2020 |
| MSI           | A88X-G45 GAMING             | [5321862a29](https://linux-hardware.org/?probe=5321862a29) | May 25, 2020 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [fe4766c68b](https://linux-hardware.org/?probe=fe4766c68b) | May 24, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [73ff075e8b](https://linux-hardware.org/?probe=73ff075e8b) | May 23, 2020 |
| Fujitsu Si... | D2610-A1 S26361-D2610-A1    | [83c143bfd7](https://linux-hardware.org/?probe=83c143bfd7) | May 23, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [04495f26dd](https://linux-hardware.org/?probe=04495f26dd) | May 23, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [104dcd648a](https://linux-hardware.org/?probe=104dcd648a) | May 23, 2020 |
| Medion        | B250H4-EM                   | [7202ccb609](https://linux-hardware.org/?probe=7202ccb609) | May 23, 2020 |
| Gigabyte      | P55A-UD4                    | [c1f8a1209b](https://linux-hardware.org/?probe=c1f8a1209b) | May 20, 2020 |
| ASUSTek       | PRIME A320I-K               | [bea9fd77be](https://linux-hardware.org/?probe=bea9fd77be) | May 19, 2020 |
| HP            | 1905                        | [e70c3c026a](https://linux-hardware.org/?probe=e70c3c026a) | May 16, 2020 |
| MSI           | Z68MA-ED55                  | [2562e1a6d7](https://linux-hardware.org/?probe=2562e1a6d7) | May 14, 2020 |
| HP            | 1495                        | [f0d3a50933](https://linux-hardware.org/?probe=f0d3a50933) | May 13, 2020 |
| Lenovo        | GA-6UASV2 E1_2              | [38e4b2547a](https://linux-hardware.org/?probe=38e4b2547a) | May 13, 2020 |
| ASUSTek       | P8H77-V LE                  | [bf8510147c](https://linux-hardware.org/?probe=bf8510147c) | May 13, 2020 |
| ASUSTek       | P6X58D-E                    | [5a566d4992](https://linux-hardware.org/?probe=5a566d4992) | May 12, 2020 |
| Gigabyte      | P55A-UD4                    | [697d506a6f](https://linux-hardware.org/?probe=697d506a6f) | May 11, 2020 |
| Gigabyte      | Z97P-D3                     | [9ee0d24e00](https://linux-hardware.org/?probe=9ee0d24e00) | May 10, 2020 |
| HP            | 1495                        | [34b3c59a20](https://linux-hardware.org/?probe=34b3c59a20) | May 09, 2020 |
| MSI           | H61MU-E35                   | [e5efecff9f](https://linux-hardware.org/?probe=e5efecff9f) | May 05, 2020 |
| ASUSTek       | PRIME A320I-K               | [1a70114ffb](https://linux-hardware.org/?probe=1a70114ffb) | May 05, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [13c69a7e65](https://linux-hardware.org/?probe=13c69a7e65) | May 05, 2020 |
| IBM           | 59Y3432 SIT                 | [056b639e0c](https://linux-hardware.org/?probe=056b639e0c) | May 04, 2020 |
| Shuttle       | FS61                        | [06e7b64da1](https://linux-hardware.org/?probe=06e7b64da1) | May 03, 2020 |
| Sapphire      | PI-AM3RS760G2               | [9ac1ac4237](https://linux-hardware.org/?probe=9ac1ac4237) | May 02, 2020 |
| Sapphire      | PI-AM3RS760G2               | [a700f16cf8](https://linux-hardware.org/?probe=a700f16cf8) | May 02, 2020 |
| Sapphire      | PI-AM3RS760G2               | [e0632f7f90](https://linux-hardware.org/?probe=e0632f7f90) | May 02, 2020 |
| HP            | 1495                        | [79ab6a37e9](https://linux-hardware.org/?probe=79ab6a37e9) | May 02, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [dd0d7252fc](https://linux-hardware.org/?probe=dd0d7252fc) | May 02, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [b4ed75c290](https://linux-hardware.org/?probe=b4ed75c290) | May 01, 2020 |
| Medion        | MS-7800                     | [b49432576f](https://linux-hardware.org/?probe=b49432576f) | Apr 30, 2020 |
| Medion        | MS-7800                     | [c6e7751601](https://linux-hardware.org/?probe=c6e7751601) | Apr 30, 2020 |
| ASUSTek       | M5A78L-M LE                 | [4c00485154](https://linux-hardware.org/?probe=4c00485154) | Apr 29, 2020 |
| ASUSTek       | P6T                         | [08f2e0c42d](https://linux-hardware.org/?probe=08f2e0c42d) | Apr 29, 2020 |
| Sapphire      | PI-AM3RS760G2               | [d5a11756e4](https://linux-hardware.org/?probe=d5a11756e4) | Apr 27, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [25299e6aa0](https://linux-hardware.org/?probe=25299e6aa0) | Apr 26, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [0040f0e90b](https://linux-hardware.org/?probe=0040f0e90b) | Apr 26, 2020 |
| MSI           | Z97 GAMING 9 ACK            | [7b9e17c081](https://linux-hardware.org/?probe=7b9e17c081) | Apr 25, 2020 |
| Acer          | RS780HVF                    | [15e8b006b4](https://linux-hardware.org/?probe=15e8b006b4) | Apr 24, 2020 |
| Acer          | RS780HVF                    | [fd298ac831](https://linux-hardware.org/?probe=fd298ac831) | Apr 22, 2020 |
| Acer          | RS780HVF                    | [1118996f35](https://linux-hardware.org/?probe=1118996f35) | Apr 22, 2020 |
| Acer          | RS780HVF                    | [c1fee6cb8b](https://linux-hardware.org/?probe=c1fee6cb8b) | Apr 21, 2020 |
| ASUSTek       | P5B                         | [436080c949](https://linux-hardware.org/?probe=436080c949) | Apr 20, 2020 |
| ASRock        | Z68 Pro3                    | [4313e511b6](https://linux-hardware.org/?probe=4313e511b6) | Apr 14, 2020 |
| ASRock        | Z68 Pro3                    | [099a117f0b](https://linux-hardware.org/?probe=099a117f0b) | Apr 14, 2020 |
| ASUSTek       | F2A85-V PRO                 | [28f4f3baf5](https://linux-hardware.org/?probe=28f4f3baf5) | Apr 10, 2020 |
| ASRock        | N68-GE3 UCC                 | [212d62f70b](https://linux-hardware.org/?probe=212d62f70b) | Apr 10, 2020 |
| Lenovo        | SHARKBAY NOK                | [ca34648c4b](https://linux-hardware.org/?probe=ca34648c4b) | Apr 08, 2020 |
| ASUSTek       | F2A85-V PRO                 | [256ee14889](https://linux-hardware.org/?probe=256ee14889) | Apr 07, 2020 |
| ASUSTek       | F2A85-V PRO                 | [39d4b7909a](https://linux-hardware.org/?probe=39d4b7909a) | Apr 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [993050d9df](https://linux-hardware.org/?probe=993050d9df) | Apr 04, 2020 |
| Medion        | MS-7800                     | [f3afd63ba2](https://linux-hardware.org/?probe=f3afd63ba2) | Apr 01, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [0120aa60f5](https://linux-hardware.org/?probe=0120aa60f5) | Mar 29, 2020 |
| Gigabyte      | Z370M D3H-CF                | [176480702c](https://linux-hardware.org/?probe=176480702c) | Mar 14, 2020 |
| Foxconn       | AT-5000 Series PCB/1.1      | [7dc424d59f](https://linux-hardware.org/?probe=7dc424d59f) | Mar 06, 2020 |
| Foxconn       | AT-5000 Series PCB/1.1      | [94c91254ef](https://linux-hardware.org/?probe=94c91254ef) | Mar 06, 2020 |
| ASRock        | Z87 Killer                  | [983418b600](https://linux-hardware.org/?probe=983418b600) | Mar 06, 2020 |
| MSI           | B450 TOMAHAWK               | [8088ded621](https://linux-hardware.org/?probe=8088ded621) | Feb 21, 2020 |
| ASUSTek       | X99-A                       | [2d2ef6c415](https://linux-hardware.org/?probe=2d2ef6c415) | Feb 20, 2020 |
| MSI           | B450 TOMAHAWK               | [ce8f69c02b](https://linux-hardware.org/?probe=ce8f69c02b) | Feb 20, 2020 |
| ASRock        | Z87 Killer                  | [6ce107652f](https://linux-hardware.org/?probe=6ce107652f) | Feb 10, 2020 |
| Medion        | MS-7728                     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASRock        | FM2A88X Extreme4+           | [f3c713b688](https://linux-hardware.org/?probe=f3c713b688) | Feb 04, 2020 |
| ASUSTek       | Rampage IV EXTREME          | [c2bebe9cae](https://linux-hardware.org/?probe=c2bebe9cae) | Feb 03, 2020 |
| Pegatron      | Benicia                     | [077bb98064](https://linux-hardware.org/?probe=077bb98064) | Feb 03, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2fdfff2aeb](https://linux-hardware.org/?probe=2fdfff2aeb) | Feb 02, 2020 |
| ASRock        | H97 Pro4                    | [9692f4331b](https://linux-hardware.org/?probe=9692f4331b) | Jan 30, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e2420dad2](https://linux-hardware.org/?probe=9e2420dad2) | Jan 30, 2020 |
| ASRock        | H97 Pro4                    | [8e0ed4d700](https://linux-hardware.org/?probe=8e0ed4d700) | Jan 30, 2020 |
| Pegatron      | Benicia                     | [7ad790ff7a](https://linux-hardware.org/?probe=7ad790ff7a) | Jan 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [146d3c4f96](https://linux-hardware.org/?probe=146d3c4f96) | Jan 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [5642861837](https://linux-hardware.org/?probe=5642861837) | Jan 24, 2020 |
| Lenovo        | MAHOBAY No DPK              | [d72cbdf691](https://linux-hardware.org/?probe=d72cbdf691) | Jan 20, 2020 |
| Biostar       | A10N-8800E                  | [1b678941da](https://linux-hardware.org/?probe=1b678941da) | Jan 19, 2020 |
| ASUSTek       | H87M-PRO                    | [001ad7f036](https://linux-hardware.org/?probe=001ad7f036) | Jan 19, 2020 |
| ASUSTek       | M3N78-EM                    | [e7441046c0](https://linux-hardware.org/?probe=e7441046c0) | Jan 15, 2020 |
| ASUSTek       | M4A78T-E                    | [259abe496b](https://linux-hardware.org/?probe=259abe496b) | Jan 10, 2020 |
| HP            | 0AA8h                       | [6bfa4ca4a7](https://linux-hardware.org/?probe=6bfa4ca4a7) | Jan 01, 2020 |
| ASUSTek       | H81M-PLUS                   | [08a52838c1](https://linux-hardware.org/?probe=08a52838c1) | Dec 29, 2019 |
| Medion        | MS-7728                     | [a86ef1e6d5](https://linux-hardware.org/?probe=a86ef1e6d5) | Dec 26, 2019 |
| Gigabyte      | B250-FinTech-CF             | [74a6661df4](https://linux-hardware.org/?probe=74a6661df4) | Dec 09, 2019 |
| MSI           | X470 GAMING PRO             | [3c409e3fac](https://linux-hardware.org/?probe=3c409e3fac) | Nov 17, 2019 |
| ASUSTek       | P8H67                       | [6592929d60](https://linux-hardware.org/?probe=6592929d60) | Nov 13, 2019 |
| MSI           | X370 KRAIT GAMING           | [2030142a09](https://linux-hardware.org/?probe=2030142a09) | Nov 08, 2019 |
| MSI           | X370 KRAIT GAMING           | [2fc6906f36](https://linux-hardware.org/?probe=2fc6906f36) | Nov 08, 2019 |
| Dell          | 0DN075                      | [588c79360b](https://linux-hardware.org/?probe=588c79360b) | Oct 31, 2019 |
| ASUSTek       | V-P7H55E                    | [f973a6c8a9](https://linux-hardware.org/?probe=f973a6c8a9) | Oct 28, 2019 |
| Packard Be... | IMEDIA S1300                | [0fda47e3b7](https://linux-hardware.org/?probe=0fda47e3b7) | Oct 23, 2019 |
| ASRock        | Z87 Killer                  | [8ae3df832b](https://linux-hardware.org/?probe=8ae3df832b) | Oct 17, 2019 |
| ASRock        | Z87 Killer                  | [41c93cac66](https://linux-hardware.org/?probe=41c93cac66) | Oct 08, 2019 |
| MSI           | X470 GAMING PRO             | [7904813ed9](https://linux-hardware.org/?probe=7904813ed9) | Oct 06, 2019 |
| ASRock        | Z87 Killer                  | [ff79176dae](https://linux-hardware.org/?probe=ff79176dae) | Oct 04, 2019 |
| MSI           | X470 GAMING PRO             | [21c0db91eb](https://linux-hardware.org/?probe=21c0db91eb) | Oct 02, 2019 |
| ASRock        | Z87 Killer                  | [46b0add918](https://linux-hardware.org/?probe=46b0add918) | Sep 30, 2019 |
| ASUSTek       | P8H67                       | [8e59924d0d](https://linux-hardware.org/?probe=8e59924d0d) | Sep 30, 2019 |
| ASUSTek       | P6T SE                      | [f829c40cce](https://linux-hardware.org/?probe=f829c40cce) | Sep 28, 2019 |
| ASUSTek       | P6T SE                      | [8dcf40d84d](https://linux-hardware.org/?probe=8dcf40d84d) | Sep 28, 2019 |
| Acer          | Veriton M2631 V:1.0         | [6542efae35](https://linux-hardware.org/?probe=6542efae35) | Sep 23, 2019 |
| MSI           | X99S MPOWER                 | [fd30de16b0](https://linux-hardware.org/?probe=fd30de16b0) | Sep 22, 2019 |
| Lenovo        | ThinkCentre M58p 6137E61    | [ed59e38f8c](https://linux-hardware.org/?probe=ed59e38f8c) | Sep 06, 2019 |
| Lenovo        | ThinkCentre M58p 6137E61    | [52fa080e49](https://linux-hardware.org/?probe=52fa080e49) | Sep 06, 2019 |
| Unknown       | 1.2                         | [e6ac162ade](https://linux-hardware.org/?probe=e6ac162ade) | Aug 27, 2019 |
| ASUSTek       | P8H61-M LE/USB3             | [d73f3f8528](https://linux-hardware.org/?probe=d73f3f8528) | Aug 22, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [85ef01ba25](https://linux-hardware.org/?probe=85ef01ba25) | Aug 15, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [cfc5e59508](https://linux-hardware.org/?probe=cfc5e59508) | Aug 15, 2019 |
| MSI           | X470 GAMING PRO             | [9d586233cb](https://linux-hardware.org/?probe=9d586233cb) | Aug 13, 2019 |
| ASUSTek       | H61M-A/USB3                 | [f2e8562a52](https://linux-hardware.org/?probe=f2e8562a52) | Aug 10, 2019 |
| MSI           | A75MA-P35                   | [6a11324b77](https://linux-hardware.org/?probe=6a11324b77) | Aug 04, 2019 |
| MSI           | X370 XPOWER GAMING TITAN... | [d084d64bdf](https://linux-hardware.org/?probe=d084d64bdf) | Jul 27, 2019 |
| Medion        | MS-7646                     | [0be5f7a9e8](https://linux-hardware.org/?probe=0be5f7a9e8) | Jul 26, 2019 |
| Gigabyte      | Z270P-D3-CF                 | [9a41c725f3](https://linux-hardware.org/?probe=9a41c725f3) | Jul 23, 2019 |
| HP            | 1495                        | [2d53282148](https://linux-hardware.org/?probe=2d53282148) | Jul 18, 2019 |
| HP            | 1495                        | [f63a4cd715](https://linux-hardware.org/?probe=f63a4cd715) | Jul 18, 2019 |
| ASUSTek       | P8H67                       | [7a74eb0f6f](https://linux-hardware.org/?probe=7a74eb0f6f) | Jul 16, 2019 |
| ASUSTek       | P8H67                       | [640c9f1ab7](https://linux-hardware.org/?probe=640c9f1ab7) | Jul 16, 2019 |
| ASUSTek       | P8H67                       | [9a951d161f](https://linux-hardware.org/?probe=9a951d161f) | Jul 16, 2019 |
| Medion        | H81H3-EM2                   | [98746816d9](https://linux-hardware.org/?probe=98746816d9) | Jul 04, 2019 |
| Medion        | H81H3-EM2                   | [a87ceb42ad](https://linux-hardware.org/?probe=a87ceb42ad) | Jul 04, 2019 |
| Pegatron      | Benicia                     | [719994a01b](https://linux-hardware.org/?probe=719994a01b) | Jul 01, 2019 |
| Shuttle       | XS36V                       | [cd64391dda](https://linux-hardware.org/?probe=cd64391dda) | Jun 19, 2019 |
| Acer          | Aspire TC-710 V:1.1         | [98a8d47fc0](https://linux-hardware.org/?probe=98a8d47fc0) | Jun 12, 2019 |
| ASUSTek       | A68HM-K                     | [1a2a8102fb](https://linux-hardware.org/?probe=1a2a8102fb) | Jun 02, 2019 |
| ASUSTek       | H81M-PLUS                   | [d2de9e43a6](https://linux-hardware.org/?probe=d2de9e43a6) | May 13, 2019 |
| ASUSTek       | Rampage III Extreme         | [204eddf27d](https://linux-hardware.org/?probe=204eddf27d) | May 10, 2019 |
| ASUSTek       | M5A78L-M LX3                | [0987b1062f](https://linux-hardware.org/?probe=0987b1062f) | May 09, 2019 |
| Acer          | RS880M05                    | [3cc746c01b](https://linux-hardware.org/?probe=3cc746c01b) | May 04, 2019 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [80427eb045](https://linux-hardware.org/?probe=80427eb045) | May 04, 2019 |
| ASUSTek       | P9X79                       | [e47e6eba5d](https://linux-hardware.org/?probe=e47e6eba5d) | May 02, 2019 |
| ASUSTek       | H81M-PLUS                   | [289f136d3f](https://linux-hardware.org/?probe=289f136d3f) | Apr 29, 2019 |
| ASRock        | 970 Pro3 R2.0               | [89e1c14d18](https://linux-hardware.org/?probe=89e1c14d18) | Apr 28, 2019 |
| HP            | 500-287eg                   | [92eae585a5](https://linux-hardware.org/?probe=92eae585a5) | Apr 21, 2019 |
| Lenovo        | 31900058 STD                | [1b6751d51a](https://linux-hardware.org/?probe=1b6751d51a) | Apr 16, 2019 |
| TYAN Compu... | S5120                       | [7ce7f79d09](https://linux-hardware.org/?probe=7ce7f79d09) | Apr 03, 2019 |
| Gigabyte      | Z87N-WIFI                   | [c689ce31bb](https://linux-hardware.org/?probe=c689ce31bb) | Mar 25, 2019 |
| Biostar       | GF8100 M2+ TE               | [0e4bbf6c92](https://linux-hardware.org/?probe=0e4bbf6c92) | Mar 13, 2019 |
| ASUSTek       | M4A77TD                     | [a3a5486ddc](https://linux-hardware.org/?probe=a3a5486ddc) | Mar 13, 2019 |
| Gigabyte      | Z77X-UP5 TH-CF              | [190e0fcd2a](https://linux-hardware.org/?probe=190e0fcd2a) | Mar 11, 2019 |
| HP            | 8433 11                     | [2bcad0a319](https://linux-hardware.org/?probe=2bcad0a319) | Mar 07, 2019 |
| MSI           | X470 GAMING PRO             | [040f7ac7c4](https://linux-hardware.org/?probe=040f7ac7c4) | Feb 27, 2019 |
| Acer          | Aspire XC-830               | [683ab95a31](https://linux-hardware.org/?probe=683ab95a31) | Feb 18, 2019 |
| Gigabyte      | MZBSWBP-00                  | [22bf9556b0](https://linux-hardware.org/?probe=22bf9556b0) | Feb 03, 2019 |
| Intel         | DB75EN AAG39650-302         | [1aac6deb59](https://linux-hardware.org/?probe=1aac6deb59) | Jan 31, 2019 |
| AMI           | Cherry Trail CR             | [0ad2e06845](https://linux-hardware.org/?probe=0ad2e06845) | Jan 30, 2019 |
| ASUSTek       | Z10PE-D16 WS                | [9ee9f662a8](https://linux-hardware.org/?probe=9ee9f662a8) | Jan 19, 2019 |
| ASUSTek       | Z10PE-D16 WS                | [8683e5f64d](https://linux-hardware.org/?probe=8683e5f64d) | Jan 19, 2019 |
| MSI           | 880GM-E41                   | [4b8fd34544](https://linux-hardware.org/?probe=4b8fd34544) | Jan 12, 2019 |
| ASUSTek       | X99-A                       | [5cf9372da9](https://linux-hardware.org/?probe=5cf9372da9) | Dec 29, 2018 |
| Gigabyte      | X58A-UD3R                   | [06a381a625](https://linux-hardware.org/?probe=06a381a625) | Dec 28, 2018 |
| Gigabyte      | X58A-UD3R                   | [3c1b7efac9](https://linux-hardware.org/?probe=3c1b7efac9) | Dec 28, 2018 |
| ASUSTek       | P8Z68-V PRO                 | [41f8c8c4bb](https://linux-hardware.org/?probe=41f8c8c4bb) | Dec 23, 2018 |
| MSI           | A320M PRO-M2                | [4408553bfe](https://linux-hardware.org/?probe=4408553bfe) | Dec 22, 2018 |
| MSI           | A320M PRO-M2                | [0adc826264](https://linux-hardware.org/?probe=0adc826264) | Dec 22, 2018 |
| ASRock        | H87 Pro4                    | [484cf4a1a4](https://linux-hardware.org/?probe=484cf4a1a4) | Dec 14, 2018 |
| Lenovo        | ThinkCentre M81 5048W4M     | [cc79e0559c](https://linux-hardware.org/?probe=cc79e0559c) | Dec 11, 2018 |
| Lenovo        | ThinkCentre M81 5048W4M     | [49b676468f](https://linux-hardware.org/?probe=49b676468f) | Dec 11, 2018 |
| Biostar       | A78MD                       | [ccfbf83ff8](https://linux-hardware.org/?probe=ccfbf83ff8) | Nov 25, 2018 |
| Biostar       | A78MD                       | [80cbd4570d](https://linux-hardware.org/?probe=80cbd4570d) | Nov 25, 2018 |
| HP            | 81C5 MVB                    | [e39b189386](https://linux-hardware.org/?probe=e39b189386) | Nov 24, 2018 |
| Foxconn       | G31MX Series                | [a0a7c180c5](https://linux-hardware.org/?probe=a0a7c180c5) | Nov 21, 2018 |
| MSI           | MS-7502 Fab D               | [11f6c0d362](https://linux-hardware.org/?probe=11f6c0d362) | Nov 16, 2018 |
| MSI           | MS-7502 Fab D               | [8fa6a7b89f](https://linux-hardware.org/?probe=8fa6a7b89f) | Nov 11, 2018 |
| ASRock        | H97 Anniversary             | [8fd474da8b](https://linux-hardware.org/?probe=8fd474da8b) | Nov 04, 2018 |
| ASRock        | E350M1                      | [51fb6fa87d](https://linux-hardware.org/?probe=51fb6fa87d) | Nov 01, 2018 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2fe6ddfbdf](https://linux-hardware.org/?probe=2fe6ddfbdf) | Oct 18, 2018 |
| HP            | 0A54h                       | [a30fb7b788](https://linux-hardware.org/?probe=a30fb7b788) | Oct 14, 2018 |
| ASUSTek       | PRIME Z270-A                | [b0872a1be5](https://linux-hardware.org/?probe=b0872a1be5) | Sep 17, 2018 |
| ASRock        | Z270 Gaming K6              | [a64b2acb05](https://linux-hardware.org/?probe=a64b2acb05) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [b8488b8bd7](https://linux-hardware.org/?probe=b8488b8bd7) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [cc813a1c15](https://linux-hardware.org/?probe=cc813a1c15) | Sep 07, 2018 |
| ASUSTek       | H110M-K                     | [2c499101d4](https://linux-hardware.org/?probe=2c499101d4) | Sep 06, 2018 |
| MSI           | X470 GAMING PRO             | [4d480c550e](https://linux-hardware.org/?probe=4d480c550e) | Sep 02, 2018 |
| MSI           | X470 GAMING PRO             | [75193022d0](https://linux-hardware.org/?probe=75193022d0) | Jul 31, 2018 |
| Intel         | Thurley                     | [e37057e69e](https://linux-hardware.org/?probe=e37057e69e) | Jun 12, 2018 |
| ASRock        | 970M Pro3                   | [c956817504](https://linux-hardware.org/?probe=c956817504) | Dec 22, 2017 |
| ASRock        | Z68 Professional Gen3       | [3e2eeae3e8](https://linux-hardware.org/?probe=3e2eeae3e8) | Jun 02, 2017 |
| ASUSTek       | F1A75-M-PRO R2.0            | [8ae18559e3](https://linux-hardware.org/?probe=8ae18559e3) | May 16, 2017 |
| MSI           | A78M-E35                    | [de8317d2c2](https://linux-hardware.org/?probe=de8317d2c2) | Apr 21, 2017 |
| Gigabyte      | F2A88XM-DS2                 | [1e5325c9d7](https://linux-hardware.org/?probe=1e5325c9d7) | Apr 09, 2017 |
| ASUSTek       | X99-A II                    | [fcf4afe5c6](https://linux-hardware.org/?probe=fcf4afe5c6) | Jan 21, 2017 |
| ECS           | A780GM-A                    | [6a2afa0d77](https://linux-hardware.org/?probe=6a2afa0d77) | Jan 03, 2017 |
| ASUSTek       | Maximus VIII EXTREME        | [f3e8817609](https://linux-hardware.org/?probe=f3e8817609) | Jul 22, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 92       | 14.38%  |
| Ubuntu 18.04                 | 59       | 9.22%   |
| OpenMandriva 4.3             | 26       | 4.06%   |
| Ubuntu 22.04                 | 24       | 3.75%   |
| OpenMandriva 4.2             | 22       | 3.44%   |
| Arch Rolling                 | 21       | 3.28%   |
| Arch                         | 21       | 3.28%   |
| Debian 11                    | 17       | 2.66%   |
| Manjaro                      | 12       | 1.88%   |
| Ubuntu 20.10                 | 11       | 1.72%   |
| Pop!_OS 20.10                | 11       | 1.72%   |
| Linux Mint 19.3              | 11       | 1.72%   |
| Ubuntu 21.04                 | 10       | 1.56%   |
| ROSA R11                     | 9        | 1.41%   |
| Linux Mint 20.1              | 9        | 1.41%   |
| Xubuntu 20.04                | 8        | 1.25%   |
| Linux Mint 20.2              | 8        | 1.25%   |
| Linux Mint 20                | 8        | 1.25%   |
| Fedora 35                    | 8        | 1.25%   |
| Debian 10                    | 8        | 1.25%   |
| ROSA R10                     | 7        | 1.09%   |
| Pop!_OS 22.04                | 7        | 1.09%   |
| Fedora 33                    | 7        | 1.09%   |
| Fedora 32                    | 7        | 1.09%   |
| ArcoLinux Rolling            | 7        | 1.09%   |
| Ubuntu 18.10                 | 6        | 0.94%   |
| OpenMandriva 4.50            | 6        | 0.94%   |
| Linux Mint 20.3              | 6        | 0.94%   |
| EndeavourOS Rolling          | 6        | 0.94%   |
| Pop!_OS 20.04                | 5        | 0.78%   |
| KDE neon 20.04               | 5        | 0.78%   |
| Ubuntu 21.10                 | 4        | 0.63%   |
| Ubuntu 19.04                 | 4        | 0.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 0.63%   |
| OpenMandriva 4.90            | 4        | 0.63%   |
| Manjaro 22.0.0               | 4        | 0.63%   |
| Linux Mint 21                | 4        | 0.63%   |
| Linux Mint 19.1              | 4        | 0.63%   |
| Kubuntu 20.04                | 4        | 0.63%   |
| Fedora 37                    | 4        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 211      | 34.36%  |
| OpenMandriva  | 59       | 9.61%   |
| Linux Mint    | 55       | 8.96%   |
| Arch          | 41       | 6.68%   |
| Manjaro       | 32       | 5.21%   |
| Debian        | 32       | 5.21%   |
| Fedora        | 30       | 4.89%   |
| Pop!_OS       | 24       | 3.91%   |
| ROSA          | 23       | 3.75%   |
| Kubuntu       | 14       | 2.28%   |
| Xubuntu       | 10       | 1.63%   |
| ArcoLinux     | 8        | 1.3%    |
| Zorin         | 6        | 0.98%   |
| Ubuntu MATE   | 6        | 0.98%   |
| openSUSE      | 6        | 0.98%   |
| KDE neon      | 6        | 0.98%   |
| EndeavourOS   | 6        | 0.98%   |
| Gentoo        | 5        | 0.81%   |
| Elementary    | 5        | 0.81%   |
| BlackPanther  | 4        | 0.65%   |
| Ubuntu Unity  | 3        | 0.49%   |
| Ubuntu Studio | 3        | 0.49%   |
| LMDE          | 3        | 0.49%   |
| Clear Linux   | 3        | 0.49%   |
| Parrot        | 2        | 0.33%   |
| NixOS         | 2        | 0.33%   |
| Endless       | 2        | 0.33%   |
| Xero          | 1        | 0.16%   |
| UbuntuDDE     | 1        | 0.16%   |
| TUXEDO OS     | 1        | 0.16%   |
| SteamOS       | 1        | 0.16%   |
| Siduction     | 1        | 0.16%   |
| RHEL          | 1        | 0.16%   |
| Reborn OS     | 1        | 0.16%   |
| Nobara        | 1        | 0.16%   |
| MX            | 1        | 0.16%   |
| Lubuntu       | 1        | 0.16%   |
| Deepin        | 1        | 0.16%   |
| Artix         | 1        | 0.16%   |
| Alpine        | 1        | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 26       | 3.63%   |
| 5.10.14-desktop-1omv4002        | 21       | 2.93%   |
| 5.4.0-42-generic                | 11       | 1.53%   |
| 5.4.0-58-generic                | 8        | 1.12%   |
| 5.4.0-52-generic                | 7        | 0.98%   |
| 5.4.0-28-generic                | 7        | 0.98%   |
| 5.8.0-7630-generic              | 6        | 0.84%   |
| 5.4.0-33-generic                | 6        | 0.84%   |
| 5.15.0-52-generic               | 6        | 0.84%   |
| 5.13.0-39-generic               | 6        | 0.84%   |
| 4.15.0-desktop-60.7rosa-x86_64  | 6        | 0.84%   |
| 5.4.0-80-generic                | 5        | 0.7%    |
| 5.4.0-72-generic                | 5        | 0.7%    |
| 5.4.0-48-generic                | 5        | 0.7%    |
| 5.15.0-47-generic               | 5        | 0.7%    |
| 5.12.4-desktop-1omv4050         | 5        | 0.7%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 0.7%    |
| 4.18.0-15-generic               | 5        | 0.7%    |
| 5.8.0-44-generic                | 4        | 0.56%   |
| 5.8.0-41-generic                | 4        | 0.56%   |
| 5.4.0-89-generic                | 4        | 0.56%   |
| 5.4.0-74-generic                | 4        | 0.56%   |
| 5.4.0-71-generic                | 4        | 0.56%   |
| 5.4.0-67-generic                | 4        | 0.56%   |
| 5.4.0-65-generic                | 4        | 0.56%   |
| 5.4.0-40-generic                | 4        | 0.56%   |
| 5.3.0-46-generic                | 4        | 0.56%   |
| 5.15.0-41-generic               | 4        | 0.56%   |
| 5.15.0-25-generic               | 4        | 0.56%   |
| 5.13.0-30-generic               | 4        | 0.56%   |
| 5.13.0-27-generic               | 4        | 0.56%   |
| 5.11.0-22-generic               | 4        | 0.56%   |
| 5.10.0-9-amd64                  | 4        | 0.56%   |
| 5.10.0-19-amd64                 | 4        | 0.56%   |
| 4.18.16-desktop-1bP             | 4        | 0.56%   |
| 4.15.0-66-generic               | 4        | 0.56%   |
| 4.15.0-54-generic               | 4        | 0.56%   |
| 5.8.0-7642-generic              | 3        | 0.42%   |
| 5.8.0-43-generic                | 3        | 0.42%   |
| 5.8.0-36-generic                | 3        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 120      | 17.88%  |
| 4.15.0  | 51       | 7.6%    |
| 5.15.0  | 38       | 5.66%   |
| 5.8.0   | 36       | 5.37%   |
| 5.11.0  | 32       | 4.77%   |
| 5.13.0  | 30       | 4.47%   |
| 5.16.7  | 27       | 4.02%   |
| 5.10.14 | 22       | 3.28%   |
| 5.10.0  | 18       | 2.68%   |
| 4.18.0  | 17       | 2.53%   |
| 5.3.0   | 15       | 2.24%   |
| 5.0.0   | 10       | 1.49%   |
| 4.19.0  | 8        | 1.19%   |
| 5.12.4  | 6        | 0.89%   |
| 4.9.60  | 5        | 0.75%   |
| 5.9.16  | 4        | 0.6%    |
| 5.9.11  | 4        | 0.6%    |
| 5.19.0  | 4        | 0.6%    |
| 5.18.12 | 4        | 0.6%    |
| 5.17.5  | 4        | 0.6%    |
| 5.16.0  | 4        | 0.6%    |
| 4.4.0   | 4        | 0.6%    |
| 4.18.16 | 4        | 0.6%    |
| 5.8.13  | 3        | 0.45%   |
| 5.19.2  | 3        | 0.45%   |
| 5.18.10 | 3        | 0.45%   |
| 5.15.6  | 3        | 0.45%   |
| 6.0.8   | 2        | 0.3%    |
| 6.0.7   | 2        | 0.3%    |
| 6.0.6   | 2        | 0.3%    |
| 6.0.10  | 2        | 0.3%    |
| 5.9.14  | 2        | 0.3%    |
| 5.9.0   | 2        | 0.3%    |
| 5.8.9   | 2        | 0.3%    |
| 5.8.6   | 2        | 0.3%    |
| 5.8.4   | 2        | 0.3%    |
| 5.8.14  | 2        | 0.3%    |
| 5.6.7   | 2        | 0.3%    |
| 5.5.0   | 2        | 0.3%    |
| 5.4.43  | 2        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 139      | 21.09%  |
| 5.15    | 62       | 9.41%   |
| 5.10    | 55       | 8.35%   |
| 5.8     | 51       | 7.74%   |
| 4.15    | 51       | 7.74%   |
| 5.11    | 42       | 6.37%   |
| 5.16    | 37       | 5.61%   |
| 5.13    | 36       | 5.46%   |
| 4.18    | 23       | 3.49%   |
| 5.3     | 18       | 2.73%   |
| 5.12    | 17       | 2.58%   |
| 5.9     | 15       | 2.28%   |
| 5.19    | 13       | 1.97%   |
| 6.0     | 12       | 1.82%   |
| 5.18    | 12       | 1.82%   |
| 5.17    | 12       | 1.82%   |
| 5.0     | 10       | 1.52%   |
| 4.9     | 10       | 1.52%   |
| 4.19    | 10       | 1.52%   |
| 5.6     | 6        | 0.91%   |
| 5.14    | 6        | 0.91%   |
| 5.7     | 4        | 0.61%   |
| 5.5     | 4        | 0.61%   |
| 4.4     | 4        | 0.61%   |
| 4.1     | 4        | 0.61%   |
| 4.10    | 2        | 0.3%    |
| 6.1     | 1        | 0.15%   |
| 4.6     | 1        | 0.15%   |
| 4.12    | 1        | 0.15%   |
| 3.10    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 594      | 99%     |
| i686   | 6        | 1%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 233      | 37.34%  |
| KDE5          | 120      | 19.23%  |
| Unknown       | 98       | 15.71%  |
| XFCE          | 47       | 7.53%   |
| X-Cinnamon    | 45       | 7.21%   |
| MATE          | 17       | 2.72%   |
| KDE           | 17       | 2.72%   |
| KDE4          | 13       | 2.08%   |
| Cinnamon      | 6        | 0.96%   |
| Pantheon      | 5        | 0.8%    |
| LXQt          | 4        | 0.64%   |
| Unity         | 3        | 0.48%   |
| i3            | 3        | 0.48%   |
| Budgie        | 3        | 0.48%   |
| xmonad        | 2        | 0.32%   |
| Deepin        | 2        | 0.32%   |
| awesome       | 2        | 0.32%   |
| sway          | 1        | 0.16%   |
| LXDE          | 1        | 0.16%   |
| leftwm        | 1        | 0.16%   |
| GNOME Classic | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 485      | 78.48%  |
| Unknown | 56       | 9.06%   |
| Wayland | 54       | 8.74%   |
| Tty     | 23       | 3.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 304      | 48.95%  |
| SDDM    | 116      | 18.68%  |
| LightDM | 55       | 8.86%   |
| GDM3    | 54       | 8.7%    |
| GDM     | 53       | 8.53%   |
| TDM     | 21       | 3.38%   |
| KDM     | 14       | 2.25%   |
| SLiM    | 2        | 0.32%   |
| XDM     | 1        | 0.16%   |
| LXDM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| de_AT      | 240      | 39.02%  |
| en_US      | 152      | 24.72%  |
| Unknown    | 94       | 15.28%  |
| de_DE      | 82       | 13.33%  |
| en_GB      | 18       | 2.93%   |
| C          | 9        | 1.46%   |
| en_IE      | 6        | 0.98%   |
| pl_PL      | 3        | 0.49%   |
| ru_RU      | 2        | 0.33%   |
| it_IT      | 2        | 0.33%   |
| tr_TR      | 1        | 0.16%   |
| hu_HU      | 1        | 0.16%   |
| fa_IR      | 1        | 0.16%   |
| en_US.UTF8 | 1        | 0.16%   |
| en_AT      | 1        | 0.16%   |
| de_AT.UTF8 | 1        | 0.16%   |
| da_DK      | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 337      | 54.98%  |
| EFI  | 276      | 45.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 452      | 74.1%   |
| Overlay | 67       | 10.98%  |
| Btrfs   | 50       | 8.2%    |
| Unknown | 26       | 4.26%   |
| Zfs     | 5        | 0.82%   |
| Xfs     | 5        | 0.82%   |
| Ext2    | 3        | 0.49%   |
| Tmpfs   | 1        | 0.16%   |
| F2fs    | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 326      | 53.36%  |
| GPT     | 223      | 36.5%   |
| MBR     | 62       | 10.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 470      | 76.42%  |
| Yes       | 145      | 23.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 375      | 61.07%  |
| Yes       | 239      | 38.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUSTek Computer          | 189      | 31.5%   |
| MSI                       | 96       | 16%     |
| Gigabyte Technology       | 76       | 12.67%  |
| ASRock                    | 71       | 11.83%  |
| Hewlett-Packard           | 40       | 6.67%   |
| Lenovo                    | 26       | 4.33%   |
| Medion                    | 18       | 3%      |
| Dell                      | 17       | 2.83%   |
| Acer                      | 16       | 2.67%   |
| Intel                     | 7        | 1.17%   |
| Fujitsu                   | 7        | 1.17%   |
| Biostar                   | 7        | 1.17%   |
| Unknown                   | 7        | 1.17%   |
| Foxconn                   | 4        | 0.67%   |
| Shuttle                   | 3        | 0.5%    |
| Sapphire                  | 2        | 0.33%   |
| Pegatron                  | 2        | 0.33%   |
| Fujitsu Siemens           | 2        | 0.33%   |
| ECS                       | 2        | 0.33%   |
| TYAN Computer             | 1        | 0.17%   |
| Packard Bell              | 1        | 0.17%   |
| Matrox Electronic Systems | 1        | 0.17%   |
| IBM                       | 1        | 0.17%   |
| BESSTAR Tech              | 1        | 0.17%   |
| AZW                       | 1        | 0.17%   |
| ASRockRack                | 1        | 0.17%   |
| AMI                       | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 25       | 4.17%   |
| MSI MS-7C37                          | 10       | 1.67%   |
| MSI MS-7B79                          | 7        | 1.17%   |
| Unknown                              | 7        | 1.17%   |
| ASRock Z87 Killer                    | 6        | 1%      |
| MSI MS-7B86                          | 5        | 0.83%   |
| ASUS ROG STRIX B450-F GAMING         | 5        | 0.83%   |
| MSI MS-7C91                          | 4        | 0.67%   |
| ASUS ROG STRIX B550-I GAMING         | 4        | 0.67%   |
| ASUS ROG STRIX B550-F GAMING         | 4        | 0.67%   |
| ASUS PRIME B450-PLUS                 | 4        | 0.67%   |
| MSI MS-7971                          | 3        | 0.5%    |
| MSI MS-7817                          | 3        | 0.5%    |
| MSI MS-7721                          | 3        | 0.5%    |
| Medion MS-7800                       | 3        | 0.5%    |
| Medion MS-7707                       | 3        | 0.5%    |
| HP Z800 Workstation                  | 3        | 0.5%    |
| HP EliteDesk 800 G1 SFF              | 3        | 0.5%    |
| HP Compaq 8100 Elite CMT PC          | 3        | 0.5%    |
| Biostar A10N-8800E                   | 3        | 0.5%    |
| ASUS TUF Gaming X570-PLUS            | 3        | 0.5%    |
| ASUS TUF Gaming B550-PLUS            | 3        | 0.5%    |
| ASUS SABERTOOTH 990FX R2.0           | 3        | 0.5%    |
| ASUS PRIME A320M-K                   | 3        | 0.5%    |
| ASUS P8H77-M PRO                     | 3        | 0.5%    |
| ASRock 970 Pro3 R2.0                 | 3        | 0.5%    |
| Pegatron FZ116AA-ACP a6551.at        | 2        | 0.33%   |
| MSI MS-7C35                          | 2        | 0.33%   |
| MSI MS-7C02                          | 2        | 0.33%   |
| MSI MS-7B89                          | 2        | 0.33%   |
| MSI MS-7B85                          | 2        | 0.33%   |
| MSI MS-7A38                          | 2        | 0.33%   |
| MSI MS-7821                          | 2        | 0.33%   |
| MSI MS-7693                          | 2        | 0.33%   |
| MSI MS-7676                          | 2        | 0.33%   |
| MSI MS-7502                          | 2        | 0.33%   |
| Medion MS-7728                       | 2        | 0.33%   |
| Lenovo ThinkCentre M93p 10A8S0CE11   | 2        | 0.33%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 2        | 0.33%   |
| HP Compaq Elite 8300 SFF             | 2        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 29       | 4.83%   |
| ASUS ROG            | 25       | 4.17%   |
| ASUS All            | 25       | 4.17%   |
| Lenovo ThinkCentre  | 16       | 2.67%   |
| HP Compaq           | 14       | 2.33%   |
| Dell OptiPlex       | 12       | 2%      |
| ASUS TUF            | 12       | 2%      |
| MSI MS-7C37         | 10       | 1.67%   |
| MSI MS-7B79         | 7        | 1.17%   |
| Gigabyte X570       | 7        | 1.17%   |
| ASUS SABERTOOTH     | 7        | 1.17%   |
| ASRock Z87          | 7        | 1.17%   |
| Acer Aspire         | 7        | 1.17%   |
| Unknown             | 7        | 1.17%   |
| MSI MS-7B86         | 5        | 0.83%   |
| HP EliteDesk        | 5        | 0.83%   |
| Gigabyte Z390       | 5        | 0.83%   |
| ASUS M5A78L-M       | 5        | 0.83%   |
| ASRock 970          | 5        | 0.83%   |
| MSI MS-7C91         | 4        | 0.67%   |
| Lenovo ThinkStation | 4        | 0.67%   |
| HP Pavilion         | 4        | 0.67%   |
| Gigabyte Z590       | 4        | 0.67%   |
| Gigabyte B550       | 4        | 0.67%   |
| ASUS Rampage        | 4        | 0.67%   |
| ASUS Maximus        | 4        | 0.67%   |
| ASRock Z170         | 4        | 0.67%   |
| Acer Veriton        | 4        | 0.67%   |
| MSI MS-7971         | 3        | 0.5%    |
| MSI MS-7817         | 3        | 0.5%    |
| MSI MS-7721         | 3        | 0.5%    |
| Medion MS-7800      | 3        | 0.5%    |
| Medion MS-7707      | 3        | 0.5%    |
| Lenovo IdeaCentre   | 3        | 0.5%    |
| HP Z800             | 3        | 0.5%    |
| Gigabyte B550M      | 3        | 0.5%    |
| Gigabyte B450M      | 3        | 0.5%    |
| Gigabyte B450       | 3        | 0.5%    |
| Biostar A10N-8800E  | 3        | 0.5%    |
| ASUS P9X79          | 3        | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 76       | 12.67%  |
| 2013 | 66       | 11%     |
| 2019 | 65       | 10.83%  |
| 2012 | 54       | 9%      |
| 2020 | 51       | 8.5%    |
| 2011 | 46       | 7.67%   |
| 2015 | 33       | 5.5%    |
| 2014 | 32       | 5.33%   |
| 2010 | 31       | 5.17%   |
| 2009 | 29       | 4.83%   |
| 2016 | 28       | 4.67%   |
| 2017 | 27       | 4.5%    |
| 2021 | 21       | 3.5%    |
| 2007 | 16       | 2.67%   |
| 2008 | 14       | 2.33%   |
| 2006 | 6        | 1%      |
| 2022 | 3        | 0.5%    |
| 2005 | 2        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 600      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 585      | 97.18%  |
| Enabled  | 17       | 2.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 600      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 163      | 26.85%  |
| 8.01-16.0       | 118      | 19.44%  |
| 32.01-64.0      | 115      | 18.95%  |
| 4.01-8.0        | 75       | 12.36%  |
| 3.01-4.0        | 66       | 10.87%  |
| 64.01-256.0     | 33       | 5.44%   |
| 24.01-32.0      | 20       | 3.29%   |
| 1.01-2.0        | 8        | 1.32%   |
| More than 256.0 | 4        | 0.66%   |
| 2.01-3.0        | 3        | 0.49%   |
| 0.51-1.0        | 1        | 0.16%   |
| Unknown         | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 222      | 33.74%  |
| 2.01-3.0   | 147      | 22.34%  |
| 4.01-8.0   | 101      | 15.35%  |
| 3.01-4.0   | 77       | 11.7%   |
| 8.01-16.0  | 48       | 7.29%   |
| 0.51-1.0   | 40       | 6.08%   |
| 0.01-0.5   | 8        | 1.22%   |
| 16.01-24.0 | 7        | 1.06%   |
| 32.01-64.0 | 4        | 0.61%   |
| 24.01-32.0 | 3        | 0.46%   |
| Unknown    | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 204      | 32.28%  |
| 2      | 178      | 28.16%  |
| 3      | 117      | 18.51%  |
| 4      | 68       | 10.76%  |
| 5      | 25       | 3.96%   |
| 6      | 16       | 2.53%   |
| 9      | 10       | 1.58%   |
| 7      | 6        | 0.95%   |
| 10     | 3        | 0.47%   |
| 11     | 2        | 0.32%   |
| 8      | 2        | 0.32%   |
| 0      | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 330      | 54.55%  |
| No        | 275      | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 597      | 99.5%   |
| No        | 3        | 0.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 361      | 59.47%  |
| Yes       | 246      | 40.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 426      | 70.65%  |
| Yes       | 177      | 29.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 600      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 331      | 52.71%  |
| Graz              | 35       | 5.57%   |
| Linz              | 20       | 3.18%   |
| Innsbruck         | 18       | 2.87%   |
| Salzburg          | 12       | 1.91%   |
| Bad Hall          | 12       | 1.91%   |
| Dornbirn          | 9        | 1.43%   |
| Sankt Pölten     | 8        | 1.27%   |
| Klagenfurt        | 7        | 1.11%   |
| Wels              | 6        | 0.96%   |
| Wiener Neustadt   | 4        | 0.64%   |
| Steyr             | 4        | 0.64%   |
| Zell am See       | 3        | 0.48%   |
| Voecklabruck      | 3        | 0.48%   |
| Seiersberg        | 3        | 0.48%   |
| Klosterneuburg    | 3        | 0.48%   |
| Horn              | 3        | 0.48%   |
| Hallein           | 3        | 0.48%   |
| Brunn am Gebirge  | 3        | 0.48%   |
| Bad Tatzmannsdorf | 3        | 0.48%   |
| Woellersdorf      | 2        | 0.32%   |
| Villach           | 2        | 0.32%   |
| Unterpremstaetten | 2        | 0.32%   |
| Traunkirchen      | 2        | 0.32%   |
| Schwechat         | 2        | 0.32%   |
| Sankt Valentin    | 2        | 0.32%   |
| Ried im Innkreis  | 2        | 0.32%   |
| Perg              | 2        | 0.32%   |
| Perchtoldsdorf    | 2        | 0.32%   |
| Neunkirchen       | 2        | 0.32%   |
| Korneuburg        | 2        | 0.32%   |
| Haid              | 2        | 0.32%   |
| Feldkirch         | 2        | 0.32%   |
| Ernsthofen        | 2        | 0.32%   |
| Enzesfeld         | 2        | 0.32%   |
| Wörgl            | 1        | 0.16%   |
| Walding           | 1        | 0.16%   |
| Wagna             | 1        | 0.16%   |
| Voitsberg         | 1        | 0.16%   |
| Unterweissenbach  | 1        | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 258      | 429    | 21.94%  |
| WDC                       | 187      | 309    | 15.9%   |
| Seagate                   | 185      | 282    | 15.73%  |
| SanDisk                   | 106      | 148    | 9.01%   |
| Crucial                   | 61       | 102    | 5.19%   |
| Kingston                  | 57       | 69     | 4.85%   |
| Toshiba                   | 54       | 99     | 4.59%   |
| Hitachi                   | 26       | 29     | 2.21%   |
| Intel                     | 24       | 34     | 2.04%   |
| Intenso                   | 20       | 25     | 1.7%    |
| Phison                    | 15       | 22     | 1.28%   |
| Unknown                   | 14       | 27     | 1.19%   |
| Transcend                 | 12       | 14     | 1.02%   |
| Micron Technology         | 12       | 13     | 1.02%   |
| A-DATA Technology         | 12       | 15     | 1.02%   |
| HGST                      | 11       | 21     | 0.94%   |
| OCZ                       | 10       | 18     | 0.85%   |
| Corsair                   | 10       | 13     | 0.85%   |
| Micron/Crucial Technology | 7        | 9      | 0.6%    |
| China                     | 7        | 11     | 0.6%    |
| SK hynix                  | 4        | 10     | 0.34%   |
| Silicon Motion            | 4        | 5      | 0.34%   |
| Maxtor                    | 4        | 4      | 0.34%   |
| ASMT                      | 4        | 10     | 0.34%   |
| Apacer                    | 4        | 5      | 0.34%   |
| SABRENT                   | 3        | 4      | 0.26%   |
| Phison Electronics        | 3        | 4      | 0.26%   |
| Patriot                   | 3        | 4      | 0.26%   |
| LITEON                    | 3        | 3      | 0.26%   |
| KIOXIA                    | 3        | 7      | 0.26%   |
| SPCC                      | 2        | 11     | 0.17%   |
| PNY                       | 2        | 2      | 0.17%   |
| Plextor                   | 2        | 2      | 0.17%   |
| JMicron Technology        | 2        | 5      | 0.17%   |
| GOODRAM                   | 2        | 2      | 0.17%   |
| Gigabyte Technology       | 2        | 3      | 0.17%   |
| Unknown                   | 2        | 2      | 0.17%   |
| WDC WDS2                  | 1        | 1      | 0.09%   |
| WD MediaMax               | 1        | 1      | 0.09%   |
| ViperTeq                  | 1        | 4      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB       | 20       | 1.44%   |
| Samsung SSD 850 EVO 250GB       | 18       | 1.29%   |
| Samsung SSD 860 EVO 500GB       | 16       | 1.15%   |
| Samsung SSD 840 EVO 250GB       | 16       | 1.15%   |
| Seagate Expansion 4TB           | 15       | 1.08%   |
| Samsung SSD 860 EVO 1TB         | 13       | 0.93%   |
| Samsung SSD 850 PRO 256GB       | 13       | 0.93%   |
| SanDisk SSD PLUS 240GB          | 12       | 0.86%   |
| Toshiba DT01ACA200 2TB          | 11       | 0.79%   |
| Samsung NVMe SSD Drive 500GB    | 11       | 0.79%   |
| Toshiba HDWD110 1TB             | 10       | 0.72%   |
| Samsung SSD 860 EVO 250GB       | 10       | 0.72%   |
| Crucial CT500MX500SSD1 500GB    | 10       | 0.72%   |
| Toshiba DT01ACA100 1TB          | 9        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB  | 9        | 0.65%   |
| SanDisk SSD PLUS 480GB          | 9        | 0.65%   |
| WDC WD30EFRX-68EUZN0 3TB        | 8        | 0.57%   |
| Unknown SD/MMC/MS PRO 64GB      | 8        | 0.57%   |
| Seagate ST4000VN008-2DR166 4TB  | 8        | 0.57%   |
| Seagate ST31000528AS 1TB        | 8        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB  | 8        | 0.57%   |
| SanDisk SSD PLUS 1000GB         | 8        | 0.57%   |
| SanDisk SDSSDH3 1T00 1TB        | 8        | 0.57%   |
| SanDisk NVMe SSD Drive 1TB      | 8        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB  | 8        | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB    | 8        | 0.57%   |
| Samsung HD103SJ 1TB             | 8        | 0.57%   |
| Kingston SA400S37120G 120GB SSD | 8        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB     | 8        | 0.57%   |
| WDC WD10EADS-22M2B0 1TB         | 7        | 0.5%    |
| Seagate ST4000DM000-1F2168 4TB  | 7        | 0.5%    |
| Samsung SSD 980 PRO 1TB         | 7        | 0.5%    |
| Samsung SSD 860 QVO 1TB         | 7        | 0.5%    |
| Kingston SA400S37240G 240GB SSD | 7        | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB        | 6        | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB        | 6        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB  | 6        | 0.43%   |
| SanDisk SDSSDA240G 240GB        | 6        | 0.43%   |
| Samsung NVMe SSD Drive 1TB      | 6        | 0.43%   |
| Samsung HD501LJ 500GB           | 6        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 180      | 269    | 35.57%  |
| WDC                 | 167      | 278    | 33%     |
| Toshiba             | 53       | 97     | 10.47%  |
| Samsung Electronics | 41       | 60     | 8.1%    |
| Hitachi             | 26       | 29     | 5.14%   |
| HGST                | 11       | 21     | 2.17%   |
| Unknown             | 9        | 15     | 1.78%   |
| Maxtor              | 4        | 4      | 0.79%   |
| ASMT                | 4        | 10     | 0.79%   |
| Intenso             | 3        | 3      | 0.59%   |
| JMicron Technology  | 2        | 4      | 0.4%    |
| WD MediaMax         | 1        | 1      | 0.2%    |
| USB                 | 1        | 1      | 0.2%    |
| Synology            | 1        | 8      | 0.2%    |
| Magnetic Data       | 1        | 1      | 0.2%    |
| LaCie               | 1        | 1      | 0.2%    |
| Hewlett-Packard     | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 167      | 249    | 34.08%  |
| SanDisk             | 88       | 122    | 17.96%  |
| Crucial             | 56       | 86     | 11.43%  |
| Kingston            | 49       | 54     | 10%     |
| Intenso             | 14       | 19     | 2.86%   |
| Intel               | 14       | 20     | 2.86%   |
| WDC                 | 11       | 13     | 2.24%   |
| Transcend           | 10       | 11     | 2.04%   |
| OCZ                 | 10       | 18     | 2.04%   |
| Micron Technology   | 8        | 9      | 1.63%   |
| China               | 7        | 11     | 1.43%   |
| A-DATA Technology   | 7        | 9      | 1.43%   |
| Corsair             | 6        | 6      | 1.22%   |
| Apacer              | 4        | 4      | 0.82%   |
| LITEON              | 3        | 3      | 0.61%   |
| SK hynix            | 2        | 8      | 0.41%   |
| Plextor             | 2        | 2      | 0.41%   |
| Patriot             | 2        | 2      | 0.41%   |
| GOODRAM             | 2        | 2      | 0.41%   |
| WDC WDS2            | 1        | 1      | 0.2%    |
| ViperTeq            | 1        | 4      | 0.2%    |
| VERICO              | 1        | 1      | 0.2%    |
| Verbatim            | 1        | 1      | 0.2%    |
| V7                  | 1        | 1      | 0.2%    |
| TSA                 | 1        | 1      | 0.2%    |
| TO Exter            | 1        | 3      | 0.2%    |
| Team                | 1        | 1      | 0.2%    |
| TCSUNBOW            | 1        | 1      | 0.2%    |
| T-FORCE             | 1        | 1      | 0.2%    |
| Super Talent        | 1        | 1      | 0.2%    |
| SPCC                | 1        | 1      | 0.2%    |
| Seagate             | 1        | 1      | 0.2%    |
| PNY                 | 1        | 1      | 0.2%    |
| Phison              | 1        | 2      | 0.2%    |
| OCZ-VERTEX3         | 1        | 1      | 0.2%    |
| NGFF                | 1        | 1      | 0.2%    |
| LITEONIT            | 1        | 1      | 0.2%    |
| KingSpec            | 1        | 1      | 0.2%    |
| KingDian            | 1        | 1      | 0.2%    |
| INNOVATION IT       | 1        | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 393      | 683    | 40.68%  |
| HDD     | 385      | 803    | 39.86%  |
| NVMe    | 172      | 307    | 17.81%  |
| Unknown | 14       | 29     | 1.45%   |
| MMC     | 2        | 3      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 549      | 1416   | 70.47%  |
| NVMe | 169      | 303    | 21.69%  |
| SAS  | 59       | 103    | 7.57%   |
| MMC  | 2        | 3      | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 407      | 729    | 46.04%  |
| 0.51-1.0   | 243      | 359    | 27.49%  |
| 1.01-2.0   | 105      | 172    | 11.88%  |
| 3.01-4.0   | 63       | 116    | 7.13%   |
| 2.01-3.0   | 31       | 44     | 3.51%   |
| 4.01-10.0  | 29       | 45     | 3.28%   |
| 10.01-20.0 | 6        | 21     | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 125      | 19.53%  |
| 501-1000       | 102      | 15.94%  |
| More than 3000 | 80       | 12.5%   |
| 251-500        | 77       | 12.03%  |
| 1001-2000      | 75       | 11.72%  |
| 1-20           | 49       | 7.66%   |
| 2001-3000      | 42       | 6.56%   |
| 51-100         | 34       | 5.31%   |
| Unknown        | 32       | 5%      |
| 21-50          | 24       | 3.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 218      | 33.13%  |
| 21-50          | 71       | 10.79%  |
| 251-500        | 61       | 9.27%   |
| 501-1000       | 61       | 9.27%   |
| 101-250        | 58       | 8.81%   |
| 1001-2000      | 53       | 8.05%   |
| 51-100         | 48       | 7.29%   |
| More than 3000 | 32       | 4.86%   |
| Unknown        | 32       | 4.86%   |
| 2001-3000      | 24       | 3.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB            | 7        | 7      | 8.14%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 5        | 5      | 5.81%   |
| Samsung Electronics HD103UJ 1TB    | 3        | 3      | 3.49%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2        | 2      | 2.33%   |
| Seagate ST3500413AS 500GB          | 2        | 2      | 2.33%   |
| SanDisk SSD PLUS 480GB             | 2        | 2      | 2.33%   |
| WDC WD6400AACS-00G8B0 640GB        | 1        | 1      | 1.16%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 1      | 1.16%   |
| WDC WD5000AAKS-60Z1A0 500GB        | 1        | 1      | 1.16%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 1      | 1.16%   |
| WDC WD5000AADS-00M2B0 500GB        | 1        | 1      | 1.16%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 1      | 1.16%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 1      | 1.16%   |
| WDC WD20EFRX-68AX9N0 2TB           | 1        | 10     | 1.16%   |
| WDC WD2003FYYS-02W0B1 2TB          | 1        | 1      | 1.16%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 1      | 1.16%   |
| WDC WD2000FYYZ-01UL1B1 2TB         | 1        | 1      | 1.16%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1        | 1      | 1.16%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 1.16%   |
| WDC WD10EZEX-75M2NA0 1TB           | 1        | 1      | 1.16%   |
| WDC WD10EACS-00D6B0 1TB            | 1        | 2      | 1.16%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 1      | 1.16%   |
| Transcend TS240GSSD220S 240GB      | 1        | 1      | 1.16%   |
| Toshiba MK1665GSX 160GB            | 1        | 1      | 1.16%   |
| Toshiba HDWD110 1TB                | 1        | 2      | 1.16%   |
| SK hynix SC308 SATA 128GB SSD      | 1        | 7      | 1.16%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 1.16%   |
| Seagate ST500LM021-1KJ152 500GB    | 1        | 1      | 1.16%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 1.16%   |
| Seagate ST3750528AS 752GB          | 1        | 1      | 1.16%   |
| Seagate ST3500830AS 500GB          | 1        | 1      | 1.16%   |
| Seagate ST3400832AS 400GB          | 1        | 1      | 1.16%   |
| Seagate ST3250823AS 250GB          | 1        | 1      | 1.16%   |
| Seagate ST3250410AS 250GB          | 1        | 1      | 1.16%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 1.16%   |
| Seagate ST3000DM001-9YN166 3TB     | 1        | 1      | 1.16%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 1.16%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 1      | 1.16%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 1      | 1.16%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1      | 1.16%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 35     | 29.63%  |
| Seagate             | 15       | 17     | 18.52%  |
| Samsung Electronics | 14       | 18     | 17.28%  |
| SanDisk             | 10       | 10     | 12.35%  |
| Hitachi             | 6        | 6      | 7.41%   |
| Toshiba             | 2        | 3      | 2.47%   |
| OCZ                 | 2        | 4      | 2.47%   |
| Transcend           | 1        | 1      | 1.23%   |
| SK hynix            | 1        | 7      | 1.23%   |
| Maxtor              | 1        | 1      | 1.23%   |
| Kingston            | 1        | 1      | 1.23%   |
| Intenso             | 1        | 1      | 1.23%   |
| Intel               | 1        | 1      | 1.23%   |
| HGST                | 1        | 9      | 1.23%   |
| Crucial             | 1        | 1      | 1.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 35     | 42.11%  |
| Seagate             | 15       | 17     | 26.32%  |
| Samsung Electronics | 8        | 9      | 14.04%  |
| Hitachi             | 6        | 6      | 10.53%  |
| Toshiba             | 2        | 3      | 3.51%   |
| Maxtor              | 1        | 1      | 1.75%   |
| HGST                | 1        | 9      | 1.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 53       | 80     | 68.83%  |
| SSD  | 21       | 31     | 27.27%  |
| NVMe | 3        | 4      | 3.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 360      | 947    | 52.55%  |
| Works    | 256      | 761    | 37.37%  |
| Malfunc  | 67       | 115    | 9.78%   |
| Failed   | 1        | 1      | 0.15%   |
| Limited  | 1        | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 367      | 38.92%  |
| AMD                           | 223      | 23.65%  |
| Samsung Electronics           | 87       | 9.23%   |
| ASMedia Technology            | 55       | 5.83%   |
| Marvell Technology Group      | 36       | 3.82%   |
| SanDisk                       | 31       | 3.29%   |
| JMicron Technology            | 30       | 3.18%   |
| Phison Electronics            | 24       | 2.55%   |
| Micron/Crucial Technology     | 12       | 1.27%   |
| Nvidia                        | 10       | 1.06%   |
| Kingston Technology Company   | 10       | 1.06%   |
| LSI Logic / Symbios Logic     | 9        | 0.95%   |
| ADATA Technology              | 7        | 0.74%   |
| Silicon Motion                | 6        | 0.64%   |
| VIA Technologies              | 5        | 0.53%   |
| Seagate Technology            | 4        | 0.42%   |
| Micron Technology             | 4        | 0.42%   |
| Broadcom / LSI                | 4        | 0.42%   |
| SK hynix                      | 3        | 0.32%   |
| Silicon Image                 | 3        | 0.32%   |
| KIOXIA                        | 3        | 0.32%   |
| OCZ Technology Group          | 2        | 0.21%   |
| Adaptec                       | 2        | 0.21%   |
| Toshiba America Info Systems  | 1        | 0.11%   |
| Realtek Semiconductor         | 1        | 0.11%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.11%   |
| Lite-On Technology            | 1        | 0.11%   |
| Lite-On IT Corp. / Plextor    | 1        | 0.11%   |
| Integrated Technology Express | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 125      | 10.91%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 56       | 4.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 55       | 4.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 50       | 4.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 49       | 4.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 41       | 3.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 37       | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 34       | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34       | 2.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 32       | 2.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 24       | 2.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 1.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 21       | 1.83%   |
| Intel SATA Controller [RAID mode]                                                       | 20       | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 18       | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 1.4%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.22%   |
| Phison E12 NVMe Controller                                                              | 13       | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 0.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 10       | 0.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 9        | 0.79%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 9        | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 9        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 0.79%   |
| AMD FCH SATA Controller D                                                               | 9        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8        | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 8        | 0.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 8        | 0.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 7        | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                         | 7        | 0.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 0.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 518      | 59.82%  |
| NVMe | 172      | 19.86%  |
| IDE  | 126      | 14.55%  |
| RAID | 37       | 4.27%   |
| SCSI | 7        | 0.81%   |
| SAS  | 6        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 366      | 61%     |
| AMD    | 234      | 39%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 16       | 2.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 1.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 10       | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 1.67%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 1.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.5%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 1.5%    |
| AMD FX-8350 Eight-Core Processor            | 9        | 1.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 8        | 1.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 1.17%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 7        | 1.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.17%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 7        | 1.17%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 1%      |
| Intel Core i7-7700K CPU @ 4.20GHz           | 6        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6        | 1%      |
| Intel Core i5-4570TE CPU @ 2.70GHz          | 6        | 1%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1%      |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 6        | 1%      |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 6        | 1%      |
| AMD FX-6300 Six-Core Processor              | 6        | 1%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.83%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 5        | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.83%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 5        | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.83%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 5        | 0.83%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 0.83%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 5        | 0.83%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.83%   |
| AMD Phenom II X4 955 Processor              | 5        | 0.83%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.67%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 4        | 0.67%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 4        | 0.67%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 121      | 20.17%  |
| Intel Core i7           | 103      | 17.17%  |
| AMD Ryzen 5             | 54       | 9%      |
| AMD Ryzen 7             | 47       | 7.83%   |
| AMD FX                  | 28       | 4.67%   |
| Intel Xeon              | 26       | 4.33%   |
| Intel Core i3           | 26       | 4.33%   |
| AMD Ryzen 9             | 19       | 3.17%   |
| Intel Celeron           | 18       | 3%      |
| AMD Phenom II X4        | 14       | 2.33%   |
| AMD Ryzen 3             | 13       | 2.17%   |
| Intel Core i9           | 12       | 2%      |
| Intel Core 2 Duo        | 11       | 1.83%   |
| AMD A8                  | 11       | 1.83%   |
| Other                   | 10       | 1.67%   |
| Intel Core 2 Quad       | 10       | 1.67%   |
| Intel Pentium           | 9        | 1.5%    |
| AMD A10                 | 8        | 1.33%   |
| AMD Phenom II X6        | 7        | 1.17%   |
| AMD Athlon II X4        | 6        | 1%      |
| AMD Athlon 64 X2        | 6        | 1%      |
| Intel Pentium Dual-Core | 5        | 0.83%   |
| Intel Atom              | 5        | 0.83%   |
| Intel Core 2            | 4        | 0.67%   |
| AMD Ryzen Threadripper  | 4        | 0.67%   |
| Intel Pentium 4         | 3        | 0.5%    |
| AMD E                   | 3        | 0.5%    |
| AMD Athlon              | 3        | 0.5%    |
| AMD Ryzen 7 PRO         | 2        | 0.33%   |
| AMD Phenom              | 2        | 0.33%   |
| AMD Athlon II X2        | 2        | 0.33%   |
| Intel Pentium Silver    | 1        | 0.17%   |
| Intel Pentium Dual      | 1        | 0.17%   |
| Intel Genuine           | 1        | 0.17%   |
| AMD Ryzen 5 PRO         | 1        | 0.17%   |
| AMD Ryzen 3 PRO         | 1        | 0.17%   |
| AMD Phenom II X2        | 1        | 0.17%   |
| AMD Athlon X4           | 1        | 0.17%   |
| AMD A6                  | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 276      | 45.85%  |
| 2       | 116      | 19.27%  |
| 6       | 85       | 14.12%  |
| 8       | 70       | 11.63%  |
| 12      | 17       | 2.82%   |
| 16      | 14       | 2.33%   |
| 3       | 6        | 1%      |
| 10      | 5        | 0.83%   |
| 1       | 5        | 0.83%   |
| 14      | 3        | 0.5%    |
| Unknown | 2        | 0.33%   |
| 64      | 1        | 0.17%   |
| 40      | 1        | 0.17%   |
| 24      | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 595      | 99.17%  |
| 2      | 5        | 0.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 366      | 60.8%   |
| 1       | 234      | 38.87%  |
| Unknown | 2        | 0.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 588      | 98%     |
| Unknown        | 10       | 1.67%   |
| 32-bit         | 2        | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 139      | 22.38%  |
| 0x306c3    | 53       | 8.53%   |
| 0x306a9    | 31       | 4.99%   |
| 0x206a7    | 29       | 4.67%   |
| 0x506e3    | 27       | 4.35%   |
| 0x08701021 | 22       | 3.54%   |
| 0x906e9    | 15       | 2.42%   |
| 0x08701013 | 14       | 2.25%   |
| 0x0800820d | 14       | 2.25%   |
| 0x06000852 | 14       | 2.25%   |
| 0x08108109 | 12       | 1.93%   |
| 0x010000c8 | 12       | 1.93%   |
| 0x906ea    | 11       | 1.77%   |
| 0x06001119 | 11       | 1.77%   |
| 0x106e5    | 10       | 1.61%   |
| 0x0a201016 | 10       | 1.61%   |
| 0x1067a    | 9        | 1.45%   |
| 0xa0655    | 8        | 1.29%   |
| 0x08001138 | 8        | 1.29%   |
| 0x0a50000c | 7        | 1.13%   |
| 0x0a201009 | 7        | 1.13%   |
| 0x306f2    | 6        | 0.97%   |
| 0x106a5    | 6        | 0.97%   |
| 0x010000dc | 6        | 0.97%   |
| 0x6fb      | 5        | 0.81%   |
| 0x0600611a | 5        | 0.81%   |
| 0xa0671    | 4        | 0.64%   |
| 0x906ed    | 4        | 0.64%   |
| 0x50654    | 4        | 0.64%   |
| 0x0a50000d | 4        | 0.64%   |
| 0x0800820b | 4        | 0.64%   |
| 0x010000db | 4        | 0.64%   |
| 0xa0653    | 3        | 0.48%   |
| 0x906ec    | 3        | 0.48%   |
| 0x90672    | 3        | 0.48%   |
| 0x706a8    | 3        | 0.48%   |
| 0x6f6      | 3        | 0.48%   |
| 0x506c9    | 3        | 0.48%   |
| 0x206d7    | 3        | 0.48%   |
| 0x206c2    | 3        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 78       | 12.98%  |
| Zen 2            | 56       | 9.32%   |
| KabyLake         | 48       | 7.99%   |
| Skylake          | 44       | 7.32%   |
| IvyBridge        | 42       | 6.99%   |
| SandyBridge      | 41       | 6.82%   |
| Zen+             | 36       | 5.99%   |
| Zen 3            | 34       | 5.66%   |
| Piledriver       | 33       | 5.49%   |
| K10              | 32       | 5.32%   |
| Penryn           | 19       | 3.16%   |
| Nehalem          | 18       | 3%      |
| Zen              | 17       | 2.83%   |
| CometLake        | 15       | 2.5%    |
| Westmere         | 14       | 2.33%   |
| Core             | 12       | 2%      |
| Unknown          | 7        | 1.16%   |
| K8 Hammer        | 6        | 1%      |
| Steamroller      | 5        | 0.83%   |
| Silvermont       | 5        | 0.83%   |
| Goldmont plus    | 5        | 0.83%   |
| Excavator        | 5        | 0.83%   |
| NetBurst         | 4        | 0.67%   |
| Goldmont         | 4        | 0.67%   |
| K10 Llano        | 3        | 0.5%    |
| Bulldozer        | 3        | 0.5%    |
| Broadwell        | 3        | 0.5%    |
| Bonnell          | 3        | 0.5%    |
| Bobcat           | 3        | 0.5%    |
| Alderlake Hybrid | 3        | 0.5%    |
| Icelake          | 2        | 0.33%   |
| Tremont          | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 273      | 42.52%  |
| AMD                        | 213      | 33.18%  |
| Intel                      | 150      | 23.36%  |
| ASPEED Technology          | 3        | 0.47%   |
| Matrox Electronics Systems | 2        | 0.31%   |
| ATI Technologies           | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 28       | 4.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 27       | 4.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 2.59%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 14       | 2.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 1.98%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 13       | 1.98%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 1.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 12       | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12       | 1.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 11       | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 1.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 9        | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 9        | 1.37%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 1.37%   |
| Intel HD Graphics 530                                                       | 9        | 1.37%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 1.37%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 1.37%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 1.22%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 8        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 1.22%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 7        | 1.07%   |
| Intel HD Graphics 630                                                       | 7        | 1.07%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 7        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 0.91%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 6        | 0.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 0.91%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6        | 0.91%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 5        | 0.76%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 5        | 0.76%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 5        | 0.76%   |
| AMD Renoir                                                                  | 5        | 0.76%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 0.61%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.61%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.61%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 4        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 254      | 41.78%  |
| 1 x AMD         | 201      | 33.06%  |
| 1 x Intel       | 121      | 19.9%   |
| Intel + Nvidia  | 9        | 1.48%   |
| 2 x AMD         | 8        | 1.32%   |
| AMD + Nvidia    | 5        | 0.82%   |
| 2 x Nvidia      | 3        | 0.49%   |
| Nvidia + ASPEED | 2        | 0.33%   |
| 1 x Matrox      | 2        | 0.33%   |
| Other           | 1        | 0.16%   |
| Intel + AMD     | 1        | 0.16%   |
| 1 x ASPEED      | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 433      | 70.75%  |
| Proprietary | 154      | 25.16%  |
| Unknown     | 25       | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 219      | 35.55%  |
| 1.01-2.0   | 91       | 14.77%  |
| 7.01-8.0   | 71       | 11.53%  |
| 0.51-1.0   | 62       | 10.06%  |
| 0.01-0.5   | 59       | 9.58%   |
| 3.01-4.0   | 58       | 9.42%   |
| 5.01-6.0   | 28       | 4.55%   |
| 8.01-16.0  | 16       | 2.6%    |
| 2.01-3.0   | 8        | 1.3%    |
| 16.01-24.0 | 3        | 0.49%   |
| 4.01-5.0   | 1        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 138      | 20.41%  |
| BenQ                    | 72       | 10.65%  |
| Dell                    | 49       | 7.25%   |
| Acer                    | 42       | 6.21%   |
| Hewlett-Packard         | 41       | 6.07%   |
| Goldstar                | 38       | 5.62%   |
| AOC                     | 36       | 5.33%   |
| Philips                 | 35       | 5.18%   |
| Iiyama                  | 29       | 4.29%   |
| Ancor Communications    | 23       | 3.4%    |
| Medion                  | 18       | 2.66%   |
| Eizo                    | 18       | 2.66%   |
| NEC Computers           | 10       | 1.48%   |
| Gericom                 | 10       | 1.48%   |
| Fujitsu Siemens         | 10       | 1.48%   |
| ViewSonic               | 9        | 1.33%   |
| Lenovo                  | 9        | 1.33%   |
| Unknown                 | 8        | 1.18%   |
| Sony                    | 8        | 1.18%   |
| LG Electronics          | 5        | 0.74%   |
| Idek Iiyama             | 5        | 0.74%   |
| HannStar                | 4        | 0.59%   |
| GRM                     | 4        | 0.59%   |
| ASUSTek Computer        | 4        | 0.59%   |
| Toshiba                 | 3        | 0.44%   |
| MSI                     | 3        | 0.44%   |
| HVR                     | 3        | 0.44%   |
| Belinea                 | 3        | 0.44%   |
| Apple                   | 3        | 0.44%   |
| Vestel Elektronik       | 2        | 0.3%    |
| Plain Tree Systems      | 2        | 0.3%    |
| Lenovo Group Limited    | 2        | 0.3%    |
| Jean                    | 2        | 0.3%    |
| Hitachi                 | 2        | 0.3%    |
| DENON                   | 2        | 0.3%    |
| Chi Mei Optoelectronics | 2        | 0.3%    |
| YUK                     | 1        | 0.15%   |
| TVT                     | 1        | 0.15%   |
| TopView                 | 1        | 0.15%   |
| SKY                     | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 7        | 0.95%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 7        | 0.95%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                       | 7        | 0.95%   |
| Gericom Q24 QMX2421 1920x1080 521x293mm 23.5-inch                     | 5        | 0.68%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5        | 0.68%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 4        | 0.54%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 4        | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.54%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 4        | 0.54%   |
| GRM GM2600 GRM5BC6 1920x1200 550x344mm 25.5-inch                      | 4        | 0.54%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.54%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 3        | 0.41%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 3        | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 3        | 0.41%   |
| Samsung Electronics S24C450 SAM09CA 1920x1080 531x299mm 24.0-inch     | 3        | 0.41%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 3        | 0.41%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.41%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                 | 3        | 0.41%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 3        | 0.41%   |
| Eizo S2202W ENC1975 1680x1050 474x297mm 22.0-inch                     | 3        | 0.41%   |
| Dell U2719D DEL415F 2560x1440 597x336mm 27.0-inch                     | 3        | 0.41%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 3        | 0.41%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                    | 3        | 0.41%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.41%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 3        | 0.41%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 3        | 0.41%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 2        | 0.27%   |
| Unknown LCD Monitor GRM GM2600 1920x1200                              | 2        | 0.27%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                       | 2        | 0.27%   |
| Sony TV *00 SNY3F05 3840x2160 1439x809mm 65.0-inch                    | 2        | 0.27%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                      | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM034E 1280x1024 376x301mm 19.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.27%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch    | 2        | 0.27%   |
| Samsung Electronics SMBX2035 SAM06FE 1600x900 440x250mm 19.9-inch     | 2        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 289      | 43.33%  |
| 3840x2160 (4K)     | 82       | 12.29%  |
| 2560x1440 (QHD)    | 62       | 9.3%    |
| 1680x1050 (WSXGA+) | 54       | 8.1%    |
| 1280x1024 (SXGA)   | 47       | 7.05%   |
| 1920x1200 (WUXGA)  | 43       | 6.45%   |
| Unknown            | 15       | 2.25%   |
| 3440x1440          | 12       | 1.8%    |
| 2560x1080          | 8        | 1.2%    |
| 3840x1080          | 7        | 1.05%   |
| 2560x1600          | 5        | 0.75%   |
| 1920x540           | 4        | 0.6%    |
| 1600x900 (HD+)     | 4        | 0.6%    |
| 1440x900 (WXGA+)   | 4        | 0.6%    |
| 1366x768 (WXGA)    | 4        | 0.6%    |
| 2160x1200          | 3        | 0.45%   |
| 2048x1152          | 3        | 0.45%   |
| 1024x768 (XGA)     | 3        | 0.45%   |
| 5760x2160          | 2        | 0.3%    |
| 5120x1440          | 2        | 0.3%    |
| 4480x1440          | 2        | 0.3%    |
| 1600x1200          | 2        | 0.3%    |
| 5760x1080          | 1        | 0.15%   |
| 3840x2560          | 1        | 0.15%   |
| 3840x1200          | 1        | 0.15%   |
| 3600x1080          | 1        | 0.15%   |
| 3520x1080          | 1        | 0.15%   |
| 3360x1050          | 1        | 0.15%   |
| 3200x1080          | 1        | 0.15%   |
| 1400x1050          | 1        | 0.15%   |
| 1360x768           | 1        | 0.15%   |
| 1280x960           | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 124      | 18.4%   |
| 27      | 110      | 16.32%  |
| 23      | 85       | 12.61%  |
| Unknown | 73       | 10.83%  |
| 19      | 43       | 6.38%   |
| 22      | 40       | 5.93%   |
| 21      | 38       | 5.64%   |
| 31      | 31       | 4.6%    |
| 25      | 17       | 2.52%   |
| 34      | 15       | 2.23%   |
| 20      | 13       | 1.93%   |
| 84      | 11       | 1.63%   |
| 17      | 11       | 1.63%   |
| 32      | 6        | 0.89%   |
| 28      | 6        | 0.89%   |
| 65      | 5        | 0.74%   |
| 54      | 5        | 0.74%   |
| 40      | 5        | 0.74%   |
| 18      | 5        | 0.74%   |
| 15      | 4        | 0.59%   |
| 72      | 3        | 0.45%   |
| 42      | 3        | 0.45%   |
| 29      | 3        | 0.45%   |
| 75      | 2        | 0.3%    |
| 48      | 2        | 0.3%    |
| 33      | 2        | 0.3%    |
| 61      | 1        | 0.15%   |
| 60      | 1        | 0.15%   |
| 52      | 1        | 0.15%   |
| 49      | 1        | 0.15%   |
| 46      | 1        | 0.15%   |
| 43      | 1        | 0.15%   |
| 41      | 1        | 0.15%   |
| 39      | 1        | 0.15%   |
| 35      | 1        | 0.15%   |
| 26      | 1        | 0.15%   |
| 16      | 1        | 0.15%   |
| 13      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 287      | 44.29%  |
| 401-500     | 99       | 15.28%  |
| Unknown     | 73       | 11.27%  |
| 601-700     | 61       | 9.41%   |
| 351-400     | 44       | 6.79%   |
| 701-800     | 22       | 3.4%    |
| 1001-1500   | 17       | 2.62%   |
| 1501-2000   | 16       | 2.47%   |
| 301-350     | 15       | 2.31%   |
| 801-900     | 7        | 1.08%   |
| 901-1000    | 5        | 0.77%   |
| 201-300     | 2        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 378      | 60.19%  |
| 16/10   | 111      | 17.68%  |
| Unknown | 56       | 8.92%   |
| 5/4     | 48       | 7.64%   |
| 21/9    | 16       | 2.55%   |
| 4/3     | 6        | 0.96%   |
| 32/9    | 6        | 0.96%   |
| 3/2     | 4        | 0.64%   |
| 6/5     | 2        | 0.32%   |
| 0.80    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 218      | 32.88%  |
| 301-350        | 111      | 16.74%  |
| 151-200        | 73       | 11.01%  |
| Unknown        | 73       | 11.01%  |
| 251-300        | 66       | 9.95%   |
| 351-500        | 61       | 9.2%    |
| More than 1000 | 28       | 4.22%   |
| 501-1000       | 15       | 2.26%   |
| 141-150        | 11       | 1.66%   |
| 101-110        | 3        | 0.45%   |
| 71-80          | 1        | 0.15%   |
| 131-140        | 1        | 0.15%   |
| 121-130        | 1        | 0.15%   |
| 111-120        | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 375      | 61.07%  |
| 101-120 | 97       | 15.8%   |
| Unknown | 73       | 11.89%  |
| 121-160 | 42       | 6.84%   |
| 1-50    | 16       | 2.61%   |
| 161-240 | 11       | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 444      | 72.67%  |
| 2     | 117      | 19.15%  |
| 0     | 32       | 5.24%   |
| 3     | 18       | 2.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 335      | 40.07%  |
| Intel                                 | 281      | 33.61%  |
| Qualcomm Atheros                      | 45       | 5.38%   |
| Ralink Technology                     | 17       | 2.03%   |
| Broadcom                              | 17       | 2.03%   |
| TP-Link                               | 13       | 1.56%   |
| IMC Networks                          | 12       | 1.44%   |
| Microsoft                             | 10       | 1.2%    |
| Ralink                                | 9        | 1.08%   |
| Nvidia                                | 9        | 1.08%   |
| NetGear                               | 9        | 1.08%   |
| ASUSTek Computer                      | 9        | 1.08%   |
| Marvell Technology Group              | 8        | 0.96%   |
| Aquantia                              | 7        | 0.84%   |
| Edimax Technology                     | 6        | 0.72%   |
| Qualcomm Atheros Communications       | 5        | 0.6%    |
| Samsung Electronics                   | 4        | 0.48%   |
| D-Link System                         | 4        | 0.48%   |
| D-Link                                | 4        | 0.48%   |
| Broadcom Limited                      | 4        | 0.48%   |
| VIA Technologies                      | 3        | 0.36%   |
| ASIX Electronics                      | 3        | 0.36%   |
| Microchip Technology                  | 2        | 0.24%   |
| Huawei Technologies                   | 2        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.24%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.12%   |
| Xiaomi                                | 1        | 0.12%   |
| Winbond Electronics                   | 1        | 0.12%   |
| Wilocity                              | 1        | 0.12%   |
| Sigma Designs                         | 1        | 0.12%   |
| SEGGER                                | 1        | 0.12%   |
| Prusa Research (prusa3d.com)          | 1        | 0.12%   |
| Philips (or NXP)                      | 1        | 0.12%   |
| Oculus VR                             | 1        | 0.12%   |
| Motorola PCS                          | 1        | 0.12%   |
| Motorola                              | 1        | 0.12%   |
| Mellanox Technologies                 | 1        | 0.12%   |
| Lenovo                                | 1        | 0.12%   |
| BUFFALO                               | 1        | 0.12%   |
| Belkin Components                     | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 282      | 29.56%  |
| Intel I211 Gigabit Network Connection                              | 46       | 4.82%   |
| Intel Wi-Fi 6 AX200                                                | 35       | 3.67%   |
| Intel Ethernet Connection (2) I219-V                               | 35       | 3.67%   |
| Realtek RTL8125 2.5GbE Controller                                  | 28       | 2.94%   |
| Intel Ethernet Controller I225-V                                   | 23       | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 18       | 1.89%   |
| Intel 82579V Gigabit Network Connection                            | 17       | 1.78%   |
| Intel Ethernet Connection (7) I219-V                               | 16       | 1.68%   |
| Intel Ethernet Connection I217-LM                                  | 13       | 1.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 12       | 1.26%   |
| Intel Ethernet Connection I217-V                                   | 11       | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 9        | 0.94%   |
| Microsoft Xbox 360 Wireless Adapter                                | 9        | 0.94%   |
| Intel Wireless-AC 9260                                             | 9        | 0.94%   |
| Intel Ethernet Connection (2) I218-V                               | 9        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 9        | 0.94%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]               | 9        | 0.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 8        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                              | 8        | 0.84%   |
| Intel 82574L Gigabit Network Connection                            | 8        | 0.84%   |
| Intel I210 Gigabit Network Connection                              | 7        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 7        | 0.73%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 7        | 0.73%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 5        | 0.52%   |
| Ralink RT5370 Wireless Adapter                                     | 5        | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                    | 5        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 5        | 0.52%   |
| Nvidia MCP61 Ethernet                                              | 5        | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller            | 5        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                           | 5        | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 4        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4        | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4        | 0.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4        | 0.42%   |
| Ralink MT7601U Wireless Adapter                                    | 4        | 0.42%   |
| Ralink RT2800 802.11n PCI                                          | 4        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 4        | 0.42%   |
| Intel Wireless 8260                                                | 4        | 0.42%   |
| Intel Ethernet Connection (2) I218-LM                              | 4        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 87       | 32.22%  |
| Realtek Semiconductor                 | 55       | 20.37%  |
| Ralink Technology                     | 17       | 6.3%    |
| Qualcomm Atheros                      | 16       | 5.93%   |
| TP-Link                               | 13       | 4.81%   |
| IMC Networks                          | 12       | 4.44%   |
| Microsoft                             | 10       | 3.7%    |
| Ralink                                | 9        | 3.33%   |
| NetGear                               | 9        | 3.33%   |
| ASUSTek Computer                      | 9        | 3.33%   |
| Broadcom                              | 8        | 2.96%   |
| Edimax Technology                     | 6        | 2.22%   |
| Qualcomm Atheros Communications       | 5        | 1.85%   |
| D-Link System                         | 4        | 1.48%   |
| D-Link                                | 3        | 1.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.74%   |
| Wilocity                              | 1        | 0.37%   |
| Philips (or NXP)                      | 1        | 0.37%   |
| BUFFALO                               | 1        | 0.37%   |
| Broadcom Limited                      | 1        | 0.37%   |
| Belkin Components                     | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 35       | 12.73%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 9        | 3.27%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 9        | 3.27%   |
| Intel Wireless-AC 9260                                                 | 9        | 3.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 9        | 3.27%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                   | 9        | 3.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 8        | 2.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7        | 2.55%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]     | 7        | 2.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 5        | 1.82%   |
| Ralink RT5370 Wireless Adapter                                         | 5        | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 1.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 1.45%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 1.45%   |
| Ralink RT2800 802.11n PCI                                              | 4        | 1.45%   |
| Intel Wireless 8260                                                    | 4        | 1.45%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 4        | 1.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 3        | 1.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.09%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 3        | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 1.09%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.09%   |
| Ralink RT5572 Wireless Adapter                                         | 3        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 1.09%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                | 3        | 1.09%   |
| Intel Wireless 3165                                                    | 3        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 3        | 1.09%   |
| Intel Centrino Wireless-N 2230                                         | 3        | 1.09%   |
| IMC Networks AW-NU222 802.11bgn Wireless Module [Ralink RT2770+RT2720] | 3        | 1.09%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]   | 3        | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 3        | 1.09%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 3        | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.73%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 2        | 0.73%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                 | 2        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 321      | 49.77%  |
| Intel                      | 243      | 37.67%  |
| Qualcomm Atheros           | 30       | 4.65%   |
| Nvidia                     | 9        | 1.4%    |
| Broadcom                   | 9        | 1.4%    |
| Marvell Technology Group   | 8        | 1.24%   |
| Aquantia                   | 7        | 1.09%   |
| Samsung Electronics        | 4        | 0.62%   |
| VIA Technologies           | 3        | 0.47%   |
| Broadcom Limited           | 3        | 0.47%   |
| ASIX Electronics           | 3        | 0.47%   |
| ZTE WCDMA Technologies MSM | 1        | 0.16%   |
| Xiaomi                     | 1        | 0.16%   |
| Motorola PCS               | 1        | 0.16%   |
| Mellanox Technologies      | 1        | 0.16%   |
| D-Link                     | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 282      | 42.28%  |
| Intel I211 Gigabit Network Connection                             | 46       | 6.9%    |
| Intel Ethernet Connection (2) I219-V                              | 35       | 5.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 4.2%    |
| Intel Ethernet Controller I225-V                                  | 23       | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18       | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 17       | 2.55%   |
| Intel Ethernet Connection (7) I219-V                              | 16       | 2.4%    |
| Intel Ethernet Connection I217-LM                                 | 13       | 1.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12       | 1.8%    |
| Intel Ethernet Connection I217-V                                  | 11       | 1.65%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 7        | 1.05%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.75%   |
| Nvidia MCP61 Ethernet                                             | 5        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.75%   |
| Intel 82578DM Gigabit Network Connection                          | 5        | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                             | 4        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.45%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 0.45%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.45%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.3%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.3%    |
| Intel I350 Gigabit Network Connection                             | 2        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 597      | 69.99%  |
| WiFi     | 245      | 28.72%  |
| Modem    | 11       | 1.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 490      | 79.8%   |
| WiFi     | 124      | 20.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 409      | 67.83%  |
| 2     | 153      | 25.37%  |
| 3     | 29       | 4.81%   |
| 4     | 4        | 0.66%   |
| 5     | 3        | 0.5%    |
| 6     | 2        | 0.33%   |
| 0     | 2        | 0.33%   |
| 13    | 1        | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 547      | 90.41%  |
| Yes  | 58       | 9.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 83       | 45.86%  |
| Cambridge Silicon Radio         | 45       | 24.86%  |
| ASUSTek Computer                | 15       | 8.29%   |
| Realtek Semiconductor           | 13       | 7.18%   |
| Broadcom                        | 7        | 3.87%   |
| Qualcomm Atheros Communications | 4        | 2.21%   |
| HTC (High Tech Computer)        | 3        | 1.66%   |
| Belkin Components               | 3        | 1.66%   |
| D-Link System                   | 2        | 1.1%    |
| Apple                           | 2        | 1.1%    |
| Micro Star International        | 1        | 0.55%   |
| Logitech                        | 1        | 0.55%   |
| Lite-On Technology              | 1        | 0.55%   |
| IMC Networks                    | 1        | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 45       | 24.86%  |
| Intel AX200 Bluetooth                                                | 36       | 19.89%  |
| Intel Bluetooth wireless interface                                   | 13       | 7.18%   |
| Realtek Bluetooth Radio                                              | 9        | 4.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 4.42%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8        | 4.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 4.42%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5        | 2.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 2.21%   |
| Intel AX201 Bluetooth                                                | 4        | 2.21%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 3        | 1.66%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 1.66%   |
| ASUS BCM20702A0                                                      | 3        | 1.66%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.1%    |
| Realtek Bluetooth 5.1 Radio                                          | 2        | 1.1%    |
| Intel AX210 Bluetooth                                                | 2        | 1.1%    |
| D-Link System DBT-122 Bluetooth                                      | 2        | 1.1%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 1.1%    |
| ASUS Bluetooth Adapter                                               | 2        | 1.1%    |
| Apple Bluetooth USB Host Controller                                  | 2        | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.55%   |
| Micro Star International Bluetooth Device                            | 1        | 0.55%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.55%   |
| Lite-On Bluetooth Device                                             | 1        | 0.55%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.55%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.55%   |
| Broadcom BCM2210 Bluetooth                                           | 1        | 0.55%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.55%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.55%   |
| Belkin Components F8T013 Bluetooth Adapter                           | 1        | 0.55%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.55%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.55%   |
| ASUS Bluetooth Device                                                | 1        | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 345      | 32.42%  |
| AMD                                          | 289      | 27.16%  |
| Nvidia                                       | 262      | 24.62%  |
| C-Media Electronics                          | 39       | 3.67%   |
| Logitech                                     | 17       | 1.6%    |
| Creative Labs                                | 13       | 1.22%   |
| Razer USA                                    | 7        | 0.66%   |
| JMTek                                        | 6        | 0.56%   |
| GN Netcom                                    | 5        | 0.47%   |
| Corsair                                      | 5        | 0.47%   |
| SteelSeries ApS                              | 4        | 0.38%   |
| Focusrite-Novation                           | 4        | 0.38%   |
| Texas Instruments                            | 3        | 0.28%   |
| RODE Microphones                             | 3        | 0.28%   |
| Kingston Technology                          | 3        | 0.28%   |
| Bose                                         | 3        | 0.28%   |
| ASUSTek Computer                             | 3        | 0.28%   |
| Thomann                                      | 2        | 0.19%   |
| Sony                                         | 2        | 0.19%   |
| Project                                      | 2        | 0.19%   |
| Microdia                                     | 2        | 0.19%   |
| Micro Star International                     | 2        | 0.19%   |
| GYROCOM C&C                                  | 2        | 0.19%   |
| Generalplus Technology                       | 2        | 0.19%   |
| Creative Technology                          | 2        | 0.19%   |
| Asahi Kasei Microsystems                     | 2        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.09%   |
| ZOOM                                         | 1        | 0.09%   |
| VIA Technologies                             | 1        | 0.09%   |
| Unknown                                      | 1        | 0.09%   |
| Turtle Beach                                 | 1        | 0.09%   |
| Textech International                        | 1        | 0.09%   |
| TerraTec Electronic                          | 1        | 0.09%   |
| Sennheiser Communications                    | 1        | 0.09%   |
| SAVITECH                                     | 1        | 0.09%   |
| Samson Technologies                          | 1        | 0.09%   |
| Realtek Semiconductor                        | 1        | 0.09%   |
| Razer                                        | 1        | 0.09%   |
| Quanta                                       | 1        | 0.09%   |
| Qualcomm                                     | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 68       | 5.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 57       | 4.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 55       | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 39       | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 39       | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 35       | 2.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 34       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31       | 2.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30       | 2.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27       | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 25       | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 1.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 20       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19       | 1.52%   |
| AMD FCH Azalia Controller                                                  | 19       | 1.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18       | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 18       | 1.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18       | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17       | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                              | 16       | 1.28%   |
| Nvidia GM204 High Definition Audio Controller                              | 16       | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16       | 1.28%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15       | 1.2%    |
| AMD Navi 10 HDMI Audio                                                     | 15       | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 14       | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 14       | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13       | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 12       | 0.96%   |
| Nvidia High Definition Audio Controller                                    | 12       | 0.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12       | 0.96%   |
| Nvidia GK104 HDMI Audio Controller                                         | 11       | 0.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 11       | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 10       | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10       | 0.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                         | 9        | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 79       | 21.47%  |
| Kingston            | 72       | 19.57%  |
| G.Skill             | 51       | 13.86%  |
| Crucial             | 51       | 13.86%  |
| Unknown             | 38       | 10.33%  |
| Samsung Electronics | 23       | 6.25%   |
| SK hynix            | 19       | 5.16%   |
| Micron Technology   | 9        | 2.45%   |
| Nanya Technology    | 3        | 0.82%   |
| A-DATA Technology   | 3        | 0.82%   |
| Ramaxel Technology  | 2        | 0.54%   |
| JOY-IT              | 2        | 0.54%   |
| Elpida              | 2        | 0.54%   |
| Avant               | 2        | 0.54%   |
| Unifosa             | 1        | 0.27%   |
| Transcend           | 1        | 0.27%   |
| Toshiba             | 1        | 0.27%   |
| Team                | 1        | 0.27%   |
| TakeMS              | 1        | 0.27%   |
| Qimonda             | 1        | 0.27%   |
| PNY                 | 1        | 0.27%   |
| Mushkin             | 1        | 0.27%   |
| Hitachi             | 1        | 0.27%   |
| Hewlett-Packard     | 1        | 0.27%   |
| GOODRAM             | 1        | 0.27%   |
| Unknown             | 1        | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s     | 12       | 3.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 11       | 2.78%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 9        | 2.27%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 6        | 1.52%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 5        | 1.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 4        | 1.01%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s       | 4        | 1.01%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 4        | 1.01%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 4        | 1.01%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s     | 4        | 1.01%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 3        | 0.76%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s    | 3        | 0.76%   |
| Kingston RAM 9905734-059.A00G 16GB DIMM DDR4 2666MT/s     | 3        | 0.76%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s     | 3        | 0.76%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s      | 3        | 0.76%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s   | 3        | 0.76%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 3        | 0.76%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s       | 3        | 0.76%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s | 3        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2        | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 2        | 0.51%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                      | 2        | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 2        | 0.51%   |
| Unknown RAM Module 1024MB DIMM DDR2 266MT/s               | 2        | 0.51%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s      | 2        | 0.51%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 2        | 0.51%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s       | 2        | 0.51%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 2        | 0.51%   |
| Kingston RAM Module 32GB DIMM DDR4 2400MT/s               | 2        | 0.51%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s      | 2        | 0.51%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s    | 2        | 0.51%   |
| Kingston RAM 99U5471-002.A00LF 2048MB DIMM DDR3 1334MT/s  | 2        | 0.51%   |
| Kingston RAM 9905584-027.A00LF 4GB DIMM 1600MT/s          | 2        | 0.51%   |
| JOY-IT RAM QLA304G08-GGN 4GB DIMM DDR3 1600MT/s           | 2        | 0.51%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 2        | 0.51%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 2        | 0.51%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 2        | 0.51%   |
| G.Skill RAM F3-1600C11-4GNS 4096MB DIMM DDR3 1600MT/s     | 2        | 0.51%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s   | 2        | 0.51%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s     | 2        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 168      | 52.01%  |
| DDR3    | 119      | 36.84%  |
| Unknown | 12       | 3.72%   |
| DDR2    | 11       | 3.41%   |
| SDRAM   | 10       | 3.1%    |
| DDR     | 3        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 304      | 95.9%   |
| SODIMM | 13       | 4.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 143      | 40.06%  |
| 4096  | 84       | 23.53%  |
| 16384 | 68       | 19.05%  |
| 2048  | 38       | 10.64%  |
| 32768 | 10       | 2.8%    |
| 1024  | 8        | 2.24%   |
| 512   | 4        | 1.12%   |
| 256   | 1        | 0.28%   |
| 16    | 1        | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 73       | 20.62%  |
| 3200    | 47       | 13.28%  |
| 1333    | 34       | 9.6%    |
| 3600    | 30       | 8.47%   |
| 2400    | 27       | 7.63%   |
| 2133    | 17       | 4.8%    |
| 3000    | 15       | 4.24%   |
| 2667    | 13       | 3.67%   |
| 1867    | 9        | 2.54%   |
| 3733    | 7        | 1.98%   |
| 3466    | 7        | 1.98%   |
| 2666    | 7        | 1.98%   |
| 667     | 7        | 1.98%   |
| 3400    | 5        | 1.41%   |
| 2933    | 5        | 1.41%   |
| 3866    | 4        | 1.13%   |
| 1866    | 4        | 1.13%   |
| 1334    | 4        | 1.13%   |
| 1066    | 4        | 1.13%   |
| 800     | 4        | 1.13%   |
| 2800    | 3        | 0.85%   |
| Unknown | 3        | 0.85%   |
| 3800    | 2        | 0.56%   |
| 3666    | 2        | 0.56%   |
| 3066    | 2        | 0.56%   |
| 2465    | 2        | 0.56%   |
| 1800    | 2        | 0.56%   |
| 1067    | 2        | 0.56%   |
| 400     | 2        | 0.56%   |
| 266     | 2        | 0.56%   |
| 50664   | 1        | 0.28%   |
| 8400    | 1        | 0.28%   |
| 4000    | 1        | 0.28%   |
| 3334    | 1        | 0.28%   |
| 2733    | 1        | 0.28%   |
| 2472    | 1        | 0.28%   |
| 1648    | 1        | 0.28%   |
| 533     | 1        | 0.28%   |
| 133     | 1        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 9        | 26.47%  |
| Hewlett-Packard       | 8        | 23.53%  |
| Canon                 | 8        | 23.53%  |
| Seiko Epson           | 4        | 11.76%  |
| Samsung Electronics   | 1        | 2.94%   |
| Ricoh                 | 1        | 2.94%   |
| Prolific Technology   | 1        | 2.94%   |
| Oki Data              | 1        | 2.94%   |
| Lexmark International | 1        | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2530 Series                                 | 2        | 5.88%   |
| HP Deskjet 3520 series                                     | 2        | 5.88%   |
| Brother Printer                                            | 2        | 5.88%   |
| Brother HL-3040CN series                                   | 2        | 5.88%   |
| Seiko Epson XP-230 Series                                  | 1        | 2.94%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 2.94%   |
| Samsung C48x Series                                        | 1        | 2.94%   |
| Ricoh SP 212SUw                                            | 1        | 2.94%   |
| Prolific PL2305 Parallel Port                              | 1        | 2.94%   |
| Oki Data USB Device                                        | 1        | 2.94%   |
| Lexmark International CS417dn                              | 1        | 2.94%   |
| HP OfficeJet Pro 7720 series                               | 1        | 2.94%   |
| HP LaserJet 1320                                           | 1        | 2.94%   |
| HP ENVY 5000 series                                        | 1        | 2.94%   |
| HP ENVY 4520 series                                        | 1        | 2.94%   |
| HP DeskJet 940c                                            | 1        | 2.94%   |
| HP Deskjet 2050 J510                                       | 1        | 2.94%   |
| Canon TS5100 series                                        | 1        | 2.94%   |
| Canon PIXMA MX320 series                                   | 1        | 2.94%   |
| Canon MF5650 (FAX)                                         | 1        | 2.94%   |
| Canon LBP2900                                              | 1        | 2.94%   |
| Canon LaserShot LBP-1120 Printer                           | 1        | 2.94%   |
| Canon L100/L150/L170                                       | 1        | 2.94%   |
| Canon iP7200 series                                        | 1        | 2.94%   |
| Canon CanoScan LiDE 300                                    | 1        | 2.94%   |
| Brother MFC-L2710DW series                                 | 1        | 2.94%   |
| Brother MFC-L2710DN series                                 | 1        | 2.94%   |
| Brother MFC-9142CDN                                        | 1        | 2.94%   |
| Brother DCP-J140W                                          | 1        | 2.94%   |
| Brother DCP-1510                                           | 1        | 2.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 18       | 72%     |
| Seiko Epson     | 3        | 12%     |
| Fujitsu         | 3        | 12%     |
| Hewlett-Packard | 1        | 4%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Fujitsu ScanSnap SV600                                   | 3        | 12%     |
| Canon CanoScan                                           | 3        | 12%     |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2        | 8%      |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 8%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2        | 8%      |
| Canon CanoScan LiDE 220                                  | 2        | 8%      |
| Canon CanoScan LiDE 110                                  | 2        | 8%      |
| Canon CanoScan LiDE 100                                  | 2        | 8%      |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1        | 4%      |
| HP ScanJet 4850C/4890C                                   | 1        | 4%      |
| Canon CanoScan N650U/N656U                               | 1        | 4%      |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 4%      |
| Canon CanoScan LiDE 60                                   | 1        | 4%      |
| Canon CanoScan LiDE 210                                  | 1        | 4%      |
| Canon CanoScan FB630U                                    | 1        | 4%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 41       | 39.81%  |
| Microsoft                     | 10       | 9.71%   |
| Microdia                      | 8        | 7.77%   |
| Realtek Semiconductor         | 7        | 6.8%    |
| Sunplus Innovation Technology | 5        | 4.85%   |
| ARC International             | 4        | 3.88%   |
| Apple                         | 4        | 3.88%   |
| Z-Star Microelectronics       | 3        | 2.91%   |
| Samsung Electronics           | 3        | 2.91%   |
| Fujitsu                       | 3        | 2.91%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 1.94%   |
| Unknown                       | 1        | 0.97%   |
| Tobii Technology AB           | 1        | 0.97%   |
| SJ-180517-N                   | 1        | 0.97%   |
| Quanta                        | 1        | 0.97%   |
| Novatek Microelectronics      | 1        | 0.97%   |
| Nikon                         | 1        | 0.97%   |
| KYE Systems (Mouse Systems)   | 1        | 0.97%   |
| Jieli Technology              | 1        | 0.97%   |
| Generalplus Technology        | 1        | 0.97%   |
| GEMBIRD                       | 1        | 0.97%   |
| Etron Technology              | 1        | 0.97%   |
| Creative Technology           | 1        | 0.97%   |
| Arkmicro Technologies         | 1        | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 8        | 7.69%   |
| Realtek Full HD webcam                         | 6        | 5.77%   |
| Microsoft LifeCam HD-3000                      | 6        | 5.77%   |
| Logitech HD Pro Webcam C920                    | 6        | 5.77%   |
| Microdia Webcam Vitade AF                      | 5        | 4.81%   |
| Logitech HD Webcam C525                        | 5        | 4.81%   |
| ARC International Camera                       | 4        | 3.85%   |
| Samsung Galaxy A5 (MTP)                        | 3        | 2.88%   |
| Logitech Webcam C170                           | 3        | 2.88%   |
| Logitech QuickCam Pro for Notebooks            | 3        | 2.88%   |
| Logitech QuickCam Pro 9000                     | 3        | 2.88%   |
| Fujitsu USB Camera                             | 3        | 2.88%   |
| Z-Star Venus USB2.0 Camera                     | 2        | 1.92%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 1.92%   |
| Microsoft LifeCam VX-500 [1357]                | 2        | 1.92%   |
| Microdia Sonix USB 2.0 Camera                  | 2        | 1.92%   |
| Logitech HD Webcam C510                        | 2        | 1.92%   |
| Logitech C922 Pro Stream Webcam                | 2        | 1.92%   |
| Apple iPhone5/5C/5S/6                          | 2        | 1.92%   |
| Z-Star Integrated Camera                       | 1        | 0.96%   |
| Unknown Konftel Cam20                          | 1        | 0.96%   |
| Tobii AB EyeChip                               | 1        | 0.96%   |
| Sunplus SPCA2650 AV Camera                     | 1        | 0.96%   |
| Sunplus SPCA2281 Web Camera                    | 1        | 0.96%   |
| Sunplus HD 720P webcam                         | 1        | 0.96%   |
| Sunplus Full HD webcam                         | 1        | 0.96%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 0.96%   |
| SJ-180517-N 1080P Webcam                       | 1        | 0.96%   |
| Realtek NexiGo N660P FHD Webcam                | 1        | 0.96%   |
| Quanta HD Camera                               | 1        | 0.96%   |
| Novatek J1455                                  | 1        | 0.96%   |
| Nikon DSC D90                                  | 1        | 0.96%   |
| Microsoft MicrosoftÂ LifeCam VX-5500          | 1        | 0.96%   |
| Microsoft LifeCam Cinema                       | 1        | 0.96%   |
| Microdia USB 2.0 Camera                        | 1        | 0.96%   |
| Logitech Webcam Pro 9000                       | 1        | 0.96%   |
| Logitech Webcam C925e                          | 1        | 0.96%   |
| Logitech Webcam C310                           | 1        | 0.96%   |
| Logitech Webcam C300                           | 1        | 0.96%   |
| Logitech Webcam B500                           | 1        | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 25%     |
| Lenovo                | 1        | 25%     |
| Cherry                | 1        | 25%     |
| Alcor Micro           | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 25%     |
| Lenovo Smartcard Keyboard                         | 1        | 25%     |
| Cherry Smart Terminal XX44                        | 1        | 25%     |
| Alcor Micro Watchdata W 1981                      | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 522      | 85.57%  |
| 1     | 71       | 11.64%  |
| 2     | 13       | 2.13%   |
| 5     | 2        | 0.33%   |
| 6     | 1        | 0.16%   |
| 4     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 31.13%  |
| Net/wireless             | 25       | 23.58%  |
| Unassigned class         | 10       | 9.43%   |
| Communication controller | 8        | 7.55%   |
| Multimedia controller    | 5        | 4.72%   |
| Sound                    | 4        | 3.77%   |
| Net/ethernet             | 3        | 2.83%   |
| Camera                   | 3        | 2.83%   |
| Bluetooth                | 3        | 2.83%   |
| Tv card                  | 2        | 1.89%   |
| Fingerprint reader       | 2        | 1.89%   |
| Chipcard                 | 2        | 1.89%   |
| Storage/raid             | 1        | 0.94%   |
| Storage/ide              | 1        | 0.94%   |
| Storage/ata              | 1        | 0.94%   |
| Network                  | 1        | 0.94%   |
| Modem                    | 1        | 0.94%   |
| Card reader              | 1        | 0.94%   |

