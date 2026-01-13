LMDE 6 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 6.

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

Total: 486

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| American M... | K7S41GX                     | [1e5ee9ad40](https://linux-hardware.org/?probe=1e5ee9ad40) | Jan 01, 2026 |
| ASUSTek       | L1N64-SLI WS                | [68a8fcbc78](https://linux-hardware.org/?probe=68a8fcbc78) | Dec 25, 2025 |
| ASUSTek       | H110M-K                     | [c2430d1ead](https://linux-hardware.org/?probe=c2430d1ead) | Dec 06, 2025 |
| ASUSTek       | H110M-K                     | [0c3f148abd](https://linux-hardware.org/?probe=0c3f148abd) | Dec 05, 2025 |
| Gigabyte      | H310M A-CF                  | [9868d596d4](https://linux-hardware.org/?probe=9868d596d4) | Dec 03, 2025 |
| HP            | 8455                        | [77c23b390e](https://linux-hardware.org/?probe=77c23b390e) | Dec 01, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [682862ada2](https://linux-hardware.org/?probe=682862ada2) | Nov 07, 2025 |
| Medion        | TJ4125                      | [63e42ef2ef](https://linux-hardware.org/?probe=63e42ef2ef) | Nov 04, 2025 |
| MSI           | Z77A-G43                    | [830f7ec089](https://linux-hardware.org/?probe=830f7ec089) | Nov 04, 2025 |
| Medion        | TJ4125                      | [92b1b520f0](https://linux-hardware.org/?probe=92b1b520f0) | Nov 03, 2025 |
| G7-2011       | X79                         | [cb93f5ed68](https://linux-hardware.org/?probe=cb93f5ed68) | Nov 01, 2025 |
| Gigabyte      | Z77X-D3H                    | [c02b5b750f](https://linux-hardware.org/?probe=c02b5b750f) | Oct 25, 2025 |
| HP            | 0B4Ch D                     | [700d0a69be](https://linux-hardware.org/?probe=700d0a69be) | Oct 23, 2025 |
| HP            | 8768 A                      | [31a76f1737](https://linux-hardware.org/?probe=31a76f1737) | Oct 23, 2025 |
| ASRock        | N68C-S UCC                  | [a33d72f651](https://linux-hardware.org/?probe=a33d72f651) | Oct 22, 2025 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a1a196668e](https://linux-hardware.org/?probe=a1a196668e) | Oct 21, 2025 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [98d85b2c6b](https://linux-hardware.org/?probe=98d85b2c6b) | Oct 18, 2025 |
| HP            | 8455                        | [d1afecec96](https://linux-hardware.org/?probe=d1afecec96) | Oct 16, 2025 |
| MSI           | PRO B550M-VC WIFI           | [e814c82d53](https://linux-hardware.org/?probe=e814c82d53) | Oct 13, 2025 |
| Gigabyte      | 965P-DS3                    | [b787c8b019](https://linux-hardware.org/?probe=b787c8b019) | Oct 13, 2025 |
| Medion        | TJ4125                      | [79e6dbfaac](https://linux-hardware.org/?probe=79e6dbfaac) | Oct 12, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2d44f8fc4d](https://linux-hardware.org/?probe=2d44f8fc4d) | Oct 11, 2025 |
| Medion        | TJ4125                      | [2d80da577e](https://linux-hardware.org/?probe=2d80da577e) | Oct 11, 2025 |
| ASUSTek       | M4A88T-V EVO/USB3           | [0597cfadf8](https://linux-hardware.org/?probe=0597cfadf8) | Oct 06, 2025 |
| HP            | 1587h                       | [d7614e4788](https://linux-hardware.org/?probe=d7614e4788) | Oct 05, 2025 |
| HP            | 18E7                        | [99ee0a97ed](https://linux-hardware.org/?probe=99ee0a97ed) | Oct 02, 2025 |
| ASUSTek       | P8H61-M LE                  | [c2431dbbc0](https://linux-hardware.org/?probe=c2431dbbc0) | Sep 29, 2025 |
| GEEKOM        | AE8                         | [09521a14be](https://linux-hardware.org/?probe=09521a14be) | Sep 28, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [66ce917656](https://linux-hardware.org/?probe=66ce917656) | Sep 28, 2025 |
| Medion        | TJ4125                      | [69fb618207](https://linux-hardware.org/?probe=69fb618207) | Sep 26, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | [be8df43d21](https://linux-hardware.org/?probe=be8df43d21) | Sep 17, 2025 |
| Gigabyte      | A520M K V2                  | [5423a2a6a0](https://linux-hardware.org/?probe=5423a2a6a0) | Sep 16, 2025 |
| Lenovo        | 317C SDK0J40697 WIN 3305... | [4ac7b0be11](https://linux-hardware.org/?probe=4ac7b0be11) | Sep 10, 2025 |
| Medion        | TJ4125                      | [19d5d8b4f0](https://linux-hardware.org/?probe=19d5d8b4f0) | Sep 06, 2025 |
| Medion        | TJ4125                      | [c020fb32c9](https://linux-hardware.org/?probe=c020fb32c9) | Sep 06, 2025 |
| Dell          | 0F0TGN A00                  | [028e8ba4e0](https://linux-hardware.org/?probe=028e8ba4e0) | Sep 03, 2025 |
| Dell          | 0RY007                      | [a9cda38b58](https://linux-hardware.org/?probe=a9cda38b58) | Sep 01, 2025 |
| ASUSTek       | Z77-A                       | [d14cd8d02c](https://linux-hardware.org/?probe=d14cd8d02c) | Sep 01, 2025 |
| Dell          | 0F0TGN A00                  | [df4aec1d37](https://linux-hardware.org/?probe=df4aec1d37) | Aug 30, 2025 |
| Lenovo        | SHARKBAY NOK                | [1adf3a3841](https://linux-hardware.org/?probe=1adf3a3841) | Aug 26, 2025 |
| Gigabyte      | 970A-DS3P                   | [e7930bbade](https://linux-hardware.org/?probe=e7930bbade) | Aug 24, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d507e6e482](https://linux-hardware.org/?probe=d507e6e482) | Aug 24, 2025 |
| HP            | 0B4Ch D                     | [29307b6ba6](https://linux-hardware.org/?probe=29307b6ba6) | Aug 19, 2025 |
| ASRock        | B650E PG Riptide WiFi       | [c2cf331637](https://linux-hardware.org/?probe=c2cf331637) | Aug 19, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45339db027](https://linux-hardware.org/?probe=45339db027) | Aug 19, 2025 |
| HP            | 0B40h                       | [32f5bb2fc7](https://linux-hardware.org/?probe=32f5bb2fc7) | Aug 14, 2025 |
| HP            | 2820h                       | [7fe6722bde](https://linux-hardware.org/?probe=7fe6722bde) | Aug 13, 2025 |
| Gigabyte      | Z77X-UD5H                   | [2fe929814c](https://linux-hardware.org/?probe=2fe929814c) | Aug 07, 2025 |
| ASUSTek       | TUF Gaming B850-BTF WIFI... | [d1eafaf49b](https://linux-hardware.org/?probe=d1eafaf49b) | Aug 06, 2025 |
| ASUSTek       | TUF Gaming B850-BTF WIFI... | [2578e8015b](https://linux-hardware.org/?probe=2578e8015b) | Aug 06, 2025 |
| Dell          | 0F756F A00                  | [4c88458a84](https://linux-hardware.org/?probe=4c88458a84) | Aug 06, 2025 |
| Dell          | 0F756F A00                  | [053f2e82d8](https://linux-hardware.org/?probe=053f2e82d8) | Aug 05, 2025 |
| ASUSTek       | PRIME Z390-P                | [b55f8909e0](https://linux-hardware.org/?probe=b55f8909e0) | Aug 04, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | [76f7babeb1](https://linux-hardware.org/?probe=76f7babeb1) | Aug 01, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [46aca721ed](https://linux-hardware.org/?probe=46aca721ed) | Jul 31, 2025 |
| ASUSTek       | H97M-E                      | [abfde43d99](https://linux-hardware.org/?probe=abfde43d99) | Jul 28, 2025 |
| HP            | 0B40h                       | [876fc49961](https://linux-hardware.org/?probe=876fc49961) | Jul 23, 2025 |
| Medion        | TJ4125                      | [19aff278e5](https://linux-hardware.org/?probe=19aff278e5) | Jul 19, 2025 |
| ASRock        | X670E Taichi Carrara        | [f9716af58a](https://linux-hardware.org/?probe=f9716af58a) | Jul 18, 2025 |
| Gigabyte      | B250M-DS3H-CF               | [fcc02de185](https://linux-hardware.org/?probe=fcc02de185) | Jul 13, 2025 |
| Medion        | TJ4125                      | [ead4f97792](https://linux-hardware.org/?probe=ead4f97792) | Jul 12, 2025 |
| GEEKOM        | A7                          | [51b9dc5acd](https://linux-hardware.org/?probe=51b9dc5acd) | Jul 09, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [17f31ff9bc](https://linux-hardware.org/?probe=17f31ff9bc) | Jul 09, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2bb00a50d0](https://linux-hardware.org/?probe=2bb00a50d0) | Jul 06, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [6c0adbaf73](https://linux-hardware.org/?probe=6c0adbaf73) | Jul 06, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [4c9772035e](https://linux-hardware.org/?probe=4c9772035e) | Jul 04, 2025 |
| Dell          | 0WMJ54 A01                  | [89f53b6c82](https://linux-hardware.org/?probe=89f53b6c82) | Jul 01, 2025 |
| ASRock        | B250M Pro4                  | [23c030fc52](https://linux-hardware.org/?probe=23c030fc52) | Jun 27, 2025 |
| MSI           | H110M PRO-D                 | [9677fb0820](https://linux-hardware.org/?probe=9677fb0820) | Jun 26, 2025 |
| Dell          | 0WR1RF A05                  | [c935ad3bd9](https://linux-hardware.org/?probe=c935ad3bd9) | Jun 25, 2025 |
| Lenovo        | IdeaCentre K330B            | [baa79dad9b](https://linux-hardware.org/?probe=baa79dad9b) | Jun 24, 2025 |
| Intel         | D54250WYK H13922-303        | [a4f86ce7fb](https://linux-hardware.org/?probe=a4f86ce7fb) | Jun 22, 2025 |
| Gigabyte      | B760 GAMING X DDR4          | [274069e10a](https://linux-hardware.org/?probe=274069e10a) | Jun 21, 2025 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [783a6ca047](https://linux-hardware.org/?probe=783a6ca047) | Jun 21, 2025 |
| Gigabyte      | B760 GAMING X DDR4          | [07026815a1](https://linux-hardware.org/?probe=07026815a1) | Jun 19, 2025 |
| ASUSTek       | PRIME A520M-K               | [73e9ad5501](https://linux-hardware.org/?probe=73e9ad5501) | Jun 16, 2025 |
| ASUSTek       | PRIME A520M-K               | [797a0b684c](https://linux-hardware.org/?probe=797a0b684c) | Jun 16, 2025 |
| Dell          | 00V62H A01                  | [89f331ee71](https://linux-hardware.org/?probe=89f331ee71) | Jun 15, 2025 |
| Dell          | 09M8Y8 A01                  | [66b19b8b8b](https://linux-hardware.org/?probe=66b19b8b8b) | Jun 15, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | [0aeec37aa0](https://linux-hardware.org/?probe=0aeec37aa0) | Jun 15, 2025 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [5d1855fa5e](https://linux-hardware.org/?probe=5d1855fa5e) | Jun 13, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2a2a5d6f61](https://linux-hardware.org/?probe=2a2a5d6f61) | Jun 11, 2025 |
| ECS           | H61H2-CM                    | [9541786163](https://linux-hardware.org/?probe=9541786163) | Jun 09, 2025 |
| Gigabyte      | B460M DS3H AC-Y1            | [e0c47af925](https://linux-hardware.org/?probe=e0c47af925) | Jun 08, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | [ca5fc3e6bf](https://linux-hardware.org/?probe=ca5fc3e6bf) | Jun 07, 2025 |
| Medion        | TJ4125                      | [ac1165f893](https://linux-hardware.org/?probe=ac1165f893) | Jun 05, 2025 |
| ASUSTek       | D520MT_D520SF_D320MT        | [8130f151f8](https://linux-hardware.org/?probe=8130f151f8) | Jun 02, 2025 |
| ASUSTek       | P8H61-M LE                  | [a4dafa5bf4](https://linux-hardware.org/?probe=a4dafa5bf4) | Jun 02, 2025 |
| ASRock        | B450 Gaming-ITX/ac          | [7b4176a222](https://linux-hardware.org/?probe=7b4176a222) | Jun 01, 2025 |
| MSI           | Z270M MORTAR                | [0d97e1ec7f](https://linux-hardware.org/?probe=0d97e1ec7f) | May 30, 2025 |
| Minix         | NEO Z83-4 V1.1              | [668bebd807](https://linux-hardware.org/?probe=668bebd807) | May 28, 2025 |
| WeiBu         | ADL-N Prod                  | [443f7decd6](https://linux-hardware.org/?probe=443f7decd6) | May 27, 2025 |
| HP            | 339A                        | [0adea6e20d](https://linux-hardware.org/?probe=0adea6e20d) | May 25, 2025 |
| MSI           | MPG B650 CARBON WIFI        | [1756e42bfe](https://linux-hardware.org/?probe=1756e42bfe) | May 25, 2025 |
| ASRock        | B450 Gaming-ITX/ac          | [f26af33f47](https://linux-hardware.org/?probe=f26af33f47) | May 24, 2025 |
| Intel         | DQ965GF AAD41676-402        | [cbcd411d7c](https://linux-hardware.org/?probe=cbcd411d7c) | May 23, 2025 |
| MSI           | MPG B650 CARBON WIFI        | [479c35845a](https://linux-hardware.org/?probe=479c35845a) | May 21, 2025 |
| ASUSTek       | P8H61-M LE                  | [b4c54b9c8b](https://linux-hardware.org/?probe=b4c54b9c8b) | May 19, 2025 |
| Dell          | 0X4H68 A00                  | [1a74d03045](https://linux-hardware.org/?probe=1a74d03045) | May 17, 2025 |
| ASUSTek       | PRIME Z370-P II             | [ce93cc89b1](https://linux-hardware.org/?probe=ce93cc89b1) | May 17, 2025 |
| Dell          | 00V62H A01                  | [f42972c0cd](https://linux-hardware.org/?probe=f42972c0cd) | May 14, 2025 |
| ASUSTek       | P8H61-M LE                  | [5873f9e355](https://linux-hardware.org/?probe=5873f9e355) | May 13, 2025 |
| MSI           | Z170A GAMING PRO CARBON     | [fff2a96d4a](https://linux-hardware.org/?probe=fff2a96d4a) | May 13, 2025 |
| MSI           | Z170A GAMING PRO CARBON     | [f72c58cc29](https://linux-hardware.org/?probe=f72c58cc29) | May 13, 2025 |
| ASUSTek       | H81M-C                      | [11dd2b44ab](https://linux-hardware.org/?probe=11dd2b44ab) | May 12, 2025 |
| Lenovo        | IdeaCentre K330B            | [f68a264591](https://linux-hardware.org/?probe=f68a264591) | May 12, 2025 |
| Dell          | 04YP6J A02                  | [533d3b1997](https://linux-hardware.org/?probe=533d3b1997) | May 10, 2025 |
| GEEKOM        | Mini IT11                   | [421d3aae29](https://linux-hardware.org/?probe=421d3aae29) | May 10, 2025 |
| Dell          | 0GX297                      | [36fa47b8bf](https://linux-hardware.org/?probe=36fa47b8bf) | May 06, 2025 |
| NZXT          | N7 B550                     | [db31437e07](https://linux-hardware.org/?probe=db31437e07) | May 05, 2025 |
| Dell          | 09M8Y8 A01                  | [9c14f33700](https://linux-hardware.org/?probe=9c14f33700) | May 04, 2025 |
| Dell          | 09M8Y8 A01                  | [494ce1a7d0](https://linux-hardware.org/?probe=494ce1a7d0) | May 04, 2025 |
| GEEKOM        | AE8                         | [9158c70300](https://linux-hardware.org/?probe=9158c70300) | May 04, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | [8c7b8e24fc](https://linux-hardware.org/?probe=8c7b8e24fc) | May 03, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [47aa3a80b3](https://linux-hardware.org/?probe=47aa3a80b3) | May 03, 2025 |
| GEEKOM        | AE8                         | [7cdc357a94](https://linux-hardware.org/?probe=7cdc357a94) | May 03, 2025 |
| MSI           | B550M PRO-VDH WIFI          | [1dd652fa65](https://linux-hardware.org/?probe=1dd652fa65) | May 02, 2025 |
| ASRock        | Z68 Extreme3 Gen3           | [ea0bc65f32](https://linux-hardware.org/?probe=ea0bc65f32) | May 02, 2025 |
| Gigabyte      | B760M DS3H AX               | [d2dabf6705](https://linux-hardware.org/?probe=d2dabf6705) | Apr 29, 2025 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [3ec993fcb1](https://linux-hardware.org/?probe=3ec993fcb1) | Apr 28, 2025 |
| Gigabyte      | X570S AORUS ELITE AX        | [69a71355b4](https://linux-hardware.org/?probe=69a71355b4) | Apr 28, 2025 |
| Dell          | 0WMJ54 A01                  | [a3a7e67460](https://linux-hardware.org/?probe=a3a7e67460) | Apr 28, 2025 |
| Gigabyte      | X570S AORUS ELITE AX        | [9adcab1856](https://linux-hardware.org/?probe=9adcab1856) | Apr 27, 2025 |
| Clientron ... | L700                        | [eed16cfff6](https://linux-hardware.org/?probe=eed16cfff6) | Apr 27, 2025 |
| ASUSTek       | PRIME A520M-K               | [3e459dab89](https://linux-hardware.org/?probe=3e459dab89) | Apr 25, 2025 |
| HP            | 0B4Ch D                     | [dd487cf2a9](https://linux-hardware.org/?probe=dd487cf2a9) | Apr 25, 2025 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9ddbf43336](https://linux-hardware.org/?probe=9ddbf43336) | Apr 24, 2025 |
| MSI           | PRO B550M-VC WIFI           | [a4ffee729b](https://linux-hardware.org/?probe=a4ffee729b) | Apr 24, 2025 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c64b2890b9](https://linux-hardware.org/?probe=c64b2890b9) | Apr 19, 2025 |
| HP            | 0B4Ch D                     | [3cf36ba352](https://linux-hardware.org/?probe=3cf36ba352) | Apr 17, 2025 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [50069c6280](https://linux-hardware.org/?probe=50069c6280) | Apr 17, 2025 |
| ASRock        | B85 Pro4                    | [6cea1e7a20](https://linux-hardware.org/?probe=6cea1e7a20) | Apr 16, 2025 |
| ASRock        | B85 Pro4                    | [824c2a3efb](https://linux-hardware.org/?probe=824c2a3efb) | Apr 16, 2025 |
| ASRock        | A320M-HDV R4.0              | [5f5a576b99](https://linux-hardware.org/?probe=5f5a576b99) | Apr 16, 2025 |
| Lenovo        | ThinkStation S20 4105J6G    | [dcca17605e](https://linux-hardware.org/?probe=dcca17605e) | Apr 15, 2025 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [63e7cb0712](https://linux-hardware.org/?probe=63e7cb0712) | Apr 15, 2025 |
| Dell          | 0WWJRX A00                  | [5cb44e756c](https://linux-hardware.org/?probe=5cb44e756c) | Apr 14, 2025 |
| Dell          | 0WWJRX A00                  | [9e0233cc61](https://linux-hardware.org/?probe=9e0233cc61) | Apr 14, 2025 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ddb0b76533](https://linux-hardware.org/?probe=ddb0b76533) | Apr 14, 2025 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7522f8f475](https://linux-hardware.org/?probe=7522f8f475) | Apr 14, 2025 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [944fb85015](https://linux-hardware.org/?probe=944fb85015) | Apr 13, 2025 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [cc4bab3b31](https://linux-hardware.org/?probe=cc4bab3b31) | Apr 13, 2025 |
| Biostar       | H310MHC2                    | [1ab3c7b926](https://linux-hardware.org/?probe=1ab3c7b926) | Apr 08, 2025 |
| MSI           | C847MS-E33                  | [46cd07a997](https://linux-hardware.org/?probe=46cd07a997) | Apr 07, 2025 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [719ad29e5f](https://linux-hardware.org/?probe=719ad29e5f) | Apr 03, 2025 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [ca0dcab902](https://linux-hardware.org/?probe=ca0dcab902) | Apr 02, 2025 |
| ASUSTek       | P7P55D LE                   | [a5bf5753af](https://linux-hardware.org/?probe=a5bf5753af) | Apr 02, 2025 |
| MSI           | B760 GAMING PLUS WIFI       | [73732a2f7c](https://linux-hardware.org/?probe=73732a2f7c) | Mar 30, 2025 |
| Gigabyte      | B450M DS3H V2               | [8699e5c8bf](https://linux-hardware.org/?probe=8699e5c8bf) | Mar 29, 2025 |
| Lenovo        | SHARKBAY 31900003 STD       | [b767cf4f14](https://linux-hardware.org/?probe=b767cf4f14) | Mar 29, 2025 |
| HP            | 1497                        | [a6252a2fea](https://linux-hardware.org/?probe=a6252a2fea) | Mar 28, 2025 |
| ASUSTek       | M4A88T-M/USB3               | [6c2e466d8e](https://linux-hardware.org/?probe=6c2e466d8e) | Mar 27, 2025 |
| ASUSTek       | P8H67-M PRO                 | [1686a17e4a](https://linux-hardware.org/?probe=1686a17e4a) | Mar 27, 2025 |
| ASUSTek       | P8H67-M PRO                 | [e7b070821e](https://linux-hardware.org/?probe=e7b070821e) | Mar 27, 2025 |
| ASRock        | B250M Pro4                  | [d80d521a9d](https://linux-hardware.org/?probe=d80d521a9d) | Mar 25, 2025 |
| ECS           | A780GM-A                    | [12d6f63d69](https://linux-hardware.org/?probe=12d6f63d69) | Mar 24, 2025 |
| ECS           | A780GM-A                    | [036a7b9176](https://linux-hardware.org/?probe=036a7b9176) | Mar 24, 2025 |
| Dell          | 0Y2MRG A00                  | [d43df1600f](https://linux-hardware.org/?probe=d43df1600f) | Mar 21, 2025 |
| ASUSTek       | P8H61-M LX3 PLUS            | [c419030a03](https://linux-hardware.org/?probe=c419030a03) | Mar 18, 2025 |
| ASRock        | H110M-HG4                   | [33b8554985](https://linux-hardware.org/?probe=33b8554985) | Mar 18, 2025 |
| Dell          | 0Y2MRG A00                  | [1cb24fc1b0](https://linux-hardware.org/?probe=1cb24fc1b0) | Mar 18, 2025 |
| MSI           | B550-A PRO                  | [a3314aa5b6](https://linux-hardware.org/?probe=a3314aa5b6) | Mar 15, 2025 |
| Dell          | 0TP406                      | [2b332802b6](https://linux-hardware.org/?probe=2b332802b6) | Mar 14, 2025 |
| ASUSTek       | P5B-MX                      | [35cb44c5c5](https://linux-hardware.org/?probe=35cb44c5c5) | Mar 12, 2025 |
| Dell          | 0X4H68 A00                  | [2cc90f7a43](https://linux-hardware.org/?probe=2cc90f7a43) | Mar 10, 2025 |
| Lenovo        | IdeaCentre K330B            | [34aa7baafc](https://linux-hardware.org/?probe=34aa7baafc) | Mar 10, 2025 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [e4731d0c0d](https://linux-hardware.org/?probe=e4731d0c0d) | Mar 05, 2025 |
| Acer          | Aspire GX-781               | [aa719f1093](https://linux-hardware.org/?probe=aa719f1093) | Mar 03, 2025 |
| ASUSTek       | B85M-G                      | [5aee5aae1b](https://linux-hardware.org/?probe=5aee5aae1b) | Feb 28, 2025 |
| ASUSTek       | B85M-G                      | [5c7a810ab7](https://linux-hardware.org/?probe=5c7a810ab7) | Feb 27, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [f810c98a11](https://linux-hardware.org/?probe=f810c98a11) | Feb 26, 2025 |
| HC Technol... | HCAR4000-MI                 | [54e76aa36e](https://linux-hardware.org/?probe=54e76aa36e) | Feb 23, 2025 |
| ASUSTek       | P5Q                         | [2f5cc472e4](https://linux-hardware.org/?probe=2f5cc472e4) | Feb 23, 2025 |
| ASUSTek       | P5Q                         | [dfc1e4f83f](https://linux-hardware.org/?probe=dfc1e4f83f) | Feb 23, 2025 |
| MSI           | B75MA-P45                   | [7474b49f5c](https://linux-hardware.org/?probe=7474b49f5c) | Feb 22, 2025 |
| PELADN        | WI-6                        | [7e0e77a962](https://linux-hardware.org/?probe=7e0e77a962) | Feb 16, 2025 |
| Medion        | MS-7707                     | [6e36b94a5a](https://linux-hardware.org/?probe=6e36b94a5a) | Feb 15, 2025 |
| Dell          | 0X9M3X A04                  | [394e03fa0e](https://linux-hardware.org/?probe=394e03fa0e) | Feb 12, 2025 |
| Gigabyte      | Z77-DS3H                    | [0ee5279781](https://linux-hardware.org/?probe=0ee5279781) | Feb 11, 2025 |
| MSI           | B75MA-P45                   | [491c8852e9](https://linux-hardware.org/?probe=491c8852e9) | Feb 10, 2025 |
| Medion        | MS-7707                     | [bd0176f563](https://linux-hardware.org/?probe=bd0176f563) | Feb 09, 2025 |
| ASRock        | A320M-HDV R4.0              | [94bd213028](https://linux-hardware.org/?probe=94bd213028) | Feb 06, 2025 |
| ASRock        | Z390 Phantom Gaming 4/AC    | [b570c6d606](https://linux-hardware.org/?probe=b570c6d606) | Jan 31, 2025 |
| Foxconn       | ETON                        | [19ce5c04c2](https://linux-hardware.org/?probe=19ce5c04c2) | Jan 31, 2025 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | [70479fdb19](https://linux-hardware.org/?probe=70479fdb19) | Jan 29, 2025 |
| Lenovo        | IdeaCentre K330B            | [9253c594fc](https://linux-hardware.org/?probe=9253c594fc) | Jan 29, 2025 |
| PELADN        | WI-6                        | [bb87fb47ce](https://linux-hardware.org/?probe=bb87fb47ce) | Jan 26, 2025 |
| ASRock        | 970 Pro3 R2.0               | [ec028380c5](https://linux-hardware.org/?probe=ec028380c5) | Jan 25, 2025 |
| ASRock        | 970 Pro3 R2.0               | [d5242ec865](https://linux-hardware.org/?probe=d5242ec865) | Jan 25, 2025 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a700fbd0ed](https://linux-hardware.org/?probe=a700fbd0ed) | Jan 25, 2025 |
| ASUSTek       | TUF B450M-PRO GAMING        | [8aad6328bf](https://linux-hardware.org/?probe=8aad6328bf) | Jan 25, 2025 |
| PELADN        | WI-6                        | [c97c817643](https://linux-hardware.org/?probe=c97c817643) | Jan 23, 2025 |
| ASUSTek       | PRIME Z390-P                | [2b5ea4e149](https://linux-hardware.org/?probe=2b5ea4e149) | Jan 20, 2025 |
| HP            | 82B4                        | [b97dc50326](https://linux-hardware.org/?probe=b97dc50326) | Jan 19, 2025 |
| Dell          | 0HHV7N A00                  | [bdf33bafff](https://linux-hardware.org/?probe=bdf33bafff) | Jan 19, 2025 |
| HP            | 1587h                       | [74cc78a058](https://linux-hardware.org/?probe=74cc78a058) | Jan 18, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cb87984b34](https://linux-hardware.org/?probe=cb87984b34) | Jan 18, 2025 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [2024201637](https://linux-hardware.org/?probe=2024201637) | Jan 15, 2025 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [fac00c4aaa](https://linux-hardware.org/?probe=fac00c4aaa) | Jan 13, 2025 |
| Acer          | Aspire M3400                | [f6d8d35f2d](https://linux-hardware.org/?probe=f6d8d35f2d) | Jan 13, 2025 |
| HP            | 1587h                       | [512209ee9a](https://linux-hardware.org/?probe=512209ee9a) | Jan 12, 2025 |
| Acer          | Aspire X1420                | [80abd0c20b](https://linux-hardware.org/?probe=80abd0c20b) | Jan 12, 2025 |
| ASUSTek       | PRIME X570-PRO              | [93d0ec3ead](https://linux-hardware.org/?probe=93d0ec3ead) | Jan 07, 2025 |
| Pegatron      | 2AD5                        | [83c81f49c1](https://linux-hardware.org/?probe=83c81f49c1) | Jan 07, 2025 |
| PELADN        | WI-6                        | [4eb39eba20](https://linux-hardware.org/?probe=4eb39eba20) | Jan 06, 2025 |
| PELADN        | WI-6                        | [537a11ae44](https://linux-hardware.org/?probe=537a11ae44) | Jan 06, 2025 |
| ASUSTek       | PRIME Z390-P                | [d6e8f1ee6c](https://linux-hardware.org/?probe=d6e8f1ee6c) | Jan 04, 2025 |
| MSI           | B450 TOMAHAWK MAX           | [88d10a1126](https://linux-hardware.org/?probe=88d10a1126) | Jan 04, 2025 |
| PELADN        | WI-6                        | [ed403a09ce](https://linux-hardware.org/?probe=ed403a09ce) | Jan 01, 2025 |
| PELADN        | WI-6                        | [9961c80013](https://linux-hardware.org/?probe=9961c80013) | Dec 31, 2024 |
| PELADN        | WI-6                        | [ad75e2844c](https://linux-hardware.org/?probe=ad75e2844c) | Dec 31, 2024 |
| PELADN        | WI-6                        | [a4d452eb65](https://linux-hardware.org/?probe=a4d452eb65) | Dec 31, 2024 |
| Dell          | 0MWYPT A02                  | [3a7c58054c](https://linux-hardware.org/?probe=3a7c58054c) | Dec 29, 2024 |
| ASUSTek       | PRIME Z390-P                | [f680af729c](https://linux-hardware.org/?probe=f680af729c) | Dec 28, 2024 |
| ASRock        | H110M-HDV R3.0              | [43e003f874](https://linux-hardware.org/?probe=43e003f874) | Dec 22, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8144311954](https://linux-hardware.org/?probe=8144311954) | Dec 22, 2024 |
| HP            | 2820h                       | [64ccd9e1f2](https://linux-hardware.org/?probe=64ccd9e1f2) | Dec 22, 2024 |
| ASUSTek       | PRIME B250M-C               | [ebcaaa33b0](https://linux-hardware.org/?probe=ebcaaa33b0) | Dec 15, 2024 |
| ASUSTek       | PRIME B250M-C               | [787e3a402c](https://linux-hardware.org/?probe=787e3a402c) | Dec 14, 2024 |
| ASUSTek       | H81M-K                      | [4c7c8cc298](https://linux-hardware.org/?probe=4c7c8cc298) | Dec 08, 2024 |
| Gigabyte      | B550M DS3H                  | [146d9d897a](https://linux-hardware.org/?probe=146d9d897a) | Dec 02, 2024 |
| Lenovo        | ThinkCentre M58p 7220AVG    | [9d47a500ed](https://linux-hardware.org/?probe=9d47a500ed) | Dec 01, 2024 |
| ASRock        | B450 Pro4                   | [ca8808db77](https://linux-hardware.org/?probe=ca8808db77) | Nov 29, 2024 |
| ASRock        | B450 Pro4                   | [fb2858b084](https://linux-hardware.org/?probe=fb2858b084) | Nov 28, 2024 |
| PELADN        | WI-6                        | [deec076d09](https://linux-hardware.org/?probe=deec076d09) | Nov 24, 2024 |
| PELADN        | WI-6                        | [f1daf75b91](https://linux-hardware.org/?probe=f1daf75b91) | Nov 24, 2024 |
| ASUSTek       | PRIME Z390-P                | [a087a2818f](https://linux-hardware.org/?probe=a087a2818f) | Nov 18, 2024 |
| Dell          | 00V62H A01                  | [3f6a95ad11](https://linux-hardware.org/?probe=3f6a95ad11) | Nov 18, 2024 |
| Dell          | 073MMW A03                  | [715ccc808c](https://linux-hardware.org/?probe=715ccc808c) | Nov 16, 2024 |
| ASRock        | A320M-HDV R4.0              | [bd75bc63f7](https://linux-hardware.org/?probe=bd75bc63f7) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [7ac1792400](https://linux-hardware.org/?probe=7ac1792400) | Nov 14, 2024 |
| Gigabyte      | A520M S2H                   | [53fa642cd5](https://linux-hardware.org/?probe=53fa642cd5) | Nov 13, 2024 |
| ASUSTek       | PRIME Z390-P                | [acecc3bec2](https://linux-hardware.org/?probe=acecc3bec2) | Nov 09, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [01063d0f9e](https://linux-hardware.org/?probe=01063d0f9e) | Nov 08, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [856f712b05](https://linux-hardware.org/?probe=856f712b05) | Nov 08, 2024 |
| ASUSTek       | P8H67-M                     | [d7ef318b8e](https://linux-hardware.org/?probe=d7ef318b8e) | Nov 06, 2024 |
| Intel         | H110D4-P1                   | [65e304fcef](https://linux-hardware.org/?probe=65e304fcef) | Nov 02, 2024 |
| AZW           | MINI S 10                   | [a76f3d4f56](https://linux-hardware.org/?probe=a76f3d4f56) | Nov 01, 2024 |
| AZW           | MINI S 10                   | [eae99fa9a9](https://linux-hardware.org/?probe=eae99fa9a9) | Nov 01, 2024 |
| HP            | 2820h                       | [940082e5de](https://linux-hardware.org/?probe=940082e5de) | Oct 30, 2024 |
| HP            | 1906                        | [2d314c1b57](https://linux-hardware.org/?probe=2d314c1b57) | Oct 28, 2024 |
| ASRock        | A320M-HDV                   | [7ae06e5667](https://linux-hardware.org/?probe=7ae06e5667) | Oct 27, 2024 |
| Gigabyte      | Z77X-D3H                    | [91631ac2c3](https://linux-hardware.org/?probe=91631ac2c3) | Oct 27, 2024 |
| HP            | 2AFB                        | [c7b44337e2](https://linux-hardware.org/?probe=c7b44337e2) | Oct 23, 2024 |
| HP            | 2AFB                        | [cedecd78de](https://linux-hardware.org/?probe=cedecd78de) | Oct 23, 2024 |
| ASUSTek       | Crosshair IV Formula        | [50d12895aa](https://linux-hardware.org/?probe=50d12895aa) | Oct 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [2c7a8f6c86](https://linux-hardware.org/?probe=2c7a8f6c86) | Oct 17, 2024 |
| PELADN        | WI-6                        | [475cbc4d32](https://linux-hardware.org/?probe=475cbc4d32) | Oct 12, 2024 |
| PELADN        | WI-6                        | [26845b5304](https://linux-hardware.org/?probe=26845b5304) | Oct 12, 2024 |
| PELADN        | WI-6                        | [0531287d03](https://linux-hardware.org/?probe=0531287d03) | Oct 12, 2024 |
| PELADN        | WI-6                        | [ab803d1e89](https://linux-hardware.org/?probe=ab803d1e89) | Oct 12, 2024 |
| Medion        | TJ4125                      | [a371c066fd](https://linux-hardware.org/?probe=a371c066fd) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | [31774f82cc](https://linux-hardware.org/?probe=31774f82cc) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | [f42bacdfa7](https://linux-hardware.org/?probe=f42bacdfa7) | Oct 11, 2024 |
| Medion        | TJ4125                      | [24e446e7a7](https://linux-hardware.org/?probe=24e446e7a7) | Oct 08, 2024 |
| MSI           | PRO B550M-P GEN3            | [f216dafbba](https://linux-hardware.org/?probe=f216dafbba) | Oct 04, 2024 |
| ASUSTek       | PRIME X570-PRO              | [bc7fdf7279](https://linux-hardware.org/?probe=bc7fdf7279) | Oct 01, 2024 |
| Gigabyte      | Z77X-D3H                    | [e9bbaa808d](https://linux-hardware.org/?probe=e9bbaa808d) | Sep 30, 2024 |
| Gigabyte      | Z77X-D3H                    | [51fe2ae08f](https://linux-hardware.org/?probe=51fe2ae08f) | Sep 29, 2024 |
| ASRock        | A320M-HDV                   | [23c6bbe37a](https://linux-hardware.org/?probe=23c6bbe37a) | Sep 25, 2024 |
| ASUSTek       | P5G41T-M LE                 | [d2315eef29](https://linux-hardware.org/?probe=d2315eef29) | Sep 22, 2024 |
| Biostar       | P31-A7                      | [8f249ff212](https://linux-hardware.org/?probe=8f249ff212) | Sep 22, 2024 |
| MSI           | B350 TOMAHAWK               | [f87173b8b2](https://linux-hardware.org/?probe=f87173b8b2) | Sep 20, 2024 |
| Dell          | 0T568R A00                  | [1e475fbe85](https://linux-hardware.org/?probe=1e475fbe85) | Sep 18, 2024 |
| ASRock        | B650M Pro RS WiFi           | [8f68843f40](https://linux-hardware.org/?probe=8f68843f40) | Sep 18, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [47ffb7c0c0](https://linux-hardware.org/?probe=47ffb7c0c0) | Sep 11, 2024 |
| PELADN        | WI-6                        | [1a20712dde](https://linux-hardware.org/?probe=1a20712dde) | Sep 08, 2024 |
| PELADN        | WI-6                        | [c250dba9ae](https://linux-hardware.org/?probe=c250dba9ae) | Sep 07, 2024 |
| MSI           | A68HM GRENADE               | [d823f74970](https://linux-hardware.org/?probe=d823f74970) | Aug 29, 2024 |
| MSI           | A68HM GRENADE               | [10f8a9b965](https://linux-hardware.org/?probe=10f8a9b965) | Aug 29, 2024 |
| ASUSTek       | G11CD-K                     | [97151fcf68](https://linux-hardware.org/?probe=97151fcf68) | Aug 27, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [c771260335](https://linux-hardware.org/?probe=c771260335) | Aug 19, 2024 |
| PELADN        | WI-6                        | [862128760a](https://linux-hardware.org/?probe=862128760a) | Aug 15, 2024 |
| Shenzhen M... | DNBIB                       | [b96a88e34c](https://linux-hardware.org/?probe=b96a88e34c) | Aug 13, 2024 |
| PELADN        | WI-6                        | [e23677d993](https://linux-hardware.org/?probe=e23677d993) | Aug 13, 2024 |
| ASRock        | X370 Killer SLI             | [e2b748b24a](https://linux-hardware.org/?probe=e2b748b24a) | Aug 11, 2024 |
| MACHINIST     | X99 PR9                     | [fd08f80e3b](https://linux-hardware.org/?probe=fd08f80e3b) | Aug 10, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | [ac8d4298ad](https://linux-hardware.org/?probe=ac8d4298ad) | Aug 06, 2024 |
| Gigabyte      | B760M DS3H DDR4             | [f65ee4168b](https://linux-hardware.org/?probe=f65ee4168b) | Aug 06, 2024 |
| GEEKOM        | A7                          | [a642de18b4](https://linux-hardware.org/?probe=a642de18b4) | Aug 03, 2024 |
| GEEKOM        | A7                          | [5e4d479deb](https://linux-hardware.org/?probe=5e4d479deb) | Aug 03, 2024 |
| MSI           | B560M PRO-E                 | [e822834efe](https://linux-hardware.org/?probe=e822834efe) | Jul 31, 2024 |
| ASRock        | Z68 Extreme3 Gen3           | [a7c539d689](https://linux-hardware.org/?probe=a7c539d689) | Jul 27, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [9a733fe6d3](https://linux-hardware.org/?probe=9a733fe6d3) | Jul 26, 2024 |
| Medion        | TJ4125                      | [8a4a376199](https://linux-hardware.org/?probe=8a4a376199) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [5261c040c3](https://linux-hardware.org/?probe=5261c040c3) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [9f6655b549](https://linux-hardware.org/?probe=9f6655b549) | Jul 25, 2024 |
| Unknown       | Unknown                     | [9f21efbdc8](https://linux-hardware.org/?probe=9f21efbdc8) | Jul 24, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [c031d1b6ab](https://linux-hardware.org/?probe=c031d1b6ab) | Jul 22, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [ae9443b715](https://linux-hardware.org/?probe=ae9443b715) | Jul 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0300a1940](https://linux-hardware.org/?probe=a0300a1940) | Jul 21, 2024 |
| Medion        | TJ4125                      | [50af4fbfc4](https://linux-hardware.org/?probe=50af4fbfc4) | Jul 20, 2024 |
| Intel         | H81                         | [22d5bf41a9](https://linux-hardware.org/?probe=22d5bf41a9) | Jul 17, 2024 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [ae5c5e7f74](https://linux-hardware.org/?probe=ae5c5e7f74) | Jul 16, 2024 |
| ASRock        | H270M Pro4                  | [0098f75d27](https://linux-hardware.org/?probe=0098f75d27) | Jul 16, 2024 |
| PELADN        | WI-6                        | [5bf72a6fb4](https://linux-hardware.org/?probe=5bf72a6fb4) | Jul 07, 2024 |
| Medion        | TJ4125                      | [d6eea34c91](https://linux-hardware.org/?probe=d6eea34c91) | Jul 06, 2024 |
| PELADN        | WI-6                        | [bf8f9bc3b3](https://linux-hardware.org/?probe=bf8f9bc3b3) | Jul 06, 2024 |
| Medion        | TJ4125                      | [01eef112d6](https://linux-hardware.org/?probe=01eef112d6) | Jul 06, 2024 |
| Intel         | H61                         | [0373caa5cc](https://linux-hardware.org/?probe=0373caa5cc) | Jun 28, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [4070fa9d3e](https://linux-hardware.org/?probe=4070fa9d3e) | Jun 28, 2024 |
| ASUSTek       | PRIME N100I-D D4            | [3ef6295470](https://linux-hardware.org/?probe=3ef6295470) | Jun 27, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [e58ec4ab82](https://linux-hardware.org/?probe=e58ec4ab82) | Jun 27, 2024 |
| Dell          | 0T568R A00                  | [be28ff899b](https://linux-hardware.org/?probe=be28ff899b) | Jun 25, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31708d14fb](https://linux-hardware.org/?probe=31708d14fb) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [286891ce23](https://linux-hardware.org/?probe=286891ce23) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [43ddc59145](https://linux-hardware.org/?probe=43ddc59145) | Jun 22, 2024 |
| Dell          | 048DY8 A01                  | [b044c0600b](https://linux-hardware.org/?probe=b044c0600b) | Jun 22, 2024 |
| Lenovo        | ThinkCentre M71e 3133A8S    | [e73d8477a0](https://linux-hardware.org/?probe=e73d8477a0) | Jun 21, 2024 |
| ASUSTek       | STRIX H270F GAMING          | [fcc5c05273](https://linux-hardware.org/?probe=fcc5c05273) | Jun 20, 2024 |
| HP            | 3397                        | [6156808fc9](https://linux-hardware.org/?probe=6156808fc9) | Jun 20, 2024 |
| HP            | 3397                        | [28f359e68a](https://linux-hardware.org/?probe=28f359e68a) | Jun 20, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [86fb4cb7e8](https://linux-hardware.org/?probe=86fb4cb7e8) | Jun 18, 2024 |
| ASUSTek       | P7P55 LX                    | [a8754caf68](https://linux-hardware.org/?probe=a8754caf68) | Jun 17, 2024 |
| Gigabyte      | B650 GAMING X AX            | [cb0f2121d5](https://linux-hardware.org/?probe=cb0f2121d5) | Jun 14, 2024 |
| Shenzhen M... | F7BRC                       | [c5fa0bb59b](https://linux-hardware.org/?probe=c5fa0bb59b) | Jun 10, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [55b98015cb](https://linux-hardware.org/?probe=55b98015cb) | Jun 06, 2024 |
| MSI           | A320M-A PRO MAX             | [ee19bbcc37](https://linux-hardware.org/?probe=ee19bbcc37) | May 19, 2024 |
| ASUSTek       | P8H61-M                     | [451e286c21](https://linux-hardware.org/?probe=451e286c21) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | [2736095341](https://linux-hardware.org/?probe=2736095341) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | [9ae2bfab73](https://linux-hardware.org/?probe=9ae2bfab73) | May 18, 2024 |
| Gigabyte      | Q87M-D2H                    | [57e0f5eb29](https://linux-hardware.org/?probe=57e0f5eb29) | May 13, 2024 |
| PELADN        | WI-6                        | [4cabf19872](https://linux-hardware.org/?probe=4cabf19872) | May 13, 2024 |
| ASUSTek       | PRIME B250M-C               | [1f7c62ca20](https://linux-hardware.org/?probe=1f7c62ca20) | May 11, 2024 |
| ASUSTek       | P5Q SE2                     | [0a49b531a8](https://linux-hardware.org/?probe=0a49b531a8) | May 10, 2024 |
| ASUSTek       | PRIME B250M-C               | [0a6d61d9f6](https://linux-hardware.org/?probe=0a6d61d9f6) | May 09, 2024 |
| ASUSTek       | P5Q SE2                     | [cf126cd087](https://linux-hardware.org/?probe=cf126cd087) | May 08, 2024 |
| PELADN        | WI-6                        | [73069ab9f5](https://linux-hardware.org/?probe=73069ab9f5) | May 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [9176ad5eb1](https://linux-hardware.org/?probe=9176ad5eb1) | May 04, 2024 |
| ASUSTek       | M5A99X EVO                  | [9d375acdb0](https://linux-hardware.org/?probe=9d375acdb0) | May 03, 2024 |
| ASUSTek       | H81-PLUS                    | [efe7c01899](https://linux-hardware.org/?probe=efe7c01899) | May 01, 2024 |
| ASUSTek       | H81-PLUS                    | [512660cdbc](https://linux-hardware.org/?probe=512660cdbc) | May 01, 2024 |
| Medion        | TJ4125                      | [5107c56945](https://linux-hardware.org/?probe=5107c56945) | Apr 29, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [a52ce5dea5](https://linux-hardware.org/?probe=a52ce5dea5) | Apr 27, 2024 |
| Pegatron      | 2A94                        | [3673d4e290](https://linux-hardware.org/?probe=3673d4e290) | Apr 25, 2024 |
| HP            | 8876 11                     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| AMI           | Intel                       | [7f5a03f6a3](https://linux-hardware.org/?probe=7f5a03f6a3) | Apr 23, 2024 |
| Unknown       | Unknown                     | [2be166cff9](https://linux-hardware.org/?probe=2be166cff9) | Apr 22, 2024 |
| Unknown       | Unknown                     | [9bce7f48fb](https://linux-hardware.org/?probe=9bce7f48fb) | Apr 22, 2024 |
| ASUSTek       | PRIME B250M-C               | [46d23f3585](https://linux-hardware.org/?probe=46d23f3585) | Apr 21, 2024 |
| HP            | 1495                        | [0eb85fb716](https://linux-hardware.org/?probe=0eb85fb716) | Apr 20, 2024 |
| HP            | 1495                        | [f3b383fe91](https://linux-hardware.org/?probe=f3b383fe91) | Apr 20, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7cfe6d651b](https://linux-hardware.org/?probe=7cfe6d651b) | Apr 18, 2024 |
| Medion        | TJ4125                      | [283e08c36b](https://linux-hardware.org/?probe=283e08c36b) | Apr 18, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [0bf4de97cf](https://linux-hardware.org/?probe=0bf4de97cf) | Apr 17, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [a996f7b2e9](https://linux-hardware.org/?probe=a996f7b2e9) | Apr 12, 2024 |
| Gigabyte      | Q87M-D2H                    | [3d748511c8](https://linux-hardware.org/?probe=3d748511c8) | Apr 08, 2024 |
| PELADN        | WI-6                        | [16b9fe150d](https://linux-hardware.org/?probe=16b9fe150d) | Apr 07, 2024 |
| PELADN        | WI-6                        | [e3e158c12c](https://linux-hardware.org/?probe=e3e158c12c) | Apr 05, 2024 |
| Medion        | TJ4125                      | [9d159ef9de](https://linux-hardware.org/?probe=9d159ef9de) | Apr 04, 2024 |
| Medion        | TJ4125                      | [3133554055](https://linux-hardware.org/?probe=3133554055) | Apr 04, 2024 |
| ASUSTek       | PRIME Z370-P II             | [e075d81601](https://linux-hardware.org/?probe=e075d81601) | Apr 04, 2024 |
| Quanta        | 2AC7 011                    | [ee7988e621](https://linux-hardware.org/?probe=ee7988e621) | Mar 29, 2024 |
| ASRock        | J3455-ITX                   | [a0f0f8fc52](https://linux-hardware.org/?probe=a0f0f8fc52) | Mar 26, 2024 |
| Gigabyte      | Q87M-D2H                    | [14cbf1cf7d](https://linux-hardware.org/?probe=14cbf1cf7d) | Mar 25, 2024 |
| PELADN        | WI-6                        | [76b4088a9e](https://linux-hardware.org/?probe=76b4088a9e) | Mar 23, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [07889f98fc](https://linux-hardware.org/?probe=07889f98fc) | Mar 22, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [dfa8ff45b7](https://linux-hardware.org/?probe=dfa8ff45b7) | Mar 21, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [5c0de1313b](https://linux-hardware.org/?probe=5c0de1313b) | Mar 21, 2024 |
| Gigabyte      | Z170-HD3P-CF                | [230ed44a0f](https://linux-hardware.org/?probe=230ed44a0f) | Mar 18, 2024 |
| ASUSTek       | PRIME B450M-A II            | [e5bf526b80](https://linux-hardware.org/?probe=e5bf526b80) | Mar 13, 2024 |
| Unknown       | G31T-M7                     | [1bf4ded8e3](https://linux-hardware.org/?probe=1bf4ded8e3) | Mar 09, 2024 |
| Gigabyte      | A320M-H-CF                  | [954a5c5822](https://linux-hardware.org/?probe=954a5c5822) | Feb 20, 2024 |
| Gigabyte      | Q87M-D2H                    | [54eb218a18](https://linux-hardware.org/?probe=54eb218a18) | Feb 20, 2024 |
| MSI           | Z370-A PRO                  | [3715fac015](https://linux-hardware.org/?probe=3715fac015) | Feb 20, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [29958a239f](https://linux-hardware.org/?probe=29958a239f) | Feb 19, 2024 |
| MSI           | Z170A SLI PLUS              | [5dff40d28c](https://linux-hardware.org/?probe=5dff40d28c) | Feb 19, 2024 |
| ASRock        | B760M Pro RS/D4             | [f0f36877ea](https://linux-hardware.org/?probe=f0f36877ea) | Feb 19, 2024 |
| Gigabyte      | Q87M-D2H                    | [741292eb40](https://linux-hardware.org/?probe=741292eb40) | Feb 18, 2024 |
| Gigabyte      | B560M D3H                   | [dd40636963](https://linux-hardware.org/?probe=dd40636963) | Feb 17, 2024 |
| Inventec      | VXC Class A02               | [f5467a7fcc](https://linux-hardware.org/?probe=f5467a7fcc) | Feb 12, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [b342dc33d2](https://linux-hardware.org/?probe=b342dc33d2) | Feb 11, 2024 |
| Inventec      | VXC Class A02               | [cd813cc599](https://linux-hardware.org/?probe=cd813cc599) | Feb 10, 2024 |
| Intel         | B75                         | [23e52718b5](https://linux-hardware.org/?probe=23e52718b5) | Feb 03, 2024 |
| HP            | 212B                        | [ada937137f](https://linux-hardware.org/?probe=ada937137f) | Feb 03, 2024 |
| Gigabyte      | Q87M-D2H                    | [32b5d46627](https://linux-hardware.org/?probe=32b5d46627) | Feb 02, 2024 |
| Gigabyte      | Q87M-D2H                    | [4c5e48c75f](https://linux-hardware.org/?probe=4c5e48c75f) | Feb 02, 2024 |
| Inventec      | DQ Class A02                | [4cb447dae2](https://linux-hardware.org/?probe=4cb447dae2) | Feb 02, 2024 |
| Gigabyte      | Q87M-D2H                    | [78ef1fbd6c](https://linux-hardware.org/?probe=78ef1fbd6c) | Jan 31, 2024 |
| Medion        | TJ4125                      | [2705de4986](https://linux-hardware.org/?probe=2705de4986) | Jan 31, 2024 |
| MSI           | MS-7345                     | [3453f85c21](https://linux-hardware.org/?probe=3453f85c21) | Jan 30, 2024 |
| MSI           | MAG B560 TORPEDO            | [429541ce17](https://linux-hardware.org/?probe=429541ce17) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c7a52fe756](https://linux-hardware.org/?probe=c7a52fe756) | Jan 29, 2024 |
| HP            | 805D                        | [81113f9b0d](https://linux-hardware.org/?probe=81113f9b0d) | Jan 29, 2024 |
| ASUSTek       | PRIME X670-P                | [08b5799cfd](https://linux-hardware.org/?probe=08b5799cfd) | Jan 27, 2024 |
| MSI           | MAG B560 TORPEDO            | [30954e841f](https://linux-hardware.org/?probe=30954e841f) | Jan 26, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [56bd222ae5](https://linux-hardware.org/?probe=56bd222ae5) | Jan 24, 2024 |
| Gigabyte      | B450 AORUS M                | [ed52617ade](https://linux-hardware.org/?probe=ed52617ade) | Jan 23, 2024 |
| ASRock        | Z690 Pro RS                 | [4083a31da9](https://linux-hardware.org/?probe=4083a31da9) | Jan 21, 2024 |
| ASRock        | X670E Taichi Carrara        | [52318f5ae6](https://linux-hardware.org/?probe=52318f5ae6) | Jan 20, 2024 |
| ASUSTek       | P7P55D-E                    | [bb8785aa08](https://linux-hardware.org/?probe=bb8785aa08) | Jan 15, 2024 |
| MSI           | MEG X670E ACE               | [08ee758712](https://linux-hardware.org/?probe=08ee758712) | Jan 15, 2024 |
| ASRock        | Z97 Pro4                    | [e3ef5ae05b](https://linux-hardware.org/?probe=e3ef5ae05b) | Jan 14, 2024 |
| Gigabyte      | GA-78LMT-S2P 78LMT2         | [b81e3342c6](https://linux-hardware.org/?probe=b81e3342c6) | Jan 13, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [70dedc5c9d](https://linux-hardware.org/?probe=70dedc5c9d) | Jan 12, 2024 |
| ASUSTek       | P5G41T-M LX3                | [a358114f21](https://linux-hardware.org/?probe=a358114f21) | Jan 12, 2024 |
| Gigabyte      | B450 AORUS M                | [6b5cc546b5](https://linux-hardware.org/?probe=6b5cc546b5) | Jan 12, 2024 |
| MSI           | Z390-A PRO                  | [538119eb86](https://linux-hardware.org/?probe=538119eb86) | Jan 11, 2024 |
| MSI           | B350M BAZOOKA               | [fab33560f3](https://linux-hardware.org/?probe=fab33560f3) | Jan 10, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [c9096376d8](https://linux-hardware.org/?probe=c9096376d8) | Jan 09, 2024 |
| MSI           | B550-A PRO                  | [e2e58f59b7](https://linux-hardware.org/?probe=e2e58f59b7) | Jan 06, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| Medion        | TJ4125                      | [ca0e4105c2](https://linux-hardware.org/?probe=ca0e4105c2) | Jan 02, 2024 |
| Gigabyte      | Q87M-D2H                    | [26f77fa950](https://linux-hardware.org/?probe=26f77fa950) | Jan 02, 2024 |
| ASUSTek       | H110M-A/M.2                 | [9e622b4006](https://linux-hardware.org/?probe=9e622b4006) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [0f440edfb5](https://linux-hardware.org/?probe=0f440edfb5) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [edbe61f4fa](https://linux-hardware.org/?probe=edbe61f4fa) | Dec 31, 2023 |
| Dell          | 0RW199                      | [906719d239](https://linux-hardware.org/?probe=906719d239) | Dec 27, 2023 |
| HP            | 090Ch                       | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [4b2ed8b976](https://linux-hardware.org/?probe=4b2ed8b976) | Dec 23, 2023 |
| ASUSTek       | X99-A II                    | [37e4430c0e](https://linux-hardware.org/?probe=37e4430c0e) | Dec 23, 2023 |
| ASRock        | Z97 Pro4                    | [f8e2df67b1](https://linux-hardware.org/?probe=f8e2df67b1) | Dec 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [db8c00daf3](https://linux-hardware.org/?probe=db8c00daf3) | Dec 22, 2023 |
| Lenovo        | 317C NOK                    | [87064e6d98](https://linux-hardware.org/?probe=87064e6d98) | Dec 20, 2023 |
| Medion        | TJ4125                      | [8fce958467](https://linux-hardware.org/?probe=8fce958467) | Dec 20, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [a1f4076586](https://linux-hardware.org/?probe=a1f4076586) | Dec 19, 2023 |
| Medion        | TJ4125                      | [c7eeb77279](https://linux-hardware.org/?probe=c7eeb77279) | Dec 18, 2023 |
| Gigabyte      | Q87M-D2H                    | [378b82ce2f](https://linux-hardware.org/?probe=378b82ce2f) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | [e7f9b37ee3](https://linux-hardware.org/?probe=e7f9b37ee3) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | [935f688c90](https://linux-hardware.org/?probe=935f688c90) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | [f53d129b3d](https://linux-hardware.org/?probe=f53d129b3d) | Dec 17, 2023 |
| Medion        | TJ4125                      | [7556d73046](https://linux-hardware.org/?probe=7556d73046) | Dec 17, 2023 |
| Gigabyte      | A520M S2H                   | [0b4a9d3a4e](https://linux-hardware.org/?probe=0b4a9d3a4e) | Dec 16, 2023 |
| Acer          | Veriton M4630G V:1.0        | [91ec51ebf5](https://linux-hardware.org/?probe=91ec51ebf5) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | [3184d3c38b](https://linux-hardware.org/?probe=3184d3c38b) | Dec 11, 2023 |
| ASRock        | H310M-STX                   | [205a5c1696](https://linux-hardware.org/?probe=205a5c1696) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | [71de71e3f4](https://linux-hardware.org/?probe=71de71e3f4) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | [64b0038221](https://linux-hardware.org/?probe=64b0038221) | Dec 10, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4525b7e30c](https://linux-hardware.org/?probe=4525b7e30c) | Dec 09, 2023 |
| ASUSTek       | P5G41T-M LX3                | [42a7acfe4b](https://linux-hardware.org/?probe=42a7acfe4b) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [b553ec2266](https://linux-hardware.org/?probe=b553ec2266) | Dec 08, 2023 |
| ASUSTek       | Rampage III Extreme         | [d4d934c9be](https://linux-hardware.org/?probe=d4d934c9be) | Dec 08, 2023 |
| Unknown       | Unknown                     | [7144bda606](https://linux-hardware.org/?probe=7144bda606) | Dec 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6fca6c7335](https://linux-hardware.org/?probe=6fca6c7335) | Dec 03, 2023 |
| ASUSTek       | PRIME B450M-K               | [9fa48c41da](https://linux-hardware.org/?probe=9fa48c41da) | Nov 27, 2023 |
| Gigabyte      | B560M D3H                   | [8a894da286](https://linux-hardware.org/?probe=8a894da286) | Nov 26, 2023 |
| Shenzhen M... | F7BRC                       | [9ff2c76737](https://linux-hardware.org/?probe=9ff2c76737) | Nov 26, 2023 |
| MSI           | MAG B760M MORTAR WIFI DD... | [b11fcf42c2](https://linux-hardware.org/?probe=b11fcf42c2) | Nov 25, 2023 |
| Medion        | TJ4125                      | [512206df27](https://linux-hardware.org/?probe=512206df27) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [81d1db42ea](https://linux-hardware.org/?probe=81d1db42ea) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | [af55920808](https://linux-hardware.org/?probe=af55920808) | Nov 23, 2023 |
| MSI           | PRO Z790-A WIFI             | [b564a39ed5](https://linux-hardware.org/?probe=b564a39ed5) | Nov 22, 2023 |
| Dell          | 0Y2YM6 A00                  | [ce96501574](https://linux-hardware.org/?probe=ce96501574) | Nov 22, 2023 |
| Gigabyte      | Q87M-D2H                    | [a0f12099c5](https://linux-hardware.org/?probe=a0f12099c5) | Nov 22, 2023 |
| Soyo          | SY-N3150L Quad              | [7fd72fcced](https://linux-hardware.org/?probe=7fd72fcced) | Nov 21, 2023 |
| Gigabyte      | Q87M-D2H                    | [085623428e](https://linux-hardware.org/?probe=085623428e) | Nov 19, 2023 |
| Acer          | Aspire X3400                | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| Acer          | Aspire X3400                | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| ASUSTek       | P5G41T-M LX3                | [e65cf40bcb](https://linux-hardware.org/?probe=e65cf40bcb) | Nov 19, 2023 |
| HP            | 8265                        | [d3f5c1d6ce](https://linux-hardware.org/?probe=d3f5c1d6ce) | Nov 15, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [c4b486ecb1](https://linux-hardware.org/?probe=c4b486ecb1) | Nov 13, 2023 |
| Medion        | TJ4125                      | [1e0f7cdf34](https://linux-hardware.org/?probe=1e0f7cdf34) | Nov 12, 2023 |
| Medion        | TJ4125                      | [ab37177769](https://linux-hardware.org/?probe=ab37177769) | Nov 10, 2023 |
| Gigabyte      | Q87M-D2H                    | [80bba409c5](https://linux-hardware.org/?probe=80bba409c5) | Nov 10, 2023 |
| Dell          | 0HH807                      | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| ASUSTek       | P5G41T-M LX3                | [8d5332d643](https://linux-hardware.org/?probe=8d5332d643) | Nov 07, 2023 |
| MSI           | B75MA-P45                   | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [62a888f71c](https://linux-hardware.org/?probe=62a888f71c) | Nov 05, 2023 |
| Medion        | TJ4125                      | [65a059325e](https://linux-hardware.org/?probe=65a059325e) | Nov 05, 2023 |
| Gigabyte      | MZBSWAP-K4                  | [ef6c15830d](https://linux-hardware.org/?probe=ef6c15830d) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX                 | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| ASRock        | Z97 Pro4                    | [6fa2a70f99](https://linux-hardware.org/?probe=6fa2a70f99) | Nov 01, 2023 |
| HP            | 18EB                        | [83596ab9d9](https://linux-hardware.org/?probe=83596ab9d9) | Oct 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| ASRock        | Z690M-ITX/ax                | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Gigabyte      | MZBSWAP-K4                  | [aed94a16c1](https://linux-hardware.org/?probe=aed94a16c1) | Oct 30, 2023 |
| Trigkey       | Green G4 10                 | [bb72f6af02](https://linux-hardware.org/?probe=bb72f6af02) | Oct 29, 2023 |
| Medion        | TJ4125                      | [f791cf88cb](https://linux-hardware.org/?probe=f791cf88cb) | Oct 27, 2023 |
| Dell          | 0HH807                      | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Unknown       | P4M800CE-8237               | [bf22b887f8](https://linux-hardware.org/?probe=bf22b887f8) | Oct 26, 2023 |
| ASRock        | Z97 Pro4                    | [bcf737a9cd](https://linux-hardware.org/?probe=bcf737a9cd) | Oct 25, 2023 |
| Gigabyte      | Q87M-D2H                    | [74d5de2172](https://linux-hardware.org/?probe=74d5de2172) | Oct 21, 2023 |
| Gigabyte      | Q87M-D2H                    | [4633508fb0](https://linux-hardware.org/?probe=4633508fb0) | Oct 20, 2023 |
| Acer          | Predator G3-605             | [d3b59b34a0](https://linux-hardware.org/?probe=d3b59b34a0) | Oct 19, 2023 |
| Intel         | DG31PR AAD97573-206         | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| HP            | 843B                        | [0e5a69e3ab](https://linux-hardware.org/?probe=0e5a69e3ab) | Oct 17, 2023 |
| ASRock        | H310M-STX                   | [b0bc91de7a](https://linux-hardware.org/?probe=b0bc91de7a) | Oct 14, 2023 |
| Medion        | TJ4125                      | [e60adf45ac](https://linux-hardware.org/?probe=e60adf45ac) | Oct 10, 2023 |
| Gigabyte      | A520M S2H                   | [d71ced0f1d](https://linux-hardware.org/?probe=d71ced0f1d) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [04473f37e9](https://linux-hardware.org/?probe=04473f37e9) | Oct 07, 2023 |
| Gigabyte      | G31M-ES2L                   | [bfed98df15](https://linux-hardware.org/?probe=bfed98df15) | Oct 04, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [5fa6a632ae](https://linux-hardware.org/?probe=5fa6a632ae) | Sep 18, 2023 |
| HP            | 158B                        | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| ASRock        | X670E Pro RS                | [11d9d55772](https://linux-hardware.org/?probe=11d9d55772) | Sep 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [807a40b618](https://linux-hardware.org/?probe=807a40b618) | Sep 15, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.1.0-12-amd64        | 35       | 10.23%  |
| 6.1.0-37-amd64        | 32       | 9.36%   |
| 6.1.0-13-amd64        | 26       | 7.6%    |
| 6.1.0-17-amd64        | 22       | 6.43%   |
| 6.1.0-23-amd64        | 16       | 4.68%   |
| 6.1.0-21-amd64        | 16       | 4.68%   |
| 6.1.0-34-amd64        | 15       | 4.39%   |
| 6.1.0-26-amd64        | 15       | 4.39%   |
| 6.1.0-31-amd64        | 13       | 3.8%    |
| 6.1.0-28-amd64        | 12       | 3.51%   |
| 6.1.0-18-amd64        | 12       | 3.51%   |
| 6.1.0-20-amd64        | 11       | 3.22%   |
| 6.1.0-38-amd64        | 10       | 2.92%   |
| 6.1.0-32-amd64        | 10       | 2.92%   |
| 6.1.0-40-amd64        | 9        | 2.63%   |
| 6.1.0-30-amd64        | 9        | 2.63%   |
| 6.1.0-33-amd64        | 8        | 2.34%   |
| 6.1.0-25-amd64        | 8        | 2.34%   |
| 6.1.0-16-amd64        | 8        | 2.34%   |
| 6.1.0-27-amd64        | 5        | 1.46%   |
| 6.1.0-29-amd64        | 4        | 1.17%   |
| 6.1.0-22-amd64        | 4        | 1.17%   |
| 6.1.0-12-686          | 4        | 1.17%   |
| 6.1.0-39-amd64        | 3        | 0.88%   |
| 6.12.9+bpo-amd64      | 2        | 0.58%   |
| 6.12.12+bpo-amd64     | 2        | 0.58%   |
| 6.10.11+bpo-amd64     | 2        | 0.58%   |
| 6.1.0-41-amd64        | 2        | 0.58%   |
| 6.1.0-41-686          | 2        | 0.58%   |
| 6.1.0-35-amd64        | 2        | 0.58%   |
| 6.1.0-15-amd64        | 2        | 0.58%   |
| 6.1.0-14-amd64        | 2        | 0.58%   |
| 6.9.7+bpo-amd64       | 1        | 0.29%   |
| 6.7.12+bpo-amd64      | 1        | 0.29%   |
| 6.7.10-060710-generic | 1        | 0.29%   |
| 6.6.13+bpo-amd64      | 1        | 0.29%   |
| 6.6.11-x64v3-xanmod1  | 1        | 0.29%   |
| 6.5.0-0.deb12.4-amd64 | 1        | 0.29%   |
| 6.16.7-x64v3-xanmod1  | 1        | 0.29%   |
| 6.14.0-061400-generic | 1        | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.0   | 275      | 93.22%  |
| 6.12.9  | 3        | 1.02%   |
| 6.12.12 | 3        | 1.02%   |
| 6.10.11 | 2        | 0.68%   |
| 6.9.7   | 1        | 0.34%   |
| 6.7.12  | 1        | 0.34%   |
| 6.7.10  | 1        | 0.34%   |
| 6.6.13  | 1        | 0.34%   |
| 6.6.11  | 1        | 0.34%   |
| 6.5.0   | 1        | 0.34%   |
| 6.16.7  | 1        | 0.34%   |
| 6.14.0  | 1        | 0.34%   |
| 6.13.8  | 1        | 0.34%   |
| 6.12.28 | 1        | 0.34%   |
| 6.12.22 | 1        | 0.34%   |
| 6.11.10 | 1        | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 275      | 93.22%  |
| 6.12    | 8        | 2.71%   |
| 6.7     | 2        | 0.68%   |
| 6.6     | 2        | 0.68%   |
| 6.10    | 2        | 0.68%   |
| 6.9     | 1        | 0.34%   |
| 6.5     | 1        | 0.34%   |
| 6.16    | 1        | 0.34%   |
| 6.14    | 1        | 0.34%   |
| 6.13    | 1        | 0.34%   |
| 6.11    | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 286      | 97.28%  |
| i686   | 8        | 2.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 275      | 92.28%  |
| XFCE       | 6        | 2.01%   |
| Cinnamon   | 6        | 2.01%   |
| Unknown    | 5        | 1.68%   |
| MATE       | 2        | 0.67%   |
| KDE5       | 2        | 0.67%   |
| LXDE       | 1        | 0.34%   |
| GNOME      | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 287      | 97.29%  |
| Wayland | 6        | 2.03%   |
| Tty     | 2        | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 162      | 54.55%  |
| Unknown | 134      | 45.12%  |
| GDM3    | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 106      | 35.81%  |
| de_DE   | 45       | 15.2%   |
| it_IT   | 37       | 12.5%   |
| en_GB   | 22       | 7.43%   |
| fr_FR   | 13       | 4.39%   |
| pt_BR   | 8        | 2.7%    |
| ru_RU   | 6        | 2.03%   |
| pl_PL   | 5        | 1.69%   |
| Unknown | 5        | 1.69%   |
| es_ES   | 4        | 1.35%   |
| en_AU   | 4        | 1.35%   |
| cs_CZ   | 4        | 1.35%   |
| tr_TR   | 2        | 0.68%   |
| nl_BE   | 2        | 0.68%   |
| ja_JP   | 2        | 0.68%   |
| hu_HU   | 2        | 0.68%   |
| hr_HR   | 2        | 0.68%   |
| fr_CA   | 2        | 0.68%   |
| es_UY   | 2        | 0.68%   |
| es_AR   | 2        | 0.68%   |
| en_NZ   | 2        | 0.68%   |
| en_DK   | 2        | 0.68%   |
| en_CA   | 2        | 0.68%   |
| sv_SE   | 1        | 0.34%   |
| sr_RS   | 1        | 0.34%   |
| nl_NL   | 1        | 0.34%   |
| nb_NO   | 1        | 0.34%   |
| fi_FI   | 1        | 0.34%   |
| es_VE   | 1        | 0.34%   |
| es_PE   | 1        | 0.34%   |
| es_PA   | 1        | 0.34%   |
| es_MX   | 1        | 0.34%   |
| es_HN   | 1        | 0.34%   |
| es_CL   | 1        | 0.34%   |
| el_GR   | 1        | 0.34%   |
| de_CH   | 1        | 0.34%   |
| de_AT   | 1        | 0.34%   |
| bs_BA   | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 182      | 61.28%  |
| BIOS | 115      | 38.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 263      | 89.15%  |
| Btrfs   | 15       | 5.08%   |
| Overlay | 10       | 3.39%   |
| Tmpfs   | 7        | 2.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 129      | 43.58%  |
| GPT     | 126      | 42.57%  |
| MBR     | 41       | 13.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 253      | 85.76%  |
| Yes       | 42       | 14.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 221      | 74.66%  |
| Yes       | 75       | 25.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 69       | 23.47%  |
| Gigabyte Technology                  | 37       | 12.59%  |
| MSI                                  | 35       | 11.9%   |
| ASRock                               | 28       | 9.52%   |
| Dell                                 | 26       | 8.84%   |
| Hewlett-Packard                      | 21       | 7.14%   |
| Lenovo                               | 13       | 4.42%   |
| Fujitsu                              | 12       | 4.08%   |
| Intel                                | 7        | 2.38%   |
| Acer                                 | 6        | 2.04%   |
| GEEKOM                               | 5        | 1.7%    |
| Unknown                              | 5        | 1.7%    |
| Shenzhen Meigao Electronic Equipment | 3        | 1.02%   |
| PELADN                               | 2        | 0.68%   |
| Pegatron                             | 2        | 0.68%   |
| Medion                               | 2        | 0.68%   |
| Inventec                             | 2        | 0.68%   |
| ECS                                  | 2        | 0.68%   |
| Apple                                | 2        | 0.68%   |
| WeiBu                                | 1        | 0.34%   |
| Trigkey                              | 1        | 0.34%   |
| Soyo                                 | 1        | 0.34%   |
| Quanta                               | 1        | 0.34%   |
| NZXT                                 | 1        | 0.34%   |
| Minix                                | 1        | 0.34%   |
| MACHINIST                            | 1        | 0.34%   |
| HC Technology.                       | 1        | 0.34%   |
| G7-2011                              | 1        | 0.34%   |
| Foxconn                              | 1        | 0.34%   |
| Clientron Crop.                      | 1        | 0.34%   |
| Biostar                              | 1        | 0.34%   |
| AZW                                  | 1        | 0.34%   |
| AMI                                  | 1        | 0.34%   |
| American Megatrends                  | 1        | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| ASUS All Series                                     | 5        | 1.7%    |
| Unknown                                             | 5        | 1.7%    |
| Dell OptiPlex 3020                                  | 3        | 1.02%   |
| ASRock A320M-HDV R4.0                               | 3        | 1.02%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 2        | 0.68%   |
| PELADN WI-6                                         | 2        | 0.68%   |
| MSI MS-7D91                                         | 2        | 0.68%   |
| MSI MS-7C95                                         | 2        | 0.68%   |
| MSI MS-7C56                                         | 2        | 0.68%   |
| MSI MS-7798                                         | 2        | 0.68%   |
| Lenovo ThinkCentre M93p 10A8S4B200                  | 2        | 0.68%   |
| HP Compaq dc5800 Microtower                         | 2        | 0.68%   |
| Gigabyte B360 AORUS GAMING 3 WIFI                   | 2        | 0.68%   |
| Gigabyte A520M S2H                                  | 2        | 0.68%   |
| Gigabyte 970A-DS3P                                  | 2        | 0.68%   |
| GEEKOM AE8                                          | 2        | 0.68%   |
| GEEKOM A7                                           | 2        | 0.68%   |
| Dell Precision Tower 5810                           | 2        | 0.68%   |
| Dell Precision T3610                                | 2        | 0.68%   |
| Dell Precision T1700                                | 2        | 0.68%   |
| Dell OptiPlex 7010                                  | 2        | 0.68%   |
| ASUS SABERTOOTH 990FX R2.0                          | 2        | 0.68%   |
| ASUS ROG STRIX B550-F GAMING                        | 2        | 0.68%   |
| ASUS ROG STRIX B450-F GAMING                        | 2        | 0.68%   |
| ASRock X670E Taichi Carrara                         | 2        | 0.68%   |
| Apple MacPro6,1                                     | 2        | 0.68%   |
| WeiBu ADL-N                                         | 1        | 0.34%   |
| Trigkey Green G4                                    | 1        | 0.34%   |
| Soyo SY-N3150L Quad                                 | 1        | 0.34%   |
| Shenzhen Meigao Electronic Equipment Venus Series   | 1        | 0.34%   |
| Quanta 120-1125                                     | 1        | 0.34%   |
| Pegatron Pro 3120 Microtower PC                     | 1        | 0.34%   |
| Pegatron Elite 7500 Series MT                       | 1        | 0.34%   |
| NZXT N7 B550                                        | 1        | 0.34%   |
| MSI MS-7E16                                         | 1        | 0.34%   |
| MSI MS-7E07                                         | 1        | 0.34%   |
| MSI MS-7E01                                         | 1        | 0.34%   |
| MSI MS-7D98                                         | 1        | 0.34%   |
| MSI MS-7D95                                         | 1        | 0.34%   |
| MSI MS-7D74                                         | 1        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Dell OptiPlex                                | 11       | 3.74%   |
| ASUS PRIME                                   | 11       | 3.74%   |
| ASUS ROG                                     | 10       | 3.4%    |
| Dell Precision                               | 9        | 3.06%   |
| Lenovo ThinkCentre                           | 8        | 2.72%   |
| Fujitsu ESPRIMO                              | 8        | 2.72%   |
| ASUS TUF                                     | 8        | 2.72%   |
| HP Compaq                                    | 6        | 2.04%   |
| ASUS All                                     | 5        | 1.7%    |
| Unknown                                      | 5        | 1.7%    |
| HP ProDesk                                   | 4        | 1.36%   |
| ASRock A320M-HDV                             | 4        | 1.36%   |
| Acer Aspire                                  | 4        | 1.36%   |
| Gigabyte A520M                               | 3        | 1.02%   |
| ASUS P8H61-M                                 | 3        | 1.02%   |
| ASUS P5G41T-M                                | 3        | 1.02%   |
| ASRock X670E                                 | 3        | 1.02%   |
| Shenzhen Meigao Electronic Equipment Mercury | 2        | 0.68%   |
| PELADN WI-6                                  | 2        | 0.68%   |
| MSI MS-7D91                                  | 2        | 0.68%   |
| MSI MS-7C95                                  | 2        | 0.68%   |
| MSI MS-7C56                                  | 2        | 0.68%   |
| MSI MS-7798                                  | 2        | 0.68%   |
| Lenovo IdeaCentre                            | 2        | 0.68%   |
| Gigabyte B760M                               | 2        | 0.68%   |
| Gigabyte B450M                               | 2        | 0.68%   |
| Gigabyte B450                                | 2        | 0.68%   |
| Gigabyte B360                                | 2        | 0.68%   |
| Gigabyte 970A-DS3P                           | 2        | 0.68%   |
| GEEKOM AE8                                   | 2        | 0.68%   |
| GEEKOM A7                                    | 2        | 0.68%   |
| Fujitsu CELSIUS                              | 2        | 0.68%   |
| Dell XPS                                     | 2        | 0.68%   |
| ASUS SABERTOOTH                              | 2        | 0.68%   |
| ASUS P8H67-M                                 | 2        | 0.68%   |
| ASUS Crosshair                               | 2        | 0.68%   |
| ASRock Z690                                  | 2        | 0.68%   |
| ASRock B450                                  | 2        | 0.68%   |
| Apple MacPro6                                | 2        | 0.68%   |
| WeiBu ADL-N                                  | 1        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 28       | 9.52%   |
| 2022 | 26       | 8.84%   |
| 2012 | 23       | 7.82%   |
| 2010 | 21       | 7.14%   |
| 2020 | 19       | 6.46%   |
| 2017 | 18       | 6.12%   |
| 2016 | 18       | 6.12%   |
| 2013 | 18       | 6.12%   |
| 2023 | 17       | 5.78%   |
| 2011 | 16       | 5.44%   |
| 2019 | 13       | 4.42%   |
| 2015 | 13       | 4.42%   |
| 2021 | 11       | 3.74%   |
| 2014 | 11       | 3.74%   |
| 2009 | 10       | 3.4%    |
| 2008 | 10       | 3.4%    |
| 2007 | 9        | 3.06%   |
| 2024 | 8        | 2.72%   |
| 2006 | 2        | 0.68%   |
| 2004 | 2        | 0.68%   |
| 2025 | 1        | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 294      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 280      | 94.92%  |
| Enabled  | 15       | 5.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 294      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 81       | 27%     |
| 32.01-64.0  | 66       | 22%     |
| 4.01-8.0    | 42       | 14%     |
| 8.01-16.0   | 35       | 11.67%  |
| 64.01-256.0 | 27       | 9%      |
| 3.01-4.0    | 21       | 7%      |
| 24.01-32.0  | 17       | 5.67%   |
| 2.01-3.0    | 5        | 1.67%   |
| 1.01-2.0    | 5        | 1.67%   |
| 0.51-1.0    | 1        | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 96       | 29.91%  |
| 4.01-8.0   | 76       | 23.68%  |
| 1.01-2.0   | 68       | 21.18%  |
| 3.01-4.0   | 59       | 18.38%  |
| 8.01-16.0  | 16       | 4.98%   |
| 0.51-1.0   | 5        | 1.56%   |
| 24.01-32.0 | 1        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 39.14%  |
| 2      | 76       | 25%     |
| 3      | 51       | 16.78%  |
| 4      | 33       | 10.86%  |
| 5      | 10       | 3.29%   |
| 6      | 7        | 2.3%    |
| 7      | 4        | 1.32%   |
| 8      | 2        | 0.66%   |
| 10     | 1        | 0.33%   |
| 0      | 1        | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 170      | 57.63%  |
| Yes       | 125      | 42.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 290      | 98.64%  |
| No        | 4        | 1.36%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 52.53%  |
| Yes       | 141      | 47.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 57.19%  |
| Yes       | 128      | 42.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 62       | 21.09%  |
| Germany                | 53       | 18.03%  |
| Italy                  | 45       | 15.31%  |
| UK                     | 12       | 4.08%   |
| France                 | 12       | 4.08%   |
| Brazil                 | 9        | 3.06%   |
| Russia                 | 7        | 2.38%   |
| Canada                 | 7        | 2.38%   |
| Malaysia               | 6        | 2.04%   |
| Spain                  | 4        | 1.36%   |
| Poland                 | 4        | 1.36%   |
| Norway                 | 4        | 1.36%   |
| Czechia                | 4        | 1.36%   |
| Australia              | 4        | 1.36%   |
| Argentina              | 4        | 1.36%   |
| New Zealand            | 3        | 1.02%   |
| Netherlands            | 3        | 1.02%   |
| Hungary                | 3        | 1.02%   |
| Croatia                | 3        | 1.02%   |
| Belgium                | 3        | 1.02%   |
| Uruguay                | 2        | 0.68%   |
| Turkey                 | 2        | 0.68%   |
| Sweden                 | 2        | 0.68%   |
| Peru                   | 2        | 0.68%   |
| Paraguay               | 2        | 0.68%   |
| Mexico                 | 2        | 0.68%   |
| Japan                  | 2        | 0.68%   |
| India                  | 2        | 0.68%   |
| Greece                 | 2        | 0.68%   |
| Denmark                | 2        | 0.68%   |
| Bosnia and Herzegovina | 2        | 0.68%   |
| Venezuela              | 1        | 0.34%   |
| Thailand               | 1        | 0.34%   |
| Switzerland            | 1        | 0.34%   |
| Slovakia               | 1        | 0.34%   |
| Serbia                 | 1        | 0.34%   |
| Romania                | 1        | 0.34%   |
| Portugal               | 1        | 0.34%   |
| Panama                 | 1        | 0.34%   |
| Morocco                | 1        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 8        | 2.56%   |
| Rome                  | 5        | 1.6%    |
| Turin                 | 4        | 1.28%   |
| Kuala Lumpur          | 4        | 1.28%   |
| Moscow                | 3        | 0.96%   |
| Hamburg               | 3        | 0.96%   |
| Delligsen             | 3        | 0.96%   |
| Dallas                | 3        | 0.96%   |
| Bologna               | 3        | 0.96%   |
| Berlin                | 3        | 0.96%   |
| Auckland              | 3        | 0.96%   |
| Uetze                 | 2        | 0.64%   |
| Trondheim             | 2        | 0.64%   |
| Troisdorf             | 2        | 0.64%   |
| Traunstein            | 2        | 0.64%   |
| Tokushima             | 2        | 0.64%   |
| Sydney                | 2        | 0.64%   |
| South Bend            | 2        | 0.64%   |
| Šlapanice            | 2        | 0.64%   |
| Plochingen            | 2        | 0.64%   |
| Parshall              | 2        | 0.64%   |
| Panama City           | 2        | 0.64%   |
| Padova                | 2        | 0.64%   |
| Munich                | 2        | 0.64%   |
| Montevideo            | 2        | 0.64%   |
| Melbourne             | 2        | 0.64%   |
| Ludwigshafen am Rhein | 2        | 0.64%   |
| Freden                | 2        | 0.64%   |
| Florence              | 2        | 0.64%   |
| Fitchburg             | 2        | 0.64%   |
| Düsseldorf           | 2        | 0.64%   |
| Cullompton            | 2        | 0.64%   |
| Clinton               | 2        | 0.64%   |
| Bremen                | 2        | 0.64%   |
| Athens                | 2        | 0.64%   |
| Ancona                | 2        | 0.64%   |
| York                  | 1        | 0.32%   |
| Woodway               | 1        | 0.32%   |
| Wisconsin Dells       | 1        | 0.32%   |
| Winchester            | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 91       | 136    | 15.56%  |
| Samsung Electronics         | 78       | 133    | 13.33%  |
| Seagate                     | 72       | 124    | 12.31%  |
| Kingston                    | 38       | 60     | 6.5%    |
| SanDisk                     | 31       | 42     | 5.3%    |
| Crucial                     | 28       | 35     | 4.79%   |
| Toshiba                     | 23       | 29     | 3.93%   |
| Hitachi                     | 13       | 19     | 2.22%   |
| Intel                       | 10       | 13     | 1.71%   |
| China                       | 10       | 11     | 1.71%   |
| PNY                         | 9        | 15     | 1.54%   |
| A-DATA Technology           | 9        | 10     | 1.54%   |
| Micron Technology           | 8        | 9      | 1.37%   |
| Intenso                     | 8        | 10     | 1.37%   |
| SPCC                        | 7        | 7      | 1.2%    |
| Unknown                     | 7        | 16     | 1.2%    |
| Unknown                     | 6        | 12     | 1.03%   |
| Patriot                     | 6        | 6      | 1.03%   |
| Micron/Crucial Technology   | 6        | 9      | 1.03%   |
| ADATA Technology            | 6        | 10     | 1.03%   |
| Verbatim                    | 5        | 8      | 0.85%   |
| Phison Electronics          | 5        | 5      | 0.85%   |
| MAXIO Technology (Hangzhou) | 5        | 5      | 0.85%   |
| Kingston Technology Company | 5        | 7      | 0.85%   |
| JMicron Technology          | 5        | 5      | 0.85%   |
| HGST                        | 5        | 7      | 0.85%   |
| Gigabyte Technology         | 4        | 4      | 0.68%   |
| Apacer                      | 4        | 4      | 0.68%   |
| XrayDisk                    | 3        | 3      | 0.51%   |
| Team                        | 3        | 4      | 0.51%   |
| OCZ                         | 3        | 3      | 0.51%   |
| Maxtor                      | 3        | 3      | 0.51%   |
| KingSpec                    | 3        | 3      | 0.51%   |
| GOODRAM                     | 3        | 3      | 0.51%   |
| Corsair                     | 3        | 4      | 0.51%   |
| T-FORCE                     | 2        | 2      | 0.34%   |
| SK hynix                    | 2        | 2      | 0.34%   |
| Silicon Motion              | 2        | 2      | 0.34%   |
| Phison                      | 2        | 12     | 0.34%   |
| PELADN                      | 2        | 2      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD                                    | 9        | 1.33%   |
| Kingston SA400S37240G 240GB SSD                                    | 9        | 1.33%   |
| Samsung SSD 850 EVO 250GB                                          | 7        | 1.03%   |
| Unknown                                                            | 7        | 1.03%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 6        | 0.88%   |
| SanDisk NVMe SSD Drive 2TB                                         | 6        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 6        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 6        | 0.88%   |
| Toshiba DT01ACA100 1TB                                             | 5        | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                                    | 5        | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB                                     | 5        | 0.74%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 5        | 0.74%   |
| SanDisk NVMe SSD Drive 1TB                                         | 5        | 0.74%   |
| Samsung SSD 990 PRO 2TB                                            | 5        | 0.74%   |
| Crucial CT500MX500SSD1 500GB                                       | 5        | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 4        | 0.59%   |
| Samsung SSD 980 1TB                                                | 4        | 0.59%   |
| Samsung SSD 860 EVO 500GB                                          | 4        | 0.59%   |
| Kingston SA400S37120G 120GB SSD                                    | 4        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB                                       | 3        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                   | 3        | 0.44%   |
| WDC WD40EZRZ-00GXCB0 4TB                                           | 3        | 0.44%   |
| WDC WD40EZAZ-00SF3B0 4TB                                           | 3        | 0.44%   |
| WDC WD20EARX-00PASB0 2TB                                           | 3        | 0.44%   |
| Verbatim Vi550 S3 1024GB                                           | 3        | 0.44%   |
| Toshiba DT01ACA050 500GB                                           | 3        | 0.44%   |
| SPCC Solid State Disk 512GB                                        | 3        | 0.44%   |
| Seagate ST500DM002-1SB10A 500GB                                    | 3        | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 3        | 0.44%   |
| SanDisk SSD PLUS 1000GB                                            | 3        | 0.44%   |
| Samsung SSD 980 500GB                                              | 3        | 0.44%   |
| Samsung SSD 870 EVO 500GB                                          | 3        | 0.44%   |
| Samsung SSD 870 EVO 4TB                                            | 3        | 0.44%   |
| Samsung SSD 860 EVO 1TB                                            | 3        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 3        | 0.44%   |
| Samsung HD204UI 2TB                                                | 3        | 0.44%   |
| PNY CS900 240GB SSD                                                | 3        | 0.44%   |
| Micron/Crucial CT2000T500SSD8 2TB                                  | 3        | 0.44%   |
| MAXIO (Hangzhou) NVMe SSD Drive 512GB                              | 3        | 0.44%   |
| JMicron Tech 250GB                                                 | 3        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 107    | 34.78%  |
| Seagate             | 71       | 120    | 34.3%   |
| Toshiba             | 19       | 25     | 9.18%   |
| Hitachi             | 13       | 19     | 6.28%   |
| Samsung Electronics | 9        | 11     | 4.35%   |
| HGST                | 5        | 7      | 2.42%   |
| Maxtor              | 3        | 3      | 1.45%   |
| Unknown             | 2        | 3      | 0.97%   |
| JMicron Technology  | 2        | 2      | 0.97%   |
| External            | 2        | 2      | 0.97%   |
| USB3.0              | 1        | 1      | 0.48%   |
| TrueNAS             | 1        | 2      | 0.48%   |
| TO Exter            | 1        | 1      | 0.48%   |
| Intenso             | 1        | 1      | 0.48%   |
| IBM/Hitachi         | 1        | 1      | 0.48%   |
| DC-624e             | 1        | 1      | 0.48%   |
| ASMT                | 1        | 2      | 0.48%   |
| ASMedia             | 1        | 1      | 0.48%   |
| Unknown             | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 42       | 53     | 17.57%  |
| Kingston            | 30       | 45     | 12.55%  |
| Crucial             | 19       | 25     | 7.95%   |
| WDC                 | 18       | 23     | 7.53%   |
| SanDisk             | 10       | 13     | 4.18%   |
| China               | 10       | 11     | 4.18%   |
| PNY                 | 9        | 15     | 3.77%   |
| Intenso             | 7        | 9      | 2.93%   |
| A-DATA Technology   | 7        | 8      | 2.93%   |
| SPCC                | 6        | 6      | 2.51%   |
| Patriot             | 6        | 6      | 2.51%   |
| Micron Technology   | 6        | 7      | 2.51%   |
| Intel               | 6        | 8      | 2.51%   |
| Verbatim            | 5        | 8      | 2.09%   |
| Unknown             | 5        | 13     | 2.09%   |
| Toshiba             | 3        | 3      | 1.26%   |
| Team                | 3        | 4      | 1.26%   |
| OCZ                 | 3        | 3      | 1.26%   |
| KingSpec            | 3        | 3      | 1.26%   |
| Apacer              | 3        | 3      | 1.26%   |
| T-FORCE             | 2        | 2      | 0.84%   |
| Seagate             | 2        | 2      | 0.84%   |
| KingDian            | 2        | 2      | 0.84%   |
| Integral            | 2        | 2      | 0.84%   |
| GOODRAM             | 2        | 2      | 0.84%   |
| Gigabyte Technology | 2        | 2      | 0.84%   |
| XrayDisk            | 1        | 1      | 0.42%   |
| X12                 | 1        | 1      | 0.42%   |
| Vi550               | 1        | 2      | 0.42%   |
| V Series            | 1        | 1      | 0.42%   |
| Transcend           | 1        | 1      | 0.42%   |
| Solid               | 1        | 1      | 0.42%   |
| Phison              | 1        | 11     | 0.42%   |
| PELADN              | 1        | 1      | 0.42%   |
| Moment              | 1        | 1      | 0.42%   |
| LITEONIT            | 1        | 1      | 0.42%   |
| LITEON              | 1        | 1      | 0.42%   |
| Lexar               | 1        | 1      | 0.42%   |
| Leven               | 1        | 1      | 0.42%   |
| LDLC                | 1        | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 185      | 318    | 38.7%   |
| HDD     | 164      | 310    | 34.31%  |
| NVMe    | 114      | 203    | 23.85%  |
| Unknown | 13       | 22     | 2.72%   |
| MMC     | 2        | 3      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 260      | 602    | 62.95%  |
| NVMe | 114      | 200    | 27.6%   |
| SAS  | 37       | 51     | 8.96%   |
| MMC  | 2        | 3      | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 190      | 324    | 50%     |
| 0.51-1.0   | 98       | 150    | 25.79%  |
| 1.01-2.0   | 44       | 77     | 11.58%  |
| 3.01-4.0   | 26       | 43     | 6.84%   |
| 4.01-10.0  | 11       | 20     | 2.89%   |
| 2.01-3.0   | 6        | 8      | 1.58%   |
| 10.01-20.0 | 5        | 6      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 59       | 19.03%  |
| 101-250        | 57       | 18.39%  |
| 251-500        | 56       | 18.06%  |
| More than 3000 | 46       | 14.84%  |
| 1001-2000      | 40       | 12.9%   |
| 2001-3000      | 22       | 7.1%    |
| 51-100         | 11       | 3.55%   |
| 1-20           | 10       | 3.23%   |
| Unknown        | 5        | 1.61%   |
| 21-50          | 4        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 71       | 21.98%  |
| 21-50          | 53       | 16.41%  |
| 101-250        | 45       | 13.93%  |
| 51-100         | 38       | 11.76%  |
| 501-1000       | 36       | 11.15%  |
| 251-500        | 33       | 10.22%  |
| More than 3000 | 20       | 6.19%   |
| 2001-3000      | 11       | 3.41%   |
| 1001-2000      | 11       | 3.41%   |
| Unknown        | 5        | 1.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB                   | 2        | 3      | 5.13%   |
| Intel SSDSA2M160G2GC 160GB                          | 2        | 2      | 5.13%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1        | 1      | 2.56%   |
| WDC WD3200AAKS-00L9A0 320GB                         | 1        | 1      | 2.56%   |
| WDC WD1600JS-60MHB5 160GB                           | 1        | 1      | 2.56%   |
| WDC WD15EADS-00P8B0 1TB                             | 1        | 1      | 2.56%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1        | 1      | 2.56%   |
| WDC WD10EZEX-75M2NA0 1TB                            | 1        | 1      | 2.56%   |
| WDC WD10EFRX-68PJCN0 1TB                            | 1        | 1      | 2.56%   |
| WDC WD Green 2.5 240GB                              | 1        | 1      | 2.56%   |
| Solid SSD0256S00 256GB                              | 1        | 1      | 2.56%   |
| Seagate ST9500325AS 500GB                           | 1        | 1      | 2.56%   |
| Seagate ST9250315AS 250GB                           | 1        | 1      | 2.56%   |
| Seagate ST31000528AS 1TB                            | 1        | 1      | 2.56%   |
| Seagate ST31000524AS 1TB                            | 1        | 1      | 2.56%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1        | 1      | 2.56%   |
| Seagate ST1000DX001-1NS162 1TB                      | 1        | 1      | 2.56%   |
| Seagate ST1000DM003-1SB102 1TB                      | 1        | 1      | 2.56%   |
| SanDisk SSD PLUS 480 GB                             | 1        | 1      | 2.56%   |
| SanDisk SDSSDHII120G 120GB                          | 1        | 2      | 2.56%   |
| Samsung Electronics SSD 970 EVO 500GB               | 1        | 1      | 2.56%   |
| Samsung Electronics HD403LJ 400GB                   | 1        | 1      | 2.56%   |
| Samsung Electronics HD103UJ 1TB                     | 1        | 1      | 2.56%   |
| Micron Technology MTFDDAK512MAY-1AE1ZABHA 512GB SSD | 1        | 1      | 2.56%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD      | 1        | 1      | 2.56%   |
| Maxtor STM3250310AS 250GB                           | 1        | 1      | 2.56%   |
| Maxtor 6E040L0 41GB                                 | 1        | 1      | 2.56%   |
| Leven JAJS600M128C 128GB SSD                        | 1        | 1      | 2.56%   |
| Kingston SKC2500M8500G 500GB                        | 1        | 1      | 2.56%   |
| KingSpec Q-360 360GB                                | 1        | 1      | 2.56%   |
| Intel SSDSC2BF180A4H 180GB                          | 1        | 1      | 2.56%   |
| IBM/Hitachi IC35L040AVER07-0 41GB                   | 1        | 1      | 2.56%   |
| Hitachi HTS545050A7E380 500GB                       | 1        | 1      | 2.56%   |
| Hitachi HDT725032VLA380 320GB                       | 1        | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB                          | 1        | 1      | 2.56%   |
| A-DATA Technology SU650 240GB SSD                   | 1        | 1      | 2.56%   |
| A-DATA Technology SP920SS 128GB SSD                 | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 21.05%  |
| Seagate             | 7        | 7      | 18.42%  |
| Samsung Electronics | 5        | 6      | 13.16%  |
| Intel               | 3        | 3      | 7.89%   |
| SanDisk             | 2        | 3      | 5.26%   |
| Micron Technology   | 2        | 2      | 5.26%   |
| Maxtor              | 2        | 2      | 5.26%   |
| A-DATA Technology   | 2        | 2      | 5.26%   |
| Solid               | 1        | 1      | 2.63%   |
| Leven               | 1        | 1      | 2.63%   |
| Kingston            | 1        | 1      | 2.63%   |
| KingSpec            | 1        | 1      | 2.63%   |
| IBM/Hitachi         | 1        | 1      | 2.63%   |
| Hitachi             | 1        | 2      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 7      | 31.82%  |
| WDC                 | 6        | 6      | 27.27%  |
| Samsung Electronics | 4        | 5      | 18.18%  |
| Maxtor              | 2        | 2      | 9.09%   |
| IBM/Hitachi         | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 2      | 4.55%   |
| HGST                | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 24     | 57.89%  |
| SSD  | 14       | 15     | 36.84%  |
| NVMe | 2        | 2      | 5.26%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 164      | 439    | 46.46%  |
| Works    | 152      | 376    | 43.06%  |
| Malfunc  | 37       | 41     | 10.48%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 185      | 39.96%  |
| AMD                              | 93       | 20.09%  |
| Samsung Electronics              | 39       | 8.42%   |
| SanDisk                          | 23       | 4.97%   |
| ASMedia Technology               | 16       | 3.46%   |
| Phison Electronics               | 14       | 3.02%   |
| Kingston Technology Company      | 14       | 3.02%   |
| Micron/Crucial Technology        | 13       | 2.81%   |
| Marvell Technology Group         | 9        | 1.94%   |
| JMicron Technology               | 9        | 1.94%   |
| ADATA Technology                 | 8        | 1.73%   |
| MAXIO Technology (Hangzhou)      | 7        | 1.51%   |
| VIA Technologies                 | 5        | 1.08%   |
| Nvidia                           | 4        | 0.86%   |
| Micron Technology                | 3        | 0.65%   |
| SK hynix                         | 2        | 0.43%   |
| Silicon Motion                   | 2        | 0.43%   |
| Silicon Image                    | 2        | 0.43%   |
| Hosin Global Electronics         | 2        | 0.43%   |
| Toshiba America Info Systems     | 1        | 0.22%   |
| Silicon Integrated Systems [SiS] | 1        | 0.22%   |
| Shenzhen Longsys Electronics     | 1        | 0.22%   |
| Seagate Technology               | 1        | 0.22%   |
| Realtek Semiconductor            | 1        | 0.22%   |
| Netac Technology                 | 1        | 0.22%   |
| LSI Logic / Symbios Logic        | 1        | 0.22%   |
| KIOXIA                           | 1        | 0.22%   |
| Integrated Technology Express    | 1        | 0.22%   |
| INNOGRIT                         | 1        | 0.22%   |
| Chelsio Communications           | 1        | 0.22%   |
| Broadcom / LSI                   | 1        | 0.22%   |
| Adaptec                          | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30       | 5.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 21       | 3.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 3.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18       | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 2.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 2.9%    |
| Intel SATA Controller [RAID mode]                                                       | 15       | 2.72%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 14       | 2.54%   |
| AMD 600 Series Chipset SATA Controller                                                  | 14       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 2.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2%      |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 10       | 1.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 1.81%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 9        | 1.63%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 9        | 1.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8        | 1.45%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 8        | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 1.27%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 6        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.09%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 5        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 0.91%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.91%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 4        | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 4        | 0.73%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 4        | 0.73%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 0.73%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.54%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 3        | 0.54%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 233      | 54.44%  |
| NVMe | 113      | 26.4%   |
| IDE  | 57       | 13.32%  |
| RAID | 22       | 5.14%   |
| SCSI | 2        | 0.47%   |
| SAS  | 1        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 189      | 64.29%  |
| AMD          | 104      | 35.37%  |
| CentaurHauls | 1        | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel N100                                  | 7        | 2.37%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 1.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 1.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.36%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.36%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.36%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 1.36%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 4        | 1.36%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 1.02%   |
| Intel N95                                   | 3        | 1.02%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 1.02%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 1.02%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 1.02%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 1.02%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.02%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.02%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 1.02%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 3        | 1.02%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.02%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3        | 1.02%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.02%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 1.02%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.02%   |
| AMD Ryzen 5 5500                            | 3        | 1.02%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2        | 0.68%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 2        | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.68%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.68%   |
| Intel Core i5-7600 CPU @ 3.50GHz            | 2        | 0.68%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 2        | 0.68%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.68%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.68%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.68%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 60       | 20.34%  |
| Intel Core i7           | 32       | 10.85%  |
| AMD Ryzen 7             | 28       | 9.49%   |
| Other                   | 24       | 8.14%   |
| AMD Ryzen 5             | 23       | 7.8%    |
| Intel Xeon              | 21       | 7.12%   |
| AMD Ryzen 9             | 18       | 6.1%    |
| Intel Core i3           | 15       | 5.08%   |
| Intel Pentium Dual-Core | 9        | 3.05%   |
| Intel Celeron           | 7        | 2.37%   |
| Intel Core 2 Quad       | 6        | 2.03%   |
| Intel Core 2 Duo        | 6        | 2.03%   |
| AMD Phenom II X6        | 6        | 2.03%   |
| AMD Ryzen 3             | 5        | 1.69%   |
| AMD FX                  | 5        | 1.69%   |
| Intel Pentium 4         | 2        | 0.68%   |
| Intel Pentium           | 2        | 0.68%   |
| Intel Core i9           | 2        | 0.68%   |
| AMD Phenom II X4        | 2        | 0.68%   |
| AMD G                   | 2        | 0.68%   |
| AMD Athlon II X4        | 2        | 0.68%   |
| AMD Athlon II X2        | 2        | 0.68%   |
| AMD Athlon              | 2        | 0.68%   |
| AMD A8                  | 2        | 0.68%   |
| Intel Pentium Dual      | 1        | 0.34%   |
| Intel Pentium D         | 1        | 0.34%   |
| Intel Atom              | 1        | 0.34%   |
| CentaurHauls VIA Eden   | 1        | 0.34%   |
| AMD Sempron             | 1        | 0.34%   |
| AMD Ryzen 5 PRO         | 1        | 0.34%   |
| AMD Phenom II X3        | 1        | 0.34%   |
| AMD Opteron             | 1        | 0.34%   |
| AMD GX                  | 1        | 0.34%   |
| AMD E                   | 1        | 0.34%   |
| AMD Athlon 64           | 1        | 0.34%   |
| AMD A12                 | 1        | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 128      | 43.39%  |
| 6      | 47       | 15.93%  |
| 2      | 46       | 15.59%  |
| 8      | 36       | 12.2%   |
| 16     | 12       | 4.07%   |
| 12     | 9        | 3.05%   |
| 1      | 8        | 2.71%   |
| 14     | 4        | 1.36%   |
| 24     | 2        | 0.68%   |
| 3      | 2        | 0.68%   |
| 10     | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 291      | 98.98%  |
| 2      | 3        | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 165      | 56.12%  |
| 1      | 129      | 43.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 291      | 98.98%  |
| 32-bit         | 3        | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 13.29%  |
| 0x306c3    | 22       | 7.31%   |
| 0x306a9    | 18       | 5.98%   |
| 0x206a7    | 16       | 5.32%   |
| 0x1067a    | 15       | 4.98%   |
| 0x906e9    | 14       | 4.65%   |
| 0x506e3    | 11       | 3.65%   |
| 0xb06e0    | 8        | 2.66%   |
| 0xb0671    | 6        | 1.99%   |
| 0x306e4    | 6        | 1.99%   |
| 0x0a20120e | 6        | 1.99%   |
| 0x010000c8 | 6        | 1.99%   |
| 0x906ea    | 5        | 1.66%   |
| 0x0810100b | 5        | 1.66%   |
| 0x010000dc | 5        | 1.66%   |
| 0x6fb      | 4        | 1.33%   |
| 0x0a50000d | 4        | 1.33%   |
| 0x0800820d | 4        | 1.33%   |
| 0x08001138 | 4        | 1.33%   |
| 0x06000852 | 4        | 1.33%   |
| 0xa0655    | 3        | 1%      |
| 0xa0653    | 3        | 1%      |
| 0x906ed    | 3        | 1%      |
| 0x90672    | 3        | 1%      |
| 0x106e5    | 3        | 1%      |
| 0x106a5    | 3        | 1%      |
| 0x0a601209 | 3        | 1%      |
| 0x0a50000f | 3        | 1%      |
| 0x0a20120a | 3        | 1%      |
| 0x08701030 | 3        | 1%      |
| 0x08701021 | 3        | 1%      |
| 0x08108109 | 3        | 1%      |
| 0x90675    | 2        | 0.66%   |
| 0x406f1    | 2        | 0.66%   |
| 0x406c3    | 2        | 0.66%   |
| 0x306f2    | 2        | 0.66%   |
| 0x10676    | 2        | 0.66%   |
| 0x0a601206 | 2        | 0.66%   |
| 0x0a601203 | 2        | 0.66%   |
| 0x0a50000c | 2        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 31       | 10.51%  |
| KabyLake         | 28       | 9.49%   |
| Zen 3            | 27       | 9.15%   |
| IvyBridge        | 25       | 8.47%   |
| Unknown          | 24       | 8.14%   |
| Penryn           | 18       | 6.1%    |
| SandyBridge      | 17       | 5.76%   |
| K10              | 14       | 4.75%   |
| Skylake          | 13       | 4.41%   |
| Alderlake Hybrid | 13       | 4.41%   |
| Zen              | 11       | 3.73%   |
| Zen 2            | 10       | 3.39%   |
| Zen+             | 8        | 2.71%   |
| Gracemont        | 8        | 2.71%   |
| Nehalem          | 7        | 2.37%   |
| Piledriver       | 6        | 2.03%   |
| Core             | 6        | 2.03%   |
| CometLake        | 6        | 2.03%   |
| NetBurst         | 4        | 1.36%   |
| Silvermont       | 3        | 1.02%   |
| Westmere         | 2        | 0.68%   |
| Broadwell        | 2        | 0.68%   |
| Bobcat           | 2        | 0.68%   |
| TigerLake        | 1        | 0.34%   |
| Steamroller      | 1        | 0.34%   |
| K8 Hammer        | 1        | 0.34%   |
| K6               | 1        | 0.34%   |
| Jaguar           | 1        | 0.34%   |
| Icelake          | 1        | 0.34%   |
| Goldmont plus    | 1        | 0.34%   |
| Goldmont         | 1        | 0.34%   |
| Excavator        | 1        | 0.34%   |
| Bulldozer        | 1        | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 108      | 34.5%   |
| Nvidia           | 105      | 33.55%  |
| Intel            | 99       | 31.63%  |
| VIA Technologies | 1        | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 3.37%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 10       | 3.07%   |
| AMD Raphael                                                                              | 10       | 3.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 2.76%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 8        | 2.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 2.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 8        | 2.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7        | 2.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 2.15%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5        | 1.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5        | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.53%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 1.53%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 5        | 1.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4        | 1.23%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 4        | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.23%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 4        | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4        | 1.23%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 4        | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 1.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4        | 1.23%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 1.23%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3        | 0.92%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 3        | 0.92%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 3        | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 0.92%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 3        | 0.92%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 3        | 0.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 0.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 0.92%   |
| AMD Phoenix1                                                                             | 3        | 0.92%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 3        | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 97       | 32.88%  |
| 1 x AMD        | 92       | 31.19%  |
| 1 x Intel      | 81       | 27.46%  |
| 2 x AMD        | 13       | 4.41%   |
| Intel + Nvidia | 5        | 1.69%   |
| Intel + AMD    | 2        | 0.68%   |
| AMD + Nvidia   | 2        | 0.68%   |
| 2 x Nvidia     | 1        | 0.34%   |
| 2 x Intel      | 1        | 0.34%   |
| 1 x VIA        | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 240      | 81.36%  |
| Proprietary | 47       | 15.93%  |
| Unknown     | 8        | 2.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 34.8%   |
| 3.01-4.0   | 33       | 11.15%  |
| 1.01-2.0   | 33       | 11.15%  |
| 0.01-0.5   | 32       | 10.81%  |
| 7.01-8.0   | 31       | 10.47%  |
| 0.51-1.0   | 23       | 7.77%   |
| 8.01-16.0  | 17       | 5.74%   |
| 5.01-6.0   | 14       | 4.73%   |
| 2.01-3.0   | 6        | 2.03%   |
| 16.01-24.0 | 4        | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 55       | 17.68%  |
| Goldstar             | 37       | 11.9%   |
| Dell                 | 30       | 9.65%   |
| Hewlett-Packard      | 22       | 7.07%   |
| Acer                 | 19       | 6.11%   |
| AOC                  | 17       | 5.47%   |
| Philips              | 16       | 5.14%   |
| BenQ                 | 12       | 3.86%   |
| Ancor Communications | 12       | 3.86%   |
| MSI                  | 7        | 2.25%   |
| Lenovo               | 6        | 1.93%   |
| HUAWEI               | 6        | 1.93%   |
| Eizo                 | 6        | 1.93%   |
| Fujitsu Siemens      | 5        | 1.61%   |
| ASUSTek Computer     | 5        | 1.61%   |
| NEC Computers        | 4        | 1.29%   |
| Iiyama               | 4        | 1.29%   |
| Vizio                | 3        | 0.96%   |
| ViewSonic            | 3        | 0.96%   |
| Belinea              | 3        | 0.96%   |
| VIZTA                | 2        | 0.64%   |
| Toshiba              | 2        | 0.64%   |
| Sceptre              | 2        | 0.64%   |
| Mi                   | 2        | 0.64%   |
| LG Electronics       | 2        | 0.64%   |
| Insignia             | 2        | 0.64%   |
| VIZ                  | 1        | 0.32%   |
| Unknown              | 1        | 0.32%   |
| TMD                  | 1        | 0.32%   |
| Tech Concepts        | 1        | 0.32%   |
| TCL                  | 1        | 0.32%   |
| Sony                 | 1        | 0.32%   |
| SKG                  | 1        | 0.32%   |
| Sceptre Tech         | 1        | 0.32%   |
| RTK                  | 1        | 0.32%   |
| RGT                  | 1        | 0.32%   |
| Nixeus               | 1        | 0.32%   |
| MStar                | 1        | 0.32%   |
| Microstep            | 1        | 0.32%   |
| LBT                  | 1        | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                 | 4        | 1.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4        | 1.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 0.92%   |
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                  | 2        | 0.62%   |
| Samsung Electronics SyncMaster SAM0456 1360x768 410x230mm 18.5-inch  | 2        | 0.62%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 0.62%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 2        | 0.62%   |
| Philips PHL 244E5 PHLC0C0 1920x1080 527x296mm 23.8-inch              | 2        | 0.62%   |
| NEC Computers PA271W NEC67DA 2560x1440 596x335mm 26.9-inch           | 2        | 0.62%   |
| Lenovo LEN G32qc-10 LEN66A2 2560x1440 698x392mm 31.5-inch            | 2        | 0.62%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                  | 2        | 0.62%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2        | 0.62%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 2        | 0.62%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.62%   |
| Eizo S2202W ENC1975 1680x1050 474x297mm 22.0-inch                    | 2        | 0.62%   |
| Dell U2720QM DEL41BC 3840x2160 597x336mm 27.0-inch                   | 2        | 0.62%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                     | 2        | 0.62%   |
| Dell E1916H DELF065 1366x768 410x230mm 18.5-inch                     | 2        | 0.62%   |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                    | 2        | 0.62%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 2        | 0.62%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 2        | 0.62%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                     | 2        | 0.62%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch     | 2        | 0.62%   |
| VIZTA P241WDC JRY2150 1920x1080 409x330mm 20.7-inch                  | 1        | 0.31%   |
| VIZTA 27HQ CURVO JRY2700 1920x1080 698x393mm 31.5-inch               | 1        | 0.31%   |
| Vizio E601i-A3 VIZ0092 1920x1080 1329x748mm 60.0-inch                | 1        | 0.31%   |
| VIZ LCD Monitor D32f-E1 1920x1080                                    | 1        | 0.31%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 0.31%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 1        | 0.31%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch               | 1        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.31%   |
| Toshiba TV TSB0110 1920x1080 890x500mm 40.2-inch                     | 1        | 0.31%   |
| Toshiba TV TSB0104 720x576 1960x1420mm 95.3-inch                     | 1        | 0.31%   |
| TMD TMDTMD24S1 TMD2381 1920x1080 527x296mm 23.8-inch                 | 1        | 0.31%   |
| Tech Concepts LCD Monitor 43S451                                     | 1        | 0.31%   |
| TCL Beyond TV TCL9653 3840x2160 1210x680mm 54.6-inch                 | 1        | 0.31%   |
| Sony TV SNY7001 1920x1080                                            | 1        | 0.31%   |
| SKG PMO G340-CWQK SKG3418 3440x1440 810x350mm 34.7-inch              | 1        | 0.31%   |
| Sceptre Tech Sceptre F22 SPT08E3 1920x1080 475x267mm 21.5-inch       | 1        | 0.31%   |
| Sceptre LCD Monitor X24WG 9600x2160                                  | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 131      | 42.81%  |
| 3840x2160 (4K)     | 44       | 14.38%  |
| 2560x1440 (QHD)    | 23       | 7.52%   |
| 1680x1050 (WSXGA+) | 21       | 6.86%   |
| 1280x1024 (SXGA)   | 14       | 4.58%   |
| 1366x768 (WXGA)    | 12       | 3.92%   |
| 3440x1440          | 9        | 2.94%   |
| 1600x900 (HD+)     | 9        | 2.94%   |
| Unknown            | 8        | 2.61%   |
| 1920x1200 (WUXGA)  | 7        | 2.29%   |
| 1440x900 (WXGA+)   | 6        | 1.96%   |
| 3840x1080          | 5        | 1.63%   |
| 2560x1080          | 4        | 1.31%   |
| 1360x768           | 4        | 1.31%   |
| 1920x540           | 2        | 0.65%   |
| 9600x2160          | 1        | 0.33%   |
| 4480x1440          | 1        | 0.33%   |
| 3840x1600          | 1        | 0.33%   |
| 2560x1600          | 1        | 0.33%   |
| 2560x1024          | 1        | 0.33%   |
| 1600x1200          | 1        | 0.33%   |
| 1280x720 (HD)      | 1        | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 48       | 15.64%  |
| 24      | 40       | 13.03%  |
| 23      | 34       | 11.07%  |
| Unknown | 23       | 7.49%   |
| 21      | 22       | 7.17%   |
| 22      | 20       | 6.51%   |
| 31      | 18       | 5.86%   |
| 19      | 18       | 5.86%   |
| 34      | 15       | 4.89%   |
| 18      | 13       | 4.23%   |
| 20      | 9        | 2.93%   |
| 32      | 6        | 1.95%   |
| 17      | 6        | 1.95%   |
| 54      | 5        | 1.63%   |
| 84      | 3        | 0.98%   |
| 72      | 3        | 0.98%   |
| 49      | 3        | 0.98%   |
| 26      | 3        | 0.98%   |
| 63      | 2        | 0.65%   |
| 42      | 2        | 0.65%   |
| 40      | 2        | 0.65%   |
| 15      | 2        | 0.65%   |
| 95      | 1        | 0.33%   |
| 86      | 1        | 0.33%   |
| 60      | 1        | 0.33%   |
| 52      | 1        | 0.33%   |
| 50      | 1        | 0.33%   |
| 46      | 1        | 0.33%   |
| 38      | 1        | 0.33%   |
| 37      | 1        | 0.33%   |
| 30      | 1        | 0.33%   |
| 16      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 113      | 37.67%  |
| 401-500     | 73       | 24.33%  |
| 601-700     | 25       | 8.33%   |
| Unknown     | 23       | 7.67%   |
| 701-800     | 20       | 6.67%   |
| 1001-1500   | 14       | 4.67%   |
| 351-400     | 9        | 3%      |
| 301-350     | 8        | 2.67%   |
| 1501-2000   | 8        | 2.67%   |
| 801-900     | 5        | 1.67%   |
| 901-1000    | 2        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 196      | 67.35%  |
| 16/10   | 41       | 14.09%  |
| Unknown | 21       | 7.22%   |
| 21/9    | 16       | 5.5%    |
| 5/4     | 14       | 4.81%   |
| 4/3     | 2        | 0.69%   |
| 3/2     | 1        | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 86       | 29.05%  |
| 301-350        | 49       | 16.55%  |
| 351-500        | 40       | 13.51%  |
| 151-200        | 34       | 11.49%  |
| Unknown        | 23       | 7.77%   |
| More than 1000 | 21       | 7.09%   |
| 141-150        | 18       | 6.08%   |
| 251-300        | 15       | 5.07%   |
| 501-1000       | 7        | 2.36%   |
| 111-120        | 1        | 0.34%   |
| 101-110        | 1        | 0.34%   |
| 91-100         | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 179      | 62.15%  |
| 101-120 | 53       | 18.4%   |
| Unknown | 23       | 7.99%   |
| 1-50    | 15       | 5.21%   |
| 121-160 | 13       | 4.51%   |
| 161-240 | 5        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 249      | 84.12%  |
| 2     | 35       | 11.82%  |
| 0     | 7        | 2.36%   |
| 3     | 3        | 1.01%   |
| 4     | 2        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 184      | 44.44%  |
| Intel                            | 124      | 29.95%  |
| Qualcomm Atheros                 | 22       | 5.31%   |
| MediaTek                         | 16       | 3.86%   |
| TP-Link                          | 14       | 3.38%   |
| Broadcom                         | 14       | 3.38%   |
| Ralink Technology                | 9        | 2.17%   |
| Nvidia                           | 4        | 0.97%   |
| Ralink                           | 3        | 0.72%   |
| ASIX Electronics                 | 3        | 0.72%   |
| VIA Technologies                 | 2        | 0.48%   |
| Microsoft                        | 2        | 0.48%   |
| Marvell Technology Group         | 2        | 0.48%   |
| Xiaomi                           | 1        | 0.24%   |
| Silicon Integrated Systems [SiS] | 1        | 0.24%   |
| Samsung Electronics              | 1        | 0.24%   |
| NetGear                          | 1        | 0.24%   |
| Mercucys                         | 1        | 0.24%   |
| Mellanox Technologies            | 1        | 0.24%   |
| IMC Networks                     | 1        | 0.24%   |
| Edimax Technology                | 1        | 0.24%   |
| D-Link System                    | 1        | 0.24%   |
| D-Link                           | 1        | 0.24%   |
| Chelsio Communications           | 1        | 0.24%   |
| Broadcom Limited                 | 1        | 0.24%   |
| Belkin Components                | 1        | 0.24%   |
| ASUSTek Computer                 | 1        | 0.24%   |
| Aquantia                         | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 121      | 24.74%  |
| Realtek RTL8125 2.5GbE Controller                                      | 34       | 6.95%   |
| Intel Ethernet Connection (2) I219-V                                   | 13       | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13       | 2.66%   |
| Intel Ethernet Connection I217-LM                                      | 12       | 2.45%   |
| Intel I211 Gigabit Network Connection                                  | 11       | 2.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10       | 2.04%   |
| Intel Wi-Fi 6 AX200                                                    | 9        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8        | 1.64%   |
| Intel Ethernet Controller I225-V                                       | 8        | 1.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7        | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7        | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7        | 1.43%   |
| Realtek 802.11ac NIC                                                   | 6        | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 6        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6        | 1.23%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 6        | 1.23%   |
| Ralink RT5370 Wireless Adapter                                         | 5        | 1.02%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 4        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4        | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 4        | 0.82%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 3        | 0.61%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 3        | 0.61%   |
| TP-Link 802.11ac WLAN Adapter                                          | 3        | 0.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3        | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 3        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 3        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                        | 3        | 0.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 3        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3        | 0.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 0.61%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.61%   |
| Intel Alder Lake-N PCH CNVi WiFi                                       | 3        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 46       | 29.87%  |
| Intel                 | 43       | 27.92%  |
| TP-Link               | 14       | 9.09%   |
| MediaTek              | 13       | 8.44%   |
| Qualcomm Atheros      | 11       | 7.14%   |
| Ralink Technology     | 9        | 5.84%   |
| Broadcom              | 7        | 4.55%   |
| Ralink                | 3        | 1.95%   |
| Microsoft             | 2        | 1.3%    |
| NetGear               | 1        | 0.65%   |
| Mercucys              | 1        | 0.65%   |
| IMC Networks          | 1        | 0.65%   |
| Edimax Technology     | 1        | 0.65%   |
| D-Link                | 1        | 0.65%   |
| ASUSTek Computer      | 1        | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10       | 6.37%   |
| Intel Wi-Fi 6 AX200                                            | 9        | 5.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8        | 5.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7        | 4.46%   |
| Realtek 802.11ac NIC                                           | 6        | 3.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 3.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 3.82%   |
| Intel 700 Series Chipset CNVi WiFi                             | 6        | 3.82%   |
| Ralink RT5370 Wireless Adapter                                 | 5        | 3.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 4        | 2.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 2.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4        | 2.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3        | 1.91%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                          | 3        | 1.91%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.91%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 3        | 1.91%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.91%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 1.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3        | 1.91%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3        | 1.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 1.27%   |
| Realtek 802.11ac WLAN Adapter                                  | 2        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 1.27%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2        | 1.27%   |
| Intel Wireless 7260                                            | 2        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 1.27%   |
| Intel Alder Lake-N PCH CNVi WiFi                               | 2        | 1.27%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 0.64%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.64%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter       | 1        | 0.64%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 1        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 0.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 0.64%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 169      | 53.31%  |
| Intel                            | 103      | 32.49%  |
| Qualcomm Atheros                 | 12       | 3.79%   |
| Broadcom                         | 10       | 3.15%   |
| Nvidia                           | 4        | 1.26%   |
| MediaTek                         | 3        | 0.95%   |
| ASIX Electronics                 | 3        | 0.95%   |
| VIA Technologies                 | 2        | 0.63%   |
| Marvell Technology Group         | 2        | 0.63%   |
| Xiaomi                           | 1        | 0.32%   |
| Silicon Integrated Systems [SiS] | 1        | 0.32%   |
| Samsung Electronics              | 1        | 0.32%   |
| Mellanox Technologies            | 1        | 0.32%   |
| D-Link System                    | 1        | 0.32%   |
| Chelsio Communications           | 1        | 0.32%   |
| Broadcom Limited                 | 1        | 0.32%   |
| Belkin Components                | 1        | 0.32%   |
| Aquantia                         | 1        | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 121      | 36.45%  |
| Realtek RTL8125 2.5GbE Controller                                      | 34       | 10.24%  |
| Intel Ethernet Connection (2) I219-V                                   | 13       | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13       | 3.92%   |
| Intel Ethernet Connection I217-LM                                      | 12       | 3.61%   |
| Intel I211 Gigabit Network Connection                                  | 11       | 3.31%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7        | 2.11%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4        | 1.2%    |
| Intel Ethernet Connection I217-V                                       | 4        | 1.2%    |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.9%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 3        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3        | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3        | 0.9%    |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 3        | 0.9%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.6%    |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.6%    |
| Intel Ethernet Controller I226-V                                       | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.6%    |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.6%    |
| Intel Ethernet Connection (10) I219-V                                  | 2        | 0.6%    |
| Intel 82566DC-2 Gigabit Network Connection                             | 2        | 0.6%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 2        | 0.6%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 2        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 2        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.3%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.3%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.3%    |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter               | 1        | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 290      | 67.13%  |
| WiFi     | 142      | 32.87%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 239      | 78.88%  |
| WiFi     | 64       | 21.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 175      | 59.12%  |
| 2     | 104      | 35.14%  |
| 3     | 15       | 5.07%   |
| 7     | 1        | 0.34%   |
| 0     | 1        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 192      | 64%     |
| Yes  | 108      | 36%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 34.88%  |
| Realtek Semiconductor           | 19       | 14.73%  |
| Cambridge Silicon Radio         | 19       | 14.73%  |
| MediaTek                        | 12       | 9.3%    |
| IMC Networks                    | 11       | 8.53%   |
| Broadcom                        | 4        | 3.1%    |
| Apple                           | 4        | 3.1%    |
| Integrated System Solution      | 3        | 2.33%   |
| ASUSTek Computer                | 3        | 2.33%   |
| TP-Link                         | 2        | 1.55%   |
| Qualcomm Atheros Communications | 2        | 1.55%   |
| Logitech                        | 1        | 0.78%   |
| Edimax Technology               | 1        | 0.78%   |
| Dynex                           | 1        | 0.78%   |
| Dell                            | 1        | 0.78%   |
| Unknown                         | 1        | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 19       | 14.73%  |
| Realtek Bluetooth Radio                                  | 15       | 11.63%  |
| MediaTek Wireless_Device                                 | 12       | 9.3%    |
| Intel AX210 Bluetooth                                    | 9        | 6.98%   |
| Intel AX200 Bluetooth                                    | 9        | 6.98%   |
| Intel Bluetooth Device                                   | 8        | 6.2%    |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 4.65%   |
| IMC Networks Wireless_Device                             | 5        | 3.88%   |
| IMC Networks Bluetooth Radio                             | 5        | 3.88%   |
| Intel Bluetooth wireless interface                       | 4        | 3.1%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 4        | 3.1%    |
| Apple Bluetooth Host Controller                          | 4        | 3.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3        | 2.33%   |
| TP-Link TP-T@- UB500 Adapter                             | 2        | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 1.55%   |
| Intel AX201 Bluetooth                                    | 2        | 1.55%   |
| Integrated System Solution Bluetooth Device              | 2        | 1.55%   |
| ASUS ASUS USB-BT500                                      | 2        | 1.55%   |
| Realtek Bluetooth 5.3 Radio                              | 1        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                            | 1        | 0.78%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.78%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 1        | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.78%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.78%   |
| IMC Networks Bluetooth Device                            | 1        | 0.78%   |
| Edimax Bluetooth Device                                  | 1        | 0.78%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.78%   |
| Dell BT Mini-Receiver                                    | 1        | 0.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.78%   |
| Unknown                                                  | 1        | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 185      | 36.13%  |
| AMD                                          | 135      | 26.37%  |
| Nvidia                                       | 105      | 20.51%  |
| C-Media Electronics                          | 12       | 2.34%   |
| Creative Technology                          | 9        | 1.76%   |
| Creative Labs                                | 8        | 1.56%   |
| Logitech                                     | 5        | 0.98%   |
| Micro Star International                     | 4        | 0.78%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.59%   |
| VIA Technologies                             | 3        | 0.59%   |
| JMTek                                        | 3        | 0.59%   |
| GN Netcom                                    | 3        | 0.59%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.39%   |
| Texas Instruments                            | 2        | 0.39%   |
| Mark of the Unicorn                          | 2        | 0.39%   |
| Jieli Technology                             | 2        | 0.39%   |
| Hewlett-Packard                              | 2        | 0.39%   |
| Generalplus Technology                       | 2        | 0.39%   |
| BEHRINGER International                      | 2        | 0.39%   |
| ASRock                                       | 2        | 0.39%   |
| ZOOM                                         | 1        | 0.2%    |
| XMOS                                         | 1        | 0.2%    |
| Tenx Technology                              | 1        | 0.2%    |
| Silicon Integrated Systems [SiS]             | 1        | 0.2%    |
| Samson Technologies                          | 1        | 0.2%    |
| Realtek Semiconductor                        | 1        | 0.2%    |
| Razer USA                                    | 1        | 0.2%    |
| Kingston Technology                          | 1        | 0.2%    |
| JBL                                          | 1        | 0.2%    |
| Guillemot                                    | 1        | 0.2%    |
| Google                                       | 1        | 0.2%    |
| Focusrite-Novation                           | 1        | 0.2%    |
| Earth Computer Technologies                  | 1        | 0.2%    |
| DSEA A/S                                     | 1        | 0.2%    |
| Bluetrum                                     | 1        | 0.2%    |
| Blue Microphones                             | 1        | 0.2%    |
| ASUSTek Computer                             | 1        | 0.2%    |
| Asahi Kasei Microsystems                     | 1        | 0.2%    |
| Apple                                        | 1        | 0.2%    |
| Altec Lansing Technologies                   | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                                     | 43       | 7.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 25       | 4.12%   |
| AMD Starship/Matisse HD Audio Controller                                          | 22       | 3.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 19       | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 19       | 3.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 19       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 18       | 2.97%   |
| AMD Radeon High Definition Audio Controller                                       | 18       | 2.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 17       | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 2.31%   |
| Intel 200 Series PCH HD Audio                                                     | 13       | 2.14%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 13       | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 11       | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 11       | 1.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 10       | 1.65%   |
| Intel Raptor Lake High Definition Audio Controller                                | 10       | 1.65%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 10       | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                        | 9        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 8        | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                                     | 7        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7        | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 1.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                | 6        | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 0.82%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5        | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5        | 0.82%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 5        | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 0.82%   |
| Nvidia GP102 HDMI Audio Controller                                                | 4        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 0.66%   |
| Micro Star International USB Audio                                                | 4        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 40       | 20.62%  |
| Corsair             | 27       | 13.92%  |
| Samsung Electronics | 23       | 11.86%  |
| G.Skill             | 22       | 11.34%  |
| Unknown             | 18       | 9.28%   |
| SK hynix            | 16       | 8.25%   |
| Crucial             | 12       | 6.19%   |
| Micron Technology   | 8        | 4.12%   |
| Unknown             | 5        | 2.58%   |
| Team                | 3        | 1.55%   |
| Patriot             | 3        | 1.55%   |
| Ramaxel Technology  | 2        | 1.03%   |
| Nanya Technology    | 2        | 1.03%   |
| Unknown (ABCD)      | 1        | 0.52%   |
| Unknown (87CE)      | 1        | 0.52%   |
| Unknown (0x0E9D)    | 1        | 0.52%   |
| Unknown (0x0CC7)    | 1        | 0.52%   |
| Unknown (0x0B45)    | 1        | 0.52%   |
| Transcend           | 1        | 0.52%   |
| Qimonda             | 1        | 0.52%   |
| PNY                 | 1        | 0.52%   |
| Mushkin             | 1        | 0.52%   |
| Lexar Co Limited    | 1        | 0.52%   |
| GeIL                | 1        | 0.52%   |
| Avant               | 1        | 0.52%   |
| Apacer              | 1        | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Unknown                                                            | 5        | 2.31%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s               | 4        | 1.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s              | 4        | 1.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 2        | 0.93%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                               | 2        | 0.93%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                               | 2        | 0.93%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s               | 2        | 0.93%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                | 2        | 0.93%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s                 | 2        | 0.93%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s               | 2        | 0.93%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s                | 2        | 0.93%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s                | 2        | 0.93%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3733MT/s              | 2        | 0.93%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s              | 2        | 0.93%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s              | 2        | 0.93%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6200MT/s               | 2        | 0.93%   |
| Crucial RAM CT16G56C46S5.M8B2 16GB SODIMM DDR5 5600MT/s            | 2        | 0.93%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s             | 2        | 0.93%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s              | 2        | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR 1333MT/s                           | 1        | 0.46%   |
| Unknown RAM Module 512MB DIMM                                      | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM                                        | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                          | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2                                   | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                            | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                           | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM                                        | 1        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s     | 1        | 0.46%   |
| Unknown (87CE) RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 0.46%   |
| Unknown (0x0E9D) RAM KINSOTIN16GB2666MHZ 16GB SODIMM DDR4 2667MT/s | 1        | 0.46%   |
| Unknown (0x0CC7) RAM DDR4 NB 8G 3200 8GB SODIMM DDR4 3200MT/s      | 1        | 0.46%   |
| Unknown (0x0B45) RAM WPBH32D416SWA-16G 16GB SODIMM DDR4 3200MT/s   | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 74       | 43.27%  |
| DDR3    | 46       | 26.9%   |
| DDR5    | 19       | 11.11%  |
| SDRAM   | 9        | 5.26%   |
| Unknown | 8        | 4.68%   |
| DDR2    | 7        | 4.09%   |
| LPDDR5  | 4        | 2.34%   |
| DDR     | 3        | 1.75%   |
| LPDDR4  | 1        | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 139      | 84.76%  |
| SODIMM       | 22       | 13.41%  |
| Row Of Chips | 2        | 1.22%   |
| RIMM         | 1        | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 63       | 34.62%  |
| 16384 | 40       | 21.98%  |
| 4096  | 33       | 18.13%  |
| 2048  | 24       | 13.19%  |
| 32768 | 14       | 7.69%   |
| 1024  | 4        | 2.2%    |
| 49152 | 2        | 1.1%    |
| 512   | 2        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 12.3%   |
| 3200    | 20       | 10.7%   |
| 3600    | 17       | 9.09%   |
| 1333    | 14       | 7.49%   |
| 2667    | 11       | 5.88%   |
| 2133    | 9        | 4.81%   |
| 2400    | 8        | 4.28%   |
| 5600    | 7        | 3.74%   |
| 6000    | 6        | 3.21%   |
| 6400    | 5        | 2.67%   |
| 2800    | 5        | 2.67%   |
| Unknown | 5        | 2.67%   |
| 3733    | 4        | 2.14%   |
| 3400    | 4        | 2.14%   |
| 1867    | 4        | 2.14%   |
| 1866    | 4        | 2.14%   |
| 667     | 4        | 2.14%   |
| 6200    | 3        | 1.6%    |
| 3000    | 3        | 1.6%    |
| 1066    | 3        | 1.6%    |
| 800     | 3        | 1.6%    |
| 2666    | 2        | 1.07%   |
| 2448    | 2        | 1.07%   |
| 1800    | 2        | 1.07%   |
| 533     | 2        | 1.07%   |
| 8400    | 1        | 0.53%   |
| 7200    | 1        | 0.53%   |
| 4800    | 1        | 0.53%   |
| 4000    | 1        | 0.53%   |
| 3500    | 1        | 0.53%   |
| 3466    | 1        | 0.53%   |
| 3333    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 2934    | 1        | 0.53%   |
| 2933    | 1        | 0.53%   |
| 2048    | 1        | 0.53%   |
| 2000    | 1        | 0.53%   |
| 1648    | 1        | 0.53%   |
| 1639    | 1        | 0.53%   |
| 1334    | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 10       | 52.63%  |
| Seiko Epson           | 3        | 15.79%  |
| Canon                 | 3        | 15.79%  |
| Lexmark International | 2        | 10.53%  |
| Brother Industries    | 1        | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP ENVY 5000 series                    | 2        | 10.53%  |
| Seiko Epson L210 Series                | 1        | 5.26%   |
| Seiko Epson L1250 Series               | 1        | 5.26%   |
| Seiko Epson ET-2820 Series             | 1        | 5.26%   |
| Lexmark International Printing Support | 1        | 5.26%   |
| Lexmark International MX310dn          | 1        | 5.26%   |
| HP OfficeJet Pro 7740 series           | 1        | 5.26%   |
| HP LaserJet P2015 series               | 1        | 5.26%   |
| HP LaserJet P1005                      | 1        | 5.26%   |
| HP LaserJet M14-M17                    | 1        | 5.26%   |
| HP HP LaserJet Pro M404-M405           | 1        | 5.26%   |
| HP ENVY 4520 series                    | 1        | 5.26%   |
| HP DeskJet F4200 series                | 1        | 5.26%   |
| HP Color LaserJet CP2025dn             | 1        | 5.26%   |
| Canon TS9100 series                    | 1        | 5.26%   |
| Canon LiDE 300                         | 1        | 5.26%   |
| Canon D570 UFRII LT                    | 1        | 5.26%   |
| Brother MFC-T4500DW                    | 1        | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 50%     |
| Canon CanoScan LiDE 210                     | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 38.64%  |
| Microdia                      | 6        | 13.64%  |
| Microsoft                     | 4        | 9.09%   |
| MacroSilicon                  | 3        | 6.82%   |
| Sunplus Innovation Technology | 2        | 4.55%   |
| Apple                         | 2        | 4.55%   |
| Web Camera                    | 1        | 2.27%   |
| Samsung Electronics           | 1        | 2.27%   |
| OmniVision Technologies       | 1        | 2.27%   |
| Magic Control Technology      | 1        | 2.27%   |
| KYE Systems (Mouse Systems)   | 1        | 2.27%   |
| Jieli Technology              | 1        | 2.27%   |
| Generalplus Technology        | 1        | 2.27%   |
| Elgato Systems                | 1        | 2.27%   |
| Chicony Electronics           | 1        | 2.27%   |
| AVerMedia Technologies        | 1        | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                    | 3        | 6.67%   |
| Microdia USB 2.0 Camera                        | 2        | 4.44%   |
| MacroSilicon USB Video                         | 2        | 4.44%   |
| Logitech Webcam C270                           | 2        | 4.44%   |
| Logitech HD Webcam C615                        | 2        | 4.44%   |
| Logitech HD Webcam C525                        | 2        | 4.44%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 4.44%   |
| Web Camera Web Camera                          | 1        | 2.22%   |
| Sunplus Integrated Camera                      | 1        | 2.22%   |
| Sunplus Full HD webcam                         | 1        | 2.22%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 2.22%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 2.22%   |
| Microsoft Microsoft LifeCam Cinema             | 1        | 2.22%   |
| Microsoft LifeCam VX-700                       | 1        | 2.22%   |
| Microsoft LifeCam Studio                       | 1        | 2.22%   |
| Microsoft LifeCam HD-3000                      | 1        | 2.22%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 2.22%   |
| Microdia Rapoo Camera                          | 1        | 2.22%   |
| Microdia Camera                                | 1        | 2.22%   |
| Microdia ACR010 USB Webcam                     | 1        | 2.22%   |
| Magic Control j5 WebCam JVCU100                | 1        | 2.22%   |
| MacroSilicon ClearClick                        | 1        | 2.22%   |
| Logitech Webcam C310                           | 1        | 2.22%   |
| Logitech Webcam C170                           | 1        | 2.22%   |
| Logitech Portable Webcam C905                  | 1        | 2.22%   |
| Logitech CrystalCam                            | 1        | 2.22%   |
| Logitech C922 Pro Stream Webcam                | 1        | 2.22%   |
| Logitech C920 PRO HD Webcam                    | 1        | 2.22%   |
| KYE Systems (Mouse Systems) Genius FaceCam 312 | 1        | 2.22%   |
| Jieli USB PHY 2.0                              | 1        | 2.22%   |
| Generalplus GENERAL WEBCAM                     | 1        | 2.22%   |
| Elgato Systems Elgato HD60 X                   | 1        | 2.22%   |
| Elgato Systems Elgato Facecam                  | 1        | 2.22%   |
| Chicony HP 0.3MP Webcam                        | 1        | 2.22%   |
| AVerMedia Live Gamer Mini                      | 1        | 2.22%   |
| Apple iSight in LED Cinema Display             | 1        | 2.22%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 50%     |
| AuthenTec             | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 50%     |
| AuthenTec AES3500 TruePrint Sensor        | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Swissbit    | 1        | 33.33%  |
| OmniKey     | 1        | 33.33%  |
| Alcor Micro | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Swissbit iShield Key FIDO2          | 1        | 33.33%  |
| OmniKey 3x21 Smart Card Reader      | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 245      | 81.4%   |
| 1     | 51       | 16.94%  |
| 2     | 5        | 1.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 25       | 43.1%   |
| Graphics card            | 14       | 24.14%  |
| Unassigned class         | 4        | 6.9%    |
| Communication controller | 4        | 6.9%    |
| Multimedia controller    | 2        | 3.45%   |
| Fingerprint reader       | 2        | 3.45%   |
| Chipcard                 | 2        | 3.45%   |
| Sound                    | 1        | 1.72%   |
| Network                  | 1        | 1.72%   |
| Dvb card                 | 1        | 1.72%   |
| Card reader              | 1        | 1.72%   |
| Camera                   | 1        | 1.72%   |

