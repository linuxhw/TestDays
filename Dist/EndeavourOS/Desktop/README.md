EndeavourOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 225

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock     | B450 Pro4                   | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek    | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte   | B450 GAMING X               | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Lenovo     | ThinkStation C20 426593U    | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [6c063a5e86](https://linux-hardware.org/?probe=6c063a5e86) | Mar 19, 2022 |
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
| ASUSTek    | TUF GAMING X570-PLUS        | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek    | TUF GAMING X570-PRO         | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| HP         | 1905                        | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| ASUSTek    | P8H77-V                     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| MSI        | B75MA-P45                   | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| ASUSTek    | ROG ZENITH EXTREME          | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| ASRock     | A320M-HD                    | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| MSI        | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP         | 8643 SMVB                   | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| ASUSTek    | TUF GAMING B560-PLUS WIF... | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock     | B550M Steel Legend          | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek    | TUF GAMING B560M-PLUS WI... | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
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
| Lenovo     | ThinkStation C20 426593U    | [fd75c6dc41](https://linux-hardware.org/?probe=fd75c6dc41) | Dec 13, 2021 |
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
| ASUSTek    | ROG STRIX X570-E GAMING     | [36b667da98](https://linux-hardware.org/?probe=36b667da98) | Oct 29, 2021 |
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
| Lenovo     | ThinkStation C20 426593U    | [bcd0cff6bb](https://linux-hardware.org/?probe=bcd0cff6bb) | Aug 29, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [292b3048d8](https://linux-hardware.org/?probe=292b3048d8) | Aug 26, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [6b88068dc4](https://linux-hardware.org/?probe=6b88068dc4) | Aug 26, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [504260a3f8](https://linux-hardware.org/?probe=504260a3f8) | Aug 25, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP         | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte   | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI        | B450M PRO-VDH MAX           | [fe3d61f4d6](https://linux-hardware.org/?probe=fe3d61f4d6) | Aug 09, 2021 |
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
| Gigabyte   | B550M AORUS PRO             | [650e9efbab](https://linux-hardware.org/?probe=650e9efbab) | Apr 13, 2021 |
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
| ASUSTek    | TUF GAMING X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
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
| Gigabyte   | B550M AORUS PRO             | [8a8d0b8b26](https://linux-hardware.org/?probe=8a8d0b8b26) | Dec 13, 2020 |
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
| Gigabyte   | B365M DS3H                  | [7994cb0fae](https://linux-hardware.org/?probe=7994cb0fae) | Jul 13, 2020 |
| ASUSTek    | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI        | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte   | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI        | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek    | TUF GAMING X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar    | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte   | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek    | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte   | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek    | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek    | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek    | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [eb3f07de2a](https://linux-hardware.org/?probe=eb3f07de2a) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [d95c487c0a](https://linux-hardware.org/?probe=d95c487c0a) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [c75091b3fd](https://linux-hardware.org/?probe=c75091b3fd) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [53dcfb848c](https://linux-hardware.org/?probe=53dcfb848c) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek    | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [612f3a46e8](https://linux-hardware.org/?probe=612f3a46e8) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [da3b984be5](https://linux-hardware.org/?probe=da3b984be5) | Nov 07, 2019 |
| ASUSTek    | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| EndeavourOS Rolling | 115      | 76.16%  |
| EndeavourOS         | 36       | 23.84%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| EndeavourOS | 150      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.15.12-arch1-1       | 10       | 5.71%   |
| 5.7.7-arch1-1         | 6        | 3.43%   |
| 5.16.2-arch1-1        | 5        | 2.86%   |
| 5.15.7-arch1-1        | 4        | 2.29%   |
| 5.11.11-arch1-1       | 4        | 2.29%   |
| 5.16.10-arch1-1       | 3        | 1.71%   |
| 5.15.8-arch1-1        | 3        | 1.71%   |
| 5.15.12-zen1-1-zen    | 3        | 1.71%   |
| 5.15.10-arch1-1       | 3        | 1.71%   |
| 5.14.9-arch2-1        | 3        | 1.71%   |
| 5.14.8-arch1-1        | 3        | 1.71%   |
| 5.10.88-2-lts         | 3        | 1.71%   |
| 5.9.14-arch1-1        | 2        | 1.14%   |
| 5.9.12-arch1-1        | 2        | 1.14%   |
| 5.9.1-arch1-1         | 2        | 1.14%   |
| 5.8.11-arch1-1        | 2        | 1.14%   |
| 5.8.10-arch1-1        | 2        | 1.14%   |
| 5.16.16-zen1-1-zen    | 2        | 1.14%   |
| 5.16.16-arch1-1       | 2        | 1.14%   |
| 5.16.14-arch1-1       | 2        | 1.14%   |
| 5.16.11-arch1-1       | 2        | 1.14%   |
| 5.16.1-arch1-1        | 2        | 1.14%   |
| 5.15.13-zen1-1-zen    | 2        | 1.14%   |
| 5.15.11-arch2-1       | 2        | 1.14%   |
| 5.14.2-arch1-2        | 2        | 1.14%   |
| 5.14.16-arch1-1       | 2        | 1.14%   |
| 5.14.14-arch1-1       | 2        | 1.14%   |
| 5.12.15-arch1-1       | 2        | 1.14%   |
| 5.11.6-arch1-1        | 2        | 1.14%   |
| 5.11.15-arch1-2       | 2        | 1.14%   |
| 5.11.13-arch1-1       | 2        | 1.14%   |
| 5.9.9-arch1-1         | 1        | 0.57%   |
| 5.9.8-zen1-1-zen      | 1        | 0.57%   |
| 5.9.6-zen1-1-zen      | 1        | 0.57%   |
| 5.9.2-arch1-1         | 1        | 0.57%   |
| 5.9.13-arch1-1        | 1        | 0.57%   |
| 5.9.10-arch1-1        | 1        | 0.57%   |
| 5.9.1-6-tkg-bmq       | 1        | 0.57%   |
| 5.9.0-rc3-1-mainline  | 1        | 0.57%   |
| 5.8.8-arch1-1         | 1        | 0.57%   |
| 5.8.5-zen1-1-zen      | 1        | 0.57%   |
| 5.8.5-arch1-1         | 1        | 0.57%   |
| 5.8.5-8-tkg-pds       | 1        | 0.57%   |
| 5.8.5-8-tkg-bmq       | 1        | 0.57%   |
| 5.8.12-arch1-1        | 1        | 0.57%   |
| 5.7.8-arch1-1         | 1        | 0.57%   |
| 5.7.6-arch1-1         | 1        | 0.57%   |
| 5.7.12-zen1-1-zen     | 1        | 0.57%   |
| 5.7.12-arch1-1        | 1        | 0.57%   |
| 5.6.6-arch1-1         | 1        | 0.57%   |
| 5.6.15-arch1-1        | 1        | 0.57%   |
| 5.6.10-arch1-1        | 1        | 0.57%   |
| 5.5.4-zen1-1-zen      | 1        | 0.57%   |
| 5.5.2-arch2-2         | 1        | 0.57%   |
| 5.4.90-1-lts          | 1        | 0.57%   |
| 5.17.0-rc4-1-mainline | 1        | 0.57%   |
| 5.16.7-arch1-1        | 1        | 0.57%   |
| 5.16.4-arch1-1        | 1        | 0.57%   |
| 5.16.4-242-tkg-pds    | 1        | 0.57%   |
| 5.16.3-arch1-1        | 1        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 14       | 8%      |
| 5.7.7   | 6        | 3.43%   |
| 5.16.2  | 5        | 2.86%   |
| 5.15.7  | 5        | 2.86%   |
| 5.8.5   | 4        | 2.29%   |
| 5.16.16 | 4        | 2.29%   |
| 5.11.11 | 4        | 2.29%   |
| 5.10.88 | 4        | 2.29%   |
| 5.9.1   | 3        | 1.71%   |
| 5.16.11 | 3        | 1.71%   |
| 5.16.10 | 3        | 1.71%   |
| 5.15.8  | 3        | 1.71%   |
| 5.15.13 | 3        | 1.71%   |
| 5.15.11 | 3        | 1.71%   |
| 5.15.10 | 3        | 1.71%   |
| 5.14.9  | 3        | 1.71%   |
| 5.14.8  | 3        | 1.71%   |
| 5.12.15 | 3        | 1.71%   |
| 5.9.14  | 2        | 1.14%   |
| 5.9.12  | 2        | 1.14%   |
| 5.8.11  | 2        | 1.14%   |
| 5.8.10  | 2        | 1.14%   |
| 5.7.12  | 2        | 1.14%   |
| 5.16.4  | 2        | 1.14%   |
| 5.16.14 | 2        | 1.14%   |
| 5.16.1  | 2        | 1.14%   |
| 5.14.2  | 2        | 1.14%   |
| 5.14.16 | 2        | 1.14%   |
| 5.14.14 | 2        | 1.14%   |
| 5.14.11 | 2        | 1.14%   |
| 5.13.13 | 2        | 1.14%   |
| 5.12.5  | 2        | 1.14%   |
| 5.12.4  | 2        | 1.14%   |
| 5.12.14 | 2        | 1.14%   |
| 5.11.6  | 2        | 1.14%   |
| 5.11.15 | 2        | 1.14%   |
| 5.11.13 | 2        | 1.14%   |
| 5.9.9   | 1        | 0.57%   |
| 5.9.8   | 1        | 0.57%   |
| 5.9.6   | 1        | 0.57%   |
| 5.9.2   | 1        | 0.57%   |
| 5.9.13  | 1        | 0.57%   |
| 5.9.10  | 1        | 0.57%   |
| 5.9.0   | 1        | 0.57%   |
| 5.8.8   | 1        | 0.57%   |
| 5.8.12  | 1        | 0.57%   |
| 5.7.8   | 1        | 0.57%   |
| 5.7.6   | 1        | 0.57%   |
| 5.6.6   | 1        | 0.57%   |
| 5.6.15  | 1        | 0.57%   |
| 5.6.10  | 1        | 0.57%   |
| 5.5.4   | 1        | 0.57%   |
| 5.5.2   | 1        | 0.57%   |
| 5.4.90  | 1        | 0.57%   |
| 5.17.0  | 1        | 0.57%   |
| 5.16.7  | 1        | 0.57%   |
| 5.16.3  | 1        | 0.57%   |
| 5.16.13 | 1        | 0.57%   |
| 5.15.6  | 1        | 0.57%   |
| 5.15.4  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 38       | 22.35%  |
| 5.16    | 24       | 14.12%  |
| 5.14    | 18       | 10.59%  |
| 5.10    | 15       | 8.82%   |
| 5.9     | 14       | 8.24%   |
| 5.11    | 14       | 8.24%   |
| 5.12    | 13       | 7.65%   |
| 5.8     | 10       | 5.88%   |
| 5.7     | 9        | 5.29%   |
| 5.13    | 7        | 4.12%   |
| 5.6     | 3        | 1.76%   |
| 5.5     | 2        | 1.18%   |
| 5.4     | 1        | 0.59%   |
| 5.17    | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 150      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 54       | 33.54%  |
| GNOME           | 30       | 18.63%  |
| XFCE            | 27       | 16.77%  |
| KDE             | 11       | 6.83%   |
| X-Cinnamon      | 9        | 5.59%   |
| i3              | 8        | 4.97%   |
| Budgie          | 5        | 3.11%   |
| Cinnamon        | 4        | 2.48%   |
| sway            | 3        | 1.86%   |
| MATE            | 2        | 1.24%   |
| LXQt            | 2        | 1.24%   |
| Unknown         | 2        | 1.24%   |
| jwm             | 1        | 0.62%   |
| herbstluftwm    | 1        | 0.62%   |
| GNOME Flashback | 1        | 0.62%   |
| awesome         | 1        | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 135      | 85.99%  |
| Wayland | 15       | 9.55%   |
| Tty     | 4        | 2.55%   |
| Unknown | 2        | 1.27%   |
| Web     | 1        | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 44       | 28.39%  |
| LightDM | 40       | 25.81%  |
| Unknown | 35       | 22.58%  |
| TDM     | 20       | 12.9%   |
| GDM     | 16       | 10.32%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 70       | 46.36%  |
| de_DE   | 15       | 9.93%   |
| en_GB   | 11       | 7.28%   |
| it_IT   | 7        | 4.64%   |
| pl_PL   | 6        | 3.97%   |
| en_CA   | 4        | 2.65%   |
| ru_RU   | 3        | 1.99%   |
| nl_NL   | 3        | 1.99%   |
| fr_FR   | 3        | 1.99%   |
| es_AR   | 3        | 1.99%   |
| pt_BR   | 2        | 1.32%   |
| es_MX   | 2        | 1.32%   |
| en_HK   | 2        | 1.32%   |
| Unknown | 2        | 1.32%   |
| tr_TR   | 1        | 0.66%   |
| sv_SE   | 1        | 0.66%   |
| sl_SI   | 1        | 0.66%   |
| nl_BE   | 1        | 0.66%   |
| hu_HU   | 1        | 0.66%   |
| fr_CA   | 1        | 0.66%   |
| es_GT   | 1        | 0.66%   |
| es_ES   | 1        | 0.66%   |
| es_CR   | 1        | 0.66%   |
| eo      | 1        | 0.66%   |
| en_ZA   | 1        | 0.66%   |
| en_SG   | 1        | 0.66%   |
| en_IN   | 1        | 0.66%   |
| en_FI   | 1        | 0.66%   |
| en_DK   | 1        | 0.66%   |
| en_AU   | 1        | 0.66%   |
| de_AT   | 1        | 0.66%   |
| cs_CZ   | 1        | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 91       | 59.48%  |
| BIOS | 62       | 40.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 105      | 70%     |
| Btrfs   | 42       | 28%     |
| Xfs     | 1        | 0.67%   |
| Overlay | 1        | 0.67%   |
| F2fs    | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 100      | 65.79%  |
| Unknown | 38       | 25%     |
| MBR     | 14       | 9.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 78.15%  |
| Yes       | 33       | 21.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 54.61%  |
| Yes       | 69       | 45.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 44       | 29.33%  |
| Gigabyte Technology | 35       | 23.33%  |
| MSI                 | 26       | 17.33%  |
| ASRock              | 15       | 10%     |
| Dell                | 7        | 4.67%   |
| Lenovo              | 6        | 4%      |
| Hewlett-Packard     | 6        | 4%      |
| Fujitsu             | 2        | 1.33%   |
| Biostar             | 2        | 1.33%   |
| UMAX                | 1        | 0.67%   |
| Samsung Electronics | 1        | 0.67%   |
| Positivo            | 1        | 0.67%   |
| LattePanda          | 1        | 0.67%   |
| Intel               | 1        | 0.67%   |
| Acer                | 1        | 0.67%   |
| Unknown             | 1        | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 6        | 4%      |
| MSI MS-7C02                            | 4        | 2.67%   |
| ASUS ROG STRIX X570-E GAMING           | 4        | 2.67%   |
| ASUS TUF GAMING X570-PLUS              | 3        | 2%      |
| ASRock B450M Pro4                      | 3        | 2%      |
| MSI MS-7C84                            | 2        | 1.33%   |
| MSI MS-7C37                            | 2        | 1.33%   |
| MSI MS-7B86                            | 2        | 1.33%   |
| MSI MS-7A38                            | 2        | 1.33%   |
| MSI MS-7850                            | 2        | 1.33%   |
| MSI MS-7798                            | 2        | 1.33%   |
| HP Z230 Tower Workstation              | 2        | 1.33%   |
| Gigabyte H110M-S2                      | 2        | 1.33%   |
| Gigabyte B550M AORUS PRO               | 2        | 1.33%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 1.33%   |
| Biostar G31-M7 TE                      | 2        | 1.33%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 2        | 1.33%   |
| ASUS K30AD_M31AD_M51AD                 | 2        | 1.33%   |
| ASRock B550M Steel Legend              | 2        | 1.33%   |
| UMAX J42 Nano                          | 1        | 0.67%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.67%   |
| Positivo POS-PIH81DI                   | 1        | 0.67%   |
| MSI MS-7C91                            | 1        | 0.67%   |
| MSI MS-7C75                            | 1        | 0.67%   |
| MSI MS-7A34                            | 1        | 0.67%   |
| MSI MS-7A32                            | 1        | 0.67%   |
| MSI MS-7A31                            | 1        | 0.67%   |
| MSI MS-7994                            | 1        | 0.67%   |
| MSI MS-7978                            | 1        | 0.67%   |
| MSI MS-7821                            | 1        | 0.67%   |
| MSI MS-7592                            | 1        | 0.67%   |
| MSI MS-7366                            | 1        | 0.67%   |
| Lenovo ThinkStation C20 426593U        | 1        | 0.67%   |
| Lenovo ThinkCentre M93p 10AAS03T00     | 1        | 0.67%   |
| Lenovo ThinkCentre M92p 32383L6        | 1        | 0.67%   |
| Lenovo ThinkCentre M710q 10MR0009US    | 1        | 0.67%   |
| Lenovo IdeaCentre 510-15ICB 90HU002QGE | 1        | 0.67%   |
| Lenovo IdeaCentre 510-15ICB 90HU002JSP | 1        | 0.67%   |
| LattePanda Alpha                       | 1        | 0.67%   |
| Intel DH55HC AAE70933-504              | 1        | 0.67%   |
| HP Z2 Tower G4 Workstation             | 1        | 0.67%   |
| HP Pavilion Gaming Desktop TG01-2xxx   | 1        | 0.67%   |
| HP Desktop M01-F0xxx                   | 1        | 0.67%   |
| HP 700-502ng                           | 1        | 0.67%   |
| Gigabyte Z97X-Gaming 5                 | 1        | 0.67%   |
| Gigabyte Z97X-Gaming 3                 | 1        | 0.67%   |
| Gigabyte Z77X-D3H                      | 1        | 0.67%   |
| Gigabyte Z390 GAMING SLI               | 1        | 0.67%   |
| Gigabyte Z170-Gaming K3                | 1        | 0.67%   |
| Gigabyte X58A-UD3R                     | 1        | 0.67%   |
| Gigabyte X570 I AORUS PRO WIFI         | 1        | 0.67%   |
| Gigabyte X570 AORUS ULTRA              | 1        | 0.67%   |
| Gigabyte X570 AORUS MASTER             | 1        | 0.67%   |
| Gigabyte X570 AORUS ELITE              | 1        | 0.67%   |
| Gigabyte X399 AORUS PRO                | 1        | 0.67%   |
| Gigabyte TRX40 AORUS MASTER            | 1        | 0.67%   |
| Gigabyte P55A-UD3                      | 1        | 0.67%   |
| Gigabyte P35-DS3R                      | 1        | 0.67%   |
| Gigabyte M68M-S2P                      | 1        | 0.67%   |
| Gigabyte H270-HD3                      | 1        | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 13       | 8.67%   |
| ASUS TUF             | 7        | 4.67%   |
| ASUS All             | 6        | 4%      |
| ASUS PRIME           | 5        | 3.33%   |
| MSI MS-7C02          | 4        | 2.67%   |
| Gigabyte X570        | 4        | 2.67%   |
| Dell OptiPlex        | 4        | 2.67%   |
| Lenovo ThinkCentre   | 3        | 2%      |
| Gigabyte B550        | 3        | 2%      |
| Gigabyte B450        | 3        | 2%      |
| ASRock B550M         | 3        | 2%      |
| ASRock B450M         | 3        | 2%      |
| ASRock B450          | 3        | 2%      |
| MSI MS-7C84          | 2        | 1.33%   |
| MSI MS-7C37          | 2        | 1.33%   |
| MSI MS-7B86          | 2        | 1.33%   |
| MSI MS-7A38          | 2        | 1.33%   |
| MSI MS-7850          | 2        | 1.33%   |
| MSI MS-7798          | 2        | 1.33%   |
| Lenovo IdeaCentre    | 2        | 1.33%   |
| HP Z230              | 2        | 1.33%   |
| Gigabyte Z97X-Gaming | 2        | 1.33%   |
| Gigabyte H110M-S2    | 2        | 1.33%   |
| Gigabyte B550M       | 2        | 1.33%   |
| Gigabyte B450M       | 2        | 1.33%   |
| Fujitsu CELSIUS      | 2        | 1.33%   |
| Biostar G31-M7       | 2        | 1.33%   |
| ASUS STRIX           | 2        | 1.33%   |
| ASUS K30AD           | 2        | 1.33%   |
| UMAX J42             | 1        | 0.67%   |
| Samsung 500T8A       | 1        | 0.67%   |
| Positivo POS-PIH81DI | 1        | 0.67%   |
| MSI MS-7C91          | 1        | 0.67%   |
| MSI MS-7C75          | 1        | 0.67%   |
| MSI MS-7A34          | 1        | 0.67%   |
| MSI MS-7A32          | 1        | 0.67%   |
| MSI MS-7A31          | 1        | 0.67%   |
| MSI MS-7994          | 1        | 0.67%   |
| MSI MS-7978          | 1        | 0.67%   |
| MSI MS-7821          | 1        | 0.67%   |
| MSI MS-7592          | 1        | 0.67%   |
| MSI MS-7366          | 1        | 0.67%   |
| Lenovo ThinkStation  | 1        | 0.67%   |
| LattePanda Alpha     | 1        | 0.67%   |
| Intel DH55HC         | 1        | 0.67%   |
| HP Z2                | 1        | 0.67%   |
| HP Pavilion          | 1        | 0.67%   |
| HP Desktop           | 1        | 0.67%   |
| HP 700-502ng         | 1        | 0.67%   |
| Gigabyte Z77X-D3H    | 1        | 0.67%   |
| Gigabyte Z390        | 1        | 0.67%   |
| Gigabyte Z170-Gaming | 1        | 0.67%   |
| Gigabyte X58A-UD3R   | 1        | 0.67%   |
| Gigabyte X399        | 1        | 0.67%   |
| Gigabyte TRX40       | 1        | 0.67%   |
| Gigabyte P55A-UD3    | 1        | 0.67%   |
| Gigabyte P35-DS3R    | 1        | 0.67%   |
| Gigabyte M68M-S2P    | 1        | 0.67%   |
| Gigabyte H270-HD3    | 1        | 0.67%   |
| Gigabyte H110N       | 1        | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 28       | 18.67%  |
| 2018 | 25       | 16.67%  |
| 2020 | 18       | 12%     |
| 2013 | 13       | 8.67%   |
| 2017 | 12       | 8%      |
| 2021 | 10       | 6.67%   |
| 2014 | 9        | 6%      |
| 2012 | 9        | 6%      |
| 2016 | 8        | 5.33%   |
| 2011 | 5        | 3.33%   |
| 2009 | 4        | 2.67%   |
| 2008 | 3        | 2%      |
| 2015 | 2        | 1.33%   |
| 2010 | 2        | 1.33%   |
| 2007 | 2        | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 150      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 149      | 99.33%  |
| Enabled  | 1        | 0.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 54       | 35.76%  |
| 32.01-64.0  | 35       | 23.18%  |
| 8.01-16.0   | 23       | 15.23%  |
| 4.01-8.0    | 11       | 7.28%   |
| 24.01-32.0  | 10       | 6.62%   |
| 3.01-4.0    | 9        | 5.96%   |
| 64.01-256.0 | 9        | 5.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 38       | 23.17%  |
| 1.01-2.0   | 38       | 23.17%  |
| 2.01-3.0   | 36       | 21.95%  |
| 3.01-4.0   | 26       | 15.85%  |
| 8.01-16.0  | 17       | 10.37%  |
| 0.51-1.0   | 5        | 3.05%   |
| 16.01-24.0 | 3        | 1.83%   |
| 24.01-32.0 | 1        | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 28.76%  |
| 4      | 28       | 18.3%   |
| 3      | 27       | 17.65%  |
| 1      | 27       | 17.65%  |
| 5      | 19       | 12.42%  |
| 7      | 3        | 1.96%   |
| 6      | 3        | 1.96%   |
| 9      | 1        | 0.65%   |
| 0      | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 75.5%   |
| Yes       | 37       | 24.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 149      | 99.33%  |
| No        | 1        | 0.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 50.33%  |
| No        | 75       | 49.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 52.63%  |
| Yes       | 72       | 47.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 36       | 24%     |
| Germany      | 23       | 15.33%  |
| Italy        | 10       | 6.67%   |
| France       | 8        | 5.33%   |
| Poland       | 7        | 4.67%   |
| Canada       | 7        | 4.67%   |
| UK           | 6        | 4%      |
| Netherlands  | 6        | 4%      |
| Belgium      | 5        | 3.33%   |
| Brazil       | 4        | 2.67%   |
| Austria      | 4        | 2.67%   |
| Mexico       | 3        | 2%      |
| Argentina    | 3        | 2%      |
| Switzerland  | 2        | 1.33%   |
| Spain        | 2        | 1.33%   |
| Slovenia     | 2        | 1.33%   |
| India        | 2        | 1.33%   |
| Hong Kong    | 2        | 1.33%   |
| Turkey       | 1        | 0.67%   |
| Sweden       | 1        | 0.67%   |
| South Korea  | 1        | 0.67%   |
| South Africa | 1        | 0.67%   |
| Singapore    | 1        | 0.67%   |
| Russia       | 1        | 0.67%   |
| Portugal     | 1        | 0.67%   |
| Jordan       | 1        | 0.67%   |
| Hungary      | 1        | 0.67%   |
| Guatemala    | 1        | 0.67%   |
| Greece       | 1        | 0.67%   |
| Finland      | 1        | 0.67%   |
| Denmark      | 1        | 0.67%   |
| Czechia      | 1        | 0.67%   |
| Costa Rica   | 1        | 0.67%   |
| Chile        | 1        | 0.67%   |
| Bulgaria     | 1        | 0.67%   |
| Australia    | 1        | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Berlin                         | 4        | 2.56%   |
| Turin                          | 3        | 1.92%   |
| Tuen Mun                       | 2        | 1.28%   |
| Toronto                        | 2        | 1.28%   |
| Seattle                        | 2        | 1.28%   |
| Ottawa                         | 2        | 1.28%   |
| Llanelli                       | 2        | 1.28%   |
| Leipzig                        | 2        | 1.28%   |
| Hamburg                        | 2        | 1.28%   |
| Geesteren                      | 2        | 1.28%   |
| Zurich                         | 1        | 0.64%   |
| Zapopan                        | 1        | 0.64%   |
| Wiesbaden                      | 1        | 0.64%   |
| Whiteville                     | 1        | 0.64%   |
| Westminster                    | 1        | 0.64%   |
| West Haddon                    | 1        | 0.64%   |
| Washington                     | 1        | 0.64%   |
| Warsaw                         | 1        | 0.64%   |
| Volketswil / Volketswil (Dorf) | 1        | 0.64%   |
| Villa Ballester                | 1        | 0.64%   |
| Vienna                         | 1        | 0.64%   |
| Union                          | 1        | 0.64%   |
| Toledo                         | 1        | 0.64%   |
| Thessaloniki                   | 1        | 0.64%   |
| Tempe                          | 1        | 0.64%   |
| Taby                           | 1        | 0.64%   |
| Sullivan                       | 1        | 0.64%   |
| Stuttgart                      | 1        | 0.64%   |
| Strombeek-Bever                | 1        | 0.64%   |
| St Petersburg                  | 1        | 0.64%   |
| Spring                         | 1        | 0.64%   |
| Spijkenisse                    | 1        | 0.64%   |
| Sofia                          | 1        | 0.64%   |
| Skorcz                         | 1        | 0.64%   |
| Singapore                      | 1        | 0.64%   |
| Sheboygan                      | 1        | 0.64%   |
| Senonches                      | 1        | 0.64%   |
| Sao Joao de Meriti             | 1        | 0.64%   |
| Santiago                       | 1        | 0.64%   |
| Santa Clarita                  | 1        | 0.64%   |
| Santa Ana                      | 1        | 0.64%   |
| Sant'Agata de' Goti            | 1        | 0.64%   |
| San NicolГЎs de los Arroyos  | 1        | 0.64%   |
| Salvador                       | 1        | 0.64%   |
| Saint-Felix-de-Valois          | 1        | 0.64%   |
| Rtyne v Podkrkonosi            | 1        | 0.64%   |
| Roden                          | 1        | 0.64%   |
| Ringgold                       | 1        | 0.64%   |
| RibeirÃ£o das Neves          | 1        | 0.64%   |
| Renton                         | 1        | 0.64%   |
| Reggiolo                       | 1        | 0.64%   |
| Rauma                          | 1        | 0.64%   |
| Ramada                         | 1        | 0.64%   |
| Praia Grande                   | 1        | 0.64%   |
| Pipe Creek                     | 1        | 0.64%   |
| Pasadena                       | 1        | 0.64%   |
| Paris                          | 1        | 0.64%   |
| Paladina                       | 1        | 0.64%   |
| Pabianice                      | 1        | 0.64%   |
| Oschatz                        | 1        | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 63       | 109    | 18.64%  |
| Samsung Electronics | 62       | 112    | 18.34%  |
| Seagate             | 58       | 88     | 17.16%  |
| Crucial             | 23       | 38     | 6.8%    |
| Kingston            | 22       | 40     | 6.51%   |
| Toshiba             | 14       | 19     | 4.14%   |
| Sandisk             | 11       | 13     | 3.25%   |
| Phison              | 8        | 9      | 2.37%   |
| Intel               | 8        | 12     | 2.37%   |
| Hitachi             | 5        | 5      | 1.48%   |
| A-DATA Technology   | 5        | 12     | 1.48%   |
| SPCC                | 4        | 4      | 1.18%   |
| Micron Technology   | 4        | 5      | 1.18%   |
| Corsair             | 4        | 4      | 1.18%   |
| Unknown             | 3        | 4      | 0.89%   |
| PNY                 | 3        | 3      | 0.89%   |
| Intenso             | 3        | 3      | 0.89%   |
| XPG                 | 2        | 2      | 0.59%   |
| OCZ                 | 2        | 2      | 0.59%   |
| JMicron             | 2        | 2      | 0.59%   |
| HGST                | 2        | 2      | 0.59%   |
| Gigabyte Technology | 2        | 3      | 0.59%   |
| China               | 2        | 2      | 0.59%   |
| USB3.1              | 1        | 1      | 0.3%    |
| UMAX                | 1        | 1      | 0.3%    |
| Transcend           | 1        | 1      | 0.3%    |
| SK Hynix            | 1        | 1      | 0.3%    |
| SABRENT             | 1        | 1      | 0.3%    |
| Realtek             | 1        | 1      | 0.3%    |
| PLEXTOR             | 1        | 1      | 0.3%    |
| Pioneer             | 1        | 3      | 0.3%    |
| PI-041              | 1        | 1      | 0.3%    |
| Phison Electronics  | 1        | 1      | 0.3%    |
| Patriot             | 1        | 2      | 0.3%    |
| Netac               | 1        | 1      | 0.3%    |
| Mushkin             | 1        | 1      | 0.3%    |
| MAXTOR              | 1        | 1      | 0.3%    |
| Maxone              | 1        | 1      | 0.3%    |
| LITEONIT            | 1        | 1      | 0.3%    |
| Leven               | 1        | 1      | 0.3%    |
| LDLC                | 1        | 1      | 0.3%    |
| KIOXIA              | 1        | 1      | 0.3%    |
| Kingmax             | 1        | 2      | 0.3%    |
| imation             | 1        | 1      | 0.3%    |
| HPE                 | 1        | 1      | 0.3%    |
| Hewlett-Packard     | 1        | 1      | 0.3%    |
| DREVO               | 1        | 1      | 0.3%    |
| ASMT                | 1        | 2      | 0.3%    |
| ASMedia             | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB          | 8        | 1.9%    |
| Crucial CT500MX500SSD1 500GB     | 8        | 1.9%    |
| Seagate ST2000DM008-2FR102 2TB   | 7        | 1.66%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 1.43%   |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 1.43%   |
| Samsung SSD 860 EVO 500GB        | 6        | 1.43%   |
| Samsung SSD 850 EVO 500GB        | 6        | 1.43%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.43%   |
| Kingston SA400S37120G 120GB SSD  | 6        | 1.43%   |
| WDC WD10EZEX-00BN5A0 1TB         | 5        | 1.19%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 0.95%   |
| Seagate Expansion Desk 4TB       | 4        | 0.95%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 0.95%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.71%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 3        | 0.71%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 3        | 0.71%   |
| WDC WD10EZEX-00RKKA0 1TB         | 3        | 0.71%   |
| Toshiba HDWD110 1TB              | 3        | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.71%   |
| Samsung SSD 970 EVO 500GB        | 3        | 0.71%   |
| Samsung SSD 970 EVO 1TB          | 3        | 0.71%   |
| Samsung SSD 960 EVO 500GB        | 3        | 0.71%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.71%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.71%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 0.71%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.48%   |
| WDC WDS100T3XHC-00SJG0 1TB       | 2        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.48%   |
| WDC WD10EZRX-00A8LB0 1TB         | 2        | 0.48%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.48%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.48%   |
| WDC WD10EACS-00D6B1 1TB          | 2        | 0.48%   |
| Unknown SD/MMC/MS PRO 32GB       | 2        | 0.48%   |
| Toshiba THNSNJ256GCSU 256GB SSD  | 2        | 0.48%   |
| Toshiba DT01ACA300 3TB           | 2        | 0.48%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.48%   |
| Toshiba A100 120GB SSD           | 2        | 0.48%   |
| SPCC Solid State Disk 240GB      | 2        | 0.48%   |
| Seagate ST95005620AS 500GB       | 2        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.48%   |
| Seagate ST1000VM002-1CT162 1TB   | 2        | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.48%   |
| Seagate Expansion 320GB          | 2        | 0.48%   |
| Sandisk NVMe SSD Drive 500GB     | 2        | 0.48%   |
| Samsung SSD SM841 2.5 7mm 128GB  | 2        | 0.48%   |
| Samsung SSD 980 PRO 500GB        | 2        | 0.48%   |
| Samsung SSD 980 500GB            | 2        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.48%   |
| Samsung SSD 840 EVO 500GB        | 2        | 0.48%   |
| Samsung SSD 750 EVO 120GB        | 2        | 0.48%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.48%   |
| Samsung HD103SJ 1TB              | 2        | 0.48%   |
| Phison Sabrent 1TB               | 2        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 57       | 87     | 41.3%   |
| WDC                 | 49       | 77     | 35.51%  |
| Toshiba             | 11       | 12     | 7.97%   |
| Hitachi             | 5        | 5      | 3.62%   |
| Samsung Electronics | 4        | 6      | 2.9%    |
| Unknown             | 2        | 2      | 1.45%   |
| HGST                | 2        | 2      | 1.45%   |
| SABRENT             | 1        | 1      | 0.72%   |
| PI-041              | 1        | 1      | 0.72%   |
| MAXTOR              | 1        | 1      | 0.72%   |
| Maxone              | 1        | 1      | 0.72%   |
| JMicron             | 1        | 1      | 0.72%   |
| HPE                 | 1        | 1      | 0.72%   |
| ASMT                | 1        | 2      | 0.72%   |
| ASMedia             | 1        | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 48       | 75     | 33.1%   |
| Crucial             | 20       | 27     | 13.79%  |
| Kingston            | 17       | 34     | 11.72%  |
| WDC                 | 10       | 14     | 6.9%    |
| SanDisk             | 8        | 9      | 5.52%   |
| Intel               | 5        | 7      | 3.45%   |
| Toshiba             | 4        | 6      | 2.76%   |
| Micron Technology   | 4        | 5      | 2.76%   |
| Intenso             | 3        | 3      | 2.07%   |
| SPCC                | 2        | 2      | 1.38%   |
| PNY                 | 2        | 2      | 1.38%   |
| OCZ                 | 2        | 2      | 1.38%   |
| Corsair             | 2        | 2      | 1.38%   |
| China               | 2        | 2      | 1.38%   |
| UMAX                | 1        | 1      | 0.69%   |
| Transcend           | 1        | 1      | 0.69%   |
| Pioneer             | 1        | 3      | 0.69%   |
| PHISON              | 1        | 1      | 0.69%   |
| Patriot             | 1        | 2      | 0.69%   |
| Mushkin             | 1        | 1      | 0.69%   |
| LITEONIT            | 1        | 1      | 0.69%   |
| Leven               | 1        | 1      | 0.69%   |
| LDLC                | 1        | 1      | 0.69%   |
| Kingmax             | 1        | 2      | 0.69%   |
| JMicron             | 1        | 1      | 0.69%   |
| imation             | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| Gigabyte Technology | 1        | 1      | 0.69%   |
| DREVO               | 1        | 1      | 0.69%   |
| A-DATA Technology   | 1        | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 105      | 210    | 37.91%  |
| HDD     | 104      | 200    | 37.55%  |
| NVMe    | 66       | 111    | 23.83%  |
| Unknown | 2        | 3      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 135      | 387    | 60.54%  |
| NVMe | 66       | 110    | 29.6%   |
| SAS  | 22       | 27     | 9.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 202    | 39.18%  |
| 0.51-1.0   | 77       | 113    | 31.43%  |
| 1.01-2.0   | 35       | 49     | 14.29%  |
| 3.01-4.0   | 19       | 25     | 7.76%   |
| 2.01-3.0   | 10       | 11     | 4.08%   |
| 4.01-10.0  | 6        | 8      | 2.45%   |
| 10.01-20.0 | 2        | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 38       | 24.68%  |
| More than 3000 | 26       | 16.88%  |
| 501-1000       | 25       | 16.23%  |
| 101-250        | 17       | 11.04%  |
| 251-500        | 16       | 10.39%  |
| 2001-3000      | 15       | 9.74%   |
| Unknown        | 11       | 7.14%   |
| 51-100         | 4        | 2.6%    |
| 21-50          | 1        | 0.65%   |
| 1-20           | 1        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 23       | 13.86%  |
| 501-1000       | 23       | 13.86%  |
| 251-500        | 22       | 13.25%  |
| 101-250        | 20       | 12.05%  |
| 1-20           | 20       | 12.05%  |
| 51-100         | 19       | 11.45%  |
| More than 3000 | 11       | 6.63%   |
| 21-50          | 11       | 6.63%   |
| Unknown        | 11       | 6.63%   |
| 2001-3000      | 6        | 3.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AZRX-00A8LB0 500GB          | 1        | 1      | 5.56%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 5.56%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 5.56%   |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 5.56%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 5.56%   |
| Seagate ST9320325AS 320GB             | 1        | 5      | 5.56%   |
| Seagate ST6000VX0023-2EF110 6TB       | 1        | 1      | 5.56%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 5.56%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 960 EVO 500GB | 1        | 1      | 5.56%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB         | 1        | 1      | 5.56%   |
| DREVO X1 SSD 120GB                    | 1        | 1      | 5.56%   |
| Crucial CT500MX500SSD1 500GB          | 1        | 1      | 5.56%   |
| Crucial CT1050MX300SSD1 1050GB        | 1        | 1      | 5.56%   |
| Corsair Force LS SSD 120GB            | 1        | 1      | 5.56%   |
| ASMT ASM1156-PM 4TB                   | 1        | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 5      | 23.53%  |
| Seagate             | 3        | 8      | 17.65%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Crucial             | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| Kingston            | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |
| DREVO               | 1        | 1      | 5.88%   |
| Corsair             | 1        | 1      | 5.88%   |
| ASMT                | 1        | 2      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 5      | 36.36%  |
| Seagate             | 3        | 8      | 27.27%  |
| Toshiba             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |
| ASMT                | 1        | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 18     | 68.75%  |
| SSD  | 4        | 5      | 25%     |
| NVMe | 1        | 1      | 6.25%   |

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
| Works    | 111      | 343    | 61.33%  |
| Detected | 54       | 156    | 29.83%  |
| Malfunc  | 15       | 24     | 8.29%   |
| Failed   | 1        | 1      | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 74       | 29.96%  |
| AMD                            | 74       | 29.96%  |
| Samsung Electronics            | 25       | 10.12%  |
| Sandisk                        | 17       | 6.88%   |
| Phison Electronics             | 13       | 5.26%   |
| ASMedia Technology             | 11       | 4.45%   |
| Marvell Technology Group       | 5        | 2.02%   |
| Kingston Technology Company    | 5        | 2.02%   |
| Realtek Semiconductor          | 4        | 1.62%   |
| Micron/Crucial Technology      | 3        | 1.21%   |
| JMicron Technology             | 3        | 1.21%   |
| ADATA Technology               | 3        | 1.21%   |
| Nvidia                         | 2        | 0.81%   |
| Toshiba America Info Systems   | 1        | 0.4%    |
| Solid State Storage Technology | 1        | 0.4%    |
| SK Hynix                       | 1        | 0.4%    |
| Silicon Motion                 | 1        | 0.4%    |
| Seagate Technology             | 1        | 0.4%    |
| Micron Technology              | 1        | 0.4%    |
| LSI Logic / Symbios Logic      | 1        | 0.4%    |
| KIOXIA                         | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 50       | 17.3%   |
| AMD 400 Series Chipset SATA Controller                                           | 26       | 9%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15       | 5.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13       | 4.5%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 11       | 3.81%   |
| AMD 500 Series Chipset SATA Controller                                           | 11       | 3.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 2.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8        | 2.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8        | 2.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7        | 2.42%   |
| Phison E12 NVMe Controller                                                       | 6        | 2.08%   |
| Intel SATA Controller [RAID mode]                                                | 6        | 2.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 5        | 1.73%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5        | 1.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5        | 1.73%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5        | 1.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5        | 1.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4        | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3        | 1.04%   |
| Realtek Realtek Non-Volatile memory controller                                   | 3        | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3        | 1.04%   |
| Kingston Company A2000 NVMe SSD                                                  | 3        | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3        | 1.04%   |
| AMD X370 Series Chipset SATA Controller                                          | 3        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 1.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 3        | 1.04%   |
| Samsung NVMe SSD Controller 980                                                  | 2        | 0.69%   |
| Kingston Company KC2000 NVMe SSD                                                 | 2        | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.69%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2        | 0.69%   |
| AMD X399 Series Chipset SATA Controller                                          | 2        | 0.69%   |
| AMD FCH SATA Controller D                                                        | 2        | 0.69%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1        | 0.35%   |
| Solid State Storage Non-Volatile memory controller                               | 1        | 0.35%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1        | 0.35%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1        | 0.35%   |
| Seagate FireCuda 520 SSD                                                         | 1        | 0.35%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.35%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.35%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1        | 0.35%   |
| Phison E7 NVMe Controller                                                        | 1        | 0.35%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1        | 0.35%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1        | 0.35%   |
| Nvidia MCP73 IDE Controller                                                      | 1        | 0.35%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 0.35%   |
| Nvidia MCP61 IDE                                                                 | 1        | 0.35%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 0.35%   |
| Micron Non-Volatile memory controller                                            | 1        | 0.35%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1        | 0.35%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 0.35%   |
| Marvell Group 88SE912x IDE Controller                                            | 1        | 0.35%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1        | 0.35%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                             | 1        | 0.35%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1        | 0.35%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                   | 1        | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 136      | 61.26%  |
| NVMe | 66       | 29.73%  |
| IDE  | 13       | 5.86%   |
| RAID | 6        | 2.7%    |
| SAS  | 1        | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 75       | 50%     |
| AMD    | 75       | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 6.67%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 5.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 3.33%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 3.33%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 3.33%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 2.67%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 2.67%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 2.67%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 2.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 2%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2%      |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 2%      |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 2%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.33%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 1.33%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2        | 1.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.33%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.33%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.33%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.67%   |
| Intel Xeon CPU W5580 @ 3.20GHz              | 1        | 0.67%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.67%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1        | 0.67%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.67%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1        | 0.67%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.67%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.67%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.67%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 1        | 0.67%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.67%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.67%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.67%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.67%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.67%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.67%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.67%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.67%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 0.67%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.67%   |
| Intel Core i5-6500TE CPU @ 2.30GHz          | 1        | 0.67%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.67%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 0.67%   |
| Intel Core i5-4460S CPU @ 2.90GHz           | 1        | 0.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.67%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.67%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.67%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 0.67%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.67%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.67%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 0.67%   |
| Intel Core i3-7100T CPU @ 3.40GHz           | 1        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 30       | 20%     |
| AMD Ryzen 5             | 30       | 20%     |
| Intel Core i7           | 20       | 13.33%  |
| AMD Ryzen 7             | 20       | 13.33%  |
| AMD Ryzen 9             | 13       | 8.67%   |
| Intel Xeon              | 7        | 4.67%   |
| Intel Core i3           | 5        | 3.33%   |
| Intel Core 2 Quad       | 3        | 2%      |
| AMD Ryzen Threadripper  | 3        | 2%      |
| AMD Ryzen 3             | 3        | 2%      |
| AMD FX                  | 3        | 2%      |
| Other                   | 2        | 1.33%   |
| Intel Celeron           | 2        | 1.33%   |
| Intel Pentium Gold      | 1        | 0.67%   |
| Intel Pentium Dual-Core | 1        | 0.67%   |
| Intel Pentium Dual      | 1        | 0.67%   |
| Intel Pentium           | 1        | 0.67%   |
| Intel Core m3           | 1        | 0.67%   |
| Intel Core 2 Duo        | 1        | 0.67%   |
| AMD Phenom II X4        | 1        | 0.67%   |
| AMD Athlon X4           | 1        | 0.67%   |
| AMD Athlon II X4        | 1        | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 60       | 39.74%  |
| 6      | 37       | 24.5%   |
| 8      | 21       | 13.91%  |
| 2      | 13       | 8.61%   |
| 12     | 12       | 7.95%   |
| 16     | 4        | 2.65%   |
| 3      | 2        | 1.32%   |
| 32     | 1        | 0.66%   |
| 10     | 1        | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 149      | 98.68%  |
| 2      | 2        | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 108      | 72%     |
| 1      | 42       | 28%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 150      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 29.41%  |
| 0x08701021 | 19       | 12.42%  |
| 0x306c3    | 12       | 7.84%   |
| 0x0a201009 | 8        | 5.23%   |
| 0x506e3    | 7        | 4.58%   |
| 0x306a9    | 7        | 4.58%   |
| 0x08701013 | 7        | 4.58%   |
| 0x906ea    | 5        | 3.27%   |
| 0x0a201016 | 4        | 2.61%   |
| 0x0800820d | 4        | 2.61%   |
| 0x906e9    | 3        | 1.96%   |
| 0x106a5    | 3        | 1.96%   |
| 0x08108109 | 3        | 1.96%   |
| 0x08001138 | 3        | 1.96%   |
| 0xa0655    | 2        | 1.31%   |
| 0x6fd      | 2        | 1.31%   |
| 0x106e5    | 2        | 1.31%   |
| 0x0a50000c | 2        | 1.31%   |
| 0x08101016 | 2        | 1.31%   |
| 0x08001137 | 2        | 1.31%   |
| 0xa0671    | 1        | 0.65%   |
| 0x906ed    | 1        | 0.65%   |
| 0x906eb    | 1        | 0.65%   |
| 0x706a8    | 1        | 0.65%   |
| 0x6fb      | 1        | 0.65%   |
| 0x306f2    | 1        | 0.65%   |
| 0x206c2    | 1        | 0.65%   |
| 0x20652    | 1        | 0.65%   |
| 0x0a50000b | 1        | 0.65%   |
| 0x06000852 | 1        | 0.65%   |
| 0x010000c8 | 1        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 33       | 22%     |
| Haswell       | 22       | 14.67%  |
| Zen 3         | 17       | 11.33%  |
| KabyLake      | 14       | 9.33%   |
| Zen           | 11       | 7.33%   |
| Skylake       | 10       | 6.67%   |
| IvyBridge     | 9        | 6%      |
| Zen+          | 8        | 5.33%   |
| Nehalem       | 5        | 3.33%   |
| Core          | 5        | 3.33%   |
| CometLake     | 3        | 2%      |
| Westmere      | 2        | 1.33%   |
| Piledriver    | 2        | 1.33%   |
| Steamroller   | 1        | 0.67%   |
| SandyBridge   | 1        | 0.67%   |
| Penryn        | 1        | 0.67%   |
| K10 Llano     | 1        | 0.67%   |
| K10           | 1        | 0.67%   |
| Icelake       | 1        | 0.67%   |
| Goldmont plus | 1        | 0.67%   |
| Bulldozer     | 1        | 0.67%   |
| Unknown       | 1        | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 82       | 50.31%  |
| AMD    | 58       | 35.58%  |
| Intel  | 23       | 14.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20       | 12.2%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 6.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 5.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 4.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 4.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 3.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.44%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.44%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 2.44%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 2.44%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.83%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1.83%   |
| AMD Cezanne                                                                 | 3        | 1.83%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.22%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.22%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.22%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.22%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.22%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 2        | 1.22%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.22%   |
| Intel HD Graphics 630                                                       | 2        | 1.22%   |
| Intel HD Graphics 530                                                       | 2        | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 2        | 1.22%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 2        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.61%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.61%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.61%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.61%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.61%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                          | 1        | 0.61%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.61%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.61%   |
| Nvidia GF106 [GeForce GTS 450 OEM]                                          | 1        | 0.61%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.61%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 0.61%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.61%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.61%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 0.61%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.61%   |
| Intel UHD Graphics 615                                                      | 1        | 0.61%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.61%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.61%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 0.61%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 74       | 49.01%  |
| 1 x AMD        | 52       | 34.44%  |
| 1 x Intel      | 15       | 9.93%   |
| AMD + Nvidia   | 5        | 3.31%   |
| Intel + Nvidia | 2        | 1.32%   |
| 2 x Nvidia     | 1        | 0.66%   |
| 2 x AMD        | 1        | 0.66%   |
| Intel + AMD    | 1        | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 54%     |
| Proprietary | 69       | 46%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 24.68%  |
| 7.01-8.0   | 34       | 22.08%  |
| 3.01-4.0   | 21       | 13.64%  |
| 1.01-2.0   | 20       | 12.99%  |
| 5.01-6.0   | 13       | 8.44%   |
| 8.01-16.0  | 12       | 7.79%   |
| 0.51-1.0   | 9        | 5.84%   |
| 0.01-0.5   | 5        | 3.25%   |
| 2.01-3.0   | 1        | 0.65%   |
| 16.01-24.0 | 1        | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 32       | 16.24%  |
| Goldstar             | 20       | 10.15%  |
| Dell                 | 19       | 9.64%   |
| BenQ                 | 15       | 7.61%   |
| Acer                 | 15       | 7.61%   |
| AOC                  | 14       | 7.11%   |
| Ancor Communications | 13       | 6.6%    |
| Iiyama               | 6        | 3.05%   |
| ASUSTek Computer     | 6        | 3.05%   |
| Vizio                | 5        | 2.54%   |
| ViewSonic            | 5        | 2.54%   |
| Lenovo               | 5        | 2.54%   |
| Hewlett-Packard      | 5        | 2.54%   |
| LG Electronics       | 3        | 1.52%   |
| Fujitsu Siemens      | 3        | 1.52%   |
| Valve                | 2        | 1.02%   |
| Philips              | 2        | 1.02%   |
| Lenovo Group Limited | 2        | 1.02%   |
| Gigabyte Technology  | 2        | 1.02%   |
| Unknown (XXX)        | 1        | 0.51%   |
| Unknown              | 1        | 0.51%   |
| Sony                 | 1        | 0.51%   |
| Sceptre Tech         | 1        | 0.51%   |
| SAC                  | 1        | 0.51%   |
| RS                   | 1        | 0.51%   |
| Planar               | 1        | 0.51%   |
| Pixio                | 1        | 0.51%   |
| Panasonic            | 1        | 0.51%   |
| Orion                | 1        | 0.51%   |
| NEC Computers        | 1        | 0.51%   |
| MSI                  | 1        | 0.51%   |
| Insignia             | 1        | 0.51%   |
| HVR                  | 1        | 0.51%   |
| HPN                  | 1        | 0.51%   |
| Grundig              | 1        | 0.51%   |
| GET                  | 1        | 0.51%   |
| Gateway              | 1        | 0.51%   |
| Fluid                | 1        | 0.51%   |
| Eizo                 | 1        | 0.51%   |
| CTV                  | 1        | 0.51%   |
| Belinea              | 1        | 0.51%   |
| Unknown              | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Valve Index HMD VLV91A8                                                | 2        | 0.96%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.96%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch      | 2        | 0.96%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.96%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch               | 2        | 0.96%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 2        | 0.96%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 0.96%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.96%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2        | 0.96%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2        | 0.96%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                      | 2        | 0.96%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.96%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch           | 2        | 0.96%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                     | 2        | 0.96%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 2        | 0.96%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                      | 2        | 0.96%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 2        | 0.96%   |
| Vizio V505-G9 VIZ1033 3840x2160 1100x620mm 49.7-inch                   | 1        | 0.48%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                    | 1        | 0.48%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                     | 1        | 0.48%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1        | 0.48%   |
| Vizio 320AR VIZ0089 1360x768 477x268mm 21.5-inch                       | 1        | 0.48%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 0.48%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.48%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch          | 1        | 0.48%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 1        | 0.48%   |
| ViewSonic LCD Monitor VSC3E32 1920x1080 600x340mm 27.2-inch            | 1        | 0.48%   |
| Unknown LCD Monitor MARANTZ JAPAN, INC. marantz-AVR 3840x2160          | 1        | 0.48%   |
| Unknown (XXX) HDMI XXX0101 2560x1600 220x130mm 10.1-inch               | 1        | 0.48%   |
| Sony TV SNY8002 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.48%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch         | 1        | 0.48%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.48%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch      | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch   | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch   | 1        | 0.48%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch     | 1        | 0.48%   |
| Samsung Electronics SMBX2350 SAM071D 1920x1080 509x286mm 23.0-inch     | 1        | 0.48%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch     | 1        | 0.48%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 0.48%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch  | 1        | 0.48%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch  | 1        | 0.48%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch      | 1        | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.48%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch      | 1        | 0.48%   |
| Samsung Electronics S24B240 SAM08E9 1920x1080 521x293mm 23.5-inch      | 1        | 0.48%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 480x270mm 21.7-inch      | 1        | 0.48%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch      | 1        | 0.48%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 1        | 0.48%   |
| Samsung Electronics LCD Monitor SAM0FA5 3840x2160 1210x680mm 54.6-inch | 1        | 0.48%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1        | 0.48%   |
| Samsung Electronics LCD Monitor SAM0C28 1920x1080 1209x680mm 54.6-inch | 1        | 0.48%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch  | 1        | 0.48%   |
| Samsung Electronics LCD Monitor LU28R55 9840x3840                      | 1        | 0.48%   |
| Samsung Electronics LCD Monitor LU28R55                                | 1        | 0.48%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 1        | 0.48%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1        | 0.48%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 598x337mm 27.0-inch      | 1        | 0.48%   |
| Samsung Electronics C27F398 SAM0D45 1920x1080 598x336mm 27.0-inch      | 1        | 0.48%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch      | 1        | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 43.01%  |
| 2560x1440 (QHD)    | 27       | 13.99%  |
| 3840x2160 (4K)     | 23       | 11.92%  |
| 1280x1024 (SXGA)   | 10       | 5.18%   |
| 1920x1200 (WUXGA)  | 8        | 4.15%   |
| Unknown            | 7        | 3.63%   |
| 2560x1080          | 4        | 2.07%   |
| 1680x1050 (WSXGA+) | 4        | 2.07%   |
| 1600x900 (HD+)     | 4        | 2.07%   |
| 3440x1440          | 3        | 1.55%   |
| 1440x900 (WXGA+)   | 3        | 1.55%   |
| 1366x768 (WXGA)    | 3        | 1.55%   |
| 1360x768           | 3        | 1.55%   |
| 3840x1080          | 2        | 1.04%   |
| 9840x3840          | 1        | 0.52%   |
| 4480x1440          | 1        | 0.52%   |
| 3840x1600          | 1        | 0.52%   |
| 3840x1200          | 1        | 0.52%   |
| 3520x1080          | 1        | 0.52%   |
| 2880x1700          | 1        | 0.52%   |
| 2560x1600          | 1        | 0.52%   |
| 1920x540           | 1        | 0.52%   |
| 1600x1200          | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 47       | 23.74%  |
| 27      | 39       | 19.7%   |
| 21      | 19       | 9.6%    |
| Unknown | 17       | 8.59%   |
| 23      | 16       | 8.08%   |
| 34      | 10       | 5.05%   |
| 19      | 8        | 4.04%   |
| 31      | 7        | 3.54%   |
| 22      | 6        | 3.03%   |
| 18      | 4        | 2.02%   |
| 54      | 3        | 1.52%   |
| 32      | 3        | 1.52%   |
| 20      | 3        | 1.52%   |
| 17      | 3        | 1.52%   |
| 49      | 2        | 1.01%   |
| 84      | 1        | 0.51%   |
| 74      | 1        | 0.51%   |
| 72      | 1        | 0.51%   |
| 69      | 1        | 0.51%   |
| 60      | 1        | 0.51%   |
| 48      | 1        | 0.51%   |
| 42      | 1        | 0.51%   |
| 37      | 1        | 0.51%   |
| 16      | 1        | 0.51%   |
| 15      | 1        | 0.51%   |
| 10      | 1        | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 84       | 45.65%  |
| 401-500     | 34       | 18.48%  |
| Unknown     | 17       | 9.24%   |
| 701-800     | 13       | 7.07%   |
| 601-700     | 13       | 7.07%   |
| 1001-1500   | 7        | 3.8%    |
| 301-350     | 5        | 2.72%   |
| 351-400     | 4        | 2.17%   |
| 1501-2000   | 4        | 2.17%   |
| 801-900     | 1        | 0.54%   |
| 201-300     | 1        | 0.54%   |
| 901-1000    | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 114      | 65.9%   |
| 16/10   | 23       | 13.29%  |
| Unknown | 15       | 8.67%   |
| 21/9    | 8        | 4.62%   |
| 5/4     | 6        | 3.47%   |
| 32/9    | 3        | 1.73%   |
| 6/5     | 2        | 1.16%   |
| 4/3     | 2        | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 33.68%  |
| 301-350        | 39       | 20.21%  |
| 351-500        | 18       | 9.33%   |
| 251-300        | 18       | 9.33%   |
| Unknown        | 17       | 8.81%   |
| 151-200        | 12       | 6.22%   |
| More than 1000 | 9        | 4.66%   |
| 141-150        | 6        | 3.11%   |
| 501-1000       | 6        | 3.11%   |
| 41-50          | 1        | 0.52%   |
| 131-140        | 1        | 0.52%   |
| 111-120        | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 98       | 56.65%  |
| 101-120       | 39       | 22.54%  |
| Unknown       | 17       | 9.83%   |
| 1-50          | 7        | 4.05%   |
| 121-160       | 7        | 4.05%   |
| 161-240       | 4        | 2.31%   |
| More than 240 | 1        | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 69.08%  |
| 2     | 35       | 23.03%  |
| 3     | 10       | 6.58%   |
| 4     | 2        | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 99       | 44.59%  |
| Intel                 | 72       | 32.43%  |
| Qualcomm Atheros      | 13       | 5.86%   |
| Microsoft             | 6        | 2.7%    |
| Broadcom              | 6        | 2.7%    |
| Ralink Technology     | 3        | 1.35%   |
| Ralink                | 3        | 1.35%   |
| Aquantia              | 3        | 1.35%   |
| Xiaomi                | 2        | 0.9%    |
| TP-Link               | 2        | 0.9%    |
| Nvidia                | 2        | 0.9%    |
| ASIX Electronics      | 2        | 0.9%    |
| Wilocity              | 1        | 0.45%   |
| NetGear               | 1        | 0.45%   |
| MediaTek              | 1        | 0.45%   |
| Linksys               | 1        | 0.45%   |
| InterBiometrics       | 1        | 0.45%   |
| Huawei Technologies   | 1        | 0.45%   |
| Exar                  | 1        | 0.45%   |
| Edimax Technology     | 1        | 0.45%   |
| Broadcom Limited      | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 72       | 27.69%  |
| Intel I211 Gigabit Network Connection                               | 22       | 8.46%   |
| Intel Wi-Fi 6 AX200                                                 | 21       | 8.08%   |
| Realtek RTL8125 2.5GbE Controller                                   | 18       | 6.92%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 2.69%   |
| Intel Wireless-AC 9260                                              | 5        | 1.92%   |
| Intel Ethernet Controller I225-V                                    | 5        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 4        | 1.54%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.54%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.15%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                | 3        | 1.15%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 2        | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.77%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 0.77%   |
| Intel Wireless 8260                                                 | 2        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 0.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2        | 0.77%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 0.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.38%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.38%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.38%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.38%   |
| Realtek 802.11ac NIC                                                | 1        | 0.38%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.38%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 0.38%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.38%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.38%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.38%   |
| NetGear A6210                                                       | 1        | 0.38%   |
| Microsoft XBOX ACC                                                  | 1        | 0.38%   |
| MediaTek WiFi                                                       | 1        | 0.38%   |
| Linksys WUSB54GC v3 802.11g Adapter [Ralink RT2070L]                | 1        | 0.38%   |
| InterBiometrics Dygma Shortcut Keyboard                             | 1        | 0.38%   |
| Intel Wireless 8265 / 8275                                          | 1        | 0.38%   |
| Intel Wireless 7265                                                 | 1        | 0.38%   |
| Intel Wireless 7260                                                 | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 40       | 46.51%  |
| Realtek Semiconductor | 16       | 18.6%   |
| Qualcomm Atheros      | 6        | 6.98%   |
| Microsoft             | 6        | 6.98%   |
| Broadcom              | 5        | 5.81%   |
| Ralink Technology     | 3        | 3.49%   |
| Ralink                | 3        | 3.49%   |
| TP-Link               | 2        | 2.33%   |
| Wilocity              | 1        | 1.16%   |
| NetGear               | 1        | 1.16%   |
| MediaTek              | 1        | 1.16%   |
| Linksys               | 1        | 1.16%   |
| Edimax Technology     | 1        | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 21       | 24.42%  |
| Intel Wireless-AC 9260                                              | 5        | 5.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 4        | 4.65%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 3.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 3.49%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 3.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 2.33%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 2        | 2.33%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 2        | 2.33%   |
| Intel Wireless 8260                                                 | 2        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 2.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 2.33%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 1.16%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 1.16%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.16%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 1.16%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 1.16%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 1.16%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 1.16%   |
| Realtek 802.11ac NIC                                                | 1        | 1.16%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 1.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.16%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 1.16%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 1.16%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.16%   |
| NetGear A6210                                                       | 1        | 1.16%   |
| Microsoft XBOX ACC                                                  | 1        | 1.16%   |
| MediaTek WiFi                                                       | 1        | 1.16%   |
| Linksys WUSB54GC v3 802.11g Adapter [Ralink RT2070L]                | 1        | 1.16%   |
| Intel Wireless 8265 / 8275                                          | 1        | 1.16%   |
| Intel Wireless 7265                                                 | 1        | 1.16%   |
| Intel Wireless 7260                                                 | 1        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 1.16%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]            | 1        | 1.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                       | 1        | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 93       | 55.36%  |
| Intel                 | 56       | 33.33%  |
| Qualcomm Atheros      | 8        | 4.76%   |
| Aquantia              | 3        | 1.79%   |
| Xiaomi                | 2        | 1.19%   |
| Nvidia                | 2        | 1.19%   |
| ASIX Electronics      | 2        | 1.19%   |
| Broadcom Limited      | 1        | 0.6%    |
| Broadcom              | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72       | 42.11%  |
| Intel I211 Gigabit Network Connection                             | 22       | 12.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 18       | 10.53%  |
| Intel Ethernet Connection (2) I219-V                              | 7        | 4.09%   |
| Intel Ethernet Controller I225-V                                  | 5        | 2.92%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.34%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 1.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.58%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.58%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.58%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.58%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.58%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.58%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1        | 0.58%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.58%   |
| ASIX AX88772B                                                     | 1        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.58%   |
| Aquantia Ethernet controller                                      | 1        | 0.58%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.58%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 149      | 65.35%  |
| WiFi     | 76       | 33.33%  |
| Modem    | 3        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 131      | 75.72%  |
| WiFi     | 42       | 24.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 55.63%  |
| 2     | 52       | 34.44%  |
| 3     | 11       | 7.28%   |
| 4     | 3        | 1.99%   |
| 0     | 1        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 119      | 77.27%  |
| Yes  | 35       | 22.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 35       | 46.67%  |
| Cambridge Silicon Radio  | 12       | 16%     |
| Realtek Semiconductor    | 11       | 14.67%  |
| Broadcom                 | 7        | 9.33%   |
| ASUSTek Computer         | 6        | 8%      |
| IMC Networks             | 2        | 2.67%   |
| Toshiba                  | 1        | 1.33%   |
| HTC (High Tech Computer) | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 19       | 25.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 16%     |
| Realtek Bluetooth Radio                             | 10       | 13.33%  |
| Intel Bluetooth wireless interface                  | 5        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5        | 6.67%   |
| Intel Bluetooth Device                              | 4        | 5.33%   |
| Intel AX201 Bluetooth                               | 3        | 4%      |
| Intel AX210 Bluetooth                               | 2        | 2.67%   |
| IMC Networks Bluetooth Radio                        | 2        | 2.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 2.67%   |
| ASUS Bluetooth Device                               | 2        | 2.67%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.33%   |
| HTC (High Tech Computer) BCM920703 Bluetooth 4.1    | 1        | 1.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1        | 1.33%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 1.33%   |
| ASUS Bluetooth Adapter                              | 1        | 1.33%   |
| ASUS BCM20702A0                                     | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 89       | 27.81%  |
| Nvidia                                          | 80       | 25%     |
| Intel                                           | 71       | 22.19%  |
| C-Media Electronics                             | 10       | 3.13%   |
| SteelSeries ApS                                 | 9        | 2.81%   |
| Logitech                                        | 9        | 2.81%   |
| Creative Labs                                   | 5        | 1.56%   |
| Texas Instruments                               | 4        | 1.25%   |
| Kingston Technology                             | 4        | 1.25%   |
| Valve Software                                  | 3        | 0.94%   |
| JMTek                                           | 3        | 0.94%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.63%   |
| Sony                                            | 2        | 0.63%   |
| Sennheiser Communications                       | 2        | 0.63%   |
| RODE Microphones                                | 2        | 0.63%   |
| Razer USA                                       | 2        | 0.63%   |
| Creative Technology                             | 2        | 0.63%   |
| Corsair                                         | 2        | 0.63%   |
| Blue Microphones                                | 2        | 0.63%   |
| Xilinx                                          | 1        | 0.31%   |
| VIA Technologies                                | 1        | 0.31%   |
| Solid State System                              | 1        | 0.31%   |
| Samson Technologies                             | 1        | 0.31%   |
| Plantronics                                     | 1        | 0.31%   |
| No brand                                        | 1        | 0.31%   |
| Native Instruments                              | 1        | 0.31%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.31%   |
| iConnectivity                                   | 1        | 0.31%   |
| Hewlett-Packard                                 | 1        | 0.31%   |
| GYROCOM C&C                                     | 1        | 0.31%   |
| GN Netcom                                       | 1        | 0.31%   |
| Giga-Byte Technology                            | 1        | 0.31%   |
| Generalplus Technology                          | 1        | 0.31%   |
| FiiO Electronics Technology                     | 1        | 0.31%   |
| BEHRINGER International                         | 1        | 0.31%   |
| AKAI Professional M.I.                          | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                    | 41       | 11.17%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 20       | 5.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 15       | 4.09%   |
| Nvidia GP107GL High Definition Audio Controller                             | 13       | 3.54%   |
| Nvidia GP104 High Definition Audio Controller                               | 13       | 3.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 13       | 3.54%   |
| AMD Navi 10 HDMI Audio                                                      | 10       | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 9        | 2.45%   |
| Intel 200 Series PCH HD Audio                                               | 9        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 9        | 2.45%   |
| AMD Family 17h/19h HD Audio Controller                                      | 9        | 2.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 7        | 1.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 7        | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 6        | 1.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                     | 6        | 1.63%   |
| Nvidia TU106 High Definition Audio Controller                               | 5        | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                               | 5        | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                  | 5        | 1.36%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 5        | 1.36%   |
| SteelSeries ApS Arctis Pro Wireless                                         | 4        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                               | 4        | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                          | 4        | 1.09%   |
| Nvidia GA102 High Definition Audio Controller                               | 4        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 4        | 1.09%   |
| Valve Software Valve VR Radio & HMD Mic                                     | 3        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 0.82%   |
| Nvidia TU104 HD Audio Controller                                            | 3        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 3        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 3        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 0.82%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]               | 3        | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 3        | 0.82%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 3        | 0.82%   |
| Thesycon Systemsoftware & Consulting D30 Pro                                | 2        | 0.54%   |
| Texas Instruments PCM2902 Audio Codec                                       | 2        | 0.54%   |
| SteelSeries ApS SteelSeries Arctis 7                                        | 2        | 0.54%   |
| SteelSeries ApS Arctis 7 wireless adapter                                   | 2        | 0.54%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                | 2        | 0.54%   |
| RODE Microphones RODE NT-USB                                                | 2        | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 0.54%   |
| Nvidia GP102 HDMI Audio Controller                                          | 2        | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                               | 2        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 0.54%   |
| Nvidia GF106 High Definition Audio Controller                               | 2        | 0.54%   |
| Logitech [G533 Wireless Headset Dongle]                                     | 2        | 0.54%   |
| Kingston Technology HyperX 7.1 Audio                                        | 2        | 0.54%   |
| JMTek USB PnP Audio Device                                                  | 2        | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                      | 2        | 0.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 2        | 0.54%   |
| Intel Audio device                                                          | 2        | 0.54%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                   | 2        | 0.54%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 2        | 0.54%   |
| Blue Microphones Yeti Stereo Microphone                                     | 2        | 0.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 2        | 0.54%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                       | 2        | 0.54%   |
| AMD FCH Azalia Controller                                                   | 2        | 0.54%   |
| Xilinx RME Digi9652 (Hammerfall)                                            | 1        | 0.27%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.27%   |
| Texas Instruments SMSL Q5 AMP                                               | 1        | 0.27%   |
| Texas Instruments PCM2707 stereo audio DAC                                  | 1        | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 29       | 21.97%  |
| G.Skill             | 27       | 20.45%  |
| Crucial             | 15       | 11.36%  |
| Kingston            | 14       | 10.61%  |
| Samsung Electronics | 10       | 7.58%   |
| Unknown             | 9        | 6.82%   |
| Team                | 5        | 3.79%   |
| SK Hynix            | 5        | 3.79%   |
| Patriot             | 4        | 3.03%   |
| Micron Technology   | 4        | 3.03%   |
| A-DATA Technology   | 3        | 2.27%   |
| Unknown (ABCD)      | 1        | 0.76%   |
| Strontium           | 1        | 0.76%   |
| Ramaxel Technology  | 1        | 0.76%   |
| PNY                 | 1        | 0.76%   |
| Golden Empire       | 1        | 0.76%   |
| GeIL                | 1        | 0.76%   |
| Unknown             | 1        | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s       | 6        | 3.97%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 5        | 3.31%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 3        | 1.99%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s      | 2        | 1.32%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s         | 2        | 1.32%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s            | 2        | 1.32%   |
| G.Skill RAM F4-3600C18-16GTZR 16384MB DIMM DDR4 3600MT/s       | 2        | 1.32%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s      | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s           | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s          | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 2        | 1.32%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s         | 2        | 1.32%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 2        | 1.32%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                    | 2        | 1.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.66%   |
| Unknown RAM 04S2666CL19DM 4GB DIMM DDR4 2667MT/s               | 1        | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3733MT/s         | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 1        | 0.66%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1        | 0.66%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                  | 1        | 0.66%   |
| Team RAM Dark-1600 2GB DIMM DDR3 1600MT/s                      | 1        | 0.66%   |
| Strontium RAM SRT8G86U0-H9M 8GB DIMM DDR3 1333MT/s             | 1        | 0.66%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.66%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 1        | 0.66%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 1        | 0.66%   |
| SK Hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR2 1066MT/s           | 1        | 0.66%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1        | 0.66%   |
| Samsung RAM M393B1K70CH0-YH9 8192MB DIMM 1333MT/s              | 1        | 0.66%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 0.66%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                 | 1        | 0.66%   |
| Samsung RAM M378B1G73AH0-K0 8GB DIMM DDR3 1600MT/s             | 1        | 0.66%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s            | 1        | 0.66%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 0.66%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s            | 1        | 0.66%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s        | 1        | 0.66%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s            | 1        | 0.66%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                 | 1        | 0.66%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s                 | 1        | 0.66%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 1        | 0.66%   |
| Patriot RAM 1600 CL9 Series 4GB DIMM DDR3 1600MT/s             | 1        | 0.66%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s         | 1        | 0.66%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1        | 0.66%   |
| Micron RAM 18ASF1G72PZ-2G1A2 8GB RIMM DDR4 2133MT/s            | 1        | 0.66%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s            | 1        | 0.66%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s            | 1        | 0.66%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 1        | 0.66%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s         | 1        | 0.66%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s       | 1        | 0.66%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s          | 1        | 0.66%   |
| Kingston RAM K66GKY-MIN 8GB DIMM DDR3 1600MT/s                 | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 78       | 66.1%   |
| DDR3    | 26       | 22.03%  |
| Unknown | 5        | 4.24%   |
| SDRAM   | 3        | 2.54%   |
| LPDDR4  | 3        | 2.54%   |
| DDR2    | 2        | 1.69%   |
| DDR     | 1        | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 109      | 95.61%  |
| SODIMM | 4        | 3.51%   |
| RIMM   | 1        | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 59       | 47.2%   |
| 4096  | 25       | 20%     |
| 16384 | 23       | 18.4%   |
| 2048  | 10       | 8%      |
| 32768 | 7        | 5.6%    |
| 1024  | 1        | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 30       | 22.06%  |
| 3600    | 18       | 13.24%  |
| 1600    | 14       | 10.29%  |
| 1333    | 12       | 8.82%   |
| 2400    | 7        | 5.15%   |
| 3466    | 6        | 4.41%   |
| 2667    | 6        | 4.41%   |
| 2133    | 6        | 4.41%   |
| 3533    | 3        | 2.21%   |
| 1867    | 3        | 2.21%   |
| 800     | 3        | 2.21%   |
| 3733    | 2        | 1.47%   |
| 3333    | 2        | 1.47%   |
| 3000    | 2        | 1.47%   |
| 2800    | 2        | 1.47%   |
| 2733    | 2        | 1.47%   |
| 2666    | 2        | 1.47%   |
| 1800    | 2        | 1.47%   |
| 4333    | 1        | 0.74%   |
| 4000    | 1        | 0.74%   |
| 3800    | 1        | 0.74%   |
| 3500    | 1        | 0.74%   |
| 3400    | 1        | 0.74%   |
| 3151    | 1        | 0.74%   |
| 3134    | 1        | 0.74%   |
| 3067    | 1        | 0.74%   |
| 2933    | 1        | 0.74%   |
| 2048    | 1        | 0.74%   |
| 1280    | 1        | 0.74%   |
| 1066    | 1        | 0.74%   |
| 400     | 1        | 0.74%   |
| Unknown | 1        | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 66.67%  |
| Prolific Technology | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 33.33%  |
| Brother Printer               | 1        | 33.33%  |
| Brother HL-2130 series        | 1        | 33.33%  |

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
| Logitech                 | 20       | 47.62%  |
| Microsoft                | 5        | 11.9%   |
| Valve Software           | 3        | 7.14%   |
| Microdia                 | 2        | 4.76%   |
| Hewlett-Packard          | 2        | 4.76%   |
| Xiaomi                   | 1        | 2.38%   |
| Tobii AB                 | 1        | 2.38%   |
| Sunplus IT               | 1        | 2.38%   |
| Realtek Semiconductor    | 1        | 2.38%   |
| Razer USA                | 1        | 2.38%   |
| Leap Motion              | 1        | 2.38%   |
| Huawei Technologies      | 1        | 2.38%   |
| HTC (High Tech Computer) | 1        | 2.38%   |
| Creative Technology      | 1        | 2.38%   |
| Unknown                  | 1        | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 6        | 14.29%  |
| Logitech HD Pro Webcam C920           | 6        | 14.29%  |
| Valve Software 3D Camera              | 3        | 7.14%   |
| Microsoft LifeCam HD-3000             | 2        | 4.76%   |
| Logitech Webcam C310                  | 2        | 4.76%   |
| HP Webcam HD 2300                     | 2        | 4.76%   |
| Xiaomi Mi/Redmi series (PTP + ADB)    | 1        | 2.38%   |
| Tobii AB EyeChip                      | 1        | 2.38%   |
| Sunplus IT Full HD webcam             | 1        | 2.38%   |
| Realtek Webcam                        | 1        | 2.38%   |
| Razer USA Gaming Webcam [Kiyo]        | 1        | 2.38%   |
| Microsoft LifeCam VX-5000             | 1        | 2.38%   |
| Microsoft LifeCam VX-2000             | 1        | 2.38%   |
| Microsoft LifeCam Cinema              | 1        | 2.38%   |
| Microdia Webcam Vitade AF             | 1        | 2.38%   |
| Microdia USB 2.0 Camera               | 1        | 2.38%   |
| Logitech StreamCam                    | 1        | 2.38%   |
| Logitech HD Webcam C525               | 1        | 2.38%   |
| Logitech HD Webcam B910               | 1        | 2.38%   |
| Logitech CrystalCam                   | 1        | 2.38%   |
| Logitech C922 Pro Stream Webcam       | 1        | 2.38%   |
| Logitech BRIO                         | 1        | 2.38%   |
| Leap Motion Controller                | 1        | 2.38%   |
| Huawei UVC Camera                     | 1        | 2.38%   |
| HTC (High Tech Computer) VIVE COSMOS  | 1        | 2.38%   |
| Creative Live! Cam Socialize [VF0640] | 1        | 2.38%   |
| Unknown                               | 1        | 2.38%   |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| HID Global | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HID Global USB Reader V3 | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 132      | 86.27%  |
| 1     | 19       | 12.42%  |
| 3     | 1        | 0.65%   |
| 2     | 1        | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Network          | 5        | 23.81%  |
| Net/ethernet     | 4        | 19.05%  |
| Graphics card    | 3        | 14.29%  |
| Net/wireless     | 2        | 9.52%   |
| Bluetooth        | 2        | 9.52%   |
| Unassigned class | 1        | 4.76%   |
| Sound            | 1        | 4.76%   |
| Dvb card         | 1        | 4.76%   |
| Chipcard         | 1        | 4.76%   |
| Camera           | 1        | 4.76%   |

