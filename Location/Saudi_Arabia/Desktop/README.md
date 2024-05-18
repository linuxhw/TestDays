Linux in Saudi Arabia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

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

Total: 250

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | G20AJ                       | [bbb2ae3890](https://linux-hardware.org/?probe=bbb2ae3890) | Apr 20, 2024 |
| ASUSTek       | G20AJ                       | [f9741e3c18](https://linux-hardware.org/?probe=f9741e3c18) | Apr 20, 2024 |
| HP            | 2B38                        | [db7129fcde](https://linux-hardware.org/?probe=db7129fcde) | Apr 07, 2024 |
| HP            | 2B38                        | [44386f0027](https://linux-hardware.org/?probe=44386f0027) | Apr 07, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [c55cd9fbac](https://linux-hardware.org/?probe=c55cd9fbac) | Mar 22, 2024 |
| Gigabyte      | B760 DS3H DDR4              | [18eb8a593e](https://linux-hardware.org/?probe=18eb8a593e) | Mar 18, 2024 |
| Dell          | 0JCTF8 A00                  | [eb32037afd](https://linux-hardware.org/?probe=eb32037afd) | Mar 16, 2024 |
| Dell          | 0JCTF8 A00                  | [ff149982e7](https://linux-hardware.org/?probe=ff149982e7) | Mar 16, 2024 |
| ASRock        | B450 Pro4                   | [723f208e9b](https://linux-hardware.org/?probe=723f208e9b) | Mar 14, 2024 |
| ASRock        | B450 Pro4                   | [a3a7dd03fc](https://linux-hardware.org/?probe=a3a7dd03fc) | Mar 14, 2024 |
| Lenovo        | MAHOBAY                     | [ea1d8e1132](https://linux-hardware.org/?probe=ea1d8e1132) | Mar 03, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [094127d440](https://linux-hardware.org/?probe=094127d440) | Feb 26, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [adace6bd02](https://linux-hardware.org/?probe=adace6bd02) | Feb 22, 2024 |
| HP            | 3648h                       | [96e8e58699](https://linux-hardware.org/?probe=96e8e58699) | Feb 11, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [7cd906021e](https://linux-hardware.org/?probe=7cd906021e) | Feb 07, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [bbc54bcc7c](https://linux-hardware.org/?probe=bbc54bcc7c) | Jan 27, 2024 |
| Lenovo        | 3740 NOK                    | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | [803c2f0bd9](https://linux-hardware.org/?probe=803c2f0bd9) | Jan 16, 2024 |
| Lenovo        | MAHOBAY                     | [68a882e9f2](https://linux-hardware.org/?probe=68a882e9f2) | Jan 10, 2024 |
| HP            | 2215                        | [cea6ba103b](https://linux-hardware.org/?probe=cea6ba103b) | Jan 07, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| Gigabyte      | B550 AORUS MASTER           | [d52d7379c3](https://linux-hardware.org/?probe=d52d7379c3) | Dec 06, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Shenzhen M... | F7BAA                       | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | 0HY9JP A00                  | [f4c78fb767](https://linux-hardware.org/?probe=f4c78fb767) | Nov 19, 2023 |
| Dell          | 0HY9JP A00                  | [c845b4f25f](https://linux-hardware.org/?probe=c845b4f25f) | Nov 18, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [9aa2678591](https://linux-hardware.org/?probe=9aa2678591) | Nov 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [6c51a94d03](https://linux-hardware.org/?probe=6c51a94d03) | Nov 15, 2023 |
| ASUSTek       | TUF H310-PLUS GAMING        | [b9e39aa8c1](https://linux-hardware.org/?probe=b9e39aa8c1) | Nov 10, 2023 |
| MSI           | 2A9Ch                       | [3e7da65a41](https://linux-hardware.org/?probe=3e7da65a41) | Oct 27, 2023 |
| MSI           | 2A9Ch                       | [6b9e5b921c](https://linux-hardware.org/?probe=6b9e5b921c) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| MSI           | 2A9Ch                       | [81c485dfbe](https://linux-hardware.org/?probe=81c485dfbe) | Oct 16, 2023 |
| MSI           | 2A9Ch                       | [6b86dab25f](https://linux-hardware.org/?probe=6b86dab25f) | Oct 16, 2023 |
| HP            | 3397                        | [5740126c3c](https://linux-hardware.org/?probe=5740126c3c) | Sep 25, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [40df085797](https://linux-hardware.org/?probe=40df085797) | Sep 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [78f326afa5](https://linux-hardware.org/?probe=78f326afa5) | Sep 12, 2023 |
| HP            | 3397                        | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| Lenovo        | 3740 NOK                    | [b1beaf9e38](https://linux-hardware.org/?probe=b1beaf9e38) | Aug 22, 2023 |
| ASUSTek       | X99-A II                    | [4587b7ff26](https://linux-hardware.org/?probe=4587b7ff26) | Aug 14, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| Dell          | 0HY9JP A00                  | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | 3397                        | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dcbf7b10c](https://linux-hardware.org/?probe=9dcbf7b10c) | Aug 03, 2023 |
| Gigabyte      | B460M DS3H V2               | [42b35cd473](https://linux-hardware.org/?probe=42b35cd473) | Jul 30, 2023 |
| Lenovo        | 3740 NOK                    | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| ASUSTek       | H81M-V3                     | [017671472c](https://linux-hardware.org/?probe=017671472c) | Jul 15, 2023 |
| Dell          | 0N4YC8 A00                  | [b6c778034c](https://linux-hardware.org/?probe=b6c778034c) | Jul 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [4d8e159540](https://linux-hardware.org/?probe=4d8e159540) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [6dbef58b31](https://linux-hardware.org/?probe=6dbef58b31) | Jul 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [4e2b34c387](https://linux-hardware.org/?probe=4e2b34c387) | Jul 02, 2023 |
| Lenovo        | 3740 NOK                    | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [436b4c3ab9](https://linux-hardware.org/?probe=436b4c3ab9) | Jun 16, 2023 |
| DJI           | MANIFOLD 2-C                | [44edfc848e](https://linux-hardware.org/?probe=44edfc848e) | Jun 13, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Gigabyte      | B460M DS3H V2               | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| Dell          | 042P49 A02                  | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| ASUSTek       | H81M-V3                     | [fd123bea36](https://linux-hardware.org/?probe=fd123bea36) | Mar 29, 2023 |
| ASUSTek       | H81M-V3                     | [ce98454e55](https://linux-hardware.org/?probe=ce98454e55) | Mar 29, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Gigabyte      | B365M H                     | [70e1aa9793](https://linux-hardware.org/?probe=70e1aa9793) | Mar 13, 2023 |
| Dell          | 0PC5F7 A03                  | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| Medion        | MS-7797                     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Unknown       | 1.0                         | [402bce9e43](https://linux-hardware.org/?probe=402bce9e43) | Feb 03, 2023 |
| Unknown       | 1.0                         | [85d36881c1](https://linux-hardware.org/?probe=85d36881c1) | Jan 26, 2023 |
| Unknown       | 1.0                         | [a25e1d1008](https://linux-hardware.org/?probe=a25e1d1008) | Jan 26, 2023 |
| Unknown       | 1.0                         | [99201dd05a](https://linux-hardware.org/?probe=99201dd05a) | Jan 24, 2023 |
| Unknown       | 1.0                         | [678e6d3875](https://linux-hardware.org/?probe=678e6d3875) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [476d23dca7](https://linux-hardware.org/?probe=476d23dca7) | Jan 21, 2023 |
| ASUSTek       | PRIME Z370-A                | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| Gigabyte      | G41M-ES2L                   | [b69b2d21e9](https://linux-hardware.org/?probe=b69b2d21e9) | Jan 15, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [5ac16a435c](https://linux-hardware.org/?probe=5ac16a435c) | Jan 09, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| ASUSTek       | PRIME B560M-A               | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| HP            | 212B                        | [3df121c98b](https://linux-hardware.org/?probe=3df121c98b) | Dec 21, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [eb95cbbbe0](https://linux-hardware.org/?probe=eb95cbbbe0) | Dec 03, 2022 |
| MSI           | B560M-A PRO                 | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| HP            | 212B                        | [d5cc313fba](https://linux-hardware.org/?probe=d5cc313fba) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| HP            | 8906 SMVB                   | [3e86b56fb8](https://linux-hardware.org/?probe=3e86b56fb8) | Oct 23, 2022 |
| Dell          | 0VD92X A00                  | [7f90427c64](https://linux-hardware.org/?probe=7f90427c64) | Oct 15, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [8373c5268a](https://linux-hardware.org/?probe=8373c5268a) | Sep 05, 2022 |
| Dell          | 0HY9JP A01                  | [b87b0407d9](https://linux-hardware.org/?probe=b87b0407d9) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | [fbb579a5d6](https://linux-hardware.org/?probe=fbb579a5d6) | Aug 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Dell          | 0VD92X A00                  | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Dell          | 0VD92X A00                  | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| MSI           | B250M BAZOOKA               | [870c420b4b](https://linux-hardware.org/?probe=870c420b4b) | Jun 04, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [d7d06bf7ef](https://linux-hardware.org/?probe=d7d06bf7ef) | May 26, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Dell          | 0M9KCM A01                  | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Unknown       | HX90                        | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| Unknown       | HX90                        | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Dell          | 0VD92X A00                  | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| Dell          | 0VD92X A00                  | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Gigabyte      | B75M-HD3                    | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | 0VD92X A00                  | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| Dell          | 0WWJRX A00                  | [bb620cc0f9](https://linux-hardware.org/?probe=bb620cc0f9) | Feb 26, 2022 |
| Gigabyte      | MJPLNAB-00                  | [007ec5dbf5](https://linux-hardware.org/?probe=007ec5dbf5) | Feb 24, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| ASRock        | B365M Phantom Gaming 4      | [9dd59e5403](https://linux-hardware.org/?probe=9dd59e5403) | Feb 08, 2022 |
| Dell          | 09M8Y8 A01                  | [e0748343d9](https://linux-hardware.org/?probe=e0748343d9) | Feb 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| HP            | 8906 SMVB                   | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| MSI           | MS-7529                     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Gigabyte      | Z77-D3H                     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| Intel         | DP55WB AAE64798-206         | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Dell          | 0T656F A02                  | [a1abd4e08e](https://linux-hardware.org/?probe=a1abd4e08e) | Nov 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [65c4bea87a](https://linux-hardware.org/?probe=65c4bea87a) | Oct 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [b22e6dc21a](https://linux-hardware.org/?probe=b22e6dc21a) | Oct 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [428e41ed23](https://linux-hardware.org/?probe=428e41ed23) | Oct 05, 2021 |
| Dell          | 054KM3 A01                  | [6d277dcd36](https://linux-hardware.org/?probe=6d277dcd36) | Sep 18, 2021 |
| Gigabyte      | H81M-S2PH                   | [ef4fb4b996](https://linux-hardware.org/?probe=ef4fb4b996) | Aug 28, 2021 |
| Dell          | 0M9KCM A00                  | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Dell          | 0W0CHX A01                  | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| Dell          | 0XHGV1 A01                  | [4fcd4b7e98](https://linux-hardware.org/?probe=4fcd4b7e98) | Jun 22, 2021 |
| Intel         | BTC-T37                     | [6cd9eb4fd4](https://linux-hardware.org/?probe=6cd9eb4fd4) | Jun 19, 2021 |
| Intel         | BTC-T37                     | [3f0a790d81](https://linux-hardware.org/?probe=3f0a790d81) | Jun 19, 2021 |
| MSI           | Z77A-G43                    | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| Dell          | 042P49 A00                  | [f146c310d6](https://linux-hardware.org/?probe=f146c310d6) | May 18, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| Gigabyte      | B75M-HD3                    | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| ASUSTek       | P6X58D PREMIUM              | [f568952b1d](https://linux-hardware.org/?probe=f568952b1d) | Mar 10, 2021 |
| Huanan        | X99-F8                      | [3bbee45dc4](https://linux-hardware.org/?probe=3bbee45dc4) | Mar 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c03aab940e](https://linux-hardware.org/?probe=c03aab940e) | Feb 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66003aa802](https://linux-hardware.org/?probe=66003aa802) | Feb 28, 2021 |
| ASUSTek       | PRIME Z490-P                | [290dbb71c2](https://linux-hardware.org/?probe=290dbb71c2) | Feb 25, 2021 |
| HP            | 8591                        | [b6b7f6af35](https://linux-hardware.org/?probe=b6b7f6af35) | Feb 15, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [c8b28bb334](https://linux-hardware.org/?probe=c8b28bb334) | Feb 13, 2021 |
| Dell          | 0GY6Y8 A02                  | [5ed908976b](https://linux-hardware.org/?probe=5ed908976b) | Feb 09, 2021 |
| MSI           | B450M PRO-M2 V2             | [1d97b5c83d](https://linux-hardware.org/?probe=1d97b5c83d) | Jan 31, 2021 |
| MSI           | B450M PRO-M2 V2             | [5911afaa7a](https://linux-hardware.org/?probe=5911afaa7a) | Jan 27, 2021 |
| MSI           | B450M PRO-M2 V2             | [6bdd3b4a5d](https://linux-hardware.org/?probe=6bdd3b4a5d) | Jan 27, 2021 |
| Pegatron      | 2AD5                        | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2249011658](https://linux-hardware.org/?probe=2249011658) | Dec 30, 2020 |
| Dell          | 0GN6JF A01                  | [b4ea210c79](https://linux-hardware.org/?probe=b4ea210c79) | Dec 27, 2020 |
| OEM           | B250                        | [80af247c92](https://linux-hardware.org/?probe=80af247c92) | Dec 09, 2020 |
| HP            | 198E                        | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | X570 Steel Legend           | [6c1033e9f9](https://linux-hardware.org/?probe=6c1033e9f9) | Dec 04, 2020 |
| ASRock        | X570 Steel Legend           | [1e0a7199b7](https://linux-hardware.org/?probe=1e0a7199b7) | Dec 03, 2020 |
| HP            | 843C                        | [fd8c0fa877](https://linux-hardware.org/?probe=fd8c0fa877) | Nov 10, 2020 |
| OEM           | B250                        | [f6bcb7135c](https://linux-hardware.org/?probe=f6bcb7135c) | Nov 10, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e1c5dde63a](https://linux-hardware.org/?probe=e1c5dde63a) | Oct 12, 2020 |
| ASRock        | X470 Master SLI/ac          | [3ec057ab8d](https://linux-hardware.org/?probe=3ec057ab8d) | Sep 18, 2020 |
| ASRock        | Z270M Pro4                  | [ed0a963b78](https://linux-hardware.org/?probe=ed0a963b78) | Sep 05, 2020 |
| Gigabyte      | H81M-S2PH                   | [8634132c3a](https://linux-hardware.org/?probe=8634132c3a) | Aug 24, 2020 |
| Gigabyte      | H81M-S2PH                   | [54032f9ee7](https://linux-hardware.org/?probe=54032f9ee7) | Aug 19, 2020 |
| MSI           | Z370 KRAIT GAMING           | [c04081db17](https://linux-hardware.org/?probe=c04081db17) | Aug 07, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [fa825c1fce](https://linux-hardware.org/?probe=fa825c1fce) | Jul 26, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | [3098a39bdb](https://linux-hardware.org/?probe=3098a39bdb) | Jul 26, 2020 |
| Unknown       | Unknown                     | [1c82bd39f0](https://linux-hardware.org/?probe=1c82bd39f0) | Jul 01, 2020 |
| Dell          | 0GN6JF A01                  | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [6c1261f611](https://linux-hardware.org/?probe=6c1261f611) | Jun 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [eb4135b12e](https://linux-hardware.org/?probe=eb4135b12e) | Jun 07, 2020 |
| Pegatron      | 2A84h                       | [a5884bfb13](https://linux-hardware.org/?probe=a5884bfb13) | Jun 01, 2020 |
| Gigabyte      | H61M-S2P                    | [aecc9b0111](https://linux-hardware.org/?probe=aecc9b0111) | May 25, 2020 |
| Gigabyte      | B75M-HD3                    | [bedfc8fa0f](https://linux-hardware.org/?probe=bedfc8fa0f) | May 21, 2020 |
| Dell          | 0GY6Y8 A03                  | [874c2cb817](https://linux-hardware.org/?probe=874c2cb817) | May 20, 2020 |
| ASRock        | 990FX Extreme9              | [1947ac6d52](https://linux-hardware.org/?probe=1947ac6d52) | May 16, 2020 |
| ASRock        | 990FX Extreme9              | [dc7f6cc9e8](https://linux-hardware.org/?probe=dc7f6cc9e8) | May 16, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASRock        | Z77 Extreme4                | [5aaf89e123](https://linux-hardware.org/?probe=5aaf89e123) | Feb 03, 2020 |
| Intel         | DP55WB AAE64798-206         | [bb1c5e0c3a](https://linux-hardware.org/?probe=bb1c5e0c3a) | Jan 01, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [0da4e7552a](https://linux-hardware.org/?probe=0da4e7552a) | Dec 29, 2019 |
| Intel         | DP55WB AAE64798-206         | [c137a7866b](https://linux-hardware.org/?probe=c137a7866b) | Dec 14, 2019 |
| MSI           | 2A78h                       | [83e806e50e](https://linux-hardware.org/?probe=83e806e50e) | Oct 25, 2019 |
| MSI           | 2A78h                       | [b5679811c8](https://linux-hardware.org/?probe=b5679811c8) | Oct 25, 2019 |
| MSI           | B360M GAMING PLUS           | [f54aa10fcc](https://linux-hardware.org/?probe=f54aa10fcc) | Oct 24, 2019 |
| MSI           | B360M GAMING PLUS           | [96ee6c9f88](https://linux-hardware.org/?probe=96ee6c9f88) | Oct 24, 2019 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | [4976e1673d](https://linux-hardware.org/?probe=4976e1673d) | Oct 01, 2019 |
| Dell          | 0HN7XN A01                  | [b9dd067151](https://linux-hardware.org/?probe=b9dd067151) | Aug 18, 2019 |
| Dell          | 0HN7XN A01                  | [67161826ca](https://linux-hardware.org/?probe=67161826ca) | Aug 18, 2019 |
| Intel         | DP55WB AAE64798-206         | [0a1b8c3a29](https://linux-hardware.org/?probe=0a1b8c3a29) | Aug 17, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [bc9f90fd94](https://linux-hardware.org/?probe=bc9f90fd94) | Jul 20, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [a5dd292f0e](https://linux-hardware.org/?probe=a5dd292f0e) | Jul 20, 2019 |
| Intel         | DP55WB AAE64798-206         | [78b4fe060a](https://linux-hardware.org/?probe=78b4fe060a) | Jul 19, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [b3224eb5fc](https://linux-hardware.org/?probe=b3224eb5fc) | Jul 19, 2019 |
| Intel         | DP55WB AAE64798-206         | [f8b4fc087b](https://linux-hardware.org/?probe=f8b4fc087b) | Jul 13, 2019 |
| Dell          | 0PC5F7 A02                  | [d5c119cb28](https://linux-hardware.org/?probe=d5c119cb28) | Jun 04, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | [9a655727f9](https://linux-hardware.org/?probe=9a655727f9) | Jun 02, 2019 |
| ASUSTek       | Z97-A                       | [5bca621b29](https://linux-hardware.org/?probe=5bca621b29) | May 31, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [14b4f17a8a](https://linux-hardware.org/?probe=14b4f17a8a) | Apr 22, 2019 |
| Dell          | 0C27VV A03                  | [4a17c281b7](https://linux-hardware.org/?probe=4a17c281b7) | Apr 05, 2019 |
| Gigabyte      | B360N WIFI-CF               | [8366ef739b](https://linux-hardware.org/?probe=8366ef739b) | Jan 19, 2019 |
| Gigabyte      | B360N WIFI-CF               | [8c5dcea151](https://linux-hardware.org/?probe=8c5dcea151) | Jan 07, 2019 |
| Gigabyte      | B360N WIFI-CF               | [f238cfd7d7](https://linux-hardware.org/?probe=f238cfd7d7) | Jan 07, 2019 |
| Lenovo        | NOK                         | [2761f888c3](https://linux-hardware.org/?probe=2761f888c3) | Nov 16, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [3e2fa165a6](https://linux-hardware.org/?probe=3e2fa165a6) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [a7272b3797](https://linux-hardware.org/?probe=a7272b3797) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [9c149f8d89](https://linux-hardware.org/?probe=9c149f8d89) | Oct 28, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [5c682ba446](https://linux-hardware.org/?probe=5c682ba446) | Oct 26, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [28a72027c5](https://linux-hardware.org/?probe=28a72027c5) | Oct 25, 2018 |
| Gigabyte      | P35-DS3R                    | [2f8f1a592b](https://linux-hardware.org/?probe=2f8f1a592b) | Aug 14, 2018 |
| Gigabyte      | H81M-S2PH                   | [d9e3df518a](https://linux-hardware.org/?probe=d9e3df518a) | Dec 08, 2017 |
| Dell          | 0VNP2H A00                  | [68fa7ad805](https://linux-hardware.org/?probe=68fa7ad805) | Nov 25, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 22.04        | 15       | 9.62%   |
| Ubuntu 20.04        | 13       | 8.33%   |
| Ubuntu 18.04        | 7        | 4.49%   |
| OpenMandriva 4.3    | 5        | 3.21%   |
| OpenMandriva 4.2    | 5        | 3.21%   |
| Manjaro             | 5        | 3.21%   |
| Pop!_OS 21.10       | 4        | 2.56%   |
| Debian 10           | 4        | 2.56%   |
| Ubuntu 19.10        | 3        | 1.92%   |
| ROSA R10            | 3        | 1.92%   |
| OpenMandriva 23.01  | 3        | 1.92%   |
| Nobara 37           | 3        | 1.92%   |
| Debian 11           | 3        | 1.92%   |
| ArcoLinux Rolling   | 3        | 1.92%   |
| Ubuntu Unity 18.04  | 2        | 1.28%   |
| Ubuntu 22.10        | 2        | 1.28%   |
| Ubuntu 21.10        | 2        | 1.28%   |
| Pop!_OS 22.04       | 2        | 1.28%   |
| Pop!_OS 21.04       | 2        | 1.28%   |
| OpenMandriva 23.08  | 2        | 1.28%   |
| Manjaro 20.2        | 2        | 1.28%   |
| Kubuntu 22.10       | 2        | 1.28%   |
| Fedora 39           | 2        | 1.28%   |
| Fedora 37           | 2        | 1.28%   |
| Fedora 35           | 2        | 1.28%   |
| Endless 3.9.0       | 2        | 1.28%   |
| Arch                | 2        | 1.28%   |
| Zorin 17            | 1        | 0.64%   |
| Zorin 16            | 1        | 0.64%   |
| Zorin 15            | 1        | 0.64%   |
| Ubuntu MATE 22.04   | 1        | 0.64%   |
| Ubuntu Budgie 20.04 | 1        | 0.64%   |
| Ubuntu 23.10        | 1        | 0.64%   |
| Ubuntu 23.04        | 1        | 0.64%   |
| Ubuntu 19.04        | 1        | 0.64%   |
| Ubuntu 18.10        | 1        | 0.64%   |
| Ubuntu 16.04        | 1        | 0.64%   |
| Solus 4.3           | 1        | 0.64%   |
| ROSA R8             | 1        | 0.64%   |
| ROSA R11.1          | 1        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 44       | 30.34%  |
| OpenMandriva     | 17       | 11.72%  |
| Manjaro          | 10       | 6.9%    |
| Fedora           | 9        | 6.21%   |
| Pop!_OS          | 8        | 5.52%   |
| ROSA             | 7        | 4.83%   |
| Debian           | 7        | 4.83%   |
| Endless          | 5        | 3.45%   |
| Nobara           | 4        | 2.76%   |
| Kubuntu          | 4        | 2.76%   |
| Kali             | 4        | 2.76%   |
| Zorin            | 3        | 2.07%   |
| Linux Mint       | 3        | 2.07%   |
| ArcoLinux        | 3        | 2.07%   |
| Arch             | 3        | 2.07%   |
| Ubuntu Unity     | 2        | 1.38%   |
| Ubuntu MATE      | 1        | 0.69%   |
| Ubuntu Budgie    | 1        | 0.69%   |
| Solus            | 1        | 0.69%   |
| Pear OS          | 1        | 0.69%   |
| org.kde.Platform | 1        | 0.69%   |
| openSUSE         | 1        | 0.69%   |
| Linux Lite       | 1        | 0.69%   |
| KDE neon         | 1        | 0.69%   |
| EndeavourOS      | 1        | 0.69%   |
| Drauger OS       | 1        | 0.69%   |
| Clear Linux      | 1        | 0.69%   |
| CentOS           | 1        | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 5        | 2.82%   |
| 5.10.14-desktop-1omv4002        | 5        | 2.82%   |
| 6.1.1-desktop-1omv2290          | 3        | 1.69%   |
| 5.13.0-37-generic               | 3        | 1.69%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3        | 1.69%   |
| 6.5.0-kali3-amd64               | 2        | 1.13%   |
| 6.4.11-desktop-1omv2390         | 2        | 1.13%   |
| 6.2.0-26-generic                | 2        | 1.13%   |
| 5.9.11-3-MANJARO                | 2        | 1.13%   |
| 5.8.0-14-generic                | 2        | 1.13%   |
| 5.4.0-42-generic                | 2        | 1.13%   |
| 5.19.0-50-generic               | 2        | 1.13%   |
| 5.19.0-23-generic               | 2        | 1.13%   |
| 5.15.5-76051505-generic         | 2        | 1.13%   |
| 5.15.0-75-generic               | 2        | 1.13%   |
| 4.18.0-25-generic               | 2        | 1.13%   |
| 4.18.0-17-generic               | 2        | 1.13%   |
| 6.8.4-200.fc39.x86_64           | 1        | 0.56%   |
| 6.7.9-arch1-1                   | 1        | 0.56%   |
| 6.7.9-200.fc39.x86_64           | 1        | 0.56%   |
| 6.7.2-1-default                 | 1        | 0.56%   |
| 6.7.1-1-default                 | 1        | 0.56%   |
| 6.6.9-amd64                     | 1        | 0.56%   |
| 6.6.6-76060606-generic          | 1        | 0.56%   |
| 6.6.4-arch1-1                   | 1        | 0.56%   |
| 6.6.2-desktop-1omv2390          | 1        | 0.56%   |
| 6.5.6-76060506-generic          | 1        | 0.56%   |
| 6.5.3-arch1-1                   | 1        | 0.56%   |
| 6.5.0-28-generic                | 1        | 0.56%   |
| 6.5.0-26-generic                | 1        | 0.56%   |
| 6.5.0-25-generic                | 1        | 0.56%   |
| 6.5.0-21-generic                | 1        | 0.56%   |
| 6.5.0-14-generic                | 1        | 0.56%   |
| 6.5.0-10-lowlatency             | 1        | 0.56%   |
| 6.4.7-200.fc38.x86_64           | 1        | 0.56%   |
| 6.4.1-zen1-1-zen                | 1        | 0.56%   |
| 6.3.12-204.fsync.fc38.x86_64    | 1        | 0.56%   |
| 6.2.6-desktop-1omv2390          | 1        | 0.56%   |
| 6.2.12-200.fsync.fc37.x86_64    | 1        | 0.56%   |
| 6.2.0-39-generic                | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 13       | 7.6%    |
| 5.15.0  | 12       | 7.02%   |
| 5.19.0  | 9        | 5.26%   |
| 6.5.0   | 8        | 4.68%   |
| 6.2.0   | 6        | 3.51%   |
| 4.18.0  | 6        | 3.51%   |
| 4.15.0  | 6        | 3.51%   |
| 5.8.0   | 5        | 2.92%   |
| 5.3.0   | 5        | 2.92%   |
| 5.16.7  | 5        | 2.92%   |
| 5.13.0  | 5        | 2.92%   |
| 5.10.14 | 5        | 2.92%   |
| 5.11.0  | 4        | 2.34%   |
| 6.1.1   | 3        | 1.75%   |
| 5.10.0  | 3        | 1.75%   |
| 4.9.60  | 3        | 1.75%   |
| 6.7.9   | 2        | 1.17%   |
| 6.4.11  | 2        | 1.17%   |
| 6.0.8   | 2        | 1.17%   |
| 5.9.11  | 2        | 1.17%   |
| 5.5.0   | 2        | 1.17%   |
| 5.16.11 | 2        | 1.17%   |
| 5.15.5  | 2        | 1.17%   |
| 5.0.0   | 2        | 1.17%   |
| 4.19.0  | 2        | 1.17%   |
| 6.8.4   | 1        | 0.58%   |
| 6.7.2   | 1        | 0.58%   |
| 6.7.1   | 1        | 0.58%   |
| 6.6.9   | 1        | 0.58%   |
| 6.6.6   | 1        | 0.58%   |
| 6.6.4   | 1        | 0.58%   |
| 6.6.2   | 1        | 0.58%   |
| 6.5.6   | 1        | 0.58%   |
| 6.5.3   | 1        | 0.58%   |
| 6.4.7   | 1        | 0.58%   |
| 6.4.1   | 1        | 0.58%   |
| 6.3.12  | 1        | 0.58%   |
| 6.2.6   | 1        | 0.58%   |
| 6.2.12  | 1        | 0.58%   |
| 6.1.8   | 1        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 20       | 12.05%  |
| 5.4     | 13       | 7.83%   |
| 5.10    | 11       | 6.63%   |
| 6.5     | 10       | 6.02%   |
| 5.19    | 10       | 6.02%   |
| 5.16    | 9        | 5.42%   |
| 6.2     | 8        | 4.82%   |
| 6.1     | 7        | 4.22%   |
| 5.8     | 7        | 4.22%   |
| 4.18    | 6        | 3.61%   |
| 4.15    | 6        | 3.61%   |
| 5.3     | 5        | 3.01%   |
| 5.13    | 5        | 3.01%   |
| 5.11    | 5        | 3.01%   |
| 6.6     | 4        | 2.41%   |
| 6.4     | 4        | 2.41%   |
| 6.0     | 4        | 2.41%   |
| 4.9     | 4        | 2.41%   |
| 6.7     | 3        | 1.81%   |
| 5.9     | 3        | 1.81%   |
| 5.5     | 3        | 1.81%   |
| 5.18    | 3        | 1.81%   |
| 5.17    | 3        | 1.81%   |
| 5.6     | 2        | 1.2%    |
| 5.14    | 2        | 1.2%    |
| 5.0     | 2        | 1.2%    |
| 4.19    | 2        | 1.2%    |
| 6.8     | 1        | 0.6%    |
| 6.3     | 1        | 0.6%    |
| 5.7     | 1        | 0.6%    |
| 4.20    | 1        | 0.6%    |
| 4.1     | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 128      | 98.46%  |
| i686   | 2        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 65       | 45.45%  |
| KDE5       | 34       | 23.78%  |
| Unknown    | 15       | 10.49%  |
| XFCE       | 8        | 5.59%   |
| KDE        | 5        | 3.5%    |
| Budgie     | 4        | 2.8%    |
| KDE4       | 3        | 2.1%    |
| X-Cinnamon | 2        | 1.4%    |
| Unity      | 2        | 1.4%    |
| Deepin     | 2        | 1.4%    |
| MATE       | 1        | 0.7%    |
| DDE        | 1        | 0.7%    |
| Cinnamon   | 1        | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 94       | 69.63%  |
| Wayland | 29       | 21.48%  |
| Unknown | 10       | 7.41%   |
| Tty     | 2        | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 68       | 48.23%  |
| SDDM    | 27       | 19.15%  |
| GDM3    | 23       | 16.31%  |
| GDM     | 11       | 7.8%    |
| LightDM | 6        | 4.26%   |
| TDM     | 3        | 2.13%   |
| KDM     | 3        | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 94       | 68.12%  |
| Unknown | 18       | 13.04%  |
| ar_SA   | 10       | 7.25%   |
| ar_EG   | 6        | 4.35%   |
| en_GB   | 2        | 1.45%   |
| ar_AE   | 2        | 1.45%   |
| ru_RU   | 1        | 0.72%   |
| nl_BE   | 1        | 0.72%   |
| en_IL   | 1        | 0.72%   |
| en_AU   | 1        | 0.72%   |
| de_DE   | 1        | 0.72%   |
| ar_KW   | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 80       | 57.55%  |
| EFI  | 59       | 42.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 88       | 65.19%  |
| Btrfs   | 15       | 11.11%  |
| Overlay | 12       | 8.89%   |
| Tmpfs   | 11       | 8.15%   |
| Unknown | 6        | 4.44%   |
| Xfs     | 2        | 1.48%   |
| Ext2    | 1        | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 75       | 53.57%  |
| GPT     | 55       | 39.29%  |
| MBR     | 10       | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 79.1%   |
| Yes       | 28       | 20.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 60.87%  |
| Yes       | 54       | 39.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell                                 | 25       | 19.23%  |
| Gigabyte Technology                  | 24       | 18.46%  |
| ASUSTek Computer                     | 23       | 17.69%  |
| MSI                                  | 16       | 12.31%  |
| Hewlett-Packard                      | 11       | 8.46%   |
| ASRock                               | 9        | 6.92%   |
| Lenovo                               | 7        | 5.38%   |
| Unknown                              | 4        | 3.08%   |
| Pegatron                             | 2        | 1.54%   |
| Intel                                | 2        | 1.54%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.77%   |
| OEM                                  | 1        | 0.77%   |
| Medion                               | 1        | 0.77%   |
| Huanan                               | 1        | 0.77%   |
| Fujitsu Siemens                      | 1        | 0.77%   |
| DJI                                  | 1        | 0.77%   |
| Biostar                              | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 5        | 3.85%   |
| Dell OptiPlex 9020                          | 4        | 3.08%   |
| Unknown                                     | 4        | 3.08%   |
| MSI MS-7C90                                 | 2        | 1.54%   |
| Lenovo Legion T5 26IOB6 90RT00TVKS          | 2        | 1.54%   |
| HP Compaq Elite 8300 SFF                    | 2        | 1.54%   |
| Gigabyte H81M-S2PH                          | 2        | 1.54%   |
| Dell OptiPlex 9010                          | 2        | 1.54%   |
| Dell OptiPlex 790                           | 2        | 1.54%   |
| Dell OptiPlex 7050                          | 2        | 1.54%   |
| Dell OptiPlex 7010                          | 2        | 1.54%   |
| Dell OptiPlex 3010                          | 2        | 1.54%   |
| ASUS TUF Gaming X570-PLUS                   | 2        | 1.54%   |
| Shenzhen Meigao Electronic Equipment HX99G  | 1        | 0.77%   |
| Pegatron h8-1400ex                          | 1        | 0.77%   |
| Pegatron Compaq dx7500 Microtower           | 1        | 0.77%   |
| OEM B250                                    | 1        | 0.77%   |
| MSI MS-7E25                                 | 1        | 0.77%   |
| MSI MS-7D20                                 | 1        | 0.77%   |
| MSI MS-7C91                                 | 1        | 0.77%   |
| MSI MS-7C75                                 | 1        | 0.77%   |
| MSI MS-7C56                                 | 1        | 0.77%   |
| MSI MS-7C37                                 | 1        | 0.77%   |
| MSI MS-7B84                                 | 1        | 0.77%   |
| MSI MS-7B46                                 | 1        | 0.77%   |
| MSI MS-7B19                                 | 1        | 0.77%   |
| MSI MS-7A70                                 | 1        | 0.77%   |
| MSI MS-7758                                 | 1        | 0.77%   |
| MSI MS-7529                                 | 1        | 0.77%   |
| MSI Elite 7100 Microtower PC                | 1        | 0.77%   |
| MSI Compaq dx2390 Microtower                | 1        | 0.77%   |
| Medion MS-7797                              | 1        | 0.77%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE00A7AX | 1        | 0.77%   |
| Lenovo ThinkCentre M93p 10A8S3C100          | 1        | 0.77%   |
| Lenovo ThinkCentre M72z 3535A48             | 1        | 0.77%   |
| Lenovo ThinkCentre M710t 10MAS1FT00         | 1        | 0.77%   |
| Lenovo ThinkCentre E73 10AS0040AX           | 1        | 0.77%   |
| Intel DP55WB AAE64798-206                   | 1        | 0.77%   |
| Intel BTC-T37                               | 1        | 0.77%   |
| Huanan X99-F8                               | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 21       | 16.15%  |
| ASUS TUF                                   | 6        | 4.62%   |
| Lenovo ThinkCentre                         | 5        | 3.85%   |
| ASUS All                                   | 5        | 3.85%   |
| ASUS PRIME                                 | 4        | 3.08%   |
| Unknown                                    | 4        | 3.08%   |
| HP EliteDesk                               | 3        | 2.31%   |
| HP Compaq                                  | 3        | 2.31%   |
| ASUS ROG                                   | 3        | 2.31%   |
| MSI MS-7C90                                | 2        | 1.54%   |
| Lenovo Legion                              | 2        | 1.54%   |
| Gigabyte H81M-S2PH                         | 2        | 1.54%   |
| Dell Vostro                                | 2        | 1.54%   |
| Dell Precision                             | 2        | 1.54%   |
| ASRock X570                                | 2        | 1.54%   |
| Shenzhen Meigao Electronic Equipment HX99G | 1        | 0.77%   |
| Pegatron h8-1400ex                         | 1        | 0.77%   |
| Pegatron Compaq                            | 1        | 0.77%   |
| OEM B250                                   | 1        | 0.77%   |
| MSI MS-7E25                                | 1        | 0.77%   |
| MSI MS-7D20                                | 1        | 0.77%   |
| MSI MS-7C91                                | 1        | 0.77%   |
| MSI MS-7C75                                | 1        | 0.77%   |
| MSI MS-7C56                                | 1        | 0.77%   |
| MSI MS-7C37                                | 1        | 0.77%   |
| MSI MS-7B84                                | 1        | 0.77%   |
| MSI MS-7B46                                | 1        | 0.77%   |
| MSI MS-7B19                                | 1        | 0.77%   |
| MSI MS-7A70                                | 1        | 0.77%   |
| MSI MS-7758                                | 1        | 0.77%   |
| MSI MS-7529                                | 1        | 0.77%   |
| MSI Elite                                  | 1        | 0.77%   |
| MSI Compaq                                 | 1        | 0.77%   |
| Medion MS-7797                             | 1        | 0.77%   |
| Intel DP55WB                               | 1        | 0.77%   |
| Intel BTC-T37                              | 1        | 0.77%   |
| Huanan X99-F8                              | 1        | 0.77%   |
| HP Z440                                    | 1        | 0.77%   |
| HP ProDesk                                 | 1        | 0.77%   |
| HP Pavilion                                | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 16       | 12.31%  |
| 2012 | 16       | 12.31%  |
| 2020 | 12       | 9.23%   |
| 2021 | 11       | 8.46%   |
| 2019 | 11       | 8.46%   |
| 2014 | 10       | 7.69%   |
| 2013 | 9        | 6.92%   |
| 2015 | 7        | 5.38%   |
| 2017 | 6        | 4.62%   |
| 2016 | 6        | 4.62%   |
| 2010 | 6        | 4.62%   |
| 2011 | 5        | 3.85%   |
| 2023 | 4        | 3.08%   |
| 2009 | 3        | 2.31%   |
| 2008 | 3        | 2.31%   |
| 2022 | 2        | 1.54%   |
| 2007 | 2        | 1.54%   |
| 2006 | 1        | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 130      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 124      | 94.66%  |
| Enabled  | 7        | 5.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 26.87%  |
| 32.01-64.0  | 25       | 18.66%  |
| 4.01-8.0    | 23       | 17.16%  |
| 8.01-16.0   | 23       | 17.16%  |
| 3.01-4.0    | 8        | 5.97%   |
| 64.01-256.0 | 6        | 4.48%   |
| 1.01-2.0    | 6        | 4.48%   |
| 24.01-32.0  | 5        | 3.73%   |
| 2.01-3.0    | 1        | 0.75%   |
| 0.51-1.0    | 1        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 43       | 28.29%  |
| 4.01-8.0   | 34       | 22.37%  |
| 2.01-3.0   | 27       | 17.76%  |
| 3.01-4.0   | 26       | 17.11%  |
| 8.01-16.0  | 10       | 6.58%   |
| 0.51-1.0   | 9        | 5.92%   |
| 16.01-24.0 | 3        | 1.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 40%     |
| 2      | 36       | 24.83%  |
| 3      | 28       | 19.31%  |
| 4      | 13       | 8.97%   |
| 5      | 5        | 3.45%   |
| 6      | 4        | 2.76%   |
| 7      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 65.91%  |
| Yes       | 45       | 34.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 130      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 63.36%  |
| No        | 48       | 36.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 55.64%  |
| Yes       | 59       | 44.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Saudi Arabia | 130      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Riyadh               | 52       | 35.62%  |
| Jeddah               | 32       | 21.92%  |
| Makkah               | 16       | 10.96%  |
| Dammam               | 11       | 7.53%   |
| Medina               | 10       | 6.85%   |
| Khobar               | 6        | 4.11%   |
| Al Qatif             | 4        | 2.74%   |
| Ta'if                | 3        | 2.05%   |
| Dhahran              | 3        | 2.05%   |
| Baq`a' ash Sharqiyah | 2        | 1.37%   |
| Shaqra               | 1        | 0.68%   |
| Jubail               | 1        | 0.68%   |
| Buraidah             | 1        | 0.68%   |
| Bisha                | 1        | 0.68%   |
| At Tuwal             | 1        | 0.68%   |
| Al Faruq             | 1        | 0.68%   |
| Abha                 | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 67       | 118    | 26.17%  |
| Seagate                     | 38       | 63     | 14.84%  |
| Kingston                    | 35       | 62     | 13.67%  |
| Samsung Electronics         | 22       | 47     | 8.59%   |
| Toshiba                     | 14       | 16     | 5.47%   |
| SanDisk                     | 10       | 10     | 3.91%   |
| Crucial                     | 9        | 11     | 3.52%   |
| Team                        | 6        | 6      | 2.34%   |
| Phison Electronics          | 5        | 8      | 1.95%   |
| Lexar                       | 5        | 5      | 1.95%   |
| Silicon Motion              | 4        | 5      | 1.56%   |
| Phison                      | 4        | 4      | 1.56%   |
| Hitachi                     | 4        | 5      | 1.56%   |
| Unknown                     | 3        | 6      | 1.17%   |
| PNY                         | 2        | 3      | 0.78%   |
| Micron/Crucial Technology   | 2        | 2      | 0.78%   |
| Kingston Technology Company | 2        | 3      | 0.78%   |
| Intel                       | 2        | 2      | 0.78%   |
| HS-SSD-C100                 | 2        | 3      | 0.78%   |
| HGST                        | 2        | 5      | 0.78%   |
| Hewlett-Packard             | 2        | 3      | 0.78%   |
| China                       | 2        | 2      | 0.78%   |
| Unknown                     | 2        | 2      | 0.78%   |
| WD MediaMax                 | 1        | 1      | 0.39%   |
| Transcend                   | 1        | 1      | 0.39%   |
| SPCC Sol                    | 1        | 1      | 0.39%   |
| SPCC                        | 1        | 2      | 0.39%   |
| SK hynix                    | 1        | 4      | 0.39%   |
| Maxtor                      | 1        | 1      | 0.39%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.39%   |
| KESU                        | 1        | 1      | 0.39%   |
| JMicron Technology          | 1        | 1      | 0.39%   |
| Hoodisk                     | 1        | 1      | 0.39%   |
| Fanxiang                    | 1        | 1      | 0.39%   |
| Corsair                     | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 10       | 3.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 7        | 2.33%   |
| Seagate ST500DM002-1BD142 500GB                    | 7        | 2.33%   |
| Kingston SA400S37480G 480GB SSD                    | 7        | 2.33%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 4        | 1.33%   |
| WDC WD10EZEX-75WN4A1 1TB                           | 4        | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4        | 1.33%   |
| Toshiba DT01ACA050 500GB                           | 3        | 1%      |
| Samsung SSD 860 EVO 1TB                            | 3        | 1%      |
| Kingston SA400S37960G 960GB SSD                    | 3        | 1%      |
| Kingston SA400S37120G 120GB SSD                    | 3        | 1%      |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 2        | 0.67%   |
| WDC WD4005FZBX-00K5WB0 4TB                         | 2        | 0.67%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 2        | 0.67%   |
| WDC WD10EZRX-00A8LB0 1TB                           | 2        | 0.67%   |
| WDC WD10EARX-00N0YB0 1TB                           | 2        | 0.67%   |
| WDC WD10EADS-00M2B0 1TB                            | 2        | 0.67%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 2        | 0.67%   |
| Toshiba MQ01ABD100 1TB                             | 2        | 0.67%   |
| Toshiba MK1059GSM 1TB                              | 2        | 0.67%   |
| Toshiba DT01ACA100 1TB                             | 2        | 0.67%   |
| Team T253X2001T 1024GB SSD                         | 2        | 0.67%   |
| Silicon Motion NVMe SSD Drive 2TB                  | 2        | 0.67%   |
| Seagate ST2000LM007-1R8174 2TB                     | 2        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2        | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB                     | 2        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB                     | 2        | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB                     | 2        | 0.67%   |
| Samsung SSD 960 EVO 250GB                          | 2        | 0.67%   |
| Samsung SSD 860 EVO 500GB                          | 2        | 0.67%   |
| Samsung SSD 860 EVO 250GB                          | 2        | 0.67%   |
| Samsung NVMe SSD Drive 500GB                       | 2        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2        | 0.67%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 2        | 0.67%   |
| Phison E12 NVMe Controller 2TB                     | 2        | 0.67%   |
| Lexar 128GB SSD                                    | 2        | 0.67%   |
| Kingston SMS200S3240G 240GB SSD                    | 2        | 0.67%   |
| Kingston SH103S3120G 120GB SSD                     | 2        | 0.67%   |
| Hitachi HTS545050A7E380 500GB                      | 2        | 0.67%   |
| Crucial CT500MX500SSD1 500GB                       | 2        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 62       | 108    | 49.6%   |
| Seagate             | 38       | 63     | 30.4%   |
| Toshiba             | 14       | 16     | 11.2%   |
| Hitachi             | 4        | 5      | 3.2%    |
| HGST                | 2        | 5      | 1.6%    |
| Unknown             | 1        | 3      | 0.8%    |
| Samsung Electronics | 1        | 2      | 0.8%    |
| Maxtor              | 1        | 1      | 0.8%    |
| KESU                | 1        | 1      | 0.8%    |
| JMicron Technology  | 1        | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 31       | 54     | 38.27%  |
| Samsung Electronics | 12       | 23     | 14.81%  |
| Crucial             | 9        | 11     | 11.11%  |
| SanDisk             | 5        | 5      | 6.17%   |
| WDC                 | 4        | 7      | 4.94%   |
| Team                | 4        | 4      | 4.94%   |
| Lexar               | 4        | 4      | 4.94%   |
| PNY                 | 2        | 3      | 2.47%   |
| China               | 2        | 2      | 2.47%   |
| Unknown             | 2        | 2      | 2.47%   |
| Transcend           | 1        | 1      | 1.23%   |
| SPCC Sol            | 1        | 1      | 1.23%   |
| SPCC                | 1        | 2      | 1.23%   |
| Hoodisk             | 1        | 1      | 1.23%   |
| Hewlett-Packard     | 1        | 2      | 1.23%   |
| Corsair             | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 94       | 205    | 45.85%  |
| SSD     | 68       | 123    | 33.17%  |
| NVMe    | 39       | 74     | 19.02%  |
| Unknown | 3        | 4      | 1.46%   |
| MMC     | 1        | 2      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 118      | 320    | 71.95%  |
| NVMe | 39       | 73     | 23.78%  |
| SAS  | 6        | 13     | 3.66%   |
| MMC  | 1        | 2      | 0.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 79       | 169    | 46.2%   |
| 0.51-1.0   | 55       | 104    | 32.16%  |
| 1.01-2.0   | 21       | 32     | 12.28%  |
| 3.01-4.0   | 11       | 14     | 6.43%   |
| 2.01-3.0   | 4        | 5      | 2.34%   |
| 4.01-10.0  | 1        | 4      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 32       | 22.22%  |
| 251-500        | 31       | 21.53%  |
| 101-250        | 28       | 19.44%  |
| 1001-2000      | 13       | 9.03%   |
| More than 3000 | 10       | 6.94%   |
| 1-20           | 9        | 6.25%   |
| 2001-3000      | 8        | 5.56%   |
| 51-100         | 7        | 4.86%   |
| 21-50          | 4        | 2.78%   |
| Unknown        | 2        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 53       | 33.33%  |
| 21-50          | 30       | 18.87%  |
| 101-250        | 19       | 11.95%  |
| 251-500        | 15       | 9.43%   |
| 51-100         | 15       | 9.43%   |
| 501-1000       | 11       | 6.92%   |
| 1001-2000      | 6        | 3.77%   |
| More than 3000 | 4        | 2.52%   |
| 2001-3000      | 4        | 2.52%   |
| Unknown        | 2        | 1.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Unknown                         | 2        | 2      | 11.11%  |
| WDC WD5000AAKS-00WWPA0 500GB    | 1        | 1      | 5.56%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1        | 1      | 5.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 1      | 5.56%   |
| WDC WD1600AAJS-60B4A0 160GB     | 1        | 1      | 5.56%   |
| WDC WD10PURZ-85U8XY0 1TB        | 1        | 1      | 5.56%   |
| WDC WD10EUCX-73YZ1Y0 1TB        | 1        | 1      | 5.56%   |
| WDC WD Green 2.5 480GB SSD      | 1        | 1      | 5.56%   |
| Seagate ST9320325AS 320GB       | 1        | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 5.56%   |
| Seagate ST2000DM001-1CH164 2TB  | 1        | 1      | 5.56%   |
| Seagate ST1000DM003-9YN162 1TB  | 1        | 1      | 5.56%   |
| SanDisk SSD PLUS 480GB          | 1        | 1      | 5.56%   |
| Kingston SMS200S3240G 240GB SSD | 1        | 1      | 5.56%   |
| Kingston SA400S37480G 480GB SSD | 1        | 1      | 5.56%   |
| Hitachi HDS721032CLA362 320GB   | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 7        | 7      | 41.18%  |
| Seagate  | 4        | 5      | 23.53%  |
| Kingston | 2        | 2      | 11.76%  |
| Unknown  | 2        | 2      | 11.76%  |
| SanDisk  | 1        | 1      | 5.88%   |
| Hitachi  | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 6      | 54.55%  |
| Seagate | 4        | 5      | 36.36%  |
| Hitachi | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 69.23%  |
| SSD  | 4        | 6      | 30.77%  |

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
| Detected | 92       | 283    | 62.16%  |
| Works    | 44       | 107    | 29.73%  |
| Malfunc  | 12       | 18     | 8.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 107      | 58.15%  |
| AMD                         | 22       | 11.96%  |
| Samsung Electronics         | 10       | 5.43%   |
| Phison Electronics          | 8        | 4.35%   |
| SanDisk                     | 7        | 3.8%    |
| Kingston Technology Company | 7        | 3.8%    |
| ASMedia Technology          | 7        | 3.8%    |
| Silicon Motion              | 5        | 2.72%   |
| Micron/Crucial Technology   | 2        | 1.09%   |
| VIA Technologies            | 1        | 0.54%   |
| SK hynix                    | 1        | 0.54%   |
| MAXIO Technology (Hangzhou) | 1        | 0.54%   |
| Marvell Technology Group    | 1        | 0.54%   |
| LSI Logic / Symbios Logic   | 1        | 0.54%   |
| JMicron Technology          | 1        | 0.54%   |
| INNOGRIT                    | 1        | 0.54%   |
| Hosin Global Electronics    | 1        | 0.54%   |
| ADATA Technology            | 1        | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 6.67%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 5.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 4.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.81%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.9%    |
| Phison E12 NVMe Controller                                                              | 4        | 1.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 1.9%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 1.9%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.43%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 3        | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.95%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.95%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.95%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2        | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2        | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 0.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.95%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 102      | 58.62%  |
| NVMe | 39       | 22.41%  |
| IDE  | 18       | 10.34%  |
| RAID | 15       | 8.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 108      | 83.08%  |
| AMD    | 22       | 16.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 4.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 3.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 2.29%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 2.29%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 2.29%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 2.29%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.29%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 2.29%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.53%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.53%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.53%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 1.53%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 1.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.53%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.53%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.53%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2        | 1.53%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.53%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 1.53%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.53%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 1.53%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.53%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.53%   |
| Intel Xeon E-2286M CPU @ 2.40GHz            | 1        | 0.76%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1        | 0.76%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.76%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.76%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.76%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1        | 0.76%   |
| Intel Core i9-7900X CPU @ 3.30GHz           | 1        | 0.76%   |
| Intel Core i9-14900K                        | 1        | 0.76%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 1        | 0.76%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 35       | 26.72%  |
| Intel Core i5           | 30       | 22.9%   |
| Intel Core i3           | 11       | 8.4%    |
| Other                   | 8        | 6.11%   |
| AMD Ryzen 5             | 8        | 6.11%   |
| AMD Ryzen 9             | 7        | 5.34%   |
| Intel Core 2 Duo        | 6        | 4.58%   |
| Intel Xeon              | 5        | 3.82%   |
| Intel Core i9           | 4        | 3.05%   |
| Intel Celeron           | 4        | 3.05%   |
| AMD Ryzen 7             | 4        | 3.05%   |
| AMD FX                  | 3        | 2.29%   |
| Intel Pentium Silver    | 1        | 0.76%   |
| Intel Pentium Dual-Core | 1        | 0.76%   |
| Intel Pentium 4         | 1        | 0.76%   |
| Intel Core 2 Quad       | 1        | 0.76%   |
| Intel Core 2            | 1        | 0.76%   |
| AMD A4                  | 1        | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 63       | 48.09%  |
| 6      | 22       | 16.79%  |
| 8      | 15       | 11.45%  |
| 2      | 15       | 11.45%  |
| 12     | 4        | 3.05%   |
| 1      | 4        | 3.05%   |
| 16     | 3        | 2.29%   |
| 10     | 3        | 2.29%   |
| 24     | 2        | 1.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 99.23%  |
| 2      | 1        | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 59.85%  |
| 1      | 53       | 40.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 128      | 98.46%  |
| Unknown        | 2        | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 42.47%  |
| 0x306c3    | 13       | 8.9%    |
| 0x306a9    | 9        | 6.16%   |
| 0x906e9    | 6        | 4.11%   |
| 0x206a7    | 6        | 4.11%   |
| 0x1067a    | 6        | 4.11%   |
| 0x906ea    | 4        | 2.74%   |
| 0xa0653    | 3        | 2.05%   |
| 0x906ed    | 3        | 2.05%   |
| 0xa0655    | 2        | 1.37%   |
| 0x506c9    | 2        | 1.37%   |
| 0x106e5    | 2        | 1.37%   |
| 0x0a201016 | 2        | 1.37%   |
| 0x08701021 | 2        | 1.37%   |
| 0x0800820d | 2        | 1.37%   |
| 0x06000852 | 2        | 1.37%   |
| 0xf64      | 1        | 0.68%   |
| 0xb0671    | 1        | 0.68%   |
| 0xa0652    | 1        | 0.68%   |
| 0x906ec    | 1        | 0.68%   |
| 0x906eb    | 1        | 0.68%   |
| 0x906c0    | 1        | 0.68%   |
| 0x90675    | 1        | 0.68%   |
| 0x806ea    | 1        | 0.68%   |
| 0x6fb      | 1        | 0.68%   |
| 0x6f2      | 1        | 0.68%   |
| 0x506e3    | 1        | 0.68%   |
| 0x306f2    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x206d7    | 1        | 0.68%   |
| 0x106a4    | 1        | 0.68%   |
| 0x10661    | 1        | 0.68%   |
| 0x0a404102 | 1        | 0.68%   |
| 0x0a20102b | 1        | 0.68%   |
| 0x0a201009 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 23       | 17.42%  |
| Haswell          | 20       | 15.15%  |
| IvyBridge        | 15       | 11.36%  |
| Zen 3            | 9        | 6.82%   |
| SandyBridge      | 9        | 6.82%   |
| CometLake        | 8        | 6.06%   |
| Penryn           | 7        | 5.3%    |
| Unknown          | 7        | 5.3%    |
| Zen 2            | 5        | 3.79%   |
| Skylake          | 5        | 3.79%   |
| Zen+             | 4        | 3.03%   |
| Piledriver       | 4        | 3.03%   |
| Nehalem          | 4        | 3.03%   |
| Core             | 3        | 2.27%   |
| Icelake          | 2        | 1.52%   |
| Goldmont         | 2        | 1.52%   |
| Alderlake Hybrid | 2        | 1.52%   |
| Tremont          | 1        | 0.76%   |
| NetBurst         | 1        | 0.76%   |
| Broadwell        | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 64       | 43.54%  |
| Intel            | 57       | 38.78%  |
| AMD              | 25       | 17.01%  |
| VIA Technologies | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 5.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 4%      |
| Intel HD Graphics 630                                                       | 6        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 2.67%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 2.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 2%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2%      |
| Intel HD Graphics 530                                                       | 3        | 2%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 2%      |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.33%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.33%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.33%   |
| Intel HD Graphics 500                                                       | 2        | 1.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.33%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1        | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.67%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.67%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.67%   |
| Nvidia GT200GL [Quadro FX 5800]                                             | 1        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 56       | 42.11%  |
| 1 x Intel      | 43       | 32.33%  |
| 1 x AMD        | 20       | 15.04%  |
| Intel + Nvidia | 7        | 5.26%   |
| Intel + AMD    | 4        | 3.01%   |
| 2 x AMD        | 1        | 0.75%   |
| 1 x VIA        | 1        | 0.75%   |
| AMD + Nvidia   | 1        | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 89       | 65.44%  |
| Proprietary | 42       | 30.88%  |
| Unknown     | 5        | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 51.8%   |
| 7.01-8.0   | 17       | 12.23%  |
| 3.01-4.0   | 17       | 12.23%  |
| 1.01-2.0   | 14       | 10.07%  |
| 8.01-16.0  | 6        | 4.32%   |
| 0.51-1.0   | 6        | 4.32%   |
| 0.01-0.5   | 4        | 2.88%   |
| 2.01-3.0   | 2        | 1.44%   |
| 5.01-6.0   | 1        | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 25       | 18.94%  |
| Dell                 | 23       | 17.42%  |
| BenQ                 | 16       | 12.12%  |
| Goldstar             | 10       | 7.58%   |
| Hewlett-Packard      | 9        | 6.82%   |
| Lenovo               | 5        | 3.79%   |
| Acer                 | 5        | 3.79%   |
| Unknown              | 4        | 3.03%   |
| Sony                 | 3        | 2.27%   |
| Sharp                | 3        | 2.27%   |
| AOC                  | 3        | 2.27%   |
| Ancor Communications | 2        | 1.52%   |
| WIT                  | 1        | 0.76%   |
| ViewSonic            | 1        | 0.76%   |
| Unknown (XXX)        | 1        | 0.76%   |
| Tech Concepts        | 1        | 0.76%   |
| TCL                  | 1        | 0.76%   |
| Sun                  | 1        | 0.76%   |
| SKY                  | 1        | 0.76%   |
| SHC                  | 1        | 0.76%   |
| RTK                  | 1        | 0.76%   |
| RGT                  | 1        | 0.76%   |
| Pioneer              | 1        | 0.76%   |
| Philips              | 1        | 0.76%   |
| MStar                | 1        | 0.76%   |
| Mi                   | 1        | 0.76%   |
| LG Electronics       | 1        | 0.76%   |
| Lenovo Group Limited | 1        | 0.76%   |
| Konka                | 1        | 0.76%   |
| HUAWEI               | 1        | 0.76%   |
| Gigabyte Technology  | 1        | 0.76%   |
| GDH                  | 1        | 0.76%   |
| eMachines            | 1        | 0.76%   |
| BOE                  | 1        | 0.76%   |
| ASUSTek Computer     | 1        | 0.76%   |
| Unknown              | 1        | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 4        | 2.78%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 3        | 2.08%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 2        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 2        | 1.39%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch              | 2        | 1.39%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 2        | 1.39%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 2        | 1.39%   |
| Dell P2312H DEL4076 1920x1080 510x287mm 23.0-inch                     | 2        | 1.39%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 2        | 1.39%   |
| WIT DVI WIT00FA 2560x1600 670x430mm 31.3-inch                         | 1        | 0.69%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch         | 1        | 0.69%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                      | 1        | 0.69%   |
| Unknown LCD Monitor SCEI MONITOR 1920x1080                            | 1        | 0.69%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.69%   |
| Unknown LCD Monitor AAA HDTV 1366x768                                 | 1        | 0.69%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch        | 1        | 0.69%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 1        | 0.69%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1        | 0.69%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1        | 0.69%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                         | 1        | 0.69%   |
| Sony TV *00 SNY7C04 3840x2160 1218x685mm 55.0-inch                    | 1        | 0.69%   |
| Sony LCD Monitor TV  *00 3840x2160                                    | 1        | 0.69%   |
| SKY TV-PHILCO SKY0104 1920x1080 885x498mm 40.0-inch                   | 1        | 0.69%   |
| SHC SHARP SHC0030 3840x2160 708x398mm 32.0-inch                       | 1        | 0.69%   |
| Sharp SHARP SHC0030 3840x2160 708x398mm 32.0-inch                     | 1        | 0.69%   |
| Sharp LCD SHP4176 1920x1080 640x360mm 28.9-inch                       | 1        | 0.69%   |
| Sharp LCD Monitor HDMI 1920x1080                                      | 1        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.69%   |
| Samsung Electronics T27C370 SAM0ADC 1920x1080 598x336mm 27.0-inch     | 1        | 0.69%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 0.69%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch    | 1        | 0.69%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch    | 1        | 0.69%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch  | 1        | 0.69%   |
| Samsung Electronics S24C300 SAM0A2A 1920x1080 521x293mm 23.5-inch     | 1        | 0.69%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 0.69%   |
| Samsung Electronics S22D300 SAM0B3C 1920x1080 477x268mm 21.5-inch     | 1        | 0.69%   |
| Samsung Electronics LS49AG95 SAM71AC 3840x1080 1193x336mm 48.8-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SMBX2450 3840x1080                    | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SMBX2450                              | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 66       | 50.38%  |
| 3840x2160 (4K)     | 22       | 16.79%  |
| 1366x768 (WXGA)    | 11       | 8.4%    |
| 2560x1440 (QHD)    | 9        | 6.87%   |
| 2560x1080          | 4        | 3.05%   |
| 3440x1440          | 3        | 2.29%   |
| 1600x900 (HD+)     | 3        | 2.29%   |
| 3840x1080          | 2        | 1.53%   |
| 1440x900 (WXGA+)   | 2        | 1.53%   |
| 1280x1024 (SXGA)   | 2        | 1.53%   |
| Unknown            | 2        | 1.53%   |
| 7040x1440          | 1        | 0.76%   |
| 3840x1600          | 1        | 0.76%   |
| 2560x1600          | 1        | 0.76%   |
| 1920x1200 (WUXGA)  | 1        | 0.76%   |
| 1680x1050 (WSXGA+) | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 18       | 13.24%  |
| 27      | 17       | 12.5%   |
| 23      | 16       | 11.76%  |
| Unknown | 13       | 9.56%   |
| 31      | 10       | 7.35%   |
| 21      | 10       | 7.35%   |
| 18      | 9        | 6.62%   |
| 54      | 6        | 4.41%   |
| 34      | 6        | 4.41%   |
| 84      | 5        | 3.68%   |
| 32      | 4        | 2.94%   |
| 19      | 4        | 2.94%   |
| 52      | 3        | 2.21%   |
| 22      | 2        | 1.47%   |
| 17      | 2        | 1.47%   |
| 72      | 1        | 0.74%   |
| 65      | 1        | 0.74%   |
| 57      | 1        | 0.74%   |
| 48      | 1        | 0.74%   |
| 46      | 1        | 0.74%   |
| 40      | 1        | 0.74%   |
| 37      | 1        | 0.74%   |
| 29      | 1        | 0.74%   |
| 25      | 1        | 0.74%   |
| 20      | 1        | 0.74%   |
| 16      | 1        | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 47       | 35.34%  |
| 401-500     | 26       | 19.55%  |
| 601-700     | 13       | 9.77%   |
| 1001-1500   | 13       | 9.77%   |
| Unknown     | 13       | 9.77%   |
| 701-800     | 10       | 7.52%   |
| 1501-2000   | 6        | 4.51%   |
| 801-900     | 2        | 1.5%    |
| 301-350     | 2        | 1.5%    |
| 351-400     | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 96       | 75.59%  |
| Unknown | 13       | 10.24%  |
| 21/9    | 8        | 6.3%    |
| 16/10   | 7        | 5.51%   |
| 5/4     | 2        | 1.57%   |
| 32/9    | 1        | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 26.87%  |
| 351-500        | 20       | 14.93%  |
| 301-350        | 18       | 13.43%  |
| More than 1000 | 17       | 12.69%  |
| Unknown        | 13       | 9.7%    |
| 141-150        | 11       | 8.21%   |
| 151-200        | 8        | 5.97%   |
| 251-300        | 6        | 4.48%   |
| 501-1000       | 4        | 2.99%   |
| 101-110        | 1        | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 83       | 62.88%  |
| 101-120 | 17       | 12.88%  |
| Unknown | 13       | 9.85%   |
| 1-50    | 11       | 8.33%   |
| 121-160 | 8        | 6.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 81.95%  |
| 2     | 18       | 13.53%  |
| 0     | 4        | 3.01%   |
| 3     | 2        | 1.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 77       | 36.49%  |
| Realtek Semiconductor           | 68       | 32.23%  |
| Broadcom                        | 10       | 4.74%   |
| TP-Link                         | 9        | 4.27%   |
| Qualcomm Atheros                | 9        | 4.27%   |
| Ralink Technology               | 8        | 3.79%   |
| Samsung Electronics             | 5        | 2.37%   |
| Ralink                          | 3        | 1.42%   |
| MediaTek                        | 3        | 1.42%   |
| Microsoft                       | 2        | 0.95%   |
| Linksys                         | 2        | 0.95%   |
| D-Link                          | 2        | 0.95%   |
| Xiaomi                          | 1        | 0.47%   |
| Wilocity                        | 1        | 0.47%   |
| VIA Technologies                | 1        | 0.47%   |
| T & A Mobile Phones             | 1        | 0.47%   |
| Qualcomm Technologies           | 1        | 0.47%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| Marvell Technology Group        | 1        | 0.47%   |
| Huawei Technologies             | 1        | 0.47%   |
| Edimax Technology               | 1        | 0.47%   |
| DisplayLink                     | 1        | 0.47%   |
| Conexant Systems                | 1        | 0.47%   |
| Belkin Components               | 1        | 0.47%   |
| Apple                           | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 47       | 19.42%  |
| Intel Wi-Fi 6 AX200                                                    | 12       | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11       | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 4.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 7        | 2.89%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 2.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 7        | 2.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 2.48%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5        | 2.07%   |
| Intel Ethernet Controller I225-V                                       | 5        | 2.07%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 2.07%   |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 2.07%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 1.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 3        | 1.24%   |
| Intel Wireless 3165                                                    | 3        | 1.24%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3        | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 1.24%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3        | 1.24%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2        | 0.83%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 2        | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.83%   |
| Intel Wireless 7260                                                    | 2        | 0.83%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.83%   |
| Intel 82583V Gigabit Network Connection                                | 2        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2        | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.41%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                             | 1        | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.41%   |
| TP-Link 802.11ac NIC                                                   | 1        | 0.41%   |
| T & A Mobile Phones Alcatel 1S                                         | 1        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 29       | 30.85%  |
| Realtek Semiconductor           | 18       | 19.15%  |
| TP-Link                         | 9        | 9.57%   |
| Ralink Technology               | 8        | 8.51%   |
| Qualcomm Atheros                | 8        | 8.51%   |
| Broadcom                        | 5        | 5.32%   |
| Ralink                          | 3        | 3.19%   |
| MediaTek                        | 3        | 3.19%   |
| Microsoft                       | 2        | 2.13%   |
| Linksys                         | 2        | 2.13%   |
| D-Link                          | 2        | 2.13%   |
| Wilocity                        | 1        | 1.06%   |
| Qualcomm Technologies           | 1        | 1.06%   |
| Qualcomm Atheros Communications | 1        | 1.06%   |
| Edimax Technology               | 1        | 1.06%   |
| Belkin Components               | 1        | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 12       | 12.77%  |
| Ralink RT2870/RT3070 Wireless Adapter                               | 7        | 7.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 4        | 4.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 4.26%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 3        | 3.19%   |
| Intel Wireless 3165                                                 | 3        | 3.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 3        | 3.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 3        | 3.19%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 3        | 3.19%   |
| TP-Link 802.11ac WLAN Adapter                                       | 2        | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2        | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 2        | 2.13%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 2        | 2.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 2.13%   |
| Intel Wireless 7260                                                 | 2        | 2.13%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 1        | 1.06%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 1.06%   |
| TP-Link 802.11ac NIC                                                | 1        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.06%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 1.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.06%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 1.06%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 1.06%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 1.06%   |
| Realtek RTL8187 Wireless Adapter                                    | 1        | 1.06%   |
| Realtek 802.11ac NIC                                                | 1        | 1.06%   |
| Ralink RT2501/RT2573 Wireless Adapter                               | 1        | 1.06%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter              | 1        | 1.06%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                | 1        | 1.06%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 1.06%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]    | 1        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 1.06%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 1.06%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 63       | 44.68%  |
| Realtek Semiconductor    | 60       | 42.55%  |
| Samsung Electronics      | 5        | 3.55%   |
| Broadcom                 | 5        | 3.55%   |
| Xiaomi                   | 1        | 0.71%   |
| VIA Technologies         | 1        | 0.71%   |
| T & A Mobile Phones      | 1        | 0.71%   |
| Qualcomm Atheros         | 1        | 0.71%   |
| Marvell Technology Group | 1        | 0.71%   |
| Huawei Technologies      | 1        | 0.71%   |
| DisplayLink              | 1        | 0.71%   |
| Apple                    | 1        | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 47       | 31.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11       | 7.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 6.8%    |
| Intel I211 Gigabit Network Connection                                  | 7        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 7        | 4.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 4.08%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5        | 3.4%    |
| Intel Ethernet Controller I225-V                                       | 5        | 3.4%    |
| Intel Ethernet Connection I217-LM                                      | 5        | 3.4%    |
| Intel Ethernet Connection (2) I218-V                                   | 5        | 3.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.36%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 1.36%   |
| Intel 82583V Gigabit Network Connection                                | 2        | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2        | 1.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.68%   |
| T & A Mobile Phones Alcatel 1S                                         | 1        | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.68%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.68%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.68%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 1        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.68%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 0.68%   |
| Intel Ethernet Connection (12) I219-V                                  | 1        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.68%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 0.68%   |
| Intel 82567V-2 Gigabit Network Connection                              | 1        | 0.68%   |
| Huawei VTR-L09                                                         | 1        | 0.68%   |
| DisplayLink Dell D3100 Docking Station                                 | 1        | 0.68%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 60.85%  |
| WiFi     | 82       | 38.68%  |
| Modem    | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 67.14%  |
| WiFi     | 46       | 32.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 58.02%  |
| 2     | 51       | 38.93%  |
| 4     | 2        | 1.53%   |
| 3     | 2        | 1.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 83       | 61.03%  |
| Yes  | 53       | 38.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 28       | 46.67%  |
| Cambridge Silicon Radio | 19       | 31.67%  |
| TP-Link                 | 3        | 5%      |
| Realtek Semiconductor   | 2        | 3.33%   |
| MediaTek                | 2        | 3.33%   |
| ASUSTek Computer        | 2        | 3.33%   |
| SiW                     | 1        | 1.67%   |
| IMC Networks            | 1        | 1.67%   |
| Foxconn / Hon Hai       | 1        | 1.67%   |
| Broadcom                | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 19       | 31.67%  |
| Intel AX200 Bluetooth                                 | 12       | 20%     |
| Intel Bluetooth wireless interface                    | 5        | 8.33%   |
| Intel AX201 Bluetooth                                 | 4        | 6.67%   |
| TP-Link UB500 Adapter                                 | 3        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 5%      |
| MediaTek Wireless_Device                              | 2        | 3.33%   |
| SiW SiW                                               | 1        | 1.67%   |
| Realtek Bluetooth Radio                               | 1        | 1.67%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 1.67%   |
| Intel Bluetooth Device                                | 1        | 1.67%   |
| Intel AX211 Bluetooth                                 | 1        | 1.67%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 1.67%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.67%   |
| ASUS Bluetooth Device                                 | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 105      | 45.65%  |
| Nvidia                   | 60       | 26.09%  |
| AMD                      | 35       | 15.22%  |
| C-Media Electronics      | 11       | 4.78%   |
| Kingston Technology      | 3        | 1.3%    |
| Creative Labs            | 3        | 1.3%    |
| Tenx Technology          | 2        | 0.87%   |
| VIA Technologies         | 1        | 0.43%   |
| Texas Instruments        | 1        | 0.43%   |
| Plantronics              | 1        | 0.43%   |
| Micro Star International | 1        | 0.43%   |
| Logitech                 | 1        | 0.43%   |
| JMTek                    | 1        | 0.43%   |
| GYROCOM C&C              | 1        | 0.43%   |
| DCMT Technology          | 1        | 0.43%   |
| Creative Technology      | 1        | 0.43%   |
| Corsair                  | 1        | 0.43%   |
| Cooler Master            | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH HD Audio                                              | 15       | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 5.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 4.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 3.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 5        | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.94%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5        | 1.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 1.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.55%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.55%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.55%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 1.55%   |
| C-Media Electronics CM108 Audio Controller                                 | 4        | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 1.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 1.55%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.16%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.16%   |
| Nvidia Audio device                                                        | 3        | 1.16%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.16%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.16%   |
| Tenx Technology TP6911 Audio Headset                                       | 2        | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Kingston              | 15       | 20.55%  |
| SK hynix              | 8        | 10.96%  |
| Samsung Electronics   | 8        | 10.96%  |
| G.Skill               | 8        | 10.96%  |
| Micron Technology     | 7        | 9.59%   |
| Unknown               | 6        | 8.22%   |
| Team                  | 5        | 6.85%   |
| Corsair               | 4        | 5.48%   |
| Crucial               | 3        | 4.11%   |
| Hikvision             | 2        | 2.74%   |
| Unknown (ABCD)        | 1        | 1.37%   |
| Nanya Technology      | 1        | 1.37%   |
| Lexar Co Limited      | 1        | 1.37%   |
| Kingmax Semiconductor | 1        | 1.37%   |
| Elpida                | 1        | 1.37%   |
| D3860000              | 1        | 1.37%   |
| A-DATA Technology     | 1        | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 3        | 3.95%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s               | 2        | 2.63%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s             | 2        | 2.63%   |
| Micron RAM Module 4GB DIMM DDR3 1333MT/s                         | 2        | 2.63%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s            | 2        | 2.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 1.32%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1        | 1.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1        | 1.32%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1        | 1.32%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1        | 1.32%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 1        | 1.32%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1        | 1.32%   |
| Team RAM UD5-5600 16GB DIMM DDR5 12800MT/s                       | 1        | 1.32%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1        | 1.32%   |
| Team RAM Dark-1600 8GB DIMM DDR3 1600MT/s                        | 1        | 1.32%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1        | 1.32%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s             | 1        | 1.32%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1600MT/s             | 1        | 1.32%   |
| SK hynix RAM HMA851U6DJR6N-XN 4GB DIMM DDR4 3200MT/s             | 1        | 1.32%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s             | 1        | 1.32%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s             | 1        | 1.32%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                        | 1        | 1.32%   |
| Samsung RAM M393B1K70DH0-CK0 8192MB DIMM DDR3 1333MT/s           | 1        | 1.32%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s              | 1        | 1.32%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 1.32%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 1.32%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 1.32%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s             | 1        | 1.32%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s             | 1        | 1.32%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s               | 1        | 1.32%   |
| Micron RAM ITC 4GB DIMM DDR3 1648MT/s                            | 1        | 1.32%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s              | 1        | 1.32%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1        | 1.32%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s              | 1        | 1.32%   |
| Micron RAM 36JSF1G72PZ-1G6K1 8GB DIMM DDR3 1333MT/s              | 1        | 1.32%   |
| Lexar Co Limited RAM LD4AS008G-H3200GST 8GB SODIMM DDR4 3200MT/s | 1        | 1.32%   |
| Kingston RAM KHX3733C19D4/8GX 8GB DIMM DDR4 3600MT/s             | 1        | 1.32%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s             | 1        | 1.32%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 1        | 1.32%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s             | 1        | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 50%     |
| DDR3    | 21       | 36.21%  |
| Unknown | 3        | 5.17%   |
| DDR5    | 2        | 3.45%   |
| SDRAM   | 1        | 1.72%   |
| LPDDR4  | 1        | 1.72%   |
| DDR2    | 1        | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 52       | 91.23%  |
| SODIMM | 5        | 8.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 24       | 40%     |
| 4096  | 14       | 23.33%  |
| 16384 | 13       | 21.67%  |
| 2048  | 5        | 8.33%   |
| 32768 | 3        | 5%      |
| 1024  | 1        | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 16.67%  |
| 3200  | 10       | 15.15%  |
| 1333  | 9        | 13.64%  |
| 3600  | 5        | 7.58%   |
| 2667  | 5        | 7.58%   |
| 2133  | 4        | 6.06%   |
| 2400  | 3        | 4.55%   |
| 1800  | 3        | 4.55%   |
| 1867  | 2        | 3.03%   |
| 1866  | 2        | 3.03%   |
| 800   | 2        | 3.03%   |
| 12800 | 1        | 1.52%   |
| 4800  | 1        | 1.52%   |
| 3866  | 1        | 1.52%   |
| 3733  | 1        | 1.52%   |
| 3466  | 1        | 1.52%   |
| 3400  | 1        | 1.52%   |
| 3066  | 1        | 1.52%   |
| 2933  | 1        | 1.52%   |
| 1648  | 1        | 1.52%   |
| 667   | 1        | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 7        | 70%     |
| Brother Industries     | 2        | 20%     |
| Panasonic (Matsushita) | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Brother HL-2130 series             | 2        | 18.18%  |
| Panasonic (Matsushita) KX-MB1500RU | 1        | 9.09%   |
| HP LaserJet P2055 series           | 1        | 9.09%   |
| HP LaserJet P2015 series           | 1        | 9.09%   |
| HP LaserJet M101-M106              | 1        | 9.09%   |
| HP LaserJet CP 1025nw              | 1        | 9.09%   |
| HP LaserJet 400 M401dne            | 1        | 9.09%   |
| HP LaserJet 1020                   | 1        | 9.09%   |
| HP DeskJet 2700 series             | 1        | 9.09%   |
| HP DeskJet 2130 series             | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 500F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microsoft                     | 5        | 35.71%  |
| Sunplus Innovation Technology | 2        | 14.29%  |
| ARC International             | 2        | 14.29%  |
| Apple                         | 2        | 14.29%  |
| Z-Star Microelectronics       | 1        | 7.14%   |
| Samsung Electronics           | 1        | 7.14%   |
| Arkmicro Technologies         | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ARC International Camera                | 2        | 14.29%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 2        | 14.29%  |
| Z-Star Integrated Camera                | 1        | 7.14%   |
| Sunplus Lihappe8 Webcam L0485A2SP       | 1        | 7.14%   |
| Sunplus Integrated_Webcam_HD            | 1        | 7.14%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.14%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 1        | 7.14%   |
| Microsoft LifeCam VX-800                | 1        | 7.14%   |
| Microsoft LifeCam HD-5000               | 1        | 7.14%   |
| Microsoft LifeCam HD-3000               | 1        | 7.14%   |
| Microsoft LifeCam Cinema                | 1        | 7.14%   |
| Arkmicro USB2.0 PC CAMERA               | 1        | 7.14%   |

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
| 0     | 109      | 80.15%  |
| 1     | 24       | 17.65%  |
| 2     | 3        | 2.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 41.38%  |
| Graphics card            | 8        | 27.59%  |
| Unassigned class         | 4        | 13.79%  |
| Communication controller | 3        | 10.34%  |
| Storage/raid             | 1        | 3.45%   |
| Camera                   | 1        | 3.45%   |

