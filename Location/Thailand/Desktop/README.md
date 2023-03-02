Linux in Thailand - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 242

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Supermicro    | X10DRiB                     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Dell          | 040DDP A01                  | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 054KM3 A00                  | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| Gigabyte      | B650M DS3H                  | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Gigabyte      | 970A-D3                     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| ASRock        | B550M-ITX/ac                | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Dell          | 088DT1 A01                  | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| ASUSTek       | ROG Maximus X APEX          | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| Dell          | 04YP6J A02                  | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Intel         | D54250WYK H13922-305        | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| HP            | 18E7                        | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| ASRock        | H370 Pro4                   | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| ASUSTek       | H81M-E                      | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Gigabyte      | GA-970A-DS3                 | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| ASRock        | H410M-HDV R2.0              | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | Z170-K                      | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| HP            | 82B4                        | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| HP            | 82B4                        | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | 0YXT71 A02                  | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Gigabyte      | F2A68HM-DS2                 | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | 880GM-LE FX                 | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| ASUSTek       | M2N68-AM Plus               | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| ASUSTek       | H81M-A                      | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Dell          | 0D24M8 A00                  | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| ASRock        | B450M Steel Legend          | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| ASRock        | B450M Steel Legend          | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| ASRock        | H81M-HDS R2.0               | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| ASRock        | H110M-DVS R3.0              | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | B450M MORTAR MAX            | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| MSI           | A320M-A PRO MAX             | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| Intel         | H61M S1                     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| Acer          | Veriton X2665G              | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Huanan        | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| ASRock        | B450M Steel Legend          | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Gigabyte      | Z490 UD                     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Gigabyte      | F2A75M-HD2                  | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| HP            | 1998                        | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Dell          | 0F8096                      | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Dell          | 0F8096                      | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Acer          | Aspire M1935                | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| Fujitsu       | JIM76YK3                    | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| ASRock        | Z390 Pro4                   | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Unknown       | Unknown                     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASRock        | Z270 Killer SLI             | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Gigabyte      | F2A85XM-HD3                 | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| ASRock        | B460M Steel Legend          | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| ASRock        | B450M Steel Legend          | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Dell          | 0X8DXD A01                  | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| ASRock        | B450 Pro4                   | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| ASUSTek       | H61M-D                      | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | S340MF                      | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| Gigabyte      | Z390 UD                     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| ASUSTek       | Z170-P D3                   | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | M2N                         | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | Z170-P D3                   | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Unknown       | Unknown                     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Pegatron      | 2A99                        | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Packard Be... | IMEDIA S3720                | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Aspire XC-330               | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | 3048h                       | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| HP            | 2B15A                       | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| MSI           | B450M PRO-VDH PLUS          | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| ASUSTek       | H110M-E/M.2                 | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| MSI           | H110M PRO-VD PLUS           | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| ASUSTek       | H81M-CS                     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| ASUSTek       | H81M-E                      | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| Gigabyte      | F2A88XM-HD3P                | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Biostar       | A10N-8800E                  | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| ASUSTek       | P7P55 LX                    | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| ASRock        | Z77 Pro4                    | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| ASUSTek       | P8H61-M LE                  | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 27       | 15.98%  |
| Ubuntu 18.04                 | 23       | 13.61%  |
| Ubuntu 22.04                 | 8        | 4.73%   |
| OpenMandriva 4.3             | 8        | 4.73%   |
| OpenMandriva 4.2             | 7        | 4.14%   |
| Manjaro                      | 6        | 3.55%   |
| Arch Rolling                 | 5        | 2.96%   |
| Xubuntu 20.04                | 3        | 1.78%   |
| Pop!_OS 22.04                | 3        | 1.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.78%   |
| OpenMandriva 23.01           | 3        | 1.78%   |
| KDE neon 20.04               | 3        | 1.78%   |
| Fedora 37                    | 3        | 1.78%   |
| Zorin 16                     | 2        | 1.18%   |
| Zorin 15                     | 2        | 1.18%   |
| Xubuntu 18.04                | 2        | 1.18%   |
| Ubuntu 21.10                 | 2        | 1.18%   |
| Ubuntu 19.10                 | 2        | 1.18%   |
| Reborn OS                    | 2        | 1.18%   |
| Linux Mint 21                | 2        | 1.18%   |
| Linux Mint 20                | 2        | 1.18%   |
| Kubuntu 22.04                | 2        | 1.18%   |
| Fedora 36                    | 2        | 1.18%   |
| Endless 3.9.5                | 2        | 1.18%   |
| Endless 3.7.6                | 2        | 1.18%   |
| Debian 11                    | 2        | 1.18%   |
| Arch                         | 2        | 1.18%   |
| Xubuntu 21.10                | 1        | 0.59%   |
| UbuntuDDE 20.04              | 1        | 0.59%   |
| Ubuntu MATE 18.04            | 1        | 0.59%   |
| Ubuntu Budgie 20.10          | 1        | 0.59%   |
| Ubuntu 22.10                 | 1        | 0.59%   |
| Ubuntu 21.04                 | 1        | 0.59%   |
| Ubuntu 19.04                 | 1        | 0.59%   |
| Ubuntu 16.04                 | 1        | 0.59%   |
| Solus 4.3                    | 1        | 0.59%   |
| Pop!_OS 21.10                | 1        | 0.59%   |
| Pop!_OS 21.04                | 1        | 0.59%   |
| Pop!_OS 20.10                | 1        | 0.59%   |
| Pop!_OS 20.04                | 1        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 64       | 39.51%  |
| OpenMandriva  | 18       | 11.11%  |
| Linux Mint    | 9        | 5.56%   |
| Fedora        | 8        | 4.94%   |
| Pop!_OS       | 7        | 4.32%   |
| Arch          | 7        | 4.32%   |
| Xubuntu       | 6        | 3.7%    |
| Manjaro       | 6        | 3.7%    |
| Endless       | 6        | 3.7%    |
| Zorin         | 4        | 2.47%   |
| openSUSE      | 3        | 1.85%   |
| KDE neon      | 3        | 1.85%   |
| Debian        | 3        | 1.85%   |
| Reborn OS     | 2        | 1.23%   |
| Kubuntu       | 2        | 1.23%   |
| Elementary    | 2        | 1.23%   |
| Clear Linux   | 2        | 1.23%   |
| CentOS        | 2        | 1.23%   |
| UbuntuDDE     | 1        | 0.62%   |
| Ubuntu MATE   | 1        | 0.62%   |
| Ubuntu Budgie | 1        | 0.62%   |
| Solus         | 1        | 0.62%   |
| Kali          | 1        | 0.62%   |
| GNOME OS      | 1        | 0.62%   |
| BlackPanther  | 1        | 0.62%   |
| ArcoLinux     | 1        | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 3.93%   |
| 5.16.7-desktop-1omv4003  | 6        | 3.37%   |
| 5.4.0-48-generic         | 4        | 2.25%   |
| 5.15.0-46-generic        | 4        | 2.25%   |
| 6.1.1-desktop-1omv2290   | 3        | 1.69%   |
| 5.8.0-14-generic         | 3        | 1.69%   |
| 5.4.0-42-generic         | 3        | 1.69%   |
| 5.15.0-56-generic        | 3        | 1.69%   |
| 5.15.0-43-generic        | 3        | 1.69%   |
| 5.8.0-63-generic         | 2        | 1.12%   |
| 5.4.0-77-generic         | 2        | 1.12%   |
| 5.4.0-66-generic         | 2        | 1.12%   |
| 5.4.0-65-generic         | 2        | 1.12%   |
| 5.4.0-59-generic         | 2        | 1.12%   |
| 5.4.0-45-generic         | 2        | 1.12%   |
| 5.4.0-37-generic         | 2        | 1.12%   |
| 5.3.0-23-generic         | 2        | 1.12%   |
| 5.19.0-76051900-generic  | 2        | 1.12%   |
| 5.17.5-76051705-generic  | 2        | 1.12%   |
| 5.17.3-arch1-1           | 2        | 1.12%   |
| 5.16.13-desktop-1omv4003 | 2        | 1.12%   |
| 5.13.0-51-generic        | 2        | 1.12%   |
| 5.13.0-22-generic        | 2        | 1.12%   |
| 5.11.0-41-generic        | 2        | 1.12%   |
| 5.11.0-37-generic        | 2        | 1.12%   |
| 5.0.0-37-generic         | 2        | 1.12%   |
| 5.0.0-23-generic         | 2        | 1.12%   |
| 6.1.5-200.fc37.x86_64    | 1        | 0.56%   |
| 6.1.3-1-default          | 1        | 0.56%   |
| 6.1.12-200.fc37.x86_64   | 1        | 0.56%   |
| 6.0.15-300.fc37.x86_64   | 1        | 0.56%   |
| 6.0.12-300.fc37.x86_64   | 1        | 0.56%   |
| 6.0.0-kali3-amd64        | 1        | 0.56%   |
| 5.9.16-1-MANJARO         | 1        | 0.56%   |
| 5.8.1-arch1-1            | 1        | 0.56%   |
| 5.8.0-7630-generic       | 1        | 0.56%   |
| 5.8.0-59-generic         | 1        | 0.56%   |
| 5.8.0-48-generic         | 1        | 0.56%   |
| 5.8.0-43-generic         | 1        | 0.56%   |
| 5.8.0-41-generic         | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 18.29%  |
| 5.15.0  | 13       | 7.43%   |
| 5.8.0   | 12       | 6.86%   |
| 5.13.0  | 11       | 6.29%   |
| 4.15.0  | 11       | 6.29%   |
| 5.3.0   | 8        | 4.57%   |
| 5.10.14 | 7        | 4%      |
| 5.0.0   | 7        | 4%      |
| 5.16.7  | 6        | 3.43%   |
| 5.11.0  | 6        | 3.43%   |
| 4.18.0  | 5        | 2.86%   |
| 6.1.1   | 3        | 1.71%   |
| 5.19.0  | 3        | 1.71%   |
| 5.17.5  | 3        | 1.71%   |
| 5.5.7   | 2        | 1.14%   |
| 5.17.3  | 2        | 1.14%   |
| 5.16.13 | 2        | 1.14%   |
| 5.10.0  | 2        | 1.14%   |
| 6.1.5   | 1        | 0.57%   |
| 6.1.3   | 1        | 0.57%   |
| 6.1.12  | 1        | 0.57%   |
| 6.0.15  | 1        | 0.57%   |
| 6.0.12  | 1        | 0.57%   |
| 6.0.0   | 1        | 0.57%   |
| 5.9.16  | 1        | 0.57%   |
| 5.8.1   | 1        | 0.57%   |
| 5.7.13  | 1        | 0.57%   |
| 5.6.6   | 1        | 0.57%   |
| 5.6.2   | 1        | 0.57%   |
| 5.6.16  | 1        | 0.57%   |
| 5.6.14  | 1        | 0.57%   |
| 5.4.82  | 1        | 0.57%   |
| 5.4.80  | 1        | 0.57%   |
| 5.3.12  | 1        | 0.57%   |
| 5.19.16 | 1        | 0.57%   |
| 5.18.5  | 1        | 0.57%   |
| 5.17.6  | 1        | 0.57%   |
| 5.17.4  | 1        | 0.57%   |
| 5.17.1  | 1        | 0.57%   |
| 5.16.9  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 19.65%  |
| 5.15    | 16       | 9.25%   |
| 5.13    | 14       | 8.09%   |
| 5.8     | 13       | 7.51%   |
| 5.16    | 13       | 7.51%   |
| 4.15    | 11       | 6.36%   |
| 5.10    | 10       | 5.78%   |
| 5.3     | 9        | 5.2%    |
| 5.17    | 8        | 4.62%   |
| 5.0     | 8        | 4.62%   |
| 6.1     | 6        | 3.47%   |
| 5.11    | 6        | 3.47%   |
| 4.18    | 5        | 2.89%   |
| 5.19    | 4        | 2.31%   |
| 5.6     | 3        | 1.73%   |
| 6.0     | 2        | 1.16%   |
| 5.5     | 2        | 1.16%   |
| 5.14    | 2        | 1.16%   |
| 5.9     | 1        | 0.58%   |
| 5.7     | 1        | 0.58%   |
| 5.18    | 1        | 0.58%   |
| 5.12    | 1        | 0.58%   |
| 5.1     | 1        | 0.58%   |
| 4.4     | 1        | 0.58%   |
| 4.17    | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 156      | 99.36%  |
| i686   | 1        | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 84       | 51.53%  |
| KDE5       | 25       | 15.34%  |
| Unknown    | 20       | 12.27%  |
| XFCE       | 12       | 7.36%   |
| X-Cinnamon | 9        | 5.52%   |
| MATE       | 3        | 1.84%   |
| KDE        | 3        | 1.84%   |
| Pantheon   | 2        | 1.23%   |
| Deepin     | 2        | 1.23%   |
| Budgie     | 2        | 1.23%   |
| Cinnamon   | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 126      | 78.75%  |
| Wayland | 19       | 11.88%  |
| Unknown | 13       | 8.13%   |
| Tty     | 2        | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 59.01%  |
| SDDM    | 23       | 14.29%  |
| GDM3    | 16       | 9.94%   |
| GDM     | 15       | 9.32%   |
| LightDM | 9        | 5.59%   |
| TDM     | 3        | 1.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 112      | 69.57%  |
| Unknown | 16       | 9.94%   |
| th_TH   | 10       | 6.21%   |
| en_GB   | 10       | 6.21%   |
| de_DE   | 5        | 3.11%   |
| C       | 4        | 2.48%   |
| it_IT   | 2        | 1.24%   |
| sv_SE   | 1        | 0.62%   |
| de_CH   | 1        | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 98       | 60.49%  |
| EFI  | 64       | 39.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 127      | 78.88%  |
| Overlay | 18       | 11.18%  |
| Btrfs   | 8        | 4.97%   |
| Unknown | 4        | 2.48%   |
| Xfs     | 3        | 1.86%   |
| Zfs     | 1        | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 104      | 65.41%  |
| GPT     | 44       | 27.67%  |
| MBR     | 11       | 6.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 79.11%  |
| Yes       | 33       | 20.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 60%     |
| Yes       | 64       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 36       | 22.93%  |
| ASUSTek Computer    | 33       | 21.02%  |
| ASRock              | 22       | 14.01%  |
| MSI                 | 15       | 9.55%   |
| Dell                | 14       | 8.92%   |
| Hewlett-Packard     | 11       | 7.01%   |
| Acer                | 7        | 4.46%   |
| Unknown             | 3        | 1.91%   |
| Intel               | 2        | 1.27%   |
| Huanan              | 2        | 1.27%   |
| VIA Technologies    | 1        | 0.64%   |
| Supermicro          | 1        | 0.64%   |
| SHARKBAY            | 1        | 0.64%   |
| Pegatron            | 1        | 0.64%   |
| Packard Bell        | 1        | 0.64%   |
| OEM                 | 1        | 0.64%   |
| MiTAC               | 1        | 0.64%   |
| Fujitsu             | 1        | 0.64%   |
| Biostar             | 1        | 0.64%   |
| BESSTAR Tech        | 1        | 0.64%   |
| Apple               | 1        | 0.64%   |
| AFOX                | 1        | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 6        | 3.82%   |
| Unknown                    | 4        | 2.55%   |
| Dell OptiPlex 7010         | 3        | 1.91%   |
| ASUS P8H61-M LE            | 3        | 1.91%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 1.27%   |
| Gigabyte Z97X-UD3H-BK      | 2        | 1.27%   |
| Gigabyte F2A88XM-HD3P      | 2        | 1.27%   |
| Gigabyte F2A68HM-DS2       | 2        | 1.27%   |
| Gigabyte B250-HD3          | 2        | 1.27%   |
| Dell OptiPlex 3020         | 2        | 1.27%   |
| Dell Inspiron 3847         | 2        | 1.27%   |
| ASUS H110M-E/M.2           | 2        | 1.27%   |
| ASRock B450 Steel Legend   | 2        | 1.27%   |
| Acer Aspire TC-885         | 2        | 1.27%   |
| VIA VX900                  | 1        | 0.64%   |
| Supermicro AT350 F3        | 1        | 0.64%   |
| Pegatron CQ3476L           | 1        | 0.64%   |
| Packard Bell IMEDIA S3720  | 1        | 0.64%   |
| OEM Intel H81              | 1        | 0.64%   |
| MSI Pro 3130 Microtower PC | 1        | 0.64%   |
| MSI Pro 2000/2080          | 1        | 0.64%   |
| MSI p6772l                 | 1        | 0.64%   |
| MSI MS-7C52                | 1        | 0.64%   |
| MSI MS-7C35                | 1        | 0.64%   |
| MSI MS-7B89                | 1        | 0.64%   |
| MSI MS-7B85                | 1        | 0.64%   |
| MSI MS-7A63                | 1        | 0.64%   |
| MSI MS-7A38                | 1        | 0.64%   |
| MSI MS-7A32                | 1        | 0.64%   |
| MSI MS-7A15                | 1        | 0.64%   |
| MSI MS-7978                | 1        | 0.64%   |
| MSI MS-7914                | 1        | 0.64%   |
| MSI MS-7641                | 1        | 0.64%   |
| MSI KY779AA-AKL CQ3070L    | 1        | 0.64%   |
| MiTAC PD14RI               | 1        | 0.64%   |
| Intel H61M S1              | 1        | 0.64%   |
| Intel D54250WYK H13922-305 | 1        | 0.64%   |
| Huanan X79 V6.11           | 1        | 0.64%   |
| Huanan X79 249PC V2.2      | 1        | 0.64%   |
| HP Z800 Workstation        | 1        | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 9        | 5.73%   |
| ASUS All               | 6        | 3.82%   |
| ASUS PRIME             | 5        | 3.18%   |
| Acer Aspire            | 5        | 3.18%   |
| ASRock B450            | 4        | 2.55%   |
| Unknown                | 4        | 2.55%   |
| HP ProDesk             | 3        | 1.91%   |
| ASUS ROG               | 3        | 1.91%   |
| ASUS P8H61-M           | 3        | 1.91%   |
| ASUS M5A78L-M          | 3        | 1.91%   |
| MSI Pro                | 2        | 1.27%   |
| Huanan X79             | 2        | 1.27%   |
| HP EliteDesk           | 2        | 1.27%   |
| HP Compaq              | 2        | 1.27%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 1.27%   |
| Gigabyte Z390          | 2        | 1.27%   |
| Gigabyte GA-78LMT-USB3 | 2        | 1.27%   |
| Gigabyte F2A88XM-HD3P  | 2        | 1.27%   |
| Gigabyte F2A68HM-DS2   | 2        | 1.27%   |
| Gigabyte B250-HD3      | 2        | 1.27%   |
| Dell Precision         | 2        | 1.27%   |
| Dell Inspiron          | 2        | 1.27%   |
| ASUS H110M-E           | 2        | 1.27%   |
| ASRock Z77             | 2        | 1.27%   |
| ASRock B450M           | 2        | 1.27%   |
| Acer Veriton           | 2        | 1.27%   |
| VIA VX900              | 1        | 0.64%   |
| Supermicro AT350       | 1        | 0.64%   |
| Pegatron CQ3476L       | 1        | 0.64%   |
| Packard Bell IMEDIA    | 1        | 0.64%   |
| OEM Intel              | 1        | 0.64%   |
| MSI p6772l             | 1        | 0.64%   |
| MSI MS-7C52            | 1        | 0.64%   |
| MSI MS-7C35            | 1        | 0.64%   |
| MSI MS-7B89            | 1        | 0.64%   |
| MSI MS-7B85            | 1        | 0.64%   |
| MSI MS-7A63            | 1        | 0.64%   |
| MSI MS-7A38            | 1        | 0.64%   |
| MSI MS-7A32            | 1        | 0.64%   |
| MSI MS-7A15            | 1        | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 23       | 14.65%  |
| 2013 | 16       | 10.19%  |
| 2019 | 13       | 8.28%   |
| 2016 | 13       | 8.28%   |
| 2014 | 13       | 8.28%   |
| 2012 | 13       | 8.28%   |
| 2020 | 11       | 7.01%   |
| 2017 | 11       | 7.01%   |
| 2011 | 10       | 6.37%   |
| 2009 | 10       | 6.37%   |
| 2015 | 6        | 3.82%   |
| 2010 | 5        | 3.18%   |
| 2021 | 4        | 2.55%   |
| 2008 | 4        | 2.55%   |
| 2006 | 2        | 1.27%   |
| 2022 | 1        | 0.64%   |
| 2007 | 1        | 0.64%   |
| 2005 | 1        | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 157      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 153      | 96.84%  |
| Enabled  | 5        | 3.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 157      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 39       | 24.07%  |
| 8.01-16.0       | 39       | 24.07%  |
| 3.01-4.0        | 27       | 16.67%  |
| 4.01-8.0        | 26       | 16.05%  |
| 32.01-64.0      | 18       | 11.11%  |
| 1.01-2.0        | 7        | 4.32%   |
| 24.01-32.0      | 2        | 1.23%   |
| 64.01-256.0     | 2        | 1.23%   |
| More than 256.0 | 1        | 0.62%   |
| 0.51-1.0        | 1        | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 64       | 37.21%  |
| 2.01-3.0   | 56       | 32.56%  |
| 4.01-8.0   | 18       | 10.47%  |
| 3.01-4.0   | 16       | 9.3%    |
| 0.51-1.0   | 9        | 5.23%   |
| 8.01-16.0  | 4        | 2.33%   |
| 16.01-24.0 | 3        | 1.74%   |
| 24.01-32.0 | 1        | 0.58%   |
| 0.01-0.5   | 1        | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 38.41%  |
| 2      | 48       | 29.27%  |
| 3      | 30       | 18.29%  |
| 4      | 11       | 6.71%   |
| 5      | 5        | 3.05%   |
| 0      | 4        | 2.44%   |
| 51     | 1        | 0.61%   |
| 32     | 1        | 0.61%   |
| 6      | 1        | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 59.12%  |
| Yes       | 65       | 40.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 153      | 97.45%  |
| No        | 4        | 2.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 50.31%  |
| No        | 79       | 49.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 73.75%  |
| Yes       | 42       | 26.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 157      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Bangkok             | 54       | 33.33%  |
| Chiang Mai          | 18       | 11.11%  |
| Khon Kaen           | 6        | 3.7%    |
| Bang Lamung         | 6        | 3.7%    |
| Phuket              | 5        | 3.09%   |
| Songkhla            | 4        | 2.47%   |
| Nakhon Ratchasima   | 4        | 2.47%   |
| Surin               | 3        | 1.85%   |
| Pattaya             | 3        | 1.85%   |
| Nakhon Pathom       | 3        | 1.85%   |
| Chon Buri           | 3        | 1.85%   |
| Si Racha            | 2        | 1.23%   |
| Phitsanulok         | 2        | 1.23%   |
| Pathum Thani        | 2        | 1.23%   |
| Pak Kret            | 2        | 1.23%   |
| Nonthaburi          | 2        | 1.23%   |
| Lat Krabang         | 2        | 1.23%   |
| Lampang             | 2        | 1.23%   |
| Hua Hin             | 2        | 1.23%   |
| Bang Khae           | 2        | 1.23%   |
| Ban Du              | 2        | 1.23%   |
| Ban Bang Tanot      | 2        | 1.23%   |
| Yarang              | 1        | 0.62%   |
| Wichian Buri        | 1        | 0.62%   |
| Trat                | 1        | 0.62%   |
| Thung Song          | 1        | 0.62%   |
| Suan Luang          | 1        | 0.62%   |
| San Sai             | 1        | 0.62%   |
| Samut Songkhram     | 1        | 0.62%   |
| Samphanthawong      | 1        | 0.62%   |
| Phetchabun          | 1        | 0.62%   |
| Phan                | 1        | 0.62%   |
| Nong Khaem          | 1        | 0.62%   |
| Nakhon Si Thammarat | 1        | 0.62%   |
| Nakhon Sawan        | 1        | 0.62%   |
| Mukdahan            | 1        | 0.62%   |
| Mueang Phuket       | 1        | 0.62%   |
| Loei                | 1        | 0.62%   |
| Krabi               | 1        | 0.62%   |
| Kosamphi Nakhon     | 1        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 63       | 110    | 22.83%  |
| Seagate                   | 54       | 83     | 19.57%  |
| Samsung Electronics       | 27       | 45     | 9.78%   |
| Kingston                  | 15       | 15     | 5.43%   |
| Sandisk                   | 13       | 18     | 4.71%   |
| Toshiba                   | 10       | 51     | 3.62%   |
| Crucial                   | 8        | 8      | 2.9%    |
| Hitachi                   | 7        | 7      | 2.54%   |
| HS-SSD-C100               | 6        | 11     | 2.17%   |
| Apacer                    | 6        | 6      | 2.17%   |
| Unknown                   | 5        | 10     | 1.81%   |
| Phison                    | 5        | 10     | 1.81%   |
| Intel                     | 4        | 4      | 1.45%   |
| Hikvision                 | 4        | 4      | 1.45%   |
| Silicon Motion            | 3        | 4      | 1.09%   |
| KingSpec                  | 3        | 5      | 1.09%   |
| JMicron Technology        | 3        | 3      | 1.09%   |
| HGST                      | 3        | 11     | 1.09%   |
| GALAX                     | 3        | 3      | 1.09%   |
| USB3.0                    | 2        | 2      | 0.72%   |
| TO Exter                  | 2        | 2      | 0.72%   |
| SK hynix                  | 2        | 3      | 0.72%   |
| Plextor                   | 2        | 2      | 0.72%   |
| Hewlett-Packard           | 2        | 4      | 0.72%   |
| External                  | 2        | 2      | 0.72%   |
| Corsair                   | 2        | 2      | 0.72%   |
| Colorful                  | 2        | 3      | 0.72%   |
| China                     | 2        | 2      | 0.72%   |
| WALRAM                    | 1        | 1      | 0.36%   |
| Verbatim                  | 1        | 1      | 0.36%   |
| Transcend                 | 1        | 1      | 0.36%   |
| SPCC                      | 1        | 1      | 0.36%   |
| Realtek Semiconductor     | 1        | 1      | 0.36%   |
| Pioneer                   | 1        | 1      | 0.36%   |
| Phison Electronics        | 1        | 1      | 0.36%   |
| OCZ                       | 1        | 1      | 0.36%   |
| Micron/Crucial Technology | 1        | 1      | 0.36%   |
| Micron Technology         | 1        | 1      | 0.36%   |
| Lexar                     | 1        | 1      | 0.36%   |
| HS-SSD-E100               | 1        | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB         | 8        | 2.51%   |
| Seagate ST500DM002-1BD142 500GB        | 7        | 2.19%   |
| Seagate ST1000DM003-1ER162 1TB         | 6        | 1.88%   |
| WDC WD10EZEX-00WN4A0 1TB               | 5        | 1.57%   |
| Kingston SUV400S37120G 120GB SSD       | 5        | 1.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 4        | 1.25%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4        | 1.25%   |
| Toshiba DT01ACA100 1TB                 | 4        | 1.25%   |
| Seagate ST2000VX008-2E3164 2TB         | 4        | 1.25%   |
| Samsung HD103SJ 1TB                    | 4        | 1.25%   |
| Kingston SA400S37240G 240GB SSD        | 4        | 1.25%   |
| Crucial CT500MX500SSD1 500GB           | 4        | 1.25%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 3        | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3        | 0.94%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 0.94%   |
| WDC WD20EZAZ-00GGJB0 2TB               | 3        | 0.94%   |
| Unknown SD/MMC/MS PRO 16GB             | 3        | 0.94%   |
| Seagate ST3500418AS 500GB              | 3        | 0.94%   |
| SanDisk SDSSDA120G 120GB               | 3        | 0.94%   |
| SanDisk NVMe SSD Drive 250GB           | 3        | 0.94%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 3        | 0.94%   |
| Phison NVMe SSD Drive 240GB            | 3        | 0.94%   |
| HS-SSD-C100 240G                       | 3        | 0.94%   |
| HS-SSD-C100 120G                       | 3        | 0.94%   |
| WDC WDS250G3X0C-00SJG0 250GB           | 2        | 0.63%   |
| WDC WD5000AAKX-001CA0 500GB            | 2        | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2        | 0.63%   |
| WDC WD2002FAEX-007BA0 2TB              | 2        | 0.63%   |
| WDC WD10EZEX-21WN4A0 1TB               | 2        | 0.63%   |
| WDC WD10EZEX-00MFCA0 1TB               | 2        | 0.63%   |
| WDC WD10EFRX-68FYTN0 1TB               | 2        | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB                | 2        | 0.63%   |
| USB3.0 Super Speed 960GB               | 2        | 0.63%   |
| TO Exter nal USB 3.0 240GB             | 2        | 0.63%   |
| Seagate ST500DM002-1BD14 500GB         | 2        | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB         | 2        | 0.63%   |
| Seagate ST3320620AS 320GB              | 2        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB         | 2        | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB         | 2        | 0.63%   |
| Seagate ST1000DM003-1SB102 1TB         | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 53       | 85     | 36.81%  |
| Seagate             | 53       | 82     | 36.81%  |
| Toshiba             | 10       | 51     | 6.94%   |
| Samsung Electronics | 9        | 14     | 6.25%   |
| Hitachi             | 7        | 7      | 4.86%   |
| Unknown             | 4        | 9      | 2.78%   |
| HGST                | 3        | 11     | 2.08%   |
| USB3.0              | 2        | 2      | 1.39%   |
| JMicron Technology  | 2        | 2      | 1.39%   |
| Hewlett-Packard     | 1        | 3      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 18     | 14.44%  |
| Samsung Electronics | 12       | 17     | 13.33%  |
| Kingston            | 12       | 12     | 13.33%  |
| Crucial             | 8        | 8      | 8.89%   |
| Apacer              | 6        | 6      | 6.67%   |
| SanDisk             | 5        | 6      | 5.56%   |
| Intel               | 4        | 4      | 4.44%   |
| KingSpec            | 3        | 5      | 3.33%   |
| Hikvision           | 3        | 3      | 3.33%   |
| GALAX               | 3        | 3      | 3.33%   |
| TO Exter            | 2        | 2      | 2.22%   |
| Plextor             | 2        | 2      | 2.22%   |
| China               | 2        | 2      | 2.22%   |
| WALRAM              | 1        | 1      | 1.11%   |
| Verbatim            | 1        | 1      | 1.11%   |
| SPCC                | 1        | 1      | 1.11%   |
| SK hynix            | 1        | 2      | 1.11%   |
| Pioneer             | 1        | 1      | 1.11%   |
| OCZ                 | 1        | 1      | 1.11%   |
| Micron Technology   | 1        | 1      | 1.11%   |
| Lexar               | 1        | 1      | 1.11%   |
| HS-SSD-E100         | 1        | 1      | 1.11%   |
| Hewlett-Packard     | 1        | 1      | 1.11%   |
| DGM                 | 1        | 1      | 1.11%   |
| Corsair             | 1        | 1      | 1.11%   |
| Colorful            | 1        | 2      | 1.11%   |
| Acer                | 1        | 3      | 1.11%   |
| A-DATA Technology   | 1        | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 109      | 266    | 47.6%   |
| SSD     | 73       | 107    | 31.88%  |
| NVMe    | 36       | 59     | 15.72%  |
| Unknown | 11       | 16     | 4.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 146      | 370    | 74.49%  |
| NVMe | 34       | 57     | 17.35%  |
| SAS  | 16       | 21     | 8.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 104      | 164    | 49.52%  |
| 0.51-1.0   | 63       | 88     | 30%     |
| 1.01-2.0   | 26       | 31     | 12.38%  |
| 3.01-4.0   | 9        | 56     | 4.29%   |
| 2.01-3.0   | 3        | 8      | 1.43%   |
| 4.01-10.0  | 3        | 15     | 1.43%   |
| 10.01-20.0 | 2        | 11     | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 44       | 26.83%  |
| 501-1000       | 25       | 15.24%  |
| 251-500        | 23       | 14.02%  |
| 1-20           | 19       | 11.59%  |
| 1001-2000      | 12       | 7.32%   |
| More than 3000 | 11       | 6.71%   |
| 2001-3000      | 11       | 6.71%   |
| 21-50          | 7        | 4.27%   |
| 51-100         | 7        | 4.27%   |
| Unknown        | 5        | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 63       | 37.06%  |
| 21-50          | 26       | 15.29%  |
| 101-250        | 19       | 11.18%  |
| 51-100         | 19       | 11.18%  |
| 501-1000       | 13       | 7.65%   |
| 251-500        | 8        | 4.71%   |
| 1001-2000      | 8        | 4.71%   |
| More than 3000 | 7        | 4.12%   |
| Unknown        | 5        | 2.94%   |
| 2001-3000      | 2        | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2        | 2      | 11.76%  |
| Seagate ST500DM002-1BD14 500GB           | 2        | 3      | 11.76%  |
| Samsung Electronics SSD 830 Series 128GB | 2        | 2      | 11.76%  |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 5.88%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1        | 1      | 5.88%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1        | 1      | 5.88%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1        | 1      | 5.88%   |
| Toshiba HDWL110 1TB                      | 1        | 1      | 5.88%   |
| Seagate ST9120822AS 120GB                | 1        | 1      | 5.88%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 5.88%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 5.88%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 5.88%   |
| Samsung Electronics HD253GJ 250GB        | 1        | 1      | 5.88%   |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 37.5%   |
| WDC                 | 5        | 6      | 31.25%  |
| Samsung Electronics | 4        | 4      | 25%     |
| Toshiba             | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 42.86%  |
| WDC                 | 5        | 6      | 35.71%  |
| Samsung Electronics | 2        | 2      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 17     | 86.67%  |
| SSD  | 2        | 2      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 116      | 262    | 65.54%  |
| Works    | 47       | 166    | 26.55%  |
| Malfunc  | 13       | 19     | 7.34%   |
| Failed   | 1        | 1      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 103      | 49.52%  |
| AMD                         | 46       | 22.12%  |
| SanDisk                     | 13       | 6.25%   |
| ASMedia Technology          | 10       | 4.81%   |
| Samsung Electronics         | 7        | 3.37%   |
| Phison Electronics          | 7        | 3.37%   |
| Nvidia                      | 6        | 2.88%   |
| Silicon Motion              | 3        | 1.44%   |
| Kingston Technology Company | 3        | 1.44%   |
| VIA Technologies            | 2        | 0.96%   |
| Broadcom / LSI              | 2        | 0.96%   |
| SK hynix                    | 1        | 0.48%   |
| Realtek Semiconductor       | 1        | 0.48%   |
| Micron/Crucial Technology   | 1        | 0.48%   |
| MAXIO Technology (Hangzhou) | 1        | 0.48%   |
| LSI Logic / Symbios Logic   | 1        | 0.48%   |
| JMicron Technology          | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 10.12%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 6.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 5.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 3.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 3.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 3.5%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 3.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 3.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 2.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.33%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4        | 1.56%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.56%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.17%   |
| SanDisk Non-Volatile memory controller                                                  | 3        | 1.17%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.17%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.17%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.78%   |
| Nvidia MCP73 IDE Controller                                                             | 2        | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.78%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 125      | 59.52%  |
| IDE  | 39       | 18.57%  |
| NVMe | 35       | 16.67%  |
| RAID | 9        | 4.29%   |
| SAS  | 1        | 0.48%   |
| SCSI | 1        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 106      | 67.52%  |
| AMD          | 50       | 31.85%  |
| CentaurHauls | 1        | 0.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 3.14%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.52%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 1.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 1.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.26%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.26%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.26%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.26%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.26%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.26%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.26%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 1.26%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.26%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.26%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.26%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.26%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.26%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.26%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.26%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.26%   |
| AMD Phenom II X6 1055T Processor            | 2        | 1.26%   |
| AMD Athlon II X2 270 Processor              | 2        | 1.26%   |
| AMD A10-5800K APU with Radeon HD Graphics   | 2        | 1.26%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.63%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.63%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.63%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz         | 1        | 0.63%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 0.63%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz         | 1        | 0.63%   |
| Intel Xeon CPU E5-2640 v2 @ 2.00GHz         | 1        | 0.63%   |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz         | 1        | 0.63%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.63%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.63%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 20.89%  |
| Intel Core i3           | 24       | 15.19%  |
| Intel Core i7           | 20       | 12.66%  |
| AMD Ryzen 5             | 11       | 6.96%   |
| Intel Xeon              | 9        | 5.7%    |
| AMD Ryzen 7             | 7        | 4.43%   |
| AMD FX                  | 5        | 3.16%   |
| AMD Athlon II X2        | 5        | 3.16%   |
| Intel Pentium           | 4        | 2.53%   |
| Intel Core 2 Quad       | 4        | 2.53%   |
| AMD Ryzen 3             | 4        | 2.53%   |
| AMD A10                 | 4        | 2.53%   |
| Intel Pentium Dual-Core | 3        | 1.9%    |
| AMD Ryzen 9             | 3        | 1.9%    |
| Intel Core i9           | 2        | 1.27%   |
| Intel Core 2 Duo        | 2        | 1.27%   |
| Intel Celeron           | 2        | 1.27%   |
| AMD Phenom II X6        | 2        | 1.27%   |
| AMD Phenom II X4        | 2        | 1.27%   |
| AMD Athlon 64 X2        | 2        | 1.27%   |
| AMD A6                  | 2        | 1.27%   |
| AMD A4                  | 2        | 1.27%   |
| Intel Pentium Dual      | 1        | 0.63%   |
| Intel Pentium 4         | 1        | 0.63%   |
| Intel Atom              | 1        | 0.63%   |
| CentaurHauls VIA Eden   | 1        | 0.63%   |
| AMD Ryzen 3 PRO         | 1        | 0.63%   |
| AMD Phenom II X3        | 1        | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 60       | 37.97%  |
| 2      | 49       | 31.01%  |
| 6      | 22       | 13.92%  |
| 8      | 16       | 10.13%  |
| 12     | 3        | 1.9%    |
| 1      | 3        | 1.9%    |
| 3      | 2        | 1.27%   |
| 40     | 1        | 0.63%   |
| 24     | 1        | 0.63%   |
| 10     | 1        | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 153      | 97.45%  |
| 2      | 4        | 2.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 91       | 57.59%  |
| 1      | 67       | 42.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 157      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 23.17%  |
| 0x306c3    | 17       | 10.37%  |
| 0x206a7    | 10       | 6.1%    |
| 0x506e3    | 8        | 4.88%   |
| 0x906e9    | 7        | 4.27%   |
| 0x906ea    | 6        | 3.66%   |
| 0x306a9    | 6        | 3.66%   |
| 0x1067a    | 6        | 3.66%   |
| 0x0800820d | 4        | 2.44%   |
| 0x06001119 | 4        | 2.44%   |
| 0x010000c8 | 4        | 2.44%   |
| 0xa0655    | 3        | 1.83%   |
| 0x906ec    | 3        | 1.83%   |
| 0x406f1    | 3        | 1.83%   |
| 0x20655    | 3        | 1.83%   |
| 0x08701021 | 3        | 1.83%   |
| 0x106e5    | 2        | 1.22%   |
| 0x08001138 | 2        | 1.22%   |
| 0x06003106 | 2        | 1.22%   |
| 0x06000852 | 2        | 1.22%   |
| 0xf49      | 1        | 0.61%   |
| 0xa0653    | 1        | 0.61%   |
| 0x906ed    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x6fd      | 1        | 0.61%   |
| 0x6fb      | 1        | 0.61%   |
| 0x50654    | 1        | 0.61%   |
| 0x406c3    | 1        | 0.61%   |
| 0x40651    | 1        | 0.61%   |
| 0x306e4    | 1        | 0.61%   |
| 0x30678    | 1        | 0.61%   |
| 0x206c2    | 1        | 0.61%   |
| 0x106ca    | 1        | 0.61%   |
| 0x10677    | 1        | 0.61%   |
| 0x10676    | 1        | 0.61%   |
| 0x0a601201 | 1        | 0.61%   |
| 0x0a201204 | 1        | 0.61%   |
| 0x0a201009 | 1        | 0.61%   |
| 0x08701013 | 1        | 0.61%   |
| 0x08600106 | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 23       | 14.56%  |
| KabyLake    | 20       | 12.66%  |
| SandyBridge | 12       | 7.59%   |
| Zen 2       | 11       | 6.96%   |
| Skylake     | 11       | 6.96%   |
| IvyBridge   | 11       | 6.96%   |
| Penryn      | 9        | 5.7%    |
| K10         | 9        | 5.7%    |
| Piledriver  | 8        | 5.06%   |
| Zen+        | 7        | 4.43%   |
| CometLake   | 5        | 3.16%   |
| Zen         | 4        | 2.53%   |
| Westmere    | 4        | 2.53%   |
| Zen 3       | 3        | 1.9%    |
| Silvermont  | 3        | 1.9%    |
| Broadwell   | 3        | 1.9%    |
| Steamroller | 2        | 1.27%   |
| Nehalem     | 2        | 1.27%   |
| K8 Hammer   | 2        | 1.27%   |
| Excavator   | 2        | 1.27%   |
| Core        | 2        | 1.27%   |
| Unknown     | 2        | 1.27%   |
| NetBurst    | 1        | 0.63%   |
| K10 Llano   | 1        | 0.63%   |
| Bonnell     | 1        | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 71       | 42.01%  |
| Intel             | 50       | 29.59%  |
| AMD               | 46       | 27.22%  |
| VIA Technologies  | 1        | 0.59%   |
| ASPEED Technology | 1        | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8        | 4.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6        | 3.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.41%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 2.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 2.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5        | 2.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 2.84%   |
| Intel HD Graphics 530                                                                    | 5        | 2.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.7%    |
| Intel HD Graphics 630                                                                    | 3        | 1.7%    |
| AMD Renoir                                                                               | 3        | 1.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.14%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.14%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2        | 1.14%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.14%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.14%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.14%   |
| AMD Juniper PRO [Radeon HD 6750]                                                         | 2        | 1.14%   |
| AMD Fiji [Radeon R9 FURY / NANO Series]                                                  | 2        | 1.14%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 1.14%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.14%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                             | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.57%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.57%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 63       | 38.18%  |
| 1 x Intel            | 46       | 27.88%  |
| 1 x AMD              | 41       | 24.85%  |
| AMD + Nvidia         | 4        | 2.42%   |
| 2 x AMD              | 3        | 1.82%   |
| Intel + Nvidia       | 2        | 1.21%   |
| 3 x Nvidia           | 1        | 0.61%   |
| 2 x Nvidia           | 1        | 0.61%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.61%   |
| 1 x VIA              | 1        | 0.61%   |
| 1 x ASPEED           | 1        | 0.61%   |
| AMD + 2 x Nvidia     | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 120      | 74.07%  |
| Proprietary | 34       | 20.99%  |
| Unknown     | 8        | 4.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 46.39%  |
| 1.01-2.0   | 25       | 15.06%  |
| 3.01-4.0   | 16       | 9.64%   |
| 0.51-1.0   | 15       | 9.04%   |
| 0.01-0.5   | 13       | 7.83%   |
| 7.01-8.0   | 12       | 7.23%   |
| 5.01-6.0   | 4        | 2.41%   |
| 4.01-5.0   | 1        | 0.6%    |
| 2.01-3.0   | 1        | 0.6%    |
| 16.01-24.0 | 1        | 0.6%    |
| 8.01-16.0  | 1        | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 35       | 21.88%  |
| Acer                 | 29       | 18.13%  |
| Goldstar             | 23       | 14.38%  |
| Hewlett-Packard      | 11       | 6.88%   |
| Dell                 | 10       | 6.25%   |
| AOC                  | 9        | 5.63%   |
| BenQ                 | 6        | 3.75%   |
| ViewSonic            | 4        | 2.5%    |
| LG Electronics       | 4        | 2.5%    |
| Lenovo               | 3        | 1.88%   |
| Unknown (XXX)        | 2        | 1.25%   |
| Sharp                | 2        | 1.25%   |
| MStar                | 2        | 1.25%   |
| Ancor Communications | 2        | 1.25%   |
| Toshiba              | 1        | 0.63%   |
| Sony                 | 1        | 0.63%   |
| SGT                  | 1        | 0.63%   |
| Philips              | 1        | 0.63%   |
| MSI                  | 1        | 0.63%   |
| MIG                  | 1        | 0.63%   |
| Microstep            | 1        | 0.63%   |
| ITE                  | 1        | 0.63%   |
| IOD                  | 1        | 0.63%   |
| HUYINIUDA            | 1        | 0.63%   |
| HPN                  | 1        | 0.63%   |
| Gateway              | 1        | 0.63%   |
| Fujitsu Siemens      | 1        | 0.63%   |
| Fujitsu              | 1        | 0.63%   |
| Envision Peripherals | 1        | 0.63%   |
| CHI                  | 1        | 0.63%   |
| ASUSTek Computer     | 1        | 0.63%   |
| Apple                | 1        | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3        | 1.78%   |
| Acer K222HQL ACR0512 1920x1080 476x268mm 21.5-inch                    | 3        | 1.78%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2        | 1.18%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2        | 1.18%   |
| Samsung Electronics SME1920 SAM06B7 1360x768 410x230mm 18.5-inch      | 2        | 1.18%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 1.18%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 1.18%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 1.18%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 2        | 1.18%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2        | 1.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.18%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 1.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 1.18%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 2        | 1.18%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                      | 2        | 1.18%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 2        | 1.18%   |
| Acer S200HQL ACR0359 1600x900 434x236mm 19.4-inch                     | 2        | 1.18%   |
| Acer P193W ACR000C 1440x900 410x256mm 19.0-inch                       | 2        | 1.18%   |
| Acer K242HQL ACR042E 1920x1080 509x286mm 23.0-inch                    | 2        | 1.18%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                | 1        | 0.59%   |
| ViewSonic VA1703wSERIES VSC121F 1440x900 367x230mm 17.1-inch          | 1        | 0.59%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1210x680mm 54.6-inch         | 1        | 0.59%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.59%   |
| Toshiba TV TSB0114 1920x1080 882x498mm 39.9-inch                      | 1        | 0.59%   |
| Sony TV SNY9402 1920x1080                                             | 1        | 0.59%   |
| Sharp HDMI SHP113E 1920x1080 1330x748mm 60.1-inch                     | 1        | 0.59%   |
| Sharp HDMI SHP110F 1920x1080 700x390mm 31.5-inch                      | 1        | 0.59%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM044F 1440x900 408x255mm 18.9-inch   | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM03BA 1680x1050                      | 1        | 0.59%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 1        | 0.59%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 0.59%   |
| Samsung Electronics SA300/SA350 SAM0790 1920x1080 510x287mm 23.0-inch | 1        | 0.59%   |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch     | 1        | 0.59%   |
| Samsung Electronics S27D590 SAM0BE9 1920x1080 598x336mm 27.0-inch     | 1        | 0.59%   |
| Samsung Electronics S24R35A SAM729F 1920x1080 527x296mm 23.8-inch     | 1        | 0.59%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.59%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 78       | 49.37%  |
| 1366x768 (WXGA)    | 14       | 8.86%   |
| 1600x900 (HD+)     | 13       | 8.23%   |
| 3840x2160 (4K)     | 9        | 5.7%    |
| 1440x900 (WXGA+)   | 9        | 5.7%    |
| 1680x1050 (WSXGA+) | 8        | 5.06%   |
| 2560x1440 (QHD)    | 5        | 3.16%   |
| 1280x1024 (SXGA)   | 5        | 3.16%   |
| 2560x1080          | 4        | 2.53%   |
| Unknown            | 4        | 2.53%   |
| 3840x1080          | 2        | 1.27%   |
| 1360x768           | 2        | 1.27%   |
| 3440x1440          | 1        | 0.63%   |
| 2732x768           | 1        | 0.63%   |
| 2560x1600          | 1        | 0.63%   |
| 1600x1200          | 1        | 0.63%   |
| 1280x720 (HD)      | 1        | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 27       | 16.77%  |
| 21      | 17       | 10.56%  |
| 24      | 16       | 9.94%   |
| Unknown | 16       | 9.94%   |
| 18      | 15       | 9.32%   |
| 27      | 14       | 8.7%    |
| 19      | 13       | 8.07%   |
| 20      | 12       | 7.45%   |
| 22      | 6        | 3.73%   |
| 34      | 5        | 3.11%   |
| 17      | 3        | 1.86%   |
| 15      | 3        | 1.86%   |
| 72      | 2        | 1.24%   |
| 52      | 2        | 1.24%   |
| 47      | 2        | 1.24%   |
| 31      | 2        | 1.24%   |
| 84      | 1        | 0.62%   |
| 60      | 1        | 0.62%   |
| 54      | 1        | 0.62%   |
| 39      | 1        | 0.62%   |
| 29      | 1        | 0.62%   |
| 16      | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 61       | 39.1%   |
| 501-600     | 53       | 33.97%  |
| Unknown     | 16       | 10.26%  |
| 301-350     | 6        | 3.85%   |
| 1001-1500   | 6        | 3.85%   |
| 701-800     | 5        | 3.21%   |
| 601-700     | 3        | 1.92%   |
| 351-400     | 3        | 1.92%   |
| 1501-2000   | 2        | 1.28%   |
| 801-900     | 1        | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 105      | 69.54%  |
| 16/10   | 20       | 13.25%  |
| Unknown | 15       | 9.93%   |
| 5/4     | 5        | 3.31%   |
| 21/9    | 5        | 3.31%   |
| 4/3     | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 36.71%  |
| 151-200        | 29       | 18.35%  |
| Unknown        | 16       | 10.13%  |
| 301-350        | 14       | 8.86%   |
| 141-150        | 14       | 8.86%   |
| 351-500        | 8        | 5.06%   |
| More than 1000 | 6        | 3.8%    |
| 251-300        | 4        | 2.53%   |
| 101-110        | 3        | 1.9%    |
| 501-1000       | 3        | 1.9%    |
| 131-140        | 2        | 1.27%   |
| 121-130        | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 95       | 64.19%  |
| 101-120 | 24       | 16.22%  |
| Unknown | 16       | 10.81%  |
| 1-50    | 7        | 4.73%   |
| 161-240 | 4        | 2.7%    |
| 121-160 | 2        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 127      | 77.91%  |
| 2     | 21       | 12.88%  |
| 0     | 12       | 7.36%   |
| 3     | 3        | 1.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 106      | 46.7%   |
| Intel                           | 52       | 22.91%  |
| Qualcomm Atheros                | 15       | 6.61%   |
| Ralink Technology               | 10       | 4.41%   |
| D-Link                          | 7        | 3.08%   |
| Broadcom                        | 7        | 3.08%   |
| TP-Link                         | 5        | 2.2%    |
| Nvidia                          | 5        | 2.2%    |
| D-Link System                   | 3        | 1.32%   |
| Samsung Electronics             | 2        | 0.88%   |
| Ralink                          | 2        | 0.88%   |
| Mercucys                        | 2        | 0.88%   |
| MediaTek                        | 2        | 0.88%   |
| Xiaomi                          | 1        | 0.44%   |
| VIA Technologies                | 1        | 0.44%   |
| Qualcomm Atheros Communications | 1        | 0.44%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.44%   |
| Huawei Technologies             | 1        | 0.44%   |
| Edimax Technology               | 1        | 0.44%   |
| BUFFALO                         | 1        | 0.44%   |
| ASUSTek Computer                | 1        | 0.44%   |
| Aquantia                        | 1        | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90       | 35.16%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 2.34%   |
| Intel I211 Gigabit Network Connection                             | 6        | 2.34%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.95%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.95%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 1.95%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.56%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.56%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]     | 4        | 1.56%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.17%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.78%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.78%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.78%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.78%   |
| Mercucys 802.11n NIC                                              | 2        | 0.78%   |
| Intel Wireless-AC 9260                                            | 2        | 0.78%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.78%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.78%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.78%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.39%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.39%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 1        | 0.39%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.39%   |
| TP-Link 802.11ac NIC                                              | 1        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 25.3%   |
| Intel                           | 14       | 16.87%  |
| Qualcomm Atheros                | 12       | 14.46%  |
| Ralink Technology               | 10       | 12.05%  |
| D-Link                          | 7        | 8.43%   |
| TP-Link                         | 5        | 6.02%   |
| Broadcom                        | 3        | 3.61%   |
| Ralink                          | 2        | 2.41%   |
| Mercucys                        | 2        | 2.41%   |
| MediaTek                        | 2        | 2.41%   |
| Qualcomm Atheros Communications | 1        | 1.2%    |
| Edimax Technology               | 1        | 1.2%    |
| D-Link System                   | 1        | 1.2%    |
| BUFFALO                         | 1        | 1.2%    |
| ASUSTek Computer                | 1        | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 7.14%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 5.95%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 4.76%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 4        | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 3.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 2.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 2.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 2.38%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 2        | 2.38%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 2        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2        | 2.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 2.38%   |
| Mercucys 802.11n NIC                                                   | 2        | 2.38%   |
| Intel Wireless-AC 9260                                                 | 2        | 2.38%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 2.38%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 1        | 1.19%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 1.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 1.19%   |
| TP-Link 802.11ac NIC                                                   | 1        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.19%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.19%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 1.19%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 1.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 1.19%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 1.19%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                   | 1        | 1.19%   |
| Ralink RT2561/RT61 rev B 802.11g                                       | 1        | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 1.19%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.19%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 1.19%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.19%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]    | 1        | 1.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 100      | 60.24%  |
| Intel                         | 45       | 27.11%  |
| Nvidia                        | 5        | 3.01%   |
| Qualcomm Atheros              | 4        | 2.41%   |
| Broadcom                      | 4        | 2.41%   |
| Samsung Electronics           | 2        | 1.2%    |
| D-Link System                 | 2        | 1.2%    |
| Xiaomi                        | 1        | 0.6%    |
| VIA Technologies              | 1        | 0.6%    |
| OnePlus Technology (Shenzhen) | 1        | 0.6%    |
| Aquantia                      | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 90       | 52.63%  |
| Intel I211 Gigabit Network Connection                                         | 6        | 3.51%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 3.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 2.92%   |
| Intel Ethernet Connection I217-V                                              | 5        | 2.92%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 2.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 2.34%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 2.34%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2        | 1.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 1.17%   |
| Nvidia MCP73 Ethernet                                                         | 2        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.17%   |
| Intel Ethernet Connection (12) I219-V                                         | 2        | 1.17%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 1.17%   |
| Xiaomi 100Mbps Network Card Adapter                                           | 1        | 0.58%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                             | 1        | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.58%   |
| OnePlus (Shenzhen) Android                                                    | 1        | 0.58%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.58%   |
| Intel I210 Gigabit Unprogrammed                                               | 1        | 0.58%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.58%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.58%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.58%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.58%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.58%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                       | 1        | 0.58%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 65.38%  |
| WiFi     | 80       | 34.19%  |
| Modem    | 1        | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 63.52%  |
| WiFi     | 58       | 36.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 64.56%  |
| 2     | 46       | 29.11%  |
| 0     | 4        | 2.53%   |
| 3     | 3        | 1.9%    |
| 4     | 2        | 1.27%   |
| 5     | 1        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 73.17%  |
| Yes  | 44       | 26.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 20       | 46.51%  |
| Intel                           | 12       | 27.91%  |
| ASUSTek Computer                | 3        | 6.98%   |
| Qualcomm Atheros Communications | 2        | 4.65%   |
| MediaTek                        | 2        | 4.65%   |
| Realtek Semiconductor           | 1        | 2.33%   |
| Lite-On Technology              | 1        | 2.33%   |
| Broadcom                        | 1        | 2.33%   |
| Apple                           | 1        | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 46.51%  |
| Intel Bluetooth wireless interface                  | 3        | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6.98%   |
| MediaTek Wireless_Device                            | 2        | 4.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.65%   |
| Intel AX200 Bluetooth                               | 2        | 4.65%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 2.33%   |
| Broadcom HP Portable Valentine                      | 1        | 2.33%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.33%   |
| ASUS Bluetooth Device                               | 1        | 2.33%   |
| Apple Bluetooth HCI                                 | 1        | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 104      | 39.25%  |
| Nvidia                      | 66       | 24.91%  |
| AMD                         | 64       | 24.15%  |
| C-Media Electronics         | 11       | 4.15%   |
| JMTek                       | 4        | 1.51%   |
| Razer USA                   | 3        | 1.13%   |
| SAVITECH                    | 2        | 0.75%   |
| Elan Microelectronics       | 2        | 0.75%   |
| VIA Technologies            | 1        | 0.38%   |
| Texas Instruments           | 1        | 0.38%   |
| Nordic Semiconductor ASA    | 1        | 0.38%   |
| Kingston Technology         | 1        | 0.38%   |
| Generalplus Technology      | 1        | 0.38%   |
| ESS Technology              | 1        | 0.38%   |
| Earth Computer Technologies | 1        | 0.38%   |
| Creative Labs               | 1        | 0.38%   |
| Blue Microphones            | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 5.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16       | 5%      |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 3.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 3.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.81%   |
| Nvidia High Definition Audio Controller                                    | 8        | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 2.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 2.5%    |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.19%   |
| AMD FCH Azalia Controller                                                  | 7        | 2.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 2.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.88%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.56%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 1.25%   |
| JMTek USB PnP Audio Device                                                 | 4        | 1.25%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.25%   |
| C-Media Electronics USB Audio Device                                       | 4        | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.25%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.94%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.94%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 0.94%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 0.94%   |
| SAVITECH SA9023 audio controller                                           | 2        | 0.63%   |
| Nvidia MCP73 High Definition Audio                                         | 2        | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 29       | 42.03%  |
| Unknown             | 10       | 14.49%  |
| Corsair             | 9        | 13.04%  |
| SK hynix            | 8        | 11.59%  |
| Samsung Electronics | 6        | 8.7%    |
| G.Skill             | 2        | 2.9%    |
| Unknown (0x02BA)    | 1        | 1.45%   |
| Transcend           | 1        | 1.45%   |
| Team                | 1        | 1.45%   |
| A-DATA Technology   | 1        | 1.45%   |
| Unknown             | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 5        | 6.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 3        | 4%      |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s      | 3        | 4%      |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 2        | 2.67%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s            | 2        | 2.67%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 2        | 2.67%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 2.67%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 2.67%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 2        | 2.67%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s       | 2        | 2.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 1.33%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 1.33%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s   | 1        | 1.33%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s          | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s       | 1        | 1.33%   |
| SK hynix RAM Module 1024MB FB-DIMM DDR2 800MT/s           | 1        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| SK hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1        | 1.33%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 1.33%   |
| SK hynix RAM HMA84GL7AMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 1.33%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1        | 1.33%   |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s      | 1        | 1.33%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s            | 1        | 1.33%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s    | 1        | 1.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.33%   |
| Kingston RAM Module 2GB DIMM DDR 533MT/s                  | 1        | 1.33%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 1.33%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s       | 1        | 1.33%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.33%   |
| Kingston RAM KHX2666C16D4/16GX 16384MB DIMM DDR4 2667MT/s | 1        | 1.33%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s       | 1        | 1.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 1        | 1.33%   |
| Kingston RAM KHX1600C9D3/8 8GB DIMM DDR3 1333MT/s         | 1        | 1.33%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s       | 1        | 1.33%   |
| Kingston RAM KF556C40-16 16GB DIMM DDR5 5600MT/s          | 1        | 1.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 42.86%  |
| DDR3    | 21       | 33.33%  |
| SDRAM   | 5        | 7.94%   |
| Unknown | 4        | 6.35%   |
| DDR2    | 2        | 3.17%   |
| DDR     | 2        | 3.17%   |
| LPDDR4  | 1        | 1.59%   |
| DDR5    | 1        | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 54       | 91.53%  |
| SODIMM  | 3        | 5.08%   |
| RIMM    | 1        | 1.69%   |
| FB-DIMM | 1        | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 39.06%  |
| 4096  | 18       | 28.13%  |
| 2048  | 10       | 15.63%  |
| 16384 | 7        | 10.94%  |
| 32768 | 2        | 3.13%   |
| 1024  | 2        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 15       | 22.06%  |
| 1600    | 11       | 16.18%  |
| 3600    | 6        | 8.82%   |
| 3200    | 4        | 5.88%   |
| 2400    | 4        | 5.88%   |
| 2133    | 3        | 4.41%   |
| 1867    | 3        | 4.41%   |
| 3466    | 2        | 2.94%   |
| 3400    | 2        | 2.94%   |
| 3151    | 2        | 2.94%   |
| 3000    | 2        | 2.94%   |
| 2667    | 2        | 2.94%   |
| 1866    | 2        | 2.94%   |
| 667     | 2        | 2.94%   |
| 5600    | 1        | 1.47%   |
| 3534    | 1        | 1.47%   |
| 3333    | 1        | 1.47%   |
| 2800    | 1        | 1.47%   |
| 2666    | 1        | 1.47%   |
| 800     | 1        | 1.47%   |
| 533     | 1        | 1.47%   |
| Unknown | 1        | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 4        | 44.44%  |
| Seiko Epson        | 2        | 22.22%  |
| STMicroelectronics | 1        | 11.11%  |
| Pantum             | 1        | 11.11%  |
| Canon              | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| STMicroelectronics USB Printer P | 1        | 11.11%  |
| Seiko Epson LQ-310               | 1        | 11.11%  |
| Seiko Epson L220 Series          | 1        | 11.11%  |
| Pantum P2500W series             | 1        | 11.11%  |
| Canon E4200 series               | 1        | 11.11%  |
| Brother HL-1110 series           | 1        | 11.11%  |
| Brother DCP-T510W                | 1        | 11.11%  |
| Brother DCP-T300                 | 1        | 11.11%  |
| Brother DCP-L3551CDW             | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 33.33%  |
| Microdia                      | 4        | 19.05%  |
| Aveo Technology               | 3        | 14.29%  |
| Suyin                         | 1        | 4.76%   |
| Sunplus Innovation Technology | 1        | 4.76%   |
| Realtek Semiconductor         | 1        | 4.76%   |
| Owon                          | 1        | 4.76%   |
| Microsoft                     | 1        | 4.76%   |
| Generalplus Technology        | 1        | 4.76%   |
| Apple                         | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microdia Camera                      | 3        | 14.29%  |
| Logitech Webcam C310                 | 2        | 9.52%   |
| Aveo USB2.0 Camera                   | 2        | 9.52%   |
| Suyin HP Integrated Webcam           | 1        | 4.76%   |
| Sunplus AAPDQT-0622-W                | 1        | 4.76%   |
| Realtek USB Boot                     | 1        | 4.76%   |
| Owon USB CAMERA                      | 1        | 4.76%   |
| Microsoft MicrosoftÂ LifeCam Cinema | 1        | 4.76%   |
| Microdia Integrated Camera           | 1        | 4.76%   |
| Logitech Webcam C600                 | 1        | 4.76%   |
| Logitech Webcam C270                 | 1        | 4.76%   |
| Logitech Mic (Notebooks Pro)         | 1        | 4.76%   |
| Logitech HD Webcam C525              | 1        | 4.76%   |
| Logitech HD Webcam C510              | 1        | 4.76%   |
| Generalplus GENERAL WEBCAM           | 1        | 4.76%   |
| Aveo UVC camera (Bresser microscope) | 1        | 4.76%   |
| Apple iPad 2 (3G; 64GB)              | 1        | 4.76%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 134      | 85.35%  |
| 1     | 19       | 12.1%   |
| 2     | 2        | 1.27%   |
| 7     | 1        | 0.64%   |
| 5     | 1        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 31.03%  |
| Net/wireless             | 6        | 20.69%  |
| Sound                    | 5        | 17.24%  |
| Communication controller | 4        | 13.79%  |
| Unassigned class         | 3        | 10.34%  |
| Network                  | 1        | 3.45%   |
| Net/ethernet             | 1        | 3.45%   |

