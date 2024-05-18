BlackPanther - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BlackPanther.

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

Total: 4023

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
| Gigabyte      | H110M-S2V-CF                | [22eb41201e](https://linux-hardware.org/?probe=22eb41201e) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [e8e1e2e2f8](https://linux-hardware.org/?probe=e8e1e2e2f8) | May 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [07a4ffe918](https://linux-hardware.org/?probe=07a4ffe918) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | [f696d03152](https://linux-hardware.org/?probe=f696d03152) | May 07, 2024 |
| Gigabyte      | A520M S2H                   | [c14a7e4724](https://linux-hardware.org/?probe=c14a7e4724) | May 07, 2024 |
| ASUSTek       | A88XM-E                     | [bba7d20511](https://linux-hardware.org/?probe=bba7d20511) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [c23f1deec5](https://linux-hardware.org/?probe=c23f1deec5) | May 06, 2024 |
| Gigabyte      | Z390 UD                     | [af2a20709c](https://linux-hardware.org/?probe=af2a20709c) | May 05, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [b1077f633d](https://linux-hardware.org/?probe=b1077f633d) | May 04, 2024 |
| HP            | 8062                        | [87c4c1fbfb](https://linux-hardware.org/?probe=87c4c1fbfb) | May 02, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [ff55d733a4](https://linux-hardware.org/?probe=ff55d733a4) | May 01, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [fbb11f7603](https://linux-hardware.org/?probe=fbb11f7603) | May 01, 2024 |
| HP            | 0B4Ch D                     | [db2b347526](https://linux-hardware.org/?probe=db2b347526) | Apr 30, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [120693fd0b](https://linux-hardware.org/?probe=120693fd0b) | Apr 29, 2024 |
| HP            | 0B4Ch D                     | [a4057cd447](https://linux-hardware.org/?probe=a4057cd447) | Apr 28, 2024 |
| ASRock        | Z390 Pro4                   | [b50024c729](https://linux-hardware.org/?probe=b50024c729) | Apr 28, 2024 |
| Gigabyte      | B450M GAMING                | [f81c1dea8d](https://linux-hardware.org/?probe=f81c1dea8d) | Apr 27, 2024 |
| Gigabyte      | B450M GAMING                | [0edf4e838c](https://linux-hardware.org/?probe=0edf4e838c) | Apr 27, 2024 |
| Dell          | 0D883F A06                  | [a82d507833](https://linux-hardware.org/?probe=a82d507833) | Apr 27, 2024 |
| Dell          | 0W0CHX A00                  | [9da5e84704](https://linux-hardware.org/?probe=9da5e84704) | Apr 27, 2024 |
| Dell          | 0W0CHX A00                  | [dd4600928f](https://linux-hardware.org/?probe=dd4600928f) | Apr 27, 2024 |
| Dell          | 0200DY A03                  | [96991fe0ba](https://linux-hardware.org/?probe=96991fe0ba) | Apr 27, 2024 |
| ASUSTek       | A88XM-E                     | [96107974e8](https://linux-hardware.org/?probe=96107974e8) | Apr 25, 2024 |
| Lenovo        | 1036 NO DPK                 | [e69292ead4](https://linux-hardware.org/?probe=e69292ead4) | Apr 25, 2024 |
| ASRock        | B550M Pro4                  | [60952c8e62](https://linux-hardware.org/?probe=60952c8e62) | Apr 24, 2024 |
| Gigabyte      | H310M A-CF x.x              | [250df2037f](https://linux-hardware.org/?probe=250df2037f) | Apr 24, 2024 |
| Dell          | 0200DY A03                  | [a838cb0e0d](https://linux-hardware.org/?probe=a838cb0e0d) | Apr 23, 2024 |
| HP            | 1494                        | [82c9d00df1](https://linux-hardware.org/?probe=82c9d00df1) | Apr 22, 2024 |
| Dell          | 0HY9JP A02                  | [08e7641b37](https://linux-hardware.org/?probe=08e7641b37) | Apr 22, 2024 |
| Lenovo        | 1036 NO DPK                 | [1462b6d76a](https://linux-hardware.org/?probe=1462b6d76a) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [91735d80f4](https://linux-hardware.org/?probe=91735d80f4) | Apr 22, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [ff2ff25197](https://linux-hardware.org/?probe=ff2ff25197) | Apr 22, 2024 |
| Gigabyte      | Z390 UD                     | [60d76632dc](https://linux-hardware.org/?probe=60d76632dc) | Apr 21, 2024 |
| Dell          | 0TY565                      | [f5c8cf7e9b](https://linux-hardware.org/?probe=f5c8cf7e9b) | Apr 21, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [8b93f4607f](https://linux-hardware.org/?probe=8b93f4607f) | Apr 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [b10f7daaa1](https://linux-hardware.org/?probe=b10f7daaa1) | Apr 20, 2024 |
| MSI           | X58 Pro-E                   | [4411cb9e36](https://linux-hardware.org/?probe=4411cb9e36) | Apr 18, 2024 |
| Dell          | 0HD5W2 A01                  | [1c7957de19](https://linux-hardware.org/?probe=1c7957de19) | Apr 16, 2024 |
| ASRock        | X370 Gaming X               | [db397e4511](https://linux-hardware.org/?probe=db397e4511) | Apr 15, 2024 |
| Dell          | 0VHWTR A02                  | [4e32c7cfca](https://linux-hardware.org/?probe=4e32c7cfca) | Apr 15, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [88ad8806c3](https://linux-hardware.org/?probe=88ad8806c3) | Apr 13, 2024 |
| HP            | 8265                        | [c4d4cdac41](https://linux-hardware.org/?probe=c4d4cdac41) | Apr 13, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5bc49637b9](https://linux-hardware.org/?probe=5bc49637b9) | Apr 12, 2024 |
| Gigabyte      | H61M-S1                     | [1a9697f39d](https://linux-hardware.org/?probe=1a9697f39d) | Apr 12, 2024 |
| ASUSTek       | P8Z77-V LX                  | [c108665460](https://linux-hardware.org/?probe=c108665460) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5fb89da542](https://linux-hardware.org/?probe=5fb89da542) | Apr 11, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [74dd149115](https://linux-hardware.org/?probe=74dd149115) | Apr 11, 2024 |
| HP            | 8062                        | [358bbe16f0](https://linux-hardware.org/?probe=358bbe16f0) | Apr 11, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [dd15f5797f](https://linux-hardware.org/?probe=dd15f5797f) | Apr 09, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [2d897e4ab7](https://linux-hardware.org/?probe=2d897e4ab7) | Apr 09, 2024 |
| ASUSTek       | PRIME A320M-R               | [eb77201fa8](https://linux-hardware.org/?probe=eb77201fa8) | Apr 09, 2024 |
| Gigabyte      | B75M-D3H                    | [fa4c48c242](https://linux-hardware.org/?probe=fa4c48c242) | Apr 09, 2024 |
| ASUSTek       | ROG Maximus X CODE          | [446576913d](https://linux-hardware.org/?probe=446576913d) | Apr 08, 2024 |
| ASUSTek       | M4A785TD-V EVO              | [2dbe37af95](https://linux-hardware.org/?probe=2dbe37af95) | Apr 07, 2024 |
| HP            | 8265                        | [601051ee6c](https://linux-hardware.org/?probe=601051ee6c) | Apr 07, 2024 |
| Gigabyte      | H61M-S1                     | [7fe942c453](https://linux-hardware.org/?probe=7fe942c453) | Apr 07, 2024 |
| Dell          | 0D883F A06                  | [74170027e8](https://linux-hardware.org/?probe=74170027e8) | Apr 07, 2024 |
| ASUSTek       | PRIME B365M-A               | [50b8d3eaf1](https://linux-hardware.org/?probe=50b8d3eaf1) | Apr 07, 2024 |
| Gigabyte      | Z390 UD                     | [3378d48eb3](https://linux-hardware.org/?probe=3378d48eb3) | Apr 07, 2024 |
| HP            | 8265                        | [b08747219b](https://linux-hardware.org/?probe=b08747219b) | Apr 06, 2024 |
| ASRock        | Z370 Extreme4               | [6354d3d2a2](https://linux-hardware.org/?probe=6354d3d2a2) | Apr 05, 2024 |
| ASRock        | Z370 Extreme4               | [f6925b3c88](https://linux-hardware.org/?probe=f6925b3c88) | Apr 05, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [102e8ee904](https://linux-hardware.org/?probe=102e8ee904) | Apr 05, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [95a657f223](https://linux-hardware.org/?probe=95a657f223) | Apr 03, 2024 |
| ASRock        | 4CoreDual-SATA2             | [469a404c91](https://linux-hardware.org/?probe=469a404c91) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [3c0b19e9f2](https://linux-hardware.org/?probe=3c0b19e9f2) | Apr 03, 2024 |
| Dell          | 0YP693 A02                  | [48ec750bd0](https://linux-hardware.org/?probe=48ec750bd0) | Apr 03, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [6d4eaf0bc7](https://linux-hardware.org/?probe=6d4eaf0bc7) | Apr 01, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4d733040a](https://linux-hardware.org/?probe=b4d733040a) | Mar 31, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [b4555fa57d](https://linux-hardware.org/?probe=b4555fa57d) | Mar 31, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [bc68546a92](https://linux-hardware.org/?probe=bc68546a92) | Mar 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [c0736cef30](https://linux-hardware.org/?probe=c0736cef30) | Mar 29, 2024 |
| ASUSTek       | H110M-A                     | [d7699c7455](https://linux-hardware.org/?probe=d7699c7455) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [30817e9020](https://linux-hardware.org/?probe=30817e9020) | Mar 29, 2024 |
| ASRock        | 4CoreDual-SATA2             | [cbccd74400](https://linux-hardware.org/?probe=cbccd74400) | Mar 29, 2024 |
| Lenovo        | 1036 NO DPK                 | [ba8b769eb3](https://linux-hardware.org/?probe=ba8b769eb3) | Mar 29, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [368a738712](https://linux-hardware.org/?probe=368a738712) | Mar 28, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [84c4c90a3f](https://linux-hardware.org/?probe=84c4c90a3f) | Mar 27, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [6c186bed7b](https://linux-hardware.org/?probe=6c186bed7b) | Mar 26, 2024 |
| HP            | 1495                        | [806af03d1c](https://linux-hardware.org/?probe=806af03d1c) | Mar 26, 2024 |
| ASRock        | B550M Pro4                  | [e9c2053699](https://linux-hardware.org/?probe=e9c2053699) | Mar 25, 2024 |
| ASRock        | N68C-GS FX                  | [793650d556](https://linux-hardware.org/?probe=793650d556) | Mar 25, 2024 |
| HP            | 339A                        | [a07dca6a8c](https://linux-hardware.org/?probe=a07dca6a8c) | Mar 25, 2024 |
| Dell          | 0K240Y A01                  | [eff3389fdb](https://linux-hardware.org/?probe=eff3389fdb) | Mar 25, 2024 |
| HP            | 1495                        | [50e1e9d3da](https://linux-hardware.org/?probe=50e1e9d3da) | Mar 25, 2024 |
| MSI           | P43i                        | [d56d55fd40](https://linux-hardware.org/?probe=d56d55fd40) | Mar 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [fa1a2097f6](https://linux-hardware.org/?probe=fa1a2097f6) | Mar 24, 2024 |
| Gigabyte      | P67A-D3-B3                  | [1f06fd5eea](https://linux-hardware.org/?probe=1f06fd5eea) | Mar 24, 2024 |
| Dell          | 0RN474                      | [665f831546](https://linux-hardware.org/?probe=665f831546) | Mar 24, 2024 |
| ASRock        | B85M                        | [4c906767aa](https://linux-hardware.org/?probe=4c906767aa) | Mar 24, 2024 |
| ASUSTek       | Maximus VI HERO             | [4fac588ebc](https://linux-hardware.org/?probe=4fac588ebc) | Mar 23, 2024 |
| ASUSTek       | Maximus VI HERO             | [2016d6fb0a](https://linux-hardware.org/?probe=2016d6fb0a) | Mar 23, 2024 |
| Dell          | 0M858N A01                  | [fa3478bb8f](https://linux-hardware.org/?probe=fa3478bb8f) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1f9a0b4802](https://linux-hardware.org/?probe=1f9a0b4802) | Mar 23, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1a34385882](https://linux-hardware.org/?probe=1a34385882) | Mar 23, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [1ee4446988](https://linux-hardware.org/?probe=1ee4446988) | Mar 23, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3d39374ca9](https://linux-hardware.org/?probe=3d39374ca9) | Mar 23, 2024 |
| Gigabyte      | Z390 UD                     | [9052435efd](https://linux-hardware.org/?probe=9052435efd) | Mar 23, 2024 |
| Gigabyte      | H310M A-CF x.x              | [ef274edd0e](https://linux-hardware.org/?probe=ef274edd0e) | Mar 23, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [1368766d06](https://linux-hardware.org/?probe=1368766d06) | Mar 23, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cf4153f8c](https://linux-hardware.org/?probe=5cf4153f8c) | Mar 23, 2024 |
| Gigabyte      | A520M S2H                   | [11901df61a](https://linux-hardware.org/?probe=11901df61a) | Mar 23, 2024 |
| Gigabyte      | H97-D3H-CF                  | [76ee872777](https://linux-hardware.org/?probe=76ee872777) | Mar 22, 2024 |
| ASUSTek       | H110M-A                     | [2d969a527b](https://linux-hardware.org/?probe=2d969a527b) | Mar 22, 2024 |
| Gigabyte      | B250-HD3P-CF                | [a562caa39d](https://linux-hardware.org/?probe=a562caa39d) | Mar 22, 2024 |
| Gigabyte      | P61-USB3-B3                 | [bd7ae42260](https://linux-hardware.org/?probe=bd7ae42260) | Mar 22, 2024 |
| Dell          | 0200DY A03                  | [0838a0e911](https://linux-hardware.org/?probe=0838a0e911) | Mar 21, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [4276c6c62c](https://linux-hardware.org/?probe=4276c6c62c) | Mar 21, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c8b0e932f7](https://linux-hardware.org/?probe=c8b0e932f7) | Mar 21, 2024 |
| MSI           | A320M-A PRO MAX             | [faff855b6c](https://linux-hardware.org/?probe=faff855b6c) | Mar 21, 2024 |
| Gigabyte      | H110M-S2V-CF                | [be31fe508d](https://linux-hardware.org/?probe=be31fe508d) | Mar 21, 2024 |
| MSI           | MS-7369                     | [0a36f4715f](https://linux-hardware.org/?probe=0a36f4715f) | Mar 21, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9d36d6bf2a](https://linux-hardware.org/?probe=9d36d6bf2a) | Mar 21, 2024 |
| MSI           | H61M-P21                    | [feba614c1c](https://linux-hardware.org/?probe=feba614c1c) | Mar 21, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [5de3598ad6](https://linux-hardware.org/?probe=5de3598ad6) | Mar 21, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [a58bb79ea5](https://linux-hardware.org/?probe=a58bb79ea5) | Mar 20, 2024 |
| Fujitsu       | D3003-C1 S26361-D3003-C1    | [98cfbdc7b2](https://linux-hardware.org/?probe=98cfbdc7b2) | Mar 20, 2024 |
| ASUSTek       | PRIME A320M-R               | [50369a26af](https://linux-hardware.org/?probe=50369a26af) | Mar 19, 2024 |
| ASUSTek       | PRIME A520M-E               | [fe6517ecf5](https://linux-hardware.org/?probe=fe6517ecf5) | Mar 18, 2024 |
| ASUSTek       | PRIME A520M-E               | [151ae9cdaf](https://linux-hardware.org/?probe=151ae9cdaf) | Mar 18, 2024 |
| ASUSTek       | G15DK                       | [1265b31544](https://linux-hardware.org/?probe=1265b31544) | Mar 18, 2024 |
| Gigabyte      | P35-DS3R                    | [0e8135e5be](https://linux-hardware.org/?probe=0e8135e5be) | Mar 17, 2024 |
| Gigabyte      | P35-DS3R                    | [37d7839fa0](https://linux-hardware.org/?probe=37d7839fa0) | Mar 17, 2024 |
| Gigabyte      | Z170-Gaming K3-CF           | [e6b3e23ce6](https://linux-hardware.org/?probe=e6b3e23ce6) | Mar 16, 2024 |
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
| Gigabyte      | B250M-Gaming 3-CF           | [dfa4480394](https://linux-hardware.org/?probe=dfa4480394) | Mar 10, 2024 |
| ASUSTek       | PRIME B250M-PLUS            | [7f8abbb276](https://linux-hardware.org/?probe=7f8abbb276) | Mar 09, 2024 |
| Gigabyte      | H110M-S2V-CF                | [9eecf787b4](https://linux-hardware.org/?probe=9eecf787b4) | Mar 09, 2024 |
| Dell          | 0VHWTR A02                  | [414f810f95](https://linux-hardware.org/?probe=414f810f95) | Mar 08, 2024 |
| ASUSTek       | PRIME A320M-K               | [bf70b84d81](https://linux-hardware.org/?probe=bf70b84d81) | Mar 08, 2024 |
| HP            | 805D                        | [853e435928](https://linux-hardware.org/?probe=853e435928) | Mar 08, 2024 |
| Lenovo        | SHARKBAY NOK                | [4076eb2209](https://linux-hardware.org/?probe=4076eb2209) | Mar 07, 2024 |
| ASUSTek       | PRIME A320M-K               | [90d69200ef](https://linux-hardware.org/?probe=90d69200ef) | Mar 07, 2024 |
| Medion        | MS-7748                     | [77a10d77ea](https://linux-hardware.org/?probe=77a10d77ea) | Mar 07, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [c9d0284a9b](https://linux-hardware.org/?probe=c9d0284a9b) | Mar 06, 2024 |
| ASUSTek       | H110M-A                     | [695e54f273](https://linux-hardware.org/?probe=695e54f273) | Mar 05, 2024 |
| Gigabyte      | B450 GAMING X               | [ab4aeaa345](https://linux-hardware.org/?probe=ab4aeaa345) | Mar 03, 2024 |
| ASRock        | G41M-VS3                    | [03a42b8972](https://linux-hardware.org/?probe=03a42b8972) | Mar 03, 2024 |
| HP            | 3047h                       | [fb25a061b8](https://linux-hardware.org/?probe=fb25a061b8) | Mar 03, 2024 |
| HP            | 3047h                       | [171fc32e0a](https://linux-hardware.org/?probe=171fc32e0a) | Mar 03, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7f0877ee14](https://linux-hardware.org/?probe=7f0877ee14) | Mar 03, 2024 |
| Dell          | 0200DY A03                  | [b06d040c63](https://linux-hardware.org/?probe=b06d040c63) | Mar 03, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [c9c10a188e](https://linux-hardware.org/?probe=c9c10a188e) | Mar 02, 2024 |
| Gigabyte      | B450M GAMING                | [5ffab2a305](https://linux-hardware.org/?probe=5ffab2a305) | Mar 02, 2024 |
| Gigabyte      | Z390 UD                     | [9cbfa725df](https://linux-hardware.org/?probe=9cbfa725df) | Feb 28, 2024 |
| ASRock        | B550M Pro4                  | [795e44e4cf](https://linux-hardware.org/?probe=795e44e4cf) | Feb 28, 2024 |
| HP            | 1497                        | [8fc0f49c19](https://linux-hardware.org/?probe=8fc0f49c19) | Feb 26, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [7019e3f6f8](https://linux-hardware.org/?probe=7019e3f6f8) | Feb 25, 2024 |
| Gigabyte      | H310M A-CF x.x              | [af6ad45d24](https://linux-hardware.org/?probe=af6ad45d24) | Feb 25, 2024 |
| Lenovo        | 1730-A1G                    | [a6ca9cff31](https://linux-hardware.org/?probe=a6ca9cff31) | Feb 25, 2024 |
| HP            | 304Ah                       | [0c2c06e76f](https://linux-hardware.org/?probe=0c2c06e76f) | Feb 25, 2024 |
| HP            | 304Ah                       | [98ce8f9cf7](https://linux-hardware.org/?probe=98ce8f9cf7) | Feb 25, 2024 |
| Dell          | 0RN474                      | [c2ca6576b9](https://linux-hardware.org/?probe=c2ca6576b9) | Feb 25, 2024 |
| MSI           | MS-7369                     | [d771ce7ed3](https://linux-hardware.org/?probe=d771ce7ed3) | Feb 25, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [bf94f23691](https://linux-hardware.org/?probe=bf94f23691) | Feb 24, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6a9db010d9](https://linux-hardware.org/?probe=6a9db010d9) | Feb 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [2ae75f745e](https://linux-hardware.org/?probe=2ae75f745e) | Feb 23, 2024 |
| Dell          | 0D883F A06                  | [2f2b1cd47c](https://linux-hardware.org/?probe=2f2b1cd47c) | Feb 21, 2024 |
| HP            | 8265                        | [530f502c52](https://linux-hardware.org/?probe=530f502c52) | Feb 20, 2024 |
| Gigabyte      | G31M-S2C                    | [678ad5ec54](https://linux-hardware.org/?probe=678ad5ec54) | Feb 20, 2024 |
| ASRock        | FM2A75M Pro4+               | [cbc49630c4](https://linux-hardware.org/?probe=cbc49630c4) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [3279f823cb](https://linux-hardware.org/?probe=3279f823cb) | Feb 19, 2024 |
| Lenovo        | ThinkStation D20 4158AF8    | [c301bbef33](https://linux-hardware.org/?probe=c301bbef33) | Feb 19, 2024 |
| Gigabyte      | H310M A-CF x.x              | [5df2e64ba9](https://linux-hardware.org/?probe=5df2e64ba9) | Feb 18, 2024 |
| Gigabyte      | EP31-DS3L                   | [a2f2f76c2e](https://linux-hardware.org/?probe=a2f2f76c2e) | Feb 18, 2024 |
| Dell          | 0Y2MRG A00                  | [ddea40bc9b](https://linux-hardware.org/?probe=ddea40bc9b) | Feb 18, 2024 |
| Dell          | 0Y2MRG A00                  | [d23358d851](https://linux-hardware.org/?probe=d23358d851) | Feb 18, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [ad35cbf450](https://linux-hardware.org/?probe=ad35cbf450) | Feb 17, 2024 |
| HP            | 3047h                       | [45ba601c69](https://linux-hardware.org/?probe=45ba601c69) | Feb 16, 2024 |
| ASRock        | B85M                        | [c9300aa54b](https://linux-hardware.org/?probe=c9300aa54b) | Feb 16, 2024 |
| Gigabyte      | A520M S2H                   | [ff0aa6019c](https://linux-hardware.org/?probe=ff0aa6019c) | Feb 16, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [0139a8dd1b](https://linux-hardware.org/?probe=0139a8dd1b) | Feb 15, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [b116cf57b4](https://linux-hardware.org/?probe=b116cf57b4) | Feb 15, 2024 |
| Lenovo        | 1036 NO DPK                 | [125c31fd2c](https://linux-hardware.org/?probe=125c31fd2c) | Feb 15, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [e962ebfe4d](https://linux-hardware.org/?probe=e962ebfe4d) | Feb 14, 2024 |
| HP            | 8265                        | [e4997d7fc2](https://linux-hardware.org/?probe=e4997d7fc2) | Feb 14, 2024 |
| HP            | 339A                        | [69c4f45b66](https://linux-hardware.org/?probe=69c4f45b66) | Feb 14, 2024 |
| Gigabyte      | H97-D3H-CF                  | [a5117dd4fd](https://linux-hardware.org/?probe=a5117dd4fd) | Feb 13, 2024 |
| ASUSTek       | PRIME B365M-A               | [2955560f16](https://linux-hardware.org/?probe=2955560f16) | Feb 13, 2024 |
| ASRock        | N68C-GS FX                  | [81bc175b9c](https://linux-hardware.org/?probe=81bc175b9c) | Feb 13, 2024 |
| ASRock        | B550M Pro4                  | [39aa1a05dd](https://linux-hardware.org/?probe=39aa1a05dd) | Feb 13, 2024 |
| Dell          | 0200DY A03                  | [6075938249](https://linux-hardware.org/?probe=6075938249) | Feb 12, 2024 |
| Gigabyte      | H61M-S1                     | [5ba6bba9d7](https://linux-hardware.org/?probe=5ba6bba9d7) | Feb 11, 2024 |
| Gigabyte      | H61M-S2PV                   | [1f1cba872e](https://linux-hardware.org/?probe=1f1cba872e) | Feb 11, 2024 |
| Gigabyte      | P67A-D3-B3                  | [a1b482c4e5](https://linux-hardware.org/?probe=a1b482c4e5) | Feb 11, 2024 |
| ASUSTek       | P8Z77-V LX                  | [1db2b9826c](https://linux-hardware.org/?probe=1db2b9826c) | Feb 11, 2024 |
| Gigabyte      | H61M-S2PV                   | [214f3483d2](https://linux-hardware.org/?probe=214f3483d2) | Feb 11, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [1c432f8df1](https://linux-hardware.org/?probe=1c432f8df1) | Feb 11, 2024 |
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
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [edb250e20a](https://linux-hardware.org/?probe=edb250e20a) | Feb 10, 2024 |
| ASUSTek       | H110M-K                     | [5002d94a38](https://linux-hardware.org/?probe=5002d94a38) | Feb 09, 2024 |
| ASRock        | 775i945GZ                   | [38891b0920](https://linux-hardware.org/?probe=38891b0920) | Feb 09, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [e9f7f560fe](https://linux-hardware.org/?probe=e9f7f560fe) | Feb 09, 2024 |
| HP            | 1495                        | [6fff4b1751](https://linux-hardware.org/?probe=6fff4b1751) | Feb 09, 2024 |
| Dell          | 0M858N A01                  | [e57e9094b4](https://linux-hardware.org/?probe=e57e9094b4) | Feb 08, 2024 |
| MSI           | P43i                        | [b4c30541fa](https://linux-hardware.org/?probe=b4c30541fa) | Feb 08, 2024 |
| ASUSTek       | H110M-A                     | [4515105b8d](https://linux-hardware.org/?probe=4515105b8d) | Feb 08, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [742d19f797](https://linux-hardware.org/?probe=742d19f797) | Feb 08, 2024 |
| Gigabyte      | H110M-S2V-CF                | [84a355a004](https://linux-hardware.org/?probe=84a355a004) | Feb 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [90a5d44bde](https://linux-hardware.org/?probe=90a5d44bde) | Feb 08, 2024 |
| MSI           | A320M-A PRO MAX             | [986691347b](https://linux-hardware.org/?probe=986691347b) | Feb 07, 2024 |
| Dell          | 0VHWTR A02                  | [d37b4c9999](https://linux-hardware.org/?probe=d37b4c9999) | Feb 07, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [d1be9e4f66](https://linux-hardware.org/?probe=d1be9e4f66) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [9f50a00ce2](https://linux-hardware.org/?probe=9f50a00ce2) | Feb 07, 2024 |
| Lenovo        | 1730-A1G                    | [52d70892db](https://linux-hardware.org/?probe=52d70892db) | Feb 07, 2024 |
| HP            | 1495                        | [72869998f4](https://linux-hardware.org/?probe=72869998f4) | Feb 07, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [0c0a1d2651](https://linux-hardware.org/?probe=0c0a1d2651) | Feb 06, 2024 |
| HP            | 0B4Ch D                     | [9258e387e7](https://linux-hardware.org/?probe=9258e387e7) | Feb 06, 2024 |
| Gigabyte      | H61M-S1                     | [89b53566aa](https://linux-hardware.org/?probe=89b53566aa) | Feb 06, 2024 |
| Lenovo        | 1036 NO DPK                 | [90b0945a98](https://linux-hardware.org/?probe=90b0945a98) | Feb 06, 2024 |
| Dell          | 0M858N A01                  | [efe0f9fc26](https://linux-hardware.org/?probe=efe0f9fc26) | Feb 05, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5013c4bba6](https://linux-hardware.org/?probe=5013c4bba6) | Feb 05, 2024 |
| Gigabyte      | H310M A-CF x.x              | [e9ae02c21e](https://linux-hardware.org/?probe=e9ae02c21e) | Feb 05, 2024 |
| Gigabyte      | A520M S2H                   | [a5467dc900](https://linux-hardware.org/?probe=a5467dc900) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [79200de704](https://linux-hardware.org/?probe=79200de704) | Feb 04, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ca1fce3f2f](https://linux-hardware.org/?probe=ca1fce3f2f) | Feb 04, 2024 |
| Dell          | 0D883F A06                  | [553aeec0a5](https://linux-hardware.org/?probe=553aeec0a5) | Feb 04, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [a0c3cd5ffd](https://linux-hardware.org/?probe=a0c3cd5ffd) | Feb 04, 2024 |
| ASUSTek       | PRIME A320M-R               | [533592b8f0](https://linux-hardware.org/?probe=533592b8f0) | Feb 04, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [e70b13c7d6](https://linux-hardware.org/?probe=e70b13c7d6) | Feb 04, 2024 |
| ASUSTek       | H110M-A                     | [684ac8da19](https://linux-hardware.org/?probe=684ac8da19) | Feb 04, 2024 |
| Dell          | 0200DY A03                  | [07d45f5532](https://linux-hardware.org/?probe=07d45f5532) | Feb 03, 2024 |
| Gigabyte      | H97-D3H-CF                  | [9c4309b1ea](https://linux-hardware.org/?probe=9c4309b1ea) | Feb 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6068e871ed](https://linux-hardware.org/?probe=6068e871ed) | Feb 03, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5eb37a9fb2](https://linux-hardware.org/?probe=5eb37a9fb2) | Feb 03, 2024 |
| HP            | 1497                        | [ae90a32790](https://linux-hardware.org/?probe=ae90a32790) | Feb 02, 2024 |
| Gigabyte      | G31M-S2C                    | [b0e201e74a](https://linux-hardware.org/?probe=b0e201e74a) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [4009a96bd4](https://linux-hardware.org/?probe=4009a96bd4) | Feb 02, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [ab60a0a3b4](https://linux-hardware.org/?probe=ab60a0a3b4) | Feb 02, 2024 |
| ASRock        | B550M Pro4                  | [ce95a21f31](https://linux-hardware.org/?probe=ce95a21f31) | Feb 01, 2024 |
| ASRock        | X370 Gaming X               | [54fa92de97](https://linux-hardware.org/?probe=54fa92de97) | Feb 01, 2024 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [1cee0ab81d](https://linux-hardware.org/?probe=1cee0ab81d) | Feb 01, 2024 |
| ASUSTek       | H110M-A                     | [ef9ec58561](https://linux-hardware.org/?probe=ef9ec58561) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [c85924bf6f](https://linux-hardware.org/?probe=c85924bf6f) | Jan 31, 2024 |
| Gigabyte      | F2A88XN-WIFI                | [aad32e443a](https://linux-hardware.org/?probe=aad32e443a) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-R               | [4995dfcd57](https://linux-hardware.org/?probe=4995dfcd57) | Jan 31, 2024 |
| MSI           | MS-7817                     | [e67644d160](https://linux-hardware.org/?probe=e67644d160) | Jan 31, 2024 |
| ASRock        | B550M Pro4                  | [562a7e84b6](https://linux-hardware.org/?probe=562a7e84b6) | Jan 31, 2024 |
| Gigabyte      | B365M DS3H                  | [bb6bab84d0](https://linux-hardware.org/?probe=bb6bab84d0) | Jan 31, 2024 |
| Gigabyte      | B365M DS3H                  | [8a8a84c18b](https://linux-hardware.org/?probe=8a8a84c18b) | Jan 31, 2024 |
| Dell          | 0TY565                      | [7b0be6d329](https://linux-hardware.org/?probe=7b0be6d329) | Jan 31, 2024 |
| Dell          | 0TY565                      | [a1dd2e6d5d](https://linux-hardware.org/?probe=a1dd2e6d5d) | Jan 31, 2024 |
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
| Gigabyte      | H61M-S1                     | [9a7978bd86](https://linux-hardware.org/?probe=9a7978bd86) | Jan 29, 2024 |
| Dell          | 0200DY A03                  | [26d8100c96](https://linux-hardware.org/?probe=26d8100c96) | Jan 28, 2024 |
| Lenovo        | 1036 NO DPK                 | [aa54fcaee1](https://linux-hardware.org/?probe=aa54fcaee1) | Jan 28, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [32a41e8aff](https://linux-hardware.org/?probe=32a41e8aff) | Jan 28, 2024 |
| Gigabyte      | H61M-S2PV                   | [b313d408fc](https://linux-hardware.org/?probe=b313d408fc) | Jan 27, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [f17f689f78](https://linux-hardware.org/?probe=f17f689f78) | Jan 27, 2024 |
| MSI           | MS-7817                     | [53d14e5734](https://linux-hardware.org/?probe=53d14e5734) | Jan 26, 2024 |
| ASUSTek       | P5LD2-X/1333                | [6175179da0](https://linux-hardware.org/?probe=6175179da0) | Jan 26, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [c0926b6944](https://linux-hardware.org/?probe=c0926b6944) | Jan 26, 2024 |
| ASUSTek       | P5KPL-AM SE                 | [fd8742e98a](https://linux-hardware.org/?probe=fd8742e98a) | Jan 26, 2024 |
| Gigabyte      | H61M-S2PV                   | [ec7c2fd28c](https://linux-hardware.org/?probe=ec7c2fd28c) | Jan 26, 2024 |
| HP            | 1497                        | [70ed07412a](https://linux-hardware.org/?probe=70ed07412a) | Jan 26, 2024 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [f1397d3500](https://linux-hardware.org/?probe=f1397d3500) | Jan 26, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [919e1d0d1a](https://linux-hardware.org/?probe=919e1d0d1a) | Jan 25, 2024 |
| ASRock        | FM2A75M Pro4+               | [b13e328c84](https://linux-hardware.org/?probe=b13e328c84) | Jan 25, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ecec004de9](https://linux-hardware.org/?probe=ecec004de9) | Jan 25, 2024 |
| ASUSTek       | H110M-K                     | [e187cbf4f0](https://linux-hardware.org/?probe=e187cbf4f0) | Jan 24, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [9aa36d0ef2](https://linux-hardware.org/?probe=9aa36d0ef2) | Jan 24, 2024 |
| Gigabyte      | A520M S2H                   | [3c14c44a2e](https://linux-hardware.org/?probe=3c14c44a2e) | Jan 24, 2024 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [5cc29f2f4d](https://linux-hardware.org/?probe=5cc29f2f4d) | Jan 24, 2024 |
| Gigabyte      | H97-D3H-CF                  | [5b4d20246c](https://linux-hardware.org/?probe=5b4d20246c) | Jan 23, 2024 |
| Gigabyte      | B660M GAMING DDR4           | [4c6536c12f](https://linux-hardware.org/?probe=4c6536c12f) | Jan 23, 2024 |
| MSI           | P43i                        | [96ed9e6412](https://linux-hardware.org/?probe=96ed9e6412) | Jan 23, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d3cf795f5d](https://linux-hardware.org/?probe=d3cf795f5d) | Jan 22, 2024 |
| Gigabyte      | X570 AORUS XTREME           | [b63d070fe7](https://linux-hardware.org/?probe=b63d070fe7) | Jan 22, 2024 |
| Gigabyte      | H61M-S1                     | [f0a97be10f](https://linux-hardware.org/?probe=f0a97be10f) | Jan 22, 2024 |
| Dell          | 0K240Y A01                  | [ea975a38d2](https://linux-hardware.org/?probe=ea975a38d2) | Jan 22, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [448b20e8f3](https://linux-hardware.org/?probe=448b20e8f3) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f18016d0b6](https://linux-hardware.org/?probe=f18016d0b6) | Jan 22, 2024 |
| Gigabyte      | B85N PHOENIX-CF             | [f55473c84d](https://linux-hardware.org/?probe=f55473c84d) | Jan 22, 2024 |
| HP            | 0B4Ch D                     | [382a956d11](https://linux-hardware.org/?probe=382a956d11) | Jan 22, 2024 |
| Dell          | 0GY6Y8 A01                  | [70ed7265d7](https://linux-hardware.org/?probe=70ed7265d7) | Jan 22, 2024 |
| HP            | 0B4Ch D                     | [ac643dc1d4](https://linux-hardware.org/?probe=ac643dc1d4) | Jan 21, 2024 |
| ASRock        | N68C-S UCC                  | [dc2724d2ca](https://linux-hardware.org/?probe=dc2724d2ca) | Jan 20, 2024 |
| Medion        | MS-7748                     | [0da6204fe7](https://linux-hardware.org/?probe=0da6204fe7) | Jan 19, 2024 |
| ASUSTek       | PRIME A320M-R               | [314cb08407](https://linux-hardware.org/?probe=314cb08407) | Jan 18, 2024 |
| Lenovo        | 1036 NO DPK                 | [fe04dc8528](https://linux-hardware.org/?probe=fe04dc8528) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [382d54efe4](https://linux-hardware.org/?probe=382d54efe4) | Jan 18, 2024 |
| ASRock        | B550M-HDV                   | [f2ae4fae96](https://linux-hardware.org/?probe=f2ae4fae96) | Jan 18, 2024 |
| ASUSTek       | P5LD2-X/1333                | [7670d862e1](https://linux-hardware.org/?probe=7670d862e1) | Jan 17, 2024 |
| ASRock        | FM2A75M Pro4+               | [8b6cc378c3](https://linux-hardware.org/?probe=8b6cc378c3) | Jan 16, 2024 |
| Gigabyte      | H61M-S2PV                   | [3e4a544656](https://linux-hardware.org/?probe=3e4a544656) | Jan 13, 2024 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [ea74a34365](https://linux-hardware.org/?probe=ea74a34365) | Jan 13, 2024 |
| ASRock        | B550M Pro4                  | [f4660fbf02](https://linux-hardware.org/?probe=f4660fbf02) | Jan 12, 2024 |
| Gigabyte      | H310M A-CF x.x              | [4b838199f5](https://linux-hardware.org/?probe=4b838199f5) | Jan 11, 2024 |
| Gigabyte      | H310M A-CF x.x              | [cb71ddc06e](https://linux-hardware.org/?probe=cb71ddc06e) | Jan 11, 2024 |
| Medion        | MS-7748                     | [fd6786798c](https://linux-hardware.org/?probe=fd6786798c) | Jan 11, 2024 |
| ASRock        | N68C-S UCC                  | [fb39fef7a4](https://linux-hardware.org/?probe=fb39fef7a4) | Jan 09, 2024 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [177fdc1d8d](https://linux-hardware.org/?probe=177fdc1d8d) | Jan 08, 2024 |
| Dell          | 0T0MHW A02                  | [a71fc6258c](https://linux-hardware.org/?probe=a71fc6258c) | Jan 08, 2024 |
| HP            | 339A                        | [7f31e925d5](https://linux-hardware.org/?probe=7f31e925d5) | Jan 07, 2024 |
| Dell          | 0200DY A03                  | [398cb20c88](https://linux-hardware.org/?probe=398cb20c88) | Jan 07, 2024 |
| ASUSTek       | H110M-A                     | [d24e2d377c](https://linux-hardware.org/?probe=d24e2d377c) | Jan 07, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [c5f32d31a4](https://linux-hardware.org/?probe=c5f32d31a4) | Jan 06, 2024 |
| Lenovo        | ThinkStation C30 1097A34    | [db15f78582](https://linux-hardware.org/?probe=db15f78582) | Jan 06, 2024 |
| Gigabyte      | GA-MA78GPM-DS2H             | [22e4df864b](https://linux-hardware.org/?probe=22e4df864b) | Jan 06, 2024 |
| HP            | 8265                        | [227d139424](https://linux-hardware.org/?probe=227d139424) | Jan 05, 2024 |
| ASUSTek       | A88XM-E                     | [671224ec71](https://linux-hardware.org/?probe=671224ec71) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [0a4ab17035](https://linux-hardware.org/?probe=0a4ab17035) | Jan 05, 2024 |
| Lenovo        | 312A NOK                    | [a6bd11e06b](https://linux-hardware.org/?probe=a6bd11e06b) | Jan 05, 2024 |
| ASRock        | X370 Gaming X               | [b780de408a](https://linux-hardware.org/?probe=b780de408a) | Jan 05, 2024 |
| Dell          | 0M858N A01                  | [115fd937a1](https://linux-hardware.org/?probe=115fd937a1) | Jan 04, 2024 |
| ASRock        | B85M                        | [093643c0f0](https://linux-hardware.org/?probe=093643c0f0) | Jan 04, 2024 |
| ASRock        | G41M-VS3                    | [4a19917cf2](https://linux-hardware.org/?probe=4a19917cf2) | Jan 04, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | [d99098989d](https://linux-hardware.org/?probe=d99098989d) | Jan 03, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [76a2205872](https://linux-hardware.org/?probe=76a2205872) | Jan 03, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [74e244eb6c](https://linux-hardware.org/?probe=74e244eb6c) | Jan 02, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [7f438185af](https://linux-hardware.org/?probe=7f438185af) | Jan 02, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [79b5e7c7b0](https://linux-hardware.org/?probe=79b5e7c7b0) | Jan 01, 2024 |
| Gigabyte      | H61M-S1                     | [1e34cd1559](https://linux-hardware.org/?probe=1e34cd1559) | Jan 01, 2024 |
| Gigabyte      | P67A-D3-B3                  | [28494e9d46](https://linux-hardware.org/?probe=28494e9d46) | Jan 01, 2024 |
| Gigabyte      | F2A88XM-HD3                 | [23eb635b4e](https://linux-hardware.org/?probe=23eb635b4e) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [da76fd5108](https://linux-hardware.org/?probe=da76fd5108) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-R               | [d646e8d5fb](https://linux-hardware.org/?probe=d646e8d5fb) | Jan 01, 2024 |
| MSI           | P43i                        | [a31ae3403f](https://linux-hardware.org/?probe=a31ae3403f) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [e89341eb95](https://linux-hardware.org/?probe=e89341eb95) | Dec 31, 2023 |
| MSI           | A320M-A PRO MAX             | [b24918bdbc](https://linux-hardware.org/?probe=b24918bdbc) | Dec 31, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [f59bee0805](https://linux-hardware.org/?probe=f59bee0805) | Dec 31, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [99950d43fc](https://linux-hardware.org/?probe=99950d43fc) | Dec 31, 2023 |
| ASUSTek       | H110M-A                     | [f2fd99d70d](https://linux-hardware.org/?probe=f2fd99d70d) | Dec 30, 2023 |
| Dell          | 0TY565                      | [97111d45ea](https://linux-hardware.org/?probe=97111d45ea) | Dec 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6cb0db7e23](https://linux-hardware.org/?probe=6cb0db7e23) | Dec 30, 2023 |
| Gigabyte      | EP31-DS3L                   | [428843cfe5](https://linux-hardware.org/?probe=428843cfe5) | Dec 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a2ba669444](https://linux-hardware.org/?probe=a2ba669444) | Dec 30, 2023 |
| Gigabyte      | H310M A-CF x.x              | [85efe53330](https://linux-hardware.org/?probe=85efe53330) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [d094c3b4e3](https://linux-hardware.org/?probe=d094c3b4e3) | Dec 29, 2023 |
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
| ASUSTek       | H110M-A                     | [6add1ba46c](https://linux-hardware.org/?probe=6add1ba46c) | Dec 27, 2023 |
| Medion        | MS-7748                     | [029849e475](https://linux-hardware.org/?probe=029849e475) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | [e741a22dc6](https://linux-hardware.org/?probe=e741a22dc6) | Dec 27, 2023 |
| Gigabyte      | H61M-S1                     | [ab14001c30](https://linux-hardware.org/?probe=ab14001c30) | Dec 27, 2023 |
| ASUSTek       | H81M-E                      | [55173f5056](https://linux-hardware.org/?probe=55173f5056) | Dec 26, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [8c5b941b48](https://linux-hardware.org/?probe=8c5b941b48) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [82333229d6](https://linux-hardware.org/?probe=82333229d6) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [a87c271e68](https://linux-hardware.org/?probe=a87c271e68) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | [30780ea209](https://linux-hardware.org/?probe=30780ea209) | Dec 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [a8007743a8](https://linux-hardware.org/?probe=a8007743a8) | Dec 25, 2023 |
| Gigabyte      | H61M-S2PV                   | [2825577fd0](https://linux-hardware.org/?probe=2825577fd0) | Dec 25, 2023 |
| MSI           | H110M PRO-VD                | [624b1cbd0b](https://linux-hardware.org/?probe=624b1cbd0b) | Dec 24, 2023 |
| Medion        | MS-7748                     | [4df862d09e](https://linux-hardware.org/?probe=4df862d09e) | Dec 24, 2023 |
| MSI           | H110M PRO-VD                | [121d2e0b06](https://linux-hardware.org/?probe=121d2e0b06) | Dec 24, 2023 |
| ASUSTek       | H110M-A                     | [63306d22b2](https://linux-hardware.org/?probe=63306d22b2) | Dec 23, 2023 |
| Gigabyte      | Z390 UD                     | [cd36fc0dc1](https://linux-hardware.org/?probe=cd36fc0dc1) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0bc1c80333](https://linux-hardware.org/?probe=0bc1c80333) | Dec 21, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [544fdd3054](https://linux-hardware.org/?probe=544fdd3054) | Dec 21, 2023 |
| ASUSTek       | H110M-A                     | [3b149d0e20](https://linux-hardware.org/?probe=3b149d0e20) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | [0f7957917e](https://linux-hardware.org/?probe=0f7957917e) | Dec 21, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [d688c80ef7](https://linux-hardware.org/?probe=d688c80ef7) | Dec 18, 2023 |
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
| Lenovo        | 1036 NO DPK                 | [08f10e4a70](https://linux-hardware.org/?probe=08f10e4a70) | Dec 15, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [7701847681](https://linux-hardware.org/?probe=7701847681) | Dec 15, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [470281aedd](https://linux-hardware.org/?probe=470281aedd) | Dec 15, 2023 |
| HP            | 0B4Ch D                     | [e40498b1d1](https://linux-hardware.org/?probe=e40498b1d1) | Dec 14, 2023 |
| HP            | 0B4Ch D                     | [bb8a731dab](https://linux-hardware.org/?probe=bb8a731dab) | Dec 14, 2023 |
| Gigabyte      | B450M GAMING                | [02b6b32440](https://linux-hardware.org/?probe=02b6b32440) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | [016f269490](https://linux-hardware.org/?probe=016f269490) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [d55fed29c1](https://linux-hardware.org/?probe=d55fed29c1) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | [fc0fe04fab](https://linux-hardware.org/?probe=fc0fe04fab) | Dec 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [2199e3dc0f](https://linux-hardware.org/?probe=2199e3dc0f) | Dec 12, 2023 |
| HP            | 3033h                       | [3dddd6881a](https://linux-hardware.org/?probe=3dddd6881a) | Dec 11, 2023 |
| ASRock        | X370 Gaming X               | [3cba3acfa9](https://linux-hardware.org/?probe=3cba3acfa9) | Dec 10, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [840ffb67be](https://linux-hardware.org/?probe=840ffb67be) | Dec 10, 2023 |
| Gigabyte      | H61MA-D3V                   | [1b2d2135d4](https://linux-hardware.org/?probe=1b2d2135d4) | Dec 09, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [8ec0cd2d39](https://linux-hardware.org/?probe=8ec0cd2d39) | Dec 09, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [bdff414c43](https://linux-hardware.org/?probe=bdff414c43) | Dec 09, 2023 |
| MSI           | H110M PRO-VD                | [a691f52012](https://linux-hardware.org/?probe=a691f52012) | Dec 08, 2023 |
| MSI           | H110M PRO-VD                | [aa3ae99bf2](https://linux-hardware.org/?probe=aa3ae99bf2) | Dec 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [6be53926db](https://linux-hardware.org/?probe=6be53926db) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [1c2750202f](https://linux-hardware.org/?probe=1c2750202f) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ba4f3255bc](https://linux-hardware.org/?probe=ba4f3255bc) | Dec 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ae2fdd9470](https://linux-hardware.org/?probe=ae2fdd9470) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [dc50493c88](https://linux-hardware.org/?probe=dc50493c88) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | [9f5a520013](https://linux-hardware.org/?probe=9f5a520013) | Dec 08, 2023 |
| Dell          | 0TY565                      | [f037c10bc9](https://linux-hardware.org/?probe=f037c10bc9) | Dec 07, 2023 |
| Medion        | MS-7748                     | [1f11eab8f8](https://linux-hardware.org/?probe=1f11eab8f8) | Dec 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [e9436c2809](https://linux-hardware.org/?probe=e9436c2809) | Dec 06, 2023 |
| ASUSTek       | H110M-K                     | [2ebb7abc4c](https://linux-hardware.org/?probe=2ebb7abc4c) | Dec 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d658b900e7](https://linux-hardware.org/?probe=d658b900e7) | Dec 05, 2023 |
| HP            | 1495                        | [626fcfb788](https://linux-hardware.org/?probe=626fcfb788) | Dec 05, 2023 |
| Medion        | MS-7748                     | [8c5106d00b](https://linux-hardware.org/?probe=8c5106d00b) | Dec 05, 2023 |
| ASRock        | 960GC-GS FX                 | [524de55da0](https://linux-hardware.org/?probe=524de55da0) | Dec 04, 2023 |
| HP            | 339A                        | [b596b82bf1](https://linux-hardware.org/?probe=b596b82bf1) | Dec 04, 2023 |
| Dell          | 0PU052                      | [a436be0e88](https://linux-hardware.org/?probe=a436be0e88) | Dec 04, 2023 |
| ASRock        | H310CM-DVS                  | [1bf52989ef](https://linux-hardware.org/?probe=1bf52989ef) | Dec 03, 2023 |
| Gigabyte      | P67A-D3-B3                  | [77472c25c8](https://linux-hardware.org/?probe=77472c25c8) | Dec 03, 2023 |
| ASUSTek       | H110M-K                     | [e21f4b08b1](https://linux-hardware.org/?probe=e21f4b08b1) | Dec 03, 2023 |
| Gigabyte      | Z390 UD                     | [694abd409f](https://linux-hardware.org/?probe=694abd409f) | Dec 03, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b70c84adcf](https://linux-hardware.org/?probe=b70c84adcf) | Dec 01, 2023 |
| Gigabyte      | A520M S2H                   | [cdfe1883bc](https://linux-hardware.org/?probe=cdfe1883bc) | Nov 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [18ce09355c](https://linux-hardware.org/?probe=18ce09355c) | Nov 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | [875f72f0f7](https://linux-hardware.org/?probe=875f72f0f7) | Nov 28, 2023 |
| Dell          | 0K240Y A01                  | [d5440204b6](https://linux-hardware.org/?probe=d5440204b6) | Nov 28, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [05686c86bb](https://linux-hardware.org/?probe=05686c86bb) | Nov 28, 2023 |
| MSI           | P43i                        | [3291b84f5e](https://linux-hardware.org/?probe=3291b84f5e) | Nov 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [5e1e9b6a9e](https://linux-hardware.org/?probe=5e1e9b6a9e) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | [206d92bed2](https://linux-hardware.org/?probe=206d92bed2) | Nov 27, 2023 |
| Gigabyte      | 970A-UD3P                   | [bd533274c5](https://linux-hardware.org/?probe=bd533274c5) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [159ce7eba2](https://linux-hardware.org/?probe=159ce7eba2) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfc194ba14](https://linux-hardware.org/?probe=bfc194ba14) | Nov 27, 2023 |
| ASRock        | B85M                        | [0d3f6ceeea](https://linux-hardware.org/?probe=0d3f6ceeea) | Nov 27, 2023 |
| MSI           | H61M-P21                    | [5c106c49f4](https://linux-hardware.org/?probe=5c106c49f4) | Nov 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [1e0fa8c965](https://linux-hardware.org/?probe=1e0fa8c965) | Nov 27, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [c9dd5240c4](https://linux-hardware.org/?probe=c9dd5240c4) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | [4618c61b6c](https://linux-hardware.org/?probe=4618c61b6c) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | [bb4bd3eceb](https://linux-hardware.org/?probe=bb4bd3eceb) | Nov 26, 2023 |
| ASRock        | G41M-VS3                    | [c2e61e0cf9](https://linux-hardware.org/?probe=c2e61e0cf9) | Nov 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [200ddef2b0](https://linux-hardware.org/?probe=200ddef2b0) | Nov 26, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [250bd9f1df](https://linux-hardware.org/?probe=250bd9f1df) | Nov 26, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [61b5003420](https://linux-hardware.org/?probe=61b5003420) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | [c02d4a69b7](https://linux-hardware.org/?probe=c02d4a69b7) | Nov 25, 2023 |
| Gigabyte      | J4005ND2P-CF                | [04b5574c35](https://linux-hardware.org/?probe=04b5574c35) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [86b63c1acf](https://linux-hardware.org/?probe=86b63c1acf) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [8c071d6cda](https://linux-hardware.org/?probe=8c071d6cda) | Nov 24, 2023 |
| ASRock        | B550M Pro4                  | [4a05411844](https://linux-hardware.org/?probe=4a05411844) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-R               | [cbdb153211](https://linux-hardware.org/?probe=cbdb153211) | Nov 24, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [aed927ecb5](https://linux-hardware.org/?probe=aed927ecb5) | Nov 24, 2023 |
| Gigabyte      | H61M-S1                     | [38e1d661bf](https://linux-hardware.org/?probe=38e1d661bf) | Nov 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [977d9e09f1](https://linux-hardware.org/?probe=977d9e09f1) | Nov 23, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [b99f6e4f94](https://linux-hardware.org/?probe=b99f6e4f94) | Nov 23, 2023 |
| HP            | 1494                        | [3ff4bec1f2](https://linux-hardware.org/?probe=3ff4bec1f2) | Nov 23, 2023 |
| HP            | 1495                        | [630e59993e](https://linux-hardware.org/?probe=630e59993e) | Nov 23, 2023 |
| Dell          | 0TY565                      | [bf643a514f](https://linux-hardware.org/?probe=bf643a514f) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [d2a213e349](https://linux-hardware.org/?probe=d2a213e349) | Nov 21, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [d5cdc3089f](https://linux-hardware.org/?probe=d5cdc3089f) | Nov 21, 2023 |
| Dell          | 0XPDFK A00                  | [280e97cc34](https://linux-hardware.org/?probe=280e97cc34) | Nov 20, 2023 |
| Gigabyte      | B450M GAMING                | [dbf835efbb](https://linux-hardware.org/?probe=dbf835efbb) | Nov 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [795b0f6741](https://linux-hardware.org/?probe=795b0f6741) | Nov 16, 2023 |
| Dell          | 0TY565                      | [bd5ec5457e](https://linux-hardware.org/?probe=bd5ec5457e) | Nov 16, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [c79a431698](https://linux-hardware.org/?probe=c79a431698) | Nov 15, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d5cb68f63d](https://linux-hardware.org/?probe=d5cb68f63d) | Nov 12, 2023 |
| ASUSTek       | PRIME A320M-R               | [e02cd94d67](https://linux-hardware.org/?probe=e02cd94d67) | Nov 10, 2023 |
| ASUSTek       | PRIME A320M-R               | [ce2c43cb86](https://linux-hardware.org/?probe=ce2c43cb86) | Nov 10, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [f45397a161](https://linux-hardware.org/?probe=f45397a161) | Nov 09, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [5e0d19391e](https://linux-hardware.org/?probe=5e0d19391e) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-A               | [1399a1f267](https://linux-hardware.org/?probe=1399a1f267) | Nov 09, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [4c8dc5f59a](https://linux-hardware.org/?probe=4c8dc5f59a) | Nov 08, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [420d0d1ddc](https://linux-hardware.org/?probe=420d0d1ddc) | Nov 08, 2023 |
| Lenovo        | 1036 NO DPK                 | [ae88c578fa](https://linux-hardware.org/?probe=ae88c578fa) | Nov 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9c7020c9cc](https://linux-hardware.org/?probe=9c7020c9cc) | Nov 08, 2023 |
| Lenovo        | SDK0E50510 WIN              | [72a7ba6dde](https://linux-hardware.org/?probe=72a7ba6dde) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | [ef707f88ea](https://linux-hardware.org/?probe=ef707f88ea) | Nov 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [813b0c06e0](https://linux-hardware.org/?probe=813b0c06e0) | Nov 08, 2023 |
| Gigabyte      | H61M-S1                     | [68f36bd8cc](https://linux-hardware.org/?probe=68f36bd8cc) | Nov 08, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0d04acd22d](https://linux-hardware.org/?probe=0d04acd22d) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [982bf3ea4c](https://linux-hardware.org/?probe=982bf3ea4c) | Nov 07, 2023 |
| Dell          | 0TY565                      | [086bd4ec8f](https://linux-hardware.org/?probe=086bd4ec8f) | Nov 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [6e0b8b9df9](https://linux-hardware.org/?probe=6e0b8b9df9) | Nov 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [038e8719ec](https://linux-hardware.org/?probe=038e8719ec) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | [1e59a67f24](https://linux-hardware.org/?probe=1e59a67f24) | Nov 05, 2023 |
| HP            | 8265                        | [f6b38e869b](https://linux-hardware.org/?probe=f6b38e869b) | Nov 04, 2023 |
| HP            | 8265                        | [49cb61db2e](https://linux-hardware.org/?probe=49cb61db2e) | Nov 04, 2023 |
| Dell          | 0VHWTR A02                  | [7663b608dd](https://linux-hardware.org/?probe=7663b608dd) | Nov 03, 2023 |
| Gigabyte      | H61M-S1                     | [3b14b40bc9](https://linux-hardware.org/?probe=3b14b40bc9) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [0af35bd53b](https://linux-hardware.org/?probe=0af35bd53b) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | [32a001fb07](https://linux-hardware.org/?probe=32a001fb07) | Nov 02, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [dacdb79776](https://linux-hardware.org/?probe=dacdb79776) | Nov 01, 2023 |
| Gigabyte      | EP31-DS3L                   | [0a33a8b925](https://linux-hardware.org/?probe=0a33a8b925) | Nov 01, 2023 |
| MSI           | P43i                        | [847f1890e2](https://linux-hardware.org/?probe=847f1890e2) | Nov 01, 2023 |
| Dell          | 0RN474                      | [0ae8ddb9b3](https://linux-hardware.org/?probe=0ae8ddb9b3) | Nov 01, 2023 |
| ASRock        | G41M-VS3                    | [1d5b98622d](https://linux-hardware.org/?probe=1d5b98622d) | Oct 31, 2023 |
| ASRock        | G41M-VS3                    | [1a0da2bf85](https://linux-hardware.org/?probe=1a0da2bf85) | Oct 31, 2023 |
| Gigabyte      | H81M-HD3                    | [5f6ce5dbfb](https://linux-hardware.org/?probe=5f6ce5dbfb) | Oct 31, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [4cf4e845eb](https://linux-hardware.org/?probe=4cf4e845eb) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [1813899897](https://linux-hardware.org/?probe=1813899897) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | [6cf499a771](https://linux-hardware.org/?probe=6cf499a771) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [2a5fda7baf](https://linux-hardware.org/?probe=2a5fda7baf) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | [7d99dba1af](https://linux-hardware.org/?probe=7d99dba1af) | Oct 30, 2023 |
| ASUSTek       | H81M-E                      | [b48b015b4c](https://linux-hardware.org/?probe=b48b015b4c) | Oct 29, 2023 |
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
| ASUSTek       | M5A78L-M PLUS/USB3          | [a7a49e3d3f](https://linux-hardware.org/?probe=a7a49e3d3f) | Oct 23, 2023 |
| Gigabyte      | Z390 UD                     | [c926b51230](https://linux-hardware.org/?probe=c926b51230) | Oct 22, 2023 |
| Gigabyte      | Z390 UD                     | [ce8bac4075](https://linux-hardware.org/?probe=ce8bac4075) | Oct 22, 2023 |
| Dell          | 0D883F A06                  | [f687230e43](https://linux-hardware.org/?probe=f687230e43) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | [2cff132417](https://linux-hardware.org/?probe=2cff132417) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [dad965a109](https://linux-hardware.org/?probe=dad965a109) | Oct 19, 2023 |
| Lenovo        | 1036 NO DPK                 | [0733e9c4ae](https://linux-hardware.org/?probe=0733e9c4ae) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | [8ca65eabee](https://linux-hardware.org/?probe=8ca65eabee) | Oct 19, 2023 |
| MSI           | H61M-P21                    | [ba5fb8f49c](https://linux-hardware.org/?probe=ba5fb8f49c) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [330170d5d7](https://linux-hardware.org/?probe=330170d5d7) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | [e6840ccb2f](https://linux-hardware.org/?probe=e6840ccb2f) | Oct 19, 2023 |
| Dell          | 0K240Y A01                  | [e57b8986ab](https://linux-hardware.org/?probe=e57b8986ab) | Oct 18, 2023 |
| Gigabyte      | J4005ND2P-CF                | [23efcaf7a2](https://linux-hardware.org/?probe=23efcaf7a2) | Oct 18, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [ce65c73e40](https://linux-hardware.org/?probe=ce65c73e40) | Oct 18, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [64e28141f8](https://linux-hardware.org/?probe=64e28141f8) | Oct 17, 2023 |
| HP            | 8265                        | [4e8e0ea26a](https://linux-hardware.org/?probe=4e8e0ea26a) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9e3034f710](https://linux-hardware.org/?probe=9e3034f710) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [ea34b890ed](https://linux-hardware.org/?probe=ea34b890ed) | Oct 17, 2023 |
| HP            | 8265                        | [8f4c84f4f4](https://linux-hardware.org/?probe=8f4c84f4f4) | Oct 16, 2023 |
| ASUSTek       | PRIME B365M-A               | [b7fb2c5300](https://linux-hardware.org/?probe=b7fb2c5300) | Oct 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [707b8c0acd](https://linux-hardware.org/?probe=707b8c0acd) | Oct 15, 2023 |
| ASUSTek       | PRIME B365M-A               | [59a2975041](https://linux-hardware.org/?probe=59a2975041) | Oct 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [2c2a10deb9](https://linux-hardware.org/?probe=2c2a10deb9) | Oct 12, 2023 |
| ASRock        | H310CM-DVS                  | [1ae8fcd28c](https://linux-hardware.org/?probe=1ae8fcd28c) | Oct 12, 2023 |
| Medion        | MS-7748                     | [8b625acaae](https://linux-hardware.org/?probe=8b625acaae) | Oct 12, 2023 |
| Pegatron      | 2AB6                        | [50fbeed34d](https://linux-hardware.org/?probe=50fbeed34d) | Oct 11, 2023 |
| Pegatron      | 2AB6                        | [e97e82006c](https://linux-hardware.org/?probe=e97e82006c) | Oct 11, 2023 |
| Dell          | 0D883F A06                  | [d1e2846467](https://linux-hardware.org/?probe=d1e2846467) | Oct 11, 2023 |
| HP            | 0AA8h                       | [5b821194a7](https://linux-hardware.org/?probe=5b821194a7) | Oct 11, 2023 |
| HP            | 0AA8h                       | [d88c5dced7](https://linux-hardware.org/?probe=d88c5dced7) | Oct 11, 2023 |
| MSI           | MS-7817                     | [ed5e21c562](https://linux-hardware.org/?probe=ed5e21c562) | Oct 10, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [abca75fa11](https://linux-hardware.org/?probe=abca75fa11) | Oct 10, 2023 |
| eMachines     | EL1358G                     | [0548d7e6c7](https://linux-hardware.org/?probe=0548d7e6c7) | Oct 10, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [2cba957b98](https://linux-hardware.org/?probe=2cba957b98) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [be9975c532](https://linux-hardware.org/?probe=be9975c532) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | [c3d3003248](https://linux-hardware.org/?probe=c3d3003248) | Oct 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | [d935714c39](https://linux-hardware.org/?probe=d935714c39) | Oct 08, 2023 |
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
| Gigabyte      | Z390 UD                     | [539e4b56a6](https://linux-hardware.org/?probe=539e4b56a6) | Oct 06, 2023 |
| Medion        | MS-7748                     | [01b345394a](https://linux-hardware.org/?probe=01b345394a) | Oct 06, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [9e00c6f4b0](https://linux-hardware.org/?probe=9e00c6f4b0) | Oct 06, 2023 |
| HP            | 8265                        | [6fffe02648](https://linux-hardware.org/?probe=6fffe02648) | Oct 05, 2023 |
| HP            | 8265                        | [fe09b6a8e0](https://linux-hardware.org/?probe=fe09b6a8e0) | Oct 04, 2023 |
| ASUSTek       | PRIME A320M-R               | [d247c129c4](https://linux-hardware.org/?probe=d247c129c4) | Oct 04, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [d6cc456788](https://linux-hardware.org/?probe=d6cc456788) | Oct 04, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [78c456d55d](https://linux-hardware.org/?probe=78c456d55d) | Oct 04, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [2c0427d154](https://linux-hardware.org/?probe=2c0427d154) | Oct 03, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [0a765bb242](https://linux-hardware.org/?probe=0a765bb242) | Oct 03, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [ee08a8d73a](https://linux-hardware.org/?probe=ee08a8d73a) | Oct 02, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | [913fafd8a7](https://linux-hardware.org/?probe=913fafd8a7) | Oct 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | [c64f3bbdbd](https://linux-hardware.org/?probe=c64f3bbdbd) | Oct 02, 2023 |
| HP            | 1494                        | [1c5842d2b7](https://linux-hardware.org/?probe=1c5842d2b7) | Oct 01, 2023 |
| HP            | 1494                        | [4ffbf86079](https://linux-hardware.org/?probe=4ffbf86079) | Oct 01, 2023 |
| HP            | 339A                        | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| HP            | 1494                        | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Gigabyte      | Z390 UD                     | [e470a4941a](https://linux-hardware.org/?probe=e470a4941a) | Oct 01, 2023 |
| Gigabyte      | Z390 UD                     | [864f9a143f](https://linux-hardware.org/?probe=864f9a143f) | Sep 30, 2023 |
| ASRock        | B550M Pro4                  | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| ASRock        | X370 Gaming X               | [ee8f74ab5e](https://linux-hardware.org/?probe=ee8f74ab5e) | Sep 27, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [4cbe33187c](https://linux-hardware.org/?probe=4cbe33187c) | Sep 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [a3fc0915cd](https://linux-hardware.org/?probe=a3fc0915cd) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [3ffed1f144](https://linux-hardware.org/?probe=3ffed1f144) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | [e6eff7d60d](https://linux-hardware.org/?probe=e6eff7d60d) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [263bf34c40](https://linux-hardware.org/?probe=263bf34c40) | Sep 25, 2023 |
| Dell          | 0200DY A02                  | [0ecd2d60b4](https://linux-hardware.org/?probe=0ecd2d60b4) | Sep 25, 2023 |
| MSI           | B85M-E33                    | [1e246dda8b](https://linux-hardware.org/?probe=1e246dda8b) | Sep 25, 2023 |
| HP            | 09F8h                       | [3d8c4a9ace](https://linux-hardware.org/?probe=3d8c4a9ace) | Sep 25, 2023 |
| HP            | 09F8h                       | [f844e52238](https://linux-hardware.org/?probe=f844e52238) | Sep 25, 2023 |
| HP            | 09F8h                       | [d2ade2ea70](https://linux-hardware.org/?probe=d2ade2ea70) | Sep 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f94c540fde](https://linux-hardware.org/?probe=f94c540fde) | Sep 24, 2023 |
| ASRock        | G41M-VS3                    | [1dd60939d2](https://linux-hardware.org/?probe=1dd60939d2) | Sep 24, 2023 |
| ASUSTek       | PRIME B365M-A               | [ce1b08cdf9](https://linux-hardware.org/?probe=ce1b08cdf9) | Sep 23, 2023 |
| HP            | 1497                        | [cbbd6a0182](https://linux-hardware.org/?probe=cbbd6a0182) | Sep 23, 2023 |
| MSI           | MS-7309                     | [356be353d5](https://linux-hardware.org/?probe=356be353d5) | Sep 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [b519a4adea](https://linux-hardware.org/?probe=b519a4adea) | Sep 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [8d7c00fcd2](https://linux-hardware.org/?probe=8d7c00fcd2) | Sep 23, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [1752297c85](https://linux-hardware.org/?probe=1752297c85) | Sep 22, 2023 |
| Gigabyte      | A520M S2H                   | [134cfff173](https://linux-hardware.org/?probe=134cfff173) | Sep 22, 2023 |
| ASRock        | B550M Pro4                  | [daa9128e32](https://linux-hardware.org/?probe=daa9128e32) | Sep 22, 2023 |
| Gigabyte      | H97-D3H-CF                  | [61ce9ed478](https://linux-hardware.org/?probe=61ce9ed478) | Sep 22, 2023 |
| Gigabyte      | H110M-S2V-CF                | [96ba82f38e](https://linux-hardware.org/?probe=96ba82f38e) | Sep 22, 2023 |
| Gigabyte      | EP31-DS3L                   | [701abaeb8f](https://linux-hardware.org/?probe=701abaeb8f) | Sep 22, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [ff935c4dbe](https://linux-hardware.org/?probe=ff935c4dbe) | Sep 22, 2023 |
| Gigabyte      | H61M-S1                     | [caa45f79f6](https://linux-hardware.org/?probe=caa45f79f6) | Sep 22, 2023 |
| ASRock        | B85M                        | [5b78620442](https://linux-hardware.org/?probe=5b78620442) | Sep 22, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [60976010ac](https://linux-hardware.org/?probe=60976010ac) | Sep 21, 2023 |
| ASUSTek       | H110M-A                     | [b21f53b9e1](https://linux-hardware.org/?probe=b21f53b9e1) | Sep 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d1b966125a](https://linux-hardware.org/?probe=d1b966125a) | Sep 21, 2023 |
| Lenovo        | SDK0E50510 WIN              | [6b9f9348c0](https://linux-hardware.org/?probe=6b9f9348c0) | Sep 21, 2023 |
| HP            | 1495                        | [9c5926d73b](https://linux-hardware.org/?probe=9c5926d73b) | Sep 21, 2023 |
| Gigabyte      | J4005ND2P-CF                | [f3deee7792](https://linux-hardware.org/?probe=f3deee7792) | Sep 20, 2023 |
| Lenovo        | 1730-A1G                    | [9f9580c81f](https://linux-hardware.org/?probe=9f9580c81f) | Sep 19, 2023 |
| Lenovo        | 1730-A1G                    | [e58cd05ca6](https://linux-hardware.org/?probe=e58cd05ca6) | Sep 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | [12a4225b04](https://linux-hardware.org/?probe=12a4225b04) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | [851a7301bc](https://linux-hardware.org/?probe=851a7301bc) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | [8ee590e888](https://linux-hardware.org/?probe=8ee590e888) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | [42ade99539](https://linux-hardware.org/?probe=42ade99539) | Sep 18, 2023 |
| HP            | 1494                        | [f7dcc5924c](https://linux-hardware.org/?probe=f7dcc5924c) | Sep 17, 2023 |
| HP            | 1494                        | [35c90d3fb2](https://linux-hardware.org/?probe=35c90d3fb2) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | [92ff22e072](https://linux-hardware.org/?probe=92ff22e072) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | [7d679bbf7f](https://linux-hardware.org/?probe=7d679bbf7f) | Sep 17, 2023 |
| Huanan        | X99-QD4 V1.0                | [ae9c2e3978](https://linux-hardware.org/?probe=ae9c2e3978) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | [8076be0adb](https://linux-hardware.org/?probe=8076be0adb) | Sep 16, 2023 |
| Dell          | 0K240Y A01                  | [bd5fae0639](https://linux-hardware.org/?probe=bd5fae0639) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | [781590255d](https://linux-hardware.org/?probe=781590255d) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | [382acd4186](https://linux-hardware.org/?probe=382acd4186) | Sep 15, 2023 |
| Gigabyte      | P67A-D3-B3                  | [14a4828110](https://linux-hardware.org/?probe=14a4828110) | Sep 14, 2023 |
| HP            | 8265                        | [1e16a47683](https://linux-hardware.org/?probe=1e16a47683) | Sep 13, 2023 |
| ASRock        | G41M-VS3                    | [bc19e0cdbb](https://linux-hardware.org/?probe=bc19e0cdbb) | Sep 13, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [60b271e896](https://linux-hardware.org/?probe=60b271e896) | Sep 11, 2023 |
| HP            | 8265                        | [f7e98e0f58](https://linux-hardware.org/?probe=f7e98e0f58) | Sep 10, 2023 |
| HP            | 3047h                       | [1070c2f57a](https://linux-hardware.org/?probe=1070c2f57a) | Sep 10, 2023 |
| HP            | 3047h                       | [746e154eaf](https://linux-hardware.org/?probe=746e154eaf) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | [31f5d64453](https://linux-hardware.org/?probe=31f5d64453) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | [625c711748](https://linux-hardware.org/?probe=625c711748) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9c9441fa1c](https://linux-hardware.org/?probe=9c9441fa1c) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2706096498](https://linux-hardware.org/?probe=2706096498) | Sep 10, 2023 |
| HP            | 339A                        | [f19d37b028](https://linux-hardware.org/?probe=f19d37b028) | Sep 10, 2023 |
| HP            | 339A                        | [794685ff75](https://linux-hardware.org/?probe=794685ff75) | Sep 10, 2023 |
| HP            | 1497                        | [e420bbd661](https://linux-hardware.org/?probe=e420bbd661) | Sep 09, 2023 |
| HP            | 1497                        | [6de463b204](https://linux-hardware.org/?probe=6de463b204) | Sep 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [8a383606e3](https://linux-hardware.org/?probe=8a383606e3) | Sep 08, 2023 |
| ASUSTek       | H110M-A/M.2                 | [7ccec4335d](https://linux-hardware.org/?probe=7ccec4335d) | Sep 08, 2023 |
| ASUSTek       | H110M-A/M.2                 | [566a29eb5e](https://linux-hardware.org/?probe=566a29eb5e) | Sep 08, 2023 |
| Gigabyte      | A520M S2H                   | [49adfda956](https://linux-hardware.org/?probe=49adfda956) | Sep 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [898930f2b1](https://linux-hardware.org/?probe=898930f2b1) | Sep 07, 2023 |
| Gigabyte      | A520M S2H                   | [132fa17be7](https://linux-hardware.org/?probe=132fa17be7) | Sep 06, 2023 |
| Gigabyte      | A520M S2H                   | [36e10816ea](https://linux-hardware.org/?probe=36e10816ea) | Sep 06, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [c19df6a939](https://linux-hardware.org/?probe=c19df6a939) | Sep 06, 2023 |
| Huanan        | X99-QD4 V1.0                | [86a4e0d5b8](https://linux-hardware.org/?probe=86a4e0d5b8) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | [d729a17611](https://linux-hardware.org/?probe=d729a17611) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | [857d41cc6a](https://linux-hardware.org/?probe=857d41cc6a) | Sep 06, 2023 |
| ASUSTek       | PRIME B365M-A               | [65bbed09ce](https://linux-hardware.org/?probe=65bbed09ce) | Sep 06, 2023 |
| Gigabyte      | H61M-S1                     | [8f2ba921b5](https://linux-hardware.org/?probe=8f2ba921b5) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | [6d7631e83a](https://linux-hardware.org/?probe=6d7631e83a) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | [304ccb5f7e](https://linux-hardware.org/?probe=304ccb5f7e) | Sep 05, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [6d1d81c7b3](https://linux-hardware.org/?probe=6d1d81c7b3) | Sep 05, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [4297e9f110](https://linux-hardware.org/?probe=4297e9f110) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | [e6eb36b583](https://linux-hardware.org/?probe=e6eb36b583) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | [7647c25446](https://linux-hardware.org/?probe=7647c25446) | Sep 05, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [d66af7c01e](https://linux-hardware.org/?probe=d66af7c01e) | Sep 05, 2023 |
| Huanan        | X99-QD4 V1.0                | [9051992ac5](https://linux-hardware.org/?probe=9051992ac5) | Sep 05, 2023 |
| HP            | 1495                        | [272f11edff](https://linux-hardware.org/?probe=272f11edff) | Sep 05, 2023 |
| Dell          | 0VHWTR A02                  | [8e4830d581](https://linux-hardware.org/?probe=8e4830d581) | Sep 04, 2023 |
| MSI           | H61M-P21                    | [9eddb8442b](https://linux-hardware.org/?probe=9eddb8442b) | Sep 04, 2023 |
| Dell          | 0TY565                      | [c1a456e342](https://linux-hardware.org/?probe=c1a456e342) | Sep 04, 2023 |
| MSI           | B85M-E33                    | [13b7edd351](https://linux-hardware.org/?probe=13b7edd351) | Sep 04, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [6dd9f72144](https://linux-hardware.org/?probe=6dd9f72144) | Sep 04, 2023 |
| Gigabyte      | A520M S2H                   | [a6957d8672](https://linux-hardware.org/?probe=a6957d8672) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | [8bbf469df8](https://linux-hardware.org/?probe=8bbf469df8) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [c450c306b1](https://linux-hardware.org/?probe=c450c306b1) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [f56611f610](https://linux-hardware.org/?probe=f56611f610) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [29553c1c51](https://linux-hardware.org/?probe=29553c1c51) | Sep 03, 2023 |
| Huanan        | X99-QD4 V1.0                | [adaa4a1718](https://linux-hardware.org/?probe=adaa4a1718) | Sep 02, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [b6a5325068](https://linux-hardware.org/?probe=b6a5325068) | Sep 02, 2023 |
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
| Gigabyte      | H61M-S1                     | [f341ee514c](https://linux-hardware.org/?probe=f341ee514c) | Aug 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [ebfb32e1a8](https://linux-hardware.org/?probe=ebfb32e1a8) | Aug 29, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [cc92a730bc](https://linux-hardware.org/?probe=cc92a730bc) | Aug 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [33fbfa4413](https://linux-hardware.org/?probe=33fbfa4413) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | [8a109f7691](https://linux-hardware.org/?probe=8a109f7691) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | [c806d70c9d](https://linux-hardware.org/?probe=c806d70c9d) | Aug 29, 2023 |
| ASUSTek       | H110M-K                     | [3869234a03](https://linux-hardware.org/?probe=3869234a03) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | [9cbff867a4](https://linux-hardware.org/?probe=9cbff867a4) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | [8cc632de8d](https://linux-hardware.org/?probe=8cc632de8d) | Aug 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ebf28922af](https://linux-hardware.org/?probe=ebf28922af) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | [16c1728f79](https://linux-hardware.org/?probe=16c1728f79) | Aug 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [39db55a5e2](https://linux-hardware.org/?probe=39db55a5e2) | Aug 28, 2023 |
| HP            | 339A                        | [56775507f8](https://linux-hardware.org/?probe=56775507f8) | Aug 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | [21b85ec9f3](https://linux-hardware.org/?probe=21b85ec9f3) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | [9b898e43e7](https://linux-hardware.org/?probe=9b898e43e7) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | [43c8f5f7bd](https://linux-hardware.org/?probe=43c8f5f7bd) | Aug 28, 2023 |
| ASUSTek       | H110M-A/M.2                 | [d8c81e6e37](https://linux-hardware.org/?probe=d8c81e6e37) | Aug 28, 2023 |
| ASRock        | X370 Gaming X               | [d9efc054ab](https://linux-hardware.org/?probe=d9efc054ab) | Aug 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8169effdbe](https://linux-hardware.org/?probe=8169effdbe) | Aug 27, 2023 |
| ASUSTek       | H110M-A                     | [c7ee25be08](https://linux-hardware.org/?probe=c7ee25be08) | Aug 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | [579e64039e](https://linux-hardware.org/?probe=579e64039e) | Aug 27, 2023 |
| ASRock        | B85M                        | [e1030ad449](https://linux-hardware.org/?probe=e1030ad449) | Aug 27, 2023 |
| ASUSTek       | H110M-K                     | [bfaf77795d](https://linux-hardware.org/?probe=bfaf77795d) | Aug 27, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [7a3378b6eb](https://linux-hardware.org/?probe=7a3378b6eb) | Aug 27, 2023 |
| HP            | 8265                        | [39f6952188](https://linux-hardware.org/?probe=39f6952188) | Aug 26, 2023 |
| ASRock        | B85M                        | [70af81b1a1](https://linux-hardware.org/?probe=70af81b1a1) | Aug 26, 2023 |
| ASUSTek       | H110M-A                     | [56f9a82624](https://linux-hardware.org/?probe=56f9a82624) | Aug 26, 2023 |
| Gigabyte      | H110M-S2V-CF                | [855ad99ea5](https://linux-hardware.org/?probe=855ad99ea5) | Aug 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [78a62eeefe](https://linux-hardware.org/?probe=78a62eeefe) | Aug 26, 2023 |
| MSI           | P43i                        | [3f3ea5ff94](https://linux-hardware.org/?probe=3f3ea5ff94) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [e226d45872](https://linux-hardware.org/?probe=e226d45872) | Aug 26, 2023 |
| ASRock        | G41M-VS3                    | [b1e5815ba9](https://linux-hardware.org/?probe=b1e5815ba9) | Aug 26, 2023 |
| ASUSTek       | H81M-E                      | [5e884e12a0](https://linux-hardware.org/?probe=5e884e12a0) | Aug 26, 2023 |
| MSI           | MS-7817                     | [9b7cfe20df](https://linux-hardware.org/?probe=9b7cfe20df) | Aug 25, 2023 |
| Gigabyte      | H97-D3H-CF                  | [675c426397](https://linux-hardware.org/?probe=675c426397) | Aug 25, 2023 |
| ASRock        | H81M-HDS                    | [9d18657882](https://linux-hardware.org/?probe=9d18657882) | Aug 22, 2023 |
| HP            | 0B4Ch D                     | [4cb50f9265](https://linux-hardware.org/?probe=4cb50f9265) | Aug 22, 2023 |
| Gigabyte      | H310M A-CF x.x              | [76d74daf52](https://linux-hardware.org/?probe=76d74daf52) | Aug 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | [2f0cd6e6d3](https://linux-hardware.org/?probe=2f0cd6e6d3) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | [25fbe59866](https://linux-hardware.org/?probe=25fbe59866) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | [a6cf8bf5f2](https://linux-hardware.org/?probe=a6cf8bf5f2) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | [97a587e6ad](https://linux-hardware.org/?probe=97a587e6ad) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | [5ac356a22f](https://linux-hardware.org/?probe=5ac356a22f) | Aug 19, 2023 |
| Gigabyte      | B450M GAMING                | [68bfd376a0](https://linux-hardware.org/?probe=68bfd376a0) | Aug 18, 2023 |
| HP            | 3031h                       | [4ce70764b2](https://linux-hardware.org/?probe=4ce70764b2) | Aug 16, 2023 |
| HP            | 1495                        | [1d04585fac](https://linux-hardware.org/?probe=1d04585fac) | Aug 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | [7b48c318ed](https://linux-hardware.org/?probe=7b48c318ed) | Aug 15, 2023 |
| Gigabyte      | H61M-S1                     | [e63deac9b1](https://linux-hardware.org/?probe=e63deac9b1) | Aug 13, 2023 |
| Huanan        | X99-QD4 V1.0                | [72977f6f8a](https://linux-hardware.org/?probe=72977f6f8a) | Aug 13, 2023 |
| Gigabyte      | H61M-S1                     | [b92a6f8a9e](https://linux-hardware.org/?probe=b92a6f8a9e) | Aug 12, 2023 |
| Gigabyte      | H61M-S1                     | [031ed1d4e7](https://linux-hardware.org/?probe=031ed1d4e7) | Aug 12, 2023 |
| HP            | 1495                        | [837afb7bfa](https://linux-hardware.org/?probe=837afb7bfa) | Aug 12, 2023 |
| HP            | 1495                        | [9e8b73f16e](https://linux-hardware.org/?probe=9e8b73f16e) | Aug 11, 2023 |
| Huanan        | X99-QD4 V1.0                | [17e503622d](https://linux-hardware.org/?probe=17e503622d) | Aug 11, 2023 |
| Lenovo        | SDK0E50510 WIN              | [485a8bf15d](https://linux-hardware.org/?probe=485a8bf15d) | Aug 10, 2023 |
| HP            | 1495                        | [6c458bf059](https://linux-hardware.org/?probe=6c458bf059) | Aug 10, 2023 |
| HP            | 0AA4h                       | [e4da6a6aaf](https://linux-hardware.org/?probe=e4da6a6aaf) | Aug 09, 2023 |
| HP            | 0AA4h                       | [4081f7bbda](https://linux-hardware.org/?probe=4081f7bbda) | Aug 09, 2023 |
| Dell          | 0RN474                      | [61153fe575](https://linux-hardware.org/?probe=61153fe575) | Aug 09, 2023 |
| Gigabyte      | H61M-S1                     | [c160e44518](https://linux-hardware.org/?probe=c160e44518) | Aug 08, 2023 |
| ASRock        | H81M-HDS                    | [64dc45c007](https://linux-hardware.org/?probe=64dc45c007) | Aug 07, 2023 |
| Huanan        | X99-QD4 V1.0                | [b62c8c40f5](https://linux-hardware.org/?probe=b62c8c40f5) | Aug 07, 2023 |
| Gigabyte      | J4005ND2P-CF                | [f3644b56ad](https://linux-hardware.org/?probe=f3644b56ad) | Aug 06, 2023 |
| Huanan        | X99-QD4 V1.0                | [9aaaaec131](https://linux-hardware.org/?probe=9aaaaec131) | Aug 05, 2023 |
| HP            | 1495                        | [17ae98cda8](https://linux-hardware.org/?probe=17ae98cda8) | Aug 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [91b8e07f0d](https://linux-hardware.org/?probe=91b8e07f0d) | Aug 04, 2023 |
| Gigabyte      | H61M-S1                     | [64803a4cd7](https://linux-hardware.org/?probe=64803a4cd7) | Aug 04, 2023 |
| HP            | 1495                        | [75dae4c3a6](https://linux-hardware.org/?probe=75dae4c3a6) | Aug 04, 2023 |
| MSI           | P43i                        | [683b26e344](https://linux-hardware.org/?probe=683b26e344) | Aug 03, 2023 |
| Medion        | MS-7748                     | [413b9e74a6](https://linux-hardware.org/?probe=413b9e74a6) | Aug 03, 2023 |
| Huanan        | X99-QD4 V1.0                | [e47b01848a](https://linux-hardware.org/?probe=e47b01848a) | Aug 03, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [99cae22846](https://linux-hardware.org/?probe=99cae22846) | Aug 02, 2023 |
| Huanan        | X99-QD4 V1.0                | [56573f8499](https://linux-hardware.org/?probe=56573f8499) | Aug 01, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [6202f3b97e](https://linux-hardware.org/?probe=6202f3b97e) | Jul 31, 2023 |
| Dell          | 0WMJ54 A01                  | [908f49c376](https://linux-hardware.org/?probe=908f49c376) | Jul 31, 2023 |
| Lenovo        | SDK0E50510 WIN              | [385c97c1d3](https://linux-hardware.org/?probe=385c97c1d3) | Jul 28, 2023 |
| Gigabyte      | H61M-S1                     | [ec84069efb](https://linux-hardware.org/?probe=ec84069efb) | Jul 28, 2023 |
| Gigabyte      | H61M-S1                     | [89557d5880](https://linux-hardware.org/?probe=89557d5880) | Jul 28, 2023 |
| HP            | 1495                        | [b4e2031d1e](https://linux-hardware.org/?probe=b4e2031d1e) | Jul 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [ea550fb04c](https://linux-hardware.org/?probe=ea550fb04c) | Jul 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5b17937c10](https://linux-hardware.org/?probe=5b17937c10) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | [ebaacb8057](https://linux-hardware.org/?probe=ebaacb8057) | Jul 26, 2023 |
| Dell          | 0D883F A06                  | [3988b909c7](https://linux-hardware.org/?probe=3988b909c7) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [de48c51732](https://linux-hardware.org/?probe=de48c51732) | Jul 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [f2bef973eb](https://linux-hardware.org/?probe=f2bef973eb) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [04a75d9e0c](https://linux-hardware.org/?probe=04a75d9e0c) | Jul 26, 2023 |
| HP            | 8265                        | [96a99f0e8f](https://linux-hardware.org/?probe=96a99f0e8f) | Jul 25, 2023 |
| Acer          | Veriton M4610G              | [aef65d0501](https://linux-hardware.org/?probe=aef65d0501) | Jul 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4c5c8def02](https://linux-hardware.org/?probe=4c5c8def02) | Jul 24, 2023 |
| Dell          | 0TY565                      | [828f20c8bb](https://linux-hardware.org/?probe=828f20c8bb) | Jul 24, 2023 |
| Acer          | Veriton M4610G              | [57cdc7820f](https://linux-hardware.org/?probe=57cdc7820f) | Jul 23, 2023 |
| Gigabyte      | G31M-ES2L                   | [91d19df4b4](https://linux-hardware.org/?probe=91d19df4b4) | Jul 23, 2023 |
| HP            | 8265                        | [0e5a193692](https://linux-hardware.org/?probe=0e5a193692) | Jul 23, 2023 |
| HP            | 1495                        | [a9bd3f59e8](https://linux-hardware.org/?probe=a9bd3f59e8) | Jul 23, 2023 |
| Dell          | 0PU052                      | [43454a5114](https://linux-hardware.org/?probe=43454a5114) | Jul 22, 2023 |
| Dell          | 0PU052                      | [b1ba2d4239](https://linux-hardware.org/?probe=b1ba2d4239) | Jul 22, 2023 |
| Huanan        | X99-QD4 V1.0                | [fc1e32f937](https://linux-hardware.org/?probe=fc1e32f937) | Jul 17, 2023 |
| MSI           | B85M-E33                    | [6d2ee4521b](https://linux-hardware.org/?probe=6d2ee4521b) | Jul 17, 2023 |
| MSI           | B85M-E33                    | [a8bbbd8c49](https://linux-hardware.org/?probe=a8bbbd8c49) | Jul 17, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | [f04f199334](https://linux-hardware.org/?probe=f04f199334) | Jul 16, 2023 |
| Huanan        | X99-QD4 V1.0                | [b5588d7209](https://linux-hardware.org/?probe=b5588d7209) | Jul 15, 2023 |
| Dell          | 0GY6Y8 A01                  | [a562b6518f](https://linux-hardware.org/?probe=a562b6518f) | Jul 15, 2023 |
| Gigabyte      | H310M A-CF x.x              | [655cb31a8a](https://linux-hardware.org/?probe=655cb31a8a) | Jul 14, 2023 |
| Lenovo        | SDK0E50510 WIN              | [0d773629f2](https://linux-hardware.org/?probe=0d773629f2) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | [e695d46a05](https://linux-hardware.org/?probe=e695d46a05) | Jul 14, 2023 |
| Dell          | 0VHWTR A02                  | [93a455ac9b](https://linux-hardware.org/?probe=93a455ac9b) | Jul 14, 2023 |
| Gigabyte      | G31M-ES2C                   | [202ada5369](https://linux-hardware.org/?probe=202ada5369) | Jul 13, 2023 |
| Gigabyte      | G31M-ES2C                   | [88982c878a](https://linux-hardware.org/?probe=88982c878a) | Jul 13, 2023 |
| Gigabyte      | B450M GAMING                | [2f3da717f3](https://linux-hardware.org/?probe=2f3da717f3) | Jul 12, 2023 |
| Gigabyte      | B450M GAMING                | [bfe4c07a40](https://linux-hardware.org/?probe=bfe4c07a40) | Jul 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [657750190f](https://linux-hardware.org/?probe=657750190f) | Jul 08, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [81dd9a0120](https://linux-hardware.org/?probe=81dd9a0120) | Jul 08, 2023 |
| Gigabyte      | H61M-S2PV                   | [5a62a75599](https://linux-hardware.org/?probe=5a62a75599) | Jul 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | [bd3b079d0d](https://linux-hardware.org/?probe=bd3b079d0d) | Jul 04, 2023 |
| ASRock        | FM2A75M Pro4+               | [7390114024](https://linux-hardware.org/?probe=7390114024) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | [84a32e1b42](https://linux-hardware.org/?probe=84a32e1b42) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [9393d317b6](https://linux-hardware.org/?probe=9393d317b6) | Jul 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [2a7725896c](https://linux-hardware.org/?probe=2a7725896c) | Jul 03, 2023 |
| Gigabyte      | Z390 UD                     | [12bdaa446f](https://linux-hardware.org/?probe=12bdaa446f) | Jul 03, 2023 |
| Lenovo        | SDK0E50510 WIN              | [eb7ec8410d](https://linux-hardware.org/?probe=eb7ec8410d) | Jul 02, 2023 |
| Dell          | 0D883F A06                  | [b27b2b3825](https://linux-hardware.org/?probe=b27b2b3825) | Jul 01, 2023 |
| Dell          | 0D883F A06                  | [e50079b95e](https://linux-hardware.org/?probe=e50079b95e) | Jul 01, 2023 |
| Lenovo        | SDK0E50510 WIN              | [ca1817783e](https://linux-hardware.org/?probe=ca1817783e) | Jul 01, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [908af533fc](https://linux-hardware.org/?probe=908af533fc) | Jun 30, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | [298a4bf290](https://linux-hardware.org/?probe=298a4bf290) | Jun 30, 2023 |
| ASRock        | G41M-VS3                    | [344a5eda20](https://linux-hardware.org/?probe=344a5eda20) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [565c1ea1c2](https://linux-hardware.org/?probe=565c1ea1c2) | Jun 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | [545a2c4e26](https://linux-hardware.org/?probe=545a2c4e26) | Jun 28, 2023 |
| Dell          | 0D883F A06                  | [b26a7fb008](https://linux-hardware.org/?probe=b26a7fb008) | Jun 25, 2023 |
| Dell          | 0D883F A06                  | [04f61a169e](https://linux-hardware.org/?probe=04f61a169e) | Jun 25, 2023 |
| Lenovo        | SDK0E50510 WIN              | [839490cb5a](https://linux-hardware.org/?probe=839490cb5a) | Jun 25, 2023 |
| ASUSTek       | H110M-A/M.2                 | [6b36aca9e6](https://linux-hardware.org/?probe=6b36aca9e6) | Jun 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | [75cab0a675](https://linux-hardware.org/?probe=75cab0a675) | Jun 24, 2023 |
| HP            | 8265                        | [863a585141](https://linux-hardware.org/?probe=863a585141) | Jun 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0a065bce17](https://linux-hardware.org/?probe=0a065bce17) | Jun 22, 2023 |
| ASRock        | FM2A75M Pro4+               | [a3f0d3cbc6](https://linux-hardware.org/?probe=a3f0d3cbc6) | Jun 21, 2023 |
| ASRock        | FM2A75M Pro4+               | [8cfeb06220](https://linux-hardware.org/?probe=8cfeb06220) | Jun 21, 2023 |
| Gigabyte      | B450M GAMING                | [a6f14223ae](https://linux-hardware.org/?probe=a6f14223ae) | Jun 20, 2023 |
| Gigabyte      | B450M GAMING                | [076a78c151](https://linux-hardware.org/?probe=076a78c151) | Jun 20, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [d09be5d97c](https://linux-hardware.org/?probe=d09be5d97c) | Jun 20, 2023 |
| Dell          | 0WMJ54 A01                  | [0cbbe081c8](https://linux-hardware.org/?probe=0cbbe081c8) | Jun 19, 2023 |
| Dell          | 0WMJ54 A01                  | [41c5ad600b](https://linux-hardware.org/?probe=41c5ad600b) | Jun 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [eeb6dfe9be](https://linux-hardware.org/?probe=eeb6dfe9be) | Jun 18, 2023 |
| Gigabyte      | G31M-ES2L                   | [b90840dbba](https://linux-hardware.org/?probe=b90840dbba) | Jun 18, 2023 |
| ASRock        | G41M-VS3                    | [6bd02aa0f2](https://linux-hardware.org/?probe=6bd02aa0f2) | Jun 18, 2023 |
| ASRock        | A520M-HDV                   | [e0d2c8f040](https://linux-hardware.org/?probe=e0d2c8f040) | Jun 18, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [24624ec732](https://linux-hardware.org/?probe=24624ec732) | Jun 17, 2023 |
| ASRock        | A520M-HDV                   | [4f97748920](https://linux-hardware.org/?probe=4f97748920) | Jun 16, 2023 |
| Dell          | 0WMJ54 A01                  | [11c34f6cde](https://linux-hardware.org/?probe=11c34f6cde) | Jun 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | [6adbb0811a](https://linux-hardware.org/?probe=6adbb0811a) | Jun 15, 2023 |
| ASUSTek       | PRIME B365M-A               | [bab5e06a26](https://linux-hardware.org/?probe=bab5e06a26) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b560ba8109](https://linux-hardware.org/?probe=b560ba8109) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [9111abbf0e](https://linux-hardware.org/?probe=9111abbf0e) | Jun 14, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [817c9acfa2](https://linux-hardware.org/?probe=817c9acfa2) | Jun 14, 2023 |
| MSI           | MS-7309                     | [fc85dd07ed](https://linux-hardware.org/?probe=fc85dd07ed) | Jun 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [807fe357c7](https://linux-hardware.org/?probe=807fe357c7) | Jun 13, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [6385fdf921](https://linux-hardware.org/?probe=6385fdf921) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | [9e5b8610e3](https://linux-hardware.org/?probe=9e5b8610e3) | Jun 13, 2023 |
| HP            | 339A                        | [a8e90edbdb](https://linux-hardware.org/?probe=a8e90edbdb) | Jun 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0c2fae415b](https://linux-hardware.org/?probe=0c2fae415b) | Jun 12, 2023 |
| ASUSTek       | H110M-A                     | [a6333257c7](https://linux-hardware.org/?probe=a6333257c7) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [7d188dbdfa](https://linux-hardware.org/?probe=7d188dbdfa) | Jun 12, 2023 |
| Gigabyte      | H61M-S1                     | [edbcec7f32](https://linux-hardware.org/?probe=edbcec7f32) | Jun 12, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [75b330369d](https://linux-hardware.org/?probe=75b330369d) | Jun 12, 2023 |
| Gigabyte      | Z390 UD                     | [62965b4b77](https://linux-hardware.org/?probe=62965b4b77) | Jun 12, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [9e9746b2bc](https://linux-hardware.org/?probe=9e9746b2bc) | Jun 12, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [b2e6e1ed18](https://linux-hardware.org/?probe=b2e6e1ed18) | Jun 12, 2023 |
| Gigabyte      | H110M-S2V-CF                | [5e96ddeeac](https://linux-hardware.org/?probe=5e96ddeeac) | Jun 12, 2023 |
| HP            | 8265                        | [fb5cbd10fa](https://linux-hardware.org/?probe=fb5cbd10fa) | Jun 11, 2023 |
| Gigabyte      | Z390 UD                     | [d9ff4ccb1c](https://linux-hardware.org/?probe=d9ff4ccb1c) | Jun 11, 2023 |
| Gigabyte      | Z390 UD                     | [5adb23a979](https://linux-hardware.org/?probe=5adb23a979) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e98ac1bb4c](https://linux-hardware.org/?probe=e98ac1bb4c) | Jun 11, 2023 |
| Gigabyte      | P35-S3G                     | [71339b40ec](https://linux-hardware.org/?probe=71339b40ec) | Jun 10, 2023 |
| MSI           | MS-7309                     | [9c6db3b61d](https://linux-hardware.org/?probe=9c6db3b61d) | Jun 10, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dfac11ccad](https://linux-hardware.org/?probe=dfac11ccad) | Jun 10, 2023 |
| Gigabyte      | P67A-D3-B3                  | [142fc47b59](https://linux-hardware.org/?probe=142fc47b59) | Jun 09, 2023 |
| Gigabyte      | G41M-ES2L                   | [22e9021ae3](https://linux-hardware.org/?probe=22e9021ae3) | Jun 09, 2023 |
| HP            | 18E7                        | [d80810b7f8](https://linux-hardware.org/?probe=d80810b7f8) | Jun 08, 2023 |
| Gigabyte      | G41M-ES2L                   | [a707a562b8](https://linux-hardware.org/?probe=a707a562b8) | Jun 08, 2023 |
| Gigabyte      | H61M-S1                     | [3063c26aca](https://linux-hardware.org/?probe=3063c26aca) | Jun 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9de320e96f](https://linux-hardware.org/?probe=9de320e96f) | Jun 08, 2023 |
| ASUSTek       | H110M-A                     | [a9ca37ac88](https://linux-hardware.org/?probe=a9ca37ac88) | Jun 07, 2023 |
| Gigabyte      | GA-880GM-D2H                | [328aaf23c9](https://linux-hardware.org/?probe=328aaf23c9) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | [e33a2ba9dc](https://linux-hardware.org/?probe=e33a2ba9dc) | Jun 07, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [3c89a2a6a2](https://linux-hardware.org/?probe=3c89a2a6a2) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | [e05fc7beed](https://linux-hardware.org/?probe=e05fc7beed) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [26be42ecb8](https://linux-hardware.org/?probe=26be42ecb8) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [6ba5aae544](https://linux-hardware.org/?probe=6ba5aae544) | Jun 07, 2023 |
| Gigabyte      | Z390 UD                     | [1bf88bda62](https://linux-hardware.org/?probe=1bf88bda62) | Jun 06, 2023 |
| ASUSTek       | PRIME B365M-A               | [c33a9e5ccb](https://linux-hardware.org/?probe=c33a9e5ccb) | Jun 06, 2023 |
| ASRock        | X370 Gaming X               | [558e181232](https://linux-hardware.org/?probe=558e181232) | Jun 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [fa3bffbe76](https://linux-hardware.org/?probe=fa3bffbe76) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0b48c563e5](https://linux-hardware.org/?probe=0b48c563e5) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6f1c2a6a61](https://linux-hardware.org/?probe=6f1c2a6a61) | Jun 05, 2023 |
| Gigabyte      | G31M-ES2L                   | [6f15ff21e4](https://linux-hardware.org/?probe=6f15ff21e4) | Jun 05, 2023 |
| Dell          | 0VD5HY A07                  | [4e11e5ab66](https://linux-hardware.org/?probe=4e11e5ab66) | Jun 05, 2023 |
| Gigabyte      | Z390 UD                     | [b66cbe20f8](https://linux-hardware.org/?probe=b66cbe20f8) | Jun 01, 2023 |
| Gigabyte      | Z390 UD                     | [3cca879110](https://linux-hardware.org/?probe=3cca879110) | Jun 01, 2023 |
| ASUSTek       | PRIME B365M-A               | [0005e56720](https://linux-hardware.org/?probe=0005e56720) | May 31, 2023 |
| Gigabyte      | H61M-S1                     | [5d33af1d5a](https://linux-hardware.org/?probe=5d33af1d5a) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | [6872b07bb6](https://linux-hardware.org/?probe=6872b07bb6) | May 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [03d2cac76c](https://linux-hardware.org/?probe=03d2cac76c) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [54d3fad8f3](https://linux-hardware.org/?probe=54d3fad8f3) | May 29, 2023 |
| HP            | 8265                        | [a554e3bddf](https://linux-hardware.org/?probe=a554e3bddf) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | [e681025f33](https://linux-hardware.org/?probe=e681025f33) | May 29, 2023 |
| HP            | 8265                        | [66f0a2d631](https://linux-hardware.org/?probe=66f0a2d631) | May 29, 2023 |
| Gigabyte      | H81M-S2H                    | [68ec8b84a1](https://linux-hardware.org/?probe=68ec8b84a1) | May 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [8c6f8829e2](https://linux-hardware.org/?probe=8c6f8829e2) | May 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [035161324d](https://linux-hardware.org/?probe=035161324d) | May 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8656657a77](https://linux-hardware.org/?probe=8656657a77) | May 28, 2023 |
| Dell          | 0D883F A06                  | [82fa1dfa46](https://linux-hardware.org/?probe=82fa1dfa46) | May 28, 2023 |
| Dell          | 0D883F A06                  | [c301857917](https://linux-hardware.org/?probe=c301857917) | May 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [1718d8d65e](https://linux-hardware.org/?probe=1718d8d65e) | May 28, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [7d4df58daf](https://linux-hardware.org/?probe=7d4df58daf) | May 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [0aac24410d](https://linux-hardware.org/?probe=0aac24410d) | May 27, 2023 |
| HP            | 8265                        | [33488b045e](https://linux-hardware.org/?probe=33488b045e) | May 26, 2023 |
| Dell          | 0WMJ54 A01                  | [d26d09ef64](https://linux-hardware.org/?probe=d26d09ef64) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [512abef14b](https://linux-hardware.org/?probe=512abef14b) | May 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d93a5e7c70](https://linux-hardware.org/?probe=d93a5e7c70) | May 25, 2023 |
| ASRock        | G41M-VS3                    | [575d3814e9](https://linux-hardware.org/?probe=575d3814e9) | May 25, 2023 |
| ASRock        | G41M-VS3                    | [d7d112d2f0](https://linux-hardware.org/?probe=d7d112d2f0) | May 25, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [8fd8cdb823](https://linux-hardware.org/?probe=8fd8cdb823) | May 24, 2023 |
| ASRock        | E350M1                      | [d366f5f318](https://linux-hardware.org/?probe=d366f5f318) | May 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5837575ac6](https://linux-hardware.org/?probe=5837575ac6) | May 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dc47e13a60](https://linux-hardware.org/?probe=dc47e13a60) | May 23, 2023 |
| ASRock        | E350M1                      | [1debe3dcdf](https://linux-hardware.org/?probe=1debe3dcdf) | May 23, 2023 |
| Gigabyte      | G31M-ES2L                   | [5798ed934b](https://linux-hardware.org/?probe=5798ed934b) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | [9320baf9c8](https://linux-hardware.org/?probe=9320baf9c8) | May 22, 2023 |
| Medion        | MS-7748                     | [84765690f5](https://linux-hardware.org/?probe=84765690f5) | May 22, 2023 |
| Gigabyte      | B450M GAMING                | [88ffb8b020](https://linux-hardware.org/?probe=88ffb8b020) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | [5f83edfb1e](https://linux-hardware.org/?probe=5f83edfb1e) | May 22, 2023 |
| HP            | 8265                        | [5ce02f4648](https://linux-hardware.org/?probe=5ce02f4648) | May 22, 2023 |
| Gigabyte      | G31M-ES2L                   | [c0330d366f](https://linux-hardware.org/?probe=c0330d366f) | May 21, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [2ab72e28d7](https://linux-hardware.org/?probe=2ab72e28d7) | May 21, 2023 |
| Medion        | MS-7748                     | [dc5431a93b](https://linux-hardware.org/?probe=dc5431a93b) | May 21, 2023 |
| MSI           | MS-7309                     | [0b5d330939](https://linux-hardware.org/?probe=0b5d330939) | May 21, 2023 |
| Medion        | MS-7748                     | [d2fa9ef11a](https://linux-hardware.org/?probe=d2fa9ef11a) | May 21, 2023 |
| ASUSTek       | H110M-K                     | [74122892bc](https://linux-hardware.org/?probe=74122892bc) | May 21, 2023 |
| ASUSTek       | H110M-A/M.2                 | [3f97487981](https://linux-hardware.org/?probe=3f97487981) | May 21, 2023 |
| ASUSTek       | H110M-K                     | [4e4024bced](https://linux-hardware.org/?probe=4e4024bced) | May 21, 2023 |
| Gigabyte      | G31M-ES2L                   | [562bec5076](https://linux-hardware.org/?probe=562bec5076) | May 20, 2023 |
| Gigabyte      | M61SME-S2                   | [1d729ae4ea](https://linux-hardware.org/?probe=1d729ae4ea) | May 19, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [c791e54f97](https://linux-hardware.org/?probe=c791e54f97) | May 19, 2023 |
| Lenovo        | SDK0E50510 WIN              | [edbc15eb75](https://linux-hardware.org/?probe=edbc15eb75) | May 18, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4587e40310](https://linux-hardware.org/?probe=4587e40310) | May 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | [75c2a22eb5](https://linux-hardware.org/?probe=75c2a22eb5) | May 18, 2023 |
| Gigabyte      | M61SME-S2                   | [b3b39b07a5](https://linux-hardware.org/?probe=b3b39b07a5) | May 18, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [a7f0d5509c](https://linux-hardware.org/?probe=a7f0d5509c) | May 17, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [30c42f6f19](https://linux-hardware.org/?probe=30c42f6f19) | May 17, 2023 |
| Dell          | 0GY6Y8 A01                  | [6b606c0c57](https://linux-hardware.org/?probe=6b606c0c57) | May 16, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [f9672e78a2](https://linux-hardware.org/?probe=f9672e78a2) | May 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e2878f2250](https://linux-hardware.org/?probe=e2878f2250) | May 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f977ce9be3](https://linux-hardware.org/?probe=f977ce9be3) | May 15, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [d3bc261952](https://linux-hardware.org/?probe=d3bc261952) | May 15, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [8661cb20d2](https://linux-hardware.org/?probe=8661cb20d2) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ba63571489](https://linux-hardware.org/?probe=ba63571489) | May 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [d72abd1f09](https://linux-hardware.org/?probe=d72abd1f09) | May 14, 2023 |
| Gigabyte      | B450M GAMING                | [60ac4f3964](https://linux-hardware.org/?probe=60ac4f3964) | May 13, 2023 |
| Gigabyte      | B450M GAMING                | [1e8aca1c49](https://linux-hardware.org/?probe=1e8aca1c49) | May 13, 2023 |
| HP            | 8055                        | [7f692f60e6](https://linux-hardware.org/?probe=7f692f60e6) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | [024b4d4f97](https://linux-hardware.org/?probe=024b4d4f97) | May 12, 2023 |
| Acer          | Aspire TC-605               | [f9ccb88980](https://linux-hardware.org/?probe=f9ccb88980) | May 12, 2023 |
| Medion        | MS-7748                     | [c5b24a357f](https://linux-hardware.org/?probe=c5b24a357f) | May 12, 2023 |
| Dell          | 0D883F A06                  | [e69c9bb60f](https://linux-hardware.org/?probe=e69c9bb60f) | May 11, 2023 |
| Dell          | 0D883F A06                  | [17cf022069](https://linux-hardware.org/?probe=17cf022069) | May 11, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | [56d9faa756](https://linux-hardware.org/?probe=56d9faa756) | May 10, 2023 |
| Acer          | Aspire TC-605               | [d4846b3b14](https://linux-hardware.org/?probe=d4846b3b14) | May 10, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [78b60f4ad9](https://linux-hardware.org/?probe=78b60f4ad9) | May 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/BlackPanther/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| BlackPanther 18.1 | 1367     | 91.81%  |
| BlackPanther 16.2 | 79       | 5.31%   |
| BlackPanther 22.1 | 41       | 2.75%   |
| BlackPanther 16.1 | 2        | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| BlackPanther | 1457     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 4.18.16-desktop-1bP     | 1005     | 60.25%  |
| 5.6.14-desktop-2bP      | 401      | 24.04%  |
| 5.15.85-desktop-1bP     | 79       | 4.74%   |
| 4.9.20-desktop-pae-1bP  | 69       | 4.14%   |
| 5.1.15-desktop-1bP      | 40       | 2.4%    |
| 6.3.8-desktop-1bP       | 23       | 1.38%   |
| 6.3.3-desktop-1bP       | 14       | 0.84%   |
| 6.4.3-desktop-1bP       | 6        | 0.36%   |
| 4.7.0-desktop-1bP       | 6        | 0.36%   |
| 6.2.9-desktop-1bP       | 4        | 0.24%   |
| 6.7.0-power-2bP         | 3        | 0.18%   |
| 4.9.20-desktop-1bP      | 3        | 0.18%   |
| 6.7.2-tkg-pds           | 2        | 0.12%   |
| 6.7.0-rc4-tkg-eevdf     | 2        | 0.12%   |
| 6.5.7-power-1bP         | 2        | 0.12%   |
| 6.8.9-power-1bP         | 1        | 0.06%   |
| 6.7.3_tkg_eevdf         | 1        | 0.06%   |
| 6.1.0-1bP               | 1        | 0.06%   |
| 5.6.14-server-2bP       | 1        | 0.06%   |
| 5.15.83-1-lts           | 1        | 0.06%   |
| 5.1.15-server-1bP       | 1        | 0.06%   |
| 4.19.0-6-amd64          | 1        | 0.06%   |
| 4.14.14-desktop-pae-1bP | 1        | 0.06%   |
| 3.13.0-35-generic       | 1        | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.16 | 1005     | 60.25%  |
| 5.6.14  | 402      | 24.1%   |
| 5.15.85 | 79       | 4.74%   |
| 4.9.20  | 72       | 4.32%   |
| 5.1.15  | 41       | 2.46%   |
| 6.3.8   | 23       | 1.38%   |
| 6.3.3   | 14       | 0.84%   |
| 6.4.3   | 6        | 0.36%   |
| 4.7.0   | 6        | 0.36%   |
| 6.7.0   | 5        | 0.3%    |
| 6.2.9   | 4        | 0.24%   |
| 6.7.2   | 2        | 0.12%   |
| 6.5.7   | 2        | 0.12%   |
| 6.8.9   | 1        | 0.06%   |
| 6.7.3   | 1        | 0.06%   |
| 6.1.0   | 1        | 0.06%   |
| 5.15.83 | 1        | 0.06%   |
| 4.19.0  | 1        | 0.06%   |
| 4.14.14 | 1        | 0.06%   |
| 3.13.0  | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 1005     | 60.4%   |
| 5.6     | 402      | 24.16%  |
| 5.15    | 80       | 4.81%   |
| 4.9     | 72       | 4.33%   |
| 5.1     | 41       | 2.46%   |
| 6.3     | 34       | 2.04%   |
| 6.7     | 7        | 0.42%   |
| 6.4     | 6        | 0.36%   |
| 4.7     | 6        | 0.36%   |
| 6.2     | 4        | 0.24%   |
| 6.5     | 2        | 0.12%   |
| 6.8     | 1        | 0.06%   |
| 6.1     | 1        | 0.06%   |
| 4.19    | 1        | 0.06%   |
| 4.14    | 1        | 0.06%   |
| 3.13    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1401     | 94.66%  |
| i686   | 78       | 5.27%   |
| unknow | 1        | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 1416     | 96.92%  |
| Unknown | 44       | 3.01%   |
| KDE     | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1449     | 99.04%  |
| Wayland | 14       | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 1455     | 99.66%  |
| Unknown | 5        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1456     | 99.79%  |
| hu_HU   | 2        | 0.14%   |
| en_AU   | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1111     | 72.57%  |
| EFI  | 420      | 27.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 1040     | 62.13%  |
| Ext4    | 613      | 36.62%  |
| Btrfs   | 9        | 0.54%   |
| Unknown | 5        | 0.3%    |
| Ext3    | 4        | 0.24%   |
| Ext2    | 2        | 0.12%   |
| Ntfs    | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 994      | 64.05%  |
| GPT     | 537      | 34.6%   |
| Unknown | 21       | 1.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 962      | 58.69%  |
| Yes       | 677      | 41.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 883      | 55.08%  |
| No        | 720      | 44.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Gigabyte Technology            | 270      | 18.53%  |
| ASUSTek Computer               | 263      | 18.05%  |
| ASRock                         | 215      | 14.76%  |
| Dell                           | 166      | 11.39%  |
| Hewlett-Packard                | 143      | 9.81%   |
| MSI                            | 98       | 6.73%   |
| Lenovo                         | 79       | 5.42%   |
| Fujitsu                        | 44       | 3.02%   |
| Acer                           | 26       | 1.78%   |
| Fujitsu Siemens                | 23       | 1.58%   |
| Intel                          | 21       | 1.44%   |
| Foxconn                        | 17       | 1.17%   |
| Pegatron                       | 11       | 0.75%   |
| Medion                         | 11       | 0.75%   |
| Unknown                        | 10       | 0.69%   |
| Biostar                        | 7        | 0.48%   |
| Huanan                         | 5        | 0.34%   |
| Gateway                        | 5        | 0.34%   |
| ECS                            | 5        | 0.34%   |
| Shuttle                        | 3        | 0.21%   |
| Sapphire                       | 3        | 0.21%   |
| Packard Bell                   | 3        | 0.21%   |
| ABIT                           | 3        | 0.21%   |
| Supermicro                     | 2        | 0.14%   |
| Nvidia                         | 2        | 0.14%   |
| AMD                            | 2        | 0.14%   |
| ZOTAC                          | 1        | 0.07%   |
| Wincor Nixdorf                 | 1        | 0.07%   |
| ViewSonic                      | 1        | 0.07%   |
| TYAN Computer                  | 1        | 0.07%   |
| Shanghai Zhaoxin Semiconductor | 1        | 0.07%   |
| Qbex                           | 1        | 0.07%   |
| PCSMART                        | 1        | 0.07%   |
| NEC Computers                  | 1        | 0.07%   |
| MouseComputer                  | 1        | 0.07%   |
| Login Informatica              | 1        | 0.07%   |
| Lex                            | 1        | 0.07%   |
| Itautec                        | 1        | 0.07%   |
| IBM                            | 1        | 0.07%   |
| GIADA                          | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASRock FM2A75M Pro4+               | 32       | 2.2%    |
| ASUS All Series                    | 26       | 1.78%   |
| Dell OptiPlex 3020                 | 18       | 1.24%   |
| Dell OptiPlex 780                  | 14       | 0.96%   |
| Dell OptiPlex 760                  | 13       | 0.89%   |
| Dell OptiPlex 755                  | 13       | 0.89%   |
| Unknown                            | 13       | 0.89%   |
| Gigabyte H61M-S1                   | 11       | 0.75%   |
| Gigabyte G31M-ES2L                 | 11       | 0.75%   |
| ASUS P5KPL-AM EPU                  | 10       | 0.69%   |
| Dell OptiPlex 745                  | 9        | 0.62%   |
| HP ProDesk 600 G2 SFF              | 8        | 0.55%   |
| Dell OptiPlex 7010                 | 8        | 0.55%   |
| ASRock G41M-VS3                    | 8        | 0.55%   |
| MSI MS-7817                        | 7        | 0.48%   |
| MSI MS-7680                        | 7        | 0.48%   |
| Lenovo ThinkStation D20 4158AF8    | 7        | 0.48%   |
| HP Compaq dc5800 Small Form Factor | 7        | 0.48%   |
| Gigabyte 970A-DS3P                 | 7        | 0.48%   |
| MSI MS-7592                        | 6        | 0.41%   |
| HP Compaq 8000 Elite SFF PC        | 6        | 0.41%   |
| Gigabyte Z390 UD                   | 6        | 0.41%   |
| HP EliteDesk 705 G3 SFF            | 5        | 0.34%   |
| HP Compaq Pro 6300 SFF             | 5        | 0.34%   |
| HP Compaq Pro 6300 MT              | 5        | 0.34%   |
| HP Compaq dc5850 Small Form Factor | 5        | 0.34%   |
| HP Compaq 6005 Pro SFF PC          | 5        | 0.34%   |
| Gigabyte G31M-ES2C                 | 5        | 0.34%   |
| Foxconn Pro 3500 Series            | 5        | 0.34%   |
| Dell Precision WorkStation T3500   | 5        | 0.34%   |
| Dell OptiPlex 9020                 | 5        | 0.34%   |
| Dell OptiPlex 790                  | 5        | 0.34%   |
| Dell OptiPlex 740 Enhanced         | 5        | 0.34%   |
| Dell OptiPlex 390                  | 5        | 0.34%   |
| Dell OptiPlex 330                  | 5        | 0.34%   |
| ASUS P5KPL-AM SE                   | 5        | 0.34%   |
| ASRock N68C-S UCC                  | 5        | 0.34%   |
| ASRock G31M-S                      | 5        | 0.34%   |
| ASRock 970 Pro3 R2.0               | 5        | 0.34%   |
| MSI MS-7C91                        | 4        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 138      | 9.47%   |
| HP Compaq               | 99       | 6.79%   |
| Lenovo ThinkCentre      | 50       | 3.43%   |
| ASUS PRIME              | 39       | 2.68%   |
| Fujitsu ESPRIMO         | 33       | 2.26%   |
| ASRock FM2A75M          | 32       | 2.2%    |
| ASUS All                | 26       | 1.78%   |
| Fujitsu Siemens ESPRIMO | 16       | 1.1%    |
| ASUS P5KPL-AM           | 16       | 1.1%    |
| HP ProDesk              | 15       | 1.03%   |
| Lenovo ThinkStation     | 14       | 0.96%   |
| Unknown                 | 13       | 0.89%   |
| ASUS ROG                | 12       | 0.82%   |
| Acer Veriton            | 12       | 0.82%   |
| Gigabyte H61M-S1        | 11       | 0.75%   |
| Gigabyte G31M-ES2L      | 11       | 0.75%   |
| Dell Precision          | 11       | 0.75%   |
| HP EliteDesk            | 10       | 0.69%   |
| ASUS M5A97              | 9        | 0.62%   |
| Acer Aspire             | 9        | 0.62%   |
| Gigabyte B450           | 8        | 0.55%   |
| ASUS M5A78L-M           | 8        | 0.55%   |
| ASRock G41M-VS3         | 8        | 0.55%   |
| ASRock 970              | 8        | 0.55%   |
| MSI MS-7817             | 7        | 0.48%   |
| MSI MS-7680             | 7        | 0.48%   |
| Gigabyte Z390           | 7        | 0.48%   |
| Gigabyte 970A-DS3P      | 7        | 0.48%   |
| Fujitsu CELSIUS         | 7        | 0.48%   |
| MSI MS-7592             | 6        | 0.41%   |
| Foxconn Pro             | 6        | 0.41%   |
| Dell Vostro             | 6        | 0.41%   |
| ASUS H110M-A            | 6        | 0.41%   |
| ASRock N68C-S           | 6        | 0.41%   |
| Huanan X99-QD4          | 5        | 0.34%   |
| Gigabyte X570           | 5        | 0.34%   |
| Gigabyte H310M          | 5        | 0.34%   |
| Gigabyte GA-78LMT-USB3  | 5        | 0.34%   |
| Gigabyte G31M-ES2C      | 5        | 0.34%   |
| Gigabyte B450M          | 5        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 148      | 10.16%  |
| 2012 | 148      | 10.16%  |
| 2009 | 148      | 10.16%  |
| 2010 | 133      | 9.13%   |
| 2014 | 131      | 8.99%   |
| 2008 | 130      | 8.92%   |
| 2011 | 127      | 8.72%   |
| 2007 | 109      | 7.48%   |
| 2018 | 83       | 5.7%    |
| 2015 | 66       | 4.53%   |
| 2016 | 47       | 3.23%   |
| 2017 | 46       | 3.16%   |
| 2006 | 42       | 2.88%   |
| 2019 | 37       | 2.54%   |
| 2020 | 23       | 1.58%   |
| 2005 | 15       | 1.03%   |
| 2021 | 13       | 0.89%   |
| 2004 | 4        | 0.27%   |
| 2022 | 3        | 0.21%   |
| 2024 | 2        | 0.14%   |
| 2023 | 1        | 0.07%   |
| 2003 | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1457     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1457     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1457     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 446      | 29.23%  |
| 8.01-16.0   | 396      | 25.95%  |
| 4.01-8.0    | 239      | 15.66%  |
| 16.01-24.0  | 194      | 12.71%  |
| 1.01-2.0    | 130      | 8.52%   |
| 32.01-64.0  | 56       | 3.67%   |
| 2.01-3.0    | 30       | 1.97%   |
| 24.01-32.0  | 19       | 1.25%   |
| 0.51-1.0    | 12       | 0.79%   |
| 64.01-256.0 | 4        | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 700      | 39.24%  |
| 0.51-1.0  | 651      | 36.49%  |
| 1.01-2.0  | 332      | 18.61%  |
| 2.01-3.0  | 74       | 4.15%   |
| 3.01-4.0  | 16       | 0.9%    |
| 4.01-8.0  | 9        | 0.5%    |
| 8.01-16.0 | 1        | 0.06%   |
| Unknown   | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 859      | 52.73%  |
| 2      | 417      | 25.6%   |
| 3      | 188      | 11.54%  |
| 4      | 74       | 4.54%   |
| 5      | 38       | 2.33%   |
| 0      | 34       | 2.09%   |
| 6      | 10       | 0.61%   |
| 9      | 3        | 0.18%   |
| 10     | 2        | 0.12%   |
| 8      | 2        | 0.12%   |
| 7      | 2        | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 985      | 64.76%  |
| No        | 536      | 35.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1446     | 99.25%  |
| No        | 11       | 0.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1104     | 73.65%  |
| Yes       | 395      | 26.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1287     | 86.09%  |
| Yes       | 208      | 13.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Hungary      | 1071     | 73.36%  |
| Germany      | 62       | 4.25%   |
| USA          | 58       | 3.97%   |
| Romania      | 33       | 2.26%   |
| Slovakia     | 18       | 1.23%   |
| UK           | 17       | 1.16%   |
| France       | 16       | 1.1%    |
| Brazil       | 16       | 1.1%    |
| Italy        | 15       | 1.03%   |
| Spain        | 12       | 0.82%   |
| Canada       | 12       | 0.82%   |
| Poland       | 11       | 0.75%   |
| Serbia       | 10       | 0.68%   |
| Australia    | 10       | 0.68%   |
| Philippines  | 8        | 0.55%   |
| Japan        | 7        | 0.48%   |
| South Africa | 6        | 0.41%   |
| Ukraine      | 5        | 0.34%   |
| Austria      | 5        | 0.34%   |
| Argentina    | 5        | 0.34%   |
| India        | 4        | 0.27%   |
| Greece       | 4        | 0.27%   |
| Netherlands  | 3        | 0.21%   |
| Ireland      | 3        | 0.21%   |
| Finland      | 3        | 0.21%   |
| Egypt        | 3        | 0.21%   |
| Belgium      | 3        | 0.21%   |
| Uruguay      | 2        | 0.14%   |
| Turkey       | 2        | 0.14%   |
| Switzerland  | 2        | 0.14%   |
| Russia       | 2        | 0.14%   |
| Morocco      | 2        | 0.14%   |
| Kuwait       | 2        | 0.14%   |
| Colombia     | 2        | 0.14%   |
| Belarus      | 2        | 0.14%   |
| Thailand     | 1        | 0.07%   |
| Tanzania     | 1        | 0.07%   |
| Taiwan       | 1        | 0.07%   |
| South Korea  | 1        | 0.07%   |
| Slovenia     | 1        | 0.07%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Budapest                | 347      | 19.62%  |
| Győr                   | 31       | 1.75%   |
| Zalaegerszeg            | 25       | 1.41%   |
| Pécs                   | 25       | 1.41%   |
| Szeged                  | 23       | 1.3%    |
| Miskolc                 | 23       | 1.3%    |
| Karcag                  | 22       | 1.24%   |
| Debrecen                | 22       | 1.24%   |
| Eger                    | 18       | 1.02%   |
| Szombathely             | 16       | 0.9%    |
| Oroshaza                | 16       | 0.9%    |
| Kecskemét              | 15       | 0.85%   |
| Berettyóújfalu        | 14       | 0.79%   |
| Tatabánya              | 13       | 0.73%   |
| Gödöllő              | 13       | 0.73%   |
| Toeroekbalint           | 12       | 0.68%   |
| Szekszárd              | 12       | 0.68%   |
| Székesfehérvár       | 11       | 0.62%   |
| Nyiregyhaza             | 11       | 0.62%   |
| Szolnok                 | 10       | 0.57%   |
| Szigetszentmiklos       | 10       | 0.57%   |
| Papa                    | 10       | 0.57%   |
| Tiszafured              | 9        | 0.51%   |
| Szentendre              | 9        | 0.51%   |
| Nagykanizsa             | 9        | 0.51%   |
| Hajduboszormeny         | 9        | 0.51%   |
| Mosonmagyaróvár       | 8        | 0.45%   |
| Esztergom               | 8        | 0.45%   |
| Bucharest               | 8        | 0.45%   |
| Veresegyhaz             | 7        | 0.4%    |
| Pfaffenhofen an der Ilm | 7        | 0.4%    |
| Érd                    | 7        | 0.4%    |
| Dunaharaszti            | 7        | 0.4%    |
| Ajka                    | 7        | 0.4%    |
| Zalău                  | 6        | 0.34%   |
| Sarbogard               | 6        | 0.34%   |
| Nagyatad                | 6        | 0.34%   |
| Mohács                 | 6        | 0.34%   |
| Hodmezovasarhely        | 6        | 0.34%   |
| Hatvan                  | 6        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 535      | 1135   | 21.49%  |
| Seagate                     | 419      | 667    | 16.83%  |
| Samsung Electronics         | 353      | 734    | 14.18%  |
| Kingston                    | 274      | 594    | 11%     |
| Toshiba                     | 161      | 345    | 6.47%   |
| Hitachi                     | 120      | 188    | 4.82%   |
| A-DATA Technology           | 77       | 147    | 3.09%   |
| Maxtor                      | 57       | 73     | 2.29%   |
| SanDisk                     | 55       | 104    | 2.21%   |
| Crucial                     | 44       | 78     | 1.77%   |
| SPCC                        | 32       | 47     | 1.29%   |
| HGST                        | 29       | 82     | 1.16%   |
| Intenso                     | 25       | 48     | 1%      |
| Intel                       | 24       | 43     | 0.96%   |
| Fujitsu                     | 19       | 19     | 0.76%   |
| Patriot                     | 16       | 52     | 0.64%   |
| OCZ                         | 14       | 19     | 0.56%   |
| Gigabyte Technology         | 14       | 49     | 0.56%   |
| Apacer                      | 14       | 22     | 0.56%   |
| PNY                         | 13       | 22     | 0.52%   |
| JMicron Technology          | 13       | 16     | 0.52%   |
| China                       | 12       | 19     | 0.48%   |
| Kingmax                     | 10       | 31     | 0.4%    |
| Hewlett-Packard             | 10       | 16     | 0.4%    |
| XPG                         | 9        | 16     | 0.36%   |
| SK hynix                    | 9        | 14     | 0.36%   |
| Micron Technology           | 8        | 15     | 0.32%   |
| Unknown                     | 7        | 22     | 0.28%   |
| Corsair                     | 7        | 9      | 0.28%   |
| Zheino                      | 6        | 22     | 0.24%   |
| KingSpec                    | 6        | 8      | 0.24%   |
| WD MediaMax                 | 5        | 6      | 0.2%    |
| Team                        | 5        | 7      | 0.2%    |
| Netac                       | 5        | 12     | 0.2%    |
| ASMT                        | 5        | 7      | 0.2%    |
| Verbatim                    | 4        | 8      | 0.16%   |
| USB3.0                      | 4        | 5      | 0.16%   |
| Transcend                   | 4        | 10     | 0.16%   |
| LITEON                      | 4        | 4      | 0.16%   |
| Kingston Technology Company | 4        | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD    | 62       | 2.18%   |
| Seagate ST500DM002-1BD142 500GB    | 58       | 2.04%   |
| Kingston SA400S37240G 240GB SSD    | 53       | 1.86%   |
| Toshiba DT01ACA100 1TB             | 47       | 1.65%   |
| Kingston SV300S37A120G 120GB SSD   | 46       | 1.62%   |
| Toshiba DT01ACA050 500GB           | 31       | 1.09%   |
| A-DATA SU630 240GB SSD             | 30       | 1.06%   |
| Seagate ST380815AS 80GB            | 23       | 0.81%   |
| Kingston SA400S37480G 480GB SSD    | 23       | 0.81%   |
| Kingston SUV400S37120G 120GB SSD   | 20       | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB           | 19       | 0.67%   |
| Samsung HD502HJ 500GB              | 19       | 0.67%   |
| A-DATA SU700 120GB SSD             | 18       | 0.63%   |
| Seagate ST3160815AS 160GB          | 17       | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 17       | 0.6%    |
| Samsung HD103UJ 1TB                | 16       | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB     | 15       | 0.53%   |
| Toshiba HDWD110 1TB                | 14       | 0.49%   |
| Seagate ST3250318AS 250GB          | 14       | 0.49%   |
| Samsung SSD 850 EVO 250GB          | 14       | 0.49%   |
| WDC WD5000AAKX-001CA0 500GB        | 13       | 0.46%   |
| Toshiba DT01ACA200 2TB             | 13       | 0.46%   |
| SPCC Solid State Disk 256GB        | 13       | 0.46%   |
| Seagate ST3160318AS 160GB          | 13       | 0.46%   |
| JMicron Generic 320GB              | 13       | 0.46%   |
| Seagate ST3500418AS 500GB          | 12       | 0.42%   |
| Samsung SSD 860 EVO 250GB          | 12       | 0.42%   |
| Samsung HD322HJ 320GB              | 12       | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 11       | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11       | 0.39%   |
| Samsung HD161HJ 160GB              | 11       | 0.39%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 10       | 0.35%   |
| WDC WD5000AAKS-007AA0 500GB        | 10       | 0.35%   |
| Seagate ST250DM000-1BD141 250GB    | 10       | 0.35%   |
| Samsung HD502IJ 500GB              | 10       | 0.35%   |
| Samsung HD082GJ 80GB               | 10       | 0.35%   |
| Kingston SV300S37A60G 64GB SSD     | 10       | 0.35%   |
| Kingston SV300S37A240G 240GB SSD   | 10       | 0.35%   |
| Hitachi HDS721050CLA662 500GB      | 10       | 0.35%   |
| Hitachi HDS721050CLA360 500GB      | 10       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 502      | 1036   | 32.39%  |
| Seagate             | 416      | 662    | 26.84%  |
| Samsung Electronics | 206      | 350    | 13.29%  |
| Toshiba             | 155      | 339    | 10%     |
| Hitachi             | 120      | 188    | 7.74%   |
| Maxtor              | 56       | 72     | 3.61%   |
| HGST                | 29       | 82     | 1.87%   |
| Fujitsu             | 19       | 19     | 1.23%   |
| JMicron Technology  | 13       | 16     | 0.84%   |
| Hewlett-Packard     | 6        | 8      | 0.39%   |
| WD MediaMax         | 5        | 6      | 0.32%   |
| ASMT                | 4        | 6      | 0.26%   |
| USB3.0              | 3        | 4      | 0.19%   |
| Unknown             | 3        | 4      | 0.19%   |
| Apple               | 3        | 3      | 0.19%   |
| Quantum             | 2        | 2      | 0.13%   |
| ExcelStor           | 2        | 2      | 0.13%   |
| USB                 | 1        | 2      | 0.06%   |
| ICY BOX             | 1        | 3      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Emphase             | 1        | 2      | 0.06%   |
| Unknown             | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 252      | 530    | 30.58%  |
| Samsung Electronics | 126      | 276    | 15.29%  |
| A-DATA Technology   | 70       | 134    | 8.5%    |
| SanDisk             | 51       | 93     | 6.19%   |
| WDC                 | 39       | 84     | 4.73%   |
| Crucial             | 37       | 67     | 4.49%   |
| SPCC                | 27       | 41     | 3.28%   |
| Intenso             | 25       | 48     | 3.03%   |
| Intel               | 17       | 28     | 2.06%   |
| Patriot             | 15       | 51     | 1.82%   |
| OCZ                 | 14       | 19     | 1.7%    |
| Apacer              | 14       | 22     | 1.7%    |
| PNY                 | 13       | 22     | 1.58%   |
| China               | 12       | 19     | 1.46%   |
| Gigabyte Technology | 11       | 42     | 1.33%   |
| Kingmax             | 9        | 30     | 1.09%   |
| SK hynix            | 7        | 12     | 0.85%   |
| Micron Technology   | 7        | 14     | 0.85%   |
| Corsair             | 7        | 9      | 0.85%   |
| Toshiba             | 6        | 6      | 0.73%   |
| KingSpec            | 6        | 8      | 0.73%   |
| Team                | 5        | 7      | 0.61%   |
| Netac               | 5        | 12     | 0.61%   |
| Verbatim            | 4        | 8      | 0.49%   |
| LITEON              | 4        | 4      | 0.49%   |
| GOODRAM             | 4        | 4      | 0.49%   |
| Transcend           | 3        | 5      | 0.36%   |
| Emtec               | 3        | 3      | 0.36%   |
| StoreJet            | 2        | 2      | 0.24%   |
| sobetter            | 2        | 2      | 0.24%   |
| KingFast            | 2        | 3      | 0.24%   |
| Integral            | 2        | 3      | 0.24%   |
| Hewlett-Packard     | 2        | 3      | 0.24%   |
| BIWIN               | 2        | 6      | 0.24%   |
| Vaseky              | 1        | 1      | 0.12%   |
| USB3.0              | 1        | 1      | 0.12%   |
| Unknown             | 1        | 2      | 0.12%   |
| Teclast             | 1        | 1      | 0.12%   |
| SMI                 | 1        | 1      | 0.12%   |
| Seagate             | 1        | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1168     | 2809   | 58.75%  |
| SSD     | 686      | 1641   | 34.51%  |
| NVMe    | 120      | 325    | 6.04%   |
| Unknown | 13       | 25     | 0.65%   |
| MMC     | 1        | 1      | 0.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1407     | 4322   | 87.39%  |
| NVMe | 120      | 325    | 7.45%   |
| SAS  | 82       | 153    | 5.09%   |
| MMC  | 1        | 1      | 0.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1270     | 3106   | 68.83%  |
| 0.51-1.0        | 390      | 885    | 21.14%  |
| 1.01-2.0        | 101      | 226    | 5.47%   |
| 3.01-4.0        | 35       | 87     | 1.9%    |
| 2.01-3.0        | 30       | 121    | 1.63%   |
| 4.01-10.0       | 12       | 17     | 0.65%   |
| More than 100.0 | 4        | 4      | 0.22%   |
| 10.01-20.0      | 3        | 4      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1027     | 57.54%  |
| 101-250        | 270      | 15.13%  |
| 251-500        | 163      | 9.13%   |
| 51-100         | 111      | 6.22%   |
| 501-1000       | 88       | 4.93%   |
| 21-50          | 60       | 3.36%   |
| 1001-2000      | 34       | 1.9%    |
| 1-20           | 19       | 1.06%   |
| More than 3000 | 12       | 0.67%   |
| 2001-3000      | 1        | 0.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1027     | 58.09%  |
| 1-20           | 508      | 28.73%  |
| 21-50          | 90       | 5.09%   |
| 51-100         | 52       | 2.94%   |
| 101-250        | 48       | 2.71%   |
| 501-1000       | 17       | 0.96%   |
| 251-500        | 14       | 0.79%   |
| 1001-2000      | 7        | 0.4%    |
| More than 3000 | 4        | 0.23%   |
| 2001-3000      | 1        | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 29       | 46     | 3.75%   |
| A-DATA Technology SU630 240GB SSD  | 19       | 33     | 2.45%   |
| Kingston SV300S37A120G 120GB SSD   | 15       | 17     | 1.94%   |
| Samsung Electronics HD103UJ 1TB    | 14       | 31     | 1.81%   |
| Toshiba DT01ACA050 500GB           | 11       | 14     | 1.42%   |
| WDC WD5000AAKX-001CA0 500GB        | 10       | 10     | 1.29%   |
| Toshiba DT01ACA100 1TB             | 10       | 20     | 1.29%   |
| Seagate ST500LT012-9WS142 500GB    | 8        | 9      | 1.03%   |
| WDC WD5000AAKS-007AA0 500GB        | 7        | 26     | 0.9%    |
| Seagate ST3500418AS 500GB          | 7        | 12     | 0.9%    |
| Seagate ST3160815AS 160GB          | 7        | 9      | 0.9%    |
| WDC WD5000AAKS-00UU3A0 500GB       | 6        | 13     | 0.78%   |
| WDC WD5000AADS-00S9B0 500GB        | 6        | 8      | 0.78%   |
| WDC WD10EARS-00Y5B1 1TB            | 6        | 15     | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6        | 8      | 0.78%   |
| Samsung Electronics SP2504C 250GB  | 6        | 10     | 0.78%   |
| Samsung Electronics HD321KJ 320GB  | 6        | 6      | 0.78%   |
| Samsung Electronics HD161HJ 160GB  | 6        | 6      | 0.78%   |
| Samsung Electronics HD103SI 1TB    | 6        | 6      | 0.78%   |
| Hitachi HDS721050CLA362 500GB      | 6        | 11     | 0.78%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 5        | 9      | 0.65%   |
| Seagate ST380815AS 80GB            | 5        | 8      | 0.65%   |
| Seagate ST3250318AS 250GB          | 5        | 8      | 0.65%   |
| Seagate ST3160812AS 160GB          | 5        | 5      | 0.65%   |
| Samsung Electronics HD080HJ 80GB   | 5        | 5      | 0.65%   |
| Hitachi HDP725050GLA360 500GB      | 5        | 5      | 0.65%   |
| WDC WD3200AAKS-00L9A0 320GB        | 4        | 6      | 0.52%   |
| WDC WD10PURZ-85U8XY0 1TB           | 4        | 12     | 0.52%   |
| Seagate ST3160318AS 160GB          | 4        | 4      | 0.52%   |
| Samsung Electronics SP2004C 200GB  | 4        | 6      | 0.52%   |
| Samsung Electronics HD642JJ 640GB  | 4        | 7      | 0.52%   |
| Samsung Electronics HD502HJ 500GB  | 4        | 7      | 0.52%   |
| Samsung Electronics HD501LJ 500GB  | 4        | 5      | 0.52%   |
| Samsung Electronics HD161GJ 160GB  | 4        | 5      | 0.52%   |
| Samsung Electronics HD082GJ 80GB   | 4        | 4      | 0.52%   |
| Maxtor 6Y080M0 82GB                | 4        | 5      | 0.52%   |
| Maxtor 6Y080L0 82GB                | 4        | 5      | 0.52%   |
| Maxtor 2B020H1 20GB                | 4        | 8      | 0.52%   |
| Kingston SUV400S37120G 120GB SSD   | 4        | 9      | 0.52%   |
| Hitachi HTS545050B9A300 500GB      | 4        | 6      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 200      | 359    | 27.55%  |
| Seagate             | 178      | 248    | 24.52%  |
| Samsung Electronics | 111      | 174    | 15.29%  |
| Hitachi             | 52       | 87     | 7.16%   |
| Toshiba             | 45       | 77     | 6.2%    |
| Maxtor              | 33       | 46     | 4.55%   |
| Kingston            | 31       | 47     | 4.27%   |
| A-DATA Technology   | 25       | 48     | 3.44%   |
| HGST                | 9        | 10     | 1.24%   |
| OCZ                 | 7        | 10     | 0.96%   |
| WD MediaMax         | 5        | 6      | 0.69%   |
| Intel               | 4        | 11     | 0.55%   |
| Fujitsu             | 4        | 4      | 0.55%   |
| Hewlett-Packard     | 3        | 3      | 0.41%   |
| SK hynix            | 2        | 5      | 0.28%   |
| SanDisk             | 2        | 2      | 0.28%   |
| KingSpec            | 2        | 2      | 0.28%   |
| SATAFIRM            | 1        | 1      | 0.14%   |
| QUANTUM             | 1        | 1      | 0.14%   |
| Patriot             | 1        | 1      | 0.14%   |
| LITEON              | 1        | 1      | 0.14%   |
| Kingmax             | 1        | 1      | 0.14%   |
| Intenso             | 1        | 1      | 0.14%   |
| IBM/Hitachi         | 1        | 1      | 0.14%   |
| ExcelStor           | 1        | 1      | 0.14%   |
| Crucial             | 1        | 1      | 0.14%   |
| Corsair             | 1        | 1      | 0.14%   |
| China               | 1        | 1      | 0.14%   |
| BIWIN               | 1        | 1      | 0.14%   |
| ASMT                | 1        | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 198      | 357    | 31.08%  |
| Seagate             | 178      | 248    | 27.94%  |
| Samsung Electronics | 108      | 164    | 16.95%  |
| Hitachi             | 52       | 87     | 8.16%   |
| Toshiba             | 44       | 76     | 6.91%   |
| Maxtor              | 33       | 46     | 5.18%   |
| HGST                | 9        | 10     | 1.41%   |
| WD MediaMax         | 5        | 6      | 0.78%   |
| Fujitsu             | 4        | 4      | 0.63%   |
| Hewlett-Packard     | 2        | 2      | 0.31%   |
| QUANTUM             | 1        | 1      | 0.16%   |
| IBM/Hitachi         | 1        | 1      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |
| ASMT                | 1        | 1      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 543      | 1004   | 86.19%  |
| SSD  | 84       | 145    | 13.33%  |
| NVMe | 3        | 3      | 0.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 2        | 3      | 12.5%   |
| Samsung Electronics HD103SJ 1TB   | 2        | 2      | 12.5%   |
| Zheino CHN-NGFFNV2280-256 256GB   | 1        | 1      | 6.25%   |
| WDC WD1600BEVT-80A23T0 160GB      | 1        | 1      | 6.25%   |
| Seagate ST9160412AS 160GB         | 1        | 1      | 6.25%   |
| Seagate ST380815AS 80GB           | 1        | 3      | 6.25%   |
| Seagate ST3160815AS 160GB         | 1        | 1      | 6.25%   |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 6.25%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 6.25%   |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 6.25%   |
| OCZ-AGIL ITY3 64GB SSD            | 1        | 1      | 6.25%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 6.25%   |
| ExcelStor Technology J8160S 160GB | 1        | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 43.75%  |
| Seagate             | 3        | 5      | 18.75%  |
| Zheino              | 1        | 1      | 6.25%   |
| WDC                 | 1        | 1      | 6.25%   |
| OCZ-AGIL            | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 1      | 6.25%   |
| ExcelStor           | 1        | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1162     | 3398   | 60.87%  |
| Malfunc  | 607      | 1152   | 31.8%   |
| Detected | 124      | 232    | 6.5%    |
| Failed   | 16       | 19     | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 989      | 56.19%  |
| AMD                              | 377      | 21.42%  |
| JMicron Technology               | 75       | 4.26%   |
| Nvidia                           | 72       | 4.09%   |
| Samsung Electronics              | 45       | 2.56%   |
| ASMedia Technology               | 38       | 2.16%   |
| Marvell Technology Group         | 33       | 1.88%   |
| Kingston Technology Company      | 30       | 1.7%    |
| VIA Technologies                 | 17       | 0.97%   |
| Silicon Motion                   | 12       | 0.68%   |
| Silicon Image                    | 11       | 0.63%   |
| Phison Electronics               | 11       | 0.63%   |
| SanDisk                          | 10       | 0.57%   |
| Realtek Semiconductor            | 9        | 0.51%   |
| Micron/Crucial Technology        | 6        | 0.34%   |
| ADATA Technology                 | 5        | 0.28%   |
| SK hynix                         | 2        | 0.11%   |
| Silicon Integrated Systems [SiS] | 2        | 0.11%   |
| LSI Logic / Symbios Logic        | 2        | 0.11%   |
| Integrated Technology Express    | 2        | 0.11%   |
| Adaptec                          | 2        | 0.11%   |
| 3ware                            | 2        | 0.11%   |
| Zhaoxin                          | 1        | 0.06%   |
| ULi Electronics                  | 1        | 0.06%   |
| Promise Technology               | 1        | 0.06%   |
| Micron Technology                | 1        | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.06%   |
| Lite-On Technology               | 1        | 0.06%   |
| Hewlett-Packard                  | 1        | 0.06%   |
| Broadcom / LSI                   | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 186      | 7.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 175      | 6.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 130      | 5.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 122      | 4.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 99       | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 84       | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 72       | 2.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 72       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 61       | 2.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 60       | 2.36%   |
| AMD FCH IDE Controller                                                                  | 60       | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 56       | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 56       | 2.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 55       | 2.16%   |
| Intel SATA Controller [RAID mode]                                                       | 51       | 2.01%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 51       | 2.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 50       | 1.97%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 43       | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 40       | 1.57%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 36       | 1.42%   |
| Nvidia MCP61 SATA Controller                                                            | 35       | 1.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 35       | 1.38%   |
| Nvidia MCP61 IDE                                                                        | 32       | 1.26%   |
| JMicron JMB368 IDE controller                                                           | 31       | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29       | 1.14%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 29       | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 26       | 1.02%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 25       | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 25       | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 25       | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 24       | 0.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 23       | 0.9%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 22       | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 21       | 0.83%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 21       | 0.83%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 19       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 17       | 0.67%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 16       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 16       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 950      | 50.77%  |
| IDE  | 721      | 38.54%  |
| NVMe | 120      | 6.41%   |
| RAID | 73       | 3.9%    |
| SCSI | 5        | 0.27%   |
| SAS  | 2        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1011     | 69.39%  |
| AMD          | 445      | 30.54%  |
| CentaurHauls | 1        | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 48       | 3.26%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 34       | 2.31%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 25       | 1.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 25       | 1.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 25       | 1.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24       | 1.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 23       | 1.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 22       | 1.49%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 22       | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 19       | 1.29%   |
| AMD FX-6300 Six-Core Processor                | 17       | 1.15%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 16       | 1.09%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 13       | 0.88%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 12       | 0.81%   |
| Intel Pentium 4 CPU 3.00GHz                   | 12       | 0.81%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 12       | 0.81%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 12       | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 11       | 0.75%   |
| AMD FX-8350 Eight-Core Processor              | 11       | 0.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 10       | 0.68%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 10       | 0.68%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 10       | 0.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 9        | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 9        | 0.61%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 9        | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9        | 0.61%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 9        | 0.61%   |
| AMD Athlon II X2 260 Processor                | 9        | 0.61%   |
| Intel Pentium CPU G840 @ 2.80GHz              | 8        | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 8        | 0.54%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 8        | 0.54%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 8        | 0.54%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 8        | 0.54%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 8        | 0.54%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 8        | 0.54%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 8        | 0.54%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8        | 0.54%   |
| AMD Phenom II X4 965 Processor                | 8        | 0.54%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 8        | 0.54%   |
| Intel Xeon CPU X5677 @ 3.47GHz                | 7        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 235      | 16.02%  |
| Intel Core i3           | 172      | 11.72%  |
| Intel Core 2 Duo        | 153      | 10.43%  |
| Intel Core i7           | 66       | 4.5%    |
| Intel Core 2 Quad       | 65       | 4.43%   |
| Intel Pentium           | 61       | 4.16%   |
| AMD A8                  | 57       | 3.89%   |
| Intel Pentium Dual-Core | 56       | 3.82%   |
| AMD FX                  | 54       | 3.68%   |
| Intel Xeon              | 53       | 3.61%   |
| Intel Celeron           | 52       | 3.54%   |
| AMD Ryzen 5             | 43       | 2.93%   |
| AMD Athlon II X2        | 40       | 2.73%   |
| AMD Athlon 64 X2        | 31       | 2.11%   |
| AMD Ryzen 7             | 24       | 1.64%   |
| AMD Phenom II X4        | 24       | 1.64%   |
| Intel Pentium 4         | 23       | 1.57%   |
| Intel Pentium Dual      | 22       | 1.5%    |
| AMD A4                  | 21       | 1.43%   |
| Intel Core 2            | 20       | 1.36%   |
| AMD Ryzen 3             | 19       | 1.3%    |
| AMD A10                 | 16       | 1.09%   |
| Other                   | 15       | 1.02%   |
| Intel Atom              | 15       | 1.02%   |
| Intel Pentium D         | 13       | 0.89%   |
| AMD Sempron             | 13       | 0.89%   |
| AMD Athlon II X4        | 13       | 0.89%   |
| AMD A6                  | 11       | 0.75%   |
| AMD Athlon Dual Core    | 9        | 0.61%   |
| AMD Athlon X4           | 8        | 0.55%   |
| AMD Athlon              | 8        | 0.55%   |
| AMD Athlon 64           | 7        | 0.48%   |
| AMD Phenom II X6        | 6        | 0.41%   |
| AMD Phenom II X2        | 4        | 0.27%   |
| AMD Phenom              | 4        | 0.27%   |
| Intel Pentium Gold      | 3        | 0.2%    |
| Intel Celeron D         | 3        | 0.2%    |
| AMD Turion II Neo       | 3        | 0.2%    |
| AMD Ryzen 9             | 3        | 0.2%    |
| AMD E                   | 3        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 735      | 49.83%  |
| 4       | 470      | 31.86%  |
| 1       | 102      | 6.92%   |
| 6       | 88       | 5.97%   |
| 8       | 41       | 2.78%   |
| 3       | 26       | 1.76%   |
| 18      | 5        | 0.34%   |
| 10      | 3        | 0.2%    |
| 16      | 2        | 0.14%   |
| 12      | 2        | 0.14%   |
| Unknown | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1445     | 99.04%  |
| 2      | 13       | 0.89%   |
| 4      | 1        | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 929      | 63.2%   |
| 2       | 540      | 36.73%  |
| Unknown | 1        | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1451     | 99.52%  |
| 32-bit         | 5        | 0.34%   |
| Unknown        | 2        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 185      | 12.26%  |
| Unknown    | 142      | 9.41%   |
| 0x306c3    | 137      | 9.08%   |
| 0x206a7    | 119      | 7.89%   |
| 0x306a9    | 89       | 5.9%    |
| 0x06001119 | 71       | 4.71%   |
| 0x010000c8 | 59       | 3.91%   |
| 0x506e3    | 45       | 2.98%   |
| 0x10676    | 43       | 2.85%   |
| 0x6fb      | 40       | 2.65%   |
| 0x906e9    | 38       | 2.52%   |
| 0x6fd      | 36       | 2.39%   |
| 0x906ea    | 35       | 2.32%   |
| 0x06000852 | 26       | 1.72%   |
| 0x0600084f | 19       | 1.26%   |
| 0x06003106 | 18       | 1.19%   |
| 0x0800820d | 16       | 1.06%   |
| 0x010000db | 14       | 0.93%   |
| 0x906eb    | 13       | 0.86%   |
| 0x6f2      | 13       | 0.86%   |
| 0x106a5    | 13       | 0.86%   |
| 0x03000027 | 13       | 0.86%   |
| 0x20655    | 12       | 0.8%    |
| 0x106e5    | 12       | 0.8%    |
| 0x10677    | 12       | 0.8%    |
| 0x08001138 | 12       | 0.8%    |
| 0xf43      | 11       | 0.73%   |
| 0x206c2    | 11       | 0.73%   |
| 0x20652    | 11       | 0.73%   |
| 0x08108109 | 10       | 0.66%   |
| 0x0810100b | 10       | 0.66%   |
| 0x0600063e | 9        | 0.6%    |
| 0xf65      | 8        | 0.53%   |
| 0xa0653    | 8        | 0.53%   |
| 0x6f6      | 8        | 0.53%   |
| 0x0700010f | 8        | 0.53%   |
| 0x0600611a | 8        | 0.53%   |
| 0x106ca    | 7        | 0.46%   |
| 0x08701021 | 7        | 0.46%   |
| 0x30678    | 6        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 241      | 16.51%  |
| Haswell          | 149      | 10.21%  |
| SandyBridge      | 122      | 8.36%   |
| Piledriver       | 114      | 7.81%   |
| K10              | 106      | 7.26%   |
| Core             | 104      | 7.12%   |
| KabyLake         | 97       | 6.64%   |
| IvyBridge        | 94       | 6.44%   |
| K8 Hammer        | 58       | 3.97%   |
| Skylake          | 55       | 3.77%   |
| NetBurst         | 44       | 3.01%   |
| Westmere         | 39       | 2.67%   |
| Zen              | 32       | 2.19%   |
| Zen+             | 28       | 1.92%   |
| Nehalem          | 25       | 1.71%   |
| Steamroller      | 23       | 1.58%   |
| Zen 3            | 16       | 1.1%    |
| Zen 2            | 15       | 1.03%   |
| Bonnell          | 15       | 1.03%   |
| K10 Llano        | 13       | 0.89%   |
| Excavator        | 13       | 0.89%   |
| Bulldozer        | 13       | 0.89%   |
| Silvermont       | 11       | 0.75%   |
| CometLake        | 9        | 0.62%   |
| Jaguar           | 8        | 0.55%   |
| Bobcat           | 6        | 0.41%   |
| Puma             | 3        | 0.21%   |
| Alderlake Hybrid | 3        | 0.21%   |
| Goldmont plus    | 2        | 0.14%   |
| Broadwell        | 1        | 0.07%   |
| Unknown          | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 534      | 34.32%  |
| Intel                                        | 519      | 33.35%  |
| AMD                                          | 492      | 31.62%  |
| VIA Technologies                             | 5        | 0.32%   |
| ATI Technologies                             | 2        | 0.13%   |
| Zhaoxin                                      | 1        | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.06%   |
| Matrox Electronics Systems                   | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 78       | 4.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 68       | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 59       | 3.64%   |
| Nvidia GK208B [GeForce GT 710]                                              | 52       | 3.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 43       | 2.65%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 42       | 2.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 41       | 2.53%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 36       | 2.22%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 35       | 2.16%   |
| AMD Richland [Radeon HD 8570D]                                              | 34       | 2.09%   |
| Intel HD Graphics 530                                                       | 33       | 2.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 32       | 1.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 30       | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 29       | 1.79%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 25       | 1.54%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 24       | 1.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 22       | 1.36%   |
| Nvidia GF108 [GeForce GT 630]                                               | 18       | 1.11%   |
| Nvidia GF119 [GeForce GT 610]                                               | 16       | 0.99%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 15       | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 14       | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 14       | 0.86%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 14       | 0.86%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 14       | 0.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 14       | 0.86%   |
| Nvidia GK208B [GeForce GT 730]                                              | 13       | 0.8%    |
| AMD RS880 [Radeon HD 4200]                                                  | 13       | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 0.74%   |
| AMD RS780L [Radeon 3000]                                                    | 12       | 0.74%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 12       | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 11       | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                               | 11       | 0.68%   |
| Intel HD Graphics 630                                                       | 11       | 0.68%   |
| Intel Core Processor Integrated Graphics Controller                         | 11       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 11       | 0.68%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 11       | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 10       | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 10       | 0.62%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 9        | 0.55%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 9        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 510      | 33.8%   |
| 1 x Intel      | 472      | 31.28%  |
| 1 x AMD        | 444      | 29.42%  |
| 2 x AMD        | 40       | 2.65%   |
| Intel + Nvidia | 16       | 1.06%   |
| Intel + AMD    | 9        | 0.6%    |
| AMD + Nvidia   | 6        | 0.4%    |
| 1 x VIA        | 5        | 0.33%   |
| 2 x Nvidia     | 3        | 0.2%    |
| 1 x Zhaoxin    | 1        | 0.07%   |
| 1 x XGI        | 1        | 0.07%   |
| 1 x SiS        | 1        | 0.07%   |
| 1 x Matrox     | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1398     | 94.59%  |
| Unknown     | 76       | 5.14%   |
| Proprietary | 4        | 0.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 537      | 34.58%  |
| 0.51-1.0   | 353      | 22.73%  |
| 0.01-0.5   | 288      | 18.54%  |
| 1.01-2.0   | 196      | 12.62%  |
| 3.01-4.0   | 84       | 5.41%   |
| 7.01-8.0   | 37       | 2.38%   |
| 5.01-6.0   | 23       | 1.48%   |
| 2.01-3.0   | 21       | 1.35%   |
| 8.01-16.0  | 13       | 0.84%   |
| 4.01-5.0   | 1        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 284      | 19.27%  |
| Goldstar                | 248      | 16.82%  |
| Dell                    | 118      | 8.01%   |
| Hewlett-Packard         | 85       | 5.77%   |
| Acer                    | 80       | 5.43%   |
| Philips                 | 79       | 5.36%   |
| BenQ                    | 74       | 5.02%   |
| Ancor Communications    | 71       | 4.82%   |
| AOC                     | 48       | 3.26%   |
| Fujitsu Siemens         | 44       | 2.99%   |
| Lenovo                  | 23       | 1.56%   |
| Eizo                    | 21       | 1.42%   |
| Iiyama                  | 20       | 1.36%   |
| Vestel Elektronik       | 17       | 1.15%   |
| HKC                     | 16       | 1.09%   |
| NEC Computers           | 15       | 1.02%   |
| HannStar                | 15       | 1.02%   |
| Medion                  | 14       | 0.95%   |
| ViewSonic               | 13       | 0.88%   |
| Sony                    | 12       | 0.81%   |
| ASUSTek Computer        | 11       | 0.75%   |
| Chi Mei Optoelectronics | 10       | 0.68%   |
| Belinea                 | 9        | 0.61%   |
| Plain Tree Systems      | 8        | 0.54%   |
| Panasonic               | 7        | 0.47%   |
| OEM                     | 7        | 0.47%   |
| IBM                     | 7        | 0.47%   |
| Toshiba                 | 6        | 0.41%   |
| MStar                   | 6        | 0.41%   |
| LG Electronics          | 6        | 0.41%   |
| Videoseven              | 5        | 0.34%   |
| Unknown                 | 5        | 0.34%   |
| KTC                     | 5        | 0.34%   |
| Gericom                 | 5        | 0.34%   |
| NCS                     | 4        | 0.27%   |
| CVT                     | 4        | 0.27%   |
| Sceptre Tech            | 3        | 0.2%    |
| S2-Tek                  | 3        | 0.2%    |
| Orion                   | 3        | 0.2%    |
| InnoLux Display         | 3        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 30       | 1.96%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 17       | 1.11%   |
| HKC '' HKC1850 1360x768 304x228mm 15.0-inch                              | 11       | 0.72%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 10       | 0.65%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 10       | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 9        | 0.59%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 9        | 0.59%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                       | 9        | 0.59%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 8        | 0.52%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                    | 8        | 0.52%   |
| HannStar Hanns.G HQ191 HSD0013 1280x1024 376x301mm 19.0-inch             | 8        | 0.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 8        | 0.52%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 8        | 0.52%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 7        | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 7        | 0.46%   |
| OEM 26W_LCD_TV OEM3700 1920x540                                          | 7        | 0.46%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch                 | 6        | 0.39%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 6        | 0.39%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                    | 6        | 0.39%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 6        | 0.39%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 6        | 0.39%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                         | 6        | 0.39%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                   | 6        | 0.39%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                        | 6        | 0.39%   |
| Chi Mei Optoelectronics CMC 19" AD CMO0198 1280x1024 338x270mm 17.0-inch | 6        | 0.39%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 6        | 0.39%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 5        | 0.33%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch        | 5        | 0.33%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 5        | 0.33%   |
| Samsung Electronics LS27AG30x SAM717A 1920x1080 597x336mm 27.0-inch      | 5        | 0.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 5        | 0.33%   |
| Lenovo L1951p Wide LEN0990 1440x900 408x255mm 18.9-inch                  | 5        | 0.33%   |
| Hewlett-Packard P222va HWP322B 1920x1080 476x268mm 21.5-inch             | 5        | 0.33%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                     | 5        | 0.33%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 5        | 0.33%   |
| Eizo S2202W ENC1976 1680x1050 474x297mm 22.0-inch                        | 5        | 0.33%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                         | 5        | 0.33%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                        | 5        | 0.33%   |
| Ancor Communications ASUS VH192 ACI19E4 1366x768 410x230mm 18.5-inch     | 5        | 0.33%   |
| Acer V226HQL ACR032D 1920x1080 480x270mm 21.7-inch                       | 5        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 577      | 40.41%  |
| 1280x1024 (SXGA)   | 237      | 16.6%   |
| 1680x1050 (WSXGA+) | 143      | 10.01%  |
| 1440x900 (WXGA+)   | 103      | 7.21%   |
| 3840x2160 (4K)     | 74       | 5.18%   |
| 1366x768 (WXGA)    | 72       | 5.04%   |
| 1600x900 (HD+)     | 38       | 2.66%   |
| 1360x768           | 38       | 2.66%   |
| 2560x1080          | 24       | 1.68%   |
| 2560x1440 (QHD)    | 23       | 1.61%   |
| 1920x1200 (WUXGA)  | 23       | 1.61%   |
| 1024x768 (XGA)     | 20       | 1.4%    |
| 1920x540           | 14       | 0.98%   |
| 1600x1200          | 9        | 0.63%   |
| 3840x1080          | 6        | 0.42%   |
| 1280x720 (HD)      | 6        | 0.42%   |
| 2288x1287          | 4        | 0.28%   |
| 1152x864           | 4        | 0.28%   |
| 3440x1440          | 2        | 0.14%   |
| 1280x960           | 2        | 0.14%   |
| 800x600            | 1        | 0.07%   |
| 4093x4093          | 1        | 0.07%   |
| 3840x1200          | 1        | 0.07%   |
| 2880x1200          | 1        | 0.07%   |
| 2560x1600          | 1        | 0.07%   |
| 2048x1536          | 1        | 0.07%   |
| 1280x768           | 1        | 0.07%   |
| 1024x600           | 1        | 0.07%   |
| Unknown            | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 224      | 15.16%  |
| 19      | 212      | 14.34%  |
| 23      | 153      | 10.35%  |
| 17      | 117      | 7.92%   |
| 27      | 116      | 7.85%   |
| 24      | 116      | 7.85%   |
| 22      | 105      | 7.1%    |
| 18      | 103      | 6.97%   |
| 20      | 65       | 4.4%    |
| Unknown | 39       | 2.64%   |
| 15      | 32       | 2.17%   |
| 31      | 29       | 1.96%   |
| 84      | 26       | 1.76%   |
| 34      | 25       | 1.69%   |
| 72      | 14       | 0.95%   |
| 40      | 14       | 0.95%   |
| 32      | 10       | 0.68%   |
| 54      | 7        | 0.47%   |
| 42      | 7        | 0.47%   |
| 65      | 6        | 0.41%   |
| 52      | 6        | 0.41%   |
| 12      | 6        | 0.41%   |
| 49      | 5        | 0.34%   |
| 48      | 4        | 0.27%   |
| 46      | 4        | 0.27%   |
| 26      | 4        | 0.27%   |
| 25      | 4        | 0.27%   |
| 14      | 4        | 0.27%   |
| 60      | 3        | 0.2%    |
| 142     | 2        | 0.14%   |
| 58      | 2        | 0.14%   |
| 39      | 2        | 0.14%   |
| 85      | 1        | 0.07%   |
| 64      | 1        | 0.07%   |
| 63      | 1        | 0.07%   |
| 59      | 1        | 0.07%   |
| 55      | 1        | 0.07%   |
| 47      | 1        | 0.07%   |
| 44      | 1        | 0.07%   |
| 41      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 565      | 39.15%  |
| 501-600        | 370      | 25.64%  |
| 301-350        | 145      | 10.05%  |
| 351-400        | 131      | 9.08%   |
| 1001-1500      | 42       | 2.91%   |
| 1501-2000      | 41       | 2.84%   |
| Unknown        | 39       | 2.7%    |
| 701-800        | 37       | 2.56%   |
| 601-700        | 35       | 2.43%   |
| 801-900        | 17       | 1.18%   |
| 201-300        | 10       | 0.69%   |
| 901-1000       | 9        | 0.62%   |
| More than 2000 | 2        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 794      | 57.16%  |
| 16/10   | 247      | 17.78%  |
| 5/4     | 235      | 16.92%  |
| 4/3     | 45       | 3.24%   |
| 21/9    | 26       | 1.87%   |
| 3/2     | 14       | 1.01%   |
| Unknown | 11       | 0.79%   |
| 6/5     | 7        | 0.5%    |
| 32/9    | 7        | 0.5%    |
| 1.00    | 3        | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 507      | 34.77%  |
| 151-200        | 339      | 23.25%  |
| 141-150        | 197      | 13.51%  |
| 301-350        | 117      | 8.02%   |
| More than 1000 | 74       | 5.08%   |
| 351-500        | 67       | 4.6%    |
| 251-300        | 39       | 2.67%   |
| Unknown        | 39       | 2.67%   |
| 501-1000       | 37       | 2.54%   |
| 101-110        | 19       | 1.3%    |
| 111-120        | 14       | 0.96%   |
| 71-80          | 6        | 0.41%   |
| 91-100         | 3        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1015     | 73.87%  |
| 101-120       | 243      | 17.69%  |
| 1-50          | 58       | 4.22%   |
| Unknown       | 39       | 2.84%   |
| 161-240       | 10       | 0.73%   |
| 121-160       | 8        | 0.58%   |
| More than 240 | 1        | 0.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1355     | 90.76%  |
| 2     | 91       | 6.1%    |
| 0     | 35       | 2.34%   |
| 3     | 12       | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 803      | 42.78%  |
| Intel                                  | 400      | 21.31%  |
| Qualcomm Atheros                       | 176      | 9.38%   |
| Broadcom                               | 87       | 4.64%   |
| Ralink Technology                      | 60       | 3.2%    |
| Nvidia                                 | 51       | 2.72%   |
| Qualcomm Atheros Communications        | 50       | 2.66%   |
| Broadcom Limited                       | 42       | 2.24%   |
| Marvell Technology Group               | 33       | 1.76%   |
| TP-Link                                | 30       | 1.6%    |
| Ralink                                 | 23       | 1.23%   |
| VIA Technologies                       | 15       | 0.8%    |
| Samsung Electronics                    | 12       | 0.64%   |
| D-Link                                 | 10       | 0.53%   |
| ASUSTek Computer                       | 10       | 0.53%   |
| Huawei Technologies                    | 9        | 0.48%   |
| D-Link System                          | 8        | 0.43%   |
| IMC Networks                           | 7        | 0.37%   |
| Microsoft                              | 5        | 0.27%   |
| NetGear                                | 4        | 0.21%   |
| Edimax Technology                      | 4        | 0.21%   |
| Belkin Components                      | 4        | 0.21%   |
| ASIX Electronics                       | 4        | 0.21%   |
| Accton Technology                      | 4        | 0.21%   |
| Xiaomi                                 | 3        | 0.16%   |
| JMicron Technology                     | 3        | 0.16%   |
| MediaTek                               | 2        | 0.11%   |
| Aquantia                               | 2        | 0.11%   |
| ZyXEL Communications                   | 1        | 0.05%   |
| ZyDAS                                  | 1        | 0.05%   |
| Westell                                | 1        | 0.05%   |
| Wacom                                  | 1        | 0.05%   |
| TRENDnet                               | 1        | 0.05%   |
| Texas Instruments                      | 1        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.05%   |
| Qualcomm                               | 1        | 0.05%   |
| Mercucys                               | 1        | 0.05%   |
| HMD Global                             | 1        | 0.05%   |
| Gemtek                                 | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 649      | 32.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 76       | 3.82%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 56       | 2.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 2.51%   |
| Qualcomm Atheros AR9271 802.11n                                        | 44       | 2.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 42       | 2.11%   |
| Intel Ethernet Connection I217-LM                                      | 38       | 1.91%   |
| Intel Ethernet Connection (2) I219-V                                   | 36       | 1.81%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 33       | 1.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 32       | 1.61%   |
| Nvidia MCP61 Ethernet                                                  | 31       | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 29       | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 25       | 1.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 23       | 1.15%   |
| Ralink MT7601U Wireless Adapter                                        | 21       | 1.05%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                  | 20       | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 19       | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 15       | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.75%   |
| Intel 82579V Gigabit Network Connection                                | 15       | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 14       | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.7%    |
| Intel Ethernet Connection I217-V                                       | 13       | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 12       | 0.6%    |
| Ralink RT5370 Wireless Adapter                                         | 12       | 0.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 12       | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 11       | 0.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 10       | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 0.5%    |
| Ralink RT2561/RT61 802.11g PCI                                         | 10       | 0.5%    |
| Intel 82567LF-3 Gigabit Network Connection                             | 10       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 9        | 0.45%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 9        | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 8        | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 8        | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 0.4%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 8        | 0.4%    |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 8        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 92       | 22.06%  |
| Ralink Technology                     | 60       | 14.39%  |
| Qualcomm Atheros Communications       | 50       | 11.99%  |
| Qualcomm Atheros                      | 50       | 11.99%  |
| Intel                                 | 43       | 10.31%  |
| TP-Link                               | 30       | 7.19%   |
| Ralink                                | 23       | 5.52%   |
| Broadcom                              | 11       | 2.64%   |
| ASUSTek Computer                      | 10       | 2.4%    |
| D-Link                                | 9        | 2.16%   |
| IMC Networks                          | 7        | 1.68%   |
| Microsoft                             | 5        | 1.2%    |
| NetGear                               | 4        | 0.96%   |
| Edimax Technology                     | 4        | 0.96%   |
| D-Link System                         | 4        | 0.96%   |
| Belkin Components                     | 4        | 0.96%   |
| ZyXEL Communications                  | 1        | 0.24%   |
| ZyDAS                                 | 1        | 0.24%   |
| Wacom                                 | 1        | 0.24%   |
| TRENDnet                              | 1        | 0.24%   |
| Texas Instruments                     | 1        | 0.24%   |
| Mercucys                              | 1        | 0.24%   |
| MediaTek                              | 1        | 0.24%   |
| Gemtek                                | 1        | 0.24%   |
| Fujitsu Siemens Computers             | 1        | 0.24%   |
| AVM                                   | 1        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 44       | 10.43%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 25       | 5.92%   |
| Ralink MT7601U Wireless Adapter                                               | 21       | 4.98%   |
| Ralink RT5370 Wireless Adapter                                                | 12       | 2.84%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 12       | 2.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 11       | 2.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 10       | 2.37%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 10       | 2.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 8        | 1.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 8        | 1.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 7        | 1.66%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 6        | 1.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 6        | 1.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 6        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 1.42%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 6        | 1.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5        | 1.18%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 5        | 1.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 5        | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 5        | 1.18%   |
| Ralink RT5372 Wireless Adapter                                                | 5        | 1.18%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 5        | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 5        | 1.18%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 5        | 1.18%   |
| Intel Wireless 8265 / 8275                                                    | 5        | 1.18%   |
| Intel Wireless 7260                                                           | 5        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 0.95%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 4        | 0.95%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 4        | 0.95%   |
| Ralink RT2070 Wireless Adapter                                                | 4        | 0.95%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 4        | 0.95%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]          | 4        | 0.95%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                     | 4        | 0.95%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 3        | 0.71%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 3        | 0.71%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 3        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 3        | 0.71%   |
| Intel Wireless 7265                                                           | 3        | 0.71%   |
| Intel Wireless 3165                                                           | 3        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 760      | 49.51%  |
| Intel                                  | 379      | 24.69%  |
| Qualcomm Atheros                       | 130      | 8.47%   |
| Broadcom                               | 79       | 5.15%   |
| Nvidia                                 | 51       | 3.32%   |
| Broadcom Limited                       | 42       | 2.74%   |
| Marvell Technology Group               | 33       | 2.15%   |
| VIA Technologies                       | 14       | 0.91%   |
| Samsung Electronics                    | 12       | 0.78%   |
| Huawei Technologies                    | 7        | 0.46%   |
| D-Link System                          | 4        | 0.26%   |
| ASIX Electronics                       | 4        | 0.26%   |
| Accton Technology                      | 4        | 0.26%   |
| Xiaomi                                 | 3        | 0.2%    |
| JMicron Technology                     | 3        | 0.2%    |
| Aquantia                               | 2        | 0.13%   |
| Westell                                | 1        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.07%   |
| Qualcomm                               | 1        | 0.07%   |
| MediaTek                               | 1        | 0.07%   |
| HMD Global                             | 1        | 0.07%   |
| D-Link                                 | 1        | 0.07%   |
| 3Com                                   | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 649      | 41.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 76       | 4.85%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 56       | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 3.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 42       | 2.68%   |
| Intel Ethernet Connection I217-LM                                      | 38       | 2.43%   |
| Intel Ethernet Connection (2) I219-V                                   | 36       | 2.3%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 33       | 2.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 32       | 2.04%   |
| Nvidia MCP61 Ethernet                                                  | 31       | 1.98%   |
| Intel I211 Gigabit Network Connection                                  | 29       | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 24       | 1.53%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 23       | 1.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 21       | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                                  | 20       | 1.28%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 19       | 1.21%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 15       | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.96%   |
| Intel 82579V Gigabit Network Connection                                | 15       | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 14       | 0.89%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 14       | 0.89%   |
| Intel Ethernet Connection I217-V                                       | 13       | 0.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 12       | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 0.64%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 10       | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9        | 0.57%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 9        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 0.51%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 8        | 0.51%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express        | 8        | 0.51%   |
| Intel 82574L Gigabit Network Connection                                | 7        | 0.45%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 7        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6        | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 6        | 0.38%   |
| Huawei VTR-L09                                                         | 6        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5        | 0.32%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 5        | 0.32%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 5        | 0.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1446     | 78.54%  |
| WiFi     | 392      | 21.29%  |
| Modem    | 3        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1250     | 83.5%   |
| WiFi     | 247      | 16.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1212     | 82.11%  |
| 2     | 230      | 15.58%  |
| 3     | 17       | 1.15%   |
| 0     | 14       | 0.95%   |
| 4     | 3        | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1278     | 83.58%  |
| Yes  | 251      | 16.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 105      | 50.24%  |
| Intel                           | 40       | 19.14%  |
| Broadcom                        | 14       | 6.7%    |
| ASUSTek Computer                | 10       | 4.78%   |
| Realtek Semiconductor           | 7        | 3.35%   |
| Logitech                        | 4        | 1.91%   |
| Lite-On Technology              | 4        | 1.91%   |
| Integrated System Solution      | 4        | 1.91%   |
| Conwise Technology              | 4        | 1.91%   |
| Belkin Components               | 4        | 1.91%   |
| Qualcomm Atheros Communications | 3        | 1.44%   |
| TP-Link                         | 2        | 0.96%   |
| IMC Networks                    | 2        | 0.96%   |
| Hewlett-Packard                 | 2        | 0.96%   |
| Edimax Technology               | 2        | 0.96%   |
| Dell                            | 1        | 0.48%   |
| Apple                           | 1        | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 105      | 50.24%  |
| Intel Bluetooth wireless interface                      | 12       | 5.74%   |
| Intel Bluetooth Device                                  | 6        | 2.87%   |
| Intel AX200 Bluetooth                                   | 6        | 2.87%   |
| Intel Wireless-AC 3168 Bluetooth                        | 5        | 2.39%   |
| Broadcom BCM2035 Bluetooth dongle                       | 5        | 2.39%   |
| ASUS Bluetooth Radio                                    | 5        | 2.39%   |
| Realtek  Bluetooth 4.2 Adapter                          | 4        | 1.91%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 4        | 1.91%   |
| Conwise CW6622                                          | 4        | 1.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 1.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3        | 1.44%   |
| Broadcom Bluetooth 3.0 Device                           | 3        | 1.44%   |
| Belkin Components Bluetooth Mini Dongle                 | 3        | 1.44%   |
| TP-Link UB500 Adapter                                   | 2        | 0.96%   |
| Realtek RTL8821A Bluetooth                              | 2        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 2        | 0.96%   |
| Lite-On Bluetooth Device                                | 2        | 0.96%   |
| Intel AX210 Bluetooth                                   | 2        | 0.96%   |
| Intel AX201 Bluetooth                                   | 2        | 0.96%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 2        | 0.96%   |
| Integrated System Solution Bluetooth Device             | 2        | 0.96%   |
| HP Bluetooth Adapter                                    | 2        | 0.96%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 0.96%   |
| Broadcom Bluetooth dongle                               | 2        | 0.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 0.96%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1        | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1        | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter        | 1        | 0.48%   |
| IMC Networks Wireless_Device                            | 1        | 0.48%   |
| IMC Networks Bluetooth Radio                            | 1        | 0.48%   |
| Dell Wireless 365 Bluetooth                             | 1        | 0.48%   |
| Broadcom HP Portable Bumble Bee                         | 1        | 0.48%   |
| Broadcom HP Bluethunder                                 | 1        | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 1        | 0.48%   |
| Broadcom BCM2045 Bluetooth                              | 1        | 0.48%   |
| Belkin Components F8T013 Bluetooth Adapter              | 1        | 0.48%   |
| ASUS Bluetooth Device                                   | 1        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 969      | 44.31%  |
| AMD                              | 567      | 25.93%  |
| Nvidia                           | 466      | 21.31%  |
| C-Media Electronics              | 52       | 2.38%   |
| Creative Labs                    | 38       | 1.74%   |
| VIA Technologies                 | 12       | 0.55%   |
| Texas Instruments                | 10       | 0.46%   |
| Logitech                         | 6        | 0.27%   |
| JMTek                            | 6        | 0.27%   |
| Plantronics                      | 4        | 0.18%   |
| GN Netcom                        | 4        | 0.18%   |
| Tenx Technology                  | 3        | 0.14%   |
| Generalplus Technology           | 3        | 0.14%   |
| Ensoniq                          | 3        | 0.14%   |
| Creative Technology              | 3        | 0.14%   |
| BEHRINGER International          | 3        | 0.14%   |
| ASUSTek Computer                 | 3        | 0.14%   |
| Syntek                           | 2        | 0.09%   |
| Silicon Integrated Systems [SiS] | 2        | 0.09%   |
| Razer USA                        | 2        | 0.09%   |
| Promethean Limited               | 2        | 0.09%   |
| Kingston Technology              | 2        | 0.09%   |
| ATI Technologies                 | 2        | 0.09%   |
| Zhaoxin                          | 1        | 0.05%   |
| ULi Electronics                  | 1        | 0.05%   |
| Trust                            | 1        | 0.05%   |
| Superlux digit                   | 1        | 0.05%   |
| Sunplus Technology               | 1        | 0.05%   |
| SteelSeries ApS                  | 1        | 0.05%   |
| Sony                             | 1        | 0.05%   |
| SM950T Microphone                | 1        | 0.05%   |
| Nektar                           | 1        | 0.05%   |
| Native Instruments               | 1        | 0.05%   |
| MCS                              | 1        | 0.05%   |
| KORG                             | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |
| Evolution Electronics            | 1        | 0.05%   |
| Elite Silicon                    | 1        | 0.05%   |
| DigiTech                         | 1        | 0.05%   |
| DEXP U700 microphone             | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 170      | 6.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 148      | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 137      | 5.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 131      | 5.11%   |
| AMD FCH Azalia Controller                                                         | 116      | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 90       | 3.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 72       | 2.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 72       | 2.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 69       | 2.69%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 65       | 2.53%   |
| Intel 200 Series PCH HD Audio                                                     | 60       | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 60       | 2.34%   |
| AMD Trinity HDMI Audio Controller                                                 | 58       | 2.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 58       | 2.26%   |
| Nvidia High Definition Audio Controller                                           | 54       | 2.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 54       | 2.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 50       | 1.95%   |
| Nvidia GF108 High Definition Audio Controller                                     | 45       | 1.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 36       | 1.4%    |
| Nvidia MCP61 High Definition Audio                                                | 34       | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 34       | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 34       | 1.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 33       | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 33       | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                        | 28       | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 27       | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                                     | 27       | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 26       | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                                | 24       | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 24       | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                          | 21       | 0.82%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 21       | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 19       | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 18       | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 17       | 0.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17       | 0.66%   |
| AMD Kabini HDMI/DP Audio                                                          | 17       | 0.66%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 16       | 0.62%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 16       | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                                     | 14       | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 488      | 28.03%  |
| Kingston                   | 339      | 19.47%  |
| Samsung Electronics        | 186      | 10.68%  |
| SK hynix                   | 175      | 10.05%  |
| Micron Technology          | 88       | 5.05%   |
| Crucial                    | 64       | 3.68%   |
| Kingmax                    | 62       | 3.56%   |
| Nanya Technology           | 60       | 3.45%   |
| Corsair                    | 57       | 3.27%   |
| G.Skill                    | 48       | 2.76%   |
| Elpida                     | 25       | 1.44%   |
| Team                       | 16       | 0.92%   |
| CSX                        | 15       | 0.86%   |
| Transcend                  | 13       | 0.75%   |
| Ramaxel Technology         | 13       | 0.75%   |
| Patriot                    | 12       | 0.69%   |
| A-DATA Technology          | 11       | 0.63%   |
| Qimonda                    | 7        | 0.4%    |
| Melco                      | 5        | 0.29%   |
| Goodram                    | 5        | 0.29%   |
| OCZ                        | 4        | 0.23%   |
| H                          | 4        | 0.23%   |
| Apacer                     | 4        | 0.23%   |
| Kingmax Semiconductor      | 3        | 0.17%   |
| GeIL                       | 3        | 0.17%   |
| 48spaces                   | 3        | 0.17%   |
| TwinMOS                    | 2        | 0.11%   |
| Smart                      | 2        | 0.11%   |
| Silicon Power              | 2        | 0.11%   |
| Multilaser                 | 2        | 0.11%   |
| Hikvision                  | 2        | 0.11%   |
| Uroad                      | 1        | 0.06%   |
| Unknown (7F7F7F7F7F970000) | 1        | 0.06%   |
| Unifosa                    | 1        | 0.06%   |
| Toshiba                    | 1        | 0.06%   |
| TakeMS                     | 1        | 0.06%   |
| Ramos Technology           | 1        | 0.06%   |
| Princeton                  | 1        | 0.06%   |
| Mushkin                    | 1        | 0.06%   |
| Level One Communication    | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                   | 47       | 2.3%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 45       | 2.2%    |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 44       | 2.15%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 27       | 1.32%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 23       | 1.13%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 23       | 1.13%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 22       | 1.08%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 21       | 1.03%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 20       | 0.98%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 19       | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 18       | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 17       | 0.83%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 16       | 0.78%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 16       | 0.78%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 13       | 0.64%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 13       | 0.64%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 13       | 0.64%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 13       | 0.64%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 13       | 0.64%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 12       | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 11       | 0.54%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 11       | 0.54%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 11       | 0.54%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 10       | 0.49%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s | 10       | 0.49%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 10       | 0.49%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 9        | 0.44%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 9        | 0.44%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 9        | 0.44%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 9        | 0.44%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 9        | 0.44%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 8        | 0.39%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s           | 8        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                | 8        | 0.39%   |
| Unknown RAM Module 1024MB DIMM                         | 8        | 0.39%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s    | 8        | 0.39%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s   | 8        | 0.39%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s    | 8        | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 8        | 0.39%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 7        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 589      | 39.21%  |
| DDR4    | 267      | 17.78%  |
| DDR2    | 225      | 14.98%  |
| Unknown | 185      | 12.32%  |
| SDRAM   | 180      | 11.98%  |
| DDR     | 55       | 3.66%   |
| DDR5    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1373     | 96.76%  |
| SODIMM  | 42       | 2.96%   |
| RIMM    | 3        | 0.21%   |
| FB-DIMM | 1        | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 522      | 30.74%  |
| 2048  | 517      | 30.45%  |
| 8192  | 321      | 18.9%   |
| 1024  | 223      | 13.13%  |
| 16384 | 54       | 3.18%   |
| 512   | 38       | 2.24%   |
| 32768 | 12       | 0.71%   |
| 256   | 7        | 0.41%   |
| 16    | 2        | 0.12%   |
| 128   | 1        | 0.06%   |
| 13    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 304      | 17.85%  |
| 1333    | 281      | 16.5%   |
| 800     | 206      | 12.1%   |
| 667     | 120      | 7.05%   |
| Unknown | 97       | 5.7%    |
| 2400    | 85       | 4.99%   |
| 2133    | 69       | 4.05%   |
| 1866    | 67       | 3.93%   |
| 1867    | 40       | 2.35%   |
| 3200    | 38       | 2.23%   |
| 1066    | 35       | 2.06%   |
| 533     | 29       | 1.7%    |
| 400     | 28       | 1.64%   |
| 2667    | 27       | 1.59%   |
| 3600    | 25       | 1.47%   |
| 2666    | 20       | 1.17%   |
| 1067    | 18       | 1.06%   |
| 2048    | 17       | 1%      |
| 1800    | 16       | 0.94%   |
| 1639    | 14       | 0.82%   |
| 3733    | 13       | 0.76%   |
| 2933    | 13       | 0.76%   |
| 3400    | 12       | 0.7%    |
| 3000    | 12       | 0.7%    |
| 3466    | 11       | 0.65%   |
| 49926   | 9        | 0.53%   |
| 333     | 9        | 0.53%   |
| 2000    | 8        | 0.47%   |
| 1648    | 7        | 0.41%   |
| 1334    | 6        | 0.35%   |
| 3334    | 5        | 0.29%   |
| 1331    | 5        | 0.29%   |
| 266     | 5        | 0.29%   |
| 2733    | 4        | 0.23%   |
| 1400    | 4        | 0.23%   |
| 3800    | 3        | 0.18%   |
| 3333    | 3        | 0.18%   |
| 3151    | 3        | 0.18%   |
| 3066    | 3        | 0.18%   |
| 133     | 3        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 50       | 51.02%  |
| Samsung Electronics   | 23       | 23.47%  |
| Canon                 | 12       | 12.24%  |
| Brother Industries    | 6        | 6.12%   |
| Seiko Epson           | 2        | 2.04%   |
| QinHeng Electronics   | 2        | 2.04%   |
| STMicroelectronics    | 1        | 1.02%   |
| Lexmark International | 1        | 1.02%   |
| Dymo-CoStar           | 1        | 1.02%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2600 series                                    | 10       | 10.1%   |
| Samsung M2020 Series                                      | 5        | 5.05%   |
| Samsung ML-2010P Mono Laser Printer                       | 4        | 4.04%   |
| Samsung ML-1640 Series Laser Printer                      | 3        | 3.03%   |
| HP OfficeJet 6950                                         | 3        | 3.03%   |
| HP LaserJet 1020                                          | 3        | 3.03%   |
| Samsung SCX-3400 Series                                   | 2        | 2.02%   |
| Samsung ML-1660 Series                                    | 2        | 2.02%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 2        | 2.02%   |
| QinHeng CH340S                                            | 2        | 2.02%   |
| HP LaserJet P1005                                         | 2        | 2.02%   |
| HP LaserJet 1018                                          | 2        | 2.02%   |
| HP LaserJet 1010                                          | 2        | 2.02%   |
| HP DeskJet F4100 Printer series                           | 2        | 2.02%   |
| HP Deskjet F2280 series                                   | 2        | 2.02%   |
| HP Deskjet 3520 series                                    | 2        | 2.02%   |
| HP DeskJet 2130 series                                    | 2        | 2.02%   |
| HP Deskjet 1050 J410                                      | 2        | 2.02%   |
| Canon PIXMA MG3600 Series                                 | 2        | 2.02%   |
| Brother HL-L2300D series                                  | 2        | 2.02%   |
| Brother HL-1110 series                                    | 2        | 2.02%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.01%   |
| Seiko Epson WF-3010 Series                                | 1        | 1.01%   |
| Seiko Epson L395 Series                                   | 1        | 1.01%   |
| Samsung SCX-4623 Series                                   | 1        | 1.01%   |
| Samsung SCX-3200 Series                                   | 1        | 1.01%   |
| Samsung ML-1630 Series                                    | 1        | 1.01%   |
| Samsung M2070 Series                                      | 1        | 1.01%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 1.01%   |
| Lexmark International InkJet Color Printer                | 1        | 1.01%   |
| HP OfficeJet Pro 6970                                     | 1        | 1.01%   |
| HP LaserJet 2600n                                         | 1        | 1.01%   |
| HP LaserJet 1300                                          | 1        | 1.01%   |
| HP LaserJet 1000                                          | 1        | 1.01%   |
| HP Ink Tank Wireless 410 series                           | 1        | 1.01%   |
| HP HP LaserJet M14-M17                                    | 1        | 1.01%   |
| HP DeskJet F2100 Printer series                           | 1        | 1.01%   |
| HP Deskjet D1500 series                                   | 1        | 1.01%   |
| HP DeskJet D1360                                          | 1        | 1.01%   |
| HP DeskJet 959c                                           | 1        | 1.01%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 9        | 75%     |
| Seiko Epson     | 2        | 16.67%  |
| Hewlett-Packard | 1        | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                      | 4        | 33.33%  |
| Canon CanoScan LIDE 25                                  | 2        | 16.67%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 8.33%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1        | 8.33%   |
| HP ScanJet 3670                                         | 1        | 8.33%   |
| Canon CanoScan LiDE 120                                 | 1        | 8.33%   |
| Canon CanoScan LiDE 110                                 | 1        | 8.33%   |
| Canon CanoScan LiDE 100                                 | 1        | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 46       | 24.86%  |
| Microdia                      | 29       | 15.68%  |
| KYE Systems (Mouse Systems)   | 16       | 8.65%   |
| Microsoft                     | 15       | 8.11%   |
| Z-Star Microelectronics       | 14       | 7.57%   |
| GEMBIRD                       | 10       | 5.41%   |
| Pixart Imaging                | 7        | 3.78%   |
| Cubeternet                    | 6        | 3.24%   |
| Samsung Electronics           | 5        | 2.7%    |
| Trust                         | 4        | 2.16%   |
| Chicony Electronics           | 4        | 2.16%   |
| Apple                         | 4        | 2.16%   |
| Realtek Semiconductor         | 3        | 1.62%   |
| Aveo Technology               | 3        | 1.62%   |
| Arkmicro Technologies         | 3        | 1.62%   |
| Sunplus Innovation Technology | 2        | 1.08%   |
| MacroSilicon                  | 2        | 1.08%   |
| LG Electronics                | 2        | 1.08%   |
| Generalplus Technology        | 2        | 1.08%   |
| Creative Technology           | 2        | 1.08%   |
| Unknown                       | 1        | 0.54%   |
| Novatek Microelectronics      | 1        | 0.54%   |
| Jieli Technology              | 1        | 0.54%   |
| IMC Networks                  | 1        | 0.54%   |
| Hewlett-Packard               | 1        | 0.54%   |
| 2M UVC CAMERA                 | 1        | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Microdia Camera                                       | 15       | 8.06%   |
| Logitech Webcam C270                                  | 10       | 5.38%   |
| Microdia Sonix USB 2.0 Camera                         | 8        | 4.3%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 8        | 4.3%    |
| Logitech Webcam C600                                  | 7        | 3.76%   |
| Z-Star Vimicro USB Camera (Altair)                    | 6        | 3.23%   |
| Z-Star Venus USB2.0 Camera                            | 5        | 2.69%   |
| Samsung Galaxy series, misc. (MTP mode)               | 5        | 2.69%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 5        | 2.69%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 5        | 2.69%   |
| Microsoft LifeCam HD-3000                             | 4        | 2.15%   |
| Logitech Webcam C170                                  | 4        | 2.15%   |
| Logitech HD Pro Webcam C920                           | 4        | 2.15%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 4        | 2.15%   |
| Cubeternet USB2.0 Camera                              | 4        | 2.15%   |
| Microsoft LifeCam VX-2000                             | 3        | 1.61%   |
| Logitech Webcam C250                                  | 3        | 1.61%   |
| Logitech QuickCam Pro 9000                            | 3        | 1.61%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 3        | 1.61%   |
| Arkmicro USB2.0 PC CAMERA                             | 3        | 1.61%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 3        | 1.61%   |
| Z-Star Saturn USB 2.0 Camera                          | 2        | 1.08%   |
| Trust 17676 Webcam                                    | 2        | 1.08%   |
| Sunplus Full HD webcam                                | 2        | 1.08%   |
| Microsoft LifeCam VX-700                              | 2        | 1.08%   |
| Microsoft LifeCam VX-500 [1357]                       | 2        | 1.08%   |
| Microdia USB 2.0 Camera                               | 2        | 1.08%   |
| Microdia Integrated Camera                            | 2        | 1.08%   |
| Logitech Webcam C310                                  | 2        | 1.08%   |
| Logitech Webcam C210                                  | 2        | 1.08%   |
| Logitech QuickCam Communicate Deluxe/S7500            | 2        | 1.08%   |
| Logitech HD Webcam C525                               | 2        | 1.08%   |
| Logitech C920 PRO HD Webcam                           | 2        | 1.08%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.08%   |
| KYE Systems (Mouse Systems) FaceCam 320X              | 2        | 1.08%   |
| GEMBIRD USB2.0 PC CAMERA                              | 2        | 1.08%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 2        | 1.08%   |
| Aveo USB2.0 Camera                                    | 2        | 1.08%   |
| Z-Star Vega USB 2.0 Camera                            | 1        | 0.54%   |
| Unknown HD camera                                     | 1        | 0.54%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 2        | 40%     |
| Reiner SCT Kartensysteme  | 1        | 20%     |
| Gemalto (was Gemplus)     | 1        | 20%     |
| Aladdin Knowledge Systems | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 40%     |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 20%     |
| Aladdin Knowledge Systems Token JC                                         | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1313     | 87.3%   |
| 1     | 177      | 11.77%  |
| 2     | 12       | 0.8%    |
| 5     | 1        | 0.07%   |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 141      | 70.5%   |
| Net/wireless             | 22       | 11%     |
| Camera                   | 10       | 5%      |
| Communication controller | 7        | 3.5%    |
| Unassigned class         | 6        | 3%      |
| Chipcard                 | 4        | 2%      |
| Sound                    | 3        | 1.5%    |
| Net/ethernet             | 2        | 1%      |
| Card reader              | 2        | 1%      |
| Storage                  | 1        | 0.5%    |
| Fingerprint reader       | 1        | 0.5%    |
| Bluetooth                | 1        | 0.5%    |

