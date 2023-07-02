Gentoo 2.13 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.13.

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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X570 Taichi                 | [af8af2c7e8](https://linux-hardware.org/?probe=af8af2c7e8) | Jun 30, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [4df7190c46](https://linux-hardware.org/?probe=4df7190c46) | Jun 29, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [6388cc47ae](https://linux-hardware.org/?probe=6388cc47ae) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| ASUSTek       | M3A78-CM                    | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| ASRock        | J3160M                      | [0521c9a5a7](https://linux-hardware.org/?probe=0521c9a5a7) | Jun 22, 2023 |
| ASUSTek       | M3A78-CM                    | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [8e26542f2d](https://linux-hardware.org/?probe=8e26542f2d) | Jun 17, 2023 |
| ASUSTek       | PRIME X570-P                | [1f5163e415](https://linux-hardware.org/?probe=1f5163e415) | Jun 16, 2023 |
| MSI           | MEG X570 UNIFY              | [deeef80345](https://linux-hardware.org/?probe=deeef80345) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [153ae28a9e](https://linux-hardware.org/?probe=153ae28a9e) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [26262445d4](https://linux-hardware.org/?probe=26262445d4) | Jun 09, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [96256dca48](https://linux-hardware.org/?probe=96256dca48) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [d7ae224bea](https://linux-hardware.org/?probe=d7ae224bea) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASRock        | X670E Steel Legend          | [c1cfe9f08d](https://linux-hardware.org/?probe=c1cfe9f08d) | Jun 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Pegatron      | 2ACE                        | [fd6056dba8](https://linux-hardware.org/?probe=fd6056dba8) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | [5384efc9d9](https://linux-hardware.org/?probe=5384efc9d9) | May 28, 2023 |
| MSI           | Z590-A PRO                  | [39f6ad44fe](https://linux-hardware.org/?probe=39f6ad44fe) | May 28, 2023 |
| Lenovo        | 1036 SDK0Q40112 WIN 3305... | [f7a170dd7d](https://linux-hardware.org/?probe=f7a170dd7d) | May 28, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [95231653d0](https://linux-hardware.org/?probe=95231653d0) | May 26, 2023 |
| ASRock        | X670E Taichi                | [6c74d47711](https://linux-hardware.org/?probe=6c74d47711) | May 25, 2023 |
| MSI           | PRO X670-P WIFI             | [aa919fe5b3](https://linux-hardware.org/?probe=aa919fe5b3) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [41ca623e3c](https://linux-hardware.org/?probe=41ca623e3c) | May 24, 2023 |
| ASRock        | Z170 OC Formula             | [d7a354fa41](https://linux-hardware.org/?probe=d7a354fa41) | May 24, 2023 |
| ASUSTek       | M3A78-CM                    | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [7ad8de5a40](https://linux-hardware.org/?probe=7ad8de5a40) | May 22, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e0611754f3](https://linux-hardware.org/?probe=e0611754f3) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| Foxconn       | TPS01                       | [385129d471](https://linux-hardware.org/?probe=385129d471) | May 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [46697ea0e2](https://linux-hardware.org/?probe=46697ea0e2) | May 20, 2023 |
| Foxconn       | TPS01                       | [853284b818](https://linux-hardware.org/?probe=853284b818) | May 20, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [7c52ccb596](https://linux-hardware.org/?probe=7c52ccb596) | May 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [22ef34bb50](https://linux-hardware.org/?probe=22ef34bb50) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [8bd01d7d16](https://linux-hardware.org/?probe=8bd01d7d16) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [beacb75b2c](https://linux-hardware.org/?probe=beacb75b2c) | May 18, 2023 |
| TYAN Compu... | S2505T                      | [a17c60c707](https://linux-hardware.org/?probe=a17c60c707) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [9257bb2c1a](https://linux-hardware.org/?probe=9257bb2c1a) | May 16, 2023 |
| ASUSTek       | Z87-PLUS                    | [4160bd4f84](https://linux-hardware.org/?probe=4160bd4f84) | May 16, 2023 |
| ASUSTek       | Maximus VI HERO             | [6d60b321b1](https://linux-hardware.org/?probe=6d60b321b1) | May 16, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [a13951a75b](https://linux-hardware.org/?probe=a13951a75b) | May 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| Foxconn       | nT-330i                     | [b95166587e](https://linux-hardware.org/?probe=b95166587e) | May 14, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [334b015373](https://linux-hardware.org/?probe=334b015373) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Unknown       | Unknown                     | [e172257a22](https://linux-hardware.org/?probe=e172257a22) | May 13, 2023 |
| ASUSTek       | M3A78-CM                    | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| MSI           | MEG X570 UNIFY              | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0ae43bcc58](https://linux-hardware.org/?probe=0ae43bcc58) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [49ad1e2075](https://linux-hardware.org/?probe=49ad1e2075) | May 09, 2023 |
| ASUSTek       | M3A78-CM                    | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| MSI           | H81M-P33                    | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [aa2af0a4bc](https://linux-hardware.org/?probe=aa2af0a4bc) | May 08, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [bfd53a8d28](https://linux-hardware.org/?probe=bfd53a8d28) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [5d774e899c](https://linux-hardware.org/?probe=5d774e899c) | May 06, 2023 |
| ASUSTek       | M3A78-CM                    | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Taichi                 | [063e548538](https://linux-hardware.org/?probe=063e548538) | May 03, 2023 |
| HP            | 1589                        | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| ASRock        | X670E Pro RS                | [a17449f761](https://linux-hardware.org/?probe=a17449f761) | May 02, 2023 |
| HP            | 1589                        | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | [77ef33da62](https://linux-hardware.org/?probe=77ef33da62) | May 02, 2023 |
| ASRock        | B550M-ITX/ac                | [1c158dca0e](https://linux-hardware.org/?probe=1c158dca0e) | May 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| ASRock        | B550M Pro4                  | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [0f7e30ded3](https://linux-hardware.org/?probe=0f7e30ded3) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | B460 HD3                    | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [80ead18196](https://linux-hardware.org/?probe=80ead18196) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0f17162503](https://linux-hardware.org/?probe=0f17162503) | Apr 21, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [056db62b47](https://linux-hardware.org/?probe=056db62b47) | Apr 20, 2023 |
| Intel         | D510MO AAE76523-401         | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cb21111c89](https://linux-hardware.org/?probe=cb21111c89) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| ASRock        | B450M Steel Legend          | [6b71471847](https://linux-hardware.org/?probe=6b71471847) | Apr 15, 2023 |
| HP            | ProLiant MicroServer Gen... | [d00ebfbc62](https://linux-hardware.org/?probe=d00ebfbc62) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8b0e1ffa20](https://linux-hardware.org/?probe=8b0e1ffa20) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [3b2ac9206c](https://linux-hardware.org/?probe=3b2ac9206c) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [16ee5e0082](https://linux-hardware.org/?probe=16ee5e0082) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [1b21351033](https://linux-hardware.org/?probe=1b21351033) | Apr 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [f6f55c801f](https://linux-hardware.org/?probe=f6f55c801f) | Apr 14, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7f20e3160b](https://linux-hardware.org/?probe=7f20e3160b) | Apr 13, 2023 |
| ASUSTek       | Z87-PLUS                    | [1b44c95410](https://linux-hardware.org/?probe=1b44c95410) | Apr 13, 2023 |
| ASUSTek       | Maximus VI HERO             | [f46283dc4c](https://linux-hardware.org/?probe=f46283dc4c) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f5241c853f](https://linux-hardware.org/?probe=f5241c853f) | Apr 12, 2023 |
| ASRock        | X370 Gaming X               | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f85fdf6564](https://linux-hardware.org/?probe=f85fdf6564) | Apr 09, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e378272577](https://linux-hardware.org/?probe=e378272577) | Apr 08, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [97e76297c9](https://linux-hardware.org/?probe=97e76297c9) | Apr 08, 2023 |
| ASUSTek       | M3A78-CM                    | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d19221e116](https://linux-hardware.org/?probe=d19221e116) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| ASUSTek       | M3A78-CM                    | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [4bf7fa5f9c](https://linux-hardware.org/?probe=4bf7fa5f9c) | Mar 23, 2023 |
| ASUSTek       | M3A78-CM                    | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| MSI           | 990FXA-GD80                 | [e79acda971](https://linux-hardware.org/?probe=e79acda971) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [fab37d7522](https://linux-hardware.org/?probe=fab37d7522) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| ASRock        | H81M-HDS                    | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Foxconn       | TPS01                       | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [06d54f03f9](https://linux-hardware.org/?probe=06d54f03f9) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| ASRock        | AM1H-ITX                    | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| ASRock        | H170 Pro4                   | [7d749add31](https://linux-hardware.org/?probe=7d749add31) | Mar 07, 2023 |
| ASRock        | X570 Taichi                 | [4d48b829ca](https://linux-hardware.org/?probe=4d48b829ca) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Unknown       | Unknown                     | [ffd546b665](https://linux-hardware.org/?probe=ffd546b665) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| ASUSTek       | M3A78-CM                    | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| Gigabyte      | Z590 UD                     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| ASUSTek       | PRIME X570-P                | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.19-gentoo           | 9        | 7.89%   |
| 6.1.19-gentoo-x86_64    | 7        | 6.14%   |
| 6.1.12-gentoo           | 6        | 5.26%   |
| 6.1.28-gentoo           | 5        | 4.39%   |
| 6.1.12-gentoo-x86_64    | 5        | 4.39%   |
| 6.3.1-gentoo            | 4        | 3.51%   |
| 6.2.11-gentoo           | 4        | 3.51%   |
| 6.3.4-gentoo            | 3        | 2.63%   |
| 6.2.11-gentoo-x86_64    | 3        | 2.63%   |
| 6.1.27-gentoo-r1-x86_64 | 3        | 2.63%   |
| 6.1.22-gentoo-dist      | 3        | 2.63%   |
| 6.3.3-gentoo            | 2        | 1.75%   |
| 6.3.0-gentoo            | 2        | 1.75%   |
| 6.2.9-gentoo-x86_64     | 2        | 1.75%   |
| 6.2.8-gentoo-x86_64     | 2        | 1.75%   |
| 6.2.12-gentoo-x86_64    | 2        | 1.75%   |
| 6.1.31-gentoo-x86_64    | 2        | 1.75%   |
| 6.4.0-rc2-x86_64        | 1        | 0.88%   |
| 6.3.8-gentoo-dist       | 1        | 0.88%   |
| 6.3.8-gentoo            | 1        | 0.88%   |
| 6.3.7-gentoo_ap         | 1        | 0.88%   |
| 6.3.5-gentoo-x86_64     | 1        | 0.88%   |
| 6.3.4-gentoo-c17        | 1        | 0.88%   |
| 6.3.3-gentoo-dist       | 1        | 0.88%   |
| 6.3.2-gentoo-x86_64     | 1        | 0.88%   |
| 6.3.1-zen1              | 1        | 0.88%   |
| 6.3.1-x86_64            | 1        | 0.88%   |
| 6.3.1-gentoo_ap         | 1        | 0.88%   |
| 6.3.1-gentoo-x86_64     | 1        | 0.88%   |
| 6.3.1-gentoo-polaris    | 1        | 0.88%   |
| 6.3.0-gentoo-x86_64     | 1        | 0.88%   |
| 6.2.9-xanmod1           | 1        | 0.88%   |
| 6.2.9-gentoo-dist       | 1        | 0.88%   |
| 6.2.6-x86_64            | 1        | 0.88%   |
| 6.2.5-gentoo-dist       | 1        | 0.88%   |
| 6.2.3-gentoo-x86_64     | 1        | 0.88%   |
| 6.2.3-gentoo            | 1        | 0.88%   |
| 6.2.2-gentoo            | 1        | 0.88%   |
| 6.2.13-zen              | 1        | 0.88%   |
| 6.2.13-gentoo-dist      | 1        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.19   | 20       | 17.54%  |
| 6.1.12   | 13       | 11.4%   |
| 6.3.1    | 9        | 7.89%   |
| 6.2.11   | 7        | 6.14%   |
| 6.1.27   | 7        | 6.14%   |
| 6.1.28   | 5        | 4.39%   |
| 6.3.4    | 4        | 3.51%   |
| 6.2.9    | 4        | 3.51%   |
| 6.3.3    | 3        | 2.63%   |
| 6.3.0    | 3        | 2.63%   |
| 6.2.0    | 3        | 2.63%   |
| 6.1.31   | 3        | 2.63%   |
| 6.1.22   | 3        | 2.63%   |
| 6.3.8    | 2        | 1.75%   |
| 6.2.8    | 2        | 1.75%   |
| 6.2.3    | 2        | 1.75%   |
| 6.2.13   | 2        | 1.75%   |
| 6.2.12   | 2        | 1.75%   |
| 6.4.0    | 1        | 0.88%   |
| 6.3.7    | 1        | 0.88%   |
| 6.3.5    | 1        | 0.88%   |
| 6.3.2    | 1        | 0.88%   |
| 6.2.6    | 1        | 0.88%   |
| 6.2.5    | 1        | 0.88%   |
| 6.2.2    | 1        | 0.88%   |
| 6.2.10   | 1        | 0.88%   |
| 6.2.1    | 1        | 0.88%   |
| 6.1.9    | 1        | 0.88%   |
| 6.1.8    | 1        | 0.88%   |
| 6.1.24   | 1        | 0.88%   |
| 6.1.15   | 1        | 0.88%   |
| 6.1.11   | 1        | 0.88%   |
| 6.1.0    | 1        | 0.88%   |
| 5.17.1   | 1        | 0.88%   |
| 5.15.91  | 1        | 0.88%   |
| 5.15.59  | 1        | 0.88%   |
| 5.15.0   | 1        | 0.88%   |
| 5.10.174 | 1        | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 46       | 46.46%  |
| 6.2     | 25       | 25.25%  |
| 6.3     | 22       | 22.22%  |
| 5.15    | 3        | 3.03%   |
| 6.4     | 1        | 1.01%   |
| 5.17    | 1        | 1.01%   |
| 5.10    | 1        | 1.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 91       | 97.85%  |
| i686   | 2        | 2.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 28       | 29.47%  |
| Unknown  | 28       | 29.47%  |
| XFCE     | 13       | 13.68%  |
| GNOME    | 12       | 12.63%  |
| LXQt     | 4        | 4.21%   |
| MATE     | 2        | 2.11%   |
| KDE      | 2        | 2.11%   |
| i3       | 2        | 2.11%   |
| sway     | 1        | 1.05%   |
| openbox  | 1        | 1.05%   |
| LXDE     | 1        | 1.05%   |
| Hyprland | 1        | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 43       | 43.43%  |
| Wayland | 22       | 22.22%  |
| Tty     | 19       | 19.19%  |
| Unknown | 15       | 15.15%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 35.79%  |
| SDDM    | 30       | 31.58%  |
| LightDM | 13       | 13.68%  |
| GDM     | 11       | 11.58%  |
| SLiM    | 3        | 3.16%   |
| LXDM    | 3        | 3.16%   |
| GREETD  | 1        | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 38       | 39.18%  |
| C.UTF8     | 13       | 13.4%   |
| en_GB      | 8        | 8.25%   |
| Unknown    | 8        | 8.25%   |
| de_DE      | 6        | 6.19%   |
| en_IE      | 4        | 4.12%   |
| C          | 4        | 4.12%   |
| ru_RU      | 3        | 3.09%   |
| fr_FR      | 3        | 3.09%   |
| uk_UA      | 1        | 1.03%   |
| ru_RU.UTF8 | 1        | 1.03%   |
| pl_PL      | 1        | 1.03%   |
| it_IT      | 1        | 1.03%   |
| fi_FI      | 1        | 1.03%   |
| es_MX      | 1        | 1.03%   |
| es_ES      | 1        | 1.03%   |
| en_IL      | 1        | 1.03%   |
| da_DK      | 1        | 1.03%   |
| cs_CZ      | 1        | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 67       | 70.53%  |
| BIOS | 28       | 29.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 49       | 51.58%  |
| Btrfs    | 27       | 28.42%  |
| Zfs      | 6        | 6.32%   |
| F2fs     | 6        | 6.32%   |
| Xfs      | 3        | 3.16%   |
| XXXXXXX  | 2        | 2.11%   |
| Reiserfs | 2        | 2.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 79       | 84.95%  |
| MBR     | 11       | 11.83%  |
| Unknown | 3        | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 57.29%  |
| Yes       | 41       | 42.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 63.83%  |
| Yes       | 34       | 36.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 37.63%  |
| Gigabyte Technology | 16       | 17.2%   |
| ASRock              | 15       | 16.13%  |
| MSI                 | 9        | 9.68%   |
| Hewlett-Packard     | 4        | 4.3%    |
| Unknown             | 3        | 3.23%   |
| Lenovo              | 2        | 2.15%   |
| Foxconn             | 2        | 2.15%   |
| ZOTAC               | 1        | 1.08%   |
| TYAN Computer       | 1        | 1.08%   |
| Supermicro          | 1        | 1.08%   |
| Pegatron            | 1        | 1.08%   |
| Intel               | 1        | 1.08%   |
| HPE                 | 1        | 1.08%   |
| Fujitsu Siemens     | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP ProLiant MicroServer Gen8         | 3        | 3.23%   |
| ASRock X570 Taichi                   | 3        | 3.23%   |
| Unknown                              | 3        | 3.23%   |
| MSI MS-7B85                          | 2        | 2.15%   |
| Gigabyte X570S AORUS ELITE AX        | 2        | 2.15%   |
| ASUS TUF Gaming X570-PLUS            | 2        | 2.15%   |
| ASUS ROG STRIX Z590-F GAMING WIFI    | 2        | 2.15%   |
| ASUS ROG STRIX X570-E GAMING         | 2        | 2.15%   |
| ASUS ROG STRIX B650E-F GAMING WIFI   | 2        | 2.15%   |
| ASUS M3A78-CM                        | 2        | 2.15%   |
| ASUS All Series                      | 2        | 2.15%   |
| ZOTAC H67ITX-C-E                     | 1        | 1.08%   |
| TYAN VT82C694T                       | 1        | 1.08%   |
| Supermicro SSG-6028R-ER12-HDP-AI050  | 1        | 1.08%   |
| Pegatron 810-170st                   | 1        | 1.08%   |
| MSI MS-7D67                          | 1        | 1.08%   |
| MSI MS-7D09                          | 1        | 1.08%   |
| MSI MS-7C91                          | 1        | 1.08%   |
| MSI MS-7C35                          | 1        | 1.08%   |
| MSI MS-7B18                          | 1        | 1.08%   |
| MSI MS-7817                          | 1        | 1.08%   |
| MSI MS-7640                          | 1        | 1.08%   |
| Lenovo ThinkStation P520c 30BX001KUS | 1        | 1.08%   |
| Lenovo ThinkStation P340 30DJS35Q00  | 1        | 1.08%   |
| Intel T series                       | 1        | 1.08%   |
| HPE ProLiant MicroServer Gen10 Plus  | 1        | 1.08%   |
| HP Z420 Workstation                  | 1        | 1.08%   |
| Gigabyte Z77X-UD5H                   | 1        | 1.08%   |
| Gigabyte Z690 AORUS MASTER           | 1        | 1.08%   |
| Gigabyte Z590 UD                     | 1        | 1.08%   |
| Gigabyte Z390 GAMING X               | 1        | 1.08%   |
| Gigabyte X670E AORUS MASTER          | 1        | 1.08%   |
| Gigabyte X570 AORUS MASTER           | 1        | 1.08%   |
| Gigabyte X570 AORUS ELITE            | 1        | 1.08%   |
| Gigabyte X470 AORUS ULTRA GAMING     | 1        | 1.08%   |
| Gigabyte B550M AORUS ELITE           | 1        | 1.08%   |
| Gigabyte B460HD3                     | 1        | 1.08%   |
| Gigabyte B450M DS3H V2               | 1        | 1.08%   |
| Gigabyte B150M-D2V DDR3              | 1        | 1.08%   |
| Gigabyte AB350-Gaming                | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS ROG                            | 13       | 13.98%  |
| ASUS PRIME                          | 8        | 8.6%    |
| ASUS TUF                            | 5        | 5.38%   |
| HP ProLiant                         | 3        | 3.23%   |
| ASRock X670E                        | 3        | 3.23%   |
| ASRock X570                         | 3        | 3.23%   |
| Unknown                             | 3        | 3.23%   |
| MSI MS-7B85                         | 2        | 2.15%   |
| Lenovo ThinkStation                 | 2        | 2.15%   |
| Gigabyte X570S                      | 2        | 2.15%   |
| Gigabyte X570                       | 2        | 2.15%   |
| ASUS M3A78-CM                       | 2        | 2.15%   |
| ASUS All                            | 2        | 2.15%   |
| ZOTAC H67ITX-C-E                    | 1        | 1.08%   |
| TYAN VT82C694T                      | 1        | 1.08%   |
| Supermicro SSG-6028R-ER12-HDP-AI050 | 1        | 1.08%   |
| Pegatron 810-170st                  | 1        | 1.08%   |
| MSI MS-7D67                         | 1        | 1.08%   |
| MSI MS-7D09                         | 1        | 1.08%   |
| MSI MS-7C91                         | 1        | 1.08%   |
| MSI MS-7C35                         | 1        | 1.08%   |
| MSI MS-7B18                         | 1        | 1.08%   |
| MSI MS-7817                         | 1        | 1.08%   |
| MSI MS-7640                         | 1        | 1.08%   |
| Intel T                             | 1        | 1.08%   |
| HPE ProLiant                        | 1        | 1.08%   |
| HP Z420                             | 1        | 1.08%   |
| Gigabyte Z77X-UD5H                  | 1        | 1.08%   |
| Gigabyte Z690                       | 1        | 1.08%   |
| Gigabyte Z590                       | 1        | 1.08%   |
| Gigabyte Z390                       | 1        | 1.08%   |
| Gigabyte X670E                      | 1        | 1.08%   |
| Gigabyte X470                       | 1        | 1.08%   |
| Gigabyte B550M                      | 1        | 1.08%   |
| Gigabyte B460HD3                    | 1        | 1.08%   |
| Gigabyte B450M                      | 1        | 1.08%   |
| Gigabyte B150M-D2V                  | 1        | 1.08%   |
| Gigabyte AB350-Gaming               | 1        | 1.08%   |
| Gigabyte 970A-DS3P                  | 1        | 1.08%   |
| Fujitsu Siemens D1547               | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 15       | 16.13%  |
| 2019 | 14       | 15.05%  |
| 2020 | 11       | 11.83%  |
| 2021 | 10       | 10.75%  |
| 2018 | 7        | 7.53%   |
| 2013 | 6        | 6.45%   |
| 2012 | 5        | 5.38%   |
| 2017 | 4        | 4.3%    |
| 2010 | 4        | 4.3%    |
| 2016 | 3        | 3.23%   |
| 2014 | 3        | 3.23%   |
| 2009 | 3        | 3.23%   |
| 2023 | 2        | 2.15%   |
| 2008 | 2        | 2.15%   |
| 2015 | 1        | 1.08%   |
| 2011 | 1        | 1.08%   |
| 2003 | 1        | 1.08%   |
| 2002 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 92       | 98.92%  |
| Enabled  | 1        | 1.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 27       | 28.72%  |
| 32.01-64.0      | 25       | 26.6%   |
| 16.01-24.0      | 15       | 15.96%  |
| 24.01-32.0      | 8        | 8.51%   |
| 8.01-16.0       | 5        | 5.32%   |
| 4.01-8.0        | 4        | 4.26%   |
| 3.01-4.0        | 4        | 4.26%   |
| 1.01-2.0        | 3        | 3.19%   |
| 2.01-3.0        | 2        | 2.13%   |
| More than 256.0 | 1        | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 22       | 20.95%  |
| 4.01-8.0   | 21       | 20%     |
| 8.01-16.0  | 16       | 15.24%  |
| 3.01-4.0   | 13       | 12.38%  |
| 1.01-2.0   | 11       | 10.48%  |
| 0.51-1.0   | 8        | 7.62%   |
| 0.01-0.5   | 7        | 6.67%   |
| 16.01-24.0 | 5        | 4.76%   |
| 32.01-64.0 | 1        | 0.95%   |
| 24.01-32.0 | 1        | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 22.58%  |
| 1      | 20       | 21.51%  |
| 3      | 18       | 19.35%  |
| 5      | 14       | 15.05%  |
| 4      | 7        | 7.53%   |
| 6      | 5        | 5.38%   |
| 8      | 2        | 2.15%   |
| 7      | 2        | 2.15%   |
| 21     | 1        | 1.08%   |
| 13     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |
| 0      | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 72.04%  |
| Yes       | 26       | 27.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 92       | 98.92%  |
| No        | 1        | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 47       | 50%     |
| No        | 47       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 53.68%  |
| Yes       | 44       | 46.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 28       | 29.47%  |
| Germany     | 17       | 17.89%  |
| UK          | 8        | 8.42%   |
| France      | 8        | 8.42%   |
| Poland      | 6        | 6.32%   |
| Russia      | 5        | 5.26%   |
| Canada      | 3        | 3.16%   |
| Vietnam     | 2        | 2.11%   |
| Sweden      | 2        | 2.11%   |
| Brazil      | 2        | 2.11%   |
| Ukraine     | 1        | 1.05%   |
| Switzerland | 1        | 1.05%   |
| Spain       | 1        | 1.05%   |
| Netherlands | 1        | 1.05%   |
| Mexico      | 1        | 1.05%   |
| Luxembourg  | 1        | 1.05%   |
| Italy       | 1        | 1.05%   |
| Israel      | 1        | 1.05%   |
| Indonesia   | 1        | 1.05%   |
| Hungary     | 1        | 1.05%   |
| Finland     | 1        | 1.05%   |
| Denmark     | 1        | 1.05%   |
| Czechia     | 1        | 1.05%   |
| China       | 1        | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Paris              | 4        | 4.08%   |
| Berlin             | 4        | 4.08%   |
| Warsaw             | 3        | 3.06%   |
| Sterling           | 3        | 3.06%   |
| Frankfurt am Main  | 3        | 3.06%   |
| Cieszyn            | 3        | 3.06%   |
| Vladivostok        | 2        | 2.04%   |
| Summerville        | 2        | 2.04%   |
| Moscow             | 2        | 2.04%   |
| Leeds              | 2        | 2.04%   |
| Hanoi              | 2        | 2.04%   |
| Flint              | 2        | 2.04%   |
| Beaverton          | 2        | 2.04%   |
| Zurich             | 1        | 1.02%   |
| Yucaipa            | 1        | 1.02%   |
| Wheaton            | 1        | 1.02%   |
| Vechta             | 1        | 1.02%   |
| Vancouver          | 1        | 1.02%   |
| Surabaya           | 1        | 1.02%   |
| Stockholm          | 1        | 1.02%   |
| Stade              | 1        | 1.02%   |
| St Petersburg      | 1        | 1.02%   |
| Šlapanice         | 1        | 1.02%   |
| Shanghai           | 1        | 1.02%   |
| Seattle            | 1        | 1.02%   |
| San Francisco      | 1        | 1.02%   |
| Round Rock         | 1        | 1.02%   |
| Rotterdam          | 1        | 1.02%   |
| Pozzuoli           | 1        | 1.02%   |
| Portland           | 1        | 1.02%   |
| Oulu               | 1        | 1.02%   |
| Orange             | 1        | 1.02%   |
| Norwich            | 1        | 1.02%   |
| Montpon-Menesterol | 1        | 1.02%   |
| Marysville         | 1        | 1.02%   |
| Malmo              | 1        | 1.02%   |
| Mainhausen         | 1        | 1.02%   |
| Luxembourg         | 1        | 1.02%   |
| Lich               | 1        | 1.02%   |
| Kippens            | 1        | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 41       | 87     | 19.9%   |
| WDC                         | 31       | 62     | 15.05%  |
| Seagate                     | 28       | 71     | 13.59%  |
| SanDisk                     | 15       | 17     | 7.28%   |
| Crucial                     | 12       | 24     | 5.83%   |
| Toshiba                     | 10       | 15     | 4.85%   |
| Phison Electronics          | 9        | 12     | 4.37%   |
| Kingston                    | 9        | 11     | 4.37%   |
| China                       | 6        | 15     | 2.91%   |
| Intel                       | 5        | 7      | 2.43%   |
| Hitachi                     | 5        | 17     | 2.43%   |
| Micron/Crucial Technology   | 4        | 5      | 1.94%   |
| GOODRAM                     | 3        | 12     | 1.46%   |
| SK hynix                    | 2        | 2      | 0.97%   |
| PNY                         | 2        | 4      | 0.97%   |
| Phison                      | 2        | 3      | 0.97%   |
| OCZ                         | 2        | 2      | 0.97%   |
| Micron Technology           | 2        | 3      | 0.97%   |
| Kingston Technology Company | 2        | 2      | 0.97%   |
| ADROITLARK                  | 2        | 3      | 0.97%   |
| A-DATA Technology           | 2        | 2      | 0.97%   |
| V-GeN                       | 1        | 1      | 0.49%   |
| Transcend                   | 1        | 1      | 0.49%   |
| T-FORCE                     | 1        | 1      | 0.49%   |
| Silicon Motion              | 1        | 2      | 0.49%   |
| SABRENT                     | 1        | 1      | 0.49%   |
| Realtek Semiconductor       | 1        | 1      | 0.49%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.49%   |
| LITEONIT                    | 1        | 1      | 0.49%   |
| KingSpec                    | 1        | 1      | 0.49%   |
| HGST                        | 1        | 1      | 0.49%   |
| ADATA Technology            | 1        | 2      | 0.49%   |
| Unknown                     | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 12       | 4.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 11       | 4.23%   |
| Seagate ST4000DM004-2CV104 4TB                      | 6        | 2.31%   |
| Samsung SSD 980 1TB                                 | 5        | 1.92%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 1.54%   |
| Crucial CT1000MX500SSD1 1TB                         | 4        | 1.54%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 3        | 1.15%   |
| Samsung SSD 870 EVO 1TB                             | 3        | 1.15%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3        | 1.15%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 3        | 1.15%   |
| Intel SSD 660P Series 512GB                         | 3        | 1.15%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 2        | 0.77%   |
| WDC WD5000LPLX-66ZNTT1 500GB                        | 2        | 0.77%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2        | 0.77%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2        | 0.77%   |
| WDC WD20EARX-00PASB0 2TB                            | 2        | 0.77%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 2        | 0.77%   |
| WDC WD1502FYPS-02W3B0 1TB                           | 2        | 0.77%   |
| WDC WD120EFBX-68B0EN0 12TB                          | 2        | 0.77%   |
| Toshiba DT01ACA200 2TB                              | 2        | 0.77%   |
| Seagate ST6000DM003-2CY186 6TB                      | 2        | 0.77%   |
| Sandisk WD_BLACK SN770 1TB                          | 2        | 0.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2        | 0.77%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 0.77%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.77%   |
| Samsung SSD 860 EVO 4TB                             | 2        | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 2        | 0.77%   |
| Phison E7 NVMe Controller 120GB                     | 2        | 0.77%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2        | 0.77%   |
| Phison E12 NVMe Controller 1TB                      | 2        | 0.77%   |
| Phison Corsair MP600 PRO XT 2TB                     | 2        | 0.77%   |
| Kingston SA400S37480G 480GB SSD                     | 2        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                     | 2        | 0.77%   |
| GOODRAM SSDPR-CL100-480-G2 480GB                    | 2        | 0.77%   |
| China SSD 240GB                                     | 2        | 0.77%   |
| China SATA SSD 960GB                                | 2        | 0.77%   |
| ADROITLARK SSD 120GB                                | 2        | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.38%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 60     | 39.19%  |
| Seagate             | 28       | 69     | 37.84%  |
| Toshiba             | 10       | 15     | 13.51%  |
| Hitachi             | 5        | 17     | 6.76%   |
| Samsung Electronics | 1        | 1      | 1.35%   |
| HGST                | 1        | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 39     | 29.11%  |
| Crucial             | 12       | 24     | 15.19%  |
| Kingston            | 8        | 9      | 10.13%  |
| SanDisk             | 7        | 8      | 8.86%   |
| China               | 6        | 15     | 7.59%   |
| GOODRAM             | 3        | 12     | 3.8%    |
| WDC                 | 2        | 2      | 2.53%   |
| PNY                 | 2        | 4      | 2.53%   |
| OCZ                 | 2        | 2      | 2.53%   |
| Micron Technology   | 2        | 3      | 2.53%   |
| Intel               | 2        | 3      | 2.53%   |
| ADROITLARK          | 2        | 3      | 2.53%   |
| A-DATA Technology   | 2        | 2      | 2.53%   |
| V-GeN               | 1        | 1      | 1.27%   |
| Transcend           | 1        | 1      | 1.27%   |
| T-FORCE             | 1        | 1      | 1.27%   |
| LITEONIT            | 1        | 1      | 1.27%   |
| KingSpec            | 1        | 1      | 1.27%   |
| Unknown             | 1        | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 55       | 132    | 35.03%  |
| HDD     | 52       | 163    | 33.12%  |
| NVMe    | 48       | 92     | 30.57%  |
| Unknown | 2        | 3      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 288    | 59.23%  |
| NVMe | 48       | 91     | 36.92%  |
| SAS  | 5        | 11     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 84     | 34.23%  |
| 0.51-1.0   | 37       | 82     | 24.83%  |
| 1.01-2.0   | 23       | 37     | 15.44%  |
| 3.01-4.0   | 16       | 35     | 10.74%  |
| 4.01-10.0  | 14       | 30     | 9.4%    |
| 2.01-3.0   | 5        | 21     | 3.36%   |
| 10.01-20.0 | 3        | 6      | 2.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 27       | 27.84%  |
| 501-1000       | 16       | 16.49%  |
| 1001-2000      | 14       | 14.43%  |
| 251-500        | 11       | 11.34%  |
| 2001-3000      | 9        | 9.28%   |
| 101-250        | 6        | 6.19%   |
| 1-20           | 6        | 6.19%   |
| Unknown        | 5        | 5.15%   |
| 51-100         | 3        | 3.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 17.17%  |
| 501-1000       | 17       | 17.17%  |
| More than 3000 | 16       | 16.16%  |
| 1001-2000      | 11       | 11.11%  |
| 21-50          | 10       | 10.1%   |
| 101-250        | 10       | 10.1%   |
| 251-500        | 8        | 8.08%   |
| Unknown        | 5        | 5.05%   |
| 51-100         | 3        | 3.03%   |
| 2001-3000      | 2        | 2.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba DT01ACA200 2TB              | 2        | 2      | 8.7%    |
| WDC WD60PURZ-85ZUFY1 6TB            | 1        | 1      | 4.35%   |
| WDC WD60EZRX-00MVLB1 6TB            | 1        | 1      | 4.35%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1        | 2      | 4.35%   |
| Toshiba MK1633GSG 160GB             | 1        | 1      | 4.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1      | 4.35%   |
| Seagate ST380011A 80GB              | 1        | 1      | 4.35%   |
| Seagate ST3500630NS 500GB           | 1        | 2      | 4.35%   |
| Seagate ST3000DM001-9YN166 3TB      | 1        | 1      | 4.35%   |
| Seagate ST2000DX002-2DV164 2TB      | 1        | 1      | 4.35%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1      | 4.35%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 4.35%   |
| SanDisk SSD PLUS 480GB              | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 980 1TB     | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 8      | 4.35%   |
| PNY SSD2SC120G1LC763C121S459P 120GB | 1        | 1      | 4.35%   |
| Intel SSDSC2BB160G4T 160GB          | 1        | 2      | 4.35%   |
| Hitachi HTS721080G9SA00 80GB        | 1        | 1      | 4.35%   |
| Crucial M4-CT512M4SSD2 512GB        | 1        | 1      | 4.35%   |
| China SSD 240GB                     | 1        | 1      | 4.35%   |
| China SATA SSD 960GB                | 1        | 2      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 31.82%  |
| WDC                 | 3        | 4      | 13.64%  |
| Toshiba             | 3        | 3      | 13.64%  |
| Samsung Electronics | 2        | 9      | 9.09%   |
| China               | 2        | 3      | 9.09%   |
| SanDisk             | 1        | 1      | 4.55%   |
| PNY                 | 1        | 1      | 4.55%   |
| Intel               | 1        | 2      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 7        | 9      | 50%     |
| WDC     | 3        | 4      | 21.43%  |
| Toshiba | 3        | 3      | 21.43%  |
| Hitachi | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 17     | 61.9%   |
| SSD  | 7        | 16     | 33.33%  |
| NVMe | 1        | 1      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 83       | 325    | 73.45%  |
| Malfunc  | 20       | 34     | 17.7%   |
| Detected | 9        | 29     | 7.96%   |
| Failed   | 1        | 2      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 48       | 27.12%  |
| Intel                       | 42       | 23.73%  |
| Samsung Electronics         | 26       | 14.69%  |
| ASMedia Technology          | 12       | 6.78%   |
| Phison Electronics          | 10       | 5.65%   |
| SanDisk                     | 9        | 5.08%   |
| Marvell Technology Group    | 5        | 2.82%   |
| Micron/Crucial Technology   | 4        | 2.26%   |
| JMicron Technology          | 4        | 2.26%   |
| Kingston Technology Company | 3        | 1.69%   |
| Broadcom / LSI              | 3        | 1.69%   |
| SK hynix                    | 2        | 1.13%   |
| Nvidia                      | 2        | 1.13%   |
| VIA Technologies            | 1        | 0.56%   |
| Silicon Motion              | 1        | 0.56%   |
| Silicon Image               | 1        | 0.56%   |
| Realtek Semiconductor       | 1        | 0.56%   |
| MAXIO Technology (Hangzhou) | 1        | 0.56%   |
| LSI Logic / Symbios Logic   | 1        | 0.56%   |
| ADATA Technology            | 1        | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 36       | 17.65%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12       | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11       | 5.39%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10       | 4.9%    |
| Samsung NVMe SSD Controller 980                                                | 6        | 2.94%   |
| AMD 500 Series Chipset SATA Controller                                         | 6        | 2.94%   |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 2.94%   |
| Phison E18 PCIe4 NVMe Controller                                               | 5        | 2.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 1.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 1.47%   |
| Intel SSD 660P Series                                                          | 3        | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3        | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 1.47%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 2        | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2        | 0.98%   |
| Phison E7 NVMe Controller                                                      | 2        | 0.98%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.98%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.98%   |
| Nvidia MCP79 SATA Controller                                                   | 2        | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 0.98%   |
| Kingston Company FURY Renegade NVMe SSD                                        | 2        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 0.98%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 0.98%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 2        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 0.98%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 0.49%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1        | 0.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.49%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                             | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 85       | 55.19%  |
| NVMe | 48       | 31.17%  |
| IDE  | 12       | 7.79%   |
| RAID | 5        | 3.25%   |
| SAS  | 4        | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 49       | 52.69%  |
| Intel  | 44       | 47.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| AMD Ryzen 9 7900X 12-Core Processor      | 6        | 6.45%   |
| AMD Ryzen 9 7950X 16-Core Processor      | 4        | 4.3%    |
| AMD Ryzen 7 3700X 8-Core Processor       | 4        | 4.3%    |
| AMD Ryzen 5 5600X 6-Core Processor       | 4        | 4.3%    |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 3        | 3.23%   |
| AMD Ryzen 9 5950X 16-Core Processor      | 3        | 3.23%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 3        | 3.23%   |
| Intel Core i9-10850K CPU @ 3.60GHz       | 2        | 2.15%   |
| Intel Core i7-10700K CPU @ 3.80GHz       | 2        | 2.15%   |
| Intel Atom CPU D510 @ 1.66GHz            | 2        | 2.15%   |
| Intel Atom CPU 330 @ 1.60GHz             | 2        | 2.15%   |
| Intel 11th Gen Core i9-11900KF @ 3.50GHz | 2        | 2.15%   |
| AMD Ryzen 9 3950X 16-Core Processor      | 2        | 2.15%   |
| AMD Ryzen 7 5800X3D 8-Core Processor     | 2        | 2.15%   |
| AMD Ryzen 5 7600X 6-Core Processor       | 2        | 2.15%   |
| AMD Ryzen 5 5500                         | 2        | 2.15%   |
| AMD Phenom II X4 955 Processor           | 2        | 2.15%   |
| Intel Xeon W-2145 CPU @ 3.70GHz          | 1        | 1.08%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1        | 1.08%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz      | 1        | 1.08%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz      | 1        | 1.08%   |
| Intel Pentium III CPU - S 1400MHz        | 1        | 1.08%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 1        | 1.08%   |
| Intel Pentium 4 CPU 2.66GHz              | 1        | 1.08%   |
| Intel Core i7-9700KF CPU @ 3.60GHz       | 1        | 1.08%   |
| Intel Core i7-9700 CPU @ 3.00GHz         | 1        | 1.08%   |
| Intel Core i7-8700K CPU @ 3.70GHz        | 1        | 1.08%   |
| Intel Core i7-7800X CPU @ 3.50GHz        | 1        | 1.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 1        | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 1        | 1.08%   |
| Intel Core i7-4930K CPU @ 3.40GHz        | 1        | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 1        | 1.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 1        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 1        | 1.08%   |
| Intel Core i7 CPU 970 @ 3.20GHz          | 1        | 1.08%   |
| Intel Core i7 CPU 950 @ 3.07GHz          | 1        | 1.08%   |
| Intel Core i5-4590T CPU @ 2.00GHz        | 1        | 1.08%   |
| Intel Core i5-3450 CPU @ 3.10GHz         | 1        | 1.08%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 1        | 1.08%   |
| Intel Core i3-2100T CPU @ 2.50GHz        | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 9       | 20       | 21.51%  |
| Intel Core i7     | 14       | 15.05%  |
| AMD Ryzen 5       | 14       | 15.05%  |
| AMD Ryzen 7       | 9        | 9.68%   |
| Other             | 8        | 8.6%    |
| Intel Xeon        | 7        | 7.53%   |
| Intel Atom        | 5        | 5.38%   |
| AMD Phenom II X4  | 3        | 3.23%   |
| Intel Core i9     | 2        | 2.15%   |
| Intel Core i5     | 2        | 2.15%   |
| Intel Core i3     | 2        | 2.15%   |
| AMD FX            | 2        | 2.15%   |
| Intel Pentium III | 1        | 1.08%   |
| Intel Pentium 4   | 1        | 1.08%   |
| Intel Pentium     | 1        | 1.08%   |
| Intel Celeron     | 1        | 1.08%   |
| AMD Athlon        | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 22.58%  |
| 8      | 19       | 20.43%  |
| 6      | 17       | 18.28%  |
| 16     | 12       | 12.9%   |
| 12     | 11       | 11.83%  |
| 2      | 9        | 9.68%   |
| 10     | 2        | 2.15%   |
| 44     | 1        | 1.08%   |
| 1      | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 91       | 97.85%  |
| 2      | 2        | 2.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 84.95%  |
| 1      | 14       | 15.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 91       | 97.85%  |
| 32-bit         | 2        | 2.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 29.79%  |
| 0x0a601203 | 12       | 12.77%  |
| 0x0a20120a | 6        | 6.38%   |
| 0x08701021 | 6        | 6.38%   |
| 0x0800820d | 4        | 4.26%   |
| 0x306c3    | 3        | 3.19%   |
| 0xa0671    | 2        | 2.13%   |
| 0x906ed    | 2        | 2.13%   |
| 0x906ea    | 2        | 2.13%   |
| 0x0a50000d | 2        | 2.13%   |
| 0x0a201016 | 2        | 2.13%   |
| 0xf29      | 1        | 1.06%   |
| 0xa0655    | 1        | 1.06%   |
| 0x906e9    | 1        | 1.06%   |
| 0x806c1    | 1        | 1.06%   |
| 0x506e3    | 1        | 1.06%   |
| 0x50654    | 1        | 1.06%   |
| 0x406f1    | 1        | 1.06%   |
| 0x406c4    | 1        | 1.06%   |
| 0x306e4    | 1        | 1.06%   |
| 0x306a9    | 1        | 1.06%   |
| 0x106c2    | 1        | 1.06%   |
| 0x106a5    | 1        | 1.06%   |
| 0x0a601201 | 1        | 1.06%   |
| 0x0a50000c | 1        | 1.06%   |
| 0x0a201205 | 1        | 1.06%   |
| 0x0a201025 | 1        | 1.06%   |
| 0x08701030 | 1        | 1.06%   |
| 0x08701013 | 1        | 1.06%   |
| 0x08108109 | 1        | 1.06%   |
| 0x08001138 | 1        | 1.06%   |
| 0x0700010f | 1        | 1.06%   |
| 0x06000822 | 1        | 1.06%   |
| 0x0600063e | 1        | 1.06%   |
| 0x010000db | 1        | 1.06%   |
| 0x010000c8 | 1        | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 15       | 16.13%  |
| Unknown          | 13       | 13.98%  |
| Zen 2            | 9        | 9.68%   |
| IvyBridge        | 7        | 7.53%   |
| Zen+             | 5        | 5.38%   |
| KabyLake         | 5        | 5.38%   |
| Bonnell          | 5        | 5.38%   |
| Skylake          | 4        | 4.3%    |
| Icelake          | 4        | 4.3%    |
| Haswell          | 4        | 4.3%    |
| CometLake        | 4        | 4.3%    |
| K10              | 3        | 3.23%   |
| Alderlake Hybrid | 3        | 3.23%   |
| Zen              | 1        | 1.08%   |
| Westmere         | 1        | 1.08%   |
| TigerLake        | 1        | 1.08%   |
| Silvermont       | 1        | 1.08%   |
| SandyBridge      | 1        | 1.08%   |
| Piledriver       | 1        | 1.08%   |
| P6               | 1        | 1.08%   |
| NetBurst         | 1        | 1.08%   |
| Nehalem          | 1        | 1.08%   |
| Jaguar           | 1        | 1.08%   |
| Bulldozer        | 1        | 1.08%   |
| Broadwell        | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 46       | 45.1%   |
| Nvidia                     | 36       | 35.29%  |
| Intel                      | 15       | 14.71%  |
| Matrox Electronics Systems | 4        | 3.92%   |
| ASPEED Technology          | 1        | 0.98%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Raphael                                                                 | 10       | 8.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 6.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 6.19%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 5        | 4.42%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 4        | 3.54%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 3.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 2.65%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 2.65%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 2.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 3        | 2.65%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 2.65%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 2.65%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.77%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.77%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 1.77%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.77%   |
| Nvidia C79 [ION]                                                            | 2        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 1.77%   |
| Intel HD Graphics 530                                                       | 2        | 1.77%   |
| AMD RS780C [Radeon 3100]                                                    | 2        | 1.77%   |
| Nvidia VGA compatible controller                                            | 1        | 0.88%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.88%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.88%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.88%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.88%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 0.88%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1        | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1        | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 33       | 34.38%  |
| 1 x Nvidia     | 28       | 29.17%  |
| 1 x Intel      | 11       | 11.46%  |
| 2 x AMD        | 9        | 9.38%   |
| AMD + Nvidia   | 6        | 6.25%   |
| 1 x Matrox     | 4        | 4.17%   |
| Intel + Nvidia | 2        | 2.08%   |
| 2 x Intel      | 1        | 1.04%   |
| Intel + AMD    | 1        | 1.04%   |
| 1 x ASPEED     | 1        | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 64.21%  |
| Proprietary | 25       | 26.32%  |
| Unknown     | 9        | 9.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 26.88%  |
| 7.01-8.0   | 19       | 20.43%  |
| 8.01-16.0  | 17       | 18.28%  |
| 0.01-0.5   | 8        | 8.6%    |
| 0.51-1.0   | 7        | 7.53%   |
| 16.01-24.0 | 6        | 6.45%   |
| 1.01-2.0   | 4        | 4.3%    |
| 5.01-6.0   | 3        | 3.23%   |
| 3.01-4.0   | 3        | 3.23%   |
| 2.01-3.0   | 1        | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 18       | 18.37%  |
| Dell                    | 11       | 11.22%  |
| Goldstar                | 9        | 9.18%   |
| ASUSTek Computer        | 8        | 8.16%   |
| AOC                     | 7        | 7.14%   |
| BenQ                    | 6        | 6.12%   |
| Acer                    | 5        | 5.1%    |
| Ancor Communications    | 4        | 4.08%   |
| Unknown                 | 3        | 3.06%   |
| Gigabyte Technology     | 3        | 3.06%   |
| Lenovo                  | 2        | 2.04%   |
| Iiyama                  | 2        | 2.04%   |
| Hewlett-Packard         | 2        | 2.04%   |
| Eizo                    | 2        | 2.04%   |
| Vizio                   | 1        | 1.02%   |
| Sceptre Tech            | 1        | 1.02%   |
| Philips                 | 1        | 1.02%   |
| Onkyo                   | 1        | 1.02%   |
| MStar                   | 1        | 1.02%   |
| Microstep               | 1        | 1.02%   |
| Idek Iiyama             | 1        | 1.02%   |
| IBM                     | 1        | 1.02%   |
| HJW                     | 1        | 1.02%   |
| Gateway                 | 1        | 1.02%   |
| Envision Peripherals    | 1        | 1.02%   |
| Denver                  | 1        | 1.02%   |
| Chi Mei Optoelectronics | 1        | 1.02%   |
| Arnos Instruments       | 1        | 1.02%   |
| AHA                     | 1        | 1.02%   |
| Unknown                 | 1        | 1.02%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 2        | 1.87%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 2        | 1.87%   |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1420x800mm 64.2-inch  | 2        | 1.87%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2        | 1.87%   |
| Gigabyte Technology G27FC A GBT2715 1920x1080 598x336mm 27.0-inch       | 2        | 1.87%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2        | 1.87%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 2        | 1.87%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch            | 2        | 1.87%   |
| AOC LCD Monitor U2879G6 3840x2160                                       | 2        | 1.87%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                        | 2        | 1.87%   |
| Acer ED320QR S ACR0805 1920x1080 609x348mm 27.6-inch                    | 2        | 1.87%   |
| Vizio D43n-E1 VIZ1009 1920x1080 953x543mm 43.2-inch                     | 1        | 0.93%   |
| Unknown LCD Monitor RTK                                                 | 1        | 0.93%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch         | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                        | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch    | 1        | 0.93%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch     | 1        | 0.93%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1        | 0.93%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch    | 1        | 0.93%   |
| Samsung Electronics SME2020N SAM06A6 1600x900 443x249mm 20.0-inch       | 1        | 0.93%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch       | 1        | 0.93%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1872x1053mm 84.6-inch | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768 700x390mm 31.5-inch    | 1        | 0.93%   |
| Samsung Electronics LCD Monitor C27FG7x 1920x1080                       | 1        | 0.93%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1        | 0.93%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch      | 1        | 0.93%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch       | 1        | 0.93%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.93%   |
| Philips LCD Monitor PHL 246V5 3840x1080                                 | 1        | 0.93%   |
| Philips LCD Monitor PHL 246V5                                           | 1        | 0.93%   |
| Onkyo AV Receiver ONK1061 1024x768                                      | 1        | 0.93%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                          | 1        | 0.93%   |
| Microstep LCD Monitor Optix MAG27CQ 2560x1440                           | 1        | 0.93%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                | 1        | 0.93%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch                  | 1        | 0.93%   |
| Iiyama PL2792UH IVM664C 3840x2160 596x335mm 26.9-inch                   | 1        | 0.93%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                    | 1        | 0.93%   |
| Idek Iiyama LCD Monitor PL2473HD 1920x1080                              | 1        | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 30.21%  |
| 3840x2160 (4K)     | 22       | 22.92%  |
| 2560x1440 (QHD)    | 15       | 15.63%  |
| 3440x1440          | 6        | 6.25%   |
| 3840x1080          | 3        | 3.13%   |
| Unknown            | 3        | 3.13%   |
| 2560x1080          | 2        | 2.08%   |
| 2288x1287          | 2        | 2.08%   |
| 1920x1200 (WUXGA)  | 2        | 2.08%   |
| 1680x1050 (WSXGA+) | 2        | 2.08%   |
| 1600x900 (HD+)     | 2        | 2.08%   |
| 1440x900 (WXGA+)   | 2        | 2.08%   |
| 1024x768 (XGA)     | 2        | 2.08%   |
| 3840x1200          | 1        | 1.04%   |
| 1360x768           | 1        | 1.04%   |
| 1280x800 (WXGA)    | 1        | 1.04%   |
| 1280x1024 (SXGA)   | 1        | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 26       | 26.26%  |
| Unknown | 11       | 11.11%  |
| 24      | 10       | 10.1%   |
| 23      | 7        | 7.07%   |
| 21      | 7        | 7.07%   |
| 34      | 6        | 6.06%   |
| 31      | 5        | 5.05%   |
| 84      | 3        | 3.03%   |
| 32      | 3        | 3.03%   |
| 19      | 3        | 3.03%   |
| 142     | 2        | 2.02%   |
| 22      | 2        | 2.02%   |
| 49      | 1        | 1.01%   |
| 48      | 1        | 1.01%   |
| 43      | 1        | 1.01%   |
| 42      | 1        | 1.01%   |
| 41      | 1        | 1.01%   |
| 40      | 1        | 1.01%   |
| 35      | 1        | 1.01%   |
| 29      | 1        | 1.01%   |
| 26      | 1        | 1.01%   |
| 25      | 1        | 1.01%   |
| 20      | 1        | 1.01%   |
| 17      | 1        | 1.01%   |
| 15      | 1        | 1.01%   |
| 9       | 1        | 1.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 38       | 41.3%   |
| 401-500        | 11       | 11.96%  |
| Unknown        | 11       | 11.96%  |
| 701-800        | 9        | 9.78%   |
| 601-700        | 8        | 8.7%    |
| 1501-2000      | 3        | 3.26%   |
| 901-1000       | 3        | 3.26%   |
| More than 2000 | 2        | 2.17%   |
| 801-900        | 2        | 2.17%   |
| 301-350        | 2        | 2.17%   |
| 1001-1500      | 2        | 2.17%   |
| 201-300        | 1        | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 55       | 62.5%   |
| 16/10   | 10       | 11.36%  |
| Unknown | 9        | 10.23%  |
| 21/9    | 7        | 7.95%   |
| 4/3     | 2        | 2.27%   |
| 32/9    | 2        | 2.27%   |
| 1.00    | 2        | 2.27%   |
| 5/4     | 1        | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 27       | 28.42%  |
| 201-250        | 18       | 18.95%  |
| 351-500        | 15       | 15.79%  |
| Unknown        | 11       | 11.58%  |
| 501-1000       | 6        | 6.32%   |
| More than 1000 | 5        | 5.26%   |
| 251-300        | 5        | 5.26%   |
| 151-200        | 5        | 5.26%   |
| 41-50          | 1        | 1.05%   |
| 141-150        | 1        | 1.05%   |
| 101-110        | 1        | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 41       | 44.57%  |
| 101-120 | 24       | 26.09%  |
| Unknown | 11       | 11.96%  |
| 161-240 | 7        | 7.61%   |
| 121-160 | 5        | 5.43%   |
| 1-50    | 4        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 68.75%  |
| 2     | 14       | 14.58%  |
| 0     | 10       | 10.42%  |
| 3     | 4        | 4.17%   |
| 4     | 2        | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 53       | 38.13%  |
| Realtek Semiconductor           | 49       | 35.25%  |
| MediaTek                        | 8        | 5.76%   |
| Qualcomm Atheros                | 6        | 4.32%   |
| Broadcom                        | 5        | 3.6%    |
| Qualcomm Atheros Communications | 2        | 1.44%   |
| Microsoft                       | 2        | 1.44%   |
| Aquantia                        | 2        | 1.44%   |
| Wilocity                        | 1        | 0.72%   |
| Ralink                          | 1        | 0.72%   |
| OpenMoko                        | 1        | 0.72%   |
| Nvidia                          | 1        | 0.72%   |
| NetGear                         | 1        | 0.72%   |
| Mellanox Technologies           | 1        | 0.72%   |
| Marvell Technology Group        | 1        | 0.72%   |
| ICS Advent                      | 1        | 0.72%   |
| Huawei Technologies             | 1        | 0.72%   |
| Hewlett-Packard                 | 1        | 0.72%   |
| Broadcom Limited                | 1        | 0.72%   |
| ASIX Electronics                | 1        | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Desktops | Percent |
|------------------------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 33       | 19.64%  |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 15       | 8.93%   |
| Intel I211 Gigabit Network Connection                                                                                  | 14       | 8.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 13       | 7.74%   |
| Intel Ethernet Controller I225-V                                                                                       | 13       | 7.74%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 9        | 5.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 4        | 2.38%   |
| Intel Wireless-AC 9260                                                                                                 | 4        | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                          | 3        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                                                                   | 3        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                                                                   | 3        | 1.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                                                       | 3        | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                                                                        | 2        | 1.19%   |
| Microsoft Xbox Wireless Adapter for Windows                                                                            | 2        | 1.19%   |
| Intel I350 Gigabit Network Connection                                                                                  | 2        | 1.19%   |
| Intel Ethernet Connection I217-V                                                                                       | 2        | 1.19%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                                       | 2        | 1.19%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                                                   | 2        | 1.19%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                                                     | 1        | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 1        | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                            | 1        | 0.6%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                                                 | 1        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                                        | 1        | 0.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                                             | 1        | 0.6%    |
| Realtek Killer E3000 2.5GbE Controller                                                                                 | 1        | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                                              | 1        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                                             | 1        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                                         | 1        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                                         | 1        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                                          | 1        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                                               | 1        | 0.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                                             | 1        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                                                | 1        | 0.6%    |
| OpenMoko OneRNG entropy device                                                                                         | 1        | 0.6%    |
| Nvidia MCP79 Ethernet                                                                                                  | 1        | 0.6%    |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                                                                       | 1        | 0.6%    |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 1        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 1        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                                                | 1        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 27       | 51.92%  |
| MediaTek                        | 8        | 15.38%  |
| Qualcomm Atheros                | 5        | 9.62%   |
| Realtek Semiconductor           | 3        | 5.77%   |
| Qualcomm Atheros Communications | 2        | 3.85%   |
| Microsoft                       | 2        | 3.85%   |
| Wilocity                        | 1        | 1.92%   |
| Ralink                          | 1        | 1.92%   |
| NetGear                         | 1        | 1.92%   |
| Broadcom Limited                | 1        | 1.92%   |
| Broadcom                        | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 13       | 24.53%  |
| Intel Wi-Fi 6 AX200                                                     | 9        | 16.98%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4        | 7.55%   |
| Intel Wireless-AC 9260                                                  | 4        | 7.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3        | 5.66%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2        | 3.77%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 2        | 3.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2        | 3.77%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                      | 1        | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1        | 1.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1        | 1.89%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1        | 1.89%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1        | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.89%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1        | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.89%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                        | 1        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.89%   |
| Broadcom Network controller                                             | 1        | 1.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 48       | 46.15%  |
| Intel                    | 43       | 41.35%  |
| Broadcom                 | 4        | 3.85%   |
| Qualcomm Atheros         | 2        | 1.92%   |
| Aquantia                 | 2        | 1.92%   |
| Nvidia                   | 1        | 0.96%   |
| Marvell Technology Group | 1        | 0.96%   |
| ICS Advent               | 1        | 0.96%   |
| Hewlett-Packard          | 1        | 0.96%   |
| ASIX Electronics         | 1        | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33       | 29.46%  |
| Realtek RTL8125 2.5GbE Controller                                             | 15       | 13.39%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 12.5%   |
| Intel Ethernet Controller I225-V                                              | 13       | 11.61%  |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 2.68%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.68%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 2.68%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.79%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.79%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.89%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.89%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.89%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.89%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.89%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 0.89%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.89%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.89%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.89%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.89%   |
| HP Virtual NIC                                                                | 1        | 0.89%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1        | 0.89%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.89%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 1        | 0.89%   |
| Aquantia AQC113C NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]            | 1        | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 92       | 64.79%  |
| WiFi     | 47       | 33.1%   |
| Modem    | 2        | 1.41%   |
| Unknown  | 1        | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 82.29%  |
| WiFi     | 17       | 17.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 41       | 43.62%  |
| 1     | 37       | 39.36%  |
| 3     | 9        | 9.57%   |
| 7     | 2        | 2.13%   |
| 6     | 2        | 2.13%   |
| 4     | 2        | 2.13%   |
| 5     | 1        | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 64.21%  |
| Yes  | 34       | 35.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 55.56%  |
| MediaTek                        | 7        | 15.56%  |
| Realtek Semiconductor           | 3        | 6.67%   |
| IMC Networks                    | 2        | 4.44%   |
| Foxconn / Hon Hai               | 2        | 4.44%   |
| Cambridge Silicon Radio         | 2        | 4.44%   |
| ASUSTek Computer                | 2        | 4.44%   |
| Qualcomm Atheros Communications | 1        | 2.22%   |
| Broadcom                        | 1        | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 10       | 22.22%  |
| Intel AX200 Bluetooth                               | 9        | 20%     |
| MediaTek Wireless_Device                            | 7        | 15.56%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 8.89%   |
| Realtek Bluetooth Radio                             | 3        | 6.67%   |
| Intel Bluetooth Device                              | 2        | 4.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 4.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.22%   |
| IMC Networks Wireless_Device                        | 1        | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.22%   |
| Broadcom BCM20702A0                                 | 1        | 2.22%   |
| ASUS Bluetooth Device                               | 1        | 2.22%   |
| ASUS ASUS USB-BT500                                 | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 54       | 29.83%  |
| Nvidia                               | 35       | 19.34%  |
| Intel                                | 30       | 16.57%  |
| ASUSTek Computer                     | 10       | 5.52%   |
| C-Media Electronics                  | 9        | 4.97%   |
| SteelSeries ApS                      | 3        | 1.66%   |
| Creative Labs                        | 3        | 1.66%   |
| Thesycon Systemsoftware & Consulting | 2        | 1.1%    |
| Solid State Logic                    | 2        | 1.1%    |
| Razer USA                            | 2        | 1.1%    |
| Audient                              | 2        | 1.1%    |
| AKG C44-USB Microphone               | 2        | 1.1%    |
| Yamaha                               | 1        | 0.55%   |
| VIA Technologies                     | 1        | 0.55%   |
| Texas Instruments                    | 1        | 0.55%   |
| TEAC                                 | 1        | 0.55%   |
| Sony                                 | 1        | 0.55%   |
| Schiit Audio                         | 1        | 0.55%   |
| Scarlett                             | 1        | 0.55%   |
| SAVITECH                             | 1        | 0.55%   |
| RODE Microphones                     | 1        | 0.55%   |
| Microsoft                            | 1        | 0.55%   |
| Micro Star International             | 1        | 0.55%   |
| Medeli Electronics                   | 1        | 0.55%   |
| MAG Technology                       | 1        | 0.55%   |
| M-Audio                              | 1        | 0.55%   |
| Logitech                             | 1        | 0.55%   |
| Kingston Technology                  | 1        | 0.55%   |
| JMTek                                | 1        | 0.55%   |
| Huawei Technologies                  | 1        | 0.55%   |
| GYROCOM C&C                          | 1        | 0.55%   |
| Elgato Systems                       | 1        | 0.55%   |
| Corsair                              | 1        | 0.55%   |
| BEHRINGER International              | 1        | 0.55%   |
| ASRock                               | 1        | 0.55%   |
| ARCAM                                | 1        | 0.55%   |
| Anlya.cn                             | 1        | 0.55%   |
| AKAI Professional M.I.               | 1        | 0.55%   |
| Unknown                              | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 20       | 9.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 15       | 6.82%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 10       | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 10       | 4.55%   |
| ASUSTek Computer USB Audio                                                                      | 7        | 3.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 7        | 3.18%   |
| Nvidia TU104 HD Audio Controller                                                                | 5        | 2.27%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 5        | 2.27%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                                         | 5        | 2.27%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 4        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 4        | 1.82%   |
| AMD Navi 10 HDMI Audio                                                                          | 4        | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 1.82%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 3        | 1.36%   |
| Nvidia AD102 High Definition Audio Controller                                                   | 3        | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 1.36%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 3        | 1.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 3        | 1.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.36%   |
| Thesycon Systemsoftware & Consulting SABAJ USB AUDIO                                            | 2        | 0.91%   |
| Nvidia MCP79 High Definition Audio                                                              | 2        | 0.91%   |
| Nvidia High Definition Audio Controller                                                         | 2        | 0.91%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 2        | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                                              | 2        | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 2        | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 2        | 0.91%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 2        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2        | 0.91%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 0.91%   |
| C-Media Electronics USB Audio Device                                                            | 2        | 0.91%   |
| Audient EVO4                                                                                    | 2        | 0.91%   |
| ASUSTek Computer Xonar SoundCard                                                                | 2        | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2        | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 2        | 0.91%   |
| AKG C44-USB Microphone AKG C44-USB Microphone                                                   | 2        | 0.91%   |
| Yamaha Steinberg UR22C                                                                          | 1        | 0.45%   |
| VIA Technologies FX-AUDIO-DAC-X6                                                                | 1        | 0.45%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 1        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 22       | 23.66%  |
| Corsair             | 19       | 20.43%  |
| Kingston            | 14       | 15.05%  |
| Crucial             | 11       | 11.83%  |
| Unknown             | 10       | 10.75%  |
| Team                | 3        | 3.23%   |
| Micron Technology   | 3        | 3.23%   |
| A-DATA Technology   | 3        | 3.23%   |
| SK hynix            | 1        | 1.08%   |
| SGS/Thomson         | 1        | 1.08%   |
| Samsung Electronics | 1        | 1.08%   |
| Patriot Memory      | 1        | 1.08%   |
| Patriot             | 1        | 1.08%   |
| Nanya Technology    | 1        | 1.08%   |
| HPE                 | 1        | 1.08%   |
| Hewlett-Packard     | 1        | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s       | 4        | 4.04%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s       | 3        | 3.03%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3400MT/s   | 3        | 3.03%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                  | 2        | 2.02%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                   | 2        | 2.02%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s        | 2        | 2.02%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s      | 2        | 2.02%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s      | 2        | 2.02%   |
| Unknown RAM Module 512MB DIMM                              | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1        | 1.01%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                       | 1        | 1.01%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                    | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s         | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s         | 1        | 1.01%   |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                 | 1        | 1.01%   |
| SK hynix RAM Module 16GB DIMM DDR4 2133MT/s                | 1        | 1.01%   |
| SGS/Thomson RAM Module 1GB DIMM SDRAM 2048MT/s             | 1        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.01%   |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                  | 1        | 1.01%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s | 1        | 1.01%   |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s         | 1        | 1.01%   |
| Micron RAM 36JSF2G72PZ-1G9N1 16GB DIMM DDR3 1866MT/s       | 1        | 1.01%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s       | 1        | 1.01%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s       | 1        | 1.01%   |
| Micron RAM 16JTF51264AZ-1G4D 4GB DIMM DDR3 1333MT/s        | 1        | 1.01%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.01%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s          | 1        | 1.01%   |
| Kingston RAM KF564C32-16 16GB DIMM DDR5 6400MT/s           | 1        | 1.01%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s           | 1        | 1.01%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3600MT/s      | 1        | 1.01%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.01%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 1.01%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s      | 1        | 1.01%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 1.01%   |
| Kingston RAM HP698651-154-KEB 8GB DIMM DDR3 1333MT/s       | 1        | 1.01%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s      | 1        | 1.01%   |
| Kingston RAM 99U5474-037.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 1.01%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 49.44%  |
| DDR5    | 17       | 19.1%   |
| DDR3    | 17       | 19.1%   |
| DDR2    | 5        | 5.62%   |
| Unknown | 3        | 3.37%   |
| SDRAM   | 2        | 2.25%   |
| DDR     | 1        | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 87       | 96.67%  |
| SODIMM | 3        | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 31       | 33.7%   |
| 8192  | 24       | 26.09%  |
| 32768 | 18       | 19.57%  |
| 4096  | 9        | 9.78%   |
| 2048  | 7        | 7.61%   |
| 1024  | 2        | 2.17%   |
| 512   | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 11       | 11.7%   |
| 1600    | 10       | 10.64%  |
| 3200    | 7        | 7.45%   |
| 6400    | 6        | 6.38%   |
| 1333    | 5        | 5.32%   |
| 6000    | 4        | 4.26%   |
| 4800    | 4        | 4.26%   |
| 3400    | 4        | 4.26%   |
| 1866    | 4        | 4.26%   |
| 667     | 4        | 4.26%   |
| 3866    | 3        | 3.19%   |
| 3666    | 3        | 3.19%   |
| 2666    | 3        | 3.19%   |
| 800     | 3        | 3.19%   |
| 5200    | 2        | 2.13%   |
| 3800    | 2        | 2.13%   |
| 3466    | 2        | 2.13%   |
| 2667    | 2        | 2.13%   |
| 2400    | 2        | 2.13%   |
| 2133    | 2        | 2.13%   |
| 2048    | 2        | 2.13%   |
| 5600    | 1        | 1.06%   |
| 3933    | 1        | 1.06%   |
| 3733    | 1        | 1.06%   |
| 3534    | 1        | 1.06%   |
| 3533    | 1        | 1.06%   |
| 3100    | 1        | 1.06%   |
| 1066    | 1        | 1.06%   |
| 333     | 1        | 1.06%   |
| Unknown | 1        | 1.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 1        | 25%     |
| Samsung Electronics | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |
| Brother Industries  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-4200 Series | 1        | 25%     |
| Samsung ML-1630 Series     | 1        | 25%     |
| HP LaserJet M14-M17        | 1        | 25%     |
| Brother MFC-9340CDW        | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 1        | 50%     |
| AGFA-Gevaert NV | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| AGFA-Gevaert NV SnapScan e20  | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 28.57%  |
| Sunplus Innovation Technology | 2        | 9.52%   |
| Samsung Electronics           | 2        | 9.52%   |
| Microsoft                     | 2        | 9.52%   |
| Microdia                      | 2        | 9.52%   |
| MacroSilicon                  | 2        | 9.52%   |
| Quanta                        | 1        | 4.76%   |
| GEMBIRD                       | 1        | 4.76%   |
| Elgato Systems                | 1        | 4.76%   |
| Chicony Electronics           | 1        | 4.76%   |
| A4Tech                        | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)              | 2        | 9.52%   |
| MacroSilicon USB Video               | 2        | 9.52%   |
| Logitech C922 Pro Stream Webcam      | 2        | 9.52%   |
| Sunplus MiraBox Video Capture        | 1        | 4.76%   |
| Sunplus Full HD webcam               | 1        | 4.76%   |
| Quanta RGB-IR Camera                 | 1        | 4.76%   |
| Microsoft MicrosoftÂ LifeCam Studio | 1        | 4.76%   |
| Microsoft LifeCam Cinema             | 1        | 4.76%   |
| Microdia REDRAGON Live Camera Audio  | 1        | 4.76%   |
| Microdia Camera                      | 1        | 4.76%   |
| Logitech Webcam C270                 | 1        | 4.76%   |
| Logitech StreamCam                   | 1        | 4.76%   |
| Logitech BRIO Ultra HD Webcam        | 1        | 4.76%   |
| Logitech BRIO 4K Stream Edition      | 1        | 4.76%   |
| GEMBIRD USB2.0 PC CAMERA             | 1        | 4.76%   |
| Elgato Systems Elgato Facecam        | 1        | 4.76%   |
| Chicony Gateway Webcam               | 1        | 4.76%   |
| A4Tech REDRAGON Live Camera          | 1        | 4.76%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| Hewlett-Packard       | 1        | 25%     |
| Bit4id                | 1        | 25%     |
| Advanced Card Systems | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 25%     |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)          | 1        | 25%     |
| Bit4id miniLector-s                                    | 1        | 25%     |
| Advanced Card Systems ACR122U                          | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 51       | 52.58%  |
| 1     | 26       | 26.8%   |
| 2     | 11       | 11.34%  |
| 3     | 4        | 4.12%   |
| 6     | 2        | 2.06%   |
| 7     | 1        | 1.03%   |
| 5     | 1        | 1.03%   |
| 4     | 1        | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 18.57%  |
| Communication controller | 12       | 17.14%  |
| Net/wireless             | 11       | 15.71%  |
| Bluetooth                | 7        | 10%     |
| Sound                    | 6        | 8.57%   |
| Network                  | 4        | 5.71%   |
| Storage/ide              | 3        | 4.29%   |
| Net/ethernet             | 3        | 4.29%   |
| Firewire controller      | 3        | 4.29%   |
| Camera                   | 2        | 2.86%   |
| Unassigned class         | 1        | 1.43%   |
| Storage/raid             | 1        | 1.43%   |
| Storage/ata              | 1        | 1.43%   |
| Multimedia controller    | 1        | 1.43%   |
| Chipcard                 | 1        | 1.43%   |
| Card reader              | 1        | 1.43%   |

