EndeavourOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

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

Total: 271

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI        | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte   | P55A-UD3                    | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| HP         | 18E7                        | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek    | Maximus IX HERO             | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock     | B550M Pro4                  | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| MSI        | A320M PRO-E                 | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| ASUSTek    | PRIME X570-P                | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| AZW        | U59                         | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Gigabyte   | B550M AORUS PRO             | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| ASRock     | A320M-HDV R4.0              | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| MSI        | PRO Z690-A WIFI             | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte   | Z690 GAMING X DDR4          | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| ASUSTek    | TUF Gaming B550-PRO         | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Samsung    | DeskTop System              | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung    | DeskTop System              | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| ASUSTek    | TUF B450-PLUS GAMING        | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Gigabyte   | B550 AORUS ELITE            | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte   | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP         | 158B                        | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| Gigabyte   | N3160TN                     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte   | P55A-UD3                    | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock     | B450M Pro4                  | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| ASUSTek    | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI        | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| ASUSTek    | P8Z77-V                     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell       | 040DDP A01                  | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI        | B450 GAMING PRO CARBON A... | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Gigabyte   | B550M AORUS PRO-P           | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| ASUSTek    | SABERTOOTH X99              | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek    | H110M-E/M.2                 | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASRock     | B450 Pro4                   | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Gigabyte   | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte   | B550M AORUS PRO             | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell       | 0K240Y A01                  | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| HP         | 0A08h                       | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP         | 0A08h                       | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| ASRock     | A320M/ac                    | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP         | 3647h                       | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP         | 8906 SMVB                   | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI        | B75MA-E33                   | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASUSTek    | P8H77-M                     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock     | B450 Pro4                   | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock     | B450 Pro4                   | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock     | AB350M Pro4                 | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte   | P55A-UD3                    | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock     | B450M Pro4                  | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| ASUSTek    | TUF B450-PRO GAMING         | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek    | TUF B450-PRO GAMING         | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte   | B450M DS3H-CF               | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| ASRock     | B560 Pro4                   | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| ASUSTek    | PRIME H410M-E               | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| Gigabyte   | Z390 AORUS PRO-CF           | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte   | B450 AORUS ELITE            | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| ASRock     | B560 Pro4                   | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| Dell       | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| ASUSTek    | PRIME Z390-A                | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASRock     | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek    | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte   | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Lenovo     | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASUSTek    | STRIX Z270F GAMING          | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Dell       | 0JP3NX A01                  | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte   | P55A-UD3                    | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock     | B450M Pro4                  | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| MSI        | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell       | 0KWVT8 A03                  | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| ASRock     | B450M Pro4                  | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock     | B450M Pro4                  | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| Gigabyte   | B450 AORUS ELITE            | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| ASUSTek    | TUF Gaming X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| HP         | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASUSTek    | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| MSI        | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| ASRock     | A320M-HD                    | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| MSI        | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| ASUSTek    | TUF Gaming B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock     | B550M Steel Legend          | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| MSI        | Z170A GAMING M3             | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| MSI        | X370 XPOWER GAMING TITAN... | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| Gigabyte   | TRX40 AORUS MASTER          | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| ASUSTek    | Maximus VII GENE            | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock     | FM2A88X Pro3+               | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| Dell       | 0K240Y A01                  | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| MSI        | Z97 PC Mate                 | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek    | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek    | P8Z77-V LX                  | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Gigabyte   | B550 AORUS ELITE V2         | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI        | Z490-A PRO                  | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Positivo   | POS-PIH81DI                 | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| ASUSTek    | Z97-A                       | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Gigabyte   | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock     | B450 Steel Legend           | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| LattePanda | Alpha                       | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar    | G31-M7 TE                   | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda | Alpha                       | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte   | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Acer       | Aspire XC-1660G V:1.1       | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| Gigabyte   | H110N-CF                    | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| MSI        | Z87-G41 PC Mate             | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| Unknown    | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell       | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek    | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte   | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| MSI        | B350 PC MATE                | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Gigabyte   | B560M DS3H                  | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| ASUSTek    | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte   | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| Gigabyte   | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek    | Maximus VIII HERO           | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| ASRock     | H310CM-DVS                  | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock     | H310CM-DVS                  | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| Gigabyte   | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock     | B550M Pro4                  | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| UMAX       | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte   | B85M-HD3                    | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Gigabyte   | B550 VISION D               | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| MSI        | G41M-P33 Combo              | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte   | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Gigabyte   | H110M-S2-CF                 | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Gigabyte   | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte   | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| MSI        | B450M PRO-VDH MAX           | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| MSI        | B450-A PRO MAX              | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| Intel      | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP         | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte   | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI        | B450M PRO-VDH MAX           | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell       | 0K240Y A01                  | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte   | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte   | GA-78LMT-S2P                | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek    | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| Gigabyte   | Z97X-Gaming 5               | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| ASUSTek    | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte   | B550 AORUS ELITE V2         | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| HP         | 2B36                        | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| ASRock     | A300M-STX                   | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| ASUSTek    | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo     | SHARKBAY NOK                | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte   | B550M AORUS PRO             | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Gigabyte   | B450 AORUS M                | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Dell       | 0080PM A00                  | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo     | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Samsung    | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Gigabyte   | B550M AORUS PRO             | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| MSI        | Z87-G45 GAMING              | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| MSI        | Z87-G45 GAMING              | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock     | B550 Phantom Gaming 4       | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek    | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| ASRock     | B550M Steel Legend          | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| ASUSTek    | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Gigabyte   | X58A-UD3R                   | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek    | Z87-PRO                     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek    | Maximus VIII HERO           | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek    | Maximus VIII HERO           | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| HP         | 1905                        | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| Gigabyte   | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| Gigabyte   | X58A-UD3R                   | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek    | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Lenovo     | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Dell       | 0KRC95 A02                  | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| ASRock     | Z77 Extreme4                | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock     | Z77 Extreme4                | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell       | 0KRC95 A02                  | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Gigabyte   | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP         | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP         | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| Dell       | 0G214D A00                  | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| MSI        | MS-7366                     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell       | 096JG8 A01                  | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| MSI        | B450 TOMAHAWK MAX           | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek    | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| MSI        | MS-7366                     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte   | B450 AORUS M                | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte   | B550M AORUS PRO             | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP         | 1497                        | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Gigabyte   | B550M AORUS PRO             | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASRock     | X470 Gaming-ITX/ac          | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek    | M5A97 R2.0                  | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte   | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| ASUSTek    | Z87M-PLUS                   | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek    | PRIME X570-P                | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Gigabyte   | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu    | D2618-C1 S26361-D2618-C1    | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo     | MAHOBAY NOK                 | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek    | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI        | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte   | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI        | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar    | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte   | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek    | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte   | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek    | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek    | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek    | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek    | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| EndeavourOS Rolling | 143      | 72.59%  |
| EndeavourOS         | 54       | 27.41%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 196      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.12-arch1-1      | 10       | 4.39%   |
| 5.7.7-arch1-1        | 6        | 2.63%   |
| 5.17.5-arch1-1       | 5        | 2.19%   |
| 5.17.1-arch1-1       | 5        | 2.19%   |
| 5.16.2-arch1-1       | 5        | 2.19%   |
| 5.18.12-arch1-1      | 4        | 1.75%   |
| 5.15.7-arch1-1       | 4        | 1.75%   |
| 5.11.11-arch1-1      | 4        | 1.75%   |
| 5.18.7-arch1-1       | 3        | 1.32%   |
| 5.18.5-arch1-1       | 3        | 1.32%   |
| 5.17.9-arch1-1       | 3        | 1.32%   |
| 5.16.16-arch1-1      | 3        | 1.32%   |
| 5.16.10-arch1-1      | 3        | 1.32%   |
| 5.15.8-arch1-1       | 3        | 1.32%   |
| 5.15.12-zen1-1-zen   | 3        | 1.32%   |
| 5.15.10-arch1-1      | 3        | 1.32%   |
| 5.14.9-arch2-1       | 3        | 1.32%   |
| 5.14.8-arch1-1       | 3        | 1.32%   |
| 5.10.88-2-lts        | 3        | 1.32%   |
| 5.9.14-arch1-1       | 2        | 0.88%   |
| 5.9.12-arch1-1       | 2        | 0.88%   |
| 5.9.1-arch1-1        | 2        | 0.88%   |
| 5.8.11-arch1-1       | 2        | 0.88%   |
| 5.8.10-arch1-1       | 2        | 0.88%   |
| 5.18.9-arch1-1       | 2        | 0.88%   |
| 5.18.6-arch1-1       | 2        | 0.88%   |
| 5.17.8-arch1-1       | 2        | 0.88%   |
| 5.17.5-zen1-1-zen    | 2        | 0.88%   |
| 5.16.16-zen1-1-zen   | 2        | 0.88%   |
| 5.16.11-arch1-1      | 2        | 0.88%   |
| 5.16.1-arch1-1       | 2        | 0.88%   |
| 5.15.13-zen1-1-zen   | 2        | 0.88%   |
| 5.14.2-arch1-2       | 2        | 0.88%   |
| 5.14.16-arch1-1      | 2        | 0.88%   |
| 5.12.15-arch1-1      | 2        | 0.88%   |
| 5.11.6-arch1-1       | 2        | 0.88%   |
| 5.11.15-arch1-2      | 2        | 0.88%   |
| 5.11.13-arch1-1      | 2        | 0.88%   |
| 5.9.9-arch1-1        | 1        | 0.44%   |
| 5.9.8-zen1-1-zen     | 1        | 0.44%   |
| 5.9.6-zen1-1-zen     | 1        | 0.44%   |
| 5.9.2-arch1-1        | 1        | 0.44%   |
| 5.9.10-arch1-1       | 1        | 0.44%   |
| 5.9.1-6-tkg-bmq      | 1        | 0.44%   |
| 5.9.0-rc3-1-mainline | 1        | 0.44%   |
| 5.8.8-arch1-1        | 1        | 0.44%   |
| 5.8.5-zen1-1-zen     | 1        | 0.44%   |
| 5.8.5-arch1-1        | 1        | 0.44%   |
| 5.8.5-8-tkg-pds      | 1        | 0.44%   |
| 5.8.5-8-tkg-bmq      | 1        | 0.44%   |
| 5.8.12-arch1-1       | 1        | 0.44%   |
| 5.7.8-arch1-1        | 1        | 0.44%   |
| 5.7.6-arch1-1        | 1        | 0.44%   |
| 5.7.12-zen1-1-zen    | 1        | 0.44%   |
| 5.7.12-arch1-1       | 1        | 0.44%   |
| 5.6.6-arch1-1        | 1        | 0.44%   |
| 5.6.15-arch1-1       | 1        | 0.44%   |
| 5.6.10-arch1-1       | 1        | 0.44%   |
| 5.5.4-zen1-1-zen     | 1        | 0.44%   |
| 5.5.2-arch2-2        | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 6.14%   |
| 5.17.5  | 7        | 3.07%   |
| 5.7.7   | 6        | 2.63%   |
| 5.18.12 | 5        | 2.19%   |
| 5.17.1  | 5        | 2.19%   |
| 5.16.2  | 5        | 2.19%   |
| 5.16.16 | 5        | 2.19%   |
| 5.15.7  | 5        | 2.19%   |
| 5.8.5   | 4        | 1.75%   |
| 5.18.5  | 4        | 1.75%   |
| 5.17.9  | 4        | 1.75%   |
| 5.11.11 | 4        | 1.75%   |
| 5.10.88 | 4        | 1.75%   |
| 5.9.1   | 3        | 1.32%   |
| 5.18.7  | 3        | 1.32%   |
| 5.16.11 | 3        | 1.32%   |
| 5.16.10 | 3        | 1.32%   |
| 5.15.8  | 3        | 1.32%   |
| 5.15.13 | 3        | 1.32%   |
| 5.15.10 | 3        | 1.32%   |
| 5.14.9  | 3        | 1.32%   |
| 5.14.8  | 3        | 1.32%   |
| 5.12.15 | 3        | 1.32%   |
| 5.9.14  | 2        | 0.88%   |
| 5.9.12  | 2        | 0.88%   |
| 5.8.11  | 2        | 0.88%   |
| 5.8.10  | 2        | 0.88%   |
| 5.7.12  | 2        | 0.88%   |
| 5.19.5  | 2        | 0.88%   |
| 5.18.9  | 2        | 0.88%   |
| 5.18.6  | 2        | 0.88%   |
| 5.18.16 | 2        | 0.88%   |
| 5.18.1  | 2        | 0.88%   |
| 5.17.8  | 2        | 0.88%   |
| 5.17.4  | 2        | 0.88%   |
| 5.16.4  | 2        | 0.88%   |
| 5.16.1  | 2        | 0.88%   |
| 5.15.11 | 2        | 0.88%   |
| 5.14.2  | 2        | 0.88%   |
| 5.14.16 | 2        | 0.88%   |
| 5.14.11 | 2        | 0.88%   |
| 5.13.13 | 2        | 0.88%   |
| 5.12.5  | 2        | 0.88%   |
| 5.12.4  | 2        | 0.88%   |
| 5.12.14 | 2        | 0.88%   |
| 5.11.6  | 2        | 0.88%   |
| 5.11.15 | 2        | 0.88%   |
| 5.11.13 | 2        | 0.88%   |
| 5.9.9   | 1        | 0.44%   |
| 5.9.8   | 1        | 0.44%   |
| 5.9.6   | 1        | 0.44%   |
| 5.9.2   | 1        | 0.44%   |
| 5.9.10  | 1        | 0.44%   |
| 5.9.0   | 1        | 0.44%   |
| 5.8.8   | 1        | 0.44%   |
| 5.8.12  | 1        | 0.44%   |
| 5.7.8   | 1        | 0.44%   |
| 5.7.6   | 1        | 0.44%   |
| 5.6.6   | 1        | 0.44%   |
| 5.6.15  | 1        | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 40       | 17.94%  |
| 5.18    | 26       | 11.66%  |
| 5.16    | 25       | 11.21%  |
| 5.17    | 21       | 9.42%   |
| 5.14    | 17       | 7.62%   |
| 5.10    | 15       | 6.73%   |
| 5.11    | 14       | 6.28%   |
| 5.9     | 13       | 5.83%   |
| 5.12    | 13       | 5.83%   |
| 5.8     | 10       | 4.48%   |
| 5.7     | 9        | 4.04%   |
| 5.13    | 7        | 3.14%   |
| 5.19    | 6        | 2.69%   |
| 5.6     | 3        | 1.35%   |
| 5.5     | 2        | 0.9%    |
| 5.4     | 1        | 0.45%   |
| Unknown | 1        | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 196      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 73       | 34.93%  |
| XFCE            | 40       | 19.14%  |
| GNOME           | 39       | 18.66%  |
| X-Cinnamon      | 13       | 6.22%   |
| KDE             | 11       | 5.26%   |
| i3              | 9        | 4.31%   |
| Budgie          | 6        | 2.87%   |
| Cinnamon        | 4        | 1.91%   |
| sway            | 3        | 1.44%   |
| LXQt            | 3        | 1.44%   |
| MATE            | 2        | 0.96%   |
| Unknown         | 2        | 0.96%   |
| jwm             | 1        | 0.48%   |
| herbstluftwm    | 1        | 0.48%   |
| GNOME Flashback | 1        | 0.48%   |
| awesome         | 1        | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 173      | 85.64%  |
| Wayland | 20       | 9.9%    |
| Tty     | 6        | 2.97%   |
| Unknown | 2        | 0.99%   |
| Web     | 1        | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 58       | 28.71%  |
| Unknown | 53       | 26.24%  |
| SDDM    | 50       | 24.75%  |
| GDM     | 21       | 10.4%   |
| TDM     | 20       | 9.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 94       | 47.72%  |
| de_DE   | 20       | 10.15%  |
| en_GB   | 13       | 6.6%    |
| it_IT   | 8        | 4.06%   |
| pl_PL   | 6        | 3.05%   |
| en_CA   | 6        | 3.05%   |
| ru_RU   | 5        | 2.54%   |
| en_AG   | 4        | 2.03%   |
| nl_NL   | 3        | 1.52%   |
| fr_FR   | 3        | 1.52%   |
| es_AR   | 3        | 1.52%   |
| en_DK   | 3        | 1.52%   |
| pt_BR   | 2        | 1.02%   |
| nl_BE   | 2        | 1.02%   |
| es_MX   | 2        | 1.02%   |
| en_IN   | 2        | 1.02%   |
| en_HK   | 2        | 1.02%   |
| en_AU   | 2        | 1.02%   |
| Unknown | 2        | 1.02%   |
| tr_TR   | 1        | 0.51%   |
| sv_SE   | 1        | 0.51%   |
| sl_SI   | 1        | 0.51%   |
| hu_HU   | 1        | 0.51%   |
| fr_CA   | 1        | 0.51%   |
| es_GT   | 1        | 0.51%   |
| es_ES   | 1        | 0.51%   |
| es_CR   | 1        | 0.51%   |
| eo      | 1        | 0.51%   |
| en_ZA   | 1        | 0.51%   |
| en_SG   | 1        | 0.51%   |
| en_FI   | 1        | 0.51%   |
| de_CH   | 1        | 0.51%   |
| de_AT   | 1        | 0.51%   |
| cs_CZ   | 1        | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 114      | 57.29%  |
| BIOS | 85       | 42.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 139      | 70.56%  |
| Btrfs   | 53       | 26.9%   |
| Overlay | 2        | 1.02%   |
| XXX4    | 1        | 0.51%   |
| Xfs     | 1        | 0.51%   |
| F2fs    | 1        | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 62.63%  |
| Unknown | 58       | 29.29%  |
| MBR     | 16       | 8.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 78.28%  |
| Yes       | 43       | 21.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 57.5%   |
| Yes       | 85       | 42.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 57       | 29.08%  |
| Gigabyte Technology | 45       | 22.96%  |
| MSI                 | 35       | 17.86%  |
| ASRock              | 20       | 10.2%   |
| Hewlett-Packard     | 11       | 5.61%   |
| Dell                | 9        | 4.59%   |
| Lenovo              | 6        | 3.06%   |
| Samsung Electronics | 2        | 1.02%   |
| Fujitsu             | 2        | 1.02%   |
| Biostar             | 2        | 1.02%   |
| UMAX                | 1        | 0.51%   |
| Positivo            | 1        | 0.51%   |
| LattePanda          | 1        | 0.51%   |
| Intel               | 1        | 0.51%   |
| AZW                 | 1        | 0.51%   |
| Acer                | 1        | 0.51%   |
| Unknown             | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C37                            | 6        | 3.06%   |
| ASUS All Series                        | 6        | 3.06%   |
| ASUS ROG STRIX X570-E GAMING           | 4        | 2.04%   |
| MSI MS-7C02                            | 3        | 1.53%   |
| MSI MS-7A38                            | 3        | 1.53%   |
| Gigabyte B550M AORUS PRO               | 3        | 1.53%   |
| ASUS TUF Gaming X570-PLUS              | 3        | 1.53%   |
| ASRock B450M Pro4                      | 3        | 1.53%   |
| MSI MS-7C91                            | 2        | 1.02%   |
| MSI MS-7C84                            | 2        | 1.02%   |
| MSI MS-7B86                            | 2        | 1.02%   |
| MSI MS-7850                            | 2        | 1.02%   |
| MSI MS-7798                            | 2        | 1.02%   |
| HP Z230 Tower Workstation              | 2        | 1.02%   |
| Gigabyte H110M-S2                      | 2        | 1.02%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 1.02%   |
| Gigabyte B450M DS3H                    | 2        | 1.02%   |
| Gigabyte B450 AORUS ELITE              | 2        | 1.02%   |
| Dell OptiPlex 3020                     | 2        | 1.02%   |
| Biostar G31-M7 TE                      | 2        | 1.02%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 2        | 1.02%   |
| ASUS PRIME X570-P                      | 2        | 1.02%   |
| ASUS K30AD_M31AD_M51AD                 | 2        | 1.02%   |
| ASRock B550M Steel Legend              | 2        | 1.02%   |
| ASRock B550M Pro4                      | 2        | 1.02%   |
| ASRock B450 Pro4                       | 2        | 1.02%   |
| UMAX J42 Nano                          | 1        | 0.51%   |
| Samsung DeskTop System                 | 1        | 0.51%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.51%   |
| Positivo POS-PIH81DI                   | 1        | 0.51%   |
| MSI MS-7D25                            | 1        | 0.51%   |
| MSI MS-7C75                            | 1        | 0.51%   |
| MSI MS-7B85                            | 1        | 0.51%   |
| MSI MS-7A34                            | 1        | 0.51%   |
| MSI MS-7A32                            | 1        | 0.51%   |
| MSI MS-7A31                            | 1        | 0.51%   |
| MSI MS-7994                            | 1        | 0.51%   |
| MSI MS-7978                            | 1        | 0.51%   |
| MSI MS-7821                            | 1        | 0.51%   |
| MSI MS-7808                            | 1        | 0.51%   |
| MSI MS-7592                            | 1        | 0.51%   |
| MSI MS-7366                            | 1        | 0.51%   |
| MSI Hyrican PC A320M PRO-E             | 1        | 0.51%   |
| Lenovo ThinkStation C20 426593U        | 1        | 0.51%   |
| Lenovo ThinkCentre M93p 10AAS03T00     | 1        | 0.51%   |
| Lenovo ThinkCentre M92p 32383L6        | 1        | 0.51%   |
| Lenovo ThinkCentre M710q 10MR0009US    | 1        | 0.51%   |
| Lenovo IdeaCentre 510-15ICB 90HU002QGE | 1        | 0.51%   |
| Lenovo IdeaCentre 510-15ICB 90HU002JSP | 1        | 0.51%   |
| LattePanda Alpha                       | 1        | 0.51%   |
| Intel DH55HC AAE70933-504              | 1        | 0.51%   |
| HP Z820 Workstation                    | 1        | 0.51%   |
| HP Z2 Tower G4 Workstation             | 1        | 0.51%   |
| HP xw8400 Workstation                  | 1        | 0.51%   |
| HP ProDesk 600 G1 SFF                  | 1        | 0.51%   |
| HP Pavilion Gaming Desktop TG01-2xxx   | 1        | 0.51%   |
| HP Pavilion Desktop TP01-2xxx          | 1        | 0.51%   |
| HP Desktop M01-F0xxx                   | 1        | 0.51%   |
| HP Compaq 8000 Elite CMT PC            | 1        | 0.51%   |
| HP 700-502ng                           | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 15       | 7.65%   |
| ASUS TUF             | 11       | 5.61%   |
| ASUS PRIME           | 8        | 4.08%   |
| MSI MS-7C37          | 6        | 3.06%   |
| Dell OptiPlex        | 6        | 3.06%   |
| ASUS All             | 6        | 3.06%   |
| Gigabyte B450        | 5        | 2.55%   |
| Gigabyte X570        | 4        | 2.04%   |
| Gigabyte B550M       | 4        | 2.04%   |
| Gigabyte B550        | 4        | 2.04%   |
| ASRock B550M         | 4        | 2.04%   |
| ASRock B450          | 4        | 2.04%   |
| MSI MS-7C02          | 3        | 1.53%   |
| MSI MS-7A38          | 3        | 1.53%   |
| Lenovo ThinkCentre   | 3        | 1.53%   |
| Gigabyte B450M       | 3        | 1.53%   |
| ASRock B450M         | 3        | 1.53%   |
| MSI MS-7C91          | 2        | 1.02%   |
| MSI MS-7C84          | 2        | 1.02%   |
| MSI MS-7B86          | 2        | 1.02%   |
| MSI MS-7850          | 2        | 1.02%   |
| MSI MS-7798          | 2        | 1.02%   |
| Lenovo IdeaCentre    | 2        | 1.02%   |
| HP Z230              | 2        | 1.02%   |
| HP Pavilion          | 2        | 1.02%   |
| Gigabyte Z97X-Gaming | 2        | 1.02%   |
| Gigabyte Z390        | 2        | 1.02%   |
| Gigabyte H110M-S2    | 2        | 1.02%   |
| Fujitsu CELSIUS      | 2        | 1.02%   |
| Biostar G31-M7       | 2        | 1.02%   |
| ASUS STRIX           | 2        | 1.02%   |
| ASUS P8Z77-V         | 2        | 1.02%   |
| ASUS Maximus         | 2        | 1.02%   |
| ASUS K30AD           | 2        | 1.02%   |
| UMAX J42             | 1        | 0.51%   |
| Samsung DeskTop      | 1        | 0.51%   |
| Samsung 500T8A       | 1        | 0.51%   |
| Positivo POS-PIH81DI | 1        | 0.51%   |
| MSI MS-7D25          | 1        | 0.51%   |
| MSI MS-7C75          | 1        | 0.51%   |
| MSI MS-7B85          | 1        | 0.51%   |
| MSI MS-7A34          | 1        | 0.51%   |
| MSI MS-7A32          | 1        | 0.51%   |
| MSI MS-7A31          | 1        | 0.51%   |
| MSI MS-7994          | 1        | 0.51%   |
| MSI MS-7978          | 1        | 0.51%   |
| MSI MS-7821          | 1        | 0.51%   |
| MSI MS-7808          | 1        | 0.51%   |
| MSI MS-7592          | 1        | 0.51%   |
| MSI MS-7366          | 1        | 0.51%   |
| MSI Hyrican          | 1        | 0.51%   |
| Lenovo ThinkStation  | 1        | 0.51%   |
| LattePanda Alpha     | 1        | 0.51%   |
| Intel DH55HC         | 1        | 0.51%   |
| HP Z820              | 1        | 0.51%   |
| HP Z2                | 1        | 0.51%   |
| HP xw8400            | 1        | 0.51%   |
| HP ProDesk           | 1        | 0.51%   |
| HP Desktop           | 1        | 0.51%   |
| HP Compaq            | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 37       | 18.88%  |
| 2019 | 35       | 17.86%  |
| 2020 | 25       | 12.76%  |
| 2021 | 17       | 8.67%   |
| 2013 | 14       | 7.14%   |
| 2012 | 13       | 6.63%   |
| 2017 | 12       | 6.12%   |
| 2014 | 12       | 6.12%   |
| 2016 | 9        | 4.59%   |
| 2009 | 6        | 3.06%   |
| 2011 | 5        | 2.55%   |
| 2008 | 3        | 1.53%   |
| 2007 | 3        | 1.53%   |
| 2015 | 2        | 1.02%   |
| 2010 | 2        | 1.02%   |
| 2022 | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 196      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 195      | 99.49%  |
| Enabled  | 1        | 0.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 196      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 68       | 34.34%  |
| 32.01-64.0  | 51       | 25.76%  |
| 8.01-16.0   | 33       | 16.67%  |
| 4.01-8.0    | 13       | 6.57%   |
| 64.01-256.0 | 12       | 6.06%   |
| 24.01-32.0  | 11       | 5.56%   |
| 3.01-4.0    | 9        | 4.55%   |
| 1.01-2.0    | 1        | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 52       | 24.64%  |
| 1.01-2.0   | 48       | 22.75%  |
| 2.01-3.0   | 45       | 21.33%  |
| 3.01-4.0   | 34       | 16.11%  |
| 8.01-16.0  | 22       | 10.43%  |
| 0.51-1.0   | 5        | 2.37%   |
| 16.01-24.0 | 3        | 1.42%   |
| 24.01-32.0 | 2        | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 29.7%   |
| 3      | 44       | 21.78%  |
| 4      | 34       | 16.83%  |
| 1      | 33       | 16.34%  |
| 5      | 22       | 10.89%  |
| 7      | 3        | 1.49%   |
| 6      | 3        | 1.49%   |
| 9      | 1        | 0.5%    |
| 8      | 1        | 0.5%    |
| 0      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 150      | 76.14%  |
| Yes       | 47       | 23.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 195      | 99.49%  |
| No        | 1        | 0.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 50.51%  |
| No        | 98       | 49.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 53.77%  |
| Yes       | 92       | 46.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 51       | 26.02%  |
| Germany             | 27       | 13.78%  |
| Italy               | 11       | 5.61%   |
| Canada              | 9        | 4.59%   |
| Poland              | 8        | 4.08%   |
| France              | 8        | 4.08%   |
| Netherlands         | 7        | 3.57%   |
| UK                  | 6        | 3.06%   |
| Belgium             | 6        | 3.06%   |
| Austria             | 5        | 2.55%   |
| Russia              | 4        | 2.04%   |
| Brazil              | 4        | 2.04%   |
| Switzerland         | 3        | 1.53%   |
| Spain               | 3        | 1.53%   |
| Mexico              | 3        | 1.53%   |
| India               | 3        | 1.53%   |
| Argentina           | 3        | 1.53%   |
| Turkey              | 2        | 1.02%   |
| Sweden              | 2        | 1.02%   |
| Slovenia            | 2        | 1.02%   |
| Norway              | 2        | 1.02%   |
| Hungary             | 2        | 1.02%   |
| Hong Kong           | 2        | 1.02%   |
| Denmark             | 2        | 1.02%   |
| Czechia             | 2        | 1.02%   |
| Australia           | 2        | 1.02%   |
| Vietnam             | 1        | 0.51%   |
| Trinidad and Tobago | 1        | 0.51%   |
| Sri Lanka           | 1        | 0.51%   |
| South Korea         | 1        | 0.51%   |
| South Africa        | 1        | 0.51%   |
| Singapore           | 1        | 0.51%   |
| Saudi Arabia        | 1        | 0.51%   |
| Portugal            | 1        | 0.51%   |
| Malaysia            | 1        | 0.51%   |
| Lithuania           | 1        | 0.51%   |
| Jordan              | 1        | 0.51%   |
| Guatemala           | 1        | 0.51%   |
| Greece              | 1        | 0.51%   |
| Finland             | 1        | 0.51%   |
| Costa Rica          | 1        | 0.51%   |
| Chile               | 1        | 0.51%   |
| Bulgaria            | 1        | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Berlin                      | 5        | 2.43%   |
| Turin                       | 3        | 1.46%   |
| Ottawa                      | 3        | 1.46%   |
| Zurich                      | 2        | 0.97%   |
| Wroclaw                     | 2        | 0.97%   |
| Warsaw                      | 2        | 0.97%   |
| Tuen Mun                    | 2        | 0.97%   |
| Toronto                     | 2        | 0.97%   |
| St Petersburg               | 2        | 0.97%   |
| Snohomish                   | 2        | 0.97%   |
| Schiedam                    | 2        | 0.97%   |
| Porth                       | 2        | 0.97%   |
| Leipzig                     | 2        | 0.97%   |
| Istanbul                    | 2        | 0.97%   |
| Houston                     | 2        | 0.97%   |
| Hamburg                     | 2        | 0.97%   |
| Geesteren                   | 2        | 0.97%   |
| Barbentane                  | 2        | 0.97%   |
| Amsterdam                   | 2        | 0.97%   |
| Zuidlaren                   | 1        | 0.49%   |
| Zapopan                     | 1        | 0.49%   |
| Wimauma                     | 1        | 0.49%   |
| Whiteville                  | 1        | 0.49%   |
| Weybridge                   | 1        | 0.49%   |
| Westminster                 | 1        | 0.49%   |
| West Haddon                 | 1        | 0.49%   |
| Virar                       | 1        | 0.49%   |
| Vilnius                     | 1        | 0.49%   |
| Villanova                   | 1        | 0.49%   |
| Villa Ballester             | 1        | 0.49%   |
| Vienna                      | 1        | 0.49%   |
| Union                       | 1        | 0.49%   |
| Toledo                      | 1        | 0.49%   |
| The Colony                  | 1        | 0.49%   |
| Tempe                       | 1        | 0.49%   |
| Sullivan                    | 1        | 0.49%   |
| Stuttgart                   | 1        | 0.49%   |
| Stapelfeld                  | 1        | 0.49%   |
| Spring Field                | 1        | 0.49%   |
| Spring                      | 1        | 0.49%   |
| Spijkenisse                 | 1        | 0.49%   |
| Sopron                      | 1        | 0.49%   |
| Sofia                       | 1        | 0.49%   |
| Singapore                   | 1        | 0.49%   |
| Sheboygan                   | 1        | 0.49%   |
| Severna Park                | 1        | 0.49%   |
| Seoul                       | 1        | 0.49%   |
| Senonches                   | 1        | 0.49%   |
| Schorndorf                  | 1        | 0.49%   |
| Schaarbeek                  | 1        | 0.49%   |
| Santiago                    | 1        | 0.49%   |
| Santa Clarita               | 1        | 0.49%   |
| Santa Ana                   | 1        | 0.49%   |
| San Vendemiano-Fossamerlo   | 1        | 0.49%   |
| San Nicolás de los Arroyos | 1        | 0.49%   |
| Salvador                    | 1        | 0.49%   |
| Sala                        | 1        | 0.49%   |
| Rotterdam                   | 1        | 0.49%   |
| Riyadh                      | 1        | 0.49%   |
| Ripollet                    | 1        | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 84       | 140    | 19%     |
| Samsung Electronics       | 83       | 148    | 18.78%  |
| Seagate                   | 73       | 108    | 16.52%  |
| Kingston                  | 30       | 53     | 6.79%   |
| Crucial                   | 29       | 48     | 6.56%   |
| Toshiba                   | 17       | 22     | 3.85%   |
| SanDisk                   | 16       | 21     | 3.62%   |
| Phison                    | 10       | 11     | 2.26%   |
| Hitachi                   | 10       | 10     | 2.26%   |
| Intel                     | 7        | 9      | 1.58%   |
| Corsair                   | 6        | 6      | 1.36%   |
| A-DATA Technology         | 6        | 12     | 1.36%   |
| SPCC                      | 5        | 5      | 1.13%   |
| Micron Technology         | 5        | 7      | 1.13%   |
| XPG                       | 4        | 4      | 0.9%    |
| Intenso                   | 4        | 5      | 0.9%    |
| Unknown                   | 3        | 4      | 0.68%   |
| PNY                       | 3        | 3      | 0.68%   |
| OCZ                       | 3        | 3      | 0.68%   |
| China                     | 3        | 3      | 0.68%   |
| Plextor                   | 2        | 3      | 0.45%   |
| Lexar                     | 2        | 2      | 0.45%   |
| Leven                     | 2        | 3      | 0.45%   |
| JMicron Technology        | 2        | 2      | 0.45%   |
| HGST                      | 2        | 2      | 0.45%   |
| Gigabyte Technology       | 2        | 3      | 0.45%   |
| USB3.1                    | 1        | 1      | 0.23%   |
| UMAX                      | 1        | 1      | 0.23%   |
| Transcend                 | 1        | 1      | 0.23%   |
| T-FORCE                   | 1        | 1      | 0.23%   |
| SK hynix                  | 1        | 1      | 0.23%   |
| SABRENT                   | 1        | 1      | 0.23%   |
| Realtek Semiconductor     | 1        | 1      | 0.23%   |
| Realtek                   | 1        | 1      | 0.23%   |
| Pioneer                   | 1        | 3      | 0.23%   |
| PI-041                    | 1        | 1      | 0.23%   |
| Phison Electronics        | 1        | 1      | 0.23%   |
| Patriot                   | 1        | 2      | 0.23%   |
| NGFF                      | 1        | 1      | 0.23%   |
| Netac                     | 1        | 1      | 0.23%   |
| Mushkin                   | 1        | 1      | 0.23%   |
| Micron/Crucial Technology | 1        | 1      | 0.23%   |
| Maxtor                    | 1        | 1      | 0.23%   |
| Maxone                    | 1        | 1      | 0.23%   |
| LITEONIT                  | 1        | 1      | 0.23%   |
| LDLC                      | 1        | 1      | 0.23%   |
| KIOXIA                    | 1        | 1      | 0.23%   |
| Kingmax                   | 1        | 2      | 0.23%   |
| Imation                   | 1        | 1      | 0.23%   |
| IBM-ESXS                  | 1        | 1      | 0.23%   |
| HPE                       | 1        | 1      | 0.23%   |
| Hewlett-Packard           | 1        | 1      | 0.23%   |
| Drevo                     | 1        | 1      | 0.23%   |
| ASMT                      | 1        | 2      | 0.23%   |
| ASMedia                   | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 12       | 2.21%   |
| Samsung SSD 860 EVO 1TB          | 9        | 1.65%   |
| Crucial CT500MX500SSD1 500GB     | 9        | 1.65%   |
| WDC WD10EZEX-08WN4A0 1TB         | 8        | 1.47%   |
| Seagate ST4000DM004-2CV104 4TB   | 8        | 1.47%   |
| Samsung SSD 850 EVO 250GB        | 8        | 1.47%   |
| Samsung SSD 860 EVO 500GB        | 7        | 1.29%   |
| Kingston SA400S37120G 120GB SSD  | 7        | 1.29%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 1.1%    |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB   | 6        | 1.1%    |
| Samsung SSD 850 EVO 500GB        | 6        | 1.1%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 4        | 0.74%   |
| Seagate Expansion Desk 4TB       | 4        | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 0.74%   |
| Samsung SSD 970 EVO 500GB        | 4        | 0.74%   |
| Samsung NVMe SSD Drive 1TB       | 4        | 0.74%   |
| Kingston NVMe SSD Drive 1TB      | 4        | 0.74%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.74%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.55%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 3        | 0.55%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 3        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.55%   |
| WDC WD10EZEX-00RKKA0 1TB         | 3        | 0.55%   |
| Toshiba HDWD110 1TB              | 3        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.55%   |
| Samsung SSD 980 500GB            | 3        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 0.55%   |
| Samsung SSD 970 EVO 1TB          | 3        | 0.55%   |
| Samsung SSD 960 EVO 500GB        | 3        | 0.55%   |
| Samsung SSD 870 QVO 1TB          | 3        | 0.55%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.55%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.55%   |
| Samsung SSD 840 EVO 120GB        | 3        | 0.55%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 0.55%   |
| Samsung NVMe SSD Drive 250GB     | 3        | 0.55%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 0.55%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 0.55%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 0.55%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2        | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.37%   |
| WDC WDS100T3XHC-00SJG0 1TB       | 2        | 0.37%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 2        | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.37%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 0.37%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 2        | 0.37%   |
| WDC WD10EZRX-00A8LB0 1TB         | 2        | 0.37%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.37%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.37%   |
| WDC WD10EACS-00D6B1 1TB          | 2        | 0.37%   |
| WDC WD100EMAZ-00WJTA0 10TB       | 2        | 0.37%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 2        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB      | 2        | 0.37%   |
| Toshiba THNSNJ256GCSU 256GB SSD  | 2        | 0.37%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.37%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.37%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.37%   |
| Toshiba A100 120GB SSD           | 2        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 72       | 107    | 40.22%  |
| WDC                 | 65       | 95     | 36.31%  |
| Toshiba             | 14       | 15     | 7.82%   |
| Hitachi             | 10       | 10     | 5.59%   |
| Samsung Electronics | 6        | 13     | 3.35%   |
| Unknown             | 2        | 2      | 1.12%   |
| HGST                | 2        | 2      | 1.12%   |
| SABRENT             | 1        | 1      | 0.56%   |
| PI-041              | 1        | 1      | 0.56%   |
| Maxtor              | 1        | 1      | 0.56%   |
| Maxone              | 1        | 1      | 0.56%   |
| JMicron Technology  | 1        | 1      | 0.56%   |
| HPE                 | 1        | 1      | 0.56%   |
| ASMT                | 1        | 2      | 0.56%   |
| ASMedia             | 1        | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 58       | 86     | 31.87%  |
| Crucial             | 25       | 36     | 13.74%  |
| Kingston            | 20       | 38     | 10.99%  |
| WDC                 | 17       | 24     | 9.34%   |
| SanDisk             | 11       | 15     | 6.04%   |
| Micron Technology   | 5        | 7      | 2.75%   |
| Toshiba             | 4        | 6      | 2.2%    |
| Intenso             | 4        | 5      | 2.2%    |
| Intel               | 4        | 5      | 2.2%    |
| SPCC                | 3        | 3      | 1.65%   |
| OCZ                 | 3        | 3      | 1.65%   |
| China               | 3        | 3      | 1.65%   |
| PNY                 | 2        | 2      | 1.1%    |
| Leven               | 2        | 3      | 1.1%    |
| Corsair             | 2        | 2      | 1.1%    |
| A-DATA Technology   | 2        | 2      | 1.1%    |
| UMAX                | 1        | 1      | 0.55%   |
| Transcend           | 1        | 1      | 0.55%   |
| Plextor             | 1        | 2      | 0.55%   |
| Pioneer             | 1        | 3      | 0.55%   |
| Phison              | 1        | 1      | 0.55%   |
| Patriot             | 1        | 2      | 0.55%   |
| NGFF                | 1        | 1      | 0.55%   |
| Mushkin             | 1        | 1      | 0.55%   |
| LITEONIT            | 1        | 1      | 0.55%   |
| Lexar               | 1        | 1      | 0.55%   |
| LDLC                | 1        | 1      | 0.55%   |
| Kingmax             | 1        | 2      | 0.55%   |
| JMicron Technology  | 1        | 1      | 0.55%   |
| Imation             | 1        | 1      | 0.55%   |
| Hewlett-Packard     | 1        | 1      | 0.55%   |
| Gigabyte Technology | 1        | 1      | 0.55%   |
| Drevo               | 1        | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 134      | 262    | 37.02%  |
| HDD     | 133      | 253    | 36.74%  |
| NVMe    | 91       | 151    | 25.14%  |
| Unknown | 4        | 5      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 176      | 490    | 60.48%  |
| NVMe | 91       | 150    | 31.27%  |
| SAS  | 24       | 31     | 8.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 125      | 253    | 39.68%  |
| 0.51-1.0   | 96       | 141    | 30.48%  |
| 1.01-2.0   | 47       | 60     | 14.92%  |
| 3.01-4.0   | 23       | 34     | 7.3%    |
| 2.01-3.0   | 12       | 13     | 3.81%   |
| 4.01-10.0  | 9        | 11     | 2.86%   |
| 10.01-20.0 | 3        | 3      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 50       | 24.63%  |
| More than 3000 | 37       | 18.23%  |
| 501-1000       | 29       | 14.29%  |
| 101-250        | 24       | 11.82%  |
| 2001-3000      | 21       | 10.34%  |
| 251-500        | 20       | 9.85%   |
| Unknown        | 13       | 6.4%    |
| 1-20           | 4        | 1.97%   |
| 51-100         | 4        | 1.97%   |
| 21-50          | 1        | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 31       | 14.42%  |
| 101-250        | 29       | 13.49%  |
| 501-1000       | 29       | 13.49%  |
| 1-20           | 28       | 13.02%  |
| 251-500        | 27       | 12.56%  |
| 51-100         | 22       | 10.23%  |
| 21-50          | 15       | 6.98%   |
| More than 3000 | 14       | 6.51%   |
| Unknown        | 13       | 6.05%   |
| 2001-3000      | 7        | 3.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| XPG GAMMIX S11 480GB                  | 1        | 1      | 3.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 1      | 3.85%   |
| WDC WD5000AZRX-00A8LB0 500GB          | 1        | 1      | 3.85%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 3.85%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 3.85%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1        | 1      | 3.85%   |
| WDC WD2002FYPS-01U1B0 2TB             | 1        | 1      | 3.85%   |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 3.85%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 3.85%   |
| Seagate ST9320325AS 320GB             | 1        | 4      | 3.85%   |
| Seagate ST6000VX0023-2EF110 6TB       | 1        | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 3.85%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 3.85%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 960 EVO 500GB | 1        | 1      | 3.85%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 3.85%   |
| OCZ VERTEX3 240GB SSD                 | 1        | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB         | 1        | 1      | 3.85%   |
| Hitachi HDT725025VLA380 250GB         | 1        | 1      | 3.85%   |
| Drevo X1 SSD 120GB                    | 1        | 1      | 3.85%   |
| Crucial CT500MX500SSD1 500GB          | 1        | 4      | 3.85%   |
| Crucial CT1050MX300SSD1 1050GB        | 1        | 1      | 3.85%   |
| Corsair Force LS SSD 120GB            | 1        | 1      | 3.85%   |
| ASMT ASM1156-PM 1TB                   | 1        | 2      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 28%     |
| Seagate             | 4        | 8      | 16%     |
| Samsung Electronics | 3        | 3      | 12%     |
| Hitachi             | 2        | 2      | 8%      |
| Crucial             | 2        | 5      | 8%      |
| XPG                 | 1        | 1      | 4%      |
| Toshiba             | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| Drevo               | 1        | 1      | 4%      |
| Corsair             | 1        | 1      | 4%      |
| ASMT                | 1        | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 40%     |
| Seagate             | 4        | 8      | 26.67%  |
| Hitachi             | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 1      | 6.67%   |
| ASMT                | 1        | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 21     | 62.5%   |
| SSD  | 6        | 10     | 25%     |
| NVMe | 3        | 3      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 50%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 136      | 407    | 57.87%  |
| Detected | 74       | 228    | 31.49%  |
| Malfunc  | 23       | 34     | 9.79%   |
| Failed   | 2        | 2      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 99       | 29.73%  |
| Intel                          | 94       | 28.23%  |
| Samsung Electronics            | 37       | 11.11%  |
| SanDisk                        | 22       | 6.61%   |
| ASMedia Technology             | 18       | 5.41%   |
| Phison Electronics             | 17       | 5.11%   |
| Kingston Technology Company    | 10       | 3%      |
| Realtek Semiconductor          | 5        | 1.5%    |
| Micron/Crucial Technology      | 5        | 1.5%    |
| Marvell Technology Group       | 5        | 1.5%    |
| ADATA Technology               | 4        | 1.2%    |
| Silicon Motion                 | 3        | 0.9%    |
| Nvidia                         | 3        | 0.9%    |
| JMicron Technology             | 3        | 0.9%    |
| Toshiba America Info Systems   | 1        | 0.3%    |
| Solid State Storage Technology | 1        | 0.3%    |
| SK hynix                       | 1        | 0.3%    |
| Seagate Technology             | 1        | 0.3%    |
| Micron Technology              | 1        | 0.3%    |
| LSI Logic / Symbios Logic      | 1        | 0.3%    |
| KIOXIA                         | 1        | 0.3%    |
| Broadcom / LSI                 | 1        | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 64       | 16.28%  |
| AMD 400 Series Chipset SATA Controller                                           | 35       | 8.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 21       | 5.34%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 18       | 4.58%   |
| AMD 500 Series Chipset SATA Controller                                           | 18       | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16       | 4.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 11       | 2.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 9        | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9        | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9        | 2.29%   |
| Phison E12 NVMe Controller                                                       | 8        | 2.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7        | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7        | 1.78%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 7        | 1.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6        | 1.53%   |
| Samsung NVMe SSD Controller 980                                                  | 6        | 1.53%   |
| Kingston Company A2000 NVMe SSD                                                  | 6        | 1.53%   |
| Intel SATA Controller [RAID mode]                                                | 6        | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5        | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5        | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5        | 1.27%   |
| AMD FCH SATA Controller D                                                        | 5        | 1.27%   |
| Realtek Realtek Non-Volatile memory controller                                   | 4        | 1.02%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4        | 1.02%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3        | 0.76%   |
| Kingston Company KC2000 NVMe SSD                                                 | 3        | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 3        | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3        | 0.76%   |
| AMD X370 Series Chipset SATA Controller                                          | 3        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 0.76%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2        | 0.51%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 2        | 0.51%   |
| Nvidia MCP73 IDE Controller                                                      | 2        | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2        | 0.51%   |
| Kingston Company Company Non-Volatile memory controller                          | 2        | 0.51%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.51%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2        | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2        | 0.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2        | 0.51%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 2        | 0.51%   |
| AMD X399 Series Chipset SATA Controller                                          | 2        | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.51%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1        | 0.25%   |
| Solid State Storage Non-Volatile memory controller                               | 1        | 0.25%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1        | 0.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.25%   |
| Seagate FireCuda 520 SSD                                                         | 1        | 0.25%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.25%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.25%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1        | 0.25%   |
| Phison E7 NVMe Controller                                                        | 1        | 0.25%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1        | 0.25%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.25%   |
| Nvidia MCP61 IDE                                                                 | 1        | 0.25%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1        | 0.25%   |
| Micron Non-Volatile memory controller                                            | 1        | 0.25%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1        | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 179      | 60.07%  |
| NVMe | 91       | 30.54%  |
| IDE  | 18       | 6.04%   |
| RAID | 8        | 2.68%   |
| SAS  | 2        | 0.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 100      | 51.02%  |
| Intel  | 96       | 48.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 5.61%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 5.1%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 4.59%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 3.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 3.06%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 2.04%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 2.04%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 2.04%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 2.04%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 2.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.53%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.53%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.53%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.53%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.02%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.02%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 1.02%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.02%   |
| Intel 12th Gen Core i5-12600K               | 2        | 1.02%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.02%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.02%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.02%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 2        | 1.02%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 1.02%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.02%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.51%   |
| Intel Xeon CPU W5580 @ 3.20GHz              | 1        | 0.51%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.51%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 0.51%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.51%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.51%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.51%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.51%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 0.51%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.51%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.51%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 0.51%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.51%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.51%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.51%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.51%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.51%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.51%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.51%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.51%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.51%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.51%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.51%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.51%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 0.51%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 43       | 21.94%  |
| Intel Core i5           | 32       | 16.33%  |
| AMD Ryzen 7             | 27       | 13.78%  |
| Intel Core i7           | 26       | 13.27%  |
| AMD Ryzen 9             | 16       | 8.16%   |
| Intel Xeon              | 9        | 4.59%   |
| Intel Core i3           | 7        | 3.57%   |
| Other                   | 6        | 3.06%   |
| Intel Celeron           | 4        | 2.04%   |
| AMD Ryzen 3             | 4        | 2.04%   |
| Intel Core 2 Quad       | 3        | 1.53%   |
| AMD Ryzen Threadripper  | 3        | 1.53%   |
| AMD FX                  | 3        | 1.53%   |
| Intel Core 2 Duo        | 2        | 1.02%   |
| Intel Pentium Gold      | 1        | 0.51%   |
| Intel Pentium Dual-Core | 1        | 0.51%   |
| Intel Pentium Dual      | 1        | 0.51%   |
| Intel Pentium           | 1        | 0.51%   |
| Intel Core m3           | 1        | 0.51%   |
| Intel Core i9           | 1        | 0.51%   |
| Intel Core 2            | 1        | 0.51%   |
| AMD Phenom II X4        | 1        | 0.51%   |
| AMD Athlon X4           | 1        | 0.51%   |
| AMD Athlon II X4        | 1        | 0.51%   |
| AMD A8                  | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 71       | 36.04%  |
| 6      | 51       | 25.89%  |
| 8      | 30       | 15.23%  |
| 2      | 18       | 9.14%   |
| 12     | 16       | 8.12%   |
| 16     | 5        | 2.54%   |
| 10     | 3        | 1.52%   |
| 3      | 2        | 1.02%   |
| 32     | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 193      | 97.97%  |
| 2      | 4        | 2.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 144      | 73.47%  |
| 1      | 52       | 26.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 196      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 35.5%   |
| 0x08701021 | 22       | 11%     |
| 0x306c3    | 15       | 7.5%    |
| 0x0a201009 | 9        | 4.5%    |
| 0x08701013 | 8        | 4%      |
| 0x506e3    | 7        | 3.5%    |
| 0x306a9    | 7        | 3.5%    |
| 0x906ea    | 5        | 2.5%    |
| 0x906e9    | 5        | 2.5%    |
| 0x0a50000c | 5        | 2.5%    |
| 0x0a201016 | 4        | 2%      |
| 0x0800820d | 4        | 2%      |
| 0x106a5    | 3        | 1.5%    |
| 0x08108109 | 3        | 1.5%    |
| 0x08001138 | 3        | 1.5%    |
| 0x08001137 | 3        | 1.5%    |
| 0xa0655    | 2        | 1%      |
| 0x6fd      | 2        | 1%      |
| 0x106e5    | 2        | 1%      |
| 0x08101016 | 2        | 1%      |
| 0xa0671    | 1        | 0.5%    |
| 0x906ed    | 1        | 0.5%    |
| 0x906ec    | 1        | 0.5%    |
| 0x906eb    | 1        | 0.5%    |
| 0x90672    | 1        | 0.5%    |
| 0x706a8    | 1        | 0.5%    |
| 0x6fb      | 1        | 0.5%    |
| 0x6f6      | 1        | 0.5%    |
| 0x6f2      | 1        | 0.5%    |
| 0x406c4    | 1        | 0.5%    |
| 0x306f2    | 1        | 0.5%    |
| 0x206c2    | 1        | 0.5%    |
| 0x206a7    | 1        | 0.5%    |
| 0x20652    | 1        | 0.5%    |
| 0x0a50000b | 1        | 0.5%    |
| 0x0a20120a | 1        | 0.5%    |
| 0x06000852 | 1        | 0.5%    |
| 0x010000c8 | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 43       | 21.94%  |
| Zen 3            | 26       | 13.27%  |
| Haswell          | 25       | 12.76%  |
| KabyLake         | 18       | 9.18%   |
| Zen+             | 12       | 6.12%   |
| Zen              | 12       | 6.12%   |
| IvyBridge        | 11       | 5.61%   |
| Skylake          | 10       | 5.1%    |
| Core             | 7        | 3.57%   |
| Nehalem          | 5        | 2.55%   |
| Unknown          | 5        | 2.55%   |
| CometLake        | 4        | 2.04%   |
| SandyBridge      | 3        | 1.53%   |
| Westmere         | 2        | 1.02%   |
| Piledriver       | 2        | 1.02%   |
| Penryn           | 2        | 1.02%   |
| Steamroller      | 1        | 0.51%   |
| Silvermont       | 1        | 0.51%   |
| K10 Llano        | 1        | 0.51%   |
| K10              | 1        | 0.51%   |
| Icelake          | 1        | 0.51%   |
| Goldmont plus    | 1        | 0.51%   |
| Excavator        | 1        | 0.51%   |
| Bulldozer        | 1        | 0.51%   |
| Alderlake Hybrid | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 102      | 47.89%  |
| AMD    | 79       | 37.09%  |
| Intel  | 32       | 15.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23       | 10.6%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 4.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 3.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 3.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 3.23%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 3.23%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 2.76%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 6        | 2.76%   |
| AMD Cezanne                                                                 | 6        | 2.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 2.3%    |
| Nvidia GA102 [GeForce RTX 3080]                                             | 5        | 2.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 2.3%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.84%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 1.38%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 1.38%   |
| Intel HD Graphics 630                                                       | 3        | 1.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1.38%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.38%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.92%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.92%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.92%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.92%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.92%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.92%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 0.92%   |
| Intel HD Graphics 530                                                       | 2        | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 0.92%   |
| Intel AlderLake-S GT1                                                       | 2        | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 0.92%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 2        | 0.92%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.46%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.46%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.46%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.46%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.46%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.46%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.46%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.46%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.46%   |
| Nvidia GK104GL [Quadro K5000]                                               | 1        | 0.46%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.46%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                          | 1        | 0.46%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.46%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.46%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.46%   |
| Nvidia GF106 [GeForce GTS 450 OEM]                                          | 1        | 0.46%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.46%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.46%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.46%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.46%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 0.46%   |
| Nvidia G70GL [Quadro FX 4500]                                               | 1        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 92       | 46.46%  |
| 1 x AMD        | 68       | 34.34%  |
| 1 x Intel      | 21       | 10.61%  |
| AMD + Nvidia   | 6        | 3.03%   |
| 2 x AMD        | 4        | 2.02%   |
| Intel + Nvidia | 3        | 1.52%   |
| Intel + AMD    | 3        | 1.52%   |
| 2 x Nvidia     | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 56.63%  |
| Proprietary | 85       | 43.37%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 30%     |
| 7.01-8.0   | 40       | 20%     |
| 3.01-4.0   | 24       | 12%     |
| 1.01-2.0   | 22       | 11%     |
| 5.01-6.0   | 18       | 9%      |
| 8.01-16.0  | 17       | 8.5%    |
| 0.51-1.0   | 9        | 4.5%    |
| 0.01-0.5   | 8        | 4%      |
| 2.01-3.0   | 1        | 0.5%    |
| 16.01-24.0 | 1        | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 40       | 15.87%  |
| Dell                 | 28       | 11.11%  |
| Goldstar             | 25       | 9.92%   |
| Acer                 | 19       | 7.54%   |
| AOC                  | 18       | 7.14%   |
| BenQ                 | 17       | 6.75%   |
| Ancor Communications | 17       | 6.75%   |
| Hewlett-Packard      | 9        | 3.57%   |
| ASUSTek Computer     | 7        | 2.78%   |
| Vizio                | 6        | 2.38%   |
| Iiyama               | 6        | 2.38%   |
| ViewSonic            | 5        | 1.98%   |
| Philips              | 5        | 1.98%   |
| Lenovo               | 5        | 1.98%   |
| Gigabyte Technology  | 4        | 1.59%   |
| LG Electronics       | 3        | 1.19%   |
| Fujitsu Siemens      | 3        | 1.19%   |
| Valve                | 2        | 0.79%   |
| Lenovo Group Limited | 2        | 0.79%   |
| VOXICON              | 1        | 0.4%    |
| Unknown (XXX)        | 1        | 0.4%    |
| Unknown              | 1        | 0.4%    |
| Sony                 | 1        | 0.4%    |
| Sceptre Tech         | 1        | 0.4%    |
| SAC                  | 1        | 0.4%    |
| RTK                  | 1        | 0.4%    |
| RS                   | 1        | 0.4%    |
| Planar               | 1        | 0.4%    |
| Pixio                | 1        | 0.4%    |
| Panasonic            | 1        | 0.4%    |
| Orion                | 1        | 0.4%    |
| NEC Computers        | 1        | 0.4%    |
| MSI                  | 1        | 0.4%    |
| Mi                   | 1        | 0.4%    |
| Insignia             | 1        | 0.4%    |
| Idek Iiyama          | 1        | 0.4%    |
| Hyundai ImageQuest   | 1        | 0.4%    |
| HVR                  | 1        | 0.4%    |
| HPN                  | 1        | 0.4%    |
| Hitachi              | 1        | 0.4%    |
| HannStar             | 1        | 0.4%    |
| Grundig              | 1        | 0.4%    |
| GET                  | 1        | 0.4%    |
| GDH                  | 1        | 0.4%    |
| Gateway              | 1        | 0.4%    |
| Fluid                | 1        | 0.4%    |
| Eizo                 | 1        | 0.4%    |
| CTV                  | 1        | 0.4%    |
| Belinea              | 1        | 0.4%    |
| Unknown              | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 4        | 1.49%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch      | 3        | 1.12%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 3        | 1.12%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 1.12%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 1.12%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 3        | 1.12%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 3        | 1.12%   |
| Valve Index HMD VLV91A8                                                | 2        | 0.74%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.74%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch               | 2        | 0.74%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 2        | 0.74%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 0.74%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 2        | 0.74%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 600x330mm 27.0-inch         | 2        | 0.74%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2        | 0.74%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                      | 2        | 0.74%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2        | 0.74%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                      | 2        | 0.74%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.74%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                     | 2        | 0.74%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch           | 2        | 0.74%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                        | 2        | 0.74%   |
| VOXICON D32QO DUS3200 2560x1440 708x398mm 32.0-inch                    | 1        | 0.37%   |
| Vizio M43Q6-J04 VIZ1033 3840x2160 1096x616mm 49.5-inch                 | 1        | 0.37%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                    | 1        | 0.37%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                      | 1        | 0.37%   |
| Vizio E240AR VIZ0089 1360x768 477x268mm 21.5-inch                      | 1        | 0.37%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                     | 1        | 0.37%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1        | 0.37%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 0.37%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 0.37%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.37%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch          | 1        | 0.37%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 1        | 0.37%   |
| Unknown LCD Monitor MARANTZ JAPAN, INC. marantz-AVR 3840x2160          | 1        | 0.37%   |
| Unknown (XXX) HDMI XXX0101 2560x1600 220x130mm 10.1-inch               | 1        | 0.37%   |
| Sony TV SNY8002 1920x1080                                              | 1        | 0.37%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch         | 1        | 0.37%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.37%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM0522 1600x900 443x249mm 20.0-inch    | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1        | 0.37%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch   | 1        | 0.37%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 480x270mm 21.7-inch     | 1        | 0.37%   |
| Samsung Electronics SMBX2350 SAM071D 1920x1080 509x286mm 23.0-inch     | 1        | 0.37%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch     | 1        | 0.37%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch      | 1        | 0.37%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch  | 1        | 0.37%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch  | 1        | 0.37%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch      | 1        | 0.37%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 1        | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.37%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch      | 1        | 0.37%   |
| Samsung Electronics S24B240 SAM08E9 1920x1080 521x293mm 23.5-inch      | 1        | 0.37%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch      | 1        | 0.37%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch      | 1        | 0.37%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 1        | 0.37%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 103      | 41.87%  |
| 2560x1440 (QHD)    | 37       | 15.04%  |
| 3840x2160 (4K)     | 33       | 13.41%  |
| 1280x1024 (SXGA)   | 11       | 4.47%   |
| 1920x1200 (WUXGA)  | 9        | 3.66%   |
| Unknown            | 8        | 3.25%   |
| 1600x900 (HD+)     | 6        | 2.44%   |
| 3440x1440          | 5        | 2.03%   |
| 2560x1080          | 5        | 2.03%   |
| 1680x1050 (WSXGA+) | 5        | 2.03%   |
| 1440x900 (WXGA+)   | 4        | 1.63%   |
| 1366x768 (WXGA)    | 3        | 1.22%   |
| 1360x768           | 3        | 1.22%   |
| 3840x1600          | 2        | 0.81%   |
| 3840x1080          | 2        | 0.81%   |
| 9840x3840          | 1        | 0.41%   |
| 4480x1440          | 1        | 0.41%   |
| 3840x1200          | 1        | 0.41%   |
| 3520x1080          | 1        | 0.41%   |
| 3200x1080          | 1        | 0.41%   |
| 2880x1700          | 1        | 0.41%   |
| 2560x1600          | 1        | 0.41%   |
| 1920x540           | 1        | 0.41%   |
| 1600x1200          | 1        | 0.41%   |
| 1024x768 (XGA)     | 1        | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 52       | 20.8%   |
| 24      | 52       | 20.8%   |
| 23      | 22       | 8.8%    |
| 21      | 21       | 8.4%    |
| Unknown | 19       | 7.6%    |
| 31      | 15       | 6%      |
| 34      | 13       | 5.2%    |
| 19      | 11       | 4.4%    |
| 22      | 6        | 2.4%    |
| 20      | 5        | 2%      |
| 32      | 4        | 1.6%    |
| 18      | 4        | 1.6%    |
| 17      | 4        | 1.6%    |
| 84      | 3        | 1.2%    |
| 54      | 3        | 1.2%    |
| 49      | 2        | 0.8%    |
| 37      | 2        | 0.8%    |
| 74      | 1        | 0.4%    |
| 72      | 1        | 0.4%    |
| 69      | 1        | 0.4%    |
| 60      | 1        | 0.4%    |
| 52      | 1        | 0.4%    |
| 48      | 1        | 0.4%    |
| 46      | 1        | 0.4%    |
| 42      | 1        | 0.4%    |
| 28      | 1        | 0.4%    |
| 16      | 1        | 0.4%    |
| 15      | 1        | 0.4%    |
| 10      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 107      | 45.34%  |
| 401-500     | 40       | 16.95%  |
| 601-700     | 23       | 9.75%   |
| Unknown     | 19       | 8.05%   |
| 701-800     | 17       | 7.2%    |
| 1001-1500   | 9        | 3.81%   |
| 301-350     | 6        | 2.54%   |
| 1501-2000   | 6        | 2.54%   |
| 351-400     | 5        | 2.12%   |
| 801-900     | 2        | 0.85%   |
| 201-300     | 1        | 0.42%   |
| 901-1000    | 1        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 149      | 67.73%  |
| 16/10   | 27       | 12.27%  |
| Unknown | 17       | 7.73%   |
| 21/9    | 12       | 5.45%   |
| 5/4     | 8        | 3.64%   |
| 32/9    | 3        | 1.36%   |
| 6/5     | 2        | 0.91%   |
| 4/3     | 2        | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 77       | 31.69%  |
| 301-350        | 52       | 21.4%   |
| 351-500        | 30       | 12.35%  |
| Unknown        | 19       | 7.82%   |
| 251-300        | 18       | 7.41%   |
| 151-200        | 17       | 7%      |
| More than 1000 | 12       | 4.94%   |
| 501-1000       | 8        | 3.29%   |
| 141-150        | 7        | 2.88%   |
| 41-50          | 1        | 0.41%   |
| 131-140        | 1        | 0.41%   |
| 111-120        | 1        | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 127      | 57.47%  |
| 101-120       | 48       | 21.72%  |
| Unknown       | 19       | 8.6%    |
| 1-50          | 10       | 4.52%   |
| 121-160       | 9        | 4.07%   |
| 161-240       | 7        | 3.17%   |
| More than 240 | 1        | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 134      | 67.68%  |
| 2     | 51       | 25.76%  |
| 3     | 11       | 5.56%   |
| 4     | 2        | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 131      | 46.45%  |
| Intel                                 | 90       | 31.91%  |
| Qualcomm Atheros                      | 14       | 4.96%   |
| Microsoft                             | 8        | 2.84%   |
| Broadcom                              | 7        | 2.48%   |
| Ralink Technology                     | 5        | 1.77%   |
| TP-Link                               | 4        | 1.42%   |
| Ralink                                | 3        | 1.06%   |
| Aquantia                              | 3        | 1.06%   |
| Xiaomi                                | 2        | 0.71%   |
| Nvidia                                | 2        | 0.71%   |
| ASIX Electronics                      | 2        | 0.71%   |
| Wilocity                              | 1        | 0.35%   |
| Samsung Electronics                   | 1        | 0.35%   |
| NetGear                               | 1        | 0.35%   |
| Motorola PCS                          | 1        | 0.35%   |
| MediaTek                              | 1        | 0.35%   |
| InterBiometrics                       | 1        | 0.35%   |
| Huawei Technologies                   | 1        | 0.35%   |
| Exar                                  | 1        | 0.35%   |
| Edimax Technology                     | 1        | 0.35%   |
| Broadcom Limited                      | 1        | 0.35%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 96       | 28.66%  |
| Intel I211 Gigabit Network Connection                               | 26       | 7.76%   |
| Realtek RTL8125 2.5GbE Controller                                   | 24       | 7.16%   |
| Intel Wi-Fi 6 AX200                                                 | 22       | 6.57%   |
| Intel Wireless-AC 9260                                              | 8        | 2.39%   |
| Intel Ethernet Connection (2) I219-V                                | 8        | 2.39%   |
| Intel Ethernet Controller I225-V                                    | 7        | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5        | 1.49%   |
| Intel Ethernet Connection I217-LM                                   | 5        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 1.19%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4        | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.9%    |
| Microsoft XBOX ACC                                                  | 3        | 0.9%    |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 0.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 0.9%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.6%    |
| TP-Link TL-WN722N v2                                                | 2        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 0.6%    |
| Realtek 802.11ac NIC                                                | 2        | 0.6%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.6%    |
| Intel Wireless 8260                                                 | 2        | 0.6%    |
| Intel Wireless 7265                                                 | 2        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 0.6%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.6%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.3%    |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.3%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.3%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)           | 1        | 0.3%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.3%    |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.3%    |
| Ralink RT2870 Wireless Adapter                                      | 1        | 0.3%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1        | 0.3%    |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.3%    |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.3%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 52       | 47.27%  |
| Realtek Semiconductor                 | 22       | 20%     |
| Microsoft                             | 8        | 7.27%   |
| Qualcomm Atheros                      | 7        | 6.36%   |
| Ralink Technology                     | 5        | 4.55%   |
| Broadcom                              | 5        | 4.55%   |
| TP-Link                               | 3        | 2.73%   |
| Ralink                                | 3        | 2.73%   |
| Wilocity                              | 1        | 0.91%   |
| NetGear                               | 1        | 0.91%   |
| MediaTek                              | 1        | 0.91%   |
| Edimax Technology                     | 1        | 0.91%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                | 22       | 20%     |
| Intel Wireless-AC 9260                                                             | 8        | 7.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                           | 5        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                             | 4        | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 4        | 3.64%   |
| Microsoft XBOX ACC                                                                 | 3        | 2.73%   |
| Microsoft Wireless XBox Controller Dongle                                          | 3        | 2.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                                     | 3        | 2.73%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                 | 3        | 2.73%   |
| TP-Link TL-WN722N v2                                                               | 2        | 1.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                           | 2        | 1.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                           | 2        | 1.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                    | 2        | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 2        | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                         | 2        | 1.82%   |
| Realtek 802.11ac NIC                                                               | 2        | 1.82%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                               | 2        | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                   | 2        | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 2        | 1.82%   |
| Microsoft Xbox 360 Wireless Adapter                                                | 2        | 1.82%   |
| Intel Wireless 8260                                                                | 2        | 1.82%   |
| Intel Wireless 7265                                                                | 2        | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                    | 2        | 1.82%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                 | 1        | 0.91%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                | 1        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                 | 1        | 0.91%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                         | 1        | 0.91%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                    | 1        | 0.91%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                          | 1        | 0.91%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                           | 1        | 0.91%   |
| Ralink RT5572 Wireless Adapter                                                     | 1        | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                              | 1        | 0.91%   |
| Ralink RT2870 Wireless Adapter                                                     | 1        | 0.91%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                  | 1        | 0.91%   |
| Ralink MT7601U Wireless Adapter                                                    | 1        | 0.91%   |
| Ralink RT2561/RT61 802.11g PCI                                                     | 1        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                         | 1        | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 1        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                     | 1        | 0.91%   |
| NetGear A6210                                                                      | 1        | 0.91%   |
| MediaTek WiFi                                                                      | 1        | 0.91%   |
| Intel Wireless 8265 / 8275                                                         | 1        | 0.91%   |
| Intel Wireless 7260                                                                | 1        | 0.91%   |
| Intel Wireless 3165                                                                | 1        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                                    | 1        | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                   | 1        | 0.91%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                           | 1        | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                 | 1        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                                      | 1        | 0.91%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 1        | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 124      | 57.14%  |
| Intel                 | 70       | 32.26%  |
| Qualcomm Atheros      | 8        | 3.69%   |
| Aquantia              | 3        | 1.38%   |
| Xiaomi                | 2        | 0.92%   |
| Nvidia                | 2        | 0.92%   |
| Broadcom              | 2        | 0.92%   |
| ASIX Electronics      | 2        | 0.92%   |
| TP-Link               | 1        | 0.46%   |
| Samsung Electronics   | 1        | 0.46%   |
| Motorola PCS          | 1        | 0.46%   |
| Broadcom Limited      | 1        | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 96       | 43.24%  |
| Intel I211 Gigabit Network Connection                               | 26       | 11.71%  |
| Realtek RTL8125 2.5GbE Controller                                   | 24       | 10.81%  |
| Intel Ethernet Connection (2) I219-V                                | 8        | 3.6%    |
| Intel Ethernet Controller I225-V                                    | 7        | 3.15%   |
| Intel Ethernet Connection I217-LM                                   | 5        | 2.25%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 2.25%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.9%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.45%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.45%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.45%   |
| Motorola PCS Moto E (4) Plus                                        | 1        | 0.45%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.45%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.45%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.45%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 0.45%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 0.45%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express             | 1        | 0.45%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express               | 1        | 0.45%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 1        | 0.45%   |
| ASIX AX88772B                                                       | 1        | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.45%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.45%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 195      | 65.66%  |
| WiFi     | 99       | 33.33%  |
| Modem    | 3        | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 78.1%   |
| WiFi     | 46       | 21.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 113      | 57.07%  |
| 2     | 69       | 34.85%  |
| 3     | 12       | 6.06%   |
| 4     | 3        | 1.52%   |
| 0     | 1        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 158      | 79%     |
| Yes  | 42       | 21%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 46       | 48.42%  |
| Cambridge Silicon Radio  | 16       | 16.84%  |
| Realtek Semiconductor    | 14       | 14.74%  |
| Broadcom                 | 7        | 7.37%   |
| ASUSTek Computer         | 7        | 7.37%   |
| IMC Networks             | 2        | 2.11%   |
| Toshiba                  | 1        | 1.05%   |
| HTC (High Tech Computer) | 1        | 1.05%   |
| Dynex                    | 1        | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 20       | 21.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 16       | 16.84%  |
| Realtek Bluetooth Radio                                              | 13       | 13.68%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 7.37%   |
| Intel Bluetooth wireless interface                                   | 7        | 7.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 5.26%   |
| Intel AX210 Bluetooth                                                | 4        | 4.21%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 3.16%   |
| Intel AX201 Bluetooth                                                | 3        | 3.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3        | 3.16%   |
| IMC Networks Bluetooth Radio                                         | 2        | 2.11%   |
| ASUS Bluetooth Device                                                | 2        | 2.11%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 1.05%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.05%   |
| Intel Bluetooth Device                                               | 1        | 1.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 1.05%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.05%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 1.05%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 1.05%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1.05%   |
| ASUS Bluetooth Adapter                                               | 1        | 1.05%   |
| ASUS BCM20702A0                                                      | 1        | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 119      | 28.81%  |
| Nvidia                                          | 99       | 23.97%  |
| Intel                                           | 91       | 22.03%  |
| C-Media Electronics                             | 13       | 3.15%   |
| SteelSeries ApS                                 | 11       | 2.66%   |
| Logitech                                        | 10       | 2.42%   |
| Creative Labs                                   | 7        | 1.69%   |
| Texas Instruments                               | 6        | 1.45%   |
| JMTek                                           | 5        | 1.21%   |
| Kingston Technology                             | 4        | 0.97%   |
| Blue Microphones                                | 4        | 0.97%   |
| Valve Software                                  | 3        | 0.73%   |
| Sony                                            | 3        | 0.73%   |
| RODE Microphones                                | 3        | 0.73%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.48%   |
| Sennheiser Communications                       | 2        | 0.48%   |
| Samson Technologies                             | 2        | 0.48%   |
| Razer USA                                       | 2        | 0.48%   |
| Creative Technology                             | 2        | 0.48%   |
| Corsair                                         | 2        | 0.48%   |
| Xilinx                                          | 1        | 0.24%   |
| VIA Technologies                                | 1        | 0.24%   |
| Trust                                           | 1        | 0.24%   |
| Solid State System                              | 1        | 0.24%   |
| Plantronics                                     | 1        | 0.24%   |
| No brand                                        | 1        | 0.24%   |
| Native Instruments                              | 1        | 0.24%   |
| M-Audio                                         | 1        | 0.24%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.24%   |
| KTMicro                                         | 1        | 0.24%   |
| iConnectivity                                   | 1        | 0.24%   |
| Hewlett-Packard                                 | 1        | 0.24%   |
| GYROCOM C&C                                     | 1        | 0.24%   |
| GN Netcom                                       | 1        | 0.24%   |
| Giga-Byte Technology                            | 1        | 0.24%   |
| Generalplus Technology                          | 1        | 0.24%   |
| Focusrite-Novation                              | 1        | 0.24%   |
| FiiO Electronics Technology                     | 1        | 0.24%   |
| Cooler Master                                   | 1        | 0.24%   |
| Cambridge Silicon Radio                         | 1        | 0.24%   |
| BEHRINGER International                         | 1        | 0.24%   |
| ASUSTek Computer                                | 1        | 0.24%   |
| AKAI Professional M.I.                          | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 57       | 11.9%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 23       | 4.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 18       | 3.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 17       | 3.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 17       | 3.55%   |
| Nvidia GP104 High Definition Audio Controller                           | 14       | 2.92%   |
| Nvidia GP107GL High Definition Audio Controller                         | 13       | 2.71%   |
| AMD Family 17h/19h HD Audio Controller                                  | 13       | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 12       | 2.51%   |
| AMD Navi 10 HDMI Audio                                                  | 11       | 2.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 10       | 2.09%   |
| Intel 200 Series PCH HD Audio                                           | 10       | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 10       | 2.09%   |
| Nvidia GA104 High Definition Audio Controller                           | 9        | 1.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 8        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 8        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                           | 7        | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                           | 7        | 1.46%   |
| Intel Cannon Lake PCH cAVS                                              | 7        | 1.46%   |
| Nvidia GA102 High Definition Audio Controller                           | 6        | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 6        | 1.25%   |
| SteelSeries ApS Arctis Pro Wireless                                     | 5        | 1.04%   |
| Nvidia GK104 HDMI Audio Controller                                      | 5        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                       | 5        | 1.04%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 5        | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 5        | 1.04%   |
| Texas Instruments PCM2902 Audio Codec                                   | 4        | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 4        | 0.84%   |
| JMTek USB PnP Audio Device                                              | 4        | 0.84%   |
| Blue Microphones Yeti Stereo Microphone                                 | 4        | 0.84%   |
| Valve Software Valve VR Radio & HMD Mic                                 | 3        | 0.63%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 3        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                           | 3        | 0.63%   |
| Nvidia TU104 HD Audio Controller                                        | 3        | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                           | 3        | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3        | 0.63%   |
| Intel Alder Lake-S HD Audio Controller                                  | 3        | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                        | 3        | 0.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 3        | 0.63%   |
| C-Media Electronics USB Audio Device                                    | 3        | 0.63%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 3        | 0.63%   |
| Thesycon Systemsoftware & Consulting U90                                | 2        | 0.42%   |
| SteelSeries ApS SteelSeries Arctis 7                                    | 2        | 0.42%   |
| Sony DualShock 4 [CUH-ZCT2x]                                            | 2        | 0.42%   |
| RODE Microphones RODE NT-USB                                            | 2        | 0.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2        | 0.42%   |
| Nvidia MCP73 High Definition Audio                                      | 2        | 0.42%   |
| Nvidia GP102 HDMI Audio Controller                                      | 2        | 0.42%   |
| Nvidia GF119 HDMI Audio Controller                                      | 2        | 0.42%   |
| Nvidia GF106 High Definition Audio Controller                           | 2        | 0.42%   |
| Logitech [G533 Wireless Headset Dongle]                                 | 2        | 0.42%   |
| Kingston Technology HyperX 7.1 Audio                                    | 2        | 0.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 2        | 0.42%   |
| Intel C600/X79 series chipset High Definition Audio Controller          | 2        | 0.42%   |
| Intel Audio device                                                      | 2        | 0.42%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                     | 2        | 0.42%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                           | 2        | 0.42%   |
| C-Media Electronics Blue Snowball                                       | 2        | 0.42%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                       | 2        | 0.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2        | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 36       | 21.95%  |
| Corsair             | 33       | 20.12%  |
| Kingston            | 19       | 11.59%  |
| Crucial             | 16       | 9.76%   |
| Samsung Electronics | 12       | 7.32%   |
| Unknown             | 10       | 6.1%    |
| SK hynix            | 7        | 4.27%   |
| Patriot             | 6        | 3.66%   |
| Team                | 5        | 3.05%   |
| Micron Technology   | 5        | 3.05%   |
| A-DATA Technology   | 3        | 1.83%   |
| Ramaxel Technology  | 2        | 1.22%   |
| Unknown             | 2        | 1.22%   |
| Unknown (ABCD)      | 1        | 0.61%   |
| Unknown (0x5846)    | 1        | 0.61%   |
| Strontium           | 1        | 0.61%   |
| PNY                 | 1        | 0.61%   |
| Neo Forza           | 1        | 0.61%   |
| Golden Empire       | 1        | 0.61%   |
| GeIL                | 1        | 0.61%   |
| AMD                 | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 8        | 4.26%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s         | 5        | 2.66%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 4        | 2.13%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s        | 3        | 1.6%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s          | 2        | 1.06%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s        | 2        | 1.06%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s           | 2        | 1.06%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s           | 2        | 1.06%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                | 2        | 1.06%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s         | 2        | 1.06%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s        | 2        | 1.06%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s         | 2        | 1.06%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s         | 2        | 1.06%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s          | 2        | 1.06%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s          | 2        | 1.06%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s           | 2        | 1.06%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4096MB DIMM DDR4 2733MT/s     | 2        | 1.06%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s         | 2        | 1.06%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s        | 2        | 1.06%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                   | 2        | 1.06%   |
| Unknown                                                       | 2        | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 400MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                             | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                      | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                          | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR2                              | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM 800MT/s                           | 1        | 0.53%   |
| Unknown RAM 04S2666CL19DM 4GB DIMM DDR4 2667MT/s              | 1        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s  | 1        | 0.53%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s           | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s            | 1        | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s         | 1        | 0.53%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                 | 1        | 0.53%   |
| Team RAM Dark-1600 2GB DIMM DDR3 1600MT/s                     | 1        | 0.53%   |
| Strontium RAM SRT8G86U0-H9M 8GB DIMM DDR3 1333MT/s            | 1        | 0.53%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s   | 1        | 0.53%   |
| SK hynix RAM HYMP151F72CP4D3-Y5 4GB FB-DIMM DDR2 667MT/s      | 1        | 0.53%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                   | 1        | 0.53%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s          | 1        | 0.53%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s          | 1        | 0.53%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR2 1066MT/s          | 1        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1        | 0.53%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1        | 0.53%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s        | 1        | 0.53%   |
| Samsung RAM M393B1K70CH0-YH9 8GB DIMM DDR3 1333MT/s           | 1        | 0.53%   |
| Samsung RAM M378B5673FH0-CH9 2048MB DIMM DDR3 1600MT/s        | 1        | 0.53%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s           | 1        | 0.53%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s           | 1        | 0.53%   |
| Samsung RAM M378B1G73AH0-K0 8GB DIMM DDR3 1600MT/s            | 1        | 0.53%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s           | 1        | 0.53%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s        | 1        | 0.53%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s           | 1        | 0.53%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s       | 1        | 0.53%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 98       | 67.12%  |
| DDR3    | 31       | 21.23%  |
| Unknown | 5        | 3.42%   |
| SDRAM   | 4        | 2.74%   |
| DDR2    | 4        | 2.74%   |
| LPDDR4  | 3        | 2.05%   |
| DDR     | 1        | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 134      | 95.04%  |
| SODIMM  | 5        | 3.55%   |
| RIMM    | 1        | 0.71%   |
| FB-DIMM | 1        | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 72       | 46.45%  |
| 16384 | 32       | 20.65%  |
| 4096  | 30       | 19.35%  |
| 2048  | 11       | 7.1%    |
| 32768 | 8        | 5.16%   |
| 1024  | 2        | 1.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 34       | 20.24%  |
| 3600    | 27       | 16.07%  |
| 1600    | 19       | 11.31%  |
| 1333    | 13       | 7.74%   |
| 2400    | 9        | 5.36%   |
| 3466    | 7        | 4.17%   |
| 2667    | 7        | 4.17%   |
| 2133    | 7        | 4.17%   |
| 3000    | 4        | 2.38%   |
| 3400    | 3        | 1.79%   |
| 1867    | 3        | 1.79%   |
| 1800    | 3        | 1.79%   |
| 800     | 3        | 1.79%   |
| 3866    | 2        | 1.19%   |
| 3733    | 2        | 1.19%   |
| 3333    | 2        | 1.19%   |
| 2733    | 2        | 1.19%   |
| 2666    | 2        | 1.19%   |
| Unknown | 2        | 1.19%   |
| 65535   | 1        | 0.6%    |
| 4333    | 1        | 0.6%    |
| 4000    | 1        | 0.6%    |
| 3800    | 1        | 0.6%    |
| 3500    | 1        | 0.6%    |
| 3151    | 1        | 0.6%    |
| 3134    | 1        | 0.6%    |
| 3067    | 1        | 0.6%    |
| 3066    | 1        | 0.6%    |
| 2933    | 1        | 0.6%    |
| 2800    | 1        | 0.6%    |
| 2267    | 1        | 0.6%    |
| 2048    | 1        | 0.6%    |
| 1280    | 1        | 0.6%    |
| 1066    | 1        | 0.6%    |
| 667     | 1        | 0.6%    |
| 400     | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 50%     |
| Prolific Technology | 1        | 25%     |
| Pantum              | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 25%     |
| Pantum P2500W series          | 1        | 25%     |
| Brother Printer               | 1        | 25%     |
| Brother HL-2130 series        | 1        | 25%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 27       | 45%     |
| Microsoft                   | 5        | 8.33%   |
| Valve Software              | 3        | 5%      |
| Microdia                    | 3        | 5%      |
| Hewlett-Packard             | 3        | 5%      |
| Xiaomi                      | 1        | 1.67%   |
| Trust                       | 1        | 1.67%   |
| Tobii Technology AB         | 1        | 1.67%   |
| Sunplus IT                  | 1        | 1.67%   |
| SN0002                      | 1        | 1.67%   |
| SJ-180517-N                 | 1        | 1.67%   |
| Samsung Electronics         | 1        | 1.67%   |
| Realtek Semiconductor       | 1        | 1.67%   |
| Razer USA                   | 1        | 1.67%   |
| LG Electronics              | 1        | 1.67%   |
| Lenovo                      | 1        | 1.67%   |
| Leap Motion                 | 1        | 1.67%   |
| KYE Systems (Mouse Systems) | 1        | 1.67%   |
| Huawei Technologies         | 1        | 1.67%   |
| HTC (High Tech Computer)    | 1        | 1.67%   |
| GEMBIRD                     | 1        | 1.67%   |
| EVGA                        | 1        | 1.67%   |
| Creative Technology         | 1        | 1.67%   |
| Unknown                     | 1        | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 8        | 13.33%  |
| Logitech Webcam C270                                  | 7        | 11.67%  |
| Valve Software 3D Camera                              | 3        | 5%      |
| Microsoft LifeCam HD-3000                             | 2        | 3.33%   |
| Microdia USB 2.0 Camera                               | 2        | 3.33%   |
| Logitech Webcam C310                                  | 2        | 3.33%   |
| Logitech C922 Pro Stream Webcam                       | 2        | 3.33%   |
| HP Webcam HD 2300                                     | 2        | 3.33%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                    | 1        | 1.67%   |
| Trust Full HD Webcam                                  | 1        | 1.67%   |
| Tobii AB EyeChip                                      | 1        | 1.67%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 1        | 1.67%   |
| SN0002 1080P Web Camera                               | 1        | 1.67%   |
| SJ-180517-N 1080P Webcam                              | 1        | 1.67%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 1.67%   |
| Realtek Webcam                                        | 1        | 1.67%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 1.67%   |
| Microsoft LifeCam VX-5000                             | 1        | 1.67%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.67%   |
| Microsoft LifeCam Cinema                              | 1        | 1.67%   |
| Microdia Webcam Vitade AF                             | 1        | 1.67%   |
| Logitech Webcam C600                                  | 1        | 1.67%   |
| Logitech Webcam C170                                  | 1        | 1.67%   |
| Logitech Webcam C110                                  | 1        | 1.67%   |
| Logitech StreamCam                                    | 1        | 1.67%   |
| Logitech HD Webcam C525                               | 1        | 1.67%   |
| Logitech HD Webcam B910                               | 1        | 1.67%   |
| Logitech CrystalCam                                   | 1        | 1.67%   |
| Logitech BRIO Ultra HD Webcam                         | 1        | 1.67%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.67%   |
| Lenovo 500 RGB Camera                                 | 1        | 1.67%   |
| Leap Motion Controller                                | 1        | 1.67%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 1        | 1.67%   |
| Huawei UVC Camera                                     | 1        | 1.67%   |
| HTC (High Tech Computer) VIVE COSMOS                  | 1        | 1.67%   |
| HP Webcam 1300                                        | 1        | 1.67%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 1        | 1.67%   |
| EVGA XR1 Lite Capture Box Video                       | 1        | 1.67%   |
| Creative Live! Cam Socialize [VF0640]                 | 1        | 1.67%   |
| Unknown                                               | 1        | 1.67%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| HID Global  | 1        | 50%     |
| Alcor Micro | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| HID Global USB Reader V3            | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 172      | 86.43%  |
| 1     | 24       | 12.06%  |
| 2     | 2        | 1.01%   |
| 3     | 1        | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Network               | 6        | 21.43%  |
| Net/wireless          | 4        | 14.29%  |
| Net/ethernet          | 4        | 14.29%  |
| Graphics card         | 4        | 14.29%  |
| Chipcard              | 2        | 7.14%   |
| Camera                | 2        | 7.14%   |
| Bluetooth             | 2        | 7.14%   |
| Unassigned class      | 1        | 3.57%   |
| Sound                 | 1        | 3.57%   |
| Multimedia controller | 1        | 3.57%   |
| Dvb card              | 1        | 3.57%   |

