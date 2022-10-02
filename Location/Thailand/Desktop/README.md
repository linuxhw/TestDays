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

Total: 210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 27       | 18.49%  |
| Ubuntu 18.04                 | 23       | 15.75%  |
| OpenMandriva 4.2             | 7        | 4.79%   |
| Manjaro                      | 6        | 4.11%   |
| OpenMandriva 4.3             | 5        | 3.42%   |
| Arch Rolling                 | 5        | 3.42%   |
| Ubuntu 22.04                 | 4        | 2.74%   |
| Xubuntu 20.04                | 3        | 2.05%   |
| KDE neon 20.04               | 3        | 2.05%   |
| Zorin 15                     | 2        | 1.37%   |
| Xubuntu 18.04                | 2        | 1.37%   |
| Ubuntu 21.10                 | 2        | 1.37%   |
| Ubuntu 19.10                 | 2        | 1.37%   |
| Reborn OS                    | 2        | 1.37%   |
| Pop!_OS 22.04                | 2        | 1.37%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.37%   |
| Linux Mint 21                | 2        | 1.37%   |
| Linux Mint 20                | 2        | 1.37%   |
| Fedora 36                    | 2        | 1.37%   |
| Endless 3.9.5                | 2        | 1.37%   |
| Endless 3.7.6                | 2        | 1.37%   |
| Arch                         | 2        | 1.37%   |
| Zorin 16                     | 1        | 0.68%   |
| Xubuntu 21.10                | 1        | 0.68%   |
| UbuntuDDE 20.04              | 1        | 0.68%   |
| Ubuntu MATE 18.04            | 1        | 0.68%   |
| Ubuntu Budgie 20.10          | 1        | 0.68%   |
| Ubuntu 21.04                 | 1        | 0.68%   |
| Ubuntu 19.04                 | 1        | 0.68%   |
| Ubuntu 16.04                 | 1        | 0.68%   |
| Solus 4.3                    | 1        | 0.68%   |
| Pop!_OS 21.10                | 1        | 0.68%   |
| Pop!_OS 21.04                | 1        | 0.68%   |
| Pop!_OS 20.10                | 1        | 0.68%   |
| Pop!_OS 20.04                | 1        | 0.68%   |
| OpenMandriva 4.50            | 1        | 0.68%   |
| Manjaro 18.1.3               | 1        | 0.68%   |
| Linux Mint 20.3              | 1        | 0.68%   |
| Linux Mint 20.2              | 1        | 0.68%   |
| Linux Mint 19.3              | 1        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 59       | 42.14%  |
| OpenMandriva  | 13       | 9.29%   |
| Linux Mint    | 9        | 6.43%   |
| Arch          | 7        | 5%      |
| Xubuntu       | 6        | 4.29%   |
| Pop!_OS       | 6        | 4.29%   |
| Manjaro       | 6        | 4.29%   |
| Endless       | 6        | 4.29%   |
| Fedora        | 5        | 3.57%   |
| Zorin         | 3        | 2.14%   |
| KDE neon      | 3        | 2.14%   |
| Reborn OS     | 2        | 1.43%   |
| openSUSE      | 2        | 1.43%   |
| Elementary    | 2        | 1.43%   |
| Clear Linux   | 2        | 1.43%   |
| UbuntuDDE     | 1        | 0.71%   |
| Ubuntu MATE   | 1        | 0.71%   |
| Ubuntu Budgie | 1        | 0.71%   |
| Solus         | 1        | 0.71%   |
| Kubuntu       | 1        | 0.71%   |
| Debian        | 1        | 0.71%   |
| CentOS        | 1        | 0.71%   |
| BlackPanther  | 1        | 0.71%   |
| ArcoLinux     | 1        | 0.71%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 4.58%   |
| 5.4.0-48-generic         | 4        | 2.61%   |
| 5.16.7-desktop-1omv4003  | 4        | 2.61%   |
| 5.15.0-46-generic        | 4        | 2.61%   |
| 5.8.0-14-generic         | 3        | 1.96%   |
| 5.4.0-42-generic         | 3        | 1.96%   |
| 5.8.0-63-generic         | 2        | 1.31%   |
| 5.4.0-77-generic         | 2        | 1.31%   |
| 5.4.0-66-generic         | 2        | 1.31%   |
| 5.4.0-65-generic         | 2        | 1.31%   |
| 5.4.0-59-generic         | 2        | 1.31%   |
| 5.4.0-45-generic         | 2        | 1.31%   |
| 5.4.0-37-generic         | 2        | 1.31%   |
| 5.3.0-23-generic         | 2        | 1.31%   |
| 5.17.5-76051705-generic  | 2        | 1.31%   |
| 5.17.3-arch1-1           | 2        | 1.31%   |
| 5.15.0-43-generic        | 2        | 1.31%   |
| 5.13.0-51-generic        | 2        | 1.31%   |
| 5.13.0-22-generic        | 2        | 1.31%   |
| 5.11.0-41-generic        | 2        | 1.31%   |
| 5.11.0-37-generic        | 2        | 1.31%   |
| 5.0.0-37-generic         | 2        | 1.31%   |
| 5.0.0-23-generic         | 2        | 1.31%   |
| 5.9.16-1-MANJARO         | 1        | 0.65%   |
| 5.8.1-arch1-1            | 1        | 0.65%   |
| 5.8.0-7630-generic       | 1        | 0.65%   |
| 5.8.0-59-generic         | 1        | 0.65%   |
| 5.8.0-48-generic         | 1        | 0.65%   |
| 5.8.0-43-generic         | 1        | 0.65%   |
| 5.8.0-41-generic         | 1        | 0.65%   |
| 5.8.0-2-amd64            | 1        | 0.65%   |
| 5.8.0-1-default          | 1        | 0.65%   |
| 5.7.13-975.native        | 1        | 0.65%   |
| 5.6.6-300.fc32.x86_64    | 1        | 0.65%   |
| 5.6.2-arch1-2            | 1        | 0.65%   |
| 5.6.16-300.fc32.x86_64   | 1        | 0.65%   |
| 5.6.14-desktop-2bP       | 1        | 0.65%   |
| 5.5.7-arch1-1            | 1        | 0.65%   |
| 5.5.7-1-MANJARO          | 1        | 0.65%   |
| 5.4.82-1-lts             | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 21.33%  |
| 5.8.0   | 12       | 8%      |
| 5.13.0  | 11       | 7.33%   |
| 4.15.0  | 11       | 7.33%   |
| 5.3.0   | 8        | 5.33%   |
| 5.15.0  | 7        | 4.67%   |
| 5.10.14 | 7        | 4.67%   |
| 5.0.0   | 7        | 4.67%   |
| 5.11.0  | 6        | 4%      |
| 4.18.0  | 5        | 3.33%   |
| 5.16.7  | 4        | 2.67%   |
| 5.17.5  | 3        | 2%      |
| 5.5.7   | 2        | 1.33%   |
| 5.17.3  | 2        | 1.33%   |
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

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 22.82%  |
| 5.13    | 14       | 9.4%    |
| 5.8     | 13       | 8.72%   |
| 4.15    | 11       | 7.38%   |
| 5.16    | 10       | 6.71%   |
| 5.15    | 10       | 6.71%   |
| 5.3     | 9        | 6.04%   |
| 5.17    | 8        | 5.37%   |
| 5.10    | 8        | 5.37%   |
| 5.0     | 8        | 5.37%   |
| 5.11    | 6        | 4.03%   |
| 4.18    | 5        | 3.36%   |
| 5.6     | 3        | 2.01%   |
| 5.5     | 2        | 1.34%   |
| 5.14    | 2        | 1.34%   |
| 5.9     | 1        | 0.67%   |
| 5.7     | 1        | 0.67%   |
| 5.18    | 1        | 0.67%   |
| 5.12    | 1        | 0.67%   |
| 5.1     | 1        | 0.67%   |
| 4.4     | 1        | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 134      | 99.26%  |
| i686   | 1        | 0.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 73       | 51.77%  |
| KDE5       | 19       | 13.48%  |
| Unknown    | 18       | 12.77%  |
| XFCE       | 9        | 6.38%   |
| X-Cinnamon | 9        | 6.38%   |
| MATE       | 3        | 2.13%   |
| KDE        | 3        | 2.13%   |
| Pantheon   | 2        | 1.42%   |
| Deepin     | 2        | 1.42%   |
| Budgie     | 2        | 1.42%   |
| Cinnamon   | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 112      | 81.16%  |
| Wayland | 12       | 8.7%    |
| Unknown | 12       | 8.7%    |
| Tty     | 2        | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 88       | 63.31%  |
| SDDM    | 17       | 12.23%  |
| GDM3    | 12       | 8.63%   |
| GDM     | 11       | 7.91%   |
| LightDM | 8        | 5.76%   |
| TDM     | 3        | 2.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 94       | 67.63%  |
| Unknown | 16       | 11.51%  |
| th_TH   | 10       | 7.19%   |
| en_GB   | 8        | 5.76%   |
| de_DE   | 5        | 3.6%    |
| C       | 3        | 2.16%   |
| sv_SE   | 1        | 0.72%   |
| it_IT   | 1        | 0.72%   |
| de_CH   | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 88       | 62.86%  |
| EFI  | 52       | 37.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 114      | 82.61%  |
| Overlay | 12       | 8.7%    |
| Btrfs   | 4        | 2.9%    |
| Unknown | 4        | 2.9%    |
| Xfs     | 3        | 2.17%   |
| Zfs     | 1        | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 98       | 71.53%  |
| GPT     | 30       | 21.9%   |
| MBR     | 9        | 6.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 80.88%  |
| Yes       | 26       | 19.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 57.25%  |
| Yes       | 59       | 42.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 29       | 21.48%  |
| ASUSTek Computer    | 28       | 20.74%  |
| ASRock              | 21       | 15.56%  |
| MSI                 | 15       | 11.11%  |
| Dell                | 10       | 7.41%   |
| Hewlett-Packard     | 9        | 6.67%   |
| Acer                | 6        | 4.44%   |
| Unknown             | 3        | 2.22%   |
| Intel               | 2        | 1.48%   |
| Huanan              | 2        | 1.48%   |
| VIA Technologies    | 1        | 0.74%   |
| SHARKBAY            | 1        | 0.74%   |
| Pegatron            | 1        | 0.74%   |
| Packard Bell        | 1        | 0.74%   |
| OEM                 | 1        | 0.74%   |
| MiTAC               | 1        | 0.74%   |
| Fujitsu             | 1        | 0.74%   |
| Biostar             | 1        | 0.74%   |
| Apple               | 1        | 0.74%   |
| AFOX                | 1        | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 4        | 2.96%   |
| Unknown                    | 4        | 2.96%   |
| Dell OptiPlex 7010         | 3        | 2.22%   |
| ASUS P8H61-M LE            | 3        | 2.22%   |
| HP EliteDesk 800 G1 SFF PC | 2        | 1.48%   |
| Gigabyte Z97X-UD3H-BK      | 2        | 1.48%   |
| Gigabyte B250-HD3          | 2        | 1.48%   |
| ASUS H110M-E/M.2           | 2        | 1.48%   |
| ASRock B450 Steel Legend   | 2        | 1.48%   |
| Acer Aspire TC-885         | 2        | 1.48%   |
| VIA VX900                  | 1        | 0.74%   |
| Pegatron CQ3476L           | 1        | 0.74%   |
| Packard Bell IMEDIA S3720  | 1        | 0.74%   |
| OEM Intel H81              | 1        | 0.74%   |
| MSI Pro 3130 Microtower PC | 1        | 0.74%   |
| MSI Pro 2000/2080          | 1        | 0.74%   |
| MSI p6772l                 | 1        | 0.74%   |
| MSI MS-7C52                | 1        | 0.74%   |
| MSI MS-7C35                | 1        | 0.74%   |
| MSI MS-7B89                | 1        | 0.74%   |
| MSI MS-7B85                | 1        | 0.74%   |
| MSI MS-7A63                | 1        | 0.74%   |
| MSI MS-7A38                | 1        | 0.74%   |
| MSI MS-7A32                | 1        | 0.74%   |
| MSI MS-7A15                | 1        | 0.74%   |
| MSI MS-7978                | 1        | 0.74%   |
| MSI MS-7914                | 1        | 0.74%   |
| MSI MS-7641                | 1        | 0.74%   |
| MSI KY779AA-AKL CQ3070L    | 1        | 0.74%   |
| MiTAC PD14RI               | 1        | 0.74%   |
| Intel H61M S1              | 1        | 0.74%   |
| Intel D54250WYK H13922-305 | 1        | 0.74%   |
| Huanan X79 V6.11           | 1        | 0.74%   |
| Huanan X79 249PC V2.2      | 1        | 0.74%   |
| HP Z800 Workstation        | 1        | 0.74%   |
| HP ProDesk 600 G3 SFF      | 1        | 0.74%   |
| HP ProDesk 600 G1 SFF      | 1        | 0.74%   |
| HP ProDesk 400 G3 SFF      | 1        | 0.74%   |
| HP Compaq 6200 Pro SFF PC  | 1        | 0.74%   |
| HP Compaq 6000 Pro SFF PC  | 1        | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 7        | 5.19%   |
| Acer Aspire            | 5        | 3.7%    |
| ASUS PRIME             | 4        | 2.96%   |
| ASUS All               | 4        | 2.96%   |
| Unknown                | 4        | 2.96%   |
| HP ProDesk             | 3        | 2.22%   |
| ASUS P8H61-M           | 3        | 2.22%   |
| ASRock B450            | 3        | 2.22%   |
| MSI Pro                | 2        | 1.48%   |
| Huanan X79             | 2        | 1.48%   |
| HP EliteDesk           | 2        | 1.48%   |
| HP Compaq              | 2        | 1.48%   |
| Gigabyte Z97X-UD3H-BK  | 2        | 1.48%   |
| Gigabyte Z390          | 2        | 1.48%   |
| Gigabyte GA-78LMT-USB3 | 2        | 1.48%   |
| Gigabyte B250-HD3      | 2        | 1.48%   |
| Dell Precision         | 2        | 1.48%   |
| ASUS ROG               | 2        | 1.48%   |
| ASUS M5A78L-M          | 2        | 1.48%   |
| ASUS H110M-E           | 2        | 1.48%   |
| ASRock Z77             | 2        | 1.48%   |
| ASRock B450M           | 2        | 1.48%   |
| VIA VX900              | 1        | 0.74%   |
| Pegatron CQ3476L       | 1        | 0.74%   |
| Packard Bell IMEDIA    | 1        | 0.74%   |
| OEM Intel              | 1        | 0.74%   |
| MSI p6772l             | 1        | 0.74%   |
| MSI MS-7C52            | 1        | 0.74%   |
| MSI MS-7C35            | 1        | 0.74%   |
| MSI MS-7B89            | 1        | 0.74%   |
| MSI MS-7B85            | 1        | 0.74%   |
| MSI MS-7A63            | 1        | 0.74%   |
| MSI MS-7A38            | 1        | 0.74%   |
| MSI MS-7A32            | 1        | 0.74%   |
| MSI MS-7A15            | 1        | 0.74%   |
| MSI MS-7978            | 1        | 0.74%   |
| MSI MS-7914            | 1        | 0.74%   |
| MSI MS-7641            | 1        | 0.74%   |
| MSI KY779AA-AKL        | 1        | 0.74%   |
| MiTAC PD14RI           | 1        | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 21       | 15.56%  |
| 2019 | 12       | 8.89%   |
| 2013 | 12       | 8.89%   |
| 2016 | 11       | 8.15%   |
| 2012 | 11       | 8.15%   |
| 2020 | 10       | 7.41%   |
| 2014 | 10       | 7.41%   |
| 2011 | 10       | 7.41%   |
| 2017 | 9        | 6.67%   |
| 2009 | 9        | 6.67%   |
| 2010 | 5        | 3.7%    |
| 2015 | 4        | 2.96%   |
| 2008 | 4        | 2.96%   |
| 2021 | 3        | 2.22%   |
| 2006 | 2        | 1.48%   |
| 2007 | 1        | 0.74%   |
| 2005 | 1        | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 135      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 133      | 97.79%  |
| Enabled  | 3        | 2.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 33       | 23.57%  |
| 8.01-16.0       | 33       | 23.57%  |
| 4.01-8.0        | 25       | 17.86%  |
| 3.01-4.0        | 24       | 17.14%  |
| 32.01-64.0      | 14       | 10%     |
| 1.01-2.0        | 6        | 4.29%   |
| 64.01-256.0     | 2        | 1.43%   |
| More than 256.0 | 1        | 0.71%   |
| 24.01-32.0      | 1        | 0.71%   |
| 0.51-1.0        | 1        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 56       | 37.33%  |
| 2.01-3.0   | 49       | 32.67%  |
| 4.01-8.0   | 15       | 10%     |
| 3.01-4.0   | 14       | 9.33%   |
| 0.51-1.0   | 8        | 5.33%   |
| 8.01-16.0  | 4        | 2.67%   |
| 16.01-24.0 | 2        | 1.33%   |
| 24.01-32.0 | 1        | 0.67%   |
| 0.01-0.5   | 1        | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 57       | 40.43%  |
| 2      | 43       | 30.5%   |
| 3      | 22       | 15.6%   |
| 4      | 10       | 7.09%   |
| 5      | 5        | 3.55%   |
| 0      | 3        | 2.13%   |
| 32     | 1        | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 59.12%  |
| Yes       | 56       | 40.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 131      | 97.04%  |
| No        | 4        | 2.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 51.09%  |
| No        | 67       | 48.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 73.19%  |
| Yes       | 37       | 26.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Thailand | 135      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Bangkok           | 47       | 33.57%  |
| Chiang Mai        | 18       | 12.86%  |
| Phuket            | 5        | 3.57%   |
| Bang Lamung       | 5        | 3.57%   |
| Khon Kaen         | 4        | 2.86%   |
| Surin             | 3        | 2.14%   |
| Songkhla          | 3        | 2.14%   |
| Pattaya           | 3        | 2.14%   |
| Chon Buri         | 3        | 2.14%   |
| Phitsanulok       | 2        | 1.43%   |
| Pathum Thani      | 2        | 1.43%   |
| Nonthaburi        | 2        | 1.43%   |
| Nakhon Ratchasima | 2        | 1.43%   |
| Nakhon Pathom     | 2        | 1.43%   |
| Lampang           | 2        | 1.43%   |
| Hua Hin           | 2        | 1.43%   |
| Bang Khae         | 2        | 1.43%   |
| Ban Du            | 2        | 1.43%   |
| Ban Bang Tanot    | 2        | 1.43%   |
| Yarang            | 1        | 0.71%   |
| Trat              | 1        | 0.71%   |
| Thung Song        | 1        | 0.71%   |
| Suan Luang        | 1        | 0.71%   |
| Si Racha          | 1        | 0.71%   |
| San Sai           | 1        | 0.71%   |
| Samut Songkhram   | 1        | 0.71%   |
| Samphanthawong    | 1        | 0.71%   |
| Phetchabun        | 1        | 0.71%   |
| Phan              | 1        | 0.71%   |
| Pak Kret          | 1        | 0.71%   |
| Nong Khaem        | 1        | 0.71%   |
| Nakhon Sawan      | 1        | 0.71%   |
| Mukdahan          | 1        | 0.71%   |
| Mueang Phuket     | 1        | 0.71%   |
| Loei              | 1        | 0.71%   |
| Lat Krabang       | 1        | 0.71%   |
| Krabi             | 1        | 0.71%   |
| Khlong Luang      | 1        | 0.71%   |
| Don Mueang        | 1        | 0.71%   |
| Chok Chai         | 1        | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 53       | 87     | 22.36%  |
| Seagate                   | 50       | 76     | 21.1%   |
| Samsung Electronics       | 22       | 38     | 9.28%   |
| Kingston                  | 13       | 13     | 5.49%   |
| SanDisk                   | 10       | 12     | 4.22%   |
| Crucial                   | 8        | 8      | 3.38%   |
| Toshiba                   | 7        | 9      | 2.95%   |
| Hitachi                   | 7        | 7      | 2.95%   |
| HS-SSD-C100               | 6        | 10     | 2.53%   |
| Unknown                   | 5        | 10     | 2.11%   |
| Apacer                    | 5        | 5      | 2.11%   |
| Phison                    | 4        | 9      | 1.69%   |
| Intel                     | 4        | 4      | 1.69%   |
| Silicon Motion            | 3        | 4      | 1.27%   |
| KingSpec                  | 3        | 5      | 1.27%   |
| JMicron Technology        | 3        | 3      | 1.27%   |
| Hikvision                 | 3        | 3      | 1.27%   |
| GALAX                     | 3        | 3      | 1.27%   |
| SK hynix                  | 2        | 3      | 0.84%   |
| Plextor                   | 2        | 2      | 0.84%   |
| HGST                      | 2        | 5      | 0.84%   |
| External                  | 2        | 2      | 0.84%   |
| Corsair                   | 2        | 2      | 0.84%   |
| Colorful                  | 2        | 3      | 0.84%   |
| China                     | 2        | 2      | 0.84%   |
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
| Seagate ST500DM002-1BD142 500GB  | 7        | 2.57%   |
| Seagate ST1000DM010-2EP102 1TB   | 6        | 2.21%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 1.84%   |
| Kingston SUV400S37120G 120GB SSD | 5        | 1.84%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 1.47%   |
| WDC WD10EZEX-00WN4A0 1TB         | 4        | 1.47%   |
| Seagate ST2000VX008-2E3164 2TB   | 4        | 1.47%   |
| Crucial CT500MX500SSD1 500GB     | 4        | 1.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 3        | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 3        | 1.1%    |
| WDC WD20EZAZ-00GGJB0 2TB         | 3        | 1.1%    |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.1%    |
| Unknown SD/MMC/MS PRO 2GB        | 3        | 1.1%    |
| Toshiba DT01ACA100 1TB           | 3        | 1.1%    |
| Seagate ST3500418AS 500GB        | 3        | 1.1%    |
| SanDisk SDSSDA120G 120GB         | 3        | 1.1%    |
| Samsung NVMe SSD Drive 250GB     | 3        | 1.1%    |
| Samsung HD103SJ 1TB              | 3        | 1.1%    |
| Phison NVMe SSD Drive 240GB      | 3        | 1.1%    |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.1%    |
| HS-SSD-C100 240G                 | 3        | 1.1%    |
| HS-SSD-C100 120G                 | 3        | 1.1%    |
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
| Apacer              | 5        | 5      | 6.41%   |
| SanDisk             | 4        | 5      | 5.13%   |
| Intel               | 4        | 4      | 5.13%   |
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
| HDD     | 94       | 187    | 47.47%  |
| SSD     | 64       | 90     | 32.32%  |
| NVMe    | 29       | 49     | 14.65%  |
| Unknown | 11       | 15     | 5.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 126      | 276    | 75.9%   |
| NVMe | 26       | 46     | 15.66%  |
| SAS  | 14       | 19     | 8.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 145    | 53.63%  |
| 0.51-1.0   | 49       | 70     | 27.37%  |
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
| 101-250        | 40       | 28.37%  |
| 251-500        | 21       | 14.89%  |
| 501-1000       | 19       | 13.48%  |
| 1-20           | 14       | 9.93%   |
| 1001-2000      | 10       | 7.09%   |
| More than 3000 | 9        | 6.38%   |
| 2001-3000      | 9        | 6.38%   |
| 21-50          | 7        | 4.96%   |
| 51-100         | 7        | 4.96%   |
| Unknown        | 5        | 3.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 36.73%  |
| 21-50          | 24       | 16.33%  |
| 101-250        | 15       | 10.2%   |
| 51-100         | 15       | 10.2%   |
| 501-1000       | 11       | 7.48%   |
| 1001-2000      | 8        | 5.44%   |
| 251-500        | 7        | 4.76%   |
| More than 3000 | 6        | 4.08%   |
| Unknown        | 5        | 3.4%    |
| 2001-3000      | 2        | 1.36%   |

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
| Detected | 105      | 242    | 70%     |
| Works    | 34       | 85     | 22.67%  |
| Malfunc  | 10       | 13     | 6.67%   |
| Failed   | 1        | 1      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 92       | 52.27%  |
| AMD                         | 36       | 20.45%  |
| SanDisk                     | 9        | 5.11%   |
| ASMedia Technology          | 8        | 4.55%   |
| Samsung Electronics         | 7        | 3.98%   |
| Nvidia                      | 6        | 3.41%   |
| Phison Electronics          | 5        | 2.84%   |
| Silicon Motion              | 3        | 1.7%    |
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
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 10%     |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 5.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 5.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 4.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 4.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 4.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 3.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.73%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.27%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 1.36%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 1.36%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.36%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.36%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 1.36%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.36%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.36%   |
| SanDisk Non-Volatile memory controller                                                  | 2        | 0.91%   |
| Nvidia MCP73 IDE Controller                                                             | 2        | 0.91%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.91%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.91%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.91%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.91%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.91%   |
| VIA VX900 Series Serial-ATA Controller                                                  | 1        | 0.45%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.45%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 107      | 59.44%  |
| IDE  | 37       | 20.56%  |
| NVMe | 27       | 15%     |
| RAID | 7        | 3.89%   |
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
| Intel        | 94       | 69.63%  |
| AMD          | 40       | 29.63%  |
| CentaurHauls | 1        | 0.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 3.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 2.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.19%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 2.19%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.46%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.46%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.46%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.46%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.46%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.46%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.46%   |
| AMD Phenom II X6 1055T Processor            | 2        | 1.46%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 0.73%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.73%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.73%   |
| Intel Xeon CPU E5-2698 v4 @ 2.20GHz         | 1        | 0.73%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 0.73%   |
| Intel Xeon CPU E5-2640 v2 @ 2.00GHz         | 1        | 0.73%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 1        | 0.73%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.73%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1        | 0.73%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.73%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.73%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.73%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.73%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.73%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.73%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.73%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.73%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.73%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.73%   |
| Intel Core i7-4790T CPU @ 2.70GHz           | 1        | 0.73%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1        | 0.73%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.73%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 20.59%  |
| Intel Core i3           | 21       | 15.44%  |
| Intel Core i7           | 18       | 13.24%  |
| AMD Ryzen 5             | 8        | 5.88%   |
| Intel Xeon              | 7        | 5.15%   |
| AMD Ryzen 7             | 5        | 3.68%   |
| Intel Pentium           | 4        | 2.94%   |
| Intel Core 2 Quad       | 4        | 2.94%   |
| AMD Ryzen 3             | 4        | 2.94%   |
| AMD FX                  | 4        | 2.94%   |
| AMD Athlon II X2        | 4        | 2.94%   |
| Intel Pentium Dual-Core | 3        | 2.21%   |
| Intel Core i9           | 2        | 1.47%   |
| Intel Core 2 Duo        | 2        | 1.47%   |
| Intel Celeron           | 2        | 1.47%   |
| AMD Ryzen 9             | 2        | 1.47%   |
| AMD Phenom II X6        | 2        | 1.47%   |
| AMD Phenom II X4        | 2        | 1.47%   |
| AMD Athlon 64 X2        | 2        | 1.47%   |
| AMD A6                  | 2        | 1.47%   |
| AMD A4                  | 2        | 1.47%   |
| AMD A10                 | 2        | 1.47%   |
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
| 4      | 53       | 38.97%  |
| 2      | 43       | 31.62%  |
| 6      | 19       | 13.97%  |
| 8      | 13       | 9.56%   |
| 12     | 3        | 2.21%   |
| 1      | 3        | 2.21%   |
| 40     | 1        | 0.74%   |
| 3      | 1        | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 132      | 97.78%  |
| 2      | 3        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 75       | 55.15%  |
| 1      | 61       | 44.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 135      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 22.7%   |
| 0x306c3    | 14       | 9.93%   |
| 0x206a7    | 9        | 6.38%   |
| 0x506e3    | 8        | 5.67%   |
| 0x906ea    | 6        | 4.26%   |
| 0x906e9    | 6        | 4.26%   |
| 0x1067a    | 6        | 4.26%   |
| 0x306a9    | 4        | 2.84%   |
| 0x0800820d | 4        | 2.84%   |
| 0xa0655    | 3        | 2.13%   |
| 0x906ec    | 3        | 2.13%   |
| 0x20655    | 3        | 2.13%   |
| 0x010000c8 | 3        | 2.13%   |
| 0x08001138 | 2        | 1.42%   |
| 0x06003106 | 2        | 1.42%   |
| 0x06001119 | 2        | 1.42%   |
| 0x06000852 | 2        | 1.42%   |
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
| 0x0a201009 | 1        | 0.71%   |
| 0x08701021 | 1        | 0.71%   |
| 0x08701013 | 1        | 0.71%   |
| 0x08600106 | 1        | 0.71%   |
| 0x08108109 | 1        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 19       | 13.97%  |
| KabyLake    | 18       | 13.24%  |
| Skylake     | 11       | 8.09%   |
| SandyBridge | 11       | 8.09%   |
| Penryn      | 9        | 6.62%   |
| IvyBridge   | 9        | 6.62%   |
| K10         | 8        | 5.88%   |
| Zen 2       | 7        | 5.15%   |
| Zen+        | 6        | 4.41%   |
| Piledriver  | 5        | 3.68%   |
| CometLake   | 5        | 3.68%   |
| Zen         | 4        | 2.94%   |
| Westmere    | 4        | 2.94%   |
| Zen 3       | 3        | 2.21%   |
| Silvermont  | 3        | 2.21%   |
| Steamroller | 2        | 1.47%   |
| K8 Hammer   | 2        | 1.47%   |
| Excavator   | 2        | 1.47%   |
| Core        | 2        | 1.47%   |
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
| Nvidia           | 62       | 42.47%  |
| Intel            | 45       | 30.82%  |
| AMD              | 38       | 26.03%  |
| VIA Technologies | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 5.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 4.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 3.95%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.29%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 3.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5        | 3.29%   |
| Intel HD Graphics 530                                                                    | 5        | 3.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.97%   |
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
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.66%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.66%   |
| Nvidia GT218 [ION]                                                                       | 1        | 0.66%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.66%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.66%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 54       | 38.03%  |
| 1 x Intel            | 42       | 29.58%  |
| 1 x AMD              | 34       | 23.94%  |
| AMD + Nvidia         | 4        | 2.82%   |
| Intel + Nvidia       | 2        | 1.41%   |
| 3 x Nvidia           | 1        | 0.7%    |
| 2 x Nvidia           | 1        | 0.7%    |
| 2 x AMD + 1 x Nvidia | 1        | 0.7%    |
| 2 x AMD              | 1        | 0.7%    |
| 1 x VIA              | 1        | 0.7%    |
| AMD + 2 x Nvidia     | 1        | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 74.1%   |
| Proprietary | 30       | 21.58%  |
| Unknown     | 6        | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 44.44%  |
| 1.01-2.0   | 23       | 15.97%  |
| 0.51-1.0   | 14       | 9.72%   |
| 3.01-4.0   | 13       | 9.03%   |
| 0.01-0.5   | 12       | 8.33%   |
| 7.01-8.0   | 10       | 6.94%   |
| 5.01-6.0   | 4        | 2.78%   |
| 4.01-5.0   | 1        | 0.69%   |
| 2.01-3.0   | 1        | 0.69%   |
| 16.01-24.0 | 1        | 0.69%   |
| 8.01-16.0  | 1        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 30       | 21.43%  |
| Acer                 | 22       | 15.71%  |
| Goldstar             | 21       | 15%     |
| Hewlett-Packard      | 10       | 7.14%   |
| Dell                 | 9        | 6.43%   |
| AOC                  | 9        | 6.43%   |
| BenQ                 | 6        | 4.29%   |
| LG Electronics       | 4        | 2.86%   |
| ViewSonic            | 3        | 2.14%   |
| Lenovo               | 3        | 2.14%   |
| Unknown (XXX)        | 2        | 1.43%   |
| Sharp                | 2        | 1.43%   |
| MStar                | 2        | 1.43%   |
| Ancor Communications | 2        | 1.43%   |
| Toshiba              | 1        | 0.71%   |
| Sony                 | 1        | 0.71%   |
| SGT                  | 1        | 0.71%   |
| MIG                  | 1        | 0.71%   |
| Microstep            | 1        | 0.71%   |
| ITE                  | 1        | 0.71%   |
| IOD                  | 1        | 0.71%   |
| HUYINIUDA            | 1        | 0.71%   |
| HPN                  | 1        | 0.71%   |
| Gateway              | 1        | 0.71%   |
| Fujitsu Siemens      | 1        | 0.71%   |
| Fujitsu              | 1        | 0.71%   |
| CHI                  | 1        | 0.71%   |
| ASUSTek Computer     | 1        | 0.71%   |
| Apple                | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2        | 1.34%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2        | 1.34%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2        | 1.34%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 1.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 1.34%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch      | 2        | 1.34%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2        | 1.34%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2        | 1.34%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 2        | 1.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 1.34%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                       | 2        | 1.34%   |
| Acer X193W ACR000C 1440x900 410x256mm 19.0-inch                       | 2        | 1.34%   |
| Acer X193HQ ACR0067 1366x768 410x230mm 18.5-inch                      | 2        | 1.34%   |
| Acer S200HQL ACR0359 1600x900 434x236mm 19.4-inch                     | 2        | 1.34%   |
| Acer K242HQL ACR042E 1920x1080 521x293mm 23.5-inch                    | 2        | 1.34%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                | 1        | 0.67%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1210x680mm 54.6-inch         | 1        | 0.67%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch             | 1        | 0.67%   |
| Toshiba TV TSB0114 1920x1080 882x498mm 39.9-inch                      | 1        | 0.67%   |
| Sony TV SNY9402 1920x1080                                             | 1        | 0.67%   |
| Sharp HDMI SHP113E 1920x1080 1330x748mm 60.1-inch                     | 1        | 0.67%   |
| Sharp HDMI SHP110F 1920x1080 700x390mm 31.5-inch                      | 1        | 0.67%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM044F 1440x900 408x255mm 18.9-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM03BA 1680x1050                      | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 1        | 0.67%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch     | 1        | 0.67%   |
| Samsung Electronics SA300/SA350 SAM0790 1920x1080 510x287mm 23.0-inch | 1        | 0.67%   |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch     | 1        | 0.67%   |
| Samsung Electronics S27D590 SAM0BE9 1920x1080 598x336mm 27.0-inch     | 1        | 0.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.67%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 0.67%   |
| Samsung Electronics S23B370 SAM089B 1920x1080 510x287mm 23.0-inch     | 1        | 0.67%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 0.67%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch     | 1        | 0.67%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1        | 0.67%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch      | 1        | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 48.2%   |
| 1600x900 (HD+)     | 12       | 8.63%   |
| 1366x768 (WXGA)    | 11       | 7.91%   |
| 3840x2160 (4K)     | 8        | 5.76%   |
| 1680x1050 (WSXGA+) | 8        | 5.76%   |
| 1440x900 (WXGA+)   | 8        | 5.76%   |
| 1280x1024 (SXGA)   | 5        | 3.6%    |
| 2560x1440 (QHD)    | 4        | 2.88%   |
| Unknown            | 4        | 2.88%   |
| 2560x1080          | 3        | 2.16%   |
| 3840x1080          | 2        | 1.44%   |
| 1360x768           | 2        | 1.44%   |
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
| 23      | 24       | 17.02%  |
| Unknown | 16       | 11.35%  |
| 24      | 14       | 9.93%   |
| 19      | 13       | 9.22%   |
| 27      | 12       | 8.51%   |
| 21      | 12       | 8.51%   |
| 18      | 12       | 8.51%   |
| 20      | 11       | 7.8%    |
| 22      | 6        | 4.26%   |
| 34      | 4        | 2.84%   |
| 15      | 3        | 2.13%   |
| 52      | 2        | 1.42%   |
| 31      | 2        | 1.42%   |
| 17      | 2        | 1.42%   |
| 84      | 1        | 0.71%   |
| 72      | 1        | 0.71%   |
| 60      | 1        | 0.71%   |
| 54      | 1        | 0.71%   |
| 47      | 1        | 0.71%   |
| 39      | 1        | 0.71%   |
| 29      | 1        | 0.71%   |
| 16      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 52       | 38.24%  |
| 501-600     | 46       | 33.82%  |
| Unknown     | 16       | 11.76%  |
| 301-350     | 6        | 4.41%   |
| 1001-1500   | 5        | 3.68%   |
| 701-800     | 4        | 2.94%   |
| 601-700     | 3        | 2.21%   |
| 351-400     | 2        | 1.47%   |
| 801-900     | 1        | 0.74%   |
| 1501-2000   | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 90       | 67.67%  |
| 16/10   | 18       | 13.53%  |
| Unknown | 15       | 11.28%  |
| 5/4     | 5        | 3.76%   |
| 21/9    | 4        | 3.01%   |
| 4/3     | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 49       | 35.51%  |
| 151-200        | 28       | 20.29%  |
| Unknown        | 16       | 11.59%  |
| 301-350        | 12       | 8.7%    |
| 141-150        | 11       | 7.97%   |
| 351-500        | 7        | 5.07%   |
| More than 1000 | 5        | 3.62%   |
| 251-300        | 3        | 2.17%   |
| 101-110        | 3        | 2.17%   |
| 501-1000       | 2        | 1.45%   |
| 131-140        | 1        | 0.72%   |
| 121-130        | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 83       | 64.34%  |
| 101-120 | 18       | 13.95%  |
| Unknown | 16       | 12.4%   |
| 1-50    | 6        | 4.65%   |
| 161-240 | 4        | 3.1%    |
| 121-160 | 2        | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 78.57%  |
| 2     | 18       | 12.86%  |
| 0     | 9        | 6.43%   |
| 3     | 3        | 2.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 89       | 46.11%  |
| Intel                           | 44       | 22.8%   |
| Qualcomm Atheros                | 14       | 7.25%   |
| Ralink Technology               | 10       | 5.18%   |
| D-Link                          | 6        | 3.11%   |
| Nvidia                          | 5        | 2.59%   |
| Broadcom                        | 4        | 2.07%   |
| TP-Link                         | 3        | 1.55%   |
| D-Link System                   | 3        | 1.55%   |
| Ralink                          | 2        | 1.04%   |
| Mercucys                        | 2        | 1.04%   |
| Xiaomi                          | 1        | 0.52%   |
| VIA Technologies                | 1        | 0.52%   |
| Samsung Electronics             | 1        | 0.52%   |
| Qualcomm Atheros Communications | 1        | 0.52%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.52%   |
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


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75       | 34.72%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.31%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 5        | 2.31%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 2.31%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4        | 1.85%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.85%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.85%   |
| Realtek 802.11ac NIC                                              | 3        | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.39%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]     | 3        | 1.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.93%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.93%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 2        | 0.93%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.93%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.93%   |
| Mercucys 802.11n NIC                                              | 2        | 0.93%   |
| Intel Wireless-AC 9260                                            | 2        | 0.93%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.93%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.93%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.46%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.46%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1        | 0.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.46%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.46%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 25.35%  |
| Intel                           | 12       | 16.9%   |
| Qualcomm Atheros                | 11       | 15.49%  |
| Ralink Technology               | 10       | 14.08%  |
| D-Link                          | 6        | 8.45%   |
| TP-Link                         | 3        | 4.23%   |
| Ralink                          | 2        | 2.82%   |
| Mercucys                        | 2        | 2.82%   |
| Qualcomm Atheros Communications | 1        | 1.41%   |
| MediaTek                        | 1        | 1.41%   |
| Edimax Technology               | 1        | 1.41%   |
| D-Link System                   | 1        | 1.41%   |
| BUFFALO                         | 1        | 1.41%   |
| Broadcom                        | 1        | 1.41%   |
| ASUSTek Computer                | 1        | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 6        | 8.45%   |
| Ralink MT7601U Wireless Adapter                                              | 5        | 7.04%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                              | 4        | 5.63%   |
| Realtek 802.11ac NIC                                                         | 3        | 4.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 3        | 4.23%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                | 3        | 4.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                              | 2        | 2.82%   |
| Ralink RT2501/RT2573 Wireless Adapter                                        | 2        | 2.82%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                            | 2        | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 2        | 2.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)               | 2        | 2.82%   |
| Mercucys 802.11n NIC                                                         | 2        | 2.82%   |
| Intel Wireless-AC 9260                                                       | 2        | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                             | 2        | 2.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                 | 1        | 1.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                   | 1        | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                   | 1        | 1.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                          | 1        | 1.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                       | 1        | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                   | 1        | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                        | 1        | 1.41%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                         | 1        | 1.41%   |
| Ralink RT2561/RT61 rev B 802.11g                                             | 1        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 1        | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1        | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 1        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 1        | 1.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                             | 1        | 1.41%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]       | 1        | 1.41%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]          | 1        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                | 1        | 1.41%   |
| Intel Wireless 7260                                                          | 1        | 1.41%   |
| Intel Wireless 3165                                                          | 1        | 1.41%   |
| Intel Wireless 3160                                                          | 1        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                       | 1        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                          | 1        | 1.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]               | 1        | 1.41%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]         | 1        | 1.41%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 1        | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 83       | 59.29%  |
| Intel                         | 38       | 27.14%  |
| Nvidia                        | 5        | 3.57%   |
| Qualcomm Atheros              | 4        | 2.86%   |
| Broadcom                      | 3        | 2.14%   |
| D-Link System                 | 2        | 1.43%   |
| Xiaomi                        | 1        | 0.71%   |
| VIA Technologies              | 1        | 0.71%   |
| Samsung Electronics           | 1        | 0.71%   |
| OnePlus Technology (Shenzhen) | 1        | 0.71%   |
| Aquantia                      | 1        | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75       | 52.08%  |
| Intel Ethernet Connection (2) I219-V                              | 6        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.47%   |
| Intel I211 Gigabit Network Connection                             | 5        | 3.47%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.47%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.78%   |
| Nvidia MCP61 Ethernet                                             | 3        | 2.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 1.39%   |
| Nvidia MCP73 Ethernet                                             | 2        | 1.39%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.39%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.39%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1        | 0.69%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.69%   |
| OnePlus (Shenzhen) OnePlus                                        | 1        | 0.69%   |
| Intel I210 Gigabit Unprogrammed                                   | 1        | 0.69%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.69%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.69%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.69%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.69%   |
| Aquantia AQC108 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 64.85%  |
| WiFi     | 70       | 34.65%  |
| Modem    | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 85       | 61.59%  |
| WiFi     | 53       | 38.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 64.71%  |
| 2     | 41       | 30.15%  |
| 0     | 4        | 2.94%   |
| 4     | 2        | 1.47%   |
| 3     | 1        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 109      | 76.76%  |
| Yes  | 33       | 23.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 20       | 52.63%  |
| Intel                           | 11       | 28.95%  |
| Qualcomm Atheros Communications | 2        | 5.26%   |
| ASUSTek Computer                | 2        | 5.26%   |
| MediaTek                        | 1        | 2.63%   |
| Lite-On Technology              | 1        | 2.63%   |
| Apple                           | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 52.63%  |
| Intel Bluetooth wireless interface                  | 3        | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 7.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 2.63%   |
| MediaTek Wireless_Device                            | 1        | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 2.63%   |
| Intel AX200 Bluetooth                               | 1        | 2.63%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.63%   |
| ASUS Bluetooth Device                               | 1        | 2.63%   |
| Apple Bluetooth HCI                                 | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 40.61%  |
| Nvidia                      | 58       | 25.33%  |
| AMD                         | 52       | 22.71%  |
| C-Media Electronics         | 9        | 3.93%   |
| JMTek                       | 3        | 1.31%   |
| SAVITECH                    | 2        | 0.87%   |
| Elan Microelectronics       | 2        | 0.87%   |
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
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14       | 5.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13       | 4.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 12       | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9        | 3.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.28%   |
| Nvidia High Definition Audio Controller                                                           | 8        | 2.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 2.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 2.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7        | 2.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 2.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6        | 2.19%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6        | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6        | 2.19%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5        | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 5        | 1.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5        | 1.82%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4        | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 1.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.46%   |
| C-Media Electronics USB Audio Device                                                              | 4        | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 1.46%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.09%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 3        | 1.09%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.09%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3        | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 1.09%   |
| AMD Navi 10 HDMI Audio                                                                            | 3        | 1.09%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3        | 1.09%   |
| SAVITECH SA9023 audio controller                                                                  | 2        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 0.73%   |
| Nvidia MCP73 High Definition Audio                                                                | 2        | 0.73%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 2        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 43.4%   |
| Unknown             | 9        | 16.98%  |
| SK hynix            | 7        | 13.21%  |
| Corsair             | 5        | 9.43%   |
| Samsung Electronics | 3        | 5.66%   |
| G.Skill             | 2        | 3.77%   |
| Unknown (0x02BA)    | 1        | 1.89%   |
| Transcend           | 1        | 1.89%   |
| A-DATA Technology   | 1        | 1.89%   |
| Unknown             | 1        | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 5        | 8.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 3        | 5.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 2        | 3.45%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s      | 2        | 3.45%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s       | 2        | 3.45%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 2        | 3.45%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 3.45%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2        | 3.45%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 1.72%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 1.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 1.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 1.72%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s   | 1        | 1.72%   |
| Transcend RAM TS256MLQ64V8U 2GB DIMM DDR 533MT/s          | 1        | 1.72%   |
| SK hynix RAM Module 1024MB FB-DIMM DDR2 800MT/s           | 1        | 1.72%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s     | 1        | 1.72%   |
| SK hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1        | 1.72%   |
| SK hynix RAM HMA84GL7MMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 1.72%   |
| SK hynix RAM HMA84GL7AMR4N-TF 32GB RIMM DDR4 2133MT/s     | 1        | 1.72%   |
| SK hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s | 1        | 1.72%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 1.72%   |
| Kingston RAM Module 2GB DIMM DDR 533MT/s                  | 1        | 1.72%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 1.72%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s       | 1        | 1.72%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.72%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s    | 1        | 1.72%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s       | 1        | 1.72%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 1.72%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 1.72%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s       | 1        | 1.72%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 1.72%   |
| Kingston RAM 99U5474-026.A 4GB DIMM DDR3 1333MT/s         | 1        | 1.72%   |
| Kingston RAM 99U5471-050.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 1.72%   |
| Kingston RAM 99U5403-002.A00G 2048MB DIMM DDR3 1333MT/s   | 1        | 1.72%   |
| Kingston RAM 9905678-041.A00G 4GB DIMM DDR4 2400MT/s      | 1        | 1.72%   |
| Kingston RAM 9905428-123.A00LF 8GB SODIMM DDR3 1600MT/s   | 1        | 1.72%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s       | 1        | 1.72%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1600MT/s         | 1        | 1.72%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s    | 1        | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 47.92%  |
| DDR3    | 13       | 27.08%  |
| Unknown | 4        | 8.33%   |
| SDRAM   | 3        | 6.25%   |
| DDR2    | 2        | 4.17%   |
| DDR     | 2        | 4.17%   |
| LPDDR4  | 1        | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 41       | 91.11%  |
| SODIMM  | 2        | 4.44%   |
| RIMM    | 1        | 2.22%   |
| FB-DIMM | 1        | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 20       | 41.67%  |
| 4096  | 14       | 29.17%  |
| 2048  | 7        | 14.58%  |
| 16384 | 4        | 8.33%   |
| 1024  | 2        | 4.17%   |
| 32768 | 1        | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 11       | 21.15%  |
| 1600    | 8        | 15.38%  |
| 3600    | 6        | 11.54%  |
| 3200    | 4        | 7.69%   |
| 2400    | 3        | 5.77%   |
| 3466    | 2        | 3.85%   |
| 3151    | 2        | 3.85%   |
| 2667    | 2        | 3.85%   |
| 2133    | 2        | 3.85%   |
| 1866    | 2        | 3.85%   |
| 3333    | 1        | 1.92%   |
| 3000    | 1        | 1.92%   |
| 2933    | 1        | 1.92%   |
| 2800    | 1        | 1.92%   |
| 2666    | 1        | 1.92%   |
| 1867    | 1        | 1.92%   |
| 800     | 1        | 1.92%   |
| 667     | 1        | 1.92%   |
| 533     | 1        | 1.92%   |
| Unknown | 1        | 1.92%   |

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
| Seiko Epson L222 Series          | 1        | 14.29%  |
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
| Sunplus USB camera                   | 1        | 5.26%   |
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
| 0     | 119      | 88.15%  |
| 1     | 13       | 9.63%   |
| 7     | 1        | 0.74%   |
| 5     | 1        | 0.74%   |
| 2     | 1        | 0.74%   |

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

