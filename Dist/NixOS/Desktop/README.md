NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 497

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Packard Be... | IMEDIA S2185                | [8cd832ce44](https://linux-hardware.org/?probe=8cd832ce44) | Jan 01, 2026 |
| ASRock        | J4125M                      | [73bf79c7ab](https://linux-hardware.org/?probe=73bf79c7ab) | Dec 28, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [332a3f5508](https://linux-hardware.org/?probe=332a3f5508) | Dec 27, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | [4e14db0632](https://linux-hardware.org/?probe=4e14db0632) | Dec 21, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cc2b3fa079](https://linux-hardware.org/?probe=cc2b3fa079) | Dec 18, 2025 |
| Gigabyte      | Z270X-UD3-CF                | [6279616824](https://linux-hardware.org/?probe=6279616824) | Dec 18, 2025 |
| Gigabyte      | Z270X-UD3-CF                | [14a7fde1cf](https://linux-hardware.org/?probe=14a7fde1cf) | Dec 18, 2025 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [21ba85fbd1](https://linux-hardware.org/?probe=21ba85fbd1) | Dec 18, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | [db3911f23f](https://linux-hardware.org/?probe=db3911f23f) | Dec 14, 2025 |
| Lenovo        | 1066 NOK                    | [3f6467951f](https://linux-hardware.org/?probe=3f6467951f) | Dec 11, 2025 |
| ASRock        | B850 Steel Legend WiFi      | [2ef0fc7259](https://linux-hardware.org/?probe=2ef0fc7259) | Dec 10, 2025 |
| ASRock        | X570 Phantom Gaming-ITX/... | [122966ef35](https://linux-hardware.org/?probe=122966ef35) | Dec 08, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [df39a3dd43](https://linux-hardware.org/?probe=df39a3dd43) | Dec 08, 2025 |
| Gigabyte      | Z390 GAMING SLI-CF          | [ce0d048003](https://linux-hardware.org/?probe=ce0d048003) | Dec 08, 2025 |
| Gigabyte      | Z390 GAMING SLI-CF          | [40cdbd71e9](https://linux-hardware.org/?probe=40cdbd71e9) | Dec 08, 2025 |
| Gigabyte      | Z690 UD DDR4                | [5149256742](https://linux-hardware.org/?probe=5149256742) | Dec 08, 2025 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [59704e13be](https://linux-hardware.org/?probe=59704e13be) | Dec 07, 2025 |
| Gigabyte      | Z170-HD3-CF                 | [db42fcbc8b](https://linux-hardware.org/?probe=db42fcbc8b) | Dec 07, 2025 |
| Gigabyte      | Z170-HD3-CF                 | [ee0dfcae36](https://linux-hardware.org/?probe=ee0dfcae36) | Dec 07, 2025 |
| Lenovo        | 1066 NOK                    | [c25ceb76ec](https://linux-hardware.org/?probe=c25ceb76ec) | Dec 07, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [d60c022572](https://linux-hardware.org/?probe=d60c022572) | Dec 07, 2025 |
| Dell          | 0T7D40 A01                  | [ba6a0add71](https://linux-hardware.org/?probe=ba6a0add71) | Dec 07, 2025 |
| AZW           | MINI S 10                   | [3b25335cca](https://linux-hardware.org/?probe=3b25335cca) | Dec 07, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [3138dced71](https://linux-hardware.org/?probe=3138dced71) | Dec 07, 2025 |
| ASRock        | B550M Steel Legend          | [015b8ef8ac](https://linux-hardware.org/?probe=015b8ef8ac) | Dec 07, 2025 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [ccc7343e86](https://linux-hardware.org/?probe=ccc7343e86) | Dec 07, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [660f98f6c6](https://linux-hardware.org/?probe=660f98f6c6) | Dec 07, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [2be248c891](https://linux-hardware.org/?probe=2be248c891) | Dec 07, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [28ba832f3a](https://linux-hardware.org/?probe=28ba832f3a) | Dec 07, 2025 |
| MSI           | PRO B650-S WIFI             | [056a5b7ed0](https://linux-hardware.org/?probe=056a5b7ed0) | Dec 06, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | [922a5ed845](https://linux-hardware.org/?probe=922a5ed845) | Dec 06, 2025 |
| MSI           | MPG X570S CARBON MAX WIF... | [547f3ee0ed](https://linux-hardware.org/?probe=547f3ee0ed) | Dec 06, 2025 |
| ASRock        | B650M PG Riptide            | [cdbdc77a51](https://linux-hardware.org/?probe=cdbdc77a51) | Dec 06, 2025 |
| MSI           | B450M PRO-M2 MAX            | [e90d7b0917](https://linux-hardware.org/?probe=e90d7b0917) | Dec 06, 2025 |
| ASRock        | AB350M Pro4                 | [6cd071662d](https://linux-hardware.org/?probe=6cd071662d) | Dec 04, 2025 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [3ea11d6313](https://linux-hardware.org/?probe=3ea11d6313) | Dec 03, 2025 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [8534198a05](https://linux-hardware.org/?probe=8534198a05) | Dec 01, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [a87d4a13b3](https://linux-hardware.org/?probe=a87d4a13b3) | Nov 30, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [f316898d53](https://linux-hardware.org/?probe=f316898d53) | Nov 29, 2025 |
| ASUSTek       | PRIME B650M-A               | [fd87d5b77a](https://linux-hardware.org/?probe=fd87d5b77a) | Nov 29, 2025 |
| ASUSTek       | PRIME B550M-A               | [db6754a9c9](https://linux-hardware.org/?probe=db6754a9c9) | Nov 19, 2025 |
| MSI           | MAG B850M MORTAR WIFI       | [049e136079](https://linux-hardware.org/?probe=049e136079) | Nov 17, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [8df173db68](https://linux-hardware.org/?probe=8df173db68) | Nov 16, 2025 |
| Gigabyte      | Z170MX-Gaming 5             | [605ec1fff1](https://linux-hardware.org/?probe=605ec1fff1) | Nov 09, 2025 |
| ASUSTek       | PRIME A320M-K               | [9f287a9506](https://linux-hardware.org/?probe=9f287a9506) | Nov 08, 2025 |
| ASRock        | X670E Taichi                | [b638fb7057](https://linux-hardware.org/?probe=b638fb7057) | Nov 05, 2025 |
| ASRock        | X670E Taichi                | [d296b00f20](https://linux-hardware.org/?probe=d296b00f20) | Nov 05, 2025 |
| MSI           | MEG Z490I UNIFY             | [6c7f2eee25](https://linux-hardware.org/?probe=6c7f2eee25) | Oct 30, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [a34d1afd16](https://linux-hardware.org/?probe=a34d1afd16) | Oct 29, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | [600e34ee6e](https://linux-hardware.org/?probe=600e34ee6e) | Oct 25, 2025 |
| SYWZ          | S210HA Series               | [b0a9689e86](https://linux-hardware.org/?probe=b0a9689e86) | Oct 18, 2025 |
| ASRock        | B650E PG-ITX WiFi           | [5e94d376e2](https://linux-hardware.org/?probe=5e94d376e2) | Oct 02, 2025 |
| ASUSTek       | PRIME H410M-E               | [662c2990a5](https://linux-hardware.org/?probe=662c2990a5) | Oct 01, 2025 |
| ASRock        | X870 Steel Legend WiFi      | [3399f186a9](https://linux-hardware.org/?probe=3399f186a9) | Sep 28, 2025 |
| ASRock        | X870 Steel Legend WiFi      | [5a220ebc6d](https://linux-hardware.org/?probe=5a220ebc6d) | Sep 28, 2025 |
| ASRock        | B450M Steel Legend          | [518241f097](https://linux-hardware.org/?probe=518241f097) | Sep 24, 2025 |
| MSI           | MEG X570 UNIFY              | [8ed7bcf178](https://linux-hardware.org/?probe=8ed7bcf178) | Sep 24, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | [ef3a971d1e](https://linux-hardware.org/?probe=ef3a971d1e) | Sep 23, 2025 |
| ASRock        | B650M-HDV/M.2               | [3c8eae06aa](https://linux-hardware.org/?probe=3c8eae06aa) | Sep 23, 2025 |
| MSI           | B450-A PRO MAX              | [09c3faca8b](https://linux-hardware.org/?probe=09c3faca8b) | Sep 21, 2025 |
| MSI           | X570-A PRO                  | [6c421014ba](https://linux-hardware.org/?probe=6c421014ba) | Sep 13, 2025 |
| ASUSTek       | PRIME X570-P                | [0ef209cdbe](https://linux-hardware.org/?probe=0ef209cdbe) | Sep 11, 2025 |
| ASRock        | B550 Steel Legend           | [64ff43de42](https://linux-hardware.org/?probe=64ff43de42) | Sep 10, 2025 |
| ASUSTek       | ROG Maximus XIII HERO       | [7e7544a889](https://linux-hardware.org/?probe=7e7544a889) | Sep 10, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | [75a32d80db](https://linux-hardware.org/?probe=75a32d80db) | Sep 06, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | [4495fafe55](https://linux-hardware.org/?probe=4495fafe55) | Sep 05, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8d64b64e12](https://linux-hardware.org/?probe=8d64b64e12) | Aug 30, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [95255bd2ff](https://linux-hardware.org/?probe=95255bd2ff) | Aug 28, 2025 |
| ASRock        | X670E Taichi                | [f38c4a921b](https://linux-hardware.org/?probe=f38c4a921b) | Aug 26, 2025 |
| ASRock        | X670E Taichi                | [3ed0f55fed](https://linux-hardware.org/?probe=3ed0f55fed) | Aug 26, 2025 |
| MSI           | B450 TOMAHAWK MAX           | [b7db5ee669](https://linux-hardware.org/?probe=b7db5ee669) | Aug 23, 2025 |
| MSI           | H110M PRO-VH                | [e23386359a](https://linux-hardware.org/?probe=e23386359a) | Aug 19, 2025 |
| MSI           | PRO A620M-E                 | [5fa1bb3645](https://linux-hardware.org/?probe=5fa1bb3645) | Aug 16, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [bee7322ddf](https://linux-hardware.org/?probe=bee7322ddf) | Aug 14, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [17f458f35e](https://linux-hardware.org/?probe=17f458f35e) | Aug 14, 2025 |
| MSI           | MAG X870E TOMAHAWK WIFI     | [fa5146c4a9](https://linux-hardware.org/?probe=fa5146c4a9) | Aug 08, 2025 |
| ASUSTek       | ROG Maximus XII FORMULA     | [f9c9c6be0a](https://linux-hardware.org/?probe=f9c9c6be0a) | Aug 06, 2025 |
| Dell          | 0VHWTR A02                  | [6859268e4e](https://linux-hardware.org/?probe=6859268e4e) | Aug 02, 2025 |
| ASUSTek       | B85-PLUS                    | [ac15c6c9bc](https://linux-hardware.org/?probe=ac15c6c9bc) | Jul 23, 2025 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [70f66ccba5](https://linux-hardware.org/?probe=70f66ccba5) | Jul 22, 2025 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [10eb6cca09](https://linux-hardware.org/?probe=10eb6cca09) | Jul 22, 2025 |
| GEEKOM        | A6                          | [a23baa592b](https://linux-hardware.org/?probe=a23baa592b) | Jul 21, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [afffec8d2e](https://linux-hardware.org/?probe=afffec8d2e) | Jul 19, 2025 |
| MSI           | Z390-A PRO                  | [9d16d99c79](https://linux-hardware.org/?probe=9d16d99c79) | Jul 19, 2025 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ac68d184a8](https://linux-hardware.org/?probe=ac68d184a8) | Jul 18, 2025 |
| MSI           | X570-A PRO                  | [a3995d869c](https://linux-hardware.org/?probe=a3995d869c) | Jul 18, 2025 |
| Gigabyte      | B250M-DS3H-CF               | [20a8ec52a1](https://linux-hardware.org/?probe=20a8ec52a1) | Jul 17, 2025 |
| ASRock        | B550M-HDV                   | [4c72b96700](https://linux-hardware.org/?probe=4c72b96700) | Jul 10, 2025 |
| ASUSTek       | PRIME X570-P                | [ab817e3483](https://linux-hardware.org/?probe=ab817e3483) | Jul 10, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [a192022aa7](https://linux-hardware.org/?probe=a192022aa7) | Jul 08, 2025 |
| ASRock        | B550M-HDV                   | [2a5646ee56](https://linux-hardware.org/?probe=2a5646ee56) | Jul 05, 2025 |
| MSI           | MPG B650I EDGE WIFI         | [143eeb226d](https://linux-hardware.org/?probe=143eeb226d) | Jul 04, 2025 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6a94d5a715](https://linux-hardware.org/?probe=6a94d5a715) | Jul 03, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [4d63f0af3a](https://linux-hardware.org/?probe=4d63f0af3a) | Jul 02, 2025 |
| Lenovo        | 36EF SDK0J40709 WIN 3259... | [97e11f9b51](https://linux-hardware.org/?probe=97e11f9b51) | Jun 26, 2025 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [bb5d2dca1a](https://linux-hardware.org/?probe=bb5d2dca1a) | Jun 22, 2025 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [49ca453d97](https://linux-hardware.org/?probe=49ca453d97) | Jun 19, 2025 |
| MSI           | MAG B850 TOMAHAWK MAX WI... | [5b127b3a99](https://linux-hardware.org/?probe=5b127b3a99) | Jun 19, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d81ee73dd2](https://linux-hardware.org/?probe=d81ee73dd2) | Jun 18, 2025 |
| MSI           | B850 GAMING PLUS WIFI       | [c795c71b4e](https://linux-hardware.org/?probe=c795c71b4e) | Jun 15, 2025 |
| Gigabyte      | B450M S2H V2                | [6a331a492d](https://linux-hardware.org/?probe=6a331a492d) | Jun 13, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [a54f944f23](https://linux-hardware.org/?probe=a54f944f23) | Jun 12, 2025 |
| Gigabyte      | X570S AORUS PRO AX          | [c8c9cc4291](https://linux-hardware.org/?probe=c8c9cc4291) | Jun 12, 2025 |
| ASUSTek       | PRIME X570-P                | [3df29b8507](https://linux-hardware.org/?probe=3df29b8507) | Jun 11, 2025 |
| Lenovo        | 3768 SDK0T76461 WIN 3422... | [d99b3bae9c](https://linux-hardware.org/?probe=d99b3bae9c) | Jun 10, 2025 |
| ASUSTek       | PRIME X670-P WIFI           | [bfdb165b8a](https://linux-hardware.org/?probe=bfdb165b8a) | Jun 10, 2025 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | [addc8f954c](https://linux-hardware.org/?probe=addc8f954c) | Jun 06, 2025 |
| ASUSTek       | ROG Maximus XII FORMULA     | [28cf2a444d](https://linux-hardware.org/?probe=28cf2a444d) | Jun 05, 2025 |
| ASUSTek       | Pro A620M-C                 | [4c1ed92a35](https://linux-hardware.org/?probe=4c1ed92a35) | May 26, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [ac8e0895ad](https://linux-hardware.org/?probe=ac8e0895ad) | May 24, 2025 |
| ASUSTek       | PRIME Z790-P                | [4649651dfb](https://linux-hardware.org/?probe=4649651dfb) | May 21, 2025 |
| ASUSTek       | Pro A620M-C                 | [b43838d998](https://linux-hardware.org/?probe=b43838d998) | May 15, 2025 |
| Gigabyte      | B650M AORUS ELITE AX        | [475489067d](https://linux-hardware.org/?probe=475489067d) | May 14, 2025 |
| Gigabyte      | B550 UD AC                  | [e6c73323bd](https://linux-hardware.org/?probe=e6c73323bd) | May 12, 2025 |
| MSI           | Z270 SLI                    | [a34f21ed9c](https://linux-hardware.org/?probe=a34f21ed9c) | May 10, 2025 |
| MSI           | PRO X870-P WIFI             | [5c9eca053a](https://linux-hardware.org/?probe=5c9eca053a) | May 10, 2025 |
| ASRock        | Z97 Extreme6/ac             | [57557749f9](https://linux-hardware.org/?probe=57557749f9) | May 07, 2025 |
| ASRock        | B360M Pro4                  | [11cb510adf](https://linux-hardware.org/?probe=11cb510adf) | May 04, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0803524a36](https://linux-hardware.org/?probe=0803524a36) | May 02, 2025 |
| ASRock        | B850 Steel Legend WiFi      | [34eea9cea5](https://linux-hardware.org/?probe=34eea9cea5) | Apr 26, 2025 |
| Gigabyte      | B650M AORUS ELITE AX        | [5ce8f7b552](https://linux-hardware.org/?probe=5ce8f7b552) | Apr 25, 2025 |
| Gigabyte      | B650 AORUS ELITE AX ICE     | [d20474d941](https://linux-hardware.org/?probe=d20474d941) | Apr 24, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [a4c246ec26](https://linux-hardware.org/?probe=a4c246ec26) | Apr 24, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [cce47c96d7](https://linux-hardware.org/?probe=cce47c96d7) | Apr 22, 2025 |
| ASUSTek       | Maximus VI IMPACT           | [408a5cc5f4](https://linux-hardware.org/?probe=408a5cc5f4) | Apr 22, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [3d51e0f2d6](https://linux-hardware.org/?probe=3d51e0f2d6) | Apr 20, 2025 |
| Unknown       | Unknown                     | [af9a49d6db](https://linux-hardware.org/?probe=af9a49d6db) | Apr 19, 2025 |
| MSI           | MPG Z790 CARBON WIFI        | [50ac4eace2](https://linux-hardware.org/?probe=50ac4eace2) | Apr 18, 2025 |
| ASUSTek       | Maximus VI IMPACT           | [c9f2ce5f83](https://linux-hardware.org/?probe=c9f2ce5f83) | Apr 18, 2025 |
| MSI           | MPG B650I EDGE WIFI         | [be99dc5e62](https://linux-hardware.org/?probe=be99dc5e62) | Apr 17, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1581cc4895](https://linux-hardware.org/?probe=1581cc4895) | Apr 15, 2025 |
| ASRock        | B550 Phantom Gaming-ITX/... | [31b7e3a60a](https://linux-hardware.org/?probe=31b7e3a60a) | Apr 14, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | [5a54c1755a](https://linux-hardware.org/?probe=5a54c1755a) | Apr 13, 2025 |
| ASRock        | N100M                       | [752ffaa3ef](https://linux-hardware.org/?probe=752ffaa3ef) | Apr 02, 2025 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | [64fa18486f](https://linux-hardware.org/?probe=64fa18486f) | Mar 31, 2025 |
| Gigabyte      | B650I AORUS ULTRA           | [19331963fb](https://linux-hardware.org/?probe=19331963fb) | Mar 28, 2025 |
| Unknown       | QADL03                      | [ce22d231b9](https://linux-hardware.org/?probe=ce22d231b9) | Mar 28, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [48cde9515e](https://linux-hardware.org/?probe=48cde9515e) | Mar 27, 2025 |
| ASRock        | B650E PG Riptide WiFi       | [ff3d59962a](https://linux-hardware.org/?probe=ff3d59962a) | Mar 26, 2025 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [1027e6d46a](https://linux-hardware.org/?probe=1027e6d46a) | Mar 26, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [7e550e8391](https://linux-hardware.org/?probe=7e550e8391) | Mar 24, 2025 |
| KVM           | Standard PC pc-q35-8.2      | [7f28fa2bab](https://linux-hardware.org/?probe=7f28fa2bab) | Mar 22, 2025 |
| Gigabyte      | B550M AORUS PRO-P           | [1ae374818c](https://linux-hardware.org/?probe=1ae374818c) | Mar 22, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0b7ae7e487](https://linux-hardware.org/?probe=0b7ae7e487) | Mar 20, 2025 |
| MSI           | X470 GAMING PLUS            | [eac87e9fda](https://linux-hardware.org/?probe=eac87e9fda) | Mar 18, 2025 |
| MSI           | X470 GAMING PLUS            | [60b7d59c54](https://linux-hardware.org/?probe=60b7d59c54) | Mar 18, 2025 |
| Lenovo        | 3733                        | [7355fd34e3](https://linux-hardware.org/?probe=7355fd34e3) | Mar 17, 2025 |
| ASRock        | Z790 Nova WiFi              | [4bdeba6130](https://linux-hardware.org/?probe=4bdeba6130) | Mar 15, 2025 |
| AZW           | EQ                          | [1846cfe355](https://linux-hardware.org/?probe=1846cfe355) | Mar 14, 2025 |
| AZW           | EQ                          | [d074853579](https://linux-hardware.org/?probe=d074853579) | Mar 14, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [ae2333840b](https://linux-hardware.org/?probe=ae2333840b) | Mar 13, 2025 |
| ASUSTek       | PRIME B650-PLUS             | [28ab8a7ede](https://linux-hardware.org/?probe=28ab8a7ede) | Mar 06, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | [5bbdad4c70](https://linux-hardware.org/?probe=5bbdad4c70) | Mar 05, 2025 |
| MSI           | MAG B650M MORTAR WIFI       | [b5914f98c0](https://linux-hardware.org/?probe=b5914f98c0) | Mar 04, 2025 |
| ASRock        | AB350M Pro4                 | [6162af4f4f](https://linux-hardware.org/?probe=6162af4f4f) | Feb 25, 2025 |
| ASUSTek       | PRIME B650M-A AX6 II        | [05f9ca5af4](https://linux-hardware.org/?probe=05f9ca5af4) | Feb 24, 2025 |
| GMKtec        | NucBox K6                   | [c7404d3e8a](https://linux-hardware.org/?probe=c7404d3e8a) | Feb 22, 2025 |
| ASRock        | X570 Taichi                 | [d56295c88d](https://linux-hardware.org/?probe=d56295c88d) | Feb 20, 2025 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | [e92e73e5c2](https://linux-hardware.org/?probe=e92e73e5c2) | Feb 19, 2025 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | [c021d7c409](https://linux-hardware.org/?probe=c021d7c409) | Feb 19, 2025 |
| MSI           | MAG X570S TORPEDO MAX       | [d83dbf9566](https://linux-hardware.org/?probe=d83dbf9566) | Feb 19, 2025 |
| ASUSTek       | PRIME Z890M-PLUS WIFI       | [a1e7a6a1ba](https://linux-hardware.org/?probe=a1e7a6a1ba) | Feb 16, 2025 |
| ASUSTek       | Z170M-PLUS                  | [7bbf53115a](https://linux-hardware.org/?probe=7bbf53115a) | Feb 16, 2025 |
| ASUSTek       | Z170M-PLUS                  | [a56a19f682](https://linux-hardware.org/?probe=a56a19f682) | Feb 16, 2025 |
| ASUSTek       | Z97-P                       | [38cfd8a844](https://linux-hardware.org/?probe=38cfd8a844) | Feb 15, 2025 |
| ASUSTek       | Z97-P                       | [c2854fc79e](https://linux-hardware.org/?probe=c2854fc79e) | Feb 15, 2025 |
| Unknown       | Unknown                     | [86358e670a](https://linux-hardware.org/?probe=86358e670a) | Feb 15, 2025 |
| Gigabyte      | B650M DS3H                  | [75dd0b7f14](https://linux-hardware.org/?probe=75dd0b7f14) | Feb 09, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [5a57c026a7](https://linux-hardware.org/?probe=5a57c026a7) | Feb 09, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [7255db5bbd](https://linux-hardware.org/?probe=7255db5bbd) | Feb 08, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [3ff7ae4fe4](https://linux-hardware.org/?probe=3ff7ae4fe4) | Feb 07, 2025 |
| Gigabyte      | Z390 GAMING SLI-CF          | [dc0d009524](https://linux-hardware.org/?probe=dc0d009524) | Feb 07, 2025 |
| Dell          | 0NNNCT A01                  | [b09a2db974](https://linux-hardware.org/?probe=b09a2db974) | Feb 07, 2025 |
| Gigabyte      | H81M-S2H                    | [6deeb244c5](https://linux-hardware.org/?probe=6deeb244c5) | Feb 06, 2025 |
| HP            | 82F2                        | [90f0e0fdc9](https://linux-hardware.org/?probe=90f0e0fdc9) | Feb 04, 2025 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [fa321d8a0f](https://linux-hardware.org/?probe=fa321d8a0f) | Feb 03, 2025 |
| Gigabyte      | X399 AORUS Gaming 7         | [e6b2e04ecd](https://linux-hardware.org/?probe=e6b2e04ecd) | Feb 02, 2025 |
| ASUSTek       | ROG Maximus XII FORMULA     | [2c1e65236a](https://linux-hardware.org/?probe=2c1e65236a) | Feb 02, 2025 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [2216bd7cc6](https://linux-hardware.org/?probe=2216bd7cc6) | Jan 30, 2025 |
| ASUSTek       | PRIME A320M-K               | [685afa4a21](https://linux-hardware.org/?probe=685afa4a21) | Jan 30, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [b0cb7234e5](https://linux-hardware.org/?probe=b0cb7234e5) | Jan 27, 2025 |
| ASRock        | Z790 PG-ITX/TB4             | [ae811e3040](https://linux-hardware.org/?probe=ae811e3040) | Jan 24, 2025 |
| Gigabyte      | B550I AORUS PRO AX          | [28271b6cb4](https://linux-hardware.org/?probe=28271b6cb4) | Jan 22, 2025 |
| ASRock        | Z790M-ITX WiFi              | [ba0daa2003](https://linux-hardware.org/?probe=ba0daa2003) | Jan 22, 2025 |
| Gigabyte      | B650E AORUS PRO X USB4      | [5b1075b9d0](https://linux-hardware.org/?probe=5b1075b9d0) | Jan 20, 2025 |
| AZW           | SER V1                      | [3637369fa6](https://linux-hardware.org/?probe=3637369fa6) | Jan 19, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [2a8d23e278](https://linux-hardware.org/?probe=2a8d23e278) | Jan 17, 2025 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [c9dcbe7d77](https://linux-hardware.org/?probe=c9dcbe7d77) | Jan 16, 2025 |
| Gigabyte      | B650M AORUS ELITE AX        | [d45077a1a1](https://linux-hardware.org/?probe=d45077a1a1) | Jan 16, 2025 |
| MSI           | X570-A PRO                  | [c100678ae2](https://linux-hardware.org/?probe=c100678ae2) | Jan 13, 2025 |
| Gigabyte      | B550I AORUS PRO AX          | [b0c36d9151](https://linux-hardware.org/?probe=b0c36d9151) | Jan 11, 2025 |
| MSI           | PRO X870-P WIFI             | [11590952bb](https://linux-hardware.org/?probe=11590952bb) | Jan 07, 2025 |
| MSI           | MEG X570 UNIFY              | [fc581d20c5](https://linux-hardware.org/?probe=fc581d20c5) | Jan 04, 2025 |
| Gigabyte      | B550I AORUS PRO AX          | [465d7bcabe](https://linux-hardware.org/?probe=465d7bcabe) | Jan 03, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [1ad78511fb](https://linux-hardware.org/?probe=1ad78511fb) | Jan 02, 2025 |
| Gigabyte      | GA-MA790GP-DS4H             | [ba9e4bcced](https://linux-hardware.org/?probe=ba9e4bcced) | Dec 31, 2024 |
| ASUSTek       | ROG STRIX X870-I GAMING ... | [13514b4f65](https://linux-hardware.org/?probe=13514b4f65) | Dec 27, 2024 |
| MSI           | MPG B650I EDGE WIFI         | [9f7cf29dd9](https://linux-hardware.org/?probe=9f7cf29dd9) | Dec 25, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [9c8b89e00a](https://linux-hardware.org/?probe=9c8b89e00a) | Dec 18, 2024 |
| MSI           | PRO B760-VC WIFI 7 BULK     | [624168065a](https://linux-hardware.org/?probe=624168065a) | Dec 18, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [7e6d9bed21](https://linux-hardware.org/?probe=7e6d9bed21) | Dec 16, 2024 |
| CWWK          | MINIPC-G12                  | [b7abc4972b](https://linux-hardware.org/?probe=b7abc4972b) | Dec 15, 2024 |
| CWWK          | MINIPC-G12                  | [da5ce0c723](https://linux-hardware.org/?probe=da5ce0c723) | Dec 15, 2024 |
| ASUSTek       | X99-DELUXE                  | [d27995c12e](https://linux-hardware.org/?probe=d27995c12e) | Dec 12, 2024 |
| Gigabyte      | TRX50 AERO D                | [806cbde5a6](https://linux-hardware.org/?probe=806cbde5a6) | Dec 11, 2024 |
| Gigabyte      | TRX50 AERO D                | [d4cb8b5bdb](https://linux-hardware.org/?probe=d4cb8b5bdb) | Dec 11, 2024 |
| ASRock        | B550M Steel Legend          | [6f47f74e85](https://linux-hardware.org/?probe=6f47f74e85) | Dec 07, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [a9d455e4cb](https://linux-hardware.org/?probe=a9d455e4cb) | Nov 29, 2024 |
| Unknown       | QADL03                      | [c2aaa4505e](https://linux-hardware.org/?probe=c2aaa4505e) | Nov 29, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [c602a79e72](https://linux-hardware.org/?probe=c602a79e72) | Nov 29, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [1c66e560b6](https://linux-hardware.org/?probe=1c66e560b6) | Nov 27, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [f442911c71](https://linux-hardware.org/?probe=f442911c71) | Nov 26, 2024 |
| Gigabyte      | B550M DS3H                  | [7154d27150](https://linux-hardware.org/?probe=7154d27150) | Nov 25, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | [2c0c09c053](https://linux-hardware.org/?probe=2c0c09c053) | Nov 14, 2024 |
| ASUSTek       | PRIME TRX40-PRO S           | [1497f6e734](https://linux-hardware.org/?probe=1497f6e734) | Nov 13, 2024 |
| ASUSTek       | PRIME B760M-A AX6 II        | [435b3b8915](https://linux-hardware.org/?probe=435b3b8915) | Nov 12, 2024 |
| Unknown       | QDNV01                      | [c799dc9a8c](https://linux-hardware.org/?probe=c799dc9a8c) | Nov 08, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [50f70bccb9](https://linux-hardware.org/?probe=50f70bccb9) | Nov 07, 2024 |
| Dell          | 06NWYK A00                  | [d3d8a8b29a](https://linux-hardware.org/?probe=d3d8a8b29a) | Nov 04, 2024 |
| Gigabyte      | Z390 GAMING SLI-CF          | [fe10e09e4d](https://linux-hardware.org/?probe=fe10e09e4d) | Nov 04, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [f84b68557e](https://linux-hardware.org/?probe=f84b68557e) | Nov 03, 2024 |
| ASRock        | X670E Taichi Carrara        | [bb8f80dc95](https://linux-hardware.org/?probe=bb8f80dc95) | Oct 27, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS       | [aefe5002a6](https://linux-hardware.org/?probe=aefe5002a6) | Oct 27, 2024 |
| Gigabyte      | B450 AORUS M                | [bbb7263070](https://linux-hardware.org/?probe=bbb7263070) | Oct 24, 2024 |
| ASRock        | B650I Lightning WiFi        | [c6bb27bfc6](https://linux-hardware.org/?probe=c6bb27bfc6) | Oct 22, 2024 |
| Dell          | 057FFP A00                  | [1f3c1adda1](https://linux-hardware.org/?probe=1f3c1adda1) | Oct 17, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | [d51c94d9e8](https://linux-hardware.org/?probe=d51c94d9e8) | Oct 16, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6531fb24dd](https://linux-hardware.org/?probe=6531fb24dd) | Oct 16, 2024 |
| MSI           | B450M PRO-VDH MAX           | [e4eac64915](https://linux-hardware.org/?probe=e4eac64915) | Oct 15, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | [71afcb15a1](https://linux-hardware.org/?probe=71afcb15a1) | Oct 11, 2024 |
| HP            | 802E                        | [b346ea5ea8](https://linux-hardware.org/?probe=b346ea5ea8) | Oct 06, 2024 |
| ASRock        | B650E PG-ITX WiFi           | [d23633905e](https://linux-hardware.org/?probe=d23633905e) | Oct 02, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a45b22c07c](https://linux-hardware.org/?probe=a45b22c07c) | Sep 29, 2024 |
| MSI           | B550-A PRO                  | [354adca291](https://linux-hardware.org/?probe=354adca291) | Sep 29, 2024 |
| Gigabyte      | B650 GAMING X AX            | [cb693ee232](https://linux-hardware.org/?probe=cb693ee232) | Sep 27, 2024 |
| MSI           | B550-A PRO                  | [1a953cc7cd](https://linux-hardware.org/?probe=1a953cc7cd) | Sep 27, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e18053e73e](https://linux-hardware.org/?probe=e18053e73e) | Sep 24, 2024 |
| Dell          | 0HV8FN A01                  | [c38e664bd9](https://linux-hardware.org/?probe=c38e664bd9) | Sep 24, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [6e55cb377d](https://linux-hardware.org/?probe=6e55cb377d) | Sep 22, 2024 |
| ASRock        | N100M                       | [8089f66e82](https://linux-hardware.org/?probe=8089f66e82) | Sep 21, 2024 |
| ASRock        | N100M                       | [d0230cada1](https://linux-hardware.org/?probe=d0230cada1) | Sep 21, 2024 |
| ASRock        | X670E Steel Legend          | [255badd442](https://linux-hardware.org/?probe=255badd442) | Sep 21, 2024 |
| BESSTAR Te... | UM350                       | [6c34d848f3](https://linux-hardware.org/?probe=6c34d848f3) | Sep 18, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [b752f4bbb2](https://linux-hardware.org/?probe=b752f4bbb2) | Sep 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8cbd80360d](https://linux-hardware.org/?probe=8cbd80360d) | Sep 16, 2024 |
| HP            | 8906 SMVB                   | [30ba42125a](https://linux-hardware.org/?probe=30ba42125a) | Sep 13, 2024 |
| Gigabyte      | B450M DS3H-CF               | [d93b2a5052](https://linux-hardware.org/?probe=d93b2a5052) | Sep 12, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [532287509c](https://linux-hardware.org/?probe=532287509c) | Sep 11, 2024 |
| ASRock        | X399 Taichi                 | [17d92d46bd](https://linux-hardware.org/?probe=17d92d46bd) | Sep 09, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [7fb93a9375](https://linux-hardware.org/?probe=7fb93a9375) | Sep 09, 2024 |
| Gigabyte      | B650M DS3H                  | [2f3b657d09](https://linux-hardware.org/?probe=2f3b657d09) | Sep 09, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [f1221250ec](https://linux-hardware.org/?probe=f1221250ec) | Sep 09, 2024 |
| ASUSTek       | PRIME X570-P                | [9a0e29b5dd](https://linux-hardware.org/?probe=9a0e29b5dd) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ca68fb7e5](https://linux-hardware.org/?probe=2ca68fb7e5) | Sep 09, 2024 |
| ASUSTek       | H61M-A/USB3                 | [727745c91c](https://linux-hardware.org/?probe=727745c91c) | Sep 09, 2024 |
| ASUSTek       | PRIME B550M-A               | [83ac3368b3](https://linux-hardware.org/?probe=83ac3368b3) | Sep 09, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [262a99dba5](https://linux-hardware.org/?probe=262a99dba5) | Sep 09, 2024 |
| ASUSTek       | ROG Maximus XII HERO        | [547ecee59b](https://linux-hardware.org/?probe=547ecee59b) | Sep 09, 2024 |
| ASRock        | X570M Pro4                  | [22bdc94b6c](https://linux-hardware.org/?probe=22bdc94b6c) | Sep 09, 2024 |
| ASUSTek       | PRIME X670-P                | [6d3e3c0adf](https://linux-hardware.org/?probe=6d3e3c0adf) | Sep 08, 2024 |
| Intel         | BQM5                        | [6fc656eb18](https://linux-hardware.org/?probe=6fc656eb18) | Sep 08, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [adf334ef70](https://linux-hardware.org/?probe=adf334ef70) | Sep 08, 2024 |
| ASRock        | Z690M-ITX/ax                | [ed55d6abbe](https://linux-hardware.org/?probe=ed55d6abbe) | Sep 08, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1912bfe794](https://linux-hardware.org/?probe=1912bfe794) | Sep 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ac0c806aba](https://linux-hardware.org/?probe=ac0c806aba) | Sep 08, 2024 |
| Unknown       | Unknown                     | [39176c7388](https://linux-hardware.org/?probe=39176c7388) | Sep 08, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5d92acf8a8](https://linux-hardware.org/?probe=5d92acf8a8) | Sep 08, 2024 |
| Dell          | 0NV0M7 A02                  | [f7cd26365e](https://linux-hardware.org/?probe=f7cd26365e) | Sep 08, 2024 |
| ASRock        | X570 Steel Legend           | [d9aeff6714](https://linux-hardware.org/?probe=d9aeff6714) | Sep 08, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [68aa788771](https://linux-hardware.org/?probe=68aa788771) | Sep 08, 2024 |
| MSI           | B450M PRO-M2                | [2b071d194a](https://linux-hardware.org/?probe=2b071d194a) | Sep 08, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [f8b0d632dc](https://linux-hardware.org/?probe=f8b0d632dc) | Sep 08, 2024 |
| Gigabyte      | B650M DS3H                  | [9214328551](https://linux-hardware.org/?probe=9214328551) | Sep 05, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [6f4213eab2](https://linux-hardware.org/?probe=6f4213eab2) | Sep 04, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a1cc07db50](https://linux-hardware.org/?probe=a1cc07db50) | Sep 03, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [7ca08ce5f0](https://linux-hardware.org/?probe=7ca08ce5f0) | Sep 03, 2024 |
| ASUSTek       | PRIME X570-P                | [70ddee6281](https://linux-hardware.org/?probe=70ddee6281) | Sep 02, 2024 |
| Gigabyte      | H81M-S2H                    | [d610978a5b](https://linux-hardware.org/?probe=d610978a5b) | Sep 01, 2024 |
| Gigabyte      | B560M DS3H V2               | [f0c3274e0f](https://linux-hardware.org/?probe=f0c3274e0f) | Aug 28, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [48ee3a93df](https://linux-hardware.org/?probe=48ee3a93df) | Aug 26, 2024 |
| ASRock        | X570M Pro4                  | [56a21fdc14](https://linux-hardware.org/?probe=56a21fdc14) | Aug 23, 2024 |
| ASUSTek       | PRIME X570-PRO              | [70bd40f935](https://linux-hardware.org/?probe=70bd40f935) | Aug 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ca58993e0b](https://linux-hardware.org/?probe=ca58993e0b) | Aug 18, 2024 |
| Lenovo        | ThinkCentre M81 7518C5U     | [86596e708e](https://linux-hardware.org/?probe=86596e708e) | Aug 16, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [92577f9db8](https://linux-hardware.org/?probe=92577f9db8) | Aug 09, 2024 |
| MSI           | B450M MORTAR MAX            | [e5132e0d40](https://linux-hardware.org/?probe=e5132e0d40) | Aug 02, 2024 |
| MSI           | B450M PRO-VDH MAX           | [e096f31889](https://linux-hardware.org/?probe=e096f31889) | Aug 01, 2024 |
| ASRock        | B550M Pro4                  | [8b95588367](https://linux-hardware.org/?probe=8b95588367) | Jul 29, 2024 |
| MSI           | B450M MORTAR MAX            | [8adadff9e1](https://linux-hardware.org/?probe=8adadff9e1) | Jul 28, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [31a5f645ab](https://linux-hardware.org/?probe=31a5f645ab) | Jul 27, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d222ae3b6b](https://linux-hardware.org/?probe=d222ae3b6b) | Jul 23, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | [4ee3f73fe2](https://linux-hardware.org/?probe=4ee3f73fe2) | Jul 22, 2024 |
| Dell          | 06NWYK A00                  | [694e65b0fd](https://linux-hardware.org/?probe=694e65b0fd) | Jul 20, 2024 |
| ASRock        | X570 Taichi                 | [04653db6d4](https://linux-hardware.org/?probe=04653db6d4) | Jun 24, 2024 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [b04f8ad772](https://linux-hardware.org/?probe=b04f8ad772) | Jun 24, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [84e558ae8b](https://linux-hardware.org/?probe=84e558ae8b) | Jun 19, 2024 |
| ECS           | A55F-M3                     | [a3c0b7c82c](https://linux-hardware.org/?probe=a3c0b7c82c) | Jun 12, 2024 |
| ASRock        | X570 Taichi                 | [c6b236ec91](https://linux-hardware.org/?probe=c6b236ec91) | Jun 12, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [24714ff60d](https://linux-hardware.org/?probe=24714ff60d) | Jun 08, 2024 |
| ASRock        | B450M-HDV R4.0              | [c7f4708e9a](https://linux-hardware.org/?probe=c7f4708e9a) | Jun 06, 2024 |
| ASUSTek       | PRIME H410M-E               | [a1345d5c40](https://linux-hardware.org/?probe=a1345d5c40) | Jun 06, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [d8d7c0ad38](https://linux-hardware.org/?probe=d8d7c0ad38) | May 30, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [205d0cf89e](https://linux-hardware.org/?probe=205d0cf89e) | May 27, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [1d15655bed](https://linux-hardware.org/?probe=1d15655bed) | May 24, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [ab20443ff3](https://linux-hardware.org/?probe=ab20443ff3) | May 17, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [930575c4e1](https://linux-hardware.org/?probe=930575c4e1) | May 16, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e1d8dfbde5](https://linux-hardware.org/?probe=e1d8dfbde5) | May 14, 2024 |
| Gigabyte      | X570S AORUS MASTER          | [249d632a13](https://linux-hardware.org/?probe=249d632a13) | May 13, 2024 |
| Gigabyte      | B450 AORUS M                | [b522afd531](https://linux-hardware.org/?probe=b522afd531) | May 12, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2e284b3d40](https://linux-hardware.org/?probe=2e284b3d40) | May 11, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [4648f8b379](https://linux-hardware.org/?probe=4648f8b379) | May 11, 2024 |
| Gigabyte      | B450 AORUS M                | [296accd3a3](https://linux-hardware.org/?probe=296accd3a3) | May 11, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [73060b4642](https://linux-hardware.org/?probe=73060b4642) | May 07, 2024 |
| HP            | 2B2C                        | [082d220d35](https://linux-hardware.org/?probe=082d220d35) | May 04, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [1902c0eeab](https://linux-hardware.org/?probe=1902c0eeab) | May 02, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [3146b9914d](https://linux-hardware.org/?probe=3146b9914d) | May 01, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [32d8346d26](https://linux-hardware.org/?probe=32d8346d26) | May 01, 2024 |
| MSI           | PRO Z790-P WIFI             | [836078acb2](https://linux-hardware.org/?probe=836078acb2) | Apr 29, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [7c970a2e6f](https://linux-hardware.org/?probe=7c970a2e6f) | Apr 27, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [33f2b78f07](https://linux-hardware.org/?probe=33f2b78f07) | Apr 27, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [55a3147182](https://linux-hardware.org/?probe=55a3147182) | Apr 26, 2024 |
| Unknown       | X79A                        | [c0456a0238](https://linux-hardware.org/?probe=c0456a0238) | Apr 26, 2024 |
| Jetway        | 1.0                         | [5410155063](https://linux-hardware.org/?probe=5410155063) | Apr 25, 2024 |
| MSI           | B450 GAMING PRO CARBON M... | [26f465d651](https://linux-hardware.org/?probe=26f465d651) | Apr 24, 2024 |
| Gigabyte      | Z390 GAMING SLI-CF          | [95968f8653](https://linux-hardware.org/?probe=95968f8653) | Apr 19, 2024 |
| Gigabyte      | Z790 UD                     | [098435751f](https://linux-hardware.org/?probe=098435751f) | Apr 18, 2024 |
| Gigabyte      | Z790 UD                     | [ab7e23fe7d](https://linux-hardware.org/?probe=ab7e23fe7d) | Apr 18, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [a805996b80](https://linux-hardware.org/?probe=a805996b80) | Apr 16, 2024 |
| ASRock        | B650E PG Riptide WiFi       | [edae497a7d](https://linux-hardware.org/?probe=edae497a7d) | Apr 14, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [12d5a6c723](https://linux-hardware.org/?probe=12d5a6c723) | Apr 08, 2024 |
| Gigabyte      | GA-H61TN-SI                 | [3f6b496eb7](https://linux-hardware.org/?probe=3f6b496eb7) | Apr 02, 2024 |
| HP            | 89D8 SMVB                   | [32e0d11ee9](https://linux-hardware.org/?probe=32e0d11ee9) | Apr 02, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [75613012d4](https://linux-hardware.org/?probe=75613012d4) | Mar 27, 2024 |
| MSI           | B450-A PRO MAX              | [5448e71afb](https://linux-hardware.org/?probe=5448e71afb) | Mar 23, 2024 |
| Gigabyte      | Z790 AORUS ELITE X WIFI7    | [9a507bf688](https://linux-hardware.org/?probe=9a507bf688) | Mar 23, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | [b835c572e5](https://linux-hardware.org/?probe=b835c572e5) | Mar 18, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1ceb0c75ea](https://linux-hardware.org/?probe=1ceb0c75ea) | Mar 15, 2024 |
| MSI           | B450-A PRO                  | [fcf37e125a](https://linux-hardware.org/?probe=fcf37e125a) | Mar 14, 2024 |
| Gigabyte      | GA-MA790GP-DS4H             | [9ffb06c47b](https://linux-hardware.org/?probe=9ffb06c47b) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [0772d17a95](https://linux-hardware.org/?probe=0772d17a95) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [644c52ac31](https://linux-hardware.org/?probe=644c52ac31) | Mar 13, 2024 |
| MSI           | B85M-E45                    | [6623f1bc66](https://linux-hardware.org/?probe=6623f1bc66) | Mar 12, 2024 |
| ASUSTek       | ROG Maximus XII EXTREME     | [260fb753fe](https://linux-hardware.org/?probe=260fb753fe) | Mar 11, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | [1bf5956e3f](https://linux-hardware.org/?probe=1bf5956e3f) | Mar 10, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [34bed62abf](https://linux-hardware.org/?probe=34bed62abf) | Mar 10, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [dc8badd739](https://linux-hardware.org/?probe=dc8badd739) | Mar 08, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [36f42c8be7](https://linux-hardware.org/?probe=36f42c8be7) | Mar 08, 2024 |
| MSI           | B450-A PRO                  | [ec32ffdea7](https://linux-hardware.org/?probe=ec32ffdea7) | Mar 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [2fae47ca0a](https://linux-hardware.org/?probe=2fae47ca0a) | Feb 29, 2024 |
| Gigabyte      | GA-MA790GP-DS4H             | [0bdc619992](https://linux-hardware.org/?probe=0bdc619992) | Feb 28, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7a1e61aea2](https://linux-hardware.org/?probe=7a1e61aea2) | Feb 24, 2024 |
| Win elemen... | M600                        | [706d9a6da6](https://linux-hardware.org/?probe=706d9a6da6) | Feb 15, 2024 |
| Biostar       | TZ590-BTC DUO               | [43894bcb57](https://linux-hardware.org/?probe=43894bcb57) | Feb 15, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7efa507cb3](https://linux-hardware.org/?probe=7efa507cb3) | Feb 12, 2024 |
| Gigabyte      | Z390 GAMING SLI-CF          | [fefa1b06db](https://linux-hardware.org/?probe=fefa1b06db) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9db247a049](https://linux-hardware.org/?probe=9db247a049) | Feb 08, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [696b85242c](https://linux-hardware.org/?probe=696b85242c) | Feb 03, 2024 |
| Biostar       | TZ590-BTC DUO               | [86684436da](https://linux-hardware.org/?probe=86684436da) | Jan 27, 2024 |
| Biostar       | TZ590-BTC DUO               | [68df04d154](https://linux-hardware.org/?probe=68df04d154) | Jan 27, 2024 |
| MSI           | MS-B1831                    | [45dd2bc3a1](https://linux-hardware.org/?probe=45dd2bc3a1) | Jan 25, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [6cfbe412a8](https://linux-hardware.org/?probe=6cfbe412a8) | Jan 16, 2024 |
| Gigabyte      | B650M GAMING X AX           | [655122ef53](https://linux-hardware.org/?probe=655122ef53) | Jan 14, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [268e37f04e](https://linux-hardware.org/?probe=268e37f04e) | Jan 14, 2024 |
| ASUSTek       | P8Z77-V LE                  | [929c108f73](https://linux-hardware.org/?probe=929c108f73) | Jan 13, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | [c5eb936632](https://linux-hardware.org/?probe=c5eb936632) | Jan 13, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [bdc05e8e4e](https://linux-hardware.org/?probe=bdc05e8e4e) | Jan 11, 2024 |
| MSI           | Z170A SLI                   | [e58029e4a2](https://linux-hardware.org/?probe=e58029e4a2) | Jan 08, 2024 |
| Dell          | 0FXD80 A00                  | [628772fa2d](https://linux-hardware.org/?probe=628772fa2d) | Jan 07, 2024 |
| ASUSTek       | PRIME H410M-E               | [3e11f092ef](https://linux-hardware.org/?probe=3e11f092ef) | Jan 07, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | [fb05620dfd](https://linux-hardware.org/?probe=fb05620dfd) | Jan 05, 2024 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [cfba81369c](https://linux-hardware.org/?probe=cfba81369c) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [527cc7c1d4](https://linux-hardware.org/?probe=527cc7c1d4) | Jan 05, 2024 |
| HP            | 1790                        | [e554a0f029](https://linux-hardware.org/?probe=e554a0f029) | Jan 04, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | [91b39eb7b5](https://linux-hardware.org/?probe=91b39eb7b5) | Jan 03, 2024 |
| Gigabyte      | B450 AORUS M                | [733b1e64b3](https://linux-hardware.org/?probe=733b1e64b3) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [f96513dd00](https://linux-hardware.org/?probe=f96513dd00) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c6c9c3c74e](https://linux-hardware.org/?probe=c6c9c3c74e) | Jan 01, 2024 |
| AZW           | EQ                          | [f27e8ec7a4](https://linux-hardware.org/?probe=f27e8ec7a4) | Dec 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f8483f02ab](https://linux-hardware.org/?probe=f8483f02ab) | Dec 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a953876b2c](https://linux-hardware.org/?probe=a953876b2c) | Dec 23, 2023 |
| ASRock        | X670E PG Lightning          | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| AZW           | EQ                          | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [62c4dde3a6](https://linux-hardware.org/?probe=62c4dde3a6) | Dec 07, 2023 |
| AZW           | EQ                          | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7273cc93a9](https://linux-hardware.org/?probe=7273cc93a9) | Dec 02, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [34b2b48e8c](https://linux-hardware.org/?probe=34b2b48e8c) | Nov 19, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [a263ed1c12](https://linux-hardware.org/?probe=a263ed1c12) | Nov 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [67938dee90](https://linux-hardware.org/?probe=67938dee90) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| ASUSTek       | PRIME X399-A                | [e0883e3bd0](https://linux-hardware.org/?probe=e0883e3bd0) | Nov 11, 2023 |
| Nvidia        | snc302eeh                   | [2b0a14caec](https://linux-hardware.org/?probe=2b0a14caec) | Nov 10, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d9cad8ffde](https://linux-hardware.org/?probe=d9cad8ffde) | Nov 09, 2023 |
| ASUSTek       | PRIME X570-PRO              | [1786e4735e](https://linux-hardware.org/?probe=1786e4735e) | Nov 07, 2023 |
| MSI           | X570-A PRO                  | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| HP            | 83E1                        | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| LattePanda    | Sigma                       | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| ECS           | A55F-M3                     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| Unknown       | HX90                        | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| ASUSTek       | P7H55                       | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| ASRock        | Z87 Extreme4                | [642a2f5a9b](https://linux-hardware.org/?probe=642a2f5a9b) | Oct 04, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| MSI           | Z68A-GD65                   | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| HP            | 1998                        | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| HP            | 8767 A                      | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| AZW           | EQ                          | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| ASUSTek       | Z87-EXPERT                  | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P II             | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| ASUSTek       | PRIME B350M-A               | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| MSI           | B550-A PRO                  | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| MSI           | Z77A-G43                    | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| ASRock        | Z87 Extreme4                | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Shenzhen M... | F7BFC                       | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| ASUSTek       | Z87-C                       | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| MSI           | B550-A PRO                  | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | PRIME B550M-A               | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| ASUSTek       | PRIME B550M-A               | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| ASRock        | AB350 Pro4                  | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| MSI           | MEG X570 UNIFY              | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| MSI           | MEG X570 UNIFY              | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| ASUSTek       | PRIME A520M-K               | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| ASUSTek       | PRIME X570-P                | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| ASUSTek       | P8Q77-M                     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| ASUSTek       | P8Z77-V LK                  | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | X399 SLI PLUS               | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASUSTek       | Z170-P                      | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | PRIME Z390-A                | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Gigabyte      | H97M-D3H                    | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| MSI           | X399 SLI PLUS               | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASRock        | X570 Taichi                 | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | SABERTOOTH X99              | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| ASUSTek       | Pro WS W480-ACE             | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| MSI           | MAG B550M BAZOOKA           | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| ASRock        | TRX40 Creator               | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| NixOS 25.05                      | 85       | 20.58%  |
| NixOS 24.11                      | 81       | 19.61%  |
| NixOS 24.05                      | 62       | 15.01%  |
| NixOS 25.11                      | 49       | 11.86%  |
| NixOS 23.11                      | 43       | 10.41%  |
| NixOS 23.05                      | 28       | 6.78%   |
| NixOS 26.05                      | 14       | 3.39%   |
| NixOS 22.11                      | 13       | 3.15%   |
| NixOS 22.05                      | 13       | 3.15%   |
| NixOS 21.11                      | 7        | 1.69%   |
| NixOS                            | 3        | 0.73%   |
| NixOS 21.05pre-git               | 2        | 0.48%   |
| NixOS 21.11.20210528.540dccb     | 1        | 0.24%   |
| NixOS 21.05.993.93963c27b93      | 1        | 0.24%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1        | 0.24%   |
| NixOS 21.05.20210929.ee90403     | 1        | 0.24%   |
| NixOS 21.05.20210430.c8dff32     | 1        | 0.24%   |
| NixOS 21.05.20210224.f6b5bfd     | 1        | 0.24%   |
| NixOS 21.05.1471.a7512bb64b1     | 1        | 0.24%   |
| NixOS 21.03pre246062.420f89ceb26 | 1        | 0.24%   |
| NixOS 21.03.git.b4349c13a6d      | 1        | 0.24%   |
| NixOS 21.03.20201007.420f89c     | 1        | 0.24%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1        | 0.24%   |
| NixOS 20.09pre-git               | 1        | 0.24%   |
| NixOS 20.09.git.4a361b06a93      | 1        | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| NixOS | 379      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Desktops | Percent |
|---------------|----------|---------|
| 6.6.48        | 6        | 1.36%   |
| 6.12.59       | 5        | 1.14%   |
| 6.10.6        | 5        | 1.14%   |
| 6.1.69        | 5        | 1.14%   |
| 6.1.55        | 5        | 1.14%   |
| 6.6.63        | 4        | 0.91%   |
| 6.6.46        | 4        | 0.91%   |
| 6.6.41        | 4        | 0.91%   |
| 6.6.28        | 4        | 0.91%   |
| 6.13.0        | 4        | 0.91%   |
| 6.12.33       | 4        | 0.91%   |
| 6.11.0        | 4        | 0.91%   |
| 6.10.7        | 4        | 0.91%   |
| 6.9.3         | 3        | 0.68%   |
| 6.8.9         | 3        | 0.68%   |
| 6.7.6         | 3        | 0.68%   |
| 6.6.87        | 3        | 0.68%   |
| 6.6.8         | 3        | 0.68%   |
| 6.6.71        | 3        | 0.68%   |
| 6.6.69        | 3        | 0.68%   |
| 6.6.0         | 3        | 0.68%   |
| 6.18.0        | 3        | 0.68%   |
| 6.12.57       | 3        | 0.68%   |
| 6.12.32       | 3        | 0.68%   |
| 6.12.26       | 3        | 0.68%   |
| 6.12.13       | 3        | 0.68%   |
| 6.10.7-zen1   | 3        | 0.68%   |
| 6.1.91        | 3        | 0.68%   |
| 6.1.37        | 3        | 0.68%   |
| 6.8.6         | 2        | 0.45%   |
| 6.7.6-xanmod1 | 2        | 0.45%   |
| 6.7.0         | 2        | 0.45%   |
| 6.6.80        | 2        | 0.45%   |
| 6.6.60        | 2        | 0.45%   |
| 6.6.58        | 2        | 0.45%   |
| 6.6.45        | 2        | 0.45%   |
| 6.6.43        | 2        | 0.45%   |
| 6.6.31        | 2        | 0.45%   |
| 6.6.22        | 2        | 0.45%   |
| 6.4.7         | 2        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.48  | 7        | 1.59%   |
| 6.10.7  | 7        | 1.59%   |
| 6.12.59 | 6        | 1.36%   |
| 6.11.0  | 6        | 1.36%   |
| 6.10.6  | 6        | 1.36%   |
| 6.1.55  | 6        | 1.36%   |
| 6.7.6   | 5        | 1.14%   |
| 6.1.69  | 5        | 1.14%   |
| 6.8.9   | 4        | 0.91%   |
| 6.7.0   | 4        | 0.91%   |
| 6.6.63  | 4        | 0.91%   |
| 6.6.46  | 4        | 0.91%   |
| 6.6.41  | 4        | 0.91%   |
| 6.6.28  | 4        | 0.91%   |
| 6.18.0  | 4        | 0.91%   |
| 6.17.8  | 4        | 0.91%   |
| 6.15.0  | 4        | 0.91%   |
| 6.13.1  | 4        | 0.91%   |
| 6.13.0  | 4        | 0.91%   |
| 6.12.57 | 4        | 0.91%   |
| 6.12.33 | 4        | 0.91%   |
| 6.9.3   | 3        | 0.68%   |
| 6.6.87  | 3        | 0.68%   |
| 6.6.8   | 3        | 0.68%   |
| 6.6.71  | 3        | 0.68%   |
| 6.6.69  | 3        | 0.68%   |
| 6.6.0   | 3        | 0.68%   |
| 6.17.9  | 3        | 0.68%   |
| 6.15.4  | 3        | 0.68%   |
| 6.14.0  | 3        | 0.68%   |
| 6.12.9  | 3        | 0.68%   |
| 6.12.60 | 3        | 0.68%   |
| 6.12.32 | 3        | 0.68%   |
| 6.12.26 | 3        | 0.68%   |
| 6.12.13 | 3        | 0.68%   |
| 6.10.8  | 3        | 0.68%   |
| 6.1.91  | 3        | 0.68%   |
| 6.1.37  | 3        | 0.68%   |
| 6.9.9   | 2        | 0.45%   |
| 6.8.6   | 2        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 86       | 20.14%  |
| 6.12    | 80       | 18.74%  |
| 6.1     | 48       | 11.24%  |
| 6.10    | 26       | 6.09%   |
| 5.15    | 23       | 5.39%   |
| 6.13    | 17       | 3.98%   |
| 6.7     | 15       | 3.51%   |
| 6.11    | 15       | 3.51%   |
| 6.15    | 13       | 3.04%   |
| 6.8     | 11       | 2.58%   |
| 6.17    | 11       | 2.58%   |
| 6.16    | 11       | 2.58%   |
| 6.9     | 9        | 2.11%   |
| 6.14    | 9        | 2.11%   |
| 5.10    | 9        | 2.11%   |
| 6.5     | 8        | 1.87%   |
| 6.18    | 6        | 1.41%   |
| 6.4     | 5        | 1.17%   |
| 5.4     | 5        | 1.17%   |
| 6.2     | 3        | 0.7%    |
| 5.8     | 3        | 0.7%    |
| 6.0     | 2        | 0.47%   |
| 5.18    | 2        | 0.47%   |
| 5.11    | 2        | 0.47%   |
| 6.3     | 1        | 0.23%   |
| 5.7     | 1        | 0.23%   |
| 5.19    | 1        | 0.23%   |
| 5.17    | 1        | 0.23%   |
| 5.16    | 1        | 0.23%   |
| 5.14    | 1        | 0.23%   |
| 5.13    | 1        | 0.23%   |
| 5.12    | 1        | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 379      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 99       | 25.52%  |
| Hyprland       | 66       | 17.01%  |
| GNOME          | 51       | 13.14%  |
| KDE6           | 46       | 11.86%  |
| KDE            | 34       | 8.76%   |
| KDE5           | 29       | 7.47%   |
| sway           | 19       | 4.9%    |
| XFCE           | 9        | 2.32%   |
| niri           | 6        | 1.55%   |
| X-Cinnamon     | 5        | 1.29%   |
| none+i3        | 5        | 1.29%   |
| none+awesome   | 3        | 0.77%   |
| COSMIC         | 3        | 0.77%   |
| none+xmonad    | 2        | 0.52%   |
| none+bspwm     | 2        | 0.52%   |
| xterm          | 1        | 0.26%   |
| xsession       | 1        | 0.26%   |
| X-Generic      | 1        | 0.26%   |
| start-hyprland | 1        | 0.26%   |
| Pantheon       | 1        | 0.26%   |
| none+xsession  | 1        | 0.26%   |
| none+dwm       | 1        | 0.26%   |
| MATE           | 1        | 0.26%   |
| LXQt           | 1        | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 185      | 47.44%  |
| Unknown | 107      | 27.44%  |
| X11     | 56       | 14.36%  |
| Tty     | 42       | 10.77%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| SDDM                  | 128      | 33.07%  |
| Unknown               | 111      | 28.68%  |
| GDM                   | 71       | 18.35%  |
| LightDM               | 39       | 10.08%  |
| GREETD                | 30       | 7.75%   |
| DISPLAY-MANAGER-START | 8        | 2.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 261      | 68.5%   |
| en_GB      | 35       | 9.19%   |
| Unknown    | 24       | 6.3%    |
| de_DE      | 12       | 3.15%   |
| ru_RU      | 10       | 2.62%   |
| en_CA      | 9        | 2.36%   |
| en_AU      | 8        | 2.1%    |
| en_DK      | 5        | 1.31%   |
| pt_BR      | 3        | 0.79%   |
| en_NZ      | 3        | 0.79%   |
| sv_SE      | 2        | 0.52%   |
| en_IE      | 2        | 0.52%   |
| sl_SI      | 1        | 0.26%   |
| nb_NO      | 1        | 0.26%   |
| ja_JP      | 1        | 0.26%   |
| it_IT      | 1        | 0.26%   |
| es_MX      | 1        | 0.26%   |
| en_IE.UTF8 | 1        | 0.26%   |
| de_CH      | 1        | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 344      | 90.53%  |
| BIOS | 36       | 9.47%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 222      | 58.12%  |
| Btrfs    | 91       | 23.82%  |
| Zfs      | 28       | 7.33%   |
| Tmpfs    | 20       | 5.24%   |
| Xfs      | 13       | 3.4%    |
| Bcachefs | 3        | 0.79%   |
| Unknown  | 3        | 0.79%   |
| F2fs     | 1        | 0.26%   |
| Ext2     | 1        | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 365      | 96.31%  |
| MBR     | 12       | 3.17%   |
| Unknown | 2        | 0.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 277      | 71.95%  |
| Yes       | 108      | 28.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 228      | 58.91%  |
| Yes       | 159      | 41.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 131      | 34.56%  |
| MSI                                  | 73       | 19.26%  |
| Gigabyte Technology                  | 72       | 19%     |
| ASRock                               | 45       | 11.87%  |
| Hewlett-Packard                      | 11       | 2.9%    |
| Dell                                 | 9        | 2.37%   |
| Unknown                              | 7        | 1.85%   |
| Lenovo                               | 5        | 1.32%   |
| AZW                                  | 4        | 1.06%   |
| Acer                                 | 3        | 0.79%   |
| Win element                          | 1        | 0.26%   |
| SYWZ                                 | 1        | 0.26%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.26%   |
| Packard Bell                         | 1        | 0.26%   |
| Nvidia                               | 1        | 0.26%   |
| LattePanda                           | 1        | 0.26%   |
| KVM                                  | 1        | 0.26%   |
| Jetway                               | 1        | 0.26%   |
| Intel                                | 1        | 0.26%   |
| Hardkernel                           | 1        | 0.26%   |
| GMKtec                               | 1        | 0.26%   |
| GEEKOM                               | 1        | 0.26%   |
| Fujitsu                              | 1        | 0.26%   |
| EVGA                                 | 1        | 0.26%   |
| ECS                                  | 1        | 0.26%   |
| CWWK                                 | 1        | 0.26%   |
| Biostar                              | 1        | 0.26%   |
| BESSTAR Tech                         | 1        | 0.26%   |
| Apple                                | 1        | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7C37                        | 7        | 1.85%   |
| ASUS TUF Gaming X570-PLUS          | 7        | 1.85%   |
| ASUS All Series                    | 7        | 1.85%   |
| Unknown                            | 7        | 1.85%   |
| MSI MS-7C56                        | 5        | 1.32%   |
| MSI MS-7B86                        | 5        | 1.32%   |
| Gigabyte B650M AORUS ELITE AX      | 5        | 1.32%   |
| MSI MS-7E26                        | 4        | 1.06%   |
| MSI MS-7E12                        | 4        | 1.06%   |
| Gigabyte B550I AORUS PRO AX        | 4        | 1.06%   |
| ASUS ROG STRIX X570-E GAMING       | 4        | 1.06%   |
| ASUS ROG STRIX B550-F GAMING       | 4        | 1.06%   |
| ASUS PRIME X570-P                  | 4        | 1.06%   |
| MSI MS-7C95                        | 3        | 0.79%   |
| MSI MS-7C84                        | 3        | 0.79%   |
| MSI MS-7C35                        | 3        | 0.79%   |
| Gigabyte X870I AORUS PRO ICE       | 3        | 0.79%   |
| Gigabyte B450M DS3H                | 3        | 0.79%   |
| Gigabyte B450 AORUS M              | 3        | 0.79%   |
| ASUS ROG STRIX B550-I GAMING       | 3        | 0.79%   |
| ASUS PRIME B550M-A                 | 3        | 0.79%   |
| MSI MS-7E47                        | 2        | 0.53%   |
| MSI MS-7D73                        | 2        | 0.53%   |
| MSI MS-7C91                        | 2        | 0.53%   |
| MSI MS-7B89                        | 2        | 0.53%   |
| MSI MS-7B84                        | 2        | 0.53%   |
| Gigabyte Z390 GAMING SLI           | 2        | 0.53%   |
| Gigabyte Z390 AORUS PRO WIFI       | 2        | 0.53%   |
| Gigabyte X570 AORUS ELITE          | 2        | 0.53%   |
| Gigabyte B650 AORUS ELITE AX V2    | 2        | 0.53%   |
| Gigabyte B550M AORUS ELITE         | 2        | 0.53%   |
| Gigabyte B450 I AORUS PRO WIFI     | 2        | 0.53%   |
| AZW EQ                             | 2        | 0.53%   |
| ASUS TUF Gaming B650M-E WIFI       | 2        | 0.53%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.53%   |
| ASUS ROG STRIX X570-F GAMING       | 2        | 0.53%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 2        | 0.53%   |
| ASUS ROG STRIX B650E-F GAMING WIFI | 2        | 0.53%   |
| ASUS ROG STRIX B550-A GAMING       | 2        | 0.53%   |
| ASUS ROG STRIX B450-F GAMING       | 2        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| ASUS ROG       | 44       | 11.61%  |
| ASUS PRIME     | 34       | 8.97%   |
| ASUS TUF       | 23       | 6.07%   |
| MSI MS-7C37    | 7        | 1.85%   |
| Gigabyte B650M | 7        | 1.85%   |
| ASUS All       | 7        | 1.85%   |
| Unknown        | 7        | 1.85%   |
| Gigabyte Z390  | 6        | 1.58%   |
| Gigabyte B450  | 6        | 1.58%   |
| Dell OptiPlex  | 6        | 1.58%   |
| MSI MS-7C56    | 5        | 1.32%   |
| MSI MS-7B86    | 5        | 1.32%   |
| Gigabyte X570  | 5        | 1.32%   |
| Gigabyte B450M | 5        | 1.32%   |
| ASUS Pro       | 5        | 1.32%   |
| MSI MS-7E26    | 4        | 1.06%   |
| MSI MS-7E12    | 4        | 1.06%   |
| Gigabyte B650  | 4        | 1.06%   |
| Gigabyte B550M | 4        | 1.06%   |
| Gigabyte B550I | 4        | 1.06%   |
| ASRock X670E   | 4        | 1.06%   |
| ASRock B550M   | 4        | 1.06%   |
| MSI MS-7C95    | 3        | 0.79%   |
| MSI MS-7C84    | 3        | 0.79%   |
| MSI MS-7C35    | 3        | 0.79%   |
| Lenovo Legion  | 3        | 0.79%   |
| HP Pavilion    | 3        | 0.79%   |
| HP EliteDesk   | 3        | 0.79%   |
| Gigabyte Z790  | 3        | 0.79%   |
| Gigabyte X870I | 3        | 0.79%   |
| Dell Precision | 3        | 0.79%   |
| ASUS ProArt    | 3        | 0.79%   |
| ASRock X570    | 3        | 0.79%   |
| ASRock B650E   | 3        | 0.79%   |
| ASRock B550    | 3        | 0.79%   |
| MSI MS-7E47    | 2        | 0.53%   |
| MSI MS-7D73    | 2        | 0.53%   |
| MSI MS-7C91    | 2        | 0.53%   |
| MSI MS-7B89    | 2        | 0.53%   |
| MSI MS-7B84    | 2        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 59       | 15.57%  |
| 2019 | 52       | 13.72%  |
| 2022 | 46       | 12.14%  |
| 2023 | 45       | 11.87%  |
| 2018 | 43       | 11.35%  |
| 2024 | 34       | 8.97%   |
| 2021 | 22       | 5.8%    |
| 2017 | 16       | 4.22%   |
| 2012 | 12       | 3.17%   |
| 2013 | 11       | 2.9%    |
| 2014 | 10       | 2.64%   |
| 2016 | 9        | 2.37%   |
| 2015 | 9        | 2.37%   |
| 2011 | 5        | 1.32%   |
| 2008 | 3        | 0.79%   |
| 2025 | 2        | 0.53%   |
| 2010 | 1        | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 379      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 353      | 92.41%  |
| Enabled  | 29       | 7.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 379      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 122      | 31.61%  |
| 64.01-256.0     | 116      | 30.05%  |
| 16.01-24.0      | 70       | 18.13%  |
| 24.01-32.0      | 43       | 11.14%  |
| 8.01-16.0       | 17       | 4.4%    |
| 4.01-8.0        | 12       | 3.11%   |
| More than 256.0 | 3        | 0.78%   |
| 3.01-4.0        | 3        | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 142      | 35.06%  |
| 8.01-16.0   | 85       | 20.99%  |
| 3.01-4.0    | 41       | 10.12%  |
| 2.01-3.0    | 38       | 9.38%   |
| 16.01-24.0  | 34       | 8.4%    |
| 1.01-2.0    | 29       | 7.16%   |
| 32.01-64.0  | 16       | 3.95%   |
| 24.01-32.0  | 12       | 2.96%   |
| 0.51-1.0    | 4        | 0.99%   |
| 64.01-256.0 | 3        | 0.74%   |
| 0.01-0.5    | 1        | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 126      | 31.98%  |
| 1      | 93       | 23.6%   |
| 3      | 82       | 20.81%  |
| 4      | 41       | 10.41%  |
| 5      | 24       | 6.09%   |
| 6      | 13       | 3.3%    |
| 7      | 7        | 1.78%   |
| 8      | 3        | 0.76%   |
| 23     | 1        | 0.25%   |
| 17     | 1        | 0.25%   |
| 16     | 1        | 0.25%   |
| 9      | 1        | 0.25%   |
| 0      | 1        | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 335      | 87.93%  |
| Yes       | 46       | 12.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 377      | 99.47%  |
| No        | 2        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 208      | 54.31%  |
| No        | 175      | 45.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 248      | 64.92%  |
| No        | 134      | 35.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 90       | 23.75%  |
| Germany         | 55       | 14.51%  |
| Russia          | 27       | 7.12%   |
| UK              | 20       | 5.28%   |
| Canada          | 20       | 5.28%   |
| Poland          | 12       | 3.17%   |
| Italy           | 12       | 3.17%   |
| France          | 11       | 2.9%    |
| Sweden          | 10       | 2.64%   |
| Netherlands     | 10       | 2.64%   |
| Australia       | 10       | 2.64%   |
| Brazil          | 9        | 2.37%   |
| Belgium         | 9        | 2.37%   |
| Norway          | 6        | 1.58%   |
| Czechia         | 6        | 1.58%   |
| Austria         | 6        | 1.58%   |
| Romania         | 5        | 1.32%   |
| Finland         | 5        | 1.32%   |
| Denmark         | 5        | 1.32%   |
| Hong Kong       | 4        | 1.06%   |
| Switzerland     | 3        | 0.79%   |
| Spain           | 3        | 0.79%   |
| Slovenia        | 3        | 0.79%   |
| New Zealand     | 3        | 0.79%   |
| Japan           | 3        | 0.79%   |
| Hungary         | 3        | 0.79%   |
| Ukraine         | 2        | 0.53%   |
| Turkey          | 2        | 0.53%   |
| The Netherlands | 2        | 0.53%   |
| Thailand        | 2        | 0.53%   |
| Taiwan          | 2        | 0.53%   |
| India           | 2        | 0.53%   |
| Chile           | 2        | 0.53%   |
| Sri Lanka       | 1        | 0.26%   |
| Slovakia        | 1        | 0.26%   |
| Singapore       | 1        | 0.26%   |
| Serbia          | 1        | 0.26%   |
| Saudi Arabia    | 1        | 0.26%   |
| Portugal        | 1        | 0.26%   |
| Philippines     | 1        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 9        | 2.31%   |
| Amsterdam      | 6        | 1.54%   |
| Warsaw         | 4        | 1.03%   |
| Vienna         | 4        | 1.03%   |
| Los Angeles    | 4        | 1.03%   |
| Hamburg        | 4        | 1.03%   |
| Sydney         | 3        | 0.77%   |
| St Petersburg  | 3        | 0.77%   |
| San Jose       | 3        | 0.77%   |
| Munich         | 3        | 0.77%   |
| Leipzig        | 3        | 0.77%   |
| Haarlem        | 3        | 0.77%   |
| Darmstadt      | 3        | 0.77%   |
| Budapest       | 3        | 0.77%   |
| Brno           | 3        | 0.77%   |
| Austin         | 3        | 0.77%   |
| Woodbridge     | 2        | 0.51%   |
| Wellington     | 2        | 0.51%   |
| Virginia Beach | 2        | 0.51%   |
| Troisdorf      | 2        | 0.51%   |
| Tokyo          | 2        | 0.51%   |
| Stockholm      | 2        | 0.51%   |
| Sorocaba       | 2        | 0.51%   |
| Sibiu          | 2        | 0.51%   |
| Sham Shui Po   | 2        | 0.51%   |
| Seattle        | 2        | 0.51%   |
| Schaafheim     | 2        | 0.51%   |
| Sao Paulo      | 2        | 0.51%   |
| Santa Clara    | 2        | 0.51%   |
| Salt Lake City | 2        | 0.51%   |
| Ramenskoye     | 2        | 0.51%   |
| Prague         | 2        | 0.51%   |
| Plymouth       | 2        | 0.51%   |
| Perth          | 2        | 0.51%   |
| Oulu           | 2        | 0.51%   |
| Oslo           | 2        | 0.51%   |
| Montreal       | 2        | 0.51%   |
| Melbourne      | 2        | 0.51%   |
| Marki          | 2        | 0.51%   |
| Lincoln        | 2        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 198      | 348    | 25.98%  |
| WDC                          | 101      | 196    | 13.25%  |
| Seagate                      | 78       | 128    | 10.24%  |
| Crucial                      | 51       | 67     | 6.69%   |
| Kingston                     | 38       | 53     | 4.99%   |
| SanDisk                      | 34       | 45     | 4.46%   |
| Toshiba                      | 31       | 47     | 4.07%   |
| Unknown                      | 22       | 26     | 2.89%   |
| Intel                        | 17       | 20     | 2.23%   |
| Kingston Technology Company  | 16       | 35     | 2.1%    |
| A-DATA Technology            | 14       | 17     | 1.84%   |
| Unknown                      | 11       | 16     | 1.44%   |
| Phison Electronics           | 10       | 13     | 1.31%   |
| Micron/Crucial Technology    | 10       | 11     | 1.31%   |
| Phison                       | 7        | 11     | 0.92%   |
| Micron Technology            | 7        | 7      | 0.92%   |
| HGST                         | 7        | 11     | 0.92%   |
| Corsair                      | 7        | 8      | 0.92%   |
| Team                         | 6        | 7      | 0.79%   |
| SPCC                         | 5        | 5      | 0.66%   |
| SK hynix                     | 5        | 5      | 0.66%   |
| Silicon Motion               | 5        | 5      | 0.66%   |
| Lexar                        | 5        | 8      | 0.66%   |
| Hitachi                      | 5        | 8      | 0.66%   |
| Realtek Semiconductor        | 4        | 16     | 0.52%   |
| PNY                          | 4        | 4      | 0.52%   |
| MAXIO Technology (Hangzhou)  | 4        | 6      | 0.52%   |
| Apacer                       | 4        | 7      | 0.52%   |
| T-FORCE                      | 3        | 3      | 0.39%   |
| Seagate Technology           | 3        | 3      | 0.39%   |
| KIOXIA                       | 3        | 3      | 0.39%   |
| Intenso                      | 3        | 3      | 0.39%   |
| Verbatim                     | 2        | 5      | 0.26%   |
| Transcend                    | 2        | 2      | 0.26%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.26%   |
| SABRENT                      | 2        | 2      | 0.26%   |
| Patriot                      | 2        | 3      | 0.26%   |
| OCZ                          | 2        | 2      | 0.26%   |
| Gigabyte Technology          | 2        | 2      | 0.26%   |
| ASMT                         | 2        | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 30       | 3.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 17       | 1.81%   |
| Samsung SSD 860 EVO 1TB                            | 15       | 1.6%    |
| Samsung SSD 860 EVO 500GB                          | 14       | 1.49%   |
| Samsung SSD 970 EVO Plus 1TB                       | 13       | 1.38%   |
| Samsung SSD 990 PRO 2TB                            | 12       | 1.28%   |
| Kingston SA400S37480G 480GB SSD                    | 12       | 1.28%   |
| Samsung SSD 970 EVO Plus 2TB                       | 11       | 1.17%   |
| Unknown                                            | 11       | 1.17%   |
| Unknown NVMe SSD Drive 1TB                         | 10       | 1.06%   |
| Samsung SSD 990 PRO 1TB                            | 9        | 0.96%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 8        | 0.85%   |
| Kingston Company SNV2S1000G 1TB                    | 8        | 0.85%   |
| Crucial CT1000BX500SSD1 1TB                        | 8        | 0.85%   |
| Unknown NVMe SSD Drive 2TB                         | 7        | 0.74%   |
| Samsung SSD 980 PRO 2TB                            | 7        | 0.74%   |
| Samsung SSD 980 1TB                                | 7        | 0.74%   |
| Samsung SSD 970 EVO 500GB                          | 7        | 0.74%   |
| Crucial CT500MX500SSD1 500GB                       | 7        | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                     | 6        | 0.64%   |
| Samsung SSD 980 PRO 1TB                            | 6        | 0.64%   |
| Samsung SSD 850 EVO 250GB                          | 6        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                     | 5        | 0.53%   |
| Samsung SSD 870 EVO 500GB                          | 5        | 0.53%   |
| Samsung SSD 860 QVO 1TB                            | 5        | 0.53%   |
| Samsung SSD 850 EVO 500GB                          | 5        | 0.53%   |
| Kingston SKC3000D2048G 2TB                         | 5        | 0.53%   |
| Toshiba DT01ACA100 1TB                             | 4        | 0.43%   |
| Seagate ST4000VN008-2DR166 4TB                     | 4        | 0.43%   |
| Seagate ST3000DM001-1ER166 3TB                     | 4        | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB                     | 4        | 0.43%   |
| Samsung SSD 870 EVO 2TB                            | 4        | 0.43%   |
| Samsung SSD 860 EVO 2TB                            | 4        | 0.43%   |
| Samsung SSD 860 EVO 250GB                          | 4        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 4        | 0.43%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 4        | 0.43%   |
| Kingston Company A2000 NVMe SSD 250GB              | 4        | 0.43%   |
| Kingston SA400S37960G 960GB SSD                    | 4        | 0.43%   |
| WDC WDS100T3X0C-00SJG0 1TB                         | 3        | 0.32%   |
| WDC WD40EZRZ-00GXCB0 4TB                           | 3        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 85       | 165    | 40.09%  |
| Seagate             | 76       | 124    | 35.85%  |
| Toshiba             | 28       | 40     | 13.21%  |
| HGST                | 7        | 11     | 3.3%    |
| Samsung Electronics | 5        | 5      | 2.36%   |
| Hitachi             | 5        | 8      | 2.36%   |
| Unknown             | 1        | 1      | 0.47%   |
| Synology            | 1        | 1      | 0.47%   |
| RSH-339             | 1        | 1      | 0.47%   |
| QEMU                | 1        | 1      | 0.47%   |
| ASMT                | 1        | 1      | 0.47%   |
| Apple               | 1        | 2      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 78       | 118    | 33.91%  |
| Crucial             | 36       | 48     | 15.65%  |
| Kingston            | 25       | 31     | 10.87%  |
| WDC                 | 15       | 18     | 6.52%   |
| SanDisk             | 13       | 17     | 5.65%   |
| Intel               | 8        | 11     | 3.48%   |
| A-DATA Technology   | 6        | 7      | 2.61%   |
| SPCC                | 5        | 5      | 2.17%   |
| PNY                 | 3        | 3      | 1.3%    |
| Micron Technology   | 3        | 3      | 1.3%    |
| Intenso             | 3        | 3      | 1.3%    |
| Verbatim            | 2        | 5      | 0.87%   |
| Team                | 2        | 3      | 0.87%   |
| T-FORCE             | 2        | 2      | 0.87%   |
| SK hynix            | 2        | 2      | 0.87%   |
| SABRENT             | 2        | 2      | 0.87%   |
| Patriot             | 2        | 3      | 0.87%   |
| OCZ                 | 2        | 2      | 0.87%   |
| Lexar               | 2        | 5      | 0.87%   |
| Corsair             | 2        | 2      | 0.87%   |
| Apacer              | 2        | 2      | 0.87%   |
| ZHITAI              | 1        | 1      | 0.43%   |
| WALRAM              | 1        | 1      | 0.43%   |
| Transcend           | 1        | 1      | 0.43%   |
| Toshiba             | 1        | 1      | 0.43%   |
| SD                  | 1        | 2      | 0.43%   |
| Netac               | 1        | 1      | 0.43%   |
| LITEON              | 1        | 1      | 0.43%   |
| KingSpec            | 1        | 1      | 0.43%   |
| KingFast            | 1        | 1      | 0.43%   |
| GOODRAM             | 1        | 1      | 0.43%   |
| Fanxiang            | 1        | 1      | 0.43%   |
| China               | 1        | 1      | 0.43%   |
| ASMT                | 1        | 1      | 0.43%   |
| Apple               | 1        | 2      | 0.43%   |
| Unknown             | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 295      | 525    | 45.11%  |
| SSD     | 192      | 309    | 29.36%  |
| HDD     | 165      | 360    | 25.23%  |
| Unknown | 2        | 2      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 295      | 524    | 52.68%  |
| SATA | 249      | 655    | 44.46%  |
| SAS  | 16       | 17     | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 147      | 210    | 35.68%  |
| 0.51-1.0   | 117      | 184    | 28.4%   |
| 1.01-2.0   | 57       | 88     | 13.83%  |
| 3.01-4.0   | 30       | 57     | 7.28%   |
| 4.01-10.0  | 29       | 66     | 7.04%   |
| 2.01-3.0   | 23       | 39     | 5.58%   |
| 10.01-20.0 | 9        | 25     | 2.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 91       | 23.33%  |
| 1001-2000      | 67       | 17.18%  |
| 501-1000       | 58       | 14.87%  |
| 1-20           | 55       | 14.1%   |
| 251-500        | 33       | 8.46%   |
| Unknown        | 30       | 7.69%   |
| 2001-3000      | 27       | 6.92%   |
| 101-250        | 24       | 6.15%   |
| 51-100         | 3        | 0.77%   |
| 21-50          | 2        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 82       | 20.45%  |
| 501-1000       | 53       | 13.22%  |
| 1001-2000      | 50       | 12.47%  |
| More than 3000 | 43       | 10.72%  |
| 101-250        | 42       | 10.47%  |
| 251-500        | 40       | 9.98%   |
| Unknown        | 30       | 7.48%   |
| 51-100         | 27       | 6.73%   |
| 21-50          | 20       | 4.99%   |
| 2001-3000      | 14       | 3.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| A-DATA Technology SP900 256GB SSD     | 2        | 2      | 2.78%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 1.39%   |
| WDC WD80EFZZ-68BTXN0 8TB              | 1        | 1      | 1.39%   |
| WDC WD800AAJS-00B4A0 80GB             | 1        | 1      | 1.39%   |
| WDC WD7500BPKT-00PK4T0 752GB          | 1        | 1      | 1.39%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 1.39%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1        | 1      | 1.39%   |
| WDC WD40PURX-64GVNY0 4TB              | 1        | 1      | 1.39%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 2      | 1.39%   |
| WDC WD3200BPVT-22ZEST0 320GB          | 1        | 1      | 1.39%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1        | 1      | 1.39%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 1      | 1.39%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 10     | 1.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 1.39%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 1.39%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 1.39%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 1.39%   |
| WDC WD20EARX-008FB0 2TB               | 1        | 1      | 1.39%   |
| WDC WD20EARS-22MVWB0 2TB              | 1        | 3      | 1.39%   |
| WDC WD20EARS-00MVWB0 2TB              | 1        | 1      | 1.39%   |
| WDC WD1600JS-00NCB1 160GB             | 1        | 1      | 1.39%   |
| WDC WD120EDBZ-11B1HA0 12TB            | 1        | 1      | 1.39%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1        | 1      | 1.39%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.39%   |
| WDC WD10EALX-009BA0 1TB               | 1        | 1      | 1.39%   |
| WDC WD1001FALS-403AA0 1TB             | 1        | 4      | 1.39%   |
| Transcend TS4TMTE250S 4TB             | 1        | 1      | 1.39%   |
| Toshiba MQ02ABF100 1TB                | 1        | 1      | 1.39%   |
| Toshiba MK6475GSX 640GB               | 1        | 1      | 1.39%   |
| Toshiba HDWQ140 4TB                   | 1        | 1      | 1.39%   |
| Team TM8FP6002T 2TB                   | 1        | 1      | 1.39%   |
| SK hynix HFS250G32TND-N1A2A 250GB SSD | 1        | 1      | 1.39%   |
| Seagate ST9320421ASG 320GB            | 1        | 1      | 1.39%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 1.39%   |
| Seagate ST8000VN0022-2EL112 8TB       | 1        | 1      | 1.39%   |
| Seagate ST500LX005-1CW162 500GB       | 1        | 1      | 1.39%   |
| Seagate ST4000VN008-2DR166 4TB        | 1        | 4      | 1.39%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.39%   |
| Seagate ST31500341AS 1TB              | 1        | 2      | 1.39%   |
| Seagate ST2000DX001-1CM164 2TB        | 1        | 2      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 40     | 33.33%  |
| Seagate             | 12       | 19     | 17.39%  |
| Samsung Electronics | 9        | 10     | 13.04%  |
| Intel               | 4        | 4      | 5.8%    |
| Toshiba             | 3        | 3      | 4.35%   |
| Hitachi             | 2        | 3      | 2.9%    |
| HGST                | 2        | 2      | 2.9%    |
| Crucial             | 2        | 2      | 2.9%    |
| A-DATA Technology   | 2        | 2      | 2.9%    |
| Transcend           | 1        | 1      | 1.45%   |
| Team                | 1        | 1      | 1.45%   |
| SK hynix            | 1        | 1      | 1.45%   |
| SD                  | 1        | 1      | 1.45%   |
| SanDisk             | 1        | 1      | 1.45%   |
| Micron Technology   | 1        | 1      | 1.45%   |
| Intenso             | 1        | 1      | 1.45%   |
| Corsair             | 1        | 1      | 1.45%   |
| ASMT                | 1        | 1      | 1.45%   |
| Apple               | 1        | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 39     | 51.16%  |
| Seagate             | 12       | 19     | 27.91%  |
| Toshiba             | 3        | 3      | 6.98%   |
| Hitachi             | 2        | 3      | 4.65%   |
| HGST                | 2        | 2      | 4.65%   |
| Samsung Electronics | 1        | 1      | 2.33%   |
| Apple               | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 39       | 68     | 60%     |
| SSD  | 18       | 18     | 27.69%  |
| NVMe | 8        | 9      | 12.31%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                            | Desktops | Drives | Percent |
|------------------------------------------------------------------|----------|--------|---------|
| Toshiba MG03ACA300 3TB                                           | 1        | 1      | 25%     |
| Toshiba HDWG180 8TB                                              | 1        | 4      | 25%     |
| SK hynix BC501 NVMe Solid State Drive 512GB                      | 1        | 1      | 25%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1024GB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 5      | 50%     |
| SK hynix            | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 358      | 1024   | 76.5%   |
| Malfunc  | 56       | 95     | 11.97%  |
| Detected | 50       | 70     | 10.68%  |
| Failed   | 4        | 7      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 242      | 31.19%  |
| Samsung Electronics          | 150      | 19.33%  |
| Intel                        | 133      | 17.14%  |
| SanDisk                      | 53       | 6.83%   |
| ASMedia Technology           | 37       | 4.77%   |
| Kingston Technology Company  | 29       | 3.74%   |
| Phison Electronics           | 25       | 3.22%   |
| Micron/Crucial Technology    | 22       | 2.84%   |
| MAXIO Technology (Hangzhou)  | 13       | 1.68%   |
| ADATA Technology             | 8        | 1.03%   |
| Seagate Technology           | 7        | 0.9%    |
| Realtek Semiconductor        | 7        | 0.9%    |
| Micron Technology            | 7        | 0.9%    |
| Silicon Motion               | 5        | 0.64%   |
| Toshiba America Info Systems | 4        | 0.52%   |
| Shenzhen Longsys Electronics | 4        | 0.52%   |
| INNOGRIT                     | 4        | 0.52%   |
| SK hynix                     | 3        | 0.39%   |
| LSI Logic / Symbios Logic    | 3        | 0.39%   |
| KIOXIA                       | 3        | 0.39%   |
| Solidigm                     | 2        | 0.26%   |
| Marvell Technology Group     | 2        | 0.26%   |
| Hosin Global Electronics     | 2        | 0.26%   |
| Broadcom / LSI               | 2        | 0.26%   |
| Biwin Storage Technology     | 2        | 0.26%   |
| Yangtze Memory Technologies  | 1        | 0.13%   |
| Transcend                    | 1        | 0.13%   |
| TenaFe                       | 1        | 0.13%   |
| Red Hat                      | 1        | 0.13%   |
| Nvidia                       | 1        | 0.13%   |
| Lite-On Technology           | 1        | 0.13%   |
| Corsair Memory               | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 93       | 10.84%  |
| AMD 600 Series Chipset SATA Controller                                         | 81       | 9.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 71       | 8.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 47       | 5.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38       | 4.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 35       | 4.08%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 28       | 3.26%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 28       | 3.26%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 18       | 2.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16       | 1.86%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 15       | 1.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14       | 1.63%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 11       | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 1.28%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 10       | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10       | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9        | 1.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 9        | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 9        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9        | 1.05%   |
| Phison E12 NVMe Controller                                                     | 8        | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 8        | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 7        | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                               | 7        | 0.82%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 7        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 0.82%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 0.7%    |
| Intel Alder Lake-N SATA AHCI Controller                                        | 6        | 0.7%    |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 5        | 0.58%   |
| Micron/Crucial T500 NVMe PCIe SSD                                              | 5        | 0.58%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 5        | 0.58%   |
| Intel SSD 660P Series                                                          | 5        | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 0.58%   |
| ASMedia ASM1064 Serial ATA Controller                                          | 5        | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 0.58%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 4        | 0.47%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4        | 0.47%   |
| Phison E18 PCIe4 NVMe Controller                                               | 4        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 366      | 53.28%  |
| NVMe | 295      | 42.94%  |
| RAID | 12       | 1.75%   |
| IDE  | 8        | 1.16%   |
| SAS  | 5        | 0.73%   |
| SCSI | 1        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 249      | 65.7%   |
| Intel  | 130      | 34.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 9 5950X 16-Core Processor    | 18       | 4.75%   |
| AMD Ryzen 5 3600 6-Core Processor      | 16       | 4.22%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 14       | 3.69%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 13       | 3.43%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 11       | 2.9%    |
| AMD Ryzen 9 7950X 16-Core Processor    | 10       | 2.64%   |
| AMD Ryzen 7 9800X3D 8-Core Processor   | 10       | 2.64%   |
| AMD Ryzen 7 7800X3D 8-Core Processor   | 9        | 2.37%   |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 9        | 2.37%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 7        | 1.85%   |
| AMD Ryzen 7 7700X 8-Core Processor     | 6        | 1.58%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 6        | 1.58%   |
| Intel N100                             | 5        | 1.32%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 5        | 1.32%   |
| AMD Ryzen 9 9900X 12-Core Processor    | 5        | 1.32%   |
| AMD Ryzen 9 7950X3D 16-Core Processor  | 5        | 1.32%   |
| AMD Ryzen 7 7700 8-Core Processor      | 5        | 1.32%   |
| AMD Ryzen 7 3800X 8-Core Processor     | 5        | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 5        | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 5        | 1.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 4        | 1.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 4        | 1.06%   |
| AMD Ryzen 9 9950X3D 16-Core Processor  | 4        | 1.06%   |
| AMD Ryzen 9 9950X 16-Core Processor    | 4        | 1.06%   |
| AMD Ryzen 9 7900X 12-Core Processor    | 4        | 1.06%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 4        | 1.06%   |
| Intel Core i9-14900K                   | 3        | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 0.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 3        | 0.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.79%   |
| Intel 12th Gen Core i5-12600KF         | 3        | 0.79%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 3        | 0.79%   |
| AMD Ryzen 7 9700X 8-Core Processor     | 3        | 0.79%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 3        | 0.79%   |
| AMD Ryzen 5 9600X 6-Core Processor     | 3        | 0.79%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 3        | 0.79%   |
| AMD Ryzen 5 5600 6-Core Processor      | 3        | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 0.79%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 3        | 0.79%   |
| AMD FX-8320 Eight-Core Processor       | 3        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 7            | 80       | 21.11%  |
| AMD Ryzen 9            | 79       | 20.84%  |
| AMD Ryzen 5            | 67       | 17.68%  |
| Intel Core i7          | 38       | 10.03%  |
| Intel Core i5          | 30       | 7.92%   |
| Other                  | 28       | 7.39%   |
| Intel Core i9          | 15       | 3.96%   |
| AMD Ryzen Threadripper | 11       | 2.9%    |
| Intel Xeon             | 7        | 1.85%   |
| Intel Celeron          | 5        | 1.32%   |
| AMD FX                 | 4        | 1.06%   |
| Intel Core i3          | 3        | 0.79%   |
| AMD Ryzen 3            | 2        | 0.53%   |
| Intel Pentium D        | 1        | 0.26%   |
| Intel Genuine          | 1        | 0.26%   |
| Intel Core             | 1        | 0.26%   |
| Intel Atom             | 1        | 0.26%   |
| AMD Ryzen 7 PRO        | 1        | 0.26%   |
| AMD EPYC               | 1        | 0.26%   |
| AMD E1                 | 1        | 0.26%   |
| AMD Athlon II X4       | 1        | 0.26%   |
| AMD Athlon 64 X2       | 1        | 0.26%   |
| AMD Athlon             | 1        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 98       | 25.86%  |
| 6      | 88       | 23.22%  |
| 4      | 65       | 17.15%  |
| 16     | 49       | 12.93%  |
| 12     | 35       | 9.23%   |
| 10     | 13       | 3.43%   |
| 24     | 11       | 2.9%    |
| 2      | 8        | 2.11%   |
| 14     | 4        | 1.06%   |
| 20     | 3        | 0.79%   |
| 64     | 2        | 0.53%   |
| 32     | 1        | 0.26%   |
| 22     | 1        | 0.26%   |
| 3      | 1        | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 378      | 99.74%  |
| 2      | 1        | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 330      | 86.84%  |
| 1      | 50       | 13.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 379      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 240      | 61.54%  |
| 0x08701021 | 12       | 3.08%   |
| 0x306a9    | 9        | 2.31%   |
| 0x0a601203 | 8        | 2.05%   |
| 0x306c3    | 7        | 1.79%   |
| 0x0a601206 | 6        | 1.54%   |
| 0x906ea    | 5        | 1.28%   |
| 0x08701013 | 5        | 1.28%   |
| 0x0800820d | 5        | 1.28%   |
| 0x0a50000d | 4        | 1.03%   |
| 0x0a20120e | 4        | 1.03%   |
| 0x0a201025 | 4        | 1.03%   |
| 0x506e3    | 3        | 0.77%   |
| 0x0a50000c | 3        | 0.77%   |
| 0x0a20120a | 3        | 0.77%   |
| 0x0a20102b | 3        | 0.77%   |
| 0x0a201016 | 3        | 0.77%   |
| 0x0a201009 | 3        | 0.77%   |
| 0x08701030 | 3        | 0.77%   |
| 0x08001138 | 3        | 0.77%   |
| 0x06000852 | 3        | 0.77%   |
| 0xb0671    | 2        | 0.51%   |
| 0xa0653    | 2        | 0.51%   |
| 0x906e9    | 2        | 0.51%   |
| 0x0b404035 | 2        | 0.51%   |
| 0x0b404023 | 2        | 0.51%   |
| 0x0a601209 | 2        | 0.51%   |
| 0x0a50000f | 2        | 0.51%   |
| 0x0a404102 | 2        | 0.51%   |
| 0x0a201204 | 2        | 0.51%   |
| 0x0830107b | 2        | 0.51%   |
| 0x0810100b | 2        | 0.51%   |
| 0x08001137 | 2        | 0.51%   |
| 0xf64      | 1        | 0.26%   |
| 0xb06e0    | 1        | 0.26%   |
| 0xb06a2    | 1        | 0.26%   |
| 0xa0655    | 1        | 0.26%   |
| 0x906ec    | 1        | 0.26%   |
| 0x90672    | 1        | 0.26%   |
| 0x806ec    | 1        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 94       | 24.74%  |
| Zen 3            | 84       | 22.11%  |
| Zen 2            | 48       | 12.63%  |
| KabyLake         | 27       | 7.11%   |
| Alderlake Hybrid | 21       | 5.53%   |
| Haswell          | 17       | 4.47%   |
| Zen+             | 12       | 3.16%   |
| Zen              | 12       | 3.16%   |
| CometLake        | 12       | 3.16%   |
| Skylake          | 11       | 2.89%   |
| IvyBridge        | 11       | 2.89%   |
| Icelake          | 5        | 1.32%   |
| Gracemont        | 5        | 1.32%   |
| SandyBridge      | 4        | 1.05%   |
| Piledriver       | 4        | 1.05%   |
| Goldmont plus    | 2        | 0.53%   |
| Broadwell        | 2        | 0.53%   |
| Tremont          | 1        | 0.26%   |
| Silvermont       | 1        | 0.26%   |
| NetBurst         | 1        | 0.26%   |
| Nehalem          | 1        | 0.26%   |
| Lunarlake Hybrid | 1        | 0.26%   |
| K8 Hammer        | 1        | 0.26%   |
| K10 Llano        | 1        | 0.26%   |
| Jaguar           | 1        | 0.26%   |
| Goldmont         | 1        | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 231      | 52.26%  |
| Nvidia            | 143      | 32.35%  |
| Intel             | 65       | 14.71%  |
| ASPEED Technology | 2        | 0.45%   |
| Red Hat           | 1        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Raphael                                                                 | 40       | 8.23%   |
| AMD Granite Ridge [Radeon Graphics]                                         | 26       | 5.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 22       | 4.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 21       | 4.32%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 20       | 4.12%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 18       | 3.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 17       | 3.5%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 15       | 3.09%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 12       | 2.47%   |
| AMD Navi 48 [Radeon RX 9070/9070 XT/9070 GRE]                               | 11       | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 1.85%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 8        | 1.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.44%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 7        | 1.44%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 7        | 1.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.23%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 1.23%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 6        | 1.23%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 6        | 1.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.03%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 1.03%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 5        | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.82%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 0.82%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 0.82%   |
| Nvidia AD104 [GeForce RTX 4070]                                             | 4        | 0.82%   |
| Nvidia AD104 [GeForce RTX 4070 SUPER]                                       | 4        | 0.82%   |
| Nvidia AD103 [GeForce RTX 4070 Ti SUPER]                                    | 4        | 0.82%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 4        | 0.82%   |
| Intel DG2 [Arc A380]                                                        | 4        | 0.82%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 4        | 0.82%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4        | 0.82%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 4        | 0.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.62%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x AMD              | 153      | 39.95%  |
| 1 x Nvidia           | 91       | 23.76%  |
| 1 x Intel            | 37       | 9.66%   |
| 2 x AMD              | 36       | 9.4%    |
| AMD + Nvidia         | 31       | 8.09%   |
| Intel + Nvidia       | 15       | 3.92%   |
| Intel + AMD          | 11       | 2.87%   |
| 2 x Nvidia           | 3        | 0.78%   |
| Other                | 1        | 0.26%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.26%   |
| 1 x Red Hat          | 1        | 0.26%   |
| Nvidia + ASPEED      | 1        | 0.26%   |
| Intel + 2 x AMD      | 1        | 0.26%   |
| 1 x ASPEED           | 1        | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 266      | 69.63%  |
| Proprietary | 94       | 24.61%  |
| Unknown     | 22       | 5.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 168      | 43.41%  |
| 8.01-16.0  | 68       | 17.57%  |
| 7.01-8.0   | 61       | 15.76%  |
| 0.01-0.5   | 34       | 8.79%   |
| 1.01-2.0   | 20       | 5.17%   |
| 16.01-24.0 | 18       | 4.65%   |
| 3.01-4.0   | 9        | 2.33%   |
| 5.01-6.0   | 4        | 1.03%   |
| 0.51-1.0   | 4        | 1.03%   |
| 2.01-3.0   | 1        | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 77       | 16.78%  |
| Dell                 | 64       | 13.94%  |
| Samsung Electronics  | 47       | 10.24%  |
| Acer                 | 36       | 7.84%   |
| ASUSTek Computer     | 27       | 5.88%   |
| AOC                  | 25       | 5.45%   |
| Ancor Communications | 22       | 4.79%   |
| BenQ                 | 19       | 4.14%   |
| Gigabyte Technology  | 17       | 3.7%    |
| Hewlett-Packard      | 15       | 3.27%   |
| MSI                  | 12       | 2.61%   |
| Philips              | 11       | 2.4%    |
| Lenovo               | 9        | 1.96%   |
| Iiyama               | 9        | 1.96%   |
| ViewSonic            | 8        | 1.74%   |
| Unknown              | 5        | 1.09%   |
| Sceptre Tech         | 4        | 0.87%   |
| Pixio                | 3        | 0.65%   |
| Mi                   | 3        | 0.65%   |
| Vizio                | 2        | 0.44%   |
| VCS                  | 2        | 0.44%   |
| Toshiba              | 2        | 0.44%   |
| Sony                 | 2        | 0.44%   |
| Huion                | 2        | 0.44%   |
| HUAWEI               | 2        | 0.44%   |
| HKC                  | 2        | 0.44%   |
| Hitachi              | 2        | 0.44%   |
| Eizo                 | 2        | 0.44%   |
| DENON                | 2        | 0.44%   |
| Wacom                | 1        | 0.22%   |
| VIZTA                | 1        | 0.22%   |
| Vestel Elektronik    | 1        | 0.22%   |
| Valve                | 1        | 0.22%   |
| Unknown (AAA)        | 1        | 0.22%   |
| TCL                  | 1        | 0.22%   |
| STD                  | 1        | 0.22%   |
| SKG                  | 1        | 0.22%   |
| SGT                  | 1        | 0.22%   |
| SAC                  | 1        | 0.22%   |
| RTK                  | 1        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 8        | 1.63%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 5        | 1.02%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 5        | 1.02%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 4        | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4        | 0.81%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 4        | 0.81%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 4        | 0.81%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                     | 4        | 0.81%   |
| Goldstar HDR WQHD GSM772E 3440x1440 800x335mm 34.1-inch                 | 3        | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 0.61%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch          | 3        | 0.61%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 3        | 0.61%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 3        | 0.61%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                      | 3        | 0.61%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch   | 3        | 0.61%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch  | 3        | 0.61%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 2        | 0.41%   |
| VCS Connector VCS1145 1920x1080 575x323mm 26.0-inch                     | 2        | 0.41%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 2        | 0.41%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 0.41%   |
| Samsung Electronics Odyssey G85SB SAM72F2 3440x1440 809x354mm 34.8-inch | 2        | 0.41%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 2        | 0.41%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch      | 2        | 0.41%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 597x336mm 27.0-inch      | 2        | 0.41%   |
| Philips PHL BDM4065 PHL08E1 3840x2160 878x485mm 39.5-inch               | 2        | 0.41%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 2        | 0.41%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                          | 2        | 0.41%   |
| Huion Kamvas Pro 16 HAT1560 1920x1080 345x195mm 15.6-inch               | 2        | 0.41%   |
| Goldstar ULTRAGEAR GSM774B 3440x1440 800x335mm 34.1-inch                | 2        | 0.41%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch                | 2        | 0.41%   |
| Goldstar SDQHD GSM5BF5 2560x2880 465x523mm 27.6-inch                    | 2        | 0.41%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                      | 2        | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch             | 2        | 0.41%   |
| Goldstar LG ULTRAGEAR GSM5B73 1920x1080 530x300mm 24.0-inch             | 2        | 0.41%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch                 | 2        | 0.41%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch                  | 2        | 0.41%   |
| Gigabyte Technology M32QC GBT3205 2560x1440 697x392mm 31.5-inch         | 2        | 0.41%   |
| Gigabyte Technology M28U GBT2800 3840x2160 697x392mm 31.5-inch          | 2        | 0.41%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                       | 2        | 0.41%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                       | 2        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 146      | 34.27%  |
| 2560x1440 (QHD)    | 95       | 22.3%   |
| 3840x2160 (4K)     | 92       | 21.6%   |
| 3440x1440          | 33       | 7.75%   |
| 1280x1024 (SXGA)   | 10       | 2.35%   |
| 2560x1080          | 8        | 1.88%   |
| 1920x1200 (WUXGA)  | 7        | 1.64%   |
| 2288x1287          | 5        | 1.17%   |
| 3840x1600          | 4        | 0.94%   |
| 3840x1080          | 4        | 0.94%   |
| 3840x2560          | 3        | 0.7%    |
| 1600x900 (HD+)     | 3        | 0.7%    |
| 2560x2880          | 2        | 0.47%   |
| 1680x1050 (WSXGA+) | 2        | 0.47%   |
| 1600x1200          | 2        | 0.47%   |
| 1366x768 (WXGA)    | 2        | 0.47%   |
| 1360x768           | 2        | 0.47%   |
| 2560x1397          | 1        | 0.23%   |
| 2160x1200          | 1        | 0.23%   |
| 1920x2160          | 1        | 0.23%   |
| 1280x800 (WXGA)    | 1        | 0.23%   |
| 1280x720 (HD)      | 1        | 0.23%   |
| Unknown            | 1        | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 135      | 29.87%  |
| 24      | 61       | 13.5%   |
| 23      | 48       | 10.62%  |
| 31      | 43       | 9.51%   |
| 34      | 41       | 9.07%   |
| 21      | 19       | 4.2%    |
| 26      | 10       | 2.21%   |
| 19      | 9        | 1.99%   |
| 32      | 7        | 1.55%   |
| 28      | 7        | 1.55%   |
| 25      | 7        | 1.55%   |
| 84      | 6        | 1.33%   |
| 20      | 6        | 1.33%   |
| Unknown | 6        | 1.33%   |
| 142     | 5        | 1.11%   |
| 72      | 5        | 1.11%   |
| 37      | 4        | 0.88%   |
| 35      | 4        | 0.88%   |
| 15      | 4        | 0.88%   |
| 54      | 3        | 0.66%   |
| 48      | 3        | 0.66%   |
| 40      | 3        | 0.66%   |
| 39      | 3        | 0.66%   |
| 17      | 2        | 0.44%   |
| 85      | 1        | 0.22%   |
| 74      | 1        | 0.22%   |
| 63      | 1        | 0.22%   |
| 49      | 1        | 0.22%   |
| 38      | 1        | 0.22%   |
| 36      | 1        | 0.22%   |
| 29      | 1        | 0.22%   |
| 22      | 1        | 0.22%   |
| 18      | 1        | 0.22%   |
| 14      | 1        | 0.22%   |
| 12      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 223      | 52.35%  |
| 601-700        | 62       | 14.55%  |
| 701-800        | 45       | 10.56%  |
| 401-500        | 30       | 7.04%   |
| 801-900        | 17       | 3.99%   |
| 1501-2000      | 13       | 3.05%   |
| 351-400        | 8        | 1.88%   |
| 1001-1500      | 8        | 1.88%   |
| 301-350        | 6        | 1.41%   |
| Unknown        | 6        | 1.41%   |
| More than 2000 | 5        | 1.17%   |
| 201-300        | 2        | 0.47%   |
| 901-1000       | 1        | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 282      | 73.82%  |
| 21/9    | 48       | 12.57%  |
| 16/10   | 22       | 5.76%   |
| 5/4     | 9        | 2.36%   |
| 1.00    | 6        | 1.57%   |
| 32/9    | 4        | 1.05%   |
| 3/2     | 3        | 0.79%   |
| 0.89    | 3        | 0.79%   |
| 4/3     | 2        | 0.52%   |
| 6/5     | 1        | 0.26%   |
| 2.01    | 1        | 0.26%   |
| Unknown | 1        | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 140      | 32.04%  |
| 201-250        | 103      | 23.57%  |
| 351-500        | 96       | 21.97%  |
| 251-300        | 27       | 6.18%   |
| More than 1000 | 22       | 5.03%   |
| 151-200        | 18       | 4.12%   |
| 501-1000       | 16       | 3.66%   |
| Unknown        | 6        | 1.37%   |
| 101-110        | 5        | 1.14%   |
| 141-150        | 3        | 0.69%   |
| 71-80          | 1        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 198      | 47.14%  |
| 101-120 | 127      | 30.24%  |
| 121-160 | 46       | 10.95%  |
| 161-240 | 30       | 7.14%   |
| 1-50    | 13       | 3.1%    |
| Unknown | 6        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 210      | 54.26%  |
| 2     | 107      | 27.65%  |
| 0     | 45       | 11.63%  |
| 3     | 22       | 5.68%   |
| 4     | 3        | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 255      | 43.07%  |
| Intel                      | 202      | 34.12%  |
| MediaTek                   | 57       | 9.63%   |
| Aquantia                   | 19       | 3.21%   |
| Qualcomm Atheros           | 9        | 1.52%   |
| Qualcomm Technologies      | 7        | 1.18%   |
| TP-Link                    | 5        | 0.84%   |
| Broadcom                   | 5        | 0.84%   |
| Ralink Technology          | 3        | 0.51%   |
| QinHeng Electronics        | 3        | 0.51%   |
| Microsoft                  | 3        | 0.51%   |
| Ralink                     | 2        | 0.34%   |
| Google                     | 2        | 0.34%   |
| D-Link System              | 2        | 0.34%   |
| Xiaomi                     | 1        | 0.17%   |
| Texas Instruments          | 1        | 0.17%   |
| STMicroelectronics         | 1        | 0.17%   |
| Samsung Electronics        | 1        | 0.17%   |
| Oculus VR                  | 1        | 0.17%   |
| Nvidia                     | 1        | 0.17%   |
| NetGear                    | 1        | 0.17%   |
| Microchip Technology       | 1        | 0.17%   |
| Mellanox Technologies      | 1        | 0.17%   |
| Kinesis                    | 1        | 0.17%   |
| Emulex                     | 1        | 0.17%   |
| D-Link                     | 1        | 0.17%   |
| Chelsio Communications     | 1        | 0.17%   |
| Bluegiga Technologies      | 1        | 0.17%   |
| ASUSTek Computer           | 1        | 0.17%   |
| ASIX Electronics           | 1        | 0.17%   |
| American Future Technology | 1        | 0.17%   |
| Unknown                    | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 129      | 18.38%  |
| Realtek RTL8125 2.5GbE Controller                                               | 104      | 14.81%  |
| Intel I211 Gigabit Network Connection                                           | 44       | 6.27%   |
| Intel Wi-Fi 6 AX200                                                             | 36       | 5.13%   |
| Intel Ethernet Controller I225-V                                                | 36       | 5.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 27       | 3.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 20       | 2.85%   |
| Intel Ethernet Controller I226-V                                                | 14       | 1.99%   |
| Intel Ethernet Connection (7) I219-V                                            | 14       | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 13       | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 10       | 1.42%   |
| Intel Ethernet Connection (2) I219-V                                            | 9        | 1.28%   |
| Realtek RTL8126 5GbE Controller                                                 | 8        | 1.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 8        | 1.14%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]                | 7        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                                  | 7        | 1%      |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                     | 6        | 0.85%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 6        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 6        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 5        | 0.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 5        | 0.71%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 0.71%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 4        | 0.57%   |
| MediaTek MT7927 802.11be 320MHz 2x2 PCIe Wireless Network Adapter [Filogic 380] | 4        | 0.57%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 4        | 0.57%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 4        | 0.57%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 4        | 0.57%   |
| Intel Wireless 7265                                                             | 4        | 0.57%   |
| Intel Ethernet Connection I217-V                                                | 4        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                            | 4        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 4        | 0.57%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 4        | 0.57%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter                        | 3        | 0.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 3        | 0.43%   |
| QinHeng 800 Z-Wave Stick                                                        | 3        | 0.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                | 3        | 0.43%   |
| Intel Alder Lake-N PCH CNVi WiFi                                                | 3        | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                            | 3        | 0.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 3        | 0.43%   |
| Aquantia AQtion AQC113 NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 104      | 49.52%  |
| MediaTek              | 50       | 23.81%  |
| Realtek Semiconductor | 28       | 13.33%  |
| TP-Link               | 5        | 2.38%   |
| Qualcomm Atheros      | 5        | 2.38%   |
| Broadcom              | 4        | 1.9%    |
| Ralink Technology     | 3        | 1.43%   |
| Microsoft             | 3        | 1.43%   |
| Ralink                | 2        | 0.95%   |
| Qualcomm Technologies | 2        | 0.95%   |
| NetGear               | 1        | 0.48%   |
| D-Link System         | 1        | 0.48%   |
| D-Link                | 1        | 0.48%   |
| ASUSTek Computer      | 1        | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                             | 36       | 17.14%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 26       | 12.38%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 20       | 9.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 10       | 4.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 8        | 3.81%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 7        | 3.33%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                     | 6        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 6        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 5        | 2.38%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 4        | 1.9%    |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 4        | 1.9%    |
| Intel Wireless 7265                                                             | 4        | 1.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 4        | 1.9%    |
| Intel 700 Series Chipset CNVi WiFi                                              | 4        | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 3        | 1.43%   |
| Intel Alder Lake-N PCH CNVi WiFi                                                | 3        | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                    | 3        | 1.43%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                             | 2        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                              | 2        | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 2        | 0.95%   |
| Realtek RTL8851BE PCIe 802.11ax Wireless Network Controller                     | 2        | 0.95%   |
| Realtek 802.11ac NIC                                                            | 2        | 0.95%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]                | 2        | 0.95%   |
| Microsoft Xbox 360 Wireless Adapter                                             | 2        | 0.95%   |
| MediaTek MT7927 802.11be 320MHz 2x2 PCIe Wireless Network Adapter [Filogic 380] | 2        | 0.95%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 2        | 0.95%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                                          | 2        | 0.95%   |
| Intel Wireless 8265 / 8275                                                      | 2        | 0.95%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 2        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                | 2        | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                     | 1        | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                      | 1        | 0.48%   |
| TP-Link 802.11ac NIC                                                            | 1        | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 1        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                 | 1        | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                         | 1        | 0.48%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                        | 1        | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                      | 1        | 0.48%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                          | 1        | 0.48%   |
| Ralink RT5572 Wireless Adapter                                                  | 1        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 251      | 55.78%  |
| Intel                  | 155      | 34.44%  |
| Aquantia               | 19       | 4.22%   |
| Qualcomm Technologies  | 5        | 1.11%   |
| Qualcomm Atheros       | 4        | 0.89%   |
| MediaTek               | 3        | 0.67%   |
| Google                 | 2        | 0.44%   |
| Broadcom               | 2        | 0.44%   |
| Xiaomi                 | 1        | 0.22%   |
| Samsung Electronics    | 1        | 0.22%   |
| Nvidia                 | 1        | 0.22%   |
| Mellanox Technologies  | 1        | 0.22%   |
| Emulex                 | 1        | 0.22%   |
| D-Link System          | 1        | 0.22%   |
| Chelsio Communications | 1        | 0.22%   |
| ASIX Electronics       | 1        | 0.22%   |
| Unknown                | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 129      | 26.99%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 104      | 21.76%  |
| Intel I211 Gigabit Network Connection                                             | 44       | 9.21%   |
| Intel Ethernet Controller I225-V                                                  | 36       | 7.53%   |
| Intel Ethernet Controller I226-V                                                  | 14       | 2.93%   |
| Intel Ethernet Connection (7) I219-V                                              | 14       | 2.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 13       | 2.72%   |
| Intel Ethernet Connection (2) I219-V                                              | 9        | 1.88%   |
| Realtek RTL8126 5GbE Controller                                                   | 8        | 1.67%   |
| Realtek Killer E3000 2.5GbE Controller                                            | 6        | 1.26%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]                  | 5        | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 5        | 1.05%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 5        | 1.05%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 4        | 0.84%   |
| Intel Ethernet Connection I217-V                                                  | 4        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                              | 4        | 0.84%   |
| Realtek RTL8922AE 802.11be PCIe Wireless Network Adapter                          | 3        | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                              | 3        | 0.63%   |
| Aquantia AQtion AQC113 NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]     | 3        | 0.63%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 3        | 0.63%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                 | 3        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 2        | 0.42%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360]   | 2        | 0.42%   |
| Intel Ethernet Controller I225-LM                                                 | 2        | 0.42%   |
| Intel Ethernet Connection I217-LM                                                 | 2        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                             | 2        | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 0.42%   |
| Intel Ethernet Connection (17) I219-V                                             | 2        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                             | 2        | 0.42%   |
| Intel 82599 10 Gigabit Network Connection                                         | 2        | 0.42%   |
| Intel 82576 Gigabit Network Connection                                            | 2        | 0.42%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 2        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 1        | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 1        | 0.21%   |
| Realtek USB 10/100/1G/2.5 LAN                                                     | 1        | 0.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                             | 1        | 0.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 1        | 0.21%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 1        | 0.21%   |
| Nvidia MCP55 Ethernet                                                             | 1        | 0.21%   |
| Mellanox MT27500 Family [ConnectX-3]                                              | 1        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 377      | 63.26%  |
| WiFi     | 205      | 34.4%   |
| Modem    | 10       | 1.68%   |
| Unknown  | 4        | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 305      | 78.61%  |
| WiFi     | 83       | 21.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 174      | 45.43%  |
| 1     | 148      | 38.64%  |
| 3     | 46       | 12.01%  |
| 4     | 6        | 1.57%   |
| 5     | 4        | 1.04%   |
| 6     | 2        | 0.52%   |
| 0     | 2        | 0.52%   |
| 9     | 1        | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 252      | 65.45%  |
| Yes  | 133      | 34.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 100      | 38.61%  |
| Cambridge Silicon Radio  | 34       | 13.13%  |
| MediaTek                 | 30       | 11.58%  |
| Foxconn / Hon Hai        | 24       | 9.27%   |
| Realtek Semiconductor    | 23       | 8.88%   |
| IMC Networks             | 16       | 6.18%   |
| ASUSTek Computer         | 14       | 5.41%   |
| TP-Link                  | 6        | 2.32%   |
| Broadcom                 | 6        | 2.32%   |
| SINO WEALTH              | 1        | 0.39%   |
| Lite-On Technology       | 1        | 0.39%   |
| HTC (High Tech Computer) | 1        | 0.39%   |
| Belkin Components        | 1        | 0.39%   |
| Apple                    | 1        | 0.39%   |
| Unknown                  | 1        | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 34       | 13.13%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 34       | 13.13%  |
| MediaTek Wireless_Device                                             | 30       | 11.58%  |
| Realtek Bluetooth Radio                                              | 21       | 8.11%   |
| Intel AX210 Bluetooth                                                | 18       | 6.95%   |
| Intel AX201 Bluetooth                                                | 14       | 5.41%   |
| Foxconn / Hon Hai Wireless_Device                                    | 12       | 4.63%   |
| IMC Networks Wireless_Device                                         | 11       | 4.25%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 10       | 3.86%   |
| Intel Bluetooth wireless interface                                   | 8        | 3.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 7        | 2.7%    |
| Intel Bluetooth Device                                               | 7        | 2.7%    |
| ASUS ASUS USB-BT500                                                  | 7        | 2.7%    |
| TP-Link TP-T@- UB500 Adapter                                         | 6        | 2.32%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 6        | 2.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 6        | 2.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6        | 2.32%   |
| IMC Networks Bluetooth Radio                                         | 4        | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3        | 1.16%   |
| SINO WEALTH Bluetooth Keyboard                                       | 1        | 0.39%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.39%   |
| Realtek Bluetooth 5.4 Radio                                          | 1        | 0.39%   |
| Lite-On Wireless_Device                                              | 1        | 0.39%   |
| IMC Networks BCM20702A0                                              | 1        | 0.39%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.39%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                          | 1        | 0.39%   |
| Foxconn / Hon Hai Bluetooth Radio                                    | 1        | 0.39%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.39%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.39%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.39%   |
| ASUS Bluetooth Device                                                | 1        | 0.39%   |
| ASUS BCM20702A0                                                      | 1        | 0.39%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.39%   |
| Unknown                                                              | 1        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 275      | 33.05%  |
| Nvidia                               | 143      | 17.19%  |
| Intel                                | 130      | 15.63%  |
| C-Media Electronics                  | 28       | 3.37%   |
| Focusrite-Novation                   | 20       | 2.4%    |
| Logitech                             | 17       | 2.04%   |
| ASUSTek Computer                     | 15       | 1.8%    |
| Texas Instruments                    | 10       | 1.2%    |
| Micro Star International             | 10       | 1.2%    |
| SteelSeries ApS                      | 9        | 1.08%   |
| Razer USA                            | 9        | 1.08%   |
| Kingston Technology                  | 9        | 1.08%   |
| RODE Microphones                     | 7        | 0.84%   |
| ASRock                               | 7        | 0.84%   |
| Thesycon Systemsoftware & Consulting | 6        | 0.72%   |
| JMTek                                | 6        | 0.72%   |
| Giga-Byte Technology                 | 6        | 0.72%   |
| Blue Microphones                     | 6        | 0.72%   |
| Sony                                 | 5        | 0.6%    |
| FiiO Electronics Technology          | 5        | 0.6%    |
| Yamaha                               | 4        | 0.48%   |
| Shure                                | 4        | 0.48%   |
| Schiit Audio                         | 4        | 0.48%   |
| GYROCOM C&C                          | 4        | 0.48%   |
| fifine Microphones                   | 4        | 0.48%   |
| Corsair                              | 4        | 0.48%   |
| Samson Technologies                  | 3        | 0.36%   |
| Medeli Electronics                   | 3        | 0.36%   |
| Jieli Technology                     | 3        | 0.36%   |
| Elgato Systems                       | 3        | 0.36%   |
| Creative Labs                        | 3        | 0.36%   |
| Unknown                              | 3        | 0.36%   |
| PreSonus Audio Electronics           | 2        | 0.24%   |
| Microsoft                            | 2        | 0.24%   |
| KTMicro                              | 2        | 0.24%   |
| DSEA A/S                             | 2        | 0.24%   |
| Creative Technology                  | 2        | 0.24%   |
| Conexant Systems                     | 2        | 0.24%   |
| Beyerdynamic                         | 2        | 0.24%   |
| Audio-Technica                       | 2        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 105      | 9.8%    |
| AMD Ryzen HD Audio Controller                                              | 96       | 8.96%   |
| AMD Radeon High Definition Audio Controller                                | 73       | 6.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 57       | 5.32%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 39       | 3.64%   |
| AMD Navi 10 HDMI Audio                                                     | 23       | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 23       | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 18       | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17       | 1.59%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 16       | 1.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 15       | 1.4%    |
| Intel Raptor Lake High Definition Audio Controller                         | 15       | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 13       | 1.21%   |
| ASUSTek Computer USB Audio                                                 | 13       | 1.21%   |
| AMD Navi 48 HDMI/DP Audio Controller                                       | 13       | 1.21%   |
| Nvidia GA104 High Definition Audio Controller                              | 12       | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 10       | 0.93%   |
| Micro Star International USB Audio                                         | 10       | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 10       | 0.93%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 0.84%   |
| Nvidia AD104 High Definition Audio Controller                              | 9        | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 0.84%   |
| Nvidia TU104 HD Audio Controller                                           | 8        | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 8        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 8        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 0.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7        | 0.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 0.65%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 7        | 0.65%   |
| ASRock USB Audio                                                           | 7        | 0.65%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 7        | 0.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 6        | 0.56%   |
| Nvidia AD102 High Definition Audio Controller                              | 6        | 0.56%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 6        | 0.56%   |
| Giga-Byte Technology USB Audio                                             | 6        | 0.56%   |
| Focusrite-Novation Scarlett 2i2 3rd Gen                                    | 6        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 102      | 25.19%  |
| G.Skill                      | 84       | 20.74%  |
| Kingston                     | 58       | 14.32%  |
| Crucial                      | 36       | 8.89%   |
| Samsung Electronics          | 20       | 4.94%   |
| Unknown                      | 14       | 3.46%   |
| A-DATA Technology            | 14       | 3.46%   |
| Unknown                      | 13       | 3.21%   |
| Team                         | 11       | 2.72%   |
| SK hynix                     | 11       | 2.72%   |
| Micron Technology            | 10       | 2.47%   |
| Patriot                      | 9        | 2.22%   |
| GOODRAM                      | 3        | 0.74%   |
| Transcend                    | 2        | 0.49%   |
| Ramaxel Technology           | 2        | 0.49%   |
| GLOWAY                       | 2        | 0.49%   |
| Wodposit                     | 1        | 0.25%   |
| Wilk                         | 1        | 0.25%   |
| Unknown (ABCD)               | 1        | 0.25%   |
| Unknown (0x0E9D)             | 1        | 0.25%   |
| Unknown (0x0CB9)             | 1        | 0.25%   |
| Timetec                      | 1        | 0.25%   |
| TeamGroup                    | 1        | 0.25%   |
| Strontium                    | 1        | 0.25%   |
| QEMU                         | 1        | 0.25%   |
| Patriot Memory (PDP Systems) | 1        | 0.25%   |
| Lexar Co Limited             | 1        | 0.25%   |
| Lenovo                       | 1        | 0.25%   |
| Colorful                     | 1        | 0.25%   |
| AMD                          | 1        | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 13       | 2.95%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s   | 8        | 1.81%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6200MT/s     | 7        | 1.59%   |
| G.Skill RAM F5-6000J3038F16G 16GB DIMM DDR5 6000MT/s     | 6        | 1.36%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 6        | 1.36%   |
| Kingston RAM KF552C40-32 32GB DIMM DDR5 5200MT/s         | 5        | 1.13%   |
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3800MT/s    | 5        | 1.13%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s   | 5        | 1.13%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s   | 5        | 1.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s    | 5        | 1.13%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 4        | 0.91%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s       | 4        | 0.91%   |
| Kingston RAM KF560C30-16 16GB DIMM DDR5 6000MT/s         | 4        | 0.91%   |
| G.Skill RAM F5-6000J3238F16G 16GB DIMM DDR5 12800MT/s    | 4        | 0.91%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 4        | 0.91%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 4        | 0.91%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s   | 4        | 0.91%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3600MT/s   | 4        | 0.91%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s     | 3        | 0.68%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3600MT/s      | 3        | 0.68%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 3        | 0.68%   |
| G.Skill RAM F4-3200C16-16GTZRX 16GB DIMM DDR4 3200MT/s   | 3        | 0.68%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3800MT/s | 3        | 0.68%   |
| Corsair RAM CMW32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s   | 3        | 0.68%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s   | 3        | 0.68%   |
| Corsair RAM CMK32GX4M2D3000C16 16GB DIMM DDR4 3200MT/s   | 3        | 0.68%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s   | 3        | 0.68%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 4000MT/s    | 3        | 0.68%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s             | 3        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 2        | 0.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s       | 2        | 0.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s     | 2        | 0.45%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 2        | 0.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 0.45%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 2        | 0.45%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s      | 2        | 0.45%   |
| Kingston RAM KF560C40-16 16GB DIMM 6000MT/s              | 2        | 0.45%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s         | 2        | 0.45%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s      | 2        | 0.45%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s    | 2        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 226      | 60.11%  |
| DDR5    | 105      | 27.93%  |
| DDR3    | 35       | 9.31%   |
| Unknown | 4        | 1.06%   |
| SDRAM   | 1        | 0.27%   |
| RAM     | 1        | 0.27%   |
| LPDDR5  | 1        | 0.27%   |
| LPDDR4  | 1        | 0.27%   |
| DRAM    | 1        | 0.27%   |
| DDR     | 1        | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 350      | 93.33%  |
| SODIMM       | 22       | 5.87%   |
| RIMM         | 2        | 0.53%   |
| Row Of Chips | 1        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 160      | 39.6%   |
| 32768 | 105      | 25.99%  |
| 8192  | 99       | 24.5%   |
| 4096  | 22       | 5.45%   |
| 49152 | 8        | 1.98%   |
| 2048  | 5        | 1.24%   |
| 65536 | 2        | 0.5%    |
| 24576 | 2        | 0.5%    |
| 4000  | 1        | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 70       | 16.91%  |
| 3200  | 67       | 16.18%  |
| 6000  | 39       | 9.42%   |
| 3800  | 25       | 6.04%   |
| 1600  | 22       | 5.31%   |
| 4800  | 17       | 4.11%   |
| 5600  | 16       | 3.86%   |
| 3733  | 16       | 3.86%   |
| 2667  | 14       | 3.38%   |
| 2133  | 14       | 3.38%   |
| 2400  | 12       | 2.9%    |
| 5200  | 11       | 2.66%   |
| 1333  | 8        | 1.93%   |
| 6400  | 7        | 1.69%   |
| 6200  | 7        | 1.69%   |
| 12800 | 6        | 1.45%   |
| 4000  | 6        | 1.45%   |
| 3866  | 6        | 1.45%   |
| 3000  | 6        | 1.45%   |
| 3400  | 4        | 0.97%   |
| 2933  | 4        | 0.97%   |
| 2666  | 4        | 0.97%   |
| 3466  | 3        | 0.72%   |
| 1866  | 3        | 0.72%   |
| 6800  | 2        | 0.48%   |
| 3933  | 2        | 0.48%   |
| 3334  | 2        | 0.48%   |
| 3333  | 2        | 0.48%   |
| 3100  | 2        | 0.48%   |
| 2800  | 2        | 0.48%   |
| 1867  | 2        | 0.48%   |
| 667   | 2        | 0.48%   |
| 8000  | 1        | 0.24%   |
| 7000  | 1        | 0.24%   |
| 5900  | 1        | 0.24%   |
| 4333  | 1        | 0.24%   |
| 2934  | 1        | 0.24%   |
| 2733  | 1        | 0.24%   |
| 2134  | 1        | 0.24%   |
| 1800  | 1        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 40%     |
| Xerox              | 1        | 20%     |
| Printer            | 1        | 20%     |
| Canon              | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Xerox Phaser 6125N        | 1        | 20%     |
| Printer Printer           | 1        | 20%     |
| Canon PIXMA MG3600 Series | 1        | 20%     |
| Brother MFC-J6530DW       | 1        | 20%     |
| Brother HL-L2300D series  | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 71       | 60.17%  |
| Microdia                      | 7        | 5.93%   |
| MacroSilicon                  | 7        | 5.93%   |
| Sunplus Innovation Technology | 6        | 5.08%   |
| Realtek Semiconductor         | 3        | 2.54%   |
| Razer USA                     | 3        | 2.54%   |
| Oculus VR                     | 2        | 1.69%   |
| Microsoft                     | 2        | 1.69%   |
| Generalplus Technology        | 2        | 1.69%   |
| Apple                         | 2        | 1.69%   |
| webcam                        | 1        | 0.85%   |
| Valve Software                | 1        | 0.85%   |
| Tobii Technology AB           | 1        | 0.85%   |
| SN0002                        | 1        | 0.85%   |
| Samsung Electronics           | 1        | 0.85%   |
| Insta360                      | 1        | 0.85%   |
| GRANDSTREAM GUV3100           | 1        | 0.85%   |
| GoPro                         | 1        | 0.85%   |
| Google                        | 1        | 0.85%   |
| AVerMedia Technologies        | 1        | 0.85%   |
| Arkmicro Technologies         | 1        | 0.85%   |
| Anker PowerConf C200          | 1        | 0.85%   |
| A4Tech                        | 1        | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech C922 Pro Stream Webcam         | 17       | 14.41%  |
| Logitech HD Pro Webcam C920             | 15       | 12.71%  |
| Logitech Webcam C270                    | 8        | 6.78%   |
| MacroSilicon USB Video                  | 6        | 5.08%   |
| Logitech C920 PRO HD Webcam             | 6        | 5.08%   |
| Logitech StreamCam                      | 5        | 4.24%   |
| Logitech BRIO Ultra HD Webcam           | 5        | 4.24%   |
| Sunplus Integrated Camera               | 3        | 2.54%   |
| Sunplus Full HD webcam                  | 2        | 1.69%   |
| Razer USA Razer Kiyo Pro                | 2        | 1.69%   |
| Oculus VR Quest 2                       | 2        | 1.69%   |
| Microsoft LifeCam Studio                | 2        | 1.69%   |
| Microdia Camera                         | 2        | 1.69%   |
| Logitech Webcam C930e                   | 2        | 1.69%   |
| Logitech Logitech Webcam C925e          | 2        | 1.69%   |
| Logitech HD Webcam C525                 | 2        | 1.69%   |
| Generalplus GENERAL WEBCAM              | 2        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 2        | 1.69%   |
| webcam webcam                           | 1        | 0.85%   |
| Valve Software 3D Camera                | 1        | 0.85%   |
| Tobii AB EyeChip                        | 1        | 0.85%   |
| Sunplus 2K FHD camera                   | 1        | 0.85%   |
| SN0002 2K USB Camera                    | 1        | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 0.85%   |
| Realtek USB Camera                      | 1        | 0.85%   |
| Realtek Thronmax Stream Go Pro Webcam   | 1        | 0.85%   |
| Realtek FULL HD 1080P Webcam            | 1        | 0.85%   |
| Razer USA Razer Kiyo X                  | 1        | 0.85%   |
| Microdia Webcam Vitade AF               | 1        | 0.85%   |
| Microdia USB Camera                     | 1        | 0.85%   |
| Microdia USB 2.0 Camera                 | 1        | 0.85%   |
| Microdia UGREEN Camera                  | 1        | 0.85%   |
| Microdia CyberTrack H7                  | 1        | 0.85%   |
| MacroSilicon UGREEN 15390               | 1        | 0.85%   |
| Logitech Webcam Pro 9000                | 1        | 0.85%   |
| Logitech Webcam C920-C                  | 1        | 0.85%   |
| Logitech Webcam C120                    | 1        | 0.85%   |
| Logitech MX Brio                        | 1        | 0.85%   |
| Logitech HD Webcam C615                 | 1        | 0.85%   |
| Logitech C930c                          | 1        | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 2        | 33.33%  |
| SCM Microsystems      | 1        | 16.67%  |
| OmniKey               | 1        | 16.67%  |
| Clay Logic            | 1        | 16.67%  |
| Advanced Card Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                        | 2        | 33.33%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 16.67%  |
| OmniKey CardMan Smart@Link                             | 1        | 16.67%  |
| Clay Logic Nitrokey HSM                                | 1        | 16.67%  |
| Advanced Card Systems ACR39U                           | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 294      | 76.36%  |
| 1     | 79       | 20.52%  |
| 2     | 10       | 2.6%    |
| 6     | 1        | 0.26%   |
| 3     | 1        | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 33%     |
| Net/wireless             | 22       | 22%     |
| Sound                    | 11       | 11%     |
| Network                  | 6        | 6%      |
| Unassigned class         | 4        | 4%      |
| Multimedia controller    | 4        | 4%      |
| Chipcard                 | 4        | 4%      |
| Camera                   | 4        | 4%      |
| Bluetooth                | 4        | 4%      |
| Net/ethernet             | 3        | 3%      |
| Communication controller | 2        | 2%      |
| Firewire controller      | 1        | 1%      |
| Fingerprint reader       | 1        | 1%      |
| Dvb card                 | 1        | 1%      |

