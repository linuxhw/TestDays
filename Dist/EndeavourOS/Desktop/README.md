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

Total: 240

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MSI        | B450 TOMAHAWK               | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
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
| MSI        | B450 TOMAHAWK               | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
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
| EndeavourOS Rolling | 128      | 74.42%  |
| EndeavourOS         | 44       | 25.58%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 171      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.12-arch1-1      | 10       | 5.03%   |
| 5.7.7-arch1-1        | 6        | 3.02%   |
| 5.17.5-arch1-1       | 5        | 2.51%   |
| 5.17.1-arch1-1       | 5        | 2.51%   |
| 5.16.2-arch1-1       | 5        | 2.51%   |
| 5.15.7-arch1-1       | 4        | 2.01%   |
| 5.11.11-arch1-1      | 4        | 2.01%   |
| 5.17.9-arch1-1       | 3        | 1.51%   |
| 5.16.16-arch1-1      | 3        | 1.51%   |
| 5.16.10-arch1-1      | 3        | 1.51%   |
| 5.15.8-arch1-1       | 3        | 1.51%   |
| 5.15.12-zen1-1-zen   | 3        | 1.51%   |
| 5.15.10-arch1-1      | 3        | 1.51%   |
| 5.14.9-arch2-1       | 3        | 1.51%   |
| 5.14.8-arch1-1       | 3        | 1.51%   |
| 5.10.88-2-lts        | 3        | 1.51%   |
| 5.9.14-arch1-1       | 2        | 1.01%   |
| 5.9.12-arch1-1       | 2        | 1.01%   |
| 5.9.1-arch1-1        | 2        | 1.01%   |
| 5.8.11-arch1-1       | 2        | 1.01%   |
| 5.8.10-arch1-1       | 2        | 1.01%   |
| 5.17.8-arch1-1       | 2        | 1.01%   |
| 5.17.5-zen1-1-zen    | 2        | 1.01%   |
| 5.16.16-zen1-1-zen   | 2        | 1.01%   |
| 5.16.11-arch1-1      | 2        | 1.01%   |
| 5.16.1-arch1-1       | 2        | 1.01%   |
| 5.15.13-zen1-1-zen   | 2        | 1.01%   |
| 5.15.11-arch2-1      | 2        | 1.01%   |
| 5.14.2-arch1-2       | 2        | 1.01%   |
| 5.14.16-arch1-1      | 2        | 1.01%   |
| 5.12.15-arch1-1      | 2        | 1.01%   |
| 5.11.6-arch1-1       | 2        | 1.01%   |
| 5.11.15-arch1-2      | 2        | 1.01%   |
| 5.11.13-arch1-1      | 2        | 1.01%   |
| 5.9.9-arch1-1        | 1        | 0.5%    |
| 5.9.8-zen1-1-zen     | 1        | 0.5%    |
| 5.9.6-zen1-1-zen     | 1        | 0.5%    |
| 5.9.2-arch1-1        | 1        | 0.5%    |
| 5.9.10-arch1-1       | 1        | 0.5%    |
| 5.9.1-6-tkg-bmq      | 1        | 0.5%    |
| 5.9.0-rc3-1-mainline | 1        | 0.5%    |
| 5.8.8-arch1-1        | 1        | 0.5%    |
| 5.8.5-zen1-1-zen     | 1        | 0.5%    |
| 5.8.5-arch1-1        | 1        | 0.5%    |
| 5.8.5-8-tkg-pds      | 1        | 0.5%    |
| 5.8.5-8-tkg-bmq      | 1        | 0.5%    |
| 5.8.12-arch1-1       | 1        | 0.5%    |
| 5.7.8-arch1-1        | 1        | 0.5%    |
| 5.7.6-arch1-1        | 1        | 0.5%    |
| 5.7.12-zen1-1-zen    | 1        | 0.5%    |
| 5.7.12-arch1-1       | 1        | 0.5%    |
| 5.6.6-arch1-1        | 1        | 0.5%    |
| 5.6.15-arch1-1       | 1        | 0.5%    |
| 5.6.10-arch1-1       | 1        | 0.5%    |
| 5.5.4-zen1-1-zen     | 1        | 0.5%    |
| 5.5.2-arch2-2        | 1        | 0.5%    |
| 5.4.90-1-lts         | 1        | 0.5%    |
| 5.18.0-arch1-1       | 1        | 0.5%    |
| 5.17.9-zen1-1-zen    | 1        | 0.5%    |
| 5.17.4-zen1-1-zen    | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 7.04%   |
| 5.17.5  | 7        | 3.52%   |
| 5.7.7   | 6        | 3.02%   |
| 5.17.1  | 5        | 2.51%   |
| 5.16.2  | 5        | 2.51%   |
| 5.16.16 | 5        | 2.51%   |
| 5.15.7  | 5        | 2.51%   |
| 5.8.5   | 4        | 2.01%   |
| 5.17.9  | 4        | 2.01%   |
| 5.11.11 | 4        | 2.01%   |
| 5.10.88 | 4        | 2.01%   |
| 5.9.1   | 3        | 1.51%   |
| 5.16.11 | 3        | 1.51%   |
| 5.16.10 | 3        | 1.51%   |
| 5.15.8  | 3        | 1.51%   |
| 5.15.13 | 3        | 1.51%   |
| 5.15.11 | 3        | 1.51%   |
| 5.15.10 | 3        | 1.51%   |
| 5.14.9  | 3        | 1.51%   |
| 5.14.8  | 3        | 1.51%   |
| 5.12.15 | 3        | 1.51%   |
| 5.9.14  | 2        | 1.01%   |
| 5.9.12  | 2        | 1.01%   |
| 5.8.11  | 2        | 1.01%   |
| 5.8.10  | 2        | 1.01%   |
| 5.7.12  | 2        | 1.01%   |
| 5.17.8  | 2        | 1.01%   |
| 5.17.4  | 2        | 1.01%   |
| 5.16.4  | 2        | 1.01%   |
| 5.16.1  | 2        | 1.01%   |
| 5.14.2  | 2        | 1.01%   |
| 5.14.16 | 2        | 1.01%   |
| 5.14.11 | 2        | 1.01%   |
| 5.13.13 | 2        | 1.01%   |
| 5.12.5  | 2        | 1.01%   |
| 5.12.4  | 2        | 1.01%   |
| 5.12.14 | 2        | 1.01%   |
| 5.11.6  | 2        | 1.01%   |
| 5.11.15 | 2        | 1.01%   |
| 5.11.13 | 2        | 1.01%   |
| 5.9.9   | 1        | 0.5%    |
| 5.9.8   | 1        | 0.5%    |
| 5.9.6   | 1        | 0.5%    |
| 5.9.2   | 1        | 0.5%    |
| 5.9.10  | 1        | 0.5%    |
| 5.9.0   | 1        | 0.5%    |
| 5.8.8   | 1        | 0.5%    |
| 5.8.12  | 1        | 0.5%    |
| 5.7.8   | 1        | 0.5%    |
| 5.7.6   | 1        | 0.5%    |
| 5.6.6   | 1        | 0.5%    |
| 5.6.15  | 1        | 0.5%    |
| 5.6.10  | 1        | 0.5%    |
| 5.5.4   | 1        | 0.5%    |
| 5.5.2   | 1        | 0.5%    |
| 5.4.90  | 1        | 0.5%    |
| 5.18.0  | 1        | 0.5%    |
| 5.17.3  | 1        | 0.5%    |
| 5.17.0  | 1        | 0.5%    |
| 5.16.7  | 1        | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 41       | 21.13%  |
| 5.16    | 25       | 12.89%  |
| 5.17    | 22       | 11.34%  |
| 5.14    | 17       | 8.76%   |
| 5.10    | 15       | 7.73%   |
| 5.11    | 14       | 7.22%   |
| 5.9     | 13       | 6.7%    |
| 5.12    | 13       | 6.7%    |
| 5.8     | 10       | 5.15%   |
| 5.7     | 9        | 4.64%   |
| 5.13    | 7        | 3.61%   |
| 5.6     | 3        | 1.55%   |
| 5.5     | 2        | 1.03%   |
| 5.4     | 1        | 0.52%   |
| 5.18    | 1        | 0.52%   |
| Unknown | 1        | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 171      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 61       | 33.15%  |
| GNOME           | 37       | 20.11%  |
| XFCE            | 32       | 17.39%  |
| X-Cinnamon      | 12       | 6.52%   |
| KDE             | 11       | 5.98%   |
| i3              | 9        | 4.89%   |
| Budgie          | 5        | 2.72%   |
| Cinnamon        | 4        | 2.17%   |
| sway            | 3        | 1.63%   |
| MATE            | 2        | 1.09%   |
| LXQt            | 2        | 1.09%   |
| Unknown         | 2        | 1.09%   |
| jwm             | 1        | 0.54%   |
| herbstluftwm    | 1        | 0.54%   |
| GNOME Flashback | 1        | 0.54%   |
| awesome         | 1        | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 152      | 85.88%  |
| Wayland | 17       | 9.6%    |
| Tty     | 5        | 2.82%   |
| Unknown | 2        | 1.13%   |
| Web     | 1        | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 48       | 27.12%  |
| SDDM    | 46       | 25.99%  |
| Unknown | 43       | 24.29%  |
| TDM     | 20       | 11.3%   |
| GDM     | 20       | 11.3%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 84       | 48.84%  |
| de_DE   | 17       | 9.88%   |
| en_GB   | 11       | 6.4%    |
| it_IT   | 7        | 4.07%   |
| pl_PL   | 6        | 3.49%   |
| en_CA   | 5        | 2.91%   |
| ru_RU   | 3        | 1.74%   |
| nl_NL   | 3        | 1.74%   |
| fr_FR   | 3        | 1.74%   |
| es_AR   | 3        | 1.74%   |
| pt_BR   | 2        | 1.16%   |
| nl_BE   | 2        | 1.16%   |
| es_MX   | 2        | 1.16%   |
| en_HK   | 2        | 1.16%   |
| en_DK   | 2        | 1.16%   |
| en_AU   | 2        | 1.16%   |
| Unknown | 2        | 1.16%   |
| tr_TR   | 1        | 0.58%   |
| sv_SE   | 1        | 0.58%   |
| sl_SI   | 1        | 0.58%   |
| hu_HU   | 1        | 0.58%   |
| fr_CA   | 1        | 0.58%   |
| es_GT   | 1        | 0.58%   |
| es_ES   | 1        | 0.58%   |
| es_CR   | 1        | 0.58%   |
| eo      | 1        | 0.58%   |
| en_ZA   | 1        | 0.58%   |
| en_SG   | 1        | 0.58%   |
| en_IN   | 1        | 0.58%   |
| en_FI   | 1        | 0.58%   |
| de_CH   | 1        | 0.58%   |
| de_AT   | 1        | 0.58%   |
| cs_CZ   | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 102      | 58.62%  |
| BIOS | 72       | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 121      | 70.35%  |
| Btrfs   | 47       | 27.33%  |
| XXX4    | 1        | 0.58%   |
| Xfs     | 1        | 0.58%   |
| Overlay | 1        | 0.58%   |
| F2fs    | 1        | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 111      | 64.16%  |
| Unknown | 47       | 27.17%  |
| MBR     | 15       | 8.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 76.88%  |
| Yes       | 40       | 23.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 56.57%  |
| Yes       | 76       | 43.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 50       | 29.24%  |
| Gigabyte Technology | 40       | 23.39%  |
| MSI                 | 29       | 16.96%  |
| ASRock              | 18       | 10.53%  |
| Hewlett-Packard     | 9        | 5.26%   |
| Dell                | 8        | 4.68%   |
| Lenovo              | 6        | 3.51%   |
| Fujitsu             | 2        | 1.17%   |
| Biostar             | 2        | 1.17%   |
| UMAX                | 1        | 0.58%   |
| Samsung Electronics | 1        | 0.58%   |
| Positivo            | 1        | 0.58%   |
| LattePanda          | 1        | 0.58%   |
| Intel               | 1        | 0.58%   |
| Acer                | 1        | 0.58%   |
| Unknown             | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 3.51%   |
| MSI MS-7C02                            | 4        | 2.34%   |
| ASUS ROG STRIX X570-E GAMING           | 4        | 2.34%   |
| MSI MS-7C37                            | 3        | 1.75%   |
| MSI MS-7A38                            | 3        | 1.75%   |
| Gigabyte B550M AORUS PRO               | 3        | 1.75%   |
| ASUS TUF Gaming X570-PLUS              | 3        | 1.75%   |
| ASRock B450M Pro4                      | 3        | 1.75%   |
| MSI MS-7C84                            | 2        | 1.17%   |
| MSI MS-7B86                            | 2        | 1.17%   |
| MSI MS-7850                            | 2        | 1.17%   |
| MSI MS-7798                            | 2        | 1.17%   |
| HP Z230 Tower Workstation              | 2        | 1.17%   |
| Gigabyte H110M-S2                      | 2        | 1.17%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 1.17%   |
| Gigabyte B450M DS3H                    | 2        | 1.17%   |
| Gigabyte B450 AORUS ELITE              | 2        | 1.17%   |
| Biostar G31-M7 TE                      | 2        | 1.17%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 2        | 1.17%   |
| ASUS K30AD_M31AD_M51AD                 | 2        | 1.17%   |
| ASRock B550M Steel Legend              | 2        | 1.17%   |
| ASRock B450 Pro4                       | 2        | 1.17%   |
| UMAX J42 Nano                          | 1        | 0.58%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.58%   |
| Positivo POS-PIH81DI                   | 1        | 0.58%   |
| MSI MS-7C91                            | 1        | 0.58%   |
| MSI MS-7C75                            | 1        | 0.58%   |
| MSI MS-7A34                            | 1        | 0.58%   |
| MSI MS-7A32                            | 1        | 0.58%   |
| MSI MS-7A31                            | 1        | 0.58%   |
| MSI MS-7994                            | 1        | 0.58%   |
| MSI MS-7978                            | 1        | 0.58%   |
| MSI MS-7821                            | 1        | 0.58%   |
| MSI MS-7808                            | 1        | 0.58%   |
| MSI MS-7592                            | 1        | 0.58%   |
| MSI MS-7366                            | 1        | 0.58%   |
| Lenovo ThinkStation C20 426593U        | 1        | 0.58%   |
| Lenovo ThinkCentre M93p 10AAS03T00     | 1        | 0.58%   |
| Lenovo ThinkCentre M92p 32383L6        | 1        | 0.58%   |
| Lenovo ThinkCentre M710q 10MR0009US    | 1        | 0.58%   |
| Lenovo IdeaCentre 510-15ICB 90HU002QGE | 1        | 0.58%   |
| Lenovo IdeaCentre 510-15ICB 90HU002JSP | 1        | 0.58%   |
| LattePanda Alpha                       | 1        | 0.58%   |
| Intel DH55HC AAE70933-504              | 1        | 0.58%   |
| HP Z2 Tower G4 Workstation             | 1        | 0.58%   |
| HP xw8400 Workstation                  | 1        | 0.58%   |
| HP Pavilion Gaming Desktop TG01-2xxx   | 1        | 0.58%   |
| HP Pavilion Desktop TP01-2xxx          | 1        | 0.58%   |
| HP Desktop M01-F0xxx                   | 1        | 0.58%   |
| HP Compaq 8000 Elite CMT PC            | 1        | 0.58%   |
| HP 700-502ng                           | 1        | 0.58%   |
| Gigabyte Z97X-Gaming 5                 | 1        | 0.58%   |
| Gigabyte Z97X-Gaming 3                 | 1        | 0.58%   |
| Gigabyte Z77X-D3H                      | 1        | 0.58%   |
| Gigabyte Z390 GAMING SLI               | 1        | 0.58%   |
| Gigabyte Z390 AORUS PRO                | 1        | 0.58%   |
| Gigabyte Z170-Gaming K3                | 1        | 0.58%   |
| Gigabyte X58A-UD3R                     | 1        | 0.58%   |
| Gigabyte X570 I AORUS PRO WIFI         | 1        | 0.58%   |
| Gigabyte X570 AORUS ULTRA              | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 14       | 8.19%   |
| ASUS TUF             | 9        | 5.26%   |
| ASUS PRIME           | 7        | 4.09%   |
| ASUS All             | 6        | 3.51%   |
| Dell OptiPlex        | 5        | 2.92%   |
| MSI MS-7C02          | 4        | 2.34%   |
| Gigabyte X570        | 4        | 2.34%   |
| Gigabyte B450        | 4        | 2.34%   |
| ASRock B450          | 4        | 2.34%   |
| MSI MS-7C37          | 3        | 1.75%   |
| MSI MS-7A38          | 3        | 1.75%   |
| Lenovo ThinkCentre   | 3        | 1.75%   |
| Gigabyte B550M       | 3        | 1.75%   |
| Gigabyte B550        | 3        | 1.75%   |
| Gigabyte B450M       | 3        | 1.75%   |
| ASRock B550M         | 3        | 1.75%   |
| ASRock B450M         | 3        | 1.75%   |
| MSI MS-7C84          | 2        | 1.17%   |
| MSI MS-7B86          | 2        | 1.17%   |
| MSI MS-7850          | 2        | 1.17%   |
| MSI MS-7798          | 2        | 1.17%   |
| Lenovo IdeaCentre    | 2        | 1.17%   |
| HP Z230              | 2        | 1.17%   |
| HP Pavilion          | 2        | 1.17%   |
| Gigabyte Z97X-Gaming | 2        | 1.17%   |
| Gigabyte Z390        | 2        | 1.17%   |
| Gigabyte H110M-S2    | 2        | 1.17%   |
| Fujitsu CELSIUS      | 2        | 1.17%   |
| Biostar G31-M7       | 2        | 1.17%   |
| ASUS STRIX           | 2        | 1.17%   |
| ASUS K30AD           | 2        | 1.17%   |
| UMAX J42             | 1        | 0.58%   |
| Samsung 500T8A       | 1        | 0.58%   |
| Positivo POS-PIH81DI | 1        | 0.58%   |
| MSI MS-7C91          | 1        | 0.58%   |
| MSI MS-7C75          | 1        | 0.58%   |
| MSI MS-7A34          | 1        | 0.58%   |
| MSI MS-7A32          | 1        | 0.58%   |
| MSI MS-7A31          | 1        | 0.58%   |
| MSI MS-7994          | 1        | 0.58%   |
| MSI MS-7978          | 1        | 0.58%   |
| MSI MS-7821          | 1        | 0.58%   |
| MSI MS-7808          | 1        | 0.58%   |
| MSI MS-7592          | 1        | 0.58%   |
| MSI MS-7366          | 1        | 0.58%   |
| Lenovo ThinkStation  | 1        | 0.58%   |
| LattePanda Alpha     | 1        | 0.58%   |
| Intel DH55HC         | 1        | 0.58%   |
| HP Z2                | 1        | 0.58%   |
| HP xw8400            | 1        | 0.58%   |
| HP Desktop           | 1        | 0.58%   |
| HP Compaq            | 1        | 0.58%   |
| HP 700-502ng         | 1        | 0.58%   |
| Gigabyte Z77X-D3H    | 1        | 0.58%   |
| Gigabyte Z170-Gaming | 1        | 0.58%   |
| Gigabyte X58A-UD3R   | 1        | 0.58%   |
| Gigabyte X470        | 1        | 0.58%   |
| Gigabyte X399        | 1        | 0.58%   |
| Gigabyte TRX40       | 1        | 0.58%   |
| Gigabyte P55A-UD3    | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 32       | 18.71%  |
| 2019 | 31       | 18.13%  |
| 2020 | 22       | 12.87%  |
| 2013 | 13       | 7.6%    |
| 2021 | 12       | 7.02%   |
| 2017 | 11       | 6.43%   |
| 2014 | 11       | 6.43%   |
| 2012 | 11       | 6.43%   |
| 2016 | 8        | 4.68%   |
| 2011 | 5        | 2.92%   |
| 2009 | 5        | 2.92%   |
| 2008 | 3        | 1.75%   |
| 2007 | 3        | 1.75%   |
| 2015 | 2        | 1.17%   |
| 2010 | 2        | 1.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 171      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 170      | 99.42%  |
| Enabled  | 1        | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 171      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 60       | 34.68%  |
| 32.01-64.0  | 44       | 25.43%  |
| 8.01-16.0   | 27       | 15.61%  |
| 4.01-8.0    | 12       | 6.94%   |
| 24.01-32.0  | 11       | 6.36%   |
| 64.01-256.0 | 10       | 5.78%   |
| 3.01-4.0    | 9        | 5.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 46       | 24.86%  |
| 2.01-3.0   | 40       | 21.62%  |
| 1.01-2.0   | 40       | 21.62%  |
| 3.01-4.0   | 31       | 16.76%  |
| 8.01-16.0  | 19       | 10.27%  |
| 0.51-1.0   | 5        | 2.7%    |
| 16.01-24.0 | 3        | 1.62%   |
| 24.01-32.0 | 1        | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 55       | 31.07%  |
| 3      | 34       | 19.21%  |
| 4      | 31       | 17.51%  |
| 1      | 28       | 15.82%  |
| 5      | 20       | 11.3%   |
| 7      | 3        | 1.69%   |
| 6      | 3        | 1.69%   |
| 9      | 1        | 0.56%   |
| 8      | 1        | 0.56%   |
| 0      | 1        | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 75%     |
| Yes       | 43       | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 170      | 99.42%  |
| No        | 1        | 0.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 50.29%  |
| No        | 86       | 49.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 52.3%   |
| Yes       | 83       | 47.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 44       | 25.73%  |
| Germany             | 25       | 14.62%  |
| Italy               | 10       | 5.85%   |
| France              | 8        | 4.68%   |
| Canada              | 8        | 4.68%   |
| Poland              | 7        | 4.09%   |
| UK                  | 6        | 3.51%   |
| Netherlands         | 6        | 3.51%   |
| Belgium             | 6        | 3.51%   |
| Brazil              | 4        | 2.34%   |
| Austria             | 4        | 2.34%   |
| Switzerland         | 3        | 1.75%   |
| Mexico              | 3        | 1.75%   |
| Argentina           | 3        | 1.75%   |
| Sweden              | 2        | 1.17%   |
| Spain               | 2        | 1.17%   |
| Slovenia            | 2        | 1.17%   |
| Norway              | 2        | 1.17%   |
| India               | 2        | 1.17%   |
| Hungary             | 2        | 1.17%   |
| Hong Kong           | 2        | 1.17%   |
| Czechia             | 2        | 1.17%   |
| Australia           | 2        | 1.17%   |
| Turkey              | 1        | 0.58%   |
| Trinidad and Tobago | 1        | 0.58%   |
| South Korea         | 1        | 0.58%   |
| South Africa        | 1        | 0.58%   |
| Singapore           | 1        | 0.58%   |
| Russia              | 1        | 0.58%   |
| Portugal            | 1        | 0.58%   |
| Lithuania           | 1        | 0.58%   |
| Jordan              | 1        | 0.58%   |
| Guatemala           | 1        | 0.58%   |
| Greece              | 1        | 0.58%   |
| Finland             | 1        | 0.58%   |
| Denmark             | 1        | 0.58%   |
| Costa Rica          | 1        | 0.58%   |
| Chile               | 1        | 0.58%   |
| Bulgaria            | 1        | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Berlin                      | 5        | 2.78%   |
| Turin                       | 3        | 1.67%   |
| Ottawa                      | 3        | 1.67%   |
| Zurich                      | 2        | 1.11%   |
| Warsaw                      | 2        | 1.11%   |
| Tuen Mun                    | 2        | 1.11%   |
| Toronto                     | 2        | 1.11%   |
| Snohomish                   | 2        | 1.11%   |
| Schiedam                    | 2        | 1.11%   |
| Porth                       | 2        | 1.11%   |
| Leipzig                     | 2        | 1.11%   |
| Hamburg                     | 2        | 1.11%   |
| Geesteren                   | 2        | 1.11%   |
| Barbentane                  | 2        | 1.11%   |
| Zapopan                     | 1        | 0.56%   |
| Wroclaw                     | 1        | 0.56%   |
| Whiteville                  | 1        | 0.56%   |
| Weybridge                   | 1        | 0.56%   |
| Westminster                 | 1        | 0.56%   |
| West Haddon                 | 1        | 0.56%   |
| Vilnius                     | 1        | 0.56%   |
| Villanova                   | 1        | 0.56%   |
| Villa Ballester             | 1        | 0.56%   |
| Vienna                      | 1        | 0.56%   |
| Union                       | 1        | 0.56%   |
| Toledo                      | 1        | 0.56%   |
| Tempe                       | 1        | 0.56%   |
| Sullivan                    | 1        | 0.56%   |
| Stuttgart                   | 1        | 0.56%   |
| Stapelfeld                  | 1        | 0.56%   |
| St Petersburg               | 1        | 0.56%   |
| Spring Field                | 1        | 0.56%   |
| Spring                      | 1        | 0.56%   |
| Spijkenisse                 | 1        | 0.56%   |
| Sopron                      | 1        | 0.56%   |
| Sofia                       | 1        | 0.56%   |
| Singapore                   | 1        | 0.56%   |
| Sheboygan                   | 1        | 0.56%   |
| Seoul                       | 1        | 0.56%   |
| Senonches                   | 1        | 0.56%   |
| Schorndorf                  | 1        | 0.56%   |
| Schaarbeek                  | 1        | 0.56%   |
| Santiago                    | 1        | 0.56%   |
| Santa Clarita               | 1        | 0.56%   |
| Santa Ana                   | 1        | 0.56%   |
| San Vendemiano-Fossamerlo   | 1        | 0.56%   |
| San Nicolás de los Arroyos | 1        | 0.56%   |
| Salvador                    | 1        | 0.56%   |
| Sala                        | 1        | 0.56%   |
| Rotterdam                   | 1        | 0.56%   |
| Ripollet                    | 1        | 0.56%   |
| Ringgold                    | 1        | 0.56%   |
| Ribeirao das Neves          | 1        | 0.56%   |
| Renton                      | 1        | 0.56%   |
| Pune                        | 1        | 0.56%   |
| Praia Grande                | 1        | 0.56%   |
| Prague                      | 1        | 0.56%   |
| Pont-y-clun                 | 1        | 0.56%   |
| Pipe Creek                  | 1        | 0.56%   |
| Peachtree Corners           | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 74       | 127    | 19.27%  |
| Samsung Electronics | 72       | 129    | 18.75%  |
| Seagate             | 65       | 95     | 16.93%  |
| Crucial             | 26       | 42     | 6.77%   |
| Kingston            | 25       | 46     | 6.51%   |
| Toshiba             | 15       | 20     | 3.91%   |
| SanDisk             | 13       | 16     | 3.39%   |
| Phison              | 9        | 10     | 2.34%   |
| Intel               | 8        | 11     | 2.08%   |
| Hitachi             | 7        | 7      | 1.82%   |
| A-DATA Technology   | 6        | 12     | 1.56%   |
| Micron Technology   | 5        | 7      | 1.3%    |
| SPCC                | 4        | 4      | 1.04%   |
| Corsair             | 4        | 4      | 1.04%   |
| Unknown             | 3        | 4      | 0.78%   |
| PNY                 | 3        | 3      | 0.78%   |
| OCZ                 | 3        | 3      | 0.78%   |
| Intenso             | 3        | 3      | 0.78%   |
| XPG                 | 2        | 2      | 0.52%   |
| Leven               | 2        | 2      | 0.52%   |
| JMicron             | 2        | 2      | 0.52%   |
| HGST                | 2        | 2      | 0.52%   |
| Gigabyte Technology | 2        | 3      | 0.52%   |
| China               | 2        | 2      | 0.52%   |
| USB3.1              | 1        | 1      | 0.26%   |
| UMAX                | 1        | 1      | 0.26%   |
| Transcend           | 1        | 1      | 0.26%   |
| T-FORCE             | 1        | 1      | 0.26%   |
| SK Hynix            | 1        | 1      | 0.26%   |
| SABRENT             | 1        | 1      | 0.26%   |
| Realtek             | 1        | 1      | 0.26%   |
| PLEXTOR             | 1        | 1      | 0.26%   |
| Pioneer             | 1        | 3      | 0.26%   |
| PI-041              | 1        | 1      | 0.26%   |
| Phison Electronics  | 1        | 1      | 0.26%   |
| Patriot             | 1        | 2      | 0.26%   |
| Netac               | 1        | 1      | 0.26%   |
| Mushkin             | 1        | 1      | 0.26%   |
| MAXTOR              | 1        | 1      | 0.26%   |
| Maxone              | 1        | 1      | 0.26%   |
| LITEONIT            | 1        | 1      | 0.26%   |
| Lexar               | 1        | 1      | 0.26%   |
| LDLC                | 1        | 1      | 0.26%   |
| KIOXIA              | 1        | 1      | 0.26%   |
| Kingmax             | 1        | 2      | 0.26%   |
| imation             | 1        | 1      | 0.26%   |
| HPE                 | 1        | 1      | 0.26%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| DREVO               | 1        | 1      | 0.26%   |
| ASMT                | 1        | 2      | 0.26%   |
| ASMedia             | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Crucial CT500MX500SSD1 500GB     | 9        | 1.88%   |
| Seagate ST2000DM008-2FR102 2TB   | 8        | 1.67%   |
| Samsung SSD 860 EVO 1TB          | 8        | 1.67%   |
| Seagate ST4000DM004-2CV104 4TB   | 7        | 1.46%   |
| Samsung SSD 860 EVO 500GB        | 7        | 1.46%   |
| Kingston SA400S37120G 120GB SSD  | 7        | 1.46%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 1.25%   |
| WDC WD10EZEX-00BN5A0 1TB         | 6        | 1.25%   |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 1.25%   |
| Samsung SSD 850 EVO 500GB        | 6        | 1.25%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB   | 5        | 1.04%   |
| Seagate Expansion Desk 10TB      | 4        | 0.83%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 0.83%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.83%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.63%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 3        | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 3        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.63%   |
| WDC WD10EZEX-00RKKA0 1TB         | 3        | 0.63%   |
| Toshiba HDWD110 1TB              | 3        | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 0.63%   |
| Samsung SSD 970 EVO 500GB        | 3        | 0.63%   |
| Samsung SSD 970 EVO 1TB          | 3        | 0.63%   |
| Samsung SSD 960 EVO 500GB        | 3        | 0.63%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.63%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.63%   |
| Samsung SSD 840 EVO 120GB        | 3        | 0.63%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 0.63%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 0.63%   |
| Kingston NVMe SSD Drive 1TB      | 3        | 0.63%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.42%   |
| WDC WDS100T3XHC-00SJG0 1TB       | 2        | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2        | 0.42%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 0.42%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.42%   |
| WDC WD10EZRX-00A8LB0 1TB         | 2        | 0.42%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.42%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.42%   |
| WDC WD10EACS-00D6B1 1TB          | 2        | 0.42%   |
| WDC WD100EMAZ-00WJTA0 10TB       | 2        | 0.42%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 2        | 0.42%   |
| Unknown SD/MMC/MS PRO 999GB      | 2        | 0.42%   |
| Toshiba THNSNJ256GCSU 256GB SSD  | 2        | 0.42%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.42%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.42%   |
| Toshiba A100 120GB SSD           | 2        | 0.42%   |
| SPCC Solid State Disk 240GB      | 2        | 0.42%   |
| Seagate ST95005620AS 500GB       | 2        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.42%   |
| Seagate ST1000VM002-1CT162 1TB   | 2        | 0.42%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.42%   |
| Seagate Expansion 4TB            | 2        | 0.42%   |
| SanDisk SSD PLUS 240GB           | 2        | 0.42%   |
| Sandisk NVMe SSD Drive 500GB     | 2        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 64       | 94     | 41.03%  |
| WDC                 | 56       | 85     | 35.9%   |
| Toshiba             | 12       | 13     | 7.69%   |
| Hitachi             | 7        | 7      | 4.49%   |
| Samsung Electronics | 5        | 9      | 3.21%   |
| Unknown             | 2        | 2      | 1.28%   |
| HGST                | 2        | 2      | 1.28%   |
| SABRENT             | 1        | 1      | 0.64%   |
| PI-041              | 1        | 1      | 0.64%   |
| MAXTOR              | 1        | 1      | 0.64%   |
| Maxone              | 1        | 1      | 0.64%   |
| JMicron             | 1        | 1      | 0.64%   |
| HPE                 | 1        | 1      | 0.64%   |
| ASMT                | 1        | 2      | 0.64%   |
| ASMedia             | 1        | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 54       | 81     | 32.73%  |
| Crucial             | 23       | 31     | 13.94%  |
| Kingston            | 18       | 36     | 10.91%  |
| WDC                 | 14       | 19     | 8.48%   |
| SanDisk             | 10       | 12     | 6.06%   |
| Micron Technology   | 5        | 7      | 3.03%   |
| Intel               | 5        | 7      | 3.03%   |
| Toshiba             | 4        | 6      | 2.42%   |
| OCZ                 | 3        | 3      | 1.82%   |
| Intenso             | 3        | 3      | 1.82%   |
| SPCC                | 2        | 2      | 1.21%   |
| PNY                 | 2        | 2      | 1.21%   |
| Leven               | 2        | 2      | 1.21%   |
| Corsair             | 2        | 2      | 1.21%   |
| China               | 2        | 2      | 1.21%   |
| A-DATA Technology   | 2        | 2      | 1.21%   |
| UMAX                | 1        | 1      | 0.61%   |
| Transcend           | 1        | 1      | 0.61%   |
| Pioneer             | 1        | 3      | 0.61%   |
| PHISON              | 1        | 1      | 0.61%   |
| Patriot             | 1        | 2      | 0.61%   |
| Mushkin             | 1        | 1      | 0.61%   |
| LITEONIT            | 1        | 1      | 0.61%   |
| LDLC                | 1        | 1      | 0.61%   |
| Kingmax             | 1        | 2      | 0.61%   |
| JMicron             | 1        | 1      | 0.61%   |
| imation             | 1        | 1      | 0.61%   |
| Hewlett-Packard     | 1        | 1      | 0.61%   |
| Gigabyte Technology | 1        | 1      | 0.61%   |
| DREVO               | 1        | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 119      | 235    | 37.66%  |
| HDD     | 116      | 221    | 36.71%  |
| NVMe    | 78       | 128    | 24.68%  |
| Unknown | 3        | 4      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 155      | 433    | 60.55%  |
| NVMe | 78       | 127    | 30.47%  |
| SAS  | 23       | 28     | 8.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 110      | 224    | 39.57%  |
| 0.51-1.0   | 84       | 123    | 30.22%  |
| 1.01-2.0   | 39       | 52     | 14.03%  |
| 3.01-4.0   | 17       | 25     | 6.12%   |
| 2.01-3.0   | 13       | 15     | 4.68%   |
| 4.01-10.0  | 12       | 14     | 4.32%   |
| 10.01-20.0 | 3        | 3      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 44       | 24.72%  |
| More than 3000 | 31       | 17.42%  |
| 501-1000       | 27       | 15.17%  |
| 101-250        | 20       | 11.24%  |
| 251-500        | 19       | 10.67%  |
| 2001-3000      | 18       | 10.11%  |
| Unknown        | 12       | 6.74%   |
| 51-100         | 4        | 2.25%   |
| 1-20           | 2        | 1.12%   |
| 21-50          | 1        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 27       | 14.21%  |
| 251-500        | 26       | 13.68%  |
| 1001-2000      | 26       | 13.68%  |
| 101-250        | 23       | 12.11%  |
| 1-20           | 23       | 12.11%  |
| 51-100         | 22       | 11.58%  |
| More than 3000 | 13       | 6.84%   |
| 21-50          | 12       | 6.32%   |
| Unknown        | 12       | 6.32%   |
| 2001-3000      | 6        | 3.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AZRX-00A8LB0 500GB          | 1        | 1      | 5%      |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 5%      |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5%      |
| WDC WD2002FYPS-01U1B0 2TB             | 1        | 1      | 5%      |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 5%      |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 5%      |
| Seagate ST9320325AS 320GB             | 1        | 4      | 5%      |
| Seagate ST6000VX0023-2EF110 6TB       | 1        | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 5%      |
| Seagate ST3320620AS 320GB             | 1        | 1      | 5%      |
| Samsung Electronics SSD 960 EVO 500GB | 1        | 1      | 5%      |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 5%      |
| OCZ VERTEX3 240GB SSD                 | 1        | 1      | 5%      |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB         | 1        | 1      | 5%      |
| DREVO X1 SSD 120GB                    | 1        | 1      | 5%      |
| Crucial CT500MX500SSD1 500GB          | 1        | 2      | 5%      |
| Crucial CT1050MX300SSD1 1050GB        | 1        | 1      | 5%      |
| Corsair Force LS SSD 120GB            | 1        | 1      | 5%      |
| ASMT ASM1156-PM 3TB                   | 1        | 2      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 26.32%  |
| Seagate             | 3        | 7      | 15.79%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| Crucial             | 2        | 3      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| OCZ                 | 1        | 1      | 5.26%   |
| Kingston            | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| DREVO               | 1        | 1      | 5.26%   |
| Corsair             | 1        | 1      | 5.26%   |
| ASMT                | 1        | 2      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 41.67%  |
| Seagate             | 3        | 7      | 25%     |
| Toshiba             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| ASMT                | 1        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 18     | 66.67%  |
| SSD  | 5        | 7      | 27.78%  |
| NVMe | 1        | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB | 1        | 1      | 100%    |

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
| Works    | 124      | 374    | 60.49%  |
| Detected | 63       | 187    | 30.73%  |
| Malfunc  | 17       | 26     | 8.29%   |
| Failed   | 1        | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 86       | 30.39%  |
| Intel                          | 83       | 29.33%  |
| Samsung Electronics            | 30       | 10.6%   |
| Sandisk                        | 21       | 7.42%   |
| Phison Electronics             | 14       | 4.95%   |
| ASMedia Technology             | 13       | 4.59%   |
| Kingston Technology Company    | 7        | 2.47%   |
| Marvell Technology Group       | 5        | 1.77%   |
| Realtek Semiconductor          | 4        | 1.41%   |
| Micron/Crucial Technology      | 3        | 1.06%   |
| JMicron Technology             | 3        | 1.06%   |
| ADATA Technology               | 3        | 1.06%   |
| Silicon Motion                 | 2        | 0.71%   |
| Nvidia                         | 2        | 0.71%   |
| Toshiba America Info Systems   | 1        | 0.35%   |
| Solid State Storage Technology | 1        | 0.35%   |
| SK Hynix                       | 1        | 0.35%   |
| Seagate Technology             | 1        | 0.35%   |
| Micron Technology              | 1        | 0.35%   |
| LSI Logic / Symbios Logic      | 1        | 0.35%   |
| KIOXIA                         | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 57       | 17.01%  |
| AMD 400 Series Chipset SATA Controller                                           | 33       | 9.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18       | 5.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14       | 4.18%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 13       | 3.88%   |
| AMD 500 Series Chipset SATA Controller                                           | 13       | 3.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10       | 2.99%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 8        | 2.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8        | 2.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7        | 2.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7        | 2.09%   |
| Phison E12 NVMe Controller                                                       | 7        | 2.09%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6        | 1.79%   |
| Intel SATA Controller [RAID mode]                                                | 6        | 1.79%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5        | 1.49%   |
| Kingston Company A2000 NVMe SSD                                                  | 5        | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5        | 1.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5        | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5        | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3        | 0.9%    |
| Samsung NVMe SSD Controller 980                                                  | 3        | 0.9%    |
| Realtek Realtek Non-Volatile memory controller                                   | 3        | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3        | 0.9%    |
| Kingston Company KC2000 NVMe SSD                                                 | 3        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3        | 0.9%    |
| AMD X370 Series Chipset SATA Controller                                          | 3        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 0.9%    |
| AMD FCH SATA Controller D                                                        | 3        | 0.9%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 3        | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.6%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2        | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2        | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 2        | 0.6%    |
| AMD X399 Series Chipset SATA Controller                                          | 2        | 0.6%    |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.6%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1        | 0.3%    |
| Solid State Storage Non-Volatile memory controller                               | 1        | 0.3%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1        | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.3%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1        | 0.3%    |
| Seagate FireCuda 520 SSD                                                         | 1        | 0.3%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.3%    |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1        | 0.3%    |
| Phison E7 NVMe Controller                                                        | 1        | 0.3%    |
| Phison E18 PCIe4 NVMe Controller                                                 | 1        | 0.3%    |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1        | 0.3%    |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.3%    |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.3%    |
| Nvidia MCP61 IDE                                                                 | 1        | 0.3%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 0.3%    |
| Micron Non-Volatile memory controller                                            | 1        | 0.3%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1        | 0.3%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.3%    |
| Marvell Group 88SE912x IDE Controller                                            | 1        | 0.3%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 156      | 60.7%   |
| NVMe | 78       | 30.35%  |
| IDE  | 16       | 6.23%   |
| RAID | 6        | 2.33%   |
| SAS  | 1        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 87       | 50.88%  |
| Intel  | 84       | 49.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 6.43%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 5.26%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 4.09%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 3.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 2.92%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 2.34%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 2.34%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 2.34%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 2.34%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.34%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.75%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 1.75%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.17%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.17%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.17%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 1.17%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.17%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.17%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.17%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.17%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.58%   |
| Intel Xeon CPU W5580 @ 3.20GHz              | 1        | 0.58%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.58%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.58%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.58%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.58%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.58%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 0.58%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.58%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 0.58%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.58%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.58%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.58%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 1        | 0.58%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.58%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.58%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.58%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.58%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.58%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 0.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.58%   |
| Intel Core i5-6500TE CPU @ 2.30GHz          | 1        | 0.58%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.58%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.58%   |
| Intel Core i5-4460S CPU @ 2.90GHz           | 1        | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.58%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 36       | 21.05%  |
| Intel Core i5           | 30       | 17.54%  |
| Intel Core i7           | 24       | 14.04%  |
| AMD Ryzen 7             | 24       | 14.04%  |
| AMD Ryzen 9             | 14       | 8.19%   |
| Intel Xeon              | 8        | 4.68%   |
| Intel Core i3           | 6        | 3.51%   |
| Other                   | 3        | 1.75%   |
| Intel Core 2 Quad       | 3        | 1.75%   |
| AMD Ryzen Threadripper  | 3        | 1.75%   |
| AMD Ryzen 3             | 3        | 1.75%   |
| AMD FX                  | 3        | 1.75%   |
| Intel Core 2 Duo        | 2        | 1.17%   |
| Intel Celeron           | 2        | 1.17%   |
| Intel Pentium Gold      | 1        | 0.58%   |
| Intel Pentium Dual-Core | 1        | 0.58%   |
| Intel Pentium Dual      | 1        | 0.58%   |
| Intel Pentium           | 1        | 0.58%   |
| Intel Core m3           | 1        | 0.58%   |
| Intel Core i9           | 1        | 0.58%   |
| AMD Phenom II X4        | 1        | 0.58%   |
| AMD Athlon X4           | 1        | 0.58%   |
| AMD Athlon II X4        | 1        | 0.58%   |
| AMD A8                  | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 64       | 37.21%  |
| 6      | 44       | 25.58%  |
| 8      | 27       | 15.7%   |
| 2      | 16       | 9.3%    |
| 12     | 13       | 7.56%   |
| 16     | 4        | 2.33%   |
| 3      | 2        | 1.16%   |
| 32     | 1        | 0.58%   |
| 10     | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 169      | 98.26%  |
| 2      | 3        | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 126      | 73.68%  |
| 1      | 45       | 26.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 171      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 58       | 33.14%  |
| 0x08701021 | 20       | 11.43%  |
| 0x306c3    | 13       | 7.43%   |
| 0x0a201009 | 9        | 5.14%   |
| 0x08701013 | 8        | 4.57%   |
| 0x506e3    | 7        | 4%      |
| 0x306a9    | 7        | 4%      |
| 0x906ea    | 5        | 2.86%   |
| 0x0a50000c | 4        | 2.29%   |
| 0x0a201016 | 4        | 2.29%   |
| 0x0800820d | 4        | 2.29%   |
| 0x906e9    | 3        | 1.71%   |
| 0x106a5    | 3        | 1.71%   |
| 0x08108109 | 3        | 1.71%   |
| 0x08001138 | 3        | 1.71%   |
| 0xa0655    | 2        | 1.14%   |
| 0x6fd      | 2        | 1.14%   |
| 0x106e5    | 2        | 1.14%   |
| 0x08101016 | 2        | 1.14%   |
| 0x08001137 | 2        | 1.14%   |
| 0xa0671    | 1        | 0.57%   |
| 0x906ed    | 1        | 0.57%   |
| 0x906ec    | 1        | 0.57%   |
| 0x906eb    | 1        | 0.57%   |
| 0x706a8    | 1        | 0.57%   |
| 0x6fb      | 1        | 0.57%   |
| 0x6f6      | 1        | 0.57%   |
| 0x306f2    | 1        | 0.57%   |
| 0x206c2    | 1        | 0.57%   |
| 0x206a7    | 1        | 0.57%   |
| 0x20652    | 1        | 0.57%   |
| 0x0a50000b | 1        | 0.57%   |
| 0x06000852 | 1        | 0.57%   |
| 0x010000c8 | 1        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 38       | 22.22%  |
| Haswell       | 23       | 13.45%  |
| Zen 3         | 21       | 12.28%  |
| KabyLake      | 16       | 9.36%   |
| Zen           | 11       | 6.43%   |
| Zen+          | 10       | 5.85%   |
| Skylake       | 10       | 5.85%   |
| IvyBridge     | 10       | 5.85%   |
| Core          | 6        | 3.51%   |
| Nehalem       | 5        | 2.92%   |
| CometLake     | 4        | 2.34%   |
| Westmere      | 2        | 1.17%   |
| SandyBridge   | 2        | 1.17%   |
| Piledriver    | 2        | 1.17%   |
| Penryn        | 2        | 1.17%   |
| Unknown       | 2        | 1.17%   |
| Steamroller   | 1        | 0.58%   |
| K10 Llano     | 1        | 0.58%   |
| K10           | 1        | 0.58%   |
| Icelake       | 1        | 0.58%   |
| Goldmont plus | 1        | 0.58%   |
| Excavator     | 1        | 0.58%   |
| Bulldozer     | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 92       | 50%     |
| AMD    | 67       | 36.41%  |
| Intel  | 25       | 13.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 11.76%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 5.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 4.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 3.74%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 3.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 3.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 5        | 2.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 2.67%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 5        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 2.67%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5        | 2.67%   |
| AMD Cezanne                                                                 | 5        | 2.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 2.14%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.6%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 1.6%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 3        | 1.6%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1.6%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.07%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.07%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.07%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.07%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.07%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 1.07%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.07%   |
| Intel HD Graphics 630                                                       | 2        | 1.07%   |
| Intel HD Graphics 530                                                       | 2        | 1.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.07%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 2        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.53%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.53%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.53%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.53%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.53%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.53%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.53%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                          | 1        | 0.53%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.53%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.53%   |
| Nvidia GF106 [GeForce GTS 450 OEM]                                          | 1        | 0.53%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.53%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.53%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.53%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.53%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 0.53%   |
| Nvidia G70GL [Quadro FX 4500]                                               | 1        | 0.53%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.53%   |
| Intel UHD Graphics 615                                                      | 1        | 0.53%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 84       | 48.55%  |
| 1 x AMD        | 60       | 34.68%  |
| 1 x Intel      | 17       | 9.83%   |
| AMD + Nvidia   | 5        | 2.89%   |
| 2 x AMD        | 3        | 1.73%   |
| Intel + Nvidia | 2        | 1.16%   |
| 2 x Nvidia     | 1        | 0.58%   |
| Intel + AMD    | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 94       | 54.97%  |
| Proprietary | 77       | 45.03%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 27.43%  |
| 7.01-8.0   | 36       | 20.57%  |
| 3.01-4.0   | 23       | 13.14%  |
| 1.01-2.0   | 22       | 12.57%  |
| 5.01-6.0   | 14       | 8%      |
| 8.01-16.0  | 14       | 8%      |
| 0.51-1.0   | 9        | 5.14%   |
| 0.01-0.5   | 7        | 4%      |
| 2.01-3.0   | 1        | 0.57%   |
| 16.01-24.0 | 1        | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 37       | 16.44%  |
| Dell                 | 26       | 11.56%  |
| Goldstar             | 23       | 10.22%  |
| BenQ                 | 16       | 7.11%   |
| Acer                 | 16       | 7.11%   |
| AOC                  | 14       | 6.22%   |
| Ancor Communications | 14       | 6.22%   |
| Hewlett-Packard      | 8        | 3.56%   |
| Vizio                | 6        | 2.67%   |
| Iiyama               | 6        | 2.67%   |
| ASUSTek Computer     | 6        | 2.67%   |
| ViewSonic            | 5        | 2.22%   |
| Lenovo               | 5        | 2.22%   |
| Philips              | 4        | 1.78%   |
| LG Electronics       | 3        | 1.33%   |
| Gigabyte Technology  | 3        | 1.33%   |
| Fujitsu Siemens      | 3        | 1.33%   |
| Valve                | 2        | 0.89%   |
| Lenovo Group Limited | 2        | 0.89%   |
| VOXICON              | 1        | 0.44%   |
| Unknown (XXX)        | 1        | 0.44%   |
| Unknown              | 1        | 0.44%   |
| Sony                 | 1        | 0.44%   |
| Sceptre Tech         | 1        | 0.44%   |
| SAC                  | 1        | 0.44%   |
| RTK                  | 1        | 0.44%   |
| RS                   | 1        | 0.44%   |
| Planar               | 1        | 0.44%   |
| Pixio                | 1        | 0.44%   |
| Panasonic            | 1        | 0.44%   |
| Orion                | 1        | 0.44%   |
| NEC Computers        | 1        | 0.44%   |
| MSI                  | 1        | 0.44%   |
| Insignia             | 1        | 0.44%   |
| Hyundai ImageQuest   | 1        | 0.44%   |
| HVR                  | 1        | 0.44%   |
| HPN                  | 1        | 0.44%   |
| Grundig              | 1        | 0.44%   |
| GET                  | 1        | 0.44%   |
| Gateway              | 1        | 0.44%   |
| Fluid                | 1        | 0.44%   |
| Eizo                 | 1        | 0.44%   |
| CTV                  | 1        | 0.44%   |
| Belinea              | 1        | 0.44%   |
| Unknown              | 1        | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch       | 3        | 1.25%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch             | 3        | 1.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 1.25%   |
| Valve Index HMD VLV91A8                                                 | 2        | 0.83%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch     | 2        | 0.83%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 0.83%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch                | 2        | 0.83%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                    | 2        | 0.83%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2        | 0.83%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch          | 2        | 0.83%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                     | 2        | 0.83%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 2        | 0.83%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                       | 2        | 0.83%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                      | 2        | 0.83%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                      | 2        | 0.83%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch            | 2        | 0.83%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2        | 0.83%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                       | 2        | 0.83%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                       | 2        | 0.83%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch        | 2        | 0.83%   |
| VOXICON D32QO DUS3200 2560x1440 708x398mm 32.0-inch                     | 1        | 0.42%   |
| Vizio V505-G9 VIZ1033 3840x2160 1096x616mm 49.5-inch                    | 1        | 0.42%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                     | 1        | 0.42%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                       | 1        | 0.42%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                      | 1        | 0.42%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                     | 1        | 0.42%   |
| Vizio 320AR VIZ0089 1360x768 477x268mm 21.5-inch                        | 1        | 0.42%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch           | 1        | 0.42%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                  | 1        | 0.42%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch           | 1        | 0.42%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1        | 0.42%   |
| ViewSonic LCD Monitor VSCCB25 1920x1080 480x270mm 21.7-inch             | 1        | 0.42%   |
| Unknown LCD Monitor MARANTZ JAPAN, INC. marantz-AVR 3840x2160           | 1        | 0.42%   |
| Unknown (XXX) HDMI XXX0101 2560x1600 220x130mm 10.1-inch                | 1        | 0.42%   |
| Sony TV SNY8002 1920x1080 1600x900mm 72.3-inch                          | 1        | 0.42%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch          | 1        | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.42%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch       | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch    | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0522 1600x900 443x249mm 20.0-inch     | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 0.42%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1        | 0.42%   |
| Samsung Electronics SMBX2350 SAM071D 1920x1080 509x286mm 23.0-inch      | 1        | 0.42%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 520x290mm 23.4-inch      | 1        | 0.42%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch   | 1        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch   | 1        | 0.42%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch       | 1        | 0.42%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S24B240 SAM08E9 1920x1080 521x293mm 23.5-inch       | 1        | 0.42%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch       | 1        | 0.42%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch       | 1        | 0.42%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch        | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0FA5 3840x2160 1872x1053mm 84.6-inch | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch   | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0C28 1920x1080 1209x680mm 54.6-inch  | 1        | 0.42%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch  | 1        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 94       | 42.92%  |
| 2560x1440 (QHD)    | 32       | 14.61%  |
| 3840x2160 (4K)     | 27       | 12.33%  |
| 1280x1024 (SXGA)   | 11       | 5.02%   |
| 1920x1200 (WUXGA)  | 8        | 3.65%   |
| Unknown            | 7        | 3.2%    |
| 1600x900 (HD+)     | 5        | 2.28%   |
| 3440x1440          | 4        | 1.83%   |
| 2560x1080          | 4        | 1.83%   |
| 1680x1050 (WSXGA+) | 4        | 1.83%   |
| 1440x900 (WXGA+)   | 4        | 1.83%   |
| 1366x768 (WXGA)    | 3        | 1.37%   |
| 1360x768           | 3        | 1.37%   |
| 3840x1600          | 2        | 0.91%   |
| 3840x1080          | 2        | 0.91%   |
| 9840x3840          | 1        | 0.46%   |
| 4480x1440          | 1        | 0.46%   |
| 3840x1200          | 1        | 0.46%   |
| 3520x1080          | 1        | 0.46%   |
| 2880x1700          | 1        | 0.46%   |
| 2560x1600          | 1        | 0.46%   |
| 1920x540           | 1        | 0.46%   |
| 1600x1200          | 1        | 0.46%   |
| 1024x768 (XGA)     | 1        | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 48       | 21.43%  |
| 27      | 45       | 20.09%  |
| 21      | 21       | 9.38%   |
| 23      | 19       | 8.48%   |
| Unknown | 18       | 8.04%   |
| 34      | 11       | 4.91%   |
| 31      | 11       | 4.91%   |
| 19      | 9        | 4.02%   |
| 22      | 6        | 2.68%   |
| 32      | 4        | 1.79%   |
| 20      | 4        | 1.79%   |
| 18      | 4        | 1.79%   |
| 17      | 4        | 1.79%   |
| 54      | 3        | 1.34%   |
| 84      | 2        | 0.89%   |
| 49      | 2        | 0.89%   |
| 37      | 2        | 0.89%   |
| 74      | 1        | 0.45%   |
| 72      | 1        | 0.45%   |
| 69      | 1        | 0.45%   |
| 60      | 1        | 0.45%   |
| 48      | 1        | 0.45%   |
| 46      | 1        | 0.45%   |
| 42      | 1        | 0.45%   |
| 28      | 1        | 0.45%   |
| 16      | 1        | 0.45%   |
| 15      | 1        | 0.45%   |
| 10      | 1        | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 93       | 44.29%  |
| 401-500     | 38       | 18.1%   |
| 601-700     | 19       | 9.05%   |
| Unknown     | 18       | 8.57%   |
| 701-800     | 15       | 7.14%   |
| 1001-1500   | 8        | 3.81%   |
| 301-350     | 6        | 2.86%   |
| 1501-2000   | 5        | 2.38%   |
| 351-400     | 4        | 1.9%    |
| 801-900     | 2        | 0.95%   |
| 201-300     | 1        | 0.48%   |
| 901-1000    | 1        | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 131      | 67.18%  |
| 16/10   | 24       | 12.31%  |
| Unknown | 16       | 8.21%   |
| 21/9    | 10       | 5.13%   |
| 5/4     | 7        | 3.59%   |
| 32/9    | 3        | 1.54%   |
| 6/5     | 2        | 1.03%   |
| 4/3     | 2        | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 32.26%  |
| 301-350        | 45       | 20.74%  |
| 351-500        | 24       | 11.06%  |
| 251-300        | 18       | 8.29%   |
| Unknown        | 18       | 8.29%   |
| 151-200        | 14       | 6.45%   |
| More than 1000 | 10       | 4.61%   |
| 501-1000       | 8        | 3.69%   |
| 141-150        | 7        | 3.23%   |
| 41-50          | 1        | 0.46%   |
| 131-140        | 1        | 0.46%   |
| 111-120        | 1        | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 110      | 55.84%  |
| 101-120       | 45       | 22.84%  |
| Unknown       | 18       | 9.14%   |
| 1-50          | 9        | 4.57%   |
| 121-160       | 8        | 4.06%   |
| 161-240       | 6        | 3.05%   |
| More than 240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 66.47%  |
| 2     | 45       | 26.01%  |
| 3     | 11       | 6.36%   |
| 4     | 2        | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 113      | 45.56%  |
| Intel                 | 80       | 32.26%  |
| Qualcomm Atheros      | 14       | 5.65%   |
| Microsoft             | 7        | 2.82%   |
| Broadcom              | 7        | 2.82%   |
| Ralink Technology     | 3        | 1.21%   |
| Ralink                | 3        | 1.21%   |
| Aquantia              | 3        | 1.21%   |
| Xiaomi                | 2        | 0.81%   |
| TP-Link               | 2        | 0.81%   |
| Nvidia                | 2        | 0.81%   |
| ASIX Electronics      | 2        | 0.81%   |
| Wilocity              | 1        | 0.4%    |
| NetGear               | 1        | 0.4%    |
| Motorola PCS          | 1        | 0.4%    |
| MediaTek              | 1        | 0.4%    |
| Linksys               | 1        | 0.4%    |
| InterBiometrics       | 1        | 0.4%    |
| Huawei Technologies   | 1        | 0.4%    |
| Exar                  | 1        | 0.4%    |
| Edimax Technology     | 1        | 0.4%    |
| Broadcom Limited      | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 85       | 29.11%  |
| Intel I211 Gigabit Network Connection                               | 24       | 8.22%   |
| Intel Wi-Fi 6 AX200                                                 | 23       | 7.88%   |
| Realtek RTL8125 2.5GbE Controller                                   | 19       | 6.51%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 2.4%    |
| Intel Wireless-AC 9260                                              | 6        | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5        | 1.71%   |
| Intel Ethernet Controller I225-V                                    | 5        | 1.71%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 1.71%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.37%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.03%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 1.03%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.68%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.68%   |
| Microsoft XBOX ACC                                                  | 2        | 0.68%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.68%   |
| Intel Wireless 8260                                                 | 2        | 0.68%   |
| Intel Wireless 7265                                                 | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 0.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 0.68%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.34%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.34%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.34%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.34%   |
| Realtek 802.11ac NIC                                                | 1        | 0.34%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.34%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 0.34%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.34%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.34%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.34%   |
| NetGear A6210                                                       | 1        | 0.34%   |
| Motorola PCS moto g(6) play                                         | 1        | 0.34%   |
| MediaTek WiFi                                                       | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 46       | 47.92%  |
| Realtek Semiconductor | 18       | 18.75%  |
| Qualcomm Atheros      | 7        | 7.29%   |
| Microsoft             | 7        | 7.29%   |
| Broadcom              | 5        | 5.21%   |
| Ralink Technology     | 3        | 3.13%   |
| Ralink                | 3        | 3.13%   |
| TP-Link               | 2        | 2.08%   |
| Wilocity              | 1        | 1.04%   |
| NetGear               | 1        | 1.04%   |
| MediaTek              | 1        | 1.04%   |
| Linksys               | 1        | 1.04%   |
| Edimax Technology     | 1        | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 23       | 23.96%  |
| Intel Wireless-AC 9260                                              | 6        | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5        | 5.21%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 3.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 2.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 2.08%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 2.08%   |
| Microsoft XBOX ACC                                                  | 2        | 2.08%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 2.08%   |
| Intel Wireless 8260                                                 | 2        | 2.08%   |
| Intel Wireless 7265                                                 | 2        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 2.08%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 1.04%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 1.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.04%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 1.04%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 1.04%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 1.04%   |
| Realtek 802.11ac NIC                                                | 1        | 1.04%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.04%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 1.04%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 1.04%   |
| NetGear A6210                                                       | 1        | 1.04%   |
| MediaTek WiFi                                                       | 1        | 1.04%   |
| Linksys WUSB54GC v3 802.11g Adapter [Ralink RT2070L]                | 1        | 1.04%   |
| Intel Wireless 8265 / 8275                                          | 1        | 1.04%   |
| Intel Wireless 7260                                                 | 1        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 1.04%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]            | 1        | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                       | 1        | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 107      | 56.32%  |
| Intel                 | 62       | 32.63%  |
| Qualcomm Atheros      | 8        | 4.21%   |
| Aquantia              | 3        | 1.58%   |
| Xiaomi                | 2        | 1.05%   |
| Nvidia                | 2        | 1.05%   |
| Broadcom              | 2        | 1.05%   |
| ASIX Electronics      | 2        | 1.05%   |
| Motorola PCS          | 1        | 0.53%   |
| Broadcom Limited      | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 85       | 44.04%  |
| Intel I211 Gigabit Network Connection                               | 24       | 12.44%  |
| Realtek RTL8125 2.5GbE Controller                                   | 19       | 9.84%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 3.63%   |
| Intel Ethernet Controller I225-V                                    | 5        | 2.59%   |
| Intel Ethernet Connection (7) I219-V                                | 5        | 2.59%   |
| Intel Ethernet Connection I217-V                                    | 4        | 2.07%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 1.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 1.04%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2        | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.52%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.52%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.52%   |
| Motorola PCS moto g(6) play                                         | 1        | 0.52%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                               | 1        | 0.52%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.52%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.52%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 0.52%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express             | 1        | 0.52%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express               | 1        | 0.52%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 1        | 0.52%   |
| ASIX AX88772B                                                       | 1        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.52%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 170      | 65.64%  |
| WiFi     | 86       | 33.2%   |
| Modem    | 3        | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 77.96%  |
| WiFi     | 41       | 22.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 97       | 56.07%  |
| 2     | 61       | 35.26%  |
| 3     | 11       | 6.36%   |
| 4     | 3        | 1.73%   |
| 0     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 137      | 78.29%  |
| Yes  | 38       | 21.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 41       | 47.67%  |
| Realtek Semiconductor    | 13       | 15.12%  |
| Cambridge Silicon Radio  | 13       | 15.12%  |
| Broadcom                 | 7        | 8.14%   |
| ASUSTek Computer         | 7        | 8.14%   |
| IMC Networks             | 2        | 2.33%   |
| Toshiba                  | 1        | 1.16%   |
| HTC (High Tech Computer) | 1        | 1.16%   |
| Dynex                    | 1        | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 21       | 24.42%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 13       | 15.12%  |
| Realtek Bluetooth Radio                                              | 12       | 13.95%  |
| Intel Bluetooth wireless interface                                   | 6        | 6.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 5.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 5.81%   |
| Intel AX210 Bluetooth                                                | 3        | 3.49%   |
| Intel AX201 Bluetooth                                                | 3        | 3.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3        | 3.49%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 2.33%   |
| IMC Networks Bluetooth Radio                                         | 2        | 2.33%   |
| ASUS Bluetooth Device                                                | 2        | 2.33%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 1.16%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 1.16%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.16%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 1.16%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 1.16%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1.16%   |
| ASUS Bluetooth Adapter                                               | 1        | 1.16%   |
| ASUS BCM20702A0                                                      | 1        | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 103      | 28.37%  |
| Nvidia                                          | 89       | 24.52%  |
| Intel                                           | 80       | 22.04%  |
| SteelSeries ApS                                 | 11       | 3.03%   |
| C-Media Electronics                             | 11       | 3.03%   |
| Logitech                                        | 9        | 2.48%   |
| Creative Labs                                   | 6        | 1.65%   |
| Texas Instruments                               | 5        | 1.38%   |
| Kingston Technology                             | 4        | 1.1%    |
| Valve Software                                  | 3        | 0.83%   |
| Sony                                            | 3        | 0.83%   |
| JMTek                                           | 3        | 0.83%   |
| Blue Microphones                                | 3        | 0.83%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.55%   |
| Sennheiser Communications                       | 2        | 0.55%   |
| Samson Technologies                             | 2        | 0.55%   |
| RODE Microphones                                | 2        | 0.55%   |
| Razer USA                                       | 2        | 0.55%   |
| Creative Technology                             | 2        | 0.55%   |
| Corsair                                         | 2        | 0.55%   |
| Xilinx                                          | 1        | 0.28%   |
| VIA Technologies                                | 1        | 0.28%   |
| Trust                                           | 1        | 0.28%   |
| Solid State System                              | 1        | 0.28%   |
| Plantronics                                     | 1        | 0.28%   |
| No brand                                        | 1        | 0.28%   |
| Native Instruments                              | 1        | 0.28%   |
| M-Audio                                         | 1        | 0.28%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.28%   |
| iConnectivity                                   | 1        | 0.28%   |
| Hewlett-Packard                                 | 1        | 0.28%   |
| GYROCOM C&C                                     | 1        | 0.28%   |
| GN Netcom                                       | 1        | 0.28%   |
| Giga-Byte Technology                            | 1        | 0.28%   |
| Generalplus Technology                          | 1        | 0.28%   |
| FiiO Electronics Technology                     | 1        | 0.28%   |
| Cambridge Silicon Radio                         | 1        | 0.28%   |
| BEHRINGER International                         | 1        | 0.28%   |
| AKAI Professional M.I.                          | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                    | 48       | 11.46%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 22       | 5.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 16       | 3.82%   |
| Nvidia GP104 High Definition Audio Controller                               | 14       | 3.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 14       | 3.34%   |
| Nvidia GP107GL High Definition Audio Controller                             | 13       | 3.1%    |
| AMD Family 17h/19h HD Audio Controller                                      | 12       | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 10       | 2.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                     | 10       | 2.39%   |
| AMD Navi 10 HDMI Audio                                                      | 10       | 2.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 9        | 2.15%   |
| Intel 200 Series PCH HD Audio                                               | 9        | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 9        | 2.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 7        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                  | 7        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 7        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                               | 6        | 1.43%   |
| Nvidia GA104 High Definition Audio Controller                               | 6        | 1.43%   |
| Nvidia GA102 High Definition Audio Controller                               | 6        | 1.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 5        | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 5        | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 5        | 1.19%   |
| SteelSeries ApS Arctis Pro Wireless                                         | 4        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                               | 4        | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 4        | 0.95%   |
| Nvidia GK104 HDMI Audio Controller                                          | 4        | 0.95%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]               | 4        | 0.95%   |
| Valve Software Valve VR Radio & HMD Mic                                     | 3        | 0.72%   |
| Texas Instruments PCM2902 Audio Codec                                       | 3        | 0.72%   |
| SteelSeries ApS Arctis 7 wireless adapter                                   | 3        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                            | 3        | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                               | 3        | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                      | 3        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 3        | 0.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 0.72%   |
| Blue Microphones Yeti Stereo Microphone                                     | 3        | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 3        | 0.72%   |
| Thesycon Systemsoftware & Consulting E30                                    | 2        | 0.48%   |
| SteelSeries ApS SteelSeries Arctis 7                                        | 2        | 0.48%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                | 2        | 0.48%   |
| RODE Microphones RODE NT-USB                                                | 2        | 0.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 0.48%   |
| Nvidia GP102 HDMI Audio Controller                                          | 2        | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 0.48%   |
| Nvidia GF106 High Definition Audio Controller                               | 2        | 0.48%   |
| Logitech [G533 Wireless Headset Dongle]                                     | 2        | 0.48%   |
| Kingston Technology HyperX 7.1 Audio                                        | 2        | 0.48%   |
| JMTek USB PnP Audio Device                                                  | 2        | 0.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 2        | 0.48%   |
| Intel Audio device                                                          | 2        | 0.48%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 0.48%   |
| C-Media Electronics SADES Luna                                              | 2        | 0.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 2        | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                           | 2        | 0.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 2        | 0.48%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                       | 2        | 0.48%   |
| AMD FCH Azalia Controller                                                   | 2        | 0.48%   |
| Xilinx RME Digi9652 (Hammerfall)                                            | 1        | 0.24%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 32       | 21.62%  |
| G.Skill             | 31       | 20.95%  |
| Kingston            | 17       | 11.49%  |
| Crucial             | 15       | 10.14%  |
| Samsung Electronics | 11       | 7.43%   |
| Unknown             | 9        | 6.08%   |
| SK Hynix            | 7        | 4.73%   |
| Team                | 5        | 3.38%   |
| Patriot             | 5        | 3.38%   |
| Micron Technology   | 4        | 2.7%    |
| A-DATA Technology   | 3        | 2.03%   |
| Ramaxel Technology  | 2        | 1.35%   |
| Unknown (ABCD)      | 1        | 0.68%   |
| Strontium           | 1        | 0.68%   |
| PNY                 | 1        | 0.68%   |
| Neo Forza           | 1        | 0.68%   |
| Golden Empire       | 1        | 0.68%   |
| GeIL                | 1        | 0.68%   |
| Unknown             | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 7        | 4.09%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 5        | 2.92%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s        | 4        | 2.34%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 3        | 1.75%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 2        | 1.17%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2        | 1.17%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 2        | 1.17%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s            | 2        | 1.17%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s          | 2        | 1.17%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s         | 2        | 1.17%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s           | 2        | 1.17%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s          | 2        | 1.17%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 2        | 1.17%   |
| G.Skill RAM F4-3200C16-16GIS 16384MB DIMM DDR4 3600MT/s        | 2        | 1.17%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s         | 2        | 1.17%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 1.17%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 2        | 1.17%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                    | 2        | 1.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 0.58%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.58%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.58%   |
| Unknown RAM 04S2666CL19DM 4GB DIMM DDR4 2667MT/s               | 1        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s            | 1        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1        | 0.58%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1        | 0.58%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                  | 1        | 0.58%   |
| Team RAM Dark-1600 2GB DIMM DDR3 1600MT/s                      | 1        | 0.58%   |
| Strontium RAM SRT8G86U0-H9M 8GB DIMM DDR3 1333MT/s             | 1        | 0.58%   |
| SK Hynix RAM HYMP151F72CP4N3-Y5 4GB FB-DIMM DDR2 667MT/s       | 1        | 0.58%   |
| SK Hynix RAM HYMP151F72CP4D3-Y5 4GB FB-DIMM DDR2 667MT/s       | 1        | 0.58%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 1        | 0.58%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.58%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 1        | 0.58%   |
| SK Hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR2 1066MT/s           | 1        | 0.58%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 1        | 0.58%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1        | 0.58%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s         | 1        | 0.58%   |
| Samsung RAM M393B1K70CH0-YH9 8192MB DIMM 1333MT/s              | 1        | 0.58%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 0.58%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s         | 1        | 0.58%   |
| Samsung RAM M378B1G73AH0-K0 8GB DIMM DDR3 1600MT/s             | 1        | 0.58%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s            | 1        | 0.58%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s         | 1        | 0.58%   |
| Samsung RAM M378A1G44AB0-CWE 8192MB DIMM DDR4 3200MT/s         | 1        | 0.58%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s        | 1        | 0.58%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 1        | 0.58%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s            | 1        | 0.58%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                 | 1        | 0.58%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s                 | 1        | 0.58%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 1        | 0.58%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 1        | 0.58%   |
| Patriot RAM 1600 CL9 Series 8192MB DIMM DDR3 1600MT/s          | 1        | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 89       | 67.42%  |
| DDR3    | 27       | 20.45%  |
| Unknown | 5        | 3.79%   |
| SDRAM   | 4        | 3.03%   |
| LPDDR4  | 3        | 2.27%   |
| DDR2    | 3        | 2.27%   |
| DDR     | 1        | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 121      | 95.28%  |
| SODIMM  | 4        | 3.15%   |
| RIMM    | 1        | 0.79%   |
| FB-DIMM | 1        | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 46.43%  |
| 16384 | 29       | 20.71%  |
| 4096  | 27       | 19.29%  |
| 2048  | 10       | 7.14%   |
| 32768 | 8        | 5.71%   |
| 1024  | 1        | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 33       | 21.85%  |
| 3600    | 22       | 14.57%  |
| 1600    | 16       | 10.6%   |
| 1333    | 12       | 7.95%   |
| 3466    | 7        | 4.64%   |
| 2400    | 7        | 4.64%   |
| 2667    | 6        | 3.97%   |
| 2133    | 6        | 3.97%   |
| 3533    | 4        | 2.65%   |
| 3000    | 4        | 2.65%   |
| 1867    | 3        | 1.99%   |
| 1800    | 3        | 1.99%   |
| 800     | 3        | 1.99%   |
| 3733    | 2        | 1.32%   |
| 3333    | 2        | 1.32%   |
| 2733    | 2        | 1.32%   |
| 2666    | 2        | 1.32%   |
| 4333    | 1        | 0.66%   |
| 4000    | 1        | 0.66%   |
| 3866    | 1        | 0.66%   |
| 3800    | 1        | 0.66%   |
| 3500    | 1        | 0.66%   |
| 3400    | 1        | 0.66%   |
| 3151    | 1        | 0.66%   |
| 3134    | 1        | 0.66%   |
| 3067    | 1        | 0.66%   |
| 2933    | 1        | 0.66%   |
| 2800    | 1        | 0.66%   |
| 2048    | 1        | 0.66%   |
| 1280    | 1        | 0.66%   |
| 1066    | 1        | 0.66%   |
| 667     | 1        | 0.66%   |
| 400     | 1        | 0.66%   |
| Unknown | 1        | 0.66%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 25       | 48.08%  |
| Microsoft                | 5        | 9.62%   |
| Valve Software           | 3        | 5.77%   |
| Microdia                 | 3        | 5.77%   |
| Hewlett-Packard          | 2        | 3.85%   |
| Xiaomi                   | 1        | 1.92%   |
| Tobii Technology AB      | 1        | 1.92%   |
| SunplusIT                | 1        | 1.92%   |
| Sunplus IT               | 1        | 1.92%   |
| Samsung Electronics      | 1        | 1.92%   |
| Realtek Semiconductor    | 1        | 1.92%   |
| Razer USA                | 1        | 1.92%   |
| LG Electronics           | 1        | 1.92%   |
| Leap Motion              | 1        | 1.92%   |
| Huawei Technologies      | 1        | 1.92%   |
| HTC (High Tech Computer) | 1        | 1.92%   |
| GEMBIRD                  | 1        | 1.92%   |
| Creative Technology      | 1        | 1.92%   |
| Unknown                  | 1        | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 8        | 15.38%  |
| Logitech Webcam C270                                  | 7        | 13.46%  |
| Valve Software 3D Camera                              | 3        | 5.77%   |
| Microsoft LifeCam HD-3000                             | 2        | 3.85%   |
| Microdia USB 2.0 Camera                               | 2        | 3.85%   |
| Logitech Webcam C310                                  | 2        | 3.85%   |
| Logitech C922 Pro Stream Webcam                       | 2        | 3.85%   |
| HP Webcam HD 2300                                     | 2        | 3.85%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                    | 1        | 1.92%   |
| Tobii AB EyeChip                                      | 1        | 1.92%   |
| SunplusIT USB 2.0 Camera                              | 1        | 1.92%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 1        | 1.92%   |
| Samsung Galaxy A5 (MTP)                               | 1        | 1.92%   |
| Realtek Webcam                                        | 1        | 1.92%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 1.92%   |
| Microsoft LifeCam VX-5000                             | 1        | 1.92%   |
| Microsoft LifeCam VX-2000                             | 1        | 1.92%   |
| Microsoft LifeCam Cinema                              | 1        | 1.92%   |
| Microdia Webcam Vitade AF                             | 1        | 1.92%   |
| Logitech Webcam C110                                  | 1        | 1.92%   |
| Logitech StreamCam                                    | 1        | 1.92%   |
| Logitech HD Webcam C525                               | 1        | 1.92%   |
| Logitech HD Webcam B910                               | 1        | 1.92%   |
| Logitech CrystalCam                                   | 1        | 1.92%   |
| Logitech BRIO Ultra HD Webcam                         | 1        | 1.92%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.92%   |
| Leap Motion Controller                                | 1        | 1.92%   |
| Huawei UVC Camera                                     | 1        | 1.92%   |
| HTC (High Tech Computer) VIVE COSMOS                  | 1        | 1.92%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 1        | 1.92%   |
| Creative Live! Cam Socialize [VF0640]                 | 1        | 1.92%   |
| Unknown                                               | 1        | 1.92%   |

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
| 0     | 149      | 85.63%  |
| 1     | 23       | 13.22%  |
| 3     | 1        | 0.57%   |
| 2     | 1        | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Network               | 5        | 20%     |
| Net/ethernet          | 4        | 16%     |
| Graphics card         | 4        | 16%     |
| Net/wireless          | 2        | 8%      |
| Chipcard              | 2        | 8%      |
| Camera                | 2        | 8%      |
| Bluetooth             | 2        | 8%      |
| Unassigned class      | 1        | 4%      |
| Sound                 | 1        | 4%      |
| Multimedia controller | 1        | 4%      |
| Dvb card              | 1        | 4%      |

