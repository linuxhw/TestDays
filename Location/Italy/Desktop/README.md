Linux in Italy - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 3550

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [b792043acd](https://linux-hardware.org/?probe=b792043acd) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [48bccd4f38](https://linux-hardware.org/?probe=48bccd4f38) | Feb 01, 2023 |
| Pegatron      | 2A94                        | [58961a542f](https://linux-hardware.org/?probe=58961a542f) | Feb 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3bdb934f29](https://linux-hardware.org/?probe=3bdb934f29) | Jan 30, 2023 |
| Intel         | B75                         | [6597bed6da](https://linux-hardware.org/?probe=6597bed6da) | Jan 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| MSI           | P55-CD53                    | [7c46f17179](https://linux-hardware.org/?probe=7c46f17179) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| ASUSTek       | F2A55-M LK2                 | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| Dell          | 0HD5W2 A00                  | [890cad48c3](https://linux-hardware.org/?probe=890cad48c3) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | [8f6ea9ffff](https://linux-hardware.org/?probe=8f6ea9ffff) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [6f449734a9](https://linux-hardware.org/?probe=6f449734a9) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | [edb16eafc7](https://linux-hardware.org/?probe=edb16eafc7) | Jan 25, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [3e1520340a](https://linux-hardware.org/?probe=3e1520340a) | Jan 25, 2023 |
| MSI           | Boston                      | [456d7782ad](https://linux-hardware.org/?probe=456d7782ad) | Jan 24, 2023 |
| MSI           | P55-CD53                    | [7c3a675f94](https://linux-hardware.org/?probe=7c3a675f94) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| Packard Be... | EG43M                       | [92810508a2](https://linux-hardware.org/?probe=92810508a2) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| HP            | 8433 11                     | [a5c598c4c5](https://linux-hardware.org/?probe=a5c598c4c5) | Jan 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [b919144e1c](https://linux-hardware.org/?probe=b919144e1c) | Jan 22, 2023 |
| ASRock        | G31M-S                      | [dbf8922f3a](https://linux-hardware.org/?probe=dbf8922f3a) | Jan 22, 2023 |
| MSI           | Boston                      | [34413408ce](https://linux-hardware.org/?probe=34413408ce) | Jan 22, 2023 |
| Dell          | 0YXT71 A02                  | [5d3b4c4823](https://linux-hardware.org/?probe=5d3b4c4823) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [0aa5260ed0](https://linux-hardware.org/?probe=0aa5260ed0) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [7389389089](https://linux-hardware.org/?probe=7389389089) | Jan 22, 2023 |
| ASRock        | X370 Pro4                   | [6a8cc962ad](https://linux-hardware.org/?probe=6a8cc962ad) | Jan 22, 2023 |
| ASRock        | B365 Pro4                   | [44fa1b3713](https://linux-hardware.org/?probe=44fa1b3713) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| HP            | 1497                        | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [9229e3b2ae](https://linux-hardware.org/?probe=9229e3b2ae) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [62dc562b9e](https://linux-hardware.org/?probe=62dc562b9e) | Jan 21, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [eb57bb7cd7](https://linux-hardware.org/?probe=eb57bb7cd7) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [2e73bc84e7](https://linux-hardware.org/?probe=2e73bc84e7) | Jan 20, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2e54ccac4d](https://linux-hardware.org/?probe=2e54ccac4d) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [763f4cb45f](https://linux-hardware.org/?probe=763f4cb45f) | Jan 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [dcf9186db1](https://linux-hardware.org/?probe=dcf9186db1) | Jan 18, 2023 |
| ASRock        | G31M-S                      | [d3aa4e7eea](https://linux-hardware.org/?probe=d3aa4e7eea) | Jan 18, 2023 |
| MSI           | Z170A GAMING M7             | [d58a30b560](https://linux-hardware.org/?probe=d58a30b560) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [4e8759fda2](https://linux-hardware.org/?probe=4e8759fda2) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [d1310959ea](https://linux-hardware.org/?probe=d1310959ea) | Jan 17, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [52c1a6c197](https://linux-hardware.org/?probe=52c1a6c197) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b9f958e5c4](https://linux-hardware.org/?probe=b9f958e5c4) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| Unknown       | T3 MRD                      | [df73fafeb7](https://linux-hardware.org/?probe=df73fafeb7) | Jan 17, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [4d4b18a5b3](https://linux-hardware.org/?probe=4d4b18a5b3) | Jan 16, 2023 |
| ASUSTek       | PRIME B460M-A               | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [1dd0101330](https://linux-hardware.org/?probe=1dd0101330) | Jan 16, 2023 |
| Dell          | 0WMJ54 A01                  | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Gigabyte      | Z97X-Gaming G1              | [58c875e5d5](https://linux-hardware.org/?probe=58c875e5d5) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [084cfebfdb](https://linux-hardware.org/?probe=084cfebfdb) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [f8c56a73c0](https://linux-hardware.org/?probe=f8c56a73c0) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [7b8818c038](https://linux-hardware.org/?probe=7b8818c038) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [74dfb9a261](https://linux-hardware.org/?probe=74dfb9a261) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Dell          | 0D24M8 A01                  | [d4cc07d2d2](https://linux-hardware.org/?probe=d4cc07d2d2) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [05f1e26e96](https://linux-hardware.org/?probe=05f1e26e96) | Jan 13, 2023 |
| Dell          | 0WG261                      | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [a86e03551c](https://linux-hardware.org/?probe=a86e03551c) | Jan 13, 2023 |
| Dell          | 0WG261                      | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [64808b5735](https://linux-hardware.org/?probe=64808b5735) | Jan 12, 2023 |
| Pegatron      | 2ACF                        | [611b2fb2a3](https://linux-hardware.org/?probe=611b2fb2a3) | Jan 12, 2023 |
| AOpen         | D1007 0BBA                  | [63a1413fa3](https://linux-hardware.org/?probe=63a1413fa3) | Jan 12, 2023 |
| Gigabyte      | Z790 AERO G                 | [0d6b77da1a](https://linux-hardware.org/?probe=0d6b77da1a) | Jan 11, 2023 |
| ASUSTek       | PRIME B360M-A               | [75584dc48c](https://linux-hardware.org/?probe=75584dc48c) | Jan 11, 2023 |
| Acer          | Veriton X2640G V:1.0        | [0daf81fe54](https://linux-hardware.org/?probe=0daf81fe54) | Jan 11, 2023 |
| HP            | 8767 A                      | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | BT6130                      | [53c9ec0145](https://linux-hardware.org/?probe=53c9ec0145) | Jan 10, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [71f6d7912a](https://linux-hardware.org/?probe=71f6d7912a) | Jan 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [0d0a198245](https://linux-hardware.org/?probe=0d0a198245) | Jan 10, 2023 |
| ASRockRack    | EPC602D8A                   | [2d1d53f993](https://linux-hardware.org/?probe=2d1d53f993) | Jan 10, 2023 |
| MSI           | B450M MORTAR MAX            | [36530dbc41](https://linux-hardware.org/?probe=36530dbc41) | Jan 10, 2023 |
| MSI           | H310M PRO-D                 | [1ba0a170aa](https://linux-hardware.org/?probe=1ba0a170aa) | Jan 09, 2023 |
| MSI           | MS-7378                     | [965cd11e84](https://linux-hardware.org/?probe=965cd11e84) | Jan 09, 2023 |
| MSI           | Z77A-GD65                   | [f4b0c86cfa](https://linux-hardware.org/?probe=f4b0c86cfa) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR            | [1549344aef](https://linux-hardware.org/?probe=1549344aef) | Jan 09, 2023 |
| ASRock        | H87 Performance             | [8e1b7a9033](https://linux-hardware.org/?probe=8e1b7a9033) | Jan 09, 2023 |
| MSI           | H310M PRO-D                 | [e5a8783118](https://linux-hardware.org/?probe=e5a8783118) | Jan 09, 2023 |
| ASRock        | 980DE3/U3S3                 | [92d7b143d8](https://linux-hardware.org/?probe=92d7b143d8) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ca7597c4fb](https://linux-hardware.org/?probe=ca7597c4fb) | Jan 08, 2023 |
| Gigabyte      | 990XA-UD3                   | [1c85ed2f4b](https://linux-hardware.org/?probe=1c85ed2f4b) | Jan 08, 2023 |
| Gigabyte      | A520M S2H                   | [a303af0bcf](https://linux-hardware.org/?probe=a303af0bcf) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| Acer          | Veriton N2620G              | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| HP            | 8399                        | [eccd5189f5](https://linux-hardware.org/?probe=eccd5189f5) | Jan 07, 2023 |
| HP            | 89D8 SMVB                   | [dac20769fc](https://linux-hardware.org/?probe=dac20769fc) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| Intel         | DH61DL AAG14066-205         | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Gigabyte      | B560M DS3H                  | [667c8405f0](https://linux-hardware.org/?probe=667c8405f0) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Intel         | B75                         | [bb046d2540](https://linux-hardware.org/?probe=bb046d2540) | Jan 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e9393e884](https://linux-hardware.org/?probe=0e9393e884) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [31dfc11401](https://linux-hardware.org/?probe=31dfc11401) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [1497921a99](https://linux-hardware.org/?probe=1497921a99) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASRock        | H77M                        | [b7f415926b](https://linux-hardware.org/?probe=b7f415926b) | Jan 03, 2023 |
| ASRock        | H77M                        | [82c399688f](https://linux-hardware.org/?probe=82c399688f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [008e5d125e](https://linux-hardware.org/?probe=008e5d125e) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [0d47a13713](https://linux-hardware.org/?probe=0d47a13713) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [25466113c1](https://linux-hardware.org/?probe=25466113c1) | Jan 02, 2023 |
| MSI           | H310M PRO-D                 | [27482bbe30](https://linux-hardware.org/?probe=27482bbe30) | Jan 02, 2023 |
| Dell          | 0RF703                      | [66180b5fdf](https://linux-hardware.org/?probe=66180b5fdf) | Jan 02, 2023 |
| MSI           | B250M PRO-VD                | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| ASRock        | B450 Steel Legend           | [b953257b12](https://linux-hardware.org/?probe=b953257b12) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Intel         | DH61DL AAG14066-205         | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| HP            | 82B4                        | [4e2d86906f](https://linux-hardware.org/?probe=4e2d86906f) | Jan 01, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [afdda0ad31](https://linux-hardware.org/?probe=afdda0ad31) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3659d7377d](https://linux-hardware.org/?probe=3659d7377d) | Dec 31, 2022 |
| BESSTAR Te... | C-J34 Pro                   | [1b54a52c3c](https://linux-hardware.org/?probe=1b54a52c3c) | Dec 30, 2022 |
| ASUSTek       | H81M-A                      | [10f0b28589](https://linux-hardware.org/?probe=10f0b28589) | Dec 29, 2022 |
| HP            | 0AE8h                       | [b23a6da065](https://linux-hardware.org/?probe=b23a6da065) | Dec 29, 2022 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| HP            | 8399                        | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [d0969c6a4c](https://linux-hardware.org/?probe=d0969c6a4c) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [8a4dce4662](https://linux-hardware.org/?probe=8a4dce4662) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6297565fda](https://linux-hardware.org/?probe=6297565fda) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASRock        | 4CoreDual-SATA2             | [05ae1afd3f](https://linux-hardware.org/?probe=05ae1afd3f) | Dec 28, 2022 |
| HP            | 0AE8h                       | [c1bd1ff073](https://linux-hardware.org/?probe=c1bd1ff073) | Dec 27, 2022 |
| Unknown       | Unknown                     | [ccce0caf7e](https://linux-hardware.org/?probe=ccce0caf7e) | Dec 27, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0PTTT9 A01                  | [78512365ca](https://linux-hardware.org/?probe=78512365ca) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [b2acfa6e70](https://linux-hardware.org/?probe=b2acfa6e70) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [59e6ec4132](https://linux-hardware.org/?probe=59e6ec4132) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| MSI           | Boston                      | [5ffbd4e9a5](https://linux-hardware.org/?probe=5ffbd4e9a5) | Dec 25, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [384d09ccdb](https://linux-hardware.org/?probe=384d09ccdb) | Dec 25, 2022 |
| Dell          | 0DN075                      | [9fd08be389](https://linux-hardware.org/?probe=9fd08be389) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| AMI           | Cherry Trail FFD            | [7070bf387d](https://linux-hardware.org/?probe=7070bf387d) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| Foxconn       | 2AA9                        | [07650be639](https://linux-hardware.org/?probe=07650be639) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| ASUSTek       | M5A78L/USB3                 | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [568df9daf7](https://linux-hardware.org/?probe=568df9daf7) | Dec 23, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [9e19c2db67](https://linux-hardware.org/?probe=9e19c2db67) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [ec808658f8](https://linux-hardware.org/?probe=ec808658f8) | Dec 22, 2022 |
| Acer          | Aspire M3920                | [803cd5d8f9](https://linux-hardware.org/?probe=803cd5d8f9) | Dec 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [fc162d4cb2](https://linux-hardware.org/?probe=fc162d4cb2) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [1cdb02c6db](https://linux-hardware.org/?probe=1cdb02c6db) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | [c7b2f48d96](https://linux-hardware.org/?probe=c7b2f48d96) | Dec 20, 2022 |
| ASUSTek       | PRIME A320M-K               | [3b38fc673c](https://linux-hardware.org/?probe=3b38fc673c) | Dec 19, 2022 |
| Gigabyte      | 970-GAMING                  | [cf93a75cf0](https://linux-hardware.org/?probe=cf93a75cf0) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| Gigabyte      | B75M-D3H                    | [ad506ad64e](https://linux-hardware.org/?probe=ad506ad64e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [831f650b05](https://linux-hardware.org/?probe=831f650b05) | Dec 19, 2022 |
| HP            | 18E7                        | [9f601a9f1a](https://linux-hardware.org/?probe=9f601a9f1a) | Dec 19, 2022 |
| MSI           | B250M PRO-VDH               | [14ea50f3b2](https://linux-hardware.org/?probe=14ea50f3b2) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Intel         | H55                         | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| ASUSTek       | P7H55D-M EVO                | [1e294ecd38](https://linux-hardware.org/?probe=1e294ecd38) | Dec 18, 2022 |
| ASUSTek       | F1A55-M LE                  | [c2db38b403](https://linux-hardware.org/?probe=c2db38b403) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| MSI           | MS-B1711                    | [a5b142e258](https://linux-hardware.org/?probe=a5b142e258) | Dec 17, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [25ba267a65](https://linux-hardware.org/?probe=25ba267a65) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [14d39a67c2](https://linux-hardware.org/?probe=14d39a67c2) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [fc99e84afd](https://linux-hardware.org/?probe=fc99e84afd) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| HP            | 843C                        | [e647aa1207](https://linux-hardware.org/?probe=e647aa1207) | Dec 14, 2022 |
| HP            | 2AF7                        | [089612dee6](https://linux-hardware.org/?probe=089612dee6) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| HP            | 2AF7                        | [2c6c08c8b8](https://linux-hardware.org/?probe=2c6c08c8b8) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Foxconn       | 2ABF                        | [48f3c01650](https://linux-hardware.org/?probe=48f3c01650) | Dec 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9a73e431ee](https://linux-hardware.org/?probe=9a73e431ee) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [2212bad256](https://linux-hardware.org/?probe=2212bad256) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [20cb7a525a](https://linux-hardware.org/?probe=20cb7a525a) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| MSI           | Boston                      | [4cc25e826f](https://linux-hardware.org/?probe=4cc25e826f) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [746c717d34](https://linux-hardware.org/?probe=746c717d34) | Dec 10, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [768329e263](https://linux-hardware.org/?probe=768329e263) | Dec 07, 2022 |
| ASRock        | Z170 Extreme7+              | [15f86800ee](https://linux-hardware.org/?probe=15f86800ee) | Dec 07, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9d8dee4e41](https://linux-hardware.org/?probe=9d8dee4e41) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASRock        | A320M-DGS                   | [fd3597e4bf](https://linux-hardware.org/?probe=fd3597e4bf) | Dec 06, 2022 |
| HP            | 843C                        | [278cbd2708](https://linux-hardware.org/?probe=278cbd2708) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| HP            | 0A64h                       | [58658d8b61](https://linux-hardware.org/?probe=58658d8b61) | Dec 06, 2022 |
| MSI           | MS-B1711                    | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| MSI           | Boston                      | [fd25ac3a2e](https://linux-hardware.org/?probe=fd25ac3a2e) | Dec 05, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [d0230b5c69](https://linux-hardware.org/?probe=d0230b5c69) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [84bc78ebb6](https://linux-hardware.org/?probe=84bc78ebb6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| Pegatron      | 2ACF                        | [f2d1d7fb3d](https://linux-hardware.org/?probe=f2d1d7fb3d) | Dec 03, 2022 |
| MSI           | X99S SLI PLUS               | [03a2e66a94](https://linux-hardware.org/?probe=03a2e66a94) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d42d3210f](https://linux-hardware.org/?probe=7d42d3210f) | Dec 03, 2022 |
| HP            | 2B52                        | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Gigabyte      | B75M-D2V                    | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| MSI           | Z170A GAMING M3             | [e4fd5dfa0e](https://linux-hardware.org/?probe=e4fd5dfa0e) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| MSI           | Boston                      | [0564f7ed2d](https://linux-hardware.org/?probe=0564f7ed2d) | Nov 30, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| MSI           | Z170A GAMING M3             | [dfe92c80c1](https://linux-hardware.org/?probe=dfe92c80c1) | Nov 30, 2022 |
| IBM           | MSI-9151 Boards             | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [719921de81](https://linux-hardware.org/?probe=719921de81) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [f998b6a0d9](https://linux-hardware.org/?probe=f998b6a0d9) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [d5702f8b2d](https://linux-hardware.org/?probe=d5702f8b2d) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [640a031786](https://linux-hardware.org/?probe=640a031786) | Nov 29, 2022 |
| HP            | 843B                        | [19bd35484c](https://linux-hardware.org/?probe=19bd35484c) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Dell          | 042P49 A01                  | [8f510e55e2](https://linux-hardware.org/?probe=8f510e55e2) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Gigabyte      | F2A78M-HD2                  | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 3397                        | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [30081f61ca](https://linux-hardware.org/?probe=30081f61ca) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [9e33d3b8f1](https://linux-hardware.org/?probe=9e33d3b8f1) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [14c0f082d8](https://linux-hardware.org/?probe=14c0f082d8) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [d0bd92a5e0](https://linux-hardware.org/?probe=d0bd92a5e0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [b4cc2dc00b](https://linux-hardware.org/?probe=b4cc2dc00b) | Nov 22, 2022 |
| HP            | 83E2                        | [b04e1014da](https://linux-hardware.org/?probe=b04e1014da) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| HP            | 2AF3                        | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [07ca09898f](https://linux-hardware.org/?probe=07ca09898f) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [835c000337](https://linux-hardware.org/?probe=835c000337) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| Lenovo        | 31900058 STD                | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Acer          | E946GZ                      | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| Mediacom      | M-AO241/64                  | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| ASRock        | J3455B-ITX                  | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| HP            | 802F                        | [8e7dbc3f9f](https://linux-hardware.org/?probe=8e7dbc3f9f) | Nov 14, 2022 |
| HP            | 802F                        | [89441a53f7](https://linux-hardware.org/?probe=89441a53f7) | Nov 14, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [c3573fb12b](https://linux-hardware.org/?probe=c3573fb12b) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| HP            | 3397                        | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [7d72f2fa26](https://linux-hardware.org/?probe=7d72f2fa26) | Nov 12, 2022 |
| MSI           | MS-7309                     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3                    | [7c25342680](https://linux-hardware.org/?probe=7c25342680) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| ASUSTek       | P5L1394                     | [d4c699bf10](https://linux-hardware.org/?probe=d4c699bf10) | Nov 11, 2022 |
| Unknown       | 1.0                         | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4fddb7605a](https://linux-hardware.org/?probe=4fddb7605a) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [779188af6a](https://linux-hardware.org/?probe=779188af6a) | Nov 11, 2022 |
| Intel         | DQ57TM AAE70931-403         | [1759cf3bec](https://linux-hardware.org/?probe=1759cf3bec) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| ASRock        | B365 Pro4                   | [3069280223](https://linux-hardware.org/?probe=3069280223) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| ASUSTek       | P5KPL-SE                    | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASRock        | X370 Gaming K4              | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [92cf5ed7b4](https://linux-hardware.org/?probe=92cf5ed7b4) | Nov 07, 2022 |
| Dell          | 0X231R A01                  | [5846e23f06](https://linux-hardware.org/?probe=5846e23f06) | Nov 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| ASRock        | B365 Pro4                   | [6c37cfce25](https://linux-hardware.org/?probe=6c37cfce25) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| ASRock        | B450M Pro4                  | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| AMI           | Cherry Trail CR             | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [1534af11b9](https://linux-hardware.org/?probe=1534af11b9) | Nov 05, 2022 |
| HP            | 8053                        | [20c566d4e7](https://linux-hardware.org/?probe=20c566d4e7) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6494c493cb](https://linux-hardware.org/?probe=6494c493cb) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| Dell          | 0W5363                      | [20c6f0d689](https://linux-hardware.org/?probe=20c6f0d689) | Nov 03, 2022 |
| Dell          | 0W5363                      | [7400a9beb1](https://linux-hardware.org/?probe=7400a9beb1) | Nov 03, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [e4206174ca](https://linux-hardware.org/?probe=e4206174ca) | Nov 03, 2022 |
| ASUSTek       | H81T                        | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | B85-PLUS                    | [dd24c26ffa](https://linux-hardware.org/?probe=dd24c26ffa) | Nov 02, 2022 |
| Dell          | 0GWHMW A01                  | [732eaeede7](https://linux-hardware.org/?probe=732eaeede7) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [8f2b0bc926](https://linux-hardware.org/?probe=8f2b0bc926) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [a14fa00a56](https://linux-hardware.org/?probe=a14fa00a56) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [bfa1db2eb1](https://linux-hardware.org/?probe=bfa1db2eb1) | Nov 01, 2022 |
| ASUSTek       | H61M-K                      | [ca5a47c66a](https://linux-hardware.org/?probe=ca5a47c66a) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [d39c952932](https://linux-hardware.org/?probe=d39c952932) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| ASUSTek       | CG8480                      | [0f7c1dc1cf](https://linux-hardware.org/?probe=0f7c1dc1cf) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| MSI           | 990FXA-GD80                 | [baaa1111ec](https://linux-hardware.org/?probe=baaa1111ec) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [08cf9e2ccd](https://linux-hardware.org/?probe=08cf9e2ccd) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [e28a25b18a](https://linux-hardware.org/?probe=e28a25b18a) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| HP            | 1495                        | [b62f9d83b9](https://linux-hardware.org/?probe=b62f9d83b9) | Oct 30, 2022 |
| MSI           | A320M-A PRO MAX             | [80d6d99bcf](https://linux-hardware.org/?probe=80d6d99bcf) | Oct 30, 2022 |
| HP            | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [6549416d9d](https://linux-hardware.org/?probe=6549416d9d) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASRock        | 890GX Extreme3              | [ff1af2eaf0](https://linux-hardware.org/?probe=ff1af2eaf0) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [95af9b0439](https://linux-hardware.org/?probe=95af9b0439) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| Acer          | MCP7A                       | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| Unknown       | 775V88+                     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| MSI           | H81M-P33                    | [16a78334cd](https://linux-hardware.org/?probe=16a78334cd) | Oct 28, 2022 |
| MSI           | Z370 KRAIT GAMING           | [cbf597cec1](https://linux-hardware.org/?probe=cbf597cec1) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1759cbebe1](https://linux-hardware.org/?probe=1759cbebe1) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Packard Be... | IMEDIA S3810                | [f492fb9369](https://linux-hardware.org/?probe=f492fb9369) | Oct 27, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | X58 Pro                     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| HP            | 1589                        | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Intel         | H55                         | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [06f33f301b](https://linux-hardware.org/?probe=06f33f301b) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| ASRock        | H77 Pro4/MVP                | [94d8bc13bb](https://linux-hardware.org/?probe=94d8bc13bb) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| HP            | 1494                        | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| HP            | 8509                        | [81bfb5a782](https://linux-hardware.org/?probe=81bfb5a782) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [50c68d9bb4](https://linux-hardware.org/?probe=50c68d9bb4) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | H110M-K                     | [06c00dc8d5](https://linux-hardware.org/?probe=06c00dc8d5) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASRock        | AB350 Pro4                  | [82ee095168](https://linux-hardware.org/?probe=82ee095168) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| MSI           | Z170A GAMING M5             | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Pegatron      | Benicia                     | [3735dca311](https://linux-hardware.org/?probe=3735dca311) | Oct 25, 2022 |
| HP            | 805F                        | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [ab5d5a6170](https://linux-hardware.org/?probe=ab5d5a6170) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [7b59865f68](https://linux-hardware.org/?probe=7b59865f68) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | Z97-G55 SLI                 | [25ddd5274f](https://linux-hardware.org/?probe=25ddd5274f) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [74ca211759](https://linux-hardware.org/?probe=74ca211759) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock        | B450 Gaming K4              | [122a54b0c2](https://linux-hardware.org/?probe=122a54b0c2) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a0e0f661af](https://linux-hardware.org/?probe=a0e0f661af) | Oct 24, 2022 |
| ASRock        | H370M-ITX/ac                | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| MSI           | H510M-A PRO                 | [02e8dbe21d](https://linux-hardware.org/?probe=02e8dbe21d) | Oct 24, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [e5264df501](https://linux-hardware.org/?probe=e5264df501) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [b63ff47508](https://linux-hardware.org/?probe=b63ff47508) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | H170 PRO GAMING             | [905f41afd6](https://linux-hardware.org/?probe=905f41afd6) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1dea808353](https://linux-hardware.org/?probe=1dea808353) | Oct 24, 2022 |
| Gigabyte      | B85M-D3H                    | [f4182ec2e9](https://linux-hardware.org/?probe=f4182ec2e9) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | PRIME B450M-A               | [fb3feaef06](https://linux-hardware.org/?probe=fb3feaef06) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [164b8dd0d8](https://linux-hardware.org/?probe=164b8dd0d8) | Oct 24, 2022 |
| Dell          | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | 0RW199                      | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| MSI           | Z390-A PRO                  | [40f916420e](https://linux-hardware.org/?probe=40f916420e) | Oct 23, 2022 |
| HP            | 3397                        | [6f58590d3d](https://linux-hardware.org/?probe=6f58590d3d) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| Dell          | 0WR7PY A02                  | [07fb028e18](https://linux-hardware.org/?probe=07fb028e18) | Oct 22, 2022 |
| MSI           | X58 Pro                     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| MSI           | PRO Z690-A                  | [9ea661d3b9](https://linux-hardware.org/?probe=9ea661d3b9) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| ASUSTek       | H110M-A                     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| HP            | 87D6 SMVB                   | [86740d9460](https://linux-hardware.org/?probe=86740d9460) | Oct 21, 2022 |
| ASUSTek       | P7P55-M                     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| ASUSTek       | Leonite2                    | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e455bef105](https://linux-hardware.org/?probe=e455bef105) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| Dell          | 0C522T A03                  | [20703ba8b3](https://linux-hardware.org/?probe=20703ba8b3) | Oct 18, 2022 |
| HP            | 3048h                       | [624ad8a33c](https://linux-hardware.org/?probe=624ad8a33c) | Oct 17, 2022 |
| HP            | 3048h                       | [1b3d31f720](https://linux-hardware.org/?probe=1b3d31f720) | Oct 17, 2022 |
| MSI           | MS-B1711                    | [231d1c3373](https://linux-hardware.org/?probe=231d1c3373) | Oct 16, 2022 |
| MSI           | MS-B1711                    | [964bad6988](https://linux-hardware.org/?probe=964bad6988) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Packard Be... | IMEDIA S3712                | [d9aa81c4c3](https://linux-hardware.org/?probe=d9aa81c4c3) | Oct 15, 2022 |
| ASUSTek       | H87M-PRO                    | [4f1304fbdd](https://linux-hardware.org/?probe=4f1304fbdd) | Oct 15, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b1eab51bd7](https://linux-hardware.org/?probe=b1eab51bd7) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Intel         | STK2MV64CC H89290-502       | [85670dc1fe](https://linux-hardware.org/?probe=85670dc1fe) | Oct 14, 2022 |
| Supermicro    | C7P67                       | [70613229ac](https://linux-hardware.org/?probe=70613229ac) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [c8ee640a4d](https://linux-hardware.org/?probe=c8ee640a4d) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| ASRock        | H77M                        | [4ce05e4d0a](https://linux-hardware.org/?probe=4ce05e4d0a) | Oct 07, 2022 |
| Packard Be... | IMEDIA S3712                | [a528de7c22](https://linux-hardware.org/?probe=a528de7c22) | Oct 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| HP            | 1906                        | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASUSTek       | P8Z68-V LX                  | [42b887e821](https://linux-hardware.org/?probe=42b887e821) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| AZW           | Gemini X45                  | [721b4545a2](https://linux-hardware.org/?probe=721b4545a2) | Oct 02, 2022 |
| Packard Be... | IMEDIA S3712                | [1fd820d1d0](https://linux-hardware.org/?probe=1fd820d1d0) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| Dell          | 0YXT71 A02                  | [f36bc1d24e](https://linux-hardware.org/?probe=f36bc1d24e) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| Gigabyte      | F2A55M-DS2                  | [c17c689217](https://linux-hardware.org/?probe=c17c689217) | Sep 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [960c35d712](https://linux-hardware.org/?probe=960c35d712) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [bb57b80866](https://linux-hardware.org/?probe=bb57b80866) | Sep 27, 2022 |
| HP            | 8433 11                     | [a1d424bced](https://linux-hardware.org/?probe=a1d424bced) | Sep 27, 2022 |
| ASRock        | AB350 Gaming K4             | [184070d232](https://linux-hardware.org/?probe=184070d232) | Sep 26, 2022 |
| ASRock        | 775Dual-VSTA                | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | H81M-K                      | [badc988393](https://linux-hardware.org/?probe=badc988393) | Sep 26, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [4ed673ff1a](https://linux-hardware.org/?probe=4ed673ff1a) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| ASUSTek       | P8H61-M LX                  | [164f5bfea2](https://linux-hardware.org/?probe=164f5bfea2) | Sep 25, 2022 |
| HP            | 8433 11                     | [dffc61c155](https://linux-hardware.org/?probe=dffc61c155) | Sep 24, 2022 |
| ASRock        | 4CoreDual-SATA2             | [eb0e992df7](https://linux-hardware.org/?probe=eb0e992df7) | Sep 24, 2022 |
| ASUSTek       | P8B75-M LE                  | [8975676700](https://linux-hardware.org/?probe=8975676700) | Sep 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fd43d92335](https://linux-hardware.org/?probe=fd43d92335) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [0c6cbcc99d](https://linux-hardware.org/?probe=0c6cbcc99d) | Sep 22, 2022 |
| ASUSTek       | M3N78-VM                    | [edaab96cde](https://linux-hardware.org/?probe=edaab96cde) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 0GM819                      | [951ce34bb2](https://linux-hardware.org/?probe=951ce34bb2) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| Intel         | H55                         | [6de435d14c](https://linux-hardware.org/?probe=6de435d14c) | Sep 20, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9c483616f6](https://linux-hardware.org/?probe=9c483616f6) | Sep 20, 2022 |
| Acer          | Aspire M3970                | [d135989361](https://linux-hardware.org/?probe=d135989361) | Sep 19, 2022 |
| Supermicro    | C7P67                       | [16bff71d62](https://linux-hardware.org/?probe=16bff71d62) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [2432fca2f8](https://linux-hardware.org/?probe=2432fca2f8) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| MSI           | Boston                      | [b884bd8c03](https://linux-hardware.org/?probe=b884bd8c03) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4cf17a7b6f](https://linux-hardware.org/?probe=4cf17a7b6f) | Sep 17, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [3ba3a4becf](https://linux-hardware.org/?probe=3ba3a4becf) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e6fe8aa148](https://linux-hardware.org/?probe=e6fe8aa148) | Sep 16, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Dell          | 0WR7PY A02                  | [0a587d6fee](https://linux-hardware.org/?probe=0a587d6fee) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [2391f4673a](https://linux-hardware.org/?probe=2391f4673a) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [89963f6bf1](https://linux-hardware.org/?probe=89963f6bf1) | Sep 12, 2022 |
| MSI           | X58 Pro                     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| Acer          | E415SM                      | [bc9ef15cab](https://linux-hardware.org/?probe=bc9ef15cab) | Sep 11, 2022 |
| Acer          | E415SM                      | [4f8a53c667](https://linux-hardware.org/?probe=4f8a53c667) | Sep 11, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [b76fc41706](https://linux-hardware.org/?probe=b76fc41706) | Sep 11, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [ad6a16f658](https://linux-hardware.org/?probe=ad6a16f658) | Sep 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4df5d0194d](https://linux-hardware.org/?probe=4df5d0194d) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ee06685499](https://linux-hardware.org/?probe=ee06685499) | Sep 11, 2022 |
| Dell          | 09M8Y8 A01                  | [c719d7f544](https://linux-hardware.org/?probe=c719d7f544) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| ASRock        | N3700-ITX                   | [5af515a1f9](https://linux-hardware.org/?probe=5af515a1f9) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| MSI           | H61M-P31                    | [56a8b0b2a7](https://linux-hardware.org/?probe=56a8b0b2a7) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Pegatron      | Narra6                      | [b2a70f42a0](https://linux-hardware.org/?probe=b2a70f42a0) | Sep 07, 2022 |
| ASRock        | Q1900M                      | [05cf506f57](https://linux-hardware.org/?probe=05cf506f57) | Sep 06, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [42e666abe1](https://linux-hardware.org/?probe=42e666abe1) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [cc631912bf](https://linux-hardware.org/?probe=cc631912bf) | Sep 06, 2022 |
| ASUSTek       | P9X79 PRO                   | [7e53f87cc4](https://linux-hardware.org/?probe=7e53f87cc4) | Sep 06, 2022 |
| ASUSTek       | H81M-PLUS                   | [826b486f77](https://linux-hardware.org/?probe=826b486f77) | Sep 05, 2022 |
| HP            | 0B4Ch D                     | [87c4023810](https://linux-hardware.org/?probe=87c4023810) | Sep 05, 2022 |
| ASRock        | Q1900M                      | [6b53538e90](https://linux-hardware.org/?probe=6b53538e90) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| Dell          | 0MWYPT A01                  | [57b81c35c1](https://linux-hardware.org/?probe=57b81c35c1) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [502995e6f3](https://linux-hardware.org/?probe=502995e6f3) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | P9X79 DELUXE                | [2aa7ada396](https://linux-hardware.org/?probe=2aa7ada396) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [26e63d2357](https://linux-hardware.org/?probe=26e63d2357) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [008133bf59](https://linux-hardware.org/?probe=008133bf59) | Sep 04, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [9cd2bcff37](https://linux-hardware.org/?probe=9cd2bcff37) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| ASUSTek       | P5P43TD                     | [cca9e79d90](https://linux-hardware.org/?probe=cca9e79d90) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | [ed16086671](https://linux-hardware.org/?probe=ed16086671) | Sep 04, 2022 |
| ASUSTek       | UN45                        | [87eca02296](https://linux-hardware.org/?probe=87eca02296) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [bf4936f3bc](https://linux-hardware.org/?probe=bf4936f3bc) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [878661705c](https://linux-hardware.org/?probe=878661705c) | Sep 04, 2022 |
| Dell          | 0T1D10 A01                  | [3064d08dc1](https://linux-hardware.org/?probe=3064d08dc1) | Sep 03, 2022 |
| ASUSTek       | PRIME H470-PLUS             | [e80ac4d271](https://linux-hardware.org/?probe=e80ac4d271) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [312013ef36](https://linux-hardware.org/?probe=312013ef36) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [6de688d21a](https://linux-hardware.org/?probe=6de688d21a) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| ASUSTek       | P5KC                        | [602e22310b](https://linux-hardware.org/?probe=602e22310b) | Sep 03, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | P7P55D                      | [ad2b0a0a89](https://linux-hardware.org/?probe=ad2b0a0a89) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASRock        | H310CM-HDV                  | [df5d5f2e7f](https://linux-hardware.org/?probe=df5d5f2e7f) | Sep 03, 2022 |
| Gigabyte      | Z97X-UD5H-BK                | [97a21d48e0](https://linux-hardware.org/?probe=97a21d48e0) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [982df83fdf](https://linux-hardware.org/?probe=982df83fdf) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [32d39c8b65](https://linux-hardware.org/?probe=32d39c8b65) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [709825bde3](https://linux-hardware.org/?probe=709825bde3) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| MSI           | H170 GAMING M3              | [b0d669cf4b](https://linux-hardware.org/?probe=b0d669cf4b) | Sep 03, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c13f075f83](https://linux-hardware.org/?probe=c13f075f83) | Sep 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [c64d84d331](https://linux-hardware.org/?probe=c64d84d331) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a591a1fecf](https://linux-hardware.org/?probe=a591a1fecf) | Sep 03, 2022 |
| ASRock        | FM2A88X-ITX+                | [9c22b70a4f](https://linux-hardware.org/?probe=9c22b70a4f) | Sep 03, 2022 |
| MSI           | B550-A PRO                  | [65bfdaa6ea](https://linux-hardware.org/?probe=65bfdaa6ea) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | [4d9025cf5c](https://linux-hardware.org/?probe=4d9025cf5c) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [acfa42b951](https://linux-hardware.org/?probe=acfa42b951) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7829cfc920](https://linux-hardware.org/?probe=7829cfc920) | Sep 02, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [5485918ea2](https://linux-hardware.org/?probe=5485918ea2) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Pegatron      | 2AB6                        | [c4ca3989e0](https://linux-hardware.org/?probe=c4ca3989e0) | Aug 31, 2022 |
| HP            | 18E9                        | [2dff78f303](https://linux-hardware.org/?probe=2dff78f303) | Aug 31, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [98e0a08e65](https://linux-hardware.org/?probe=98e0a08e65) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| OEM           | G41 775 ICH7 8712           | [4225df6517](https://linux-hardware.org/?probe=4225df6517) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [7a2c713719](https://linux-hardware.org/?probe=7a2c713719) | Aug 29, 2022 |
| HP            | 8751                        | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [17e8c1560b](https://linux-hardware.org/?probe=17e8c1560b) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| Gigabyte      | H97-HD3                     | [25e4d6c064](https://linux-hardware.org/?probe=25e4d6c064) | Aug 28, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| Gigabyte      | Z490 UD                     | [a872472b1c](https://linux-hardware.org/?probe=a872472b1c) | Aug 26, 2022 |
| Intel         | D2550MUD2 AAG81497-700      | [a181512016](https://linux-hardware.org/?probe=a181512016) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [a096217ea3](https://linux-hardware.org/?probe=a096217ea3) | Aug 24, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [1528da74f6](https://linux-hardware.org/?probe=1528da74f6) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | [dab0f526b0](https://linux-hardware.org/?probe=dab0f526b0) | Aug 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e064c453da](https://linux-hardware.org/?probe=e064c453da) | Aug 21, 2022 |
| Gigabyte      | P35-DS3L                    | [1ee42449ed](https://linux-hardware.org/?probe=1ee42449ed) | Aug 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [71bfa72a22](https://linux-hardware.org/?probe=71bfa72a22) | Aug 21, 2022 |
| MSI           | G31M3                       | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Boston                      | [4a10f122a2](https://linux-hardware.org/?probe=4a10f122a2) | Aug 19, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [410c71e7ef](https://linux-hardware.org/?probe=410c71e7ef) | Aug 18, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASRock        | 775Dual-VSTA                | [89ac2bb6fe](https://linux-hardware.org/?probe=89ac2bb6fe) | Aug 17, 2022 |
| HP            | 1495                        | [34b69b08b1](https://linux-hardware.org/?probe=34b69b08b1) | Aug 15, 2022 |
| HP            | 1495                        | [6db4307c50](https://linux-hardware.org/?probe=6db4307c50) | Aug 15, 2022 |
| HP            | 1495                        | [c122ce06ab](https://linux-hardware.org/?probe=c122ce06ab) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [4ba26713bc](https://linux-hardware.org/?probe=4ba26713bc) | Aug 15, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [2162cafc91](https://linux-hardware.org/?probe=2162cafc91) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [e5e5d0d3a3](https://linux-hardware.org/?probe=e5e5d0d3a3) | Aug 11, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [93ecf84dcf](https://linux-hardware.org/?probe=93ecf84dcf) | Aug 11, 2022 |
| ASRock        | G41M-VS3                    | [4185ab0f97](https://linux-hardware.org/?probe=4185ab0f97) | Aug 10, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [7792f4471e](https://linux-hardware.org/?probe=7792f4471e) | Aug 10, 2022 |
| ASRock        | H55M-LE                     | [841c63de14](https://linux-hardware.org/?probe=841c63de14) | Aug 08, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7ca881aae7](https://linux-hardware.org/?probe=7ca881aae7) | Aug 08, 2022 |
| Acer          | Predator PO3-620            | [ff0507688f](https://linux-hardware.org/?probe=ff0507688f) | Aug 02, 2022 |
| Acer          | FIH57                       | [eec3e58c8c](https://linux-hardware.org/?probe=eec3e58c8c) | Aug 02, 2022 |
| Acer          | FIH57                       | [a6b9d91f36](https://linux-hardware.org/?probe=a6b9d91f36) | Jul 30, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [bace89cd10](https://linux-hardware.org/?probe=bace89cd10) | Jul 30, 2022 |
| ASUSTek       | P6T DELUXE V2               | [3c18081f88](https://linux-hardware.org/?probe=3c18081f88) | Jul 29, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [54d5ee0a3a](https://linux-hardware.org/?probe=54d5ee0a3a) | Jul 28, 2022 |
| MSI           | B250M PRO-VD                | [e58c8fca5a](https://linux-hardware.org/?probe=e58c8fca5a) | Jul 28, 2022 |
| ASUSTek       | Z97-C                       | [e292699b1c](https://linux-hardware.org/?probe=e292699b1c) | Jul 28, 2022 |
| Acer          | EM61SM/EM61PM               | [2de6d95c80](https://linux-hardware.org/?probe=2de6d95c80) | Jul 28, 2022 |
| HP            | 1495                        | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| Acer          | FIH57                       | [f351802c52](https://linux-hardware.org/?probe=f351802c52) | Jul 26, 2022 |
| Dell          | 0KH290                      | [74934828fa](https://linux-hardware.org/?probe=74934828fa) | Jul 26, 2022 |
| MSI           | Z490-A PRO                  | [fe48f1e5cd](https://linux-hardware.org/?probe=fe48f1e5cd) | Jul 26, 2022 |
| Acer          | FIH57                       | [df3c42e452](https://linux-hardware.org/?probe=df3c42e452) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASRock        | 990FX Extreme3              | [158c8d142b](https://linux-hardware.org/?probe=158c8d142b) | Jul 24, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4f170da9](https://linux-hardware.org/?probe=6e4f170da9) | Jul 22, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| ASUSTek       | H110M-A/M.2                 | [97f5b09dd2](https://linux-hardware.org/?probe=97f5b09dd2) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6e4fbc6688](https://linux-hardware.org/?probe=6e4fbc6688) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Foxconn       | 2ABF                        | [765d75028c](https://linux-hardware.org/?probe=765d75028c) | Jul 19, 2022 |
| Dell          | 0F6X5P A00                  | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Acer          | FIH57                       | [ea25a3cc88](https://linux-hardware.org/?probe=ea25a3cc88) | Jul 15, 2022 |
| ASUSTek       | P5QLD PRO                   | [fbf3a31304](https://linux-hardware.org/?probe=fbf3a31304) | Jul 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [8f2f28b1c3](https://linux-hardware.org/?probe=8f2f28b1c3) | Jul 15, 2022 |
| Intel         | DQ77MK AAG39642-500         | [7b6a43a9f1](https://linux-hardware.org/?probe=7b6a43a9f1) | Jul 15, 2022 |
| HP            | 2B4B                        | [6592fe9157](https://linux-hardware.org/?probe=6592fe9157) | Jul 13, 2022 |
| MSI           | Boston                      | [4966d9bfdf](https://linux-hardware.org/?probe=4966d9bfdf) | Jul 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [491e37bdfb](https://linux-hardware.org/?probe=491e37bdfb) | Jul 12, 2022 |
| Acer          | FIH57                       | [b052eec1d0](https://linux-hardware.org/?probe=b052eec1d0) | Jul 10, 2022 |
| ASRock        | N68C-S UCC                  | [8c5338cc67](https://linux-hardware.org/?probe=8c5338cc67) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| MSI           | Z390-A PRO                  | [f3a1f552c8](https://linux-hardware.org/?probe=f3a1f552c8) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e7dfa60f77](https://linux-hardware.org/?probe=e7dfa60f77) | Jul 09, 2022 |
| MSI           | H110M GAMING                | [92f54d6efd](https://linux-hardware.org/?probe=92f54d6efd) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [d66a60be9a](https://linux-hardware.org/?probe=d66a60be9a) | Jul 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| MSI           | B250M PRO-VH                | [cab2cbb630](https://linux-hardware.org/?probe=cab2cbb630) | Jul 07, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| Acer          | FIH57                       | [75895f96b9](https://linux-hardware.org/?probe=75895f96b9) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5c8477b1a3](https://linux-hardware.org/?probe=5c8477b1a3) | Jul 04, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| ASRock        | J4105M                      | [502c01c109](https://linux-hardware.org/?probe=502c01c109) | Jul 03, 2022 |
| Gigabyte      | G31M-S2L                    | [d555145d9f](https://linux-hardware.org/?probe=d555145d9f) | Jul 03, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| ASRock        | AM1B-M                      | [e0e4a278c9](https://linux-hardware.org/?probe=e0e4a278c9) | Jul 02, 2022 |
| Intel         | D2500CC AAG81477-400        | [c9a6658803](https://linux-hardware.org/?probe=c9a6658803) | Jul 02, 2022 |
| ASRock        | 775Dual-VSTA                | [31825f35da](https://linux-hardware.org/?probe=31825f35da) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| Dell          | 0RF703                      | [7b1a5ddcb6](https://linux-hardware.org/?probe=7b1a5ddcb6) | Jun 27, 2022 |
| MSI           | B250 GAMING M3              | [b294a7b0b1](https://linux-hardware.org/?probe=b294a7b0b1) | Jun 26, 2022 |
| HP            | 3398                        | [4241fd0ba0](https://linux-hardware.org/?probe=4241fd0ba0) | Jun 26, 2022 |
| MSI           | B250 GAMING M3              | [f79c31ad28](https://linux-hardware.org/?probe=f79c31ad28) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Foxconn       | 945 7MC Series              | [16836e63f5](https://linux-hardware.org/?probe=16836e63f5) | Jun 25, 2022 |
| MSI           | A78M-E45                    | [ca217e0ccb](https://linux-hardware.org/?probe=ca217e0ccb) | Jun 25, 2022 |
| ASRock        | H77 Pro4/MVP                | [f022b1b430](https://linux-hardware.org/?probe=f022b1b430) | Jun 24, 2022 |
| ASRock        | X370 Pro4                   | [df6751dcaa](https://linux-hardware.org/?probe=df6751dcaa) | Jun 22, 2022 |
| Intel         | DX58SO AAE29331-703         | [edb0ff1a68](https://linux-hardware.org/?probe=edb0ff1a68) | Jun 22, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [1529cf29a5](https://linux-hardware.org/?probe=1529cf29a5) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [4a2493f02c](https://linux-hardware.org/?probe=4a2493f02c) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Unknown       | RS780-SB700                 | [a4649c2c4a](https://linux-hardware.org/?probe=a4649c2c4a) | Jun 21, 2022 |
| HP            | 0AA0h                       | [ccc94e1725](https://linux-hardware.org/?probe=ccc94e1725) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Dell          | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [7912825604](https://linux-hardware.org/?probe=7912825604) | Jun 19, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [c5763f8865](https://linux-hardware.org/?probe=c5763f8865) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [fb36d0a844](https://linux-hardware.org/?probe=fb36d0a844) | Jun 15, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [8852623d3d](https://linux-hardware.org/?probe=8852623d3d) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [c8dfb12509](https://linux-hardware.org/?probe=c8dfb12509) | Jun 14, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [d827dcbe06](https://linux-hardware.org/?probe=d827dcbe06) | Jun 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [1c1f01b85f](https://linux-hardware.org/?probe=1c1f01b85f) | Jun 12, 2022 |
| Foxconn       | Irvine HP P/N               | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| MSI           | Boston                      | [f44a102ffb](https://linux-hardware.org/?probe=f44a102ffb) | Jun 11, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [2dd49013ff](https://linux-hardware.org/?probe=2dd49013ff) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [59f197c68d](https://linux-hardware.org/?probe=59f197c68d) | Jun 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| ASRock        | 775Dual-VSTA                | [5dca8ae4cb](https://linux-hardware.org/?probe=5dca8ae4cb) | Jun 06, 2022 |
| ASRock        | 775Dual-VSTA                | [b627c94dff](https://linux-hardware.org/?probe=b627c94dff) | Jun 06, 2022 |
| MSI           | B550M PRO-VDH               | [8279a4df3a](https://linux-hardware.org/?probe=8279a4df3a) | Jun 06, 2022 |
| MSI           | Boston                      | [2497abc0c1](https://linux-hardware.org/?probe=2497abc0c1) | Jun 05, 2022 |
| MSI           | X570-A PRO                  | [95af0fa349](https://linux-hardware.org/?probe=95af0fa349) | Jun 04, 2022 |
| ASUSTek       | Z170-A                      | [ed86450031](https://linux-hardware.org/?probe=ed86450031) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | H110M-A/M.2                 | [990cfd2d12](https://linux-hardware.org/?probe=990cfd2d12) | May 31, 2022 |
| HP            | 3047h                       | [59affe5430](https://linux-hardware.org/?probe=59affe5430) | May 31, 2022 |
| Pegatron      | 2A73h                       | [c9af41f21f](https://linux-hardware.org/?probe=c9af41f21f) | May 28, 2022 |
| Pegatron      | 2A73h                       | [d09310f985](https://linux-hardware.org/?probe=d09310f985) | May 28, 2022 |
| MSI           | Boston                      | [53510ee8ef](https://linux-hardware.org/?probe=53510ee8ef) | May 28, 2022 |
| Dell          | 04YP6J A02                  | [5c0b3c0e56](https://linux-hardware.org/?probe=5c0b3c0e56) | May 28, 2022 |
| ASUSTek       | PRIME B460M-K               | [a6dafabf0c](https://linux-hardware.org/?probe=a6dafabf0c) | May 27, 2022 |
| ASRock        | AB350M Pro4                 | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Dell          | 0RF703                      | [228efad4f1](https://linux-hardware.org/?probe=228efad4f1) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [1715d72a33](https://linux-hardware.org/?probe=1715d72a33) | May 25, 2022 |
| T-bao         | MINI PC V1.0                | [f964c9691e](https://linux-hardware.org/?probe=f964c9691e) | May 25, 2022 |
| Gigabyte      | P55-UD3L                    | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| HP            | 1495                        | [68ead7bd6a](https://linux-hardware.org/?probe=68ead7bd6a) | May 23, 2022 |
| Foxconn       | 946 7MA Series              | [9f88edf79e](https://linux-hardware.org/?probe=9f88edf79e) | May 19, 2022 |
| MSI           | Z97-G45 GAMING              | [1b02844b0b](https://linux-hardware.org/?probe=1b02844b0b) | May 18, 2022 |
| MSI           | Boston                      | [b49f5c367f](https://linux-hardware.org/?probe=b49f5c367f) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [c84b325929](https://linux-hardware.org/?probe=c84b325929) | May 13, 2022 |
| ASUSTek       | NARRA3                      | [ca524c9e95](https://linux-hardware.org/?probe=ca524c9e95) | May 13, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Unknown       | Unknown                     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| HP            | 2B4B                        | [868bd14401](https://linux-hardware.org/?probe=868bd14401) | May 11, 2022 |
| ASUSTek       | H61M-K                      | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASUSTek       | P9X79                       | [694affb24e](https://linux-hardware.org/?probe=694affb24e) | May 10, 2022 |
| MSI           | B450M PRO-VDH MAX           | [feafca0464](https://linux-hardware.org/?probe=feafca0464) | May 10, 2022 |
| Unknown       | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [17e7dcafe2](https://linux-hardware.org/?probe=17e7dcafe2) | May 08, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| HP            | 18E7                        | [57194bb53c](https://linux-hardware.org/?probe=57194bb53c) | May 04, 2022 |
| ASUSTek       | CM6650                      | [d41d1228db](https://linux-hardware.org/?probe=d41d1228db) | May 04, 2022 |
| ASUSTek       | PRIME X370-A                | [4d1f9886c2](https://linux-hardware.org/?probe=4d1f9886c2) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [8d3881574d](https://linux-hardware.org/?probe=8d3881574d) | Apr 30, 2022 |
| HP            | 1494                        | [939f3b7987](https://linux-hardware.org/?probe=939f3b7987) | Apr 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8c1bf73769](https://linux-hardware.org/?probe=8c1bf73769) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| HP            | 1588h                       | [20624367eb](https://linux-hardware.org/?probe=20624367eb) | Apr 27, 2022 |
| HP            | 1588h                       | [831e4e5993](https://linux-hardware.org/?probe=831e4e5993) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [80792ef9d7](https://linux-hardware.org/?probe=80792ef9d7) | Apr 27, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire TC-780               | [501877dba5](https://linux-hardware.org/?probe=501877dba5) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [35975b7d55](https://linux-hardware.org/?probe=35975b7d55) | Apr 25, 2022 |
| ASUSTek       | P8H61-M LX2                 | [a60c0bf48d](https://linux-hardware.org/?probe=a60c0bf48d) | Apr 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| ASUSTek       | P5GD1                       | [11b7aa3465](https://linux-hardware.org/?probe=11b7aa3465) | Apr 24, 2022 |
| HP            | 09F8h                       | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [30f8dbd98c](https://linux-hardware.org/?probe=30f8dbd98c) | Apr 22, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [179d1e1a0f](https://linux-hardware.org/?probe=179d1e1a0f) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Lenovo        | SDK0E50510 WIN              | [3d829a871e](https://linux-hardware.org/?probe=3d829a871e) | Apr 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [beab5308cb](https://linux-hardware.org/?probe=beab5308cb) | Apr 19, 2022 |
| ASUSTek       | PRIME H510M-A               | [59fb2af2c2](https://linux-hardware.org/?probe=59fb2af2c2) | Apr 18, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [98637b4cf2](https://linux-hardware.org/?probe=98637b4cf2) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0169381aeb](https://linux-hardware.org/?probe=0169381aeb) | Apr 15, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [c3d8900f58](https://linux-hardware.org/?probe=c3d8900f58) | Apr 15, 2022 |
| Dell          | 0HN7XN A01                  | [5a9ba12201](https://linux-hardware.org/?probe=5a9ba12201) | Apr 15, 2022 |
| Gigabyte      | GA-A55M-S2V                 | [36d5c02824](https://linux-hardware.org/?probe=36d5c02824) | Apr 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | [7cc9a1bbb7](https://linux-hardware.org/?probe=7cc9a1bbb7) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | A68HM-P33                   | [8c395556de](https://linux-hardware.org/?probe=8c395556de) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e3a8701de2](https://linux-hardware.org/?probe=e3a8701de2) | Apr 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [58dab53fb1](https://linux-hardware.org/?probe=58dab53fb1) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [8c2362aa24](https://linux-hardware.org/?probe=8c2362aa24) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [14b70a1c77](https://linux-hardware.org/?probe=14b70a1c77) | Apr 10, 2022 |
| ASUSTek       | M2N8L                       | [dc78c18c3f](https://linux-hardware.org/?probe=dc78c18c3f) | Apr 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a56209b0c7](https://linux-hardware.org/?probe=a56209b0c7) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [8d440b5da5](https://linux-hardware.org/?probe=8d440b5da5) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| HP            | 3397                        | [d22ff33b0e](https://linux-hardware.org/?probe=d22ff33b0e) | Apr 08, 2022 |
| Lenovo        | ThinkStation S20 4157WC1    | [d64502fb70](https://linux-hardware.org/?probe=d64502fb70) | Apr 08, 2022 |
| Intel         | STK2MV64CC H89290-502       | [b2cb31c994](https://linux-hardware.org/?probe=b2cb31c994) | Apr 07, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| ASRock        | C2750D4I                    | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASRock        | 970 Extreme4                | [cc65547e82](https://linux-hardware.org/?probe=cc65547e82) | Apr 03, 2022 |
| MSI           | Z590-A PRO                  | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Acer          | Aspire M1920                | [00d3df045a](https://linux-hardware.org/?probe=00d3df045a) | Apr 02, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [3807eeb187](https://linux-hardware.org/?probe=3807eeb187) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| ASUSTek       | A68HM-K                     | [482d5e9c62](https://linux-hardware.org/?probe=482d5e9c62) | Apr 01, 2022 |
| ASRock        | 775Dual-VSTA                | [f5aea8ce64](https://linux-hardware.org/?probe=f5aea8ce64) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [79a7adfb69](https://linux-hardware.org/?probe=79a7adfb69) | Mar 29, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [641cb912c4](https://linux-hardware.org/?probe=641cb912c4) | Mar 29, 2022 |
| Gigabyte      | H81M-S2PV                   | [5a75a3f121](https://linux-hardware.org/?probe=5a75a3f121) | Mar 29, 2022 |
| ASUSTek       | AM1M-A                      | [29e10859da](https://linux-hardware.org/?probe=29e10859da) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [9688bbdb3f](https://linux-hardware.org/?probe=9688bbdb3f) | Mar 28, 2022 |
| ASUSTek       | H110M-K                     | [4e238835bd](https://linux-hardware.org/?probe=4e238835bd) | Mar 28, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | [6f66a7137f](https://linux-hardware.org/?probe=6f66a7137f) | Mar 28, 2022 |
| ASRock        | AMCP7AION-HT                | [23f929c975](https://linux-hardware.org/?probe=23f929c975) | Mar 27, 2022 |
| ASUSTek       | H110M-K                     | [14f509aa32](https://linux-hardware.org/?probe=14f509aa32) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [31098e4c80](https://linux-hardware.org/?probe=31098e4c80) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [e4526228cd](https://linux-hardware.org/?probe=e4526228cd) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [402c4d5758](https://linux-hardware.org/?probe=402c4d5758) | Mar 26, 2022 |
| MSI           | IONA                        | [1a625c0505](https://linux-hardware.org/?probe=1a625c0505) | Mar 25, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| Gigabyte      | MZBAYAP-D9                  | [2c077e2993](https://linux-hardware.org/?probe=2c077e2993) | Mar 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [481f4ad619](https://linux-hardware.org/?probe=481f4ad619) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [8ba917619e](https://linux-hardware.org/?probe=8ba917619e) | Mar 19, 2022 |
| Dell          | 033FF6 A00                  | [48c7f5e6ae](https://linux-hardware.org/?probe=48c7f5e6ae) | Mar 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [73bf7d8080](https://linux-hardware.org/?probe=73bf7d8080) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 373      | 14.65%  |
| Ubuntu 18.04        | 242      | 9.51%   |
| Ubuntu 22.04        | 102      | 4.01%   |
| OpenMandriva 4.2    | 101      | 3.97%   |
| OpenMandriva 4.3    | 74       | 2.91%   |
| Arch Rolling        | 52       | 2.04%   |
| Ubuntu 20.10        | 51       | 2%      |
| Debian 11           | 51       | 2%      |
| Ubuntu 19.04        | 47       | 1.85%   |
| KDE neon 20.04      | 43       | 1.69%   |
| Fedora 36           | 43       | 1.69%   |
| Ubuntu 19.10        | 42       | 1.65%   |
| Xubuntu 20.04       | 36       | 1.41%   |
| Arch                | 36       | 1.41%   |
| Linux Mint 20.3     | 35       | 1.37%   |
| Xubuntu 18.04       | 34       | 1.34%   |
| ROSA R10            | 32       | 1.26%   |
| Zorin 16            | 31       | 1.22%   |
| Linux Mint 21       | 31       | 1.22%   |
| Ubuntu 22.10        | 30       | 1.18%   |
| Ubuntu 21.10        | 30       | 1.18%   |
| Ubuntu 21.04        | 30       | 1.18%   |
| Debian 10           | 30       | 1.18%   |
| Manjaro             | 29       | 1.14%   |
| Pop!_OS 22.04       | 26       | 1.02%   |
| Kubuntu 20.04       | 26       | 1.02%   |
| Linux Mint 19.3     | 25       | 0.98%   |
| Ubuntu 18.10        | 24       | 0.94%   |
| Linux Mint 20.2     | 22       | 0.86%   |
| Linux Mint 20.1     | 22       | 0.86%   |
| Linux Mint 20       | 22       | 0.86%   |
| ROSA R11            | 20       | 0.79%   |
| OpenMandriva 23.01  | 20       | 0.79%   |
| ROSA R9             | 19       | 0.75%   |
| Zorin 15            | 18       | 0.71%   |
| Pop!_OS 20.10       | 18       | 0.71%   |
| Fedora 35           | 17       | 0.67%   |
| Linux Mint 21.1     | 16       | 0.63%   |
| EndeavourOS Rolling | 16       | 0.63%   |
| Ubuntu 16.04        | 15       | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 939      | 38.79%  |
| OpenMandriva  | 222      | 9.17%   |
| Linux Mint    | 182      | 7.52%   |
| Fedora        | 116      | 4.79%   |
| Xubuntu       | 105      | 4.34%   |
| Debian        | 105      | 4.34%   |
| ROSA          | 91       | 3.76%   |
| Arch          | 87       | 3.59%   |
| Manjaro       | 73       | 3.02%   |
| Pop!_OS       | 72       | 2.97%   |
| KDE neon      | 60       | 2.48%   |
| Kubuntu       | 59       | 2.44%   |
| Zorin         | 53       | 2.19%   |
| Lubuntu       | 25       | 1.03%   |
| Ubuntu MATE   | 23       | 0.95%   |
| EndeavourOS   | 20       | 0.83%   |
| Ubuntu Unity  | 18       | 0.74%   |
| openSUSE      | 17       | 0.7%    |
| Clear Linux   | 14       | 0.58%   |
| BlackPanther  | 14       | 0.58%   |
| Elementary    | 11       | 0.45%   |
| LMDE          | 10       | 0.41%   |
| Gentoo        | 10       | 0.41%   |
| Endless       | 10       | 0.41%   |
| Peppermint    | 9        | 0.37%   |
| MX            | 8        | 0.33%   |
| Garuda Linux  | 7        | 0.29%   |
| ArcoLinux     | 7        | 0.29%   |
| Ubuntu Studio | 6        | 0.25%   |
| Slackware     | 4        | 0.17%   |
| LinuxFX       | 4        | 0.17%   |
| CentOS        | 4        | 0.17%   |
| Q4OS          | 3        | 0.12%   |
| Kali          | 3        | 0.12%   |
| Ubuntu Budgie | 2        | 0.08%   |
| Rocky Linux   | 2        | 0.08%   |
| RHEL          | 2        | 0.08%   |
| Puppy         | 2        | 0.08%   |
| Parrot        | 2        | 0.08%   |
| Chrome OS     | 2        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 99       | 3.49%   |
| 5.16.7-desktop-1omv4003         | 72       | 2.54%   |
| 5.15.0-52-generic               | 57       | 2.01%   |
| 5.4.0-42-generic                | 52       | 1.83%   |
| 5.4.0-52-generic                | 43       | 1.52%   |
| 5.15.0-56-generic               | 34       | 1.2%    |
| 5.15.0-47-generic               | 33       | 1.16%   |
| 5.4.0-58-generic                | 24       | 0.85%   |
| 5.4.0-48-generic                | 24       | 0.85%   |
| 5.3.0-46-generic                | 23       | 0.81%   |
| 5.3.0-40-generic                | 23       | 0.81%   |
| 5.4.0-56-generic                | 22       | 0.78%   |
| 5.15.0-58-generic               | 22       | 0.78%   |
| 5.4.0-29-generic                | 21       | 0.74%   |
| 5.4.0-26-generic                | 21       | 0.74%   |
| 5.15.0-46-generic               | 21       | 0.74%   |
| 5.4.0-54-generic                | 20       | 0.71%   |
| 5.4.0-40-generic                | 19       | 0.67%   |
| 6.1.1-desktop-1omv2290          | 18       | 0.64%   |
| 5.4.0-28-generic                | 18       | 0.64%   |
| 5.11.0-38-generic               | 18       | 0.64%   |
| 5.0.0-32-generic                | 18       | 0.64%   |
| 5.8.0-59-generic                | 16       | 0.56%   |
| 5.4.0-37-generic                | 16       | 0.56%   |
| 5.8.0-41-generic                | 15       | 0.53%   |
| 5.4.0-65-generic                | 15       | 0.53%   |
| 5.4.0-33-generic                | 15       | 0.53%   |
| 5.3.0-42-generic                | 15       | 0.53%   |
| 5.4.0-47-generic                | 14       | 0.49%   |
| 5.4.0-31-generic                | 14       | 0.49%   |
| 5.19.0-23-generic               | 14       | 0.49%   |
| 5.15.0-43-generic               | 14       | 0.49%   |
| 5.10.0-19-amd64                 | 14       | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.49%   |
| 4.18.16-desktop-1bP             | 14       | 0.49%   |
| 4.18.0-25-generic               | 14       | 0.49%   |
| 5.8.0-48-generic                | 13       | 0.46%   |
| 5.13.0-39-generic               | 13       | 0.46%   |
| 5.11.0-27-generic               | 13       | 0.46%   |
| 4.15.0-29-generic               | 13       | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 507      | 19.37%  |
| 5.15.0  | 231      | 8.82%   |
| 4.15.0  | 209      | 7.98%   |
| 5.8.0   | 162      | 6.19%   |
| 5.3.0   | 140      | 5.35%   |
| 5.11.0  | 115      | 4.39%   |
| 5.10.14 | 100      | 3.82%   |
| 5.0.0   | 99       | 3.78%   |
| 5.13.0  | 84       | 3.21%   |
| 5.16.7  | 73       | 2.79%   |
| 4.18.0  | 65       | 2.48%   |
| 5.10.0  | 61       | 2.33%   |
| 5.19.0  | 48       | 1.83%   |
| 4.19.0  | 28       | 1.07%   |
| 6.0.2   | 27       | 1.03%   |
| 6.1.1   | 22       | 0.84%   |
| 4.9.60  | 18       | 0.69%   |
| 4.9.20  | 17       | 0.65%   |
| 5.19.6  | 15       | 0.57%   |
| 4.18.16 | 15       | 0.57%   |
| 6.0.6   | 14       | 0.53%   |
| 5.19.16 | 13       | 0.5%    |
| 6.0.10  | 11       | 0.42%   |
| 5.17.5  | 10       | 0.38%   |
| 4.4.0   | 10       | 0.38%   |
| 6.0.12  | 8        | 0.31%   |
| 5.12.4  | 8        | 0.31%   |
| 6.0.9   | 7        | 0.27%   |
| 6.0.8   | 7        | 0.27%   |
| 6.0.5   | 7        | 0.27%   |
| 5.19.4  | 7        | 0.27%   |
| 5.18.12 | 7        | 0.27%   |
| 5.16.11 | 7        | 0.27%   |
| 6.0.7   | 6        | 0.23%   |
| 5.9.16  | 6        | 0.23%   |
| 5.4.32  | 6        | 0.23%   |
| 5.15.15 | 6        | 0.23%   |
| 4.1.34  | 6        | 0.23%   |
| 5.9.1   | 5        | 0.19%   |
| 5.8.18  | 5        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 533      | 20.61%  |
| 5.15    | 283      | 10.94%  |
| 4.15    | 210      | 8.12%   |
| 5.10    | 189      | 7.31%   |
| 5.8     | 186      | 7.19%   |
| 5.3     | 145      | 5.61%   |
| 5.11    | 134      | 5.18%   |
| 5.19    | 105      | 4.06%   |
| 5.0     | 102      | 3.94%   |
| 5.16    | 101      | 3.91%   |
| 6.0     | 93       | 3.6%    |
| 5.13    | 91       | 3.52%   |
| 4.18    | 84       | 3.25%   |
| 4.9     | 55       | 2.13%   |
| 4.19    | 38       | 1.47%   |
| 6.1     | 35       | 1.35%   |
| 5.9     | 32       | 1.24%   |
| 5.17    | 28       | 1.08%   |
| 5.18    | 24       | 0.93%   |
| 5.6     | 20       | 0.77%   |
| 5.12    | 19       | 0.73%   |
| 5.7     | 18       | 0.7%    |
| 5.14    | 14       | 0.54%   |
| 4.4     | 10       | 0.39%   |
| 4.1     | 10       | 0.39%   |
| 5.5     | 9        | 0.35%   |
| 4.13    | 5        | 0.19%   |
| 5.1     | 2        | 0.08%   |
| 4.20    | 2        | 0.08%   |
| 5.2     | 1        | 0.04%   |
| 4.8     | 1        | 0.04%   |
| 4.7     | 1        | 0.04%   |
| 4.17    | 1        | 0.04%   |
| 4.14    | 1        | 0.04%   |
| 4.12    | 1        | 0.04%   |
| 3.14    | 1        | 0.04%   |
| 3.10    | 1        | 0.04%   |
| 2.6.35  | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2245     | 95.57%  |
| i686   | 104      | 4.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 966      | 39.41%  |
| KDE5             | 451      | 18.4%   |
| Unknown          | 358      | 14.61%  |
| XFCE             | 194      | 7.92%   |
| X-Cinnamon       | 152      | 6.2%    |
| MATE             | 69       | 2.82%   |
| KDE              | 61       | 2.49%   |
| KDE4             | 57       | 2.33%   |
| LXQt             | 32       | 1.31%   |
| LXDE             | 21       | 0.86%   |
| Cinnamon         | 20       | 0.82%   |
| Unity            | 18       | 0.73%   |
| Pantheon         | 10       | 0.41%   |
| GNOME Flashback  | 10       | 0.41%   |
| GNOME Classic    | 6        | 0.24%   |
| Deepin           | 5        | 0.2%    |
| lightdm-xsession | 4        | 0.16%   |
| Trinity          | 3        | 0.12%   |
| i3               | 3        | 0.12%   |
| Budgie           | 3        | 0.12%   |
| openbox          | 2        | 0.08%   |
| sway             | 1        | 0.04%   |
| Lubuntu          | 1        | 0.04%   |
| Hyprland         | 1        | 0.04%   |
| herbstluftwm     | 1        | 0.04%   |
| FVWM             | 1        | 0.04%   |
| bspwm            | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1936     | 80.23%  |
| Wayland | 255      | 10.57%  |
| Unknown | 187      | 7.75%   |
| Tty     | 35       | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1256     | 51.29%  |
| SDDM    | 425      | 17.35%  |
| GDM3    | 232      | 9.47%   |
| LightDM | 210      | 8.57%   |
| GDM     | 199      | 8.13%   |
| TDM     | 60       | 2.45%   |
| KDM     | 59       | 2.41%   |
| XDM     | 4        | 0.16%   |
| GREETD  | 2        | 0.08%   |
| NODM    | 1        | 0.04%   |
| LXDM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| it_IT       | 1531     | 63.69%  |
| Unknown     | 386      | 16.06%  |
| en_US       | 377      | 15.68%  |
| en_GB       | 45       | 1.87%   |
| C           | 37       | 1.54%   |
| it_CH       | 4        | 0.17%   |
| de_DE       | 4        | 0.17%   |
| ru_RU       | 3        | 0.12%   |
| de_AT       | 3        | 0.12%   |
| fr_FR       | 2        | 0.08%   |
| en_IE       | 2        | 0.08%   |
| de_IT       | 2        | 0.08%   |
| POSIX       | 1        | 0.04%   |
| it_ITutf8   | 1        | 0.04%   |
| hu_HU       | 1        | 0.04%   |
| es_MX       | 1        | 0.04%   |
| es_ES       | 1        | 0.04%   |
| en_US.ASCII | 1        | 0.04%   |
| en_AG       | 1        | 0.04%   |
| Default     | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1536     | 64.03%  |
| EFI  | 863      | 35.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1831     | 76.29%  |
| Overlay | 262      | 10.92%  |
| Btrfs   | 128      | 5.33%   |
| Unknown | 117      | 4.88%   |
| Xfs     | 26       | 1.08%   |
| Zfs     | 10       | 0.42%   |
| Ext3    | 9        | 0.38%   |
| Ext2    | 7        | 0.29%   |
| Tmpfs   | 5        | 0.21%   |
| F2fs    | 2        | 0.08%   |
| Aufs    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1349     | 55.93%  |
| GPT     | 707      | 29.31%  |
| MBR     | 356      | 14.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1875     | 77.83%  |
| Yes       | 534      | 22.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1383     | 57.6%   |
| Yes       | 1018     | 42.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 750      | 31.97%  |
| ASRock              | 298      | 12.7%   |
| MSI                 | 277      | 11.81%  |
| Gigabyte Technology | 223      | 9.51%   |
| Hewlett-Packard     | 185      | 7.89%   |
| Dell                | 114      | 4.86%   |
| Acer                | 95       | 4.05%   |
| Lenovo              | 74       | 3.15%   |
| Intel               | 52       | 2.22%   |
| Pegatron            | 40       | 1.71%   |
| Unknown             | 32       | 1.36%   |
| Fujitsu             | 29       | 1.24%   |
| Packard Bell        | 25       | 1.07%   |
| Foxconn             | 22       | 0.94%   |
| Fujitsu Siemens     | 12       | 0.51%   |
| Supermicro          | 9        | 0.38%   |
| Biostar             | 8        | 0.34%   |
| BESSTAR Tech        | 8        | 0.34%   |
| AMI                 | 8        | 0.34%   |
| AZW                 | 6        | 0.26%   |
| ABIT                | 6        | 0.26%   |
| TYAN Computer       | 5        | 0.21%   |
| Sapphire            | 5        | 0.21%   |
| IBM                 | 5        | 0.21%   |
| Apple               | 5        | 0.21%   |
| Wistron             | 4        | 0.17%   |
| NEC Computers       | 4        | 0.17%   |
| Gateway             | 3        | 0.13%   |
| ECS                 | 3        | 0.13%   |
| Alienware           | 3        | 0.13%   |
| YANYU               | 2        | 0.09%   |
| Shuttle             | 2        | 0.09%   |
| Proline             | 2        | 0.09%   |
| OEM                 | 2        | 0.09%   |
| LattePanda          | 2        | 0.09%   |
| Huanan              | 2        | 0.09%   |
| eMachines           | 2        | 0.09%   |
| American Megatrends | 2        | 0.09%   |
| AAEON               | 2        | 0.09%   |
| ZOTAC               | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 67       | 2.86%   |
| Unknown                          | 33       | 1.41%   |
| ASUS PRIME A320M-K               | 15       | 0.64%   |
| MSI MS-7C37                      | 13       | 0.55%   |
| MSI MS-7B86                      | 12       | 0.51%   |
| Dell OptiPlex 7010               | 12       | 0.51%   |
| MSI MS-7C56                      | 10       | 0.43%   |
| HP Compaq Elite 8300 SFF         | 10       | 0.43%   |
| Gigabyte B450M DS3H              | 9        | 0.38%   |
| ASUS TUF Gaming X570-PLUS        | 8        | 0.34%   |
| Supermicro H8DM8-2               | 7        | 0.3%    |
| MSI MS-7B79                      | 7        | 0.3%    |
| HP Compaq 8200 Elite SFF PC      | 7        | 0.3%    |
| Dell OptiPlex 3020               | 7        | 0.3%    |
| ASUS TUF Gaming B550-PLUS        | 7        | 0.3%    |
| ASUS ROG STRIX B550-F GAMING     | 7        | 0.3%    |
| ASUS P5KPL-SE                    | 7        | 0.3%    |
| ASRock Q1900M                    | 7        | 0.3%    |
| ASRock N68C-S UCC                | 7        | 0.3%    |
| MSI MS-7C52                      | 6        | 0.26%   |
| MSI MS-7C02                      | 6        | 0.26%   |
| MSI MS-7758                      | 6        | 0.26%   |
| Dell OptiPlex 390                | 6        | 0.26%   |
| ASUS P5KPL-AM SE                 | 6        | 0.26%   |
| ASRock B450M-HDV R4.0            | 6        | 0.26%   |
| MSI MS-7817                      | 5        | 0.21%   |
| HP ProDesk 600 G1 SFF            | 5        | 0.21%   |
| HP Compaq 6000 Pro MT PC         | 5        | 0.21%   |
| Gigabyte X570 AORUS ELITE        | 5        | 0.21%   |
| Gigabyte X470 AORUS ULTRA GAMING | 5        | 0.21%   |
| Dell OptiPlex 990                | 5        | 0.21%   |
| Dell OptiPlex 780                | 5        | 0.21%   |
| Dell OptiPlex 760                | 5        | 0.21%   |
| Dell OptiPlex 3010               | 5        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING     | 5        | 0.21%   |
| ASUS PRIME B450-PLUS             | 5        | 0.21%   |
| ASUS P6T DELUXE V2               | 5        | 0.21%   |
| ASUS M5A97 R2.0                  | 5        | 0.21%   |
| ASUS H110M-K                     | 5        | 0.21%   |
| ASRock G31M-GS                   | 5        | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 107      | 4.56%   |
| HP Compaq           | 80       | 3.41%   |
| Dell OptiPlex       | 68       | 2.9%    |
| ASUS All            | 67       | 2.86%   |
| Acer Aspire         | 53       | 2.26%   |
| ASUS TUF            | 48       | 2.05%   |
| ASUS ROG            | 46       | 1.96%   |
| Lenovo ThinkCentre  | 42       | 1.79%   |
| Unknown             | 33       | 1.41%   |
| Acer Veriton        | 29       | 1.24%   |
| Fujitsu ESPRIMO     | 26       | 1.11%   |
| Dell Precision      | 20       | 0.85%   |
| ASUS P8H61-M        | 19       | 0.81%   |
| Packard Bell IMEDIA | 17       | 0.72%   |
| HP Pavilion         | 17       | 0.72%   |
| HP ProDesk          | 16       | 0.68%   |
| Gigabyte X570       | 15       | 0.64%   |
| HP EliteDesk        | 14       | 0.6%    |
| MSI MS-7C37         | 13       | 0.55%   |
| ASUS P5KPL-AM       | 13       | 0.55%   |
| MSI MS-7B86         | 12       | 0.51%   |
| Gigabyte B450       | 12       | 0.51%   |
| ASUS M5A97          | 12       | 0.51%   |
| Gigabyte B450M      | 11       | 0.47%   |
| ASUS P5Q            | 11       | 0.47%   |
| MSI MS-7C56         | 10       | 0.43%   |
| Lenovo IdeaCentre   | 10       | 0.43%   |
| ASUS P5K            | 10       | 0.43%   |
| ASUS M5A78L-M       | 10       | 0.43%   |
| ASUS P8Z77-V        | 9        | 0.38%   |
| ASUS P6T            | 9        | 0.38%   |
| ASRock 970          | 9        | 0.38%   |
| Pegatron Pro        | 8        | 0.34%   |
| Lenovo ThinkStation | 8        | 0.34%   |
| Gigabyte Z390       | 8        | 0.34%   |
| ASUS P8P67          | 8        | 0.34%   |
| ASRock B450         | 8        | 0.34%   |
| Supermicro H8DM8-2  | 7        | 0.3%    |
| MSI MS-7B79         | 7        | 0.3%    |
| MSI Compaq          | 7        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 212      | 9.04%   |
| 2012    | 196      | 8.35%   |
| 2009    | 192      | 8.18%   |
| 2013    | 188      | 8.01%   |
| 2008    | 169      | 7.2%    |
| 2011    | 163      | 6.95%   |
| 2019    | 153      | 6.52%   |
| 2014    | 149      | 6.35%   |
| 2010    | 137      | 5.84%   |
| 2020    | 131      | 5.58%   |
| 2007    | 121      | 5.16%   |
| 2017    | 119      | 5.07%   |
| 2015    | 109      | 4.65%   |
| 2016    | 96       | 4.09%   |
| 2006    | 70       | 2.98%   |
| 2021    | 68       | 2.9%    |
| 2005    | 40       | 1.71%   |
| 2022    | 13       | 0.55%   |
| 2004    | 11       | 0.47%   |
| 2003    | 4        | 0.17%   |
| 2001    | 2        | 0.09%   |
| Unknown | 2        | 0.09%   |
| 2002    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2346     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2298     | 97.79%  |
| Enabled  | 52       | 2.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2346     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 518      | 21.73%  |
| 16.01-24.0      | 498      | 20.89%  |
| 3.01-4.0        | 487      | 20.43%  |
| 4.01-8.0        | 357      | 14.97%  |
| 32.01-64.0      | 229      | 9.61%   |
| 1.01-2.0        | 132      | 5.54%   |
| 64.01-256.0     | 58       | 2.43%   |
| 24.01-32.0      | 40       | 1.68%   |
| 2.01-3.0        | 38       | 1.59%   |
| 0.51-1.0        | 23       | 0.96%   |
| More than 256.0 | 2        | 0.08%   |
| 0.01-0.5        | 2        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1087     | 41.89%  |
| 2.01-3.0   | 587      | 22.62%  |
| 3.01-4.0   | 272      | 10.48%  |
| 4.01-8.0   | 263      | 10.13%  |
| 0.51-1.0   | 263      | 10.13%  |
| 8.01-16.0  | 73       | 2.81%   |
| 0.01-0.5   | 33       | 1.27%   |
| 16.01-24.0 | 11       | 0.42%   |
| 24.01-32.0 | 4        | 0.15%   |
| 32.01-64.0 | 1        | 0.04%   |
| Unknown    | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 925      | 37.83%  |
| 2       | 742      | 30.35%  |
| 3       | 386      | 15.79%  |
| 4       | 197      | 8.06%   |
| 5       | 90       | 3.68%   |
| 6       | 39       | 1.6%    |
| 0       | 28       | 1.15%   |
| 7       | 16       | 0.65%   |
| 8       | 10       | 0.41%   |
| 10      | 4        | 0.16%   |
| 12      | 3        | 0.12%   |
| 9       | 3        | 0.12%   |
| 13      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1454     | 61.22%  |
| No        | 921      | 38.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2330     | 99.32%  |
| No        | 16       | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1374     | 57.85%  |
| Yes       | 1001     | 42.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1787     | 74.83%  |
| Yes       | 601      | 25.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 2346     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 282      | 10.66%  |
| Rome                  | 271      | 10.24%  |
| Turin                 | 83       | 3.14%   |
| Bologna               | 73       | 2.76%   |
| Naples                | 54       | 2.04%   |
| Florence              | 48       | 1.81%   |
| Genoa                 | 46       | 1.74%   |
| Palermo               | 31       | 1.17%   |
| Padova                | 29       | 1.1%    |
| Rho                   | 26       | 0.98%   |
| Verona                | 23       | 0.87%   |
| Venice                | 20       | 0.76%   |
| Trieste               | 18       | 0.68%   |
| Catania               | 18       | 0.68%   |
| Brescia               | 17       | 0.64%   |
| Reggio Emilia         | 16       | 0.6%    |
| Capriate San Gervasio | 16       | 0.6%    |
| Pescara               | 15       | 0.57%   |
| Bari                  | 15       | 0.57%   |
| Parma                 | 14       | 0.53%   |
| Cagliari              | 14       | 0.53%   |
| Bergamo               | 13       | 0.49%   |
| Sesto San Giovanni    | 12       | 0.45%   |
| Pisa                  | 12       | 0.45%   |
| Trento                | 11       | 0.42%   |
| Taranto               | 11       | 0.42%   |
| Monza                 | 11       | 0.42%   |
| Modena                | 11       | 0.42%   |
| Como                  | 10       | 0.38%   |
| Treviso               | 9        | 0.34%   |
| Perugia               | 9        | 0.34%   |
| Lucca                 | 9        | 0.34%   |
| Casalecchio di Reno   | 9        | 0.34%   |
| Vicenza               | 8        | 0.3%    |
| Mestre                | 8        | 0.3%    |
| Udine                 | 7        | 0.26%   |
| Capannori             | 7        | 0.26%   |
| Sesto Fiorentino      | 6        | 0.23%   |
| Rozzano               | 6        | 0.23%   |
| Reggio Calabria       | 6        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 869      | 1434   | 20.58%  |
| WDC                       | 804      | 1319   | 19.04%  |
| Samsung Electronics       | 615      | 945    | 14.56%  |
| Kingston                  | 304      | 428    | 7.2%    |
| Crucial                   | 264      | 352    | 6.25%   |
| Toshiba                   | 210      | 329    | 4.97%   |
| Maxtor                    | 171      | 233    | 4.05%   |
| Hitachi                   | 151      | 205    | 3.58%   |
| SanDisk                   | 137      | 203    | 3.24%   |
| Unknown                   | 59       | 81     | 1.4%    |
| Phison                    | 51       | 61     | 1.21%   |
| China                     | 33       | 36     | 0.78%   |
| SPCC                      | 29       | 34     | 0.69%   |
| Intel                     | 28       | 36     | 0.66%   |
| Corsair                   | 28       | 44     | 0.66%   |
| HGST                      | 27       | 43     | 0.64%   |
| Intenso                   | 24       | 34     | 0.57%   |
| Micron/Crucial Technology | 23       | 31     | 0.54%   |
| OCZ                       | 21       | 23     | 0.5%    |
| A-DATA Technology         | 21       | 30     | 0.5%    |
| Transcend                 | 17       | 23     | 0.4%    |
| Micron Technology         | 17       | 18     | 0.4%    |
| PNY                       | 16       | 21     | 0.38%   |
| KingDian                  | 15       | 16     | 0.36%   |
| Patriot                   | 14       | 17     | 0.33%   |
| Silicon Motion            | 13       | 18     | 0.31%   |
| Phison Electronics        | 13       | 15     | 0.31%   |
| SK hynix                  | 11       | 12     | 0.26%   |
| Drevo                     | 11       | 12     | 0.26%   |
| Team                      | 9        | 14     | 0.21%   |
| GOODRAM                   | 9        | 14     | 0.21%   |
| Fujitsu                   | 9        | 10     | 0.21%   |
| TCSUNBOW                  | 8        | 9      | 0.19%   |
| JMicron Technology        | 8        | 8      | 0.19%   |
| XPG                       | 7        | 7      | 0.17%   |
| Lexar                     | 7        | 9      | 0.17%   |
| Dogfish                   | 7        | 10     | 0.17%   |
| LITEONIT                  | 6        | 6      | 0.14%   |
| ASMT                      | 6        | 6      | 0.14%   |
| Netac                     | 5        | 6      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 95       | 1.95%   |
| Kingston SA400S37240G 240GB SSD  | 85       | 1.74%   |
| Samsung SSD 860 EVO 500GB        | 71       | 1.45%   |
| Samsung SSD 850 EVO 250GB        | 67       | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB   | 63       | 1.29%   |
| Crucial CT500MX500SSD1 500GB     | 57       | 1.17%   |
| Toshiba DT01ACA100 1TB           | 56       | 1.15%   |
| Kingston SA400S37480G 480GB SSD  | 50       | 1.02%   |
| Seagate ST2000DM008-2FR102 2TB   | 48       | 0.98%   |
| Seagate ST3500418AS 500GB        | 45       | 0.92%   |
| Samsung SSD 860 EVO 250GB        | 41       | 0.84%   |
| Samsung SSD 850 EVO 500GB        | 41       | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB   | 36       | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB         | 35       | 0.72%   |
| Seagate ST31000528AS 1TB         | 35       | 0.72%   |
| Crucial CT240BX500SSD1 240GB     | 34       | 0.7%    |
| Seagate ST2000DM001-1ER164 2TB   | 31       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 31       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB   | 30       | 0.61%   |
| Crucial CT1000MX500SSD1 1TB      | 30       | 0.61%   |
| Kingston SV300S37A120G 120GB SSD | 29       | 0.59%   |
| Samsung NVMe SSD Drive 500GB     | 26       | 0.53%   |
| Toshiba DT01ACA050 500GB         | 25       | 0.51%   |
| Seagate ST3500413AS 500GB        | 25       | 0.51%   |
| Seagate ST1000DM003-1SB10C 1TB   | 25       | 0.51%   |
| Crucial CT480BX500SSD1 480GB     | 24       | 0.49%   |
| Samsung SSD 840 EVO 250GB        | 23       | 0.47%   |
| Toshiba DT01ACA200 2TB           | 21       | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB   | 21       | 0.43%   |
| Seagate ST1000DM003-9YN162 1TB   | 21       | 0.43%   |
| Maxtor STM3250310AS 250GB        | 21       | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB         | 20       | 0.41%   |
| Seagate M3 Portable 4TB          | 20       | 0.41%   |
| Phison Sabrent 1TB               | 20       | 0.41%   |
| WDC WD30EFRX-68EUZN0 3TB         | 18       | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 18       | 0.37%   |
| Unknown SD/MMC/MS PRO 2GB        | 18       | 0.37%   |
| Seagate Expansion 240GB          | 18       | 0.37%   |
| SanDisk SSD PLUS 240GB           | 18       | 0.37%   |
| Samsung SSD 850 PRO 256GB        | 18       | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 852      | 1397   | 37.3%   |
| WDC                 | 741      | 1196   | 32.44%  |
| Toshiba             | 184      | 292    | 8.06%   |
| Maxtor              | 171      | 233    | 7.49%   |
| Hitachi             | 151      | 205    | 6.61%   |
| Samsung Electronics | 94       | 118    | 4.12%   |
| HGST                | 27       | 43     | 1.18%   |
| Unknown             | 25       | 33     | 1.09%   |
| Fujitsu             | 9        | 10     | 0.39%   |
| SABRENT             | 4        | 4      | 0.18%   |
| ASMT                | 4        | 4      | 0.18%   |
| USB3.0              | 3        | 4      | 0.13%   |
| WD MediaMax         | 2        | 2      | 0.09%   |
| IBM/Hitachi         | 2        | 2      | 0.09%   |
| HGST HTS            | 2        | 2      | 0.09%   |
| Hewlett-Packard     | 2        | 3      | 0.09%   |
| Apple               | 2        | 2      | 0.09%   |
| USB 3.0             | 1        | 2      | 0.04%   |
| USB                 | 1        | 1      | 0.04%   |
| Promise             | 1        | 1      | 0.04%   |
| PI-041              | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| Intenso             | 1        | 3      | 0.04%   |
| FC-1307             | 1        | 2      | 0.04%   |
| Config              | 1        | 1      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 402      | 584    | 27.4%   |
| Kingston            | 285      | 401    | 19.43%  |
| Crucial             | 230      | 309    | 15.68%  |
| SanDisk             | 113      | 171    | 7.7%    |
| WDC                 | 60       | 84     | 4.09%   |
| China               | 33       | 36     | 2.25%   |
| Toshiba             | 26       | 32     | 1.77%   |
| SPCC                | 25       | 30     | 1.7%    |
| Corsair             | 22       | 36     | 1.5%    |
| Intenso             | 21       | 28     | 1.43%   |
| OCZ                 | 20       | 22     | 1.36%   |
| A-DATA Technology   | 17       | 26     | 1.16%   |
| PNY                 | 16       | 21     | 1.09%   |
| Transcend           | 15       | 21     | 1.02%   |
| KingDian            | 15       | 16     | 1.02%   |
| Patriot             | 14       | 17     | 0.95%   |
| Intel               | 12       | 17     | 0.82%   |
| GOODRAM             | 9        | 14     | 0.61%   |
| Team                | 8        | 13     | 0.55%   |
| TCSUNBOW            | 8        | 9      | 0.55%   |
| Micron Technology   | 8        | 9      | 0.55%   |
| Drevo               | 7        | 7      | 0.48%   |
| Dogfish             | 7        | 10     | 0.48%   |
| Unknown             | 6        | 7      | 0.41%   |
| LITEONIT            | 6        | 6      | 0.41%   |
| Verbatim            | 4        | 4      | 0.27%   |
| TO Exter            | 4        | 4      | 0.27%   |
| Plextor             | 4        | 8      | 0.27%   |
| LITEON              | 4        | 5      | 0.27%   |
| Lexar               | 4        | 5      | 0.27%   |
| BAITITON            | 4        | 4      | 0.27%   |
| SK hynix            | 3        | 3      | 0.2%    |
| Netac               | 3        | 3      | 0.2%    |
| KIOXIA-EXCERIA      | 3        | 3      | 0.2%    |
| KingSpec            | 3        | 4      | 0.2%    |
| JMicron Technology  | 3        | 3      | 0.2%    |
| Gigabyte Technology | 3        | 9      | 0.2%    |
| Apacer              | 3        | 3      | 0.2%    |
| S3+                 | 2        | 4      | 0.14%   |
| Inateck             | 2        | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1747     | 3564   | 50.07%  |
| SSD     | 1222     | 2027   | 35.02%  |
| NVMe    | 422      | 614    | 12.1%   |
| Unknown | 77       | 101    | 2.21%   |
| MMC     | 21       | 26     | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2194     | 5495   | 78.75%  |
| NVMe | 419      | 607    | 15.04%  |
| SAS  | 152      | 204    | 5.46%   |
| MMC  | 21       | 26     | 0.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1805     | 3385   | 57.87%  |
| 0.51-1.0   | 803      | 1296   | 25.75%  |
| 1.01-2.0   | 279      | 490    | 8.95%   |
| 2.01-3.0   | 91       | 150    | 2.92%   |
| 3.01-4.0   | 87       | 154    | 2.79%   |
| 4.01-10.0  | 48       | 105    | 1.54%   |
| 10.01-20.0 | 6        | 11     | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 596      | 23.64%  |
| 251-500        | 426      | 16.9%   |
| 501-1000       | 329      | 13.05%  |
| 1001-2000      | 275      | 10.91%  |
| 1-20           | 227      | 9%      |
| More than 3000 | 185      | 7.34%   |
| 51-100         | 183      | 7.26%   |
| 2001-3000      | 124      | 4.92%   |
| Unknown        | 90       | 3.57%   |
| 21-50          | 86       | 3.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 970      | 37.45%  |
| 21-50          | 355      | 13.71%  |
| 101-250        | 260      | 10.04%  |
| 51-100         | 237      | 9.15%   |
| 501-1000       | 211      | 8.15%   |
| 251-500        | 204      | 7.88%   |
| 1001-2000      | 133      | 5.14%   |
| Unknown        | 90       | 3.47%   |
| More than 3000 | 79       | 3.05%   |
| 2001-3000      | 51       | 1.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 14       | 16     | 4.43%   |
| Seagate ST3500418AS 500GB             | 9        | 13     | 2.85%   |
| Maxtor STM3250310AS 250GB             | 6        | 6      | 1.9%    |
| WDC WD40EFRX-68N32N0 4TB              | 4        | 5      | 1.27%   |
| Unknown MM0500EANCR 500GB             | 4        | 9      | 1.27%   |
| Seagate ST31500341AS 1TB              | 4        | 4      | 1.27%   |
| Seagate ST31000528AS 1TB              | 4        | 7      | 1.27%   |
| Maxtor STM3320820AS 320GB             | 4        | 4      | 1.27%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3        | 4      | 0.95%   |
| Seagate ST3500413AS 500GB             | 3        | 5      | 0.95%   |
| Seagate ST3500320AS 500GB             | 3        | 3      | 0.95%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 7      | 0.95%   |
| Samsung Electronics HD103UJ 1TB       | 3        | 3      | 0.95%   |
| Maxtor 6Y080L0 81GB                   | 3        | 3      | 0.95%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 2        | 2      | 0.63%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.63%   |
| WDC WD40PURZ-85TTDY0 4TB              | 2        | 2      | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.63%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2        | 3      | 0.63%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.63%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.63%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.63%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.63%   |
| Seagate ST9500530NS 500GB             | 2        | 3      | 0.63%   |
| Seagate ST9500325AS 500GB             | 2        | 2      | 0.63%   |
| Seagate ST3500620AS 500GB             | 2        | 2      | 0.63%   |
| Seagate ST3320620AS 320GB             | 2        | 3      | 0.63%   |
| Seagate ST3320613AS 320GB             | 2        | 2      | 0.63%   |
| Seagate ST3250820AS 250GB             | 2        | 3      | 0.63%   |
| Seagate ST3250318AS 249GB             | 2        | 2      | 0.63%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 2      | 0.63%   |
| Seagate ST2000DL003-9VT166 2TB        | 2        | 3      | 0.63%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB        | 2        | 2      | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 0.63%   |
| SanDisk SSD PLUS 480GB                | 2        | 2      | 0.63%   |
| Samsung Electronics SSD 860 EVO 500GB | 2        | 3      | 0.63%   |
| Samsung Electronics HD103SI 1TB       | 2        | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 96       | 132    | 31.79%  |
| WDC                 | 78       | 96     | 25.83%  |
| Maxtor              | 32       | 36     | 10.6%   |
| Hitachi             | 24       | 27     | 7.95%   |
| Samsung Electronics | 21       | 24     | 6.95%   |
| Kingston            | 11       | 11     | 3.64%   |
| Toshiba             | 8        | 8      | 2.65%   |
| Crucial             | 5        | 5      | 1.66%   |
| Unknown             | 4        | 9      | 1.32%   |
| OCZ                 | 3        | 3      | 0.99%   |
| HGST                | 3        | 4      | 0.99%   |
| SanDisk             | 2        | 2      | 0.66%   |
| Intenso             | 2        | 3      | 0.66%   |
| ASMT                | 2        | 2      | 0.66%   |
| WD MediaMax         | 1        | 1      | 0.33%   |
| USB3.0              | 1        | 1      | 0.33%   |
| TCSUNBOW            | 1        | 1      | 0.33%   |
| SK hynix            | 1        | 1      | 0.33%   |
| Micron Technology   | 1        | 1      | 0.33%   |
| LITEONIT            | 1        | 1      | 0.33%   |
| Fujitsu             | 1        | 1      | 0.33%   |
| Drevo               | 1        | 1      | 0.33%   |
| CT1000P1            | 1        | 2      | 0.33%   |
| Corsair             | 1        | 2      | 0.33%   |
| BAITITON            | 1        | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 96       | 132    | 36.36%  |
| WDC                 | 77       | 93     | 29.17%  |
| Maxtor              | 32       | 36     | 12.12%  |
| Hitachi             | 24       | 27     | 9.09%   |
| Samsung Electronics | 15       | 16     | 5.68%   |
| Toshiba             | 8        | 8      | 3.03%   |
| Unknown             | 4        | 9      | 1.52%   |
| HGST                | 3        | 4      | 1.14%   |
| ASMT                | 2        | 2      | 0.76%   |
| WD MediaMax         | 1        | 1      | 0.38%   |
| USB3.0              | 1        | 1      | 0.38%   |
| Fujitsu             | 1        | 1      | 0.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 237      | 330    | 85.87%  |
| SSD  | 35       | 40     | 12.68%  |
| NVMe | 4        | 5      | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 3      | 33.33%  |
| Seagate STM3250318AS 250GB      | 1        | 1      | 16.67%  |
| Seagate ST9500420AS 500GB       | 1        | 1      | 16.67%  |
| Hitachi HTS725050A7E630 500GB   | 1        | 1      | 16.67%  |
| Hitachi HTS543216L9A300 160GB   | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| Hitachi | 2        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1468     | 3776   | 55.8%   |
| Works    | 891      | 2174   | 33.87%  |
| Malfunc  | 266      | 375    | 10.11%  |
| Failed   | 6        | 7      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1537     | 48.2%   |
| AMD                              | 624      | 19.57%  |
| Samsung Electronics              | 182      | 5.71%   |
| JMicron Technology               | 120      | 3.76%   |
| Nvidia                           | 119      | 3.73%   |
| Marvell Technology Group         | 115      | 3.61%   |
| ASMedia Technology               | 113      | 3.54%   |
| Phison Electronics               | 72       | 2.26%   |
| Micron/Crucial Technology        | 57       | 1.79%   |
| SanDisk                          | 49       | 1.54%   |
| VIA Technologies                 | 47       | 1.47%   |
| Kingston Technology Company      | 27       | 0.85%   |
| Silicon Motion                   | 19       | 0.6%    |
| Adaptec                          | 15       | 0.47%   |
| Micron Technology                | 11       | 0.34%   |
| ADATA Technology                 | 10       | 0.31%   |
| Silicon Image                    | 9        | 0.28%   |
| SK hynix                         | 8        | 0.25%   |
| Silicon Integrated Systems [SiS] | 8        | 0.25%   |
| Toshiba America Info Systems     | 7        | 0.22%   |
| Broadcom / LSI                   | 7        | 0.22%   |
| LSI Logic / Symbios Logic        | 5        | 0.16%   |
| Realtek Semiconductor            | 4        | 0.13%   |
| Promise Technology               | 3        | 0.09%   |
| Broadcom                         | 3        | 0.09%   |
| ULi Electronics                  | 2        | 0.06%   |
| Seagate Technology               | 2        | 0.06%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.06%   |
| KIOXIA                           | 2        | 0.06%   |
| Integrated Technology Express    | 2        | 0.06%   |
| INNOGRIT                         | 2        | 0.06%   |
| HighPoint Technologies           | 2        | 0.06%   |
| Shenzhen Longsys Electronics     | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| Initio                           | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 340      | 8.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 160      | 3.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 145      | 3.46%   |
| AMD 400 Series Chipset SATA Controller                                                  | 138      | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 123      | 2.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 115      | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 114      | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 114      | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 106      | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 102      | 2.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 101      | 2.41%   |
| Intel SATA Controller [RAID mode]                                                       | 99       | 2.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 88       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 84       | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 72       | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 66       | 1.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 65       | 1.55%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 55       | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                                  | 53       | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 51       | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 51       | 1.22%   |
| Phison E12 NVMe Controller                                                              | 50       | 1.19%   |
| Nvidia MCP61 SATA Controller                                                            | 48       | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 48       | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 45       | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 43       | 1.02%   |
| Nvidia MCP61 IDE                                                                        | 41       | 0.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 36       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 36       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 35       | 0.83%   |
| Samsung NVMe SSD Controller 980                                                         | 34       | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 33       | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 32       | 0.76%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 31       | 0.74%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 30       | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 30       | 0.71%   |
| AMD FCH SATA Controller D                                                               | 29       | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 28       | 0.67%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 28       | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 27       | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1652     | 52.75%  |
| IDE  | 846      | 27.01%  |
| NVMe | 425      | 13.57%  |
| RAID | 191      | 6.1%    |
| SAS  | 9        | 0.29%   |
| SCSI | 9        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1622     | 69.14%  |
| AMD          | 723      | 30.82%  |
| CentaurHauls | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 43       | 1.83%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 37       | 1.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 35       | 1.49%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 33       | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 27       | 1.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 26       | 1.1%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 25       | 1.06%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz                 | 22       | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 22       | 0.93%   |
| AMD FX-8350 Eight-Core Processor            | 21       | 0.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 20       | 0.85%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 19       | 0.81%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 19       | 0.81%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 18       | 0.76%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.72%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 17       | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 16       | 0.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 16       | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 16       | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 15       | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15       | 0.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 15       | 0.64%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 15       | 0.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 15       | 0.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.64%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 15       | 0.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 15       | 0.64%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 0.64%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 14       | 0.59%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 14       | 0.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 14       | 0.59%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 14       | 0.59%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 14       | 0.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 14       | 0.59%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 13       | 0.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 13       | 0.55%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 13       | 0.55%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 13       | 0.55%   |
| AMD FX-8320 Eight-Core Processor            | 13       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 426      | 18.09%  |
| Intel Core i7           | 307      | 13.04%  |
| Intel Core i3           | 161      | 6.84%   |
| AMD Ryzen 5             | 155      | 6.58%   |
| AMD Ryzen 7             | 107      | 4.54%   |
| Intel Core 2 Quad       | 101      | 4.29%   |
| Intel Core 2 Duo        | 98       | 4.16%   |
| Intel Celeron           | 82       | 3.48%   |
| Intel Xeon              | 79       | 3.35%   |
| Intel Pentium Dual-Core | 73       | 3.1%    |
| AMD FX                  | 66       | 2.8%    |
| Intel Pentium           | 64       | 2.72%   |
| Intel Pentium 4         | 59       | 2.51%   |
| AMD Athlon 64 X2        | 47       | 2%      |
| AMD Ryzen 9             | 40       | 1.7%    |
| Intel Core 2            | 37       | 1.57%   |
| AMD Ryzen 3             | 34       | 1.44%   |
| Other                   | 29       | 1.23%   |
| Intel Pentium Dual      | 29       | 1.23%   |
| Intel Atom              | 28       | 1.19%   |
| AMD Phenom II X4        | 28       | 1.19%   |
| AMD A8                  | 27       | 1.15%   |
| Intel Pentium D         | 24       | 1.02%   |
| Intel Core i9           | 22       | 0.93%   |
| AMD Sempron             | 19       | 0.81%   |
| AMD Phenom II X6        | 19       | 0.81%   |
| AMD Athlon II X2        | 18       | 0.76%   |
| AMD Athlon II X4        | 15       | 0.64%   |
| AMD A10                 | 15       | 0.64%   |
| AMD Phenom              | 14       | 0.59%   |
| AMD A4                  | 14       | 0.59%   |
| AMD A6                  | 13       | 0.55%   |
| AMD Athlon 64           | 12       | 0.51%   |
| AMD Six-Core Opteron    | 11       | 0.47%   |
| AMD Athlon II X3        | 10       | 0.42%   |
| AMD Athlon              | 10       | 0.42%   |
| AMD Athlon X4           | 7        | 0.3%    |
| AMD Ryzen Threadripper  | 6        | 0.25%   |
| AMD Ryzen 5 PRO         | 4        | 0.17%   |
| AMD Quad-Core Opteron   | 4        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 978      | 41.56%  |
| 2       | 680      | 28.9%   |
| 6       | 276      | 11.73%  |
| 8       | 181      | 7.69%   |
| 1       | 124      | 5.27%   |
| 12      | 43       | 1.83%   |
| 3       | 31       | 1.32%   |
| 16      | 18       | 0.76%   |
| 10      | 14       | 0.59%   |
| 24      | 4        | 0.17%   |
| 64      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |
| 5       | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2310     | 98.47%  |
| 2      | 36       | 1.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1279     | 54.45%  |
| 2       | 1069     | 45.51%  |
| Unknown | 1        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2306     | 98.04%  |
| Unknown        | 25       | 1.06%   |
| 32-bit         | 21       | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 486      | 19.98%  |
| 0x306c3    | 185      | 7.6%    |
| 0x206a7    | 141      | 5.8%    |
| 0x1067a    | 137      | 5.63%   |
| 0x306a9    | 124      | 5.1%    |
| 0x506e3    | 86       | 3.53%   |
| 0x08701021 | 83       | 3.41%   |
| 0x906e9    | 60       | 2.47%   |
| 0x6fb      | 56       | 2.3%    |
| 0x906ea    | 51       | 2.1%    |
| 0x0800820d | 39       | 1.6%    |
| 0x010000c8 | 37       | 1.52%   |
| 0x6fd      | 34       | 1.4%    |
| 0x06000852 | 34       | 1.4%    |
| 0x106e5    | 28       | 1.15%   |
| 0x10676    | 28       | 1.15%   |
| 0x6f6      | 26       | 1.07%   |
| 0x906ed    | 25       | 1.03%   |
| 0x08701013 | 25       | 1.03%   |
| 0x06001119 | 25       | 1.03%   |
| 0x08108109 | 23       | 0.95%   |
| 0x106a5    | 22       | 0.9%    |
| 0xa0655    | 21       | 0.86%   |
| 0xa0653    | 21       | 0.86%   |
| 0x0a201016 | 21       | 0.86%   |
| 0x20655    | 19       | 0.78%   |
| 0x10677    | 19       | 0.78%   |
| 0x0a50000c | 18       | 0.74%   |
| 0x08001138 | 17       | 0.7%    |
| 0xf43      | 16       | 0.66%   |
| 0x20652    | 16       | 0.66%   |
| 0x03000027 | 16       | 0.66%   |
| 0xa0671    | 15       | 0.62%   |
| 0x30678    | 15       | 0.62%   |
| 0x010000dc | 15       | 0.62%   |
| 0x306f2    | 14       | 0.58%   |
| 0xf49      | 13       | 0.53%   |
| 0x406c4    | 13       | 0.53%   |
| 0x0810100b | 13       | 0.53%   |
| 0x06003106 | 13       | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 235      | 9.98%   |
| Penryn           | 212      | 9%      |
| KabyLake         | 196      | 8.32%   |
| SandyBridge      | 181      | 7.69%   |
| IvyBridge        | 152      | 6.45%   |
| Core             | 147      | 6.24%   |
| K10              | 136      | 5.77%   |
| Zen 2            | 127      | 5.39%   |
| Skylake          | 113      | 4.8%    |
| NetBurst         | 90       | 3.82%   |
| Piledriver       | 84       | 3.57%   |
| Zen+             | 79       | 3.35%   |
| Zen 3            | 75       | 3.18%   |
| K8 Hammer        | 73       | 3.1%    |
| Zen              | 71       | 3.01%   |
| Nehalem          | 66       | 2.8%    |
| CometLake        | 58       | 2.46%   |
| Westmere         | 55       | 2.34%   |
| Silvermont       | 47       | 2%      |
| K10 Llano        | 20       | 0.85%   |
| Steamroller      | 19       | 0.81%   |
| Goldmont plus    | 17       | 0.72%   |
| Goldmont         | 15       | 0.64%   |
| Bonnell          | 14       | 0.59%   |
| Excavator        | 12       | 0.51%   |
| Icelake          | 11       | 0.47%   |
| Bulldozer        | 10       | 0.42%   |
| Alderlake Hybrid | 10       | 0.42%   |
| Unknown          | 9        | 0.38%   |
| Jaguar           | 8        | 0.34%   |
| Puma             | 6        | 0.25%   |
| Bobcat           | 5        | 0.21%   |
| K6               | 1        | 0.04%   |
| Broadwell        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1028     | 42.04%  |
| AMD                                          | 728      | 29.78%  |
| Intel                                        | 661      | 27.03%  |
| VIA Technologies                             | 10       | 0.41%   |
| Matrox Electronics Systems                   | 7        | 0.29%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.2%    |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.12%   |
| ASPEED Technology                            | 3        | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90       | 3.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 88       | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80       | 3.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 66       | 2.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 65       | 2.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 58       | 2.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 53       | 2.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51       | 2.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 34       | 1.35%   |
| Intel HD Graphics 530                                                                    | 34       | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 33       | 1.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 33       | 1.31%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 33       | 1.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 31       | 1.23%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 29       | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 28       | 1.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27       | 1.07%   |
| Intel HD Graphics 630                                                                    | 26       | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26       | 1.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 26       | 1.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 25       | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25       | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25       | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 23       | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23       | 0.91%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 22       | 0.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 21       | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 20       | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19       | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 19       | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 18       | 0.72%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 18       | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 18       | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 17       | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 17       | 0.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17       | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 16       | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 16       | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 15       | 0.6%    |
| Nvidia GK208B [GeForce GT 720]                                                           | 15       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 987      | 41.77%  |
| 1 x AMD              | 654      | 27.68%  |
| 1 x Intel            | 595      | 25.18%  |
| 2 x AMD              | 47       | 1.99%   |
| Intel + Nvidia       | 19       | 0.8%    |
| AMD + Nvidia         | 15       | 0.63%   |
| 1 x VIA              | 10       | 0.42%   |
| Intel + AMD          | 8        | 0.34%   |
| 1 x SiS              | 5        | 0.21%   |
| 2 x Nvidia           | 4        | 0.17%   |
| Other                | 3        | 0.13%   |
| 1 x XGI              | 3        | 0.13%   |
| Nvidia + Matrox      | 3        | 0.13%   |
| 1 x Matrox           | 3        | 0.13%   |
| 1 x ASPEED           | 3        | 0.13%   |
| 3 x AMD              | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD      | 1        | 0.04%   |
| AMD + Matrox         | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1793     | 74.74%  |
| Proprietary | 527      | 21.97%  |
| Unknown     | 79       | 3.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 891      | 36.67%  |
| 1.01-2.0   | 377      | 15.51%  |
| 0.01-0.5   | 351      | 14.44%  |
| 0.51-1.0   | 339      | 13.95%  |
| 3.01-4.0   | 182      | 7.49%   |
| 7.01-8.0   | 139      | 5.72%   |
| 5.01-6.0   | 88       | 3.62%   |
| 2.01-3.0   | 34       | 1.4%    |
| 8.01-16.0  | 27       | 1.11%   |
| 4.01-5.0   | 1        | 0.04%   |
| 16.01-24.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 494      | 20.46%  |
| Hewlett-Packard         | 241      | 9.98%   |
| Goldstar                | 235      | 9.73%   |
| Philips                 | 227      | 9.4%    |
| Ancor Communications    | 208      | 8.62%   |
| Acer                    | 179      | 7.42%   |
| BenQ                    | 112      | 4.64%   |
| Dell                    | 108      | 4.47%   |
| AOC                     | 91       | 3.77%   |
| Lenovo                  | 38       | 1.57%   |
| HannStar                | 37       | 1.53%   |
| LG Electronics          | 36       | 1.49%   |
| Unknown                 | 34       | 1.41%   |
| Sony                    | 30       | 1.24%   |
| ASUSTek Computer        | 28       | 1.16%   |
| Fujitsu Siemens         | 15       | 0.62%   |
| Eizo                    | 15       | 0.62%   |
| Packard Bell            | 11       | 0.46%   |
| MSI                     | 11       | 0.46%   |
| Mi                      | 10       | 0.41%   |
| NEC Computers           | 9        | 0.37%   |
| Belinea                 | 9        | 0.37%   |
| Sharp                   | 8        | 0.33%   |
| HPN                     | 8        | 0.33%   |
| CVT                     | 8        | 0.33%   |
| ViewSonic               | 7        | 0.29%   |
| Vestel Elektronik       | 7        | 0.29%   |
| MiTAC                   | 7        | 0.29%   |
| Panasonic               | 6        | 0.25%   |
| OEM                     | 6        | 0.25%   |
| HannStar Display        | 6        | 0.25%   |
| ___                     | 5        | 0.21%   |
| QBell                   | 5        | 0.21%   |
| Microstep               | 5        | 0.21%   |
| Lenovo Group Limited    | 5        | 0.21%   |
| Hyundai ImageQuest      | 5        | 0.21%   |
| Chi Mei Optoelectronics | 5        | 0.21%   |
| Unknown (XXX)           | 4        | 0.17%   |
| RTK                     | 4        | 0.17%   |
| Iiyama                  | 4        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 21       | 0.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 17       | 0.66%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 17       | 0.66%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 14       | 0.55%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 12       | 0.47%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 12       | 0.47%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 11       | 0.43%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 11       | 0.43%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 11       | 0.43%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 9        | 0.35%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 9        | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 8        | 0.31%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 8        | 0.31%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 8        | 0.31%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 8        | 0.31%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 8        | 0.31%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 8        | 0.31%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 7        | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 0.27%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 7        | 0.27%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch     | 7        | 0.27%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 7        | 0.27%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch             | 7        | 0.27%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 7        | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 7        | 0.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 7        | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 7        | 0.27%   |
| Dell 2009W DEL4042 1680x1050 433x270mm 20.1-inch                      | 7        | 0.27%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 7        | 0.27%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 7        | 0.27%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 6        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 6        | 0.23%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 6        | 0.23%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                    | 6        | 0.23%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 337x270mm 17.0-inch           | 6        | 0.23%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 6        | 0.23%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 6        | 0.23%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 6        | 0.23%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 6        | 0.23%   |
| Ancor Communications VW222 ACI22A2 1680x1050 473x296mm 22.0-inch      | 6        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1123     | 47.34%  |
| 1280x1024 (SXGA)   | 267      | 11.26%  |
| 3840x2160 (4K)     | 157      | 6.62%   |
| 1680x1050 (WSXGA+) | 155      | 6.53%   |
| 1440x900 (WXGA+)   | 143      | 6.03%   |
| 2560x1440 (QHD)    | 106      | 4.47%   |
| 1366x768 (WXGA)    | 59       | 2.49%   |
| Unknown            | 51       | 2.15%   |
| 1360x768           | 50       | 2.11%   |
| 1920x1200 (WUXGA)  | 39       | 1.64%   |
| 1600x900 (HD+)     | 38       | 1.6%    |
| 2560x1080          | 34       | 1.43%   |
| 1024x768 (XGA)     | 28       | 1.18%   |
| 3840x1080          | 24       | 1.01%   |
| 3440x1440          | 17       | 0.72%   |
| 1600x1200          | 12       | 0.51%   |
| 1920x540           | 10       | 0.42%   |
| 1280x720 (HD)      | 8        | 0.34%   |
| 1280x768           | 4        | 0.17%   |
| 4480x1440          | 3        | 0.13%   |
| 3200x1080          | 3        | 0.13%   |
| 2560x1600          | 3        | 0.13%   |
| 2288x1287          | 3        | 0.13%   |
| 8960x2160          | 2        | 0.08%   |
| 5760x1080          | 2        | 0.08%   |
| 5120x1440          | 2        | 0.08%   |
| 2640x1024          | 2        | 0.08%   |
| 2304x1024          | 2        | 0.08%   |
| 1818x1022          | 2        | 0.08%   |
| 6784x2160          | 1        | 0.04%   |
| 5760x2160          | 1        | 0.04%   |
| 5520x2160          | 1        | 0.04%   |
| 4480x1080          | 1        | 0.04%   |
| 4093x4093          | 1        | 0.04%   |
| 3968x1152          | 1        | 0.04%   |
| 3840x1920          | 1        | 0.04%   |
| 3840x1600          | 1        | 0.04%   |
| 3840x1200          | 1        | 0.04%   |
| 3520x1080          | 1        | 0.04%   |
| 3360x1080          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 317      | 13.11%  |
| 24      | 309      | 12.78%  |
| 27      | 302      | 12.49%  |
| Unknown | 289      | 11.95%  |
| 23      | 229      | 9.47%   |
| 19      | 225      | 9.31%   |
| 17      | 128      | 5.29%   |
| 18      | 110      | 4.55%   |
| 22      | 85       | 3.52%   |
| 20      | 83       | 3.43%   |
| 31      | 52       | 2.15%   |
| 34      | 50       | 2.07%   |
| 15      | 39       | 1.61%   |
| 40      | 28       | 1.16%   |
| 84      | 21       | 0.87%   |
| 54      | 20       | 0.83%   |
| 72      | 18       | 0.74%   |
| 25      | 13       | 0.54%   |
| 32      | 11       | 0.45%   |
| 28      | 8        | 0.33%   |
| 52      | 7        | 0.29%   |
| 48      | 7        | 0.29%   |
| 42      | 7        | 0.29%   |
| 47      | 6        | 0.25%   |
| 39      | 4        | 0.17%   |
| 37      | 4        | 0.17%   |
| 33      | 4        | 0.17%   |
| 29      | 4        | 0.17%   |
| 26      | 4        | 0.17%   |
| 142     | 3        | 0.12%   |
| 60      | 3        | 0.12%   |
| 50      | 3        | 0.12%   |
| 46      | 3        | 0.12%   |
| 43      | 3        | 0.12%   |
| 14      | 3        | 0.12%   |
| 12      | 3        | 0.12%   |
| 16      | 2        | 0.08%   |
| 75      | 1        | 0.04%   |
| 74      | 1        | 0.04%   |
| 65      | 1        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 779      | 32.99%  |
| 401-500        | 679      | 28.76%  |
| Unknown        | 289      | 12.24%  |
| 301-350        | 162      | 6.86%   |
| 351-400        | 143      | 6.06%   |
| 601-700        | 92       | 3.9%    |
| 701-800        | 65       | 2.75%   |
| 1001-1500      | 55       | 2.33%   |
| 1501-2000      | 41       | 1.74%   |
| 801-900        | 37       | 1.57%   |
| 901-1000       | 10       | 0.42%   |
| 201-300        | 5        | 0.21%   |
| More than 2000 | 3        | 0.13%   |
| 101-200        | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1340     | 58.31%  |
| 16/10   | 328      | 14.27%  |
| 5/4     | 253      | 11.01%  |
| Unknown | 247      | 10.75%  |
| 4/3     | 55       | 2.39%   |
| 21/9    | 48       | 2.09%   |
| 6/5     | 9        | 0.39%   |
| 3/2     | 9        | 0.39%   |
| 32/9    | 5        | 0.22%   |
| 1.00    | 3        | 0.13%   |
| 2.65    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 748      | 31.51%  |
| 151-200        | 430      | 18.11%  |
| 301-350        | 306      | 12.89%  |
| Unknown        | 289      | 12.17%  |
| 141-150        | 185      | 7.79%   |
| 351-500        | 117      | 4.93%   |
| 251-300        | 99       | 4.17%   |
| More than 1000 | 86       | 3.62%   |
| 501-1000       | 65       | 2.74%   |
| 101-110        | 37       | 1.56%   |
| 131-140        | 4        | 0.17%   |
| 71-80          | 3        | 0.13%   |
| 91-100         | 2        | 0.08%   |
| 81-90          | 1        | 0.04%   |
| 1-40           | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1441     | 62.35%  |
| 101-120       | 411      | 17.78%  |
| Unknown       | 289      | 12.51%  |
| 1-50          | 84       | 3.63%   |
| 121-160       | 51       | 2.21%   |
| 161-240       | 34       | 1.47%   |
| More than 240 | 1        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1998     | 83.98%  |
| 2     | 265      | 11.14%  |
| 0     | 90       | 3.78%   |
| 3     | 26       | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1419     | 42.7%   |
| Intel                            | 825      | 24.83%  |
| Qualcomm Atheros                 | 228      | 6.86%   |
| Broadcom                         | 99       | 2.98%   |
| Nvidia                           | 96       | 2.89%   |
| TP-Link                          | 81       | 2.44%   |
| Ralink Technology                | 77       | 2.32%   |
| Marvell Technology Group         | 60       | 1.81%   |
| Ralink                           | 40       | 1.2%    |
| Qualcomm Atheros Communications  | 36       | 1.08%   |
| Broadcom Limited                 | 34       | 1.02%   |
| D-Link System                    | 32       | 0.96%   |
| VIA Technologies                 | 27       | 0.81%   |
| Huawei Technologies              | 25       | 0.75%   |
| D-Link                           | 24       | 0.72%   |
| Sitecom Europe                   | 21       | 0.63%   |
| NetGear                          | 20       | 0.6%    |
| Xiaomi                           | 18       | 0.54%   |
| Samsung Electronics              | 16       | 0.48%   |
| ASUSTek Computer                 | 16       | 0.48%   |
| MediaTek                         | 12       | 0.36%   |
| Microsoft                        | 11       | 0.33%   |
| Gemtek                           | 9        | 0.27%   |
| Belkin Components                | 7        | 0.21%   |
| ASIX Electronics                 | 7        | 0.21%   |
| Aquantia                         | 7        | 0.21%   |
| Silicon Integrated Systems [SiS] | 6        | 0.18%   |
| Linksys                          | 5        | 0.15%   |
| DisplayLink                      | 5        | 0.15%   |
| AVM                              | 5        | 0.15%   |
| 3Com                             | 5        | 0.15%   |
| OPPO Electronics                 | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)    | 3        | 0.09%   |
| Motorola                         | 3        | 0.09%   |
| Microchip Technology             | 3        | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| Smart Link                       | 2        | 0.06%   |
| Qualcomm                         | 2        | 0.06%   |
| Google                           | 2        | 0.06%   |
| Exar                             | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1141     | 30.83%  |
| Intel Ethernet Connection (2) I219-V                              | 100      | 2.7%    |
| Intel I211 Gigabit Network Connection                             | 97       | 2.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 86       | 2.32%   |
| Intel Wi-Fi 6 AX200                                               | 82       | 2.22%   |
| Intel 82579V Gigabit Network Connection                           | 60       | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48       | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42       | 1.13%   |
| Nvidia MCP61 Ethernet                                             | 39       | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 38       | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                   | 35       | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 35       | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 34       | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 32       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 32       | 0.86%   |
| Realtek 802.11ac NIC                                              | 31       | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 0.76%   |
| Intel Wireless 7265                                               | 27       | 0.73%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22       | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 22       | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 22       | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 21       | 0.57%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 21       | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 20       | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 18       | 0.49%   |
| Intel Wireless-AC 9260                                            | 18       | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18       | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17       | 0.46%   |
| Nvidia MCP77 Ethernet                                             | 16       | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.43%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 16       | 0.43%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 15       | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 293      | 27.33%  |
| Intel                                 | 234      | 21.83%  |
| Qualcomm Atheros                      | 116      | 10.82%  |
| TP-Link                               | 79       | 7.37%   |
| Ralink Technology                     | 77       | 7.18%   |
| Ralink                                | 40       | 3.73%   |
| Broadcom                              | 37       | 3.45%   |
| Qualcomm Atheros Communications       | 36       | 3.36%   |
| D-Link System                         | 24       | 2.24%   |
| D-Link                                | 24       | 2.24%   |
| Sitecom Europe                        | 21       | 1.96%   |
| NetGear                               | 19       | 1.77%   |
| ASUSTek Computer                      | 15       | 1.4%    |
| Microsoft                             | 10       | 0.93%   |
| Gemtek                                | 9        | 0.84%   |
| Belkin Components                     | 7        | 0.65%   |
| Broadcom Limited                      | 6        | 0.56%   |
| MediaTek                              | 5        | 0.47%   |
| Linksys                               | 5        | 0.47%   |
| AVM                                   | 5        | 0.47%   |
| Edimax Technology                     | 2        | 0.19%   |
| ZyXEL Communications                  | 1        | 0.09%   |
| ZyDAS                                 | 1        | 0.09%   |
| Wilocity                              | 1        | 0.09%   |
| Wacom                                 | 1        | 0.09%   |
| Samsung Electronics                   | 1        | 0.09%   |
| Fiberline                             | 1        | 0.09%   |
| AboCom Systems                        | 1        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 82       | 7.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 35       | 3.22%   |
| Qualcomm Atheros AR9271 802.11n                                            | 35       | 3.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 32       | 2.95%   |
| Realtek 802.11ac NIC                                                       | 31       | 2.85%   |
| Intel Wireless 7265                                                        | 27       | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 22       | 2.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 22       | 2.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 22       | 2.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 21       | 1.93%   |
| Ralink MT7601U Wireless Adapter                                            | 20       | 1.84%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 18       | 1.66%   |
| Intel Wireless-AC 9260                                                     | 18       | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 18       | 1.66%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 16       | 1.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 15       | 1.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 15       | 1.38%   |
| Ralink RT5370 Wireless Adapter                                             | 14       | 1.29%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 13       | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 13       | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 13       | 1.2%    |
| Intel Wireless 3165                                                        | 13       | 1.2%    |
| Intel Wireless 7260                                                        | 12       | 1.1%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 11       | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 11       | 1.01%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 11       | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 11       | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 10       | 0.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 10       | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 10       | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 10       | 0.92%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]         | 10       | 0.92%   |
| TP-Link 802.11ac WLAN Adapter                                              | 9        | 0.83%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                   | 9        | 0.83%   |
| Realtek RTL8187 Wireless Adapter                                           | 9        | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 9        | 0.83%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 9        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 9        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 9        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 9        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1318     | 51.99%  |
| Intel                             | 689      | 27.18%  |
| Qualcomm Atheros                  | 130      | 5.13%   |
| Nvidia                            | 96       | 3.79%   |
| Broadcom                          | 64       | 2.52%   |
| Marvell Technology Group          | 60       | 2.37%   |
| Broadcom Limited                  | 28       | 1.1%    |
| VIA Technologies                  | 26       | 1.03%   |
| Huawei Technologies               | 23       | 0.91%   |
| Xiaomi                            | 18       | 0.71%   |
| Samsung Electronics               | 15       | 0.59%   |
| D-Link System                     | 8        | 0.32%   |
| MediaTek                          | 7        | 0.28%   |
| ASIX Electronics                  | 7        | 0.28%   |
| Aquantia                          | 7        | 0.28%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.24%   |
| DisplayLink                       | 5        | 0.2%    |
| 3Com                              | 5        | 0.2%    |
| OPPO Electronics                  | 3        | 0.12%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.08%   |
| TP-Link                           | 2        | 0.08%   |
| Qualcomm                          | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.08%   |
| Google                            | 2        | 0.08%   |
| ULi Electronics                   | 1        | 0.04%   |
| SysKonnect                        | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| NetGear                           | 1        | 0.04%   |
| Motorola PCS                      | 1        | 0.04%   |
| LG Electronics                    | 1        | 0.04%   |
| JMicron Technology                | 1        | 0.04%   |
| HTC (High Tech Computer)          | 1        | 0.04%   |
| HMD Global                        | 1        | 0.04%   |
| ASUSTek Computer                  | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1141     | 44.12%  |
| Intel Ethernet Connection (2) I219-V                              | 100      | 3.87%   |
| Intel I211 Gigabit Network Connection                             | 97       | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 86       | 3.33%   |
| Intel 82579V Gigabit Network Connection                           | 60       | 2.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48       | 1.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42       | 1.62%   |
| Nvidia MCP61 Ethernet                                             | 39       | 1.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 1.51%   |
| Intel Ethernet Controller I225-V                                  | 38       | 1.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 35       | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 34       | 1.31%   |
| Intel Ethernet Connection I217-V                                  | 32       | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 32       | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29       | 1.12%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28       | 1.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 21       | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17       | 0.66%   |
| Nvidia MCP77 Ethernet                                             | 16       | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.58%   |
| Nvidia MCP73 Ethernet                                             | 14       | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 14       | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 14       | 0.54%   |
| Intel 82578DM Gigabit Network Connection                          | 13       | 0.5%    |
| Intel 82578DC Gigabit Network Connection                          | 13       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 12       | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12       | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                             | 12       | 0.46%   |
| Huawei ELS-NX9                                                    | 12       | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11       | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10       | 0.39%   |
| Nvidia MCP55 Ethernet                                             | 9        | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 9        | 0.35%   |
| Intel 82567V-2 Gigabit Network Connection                         | 9        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2329     | 69.42%  |
| WiFi     | 998      | 29.75%  |
| Modem    | 25       | 0.75%   |
| Unknown  | 3        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1805     | 75.18%  |
| WiFi     | 595      | 24.78%  |
| Unknown  | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1630     | 69.07%  |
| 2     | 643      | 27.25%  |
| 3     | 66       | 2.8%    |
| 0     | 13       | 0.55%   |
| 4     | 4        | 0.17%   |
| 5     | 2        | 0.08%   |
| 12    | 1        | 0.04%   |
| 6     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2246     | 95.09%  |
| Yes  | 116      | 4.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 207      | 33.77%  |
| Cambridge Silicon Radio         | 185      | 30.18%  |
| Realtek Semiconductor           | 57       | 9.3%    |
| Broadcom                        | 46       | 7.5%    |
| ASUSTek Computer                | 38       | 6.2%    |
| Qualcomm Atheros Communications | 16       | 2.61%   |
| IMC Networks                    | 12       | 1.96%   |
| Apple                           | 11       | 1.79%   |
| Integrated System Solution      | 8        | 1.31%   |
| TP-Link                         | 6        | 0.98%   |
| Lite-On Technology              | 4        | 0.65%   |
| Belkin Components               | 4        | 0.65%   |
| Sitecom Europe                  | 3        | 0.49%   |
| MediaTek                        | 3        | 0.49%   |
| D-Link System                   | 2        | 0.33%   |
| Unknown                         | 1        | 0.16%   |
| Realtek                         | 1        | 0.16%   |
| Logitech                        | 1        | 0.16%   |
| HTC (High Tech Computer)        | 1        | 0.16%   |
| Hewlett-Packard                 | 1        | 0.16%   |
| Fujitsu Siemens Computers       | 1        | 0.16%   |
| Fujitsu                         | 1        | 0.16%   |
| Foxconn / Hon Hai               | 1        | 0.16%   |
| Dell                            | 1        | 0.16%   |
| Conwise Technology              | 1        | 0.16%   |
| 3Com                            | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 185      | 30.13%  |
| Intel AX200 Bluetooth                                     | 70       | 11.4%   |
| Intel Bluetooth wireless interface                        | 57       | 9.28%   |
| Realtek Bluetooth Radio                                   | 38       | 6.19%   |
| Intel Bluetooth Device                                    | 23       | 3.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 19       | 3.09%   |
| Intel Wireless-AC 3168 Bluetooth                          | 18       | 2.93%   |
| Realtek  Bluetooth 4.2 Adapter                            | 17       | 2.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 16       | 2.61%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 12       | 1.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 12       | 1.95%   |
| Broadcom BCM2045 Bluetooth                                | 12       | 1.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 11       | 1.79%   |
| Intel AX210 Bluetooth                                     | 10       | 1.63%   |
| Apple Bluetooth USB Host Controller                       | 7        | 1.14%   |
| TP-Link TPuLink UB500 Adapter                             | 6        | 0.98%   |
| IMC Networks Bluetooth Device                             | 6        | 0.98%   |
| ASUS Bluetooth Radio                                      | 6        | 0.98%   |
| ASUS BCM20702A0                                           | 6        | 0.98%   |
| IMC Networks Bluetooth Radio                              | 5        | 0.81%   |
| ASUS Qualcomm Bluetooth 4.1                               | 5        | 0.81%   |
| ASUS Bluetooth Adapter                                    | 5        | 0.81%   |
| Lite-On Bluetooth Device                                  | 4        | 0.65%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter     | 4        | 0.65%   |
| Integrated System Solution Bluetooth Device               | 4        | 0.65%   |
| MediaTek Wireless_Device                                  | 3        | 0.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 3        | 0.49%   |
| Broadcom BCM2035 Bluetooth dongle                         | 3        | 0.49%   |
| ASUS Bluetooth Device                                     | 3        | 0.49%   |
| Realtek RTL8821A Bluetooth                                | 2        | 0.33%   |
| Qualcomm Atheros  Bluetooth Device                        | 2        | 0.33%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 2        | 0.33%   |
| D-Link System DBT-122 Bluetooth                           | 2        | 0.33%   |
| Broadcom Bluetooth 3.0 Device                             | 2        | 0.33%   |
| Belkin Components F8T012 Bluetooth Adapter                | 2        | 0.33%   |
| Apple Bluetooth HCI                                       | 2        | 0.33%   |
| Unknown Bluetooth Device                                  | 1        | 0.16%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.16%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.16%   |
| Sitecom Europe Bluetooth 2.0 Adapter DFU                  | 1        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1503     | 39.35%  |
| Nvidia                               | 925      | 24.21%  |
| AMD                                  | 894      | 23.4%   |
| C-Media Electronics                  | 111      | 2.91%   |
| Creative Labs                        | 46       | 1.2%    |
| Logitech                             | 35       | 0.92%   |
| VIA Technologies                     | 32       | 0.84%   |
| Texas Instruments                    | 14       | 0.37%   |
| Razer USA                            | 14       | 0.37%   |
| JMTek                                | 14       | 0.37%   |
| Creative Technology                  | 13       | 0.34%   |
| M-Audio                              | 12       | 0.31%   |
| Focusrite-Novation                   | 12       | 0.31%   |
| Kingston Technology                  | 10       | 0.26%   |
| Generalplus Technology               | 9        | 0.24%   |
| Tenx Technology                      | 8        | 0.21%   |
| Silicon Integrated Systems [SiS]     | 8        | 0.21%   |
| ASUSTek Computer                     | 8        | 0.21%   |
| Trust                                | 7        | 0.18%   |
| Micro Star International             | 7        | 0.18%   |
| GN Netcom                            | 7        | 0.18%   |
| Ensoniq                              | 7        | 0.18%   |
| Microsoft                            | 6        | 0.16%   |
| BEHRINGER International              | 6        | 0.16%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.13%   |
| Samson Technologies                  | 5        | 0.13%   |
| Dell                                 | 5        | 0.13%   |
| Yamaha                               | 4        | 0.1%    |
| SAVITECH                             | 4        | 0.1%    |
| Plantronics                          | 4        | 0.1%    |
| XMOS                                 | 3        | 0.08%   |
| Sennheiser Communications            | 3        | 0.08%   |
| Realtek Semiconductor                | 3        | 0.08%   |
| Hewlett-Packard                      | 3        | 0.08%   |
| Corsair                              | 3        | 0.08%   |
| Cambridge Silicon Radio              | 3        | 0.08%   |
| Bose                                 | 3        | 0.08%   |
| Astro Gaming                         | 3        | 0.08%   |
| ZOOM                                 | 2        | 0.05%   |
| ULi Electronics                      | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 175      | 4.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 168      | 3.9%    |
| AMD Starship/Matisse HD Audio Controller                                          | 166      | 3.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 162      | 3.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 156      | 3.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 127      | 2.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 122      | 2.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 103      | 2.39%   |
| Intel 200 Series PCH HD Audio                                                     | 97       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 93       | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 92       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 91       | 2.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 89       | 2.07%   |
| AMD Family 17h/19h HD Audio Controller                                            | 86       | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 85       | 1.97%   |
| Nvidia High Definition Audio Controller                                           | 82       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 82       | 1.9%    |
| AMD FCH Azalia Controller                                                         | 80       | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 76       | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 73       | 1.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 56       | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                     | 54       | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                                     | 52       | 1.21%   |
| Nvidia GF119 HDMI Audio Controller                                                | 50       | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 50       | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 49       | 1.14%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 47       | 1.09%   |
| Nvidia MCP61 High Definition Audio                                                | 46       | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                                     | 45       | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 45       | 1.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 42       | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 40       | 0.93%   |
| AMD Navi 10 HDMI Audio                                                            | 34       | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                                     | 33       | 0.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 33       | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 31       | 0.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 30       | 0.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 30       | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                     | 29       | 0.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 29       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 255      | 19.14%  |
| Unknown                      | 230      | 17.27%  |
| Corsair                      | 197      | 14.79%  |
| Crucial                      | 140      | 10.51%  |
| Samsung Electronics          | 116      | 8.71%   |
| SK hynix                     | 94       | 7.06%   |
| G.Skill                      | 73       | 5.48%   |
| Micron Technology            | 61       | 4.58%   |
| Team                         | 24       | 1.8%    |
| Patriot                      | 20       | 1.5%    |
| A-DATA Technology            | 16       | 1.2%    |
| Nanya Technology             | 14       | 1.05%   |
| Ramaxel Technology           | 13       | 0.98%   |
| Elpida                       | 11       | 0.83%   |
| Unknown                      | 10       | 0.75%   |
| Unknown (ABCD)               | 9        | 0.68%   |
| Transcend                    | 7        | 0.53%   |
| Unifosa                      | 5        | 0.38%   |
| ASint Technology             | 4        | 0.3%    |
| Patriot Memory (PDP Systems) | 3        | 0.23%   |
| GeIL                         | 3        | 0.23%   |
| Unknown (AB)                 | 2        | 0.15%   |
| Silicon Power                | 2        | 0.15%   |
| Qimonda                      | 2        | 0.15%   |
| PLEXHD                       | 2        | 0.15%   |
| Hewlett-Packard              | 2        | 0.15%   |
| GOODRAM                      | 2        | 0.15%   |
| CSX                          | 2        | 0.15%   |
| A Force                      | 2        | 0.15%   |
| V-Color                      | 1        | 0.08%   |
| TwinMOS                      | 1        | 0.08%   |
| Toshiba                      | 1        | 0.08%   |
| Thermaltake                  | 1        | 0.08%   |
| PUSKILL                      | 1        | 0.08%   |
| Netac                        | 1        | 0.08%   |
| KomputerBay                  | 1        | 0.08%   |
| Kllisre                      | 1        | 0.08%   |
| Kingmax                      | 1        | 0.08%   |
| Goldkey                      | 1        | 0.08%   |
| Essencore                    | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 27       | 1.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 20       | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 16       | 1.08%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                  | 13       | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 13       | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 13       | 0.88%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 11       | 0.74%   |
| Unknown                                                      | 10       | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 9        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 9        | 0.61%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                   | 9        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 8        | 0.54%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 8        | 0.54%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 8        | 0.54%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s        | 8        | 0.54%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 7        | 0.47%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 7        | 0.47%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s        | 7        | 0.47%   |
| Unknown RAM Module 512MB DIMM SDRAM                          | 6        | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 6        | 0.41%   |
| Unknown RAM Module 1024MB DIMM                               | 6        | 0.41%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s           | 6        | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 6        | 0.41%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 6        | 0.41%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 6        | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 6        | 0.41%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 6        | 0.41%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 6        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 6        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 5        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 5        | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 5        | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 5        | 0.34%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 5        | 0.34%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 5        | 0.34%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 5        | 0.34%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 5        | 0.34%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s          | 5        | 0.34%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 5        | 0.34%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 5        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 492      | 40.8%   |
| DDR3    | 411      | 34.08%  |
| DDR2    | 121      | 10.03%  |
| SDRAM   | 80       | 6.63%   |
| Unknown | 61       | 5.06%   |
| DDR     | 22       | 1.82%   |
| LPDDR4  | 10       | 0.83%   |
| DDR5    | 5        | 0.41%   |
| LPDDR3  | 4        | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1114     | 95.62%  |
| SODIMM  | 47       | 4.03%   |
| FB-DIMM | 4        | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 461      | 35.35%  |
| 4096  | 315      | 24.16%  |
| 2048  | 242      | 18.56%  |
| 16384 | 147      | 11.27%  |
| 1024  | 86       | 6.6%    |
| 32768 | 27       | 2.07%   |
| 512   | 19       | 1.46%   |
| 256   | 4        | 0.31%   |
| 3072  | 2        | 0.15%   |
| 32    | 1        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 229      | 17.6%   |
| 1333    | 146      | 11.22%  |
| 3600    | 107      | 8.22%   |
| 3200    | 105      | 8.07%   |
| 2400    | 73       | 5.61%   |
| 800     | 72       | 5.53%   |
| 2667    | 48       | 3.69%   |
| 2133    | 46       | 3.54%   |
| 667     | 44       | 3.38%   |
| Unknown | 43       | 3.31%   |
| 1867    | 39       | 3%      |
| 3000    | 28       | 2.15%   |
| 3466    | 25       | 1.92%   |
| 3400    | 22       | 1.69%   |
| 2933    | 22       | 1.69%   |
| 1066    | 19       | 1.46%   |
| 1866    | 17       | 1.31%   |
| 3733    | 16       | 1.23%   |
| 1800    | 16       | 1.23%   |
| 266     | 15       | 1.15%   |
| 400     | 13       | 1%      |
| 1334    | 12       | 0.92%   |
| 2666    | 11       | 0.85%   |
| 3800    | 9        | 0.69%   |
| 2800    | 8        | 0.61%   |
| 533     | 8        | 0.61%   |
| 333     | 7        | 0.54%   |
| 2048    | 6        | 0.46%   |
| 2000    | 6        | 0.46%   |
| 3266    | 5        | 0.38%   |
| 1639    | 5        | 0.38%   |
| 49926   | 4        | 0.31%   |
| 3500    | 4        | 0.31%   |
| 3333    | 4        | 0.31%   |
| 3100    | 4        | 0.31%   |
| 2472    | 4        | 0.31%   |
| 1400    | 4        | 0.31%   |
| 1067    | 4        | 0.31%   |
| 4800    | 3        | 0.23%   |
| 3866    | 3        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 79       | 40.1%   |
| Samsung Electronics   | 27       | 13.71%  |
| Canon                 | 26       | 13.2%   |
| Seiko Epson           | 23       | 11.68%  |
| Brother Industries    | 22       | 11.17%  |
| Lexmark International | 4        | 2.03%   |
| Xerox                 | 2        | 1.02%   |
| Prolific Technology   | 2        | 1.02%   |
| Oki Data              | 2        | 1.02%   |
| Dymo-CoStar           | 2        | 1.02%   |
| Toshiba TEC           | 1        | 0.51%   |
| STMicroelectronics    | 1        | 0.51%   |
| Sato                  | 1        | 0.51%   |
| Ricoh                 | 1        | 0.51%   |
| QinHeng Electronics   | 1        | 0.51%   |
| Pantum                | 1        | 0.51%   |
| Kyocera               | 1        | 0.51%   |
| Apple                 | 1        | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2510 Series                                            | 7        | 3.55%   |
| Samsung M2020 Series                                                  | 7        | 3.55%   |
| HP OfficeJet 6950                                                     | 7        | 3.55%   |
| HP Deskjet 2050 J510                                                  | 5        | 2.54%   |
| Samsung M267x 287x Series                                             | 4        | 2.03%   |
| HP LaserJet 1018                                                      | 4        | 2.03%   |
| HP ENVY 4520 series                                                   | 4        | 2.03%   |
| Canon PIXMA MG3600 Series                                             | 4        | 2.03%   |
| Seiko Epson Printer                                                   | 3        | 1.52%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 3        | 1.52%   |
| Samsung ML-216x Series Laser Printer                                  | 3        | 1.52%   |
| Samsung Composite Device                                              | 3        | 1.52%   |
| HP LaserJet Professional P 1102w                                      | 3        | 1.52%   |
| HP LaserJet P1005                                                     | 3        | 1.52%   |
| HP Deskjet F4500 series                                               | 3        | 1.52%   |
| HP Deskjet 3050A                                                      | 3        | 1.52%   |
| Canon LiDE 400                                                        | 3        | 1.52%   |
| Brother MFC-L2700DW                                                   | 3        | 1.52%   |
| Brother DCP-1610W                                                     | 3        | 1.52%   |
| Seiko Epson ET-2820 Series                                            | 2        | 1.02%   |
| Samsung ML-1660 Series                                                | 2        | 1.02%   |
| Samsung ML-1640 Series Laser Printer                                  | 2        | 1.02%   |
| Prolific PL2305 Parallel Port                                         | 2        | 1.02%   |
| Oki Data USB Device                                                   | 2        | 1.02%   |
| Lexmark International InkJet Color Printer                            | 2        | 1.02%   |
| HP OfficeJet 5200 series                                              | 2        | 1.02%   |
| HP Officejet 4630 series                                              | 2        | 1.02%   |
| HP Officejet 4500 G510n-z                                             | 2        | 1.02%   |
| HP Officejet 2620 series                                              | 2        | 1.02%   |
| HP LaserJet Pro M12a                                                  | 2        | 1.02%   |
| HP LaserJet P1102                                                     | 2        | 1.02%   |
| HP LaserJet 1200                                                      | 2        | 1.02%   |
| HP ENVY 5000 series                                                   | 2        | 1.02%   |
| HP DeskJet F4200 series                                               | 2        | 1.02%   |
| HP Deskjet 3520 series                                                | 2        | 1.02%   |
| HP DeskJet 2130 series                                                | 2        | 1.02%   |
| Canon PIXMA MX920 Series                                              | 2        | 1.02%   |
| Canon PIXMA MG2500 Series                                             | 2        | 1.02%   |
| Canon CanoScan LiDE 300                                               | 2        | 1.02%   |
| Brother MFC-1810                                                      | 2        | 1.02%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 28       | 50.91%  |
| Seiko Epson        | 14       | 25.45%  |
| Hewlett-Packard    | 7        | 12.73%  |
| Mustek Systems     | 4        | 7.27%   |
| Ultima Electronics | 1        | 1.82%   |
| Plustek            | 1        | 1.82%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 6        | 10.91%  |
| Canon CanoScan LiDE 210                                                               | 5        | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 5.45%   |
| Canon CanoScan LiDE 120                                                               | 3        | 5.45%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2        | 3.64%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 3.64%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2        | 3.64%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 3.64%   |
| HP Scanjet 200                                                                        | 2        | 3.64%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.64%   |
| Canon CanoScan LiDE 100                                                               | 2        | 3.64%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.82%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 1.82%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 1.82%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1        | 1.82%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.82%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.82%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 1.82%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1        | 1.82%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.82%   |
| Plustek 600DPI USB Scanner                                                            | 1        | 1.82%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 1.82%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 1.82%   |
| HP ScanJet 3800c                                                                      | 1        | 1.82%   |
| HP ScanJet 3400cse                                                                    | 1        | 1.82%   |
| HP ScanJet 2400c                                                                      | 1        | 1.82%   |
| HP PSC 1200                                                                           | 1        | 1.82%   |
| HP HP4470C                                                                            | 1        | 1.82%   |
| Canon CanoScan LiDE 90                                                                | 1        | 1.82%   |
| Canon CanoScan LiDE 700F                                                              | 1        | 1.82%   |
| Canon CanoScan LiDE 600F                                                              | 1        | 1.82%   |
| Canon CanoScan LiDE 60                                                                | 1        | 1.82%   |
| Canon CanoScan LIDE 25                                                                | 1        | 1.82%   |
| Canon CanoScan LiDE 220                                                               | 1        | 1.82%   |
| Canon CanoScan 4200F                                                                  | 1        | 1.82%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech                                          | 158      | 33.76%  |
| Microdia                                          | 57       | 12.18%  |
| Microsoft                                         | 49       | 10.47%  |
| Sunplus Innovation Technology                     | 22       | 4.7%    |
| ARC International                                 | 15       | 3.21%   |
| Trust                                             | 14       | 2.99%   |
| Samsung Electronics                               | 12       | 2.56%   |
| Generalplus Technology                            | 11       | 2.35%   |
| Chicony Electronics                               | 11       | 2.35%   |
| Cubeternet                                        | 9        | 1.92%   |
| Realtek Semiconductor                             | 7        | 1.5%    |
| KYE Systems (Mouse Systems)                       | 7        | 1.5%    |
| Z-Star Microelectronics                           | 6        | 1.28%   |
| WaveRider Communications                          | 6        | 1.28%   |
| Huawei Technologies                               | 6        | 1.28%   |
| GEMBIRD                                           | 6        | 1.28%   |
| Sunplus IT                                        | 5        | 1.07%   |
| Apple                                             | 5        | 1.07%   |
| 2M UVC CAMERA                                     | 5        | 1.07%   |
| IMC Networks                                      | 4        | 0.85%   |
| Aveo Technology                                   | 4        | 0.85%   |
| MacroSilicon                                      | 3        | 0.64%   |
| Jieli Technology                                  | 3        | 0.64%   |
| Genesys Logic                                     | 3        | 0.64%   |
| Arkmicro Technologies                             | 3        | 0.64%   |
| Xiongmai                                          | 2        | 0.43%   |
| Unknown                                           | 2        | 0.43%   |
| SunplusIT                                         | 2        | 0.43%   |
| Silicon Motion                                    | 2        | 0.43%   |
| Novatel Wireless                                  | 2        | 0.43%   |
| LG Electronics                                    | 2        | 0.43%   |
| Hewlett-Packard                                   | 2        | 0.43%   |
| Creative Technology                               | 2        | 0.43%   |
| TerraTec Electronic                               | 1        | 0.21%   |
| Syntek                                            | 1        | 0.21%   |
| Suyin                                             | 1        | 0.21%   |
| Sunplus Technology                                | 1        | 0.21%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1        | 0.21%   |
| Sonix Technology                                  | 1        | 0.21%   |
| SiGma Micro                                       | 1        | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 45       | 9.53%   |
| Microsoft LifeCam HD-3000                  | 24       | 5.08%   |
| Logitech Webcam C170                       | 22       | 4.66%   |
| Logitech HD Pro Webcam C920                | 18       | 3.81%   |
| ARC International Camera                   | 15       | 3.18%   |
| Microdia Webcam Vitade AF                  | 13       | 2.75%   |
| Samsung Galaxy A5 (MTP)                    | 12       | 2.54%   |
| Microdia USB 2.0 Camera                    | 12       | 2.54%   |
| Microdia Camera                            | 12       | 2.54%   |
| Logitech Webcam C310                       | 11       | 2.33%   |
| Microdia Sonix USB 2.0 Camera              | 10       | 2.12%   |
| Sunplus Aukey-PC-LM1E Camera               | 8        | 1.69%   |
| WaveRider USB 2.0 Camera                   | 6        | 1.27%   |
| Microsoft LifeCam VX-2000                  | 6        | 1.27%   |
| Microdia Laptop_Integrated_Webcam_FHD      | 6        | 1.27%   |
| Logitech QuickCam Pro 9000                 | 6        | 1.27%   |
| Logitech HD Webcam C525                    | 6        | 1.27%   |
| Huawei UVC Camera                          | 6        | 1.27%   |
| Generalplus GENERAL WEBCAM                 | 6        | 1.27%   |
| Trust WB-6250X Webcam                      | 5        | 1.06%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 5        | 1.06%   |
| Logitech HD Webcam C910                    | 5        | 1.06%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam       | 5        | 1.06%   |
| Trust Webcam                               | 4        | 0.85%   |
| Trust 17676 Webcam                         | 4        | 0.85%   |
| Sunplus FHD Camera Microphone              | 4        | 0.85%   |
| Microsoft LifeCam VX-5000                  | 4        | 0.85%   |
| Logitech Webcam C200                       | 4        | 0.85%   |
| Logitech QuickCam E 3500                   | 4        | 0.85%   |
| Logitech C922 Pro Stream Webcam            | 4        | 0.85%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 4        | 0.85%   |
| GEMBIRD USB2.0 PC CAMERA                   | 4        | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE                  | 4        | 0.85%   |
| Sunplus HD 720P webcam                     | 3        | 0.64%   |
| Realtek USB Camera                         | 3        | 0.64%   |
| Microsoft LifeCam VX-700                   | 3        | 0.64%   |
| Microsoft LifeCam HD-5000                  | 3        | 0.64%   |
| Logitech Webcam C210                       | 3        | 0.64%   |
| Logitech StreamCam                         | 3        | 0.64%   |
| Logitech C920 PRO HD Webcam                | 3        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 17       | 36.96%  |
| BIT4ID                    | 6        | 13.04%  |
| Realtek Semiconductor     | 5        | 10.87%  |
| Gemalto (was Gemplus)     | 4        | 8.7%    |
| SCM Microsystems          | 3        | 6.52%   |
| Clay Logic                | 3        | 6.52%   |
| Alcor Micro               | 3        | 6.52%   |
| OmniKey                   | 2        | 4.35%   |
| Reiner SCT Kartensysteme  | 1        | 2.17%   |
| Microchip Technology      | 1        | 2.17%   |
| Fujitsu Siemens Computers | 1        | 2.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 14       | 29.79%  |
| BIT4ID miniLector EVO                                                      | 6        | 12.77%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 10.64%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 8.51%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 6.38%   |
| Advanced Card Systems ACR122U                                              | 3        | 6.38%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 4.26%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 2.13%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 2.13%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.13%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.13%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.13%   |
| OmniKey 3x21 Smart Card Reader                                             | 1        | 2.13%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 2.13%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.13%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 2.13%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2068     | 86.24%  |
| 1     | 286      | 11.93%  |
| 2     | 33       | 1.38%   |
| 3     | 6        | 0.25%   |
| 5     | 3        | 0.13%   |
| 4     | 2        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 107      | 29.08%  |
| Net/wireless             | 99       | 26.9%   |
| Communication controller | 38       | 10.33%  |
| Chipcard                 | 29       | 7.88%   |
| Unassigned class         | 23       | 6.25%   |
| Sound                    | 13       | 3.53%   |
| Camera                   | 11       | 2.99%   |
| Multimedia controller    | 9        | 2.45%   |
| Card reader              | 9        | 2.45%   |
| Modem                    | 6        | 1.63%   |
| Storage/raid             | 4        | 1.09%   |
| Firewire controller      | 4        | 1.09%   |
| Network                  | 3        | 0.82%   |
| Dvb card                 | 3        | 0.82%   |
| Bluetooth                | 3        | 0.82%   |
| Video                    | 2        | 0.54%   |
| Tv card                  | 2        | 0.54%   |
| Net/ethernet             | 2        | 0.54%   |
| Storage/ide              | 1        | 0.27%   |

