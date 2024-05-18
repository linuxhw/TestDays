Linux in Hungary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 4276

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 805D                        | [208bd3b9dd](https://linux-hardware.org/?probe=208bd3b9dd) | May 09, 2024 |
| Dell          | 00V62H A01                  | [2ea426bed2](https://linux-hardware.org/?probe=2ea426bed2) | May 08, 2024 |
| Dell          | 00V62H A01                  | [bc8a5150c3](https://linux-hardware.org/?probe=bc8a5150c3) | May 08, 2024 |
| Dell          | 0M858N A01                  | [9b34c8bbc2](https://linux-hardware.org/?probe=9b34c8bbc2) | May 08, 2024 |
| Lenovo        | 1036 NO DPK                 | [ea4077ed1b](https://linux-hardware.org/?probe=ea4077ed1b) | May 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [75811cd1df](https://linux-hardware.org/?probe=75811cd1df) | May 08, 2024 |
| HP            | 1495                        | [89464c1187](https://linux-hardware.org/?probe=89464c1187) | May 08, 2024 |
| ASRock        | B550M Pro4                  | [41c99b8030](https://linux-hardware.org/?probe=41c99b8030) | May 08, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [14bb67e07a](https://linux-hardware.org/?probe=14bb67e07a) | May 07, 2024 |
| ASUSTek       | H110M-A                     | [e4868e57a3](https://linux-hardware.org/?probe=e4868e57a3) | May 07, 2024 |
| ASUSTek       | PRIME A320M-R               | [8b5ef47376](https://linux-hardware.org/?probe=8b5ef47376) | May 07, 2024 |
| ASRock        | Z390 Pro4                   | [ee53393400](https://linux-hardware.org/?probe=ee53393400) | May 07, 2024 |
| ASUSTek       | H110M-K                     | [373b9bdb5c](https://linux-hardware.org/?probe=373b9bdb5c) | May 07, 2024 |
| ASUSTek       | P5K3 Deluxe                 | [b03bf61625](https://linux-hardware.org/?probe=b03bf61625) | May 07, 2024 |
| Gigabyte      | H110M-S2V-CF                | [22eb41201e](https://linux-hardware.org/?probe=22eb41201e) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [e8e1e2e2f8](https://linux-hardware.org/?probe=e8e1e2e2f8) | May 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [07a4ffe918](https://linux-hardware.org/?probe=07a4ffe918) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | [f696d03152](https://linux-hardware.org/?probe=f696d03152) | May 07, 2024 |
| Gigabyte      | A520M S2H                   | [c14a7e4724](https://linux-hardware.org/?probe=c14a7e4724) | May 07, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [ec3b3b1daa](https://linux-hardware.org/?probe=ec3b3b1daa) | May 07, 2024 |
| ASUSTek       | A88XM-E                     | [bba7d20511](https://linux-hardware.org/?probe=bba7d20511) | May 07, 2024 |
| Gigabyte      | H97M-HD3                    | [7548e25e9d](https://linux-hardware.org/?probe=7548e25e9d) | May 06, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [c23f1deec5](https://linux-hardware.org/?probe=c23f1deec5) | May 06, 2024 |
| ASRock        | 970 Extreme3                | [78a7df5736](https://linux-hardware.org/?probe=78a7df5736) | May 05, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [b1077f633d](https://linux-hardware.org/?probe=b1077f633d) | May 04, 2024 |
| HP            | 339A                        | [a5f44d3bdb](https://linux-hardware.org/?probe=a5f44d3bdb) | May 04, 2024 |
| Gigabyte      | H81M-S1                     | [b0e189e984](https://linux-hardware.org/?probe=b0e189e984) | May 03, 2024 |
| Gigabyte      | H81M-S1                     | [8bc865780b](https://linux-hardware.org/?probe=8bc865780b) | May 03, 2024 |
| HP            | 8298                        | [da2ba36ce9](https://linux-hardware.org/?probe=da2ba36ce9) | May 02, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [ff55d733a4](https://linux-hardware.org/?probe=ff55d733a4) | May 01, 2024 |
| Acer          | RS880M05                    | [bc549ed290](https://linux-hardware.org/?probe=bc549ed290) | Apr 30, 2024 |
| HP            | 0B4Ch D                     | [db2b347526](https://linux-hardware.org/?probe=db2b347526) | Apr 30, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [120693fd0b](https://linux-hardware.org/?probe=120693fd0b) | Apr 29, 2024 |
| HP            | 0B4Ch D                     | [a4057cd447](https://linux-hardware.org/?probe=a4057cd447) | Apr 28, 2024 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [1456965e8a](https://linux-hardware.org/?probe=1456965e8a) | Apr 28, 2024 |
| ASRock        | Z390 Pro4                   | [b50024c729](https://linux-hardware.org/?probe=b50024c729) | Apr 28, 2024 |
| HP            | 3029h                       | [1ae766a3ba](https://linux-hardware.org/?probe=1ae766a3ba) | Apr 28, 2024 |
| Gigabyte      | B450M GAMING                | [f81c1dea8d](https://linux-hardware.org/?probe=f81c1dea8d) | Apr 27, 2024 |
| Gigabyte      | B450M GAMING                | [0edf4e838c](https://linux-hardware.org/?probe=0edf4e838c) | Apr 27, 2024 |
| Dell          | 0D883F A06                  | [a82d507833](https://linux-hardware.org/?probe=a82d507833) | Apr 27, 2024 |
| Dell          | 0200DY A03                  | [96991fe0ba](https://linux-hardware.org/?probe=96991fe0ba) | Apr 27, 2024 |
| ASUSTek       | A88XM-E                     | [96107974e8](https://linux-hardware.org/?probe=96107974e8) | Apr 25, 2024 |
| Lenovo        | 1036 NO DPK                 | [e69292ead4](https://linux-hardware.org/?probe=e69292ead4) | Apr 25, 2024 |
| ASRock        | B550M Pro4                  | [60952c8e62](https://linux-hardware.org/?probe=60952c8e62) | Apr 24, 2024 |
| Gigabyte      | H310M A-CF x.x              | [250df2037f](https://linux-hardware.org/?probe=250df2037f) | Apr 24, 2024 |
| AMI           | Intel                       | [e1b1d85e3c](https://linux-hardware.org/?probe=e1b1d85e3c) | Apr 23, 2024 |
| Dell          | 0200DY A03                  | [a838cb0e0d](https://linux-hardware.org/?probe=a838cb0e0d) | Apr 23, 2024 |
| HP            | 1494                        | [82c9d00df1](https://linux-hardware.org/?probe=82c9d00df1) | Apr 22, 2024 |
| Dell          | 0HY9JP A02                  | [08e7641b37](https://linux-hardware.org/?probe=08e7641b37) | Apr 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | [0a1f16fa6a](https://linux-hardware.org/?probe=0a1f16fa6a) | Apr 22, 2024 |
| Lenovo        | 1036 NO DPK                 | [1462b6d76a](https://linux-hardware.org/?probe=1462b6d76a) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [91735d80f4](https://linux-hardware.org/?probe=91735d80f4) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [ff2ff25197](https://linux-hardware.org/?probe=ff2ff25197) | Apr 22, 2024 |
| Dell          | 0TY565                      | [f5c8cf7e9b](https://linux-hardware.org/?probe=f5c8cf7e9b) | Apr 21, 2024 |
| HP            | 82A2                        | [1eeebb4829](https://linux-hardware.org/?probe=1eeebb4829) | Apr 20, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [8b93f4607f](https://linux-hardware.org/?probe=8b93f4607f) | Apr 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [b10f7daaa1](https://linux-hardware.org/?probe=b10f7daaa1) | Apr 20, 2024 |
| ASUSTek       | P8Z77-V LK                  | [c2290882c6](https://linux-hardware.org/?probe=c2290882c6) | Apr 18, 2024 |
| MSI           | X58 Pro-E                   | [4411cb9e36](https://linux-hardware.org/?probe=4411cb9e36) | Apr 18, 2024 |
| ASRock        | B450M Pro4                  | [36dcccf3ea](https://linux-hardware.org/?probe=36dcccf3ea) | Apr 17, 2024 |
| Dell          | 0VHWTR A02                  | [4e32c7cfca](https://linux-hardware.org/?probe=4e32c7cfca) | Apr 15, 2024 |
| ASUSTek       | M4A77TD PRO                 | [1a2f03a742](https://linux-hardware.org/?probe=1a2f03a742) | Apr 14, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [88ad8806c3](https://linux-hardware.org/?probe=88ad8806c3) | Apr 13, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [b00ebd6fcc](https://linux-hardware.org/?probe=b00ebd6fcc) | Apr 13, 2024 |
| HP            | 8265                        | [c4d4cdac41](https://linux-hardware.org/?probe=c4d4cdac41) | Apr 13, 2024 |
| ASRock        | B460M Pro4                  | [51a2126e7d](https://linux-hardware.org/?probe=51a2126e7d) | Apr 12, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5bc49637b9](https://linux-hardware.org/?probe=5bc49637b9) | Apr 12, 2024 |
| ASUSTek       | H110I-PLUS                  | [c2d65f19ca](https://linux-hardware.org/?probe=c2d65f19ca) | Apr 12, 2024 |
| ASRock        | H310CM-HDV/M.2              | [a0aec56216](https://linux-hardware.org/?probe=a0aec56216) | Apr 11, 2024 |
| ASUSTek       | P8Z77-V LX                  | [c108665460](https://linux-hardware.org/?probe=c108665460) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5fb89da542](https://linux-hardware.org/?probe=5fb89da542) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [74dd149115](https://linux-hardware.org/?probe=74dd149115) | Apr 11, 2024 |
| ASUSTek       | M5A97 R2.0                  | [eadf15884b](https://linux-hardware.org/?probe=eadf15884b) | Apr 10, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [dd15f5797f](https://linux-hardware.org/?probe=dd15f5797f) | Apr 09, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [2d897e4ab7](https://linux-hardware.org/?probe=2d897e4ab7) | Apr 09, 2024 |
| ASUSTek       | PRIME A320M-R               | [eb77201fa8](https://linux-hardware.org/?probe=eb77201fa8) | Apr 09, 2024 |
| Gigabyte      | B75M-D3H                    | [fa4c48c242](https://linux-hardware.org/?probe=fa4c48c242) | Apr 09, 2024 |
| ASUSTek       | ROG Maximus X CODE          | [446576913d](https://linux-hardware.org/?probe=446576913d) | Apr 08, 2024 |
| ASUSTek       | P5G41T-M LX                 | [67249f5ab0](https://linux-hardware.org/?probe=67249f5ab0) | Apr 08, 2024 |
| ASUSTek       | M4A785TD-V EVO              | [2dbe37af95](https://linux-hardware.org/?probe=2dbe37af95) | Apr 07, 2024 |
| HP            | 8265                        | [601051ee6c](https://linux-hardware.org/?probe=601051ee6c) | Apr 07, 2024 |
| Gigabyte      | H61M-S1                     | [7fe942c453](https://linux-hardware.org/?probe=7fe942c453) | Apr 07, 2024 |
| Dell          | 0D883F A06                  | [74170027e8](https://linux-hardware.org/?probe=74170027e8) | Apr 07, 2024 |
| ASUSTek       | PRIME B365M-A               | [50b8d3eaf1](https://linux-hardware.org/?probe=50b8d3eaf1) | Apr 07, 2024 |
| HP            | 8265                        | [b08747219b](https://linux-hardware.org/?probe=b08747219b) | Apr 06, 2024 |
| Dell          | 02YYK5 A01                  | [e407d84cc9](https://linux-hardware.org/?probe=e407d84cc9) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B460-PLUS        | [3c7ff2a204](https://linux-hardware.org/?probe=3c7ff2a204) | Apr 05, 2024 |
| ASRock        | Z370 Extreme4               | [6354d3d2a2](https://linux-hardware.org/?probe=6354d3d2a2) | Apr 05, 2024 |
| ASRock        | Z370 Extreme4               | [f6925b3c88](https://linux-hardware.org/?probe=f6925b3c88) | Apr 05, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [102e8ee904](https://linux-hardware.org/?probe=102e8ee904) | Apr 05, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [95a657f223](https://linux-hardware.org/?probe=95a657f223) | Apr 03, 2024 |
| ASRock        | 4CoreDual-SATA2             | [469a404c91](https://linux-hardware.org/?probe=469a404c91) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [3c0b19e9f2](https://linux-hardware.org/?probe=3c0b19e9f2) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [48ec750bd0](https://linux-hardware.org/?probe=48ec750bd0) | Apr 03, 2024 |
| Dell          | 0773VG A02                  | [2db2c160ae](https://linux-hardware.org/?probe=2db2c160ae) | Apr 03, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4d733040a](https://linux-hardware.org/?probe=b4d733040a) | Mar 31, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4555fa57d](https://linux-hardware.org/?probe=b4555fa57d) | Mar 31, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [bc68546a92](https://linux-hardware.org/?probe=bc68546a92) | Mar 31, 2024 |
| Gigabyte      | H77N-WIFI                   | [3a99c46a79](https://linux-hardware.org/?probe=3a99c46a79) | Mar 30, 2024 |
| ASUSTek       | PRIME A320M-R               | [c0736cef30](https://linux-hardware.org/?probe=c0736cef30) | Mar 29, 2024 |
| ASRock        | 980DE3/U3S3 R2.0            | [31798dfffc](https://linux-hardware.org/?probe=31798dfffc) | Mar 29, 2024 |
| Gigabyte      | Z390 M GAMING-CF            | [8e4b596d1a](https://linux-hardware.org/?probe=8e4b596d1a) | Mar 29, 2024 |
| Gigabyte      | Z390 M GAMING-CF            | [ae47f9ded9](https://linux-hardware.org/?probe=ae47f9ded9) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [8de5850e62](https://linux-hardware.org/?probe=8de5850e62) | Mar 29, 2024 |
| ASUSTek       | H110M-A                     | [d7699c7455](https://linux-hardware.org/?probe=d7699c7455) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [30817e9020](https://linux-hardware.org/?probe=30817e9020) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [cbccd74400](https://linux-hardware.org/?probe=cbccd74400) | Mar 29, 2024 |
| Lenovo        | 1036 NO DPK                 | [ba8b769eb3](https://linux-hardware.org/?probe=ba8b769eb3) | Mar 29, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [368a738712](https://linux-hardware.org/?probe=368a738712) | Mar 28, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [84c4c90a3f](https://linux-hardware.org/?probe=84c4c90a3f) | Mar 27, 2024 |
| Lenovo        | ThinkServer TS440           | [063d6aafdb](https://linux-hardware.org/?probe=063d6aafdb) | Mar 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [be86cf3fb9](https://linux-hardware.org/?probe=be86cf3fb9) | Mar 26, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [6c186bed7b](https://linux-hardware.org/?probe=6c186bed7b) | Mar 26, 2024 |
| HP            | 1495                        | [806af03d1c](https://linux-hardware.org/?probe=806af03d1c) | Mar 26, 2024 |
| ASRock        | B550M Pro4                  | [e9c2053699](https://linux-hardware.org/?probe=e9c2053699) | Mar 25, 2024 |
| Dell          | 01TKCC A01                  | [65070b32f2](https://linux-hardware.org/?probe=65070b32f2) | Mar 25, 2024 |
| ASRock        | N68C-GS FX                  | [793650d556](https://linux-hardware.org/?probe=793650d556) | Mar 25, 2024 |
| HP            | 339A                        | [a07dca6a8c](https://linux-hardware.org/?probe=a07dca6a8c) | Mar 25, 2024 |
| Dell          | 0K240Y A01                  | [eff3389fdb](https://linux-hardware.org/?probe=eff3389fdb) | Mar 25, 2024 |
| HP            | 1495                        | [50e1e9d3da](https://linux-hardware.org/?probe=50e1e9d3da) | Mar 25, 2024 |
| MSI           | P43i                        | [d56d55fd40](https://linux-hardware.org/?probe=d56d55fd40) | Mar 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [fa1a2097f6](https://linux-hardware.org/?probe=fa1a2097f6) | Mar 24, 2024 |
| Gigabyte      | P67A-D3-B3                  | [1f06fd5eea](https://linux-hardware.org/?probe=1f06fd5eea) | Mar 24, 2024 |
| ASRock        | B85M                        | [4c906767aa](https://linux-hardware.org/?probe=4c906767aa) | Mar 24, 2024 |
| Gigabyte      | B550M DS3H                  | [920a3d2b6b](https://linux-hardware.org/?probe=920a3d2b6b) | Mar 23, 2024 |
| Dell          | 0M858N A01                  | [fa3478bb8f](https://linux-hardware.org/?probe=fa3478bb8f) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1f9a0b4802](https://linux-hardware.org/?probe=1f9a0b4802) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1ee4446988](https://linux-hardware.org/?probe=1ee4446988) | Mar 23, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3d39374ca9](https://linux-hardware.org/?probe=3d39374ca9) | Mar 23, 2024 |
| Gigabyte      | H310M A-CF x.x              | [ef274edd0e](https://linux-hardware.org/?probe=ef274edd0e) | Mar 23, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [1368766d06](https://linux-hardware.org/?probe=1368766d06) | Mar 23, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cf4153f8c](https://linux-hardware.org/?probe=5cf4153f8c) | Mar 23, 2024 |
| Gigabyte      | A520M S2H                   | [11901df61a](https://linux-hardware.org/?probe=11901df61a) | Mar 23, 2024 |
| Gigabyte      | H97-D3H-CF                  | [76ee872777](https://linux-hardware.org/?probe=76ee872777) | Mar 22, 2024 |
| ASUSTek       | H110M-A                     | [2d969a527b](https://linux-hardware.org/?probe=2d969a527b) | Mar 22, 2024 |
| Gigabyte      | B250-HD3P-CF                | [a562caa39d](https://linux-hardware.org/?probe=a562caa39d) | Mar 22, 2024 |
| Gigabyte      | P61-USB3-B3                 | [bd7ae42260](https://linux-hardware.org/?probe=bd7ae42260) | Mar 22, 2024 |
| ASRock        | FM2A75M Pro4+               | [52f8addde4](https://linux-hardware.org/?probe=52f8addde4) | Mar 22, 2024 |
| Dell          | 0200DY A03                  | [0838a0e911](https://linux-hardware.org/?probe=0838a0e911) | Mar 21, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [4276c6c62c](https://linux-hardware.org/?probe=4276c6c62c) | Mar 21, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c8b0e932f7](https://linux-hardware.org/?probe=c8b0e932f7) | Mar 21, 2024 |
| Gigabyte      | H97M-HD3                    | [e80f6ad755](https://linux-hardware.org/?probe=e80f6ad755) | Mar 21, 2024 |
| MSI           | A320M-A PRO MAX             | [faff855b6c](https://linux-hardware.org/?probe=faff855b6c) | Mar 21, 2024 |
| Gigabyte      | H110M-S2V-CF                | [be31fe508d](https://linux-hardware.org/?probe=be31fe508d) | Mar 21, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9d36d6bf2a](https://linux-hardware.org/?probe=9d36d6bf2a) | Mar 21, 2024 |
| MSI           | H61M-P21                    | [feba614c1c](https://linux-hardware.org/?probe=feba614c1c) | Mar 21, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [5de3598ad6](https://linux-hardware.org/?probe=5de3598ad6) | Mar 21, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [a58bb79ea5](https://linux-hardware.org/?probe=a58bb79ea5) | Mar 20, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [98cfbdc7b2](https://linux-hardware.org/?probe=98cfbdc7b2) | Mar 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [50369a26af](https://linux-hardware.org/?probe=50369a26af) | Mar 19, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [9010c8e968](https://linux-hardware.org/?probe=9010c8e968) | Mar 19, 2024 |
| Foxconn       | 2ABF                        | [cec4a4b661](https://linux-hardware.org/?probe=cec4a4b661) | Mar 19, 2024 |
| ASUSTek       | PRIME A520M-E               | [fe6517ecf5](https://linux-hardware.org/?probe=fe6517ecf5) | Mar 18, 2024 |
| ASUSTek       | PRIME A520M-E               | [151ae9cdaf](https://linux-hardware.org/?probe=151ae9cdaf) | Mar 18, 2024 |
| ASUSTek       | G15DK                       | [1265b31544](https://linux-hardware.org/?probe=1265b31544) | Mar 18, 2024 |
| Gigabyte      | P35-DS3R                    | [0e8135e5be](https://linux-hardware.org/?probe=0e8135e5be) | Mar 17, 2024 |
| Gigabyte      | P35-DS3R                    | [37d7839fa0](https://linux-hardware.org/?probe=37d7839fa0) | Mar 17, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [598011953e](https://linux-hardware.org/?probe=598011953e) | Mar 16, 2024 |
| Gigabyte      | Z170-Gaming K3-CF           | [e6b3e23ce6](https://linux-hardware.org/?probe=e6b3e23ce6) | Mar 16, 2024 |
| Gigabyte      | Z390 UD V2                  | [cc72fc2c00](https://linux-hardware.org/?probe=cc72fc2c00) | Mar 16, 2024 |
| MSI           | A320M-A PRO MAX             | [1d1cd6ea78](https://linux-hardware.org/?probe=1d1cd6ea78) | Mar 15, 2024 |
| Dell          | 0D883F A06                  | [6d25f1767a](https://linux-hardware.org/?probe=6d25f1767a) | Mar 15, 2024 |
| Dell          | 0K240Y A01                  | [01dc917dc9](https://linux-hardware.org/?probe=01dc917dc9) | Mar 15, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [53e053987b](https://linux-hardware.org/?probe=53e053987b) | Mar 15, 2024 |
| ASUSTek       | PRIME H410M-A               | [5a5a67a0da](https://linux-hardware.org/?probe=5a5a67a0da) | Mar 14, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [996e768c3b](https://linux-hardware.org/?probe=996e768c3b) | Mar 14, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [86d3affb55](https://linux-hardware.org/?probe=86d3affb55) | Mar 14, 2024 |
| Medion        | MS-7748                     | [2936ceb830](https://linux-hardware.org/?probe=2936ceb830) | Mar 14, 2024 |
| ASUSTek       | PRIME A320M-R               | [f3d5cd78e2](https://linux-hardware.org/?probe=f3d5cd78e2) | Mar 14, 2024 |
| ASUSTek       | PRIME H410M-A               | [ad72304437](https://linux-hardware.org/?probe=ad72304437) | Mar 13, 2024 |
| Lenovo        | 1730-A1G                    | [7c5c30e4d7](https://linux-hardware.org/?probe=7c5c30e4d7) | Mar 13, 2024 |
| Lenovo        | SHARKBAY NOK                | [ebf6bd7140](https://linux-hardware.org/?probe=ebf6bd7140) | Mar 13, 2024 |
| Gigabyte      | B450M GAMING                | [712f217722](https://linux-hardware.org/?probe=712f217722) | Mar 12, 2024 |
| Gigabyte      | P61-USB3-B3                 | [b632a864a7](https://linux-hardware.org/?probe=b632a864a7) | Mar 11, 2024 |
| Gigabyte      | B85M-HD3G                   | [61d1a0a769](https://linux-hardware.org/?probe=61d1a0a769) | Mar 11, 2024 |
| Gigabyte      | B85M-HD3G                   | [827f0d1418](https://linux-hardware.org/?probe=827f0d1418) | Mar 11, 2024 |
| ASUSTek       | A88XM-E                     | [6dc26a8c1b](https://linux-hardware.org/?probe=6dc26a8c1b) | Mar 11, 2024 |
| Gigabyte      | B75M-D3H                    | [e350a0f21a](https://linux-hardware.org/?probe=e350a0f21a) | Mar 10, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [dfa4480394](https://linux-hardware.org/?probe=dfa4480394) | Mar 10, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [7f8abbb276](https://linux-hardware.org/?probe=7f8abbb276) | Mar 09, 2024 |
| Gigabyte      | H110M-S2V-CF                | [9eecf787b4](https://linux-hardware.org/?probe=9eecf787b4) | Mar 09, 2024 |
| Dell          | 0VHWTR A02                  | [414f810f95](https://linux-hardware.org/?probe=414f810f95) | Mar 08, 2024 |
| ASRock        | H81M-VG4                    | [96f9d92727](https://linux-hardware.org/?probe=96f9d92727) | Mar 08, 2024 |
| ASRock        | H470M-HDV                   | [b780951a3d](https://linux-hardware.org/?probe=b780951a3d) | Mar 08, 2024 |
| ASRock        | H470M-HDV                   | [8a4ca76c85](https://linux-hardware.org/?probe=8a4ca76c85) | Mar 08, 2024 |
| ASUSTek       | PRIME A320M-K               | [bf70b84d81](https://linux-hardware.org/?probe=bf70b84d81) | Mar 08, 2024 |
| HP            | 805D                        | [853e435928](https://linux-hardware.org/?probe=853e435928) | Mar 08, 2024 |
| Lenovo        | SHARKBAY NOK                | [4076eb2209](https://linux-hardware.org/?probe=4076eb2209) | Mar 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [90d69200ef](https://linux-hardware.org/?probe=90d69200ef) | Mar 07, 2024 |
| Gigabyte      | H97M-HD3                    | [1b028e3789](https://linux-hardware.org/?probe=1b028e3789) | Mar 07, 2024 |
| Medion        | MS-7748                     | [77a10d77ea](https://linux-hardware.org/?probe=77a10d77ea) | Mar 07, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | [d5ee5ee229](https://linux-hardware.org/?probe=d5ee5ee229) | Mar 06, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [c9d0284a9b](https://linux-hardware.org/?probe=c9d0284a9b) | Mar 06, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [abace2521d](https://linux-hardware.org/?probe=abace2521d) | Mar 05, 2024 |
| ASUSTek       | H110M-A                     | [695e54f273](https://linux-hardware.org/?probe=695e54f273) | Mar 05, 2024 |
| Gigabyte      | B450 GAMING X               | [ab4aeaa345](https://linux-hardware.org/?probe=ab4aeaa345) | Mar 03, 2024 |
| ASRock        | G41M-VS3                    | [03a42b8972](https://linux-hardware.org/?probe=03a42b8972) | Mar 03, 2024 |
| HP            | 3047h                       | [fb25a061b8](https://linux-hardware.org/?probe=fb25a061b8) | Mar 03, 2024 |
| HP            | 3047h                       | [171fc32e0a](https://linux-hardware.org/?probe=171fc32e0a) | Mar 03, 2024 |
| Dell          | 0200DY A03                  | [b06d040c63](https://linux-hardware.org/?probe=b06d040c63) | Mar 03, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [c9c10a188e](https://linux-hardware.org/?probe=c9c10a188e) | Mar 02, 2024 |
| Gigabyte      | B450M GAMING                | [5ffab2a305](https://linux-hardware.org/?probe=5ffab2a305) | Mar 02, 2024 |
| Lenovo        | MAHOBAY NOK                 | [862d4553c0](https://linux-hardware.org/?probe=862d4553c0) | Mar 01, 2024 |
| ASRock        | B550M Pro4                  | [795e44e4cf](https://linux-hardware.org/?probe=795e44e4cf) | Feb 28, 2024 |
| ASRock        | H81M-VG4                    | [031f559cf7](https://linux-hardware.org/?probe=031f559cf7) | Feb 27, 2024 |
| HP            | 1497                        | [8fc0f49c19](https://linux-hardware.org/?probe=8fc0f49c19) | Feb 26, 2024 |
| Gigabyte      | H310M A-CF x.x              | [af6ad45d24](https://linux-hardware.org/?probe=af6ad45d24) | Feb 25, 2024 |
| Lenovo        | 1730-A1G                    | [a6ca9cff31](https://linux-hardware.org/?probe=a6ca9cff31) | Feb 25, 2024 |
| HP            | 304Ah                       | [0c2c06e76f](https://linux-hardware.org/?probe=0c2c06e76f) | Feb 25, 2024 |
| HP            | 304Ah                       | [98ce8f9cf7](https://linux-hardware.org/?probe=98ce8f9cf7) | Feb 25, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [bf94f23691](https://linux-hardware.org/?probe=bf94f23691) | Feb 24, 2024 |
| Dell          | 0M3F6C A01                  | [a6d9ac4ceb](https://linux-hardware.org/?probe=a6d9ac4ceb) | Feb 24, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6a9db010d9](https://linux-hardware.org/?probe=6a9db010d9) | Feb 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [2ae75f745e](https://linux-hardware.org/?probe=2ae75f745e) | Feb 23, 2024 |
| Dell          | 0D883F A06                  | [2f2b1cd47c](https://linux-hardware.org/?probe=2f2b1cd47c) | Feb 21, 2024 |
| HP            | 8265                        | [530f502c52](https://linux-hardware.org/?probe=530f502c52) | Feb 20, 2024 |
| Gigabyte      | G31M-S2C                    | [678ad5ec54](https://linux-hardware.org/?probe=678ad5ec54) | Feb 20, 2024 |
| ASRock        | FM2A75M Pro4+               | [cbc49630c4](https://linux-hardware.org/?probe=cbc49630c4) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [3279f823cb](https://linux-hardware.org/?probe=3279f823cb) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [c301bbef33](https://linux-hardware.org/?probe=c301bbef33) | Feb 19, 2024 |
| Gigabyte      | H77N-WIFI                   | [6c0119ee26](https://linux-hardware.org/?probe=6c0119ee26) | Feb 19, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5df2e64ba9](https://linux-hardware.org/?probe=5df2e64ba9) | Feb 18, 2024 |
| Gigabyte      | EP31-DS3L                   | [a2f2f76c2e](https://linux-hardware.org/?probe=a2f2f76c2e) | Feb 18, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [ad35cbf450](https://linux-hardware.org/?probe=ad35cbf450) | Feb 17, 2024 |
| HP            | 3047h                       | [45ba601c69](https://linux-hardware.org/?probe=45ba601c69) | Feb 16, 2024 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [0a9db7ec56](https://linux-hardware.org/?probe=0a9db7ec56) | Feb 16, 2024 |
| ASRock        | B85M                        | [c9300aa54b](https://linux-hardware.org/?probe=c9300aa54b) | Feb 16, 2024 |
| Gigabyte      | A520M S2H                   | [ff0aa6019c](https://linux-hardware.org/?probe=ff0aa6019c) | Feb 16, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [0139a8dd1b](https://linux-hardware.org/?probe=0139a8dd1b) | Feb 15, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [b116cf57b4](https://linux-hardware.org/?probe=b116cf57b4) | Feb 15, 2024 |
| Lenovo        | 1036 NO DPK                 | [125c31fd2c](https://linux-hardware.org/?probe=125c31fd2c) | Feb 15, 2024 |
| ASRock        | Z77 Extreme4                | [be56fe1029](https://linux-hardware.org/?probe=be56fe1029) | Feb 14, 2024 |
| HP            | 8265                        | [e4997d7fc2](https://linux-hardware.org/?probe=e4997d7fc2) | Feb 14, 2024 |
| HP            | 339A                        | [69c4f45b66](https://linux-hardware.org/?probe=69c4f45b66) | Feb 14, 2024 |
| Gigabyte      | G41MT-ES2L                  | [60cdce8ae3](https://linux-hardware.org/?probe=60cdce8ae3) | Feb 14, 2024 |
| Gigabyte      | H97-D3H-CF                  | [a5117dd4fd](https://linux-hardware.org/?probe=a5117dd4fd) | Feb 13, 2024 |
| ASUSTek       | PRIME B365M-A               | [2955560f16](https://linux-hardware.org/?probe=2955560f16) | Feb 13, 2024 |
| ASRock        | N68C-GS FX                  | [81bc175b9c](https://linux-hardware.org/?probe=81bc175b9c) | Feb 13, 2024 |
| ASRock        | B550M Pro4                  | [39aa1a05dd](https://linux-hardware.org/?probe=39aa1a05dd) | Feb 13, 2024 |
| HP            | 1495                        | [047dcce2b9](https://linux-hardware.org/?probe=047dcce2b9) | Feb 12, 2024 |
| Dell          | 0200DY A03                  | [6075938249](https://linux-hardware.org/?probe=6075938249) | Feb 12, 2024 |
| Gigabyte      | H61M-S2PV                   | [1f1cba872e](https://linux-hardware.org/?probe=1f1cba872e) | Feb 11, 2024 |
| Gigabyte      | P67A-D3-B3                  | [a1b482c4e5](https://linux-hardware.org/?probe=a1b482c4e5) | Feb 11, 2024 |
| ASUSTek       | P8Z77-V LX                  | [1db2b9826c](https://linux-hardware.org/?probe=1db2b9826c) | Feb 11, 2024 |
| Gigabyte      | H61M-S2PV                   | [214f3483d2](https://linux-hardware.org/?probe=214f3483d2) | Feb 11, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4086a071b2](https://linux-hardware.org/?probe=4086a071b2) | Feb 11, 2024 |
| Lenovo        | ThinkCentre M58 9960ALU     | [2eaa6f55a6](https://linux-hardware.org/?probe=2eaa6f55a6) | Feb 11, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [db64b21f5a](https://linux-hardware.org/?probe=db64b21f5a) | Feb 11, 2024 |
| Dell          | 0TY565                      | [d7a498944b](https://linux-hardware.org/?probe=d7a498944b) | Feb 11, 2024 |
| Intel         | DG35EC AAE29266-210         | [38bd2900f7](https://linux-hardware.org/?probe=38bd2900f7) | Feb 10, 2024 |
| Intel         | DG35EC AAE29266-210         | [5e6e7740d9](https://linux-hardware.org/?probe=5e6e7740d9) | Feb 10, 2024 |
| Gigabyte      | H110M-S2V-CF                | [02056c1523](https://linux-hardware.org/?probe=02056c1523) | Feb 10, 2024 |
| HP            | 8265                        | [e83158cda7](https://linux-hardware.org/?probe=e83158cda7) | Feb 10, 2024 |
| ASUSTek       | PRIME A320M-R               | [73ec818c35](https://linux-hardware.org/?probe=73ec818c35) | Feb 10, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [377976b6a3](https://linux-hardware.org/?probe=377976b6a3) | Feb 10, 2024 |
| Fujitsu       | D3313-S4 S26361-D3313-S4    | [e07a96da14](https://linux-hardware.org/?probe=e07a96da14) | Feb 10, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [edb250e20a](https://linux-hardware.org/?probe=edb250e20a) | Feb 10, 2024 |
| ASUSTek       | H110M-K                     | [5002d94a38](https://linux-hardware.org/?probe=5002d94a38) | Feb 09, 2024 |
| ASRock        | 775i945GZ                   | [38891b0920](https://linux-hardware.org/?probe=38891b0920) | Feb 09, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [e9f7f560fe](https://linux-hardware.org/?probe=e9f7f560fe) | Feb 09, 2024 |
| Acer          | RS880M05                    | [c69fcadae3](https://linux-hardware.org/?probe=c69fcadae3) | Feb 09, 2024 |
| HP            | 1495                        | [6fff4b1751](https://linux-hardware.org/?probe=6fff4b1751) | Feb 09, 2024 |
| ASUSTek       | P5G41T-M LX3                | [fd10cd8983](https://linux-hardware.org/?probe=fd10cd8983) | Feb 09, 2024 |
| ASUSTek       | P5G41T-M LX3                | [ae6f0a23e2](https://linux-hardware.org/?probe=ae6f0a23e2) | Feb 09, 2024 |
| Dell          | 0M858N A01                  | [e57e9094b4](https://linux-hardware.org/?probe=e57e9094b4) | Feb 08, 2024 |
| MSI           | P43i                        | [b4c30541fa](https://linux-hardware.org/?probe=b4c30541fa) | Feb 08, 2024 |
| Acer          | RS880M05                    | [f0581e65cc](https://linux-hardware.org/?probe=f0581e65cc) | Feb 08, 2024 |
| ASUSTek       | H110M-A                     | [4515105b8d](https://linux-hardware.org/?probe=4515105b8d) | Feb 08, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [742d19f797](https://linux-hardware.org/?probe=742d19f797) | Feb 08, 2024 |
| Gigabyte      | H110M-S2V-CF                | [84a355a004](https://linux-hardware.org/?probe=84a355a004) | Feb 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [90a5d44bde](https://linux-hardware.org/?probe=90a5d44bde) | Feb 08, 2024 |
| MSI           | A320M-A PRO MAX             | [986691347b](https://linux-hardware.org/?probe=986691347b) | Feb 07, 2024 |
| Dell          | 0VHWTR A02                  | [d37b4c9999](https://linux-hardware.org/?probe=d37b4c9999) | Feb 07, 2024 |
| Gigabyte      | Z390 UD V2                  | [1538e99333](https://linux-hardware.org/?probe=1538e99333) | Feb 07, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [d1be9e4f66](https://linux-hardware.org/?probe=d1be9e4f66) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [9f50a00ce2](https://linux-hardware.org/?probe=9f50a00ce2) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [52d70892db](https://linux-hardware.org/?probe=52d70892db) | Feb 07, 2024 |
| HP            | 1495                        | [72869998f4](https://linux-hardware.org/?probe=72869998f4) | Feb 07, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [0c0a1d2651](https://linux-hardware.org/?probe=0c0a1d2651) | Feb 06, 2024 |
| HP            | 0B4Ch D                     | [9258e387e7](https://linux-hardware.org/?probe=9258e387e7) | Feb 06, 2024 |
| Lenovo        | 1036 NO DPK                 | [90b0945a98](https://linux-hardware.org/?probe=90b0945a98) | Feb 06, 2024 |
| Dell          | 0M858N A01                  | [efe0f9fc26](https://linux-hardware.org/?probe=efe0f9fc26) | Feb 05, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5013c4bba6](https://linux-hardware.org/?probe=5013c4bba6) | Feb 05, 2024 |
| Gigabyte      | H310M A-CF x.x              | [e9ae02c21e](https://linux-hardware.org/?probe=e9ae02c21e) | Feb 05, 2024 |
| Gigabyte      | A520M S2H                   | [a5467dc900](https://linux-hardware.org/?probe=a5467dc900) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [79200de704](https://linux-hardware.org/?probe=79200de704) | Feb 04, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ca1fce3f2f](https://linux-hardware.org/?probe=ca1fce3f2f) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [553aeec0a5](https://linux-hardware.org/?probe=553aeec0a5) | Feb 04, 2024 |
| ASUSTek       | PRIME A320M-R               | [533592b8f0](https://linux-hardware.org/?probe=533592b8f0) | Feb 04, 2024 |
| ASUSTek       | H110M-A                     | [684ac8da19](https://linux-hardware.org/?probe=684ac8da19) | Feb 04, 2024 |
| Dell          | 0200DY A03                  | [07d45f5532](https://linux-hardware.org/?probe=07d45f5532) | Feb 03, 2024 |
| Gigabyte      | H97-D3H-CF                  | [9c4309b1ea](https://linux-hardware.org/?probe=9c4309b1ea) | Feb 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6068e871ed](https://linux-hardware.org/?probe=6068e871ed) | Feb 03, 2024 |
| ASUSTek       | PRIME A320M-K               | [dfa3229b6d](https://linux-hardware.org/?probe=dfa3229b6d) | Feb 03, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5eb37a9fb2](https://linux-hardware.org/?probe=5eb37a9fb2) | Feb 03, 2024 |
| HP            | 1497                        | [ae90a32790](https://linux-hardware.org/?probe=ae90a32790) | Feb 02, 2024 |
| Gigabyte      | G31M-S2C                    | [b0e201e74a](https://linux-hardware.org/?probe=b0e201e74a) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [4009a96bd4](https://linux-hardware.org/?probe=4009a96bd4) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [ab60a0a3b4](https://linux-hardware.org/?probe=ab60a0a3b4) | Feb 02, 2024 |
| ASRock        | B550M Pro4                  | [ce95a21f31](https://linux-hardware.org/?probe=ce95a21f31) | Feb 01, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [1cee0ab81d](https://linux-hardware.org/?probe=1cee0ab81d) | Feb 01, 2024 |
| ASUSTek       | H110M-A                     | [ef9ec58561](https://linux-hardware.org/?probe=ef9ec58561) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [c85924bf6f](https://linux-hardware.org/?probe=c85924bf6f) | Jan 31, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [aad32e443a](https://linux-hardware.org/?probe=aad32e443a) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [4995dfcd57](https://linux-hardware.org/?probe=4995dfcd57) | Jan 31, 2024 |
| MSI           | MS-7817                     | [e67644d160](https://linux-hardware.org/?probe=e67644d160) | Jan 31, 2024 |
| ASRock        | B550M Pro4                  | [562a7e84b6](https://linux-hardware.org/?probe=562a7e84b6) | Jan 31, 2024 |
| Dell          | 0TY565                      | [7b0be6d329](https://linux-hardware.org/?probe=7b0be6d329) | Jan 31, 2024 |
| Dell          | 0TY565                      | [a1dd2e6d5d](https://linux-hardware.org/?probe=a1dd2e6d5d) | Jan 31, 2024 |
| Dell          | 06D7TR A01                  | [34d3eaffac](https://linux-hardware.org/?probe=34d3eaffac) | Jan 31, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [2f08f48285](https://linux-hardware.org/?probe=2f08f48285) | Jan 31, 2024 |
| HP            | 8265                        | [77473b5bd8](https://linux-hardware.org/?probe=77473b5bd8) | Jan 30, 2024 |
| HP            | 1495                        | [1c71a50dfc](https://linux-hardware.org/?probe=1c71a50dfc) | Jan 30, 2024 |
| ASUSTek       | H110M-A                     | [e72fb50bf3](https://linux-hardware.org/?probe=e72fb50bf3) | Jan 29, 2024 |
| Dell          | 0M858N A01                  | [ea55d99987](https://linux-hardware.org/?probe=ea55d99987) | Jan 29, 2024 |
| MSI           | P43i                        | [ff8e7e4853](https://linux-hardware.org/?probe=ff8e7e4853) | Jan 29, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [bf9584029c](https://linux-hardware.org/?probe=bf9584029c) | Jan 29, 2024 |
| Gigabyte      | P67A-D3-B3                  | [5241c055ad](https://linux-hardware.org/?probe=5241c055ad) | Jan 29, 2024 |
| ASRock        | B85M                        | [2f1c8ac5f5](https://linux-hardware.org/?probe=2f1c8ac5f5) | Jan 29, 2024 |
| ASUSTek       | PRIME B365M-A               | [f046e20a98](https://linux-hardware.org/?probe=f046e20a98) | Jan 29, 2024 |
| HP            | 3396                        | [b59e0b4023](https://linux-hardware.org/?probe=b59e0b4023) | Jan 29, 2024 |
| Dell          | 0200DY A03                  | [26d8100c96](https://linux-hardware.org/?probe=26d8100c96) | Jan 28, 2024 |
| Lenovo        | 1036 NO DPK                 | [aa54fcaee1](https://linux-hardware.org/?probe=aa54fcaee1) | Jan 28, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [32a41e8aff](https://linux-hardware.org/?probe=32a41e8aff) | Jan 28, 2024 |
| ASRock        | B75M-DGS R2.0               | [cff86cc0d9](https://linux-hardware.org/?probe=cff86cc0d9) | Jan 27, 2024 |
| Gigabyte      | H61M-S2PV                   | [b313d408fc](https://linux-hardware.org/?probe=b313d408fc) | Jan 27, 2024 |
| MSI           | MS-7817                     | [53d14e5734](https://linux-hardware.org/?probe=53d14e5734) | Jan 26, 2024 |
| ASUSTek       | P5LD2-X/1333                | [6175179da0](https://linux-hardware.org/?probe=6175179da0) | Jan 26, 2024 |
| ASUSTek       | PRIME Z270-A                | [710334dba6](https://linux-hardware.org/?probe=710334dba6) | Jan 26, 2024 |
| Gigabyte      | H61M-S2PV                   | [ec7c2fd28c](https://linux-hardware.org/?probe=ec7c2fd28c) | Jan 26, 2024 |
| HP            | 1497                        | [70ed07412a](https://linux-hardware.org/?probe=70ed07412a) | Jan 26, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [f1397d3500](https://linux-hardware.org/?probe=f1397d3500) | Jan 26, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [919e1d0d1a](https://linux-hardware.org/?probe=919e1d0d1a) | Jan 25, 2024 |
| ASRock        | FM2A75M Pro4+               | [b13e328c84](https://linux-hardware.org/?probe=b13e328c84) | Jan 25, 2024 |
| ASUSTek       | PRIME Z270-A                | [8e84a9a187](https://linux-hardware.org/?probe=8e84a9a187) | Jan 25, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ecec004de9](https://linux-hardware.org/?probe=ecec004de9) | Jan 25, 2024 |
| Gigabyte      | Z390 UD V2                  | [43e8fec21d](https://linux-hardware.org/?probe=43e8fec21d) | Jan 25, 2024 |
| ASUSTek       | H110M-K                     | [e187cbf4f0](https://linux-hardware.org/?probe=e187cbf4f0) | Jan 24, 2024 |
| HP            | 821D                        | [c56ee90d6b](https://linux-hardware.org/?probe=c56ee90d6b) | Jan 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [9aa36d0ef2](https://linux-hardware.org/?probe=9aa36d0ef2) | Jan 24, 2024 |
| Gigabyte      | A520M S2H                   | [3c14c44a2e](https://linux-hardware.org/?probe=3c14c44a2e) | Jan 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cc29f2f4d](https://linux-hardware.org/?probe=5cc29f2f4d) | Jan 24, 2024 |
| Gigabyte      | H97-D3H-CF                  | [5b4d20246c](https://linux-hardware.org/?probe=5b4d20246c) | Jan 23, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [4c6536c12f](https://linux-hardware.org/?probe=4c6536c12f) | Jan 23, 2024 |
| MSI           | P43i                        | [96ed9e6412](https://linux-hardware.org/?probe=96ed9e6412) | Jan 23, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d3cf795f5d](https://linux-hardware.org/?probe=d3cf795f5d) | Jan 22, 2024 |
| Dell          | 0K240Y A01                  | [ea975a38d2](https://linux-hardware.org/?probe=ea975a38d2) | Jan 22, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [448b20e8f3](https://linux-hardware.org/?probe=448b20e8f3) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f18016d0b6](https://linux-hardware.org/?probe=f18016d0b6) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f55473c84d](https://linux-hardware.org/?probe=f55473c84d) | Jan 22, 2024 |
| HP            | 0B4Ch D                     | [382a956d11](https://linux-hardware.org/?probe=382a956d11) | Jan 22, 2024 |
| Dell          | 0GY6Y8 A01                  | [70ed7265d7](https://linux-hardware.org/?probe=70ed7265d7) | Jan 22, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [41a62ec1d4](https://linux-hardware.org/?probe=41a62ec1d4) | Jan 21, 2024 |
| HP            | 0B4Ch D                     | [ac643dc1d4](https://linux-hardware.org/?probe=ac643dc1d4) | Jan 21, 2024 |
| ASRock        | N68C-S UCC                  | [dc2724d2ca](https://linux-hardware.org/?probe=dc2724d2ca) | Jan 20, 2024 |
| Gigabyte      | B450M S2H                   | [5f1537cd10](https://linux-hardware.org/?probe=5f1537cd10) | Jan 19, 2024 |
| Medion        | MS-7748                     | [0da6204fe7](https://linux-hardware.org/?probe=0da6204fe7) | Jan 19, 2024 |
| ASUSTek       | PRIME A320M-R               | [314cb08407](https://linux-hardware.org/?probe=314cb08407) | Jan 18, 2024 |
| Lenovo        | 1036 NO DPK                 | [fe04dc8528](https://linux-hardware.org/?probe=fe04dc8528) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [382d54efe4](https://linux-hardware.org/?probe=382d54efe4) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [f2ae4fae96](https://linux-hardware.org/?probe=f2ae4fae96) | Jan 18, 2024 |
| ASUSTek       | P5LD2-X/1333                | [7670d862e1](https://linux-hardware.org/?probe=7670d862e1) | Jan 17, 2024 |
| ASRock        | FM2A75M Pro4+               | [8b6cc378c3](https://linux-hardware.org/?probe=8b6cc378c3) | Jan 16, 2024 |
| Gigabyte      | Z790 UD AX                  | [8d2af876bf](https://linux-hardware.org/?probe=8d2af876bf) | Jan 15, 2024 |
| Dell          | 0GM819                      | [b55d9b9a52](https://linux-hardware.org/?probe=b55d9b9a52) | Jan 14, 2024 |
| Gigabyte      | H61M-S2PV                   | [3e4a544656](https://linux-hardware.org/?probe=3e4a544656) | Jan 13, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [ea74a34365](https://linux-hardware.org/?probe=ea74a34365) | Jan 13, 2024 |
| ASUSTek       | A58M-K                      | [574d526af4](https://linux-hardware.org/?probe=574d526af4) | Jan 13, 2024 |
| ASUSTek       | PRIME Z390-A                | [bcbcc04761](https://linux-hardware.org/?probe=bcbcc04761) | Jan 13, 2024 |
| ASRock        | B550M Pro4                  | [f4660fbf02](https://linux-hardware.org/?probe=f4660fbf02) | Jan 12, 2024 |
| Gigabyte      | H310M A-CF x.x              | [4b838199f5](https://linux-hardware.org/?probe=4b838199f5) | Jan 11, 2024 |
| Gigabyte      | H310M A-CF x.x              | [cb71ddc06e](https://linux-hardware.org/?probe=cb71ddc06e) | Jan 11, 2024 |
| Medion        | MS-7748                     | [fd6786798c](https://linux-hardware.org/?probe=fd6786798c) | Jan 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [13954507ba](https://linux-hardware.org/?probe=13954507ba) | Jan 10, 2024 |
| ASRock        | N68C-S UCC                  | [fb39fef7a4](https://linux-hardware.org/?probe=fb39fef7a4) | Jan 09, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [177fdc1d8d](https://linux-hardware.org/?probe=177fdc1d8d) | Jan 08, 2024 |
| Dell          | 0T0MHW A02                  | [a71fc6258c](https://linux-hardware.org/?probe=a71fc6258c) | Jan 08, 2024 |
| HP            | 339A                        | [7f31e925d5](https://linux-hardware.org/?probe=7f31e925d5) | Jan 07, 2024 |
| Dell          | 0200DY A03                  | [398cb20c88](https://linux-hardware.org/?probe=398cb20c88) | Jan 07, 2024 |
| ASUSTek       | H110M-A                     | [d24e2d377c](https://linux-hardware.org/?probe=d24e2d377c) | Jan 07, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [db15f78582](https://linux-hardware.org/?probe=db15f78582) | Jan 06, 2024 |
| ASUSTek       | VM42                        | [78596515e5](https://linux-hardware.org/?probe=78596515e5) | Jan 06, 2024 |
| Gigabyte      | GA-MA78GPM-DS2H             | [22e4df864b](https://linux-hardware.org/?probe=22e4df864b) | Jan 06, 2024 |
| HP            | 8265                        | [227d139424](https://linux-hardware.org/?probe=227d139424) | Jan 05, 2024 |
| ASUSTek       | A88XM-E                     | [671224ec71](https://linux-hardware.org/?probe=671224ec71) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [0a4ab17035](https://linux-hardware.org/?probe=0a4ab17035) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [a6bd11e06b](https://linux-hardware.org/?probe=a6bd11e06b) | Jan 05, 2024 |
| ASUSTek       | B75M-A                      | [f18bf0c881](https://linux-hardware.org/?probe=f18bf0c881) | Jan 04, 2024 |
| Dell          | 0M858N A01                  | [115fd937a1](https://linux-hardware.org/?probe=115fd937a1) | Jan 04, 2024 |
| ASRock        | B85M                        | [093643c0f0](https://linux-hardware.org/?probe=093643c0f0) | Jan 04, 2024 |
| ASRock        | G41M-VS3                    | [4a19917cf2](https://linux-hardware.org/?probe=4a19917cf2) | Jan 04, 2024 |
| ASRock        | H61M/U3S3                   | [e6f1a43f8e](https://linux-hardware.org/?probe=e6f1a43f8e) | Jan 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [76a2205872](https://linux-hardware.org/?probe=76a2205872) | Jan 03, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [74e244eb6c](https://linux-hardware.org/?probe=74e244eb6c) | Jan 02, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [7f438185af](https://linux-hardware.org/?probe=7f438185af) | Jan 02, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [79b5e7c7b0](https://linux-hardware.org/?probe=79b5e7c7b0) | Jan 01, 2024 |
| ASUSTek       | P8H67-M EVO                 | [7c95d175bb](https://linux-hardware.org/?probe=7c95d175bb) | Jan 01, 2024 |
| Gigabyte      | P67A-D3-B3                  | [28494e9d46](https://linux-hardware.org/?probe=28494e9d46) | Jan 01, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [23eb635b4e](https://linux-hardware.org/?probe=23eb635b4e) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [da76fd5108](https://linux-hardware.org/?probe=da76fd5108) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [d646e8d5fb](https://linux-hardware.org/?probe=d646e8d5fb) | Jan 01, 2024 |
| MSI           | P43i                        | [a31ae3403f](https://linux-hardware.org/?probe=a31ae3403f) | Dec 31, 2023 |
| ASRock        | FM2A55M-HD+                 | [d60c82646d](https://linux-hardware.org/?probe=d60c82646d) | Dec 31, 2023 |
| AMI           | Intel                       | [532ef0e65e](https://linux-hardware.org/?probe=532ef0e65e) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [e89341eb95](https://linux-hardware.org/?probe=e89341eb95) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [b24918bdbc](https://linux-hardware.org/?probe=b24918bdbc) | Dec 31, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [f59bee0805](https://linux-hardware.org/?probe=f59bee0805) | Dec 31, 2023 |
| Gigabyte      | Z390 UD V2                  | [c7c5239d23](https://linux-hardware.org/?probe=c7c5239d23) | Dec 31, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [99950d43fc](https://linux-hardware.org/?probe=99950d43fc) | Dec 31, 2023 |
| HP            | 339A                        | [f109c46a8a](https://linux-hardware.org/?probe=f109c46a8a) | Dec 31, 2023 |
| ASUSTek       | H110M-A                     | [f2fd99d70d](https://linux-hardware.org/?probe=f2fd99d70d) | Dec 30, 2023 |
| Dell          | 0TY565                      | [97111d45ea](https://linux-hardware.org/?probe=97111d45ea) | Dec 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6cb0db7e23](https://linux-hardware.org/?probe=6cb0db7e23) | Dec 30, 2023 |
| Gigabyte      | EP31-DS3L                   | [428843cfe5](https://linux-hardware.org/?probe=428843cfe5) | Dec 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a2ba669444](https://linux-hardware.org/?probe=a2ba669444) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b1b1057a4b](https://linux-hardware.org/?probe=b1b1057a4b) | Dec 30, 2023 |
| Gigabyte      | H310M A-CF x.x              | [85efe53330](https://linux-hardware.org/?probe=85efe53330) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [d094c3b4e3](https://linux-hardware.org/?probe=d094c3b4e3) | Dec 29, 2023 |
| HP            | ProLiant MicroServer        | [30f06f373e](https://linux-hardware.org/?probe=30f06f373e) | Dec 29, 2023 |
| HP            | 3033h                       | [05bb2e9644](https://linux-hardware.org/?probe=05bb2e9644) | Dec 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [780047716e](https://linux-hardware.org/?probe=780047716e) | Dec 29, 2023 |
| ASUSTek       | PRIME A320M-R               | [d5b19de2f0](https://linux-hardware.org/?probe=d5b19de2f0) | Dec 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | [0d64ace463](https://linux-hardware.org/?probe=0d64ace463) | Dec 29, 2023 |
| Gigabyte      | A520M S2H                   | [8cc62b9497](https://linux-hardware.org/?probe=8cc62b9497) | Dec 28, 2023 |
| ASUSTek       | H81M-E                      | [9cd2a6ed45](https://linux-hardware.org/?probe=9cd2a6ed45) | Dec 28, 2023 |
| ASUSTek       | H110M-K                     | [b3a423171f](https://linux-hardware.org/?probe=b3a423171f) | Dec 28, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [5b652d7eba](https://linux-hardware.org/?probe=5b652d7eba) | Dec 28, 2023 |
| HP            | 1495                        | [91f12e4a03](https://linux-hardware.org/?probe=91f12e4a03) | Dec 28, 2023 |
| ASUSTek       | PRIME A320M-R               | [b30cb3fc14](https://linux-hardware.org/?probe=b30cb3fc14) | Dec 28, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [6023618793](https://linux-hardware.org/?probe=6023618793) | Dec 27, 2023 |
| HP            | 1497                        | [9c80dd9de3](https://linux-hardware.org/?probe=9c80dd9de3) | Dec 27, 2023 |
| HP            | 3048h                       | [94e268312a](https://linux-hardware.org/?probe=94e268312a) | Dec 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | [452b67f058](https://linux-hardware.org/?probe=452b67f058) | Dec 27, 2023 |
| Dell          | 0RW199                      | [906719d239](https://linux-hardware.org/?probe=906719d239) | Dec 27, 2023 |
| ASUSTek       | H110M-A                     | [6add1ba46c](https://linux-hardware.org/?probe=6add1ba46c) | Dec 27, 2023 |
| MSI           | Z97 GAMING 5                | [3b0901d1a4](https://linux-hardware.org/?probe=3b0901d1a4) | Dec 27, 2023 |
| Medion        | MS-7748                     | [029849e475](https://linux-hardware.org/?probe=029849e475) | Dec 27, 2023 |
| ASUSTek       | H81M-E                      | [55173f5056](https://linux-hardware.org/?probe=55173f5056) | Dec 26, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [8c5b941b48](https://linux-hardware.org/?probe=8c5b941b48) | Dec 26, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [0535c48b0a](https://linux-hardware.org/?probe=0535c48b0a) | Dec 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [a8007743a8](https://linux-hardware.org/?probe=a8007743a8) | Dec 25, 2023 |
| Gigabyte      | H61M-S2PV                   | [2825577fd0](https://linux-hardware.org/?probe=2825577fd0) | Dec 25, 2023 |
| MSI           | H110M PRO-VD                | [624b1cbd0b](https://linux-hardware.org/?probe=624b1cbd0b) | Dec 24, 2023 |
| Medion        | MS-7748                     | [4df862d09e](https://linux-hardware.org/?probe=4df862d09e) | Dec 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0102708c19](https://linux-hardware.org/?probe=0102708c19) | Dec 24, 2023 |
| MSI           | H110M PRO-VD                | [121d2e0b06](https://linux-hardware.org/?probe=121d2e0b06) | Dec 24, 2023 |
| ASUSTek       | H110M-A                     | [63306d22b2](https://linux-hardware.org/?probe=63306d22b2) | Dec 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [a32ea319ca](https://linux-hardware.org/?probe=a32ea319ca) | Dec 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [852693eb71](https://linux-hardware.org/?probe=852693eb71) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [544fdd3054](https://linux-hardware.org/?probe=544fdd3054) | Dec 21, 2023 |
| ASUSTek       | H110M-A                     | [3b149d0e20](https://linux-hardware.org/?probe=3b149d0e20) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | [0f7957917e](https://linux-hardware.org/?probe=0f7957917e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [ae2fef5c99](https://linux-hardware.org/?probe=ae2fef5c99) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| ASRock        | B450M-HDV R4.0              | [02d834a147](https://linux-hardware.org/?probe=02d834a147) | Dec 19, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [d688c80ef7](https://linux-hardware.org/?probe=d688c80ef7) | Dec 18, 2023 |
| ASRock        | B450M-HDV R4.0              | [da0af8ac25](https://linux-hardware.org/?probe=da0af8ac25) | Dec 18, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [b4c4267477](https://linux-hardware.org/?probe=b4c4267477) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [4302968166](https://linux-hardware.org/?probe=4302968166) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0eb62b79e1](https://linux-hardware.org/?probe=0eb62b79e1) | Dec 17, 2023 |
| HP            | 1497                        | [20ba1e3df2](https://linux-hardware.org/?probe=20ba1e3df2) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [2262526770](https://linux-hardware.org/?probe=2262526770) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [ed366a10ca](https://linux-hardware.org/?probe=ed366a10ca) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | [9b32bafcb5](https://linux-hardware.org/?probe=9b32bafcb5) | Dec 17, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [6d3774729f](https://linux-hardware.org/?probe=6d3774729f) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | [24522df925](https://linux-hardware.org/?probe=24522df925) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | [528bd3903d](https://linux-hardware.org/?probe=528bd3903d) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | [e93c46f2e9](https://linux-hardware.org/?probe=e93c46f2e9) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | [25eb2af58f](https://linux-hardware.org/?probe=25eb2af58f) | Dec 16, 2023 |
| Lenovo        | 1036 NO DPK                 | [08f10e4a70](https://linux-hardware.org/?probe=08f10e4a70) | Dec 15, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [7701847681](https://linux-hardware.org/?probe=7701847681) | Dec 15, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [470281aedd](https://linux-hardware.org/?probe=470281aedd) | Dec 15, 2023 |
| HP            | 0B4Ch D                     | [e40498b1d1](https://linux-hardware.org/?probe=e40498b1d1) | Dec 14, 2023 |
| HP            | 0B4Ch D                     | [bb8a731dab](https://linux-hardware.org/?probe=bb8a731dab) | Dec 14, 2023 |
| ASRock        | B550M Pro4                  | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | [02b6b32440](https://linux-hardware.org/?probe=02b6b32440) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | [016f269490](https://linux-hardware.org/?probe=016f269490) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [d55fed29c1](https://linux-hardware.org/?probe=d55fed29c1) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [fc0fe04fab](https://linux-hardware.org/?probe=fc0fe04fab) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| HP            | 1495                        | [9fb4cb4ac8](https://linux-hardware.org/?probe=9fb4cb4ac8) | Dec 12, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [2199e3dc0f](https://linux-hardware.org/?probe=2199e3dc0f) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | [3184d3c38b](https://linux-hardware.org/?probe=3184d3c38b) | Dec 11, 2023 |
| HP            | 3033h                       | [3dddd6881a](https://linux-hardware.org/?probe=3dddd6881a) | Dec 11, 2023 |
| HP            | 802E                        | [606309324b](https://linux-hardware.org/?probe=606309324b) | Dec 11, 2023 |
| Gigabyte      | H61MA-D3V                   | [1b2d2135d4](https://linux-hardware.org/?probe=1b2d2135d4) | Dec 09, 2023 |
| Intel         | DH61CR AAG14064-204         | [a319465535](https://linux-hardware.org/?probe=a319465535) | Dec 09, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdff414c43](https://linux-hardware.org/?probe=bdff414c43) | Dec 09, 2023 |
| MSI           | H110M PRO-VD                | [a691f52012](https://linux-hardware.org/?probe=a691f52012) | Dec 08, 2023 |
| MSI           | H110M PRO-VD                | [aa3ae99bf2](https://linux-hardware.org/?probe=aa3ae99bf2) | Dec 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [6be53926db](https://linux-hardware.org/?probe=6be53926db) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [1c2750202f](https://linux-hardware.org/?probe=1c2750202f) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ba4f3255bc](https://linux-hardware.org/?probe=ba4f3255bc) | Dec 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ae2fdd9470](https://linux-hardware.org/?probe=ae2fdd9470) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [dc50493c88](https://linux-hardware.org/?probe=dc50493c88) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [9f5a520013](https://linux-hardware.org/?probe=9f5a520013) | Dec 08, 2023 |
| ASUSTek       | PRIME A520M-K               | [a6f429594d](https://linux-hardware.org/?probe=a6f429594d) | Dec 07, 2023 |
| Dell          | 0TY565                      | [f037c10bc9](https://linux-hardware.org/?probe=f037c10bc9) | Dec 07, 2023 |
| HP            | 09F8h                       | [c988ff1e96](https://linux-hardware.org/?probe=c988ff1e96) | Dec 07, 2023 |
| MSI           | B460M PRO                   | [107b14c2d9](https://linux-hardware.org/?probe=107b14c2d9) | Dec 06, 2023 |
| Medion        | MS-7748                     | [1f11eab8f8](https://linux-hardware.org/?probe=1f11eab8f8) | Dec 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [e9436c2809](https://linux-hardware.org/?probe=e9436c2809) | Dec 06, 2023 |
| ASUSTek       | H110M-K                     | [2ebb7abc4c](https://linux-hardware.org/?probe=2ebb7abc4c) | Dec 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d658b900e7](https://linux-hardware.org/?probe=d658b900e7) | Dec 05, 2023 |
| HP            | 1495                        | [626fcfb788](https://linux-hardware.org/?probe=626fcfb788) | Dec 05, 2023 |
| Medion        | MS-7748                     | [8c5106d00b](https://linux-hardware.org/?probe=8c5106d00b) | Dec 05, 2023 |
| Gigabyte      | Z390 UD V2                  | [2d85fb4799](https://linux-hardware.org/?probe=2d85fb4799) | Dec 05, 2023 |
| ASRock        | 960GC-GS FX                 | [524de55da0](https://linux-hardware.org/?probe=524de55da0) | Dec 04, 2023 |
| HP            | 339A                        | [b596b82bf1](https://linux-hardware.org/?probe=b596b82bf1) | Dec 04, 2023 |
| Dell          | 0PU052                      | [a436be0e88](https://linux-hardware.org/?probe=a436be0e88) | Dec 04, 2023 |
| ASRock        | H310CM-DVS                  | [1bf52989ef](https://linux-hardware.org/?probe=1bf52989ef) | Dec 03, 2023 |
| Gigabyte      | P67A-D3-B3                  | [77472c25c8](https://linux-hardware.org/?probe=77472c25c8) | Dec 03, 2023 |
| ASUSTek       | H110M-K                     | [e21f4b08b1](https://linux-hardware.org/?probe=e21f4b08b1) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| Gigabyte      | B550M DS3H AC               | [62cff9080d](https://linux-hardware.org/?probe=62cff9080d) | Dec 02, 2023 |
| Gigabyte      | GA-870A-UD3                 | [0ae66633bc](https://linux-hardware.org/?probe=0ae66633bc) | Dec 01, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b70c84adcf](https://linux-hardware.org/?probe=b70c84adcf) | Dec 01, 2023 |
| Gigabyte      | A520M S2H                   | [cdfe1883bc](https://linux-hardware.org/?probe=cdfe1883bc) | Nov 30, 2023 |
| HP            | 18E7                        | [845881d2cd](https://linux-hardware.org/?probe=845881d2cd) | Nov 30, 2023 |
| HP            | 18E7                        | [f09d697221](https://linux-hardware.org/?probe=f09d697221) | Nov 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [18ce09355c](https://linux-hardware.org/?probe=18ce09355c) | Nov 28, 2023 |
| ASRock        | B365 Phantom Gaming 4       | [b3de42156e](https://linux-hardware.org/?probe=b3de42156e) | Nov 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | [875f72f0f7](https://linux-hardware.org/?probe=875f72f0f7) | Nov 28, 2023 |
| HP            | 1495                        | [17732cf790](https://linux-hardware.org/?probe=17732cf790) | Nov 28, 2023 |
| Dell          | 0K240Y A01                  | [d5440204b6](https://linux-hardware.org/?probe=d5440204b6) | Nov 28, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [05686c86bb](https://linux-hardware.org/?probe=05686c86bb) | Nov 28, 2023 |
| MSI           | P43i                        | [3291b84f5e](https://linux-hardware.org/?probe=3291b84f5e) | Nov 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [5e1e9b6a9e](https://linux-hardware.org/?probe=5e1e9b6a9e) | Nov 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [77e8b3479a](https://linux-hardware.org/?probe=77e8b3479a) | Nov 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [cd7362b85e](https://linux-hardware.org/?probe=cd7362b85e) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [159ce7eba2](https://linux-hardware.org/?probe=159ce7eba2) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfc194ba14](https://linux-hardware.org/?probe=bfc194ba14) | Nov 27, 2023 |
| ASRock        | B85M                        | [0d3f6ceeea](https://linux-hardware.org/?probe=0d3f6ceeea) | Nov 27, 2023 |
| MSI           | H61M-P21                    | [5c106c49f4](https://linux-hardware.org/?probe=5c106c49f4) | Nov 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [1e0fa8c965](https://linux-hardware.org/?probe=1e0fa8c965) | Nov 27, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [c9dd5240c4](https://linux-hardware.org/?probe=c9dd5240c4) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | [4618c61b6c](https://linux-hardware.org/?probe=4618c61b6c) | Nov 26, 2023 |
| ASRock        | G41M-VS3                    | [c2e61e0cf9](https://linux-hardware.org/?probe=c2e61e0cf9) | Nov 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [200ddef2b0](https://linux-hardware.org/?probe=200ddef2b0) | Nov 26, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [250bd9f1df](https://linux-hardware.org/?probe=250bd9f1df) | Nov 26, 2023 |
| ASRock        | B365 Phantom Gaming 4       | [97dfb05d56](https://linux-hardware.org/?probe=97dfb05d56) | Nov 26, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [61b5003420](https://linux-hardware.org/?probe=61b5003420) | Nov 25, 2023 |
| HP            | 339A                        | [35c70dde9e](https://linux-hardware.org/?probe=35c70dde9e) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [c02d4a69b7](https://linux-hardware.org/?probe=c02d4a69b7) | Nov 25, 2023 |
| Gigabyte      | J4005ND2P-CF                | [04b5574c35](https://linux-hardware.org/?probe=04b5574c35) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [86b63c1acf](https://linux-hardware.org/?probe=86b63c1acf) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [8c071d6cda](https://linux-hardware.org/?probe=8c071d6cda) | Nov 24, 2023 |
| ASRock        | B550M Pro4                  | [4a05411844](https://linux-hardware.org/?probe=4a05411844) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-R               | [cbdb153211](https://linux-hardware.org/?probe=cbdb153211) | Nov 24, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [aed927ecb5](https://linux-hardware.org/?probe=aed927ecb5) | Nov 24, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [977d9e09f1](https://linux-hardware.org/?probe=977d9e09f1) | Nov 23, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [b99f6e4f94](https://linux-hardware.org/?probe=b99f6e4f94) | Nov 23, 2023 |
| HP            | 1494                        | [3ff4bec1f2](https://linux-hardware.org/?probe=3ff4bec1f2) | Nov 23, 2023 |
| HP            | 1495                        | [630e59993e](https://linux-hardware.org/?probe=630e59993e) | Nov 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [3e89253fa2](https://linux-hardware.org/?probe=3e89253fa2) | Nov 22, 2023 |
| Dell          | 0TY565                      | [bf643a514f](https://linux-hardware.org/?probe=bf643a514f) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [667c79209d](https://linux-hardware.org/?probe=667c79209d) | Nov 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [7c048e0f1a](https://linux-hardware.org/?probe=7c048e0f1a) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [32e985afeb](https://linux-hardware.org/?probe=32e985afeb) | Nov 21, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [d2a213e349](https://linux-hardware.org/?probe=d2a213e349) | Nov 21, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [d5cdc3089f](https://linux-hardware.org/?probe=d5cdc3089f) | Nov 21, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e1e3a4bb80](https://linux-hardware.org/?probe=e1e3a4bb80) | Nov 20, 2023 |
| Dell          | 0XPDFK A00                  | [280e97cc34](https://linux-hardware.org/?probe=280e97cc34) | Nov 20, 2023 |
| ASRock        | B550M Pro4                  | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| Gigabyte      | B450M GAMING                | [dbf835efbb](https://linux-hardware.org/?probe=dbf835efbb) | Nov 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [795b0f6741](https://linux-hardware.org/?probe=795b0f6741) | Nov 16, 2023 |
| Dell          | 0TY565                      | [bd5ec5457e](https://linux-hardware.org/?probe=bd5ec5457e) | Nov 16, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [c79a431698](https://linux-hardware.org/?probe=c79a431698) | Nov 15, 2023 |
| Dell          | 05WXFV A03                  | [ecab18e943](https://linux-hardware.org/?probe=ecab18e943) | Nov 14, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d5cb68f63d](https://linux-hardware.org/?probe=d5cb68f63d) | Nov 12, 2023 |
| ASUSTek       | PRIME A320M-R               | [e02cd94d67](https://linux-hardware.org/?probe=e02cd94d67) | Nov 10, 2023 |
| MSI           | H81M-E33                    | [2a5463be7c](https://linux-hardware.org/?probe=2a5463be7c) | Nov 10, 2023 |
| Gigabyte      | Z390 UD V2                  | [2106c14823](https://linux-hardware.org/?probe=2106c14823) | Nov 10, 2023 |
| ASUSTek       | PRIME A320M-R               | [ce2c43cb86](https://linux-hardware.org/?probe=ce2c43cb86) | Nov 10, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [f45397a161](https://linux-hardware.org/?probe=f45397a161) | Nov 09, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [5e0d19391e](https://linux-hardware.org/?probe=5e0d19391e) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-A               | [1399a1f267](https://linux-hardware.org/?probe=1399a1f267) | Nov 09, 2023 |
| Gigabyte      | Z390 UD V2                  | [7cdb83cd7a](https://linux-hardware.org/?probe=7cdb83cd7a) | Nov 09, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [4c8dc5f59a](https://linux-hardware.org/?probe=4c8dc5f59a) | Nov 08, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [420d0d1ddc](https://linux-hardware.org/?probe=420d0d1ddc) | Nov 08, 2023 |
| Dell          | 02YYK5 A01                  | [e475e8c7d9](https://linux-hardware.org/?probe=e475e8c7d9) | Nov 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [ae88c578fa](https://linux-hardware.org/?probe=ae88c578fa) | Nov 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9c7020c9cc](https://linux-hardware.org/?probe=9c7020c9cc) | Nov 08, 2023 |
| Lenovo        | SDK0E50510 WIN              | [72a7ba6dde](https://linux-hardware.org/?probe=72a7ba6dde) | Nov 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [813b0c06e0](https://linux-hardware.org/?probe=813b0c06e0) | Nov 08, 2023 |
| Dell          | 0TY565                      | [086bd4ec8f](https://linux-hardware.org/?probe=086bd4ec8f) | Nov 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [6e0b8b9df9](https://linux-hardware.org/?probe=6e0b8b9df9) | Nov 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [038e8719ec](https://linux-hardware.org/?probe=038e8719ec) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | [1e59a67f24](https://linux-hardware.org/?probe=1e59a67f24) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| HP            | 8265                        | [f6b38e869b](https://linux-hardware.org/?probe=f6b38e869b) | Nov 04, 2023 |
| HP            | 8265                        | [49cb61db2e](https://linux-hardware.org/?probe=49cb61db2e) | Nov 04, 2023 |
| Dell          | 0VHWTR A02                  | [7663b608dd](https://linux-hardware.org/?probe=7663b608dd) | Nov 03, 2023 |
| Gigabyte      | H61M-S1                     | [3b14b40bc9](https://linux-hardware.org/?probe=3b14b40bc9) | Nov 02, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [41d5ec4633](https://linux-hardware.org/?probe=41d5ec4633) | Nov 02, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [dacdb79776](https://linux-hardware.org/?probe=dacdb79776) | Nov 01, 2023 |
| Gigabyte      | H61M-DS2                    | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| Gigabyte      | EP31-DS3L                   | [0a33a8b925](https://linux-hardware.org/?probe=0a33a8b925) | Nov 01, 2023 |
| MSI           | P43i                        | [847f1890e2](https://linux-hardware.org/?probe=847f1890e2) | Nov 01, 2023 |
| ASRock        | X570M Pro4                  | [ad5e8f91e5](https://linux-hardware.org/?probe=ad5e8f91e5) | Nov 01, 2023 |
| ASRock        | G41M-VS3                    | [1d5b98622d](https://linux-hardware.org/?probe=1d5b98622d) | Oct 31, 2023 |
| ASRock        | G41M-VS3                    | [1a0da2bf85](https://linux-hardware.org/?probe=1a0da2bf85) | Oct 31, 2023 |
| Gigabyte      | H81M-HD3                    | [5f6ce5dbfb](https://linux-hardware.org/?probe=5f6ce5dbfb) | Oct 31, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [4cf4e845eb](https://linux-hardware.org/?probe=4cf4e845eb) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [1813899897](https://linux-hardware.org/?probe=1813899897) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [6cf499a771](https://linux-hardware.org/?probe=6cf499a771) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [2a5fda7baf](https://linux-hardware.org/?probe=2a5fda7baf) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [7d99dba1af](https://linux-hardware.org/?probe=7d99dba1af) | Oct 30, 2023 |
| ASUSTek       | H81M-E                      | [b48b015b4c](https://linux-hardware.org/?probe=b48b015b4c) | Oct 29, 2023 |
| ASRock        | AM1B-M                      | [098a155bab](https://linux-hardware.org/?probe=098a155bab) | Oct 29, 2023 |
| Dell          | 0HHV7N A00                  | [85e507b8b2](https://linux-hardware.org/?probe=85e507b8b2) | Oct 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [2c3cefb71a](https://linux-hardware.org/?probe=2c3cefb71a) | Oct 28, 2023 |
| MSI           | MS-7817                     | [06344ac320](https://linux-hardware.org/?probe=06344ac320) | Oct 27, 2023 |
| MSI           | MS-7817                     | [dc9cc99096](https://linux-hardware.org/?probe=dc9cc99096) | Oct 27, 2023 |
| ASUSTek       | PRIME A320M-R               | [0306fca319](https://linux-hardware.org/?probe=0306fca319) | Oct 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [b58a3b7e3a](https://linux-hardware.org/?probe=b58a3b7e3a) | Oct 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [220d49592e](https://linux-hardware.org/?probe=220d49592e) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [64693f6b03](https://linux-hardware.org/?probe=64693f6b03) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [7a96d2e495](https://linux-hardware.org/?probe=7a96d2e495) | Oct 26, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [828dbad92c](https://linux-hardware.org/?probe=828dbad92c) | Oct 25, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [4f6c606196](https://linux-hardware.org/?probe=4f6c606196) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7e2c80a1d7](https://linux-hardware.org/?probe=7e2c80a1d7) | Oct 24, 2023 |
| HP            | 339A                        | [119fec0a9d](https://linux-hardware.org/?probe=119fec0a9d) | Oct 24, 2023 |
| HP            | 339A                        | [b35bc69c82](https://linux-hardware.org/?probe=b35bc69c82) | Oct 24, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [50bdbf100d](https://linux-hardware.org/?probe=50bdbf100d) | Oct 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3824135292](https://linux-hardware.org/?probe=3824135292) | Oct 23, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [875d62cbac](https://linux-hardware.org/?probe=875d62cbac) | Oct 23, 2023 |
| ASRock        | B760M PG Riptide            | [d1f12415b9](https://linux-hardware.org/?probe=d1f12415b9) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [3eafc2c647](https://linux-hardware.org/?probe=3eafc2c647) | Oct 21, 2023 |
| Dell          | 0D883F A06                  | [f687230e43](https://linux-hardware.org/?probe=f687230e43) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| ASRock        | B450 Steel Legend           | [d3036ca319](https://linux-hardware.org/?probe=d3036ca319) | Oct 20, 2023 |
| HP            | 3397                        | [7622910000](https://linux-hardware.org/?probe=7622910000) | Oct 20, 2023 |
| ASUSTek       | H110M-A                     | [2cff132417](https://linux-hardware.org/?probe=2cff132417) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [dad965a109](https://linux-hardware.org/?probe=dad965a109) | Oct 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [0733e9c4ae](https://linux-hardware.org/?probe=0733e9c4ae) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [8ca65eabee](https://linux-hardware.org/?probe=8ca65eabee) | Oct 19, 2023 |
| MSI           | H61M-P21                    | [ba5fb8f49c](https://linux-hardware.org/?probe=ba5fb8f49c) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [330170d5d7](https://linux-hardware.org/?probe=330170d5d7) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [e6840ccb2f](https://linux-hardware.org/?probe=e6840ccb2f) | Oct 19, 2023 |
| Dell          | 0K240Y A01                  | [e57b8986ab](https://linux-hardware.org/?probe=e57b8986ab) | Oct 18, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| Gigabyte      | J4005ND2P-CF                | [23efcaf7a2](https://linux-hardware.org/?probe=23efcaf7a2) | Oct 18, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [ce65c73e40](https://linux-hardware.org/?probe=ce65c73e40) | Oct 18, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [c9f674352d](https://linux-hardware.org/?probe=c9f674352d) | Oct 17, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [64e28141f8](https://linux-hardware.org/?probe=64e28141f8) | Oct 17, 2023 |
| HP            | 8265                        | [4e8e0ea26a](https://linux-hardware.org/?probe=4e8e0ea26a) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9e3034f710](https://linux-hardware.org/?probe=9e3034f710) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [ea34b890ed](https://linux-hardware.org/?probe=ea34b890ed) | Oct 17, 2023 |
| HP            | 8265                        | [8f4c84f4f4](https://linux-hardware.org/?probe=8f4c84f4f4) | Oct 16, 2023 |
| Gigabyte      | MFLP3CP-00                  | [e2ddb858a9](https://linux-hardware.org/?probe=e2ddb858a9) | Oct 16, 2023 |
| ASUSTek       | PRIME B365M-A               | [b7fb2c5300](https://linux-hardware.org/?probe=b7fb2c5300) | Oct 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [707b8c0acd](https://linux-hardware.org/?probe=707b8c0acd) | Oct 15, 2023 |
| ASUSTek       | PRIME B365M-A               | [59a2975041](https://linux-hardware.org/?probe=59a2975041) | Oct 15, 2023 |
| HP            | 2820h                       | [6b9bbe3a64](https://linux-hardware.org/?probe=6b9bbe3a64) | Oct 15, 2023 |
| ASUSTek       | P8B75-M                     | [7fba4999fa](https://linux-hardware.org/?probe=7fba4999fa) | Oct 12, 2023 |
| ASRock        | H310CM-DVS                  | [1ae8fcd28c](https://linux-hardware.org/?probe=1ae8fcd28c) | Oct 12, 2023 |
| Medion        | MS-7748                     | [8b625acaae](https://linux-hardware.org/?probe=8b625acaae) | Oct 12, 2023 |
| Pegatron      | 2AB6                        | [50fbeed34d](https://linux-hardware.org/?probe=50fbeed34d) | Oct 11, 2023 |
| Pegatron      | 2AB6                        | [e97e82006c](https://linux-hardware.org/?probe=e97e82006c) | Oct 11, 2023 |
| Dell          | 0D883F A06                  | [d1e2846467](https://linux-hardware.org/?probe=d1e2846467) | Oct 11, 2023 |
| HP            | 0AA8h                       | [5b821194a7](https://linux-hardware.org/?probe=5b821194a7) | Oct 11, 2023 |
| Lenovo        | MAHOBAY NOK                 | [83ed978b53](https://linux-hardware.org/?probe=83ed978b53) | Oct 11, 2023 |
| HP            | 0AA8h                       | [d88c5dced7](https://linux-hardware.org/?probe=d88c5dced7) | Oct 11, 2023 |
| MSI           | MS-7817                     | [ed5e21c562](https://linux-hardware.org/?probe=ed5e21c562) | Oct 10, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [abca75fa11](https://linux-hardware.org/?probe=abca75fa11) | Oct 10, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [2cba957b98](https://linux-hardware.org/?probe=2cba957b98) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [be9975c532](https://linux-hardware.org/?probe=be9975c532) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [c3d3003248](https://linux-hardware.org/?probe=c3d3003248) | Oct 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | [d935714c39](https://linux-hardware.org/?probe=d935714c39) | Oct 08, 2023 |
| HP            | ProLiant MicroServer        | [1c7c472122](https://linux-hardware.org/?probe=1c7c472122) | Oct 07, 2023 |
| MSI           | H97 GUARD-PRO               | [ffb2b71ce7](https://linux-hardware.org/?probe=ffb2b71ce7) | Oct 07, 2023 |
| ASUSTek       | H110M-K                     | [5fad8d4e39](https://linux-hardware.org/?probe=5fad8d4e39) | Oct 07, 2023 |
| MSI           | H97 GUARD-PRO               | [047ec55668](https://linux-hardware.org/?probe=047ec55668) | Oct 07, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [29adc32704](https://linux-hardware.org/?probe=29adc32704) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | [ef1dd349c2](https://linux-hardware.org/?probe=ef1dd349c2) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | [168713fd05](https://linux-hardware.org/?probe=168713fd05) | Oct 07, 2023 |
| ASUSTek       | PRIME A320M-R               | [2043b1ed85](https://linux-hardware.org/?probe=2043b1ed85) | Oct 07, 2023 |
| Gigabyte      | H61MA-D3V                   | [53f61c91bf](https://linux-hardware.org/?probe=53f61c91bf) | Oct 07, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ceaac5726a](https://linux-hardware.org/?probe=ceaac5726a) | Oct 07, 2023 |
| ASUSTek       | H110M-A                     | [a2cc2d051e](https://linux-hardware.org/?probe=a2cc2d051e) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | [c585e7e5c4](https://linux-hardware.org/?probe=c585e7e5c4) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | [276b8cea5f](https://linux-hardware.org/?probe=276b8cea5f) | Oct 06, 2023 |
| Medion        | MS-7748                     | [01b345394a](https://linux-hardware.org/?probe=01b345394a) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [9e00c6f4b0](https://linux-hardware.org/?probe=9e00c6f4b0) | Oct 06, 2023 |
| HP            | 8265                        | [6fffe02648](https://linux-hardware.org/?probe=6fffe02648) | Oct 05, 2023 |
| HP            | 8265                        | [fe09b6a8e0](https://linux-hardware.org/?probe=fe09b6a8e0) | Oct 04, 2023 |
| ASUSTek       | PRIME A320M-R               | [d247c129c4](https://linux-hardware.org/?probe=d247c129c4) | Oct 04, 2023 |
| HP            | 1825                        | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [d6cc456788](https://linux-hardware.org/?probe=d6cc456788) | Oct 04, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [78c456d55d](https://linux-hardware.org/?probe=78c456d55d) | Oct 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [74c8e5eadf](https://linux-hardware.org/?probe=74c8e5eadf) | Oct 03, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [2c0427d154](https://linux-hardware.org/?probe=2c0427d154) | Oct 03, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [0a765bb242](https://linux-hardware.org/?probe=0a765bb242) | Oct 03, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [ee08a8d73a](https://linux-hardware.org/?probe=ee08a8d73a) | Oct 02, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [913fafd8a7](https://linux-hardware.org/?probe=913fafd8a7) | Oct 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | [c64f3bbdbd](https://linux-hardware.org/?probe=c64f3bbdbd) | Oct 02, 2023 |
| HP            | 1494                        | [1c5842d2b7](https://linux-hardware.org/?probe=1c5842d2b7) | Oct 01, 2023 |
| HP            | 1494                        | [4ffbf86079](https://linux-hardware.org/?probe=4ffbf86079) | Oct 01, 2023 |
| HP            | 8298                        | [0f73d73d00](https://linux-hardware.org/?probe=0f73d73d00) | Oct 01, 2023 |
| HP            | 339A                        | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| HP            | 1494                        | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| Gigabyte      | H110M-S2H-CF                | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| ASRock        | B550M Pro4                  | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| ASUSTek       | D700MD                      | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| Lenovo        | ThinkServer TS440           | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [4cbe33187c](https://linux-hardware.org/?probe=4cbe33187c) | Sep 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [a3fc0915cd](https://linux-hardware.org/?probe=a3fc0915cd) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [3ffed1f144](https://linux-hardware.org/?probe=3ffed1f144) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [e6eff7d60d](https://linux-hardware.org/?probe=e6eff7d60d) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [263bf34c40](https://linux-hardware.org/?probe=263bf34c40) | Sep 25, 2023 |
| MSI           | B85M-E33                    | [1e246dda8b](https://linux-hardware.org/?probe=1e246dda8b) | Sep 25, 2023 |
| HP            | 09F8h                       | [3d8c4a9ace](https://linux-hardware.org/?probe=3d8c4a9ace) | Sep 25, 2023 |
| HP            | 09F8h                       | [f844e52238](https://linux-hardware.org/?probe=f844e52238) | Sep 25, 2023 |
| HP            | 09F8h                       | [d2ade2ea70](https://linux-hardware.org/?probe=d2ade2ea70) | Sep 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f94c540fde](https://linux-hardware.org/?probe=f94c540fde) | Sep 24, 2023 |
| ASRock        | G41M-VS3                    | [1dd60939d2](https://linux-hardware.org/?probe=1dd60939d2) | Sep 24, 2023 |
| ASUSTek       | PRIME B365M-A               | [ce1b08cdf9](https://linux-hardware.org/?probe=ce1b08cdf9) | Sep 23, 2023 |
| Gigabyte      | H110N-CF                    | [7655a31997](https://linux-hardware.org/?probe=7655a31997) | Sep 23, 2023 |
| HP            | 1497                        | [cbbd6a0182](https://linux-hardware.org/?probe=cbbd6a0182) | Sep 23, 2023 |
| MSI           | MS-7309                     | [356be353d5](https://linux-hardware.org/?probe=356be353d5) | Sep 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [b519a4adea](https://linux-hardware.org/?probe=b519a4adea) | Sep 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [8d7c00fcd2](https://linux-hardware.org/?probe=8d7c00fcd2) | Sep 23, 2023 |
| Gigabyte      | A520M S2H                   | [134cfff173](https://linux-hardware.org/?probe=134cfff173) | Sep 22, 2023 |
| ASRock        | B550M Pro4                  | [daa9128e32](https://linux-hardware.org/?probe=daa9128e32) | Sep 22, 2023 |
| Gigabyte      | H97-D3H-CF                  | [61ce9ed478](https://linux-hardware.org/?probe=61ce9ed478) | Sep 22, 2023 |
| Gigabyte      | H110M-S2V-CF                | [96ba82f38e](https://linux-hardware.org/?probe=96ba82f38e) | Sep 22, 2023 |
| Gigabyte      | EP31-DS3L                   | [701abaeb8f](https://linux-hardware.org/?probe=701abaeb8f) | Sep 22, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [ff935c4dbe](https://linux-hardware.org/?probe=ff935c4dbe) | Sep 22, 2023 |
| ASRock        | B85M                        | [5b78620442](https://linux-hardware.org/?probe=5b78620442) | Sep 22, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [60976010ac](https://linux-hardware.org/?probe=60976010ac) | Sep 21, 2023 |
| ASUSTek       | H110M-A                     | [b21f53b9e1](https://linux-hardware.org/?probe=b21f53b9e1) | Sep 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d1b966125a](https://linux-hardware.org/?probe=d1b966125a) | Sep 21, 2023 |
| ASUSTek       | PRIME Z370-A II             | [d348acd6c8](https://linux-hardware.org/?probe=d348acd6c8) | Sep 21, 2023 |
| Lenovo        | SDK0E50510 WIN              | [6b9f9348c0](https://linux-hardware.org/?probe=6b9f9348c0) | Sep 21, 2023 |
| HP            | 1495                        | [9c5926d73b](https://linux-hardware.org/?probe=9c5926d73b) | Sep 21, 2023 |
| Gigabyte      | J4005ND2P-CF                | [f3deee7792](https://linux-hardware.org/?probe=f3deee7792) | Sep 20, 2023 |
| Lenovo        | 1730-A1G                    | [9f9580c81f](https://linux-hardware.org/?probe=9f9580c81f) | Sep 19, 2023 |
| HP            | 8298                        | [006592d87f](https://linux-hardware.org/?probe=006592d87f) | Sep 19, 2023 |
| Lenovo        | 1730-A1G                    | [e58cd05ca6](https://linux-hardware.org/?probe=e58cd05ca6) | Sep 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | [12a4225b04](https://linux-hardware.org/?probe=12a4225b04) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | [851a7301bc](https://linux-hardware.org/?probe=851a7301bc) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | [8ee590e888](https://linux-hardware.org/?probe=8ee590e888) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | [42ade99539](https://linux-hardware.org/?probe=42ade99539) | Sep 18, 2023 |
| HP            | 1494                        | [f7dcc5924c](https://linux-hardware.org/?probe=f7dcc5924c) | Sep 17, 2023 |
| HP            | 1494                        | [35c90d3fb2](https://linux-hardware.org/?probe=35c90d3fb2) | Sep 17, 2023 |
| AZW           | U59                         | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | [92ff22e072](https://linux-hardware.org/?probe=92ff22e072) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | [7d679bbf7f](https://linux-hardware.org/?probe=7d679bbf7f) | Sep 17, 2023 |
| Dell          | 0VHWTR A02                  | [c34520d1c2](https://linux-hardware.org/?probe=c34520d1c2) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | [ae9c2e3978](https://linux-hardware.org/?probe=ae9c2e3978) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | [8076be0adb](https://linux-hardware.org/?probe=8076be0adb) | Sep 16, 2023 |
| Dell          | 0K240Y A01                  | [bd5fae0639](https://linux-hardware.org/?probe=bd5fae0639) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | [781590255d](https://linux-hardware.org/?probe=781590255d) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | [382acd4186](https://linux-hardware.org/?probe=382acd4186) | Sep 15, 2023 |
| Gigabyte      | P67A-D3-B3                  | [14a4828110](https://linux-hardware.org/?probe=14a4828110) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| HP            | 8265                        | [1e16a47683](https://linux-hardware.org/?probe=1e16a47683) | Sep 13, 2023 |
| ASRock        | G41M-VS3                    | [bc19e0cdbb](https://linux-hardware.org/?probe=bc19e0cdbb) | Sep 13, 2023 |
| Dell          | 02N3WF A01                  | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| Dell          | 0HY9JP A02                  | [ef0bc2bd79](https://linux-hardware.org/?probe=ef0bc2bd79) | Sep 12, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [60b271e896](https://linux-hardware.org/?probe=60b271e896) | Sep 11, 2023 |
| HP            | 8265                        | [f7e98e0f58](https://linux-hardware.org/?probe=f7e98e0f58) | Sep 10, 2023 |
| HP            | 3047h                       | [1070c2f57a](https://linux-hardware.org/?probe=1070c2f57a) | Sep 10, 2023 |
| HP            | 3047h                       | [746e154eaf](https://linux-hardware.org/?probe=746e154eaf) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | [31f5d64453](https://linux-hardware.org/?probe=31f5d64453) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | [625c711748](https://linux-hardware.org/?probe=625c711748) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9c9441fa1c](https://linux-hardware.org/?probe=9c9441fa1c) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2706096498](https://linux-hardware.org/?probe=2706096498) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| HP            | 339A                        | [f19d37b028](https://linux-hardware.org/?probe=f19d37b028) | Sep 10, 2023 |
| HP            | 339A                        | [794685ff75](https://linux-hardware.org/?probe=794685ff75) | Sep 10, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| AZW           | U59                         | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| HP            | 1497                        | [e420bbd661](https://linux-hardware.org/?probe=e420bbd661) | Sep 09, 2023 |
| HP            | 1497                        | [6de463b204](https://linux-hardware.org/?probe=6de463b204) | Sep 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [8a383606e3](https://linux-hardware.org/?probe=8a383606e3) | Sep 08, 2023 |
| MSI           | FM2-A85XMA-E35              | [ea1d2d5910](https://linux-hardware.org/?probe=ea1d2d5910) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Gigabyte      | A520M S2H                   | [49adfda956](https://linux-hardware.org/?probe=49adfda956) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| ASUSTek       | PRIME B365M-A               | [898930f2b1](https://linux-hardware.org/?probe=898930f2b1) | Sep 07, 2023 |
| Gigabyte      | A520M S2H                   | [132fa17be7](https://linux-hardware.org/?probe=132fa17be7) | Sep 06, 2023 |
| Gigabyte      | A520M S2H                   | [36e10816ea](https://linux-hardware.org/?probe=36e10816ea) | Sep 06, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [c19df6a939](https://linux-hardware.org/?probe=c19df6a939) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Huanan        | X99-QD4 V1.0                | [86a4e0d5b8](https://linux-hardware.org/?probe=86a4e0d5b8) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | [d729a17611](https://linux-hardware.org/?probe=d729a17611) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | [857d41cc6a](https://linux-hardware.org/?probe=857d41cc6a) | Sep 06, 2023 |
| ASUSTek       | PRIME B365M-A               | [65bbed09ce](https://linux-hardware.org/?probe=65bbed09ce) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Gigabyte      | H61M-S1                     | [8f2ba921b5](https://linux-hardware.org/?probe=8f2ba921b5) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | [6d7631e83a](https://linux-hardware.org/?probe=6d7631e83a) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | [304ccb5f7e](https://linux-hardware.org/?probe=304ccb5f7e) | Sep 05, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [6d1d81c7b3](https://linux-hardware.org/?probe=6d1d81c7b3) | Sep 05, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [4297e9f110](https://linux-hardware.org/?probe=4297e9f110) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | [e6eb36b583](https://linux-hardware.org/?probe=e6eb36b583) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | [7647c25446](https://linux-hardware.org/?probe=7647c25446) | Sep 05, 2023 |
| Huanan        | X99-QD4 V1.0                | [9051992ac5](https://linux-hardware.org/?probe=9051992ac5) | Sep 05, 2023 |
| HP            | 1495                        | [272f11edff](https://linux-hardware.org/?probe=272f11edff) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| Dell          | 0VHWTR A02                  | [8e4830d581](https://linux-hardware.org/?probe=8e4830d581) | Sep 04, 2023 |
| MSI           | H61M-P21                    | [9eddb8442b](https://linux-hardware.org/?probe=9eddb8442b) | Sep 04, 2023 |
| Dell          | 0TY565                      | [c1a456e342](https://linux-hardware.org/?probe=c1a456e342) | Sep 04, 2023 |
| MSI           | B85M-E33                    | [13b7edd351](https://linux-hardware.org/?probe=13b7edd351) | Sep 04, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [6dd9f72144](https://linux-hardware.org/?probe=6dd9f72144) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Gigabyte      | A520M S2H                   | [a6957d8672](https://linux-hardware.org/?probe=a6957d8672) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | [8bbf469df8](https://linux-hardware.org/?probe=8bbf469df8) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [c450c306b1](https://linux-hardware.org/?probe=c450c306b1) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [f56611f610](https://linux-hardware.org/?probe=f56611f610) | Sep 03, 2023 |
| AZW           | U59                         | [98e1e109a5](https://linux-hardware.org/?probe=98e1e109a5) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [29553c1c51](https://linux-hardware.org/?probe=29553c1c51) | Sep 03, 2023 |
| Huanan        | X99-QD4 V1.0                | [adaa4a1718](https://linux-hardware.org/?probe=adaa4a1718) | Sep 02, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [b6a5325068](https://linux-hardware.org/?probe=b6a5325068) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | [ab9746582a](https://linux-hardware.org/?probe=ab9746582a) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | [091c787432](https://linux-hardware.org/?probe=091c787432) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [f8bb43e243](https://linux-hardware.org/?probe=f8bb43e243) | Sep 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e705d0ef10](https://linux-hardware.org/?probe=e705d0ef10) | Sep 01, 2023 |
| ASRock        | H81M-HDS                    | [d5df2de977](https://linux-hardware.org/?probe=d5df2de977) | Sep 01, 2023 |
| Gigabyte      | H110M-S2H-CF                | [e3bd6a8273](https://linux-hardware.org/?probe=e3bd6a8273) | Aug 31, 2023 |
| Gigabyte      | H110M-S2H-CF                | [37523b5aa3](https://linux-hardware.org/?probe=37523b5aa3) | Aug 31, 2023 |
| MSI           | MS-7817                     | [badd4016f3](https://linux-hardware.org/?probe=badd4016f3) | Aug 31, 2023 |
| HP            | 339A                        | [4b43fa6951](https://linux-hardware.org/?probe=4b43fa6951) | Aug 31, 2023 |
| MSI           | P43i                        | [b7c88acd7e](https://linux-hardware.org/?probe=b7c88acd7e) | Aug 31, 2023 |
| HP            | 0B4Ch D                     | [47cb0a10f7](https://linux-hardware.org/?probe=47cb0a10f7) | Aug 31, 2023 |
| Dell          | 0TY915                      | [5ad1572cf2](https://linux-hardware.org/?probe=5ad1572cf2) | Aug 31, 2023 |
| Dell          | 0TY915                      | [e66372d79b](https://linux-hardware.org/?probe=e66372d79b) | Aug 31, 2023 |
| Dell          | 0XPDFK A00                  | [b7df67e39a](https://linux-hardware.org/?probe=b7df67e39a) | Aug 31, 2023 |
| HP            | 8265                        | [2c26b2823c](https://linux-hardware.org/?probe=2c26b2823c) | Aug 30, 2023 |
| Dell          | 0DR845                      | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [ebfb32e1a8](https://linux-hardware.org/?probe=ebfb32e1a8) | Aug 29, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [cc92a730bc](https://linux-hardware.org/?probe=cc92a730bc) | Aug 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [33fbfa4413](https://linux-hardware.org/?probe=33fbfa4413) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | [8a109f7691](https://linux-hardware.org/?probe=8a109f7691) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | [c806d70c9d](https://linux-hardware.org/?probe=c806d70c9d) | Aug 29, 2023 |
| ASUSTek       | H110M-K                     | [3869234a03](https://linux-hardware.org/?probe=3869234a03) | Aug 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ebf28922af](https://linux-hardware.org/?probe=ebf28922af) | Aug 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [39db55a5e2](https://linux-hardware.org/?probe=39db55a5e2) | Aug 28, 2023 |
| HP            | 339A                        | [56775507f8](https://linux-hardware.org/?probe=56775507f8) | Aug 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | [21b85ec9f3](https://linux-hardware.org/?probe=21b85ec9f3) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | [9b898e43e7](https://linux-hardware.org/?probe=9b898e43e7) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | [43c8f5f7bd](https://linux-hardware.org/?probe=43c8f5f7bd) | Aug 28, 2023 |
| ASUSTek       | H110M-A                     | [c7ee25be08](https://linux-hardware.org/?probe=c7ee25be08) | Aug 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [579e64039e](https://linux-hardware.org/?probe=579e64039e) | Aug 27, 2023 |
| ASRock        | B85M                        | [e1030ad449](https://linux-hardware.org/?probe=e1030ad449) | Aug 27, 2023 |
| ASUSTek       | H110M-K                     | [bfaf77795d](https://linux-hardware.org/?probe=bfaf77795d) | Aug 27, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [7a3378b6eb](https://linux-hardware.org/?probe=7a3378b6eb) | Aug 27, 2023 |
| HP            | 3047h                       | [28037f3ded](https://linux-hardware.org/?probe=28037f3ded) | Aug 26, 2023 |
| HP            | 3047h                       | [dd6e5ce100](https://linux-hardware.org/?probe=dd6e5ce100) | Aug 26, 2023 |
| HP            | 8265                        | [39f6952188](https://linux-hardware.org/?probe=39f6952188) | Aug 26, 2023 |
| ASRock        | B85M                        | [70af81b1a1](https://linux-hardware.org/?probe=70af81b1a1) | Aug 26, 2023 |
| ASUSTek       | H110M-A                     | [56f9a82624](https://linux-hardware.org/?probe=56f9a82624) | Aug 26, 2023 |
| Gigabyte      | H110M-S2V-CF                | [855ad99ea5](https://linux-hardware.org/?probe=855ad99ea5) | Aug 26, 2023 |
| MSI           | P43i                        | [3f3ea5ff94](https://linux-hardware.org/?probe=3f3ea5ff94) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [e226d45872](https://linux-hardware.org/?probe=e226d45872) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| ASRock        | G41M-VS3                    | [b1e5815ba9](https://linux-hardware.org/?probe=b1e5815ba9) | Aug 26, 2023 |
| ASUSTek       | H81M-E                      | [5e884e12a0](https://linux-hardware.org/?probe=5e884e12a0) | Aug 26, 2023 |
| MSI           | MS-7817                     | [9b7cfe20df](https://linux-hardware.org/?probe=9b7cfe20df) | Aug 25, 2023 |
| Gigabyte      | H97-D3H-CF                  | [675c426397](https://linux-hardware.org/?probe=675c426397) | Aug 25, 2023 |
| ASRock        | H81M-HDS                    | [9d18657882](https://linux-hardware.org/?probe=9d18657882) | Aug 22, 2023 |
| HP            | 0B4Ch D                     | [4cb50f9265](https://linux-hardware.org/?probe=4cb50f9265) | Aug 22, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| Gigabyte      | H310M A-CF x.x              | [76d74daf52](https://linux-hardware.org/?probe=76d74daf52) | Aug 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | [2f0cd6e6d3](https://linux-hardware.org/?probe=2f0cd6e6d3) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | [25fbe59866](https://linux-hardware.org/?probe=25fbe59866) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | [a6cf8bf5f2](https://linux-hardware.org/?probe=a6cf8bf5f2) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | [97a587e6ad](https://linux-hardware.org/?probe=97a587e6ad) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | [5ac356a22f](https://linux-hardware.org/?probe=5ac356a22f) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| ASRock        | B550M-ITX/ac                | [53a81617e7](https://linux-hardware.org/?probe=53a81617e7) | Aug 19, 2023 |
| Gigabyte      | B450M GAMING                | [68bfd376a0](https://linux-hardware.org/?probe=68bfd376a0) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| HP            | 1495                        | [1d04585fac](https://linux-hardware.org/?probe=1d04585fac) | Aug 16, 2023 |
| Dell          | 0NW6H5 A00                  | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Lenovo        | SDK0E50510 WIN              | [7b48c318ed](https://linux-hardware.org/?probe=7b48c318ed) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| ASUSTek       | P8B75-M                     | [aa3414ebdc](https://linux-hardware.org/?probe=aa3414ebdc) | Aug 14, 2023 |
| ASUSTek       | PRIME Z390-P                | [013e2fdac5](https://linux-hardware.org/?probe=013e2fdac5) | Aug 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [72977f6f8a](https://linux-hardware.org/?probe=72977f6f8a) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| HP            | 1495                        | [837afb7bfa](https://linux-hardware.org/?probe=837afb7bfa) | Aug 12, 2023 |
| HP            | 1495                        | [9e8b73f16e](https://linux-hardware.org/?probe=9e8b73f16e) | Aug 11, 2023 |
| Huanan        | X99-QD4 V1.0                | [17e503622d](https://linux-hardware.org/?probe=17e503622d) | Aug 11, 2023 |
| Lenovo        | SDK0E50510 WIN              | [485a8bf15d](https://linux-hardware.org/?probe=485a8bf15d) | Aug 10, 2023 |
| HP            | 1495                        | [6c458bf059](https://linux-hardware.org/?probe=6c458bf059) | Aug 10, 2023 |
| HP            | 0AA4h                       | [e4da6a6aaf](https://linux-hardware.org/?probe=e4da6a6aaf) | Aug 09, 2023 |
| HP            | 0AA4h                       | [4081f7bbda](https://linux-hardware.org/?probe=4081f7bbda) | Aug 09, 2023 |
| ASRock        | H81M-HDS                    | [64dc45c007](https://linux-hardware.org/?probe=64dc45c007) | Aug 07, 2023 |
| Huanan        | X99-QD4 V1.0                | [b62c8c40f5](https://linux-hardware.org/?probe=b62c8c40f5) | Aug 07, 2023 |
| Gigabyte      | J4005ND2P-CF                | [f3644b56ad](https://linux-hardware.org/?probe=f3644b56ad) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Huanan        | X99-QD4 V1.0                | [9aaaaec131](https://linux-hardware.org/?probe=9aaaaec131) | Aug 05, 2023 |
| HP            | 1588h                       | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| HP            | 1495                        | [17ae98cda8](https://linux-hardware.org/?probe=17ae98cda8) | Aug 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [91b8e07f0d](https://linux-hardware.org/?probe=91b8e07f0d) | Aug 04, 2023 |
| HP            | 1495                        | [75dae4c3a6](https://linux-hardware.org/?probe=75dae4c3a6) | Aug 04, 2023 |
| MSI           | P43i                        | [683b26e344](https://linux-hardware.org/?probe=683b26e344) | Aug 03, 2023 |
| Medion        | MS-7748                     | [413b9e74a6](https://linux-hardware.org/?probe=413b9e74a6) | Aug 03, 2023 |
| Huanan        | X99-QD4 V1.0                | [e47b01848a](https://linux-hardware.org/?probe=e47b01848a) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [99cae22846](https://linux-hardware.org/?probe=99cae22846) | Aug 02, 2023 |
| Huanan        | X99-QD4 V1.0                | [56573f8499](https://linux-hardware.org/?probe=56573f8499) | Aug 01, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [6202f3b97e](https://linux-hardware.org/?probe=6202f3b97e) | Jul 31, 2023 |
| Dell          | 0WMJ54 A01                  | [908f49c376](https://linux-hardware.org/?probe=908f49c376) | Jul 31, 2023 |
| ASUSTek       | H110M-R                     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| Lenovo        | SDK0E50510 WIN              | [385c97c1d3](https://linux-hardware.org/?probe=385c97c1d3) | Jul 28, 2023 |
| HP            | 1495                        | [b4e2031d1e](https://linux-hardware.org/?probe=b4e2031d1e) | Jul 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [ea550fb04c](https://linux-hardware.org/?probe=ea550fb04c) | Jul 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5b17937c10](https://linux-hardware.org/?probe=5b17937c10) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | [ebaacb8057](https://linux-hardware.org/?probe=ebaacb8057) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | [3988b909c7](https://linux-hardware.org/?probe=3988b909c7) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [de48c51732](https://linux-hardware.org/?probe=de48c51732) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [f2bef973eb](https://linux-hardware.org/?probe=f2bef973eb) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [04a75d9e0c](https://linux-hardware.org/?probe=04a75d9e0c) | Jul 26, 2023 |
| HP            | 8265                        | [96a99f0e8f](https://linux-hardware.org/?probe=96a99f0e8f) | Jul 25, 2023 |
| ASUSTek       | UN45                        | [ea2bebc887](https://linux-hardware.org/?probe=ea2bebc887) | Jul 25, 2023 |
| Acer          | Veriton M4610G              | [aef65d0501](https://linux-hardware.org/?probe=aef65d0501) | Jul 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4c5c8def02](https://linux-hardware.org/?probe=4c5c8def02) | Jul 24, 2023 |
| Dell          | 0TY565                      | [828f20c8bb](https://linux-hardware.org/?probe=828f20c8bb) | Jul 24, 2023 |
| Acer          | Veriton M4610G              | [57cdc7820f](https://linux-hardware.org/?probe=57cdc7820f) | Jul 23, 2023 |
| Gigabyte      | G31M-ES2L                   | [91d19df4b4](https://linux-hardware.org/?probe=91d19df4b4) | Jul 23, 2023 |
| HP            | 8265                        | [0e5a193692](https://linux-hardware.org/?probe=0e5a193692) | Jul 23, 2023 |
| HP            | 1495                        | [a9bd3f59e8](https://linux-hardware.org/?probe=a9bd3f59e8) | Jul 23, 2023 |
| Dell          | 0PU052                      | [43454a5114](https://linux-hardware.org/?probe=43454a5114) | Jul 22, 2023 |
| Dell          | 0PU052                      | [b1ba2d4239](https://linux-hardware.org/?probe=b1ba2d4239) | Jul 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| Huanan        | X99-QD4 V1.0                | [fc1e32f937](https://linux-hardware.org/?probe=fc1e32f937) | Jul 17, 2023 |
| MSI           | B85M-E33                    | [6d2ee4521b](https://linux-hardware.org/?probe=6d2ee4521b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | [a8bbbd8c49](https://linux-hardware.org/?probe=a8bbbd8c49) | Jul 17, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f04f199334](https://linux-hardware.org/?probe=f04f199334) | Jul 16, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [b5588d7209](https://linux-hardware.org/?probe=b5588d7209) | Jul 15, 2023 |
| Dell          | 0GY6Y8 A01                  | [a562b6518f](https://linux-hardware.org/?probe=a562b6518f) | Jul 15, 2023 |
| Gigabyte      | H310M A-CF x.x              | [655cb31a8a](https://linux-hardware.org/?probe=655cb31a8a) | Jul 14, 2023 |
| DFI           | WL051                       | [bfe00b9eeb](https://linux-hardware.org/?probe=bfe00b9eeb) | Jul 14, 2023 |
| Lenovo        | SDK0E50510 WIN              | [0d773629f2](https://linux-hardware.org/?probe=0d773629f2) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | [e695d46a05](https://linux-hardware.org/?probe=e695d46a05) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | [93a455ac9b](https://linux-hardware.org/?probe=93a455ac9b) | Jul 14, 2023 |
| MSI           | B150M ECO                   | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| Gigabyte      | B450M GAMING                | [2f3da717f3](https://linux-hardware.org/?probe=2f3da717f3) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | [bfe4c07a40](https://linux-hardware.org/?probe=bfe4c07a40) | Jul 12, 2023 |
| ASRock        | A520M-ITX/ac                | [1c7a630efb](https://linux-hardware.org/?probe=1c7a630efb) | Jul 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [08ae4ea22e](https://linux-hardware.org/?probe=08ae4ea22e) | Jul 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [657750190f](https://linux-hardware.org/?probe=657750190f) | Jul 08, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [81dd9a0120](https://linux-hardware.org/?probe=81dd9a0120) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [6965fec932](https://linux-hardware.org/?probe=6965fec932) | Jul 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [4e6e8dc45b](https://linux-hardware.org/?probe=4e6e8dc45b) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [5a62a75599](https://linux-hardware.org/?probe=5a62a75599) | Jul 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | [bd3b079d0d](https://linux-hardware.org/?probe=bd3b079d0d) | Jul 04, 2023 |
| ASRock        | FM2A75M Pro4+               | [7390114024](https://linux-hardware.org/?probe=7390114024) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | [84a32e1b42](https://linux-hardware.org/?probe=84a32e1b42) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [9393d317b6](https://linux-hardware.org/?probe=9393d317b6) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [2a7725896c](https://linux-hardware.org/?probe=2a7725896c) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | [eb7ec8410d](https://linux-hardware.org/?probe=eb7ec8410d) | Jul 02, 2023 |
| AOpen         | D1009 A1A4                  | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| Dell          | 0D883F A06                  | [b27b2b3825](https://linux-hardware.org/?probe=b27b2b3825) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | [e50079b95e](https://linux-hardware.org/?probe=e50079b95e) | Jul 01, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ca1817783e](https://linux-hardware.org/?probe=ca1817783e) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [908af533fc](https://linux-hardware.org/?probe=908af533fc) | Jun 30, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [298a4bf290](https://linux-hardware.org/?probe=298a4bf290) | Jun 30, 2023 |
| ASRock        | G41M-VS3                    | [344a5eda20](https://linux-hardware.org/?probe=344a5eda20) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [565c1ea1c2](https://linux-hardware.org/?probe=565c1ea1c2) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [545a2c4e26](https://linux-hardware.org/?probe=545a2c4e26) | Jun 28, 2023 |
| Dell          | 0D883F A06                  | [b26a7fb008](https://linux-hardware.org/?probe=b26a7fb008) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | [04f61a169e](https://linux-hardware.org/?probe=04f61a169e) | Jun 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | [839490cb5a](https://linux-hardware.org/?probe=839490cb5a) | Jun 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | [75cab0a675](https://linux-hardware.org/?probe=75cab0a675) | Jun 24, 2023 |
| HP            | 8265                        | [863a585141](https://linux-hardware.org/?probe=863a585141) | Jun 23, 2023 |
| ASRock        | FM2A75M Pro4+               | [a3f0d3cbc6](https://linux-hardware.org/?probe=a3f0d3cbc6) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | [8cfeb06220](https://linux-hardware.org/?probe=8cfeb06220) | Jun 21, 2023 |
| Gigabyte      | B450M GAMING                | [a6f14223ae](https://linux-hardware.org/?probe=a6f14223ae) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | [076a78c151](https://linux-hardware.org/?probe=076a78c151) | Jun 20, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [d09be5d97c](https://linux-hardware.org/?probe=d09be5d97c) | Jun 20, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [320272d785](https://linux-hardware.org/?probe=320272d785) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | [0cbbe081c8](https://linux-hardware.org/?probe=0cbbe081c8) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | [41c5ad600b](https://linux-hardware.org/?probe=41c5ad600b) | Jun 19, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [3dacc56dd5](https://linux-hardware.org/?probe=3dacc56dd5) | Jun 18, 2023 |
| Gigabyte      | G31M-ES2L                   | [b90840dbba](https://linux-hardware.org/?probe=b90840dbba) | Jun 18, 2023 |
| ASRock        | G41M-VS3                    | [6bd02aa0f2](https://linux-hardware.org/?probe=6bd02aa0f2) | Jun 18, 2023 |
| ASRock        | A520M-HDV                   | [e0d2c8f040](https://linux-hardware.org/?probe=e0d2c8f040) | Jun 18, 2023 |
| Gigabyte      | X570 GAMING X               | [fa9508da6e](https://linux-hardware.org/?probe=fa9508da6e) | Jun 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| BlackPanther 18.1  | 991      | 51.27%  |
| Ubuntu 20.04       | 100      | 5.17%   |
| BlackPanther 16.2  | 63       | 3.26%   |
| Ubuntu 18.04       | 56       | 2.9%    |
| Ubuntu 22.04       | 43       | 2.22%   |
| BlackPanther 22.1  | 41       | 2.12%   |
| OpenMandriva 4.2   | 37       | 1.91%   |
| OpenMandriva 4.3   | 21       | 1.09%   |
| Debian 11          | 20       | 1.03%   |
| Arch Rolling       | 20       | 1.03%   |
| Zorin 16           | 19       | 0.98%   |
| OpenMandriva 23.08 | 13       | 0.67%   |
| OpenMandriva 23.03 | 13       | 0.67%   |
| Linux Mint 20.2    | 13       | 0.67%   |
| Debian 12          | 13       | 0.67%   |
| OpenMandriva 4.50  | 12       | 0.62%   |
| Manjaro            | 12       | 0.62%   |
| Debian 10          | 12       | 0.62%   |
| ArcoLinux Rolling  | 12       | 0.62%   |
| Ubuntu 19.10       | 11       | 0.57%   |
| Linux Mint 20      | 11       | 0.57%   |
| Fedora 39          | 11       | 0.57%   |
| Arch               | 11       | 0.57%   |
| Xubuntu 20.04      | 10       | 0.52%   |
| Xubuntu 18.04      | 10       | 0.52%   |
| Ubuntu 21.10       | 9        | 0.47%   |
| Ubuntu 19.04       | 9        | 0.47%   |
| Pop!_OS 22.04      | 9        | 0.47%   |
| Ubuntu 23.10       | 8        | 0.41%   |
| Linux Mint 21.1    | 8        | 0.41%   |
| Linux Mint 20.3    | 8        | 0.41%   |
| OpenMandriva 5.0   | 7        | 0.36%   |
| OpenMandriva 4.90  | 7        | 0.36%   |
| Linux Mint 20.1    | 7        | 0.36%   |
| Linux Mint 19.3    | 7        | 0.36%   |
| Fedora 38          | 7        | 0.36%   |
| Zorin 15           | 6        | 0.31%   |
| Ubuntu 21.04       | 6        | 0.31%   |
| Ubuntu 20.10       | 6        | 0.31%   |
| Kubuntu 20.04      | 6        | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| BlackPanther  | 1071     | 57.89%  |
| Ubuntu        | 252      | 13.62%  |
| OpenMandriva  | 109      | 5.89%   |
| Linux Mint    | 66       | 3.57%   |
| Debian        | 49       | 2.65%   |
| Fedora        | 35       | 1.89%   |
| Arch          | 31       | 1.68%   |
| Zorin         | 30       | 1.62%   |
| Xubuntu       | 25       | 1.35%   |
| Manjaro       | 25       | 1.35%   |
| Pop!_OS       | 18       | 0.97%   |
| Kubuntu       | 18       | 0.97%   |
| ArcoLinux     | 14       | 0.76%   |
| Ubuntu MATE   | 12       | 0.65%   |
| ROSA          | 11       | 0.59%   |
| KDE neon      | 9        | 0.49%   |
| Lubuntu       | 8        | 0.43%   |
| Ubuntu Unity  | 7        | 0.38%   |
| Endless       | 7        | 0.38%   |
| Gentoo        | 6        | 0.32%   |
| openSUSE      | 5        | 0.27%   |
| Nobara        | 5        | 0.27%   |
| EndeavourOS   | 5        | 0.27%   |
| LMDE          | 4        | 0.22%   |
| Elementary    | 4        | 0.22%   |
| Garuda Linux  | 3        | 0.16%   |
| Xero          | 2        | 0.11%   |
| MX            | 2        | 0.11%   |
| CentOS        | 2        | 0.11%   |
| AlmaLinux     | 2        | 0.11%   |
| Void Linux    | 1        | 0.05%   |
| Ubuntu Budgie | 1        | 0.05%   |
| SteamOS       | 1        | 0.05%   |
| risiOS        | 1        | 0.05%   |
| Reborn OS     | 1        | 0.05%   |
| Q4OS          | 1        | 0.05%   |
| NixOS         | 1        | 0.05%   |
| Linux Lite    | 1        | 0.05%   |
| Kali          | 1        | 0.05%   |
| Clear Linux   | 1        | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.18.16-desktop-1bP      | 705      | 32.4%   |
| 5.6.14-desktop-2bP       | 316      | 14.52%  |
| 5.15.85-desktop-1bP      | 73       | 3.35%   |
| 4.9.20-desktop-pae-1bP   | 55       | 2.53%   |
| 5.10.14-desktop-1omv4002 | 34       | 1.56%   |
| 5.1.15-desktop-1bP       | 27       | 1.24%   |
| 6.3.8-desktop-1bP        | 20       | 0.92%   |
| 5.16.7-desktop-1omv4003  | 20       | 0.92%   |
| 6.3.3-desktop-1bP        | 14       | 0.64%   |
| 6.2.6-desktop-1omv2390   | 13       | 0.6%    |
| 5.4.0-42-generic         | 13       | 0.6%    |
| 6.4.11-desktop-1omv2390  | 12       | 0.55%   |
| 5.4.0-58-generic         | 12       | 0.55%   |
| 5.15.0-56-generic        | 9        | 0.41%   |
| 6.6.2-desktop-1omv2390   | 8        | 0.37%   |
| 5.4.0-52-generic         | 8        | 0.37%   |
| 5.4.0-48-generic         | 8        | 0.37%   |
| 5.11.0-27-generic        | 8        | 0.37%   |
| 5.18.12-desktop-3omv4090 | 7        | 0.32%   |
| 6.4.3-desktop-1bP        | 6        | 0.28%   |
| 5.4.0-47-generic         | 6        | 0.28%   |
| 5.3.0-46-generic         | 6        | 0.28%   |
| 5.15.0-58-generic        | 6        | 0.28%   |
| 5.11.0-43-generic        | 6        | 0.28%   |
| 6.2.0-26-generic         | 5        | 0.23%   |
| 6.1.1-desktop-1omv2290   | 5        | 0.23%   |
| 5.8.0-44-generic         | 5        | 0.23%   |
| 5.8.0-43-generic         | 5        | 0.23%   |
| 5.4.0-91-generic         | 5        | 0.23%   |
| 5.15.0-47-generic        | 5        | 0.23%   |
| 5.12.4-desktop-1omv4050  | 5        | 0.23%   |
| 5.11.0-37-generic        | 5        | 0.23%   |
| 5.0.0-37-generic         | 5        | 0.23%   |
| 4.15.0-43-generic        | 5        | 0.23%   |
| 6.5.0-14-generic         | 4        | 0.18%   |
| 6.2.9-desktop-1bP        | 4        | 0.18%   |
| 6.2.0-33-generic         | 4        | 0.18%   |
| 5.8.0-7630-generic       | 4        | 0.18%   |
| 5.4.0-88-generic         | 4        | 0.18%   |
| 5.4.0-73-generic         | 4        | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.16 | 705      | 33.18%  |
| 5.6.14  | 317      | 14.92%  |
| 5.4.0   | 130      | 6.12%   |
| 5.15.85 | 73       | 3.44%   |
| 5.15.0  | 64       | 3.01%   |
| 4.9.20  | 58       | 2.73%   |
| 4.15.0  | 45       | 2.12%   |
| 5.11.0  | 44       | 2.07%   |
| 5.8.0   | 36       | 1.69%   |
| 5.10.14 | 34       | 1.6%    |
| 5.13.0  | 31       | 1.46%   |
| 5.3.0   | 30       | 1.41%   |
| 5.1.15  | 28       | 1.32%   |
| 6.5.0   | 22       | 1.04%   |
| 6.2.0   | 22       | 1.04%   |
| 5.0.0   | 22       | 1.04%   |
| 6.3.8   | 20       | 0.94%   |
| 5.16.7  | 20       | 0.94%   |
| 5.10.0  | 18       | 0.85%   |
| 6.2.6   | 16       | 0.75%   |
| 6.3.3   | 14       | 0.66%   |
| 6.1.0   | 13       | 0.61%   |
| 4.19.0  | 13       | 0.61%   |
| 6.4.11  | 12       | 0.56%   |
| 5.19.0  | 12       | 0.56%   |
| 6.6.2   | 10       | 0.47%   |
| 6.4.3   | 8        | 0.38%   |
| 4.18.0  | 8        | 0.38%   |
| 6.1.1   | 7        | 0.33%   |
| 5.18.12 | 7        | 0.33%   |
| 6.7.0   | 6        | 0.28%   |
| 6.0.12  | 5        | 0.24%   |
| 5.14.0  | 5        | 0.24%   |
| 5.12.4  | 5        | 0.24%   |
| 6.2.9   | 4        | 0.19%   |
| 5.9.16  | 4        | 0.19%   |
| 5.16.0  | 4        | 0.19%   |
| 5.13.13 | 4        | 0.19%   |
| 6.6.6   | 3        | 0.14%   |
| 6.6.4   | 3        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 713      | 33.87%  |
| 5.6     | 319      | 15.15%  |
| 5.15    | 154      | 7.32%   |
| 5.4     | 139      | 6.6%    |
| 4.9     | 63       | 2.99%   |
| 5.10    | 61       | 2.9%    |
| 6.2     | 55       | 2.61%   |
| 5.11    | 52       | 2.47%   |
| 4.15    | 45       | 2.14%   |
| 5.8     | 41       | 1.95%   |
| 5.13    | 39       | 1.85%   |
| 6.5     | 36       | 1.71%   |
| 6.3     | 34       | 1.62%   |
| 6.1     | 31       | 1.47%   |
| 5.3     | 31       | 1.47%   |
| 5.1     | 31       | 1.47%   |
| 5.16    | 30       | 1.43%   |
| 6.4     | 28       | 1.33%   |
| 6.6     | 27       | 1.28%   |
| 5.19    | 24       | 1.14%   |
| 5.0     | 22       | 1.05%   |
| 6.0     | 17       | 0.81%   |
| 6.7     | 13       | 0.62%   |
| 5.18    | 13       | 0.62%   |
| 4.19    | 13       | 0.62%   |
| 5.14    | 12       | 0.57%   |
| 6.8     | 11       | 0.52%   |
| 5.9     | 11       | 0.52%   |
| 5.7     | 8        | 0.38%   |
| 5.17    | 8        | 0.38%   |
| 5.12    | 8        | 0.38%   |
| 5.5     | 3        | 0.14%   |
| 4.7     | 3        | 0.14%   |
| 4.4     | 2        | 0.1%    |
| 4.20    | 2        | 0.1%    |
| 4.5     | 1        | 0.05%   |
| 4.14    | 1        | 0.05%   |
| 4.12    | 1        | 0.05%   |
| 4.10    | 1        | 0.05%   |
| 4.1     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1714     | 95.38%  |
| i686   | 82       | 4.56%   |
| unknow | 1        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 1176     | 64.05%  |
| GNOME           | 300      | 16.34%  |
| Unknown         | 136      | 7.41%   |
| XFCE            | 65       | 3.54%   |
| X-Cinnamon      | 48       | 2.61%   |
| MATE            | 37       | 2.02%   |
| LXQt            | 17       | 0.93%   |
| KDE             | 11       | 0.6%    |
| Cinnamon        | 9        | 0.49%   |
| Unity           | 7        | 0.38%   |
| KDE6            | 5        | 0.27%   |
| KDE4            | 5        | 0.27%   |
| i3              | 5        | 0.27%   |
| Pantheon        | 3        | 0.16%   |
| LXDE            | 3        | 0.16%   |
| Deepin          | 3        | 0.16%   |
| Trinity         | 1        | 0.05%   |
| sway            | 1        | 0.05%   |
| GNOME Flashback | 1        | 0.05%   |
| GNOME Classic   | 1        | 0.05%   |
| Enlightenment   | 1        | 0.05%   |
| Budgie          | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1600     | 88.4%   |
| Wayland | 132      | 7.29%   |
| Unknown | 53       | 2.93%   |
| Tty     | 23       | 1.27%   |
| Web     | 2        | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 1207     | 66.1%   |
| Unknown | 356      | 19.5%   |
| GDM3    | 95       | 5.2%    |
| LightDM | 75       | 4.11%   |
| GDM     | 60       | 3.29%   |
| TDM     | 26       | 1.42%   |
| KDM     | 5        | 0.27%   |
| SLiM    | 2        | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1122     | 61.31%  |
| hu_HU      | 423      | 23.11%  |
| en_US      | 229      | 12.51%  |
| en_GB      | 25       | 1.37%   |
| C          | 13       | 0.71%   |
| de_DE      | 10       | 0.55%   |
| hu_HU.UTF8 | 2        | 0.11%   |
| sk_SK      | 1        | 0.05%   |
| ru_RU      | 1        | 0.05%   |
| POSIX      | 1        | 0.05%   |
| en_AG      | 1        | 0.05%   |
| el_GR      | 1        | 0.05%   |
| C.UTF8     | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1283     | 68.9%   |
| EFI  | 579      | 31.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1021     | 51.41%  |
| Overlay | 831      | 41.84%  |
| Btrfs   | 63       | 3.17%   |
| Tmpfs   | 35       | 1.76%   |
| Unknown | 19       | 0.96%   |
| Xfs     | 8        | 0.4%    |
| Zfs     | 5        | 0.25%   |
| Ext2    | 3        | 0.15%   |
| Ext3    | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 848      | 44.84%  |
| GPT     | 661      | 34.96%  |
| Unknown | 382      | 20.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1358     | 69.53%  |
| Yes       | 595      | 30.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 970      | 50.52%  |
| No        | 950      | 49.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 360      | 20.22%  |
| Gigabyte Technology | 358      | 20.11%  |
| ASRock              | 286      | 16.07%  |
| Dell                | 180      | 10.11%  |
| Hewlett-Packard     | 167      | 9.38%   |
| MSI                 | 117      | 6.57%   |
| Lenovo              | 82       | 4.61%   |
| Fujitsu             | 63       | 3.54%   |
| Fujitsu Siemens     | 29       | 1.63%   |
| Intel               | 25       | 1.4%    |
| Acer                | 22       | 1.24%   |
| Foxconn             | 15       | 0.84%   |
| Unknown             | 14       | 0.79%   |
| Medion              | 8        | 0.45%   |
| Pegatron            | 6        | 0.34%   |
| Huanan              | 5        | 0.28%   |
| Biostar             | 4        | 0.22%   |
| Shuttle             | 3        | 0.17%   |
| AOpen               | 3        | 0.17%   |
| AMI                 | 3        | 0.17%   |
| ABIT                | 3        | 0.17%   |
| VXL                 | 2        | 0.11%   |
| Nvidia              | 2        | 0.11%   |
| Gateway             | 2        | 0.11%   |
| AMD                 | 2        | 0.11%   |
| Wistron             | 1        | 0.06%   |
| WinFast             | 1        | 0.06%   |
| Wincor Nixdorf      | 1        | 0.06%   |
| ViewSonic           | 1        | 0.06%   |
| Supermicro          | 1        | 0.06%   |
| Seeed Studio        | 1        | 0.06%   |
| NEC Computers       | 1        | 0.06%   |
| Minix               | 1        | 0.06%   |
| Lex                 | 1        | 0.06%   |
| JW Technology       | 1        | 0.06%   |
| JGINYUE             | 1        | 0.06%   |
| IBM                 | 1        | 0.06%   |
| Hampoo              | 1        | 0.06%   |
| GIADA               | 1        | 0.06%   |
| ECS                 | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASRock FM2A75M Pro4+               | 33       | 1.85%   |
| ASUS All Series                    | 28       | 1.57%   |
| Dell OptiPlex 3020                 | 23       | 1.29%   |
| Dell OptiPlex 755                  | 14       | 0.79%   |
| Unknown                            | 14       | 0.79%   |
| Gigabyte G31M-ES2L                 | 13       | 0.73%   |
| Dell OptiPlex 780                  | 13       | 0.73%   |
| ASUS P5KPL-AM EPU                  | 12       | 0.67%   |
| Dell OptiPlex 760                  | 11       | 0.62%   |
| Dell OptiPlex 7010                 | 10       | 0.56%   |
| Gigabyte H61M-S1                   | 9        | 0.51%   |
| Dell Precision WorkStation T3500   | 9        | 0.51%   |
| MSI MS-7C02                        | 8        | 0.45%   |
| MSI MS-7817                        | 8        | 0.45%   |
| HP ProDesk 600 G2 SFF              | 8        | 0.45%   |
| ASRock G41M-VS3                    | 8        | 0.45%   |
| MSI MS-7680                        | 7        | 0.39%   |
| Lenovo ThinkStation D20 4158AF8    | 7        | 0.39%   |
| Gigabyte B450 AORUS ELITE          | 7        | 0.39%   |
| Gigabyte 970A-DS3P                 | 7        | 0.39%   |
| ASRock N68C-S UCC                  | 7        | 0.39%   |
| MSI MS-7C91                        | 6        | 0.34%   |
| MSI MS-7592                        | 6        | 0.34%   |
| HP EliteDesk 705 G3 SFF            | 6        | 0.34%   |
| HP Compaq Pro 6300 MT              | 6        | 0.34%   |
| HP Compaq Elite 8300 SFF           | 6        | 0.34%   |
| HP Compaq dc5800 Small Form Factor | 6        | 0.34%   |
| HP Compaq 8000 Elite SFF PC        | 6        | 0.34%   |
| Gigabyte H81M-S1                   | 6        | 0.34%   |
| Fujitsu Siemens ESPRIMO E5730      | 6        | 0.34%   |
| Fujitsu ESPRIMO P910               | 6        | 0.34%   |
| Dell OptiPlex 9020                 | 6        | 0.34%   |
| Dell OptiPlex 745                  | 6        | 0.34%   |
| Dell OptiPlex 330                  | 6        | 0.34%   |
| ASUS PRIME A320M-K                 | 6        | 0.34%   |
| ASUS H110M-K                       | 6        | 0.34%   |
| Acer Veriton M430                  | 6        | 0.34%   |
| HP Compaq dc5850 Small Form Factor | 5        | 0.28%   |
| HP Compaq 6005 Pro SFF PC          | 5        | 0.28%   |
| Gigabyte G41MT-S2PT                | 5        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 147      | 8.26%   |
| HP Compaq               | 111      | 6.24%   |
| ASUS PRIME              | 59       | 3.31%   |
| Lenovo ThinkCentre      | 56       | 3.15%   |
| Fujitsu ESPRIMO         | 45       | 2.53%   |
| ASRock FM2A75M          | 33       | 1.85%   |
| ASUS All                | 28       | 1.57%   |
| Fujitsu Siemens ESPRIMO | 23       | 1.29%   |
| ASUS TUF                | 22       | 1.24%   |
| ASUS ROG                | 22       | 1.24%   |
| Dell Precision          | 20       | 1.12%   |
| ASUS P5KPL-AM           | 18       | 1.01%   |
| HP EliteDesk            | 17       | 0.96%   |
| Gigabyte B450           | 17       | 0.96%   |
| Acer Veriton            | 16       | 0.9%    |
| Lenovo ThinkStation     | 14       | 0.79%   |
| HP ProDesk              | 14       | 0.79%   |
| Unknown                 | 14       | 0.79%   |
| Gigabyte G31M-ES2L      | 13       | 0.73%   |
| Fujitsu CELSIUS         | 11       | 0.62%   |
| ASUS M5A97              | 10       | 0.56%   |
| Gigabyte H61M-S1        | 9        | 0.51%   |
| Gigabyte H310M          | 9        | 0.51%   |
| Gigabyte B450M          | 9        | 0.51%   |
| ASRock 970              | 9        | 0.51%   |
| MSI MS-7C02             | 8        | 0.45%   |
| MSI MS-7817             | 8        | 0.45%   |
| ASRock N68C-S           | 8        | 0.45%   |
| ASRock G41M-VS3         | 8        | 0.45%   |
| MSI MS-7680             | 7        | 0.39%   |
| Gigabyte 970A-DS3P      | 7        | 0.39%   |
| ASUS M5A78L-M           | 7        | 0.39%   |
| ASUS H110M-A            | 7        | 0.39%   |
| ASRock B450M            | 7        | 0.39%   |
| MSI MS-7C91             | 6        | 0.34%   |
| MSI MS-7592             | 6        | 0.34%   |
| Gigabyte H81M-S1        | 6        | 0.34%   |
| ASUS P8Z77-V            | 6        | 0.34%   |
| ASUS P8H61-M            | 6        | 0.34%   |
| ASUS H110M-K            | 6        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 184      | 10.34%  |
| 2013    | 173      | 9.72%   |
| 2014    | 155      | 8.71%   |
| 2010    | 152      | 8.54%   |
| 2009    | 148      | 8.31%   |
| 2011    | 144      | 8.09%   |
| 2008    | 131      | 7.36%   |
| 2018    | 128      | 7.19%   |
| 2007    | 103      | 5.79%   |
| 2015    | 76       | 4.27%   |
| 2017    | 74       | 4.16%   |
| 2020    | 62       | 3.48%   |
| 2019    | 61       | 3.43%   |
| 2016    | 58       | 3.26%   |
| 2006    | 45       | 2.53%   |
| 2021    | 35       | 1.97%   |
| 2005    | 19       | 1.07%   |
| 2022    | 14       | 0.79%   |
| 2023    | 8        | 0.45%   |
| 2004    | 4        | 0.22%   |
| 2003    | 3        | 0.17%   |
| 2024    | 2        | 0.11%   |
| Unknown | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1780     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1762     | 98.82%  |
| Enabled  | 21       | 1.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1780     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 482      | 25.91%  |
| 8.01-16.0   | 419      | 22.53%  |
| 4.01-8.0    | 314      | 16.88%  |
| 16.01-24.0  | 302      | 16.24%  |
| 1.01-2.0    | 126      | 6.77%   |
| 32.01-64.0  | 118      | 6.34%   |
| 2.01-3.0    | 34       | 1.83%   |
| 64.01-256.0 | 29       | 1.56%   |
| 24.01-32.0  | 28       | 1.51%   |
| 0.51-1.0    | 8        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 600      | 27.74%  |
| 0.51-1.0    | 565      | 26.12%  |
| 0.01-0.5    | 513      | 23.72%  |
| 2.01-3.0    | 237      | 10.96%  |
| 3.01-4.0    | 109      | 5.04%   |
| 4.01-8.0    | 106      | 4.9%    |
| 8.01-16.0   | 23       | 1.06%   |
| 16.01-24.0  | 6        | 0.28%   |
| 64.01-256.0 | 2        | 0.09%   |
| 32.01-64.0  | 1        | 0.05%   |
| Unknown     | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 911      | 46.24%  |
| 2       | 530      | 26.9%   |
| 3       | 280      | 14.21%  |
| 4       | 124      | 6.29%   |
| 5       | 56       | 2.84%   |
| 0       | 31       | 1.57%   |
| 6       | 15       | 0.76%   |
| 8       | 7        | 0.36%   |
| 7       | 7        | 0.36%   |
| 9       | 4        | 0.2%    |
| 11      | 2        | 0.1%    |
| 10      | 2        | 0.1%    |
| Unknown | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1013     | 54.7%   |
| No        | 839      | 45.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1753     | 98.48%  |
| No        | 27       | 1.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1346     | 73.79%  |
| Yes       | 478      | 26.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1526     | 83.71%  |
| Yes       | 297      | 16.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Hungary | 1780     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Budapest          | 617      | 29.41%  |
| Szeged            | 50       | 2.38%   |
| Pécs             | 44       | 2.1%    |
| Győr             | 42       | 2%      |
| Zalaegerszeg      | 33       | 1.57%   |
| Miskolc           | 32       | 1.53%   |
| Debrecen          | 32       | 1.53%   |
| Tatabánya        | 31       | 1.48%   |
| Kecskemét        | 29       | 1.38%   |
| Szigetszentmiklos | 26       | 1.24%   |
| Szombathely       | 25       | 1.19%   |
| Érd              | 24       | 1.14%   |
| Eger              | 24       | 1.14%   |
| Karcag            | 23       | 1.1%    |
| Székesfehérvár | 21       | 1%      |
| Szekszárd        | 20       | 0.95%   |
| Gödöllő        | 18       | 0.86%   |
| Berettyóújfalu  | 18       | 0.86%   |
| Oroshaza          | 17       | 0.81%   |
| Szolnok           | 16       | 0.76%   |
| Nyiregyhaza       | 16       | 0.76%   |
| Toeroekbalint     | 14       | 0.67%   |
| Szentendre        | 13       | 0.62%   |
| Nagykanizsa       | 13       | 0.62%   |
| Hodmezovasarhely  | 13       | 0.62%   |
| Mosonmagyaróvár | 12       | 0.57%   |
| Esztergom         | 12       | 0.57%   |
| Veresegyhaz       | 11       | 0.52%   |
| Siófok           | 10       | 0.48%   |
| Papa              | 10       | 0.48%   |
| Mohács           | 10       | 0.48%   |
| Hatvan            | 10       | 0.48%   |
| Dunakeszi         | 10       | 0.48%   |
| Dunaharaszti      | 10       | 0.48%   |
| Tiszafured        | 9        | 0.43%   |
| Sopron            | 9        | 0.43%   |
| Hajduboszormeny   | 9        | 0.43%   |
| Gyomro            | 9        | 0.43%   |
| Biatorbagy        | 9        | 0.43%   |
| Ajka              | 9        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 633      | 1445   | 19.74%  |
| Samsung Electronics         | 520      | 968    | 16.21%  |
| Seagate                     | 443      | 727    | 13.81%  |
| Kingston                    | 431      | 851    | 13.44%  |
| Toshiba                     | 243      | 467    | 7.58%   |
| Hitachi                     | 121      | 176    | 3.77%   |
| A-DATA Technology           | 98       | 177    | 3.06%   |
| Maxtor                      | 53       | 69     | 1.65%   |
| Sandisk                     | 52       | 67     | 1.62%   |
| Crucial                     | 49       | 83     | 1.53%   |
| SPCC                        | 48       | 71     | 1.5%    |
| Intel                       | 33       | 58     | 1.03%   |
| HGST                        | 33       | 94     | 1.03%   |
| Apacer                      | 28       | 38     | 0.87%   |
| Intenso                     | 24       | 37     | 0.75%   |
| Fujitsu                     | 22       | 22     | 0.69%   |
| OCZ                         | 21       | 27     | 0.65%   |
| Unknown                     | 17       | 38     | 0.53%   |
| Kingston Technology Company | 17       | 19     | 0.53%   |
| JMicron Technology          | 17       | 21     | 0.53%   |
| China                       | 17       | 26     | 0.53%   |
| Patriot                     | 16       | 39     | 0.5%    |
| Gigabyte Technology         | 15       | 50     | 0.47%   |
| Micron Technology           | 14       | 21     | 0.44%   |
| Transcend                   | 13       | 19     | 0.41%   |
| PNY                         | 12       | 25     | 0.37%   |
| Kingmax                     | 12       | 40     | 0.37%   |
| Hewlett-Packard             | 12       | 18     | 0.37%   |
| SK hynix                    | 11       | 16     | 0.34%   |
| KingSpec                    | 9        | 11     | 0.28%   |
| XPG                         | 8        | 13     | 0.25%   |
| Corsair                     | 8        | 9      | 0.25%   |
| Verbatim                    | 7        | 11     | 0.22%   |
| Netac                       | 7        | 15     | 0.22%   |
| LITEON                      | 7        | 7      | 0.22%   |
| Zheino                      | 6        | 22     | 0.19%   |
| Team                        | 6        | 8      | 0.19%   |
| Phison                      | 6        | 9      | 0.19%   |
| Unknown                     | 6        | 6      | 0.19%   |
| Silicon Motion              | 5        | 6      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 96       | 2.59%   |
| Kingston SA400S37120G 120GB SSD                   | 77       | 2.07%   |
| Toshiba DT01ACA100 1TB                            | 65       | 1.75%   |
| Kingston SV300S37A120G 120GB SSD                  | 61       | 1.64%   |
| Seagate ST500DM002-1BD142 500GB                   | 56       | 1.51%   |
| Toshiba DT01ACA050 500GB                          | 43       | 1.16%   |
| Kingston SA400S37480G 480GB SSD                   | 37       | 1%      |
| A-DATA SU630 240GB SSD                            | 31       | 0.84%   |
| Samsung SSD 850 EVO 250GB                         | 27       | 0.73%   |
| Kingston SUV400S37120G 120GB SSD                  | 26       | 0.7%    |
| Samsung HD502HJ 500GB                             | 25       | 0.67%   |
| Seagate ST380815AS 80GB                           | 24       | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 23       | 0.62%   |
| Toshiba HDWD130 3TB                               | 23       | 0.62%   |
| Toshiba HDWD110 1TB                               | 23       | 0.62%   |
| Samsung SSD 860 EVO 250GB                         | 23       | 0.62%   |
| Toshiba DT01ACA200 2TB                            | 21       | 0.57%   |
| SPCC Solid State Disk 256GB                       | 20       | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                    | 20       | 0.54%   |
| A-DATA SU700 120GB SSD                            | 20       | 0.54%   |
| Samsung SSD 860 EVO 500GB                         | 18       | 0.49%   |
| Samsung HD322HJ 320GB                             | 18       | 0.49%   |
| Kingston SHFS37A120G 120GB SSD                    | 17       | 0.46%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 16       | 0.43%   |
| Seagate ST3160815AS 160GB                         | 16       | 0.43%   |
| Kingston SV300S37A240G 240GB SSD                  | 16       | 0.43%   |
| Samsung HD502IJ 500GB                             | 15       | 0.4%    |
| Samsung HD161HJ 160GB                             | 15       | 0.4%    |
| JMicron Generic 320GB                             | 15       | 0.4%    |
| Hitachi HDS721050CLA360 500GB                     | 15       | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 14       | 0.38%   |
| WDC WD10EZRX-00L4HB0 1TB                          | 14       | 0.38%   |
| Seagate ST3160318AS 160GB                         | 14       | 0.38%   |
| Seagate ST1000DM010-2EP102 1TB                    | 14       | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 13       | 0.35%   |
| Samsung HD501LJ 500GB                             | 13       | 0.35%   |
| Samsung HD154UI 1TB                               | 13       | 0.35%   |
| Samsung HD103UJ 1TB                               | 13       | 0.35%   |
| Samsung HD103SJ 1TB                               | 13       | 0.35%   |
| Kingston SV300S37A60G 64GB SSD                    | 13       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 593      | 1304   | 32.8%   |
| Seagate             | 437      | 717    | 24.17%  |
| Samsung Electronics | 264      | 441    | 14.6%   |
| Toshiba             | 232      | 454    | 12.83%  |
| Hitachi             | 121      | 176    | 6.69%   |
| Maxtor              | 53       | 69     | 2.93%   |
| HGST                | 33       | 94     | 1.83%   |
| Fujitsu             | 22       | 22     | 1.22%   |
| JMicron Technology  | 15       | 19     | 0.83%   |
| Hewlett-Packard     | 7        | 9      | 0.39%   |
| Unknown             | 5        | 6      | 0.28%   |
| HGST HTS            | 5        | 5      | 0.28%   |
| Quantum             | 4        | 4      | 0.22%   |
| USB3.0              | 3        | 4      | 0.17%   |
| WD MediaMax         | 2        | 4      | 0.11%   |
| ICY BOX             | 2        | 5      | 0.11%   |
| ExcelStor           | 2        | 2      | 0.11%   |
| Apple               | 2        | 3      | 0.11%   |
| TO Exter            | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| External            | 1        | 2      | 0.06%   |
| Dell                | 1        | 3      | 0.06%   |
| ASMT                | 1        | 1      | 0.06%   |
| Unknown             | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 387      | 745    | 33.22%  |
| Samsung Electronics | 207      | 371    | 17.77%  |
| A-DATA Technology   | 89       | 161    | 7.64%   |
| WDC                 | 59       | 129    | 5.06%   |
| Crucial             | 43       | 74     | 3.69%   |
| SPCC                | 39       | 60     | 3.35%   |
| SanDisk             | 39       | 43     | 3.35%   |
| Apacer              | 28       | 38     | 2.4%    |
| Intel               | 27       | 47     | 2.32%   |
| OCZ                 | 21       | 27     | 1.8%    |
| Intenso             | 21       | 33     | 1.8%    |
| China               | 17       | 26     | 1.46%   |
| Patriot             | 15       | 38     | 1.29%   |
| Transcend           | 12       | 14     | 1.03%   |
| Toshiba             | 12       | 13     | 1.03%   |
| PNY                 | 12       | 25     | 1.03%   |
| Micron Technology   | 12       | 19     | 1.03%   |
| Gigabyte Technology | 12       | 43     | 1.03%   |
| Kingmax             | 11       | 39     | 0.94%   |
| KingSpec            | 9        | 11     | 0.77%   |
| SK hynix            | 7        | 12     | 0.6%    |
| Netac               | 7        | 15     | 0.6%    |
| LITEON              | 7        | 7      | 0.6%    |
| Corsair             | 7        | 8      | 0.6%    |
| Verbatim            | 6        | 10     | 0.52%   |
| Team                | 6        | 8      | 0.52%   |
| GOODRAM             | 5        | 5      | 0.43%   |
| Hewlett-Packard     | 3        | 4      | 0.26%   |
| Unknown             | 3        | 3      | 0.26%   |
| SATAFIRM            | 2        | 2      | 0.17%   |
| Leven               | 2        | 2      | 0.17%   |
| KingFast            | 2        | 3      | 0.17%   |
| KingDian            | 2        | 2      | 0.17%   |
| Integral            | 2        | 2      | 0.17%   |
| BIWIN               | 2        | 6      | 0.17%   |
| Biostar             | 2        | 3      | 0.17%   |
| ASMT                | 2        | 2      | 0.17%   |
| AMD                 | 2        | 2      | 0.17%   |
| 2-Power             | 2        | 4      | 0.17%   |
| XrayDisk            | 1        | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1353     | 3347   | 52.12%  |
| SSD     | 967      | 2085   | 37.25%  |
| NVMe    | 235      | 475    | 9.05%   |
| Unknown | 34       | 64     | 1.31%   |
| MMC     | 7        | 9      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1693     | 5292   | 82.87%  |
| NVMe | 235      | 475    | 11.5%   |
| SAS  | 108      | 204    | 5.29%   |
| MMC  | 7        | 9      | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1509     | 3591   | 64.99%  |
| 0.51-1.0        | 487      | 1031   | 20.97%  |
| 1.01-2.0        | 176      | 325    | 7.58%   |
| 2.01-3.0        | 63       | 219    | 2.71%   |
| 3.01-4.0        | 55       | 177    | 2.37%   |
| 4.01-10.0       | 24       | 62     | 1.03%   |
| 10.01-20.0      | 6        | 25     | 0.26%   |
| More than 100.0 | 2        | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 757      | 35.59%  |
| 101-250        | 407      | 19.13%  |
| 251-500        | 251      | 11.8%   |
| 501-1000       | 161      | 7.57%   |
| 51-100         | 148      | 6.96%   |
| 1001-2000      | 105      | 4.94%   |
| 1-20           | 100      | 4.7%    |
| 21-50          | 78       | 3.67%   |
| More than 3000 | 76       | 3.57%   |
| 2001-3000      | 44       | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 757      | 35.59%  |
| 1-20           | 687      | 32.3%   |
| 21-50          | 179      | 8.42%   |
| 51-100         | 128      | 6.02%   |
| 101-250        | 120      | 5.64%   |
| 501-1000       | 84       | 3.95%   |
| 251-500        | 73       | 3.43%   |
| 1001-2000      | 54       | 2.54%   |
| More than 3000 | 30       | 1.41%   |
| 2001-3000      | 14       | 0.66%   |
| 0              | 1        | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 20       | 37     | 3.08%   |
| A-DATA Technology SU630 240GB SSD  | 19       | 34     | 2.92%   |
| Kingston SV300S37A120G 120GB SSD   | 16       | 16     | 2.46%   |
| Toshiba DT01ACA050 500GB           | 11       | 14     | 1.69%   |
| Samsung Electronics HD103UJ 1TB    | 10       | 27     | 1.54%   |
| Toshiba DT01ACA100 1TB             | 9        | 19     | 1.38%   |
| WDC WD5000AAKX-001CA0 500GB        | 7        | 7      | 1.08%   |
| WDC WD5000AADS-00S9B0 500GB        | 7        | 8      | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6        | 8      | 0.92%   |
| Samsung Electronics HD321KJ 320GB  | 6        | 6      | 0.92%   |
| Samsung Electronics HD161HJ 160GB  | 6        | 6      | 0.92%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 5        | 9      | 0.77%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 5        | 12     | 0.77%   |
| Seagate ST500LT012-9WS142 500GB    | 5        | 6      | 0.77%   |
| Seagate ST3250318AS 250GB          | 5        | 9      | 0.77%   |
| Seagate ST3160815AS 160GB          | 5        | 6      | 0.77%   |
| Seagate ST3160318AS 160GB          | 5        | 5      | 0.77%   |
| Samsung Electronics SP2504C 250GB  | 5        | 9      | 0.77%   |
| Samsung Electronics HD502HJ 500GB  | 5        | 8      | 0.77%   |
| Samsung Electronics HD103SI 1TB    | 5        | 5      | 0.77%   |
| Maxtor 6Y080M0 82GB                | 5        | 6      | 0.77%   |
| WDC WD3200AAKS-00L9A0 320GB        | 4        | 6      | 0.62%   |
| WDC WD15EARS-00MVWB0 1TB           | 4        | 10     | 0.62%   |
| WDC WD10PURZ-85U8XY0 1TB           | 4        | 12     | 0.62%   |
| WDC WD10EARS-00Y5B1 1TB            | 4        | 13     | 0.62%   |
| WDC WD10EALX-009BA0 1TB            | 4        | 5      | 0.62%   |
| Seagate ST380815AS 80GB            | 4        | 7      | 0.62%   |
| Seagate ST3160812AS 160GB          | 4        | 4      | 0.62%   |
| Samsung Electronics SP2004C 200GB  | 4        | 7      | 0.62%   |
| Samsung Electronics HD161GJ 160GB  | 4        | 5      | 0.62%   |
| Samsung Electronics HD103SJ 1TB    | 4        | 4      | 0.62%   |
| Samsung Electronics HD082GJ 80GB   | 4        | 4      | 0.62%   |
| Samsung Electronics HD080HJ 80GB   | 4        | 4      | 0.62%   |
| Maxtor 2B020H1 20GB                | 4        | 8      | 0.62%   |
| Hitachi HTS545050B9A300 500GB      | 4        | 6      | 0.62%   |
| WDC WD5000AAKX-07U6AA0 500GB       | 3        | 5      | 0.46%   |
| WDC WD10EZEX-22MFCA0 1TB           | 3        | 3      | 0.46%   |
| SK hynix SC210 2.5 7MM 128GB SSD   | 3        | 6      | 0.46%   |
| Seagate ST4000DM000-1F2168 4TB     | 3        | 8      | 0.46%   |
| Seagate ST3500418AS 500GB          | 3        | 6      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 172      | 295    | 27.92%  |
| Seagate             | 123      | 179    | 19.97%  |
| Samsung Electronics | 104      | 161    | 16.88%  |
| Toshiba             | 41       | 68     | 6.66%   |
| Hitachi             | 37       | 57     | 6.01%   |
| Kingston            | 36       | 47     | 5.84%   |
| Maxtor              | 30       | 44     | 4.87%   |
| A-DATA Technology   | 26       | 50     | 4.22%   |
| HGST                | 8        | 9      | 1.3%    |
| Fujitsu             | 7        | 7      | 1.14%   |
| Intel               | 6        | 13     | 0.97%   |
| SK hynix            | 3        | 6      | 0.49%   |
| Hewlett-Packard     | 3        | 3      | 0.49%   |
| WD MediaMax         | 2        | 4      | 0.32%   |
| KingSpec            | 2        | 2      | 0.32%   |
| Intenso             | 2        | 2      | 0.32%   |
| SATAFIRM            | 1        | 1      | 0.16%   |
| SanDisk             | 1        | 1      | 0.16%   |
| QUANTUM             | 1        | 1      | 0.16%   |
| Patriot             | 1        | 1      | 0.16%   |
| OCZ                 | 1        | 3      | 0.16%   |
| LITEON              | 1        | 1      | 0.16%   |
| Leven               | 1        | 1      | 0.16%   |
| Kingmax             | 1        | 1      | 0.16%   |
| ICY BOX             | 1        | 2      | 0.16%   |
| IBM/Hitachi         | 1        | 1      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |
| China               | 1        | 1      | 0.16%   |
| BIWIN               | 1        | 1      | 0.16%   |
| ASMT                | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 169      | 291    | 32.31%  |
| Seagate             | 123      | 179    | 23.52%  |
| Samsung Electronics | 100      | 156    | 19.12%  |
| Toshiba             | 40       | 67     | 7.65%   |
| Hitachi             | 37       | 57     | 7.07%   |
| Maxtor              | 30       | 44     | 5.74%   |
| HGST                | 8        | 9      | 1.53%   |
| Fujitsu             | 7        | 7      | 1.34%   |
| WD MediaMax         | 2        | 4      | 0.38%   |
| Hewlett-Packard     | 2        | 2      | 0.38%   |
| QUANTUM             | 1        | 1      | 0.19%   |
| ICY BOX             | 1        | 2      | 0.19%   |
| IBM/Hitachi         | 1        | 1      | 0.19%   |
| ExcelStor           | 1        | 1      | 0.19%   |
| ASMT                | 1        | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 444      | 822    | 82.99%  |
| SSD  | 88       | 139    | 16.45%  |
| NVMe | 3        | 3      | 0.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 2        | 3      | 18.18%  |
| Samsung Electronics HD103SJ 1TB   | 2        | 3      | 18.18%  |
| Zheino CHN-NGFFNV2280-256 256GB   | 1        | 1      | 9.09%   |
| Seagate ST9160412AS 160GB         | 1        | 1      | 9.09%   |
| Seagate ST380815AS 80GB           | 1        | 3      | 9.09%   |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 9.09%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 9.09%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 9.09%   |
| ExcelStor Technology J8160S 160GB | 1        | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 54.55%  |
| Seagate             | 2        | 4      | 18.18%  |
| Zheino              | 1        | 1      | 9.09%   |
| Hewlett-Packard     | 1        | 1      | 9.09%   |
| ExcelStor           | 1        | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1153     | 3642   | 52.34%  |
| Detected | 526      | 1359   | 23.88%  |
| Malfunc  | 513      | 964    | 23.29%  |
| Failed   | 11       | 15     | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1201     | 52.74%  |
| AMD                              | 494      | 21.7%   |
| Samsung Electronics              | 95       | 4.17%   |
| JMicron Technology               | 82       | 3.6%    |
| Kingston Technology Company      | 72       | 3.16%   |
| ASMedia Technology               | 70       | 3.07%   |
| Nvidia                           | 64       | 2.81%   |
| Marvell Technology Group         | 40       | 1.76%   |
| Phison Electronics               | 25       | 1.1%    |
| SanDisk                          | 20       | 0.88%   |
| VIA Technologies                 | 15       | 0.66%   |
| Silicon Motion                   | 15       | 0.66%   |
| Silicon Image                    | 12       | 0.53%   |
| ADATA Technology                 | 12       | 0.53%   |
| Realtek Semiconductor            | 11       | 0.48%   |
| LSI Logic / Symbios Logic        | 11       | 0.48%   |
| Micron/Crucial Technology        | 5        | 0.22%   |
| Integrated Technology Express    | 5        | 0.22%   |
| SK hynix                         | 4        | 0.18%   |
| KIOXIA                           | 3        | 0.13%   |
| Broadcom / LSI                   | 3        | 0.13%   |
| Adaptec                          | 3        | 0.13%   |
| Micron Technology                | 2        | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.09%   |
| HighPoint Technologies           | 2        | 0.09%   |
| 3ware                            | 2        | 0.09%   |
| TenaFe                           | 1        | 0.04%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| Seagate Technology               | 1        | 0.04%   |
| Promise Technology               | 1        | 0.04%   |
| OCZ Technology Group             | 1        | 0.04%   |
| Initio                           | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 253      | 8.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 184      | 5.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 151      | 4.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 139      | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 99       | 3.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 95       | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 89       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 82       | 2.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 81       | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 77       | 2.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 74       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 68       | 2.16%   |
| AMD FCH IDE Controller                                                                  | 65       | 2.07%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 61       | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 59       | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 59       | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 57       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 57       | 1.81%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 55       | 1.75%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 53       | 1.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 48       | 1.53%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44       | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 39       | 1.24%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 33       | 1.05%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 32       | 1.02%   |
| Nvidia MCP61 SATA Controller                                                            | 31       | 0.99%   |
| JMicron JMB368 IDE controller                                                           | 30       | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 29       | 0.92%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 27       | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.86%   |
| Nvidia MCP61 IDE                                                                        | 26       | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 25       | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 25       | 0.8%    |
| AMD FCH SATA Controller D                                                               | 22       | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                                  | 22       | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 21       | 0.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 21       | 0.67%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 21       | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 20       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1252     | 52.76%  |
| IDE  | 758      | 31.94%  |
| NVMe | 238      | 10.03%  |
| RAID | 105      | 4.42%   |
| SAS  | 11       | 0.46%   |
| SCSI | 9        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1224     | 68.76%  |
| AMD          | 554      | 31.12%  |
| CentaurHauls | 2        | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 43       | 2.39%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36       | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 30       | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 26       | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 26       | 1.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 24       | 1.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 22       | 1.22%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 22       | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 1%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 18       | 1%      |
| AMD FX-6300 Six-Core Processor              | 18       | 1%      |
| Intel Core i5-7500 CPU @ 3.40GHz            | 17       | 0.95%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 17       | 0.95%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.89%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 16       | 0.89%   |
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 16       | 0.89%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 15       | 0.83%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 14       | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 14       | 0.78%   |
| Intel Pentium 4 CPU 3.00GHz                 | 12       | 0.67%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 12       | 0.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 11       | 0.61%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 11       | 0.61%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 11       | 0.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 11       | 0.61%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 11       | 0.61%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 11       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 11       | 0.61%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11       | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 10       | 0.56%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 10       | 0.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 10       | 0.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 10       | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 10       | 0.56%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 10       | 0.56%   |
| AMD Athlon II X2 260 Processor              | 10       | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 0.5%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 319      | 17.8%   |
| Intel Core i3           | 194      | 10.83%  |
| Intel Core 2 Duo        | 154      | 8.59%   |
| AMD Ryzen 5             | 91       | 5.08%   |
| Intel Core i7           | 89       | 4.97%   |
| Intel Xeon              | 86       | 4.8%    |
| Intel Celeron           | 71       | 3.96%   |
| Intel Pentium           | 70       | 3.91%   |
| Intel Core 2 Quad       | 63       | 3.52%   |
| Intel Pentium Dual-Core | 58       | 3.24%   |
| AMD A8                  | 56       | 3.13%   |
| AMD FX                  | 55       | 3.07%   |
| AMD Ryzen 7             | 49       | 2.73%   |
| AMD Athlon II X2        | 42       | 2.34%   |
| AMD Athlon 64 X2        | 31       | 1.73%   |
| AMD Ryzen 3             | 28       | 1.56%   |
| AMD Phenom II X4        | 27       | 1.51%   |
| Other                   | 26       | 1.45%   |
| Intel Core 2            | 24       | 1.34%   |
| AMD A4                  | 24       | 1.34%   |
| Intel Pentium 4         | 22       | 1.23%   |
| Intel Pentium Dual      | 19       | 1.06%   |
| AMD A10                 | 18       | 1%      |
| Intel Atom              | 17       | 0.95%   |
| AMD A6                  | 14       | 0.78%   |
| Intel Pentium D         | 12       | 0.67%   |
| AMD Athlon II X4        | 12       | 0.67%   |
| AMD Sempron             | 11       | 0.61%   |
| AMD Ryzen 9             | 11       | 0.61%   |
| AMD Athlon Dual Core    | 11       | 0.61%   |
| AMD Athlon X4           | 10       | 0.56%   |
| AMD Athlon              | 10       | 0.56%   |
| AMD Athlon 64           | 6        | 0.33%   |
| AMD Phenom II X6        | 5        | 0.28%   |
| AMD Phenom II X2        | 5        | 0.28%   |
| AMD GX                  | 5        | 0.28%   |
| Intel Core i9           | 4        | 0.22%   |
| Intel Celeron D         | 4        | 0.22%   |
| AMD Phenom              | 4        | 0.22%   |
| Intel Pentium Gold      | 3        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 779      | 43.33%  |
| 4       | 605      | 33.65%  |
| 6       | 169      | 9.4%    |
| 1       | 102      | 5.67%   |
| 8       | 75       | 4.17%   |
| 3       | 31       | 1.72%   |
| 12      | 14       | 0.78%   |
| 16      | 9        | 0.5%    |
| 18      | 5        | 0.28%   |
| 10      | 4        | 0.22%   |
| 14      | 2        | 0.11%   |
| 36      | 1        | 0.06%   |
| 28      | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1765     | 99.05%  |
| 2      | 17       | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1059     | 59.1%   |
| 2       | 732      | 40.85%  |
| Unknown | 1        | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1769     | 99.27%  |
| 32-bit         | 7        | 0.39%   |
| Unknown        | 6        | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 346      | 18.52%  |
| 0x1067a    | 186      | 9.96%   |
| 0x306c3    | 149      | 7.98%   |
| 0x206a7    | 124      | 6.64%   |
| 0x306a9    | 101      | 5.41%   |
| 0x06001119 | 78       | 4.18%   |
| 0x010000c8 | 57       | 3.05%   |
| 0x506e3    | 54       | 2.89%   |
| 0x906e9    | 44       | 2.36%   |
| 0x10676    | 40       | 2.14%   |
| 0x6fb      | 34       | 1.82%   |
| 0x0800820d | 34       | 1.82%   |
| 0x6fd      | 32       | 1.71%   |
| 0x906ea    | 31       | 1.66%   |
| 0x06000852 | 27       | 1.45%   |
| 0x08701021 | 20       | 1.07%   |
| 0x06003106 | 18       | 0.96%   |
| 0x10677    | 17       | 0.91%   |
| 0x6f2      | 16       | 0.86%   |
| 0x106e5    | 15       | 0.8%    |
| 0x08001138 | 15       | 0.8%    |
| 0xa0653    | 14       | 0.75%   |
| 0x906eb    | 14       | 0.75%   |
| 0x206c2    | 14       | 0.75%   |
| 0x20655    | 14       | 0.75%   |
| 0x0600084f | 14       | 0.75%   |
| 0x106a5    | 12       | 0.64%   |
| 0x03000027 | 12       | 0.64%   |
| 0xf43      | 11       | 0.59%   |
| 0x010000db | 11       | 0.59%   |
| 0x08108109 | 10       | 0.54%   |
| 0x0810100b | 10       | 0.54%   |
| 0x0600063e | 10       | 0.54%   |
| 0x20652    | 9        | 0.48%   |
| 0x6f6      | 8        | 0.43%   |
| 0x0700010f | 8        | 0.43%   |
| 0x010000c7 | 8        | 0.43%   |
| 0xf41      | 7        | 0.37%   |
| 0x0a50000f | 7        | 0.37%   |
| 0x0a20120a | 7        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 254      | 14.23%  |
| Haswell          | 191      | 10.7%   |
| SandyBridge      | 151      | 8.46%   |
| KabyLake         | 129      | 7.23%   |
| Piledriver       | 126      | 7.06%   |
| IvyBridge        | 121      | 6.78%   |
| K10              | 109      | 6.11%   |
| Core             | 101      | 5.66%   |
| Skylake          | 76       | 4.26%   |
| K8 Hammer        | 55       | 3.08%   |
| Zen+             | 52       | 2.91%   |
| Zen 2            | 48       | 2.69%   |
| NetBurst         | 47       | 2.63%   |
| Westmere         | 45       | 2.52%   |
| Zen 3            | 41       | 2.3%    |
| Zen              | 39       | 2.18%   |
| Nehalem          | 28       | 1.57%   |
| Steamroller      | 27       | 1.51%   |
| CometLake        | 22       | 1.23%   |
| Silvermont       | 18       | 1.01%   |
| Bonnell          | 13       | 0.73%   |
| Unknown          | 13       | 0.73%   |
| K10 Llano        | 12       | 0.67%   |
| Bulldozer        | 12       | 0.67%   |
| Excavator        | 11       | 0.62%   |
| Jaguar           | 10       | 0.56%   |
| Alderlake Hybrid | 9        | 0.5%    |
| Goldmont plus    | 7        | 0.39%   |
| Puma             | 6        | 0.34%   |
| Icelake          | 5        | 0.28%   |
| Bobcat           | 3        | 0.17%   |
| Tremont          | 1        | 0.06%   |
| K8 & K10 hybrid  | 1        | 0.06%   |
| K6               | 1        | 0.06%   |
| Goldmont         | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 660      | 34.55%  |
| Intel                      | 634      | 33.19%  |
| AMD                        | 604      | 31.62%  |
| VIA Technologies           | 6        | 0.31%   |
| ASPEED Technology          | 3        | 0.16%   |
| ATI Technologies           | 2        | 0.1%    |
| Matrox Electronics Systems | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 94       | 4.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 80       | 4.02%   |
| Nvidia GK208B [GeForce GT 710]                                              | 69       | 3.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 69       | 3.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 61       | 3.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 59       | 2.96%   |
| Intel HD Graphics 530                                                       | 47       | 2.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 43       | 2.16%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 38       | 1.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 37       | 1.86%   |
| AMD Richland [Radeon HD 8570D]                                              | 37       | 1.86%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 35       | 1.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 35       | 1.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 31       | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 30       | 1.51%   |
| Intel HD Graphics 630                                                       | 24       | 1.21%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 23       | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 22       | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 22       | 1.11%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 21       | 1.06%   |
| Nvidia GF119 [GeForce GT 610]                                               | 20       | 1.01%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 18       | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 17       | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 16       | 0.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 16       | 0.8%    |
| Nvidia GF108 [GeForce GT 630]                                               | 16       | 0.8%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 15       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 14       | 0.7%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 14       | 0.7%    |
| Nvidia G94 [GeForce 9600 GT]                                                | 13       | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 13       | 0.65%   |
| AMD RS880 [Radeon HD 4200]                                                  | 13       | 0.65%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 13       | 0.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13       | 0.65%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 12       | 0.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 11       | 0.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 10       | 0.5%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 10       | 0.5%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 621      | 33.77%  |
| 1 x Intel                | 568      | 30.89%  |
| 1 x AMD                  | 542      | 29.47%  |
| 2 x AMD                  | 45       | 2.45%   |
| Intel + Nvidia           | 23       | 1.25%   |
| AMD + Nvidia             | 11       | 0.6%    |
| Intel + AMD              | 9        | 0.49%   |
| 1 x VIA                  | 6        | 0.33%   |
| 2 x Nvidia               | 5        | 0.27%   |
| 2 x Intel                | 2        | 0.11%   |
| 1 x ASPEED               | 2        | 0.11%   |
| 1 x Matrox               | 1        | 0.05%   |
| 1 x Intel + 3 x AMD      | 1        | 0.05%   |
| Intel + 2 x Nvidia       | 1        | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.05%   |
| AMD + ASPEED             | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1549     | 85.53%  |
| Proprietary | 171      | 9.44%   |
| Unknown     | 91       | 5.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 727      | 38.4%   |
| 0.51-1.0   | 335      | 17.7%   |
| 0.01-0.5   | 309      | 16.32%  |
| 1.01-2.0   | 244      | 12.89%  |
| 3.01-4.0   | 117      | 6.18%   |
| 7.01-8.0   | 79       | 4.17%   |
| 5.01-6.0   | 41       | 2.17%   |
| 2.01-3.0   | 21       | 1.11%   |
| 8.01-16.0  | 17       | 0.9%    |
| 16.01-24.0 | 3        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 389      | 21.59%  |
| Goldstar                | 310      | 17.2%   |
| Dell                    | 136      | 7.55%   |
| Ancor Communications    | 102      | 5.66%   |
| Philips                 | 100      | 5.55%   |
| BenQ                    | 93       | 5.16%   |
| Acer                    | 86       | 4.77%   |
| Hewlett-Packard         | 82       | 4.55%   |
| Fujitsu Siemens         | 52       | 2.89%   |
| AOC                     | 44       | 2.44%   |
| LG Electronics          | 27       | 1.5%    |
| Lenovo                  | 25       | 1.39%   |
| Eizo                    | 22       | 1.22%   |
| HannStar                | 21       | 1.17%   |
| ASUSTek Computer        | 19       | 1.05%   |
| Sony                    | 18       | 1%      |
| NEC Computers           | 18       | 1%      |
| Vestel Elektronik       | 17       | 0.94%   |
| HKC                     | 16       | 0.89%   |
| ViewSonic               | 14       | 0.78%   |
| Unknown                 | 13       | 0.72%   |
| Medion                  | 13       | 0.72%   |
| Iiyama                  | 12       | 0.67%   |
| Belinea                 | 11       | 0.61%   |
| IBM                     | 10       | 0.55%   |
| Chi Mei Optoelectronics | 9        | 0.5%    |
| Arnos Instruments       | 9        | 0.5%    |
| Panasonic               | 8        | 0.44%   |
| MStar                   | 8        | 0.44%   |
| OEM                     | 7        | 0.39%   |
| Toshiba                 | 6        | 0.33%   |
| Plain Tree Systems      | 6        | 0.33%   |
| Videoseven              | 5        | 0.28%   |
| NCS                     | 5        | 0.28%   |
| Gericom                 | 5        | 0.28%   |
| FUS                     | 5        | 0.28%   |
| KTC                     | 4        | 0.22%   |
| ___                     | 3        | 0.17%   |
| Orion                   | 3        | 0.17%   |
| Impression              | 3        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 32       | 1.69%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 17       | 0.9%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 14       | 0.74%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 13       | 0.69%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 12       | 0.63%   |
| Ancor Communications VW195 ACI19AB 1440x900 410x260mm 19.1-inch          | 12       | 0.63%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 11       | 0.58%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 11       | 0.58%   |
| HKC '' HKC1850 1360x768 304x228mm 15.0-inch                              | 11       | 0.58%   |
| HannStar Hanns.G HQ191 HSD0013 1280x1024 376x301mm 19.0-inch             | 11       | 0.58%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11       | 0.58%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 10       | 0.53%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 10       | 0.53%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 10       | 0.53%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 9        | 0.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 9        | 0.47%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 9        | 0.47%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                       | 9        | 0.47%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 8        | 0.42%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                    | 8        | 0.42%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                     | 8        | 0.42%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 8        | 0.42%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                         | 8        | 0.42%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 7        | 0.37%   |
| OEM 26W_LCD_TV OEM3700 1920x540                                          | 7        | 0.37%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                    | 7        | 0.37%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                   | 7        | 0.37%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 6        | 0.32%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch                 | 6        | 0.32%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch                | 6        | 0.32%   |
| Eizo S2202W ENC1976 1680x1050 474x297mm 22.0-inch                        | 6        | 0.32%   |
| Chi Mei Optoelectronics CMC 19" AD CMO0198 1280x1024 338x270mm 17.0-inch | 6        | 0.32%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 5        | 0.26%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                     | 5        | 0.26%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                    | 5        | 0.26%   |
| Goldstar TV GSM2412 1920x1080 940x530mm 42.5-inch                        | 5        | 0.26%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                     | 5        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5        | 0.26%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                   | 5        | 0.26%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                    | 5        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 732      | 41.71%  |
| 1280x1024 (SXGA)   | 293      | 16.7%   |
| 1680x1050 (WSXGA+) | 144      | 8.21%   |
| 1440x900 (WXGA+)   | 121      | 6.89%   |
| 3840x2160 (4K)     | 101      | 5.75%   |
| 1366x768 (WXGA)    | 71       | 4.05%   |
| 2560x1440 (QHD)    | 45       | 2.56%   |
| 2560x1080          | 39       | 2.22%   |
| 1360x768           | 35       | 1.99%   |
| 1920x1200 (WUXGA)  | 33       | 1.88%   |
| 1600x900 (HD+)     | 25       | 1.42%   |
| 1024x768 (XGA)     | 24       | 1.37%   |
| Unknown            | 21       | 1.2%    |
| 3840x1080          | 13       | 0.74%   |
| 1920x540           | 13       | 0.74%   |
| 1600x1200          | 8        | 0.46%   |
| 1280x720 (HD)      | 6        | 0.34%   |
| 2288x1287          | 4        | 0.23%   |
| 3440x1440          | 3        | 0.17%   |
| 3840x1200          | 2        | 0.11%   |
| 3280x1080          | 2        | 0.11%   |
| 2048x1536          | 2        | 0.11%   |
| 2048x1152          | 2        | 0.11%   |
| 1280x960           | 2        | 0.11%   |
| 1152x864           | 2        | 0.11%   |
| 7680x2160          | 1        | 0.06%   |
| 5760x2160          | 1        | 0.06%   |
| 3840x1920          | 1        | 0.06%   |
| 3600x1200          | 1        | 0.06%   |
| 3200x1080          | 1        | 0.06%   |
| 2880x1200          | 1        | 0.06%   |
| 2880x1024          | 1        | 0.06%   |
| 2304x1024          | 1        | 0.06%   |
| 1400x1050          | 1        | 0.06%   |
| 1280x800 (WXGA)    | 1        | 0.06%   |
| 1280x768           | 1        | 0.06%   |
| 1024x600           | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 277      | 15.34%  |
| 19      | 246      | 13.62%  |
| 23      | 184      | 10.19%  |
| 24      | 162      | 8.97%   |
| 17      | 144      | 7.97%   |
| 27      | 133      | 7.36%   |
| Unknown | 115      | 6.37%   |
| 22      | 111      | 6.15%   |
| 18      | 99       | 5.48%   |
| 20      | 45       | 2.49%   |
| 34      | 41       | 2.27%   |
| 31      | 40       | 2.21%   |
| 15      | 38       | 2.1%    |
| 84      | 34       | 1.88%   |
| 72      | 18       | 1%      |
| 40      | 17       | 0.94%   |
| 54      | 13       | 0.72%   |
| 12      | 9        | 0.5%    |
| 52      | 8        | 0.44%   |
| 42      | 8        | 0.44%   |
| 32      | 8        | 0.44%   |
| 65      | 6        | 0.33%   |
| 48      | 6        | 0.33%   |
| 46      | 5        | 0.28%   |
| 25      | 5        | 0.28%   |
| 60      | 4        | 0.22%   |
| 26      | 4        | 0.22%   |
| 64      | 3        | 0.17%   |
| 49      | 3        | 0.17%   |
| 14      | 3        | 0.17%   |
| 142     | 2        | 0.11%   |
| 85      | 2        | 0.11%   |
| 58      | 2        | 0.11%   |
| 39      | 2        | 0.11%   |
| 63      | 1        | 0.06%   |
| 55      | 1        | 0.06%   |
| 50      | 1        | 0.06%   |
| 47      | 1        | 0.06%   |
| 44      | 1        | 0.06%   |
| 43      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 612      | 34.63%  |
| 501-600        | 465      | 26.32%  |
| 301-350        | 176      | 9.96%   |
| 351-400        | 151      | 8.55%   |
| Unknown        | 115      | 6.51%   |
| 1501-2000      | 54       | 3.06%   |
| 1001-1500      | 54       | 3.06%   |
| 701-800        | 50       | 2.83%   |
| 601-700        | 45       | 2.55%   |
| 801-900        | 19       | 1.08%   |
| 201-300        | 13       | 0.74%   |
| 901-1000       | 10       | 0.57%   |
| More than 2000 | 2        | 0.11%   |
| 101-200        | 1        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 938      | 55.44%  |
| 5/4     | 283      | 16.73%  |
| 16/10   | 270      | 15.96%  |
| Unknown | 85       | 5.02%   |
| 4/3     | 51       | 3.01%   |
| 21/9    | 41       | 2.42%   |
| 3/2     | 11       | 0.65%   |
| 32/9    | 6        | 0.35%   |
| 6/5     | 5        | 0.3%    |
| 1.00    | 2        | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 617      | 34.6%   |
| 151-200        | 360      | 20.19%  |
| 141-150        | 220      | 12.34%  |
| 301-350        | 135      | 7.57%   |
| Unknown        | 115      | 6.45%   |
| More than 1000 | 98       | 5.5%    |
| 351-500        | 88       | 4.94%   |
| 251-300        | 56       | 3.14%   |
| 501-1000       | 42       | 2.36%   |
| 101-110        | 24       | 1.35%   |
| 111-120        | 14       | 0.79%   |
| 71-80          | 8        | 0.45%   |
| 91-100         | 3        | 0.17%   |
| 81-90          | 1        | 0.06%   |
| 61-70          | 1        | 0.06%   |
| 1-40           | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1159     | 68.78%  |
| 101-120 | 312      | 18.52%  |
| Unknown | 115      | 6.82%   |
| 1-50    | 65       | 3.86%   |
| 121-160 | 19       | 1.13%   |
| 161-240 | 15       | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1572     | 85.67%  |
| 2     | 159      | 8.66%   |
| 0     | 84       | 4.58%   |
| 3     | 20       | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1009     | 44.57%  |
| Intel                                  | 522      | 23.06%  |
| Qualcomm Atheros                       | 194      | 8.57%   |
| Broadcom                               | 91       | 4.02%   |
| Qualcomm Atheros Communications        | 64       | 2.83%   |
| Ralink Technology                      | 60       | 2.65%   |
| Broadcom Limited                       | 51       | 2.25%   |
| TP-Link                                | 48       | 2.12%   |
| Nvidia                                 | 44       | 1.94%   |
| Marvell Technology Group               | 26       | 1.15%   |
| Ralink                                 | 20       | 0.88%   |
| VIA Technologies                       | 13       | 0.57%   |
| Samsung Electronics                    | 12       | 0.53%   |
| ASUSTek Computer                       | 11       | 0.49%   |
| Aquantia                               | 9        | 0.4%    |
| Huawei Technologies                    | 8        | 0.35%   |
| Xiaomi                                 | 7        | 0.31%   |
| MediaTek                               | 7        | 0.31%   |
| Microsoft                              | 6        | 0.27%   |
| D-Link System                          | 6        | 0.27%   |
| IMC Networks                           | 5        | 0.22%   |
| Edimax Technology                      | 5        | 0.22%   |
| D-Link                                 | 5        | 0.22%   |
| Belkin Components                      | 5        | 0.22%   |
| Accton Technology                      | 4        | 0.18%   |
| Qualcomm                               | 3        | 0.13%   |
| ASIX Electronics                       | 3        | 0.13%   |
| ZyDAS                                  | 2        | 0.09%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.09%   |
| NetGear                                | 2        | 0.09%   |
| JMicron Technology                     | 2        | 0.09%   |
| Arduino SA                             | 2        | 0.09%   |
| TRENDnet                               | 1        | 0.04%   |
| Texas Instruments                      | 1        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| ShenZhen ShanWan Technology            | 1        | 0.04%   |
| Seeed Technology                       | 1        | 0.04%   |
| QLogic                                 | 1        | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 843      | 34.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 95       | 3.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 58       | 2.39%   |
| Qualcomm Atheros AR9271 802.11n                                        | 56       | 2.31%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 56       | 2.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 47       | 1.94%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 1.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37       | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 37       | 1.53%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 37       | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 35       | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 32       | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 30       | 1.24%   |
| Nvidia MCP61 Ethernet                                                  | 30       | 1.24%   |
| Ralink MT7601U Wireless Adapter                                        | 27       | 1.11%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 0.99%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 23       | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 0.87%   |
| Intel Ethernet Connection I217-V                                       | 18       | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18       | 0.74%   |
| Intel 82579V Gigabit Network Connection                                | 18       | 0.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 18       | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                   | 17       | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 16       | 0.66%   |
| Ralink RT5370 Wireless Adapter                                         | 14       | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 14       | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 13       | 0.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 13       | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13       | 0.54%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 13       | 0.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 12       | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12       | 0.5%    |
| Intel Wi-Fi 6 AX200                                                    | 12       | 0.5%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 12       | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10       | 0.41%   |
| Intel Ethernet Controller I225-V                                       | 10       | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 10       | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 9        | 0.37%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 9        | 0.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 8        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 105      | 20.92%  |
| Intel                           | 81       | 16.14%  |
| Qualcomm Atheros Communications | 64       | 12.75%  |
| Qualcomm Atheros                | 63       | 12.55%  |
| Ralink Technology               | 60       | 11.95%  |
| TP-Link                         | 48       | 9.56%   |
| Ralink                          | 20       | 3.98%   |
| ASUSTek Computer                | 11       | 2.19%   |
| Microsoft                       | 6        | 1.2%    |
| MediaTek                        | 6        | 1.2%    |
| Broadcom                        | 6        | 1.2%    |
| IMC Networks                    | 5        | 1%      |
| Edimax Technology               | 5        | 1%      |
| Belkin Components               | 5        | 1%      |
| D-Link                          | 4        | 0.8%    |
| ZyDAS                           | 2        | 0.4%    |
| NetGear                         | 2        | 0.4%    |
| D-Link System                   | 2        | 0.4%    |
| VIA Technologies                | 1        | 0.2%    |
| TRENDnet                        | 1        | 0.2%    |
| Texas Instruments               | 1        | 0.2%    |
| Mercucys                        | 1        | 0.2%    |
| Marvell Technology Group        | 1        | 0.2%    |
| Broadcom Limited                | 1        | 0.2%    |
| Accton Technology               | 1        | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 56       | 11.05%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 32       | 6.31%   |
| Ralink MT7601U Wireless Adapter                                               | 27       | 5.33%   |
| Ralink RT5370 Wireless Adapter                                                | 14       | 2.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 13       | 2.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 13       | 2.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 12       | 2.37%   |
| Intel Wi-Fi 6 AX200                                                           | 12       | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 10       | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 10       | 1.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 8        | 1.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 8        | 1.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 8        | 1.58%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 8        | 1.58%   |
| Intel Wireless 7260                                                           | 8        | 1.58%   |
| Intel Wireless 3165                                                           | 8        | 1.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 8        | 1.58%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 7        | 1.38%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 7        | 1.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 7        | 1.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 7        | 1.38%   |
| Realtek 802.11ac NIC                                                          | 6        | 1.18%   |
| Intel Wireless 7265                                                           | 6        | 1.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 6        | 1.18%   |
| TP-Link Archer T4U ver.3                                                      | 5        | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 5        | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 5        | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 5        | 0.99%   |
| Ralink RT2070 Wireless Adapter                                                | 5        | 0.99%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5        | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4        | 0.79%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 4        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.79%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 4        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4        | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4        | 0.79%   |
| Intel Wireless 3160                                                           | 4        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4        | 0.79%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 4        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 968      | 51.99%  |
| Intel                                  | 482      | 25.89%  |
| Qualcomm Atheros                       | 135      | 7.25%   |
| Broadcom                               | 85       | 4.56%   |
| Broadcom Limited                       | 50       | 2.69%   |
| Nvidia                                 | 44       | 2.36%   |
| Marvell Technology Group               | 25       | 1.34%   |
| Samsung Electronics                    | 12       | 0.64%   |
| VIA Technologies                       | 11       | 0.59%   |
| Aquantia                               | 9        | 0.48%   |
| Xiaomi                                 | 7        | 0.38%   |
| Huawei Technologies                    | 6        | 0.32%   |
| D-Link System                          | 4        | 0.21%   |
| Qualcomm                               | 3        | 0.16%   |
| ASIX Electronics                       | 3        | 0.16%   |
| Accton Technology                      | 3        | 0.16%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.11%   |
| JMicron Technology                     | 2        | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.05%   |
| QLogic                                 | 1        | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1        | 0.05%   |
| MediaTek                               | 1        | 0.05%   |
| HMD Global                             | 1        | 0.05%   |
| Hangzhou Silan Microelectronics        | 1        | 0.05%   |
| Google                                 | 1        | 0.05%   |
| DisplayLink                            | 1        | 0.05%   |
| D-Link                                 | 1        | 0.05%   |
| American Megatrends                    | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 843      | 44.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 95       | 4.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 58       | 3.04%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 56       | 2.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 47       | 2.47%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37       | 1.94%   |
| Intel I211 Gigabit Network Connection                                  | 37       | 1.94%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 37       | 1.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 35       | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 30       | 1.57%   |
| Nvidia MCP61 Ethernet                                                  | 30       | 1.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 1.26%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 23       | 1.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 1.1%    |
| Intel Ethernet Connection I217-V                                       | 18       | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18       | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 18       | 0.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 18       | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 17       | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 16       | 0.84%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 14       | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13       | 0.68%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 13       | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12       | 0.63%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 12       | 0.63%   |
| Intel Ethernet Controller I225-V                                       | 10       | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 9        | 0.47%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 9        | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 8        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 0.42%   |
| Intel 82578DM Gigabit Network Connection                               | 8        | 0.42%   |
| Intel 82574L Gigabit Network Connection                                | 8        | 0.42%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 8        | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 7        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6        | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6        | 0.31%   |
| Intel I210 Gigabit Network Connection                                  | 6        | 0.31%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 6        | 0.31%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 6        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1754     | 78.37%  |
| WiFi     | 475      | 21.22%  |
| Modem    | 7        | 0.31%   |
| Unknown  | 2        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1527     | 83.58%  |
| WiFi     | 300      | 16.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1453     | 80.9%   |
| 2     | 283      | 15.76%  |
| 3     | 28       | 1.56%   |
| 0     | 27       | 1.5%    |
| 4     | 4        | 0.22%   |
| 5     | 1        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1472     | 78.89%  |
| Yes  | 394      | 21.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 127      | 42.47%  |
| Intel                           | 79       | 26.42%  |
| ASUSTek Computer                | 22       | 7.36%   |
| Broadcom                        | 18       | 6.02%   |
| Realtek Semiconductor           | 8        | 2.68%   |
| IMC Networks                    | 7        | 2.34%   |
| Conwise Technology              | 7        | 2.34%   |
| Belkin Components               | 7        | 2.34%   |
| Qualcomm Atheros Communications | 4        | 1.34%   |
| Logitech                        | 4        | 1.34%   |
| Integrated System Solution      | 4        | 1.34%   |
| TP-Link                         | 3        | 1%      |
| MediaTek                        | 2        | 0.67%   |
| Hewlett-Packard                 | 2        | 0.67%   |
| Foxconn / Hon Hai               | 2        | 0.67%   |
| Edimax Technology               | 2        | 0.67%   |
| Lite-On Technology              | 1        | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 127      | 42.47%  |
| Intel Bluetooth wireless interface                      | 24       | 8.03%   |
| Intel AX200 Bluetooth                                   | 12       | 4.01%   |
| Intel Wireless-AC 3168 Bluetooth                        | 10       | 3.34%   |
| Intel AX210 Bluetooth                                   | 8        | 2.68%   |
| Conwise CW6622                                          | 7        | 2.34%   |
| ASUS ASUS USB-BT500                                     | 7        | 2.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 6        | 2.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 6        | 2.01%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 6        | 2.01%   |
| ASUS Bluetooth Radio                                    | 6        | 2.01%   |
| Intel Bluetooth Device                                  | 5        | 1.67%   |
| Broadcom BCM2035 Bluetooth dongle                       | 5        | 1.67%   |
| Realtek Bluetooth Radio                                 | 4        | 1.34%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 4        | 1.34%   |
| Intel AX201 Bluetooth                                   | 4        | 1.34%   |
| TP-Link UB500 Adapter                                   | 3        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver           | 3        | 1%      |
| IMC Networks Bluetooth Radio                            | 3        | 1%      |
| Broadcom Bluetooth dongle                               | 3        | 1%      |
| Broadcom Bluetooth 3.0 Device                           | 3        | 1%      |
| Belkin Components Bluetooth Mini Dongle                 | 3        | 1%      |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 0.67%   |
| Qualcomm Atheros  Bluetooth Device                      | 2        | 0.67%   |
| MediaTek Wireless_Device                                | 2        | 0.67%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 2        | 0.67%   |
| Integrated System Solution Bluetooth Device             | 2        | 0.67%   |
| IMC Networks Wireless_Device                            | 2        | 0.67%   |
| HP Bluetooth Adapter                                    | 2        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                       | 2        | 0.67%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 0.67%   |
| Broadcom HP Portable Bumble Bee                         | 2        | 0.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 2        | 0.67%   |
| Broadcom BCM2045 Bluetooth                              | 2        | 0.67%   |
| Belkin Components F8T013 Bluetooth Adapter              | 2        | 0.67%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 0.67%   |
| Realtek RTL8821A Bluetooth                              | 1        | 0.33%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1        | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1159     | 42.15%  |
| AMD                                  | 721      | 26.22%  |
| Nvidia                               | 593      | 21.56%  |
| C-Media Electronics                  | 89       | 3.24%   |
| Creative Labs                        | 42       | 1.53%   |
| Texas Instruments                    | 15       | 0.55%   |
| Logitech                             | 13       | 0.47%   |
| VIA Technologies                     | 11       | 0.4%    |
| JMTek                                | 10       | 0.36%   |
| Generalplus Technology               | 10       | 0.36%   |
| ASUSTek Computer                     | 8        | 0.29%   |
| Kingston Technology                  | 7        | 0.25%   |
| Plantronics                          | 5        | 0.18%   |
| Creative Technology                  | 5        | 0.18%   |
| BEHRINGER International              | 5        | 0.18%   |
| SteelSeries ApS                      | 4        | 0.15%   |
| GN Netcom                            | 4        | 0.15%   |
| Samson Technologies                  | 3        | 0.11%   |
| Focusrite-Novation                   | 3        | 0.11%   |
| Ensoniq                              | 3        | 0.11%   |
| Yamaha                               | 2        | 0.07%   |
| Promethean Limited                   | 2        | 0.07%   |
| ELMCU                                | 2        | 0.07%   |
| DigiTech                             | 2        | 0.07%   |
| ATI Technologies                     | 2        | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.04%   |
| Tenx Technology                      | 1        | 0.04%   |
| Syntek                               | 1        | 0.04%   |
| Superlux digit                       | 1        | 0.04%   |
| Sunplus Technology                   | 1        | 0.04%   |
| SM950T Microphone                    | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]     | 1        | 0.04%   |
| Rotel                                | 1        | 0.04%   |
| Realtek Semiconductor                | 1        | 0.04%   |
| Pixart Imaging                       | 1        | 0.04%   |
| Nektar                               | 1        | 0.04%   |
| MCS                                  | 1        | 0.04%   |
| LG Electronics                       | 1        | 0.04%   |
| KORG                                 | 1        | 0.04%   |
| JBL                                  | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 180      | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 158      | 4.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 154      | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 151      | 4.66%   |
| AMD FCH Azalia Controller                                                         | 135      | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 113      | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 104      | 3.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 95       | 2.93%   |
| Intel 200 Series PCH HD Audio                                                     | 81       | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 79       | 2.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 70       | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 69       | 2.13%   |
| AMD Trinity HDMI Audio Controller                                                 | 65       | 2.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 64       | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 63       | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 62       | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                          | 59       | 1.82%   |
| Nvidia High Definition Audio Controller                                           | 56       | 1.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 54       | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 54       | 1.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 53       | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 48       | 1.48%   |
| Nvidia GP106 High Definition Audio Controller                                     | 38       | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 38       | 1.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 38       | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 34       | 1.05%   |
| Intel Cannon Lake PCH cAVS                                                        | 31       | 0.96%   |
| Nvidia MCP61 High Definition Audio                                                | 30       | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                                | 30       | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 28       | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 26       | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                                | 25       | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 23       | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 23       | 0.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 23       | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                                     | 22       | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 22       | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                          | 22       | 0.68%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 20       | 0.62%   |
| C-Media Electronics CM108 Audio Controller                                        | 20       | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 438      | 25.48%  |
| Kingston                   | 404      | 23.5%   |
| SK hynix                   | 177      | 10.3%   |
| Samsung Electronics        | 168      | 9.77%   |
| Micron Technology          | 88       | 5.12%   |
| Kingmax                    | 73       | 4.25%   |
| Crucial                    | 61       | 3.55%   |
| Corsair                    | 60       | 3.49%   |
| G.Skill                    | 58       | 3.37%   |
| Nanya Technology           | 48       | 2.79%   |
| Elpida                     | 22       | 1.28%   |
| Team                       | 17       | 0.99%   |
| CSX                        | 15       | 0.87%   |
| Ramaxel Technology         | 11       | 0.64%   |
| Patriot                    | 8        | 0.47%   |
| A-DATA Technology          | 7        | 0.41%   |
| Transcend                  | 6        | 0.35%   |
| Melco                      | 6        | 0.35%   |
| Qimonda                    | 4        | 0.23%   |
| OCZ                        | 4        | 0.23%   |
| Kingmax Semiconductor      | 4        | 0.23%   |
| GeIL                       | 4        | 0.23%   |
| Apacer                     | 4        | 0.23%   |
| Silicon Power              | 2        | 0.12%   |
| Intersil                   | 2        | 0.12%   |
| Hikvision                  | 2        | 0.12%   |
| H                          | 2        | 0.12%   |
| Golden Empire              | 2        | 0.12%   |
| 48spaces                   | 2        | 0.12%   |
| Unknown                    | 2        | 0.12%   |
| ZION                       | 1        | 0.06%   |
| Unknown (ABCD)             | 1        | 0.06%   |
| Unknown (7F7F7F7F7F970000) | 1        | 0.06%   |
| Unknown (09D5)             | 1        | 0.06%   |
| Unigen                     | 1        | 0.06%   |
| Toshiba-0098               | 1        | 0.06%   |
| Toshiba                    | 1        | 0.06%   |
| SGS/Thomson                | 1        | 0.06%   |
| Ramos Technology           | 1        | 0.06%   |
| Princeton                  | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 45       | 2.24%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 42       | 2.09%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 35       | 1.74%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 25       | 1.25%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 21       | 1.05%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 19       | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 19       | 0.95%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 18       | 0.9%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 17       | 0.85%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 16       | 0.8%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 16       | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 15       | 0.75%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 14       | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 13       | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 13       | 0.65%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 13       | 0.65%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 13       | 0.65%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 13       | 0.65%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 12       | 0.6%    |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 11       | 0.55%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 10       | 0.5%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 10       | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 9        | 0.45%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 9        | 0.45%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 9        | 0.45%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 9        | 0.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 9        | 0.45%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s    | 9        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 8        | 0.4%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 8        | 0.4%    |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 8        | 0.4%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 8        | 0.4%    |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s   | 8        | 0.4%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s   | 8        | 0.4%    |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s | 8        | 0.4%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 8        | 0.4%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s    | 8        | 0.4%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 8        | 0.4%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 8        | 0.4%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 8        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 566      | 37.88%  |
| DDR4    | 352      | 23.56%  |
| DDR2    | 194      | 12.99%  |
| Unknown | 175      | 11.71%  |
| SDRAM   | 152      | 10.17%  |
| DDR     | 42       | 2.81%   |
| DDR5    | 9        | 0.6%    |
| LPDDR4  | 3        | 0.2%    |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1375     | 96.29%  |
| SODIMM       | 45       | 3.15%   |
| RIMM         | 5        | 0.35%   |
| Row Of Chips | 2        | 0.14%   |
| FB-DIMM      | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 516      | 31.07%  |
| 2048  | 451      | 27.15%  |
| 8192  | 350      | 21.07%  |
| 1024  | 194      | 11.68%  |
| 16384 | 88       | 5.3%    |
| 512   | 32       | 1.93%   |
| 32768 | 26       | 1.57%   |
| 256   | 4        | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 300      | 17.77%  |
| 1333    | 252      | 14.93%  |
| 800     | 175      | 10.37%  |
| 667     | 97       | 5.75%   |
| 2400    | 85       | 5.04%   |
| Unknown | 80       | 4.74%   |
| 2133    | 79       | 4.68%   |
| 1866    | 68       | 4.03%   |
| 3200    | 64       | 3.79%   |
| 3600    | 44       | 2.61%   |
| 1867    | 44       | 2.61%   |
| 2667    | 39       | 2.31%   |
| 400     | 34       | 2.01%   |
| 1066    | 31       | 1.84%   |
| 533     | 23       | 1.36%   |
| 3733    | 20       | 1.18%   |
| 2666    | 19       | 1.13%   |
| 1800    | 19       | 1.13%   |
| 2933    | 16       | 0.95%   |
| 2048    | 16       | 0.95%   |
| 3400    | 15       | 0.89%   |
| 3466    | 14       | 0.83%   |
| 1067    | 14       | 0.83%   |
| 3000    | 12       | 0.71%   |
| 2000    | 10       | 0.59%   |
| 1639    | 10       | 0.59%   |
| 3151    | 9        | 0.53%   |
| 49926   | 8        | 0.47%   |
| 1648    | 7        | 0.41%   |
| 1334    | 6        | 0.36%   |
| 5808    | 5        | 0.3%    |
| 3800    | 5        | 0.3%    |
| 3334    | 5        | 0.3%    |
| 333     | 5        | 0.3%    |
| 3933    | 4        | 0.24%   |
| 3333    | 4        | 0.24%   |
| 1400    | 4        | 0.24%   |
| 2733    | 3        | 0.18%   |
| 2200    | 3        | 0.18%   |
| 2134    | 3        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 54       | 47.79%  |
| Samsung Electronics   | 27       | 23.89%  |
| Canon                 | 15       | 13.27%  |
| Brother Industries    | 7        | 6.19%   |
| Seiko Epson           | 4        | 3.54%   |
| QinHeng Electronics   | 2        | 1.77%   |
| Xerox                 | 1        | 0.88%   |
| STMicroelectronics    | 1        | 0.88%   |
| Prolific Technology   | 1        | 0.88%   |
| Lexmark International | 1        | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2600 series                                    | 9        | 7.83%   |
| Samsung ML-2010P Mono Laser Printer                       | 6        | 5.22%   |
| Samsung M2020 Series                                      | 6        | 5.22%   |
| Samsung ML-1640 Series Laser Printer                      | 4        | 3.48%   |
| HP LaserJet 1020                                          | 4        | 3.48%   |
| HP OfficeJet 6950                                         | 3        | 2.61%   |
| HP Deskjet 2050 J510                                      | 3        | 2.61%   |
| Samsung SCX-3400 Series                                   | 2        | 1.74%   |
| Samsung ML-1660 Series                                    | 2        | 1.74%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 2        | 1.74%   |
| QinHeng CH340S                                            | 2        | 1.74%   |
| HP LaserJet P1005                                         | 2        | 1.74%   |
| HP LaserJet 1018                                          | 2        | 1.74%   |
| HP LaserJet 1010                                          | 2        | 1.74%   |
| HP LaserJet 1000                                          | 2        | 1.74%   |
| HP DeskJet F4100 Printer series                           | 2        | 1.74%   |
| HP Deskjet F2280 series                                   | 2        | 1.74%   |
| HP DeskJet F2100 Printer series                           | 2        | 1.74%   |
| HP DeskJet 840c                                           | 2        | 1.74%   |
| HP Deskjet 3520 series                                    | 2        | 1.74%   |
| HP DeskJet 2130 series                                    | 2        | 1.74%   |
| Canon TS5100 series                                       | 2        | 1.74%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.74%   |
| Canon LiDE 400                                            | 2        | 1.74%   |
| Canon LiDE 300                                            | 2        | 1.74%   |
| Brother HL-L2300D series                                  | 2        | 1.74%   |
| Brother HL-1110 series                                    | 2        | 1.74%   |
| Xerox WorkCentre 3119 Series                              | 1        | 0.87%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.87%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.87%   |
| Seiko Epson Printer                                       | 1        | 0.87%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.87%   |
| Seiko Epson L395 Series                                   | 1        | 0.87%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.87%   |
| Samsung SCX-4623 Series                                   | 1        | 0.87%   |
| Samsung ML-1630 Series                                    | 1        | 0.87%   |
| Samsung M2070 Series                                      | 1        | 0.87%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.87%   |
| Prolific PL2305 Parallel Port                             | 1        | 0.87%   |
| Lexmark International InkJet Color Printer                | 1        | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 14       | 70%     |
| Hewlett-Packard | 4        | 20%     |
| UMAX            | 1        | 5%      |
| Mustek Systems  | 1        | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 5        | 25%     |
| HP Scanjet 300                     | 2        | 10%     |
| Canon CanoScan LIDE 25             | 2        | 10%     |
| Canon CanoScan LiDE 120            | 2        | 10%     |
| Canon CanoScan LiDE 110            | 2        | 10%     |
| UMAX Astra 4400/4450               | 1        | 5%      |
| Mustek Systems SNAPSCAN e22        | 1        | 5%      |
| HP ScanJet 3770                    | 1        | 5%      |
| HP ScanJet 2400c                   | 1        | 5%      |
| Canon CanoScan N1240U/LiDE 30      | 1        | 5%      |
| Canon CanoScan LiDE 220            | 1        | 5%      |
| Canon CanoScan LiDE 100            | 1        | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 58       | 24.27%  |
| Microdia                      | 41       | 17.15%  |
| KYE Systems (Mouse Systems)   | 22       | 9.21%   |
| Microsoft                     | 20       | 8.37%   |
| Z-Star Microelectronics       | 14       | 5.86%   |
| GEMBIRD                       | 10       | 4.18%   |
| Trust                         | 6        | 2.51%   |
| Samsung Electronics           | 6        | 2.51%   |
| Aveo Technology               | 5        | 2.09%   |
| Arkmicro Technologies         | 5        | 2.09%   |
| Pixart Imaging                | 4        | 1.67%   |
| MacroSilicon                  | 4        | 1.67%   |
| LG Electronics                | 4        | 1.67%   |
| Generalplus Technology        | 4        | 1.67%   |
| Cubeternet                    | 4        | 1.67%   |
| Sunplus Innovation Technology | 3        | 1.26%   |
| Realtek Semiconductor         | 3        | 1.26%   |
| Creative Technology           | 3        | 1.26%   |
| Chicony Electronics           | 3        | 1.26%   |
| Apple                         | 3        | 1.26%   |
| Unknown                       | 2        | 0.84%   |
| Jieli Technology              | 2        | 0.84%   |
| IMC Networks                  | 2        | 0.84%   |
| Hewlett-Packard               | 2        | 0.84%   |
| Xiongmai                      | 1        | 0.42%   |
| Teslong Camera                | 1        | 0.42%   |
| Sonix Technology              | 1        | 0.42%   |
| Silicon Motion                | 1        | 0.42%   |
| OmniVision Technologies       | 1        | 0.42%   |
| Huawei Technologies           | 1        | 0.42%   |
| AVerMedia Technologies        | 1        | 0.42%   |
| ANYKA                         | 1        | 0.42%   |
| Alcor Micro                   | 1        | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 22       | 9.17%   |
| Microdia Camera                                       | 20       | 8.33%   |
| Microsoft LifeCam HD-3000                             | 8        | 3.33%   |
| Microdia Sonix USB 2.0 Camera                         | 8        | 3.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 8        | 3.33%   |
| Logitech Webcam C600                                  | 7        | 2.92%   |
| Z-Star Venus USB2.0 Camera                            | 6        | 2.5%    |
| Samsung Galaxy series, misc. (MTP mode)               | 6        | 2.5%    |
| Microdia USB 2.0 Camera                               | 6        | 2.5%    |
| Logitech Webcam C170                                  | 6        | 2.5%    |
| Z-Star Vimicro USB Camera (Altair)                    | 5        | 2.08%   |
| Logitech HD Webcam C525                               | 5        | 2.08%   |
| KYE Systems (Mouse Systems) iSlim 321R                | 5        | 2.08%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 5        | 2.08%   |
| Arkmicro USB2.0 PC CAMERA                             | 5        | 2.08%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 4        | 1.67%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 4        | 1.67%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 3        | 1.25%   |
| Microsoft LifeCam VX-2000                             | 3        | 1.25%   |
| Microsoft LifeCam Studio                              | 3        | 1.25%   |
| Cubeternet USB2.0 Camera                              | 3        | 1.25%   |
| Aveo USB2.0 Camera                                    | 3        | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 3        | 1.25%   |
| Z-Star Saturn USB 2.0 Camera                          | 2        | 0.83%   |
| Unknown HD camera                                     | 2        | 0.83%   |
| Trust Full HD Webcam                                  | 2        | 0.83%   |
| Trust 17676 Webcam                                    | 2        | 0.83%   |
| Sunplus Full HD webcam                                | 2        | 0.83%   |
| Microsoft LifeCam VX-800                              | 2        | 0.83%   |
| Microsoft LifeCam VX-700                              | 2        | 0.83%   |
| Microdia Webcam Vitade AF                             | 2        | 0.83%   |
| Microdia Integrated Camera                            | 2        | 0.83%   |
| Microdia Defender G-Lens 2577 HD720p Camera           | 2        | 0.83%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]         | 2        | 0.83%   |
| MacroSilicon MiraBox Capture                          | 2        | 0.83%   |
| Logitech Webcam C200                                  | 2        | 0.83%   |
| Logitech QuickCam Pro 9000                            | 2        | 0.83%   |
| Logitech QuickCam Communicate Deluxe/S7500            | 2        | 0.83%   |
| Logitech C920 PRO HD Webcam                           | 2        | 0.83%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Gemalto (was Gemplus)     | 4        | 44.44%  |
| Reiner SCT Kartensysteme  | 2        | 22.22%  |
| OmniKey                   | 1        | 11.11%  |
| Aladdin Knowledge Systems | 1        | 11.11%  |
| Advanced Card Systems     | 1        | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 33.33%  |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 22.22%  |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 11.11%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 11.11%  |
| Aladdin Knowledge Systems Token JC                                         | 1        | 11.11%  |
| Advanced Card Systems ACR1252 Dual Reader                                  | 1        | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1597     | 87.03%  |
| 1     | 216      | 11.77%  |
| 2     | 18       | 0.98%   |
| 3     | 2        | 0.11%   |
| 5     | 1        | 0.05%   |
| 4     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 153      | 60.24%  |
| Net/wireless             | 30       | 11.81%  |
| Communication controller | 16       | 6.3%    |
| Unassigned class         | 13       | 5.12%   |
| Multimedia controller    | 9        | 3.54%   |
| Storage/raid             | 5        | 1.97%   |
| Chipcard                 | 5        | 1.97%   |
| Camera                   | 5        | 1.97%   |
| Sound                    | 3        | 1.18%   |
| Net/ethernet             | 3        | 1.18%   |
| Storage/ide              | 2        | 0.79%   |
| Fingerprint reader       | 2        | 0.79%   |
| Card reader              | 2        | 0.79%   |
| Bluetooth                | 2        | 0.79%   |
| Storage/ata              | 1        | 0.39%   |
| Storage                  | 1        | 0.39%   |
| Network                  | 1        | 0.39%   |
| Dvb card                 | 1        | 0.39%   |

