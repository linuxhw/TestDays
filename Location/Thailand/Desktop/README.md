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

Total: 209

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 27       | 18.62%  |
| Ubuntu 18.04                 | 23       | 15.86%  |
| OpenMandriva 4.2             | 7        | 4.83%   |
| Manjaro                      | 6        | 4.14%   |
| OpenMandriva 4.3             | 5        | 3.45%   |
| Arch Rolling                 | 5        | 3.45%   |
| Ubuntu 22.04                 | 4        | 2.76%   |
| Xubuntu 20.04                | 3        | 2.07%   |
| KDE neon 20.04               | 3        | 2.07%   |
| Zorin 15                     | 2        | 1.38%   |
| Xubuntu 18.04                | 2        | 1.38%   |
| Ubuntu 21.10                 | 2        | 1.38%   |
| Ubuntu 19.10                 | 2        | 1.38%   |
| Reborn OS                    | 2        | 1.38%   |
| Pop!_OS 22.04                | 2        | 1.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.38%   |
| Linux Mint 21                | 2        | 1.38%   |
| Linux Mint 20                | 2        | 1.38%   |
| Fedora 36                    | 2        | 1.38%   |
| Endless 3.9.5                | 2        | 1.38%   |
| Endless 3.7.6                | 2        | 1.38%   |
| Arch                         | 2        | 1.38%   |
| Zorin 16                     | 1        | 0.69%   |
| Xubuntu 21.10                | 1        | 0.69%   |
| UbuntuDDE 20.04              | 1        | 0.69%   |
| Ubuntu MATE 18.04            | 1        | 0.69%   |
| Ubuntu Budgie 20.10          | 1        | 0.69%   |
| Ubuntu 21.04                 | 1        | 0.69%   |
| Ubuntu 19.04                 | 1        | 0.69%   |
| Ubuntu 16.04                 | 1        | 0.69%   |
| Solus 4.3                    | 1        | 0.69%   |
| Pop!_OS 21.10                | 1        | 0.69%   |
| Pop!_OS 21.04                | 1        | 0.69%   |
| Pop!_OS 20.10                | 1        | 0.69%   |
| Pop!_OS 20.04                | 1        | 0.69%   |
| OpenMandriva 4.50            | 1        | 0.69%   |
| Manjaro 18.1.3               | 1        | 0.69%   |
| Linux Mint 20.3              | 1        | 0.69%   |
| Linux Mint 20.2              | 1        | 0.69%   |
| Linux Mint 19.3              | 1        | 0.69%   |
| Linux Mint 19.2              | 1        | 0.69%   |
| Linux Mint 19.1              | 1        | 0.69%   |
| Fedora 35                    | 1        | 0.69%   |
| Fedora 33                    | 1        | 0.69%   |
| Fedora 32                    | 1        | 0.69%   |
| Fedora 29                    | 1        | 0.69%   |
| Endless 3.9.3                | 1        | 0.69%   |
| Endless 3.9.0                | 1        | 0.69%   |
| Endless 3.8.1                | 1        | 0.69%   |
| Endless 3.6.1-nexthw1        | 1        | 0.69%   |
| Elementary 6.1               | 1        | 0.69%   |
| Elementary 5.1.7             | 1        | 0.69%   |
| Debian Testing               | 1        | 0.69%   |
| Clear Linux 36250            | 1        | 0.69%   |
| Clear Linux                  | 1        | 0.69%   |
| CentOS 8                     | 1        | 0.69%   |
| BlackPanther 18.1            | 1        | 0.69%   |
| ArcoLinux Rolling            | 1        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 59       | 42.45%  |
| OpenMandriva  | 13       | 9.35%   |
| Linux Mint    | 9        | 6.47%   |
| Arch          | 7        | 5.04%   |
| Xubuntu       | 6        | 4.32%   |
| Pop!_OS       | 6        | 4.32%   |
| Manjaro       | 6        | 4.32%   |
| Endless       | 6        | 4.32%   |
| Fedora        | 5        | 3.6%    |
| Zorin         | 3        | 2.16%   |
| KDE neon      | 3        | 2.16%   |
| Reborn OS     | 2        | 1.44%   |
| openSUSE      | 2        | 1.44%   |
| Elementary    | 2        | 1.44%   |
| Clear Linux   | 2        | 1.44%   |
| UbuntuDDE     | 1        | 0.72%   |
| Ubuntu MATE   | 1        | 0.72%   |
| Ubuntu Budgie | 1        | 0.72%   |
| Solus         | 1        | 0.72%   |
| Debian        | 1        | 0.72%   |
| CentOS        | 1        | 0.72%   |
| BlackPanther  | 1        | 0.72%   |
| ArcoLinux     | 1        | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 4.61%   |
| 5.4.0-48-generic         | 4        | 2.63%   |
| 5.16.7-desktop-1omv4003  | 4        | 2.63%   |
| 5.15.0-46-generic        | 4        | 2.63%   |
| 5.8.0-14-generic         | 3        | 1.97%   |
| 5.4.0-42-generic         | 3        | 1.97%   |
| 5.8.0-63-generic         | 2        | 1.32%   |
| 5.4.0-77-generic         | 2        | 1.32%   |
| 5.4.0-66-generic         | 2        | 1.32%   |
| 5.4.0-65-generic         | 2        | 1.32%   |
| 5.4.0-59-generic         | 2        | 1.32%   |
| 5.4.0-45-generic         | 2        | 1.32%   |
| 5.4.0-37-generic         | 2        | 1.32%   |
| 5.3.0-23-generic         | 2        | 1.32%   |
| 5.17.5-76051705-generic  | 2        | 1.32%   |
| 5.17.3-arch1-1           | 2        | 1.32%   |
| 5.15.0-43-generic        | 2        | 1.32%   |
| 5.13.0-51-generic        | 2        | 1.32%   |
| 5.13.0-22-generic        | 2        | 1.32%   |
| 5.11.0-41-generic        | 2        | 1.32%   |
| 5.11.0-37-generic        | 2        | 1.32%   |
| 5.0.0-37-generic         | 2        | 1.32%   |
| 5.0.0-23-generic         | 2        | 1.32%   |
| 5.9.16-1-MANJARO         | 1        | 0.66%   |
| 5.8.1-arch1-1            | 1        | 0.66%   |
| 5.8.0-7630-generic       | 1        | 0.66%   |
| 5.8.0-59-generic         | 1        | 0.66%   |
| 5.8.0-48-generic         | 1        | 0.66%   |
| 5.8.0-43-generic         | 1        | 0.66%   |
| 5.8.0-41-generic         | 1        | 0.66%   |
| 5.8.0-2-amd64            | 1        | 0.66%   |
| 5.8.0-1-default          | 1        | 0.66%   |
| 5.7.13-975.native        | 1        | 0.66%   |
| 5.6.6-300.fc32.x86_64    | 1        | 0.66%   |
| 5.6.2-arch1-2            | 1        | 0.66%   |
| 5.6.16-300.fc32.x86_64   | 1        | 0.66%   |
| 5.6.14-desktop-2bP       | 1        | 0.66%   |
| 5.5.7-arch1-1            | 1        | 0.66%   |
| 5.5.7-1-MANJARO          | 1        | 0.66%   |
| 5.4.82-1-lts             | 1        | 0.66%   |
| 5.4.80-hiveos            | 1        | 0.66%   |
| 5.4.0-99-generic         | 1        | 0.66%   |
| 5.4.0-91-generic         | 1        | 0.66%   |
| 5.4.0-80-generic         | 1        | 0.66%   |
| 5.4.0-7642-generic       | 1        | 0.66%   |
| 5.4.0-51-generic         | 1        | 0.66%   |
| 5.4.0-39-generic         | 1        | 0.66%   |
| 5.4.0-33-generic         | 1        | 0.66%   |
| 5.4.0-29-generic         | 1        | 0.66%   |
| 5.4.0-26-generic         | 1        | 0.66%   |
| 5.4.0-19-generic         | 1        | 0.66%   |
| 5.4.0-124-generic        | 1        | 0.66%   |
| 5.4.0-120-generic        | 1        | 0.66%   |
| 5.4.0-113-generic        | 1        | 0.66%   |
| 5.4.0-107-generic        | 1        | 0.66%   |
| 5.3.12-1-MANJARO         | 1        | 0.66%   |
| 5.3.0-53-generic         | 1        | 0.66%   |
| 5.3.0-45-generic         | 1        | 0.66%   |
| 5.3.0-40-generic         | 1        | 0.66%   |
| 5.3.0-29-generic         | 1        | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 21.48%  |
| 5.8.0   | 12       | 8.05%   |
| 5.13.0  | 11       | 7.38%   |
| 4.15.0  | 11       | 7.38%   |
| 5.3.0   | 8        | 5.37%   |
| 5.10.14 | 7        | 4.7%    |
| 5.0.0   | 7        | 4.7%    |
| 5.15.0  | 6        | 4.03%   |
| 5.11.0  | 6        | 4.03%   |
| 4.18.0  | 5        | 3.36%   |
| 5.16.7  | 4        | 2.68%   |
| 5.17.5  | 3        | 2.01%   |
| 5.5.7   | 2        | 1.34%   |
| 5.17.3  | 2        | 1.34%   |
| 5.9.16  | 1        | 0.67%   |
| 5.8.1   | 1        | 0.67%   |
| 5.7.13  | 1        | 0.67%   |
| 5.6.6   | 1        | 0.67%   |
| 5.6.2   | 1        | 0.67%   |
| 5.6.16  | 1        | 0.67%   |
| 5.6.14  | 1        | 0.67%   |
| 5.4.82  | 1        | 0.67%   |
| 5.4.80  | 1        | 0.67%   |
| 5.3.12  | 1        | 0.67%   |
| 5.18.5  | 1        | 0.67%   |
| 5.17.6  | 1        | 0.67%   |
| 5.17.4  | 1        | 0.67%   |
| 5.17.1  | 1        | 0.67%   |
| 5.16.9  | 1        | 0.67%   |
| 5.16.2  | 1        | 0.67%   |
| 5.16.19 | 1        | 0.67%   |
| 5.16.13 | 1        | 0.67%   |
| 5.16.11 | 1        | 0.67%   |
| 5.16.0  | 1        | 0.67%   |
| 5.15.4  | 1        | 0.67%   |
| 5.15.2  | 1        | 0.67%   |
| 5.15.14 | 1        | 0.67%   |
| 5.14.6  | 1        | 0.67%   |
| 5.14.16 | 1        | 0.67%   |
| 5.13.19 | 1        | 0.67%   |
| 5.13.13 | 1        | 0.67%   |
| 5.13.1  | 1        | 0.67%   |
| 5.12.9  | 1        | 0.67%   |
| 5.10.16 | 1        | 0.67%   |
| 5.1.0   | 1        | 0.67%   |
| 5.0.17  | 1        | 0.67%   |
| 4.4.0   | 1        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 22.97%  |
| 5.13    | 14       | 9.46%   |
| 5.8     | 13       | 8.78%   |
| 4.15    | 11       | 7.43%   |
| 5.16    | 10       | 6.76%   |
| 5.3     | 9        | 6.08%   |
| 5.15    | 9        | 6.08%   |
| 5.17    | 8        | 5.41%   |
| 5.10    | 8        | 5.41%   |
| 5.0     | 8        | 5.41%   |
| 5.11    | 6        | 4.05%   |
| 4.18    | 5        | 3.38%   |
| 5.6     | 3        | 2.03%   |
| 5.5     | 2        | 1.35%   |
| 5.14    | 2        | 1.35%   |
| 5.9     | 1        | 0.68%   |
| 5.7     | 1        | 0.68%   |
| 5.18    | 1        | 0.68%   |
| 5.12    | 1        | 0.68%   |
| 5.1     | 1        | 0.68%   |
| 4.4     | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 133      | 99.25%  |
| i686   | 1        | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 73       | 52.14%  |
| KDE5       | 18       | 12.86%  |
| Unknown    | 18       | 12.86%  |
| XFCE       | 9        | 6.43%   |
| X-Cinnamon | 9        | 6.43%   |
| MATE       | 3        | 2.14%   |
| KDE        | 3        | 2.14%   |
| Pantheon   | 2        | 1.43%   |
| Deepin     | 2        | 1.43%   |
| Budgie     | 2        | 1.43%   |
| Cinnamon   | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 111      | 81.02%  |
| Wayland | 12       | 8.76%   |
| Unknown | 12       | 8.76%   |
| Tty     | 2        | 1.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 88       | 63.77%  |
| SDDM    | 16       | 11.59%  |
| GDM3    | 12       | 8.7%    |
| GDM     | 11       | 7.97%   |
| LightDM | 8        | 5.8%    |
| TDM     | 3        | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 93       | 67.39%  |
| Unknown | 16       | 11.59%  |
| th_TH   | 10       | 7.25%   |
| en_GB   | 8        | 5.8%    |
| de_DE   | 5        | 3.62%   |
| C       | 3        | 2.17%   |
| sv_SE   | 1        | 0.72%   |
| it_IT   | 1        | 0.72%   |
| de_CH   | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 88       | 63.31%  |
| EFI  | 51       | 36.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 113      | 82.48%  |
| Overlay | 12       | 8.76%   |
| Btrfs   | 4        | 2.92%   |
| Unknown | 4        | 2.92%   |
| Xfs     | 3        | 2.19%   |
| Zfs     | 1        | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 98       | 72.06%  |
| GPT     | 29       | 21.32%  |
| MBR     | 9        | 6.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 80.74%  |
| Yes       | 26       | 19.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 57.66%  |
| Yes       | 58       | 42.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 28       | 20.9%   |
| ASUSTek Computer    | 28       | 20.9%   |
| ASRock              | 21       | 15.67%  |
| MSI                 | 15       | 11.19%  |
| Dell                | 10       | 7.46%   |
| Hewlett-Packard     | 9        | 6.72%   |
| Acer                | 6        | 4.48%   |
| Unknown             | 3        | 2.24%   |
| Intel               | 2        | 1.49%   |
| Huanan              | 2        | 1.49%   |
| VIA Technologies    | 1        | 0.75%   |
| SHARKBAY            | 1        | 0.75%   |
| Pegatron            | 1        | 0.75%   |
| Packard Bell        | 1        | 0.75%   |
| OEM                 | 1        | 0.75%   |
| MiTAC               | 1        | 0.75%   |
| Fujitsu             | 1        | 0.75%   |
| Biostar             | 1        | 0.75%   |
| Apple               | 1        | 0.75%   |
| AFOX                | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 4        | 2.99%   |
| Unknown                    | 4        | 2.99%   |
| Dell OptiPlex 7010         | 3        | 2.24%   |
| ASUS P8H61-M LE            | 3        | 2.24%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 1.49%   |
| Gigabyte Z97X-UD3H-BK      | 2        | 1.49%   |
| Gigabyte B250-HD3          | 2        | 1.49%   |
| ASUS H110M-E/M.2           | 2        | 1.49%   |
| ASRock B450 Steel Legend   | 2        | 1.49%   |
| Acer Aspire TC-885         | 2        | 1.49%   |
| VIA VX900                  | 1        | 0.75%   |
| Pegatron CQ3476L           | 1        | 0.75%   |
| Packard Bell IMEDIA S3720  | 1        | 0.75%   |
| OEM Intel H81              | 1        | 0.75%   |
| MSI Pro 3130 Microtower PC | 1        | 0.75%   |
| MSI Pro 2000/2080          | 1        | 0.75%   |
| MSI p6772l                 | 1        | 0.75%   |
| MSI MS-7C52                | 1        | 0.75%   |
| MSI MS-7C35                | 1        | 0.75%   |
| MSI MS-7B89                | 1        | 0.75%   |
| MSI MS-7B85                | 1        | 0.75%   |
| MSI MS-7A63                | 1        | 0.75%   |
| MSI MS-7A38                | 1        | 0.75%   |
| MSI MS-7A32                | 1        | 0.75%   |
| MSI MS-7A15                | 1        | 0.75%   |
| MSI MS-7978                | 1        | 0.75%   |
| MSI MS-7914                | 1        | 0.75%   |
| MSI MS-7641                | 1        | 0.75%   |
| MSI KY779AA-AKL CQ3070L    | 1        | 0.75%   |
| MiTAC PD14RI               | 1        | 0.75%   |
| Intel H61M S1              | 1        | 0.75%   |
| Intel D54250WYK H13922-305 | 1        | 0.75%   |
| Huanan X79 V6.11           | 1        | 0.75%   |
| Huanan X79 249PC V2.2      | 1        | 0.75%   |
| HP Z800 Workstation        | 1        | 0.75%   |
| HP ProDesk 600 G3 SFF      | 1        | 0.75%   |
| HP ProDesk 600 G1 SFF      | 1        | 0.75%   |
| HP ProDesk 400 G3 SFF      | 1        | 0.75%   |
| HP Compaq 6200 Pro SFF PC  | 1        | 0.75%   |
| HP Compaq 6000 Pro SFF PC  | 1        | 0.75%   |
| HP 20-2300x                | 1        | 0.75%   |
| Gigabyte Z97X-UD3H         | 1        | 0.75%   |
| Gigabyte Z490 UD           | 1        | 0.75%   |
| Gigabyte Z390 UD           | 1        | 0.75%   |
| Gigabyte Z390 AORUS MASTER | 1        | 0.75%   |
| Gigabyte P67A-UD3P-B3      | 1        | 0.75%   |
| Gigabyte M52L-S3           | 1        | 0.75%   |
| Gigabyte H81M-DS2          | 1        | 0.75%   |
| Gigabyte H67MA-USB3-B3     | 1        | 0.75%   |
| Gigabyte H370M-D3H         | 1        | 0.75%   |
| Gigabyte H310M S2H 2.0     | 1        | 0.75%   |
| Gigabyte H110M-DS2V        | 1        | 0.75%   |
| Gigabyte H110M-DS2         | 1        | 0.75%   |
| Gigabyte GA-970A-DS3       | 1        | 0.75%   |
| Gigabyte GA-78LMT-USB3 R2  | 1        | 0.75%   |
| Gigabyte GA-78LMT-USB3 6.0 | 1        | 0.75%   |
| Gigabyte G41M-ES2H         | 1        | 0.75%   |
| Gigabyte G31M-ES2L         | 1        | 0.75%   |
| Gigabyte F2A88XM-HD3P      | 1        | 0.75%   |
| Gigabyte F2A85XM-HD3       | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 7        | 5.22%   |
| Acer Aspire            | 5        | 3.73%   |
| ASUS PRIME             | 4        | 2.99%   |
| ASUS All               | 4        | 2.99%   |
| Unknown                | 4        | 2.99%   |
| HP ProDesk             | 3        | 2.24%   |
| ASUS P8H61-M           | 3        | 2.24%   |
| ASRock B450            | 3        | 2.24%   |
| MSI Pro                | 2        | 1.49%   |
| Huanan X79             | 2        | 1.49%   |
| HP EliteDesk           | 2        | 1.49%   |
| HP Compaq              | 2        | 1.49%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 1.49%   |
| Gigabyte Z390          | 2        | 1.49%   |
| Gigabyte GA-78LMT-USB3 | 2        | 1.49%   |
| Gigabyte B250-HD3      | 2        | 1.49%   |
| Dell Precision         | 2        | 1.49%   |
| ASUS ROG               | 2        | 1.49%   |
| ASUS M5A78L-M          | 2        | 1.49%   |
| ASUS H110M-E           | 2        | 1.49%   |
| ASRock Z77             | 2        | 1.49%   |
| ASRock B450M           | 2        | 1.49%   |
| VIA VX900              | 1        | 0.75%   |
| Pegatron CQ3476L       | 1        | 0.75%   |
| Packard Bell IMEDIA    | 1        | 0.75%   |
| OEM Intel              | 1        | 0.75%   |
| MSI p6772l             | 1        | 0.75%   |
| MSI MS-7C52            | 1        | 0.75%   |
| MSI MS-7C35            | 1        | 0.75%   |
| MSI MS-7B89            | 1        | 0.75%   |
| MSI MS-7B85            | 1        | 0.75%   |
| MSI MS-7A63            | 1        | 0.75%   |
| MSI MS-7A38            | 1        | 0.75%   |
| MSI MS-7A32            | 1        | 0.75%   |
| MSI MS-7A15            | 1        | 0.75%   |
| MSI MS-7978            | 1        | 0.75%   |
| MSI MS-7914            | 1        | 0.75%   |
| MSI MS-7641            | 1        | 0.75%   |
| MSI KY779AA-AKL        | 1        | 0.75%   |
| MiTAC PD14RI           | 1        | 0.75%   |
| Intel H61M             | 1        | 0.75%   |
| Intel D54250WYK        | 1        | 0.75%   |
| HP Z800                | 1        | 0.75%   |
| HP 20-2300x            | 1        | 0.75%   |
| Gigabyte Z97X-UD3H     | 1        | 0.75%   |
| Gigabyte Z490          | 1        | 0.75%   |
| Gigabyte P67A-UD3P-B3  | 1        | 0.75%   |
| Gigabyte M52L-S3       | 1        | 0.75%   |
| Gigabyte H81M-DS2      | 1        | 0.75%   |
| Gigabyte H67MA-USB3-B3 | 1        | 0.75%   |
| Gigabyte H370M-D3H     | 1        | 0.75%   |
| Gigabyte H310M         | 1        | 0.75%   |
| Gigabyte H110M-DS2V    | 1        | 0.75%   |
| Gigabyte H110M-DS2     | 1        | 0.75%   |
| Gigabyte GA-970A-DS3   | 1        | 0.75%   |
| Gigabyte G41M-ES2H     | 1        | 0.75%   |
| Gigabyte G31M-ES2L     | 1        | 0.75%   |
| Gigabyte F2A88XM-HD3P  | 1        | 0.75%   |
| Gigabyte F2A85XM-HD3   | 1        | 0.75%   |
| Gigabyte F2A75M-HD2    | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 21       | 15.67%  |
| 2013 | 12       | 8.96%   |
| 2019 | 11       | 8.21%   |
| 2016 | 11       | 8.21%   |
| 2012 | 11       | 8.21%   |
| 2020 | 10       | 7.46%   |
| 2014 | 10       | 7.46%   |
| 2011 | 10       | 7.46%   |
| 2017 | 9        | 6.72%   |
| 2009 | 9        | 6.72%   |
| 2010 | 5        | 3.73%   |
| 2015 | 4        | 2.99%   |
| 2008 | 4        | 2.99%   |
| 2021 | 3        | 2.24%   |
| 2006 | 2        | 1.49%   |
| 2007 | 1        | 0.75%   |
| 2005 | 1        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 134      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 132      | 97.78%  |
| Enabled  | 3        | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 134      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 33       | 23.74%  |
| 16.01-24.0      | 32       | 23.02%  |
| 4.01-8.0        | 25       | 17.99%  |
| 3.01-4.0        | 24       | 17.27%  |
| 32.01-64.0      | 14       | 10.07%  |
| 1.01-2.0        | 6        | 4.32%   |
| 64.01-256.0     | 2        | 1.44%   |
| More than 256.0 | 1        | 0.72%   |
| 24.01-32.0      | 1        | 0.72%   |
| 0.51-1.0        | 1        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 55       | 36.91%  |
| 2.01-3.0   | 49       | 32.89%  |
| 4.01-8.0   | 15       | 10.07%  |
| 3.01-4.0   | 14       | 9.4%    |
| 0.51-1.0   | 8        | 5.37%   |
| 8.01-16.0  | 4        | 2.68%   |
| 16.01-24.0 | 2        | 1.34%   |
| 24.01-32.0 | 1        | 0.67%   |
| 0.01-0.5   | 1        | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 40%     |
| 2      | 43       | 30.71%  |
| 3      | 22       | 15.71%  |
| 4      | 10       | 7.14%   |
| 5      | 5        | 3.57%   |
| 0      | 3        | 2.14%   |
| 32     | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 58.82%  |
| Yes       | 56       | 41.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 130      | 97.01%  |
| No        | 4        | 2.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 50.74%  |
| No        | 67       | 49.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 73.72%  |
| Yes       | 36       | 26.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 134      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bangkok              | 46       | 33.09%  |
| Chiang Mai           | 18       | 12.95%  |
| Phuket               | 5        | 3.6%    |
| Bang Lamung          | 5        | 3.6%    |
| Khon Kaen            | 4        | 2.88%   |
| Surin                | 3        | 2.16%   |
| Songkhla             | 3        | 2.16%   |
| Pattaya              | 3        | 2.16%   |
| Chon Buri            | 3        | 2.16%   |
| Phitsanulok          | 2        | 1.44%   |
| Pathum Thani         | 2        | 1.44%   |
| Nonthaburi           | 2        | 1.44%   |
| Nakhon Ratchasima    | 2        | 1.44%   |
| Nakhon Pathom        | 2        | 1.44%   |
| Lampang              | 2        | 1.44%   |
| Hua Hin              | 2        | 1.44%   |
| Bang Khae            | 2        | 1.44%   |
| Ban Du               | 2        | 1.44%   |
| Ban Bang Tanot       | 2        | 1.44%   |
| Yarang               | 1        | 0.72%   |
| Trat                 | 1        | 0.72%   |
| Thung Song           | 1        | 0.72%   |
| Suan Luang           | 1        | 0.72%   |
| Si Racha             | 1        | 0.72%   |
| San Sai              | 1        | 0.72%   |
| Samut Songkhram      | 1        | 0.72%   |
| Samphanthawong       | 1        | 0.72%   |
| Phetchabun           | 1        | 0.72%   |
| Phan                 | 1        | 0.72%   |
| Pak Kret             | 1        | 0.72%   |
| Nong Khaem           | 1        | 0.72%   |
| Nakhon Sawan         | 1        | 0.72%   |
| Mukdahan             | 1        | 0.72%   |
| Mueang Phuket        | 1        | 0.72%   |
| Loei                 | 1        | 0.72%   |
| Lat Krabang          | 1        | 0.72%   |
| Krabi                | 1        | 0.72%   |
| Khlong Luang         | 1        | 0.72%   |
| Don Mueang           | 1        | 0.72%   |
| Chok Chai            | 1        | 0.72%   |
| Chaloem Phra Kiat    | 1        | 0.72%   |
| Bang Bon             | 1        | 0.72%   |
| Bang Bai Mai         | 1        | 0.72%   |
| Ban Yang Sam Ton     | 1        | 0.72%   |
| Ban Phan Don         | 1        | 0.72%   |
| Ban Krabi Noi        | 1        | 0.72%   |
| Ayutthaya            | 1        | 0.72%   |
| Amphoe Aranyaprathet | 1        | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 53       | 87     | 22.46%  |
| Seagate                   | 50       | 76     | 21.19%  |
| Samsung Electronics       | 22       | 38     | 9.32%   |
| Kingston                  | 13       | 13     | 5.51%   |
| SanDisk                   | 10       | 12     | 4.24%   |
| Crucial                   | 8        | 8      | 3.39%   |
| Toshiba                   | 7        | 9      | 2.97%   |
| Hitachi                   | 7        | 7      | 2.97%   |
| HS-SSD-C100               | 6        | 10     | 2.54%   |
| Unknown                   | 5        | 10     | 2.12%   |
| Phison                    | 4        | 9      | 1.69%   |
| Intel                     | 4        | 4      | 1.69%   |
| Apacer                    | 4        | 4      | 1.69%   |
| Silicon Motion            | 3        | 4      | 1.27%   |
| KingSpec                  | 3        | 5      | 1.27%   |
| JMicron Technology        | 3        | 3      | 1.27%   |
| Hikvision                 | 3        | 3      | 1.27%   |
| GALAX                     | 3        | 3      | 1.27%   |
| SK hynix                  | 2        | 3      | 0.85%   |
| Plextor                   | 2        | 2      | 0.85%   |
| HGST                      | 2        | 5      | 0.85%   |
| External                  | 2        | 2      | 0.85%   |
| Corsair                   | 2        | 2      | 0.85%   |
| Colorful                  | 2        | 3      | 0.85%   |
| China                     | 2        | 2      | 0.85%   |
| Verbatim                  | 1        | 1      | 0.42%   |
| USB3.0                    | 1        | 1      | 0.42%   |
| Transcend                 | 1        | 1      | 0.42%   |
| TO Exter                  | 1        | 1      | 0.42%   |
| SPCC                      | 1        | 1      | 0.42%   |
| Realtek Semiconductor     | 1        | 1      | 0.42%   |
| Pioneer                   | 1        | 1      | 0.42%   |
| OCZ                       | 1        | 1      | 0.42%   |
| Micron/Crucial Technology | 1        | 1      | 0.42%   |
| Lexar                     | 1        | 1      | 0.42%   |
| Hewlett-Packard           | 1        | 3      | 0.42%   |
| DGM                       | 1        | 1      | 0.42%   |
| BR                        | 1        | 1      | 0.42%   |
| A-DATA Technology         | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 7        | 2.58%   |
| Seagate ST1000DM010-2EP102 1TB   | 6        | 2.21%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 1.85%   |
| Kingston SUV400S37120G 120GB SSD | 5        | 1.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 1.48%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 1.48%   |
| Seagate ST2000VX008-2E3164 2TB   | 4        | 1.48%   |
| Crucial CT500MX500SSD1 500GB     | 4        | 1.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 3        | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 3        | 1.11%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 3        | 1.11%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.11%   |
| Unknown SD/MMC/MS PRO 128GB      | 3        | 1.11%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.11%   |
| Seagate ST3500418AS 500GB        | 3        | 1.11%   |
| SanDisk SDSSDA120G 120GB         | 3        | 1.11%   |
| Samsung NVMe SSD Drive 250GB     | 3        | 1.11%   |
| Samsung HD103SJ 1TB              | 3        | 1.11%   |
| Phison NVMe SSD Drive 240GB      | 3        | 1.11%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.11%   |
| HS-SSD-C100 240G                 | 3        | 1.11%   |
| HS-SSD-C100 120G                 | 3        | 1.11%   |
| WDC WDS250G3X0C-00SJG0 250GB     | 2        | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 0.74%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 0.74%   |
| WDC WD2002FAEX-007BA0 2TB        | 2        | 0.74%   |
| WDC WD10EZEX-21WN4A0 1TB         | 2        | 0.74%   |
| WDC WD10EFRX-68FYTN0 1TB         | 2        | 0.74%   |
| Seagate ST500DM002-1BD14 500GB   | 2        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.74%   |
| Seagate ST3320620AS 320GB        | 2        | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.74%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.74%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 0.74%   |
| SanDisk NVMe SSD Drive 250GB     | 2        | 0.74%   |
| SanDisk NVMe SSD Drive 1TB       | 2        | 0.74%   |
| Samsung SSD 850 120GB            | 2        | 0.74%   |
| Samsung SSD 830 Series 128GB     | 2        | 0.74%   |
| Samsung HD753LJ 752GB            | 2        | 0.74%   |
| Samsung HD502IJ 500GB            | 2        | 0.74%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.74%   |
| Intel SSDSC2CT060A3 64GB         | 2        | 0.74%   |
| External USB3.0 1TB              | 2        | 0.74%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.37%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.37%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.37%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 0.37%   |
| WDC WDS120G1G0A-00SS50 120GB SSD | 1        | 0.37%   |
| WDC WD800JD-55MUA1 80GB          | 1        | 0.37%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.37%   |
| WDC WD5003ABYX-01WERA1 500GB     | 1        | 0.37%   |
| WDC WD5000LPCX-21VHAT0 500GB     | 1        | 0.37%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 0.37%   |
| WDC WD5000AAKX-221CA1 500GB      | 1        | 0.37%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1        | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.37%   |
| WDC WD40PURZ-85TTDY0 4TB         | 1        | 0.37%   |
| WDC WD40PURZ-85AKKY0 4TB         | 1        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 75     | 40.16%  |
| WDC                 | 43       | 65     | 35.25%  |
| Toshiba             | 7        | 9      | 5.74%   |
| Samsung Electronics | 7        | 12     | 5.74%   |
| Hitachi             | 7        | 7      | 5.74%   |
| Unknown             | 4        | 9      | 3.28%   |
| HGST                | 2        | 5      | 1.64%   |
| USB3.0              | 1        | 1      | 0.82%   |
| JMicron Technology  | 1        | 1      | 0.82%   |
| Hewlett-Packard     | 1        | 3      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 16.67%  |
| Kingston            | 11       | 11     | 14.1%   |
| Samsung Electronics | 9        | 12     | 11.54%  |
| Crucial             | 8        | 8      | 10.26%  |
| SanDisk             | 4        | 5      | 5.13%   |
| Intel               | 4        | 4      | 5.13%   |
| Apacer              | 4        | 4      | 5.13%   |
| KingSpec            | 3        | 5      | 3.85%   |
| Hikvision           | 3        | 3      | 3.85%   |
| GALAX               | 3        | 3      | 3.85%   |
| Plextor             | 2        | 2      | 2.56%   |
| China               | 2        | 2      | 2.56%   |
| Verbatim            | 1        | 1      | 1.28%   |
| TO Exter            | 1        | 1      | 1.28%   |
| SPCC                | 1        | 1      | 1.28%   |
| SK hynix            | 1        | 2      | 1.28%   |
| Pioneer             | 1        | 1      | 1.28%   |
| OCZ                 | 1        | 1      | 1.28%   |
| Lexar               | 1        | 1      | 1.28%   |
| JMicron Technology  | 1        | 1      | 1.28%   |
| DGM                 | 1        | 1      | 1.28%   |
| Corsair             | 1        | 1      | 1.28%   |
| Colorful            | 1        | 2      | 1.28%   |
| A-DATA Technology   | 1        | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 94       | 187    | 47.72%  |
| SSD     | 64       | 90     | 32.49%  |
| NVMe    | 28       | 48     | 14.21%  |
| Unknown | 11       | 15     | 5.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 125      | 275    | 75.76%  |
| NVMe | 26       | 46     | 15.76%  |
| SAS  | 14       | 19     | 8.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 146    | 53.63%  |
| 0.51-1.0   | 49       | 69     | 27.37%  |
| 1.01-2.0   | 23       | 27     | 12.85%  |
| 3.01-4.0   | 6        | 13     | 3.35%   |
| 2.01-3.0   | 2        | 6      | 1.12%   |
| 4.01-10.0  | 2        | 10     | 1.12%   |
| 10.01-20.0 | 1        | 6      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 40       | 28.57%  |
| 251-500        | 20       | 14.29%  |
| 501-1000       | 19       | 13.57%  |
| 1-20           | 14       | 10%     |
| 1001-2000      | 10       | 7.14%   |
| More than 3000 | 9        | 6.43%   |
| 2001-3000      | 9        | 6.43%   |
| 21-50          | 7        | 5%      |
| 51-100         | 7        | 5%      |
| Unknown        | 5        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 36.99%  |
| 21-50          | 24       | 16.44%  |
| 51-100         | 15       | 10.27%  |
| 101-250        | 14       | 9.59%   |
| 501-1000       | 11       | 7.53%   |
| 1001-2000      | 8        | 5.48%   |
| 251-500        | 7        | 4.79%   |
| More than 3000 | 6        | 4.11%   |
| Unknown        | 5        | 3.42%   |
| 2001-3000      | 2        | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2        | 2      | 16.67%  |
| Seagate ST500DM002-1BD14 500GB           | 2        | 2      | 16.67%  |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 8.33%   |
| Toshiba HDWL110 1TB                      | 1        | 1      | 8.33%   |
| Seagate ST9120822AS 120GB                | 1        | 1      | 8.33%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB                | 1        | 2      | 8.33%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 830 Series 128GB | 1        | 1      | 8.33%   |
| Samsung Electronics HD103SJ 1TB          | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 50%     |
| WDC                 | 3        | 3      | 25%     |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 54.55%  |
| WDC                 | 3        | 3      | 27.27%  |
| Toshiba             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 90.91%  |
| SSD  | 1        | 1      | 9.09%   |

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
| Detected | 105      | 242    | 70.47%  |
| Works    | 33       | 84     | 22.15%  |
| Malfunc  | 10       | 13     | 6.71%   |
| Failed   | 1        | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 92       | 52.57%  |
| AMD                         | 35       | 20%     |
| SanDisk                     | 9        | 5.14%   |
| ASMedia Technology          | 8        | 4.57%   |
| Samsung Electronics         | 7        | 4%      |
| Nvidia                      | 6        | 3.43%   |
| Phison Electronics          | 5        | 2.86%   |
| Silicon Motion              | 3        | 1.71%   |
| VIA Technologies            | 2        | 1.14%   |
| Kingston Technology Company | 2        | 1.14%   |
| SK hynix                    | 1        | 0.57%   |
| Realtek Semiconductor       | 1        | 0.57%   |
| Micron/Crucial Technology   | 1        | 0.57%   |
| LSI Logic / Symbios Logic   | 1        | 0.57%   |
| JMicron Technology          | 1        | 0.57%   |
| Broadcom / LSI              | 1        | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21       | 9.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 5.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 5.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 4.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 4.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 4.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 3.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.74%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 2.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.28%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 1.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 1.37%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.37%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.37%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.37%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 0.91%   |
| Nvidia MCP73 IDE Controller                                                             | 2        | 0.91%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.91%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.91%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.91%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.91%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.91%   |
| VIA VX900 Series Serial-ATA Controller                                                  | 1        | 0.46%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.46%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.46%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.46%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.46%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.46%   |
| Nvidia MCP73 SATA RAID Controller                                                       | 1        | 0.46%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.46%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.46%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.46%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.46%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.46%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.46%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 0.46%   |
| Intel 7 Series/C210 Series Chipset Family IDE-r Controller                              | 1        | 0.46%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 59.22%  |
| IDE  | 37       | 20.67%  |
| NVMe | 27       | 15.08%  |
| RAID | 7        | 3.91%   |
| SAS  | 1        | 0.56%   |
| SCSI | 1        | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 94       | 70.15%  |
| AMD          | 39       | 29.1%   |
| CentaurHauls | 1        | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 3.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.21%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 2.21%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.47%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.47%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.47%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.47%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.47%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.47%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.47%   |
| AMD Phenom II X6 1055T Processor            | 2        | 1.47%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.74%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.74%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.74%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 0.74%   |
| Intel Xeon CPU E5-2640 v2 @ 2.00GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 1        | 0.74%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.74%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 0.74%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.74%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.74%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.74%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.74%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.74%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.74%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.74%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.74%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.74%   |
| Intel Core i7-4790T CPU @ 2.70GHz           | 1        | 0.74%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1        | 0.74%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.74%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.74%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.74%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 0.74%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.74%   |
| Intel Core i5-8600 CPU @ 3.10GHz            | 1        | 0.74%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 0.74%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.74%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 0.74%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 0.74%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.74%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1        | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1        | 0.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 0.74%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 0.74%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.74%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.74%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 0.74%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.74%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 0.74%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 20.74%  |
| Intel Core i3           | 21       | 15.56%  |
| Intel Core i7           | 18       | 13.33%  |
| Intel Xeon              | 7        | 5.19%   |
| AMD Ryzen 5             | 7        | 5.19%   |
| AMD Ryzen 7             | 5        | 3.7%    |
| Intel Pentium           | 4        | 2.96%   |
| Intel Core 2 Quad       | 4        | 2.96%   |
| AMD Ryzen 3             | 4        | 2.96%   |
| AMD FX                  | 4        | 2.96%   |
| AMD Athlon II X2        | 4        | 2.96%   |
| Intel Pentium Dual-Core | 3        | 2.22%   |
| Intel Core i9           | 2        | 1.48%   |
| Intel Core 2 Duo        | 2        | 1.48%   |
| Intel Celeron           | 2        | 1.48%   |
| AMD Ryzen 9             | 2        | 1.48%   |
| AMD Phenom II X6        | 2        | 1.48%   |
| AMD Phenom II X4        | 2        | 1.48%   |
| AMD Athlon 64 X2        | 2        | 1.48%   |
| AMD A6                  | 2        | 1.48%   |
| AMD A4                  | 2        | 1.48%   |
| AMD A10                 | 2        | 1.48%   |
| Intel Pentium Dual      | 1        | 0.74%   |
| Intel Pentium 4         | 1        | 0.74%   |
| Intel Atom              | 1        | 0.74%   |
| CentaurHauls VIA Eden   | 1        | 0.74%   |
| AMD Ryzen 3 PRO         | 1        | 0.74%   |
| AMD Phenom II X3        | 1        | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 53       | 39.26%  |
| 2      | 43       | 31.85%  |
| 6      | 18       | 13.33%  |
| 8      | 13       | 9.63%   |
| 12     | 3        | 2.22%   |
| 1      | 3        | 2.22%   |
| 40     | 1        | 0.74%   |
| 3      | 1        | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 131      | 97.76%  |
| 2      | 3        | 2.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 74       | 54.81%  |
| 1      | 61       | 45.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 134      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 22.86%  |
| 0x306c3    | 14       | 10%     |
| 0x206a7    | 9        | 6.43%   |
| 0x506e3    | 8        | 5.71%   |
| 0x906ea    | 6        | 4.29%   |
| 0x906e9    | 6        | 4.29%   |
| 0x1067a    | 6        | 4.29%   |
| 0x306a9    | 4        | 2.86%   |
| 0x0800820d | 4        | 2.86%   |
| 0xa0655    | 3        | 2.14%   |
| 0x906ec    | 3        | 2.14%   |
| 0x20655    | 3        | 2.14%   |
| 0x010000c8 | 3        | 2.14%   |
| 0x08001138 | 2        | 1.43%   |
| 0x06003106 | 2        | 1.43%   |
| 0x06001119 | 2        | 1.43%   |
| 0x06000852 | 2        | 1.43%   |
| 0xf49      | 1        | 0.71%   |
| 0xa0653    | 1        | 0.71%   |
| 0x906ed    | 1        | 0.71%   |
| 0x906eb    | 1        | 0.71%   |
| 0x6fd      | 1        | 0.71%   |
| 0x6fb      | 1        | 0.71%   |
| 0x50654    | 1        | 0.71%   |
| 0x406f1    | 1        | 0.71%   |
| 0x406c3    | 1        | 0.71%   |
| 0x40651    | 1        | 0.71%   |
| 0x306e4    | 1        | 0.71%   |
| 0x30678    | 1        | 0.71%   |
| 0x206c2    | 1        | 0.71%   |
| 0x106e5    | 1        | 0.71%   |
| 0x106ca    | 1        | 0.71%   |
| 0x10677    | 1        | 0.71%   |
| 0x10676    | 1        | 0.71%   |
| 0x0a201204 | 1        | 0.71%   |
| 0x08701021 | 1        | 0.71%   |
| 0x08701013 | 1        | 0.71%   |
| 0x08600106 | 1        | 0.71%   |
| 0x08108109 | 1        | 0.71%   |
| 0x08101016 | 1        | 0.71%   |
| 0x0810100b | 1        | 0.71%   |
| 0x0800820b | 1        | 0.71%   |
| 0x06006704 | 1        | 0.71%   |
| 0x0600611a | 1        | 0.71%   |
| 0x06000822 | 1        | 0.71%   |
| 0x03000027 | 1        | 0.71%   |
| 0x010000db | 1        | 0.71%   |
| 0x010000b6 | 1        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 19       | 14.07%  |
| KabyLake    | 18       | 13.33%  |
| Skylake     | 11       | 8.15%   |
| SandyBridge | 11       | 8.15%   |
| Penryn      | 9        | 6.67%   |
| IvyBridge   | 9        | 6.67%   |
| K10         | 8        | 5.93%   |
| Zen 2       | 7        | 5.19%   |
| Zen+        | 6        | 4.44%   |
| Piledriver  | 5        | 3.7%    |
| CometLake   | 5        | 3.7%    |
| Zen         | 4        | 2.96%   |
| Westmere    | 4        | 2.96%   |
| Silvermont  | 3        | 2.22%   |
| Zen 3       | 2        | 1.48%   |
| Steamroller | 2        | 1.48%   |
| K8 Hammer   | 2        | 1.48%   |
| Excavator   | 2        | 1.48%   |
| Core        | 2        | 1.48%   |
| NetBurst    | 1        | 0.74%   |
| Nehalem     | 1        | 0.74%   |
| K10 Llano   | 1        | 0.74%   |
| Broadwell   | 1        | 0.74%   |
| Bonnell     | 1        | 0.74%   |
| Unknown     | 1        | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 61       | 42.07%  |
| Intel            | 45       | 31.03%  |
| AMD              | 38       | 26.21%  |
| VIA Technologies | 1        | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 5.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 4.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.31%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 3.31%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5        | 3.31%   |
| Intel HD Graphics 530                                                                    | 5        | 3.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 2.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.99%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.32%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.32%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2        | 1.32%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.32%   |
| Intel HD Graphics 630                                                                    | 2        | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2        | 1.32%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.32%   |
| AMD Renoir                                                                               | 2        | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.32%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 1.32%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.32%   |
| AMD Juniper PRO [Radeon HD 6750]                                                         | 2        | 1.32%   |
| AMD Fiji [Radeon R9 FURY / NANO Series]                                                  | 2        | 1.32%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 1.32%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.32%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.66%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.66%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.66%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.66%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.66%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.66%   |
| Nvidia GT200GL [Quadro FX 4800]                                                          | 1        | 0.66%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 1        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1        | 0.66%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.66%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1        | 0.66%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.66%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 1        | 0.66%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 0.66%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.66%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.66%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.66%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1        | 0.66%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 0.66%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1        | 0.66%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                       | 1        | 0.66%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 0.66%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 54       | 38.3%   |
| 1 x Intel            | 42       | 29.79%  |
| 1 x AMD              | 34       | 24.11%  |
| AMD + Nvidia         | 4        | 2.84%   |
| Intel + Nvidia       | 2        | 1.42%   |
| 3 x Nvidia           | 1        | 0.71%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.71%   |
| 2 x AMD              | 1        | 0.71%   |
| 1 x VIA              | 1        | 0.71%   |
| AMD + 2 x Nvidia     | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 74.64%  |
| Proprietary | 29       | 21.01%  |
| Unknown     | 6        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 44.06%  |
| 1.01-2.0   | 23       | 16.08%  |
| 0.51-1.0   | 14       | 9.79%   |
| 3.01-4.0   | 13       | 9.09%   |
| 0.01-0.5   | 12       | 8.39%   |
| 7.01-8.0   | 10       | 6.99%   |
| 5.01-6.0   | 4        | 2.8%    |
| 4.01-5.0   | 1        | 0.7%    |
| 2.01-3.0   | 1        | 0.7%    |
| 16.01-24.0 | 1        | 0.7%    |
| 8.01-16.0  | 1        | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 29       | 20.86%  |
| Acer                 | 22       | 15.83%  |
| Goldstar             | 21       | 15.11%  |
| Hewlett-Packard      | 10       | 7.19%   |
| Dell                 | 9        | 6.47%   |
| AOC                  | 9        | 6.47%   |
| BenQ                 | 6        | 4.32%   |
| LG Electronics       | 4        | 2.88%   |
| ViewSonic            | 3        | 2.16%   |
| Lenovo               | 3        | 2.16%   |
| Unknown (XXX)        | 2        | 1.44%   |
| Sharp                | 2        | 1.44%   |
| MStar                | 2        | 1.44%   |
| Ancor Communications | 2        | 1.44%   |
| Toshiba              | 1        | 0.72%   |
| Sony                 | 1        | 0.72%   |
| SGT                  | 1        | 0.72%   |
| MIG                  | 1        | 0.72%   |
| Microstep            | 1        | 0.72%   |
| ITE                  | 1        | 0.72%   |
| IOD                  | 1        | 0.72%   |
| HUYINIUDA            | 1        | 0.72%   |
| HPN                  | 1        | 0.72%   |
| Gateway              | 1        | 0.72%   |
| Fujitsu Siemens      | 1        | 0.72%   |
| Fujitsu              | 1        | 0.72%   |
| CHI                  | 1        | 0.72%   |
| ASUSTek Computer     | 1        | 0.72%   |
| Apple                | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                  | 2        | 1.35%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch    | 2        | 1.35%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 2        | 1.35%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 2        | 1.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 2        | 1.35%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch        | 2        | 1.35%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                         | 2        | 1.35%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                      | 2        | 1.35%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 1.35%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 1.35%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 1.35%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                        | 2        | 1.35%   |
| Acer X193W ACR000C 1440x900 410x260mm 19.1-inch                         | 2        | 1.35%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                        | 2        | 1.35%   |
| Acer S200HQL ACR0359 1600x900 434x236mm 19.4-inch                       | 2        | 1.35%   |
| Acer K242HQL ACR042E 1920x1080 521x293mm 23.5-inch                      | 2        | 1.35%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                  | 1        | 0.68%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1210x680mm 54.6-inch           | 1        | 0.68%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch              | 1        | 0.68%   |
| Toshiba TV TSB0114 1920x1080 882x498mm 39.9-inch                        | 1        | 0.68%   |
| Sony TV SNY9402 1920x1080                                               | 1        | 0.68%   |
| Sharp HDMI SHP113E 1920x1080 1330x748mm 60.1-inch                       | 1        | 0.68%   |
| Sharp HDMI SHP110F 1920x1080 700x390mm 31.5-inch                        | 1        | 0.68%   |
| SGT C FORCE SGT0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch     | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM044F 1440x900 408x255mm 18.9-inch     | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM03BA 1680x1050                        | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch    | 1        | 0.68%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics SA300/SA350 SAM0790 1920x1080 510x287mm 23.0-inch   | 1        | 0.68%   |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch       | 1        | 0.68%   |
| Samsung Electronics S27D590 SAM0BE9 1920x1080 598x336mm 27.0-inch       | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.68%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch       | 1        | 0.68%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.68%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch        | 1        | 0.68%   |
| Samsung Electronics LCD Monitor T27B350                                 | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SME1920                                 | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor S23B370 3840x1080                       | 1        | 0.68%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 0.68%   |
| MIG mllgo 240 MIG2380 1920x1080 520x310mm 23.8-inch                     | 1        | 0.68%   |
| Microstep LCD Monitor Optix G241VC 1920x1080                            | 1        | 0.68%   |
| LG Electronics LCD Monitor LG TV 3840x1080                              | 1        | 0.68%   |
| LG Electronics LCD Monitor LG TV 1280x720                               | 1        | 0.68%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch              | 1        | 0.68%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                    | 1        | 0.68%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                     | 1        | 0.68%   |
| ITE DP2VGA V226 ITE6516 1920x1080 600x340mm 27.2-inch                   | 1        | 0.68%   |
| IOD LCD-MF242X IOD1804 1920x1080 520x290mm 23.4-inch                    | 1        | 0.68%   |
| HUYINIUDA HUYINIUDA HUY1850 1366x768 410x220mm 18.3-inch                | 1        | 0.68%   |
| HPN LCD Monitor HP 24f 1920x1080                                        | 1        | 0.68%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch           | 1        | 0.68%   |
| Hewlett-Packard x20LED HWP290F 1600x900 443x249mm 20.0-inch             | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 48.55%  |
| 1600x900 (HD+)     | 12       | 8.7%    |
| 1366x768 (WXGA)    | 11       | 7.97%   |
| 3840x2160 (4K)     | 8        | 5.8%    |
| 1680x1050 (WSXGA+) | 8        | 5.8%    |
| 1440x900 (WXGA+)   | 8        | 5.8%    |
| 1280x1024 (SXGA)   | 5        | 3.62%   |
| Unknown            | 4        | 2.9%    |
| 2560x1440 (QHD)    | 3        | 2.17%   |
| 2560x1080          | 3        | 2.17%   |
| 3840x1080          | 2        | 1.45%   |
| 1360x768           | 2        | 1.45%   |
| 3440x1440          | 1        | 0.72%   |
| 2732x768           | 1        | 0.72%   |
| 2560x1600          | 1        | 0.72%   |
| 1600x1200          | 1        | 0.72%   |
| 1280x720 (HD)      | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 24       | 17.14%  |
| Unknown | 16       | 11.43%  |
| 24      | 14       | 10%     |
| 19      | 13       | 9.29%   |
| 27      | 12       | 8.57%   |
| 21      | 12       | 8.57%   |
| 18      | 12       | 8.57%   |
| 20      | 11       | 7.86%   |
| 22      | 6        | 4.29%   |
| 34      | 4        | 2.86%   |
| 15      | 3        | 2.14%   |
| 52      | 2        | 1.43%   |
| 17      | 2        | 1.43%   |
| 84      | 1        | 0.71%   |
| 72      | 1        | 0.71%   |
| 60      | 1        | 0.71%   |
| 54      | 1        | 0.71%   |
| 47      | 1        | 0.71%   |
| 39      | 1        | 0.71%   |
| 31      | 1        | 0.71%   |
| 29      | 1        | 0.71%   |
| 16      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 52       | 38.52%  |
| 501-600     | 46       | 34.07%  |
| Unknown     | 16       | 11.85%  |
| 301-350     | 6        | 4.44%   |
| 1001-1500   | 5        | 3.7%    |
| 701-800     | 4        | 2.96%   |
| 601-700     | 2        | 1.48%   |
| 351-400     | 2        | 1.48%   |
| 801-900     | 1        | 0.74%   |
| 1501-2000   | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 89       | 67.42%  |
| 16/10   | 18       | 13.64%  |
| Unknown | 15       | 11.36%  |
| 5/4     | 5        | 3.79%   |
| 21/9    | 4        | 3.03%   |
| 4/3     | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 49       | 35.77%  |
| 151-200        | 28       | 20.44%  |
| Unknown        | 16       | 11.68%  |
| 301-350        | 12       | 8.76%   |
| 141-150        | 11       | 8.03%   |
| 351-500        | 6        | 4.38%   |
| More than 1000 | 5        | 3.65%   |
| 251-300        | 3        | 2.19%   |
| 101-110        | 3        | 2.19%   |
| 501-1000       | 2        | 1.46%   |
| 131-140        | 1        | 0.73%   |
| 121-130        | 1        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 64.06%  |
| 101-120 | 18       | 14.06%  |
| Unknown | 16       | 12.5%   |
| 1-50    | 6        | 4.69%   |
| 161-240 | 4        | 3.13%   |
| 121-160 | 2        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 78.42%  |
| 2     | 18       | 12.95%  |
| 0     | 9        | 6.47%   |
| 3     | 3        | 2.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 88       | 46.07%  |
| Intel                           | 44       | 23.04%  |
| Qualcomm Atheros                | 14       | 7.33%   |
| Ralink Technology               | 10       | 5.24%   |
| D-Link                          | 6        | 3.14%   |
| Nvidia                          | 5        | 2.62%   |
| Broadcom                        | 4        | 2.09%   |
| TP-Link                         | 3        | 1.57%   |
| D-Link System                   | 3        | 1.57%   |
| Ralink                          | 2        | 1.05%   |
| Xiaomi                          | 1        | 0.52%   |
| VIA Technologies                | 1        | 0.52%   |
| Samsung Electronics             | 1        | 0.52%   |
| Qualcomm Atheros Communications | 1        | 0.52%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.52%   |
| Mercucys                        | 1        | 0.52%   |
| MediaTek                        | 1        | 0.52%   |
| Huawei Technologies             | 1        | 0.52%   |
| Edimax Technology               | 1        | 0.52%   |
| BUFFALO                         | 1        | 0.52%   |
| ASUSTek Computer                | 1        | 0.52%   |
| Aquantia                        | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 74       | 34.58%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6        | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 6        | 2.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5        | 2.34%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 2.34%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 2.34%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 2.34%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 4        | 1.87%   |
| Intel Ethernet Connection I217-V                                       | 4        | 1.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 1.87%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.4%    |
| Intel Ethernet Connection (5) I219-LM                                  | 3        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 1.4%    |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]          | 3        | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 0.93%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.93%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 2        | 0.93%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 2        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.93%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.93%   |
| Intel Wireless-AC 9260                                                 | 2        | 0.93%   |
| Intel Ethernet Connection (12) I219-V                                  | 2        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.93%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.93%   |
| Xiaomi 100Mbps Network Card Adapter                                    | 1        | 0.47%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                      | 1        | 0.47%   |
| TP-Link TL-WN722N v2                                                   | 1        | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.47%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.47%   |
| Realtek 802.11ac NIC                                                   | 1        | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 0.47%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                   | 1        | 0.47%   |
| Ralink RT2561/RT61 rev B 802.11g                                       | 1        | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 0.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.47%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 0.47%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]    | 1        | 0.47%   |
| OnePlus (Shenzhen) OnePlus                                             | 1        | 0.47%   |
| Mercucys 802.11n NIC                                                   | 1        | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 0.47%   |
| Intel Wireless 7260                                                    | 1        | 0.47%   |
| Intel Wireless 3165                                                    | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 25.71%  |
| Intel                           | 12       | 17.14%  |
| Qualcomm Atheros                | 11       | 15.71%  |
| Ralink Technology               | 10       | 14.29%  |
| D-Link                          | 6        | 8.57%   |
| TP-Link                         | 3        | 4.29%   |
| Ralink                          | 2        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 1.43%   |
| Mercucys                        | 1        | 1.43%   |
| MediaTek                        | 1        | 1.43%   |
| Edimax Technology               | 1        | 1.43%   |
| D-Link System                   | 1        | 1.43%   |
| BUFFALO                         | 1        | 1.43%   |
| Broadcom                        | 1        | 1.43%   |
| ASUSTek Computer                | 1        | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 6        | 8.57%   |
| Ralink MT7601U Wireless Adapter                                              | 5        | 7.14%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                              | 4        | 5.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 3        | 4.29%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                | 3        | 4.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                           | 2        | 2.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                              | 2        | 2.86%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 2        | 2.86%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                            | 2        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 2        | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)               | 2        | 2.86%   |
| Intel Wireless-AC 9260                                                       | 2        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                             | 2        | 2.86%   |
| TP-Link TL-WN722N v2                                                         | 1        | 1.43%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                   | 1        | 1.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                   | 1        | 1.43%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                          | 1        | 1.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                                   | 1        | 1.43%   |
| Realtek 802.11ac NIC                                                         | 1        | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                        | 1        | 1.43%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                         | 1        | 1.43%   |
| Ralink RT2561/RT61 rev B 802.11g                                             | 1        | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 1        | 1.43%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 1        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 1        | 1.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                             | 1        | 1.43%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]       | 1        | 1.43%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]          | 1        | 1.43%   |
| Mercucys 802.11n NIC                                                         | 1        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                | 1        | 1.43%   |
| Intel Wireless 7260                                                          | 1        | 1.43%   |
| Intel Wireless 3165                                                          | 1        | 1.43%   |
| Intel Wireless 3160                                                          | 1        | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                       | 1        | 1.43%   |
| Intel Wi-Fi 6 AX200                                                          | 1        | 1.43%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]               | 1        | 1.43%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]         | 1        | 1.43%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 1.43%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                               | 1        | 1.43%   |
| D-Link 802.11 n WLAN                                                         | 1        | 1.43%   |
| BUFFALO Sony UWA-BR100 802.11abgn Wireless Adapter [Atheros AR7010+AR9280]   | 1        | 1.43%   |
| Broadcom BCM43228 802.11a/b/g/n                                              | 1        | 1.43%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]              | 1        | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 82       | 58.99%  |
| Intel                         | 38       | 27.34%  |
| Nvidia                        | 5        | 3.6%    |
| Qualcomm Atheros              | 4        | 2.88%   |
| Broadcom                      | 3        | 2.16%   |
| D-Link System                 | 2        | 1.44%   |
| Xiaomi                        | 1        | 0.72%   |
| VIA Technologies              | 1        | 0.72%   |
| Samsung Electronics           | 1        | 0.72%   |
| OnePlus Technology (Shenzhen) | 1        | 0.72%   |
| Aquantia                      | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 74       | 51.75%  |
| Intel Ethernet Connection (2) I219-V                              | 6        | 4.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.5%    |
| Intel I211 Gigabit Network Connection                             | 5        | 3.5%    |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.5%    |
| Intel Ethernet Connection I217-V                                  | 4        | 2.8%    |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.8%    |
| Nvidia MCP61 Ethernet                                             | 3        | 2.1%    |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.4%    |
| Nvidia MCP73 Ethernet                                             | 2        | 1.4%    |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.4%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.4%    |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.7%    |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.7%    |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 0.7%    |
| Intel I210 Gigabit Unprogrammed                                   | 1        | 0.7%    |
| Intel Ethernet Connection I218-V                                  | 1        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.7%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.7%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.7%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.7%    |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 65%     |
| WiFi     | 69       | 34.5%   |
| Modem    | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 61.31%  |
| WiFi     | 53       | 38.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 64.44%  |
| 2     | 41       | 30.37%  |
| 0     | 4        | 2.96%   |
| 4     | 2        | 1.48%   |
| 3     | 1        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 109      | 77.3%   |
| Yes  | 32       | 22.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 19       | 51.35%  |
| Intel                           | 11       | 29.73%  |
| Qualcomm Atheros Communications | 2        | 5.41%   |
| ASUSTek Computer                | 2        | 5.41%   |
| MediaTek                        | 1        | 2.7%    |
| Lite-On Technology              | 1        | 2.7%    |
| Apple                           | 1        | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 51.35%  |
| Intel Bluetooth wireless interface                  | 3        | 8.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 8.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 5.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.7%    |
| MediaTek Wireless_Device                            | 1        | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 2.7%    |
| Intel AX200 Bluetooth                               | 1        | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.7%    |
| ASUS Bluetooth Device                               | 1        | 2.7%    |
| Apple Bluetooth HCI                                 | 1        | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 40.97%  |
| Nvidia                      | 57       | 25.11%  |
| AMD                         | 51       | 22.47%  |
| C-Media Electronics         | 9        | 3.96%   |
| JMTek                       | 3        | 1.32%   |
| SAVITECH                    | 2        | 0.88%   |
| Elan Microelectronics       | 2        | 0.88%   |
| VIA Technologies            | 1        | 0.44%   |
| Texas Instruments           | 1        | 0.44%   |
| Razer USA                   | 1        | 0.44%   |
| Nordic Semiconductor ASA    | 1        | 0.44%   |
| Kingston Technology         | 1        | 0.44%   |
| Generalplus Technology      | 1        | 0.44%   |
| ESS Technology              | 1        | 0.44%   |
| Earth Computer Technologies | 1        | 0.44%   |
| Creative Labs               | 1        | 0.44%   |
| Blue Microphones            | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14       | 5.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13       | 4.78%   |
| Intel 200 Series PCH HD Audio                                                                     | 12       | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9        | 3.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 3.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.31%   |
| Nvidia High Definition Audio Controller                                                           | 8        | 2.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 2.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 2.57%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6        | 2.21%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6        | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6        | 2.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 2.21%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5        | 1.84%   |
| AMD FCH Azalia Controller                                                                         | 5        | 1.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5        | 1.84%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4        | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.47%   |
| C-Media Electronics USB Audio Device                                                              | 4        | 1.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 1.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                                                     | 3        | 1.1%    |
| JMTek USB PnP Audio Device                                                                        | 3        | 1.1%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3        | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.1%    |
| AMD Navi 10 HDMI Audio                                                                            | 3        | 1.1%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3        | 1.1%    |
| SAVITECH SA9023 audio controller                                                                  | 2        | 0.74%   |
| Nvidia MCP73 High Definition Audio                                                                | 2        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.74%   |
| Elan Microelectronics USB Audio                                                                   | 2        | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 0.74%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 0.74%   |
| AMD Fiji HDMI/DP Audio [Radeon R9 Nano / FURY/FURY X]                                             | 2        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2        | 0.74%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.37%   |
| VIA Technologies High Definition Audio Controller                                                 | 1        | 0.37%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 0.37%   |
| Razer USA Razer Kraken X USB                                                                      | 1        | 0.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 0.37%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.37%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.37%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 0.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 0.37%   |
| Nordic Semiconductor ASA Smart Control                                                            | 1        | 0.37%   |
| Kingston Technology HyperX Cloud II Wireless                                                      | 1        | 0.37%   |
| Intel USB PnP Sound Device                                                                        | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 44.23%  |
| Unknown             | 9        | 17.31%  |
| SK hynix            | 7        | 13.46%  |
| Corsair             | 5        | 9.62%   |
| Samsung Electronics | 3        | 5.77%   |
| G.Skill             | 2        | 3.85%   |
| Unknown (0x02BA)    | 1        | 1.92%   |
| Transcend           | 1        | 1.92%   |
| A-DATA Technology   | 1        | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 5        | 8.77%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 5.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 3.51%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 2        | 3.51%   |
| Samsung RAM M378B5673FH0-CH9 2048MB DIMM DDR3 1600MT/s  | 2        | 3.51%   |
| Kingston RAM KP223C-ELD 2GB DIMM 1600MT/s               | 2        | 3.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 3.51%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s     | 2        | 3.51%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 1.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 1.75%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s | 1        | 1.75%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s        | 1        | 1.75%   |
| SK hynix RAM Module 1024MB FB-DIMM DDR2 800MT/s         | 1        | 1.75%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s   | 1        | 1.75%   |
| SK hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s    | 1        | 1.75%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 1        | 1.75%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB RIMM DDR4 2133MT/s   | 1        | 1.75%   |
| SK hynix RAM HMA84GL7AMR4N-TF 32GB RIMM DDR4 2133MT/s   | 1        | 1.75%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 1        | 1.75%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s     | 1        | 1.75%   |
| Kingston RAM Module 2GB DIMM DDR 533MT/s                | 1        | 1.75%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s          | 1        | 1.75%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s     | 1        | 1.75%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 1        | 1.75%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s  | 1        | 1.75%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s     | 1        | 1.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s       | 1        | 1.75%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 1        | 1.75%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s     | 1        | 1.75%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 1        | 1.75%   |
| Kingston RAM 99U5474-026.A 4GB DIMM DDR3 1333MT/s       | 1        | 1.75%   |
| Kingston RAM 99U5471-050.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.75%   |
| Kingston RAM 99U5403-002.A00G 2048MB DIMM DDR3 1333MT/s | 1        | 1.75%   |
| Kingston RAM 9905678-041.A00G 4GB DIMM DDR4 2400MT/s    | 1        | 1.75%   |
| Kingston RAM 9905428-123.A00LF 8GB SODIMM DDR3 1600MT/s | 1        | 1.75%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s     | 1        | 1.75%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s  | 1        | 1.75%   |
| Corsair RAM CMU16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s   | 1        | 1.75%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s  | 1        | 1.75%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s   | 1        | 1.75%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s   | 1        | 1.75%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 22       | 46.81%  |
| DDR3    | 13       | 27.66%  |
| Unknown | 4        | 8.51%   |
| SDRAM   | 3        | 6.38%   |
| DDR2    | 2        | 4.26%   |
| DDR     | 2        | 4.26%   |
| LPDDR4  | 1        | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 40       | 90.91%  |
| SODIMM  | 2        | 4.55%   |
| RIMM    | 1        | 2.27%   |
| FB-DIMM | 1        | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 39.13%  |
| 4096  | 14       | 30.43%  |
| 2048  | 7        | 15.22%  |
| 16384 | 4        | 8.7%    |
| 1024  | 2        | 4.35%   |
| 32768 | 1        | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 11       | 21.57%  |
| 1600    | 8        | 15.69%  |
| 3600    | 6        | 11.76%  |
| 3200    | 4        | 7.84%   |
| 2400    | 3        | 5.88%   |
| 3466    | 2        | 3.92%   |
| 3151    | 2        | 3.92%   |
| 2667    | 2        | 3.92%   |
| 2133    | 2        | 3.92%   |
| 1866    | 2        | 3.92%   |
| 3333    | 1        | 1.96%   |
| 3000    | 1        | 1.96%   |
| 2933    | 1        | 1.96%   |
| 2800    | 1        | 1.96%   |
| 1867    | 1        | 1.96%   |
| 800     | 1        | 1.96%   |
| 667     | 1        | 1.96%   |
| 533     | 1        | 1.96%   |
| Unknown | 1        | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 28.57%  |
| Brother Industries | 2        | 28.57%  |
| STMicroelectronics | 1        | 14.29%  |
| Pantum             | 1        | 14.29%  |
| Canon              | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| STMicroelectronics USB Printer P | 1        | 14.29%  |
| Seiko Epson LQ-310               | 1        | 14.29%  |
| Seiko Epson L220 Series          | 1        | 14.29%  |
| Pantum P2500W series             | 1        | 14.29%  |
| Canon E4200 series               | 1        | 14.29%  |
| Brother DCP-T510W                | 1        | 14.29%  |
| Brother DCP-L3551CDW             | 1        | 14.29%  |

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
| Logitech                      | 7        | 36.84%  |
| Microdia                      | 4        | 21.05%  |
| Aveo Technology               | 3        | 15.79%  |
| Suyin                         | 1        | 5.26%   |
| Sunplus Innovation Technology | 1        | 5.26%   |
| Realtek Semiconductor         | 1        | 5.26%   |
| Generalplus Technology        | 1        | 5.26%   |
| Apple                         | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microdia Camera                      | 3        | 15.79%  |
| Logitech Webcam C310                 | 2        | 10.53%  |
| Aveo USB2.0 Camera                   | 2        | 10.53%  |
| Suyin HP Integrated Webcam           | 1        | 5.26%   |
| Sunplus Webcam                       | 1        | 5.26%   |
| Realtek USB Boot                     | 1        | 5.26%   |
| Microdia Integrated Camera           | 1        | 5.26%   |
| Logitech Webcam C600                 | 1        | 5.26%   |
| Logitech Webcam C270                 | 1        | 5.26%   |
| Logitech Mic (Notebooks Pro)         | 1        | 5.26%   |
| Logitech HD Webcam C525              | 1        | 5.26%   |
| Logitech HD Webcam C510              | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM           | 1        | 5.26%   |
| Aveo UVC camera (Bresser microscope) | 1        | 5.26%   |
| Apple iPad 2 (3G; 64GB)              | 1        | 5.26%   |

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
| 0     | 118      | 88.06%  |
| 1     | 13       | 9.7%    |
| 7     | 1        | 0.75%   |
| 5     | 1        | 0.75%   |
| 2     | 1        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 33.33%  |
| Sound                    | 5        | 23.81%  |
| Net/wireless             | 4        | 19.05%  |
| Communication controller | 2        | 9.52%   |
| Unassigned class         | 1        | 4.76%   |
| Network                  | 1        | 4.76%   |
| Net/ethernet             | 1        | 4.76%   |

